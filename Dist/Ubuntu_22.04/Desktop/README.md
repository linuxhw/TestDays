Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 3595

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z170-A                      | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [48e150f274](https://linux-hardware.org/?probe=48e150f274) | Feb 28, 2023 |
| ASRockRack    | E3C246D4U2-2T               | [1ad2cb5102](https://linux-hardware.org/?probe=1ad2cb5102) | Feb 28, 2023 |
| ASRock        | KBL-NUC                     | [cb504c5fa0](https://linux-hardware.org/?probe=cb504c5fa0) | Feb 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [64b2c8d5b9](https://linux-hardware.org/?probe=64b2c8d5b9) | Feb 28, 2023 |
| ASUSTek       | PRIME X570-P                | [dda5eec4b9](https://linux-hardware.org/?probe=dda5eec4b9) | Feb 28, 2023 |
| Lenovo        | 3102 NOK                    | [17a2e663e1](https://linux-hardware.org/?probe=17a2e663e1) | Feb 28, 2023 |
| Lenovo        | 3102 NOK                    | [6dabaffa28](https://linux-hardware.org/?probe=6dabaffa28) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [aefca0b663](https://linux-hardware.org/?probe=aefca0b663) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [12ccf2fe8b](https://linux-hardware.org/?probe=12ccf2fe8b) | Feb 28, 2023 |
| Dell          | 0HD5W2 A01                  | [f30a31a8ee](https://linux-hardware.org/?probe=f30a31a8ee) | Feb 28, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [cb687f4572](https://linux-hardware.org/?probe=cb687f4572) | Feb 28, 2023 |
| Acer          | TDPS05                      | [c4a636fb79](https://linux-hardware.org/?probe=c4a636fb79) | Feb 28, 2023 |
| Acer          | TDPS05                      | [114e21597f](https://linux-hardware.org/?probe=114e21597f) | Feb 28, 2023 |
| ASUSTek       | PRIME B360M-A               | [5860f51cd8](https://linux-hardware.org/?probe=5860f51cd8) | Feb 27, 2023 |
| Gigabyte      | EX58-UD5                    | [eaec9511de](https://linux-hardware.org/?probe=eaec9511de) | Feb 27, 2023 |
| HP            | 339A                        | [308d8dfac0](https://linux-hardware.org/?probe=308d8dfac0) | Feb 27, 2023 |
| Casper        | H510 001 G10a               | [95a9cfbf0b](https://linux-hardware.org/?probe=95a9cfbf0b) | Feb 27, 2023 |
| Gigabyte      | A320M-H-CF                  | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| Gigabyte      | H110M-S2V-CF                | [509c2a6e57](https://linux-hardware.org/?probe=509c2a6e57) | Feb 27, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [686c8d56c4](https://linux-hardware.org/?probe=686c8d56c4) | Feb 27, 2023 |
| ASRock        | A320M-HDV R4.0              | [37d2aab670](https://linux-hardware.org/?probe=37d2aab670) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [49f3238d4a](https://linux-hardware.org/?probe=49f3238d4a) | Feb 26, 2023 |
| HP            | 81B4 01                     | [bc06df8d32](https://linux-hardware.org/?probe=bc06df8d32) | Feb 26, 2023 |
| Gigabyte      | Z390 UD                     | [b40f9ce0d1](https://linux-hardware.org/?probe=b40f9ce0d1) | Feb 26, 2023 |
| MSI           | B450M PRO-M2 MAX            | [0c5f9a10dd](https://linux-hardware.org/?probe=0c5f9a10dd) | Feb 26, 2023 |
| Pegatron      | NARRA5                      | [fbff48e326](https://linux-hardware.org/?probe=fbff48e326) | Feb 26, 2023 |
| Lenovo        | Annapurna CRB NOK           | [77122f785f](https://linux-hardware.org/?probe=77122f785f) | Feb 26, 2023 |
| Lenovo        | Annapurna CRB NOK           | [0e521e12aa](https://linux-hardware.org/?probe=0e521e12aa) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | [4cd492ee3e](https://linux-hardware.org/?probe=4cd492ee3e) | Feb 26, 2023 |
| ASRock        | B85 Pro4                    | [0b4daba4fb](https://linux-hardware.org/?probe=0b4daba4fb) | Feb 26, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [49b1cd5754](https://linux-hardware.org/?probe=49b1cd5754) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | [9471b0f763](https://linux-hardware.org/?probe=9471b0f763) | Feb 26, 2023 |
| Gigabyte      | B560M DS3H V2               | [31f6d9e11d](https://linux-hardware.org/?probe=31f6d9e11d) | Feb 26, 2023 |
| Dell          | 0WMJ54 A01                  | [f9cae700c7](https://linux-hardware.org/?probe=f9cae700c7) | Feb 26, 2023 |
| HP            | 1632                        | [394b988862](https://linux-hardware.org/?probe=394b988862) | Feb 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [f24a3027d0](https://linux-hardware.org/?probe=f24a3027d0) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Dell          | 0HR330                      | [9110acd156](https://linux-hardware.org/?probe=9110acd156) | Feb 26, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | [f56bb767fd](https://linux-hardware.org/?probe=f56bb767fd) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | [98e70b4028](https://linux-hardware.org/?probe=98e70b4028) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| Dell          | 0F428D A00                  | [7d01f8893e](https://linux-hardware.org/?probe=7d01f8893e) | Feb 25, 2023 |
| ASRock        | Z97 Pro4                    | [451c626830](https://linux-hardware.org/?probe=451c626830) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [336a7cad31](https://linux-hardware.org/?probe=336a7cad31) | Feb 25, 2023 |
| eMachines     | EL1850                      | [81741a438a](https://linux-hardware.org/?probe=81741a438a) | Feb 25, 2023 |
| HP            | 3398                        | [5e7ae4c866](https://linux-hardware.org/?probe=5e7ae4c866) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [0620aa7f6f](https://linux-hardware.org/?probe=0620aa7f6f) | Feb 25, 2023 |
| Gigabyte      | B550M DS3H                  | [0ac3b49261](https://linux-hardware.org/?probe=0ac3b49261) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [30afdb56c5](https://linux-hardware.org/?probe=30afdb56c5) | Feb 25, 2023 |
| Protectli     | VP2420                      | [ea5f851cf3](https://linux-hardware.org/?probe=ea5f851cf3) | Feb 25, 2023 |
| Quanta        | 2AC7 011                    | [3505fadb68](https://linux-hardware.org/?probe=3505fadb68) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfa5623f15](https://linux-hardware.org/?probe=bfa5623f15) | Feb 25, 2023 |
| Acer          | Aspire X3990                | [c83e31d66b](https://linux-hardware.org/?probe=c83e31d66b) | Feb 25, 2023 |
| Acer          | Aspire X3990                | [4be9f68049](https://linux-hardware.org/?probe=4be9f68049) | Feb 25, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [7864921f8d](https://linux-hardware.org/?probe=7864921f8d) | Feb 25, 2023 |
| Dell          | 051FJ8 A02                  | [05f5f23fbb](https://linux-hardware.org/?probe=05f5f23fbb) | Feb 25, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [d78e737aaf](https://linux-hardware.org/?probe=d78e737aaf) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [df734c276f](https://linux-hardware.org/?probe=df734c276f) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [3f931a7600](https://linux-hardware.org/?probe=3f931a7600) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | [99b5c2f7f9](https://linux-hardware.org/?probe=99b5c2f7f9) | Feb 24, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | [0bb7bc3713](https://linux-hardware.org/?probe=0bb7bc3713) | Feb 24, 2023 |
| ASUSTek       | PRIME B360M-A               | [6d7221488b](https://linux-hardware.org/?probe=6d7221488b) | Feb 24, 2023 |
| Pegatron      | NARRA5                      | [af6be34173](https://linux-hardware.org/?probe=af6be34173) | Feb 24, 2023 |
| MSI           | K9N6PGM2-V2                 | [e88df81d6f](https://linux-hardware.org/?probe=e88df81d6f) | Feb 24, 2023 |
| HP            | 8433 11                     | [e8663b2a0c](https://linux-hardware.org/?probe=e8663b2a0c) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | [f4e2bfd7a0](https://linux-hardware.org/?probe=f4e2bfd7a0) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [916f372721](https://linux-hardware.org/?probe=916f372721) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [6e82a5c5d6](https://linux-hardware.org/?probe=6e82a5c5d6) | Feb 24, 2023 |
| ASRock        | B550M-C                     | [96edee86aa](https://linux-hardware.org/?probe=96edee86aa) | Feb 24, 2023 |
| ASRock        | B550M-C                     | [454c89b4eb](https://linux-hardware.org/?probe=454c89b4eb) | Feb 24, 2023 |
| Pegatron      | NARRA5                      | [ca884f817b](https://linux-hardware.org/?probe=ca884f817b) | Feb 24, 2023 |
| ASUSTek       | Q87M-E                      | [e31da94f7b](https://linux-hardware.org/?probe=e31da94f7b) | Feb 24, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [a458effa12](https://linux-hardware.org/?probe=a458effa12) | Feb 24, 2023 |
| ASUSTek       | PRIME B460M-A R2.0          | [0ccac8edb4](https://linux-hardware.org/?probe=0ccac8edb4) | Feb 24, 2023 |
| ASRock        | H510M/ac                    | [b7d570e46c](https://linux-hardware.org/?probe=b7d570e46c) | Feb 24, 2023 |
| Dell          | 0M5DCD A00                  | [88b0bf49fd](https://linux-hardware.org/?probe=88b0bf49fd) | Feb 24, 2023 |
| Dell          | 0MWYPT A02                  | [2491b0e5eb](https://linux-hardware.org/?probe=2491b0e5eb) | Feb 23, 2023 |
| HP            | 8433 11                     | [9aa13c1fa5](https://linux-hardware.org/?probe=9aa13c1fa5) | Feb 23, 2023 |
| Gigabyte      | Z390 UD                     | [5a6ab06c02](https://linux-hardware.org/?probe=5a6ab06c02) | Feb 23, 2023 |
| ASUSTek       | P5K                         | [2fb7f1713b](https://linux-hardware.org/?probe=2fb7f1713b) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6bdb8ada9c](https://linux-hardware.org/?probe=6bdb8ada9c) | Feb 23, 2023 |
| ASUSTek       | Maximus VI HERO             | [16618052ef](https://linux-hardware.org/?probe=16618052ef) | Feb 23, 2023 |
| ASUSTek       | B85M-E                      | [8a09d5e812](https://linux-hardware.org/?probe=8a09d5e812) | Feb 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [00e573a880](https://linux-hardware.org/?probe=00e573a880) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| Dell          | 0WG855                      | [49c149cff7](https://linux-hardware.org/?probe=49c149cff7) | Feb 23, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [7b27b03f4a](https://linux-hardware.org/?probe=7b27b03f4a) | Feb 23, 2023 |
| T-bao         | MINI PC                     | [68ba9fc610](https://linux-hardware.org/?probe=68ba9fc610) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [e0687d11bb](https://linux-hardware.org/?probe=e0687d11bb) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [49e71eb5b4](https://linux-hardware.org/?probe=49e71eb5b4) | Feb 22, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ce8874cff4](https://linux-hardware.org/?probe=ce8874cff4) | Feb 22, 2023 |
| MSI           | B350 TOMAHAWK               | [71aa647a28](https://linux-hardware.org/?probe=71aa647a28) | Feb 22, 2023 |
| ASRock        | B450 Pro4                   | [87600137b2](https://linux-hardware.org/?probe=87600137b2) | Feb 22, 2023 |
| ASUSTek       | PRO H410M-C                 | [d6edc5401d](https://linux-hardware.org/?probe=d6edc5401d) | Feb 22, 2023 |
| MSI           | B550-A PRO                  | [11d4db7a00](https://linux-hardware.org/?probe=11d4db7a00) | Feb 22, 2023 |
| ASUSTek       | Maximus VI HERO             | [754e37e18d](https://linux-hardware.org/?probe=754e37e18d) | Feb 22, 2023 |
| Unknown       | 1.0                         | [b7475435a7](https://linux-hardware.org/?probe=b7475435a7) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | [3362226081](https://linux-hardware.org/?probe=3362226081) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | [8230de4836](https://linux-hardware.org/?probe=8230de4836) | Feb 22, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [adc8d2fb16](https://linux-hardware.org/?probe=adc8d2fb16) | Feb 22, 2023 |
| MSI           | MEG X570 UNIFY              | [edc30b8a22](https://linux-hardware.org/?probe=edc30b8a22) | Feb 22, 2023 |
| Acer          | Aspire TC-605               | [7234bd12f6](https://linux-hardware.org/?probe=7234bd12f6) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| Gigabyte      | EP43-UD3L                   | [52c293dde6](https://linux-hardware.org/?probe=52c293dde6) | Feb 21, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6b883f967d](https://linux-hardware.org/?probe=6b883f967d) | Feb 21, 2023 |
| Gigabyte      | B365M DS3H                  | [8049beda96](https://linux-hardware.org/?probe=8049beda96) | Feb 21, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [d9a5611225](https://linux-hardware.org/?probe=d9a5611225) | Feb 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [50261acb6b](https://linux-hardware.org/?probe=50261acb6b) | Feb 21, 2023 |
| Dell          | 0HY9JP A01                  | [8c1473e111](https://linux-hardware.org/?probe=8c1473e111) | Feb 21, 2023 |
| MSI           | B550 GAMING GEN3            | [d92a4239ee](https://linux-hardware.org/?probe=d92a4239ee) | Feb 21, 2023 |
| HP            | 18E7                        | [913411cd18](https://linux-hardware.org/?probe=913411cd18) | Feb 21, 2023 |
| Acer          | Aspire X1935                | [8c4f88db47](https://linux-hardware.org/?probe=8c4f88db47) | Feb 21, 2023 |
| Dell          | 0CK520 A01                  | [6e92aa0096](https://linux-hardware.org/?probe=6e92aa0096) | Feb 20, 2023 |
| ASUSTek       | H170-PRO                    | [011dc701c1](https://linux-hardware.org/?probe=011dc701c1) | Feb 20, 2023 |
| Alienware     | 07W25T A01                  | [0ce3af1e23](https://linux-hardware.org/?probe=0ce3af1e23) | Feb 20, 2023 |
| Alienware     | 07W25T A01                  | [f965f4658b](https://linux-hardware.org/?probe=f965f4658b) | Feb 20, 2023 |
| Dell          | 0H4VK7 A01                  | [19ded2f15b](https://linux-hardware.org/?probe=19ded2f15b) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | [796ba78b54](https://linux-hardware.org/?probe=796ba78b54) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [04130aaf41](https://linux-hardware.org/?probe=04130aaf41) | Feb 20, 2023 |
| Supermicro    | X10DRiB                     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| ASRock        | H61M-DGS R2.0               | [3d8b32f453](https://linux-hardware.org/?probe=3d8b32f453) | Feb 20, 2023 |
| AZW           | GK mini                     | [6fc9af1346](https://linux-hardware.org/?probe=6fc9af1346) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a47920e014](https://linux-hardware.org/?probe=a47920e014) | Feb 20, 2023 |
| Dell          | 0WMJ54 A01                  | [59ce46dfe2](https://linux-hardware.org/?probe=59ce46dfe2) | Feb 20, 2023 |
| Pegatron      | NARRA5                      | [6d0714a928](https://linux-hardware.org/?probe=6d0714a928) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| HP            | 18E7                        | [c59f4fb1ab](https://linux-hardware.org/?probe=c59f4fb1ab) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| ASRock        | H81M-HDS R2.0               | [32b47345a6](https://linux-hardware.org/?probe=32b47345a6) | Feb 20, 2023 |
| Dell          | 0D24M8 A02                  | [a9e9dae786](https://linux-hardware.org/?probe=a9e9dae786) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8ab5bffea6](https://linux-hardware.org/?probe=8ab5bffea6) | Feb 19, 2023 |
| ASUSTek       | H81M-PLUS                   | [86f16da5e8](https://linux-hardware.org/?probe=86f16da5e8) | Feb 19, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [fccba081d1](https://linux-hardware.org/?probe=fccba081d1) | Feb 19, 2023 |
| HP            | 18E5                        | [ba623dea72](https://linux-hardware.org/?probe=ba623dea72) | Feb 19, 2023 |
| Partner       | S1-J1900                    | [0dd4327553](https://linux-hardware.org/?probe=0dd4327553) | Feb 19, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [8c8ae38704](https://linux-hardware.org/?probe=8c8ae38704) | Feb 19, 2023 |
| HP            | 0AECh D                     | [e844a614ec](https://linux-hardware.org/?probe=e844a614ec) | Feb 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [e7e9625ffc](https://linux-hardware.org/?probe=e7e9625ffc) | Feb 19, 2023 |
| MSI           | B450 TOMAHAWK               | [50b693cc98](https://linux-hardware.org/?probe=50b693cc98) | Feb 19, 2023 |
| ASRock        | 870 Extreme3 R2.0           | [68c2299161](https://linux-hardware.org/?probe=68c2299161) | Feb 19, 2023 |
| Medion        | H110H4-EM                   | [71da47e860](https://linux-hardware.org/?probe=71da47e860) | Feb 19, 2023 |
| HP            | 339A                        | [07001c3589](https://linux-hardware.org/?probe=07001c3589) | Feb 19, 2023 |
| HP            | 339A                        | [0d7bb8b04a](https://linux-hardware.org/?probe=0d7bb8b04a) | Feb 19, 2023 |
| ASRock        | X99 Extreme4                | [cbfb58fc3c](https://linux-hardware.org/?probe=cbfb58fc3c) | Feb 19, 2023 |
| ASUSTek       | A78M-E                      | [3b2adbff33](https://linux-hardware.org/?probe=3b2adbff33) | Feb 18, 2023 |
| HP            | 1905                        | [abc0c09cdf](https://linux-hardware.org/?probe=abc0c09cdf) | Feb 18, 2023 |
| Gigabyte      | X79-UD3                     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Dell          | 0PY127 A02                  | [2be7133f11](https://linux-hardware.org/?probe=2be7133f11) | Feb 18, 2023 |
| MSI           | B75A-G43                    | [bf426ce3c3](https://linux-hardware.org/?probe=bf426ce3c3) | Feb 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [105ea39c82](https://linux-hardware.org/?probe=105ea39c82) | Feb 18, 2023 |
| Dell          | 0PU052                      | [a460806b91](https://linux-hardware.org/?probe=a460806b91) | Feb 18, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [28965259ad](https://linux-hardware.org/?probe=28965259ad) | Feb 18, 2023 |
| Gateway       | IPISB-VR                    | [f67f11a59e](https://linux-hardware.org/?probe=f67f11a59e) | Feb 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [8a8696cdb1](https://linux-hardware.org/?probe=8a8696cdb1) | Feb 18, 2023 |
| ASRock        | H510M/ac                    | [ab77c84805](https://linux-hardware.org/?probe=ab77c84805) | Feb 18, 2023 |
| HP            | 8299                        | [458683cdc0](https://linux-hardware.org/?probe=458683cdc0) | Feb 18, 2023 |
| Dell          | 0WMJ54 A01                  | [c154817077](https://linux-hardware.org/?probe=c154817077) | Feb 18, 2023 |
| Dell          | 0C2XKD A01                  | [5fcdbd2986](https://linux-hardware.org/?probe=5fcdbd2986) | Feb 18, 2023 |
| Dell          | 0C2XKD A01                  | [6d786baedd](https://linux-hardware.org/?probe=6d786baedd) | Feb 18, 2023 |
| Alienware     | 07W25T A01                  | [f9427f609d](https://linux-hardware.org/?probe=f9427f609d) | Feb 17, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [b01f6d7a1f](https://linux-hardware.org/?probe=b01f6d7a1f) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [9f6834d4a9](https://linux-hardware.org/?probe=9f6834d4a9) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [131f8f99a2](https://linux-hardware.org/?probe=131f8f99a2) | Feb 17, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [6f0e4158a4](https://linux-hardware.org/?probe=6f0e4158a4) | Feb 17, 2023 |
| Casper        | H510 001 G10a               | [56402bade6](https://linux-hardware.org/?probe=56402bade6) | Feb 17, 2023 |
| IP3 Tech      | Cherry Trail CR             | [0ff2dc2202](https://linux-hardware.org/?probe=0ff2dc2202) | Feb 17, 2023 |
| Intel         | DH77DF AAG40293-301         | [f44579d8b4](https://linux-hardware.org/?probe=f44579d8b4) | Feb 17, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [271ad0ffe2](https://linux-hardware.org/?probe=271ad0ffe2) | Feb 17, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [fa1e14d3d5](https://linux-hardware.org/?probe=fa1e14d3d5) | Feb 17, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [b6217420cc](https://linux-hardware.org/?probe=b6217420cc) | Feb 17, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [b9c30fbaf8](https://linux-hardware.org/?probe=b9c30fbaf8) | Feb 17, 2023 |
| MSI           | B350 TOMAHAWK               | [de9c98193e](https://linux-hardware.org/?probe=de9c98193e) | Feb 17, 2023 |
| Gigabyte      | H81M-S2H                    | [db4fef5830](https://linux-hardware.org/?probe=db4fef5830) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8fa990093e](https://linux-hardware.org/?probe=8fa990093e) | Feb 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [9cd5183878](https://linux-hardware.org/?probe=9cd5183878) | Feb 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [7e44f9e4ff](https://linux-hardware.org/?probe=7e44f9e4ff) | Feb 17, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [01355a0714](https://linux-hardware.org/?probe=01355a0714) | Feb 17, 2023 |
| ASRock        | B360M Xtreme                | [0804d226b0](https://linux-hardware.org/?probe=0804d226b0) | Feb 17, 2023 |
| Dell          | 0C27VV A04                  | [581f38496e](https://linux-hardware.org/?probe=581f38496e) | Feb 17, 2023 |
| HP            | 82A2                        | [16aeaa4b92](https://linux-hardware.org/?probe=16aeaa4b92) | Feb 17, 2023 |
| MSI           | 890FXA-GD65                 | [f52cfe6e0d](https://linux-hardware.org/?probe=f52cfe6e0d) | Feb 17, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [00568fe98a](https://linux-hardware.org/?probe=00568fe98a) | Feb 17, 2023 |
| Biostar       | G41U3G                      | [9d534d5d74](https://linux-hardware.org/?probe=9d534d5d74) | Feb 16, 2023 |
| DIEBOLD       | H55H-CM                     | [fdfc5c5e92](https://linux-hardware.org/?probe=fdfc5c5e92) | Feb 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [7603784fce](https://linux-hardware.org/?probe=7603784fce) | Feb 16, 2023 |
| ASRock        | Q1900M                      | [2fc7d5968a](https://linux-hardware.org/?probe=2fc7d5968a) | Feb 16, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [7dfab1047b](https://linux-hardware.org/?probe=7dfab1047b) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d9b6d0ba02](https://linux-hardware.org/?probe=d9b6d0ba02) | Feb 16, 2023 |
| MSI           | Z97 GAMING 5                | [e29c56eb10](https://linux-hardware.org/?probe=e29c56eb10) | Feb 15, 2023 |
| HP            | 870C                        | [76ae5c62cf](https://linux-hardware.org/?probe=76ae5c62cf) | Feb 15, 2023 |
| Acer          | Veriton X2610G              | [22c65bbb88](https://linux-hardware.org/?probe=22c65bbb88) | Feb 15, 2023 |
| Supermicro    | X7DCL                       | [49e545591c](https://linux-hardware.org/?probe=49e545591c) | Feb 15, 2023 |
| ASUSTek       | Z170-PRO                    | [bd408485b0](https://linux-hardware.org/?probe=bd408485b0) | Feb 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f91712ea02](https://linux-hardware.org/?probe=f91712ea02) | Feb 15, 2023 |
| Biostar       | B450MH                      | [34591a7516](https://linux-hardware.org/?probe=34591a7516) | Feb 15, 2023 |
| Biostar       | B450MH                      | [12142a9f86](https://linux-hardware.org/?probe=12142a9f86) | Feb 15, 2023 |
| ASRock        | Z75 Pro3                    | [7ffb26b7dd](https://linux-hardware.org/?probe=7ffb26b7dd) | Feb 15, 2023 |
| Dell          | 0WMJ54 A01                  | [5ebabab1c5](https://linux-hardware.org/?probe=5ebabab1c5) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | [a401dfe086](https://linux-hardware.org/?probe=a401dfe086) | Feb 14, 2023 |
| ASRock        | Z77 Extreme6/TB4            | [cbcb53dec3](https://linux-hardware.org/?probe=cbcb53dec3) | Feb 14, 2023 |
| ASUSTek       | H110M-A                     | [d2d359be39](https://linux-hardware.org/?probe=d2d359be39) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | [5fefbd2419](https://linux-hardware.org/?probe=5fefbd2419) | Feb 14, 2023 |
| ASRock        | H510M/ac                    | [73161b2a1e](https://linux-hardware.org/?probe=73161b2a1e) | Feb 14, 2023 |
| Gigabyte      | H310M S2 x.x                | [0206821577](https://linux-hardware.org/?probe=0206821577) | Feb 14, 2023 |
| Gigabyte      | H310M S2 x.x                | [fcbd0e4770](https://linux-hardware.org/?probe=fcbd0e4770) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [4785d6d596](https://linux-hardware.org/?probe=4785d6d596) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [60794bd7c3](https://linux-hardware.org/?probe=60794bd7c3) | Feb 14, 2023 |
| HP            | 18E7                        | [b81cc64550](https://linux-hardware.org/?probe=b81cc64550) | Feb 14, 2023 |
| Dell          | 0GXM1W A01                  | [b79a508ddd](https://linux-hardware.org/?probe=b79a508ddd) | Feb 14, 2023 |
| ASUSTek       | Maximus VII HERO            | [ef3ee2ebf2](https://linux-hardware.org/?probe=ef3ee2ebf2) | Feb 14, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [39564bbf72](https://linux-hardware.org/?probe=39564bbf72) | Feb 13, 2023 |
| Alienware     | 07JNH0 A02                  | [0be6f8fe33](https://linux-hardware.org/?probe=0be6f8fe33) | Feb 13, 2023 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | [24d20958ab](https://linux-hardware.org/?probe=24d20958ab) | Feb 13, 2023 |
| ASUSTek       | Maximus VII HERO            | [cdd9011e76](https://linux-hardware.org/?probe=cdd9011e76) | Feb 13, 2023 |
| ASRock        | H310CM-HDV/M.2              | [dd433b9dcf](https://linux-hardware.org/?probe=dd433b9dcf) | Feb 13, 2023 |
| Medion        | Cattle24 1M                 | [2a14385869](https://linux-hardware.org/?probe=2a14385869) | Feb 13, 2023 |
| Foxconn       | 2ABF                        | [2573ae3149](https://linux-hardware.org/?probe=2573ae3149) | Feb 13, 2023 |
| Gigabyte      | Z77M-D3H                    | [6d428a3fb9](https://linux-hardware.org/?probe=6d428a3fb9) | Feb 13, 2023 |
| ASUSTek       | M5A88-M                     | [e4b1d6656b](https://linux-hardware.org/?probe=e4b1d6656b) | Feb 13, 2023 |
| Gigabyte      | H81M-S2H                    | [7458415afe](https://linux-hardware.org/?probe=7458415afe) | Feb 13, 2023 |
| Lenovo        | NOK                         | [f2fdf17bc6](https://linux-hardware.org/?probe=f2fdf17bc6) | Feb 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [f406efb6bb](https://linux-hardware.org/?probe=f406efb6bb) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c7d5effbbc](https://linux-hardware.org/?probe=c7d5effbbc) | Feb 13, 2023 |
| Gigabyte      | H55-UD3H                    | [0d0c742e0e](https://linux-hardware.org/?probe=0d0c742e0e) | Feb 12, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [d7316db223](https://linux-hardware.org/?probe=d7316db223) | Feb 12, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [4863b5361f](https://linux-hardware.org/?probe=4863b5361f) | Feb 12, 2023 |
| Gigabyte      | H110M-S2HP-CF               | [928f0b0e2e](https://linux-hardware.org/?probe=928f0b0e2e) | Feb 12, 2023 |
| ASRock        | Z370M Pro4                  | [6dfaa1ed56](https://linux-hardware.org/?probe=6dfaa1ed56) | Feb 12, 2023 |
| Gigabyte      | B75M-D3H                    | [954221ff64](https://linux-hardware.org/?probe=954221ff64) | Feb 12, 2023 |
| MSI           | 970A-G43                    | [06cc8e9889](https://linux-hardware.org/?probe=06cc8e9889) | Feb 12, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [68db95ee9b](https://linux-hardware.org/?probe=68db95ee9b) | Feb 12, 2023 |
| ASUSTek       | F2A55-M LK2                 | [01ab687841](https://linux-hardware.org/?probe=01ab687841) | Feb 12, 2023 |
| Lenovo        | 4030                        | [a0052fd936](https://linux-hardware.org/?probe=a0052fd936) | Feb 12, 2023 |
| Acer          | H57M01                      | [4efe549cf2](https://linux-hardware.org/?probe=4efe549cf2) | Feb 12, 2023 |
| ASRock        | B450 Pro4                   | [4fa0ea0e04](https://linux-hardware.org/?probe=4fa0ea0e04) | Feb 12, 2023 |
| Lenovo        | IdeaCentre K330B            | [862bd68d6f](https://linux-hardware.org/?probe=862bd68d6f) | Feb 12, 2023 |
| ASUSTek       | PRIME Z590-P                | [575dc82b32](https://linux-hardware.org/?probe=575dc82b32) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [de144d5025](https://linux-hardware.org/?probe=de144d5025) | Feb 12, 2023 |
| ASUSTek       | PRIME X399-A                | [8fbc5cca8e](https://linux-hardware.org/?probe=8fbc5cca8e) | Feb 12, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [343d75e9d7](https://linux-hardware.org/?probe=343d75e9d7) | Feb 12, 2023 |
| ASUSTek       | M5A88-M                     | [f1b285512e](https://linux-hardware.org/?probe=f1b285512e) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fb58e751aa](https://linux-hardware.org/?probe=fb58e751aa) | Feb 12, 2023 |
| Lenovo        | NOK                         | [c58a69a8c6](https://linux-hardware.org/?probe=c58a69a8c6) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [3a18e2226c](https://linux-hardware.org/?probe=3a18e2226c) | Feb 12, 2023 |
| MSI           | Z490-A PRO                  | [08ef3591e8](https://linux-hardware.org/?probe=08ef3591e8) | Feb 11, 2023 |
| ASUSTek       | PRIME X399-A                | [45f4900aa5](https://linux-hardware.org/?probe=45f4900aa5) | Feb 11, 2023 |
| ASRock        | X99 Professional Gaming ... | [56a6b8bb0f](https://linux-hardware.org/?probe=56a6b8bb0f) | Feb 11, 2023 |
| Dell          | 0WMJ54 A01                  | [350850e668](https://linux-hardware.org/?probe=350850e668) | Feb 11, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [86ca7a4821](https://linux-hardware.org/?probe=86ca7a4821) | Feb 11, 2023 |
| ASRock        | X99 Professional Gaming ... | [975e99c02f](https://linux-hardware.org/?probe=975e99c02f) | Feb 11, 2023 |
| Gigabyte      | Z370M DS3H-CF               | [2194ea605a](https://linux-hardware.org/?probe=2194ea605a) | Feb 11, 2023 |
| ASRock        | 880GMH/USB3                 | [55a9c9fd6c](https://linux-hardware.org/?probe=55a9c9fd6c) | Feb 11, 2023 |
| ASRock        | 880GMH/USB3                 | [39017e9de9](https://linux-hardware.org/?probe=39017e9de9) | Feb 11, 2023 |
| Intel         | DB85FL AAG89861-203         | [4403212f84](https://linux-hardware.org/?probe=4403212f84) | Feb 11, 2023 |
| HP            | 212B                        | [d3ac338cb9](https://linux-hardware.org/?probe=d3ac338cb9) | Feb 11, 2023 |
| Dell          | 0NC2VH A01                  | [665041c4c5](https://linux-hardware.org/?probe=665041c4c5) | Feb 11, 2023 |
| HP            | 1850                        | [54f5b16151](https://linux-hardware.org/?probe=54f5b16151) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d2098e4161](https://linux-hardware.org/?probe=d2098e4161) | Feb 11, 2023 |
| AZW           | U59                         | [db63601638](https://linux-hardware.org/?probe=db63601638) | Feb 11, 2023 |
| ASRock        | Z75 Pro3                    | [3dce5774ce](https://linux-hardware.org/?probe=3dce5774ce) | Feb 11, 2023 |
| Gigabyte      | F2A88X-UP4                  | [4c46cabf03](https://linux-hardware.org/?probe=4c46cabf03) | Feb 11, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [50e0d40c4f](https://linux-hardware.org/?probe=50e0d40c4f) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [266a3eff3f](https://linux-hardware.org/?probe=266a3eff3f) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18b84d9ea2](https://linux-hardware.org/?probe=18b84d9ea2) | Feb 10, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [fabdd92407](https://linux-hardware.org/?probe=fabdd92407) | Feb 10, 2023 |
| MSI           | PRO B660M-A CEC WIFI DDR... | [54a5198274](https://linux-hardware.org/?probe=54a5198274) | Feb 10, 2023 |
| Gigabyte      | H310M H x.x                 | [a166b37ae5](https://linux-hardware.org/?probe=a166b37ae5) | Feb 10, 2023 |
| ASRock        | KBL-NUC                     | [1093cfff1a](https://linux-hardware.org/?probe=1093cfff1a) | Feb 10, 2023 |
| MSI           | PRO B660M-A CEC WIFI DDR... | [26d146ba3f](https://linux-hardware.org/?probe=26d146ba3f) | Feb 10, 2023 |
| Gigabyte      | GB-BSi5-1135G7              | [93002e901f](https://linux-hardware.org/?probe=93002e901f) | Feb 10, 2023 |
| HP            | 8299                        | [adfbdeb133](https://linux-hardware.org/?probe=adfbdeb133) | Feb 10, 2023 |
| Alienware     | 07W25T A01                  | [e0606ee910](https://linux-hardware.org/?probe=e0606ee910) | Feb 10, 2023 |
| Dell          | 03NVJ6 A00                  | [f7df102318](https://linux-hardware.org/?probe=f7df102318) | Feb 10, 2023 |
| Gigabyte      | G41M-ES2L                   | [ea2304bdfe](https://linux-hardware.org/?probe=ea2304bdfe) | Feb 10, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [2fafc493ce](https://linux-hardware.org/?probe=2fafc493ce) | Feb 10, 2023 |
| ASUSTek       | PRIME Z270-P                | [ed180eeb68](https://linux-hardware.org/?probe=ed180eeb68) | Feb 09, 2023 |
| Gigabyte      | B550M DS3H AC               | [54773207c9](https://linux-hardware.org/?probe=54773207c9) | Feb 09, 2023 |
| HP            | 843B                        | [990b099595](https://linux-hardware.org/?probe=990b099595) | Feb 09, 2023 |
| Gigabyte      | B550M DS3H AC               | [3b6a3b2645](https://linux-hardware.org/?probe=3b6a3b2645) | Feb 09, 2023 |
| ASUSTek       | PRIME Z270-P                | [fff827c027](https://linux-hardware.org/?probe=fff827c027) | Feb 09, 2023 |
| Dell          | 0WG855                      | [ef27c0f1fd](https://linux-hardware.org/?probe=ef27c0f1fd) | Feb 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [287544d374](https://linux-hardware.org/?probe=287544d374) | Feb 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [fdcac99f8d](https://linux-hardware.org/?probe=fdcac99f8d) | Feb 09, 2023 |
| HP            | 212B                        | [cc32aa2d27](https://linux-hardware.org/?probe=cc32aa2d27) | Feb 09, 2023 |
| ASRock        | H81M-GL                     | [059a818847](https://linux-hardware.org/?probe=059a818847) | Feb 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [8e52ea763d](https://linux-hardware.org/?probe=8e52ea763d) | Feb 09, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | [da8cc0446d](https://linux-hardware.org/?probe=da8cc0446d) | Feb 09, 2023 |
| Foxconn       | 2AA9                        | [1ef39c5d1f](https://linux-hardware.org/?probe=1ef39c5d1f) | Feb 09, 2023 |
| Foxconn       | 2AA9                        | [20ea684766](https://linux-hardware.org/?probe=20ea684766) | Feb 09, 2023 |
| Dell          | 0M1GJ6 A00                  | [870a5b842b](https://linux-hardware.org/?probe=870a5b842b) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe84bf2bc9](https://linux-hardware.org/?probe=fe84bf2bc9) | Feb 09, 2023 |
| Dell          | 0HD5W2 A00                  | [ec4dc9e48c](https://linux-hardware.org/?probe=ec4dc9e48c) | Feb 08, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [7b17cbd936](https://linux-hardware.org/?probe=7b17cbd936) | Feb 08, 2023 |
| ASUSTek       | P5QL PRO                    | [9f2664ae2a](https://linux-hardware.org/?probe=9f2664ae2a) | Feb 08, 2023 |
| Dell          | 0VRWRC A00                  | [c864613b40](https://linux-hardware.org/?probe=c864613b40) | Feb 08, 2023 |
| Dell          | 0NC2VH A01                  | [85ab2e4223](https://linux-hardware.org/?probe=85ab2e4223) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | [997020aeb0](https://linux-hardware.org/?probe=997020aeb0) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | [c90f2404df](https://linux-hardware.org/?probe=c90f2404df) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | [bb851866ac](https://linux-hardware.org/?probe=bb851866ac) | Feb 08, 2023 |
| ASRock        | B550AM Gaming               | [8669f943e2](https://linux-hardware.org/?probe=8669f943e2) | Feb 08, 2023 |
| Dell          | 0NW6H5 A00                  | [6316345fe1](https://linux-hardware.org/?probe=6316345fe1) | Feb 08, 2023 |
| Gigabyte      | X79-UP4                     | [f2d4900223](https://linux-hardware.org/?probe=f2d4900223) | Feb 08, 2023 |
| Gigabyte      | X79-UP4                     | [1c26b64afb](https://linux-hardware.org/?probe=1c26b64afb) | Feb 08, 2023 |
| HP            | 3047h                       | [bdb6af834f](https://linux-hardware.org/?probe=bdb6af834f) | Feb 08, 2023 |
| ASUSTek       | B150 PRO GAMING D3          | [8178f6bf56](https://linux-hardware.org/?probe=8178f6bf56) | Feb 08, 2023 |
| ASRock        | B550AM Gaming               | [19644a12bc](https://linux-hardware.org/?probe=19644a12bc) | Feb 07, 2023 |
| ECS           | GF8100VM-M5                 | [9b536f16be](https://linux-hardware.org/?probe=9b536f16be) | Feb 07, 2023 |
| Supermicro    | X9SCI/X9SCA                 | [cd48778589](https://linux-hardware.org/?probe=cd48778589) | Feb 07, 2023 |
| ASUSTek       | PRIME X399-A                | [22ba7d722f](https://linux-hardware.org/?probe=22ba7d722f) | Feb 07, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3fce6d5f05](https://linux-hardware.org/?probe=3fce6d5f05) | Feb 07, 2023 |
| MSI           | Z97 GAMING 5                | [4d716306f0](https://linux-hardware.org/?probe=4d716306f0) | Feb 07, 2023 |
| MSI           | B550-A PRO                  | [cc856dafad](https://linux-hardware.org/?probe=cc856dafad) | Feb 07, 2023 |
| Gigabyte      | B550M DS3H AC               | [0677b143ac](https://linux-hardware.org/?probe=0677b143ac) | Feb 07, 2023 |
| Acer          | Aspire TC-1760              | [b7fdb6cd73](https://linux-hardware.org/?probe=b7fdb6cd73) | Feb 06, 2023 |
| ASUSTek       | EB1501P                     | [687e52dcb1](https://linux-hardware.org/?probe=687e52dcb1) | Feb 06, 2023 |
| MSI           | A320M-A PRO MAX             | [40ba1db546](https://linux-hardware.org/?probe=40ba1db546) | Feb 06, 2023 |
| Dell          | 06JWJY A00                  | [9745edaf8e](https://linux-hardware.org/?probe=9745edaf8e) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | [6519e2ca2f](https://linux-hardware.org/?probe=6519e2ca2f) | Feb 06, 2023 |
| MSI           | 0A90                        | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| HP            | 339A                        | [b3f42d1e4c](https://linux-hardware.org/?probe=b3f42d1e4c) | Feb 06, 2023 |
| Lenovo        | ThinkServer TS140           | [62c720768e](https://linux-hardware.org/?probe=62c720768e) | Feb 06, 2023 |
| Dell          | 0NW6H5 A00                  | [5adc441a9a](https://linux-hardware.org/?probe=5adc441a9a) | Feb 06, 2023 |
| Dell          | 0NW6H5 A00                  | [8715d15e13](https://linux-hardware.org/?probe=8715d15e13) | Feb 06, 2023 |
| HP            | 1495                        | [1843e738b9](https://linux-hardware.org/?probe=1843e738b9) | Feb 06, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [7340382218](https://linux-hardware.org/?probe=7340382218) | Feb 06, 2023 |
| ASUSTek       | M5A78L LE                   | [0e0bd23571](https://linux-hardware.org/?probe=0e0bd23571) | Feb 05, 2023 |
| Dell          | 0TTDMJ A00                  | [6dd8a1b58a](https://linux-hardware.org/?probe=6dd8a1b58a) | Feb 05, 2023 |
| Dell          | 0C113J A00                  | [2852e8c500](https://linux-hardware.org/?probe=2852e8c500) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| MSI           | H410M-A PRO                 | [6ac747c27e](https://linux-hardware.org/?probe=6ac747c27e) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| MSI           | X570-A PRO                  | [aeab6dd32b](https://linux-hardware.org/?probe=aeab6dd32b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e13f9ef899](https://linux-hardware.org/?probe=e13f9ef899) | Feb 05, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [e5707e3ff0](https://linux-hardware.org/?probe=e5707e3ff0) | Feb 05, 2023 |
| HPE           | ProLiant MicroServer Gen... | [9a9b3eed69](https://linux-hardware.org/?probe=9a9b3eed69) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [cc91f98d69](https://linux-hardware.org/?probe=cc91f98d69) | Feb 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [83a5201a65](https://linux-hardware.org/?probe=83a5201a65) | Feb 05, 2023 |
| ASRock        | H61M-HP4                    | [826a81ae2e](https://linux-hardware.org/?probe=826a81ae2e) | Feb 05, 2023 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | [9e8c261333](https://linux-hardware.org/?probe=9e8c261333) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [104a086d29](https://linux-hardware.org/?probe=104a086d29) | Feb 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [23d1d4e169](https://linux-hardware.org/?probe=23d1d4e169) | Feb 05, 2023 |
| Dell          | 02YYK5 A01                  | [493b4dec73](https://linux-hardware.org/?probe=493b4dec73) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [578b166faa](https://linux-hardware.org/?probe=578b166faa) | Feb 05, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [5755b9feb0](https://linux-hardware.org/?probe=5755b9feb0) | Feb 05, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [bb6bee6af9](https://linux-hardware.org/?probe=bb6bee6af9) | Feb 05, 2023 |
| MSI           | Z170A GAMING M5             | [1e80232772](https://linux-hardware.org/?probe=1e80232772) | Feb 04, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [0c6df9267b](https://linux-hardware.org/?probe=0c6df9267b) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7cd8292c5f](https://linux-hardware.org/?probe=7cd8292c5f) | Feb 04, 2023 |
| MSI           | MS-7376                     | [5f62748624](https://linux-hardware.org/?probe=5f62748624) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1a75c9d014](https://linux-hardware.org/?probe=1a75c9d014) | Feb 04, 2023 |
| MSI           | MS-7376                     | [33fa767f72](https://linux-hardware.org/?probe=33fa767f72) | Feb 04, 2023 |
| MSI           | Z170-A PRO                  | [564a19c004](https://linux-hardware.org/?probe=564a19c004) | Feb 04, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [07d496ada9](https://linux-hardware.org/?probe=07d496ada9) | Feb 04, 2023 |
| ASUSTek       | PRIME A320M-K               | [a1b3ef275a](https://linux-hardware.org/?probe=a1b3ef275a) | Feb 04, 2023 |
| ASUSTek       | PRIME A320M-K               | [6a67c722de](https://linux-hardware.org/?probe=6a67c722de) | Feb 04, 2023 |
| ASUSTek       | Maximus VII HERO            | [81a833cf8e](https://linux-hardware.org/?probe=81a833cf8e) | Feb 04, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7f895dc97f](https://linux-hardware.org/?probe=7f895dc97f) | Feb 04, 2023 |
| Dell          | 0D28YY A03                  | [ae7eeb7487](https://linux-hardware.org/?probe=ae7eeb7487) | Feb 04, 2023 |
| Dell          | 0D28YY A03                  | [0fe32fbdc2](https://linux-hardware.org/?probe=0fe32fbdc2) | Feb 04, 2023 |
| ASUSTek       | P8B75-M LE                  | [93ee4435a2](https://linux-hardware.org/?probe=93ee4435a2) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | [5c7d71b636](https://linux-hardware.org/?probe=5c7d71b636) | Feb 03, 2023 |
| Intel         | D33217GKE G76540-203        | [0f43f169d1](https://linux-hardware.org/?probe=0f43f169d1) | Feb 03, 2023 |
| MSI           | B550-A PRO                  | [dc4a285d49](https://linux-hardware.org/?probe=dc4a285d49) | Feb 03, 2023 |
| ASUSTek       | PRIME X570-PRO              | [348a044239](https://linux-hardware.org/?probe=348a044239) | Feb 03, 2023 |
| HP            | 8055                        | [77735e9a90](https://linux-hardware.org/?probe=77735e9a90) | Feb 03, 2023 |
| ASUSTek       | B85M-G R2.0                 | [749df590bc](https://linux-hardware.org/?probe=749df590bc) | Feb 03, 2023 |
| ASUSTek       | B85M-G R2.0                 | [4e5c031e2e](https://linux-hardware.org/?probe=4e5c031e2e) | Feb 03, 2023 |
| ASRock        | Z68 Pro3-M                  | [f72aaf6ef9](https://linux-hardware.org/?probe=f72aaf6ef9) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [afadbdee59](https://linux-hardware.org/?probe=afadbdee59) | Feb 03, 2023 |
| HP            | 802F                        | [b36a46a944](https://linux-hardware.org/?probe=b36a46a944) | Feb 03, 2023 |
| Dell          | 00V62H A01                  | [5b3fa12024](https://linux-hardware.org/?probe=5b3fa12024) | Feb 03, 2023 |
| Unknown       | 1.0                         | [402bce9e43](https://linux-hardware.org/?probe=402bce9e43) | Feb 03, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [93630ab2ea](https://linux-hardware.org/?probe=93630ab2ea) | Feb 03, 2023 |
| HP            | 3047h                       | [c18d309312](https://linux-hardware.org/?probe=c18d309312) | Feb 03, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [22c7c21b25](https://linux-hardware.org/?probe=22c7c21b25) | Feb 03, 2023 |
| HP            | 2B28                        | [19c05992eb](https://linux-hardware.org/?probe=19c05992eb) | Feb 03, 2023 |
| HP            | 212B                        | [f27b5c4aa0](https://linux-hardware.org/?probe=f27b5c4aa0) | Feb 03, 2023 |
| ASRock        | Q1900M                      | [872fb866c6](https://linux-hardware.org/?probe=872fb866c6) | Feb 02, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [df1a88f3fd](https://linux-hardware.org/?probe=df1a88f3fd) | Feb 02, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [fac45201b3](https://linux-hardware.org/?probe=fac45201b3) | Feb 02, 2023 |
| MSI           | H110M PRO-VD                | [b35d6e3a08](https://linux-hardware.org/?probe=b35d6e3a08) | Feb 02, 2023 |
| MSI           | H110M PRO-VD                | [cc717bffbe](https://linux-hardware.org/?probe=cc717bffbe) | Feb 02, 2023 |
| HP            | 2ADE                        | [b3735eb6c9](https://linux-hardware.org/?probe=b3735eb6c9) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M LE                 | [dab3550ce4](https://linux-hardware.org/?probe=dab3550ce4) | Feb 02, 2023 |
| Gigabyte      | B365M DS3H                  | [f04d195965](https://linux-hardware.org/?probe=f04d195965) | Feb 02, 2023 |
| Lenovo        | NOK                         | [c159b0565a](https://linux-hardware.org/?probe=c159b0565a) | Feb 02, 2023 |
| Wistron       | ProLiant ML110 G5           | [4af666d5b3](https://linux-hardware.org/?probe=4af666d5b3) | Feb 02, 2023 |
| MSI           | X399 SLI PLUS               | [33f2d92922](https://linux-hardware.org/?probe=33f2d92922) | Feb 02, 2023 |
| ASUSTek       | Q87M-E                      | [860c79e1aa](https://linux-hardware.org/?probe=860c79e1aa) | Feb 01, 2023 |
| Supermicro    | X10DRi-T4+                  | [afde7db629](https://linux-hardware.org/?probe=afde7db629) | Feb 01, 2023 |
| Dell          | 09M8Y8 A01                  | [6df318e1d4](https://linux-hardware.org/?probe=6df318e1d4) | Feb 01, 2023 |
| Gigabyte      | B365M DS3H                  | [d515d5d9f7](https://linux-hardware.org/?probe=d515d5d9f7) | Feb 01, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1668f1f69f](https://linux-hardware.org/?probe=1668f1f69f) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [2e458676e4](https://linux-hardware.org/?probe=2e458676e4) | Feb 01, 2023 |
| HP            | 1790                        | [d0d3ca5e7c](https://linux-hardware.org/?probe=d0d3ca5e7c) | Feb 01, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [e68a009e8f](https://linux-hardware.org/?probe=e68a009e8f) | Feb 01, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [72dae43046](https://linux-hardware.org/?probe=72dae43046) | Feb 01, 2023 |
| NCR           | Pocono                      | [1a1c878e10](https://linux-hardware.org/?probe=1a1c878e10) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [d59770af38](https://linux-hardware.org/?probe=d59770af38) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3a5ae3d1e8](https://linux-hardware.org/?probe=3a5ae3d1e8) | Jan 31, 2023 |
| Intel         | DH77DF AAG40293-301         | [1a0f7653e3](https://linux-hardware.org/?probe=1a0f7653e3) | Jan 31, 2023 |
| Dell          | 06HR05 A00                  | [b80c55d90d](https://linux-hardware.org/?probe=b80c55d90d) | Jan 31, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [01c7dbecde](https://linux-hardware.org/?probe=01c7dbecde) | Jan 31, 2023 |
| Gigabyte      | Z97M-DS3H                   | [360dc83e04](https://linux-hardware.org/?probe=360dc83e04) | Jan 31, 2023 |
| Medion        | MS-7728                     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Maxtang       | EHL30 V1.0                  | [d104ad1307](https://linux-hardware.org/?probe=d104ad1307) | Jan 31, 2023 |
| Dell          | 040DDP A01                  | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Gigabyte      | H270-Gaming 3               | [e64a1e0a5a](https://linux-hardware.org/?probe=e64a1e0a5a) | Jan 31, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [846f831269](https://linux-hardware.org/?probe=846f831269) | Jan 31, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [9e9deedf0d](https://linux-hardware.org/?probe=9e9deedf0d) | Jan 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [f018b74ad8](https://linux-hardware.org/?probe=f018b74ad8) | Jan 31, 2023 |
| Acer          | Unknown                     | [05de2b4244](https://linux-hardware.org/?probe=05de2b4244) | Jan 30, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [353272e0d2](https://linux-hardware.org/?probe=353272e0d2) | Jan 30, 2023 |
| Dell          | 0GDG8Y A00                  | [8ba7e25b58](https://linux-hardware.org/?probe=8ba7e25b58) | Jan 30, 2023 |
| Dell          | 0GDG8Y A00                  | [759e9a48d1](https://linux-hardware.org/?probe=759e9a48d1) | Jan 30, 2023 |
| Intel         | DH77DF AAG40293-301         | [1c91d911d7](https://linux-hardware.org/?probe=1c91d911d7) | Jan 30, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [529b411b46](https://linux-hardware.org/?probe=529b411b46) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [7983249b4c](https://linux-hardware.org/?probe=7983249b4c) | Jan 30, 2023 |
| HP            | 8054                        | [f2367fdcda](https://linux-hardware.org/?probe=f2367fdcda) | Jan 30, 2023 |
| MSI           | X370 SLI PLUS               | [bb20465703](https://linux-hardware.org/?probe=bb20465703) | Jan 30, 2023 |
| HP            | 18E7                        | [db4ef3e5f4](https://linux-hardware.org/?probe=db4ef3e5f4) | Jan 30, 2023 |
| Gigabyte      | H270-Gaming 3               | [4427845ac1](https://linux-hardware.org/?probe=4427845ac1) | Jan 30, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [aff06e830e](https://linux-hardware.org/?probe=aff06e830e) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4fb612b680](https://linux-hardware.org/?probe=4fb612b680) | Jan 29, 2023 |
| MSI           | MPG B550I GAMING EDGE MA... | [ff186606cd](https://linux-hardware.org/?probe=ff186606cd) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [7af163f694](https://linux-hardware.org/?probe=7af163f694) | Jan 29, 2023 |
| Gigabyte      | B250M-HD3-CF                | [f8630776ca](https://linux-hardware.org/?probe=f8630776ca) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | [873725bb74](https://linux-hardware.org/?probe=873725bb74) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | [f489fe4f5d](https://linux-hardware.org/?probe=f489fe4f5d) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-K II            | [d4a5012f93](https://linux-hardware.org/?probe=d4a5012f93) | Jan 29, 2023 |
| Dell          | 0VRWRC A01                  | [0e6a170715](https://linux-hardware.org/?probe=0e6a170715) | Jan 29, 2023 |
| HP            | 81B4                        | [01229ad5ec](https://linux-hardware.org/?probe=01229ad5ec) | Jan 29, 2023 |
| ASRock        | 970M Pro3                   | [e0a5d6512f](https://linux-hardware.org/?probe=e0a5d6512f) | Jan 29, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [9daeb7adc3](https://linux-hardware.org/?probe=9daeb7adc3) | Jan 29, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [75027cfa77](https://linux-hardware.org/?probe=75027cfa77) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [37c0fb77f5](https://linux-hardware.org/?probe=37c0fb77f5) | Jan 29, 2023 |
| Apple         | Mac-F221BEC8                | [d8de82d8c4](https://linux-hardware.org/?probe=d8de82d8c4) | Jan 29, 2023 |
| HP            | 18E7                        | [01cbafc241](https://linux-hardware.org/?probe=01cbafc241) | Jan 28, 2023 |
| ASUSTek       | F2A55-M LK2                 | [8bf2fa8d9b](https://linux-hardware.org/?probe=8bf2fa8d9b) | Jan 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [845b3c6990](https://linux-hardware.org/?probe=845b3c6990) | Jan 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d7469767f6](https://linux-hardware.org/?probe=d7469767f6) | Jan 28, 2023 |
| ASUSTek       | F2A85-V                     | [d528677cfd](https://linux-hardware.org/?probe=d528677cfd) | Jan 28, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [c7fc79b5f1](https://linux-hardware.org/?probe=c7fc79b5f1) | Jan 28, 2023 |
| BESSTAR Te... | UM350                       | [1ec2f78884](https://linux-hardware.org/?probe=1ec2f78884) | Jan 28, 2023 |
| ASUSTek       | PRIME A320M-K               | [11586188ad](https://linux-hardware.org/?probe=11586188ad) | Jan 28, 2023 |
| ASUSTek       | A58M-A/BR                   | [2e6e55e6ea](https://linux-hardware.org/?probe=2e6e55e6ea) | Jan 28, 2023 |
| ASRock        | 970M Pro3                   | [58366ca3d1](https://linux-hardware.org/?probe=58366ca3d1) | Jan 28, 2023 |
| Dell          | 0HY9JP A00                  | [f4aefcd670](https://linux-hardware.org/?probe=f4aefcd670) | Jan 28, 2023 |
| ASUSTek       | H61M-K                      | [312e07a824](https://linux-hardware.org/?probe=312e07a824) | Jan 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | [97d1ab1b7d](https://linux-hardware.org/?probe=97d1ab1b7d) | Jan 28, 2023 |
| Gigabyte      | B75M-D3H                    | [3ee2e6ab56](https://linux-hardware.org/?probe=3ee2e6ab56) | Jan 27, 2023 |
| MSI           | TRX40 PRO WIFI              | [d9508d5b22](https://linux-hardware.org/?probe=d9508d5b22) | Jan 27, 2023 |
| Dell          | 057FFP A01                  | [ec0e3da69d](https://linux-hardware.org/?probe=ec0e3da69d) | Jan 27, 2023 |
| Acer          | Predator G3620              | [0fdd7e30ce](https://linux-hardware.org/?probe=0fdd7e30ce) | Jan 27, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [6d2e490a23](https://linux-hardware.org/?probe=6d2e490a23) | Jan 27, 2023 |
| ASUSTek       | Z170-K                      | [a1f535bfca](https://linux-hardware.org/?probe=a1f535bfca) | Jan 27, 2023 |
| ASUSTek       | P5K                         | [6d496e6965](https://linux-hardware.org/?probe=6d496e6965) | Jan 27, 2023 |
| Dell          | 0GM819                      | [f5810a0a61](https://linux-hardware.org/?probe=f5810a0a61) | Jan 27, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [e660f922a4](https://linux-hardware.org/?probe=e660f922a4) | Jan 27, 2023 |
| Lenovo        | 0B98401 PRO                 | [06086e6112](https://linux-hardware.org/?probe=06086e6112) | Jan 27, 2023 |
| Dell          | 0RY206                      | [822d0f1c17](https://linux-hardware.org/?probe=822d0f1c17) | Jan 27, 2023 |
| ASUSTek       | H61M-E                      | [0ebd68a086](https://linux-hardware.org/?probe=0ebd68a086) | Jan 27, 2023 |
| Medion        | MS-7675                     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| Gigabyte      | 970A-D3P                    | [f01366b131](https://linux-hardware.org/?probe=f01366b131) | Jan 27, 2023 |
| HP            | Compaq 8200 Elite SFF PC    | [73f629ca61](https://linux-hardware.org/?probe=73f629ca61) | Jan 27, 2023 |
| Gigabyte      | X570 UD                     | [75e92725f5](https://linux-hardware.org/?probe=75e92725f5) | Jan 26, 2023 |
| Gigabyte      | H81M-S2PV                   | [4910cfdfcd](https://linux-hardware.org/?probe=4910cfdfcd) | Jan 26, 2023 |
| Positivo      | POS-PIB150DT                | [5a333d4e71](https://linux-hardware.org/?probe=5a333d4e71) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS M                | [3e65f42529](https://linux-hardware.org/?probe=3e65f42529) | Jan 26, 2023 |
| Dell          | 0CRH6C A01                  | [d06248a310](https://linux-hardware.org/?probe=d06248a310) | Jan 26, 2023 |
| Unknown       | 1.0                         | [85d36881c1](https://linux-hardware.org/?probe=85d36881c1) | Jan 26, 2023 |
| Unknown       | 1.0                         | [a25e1d1008](https://linux-hardware.org/?probe=a25e1d1008) | Jan 26, 2023 |
| HP            | 843B                        | [98d0f20b21](https://linux-hardware.org/?probe=98d0f20b21) | Jan 26, 2023 |
| HP            | 8299                        | [d73eaeeb81](https://linux-hardware.org/?probe=d73eaeeb81) | Jan 26, 2023 |
| HP            | 18E4                        | [1f51508eeb](https://linux-hardware.org/?probe=1f51508eeb) | Jan 26, 2023 |
| HP            | 8299                        | [47b5f3fdef](https://linux-hardware.org/?probe=47b5f3fdef) | Jan 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [72a508a4ad](https://linux-hardware.org/?probe=72a508a4ad) | Jan 26, 2023 |
| ASRock        | Z690 Taichi                 | [adba499f59](https://linux-hardware.org/?probe=adba499f59) | Jan 26, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [a9775027ed](https://linux-hardware.org/?probe=a9775027ed) | Jan 26, 2023 |
| ASUSTek       | Basswood3G                  | [0728a59863](https://linux-hardware.org/?probe=0728a59863) | Jan 25, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [d30b7c1657](https://linux-hardware.org/?probe=d30b7c1657) | Jan 25, 2023 |
| HP            | 1495                        | [d600418bf6](https://linux-hardware.org/?probe=d600418bf6) | Jan 25, 2023 |
| Apple         | Mac-F221BEC8                | [73b7cfc152](https://linux-hardware.org/?probe=73b7cfc152) | Jan 25, 2023 |
| MSI           | 2A9C                        | [cea7204c4b](https://linux-hardware.org/?probe=cea7204c4b) | Jan 25, 2023 |
| ASUSTek       | G20AJ                       | [ff9bda6922](https://linux-hardware.org/?probe=ff9bda6922) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| Dell          | 0KRC95 A01                  | [9580da1eb5](https://linux-hardware.org/?probe=9580da1eb5) | Jan 25, 2023 |
| Gigabyte      | H310M H x.x                 | [64ccdd32f5](https://linux-hardware.org/?probe=64ccdd32f5) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [596316a81c](https://linux-hardware.org/?probe=596316a81c) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| ASRock        | X99 Professional Gaming ... | [74054f4cb8](https://linux-hardware.org/?probe=74054f4cb8) | Jan 24, 2023 |
| ASRock        | X99 Professional Gaming ... | [2a89d751e1](https://linux-hardware.org/?probe=2a89d751e1) | Jan 24, 2023 |
| MSI           | Boston                      | [456d7782ad](https://linux-hardware.org/?probe=456d7782ad) | Jan 24, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [0300fb4b9a](https://linux-hardware.org/?probe=0300fb4b9a) | Jan 24, 2023 |
| MSI           | B560M PRO-VDH               | [8cb2b45267](https://linux-hardware.org/?probe=8cb2b45267) | Jan 24, 2023 |
| ASRock        | H110 Pro BTC+               | [f4a90a48ec](https://linux-hardware.org/?probe=f4a90a48ec) | Jan 24, 2023 |
| Unknown       | 1.0                         | [99201dd05a](https://linux-hardware.org/?probe=99201dd05a) | Jan 24, 2023 |
| MSI           | B350M MORTAR                | [1c843535db](https://linux-hardware.org/?probe=1c843535db) | Jan 24, 2023 |
| ASUSTek       | PRIME X570-P                | [c8c9f53754](https://linux-hardware.org/?probe=c8c9f53754) | Jan 24, 2023 |
| ASUSTek       | Z87-WS                      | [da3028df45](https://linux-hardware.org/?probe=da3028df45) | Jan 23, 2023 |
| Gateway       | IPIMB-ARA                   | [53527537f3](https://linux-hardware.org/?probe=53527537f3) | Jan 23, 2023 |
| Dell          | 0YC03K A04                  | [aaccd62190](https://linux-hardware.org/?probe=aaccd62190) | Jan 23, 2023 |
| ASRock        | 960GM-GS3 FX                | [f2894f6970](https://linux-hardware.org/?probe=f2894f6970) | Jan 23, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [123c1db6ac](https://linux-hardware.org/?probe=123c1db6ac) | Jan 23, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48ee4a3eef](https://linux-hardware.org/?probe=48ee4a3eef) | Jan 23, 2023 |
| Unknown       | 1.0                         | [678e6d3875](https://linux-hardware.org/?probe=678e6d3875) | Jan 23, 2023 |
| Gigabyte      | M68MT-S2P                   | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [4a6f5a78f9](https://linux-hardware.org/?probe=4a6f5a78f9) | Jan 23, 2023 |
| MSI           | Z390-A PRO                  | [68a1d06f54](https://linux-hardware.org/?probe=68a1d06f54) | Jan 23, 2023 |
| Dell          | 0NNNCT A01                  | [b80dda96de](https://linux-hardware.org/?probe=b80dda96de) | Jan 23, 2023 |
| Gigabyte      | H310M H x.x                 | [ac375e0fa7](https://linux-hardware.org/?probe=ac375e0fa7) | Jan 23, 2023 |
| MSI           | A320M-A PRO                 | [4b4420e22f](https://linux-hardware.org/?probe=4b4420e22f) | Jan 23, 2023 |
| Gateway       | IPIMB-ARA                   | [86fcc07fe3](https://linux-hardware.org/?probe=86fcc07fe3) | Jan 23, 2023 |
| ASRock        | N68-VGS3 FX                 | [d25d4580a9](https://linux-hardware.org/?probe=d25d4580a9) | Jan 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | [8e5bf9673b](https://linux-hardware.org/?probe=8e5bf9673b) | Jan 23, 2023 |
| Dell          | 0NV0M7 A02                  | [7c562ab921](https://linux-hardware.org/?probe=7c562ab921) | Jan 22, 2023 |
| ASRock        | G31M-S                      | [dbf8922f3a](https://linux-hardware.org/?probe=dbf8922f3a) | Jan 22, 2023 |
| MSI           | Boston                      | [34413408ce](https://linux-hardware.org/?probe=34413408ce) | Jan 22, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [7407dcc533](https://linux-hardware.org/?probe=7407dcc533) | Jan 22, 2023 |
| Medion        | H110H4-EM                   | [02ac31d42d](https://linux-hardware.org/?probe=02ac31d42d) | Jan 22, 2023 |
| Dell          | 0NV0M7 A02                  | [b5bd3e5d33](https://linux-hardware.org/?probe=b5bd3e5d33) | Jan 22, 2023 |
| Biostar       | A320MH                      | [4c75d6c079](https://linux-hardware.org/?probe=4c75d6c079) | Jan 22, 2023 |
| ASRock        | B365 Pro4                   | [44fa1b3713](https://linux-hardware.org/?probe=44fa1b3713) | Jan 22, 2023 |
| ASUSTek       | P5K                         | [dc5b823cb5](https://linux-hardware.org/?probe=dc5b823cb5) | Jan 22, 2023 |
| ASRock        | N68-GE3 UCC                 | [cd23d81f65](https://linux-hardware.org/?probe=cd23d81f65) | Jan 22, 2023 |
| Lenovo        | NOK                         | [78e5b6feb3](https://linux-hardware.org/?probe=78e5b6feb3) | Jan 22, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [27ec85040f](https://linux-hardware.org/?probe=27ec85040f) | Jan 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d251029940](https://linux-hardware.org/?probe=d251029940) | Jan 22, 2023 |
| HP            | 339A                        | [031e19c496](https://linux-hardware.org/?probe=031e19c496) | Jan 21, 2023 |
| Gigabyte      | B550M DS3H AC               | [47a418d177](https://linux-hardware.org/?probe=47a418d177) | Jan 21, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [4584e904f8](https://linux-hardware.org/?probe=4584e904f8) | Jan 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [6419184e6e](https://linux-hardware.org/?probe=6419184e6e) | Jan 21, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [f6f1f5e32b](https://linux-hardware.org/?probe=f6f1f5e32b) | Jan 21, 2023 |
| ASUSTek       | M4N78-AM                    | [cf65d9f981](https://linux-hardware.org/?probe=cf65d9f981) | Jan 21, 2023 |
| Dell          | 0F6X5P A00                  | [6228476153](https://linux-hardware.org/?probe=6228476153) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B560M-E          | [0bbafaf9fe](https://linux-hardware.org/?probe=0bbafaf9fe) | Jan 21, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [9229e3b2ae](https://linux-hardware.org/?probe=9229e3b2ae) | Jan 21, 2023 |
| Medion        | MS-7728                     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Intel         | DH61BF AAG81311-101         | [d6ea5bde87](https://linux-hardware.org/?probe=d6ea5bde87) | Jan 21, 2023 |
| MSI           | B450-A PRO MAX              | [9d025602e0](https://linux-hardware.org/?probe=9d025602e0) | Jan 21, 2023 |
| ASUSTek       | Maximus VII HERO            | [3fe12efbb8](https://linux-hardware.org/?probe=3fe12efbb8) | Jan 21, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [33dfa6188e](https://linux-hardware.org/?probe=33dfa6188e) | Jan 20, 2023 |
| ASUSTek       | Z87-PRO                     | [334bde8bc6](https://linux-hardware.org/?probe=334bde8bc6) | Jan 20, 2023 |
| Pegatron      | NARRA5                      | [0772fdc2db](https://linux-hardware.org/?probe=0772fdc2db) | Jan 20, 2023 |
| MSI           | MS-7369                     | [7e96534421](https://linux-hardware.org/?probe=7e96534421) | Jan 20, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [1b41330a7e](https://linux-hardware.org/?probe=1b41330a7e) | Jan 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ce99cb312d](https://linux-hardware.org/?probe=ce99cb312d) | Jan 20, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [55d330d3ea](https://linux-hardware.org/?probe=55d330d3ea) | Jan 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6c55213012](https://linux-hardware.org/?probe=6c55213012) | Jan 20, 2023 |
| Gigabyte      | B75M-D3H                    | [a3def8bf43](https://linux-hardware.org/?probe=a3def8bf43) | Jan 19, 2023 |
| ASUSTek       | PRIME B365M-A               | [c08f2e5961](https://linux-hardware.org/?probe=c08f2e5961) | Jan 19, 2023 |
| ASUSTek       | PRIME B350M-A               | [6f50700657](https://linux-hardware.org/?probe=6f50700657) | Jan 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [9301fd6936](https://linux-hardware.org/?probe=9301fd6936) | Jan 19, 2023 |
| MSI           | H110M PRO-VD                | [e000402b1c](https://linux-hardware.org/?probe=e000402b1c) | Jan 19, 2023 |
| ASRock        | H110 Pro BTC+               | [f888822c0d](https://linux-hardware.org/?probe=f888822c0d) | Jan 19, 2023 |
| ASUSTek       | PRIME X399-A                | [1a61029965](https://linux-hardware.org/?probe=1a61029965) | Jan 19, 2023 |
| MSI           | H110M PRO-VD                | [79e6461b99](https://linux-hardware.org/?probe=79e6461b99) | Jan 19, 2023 |
| MSI           | X570-A PRO                  | [9c0b3ef63b](https://linux-hardware.org/?probe=9c0b3ef63b) | Jan 19, 2023 |
| Pegatron      | EVANS                       | [798a545fa8](https://linux-hardware.org/?probe=798a545fa8) | Jan 19, 2023 |
| Pegatron      | EVANS                       | [411db3ea66](https://linux-hardware.org/?probe=411db3ea66) | Jan 19, 2023 |
| Dell          | 0WR7PY A01                  | [4197c5f3d3](https://linux-hardware.org/?probe=4197c5f3d3) | Jan 19, 2023 |
| MSI           | H81M-E33                    | [ddb1be1cc6](https://linux-hardware.org/?probe=ddb1be1cc6) | Jan 18, 2023 |
| ASRock        | G31M-S                      | [d3aa4e7eea](https://linux-hardware.org/?probe=d3aa4e7eea) | Jan 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [8e511beda6](https://linux-hardware.org/?probe=8e511beda6) | Jan 18, 2023 |
| ASUSTek       | PRIME H510M-A               | [0ccab4b1e3](https://linux-hardware.org/?probe=0ccab4b1e3) | Jan 18, 2023 |
| Medion        | MS-7728                     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| ASRock        | B550M-ITX/ac                | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| Lenovo        | 0B98401 WIN                 | [8d4e5b4499](https://linux-hardware.org/?probe=8d4e5b4499) | Jan 18, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [f7efc3545d](https://linux-hardware.org/?probe=f7efc3545d) | Jan 18, 2023 |
| Dell          | 0Y3R3K A00                  | [f2164a9c60](https://linux-hardware.org/?probe=f2164a9c60) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| HP            | 2B35                        | [559109871c](https://linux-hardware.org/?probe=559109871c) | Jan 18, 2023 |
| Intel         | DG41RQ AAE54511-205         | [1125db7cfd](https://linux-hardware.org/?probe=1125db7cfd) | Jan 18, 2023 |
| Dell          | 0T7D40 A01                  | [75b71dfa6d](https://linux-hardware.org/?probe=75b71dfa6d) | Jan 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9a99559833](https://linux-hardware.org/?probe=9a99559833) | Jan 18, 2023 |
| ASRock        | G31M-S                      | [50bc0b52b3](https://linux-hardware.org/?probe=50bc0b52b3) | Jan 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | [cfaac8c50b](https://linux-hardware.org/?probe=cfaac8c50b) | Jan 17, 2023 |
| ASUSTek       | P8Q77-M                     | [f883cb7c7b](https://linux-hardware.org/?probe=f883cb7c7b) | Jan 17, 2023 |
| ASUSTek       | PRIME Z270-A                | [ad9172f4a9](https://linux-hardware.org/?probe=ad9172f4a9) | Jan 17, 2023 |
| ASRock        | H110 Pro BTC+               | [0b515319d8](https://linux-hardware.org/?probe=0b515319d8) | Jan 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | [2cc8923eb1](https://linux-hardware.org/?probe=2cc8923eb1) | Jan 17, 2023 |
| ASRock        | B550M Pro4                  | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [4589a3ea25](https://linux-hardware.org/?probe=4589a3ea25) | Jan 17, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [eb30638f2c](https://linux-hardware.org/?probe=eb30638f2c) | Jan 17, 2023 |
| ASRock        | Z590M-ITX/ax                | [15548bbea4](https://linux-hardware.org/?probe=15548bbea4) | Jan 17, 2023 |
| ASRock        | Z590M-ITX/ax                | [5663d8c22e](https://linux-hardware.org/?probe=5663d8c22e) | Jan 17, 2023 |
| Gigabyte      | H97N-WIFI                   | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| Gigabyte      | B560M DS3H V2               | [e29ceaa96c](https://linux-hardware.org/?probe=e29ceaa96c) | Jan 17, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [e14bf959d0](https://linux-hardware.org/?probe=e14bf959d0) | Jan 17, 2023 |
| ASRock        | H81M-ITX                    | [036832c7d1](https://linux-hardware.org/?probe=036832c7d1) | Jan 17, 2023 |
| MSI           | 2AE0                        | [25f46f6bf3](https://linux-hardware.org/?probe=25f46f6bf3) | Jan 17, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [2f40be547f](https://linux-hardware.org/?probe=2f40be547f) | Jan 17, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [8c0e31f290](https://linux-hardware.org/?probe=8c0e31f290) | Jan 17, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [83b98e5580](https://linux-hardware.org/?probe=83b98e5580) | Jan 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f3b27e21a7](https://linux-hardware.org/?probe=f3b27e21a7) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | [c99128e783](https://linux-hardware.org/?probe=c99128e783) | Jan 16, 2023 |
| Gigabyte      | H310M H x.x                 | [64b395004f](https://linux-hardware.org/?probe=64b395004f) | Jan 16, 2023 |
| Foxconn       | 2ABF                        | [e39cb5cf6f](https://linux-hardware.org/?probe=e39cb5cf6f) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [cc16045ed3](https://linux-hardware.org/?probe=cc16045ed3) | Jan 16, 2023 |
| ASUSTek       | PRIME Z270-A                | [8bdec78777](https://linux-hardware.org/?probe=8bdec78777) | Jan 16, 2023 |
| Medion        | MS-7728                     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| MSI           | A320M-A PRO                 | [01c0e96288](https://linux-hardware.org/?probe=01c0e96288) | Jan 16, 2023 |
| MSI           | MS-7369                     | [ab65628cf9](https://linux-hardware.org/?probe=ab65628cf9) | Jan 16, 2023 |
| Gigabyte      | EP45-DS4                    | [ef63262326](https://linux-hardware.org/?probe=ef63262326) | Jan 16, 2023 |
| Foxconn       | ALOE X3                     | [660a1aef16](https://linux-hardware.org/?probe=660a1aef16) | Jan 16, 2023 |
| ASRock        | Z77 Professional-M          | [9fa700364f](https://linux-hardware.org/?probe=9fa700364f) | Jan 16, 2023 |
| Gigabyte      | Z97X-Gaming G1              | [58c875e5d5](https://linux-hardware.org/?probe=58c875e5d5) | Jan 15, 2023 |
| Gigabyte      | EP45-DS4                    | [9feae23438](https://linux-hardware.org/?probe=9feae23438) | Jan 15, 2023 |
| MSI           | 2A9C                        | [7a4c26c267](https://linux-hardware.org/?probe=7a4c26c267) | Jan 15, 2023 |
| ASRock        | A520M-ITX/ac                | [ec3d18e6d6](https://linux-hardware.org/?probe=ec3d18e6d6) | Jan 15, 2023 |
| MSI           | MS-7369                     | [470e3a3eca](https://linux-hardware.org/?probe=470e3a3eca) | Jan 15, 2023 |
| MSI           | MAG B560M MORTAR            | [45da89106d](https://linux-hardware.org/?probe=45da89106d) | Jan 15, 2023 |
| Gigabyte      | H310M H x.x                 | [0b80c9ddfb](https://linux-hardware.org/?probe=0b80c9ddfb) | Jan 15, 2023 |
| HP            | 1589                        | [483338b531](https://linux-hardware.org/?probe=483338b531) | Jan 15, 2023 |
| Gigabyte      | H310M H                     | [30917eef19](https://linux-hardware.org/?probe=30917eef19) | Jan 15, 2023 |
| Gigabyte      | H81M-S2PV                   | [bddd00febc](https://linux-hardware.org/?probe=bddd00febc) | Jan 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [85048ce95d](https://linux-hardware.org/?probe=85048ce95d) | Jan 15, 2023 |
| MSI           | B75MA-E33                   | [d8d5ce1a20](https://linux-hardware.org/?probe=d8d5ce1a20) | Jan 15, 2023 |
| ASRock        | J3455-ITX                   | [3ffcbce83c](https://linux-hardware.org/?probe=3ffcbce83c) | Jan 15, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [d947dd4574](https://linux-hardware.org/?probe=d947dd4574) | Jan 14, 2023 |
| Lenovo        | SHARKBAY NOK                | [6334c715d0](https://linux-hardware.org/?probe=6334c715d0) | Jan 14, 2023 |
| MSI           | AM1I                        | [8f35d58735](https://linux-hardware.org/?probe=8f35d58735) | Jan 14, 2023 |
| MSI           | AM1I                        | [7dd360654f](https://linux-hardware.org/?probe=7dd360654f) | Jan 14, 2023 |
| ASUSTek       | P8H61-M LE/CSM              | [06aff9f10a](https://linux-hardware.org/?probe=06aff9f10a) | Jan 14, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [5534c879b6](https://linux-hardware.org/?probe=5534c879b6) | Jan 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b10c786457](https://linux-hardware.org/?probe=b10c786457) | Jan 14, 2023 |
| Gigabyte      | H310M H                     | [0ac9fa6100](https://linux-hardware.org/?probe=0ac9fa6100) | Jan 14, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [538493c537](https://linux-hardware.org/?probe=538493c537) | Jan 14, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [f4be2da4dc](https://linux-hardware.org/?probe=f4be2da4dc) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | [bd4516127b](https://linux-hardware.org/?probe=bd4516127b) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | [3c475bc193](https://linux-hardware.org/?probe=3c475bc193) | Jan 14, 2023 |
| MSI           | Z170A PC MATE               | [5cec973cb5](https://linux-hardware.org/?probe=5cec973cb5) | Jan 14, 2023 |
| MSI           | H510M-A PRO                 | [406649acdf](https://linux-hardware.org/?probe=406649acdf) | Jan 14, 2023 |
| HP            | 8643 SMVB                   | [81d232a246](https://linux-hardware.org/?probe=81d232a246) | Jan 14, 2023 |
| ASUSTek       | Z170-P D3                   | [990c8c732a](https://linux-hardware.org/?probe=990c8c732a) | Jan 13, 2023 |
| Dell          | 033FF6 A00                  | [7ec0ca850c](https://linux-hardware.org/?probe=7ec0ca850c) | Jan 13, 2023 |
| Dell          | 033FF6 A00                  | [b18da1bc5b](https://linux-hardware.org/?probe=b18da1bc5b) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [a399f30ea9](https://linux-hardware.org/?probe=a399f30ea9) | Jan 13, 2023 |
| Hardkernel    | ODROID-H3                   | [85d6a0b721](https://linux-hardware.org/?probe=85d6a0b721) | Jan 13, 2023 |
| Acer          | Aspire X1800                | [16f6ad749f](https://linux-hardware.org/?probe=16f6ad749f) | Jan 13, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [87740a6180](https://linux-hardware.org/?probe=87740a6180) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | [14d0dddfc9](https://linux-hardware.org/?probe=14d0dddfc9) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | [eb61471644](https://linux-hardware.org/?probe=eb61471644) | Jan 13, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [160f56a976](https://linux-hardware.org/?probe=160f56a976) | Jan 13, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [8243f25120](https://linux-hardware.org/?probe=8243f25120) | Jan 12, 2023 |
| Gigabyte      | H81M-S                      | [77fc83eb85](https://linux-hardware.org/?probe=77fc83eb85) | Jan 12, 2023 |
| MSI           | B450-A PRO MAX              | [4e4ba08946](https://linux-hardware.org/?probe=4e4ba08946) | Jan 12, 2023 |
| Intel         | DN2800MT AAG81515-900       | [546f31d89f](https://linux-hardware.org/?probe=546f31d89f) | Jan 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | [3dcb242fd6](https://linux-hardware.org/?probe=3dcb242fd6) | Jan 12, 2023 |
| ASUSTek       | M3N78-VM                    | [dad2489f95](https://linux-hardware.org/?probe=dad2489f95) | Jan 12, 2023 |
| Dell          | 0FM586                      | [529bc38dd7](https://linux-hardware.org/?probe=529bc38dd7) | Jan 12, 2023 |
| ASUSTek       | P5K                         | [ec9ba21c49](https://linux-hardware.org/?probe=ec9ba21c49) | Jan 12, 2023 |
| ASUSTek       | P8H77-M PRO                 | [24461e4b9f](https://linux-hardware.org/?probe=24461e4b9f) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LE                 | [de94c3e313](https://linux-hardware.org/?probe=de94c3e313) | Jan 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [374777ae60](https://linux-hardware.org/?probe=374777ae60) | Jan 12, 2023 |
| Gigabyte      | 970A-DS3P                   | [da4d50adca](https://linux-hardware.org/?probe=da4d50adca) | Jan 12, 2023 |
| ASUSTek       | M5A78L LE                   | [ea76077171](https://linux-hardware.org/?probe=ea76077171) | Jan 11, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [49863a504f](https://linux-hardware.org/?probe=49863a504f) | Jan 11, 2023 |
| ASUSTek       | F2A85-V                     | [0ddddc438d](https://linux-hardware.org/?probe=0ddddc438d) | Jan 11, 2023 |
| Unknown       | Unknown                     | [3696db52a7](https://linux-hardware.org/?probe=3696db52a7) | Jan 11, 2023 |
| MSI           | B350M GAMING PRO            | [df317ef3c8](https://linux-hardware.org/?probe=df317ef3c8) | Jan 11, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [f3fe7611d3](https://linux-hardware.org/?probe=f3fe7611d3) | Jan 11, 2023 |
| Gigabyte      | GA-970A-UD3                 | [eff09c2988](https://linux-hardware.org/?probe=eff09c2988) | Jan 10, 2023 |
| ASUSTek       | P5K                         | [64c746ef0b](https://linux-hardware.org/?probe=64c746ef0b) | Jan 10, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [247bb9fe04](https://linux-hardware.org/?probe=247bb9fe04) | Jan 10, 2023 |
| Medion        | MS-7728                     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| MSI           | PRO A320M-B                 | [3ffa3cf6f0](https://linux-hardware.org/?probe=3ffa3cf6f0) | Jan 10, 2023 |
| ASUSTek       | M2A-VM HDMI                 | [02524a1989](https://linux-hardware.org/?probe=02524a1989) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [74cafb7a17](https://linux-hardware.org/?probe=74cafb7a17) | Jan 10, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [3b99403f0f](https://linux-hardware.org/?probe=3b99403f0f) | Jan 10, 2023 |
| ASRock        | H110 Pro BTC+               | [685765625e](https://linux-hardware.org/?probe=685765625e) | Jan 10, 2023 |
| AZW           | EQ59                        | [3eb85d9ee5](https://linux-hardware.org/?probe=3eb85d9ee5) | Jan 10, 2023 |
| MSI           | A320M-A PRO                 | [16a4dc82f5](https://linux-hardware.org/?probe=16a4dc82f5) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [aabe4a2438](https://linux-hardware.org/?probe=aabe4a2438) | Jan 10, 2023 |
| MSI           | B350 KRAIT GAMING           | [d27b435baf](https://linux-hardware.org/?probe=d27b435baf) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | [66ffdd11c5](https://linux-hardware.org/?probe=66ffdd11c5) | Jan 10, 2023 |
| Dell          | 0GXM1W A01                  | [30b959cb78](https://linux-hardware.org/?probe=30b959cb78) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | [0a2fd6c8e7](https://linux-hardware.org/?probe=0a2fd6c8e7) | Jan 10, 2023 |
| Gigabyte      | B450 AORUS M                | [93377fdd79](https://linux-hardware.org/?probe=93377fdd79) | Jan 09, 2023 |
| ASUSTek       | M5A78L LE                   | [0b9c1c2841](https://linux-hardware.org/?probe=0b9c1c2841) | Jan 09, 2023 |
| ASUSTek       | H97I-PLUS                   | [9f7ce3b1a8](https://linux-hardware.org/?probe=9f7ce3b1a8) | Jan 09, 2023 |
| MSI           | B450-A PRO MAX              | [ce69e29b39](https://linux-hardware.org/?probe=ce69e29b39) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [6c7320f939](https://linux-hardware.org/?probe=6c7320f939) | Jan 09, 2023 |
| Dell          | 0PC5F7 A03                  | [e91fdfdeec](https://linux-hardware.org/?probe=e91fdfdeec) | Jan 09, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | [c434b0e62f](https://linux-hardware.org/?probe=c434b0e62f) | Jan 09, 2023 |
| Acer          | Aspire XC600 v1.0           | [1784713820](https://linux-hardware.org/?probe=1784713820) | Jan 09, 2023 |
| ASRock        | J3455-ITX                   | [7d3fc9bc9c](https://linux-hardware.org/?probe=7d3fc9bc9c) | Jan 09, 2023 |
| MSI           | B360M PRO-VDH               | [d89d83be55](https://linux-hardware.org/?probe=d89d83be55) | Jan 09, 2023 |
| ASRock        | J3455-ITX                   | [d818a8b895](https://linux-hardware.org/?probe=d818a8b895) | Jan 09, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [6e1a5dc6c1](https://linux-hardware.org/?probe=6e1a5dc6c1) | Jan 09, 2023 |
| MSI           | B450M MORTAR MAX            | [3698ce3c60](https://linux-hardware.org/?probe=3698ce3c60) | Jan 09, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [6666a9b8ca](https://linux-hardware.org/?probe=6666a9b8ca) | Jan 09, 2023 |
| ASRock        | Z390 Extreme4               | [a6f511ee0c](https://linux-hardware.org/?probe=a6f511ee0c) | Jan 09, 2023 |
| Dell          | 0VRWRC A01                  | [45e73c7052](https://linux-hardware.org/?probe=45e73c7052) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [22df883df4](https://linux-hardware.org/?probe=22df883df4) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [0e705ced6f](https://linux-hardware.org/?probe=0e705ced6f) | Jan 09, 2023 |
| Unknown       | SKYBAY                      | [e4674e61c5](https://linux-hardware.org/?probe=e4674e61c5) | Jan 09, 2023 |
| Dell          | 02YYK5 A01                  | [94f72348e6](https://linux-hardware.org/?probe=94f72348e6) | Jan 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [d5ab8c32a8](https://linux-hardware.org/?probe=d5ab8c32a8) | Jan 09, 2023 |
| MSI           | H97 GAMING 3                | [39ec0d3441](https://linux-hardware.org/?probe=39ec0d3441) | Jan 09, 2023 |
| ASUSTek       | PRIME Z690-A                | [d6e6c13962](https://linux-hardware.org/?probe=d6e6c13962) | Jan 08, 2023 |
| ASUSTek       | Z170-K                      | [896e860da1](https://linux-hardware.org/?probe=896e860da1) | Jan 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ffeb1d00b5](https://linux-hardware.org/?probe=ffeb1d00b5) | Jan 08, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | [60fab630ff](https://linux-hardware.org/?probe=60fab630ff) | Jan 08, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [df436102d6](https://linux-hardware.org/?probe=df436102d6) | Jan 08, 2023 |
| ASUSTek       | H110M-A                     | [d67718b4e8](https://linux-hardware.org/?probe=d67718b4e8) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [f0aa7955bf](https://linux-hardware.org/?probe=f0aa7955bf) | Jan 08, 2023 |
| ASRock        | Z390 Taichi Ultimate        | [347a359bbc](https://linux-hardware.org/?probe=347a359bbc) | Jan 07, 2023 |
| Foxconn       | ALOE X3                     | [45eefc8f36](https://linux-hardware.org/?probe=45eefc8f36) | Jan 07, 2023 |
| Dell          | 06D7TR A00                  | [788cefd1ac](https://linux-hardware.org/?probe=788cefd1ac) | Jan 07, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f811d71835](https://linux-hardware.org/?probe=f811d71835) | Jan 07, 2023 |
| MSI           | H77MA-G43                   | [cbd020e86f](https://linux-hardware.org/?probe=cbd020e86f) | Jan 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f9fe18f923](https://linux-hardware.org/?probe=f9fe18f923) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [ae3de33f00](https://linux-hardware.org/?probe=ae3de33f00) | Jan 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [aff5a2ce85](https://linux-hardware.org/?probe=aff5a2ce85) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7142941d7c](https://linux-hardware.org/?probe=7142941d7c) | Jan 07, 2023 |
| Gigabyte      | H610M H DDR4                | [f139bfc805](https://linux-hardware.org/?probe=f139bfc805) | Jan 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fd20c9e982](https://linux-hardware.org/?probe=fd20c9e982) | Jan 07, 2023 |
| Gigabyte      | B550M DS3H                  | [e2304eaaf2](https://linux-hardware.org/?probe=e2304eaaf2) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [926acf6b8b](https://linux-hardware.org/?probe=926acf6b8b) | Jan 07, 2023 |
| MSI           | 970A-G43                    | [550c10d749](https://linux-hardware.org/?probe=550c10d749) | Jan 07, 2023 |
| Intel         | DH61WW AAG23116-302         | [702bf83225](https://linux-hardware.org/?probe=702bf83225) | Jan 06, 2023 |
| ASUSTek       | P9X79                       | [24f9083bf8](https://linux-hardware.org/?probe=24f9083bf8) | Jan 06, 2023 |
| MSI           | IONA                        | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| Dell          | 0WR7PY A03                  | [54bba4d4a0](https://linux-hardware.org/?probe=54bba4d4a0) | Jan 06, 2023 |
| MSI           | IONA                        | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Intel         | DH55TC AAE70932-303         | [7831fb0431](https://linux-hardware.org/?probe=7831fb0431) | Jan 06, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [1720ed7ed6](https://linux-hardware.org/?probe=1720ed7ed6) | Jan 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2e6f75ca07](https://linux-hardware.org/?probe=2e6f75ca07) | Jan 06, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [3566221932](https://linux-hardware.org/?probe=3566221932) | Jan 06, 2023 |
| ASUSTek       | M5A97                       | [06ff3bed63](https://linux-hardware.org/?probe=06ff3bed63) | Jan 06, 2023 |
| Gigabyte      | H81M-S1                     | [db0e909d27](https://linux-hardware.org/?probe=db0e909d27) | Jan 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [e64152748d](https://linux-hardware.org/?probe=e64152748d) | Jan 06, 2023 |
| Foxconn       | ALOE X3                     | [6d7ee00b09](https://linux-hardware.org/?probe=6d7ee00b09) | Jan 06, 2023 |
| HP            | 1905                        | [01fb70526d](https://linux-hardware.org/?probe=01fb70526d) | Jan 06, 2023 |
| ASRock        | FM2A78 Pro4+                | [a2038e788c](https://linux-hardware.org/?probe=a2038e788c) | Jan 05, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [567e08a2d6](https://linux-hardware.org/?probe=567e08a2d6) | Jan 05, 2023 |
| Medion        | MS-7728                     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Dell          | 0Y3R3K A00                  | [8337b0691c](https://linux-hardware.org/?probe=8337b0691c) | Jan 05, 2023 |
| CncTion       | J4125-4L-I225               | [2d5bc452a4](https://linux-hardware.org/?probe=2d5bc452a4) | Jan 05, 2023 |
| ASUSTek       | M51AC                       | [8113ba1636](https://linux-hardware.org/?probe=8113ba1636) | Jan 05, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [03f117a662](https://linux-hardware.org/?probe=03f117a662) | Jan 05, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [4ff5066793](https://linux-hardware.org/?probe=4ff5066793) | Jan 05, 2023 |
| Lenovo        | ThinkStation S30 0606EG6    | [fbf769b1f8](https://linux-hardware.org/?probe=fbf769b1f8) | Jan 05, 2023 |
| Lenovo        | ThinkStation S30 0606EG6    | [02cbda88e9](https://linux-hardware.org/?probe=02cbda88e9) | Jan 05, 2023 |
| Gigabyte      | A520M DS3H                  | [e351ff5e1d](https://linux-hardware.org/?probe=e351ff5e1d) | Jan 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [b1132f1491](https://linux-hardware.org/?probe=b1132f1491) | Jan 04, 2023 |
| Dell          | 0TP412                      | [b608bcbdcf](https://linux-hardware.org/?probe=b608bcbdcf) | Jan 04, 2023 |
| HP            | 1998                        | [7c067688db](https://linux-hardware.org/?probe=7c067688db) | Jan 04, 2023 |
| HP            | 1998                        | [1eb07196f7](https://linux-hardware.org/?probe=1eb07196f7) | Jan 04, 2023 |
| Medion        | MS-7728                     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| Dell          | 0M9KCM A02                  | [dc9d77448b](https://linux-hardware.org/?probe=dc9d77448b) | Jan 04, 2023 |
| Unknown       | Unknown                     | [1e69c79d74](https://linux-hardware.org/?probe=1e69c79d74) | Jan 04, 2023 |
| Dell          | 06D7TR A00                  | [c633e2eeff](https://linux-hardware.org/?probe=c633e2eeff) | Jan 04, 2023 |
| Lenovo        | ThinkStation S30 05691K5    | [9e877a3e37](https://linux-hardware.org/?probe=9e877a3e37) | Jan 04, 2023 |
| Dell          | 0NW6H5 A00                  | [5d3c5f4546](https://linux-hardware.org/?probe=5d3c5f4546) | Jan 04, 2023 |
| Dell          | 0FM586                      | [7e181126bc](https://linux-hardware.org/?probe=7e181126bc) | Jan 03, 2023 |
| ASUSTek       | A68HM-K                     | [e73ee99f9d](https://linux-hardware.org/?probe=e73ee99f9d) | Jan 03, 2023 |
| Dell          | 0FM586                      | [fff469554f](https://linux-hardware.org/?probe=fff469554f) | Jan 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e9393e884](https://linux-hardware.org/?probe=0e9393e884) | Jan 03, 2023 |
| ASUSTek       | A68HM-K                     | [bfd9c22459](https://linux-hardware.org/?probe=bfd9c22459) | Jan 03, 2023 |
| MSI           | X370 SLI PLUS               | [14937af203](https://linux-hardware.org/?probe=14937af203) | Jan 03, 2023 |
| MSI           | X370 SLI PLUS               | [5daf353714](https://linux-hardware.org/?probe=5daf353714) | Jan 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [bd3d76fa53](https://linux-hardware.org/?probe=bd3d76fa53) | Jan 03, 2023 |
| Dell          | 0JP3NX A00                  | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
| Lenovo        | SKYBAY NOK                  | [29970ac3f3](https://linux-hardware.org/?probe=29970ac3f3) | Jan 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b557b201c4](https://linux-hardware.org/?probe=b557b201c4) | Jan 03, 2023 |
| Foxconn       | ALOE X3                     | [3293dc5a36](https://linux-hardware.org/?probe=3293dc5a36) | Jan 03, 2023 |
| Intel         | DH61BF AAG81311-101         | [db8d3007ee](https://linux-hardware.org/?probe=db8d3007ee) | Jan 03, 2023 |
| ASRock        | H77M                        | [b7f415926b](https://linux-hardware.org/?probe=b7f415926b) | Jan 03, 2023 |
| ASRock        | H77M                        | [82c399688f](https://linux-hardware.org/?probe=82c399688f) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [eefb2d0334](https://linux-hardware.org/?probe=eefb2d0334) | Jan 03, 2023 |
| MSI           | 2A9C                        | [48fc400420](https://linux-hardware.org/?probe=48fc400420) | Jan 03, 2023 |
| MSI           | 880GMA-E45                  | [f55d2f2c90](https://linux-hardware.org/?probe=f55d2f2c90) | Jan 03, 2023 |
| Dell          | 0K3CM7 A00                  | [7c58c84703](https://linux-hardware.org/?probe=7c58c84703) | Jan 02, 2023 |
| Pegatron      | Benicia                     | [25466113c1](https://linux-hardware.org/?probe=25466113c1) | Jan 02, 2023 |
| Dell          | 0RF703                      | [66180b5fdf](https://linux-hardware.org/?probe=66180b5fdf) | Jan 02, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [c733b1d34b](https://linux-hardware.org/?probe=c733b1d34b) | Jan 02, 2023 |
| HP            | 0AACh                       | [216ba22b5a](https://linux-hardware.org/?probe=216ba22b5a) | Jan 02, 2023 |
| Gigabyte      | H310M H                     | [8706565860](https://linux-hardware.org/?probe=8706565860) | Jan 02, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [7125f2d1da](https://linux-hardware.org/?probe=7125f2d1da) | Jan 02, 2023 |
| MSI           | PRO B660M-E DDR4            | [6ae9b30e34](https://linux-hardware.org/?probe=6ae9b30e34) | Jan 02, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d3bab9b69b](https://linux-hardware.org/?probe=d3bab9b69b) | Jan 02, 2023 |
| ASUSTek       | P8Z68-M PRO                 | [33b212da3e](https://linux-hardware.org/?probe=33b212da3e) | Jan 02, 2023 |
| MSI           | X470 GAMING PLUS            | [dd2c27605c](https://linux-hardware.org/?probe=dd2c27605c) | Jan 02, 2023 |
| ASUSTek       | PRIME Z370-A                | [72c7ec98c5](https://linux-hardware.org/?probe=72c7ec98c5) | Jan 02, 2023 |
| HP            | 0AACh                       | [0730634b36](https://linux-hardware.org/?probe=0730634b36) | Jan 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | [f252f31761](https://linux-hardware.org/?probe=f252f31761) | Jan 01, 2023 |
| Dell          | 0WMJ54 A01                  | [c6feaa89a0](https://linux-hardware.org/?probe=c6feaa89a0) | Jan 01, 2023 |
| Gigabyte      | H81M-DS2V                   | [8e5b57a9f8](https://linux-hardware.org/?probe=8e5b57a9f8) | Jan 01, 2023 |
| Foxconn       | 2AAF                        | [813a45dc50](https://linux-hardware.org/?probe=813a45dc50) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [b0e7bc419b](https://linux-hardware.org/?probe=b0e7bc419b) | Jan 01, 2023 |
| CncTion       | J4125-4L-I225               | [b10e1afdad](https://linux-hardware.org/?probe=b10e1afdad) | Jan 01, 2023 |
| Dell          | 0DF42J A00                  | [a3e1f5ed40](https://linux-hardware.org/?probe=a3e1f5ed40) | Jan 01, 2023 |
| Intel         | X79-SERVER V1.1             | [322b016537](https://linux-hardware.org/?probe=322b016537) | Jan 01, 2023 |
| MSI           | MS-B0A41                    | [c69ab6fbe8](https://linux-hardware.org/?probe=c69ab6fbe8) | Jan 01, 2023 |
| HP            | 802F                        | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Dell          | 0GWHMW A01                  | [59287847c9](https://linux-hardware.org/?probe=59287847c9) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [e18f6635d3](https://linux-hardware.org/?probe=e18f6635d3) | Dec 31, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [7c96c6776e](https://linux-hardware.org/?probe=7c96c6776e) | Dec 31, 2022 |
| Medion        | MS-7728                     | [3d6078552c](https://linux-hardware.org/?probe=3d6078552c) | Dec 31, 2022 |
| AZW           | U59                         | [39f0dfe71f](https://linux-hardware.org/?probe=39f0dfe71f) | Dec 31, 2022 |
| Intel         | DB75EN AAG39650-400         | [086831bbca](https://linux-hardware.org/?probe=086831bbca) | Dec 31, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [b4aecf5fa1](https://linux-hardware.org/?probe=b4aecf5fa1) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [afdda0ad31](https://linux-hardware.org/?probe=afdda0ad31) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [3659d7377d](https://linux-hardware.org/?probe=3659d7377d) | Dec 31, 2022 |
| ASUSTek       | P5Q-PRO                     | [cec0830928](https://linux-hardware.org/?probe=cec0830928) | Dec 31, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [c4059f2954](https://linux-hardware.org/?probe=c4059f2954) | Dec 31, 2022 |
| Dell          | 0GDG8Y A00                  | [8c8e9d66e7](https://linux-hardware.org/?probe=8c8e9d66e7) | Dec 30, 2022 |
| Dell          | 0XPDFK A01                  | [37d47ff0dc](https://linux-hardware.org/?probe=37d47ff0dc) | Dec 30, 2022 |
| Gigabyte      | A320M-H-CF                  | [b4511daea8](https://linux-hardware.org/?probe=b4511daea8) | Dec 30, 2022 |
| MSI           | Z87-G45 GAMING              | [c2d592a9e5](https://linux-hardware.org/?probe=c2d592a9e5) | Dec 30, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | [9c4b578c67](https://linux-hardware.org/?probe=9c4b578c67) | Dec 30, 2022 |
| MSI           | H61M-P22                    | [23b5356c0a](https://linux-hardware.org/?probe=23b5356c0a) | Dec 30, 2022 |
| ASRock        | 960GM-GS3 FX                | [1d8b5f0509](https://linux-hardware.org/?probe=1d8b5f0509) | Dec 30, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | [c352c59c64](https://linux-hardware.org/?probe=c352c59c64) | Dec 30, 2022 |
| ASUSTek       | G10DK                       | [5a5172ad44](https://linux-hardware.org/?probe=5a5172ad44) | Dec 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [47f838ca34](https://linux-hardware.org/?probe=47f838ca34) | Dec 30, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [a634defd54](https://linux-hardware.org/?probe=a634defd54) | Dec 30, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [b1bfc3d1ff](https://linux-hardware.org/?probe=b1bfc3d1ff) | Dec 30, 2022 |
| Intel         | X99                         | [ad6b288b38](https://linux-hardware.org/?probe=ad6b288b38) | Dec 30, 2022 |
| ASUSTek       | PRIME X399-A                | [d8ae46ad2b](https://linux-hardware.org/?probe=d8ae46ad2b) | Dec 30, 2022 |
| BESSTAR Te... | C-J34 Pro                   | [1b54a52c3c](https://linux-hardware.org/?probe=1b54a52c3c) | Dec 30, 2022 |
| ASUSTek       | G10DK                       | [26e2460b8d](https://linux-hardware.org/?probe=26e2460b8d) | Dec 29, 2022 |
| ASUSTek       | H81M-A                      | [10f0b28589](https://linux-hardware.org/?probe=10f0b28589) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| HP            | ProLiant ML110 Gen9         | [ea9aef1e8d](https://linux-hardware.org/?probe=ea9aef1e8d) | Dec 29, 2022 |
| HP            | 158A                        | [bfd338cf36](https://linux-hardware.org/?probe=bfd338cf36) | Dec 29, 2022 |
| HP            | ProLiant ML110 Gen9         | [728793a92a](https://linux-hardware.org/?probe=728793a92a) | Dec 29, 2022 |
| Pegatron      | 2AC2                        | [adc3978bcc](https://linux-hardware.org/?probe=adc3978bcc) | Dec 29, 2022 |
| Acer          | Aspire M3920                | [49cb4f51a8](https://linux-hardware.org/?probe=49cb4f51a8) | Dec 28, 2022 |
| Dell          | 0JP3NX A01                  | [3b094471e0](https://linux-hardware.org/?probe=3b094471e0) | Dec 28, 2022 |
| Intel         | X99                         | [eb6babb799](https://linux-hardware.org/?probe=eb6babb799) | Dec 28, 2022 |
| ASUSTek       | G10DK                       | [1ffb248d93](https://linux-hardware.org/?probe=1ffb248d93) | Dec 28, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| Lanix         | P55M-UD2 LNXACT             | [5575ce838c](https://linux-hardware.org/?probe=5575ce838c) | Dec 28, 2022 |
| HP            | 0A54h                       | [7f1e1152d9](https://linux-hardware.org/?probe=7f1e1152d9) | Dec 28, 2022 |
| MSI           | Z270 PC MATE                | [08186ccafe](https://linux-hardware.org/?probe=08186ccafe) | Dec 28, 2022 |
| ASRock        | B75 Pro3-M                  | [108f0c24de](https://linux-hardware.org/?probe=108f0c24de) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6297565fda](https://linux-hardware.org/?probe=6297565fda) | Dec 28, 2022 |
| MSI           | Z370 PC PRO                 | [367bcf2d16](https://linux-hardware.org/?probe=367bcf2d16) | Dec 28, 2022 |
| Dell          | 0HY9JP A01                  | [97a3e6ce9d](https://linux-hardware.org/?probe=97a3e6ce9d) | Dec 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [20c0841830](https://linux-hardware.org/?probe=20c0841830) | Dec 28, 2022 |
| HP            | 1905                        | [5c576316f8](https://linux-hardware.org/?probe=5c576316f8) | Dec 28, 2022 |
| Gigabyte      | A320M-H-CF                  | [aff2b93aa5](https://linux-hardware.org/?probe=aff2b93aa5) | Dec 28, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [d680b8dd2a](https://linux-hardware.org/?probe=d680b8dd2a) | Dec 28, 2022 |
| ASRock        | B450M Pro4                  | [fcaf938a12](https://linux-hardware.org/?probe=fcaf938a12) | Dec 28, 2022 |
| Acer          | Aspire M3970                | [c2232f44d6](https://linux-hardware.org/?probe=c2232f44d6) | Dec 27, 2022 |
| ASUSTek       | H97I-PLUS                   | [8f039f1be9](https://linux-hardware.org/?probe=8f039f1be9) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [41b062ea94](https://linux-hardware.org/?probe=41b062ea94) | Dec 27, 2022 |
| Gigabyte      | H270-HD3-CF                 | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| Dell          | 0PTTT9 A01                  | [78512365ca](https://linux-hardware.org/?probe=78512365ca) | Dec 26, 2022 |
| NCR           | Pocono                      | [d50ad710fb](https://linux-hardware.org/?probe=d50ad710fb) | Dec 26, 2022 |
| Gigabyte      | M61SME-S2                   | [5d0485ba40](https://linux-hardware.org/?probe=5d0485ba40) | Dec 26, 2022 |
| ASUSTek       | G10DK                       | [30007c6ff0](https://linux-hardware.org/?probe=30007c6ff0) | Dec 26, 2022 |
| Gigabyte      | M61SME-S2                   | [d68451099d](https://linux-hardware.org/?probe=d68451099d) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | [aef3959b18](https://linux-hardware.org/?probe=aef3959b18) | Dec 26, 2022 |
| Gigabyte      | GB-BRR7H-4700               | [43c2d92e5f](https://linux-hardware.org/?probe=43c2d92e5f) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eda96539d7](https://linux-hardware.org/?probe=eda96539d7) | Dec 26, 2022 |
| HP            | 1495                        | [b8e1dc67eb](https://linux-hardware.org/?probe=b8e1dc67eb) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [b181e9e5a3](https://linux-hardware.org/?probe=b181e9e5a3) | Dec 26, 2022 |
| Unknown       | HX90                        | [d4265ad971](https://linux-hardware.org/?probe=d4265ad971) | Dec 26, 2022 |
| Gigabyte      | Z97M-DS3H                   | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| HP            | 304Ah                       | [6106d55390](https://linux-hardware.org/?probe=6106d55390) | Dec 26, 2022 |
| MSI           | B350 KRAIT GAMING           | [896aebf101](https://linux-hardware.org/?probe=896aebf101) | Dec 25, 2022 |
| Gigabyte      | H61M-S1                     | [384000d018](https://linux-hardware.org/?probe=384000d018) | Dec 25, 2022 |
| ASRock        | H110 Pro BTC+               | [29311fe64c](https://linux-hardware.org/?probe=29311fe64c) | Dec 25, 2022 |
| Gateway       | G33M05G1 MP                 | [8a495d2b75](https://linux-hardware.org/?probe=8a495d2b75) | Dec 25, 2022 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | [fee0a76158](https://linux-hardware.org/?probe=fee0a76158) | Dec 25, 2022 |
| MSI           | Boston                      | [5ffbd4e9a5](https://linux-hardware.org/?probe=5ffbd4e9a5) | Dec 25, 2022 |
| Dell          | 0MN1TX A02                  | [513af674c0](https://linux-hardware.org/?probe=513af674c0) | Dec 25, 2022 |
| HP            | ProLiant ML110 Gen9         | [90bb379f4e](https://linux-hardware.org/?probe=90bb379f4e) | Dec 25, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | [61be8271df](https://linux-hardware.org/?probe=61be8271df) | Dec 25, 2022 |
| Foxconn       | 2ADA                        | [7a7d8227ee](https://linux-hardware.org/?probe=7a7d8227ee) | Dec 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [1762f53462](https://linux-hardware.org/?probe=1762f53462) | Dec 25, 2022 |
| ASRock        | H110 Pro BTC+               | [90f3fd2f80](https://linux-hardware.org/?probe=90f3fd2f80) | Dec 25, 2022 |
| ASUSTek       | G10DK                       | [13379a69a6](https://linux-hardware.org/?probe=13379a69a6) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e12a45a65f](https://linux-hardware.org/?probe=e12a45a65f) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [4f28247dcb](https://linux-hardware.org/?probe=4f28247dcb) | Dec 25, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0900400806](https://linux-hardware.org/?probe=0900400806) | Dec 25, 2022 |
| Dell          | 040DDP A01                  | [2fc87b6525](https://linux-hardware.org/?probe=2fc87b6525) | Dec 25, 2022 |
| Supermicro    | C2SBX                       | [1b275899d5](https://linux-hardware.org/?probe=1b275899d5) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [571019b4b2](https://linux-hardware.org/?probe=571019b4b2) | Dec 25, 2022 |
| Dell          | 0D6H9T A00                  | [778c642778](https://linux-hardware.org/?probe=778c642778) | Dec 25, 2022 |
| Dell          | 0D6H9T A00                  | [ef62b12cdb](https://linux-hardware.org/?probe=ef62b12cdb) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-A               | [1fc8c5a4d4](https://linux-hardware.org/?probe=1fc8c5a4d4) | Dec 24, 2022 |
| ASUSTek       | P8H67-M LE                  | [892d40f349](https://linux-hardware.org/?probe=892d40f349) | Dec 24, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [7edfc4df26](https://linux-hardware.org/?probe=7edfc4df26) | Dec 24, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [7f19b0ef63](https://linux-hardware.org/?probe=7f19b0ef63) | Dec 24, 2022 |
| ASUSTek       | P8H67-M LE                  | [7517437358](https://linux-hardware.org/?probe=7517437358) | Dec 24, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5047d29893](https://linux-hardware.org/?probe=5047d29893) | Dec 24, 2022 |
| MSI           | TRX40 PRO 10G               | [f83cf989ef](https://linux-hardware.org/?probe=f83cf989ef) | Dec 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3dce1a76e7](https://linux-hardware.org/?probe=3dce1a76e7) | Dec 24, 2022 |
| Dell          | 0NW6H5 A00                  | [6c7eeae2e3](https://linux-hardware.org/?probe=6c7eeae2e3) | Dec 23, 2022 |
| Dell          | 0PTTT9 A01                  | [4618f09759](https://linux-hardware.org/?probe=4618f09759) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [7fe5933133](https://linux-hardware.org/?probe=7fe5933133) | Dec 23, 2022 |
| Dell          | 0WMJ54 A01                  | [b0b07249ae](https://linux-hardware.org/?probe=b0b07249ae) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| MSI           | H510M BOMBER                | [bb7a4c8457](https://linux-hardware.org/?probe=bb7a4c8457) | Dec 23, 2022 |
| MSI           | A78M-E35                    | [8eeb54e414](https://linux-hardware.org/?probe=8eeb54e414) | Dec 23, 2022 |
| ASRock        | Z97 Anniversary             | [c4e60094f3](https://linux-hardware.org/?probe=c4e60094f3) | Dec 23, 2022 |
| Dell          | 05GD68 A00                  | [a868fc6557](https://linux-hardware.org/?probe=a868fc6557) | Dec 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [23f2e15649](https://linux-hardware.org/?probe=23f2e15649) | Dec 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [61b7eaac72](https://linux-hardware.org/?probe=61b7eaac72) | Dec 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [08d715eaea](https://linux-hardware.org/?probe=08d715eaea) | Dec 22, 2022 |
| ASRock        | A320M-HD                    | [5307c53c91](https://linux-hardware.org/?probe=5307c53c91) | Dec 22, 2022 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e486047e83](https://linux-hardware.org/?probe=e486047e83) | Dec 22, 2022 |
| Dell          | 00V62H A01                  | [296edfbde5](https://linux-hardware.org/?probe=296edfbde5) | Dec 22, 2022 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [abb4201228](https://linux-hardware.org/?probe=abb4201228) | Dec 22, 2022 |
| ASRock        | N68-GE3 UCC                 | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| ASRock        | FM2A75 Pro4                 | [88062c13c8](https://linux-hardware.org/?probe=88062c13c8) | Dec 22, 2022 |
| Dell          | 05GD68 A00                  | [4589f84dfd](https://linux-hardware.org/?probe=4589f84dfd) | Dec 21, 2022 |
| MSI           | H97M-G43                    | [a34bd69442](https://linux-hardware.org/?probe=a34bd69442) | Dec 21, 2022 |
| eMachines     | ET1331                      | [0f9b49ac6e](https://linux-hardware.org/?probe=0f9b49ac6e) | Dec 21, 2022 |
| MSI           | A320M-A PRO                 | [88eb56085f](https://linux-hardware.org/?probe=88eb56085f) | Dec 21, 2022 |
| Gigabyte      | H170M-DS3H-CF               | [714dafad38](https://linux-hardware.org/?probe=714dafad38) | Dec 21, 2022 |
| MSI           | MAG B560M MORTAR            | [9b1e668d0a](https://linux-hardware.org/?probe=9b1e668d0a) | Dec 21, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [4d24d45918](https://linux-hardware.org/?probe=4d24d45918) | Dec 21, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [cfeb9545a3](https://linux-hardware.org/?probe=cfeb9545a3) | Dec 21, 2022 |
| MSI           | B250M GAMING PRO            | [76fd6916b6](https://linux-hardware.org/?probe=76fd6916b6) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [cb7cb7b7d7](https://linux-hardware.org/?probe=cb7cb7b7d7) | Dec 21, 2022 |
| MSI           | B250M GAMING PRO            | [9ae81949ed](https://linux-hardware.org/?probe=9ae81949ed) | Dec 21, 2022 |
| MSI           | B250M GAMING PRO            | [15f51cd9d9](https://linux-hardware.org/?probe=15f51cd9d9) | Dec 21, 2022 |
| Gigabyte      | B75M-D3H                    | [77bf96f401](https://linux-hardware.org/?probe=77bf96f401) | Dec 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [17630a4351](https://linux-hardware.org/?probe=17630a4351) | Dec 20, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [8a09a51987](https://linux-hardware.org/?probe=8a09a51987) | Dec 20, 2022 |
| Alienware     | 07JNH0 A02                  | [558828391f](https://linux-hardware.org/?probe=558828391f) | Dec 20, 2022 |
| ASUSTek       | H81M-C                      | [9ae92c3b1e](https://linux-hardware.org/?probe=9ae92c3b1e) | Dec 20, 2022 |
| Dell          | 0Y2K8N A00                  | [840fbab6e4](https://linux-hardware.org/?probe=840fbab6e4) | Dec 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [1f8d567742](https://linux-hardware.org/?probe=1f8d567742) | Dec 20, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dd024e0315](https://linux-hardware.org/?probe=dd024e0315) | Dec 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6a731c5c9b](https://linux-hardware.org/?probe=6a731c5c9b) | Dec 20, 2022 |
| Dell          | 0D6H9T A03                  | [835cdeea5e](https://linux-hardware.org/?probe=835cdeea5e) | Dec 19, 2022 |
| HP            | 0AA8h                       | [f04f3c4d42](https://linux-hardware.org/?probe=f04f3c4d42) | Dec 19, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [d7a2fa6abf](https://linux-hardware.org/?probe=d7a2fa6abf) | Dec 19, 2022 |
| Gigabyte      | B85-HD3                     | [a8d78baa67](https://linux-hardware.org/?probe=a8d78baa67) | Dec 19, 2022 |
| ASRock        | Z170 Extreme6+              | [74b4357180](https://linux-hardware.org/?probe=74b4357180) | Dec 19, 2022 |
| MSI           | B350 PC MATE                | [9bdee62034](https://linux-hardware.org/?probe=9bdee62034) | Dec 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [cc8dd14279](https://linux-hardware.org/?probe=cc8dd14279) | Dec 19, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [fcd0306cd3](https://linux-hardware.org/?probe=fcd0306cd3) | Dec 19, 2022 |
| MSI           | X399 SLI PLUS               | [fdf00892eb](https://linux-hardware.org/?probe=fdf00892eb) | Dec 19, 2022 |
| Gigabyte      | 970A-UD3P                   | [7d5ca26325](https://linux-hardware.org/?probe=7d5ca26325) | Dec 19, 2022 |
| Gigabyte      | 970A-UD3P                   | [0690e94fd6](https://linux-hardware.org/?probe=0690e94fd6) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| ASUSTek       | H170-PRO                    | [3d866a7ec8](https://linux-hardware.org/?probe=3d866a7ec8) | Dec 19, 2022 |
| ASRock        | H110 Pro BTC+               | [b44ba7da8e](https://linux-hardware.org/?probe=b44ba7da8e) | Dec 19, 2022 |
| HP            | 8597                        | [5a7ae7c6d7](https://linux-hardware.org/?probe=5a7ae7c6d7) | Dec 19, 2022 |
| Gigabyte      | B650M GAMING X AX           | [01b7250cea](https://linux-hardware.org/?probe=01b7250cea) | Dec 19, 2022 |
| Gigabyte      | B650M GAMING X AX           | [999cbfe9f7](https://linux-hardware.org/?probe=999cbfe9f7) | Dec 19, 2022 |
| HP            | 18E7                        | [9f601a9f1a](https://linux-hardware.org/?probe=9f601a9f1a) | Dec 19, 2022 |
| ASUSTek       | Z87-A                       | [17c2f5c3b2](https://linux-hardware.org/?probe=17c2f5c3b2) | Dec 19, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | [7020686bc7](https://linux-hardware.org/?probe=7020686bc7) | Dec 19, 2022 |
| Intel         | DH61BE AAG14062-206         | [88125550fb](https://linux-hardware.org/?probe=88125550fb) | Dec 19, 2022 |
| HP            | 0AA8h                       | [0c11d6bb2a](https://linux-hardware.org/?probe=0c11d6bb2a) | Dec 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [6870f7c47f](https://linux-hardware.org/?probe=6870f7c47f) | Dec 18, 2022 |
| Dell          | 0M858N A00                  | [2eb73cbb7a](https://linux-hardware.org/?probe=2eb73cbb7a) | Dec 18, 2022 |
| Intel         | HM570                       | [627a39bc3f](https://linux-hardware.org/?probe=627a39bc3f) | Dec 18, 2022 |
| Alienware     | 02XRCM A02                  | [ece4e302f1](https://linux-hardware.org/?probe=ece4e302f1) | Dec 18, 2022 |
| Intel         | HM570                       | [303e68f585](https://linux-hardware.org/?probe=303e68f585) | Dec 18, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [bdea23d60e](https://linux-hardware.org/?probe=bdea23d60e) | Dec 18, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [41da62e6ca](https://linux-hardware.org/?probe=41da62e6ca) | Dec 18, 2022 |
| ASRock        | AM1H-ITX                    | [88fc771e47](https://linux-hardware.org/?probe=88fc771e47) | Dec 18, 2022 |
| MSI           | B250M PRO-VDH               | [14ea50f3b2](https://linux-hardware.org/?probe=14ea50f3b2) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [0d4ba683ce](https://linux-hardware.org/?probe=0d4ba683ce) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [caaddcd344](https://linux-hardware.org/?probe=caaddcd344) | Dec 18, 2022 |
| Intel         | DH55TC AAE70932-303         | [631f80f725](https://linux-hardware.org/?probe=631f80f725) | Dec 18, 2022 |
| Intel         | DG31PR AAD97573-206         | [3684f593d4](https://linux-hardware.org/?probe=3684f593d4) | Dec 18, 2022 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | [15f724ada5](https://linux-hardware.org/?probe=15f724ada5) | Dec 18, 2022 |
| HP            | 8054                        | [a43a5ed0ec](https://linux-hardware.org/?probe=a43a5ed0ec) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [694e433518](https://linux-hardware.org/?probe=694e433518) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [801a4e21c6](https://linux-hardware.org/?probe=801a4e21c6) | Dec 18, 2022 |
| MSI           | MS-7360                     | [2f5a9baf11](https://linux-hardware.org/?probe=2f5a9baf11) | Dec 18, 2022 |
| MSI           | A78M-E35                    | [e67bafe6b9](https://linux-hardware.org/?probe=e67bafe6b9) | Dec 18, 2022 |
| ASUSTek       | P8Z77-V LK                  | [c106327357](https://linux-hardware.org/?probe=c106327357) | Dec 18, 2022 |
| ASUSTek       | PRIME H370M-PLUS            | [784f59e142](https://linux-hardware.org/?probe=784f59e142) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [e5525b45b5](https://linux-hardware.org/?probe=e5525b45b5) | Dec 18, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [a69cb4caca](https://linux-hardware.org/?probe=a69cb4caca) | Dec 17, 2022 |
| Dell          | 0CRH6C A02                  | [4072754835](https://linux-hardware.org/?probe=4072754835) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [fa03fe621a](https://linux-hardware.org/?probe=fa03fe621a) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [8480834751](https://linux-hardware.org/?probe=8480834751) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [67d1ddeefb](https://linux-hardware.org/?probe=67d1ddeefb) | Dec 17, 2022 |
| ASRock        | Z77 Pro4                    | [42cd781d07](https://linux-hardware.org/?probe=42cd781d07) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | [a38c2f49be](https://linux-hardware.org/?probe=a38c2f49be) | Dec 17, 2022 |
| ASUSTek       | PRIME Q270M-C               | [7dca31fdef](https://linux-hardware.org/?probe=7dca31fdef) | Dec 17, 2022 |
| MSI           | PRO B660M-E DDR4            | [3f4e01746b](https://linux-hardware.org/?probe=3f4e01746b) | Dec 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-56-generic      | 284      | 10.43%  |
| 5.15.0-52-generic      | 250      | 9.18%   |
| 5.15.0-58-generic      | 219      | 8.04%   |
| 5.15.0-48-generic      | 200      | 7.34%   |
| 5.15.0-47-generic      | 196      | 7.2%    |
| 5.15.0-43-generic      | 172      | 6.31%   |
| 5.15.0-53-generic      | 150      | 5.51%   |
| 5.15.0-46-generic      | 129      | 4.74%   |
| 5.15.0-27-generic      | 102      | 3.74%   |
| 5.15.0-25-generic      | 100      | 3.67%   |
| 5.19.0-32-generic      | 98       | 3.6%    |
| 5.15.0-41-generic      | 93       | 3.41%   |
| 5.15.0-40-generic      | 91       | 3.34%   |
| 5.15.0-60-generic      | 85       | 3.12%   |
| 5.15.0-57-generic      | 81       | 2.97%   |
| 5.15.0-50-generic      | 79       | 2.9%    |
| 5.15.0-33-generic      | 60       | 2.2%    |
| 5.15.0-30-generic      | 53       | 1.95%   |
| 5.15.0-39-generic      | 46       | 1.69%   |
| 5.15.0-35-generic      | 44       | 1.62%   |
| 5.15.0-37-generic      | 41       | 1.51%   |
| 5.15.0-23-generic      | 12       | 0.44%   |
| 5.15.0-18-generic      | 9        | 0.33%   |
| 5.15.0-32-generic      | 7        | 0.26%   |
| 5.13.0-19-generic      | 7        | 0.26%   |
| 5.17.0-1020-oem        | 6        | 0.22%   |
| 5.15.0-54-generic      | 4        | 0.15%   |
| 5.15.0-28-generic      | 4        | 0.15%   |
| 5.18.10-051810-generic | 3        | 0.11%   |
| 5.18.0-051800-generic  | 3        | 0.11%   |
| 5.15.0-45-generic      | 3        | 0.11%   |
| 5.15.0-22-generic      | 3        | 0.11%   |
| 6.0.9-060009-generic   | 2        | 0.07%   |
| 5.19.5-051905-generic  | 2        | 0.07%   |
| 5.19.17-051917-generic | 2        | 0.07%   |
| 5.19.0-051900-generic  | 2        | 0.07%   |
| 5.17.15-051715-generic | 2        | 0.07%   |
| 5.17.0-1013-oem        | 2        | 0.07%   |
| 5.17.0-051700-generic  | 2        | 0.07%   |
| 5.15.13-051513-generic | 2        | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2292     | 92.64%  |
| 5.19.0  | 101      | 4.08%   |
| 5.17.0  | 19       | 0.77%   |
| 5.13.0  | 14       | 0.57%   |
| 6.0.0   | 4        | 0.16%   |
| 5.18.0  | 4        | 0.16%   |
| 5.18.10 | 3        | 0.12%   |
| 6.0.9   | 2        | 0.08%   |
| 5.8.0   | 2        | 0.08%   |
| 5.19.5  | 2        | 0.08%   |
| 5.19.17 | 2        | 0.08%   |
| 5.17.9  | 2        | 0.08%   |
| 5.17.15 | 2        | 0.08%   |
| 5.15.13 | 2        | 0.08%   |
| 6.2.1   | 1        | 0.04%   |
| 6.2.0   | 1        | 0.04%   |
| 6.1.8   | 1        | 0.04%   |
| 6.1.6   | 1        | 0.04%   |
| 6.1.4   | 1        | 0.04%   |
| 6.0.8   | 1        | 0.04%   |
| 6.0.1   | 1        | 0.04%   |
| 5.4.0   | 1        | 0.04%   |
| 5.19.3  | 1        | 0.04%   |
| 5.18.8  | 1        | 0.04%   |
| 5.18.3  | 1        | 0.04%   |
| 5.18.13 | 1        | 0.04%   |
| 5.18.1  | 1        | 0.04%   |
| 5.17.7  | 1        | 0.04%   |
| 5.17.5  | 1        | 0.04%   |
| 5.17.4  | 1        | 0.04%   |
| 5.17.2  | 1        | 0.04%   |
| 5.17.14 | 1        | 0.04%   |
| 5.17.1  | 1        | 0.04%   |
| 5.16.0  | 1        | 0.04%   |
| 5.14.0  | 1        | 0.04%   |
| 5.11.0  | 1        | 0.04%   |
| 5.10.60 | 1        | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2294     | 92.76%  |
| 5.19    | 106      | 4.29%   |
| 5.17    | 28       | 1.13%   |
| 5.13    | 14       | 0.57%   |
| 5.18    | 11       | 0.44%   |
| 6.0     | 8        | 0.32%   |
| 6.1     | 3        | 0.12%   |
| 6.2     | 2        | 0.08%   |
| 5.8     | 2        | 0.08%   |
| 5.4     | 1        | 0.04%   |
| 5.16    | 1        | 0.04%   |
| 5.14    | 1        | 0.04%   |
| 5.11    | 1        | 0.04%   |
| 5.10    | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2452     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 2283     | 93.07%  |
| Unknown         | 124      | 5.06%   |
| X-Cinnamon      | 24       | 0.98%   |
| GNOME Flashback | 9        | 0.37%   |
| GNOME Classic   | 6        | 0.24%   |
| i3              | 3        | 0.12%   |
| ubuntu=GNOME    | 1        | 0.04%   |
| ubuntu          | 1        | 0.04%   |
| i3-with-shmlog  | 1        | 0.04%   |
| awesome         | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1347     | 53.92%  |
| X11     | 1004     | 40.19%  |
| Tty     | 95       | 3.8%    |
| Unknown | 51       | 2.04%   |
| Web     | 1        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 2174     | 88.52%  |
| Unknown | 221      | 9%      |
| LightDM | 35       | 1.43%   |
| SDDM    | 11       | 0.45%   |
| GDM     | 11       | 0.45%   |
| SLiM    | 3        | 0.12%   |
| LXDM    | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1062     | 43.19%  |
| de_DE   | 239      | 9.72%   |
| fr_FR   | 156      | 6.34%   |
| en_GB   | 127      | 5.16%   |
| pt_BR   | 96       | 3.9%    |
| it_IT   | 92       | 3.74%   |
| en_CA   | 71       | 2.89%   |
| ru_RU   | 68       | 2.77%   |
| es_ES   | 63       | 2.56%   |
| en_AU   | 39       | 1.59%   |
| en_IN   | 37       | 1.5%    |
| pl_PL   | 36       | 1.46%   |
| cs_CZ   | 25       | 1.02%   |
| nl_NL   | 24       | 0.98%   |
| C       | 24       | 0.98%   |
| sv_SE   | 19       | 0.77%   |
| ja_JP   | 19       | 0.77%   |
| es_MX   | 15       | 0.61%   |
| de_AT   | 15       | 0.61%   |
| Unknown | 15       | 0.61%   |
| zh_CN   | 14       | 0.57%   |
| es_AR   | 14       | 0.57%   |
| en_ZA   | 14       | 0.57%   |
| hu_HU   | 11       | 0.45%   |
| fr_BE   | 11       | 0.45%   |
| fi_FI   | 11       | 0.45%   |
| nl_BE   | 9        | 0.37%   |
| el_GR   | 9        | 0.37%   |
| de_CH   | 9        | 0.37%   |
| tr_TR   | 8        | 0.33%   |
| pt_PT   | 8        | 0.33%   |
| en_PH   | 8        | 0.33%   |
| fr_CA   | 7        | 0.28%   |
| ko_KR   | 6        | 0.24%   |
| en_NZ   | 6        | 0.24%   |
| sk_SK   | 5        | 0.2%    |
| es_VE   | 4        | 0.16%   |
| es_CO   | 4        | 0.16%   |
| zh_TW   | 3        | 0.12%   |
| ro_RO   | 3        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1790     | 72.24%  |
| EFI  | 688      | 27.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 2257     | 91.79%  |
| Overlay       | 72       | 2.93%   |
| Zfs           | 63       | 2.56%   |
| Btrfs         | 33       | 1.34%   |
| Xfs           | 21       | 0.85%   |
| Ext2          | 6        | 0.24%   |
| Tmpfs         | 2        | 0.08%   |
| XXXX          | 1        | 0.04%   |
| Jfs           | 1        | 0.04%   |
| Fuse.snapfuse | 1        | 0.04%   |
| Ext3          | 1        | 0.04%   |
| Unknown       | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1442     | 56.57%  |
| Unknown | 860      | 33.74%  |
| MBR     | 247      | 9.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2016     | 81.29%  |
| Yes       | 464      | 18.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1403     | 56.66%  |
| Yes       | 1073     | 43.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 602      | 24.55%  |
| Gigabyte Technology | 382      | 15.58%  |
| MSI                 | 320      | 13.05%  |
| Dell                | 265      | 10.81%  |
| Hewlett-Packard     | 192      | 7.83%   |
| ASRock              | 185      | 7.54%   |
| Lenovo              | 101      | 4.12%   |
| Intel               | 62       | 2.53%   |
| Acer                | 55       | 2.24%   |
| Unknown             | 30       | 1.22%   |
| Fujitsu             | 28       | 1.14%   |
| Pegatron            | 22       | 0.9%    |
| Medion              | 22       | 0.9%    |
| Foxconn             | 21       | 0.86%   |
| Biostar             | 13       | 0.53%   |
| Shuttle             | 12       | 0.49%   |
| Apple               | 12       | 0.49%   |
| Alienware           | 12       | 0.49%   |
| Supermicro          | 10       | 0.41%   |
| Huanan              | 10       | 0.41%   |
| ECS                 | 9        | 0.37%   |
| BESSTAR Tech        | 7        | 0.29%   |
| AZW                 | 6        | 0.24%   |
| Positivo            | 5        | 0.2%    |
| Gateway             | 5        | 0.2%    |
| Packard Bell        | 4        | 0.16%   |
| ASRockRack          | 4        | 0.16%   |
| OEM                 | 3        | 0.12%   |
| eMachines           | 3        | 0.12%   |
| Protectli           | 2        | 0.08%   |
| NCR                 | 2        | 0.08%   |
| MiTAC               | 2        | 0.08%   |
| Maxtang             | 2        | 0.08%   |
| LattePanda          | 2        | 0.08%   |
| Google              | 2        | 0.08%   |
| Fujitsu Siemens     | 2        | 0.08%   |
| AMI                 | 2        | 0.08%   |
| YANYU               | 1        | 0.04%   |
| XDO.AI              | 1        | 0.04%   |
| WTM                 | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 63       | 2.57%   |
| Unknown                      | 35       | 1.43%   |
| Dell OptiPlex 7010           | 25       | 1.02%   |
| ASUS PRIME A320M-K           | 18       | 0.73%   |
| MSI MS-7721                  | 17       | 0.69%   |
| ASUS TUF Gaming X570-PLUS    | 16       | 0.65%   |
| Dell OptiPlex 3020           | 15       | 0.61%   |
| MSI MS-7C37                  | 14       | 0.57%   |
| Dell OptiPlex 9020           | 13       | 0.53%   |
| Dell OptiPlex 790            | 13       | 0.53%   |
| HP Compaq 8200 Elite SFF PC  | 11       | 0.45%   |
| ASUS ROG STRIX B550-F GAMING | 11       | 0.45%   |
| MSI MS-7C91                  | 10       | 0.41%   |
| MSI MS-7C52                  | 9        | 0.37%   |
| Gigabyte B450M DS3H          | 9        | 0.37%   |
| ASUS M5A78L-M/USB3           | 9        | 0.37%   |
| ASRock B450M Pro4            | 9        | 0.37%   |
| MSI MS-7C02                  | 8        | 0.33%   |
| MSI MS-7817                  | 8        | 0.33%   |
| MSI MS-7693                  | 8        | 0.33%   |
| HP ProDesk 600 G1 SFF        | 8        | 0.33%   |
| Dell OptiPlex 7050           | 8        | 0.33%   |
| MSI MS-7B86                  | 7        | 0.29%   |
| MSI MS-7B79                  | 7        | 0.29%   |
| Intel H61                    | 7        | 0.29%   |
| HP Z440 Workstation          | 7        | 0.29%   |
| HP Compaq Pro 6300 SFF       | 7        | 0.29%   |
| Dell OptiPlex 990            | 7        | 0.29%   |
| Dell OptiPlex 9010           | 7        | 0.29%   |
| Dell OptiPlex 780            | 7        | 0.29%   |
| MSI MS-7C51                  | 6        | 0.24%   |
| MSI MS-7C35                  | 6        | 0.24%   |
| HP EliteDesk 800 G1 SFF      | 6        | 0.24%   |
| HP Compaq Pro 6300 MT        | 6        | 0.24%   |
| Gigabyte B75M-D3H            | 6        | 0.24%   |
| Gigabyte 970A-DS3P           | 6        | 0.24%   |
| Dell OptiPlex 7040           | 6        | 0.24%   |
| Dell OptiPlex 3050           | 6        | 0.24%   |
| ASUS ROG STRIX X570-E GAMING | 6        | 0.24%   |
| ASUS ROG STRIX B450-F GAMING | 6        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 163      | 6.65%   |
| ASUS PRIME          | 111      | 4.53%   |
| ASUS ROG            | 68       | 2.77%   |
| HP Compaq           | 67       | 2.73%   |
| ASUS All            | 63       | 2.57%   |
| ASUS TUF            | 61       | 2.49%   |
| Lenovo ThinkCentre  | 53       | 2.16%   |
| Dell Precision      | 41       | 1.67%   |
| Acer Aspire         | 36       | 1.47%   |
| Unknown             | 35       | 1.43%   |
| HP EliteDesk        | 28       | 1.14%   |
| Dell Inspiron       | 22       | 0.9%    |
| HP ProDesk          | 21       | 0.86%   |
| Fujitsu ESPRIMO     | 21       | 0.86%   |
| Lenovo ThinkStation | 19       | 0.77%   |
| Gigabyte X570       | 19       | 0.77%   |
| ASUS M5A78L-M       | 18       | 0.73%   |
| MSI MS-7721         | 17       | 0.69%   |
| Gigabyte B450M      | 15       | 0.61%   |
| Dell XPS            | 15       | 0.61%   |
| MSI MS-7C37         | 14       | 0.57%   |
| Gigabyte Z390       | 14       | 0.57%   |
| ASRock B450M        | 14       | 0.57%   |
| ASUS M5A97          | 13       | 0.53%   |
| Lenovo IdeaCentre   | 12       | 0.49%   |
| Gigabyte B450       | 12       | 0.49%   |
| ASUS Pro            | 11       | 0.45%   |
| ASUS CROSSHAIR      | 11       | 0.45%   |
| MSI MS-7C91         | 10       | 0.41%   |
| Gigabyte B550M      | 10       | 0.41%   |
| Dell Vostro         | 10       | 0.41%   |
| MSI MS-7C52         | 9        | 0.37%   |
| Gigabyte B550       | 9        | 0.37%   |
| ASUS P8Z68-V        | 9        | 0.37%   |
| ASUS P8H61-M        | 9        | 0.37%   |
| Acer Veriton        | 9        | 0.37%   |
| MSI MS-7C02         | 8        | 0.33%   |
| MSI MS-7817         | 8        | 0.33%   |
| MSI MS-7693         | 8        | 0.33%   |
| HP ProLiant         | 8        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 229      | 9.34%   |
| 2018    | 226      | 9.22%   |
| 2012    | 224      | 9.14%   |
| 2021    | 195      | 7.95%   |
| 2019    | 191      | 7.79%   |
| 2011    | 185      | 7.54%   |
| 2014    | 172      | 7.01%   |
| 2020    | 166      | 6.77%   |
| 2017    | 156      | 6.36%   |
| 2015    | 135      | 5.51%   |
| 2010    | 125      | 5.1%    |
| 2009    | 108      | 4.4%    |
| 2016    | 101      | 4.12%   |
| 2022    | 92       | 3.75%   |
| 2008    | 74       | 3.02%   |
| 2007    | 52       | 2.12%   |
| 2006    | 13       | 0.53%   |
| 2005    | 6        | 0.24%   |
| Unknown | 2        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2452     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2368     | 96.34%  |
| Enabled  | 90       | 3.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2447     | 99.8%   |
| Yes  | 5        | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 688      | 27.87%  |
| 8.01-16.0       | 422      | 17.09%  |
| 4.01-8.0        | 404      | 16.36%  |
| 32.01-64.0      | 397      | 16.08%  |
| 3.01-4.0        | 302      | 12.23%  |
| 64.01-256.0     | 138      | 5.59%   |
| 24.01-32.0      | 60       | 2.43%   |
| 1.01-2.0        | 34       | 1.38%   |
| 2.01-3.0        | 14       | 0.57%   |
| More than 256.0 | 8        | 0.32%   |
| 0.51-1.0        | 2        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 865      | 33.33%  |
| 2.01-3.0    | 795      | 30.64%  |
| 4.01-8.0    | 366      | 14.1%   |
| 3.01-4.0    | 364      | 14.03%  |
| 8.01-16.0   | 112      | 4.32%   |
| 0.51-1.0    | 52       | 2%      |
| 16.01-24.0  | 18       | 0.69%   |
| 0.01-0.5    | 10       | 0.39%   |
| 32.01-64.0  | 6        | 0.23%   |
| 24.01-32.0  | 6        | 0.23%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 981      | 39.22%  |
| 2      | 729      | 29.15%  |
| 3      | 369      | 14.75%  |
| 4      | 180      | 7.2%    |
| 5      | 104      | 4.16%   |
| 6      | 44       | 1.76%   |
| 0      | 32       | 1.28%   |
| 7      | 25       | 1%      |
| 8      | 13       | 0.52%   |
| 9      | 8        | 0.32%   |
| 11     | 6        | 0.24%   |
| 10     | 4        | 0.16%   |
| 13     | 2        | 0.08%   |
| 38     | 1        | 0.04%   |
| 20     | 1        | 0.04%   |
| 17     | 1        | 0.04%   |
| 12     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1330     | 53.96%  |
| Yes       | 1135     | 46.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2434     | 99.23%  |
| No        | 19       | 0.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1348     | 54.6%   |
| Yes       | 1121     | 45.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1665     | 67.46%  |
| Yes       | 803      | 32.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 555      | 22.61%  |
| Germany      | 276      | 11.24%  |
| France       | 162      | 6.6%    |
| Brazil       | 126      | 5.13%   |
| UK           | 120      | 4.89%   |
| Italy        | 108      | 4.4%    |
| Russia       | 105      | 4.28%   |
| Canada       | 98       | 3.99%   |
| Spain        | 68       | 2.77%   |
| Netherlands  | 47       | 1.91%   |
| Poland       | 46       | 1.87%   |
| Australia    | 43       | 1.75%   |
| India        | 39       | 1.59%   |
| Belgium      | 32       | 1.3%    |
| Switzerland  | 30       | 1.22%   |
| Sweden       | 30       | 1.22%   |
| Austria      | 30       | 1.22%   |
| Czechia      | 29       | 1.18%   |
| Finland      | 28       | 1.14%   |
| Mexico       | 26       | 1.06%   |
| Japan        | 26       | 1.06%   |
| Argentina    | 24       | 0.98%   |
| Greece       | 21       | 0.86%   |
| Turkey       | 19       | 0.77%   |
| Hungary      | 19       | 0.77%   |
| South Africa | 18       | 0.73%   |
| China        | 17       | 0.69%   |
| Slovakia     | 14       | 0.57%   |
| Portugal     | 14       | 0.57%   |
| Bulgaria     | 13       | 0.53%   |
| Norway       | 12       | 0.49%   |
| South Korea  | 11       | 0.45%   |
| Romania      | 11       | 0.45%   |
| Serbia       | 9        | 0.37%   |
| Peru         | 9        | 0.37%   |
| Thailand     | 8        | 0.33%   |
| Slovenia     | 8        | 0.33%   |
| Hong Kong    | 8        | 0.33%   |
| Denmark      | 8        | 0.33%   |
| Chile        | 8        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Cheboksary        | 24       | 0.95%   |
| Berlin            | 21       | 0.83%   |
| Vienna            | 19       | 0.75%   |
| Milan             | 19       | 0.75%   |
| Sydney            | 18       | 0.71%   |
| Paris             | 18       | 0.71%   |
| Moscow            | 18       | 0.71%   |
| Helsinki          | 16       | 0.63%   |
| Seattle           | 15       | 0.59%   |
| Sao Paulo         | 15       | 0.59%   |
| Madrid            | 15       | 0.59%   |
| Rio de Janeiro    | 13       | 0.51%   |
| San Jose          | 12       | 0.47%   |
| Prague            | 12       | 0.47%   |
| Hamburg           | 12       | 0.47%   |
| London            | 11       | 0.43%   |
| Istanbul          | 11       | 0.43%   |
| Athens            | 11       | 0.43%   |
| Toronto           | 10       | 0.4%    |
| New York          | 10       | 0.4%    |
| Munich            | 10       | 0.4%    |
| Dallas            | 10       | 0.4%    |
| Amsterdam         | 10       | 0.4%    |
| St Petersburg     | 9        | 0.36%   |
| Rome              | 9        | 0.36%   |
| Budapest          | 9        | 0.36%   |
| Novosibirsk       | 8        | 0.32%   |
| Manchester        | 8        | 0.32%   |
| Lima              | 8        | 0.32%   |
| Košice           | 8        | 0.32%   |
| Frankfurt am Main | 8        | 0.32%   |
| Brisbane          | 8        | 0.32%   |
| Zurich            | 7        | 0.28%   |
| Warsaw            | 7        | 0.28%   |
| Turin             | 7        | 0.28%   |
| Sofia             | 7        | 0.28%   |
| Portland          | 7        | 0.28%   |
| Ottawa            | 7        | 0.28%   |
| Wroclaw           | 6        | 0.24%   |
| Los Angeles       | 6        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 814      | 1329   | 18.68%  |
| Seagate                     | 812      | 1281   | 18.64%  |
| Samsung Electronics         | 642      | 976    | 14.73%  |
| Kingston                    | 273      | 335    | 6.27%   |
| Toshiba                     | 232      | 306    | 5.32%   |
| SanDisk                     | 206      | 288    | 4.73%   |
| Crucial                     | 193      | 258    | 4.43%   |
| Hitachi                     | 138      | 169    | 3.17%   |
| A-DATA Technology           | 70       | 82     | 1.61%   |
| Unknown                     | 54       | 92     | 1.24%   |
| Intel                       | 53       | 64     | 1.22%   |
| HGST                        | 50       | 76     | 1.15%   |
| China                       | 48       | 55     | 1.1%    |
| SK hynix                    | 38       | 47     | 0.87%   |
| Intenso                     | 38       | 44     | 0.87%   |
| Phison Electronics          | 37       | 49     | 0.85%   |
| Silicon Motion              | 34       | 40     | 0.78%   |
| PNY                         | 34       | 40     | 0.78%   |
| SPCC                        | 30       | 40     | 0.69%   |
| Phison                      | 29       | 42     | 0.67%   |
| Micron Technology           | 26       | 35     | 0.6%    |
| OCZ                         | 23       | 37     | 0.53%   |
| Maxtor                      | 22       | 31     | 0.5%    |
| Micron/Crucial Technology   | 21       | 31     | 0.48%   |
| Kingston Technology Company | 21       | 23     | 0.48%   |
| Corsair                     | 19       | 22     | 0.44%   |
| Patriot                     | 17       | 20     | 0.39%   |
| Lexar                       | 17       | 17     | 0.39%   |
| Gigabyte Technology         | 17       | 19     | 0.39%   |
| Team                        | 15       | 24     | 0.34%   |
| Transcend                   | 14       | 14     | 0.32%   |
| Unknown                     | 13       | 15     | 0.3%    |
| KIOXIA                      | 12       | 21     | 0.28%   |
| JMicron Technology          | 10       | 10     | 0.23%   |
| Hewlett-Packard             | 10       | 17     | 0.23%   |
| Apacer                      | 9        | 9      | 0.21%   |
| Realtek Semiconductor       | 8        | 9      | 0.18%   |
| GOODRAM                     | 8        | 12     | 0.18%   |
| ASMT                        | 8        | 10     | 0.18%   |
| SABRENT                     | 7        | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 69       | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB                        | 64       | 1.25%   |
| Kingston SA400S37240G 240GB SSD                       | 60       | 1.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 58       | 1.13%   |
| Samsung SSD 850 EVO 500GB                             | 48       | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB                        | 47       | 0.92%   |
| Samsung SSD 850 EVO 250GB                             | 47       | 0.92%   |
| Samsung SSD 860 EVO 500GB                             | 41       | 0.8%    |
| Kingston SA400S37480G 480GB SSD                       | 36       | 0.7%    |
| Toshiba DT01ACA050 500GB                              | 35       | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB                        | 34       | 0.67%   |
| Toshiba DT01ACA100 1TB                                | 33       | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                        | 32       | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 29       | 0.57%   |
| Crucial CT500MX500SSD1 500GB                          | 29       | 0.57%   |
| Toshiba HDWD110 1TB                                   | 27       | 0.53%   |
| Samsung SSD 980 PRO 1TB                               | 27       | 0.53%   |
| Kingston SA400S37120G 120GB SSD                       | 26       | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                           | 26       | 0.51%   |
| Crucial CT240BX500SSD1 240GB                          | 25       | 0.49%   |
| Samsung SSD 980 1TB                                   | 24       | 0.47%   |
| Toshiba VT180 240GB SSD                               | 23       | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB                        | 23       | 0.45%   |
| Unknown SD/MMC/MS PRO 16GB                            | 22       | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                        | 22       | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                            | 21       | 0.41%   |
| Samsung SSD 860 EVO 1TB                               | 21       | 0.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB  | 20       | 0.39%   |
| Samsung NVMe SSD Drive 1TB                            | 19       | 0.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 17       | 0.33%   |
| Seagate ST2000DM001-1CH164 2TB                        | 17       | 0.33%   |
| Samsung SSD 870 QVO 1TB                               | 17       | 0.33%   |
| Samsung SSD 870 EVO 500GB                             | 17       | 0.33%   |
| Toshiba DT01ACA200 2TB                                | 16       | 0.31%   |
| Seagate ST3500418AS 500GB                             | 16       | 0.31%   |
| Seagate ST31000528AS 1TB                              | 16       | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB                        | 16       | 0.31%   |
| Seagate Expansion Desk 5TB                            | 16       | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB                        | 16       | 0.31%   |
| Kingston SV300S37A120G 120GB SSD                      | 16       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 792      | 1241   | 37.55%  |
| WDC                 | 714      | 1167   | 33.85%  |
| Toshiba             | 200      | 255    | 9.48%   |
| Hitachi             | 138      | 169    | 6.54%   |
| Samsung Electronics | 114      | 163    | 5.41%   |
| HGST                | 50       | 72     | 2.37%   |
| Unknown             | 25       | 34     | 1.19%   |
| Maxtor              | 20       | 27     | 0.95%   |
| Intenso             | 10       | 11     | 0.47%   |
| JMicron Technology  | 9        | 9      | 0.43%   |
| SABRENT             | 7        | 9      | 0.33%   |
| Fujitsu             | 4        | 5      | 0.19%   |
| ASMT                | 4        | 5      | 0.19%   |
| Apple               | 4        | 4      | 0.19%   |
| WD MediaMax         | 3        | 3      | 0.14%   |
| USB3.0              | 2        | 3      | 0.09%   |
| HPE                 | 2        | 3      | 0.09%   |
| Hewlett-Packard     | 2        | 9      | 0.09%   |
| ASMedia             | 2        | 2      | 0.09%   |
| USB                 | 1        | 1      | 0.05%   |
| QUANTUM             | 1        | 1      | 0.05%   |
| MARVELL             | 1        | 1      | 0.05%   |
| HGST HTS            | 1        | 1      | 0.05%   |
| External            | 1        | 1      | 0.05%   |
| ExcelStor           | 1        | 1      | 0.05%   |
| DAS                 | 1        | 3      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 339      | 446    | 22.16%  |
| Kingston            | 232      | 284    | 15.16%  |
| Crucial             | 176      | 239    | 11.5%   |
| SanDisk             | 120      | 167    | 7.84%   |
| WDC                 | 92       | 111    | 6.01%   |
| A-DATA Technology   | 63       | 75     | 4.12%   |
| China               | 48       | 55     | 3.14%   |
| Toshiba             | 41       | 46     | 2.68%   |
| PNY                 | 31       | 37     | 2.03%   |
| Intel               | 30       | 33     | 1.96%   |
| SPCC                | 29       | 38     | 1.9%    |
| OCZ                 | 21       | 23     | 1.37%   |
| Intenso             | 20       | 24     | 1.31%   |
| Patriot             | 17       | 20     | 1.11%   |
| Micron Technology   | 16       | 25     | 1.05%   |
| Team                | 15       | 24     | 0.98%   |
| Transcend           | 14       | 14     | 0.92%   |
| SK hynix            | 14       | 17     | 0.92%   |
| Lexar               | 13       | 13     | 0.85%   |
| Gigabyte Technology | 13       | 15     | 0.85%   |
| Corsair             | 12       | 14     | 0.78%   |
| Hewlett-Packard     | 8        | 8      | 0.52%   |
| GOODRAM             | 8        | 12     | 0.52%   |
| Unknown             | 8        | 9      | 0.52%   |
| KingSpec            | 7        | 7      | 0.46%   |
| Apacer              | 7        | 7      | 0.46%   |
| Dogfish             | 6        | 9      | 0.39%   |
| Netac               | 5        | 5      | 0.33%   |
| Emtec               | 5        | 5      | 0.33%   |
| Seagate             | 4        | 6      | 0.26%   |
| Plextor             | 4        | 4      | 0.26%   |
| Mushkin             | 4        | 4      | 0.26%   |
| LITEONIT            | 4        | 4      | 0.26%   |
| LITEON              | 4        | 5      | 0.26%   |
| KingDian            | 4        | 4      | 0.26%   |
| ASMT                | 4        | 5      | 0.26%   |
| Verbatim            | 3        | 4      | 0.2%    |
| AMD                 | 3        | 4      | 0.2%    |
| Teclast             | 2        | 2      | 0.13%   |
| POWER               | 2        | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1629     | 3200   | 44.05%  |
| SSD     | 1293     | 1920   | 34.96%  |
| NVMe    | 669      | 993    | 18.09%  |
| Unknown | 90       | 131    | 2.43%   |
| MMC     | 17       | 25     | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2173     | 4954   | 71.2%   |
| NVMe | 669      | 991    | 21.92%  |
| SAS  | 193      | 299    | 6.32%   |
| MMC  | 17       | 25     | 0.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1551     | 2454   | 48.35%  |
| 0.51-1.0   | 926      | 1398   | 28.87%  |
| 1.01-2.0   | 363      | 564    | 11.32%  |
| 3.01-4.0   | 151      | 231    | 4.71%   |
| 4.01-10.0  | 98       | 244    | 3.05%   |
| 2.01-3.0   | 91       | 135    | 2.84%   |
| 10.01-20.0 | 28       | 94     | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 612      | 24.18%  |
| 501-1000       | 485      | 19.16%  |
| 251-500        | 474      | 18.73%  |
| 1001-2000      | 269      | 10.63%  |
| More than 3000 | 250      | 9.88%   |
| 51-100         | 132      | 5.22%   |
| 2001-3000      | 126      | 4.98%   |
| 1-20           | 104      | 4.11%   |
| 21-50          | 53       | 2.09%   |
| Unknown        | 26       | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 868      | 33.68%  |
| 21-50          | 459      | 17.81%  |
| 101-250        | 292      | 11.33%  |
| 51-100         | 285      | 11.06%  |
| 251-500        | 224      | 8.69%   |
| 501-1000       | 173      | 6.71%   |
| More than 3000 | 108      | 4.19%   |
| 1001-2000      | 95       | 3.69%   |
| 2001-3000      | 46       | 1.79%   |
| Unknown        | 26       | 1.01%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5        | 5      | 2.36%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4        | 5      | 1.89%   |
| WDC WD10EARS-00Y5B1 1TB             | 3        | 4      | 1.42%   |
| SanDisk SSD PLUS 480GB              | 3        | 3      | 1.42%   |
| Kingston SA400S37240G 240GB SSD     | 3        | 3      | 1.42%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 2        | 2      | 0.94%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 0.94%   |
| WDC WD4003FZEX-00Z4SA0 4TB          | 2        | 4      | 0.94%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 2        | 2      | 0.94%   |
| WDC WD10EZEX-22MFCA0 1TB            | 2        | 2      | 0.94%   |
| Seagate ST3750528AS 752GB           | 2        | 2      | 0.94%   |
| Seagate ST3500418AS 500GB           | 2        | 2      | 0.94%   |
| Seagate ST3320620AS 320GB           | 2        | 2      | 0.94%   |
| Seagate ST3250310AS 250GB           | 2        | 2      | 0.94%   |
| Seagate ST31000528AS 1TB            | 2        | 2      | 0.94%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 2      | 0.94%   |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 2      | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 2      | 0.94%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 2      | 0.94%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 2      | 0.94%   |
| Samsung Electronics SSD 980 PRO 1TB | 2        | 3      | 0.94%   |
| Samsung Electronics SSD 870 EVO 1TB | 2        | 2      | 0.94%   |
| Samsung Electronics HD322GJ 320GB   | 2        | 2      | 0.94%   |
| LITEONIT LCT-128M3S 128GB SSD       | 2        | 2      | 0.94%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 2      | 0.94%   |
| Intel SSDSC2CW120A3 120GB           | 2        | 2      | 0.94%   |
| Hitachi HUA722010CLA330 1TB         | 2        | 2      | 0.94%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 2      | 0.94%   |
| A-DATA Technology SU650 240GB SSD   | 2        | 2      | 0.94%   |
| YS SSD 128GB                        | 1        | 1      | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 1      | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 0.47%   |
| WDC WD75 00BPVT-16HXZ 752GB         | 1        | 1      | 0.47%   |
| WDC WD6400BEVT-60A0RT0 640GB        | 1        | 1      | 0.47%   |
| WDC WD6400AAKS-65A7B0 640GB         | 1        | 1      | 0.47%   |
| WDC WD6400AAKS-00A7B2 640GB         | 1        | 1      | 0.47%   |
| WDC WD6002FZWX-00GBGB0 6TB          | 1        | 1      | 0.47%   |
| WDC WD5001FZWX-00ZHUA0 5TB          | 1        | 1      | 0.47%   |
| WDC WD5000AZLX-60K2TA0 500GB        | 1        | 1      | 0.47%   |
| WDC WD5000AAKX-603CA0 500GB         | 1        | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 64       | 78     | 30.92%  |
| Seagate             | 52       | 59     | 25.12%  |
| Samsung Electronics | 21       | 24     | 10.14%  |
| Hitachi             | 16       | 16     | 7.73%   |
| Kingston            | 9        | 9      | 4.35%   |
| Toshiba             | 6        | 6      | 2.9%    |
| Intel               | 6        | 6      | 2.9%    |
| SanDisk             | 5        | 5      | 2.42%   |
| Maxtor              | 5        | 6      | 2.42%   |
| Crucial             | 5        | 6      | 2.42%   |
| LITEONIT            | 3        | 3      | 1.45%   |
| A-DATA Technology   | 3        | 3      | 1.45%   |
| Intenso             | 2        | 2      | 0.97%   |
| YS                  | 1        | 1      | 0.48%   |
| WD MediaMax         | 1        | 1      | 0.48%   |
| PNY                 | 1        | 1      | 0.48%   |
| OCZ                 | 1        | 1      | 0.48%   |
| Netac               | 1        | 1      | 0.48%   |
| Micron Technology   | 1        | 7      | 0.48%   |
| LDLC                | 1        | 1      | 0.48%   |
| HGST                | 1        | 2      | 0.48%   |
| China               | 1        | 1      | 0.48%   |
| Unknown             | 1        | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 62       | 76     | 40.52%  |
| Seagate             | 52       | 59     | 33.99%  |
| Hitachi             | 16       | 16     | 10.46%  |
| Samsung Electronics | 10       | 11     | 6.54%   |
| Toshiba             | 6        | 6      | 3.92%   |
| Maxtor              | 5        | 6      | 3.27%   |
| WD MediaMax         | 1        | 1      | 0.65%   |
| HGST                | 1        | 2      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 145      | 177    | 72.86%  |
| SSD  | 46       | 53     | 23.12%  |
| NVMe | 8        | 10     | 4.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1        | 1      | 33.33%  |
| Intel SSDPEKKW256G7 256GB         | 1        | 1      | 33.33%  |
| Hewlett-Packard EF0450FARMV 450GB | 1        | 4      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 33.33%  |
| Intel               | 1        | 1      | 33.33%  |
| Hewlett-Packard     | 1        | 4      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1700     | 4377   | 64.18%  |
| Works    | 761      | 1646   | 28.73%  |
| Malfunc  | 185      | 240    | 6.98%   |
| Failed   | 3        | 6      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1635     | 46.61%  |
| AMD                            | 732      | 20.87%  |
| Samsung Electronics            | 255      | 7.27%   |
| SanDisk                        | 135      | 3.85%   |
| ASMedia Technology             | 135      | 3.85%   |
| Marvell Technology Group       | 79       | 2.25%   |
| Phison Electronics             | 74       | 2.11%   |
| JMicron Technology             | 72       | 2.05%   |
| Nvidia                         | 67       | 1.91%   |
| Kingston Technology Company    | 66       | 1.88%   |
| Micron/Crucial Technology      | 38       | 1.08%   |
| Silicon Motion                 | 37       | 1.05%   |
| SK hynix                       | 26       | 0.74%   |
| LSI Logic / Symbios Logic      | 17       | 0.48%   |
| ADATA Technology               | 17       | 0.48%   |
| KIOXIA                         | 16       | 0.46%   |
| Silicon Image                  | 14       | 0.4%    |
| VIA Technologies               | 12       | 0.34%   |
| Micron Technology              | 11       | 0.31%   |
| Broadcom / LSI                 | 11       | 0.31%   |
| Seagate Technology             | 10       | 0.29%   |
| Realtek Semiconductor          | 10       | 0.29%   |
| MAXIO Technology (Hangzhou)    | 5        | 0.14%   |
| Adaptec                        | 5        | 0.14%   |
| Shenzhen Longsys Electronics   | 4        | 0.11%   |
| Toshiba America Info Systems   | 2        | 0.06%   |
| OCZ Technology Group           | 2        | 0.06%   |
| Lite-On Technology             | 2        | 0.06%   |
| Integrated Technology Express  | 2        | 0.06%   |
| Hewlett-Packard                | 2        | 0.06%   |
| 3ware                          | 2        | 0.06%   |
| Western Digital                | 1        | 0.03%   |
| Union Memory (Shenzhen)        | 1        | 0.03%   |
| Tekram Technology              | 1        | 0.03%   |
| Solidigm                       | 1        | 0.03%   |
| Solid State Storage Technology | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor     | 1        | 0.03%   |
| INNOGRIT                       | 1        | 0.03%   |
| HighPoint Technologies         | 1        | 0.03%   |
| Chelsio Communications         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 400      | 9.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 205      | 4.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 138      | 3.22%   |
| Intel SATA Controller [RAID mode]                                                       | 136      | 3.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 135      | 3.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 135      | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 130      | 3.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 129      | 3.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 125      | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 104      | 2.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 100      | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 94       | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 92       | 2.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 75       | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 72       | 1.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 64       | 1.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 63       | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 62       | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 58       | 1.35%   |
| AMD FCH SATA Controller D                                                               | 57       | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 51       | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 51       | 1.19%   |
| Samsung NVMe SSD Controller 980                                                         | 46       | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 45       | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 40       | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39       | 0.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 33       | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 32       | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 32       | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 30       | 0.7%    |
| Sandisk Non-Volatile memory controller                                                  | 29       | 0.68%   |
| Kingston Company Company Non-Volatile memory controller                                 | 29       | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 28       | 0.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 28       | 0.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 28       | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 28       | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 27       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 26       | 0.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 25       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1989     | 57.9%   |
| NVMe | 671      | 19.53%  |
| IDE  | 492      | 14.32%  |
| RAID | 240      | 6.99%   |
| SAS  | 32       | 0.93%   |
| SCSI | 11       | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1669     | 68.07%  |
| AMD    | 783      | 31.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 47       | 1.91%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 45       | 1.83%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 33       | 1.34%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 30       | 1.22%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 29       | 1.18%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 29       | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 26       | 1.06%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 25       | 1.02%   |
| AMD FX-8350 Eight-Core Processor            | 25       | 1.02%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 24       | 0.98%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 24       | 0.98%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 24       | 0.98%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 23       | 0.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 22       | 0.9%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 22       | 0.9%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 22       | 0.9%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 21       | 0.86%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 20       | 0.81%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 19       | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 19       | 0.77%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 19       | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 18       | 0.73%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 18       | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 17       | 0.69%   |
| Intel 12th Gen Core i9-12900K               | 17       | 0.69%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 17       | 0.69%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 15       | 0.61%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 15       | 0.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 15       | 0.61%   |
| AMD FX-6300 Six-Core Processor              | 15       | 0.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 14       | 0.57%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 14       | 0.57%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 14       | 0.57%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 14       | 0.57%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 13       | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 13       | 0.53%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 13       | 0.53%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 12       | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 492      | 20.06%  |
| Intel Core i7           | 351      | 14.31%  |
| Intel Core i3           | 209      | 8.52%   |
| AMD Ryzen 5             | 187      | 7.62%   |
| Intel Xeon              | 149      | 6.07%   |
| Other                   | 121      | 4.93%   |
| AMD Ryzen 7             | 121      | 4.93%   |
| AMD FX                  | 94       | 3.83%   |
| Intel Celeron           | 76       | 3.1%    |
| AMD Ryzen 9             | 73       | 2.98%   |
| Intel Core 2 Duo        | 64       | 2.61%   |
| Intel Pentium           | 59       | 2.41%   |
| Intel Core 2 Quad       | 52       | 2.12%   |
| AMD Ryzen 3             | 40       | 1.63%   |
| AMD Phenom II X4        | 29       | 1.18%   |
| AMD A10                 | 29       | 1.18%   |
| Intel Core i9           | 26       | 1.06%   |
| Intel Pentium Dual-Core | 24       | 0.98%   |
| AMD Athlon II X2        | 23       | 0.94%   |
| AMD A8                  | 23       | 0.94%   |
| AMD Ryzen Threadripper  | 18       | 0.73%   |
| AMD Phenom II X6        | 15       | 0.61%   |
| AMD Athlon 64 X2        | 15       | 0.61%   |
| AMD A6                  | 15       | 0.61%   |
| AMD A4                  | 15       | 0.61%   |
| Intel Core 2            | 14       | 0.57%   |
| Intel Atom              | 12       | 0.49%   |
| AMD Athlon II X4        | 11       | 0.45%   |
| Intel Pentium Dual      | 8        | 0.33%   |
| AMD Sempron             | 8        | 0.33%   |
| AMD Athlon              | 8        | 0.33%   |
| AMD Ryzen 5 PRO         | 7        | 0.29%   |
| AMD Athlon II X3        | 6        | 0.24%   |
| Intel Pentium 4         | 5        | 0.2%    |
| AMD Phenom II X2        | 5        | 0.2%    |
| AMD Phenom              | 4        | 0.16%   |
| AMD Athlon X4           | 4        | 0.16%   |
| Intel Pentium Gold      | 3        | 0.12%   |
| AMD Ryzen 7 PRO         | 3        | 0.12%   |
| AMD Ryzen 3 PRO         | 3        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1027     | 41.85%  |
| 2      | 553      | 22.53%  |
| 6      | 360      | 14.67%  |
| 8      | 240      | 9.78%   |
| 12     | 86       | 3.5%    |
| 16     | 65       | 2.65%   |
| 1      | 47       | 1.92%   |
| 3      | 36       | 1.47%   |
| 10     | 17       | 0.69%   |
| 24     | 7        | 0.29%   |
| 32     | 6        | 0.24%   |
| 20     | 4        | 0.16%   |
| 28     | 3        | 0.12%   |
| 64     | 1        | 0.04%   |
| 40     | 1        | 0.04%   |
| 14     | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2403     | 98%     |
| 2      | 49       | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 1414     | 57.64%  |
| 1      | 1038     | 42.32%  |
| 6      | 1        | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2451     | 99.92%  |
| Unknown        | 2        | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1571     | 62.54%  |
| 0x306c3    | 96       | 3.82%   |
| 0x306a9    | 75       | 2.99%   |
| 0x506e3    | 59       | 2.35%   |
| 0x206a7    | 57       | 2.27%   |
| 0x906ea    | 38       | 1.51%   |
| 0x08701021 | 38       | 1.51%   |
| 0x906e9    | 35       | 1.39%   |
| 0x90672    | 28       | 1.11%   |
| 0x0a201016 | 27       | 1.07%   |
| 0xa0653    | 25       | 1%      |
| 0x06000852 | 25       | 1%      |
| 0x306f2    | 22       | 0.88%   |
| 0x0800820d | 22       | 0.88%   |
| 0x1067a    | 21       | 0.84%   |
| 0x010000c8 | 20       | 0.8%    |
| 0x0a20120a | 15       | 0.6%    |
| 0x08108109 | 15       | 0.6%    |
| 0xa0671    | 14       | 0.56%   |
| 0x906ed    | 13       | 0.52%   |
| 0xa0655    | 12       | 0.48%   |
| 0x06003106 | 12       | 0.48%   |
| 0x06001119 | 11       | 0.44%   |
| 0x906ec    | 10       | 0.4%    |
| 0x0a50000c | 9        | 0.36%   |
| 0x08701013 | 9        | 0.36%   |
| 0x90675    | 8        | 0.32%   |
| 0x20655    | 8        | 0.32%   |
| 0x106a5    | 8        | 0.32%   |
| 0x0a201009 | 8        | 0.32%   |
| 0x906eb    | 7        | 0.28%   |
| 0x010000db | 7        | 0.28%   |
| 0x6fb      | 6        | 0.24%   |
| 0x206d7    | 6        | 0.24%   |
| 0x0a50000d | 6        | 0.24%   |
| 0x0a201204 | 6        | 0.24%   |
| 0x0810100b | 6        | 0.24%   |
| 0x0600611a | 6        | 0.24%   |
| 0x0600063e | 6        | 0.24%   |
| 0x906c0    | 5        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 325      | 13.24%  |
| KabyLake         | 219      | 8.92%   |
| IvyBridge        | 212      | 8.64%   |
| SandyBridge      | 182      | 7.42%   |
| Skylake          | 154      | 6.28%   |
| Zen 3            | 149      | 6.07%   |
| Zen 2            | 147      | 5.99%   |
| Penryn           | 117      | 4.77%   |
| Piledriver       | 116      | 4.73%   |
| K10              | 103      | 4.2%    |
| Zen+             | 93       | 3.79%   |
| Westmere         | 73       | 2.97%   |
| CometLake        | 73       | 2.97%   |
| Unknown          | 71       | 2.89%   |
| Zen              | 66       | 2.69%   |
| Core             | 63       | 2.57%   |
| Nehalem          | 42       | 1.71%   |
| Alderlake Hybrid | 36       | 1.47%   |
| Steamroller      | 29       | 1.18%   |
| Silvermont       | 28       | 1.14%   |
| K8 Hammer        | 24       | 0.98%   |
| Excavator        | 19       | 0.77%   |
| Bulldozer        | 18       | 0.73%   |
| Goldmont plus    | 16       | 0.65%   |
| Icelake          | 15       | 0.61%   |
| Broadwell        | 14       | 0.57%   |
| Goldmont         | 11       | 0.45%   |
| NetBurst         | 9        | 0.37%   |
| Tremont          | 6        | 0.24%   |
| TigerLake        | 6        | 0.24%   |
| K10 Llano        | 5        | 0.2%    |
| Jaguar           | 4        | 0.16%   |
| Bonnell          | 4        | 0.16%   |
| Bobcat           | 3        | 0.12%   |
| Puma             | 2        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1084     | 41.19%  |
| Intel                                        | 875      | 33.24%  |
| AMD                                          | 645      | 24.51%  |
| Matrox Electronics Systems                   | 12       | 0.46%   |
| ASPEED Technology                            | 12       | 0.46%   |
| ATI Technologies                             | 2        | 0.08%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.04%   |
| VIA Technologies                             | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 163      | 6.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 91       | 3.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 86       | 3.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 83       | 3.09%   |
| Intel HD Graphics 530                                                       | 78       | 2.91%   |
| Nvidia GK208B [GeForce GT 710]                                              | 59       | 2.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 59       | 2.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 45       | 1.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 42       | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 42       | 1.56%   |
| Intel HD Graphics 630                                                       | 40       | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 36       | 1.34%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 35       | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 35       | 1.3%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 33       | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 32       | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 31       | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 29       | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 29       | 1.08%   |
| Intel AlderLake-S GT1                                                       | 27       | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 26       | 0.97%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 24       | 0.89%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 24       | 0.89%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 23       | 0.86%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 22       | 0.82%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 21       | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 20       | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                         | 20       | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 20       | 0.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 18       | 0.67%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 18       | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 17       | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 16       | 0.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 16       | 0.6%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 16       | 0.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16       | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 15       | 0.56%   |
| Nvidia GF108 [GeForce GT 730]                                               | 15       | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 15       | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 14       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 988      | 40%     |
| 1 x Intel                | 747      | 30.24%  |
| 1 x AMD                  | 588      | 23.81%  |
| Intel + Nvidia           | 41       | 1.66%   |
| AMD + Nvidia             | 22       | 0.89%   |
| 2 x AMD                  | 21       | 0.85%   |
| 2 x Nvidia               | 19       | 0.77%   |
| Intel + AMD              | 13       | 0.53%   |
| 1 x Matrox               | 8        | 0.32%   |
| 1 x ASPEED               | 7        | 0.28%   |
| Nvidia + ASPEED          | 4        | 0.16%   |
| Nvidia + Matrox          | 3        | 0.12%   |
| Other                    | 2        | 0.08%   |
| 3 x AMD                  | 1        | 0.04%   |
| 1 x XGI                  | 1        | 0.04%   |
| 1 x VIA                  | 1        | 0.04%   |
| Intel + 2 x Nvidia       | 1        | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.04%   |
| AMD + Matrox             | 1        | 0.04%   |
| AMD + ASPEED             | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1717     | 68.93%  |
| Proprietary | 641      | 25.73%  |
| Unknown     | 133      | 5.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1841     | 73.88%  |
| 1.01-2.0   | 154      | 6.18%   |
| 0.51-1.0   | 115      | 4.61%   |
| 3.01-4.0   | 102      | 4.09%   |
| 7.01-8.0   | 101      | 4.05%   |
| 0.01-0.5   | 70       | 2.81%   |
| 8.01-16.0  | 44       | 1.77%   |
| 5.01-6.0   | 39       | 1.57%   |
| 2.01-3.0   | 15       | 0.6%    |
| 16.01-24.0 | 6        | 0.24%   |
| 4.01-5.0   | 5        | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 419      | 16.78%  |
| Dell                 | 276      | 11.05%  |
| Goldstar             | 226      | 9.05%   |
| Hewlett-Packard      | 177      | 7.09%   |
| Acer                 | 176      | 7.05%   |
| BenQ                 | 126      | 5.05%   |
| Ancor Communications | 112      | 4.49%   |
| AOC                  | 109      | 4.37%   |
| Philips              | 107      | 4.29%   |
| ViewSonic            | 56       | 2.24%   |
| Lenovo               | 56       | 2.24%   |
| ASUSTek Computer     | 54       | 2.16%   |
| Iiyama               | 51       | 2.04%   |
| Sony                 | 30       | 1.2%    |
| Vizio                | 26       | 1.04%   |
| Fujitsu Siemens      | 23       | 0.92%   |
| LG Electronics       | 22       | 0.88%   |
| Panasonic            | 20       | 0.8%    |
| Unknown              | 17       | 0.68%   |
| Sceptre Tech         | 16       | 0.64%   |
| NEC Computers        | 15       | 0.6%    |
| MSI                  | 14       | 0.56%   |
| Eizo                 | 14       | 0.56%   |
| Unknown              | 14       | 0.56%   |
| HannStar             | 13       | 0.52%   |
| Medion               | 12       | 0.48%   |
| Toshiba              | 11       | 0.44%   |
| Sharp                | 10       | 0.4%    |
| Gigabyte Technology  | 10       | 0.4%    |
| HKC                  | 9        | 0.36%   |
| Vestel Elektronik    | 8        | 0.32%   |
| Hitachi              | 8        | 0.32%   |
| Onkyo                | 7        | 0.28%   |
| MStar                | 7        | 0.28%   |
| Apple                | 7        | 0.28%   |
| RTK                  | 6        | 0.24%   |
| Plain Tree Systems   | 6        | 0.24%   |
| Mi                   | 6        | 0.24%   |
| Unknown (XXX)        | 5        | 0.2%    |
| HUAWEI               | 5        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 20       | 0.76%   |
| Unknown                                                                 | 14       | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 12       | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 10       | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 10       | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 9        | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 9        | 0.34%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 9        | 0.34%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                        | 8        | 0.3%    |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 8        | 0.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 8        | 0.3%    |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                      | 8        | 0.3%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 7        | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 6        | 0.23%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 6        | 0.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 6        | 0.23%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 6        | 0.23%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 6        | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 6        | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 6        | 0.23%   |
| Panasonic TV MEIA296 3840x2160 1872x1053mm 84.6-inch                    | 6        | 0.23%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch           | 5        | 0.19%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 5        | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 5        | 0.19%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                         | 5        | 0.19%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                    | 5        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 5        | 0.19%   |
| Goldstar Ultra HD GSM5B08 3780x2160 600x340mm 27.2-inch                 | 5        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 5        | 0.19%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                       | 5        | 0.19%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                       | 5        | 0.19%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch        | 5        | 0.19%   |
| Vizio V755-H4 VIZ1033 3840x2160 1096x616mm 49.5-inch                    | 4        | 0.15%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                         | 4        | 0.15%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 4        | 0.15%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 4        | 0.15%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 4        | 0.15%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 4        | 0.15%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 4        | 0.15%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 4        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1165     | 48.12%  |
| 3840x2160 (4K)     | 260      | 10.74%  |
| 2560x1440 (QHD)    | 172      | 7.1%    |
| 1280x1024 (SXGA)   | 151      | 6.24%   |
| 1680x1050 (WSXGA+) | 116      | 4.79%   |
| 1366x768 (WXGA)    | 82       | 3.39%   |
| 1440x900 (WXGA+)   | 79       | 3.26%   |
| 1920x1200 (WUXGA)  | 72       | 2.97%   |
| 1600x900 (HD+)     | 68       | 2.81%   |
| 3440x1440          | 32       | 1.32%   |
| 1360x768           | 31       | 1.28%   |
| 2560x1080          | 30       | 1.24%   |
| 1920x540           | 27       | 1.12%   |
| Unknown            | 23       | 0.95%   |
| 1280x720 (HD)      | 18       | 0.74%   |
| 3840x1080          | 15       | 0.62%   |
| 1024x768 (XGA)     | 14       | 0.58%   |
| 2288x1287          | 10       | 0.41%   |
| 2560x1600          | 8        | 0.33%   |
| 1600x1200          | 8        | 0.33%   |
| 3840x1600          | 5        | 0.21%   |
| 2048x1152          | 5        | 0.21%   |
| 1400x1050          | 4        | 0.17%   |
| 1280x960           | 4        | 0.17%   |
| 3600x1080          | 2        | 0.08%   |
| 3360x1080          | 2        | 0.08%   |
| 720x480            | 1        | 0.04%   |
| 5760x2160          | 1        | 0.04%   |
| 5760x1080          | 1        | 0.04%   |
| 5520x1080          | 1        | 0.04%   |
| 4480x1440          | 1        | 0.04%   |
| 4480x1080          | 1        | 0.04%   |
| 4080x2058          | 1        | 0.04%   |
| 3840x2560          | 1        | 0.04%   |
| 3520x1080          | 1        | 0.04%   |
| 3200x900           | 1        | 0.04%   |
| 3200x1080          | 1        | 0.04%   |
| 2880x1600          | 1        | 0.04%   |
| 2464x900           | 1        | 0.04%   |
| 2048x1536          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 357      | 14.3%   |
| 24      | 349      | 13.98%  |
| 23      | 319      | 12.78%  |
| 21      | 272      | 10.9%   |
| 19      | 165      | 6.61%   |
| Unknown | 144      | 5.77%   |
| 31      | 140      | 5.61%   |
| 22      | 82       | 3.29%   |
| 17      | 79       | 3.17%   |
| 20      | 77       | 3.08%   |
| 18      | 74       | 2.96%   |
| 34      | 49       | 1.96%   |
| 84      | 45       | 1.8%    |
| 32      | 41       | 1.64%   |
| 15      | 33       | 1.32%   |
| 40      | 28       | 1.12%   |
| 72      | 26       | 1.04%   |
| 25      | 24       | 0.96%   |
| 54      | 20       | 0.8%    |
| 29      | 12       | 0.48%   |
| 43      | 11       | 0.44%   |
| 37      | 11       | 0.44%   |
| 28      | 11       | 0.44%   |
| 52      | 9        | 0.36%   |
| 65      | 8        | 0.32%   |
| 48      | 7        | 0.28%   |
| 42      | 7        | 0.28%   |
| 26      | 7        | 0.28%   |
| 142     | 6        | 0.24%   |
| 49      | 6        | 0.24%   |
| 46      | 6        | 0.24%   |
| 36      | 6        | 0.24%   |
| 14      | 6        | 0.24%   |
| 64      | 5        | 0.2%    |
| 69      | 4        | 0.16%   |
| 55      | 4        | 0.16%   |
| 47      | 4        | 0.16%   |
| 39      | 4        | 0.16%   |
| 12      | 4        | 0.16%   |
| 60      | 3        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 954      | 39.47%  |
| 401-500        | 571      | 23.62%  |
| 601-700        | 204      | 8.44%   |
| Unknown        | 144      | 5.96%   |
| 301-350        | 105      | 4.34%   |
| 701-800        | 99       | 4.1%    |
| 351-400        | 97       | 4.01%   |
| 1001-1500      | 81       | 3.35%   |
| 1501-2000      | 78       | 3.23%   |
| 801-900        | 47       | 1.94%   |
| 901-1000       | 19       | 0.79%   |
| 201-300        | 11       | 0.46%   |
| More than 2000 | 7        | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1614     | 69.78%  |
| 16/10   | 299      | 12.93%  |
| 5/4     | 152      | 6.57%   |
| Unknown | 112      | 4.84%   |
| 21/9    | 66       | 2.85%   |
| 4/3     | 32       | 1.38%   |
| 32/9    | 13       | 0.56%   |
| 3/2     | 9        | 0.39%   |
| 1.00    | 8        | 0.35%   |
| 6/5     | 6        | 0.26%   |
| 1.96    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 798      | 32.52%  |
| 301-350        | 368      | 15%     |
| 151-200        | 331      | 13.49%  |
| 351-500        | 248      | 10.11%  |
| More than 1000 | 149      | 6.07%   |
| Unknown        | 144      | 5.87%   |
| 251-300        | 142      | 5.79%   |
| 141-150        | 130      | 5.3%    |
| 501-1000       | 89       | 3.63%   |
| 101-110        | 28       | 1.14%   |
| 131-140        | 8        | 0.33%   |
| 71-80          | 6        | 0.24%   |
| 111-120        | 6        | 0.24%   |
| 81-90          | 3        | 0.12%   |
| 121-130        | 2        | 0.08%   |
| 91-100         | 2        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1496     | 63.55%  |
| 101-120       | 409      | 17.37%  |
| Unknown       | 144      | 6.12%   |
| 1-50          | 134      | 5.69%   |
| 121-160       | 120      | 5.1%    |
| 161-240       | 50       | 2.12%   |
| More than 240 | 1        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1874     | 75.29%  |
| 2     | 368      | 14.79%  |
| 0     | 204      | 8.2%    |
| 3     | 37       | 1.49%   |
| 4     | 4        | 0.16%   |
| 6     | 1        | 0.04%   |
| 5     | 1        | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1473     | 42.33%  |
| Intel                                  | 1120     | 32.18%  |
| Qualcomm Atheros                       | 178      | 5.11%   |
| Broadcom                               | 102      | 2.93%   |
| Ralink Technology                      | 76       | 2.18%   |
| TP-Link                                | 74       | 2.13%   |
| Nvidia                                 | 58       | 1.67%   |
| Ralink                                 | 48       | 1.38%   |
| MediaTek                               | 29       | 0.83%   |
| Broadcom Limited                       | 25       | 0.72%   |
| NetGear                                | 23       | 0.66%   |
| Marvell Technology Group               | 23       | 0.66%   |
| Aquantia                               | 21       | 0.6%    |
| Microsoft                              | 17       | 0.49%   |
| Samsung Electronics                    | 16       | 0.46%   |
| Qualcomm Atheros Communications        | 16       | 0.46%   |
| D-Link System                          | 16       | 0.46%   |
| ASUSTek Computer                       | 12       | 0.34%   |
| Edimax Technology                      | 11       | 0.32%   |
| D-Link                                 | 11       | 0.32%   |
| Xiaomi                                 | 10       | 0.29%   |
| ASIX Electronics                       | 10       | 0.29%   |
| IMC Networks                           | 8        | 0.23%   |
| Linksys                                | 6        | 0.17%   |
| Sitecom Europe                         | 5        | 0.14%   |
| Qualcomm                               | 5        | 0.14%   |
| DisplayLink                            | 5        | 0.14%   |
| Belkin Components                      | 5        | 0.14%   |
| VIA Technologies                       | 4        | 0.11%   |
| ZyDAS                                  | 3        | 0.09%   |
| Wilocity                               | 3        | 0.09%   |
| OPPO                                   | 3        | 0.09%   |
| Mellanox Technologies                  | 3        | 0.09%   |
| ICS Advent                             | 3        | 0.09%   |
| Huawei Technologies                    | 3        | 0.09%   |
| Dresden Elektronik                     | 3        | 0.09%   |
| Unknown                                | 3        | 0.09%   |
| Tehuti Networks                        | 2        | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1163     | 29.28%  |
| Realtek RTL8125 2.5GbE Controller                                 | 138      | 3.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 133      | 3.35%   |
| Intel I211 Gigabit Network Connection                             | 121      | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 119      | 3%      |
| Intel Ethernet Connection (2) I219-V                              | 87       | 2.19%   |
| Intel Ethernet Connection I217-LM                                 | 77       | 1.94%   |
| Intel Ethernet Controller I225-V                                  | 74       | 1.86%   |
| Intel Ethernet Connection (7) I219-V                              | 51       | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 50       | 1.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 46       | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 43       | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 41       | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 1.03%   |
| Realtek 802.11ac NIC                                              | 38       | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 37       | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 35       | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 33       | 0.83%   |
| Intel 82574L Gigabit Network Connection                           | 32       | 0.81%   |
| Ralink MT7601U Wireless Adapter                                   | 31       | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 30       | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 29       | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27       | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 25       | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24       | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21       | 0.53%   |
| Intel Wireless-AC 9260                                            | 21       | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19       | 0.48%   |
| Intel Wireless 7260                                               | 19       | 0.48%   |
| Intel Wireless 7265                                               | 18       | 0.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 18       | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17       | 0.43%   |
| Intel Wireless 3165                                               | 17       | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 17       | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 16       | 0.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 16       | 0.4%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 15       | 0.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15       | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 15       | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                             | 15       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 398      | 33.25%  |
| Realtek Semiconductor           | 281      | 23.48%  |
| Qualcomm Atheros                | 103      | 8.6%    |
| Ralink Technology               | 76       | 6.35%   |
| TP-Link                         | 72       | 6.02%   |
| Ralink                          | 48       | 4.01%   |
| Broadcom                        | 39       | 3.26%   |
| MediaTek                        | 25       | 2.09%   |
| NetGear                         | 23       | 1.92%   |
| Microsoft                       | 17       | 1.42%   |
| Qualcomm Atheros Communications | 16       | 1.34%   |
| D-Link System                   | 12       | 1%      |
| ASUSTek Computer                | 12       | 1%      |
| Edimax Technology               | 11       | 0.92%   |
| D-Link                          | 11       | 0.92%   |
| Broadcom Limited                | 11       | 0.92%   |
| IMC Networks                    | 8        | 0.67%   |
| Linksys                         | 6        | 0.5%    |
| Sitecom Europe                  | 5        | 0.42%   |
| Belkin Components               | 5        | 0.42%   |
| ZyDAS                           | 3        | 0.25%   |
| Wilocity                        | 3        | 0.25%   |
| Mercucys                        | 2        | 0.17%   |
| Encore Electronics              | 2        | 0.17%   |
| AVM                             | 2        | 0.17%   |
| Sagem                           | 1        | 0.08%   |
| Philips (or NXP)                | 1        | 0.08%   |
| Micro Star International        | 1        | 0.08%   |
| LSI                             | 1        | 0.08%   |
| Gemtek                          | 1        | 0.08%   |
| BUFFALO                         | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 119      | 9.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 46       | 3.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 43       | 3.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 41       | 3.37%   |
| Realtek 802.11ac NIC                                       | 38       | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 35       | 2.88%   |
| Ralink MT7601U Wireless Adapter                            | 31       | 2.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 25       | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 24       | 1.98%   |
| Intel Wireless-AC 9260                                     | 21       | 1.73%   |
| Intel Wireless 7260                                        | 19       | 1.56%   |
| Intel Wireless 7265                                        | 18       | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 18       | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 17       | 1.4%    |
| Intel Wireless 3165                                        | 17       | 1.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 16       | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                             | 16       | 1.32%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 15       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 15       | 1.23%   |
| Ralink RT5370 Wireless Adapter                             | 14       | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 14       | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                            | 14       | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 14       | 1.15%   |
| Intel Wireless 8260                                        | 14       | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 14       | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 12       | 0.99%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 12       | 0.99%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 12       | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 12       | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 12       | 0.99%   |
| TP-Link 802.11ac WLAN Adapter                              | 11       | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 11       | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 11       | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 10       | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 10       | 0.82%   |
| Microsoft XBOX ACC                                         | 10       | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 9        | 0.74%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 9        | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 9        | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 9        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1370     | 52.01%  |
| Intel                                  | 915      | 34.74%  |
| Qualcomm Atheros                       | 82       | 3.11%   |
| Broadcom                               | 63       | 2.39%   |
| Nvidia                                 | 58       | 2.2%    |
| Marvell Technology Group               | 23       | 0.87%   |
| Aquantia                               | 21       | 0.8%    |
| Samsung Electronics                    | 16       | 0.61%   |
| Broadcom Limited                       | 14       | 0.53%   |
| Xiaomi                                 | 10       | 0.38%   |
| ASIX Electronics                       | 10       | 0.38%   |
| Qualcomm                               | 5        | 0.19%   |
| DisplayLink                            | 5        | 0.19%   |
| VIA Technologies                       | 4        | 0.15%   |
| D-Link System                          | 4        | 0.15%   |
| OPPO                                   | 3        | 0.11%   |
| MediaTek                               | 3        | 0.11%   |
| ICS Advent                             | 3        | 0.11%   |
| TP-Link                                | 2        | 0.08%   |
| Tehuti Networks                        | 2        | 0.08%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.08%   |
| Mellanox Technologies                  | 2        | 0.08%   |
| Huawei Technologies                    | 2        | 0.08%   |
| Chelsio Communications                 | 2        | 0.08%   |
| Apple                                  | 2        | 0.08%   |
| American Megatrends                    | 2        | 0.08%   |
| Prolific Technology                    | 1        | 0.04%   |
| Motorola PCS                           | 1        | 0.04%   |
| MosChip Semiconductor                  | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| JMicron Technology                     | 1        | 0.04%   |
| Google                                 | 1        | 0.04%   |
| 3Com                                   | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1163     | 42.6%   |
| Realtek RTL8125 2.5GbE Controller                                 | 138      | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 133      | 4.87%   |
| Intel I211 Gigabit Network Connection                             | 121      | 4.43%   |
| Intel Ethernet Connection (2) I219-V                              | 87       | 3.19%   |
| Intel Ethernet Connection I217-LM                                 | 77       | 2.82%   |
| Intel Ethernet Controller I225-V                                  | 74       | 2.71%   |
| Intel Ethernet Connection (7) I219-V                              | 51       | 1.87%   |
| Intel 82579V Gigabit Network Connection                           | 50       | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 1.5%    |
| Intel Ethernet Connection I217-V                                  | 37       | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 33       | 1.21%   |
| Intel 82574L Gigabit Network Connection                           | 32       | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 30       | 1.1%    |
| Nvidia MCP61 Ethernet                                             | 29       | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27       | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21       | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19       | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 17       | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 15       | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                             | 15       | 0.55%   |
| Intel Ethernet Connection (14) I219-V                             | 14       | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14       | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 13       | 0.48%   |
| Intel Ethernet Connection (2) I218-LM                             | 12       | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 12       | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11       | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11       | 0.4%    |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10       | 0.37%   |
| Intel Ethernet Controller X550                                    | 10       | 0.37%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 10       | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9        | 0.33%   |
| Nvidia MCP77 Ethernet                                             | 9        | 0.33%   |
| Intel Ethernet Connection (17) I219-V                             | 9        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 9        | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9        | 0.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8        | 0.29%   |
| Nvidia MCP73 Ethernet                                             | 8        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2433     | 67.92%  |
| WiFi     | 1123     | 31.35%  |
| Modem    | 20       | 0.56%   |
| Unknown  | 6        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1936     | 75.6%   |
| WiFi     | 624      | 24.37%  |
| Unknown  | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1533     | 62.29%  |
| 2     | 770      | 31.29%  |
| 3     | 115      | 4.67%   |
| 4     | 18       | 0.73%   |
| 0     | 15       | 0.61%   |
| 5     | 6        | 0.24%   |
| 7     | 2        | 0.08%   |
| 8     | 1        | 0.04%   |
| 6     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1675     | 67.98%  |
| Yes  | 789      | 32.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 361      | 43.92%  |
| Cambridge Silicon Radio         | 176      | 21.41%  |
| Realtek Semiconductor           | 61       | 7.42%   |
| ASUSTek Computer                | 53       | 6.45%   |
| Qualcomm Atheros Communications | 37       | 4.5%    |
| Broadcom                        | 31       | 3.77%   |
| IMC Networks                    | 16       | 1.95%   |
| MediaTek                        | 14       | 1.7%    |
| Apple                           | 14       | 1.7%    |
| TP-Link                         | 12       | 1.46%   |
| Lite-On Technology              | 12       | 1.46%   |
| Logitech                        | 4        | 0.49%   |
| Edimax Technology               | 4        | 0.49%   |
| Dell                            | 4        | 0.49%   |
| Belkin Components               | 3        | 0.36%   |
| Realtek                         | 2        | 0.24%   |
| Micro Star International        | 2        | 0.24%   |
| Integrated System Solution      | 2        | 0.24%   |
| Hewlett-Packard                 | 2        | 0.24%   |
| Foxconn / Hon Hai               | 2        | 0.24%   |
| D-Link System                   | 2        | 0.24%   |
| Conwise Technology              | 2        | 0.24%   |
| TRENDnet                        | 1        | 0.12%   |
| Toshiba                         | 1        | 0.12%   |
| Mobile Action Technology        | 1        | 0.12%   |
| HTC (High Tech Computer)        | 1        | 0.12%   |
| Dynex                           | 1        | 0.12%   |
| Unknown                         | 1        | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 176      | 21.36%  |
| Intel AX200 Bluetooth                                 | 100      | 12.14%  |
| Intel Bluetooth wireless interface                    | 74       | 8.98%   |
| Intel AX201 Bluetooth                                 | 47       | 5.7%    |
| Intel AX210 Bluetooth                                 | 44       | 5.34%   |
| Realtek Bluetooth Radio                               | 43       | 5.22%   |
| Intel Wireless-AC 3168 Bluetooth                      | 33       | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 28       | 3.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 20       | 2.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 18       | 2.18%   |
| ASUS ASUS USB-BT500                                   | 17       | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 16       | 1.94%   |
| MediaTek Wireless_Device                              | 14       | 1.7%    |
| Qualcomm Atheros  Bluetooth Device                    | 13       | 1.58%   |
| TP-Link TPuLink UB500 Adapter                         | 12       | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                        | 11       | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 10       | 1.21%   |
| Intel Bluetooth Device                                | 10       | 1.21%   |
| IMC Networks Bluetooth Radio                          | 8        | 0.97%   |
| Lite-On Bluetooth Device                              | 7        | 0.85%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 7        | 0.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 6        | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.61%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 5        | 0.61%   |
| ASUS Bluetooth Radio                                  | 5        | 0.61%   |
| Apple Bluetooth USB Host Controller                   | 5        | 0.61%   |
| Realtek RTL8821A Bluetooth                            | 4        | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.49%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.49%   |
| IMC Networks Wireless_Device                          | 4        | 0.49%   |
| ASUS Bluetooth Device                                 | 4        | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 3        | 0.36%   |
| IMC Networks Bluetooth Device                         | 3        | 0.36%   |
| Edimax Bluetooth Adapter                              | 3        | 0.36%   |
| Broadcom BCM2045 Bluetooth                            | 3        | 0.36%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.36%   |
| Apple Bluetooth HCI                                   | 3        | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2        | 0.24%   |
| Realtek Bluetooth Radio                               | 2        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1588     | 39.44%  |
| Nvidia                                       | 1023     | 25.41%  |
| AMD                                          | 952      | 23.65%  |
| C-Media Electronics                          | 80       | 1.99%   |
| Logitech                                     | 43       | 1.07%   |
| Creative Labs                                | 41       | 1.02%   |
| Micro Star International                     | 18       | 0.45%   |
| Texas Instruments                            | 17       | 0.42%   |
| Kingston Technology                          | 17       | 0.42%   |
| GN Netcom                                    | 16       | 0.4%    |
| ASUSTek Computer                             | 15       | 0.37%   |
| SteelSeries ApS                              | 12       | 0.3%    |
| Razer USA                                    | 12       | 0.3%    |
| Creative Technology                          | 12       | 0.3%    |
| JMTek                                        | 11       | 0.27%   |
| Focusrite-Novation                           | 11       | 0.27%   |
| Corsair                                      | 11       | 0.27%   |
| Plantronics                                  | 8        | 0.2%    |
| Tenx Technology                              | 7        | 0.17%   |
| VIA Technologies                             | 6        | 0.15%   |
| Generalplus Technology                       | 6        | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.12%   |
| Giga-Byte Technology                         | 5        | 0.12%   |
| Sennheiser Communications                    | 4        | 0.1%    |
| Realtek Semiconductor                        | 4        | 0.1%    |
| DSEA A/S                                     | 4        | 0.1%    |
| Blue Microphones                             | 4        | 0.1%    |
| Astro Gaming                                 | 4        | 0.1%    |
| Sony                                         | 3        | 0.07%   |
| M-Audio                                      | 3        | 0.07%   |
| KTMicro                                      | 3        | 0.07%   |
| Cambridge Silicon Radio                      | 3        | 0.07%   |
| Bose                                         | 3        | 0.07%   |
| Apple                                        | 3        | 0.07%   |
| Syntek                                       | 2        | 0.05%   |
| RODE Microphones                             | 2        | 0.05%   |
| Medeli Electronics                           | 2        | 0.05%   |
| Hewlett-Packard                              | 2        | 0.05%   |
| Elite Silicon                                | 2        | 0.05%   |
| Elgato Systems                               | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 245      | 5.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 231      | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 186      | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 179      | 3.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 169      | 3.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 162      | 3.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 145      | 3.14%   |
| Intel 200 Series PCH HD Audio                                              | 120      | 2.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 105      | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 97       | 2.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 93       | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 91       | 1.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 86       | 1.86%   |
| AMD FCH Azalia Controller                                                  | 79       | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 70       | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 65       | 1.41%   |
| Nvidia High Definition Audio Controller                                    | 62       | 1.34%   |
| Intel Alder Lake-S HD Audio Controller                                     | 62       | 1.34%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 62       | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 57       | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 56       | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 52       | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 50       | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 49       | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 49       | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                              | 47       | 1.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 47       | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 46       | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 46       | 1%      |
| Nvidia GF108 High Definition Audio Controller                              | 42       | 0.91%   |
| Nvidia GA102 High Definition Audio Controller                              | 42       | 0.91%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 41       | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 40       | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 38       | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 38       | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 37       | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                         | 37       | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                              | 35       | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 35       | 0.76%   |
| Intel Audio device                                                         | 35       | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 212      | 17.46%  |
| Corsair                      | 177      | 14.58%  |
| SK hynix                     | 128      | 10.54%  |
| Samsung Electronics          | 124      | 10.21%  |
| Unknown                      | 116      | 9.56%   |
| G.Skill                      | 92       | 7.58%   |
| Crucial                      | 90       | 7.41%   |
| Micron Technology            | 60       | 4.94%   |
| A-DATA Technology            | 30       | 2.47%   |
| Unknown                      | 27       | 2.22%   |
| Team                         | 25       | 2.06%   |
| Patriot                      | 14       | 1.15%   |
| Nanya Technology             | 12       | 0.99%   |
| Ramaxel Technology           | 10       | 0.82%   |
| Transcend                    | 7        | 0.58%   |
| PNY                          | 6        | 0.49%   |
| Unknown (ABCD)               | 5        | 0.41%   |
| Smart                        | 5        | 0.41%   |
| Elpida                       | 5        | 0.41%   |
| KETECH                       | 4        | 0.33%   |
| Hewlett-Packard              | 4        | 0.33%   |
| GOODRAM                      | 4        | 0.33%   |
| GeIL                         | 4        | 0.33%   |
| Timetec                      | 3        | 0.25%   |
| Silicon Power                | 3        | 0.25%   |
| Atermiter                    | 3        | 0.25%   |
| ASint Technology             | 3        | 0.25%   |
| Super Talent                 | 2        | 0.16%   |
| Qumo                         | 2        | 0.16%   |
| Patriot Memory (PDP Systems) | 2        | 0.16%   |
| Neo Forza                    | 2        | 0.16%   |
| KLEVV                        | 2        | 0.16%   |
| Kingmax                      | 2        | 0.16%   |
| Avant                        | 2        | 0.16%   |
| Asgard                       | 2        | 0.16%   |
| Apacer                       | 2        | 0.16%   |
| AMD                          | 2        | 0.16%   |
| ZION                         | 1        | 0.08%   |
| V-Color                      | 1        | 0.08%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 27       | 2.08%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s          | 17       | 1.31%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 14       | 1.08%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s         | 11       | 0.85%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 10       | 0.77%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 9        | 0.69%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 9        | 0.69%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 9        | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 8        | 0.62%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 8        | 0.62%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 8        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 7        | 0.54%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 7        | 0.54%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 7        | 0.54%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 7        | 0.54%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 6        | 0.46%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 6        | 0.46%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 6        | 0.46%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 6        | 0.46%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 6        | 0.46%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 5        | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 5        | 0.38%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s             | 5        | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 5        | 0.38%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 5        | 0.38%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 5        | 0.38%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 5        | 0.38%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 5        | 0.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 5        | 0.38%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s       | 5        | 0.38%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 5        | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 5        | 0.38%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s          | 5        | 0.38%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                    | 5        | 0.38%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 5        | 0.38%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 4        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 4        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 4        | 0.31%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 4        | 0.31%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s            | 4        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 549      | 51.65%  |
| DDR3    | 356      | 33.49%  |
| Unknown | 52       | 4.89%   |
| SDRAM   | 37       | 3.48%   |
| DDR2    | 30       | 2.82%   |
| LPDDR4  | 13       | 1.22%   |
| DDR5    | 13       | 1.22%   |
| DDR     | 10       | 0.94%   |
| DRAM    | 2        | 0.19%   |
| LPDDR3  | 1        | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 955      | 91.92%  |
| SODIMM       | 73       | 7.03%   |
| Row Of Chips | 5        | 0.48%   |
| RIMM         | 4        | 0.38%   |
| FB-DIMM      | 1        | 0.1%    |
| Unknown      | 1        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 433      | 38.35%  |
| 4096   | 261      | 23.12%  |
| 16384  | 216      | 19.13%  |
| 2048   | 128      | 11.34%  |
| 32768  | 63       | 5.58%   |
| 1024   | 24       | 2.13%   |
| 65536  | 2        | 0.18%   |
| 131072 | 1        | 0.09%   |
| 512    | 1        | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 224      | 19.19%  |
| 3200    | 130      | 11.14%  |
| 1333    | 120      | 10.28%  |
| 2400    | 91       | 7.8%    |
| 3600    | 86       | 7.37%   |
| 2667    | 67       | 5.74%   |
| 2133    | 58       | 4.97%   |
| 1867    | 29       | 2.49%   |
| 800     | 29       | 2.49%   |
| 3466    | 26       | 2.23%   |
| 3000    | 25       | 2.14%   |
| 2666    | 25       | 2.14%   |
| 3400    | 23       | 1.97%   |
| 667     | 22       | 1.89%   |
| 2933    | 17       | 1.46%   |
| 1800    | 16       | 1.37%   |
| 3800    | 14       | 1.2%    |
| 3733    | 12       | 1.03%   |
| 1066    | 12       | 1.03%   |
| 1866    | 11       | 0.94%   |
| 4800    | 9        | 0.77%   |
| 1067    | 8        | 0.69%   |
| Unknown | 8        | 0.69%   |
| 3534    | 7        | 0.6%    |
| 3266    | 7        | 0.6%    |
| 400     | 7        | 0.6%    |
| 3666    | 6        | 0.51%   |
| 2800    | 5        | 0.43%   |
| 2000    | 5        | 0.43%   |
| 3866    | 4        | 0.34%   |
| 2472    | 4        | 0.34%   |
| 5600    | 3        | 0.26%   |
| 4000    | 3        | 0.26%   |
| 3500    | 3        | 0.26%   |
| 3334    | 3        | 0.26%   |
| 2733    | 3        | 0.26%   |
| 1648    | 3        | 0.26%   |
| 533     | 3        | 0.26%   |
| 333     | 3        | 0.26%   |
| 6400    | 2        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 42       | 32.06%  |
| Brother Industries    | 28       | 21.37%  |
| Canon                 | 17       | 12.98%  |
| Samsung Electronics   | 16       | 12.21%  |
| Seiko Epson           | 14       | 10.69%  |
| Prolific Technology   | 3        | 2.29%   |
| QinHeng Electronics   | 2        | 1.53%   |
| Lexmark International | 2        | 1.53%   |
| Dymo-CoStar           | 2        | 1.53%   |
| Zebra                 | 1        | 0.76%   |
| Pantum                | 1        | 0.76%   |
| Oki Data              | 1        | 0.76%   |
| BESTEASY              | 1        | 0.76%   |
| Apple                 | 1        | 0.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seiko Epson ET-2720 Series              | 3        | 2.24%   |
| Samsung Composite Device                | 3        | 2.24%   |
| Prolific PL2305 Parallel Port           | 3        | 2.24%   |
| HP OfficeJet 3830 series                | 3        | 2.24%   |
| HP DeskJet 2130 series                  | 3        | 2.24%   |
| Brother HL-1440 Laser Printer           | 3        | 2.24%   |
| Seiko Epson L220 Series                 | 2        | 1.49%   |
| Seiko Epson ET-2810 Series              | 2        | 1.49%   |
| Samsung M2070 Series                    | 2        | 1.49%   |
| Samsung C460 Series                     | 2        | 1.49%   |
| QinHeng CH340S                          | 2        | 1.49%   |
| HP OfficeJet Pro 8020 series            | 2        | 1.49%   |
| HP LaserJet P1005                       | 2        | 1.49%   |
| HP LaserJet M14-M17                     | 2        | 1.49%   |
| HP LaserJet 4250                        | 2        | 1.49%   |
| HP DeskJet 4100 series                  | 2        | 1.49%   |
| HP DeskJet 2300 series                  | 2        | 1.49%   |
| HP DeskJet 1110 series                  | 2        | 1.49%   |
| Canon TS3100 series                     | 2        | 1.49%   |
| Canon LBP2900                           | 2        | 1.49%   |
| Brother Printer                         | 2        | 1.49%   |
| Brother HL-L2350DW series               | 2        | 1.49%   |
| Brother HL-2270DW Laser Printer         | 2        | 1.49%   |
| Brother DCP-J105                        | 2        | 1.49%   |
| Zebra ZP 450 Printer                    | 1        | 0.75%   |
| Seiko Epson XP-2100 Series              | 1        | 0.75%   |
| Seiko Epson WF-3520 Series              | 1        | 0.75%   |
| Seiko Epson WF-2840 Series              | 1        | 0.75%   |
| Seiko Epson WF-2510 Series              | 1        | 0.75%   |
| Seiko Epson L396 Series                 | 1        | 0.75%   |
| Seiko Epson L3110 Series                | 1        | 0.75%   |
| Seiko Epson L310 Series                 | 1        | 0.75%   |
| Seiko Epson ET-2710 Series              | 1        | 0.75%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 0.75%   |
| Samsung SCX-472x Series                 | 1        | 0.75%   |
| Samsung SCX-4600 Series                 | 1        | 0.75%   |
| Samsung ML-216x Series Laser Printer    | 1        | 0.75%   |
| Samsung ML-1740 Printer                 | 1        | 0.75%   |
| Samsung M267x 287x Series               | 1        | 0.75%   |
| Samsung CLP-310 Color Laser Printer     | 1        | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 13       | 59.09%  |
| Seiko Epson                 | 4        | 18.18%  |
| Hewlett-Packard             | 4        | 18.18%  |
| Acer Peripherals (now BenQ) | 1        | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                             | 4        | 18.18%  |
| Canon CanoScan LiDE 110                             | 2        | 9.09%   |
| Canon CanoScan LiDE 100                             | 2        | 9.09%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1        | 4.55%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1        | 4.55%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]  | 1        | 4.55%   |
| Seiko Epson GT-7700U [Perfection 1240U]             | 1        | 4.55%   |
| HP Scanjet N6010                                    | 1        | 4.55%   |
| HP ScanJet G4010                                    | 1        | 4.55%   |
| HP ScanJet 4850C/4890C                              | 1        | 4.55%   |
| HP ScanJet 3400cse                                  | 1        | 4.55%   |
| Canon CanoScan N1240U/LiDE 30                       | 1        | 4.55%   |
| Canon CanoScan LIDE 25                              | 1        | 4.55%   |
| Canon CanoScan LiDE 220                             | 1        | 4.55%   |
| Canon CanoScan LiDE 200                             | 1        | 4.55%   |
| Canon CanoScan 9000F Mark II                        | 1        | 4.55%   |
| Acer Peripherals (now BenQ) Benq 5000               | 1        | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 165      | 35.87%  |
| Microdia                      | 42       | 9.13%   |
| Microsoft                     | 34       | 7.39%   |
| Sunplus Innovation Technology | 22       | 4.78%   |
| Apple                         | 17       | 3.7%    |
| Samsung Electronics           | 15       | 3.26%   |
| Realtek Semiconductor         | 12       | 2.61%   |
| Generalplus Technology        | 12       | 2.61%   |
| Z-Star Microelectronics       | 11       | 2.39%   |
| Chicony Electronics           | 10       | 2.17%   |
| ARC International             | 9        | 1.96%   |
| 2M UVC CAMERA                 | 7        | 1.52%   |
| Trust                         | 6        | 1.3%    |
| Razer USA                     | 6        | 1.3%    |
| GEMBIRD                       | 6        | 1.3%    |
| Creative Technology           | 6        | 1.3%    |
| MacroSilicon                  | 4        | 0.87%   |
| Cubeternet                    | 4        | 0.87%   |
| WaveRider Communications      | 3        | 0.65%   |
| Sonix Technology              | 3        | 0.65%   |
| Philips (or NXP)              | 3        | 0.65%   |
| KYE Systems (Mouse Systems)   | 3        | 0.65%   |
| Hewlett-Packard               | 3        | 0.65%   |
| AVerMedia Technologies        | 3        | 0.65%   |
| Asuscom Network               | 3        | 0.65%   |
| Alcor Micro                   | 3        | 0.65%   |
| Quanta                        | 2        | 0.43%   |
| Pixart Imaging                | 2        | 0.43%   |
| OPPO Electronics              | 2        | 0.43%   |
| Linux Foundation              | 2        | 0.43%   |
| IMC Networks                  | 2        | 0.43%   |
| Huawei Technologies           | 2        | 0.43%   |
| HD WEBCAM                     | 2        | 0.43%   |
| Aveo Technology               | 2        | 0.43%   |
| Arkmicro Technologies         | 2        | 0.43%   |
| Acer                          | 2        | 0.43%   |
| Xiongmai                      | 1        | 0.22%   |
| ViewSonic                     | 1        | 0.22%   |
| Tobii AB                      | 1        | 0.22%   |
| Syntek                        | 1        | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 30       | 6.51%   |
| Logitech HD Pro Webcam C920                       | 30       | 6.51%   |
| Logitech C922 Pro Stream Webcam                   | 19       | 4.12%   |
| Apple iPhone 5/5C/5S/6/SE                         | 16       | 3.47%   |
| Samsung Galaxy A5 (MTP)                           | 15       | 3.25%   |
| Microdia Webcam Vitade AF                         | 13       | 2.82%   |
| Logitech HD Webcam C615                           | 11       | 2.39%   |
| Microsoft LifeCam HD-3000                         | 10       | 2.17%   |
| Logitech C920 PRO HD Webcam                       | 10       | 2.17%   |
| ARC International Camera                          | 9        | 1.95%   |
| Microdia USB 2.0 Camera                           | 8        | 1.74%   |
| Logitech Webcam C170                              | 8        | 1.74%   |
| Logitech HD Webcam C525                           | 7        | 1.52%   |
| Generalplus GENERAL WEBCAM                        | 7        | 1.52%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam              | 7        | 1.52%   |
| Sunplus FHD Camera Microphone                     | 6        | 1.3%    |
| Microsoft LifeCam Cinema                          | 6        | 1.3%    |
| Microdia Sonix USB 2.0 Camera                     | 6        | 1.3%    |
| Microdia Camera                                   | 6        | 1.3%    |
| Realtek FULL HD 1080P Webcam                      | 5        | 1.08%   |
| Logitech Webcam C310                              | 5        | 1.08%   |
| Sunplus Full HD webcam                            | 4        | 0.87%   |
| Razer USA Razer Kiyo                              | 4        | 0.87%   |
| Microdia CameraA                                  | 4        | 0.87%   |
| Generalplus WEB CAM                               | 4        | 0.87%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 4        | 0.87%   |
| Z-Star Venus USB2.0 Camera                        | 3        | 0.65%   |
| Z-Star Lenovo USB 2.0 UVC Camera                  | 3        | 0.65%   |
| WaveRider USB 2.0 Camera                          | 3        | 0.65%   |
| Realtek USB Camera                                | 3        | 0.65%   |
| Microsoft LifeCam VX-500 [1357]                   | 3        | 0.65%   |
| Microsoft LifeCam Studio                          | 3        | 0.65%   |
| MacroSilicon USB Video                            | 3        | 0.65%   |
| Logitech Webcam C925e                             | 3        | 0.65%   |
| Logitech QuickCam Pro 9000                        | 3        | 0.65%   |
| Logitech HD Webcam C910                           | 3        | 0.65%   |
| Logitech HD Webcam C510                           | 3        | 0.65%   |
| Logitech BRIO Ultra HD Webcam                     | 3        | 0.65%   |
| Logitech B525 HD Webcam                           | 3        | 0.65%   |
| Creative Live! Cam Chat HD [VF0700]               | 3        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Dell                  | 2        | 50%     |
| Microsoft             | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 50%     |
| Microsoft Fingerprint Reader                   | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 6        | 26.09%  |
| SCM Microsystems          | 3        | 13.04%  |
| Realtek Semiconductor     | 3        | 13.04%  |
| Gemalto (was Gemplus)     | 2        | 8.7%    |
| Chicony Electronics       | 2        | 8.7%    |
| Alcor Micro               | 2        | 8.7%    |
| Reiner SCT Kartensysteme  | 1        | 4.35%   |
| Lenovo                    | 1        | 4.35%   |
| Fujitsu Siemens Computers | 1        | 4.35%   |
| Cherry                    | 1        | 4.35%   |
| Aladdin Knowledge Systems | 1        | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 13.04%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 3        | 13.04%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 2        | 8.7%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 8.7%    |
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 8.7%    |
| Advanced Card Systems ACR122U                                              | 2        | 8.7%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 4.35%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 4.35%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 4.35%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 4.35%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 4.35%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 4.35%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 4.35%   |
| Advanced Card Systems ACR39U                                               | 1        | 4.35%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2044     | 82.35%  |
| 1     | 374      | 15.07%  |
| 2     | 38       | 1.53%   |
| 3     | 16       | 0.64%   |
| 5     | 6        | 0.24%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |
| 6     | 1        | 0.04%   |
| 4     | 1        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 196      | 37.69%  |
| Net/wireless             | 119      | 22.88%  |
| Unassigned class         | 48       | 9.23%   |
| Communication controller | 36       | 6.92%   |
| Sound                    | 31       | 5.96%   |
| Chipcard                 | 15       | 2.88%   |
| Multimedia controller    | 13       | 2.5%    |
| Net/ethernet             | 12       | 2.31%   |
| Bluetooth                | 11       | 2.12%   |
| Camera                   | 9        | 1.73%   |
| Storage/raid             | 8        | 1.54%   |
| Network                  | 5        | 0.96%   |
| Card reader              | 4        | 0.77%   |
| Dvb card                 | 3        | 0.58%   |
| Tv card                  | 2        | 0.38%   |
| Storage/nvme             | 2        | 0.38%   |
| Storage/ata              | 2        | 0.38%   |
| Fingerprint reader       | 2        | 0.38%   |
| Wireless                 | 1        | 0.19%   |
| Modem                    | 1        | 0.19%   |

