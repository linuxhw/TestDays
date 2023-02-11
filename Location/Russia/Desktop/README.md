Linux in Russia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 17764

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B660-I GAMING ... | [19d65de9b6](https://linux-hardware.org/?probe=19d65de9b6) | Jan 31, 2023 |
| Gigabyte      | B560M H                     | [65f58e4e39](https://linux-hardware.org/?probe=65f58e4e39) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a2c87504d6](https://linux-hardware.org/?probe=a2c87504d6) | Jan 31, 2023 |
| MSI           | G41M-P28                    | [7f37c4b40e](https://linux-hardware.org/?probe=7f37c4b40e) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| Gigabyte      | A320M-H-CF                  | [f5379a55ea](https://linux-hardware.org/?probe=f5379a55ea) | Jan 31, 2023 |
| ASUSTek       | B85M-G                      | [44c2ca8150](https://linux-hardware.org/?probe=44c2ca8150) | Jan 31, 2023 |
| HP            | 8599                        | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| HP            | 8599                        | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| ASUSTek       | H110-PLUS                   | [c20a43e3e5](https://linux-hardware.org/?probe=c20a43e3e5) | Jan 31, 2023 |
| ASRock        | B650M PG Riptide            | [260d257a0c](https://linux-hardware.org/?probe=260d257a0c) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [4830eacf5e](https://linux-hardware.org/?probe=4830eacf5e) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [0b59b68d55](https://linux-hardware.org/?probe=0b59b68d55) | Jan 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [10c275723f](https://linux-hardware.org/?probe=10c275723f) | Jan 30, 2023 |
| Gigabyte      | B365M H                     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| MSI           | H81M-P33                    | [32149d3b64](https://linux-hardware.org/?probe=32149d3b64) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 8526 MVB, A                 | [eaa1bf595f](https://linux-hardware.org/?probe=eaa1bf595f) | Jan 30, 2023 |
| MSI           | B450M-A PRO MAX             | [a7232f4811](https://linux-hardware.org/?probe=a7232f4811) | Jan 30, 2023 |
| ASUSTek       | P8Q77-M                     | [be0ebca5cc](https://linux-hardware.org/?probe=be0ebca5cc) | Jan 29, 2023 |
| HC            | HCAR357-MI V1.0             | [986dd858ba](https://linux-hardware.org/?probe=986dd858ba) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [868269808a](https://linux-hardware.org/?probe=868269808a) | Jan 29, 2023 |
| ASRock        | P45DE3                      | [e4c2e737f7](https://linux-hardware.org/?probe=e4c2e737f7) | Jan 29, 2023 |
| EVGA          | E689 $                      | [9d4b1aeaa9](https://linux-hardware.org/?probe=9d4b1aeaa9) | Jan 29, 2023 |
| ASRock        | Z77M                        | [83a27ed2b5](https://linux-hardware.org/?probe=83a27ed2b5) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS PRO              | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| ASRock        | G41M-S3                     | [2196343afa](https://linux-hardware.org/?probe=2196343afa) | Jan 29, 2023 |
| ASUSTek       | P7P55D LE                   | [943a02b7e9](https://linux-hardware.org/?probe=943a02b7e9) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | [c52b5b3357](https://linux-hardware.org/?probe=c52b5b3357) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [e768563b42](https://linux-hardware.org/?probe=e768563b42) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [97aa61aba5](https://linux-hardware.org/?probe=97aa61aba5) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [000203af81](https://linux-hardware.org/?probe=000203af81) | Jan 29, 2023 |
| MSI           | B450M MORTAR MAX            | [017467452c](https://linux-hardware.org/?probe=017467452c) | Jan 29, 2023 |
| Intel         | X79G V2.x                   | [40bc764c73](https://linux-hardware.org/?probe=40bc764c73) | Jan 28, 2023 |
| EVGA          | E689 $                      | [be99ae882b](https://linux-hardware.org/?probe=be99ae882b) | Jan 28, 2023 |
| ASRock        | X570 Taichi                 | [3b1c5df727](https://linux-hardware.org/?probe=3b1c5df727) | Jan 28, 2023 |
| AZW           | Gemini M                    | [5534667621](https://linux-hardware.org/?probe=5534667621) | Jan 28, 2023 |
| AZW           | GTR V02                     | [b1b34f10a2](https://linux-hardware.org/?probe=b1b34f10a2) | Jan 28, 2023 |
| Unknown       | X79                         | [164508bcb4](https://linux-hardware.org/?probe=164508bcb4) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8492e549e2](https://linux-hardware.org/?probe=8492e549e2) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [836e9a9809](https://linux-hardware.org/?probe=836e9a9809) | Jan 28, 2023 |
| DEPO Compu... | DPH410S                     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | P8Z77-M                     | [22d53e86e0](https://linux-hardware.org/?probe=22d53e86e0) | Jan 28, 2023 |
| Acer          | Aspire TC-705               | [be48644835](https://linux-hardware.org/?probe=be48644835) | Jan 27, 2023 |
| ASUSTek       | M2N-MX                      | [0920c10a0e](https://linux-hardware.org/?probe=0920c10a0e) | Jan 27, 2023 |
| Gigabyte      | B85M-D3H-A                  | [8289da39ca](https://linux-hardware.org/?probe=8289da39ca) | Jan 27, 2023 |
| Gigabyte      | 970A-DS3P                   | [547e171057](https://linux-hardware.org/?probe=547e171057) | Jan 27, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| ASUSTek       | H81M-K                      | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| ASRock        | B450 Gaming K4              | [7ce2ff0443](https://linux-hardware.org/?probe=7ce2ff0443) | Jan 27, 2023 |
| Gigabyte      | G41MT-S2                    | [774f8eb27f](https://linux-hardware.org/?probe=774f8eb27f) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Intel         | X99                         | [1fbd6cf5bd](https://linux-hardware.org/?probe=1fbd6cf5bd) | Jan 27, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [2fea9476f5](https://linux-hardware.org/?probe=2fea9476f5) | Jan 26, 2023 |
| MSI           | 770-C45                     | [3da3ee46c2](https://linux-hardware.org/?probe=3da3ee46c2) | Jan 26, 2023 |
| Gigabyte      | G41MT-S2                    | [06cd0f5943](https://linux-hardware.org/?probe=06cd0f5943) | Jan 26, 2023 |
| ASUSTek       | P6T SE                      | [1033fae7e9](https://linux-hardware.org/?probe=1033fae7e9) | Jan 26, 2023 |
| ASRock        | B650M PG Riptide            | [e9f4894d6d](https://linux-hardware.org/?probe=e9f4894d6d) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| ASRock        | H610M-HDV/M.2               | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [4ad0b3594f](https://linux-hardware.org/?probe=4ad0b3594f) | Jan 26, 2023 |
| ASUSTek       | P7H55-M                     | [34c55ab8ae](https://linux-hardware.org/?probe=34c55ab8ae) | Jan 26, 2023 |
| iRU           | v1.0                        | [5dfa804f74](https://linux-hardware.org/?probe=5dfa804f74) | Jan 26, 2023 |
| ASUSTek       | P5E-VM SE                   | [0b25483160](https://linux-hardware.org/?probe=0b25483160) | Jan 26, 2023 |
| Intel         | X99 V1.0                    | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [883b4a1c39](https://linux-hardware.org/?probe=883b4a1c39) | Jan 26, 2023 |
| Intel         | H61M-DS2V                   | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| MSI           | 770-C45                     | [42ffd24c35](https://linux-hardware.org/?probe=42ffd24c35) | Jan 25, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| MSI           | 770-C45                     | [1991e96ff2](https://linux-hardware.org/?probe=1991e96ff2) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [28effc69e6](https://linux-hardware.org/?probe=28effc69e6) | Jan 25, 2023 |
| ASRock        | H110 Pro BTC+               | [4fab0cb4c4](https://linux-hardware.org/?probe=4fab0cb4c4) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | H61M-DS2                    | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Gigabyte      | B560M AORUS PRO             | [a145217706](https://linux-hardware.org/?probe=a145217706) | Jan 25, 2023 |
| ASRock        | H310CM-DVS                  | [41b1ad4545](https://linux-hardware.org/?probe=41b1ad4545) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8a7a7f6b72](https://linux-hardware.org/?probe=8a7a7f6b72) | Jan 25, 2023 |
| ASRock        | X99 Professional Gaming ... | [74054f4cb8](https://linux-hardware.org/?probe=74054f4cb8) | Jan 24, 2023 |
| ASRock        | X99 Professional Gaming ... | [2a89d751e1](https://linux-hardware.org/?probe=2a89d751e1) | Jan 24, 2023 |
| MSI           | G41M-P28                    | [465a715dc7](https://linux-hardware.org/?probe=465a715dc7) | Jan 24, 2023 |
| Gigabyte      | B450M S2H V2                | [e8e7a44a2a](https://linux-hardware.org/?probe=e8e7a44a2a) | Jan 24, 2023 |
| MSI           | B560M PRO-VDH               | [8cb2b45267](https://linux-hardware.org/?probe=8cb2b45267) | Jan 24, 2023 |
| Biostar       | G41-M7                      | [3f66a61637](https://linux-hardware.org/?probe=3f66a61637) | Jan 24, 2023 |
| Pegatron      | IPPPV-D3G                   | [770e25fefd](https://linux-hardware.org/?probe=770e25fefd) | Jan 24, 2023 |
| ASRock        | H110 Pro BTC+               | [f4a90a48ec](https://linux-hardware.org/?probe=f4a90a48ec) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e2d597c046](https://linux-hardware.org/?probe=e2d597c046) | Jan 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [416a11089a](https://linux-hardware.org/?probe=416a11089a) | Jan 23, 2023 |
| ASRock        | B450 Gaming K4              | [0a7ef9990f](https://linux-hardware.org/?probe=0a7ef9990f) | Jan 23, 2023 |
| ASUSTek       | P8Z77-M                     | [06d41872a9](https://linux-hardware.org/?probe=06d41872a9) | Jan 23, 2023 |
| ASUSTek       | P8Z77-M                     | [f965d9b5b1](https://linux-hardware.org/?probe=f965d9b5b1) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [257f3b320c](https://linux-hardware.org/?probe=257f3b320c) | Jan 23, 2023 |
| Gigabyte      | H81M-S1                     | [ab746d7557](https://linux-hardware.org/?probe=ab746d7557) | Jan 23, 2023 |
| Intel         | SKYBAY                      | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [10fa3eeed2](https://linux-hardware.org/?probe=10fa3eeed2) | Jan 23, 2023 |
| ASUSTek       | P5K SE                      | [6d55940af7](https://linux-hardware.org/?probe=6d55940af7) | Jan 23, 2023 |
| ASUSTek       | H81M-K                      | [3c25197bac](https://linux-hardware.org/?probe=3c25197bac) | Jan 23, 2023 |
| ASRock        | X300M-STX                   | [13ce0469f3](https://linux-hardware.org/?probe=13ce0469f3) | Jan 23, 2023 |
| Dell          | 0JP3NX A01                  | [f75ac14e70](https://linux-hardware.org/?probe=f75ac14e70) | Jan 23, 2023 |
| Gigabyte      | B75M-HD3                    | [77d58eb890](https://linux-hardware.org/?probe=77d58eb890) | Jan 23, 2023 |
| ASUSTek       | P5Q SE2                     | [8618810acb](https://linux-hardware.org/?probe=8618810acb) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | A88X-PRO                    | [659f4bf9b1](https://linux-hardware.org/?probe=659f4bf9b1) | Jan 23, 2023 |
| Biostar       | H510MHP                     | [be134c4160](https://linux-hardware.org/?probe=be134c4160) | Jan 23, 2023 |
| ASUSTek       | Z97-C                       | [3a89f39a8f](https://linux-hardware.org/?probe=3a89f39a8f) | Jan 23, 2023 |
| Biostar       | H510MHP                     | [2df96ea9cf](https://linux-hardware.org/?probe=2df96ea9cf) | Jan 23, 2023 |
| MSI           | PRO H610M-E DDR4            | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| ASRock        | X99 Professional Gaming ... | [04f06d8d99](https://linux-hardware.org/?probe=04f06d8d99) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [ec7d450cb0](https://linux-hardware.org/?probe=ec7d450cb0) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [d55b2b9507](https://linux-hardware.org/?probe=d55b2b9507) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [8716ca07da](https://linux-hardware.org/?probe=8716ca07da) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [21e1d557cc](https://linux-hardware.org/?probe=21e1d557cc) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [33c845f3a4](https://linux-hardware.org/?probe=33c845f3a4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [24d2721a00](https://linux-hardware.org/?probe=24d2721a00) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [1e1066bd8b](https://linux-hardware.org/?probe=1e1066bd8b) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [7e636906b9](https://linux-hardware.org/?probe=7e636906b9) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [5aa076d0a5](https://linux-hardware.org/?probe=5aa076d0a5) | Jan 23, 2023 |
| ASUSTek       | H81M-E                      | [2a20dabdd7](https://linux-hardware.org/?probe=2a20dabdd7) | Jan 23, 2023 |
| Biostar       | N61PB-M2S                   | [bce8692808](https://linux-hardware.org/?probe=bce8692808) | Jan 22, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| Gigabyte      | F2A55M-DS2                  | [0e1605a304](https://linux-hardware.org/?probe=0e1605a304) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [4c4a17a3cf](https://linux-hardware.org/?probe=4c4a17a3cf) | Jan 22, 2023 |
| Gigabyte      | H310M H                     | [bd85a7e96e](https://linux-hardware.org/?probe=bd85a7e96e) | Jan 22, 2023 |
| MSI           | B350 TOMAHAWK               | [91ef58d8a0](https://linux-hardware.org/?probe=91ef58d8a0) | Jan 22, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [ecfd1795a0](https://linux-hardware.org/?probe=ecfd1795a0) | Jan 22, 2023 |
| ASRock        | B75M-GL R2.0                | [19b61442fe](https://linux-hardware.org/?probe=19b61442fe) | Jan 22, 2023 |
| ASRock        | B360 Pro4                   | [9cd508a59c](https://linux-hardware.org/?probe=9cd508a59c) | Jan 22, 2023 |
| ASUSTek       | P5E-VM SE                   | [a0b3d87534](https://linux-hardware.org/?probe=a0b3d87534) | Jan 22, 2023 |
| Dell          | 0JP3NX A01                  | [7189416b97](https://linux-hardware.org/?probe=7189416b97) | Jan 22, 2023 |
| Huanan        | H97-ZD3 V2.0                | [afb82fa3cf](https://linux-hardware.org/?probe=afb82fa3cf) | Jan 22, 2023 |
| MSI           | H97 GAMING 3                | [c861b7e450](https://linux-hardware.org/?probe=c861b7e450) | Jan 22, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [e967d42f1b](https://linux-hardware.org/?probe=e967d42f1b) | Jan 22, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [77a744c052](https://linux-hardware.org/?probe=77a744c052) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9672c4222a](https://linux-hardware.org/?probe=9672c4222a) | Jan 21, 2023 |
| ASUSTek       | P7H55-M                     | [18efa12cb2](https://linux-hardware.org/?probe=18efa12cb2) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| MSI           | B75MA-E33                   | [df4c3bb4d2](https://linux-hardware.org/?probe=df4c3bb4d2) | Jan 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | [3a1d7fb570](https://linux-hardware.org/?probe=3a1d7fb570) | Jan 21, 2023 |
| ASUSTek       | P7H55-USB3                  | [3f270588f4](https://linux-hardware.org/?probe=3f270588f4) | Jan 21, 2023 |
| ASRock        | 880GMH/U3S3                 | [f2dff18301](https://linux-hardware.org/?probe=f2dff18301) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [b6b4b01344](https://linux-hardware.org/?probe=b6b4b01344) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Supermicro    | X9DR6-LN4+                  | [23fe7b0642](https://linux-hardware.org/?probe=23fe7b0642) | Jan 20, 2023 |
| Supermicro    | X9DR6-LN4+                  | [4e099f57d5](https://linux-hardware.org/?probe=4e099f57d5) | Jan 20, 2023 |
| Gigabyte      | A520M H                     | [db3b391bd0](https://linux-hardware.org/?probe=db3b391bd0) | Jan 20, 2023 |
| MSI           | Z490-A PRO                  | [712d12e3e9](https://linux-hardware.org/?probe=712d12e3e9) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| ASUSTek       | P5E-VM SE                   | [b3df4a1dfa](https://linux-hardware.org/?probe=b3df4a1dfa) | Jan 20, 2023 |
| MSI           | H510M PRO-E                 | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| HP            | 3047h                       | [4bbcb58967](https://linux-hardware.org/?probe=4bbcb58967) | Jan 20, 2023 |
| MSI           | PH61-SP35                   | [3bdfad797c](https://linux-hardware.org/?probe=3bdfad797c) | Jan 20, 2023 |
| ASUSTek       | M5A78L-M LE                 | [af00f739f8](https://linux-hardware.org/?probe=af00f739f8) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| ASRock        | B450M Pro4-F                | [031b7e3b0a](https://linux-hardware.org/?probe=031b7e3b0a) | Jan 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [4ebd222ef1](https://linux-hardware.org/?probe=4ebd222ef1) | Jan 20, 2023 |
| HP            | 18E4                        | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Gigabyte      | H510M H                     | [f44f319e21](https://linux-hardware.org/?probe=f44f319e21) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Gigabyte      | B560M DS3H V2               | [d53ffd975c](https://linux-hardware.org/?probe=d53ffd975c) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| Huanan        | X99-F8D V2.4                | [26bc61b381](https://linux-hardware.org/?probe=26bc61b381) | Jan 19, 2023 |
| ASRock        | X99 Professional Gaming ... | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| AZW           | U59                         | [6621409d8c](https://linux-hardware.org/?probe=6621409d8c) | Jan 19, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| Biostar       | A780LB                      | [ffce251f42](https://linux-hardware.org/?probe=ffce251f42) | Jan 19, 2023 |
| ASRock        | H110 Pro BTC+               | [f888822c0d](https://linux-hardware.org/?probe=f888822c0d) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [348a5d1848](https://linux-hardware.org/?probe=348a5d1848) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| Gigabyte      | H610M S2H DDR4              | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| ASUSTek       | P4P800                      | [f37bee349c](https://linux-hardware.org/?probe=f37bee349c) | Jan 18, 2023 |
| MSI           | PRO H610M-E DDR4            | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| ASUSTek       | P5G41T-M LX3                | [67dc4c315a](https://linux-hardware.org/?probe=67dc4c315a) | Jan 17, 2023 |
| ASUSTek       | P8Q77-M                     | [f883cb7c7b](https://linux-hardware.org/?probe=f883cb7c7b) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | [ac58bc440d](https://linux-hardware.org/?probe=ac58bc440d) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| ASRock        | H110 Pro BTC+               | [0b515319d8](https://linux-hardware.org/?probe=0b515319d8) | Jan 17, 2023 |
| ASRock        | H410M-HVS                   | [2024f1ae76](https://linux-hardware.org/?probe=2024f1ae76) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [b01089cba7](https://linux-hardware.org/?probe=b01089cba7) | Jan 17, 2023 |
| ASUSTek       | J1800I-C                    | [c32c7f2d35](https://linux-hardware.org/?probe=c32c7f2d35) | Jan 17, 2023 |
| Biostar       | A780LB                      | [fe4d79e9f8](https://linux-hardware.org/?probe=fe4d79e9f8) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [bffcece8fb](https://linux-hardware.org/?probe=bffcece8fb) | Jan 17, 2023 |
| Gigabyte      | B360HD3                     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Gigabyte      | B450M H                     | [e3638a2110](https://linux-hardware.org/?probe=e3638a2110) | Jan 17, 2023 |
| ASRock        | H61M-HVGS                   | [2256e1c087](https://linux-hardware.org/?probe=2256e1c087) | Jan 17, 2023 |
| Gigabyte      | B560M DS3H V2               | [e29ceaa96c](https://linux-hardware.org/?probe=e29ceaa96c) | Jan 17, 2023 |
| Gigabyte      | H310M H                     | [faa3746295](https://linux-hardware.org/?probe=faa3746295) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM SE2                | [72e3ebc3b8](https://linux-hardware.org/?probe=72e3ebc3b8) | Jan 17, 2023 |
| ASUSTek       | H81-PLUS                    | [e95534600a](https://linux-hardware.org/?probe=e95534600a) | Jan 16, 2023 |
| Gigabyte      | A320M-S2H-CF                | [df0f33ee66](https://linux-hardware.org/?probe=df0f33ee66) | Jan 16, 2023 |
| Intel         | X99                         | [f966e7aa92](https://linux-hardware.org/?probe=f966e7aa92) | Jan 16, 2023 |
| Huanan        | H97-ZD3 V2.0                | [aececc6971](https://linux-hardware.org/?probe=aececc6971) | Jan 16, 2023 |
| MSI           | 970A-G43                    | [f15370df26](https://linux-hardware.org/?probe=f15370df26) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| Unknown       | T310D11                     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [2ebeb3fa1a](https://linux-hardware.org/?probe=2ebeb3fa1a) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| Gigabyte      | B450 GAMING X               | [c07c86ed27](https://linux-hardware.org/?probe=c07c86ed27) | Jan 16, 2023 |
| Gigabyte      | B450 GAMING X               | [f06080b088](https://linux-hardware.org/?probe=f06080b088) | Jan 16, 2023 |
| ASUSTek       | P8H77-V                     | [d136e01384](https://linux-hardware.org/?probe=d136e01384) | Jan 16, 2023 |
| Gigabyte      | MZBSWMP-00                  | [c1660ab5a4](https://linux-hardware.org/?probe=c1660ab5a4) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [939ab29431](https://linux-hardware.org/?probe=939ab29431) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| ASRock        | Z77 Pro4-M                  | [4c8f01cfd7](https://linux-hardware.org/?probe=4c8f01cfd7) | Jan 15, 2023 |
| MSI           | 970A-G43                    | [669512ff6c](https://linux-hardware.org/?probe=669512ff6c) | Jan 15, 2023 |
| ASUSTek       | P7H55-USB3                  | [d412197c51](https://linux-hardware.org/?probe=d412197c51) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS M                | [ac596694bd](https://linux-hardware.org/?probe=ac596694bd) | Jan 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [fe4b311f78](https://linux-hardware.org/?probe=fe4b311f78) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a65831f165](https://linux-hardware.org/?probe=a65831f165) | Jan 15, 2023 |
| ASUSTek       | P5E-VM SE                   | [af5169b24d](https://linux-hardware.org/?probe=af5169b24d) | Jan 15, 2023 |
| PLEXHD        | X79T rev. V1.0              | [9c8c729f1c](https://linux-hardware.org/?probe=9c8c729f1c) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS M                | [89a3800060](https://linux-hardware.org/?probe=89a3800060) | Jan 15, 2023 |
| Intel         | X99 V1.0                    | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [c59c9570d6](https://linux-hardware.org/?probe=c59c9570d6) | Jan 14, 2023 |
| Acer          | Aspire XC-830               | [1d9206b1f1](https://linux-hardware.org/?probe=1d9206b1f1) | Jan 14, 2023 |
| MSI           | B450M MORTAR MAX            | [1e42d818dd](https://linux-hardware.org/?probe=1e42d818dd) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | [77adbc7487](https://linux-hardware.org/?probe=77adbc7487) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | [e430030b47](https://linux-hardware.org/?probe=e430030b47) | Jan 14, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [69819d1ce1](https://linux-hardware.org/?probe=69819d1ce1) | Jan 14, 2023 |
| ASRock        | N68C-S UCC                  | [7c5f173e5c](https://linux-hardware.org/?probe=7c5f173e5c) | Jan 13, 2023 |
| ASRock        | A320M-HDV R4.0              | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [7cde78238f](https://linux-hardware.org/?probe=7cde78238f) | Jan 13, 2023 |
| ASUSTek       | P8H77-V LE                  | [ae418043f3](https://linux-hardware.org/?probe=ae418043f3) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | [e33042f453](https://linux-hardware.org/?probe=e33042f453) | Jan 13, 2023 |
| MSI           | B450M MORTAR MAX            | [e840ab1f61](https://linux-hardware.org/?probe=e840ab1f61) | Jan 13, 2023 |
| Gigabyte      | G41MT-S2                    | [25b6ab4c75](https://linux-hardware.org/?probe=25b6ab4c75) | Jan 12, 2023 |
| ASUSTek       | H81M-K                      | [8c3dc4bac3](https://linux-hardware.org/?probe=8c3dc4bac3) | Jan 12, 2023 |
| ASUSTek       | P5E-VM SE                   | [feee0755d0](https://linux-hardware.org/?probe=feee0755d0) | Jan 12, 2023 |
| ASUSTek       | H81M-K                      | [14ed7f9591](https://linux-hardware.org/?probe=14ed7f9591) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| Gigabyte      | X570S UD                    | [e3458505fd](https://linux-hardware.org/?probe=e3458505fd) | Jan 12, 2023 |
| Gigabyte      | H510M H                     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| Intel         | X79G V2.x                   | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| ASRock        | B450M Pro4                  | [5b24178097](https://linux-hardware.org/?probe=5b24178097) | Jan 11, 2023 |
| ASUSTek       | P7H55-USB3                  | [ae85db39c6](https://linux-hardware.org/?probe=ae85db39c6) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b8df2d6479](https://linux-hardware.org/?probe=b8df2d6479) | Jan 11, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [49863a504f](https://linux-hardware.org/?probe=49863a504f) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [4074262fd3](https://linux-hardware.org/?probe=4074262fd3) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a1e541c1b3](https://linux-hardware.org/?probe=a1e541c1b3) | Jan 11, 2023 |
| Intel         | SKYBAY                      | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Gigabyte      | B360HD3                     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| Intel         | SKYBAY                      | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [e9a8dfc18e](https://linux-hardware.org/?probe=e9a8dfc18e) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a57b3e3df6](https://linux-hardware.org/?probe=a57b3e3df6) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [694c5c31f9](https://linux-hardware.org/?probe=694c5c31f9) | Jan 10, 2023 |
| Gigabyte      | H61M-S2PV                   | [8248661973](https://linux-hardware.org/?probe=8248661973) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| Gigabyte      | H61M-DS2                    | [69ceed18f7](https://linux-hardware.org/?probe=69ceed18f7) | Jan 10, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [3b99403f0f](https://linux-hardware.org/?probe=3b99403f0f) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [286d590fda](https://linux-hardware.org/?probe=286d590fda) | Jan 10, 2023 |
| ECS           | BSWI-D2                     | [74f6bf3564](https://linux-hardware.org/?probe=74f6bf3564) | Jan 10, 2023 |
| ASRock        | H110 Pro BTC+               | [685765625e](https://linux-hardware.org/?probe=685765625e) | Jan 10, 2023 |
| ASUSTek       | PRIME B460-PLUS             | [88840b68e3](https://linux-hardware.org/?probe=88840b68e3) | Jan 10, 2023 |
| ASUSTek       | P7H55-M                     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Acer          | Aspire TC-605               | [77ecead5ed](https://linux-hardware.org/?probe=77ecead5ed) | Jan 09, 2023 |
| ASUSTek       | P5E-VM SE                   | [d9f3023575](https://linux-hardware.org/?probe=d9f3023575) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [ef4b23a73d](https://linux-hardware.org/?probe=ef4b23a73d) | Jan 09, 2023 |
| HP            | 18E6                        | [61070949ee](https://linux-hardware.org/?probe=61070949ee) | Jan 09, 2023 |
| Gigabyte      | GA-870A-UD3                 | [49beabba6b](https://linux-hardware.org/?probe=49beabba6b) | Jan 09, 2023 |
| Acer          | Veriton N4660G              | [8f27f893b1](https://linux-hardware.org/?probe=8f27f893b1) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [2a22078fe1](https://linux-hardware.org/?probe=2a22078fe1) | Jan 09, 2023 |
| Gigabyte      | 965P-DS3                    | [1b27c7404f](https://linux-hardware.org/?probe=1b27c7404f) | Jan 09, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [d5c81ffaec](https://linux-hardware.org/?probe=d5c81ffaec) | Jan 09, 2023 |
| ASRock        | AB350 Pro4                  | [66805743c5](https://linux-hardware.org/?probe=66805743c5) | Jan 09, 2023 |
| ASUSTek       | PRIME B560M-A               | [3447d8086d](https://linux-hardware.org/?probe=3447d8086d) | Jan 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4dd5ee2fa8](https://linux-hardware.org/?probe=4dd5ee2fa8) | Jan 09, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [50032f13ef](https://linux-hardware.org/?probe=50032f13ef) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [8ddf09108e](https://linux-hardware.org/?probe=8ddf09108e) | Jan 08, 2023 |
| ASUSTek       | Z170-K                      | [896e860da1](https://linux-hardware.org/?probe=896e860da1) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [61f4028846](https://linux-hardware.org/?probe=61f4028846) | Jan 08, 2023 |
| ASUSTek       | P5B                         | [9fd56e9b73](https://linux-hardware.org/?probe=9fd56e9b73) | Jan 08, 2023 |
| ASRock        | Z77 Extreme3                | [51f731b0f4](https://linux-hardware.org/?probe=51f731b0f4) | Jan 08, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [8ef8c9baa7](https://linux-hardware.org/?probe=8ef8c9baa7) | Jan 08, 2023 |
| ASRock        | 960GM-VGS3 FX               | [5b64e74a17](https://linux-hardware.org/?probe=5b64e74a17) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [49f4c2fbc8](https://linux-hardware.org/?probe=49f4c2fbc8) | Jan 08, 2023 |
| ASUSTek       | P5QL PRO                    | [e5d4ce1aa7](https://linux-hardware.org/?probe=e5d4ce1aa7) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | P8H77-V                     | [85e7e56c1d](https://linux-hardware.org/?probe=85e7e56c1d) | Jan 08, 2023 |
| ASUSTek       | P6X58D-E                    | [0fdf612101](https://linux-hardware.org/?probe=0fdf612101) | Jan 08, 2023 |
| ASUSTek       | PRIME B365M-A               | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| Foxconn       | H55MXV Series               | [8722a85ee1](https://linux-hardware.org/?probe=8722a85ee1) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | [93957e7a70](https://linux-hardware.org/?probe=93957e7a70) | Jan 07, 2023 |
| Gigabyte      | GA-MA770-UD3                | [b4bf97514d](https://linux-hardware.org/?probe=b4bf97514d) | Jan 07, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f811d71835](https://linux-hardware.org/?probe=f811d71835) | Jan 07, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [829138fad9](https://linux-hardware.org/?probe=829138fad9) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [9193043004](https://linux-hardware.org/?probe=9193043004) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [a6d1d6523b](https://linux-hardware.org/?probe=a6d1d6523b) | Jan 07, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [af95c3e61e](https://linux-hardware.org/?probe=af95c3e61e) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [4f26146dd8](https://linux-hardware.org/?probe=4f26146dd8) | Jan 07, 2023 |
| Gigabyte      | H610M H DDR4                | [f139bfc805](https://linux-hardware.org/?probe=f139bfc805) | Jan 07, 2023 |
| ASRock        | X300M-STX                   | [55db2decf3](https://linux-hardware.org/?probe=55db2decf3) | Jan 07, 2023 |
| MB            | A320-SF110                  | [d23ec63d82](https://linux-hardware.org/?probe=d23ec63d82) | Jan 07, 2023 |
| ASUSTek       | PRIME B460M-A               | [b5dd8ee9f3](https://linux-hardware.org/?probe=b5dd8ee9f3) | Jan 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6893b29920](https://linux-hardware.org/?probe=6893b29920) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a9288e85f6](https://linux-hardware.org/?probe=a9288e85f6) | Jan 06, 2023 |
| ASRock        | 960GM-VGS3 FX               | [633f31b57e](https://linux-hardware.org/?probe=633f31b57e) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [30bf1793c5](https://linux-hardware.org/?probe=30bf1793c5) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | [843dbca31d](https://linux-hardware.org/?probe=843dbca31d) | Jan 06, 2023 |
| ASUSTek       | P8H77-V LE                  | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| MB            | A320-SF110                  | [5b690cf226](https://linux-hardware.org/?probe=5b690cf226) | Jan 06, 2023 |
| ASRock        | A320D4-P1                   | [b6a61f9d2d](https://linux-hardware.org/?probe=b6a61f9d2d) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| Gigabyte      | H61M-S1                     | [7b61bf12d0](https://linux-hardware.org/?probe=7b61bf12d0) | Jan 06, 2023 |
| ASRock        | D1800M                      | [f70a4786d7](https://linux-hardware.org/?probe=f70a4786d7) | Jan 06, 2023 |
| ASUSTek       | P7H55-USB3                  | [e94f2584b0](https://linux-hardware.org/?probe=e94f2584b0) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6cd2288696](https://linux-hardware.org/?probe=6cd2288696) | Jan 06, 2023 |
| Gigabyte      | H77M-D3H                    | [8a0c5b7924](https://linux-hardware.org/?probe=8a0c5b7924) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | [0f4c3a7053](https://linux-hardware.org/?probe=0f4c3a7053) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| MSI           | H61M-P20                    | [f48c04fe8f](https://linux-hardware.org/?probe=f48c04fe8f) | Jan 05, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| ASRock        | M3A770DE                    | [952caf04f8](https://linux-hardware.org/?probe=952caf04f8) | Jan 05, 2023 |
| ASUSTek       | M2N68 Plus                  | [12309f8c91](https://linux-hardware.org/?probe=12309f8c91) | Jan 05, 2023 |
| ASRock        | Z77M                        | [fe6f6a7b05](https://linux-hardware.org/?probe=fe6f6a7b05) | Jan 05, 2023 |
| ASRock        | X570 Steel Legend           | [584234b202](https://linux-hardware.org/?probe=584234b202) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | [e1b3de18e9](https://linux-hardware.org/?probe=e1b3de18e9) | Jan 05, 2023 |
| ASUSTek       | A55BM-PLUS                  | [8601b7f2e9](https://linux-hardware.org/?probe=8601b7f2e9) | Jan 04, 2023 |
| ASRock        | H510M-HVS                   | [738739788a](https://linux-hardware.org/?probe=738739788a) | Jan 04, 2023 |
| Maibenben     | PC34 V1.0                   | [0ed25644b7](https://linux-hardware.org/?probe=0ed25644b7) | Jan 04, 2023 |
| Gigabyte      | P35-DS3L                    | [c07ba0a973](https://linux-hardware.org/?probe=c07ba0a973) | Jan 04, 2023 |
| ECS           | G41T-M2                     | [8df8f82fb8](https://linux-hardware.org/?probe=8df8f82fb8) | Jan 04, 2023 |
| ASRock        | FM2A85X Extreme4            | [67f24d7bfa](https://linux-hardware.org/?probe=67f24d7bfa) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| MSI           | A320M GRENADE               | [5e6f9a181c](https://linux-hardware.org/?probe=5e6f9a181c) | Jan 04, 2023 |
| MSI           | MS-B0A41                    | [f57c26d714](https://linux-hardware.org/?probe=f57c26d714) | Jan 04, 2023 |
| MSI           | B550-A PRO                  | [36c23fdfd7](https://linux-hardware.org/?probe=36c23fdfd7) | Jan 04, 2023 |
| Lenovo        | H420                        | [0765ceb3e8](https://linux-hardware.org/?probe=0765ceb3e8) | Jan 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [89868317cd](https://linux-hardware.org/?probe=89868317cd) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [c8618e40a6](https://linux-hardware.org/?probe=c8618e40a6) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASRock        | N68-GS4 FX                  | [f55d8b7bc9](https://linux-hardware.org/?probe=f55d8b7bc9) | Jan 03, 2023 |
| Gigabyte      | H470M DS3H                  | [07e46fc5f7](https://linux-hardware.org/?probe=07e46fc5f7) | Jan 03, 2023 |
| Gigabyte      | H61M-S1                     | [5ea753453b](https://linux-hardware.org/?probe=5ea753453b) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Gigabyte      | H61M-S2PV                   | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| ASUSTek       | P8Z68-M PRO                 | [33b212da3e](https://linux-hardware.org/?probe=33b212da3e) | Jan 02, 2023 |
| AZW           | MINI S                      | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| OEM           | Intel H81                   | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | H55M-USB3                   | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| Gigabyte      | EP45-DS3L                   | [e818c3c6ed](https://linux-hardware.org/?probe=e818c3c6ed) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| Huanan        | X99 F8D V2.2                | [c1818201ce](https://linux-hardware.org/?probe=c1818201ce) | Jan 01, 2023 |
| ASUSTek       | P8H67                       | [33bf029e5f](https://linux-hardware.org/?probe=33bf029e5f) | Jan 01, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | MS-B0A41                    | [c69ab6fbe8](https://linux-hardware.org/?probe=c69ab6fbe8) | Jan 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e18f6635d3](https://linux-hardware.org/?probe=e18f6635d3) | Dec 31, 2022 |
| Phoenix       | 945GM                       | [d391eaf6e2](https://linux-hardware.org/?probe=d391eaf6e2) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | [dff8a56537](https://linux-hardware.org/?probe=dff8a56537) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [8fdced7ae8](https://linux-hardware.org/?probe=8fdced7ae8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b0a607e8d8](https://linux-hardware.org/?probe=b0a607e8d8) | Dec 30, 2022 |
| ASRock        | J3455-ITX                   | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | [4ea88219d8](https://linux-hardware.org/?probe=4ea88219d8) | Dec 30, 2022 |
| AZW           | U59                         | [290e34b89a](https://linux-hardware.org/?probe=290e34b89a) | Dec 30, 2022 |
| ASRock        | N68-GS4 FX                  | [379552e4d2](https://linux-hardware.org/?probe=379552e4d2) | Dec 30, 2022 |
| ASUSTek       | PRIME B560M-A               | [ee7c086eb6](https://linux-hardware.org/?probe=ee7c086eb6) | Dec 30, 2022 |
| ASUSTek       | UN65U                       | [b7f1365865](https://linux-hardware.org/?probe=b7f1365865) | Dec 30, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [aa6b264eb4](https://linux-hardware.org/?probe=aa6b264eb4) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [6621ba66ac](https://linux-hardware.org/?probe=6621ba66ac) | Dec 30, 2022 |
| Gigabyte      | B550 GAMING X               | [6e92b3e37b](https://linux-hardware.org/?probe=6e92b3e37b) | Dec 29, 2022 |
| ASUSTek       | H97-PRO                     | [b96b861fd7](https://linux-hardware.org/?probe=b96b861fd7) | Dec 29, 2022 |
| ASRock        | B550 Taichi                 | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| ASUSTek       | PRIME A320M-A               | [2cdb821b42](https://linux-hardware.org/?probe=2cdb821b42) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2L                  | [660194090d](https://linux-hardware.org/?probe=660194090d) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2L                  | [7ba365cac3](https://linux-hardware.org/?probe=7ba365cac3) | Dec 29, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [b3970a8e5a](https://linux-hardware.org/?probe=b3970a8e5a) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [556bc61c51](https://linux-hardware.org/?probe=556bc61c51) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [f0ab6f0649](https://linux-hardware.org/?probe=f0ab6f0649) | Dec 29, 2022 |
| ASRock        | B450 Gaming K4              | [1afc5015f1](https://linux-hardware.org/?probe=1afc5015f1) | Dec 28, 2022 |
| ASUSTek       | PRIME B450M-A               | [422238387a](https://linux-hardware.org/?probe=422238387a) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [519607ec55](https://linux-hardware.org/?probe=519607ec55) | Dec 28, 2022 |
| ASUSTek       | M4A79XTD EVO                | [91c217e497](https://linux-hardware.org/?probe=91c217e497) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| ASUSTek       | M4A785-M                    | [7fb63e4360](https://linux-hardware.org/?probe=7fb63e4360) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| MSI           | B350 PC MATE                | [3b9dbdb180](https://linux-hardware.org/?probe=3b9dbdb180) | Dec 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [1aac1f7eca](https://linux-hardware.org/?probe=1aac1f7eca) | Dec 27, 2022 |
| Gigabyte      | H97-HD3                     | [1707593d6d](https://linux-hardware.org/?probe=1707593d6d) | Dec 27, 2022 |
| ASRock        | H510M-HVS                   | [3733446191](https://linux-hardware.org/?probe=3733446191) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| Pegatron      | APX85-GS                    | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [731f916db1](https://linux-hardware.org/?probe=731f916db1) | Dec 27, 2022 |
| Gigabyte      | GA-890XA-UD3                | [492719506f](https://linux-hardware.org/?probe=492719506f) | Dec 27, 2022 |
| Gigabyte      | H510M S2H V2                | [a47cb3fa7c](https://linux-hardware.org/?probe=a47cb3fa7c) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Gigabyte      | H510M S2H V2                | [7ddc3d0292](https://linux-hardware.org/?probe=7ddc3d0292) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| Gigabyte      | B365M DS3H                  | [f9d83535bd](https://linux-hardware.org/?probe=f9d83535bd) | Dec 26, 2022 |
| Gigabyte      | F2A55M-DS2                  | [735d3cfda2](https://linux-hardware.org/?probe=735d3cfda2) | Dec 26, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | [0fa5809533](https://linux-hardware.org/?probe=0fa5809533) | Dec 26, 2022 |
| Gigabyte      | H61M-S1                     | [384000d018](https://linux-hardware.org/?probe=384000d018) | Dec 25, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [5174af9fdd](https://linux-hardware.org/?probe=5174af9fdd) | Dec 25, 2022 |
| ASRock        | H110 Pro BTC+               | [29311fe64c](https://linux-hardware.org/?probe=29311fe64c) | Dec 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| ASUSTek       | H81M-K                      | [c702bed39d](https://linux-hardware.org/?probe=c702bed39d) | Dec 25, 2022 |
| ASUSTek       | P7H55-M/USB3                | [85b55a267a](https://linux-hardware.org/?probe=85b55a267a) | Dec 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8994b9a877](https://linux-hardware.org/?probe=8994b9a877) | Dec 25, 2022 |
| ASUSTek       | F1A55-M LX R2.0             | [177c5ee2a6](https://linux-hardware.org/?probe=177c5ee2a6) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c545cf1f08](https://linux-hardware.org/?probe=c545cf1f08) | Dec 25, 2022 |
| ASRock        | H110 Pro BTC+               | [90f3fd2f80](https://linux-hardware.org/?probe=90f3fd2f80) | Dec 25, 2022 |
| Huanan        | B660-D4 V1.0                | [2a3d5dc01f](https://linux-hardware.org/?probe=2a3d5dc01f) | Dec 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [f48ac4aa81](https://linux-hardware.org/?probe=f48ac4aa81) | Dec 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b98be1b1e7](https://linux-hardware.org/?probe=b98be1b1e7) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [5368526dc0](https://linux-hardware.org/?probe=5368526dc0) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [fab270a7bf](https://linux-hardware.org/?probe=fab270a7bf) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | [84ea64b29c](https://linux-hardware.org/?probe=84ea64b29c) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | [407f76f02f](https://linux-hardware.org/?probe=407f76f02f) | Dec 24, 2022 |
| ASRock        | B450 Gaming K4              | [bb8b44cf69](https://linux-hardware.org/?probe=bb8b44cf69) | Dec 24, 2022 |
| ASUSTek       | P8H67-M LE                  | [892d40f349](https://linux-hardware.org/?probe=892d40f349) | Dec 24, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [7edfc4df26](https://linux-hardware.org/?probe=7edfc4df26) | Dec 24, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [7f19b0ef63](https://linux-hardware.org/?probe=7f19b0ef63) | Dec 24, 2022 |
| ASUSTek       | P8H67-M LE                  | [7517437358](https://linux-hardware.org/?probe=7517437358) | Dec 24, 2022 |
| Gigabyte      | B660M D2H DDR4              | [c34803fb1e](https://linux-hardware.org/?probe=c34803fb1e) | Dec 24, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [6f60f1b6da](https://linux-hardware.org/?probe=6f60f1b6da) | Dec 24, 2022 |
| Dell          | 0Y5DDC A00                  | [c107bb3a14](https://linux-hardware.org/?probe=c107bb3a14) | Dec 24, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [83203eef25](https://linux-hardware.org/?probe=83203eef25) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| ASUSTek       | P8B75-V                     | [cf3882b3f7](https://linux-hardware.org/?probe=cf3882b3f7) | Dec 24, 2022 |
| Gigabyte      | H55M-S2H                    | [7cecfa756a](https://linux-hardware.org/?probe=7cecfa756a) | Dec 24, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [40c2593694](https://linux-hardware.org/?probe=40c2593694) | Dec 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [81febc2905](https://linux-hardware.org/?probe=81febc2905) | Dec 23, 2022 |
| ASUSTek       | H97-PLUS                    | [0d45265efc](https://linux-hardware.org/?probe=0d45265efc) | Dec 23, 2022 |
| Unknown       | 865GV-ICH5                  | [fe2ef2ef31](https://linux-hardware.org/?probe=fe2ef2ef31) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| ASUSTek       | H81M-C                      | [73dc1109eb](https://linux-hardware.org/?probe=73dc1109eb) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| Gigabyte      | H310M A-CF x.x              | [daf1310bfa](https://linux-hardware.org/?probe=daf1310bfa) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASUSTek       | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| ASUSTek       | P5K                         | [406d3a2d92](https://linux-hardware.org/?probe=406d3a2d92) | Dec 22, 2022 |
| Intel         | X99                         | [24e1c625cb](https://linux-hardware.org/?probe=24e1c625cb) | Dec 22, 2022 |
| Gigabyte      | EP43-DS3                    | [d0f0cd82f9](https://linux-hardware.org/?probe=d0f0cd82f9) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ae98ccd9c2](https://linux-hardware.org/?probe=ae98ccd9c2) | Dec 22, 2022 |
| Unknown       | 865GV-ICH5                  | [f42b7383f4](https://linux-hardware.org/?probe=f42b7383f4) | Dec 22, 2022 |
| ASRock        | A320M Pro4-F                | [4f2abe0c64](https://linux-hardware.org/?probe=4f2abe0c64) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [2683bf55bf](https://linux-hardware.org/?probe=2683bf55bf) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c485d688ad](https://linux-hardware.org/?probe=c485d688ad) | Dec 22, 2022 |
| DEPO Compu... | DPH410S                     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| ASUSTek       | P5K PRO                     | [4088ff40e3](https://linux-hardware.org/?probe=4088ff40e3) | Dec 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10a98289bb](https://linux-hardware.org/?probe=10a98289bb) | Dec 21, 2022 |
| ASUSTek       | VANGUARD B85                | [73560a1b6a](https://linux-hardware.org/?probe=73560a1b6a) | Dec 21, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [b7311f5a21](https://linux-hardware.org/?probe=b7311f5a21) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | [768834619c](https://linux-hardware.org/?probe=768834619c) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [c39538e70e](https://linux-hardware.org/?probe=c39538e70e) | Dec 21, 2022 |
| MSI           | A320M-A PRO                 | [88eb56085f](https://linux-hardware.org/?probe=88eb56085f) | Dec 21, 2022 |
| ASRock        | ALiveXFire-eSATA2           | [e7383e309b](https://linux-hardware.org/?probe=e7383e309b) | Dec 21, 2022 |
| MSI           | B450-A PRO MAX              | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Gigabyte      | EP41-UD3L                   | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Gigabyte      | EP43-S3L                    | [8a24afa21d](https://linux-hardware.org/?probe=8a24afa21d) | Dec 20, 2022 |
| Intel         | X99                         | [ce9b83b781](https://linux-hardware.org/?probe=ce9b83b781) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [e7cfce65f6](https://linux-hardware.org/?probe=e7cfce65f6) | Dec 20, 2022 |
| ASUSTek       | P5QL PRO                    | [44d3238797](https://linux-hardware.org/?probe=44d3238797) | Dec 20, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [65d1b97540](https://linux-hardware.org/?probe=65d1b97540) | Dec 20, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [18ad099caf](https://linux-hardware.org/?probe=18ad099caf) | Dec 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| ASUSTek       | H81M-C                      | [9ae92c3b1e](https://linux-hardware.org/?probe=9ae92c3b1e) | Dec 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [a39b8f54af](https://linux-hardware.org/?probe=a39b8f54af) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [7c854ad5e0](https://linux-hardware.org/?probe=7c854ad5e0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [f82010222c](https://linux-hardware.org/?probe=f82010222c) | Dec 20, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dd024e0315](https://linux-hardware.org/?probe=dd024e0315) | Dec 20, 2022 |
| ASRock        | Z77M                        | [33c2afa3e0](https://linux-hardware.org/?probe=33c2afa3e0) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| Unknown       | Unknown                     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Gigabyte      | B85-HD3                     | [a8d78baa67](https://linux-hardware.org/?probe=a8d78baa67) | Dec 19, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [70b20b876e](https://linux-hardware.org/?probe=70b20b876e) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | [de20614d06](https://linux-hardware.org/?probe=de20614d06) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [66e45d9a82](https://linux-hardware.org/?probe=66e45d9a82) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | [90ea21bd4a](https://linux-hardware.org/?probe=90ea21bd4a) | Dec 19, 2022 |
| ASUSTek       | P7P55D EVO                  | [c8f2df83aa](https://linux-hardware.org/?probe=c8f2df83aa) | Dec 19, 2022 |
| ASRock        | P67 Pro3 SE                 | [5a59282fea](https://linux-hardware.org/?probe=5a59282fea) | Dec 19, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| Dell          | 0Y5DDC A00                  | [aa5228e9b8](https://linux-hardware.org/?probe=aa5228e9b8) | Dec 19, 2022 |
| ASRock        | H110 Pro BTC+               | [b44ba7da8e](https://linux-hardware.org/?probe=b44ba7da8e) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| Intel         | MAHOBAY                     | [7f8c2370d4](https://linux-hardware.org/?probe=7f8c2370d4) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [afcae667f0](https://linux-hardware.org/?probe=afcae667f0) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [8d21cb0063](https://linux-hardware.org/?probe=8d21cb0063) | Dec 18, 2022 |
| Gigabyte      | GA-K8NE                     | [64adeb3e60](https://linux-hardware.org/?probe=64adeb3e60) | Dec 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [626b750c51](https://linux-hardware.org/?probe=626b750c51) | Dec 18, 2022 |
| Biostar       | TB250-BTC                   | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [4760b50d21](https://linux-hardware.org/?probe=4760b50d21) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7964862f29](https://linux-hardware.org/?probe=7964862f29) | Dec 18, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [320ef20ffa](https://linux-hardware.org/?probe=320ef20ffa) | Dec 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | [7e864dc271](https://linux-hardware.org/?probe=7e864dc271) | Dec 18, 2022 |
| Gigabyte      | P41T-D3P                    | [20f90ee21e](https://linux-hardware.org/?probe=20f90ee21e) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| MSI           | MS-B0A41                    | [3eff37d029](https://linux-hardware.org/?probe=3eff37d029) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1212530d94](https://linux-hardware.org/?probe=1212530d94) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [19e8973a92](https://linux-hardware.org/?probe=19e8973a92) | Dec 18, 2022 |
| Gigabyte      | H110N-CF                    | [239dcc2a5c](https://linux-hardware.org/?probe=239dcc2a5c) | Dec 18, 2022 |
| ASUSTek       | A88XM-A                     | [e889711ed9](https://linux-hardware.org/?probe=e889711ed9) | Dec 17, 2022 |
| ASUSTek       | M2N-XE                      | [5cf5b3eb1b](https://linux-hardware.org/?probe=5cf5b3eb1b) | Dec 17, 2022 |
| Gigabyte      | X570S AERO G                | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [43d229d12e](https://linux-hardware.org/?probe=43d229d12e) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a8936bc5e3](https://linux-hardware.org/?probe=a8936bc5e3) | Dec 17, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [74133cd0bd](https://linux-hardware.org/?probe=74133cd0bd) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [f9f06d0bcb](https://linux-hardware.org/?probe=f9f06d0bcb) | Dec 17, 2022 |
| Gigabyte      | M61SME-S2                   | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5f8287cae9](https://linux-hardware.org/?probe=5f8287cae9) | Dec 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0eb4a7c919](https://linux-hardware.org/?probe=0eb4a7c919) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | [d34f278afd](https://linux-hardware.org/?probe=d34f278afd) | Dec 17, 2022 |
| Gigabyte      | 970A-DS3P                   | [f0303dc0a9](https://linux-hardware.org/?probe=f0303dc0a9) | Dec 17, 2022 |
| Gigabyte      | H81-D3                      | [547126e9e7](https://linux-hardware.org/?probe=547126e9e7) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| HP            | 18E6                        | [62ae9ced0f](https://linux-hardware.org/?probe=62ae9ced0f) | Dec 16, 2022 |
| Biostar       | A10N-8800E                  | [bc96dc9caf](https://linux-hardware.org/?probe=bc96dc9caf) | Dec 16, 2022 |
| Gigabyte      | H110M-M2-CF                 | [11c0643905](https://linux-hardware.org/?probe=11c0643905) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Graviton      | DMB-H510-MCA01              | [702f634fc4](https://linux-hardware.org/?probe=702f634fc4) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| Gigabyte      | P75-D3                      | [32b4b4d664](https://linux-hardware.org/?probe=32b4b4d664) | Dec 16, 2022 |
| MSI           | B450I GAMING PLUS AC        | [59a22369a1](https://linux-hardware.org/?probe=59a22369a1) | Dec 16, 2022 |
| Huanan        | X99-QD4 V1.0                | [a959e56dc8](https://linux-hardware.org/?probe=a959e56dc8) | Dec 15, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [62395615bf](https://linux-hardware.org/?probe=62395615bf) | Dec 15, 2022 |
| ASRock        | X570 Pro4                   | [713a2bcaf4](https://linux-hardware.org/?probe=713a2bcaf4) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3807037a5c](https://linux-hardware.org/?probe=3807037a5c) | Dec 15, 2022 |
| MSI           | K9N6PGM2-V2                 | [c25f374572](https://linux-hardware.org/?probe=c25f374572) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [6367cb9215](https://linux-hardware.org/?probe=6367cb9215) | Dec 15, 2022 |
| ASRock        | H110 Pro BTC+               | [9821ed300c](https://linux-hardware.org/?probe=9821ed300c) | Dec 15, 2022 |
| ASRock        | A520M Pro4                  | [9a6fcc5f1b](https://linux-hardware.org/?probe=9a6fcc5f1b) | Dec 15, 2022 |
| MSI           | B450-A PRO MAX              | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [766e33e4fb](https://linux-hardware.org/?probe=766e33e4fb) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H410M H V3                  | [cf668e53f4](https://linux-hardware.org/?probe=cf668e53f4) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [db904895cc](https://linux-hardware.org/?probe=db904895cc) | Dec 15, 2022 |
| Gigabyte      | B360M D3H-CF                | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ASUSTek       | F2A55-M LE                  | [f4c6e3c225](https://linux-hardware.org/?probe=f4c6e3c225) | Dec 14, 2022 |
| Gigabyte      | H110M-S2-CF                 | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Gigabyte      | H77N-WIFI                   | [5093772c0f](https://linux-hardware.org/?probe=5093772c0f) | Dec 14, 2022 |
| Intel         | X79v2.72 KD V2.0            | [0e58af2a59](https://linux-hardware.org/?probe=0e58af2a59) | Dec 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c337db1381](https://linux-hardware.org/?probe=c337db1381) | Dec 14, 2022 |
| ASRock        | M3A770DE                    | [2e6b1f9c2d](https://linux-hardware.org/?probe=2e6b1f9c2d) | Dec 13, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [22431e9b10](https://linux-hardware.org/?probe=22431e9b10) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [0e9eba0773](https://linux-hardware.org/?probe=0e9eba0773) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [af674c6b1b](https://linux-hardware.org/?probe=af674c6b1b) | Dec 13, 2022 |
| AZW           | U59                         | [fd5ccbfbd2](https://linux-hardware.org/?probe=fd5ccbfbd2) | Dec 13, 2022 |
| Gigabyte      | Z590 UD AC                  | [895bd1b0b2](https://linux-hardware.org/?probe=895bd1b0b2) | Dec 13, 2022 |
| ASUSTek       | PRIME H270-PRO              | [dc7d6ae170](https://linux-hardware.org/?probe=dc7d6ae170) | Dec 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Intel         | X79v2.72 KD V2.0            | [476f1e7cad](https://linux-hardware.org/?probe=476f1e7cad) | Dec 12, 2022 |
| MSI           | MEG B550 UNIFY              | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| Gigabyte      | B450 GAMING X               | [8918608744](https://linux-hardware.org/?probe=8918608744) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [2e0158ba73](https://linux-hardware.org/?probe=2e0158ba73) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [c6e03bcd07](https://linux-hardware.org/?probe=c6e03bcd07) | Dec 12, 2022 |
| Gigabyte      | B450M S2H                   | [c5220a0b87](https://linux-hardware.org/?probe=c5220a0b87) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| MSI           | Z97-G43 GAMING              | [982bf94727](https://linux-hardware.org/?probe=982bf94727) | Dec 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [7d4b5e1c20](https://linux-hardware.org/?probe=7d4b5e1c20) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f0fa1101ce](https://linux-hardware.org/?probe=f0fa1101ce) | Dec 11, 2022 |
| Gigabyte      | Z77-DS3H                    | [dbd992f05e](https://linux-hardware.org/?probe=dbd992f05e) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [f883834ef1](https://linux-hardware.org/?probe=f883834ef1) | Dec 11, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [9f72d262ef](https://linux-hardware.org/?probe=9f72d262ef) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [8bd005fd95](https://linux-hardware.org/?probe=8bd005fd95) | Dec 11, 2022 |
| ASUSTek       | PRIME B360M-K               | [aac6da2dfb](https://linux-hardware.org/?probe=aac6da2dfb) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| Gigabyte      | H77-DS3H                    | [4c52e333dd](https://linux-hardware.org/?probe=4c52e333dd) | Dec 10, 2022 |
| ASRock        | H81M-HDS R2.0               | [e3c2a2bc54](https://linux-hardware.org/?probe=e3c2a2bc54) | Dec 10, 2022 |
| ASRock        | Z270 Pro4                   | [9810ecf266](https://linux-hardware.org/?probe=9810ecf266) | Dec 10, 2022 |
| Intel         | D2500HN AAG81480-500        | [0963fa0173](https://linux-hardware.org/?probe=0963fa0173) | Dec 10, 2022 |
| ASUSTek       | PRIME B350M-A               | [619a4c2f87](https://linux-hardware.org/?probe=619a4c2f87) | Dec 10, 2022 |
| ASRock        | 760GM-HDV                   | [bbd75ce275](https://linux-hardware.org/?probe=bbd75ce275) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [941668ad89](https://linux-hardware.org/?probe=941668ad89) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [fc07cad186](https://linux-hardware.org/?probe=fc07cad186) | Dec 10, 2022 |
| ASUSTek       | Z170-P                      | [5180b907e3](https://linux-hardware.org/?probe=5180b907e3) | Dec 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [d11e502254](https://linux-hardware.org/?probe=d11e502254) | Dec 10, 2022 |
| HP            | 158A                        | [ebcf08f784](https://linux-hardware.org/?probe=ebcf08f784) | Dec 10, 2022 |
| ASRock        | H97 Anniversary             | [3f7aa1b6de](https://linux-hardware.org/?probe=3f7aa1b6de) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [f064a744ba](https://linux-hardware.org/?probe=f064a744ba) | Dec 10, 2022 |
| ASUSTek       | Z170-A                      | [c9df3386c5](https://linux-hardware.org/?probe=c9df3386c5) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Gigabyte      | H61N-USB3                   | [9a8885a88d](https://linux-hardware.org/?probe=9a8885a88d) | Dec 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | [75f1600dba](https://linux-hardware.org/?probe=75f1600dba) | Dec 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ed30003f61](https://linux-hardware.org/?probe=ed30003f61) | Dec 09, 2022 |
| Gigabyte      | B365M DS3H                  | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| Gigabyte      | D425TUD                     | [4d8c330a78](https://linux-hardware.org/?probe=4d8c330a78) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [b4bd04a5a0](https://linux-hardware.org/?probe=b4bd04a5a0) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [56a6a749bb](https://linux-hardware.org/?probe=56a6a749bb) | Dec 09, 2022 |
| ASRock        | H110M-DGS                   | [2311fd9c2f](https://linux-hardware.org/?probe=2311fd9c2f) | Dec 09, 2022 |
| ASUSTek       | M2N-X                       | [63a0188273](https://linux-hardware.org/?probe=63a0188273) | Dec 09, 2022 |
| Gigabyte      | G31M-S2L                    | [05707c88e0](https://linux-hardware.org/?probe=05707c88e0) | Dec 08, 2022 |
| Gigabyte      | H81M-S1                     | [c2ba58af35](https://linux-hardware.org/?probe=c2ba58af35) | Dec 08, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [4462cb3156](https://linux-hardware.org/?probe=4462cb3156) | Dec 08, 2022 |
| MSI           | PH61-SP35                   | [c3f5b1ddd3](https://linux-hardware.org/?probe=c3f5b1ddd3) | Dec 08, 2022 |
| Gigabyte      | P31-ES3G                    | [21c291e1e2](https://linux-hardware.org/?probe=21c291e1e2) | Dec 08, 2022 |
| Huanan        | X99 F8D V2.2                | [d960add854](https://linux-hardware.org/?probe=d960add854) | Dec 08, 2022 |
| ASRock        | H470M-HVS                   | [2f4b3b1185](https://linux-hardware.org/?probe=2f4b3b1185) | Dec 08, 2022 |
| ASUSTek       | P5W DH Deluxe               | [bedb81f629](https://linux-hardware.org/?probe=bedb81f629) | Dec 08, 2022 |
| ASUSTek       | H110-PLUS                   | [57e0d3651c](https://linux-hardware.org/?probe=57e0d3651c) | Dec 08, 2022 |
| ASUSTek       | H81M-R                      | [0858714315](https://linux-hardware.org/?probe=0858714315) | Dec 08, 2022 |
| Aquarius      | AQB560M                     | [3ac41202cf](https://linux-hardware.org/?probe=3ac41202cf) | Dec 08, 2022 |
| Gigabyte      | Z370M D3H-CF                | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| eMachines     | ET1350                      | [2d05a7a068](https://linux-hardware.org/?probe=2d05a7a068) | Dec 07, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [038581b13f](https://linux-hardware.org/?probe=038581b13f) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | [c4f63ee5a1](https://linux-hardware.org/?probe=c4f63ee5a1) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | [ae67b039af](https://linux-hardware.org/?probe=ae67b039af) | Dec 06, 2022 |
| HC Technol... | HCAR4000-MI                 | [596c3680f3](https://linux-hardware.org/?probe=596c3680f3) | Dec 06, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [0327ae6d81](https://linux-hardware.org/?probe=0327ae6d81) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K               | [7e82777792](https://linux-hardware.org/?probe=7e82777792) | Dec 06, 2022 |
| Gigabyte      | GA-MA770-ES3                | [70c1a43352](https://linux-hardware.org/?probe=70c1a43352) | Dec 06, 2022 |
| ASUSTek       | H170-PRO                    | [37cf939cbd](https://linux-hardware.org/?probe=37cf939cbd) | Dec 06, 2022 |
| ASUSTek       | M2N-XE                      | [663b3c7870](https://linux-hardware.org/?probe=663b3c7870) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K               | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | 0XHGV1 A00                  | [9b9778c525](https://linux-hardware.org/?probe=9b9778c525) | Dec 06, 2022 |
| ASUSTek       | P7H55-M                     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| ASRock        | P67 Pro                     | [74b28c3c76](https://linux-hardware.org/?probe=74b28c3c76) | Dec 06, 2022 |
| ASRock        | B450M-HDV                   | [afeed5f423](https://linux-hardware.org/?probe=afeed5f423) | Dec 05, 2022 |
| Gigabyte      | 970A-DS3P                   | [517e06781a](https://linux-hardware.org/?probe=517e06781a) | Dec 05, 2022 |
| MSI           | H110M PRO-VD                | [64c80c03cf](https://linux-hardware.org/?probe=64c80c03cf) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [76ce7610ea](https://linux-hardware.org/?probe=76ce7610ea) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| Gigabyte      | B450 GAMING X               | [c8b886d9bf](https://linux-hardware.org/?probe=c8b886d9bf) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [0301ad14ee](https://linux-hardware.org/?probe=0301ad14ee) | Dec 05, 2022 |
| ASUSTek       | A55BM-K                     | [e78b25a518](https://linux-hardware.org/?probe=e78b25a518) | Dec 05, 2022 |
| MSI           | H97 PC Mate                 | [b8081159ab](https://linux-hardware.org/?probe=b8081159ab) | Dec 05, 2022 |
| ASRock        | J4205-ITX                   | [f5eb647cc9](https://linux-hardware.org/?probe=f5eb647cc9) | Dec 04, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [930b8d0ff2](https://linux-hardware.org/?probe=930b8d0ff2) | Dec 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [10dd0b119a](https://linux-hardware.org/?probe=10dd0b119a) | Dec 04, 2022 |
| Unknown       | Unknown                     | [bdf0020add](https://linux-hardware.org/?probe=bdf0020add) | Dec 04, 2022 |
| HP            | 2AAC                        | [a6fb7751ed](https://linux-hardware.org/?probe=a6fb7751ed) | Dec 04, 2022 |
| Intel         | DG41CN AAE82429-102         | [8d5cd3253c](https://linux-hardware.org/?probe=8d5cd3253c) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [d3c99c8d63](https://linux-hardware.org/?probe=d3c99c8d63) | Dec 04, 2022 |
| Intel         | D2500HN AAG34776-404        | [b1ccefe421](https://linux-hardware.org/?probe=b1ccefe421) | Dec 04, 2022 |
| ASUSTek       | H81M-C                      | [0218d4ec25](https://linux-hardware.org/?probe=0218d4ec25) | Dec 03, 2022 |
| ASUSTek       | P5K                         | [c05392b19e](https://linux-hardware.org/?probe=c05392b19e) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-A               | [91d50f0379](https://linux-hardware.org/?probe=91d50f0379) | Dec 03, 2022 |
| Gigabyte      | P35-DS3                     | [f4be331a61](https://linux-hardware.org/?probe=f4be331a61) | Dec 03, 2022 |
| ASUSTek       | H81M-C                      | [ea7168ab4c](https://linux-hardware.org/?probe=ea7168ab4c) | Dec 03, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [1d881e7756](https://linux-hardware.org/?probe=1d881e7756) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [78746e7632](https://linux-hardware.org/?probe=78746e7632) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [ead86b243b](https://linux-hardware.org/?probe=ead86b243b) | Dec 03, 2022 |
| ASRock        | K10N78D                     | [7d0d581c7a](https://linux-hardware.org/?probe=7d0d581c7a) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [f1e82e8a2a](https://linux-hardware.org/?probe=f1e82e8a2a) | Dec 03, 2022 |
| ASRock        | H110 Pro BTC+               | [d485a9f321](https://linux-hardware.org/?probe=d485a9f321) | Dec 03, 2022 |
| Gigabyte      | 970A-UD3P                   | [7bb879efed](https://linux-hardware.org/?probe=7bb879efed) | Dec 03, 2022 |
| Gigabyte      | MZBSWMP-00                  | [76ba1ef6f2](https://linux-hardware.org/?probe=76ba1ef6f2) | Dec 03, 2022 |
| MSI           | P67S-C43                    | [9674663124](https://linux-hardware.org/?probe=9674663124) | Dec 03, 2022 |
| ASUSTek       | Z170M-PLUS                  | [a39dbe7189](https://linux-hardware.org/?probe=a39dbe7189) | Dec 03, 2022 |
| Gigabyte      | H61M-D2-B3                  | [0cc7f26d32](https://linux-hardware.org/?probe=0cc7f26d32) | Dec 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| Intel         | JSL MRD                     | [1a63097a67](https://linux-hardware.org/?probe=1a63097a67) | Dec 02, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5c0129ab3f](https://linux-hardware.org/?probe=5c0129ab3f) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [eaaeeb57fe](https://linux-hardware.org/?probe=eaaeeb57fe) | Dec 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| 3Q            | TD2500G-P-Q3 A01            | [46626558f6](https://linux-hardware.org/?probe=46626558f6) | Dec 01, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [16680c5211](https://linux-hardware.org/?probe=16680c5211) | Dec 01, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9866b7f07f](https://linux-hardware.org/?probe=9866b7f07f) | Dec 01, 2022 |
| Gigabyte      | B450 GAMING X               | [ff5aef2f59](https://linux-hardware.org/?probe=ff5aef2f59) | Dec 01, 2022 |
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| MSI           | H81M-E33                    | [aa874580d3](https://linux-hardware.org/?probe=aa874580d3) | Dec 01, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [010349b87b](https://linux-hardware.org/?probe=010349b87b) | Dec 01, 2022 |
| Gigabyte      | GA-990FXA-UD7               | [e300be2b5e](https://linux-hardware.org/?probe=e300be2b5e) | Dec 01, 2022 |
| ASUSTek       | P5B                         | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | P8H77-V LE                  | [d82ed03dd9](https://linux-hardware.org/?probe=d82ed03dd9) | Dec 01, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4ae619c728](https://linux-hardware.org/?probe=4ae619c728) | Dec 01, 2022 |
| Graviton      | DMB-H510-MCA01              | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| ASUSTek       | H81M-C                      | [458ea4bd06](https://linux-hardware.org/?probe=458ea4bd06) | Nov 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [99c33f6741](https://linux-hardware.org/?probe=99c33f6741) | Nov 29, 2022 |
| HP            | 8437                        | [c5bbfc32f6](https://linux-hardware.org/?probe=c5bbfc32f6) | Nov 29, 2022 |
| Lenovo        | 3162 SDK0J40697 WIN 3305... | [296ceaab80](https://linux-hardware.org/?probe=296ceaab80) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| ASRock        | N68C-S UCC                  | [c7bff3d908](https://linux-hardware.org/?probe=c7bff3d908) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| Dell          | 0Y5DDC A00                  | [5d4811b390](https://linux-hardware.org/?probe=5d4811b390) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [66fe0c3ddf](https://linux-hardware.org/?probe=66fe0c3ddf) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| ECS           | BSWI-D2                     | [b7e4fbdd31](https://linux-hardware.org/?probe=b7e4fbdd31) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [262228b1fb](https://linux-hardware.org/?probe=262228b1fb) | Nov 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | [be98ffe55b](https://linux-hardware.org/?probe=be98ffe55b) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Intel         | X79G V2.x                   | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Gigabyte      | B365M DS3H                  | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [245ea45167](https://linux-hardware.org/?probe=245ea45167) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Gigabyte      | B550 GAMING X               | [f8979201eb](https://linux-hardware.org/?probe=f8979201eb) | Nov 27, 2022 |
| ASUSTek       | P7H55-M                     | [e5ac492508](https://linux-hardware.org/?probe=e5ac492508) | Nov 27, 2022 |
| Unknown       | Unknown                     | [1a24753132](https://linux-hardware.org/?probe=1a24753132) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [3fda27c7b6](https://linux-hardware.org/?probe=3fda27c7b6) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e6a6d0affd](https://linux-hardware.org/?probe=e6a6d0affd) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [2a77cd8415](https://linux-hardware.org/?probe=2a77cd8415) | Nov 27, 2022 |
| ASUSTek       | PRIME B250M-K               | [73b4c53383](https://linux-hardware.org/?probe=73b4c53383) | Nov 27, 2022 |
| Koloe         | X58                         | [8b80e1a74c](https://linux-hardware.org/?probe=8b80e1a74c) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | [ff31791cfb](https://linux-hardware.org/?probe=ff31791cfb) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | [e09f910876](https://linux-hardware.org/?probe=e09f910876) | Nov 27, 2022 |
| ASRock        | H110M-DGS                   | [6667ba2bc2](https://linux-hardware.org/?probe=6667ba2bc2) | Nov 27, 2022 |
| MACHINIST     | X99-RS9 V3.1                | [86cead0335](https://linux-hardware.org/?probe=86cead0335) | Nov 27, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [4fa4184bfd](https://linux-hardware.org/?probe=4fa4184bfd) | Nov 26, 2022 |
| MSI           | J1800I                      | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | [0f4c0786c2](https://linux-hardware.org/?probe=0f4c0786c2) | Nov 26, 2022 |
| ASUSTek       | H110M-R                     | [f35782a773](https://linux-hardware.org/?probe=f35782a773) | Nov 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [f368bfcbe2](https://linux-hardware.org/?probe=f368bfcbe2) | Nov 26, 2022 |
| Gigabyte      | B560 HD3                    | [f7915b54fb](https://linux-hardware.org/?probe=f7915b54fb) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| ASUSTek       | P8H77-V LE                  | [c17b2fcd65](https://linux-hardware.org/?probe=c17b2fcd65) | Nov 26, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| MSI           | K9AG Neo2                   | [a57a6f079b](https://linux-hardware.org/?probe=a57a6f079b) | Nov 25, 2022 |
| ASRock        | H55M-LE                     | [75b9a8fb03](https://linux-hardware.org/?probe=75b9a8fb03) | Nov 25, 2022 |
| Gigabyte      | X570S UD                    | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| JGINYUE       | B660M-VDH                   | [bd879c87f8](https://linux-hardware.org/?probe=bd879c87f8) | Nov 25, 2022 |
| ASUSTek       | P5K                         | [87e7a3c0d0](https://linux-hardware.org/?probe=87e7a3c0d0) | Nov 25, 2022 |
| ASUSTek       | P8H61-MX                    | [d2e3977693](https://linux-hardware.org/?probe=d2e3977693) | Nov 25, 2022 |
| ASRock        | H110 Pro BTC+               | [db556f793b](https://linux-hardware.org/?probe=db556f793b) | Nov 25, 2022 |
| Gigabyte      | B250-FinTech-CF             | [fcc81ea02b](https://linux-hardware.org/?probe=fcc81ea02b) | Nov 24, 2022 |
| ASUSTek       | PRIME Z590-P                | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| MSI           | TRX40 PRO WIFI              | [3617f324a2](https://linux-hardware.org/?probe=3617f324a2) | Nov 24, 2022 |
| ASUSTek       | P5Q3                        | [655065ee03](https://linux-hardware.org/?probe=655065ee03) | Nov 24, 2022 |
| ASUSTek       | P5P43TD                     | [324669845a](https://linux-hardware.org/?probe=324669845a) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [8a5a155a45](https://linux-hardware.org/?probe=8a5a155a45) | Nov 24, 2022 |
| ASRock        | B560M-ITX/ac                | [3e1bbe410c](https://linux-hardware.org/?probe=3e1bbe410c) | Nov 24, 2022 |
| ASUSTek       | P5KPL-VM                    | [4e15e21f75](https://linux-hardware.org/?probe=4e15e21f75) | Nov 24, 2022 |
| ASUSTek       | H81M-C                      | [e892605084](https://linux-hardware.org/?probe=e892605084) | Nov 24, 2022 |
| ASUSTek       | P5K Premium                 | [5ff50a49ba](https://linux-hardware.org/?probe=5ff50a49ba) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [a17992aaa3](https://linux-hardware.org/?probe=a17992aaa3) | Nov 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [4617b6803a](https://linux-hardware.org/?probe=4617b6803a) | Nov 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e83d79d385](https://linux-hardware.org/?probe=e83d79d385) | Nov 23, 2022 |
| ASUSTek       | P8Z68-V LX                  | [7153762b68](https://linux-hardware.org/?probe=7153762b68) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [64728372e9](https://linux-hardware.org/?probe=64728372e9) | Nov 23, 2022 |
| Gigabyte      | G31M-ES2L                   | [e8ab5ad410](https://linux-hardware.org/?probe=e8ab5ad410) | Nov 23, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [3a36391d83](https://linux-hardware.org/?probe=3a36391d83) | Nov 22, 2022 |
| Gigabyte      | B450 GAMING X               | [c427f12dca](https://linux-hardware.org/?probe=c427f12dca) | Nov 22, 2022 |
| Gigabyte      | 970A-UD3P                   | [2cd736b247](https://linux-hardware.org/?probe=2cd736b247) | Nov 22, 2022 |
| ASUSTek       | PRIME B450M-A               | [49cb3f2e52](https://linux-hardware.org/?probe=49cb3f2e52) | Nov 22, 2022 |
| Biostar       | G41D3+                      | [6ce48937fe](https://linux-hardware.org/?probe=6ce48937fe) | Nov 22, 2022 |
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
| Dell          | 0Y5DDC A00                  | [37808c6686](https://linux-hardware.org/?probe=37808c6686) | Nov 22, 2022 |
| ASRock        | H55M-LE                     | [206082ac3f](https://linux-hardware.org/?probe=206082ac3f) | Nov 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [2575d2aab2](https://linux-hardware.org/?probe=2575d2aab2) | Nov 22, 2022 |
| Gigabyte      | B75M-D3V                    | [06396e3088](https://linux-hardware.org/?probe=06396e3088) | Nov 21, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| Gigabyte      | B365M DS3H                  | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | [a81c612515](https://linux-hardware.org/?probe=a81c612515) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | [ebc5b13d4e](https://linux-hardware.org/?probe=ebc5b13d4e) | Nov 21, 2022 |
| Biostar       | G41D3+                      | [d1d42fec13](https://linux-hardware.org/?probe=d1d42fec13) | Nov 21, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| Intel         | DG45ID AAE27729-310         | [81ecca3cd1](https://linux-hardware.org/?probe=81ecca3cd1) | Nov 20, 2022 |
| ASUSTek       | M4A785T-M                   | [451b8a6b52](https://linux-hardware.org/?probe=451b8a6b52) | Nov 20, 2022 |
| Gigabyte      | Z77X-D3H                    | [1702f14317](https://linux-hardware.org/?probe=1702f14317) | Nov 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [122a37af55](https://linux-hardware.org/?probe=122a37af55) | Nov 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [910d921a9d](https://linux-hardware.org/?probe=910d921a9d) | Nov 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | [b133dcd886](https://linux-hardware.org/?probe=b133dcd886) | Nov 20, 2022 |
| ASUSTek       | P7H55                       | [aaaefec31e](https://linux-hardware.org/?probe=aaaefec31e) | Nov 20, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [64953143a6](https://linux-hardware.org/?probe=64953143a6) | Nov 20, 2022 |
| ASRock        | P43ME                       | [3b90870750](https://linux-hardware.org/?probe=3b90870750) | Nov 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [5cf9d6d04e](https://linux-hardware.org/?probe=5cf9d6d04e) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [e8171566d3](https://linux-hardware.org/?probe=e8171566d3) | Nov 19, 2022 |
| ASUSTek       | P5K                         | [44b338a17d](https://linux-hardware.org/?probe=44b338a17d) | Nov 19, 2022 |
| Gigabyte      | G31M-ES2L                   | [3e3d8f727c](https://linux-hardware.org/?probe=3e3d8f727c) | Nov 19, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| ASUSTek       | P5KPL/1600                  | [b2e20d7f28](https://linux-hardware.org/?probe=b2e20d7f28) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Dell          | 0RY007                      | [d11a712f82](https://linux-hardware.org/?probe=d11a712f82) | Nov 18, 2022 |
| ASUSTek       | PRIME Z370-P                | [65abbfb38e](https://linux-hardware.org/?probe=65abbfb38e) | Nov 18, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Unknown       | Unknown                     | [53f563177d](https://linux-hardware.org/?probe=53f563177d) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c695addaa3](https://linux-hardware.org/?probe=c695addaa3) | Nov 18, 2022 |
| HP            | 8906 SMVB                   | [f644eba622](https://linux-hardware.org/?probe=f644eba622) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | [ceafbe876d](https://linux-hardware.org/?probe=ceafbe876d) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | [f6f8ae996d](https://linux-hardware.org/?probe=f6f8ae996d) | Nov 18, 2022 |
| Unknown       | P43Twins1600                | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASUSTek       | P8B75-V                     | [6f3b172132](https://linux-hardware.org/?probe=6f3b172132) | Nov 18, 2022 |
| MSI           | H110M PRO-VH PLUS           | [54f40f8c4b](https://linux-hardware.org/?probe=54f40f8c4b) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Dell          | 0Y5DDC A00                  | [99aed6e6d2](https://linux-hardware.org/?probe=99aed6e6d2) | Nov 17, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| Gigabyte      | A520M H                     | [d353571eef](https://linux-hardware.org/?probe=d353571eef) | Nov 17, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [814b71a20c](https://linux-hardware.org/?probe=814b71a20c) | Nov 17, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [f9da339cc7](https://linux-hardware.org/?probe=f9da339cc7) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| ASUSTek       | Z170-P                      | [735035876a](https://linux-hardware.org/?probe=735035876a) | Nov 17, 2022 |
| MSI           | B450M MORTAR MAX            | [2ea755455d](https://linux-hardware.org/?probe=2ea755455d) | Nov 16, 2022 |
| Biostar       | TH67XE                      | [47da767a5a](https://linux-hardware.org/?probe=47da767a5a) | Nov 16, 2022 |
| MSI           | H61M-P32/W8                 | [82cba9e87c](https://linux-hardware.org/?probe=82cba9e87c) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2                    | [757a1066ff](https://linux-hardware.org/?probe=757a1066ff) | Nov 16, 2022 |
| ASRock        | H310CM-DVS                  | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| Gigabyte      | P75-D3                      | [02bdf99508](https://linux-hardware.org/?probe=02bdf99508) | Nov 16, 2022 |
| ASRock        | J3455-ITX                   | [71c99edeb1](https://linux-hardware.org/?probe=71c99edeb1) | Nov 16, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [b0c0ad46de](https://linux-hardware.org/?probe=b0c0ad46de) | Nov 16, 2022 |
| ASUSTek       | B75M-A                      | [087a904af2](https://linux-hardware.org/?probe=087a904af2) | Nov 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ccf8236d38](https://linux-hardware.org/?probe=ccf8236d38) | Nov 16, 2022 |
| ASUSTek       | Z87-K                       | [39078e426c](https://linux-hardware.org/?probe=39078e426c) | Nov 16, 2022 |
| Gigabyte      | H110M-S2V-CF                | [74cdb80f42](https://linux-hardware.org/?probe=74cdb80f42) | Nov 16, 2022 |
| ASRock        | N68C-GS FX                  | [e7d93e8540](https://linux-hardware.org/?probe=e7d93e8540) | Nov 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| ASRock        | N68C-GS FX                  | [c67fea651e](https://linux-hardware.org/?probe=c67fea651e) | Nov 15, 2022 |
| ASRock        | N68-GS4 FX                  | [c651e62593](https://linux-hardware.org/?probe=c651e62593) | Nov 15, 2022 |
| ASRock        | H470M-HVS                   | [e69c2f0da4](https://linux-hardware.org/?probe=e69c2f0da4) | Nov 15, 2022 |
| ASRock        | B150M-HDS                   | [032d8f7c3c](https://linux-hardware.org/?probe=032d8f7c3c) | Nov 15, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| Unknown       | Intel X79                   | [61483ea15b](https://linux-hardware.org/?probe=61483ea15b) | Nov 14, 2022 |
| Graviton      | DMB-A520-MCA01              | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| Gigabyte      | B450M DS3H V2               | [dc808c4131](https://linux-hardware.org/?probe=dc808c4131) | Nov 14, 2022 |
| Gigabyte      | P75-D3                      | [37f9da1b7f](https://linux-hardware.org/?probe=37f9da1b7f) | Nov 14, 2022 |
| HP            | 2179                        | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | [191fa275ad](https://linux-hardware.org/?probe=191fa275ad) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | [0f8a90fef7](https://linux-hardware.org/?probe=0f8a90fef7) | Nov 14, 2022 |
| Gigabyte      | H77-DS3H                    | [f28540c049](https://linux-hardware.org/?probe=f28540c049) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [53a532435e](https://linux-hardware.org/?probe=53a532435e) | Nov 14, 2022 |
| Pegatron      | 2A94h                       | [5ebd2a4bf4](https://linux-hardware.org/?probe=5ebd2a4bf4) | Nov 13, 2022 |
| Gigabyte      | H110M-M2-CF                 | [aedb84820e](https://linux-hardware.org/?probe=aedb84820e) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASUSTek       | F2A85-V PRO                 | [0127d7b1cd](https://linux-hardware.org/?probe=0127d7b1cd) | Nov 12, 2022 |
| MSI           | A320M-A PRO                 | [6b77cc7062](https://linux-hardware.org/?probe=6b77cc7062) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [2677116eee](https://linux-hardware.org/?probe=2677116eee) | Nov 12, 2022 |
| ASUSTek       | P5K-VM                      | [8d1ad25443](https://linux-hardware.org/?probe=8d1ad25443) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [7fe6789365](https://linux-hardware.org/?probe=7fe6789365) | Nov 12, 2022 |
| MSI           | Z97-G43                     | [f5946a94b0](https://linux-hardware.org/?probe=f5946a94b0) | Nov 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8d2d850a5](https://linux-hardware.org/?probe=a8d2d850a5) | Nov 12, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [c1103d767e](https://linux-hardware.org/?probe=c1103d767e) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [0d1333128b](https://linux-hardware.org/?probe=0d1333128b) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | [ff49e5ddb5](https://linux-hardware.org/?probe=ff49e5ddb5) | Nov 11, 2022 |
| Sapphire      | IPC-E350M1                  | [58a5544fb4](https://linux-hardware.org/?probe=58a5544fb4) | Nov 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [af490e0878](https://linux-hardware.org/?probe=af490e0878) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | [b152665a17](https://linux-hardware.org/?probe=b152665a17) | Nov 11, 2022 |
| ASUSTek       | H81M-PLUS                   | [12d6552ded](https://linux-hardware.org/?probe=12d6552ded) | Nov 11, 2022 |
| ASRock        | B550M-HDV                   | [277c219cef](https://linux-hardware.org/?probe=277c219cef) | Nov 11, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [a37ca89eae](https://linux-hardware.org/?probe=a37ca89eae) | Nov 11, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| ASUSTek       | PRIME B450M-K               | [ccd759a684](https://linux-hardware.org/?probe=ccd759a684) | Nov 11, 2022 |
| Intel         | DP965LT AAD41694-206        | [72773d35e0](https://linux-hardware.org/?probe=72773d35e0) | Nov 11, 2022 |
| ASRock        | H470M-HVS                   | [b81b19a472](https://linux-hardware.org/?probe=b81b19a472) | Nov 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| MSI           | B150 GAMING M3              | [13f42af580](https://linux-hardware.org/?probe=13f42af580) | Nov 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | [46ee069dd8](https://linux-hardware.org/?probe=46ee069dd8) | Nov 11, 2022 |
| MSI           | B450M GAMING PLUS           | [dd56553c17](https://linux-hardware.org/?probe=dd56553c17) | Nov 11, 2022 |
| Unknown       | NF-CK804                    | [6bda1f2345](https://linux-hardware.org/?probe=6bda1f2345) | Nov 10, 2022 |
| ASRock        | H410M-HDV                   | [985b9b55e2](https://linux-hardware.org/?probe=985b9b55e2) | Nov 10, 2022 |
| Acer          | H11H4-AI V:1.0              | [0873e8bf70](https://linux-hardware.org/?probe=0873e8bf70) | Nov 10, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [45dc316bea](https://linux-hardware.org/?probe=45dc316bea) | Nov 10, 2022 |
| ASUSTek       | P5K/EPU                     | [4bd9a2de61](https://linux-hardware.org/?probe=4bd9a2de61) | Nov 10, 2022 |
| Gigabyte      | H55M-S2H                    | [8af42c3646](https://linux-hardware.org/?probe=8af42c3646) | Nov 10, 2022 |
| ASUSTek       | P5K/EPU                     | [cd3706107a](https://linux-hardware.org/?probe=cd3706107a) | Nov 10, 2022 |
| ASUSTek       | H110M-K                     | [4d6af313f5](https://linux-hardware.org/?probe=4d6af313f5) | Nov 10, 2022 |
| Gigabyte      | H55M-S2H                    | [18d013bbc8](https://linux-hardware.org/?probe=18d013bbc8) | Nov 10, 2022 |
| ASUSTek       | P7H55-M/USB3                | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [b5ce55106f](https://linux-hardware.org/?probe=b5ce55106f) | Nov 10, 2022 |
| Gigabyte      | A320M-H-CF                  | [4cf7d8ea41](https://linux-hardware.org/?probe=4cf7d8ea41) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [a885b61478](https://linux-hardware.org/?probe=a885b61478) | Nov 10, 2022 |
| Intel         | X79                         | [f806dcc4da](https://linux-hardware.org/?probe=f806dcc4da) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [475ad820cd](https://linux-hardware.org/?probe=475ad820cd) | Nov 10, 2022 |
| Pegatron      | 2A73h                       | [dc035c362e](https://linux-hardware.org/?probe=dc035c362e) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | [640d78b1e4](https://linux-hardware.org/?probe=640d78b1e4) | Nov 10, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | [d9d004077a](https://linux-hardware.org/?probe=d9d004077a) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| MSI           | MS-B1711                    | [a80911f521](https://linux-hardware.org/?probe=a80911f521) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | [50b86d41a2](https://linux-hardware.org/?probe=50b86d41a2) | Nov 09, 2022 |
| MSI           | Z370 TOMAHAWK               | [0763a922c8](https://linux-hardware.org/?probe=0763a922c8) | Nov 09, 2022 |
| ASRock        | H97 Pro4                    | [bdd79e7a9e](https://linux-hardware.org/?probe=bdd79e7a9e) | Nov 09, 2022 |
| Gigabyte      | 990XA-UD3                   | [c92f8d8b22](https://linux-hardware.org/?probe=c92f8d8b22) | Nov 09, 2022 |
| HP            | 806A                        | [e8bee1d38a](https://linux-hardware.org/?probe=e8bee1d38a) | Nov 08, 2022 |
| MSI           | X370 GAMING PLUS            | [ae91098674](https://linux-hardware.org/?probe=ae91098674) | Nov 08, 2022 |
| Huanan        | X99-BD4 V1.3                | [e50441190a](https://linux-hardware.org/?probe=e50441190a) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [c8383aa811](https://linux-hardware.org/?probe=c8383aa811) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [7f6cff35d7](https://linux-hardware.org/?probe=7f6cff35d7) | Nov 08, 2022 |
| Gigabyte      | Z77X-D3H                    | [09e3734a06](https://linux-hardware.org/?probe=09e3734a06) | Nov 08, 2022 |
| Gigabyte      | A320M-H-CF                  | [137958160c](https://linux-hardware.org/?probe=137958160c) | Nov 08, 2022 |
| ASUSTek       | P8H67-M LX                  | [277212bfc3](https://linux-hardware.org/?probe=277212bfc3) | Nov 08, 2022 |
| Gigabyte      | EP45-UD3L                   | [2b3eb32895](https://linux-hardware.org/?probe=2b3eb32895) | Nov 07, 2022 |
| Unknown       | Unknown                     | [37226d7d92](https://linux-hardware.org/?probe=37226d7d92) | Nov 07, 2022 |
| MSI           | X370 GAMING PLUS            | [cda3bef0bc](https://linux-hardware.org/?probe=cda3bef0bc) | Nov 07, 2022 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [731ce5b944](https://linux-hardware.org/?probe=731ce5b944) | Nov 07, 2022 |
| ASRock        | D1800M                      | [4935d67430](https://linux-hardware.org/?probe=4935d67430) | Nov 07, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dd30cc2e63](https://linux-hardware.org/?probe=dd30cc2e63) | Nov 07, 2022 |
| ASRock        | N68C-GS FX                  | [c7b8fac7e2](https://linux-hardware.org/?probe=c7b8fac7e2) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [16b37f0b80](https://linux-hardware.org/?probe=16b37f0b80) | Nov 07, 2022 |
| ASUSTek       | F2A55-M LK                  | [0c888d2b1f](https://linux-hardware.org/?probe=0c888d2b1f) | Nov 07, 2022 |
| MSI           | B450M MORTAR MAX            | [eae2553adf](https://linux-hardware.org/?probe=eae2553adf) | Nov 06, 2022 |
| MSI           | H81M-P33                    | [00cb3af126](https://linux-hardware.org/?probe=00cb3af126) | Nov 06, 2022 |
| ASRock        | H370M-ITX/ac                | [fe29240874](https://linux-hardware.org/?probe=fe29240874) | Nov 06, 2022 |
| Acer          | EG31M R01-C2                | [1c541d28e0](https://linux-hardware.org/?probe=1c541d28e0) | Nov 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | [a60e7d1961](https://linux-hardware.org/?probe=a60e7d1961) | Nov 06, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [905a8c9fee](https://linux-hardware.org/?probe=905a8c9fee) | Nov 06, 2022 |
| ASRock        | B550 Extreme4               | [16154018bb](https://linux-hardware.org/?probe=16154018bb) | Nov 06, 2022 |
| MSI           | B150 GAMING M3              | [38a85b01ad](https://linux-hardware.org/?probe=38a85b01ad) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [b6a4d355bc](https://linux-hardware.org/?probe=b6a4d355bc) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | [4d260267d7](https://linux-hardware.org/?probe=4d260267d7) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | [789df18cfb](https://linux-hardware.org/?probe=789df18cfb) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [ba495c1631](https://linux-hardware.org/?probe=ba495c1631) | Nov 06, 2022 |
| Gigabyte      | F2A55M-DS2                  | [4cadf85e6e](https://linux-hardware.org/?probe=4cadf85e6e) | Nov 06, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [4a3eefaf16](https://linux-hardware.org/?probe=4a3eefaf16) | Nov 06, 2022 |
| ASUSTek       | Z97-C                       | [ce7c45a3d9](https://linux-hardware.org/?probe=ce7c45a3d9) | Nov 06, 2022 |
| Biostar       | A78LR-M3S                   | [8e8da94ddb](https://linux-hardware.org/?probe=8e8da94ddb) | Nov 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [5db0a08b25](https://linux-hardware.org/?probe=5db0a08b25) | Nov 06, 2022 |
| ASRock        | B660M PG Riptide            | [2fb2a2e140](https://linux-hardware.org/?probe=2fb2a2e140) | Nov 05, 2022 |
| Gigabyte      | B365M D3H-CF                | [53d09fc292](https://linux-hardware.org/?probe=53d09fc292) | Nov 05, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5d6951212b](https://linux-hardware.org/?probe=5d6951212b) | Nov 05, 2022 |
| ASUSTek       | PRIME H510M-R               | [922e24a1a0](https://linux-hardware.org/?probe=922e24a1a0) | Nov 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | [40ef04163d](https://linux-hardware.org/?probe=40ef04163d) | Nov 05, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d7512f31a3](https://linux-hardware.org/?probe=d7512f31a3) | Nov 05, 2022 |
| Gigabyte      | H61M-S2PV                   | [1c2a17391f](https://linux-hardware.org/?probe=1c2a17391f) | Nov 05, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [a8926fce15](https://linux-hardware.org/?probe=a8926fce15) | Nov 05, 2022 |
| MSI           | P67A-C43                    | [a5e86512d1](https://linux-hardware.org/?probe=a5e86512d1) | Nov 05, 2022 |
| Gigabyte      | H110M-S2HP-CF               | [94004d5828](https://linux-hardware.org/?probe=94004d5828) | Nov 05, 2022 |
| Gigabyte      | B75-D3V                     | [a562aef0c3](https://linux-hardware.org/?probe=a562aef0c3) | Nov 05, 2022 |
| Dell          | 0MN1TX A01                  | [a788e75812](https://linux-hardware.org/?probe=a788e75812) | Nov 05, 2022 |
| ASUSTek       | M4A77TD PRO                 | [b5fa37b726](https://linux-hardware.org/?probe=b5fa37b726) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | [edf9105fc5](https://linux-hardware.org/?probe=edf9105fc5) | Nov 04, 2022 |
| Unknown       | X79-P3                      | [f069ed7bd9](https://linux-hardware.org/?probe=f069ed7bd9) | Nov 04, 2022 |
| Gigabyte      | Z87-HD3                     | [f67d642096](https://linux-hardware.org/?probe=f67d642096) | Nov 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R11           | 1603     | 12.2%   |
| ROSA R10           | 1538     | 11.7%   |
| ROSA R8.1          | 1139     | 8.67%   |
| ROSA R8            | 1050     | 7.99%   |
| ROSA R9            | 928      | 7.06%   |
| ROSA 12.2          | 906      | 6.89%   |
| ROSA R11.1         | 862      | 6.56%   |
| Debian 11          | 652      | 4.96%   |
| Ubuntu 20.04       | 332      | 2.53%   |
| ROSA 12.3          | 294      | 2.24%   |
| OpenMandriva 4.2   | 230      | 1.75%   |
| Ubuntu 18.04       | 203      | 1.54%   |
| OpenMandriva 4.3   | 157      | 1.19%   |
| ROSA 12.1          | 143      | 1.09%   |
| Arch Rolling       | 100      | 0.76%   |
| Ubuntu 22.04       | 99       | 0.75%   |
| ROSA 12            | 93       | 0.71%   |
| KDE neon 20.04     | 87       | 0.66%   |
| Kometa P10         | 81       | 0.62%   |
| Debian 10          | 81       | 0.62%   |
| Xubuntu 20.04      | 72       | 0.55%   |
| Arch               | 68       | 0.52%   |
| RED X3             | 56       | 0.43%   |
| Manjaro            | 55       | 0.42%   |
| Linux Mint 20.3    | 55       | 0.42%   |
| RED X4             | 51       | 0.39%   |
| Linux Mint 18.3    | 51       | 0.39%   |
| Kubuntu 20.04      | 51       | 0.39%   |
| Fedora 36          | 47       | 0.36%   |
| Linux Mint 19.3    | 44       | 0.33%   |
| Linux Mint 19.1    | 43       | 0.33%   |
| Red OS 7.3.1       | 42       | 0.32%   |
| OpenMandriva 23.01 | 41       | 0.31%   |
| ROSA R12           | 38       | 0.29%   |
| OpenMandriva 4.50  | 38       | 0.29%   |
| Linux Mint 20      | 38       | 0.29%   |
| Red OS 7.3         | 37       | 0.28%   |
| Linux Mint 20.2    | 33       | 0.25%   |
| Linux Mint 20.1    | 33       | 0.25%   |
| Fedora 35          | 33       | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 7396     | 63.52%  |
| Debian       | 788      | 6.77%   |
| Ubuntu       | 757      | 6.5%    |
| OpenMandriva | 486      | 4.17%   |
| Linux Mint   | 385      | 3.31%   |
| Manjaro      | 218      | 1.87%   |
| Fedora       | 202      | 1.73%   |
| ALT Linux    | 199      | 1.71%   |
| Arch         | 163      | 1.4%    |
| Xubuntu      | 113      | 0.97%   |
| RED          | 113      | 0.97%   |
| KDE neon     | 107      | 0.92%   |
| Red OS       | 97       | 0.83%   |
| Kubuntu      | 92       | 0.79%   |
| Gentoo       | 57       | 0.49%   |
| Endless      | 53       | 0.46%   |
| Pop!_OS      | 44       | 0.38%   |
| openSUSE     | 36       | 0.31%   |
| Ubuntu MATE  | 27       | 0.23%   |
| Clear Linux  | 24       | 0.21%   |
| Elementary   | 23       | 0.2%    |
| RELS         | 22       | 0.19%   |
| CentOS       | 21       | 0.18%   |
| Zorin        | 18       | 0.15%   |
| Ubuntu Unity | 18       | 0.15%   |
| Lubuntu      | 17       | 0.15%   |
| LMDE         | 16       | 0.14%   |
| ArcoLinux    | 16       | 0.14%   |
| Kali         | 8        | 0.07%   |
| Astra Linux  | 7        | 0.06%   |
| Solus        | 6        | 0.05%   |
| MX           | 6        | 0.05%   |
| EndeavourOS  | 6        | 0.05%   |
| Artix        | 6        | 0.05%   |
| Void Linux   | 4        | 0.03%   |
| Virtuozzo    | 4        | 0.03%   |
| Slackware    | 4        | 0.03%   |
| Rocky Linux  | 4        | 0.03%   |
| Parrot       | 4        | 0.03%   |
| Devuan       | 4        | 0.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 773      | 5.46%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 700      | 4.94%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 697      | 4.92%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 667      | 4.71%   |
| 5.10.0-7-amd64                      | 472      | 3.33%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 401      | 2.83%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 332      | 2.35%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 318      | 2.25%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 255      | 1.8%    |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 250      | 1.77%   |
| 5.10.14-desktop-1omv4002            | 219      | 1.55%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 205      | 1.45%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 197      | 1.39%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 196      | 1.38%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 195      | 1.38%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 189      | 1.34%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 183      | 1.29%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 178      | 1.26%   |
| 4.15.0-desktop-45.1rosa-i586        | 168      | 1.19%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 167      | 1.18%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 165      | 1.17%   |
| 5.4.32-generic-2rosa-x86_64         | 156      | 1.1%    |
| 5.16.7-desktop-1omv4003             | 153      | 1.08%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 151      | 1.07%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 148      | 1.05%   |
| 5.4.83-generic-2rosa-x86_64         | 147      | 1.04%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 137      | 0.97%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 112      | 0.79%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 112      | 0.79%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 94       | 0.66%   |
| 5.10.0-2-amd64                      | 92       | 0.65%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 92       | 0.65%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 91       | 0.64%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 91       | 0.64%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 83       | 0.59%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 80       | 0.57%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 65       | 0.46%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 64       | 0.45%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 64       | 0.45%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 64       | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 2000     | 14.6%   |
| 4.9.60   | 884      | 6.45%   |
| 4.9.20   | 846      | 6.18%   |
| 5.10.74  | 786      | 5.74%   |
| 5.10.0   | 652      | 4.76%   |
| 4.1.34   | 546      | 3.99%   |
| 5.4.0    | 542      | 3.96%   |
| 4.1.38   | 434      | 3.17%   |
| 4.1.25   | 430      | 3.14%   |
| 4.9.9    | 402      | 2.93%   |
| 4.9.124  | 395      | 2.88%   |
| 4.9.155  | 261      | 1.91%   |
| 4.9.76   | 251      | 1.83%   |
| 4.9.41   | 250      | 1.83%   |
| 5.15.0   | 219      | 1.6%    |
| 5.10.14  | 219      | 1.6%    |
| 5.4.32   | 208      | 1.52%   |
| 5.4.83   | 186      | 1.36%   |
| 5.10.118 | 172      | 1.26%   |
| 5.16.7   | 154      | 1.12%   |
| 5.8.0    | 139      | 1.01%   |
| 5.3.0    | 137      | 1%      |
| 5.11.0   | 129      | 0.94%   |
| 4.9.95   | 120      | 0.88%   |
| 5.0.0    | 110      | 0.8%    |
| 4.9.111  | 104      | 0.76%   |
| 5.15.75  | 103      | 0.75%   |
| 5.10.71  | 92       | 0.67%   |
| 5.13.0   | 89       | 0.65%   |
| 4.9.87   | 82       | 0.6%    |
| 4.18.0   | 82       | 0.6%    |
| 5.15.79  | 81       | 0.59%   |
| 4.19.0   | 72       | 0.53%   |
| 5.10.109 | 51       | 0.37%   |
| 4.9.14   | 48       | 0.35%   |
| 6.1.1    | 45       | 0.33%   |
| 5.17.11  | 40       | 0.29%   |
| 5.4.40   | 39       | 0.28%   |
| 4.13.0   | 38       | 0.28%   |
| 4.9.34   | 37       | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 3195     | 24.98%  |
| 5.10    | 2116     | 16.54%  |
| 4.15    | 2012     | 15.73%  |
| 4.1     | 1369     | 10.7%   |
| 5.4     | 1108     | 8.66%   |
| 5.15    | 657      | 5.14%   |
| 5.16    | 214      | 1.67%   |
| 5.11    | 207      | 1.62%   |
| 5.8     | 196      | 1.53%   |
| 5.3     | 186      | 1.45%   |
| 5.0     | 129      | 1.01%   |
| 5.13    | 125      | 0.98%   |
| 5.18    | 120      | 0.94%   |
| 4.19    | 107      | 0.84%   |
| 4.18    | 92       | 0.72%   |
| 6.0     | 89       | 0.7%    |
| 5.17    | 75       | 0.59%   |
| 6.1     | 70       | 0.55%   |
| 5.19    | 68       | 0.53%   |
| 5.6     | 60       | 0.47%   |
| 5.9     | 57       | 0.45%   |
| 5.14    | 56       | 0.44%   |
| 4.4     | 52       | 0.41%   |
| 4.13    | 51       | 0.4%    |
| 5.12    | 47       | 0.37%   |
| 5.7     | 38       | 0.3%    |
| 3.10    | 38       | 0.3%    |
| 4.8     | 36       | 0.28%   |
| 5.5     | 26       | 0.2%    |
| 4.14    | 26       | 0.2%    |
| 4.16    | 25       | 0.2%    |
| 3.14    | 23       | 0.18%   |
| 5.2     | 21       | 0.16%   |
| 4.10    | 20       | 0.16%   |
| 4.20    | 13       | 0.1%    |
| 4.17    | 13       | 0.1%    |
| 4.12    | 13       | 0.1%    |
| 4.11    | 11       | 0.09%   |
| 4.7     | 8        | 0.06%   |
| 5.1     | 4        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 9822     | 85.84%  |
| i686        | 1613     | 14.1%   |
| e2k         | 4        | 0.03%   |
| ppc64       | 1        | 0.01%   |
| loongarch64 | 1        | 0.01%   |
| armv6l      | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| KDE4              | 4711     | 38.88%  |
| KDE5              | 3198     | 26.39%  |
| GNOME             | 1527     | 12.6%   |
| Unknown           | 1065     | 8.79%   |
| XFCE              | 359      | 2.96%   |
| MATE              | 318      | 2.62%   |
| LXQt              | 302      | 2.49%   |
| Cinnamon          | 185      | 1.53%   |
| X-Cinnamon        | 174      | 1.44%   |
| KDE               | 137      | 1.13%   |
| LXDE              | 23       | 0.19%   |
| Pantheon          | 22       | 0.18%   |
| Unity             | 18       | 0.15%   |
| Budgie            | 11       | 0.09%   |
| i3                | 10       | 0.08%   |
| GNOME Flashback   | 8        | 0.07%   |
| Deepin            | 8        | 0.07%   |
| GNOME Classic     | 7        | 0.06%   |
| Openbox           | 6        | 0.05%   |
| awesome           | 5        | 0.04%   |
| fly               | 4        | 0.03%   |
| bspwm             | 3        | 0.02%   |
| xmonad            | 2        | 0.02%   |
| sway              | 2        | 0.02%   |
| lightdm-xsession  | 2        | 0.02%   |
| icewm             | 2        | 0.02%   |
| Hyprland          | 2        | 0.02%   |
| X-Generic         | 1        | 0.01%   |
| Trinity           | 1        | 0.01%   |
| steamos           | 1        | 0.01%   |
| i3-with-shmlog    | 1        | 0.01%   |
| DWM               | 1        | 0.01%   |
| /etc/X11/Xsession | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 9384     | 80.64%  |
| Wayland | 1390     | 11.94%  |
| Unknown | 749      | 6.44%   |
| Tty     | 114      | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 4753     | 39.39%  |
| SDDM    | 3274     | 27.13%  |
| Unknown | 1894     | 15.7%   |
| GDM     | 1218     | 10.09%  |
| LightDM | 358      | 2.97%   |
| TDM     | 320      | 2.65%   |
| GDM3    | 194      | 1.61%   |
| MDM     | 22       | 0.18%   |
| XDM     | 10       | 0.08%   |
| SLiM    | 8        | 0.07%   |
| LXDM    | 6        | 0.05%   |
| FLY-DM  | 5        | 0.04%   |
| Ly      | 2        | 0.02%   |
| WDM     | 1        | 0.01%   |
| LDM     | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 6233     | 52.84%  |
| ru_RU       | 4697     | 39.82%  |
| en_US       | 760      | 6.44%   |
| C           | 40       | 0.34%   |
| en_GB       | 17       | 0.14%   |
| ru_RU.UTF_8 | 9        | 0.08%   |
| C.UTF8      | 7        | 0.06%   |
| ru_UA       | 6        | 0.05%   |
| ru_RU.UTF8  | 6        | 0.05%   |
| POSIX       | 4        | 0.03%   |
| cv_RU       | 3        | 0.03%   |
| tt_RU       | 2        | 0.02%   |
| en_DK       | 2        | 0.02%   |
| ba_RU       | 2        | 0.02%   |
| zh_CN       | 1        | 0.01%   |
| uk_UA       | 1        | 0.01%   |
| myv_RU      | 1        | 0.01%   |
| fr_FR       | 1        | 0.01%   |
| en_RU       | 1        | 0.01%   |
| en_CA       | 1        | 0.01%   |
| en_AG       | 1        | 0.01%   |
| de_DE       | 1        | 0.01%   |
| ce_RU       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 8460     | 72.98%  |
| EFI  | 3132     | 27.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 6452     | 53.7%   |
| Unknown  | 3833     | 31.9%   |
| Overlay  | 1044     | 8.69%   |
| Btrfs    | 456      | 3.8%    |
| Xfs      | 91       | 0.76%   |
| Ext3     | 42       | 0.35%   |
| Zfs      | 33       | 0.27%   |
| F2fs     | 21       | 0.17%   |
| Ext2     | 19       | 0.16%   |
| Aufs     | 5        | 0.04%   |
| XXXXXXX  | 3        | 0.02%   |
| SAMSUNG  | 3        | 0.02%   |
| Reiserfs | 3        | 0.02%   |
| Jfs      | 3        | 0.02%   |
| Tmpfs    | 2        | 0.02%   |
| Rootfs   | 2        | 0.02%   |
| XXXXX    | 1        | 0.01%   |
| Exfat    | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 5705     | 47.32%  |
| GPT     | 3406     | 28.25%  |
| Unknown | 2944     | 24.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9848     | 83.86%  |
| Yes       | 1896     | 16.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7559     | 63.62%  |
| Yes       | 4323     | 36.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4075     | 36.05%  |
| Gigabyte Technology | 2782     | 24.61%  |
| ASRock              | 1240     | 10.97%  |
| MSI                 | 1187     | 10.5%   |
| Intel               | 341      | 3.02%   |
| ECS                 | 256      | 2.26%   |
| Hewlett-Packard     | 173      | 1.53%   |
| Unknown             | 168      | 1.49%   |
| Acer                | 143      | 1.27%   |
| Biostar             | 123      | 1.09%   |
| Foxconn             | 116      | 1.03%   |
| Lenovo              | 97       | 0.86%   |
| Dell                | 93       | 0.82%   |
| Pegatron            | 82       | 0.73%   |
| Huanan              | 72       | 0.64%   |
| EPoX Computer       | 21       | 0.19%   |
| DEPO Computers      | 21       | 0.19%   |
| WinFast             | 20       | 0.18%   |
| Supermicro          | 18       | 0.16%   |
| Fujitsu             | 18       | 0.16%   |
| Fujitsu Siemens     | 12       | 0.11%   |
| AZW                 | 12       | 0.11%   |
| Aquarius            | 11       | 0.1%    |
| Nvidia              | 10       | 0.09%   |
| AMD                 | 10       | 0.09%   |
| MACHINIST           | 9        | 0.08%   |
| Kraftway            | 8        | 0.07%   |
| JW Technology       | 8        | 0.07%   |
| SiS Technology      | 7        | 0.06%   |
| Shuttle             | 7        | 0.06%   |
| OEM                 | 7        | 0.06%   |
| Kllisre             | 6        | 0.05%   |
| ABIT                | 6        | 0.05%   |
| Packard Bell        | 5        | 0.04%   |
| Lite-On             | 5        | 0.04%   |
| iRU                 | 5        | 0.04%   |
| IBM                 | 5        | 0.04%   |
| eMachines           | 5        | 0.04%   |
| Colorful Technology | 5        | 0.04%   |
| AMI                 | 5        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 370      | 3.27%   |
| Unknown                    | 184      | 1.63%   |
| Gigabyte 970A-DS3P         | 70       | 0.62%   |
| MSI MS-7996                | 69       | 0.61%   |
| MSI MS-7817                | 67       | 0.59%   |
| ASUS M5A78L-M LX3          | 67       | 0.59%   |
| ASUS P8H61-M LX3 R2.0      | 58       | 0.51%   |
| ASUS H110M-R               | 57       | 0.5%    |
| ASUS S20 K29               | 55       | 0.49%   |
| Intel SKYBAY               | 47       | 0.42%   |
| ASUS M5A97 R2.0            | 46       | 0.41%   |
| ASRock G31M-S              | 46       | 0.41%   |
| Gigabyte H61M-S1           | 45       | 0.4%    |
| ASUS P5K                   | 45       | 0.4%    |
| MSI MS-7529                | 43       | 0.38%   |
| Gigabyte G31M-ES2L         | 43       | 0.38%   |
| ASUS P5G41T-M LX2/GB       | 41       | 0.36%   |
| ASUS P5KPL-AM              | 40       | 0.35%   |
| ASRock N68C-S UCC          | 40       | 0.35%   |
| Gigabyte H61M-S2PV         | 39       | 0.35%   |
| ASUS M5A78L-M/USB3         | 39       | 0.35%   |
| MSI MS-7592                | 38       | 0.34%   |
| ASUS M5A97 LE R2.0         | 37       | 0.33%   |
| ASUS PRIME A320M-K         | 36       | 0.32%   |
| ASUS P5B                   | 34       | 0.3%    |
| Gigabyte Z77-DS3H          | 33       | 0.29%   |
| ASUS A68HM-K               | 33       | 0.29%   |
| ECS G31T-M9                | 32       | 0.28%   |
| ASUS P5KPL-AM IN/ROEM/SI   | 32       | 0.28%   |
| ASUS P5Q SE2               | 31       | 0.27%   |
| ASRock G41M-VS3            | 31       | 0.27%   |
| MSI MS-7721                | 30       | 0.27%   |
| Gigabyte GA-78LMT-S2       | 30       | 0.27%   |
| ASUS P8Z77-V LX            | 30       | 0.27%   |
| MSI MS-7693                | 29       | 0.26%   |
| Gigabyte GA-78LMT-S2P      | 29       | 0.26%   |
| ASUS PRIME H310M-R R2.0    | 28       | 0.25%   |
| ASUS H110M-K               | 28       | 0.25%   |
| MSI MS-7309                | 27       | 0.24%   |
| ASUS SABERTOOTH 990FX R2.0 | 27       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 373      | 3.3%    |
| ASUS All           | 370      | 3.27%   |
| ASUS P8H61-M       | 185      | 1.64%   |
| Unknown            | 184      | 1.63%   |
| ASUS M5A78L-M      | 176      | 1.56%   |
| ASUS P5KPL-AM      | 124      | 1.1%    |
| ASUS M5A97         | 112      | 0.99%   |
| ASUS P5G41T-M      | 104      | 0.92%   |
| ASUS P5K           | 95       | 0.84%   |
| Acer Aspire        | 89       | 0.79%   |
| ASUS P8Z77-V       | 85       | 0.75%   |
| ASUS P5Q           | 72       | 0.64%   |
| Gigabyte 970A-DS3P | 71       | 0.63%   |
| ASUS ROG           | 70       | 0.62%   |
| MSI MS-7996        | 69       | 0.61%   |
| ASUS TUF           | 69       | 0.61%   |
| MSI MS-7817        | 67       | 0.59%   |
| HP Compaq          | 65       | 0.58%   |
| Gigabyte B450M     | 65       | 0.58%   |
| Dell OptiPlex      | 64       | 0.57%   |
| ASUS H110M-R       | 57       | 0.5%    |
| Gigabyte B450      | 55       | 0.49%   |
| ASUS S20           | 55       | 0.49%   |
| ASUS P8H77-V       | 52       | 0.46%   |
| ASUS P8H67-M       | 52       | 0.46%   |
| Intel SKYBAY       | 47       | 0.42%   |
| ASUS SABERTOOTH    | 47       | 0.42%   |
| ASUS P8H61-MX      | 47       | 0.42%   |
| ASRock G31M-S      | 46       | 0.41%   |
| Lenovo ThinkCentre | 45       | 0.4%    |
| Gigabyte H61M-S1   | 45       | 0.4%    |
| MSI MS-7529        | 43       | 0.38%   |
| Gigabyte G31M-ES2L | 43       | 0.38%   |
| ASUS P7H55-M       | 43       | 0.38%   |
| Gigabyte A320M-S2H | 42       | 0.37%   |
| Gigabyte H310M     | 41       | 0.36%   |
| ASUS P8B75-M       | 41       | 0.36%   |
| ASRock N68C-S      | 41       | 0.36%   |
| Acer Veriton       | 41       | 0.36%   |
| ASUS P5B           | 40       | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 1582     | 14%     |
| 2009    | 998      | 8.83%   |
| 2011    | 989      | 8.75%   |
| 2010    | 902      | 7.98%   |
| 2013    | 835      | 7.39%   |
| 2018    | 801      | 7.09%   |
| 2008    | 757      | 6.7%    |
| 2007    | 716      | 6.33%   |
| 2016    | 493      | 4.36%   |
| 2006    | 462      | 4.09%   |
| 2014    | 447      | 3.95%   |
| 2017    | 426      | 3.77%   |
| 2019    | 413      | 3.65%   |
| 2020    | 385      | 3.41%   |
| 2015    | 377      | 3.34%   |
| 2021    | 312      | 2.76%   |
| 2005    | 196      | 1.73%   |
| 2022    | 72       | 0.64%   |
| 2004    | 69       | 0.61%   |
| 2003    | 41       | 0.36%   |
| Unknown | 19       | 0.17%   |
| 2002    | 7        | 0.06%   |
| 2001    | 4        | 0.04%   |
| 2000    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 11304    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11241    | 99.41%  |
| Enabled  | 67       | 0.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11302    | 99.98%  |
| Yes  | 2        | 0.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 3009     | 25.53%  |
| 8.01-16.0       | 2621     | 22.24%  |
| 4.01-8.0        | 1854     | 15.73%  |
| 16.01-24.0      | 1648     | 13.99%  |
| 1.01-2.0        | 1007     | 8.55%   |
| 2.01-3.0        | 639      | 5.42%   |
| 32.01-64.0      | 567      | 4.81%   |
| 0.51-1.0        | 156      | 1.32%   |
| 64.01-256.0     | 139      | 1.18%   |
| 24.01-32.0      | 125      | 1.06%   |
| 0.01-0.5        | 13       | 0.11%   |
| More than 256.0 | 3        | 0.03%   |
| Unknown         | 3        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 4901     | 38.26%  |
| 0.51-1.0    | 4502     | 35.15%  |
| 2.01-3.0    | 1509     | 11.78%  |
| 4.01-8.0    | 713      | 5.57%   |
| 3.01-4.0    | 609      | 4.75%   |
| 0.01-0.5    | 282      | 2.2%    |
| 8.01-16.0   | 204      | 1.59%   |
| 16.01-24.0  | 50       | 0.39%   |
| 32.01-64.0  | 14       | 0.11%   |
| 24.01-32.0  | 12       | 0.09%   |
| Unknown     | 11       | 0.09%   |
| 64.01-256.0 | 2        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 5956     | 49.75%  |
| 2       | 3240     | 27.06%  |
| 3       | 1583     | 13.22%  |
| 4       | 676      | 5.65%   |
| 5       | 278      | 2.32%   |
| 6       | 91       | 0.76%   |
| 0       | 79       | 0.66%   |
| 7       | 35       | 0.29%   |
| 8       | 17       | 0.14%   |
| 9       | 8        | 0.07%   |
| 10      | 2        | 0.02%   |
| Unknown | 2        | 0.02%   |
| 25      | 1        | 0.01%   |
| 18      | 1        | 0.01%   |
| 17      | 1        | 0.01%   |
| 13      | 1        | 0.01%   |
| 12      | 1        | 0.01%   |
| 11      | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5885     | 50.83%  |
| Yes       | 5693     | 49.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11199    | 99.06%  |
| No        | 106      | 0.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8823     | 76.8%   |
| Yes       | 2666     | 23.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9962     | 86.97%  |
| Yes       | 1492     | 13.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 11304    | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 1917     | 15.92%  |
| St Petersburg    | 777      | 6.45%   |
| Voronezh         | 744      | 6.18%   |
| Pecherskoye      | 421      | 3.5%    |
| Novosibirsk      | 373      | 3.1%    |
| Yekaterinburg    | 305      | 2.53%   |
| Krasnodar        | 262      | 2.18%   |
| Samara           | 240      | 1.99%   |
| Nizhniy Novgorod | 233      | 1.93%   |
| Rostov-on-Don    | 217      | 1.8%    |
| Perm             | 194      | 1.61%   |
| Chelyabinsk      | 194      | 1.61%   |
| Krasnoyarsk      | 152      | 1.26%   |
| Saratov          | 136      | 1.13%   |
| Omsk             | 133      | 1.1%    |
| Volgograd        | 114      | 0.95%   |
| Kazan’         | 112      | 0.93%   |
| Ufa              | 111      | 0.92%   |
| Vladivostok      | 103      | 0.86%   |
| Stavropol        | 101      | 0.84%   |
| Barnaul          | 101      | 0.84%   |
| Tyumen           | 97       | 0.81%   |
| Khabarovsk       | 94       | 0.78%   |
| Irkutsk          | 92       | 0.76%   |
| Ulyanovsk        | 79       | 0.66%   |
| Orenburg         | 77       | 0.64%   |
| Tomsk            | 74       | 0.61%   |
| Bryansk          | 72       | 0.6%    |
| Belgorod         | 71       | 0.59%   |
| Kemerovo         | 70       | 0.58%   |
| Yaroslavl        | 68       | 0.56%   |
| Novokuznetsk     | 68       | 0.56%   |
| Tolyatti         | 67       | 0.56%   |
| Tula             | 66       | 0.55%   |
| Cheboksary       | 66       | 0.55%   |
| Lipetsk          | 61       | 0.51%   |
| Kaliningrad      | 61       | 0.51%   |
| Izhevsk          | 61       | 0.51%   |
| Astrakhan        | 59       | 0.49%   |
| Ryazan           | 58       | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4641     | 7533   | 25.02%  |
| WDC                 | 4537     | 7753   | 24.46%  |
| Samsung Electronics | 1641     | 2479   | 8.85%   |
| Toshiba             | 1262     | 1873   | 6.8%    |
| Hitachi             | 1016     | 1416   | 5.48%   |
| Kingston            | 958      | 1310   | 5.16%   |
| A-DATA Technology   | 312      | 433    | 1.68%   |
| China               | 299      | 421    | 1.61%   |
| SPCC                | 289      | 366    | 1.56%   |
| Crucial             | 277      | 370    | 1.49%   |
| Maxtor              | 273      | 346    | 1.47%   |
| OCZ                 | 224      | 294    | 1.21%   |
| Intel               | 207      | 355    | 1.12%   |
| SanDisk             | 205      | 298    | 1.11%   |
| Plextor             | 186      | 287    | 1%      |
| HGST                | 178      | 273    | 0.96%   |
| Apacer              | 162      | 224    | 0.87%   |
| Smartbuy            | 114      | 153    | 0.61%   |
| Patriot             | 105      | 138    | 0.57%   |
| AMD                 | 103      | 134    | 0.56%   |
| HUAWEI              | 88       | 103    | 0.47%   |
| GOODRAM             | 80       | 113    | 0.43%   |
| Corsair             | 80       | 118    | 0.43%   |
| Silicon Motion      | 78       | 96     | 0.42%   |
| Transcend           | 75       | 95     | 0.4%    |
| KingSpec            | 68       | 86     | 0.37%   |
| Netac               | 65       | 139    | 0.35%   |
| Unknown             | 61       | 97     | 0.33%   |
| Gigabyte Technology | 54       | 64     | 0.29%   |
| Phison              | 52       | 59     | 0.28%   |
| KingDian            | 44       | 70     | 0.24%   |
| XPG                 | 43       | 53     | 0.23%   |
| Fujitsu             | 37       | 43     | 0.2%    |
| Kingmax             | 35       | 61     | 0.19%   |
| JMicron Technology  | 32       | 33     | 0.17%   |
| Foxline             | 30       | 35     | 0.16%   |
| XrayDisk            | 26       | 34     | 0.14%   |
| AXIOMTEK            | 26       | 28     | 0.14%   |
| Unknown             | 24       | 25     | 0.13%   |
| ZTE                 | 22       | 26     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 373      | 1.75%   |
| Toshiba DT01ACA050 500GB         | 269      | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB   | 245      | 1.15%   |
| Seagate ST3500418AS 500GB        | 242      | 1.13%   |
| Toshiba HDWD110 1TB              | 231      | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB         | 214      | 1%      |
| Seagate ST1000DM003-1CH162 1TB   | 194      | 0.91%   |
| Toshiba DT01ACA100 1TB           | 192      | 0.9%    |
| Kingston SA400S37120G 120GB SSD  | 151      | 0.71%   |
| Kingston SV300S37A120G 120GB SSD | 144      | 0.67%   |
| Kingston SA400S37240G 240GB SSD  | 143      | 0.67%   |
| Samsung SSD 860 EVO 250GB        | 140      | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB      | 137      | 0.64%   |
| Seagate ST3250410AS 250GB        | 130      | 0.61%   |
| Seagate ST380011A 80GB           | 128      | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 123      | 0.58%   |
| Seagate ST380815AS 80GB          | 122      | 0.57%   |
| Seagate ST31000524AS 1TB         | 120      | 0.56%   |
| Seagate ST3160815AS 160GB        | 116      | 0.54%   |
| Hitachi HDS721050CLA362 500GB    | 116      | 0.54%   |
| Seagate ST31000528AS 1TB         | 113      | 0.53%   |
| Seagate ST3250310AS 250GB        | 112      | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB   | 111      | 0.52%   |
| Seagate ST1000DM003-9YN162 1TB   | 102      | 0.48%   |
| Toshiba HDWD105 500GB            | 97       | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 96       | 0.45%   |
| Seagate ST3250318AS 249GB        | 89       | 0.42%   |
| Seagate ST250DM000-1BD141 250GB  | 88       | 0.41%   |
| Crucial CT480BX500SSD1 480GB     | 86       | 0.4%    |
| Seagate ST3500413AS 500GB        | 85       | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 83       | 0.39%   |
| SPCC Solid State Disk 120GB      | 82       | 0.38%   |
| Seagate ST3320613AS 320GB        | 80       | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB         | 79       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB   | 78       | 0.37%   |
| Seagate ST3320620AS 320GB        | 75       | 0.35%   |
| WDC WD5000AADS-00S9B0 500GB      | 73       | 0.34%   |
| Samsung SSD 860 EVO 500GB        | 72       | 0.34%   |
| Hitachi HDS721616PLA380 160GB    | 69       | 0.32%   |
| Hitachi HDS721010CLA332 1TB      | 68       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4623     | 7490   | 37.24%  |
| WDC                 | 4253     | 7124   | 34.26%  |
| Toshiba             | 1207     | 1762   | 9.72%   |
| Hitachi             | 1016     | 1416   | 8.18%   |
| Samsung Electronics | 744      | 1070   | 5.99%   |
| Maxtor              | 272      | 345    | 2.19%   |
| HGST                | 178      | 273    | 1.43%   |
| Fujitsu             | 36       | 42     | 0.29%   |
| Unknown             | 20       | 28     | 0.16%   |
| IBM/Hitachi         | 12       | 15     | 0.1%    |
| Hewlett-Packard     | 8        | 11     | 0.06%   |
| IBM                 | 4        | 4      | 0.03%   |
| USB3.0              | 3        | 3      | 0.02%   |
| Quantum             | 3        | 3      | 0.02%   |
| WD MediaMax         | 2        | 2      | 0.02%   |
| Synology            | 2        | 3      | 0.02%   |
| PHD 3.0             | 2        | 2      | 0.02%   |
| ExcelStor           | 2        | 2      | 0.02%   |
| CLOVER              | 2        | 2      | 0.02%   |
| ASMT106x            | 2        | 3      | 0.02%   |
| ASMT                | 2        | 10     | 0.02%   |
| Apple               | 2        | 2      | 0.02%   |
| Unknown             | 2        | 2      | 0.02%   |
| USB 3.0             | 1        | 1      | 0.01%   |
| USB                 | 1        | 1      | 0.01%   |
| Silicon             | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| Pioneer             | 1        | 1      | 0.01%   |
| MR2020              | 1        | 1      | 0.01%   |
| MARVELL             | 1        | 1      | 0.01%   |
| LIO-ORG             | 1        | 1      | 0.01%   |
| KESU                | 1        | 1      | 0.01%   |
| JMicron Technology  | 1        | 1      | 0.01%   |
| IET                 | 1        | 2      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |
| FreeBSD             | 1        | 1      | 0.01%   |
| External            | 1        | 1      | 0.01%   |
| ASMedia             | 1        | 2      | 0.01%   |
| AFAYA               | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 865      | 1182   | 16.84%  |
| Samsung Electronics | 617      | 893    | 12.01%  |
| WDC                 | 433      | 576    | 8.43%   |
| China               | 297      | 419    | 5.78%   |
| SPCC                | 273      | 346    | 5.31%   |
| Crucial             | 269      | 357    | 5.24%   |
| A-DATA Technology   | 258      | 339    | 5.02%   |
| OCZ                 | 223      | 293    | 4.34%   |
| SanDisk             | 172      | 254    | 3.35%   |
| Plextor             | 171      | 251    | 3.33%   |
| Intel               | 151      | 265    | 2.94%   |
| Apacer              | 144      | 201    | 2.8%    |
| Smartbuy            | 107      | 144    | 2.08%   |
| Patriot             | 100      | 132    | 1.95%   |
| AMD                 | 92       | 116    | 1.79%   |
| Toshiba             | 77       | 107    | 1.5%    |
| GOODRAM             | 75       | 108    | 1.46%   |
| Corsair             | 75       | 109    | 1.46%   |
| Transcend           | 68       | 85     | 1.32%   |
| KingSpec            | 67       | 85     | 1.3%    |
| Netac               | 55       | 126    | 1.07%   |
| KingDian            | 44       | 70     | 0.86%   |
| Gigabyte Technology | 40       | 44     | 0.78%   |
| Kingmax             | 35       | 61     | 0.68%   |
| Foxline             | 29       | 34     | 0.56%   |
| AXIOMTEK            | 26       | 28     | 0.51%   |
| JMicron Technology  | 21       | 21     | 0.41%   |
| XrayDisk            | 20       | 27     | 0.39%   |
| Qumo                | 17       | 22     | 0.33%   |
| Unknown             | 16       | 17     | 0.31%   |
| Seagate             | 13       | 23     | 0.25%   |
| Londisk             | 12       | 13     | 0.23%   |
| Team                | 11       | 12     | 0.21%   |
| Zheino              | 10       | 12     | 0.19%   |
| Palit               | 10       | 14     | 0.19%   |
| OCZ-VERTEX3         | 10       | 15     | 0.19%   |
| Micron Technology   | 10       | 14     | 0.19%   |
| KingFast            | 10       | 14     | 0.19%   |
| Hewlett-Packard     | 10       | 16     | 0.19%   |
| Unknown             | 9        | 13     | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 9611     | 19632  | 63.39%  |
| SSD     | 4323     | 7122   | 28.51%  |
| NVMe    | 992      | 1475   | 6.54%   |
| Unknown | 222      | 255    | 1.46%   |
| MMC     | 14       | 20     | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 10954    | 26524  | 88.81%  |
| NVMe | 987      | 1467   | 8%      |
| SAS  | 379      | 493    | 3.07%   |
| MMC  | 14       | 20     | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 9356     | 17796  | 63.87%  |
| 0.51-1.0        | 3807     | 6458   | 25.99%  |
| 1.01-2.0        | 985      | 1617   | 6.72%   |
| 2.01-3.0        | 226      | 388    | 1.54%   |
| 3.01-4.0        | 162      | 265    | 1.11%   |
| 4.01-10.0       | 92       | 198    | 0.63%   |
| 10.01-20.0      | 17       | 29     | 0.12%   |
| More than 100.0 | 1        | 1      | 0.01%   |
| 20.01-50.0      | 1        | 1      | 0.01%   |
| 0               | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 3207     | 25.24%  |
| 251-500        | 2196     | 17.29%  |
| 501-1000       | 1593     | 12.54%  |
| 1-20           | 1334     | 10.5%   |
| 51-100         | 1287     | 10.13%  |
| 1001-2000      | 974      | 7.67%   |
| 21-50          | 748      | 5.89%   |
| Unknown        | 691      | 5.44%   |
| 2001-3000      | 343      | 2.7%    |
| More than 3000 | 331      | 2.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 6743     | 52.87%  |
| 21-50          | 1282     | 10.05%  |
| 101-250        | 1019     | 7.99%   |
| 251-500        | 842      | 6.6%    |
| 51-100         | 842      | 6.6%    |
| Unknown        | 691      | 5.42%   |
| 501-1000       | 680      | 5.33%   |
| 1001-2000      | 397      | 3.11%   |
| More than 3000 | 138      | 1.08%   |
| 2001-3000      | 118      | 0.93%   |
| 0              | 1        | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 140      | 177    | 2.6%    |
| Seagate ST3500418AS 500GB         | 106      | 135    | 1.97%   |
| Seagate ST3250410AS 250GB         | 86       | 109    | 1.6%    |
| WDC WD5000AAKX-001CA0 500GB       | 67       | 85     | 1.24%   |
| Seagate ST3250310AS 250GB         | 65       | 106    | 1.21%   |
| Seagate ST3320613AS 320GB         | 62       | 80     | 1.15%   |
| Seagate ST31000528AS 1TB          | 54       | 61     | 1%      |
| Seagate ST1000DM003-9YN162 1TB    | 53       | 63     | 0.98%   |
| Seagate ST1000DM003-1CH162 1TB    | 50       | 78     | 0.93%   |
| Hitachi HDS721050CLA362 500GB     | 46       | 53     | 0.85%   |
| WDC WD5000AADS-00S9B0 500GB       | 45       | 52     | 0.84%   |
| Seagate ST380011A 80GB            | 45       | 48     | 0.84%   |
| Seagate ST3160815AS 160GB         | 42       | 53     | 0.78%   |
| Seagate ST250DM000-1BD141 250GB   | 42       | 56     | 0.78%   |
| Seagate ST31000524AS 1TB          | 41       | 54     | 0.76%   |
| Seagate ST3250318AS 249GB         | 39       | 46     | 0.72%   |
| Hitachi HDS721010CLA332 1TB       | 38       | 45     | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB       | 37       | 42     | 0.69%   |
| WDC WD10EARS-00Y5B1 1TB           | 36       | 60     | 0.67%   |
| Hitachi HDS721616PLA380 160GB     | 36       | 50     | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 35       | 43     | 0.65%   |
| Seagate ST380815AS 80GB           | 34       | 46     | 0.63%   |
| Seagate ST3160811AS 160GB         | 34       | 49     | 0.63%   |
| Samsung Electronics HD160JJ 160GB | 33       | 53     | 0.61%   |
| Samsung Electronics HD080HJ 80GB  | 32       | 42     | 0.59%   |
| Kingston SV300S37A120G 120GB SSD  | 32       | 33     | 0.59%   |
| Maxtor STM3250310AS 250GB         | 30       | 39     | 0.56%   |
| Seagate ST3500413AS 500GB         | 29       | 31     | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 28       | 37     | 0.52%   |
| Seagate ST31500341AS 1TB          | 28       | 36     | 0.52%   |
| Hitachi HDP725050GLA360 500GB     | 27       | 39     | 0.5%    |
| WDC WD5000AAKS-00V1A0 500GB       | 26       | 30     | 0.48%   |
| Seagate ST3320620AS 320GB         | 26       | 34     | 0.48%   |
| Samsung Electronics HD161HJ 160GB | 25       | 31     | 0.46%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 22       | 27     | 0.41%   |
| Toshiba DT01ACA050 500GB          | 22       | 33     | 0.41%   |
| Seagate ST3500320AS 500GB         | 22       | 26     | 0.41%   |
| Toshiba DT01ACA100 1TB            | 21       | 31     | 0.39%   |
| Seagate ST3320418AS 320GB         | 21       | 24     | 0.39%   |
| Seagate ST1000DL002-9TT153 1TB    | 21       | 22     | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1865     | 2677   | 37.19%  |
| WDC                 | 1506     | 2108   | 30.03%  |
| Hitachi             | 460      | 616    | 9.17%   |
| Samsung Electronics | 387      | 546    | 7.72%   |
| Toshiba             | 161      | 216    | 3.21%   |
| Maxtor              | 159      | 190    | 3.17%   |
| Kingston            | 94       | 105    | 1.87%   |
| OCZ                 | 47       | 63     | 0.94%   |
| SPCC                | 37       | 44     | 0.74%   |
| HGST                | 31       | 38     | 0.62%   |
| A-DATA Technology   | 31       | 45     | 0.62%   |
| Corsair             | 28       | 42     | 0.56%   |
| Intel               | 25       | 30     | 0.5%    |
| Kingmax             | 24       | 44     | 0.48%   |
| SanDisk             | 13       | 18     | 0.26%   |
| Plextor             | 12       | 23     | 0.24%   |
| KingSpec            | 11       | 12     | 0.22%   |
| IBM/Hitachi         | 11       | 14     | 0.22%   |
| China               | 11       | 13     | 0.22%   |
| Crucial             | 10       | 20     | 0.2%    |
| Fujitsu             | 9        | 10     | 0.18%   |
| AMD                 | 9        | 12     | 0.18%   |
| OCZ-VERTEX3         | 6        | 11     | 0.12%   |
| Neo                 | 4        | 6      | 0.08%   |
| Unknown             | 4        | 5      | 0.08%   |
| XPG                 | 3        | 4      | 0.06%   |
| Qumo                | 3        | 4      | 0.06%   |
| Netac               | 3        | 3      | 0.06%   |
| KingDian            | 3        | 4      | 0.06%   |
| IBM                 | 3        | 3      | 0.06%   |
| Apacer              | 3        | 3      | 0.06%   |
| Verbatim            | 2        | 2      | 0.04%   |
| Smartbuy            | 2        | 2      | 0.04%   |
| Silicon Motion      | 2        | 3      | 0.04%   |
| Quantum             | 2        | 2      | 0.04%   |
| PNY                 | 2        | 2      | 0.04%   |
| Patriot             | 2        | 2      | 0.04%   |
| LITEONIT            | 2        | 2      | 0.04%   |
| Intenso             | 2        | 7      | 0.04%   |
| Hewlett-Packard     | 2        | 3      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1864     | 2674   | 40.99%  |
| WDC                 | 1480     | 2060   | 32.55%  |
| Hitachi             | 460      | 616    | 10.12%  |
| Samsung Electronics | 364      | 518    | 8.01%   |
| Maxtor              | 159      | 190    | 3.5%    |
| Toshiba             | 158      | 213    | 3.47%   |
| HGST                | 31       | 38     | 0.68%   |
| IBM/Hitachi         | 11       | 14     | 0.24%   |
| Fujitsu             | 9        | 10     | 0.2%    |
| IBM                 | 3        | 3      | 0.07%   |
| Quantum             | 2        | 2      | 0.04%   |
| Hewlett-Packard     | 2        | 3      | 0.04%   |
| WD MediaMax         | 1        | 1      | 0.02%   |
| ExcelStor           | 1        | 1      | 0.02%   |
| ASMT                | 1        | 2      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3994     | 6346   | 89.55%  |
| SSD  | 446      | 603    | 10%     |
| NVMe | 20       | 33     | 0.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB          | 7        | 9      | 3.87%   |
| Seagate ST31000524AS 1TB          | 7        | 9      | 3.87%   |
| Seagate ST3500418AS 500GB         | 5        | 6      | 2.76%   |
| Seagate ST3500412AS 500GB         | 5        | 6      | 2.76%   |
| Hitachi HDS721010DLE630 1TB       | 5        | 6      | 2.76%   |
| Seagate ST31000333AS 1TB          | 3        | 3      | 1.66%   |
| Samsung Electronics SP0411N 40GB  | 3        | 4      | 1.66%   |
| Maxtor 6Y080L0 81GB               | 3        | 3      | 1.66%   |
| Hitachi HDS721010CLA332 1TB       | 3        | 3      | 1.66%   |
| HGST HTS545050A7E380 500GB        | 3        | 3      | 1.66%   |
| WDC WD5000AAKS-00V1A0 500GB       | 2        | 2      | 1.1%    |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 1.1%    |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 2      | 1.1%    |
| WDC WD15EARS-00MVWB0 1TB          | 2        | 4      | 1.1%    |
| Seagate STM3500418AS 500GB        | 2        | 2      | 1.1%    |
| Seagate ST500DM005 HD502HJ 500GB  | 2        | 3      | 1.1%    |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 1.1%    |
| Seagate ST500DM002-1BC142 500GB   | 2        | 2      | 1.1%    |
| Seagate ST3750528AS 752GB         | 2        | 2      | 1.1%    |
| Seagate ST3320613AS 320GB         | 2        | 3      | 1.1%    |
| Seagate ST3250318AS 249GB         | 2        | 2      | 1.1%    |
| Seagate ST32000542AS 2TB          | 2        | 4      | 1.1%    |
| Seagate ST3160318AS 160GB         | 2        | 2      | 1.1%    |
| Seagate ST250DM000-1BD141 250GB   | 2        | 2      | 1.1%    |
| Samsung Electronics HD503HI 500GB | 2        | 2      | 1.1%    |
| Samsung Electronics HD204UI 2TB   | 2        | 2      | 1.1%    |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 1.1%    |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 1.1%    |
| Hitachi HDS721050DLE630 500GB     | 2        | 2      | 1.1%    |
| Hitachi HDS721025CLA382 250GB     | 2        | 2      | 1.1%    |
| WDC WD800JD-22LSA0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800JB-00FMA0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800BB-55JKC0 80GB           | 1        | 2      | 0.55%   |
| WDC WD800BB-22JHA0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800BB-00JKC0 80GB           | 1        | 2      | 0.55%   |
| WDC WD800BB-00JHC0 80GB           | 1        | 1      | 0.55%   |
| WDC WD7501AALS-00J7B0 752GB       | 1        | 2      | 0.55%   |
| WDC WD6400AACS-00G8B0 640GB       | 1        | 1      | 0.55%   |
| WDC WD5001AALS-00E3A0 500GB       | 1        | 1      | 0.55%   |
| WDC WD5000BPVT-00HXZT1 500GB      | 1        | 1      | 0.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 67       | 79     | 37.22%  |
| WDC                 | 48       | 62     | 26.67%  |
| Samsung Electronics | 22       | 24     | 12.22%  |
| Hitachi             | 17       | 18     | 9.44%   |
| Maxtor              | 7        | 7      | 3.89%   |
| Toshiba             | 6        | 6      | 3.33%   |
| HGST                | 5        | 5      | 2.78%   |
| Transcend           | 1        | 1      | 0.56%   |
| OCZ                 | 1        | 1      | 0.56%   |
| Intel               | 1        | 1      | 0.56%   |
| Hewlett-Packard     | 1        | 1      | 0.56%   |
| GOODRAM             | 1        | 1      | 0.56%   |
| Crucial             | 1        | 1      | 0.56%   |
| Corsair             | 1        | 1      | 0.56%   |
| A-DATA Technology   | 1        | 1      | 0.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 7902     | 17292  | 55.74%  |
| Malfunc  | 4301     | 6982   | 30.34%  |
| Detected | 1797     | 4021   | 12.68%  |
| Failed   | 176      | 209    | 1.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 7478     | 53.05%  |
| AMD                              | 2942     | 20.87%  |
| JMicron Technology               | 759      | 5.38%   |
| Nvidia                           | 755      | 5.36%   |
| Marvell Technology Group         | 426      | 3.02%   |
| Samsung Electronics              | 363      | 2.58%   |
| ASMedia Technology               | 358      | 2.54%   |
| VIA Technologies                 | 206      | 1.46%   |
| Silicon Motion                   | 136      | 0.96%   |
| Phison Electronics               | 113      | 0.8%    |
| Kingston Technology Company      | 111      | 0.79%   |
| SanDisk                          | 73       | 0.52%   |
| ADATA Technology                 | 62       | 0.44%   |
| Realtek Semiconductor            | 53       | 0.38%   |
| Silicon Integrated Systems [SiS] | 39       | 0.28%   |
| Silicon Image                    | 36       | 0.26%   |
| Integrated Technology Express    | 30       | 0.21%   |
| Lite-On Technology               | 28       | 0.2%    |
| SK hynix                         | 15       | 0.11%   |
| Micron/Crucial Technology        | 11       | 0.08%   |
| MAXIO Technology (Hangzhou)      | 11       | 0.08%   |
| Adaptec                          | 10       | 0.07%   |
| Broadcom / LSI                   | 9        | 0.06%   |
| Netac Technology                 | 7        | 0.05%   |
| LSI Logic / Symbios Logic        | 6        | 0.04%   |
| Micron Technology                | 5        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 5        | 0.04%   |
| ULi Electronics                  | 4        | 0.03%   |
| Toshiba America Info Systems     | 4        | 0.03%   |
| Promise Technology               | 4        | 0.03%   |
| MCST                             | 4        | 0.03%   |
| KIOXIA                           | 4        | 0.03%   |
| Hewlett-Packard                  | 4        | 0.03%   |
| Shenzhen Longsys Electronics     | 3        | 0.02%   |
| Seagate Technology               | 3        | 0.02%   |
| OCZ Technology Group             | 3        | 0.02%   |
| Union Memory (Shenzhen)          | 2        | 0.01%   |
| Solid State Storage Technology   | 2        | 0.01%   |
| INNOGRIT                         | 2        | 0.01%   |
| Broadcom                         | 2        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1383     | 6.91%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1157     | 5.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1044     | 5.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1040     | 5.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 747      | 3.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 672      | 3.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 604      | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 586      | 2.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 585      | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 585      | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 557      | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 463      | 2.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 420      | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 408      | 2.04%   |
| Nvidia MCP61 SATA Controller                                                            | 394      | 1.97%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 374      | 1.87%   |
| Nvidia MCP61 IDE                                                                        | 370      | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 344      | 1.72%   |
| JMicron JMB368 IDE controller                                                           | 291      | 1.45%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 275      | 1.37%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 274      | 1.37%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 257      | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 230      | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 182      | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 182      | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 180      | 0.9%    |
| AMD FCH SATA Controller D                                                               | 180      | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 179      | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 177      | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 171      | 0.85%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 165      | 0.82%   |
| AMD FCH IDE Controller                                                                  | 140      | 0.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 135      | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 134      | 0.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 132      | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 120      | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 120      | 0.6%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 119      | 0.59%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 119      | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 115      | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7259     | 50.91%  |
| IDE  | 5692     | 39.92%  |
| NVMe | 996      | 6.99%   |
| RAID | 285      | 2%      |
| SAS  | 20       | 0.14%   |
| SCSI | 6        | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 7621     | 67.42%  |
| AMD          | 3674     | 32.5%   |
| CentaurHauls | 2        | 0.02%   |
| PowerMac7,2  | 1        | 0.01%   |
| MBE8C-PC     | 1        | 0.01%   |
| Loongson     | 1        | 0.01%   |
| Elbrus-MCST  | 1        | 0.01%   |
| E8C/EATX     | 1        | 0.01%   |
| E8C-SWTX     | 1        | 0.01%   |
| Unknown      | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 166      | 1.45%   |
| Intel Pentium 4 CPU 3.00GHz                 | 113      | 0.99%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 111      | 0.97%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 110      | 0.96%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 108      | 0.95%   |
| AMD FX-6300 Six-Core Processor              | 104      | 0.91%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 102      | 0.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 101      | 0.88%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 96       | 0.84%   |
| AMD Ryzen 5 3600 6-Core Processor           | 96       | 0.84%   |
| AMD Athlon II X2 250 Processor              | 90       | 0.79%   |
| AMD FX-8350 Eight-Core Processor            | 89       | 0.78%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 83       | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 82       | 0.72%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 80       | 0.7%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 75       | 0.66%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 74       | 0.65%   |
| AMD FX-4300 Quad-Core Processor             | 74       | 0.65%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 71       | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 70       | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 69       | 0.6%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 65       | 0.57%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 65       | 0.57%   |
| AMD FX-8320 Eight-Core Processor            | 65       | 0.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 62       | 0.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 59       | 0.52%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 58       | 0.51%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 57       | 0.5%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 57       | 0.5%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 56       | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 55       | 0.48%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 55       | 0.48%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 55       | 0.48%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 54       | 0.47%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 54       | 0.47%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 53       | 0.46%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 53       | 0.46%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 53       | 0.46%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 52       | 0.46%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 52       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1565     | 13.73%  |
| Intel Core i3           | 1164     | 10.21%  |
| Intel Core 2 Duo        | 740      | 6.49%   |
| Intel Celeron           | 675      | 5.92%   |
| Intel Pentium           | 664      | 5.82%   |
| Intel Core i7           | 627      | 5.5%    |
| AMD FX                  | 613      | 5.38%   |
| AMD Ryzen 5             | 500      | 4.39%   |
| Intel Xeon              | 489      | 4.29%   |
| AMD Athlon 64 X2        | 400      | 3.51%   |
| Intel Pentium Dual-Core | 375      | 3.29%   |
| Intel Core 2 Quad       | 338      | 2.96%   |
| AMD Athlon II X2        | 321      | 2.82%   |
| Intel Pentium 4         | 255      | 2.24%   |
| AMD Phenom II X4        | 201      | 1.76%   |
| AMD Ryzen 7             | 181      | 1.59%   |
| AMD Ryzen 3             | 158      | 1.39%   |
| AMD Athlon II X4        | 146      | 1.28%   |
| Other                   | 141      | 1.24%   |
| Intel Pentium Dual      | 139      | 1.22%   |
| Intel Core 2            | 131      | 1.15%   |
| AMD Athlon II X3        | 116      | 1.02%   |
| Intel Atom              | 115      | 1.01%   |
| Intel Pentium D         | 106      | 0.93%   |
| AMD A8                  | 103      | 0.9%    |
| AMD Phenom              | 99       | 0.87%   |
| AMD A10                 | 99       | 0.87%   |
| AMD A4                  | 95       | 0.83%   |
| AMD Athlon 64           | 88       | 0.77%   |
| AMD Phenom II X6        | 77       | 0.68%   |
| AMD A6                  | 75       | 0.66%   |
| Intel Pentium Gold      | 72       | 0.63%   |
| AMD Athlon X4           | 72       | 0.63%   |
| AMD Athlon              | 71       | 0.62%   |
| AMD Ryzen 9             | 47       | 0.41%   |
| AMD Sempron             | 42       | 0.37%   |
| Intel Genuine           | 35       | 0.31%   |
| AMD Phenom II X2        | 32       | 0.28%   |
| Intel Core i9           | 29       | 0.25%   |
| AMD Phenom II X3        | 22       | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 4786     | 41.2%   |
| 4       | 3478     | 29.94%  |
| 6       | 1040     | 8.95%   |
| Unknown | 794      | 6.83%   |
| 1       | 623      | 5.36%   |
| 8       | 420      | 3.62%   |
| 3       | 300      | 2.58%   |
| 12      | 75       | 0.65%   |
| 16      | 37       | 0.32%   |
| 10      | 36       | 0.31%   |
| 24      | 13       | 0.11%   |
| 18      | 5        | 0.04%   |
| 14      | 3        | 0.03%   |
| 32      | 2        | 0.02%   |
| 20      | 2        | 0.02%   |
| 22      | 1        | 0.01%   |
| 15      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 11242    | 99.43%  |
| 2       | 56       | 0.5%    |
| Unknown | 7        | 0.06%   |
| 4       | 1        | 0.01%   |
| 0       | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 6554     | 56.57%  |
| 2       | 4236     | 36.56%  |
| Unknown | 794      | 6.85%   |
| 6       | 2        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 11059    | 97.72%  |
| 32-bit         | 183      | 1.62%   |
| Unknown        | 70       | 0.62%   |
| 64-bit         | 5        | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1132     | 9.75%   |
| 0x1067a    | 995      | 8.57%   |
| 0x206a7    | 903      | 7.78%   |
| 0x306a9    | 812      | 7%      |
| 0x306c3    | 794      | 6.84%   |
| 0x010000c8 | 495      | 4.26%   |
| 0x506e3    | 403      | 3.47%   |
| 0x906e9    | 289      | 2.49%   |
| 0x906ea    | 284      | 2.45%   |
| 0x6fd      | 269      | 2.32%   |
| 0x10676    | 262      | 2.26%   |
| 0x06000852 | 231      | 1.99%   |
| 0x6fb      | 227      | 1.96%   |
| 0x06001119 | 217      | 1.87%   |
| 0x0600084f | 171      | 1.47%   |
| 0xa0653    | 167      | 1.44%   |
| 0x0800820d | 161      | 1.39%   |
| 0x08701021 | 153      | 1.32%   |
| 0x010000db | 145      | 1.25%   |
| 0x106e5    | 118      | 1.02%   |
| 0x20655    | 103      | 0.89%   |
| 0x06003106 | 98       | 0.84%   |
| 0x08108109 | 92       | 0.79%   |
| 0x08001138 | 90       | 0.78%   |
| 0x906eb    | 87       | 0.75%   |
| 0xf49      | 82       | 0.71%   |
| 0x6f6      | 81       | 0.7%    |
| 0x206d7    | 80       | 0.69%   |
| 0x6f2      | 79       | 0.68%   |
| 0x306f2    | 78       | 0.67%   |
| 0x010000c7 | 76       | 0.65%   |
| 0xf41      | 74       | 0.64%   |
| 0x08101016 | 70       | 0.6%    |
| 0x010000dc | 70       | 0.6%    |
| 0x03000027 | 69       | 0.59%   |
| 0x20652    | 68       | 0.59%   |
| 0x0600063d | 68       | 0.59%   |
| 0x0600063e | 65       | 0.56%   |
| 0xa0671    | 63       | 0.54%   |
| 0x10677    | 62       | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 1286     | 11.28%  |
| SandyBridge      | 1017     | 8.92%   |
| K10              | 1014     | 8.89%   |
| Haswell          | 917      | 8.04%   |
| IvyBridge        | 908      | 7.96%   |
| KabyLake         | 794      | 6.96%   |
| Core             | 778      | 6.82%   |
| Piledriver       | 698      | 6.12%   |
| K8 Hammer        | 499      | 4.38%   |
| NetBurst         | 471      | 4.13%   |
| Skylake          | 446      | 3.91%   |
| Zen+             | 303      | 2.66%   |
| Zen              | 303      | 2.66%   |
| Zen 2            | 269      | 2.36%   |
| CometLake        | 236      | 2.07%   |
| Westmere         | 202      | 1.77%   |
| Unknown          | 169      | 1.48%   |
| Nehalem          | 167      | 1.46%   |
| Bulldozer        | 140      | 1.23%   |
| Zen 3            | 117      | 1.03%   |
| Steamroller      | 109      | 0.96%   |
| Silvermont       | 100      | 0.88%   |
| Bonnell          | 93       | 0.82%   |
| K10 Llano        | 75       | 0.66%   |
| Excavator        | 55       | 0.48%   |
| Goldmont plus    | 47       | 0.41%   |
| Icelake          | 35       | 0.31%   |
| Alderlake Hybrid | 29       | 0.25%   |
| Jaguar           | 24       | 0.21%   |
| Goldmont         | 24       | 0.21%   |
| Broadwell        | 22       | 0.19%   |
| Bobcat           | 21       | 0.18%   |
| K6               | 11       | 0.1%    |
| Tremont          | 10       | 0.09%   |
| Puma             | 6        | 0.05%   |
| P6               | 5        | 0.04%   |
| TigerLake        | 2        | 0.02%   |
| K8 & K10 hybrid  | 1        | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 5693     | 47.62%  |
| AMD                                          | 3164     | 26.47%  |
| Intel                                        | 3036     | 25.4%   |
| VIA Technologies                             | 15       | 0.13%   |
| ASPEED Technology                            | 15       | 0.13%   |
| Matrox Electronics Systems                   | 13       | 0.11%   |
| ATI Technologies                             | 7        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.03%   |
| S3 Graphics                                  | 3        | 0.03%   |
| Silicon Motion                               | 2        | 0.02%   |
| Zhaoxin                                      | 1        | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.01%   |
| Loongson Technology                          | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 371      | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 364      | 2.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 292      | 2.34%   |
| Nvidia GK208B [GeForce GT 710]                                              | 259      | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 258      | 2.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 248      | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 246      | 1.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 211      | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 210      | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 206      | 1.65%   |
| Nvidia GF108 [GeForce GT 630]                                               | 174      | 1.4%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 171      | 1.37%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 165      | 1.32%   |
| Intel HD Graphics 530                                                       | 165      | 1.32%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 148      | 1.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 147      | 1.18%   |
| Nvidia GF119 [GeForce GT 610]                                               | 145      | 1.16%   |
| Intel HD Graphics 630                                                       | 134      | 1.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 129      | 1.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 121      | 0.97%   |
| Nvidia GF108 [GeForce GT 430]                                               | 121      | 0.97%   |
| Nvidia GK208B [GeForce GT 730]                                              | 120      | 0.96%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 119      | 0.96%   |
| AMD RS780L [Radeon 3000]                                                    | 118      | 0.95%   |
| Nvidia G92 [GeForce GTS 250]                                                | 116      | 0.93%   |
| Nvidia GF108 [GeForce GT 440]                                               | 114      | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 110      | 0.88%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 107      | 0.86%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 107      | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 105      | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 101      | 0.81%   |
| Nvidia GT215 [GeForce GT 240]                                               | 97       | 0.78%   |
| Nvidia GF108 [GeForce GT 730]                                               | 94       | 0.75%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 92       | 0.74%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 92       | 0.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 92       | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 90       | 0.72%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 90       | 0.72%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 88       | 0.71%   |
| Intel HD Graphics 510                                                       | 88       | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| 1 x Nvidia                    | 5466     | 47.28%  |
| 1 x AMD                       | 2840     | 24.57%  |
| 1 x Intel                     | 2666     | 23.06%  |
| 2 x AMD                       | 256      | 2.21%   |
| Intel + Nvidia                | 150      | 1.3%    |
| AMD + Nvidia                  | 45       | 0.39%   |
| Intel + AMD                   | 34       | 0.29%   |
| 2 x Nvidia                    | 30       | 0.26%   |
| 1 x VIA                       | 15       | 0.13%   |
| 1 x ASPEED                    | 13       | 0.11%   |
| 1 x Matrox                    | 11       | 0.1%    |
| Other                         | 8        | 0.07%   |
| 3 x Nvidia                    | 3        | 0.03%   |
| 3 x AMD                       | 3        | 0.03%   |
| 1 x SiS                       | 3        | 0.03%   |
| 1 x Silicon Motion            | 2        | 0.02%   |
| 1 x S3 Graphics               | 2        | 0.02%   |
| Nvidia + Matrox               | 2        | 0.02%   |
| Nvidia + ASPEED               | 2        | 0.02%   |
| 2 x Intel                     | 1        | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1        | 0.01%   |
| 1 x XGI                       | 1        | 0.01%   |
| Nvidia + Zhaoxin              | 1        | 0.01%   |
| 1 x Loongson Technology       | 1        | 0.01%   |
| Intel + 2 x Nvidia            | 1        | 0.01%   |
| Intel + 2 x AMD               | 1        | 0.01%   |
| Intel + SiS + 1 x S3 Graphics | 1        | 0.01%   |
| Intel + AMD + 4 x Nvidia      | 1        | 0.01%   |
| AMD + 2 x Nvidia              | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 8283     | 69.57%  |
| Proprietary | 2323     | 19.51%  |
| Unknown     | 1300     | 10.92%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3207     | 26.77%  |
| 1.01-2.0   | 2417     | 20.18%  |
| 0.51-1.0   | 2344     | 19.57%  |
| 0.01-0.5   | 2288     | 19.1%   |
| 3.01-4.0   | 901      | 7.52%   |
| 7.01-8.0   | 378      | 3.16%   |
| 5.01-6.0   | 201      | 1.68%   |
| 2.01-3.0   | 156      | 1.3%    |
| 8.01-16.0  | 75       | 0.63%   |
| 4.01-5.0   | 6        | 0.05%   |
| 16.01-24.0 | 6        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2630     | 24.35%  |
| Goldstar             | 1527     | 14.13%  |
| Acer                 | 1180     | 10.92%  |
| BenQ                 | 942      | 8.72%   |
| Philips              | 725      | 6.71%   |
| ViewSonic            | 535      | 4.95%   |
| AOC                  | 505      | 4.67%   |
| Dell                 | 465      | 4.3%    |
| Ancor Communications | 364      | 3.37%   |
| Hewlett-Packard      | 288      | 2.67%   |
| NEC Computers        | 242      | 2.24%   |
| Iiyama               | 143      | 1.32%   |
| Sony                 | 100      | 0.93%   |
| Unknown              | 75       | 0.69%   |
| Envision Peripherals | 61       | 0.56%   |
| ASUSTek Computer     | 61       | 0.56%   |
| Plain Tree Systems   | 56       | 0.52%   |
| LG Electronics       | 56       | 0.52%   |
| HHT                  | 45       | 0.42%   |
| Lenovo               | 44       | 0.41%   |
| Packard Bell         | 39       | 0.36%   |
| ___                  | 32       | 0.3%    |
| Toshiba              | 24       | 0.22%   |
| Fujitsu Siemens      | 23       | 0.21%   |
| Mi                   | 20       | 0.19%   |
| CHR                  | 20       | 0.19%   |
| VIE                  | 19       | 0.18%   |
| MiTAC                | 19       | 0.18%   |
| KTC                  | 19       | 0.18%   |
| HannStar             | 18       | 0.17%   |
| JRY                  | 15       | 0.14%   |
| HKC                  | 15       | 0.14%   |
| Panasonic            | 14       | 0.13%   |
| MStar                | 14       | 0.13%   |
| MSI                  | 14       | 0.13%   |
| HUAWEI               | 14       | 0.13%   |
| Haier                | 14       | 0.13%   |
| AGO                  | 14       | 0.13%   |
| Hitachi              | 12       | 0.11%   |
| BBK                  | 11       | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 78       | 0.69%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 71       | 0.63%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                   | 70       | 0.62%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 63       | 0.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 60       | 0.53%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 54       | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 54       | 0.48%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 46       | 0.41%   |
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 44       | 0.39%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch  | 43       | 0.38%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 43       | 0.38%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 43       | 0.38%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 40       | 0.36%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 38       | 0.34%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 36       | 0.32%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 35       | 0.31%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 33       | 0.29%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                   | 32       | 0.28%   |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                    | 32       | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 29       | 0.26%   |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                 | 28       | 0.25%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 28       | 0.25%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 27       | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 27       | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 27       | 0.24%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 26       | 0.23%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 26       | 0.23%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                      | 26       | 0.23%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch | 25       | 0.22%   |
| Plain Tree Systems LCD Monitor PTS06A5 1280x1024 337x270mm 17.0-inch | 25       | 0.22%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 25       | 0.22%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 25       | 0.22%   |
| Goldstar L1952S GSM4AE0 1280x1024 376x301mm 19.0-inch                | 24       | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 23       | 0.2%    |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                | 23       | 0.2%    |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                | 23       | 0.2%    |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch | 22       | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 22       | 0.2%    |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 22       | 0.2%    |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 22       | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 4614     | 43.41%  |
| 1280x1024 (SXGA)   | 2210     | 20.79%  |
| 1680x1050 (WSXGA+) | 613      | 5.77%   |
| 1440x900 (WXGA+)   | 540      | 5.08%   |
| 1366x768 (WXGA)    | 440      | 4.14%   |
| 1600x900 (HD+)     | 376      | 3.54%   |
| 3840x2160 (4K)     | 368      | 3.46%   |
| 2560x1440 (QHD)    | 359      | 3.38%   |
| 1920x1200 (WUXGA)  | 200      | 1.88%   |
| 1360x768           | 186      | 1.75%   |
| 1024x768 (XGA)     | 154      | 1.45%   |
| 1600x1200          | 86       | 0.81%   |
| 2560x1080          | 84       | 0.79%   |
| Unknown            | 83       | 0.78%   |
| 3440x1440          | 49       | 0.46%   |
| 1280x720 (HD)      | 37       | 0.35%   |
| 1920x540           | 32       | 0.3%    |
| 1400x1050          | 24       | 0.23%   |
| 3840x1080          | 22       | 0.21%   |
| 2288x1287          | 16       | 0.15%   |
| 2048x1536          | 13       | 0.12%   |
| 1152x864           | 13       | 0.12%   |
| 1280x960           | 12       | 0.11%   |
| 4480x1440          | 8        | 0.08%   |
| 2048x1152          | 8        | 0.08%   |
| 1920x1440          | 8        | 0.08%   |
| 2560x1600          | 6        | 0.06%   |
| 3200x1080          | 5        | 0.05%   |
| 7680x2160          | 4        | 0.04%   |
| 5760x1080          | 4        | 0.04%   |
| 3600x1080          | 4        | 0.04%   |
| 2160x1200          | 4        | 0.04%   |
| 5760x2160          | 3        | 0.03%   |
| 1280x768           | 3        | 0.03%   |
| 5120x1440          | 2        | 0.02%   |
| 5120x1080          | 2        | 0.02%   |
| 4093x4093          | 2        | 0.02%   |
| 4000x1440          | 2        | 0.02%   |
| 3840x2560          | 2        | 0.02%   |
| 3840x1600          | 2        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 1750     | 16.13%  |
| 19      | 1551     | 14.29%  |
| 23      | 1384     | 12.76%  |
| 24      | 1097     | 10.11%  |
| 17      | 1093     | 10.07%  |
| 27      | 715      | 6.59%   |
| 18      | 611      | 5.63%   |
| 20      | 502      | 4.63%   |
| Unknown | 421      | 3.88%   |
| 22      | 380      | 3.5%    |
| 15      | 279      | 2.57%   |
| 31      | 168      | 1.55%   |
| 34      | 120      | 1.11%   |
| 40      | 115      | 1.06%   |
| 72      | 86       | 0.79%   |
| 54      | 86       | 0.79%   |
| 32      | 73       | 0.67%   |
| 52      | 42       | 0.39%   |
| 16      | 39       | 0.36%   |
| 25      | 36       | 0.33%   |
| 84      | 32       | 0.29%   |
| 48      | 26       | 0.24%   |
| 46      | 26       | 0.24%   |
| 12      | 20       | 0.18%   |
| 43      | 19       | 0.18%   |
| 42      | 19       | 0.18%   |
| 26      | 18       | 0.17%   |
| 14      | 15       | 0.14%   |
| 142     | 14       | 0.13%   |
| 28      | 14       | 0.13%   |
| 13      | 12       | 0.11%   |
| 33      | 11       | 0.1%    |
| 29      | 9        | 0.08%   |
| 58      | 7        | 0.06%   |
| 50      | 7        | 0.06%   |
| 37      | 7        | 0.06%   |
| 60      | 6        | 0.06%   |
| 39      | 6        | 0.06%   |
| 65      | 5        | 0.05%   |
| 47      | 5        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 3706     | 34.73%  |
| 501-600        | 3053     | 28.61%  |
| 301-350        | 1386     | 12.99%  |
| 351-400        | 1100     | 10.31%  |
| Unknown        | 421      | 3.94%   |
| 601-700        | 229      | 2.15%   |
| 1001-1500      | 217      | 2.03%   |
| 701-800        | 204      | 1.91%   |
| 1501-2000      | 122      | 1.14%   |
| 801-900        | 86       | 0.81%   |
| 901-1000       | 84       | 0.79%   |
| 201-300        | 45       | 0.42%   |
| More than 2000 | 18       | 0.17%   |
| 1-100          | 1        | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 5915     | 57%     |
| 5/4     | 2098     | 20.22%  |
| 16/10   | 1281     | 12.34%  |
| 4/3     | 440      | 4.24%   |
| Unknown | 311      | 3%      |
| 21/9    | 172      | 1.66%   |
| 3/2     | 99       | 0.95%   |
| 6/5     | 37       | 0.36%   |
| 1.00    | 14       | 0.13%   |
| 32/9    | 10       | 0.1%    |
| 2.00    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3933     | 36.73%  |
| 151-200        | 2513     | 23.47%  |
| 141-150        | 1544     | 14.42%  |
| 301-350        | 732      | 6.84%   |
| Unknown        | 421      | 3.93%   |
| 351-500        | 376      | 3.51%   |
| More than 1000 | 318      | 2.97%   |
| 251-300        | 291      | 2.72%   |
| 501-1000       | 211      | 1.97%   |
| 101-110        | 176      | 1.64%   |
| 111-120        | 117      | 1.09%   |
| 121-130        | 24       | 0.22%   |
| 71-80          | 22       | 0.21%   |
| 131-140        | 14       | 0.13%   |
| 81-90          | 9        | 0.08%   |
| 91-100         | 5        | 0.05%   |
| 61-70          | 1        | 0.01%   |
| 51-60          | 1        | 0.01%   |
| 1-40           | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 7210     | 69.63%  |
| 101-120       | 2086     | 20.15%  |
| Unknown       | 421      | 4.07%   |
| 1-50          | 384      | 3.71%   |
| 121-160       | 168      | 1.62%   |
| 161-240       | 83       | 0.8%    |
| More than 240 | 2        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9544     | 82.59%  |
| 0     | 1038     | 8.98%   |
| 2     | 907      | 7.85%   |
| 3     | 64       | 0.55%   |
| 4     | 3        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8097     | 55.68%  |
| Intel                                  | 1615     | 11.11%  |
| Qualcomm Atheros                       | 1419     | 9.76%   |
| Nvidia                                 | 655      | 4.5%    |
| Ralink Technology                      | 374      | 2.57%   |
| Huawei Technologies                    | 258      | 1.77%   |
| Marvell Technology Group               | 221      | 1.52%   |
| Ralink                                 | 189      | 1.3%    |
| TP-Link                                | 186      | 1.28%   |
| VIA Technologies                       | 181      | 1.24%   |
| D-Link System                          | 142      | 0.98%   |
| D-Link                                 | 126      | 0.87%   |
| Broadcom                               | 125      | 0.86%   |
| ASUSTek Computer                       | 104      | 0.72%   |
| Qualcomm Atheros Communications        | 96       | 0.66%   |
| ZTE WCDMA Technologies MSM             | 68       | 0.47%   |
| Xiaomi                                 | 68       | 0.47%   |
| Broadcom Limited                       | 66       | 0.45%   |
| MediaTek                               | 56       | 0.39%   |
| Samsung Electronics                    | 42       | 0.29%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.25%   |
| 3Com                                   | 31       | 0.21%   |
| Silicon Integrated Systems [SiS]       | 29       | 0.2%    |
| Microsoft                              | 23       | 0.16%   |
| NetGear                                | 18       | 0.12%   |
| Mercucys                               | 16       | 0.11%   |
| IMC Networks                           | 16       | 0.11%   |
| ZyXEL Communications                   | 15       | 0.1%    |
| HTC (High Tech Computer)               | 15       | 0.1%    |
| Gemtek                                 | 15       | 0.1%    |
| ASIX Electronics                       | 14       | 0.1%    |
| Spreadtrum Communications              | 12       | 0.08%   |
| Aquantia                               | 12       | 0.08%   |
| Qualcomm                               | 11       | 0.08%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.07%   |
| OPPO Electronics                       | 10       | 0.07%   |
| LSI                                    | 9        | 0.06%   |
| GCT Semiconductor                      | 8        | 0.06%   |
| Xilinx                                 | 7        | 0.05%   |
| T & A Mobile Phones                    | 7        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6829     | 43.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 459      | 2.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 400      | 2.57%   |
| Nvidia MCP61 Ethernet                                             | 352      | 2.27%   |
| Ralink MT7601U Wireless Adapter                                   | 228      | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 209      | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 202      | 1.3%    |
| Intel I211 Gigabit Network Connection                             | 178      | 1.15%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 176      | 1.13%   |
| Intel 82579V Gigabit Network Connection                           | 158      | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 154      | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 151      | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 135      | 0.87%   |
| Huawei Modem/Networkcard                                          | 134      | 0.86%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 124      | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 123      | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 115      | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 106      | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 102      | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 91       | 0.59%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 82       | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                   | 79       | 0.51%   |
| Intel Wi-Fi 6 AX200                                               | 78       | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 77       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 75       | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 73       | 0.47%   |
| Intel Ethernet Connection (14) I219-V                             | 71       | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 67       | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 65       | 0.42%   |
| Nvidia CK804 Ethernet Controller                                  | 65       | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 64       | 0.41%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 63       | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 63       | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 62       | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 61       | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 60       | 0.39%   |
| Intel Ethernet Connection (2) I218-V                              | 58       | 0.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58       | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 57       | 0.37%   |
| Intel Ethernet Controller I225-V                                  | 55       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 694      | 24.76%  |
| Qualcomm Atheros                | 386      | 13.77%  |
| Intel                           | 375      | 13.38%  |
| Ralink Technology               | 374      | 13.34%  |
| Ralink                          | 189      | 6.74%   |
| TP-Link                         | 182      | 6.49%   |
| D-Link                          | 122      | 4.35%   |
| ASUSTek Computer                | 98       | 3.5%    |
| Qualcomm Atheros Communications | 96       | 3.42%   |
| Broadcom                        | 74       | 2.64%   |
| D-Link System                   | 60       | 2.14%   |
| Microsoft                       | 23       | 0.82%   |
| NetGear                         | 17       | 0.61%   |
| Mercucys                        | 16       | 0.57%   |
| IMC Networks                    | 16       | 0.57%   |
| MediaTek                        | 14       | 0.5%    |
| ZyXEL Communications            | 13       | 0.46%   |
| Broadcom Limited                | 10       | 0.36%   |
| Xiaomi                          | 7        | 0.25%   |
| Tenda                           | 6        | 0.21%   |
| ZyDAS                           | 3        | 0.11%   |
| VIA Technologies                | 3        | 0.11%   |
| Texas Instruments               | 3        | 0.11%   |
| Micro Star International        | 3        | 0.11%   |
| Marvell Technology Group        | 3        | 0.11%   |
| TRENDnet                        | 2        | 0.07%   |
| Edimax Technology               | 2        | 0.07%   |
| Z-Com                           | 1        | 0.04%   |
| Wilocity                        | 1        | 0.04%   |
| Sierra Wireless                 | 1        | 0.04%   |
| Linksys                         | 1        | 0.04%   |
| Gemtek                          | 1        | 0.04%   |
| Chu Yuen Enterprise             | 1        | 0.04%   |
| BUFFALO                         | 1        | 0.04%   |
| Belkin Components               | 1        | 0.04%   |
| ASUSTek Computer (wrong ID)     | 1        | 0.04%   |
| AirTies Wireless Networks       | 1        | 0.04%   |
| Accton Technology               | 1        | 0.04%   |
| AboCom Systems                  | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                    | 228      | 8.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 154      | 5.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 106      | 3.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 91       | 3.21%   |
| Qualcomm Atheros AR9271 802.11n                                    | 79       | 2.79%   |
| Intel Wi-Fi 6 AX200                                                | 78       | 2.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                   | 64       | 2.26%   |
| Ralink RT5370 Wireless Adapter                                     | 61       | 2.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 57       | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 51       | 1.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 47       | 1.66%   |
| Realtek 802.11ac NIC                                               | 47       | 1.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 46       | 1.62%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 45       | 1.59%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 45       | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 45       | 1.59%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 39       | 1.38%   |
| Ralink RT2561/RT61 rev B 802.11g                                   | 37       | 1.31%   |
| Intel Wireless-AC 9260                                             | 36       | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 35       | 1.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 34       | 1.2%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 31       | 1.09%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                         | 30       | 1.06%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                               | 30       | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 30       | 1.06%   |
| Intel Wireless 3165                                                | 30       | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 29       | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 27       | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 27       | 0.95%   |
| D-Link 802.11 n WLAN                                               | 27       | 0.95%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                | 26       | 0.92%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]          | 26       | 0.92%   |
| Intel Wireless 7265                                                | 25       | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 24       | 0.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 23       | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                          | 21       | 0.74%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 20       | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 19       | 0.67%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller          | 18       | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 18       | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 7871     | 64.63%  |
| Intel                                  | 1412     | 11.59%  |
| Qualcomm Atheros                       | 1074     | 8.82%   |
| Nvidia                                 | 655      | 5.38%   |
| Marvell Technology Group               | 218      | 1.79%   |
| VIA Technologies                       | 176      | 1.45%   |
| D-Link System                          | 83       | 0.68%   |
| Huawei Technologies                    | 78       | 0.64%   |
| ZTE WCDMA Technologies MSM             | 63       | 0.52%   |
| Xiaomi                                 | 61       | 0.5%    |
| Broadcom Limited                       | 56       | 0.46%   |
| Broadcom                               | 51       | 0.42%   |
| Samsung Electronics                    | 42       | 0.34%   |
| MediaTek                               | 41       | 0.34%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.3%    |
| 3Com                                   | 31       | 0.25%   |
| Silicon Integrated Systems [SiS]       | 29       | 0.24%   |
| HTC (High Tech Computer)               | 15       | 0.12%   |
| Gemtek                                 | 14       | 0.11%   |
| ASIX Electronics                       | 14       | 0.11%   |
| Spreadtrum Communications              | 12       | 0.1%    |
| Aquantia                               | 12       | 0.1%    |
| Qualcomm                               | 11       | 0.09%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.08%   |
| OPPO Electronics                       | 10       | 0.08%   |
| GCT Semiconductor                      | 8        | 0.07%   |
| T & A Mobile Phones                    | 7        | 0.06%   |
| Vimtron Electronics                    | 6        | 0.05%   |
| JMicron Technology                     | 6        | 0.05%   |
| HMD Global                             | 6        | 0.05%   |
| ASUSTek Computer                       | 6        | 0.05%   |
| TP-Link                                | 5        | 0.04%   |
| Lenovo                                 | 5        | 0.04%   |
| ULi Electronics                        | 4        | 0.03%   |
| MCST                                   | 4        | 0.03%   |
| D-Link                                 | 4        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.02%   |
| ICS Advent                             | 3        | 0.02%   |
| Davicom Semiconductor                  | 3        | 0.02%   |
| ZyXEL Communications                   | 2        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6829     | 54.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 459      | 3.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 400      | 3.21%   |
| Nvidia MCP61 Ethernet                                             | 352      | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 209      | 1.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 202      | 1.62%   |
| Intel I211 Gigabit Network Connection                             | 178      | 1.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 176      | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 158      | 1.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 151      | 1.21%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 135      | 1.08%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 124      | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 123      | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 115      | 0.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 102      | 0.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 82       | 0.66%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 77       | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 75       | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 73       | 0.59%   |
| Intel Ethernet Connection (14) I219-V                             | 71       | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 67       | 0.54%   |
| Nvidia MCP77 Ethernet                                             | 65       | 0.52%   |
| Nvidia CK804 Ethernet Controller                                  | 65       | 0.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 63       | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 63       | 0.51%   |
| Intel 82574L Gigabit Network Connection                           | 62       | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 60       | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 58       | 0.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58       | 0.47%   |
| Intel Ethernet Controller I225-V                                  | 55       | 0.44%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 53       | 0.43%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 52       | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 51       | 0.41%   |
| Nvidia MCP55 Ethernet                                             | 51       | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 50       | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 46       | 0.37%   |
| Huawei ELS-NX9                                                    | 43       | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 39       | 0.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 39       | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11193    | 79.33%  |
| WiFi     | 2667     | 18.9%   |
| Modem    | 229      | 1.62%   |
| Unknown  | 20       | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 9494     | 84.66%  |
| WiFi     | 1719     | 15.33%  |
| Modem    | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9175     | 80.6%   |
| 2     | 1919     | 16.86%  |
| 3     | 157      | 1.38%   |
| 0     | 96       | 0.84%   |
| 4     | 27       | 0.24%   |
| 5     | 3        | 0.03%   |
| 8     | 2        | 0.02%   |
| 6     | 2        | 0.02%   |
| 33    | 1        | 0.01%   |
| 13    | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11181    | 98.65%  |
| Yes  | 153      | 1.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 676      | 44.39%  |
| Intel                           | 336      | 22.06%  |
| ASUSTek Computer                | 142      | 9.32%   |
| Realtek Semiconductor           | 107      | 7.03%   |
| Broadcom                        | 89       | 5.84%   |
| Qualcomm Atheros Communications | 47       | 3.09%   |
| Integrated System Solution      | 28       | 1.84%   |
| IMC Networks                    | 17       | 1.12%   |
| TP-Link                         | 13       | 0.85%   |
| Lite-On Technology              | 12       | 0.79%   |
| Conwise Technology              | 9        | 0.59%   |
| MediaTek                        | 7        | 0.46%   |
| Apple                           | 7        | 0.46%   |
| Ralink                          | 6        | 0.39%   |
| Roper                           | 5        | 0.33%   |
| Logitech                        | 4        | 0.26%   |
| HTC (High Tech Computer)        | 4        | 0.26%   |
| Foxconn / Hon Hai               | 4        | 0.26%   |
| Hewlett-Packard                 | 3        | 0.2%    |
| D-Link System                   | 3        | 0.2%    |
| Micro Star International        | 2        | 0.13%   |
| TRENDnet                        | 1        | 0.07%   |
| Edimax Technology               | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 676      | 44.33%  |
| Intel Bluetooth wireless interface                                   | 95       | 6.23%   |
| Realtek Bluetooth Radio                                              | 94       | 6.16%   |
| Intel AX200 Bluetooth                                                | 75       | 4.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 62       | 4.07%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 49       | 3.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 31       | 2.03%   |
| Intel AX210 Bluetooth                                                | 31       | 2.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 28       | 1.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 24       | 1.57%   |
| ASUS Bluetooth Adapter                                               | 23       | 1.51%   |
| Intel Bluetooth Device                                               | 22       | 1.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 20       | 1.31%   |
| Broadcom BCM2045 Bluetooth                                           | 18       | 1.18%   |
| Integrated System Solution Bluetooth Device                          | 16       | 1.05%   |
| ASUS BCM20702A0                                                      | 16       | 1.05%   |
| TP-Link TPuLink UB500 Adapter                                        | 13       | 0.85%   |
| Broadcom Bluetooth 3.0 USB Dongle                                    | 13       | 0.85%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 12       | 0.79%   |
| ASUS Bluetooth Radio                                                 | 12       | 0.79%   |
| Lite-On Bluetooth Device                                             | 11       | 0.72%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 11       | 0.72%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 0.66%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 9        | 0.59%   |
| Conwise CW6622                                                       | 9        | 0.59%   |
| Broadcom BCM92045B3 ROM                                              | 9        | 0.59%   |
| ASUS ASUS USB-BT500                                                  | 9        | 0.59%   |
| MediaTek Wireless_Device                                             | 7        | 0.46%   |
| Ralink RT3290 Bluetooth                                              | 6        | 0.39%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6        | 0.39%   |
| ASUS Bluetooth Device                                                | 6        | 0.39%   |
| Roper Class 1 Bluetooth Dongle                                       | 5        | 0.33%   |
| Qualcomm Atheros Bluetooth (AR3011)                                  | 5        | 0.33%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 4        | 0.26%   |
| IMC Networks Bluetooth Radio                                         | 4        | 0.26%   |
| IMC Networks Bluetooth Module                                        | 4        | 0.26%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.26%   |
| Broadcom Bluetooth dongle                                            | 4        | 0.26%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 4        | 0.26%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 4        | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 7239     | 40.19%  |
| Nvidia                               | 4904     | 27.23%  |
| AMD                                  | 4184     | 23.23%  |
| C-Media Electronics                  | 468      | 2.6%    |
| Creative Labs                        | 298      | 1.65%   |
| VIA Technologies                     | 115      | 0.64%   |
| Creative Technology                  | 77       | 0.43%   |
| JMTek                                | 67       | 0.37%   |
| Logitech                             | 64       | 0.36%   |
| Texas Instruments                    | 45       | 0.25%   |
| Generalplus Technology               | 39       | 0.22%   |
| Silicon Integrated Systems [SiS]     | 37       | 0.21%   |
| ASUSTek Computer                     | 23       | 0.13%   |
| Kingston Technology                  | 22       | 0.12%   |
| Plantronics                          | 18       | 0.1%    |
| Sony                                 | 14       | 0.08%   |
| Yamaha                               | 13       | 0.07%   |
| Razer USA                            | 13       | 0.07%   |
| Pixart Imaging                       | 11       | 0.06%   |
| GN Netcom                            | 11       | 0.06%   |
| A4Tech                               | 11       | 0.06%   |
| Focusrite-Novation                   | 10       | 0.06%   |
| Ensoniq                              | 10       | 0.06%   |
| SteelSeries ApS                      | 9        | 0.05%   |
| Samson Technologies                  | 8        | 0.04%   |
| M-Audio                              | 8        | 0.04%   |
| KTMicro                              | 8        | 0.04%   |
| Microsoft                            | 7        | 0.04%   |
| ESS Technology                       | 7        | 0.04%   |
| Conexant Systems                     | 7        | 0.04%   |
| BEHRINGER International              | 7        | 0.04%   |
| ATI Technologies                     | 7        | 0.04%   |
| XMOS                                 | 6        | 0.03%   |
| Tenx Technology                      | 6        | 0.03%   |
| Shenzhen Rapoo Technology            | 6        | 0.03%   |
| Aureal Semiconductor                 | 6        | 0.03%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.03%   |
| SAVITECH                             | 5        | 0.03%   |
| Realtek Semiconductor                | 5        | 0.03%   |
| Nordic Semiconductor ASA             | 5        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1391     | 6.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1375     | 6.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1105     | 5.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 706      | 3.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 658      | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 576      | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 534      | 2.65%   |
| AMD FCH Azalia Controller                                                  | 438      | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 428      | 2.12%   |
| Nvidia High Definition Audio Controller                                    | 422      | 2.09%   |
| Intel 200 Series PCH HD Audio                                              | 420      | 2.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 416      | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 401      | 1.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 383      | 1.9%    |
| Nvidia MCP61 High Definition Audio                                         | 381      | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 363      | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 352      | 1.75%   |
| AMD Family 17h/19h HD Audio Controller                                     | 323      | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 308      | 1.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 299      | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                   | 280      | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 279      | 1.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 266      | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 232      | 1.15%   |
| Nvidia GK106 HDMI Audio Controller                                         | 221      | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                              | 215      | 1.07%   |
| Nvidia GF119 HDMI Audio Controller                                         | 213      | 1.06%   |
| Nvidia GF116 High Definition Audio Controller                              | 204      | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 197      | 0.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 185      | 0.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 184      | 0.91%   |
| Nvidia GK104 HDMI Audio Controller                                         | 163      | 0.81%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 143      | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 141      | 0.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 133      | 0.66%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 133      | 0.66%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 130      | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                              | 124      | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 119      | 0.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 117      | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 4542     | 41.06%  |
| Kingston                     | 2118     | 19.15%  |
| Crucial                      | 883      | 7.98%   |
| Samsung Electronics          | 688      | 6.22%   |
| Corsair                      | 458      | 4.14%   |
| SK hynix                     | 457      | 4.13%   |
| Patriot                      | 286      | 2.59%   |
| AMD                          | 268      | 2.42%   |
| Micron Technology            | 154      | 1.39%   |
| A-DATA Technology            | 91       | 0.82%   |
| Goodram                      | 90       | 0.81%   |
| Nanya Technology             | 79       | 0.71%   |
| G.Skill                      | 79       | 0.71%   |
| Kingmax                      | 63       | 0.57%   |
| Qumo                         | 62       | 0.56%   |
| Apacer                       | 59       | 0.53%   |
| Foxline                      | 51       | 0.46%   |
| Goldkey                      | 49       | 0.44%   |
| Silicon Power                | 46       | 0.42%   |
| Unknown                      | 45       | 0.41%   |
| Elpida                       | 41       | 0.37%   |
| Kllisre                      | 39       | 0.35%   |
| Transcend                    | 37       | 0.33%   |
| KETECH                       | 29       | 0.26%   |
| GeIL                         | 27       | 0.24%   |
| Ramaxel Technology           | 24       | 0.22%   |
| Hikvision                    | 24       | 0.22%   |
| Unifosa                      | 21       | 0.19%   |
| Team                         | 19       | 0.17%   |
| Atermiter                    | 19       | 0.17%   |
| Ramos Technology             | 14       | 0.13%   |
| Unknown (ABCD)               | 12       | 0.11%   |
| Neo Forza                    | 10       | 0.09%   |
| Qimonda                      | 9        | 0.08%   |
| TakeMS                       | 8        | 0.07%   |
| Patriot Memory (PDP Systems) | 8        | 0.07%   |
| Hexon                        | 7        | 0.06%   |
| Wilk Elektronik              | 6        | 0.05%   |
| Patriot Memory               | 6        | 0.05%   |
| Juhor                        | 6        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 289      | 2.24%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 268      | 2.07%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 263      | 2.04%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 222      | 1.72%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 212      | 1.64%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 205      | 1.59%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s           | 186      | 1.44%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                | 142      | 1.1%    |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s           | 137      | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 122      | 0.94%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 97       | 0.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s   | 90       | 0.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                     | 89       | 0.69%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                | 89       | 0.69%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                | 86       | 0.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 85       | 0.66%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 83       | 0.64%   |
| Unknown RAM Module 512MB DIMM SDRAM                   | 80       | 0.62%   |
| Unknown RAM Module 1024MB DIMM                        | 71       | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s          | 69       | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s           | 64       | 0.5%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                | 63       | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 63       | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 62       | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 61       | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 61       | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s           | 60       | 0.46%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s | 59       | 0.46%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s | 56       | 0.43%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3            | 52       | 0.4%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 49       | 0.38%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 47       | 0.36%   |
| Unknown RAM Module 2048MB DIMM                        | 47       | 0.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 47       | 0.36%   |
| Unknown RAM Module 512MB DIMM                         | 46       | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 46       | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 45       | 0.35%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s | 45       | 0.35%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s | 45       | 0.35%   |
| Unknown                                               | 45       | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3461     | 34.35%  |
| DDR4    | 2228     | 22.11%  |
| Unknown | 1895     | 18.81%  |
| DDR2    | 1222     | 12.13%  |
| SDRAM   | 944      | 9.37%   |
| DDR     | 283      | 2.81%   |
| LPDDR4  | 18       | 0.18%   |
| DRAM    | 14       | 0.14%   |
| DDR5    | 12       | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 9709     | 97.21%  |
| SODIMM       | 271      | 2.71%   |
| FB-DIMM      | 5        | 0.05%   |
| Row Of Chips | 2        | 0.02%   |
| RIMM         | 1        | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 3354     | 29.01%  |
| 2048  | 3104     | 26.85%  |
| 8192  | 2402     | 20.78%  |
| 1024  | 1628     | 14.08%  |
| 16384 | 474      | 4.1%    |
| 512   | 397      | 3.43%   |
| 32768 | 104      | 0.9%    |
| 256   | 88       | 0.76%   |
| 32    | 5        | 0.04%   |
| 128   | 2        | 0.02%   |
| 16    | 2        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1977     | 18.05%  |
| 1333    | 1748     | 15.96%  |
| 800     | 1224     | 11.18%  |
| Unknown | 957      | 8.74%   |
| 667     | 677      | 6.18%   |
| 2400    | 529      | 4.83%   |
| 2133    | 419      | 3.83%   |
| 2667    | 388      | 3.54%   |
| 3200    | 353      | 3.22%   |
| 400     | 272      | 2.48%   |
| 1867    | 215      | 1.96%   |
| 1866    | 203      | 1.85%   |
| 1066    | 169      | 1.54%   |
| 3600    | 164      | 1.5%    |
| 3400    | 132      | 1.21%   |
| 333     | 132      | 1.21%   |
| 533     | 127      | 1.16%   |
| 2666    | 116      | 1.06%   |
| 2933    | 113      | 1.03%   |
| 3466    | 74       | 0.68%   |
| 1800    | 70       | 0.64%   |
| 3000    | 63       | 0.58%   |
| 1067    | 59       | 0.54%   |
| 266     | 59       | 0.54%   |
| 2866    | 52       | 0.47%   |
| 2800    | 48       | 0.44%   |
| 1334    | 45       | 0.41%   |
| 3066    | 34       | 0.31%   |
| 66      | 33       | 0.3%    |
| 1648    | 31       | 0.28%   |
| 2134    | 30       | 0.27%   |
| 2000    | 28       | 0.26%   |
| 1400    | 25       | 0.23%   |
| 3334    | 24       | 0.22%   |
| 3266    | 22       | 0.2%    |
| 3733    | 19       | 0.17%   |
| 200     | 19       | 0.17%   |
| 3333    | 17       | 0.16%   |
| 2934    | 17       | 0.16%   |
| 2048    | 16       | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 270      | 28.97%  |
| Canon                           | 199      | 21.35%  |
| Samsung Electronics             | 164      | 17.6%   |
| Seiko Epson                     | 84       | 9.01%   |
| Brother Industries              | 65       | 6.97%   |
| Xerox                           | 33       | 3.54%   |
| Pantum                          | 28       | 3%      |
| Panasonic (Matsushita)          | 25       | 2.68%   |
| Kyocera                         | 18       | 1.93%   |
| QinHeng Electronics             | 11       | 1.18%   |
| Ricoh                           | 10       | 1.07%   |
| Prolific Technology             | 6        | 0.64%   |
| TSC Auto ID Technology          | 2        | 0.21%   |
| STMicroelectronics              | 2        | 0.21%   |
| NXP Semiconductors              | 2        | 0.21%   |
| Lexmark International           | 2        | 0.21%   |
| Konica Minolta                  | 2        | 0.21%   |
| cab Produkttechnik GmbH & Co KG | 2        | 0.21%   |
| Sharp                           | 1        | 0.11%   |
| Samsung Info. Systems America   | 1        | 0.11%   |
| KODAK                           | 1        | 0.11%   |
| GODEX INTERNATIONAL             | 1        | 0.11%   |
| Fuji Xerox                      | 1        | 0.11%   |
| Datamax-O'Neil                  | 1        | 0.11%   |
| Apple                           | 1        | 0.11%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| HP LaserJet 1020                      | 29       | 3.09%   |
| Canon LBP2900                         | 29       | 3.09%   |
| Samsung SCX-4200 series               | 28       | 2.98%   |
| HP LaserJet P1102                     | 24       | 2.56%   |
| HP LaserJet 1018                      | 24       | 2.56%   |
| Panasonic (Matsushita) KX-MB1500RU    | 18       | 1.92%   |
| HP LaserJet 1010                      | 17       | 1.81%   |
| HP LaserJet P1005                     | 16       | 1.7%    |
| Samsung SCX-3400 Series               | 15       | 1.6%    |
| Seiko Epson Printer                   | 14       | 1.49%   |
| Canon MF4410                          | 13       | 1.38%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 12       | 1.28%   |
| Samsung SCX-3200 Series               | 12       | 1.28%   |
| HP LaserJet 1320                      | 12       | 1.28%   |
| QinHeng CH340S                        | 11       | 1.17%   |
| Canon MF3010                          | 11       | 1.17%   |
| Samsung M2070 Series                  | 10       | 1.06%   |
| Pantum P2200 series                   | 10       | 1.06%   |
| HP LaserJet 1300                      | 10       | 1.06%   |
| HP LaserJet 1200                      | 10       | 1.06%   |
| Canon MF4010 series                   | 10       | 1.06%   |
| Samsung SCX-4100 Scanner              | 9        | 0.96%   |
| Samsung ML-2010P Mono Laser Printer   | 9        | 0.96%   |
| HP DeskJet 2130 series                | 9        | 0.96%   |
| Canon LBP3010/LBP3018/LBP3050         | 9        | 0.96%   |
| Xerox Phaser 3140 and 3155            | 8        | 0.85%   |
| Samsung ML-216x Series Laser Printer  | 8        | 0.85%   |
| Samsung ML-1640 Series Laser Printer  | 8        | 0.85%   |
| Samsung ML-1210 Printer               | 8        | 0.85%   |
| Pantum M6500 series                   | 8        | 0.85%   |
| HP LaserJet 1022                      | 8        | 0.85%   |
| Canon PIXMA MG2500 Series             | 8        | 0.85%   |
| Canon LBP810                          | 8        | 0.85%   |
| Brother DCP-7057 scanner/printer      | 8        | 0.85%   |
| Xerox WorkCentre 3119 Series          | 7        | 0.75%   |
| Seiko Epson L210 Series               | 7        | 0.75%   |
| HP LaserJet 1000                      | 7        | 0.75%   |
| Canon MG2400 series                   | 7        | 0.75%   |
| Canon LBP6000                         | 7        | 0.75%   |
| Brother HL-2030 Laser Printer         | 7        | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 100      | 37.59%  |
| Seiko Epson                 | 66       | 24.81%  |
| Hewlett-Packard             | 45       | 16.92%  |
| Mustek Systems              | 28       | 10.53%  |
| Acer Peripherals (now BenQ) | 11       | 4.14%   |
| Ultima Electronics          | 10       | 3.76%   |
| KYE Systems (Mouse Systems) | 3        | 1.13%   |
| Avision                     | 2        | 0.75%   |
| Canon Electronics           | 1        | 0.38%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                                                      | 17       | 6.37%   |
| Canon CanoScan LIDE 25                                                                | 17       | 6.37%   |
| Canon CanoScan LiDE 120                                                               | 16       | 5.99%   |
| Canon CanoScan LiDE 110                                                               | 16       | 5.99%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11       | 4.12%   |
| Canon CanoScan LiDE 210                                                               | 11       | 4.12%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 9        | 3.37%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 9        | 3.37%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 8        | 3%      |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 8        | 3%      |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8        | 3%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 7        | 2.62%   |
| Mustek Systems SNAPSCAN e22                                                           | 6        | 2.25%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6        | 2.25%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 5        | 1.87%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 5        | 1.87%   |
| Canon CanoScan LiDE 60                                                                | 5        | 1.87%   |
| Canon CanoScan LiDE 220                                                               | 5        | 1.87%   |
| Canon CanoScan LiDE 100                                                               | 5        | 1.87%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4        | 1.5%    |
| HP ScanJet 3800c                                                                      | 4        | 1.5%    |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4        | 1.5%    |
| Seiko Epson Perfection 660                                                            | 3        | 1.12%   |
| HP ScanJet 3970c                                                                      | 3        | 1.12%   |
| Canon CanoScan LiDE 70                                                                | 3        | 1.12%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3        | 1.12%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 0.75%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2        | 0.75%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2        | 0.75%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2        | 0.75%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 2        | 0.75%   |
| HP ScanJet G4050                                                                      | 2        | 0.75%   |
| HP ScanJet 4300c                                                                      | 2        | 0.75%   |
| HP ScanJet 2300c                                                                      | 2        | 0.75%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 0.75%   |
| Canon CanoScan LiDE 700F                                                              | 2        | 0.75%   |
| Canon CanoScan                                                                        | 2        | 0.75%   |
| Avision iVina FB1600/UMAX Astra 4500                                                  | 2        | 0.75%   |
| Acer Peripherals (now BenQ) Color FlatbedScanner39                                    | 2        | 0.75%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 2        | 0.75%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 748      | 33.48%  |
| Z-Star Microelectronics                | 372      | 16.65%  |
| Microdia                               | 171      | 7.65%   |
| Microsoft                              | 115      | 5.15%   |
| KYE Systems (Mouse Systems)            | 89       | 3.98%   |
| Arkmicro Technologies                  | 73       | 3.27%   |
| GEMBIRD                                | 62       | 2.78%   |
| Aveo Technology                        | 62       | 2.78%   |
| Pixart Imaging                         | 50       | 2.24%   |
| Cubeternet                             | 49       | 2.19%   |
| Chicony Electronics                    | 45       | 2.01%   |
| Creative Technology                    | 42       | 1.88%   |
| Alcor Micro                            | 39       | 1.75%   |
| Realtek Semiconductor                  | 38       | 1.7%    |
| Apple                                  | 29       | 1.3%    |
| Samsung Electronics                    | 22       | 0.98%   |
| Sunplus Innovation Technology          | 20       | 0.9%    |
| Genesys Logic                          | 18       | 0.81%   |
| A4Tech                                 | 17       | 0.76%   |
| Guillemot                              | 13       | 0.58%   |
| Philips (or NXP)                       | 10       | 0.45%   |
| Hewlett-Packard                        | 10       | 0.45%   |
| SunplusIT                              | 8        | 0.36%   |
| SiGma Micro                            | 8        | 0.36%   |
| lihappe8                               | 8        | 0.36%   |
| IMC Networks                           | 8        | 0.36%   |
| Generalplus Technology                 | 8        | 0.36%   |
| AVerMedia Technologies                 | 8        | 0.36%   |
| Trust                                  | 6        | 0.27%   |
| Unknown                                | 4        | 0.18%   |
| Silicon Motion                         | 4        | 0.18%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.18%   |
| Xiaomi                                 | 3        | 0.13%   |
| Suyin                                  | 3        | 0.13%   |
| Sony                                   | 3        | 0.13%   |
| Sonix Technology                       | 3        | 0.13%   |
| Nokia Mobile Phones                    | 3        | 0.13%   |
| MacroSilicon                           | 3        | 0.13%   |
| Jieli Technology                       | 3        | 0.13%   |
| Canon                                  | 3        | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 273      | 12.2%   |
| Z-Star Venus USB2.0 Camera                        | 157      | 7.02%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 108      | 4.83%   |
| Microdia Camera                                   | 107      | 4.78%   |
| Z-Star Vimicro USB Camera (Altair)                | 77       | 3.44%   |
| Arkmicro USB2.0 PC CAMERA                         | 67       | 3%      |
| Logitech Webcam C170                              | 61       | 2.73%   |
| Logitech Webcam C310                              | 59       | 2.64%   |
| Logitech HD Webcam C525                           | 54       | 2.41%   |
| Logitech Webcam C210                              | 47       | 2.1%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 37       | 1.65%   |
| Microsoft LifeCam HD-3000                         | 34       | 1.52%   |
| GEMBIRD USB2.0 PC CAMERA                          | 31       | 1.39%   |
| Logitech HD Pro Webcam C920                       | 30       | 1.34%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 30       | 1.34%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 27       | 1.21%   |
| Alcor Micro USB 2.0 PC Camera                     | 26       | 1.16%   |
| Logitech Webcam C110                              | 24       | 1.07%   |
| Logitech HD Webcam C510                           | 24       | 1.07%   |
| Aveo Camera                                       | 24       | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE                         | 24       | 1.07%   |
| Microsoft LifeCam VX-800                          | 22       | 0.98%   |
| Samsung Galaxy A5 (MTP)                           | 21       | 0.94%   |
| Logitech Logitech Webcam C160                     | 19       | 0.85%   |
| Aveo USB2.0 Camera                                | 19       | 0.85%   |
| Logitech HD Webcam C615                           | 18       | 0.8%    |
| Microdia USB 2.0 Camera                           | 17       | 0.76%   |
| Logitech HD Webcam C910                           | 17       | 0.76%   |
| Realtek Full HD webcam                            | 16       | 0.72%   |
| Z-Star A4 TECH HD PC Camera                       | 15       | 0.67%   |
| Microdia Sonix USB 2.0 Camera                     | 15       | 0.67%   |
| Cubeternet USB2.0 Camera                          | 15       | 0.67%   |
| Aveo UVC camera (Bresser microscope)              | 15       | 0.67%   |
| Microsoft LifeCam VX-2000                         | 14       | 0.63%   |
| Microsoft LifeCam HD-5000                         | 13       | 0.58%   |
| Microsoft LifeCam Cinema                          | 13       | 0.58%   |
| Logitech Logitech Webcam C100                     | 13       | 0.58%   |
| Genesys Logic Camera                              | 12       | 0.54%   |
| Microdia MSI Starcam Racer                        | 11       | 0.49%   |
| Logitech Webcam C250                              | 10       | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 3        | 37.5%   |
| STMicroelectronics    | 2        | 25%     |
| Microsoft             | 2        | 25%     |
| Elan Microelectronics | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader       | 2        | 25%     |
| Microsoft Fingerprint Reader                | 2        | 25%     |
| LighTuning Fingerprint Sensor               | 1        | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor   | 1        | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 12.5%   |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Aktiv                      | 12       | 27.27%  |
| Aladdin Knowledge Systems  | 9        | 20.45%  |
| Aladdin R.D.               | 6        | 13.64%  |
| Athena Smartcard Solutions | 4        | 9.09%   |
| Alcor Micro                | 4        | 9.09%   |
| Advanced Card Systems      | 4        | 9.09%   |
| Yubico.com                 | 2        | 4.55%   |
| OmniKey                    | 1        | 2.27%   |
| Gemalto (was Gemplus)      | 1        | 2.27%   |
| Castles Technology         | 1        | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Aktiv Rutoken lite                               | 12       | 27.27%  |
| Aladdin Knowledge Systems Token JC               | 9        | 20.45%  |
| Aladdin R.D. JaCarta                             | 6        | 13.64%  |
| Athena Smartcard Solutions ASEDrive CCID         | 4        | 9.09%   |
| Alcor Micro Watchdata W 1981                     | 3        | 6.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                  | 2        | 4.55%   |
| OmniKey Smart Card Reader USB                    | 1        | 2.27%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1        | 2.27%   |
| Castles Technology EZCCID Smart Card Reader      | 1        | 2.27%   |
| Alcor Micro AU9540 Smartcard Reader              | 1        | 2.27%   |
| Advanced Card Systems ACR39U                     | 1        | 2.27%   |
| Advanced Card Systems ACR3901U                   | 1        | 2.27%   |
| Advanced Card Systems ACR38 SmartCard Reader     | 1        | 2.27%   |
| Advanced Card Systems ACR1281 1S Dual Reader     | 1        | 2.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 9502     | 81.91%  |
| 1     | 1882     | 16.22%  |
| 2     | 174      | 1.5%    |
| 3     | 25       | 0.22%   |
| 4     | 10       | 0.09%   |
| 6     | 3        | 0.03%   |
| 5     | 2        | 0.02%   |
| 9     | 1        | 0.01%   |
| 7     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1489     | 65.97%  |
| Net/wireless             | 218      | 9.66%   |
| Communication controller | 142      | 6.29%   |
| Unassigned class         | 88       | 3.9%    |
| Multimedia controller    | 66       | 2.92%   |
| Sound                    | 56       | 2.48%   |
| Chipcard                 | 35       | 1.55%   |
| Camera                   | 33       | 1.46%   |
| Net/ethernet             | 23       | 1.02%   |
| Network                  | 19       | 0.84%   |
| Bluetooth                | 18       | 0.8%    |
| Modem                    | 16       | 0.71%   |
| Storage/raid             | 13       | 0.58%   |
| Fingerprint reader       | 8        | 0.35%   |
| Dvb card                 | 8        | 0.35%   |
| Firewire controller      | 6        | 0.27%   |
| Storage/ide              | 5        | 0.22%   |
| Storage/ata              | 5        | 0.22%   |
| Tv card                  | 4        | 0.18%   |
| Storage                  | 2        | 0.09%   |
| Video                    | 1        | 0.04%   |
| Unclassified device      | 1        | 0.04%   |
| Card reader              | 1        | 0.04%   |

