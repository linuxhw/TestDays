BlackPanther - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BlackPanther.

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

Total: 4392

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0HHV7N A00                  | [cd6ba4805b](https://linux-hardware.org/?probe=cd6ba4805b) | Jan 06, 2025 |
| Acer          | Aspire X1470                | [e645634cdf](https://linux-hardware.org/?probe=e645634cdf) | Jan 04, 2025 |
| Acer          | Aspire X1470                | [5546dd82bb](https://linux-hardware.org/?probe=5546dd82bb) | Jan 03, 2025 |
| HP            | 0B4Ch D                     | [bfc09a54d2](https://linux-hardware.org/?probe=bfc09a54d2) | Jan 02, 2025 |
| HP            | 0B4Ch D                     | [1416c7ff2b](https://linux-hardware.org/?probe=1416c7ff2b) | Jan 02, 2025 |
| Lenovo        | 1730-A1G                    | [7b80b5adbb](https://linux-hardware.org/?probe=7b80b5adbb) | Jan 02, 2025 |
| Lenovo        | 1730-A1G                    | [977ee06a31](https://linux-hardware.org/?probe=977ee06a31) | Jan 02, 2025 |
| Dell          | 0JP3NX A01                  | [a320c35e69](https://linux-hardware.org/?probe=a320c35e69) | Jan 02, 2025 |
| Intel         | DG43GT AAE62768-300         | [f33d4be91e](https://linux-hardware.org/?probe=f33d4be91e) | Jan 01, 2025 |
| Intel         | DG43GT AAE62768-300         | [c125d99d72](https://linux-hardware.org/?probe=c125d99d72) | Jan 01, 2025 |
| HP            | 0B4Ch D                     | [f81870b407](https://linux-hardware.org/?probe=f81870b407) | Dec 31, 2024 |
| HP            | 0B4Ch D                     | [3aa4052845](https://linux-hardware.org/?probe=3aa4052845) | Dec 31, 2024 |
| ASUSTek       | PRIME B365M-A               | [cc640facba](https://linux-hardware.org/?probe=cc640facba) | Dec 28, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [b702a2759f](https://linux-hardware.org/?probe=b702a2759f) | Dec 28, 2024 |
| Gigabyte      | 945GCM-S2L                  | [9ad1def3b0](https://linux-hardware.org/?probe=9ad1def3b0) | Dec 27, 2024 |
| Gigabyte      | 945GCM-S2L                  | [28f2ce4fde](https://linux-hardware.org/?probe=28f2ce4fde) | Dec 26, 2024 |
| Lenovo        | 1730-A1G                    | [bb3794b32b](https://linux-hardware.org/?probe=bb3794b32b) | Dec 23, 2024 |
| Gigabyte      | B75M-D3H                    | [1bb966cb7d](https://linux-hardware.org/?probe=1bb966cb7d) | Dec 21, 2024 |
| HP            | 3397                        | [800fd186e6](https://linux-hardware.org/?probe=800fd186e6) | Dec 16, 2024 |
| HP            | 3397                        | [0bfc475fe7](https://linux-hardware.org/?probe=0bfc475fe7) | Dec 16, 2024 |
| Gigabyte      | H61M-S1                     | [0291930ebb](https://linux-hardware.org/?probe=0291930ebb) | Dec 16, 2024 |
| Gigabyte      | F2A68HM-DS2                 | [af28ef87b7](https://linux-hardware.org/?probe=af28ef87b7) | Dec 15, 2024 |
| ASRock        | 4X4-V1000                   | [6a76a8988e](https://linux-hardware.org/?probe=6a76a8988e) | Dec 15, 2024 |
| Foxconn       | 2ABF                        | [6aa0202528](https://linux-hardware.org/?probe=6aa0202528) | Dec 14, 2024 |
| Foxconn       | 2ABF                        | [7372c37954](https://linux-hardware.org/?probe=7372c37954) | Dec 14, 2024 |
| ASRock        | 4X4-V1000                   | [1741e70741](https://linux-hardware.org/?probe=1741e70741) | Dec 14, 2024 |
| HP            | 3646h                       | [bec40b8a76](https://linux-hardware.org/?probe=bec40b8a76) | Dec 14, 2024 |
| Dell          | 0JP3NX A01                  | [14849f1285](https://linux-hardware.org/?probe=14849f1285) | Dec 14, 2024 |
| HP            | 3646h                       | [6aba49858b](https://linux-hardware.org/?probe=6aba49858b) | Dec 13, 2024 |
| ASRock        | A55M-HVS                    | [6ec5d183ad](https://linux-hardware.org/?probe=6ec5d183ad) | Dec 13, 2024 |
| ASRock        | A55M-HVS                    | [a88f44e9e4](https://linux-hardware.org/?probe=a88f44e9e4) | Dec 13, 2024 |
| Gigabyte      | G41M-Combo                  | [be12e82a19](https://linux-hardware.org/?probe=be12e82a19) | Dec 12, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [76eb88a8bd](https://linux-hardware.org/?probe=76eb88a8bd) | Dec 11, 2024 |
| Gigabyte      | H310M A-CF x.x              | [3f0128ce11](https://linux-hardware.org/?probe=3f0128ce11) | Dec 10, 2024 |
| Gigabyte      | H310M A-CF x.x              | [4e9d94f35e](https://linux-hardware.org/?probe=4e9d94f35e) | Dec 10, 2024 |
| MSI           | MS-7817                     | [f1e7840d6b](https://linux-hardware.org/?probe=f1e7840d6b) | Dec 10, 2024 |
| MSI           | MS-7817                     | [5311b73ce0](https://linux-hardware.org/?probe=5311b73ce0) | Dec 10, 2024 |
| ASRock        | 960GM-VGS3 FX               | [1302e07a62](https://linux-hardware.org/?probe=1302e07a62) | Dec 09, 2024 |
| ASRock        | 960GM-VGS3 FX               | [15e8e8f4f8](https://linux-hardware.org/?probe=15e8e8f4f8) | Dec 09, 2024 |
| Gigabyte      | B450M GAMING                | [cbf3a10efc](https://linux-hardware.org/?probe=cbf3a10efc) | Dec 08, 2024 |
| Gigabyte      | H310M A-CF x.x              | [491aa7568e](https://linux-hardware.org/?probe=491aa7568e) | Dec 08, 2024 |
| Lenovo        | 1730-A1G                    | [8437ab0ca5](https://linux-hardware.org/?probe=8437ab0ca5) | Dec 08, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [f8b62a20e3](https://linux-hardware.org/?probe=f8b62a20e3) | Dec 08, 2024 |
| Dell          | 0D883F A06                  | [99948b5b1e](https://linux-hardware.org/?probe=99948b5b1e) | Dec 08, 2024 |
| Dell          | 0D883F A06                  | [c5f9a7eb19](https://linux-hardware.org/?probe=c5f9a7eb19) | Dec 08, 2024 |
| HP            | 0B4Ch D                     | [e19a27372d](https://linux-hardware.org/?probe=e19a27372d) | Dec 07, 2024 |
| ASUSTek       | P8Z77-V LX                  | [56c6e2da15](https://linux-hardware.org/?probe=56c6e2da15) | Dec 07, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [635d67c028](https://linux-hardware.org/?probe=635d67c028) | Dec 07, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [58fc88417b](https://linux-hardware.org/?probe=58fc88417b) | Dec 04, 2024 |
| ASRock        | B85M Pro4                   | [87cc2b801a](https://linux-hardware.org/?probe=87cc2b801a) | Dec 02, 2024 |
| ASRock        | B85M Pro4                   | [6c15da3e1f](https://linux-hardware.org/?probe=6c15da3e1f) | Dec 02, 2024 |
| ASRock        | X299 Extreme4               | [d1ff3afc94](https://linux-hardware.org/?probe=d1ff3afc94) | Dec 02, 2024 |
| Gigabyte      | B450M GAMING                | [b22b8236a5](https://linux-hardware.org/?probe=b22b8236a5) | Dec 02, 2024 |
| HP            | 3646h                       | [adf6e6dfea](https://linux-hardware.org/?probe=adf6e6dfea) | Dec 01, 2024 |
| HP            | 0B4Ch D                     | [816487e244](https://linux-hardware.org/?probe=816487e244) | Dec 01, 2024 |
| Gigabyte      | H61M-S1                     | [d4ffafd2f5](https://linux-hardware.org/?probe=d4ffafd2f5) | Nov 29, 2024 |
| ASUSTek       | PRIME A320M-R               | [f8273a878e](https://linux-hardware.org/?probe=f8273a878e) | Nov 29, 2024 |
| Gigabyte      | F2A68HM-DS2                 | [5a1f3f02f5](https://linux-hardware.org/?probe=5a1f3f02f5) | Nov 28, 2024 |
| ASRock        | X299 Extreme4               | [ebfb054460](https://linux-hardware.org/?probe=ebfb054460) | Nov 28, 2024 |
| HP            | 805D                        | [9ddf70c273](https://linux-hardware.org/?probe=9ddf70c273) | Nov 26, 2024 |
| ASUSTek       | Maximus VIII HERO           | [f0eddec4ed](https://linux-hardware.org/?probe=f0eddec4ed) | Nov 26, 2024 |
| ASUSTek       | PRIME B365M-A               | [c83451790b](https://linux-hardware.org/?probe=c83451790b) | Nov 26, 2024 |
| HP            | 805D                        | [bcb3dfcc19](https://linux-hardware.org/?probe=bcb3dfcc19) | Nov 26, 2024 |
| Dell          | 0T7D40 A01                  | [3597056176](https://linux-hardware.org/?probe=3597056176) | Nov 26, 2024 |
| Dell          | 0T7D40 A01                  | [ab3c886551](https://linux-hardware.org/?probe=ab3c886551) | Nov 26, 2024 |
| ASUSTek       | Maximus VIII HERO           | [64d558663e](https://linux-hardware.org/?probe=64d558663e) | Nov 25, 2024 |
| ASRock        | B550M Pro4                  | [97763a7a84](https://linux-hardware.org/?probe=97763a7a84) | Nov 24, 2024 |
| ASRock        | B550M Pro4                  | [375c90560b](https://linux-hardware.org/?probe=375c90560b) | Nov 24, 2024 |
| ASUSTek       | P8Z77-V LX                  | [b04b80b8c1](https://linux-hardware.org/?probe=b04b80b8c1) | Nov 24, 2024 |
| Gigabyte      | G41M-Combo                  | [e719982d13](https://linux-hardware.org/?probe=e719982d13) | Nov 23, 2024 |
| Gigabyte      | G41M-Combo                  | [fe480aafdc](https://linux-hardware.org/?probe=fe480aafdc) | Nov 23, 2024 |
| Gigabyte      | H61M-S1                     | [1490996600](https://linux-hardware.org/?probe=1490996600) | Nov 21, 2024 |
| ASRock        | N68C-S UCC                  | [24b5436040](https://linux-hardware.org/?probe=24b5436040) | Nov 21, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b0aea64800](https://linux-hardware.org/?probe=b0aea64800) | Nov 18, 2024 |
| ASUSTek       | P5G41-M SI/DVI              | [2c4a36ab8f](https://linux-hardware.org/?probe=2c4a36ab8f) | Nov 17, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [acd9211269](https://linux-hardware.org/?probe=acd9211269) | Nov 16, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [8e9b066c80](https://linux-hardware.org/?probe=8e9b066c80) | Nov 16, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [0c95c596cd](https://linux-hardware.org/?probe=0c95c596cd) | Nov 16, 2024 |
| Gigabyte      | H61M-S1                     | [ed13d9f493](https://linux-hardware.org/?probe=ed13d9f493) | Nov 12, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [cc7ab8446b](https://linux-hardware.org/?probe=cc7ab8446b) | Nov 10, 2024 |
| Gigabyte      | H310M A-CF x.x              | [64ef79648d](https://linux-hardware.org/?probe=64ef79648d) | Nov 09, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [3da6bd30af](https://linux-hardware.org/?probe=3da6bd30af) | Nov 07, 2024 |
| HP            | 18E5                        | [b4c19621ca](https://linux-hardware.org/?probe=b4c19621ca) | Nov 04, 2024 |
| Dell          | 0D883F A06                  | [a55fa3f5de](https://linux-hardware.org/?probe=a55fa3f5de) | Nov 03, 2024 |
| ASRock        | 4X4-V1000                   | [e4f92f939d](https://linux-hardware.org/?probe=e4f92f939d) | Nov 03, 2024 |
| Dell          | 0D883F A06                  | [ba2871b501](https://linux-hardware.org/?probe=ba2871b501) | Nov 03, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [3e0226aec6](https://linux-hardware.org/?probe=3e0226aec6) | Nov 03, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [c2cf996702](https://linux-hardware.org/?probe=c2cf996702) | Nov 03, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [5ff13f15c9](https://linux-hardware.org/?probe=5ff13f15c9) | Nov 02, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [327a5ec885](https://linux-hardware.org/?probe=327a5ec885) | Nov 01, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [b1bb7ebff5](https://linux-hardware.org/?probe=b1bb7ebff5) | Oct 31, 2024 |
| Medion        | MS-7748                     | [dda2d79844](https://linux-hardware.org/?probe=dda2d79844) | Oct 31, 2024 |
| Dell          | 0KH290                      | [1a0ac895ae](https://linux-hardware.org/?probe=1a0ac895ae) | Oct 31, 2024 |
| MSI           | MS-7817                     | [bed68b38eb](https://linux-hardware.org/?probe=bed68b38eb) | Oct 30, 2024 |
| PCWare        | IPX847P1                    | [fc7aeb019e](https://linux-hardware.org/?probe=fc7aeb019e) | Oct 30, 2024 |
| Shuttle       | FH110                       | [c55fa883e2](https://linux-hardware.org/?probe=c55fa883e2) | Oct 28, 2024 |
| Gigabyte      | H61M-S1                     | [0d7062b12c](https://linux-hardware.org/?probe=0d7062b12c) | Oct 26, 2024 |
| ASUSTek       | PRIME A320M-R               | [23a4fd4923](https://linux-hardware.org/?probe=23a4fd4923) | Oct 25, 2024 |
| ASUSTek       | H110M-A                     | [be07c84e95](https://linux-hardware.org/?probe=be07c84e95) | Oct 25, 2024 |
| MSI           | MS-7817                     | [9023f6d41b](https://linux-hardware.org/?probe=9023f6d41b) | Oct 24, 2024 |
| Gigabyte      | B450M GAMING                | [1cbb55fdfd](https://linux-hardware.org/?probe=1cbb55fdfd) | Oct 24, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [335bfff363](https://linux-hardware.org/?probe=335bfff363) | Oct 24, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [284f072af5](https://linux-hardware.org/?probe=284f072af5) | Oct 23, 2024 |
| Lenovo        | 1036 NO DPK                 | [c2bde2f6b0](https://linux-hardware.org/?probe=c2bde2f6b0) | Oct 23, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [f843af5859](https://linux-hardware.org/?probe=f843af5859) | Oct 23, 2024 |
| Lenovo        | 1036 NO DPK                 | [e1a69d185b](https://linux-hardware.org/?probe=e1a69d185b) | Oct 23, 2024 |
| Dell          | 0R230R A00                  | [d5a47b1f8f](https://linux-hardware.org/?probe=d5a47b1f8f) | Oct 22, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2cbcb598ea](https://linux-hardware.org/?probe=2cbcb598ea) | Oct 22, 2024 |
| Gigabyte      | P61-USB3-B3                 | [9a83f9e71c](https://linux-hardware.org/?probe=9a83f9e71c) | Oct 22, 2024 |
| MSI           | FM2-A55M-E33                | [2ae0dae8a2](https://linux-hardware.org/?probe=2ae0dae8a2) | Oct 22, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a52ed881b1](https://linux-hardware.org/?probe=a52ed881b1) | Oct 22, 2024 |
| Lenovo        | SHARKBAY NOK                | [b3e5c587ea](https://linux-hardware.org/?probe=b3e5c587ea) | Oct 22, 2024 |
| ASRock        | N68C-S UCC                  | [d7c2f9e86c](https://linux-hardware.org/?probe=d7c2f9e86c) | Oct 22, 2024 |
| ASRock        | 4X4-V1000                   | [4a5d9de5de](https://linux-hardware.org/?probe=4a5d9de5de) | Oct 22, 2024 |
| ASUSTek       | B85M-E/DASH                 | [2ec1f53712](https://linux-hardware.org/?probe=2ec1f53712) | Oct 22, 2024 |
| ASUSTek       | H110M-A                     | [5f2472aaa7](https://linux-hardware.org/?probe=5f2472aaa7) | Oct 21, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [1152be8474](https://linux-hardware.org/?probe=1152be8474) | Oct 21, 2024 |
| Gigabyte      | H61M-S2PV                   | [2478c2ee64](https://linux-hardware.org/?probe=2478c2ee64) | Oct 20, 2024 |
| ASUSTek       | M2N-E                       | [3a2762bede](https://linux-hardware.org/?probe=3a2762bede) | Oct 18, 2024 |
| ASUSTek       | M2N-E                       | [0588174384](https://linux-hardware.org/?probe=0588174384) | Oct 18, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [5a267f0d63](https://linux-hardware.org/?probe=5a267f0d63) | Oct 13, 2024 |
| Gigabyte      | H310M A-CF x.x              | [874bef7155](https://linux-hardware.org/?probe=874bef7155) | Oct 12, 2024 |
| HP            | 1497                        | [9748a78c93](https://linux-hardware.org/?probe=9748a78c93) | Oct 11, 2024 |
| HP            | 1497                        | [bbe179ab22](https://linux-hardware.org/?probe=bbe179ab22) | Oct 10, 2024 |
| MSI           | MS-7817                     | [2c83298254](https://linux-hardware.org/?probe=2c83298254) | Oct 10, 2024 |
| Gigabyte      | H61M-S1                     | [1e54eccb05](https://linux-hardware.org/?probe=1e54eccb05) | Oct 10, 2024 |
| Lenovo        | MAHOBAY                     | [76652c9013](https://linux-hardware.org/?probe=76652c9013) | Oct 06, 2024 |
| ASUSTek       | H81I-PLUS                   | [ed26135201](https://linux-hardware.org/?probe=ed26135201) | Oct 06, 2024 |
| ASUSTek       | H81I-PLUS                   | [19591661c5](https://linux-hardware.org/?probe=19591661c5) | Oct 06, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [0d9d1e3143](https://linux-hardware.org/?probe=0d9d1e3143) | Oct 02, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [98c54c08cb](https://linux-hardware.org/?probe=98c54c08cb) | Oct 02, 2024 |
| MSI           | MS-B0A21                    | [dbda14b87c](https://linux-hardware.org/?probe=dbda14b87c) | Oct 01, 2024 |
| Dell          | 0JP3NX A01                  | [cd26982f25](https://linux-hardware.org/?probe=cd26982f25) | Oct 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [685b56cfb0](https://linux-hardware.org/?probe=685b56cfb0) | Sep 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [36245021f3](https://linux-hardware.org/?probe=36245021f3) | Sep 29, 2024 |
| ASUSTek       | P5Q-PRO                     | [ef27e1122b](https://linux-hardware.org/?probe=ef27e1122b) | Sep 28, 2024 |
| ASUSTek       | PRIME A320M-R               | [6698bffa60](https://linux-hardware.org/?probe=6698bffa60) | Sep 28, 2024 |
| ASRock        | 4X4-V1000                   | [163d361d29](https://linux-hardware.org/?probe=163d361d29) | Sep 24, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [c319a8c95e](https://linux-hardware.org/?probe=c319a8c95e) | Sep 23, 2024 |
| Gigabyte      | H310M A-CF x.x              | [bfbc14e927](https://linux-hardware.org/?probe=bfbc14e927) | Sep 23, 2024 |
| Gigabyte      | H310M A-CF x.x              | [004b08ef53](https://linux-hardware.org/?probe=004b08ef53) | Sep 23, 2024 |
| Gigabyte      | EP31-DS3L                   | [38afdbcca5](https://linux-hardware.org/?probe=38afdbcca5) | Sep 21, 2024 |
| ASRock        | J3455-ITX                   | [e8f83c57ae](https://linux-hardware.org/?probe=e8f83c57ae) | Sep 20, 2024 |
| Gigabyte      | H61M-S2PV                   | [26211343c9](https://linux-hardware.org/?probe=26211343c9) | Sep 19, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [22bb07fac9](https://linux-hardware.org/?probe=22bb07fac9) | Sep 18, 2024 |
| HP            | 3031h                       | [063670bea1](https://linux-hardware.org/?probe=063670bea1) | Sep 17, 2024 |
| HP            | 3031h                       | [1da91bca9f](https://linux-hardware.org/?probe=1da91bca9f) | Sep 17, 2024 |
| Gigabyte      | Z390 UD                     | [87365dacf6](https://linux-hardware.org/?probe=87365dacf6) | Sep 16, 2024 |
| ASRock        | 4X4-V1000                   | [a422d276cb](https://linux-hardware.org/?probe=a422d276cb) | Sep 16, 2024 |
| HP            | 3646h                       | [3e05367f15](https://linux-hardware.org/?probe=3e05367f15) | Sep 15, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [f3761f99d3](https://linux-hardware.org/?probe=f3761f99d3) | Sep 14, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [367544541b](https://linux-hardware.org/?probe=367544541b) | Sep 13, 2024 |
| Dell          | 0JP3NX A01                  | [8678ecc8af](https://linux-hardware.org/?probe=8678ecc8af) | Sep 13, 2024 |
| Gigabyte      | H61M-S1                     | [0b2a56e1e2](https://linux-hardware.org/?probe=0b2a56e1e2) | Sep 12, 2024 |
| Medion        | MS-7748                     | [310b00a3a5](https://linux-hardware.org/?probe=310b00a3a5) | Sep 10, 2024 |
| Dell          | 0D883F A06                  | [73ba45c13d](https://linux-hardware.org/?probe=73ba45c13d) | Sep 09, 2024 |
| Dell          | 0D883F A06                  | [5cb6d4941a](https://linux-hardware.org/?probe=5cb6d4941a) | Sep 09, 2024 |
| HP            | 3646h                       | [e1f13881e0](https://linux-hardware.org/?probe=e1f13881e0) | Sep 08, 2024 |
| Acer          | Aspire M1930                | [6935bec83d](https://linux-hardware.org/?probe=6935bec83d) | Sep 07, 2024 |
| Acer          | Aspire M1930                | [02eaf44b15](https://linux-hardware.org/?probe=02eaf44b15) | Sep 07, 2024 |
| ASUSTek       | PRIME B365M-A               | [e2f1e583a8](https://linux-hardware.org/?probe=e2f1e583a8) | Sep 06, 2024 |
| ASUSTek       | PRIME B365M-A               | [01e21e3a94](https://linux-hardware.org/?probe=01e21e3a94) | Sep 06, 2024 |
| ASRock        | 4X4-V1000                   | [c4df548274](https://linux-hardware.org/?probe=c4df548274) | Sep 05, 2024 |
| ASUSTek       | P5G41T-M LX                 | [f3a12a1000](https://linux-hardware.org/?probe=f3a12a1000) | Sep 05, 2024 |
| ASUSTek       | P5G41T-M LX                 | [b6f76ce650](https://linux-hardware.org/?probe=b6f76ce650) | Sep 05, 2024 |
| Gigabyte      | H310M A-CF x.x              | [f058e0e121](https://linux-hardware.org/?probe=f058e0e121) | Sep 05, 2024 |
| ASRock        | 4X4-V1000                   | [7b2170f9e6](https://linux-hardware.org/?probe=7b2170f9e6) | Sep 04, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [1f0d247a7d](https://linux-hardware.org/?probe=1f0d247a7d) | Sep 03, 2024 |
| ASRock        | G41MH/USB3                  | [e076faa995](https://linux-hardware.org/?probe=e076faa995) | Sep 01, 2024 |
| ASRock        | G41MH/USB3                  | [56ac103f26](https://linux-hardware.org/?probe=56ac103f26) | Sep 01, 2024 |
| Dell          | 0M5DCD A00                  | [674bfb55d7](https://linux-hardware.org/?probe=674bfb55d7) | Sep 01, 2024 |
| Dell          | 0M5DCD A00                  | [485e76f95f](https://linux-hardware.org/?probe=485e76f95f) | Aug 31, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [e6a913ae8d](https://linux-hardware.org/?probe=e6a913ae8d) | Aug 31, 2024 |
| HP            | 3646h                       | [ff20575292](https://linux-hardware.org/?probe=ff20575292) | Aug 30, 2024 |
| Lenovo        | MAHOBAY                     | [066219d111](https://linux-hardware.org/?probe=066219d111) | Aug 30, 2024 |
| HP            | 0B4Ch D                     | [63640e2f86](https://linux-hardware.org/?probe=63640e2f86) | Aug 29, 2024 |
| HP            | 0B4Ch D                     | [6627c51273](https://linux-hardware.org/?probe=6627c51273) | Aug 29, 2024 |
| Intel         | DG43GT AAE62768-300         | [83220ccc0e](https://linux-hardware.org/?probe=83220ccc0e) | Aug 28, 2024 |
| Intel         | DG43GT AAE62768-300         | [10741a1de9](https://linux-hardware.org/?probe=10741a1de9) | Aug 28, 2024 |
| Lenovo        | MAHOBAY                     | [e222263171](https://linux-hardware.org/?probe=e222263171) | Aug 25, 2024 |
| ASRock        | B450M Pro4-F                | [d7523db401](https://linux-hardware.org/?probe=d7523db401) | Aug 25, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [8f2d2876e1](https://linux-hardware.org/?probe=8f2d2876e1) | Aug 22, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [5862cffd7e](https://linux-hardware.org/?probe=5862cffd7e) | Aug 20, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [7dc83a52f8](https://linux-hardware.org/?probe=7dc83a52f8) | Aug 20, 2024 |
| Gigabyte      | H310M A-CF x.x              | [a509a63974](https://linux-hardware.org/?probe=a509a63974) | Aug 17, 2024 |
| Dell          | 0D883F A06                  | [8d7853301d](https://linux-hardware.org/?probe=8d7853301d) | Aug 17, 2024 |
| Dell          | 0D883F A06                  | [b84658a951](https://linux-hardware.org/?probe=b84658a951) | Aug 17, 2024 |
| ASUSTek       | P5G41-M SI/DVI              | [ff689261f9](https://linux-hardware.org/?probe=ff689261f9) | Aug 16, 2024 |
| ASUSTek       | P5G41-M SI/DVI              | [1c2ac5e49e](https://linux-hardware.org/?probe=1c2ac5e49e) | Aug 16, 2024 |
| Gigabyte      | H61M-S2PV                   | [5031301c61](https://linux-hardware.org/?probe=5031301c61) | Aug 16, 2024 |
| MSI           | FM2-A55M-E33                | [9b747e3bd4](https://linux-hardware.org/?probe=9b747e3bd4) | Aug 15, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [36ab79a347](https://linux-hardware.org/?probe=36ab79a347) | Aug 15, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [21899d80a8](https://linux-hardware.org/?probe=21899d80a8) | Aug 14, 2024 |
| ASUSTek       | P5G41-M SI/DVI              | [15e1dbbe91](https://linux-hardware.org/?probe=15e1dbbe91) | Aug 13, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [ea097380f7](https://linux-hardware.org/?probe=ea097380f7) | Aug 12, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [4533fe6d88](https://linux-hardware.org/?probe=4533fe6d88) | Aug 12, 2024 |
| ASRock        | 4X4-V1000                   | [014cfd3666](https://linux-hardware.org/?probe=014cfd3666) | Aug 09, 2024 |
| HP            | 0B4Ch D                     | [ca1b71e2ae](https://linux-hardware.org/?probe=ca1b71e2ae) | Aug 08, 2024 |
| Gigabyte      | P61-USB3-B3                 | [963ce2ad8d](https://linux-hardware.org/?probe=963ce2ad8d) | Aug 08, 2024 |
| ASRock        | 4X4-V1000                   | [fe9749295b](https://linux-hardware.org/?probe=fe9749295b) | Aug 08, 2024 |
| Gigabyte      | H61M-S2PV                   | [07e6b8c1c4](https://linux-hardware.org/?probe=07e6b8c1c4) | Aug 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [3f906cffbc](https://linux-hardware.org/?probe=3f906cffbc) | Aug 07, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [c7d8ac8e22](https://linux-hardware.org/?probe=c7d8ac8e22) | Aug 06, 2024 |
| Gigabyte      | H310M A-CF x.x              | [84df7b298d](https://linux-hardware.org/?probe=84df7b298d) | Aug 06, 2024 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [bd390404f2](https://linux-hardware.org/?probe=bd390404f2) | Aug 03, 2024 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [fde8e6244f](https://linux-hardware.org/?probe=fde8e6244f) | Aug 03, 2024 |
| Shuttle       | FH110                       | [056120fbd0](https://linux-hardware.org/?probe=056120fbd0) | Aug 02, 2024 |
| Shuttle       | FH110                       | [286239ff53](https://linux-hardware.org/?probe=286239ff53) | Aug 02, 2024 |
| Gigabyte      | H110M-S2V-CF                | [bf3790e50b](https://linux-hardware.org/?probe=bf3790e50b) | Jul 27, 2024 |
| Gigabyte      | H110M-S2V-CF                | [a2bfeb3927](https://linux-hardware.org/?probe=a2bfeb3927) | Jul 27, 2024 |
| Lenovo        | 1730-A1G                    | [2f9748fa6a](https://linux-hardware.org/?probe=2f9748fa6a) | Jul 27, 2024 |
| Lenovo        | 1730-A1G                    | [0237f8e4da](https://linux-hardware.org/?probe=0237f8e4da) | Jul 27, 2024 |
| Lenovo        | SHARKBAY NOK                | [276d7e9e8c](https://linux-hardware.org/?probe=276d7e9e8c) | Jul 26, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [eeeeadfde6](https://linux-hardware.org/?probe=eeeeadfde6) | Jul 25, 2024 |
| ASRock        | G41MH/USB3                  | [81bc78887c](https://linux-hardware.org/?probe=81bc78887c) | Jul 25, 2024 |
| ASRock        | G41MH/USB3                  | [3564068156](https://linux-hardware.org/?probe=3564068156) | Jul 25, 2024 |
| ASRock        | Z370 Extreme4               | [03c9d6db28](https://linux-hardware.org/?probe=03c9d6db28) | Jul 25, 2024 |
| ASRock        | Z370 Extreme4               | [c375bf45c1](https://linux-hardware.org/?probe=c375bf45c1) | Jul 25, 2024 |
| ASRock        | Z390 Pro4                   | [cf1805eb68](https://linux-hardware.org/?probe=cf1805eb68) | Jul 25, 2024 |
| ASUSTek       | Maximus VIII HERO           | [bb4dba4fee](https://linux-hardware.org/?probe=bb4dba4fee) | Jul 24, 2024 |
| Medion        | MS-7748                     | [64469c14f6](https://linux-hardware.org/?probe=64469c14f6) | Jul 23, 2024 |
| Medion        | MS-7748                     | [5f9ec92f54](https://linux-hardware.org/?probe=5f9ec92f54) | Jul 22, 2024 |
| ASUSTek       | PRIME A320M-R               | [e946cc82cc](https://linux-hardware.org/?probe=e946cc82cc) | Jul 21, 2024 |
| Dell          | 0M5DCD A00                  | [05a6b7317f](https://linux-hardware.org/?probe=05a6b7317f) | Jul 20, 2024 |
| Dell          | 0M5DCD A00                  | [6d9c28f0f3](https://linux-hardware.org/?probe=6d9c28f0f3) | Jul 20, 2024 |
| ASUSTek       | H110M-A                     | [0841a1a981](https://linux-hardware.org/?probe=0841a1a981) | Jul 18, 2024 |
| Gigabyte      | B450M GAMING                | [bfba7e752e](https://linux-hardware.org/?probe=bfba7e752e) | Jul 18, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [c2451127ea](https://linux-hardware.org/?probe=c2451127ea) | Jul 18, 2024 |
| Lenovo        | 1036 NO DPK                 | [c9eea3ddc0](https://linux-hardware.org/?probe=c9eea3ddc0) | Jul 18, 2024 |
| HP            | 339A                        | [62ee692b26](https://linux-hardware.org/?probe=62ee692b26) | Jul 18, 2024 |
| Foxconn       | 2ABF                        | [ad83a2a53b](https://linux-hardware.org/?probe=ad83a2a53b) | Jul 17, 2024 |
| Lenovo        | 1036 NO DPK                 | [f98bb7f8f0](https://linux-hardware.org/?probe=f98bb7f8f0) | Jul 17, 2024 |
| ASRock        | B550M Pro4                  | [ff45603528](https://linux-hardware.org/?probe=ff45603528) | Jul 17, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [fbd77590c6](https://linux-hardware.org/?probe=fbd77590c6) | Jul 16, 2024 |
| Lenovo        | SHARKBAY NOK                | [177bf6432a](https://linux-hardware.org/?probe=177bf6432a) | Jul 15, 2024 |
| MSI           | H61M-P21                    | [34fbdae75b](https://linux-hardware.org/?probe=34fbdae75b) | Jul 15, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [3a1a09b9ff](https://linux-hardware.org/?probe=3a1a09b9ff) | Jul 14, 2024 |
| ASUSTek       | B85M-E/DASH                 | [3f337466df](https://linux-hardware.org/?probe=3f337466df) | Jul 13, 2024 |
| HP            | 304Ah                       | [1c2dc5a535](https://linux-hardware.org/?probe=1c2dc5a535) | Jul 12, 2024 |
| Gigabyte      | H310M A-CF x.x              | [9694054fa1](https://linux-hardware.org/?probe=9694054fa1) | Jul 11, 2024 |
| Gigabyte      | B450M GAMING                | [a2d2862d77](https://linux-hardware.org/?probe=a2d2862d77) | Jul 10, 2024 |
| ASUSTek       | PRIME A320M-R               | [37f9d6aecb](https://linux-hardware.org/?probe=37f9d6aecb) | Jul 10, 2024 |
| Foxconn       | 2ABF                        | [f6d887e1d1](https://linux-hardware.org/?probe=f6d887e1d1) | Jul 10, 2024 |
| ASUSTek       | H110M-A                     | [8ac167f783](https://linux-hardware.org/?probe=8ac167f783) | Jul 08, 2024 |
| HP            | 304Ah                       | [4ee01b67ba](https://linux-hardware.org/?probe=4ee01b67ba) | Jul 08, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [5f824e560e](https://linux-hardware.org/?probe=5f824e560e) | Jul 08, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [0d418fcb80](https://linux-hardware.org/?probe=0d418fcb80) | Jul 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [894b8e0662](https://linux-hardware.org/?probe=894b8e0662) | Jul 08, 2024 |
| ASUSTek       | Maximus VIII HERO           | [dac3a8c694](https://linux-hardware.org/?probe=dac3a8c694) | Jul 07, 2024 |
| ASRock        | B550M Pro4                  | [c09c17083f](https://linux-hardware.org/?probe=c09c17083f) | Jul 07, 2024 |
| ASUSTek       | Maximus VIII HERO           | [d6fd5fc900](https://linux-hardware.org/?probe=d6fd5fc900) | Jul 07, 2024 |
| ASUSTek       | Maximus VIII HERO           | [ed373b0ad2](https://linux-hardware.org/?probe=ed373b0ad2) | Jul 07, 2024 |
| Gigabyte      | B450M GAMING                | [9317b3e84d](https://linux-hardware.org/?probe=9317b3e84d) | Jul 06, 2024 |
| HP            | 304Ah                       | [7e5c30dfa7](https://linux-hardware.org/?probe=7e5c30dfa7) | Jul 06, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ffd23edb63](https://linux-hardware.org/?probe=ffd23edb63) | Jul 06, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [241bc8c16f](https://linux-hardware.org/?probe=241bc8c16f) | Jul 06, 2024 |
| ASUSTek       | H110M-A                     | [e1f03f7315](https://linux-hardware.org/?probe=e1f03f7315) | Jul 05, 2024 |
| ASUSTek       | B85M-E/DASH                 | [e5d5d9bd26](https://linux-hardware.org/?probe=e5d5d9bd26) | Jul 05, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [51393e3078](https://linux-hardware.org/?probe=51393e3078) | Jul 05, 2024 |
| HP            | 304Ah                       | [2e4778cef9](https://linux-hardware.org/?probe=2e4778cef9) | Jul 05, 2024 |
| Gigabyte      | P61-USB3-B3                 | [e33c41ab47](https://linux-hardware.org/?probe=e33c41ab47) | Jul 05, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [94c565fdd8](https://linux-hardware.org/?probe=94c565fdd8) | Jul 04, 2024 |
| Lenovo        | 1036 NO DPK                 | [bb1959d7ec](https://linux-hardware.org/?probe=bb1959d7ec) | Jul 04, 2024 |
| Dell          | 0KH290                      | [5bb79e98fc](https://linux-hardware.org/?probe=5bb79e98fc) | Jul 04, 2024 |
| Medion        | MS-7748                     | [3e1a512e70](https://linux-hardware.org/?probe=3e1a512e70) | Jul 04, 2024 |
| Gigabyte      | H310M A-CF x.x              | [da88e89b8a](https://linux-hardware.org/?probe=da88e89b8a) | Jul 03, 2024 |
| Lenovo        | SHARKBAY NOK                | [bea51624aa](https://linux-hardware.org/?probe=bea51624aa) | Jul 03, 2024 |
| Dell          | 0D6H9T A01                  | [ecaf2d712b](https://linux-hardware.org/?probe=ecaf2d712b) | Jul 03, 2024 |
| ASUSTek       | PRIME A320M-R               | [3281acef4d](https://linux-hardware.org/?probe=3281acef4d) | Jul 02, 2024 |
| Gigabyte      | F2A68HM-H                   | [e4bf80206c](https://linux-hardware.org/?probe=e4bf80206c) | Jul 02, 2024 |
| Lenovo        | SHARKBAY NOK                | [7055960e2f](https://linux-hardware.org/?probe=7055960e2f) | Jun 30, 2024 |
| Dell          | 0KH290                      | [22c6478289](https://linux-hardware.org/?probe=22c6478289) | Jun 30, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [57f9fb8233](https://linux-hardware.org/?probe=57f9fb8233) | Jun 29, 2024 |
| Dell          | 0M5DCD A00                  | [a7c1176c97](https://linux-hardware.org/?probe=a7c1176c97) | Jun 29, 2024 |
| Lenovo        | 1730-A1G                    | [e59e681f5f](https://linux-hardware.org/?probe=e59e681f5f) | Jun 29, 2024 |
| Lenovo        | 1730-A1G                    | [b9f00b08d6](https://linux-hardware.org/?probe=b9f00b08d6) | Jun 29, 2024 |
| Gigabyte      | H61M-S1                     | [6c5dbc9da0](https://linux-hardware.org/?probe=6c5dbc9da0) | Jun 29, 2024 |
| Dell          | 0M5DCD A00                  | [4469e32777](https://linux-hardware.org/?probe=4469e32777) | Jun 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [2825c82b88](https://linux-hardware.org/?probe=2825c82b88) | Jun 29, 2024 |
| Gigabyte      | A520M S2H                   | [f31c64c53f](https://linux-hardware.org/?probe=f31c64c53f) | Jun 28, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [88674cc88c](https://linux-hardware.org/?probe=88674cc88c) | Jun 26, 2024 |
| Gigabyte      | H61M-S2PV                   | [452372da60](https://linux-hardware.org/?probe=452372da60) | Jun 26, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0a596b3a15](https://linux-hardware.org/?probe=0a596b3a15) | Jun 25, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [541dd376fe](https://linux-hardware.org/?probe=541dd376fe) | Jun 25, 2024 |
| Dell          | 0VD5HY A07                  | [e727d4984d](https://linux-hardware.org/?probe=e727d4984d) | Jun 24, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [68dad3008c](https://linux-hardware.org/?probe=68dad3008c) | Jun 24, 2024 |
| Dell          | 0VD5HY A07                  | [315931e6fe](https://linux-hardware.org/?probe=315931e6fe) | Jun 24, 2024 |
| Dell          | 00V62H A01                  | [ce7763c951](https://linux-hardware.org/?probe=ce7763c951) | Jun 23, 2024 |
| Foxconn       | 2ABF                        | [077530ceed](https://linux-hardware.org/?probe=077530ceed) | Jun 22, 2024 |
| Foxconn       | 2ABF                        | [27289dbbc2](https://linux-hardware.org/?probe=27289dbbc2) | Jun 21, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [a114a32ca4](https://linux-hardware.org/?probe=a114a32ca4) | Jun 20, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [d453d72cbd](https://linux-hardware.org/?probe=d453d72cbd) | Jun 19, 2024 |
| Gigabyte      | 945GCM-S2L                  | [87f752d0a6](https://linux-hardware.org/?probe=87f752d0a6) | Jun 18, 2024 |
| ASUSTek       | PRIME A520M-E               | [c16cfcbcc5](https://linux-hardware.org/?probe=c16cfcbcc5) | Jun 18, 2024 |
| Gigabyte      | G41M-Combo                  | [147b8d13a1](https://linux-hardware.org/?probe=147b8d13a1) | Jun 17, 2024 |
| ASRock        | Z390 Pro4                   | [42ac7a1fdd](https://linux-hardware.org/?probe=42ac7a1fdd) | Jun 17, 2024 |
| Gigabyte      | 945GCM-S2L                  | [682d4840e6](https://linux-hardware.org/?probe=682d4840e6) | Jun 13, 2024 |
| Dell          | 0D6H9T A01                  | [fc61008277](https://linux-hardware.org/?probe=fc61008277) | Jun 13, 2024 |
| ASRock        | B550M Pro4                  | [71a0e443db](https://linux-hardware.org/?probe=71a0e443db) | Jun 13, 2024 |
| ASUSTek       | P5QL-E                      | [6a6f4a7f73](https://linux-hardware.org/?probe=6a6f4a7f73) | Jun 12, 2024 |
| Dell          | 0D883F A06                  | [079225b3fa](https://linux-hardware.org/?probe=079225b3fa) | Jun 12, 2024 |
| ASUSTek       | P5QL-E                      | [65be90ddff](https://linux-hardware.org/?probe=65be90ddff) | Jun 12, 2024 |
| Lenovo        | SHARKBAY NOK                | [d0ad7e441c](https://linux-hardware.org/?probe=d0ad7e441c) | Jun 11, 2024 |
| Gigabyte      | H310M A-CF x.x              | [c711afbafc](https://linux-hardware.org/?probe=c711afbafc) | Jun 08, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2d4ca599f0](https://linux-hardware.org/?probe=2d4ca599f0) | Jun 06, 2024 |
| Medion        | MS-7748                     | [8da5b84f14](https://linux-hardware.org/?probe=8da5b84f14) | Jun 03, 2024 |
| Gigabyte      | B760M DS3H                  | [e31a124d8f](https://linux-hardware.org/?probe=e31a124d8f) | Jun 01, 2024 |
| Lenovo        | 1036 NO DPK                 | [cebf97eec0](https://linux-hardware.org/?probe=cebf97eec0) | May 31, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [03b2af62ce](https://linux-hardware.org/?probe=03b2af62ce) | May 28, 2024 |
| Dell          | 0VHWTR A02                  | [ad1a0ed72b](https://linux-hardware.org/?probe=ad1a0ed72b) | May 28, 2024 |
| Gigabyte      | Z390 UD                     | [65e0663229](https://linux-hardware.org/?probe=65e0663229) | May 27, 2024 |
| ASRock        | B365M Phantom Gaming 4      | [517f623f65](https://linux-hardware.org/?probe=517f623f65) | May 27, 2024 |
| ASRock        | B365M Phantom Gaming 4      | [40e95df3b4](https://linux-hardware.org/?probe=40e95df3b4) | May 27, 2024 |
| Dell          | 00V62H A01                  | [be4ffeac93](https://linux-hardware.org/?probe=be4ffeac93) | May 25, 2024 |
| ASRock        | X370 Gaming X               | [4dbaba7984](https://linux-hardware.org/?probe=4dbaba7984) | May 24, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [f241c2c732](https://linux-hardware.org/?probe=f241c2c732) | May 22, 2024 |
| Gigabyte      | Z390 UD                     | [48e5c09090](https://linux-hardware.org/?probe=48e5c09090) | May 22, 2024 |
| HP            | 0B4Ch D                     | [8fd2dd1d53](https://linux-hardware.org/?probe=8fd2dd1d53) | May 21, 2024 |
| HP            | 0B4Ch D                     | [12c9e86045](https://linux-hardware.org/?probe=12c9e86045) | May 21, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [cd94ebefb1](https://linux-hardware.org/?probe=cd94ebefb1) | May 20, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [438ad0c3e2](https://linux-hardware.org/?probe=438ad0c3e2) | May 20, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [3a559c71f1](https://linux-hardware.org/?probe=3a559c71f1) | May 20, 2024 |
| Gigabyte      | H310M A-CF x.x              | [26cce211b7](https://linux-hardware.org/?probe=26cce211b7) | May 20, 2024 |
| Gigabyte      | H310M A-CF x.x              | [490e30cf9a](https://linux-hardware.org/?probe=490e30cf9a) | May 20, 2024 |
| Dell          | 0D883F A06                  | [6cee89fe3e](https://linux-hardware.org/?probe=6cee89fe3e) | May 19, 2024 |
| HP            | 1495                        | [7e67c6b901](https://linux-hardware.org/?probe=7e67c6b901) | May 18, 2024 |
| Gigabyte      | P67A-D3-B3                  | [9bcfdc38a6](https://linux-hardware.org/?probe=9bcfdc38a6) | May 17, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [a11388c91d](https://linux-hardware.org/?probe=a11388c91d) | May 16, 2024 |
| Gigabyte      | A520M S2H                   | [1d5d18b2c5](https://linux-hardware.org/?probe=1d5d18b2c5) | May 16, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d3ac0dd23b](https://linux-hardware.org/?probe=d3ac0dd23b) | May 15, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [b131839670](https://linux-hardware.org/?probe=b131839670) | May 15, 2024 |
| Gigabyte      | B450M GAMING                | [a78c5b9bb0](https://linux-hardware.org/?probe=a78c5b9bb0) | May 15, 2024 |
| Dell          | 0TY565                      | [a151e79876](https://linux-hardware.org/?probe=a151e79876) | May 15, 2024 |
| ASUSTek       | PRIME A320M-R               | [ffd28789be](https://linux-hardware.org/?probe=ffd28789be) | May 15, 2024 |
| Dell          | 0M858N A01                  | [e829626861](https://linux-hardware.org/?probe=e829626861) | May 14, 2024 |
| ASRock        | G41M-VS3                    | [49d869ab09](https://linux-hardware.org/?probe=49d869ab09) | May 14, 2024 |
| HP            | 1495                        | [479a944647](https://linux-hardware.org/?probe=479a944647) | May 14, 2024 |
| ASUSTek       | H110M-K                     | [ec1cf7d3a7](https://linux-hardware.org/?probe=ec1cf7d3a7) | May 13, 2024 |
| Gigabyte      | H97-D3H-CF                  | [d960436ffd](https://linux-hardware.org/?probe=d960436ffd) | May 13, 2024 |
| Gigabyte      | Z390 UD                     | [e19d7dd8ae](https://linux-hardware.org/?probe=e19d7dd8ae) | May 13, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [d5b0e021f9](https://linux-hardware.org/?probe=d5b0e021f9) | May 13, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [16e661b316](https://linux-hardware.org/?probe=16e661b316) | May 13, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [0b368a7c31](https://linux-hardware.org/?probe=0b368a7c31) | May 13, 2024 |
| ASUSTek       | V-P7H55E                    | [53226b04a1](https://linux-hardware.org/?probe=53226b04a1) | May 13, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [5634be510c](https://linux-hardware.org/?probe=5634be510c) | May 13, 2024 |
| MSI           | H61M-P21                    | [f2b1198573](https://linux-hardware.org/?probe=f2b1198573) | May 13, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [806df98697](https://linux-hardware.org/?probe=806df98697) | May 13, 2024 |
| HP            | 339A                        | [d226354020](https://linux-hardware.org/?probe=d226354020) | May 12, 2024 |
| ASUSTek       | PRIME A520M-E               | [38f64dd422](https://linux-hardware.org/?probe=38f64dd422) | May 12, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [cfa00a5d7a](https://linux-hardware.org/?probe=cfa00a5d7a) | May 12, 2024 |
| HP            | 1497                        | [d75445b909](https://linux-hardware.org/?probe=d75445b909) | May 12, 2024 |
| Gigabyte      | G41M-Combo                  | [e0f1b89130](https://linux-hardware.org/?probe=e0f1b89130) | May 12, 2024 |
| Gigabyte      | H110M-S2V-CF                | [ffe1372ffa](https://linux-hardware.org/?probe=ffe1372ffa) | May 12, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [c7cb63d9fb](https://linux-hardware.org/?probe=c7cb63d9fb) | May 12, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [7298f5a42c](https://linux-hardware.org/?probe=7298f5a42c) | May 11, 2024 |
| MSI           | P43i                        | [51fe0060b1](https://linux-hardware.org/?probe=51fe0060b1) | May 11, 2024 |
| Gigabyte      | H61M-S1                     | [93a1cc6269](https://linux-hardware.org/?probe=93a1cc6269) | May 11, 2024 |
| ASUSTek       | A88XM-E                     | [bf26bf2028](https://linux-hardware.org/?probe=bf26bf2028) | May 11, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [29ae07a4b2](https://linux-hardware.org/?probe=29ae07a4b2) | May 11, 2024 |
| Lenovo        | ThinkCentre M58 9960ALU     | [122d9a348a](https://linux-hardware.org/?probe=122d9a348a) | May 11, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [1c054115b1](https://linux-hardware.org/?probe=1c054115b1) | May 11, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [d42f60f8b8](https://linux-hardware.org/?probe=d42f60f8b8) | May 11, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [62c5375519](https://linux-hardware.org/?probe=62c5375519) | May 11, 2024 |
| Gigabyte      | P61-USB3-B3                 | [1cb5ba39ca](https://linux-hardware.org/?probe=1cb5ba39ca) | May 10, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [432b3aeaeb](https://linux-hardware.org/?probe=432b3aeaeb) | May 10, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [03cb58bfd8](https://linux-hardware.org/?probe=03cb58bfd8) | May 10, 2024 |
| ASUSTek       | H110M-A                     | [0d9c011ed5](https://linux-hardware.org/?probe=0d9c011ed5) | May 10, 2024 |
| Dell          | 0M5DCD A00                  | [be5bd35f96](https://linux-hardware.org/?probe=be5bd35f96) | May 09, 2024 |
| HP            | 0B4Ch D                     | [c1829c21ab](https://linux-hardware.org/?probe=c1829c21ab) | May 09, 2024 |
| HP            | 805D                        | [208bd3b9dd](https://linux-hardware.org/?probe=208bd3b9dd) | May 09, 2024 |
| Dell          | 00V62H A01                  | [2ea426bed2](https://linux-hardware.org/?probe=2ea426bed2) | May 08, 2024 |
| Dell          | 00V62H A01                  | [bc8a5150c3](https://linux-hardware.org/?probe=bc8a5150c3) | May 08, 2024 |
| Dell          | 0M858N A01                  | [9b34c8bbc2](https://linux-hardware.org/?probe=9b34c8bbc2) | May 08, 2024 |
| Lenovo        | 1036 NO DPK                 | [ea4077ed1b](https://linux-hardware.org/?probe=ea4077ed1b) | May 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [75811cd1df](https://linux-hardware.org/?probe=75811cd1df) | May 08, 2024 |
| HP            | 1495                        | [89464c1187](https://linux-hardware.org/?probe=89464c1187) | May 08, 2024 |
| ASRock        | B550M Pro4                  | [41c99b8030](https://linux-hardware.org/?probe=41c99b8030) | May 08, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [14bb67e07a](https://linux-hardware.org/?probe=14bb67e07a) | May 07, 2024 |
| ASUSTek       | H110M-A                     | [e4868e57a3](https://linux-hardware.org/?probe=e4868e57a3) | May 07, 2024 |
| ASUSTek       | PRIME A320M-R               | [8b5ef47376](https://linux-hardware.org/?probe=8b5ef47376) | May 07, 2024 |
| ASRock        | Z390 Pro4                   | [ee53393400](https://linux-hardware.org/?probe=ee53393400) | May 07, 2024 |
| ASUSTek       | H110M-K                     | [373b9bdb5c](https://linux-hardware.org/?probe=373b9bdb5c) | May 07, 2024 |
| Gigabyte      | H110M-S2V-CF                | [22eb41201e](https://linux-hardware.org/?probe=22eb41201e) | May 07, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [e8e1e2e2f8](https://linux-hardware.org/?probe=e8e1e2e2f8) | May 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [07a4ffe918](https://linux-hardware.org/?probe=07a4ffe918) | May 07, 2024 |
| Lenovo        | SHARKBAY NOK                | [f696d03152](https://linux-hardware.org/?probe=f696d03152) | May 07, 2024 |
| Gigabyte      | A520M S2H                   | [c14a7e4724](https://linux-hardware.org/?probe=c14a7e4724) | May 07, 2024 |
| ASUSTek       | A88XM-E                     | [bba7d20511](https://linux-hardware.org/?probe=bba7d20511) | May 07, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [c23f1deec5](https://linux-hardware.org/?probe=c23f1deec5) | May 06, 2024 |
| Gigabyte      | Z390 UD                     | [af2a20709c](https://linux-hardware.org/?probe=af2a20709c) | May 05, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [b1077f633d](https://linux-hardware.org/?probe=b1077f633d) | May 04, 2024 |
| HP            | 8062                        | [87c4c1fbfb](https://linux-hardware.org/?probe=87c4c1fbfb) | May 02, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [ff55d733a4](https://linux-hardware.org/?probe=ff55d733a4) | May 01, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [fbb11f7603](https://linux-hardware.org/?probe=fbb11f7603) | May 01, 2024 |
| HP            | 0B4Ch D                     | [db2b347526](https://linux-hardware.org/?probe=db2b347526) | Apr 30, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [120693fd0b](https://linux-hardware.org/?probe=120693fd0b) | Apr 29, 2024 |
| HP            | 0B4Ch D                     | [a4057cd447](https://linux-hardware.org/?probe=a4057cd447) | Apr 28, 2024 |
| ASRock        | Z390 Pro4                   | [b50024c729](https://linux-hardware.org/?probe=b50024c729) | Apr 28, 2024 |
| Gigabyte      | B450M GAMING                | [f81c1dea8d](https://linux-hardware.org/?probe=f81c1dea8d) | Apr 27, 2024 |
| Gigabyte      | B450M GAMING                | [0edf4e838c](https://linux-hardware.org/?probe=0edf4e838c) | Apr 27, 2024 |
| Dell          | 0D883F A06                  | [a82d507833](https://linux-hardware.org/?probe=a82d507833) | Apr 27, 2024 |
| Dell          | 0W0CHX A00                  | [9da5e84704](https://linux-hardware.org/?probe=9da5e84704) | Apr 27, 2024 |
| Dell          | 0W0CHX A00                  | [dd4600928f](https://linux-hardware.org/?probe=dd4600928f) | Apr 27, 2024 |
| Dell          | 0200DY A03                  | [96991fe0ba](https://linux-hardware.org/?probe=96991fe0ba) | Apr 27, 2024 |
| ASUSTek       | A88XM-E                     | [96107974e8](https://linux-hardware.org/?probe=96107974e8) | Apr 25, 2024 |
| Lenovo        | 1036 NO DPK                 | [e69292ead4](https://linux-hardware.org/?probe=e69292ead4) | Apr 25, 2024 |
| ASRock        | B550M Pro4                  | [60952c8e62](https://linux-hardware.org/?probe=60952c8e62) | Apr 24, 2024 |
| Gigabyte      | H310M A-CF x.x              | [250df2037f](https://linux-hardware.org/?probe=250df2037f) | Apr 24, 2024 |
| Dell          | 0200DY A03                  | [a838cb0e0d](https://linux-hardware.org/?probe=a838cb0e0d) | Apr 23, 2024 |
| HP            | 1494                        | [82c9d00df1](https://linux-hardware.org/?probe=82c9d00df1) | Apr 22, 2024 |
| Dell          | 0HY9JP A02                  | [08e7641b37](https://linux-hardware.org/?probe=08e7641b37) | Apr 22, 2024 |
| Lenovo        | 1036 NO DPK                 | [1462b6d76a](https://linux-hardware.org/?probe=1462b6d76a) | Apr 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [91735d80f4](https://linux-hardware.org/?probe=91735d80f4) | Apr 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [ff2ff25197](https://linux-hardware.org/?probe=ff2ff25197) | Apr 22, 2024 |
| Gigabyte      | Z390 UD                     | [60d76632dc](https://linux-hardware.org/?probe=60d76632dc) | Apr 21, 2024 |
| Dell          | 0TY565                      | [f5c8cf7e9b](https://linux-hardware.org/?probe=f5c8cf7e9b) | Apr 21, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [8b93f4607f](https://linux-hardware.org/?probe=8b93f4607f) | Apr 20, 2024 |
| ASUSTek       | PRIME A320M-R               | [b10f7daaa1](https://linux-hardware.org/?probe=b10f7daaa1) | Apr 20, 2024 |
| MSI           | X58 Pro-E                   | [4411cb9e36](https://linux-hardware.org/?probe=4411cb9e36) | Apr 18, 2024 |
| Dell          | 0HD5W2 A01                  | [1c7957de19](https://linux-hardware.org/?probe=1c7957de19) | Apr 16, 2024 |
| ASRock        | X370 Gaming X               | [db397e4511](https://linux-hardware.org/?probe=db397e4511) | Apr 15, 2024 |
| Dell          | 0VHWTR A02                  | [4e32c7cfca](https://linux-hardware.org/?probe=4e32c7cfca) | Apr 15, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [88ad8806c3](https://linux-hardware.org/?probe=88ad8806c3) | Apr 13, 2024 |
| HP            | 8265                        | [c4d4cdac41](https://linux-hardware.org/?probe=c4d4cdac41) | Apr 13, 2024 |
| Gigabyte      | H310M A-CF x.x              | [5bc49637b9](https://linux-hardware.org/?probe=5bc49637b9) | Apr 12, 2024 |
| Gigabyte      | H61M-S1                     | [1a9697f39d](https://linux-hardware.org/?probe=1a9697f39d) | Apr 12, 2024 |
| ASUSTek       | P8Z77-V LX                  | [c108665460](https://linux-hardware.org/?probe=c108665460) | Apr 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5fb89da542](https://linux-hardware.org/?probe=5fb89da542) | Apr 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [74dd149115](https://linux-hardware.org/?probe=74dd149115) | Apr 11, 2024 |
| HP            | 8062                        | [358bbe16f0](https://linux-hardware.org/?probe=358bbe16f0) | Apr 11, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [dd15f5797f](https://linux-hardware.org/?probe=dd15f5797f) | Apr 09, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [2d897e4ab7](https://linux-hardware.org/?probe=2d897e4ab7) | Apr 09, 2024 |
| ASUSTek       | PRIME A320M-R               | [eb77201fa8](https://linux-hardware.org/?probe=eb77201fa8) | Apr 09, 2024 |
| Gigabyte      | B75M-D3H                    | [fa4c48c242](https://linux-hardware.org/?probe=fa4c48c242) | Apr 09, 2024 |
| ASUSTek       | ROG Maximus X CODE          | [446576913d](https://linux-hardware.org/?probe=446576913d) | Apr 08, 2024 |
| ASUSTek       | M4A785TD-V EVO              | [2dbe37af95](https://linux-hardware.org/?probe=2dbe37af95) | Apr 07, 2024 |
| HP            | 8265                        | [601051ee6c](https://linux-hardware.org/?probe=601051ee6c) | Apr 07, 2024 |
| Gigabyte      | H61M-S1                     | [7fe942c453](https://linux-hardware.org/?probe=7fe942c453) | Apr 07, 2024 |
| Dell          | 0D883F A06                  | [74170027e8](https://linux-hardware.org/?probe=74170027e8) | Apr 07, 2024 |
| ASUSTek       | PRIME B365M-A               | [50b8d3eaf1](https://linux-hardware.org/?probe=50b8d3eaf1) | Apr 07, 2024 |
| Gigabyte      | Z390 UD                     | [3378d48eb3](https://linux-hardware.org/?probe=3378d48eb3) | Apr 07, 2024 |
| HP            | 8265                        | [b08747219b](https://linux-hardware.org/?probe=b08747219b) | Apr 06, 2024 |
| ASRock        | Z370 Extreme4               | [6354d3d2a2](https://linux-hardware.org/?probe=6354d3d2a2) | Apr 05, 2024 |
| ASRock        | Z370 Extreme4               | [f6925b3c88](https://linux-hardware.org/?probe=f6925b3c88) | Apr 05, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [102e8ee904](https://linux-hardware.org/?probe=102e8ee904) | Apr 05, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [95a657f223](https://linux-hardware.org/?probe=95a657f223) | Apr 03, 2024 |
| ASRock        | 4CoreDual-SATA2             | [469a404c91](https://linux-hardware.org/?probe=469a404c91) | Apr 03, 2024 |
| Dell          | 0YP693 A02                  | [3c0b19e9f2](https://linux-hardware.org/?probe=3c0b19e9f2) | Apr 03, 2024 |
| Dell          | 0YP693 A02                  | [48ec750bd0](https://linux-hardware.org/?probe=48ec750bd0) | Apr 03, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [6d4eaf0bc7](https://linux-hardware.org/?probe=6d4eaf0bc7) | Apr 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b4d733040a](https://linux-hardware.org/?probe=b4d733040a) | Mar 31, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b4555fa57d](https://linux-hardware.org/?probe=b4555fa57d) | Mar 31, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [bc68546a92](https://linux-hardware.org/?probe=bc68546a92) | Mar 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [c0736cef30](https://linux-hardware.org/?probe=c0736cef30) | Mar 29, 2024 |
| ASUSTek       | H110M-A                     | [d7699c7455](https://linux-hardware.org/?probe=d7699c7455) | Mar 29, 2024 |
| ASRock        | 4CoreDual-SATA2             | [30817e9020](https://linux-hardware.org/?probe=30817e9020) | Mar 29, 2024 |
| ASRock        | 4CoreDual-SATA2             | [cbccd74400](https://linux-hardware.org/?probe=cbccd74400) | Mar 29, 2024 |
| Lenovo        | 1036 NO DPK                 | [ba8b769eb3](https://linux-hardware.org/?probe=ba8b769eb3) | Mar 29, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [368a738712](https://linux-hardware.org/?probe=368a738712) | Mar 28, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [84c4c90a3f](https://linux-hardware.org/?probe=84c4c90a3f) | Mar 27, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [6c186bed7b](https://linux-hardware.org/?probe=6c186bed7b) | Mar 26, 2024 |
| HP            | 1495                        | [806af03d1c](https://linux-hardware.org/?probe=806af03d1c) | Mar 26, 2024 |
| ASRock        | B550M Pro4                  | [e9c2053699](https://linux-hardware.org/?probe=e9c2053699) | Mar 25, 2024 |
| ASRock        | N68C-GS FX                  | [793650d556](https://linux-hardware.org/?probe=793650d556) | Mar 25, 2024 |
| HP            | 339A                        | [a07dca6a8c](https://linux-hardware.org/?probe=a07dca6a8c) | Mar 25, 2024 |
| Dell          | 0K240Y A01                  | [eff3389fdb](https://linux-hardware.org/?probe=eff3389fdb) | Mar 25, 2024 |
| HP            | 1495                        | [50e1e9d3da](https://linux-hardware.org/?probe=50e1e9d3da) | Mar 25, 2024 |
| MSI           | P43i                        | [d56d55fd40](https://linux-hardware.org/?probe=d56d55fd40) | Mar 24, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [fa1a2097f6](https://linux-hardware.org/?probe=fa1a2097f6) | Mar 24, 2024 |
| Gigabyte      | P67A-D3-B3                  | [1f06fd5eea](https://linux-hardware.org/?probe=1f06fd5eea) | Mar 24, 2024 |
| Dell          | 0RN474                      | [665f831546](https://linux-hardware.org/?probe=665f831546) | Mar 24, 2024 |
| ASRock        | B85M                        | [4c906767aa](https://linux-hardware.org/?probe=4c906767aa) | Mar 24, 2024 |
| ASUSTek       | Maximus VI HERO             | [4fac588ebc](https://linux-hardware.org/?probe=4fac588ebc) | Mar 23, 2024 |
| ASUSTek       | Maximus VI HERO             | [2016d6fb0a](https://linux-hardware.org/?probe=2016d6fb0a) | Mar 23, 2024 |
| Dell          | 0M858N A01                  | [fa3478bb8f](https://linux-hardware.org/?probe=fa3478bb8f) | Mar 23, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [1f9a0b4802](https://linux-hardware.org/?probe=1f9a0b4802) | Mar 23, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1a34385882](https://linux-hardware.org/?probe=1a34385882) | Mar 23, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [1ee4446988](https://linux-hardware.org/?probe=1ee4446988) | Mar 23, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3d39374ca9](https://linux-hardware.org/?probe=3d39374ca9) | Mar 23, 2024 |
| Gigabyte      | Z390 UD                     | [9052435efd](https://linux-hardware.org/?probe=9052435efd) | Mar 23, 2024 |
| Gigabyte      | H310M A-CF x.x              | [ef274edd0e](https://linux-hardware.org/?probe=ef274edd0e) | Mar 23, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [1368766d06](https://linux-hardware.org/?probe=1368766d06) | Mar 23, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5cf4153f8c](https://linux-hardware.org/?probe=5cf4153f8c) | Mar 23, 2024 |
| Gigabyte      | A520M S2H                   | [11901df61a](https://linux-hardware.org/?probe=11901df61a) | Mar 23, 2024 |
| Gigabyte      | H97-D3H-CF                  | [76ee872777](https://linux-hardware.org/?probe=76ee872777) | Mar 22, 2024 |
| ASUSTek       | H110M-A                     | [2d969a527b](https://linux-hardware.org/?probe=2d969a527b) | Mar 22, 2024 |
| Gigabyte      | B250-HD3P-CF                | [a562caa39d](https://linux-hardware.org/?probe=a562caa39d) | Mar 22, 2024 |
| Gigabyte      | P61-USB3-B3                 | [bd7ae42260](https://linux-hardware.org/?probe=bd7ae42260) | Mar 22, 2024 |
| Dell          | 0200DY A03                  | [0838a0e911](https://linux-hardware.org/?probe=0838a0e911) | Mar 21, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [4276c6c62c](https://linux-hardware.org/?probe=4276c6c62c) | Mar 21, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c8b0e932f7](https://linux-hardware.org/?probe=c8b0e932f7) | Mar 21, 2024 |
| MSI           | A320M-A PRO MAX             | [faff855b6c](https://linux-hardware.org/?probe=faff855b6c) | Mar 21, 2024 |
| Gigabyte      | H110M-S2V-CF                | [be31fe508d](https://linux-hardware.org/?probe=be31fe508d) | Mar 21, 2024 |
| MSI           | MS-7369                     | [0a36f4715f](https://linux-hardware.org/?probe=0a36f4715f) | Mar 21, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9d36d6bf2a](https://linux-hardware.org/?probe=9d36d6bf2a) | Mar 21, 2024 |
| MSI           | H61M-P21                    | [feba614c1c](https://linux-hardware.org/?probe=feba614c1c) | Mar 21, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [5de3598ad6](https://linux-hardware.org/?probe=5de3598ad6) | Mar 21, 2024 |
| Fujitsu       | D3003-C1 S26361-D3003-C1    | [a58bb79ea5](https://linux-hardware.org/?probe=a58bb79ea5) | Mar 20, 2024 |
| Fujitsu       | D3003-C1 S26361-D3003-C1    | [98cfbdc7b2](https://linux-hardware.org/?probe=98cfbdc7b2) | Mar 20, 2024 |
| ASUSTek       | PRIME A320M-R               | [50369a26af](https://linux-hardware.org/?probe=50369a26af) | Mar 19, 2024 |
| ASUSTek       | PRIME A520M-E               | [fe6517ecf5](https://linux-hardware.org/?probe=fe6517ecf5) | Mar 18, 2024 |
| ASUSTek       | PRIME A520M-E               | [151ae9cdaf](https://linux-hardware.org/?probe=151ae9cdaf) | Mar 18, 2024 |
| ASUSTek       | G15DK                       | [1265b31544](https://linux-hardware.org/?probe=1265b31544) | Mar 18, 2024 |
| Gigabyte      | P35-DS3R                    | [0e8135e5be](https://linux-hardware.org/?probe=0e8135e5be) | Mar 17, 2024 |
| Gigabyte      | P35-DS3R                    | [37d7839fa0](https://linux-hardware.org/?probe=37d7839fa0) | Mar 17, 2024 |
| Gigabyte      | Z170-Gaming K3-CF           | [e6b3e23ce6](https://linux-hardware.org/?probe=e6b3e23ce6) | Mar 16, 2024 |
| MSI           | A320M-A PRO MAX             | [1d1cd6ea78](https://linux-hardware.org/?probe=1d1cd6ea78) | Mar 15, 2024 |
| Dell          | 0D883F A06                  | [6d25f1767a](https://linux-hardware.org/?probe=6d25f1767a) | Mar 15, 2024 |
| Dell          | 0K240Y A01                  | [01dc917dc9](https://linux-hardware.org/?probe=01dc917dc9) | Mar 15, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [53e053987b](https://linux-hardware.org/?probe=53e053987b) | Mar 15, 2024 |
| ASUSTek       | PRIME H410M-A               | [5a5a67a0da](https://linux-hardware.org/?probe=5a5a67a0da) | Mar 14, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [996e768c3b](https://linux-hardware.org/?probe=996e768c3b) | Mar 14, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [86d3affb55](https://linux-hardware.org/?probe=86d3affb55) | Mar 14, 2024 |
| Medion        | MS-7748                     | [2936ceb830](https://linux-hardware.org/?probe=2936ceb830) | Mar 14, 2024 |
| ASUSTek       | PRIME A320M-R               | [f3d5cd78e2](https://linux-hardware.org/?probe=f3d5cd78e2) | Mar 14, 2024 |
| ASUSTek       | PRIME H410M-A               | [ad72304437](https://linux-hardware.org/?probe=ad72304437) | Mar 13, 2024 |
| Lenovo        | 1730-A1G                    | [7c5c30e4d7](https://linux-hardware.org/?probe=7c5c30e4d7) | Mar 13, 2024 |
| Lenovo        | SHARKBAY NOK                | [ebf6bd7140](https://linux-hardware.org/?probe=ebf6bd7140) | Mar 13, 2024 |
| Gigabyte      | B450M GAMING                | [712f217722](https://linux-hardware.org/?probe=712f217722) | Mar 12, 2024 |
| Gigabyte      | P61-USB3-B3                 | [b632a864a7](https://linux-hardware.org/?probe=b632a864a7) | Mar 11, 2024 |
| Gigabyte      | B85M-HD3G                   | [61d1a0a769](https://linux-hardware.org/?probe=61d1a0a769) | Mar 11, 2024 |
| Gigabyte      | B85M-HD3G                   | [827f0d1418](https://linux-hardware.org/?probe=827f0d1418) | Mar 11, 2024 |
| ASUSTek       | A88XM-E                     | [6dc26a8c1b](https://linux-hardware.org/?probe=6dc26a8c1b) | Mar 11, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [dfa4480394](https://linux-hardware.org/?probe=dfa4480394) | Mar 10, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [7f8abbb276](https://linux-hardware.org/?probe=7f8abbb276) | Mar 09, 2024 |
| Gigabyte      | H110M-S2V-CF                | [9eecf787b4](https://linux-hardware.org/?probe=9eecf787b4) | Mar 09, 2024 |
| Dell          | 0VHWTR A02                  | [414f810f95](https://linux-hardware.org/?probe=414f810f95) | Mar 08, 2024 |
| ASUSTek       | PRIME A320M-K               | [bf70b84d81](https://linux-hardware.org/?probe=bf70b84d81) | Mar 08, 2024 |
| HP            | 805D                        | [853e435928](https://linux-hardware.org/?probe=853e435928) | Mar 08, 2024 |
| Lenovo        | SHARKBAY NOK                | [4076eb2209](https://linux-hardware.org/?probe=4076eb2209) | Mar 07, 2024 |
| ASUSTek       | PRIME A320M-K               | [90d69200ef](https://linux-hardware.org/?probe=90d69200ef) | Mar 07, 2024 |
| Medion        | MS-7748                     | [77a10d77ea](https://linux-hardware.org/?probe=77a10d77ea) | Mar 07, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [c9d0284a9b](https://linux-hardware.org/?probe=c9d0284a9b) | Mar 06, 2024 |
| ASUSTek       | H110M-A                     | [695e54f273](https://linux-hardware.org/?probe=695e54f273) | Mar 05, 2024 |
| Gigabyte      | B450 GAMING X               | [ab4aeaa345](https://linux-hardware.org/?probe=ab4aeaa345) | Mar 03, 2024 |
| ASRock        | G41M-VS3                    | [03a42b8972](https://linux-hardware.org/?probe=03a42b8972) | Mar 03, 2024 |
| HP            | 3047h                       | [fb25a061b8](https://linux-hardware.org/?probe=fb25a061b8) | Mar 03, 2024 |
| HP            | 3047h                       | [171fc32e0a](https://linux-hardware.org/?probe=171fc32e0a) | Mar 03, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7f0877ee14](https://linux-hardware.org/?probe=7f0877ee14) | Mar 03, 2024 |
| Dell          | 0200DY A03                  | [b06d040c63](https://linux-hardware.org/?probe=b06d040c63) | Mar 03, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [c9c10a188e](https://linux-hardware.org/?probe=c9c10a188e) | Mar 02, 2024 |
| Gigabyte      | B450M GAMING                | [5ffab2a305](https://linux-hardware.org/?probe=5ffab2a305) | Mar 02, 2024 |
| Gigabyte      | Z390 UD                     | [9cbfa725df](https://linux-hardware.org/?probe=9cbfa725df) | Feb 28, 2024 |
| ASRock        | B550M Pro4                  | [795e44e4cf](https://linux-hardware.org/?probe=795e44e4cf) | Feb 28, 2024 |
| HP            | 1497                        | [8fc0f49c19](https://linux-hardware.org/?probe=8fc0f49c19) | Feb 26, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7019e3f6f8](https://linux-hardware.org/?probe=7019e3f6f8) | Feb 25, 2024 |
| Gigabyte      | H310M A-CF x.x              | [af6ad45d24](https://linux-hardware.org/?probe=af6ad45d24) | Feb 25, 2024 |
| Lenovo        | 1730-A1G                    | [a6ca9cff31](https://linux-hardware.org/?probe=a6ca9cff31) | Feb 25, 2024 |
| HP            | 304Ah                       | [0c2c06e76f](https://linux-hardware.org/?probe=0c2c06e76f) | Feb 25, 2024 |
| HP            | 304Ah                       | [98ce8f9cf7](https://linux-hardware.org/?probe=98ce8f9cf7) | Feb 25, 2024 |
| Dell          | 0RN474                      | [c2ca6576b9](https://linux-hardware.org/?probe=c2ca6576b9) | Feb 25, 2024 |
| MSI           | MS-7369                     | [d771ce7ed3](https://linux-hardware.org/?probe=d771ce7ed3) | Feb 25, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [bf94f23691](https://linux-hardware.org/?probe=bf94f23691) | Feb 24, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6a9db010d9](https://linux-hardware.org/?probe=6a9db010d9) | Feb 24, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [2ae75f745e](https://linux-hardware.org/?probe=2ae75f745e) | Feb 23, 2024 |
| Dell          | 0D883F A06                  | [2f2b1cd47c](https://linux-hardware.org/?probe=2f2b1cd47c) | Feb 21, 2024 |
| HP            | 8265                        | [530f502c52](https://linux-hardware.org/?probe=530f502c52) | Feb 20, 2024 |
| Gigabyte      | G31M-S2C                    | [678ad5ec54](https://linux-hardware.org/?probe=678ad5ec54) | Feb 20, 2024 |
| ASRock        | FM2A75M Pro4+               | [cbc49630c4](https://linux-hardware.org/?probe=cbc49630c4) | Feb 19, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [3279f823cb](https://linux-hardware.org/?probe=3279f823cb) | Feb 19, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [c301bbef33](https://linux-hardware.org/?probe=c301bbef33) | Feb 19, 2024 |
| Gigabyte      | H310M A-CF x.x              | [5df2e64ba9](https://linux-hardware.org/?probe=5df2e64ba9) | Feb 18, 2024 |
| Gigabyte      | EP31-DS3L                   | [a2f2f76c2e](https://linux-hardware.org/?probe=a2f2f76c2e) | Feb 18, 2024 |
| Dell          | 0Y2MRG A00                  | [ddea40bc9b](https://linux-hardware.org/?probe=ddea40bc9b) | Feb 18, 2024 |
| Dell          | 0Y2MRG A00                  | [d23358d851](https://linux-hardware.org/?probe=d23358d851) | Feb 18, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [ad35cbf450](https://linux-hardware.org/?probe=ad35cbf450) | Feb 17, 2024 |
| HP            | 3047h                       | [45ba601c69](https://linux-hardware.org/?probe=45ba601c69) | Feb 16, 2024 |
| ASRock        | B85M                        | [c9300aa54b](https://linux-hardware.org/?probe=c9300aa54b) | Feb 16, 2024 |
| Gigabyte      | A520M S2H                   | [ff0aa6019c](https://linux-hardware.org/?probe=ff0aa6019c) | Feb 16, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [0139a8dd1b](https://linux-hardware.org/?probe=0139a8dd1b) | Feb 15, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [b116cf57b4](https://linux-hardware.org/?probe=b116cf57b4) | Feb 15, 2024 |
| Lenovo        | 1036 NO DPK                 | [125c31fd2c](https://linux-hardware.org/?probe=125c31fd2c) | Feb 15, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [e962ebfe4d](https://linux-hardware.org/?probe=e962ebfe4d) | Feb 14, 2024 |
| HP            | 8265                        | [e4997d7fc2](https://linux-hardware.org/?probe=e4997d7fc2) | Feb 14, 2024 |
| HP            | 339A                        | [69c4f45b66](https://linux-hardware.org/?probe=69c4f45b66) | Feb 14, 2024 |
| Gigabyte      | H97-D3H-CF                  | [a5117dd4fd](https://linux-hardware.org/?probe=a5117dd4fd) | Feb 13, 2024 |
| ASUSTek       | PRIME B365M-A               | [2955560f16](https://linux-hardware.org/?probe=2955560f16) | Feb 13, 2024 |
| ASRock        | N68C-GS FX                  | [81bc175b9c](https://linux-hardware.org/?probe=81bc175b9c) | Feb 13, 2024 |
| ASRock        | B550M Pro4                  | [39aa1a05dd](https://linux-hardware.org/?probe=39aa1a05dd) | Feb 13, 2024 |
| Dell          | 0200DY A03                  | [6075938249](https://linux-hardware.org/?probe=6075938249) | Feb 12, 2024 |
| Gigabyte      | H61M-S1                     | [5ba6bba9d7](https://linux-hardware.org/?probe=5ba6bba9d7) | Feb 11, 2024 |
| Gigabyte      | H61M-S2PV                   | [1f1cba872e](https://linux-hardware.org/?probe=1f1cba872e) | Feb 11, 2024 |
| Gigabyte      | P67A-D3-B3                  | [a1b482c4e5](https://linux-hardware.org/?probe=a1b482c4e5) | Feb 11, 2024 |
| ASUSTek       | P8Z77-V LX                  | [1db2b9826c](https://linux-hardware.org/?probe=1db2b9826c) | Feb 11, 2024 |
| Gigabyte      | H61M-S2PV                   | [214f3483d2](https://linux-hardware.org/?probe=214f3483d2) | Feb 11, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [1c432f8df1](https://linux-hardware.org/?probe=1c432f8df1) | Feb 11, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4086a071b2](https://linux-hardware.org/?probe=4086a071b2) | Feb 11, 2024 |
| Lenovo        | ThinkCentre M58 9960ALU     | [2eaa6f55a6](https://linux-hardware.org/?probe=2eaa6f55a6) | Feb 11, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [db64b21f5a](https://linux-hardware.org/?probe=db64b21f5a) | Feb 11, 2024 |
| Dell          | 0TY565                      | [d7a498944b](https://linux-hardware.org/?probe=d7a498944b) | Feb 11, 2024 |
| Intel         | DG35EC AAE29266-210         | [38bd2900f7](https://linux-hardware.org/?probe=38bd2900f7) | Feb 10, 2024 |
| Intel         | DG35EC AAE29266-210         | [5e6e7740d9](https://linux-hardware.org/?probe=5e6e7740d9) | Feb 10, 2024 |
| Gigabyte      | H110M-S2V-CF                | [02056c1523](https://linux-hardware.org/?probe=02056c1523) | Feb 10, 2024 |
| HP            | 8265                        | [e83158cda7](https://linux-hardware.org/?probe=e83158cda7) | Feb 10, 2024 |
| ASUSTek       | PRIME A320M-R               | [73ec818c35](https://linux-hardware.org/?probe=73ec818c35) | Feb 10, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [377976b6a3](https://linux-hardware.org/?probe=377976b6a3) | Feb 10, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [edb250e20a](https://linux-hardware.org/?probe=edb250e20a) | Feb 10, 2024 |
| ASUSTek       | H110M-K                     | [5002d94a38](https://linux-hardware.org/?probe=5002d94a38) | Feb 09, 2024 |
| ASRock        | 775i945GZ                   | [38891b0920](https://linux-hardware.org/?probe=38891b0920) | Feb 09, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [e9f7f560fe](https://linux-hardware.org/?probe=e9f7f560fe) | Feb 09, 2024 |
| HP            | 1495                        | [6fff4b1751](https://linux-hardware.org/?probe=6fff4b1751) | Feb 09, 2024 |
| Dell          | 0M858N A01                  | [e57e9094b4](https://linux-hardware.org/?probe=e57e9094b4) | Feb 08, 2024 |
| MSI           | P43i                        | [b4c30541fa](https://linux-hardware.org/?probe=b4c30541fa) | Feb 08, 2024 |
| ASUSTek       | H110M-A                     | [4515105b8d](https://linux-hardware.org/?probe=4515105b8d) | Feb 08, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [742d19f797](https://linux-hardware.org/?probe=742d19f797) | Feb 08, 2024 |
| Gigabyte      | H110M-S2V-CF                | [84a355a004](https://linux-hardware.org/?probe=84a355a004) | Feb 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [90a5d44bde](https://linux-hardware.org/?probe=90a5d44bde) | Feb 08, 2024 |
| MSI           | A320M-A PRO MAX             | [986691347b](https://linux-hardware.org/?probe=986691347b) | Feb 07, 2024 |
| Dell          | 0VHWTR A02                  | [d37b4c9999](https://linux-hardware.org/?probe=d37b4c9999) | Feb 07, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [d1be9e4f66](https://linux-hardware.org/?probe=d1be9e4f66) | Feb 07, 2024 |
| Lenovo        | 1730-A1G                    | [9f50a00ce2](https://linux-hardware.org/?probe=9f50a00ce2) | Feb 07, 2024 |
| Lenovo        | 1730-A1G                    | [52d70892db](https://linux-hardware.org/?probe=52d70892db) | Feb 07, 2024 |
| HP            | 1495                        | [72869998f4](https://linux-hardware.org/?probe=72869998f4) | Feb 07, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [0c0a1d2651](https://linux-hardware.org/?probe=0c0a1d2651) | Feb 06, 2024 |
| HP            | 0B4Ch D                     | [9258e387e7](https://linux-hardware.org/?probe=9258e387e7) | Feb 06, 2024 |
| Gigabyte      | H61M-S1                     | [89b53566aa](https://linux-hardware.org/?probe=89b53566aa) | Feb 06, 2024 |
| Lenovo        | 1036 NO DPK                 | [90b0945a98](https://linux-hardware.org/?probe=90b0945a98) | Feb 06, 2024 |
| Dell          | 0M858N A01                  | [efe0f9fc26](https://linux-hardware.org/?probe=efe0f9fc26) | Feb 05, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5013c4bba6](https://linux-hardware.org/?probe=5013c4bba6) | Feb 05, 2024 |
| Gigabyte      | H310M A-CF x.x              | [e9ae02c21e](https://linux-hardware.org/?probe=e9ae02c21e) | Feb 05, 2024 |
| Gigabyte      | A520M S2H                   | [a5467dc900](https://linux-hardware.org/?probe=a5467dc900) | Feb 04, 2024 |
| Dell          | 0D883F A06                  | [79200de704](https://linux-hardware.org/?probe=79200de704) | Feb 04, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ca1fce3f2f](https://linux-hardware.org/?probe=ca1fce3f2f) | Feb 04, 2024 |
| Dell          | 0D883F A06                  | [553aeec0a5](https://linux-hardware.org/?probe=553aeec0a5) | Feb 04, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [a0c3cd5ffd](https://linux-hardware.org/?probe=a0c3cd5ffd) | Feb 04, 2024 |
| ASUSTek       | PRIME A320M-R               | [533592b8f0](https://linux-hardware.org/?probe=533592b8f0) | Feb 04, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [e70b13c7d6](https://linux-hardware.org/?probe=e70b13c7d6) | Feb 04, 2024 |
| ASUSTek       | H110M-A                     | [684ac8da19](https://linux-hardware.org/?probe=684ac8da19) | Feb 04, 2024 |
| Dell          | 0200DY A03                  | [07d45f5532](https://linux-hardware.org/?probe=07d45f5532) | Feb 03, 2024 |
| Gigabyte      | H97-D3H-CF                  | [9c4309b1ea](https://linux-hardware.org/?probe=9c4309b1ea) | Feb 03, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6068e871ed](https://linux-hardware.org/?probe=6068e871ed) | Feb 03, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5eb37a9fb2](https://linux-hardware.org/?probe=5eb37a9fb2) | Feb 03, 2024 |
| HP            | 1497                        | [ae90a32790](https://linux-hardware.org/?probe=ae90a32790) | Feb 02, 2024 |
| Gigabyte      | G31M-S2C                    | [b0e201e74a](https://linux-hardware.org/?probe=b0e201e74a) | Feb 02, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [4009a96bd4](https://linux-hardware.org/?probe=4009a96bd4) | Feb 02, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [ab60a0a3b4](https://linux-hardware.org/?probe=ab60a0a3b4) | Feb 02, 2024 |
| ASRock        | B550M Pro4                  | [ce95a21f31](https://linux-hardware.org/?probe=ce95a21f31) | Feb 01, 2024 |
| ASRock        | X370 Gaming X               | [54fa92de97](https://linux-hardware.org/?probe=54fa92de97) | Feb 01, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [1cee0ab81d](https://linux-hardware.org/?probe=1cee0ab81d) | Feb 01, 2024 |
| ASUSTek       | H110M-A                     | [ef9ec58561](https://linux-hardware.org/?probe=ef9ec58561) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [c85924bf6f](https://linux-hardware.org/?probe=c85924bf6f) | Jan 31, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [aad32e443a](https://linux-hardware.org/?probe=aad32e443a) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [4995dfcd57](https://linux-hardware.org/?probe=4995dfcd57) | Jan 31, 2024 |
| MSI           | MS-7817                     | [e67644d160](https://linux-hardware.org/?probe=e67644d160) | Jan 31, 2024 |
| ASRock        | B550M Pro4                  | [562a7e84b6](https://linux-hardware.org/?probe=562a7e84b6) | Jan 31, 2024 |
| Gigabyte      | B365M DS3H                  | [bb6bab84d0](https://linux-hardware.org/?probe=bb6bab84d0) | Jan 31, 2024 |
| Gigabyte      | B365M DS3H                  | [8a8a84c18b](https://linux-hardware.org/?probe=8a8a84c18b) | Jan 31, 2024 |
| Dell          | 0TY565                      | [7b0be6d329](https://linux-hardware.org/?probe=7b0be6d329) | Jan 31, 2024 |
| Dell          | 0TY565                      | [a1dd2e6d5d](https://linux-hardware.org/?probe=a1dd2e6d5d) | Jan 31, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [2f08f48285](https://linux-hardware.org/?probe=2f08f48285) | Jan 31, 2024 |
| HP            | 8265                        | [77473b5bd8](https://linux-hardware.org/?probe=77473b5bd8) | Jan 30, 2024 |
| HP            | 1495                        | [1c71a50dfc](https://linux-hardware.org/?probe=1c71a50dfc) | Jan 30, 2024 |
| ASUSTek       | H110M-A                     | [e72fb50bf3](https://linux-hardware.org/?probe=e72fb50bf3) | Jan 29, 2024 |
| Dell          | 0M858N A01                  | [ea55d99987](https://linux-hardware.org/?probe=ea55d99987) | Jan 29, 2024 |
| MSI           | P43i                        | [ff8e7e4853](https://linux-hardware.org/?probe=ff8e7e4853) | Jan 29, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [bf9584029c](https://linux-hardware.org/?probe=bf9584029c) | Jan 29, 2024 |
| Gigabyte      | P67A-D3-B3                  | [5241c055ad](https://linux-hardware.org/?probe=5241c055ad) | Jan 29, 2024 |
| ASRock        | B85M                        | [2f1c8ac5f5](https://linux-hardware.org/?probe=2f1c8ac5f5) | Jan 29, 2024 |
| ASUSTek       | PRIME B365M-A               | [f046e20a98](https://linux-hardware.org/?probe=f046e20a98) | Jan 29, 2024 |
| Gigabyte      | H61M-S1                     | [9a7978bd86](https://linux-hardware.org/?probe=9a7978bd86) | Jan 29, 2024 |
| Dell          | 0200DY A03                  | [26d8100c96](https://linux-hardware.org/?probe=26d8100c96) | Jan 28, 2024 |
| Lenovo        | 1036 NO DPK                 | [aa54fcaee1](https://linux-hardware.org/?probe=aa54fcaee1) | Jan 28, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [32a41e8aff](https://linux-hardware.org/?probe=32a41e8aff) | Jan 28, 2024 |
| Gigabyte      | H61M-S2PV                   | [b313d408fc](https://linux-hardware.org/?probe=b313d408fc) | Jan 27, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [f17f689f78](https://linux-hardware.org/?probe=f17f689f78) | Jan 27, 2024 |
| MSI           | MS-7817                     | [53d14e5734](https://linux-hardware.org/?probe=53d14e5734) | Jan 26, 2024 |
| ASUSTek       | P5LD2-X/1333                | [6175179da0](https://linux-hardware.org/?probe=6175179da0) | Jan 26, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [c0926b6944](https://linux-hardware.org/?probe=c0926b6944) | Jan 26, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [fd8742e98a](https://linux-hardware.org/?probe=fd8742e98a) | Jan 26, 2024 |
| Gigabyte      | H61M-S2PV                   | [ec7c2fd28c](https://linux-hardware.org/?probe=ec7c2fd28c) | Jan 26, 2024 |
| HP            | 1497                        | [70ed07412a](https://linux-hardware.org/?probe=70ed07412a) | Jan 26, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [f1397d3500](https://linux-hardware.org/?probe=f1397d3500) | Jan 26, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [919e1d0d1a](https://linux-hardware.org/?probe=919e1d0d1a) | Jan 25, 2024 |
| ASRock        | FM2A75M Pro4+               | [b13e328c84](https://linux-hardware.org/?probe=b13e328c84) | Jan 25, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ecec004de9](https://linux-hardware.org/?probe=ecec004de9) | Jan 25, 2024 |
| ASUSTek       | H110M-K                     | [e187cbf4f0](https://linux-hardware.org/?probe=e187cbf4f0) | Jan 24, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [9aa36d0ef2](https://linux-hardware.org/?probe=9aa36d0ef2) | Jan 24, 2024 |
| Gigabyte      | A520M S2H                   | [3c14c44a2e](https://linux-hardware.org/?probe=3c14c44a2e) | Jan 24, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5cc29f2f4d](https://linux-hardware.org/?probe=5cc29f2f4d) | Jan 24, 2024 |
| Gigabyte      | H97-D3H-CF                  | [5b4d20246c](https://linux-hardware.org/?probe=5b4d20246c) | Jan 23, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [4c6536c12f](https://linux-hardware.org/?probe=4c6536c12f) | Jan 23, 2024 |
| MSI           | P43i                        | [96ed9e6412](https://linux-hardware.org/?probe=96ed9e6412) | Jan 23, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d3cf795f5d](https://linux-hardware.org/?probe=d3cf795f5d) | Jan 22, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [b63d070fe7](https://linux-hardware.org/?probe=b63d070fe7) | Jan 22, 2024 |
| Gigabyte      | H61M-S1                     | [f0a97be10f](https://linux-hardware.org/?probe=f0a97be10f) | Jan 22, 2024 |
| Dell          | 0K240Y A01                  | [ea975a38d2](https://linux-hardware.org/?probe=ea975a38d2) | Jan 22, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [448b20e8f3](https://linux-hardware.org/?probe=448b20e8f3) | Jan 22, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [f18016d0b6](https://linux-hardware.org/?probe=f18016d0b6) | Jan 22, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [f55473c84d](https://linux-hardware.org/?probe=f55473c84d) | Jan 22, 2024 |
| HP            | 0B4Ch D                     | [382a956d11](https://linux-hardware.org/?probe=382a956d11) | Jan 22, 2024 |
| Dell          | 0GY6Y8 A01                  | [70ed7265d7](https://linux-hardware.org/?probe=70ed7265d7) | Jan 22, 2024 |
| HP            | 0B4Ch D                     | [ac643dc1d4](https://linux-hardware.org/?probe=ac643dc1d4) | Jan 21, 2024 |
| ASRock        | N68C-S UCC                  | [dc2724d2ca](https://linux-hardware.org/?probe=dc2724d2ca) | Jan 20, 2024 |
| Medion        | MS-7748                     | [0da6204fe7](https://linux-hardware.org/?probe=0da6204fe7) | Jan 19, 2024 |
| ASUSTek       | PRIME A320M-R               | [314cb08407](https://linux-hardware.org/?probe=314cb08407) | Jan 18, 2024 |
| Lenovo        | 1036 NO DPK                 | [fe04dc8528](https://linux-hardware.org/?probe=fe04dc8528) | Jan 18, 2024 |
| ASRock        | B550M-HDV                   | [382d54efe4](https://linux-hardware.org/?probe=382d54efe4) | Jan 18, 2024 |
| ASRock        | B550M-HDV                   | [f2ae4fae96](https://linux-hardware.org/?probe=f2ae4fae96) | Jan 18, 2024 |
| ASUSTek       | P5LD2-X/1333                | [7670d862e1](https://linux-hardware.org/?probe=7670d862e1) | Jan 17, 2024 |
| ASRock        | FM2A75M Pro4+               | [8b6cc378c3](https://linux-hardware.org/?probe=8b6cc378c3) | Jan 16, 2024 |
| Gigabyte      | H61M-S2PV                   | [3e4a544656](https://linux-hardware.org/?probe=3e4a544656) | Jan 13, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [ea74a34365](https://linux-hardware.org/?probe=ea74a34365) | Jan 13, 2024 |
| ASRock        | B550M Pro4                  | [f4660fbf02](https://linux-hardware.org/?probe=f4660fbf02) | Jan 12, 2024 |
| Gigabyte      | H310M A-CF x.x              | [4b838199f5](https://linux-hardware.org/?probe=4b838199f5) | Jan 11, 2024 |
| Gigabyte      | H310M A-CF x.x              | [cb71ddc06e](https://linux-hardware.org/?probe=cb71ddc06e) | Jan 11, 2024 |
| Medion        | MS-7748                     | [fd6786798c](https://linux-hardware.org/?probe=fd6786798c) | Jan 11, 2024 |
| ASRock        | N68C-S UCC                  | [fb39fef7a4](https://linux-hardware.org/?probe=fb39fef7a4) | Jan 09, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [177fdc1d8d](https://linux-hardware.org/?probe=177fdc1d8d) | Jan 08, 2024 |
| Dell          | 0T0MHW A02                  | [a71fc6258c](https://linux-hardware.org/?probe=a71fc6258c) | Jan 08, 2024 |
| HP            | 339A                        | [7f31e925d5](https://linux-hardware.org/?probe=7f31e925d5) | Jan 07, 2024 |
| Dell          | 0200DY A03                  | [398cb20c88](https://linux-hardware.org/?probe=398cb20c88) | Jan 07, 2024 |
| ASUSTek       | H110M-A                     | [d24e2d377c](https://linux-hardware.org/?probe=d24e2d377c) | Jan 07, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [c5f32d31a4](https://linux-hardware.org/?probe=c5f32d31a4) | Jan 06, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [db15f78582](https://linux-hardware.org/?probe=db15f78582) | Jan 06, 2024 |
| Gigabyte      | GA-MA78GPM-DS2H             | [22e4df864b](https://linux-hardware.org/?probe=22e4df864b) | Jan 06, 2024 |
| HP            | 8265                        | [227d139424](https://linux-hardware.org/?probe=227d139424) | Jan 05, 2024 |
| ASUSTek       | A88XM-E                     | [671224ec71](https://linux-hardware.org/?probe=671224ec71) | Jan 05, 2024 |
| Lenovo        | 312A NOK                    | [0a4ab17035](https://linux-hardware.org/?probe=0a4ab17035) | Jan 05, 2024 |
| Lenovo        | 312A NOK                    | [a6bd11e06b](https://linux-hardware.org/?probe=a6bd11e06b) | Jan 05, 2024 |
| ASRock        | X370 Gaming X               | [b780de408a](https://linux-hardware.org/?probe=b780de408a) | Jan 05, 2024 |
| Dell          | 0M858N A01                  | [115fd937a1](https://linux-hardware.org/?probe=115fd937a1) | Jan 04, 2024 |
| ASRock        | B85M                        | [093643c0f0](https://linux-hardware.org/?probe=093643c0f0) | Jan 04, 2024 |
| ASRock        | G41M-VS3                    | [4a19917cf2](https://linux-hardware.org/?probe=4a19917cf2) | Jan 04, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [d99098989d](https://linux-hardware.org/?probe=d99098989d) | Jan 03, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [76a2205872](https://linux-hardware.org/?probe=76a2205872) | Jan 03, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [74e244eb6c](https://linux-hardware.org/?probe=74e244eb6c) | Jan 02, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [7f438185af](https://linux-hardware.org/?probe=7f438185af) | Jan 02, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [79b5e7c7b0](https://linux-hardware.org/?probe=79b5e7c7b0) | Jan 01, 2024 |
| Gigabyte      | H61M-S1                     | [1e34cd1559](https://linux-hardware.org/?probe=1e34cd1559) | Jan 01, 2024 |
| Gigabyte      | P67A-D3-B3                  | [28494e9d46](https://linux-hardware.org/?probe=28494e9d46) | Jan 01, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [23eb635b4e](https://linux-hardware.org/?probe=23eb635b4e) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-R               | [da76fd5108](https://linux-hardware.org/?probe=da76fd5108) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-R               | [d646e8d5fb](https://linux-hardware.org/?probe=d646e8d5fb) | Jan 01, 2024 |
| MSI           | P43i                        | [a31ae3403f](https://linux-hardware.org/?probe=a31ae3403f) | Dec 31, 2023 |
| MSI           | A320M-A PRO MAX             | [e89341eb95](https://linux-hardware.org/?probe=e89341eb95) | Dec 31, 2023 |
| MSI           | A320M-A PRO MAX             | [b24918bdbc](https://linux-hardware.org/?probe=b24918bdbc) | Dec 31, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [f59bee0805](https://linux-hardware.org/?probe=f59bee0805) | Dec 31, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [99950d43fc](https://linux-hardware.org/?probe=99950d43fc) | Dec 31, 2023 |
| ASUSTek       | H110M-A                     | [f2fd99d70d](https://linux-hardware.org/?probe=f2fd99d70d) | Dec 30, 2023 |
| Dell          | 0TY565                      | [97111d45ea](https://linux-hardware.org/?probe=97111d45ea) | Dec 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6cb0db7e23](https://linux-hardware.org/?probe=6cb0db7e23) | Dec 30, 2023 |
| Gigabyte      | EP31-DS3L                   | [428843cfe5](https://linux-hardware.org/?probe=428843cfe5) | Dec 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a2ba669444](https://linux-hardware.org/?probe=a2ba669444) | Dec 30, 2023 |
| Gigabyte      | H310M A-CF x.x              | [85efe53330](https://linux-hardware.org/?probe=85efe53330) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [d094c3b4e3](https://linux-hardware.org/?probe=d094c3b4e3) | Dec 29, 2023 |
| HP            | 3033h                       | [05bb2e9644](https://linux-hardware.org/?probe=05bb2e9644) | Dec 29, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [780047716e](https://linux-hardware.org/?probe=780047716e) | Dec 29, 2023 |
| ASUSTek       | PRIME A320M-R               | [d5b19de2f0](https://linux-hardware.org/?probe=d5b19de2f0) | Dec 29, 2023 |
| Gigabyte      | H97-D3H-CF                  | [0d64ace463](https://linux-hardware.org/?probe=0d64ace463) | Dec 29, 2023 |
| Gigabyte      | A520M S2H                   | [8cc62b9497](https://linux-hardware.org/?probe=8cc62b9497) | Dec 28, 2023 |
| ASUSTek       | H81M-E                      | [9cd2a6ed45](https://linux-hardware.org/?probe=9cd2a6ed45) | Dec 28, 2023 |
| ASUSTek       | H110M-K                     | [b3a423171f](https://linux-hardware.org/?probe=b3a423171f) | Dec 28, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [5b652d7eba](https://linux-hardware.org/?probe=5b652d7eba) | Dec 28, 2023 |
| HP            | 1495                        | [91f12e4a03](https://linux-hardware.org/?probe=91f12e4a03) | Dec 28, 2023 |
| ASUSTek       | PRIME A320M-R               | [b30cb3fc14](https://linux-hardware.org/?probe=b30cb3fc14) | Dec 28, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [6023618793](https://linux-hardware.org/?probe=6023618793) | Dec 27, 2023 |
| HP            | 1497                        | [9c80dd9de3](https://linux-hardware.org/?probe=9c80dd9de3) | Dec 27, 2023 |
| ASUSTek       | H110M-A                     | [6add1ba46c](https://linux-hardware.org/?probe=6add1ba46c) | Dec 27, 2023 |
| Medion        | MS-7748                     | [029849e475](https://linux-hardware.org/?probe=029849e475) | Dec 27, 2023 |
| Gigabyte      | H61M-S1                     | [e741a22dc6](https://linux-hardware.org/?probe=e741a22dc6) | Dec 27, 2023 |
| Gigabyte      | H61M-S1                     | [ab14001c30](https://linux-hardware.org/?probe=ab14001c30) | Dec 27, 2023 |
| ASUSTek       | H81M-E                      | [55173f5056](https://linux-hardware.org/?probe=55173f5056) | Dec 26, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [8c5b941b48](https://linux-hardware.org/?probe=8c5b941b48) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | [82333229d6](https://linux-hardware.org/?probe=82333229d6) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | [a87c271e68](https://linux-hardware.org/?probe=a87c271e68) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | [30780ea209](https://linux-hardware.org/?probe=30780ea209) | Dec 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [a8007743a8](https://linux-hardware.org/?probe=a8007743a8) | Dec 25, 2023 |
| Gigabyte      | H61M-S2PV                   | [2825577fd0](https://linux-hardware.org/?probe=2825577fd0) | Dec 25, 2023 |
| MSI           | H110M PRO-VD                | [624b1cbd0b](https://linux-hardware.org/?probe=624b1cbd0b) | Dec 24, 2023 |
| Medion        | MS-7748                     | [4df862d09e](https://linux-hardware.org/?probe=4df862d09e) | Dec 24, 2023 |
| MSI           | H110M PRO-VD                | [121d2e0b06](https://linux-hardware.org/?probe=121d2e0b06) | Dec 24, 2023 |
| ASUSTek       | H110M-A                     | [63306d22b2](https://linux-hardware.org/?probe=63306d22b2) | Dec 23, 2023 |
| Gigabyte      | Z390 UD                     | [cd36fc0dc1](https://linux-hardware.org/?probe=cd36fc0dc1) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0bc1c80333](https://linux-hardware.org/?probe=0bc1c80333) | Dec 21, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [544fdd3054](https://linux-hardware.org/?probe=544fdd3054) | Dec 21, 2023 |
| ASUSTek       | H110M-A                     | [3b149d0e20](https://linux-hardware.org/?probe=3b149d0e20) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | [0f7957917e](https://linux-hardware.org/?probe=0f7957917e) | Dec 21, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [d688c80ef7](https://linux-hardware.org/?probe=d688c80ef7) | Dec 18, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [b4c4267477](https://linux-hardware.org/?probe=b4c4267477) | Dec 17, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [4302968166](https://linux-hardware.org/?probe=4302968166) | Dec 17, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0eb62b79e1](https://linux-hardware.org/?probe=0eb62b79e1) | Dec 17, 2023 |
| HP            | 1497                        | [20ba1e3df2](https://linux-hardware.org/?probe=20ba1e3df2) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | [2262526770](https://linux-hardware.org/?probe=2262526770) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | [ed366a10ca](https://linux-hardware.org/?probe=ed366a10ca) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | [9b32bafcb5](https://linux-hardware.org/?probe=9b32bafcb5) | Dec 17, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [6d3774729f](https://linux-hardware.org/?probe=6d3774729f) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF x.x              | [24522df925](https://linux-hardware.org/?probe=24522df925) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF x.x              | [528bd3903d](https://linux-hardware.org/?probe=528bd3903d) | Dec 16, 2023 |
| Lenovo        | 1036 NO DPK                 | [08f10e4a70](https://linux-hardware.org/?probe=08f10e4a70) | Dec 15, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [7701847681](https://linux-hardware.org/?probe=7701847681) | Dec 15, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [470281aedd](https://linux-hardware.org/?probe=470281aedd) | Dec 15, 2023 |
| HP            | 0B4Ch D                     | [e40498b1d1](https://linux-hardware.org/?probe=e40498b1d1) | Dec 14, 2023 |
| HP            | 0B4Ch D                     | [bb8a731dab](https://linux-hardware.org/?probe=bb8a731dab) | Dec 14, 2023 |
| Gigabyte      | B450M GAMING                | [02b6b32440](https://linux-hardware.org/?probe=02b6b32440) | Dec 13, 2023 |
| Gigabyte      | B450M GAMING                | [016f269490](https://linux-hardware.org/?probe=016f269490) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | [d55fed29c1](https://linux-hardware.org/?probe=d55fed29c1) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | [fc0fe04fab](https://linux-hardware.org/?probe=fc0fe04fab) | Dec 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [2199e3dc0f](https://linux-hardware.org/?probe=2199e3dc0f) | Dec 12, 2023 |
| HP            | 3033h                       | [3dddd6881a](https://linux-hardware.org/?probe=3dddd6881a) | Dec 11, 2023 |
| ASRock        | X370 Gaming X               | [3cba3acfa9](https://linux-hardware.org/?probe=3cba3acfa9) | Dec 10, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [840ffb67be](https://linux-hardware.org/?probe=840ffb67be) | Dec 10, 2023 |
| Gigabyte      | H61MA-D3V                   | [1b2d2135d4](https://linux-hardware.org/?probe=1b2d2135d4) | Dec 09, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [8ec0cd2d39](https://linux-hardware.org/?probe=8ec0cd2d39) | Dec 09, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [bdff414c43](https://linux-hardware.org/?probe=bdff414c43) | Dec 09, 2023 |
| MSI           | H110M PRO-VD                | [a691f52012](https://linux-hardware.org/?probe=a691f52012) | Dec 08, 2023 |
| MSI           | H110M PRO-VD                | [aa3ae99bf2](https://linux-hardware.org/?probe=aa3ae99bf2) | Dec 08, 2023 |
| Lenovo        | 1036 NO DPK                 | [6be53926db](https://linux-hardware.org/?probe=6be53926db) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [1c2750202f](https://linux-hardware.org/?probe=1c2750202f) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ba4f3255bc](https://linux-hardware.org/?probe=ba4f3255bc) | Dec 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ae2fdd9470](https://linux-hardware.org/?probe=ae2fdd9470) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | [dc50493c88](https://linux-hardware.org/?probe=dc50493c88) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | [9f5a520013](https://linux-hardware.org/?probe=9f5a520013) | Dec 08, 2023 |
| Dell          | 0TY565                      | [f037c10bc9](https://linux-hardware.org/?probe=f037c10bc9) | Dec 07, 2023 |
| Medion        | MS-7748                     | [1f11eab8f8](https://linux-hardware.org/?probe=1f11eab8f8) | Dec 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [e9436c2809](https://linux-hardware.org/?probe=e9436c2809) | Dec 06, 2023 |
| ASUSTek       | H110M-K                     | [2ebb7abc4c](https://linux-hardware.org/?probe=2ebb7abc4c) | Dec 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d658b900e7](https://linux-hardware.org/?probe=d658b900e7) | Dec 05, 2023 |
| HP            | 1495                        | [626fcfb788](https://linux-hardware.org/?probe=626fcfb788) | Dec 05, 2023 |
| Medion        | MS-7748                     | [8c5106d00b](https://linux-hardware.org/?probe=8c5106d00b) | Dec 05, 2023 |
| ASRock        | 960GC-GS FX                 | [524de55da0](https://linux-hardware.org/?probe=524de55da0) | Dec 04, 2023 |
| HP            | 339A                        | [b596b82bf1](https://linux-hardware.org/?probe=b596b82bf1) | Dec 04, 2023 |
| Dell          | 0PU052                      | [a436be0e88](https://linux-hardware.org/?probe=a436be0e88) | Dec 04, 2023 |
| ASRock        | H310CM-DVS                  | [1bf52989ef](https://linux-hardware.org/?probe=1bf52989ef) | Dec 03, 2023 |
| Gigabyte      | P67A-D3-B3                  | [77472c25c8](https://linux-hardware.org/?probe=77472c25c8) | Dec 03, 2023 |
| ASUSTek       | H110M-K                     | [e21f4b08b1](https://linux-hardware.org/?probe=e21f4b08b1) | Dec 03, 2023 |
| Gigabyte      | Z390 UD                     | [694abd409f](https://linux-hardware.org/?probe=694abd409f) | Dec 03, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [b70c84adcf](https://linux-hardware.org/?probe=b70c84adcf) | Dec 01, 2023 |
| Gigabyte      | A520M S2H                   | [cdfe1883bc](https://linux-hardware.org/?probe=cdfe1883bc) | Nov 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [18ce09355c](https://linux-hardware.org/?probe=18ce09355c) | Nov 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | [875f72f0f7](https://linux-hardware.org/?probe=875f72f0f7) | Nov 28, 2023 |
| Dell          | 0K240Y A01                  | [d5440204b6](https://linux-hardware.org/?probe=d5440204b6) | Nov 28, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [05686c86bb](https://linux-hardware.org/?probe=05686c86bb) | Nov 28, 2023 |
| MSI           | P43i                        | [3291b84f5e](https://linux-hardware.org/?probe=3291b84f5e) | Nov 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | [5e1e9b6a9e](https://linux-hardware.org/?probe=5e1e9b6a9e) | Nov 27, 2023 |
| Gigabyte      | 970A-UD3P                   | [206d92bed2](https://linux-hardware.org/?probe=206d92bed2) | Nov 27, 2023 |
| Gigabyte      | 970A-UD3P                   | [bd533274c5](https://linux-hardware.org/?probe=bd533274c5) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [159ce7eba2](https://linux-hardware.org/?probe=159ce7eba2) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfc194ba14](https://linux-hardware.org/?probe=bfc194ba14) | Nov 27, 2023 |
| ASRock        | B85M                        | [0d3f6ceeea](https://linux-hardware.org/?probe=0d3f6ceeea) | Nov 27, 2023 |
| MSI           | H61M-P21                    | [5c106c49f4](https://linux-hardware.org/?probe=5c106c49f4) | Nov 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [1e0fa8c965](https://linux-hardware.org/?probe=1e0fa8c965) | Nov 27, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [c9dd5240c4](https://linux-hardware.org/?probe=c9dd5240c4) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | [4618c61b6c](https://linux-hardware.org/?probe=4618c61b6c) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | [bb4bd3eceb](https://linux-hardware.org/?probe=bb4bd3eceb) | Nov 26, 2023 |
| ASRock        | G41M-VS3                    | [c2e61e0cf9](https://linux-hardware.org/?probe=c2e61e0cf9) | Nov 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [200ddef2b0](https://linux-hardware.org/?probe=200ddef2b0) | Nov 26, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [250bd9f1df](https://linux-hardware.org/?probe=250bd9f1df) | Nov 26, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | [61b5003420](https://linux-hardware.org/?probe=61b5003420) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | [c02d4a69b7](https://linux-hardware.org/?probe=c02d4a69b7) | Nov 25, 2023 |
| Gigabyte      | J4005ND2P-CF                | [04b5574c35](https://linux-hardware.org/?probe=04b5574c35) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [86b63c1acf](https://linux-hardware.org/?probe=86b63c1acf) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [8c071d6cda](https://linux-hardware.org/?probe=8c071d6cda) | Nov 24, 2023 |
| ASRock        | B550M Pro4                  | [4a05411844](https://linux-hardware.org/?probe=4a05411844) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-R               | [cbdb153211](https://linux-hardware.org/?probe=cbdb153211) | Nov 24, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [aed927ecb5](https://linux-hardware.org/?probe=aed927ecb5) | Nov 24, 2023 |
| Gigabyte      | H61M-S1                     | [38e1d661bf](https://linux-hardware.org/?probe=38e1d661bf) | Nov 23, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [977d9e09f1](https://linux-hardware.org/?probe=977d9e09f1) | Nov 23, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [b99f6e4f94](https://linux-hardware.org/?probe=b99f6e4f94) | Nov 23, 2023 |
| HP            | 1494                        | [3ff4bec1f2](https://linux-hardware.org/?probe=3ff4bec1f2) | Nov 23, 2023 |
| HP            | 1495                        | [630e59993e](https://linux-hardware.org/?probe=630e59993e) | Nov 23, 2023 |
| Dell          | 0TY565                      | [bf643a514f](https://linux-hardware.org/?probe=bf643a514f) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [d2a213e349](https://linux-hardware.org/?probe=d2a213e349) | Nov 21, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [d5cdc3089f](https://linux-hardware.org/?probe=d5cdc3089f) | Nov 21, 2023 |
| Dell          | 0XPDFK A00                  | [280e97cc34](https://linux-hardware.org/?probe=280e97cc34) | Nov 20, 2023 |
| Gigabyte      | B450M GAMING                | [dbf835efbb](https://linux-hardware.org/?probe=dbf835efbb) | Nov 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [795b0f6741](https://linux-hardware.org/?probe=795b0f6741) | Nov 16, 2023 |
| Dell          | 0TY565                      | [bd5ec5457e](https://linux-hardware.org/?probe=bd5ec5457e) | Nov 16, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [c79a431698](https://linux-hardware.org/?probe=c79a431698) | Nov 15, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d5cb68f63d](https://linux-hardware.org/?probe=d5cb68f63d) | Nov 12, 2023 |
| ASUSTek       | PRIME A320M-R               | [e02cd94d67](https://linux-hardware.org/?probe=e02cd94d67) | Nov 10, 2023 |
| ASUSTek       | PRIME A320M-R               | [ce2c43cb86](https://linux-hardware.org/?probe=ce2c43cb86) | Nov 10, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [f45397a161](https://linux-hardware.org/?probe=f45397a161) | Nov 09, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [5e0d19391e](https://linux-hardware.org/?probe=5e0d19391e) | Nov 09, 2023 |
| ASUSTek       | PRIME B365M-A               | [1399a1f267](https://linux-hardware.org/?probe=1399a1f267) | Nov 09, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [4c8dc5f59a](https://linux-hardware.org/?probe=4c8dc5f59a) | Nov 08, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [420d0d1ddc](https://linux-hardware.org/?probe=420d0d1ddc) | Nov 08, 2023 |
| Lenovo        | 1036 NO DPK                 | [ae88c578fa](https://linux-hardware.org/?probe=ae88c578fa) | Nov 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9c7020c9cc](https://linux-hardware.org/?probe=9c7020c9cc) | Nov 08, 2023 |
| Lenovo        | SDK0E50510 WIN              | [72a7ba6dde](https://linux-hardware.org/?probe=72a7ba6dde) | Nov 08, 2023 |
| Gigabyte      | H61M-S1                     | [ef707f88ea](https://linux-hardware.org/?probe=ef707f88ea) | Nov 08, 2023 |
| ASUSTek       | PRIME B365M-A               | [813b0c06e0](https://linux-hardware.org/?probe=813b0c06e0) | Nov 08, 2023 |
| Gigabyte      | H61M-S1                     | [68f36bd8cc](https://linux-hardware.org/?probe=68f36bd8cc) | Nov 08, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0d04acd22d](https://linux-hardware.org/?probe=0d04acd22d) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [982bf3ea4c](https://linux-hardware.org/?probe=982bf3ea4c) | Nov 07, 2023 |
| Dell          | 0TY565                      | [086bd4ec8f](https://linux-hardware.org/?probe=086bd4ec8f) | Nov 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [6e0b8b9df9](https://linux-hardware.org/?probe=6e0b8b9df9) | Nov 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [038e8719ec](https://linux-hardware.org/?probe=038e8719ec) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | [1e59a67f24](https://linux-hardware.org/?probe=1e59a67f24) | Nov 05, 2023 |
| HP            | 8265                        | [f6b38e869b](https://linux-hardware.org/?probe=f6b38e869b) | Nov 04, 2023 |
| HP            | 8265                        | [49cb61db2e](https://linux-hardware.org/?probe=49cb61db2e) | Nov 04, 2023 |
| Dell          | 0VHWTR A02                  | [7663b608dd](https://linux-hardware.org/?probe=7663b608dd) | Nov 03, 2023 |
| Gigabyte      | H61M-S1                     | [3b14b40bc9](https://linux-hardware.org/?probe=3b14b40bc9) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0af35bd53b](https://linux-hardware.org/?probe=0af35bd53b) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [32a001fb07](https://linux-hardware.org/?probe=32a001fb07) | Nov 02, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [dacdb79776](https://linux-hardware.org/?probe=dacdb79776) | Nov 01, 2023 |
| Gigabyte      | EP31-DS3L                   | [0a33a8b925](https://linux-hardware.org/?probe=0a33a8b925) | Nov 01, 2023 |
| MSI           | P43i                        | [847f1890e2](https://linux-hardware.org/?probe=847f1890e2) | Nov 01, 2023 |
| Dell          | 0RN474                      | [0ae8ddb9b3](https://linux-hardware.org/?probe=0ae8ddb9b3) | Nov 01, 2023 |
| ASRock        | G41M-VS3                    | [1d5b98622d](https://linux-hardware.org/?probe=1d5b98622d) | Oct 31, 2023 |
| ASRock        | G41M-VS3                    | [1a0da2bf85](https://linux-hardware.org/?probe=1a0da2bf85) | Oct 31, 2023 |
| Gigabyte      | H81M-HD3                    | [5f6ce5dbfb](https://linux-hardware.org/?probe=5f6ce5dbfb) | Oct 31, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [4cf4e845eb](https://linux-hardware.org/?probe=4cf4e845eb) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | [1813899897](https://linux-hardware.org/?probe=1813899897) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | [6cf499a771](https://linux-hardware.org/?probe=6cf499a771) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | [2a5fda7baf](https://linux-hardware.org/?probe=2a5fda7baf) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | [7d99dba1af](https://linux-hardware.org/?probe=7d99dba1af) | Oct 30, 2023 |
| ASUSTek       | H81M-E                      | [b48b015b4c](https://linux-hardware.org/?probe=b48b015b4c) | Oct 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [2c3cefb71a](https://linux-hardware.org/?probe=2c3cefb71a) | Oct 28, 2023 |
| MSI           | MS-7817                     | [06344ac320](https://linux-hardware.org/?probe=06344ac320) | Oct 27, 2023 |
| MSI           | MS-7817                     | [dc9cc99096](https://linux-hardware.org/?probe=dc9cc99096) | Oct 27, 2023 |
| ASUSTek       | PRIME A320M-R               | [0306fca319](https://linux-hardware.org/?probe=0306fca319) | Oct 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [b58a3b7e3a](https://linux-hardware.org/?probe=b58a3b7e3a) | Oct 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [220d49592e](https://linux-hardware.org/?probe=220d49592e) | Oct 26, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [64693f6b03](https://linux-hardware.org/?probe=64693f6b03) | Oct 26, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [7a96d2e495](https://linux-hardware.org/?probe=7a96d2e495) | Oct 26, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [828dbad92c](https://linux-hardware.org/?probe=828dbad92c) | Oct 25, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [4f6c606196](https://linux-hardware.org/?probe=4f6c606196) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [7e2c80a1d7](https://linux-hardware.org/?probe=7e2c80a1d7) | Oct 24, 2023 |
| HP            | 339A                        | [119fec0a9d](https://linux-hardware.org/?probe=119fec0a9d) | Oct 24, 2023 |
| HP            | 339A                        | [b35bc69c82](https://linux-hardware.org/?probe=b35bc69c82) | Oct 24, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [50bdbf100d](https://linux-hardware.org/?probe=50bdbf100d) | Oct 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3824135292](https://linux-hardware.org/?probe=3824135292) | Oct 23, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [875d62cbac](https://linux-hardware.org/?probe=875d62cbac) | Oct 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a7a49e3d3f](https://linux-hardware.org/?probe=a7a49e3d3f) | Oct 23, 2023 |
| Gigabyte      | Z390 UD                     | [c926b51230](https://linux-hardware.org/?probe=c926b51230) | Oct 22, 2023 |
| Gigabyte      | Z390 UD                     | [ce8bac4075](https://linux-hardware.org/?probe=ce8bac4075) | Oct 22, 2023 |
| Dell          | 0D883F A06                  | [f687230e43](https://linux-hardware.org/?probe=f687230e43) | Oct 21, 2023 |
| ASUSTek       | H110M-A                     | [2cff132417](https://linux-hardware.org/?probe=2cff132417) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | [dad965a109](https://linux-hardware.org/?probe=dad965a109) | Oct 19, 2023 |
| Lenovo        | 1036 NO DPK                 | [0733e9c4ae](https://linux-hardware.org/?probe=0733e9c4ae) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | [8ca65eabee](https://linux-hardware.org/?probe=8ca65eabee) | Oct 19, 2023 |
| MSI           | H61M-P21                    | [ba5fb8f49c](https://linux-hardware.org/?probe=ba5fb8f49c) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | [330170d5d7](https://linux-hardware.org/?probe=330170d5d7) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | [e6840ccb2f](https://linux-hardware.org/?probe=e6840ccb2f) | Oct 19, 2023 |
| Dell          | 0K240Y A01                  | [e57b8986ab](https://linux-hardware.org/?probe=e57b8986ab) | Oct 18, 2023 |
| Gigabyte      | J4005ND2P-CF                | [23efcaf7a2](https://linux-hardware.org/?probe=23efcaf7a2) | Oct 18, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [ce65c73e40](https://linux-hardware.org/?probe=ce65c73e40) | Oct 18, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [64e28141f8](https://linux-hardware.org/?probe=64e28141f8) | Oct 17, 2023 |
| HP            | 8265                        | [4e8e0ea26a](https://linux-hardware.org/?probe=4e8e0ea26a) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9e3034f710](https://linux-hardware.org/?probe=9e3034f710) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [ea34b890ed](https://linux-hardware.org/?probe=ea34b890ed) | Oct 17, 2023 |
| HP            | 8265                        | [8f4c84f4f4](https://linux-hardware.org/?probe=8f4c84f4f4) | Oct 16, 2023 |
| ASUSTek       | PRIME B365M-A               | [b7fb2c5300](https://linux-hardware.org/?probe=b7fb2c5300) | Oct 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [707b8c0acd](https://linux-hardware.org/?probe=707b8c0acd) | Oct 15, 2023 |
| ASUSTek       | PRIME B365M-A               | [59a2975041](https://linux-hardware.org/?probe=59a2975041) | Oct 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [2c2a10deb9](https://linux-hardware.org/?probe=2c2a10deb9) | Oct 12, 2023 |
| ASRock        | H310CM-DVS                  | [1ae8fcd28c](https://linux-hardware.org/?probe=1ae8fcd28c) | Oct 12, 2023 |
| Medion        | MS-7748                     | [8b625acaae](https://linux-hardware.org/?probe=8b625acaae) | Oct 12, 2023 |
| Pegatron      | 2AB6                        | [50fbeed34d](https://linux-hardware.org/?probe=50fbeed34d) | Oct 11, 2023 |
| Pegatron      | 2AB6                        | [e97e82006c](https://linux-hardware.org/?probe=e97e82006c) | Oct 11, 2023 |
| Dell          | 0D883F A06                  | [d1e2846467](https://linux-hardware.org/?probe=d1e2846467) | Oct 11, 2023 |
| HP            | 0AA8h                       | [5b821194a7](https://linux-hardware.org/?probe=5b821194a7) | Oct 11, 2023 |
| HP            | 0AA8h                       | [d88c5dced7](https://linux-hardware.org/?probe=d88c5dced7) | Oct 11, 2023 |
| MSI           | MS-7817                     | [ed5e21c562](https://linux-hardware.org/?probe=ed5e21c562) | Oct 10, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [abca75fa11](https://linux-hardware.org/?probe=abca75fa11) | Oct 10, 2023 |
| eMachines     | EL1358G                     | [0548d7e6c7](https://linux-hardware.org/?probe=0548d7e6c7) | Oct 10, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [2cba957b98](https://linux-hardware.org/?probe=2cba957b98) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | [be9975c532](https://linux-hardware.org/?probe=be9975c532) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | [c3d3003248](https://linux-hardware.org/?probe=c3d3003248) | Oct 09, 2023 |
| Gigabyte      | P67A-D3-B3                  | [d935714c39](https://linux-hardware.org/?probe=d935714c39) | Oct 08, 2023 |
| MSI           | H97 GUARD-PRO               | [ffb2b71ce7](https://linux-hardware.org/?probe=ffb2b71ce7) | Oct 07, 2023 |
| ASUSTek       | H110M-K                     | [5fad8d4e39](https://linux-hardware.org/?probe=5fad8d4e39) | Oct 07, 2023 |
| MSI           | H97 GUARD-PRO               | [047ec55668](https://linux-hardware.org/?probe=047ec55668) | Oct 07, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [29adc32704](https://linux-hardware.org/?probe=29adc32704) | Oct 07, 2023 |
| ASRock        | 775i945GZ                   | [ef1dd349c2](https://linux-hardware.org/?probe=ef1dd349c2) | Oct 07, 2023 |
| ASRock        | 775i945GZ                   | [168713fd05](https://linux-hardware.org/?probe=168713fd05) | Oct 07, 2023 |
| ASUSTek       | PRIME A320M-R               | [2043b1ed85](https://linux-hardware.org/?probe=2043b1ed85) | Oct 07, 2023 |
| Gigabyte      | H61MA-D3V                   | [53f61c91bf](https://linux-hardware.org/?probe=53f61c91bf) | Oct 07, 2023 |
| Lenovo        | SDK0E50510 WIN              | [ceaac5726a](https://linux-hardware.org/?probe=ceaac5726a) | Oct 07, 2023 |
| ASUSTek       | H110M-A                     | [a2cc2d051e](https://linux-hardware.org/?probe=a2cc2d051e) | Oct 06, 2023 |
| Gigabyte      | B75M-D3H                    | [c585e7e5c4](https://linux-hardware.org/?probe=c585e7e5c4) | Oct 06, 2023 |
| Gigabyte      | B75M-D3H                    | [276b8cea5f](https://linux-hardware.org/?probe=276b8cea5f) | Oct 06, 2023 |
| Gigabyte      | Z390 UD                     | [539e4b56a6](https://linux-hardware.org/?probe=539e4b56a6) | Oct 06, 2023 |
| Medion        | MS-7748                     | [01b345394a](https://linux-hardware.org/?probe=01b345394a) | Oct 06, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [9e00c6f4b0](https://linux-hardware.org/?probe=9e00c6f4b0) | Oct 06, 2023 |
| HP            | 8265                        | [6fffe02648](https://linux-hardware.org/?probe=6fffe02648) | Oct 05, 2023 |
| HP            | 8265                        | [fe09b6a8e0](https://linux-hardware.org/?probe=fe09b6a8e0) | Oct 04, 2023 |
| ASUSTek       | PRIME A320M-R               | [d247c129c4](https://linux-hardware.org/?probe=d247c129c4) | Oct 04, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [d6cc456788](https://linux-hardware.org/?probe=d6cc456788) | Oct 04, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [78c456d55d](https://linux-hardware.org/?probe=78c456d55d) | Oct 04, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [2c0427d154](https://linux-hardware.org/?probe=2c0427d154) | Oct 03, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [0a765bb242](https://linux-hardware.org/?probe=0a765bb242) | Oct 03, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [ee08a8d73a](https://linux-hardware.org/?probe=ee08a8d73a) | Oct 02, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [913fafd8a7](https://linux-hardware.org/?probe=913fafd8a7) | Oct 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | [c64f3bbdbd](https://linux-hardware.org/?probe=c64f3bbdbd) | Oct 02, 2023 |
| HP            | 1494                        | [1c5842d2b7](https://linux-hardware.org/?probe=1c5842d2b7) | Oct 01, 2023 |
| HP            | 1494                        | [4ffbf86079](https://linux-hardware.org/?probe=4ffbf86079) | Oct 01, 2023 |
| HP            | 339A                        | [cd104d3996](https://linux-hardware.org/?probe=cd104d3996) | Oct 01, 2023 |
| HP            | 1494                        | [5250e1dc1c](https://linux-hardware.org/?probe=5250e1dc1c) | Oct 01, 2023 |
| Gigabyte      | Z390 UD                     | [e470a4941a](https://linux-hardware.org/?probe=e470a4941a) | Oct 01, 2023 |
| Gigabyte      | Z390 UD                     | [864f9a143f](https://linux-hardware.org/?probe=864f9a143f) | Sep 30, 2023 |
| ASRock        | B550M Pro4                  | [a355202f8a](https://linux-hardware.org/?probe=a355202f8a) | Sep 28, 2023 |
| ASRock        | X370 Gaming X               | [ee8f74ab5e](https://linux-hardware.org/?probe=ee8f74ab5e) | Sep 27, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [4cbe33187c](https://linux-hardware.org/?probe=4cbe33187c) | Sep 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [a3fc0915cd](https://linux-hardware.org/?probe=a3fc0915cd) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | [3ffed1f144](https://linux-hardware.org/?probe=3ffed1f144) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | [e6eff7d60d](https://linux-hardware.org/?probe=e6eff7d60d) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [263bf34c40](https://linux-hardware.org/?probe=263bf34c40) | Sep 25, 2023 |
| Dell          | 0200DY A02                  | [0ecd2d60b4](https://linux-hardware.org/?probe=0ecd2d60b4) | Sep 25, 2023 |
| MSI           | B85M-E33                    | [1e246dda8b](https://linux-hardware.org/?probe=1e246dda8b) | Sep 25, 2023 |
| HP            | 09F8h                       | [3d8c4a9ace](https://linux-hardware.org/?probe=3d8c4a9ace) | Sep 25, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/BlackPanther/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| BlackPanther 18.1 | 1420     | 89.31%  |
| BlackPanther 22.1 | 89       | 5.6%    |
| BlackPanther 16.2 | 79       | 4.97%   |
| BlackPanther 16.1 | 2        | 0.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| BlackPanther | 1540     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 4.18.16-desktop-1bP     | 1024     | 57.24%  |
| 5.6.14-desktop-2bP      | 415      | 23.2%   |
| 5.15.85-desktop-1bP     | 105      | 5.87%   |
| 4.9.20-desktop-pae-1bP  | 69       | 3.86%   |
| 5.1.15-desktop-1bP      | 40       | 2.24%   |
| 6.6.32-power-1bP        | 34       | 1.9%    |
| 6.3.8-desktop-1bP       | 32       | 1.79%   |
| 6.3.3-desktop-1bP       | 16       | 0.89%   |
| 6.6.34-power-1bP        | 8        | 0.45%   |
| 6.4.3-desktop-1bP       | 8        | 0.45%   |
| 4.7.0-desktop-1bP       | 6        | 0.34%   |
| 6.2.9-desktop-1bP       | 4        | 0.22%   |
| 6.7.0-power-2bP         | 3        | 0.17%   |
| 4.9.20-desktop-1bP      | 3        | 0.17%   |
| 6.9.3-power-1bP         | 2        | 0.11%   |
| 6.8.9-power-1bP         | 2        | 0.11%   |
| 6.7.2-tkg-pds           | 2        | 0.11%   |
| 6.7.0-rc4-tkg-eevdf     | 2        | 0.11%   |
| 6.5.7-power-1bP         | 2        | 0.11%   |
| 6.9.5-power-1bP         | 1        | 0.06%   |
| 6.7.3_tkg_eevdf         | 1        | 0.06%   |
| 6.11.4-power-1bP        | 1        | 0.06%   |
| 6.10.3-server-1bP       | 1        | 0.06%   |
| 6.1.0-1bP               | 1        | 0.06%   |
| 5.6.14-server-2bP       | 1        | 0.06%   |
| 5.15.83-1-lts           | 1        | 0.06%   |
| 5.10.1-desktop-2bP      | 1        | 0.06%   |
| 5.1.15-server-1bP       | 1        | 0.06%   |
| 4.19.0-6-amd64          | 1        | 0.06%   |
| 4.14.14-desktop-pae-1bP | 1        | 0.06%   |
| 3.13.0-35-generic       | 1        | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.16 | 1024     | 57.24%  |
| 5.6.14  | 416      | 23.25%  |
| 5.15.85 | 105      | 5.87%   |
| 4.9.20  | 72       | 4.02%   |
| 5.1.15  | 41       | 2.29%   |
| 6.6.32  | 34       | 1.9%    |
| 6.3.8   | 32       | 1.79%   |
| 6.3.3   | 16       | 0.89%   |
| 6.6.34  | 8        | 0.45%   |
| 6.4.3   | 8        | 0.45%   |
| 4.7.0   | 6        | 0.34%   |
| 6.7.0   | 5        | 0.28%   |
| 6.2.9   | 4        | 0.22%   |
| 6.9.3   | 2        | 0.11%   |
| 6.8.9   | 2        | 0.11%   |
| 6.7.2   | 2        | 0.11%   |
| 6.5.7   | 2        | 0.11%   |
| 6.9.5   | 1        | 0.06%   |
| 6.7.3   | 1        | 0.06%   |
| 6.11.4  | 1        | 0.06%   |
| 6.10.3  | 1        | 0.06%   |
| 6.1.0   | 1        | 0.06%   |
| 5.15.83 | 1        | 0.06%   |
| 5.10.1  | 1        | 0.06%   |
| 4.19.0  | 1        | 0.06%   |
| 4.14.14 | 1        | 0.06%   |
| 3.13.0  | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 1024     | 57.53%  |
| 5.6     | 416      | 23.37%  |
| 5.15    | 106      | 5.96%   |
| 4.9     | 72       | 4.04%   |
| 6.3     | 44       | 2.47%   |
| 5.1     | 41       | 2.3%    |
| 6.6     | 38       | 2.13%   |
| 6.4     | 8        | 0.45%   |
| 6.7     | 7        | 0.39%   |
| 4.7     | 6        | 0.34%   |
| 6.2     | 4        | 0.22%   |
| 6.9     | 3        | 0.17%   |
| 6.8     | 2        | 0.11%   |
| 6.5     | 2        | 0.11%   |
| 6.11    | 1        | 0.06%   |
| 6.10    | 1        | 0.06%   |
| 6.1     | 1        | 0.06%   |
| 5.10    | 1        | 0.06%   |
| 4.19    | 1        | 0.06%   |
| 4.14    | 1        | 0.06%   |
| 3.13    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1484     | 94.95%  |
| i686   | 78       | 4.99%   |
| unknow | 1        | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 1463     | 94.75%  |
| Unknown | 80       | 5.18%   |
| KDE     | 1        | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1530     | 98.9%   |
| Wayland | 16       | 1.03%   |
| Tty     | 1        | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 1536     | 99.55%  |
| Unknown | 7        | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1538     | 99.74%  |
| hu_HU   | 3        | 0.19%   |
| en_AU   | 1        | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1160     | 71.6%   |
| EFI  | 460      | 28.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 1073     | 60.62%  |
| Ext4    | 675      | 38.14%  |
| Btrfs   | 10       | 0.56%   |
| Unknown | 5        | 0.28%   |
| Ext3    | 4        | 0.23%   |
| Ext2    | 2        | 0.11%   |
| Ntfs    | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 1037     | 63.04%  |
| GPT     | 586      | 35.62%  |
| Unknown | 22       | 1.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1030     | 59.23%  |
| Yes       | 709      | 40.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 926      | 54.5%   |
| No        | 773      | 45.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Gigabyte Technology            | 286      | 18.57%  |
| ASUSTek Computer               | 276      | 17.92%  |
| ASRock                         | 228      | 14.81%  |
| Dell                           | 173      | 11.23%  |
| Hewlett-Packard                | 151      | 9.81%   |
| MSI                            | 106      | 6.88%   |
| Lenovo                         | 86       | 5.58%   |
| Fujitsu                        | 45       | 2.92%   |
| Acer                           | 27       | 1.75%   |
| Fujitsu Siemens                | 24       | 1.56%   |
| Intel                          | 21       | 1.36%   |
| Foxconn                        | 19       | 1.23%   |
| Medion                         | 12       | 0.78%   |
| Pegatron                       | 11       | 0.71%   |
| Unknown                        | 10       | 0.65%   |
| Biostar                        | 7        | 0.45%   |
| Shuttle                        | 6        | 0.39%   |
| Huanan                         | 6        | 0.39%   |
| Gateway                        | 5        | 0.32%   |
| ECS                            | 5        | 0.32%   |
| Sapphire                       | 3        | 0.19%   |
| Packard Bell                   | 3        | 0.19%   |
| ABIT                           | 3        | 0.19%   |
| Supermicro                     | 2        | 0.13%   |
| Nvidia                         | 2        | 0.13%   |
| AMD                            | 2        | 0.13%   |
| ZOTAC                          | 1        | 0.06%   |
| Wincor Nixdorf                 | 1        | 0.06%   |
| ViewSonic                      | 1        | 0.06%   |
| TYAN Computer                  | 1        | 0.06%   |
| Shanghai Zhaoxin Semiconductor | 1        | 0.06%   |
| Qbex                           | 1        | 0.06%   |
| PCWare                         | 1        | 0.06%   |
| PCSMART                        | 1        | 0.06%   |
| NEC Computers                  | 1        | 0.06%   |
| MouseComputer                  | 1        | 0.06%   |
| Login Informatica              | 1        | 0.06%   |
| Lex                            | 1        | 0.06%   |
| Itautec                        | 1        | 0.06%   |
| IBM                            | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASRock FM2A75M Pro4+               | 32       | 2.08%   |
| ASUS All Series                    | 28       | 1.82%   |
| Dell OptiPlex 3020                 | 19       | 1.23%   |
| Dell OptiPlex 780                  | 14       | 0.91%   |
| Dell OptiPlex 760                  | 13       | 0.84%   |
| Dell OptiPlex 755                  | 13       | 0.84%   |
| Unknown                            | 13       | 0.84%   |
| Gigabyte H61M-S1                   | 12       | 0.78%   |
| Gigabyte G31M-ES2L                 | 11       | 0.71%   |
| ASUS P5KPL-AM EPU                  | 10       | 0.65%   |
| MSI MS-7680                        | 9        | 0.58%   |
| Lenovo ThinkStation D20 4158AF8    | 9        | 0.58%   |
| HP ProDesk 600 G2 SFF              | 9        | 0.58%   |
| Dell OptiPlex 745                  | 9        | 0.58%   |
| ASRock G41M-VS3                    | 9        | 0.58%   |
| HP Compaq 8000 Elite SFF PC        | 8        | 0.52%   |
| Dell OptiPlex 7010                 | 8        | 0.52%   |
| MSI MS-7817                        | 7        | 0.45%   |
| HP Compaq dc5800 Small Form Factor | 7        | 0.45%   |
| Gigabyte Z390 UD                   | 7        | 0.45%   |
| Gigabyte 970A-DS3P                 | 7        | 0.45%   |
| MSI MS-7C91                        | 6        | 0.39%   |
| MSI MS-7721                        | 6        | 0.39%   |
| MSI MS-7592                        | 6        | 0.39%   |
| Dell OptiPlex 390                  | 6        | 0.39%   |
| ASRock N68C-S UCC                  | 6        | 0.39%   |
| HP EliteDesk 705 G3 SFF            | 5        | 0.32%   |
| HP Compaq Pro 6300 SFF             | 5        | 0.32%   |
| HP Compaq Pro 6300 MT              | 5        | 0.32%   |
| HP Compaq Elite 8300 SFF           | 5        | 0.32%   |
| HP Compaq dc5850 Small Form Factor | 5        | 0.32%   |
| HP Compaq 6200 Pro MT PC           | 5        | 0.32%   |
| HP Compaq 6005 Pro SFF PC          | 5        | 0.32%   |
| Gigabyte G31M-ES2C                 | 5        | 0.32%   |
| Gigabyte F2A88XM-HD3               | 5        | 0.32%   |
| Foxconn Pro 3500 Series            | 5        | 0.32%   |
| Dell Precision WorkStation T3500   | 5        | 0.32%   |
| Dell OptiPlex 9020                 | 5        | 0.32%   |
| Dell OptiPlex 790                  | 5        | 0.32%   |
| Dell OptiPlex 740 Enhanced         | 5        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 143      | 9.29%   |
| HP Compaq               | 104      | 6.75%   |
| Lenovo ThinkCentre      | 55       | 3.57%   |
| ASUS PRIME              | 41       | 2.66%   |
| Fujitsu ESPRIMO         | 34       | 2.21%   |
| ASRock FM2A75M          | 32       | 2.08%   |
| ASUS All                | 28       | 1.82%   |
| Fujitsu Siemens ESPRIMO | 17       | 1.1%    |
| Lenovo ThinkStation     | 16       | 1.04%   |
| HP ProDesk              | 16       | 1.04%   |
| ASUS P5KPL-AM           | 16       | 1.04%   |
| Unknown                 | 13       | 0.84%   |
| Gigabyte H61M-S1        | 12       | 0.78%   |
| Dell Precision          | 12       | 0.78%   |
| ASUS ROG                | 12       | 0.78%   |
| Acer Veriton            | 12       | 0.78%   |
| HP EliteDesk            | 11       | 0.71%   |
| Gigabyte G31M-ES2L      | 11       | 0.71%   |
| ASUS M5A97              | 10       | 0.65%   |
| Acer Aspire             | 10       | 0.65%   |
| MSI MS-7680             | 9        | 0.58%   |
| ASRock G41M-VS3         | 9        | 0.58%   |
| Gigabyte Z390           | 8        | 0.52%   |
| Gigabyte H310M          | 8        | 0.52%   |
| Gigabyte B450           | 8        | 0.52%   |
| ASUS M5A78L-M           | 8        | 0.52%   |
| ASRock 970              | 8        | 0.52%   |
| MSI MS-7817             | 7        | 0.45%   |
| Gigabyte 970A-DS3P      | 7        | 0.45%   |
| Fujitsu CELSIUS         | 7        | 0.45%   |
| ASUS H110M-A            | 7        | 0.45%   |
| ASRock N68C-S           | 7        | 0.45%   |
| MSI MS-7C91             | 6        | 0.39%   |
| MSI MS-7721             | 6        | 0.39%   |
| MSI MS-7592             | 6        | 0.39%   |
| Huanan X99-QD4          | 6        | 0.39%   |
| Gigabyte B450M          | 6        | 0.39%   |
| Foxconn Pro             | 6        | 0.39%   |
| Dell Vostro             | 6        | 0.39%   |
| Gigabyte X570           | 5        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 159      | 10.32%  |
| 2013 | 158      | 10.26%  |
| 2009 | 152      | 9.87%   |
| 2010 | 143      | 9.29%   |
| 2011 | 133      | 8.64%   |
| 2008 | 132      | 8.57%   |
| 2014 | 131      | 8.51%   |
| 2007 | 112      | 7.27%   |
| 2018 | 87       | 5.65%   |
| 2015 | 73       | 4.74%   |
| 2016 | 52       | 3.38%   |
| 2017 | 50       | 3.25%   |
| 2006 | 44       | 2.86%   |
| 2019 | 43       | 2.79%   |
| 2020 | 27       | 1.75%   |
| 2021 | 15       | 0.97%   |
| 2005 | 15       | 0.97%   |
| 2022 | 4        | 0.26%   |
| 2004 | 4        | 0.26%   |
| 2024 | 3        | 0.19%   |
| 2023 | 2        | 0.13%   |
| 2003 | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1540     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1540     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1540     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 461      | 28.53%  |
| 8.01-16.0   | 414      | 25.62%  |
| 4.01-8.0    | 261      | 16.15%  |
| 16.01-24.0  | 214      | 13.24%  |
| 1.01-2.0    | 131      | 8.11%   |
| 32.01-64.0  | 63       | 3.9%    |
| 2.01-3.0    | 30       | 1.86%   |
| 24.01-32.0  | 25       | 1.55%   |
| 0.51-1.0    | 12       | 0.74%   |
| 64.01-256.0 | 5        | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 720      | 37.87%  |
| 0.51-1.0  | 679      | 35.72%  |
| 1.01-2.0  | 382      | 20.09%  |
| 2.01-3.0  | 87       | 4.58%   |
| 3.01-4.0  | 19       | 1%      |
| 4.01-8.0  | 12       | 0.63%   |
| 8.01-16.0 | 1        | 0.05%   |
| Unknown   | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 904      | 52.13%  |
| 2      | 447      | 25.78%  |
| 3      | 207      | 11.94%  |
| 4      | 80       | 4.61%   |
| 5      | 40       | 2.31%   |
| 0      | 37       | 2.13%   |
| 6      | 10       | 0.58%   |
| 9      | 3        | 0.17%   |
| 10     | 2        | 0.12%   |
| 8      | 2        | 0.12%   |
| 7      | 2        | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1039     | 64.53%  |
| No        | 571      | 35.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1528     | 99.22%  |
| No        | 12       | 0.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1167     | 73.67%  |
| Yes       | 417      | 26.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1359     | 85.9%   |
| Yes       | 223      | 14.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Hungary      | 1144     | 74.14%  |
| Germany      | 65       | 4.21%   |
| USA          | 58       | 3.76%   |
| Romania      | 34       | 2.2%    |
| Slovakia     | 19       | 1.23%   |
| UK           | 18       | 1.17%   |
| Brazil       | 17       | 1.1%    |
| France       | 16       | 1.04%   |
| Italy        | 15       | 0.97%   |
| Spain        | 12       | 0.78%   |
| Canada       | 12       | 0.78%   |
| Serbia       | 11       | 0.71%   |
| Poland       | 11       | 0.71%   |
| Australia    | 10       | 0.65%   |
| Philippines  | 8        | 0.52%   |
| Japan        | 7        | 0.45%   |
| South Africa | 6        | 0.39%   |
| Argentina    | 6        | 0.39%   |
| Ukraine      | 5        | 0.32%   |
| Austria      | 5        | 0.32%   |
| Netherlands  | 4        | 0.26%   |
| India        | 4        | 0.26%   |
| Greece       | 4        | 0.26%   |
| Ireland      | 3        | 0.19%   |
| Finland      | 3        | 0.19%   |
| Egypt        | 3        | 0.19%   |
| Belgium      | 3        | 0.19%   |
| Uruguay      | 2        | 0.13%   |
| Turkey       | 2        | 0.13%   |
| Switzerland  | 2        | 0.13%   |
| Russia       | 2        | 0.13%   |
| Morocco      | 2        | 0.13%   |
| Kuwait       | 2        | 0.13%   |
| Colombia     | 2        | 0.13%   |
| Belarus      | 2        | 0.13%   |
| Thailand     | 1        | 0.06%   |
| Tanzania     | 1        | 0.06%   |
| Taiwan       | 1        | 0.06%   |
| South Korea  | 1        | 0.06%   |
| Slovenia     | 1        | 0.06%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Budapest                | 370      | 19.67%  |
| Zalaegerszeg            | 31       | 1.65%   |
| Győr                   | 31       | 1.65%   |
| Szeged                  | 26       | 1.38%   |
| Pécs                   | 26       | 1.38%   |
| Miskolc                 | 26       | 1.38%   |
| Karcag                  | 22       | 1.17%   |
| Debrecen                | 22       | 1.17%   |
| Eger                    | 18       | 0.96%   |
| Oroshaza                | 17       | 0.9%    |
| Szombathely             | 16       | 0.85%   |
| Kecskemét              | 16       | 0.85%   |
| Berettyóújfalu        | 16       | 0.85%   |
| Tatabánya              | 14       | 0.74%   |
| Szigetszentmiklos       | 13       | 0.69%   |
| Szekszárd              | 13       | 0.69%   |
| Gödöllő              | 13       | 0.69%   |
| Toeroekbalint           | 12       | 0.64%   |
| Székesfehérvár       | 12       | 0.64%   |
| Nyiregyhaza             | 12       | 0.64%   |
| Szolnok                 | 11       | 0.58%   |
| Szentendre              | 11       | 0.58%   |
| Pfaffenhofen an der Ilm | 10       | 0.53%   |
| Papa                    | 10       | 0.53%   |
| Hajduboszormeny         | 10       | 0.53%   |
| Tiszafured              | 9        | 0.48%   |
| Nagykanizsa             | 9        | 0.48%   |
| Veresegyhaz             | 8        | 0.43%   |
| Szeghalom               | 8        | 0.43%   |
| Mosonmagyaróvár       | 8        | 0.43%   |
| Esztergom               | 8        | 0.43%   |
| Bucharest               | 8        | 0.43%   |
| Érd                    | 7        | 0.37%   |
| Dunaharaszti            | 7        | 0.37%   |
| Celldomolk              | 7        | 0.37%   |
| Bratislava              | 7        | 0.37%   |
| Baja                    | 7        | 0.37%   |
| Ajka                    | 7        | 0.37%   |
| Zalău                  | 6        | 0.32%   |
| Siófok                 | 6        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 565      | 1217   | 21.26%  |
| Seagate             | 433      | 709    | 16.29%  |
| Samsung Electronics | 369      | 791    | 13.88%  |
| Kingston            | 294      | 668    | 11.06%  |
| Toshiba             | 170      | 381    | 6.4%    |
| Hitachi             | 125      | 193    | 4.7%    |
| A-DATA Technology   | 81       | 164    | 3.05%   |
| SanDisk             | 64       | 123    | 2.41%   |
| Maxtor              | 59       | 76     | 2.22%   |
| Crucial             | 46       | 89     | 1.73%   |
| SPCC                | 36       | 52     | 1.35%   |
| Intenso             | 33       | 64     | 1.24%   |
| HGST                | 32       | 95     | 1.2%    |
| Intel               | 27       | 47     | 1.02%   |
| JMicron Technology  | 19       | 23     | 0.71%   |
| Fujitsu             | 19       | 19     | 0.71%   |
| Patriot             | 18       | 57     | 0.68%   |
| Gigabyte Technology | 15       | 53     | 0.56%   |
| PNY                 | 14       | 23     | 0.53%   |
| OCZ                 | 14       | 19     | 0.53%   |
| Apacer              | 14       | 24     | 0.53%   |
| China               | 13       | 21     | 0.49%   |
| SK hynix            | 12       | 17     | 0.45%   |
| Kingmax             | 11       | 37     | 0.41%   |
| Micron Technology   | 10       | 23     | 0.38%   |
| Hewlett-Packard     | 10       | 16     | 0.38%   |
| XPG                 | 9        | 17     | 0.34%   |
| Unknown             | 8        | 23     | 0.3%    |
| Netac               | 7        | 17     | 0.26%   |
| Corsair             | 7        | 9      | 0.26%   |
| Zheino              | 6        | 25     | 0.23%   |
| Verbatim            | 6        | 11     | 0.23%   |
| KingSpec            | 6        | 8      | 0.23%   |
| GOODRAM             | 6        | 8      | 0.23%   |
| WD MediaMax         | 5        | 6      | 0.19%   |
| Team                | 5        | 7      | 0.19%   |
| ASMT                | 5        | 7      | 0.19%   |
| USB3.0              | 4        | 5      | 0.15%   |
| Transcend           | 4        | 10     | 0.15%   |
| LITEON              | 4        | 4      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD    | 65       | 2.14%   |
| Seagate ST500DM002-1BD142 500GB    | 58       | 1.91%   |
| Kingston SA400S37240G 240GB SSD    | 57       | 1.88%   |
| Toshiba DT01ACA100 1TB             | 53       | 1.74%   |
| Kingston SV300S37A120G 120GB SSD   | 46       | 1.51%   |
| Toshiba DT01ACA050 500GB           | 31       | 1.02%   |
| A-DATA SU630 240GB SSD             | 30       | 0.99%   |
| Kingston SA400S37480G 480GB SSD    | 28       | 0.92%   |
| Seagate ST380815AS 80GB            | 23       | 0.76%   |
| Kingston SUV400S37120G 120GB SSD   | 22       | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB           | 20       | 0.66%   |
| Samsung HD502HJ 500GB              | 20       | 0.66%   |
| JMicron Generic 500GB              | 19       | 0.63%   |
| A-DATA SU700 120GB SSD             | 19       | 0.63%   |
| Seagate ST3160815AS 160GB          | 18       | 0.59%   |
| Samsung SSD 860 EVO 500GB          | 17       | 0.56%   |
| SPCC Solid State Disk 256GB        | 16       | 0.53%   |
| Samsung SSD 850 EVO 250GB          | 16       | 0.53%   |
| Samsung HD103UJ 1TB                | 16       | 0.53%   |
| Seagate ST3250318AS 250GB          | 15       | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB     | 15       | 0.49%   |
| Toshiba HDWD110 1TB                | 14       | 0.46%   |
| Seagate ST3160318AS 160GB          | 14       | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB        | 13       | 0.43%   |
| WDC WD5000AAKS-007AA0 500GB        | 13       | 0.43%   |
| Toshiba DT01ACA200 2TB             | 13       | 0.43%   |
| Seagate ST3500418AS 500GB          | 13       | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 13       | 0.43%   |
| Samsung SSD 860 EVO 250GB          | 13       | 0.43%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 12       | 0.39%   |
| Samsung HD322HJ 320GB              | 12       | 0.39%   |
| Kingston SV300S37A240G 240GB SSD   | 12       | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 11       | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB     | 11       | 0.36%   |
| Samsung HD161HJ 160GB              | 11       | 0.36%   |
| Hitachi HDS721050CLA662 500GB      | 11       | 0.36%   |
| Hitachi HDS721050CLA360 500GB      | 11       | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 10       | 0.33%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 10       | 0.33%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 10       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 531      | 1111   | 32.66%  |
| Seagate             | 430      | 699    | 26.45%  |
| Samsung Electronics | 212      | 365    | 13.04%  |
| Toshiba             | 163      | 371    | 10.02%  |
| Hitachi             | 125      | 193    | 7.69%   |
| Maxtor              | 58       | 75     | 3.57%   |
| HGST                | 32       | 95     | 1.97%   |
| JMicron Technology  | 19       | 23     | 1.17%   |
| Fujitsu             | 19       | 19     | 1.17%   |
| Hewlett-Packard     | 6        | 8      | 0.37%   |
| WD MediaMax         | 5        | 6      | 0.31%   |
| ASMT                | 4        | 6      | 0.25%   |
| Apple               | 4        | 5      | 0.25%   |
| USB3.0              | 3        | 4      | 0.18%   |
| Unknown             | 3        | 4      | 0.18%   |
| Quantum             | 2        | 2      | 0.12%   |
| ICY BOX             | 2        | 4      | 0.12%   |
| ExcelStor           | 2        | 2      | 0.12%   |
| Unknown             | 2        | 2      | 0.12%   |
| USB                 | 1        | 2      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Emphase             | 1        | 2      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 269      | 580    | 29.99%  |
| Samsung Electronics | 134      | 299    | 14.94%  |
| A-DATA Technology   | 73       | 150    | 8.14%   |
| SanDisk             | 59       | 107    | 6.58%   |
| WDC                 | 40       | 91     | 4.46%   |
| Crucial             | 38       | 76     | 4.24%   |
| Intenso             | 33       | 64     | 3.68%   |
| SPCC                | 31       | 46     | 3.46%   |
| Intel               | 20       | 32     | 2.23%   |
| Patriot             | 17       | 56     | 1.9%    |
| PNY                 | 14       | 23     | 1.56%   |
| OCZ                 | 14       | 19     | 1.56%   |
| Apacer              | 14       | 24     | 1.56%   |
| China               | 13       | 21     | 1.45%   |
| Gigabyte Technology | 12       | 45     | 1.34%   |
| Kingmax             | 10       | 35     | 1.11%   |
| Micron Technology   | 8        | 21     | 0.89%   |
| Toshiba             | 7        | 10     | 0.78%   |
| SK hynix            | 7        | 12     | 0.78%   |
| Netac               | 7        | 17     | 0.78%   |
| Corsair             | 7        | 9      | 0.78%   |
| Verbatim            | 6        | 11     | 0.67%   |
| KingSpec            | 6        | 8      | 0.67%   |
| Team                | 5        | 7      | 0.56%   |
| GOODRAM             | 5        | 7      | 0.56%   |
| LITEON              | 4        | 4      | 0.45%   |
| Transcend           | 3        | 5      | 0.33%   |
| Emtec               | 3        | 3      | 0.33%   |
| StoreJet            | 2        | 2      | 0.22%   |
| sobetter            | 2        | 2      | 0.22%   |
| KingFast            | 2        | 3      | 0.22%   |
| Integral            | 2        | 3      | 0.22%   |
| Hewlett-Packard     | 2        | 3      | 0.22%   |
| BIWIN               | 2        | 6      | 0.22%   |
| Vaseky              | 1        | 1      | 0.11%   |
| USB3.0              | 1        | 1      | 0.11%   |
| Unknown             | 1        | 2      | 0.11%   |
| Teclast             | 1        | 1      | 0.11%   |
| SMI                 | 1        | 1      | 0.11%   |
| Seagate             | 1        | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1227     | 3000   | 58.01%  |
| SSD     | 735      | 1834   | 34.75%  |
| NVMe    | 138      | 403    | 6.52%   |
| Unknown | 14       | 32     | 0.66%   |
| MMC     | 1        | 1      | 0.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1483     | 4687   | 86.47%  |
| NVMe | 138      | 403    | 8.05%   |
| SAS  | 93       | 179    | 5.42%   |
| MMC  | 1        | 1      | 0.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1339     | 3345   | 68.32%  |
| 0.51-1.0   | 427      | 984    | 21.79%  |
| 1.01-2.0   | 109      | 251    | 5.56%   |
| 3.01-4.0   | 35       | 95     | 1.79%   |
| 2.01-3.0   | 32       | 131    | 1.63%   |
| 4.01-10.0  | 16       | 25     | 0.82%   |
| 10.01-20.0 | 2        | 3      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 1060     | 55.67%  |
| 101-250        | 298      | 15.65%  |
| 251-500        | 185      | 9.72%   |
| 51-100         | 119      | 6.25%   |
| 501-1000       | 105      | 5.51%   |
| 21-50          | 61       | 3.2%    |
| 1001-2000      | 38       | 2%      |
| 1-20           | 19       | 1%      |
| More than 3000 | 13       | 0.68%   |
| 2001-3000      | 6        | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 1060     | 56.41%  |
| 1-20           | 546      | 29.06%  |
| 21-50          | 104      | 5.53%   |
| 51-100         | 63       | 3.35%   |
| 101-250        | 57       | 3.03%   |
| 501-1000       | 19       | 1.01%   |
| 251-500        | 16       | 0.85%   |
| 1001-2000      | 9        | 0.48%   |
| More than 3000 | 4        | 0.21%   |
| 2001-3000      | 1        | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 29       | 46     | 3.55%   |
| A-DATA Technology SU630 240GB SSD  | 19       | 39     | 2.32%   |
| Kingston SV300S37A120G 120GB SSD   | 15       | 18     | 1.83%   |
| Samsung Electronics HD103UJ 1TB    | 14       | 32     | 1.71%   |
| Toshiba DT01ACA100 1TB             | 12       | 25     | 1.47%   |
| Toshiba DT01ACA050 500GB           | 11       | 15     | 1.34%   |
| WDC WD5000AAKX-001CA0 500GB        | 10       | 10     | 1.22%   |
| WDC WD5000AAKS-007AA0 500GB        | 10       | 31     | 1.22%   |
| Seagate ST500LT012-9WS142 500GB    | 8        | 9      | 0.98%   |
| Seagate ST3160815AS 160GB          | 8        | 12     | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 8        | 11     | 0.98%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 7        | 19     | 0.86%   |
| Seagate ST3500418AS 500GB          | 7        | 12     | 0.86%   |
| Samsung Electronics HD321KJ 320GB  | 7        | 7      | 0.86%   |
| WDC WD5000AADS-00S9B0 500GB        | 6        | 8      | 0.73%   |
| WDC WD10EARS-00Y5B1 1TB            | 6        | 16     | 0.73%   |
| Seagate ST3250318AS 250GB          | 6        | 9      | 0.73%   |
| Samsung Electronics SP2504C 250GB  | 6        | 11     | 0.73%   |
| Samsung Electronics HD161HJ 160GB  | 6        | 6      | 0.73%   |
| Samsung Electronics HD103SI 1TB    | 6        | 6      | 0.73%   |
| Samsung Electronics HD080HJ/ 80GB  | 6        | 6      | 0.73%   |
| Hitachi HDS721050CLA362 500GB      | 6        | 11     | 0.73%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 5        | 9      | 0.61%   |
| WDC WD3200AAKS-00L9A0 320GB        | 5        | 7      | 0.61%   |
| WDC WD10PURZ-85U8XY0 1TB           | 5        | 13     | 0.61%   |
| Seagate ST380815AS 80GB            | 5        | 8      | 0.61%   |
| Seagate ST3160812AS 160GB          | 5        | 5      | 0.61%   |
| Hitachi HDP725050GLA360 500GB      | 5        | 5      | 0.61%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 4        | 5      | 0.49%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 4        | 5      | 0.49%   |
| WDC WD5000AAKX-07U6AA0 500GB       | 4        | 6      | 0.49%   |
| Seagate ST3160318AS 160GB          | 4        | 4      | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB     | 4        | 4      | 0.49%   |
| Samsung Electronics SP2004C 200GB  | 4        | 6      | 0.49%   |
| Samsung Electronics HD642JJ 640GB  | 4        | 7      | 0.49%   |
| Samsung Electronics HD502HJ 500GB  | 4        | 7      | 0.49%   |
| Samsung Electronics HD501LJ 500GB  | 4        | 5      | 0.49%   |
| Samsung Electronics HD200HJ 200GB  | 4        | 9      | 0.49%   |
| Samsung Electronics HD161GJ 160GB  | 4        | 5      | 0.49%   |
| Samsung Electronics HD082GJ 80GB   | 4        | 4      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 220      | 395    | 28.68%  |
| Seagate             | 185      | 260    | 24.12%  |
| Samsung Electronics | 115      | 184    | 14.99%  |
| Hitachi             | 53       | 88     | 6.91%   |
| Toshiba             | 47       | 85     | 6.13%   |
| Maxtor              | 34       | 48     | 4.43%   |
| Kingston            | 32       | 51     | 4.17%   |
| A-DATA Technology   | 26       | 56     | 3.39%   |
| HGST                | 10       | 11     | 1.3%    |
| OCZ                 | 7        | 10     | 0.91%   |
| WD MediaMax         | 5        | 6      | 0.65%   |
| Intel               | 4        | 12     | 0.52%   |
| Fujitsu             | 4        | 4      | 0.52%   |
| Hewlett-Packard     | 3        | 3      | 0.39%   |
| SK hynix            | 2        | 5      | 0.26%   |
| SanDisk             | 2        | 2      | 0.26%   |
| KingSpec            | 2        | 2      | 0.26%   |
| Crucial             | 2        | 5      | 0.26%   |
| SATAFIRM            | 1        | 1      | 0.13%   |
| QUANTUM             | 1        | 1      | 0.13%   |
| Patriot             | 1        | 1      | 0.13%   |
| LITEON              | 1        | 1      | 0.13%   |
| Kingmax             | 1        | 1      | 0.13%   |
| Intenso             | 1        | 1      | 0.13%   |
| ICY BOX             | 1        | 1      | 0.13%   |
| IBM/Hitachi         | 1        | 1      | 0.13%   |
| ExcelStor           | 1        | 1      | 0.13%   |
| Corsair             | 1        | 1      | 0.13%   |
| China               | 1        | 1      | 0.13%   |
| BIWIN               | 1        | 1      | 0.13%   |
| ASMT                | 1        | 1      | 0.13%   |
| Unknown             | 1        | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 218      | 393    | 32.3%   |
| Seagate             | 185      | 260    | 27.41%  |
| Samsung Electronics | 112      | 173    | 16.59%  |
| Hitachi             | 53       | 88     | 7.85%   |
| Toshiba             | 46       | 84     | 6.81%   |
| Maxtor              | 34       | 48     | 5.04%   |
| HGST                | 10       | 11     | 1.48%   |
| WD MediaMax         | 5        | 6      | 0.74%   |
| Fujitsu             | 4        | 4      | 0.59%   |
| Hewlett-Packard     | 2        | 2      | 0.3%    |
| QUANTUM             | 1        | 1      | 0.15%   |
| ICY BOX             | 1        | 1      | 0.15%   |
| IBM/Hitachi         | 1        | 1      | 0.15%   |
| ExcelStor           | 1        | 1      | 0.15%   |
| ASMT                | 1        | 1      | 0.15%   |
| Unknown             | 1        | 1      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 577      | 1075   | 86.51%  |
| SSD  | 86       | 162    | 12.89%  |
| NVMe | 4        | 4      | 0.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 2        | 3      | 12.5%   |
| Samsung Electronics HD103SJ 1TB   | 2        | 2      | 12.5%   |
| Zheino CHN-NGFFNV2280-256 256GB   | 1        | 1      | 6.25%   |
| WDC WD1600BEVT-80A23T0 160GB      | 1        | 1      | 6.25%   |
| Seagate ST9160412AS 160GB         | 1        | 1      | 6.25%   |
| Seagate ST380815AS 80GB           | 1        | 3      | 6.25%   |
| Seagate ST3160815AS 160GB         | 1        | 1      | 6.25%   |
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 6.25%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 6.25%   |
| Samsung Electronics HD103UJ 1TB   | 1        | 1      | 6.25%   |
| OCZ-AGIL ITY3 64GB SSD            | 1        | 1      | 6.25%   |
| Hitachi HDS721010DLE630 1TB       | 1        | 1      | 6.25%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 6.25%   |
| ExcelStor Technology J8160S 165GB | 1        | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 43.75%  |
| Seagate             | 3        | 5      | 18.75%  |
| Zheino              | 1        | 1      | 6.25%   |
| WDC                 | 1        | 1      | 6.25%   |
| OCZ-AGIL            | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 1      | 6.25%   |
| ExcelStor           | 1        | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1230     | 3752   | 60.68%  |
| Malfunc  | 644      | 1241   | 31.77%  |
| Detected | 137      | 258    | 6.76%   |
| Failed   | 16       | 19     | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1046     | 55.91%  |
| AMD                              | 399      | 21.33%  |
| JMicron Technology               | 76       | 4.06%   |
| Nvidia                           | 75       | 4.01%   |
| Samsung Electronics              | 49       | 2.62%   |
| ASMedia Technology               | 41       | 2.19%   |
| Kingston Technology Company      | 37       | 1.98%   |
| Marvell Technology Group         | 33       | 1.76%   |
| VIA Technologies                 | 18       | 0.96%   |
| Silicon Motion                   | 13       | 0.69%   |
| Silicon Image                    | 12       | 0.64%   |
| Phison Electronics               | 12       | 0.64%   |
| SanDisk                          | 11       | 0.59%   |
| Realtek Semiconductor            | 10       | 0.53%   |
| Micron/Crucial Technology        | 7        | 0.37%   |
| SK hynix                         | 5        | 0.27%   |
| ADATA Technology                 | 5        | 0.27%   |
| Silicon Integrated Systems [SiS] | 2        | 0.11%   |
| Micron Technology                | 2        | 0.11%   |
| LSI Logic / Symbios Logic        | 2        | 0.11%   |
| Integrated Technology Express    | 2        | 0.11%   |
| Adaptec                          | 2        | 0.11%   |
| 3ware                            | 2        | 0.11%   |
| Zhaoxin                          | 1        | 0.05%   |
| ULi Electronics                  | 1        | 0.05%   |
| Shenzhen Longsys Electronics     | 1        | 0.05%   |
| Promise Technology               | 1        | 0.05%   |
| O2 Micro                         | 1        | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.05%   |
| Lite-On Technology               | 1        | 0.05%   |
| INNOGRIT                         | 1        | 0.05%   |
| Hewlett-Packard                  | 1        | 0.05%   |
| Broadcom / LSI                   | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 197      | 7.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 183      | 6.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 135      | 5.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 129      | 4.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 101      | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 90       | 3.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 75       | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 73       | 2.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 69       | 2.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 63       | 2.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 61       | 2.27%   |
| AMD FCH IDE Controller                                                                  | 60       | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 59       | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 59       | 2.2%    |
| Intel SATA Controller [RAID mode]                                                       | 57       | 2.12%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 54       | 2.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 50       | 1.86%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 44       | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 44       | 1.64%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 39       | 1.45%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 39       | 1.45%   |
| Nvidia MCP61 SATA Controller                                                            | 36       | 1.34%   |
| Nvidia MCP61 IDE                                                                        | 33       | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 31       | 1.15%   |
| JMicron JMB368 IDE controller                                                           | 31       | 1.15%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 29       | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 28       | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 28       | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 27       | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 27       | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 24       | 0.89%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 23       | 0.86%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 22       | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 21       | 0.78%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 21       | 0.78%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 19       | 0.71%   |
| AMD 500 Series Chipset SATA Controller                                                  | 18       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 17       | 0.63%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 16       | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1015     | 51.19%  |
| IDE  | 742      | 37.42%  |
| NVMe | 138      | 6.96%   |
| RAID | 81       | 4.08%   |
| SCSI | 5        | 0.25%   |
| SAS  | 2        | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1069     | 69.42%  |
| AMD          | 470      | 30.52%  |
| CentaurHauls | 1        | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 52       | 3.34%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 34       | 2.18%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 28       | 1.8%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 27       | 1.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 25       | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24       | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 24       | 1.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 22       | 1.41%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 22       | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 22       | 1.41%   |
| AMD FX-6300 Six-Core Processor                | 18       | 1.16%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 16       | 1.03%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 14       | 0.9%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 14       | 0.9%    |
| Intel Pentium CPU G3220 @ 3.00GHz             | 12       | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                   | 12       | 0.77%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 12       | 0.77%   |
| AMD FX-8350 Eight-Core Processor              | 12       | 0.77%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 11       | 0.71%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 11       | 0.71%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 11       | 0.71%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 10       | 0.64%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 10       | 0.64%   |
| Intel Xeon CPU X5677 @ 3.47GHz                | 9        | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 9        | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 9        | 0.58%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 9        | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 9        | 0.58%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 9        | 0.58%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9        | 0.58%   |
| AMD Athlon II X2 260 Processor                | 9        | 0.58%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 9        | 0.58%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 8        | 0.51%   |
| Intel Pentium CPU G840 @ 2.80GHz              | 8        | 0.51%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 8        | 0.51%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 8        | 0.51%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 8        | 0.51%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 8        | 0.51%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 8        | 0.51%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 8        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 249      | 16.05%  |
| Intel Core i3           | 186      | 11.99%  |
| Intel Core 2 Duo        | 162      | 10.44%  |
| Intel Core i7           | 69       | 4.45%   |
| Intel Core 2 Quad       | 66       | 4.26%   |
| Intel Pentium           | 65       | 4.19%   |
| Intel Xeon              | 60       | 3.87%   |
| AMD A8                  | 59       | 3.8%    |
| Intel Pentium Dual-Core | 58       | 3.74%   |
| AMD FX                  | 57       | 3.68%   |
| Intel Celeron           | 55       | 3.55%   |
| AMD Ryzen 5             | 45       | 2.9%    |
| AMD Athlon II X2        | 40       | 2.58%   |
| AMD Athlon 64 X2        | 32       | 2.06%   |
| AMD Ryzen 7             | 29       | 1.87%   |
| AMD Phenom II X4        | 26       | 1.68%   |
| Intel Pentium 4         | 23       | 1.48%   |
| AMD A4                  | 23       | 1.48%   |
| Intel Pentium Dual      | 22       | 1.42%   |
| AMD Ryzen 3             | 21       | 1.35%   |
| Intel Core 2            | 20       | 1.29%   |
| AMD A10                 | 17       | 1.1%    |
| Other                   | 16       | 1.03%   |
| Intel Atom              | 15       | 0.97%   |
| Intel Pentium D         | 14       | 0.9%    |
| AMD Athlon II X4        | 14       | 0.9%    |
| AMD Sempron             | 13       | 0.84%   |
| AMD A6                  | 11       | 0.71%   |
| AMD Athlon Dual Core    | 10       | 0.64%   |
| AMD Athlon X4           | 9        | 0.58%   |
| AMD Athlon              | 8        | 0.52%   |
| AMD Athlon 64           | 7        | 0.45%   |
| AMD Phenom II X6        | 6        | 0.39%   |
| AMD Phenom II X2        | 4        | 0.26%   |
| AMD Phenom              | 4        | 0.26%   |
| Intel Pentium Gold      | 3        | 0.19%   |
| Intel Celeron D         | 3        | 0.19%   |
| AMD Turion II Neo       | 3        | 0.19%   |
| AMD Ryzen 9             | 3        | 0.19%   |
| AMD PRO A10             | 3        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 766      | 49.17%  |
| 4       | 503      | 32.28%  |
| 1       | 105      | 6.74%   |
| 6       | 95       | 6.1%    |
| 8       | 48       | 3.08%   |
| 3       | 27       | 1.73%   |
| 18      | 6        | 0.39%   |
| 10      | 3        | 0.19%   |
| 16      | 2        | 0.13%   |
| 12      | 2        | 0.13%   |
| Unknown | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1526     | 98.96%  |
| 2      | 15       | 0.97%   |
| 4      | 1        | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 978      | 62.85%  |
| 2       | 577      | 37.08%  |
| Unknown | 1        | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1534     | 99.55%  |
| 32-bit         | 5        | 0.32%   |
| Unknown        | 2        | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 192      | 11.98%  |
| Unknown    | 175      | 10.92%  |
| 0x306c3    | 141      | 8.8%    |
| 0x206a7    | 125      | 7.8%    |
| 0x306a9    | 92       | 5.74%   |
| 0x06001119 | 73       | 4.55%   |
| 0x010000c8 | 61       | 3.81%   |
| 0x506e3    | 47       | 2.93%   |
| 0x10676    | 46       | 2.87%   |
| 0x906e9    | 41       | 2.56%   |
| 0x6fb      | 41       | 2.56%   |
| 0x6fd      | 36       | 2.25%   |
| 0x906ea    | 35       | 2.18%   |
| 0x06000852 | 27       | 1.68%   |
| 0x06003106 | 21       | 1.31%   |
| 0x0600084f | 20       | 1.25%   |
| 0x0800820d | 17       | 1.06%   |
| 0x906eb    | 15       | 0.94%   |
| 0x010000db | 14       | 0.87%   |
| 0x6f2      | 13       | 0.81%   |
| 0x106a5    | 13       | 0.81%   |
| 0x03000027 | 13       | 0.81%   |
| 0x206c2    | 12       | 0.75%   |
| 0x20655    | 12       | 0.75%   |
| 0x106e5    | 12       | 0.75%   |
| 0x10677    | 12       | 0.75%   |
| 0x08001138 | 12       | 0.75%   |
| 0xf43      | 11       | 0.69%   |
| 0x20652    | 11       | 0.69%   |
| 0x08108109 | 10       | 0.62%   |
| 0x0810100b | 10       | 0.62%   |
| 0x0600063e | 10       | 0.62%   |
| 0xf65      | 9        | 0.56%   |
| 0xa0653    | 8        | 0.5%    |
| 0x6f6      | 8        | 0.5%    |
| 0x0700010f | 8        | 0.5%    |
| 0x0600611a | 8        | 0.5%    |
| 0x106ca    | 7        | 0.44%   |
| 0x08701021 | 7        | 0.44%   |
| 0x08101016 | 7        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 252      | 16.33%  |
| Haswell          | 158      | 10.24%  |
| SandyBridge      | 130      | 8.43%   |
| Piledriver       | 118      | 7.65%   |
| KabyLake         | 109      | 7.06%   |
| K10              | 108      | 7%      |
| Core             | 105      | 6.8%    |
| IvyBridge        | 100      | 6.48%   |
| Skylake          | 60       | 3.89%   |
| K8 Hammer        | 60       | 3.89%   |
| NetBurst         | 45       | 2.92%   |
| Westmere         | 42       | 2.72%   |
| Zen              | 34       | 2.2%    |
| Zen+             | 29       | 1.88%   |
| Steamroller      | 26       | 1.69%   |
| Nehalem          | 25       | 1.62%   |
| Zen 3            | 23       | 1.49%   |
| Zen 2            | 15       | 0.97%   |
| K10 Llano        | 15       | 0.97%   |
| Bonnell          | 15       | 0.97%   |
| Excavator        | 14       | 0.91%   |
| Bulldozer        | 14       | 0.91%   |
| Silvermont       | 11       | 0.71%   |
| CometLake        | 9        | 0.58%   |
| Jaguar           | 8        | 0.52%   |
| Bobcat           | 6        | 0.39%   |
| Alderlake Hybrid | 4        | 0.26%   |
| Puma             | 3        | 0.19%   |
| Goldmont plus    | 2        | 0.13%   |
| Goldmont         | 1        | 0.06%   |
| Broadwell        | 1        | 0.06%   |
| Unknown          | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 560      | 33.9%   |
| Intel                                        | 553      | 33.47%  |
| AMD                                          | 528      | 31.96%  |
| VIA Technologies                             | 5        | 0.3%    |
| ATI Technologies                             | 2        | 0.12%   |
| Zhaoxin                                      | 1        | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.06%   |
| Matrox Electronics Systems                   | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 84       | 4.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 72       | 4.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 64       | 3.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 54       | 3.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 49       | 2.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 42       | 2.44%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 42       | 2.44%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 39       | 2.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 36       | 2.09%   |
| Intel HD Graphics 530                                                       | 35       | 2.04%   |
| AMD Richland [Radeon HD 8570D]                                              | 34       | 1.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 33       | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 33       | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 31       | 1.8%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 27       | 1.57%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 26       | 1.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 24       | 1.4%    |
| Nvidia GF108 [GeForce GT 630]                                               | 20       | 1.16%   |
| Nvidia GF119 [GeForce GT 610]                                               | 16       | 0.93%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 16       | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 15       | 0.87%   |
| Intel HD Graphics 630                                                       | 15       | 0.87%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 15       | 0.87%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 15       | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 14       | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                              | 14       | 0.81%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 14       | 0.81%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 14       | 0.81%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 14       | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 13       | 0.76%   |
| AMD RS880 [Radeon HD 4200]                                                  | 13       | 0.76%   |
| AMD RS780L [Radeon 3000]                                                    | 12       | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12       | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 11       | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                               | 11       | 0.64%   |
| Intel Core Processor Integrated Graphics Controller                         | 11       | 0.64%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 10       | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 10       | 0.58%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 10       | 0.58%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 9        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 535      | 33.42%  |
| 1 x Intel      | 504      | 31.48%  |
| 1 x AMD        | 477      | 29.79%  |
| 2 x AMD        | 40       | 2.5%    |
| Intel + Nvidia | 16       | 1%      |
| Intel + AMD    | 10       | 0.62%   |
| AMD + Nvidia   | 7        | 0.44%   |
| 1 x VIA        | 5        | 0.31%   |
| 2 x Nvidia     | 3        | 0.19%   |
| 1 x Zhaoxin    | 1        | 0.06%   |
| 1 x XGI        | 1        | 0.06%   |
| 1 x SiS        | 1        | 0.06%   |
| 1 x Matrox     | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1476     | 94.25%  |
| Unknown     | 86       | 5.49%   |
| Proprietary | 4        | 0.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 578      | 35.12%  |
| 0.51-1.0   | 367      | 22.3%   |
| 0.01-0.5   | 297      | 18.04%  |
| 1.01-2.0   | 205      | 12.45%  |
| 3.01-4.0   | 95       | 5.77%   |
| 7.01-8.0   | 40       | 2.43%   |
| 5.01-6.0   | 24       | 1.46%   |
| 2.01-3.0   | 24       | 1.46%   |
| 8.01-16.0  | 15       | 0.91%   |
| 4.01-5.0   | 1        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 304      | 19.38%  |
| Goldstar                | 267      | 17.02%  |
| Dell                    | 128      | 8.16%   |
| Hewlett-Packard         | 89       | 5.67%   |
| Philips                 | 84       | 5.35%   |
| BenQ                    | 82       | 5.23%   |
| Acer                    | 81       | 5.16%   |
| Ancor Communications    | 74       | 4.72%   |
| AOC                     | 51       | 3.25%   |
| Fujitsu Siemens         | 48       | 3.06%   |
| Lenovo                  | 24       | 1.53%   |
| Iiyama                  | 23       | 1.47%   |
| Eizo                    | 21       | 1.34%   |
| Vestel Elektronik       | 18       | 1.15%   |
| HannStar                | 17       | 1.08%   |
| HKC                     | 16       | 1.02%   |
| NEC Computers           | 15       | 0.96%   |
| Medion                  | 15       | 0.96%   |
| ViewSonic               | 14       | 0.89%   |
| Sony                    | 13       | 0.83%   |
| ASUSTek Computer        | 12       | 0.76%   |
| Chi Mei Optoelectronics | 11       | 0.7%    |
| Belinea                 | 9        | 0.57%   |
| Plain Tree Systems      | 8        | 0.51%   |
| Panasonic               | 8        | 0.51%   |
| OEM                     | 7        | 0.45%   |
| LG Electronics          | 7        | 0.45%   |
| IBM                     | 7        | 0.45%   |
| Toshiba                 | 6        | 0.38%   |
| MStar                   | 6        | 0.38%   |
| Videoseven              | 5        | 0.32%   |
| Unknown                 | 5        | 0.32%   |
| KTC                     | 5        | 0.32%   |
| Gericom                 | 5        | 0.32%   |
| NCS                     | 4        | 0.25%   |
| CVT                     | 4        | 0.25%   |
| Unknown (XXX)           | 3        | 0.19%   |
| Sceptre Tech            | 3        | 0.19%   |
| S2-Tek                  | 3        | 0.19%   |
| Orion                   | 3        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                   | 30       | 1.84%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 18       | 1.1%    |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 11       | 0.67%   |
| HKC Monitor HKC1850 1366x768 409x230mm 18.5-inch                      | 11       | 0.67%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 11       | 0.67%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 11       | 0.67%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 10       | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10       | 0.61%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 9        | 0.55%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 9        | 0.55%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 9        | 0.55%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 8        | 0.49%   |
| Samsung Electronics LS27AG30x SAM717A 1920x1080 597x336mm 27.0-inch   | 8        | 0.49%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 8        | 0.49%   |
| HannStar HannsG HS191D HSD0013 1280x1024 376x301mm 19.0-inch          | 8        | 0.49%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 8        | 0.49%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 7        | 0.43%   |
| OEM 215_LCD_TV OEM3700 1920x1080                                      | 7        | 0.43%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                | 7        | 0.43%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 477x268mm 21.5-inch              | 6        | 0.37%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 6        | 0.37%   |
| Hewlett-Packard P222va HWP322B 1920x1080 476x268mm 21.5-inch          | 6        | 0.37%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 6        | 0.37%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 6        | 0.37%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 6        | 0.37%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.37%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                  | 6        | 0.37%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 6        | 0.37%   |
| Fujitsu Siemens L19W-9 FUS075C 1440x900 408x255mm 18.9-inch           | 6        | 0.37%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                     | 6        | 0.37%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                      | 6        | 0.37%   |
| Chi Mei Optoelectronics CMC 19 CMO0198 1280x1024 376x301mm 19.0-inch  | 6        | 0.37%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.37%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 5        | 0.31%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch     | 5        | 0.31%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 5        | 0.31%   |
| Samsung Electronics LS49A950U SAM71CC 3840x1080 1192x336mm 48.8-inch  | 5        | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 5        | 0.31%   |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch              | 5        | 0.31%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 5        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 620      | 40.74%  |
| 1280x1024 (SXGA)   | 246      | 16.16%  |
| 1680x1050 (WSXGA+) | 149      | 9.79%   |
| 1440x900 (WXGA+)   | 108      | 7.1%    |
| 1366x768 (WXGA)    | 89       | 5.85%   |
| 3840x2160 (4K)     | 79       | 5.19%   |
| 1600x900 (HD+)     | 43       | 2.83%   |
| 1360x768           | 31       | 2.04%   |
| 2560x1080          | 28       | 1.84%   |
| 1920x1200 (WUXGA)  | 25       | 1.64%   |
| 2560x1440 (QHD)    | 24       | 1.58%   |
| 1024x768 (XGA)     | 20       | 1.31%   |
| 1920x540           | 14       | 0.92%   |
| 1600x1200          | 9        | 0.59%   |
| 3840x1080          | 8        | 0.53%   |
| 1280x720 (HD)      | 6        | 0.39%   |
| 3440x1440          | 4        | 0.26%   |
| 2288x1287          | 4        | 0.26%   |
| 1152x864           | 4        | 0.26%   |
| 1280x960           | 2        | 0.13%   |
| 800x600            | 1        | 0.07%   |
| 4093x4093          | 1        | 0.07%   |
| 3840x1200          | 1        | 0.07%   |
| 2880x1200          | 1        | 0.07%   |
| 2560x1600          | 1        | 0.07%   |
| 2048x1536          | 1        | 0.07%   |
| 1280x768           | 1        | 0.07%   |
| 1024x600           | 1        | 0.07%   |
| Unknown            | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 230      | 14.6%   |
| 19      | 214      | 13.59%  |
| 23      | 172      | 10.92%  |
| 27      | 128      | 8.13%   |
| 17      | 126      | 8%      |
| 24      | 123      | 7.81%   |
| 18      | 111      | 7.05%   |
| 22      | 110      | 6.98%   |
| 20      | 68       | 4.32%   |
| Unknown | 42       | 2.67%   |
| 31      | 35       | 2.22%   |
| 15      | 32       | 2.03%   |
| 34      | 31       | 1.97%   |
| 84      | 28       | 1.78%   |
| 72      | 15       | 0.95%   |
| 40      | 13       | 0.83%   |
| 32      | 11       | 0.7%    |
| 54      | 8        | 0.51%   |
| 52      | 7        | 0.44%   |
| 42      | 7        | 0.44%   |
| 65      | 6        | 0.38%   |
| 48      | 6        | 0.38%   |
| 12      | 6        | 0.38%   |
| 49      | 5        | 0.32%   |
| 46      | 5        | 0.32%   |
| 26      | 4        | 0.25%   |
| 25      | 4        | 0.25%   |
| 14      | 4        | 0.25%   |
| 60      | 3        | 0.19%   |
| 142     | 2        | 0.13%   |
| 58      | 2        | 0.13%   |
| 50      | 2        | 0.13%   |
| 41      | 2        | 0.13%   |
| 39      | 2        | 0.13%   |
| 85      | 1        | 0.06%   |
| 64      | 1        | 0.06%   |
| 63      | 1        | 0.06%   |
| 59      | 1        | 0.06%   |
| 55      | 1        | 0.06%   |
| 47      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 586      | 38.15%  |
| 501-600        | 406      | 26.43%  |
| 301-350        | 154      | 10.03%  |
| 351-400        | 131      | 8.53%   |
| 1001-1500      | 48       | 3.13%   |
| 701-800        | 44       | 2.86%   |
| 1501-2000      | 44       | 2.86%   |
| 601-700        | 43       | 2.8%    |
| Unknown        | 42       | 2.73%   |
| 801-900        | 16       | 1.04%   |
| 201-300        | 10       | 0.65%   |
| 901-1000       | 10       | 0.65%   |
| More than 2000 | 2        | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 851      | 57.62%  |
| 16/10   | 259      | 17.54%  |
| 5/4     | 244      | 16.52%  |
| 4/3     | 45       | 3.05%   |
| 21/9    | 32       | 2.17%   |
| 3/2     | 14       | 0.95%   |
| Unknown | 13       | 0.88%   |
| 32/9    | 9        | 0.61%   |
| 6/5     | 7        | 0.47%   |
| 1.00    | 3        | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 538      | 34.73%  |
| 151-200        | 349      | 22.53%  |
| 141-150        | 209      | 13.49%  |
| 301-350        | 128      | 8.26%   |
| More than 1000 | 80       | 5.16%   |
| 351-500        | 79       | 5.1%    |
| 251-300        | 42       | 2.71%   |
| Unknown        | 42       | 2.71%   |
| 501-1000       | 40       | 2.58%   |
| 101-110        | 19       | 1.23%   |
| 111-120        | 14       | 0.9%    |
| 71-80          | 6        | 0.39%   |
| 91-100         | 3        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1088     | 74.27%  |
| 101-120       | 251      | 17.13%  |
| 1-50          | 64       | 4.37%   |
| Unknown       | 42       | 2.87%   |
| 161-240       | 10       | 0.68%   |
| 121-160       | 9        | 0.61%   |
| More than 240 | 1        | 0.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1431     | 90.51%  |
| 2     | 96       | 6.07%   |
| 0     | 41       | 2.59%   |
| 3     | 13       | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 849      | 42.77%  |
| Intel                                  | 431      | 21.71%  |
| Qualcomm Atheros                       | 185      | 9.32%   |
| Broadcom                               | 91       | 4.58%   |
| Ralink Technology                      | 64       | 3.22%   |
| Qualcomm Atheros Communications        | 53       | 2.67%   |
| Nvidia                                 | 53       | 2.67%   |
| Broadcom Limited                       | 44       | 2.22%   |
| TP-Link                                | 33       | 1.66%   |
| Marvell Technology Group               | 33       | 1.66%   |
| Ralink                                 | 23       | 1.16%   |
| VIA Technologies                       | 15       | 0.76%   |
| Samsung Electronics                    | 12       | 0.6%    |
| D-Link                                 | 10       | 0.5%    |
| ASUSTek Computer                       | 10       | 0.5%    |
| Huawei Technologies                    | 9        | 0.45%   |
| IMC Networks                           | 8        | 0.4%    |
| D-Link System                          | 8        | 0.4%    |
| Microsoft                              | 6        | 0.3%    |
| Xiaomi                                 | 4        | 0.2%    |
| NetGear                                | 4        | 0.2%    |
| Edimax Technology                      | 4        | 0.2%    |
| Belkin Components                      | 4        | 0.2%    |
| ASIX Electronics                       | 4        | 0.2%    |
| Accton Technology                      | 4        | 0.2%    |
| JMicron Technology                     | 3        | 0.15%   |
| MediaTek                               | 2        | 0.1%    |
| Aquantia                               | 2        | 0.1%    |
| ZyXEL Communications                   | 1        | 0.05%   |
| ZyDAS                                  | 1        | 0.05%   |
| Westell                                | 1        | 0.05%   |
| Wacom                                  | 1        | 0.05%   |
| TRENDnet                               | 1        | 0.05%   |
| Texas Instruments                      | 1        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.05%   |
| Qualcomm                               | 1        | 0.05%   |
| Mercucys                               | 1        | 0.05%   |
| Manta                                  | 1        | 0.05%   |
| HMD Global                             | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 689      | 32.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 80       | 3.8%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 61       | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50       | 2.37%   |
| Qualcomm Atheros AR9271 802.11n                                        | 47       | 2.23%   |
| Intel Ethernet Connection (2) I219-V                                   | 44       | 2.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 42       | 1.99%   |
| Intel Ethernet Connection I217-LM                                      | 42       | 1.99%   |
| Intel I211 Gigabit Network Connection                                  | 33       | 1.57%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 33       | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 32       | 1.52%   |
| Nvidia MCP61 Ethernet                                                  | 32       | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 27       | 1.28%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 25       | 1.19%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 24       | 1.14%   |
| Ralink MT7601U Wireless Adapter                                        | 22       | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 22       | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 21       | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 19       | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 18       | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                   | 16       | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 15       | 0.71%   |
| Intel 82579V Gigabit Network Connection                                | 15       | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 14       | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13       | 0.62%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 13       | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 12       | 0.57%   |
| Ralink RT5370 Wireless Adapter                                         | 12       | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 11       | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 11       | 0.52%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 11       | 0.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 10       | 0.47%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 10       | 0.47%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 10       | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9        | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9        | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 8        | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 8        | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 8        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 98       | 22.22%  |
| Ralink Technology                     | 64       | 14.51%  |
| Qualcomm Atheros Communications       | 53       | 12.02%  |
| Qualcomm Atheros                      | 53       | 12.02%  |
| Intel                                 | 46       | 10.43%  |
| TP-Link                               | 33       | 7.48%   |
| Ralink                                | 23       | 5.22%   |
| Broadcom                              | 11       | 2.49%   |
| ASUSTek Computer                      | 10       | 2.27%   |
| D-Link                                | 9        | 2.04%   |
| IMC Networks                          | 8        | 1.81%   |
| Microsoft                             | 6        | 1.36%   |
| NetGear                               | 4        | 0.91%   |
| Edimax Technology                     | 4        | 0.91%   |
| D-Link System                         | 4        | 0.91%   |
| Belkin Components                     | 4        | 0.91%   |
| ZyXEL Communications                  | 1        | 0.23%   |
| ZyDAS                                 | 1        | 0.23%   |
| Wacom                                 | 1        | 0.23%   |
| TRENDnet                              | 1        | 0.23%   |
| Texas Instruments                     | 1        | 0.23%   |
| Mercucys                              | 1        | 0.23%   |
| MediaTek                              | 1        | 0.23%   |
| Gemtek                                | 1        | 0.23%   |
| Fujitsu Siemens Computers             | 1        | 0.23%   |
| AVM                                   | 1        | 0.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 47       | 10.54%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 27       | 6.05%   |
| Ralink MT7601U Wireless Adapter                                               | 22       | 4.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 13       | 2.91%   |
| Ralink RT5370 Wireless Adapter                                                | 12       | 2.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 11       | 2.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 11       | 2.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 10       | 2.24%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 10       | 2.24%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 8        | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 8        | 1.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 8        | 1.79%   |
| Ralink RT5372 Wireless Adapter                                                | 7        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 1.57%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                          | 7        | 1.57%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 6        | 1.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 6        | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 1.12%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 5        | 1.12%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 5        | 1.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 5        | 1.12%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 5        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 5        | 1.12%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5        | 1.12%   |
| Intel Wireless 8265 / 8275                                                    | 5        | 1.12%   |
| Intel Wireless 7260                                                           | 5        | 1.12%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 4        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.9%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 4        | 0.9%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 4        | 0.9%    |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 4        | 0.9%    |
| Ralink RT2070 Wireless Adapter                                                | 4        | 0.9%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 4        | 0.9%    |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]          | 4        | 0.9%    |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 4        | 0.9%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 3        | 0.67%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 3        | 0.67%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 3        | 0.67%   |
| Intel Wireless 7265                                                           | 3        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 801      | 49.57%  |
| Intel                                  | 407      | 25.19%  |
| Qualcomm Atheros                       | 136      | 8.42%   |
| Broadcom                               | 83       | 5.14%   |
| Nvidia                                 | 53       | 3.28%   |
| Broadcom Limited                       | 44       | 2.72%   |
| Marvell Technology Group               | 33       | 2.04%   |
| VIA Technologies                       | 14       | 0.87%   |
| Samsung Electronics                    | 9        | 0.56%   |
| Huawei Technologies                    | 7        | 0.43%   |
| Xiaomi                                 | 4        | 0.25%   |
| D-Link System                          | 4        | 0.25%   |
| ASIX Electronics                       | 4        | 0.25%   |
| Accton Technology                      | 4        | 0.25%   |
| JMicron Technology                     | 3        | 0.19%   |
| Aquantia                               | 2        | 0.12%   |
| Westell                                | 1        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.06%   |
| Qualcomm                               | 1        | 0.06%   |
| MediaTek                               | 1        | 0.06%   |
| HMD Global                             | 1        | 0.06%   |
| D-Link                                 | 1        | 0.06%   |
| 3Com                                   | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 689      | 41.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 80       | 4.84%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 61       | 3.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50       | 3.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 44       | 2.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 42       | 2.54%   |
| Intel Ethernet Connection I217-LM                                      | 42       | 2.54%   |
| Intel I211 Gigabit Network Connection                                  | 33       | 2%      |
| Intel 82566DM-2 Gigabit Network Connection                             | 33       | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 32       | 1.94%   |
| Nvidia MCP61 Ethernet                                                  | 32       | 1.94%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 25       | 1.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 24       | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                  | 22       | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 21       | 1.27%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 19       | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 18       | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                   | 16       | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 15       | 0.91%   |
| Intel 82579V Gigabit Network Connection                                | 15       | 0.91%   |
| Intel Ethernet Connection I217-V                                       | 14       | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13       | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 12       | 0.73%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 11       | 0.67%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 10       | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9        | 0.54%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 8        | 0.48%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 8        | 0.48%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express        | 8        | 0.48%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6        | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 6        | 0.36%   |
| Huawei FOA-LX9                                                         | 6        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5        | 0.3%    |
| Nvidia MCP55 Ethernet                                                  | 5        | 0.3%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 5        | 0.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1528     | 78.36%  |
| WiFi     | 414      | 21.23%  |
| Modem    | 7        | 0.36%   |
| Unknown  | 1        | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1324     | 83.64%  |
| WiFi     | 258      | 16.3%   |
| Modem    | 1        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1280     | 82.1%   |
| 2     | 242      | 15.52%  |
| 3     | 18       | 1.15%   |
| 0     | 16       | 1.03%   |
| 4     | 3        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1326     | 81.8%   |
| Yes  | 295      | 18.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 113      | 50.45%  |
| Intel                           | 43       | 19.2%   |
| Broadcom                        | 16       | 7.14%   |
| ASUSTek Computer                | 11       | 4.91%   |
| Realtek Semiconductor           | 7        | 3.13%   |
| Logitech                        | 4        | 1.79%   |
| Lite-On Technology              | 4        | 1.79%   |
| Integrated System Solution      | 4        | 1.79%   |
| Conwise Technology              | 4        | 1.79%   |
| Belkin Components               | 4        | 1.79%   |
| Qualcomm Atheros Communications | 3        | 1.34%   |
| TP-Link                         | 2        | 0.89%   |
| IMC Networks                    | 2        | 0.89%   |
| Hewlett-Packard                 | 2        | 0.89%   |
| Edimax Technology               | 2        | 0.89%   |
| Roper                           | 1        | 0.45%   |
| Dell                            | 1        | 0.45%   |
| Apple                           | 1        | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 113      | 50.45%  |
| Intel Bluetooth wireless interface                      | 18       | 8.04%   |
| Intel Wireless-AC 3168 Bluetooth                        | 7        | 3.13%   |
| Intel AX200 Bluetooth                                   | 7        | 3.13%   |
| Broadcom BCM2035 Bluetooth dongle                       | 7        | 3.13%   |
| ASUS Bluetooth Radio                                    | 5        | 2.23%   |
| Realtek  Bluetooth 4.2 Adapter                          | 4        | 1.79%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 4        | 1.79%   |
| Conwise CW6622                                          | 4        | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 1.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 3        | 1.34%   |
| Broadcom Bluetooth 3.0 Device                           | 3        | 1.34%   |
| Belkin Components Bluetooth Mini Dongle                 | 3        | 1.34%   |
| TP-Link TP-Link Bluetooth USB Adapter                   | 2        | 0.89%   |
| Realtek RTL8821A Bluetooth                              | 2        | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 2        | 0.89%   |
| Lite-On Bluetooth Device                                | 2        | 0.89%   |
| Intel AX210 Bluetooth                                   | 2        | 0.89%   |
| Intel AX201 Bluetooth                                   | 2        | 0.89%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 2        | 0.89%   |
| Integrated System Solution Bluetooth Device             | 2        | 0.89%   |
| HP Bluetooth Adapter                                    | 2        | 0.89%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2        | 0.89%   |
| Broadcom Bluetooth dongle                               | 2        | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 2        | 0.89%   |
| Roper Class 1 Bluetooth Dongle                          | 1        | 0.45%   |
| Realtek RTL8723B Bluetooth                              | 1        | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 0.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1        | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                        | 1        | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter        | 1        | 0.45%   |
| IMC Networks Wireless_Device                            | 1        | 0.45%   |
| IMC Networks Bluetooth Radio                            | 1        | 0.45%   |
| Dell Wireless 365 Bluetooth                             | 1        | 0.45%   |
| Broadcom HP Portable Bumble Bee                         | 1        | 0.45%   |
| Broadcom HP Bluethunder                                 | 1        | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 1        | 0.45%   |
| Broadcom BCM2045 Bluetooth                              | 1        | 0.45%   |
| Belkin Components F8T013 Bluetooth Adapter              | 1        | 0.45%   |
| ASUS Bluetooth Device                                   | 1        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1026     | 44.21%  |
| AMD                              | 607      | 26.15%  |
| Nvidia                           | 492      | 21.2%   |
| C-Media Electronics              | 55       | 2.37%   |
| Creative Labs                    | 41       | 1.77%   |
| VIA Technologies                 | 12       | 0.52%   |
| Texas Instruments                | 11       | 0.47%   |
| Logitech                         | 6        | 0.26%   |
| JMTek                            | 6        | 0.26%   |
| GN Netcom                        | 5        | 0.22%   |
| Plantronics                      | 4        | 0.17%   |
| Generalplus Technology           | 4        | 0.17%   |
| Tenx Technology                  | 3        | 0.13%   |
| Razer USA                        | 3        | 0.13%   |
| Ensoniq                          | 3        | 0.13%   |
| Creative Technology              | 3        | 0.13%   |
| BEHRINGER International          | 3        | 0.13%   |
| ASUSTek Computer                 | 3        | 0.13%   |
| Syntek                           | 2        | 0.09%   |
| Silicon Integrated Systems [SiS] | 2        | 0.09%   |
| Promethean Limited               | 2        | 0.09%   |
| Kingston Technology              | 2        | 0.09%   |
| ATI Technologies                 | 2        | 0.09%   |
| Zhaoxin                          | 1        | 0.04%   |
| ULi Electronics                  | 1        | 0.04%   |
| Trust                            | 1        | 0.04%   |
| Superlux digit                   | 1        | 0.04%   |
| Sunplus Technology               | 1        | 0.04%   |
| SteelSeries ApS                  | 1        | 0.04%   |
| Sony                             | 1        | 0.04%   |
| SM950T Microphone                | 1        | 0.04%   |
| Nektar                           | 1        | 0.04%   |
| Native Instruments               | 1        | 0.04%   |
| my power                         | 1        | 0.04%   |
| MCS                              | 1        | 0.04%   |
| KORG                             | 1        | 0.04%   |
| Jieli Technology                 | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |
| Evolution Electronics            | 1        | 0.04%   |
| Elite Silicon                    | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 177      | 6.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 151      | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 146      | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 139      | 5.1%    |
| AMD FCH Azalia Controller                                                         | 123      | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 95       | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 77       | 2.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 75       | 2.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 70       | 2.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 69       | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 68       | 2.5%    |
| Intel 200 Series PCH HD Audio                                                     | 66       | 2.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 63       | 2.31%   |
| AMD Trinity HDMI Audio Controller                                                 | 58       | 2.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 57       | 2.09%   |
| Nvidia High Definition Audio Controller                                           | 56       | 2.06%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 53       | 1.95%   |
| Nvidia GF108 High Definition Audio Controller                                     | 47       | 1.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 39       | 1.43%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 38       | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 35       | 1.28%   |
| Nvidia MCP61 High Definition Audio                                                | 34       | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 34       | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 34       | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                        | 30       | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 29       | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                                     | 28       | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                | 28       | 1.03%   |
| AMD Starship/Matisse HD Audio Controller                                          | 25       | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                                | 24       | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 24       | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 23       | 0.84%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 21       | 0.77%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 19       | 0.7%    |
| Nvidia GK106 HDMI Audio Controller                                                | 18       | 0.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 18       | 0.66%   |
| AMD Kabini HDMI/DP Audio                                                          | 18       | 0.66%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 18       | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 17       | 0.62%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 17       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 509      | 27.47%  |
| Kingston                   | 364      | 19.64%  |
| Samsung Electronics        | 198      | 10.69%  |
| SK hynix                   | 185      | 9.98%   |
| Micron Technology          | 94       | 5.07%   |
| Crucial                    | 72       | 3.89%   |
| Kingmax                    | 69       | 3.72%   |
| Corsair                    | 62       | 3.35%   |
| Nanya Technology           | 60       | 3.24%   |
| G.Skill                    | 55       | 2.97%   |
| Elpida                     | 25       | 1.35%   |
| Team                       | 18       | 0.97%   |
| Patriot                    | 15       | 0.81%   |
| CSX                        | 15       | 0.81%   |
| Transcend                  | 13       | 0.7%    |
| Ramaxel Technology         | 13       | 0.7%    |
| A-DATA Technology          | 11       | 0.59%   |
| Qimonda                    | 7        | 0.38%   |
| Melco                      | 5        | 0.27%   |
| Goodram                    | 5        | 0.27%   |
| OCZ                        | 4        | 0.22%   |
| Hikvision                  | 4        | 0.22%   |
| H                          | 4        | 0.22%   |
| Apacer                     | 4        | 0.22%   |
| Smart                      | 3        | 0.16%   |
| Kingmax Semiconductor      | 3        | 0.16%   |
| GeIL                       | 3        | 0.16%   |
| 48spaces                   | 3        | 0.16%   |
| TwinMOS                    | 2        | 0.11%   |
| Toshiba                    | 2        | 0.11%   |
| Silicon Power              | 2        | 0.11%   |
| Multilaser                 | 2        | 0.11%   |
| Unknown                    | 2        | 0.11%   |
| Uroad                      | 1        | 0.05%   |
| Unknown (7F7F7F7F7F970000) | 1        | 0.05%   |
| Unifosa                    | 1        | 0.05%   |
| TakeMS                     | 1        | 0.05%   |
| Ramos Technology           | 1        | 0.05%   |
| Princeton                  | 1        | 0.05%   |
| Mushkin                    | 1        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                   | 47       | 2.15%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 46       | 2.11%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 44       | 2.01%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 27       | 1.24%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 24       | 1.1%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 23       | 1.05%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 23       | 1.05%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 22       | 1.01%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 20       | 0.92%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 19       | 0.87%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 18       | 0.82%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 18       | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 17       | 0.78%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 17       | 0.78%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 14       | 0.64%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 14       | 0.64%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 13       | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s            | 13       | 0.59%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 13       | 0.59%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 12       | 0.55%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s | 12       | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 11       | 0.5%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 11       | 0.5%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 11       | 0.5%    |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 11       | 0.5%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 11       | 0.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 11       | 0.5%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 11       | 0.5%    |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 10       | 0.46%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 10       | 0.46%   |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s   | 10       | 0.46%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 10       | 0.46%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 9        | 0.41%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 9        | 0.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s           | 8        | 0.37%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 8        | 0.37%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                | 8        | 0.37%   |
| Unknown RAM Module 1024MB DIMM                         | 8        | 0.37%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s    | 8        | 0.37%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s | 8        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 630      | 39.65%  |
| DDR4    | 295      | 18.57%  |
| DDR2    | 231      | 14.54%  |
| Unknown | 192      | 12.08%  |
| SDRAM   | 185      | 11.64%  |
| DDR     | 54       | 3.4%    |
| DDR5    | 2        | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1446     | 96.27%  |
| SODIMM  | 51       | 3.4%    |
| RIMM    | 4        | 0.27%   |
| FB-DIMM | 1        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 553      | 30.77%  |
| 2048  | 535      | 29.77%  |
| 8192  | 355      | 19.76%  |
| 1024  | 228      | 12.69%  |
| 16384 | 64       | 3.56%   |
| 512   | 38       | 2.11%   |
| 32768 | 13       | 0.72%   |
| 256   | 7        | 0.39%   |
| 16    | 2        | 0.11%   |
| 128   | 1        | 0.06%   |
| 13    | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 330      | 18.19%  |
| 1333    | 303      | 16.7%   |
| 800     | 210      | 11.58%  |
| 667     | 124      | 6.84%   |
| Unknown | 101      | 5.57%   |
| 2400    | 95       | 5.24%   |
| 2133    | 75       | 4.13%   |
| 1866    | 69       | 3.8%    |
| 3200    | 47       | 2.59%   |
| 1867    | 45       | 2.48%   |
| 1066    | 36       | 1.98%   |
| 533     | 30       | 1.65%   |
| 400     | 30       | 1.65%   |
| 3600    | 27       | 1.49%   |
| 2667    | 27       | 1.49%   |
| 2666    | 21       | 1.16%   |
| 1067    | 18       | 0.99%   |
| 2048    | 17       | 0.94%   |
| 1800    | 16       | 0.88%   |
| 3733    | 15       | 0.83%   |
| 3000    | 15       | 0.83%   |
| 1639    | 14       | 0.77%   |
| 2933    | 13       | 0.72%   |
| 3400    | 12       | 0.66%   |
| 3466    | 11       | 0.61%   |
| 333     | 10       | 0.55%   |
| 49926   | 9        | 0.5%    |
| 2000    | 8        | 0.44%   |
| 1648    | 7        | 0.39%   |
| 1334    | 7        | 0.39%   |
| 3334    | 5        | 0.28%   |
| 1331    | 5        | 0.28%   |
| 266     | 5        | 0.28%   |
| 3800    | 4        | 0.22%   |
| 2733    | 4        | 0.22%   |
| 1400    | 4        | 0.22%   |
| 3333    | 3        | 0.17%   |
| 3151    | 3        | 0.17%   |
| 3066    | 3        | 0.17%   |
| 133     | 3        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 53       | 51.96%  |
| Samsung Electronics   | 24       | 23.53%  |
| Canon                 | 12       | 11.76%  |
| Brother Industries    | 6        | 5.88%   |
| Seiko Epson           | 2        | 1.96%   |
| QinHeng Electronics   | 2        | 1.96%   |
| STMicroelectronics    | 1        | 0.98%   |
| Lexmark International | 1        | 0.98%   |
| Dymo-CoStar           | 1        | 0.98%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2620 All-in-One Printer                        | 10       | 9.71%   |
| Samsung M2020 Series                                      | 5        | 4.85%   |
| HP OfficeJet 6950                                         | 5        | 4.85%   |
| Samsung ML-2010P Mono Laser Printer                       | 4        | 3.88%   |
| Samsung ML-1640 Series Laser Printer                      | 3        | 2.91%   |
| Samsung C48x Series Color Laser Multifunction Printer     | 3        | 2.91%   |
| HP LaserJet 1020                                          | 3        | 2.91%   |
| HP Deskjet 1050 J410                                      | 3        | 2.91%   |
| Samsung SCX-3400 Series                                   | 2        | 1.94%   |
| Samsung ML-1660 Series                                    | 2        | 1.94%   |
| QinHeng CH340S                                            | 2        | 1.94%   |
| HP LaserJet P1005                                         | 2        | 1.94%   |
| HP LaserJet 1018                                          | 2        | 1.94%   |
| HP LaserJet 1010                                          | 2        | 1.94%   |
| HP DeskJet F4100 Printer series                           | 2        | 1.94%   |
| HP Deskjet F2280 series                                   | 2        | 1.94%   |
| HP Deskjet 3520 series                                    | 2        | 1.94%   |
| HP DeskJet 2130 series                                    | 2        | 1.94%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.94%   |
| Brother HL-L2300D series                                  | 2        | 1.94%   |
| Brother HL-1110 series                                    | 2        | 1.94%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.97%   |
| Seiko Epson WF-3010 Series                                | 1        | 0.97%   |
| Seiko Epson ET-2600 Series                                | 1        | 0.97%   |
| Samsung SCX-4623 Series                                   | 1        | 0.97%   |
| Samsung SCX-3200 Series                                   | 1        | 0.97%   |
| Samsung ML-1630 Series                                    | 1        | 0.97%   |
| Samsung M2070 Series                                      | 1        | 0.97%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.97%   |
| Lexmark International InkJet Color Printer                | 1        | 0.97%   |
| HP OfficeJet Pro 6970                                     | 1        | 0.97%   |
| HP LaserJet 2600n                                         | 1        | 0.97%   |
| HP LaserJet 1300                                          | 1        | 0.97%   |
| HP LaserJet 1000                                          | 1        | 0.97%   |
| HP Ink Tank Wireless 410 series                           | 1        | 0.97%   |
| HP HP LaserJet M14-M17                                    | 1        | 0.97%   |
| HP DeskJet F2100 Printer series                           | 1        | 0.97%   |
| HP Deskjet D1500 series                                   | 1        | 0.97%   |
| HP DeskJet D1360                                          | 1        | 0.97%   |
| HP DeskJet 959c                                           | 1        | 0.97%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 9        | 69.23%  |
| Seiko Epson     | 2        | 15.38%  |
| Mustek Systems  | 1        | 7.69%   |
| Hewlett-Packard | 1        | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                      | 4        | 30.77%  |
| Canon CanoScan LIDE 25                                  | 2        | 15.38%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 7.69%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1        | 7.69%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1        | 7.69%   |
| HP ScanJet 3670                                         | 1        | 7.69%   |
| Canon CanoScan LiDE 120                                 | 1        | 7.69%   |
| Canon CanoScan LiDE 110                                 | 1        | 7.69%   |
| Canon CanoScan LiDE 100                                 | 1        | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 48       | 24.74%  |
| Microdia                      | 32       | 16.49%  |
| KYE Systems (Mouse Systems)   | 16       | 8.25%   |
| Microsoft                     | 15       | 7.73%   |
| Z-Star Microelectronics       | 14       | 7.22%   |
| GEMBIRD                       | 11       | 5.67%   |
| Pixart Imaging                | 7        | 3.61%   |
| Cubeternet                    | 6        | 3.09%   |
| Samsung Electronics           | 5        | 2.58%   |
| Trust                         | 4        | 2.06%   |
| Chicony Electronics           | 4        | 2.06%   |
| Apple                         | 4        | 2.06%   |
| Sunplus Innovation Technology | 3        | 1.55%   |
| Realtek Semiconductor         | 3        | 1.55%   |
| Generalplus Technology        | 3        | 1.55%   |
| Creative Technology           | 3        | 1.55%   |
| Aveo Technology               | 3        | 1.55%   |
| Arkmicro Technologies         | 3        | 1.55%   |
| MacroSilicon                  | 2        | 1.03%   |
| LG Electronics                | 2        | 1.03%   |
| Unknown                       | 1        | 0.52%   |
| Novatek Microelectronics      | 1        | 0.52%   |
| Jieli Technology              | 1        | 0.52%   |
| IMC Networks                  | 1        | 0.52%   |
| Hewlett-Packard               | 1        | 0.52%   |
| 2M UVC CAMERA                 | 1        | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Microdia Camera                                       | 16       | 8.21%   |
| Logitech Webcam C270                                  | 11       | 5.64%   |
| Microdia Sonix USB 2.0 Camera                         | 9        | 4.62%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 9        | 4.62%   |
| Logitech Webcam C600                                  | 7        | 3.59%   |
| Z-Star Vimicro USB Camera (Altair)                    | 6        | 3.08%   |
| Logitech HD Pro Webcam C920                           | 6        | 3.08%   |
| Z-Star Venus USB2.0 Camera                            | 5        | 2.56%   |
| Samsung Galaxy series, misc. (MTP mode)               | 5        | 2.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 5        | 2.56%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 5        | 2.56%   |
| Microsoft LifeCam HD-3000                             | 4        | 2.05%   |
| Logitech Webcam C170                                  | 4        | 2.05%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320        | 4        | 2.05%   |
| Cubeternet USB2.0 Camera                              | 4        | 2.05%   |
| Sunplus FULL HD webcam                                | 3        | 1.54%   |
| Microsoft LifeCam VX-2000                             | 3        | 1.54%   |
| Microdia USB 2.0 Camera                               | 3        | 1.54%   |
| Logitech Webcam C250                                  | 3        | 1.54%   |
| Logitech QuickCam Pro 9000                            | 3        | 1.54%   |
| Logitech HD Webcam C525                               | 3        | 1.54%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 3        | 1.54%   |
| Arkmicro USB2.0 PC CAMERA                             | 3        | 1.54%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                    | 3        | 1.54%   |
| Z-Star Saturn USB 2.0 Camera                          | 2        | 1.03%   |
| Trust 17676 Webcam                                    | 2        | 1.03%   |
| Microsoft LifeCam VX-700                              | 2        | 1.03%   |
| Microsoft LifeCam VX-500 [1357]                       | 2        | 1.03%   |
| Microdia Integrated Camera                            | 2        | 1.03%   |
| Logitech Webcam C310                                  | 2        | 1.03%   |
| Logitech Webcam C210                                  | 2        | 1.03%   |
| Logitech QuickCam Communicate Deluxe/S7500            | 2        | 1.03%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 1.03%   |
| KYE Systems (Mouse Systems) FaceCam 320X              | 2        | 1.03%   |
| Generalplus GENERAL WEBCAM                            | 2        | 1.03%   |
| GEMBIRD USB2.0 PC CAMERA                              | 2        | 1.03%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 2        | 1.03%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]            | 2        | 1.03%   |
| Aveo USB2.0 Camera                                    | 2        | 1.03%   |
| Z-Star Vega USB 2.0 Camera                            | 1        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Reiner SCT Kartensysteme  | 2        | 33.33%  |
| Alcor Micro               | 2        | 33.33%  |
| Gemalto (was Gemplus)     | 1        | 16.67%  |
| Aladdin Knowledge Systems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 2        | 33.33%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 16.67%  |
| Aladdin Knowledge Systems Token JC                                         | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1366     | 85.7%   |
| 1     | 213      | 13.36%  |
| 2     | 13       | 0.82%   |
| 5     | 1        | 0.06%   |
| 4     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 175      | 73.53%  |
| Net/wireless             | 24       | 10.08%  |
| Camera                   | 10       | 4.2%    |
| Unassigned class         | 7        | 2.94%   |
| Communication controller | 7        | 2.94%   |
| Chipcard                 | 5        | 2.1%    |
| Sound                    | 3        | 1.26%   |
| Net/ethernet             | 2        | 0.84%   |
| Card reader              | 2        | 0.84%   |
| Storage                  | 1        | 0.42%   |
| Fingerprint reader       | 1        | 0.42%   |
| Bluetooth                | 1        | 0.42%   |

