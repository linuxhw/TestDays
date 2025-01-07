Debian 10 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 10.

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

Total: 1100

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [9f933e3704](https://linux-hardware.org/?probe=9f933e3704) | Nov 22, 2024 |
| ASRock        | B250M Performance           | [f157e625f8](https://linux-hardware.org/?probe=f157e625f8) | Sep 13, 2024 |
| Supermicro    | X9SCL/X9SCMA                | [bdcc9549b9](https://linux-hardware.org/?probe=bdcc9549b9) | Aug 12, 2024 |
| Unknown       | Unknown                     | [a66eadcbfc](https://linux-hardware.org/?probe=a66eadcbfc) | Aug 06, 2024 |
| Wincor Nix... | HU101                       | [39358ba4bb](https://linux-hardware.org/?probe=39358ba4bb) | Jun 26, 2024 |
| ASUSTek       | Z97-P                       | [a15cc3044a](https://linux-hardware.org/?probe=a15cc3044a) | Jun 10, 2024 |
| TYAN Compu... | S8225                       | [b94a2aaf90](https://linux-hardware.org/?probe=b94a2aaf90) | Jun 04, 2024 |
| ECS           | X79R-AX                     | [1312c42784](https://linux-hardware.org/?probe=1312c42784) | May 26, 2024 |
| ASUSTek       | P8Z77-V LX                  | [d439bfaa64](https://linux-hardware.org/?probe=d439bfaa64) | May 11, 2024 |
| Unknown       | Unknown                     | [b8c681a7fb](https://linux-hardware.org/?probe=b8c681a7fb) | Apr 15, 2024 |
| Dinson        | Unknown                     | [2aff8e107a](https://linux-hardware.org/?probe=2aff8e107a) | Apr 01, 2024 |
| Unknown       | Unknown                     | [dcdb71e975](https://linux-hardware.org/?probe=dcdb71e975) | Mar 28, 2024 |
| ASRockRack    | B450D4U-V1L                 | [4611e234b8](https://linux-hardware.org/?probe=4611e234b8) | Mar 14, 2024 |
| Gigabyte      | H97M-HD3                    | [912c171bc5](https://linux-hardware.org/?probe=912c171bc5) | Mar 05, 2024 |
| ASUSTek       | Z87M-PLUS                   | [8d1d5db604](https://linux-hardware.org/?probe=8d1d5db604) | Feb 11, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [f5e8165d7b](https://linux-hardware.org/?probe=f5e8165d7b) | Jan 17, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [60694d3668](https://linux-hardware.org/?probe=60694d3668) | Jan 16, 2024 |
| ASRock        | G41M-VS3                    | [96266413d3](https://linux-hardware.org/?probe=96266413d3) | Dec 28, 2023 |
| MSI           | B75A-G43                    | [70c44f3ff8](https://linux-hardware.org/?probe=70c44f3ff8) | Dec 22, 2023 |
| Gigabyte      | H97M-HD3                    | [aa52a8ceac](https://linux-hardware.org/?probe=aa52a8ceac) | Dec 02, 2023 |
| ASUSTek       | P8H61-M LE                  | [86dd25c85a](https://linux-hardware.org/?probe=86dd25c85a) | Oct 31, 2023 |
| Gigabyte      | H97M-HD3                    | [0d712d2765](https://linux-hardware.org/?probe=0d712d2765) | Oct 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [eda9b7d2e8](https://linux-hardware.org/?probe=eda9b7d2e8) | Jul 10, 2023 |
| Dell          | 09KPNV A01                  | [596389ea27](https://linux-hardware.org/?probe=596389ea27) | Jul 10, 2023 |
| MSI           | MAG B560 TORPEDO            | [1327fb98ac](https://linux-hardware.org/?probe=1327fb98ac) | Jul 04, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d704e4a5d3](https://linux-hardware.org/?probe=d704e4a5d3) | Jun 14, 2023 |
| Supermicro    | X11SCD-F                    | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [365eeba4c9](https://linux-hardware.org/?probe=365eeba4c9) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [df7c4a738e](https://linux-hardware.org/?probe=df7c4a738e) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| MSI           | 760GM-P23                   | [05c4685974](https://linux-hardware.org/?probe=05c4685974) | May 18, 2023 |
| ASUSTek       | Rampage IV FORMULA          | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 08HPGT A02                  | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| ASUSTek       | P11C-X Series               | [2ab6f2745c](https://linux-hardware.org/?probe=2ab6f2745c) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [55f8d9f172](https://linux-hardware.org/?probe=55f8d9f172) | Apr 14, 2023 |
| Dell          | 03V7GF A01                  | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| Dell          | 03V7GF A02                  | [cb72d83566](https://linux-hardware.org/?probe=cb72d83566) | Apr 12, 2023 |
| Lenovo        | 32E6 NOK                    | [c1d51dba1d](https://linux-hardware.org/?probe=c1d51dba1d) | Apr 11, 2023 |
| Pegatron      | Benicia                     | [96ba9b6040](https://linux-hardware.org/?probe=96ba9b6040) | Apr 04, 2023 |
| HP            | 1495                        | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| Unknown       | FT2000plus Generic Borad... | [43ec5396f3](https://linux-hardware.org/?probe=43ec5396f3) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [c305aa7562](https://linux-hardware.org/?probe=c305aa7562) | Mar 28, 2023 |
| Iskratel, ... | IN6011AX                    | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| Gigabyte      | H97M-HD3                    | [ab4dce8483](https://linux-hardware.org/?probe=ab4dce8483) | Mar 22, 2023 |
| ASUSTek       | PRIME Z370-P                | [82e7940a77](https://linux-hardware.org/?probe=82e7940a77) | Mar 15, 2023 |
| ASRock        | B450 Pro4                   | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| Lenovo        | MAHOBAY                     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Gigabyte      | H55M-S2H                    | [545e7119e9](https://linux-hardware.org/?probe=545e7119e9) | Mar 04, 2023 |
| Dell          | 0CNWVK A02                  | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| ASUSTek       | PRIME B250-A                | [c686d3d123](https://linux-hardware.org/?probe=c686d3d123) | Jan 31, 2023 |
| ASUSTek       | M2N-E                       | [2a7342c2cb](https://linux-hardware.org/?probe=2a7342c2cb) | Jan 09, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | [8b0b477726](https://linux-hardware.org/?probe=8b0b477726) | Jan 02, 2023 |
| ASRock        | A320M-DGS                   | [a9df519d4f](https://linux-hardware.org/?probe=a9df519d4f) | Dec 31, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| ASRock        | B450 Pro4                   | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| ASRock        | X570 Pro4                   | [713a2bcaf4](https://linux-hardware.org/?probe=713a2bcaf4) | Dec 15, 2022 |
| ASRock        | B75M R2.0                   | [93dc9d7b3e](https://linux-hardware.org/?probe=93dc9d7b3e) | Dec 06, 2022 |
| ASUSTek       | P5K                         | [8e3fef0d6b](https://linux-hardware.org/?probe=8e3fef0d6b) | Dec 06, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f5a5a30379](https://linux-hardware.org/?probe=f5a5a30379) | Dec 01, 2022 |
| Dell          | 0CNWVK A02                  | [726074bce6](https://linux-hardware.org/?probe=726074bce6) | Nov 09, 2022 |
| Dell          | 0CNWVK A02                  | [3ac38eb9be](https://linux-hardware.org/?probe=3ac38eb9be) | Nov 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [0fa75a005b](https://linux-hardware.org/?probe=0fa75a005b) | Nov 08, 2022 |
| ASUSTek       | P8H67-M LX                  | [277212bfc3](https://linux-hardware.org/?probe=277212bfc3) | Nov 08, 2022 |
| IBM           | M97IP SIT                   | [78703d62ae](https://linux-hardware.org/?probe=78703d62ae) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | [0301b99674](https://linux-hardware.org/?probe=0301b99674) | Nov 07, 2022 |
| Unknown       | Unknown                     | [2032d5239e](https://linux-hardware.org/?probe=2032d5239e) | Nov 05, 2022 |
| Intel         | ChiefRiver                  | [1e1f44f251](https://linux-hardware.org/?probe=1e1f44f251) | Nov 04, 2022 |
| Dell          | 0CNWVK A02                  | [9017e31507](https://linux-hardware.org/?probe=9017e31507) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | [64e4630da2](https://linux-hardware.org/?probe=64e4630da2) | Nov 04, 2022 |
| Gigabyte      | H410M S2H V3                | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [8e957f305e](https://linux-hardware.org/?probe=8e957f305e) | Oct 26, 2022 |
| Pegatron      | Benicia                     | [3735dca311](https://linux-hardware.org/?probe=3735dca311) | Oct 25, 2022 |
| Gigabyte      | E350N WIN8                  | [bff16c4d6c](https://linux-hardware.org/?probe=bff16c4d6c) | Oct 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| Unknown       | Unknown                     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| HP            | 2175                        | [97d08b25c7](https://linux-hardware.org/?probe=97d08b25c7) | Sep 08, 2022 |
| Dell          | 09KPNV A00                  | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| MSI           | E350IA-E45                  | [d1d570a455](https://linux-hardware.org/?probe=d1d570a455) | Aug 28, 2022 |
| retsamarre... | Unknown                     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| HP            | 2187 A01                    | [ab44144f07](https://linux-hardware.org/?probe=ab44144f07) | Aug 22, 2022 |
| MSI           | G31M3                       | [3bb7906f56](https://linux-hardware.org/?probe=3bb7906f56) | Aug 20, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
| Intel         | DH61AG AAG23736-505         | [7fd3a18899](https://linux-hardware.org/?probe=7fd3a18899) | Jul 28, 2022 |
| ASUSTek       | P5K                         | [f3c730853e](https://linux-hardware.org/?probe=f3c730853e) | Jul 18, 2022 |
| ASUSTek       | P5K                         | [581ed01922](https://linux-hardware.org/?probe=581ed01922) | Jul 18, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [b806c8fc09](https://linux-hardware.org/?probe=b806c8fc09) | Jul 07, 2022 |
| Supermicro    | X10SRW-FB                   | [17c2ecc642](https://linux-hardware.org/?probe=17c2ecc642) | Jul 07, 2022 |
| ASUSTek       | H81M-P PLUS                 | [6c18625cb3](https://linux-hardware.org/?probe=6c18625cb3) | Jun 27, 2022 |
| ASUSTek       | P5K                         | [e401eb71bc](https://linux-hardware.org/?probe=e401eb71bc) | Jun 27, 2022 |
| EVGA          | 151-HE-E999                 | [2725b53d0c](https://linux-hardware.org/?probe=2725b53d0c) | Jun 27, 2022 |
| MSI           | Z170A GAMING PRO            | [70e3e75c86](https://linux-hardware.org/?probe=70e3e75c86) | Jun 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c2e6e05eea](https://linux-hardware.org/?probe=c2e6e05eea) | Jun 25, 2022 |
| ASUSTek       | H81M-P PLUS                 | [b91a1b0ded](https://linux-hardware.org/?probe=b91a1b0ded) | Jun 22, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a6cb0e21fc](https://linux-hardware.org/?probe=a6cb0e21fc) | Jun 17, 2022 |
| MSI           | E350IA-E45                  | [048b860a2e](https://linux-hardware.org/?probe=048b860a2e) | Jun 05, 2022 |
| MSI           | E350IA-E45                  | [cf188991af](https://linux-hardware.org/?probe=cf188991af) | Jun 04, 2022 |
| ASUSTek       | H81M-P PLUS                 | [8c60f1e8e0](https://linux-hardware.org/?probe=8c60f1e8e0) | Jun 03, 2022 |
| ASUSTek       | P5K                         | [2e621739e6](https://linux-hardware.org/?probe=2e621739e6) | Jun 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3a7e7b471a](https://linux-hardware.org/?probe=3a7e7b471a) | Jun 01, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [33ac99c04e](https://linux-hardware.org/?probe=33ac99c04e) | May 30, 2022 |
| ASUSTek       | P5K                         | [b816732403](https://linux-hardware.org/?probe=b816732403) | May 27, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [280302cc7b](https://linux-hardware.org/?probe=280302cc7b) | May 20, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [6e8eed720d](https://linux-hardware.org/?probe=6e8eed720d) | May 20, 2022 |
| MSI           | A68HM-E33 V2                | [dedc4ce0d5](https://linux-hardware.org/?probe=dedc4ce0d5) | May 10, 2022 |
| HP            | 158A                        | [842aab71bd](https://linux-hardware.org/?probe=842aab71bd) | May 06, 2022 |
| MSI           | E350IA-E45                  | [8271a7f1d5](https://linux-hardware.org/?probe=8271a7f1d5) | Apr 23, 2022 |
| MSI           | 970A-G45                    | [35f8f0652d](https://linux-hardware.org/?probe=35f8f0652d) | Apr 21, 2022 |
| ASUSTek       | PRIME H510M-A               | [59fb2af2c2](https://linux-hardware.org/?probe=59fb2af2c2) | Apr 18, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [f0d5c82d74](https://linux-hardware.org/?probe=f0d5c82d74) | Apr 17, 2022 |
| HP            | 2129                        | [be64efcffd](https://linux-hardware.org/?probe=be64efcffd) | Apr 15, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| MSI           | N3150I ECO                  | [afe5c622e2](https://linux-hardware.org/?probe=afe5c622e2) | Apr 11, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| ASRock        | Z97 Pro3                    | [68397184cf](https://linux-hardware.org/?probe=68397184cf) | Apr 06, 2022 |
| Packard Be... | Cuba MS-7301                | [1a89e021cd](https://linux-hardware.org/?probe=1a89e021cd) | Apr 03, 2022 |
| Lenovo        | QiTianM7150                 | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| Gigabyte      | H97M-HD3                    | [9027088a52](https://linux-hardware.org/?probe=9027088a52) | Mar 28, 2022 |
| Lenovo        | 361A SDK0K17763 WIN         | [334c4c0ff2](https://linux-hardware.org/?probe=334c4c0ff2) | Mar 27, 2022 |
| Gigabyte      | H61M-USB3H                  | [f852a0cb0d](https://linux-hardware.org/?probe=f852a0cb0d) | Mar 26, 2022 |
| MSI           | E350IA-E45                  | [84a19b6203](https://linux-hardware.org/?probe=84a19b6203) | Mar 21, 2022 |
| Dell          | 0P611C A00                  | [0c433bca90](https://linux-hardware.org/?probe=0c433bca90) | Mar 18, 2022 |
| Dell          | 0P611C A00                  | [72593cf88a](https://linux-hardware.org/?probe=72593cf88a) | Mar 16, 2022 |
| Dell          | 0P611C A00                  | [8acced42b7](https://linux-hardware.org/?probe=8acced42b7) | Mar 06, 2022 |
| ASUSTek       | PRIME H510M-A               | [6381e8c673](https://linux-hardware.org/?probe=6381e8c673) | Mar 06, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [be30358301](https://linux-hardware.org/?probe=be30358301) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | [efb5f5ca61](https://linux-hardware.org/?probe=efb5f5ca61) | Mar 05, 2022 |
| Dell          | 0YXT71 A03                  | [4ac263a1a4](https://linux-hardware.org/?probe=4ac263a1a4) | Mar 04, 2022 |
| Dell          | 0YXT71 A03                  | [73b9b32509](https://linux-hardware.org/?probe=73b9b32509) | Mar 03, 2022 |
| Lenovo        | MAHOBAY                     | [cd7e96054b](https://linux-hardware.org/?probe=cd7e96054b) | Mar 01, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [6c23424026](https://linux-hardware.org/?probe=6c23424026) | Feb 28, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| Gigabyte      | H97M-HD3                    | [46b9019417](https://linux-hardware.org/?probe=46b9019417) | Feb 12, 2022 |
| ASRock        | Z68 Pro3 Gen3               | [01677c38f7](https://linux-hardware.org/?probe=01677c38f7) | Feb 11, 2022 |
| ASRock        | A320M-DGS                   | [c8857db260](https://linux-hardware.org/?probe=c8857db260) | Feb 03, 2022 |
| ASRock        | A320M-DGS                   | [be8b394e63](https://linux-hardware.org/?probe=be8b394e63) | Feb 03, 2022 |
| Gigabyte      | H110M-S2H-CF                | [fe5bd0b5ed](https://linux-hardware.org/?probe=fe5bd0b5ed) | Jan 29, 2022 |
| MSI           | A68HM-E33 V2                | [42abbebf28](https://linux-hardware.org/?probe=42abbebf28) | Jan 29, 2022 |
| ASRock        | ION3D-HT                    | [dc36b83c20](https://linux-hardware.org/?probe=dc36b83c20) | Jan 26, 2022 |
| ASRock        | B560M-ITX/ac                | [a09767a55e](https://linux-hardware.org/?probe=a09767a55e) | Jan 20, 2022 |
| Supermicro    | C7SIM-Q                     | [e4919133a9](https://linux-hardware.org/?probe=e4919133a9) | Jan 05, 2022 |
| Gigabyte      | GA-970A-D3                  | [98280b3f37](https://linux-hardware.org/?probe=98280b3f37) | Jan 04, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [8de00c21aa](https://linux-hardware.org/?probe=8de00c21aa) | Jan 01, 2022 |
| ASUSTek       | PRIME B350M-A               | [7843ddc3fb](https://linux-hardware.org/?probe=7843ddc3fb) | Dec 24, 2021 |
| Dell          | 042P49 A01                  | [631c0da1c5](https://linux-hardware.org/?probe=631c0da1c5) | Dec 15, 2021 |
| Supermicro    | X9SCL/X9SCM                 | [9c415e153b](https://linux-hardware.org/?probe=9c415e153b) | Dec 10, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [402d467e5c](https://linux-hardware.org/?probe=402d467e5c) | Nov 28, 2021 |
| SixForOne     | 64Megaspeed                 | [f85bf8ab77](https://linux-hardware.org/?probe=f85bf8ab77) | Nov 24, 2021 |
| SixForOne     | 64Megaspeed                 | [1cba9688c0](https://linux-hardware.org/?probe=1cba9688c0) | Nov 24, 2021 |
| ASUSTek       | P7P55D PRO                  | [1103284e51](https://linux-hardware.org/?probe=1103284e51) | Nov 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [3c083fe97c](https://linux-hardware.org/?probe=3c083fe97c) | Nov 15, 2021 |
| Gateway       | SX2185                      | [0e422edb56](https://linux-hardware.org/?probe=0e422edb56) | Nov 15, 2021 |
| Acer          | Batman A01                  | [707f27e3e8](https://linux-hardware.org/?probe=707f27e3e8) | Oct 31, 2021 |
| Gigabyte      | H110M-S2H-CF                | [fbaa649304](https://linux-hardware.org/?probe=fbaa649304) | Oct 30, 2021 |
| Unknown       | Phitronics H55-M            | [df6d3817cb](https://linux-hardware.org/?probe=df6d3817cb) | Oct 28, 2021 |
| MSI           | GF615M-P33                  | [79851e843c](https://linux-hardware.org/?probe=79851e843c) | Oct 27, 2021 |
| ASRock        | X570 PG Velocita            | [f0411fba64](https://linux-hardware.org/?probe=f0411fba64) | Oct 27, 2021 |
| ASUSTek       | P7P55D PRO                  | [8a6b85a2d2](https://linux-hardware.org/?probe=8a6b85a2d2) | Oct 24, 2021 |
| Dell          | 0P611C A00                  | [0693495a61](https://linux-hardware.org/?probe=0693495a61) | Oct 11, 2021 |
| ASUSTek       | P8P67 PRO                   | [13fbf3ab3d](https://linux-hardware.org/?probe=13fbf3ab3d) | Oct 09, 2021 |
| Gigabyte      | H61M-S2PV                   | [727cc6a560](https://linux-hardware.org/?probe=727cc6a560) | Oct 07, 2021 |
| ASUSTek       | PRIME X570-PRO              | [299d4c5a32](https://linux-hardware.org/?probe=299d4c5a32) | Sep 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [150644b98c](https://linux-hardware.org/?probe=150644b98c) | Sep 28, 2021 |
| Dell          | 0M017G A00                  | [e21c86fd3e](https://linux-hardware.org/?probe=e21c86fd3e) | Sep 24, 2021 |
| Supermicro    | X9SCL/X9SCM                 | [eb152f6d8d](https://linux-hardware.org/?probe=eb152f6d8d) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [23d68ab2ea](https://linux-hardware.org/?probe=23d68ab2ea) | Sep 20, 2021 |
| Dell          | 0M017G A00                  | [7ccc604345](https://linux-hardware.org/?probe=7ccc604345) | Sep 20, 2021 |
| Dell          | 0M017G A00                  | [b4ecd86a69](https://linux-hardware.org/?probe=b4ecd86a69) | Sep 18, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [8750af4b33](https://linux-hardware.org/?probe=8750af4b33) | Sep 16, 2021 |
| Wistron       | ProLiant ML110 G6           | [7deb832fbd](https://linux-hardware.org/?probe=7deb832fbd) | Sep 14, 2021 |
| HP            | 8704                        | [b26e444f12](https://linux-hardware.org/?probe=b26e444f12) | Sep 12, 2021 |
| MSI           | MEG X299 CREATION           | [f6eed137f3](https://linux-hardware.org/?probe=f6eed137f3) | Sep 12, 2021 |
| ASUSTek       | P8H67-M PRO                 | [5027b9aa4d](https://linux-hardware.org/?probe=5027b9aa4d) | Sep 09, 2021 |
| Biostar       | A780L3C                     | [65fe5eaa0f](https://linux-hardware.org/?probe=65fe5eaa0f) | Sep 08, 2021 |
| MSI           | MEG X299 CREATION           | [856c31d8d4](https://linux-hardware.org/?probe=856c31d8d4) | Sep 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [ee46f7aa7d](https://linux-hardware.org/?probe=ee46f7aa7d) | Sep 07, 2021 |
| ASUSTek       | P8H67-M PRO                 | [33d31c555e](https://linux-hardware.org/?probe=33d31c555e) | Sep 02, 2021 |
| MSI           | A88XM-E35                   | [66070c788f](https://linux-hardware.org/?probe=66070c788f) | Sep 01, 2021 |
| Gigabyte      | MCMLUAB-00                  | [ba6aa808a1](https://linux-hardware.org/?probe=ba6aa808a1) | Aug 31, 2021 |
| YANYU         | M9F baytrail                | [0e5100e716](https://linux-hardware.org/?probe=0e5100e716) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | [0bf997753c](https://linux-hardware.org/?probe=0bf997753c) | Aug 29, 2021 |
| Dell          | 042P49 A02                  | [b3c942c238](https://linux-hardware.org/?probe=b3c942c238) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | [a88269301b](https://linux-hardware.org/?probe=a88269301b) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | [25b17f5647](https://linux-hardware.org/?probe=25b17f5647) | Aug 23, 2021 |
| HP            | 0A58h                       | [e1d8370cba](https://linux-hardware.org/?probe=e1d8370cba) | Aug 20, 2021 |
| Dell          | 0HY9JP A02                  | [8da5fad507](https://linux-hardware.org/?probe=8da5fad507) | Aug 20, 2021 |
| Supermicro    | X10SRW-FB                   | [115f0bc999](https://linux-hardware.org/?probe=115f0bc999) | Aug 20, 2021 |
| ASUSTek       | M5A97 R2.0                  | [1c59d4f975](https://linux-hardware.org/?probe=1c59d4f975) | Aug 19, 2021 |
| Gigabyte      | B560M DS3H                  | [6972f0e79d](https://linux-hardware.org/?probe=6972f0e79d) | Aug 18, 2021 |
| ASRock        | B450 Steel Legend           | [c76e5dd087](https://linux-hardware.org/?probe=c76e5dd087) | Aug 18, 2021 |
| ASUSTek       | M4N68T V2                   | [6441a522b9](https://linux-hardware.org/?probe=6441a522b9) | Aug 18, 2021 |
| Gigabyte      | H97M-HD3                    | [ab21753ce9](https://linux-hardware.org/?probe=ab21753ce9) | Aug 18, 2021 |
| ASUSTek       | E45M1-I DELUXE              | [d8aaf5c676](https://linux-hardware.org/?probe=d8aaf5c676) | Aug 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [b32d294f8b](https://linux-hardware.org/?probe=b32d294f8b) | Aug 17, 2021 |
| ASRock        | P67 Pro3                    | [fd006189bc](https://linux-hardware.org/?probe=fd006189bc) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [3c340a79fc](https://linux-hardware.org/?probe=3c340a79fc) | Aug 15, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [ccc387436e](https://linux-hardware.org/?probe=ccc387436e) | Aug 13, 2021 |
| Gigabyte      | H61M-S2PV                   | [3985c521c2](https://linux-hardware.org/?probe=3985c521c2) | Aug 12, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [345c99ec14](https://linux-hardware.org/?probe=345c99ec14) | Aug 12, 2021 |
| ASRock        | P67 Pro3                    | [e03db50d11](https://linux-hardware.org/?probe=e03db50d11) | Aug 12, 2021 |
| Unknown       | Ionics Carrier Board Adv... | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| ASRock        | P67 Pro3                    | [a9d6d51216](https://linux-hardware.org/?probe=a9d6d51216) | Aug 12, 2021 |
| Dell          | 0XJ8C4 A00                  | [e92b9a1203](https://linux-hardware.org/?probe=e92b9a1203) | Aug 11, 2021 |
| ASRockRack    | X470D4U2/1N1                | [b037023625](https://linux-hardware.org/?probe=b037023625) | Aug 11, 2021 |
| Gigabyte      | GA-990FXA-D3                | [c59dc746e2](https://linux-hardware.org/?probe=c59dc746e2) | Aug 11, 2021 |
| Gigabyte      | B450 AORUS M                | [2de3749bcf](https://linux-hardware.org/?probe=2de3749bcf) | Aug 11, 2021 |
| Dell          | 0GXM1W A02                  | [519bd92b01](https://linux-hardware.org/?probe=519bd92b01) | Aug 09, 2021 |
| Dell          | 0GXM1W A02                  | [181a5b6f63](https://linux-hardware.org/?probe=181a5b6f63) | Aug 09, 2021 |
| ASUSTek       | P5KC                        | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| Gigabyte      | H170-HD3-CF                 | [71aeb24115](https://linux-hardware.org/?probe=71aeb24115) | Aug 08, 2021 |
| ECS           | H81H3-M4                    | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| HP            | 1791                        | [9de8ddbd32](https://linux-hardware.org/?probe=9de8ddbd32) | Aug 07, 2021 |
| Google        | Zako                        | [f439c69ee5](https://linux-hardware.org/?probe=f439c69ee5) | Aug 03, 2021 |
| Intel         | DH87RL AAG74240-403         | [ec1970f896](https://linux-hardware.org/?probe=ec1970f896) | Aug 02, 2021 |
| ASUSTek       | PRIME B350M-K               | [b195a48138](https://linux-hardware.org/?probe=b195a48138) | Aug 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | [f4572f52ba](https://linux-hardware.org/?probe=f4572f52ba) | Aug 01, 2021 |
| ASUSTek       | P5GC-MX/1333                | [4f034fa5e5](https://linux-hardware.org/?probe=4f034fa5e5) | Aug 01, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [710ec38bd4](https://linux-hardware.org/?probe=710ec38bd4) | Aug 01, 2021 |
| Supermicro    | X10SRW-FB                   | [be3e1efd8c](https://linux-hardware.org/?probe=be3e1efd8c) | Jul 30, 2021 |
| Gigabyte      | H61M-S2PV                   | [766df6d543](https://linux-hardware.org/?probe=766df6d543) | Jul 30, 2021 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | [2a54dde7de](https://linux-hardware.org/?probe=2a54dde7de) | Jul 29, 2021 |
| Intel         | DH55HC AAE70933-504         | [f3a838da1b](https://linux-hardware.org/?probe=f3a838da1b) | Jul 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [64b86da0e0](https://linux-hardware.org/?probe=64b86da0e0) | Jul 28, 2021 |
| ASRock        | J4105-ITX                   | [ba7a9ed588](https://linux-hardware.org/?probe=ba7a9ed588) | Jul 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [7770cf36c7](https://linux-hardware.org/?probe=7770cf36c7) | Jul 27, 2021 |
| ASUSTek       | PRIME X570-P                | [076f12ebe9](https://linux-hardware.org/?probe=076f12ebe9) | Jul 26, 2021 |
| Supermicro    | X8STi                       | [ace2d84680](https://linux-hardware.org/?probe=ace2d84680) | Jul 26, 2021 |
| MSI           | X570-A PRO                  | [db168e8daa](https://linux-hardware.org/?probe=db168e8daa) | Jul 26, 2021 |
| Intel         | DN2800MT AAG23738-600       | [37b38d65e6](https://linux-hardware.org/?probe=37b38d65e6) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | [a54c9831cf](https://linux-hardware.org/?probe=a54c9831cf) | Jul 25, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [7a88cb266b](https://linux-hardware.org/?probe=7a88cb266b) | Jul 25, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [f16cf342a6](https://linux-hardware.org/?probe=f16cf342a6) | Jul 24, 2021 |
| Gigabyte      | Z170X-GamingG1              | [b0ce1bc8f5](https://linux-hardware.org/?probe=b0ce1bc8f5) | Jul 24, 2021 |
| ASUSTek       | P8B WS                      | [328f1648f0](https://linux-hardware.org/?probe=328f1648f0) | Jul 23, 2021 |
| ASUSTek       | H170 PRO GAMING             | [8e9fa75ba6](https://linux-hardware.org/?probe=8e9fa75ba6) | Jul 21, 2021 |
| YANYU         | ITX-M51_D2L baytrail        | [92dcf334a1](https://linux-hardware.org/?probe=92dcf334a1) | Jul 21, 2021 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [48145bef99](https://linux-hardware.org/?probe=48145bef99) | Jul 20, 2021 |
| ASRock        | A320M Pro4-F                | [c98085d169](https://linux-hardware.org/?probe=c98085d169) | Jul 20, 2021 |
| Lenovo        | 36C5 SDK0Q55724 WIN 3273... | [ccff510db8](https://linux-hardware.org/?probe=ccff510db8) | Jul 19, 2021 |
| MSI           | H97M-G43                    | [ba574c6794](https://linux-hardware.org/?probe=ba574c6794) | Jul 18, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [da4454b08b](https://linux-hardware.org/?probe=da4454b08b) | Jul 16, 2021 |
| HP            | 0A58h                       | [91869f8bdf](https://linux-hardware.org/?probe=91869f8bdf) | Jul 15, 2021 |
| ASRock        | A75M-HVS                    | [95cf5b47dc](https://linux-hardware.org/?probe=95cf5b47dc) | Jul 14, 2021 |
| Dell          | 0F6X5P A00                  | [ef2cac7e8c](https://linux-hardware.org/?probe=ef2cac7e8c) | Jul 14, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [6d381a9a63](https://linux-hardware.org/?probe=6d381a9a63) | Jul 13, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [6c2c692062](https://linux-hardware.org/?probe=6c2c692062) | Jul 11, 2021 |
| Intel         | DH77EB AAG39073-304         | [e1aabfff9e](https://linux-hardware.org/?probe=e1aabfff9e) | Jul 10, 2021 |
| HP            | 2B43                        | [990d8bae5e](https://linux-hardware.org/?probe=990d8bae5e) | Jul 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [195dc4b2d6](https://linux-hardware.org/?probe=195dc4b2d6) | Jul 08, 2021 |
| ASRock        | N68-VS3 FX                  | [3bde956fe7](https://linux-hardware.org/?probe=3bde956fe7) | Jul 08, 2021 |
| ASRock        | A300M-STX                   | [315b07d723](https://linux-hardware.org/?probe=315b07d723) | Jul 08, 2021 |
| ASRock        | G31M-S                      | [dea58c596a](https://linux-hardware.org/?probe=dea58c596a) | Jul 07, 2021 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [37feca7fac](https://linux-hardware.org/?probe=37feca7fac) | Jul 06, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [55996ad01c](https://linux-hardware.org/?probe=55996ad01c) | Jul 05, 2021 |
| Dell          | OptiPlex FX170              | [a593dfa486](https://linux-hardware.org/?probe=a593dfa486) | Jul 05, 2021 |
| HP            | 3396                        | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| ASUSTek       | PRIME B460M-A               | [2e105c41dc](https://linux-hardware.org/?probe=2e105c41dc) | Jul 04, 2021 |
| HP            | 8433 11                     | [a1d7ee077e](https://linux-hardware.org/?probe=a1d7ee077e) | Jul 03, 2021 |
| ASUSTek       | PRIME A320M-K               | [205efc4b09](https://linux-hardware.org/?probe=205efc4b09) | Jul 02, 2021 |
| ASRock        | J4005M                      | [2a5b9e78a8](https://linux-hardware.org/?probe=2a5b9e78a8) | Jul 02, 2021 |
| Acer          | Aspire TC-780               | [db439f45a3](https://linux-hardware.org/?probe=db439f45a3) | Jul 02, 2021 |
| ASRock        | X570M Pro4                  | [aa62962d75](https://linux-hardware.org/?probe=aa62962d75) | Jul 01, 2021 |
| Dell          | 0R230R A00                  | [101517b2a0](https://linux-hardware.org/?probe=101517b2a0) | Jun 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | [04c4ddf9b0](https://linux-hardware.org/?probe=04c4ddf9b0) | Jun 29, 2021 |
| Dell          | 0773VG A02                  | [5b6b35aeed](https://linux-hardware.org/?probe=5b6b35aeed) | Jun 29, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| Intel         | DG33FB AAD81072-306         | [55c7b15db3](https://linux-hardware.org/?probe=55c7b15db3) | Jun 28, 2021 |
| Intel         | DG33FB AAD81072-306         | [5259f5e799](https://linux-hardware.org/?probe=5259f5e799) | Jun 28, 2021 |
| ASRock        | A300M-STX                   | [709a8c3662](https://linux-hardware.org/?probe=709a8c3662) | Jun 25, 2021 |
| IBM           | 8215D1U                     | [5d966df1d5](https://linux-hardware.org/?probe=5d966df1d5) | Jun 24, 2021 |
| ASUSTek       | Maximus VIII GENE           | [dc85bb471a](https://linux-hardware.org/?probe=dc85bb471a) | Jun 24, 2021 |
| ASUSTek       | P8B75-M LX                  | [454e6a3f6d](https://linux-hardware.org/?probe=454e6a3f6d) | Jun 24, 2021 |
| Gigabyte      | GA-970A-D3                  | [61460e5cfc](https://linux-hardware.org/?probe=61460e5cfc) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [c916e64b0d](https://linux-hardware.org/?probe=c916e64b0d) | Jun 23, 2021 |
| ASUSTek       | H81M-A/BR                   | [7f66c1890d](https://linux-hardware.org/?probe=7f66c1890d) | Jun 21, 2021 |
| HP            | 8184 X4                     | [429b73d4c9](https://linux-hardware.org/?probe=429b73d4c9) | Jun 20, 2021 |
| HP            | 8184 X4                     | [a7280fe917](https://linux-hardware.org/?probe=a7280fe917) | Jun 20, 2021 |
| HP            | 8184 X4                     | [dd1fa9b71e](https://linux-hardware.org/?probe=dd1fa9b71e) | Jun 20, 2021 |
| ASRock        | B450M/ac                    | [d37b2a101a](https://linux-hardware.org/?probe=d37b2a101a) | Jun 19, 2021 |
| Dell          | 0Y5DDC A00                  | [78557b4cba](https://linux-hardware.org/?probe=78557b4cba) | Jun 19, 2021 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [5aba9bb92a](https://linux-hardware.org/?probe=5aba9bb92a) | Jun 17, 2021 |
| ASRock        | B450M Steel Legend          | [f2d49f0b64](https://linux-hardware.org/?probe=f2d49f0b64) | Jun 14, 2021 |
| Dell          | 0R230R A00                  | [11c08ffcb7](https://linux-hardware.org/?probe=11c08ffcb7) | Jun 14, 2021 |
| Dell          | 0R230R A00                  | [d21d1799e3](https://linux-hardware.org/?probe=d21d1799e3) | Jun 14, 2021 |
| ASUSTek       | F2A55-M LK                  | [40ba16d0f3](https://linux-hardware.org/?probe=40ba16d0f3) | Jun 13, 2021 |
| ASUSTek       | P8Z68-V                     | [9f21765a53](https://linux-hardware.org/?probe=9f21765a53) | Jun 13, 2021 |
| ASUSTek       | P8Z68-V                     | [130e8ce51b](https://linux-hardware.org/?probe=130e8ce51b) | Jun 13, 2021 |
| Dell          | 0WG864                      | [f87d1e613e](https://linux-hardware.org/?probe=f87d1e613e) | Jun 12, 2021 |
| ASUSTek       | P5E                         | [975bd773a1](https://linux-hardware.org/?probe=975bd773a1) | Jun 11, 2021 |
| ASUSTek       | E35M1-M PRO                 | [ce432dc65a](https://linux-hardware.org/?probe=ce432dc65a) | Jun 11, 2021 |
| Gigabyte      | B150M-D3H-CF                | [93f4681a87](https://linux-hardware.org/?probe=93f4681a87) | Jun 10, 2021 |
| Acer          | Aspire X3400                | [8fcc9b6607](https://linux-hardware.org/?probe=8fcc9b6607) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | [cca24bd3cc](https://linux-hardware.org/?probe=cca24bd3cc) | Jun 10, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cded9fb832](https://linux-hardware.org/?probe=cded9fb832) | Jun 09, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [204b2a5d7c](https://linux-hardware.org/?probe=204b2a5d7c) | Jun 05, 2021 |
| Dell          | 0WG864                      | [d72c25e601](https://linux-hardware.org/?probe=d72c25e601) | Jun 05, 2021 |
| ASRock        | B450 Gaming K4              | [514ff6f90a](https://linux-hardware.org/?probe=514ff6f90a) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | [74d4cdffc4](https://linux-hardware.org/?probe=74d4cdffc4) | Jun 05, 2021 |
| ASRockRack    | B450D4U-V1L                 | [49a0eec9f5](https://linux-hardware.org/?probe=49a0eec9f5) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | [d4b005244b](https://linux-hardware.org/?probe=d4b005244b) | Jun 05, 2021 |
| ASRock        | B450 Pro4                   | [eac7f9afec](https://linux-hardware.org/?probe=eac7f9afec) | Jun 05, 2021 |
| ASRock        | X570 Pro4                   | [bb16149062](https://linux-hardware.org/?probe=bb16149062) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | [c933ca0d6f](https://linux-hardware.org/?probe=c933ca0d6f) | Jun 05, 2021 |
| ASUSTek       | PRIME B365M-A               | [5f426dad05](https://linux-hardware.org/?probe=5f426dad05) | Jun 05, 2021 |
| ASRock        | B450 Pro4                   | [78b9b4f958](https://linux-hardware.org/?probe=78b9b4f958) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | [d3569d37e9](https://linux-hardware.org/?probe=d3569d37e9) | Jun 05, 2021 |
| ASUSTek       | H170M-PLUS                  | [0b5c7b1cb9](https://linux-hardware.org/?probe=0b5c7b1cb9) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [ead2c4250e](https://linux-hardware.org/?probe=ead2c4250e) | Jun 04, 2021 |
| HP            | 0A04h                       | [8368917bd7](https://linux-hardware.org/?probe=8368917bd7) | Jun 03, 2021 |
| ASRock        | B450 Steel Legend           | [f1ddb51b58](https://linux-hardware.org/?probe=f1ddb51b58) | Jun 02, 2021 |
| MSI           | H81M-P33                    | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [ca61b140f1](https://linux-hardware.org/?probe=ca61b140f1) | Jun 01, 2021 |
| HP            | 8595                        | [36248f1bf0](https://linux-hardware.org/?probe=36248f1bf0) | May 31, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [a0d316eb3e](https://linux-hardware.org/?probe=a0d316eb3e) | May 31, 2021 |
| Dell          | 0WG864                      | [3e22711262](https://linux-hardware.org/?probe=3e22711262) | May 31, 2021 |
| HP            | 3048h                       | [39204d22ae](https://linux-hardware.org/?probe=39204d22ae) | May 29, 2021 |
| ASUSTek       | H110M-PLUS                  | [3310677e00](https://linux-hardware.org/?probe=3310677e00) | May 29, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [f04a4bb553](https://linux-hardware.org/?probe=f04a4bb553) | May 28, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f0145b568f](https://linux-hardware.org/?probe=f0145b568f) | May 27, 2021 |
| Dell          | OptiPlex 980                | [1fe360b027](https://linux-hardware.org/?probe=1fe360b027) | May 26, 2021 |
| ASRock        | H77M                        | [3a362598fb](https://linux-hardware.org/?probe=3a362598fb) | May 23, 2021 |
| AZW           | AP35                        | [7c30c0c3ca](https://linux-hardware.org/?probe=7c30c0c3ca) | May 22, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [ec7ceee60c](https://linux-hardware.org/?probe=ec7ceee60c) | May 22, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [8861e8ae8e](https://linux-hardware.org/?probe=8861e8ae8e) | May 22, 2021 |
| ASUSTek       | J1900I-C                    | [560fd63326](https://linux-hardware.org/?probe=560fd63326) | May 21, 2021 |
| ASRock        | B365M Pro4-F                | [9b31a1e94f](https://linux-hardware.org/?probe=9b31a1e94f) | May 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [609c071902](https://linux-hardware.org/?probe=609c071902) | May 21, 2021 |
| MSI           | Z77A-G43                    | [ea32add5cd](https://linux-hardware.org/?probe=ea32add5cd) | May 20, 2021 |
| ASRock        | B450 Steel Legend           | [7ca61ab765](https://linux-hardware.org/?probe=7ca61ab765) | May 20, 2021 |
| ASUSTek       | Z87-C                       | [90f950c23b](https://linux-hardware.org/?probe=90f950c23b) | May 19, 2021 |
| Centrium      | C2018-H310CH5-M2            | [835165a55f](https://linux-hardware.org/?probe=835165a55f) | May 18, 2021 |
| Google        | Guado                       | [d60df18545](https://linux-hardware.org/?probe=d60df18545) | May 17, 2021 |
| ASUSTek       | P5B                         | [ff621cb51a](https://linux-hardware.org/?probe=ff621cb51a) | May 17, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [9eb78f0eaa](https://linux-hardware.org/?probe=9eb78f0eaa) | May 17, 2021 |
| Intel         | DH87RL AAG74240-402         | [cdb24d5d69](https://linux-hardware.org/?probe=cdb24d5d69) | May 16, 2021 |
| ASUSTek       | PRIME X370-PRO              | [d180569750](https://linux-hardware.org/?probe=d180569750) | May 15, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [e2b7358aa7](https://linux-hardware.org/?probe=e2b7358aa7) | May 14, 2021 |
| Dell          | 0T10XW A00                  | [10eeac5c65](https://linux-hardware.org/?probe=10eeac5c65) | May 14, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [3bc05945d2](https://linux-hardware.org/?probe=3bc05945d2) | May 13, 2021 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e311ba55e3](https://linux-hardware.org/?probe=e311ba55e3) | May 13, 2021 |
| Huanan        | X99-F8 V2.0                 | [c2569c6c71](https://linux-hardware.org/?probe=c2569c6c71) | May 11, 2021 |
| HP            | 2B43                        | [354c1b840d](https://linux-hardware.org/?probe=354c1b840d) | May 10, 2021 |
| faytech       | FTJ1900-192                 | [4e210308e7](https://linux-hardware.org/?probe=4e210308e7) | May 09, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [b2a98215c7](https://linux-hardware.org/?probe=b2a98215c7) | May 08, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [0e50c08ab6](https://linux-hardware.org/?probe=0e50c08ab6) | May 08, 2021 |
| Gigabyte      | MZAPLBP-00                  | [7741641346](https://linux-hardware.org/?probe=7741641346) | May 07, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [25108d77d7](https://linux-hardware.org/?probe=25108d77d7) | May 06, 2021 |
| Intel         | DG965SS AAD41678-308        | [d76e4b9ec3](https://linux-hardware.org/?probe=d76e4b9ec3) | May 04, 2021 |
| Gigabyte      | X99-UD5 WIFI-CF             | [22d4b9fb7b](https://linux-hardware.org/?probe=22d4b9fb7b) | May 03, 2021 |
| Dell          | 0T10XW A00                  | [1f44313223](https://linux-hardware.org/?probe=1f44313223) | May 03, 2021 |
| ASUSTek       | M3A79-T DELUXE              | [3a7bb902f4](https://linux-hardware.org/?probe=3a7bb902f4) | May 02, 2021 |
| Intel         | DH67BL AAG10189-209         | [61ae6af54a](https://linux-hardware.org/?probe=61ae6af54a) | May 01, 2021 |
| Dell          | 0GXM1W A02                  | [0a78d6a11b](https://linux-hardware.org/?probe=0a78d6a11b) | Apr 28, 2021 |
| Dell          | 042P49 A02                  | [1b4c5aa3eb](https://linux-hardware.org/?probe=1b4c5aa3eb) | Apr 28, 2021 |
| ASUSTek       | Z170M-PLUS                  | [70cd900750](https://linux-hardware.org/?probe=70cd900750) | Apr 27, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [16aa72ef55](https://linux-hardware.org/?probe=16aa72ef55) | Apr 26, 2021 |
| ASUSTek       | Maximus VI FORMULA          | [353b136c95](https://linux-hardware.org/?probe=353b136c95) | Apr 26, 2021 |
| Dell          | 06FW8P A01                  | [08f4c825cc](https://linux-hardware.org/?probe=08f4c825cc) | Apr 25, 2021 |
| ASUSTek       | Rampage Formula             | [59d0d32d9c](https://linux-hardware.org/?probe=59d0d32d9c) | Apr 24, 2021 |
| ASUSTek       | Rampage Formula             | [3d78d59693](https://linux-hardware.org/?probe=3d78d59693) | Apr 24, 2021 |
| Dell          | 0VHRW1 A03                  | [bc7c3f8c4d](https://linux-hardware.org/?probe=bc7c3f8c4d) | Apr 23, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | [8d7a62ce1a](https://linux-hardware.org/?probe=8d7a62ce1a) | Apr 20, 2021 |
| Dell          | 06FW8P A02                  | [583acd1f2e](https://linux-hardware.org/?probe=583acd1f2e) | Apr 20, 2021 |
| Dell          | 06FW8P A01                  | [a0b4b692ff](https://linux-hardware.org/?probe=a0b4b692ff) | Apr 20, 2021 |
| Shuttle       | FS81                        | [14e78cfe43](https://linux-hardware.org/?probe=14e78cfe43) | Apr 20, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [77f6423cc2](https://linux-hardware.org/?probe=77f6423cc2) | Apr 20, 2021 |
| Acer          | Aspire M5910                | [6db90c645b](https://linux-hardware.org/?probe=6db90c645b) | Apr 19, 2021 |
| Inventec      | R CLASS A02                 | [d678a44af1](https://linux-hardware.org/?probe=d678a44af1) | Apr 18, 2021 |
| ASUSTek       | J1900I-C                    | [e980e0a528](https://linux-hardware.org/?probe=e980e0a528) | Apr 17, 2021 |
| ASUSTek       | M2N68-VM                    | [611ca83c61](https://linux-hardware.org/?probe=611ca83c61) | Apr 17, 2021 |
| ASUSTek       | M2N68-VM                    | [cc3fcf1a7e](https://linux-hardware.org/?probe=cc3fcf1a7e) | Apr 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [66cce64a3e](https://linux-hardware.org/?probe=66cce64a3e) | Apr 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [f8e204686b](https://linux-hardware.org/?probe=f8e204686b) | Apr 17, 2021 |
| ASUSTek       | P9X79 PRO                   | [28a07ac7f9](https://linux-hardware.org/?probe=28a07ac7f9) | Apr 16, 2021 |
| Dell          | 02N3WF A02                  | [f7e56af20d](https://linux-hardware.org/?probe=f7e56af20d) | Apr 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [06ee276b08](https://linux-hardware.org/?probe=06ee276b08) | Apr 15, 2021 |
| HP            | 3048h                       | [65c7aa979f](https://linux-hardware.org/?probe=65c7aa979f) | Apr 15, 2021 |
| ASRock        | FM2A88M-HD+ R2.0            | [fdac2fa1fd](https://linux-hardware.org/?probe=fdac2fa1fd) | Apr 14, 2021 |
| ASUSTek       | E45M1-I DELUXE              | [bb6849297b](https://linux-hardware.org/?probe=bb6849297b) | Apr 11, 2021 |
| ASRock        | X470 Taichi Ultimate        | [7ab07ae1e9](https://linux-hardware.org/?probe=7ab07ae1e9) | Apr 11, 2021 |
| ASRock        | X470 Taichi Ultimate        | [174dc97643](https://linux-hardware.org/?probe=174dc97643) | Apr 11, 2021 |
| ASUSTek       | E45M1-I DELUXE              | [7352afc8e6](https://linux-hardware.org/?probe=7352afc8e6) | Apr 10, 2021 |
| ECS           | X79R-AX                     | [53874d702a](https://linux-hardware.org/?probe=53874d702a) | Apr 10, 2021 |
| Dell          | 0M858N A00                  | [10d5dd9621](https://linux-hardware.org/?probe=10d5dd9621) | Apr 08, 2021 |
| MSI           | AMETHYST-M                  | [e47db7138d](https://linux-hardware.org/?probe=e47db7138d) | Apr 07, 2021 |
| MSI           | AMETHYST-M                  | [d54c5d4ba2](https://linux-hardware.org/?probe=d54c5d4ba2) | Apr 07, 2021 |
| HP            | 2187 A01                    | [d20795e620](https://linux-hardware.org/?probe=d20795e620) | Apr 07, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [649a2a1da2](https://linux-hardware.org/?probe=649a2a1da2) | Apr 06, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | [0784afdde4](https://linux-hardware.org/?probe=0784afdde4) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | [3c49f2205f](https://linux-hardware.org/?probe=3c49f2205f) | Apr 05, 2021 |
| MSI           | B350 PC MATE                | [ca96bbf9e2](https://linux-hardware.org/?probe=ca96bbf9e2) | Apr 05, 2021 |
| Gigabyte      | MZBAYAP-00                  | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [9b055bd98d](https://linux-hardware.org/?probe=9b055bd98d) | Apr 03, 2021 |
| Positivo      | M14                         | [a18117be54](https://linux-hardware.org/?probe=a18117be54) | Apr 02, 2021 |
| Dell          | 0WMJ54 A01                  | [92093b07f4](https://linux-hardware.org/?probe=92093b07f4) | Apr 02, 2021 |
| Dell          | 0WMJ54 A01                  | [b5d0cd8ccf](https://linux-hardware.org/?probe=b5d0cd8ccf) | Apr 02, 2021 |
| MSI           | MEG X299 CREATION           | [55cdaf18a6](https://linux-hardware.org/?probe=55cdaf18a6) | Apr 02, 2021 |
| ASRock        | A300M-STX                   | [87655d962f](https://linux-hardware.org/?probe=87655d962f) | Apr 01, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [394a2510d4](https://linux-hardware.org/?probe=394a2510d4) | Mar 31, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [0115e62e06](https://linux-hardware.org/?probe=0115e62e06) | Mar 31, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3515fc5b18](https://linux-hardware.org/?probe=3515fc5b18) | Mar 30, 2021 |
| ASUSTek       | Z170-K                      | [48b797e6b3](https://linux-hardware.org/?probe=48b797e6b3) | Mar 29, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [56de90095b](https://linux-hardware.org/?probe=56de90095b) | Mar 29, 2021 |
| Gigabyte      | M61PME-S2                   | [cd5fb42957](https://linux-hardware.org/?probe=cd5fb42957) | Mar 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [03d1a82735](https://linux-hardware.org/?probe=03d1a82735) | Mar 29, 2021 |
| HP            | 18E5                        | [15dc965007](https://linux-hardware.org/?probe=15dc965007) | Mar 28, 2021 |
| Intel         | X99                         | [0d7ee3a993](https://linux-hardware.org/?probe=0d7ee3a993) | Mar 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [743336069f](https://linux-hardware.org/?probe=743336069f) | Mar 27, 2021 |
| HP            | 8433 11                     | [3a2d54f9ca](https://linux-hardware.org/?probe=3a2d54f9ca) | Mar 26, 2021 |
| ASRock        | A320M-HDV R3.0              | [a2ad3de5d8](https://linux-hardware.org/?probe=a2ad3de5d8) | Mar 25, 2021 |
| ASRock        | B450M Pro4-F                | [c7223020fe](https://linux-hardware.org/?probe=c7223020fe) | Mar 25, 2021 |
| Gigabyte      | M61PME-S2P                  | [246f71ebbb](https://linux-hardware.org/?probe=246f71ebbb) | Mar 25, 2021 |
| Gigabyte      | M61PME-S2P                  | [e03dc458e6](https://linux-hardware.org/?probe=e03dc458e6) | Mar 25, 2021 |
| Intel         | DH87RL AAG74240-403         | [24a18712e2](https://linux-hardware.org/?probe=24a18712e2) | Mar 25, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [cc06351c8c](https://linux-hardware.org/?probe=cc06351c8c) | Mar 24, 2021 |
| Dell          | 0T1D10 A01                  | [75042368b6](https://linux-hardware.org/?probe=75042368b6) | Mar 24, 2021 |
| ASUSTek       | PRIME H310M-K               | [1faa19e424](https://linux-hardware.org/?probe=1faa19e424) | Mar 24, 2021 |
| ASRock        | H61M-GE                     | [acf1f07ce8](https://linux-hardware.org/?probe=acf1f07ce8) | Mar 24, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [e19e7b3214](https://linux-hardware.org/?probe=e19e7b3214) | Mar 24, 2021 |
| Intel         | DQ45CB AAE30148-205         | [6edbd252d4](https://linux-hardware.org/?probe=6edbd252d4) | Mar 22, 2021 |
| ASUSTek       | Z8NA-D6                     | [7167d3456a](https://linux-hardware.org/?probe=7167d3456a) | Mar 22, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [5849ed10b6](https://linux-hardware.org/?probe=5849ed10b6) | Mar 21, 2021 |
| MSI           | 9871                        | [bc22572b66](https://linux-hardware.org/?probe=bc22572b66) | Mar 20, 2021 |
| ASUSTek       | P8H61-M LX2                 | [1fbb1ece7a](https://linux-hardware.org/?probe=1fbb1ece7a) | Mar 20, 2021 |
| Gigabyte      | H81-D3                      | [a06cd7a709](https://linux-hardware.org/?probe=a06cd7a709) | Mar 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [4a8122af58](https://linux-hardware.org/?probe=4a8122af58) | Mar 17, 2021 |
| ASUSTek       | PRIME A320M-K               | [8ce684e857](https://linux-hardware.org/?probe=8ce684e857) | Mar 17, 2021 |
| Gigabyte      | Z270-Gaming K3              | [1b6cfd046e](https://linux-hardware.org/?probe=1b6cfd046e) | Mar 17, 2021 |
| HP            | 21B4 A01                    | [bab965c49d](https://linux-hardware.org/?probe=bab965c49d) | Mar 17, 2021 |
| ASUSTek       | PRIME B365M-A               | [ce2583be9e](https://linux-hardware.org/?probe=ce2583be9e) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7d73263e02](https://linux-hardware.org/?probe=7d73263e02) | Mar 16, 2021 |
| ASRock        | H77M                        | [13d87f3380](https://linux-hardware.org/?probe=13d87f3380) | Mar 16, 2021 |
| Unknown       | Intel X79                   | [a340f9988c](https://linux-hardware.org/?probe=a340f9988c) | Mar 15, 2021 |
| ASRock        | H77M                        | [f7f669b943](https://linux-hardware.org/?probe=f7f669b943) | Mar 14, 2021 |
| ASRock        | B365M Pro4-F                | [0c6489fca5](https://linux-hardware.org/?probe=0c6489fca5) | Mar 14, 2021 |
| HP            | 304Bh                       | [8ffb1720d8](https://linux-hardware.org/?probe=8ffb1720d8) | Mar 13, 2021 |
| Gigabyte      | Z87X-UD5H-CF                | [548afbb702](https://linux-hardware.org/?probe=548afbb702) | Mar 13, 2021 |
| Intel         | DH61CR AAG14064-209         | [549b5dc946](https://linux-hardware.org/?probe=549b5dc946) | Mar 11, 2021 |
| Acer          | RS740DVF                    | [f02d784520](https://linux-hardware.org/?probe=f02d784520) | Mar 11, 2021 |
| Acer          | RS740DVF                    | [9acc5ca1d0](https://linux-hardware.org/?probe=9acc5ca1d0) | Mar 11, 2021 |
| ASRock        | X299M Extreme4              | [6565147b81](https://linux-hardware.org/?probe=6565147b81) | Mar 11, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [f0d57310c5](https://linux-hardware.org/?probe=f0d57310c5) | Mar 10, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [33471c1927](https://linux-hardware.org/?probe=33471c1927) | Mar 10, 2021 |
| Intel         | DE3815TYKH H26998-403       | [d4408f7b0e](https://linux-hardware.org/?probe=d4408f7b0e) | Mar 10, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [26b1d3237f](https://linux-hardware.org/?probe=26b1d3237f) | Mar 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ae4c33fe91](https://linux-hardware.org/?probe=ae4c33fe91) | Mar 09, 2021 |
| MSI           | MEG X299 CREATION           | [167dcf290d](https://linux-hardware.org/?probe=167dcf290d) | Mar 09, 2021 |
| MSI           | MEG X299 CREATION           | [974f3ebb6c](https://linux-hardware.org/?probe=974f3ebb6c) | Mar 09, 2021 |
| ASUSTek       | P7F-M                       | [0f02f5a57c](https://linux-hardware.org/?probe=0f02f5a57c) | Mar 06, 2021 |
| Gigabyte      | GA-990XA-UD3                | [47d45dfe93](https://linux-hardware.org/?probe=47d45dfe93) | Mar 06, 2021 |
| Gigabyte      | GA-990XA-UD3                | [e0814ef8ec](https://linux-hardware.org/?probe=e0814ef8ec) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | [7e8aa7dc5a](https://linux-hardware.org/?probe=7e8aa7dc5a) | Mar 06, 2021 |
| HP            | 8433 11                     | [d4c2e201e1](https://linux-hardware.org/?probe=d4c2e201e1) | Mar 05, 2021 |
| Hardkernel    | ODROID-H2                   | [4047711d09](https://linux-hardware.org/?probe=4047711d09) | Mar 05, 2021 |
| Gigabyte      | H61M-S1                     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| SolidRun      | CEX7 Platform               | [66e1d65053](https://linux-hardware.org/?probe=66e1d65053) | Mar 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | [7ab4c4e090](https://linux-hardware.org/?probe=7ab4c4e090) | Mar 03, 2021 |
| Dell          | 0Y2K8N A00                  | [eca9b9b213](https://linux-hardware.org/?probe=eca9b9b213) | Mar 02, 2021 |
| ASRock        | G41M-VS3                    | [587becd063](https://linux-hardware.org/?probe=587becd063) | Mar 02, 2021 |
| ASUSTek       | PRIME B450M-A II            | [71c4ab6da6](https://linux-hardware.org/?probe=71c4ab6da6) | Mar 01, 2021 |
| ASUSTek       | X99-A                       | [d8025d1213](https://linux-hardware.org/?probe=d8025d1213) | Mar 01, 2021 |
| Intel         | DH61CR AAG14064-207         | [307eff40e3](https://linux-hardware.org/?probe=307eff40e3) | Mar 01, 2021 |
| Intel         | DH61CR AAG14064-207         | [c669652423](https://linux-hardware.org/?probe=c669652423) | Feb 28, 2021 |
| MSI           | Z97 GAMING 9 ACK            | [11e9217472](https://linux-hardware.org/?probe=11e9217472) | Feb 28, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [36543664dc](https://linux-hardware.org/?probe=36543664dc) | Feb 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [6becd1cb83](https://linux-hardware.org/?probe=6becd1cb83) | Feb 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [50350be1af](https://linux-hardware.org/?probe=50350be1af) | Feb 25, 2021 |
| Intel         | DN2800MT AAG23738-801       | [ed8bf69f6b](https://linux-hardware.org/?probe=ed8bf69f6b) | Feb 25, 2021 |
| Dell          | 0F8096                      | [307334b9d5](https://linux-hardware.org/?probe=307334b9d5) | Feb 24, 2021 |
| ASRock        | X300M-STX                   | [89f61ec69c](https://linux-hardware.org/?probe=89f61ec69c) | Feb 23, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [3047e086a8](https://linux-hardware.org/?probe=3047e086a8) | Feb 21, 2021 |
| ASRock        | N68-S3 FX                   | [ef6f9922c0](https://linux-hardware.org/?probe=ef6f9922c0) | Feb 20, 2021 |
| Intel X79     | Unknown                     | [4fe62c374e](https://linux-hardware.org/?probe=4fe62c374e) | Feb 18, 2021 |
| HP            | 21B4 A01                    | [0dab6984ed](https://linux-hardware.org/?probe=0dab6984ed) | Feb 16, 2021 |
| ASRock        | AB350M Pro4                 | [427b038f6c](https://linux-hardware.org/?probe=427b038f6c) | Feb 16, 2021 |
| HP            | 21D0                        | [2505114bad](https://linux-hardware.org/?probe=2505114bad) | Feb 15, 2021 |
| Intel X79     | Unknown                     | [b74cbda521](https://linux-hardware.org/?probe=b74cbda521) | Feb 14, 2021 |
| Lenovo        | MAHOBAY                     | [a40dfa6272](https://linux-hardware.org/?probe=a40dfa6272) | Feb 13, 2021 |
| ASRock        | Z87 Extreme4                | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [183a4413fa](https://linux-hardware.org/?probe=183a4413fa) | Feb 12, 2021 |
| HP            | 2B47                        | [fed2a32cca](https://linux-hardware.org/?probe=fed2a32cca) | Feb 12, 2021 |
| ASUSTek       | SABERTOOTH X79              | [fc969f36d0](https://linux-hardware.org/?probe=fc969f36d0) | Feb 11, 2021 |
| Intel X79     | Unknown                     | [e0a4e5c1c4](https://linux-hardware.org/?probe=e0a4e5c1c4) | Feb 11, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [a2bd5bab18](https://linux-hardware.org/?probe=a2bd5bab18) | Feb 10, 2021 |
| Gigabyte      | B75M-D3H                    | [8ff77d6638](https://linux-hardware.org/?probe=8ff77d6638) | Feb 08, 2021 |
| Dell          | 0NNGP2 A00                  | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Dell          | 0J37VM A01                  | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| Alienware     | 0FPV4P A00                  | [bc3b5377f0](https://linux-hardware.org/?probe=bc3b5377f0) | Feb 06, 2021 |
| HP            | 18E5                        | [f78d266260](https://linux-hardware.org/?probe=f78d266260) | Feb 06, 2021 |
| HP            | 18E5                        | [1e1e2ef32b](https://linux-hardware.org/?probe=1e1e2ef32b) | Feb 05, 2021 |
| ASUSTek       | Z97-A                       | [fc8c462cc7](https://linux-hardware.org/?probe=fc8c462cc7) | Feb 04, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | [ebdf056184](https://linux-hardware.org/?probe=ebdf056184) | Feb 04, 2021 |
| Gigabyte      | H97M-HD3                    | [d7587e51af](https://linux-hardware.org/?probe=d7587e51af) | Feb 03, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [38ac60e3d1](https://linux-hardware.org/?probe=38ac60e3d1) | Feb 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [793bc77e48](https://linux-hardware.org/?probe=793bc77e48) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [9b37eaa9f8](https://linux-hardware.org/?probe=9b37eaa9f8) | Feb 02, 2021 |
| ASRock        | AB350M Pro4                 | [f82376b2fc](https://linux-hardware.org/?probe=f82376b2fc) | Feb 01, 2021 |
| ASUSTek       | Z87I-DELUXE                 | [24515ee809](https://linux-hardware.org/?probe=24515ee809) | Jan 31, 2021 |
| Dell          | 0GXM1W A02                  | [fdca13ca28](https://linux-hardware.org/?probe=fdca13ca28) | Jan 30, 2021 |
| ASRock        | B85M Pro4                   | [d7b5c7e13c](https://linux-hardware.org/?probe=d7b5c7e13c) | Jan 30, 2021 |
| ASUSTek       | P5KPL-SE                    | [58ac4fe903](https://linux-hardware.org/?probe=58ac4fe903) | Jan 30, 2021 |
| ASUSTek       | P5KPL-SE                    | [cecce826bf](https://linux-hardware.org/?probe=cecce826bf) | Jan 29, 2021 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [dcf453c2da](https://linux-hardware.org/?probe=dcf453c2da) | Jan 29, 2021 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [ecdd27b523](https://linux-hardware.org/?probe=ecdd27b523) | Jan 29, 2021 |
| Medion        | H81M-E34                    | [fd62670499](https://linux-hardware.org/?probe=fd62670499) | Jan 28, 2021 |
| Medion        | H81M-E34                    | [8dd34b06cd](https://linux-hardware.org/?probe=8dd34b06cd) | Jan 28, 2021 |
| ASRock        | B85M DASH/OL R2.0           | [c1c5847225](https://linux-hardware.org/?probe=c1c5847225) | Jan 28, 2021 |
| ASRock        | B85M Pro4                   | [049bd1a01d](https://linux-hardware.org/?probe=049bd1a01d) | Jan 27, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [7d18048067](https://linux-hardware.org/?probe=7d18048067) | Jan 26, 2021 |
| Dell          | 0YH299                      | [6f463264fc](https://linux-hardware.org/?probe=6f463264fc) | Jan 25, 2021 |
| ASUSTek       | B85M-G                      | [e89c5a178e](https://linux-hardware.org/?probe=e89c5a178e) | Jan 25, 2021 |
| ASUSTek       | P7H55D-M EVO                | [cfc6294323](https://linux-hardware.org/?probe=cfc6294323) | Jan 25, 2021 |
| Dell          | 0YH299                      | [2894a5398e](https://linux-hardware.org/?probe=2894a5398e) | Jan 23, 2021 |
| Apple         | Mac-F221BEC8                | [63f1b08bde](https://linux-hardware.org/?probe=63f1b08bde) | Jan 22, 2021 |
| ASUSTek       | Z87-C                       | [2320c57e92](https://linux-hardware.org/?probe=2320c57e92) | Jan 19, 2021 |
| Dell          | 0F8096                      | [27186bb8eb](https://linux-hardware.org/?probe=27186bb8eb) | Jan 18, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ecb504df58](https://linux-hardware.org/?probe=ecb504df58) | Jan 18, 2021 |
| ASUSTek       | H61M-K                      | [c31f39f48f](https://linux-hardware.org/?probe=c31f39f48f) | Jan 18, 2021 |
| ASRock        | A320M-HDV R3.0              | [ff70c56774](https://linux-hardware.org/?probe=ff70c56774) | Jan 16, 2021 |
| Hardkernel    | ODROID-H2                   | [612d77c58d](https://linux-hardware.org/?probe=612d77c58d) | Jan 16, 2021 |
| Intel         | DH87RL AAG74240-402         | [926473c2ac](https://linux-hardware.org/?probe=926473c2ac) | Jan 16, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [51b1b87213](https://linux-hardware.org/?probe=51b1b87213) | Jan 16, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [2b8813f5c4](https://linux-hardware.org/?probe=2b8813f5c4) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| Intel         | DH87RL AAG74240-402         | [dcbc8e3b20](https://linux-hardware.org/?probe=dcbc8e3b20) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [4877506709](https://linux-hardware.org/?probe=4877506709) | Jan 14, 2021 |
| PCWare        | IPMH61R2                    | [7a316c9f35](https://linux-hardware.org/?probe=7a316c9f35) | Jan 13, 2021 |
| ASUSTek       | M2A-VM                      | [054b5e3fd6](https://linux-hardware.org/?probe=054b5e3fd6) | Jan 13, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [08a002baf3](https://linux-hardware.org/?probe=08a002baf3) | Jan 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [5ba2ff2f45](https://linux-hardware.org/?probe=5ba2ff2f45) | Jan 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6d0b6eb155](https://linux-hardware.org/?probe=6d0b6eb155) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Intel         | DH87RL AAG74240-402         | [5e67f36f68](https://linux-hardware.org/?probe=5e67f36f68) | Jan 12, 2021 |
| Positivo      | POS-VVCN896BD               | [4c32986e5f](https://linux-hardware.org/?probe=4c32986e5f) | Jan 11, 2021 |
| Qbex          | H61H2-M2                    | [682a1da8fb](https://linux-hardware.org/?probe=682a1da8fb) | Jan 07, 2021 |
| NEXCOM        | NDIS B322                   | [c2789ca746](https://linux-hardware.org/?probe=c2789ca746) | Jan 06, 2021 |
| ASRock        | H110M-HDV R3.0              | [2d4610a61e](https://linux-hardware.org/?probe=2d4610a61e) | Jan 04, 2021 |
| HP            | 3048h                       | [4476c19b01](https://linux-hardware.org/?probe=4476c19b01) | Jan 03, 2021 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [5a214e240a](https://linux-hardware.org/?probe=5a214e240a) | Jan 03, 2021 |
| Lenovo        | SDK0E50510 WIN 262508091... | [29bb6e8f2d](https://linux-hardware.org/?probe=29bb6e8f2d) | Jan 03, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a3f1faa5db](https://linux-hardware.org/?probe=a3f1faa5db) | Jan 03, 2021 |
| HP            | ProLiant MicroServer Gen... | [a480941f8c](https://linux-hardware.org/?probe=a480941f8c) | Jan 02, 2021 |
| Gigabyte      | F2A78M-HD2                  | [d0530d0741](https://linux-hardware.org/?probe=d0530d0741) | Jan 02, 2021 |
| ASUSTek       | Z87I-DELUXE                 | [d043663b06](https://linux-hardware.org/?probe=d043663b06) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [32aae7f223](https://linux-hardware.org/?probe=32aae7f223) | Dec 31, 2020 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [2331e1bc7b](https://linux-hardware.org/?probe=2331e1bc7b) | Dec 31, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [837dc50ac4](https://linux-hardware.org/?probe=837dc50ac4) | Dec 31, 2020 |
| Dell          | 0K83V0 A00                  | [c4a35bef61](https://linux-hardware.org/?probe=c4a35bef61) | Dec 30, 2020 |
| HP            | 3641h                       | [f53841ba18](https://linux-hardware.org/?probe=f53841ba18) | Dec 30, 2020 |
| Dell          | 0CT017                      | [6affc8f13f](https://linux-hardware.org/?probe=6affc8f13f) | Dec 29, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [188b144bf8](https://linux-hardware.org/?probe=188b144bf8) | Dec 29, 2020 |
| Dell          | 042P49 A00                  | [5ae2867813](https://linux-hardware.org/?probe=5ae2867813) | Dec 28, 2020 |
| ASUSTek       | PRIME Z370-A                | [c0fe678cd0](https://linux-hardware.org/?probe=c0fe678cd0) | Dec 28, 2020 |
| Gigabyte      | X79-UP4                     | [f591c67467](https://linux-hardware.org/?probe=f591c67467) | Dec 28, 2020 |
| ASRock        | ConRoe945G-DVI              | [c80d106ccc](https://linux-hardware.org/?probe=c80d106ccc) | Dec 28, 2020 |
| ASRock        | A780GMH/128M                | [bf97146186](https://linux-hardware.org/?probe=bf97146186) | Dec 28, 2020 |
| Unknown       | G41 Series                  | [5269381983](https://linux-hardware.org/?probe=5269381983) | Dec 25, 2020 |
| Unknown       | G41 Series                  | [b0a897d878](https://linux-hardware.org/?probe=b0a897d878) | Dec 25, 2020 |
| HP            | 2187 A01                    | [0e816c8ee5](https://linux-hardware.org/?probe=0e816c8ee5) | Dec 25, 2020 |
| MSI           | 970 GAMING                  | [c1da0ab577](https://linux-hardware.org/?probe=c1da0ab577) | Dec 24, 2020 |
| ASUSTek       | X99-DELUXE                  | [4c3b88972f](https://linux-hardware.org/?probe=4c3b88972f) | Dec 24, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e9db8f5ca6](https://linux-hardware.org/?probe=e9db8f5ca6) | Dec 23, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [b7660e1e29](https://linux-hardware.org/?probe=b7660e1e29) | Dec 22, 2020 |
| ASUSTek       | P8Z68-V PRO                 | [3e6e5c0ff2](https://linux-hardware.org/?probe=3e6e5c0ff2) | Dec 21, 2020 |
| Lenovo        | CRESCENTBAY SDK0J40700 W... | [a4d7b52436](https://linux-hardware.org/?probe=a4d7b52436) | Dec 21, 2020 |
| ASUSTek       | P8Z68-V LE                  | [5a221d9743](https://linux-hardware.org/?probe=5a221d9743) | Dec 20, 2020 |
| Gigabyte      | G41MT-S2PT                  | [6c4fcafbcc](https://linux-hardware.org/?probe=6c4fcafbcc) | Dec 20, 2020 |
| HP            | 18E7                        | [a84ff44872](https://linux-hardware.org/?probe=a84ff44872) | Dec 20, 2020 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [25895fd0a9](https://linux-hardware.org/?probe=25895fd0a9) | Dec 19, 2020 |
| ASUSTek       | H81M-PLUS                   | [ccb3c7aa09](https://linux-hardware.org/?probe=ccb3c7aa09) | Dec 19, 2020 |
| ASRock        | A320M-HDV R3.0              | [38f82ecb34](https://linux-hardware.org/?probe=38f82ecb34) | Dec 19, 2020 |
| ASUSTek       | P5LD2EB-DHS                 | [d8cb323624](https://linux-hardware.org/?probe=d8cb323624) | Dec 19, 2020 |
| ASRock        | A320M-HDV R3.0              | [a09c3ee698](https://linux-hardware.org/?probe=a09c3ee698) | Dec 18, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [6cff41d0d5](https://linux-hardware.org/?probe=6cff41d0d5) | Dec 18, 2020 |
| Gigabyte      | H55-USB3                    | [1a4be8e99e](https://linux-hardware.org/?probe=1a4be8e99e) | Dec 18, 2020 |
| Pegatron      | 2AC2A                       | [ff38d73778](https://linux-hardware.org/?probe=ff38d73778) | Dec 17, 2020 |
| Intel         | DH61WW AAG23116-204         | [6c869ccb2b](https://linux-hardware.org/?probe=6c869ccb2b) | Dec 17, 2020 |
| ASUSTek       | M2N32-SLI DELUXE            | [b1c0b6230d](https://linux-hardware.org/?probe=b1c0b6230d) | Dec 17, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [75f375567c](https://linux-hardware.org/?probe=75f375567c) | Dec 16, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [2d6a917448](https://linux-hardware.org/?probe=2d6a917448) | Dec 16, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [b77c353ce5](https://linux-hardware.org/?probe=b77c353ce5) | Dec 16, 2020 |
| Unknown       | MYIR YA157C v2 www.myir-... | [ff25232143](https://linux-hardware.org/?probe=ff25232143) | Dec 16, 2020 |
| Unknown       | MYIR YA157C v2 www.myir-... | [05c9576d64](https://linux-hardware.org/?probe=05c9576d64) | Dec 16, 2020 |
| Fujitsu Si... | D2348-A3 S26361-D2348-A3    | [d66bc8959a](https://linux-hardware.org/?probe=d66bc8959a) | Dec 16, 2020 |
| ASRock        | H110M-HDV R3.0              | [828060a4b7](https://linux-hardware.org/?probe=828060a4b7) | Dec 15, 2020 |
| Dell          | 0WMJ54 A01                  | [67ee19cbe2](https://linux-hardware.org/?probe=67ee19cbe2) | Dec 14, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [5e1b23e45c](https://linux-hardware.org/?probe=5e1b23e45c) | Dec 14, 2020 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fed59b1011](https://linux-hardware.org/?probe=fed59b1011) | Dec 11, 2020 |
| MSI           | H81M-P33                    | [cca3c6312c](https://linux-hardware.org/?probe=cca3c6312c) | Dec 11, 2020 |
| ASUSTek       | P5G41T-M LX2/BR             | [f41192428f](https://linux-hardware.org/?probe=f41192428f) | Dec 10, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [2012529d7d](https://linux-hardware.org/?probe=2012529d7d) | Dec 09, 2020 |
| Intel         | DH61WW AAG23116-204         | [73d09a904c](https://linux-hardware.org/?probe=73d09a904c) | Dec 09, 2020 |
| Lenovo        | MAHOBAY                     | [1713ff9b55](https://linux-hardware.org/?probe=1713ff9b55) | Dec 08, 2020 |
| HP            | 198E                        | [d6e4336d03](https://linux-hardware.org/?probe=d6e4336d03) | Dec 08, 2020 |
| ASRock        | J4105-ITX                   | [0fe9076bf2](https://linux-hardware.org/?probe=0fe9076bf2) | Dec 08, 2020 |
| ASUSTek       | Pro WS X570-ACE             | [8f0e11c580](https://linux-hardware.org/?probe=8f0e11c580) | Dec 07, 2020 |
| Lenovo        | 30C1                        | [fb66b925df](https://linux-hardware.org/?probe=fb66b925df) | Dec 06, 2020 |
| AZW           | GK55                        | [7c119fa50a](https://linux-hardware.org/?probe=7c119fa50a) | Dec 05, 2020 |
| Lenovo        | 0B98401 PRO                 | [ab06e56856](https://linux-hardware.org/?probe=ab06e56856) | Dec 04, 2020 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [70ab40ca28](https://linux-hardware.org/?probe=70ab40ca28) | Dec 04, 2020 |
| MSI           | Z77A-GD65                   | [da3b838497](https://linux-hardware.org/?probe=da3b838497) | Dec 04, 2020 |
| Gigabyte      | X99-Gaming 7 WIFI           | [02f825c83c](https://linux-hardware.org/?probe=02f825c83c) | Dec 02, 2020 |
| MSI           | X470 GAMING PRO             | [b910c55313](https://linux-hardware.org/?probe=b910c55313) | Dec 01, 2020 |
| Dell          | 0CT017                      | [738fa375a9](https://linux-hardware.org/?probe=738fa375a9) | Nov 30, 2020 |
| ASUSTek       | P8H77-V LE                  | [a0a0a8b958](https://linux-hardware.org/?probe=a0a0a8b958) | Nov 29, 2020 |
| ASUSTek       | P8H77-V LE                  | [49e0e5afc0](https://linux-hardware.org/?probe=49e0e5afc0) | Nov 29, 2020 |
| ASRock        | X370 Gaming K4              | [7b8b964ce4](https://linux-hardware.org/?probe=7b8b964ce4) | Nov 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | [341ccb93dd](https://linux-hardware.org/?probe=341ccb93dd) | Nov 28, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | [888e9357fa](https://linux-hardware.org/?probe=888e9357fa) | Nov 27, 2020 |
| ASUSTek       | A7N8X-X                     | [e3c769130d](https://linux-hardware.org/?probe=e3c769130d) | Nov 27, 2020 |
| MSI           | A320M-A PRO                 | [ce774acedc](https://linux-hardware.org/?probe=ce774acedc) | Nov 27, 2020 |
| ASRock        | X370 Gaming X               | [97d8b548f4](https://linux-hardware.org/?probe=97d8b548f4) | Nov 26, 2020 |
| ASUSTek       | PRIME X370-PRO              | [45e6832bd6](https://linux-hardware.org/?probe=45e6832bd6) | Nov 26, 2020 |
| Dell          | PowerEdge M620              | [203f23f8d5](https://linux-hardware.org/?probe=203f23f8d5) | Nov 26, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | [62f7833596](https://linux-hardware.org/?probe=62f7833596) | Nov 26, 2020 |
| MSI           | B85M-G43                    | [ac6b5ed34e](https://linux-hardware.org/?probe=ac6b5ed34e) | Nov 26, 2020 |
| Gigabyte      | GA-990FXA-D3                | [ef2284e597](https://linux-hardware.org/?probe=ef2284e597) | Nov 25, 2020 |
| Dell          | PowerEdge M620              | [9c01eac2db](https://linux-hardware.org/?probe=9c01eac2db) | Nov 25, 2020 |
| HP            | 8618                        | [91f724f25b](https://linux-hardware.org/?probe=91f724f25b) | Nov 25, 2020 |
| Foxconn       | 2AB1                        | [e9ab0b7c7c](https://linux-hardware.org/?probe=e9ab0b7c7c) | Nov 25, 2020 |
| Lenovo        | MAHOBAY                     | [2cb396f734](https://linux-hardware.org/?probe=2cb396f734) | Nov 24, 2020 |
| ASRock        | AM2NF6G-VSTA                | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Gigabyte      | MZBSWAP-K4                  | [88fb429442](https://linux-hardware.org/?probe=88fb429442) | Nov 22, 2020 |
| MSI           | MS-7368                     | [03a49d47f8](https://linux-hardware.org/?probe=03a49d47f8) | Nov 22, 2020 |
| Pegatron      | Benicia                     | [5022820b4c](https://linux-hardware.org/?probe=5022820b4c) | Nov 22, 2020 |
| MSI           | B350 PC MATE                | [9935ba7ce5](https://linux-hardware.org/?probe=9935ba7ce5) | Nov 21, 2020 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [d47b6c6cdb](https://linux-hardware.org/?probe=d47b6c6cdb) | Nov 20, 2020 |
| Gigabyte      | A320M-H-CF                  | [9fc31cde8f](https://linux-hardware.org/?probe=9fc31cde8f) | Nov 20, 2020 |
| Gigabyte      | A320M-H-CF                  | [0c209e45b2](https://linux-hardware.org/?probe=0c209e45b2) | Nov 20, 2020 |
| HP            | 8298                        | [4f8241fbe7](https://linux-hardware.org/?probe=4f8241fbe7) | Nov 20, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [701229ee2c](https://linux-hardware.org/?probe=701229ee2c) | Nov 19, 2020 |
| MSI           | Z270-A PRO                  | [caf24dedc0](https://linux-hardware.org/?probe=caf24dedc0) | Nov 18, 2020 |
| MSI           | Z270-A PRO                  | [f5551f2781](https://linux-hardware.org/?probe=f5551f2781) | Nov 18, 2020 |
| Lenovo        | Remore CRB Win8 STD MM D... | [3fdbcc01bc](https://linux-hardware.org/?probe=3fdbcc01bc) | Nov 17, 2020 |
| Gigabyte      | Z97N-WIFI                   | [fe8412c266](https://linux-hardware.org/?probe=fe8412c266) | Nov 16, 2020 |
| ASRock        | H97M Pro4                   | [11527337b8](https://linux-hardware.org/?probe=11527337b8) | Nov 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [2bf4bd6c9a](https://linux-hardware.org/?probe=2bf4bd6c9a) | Nov 15, 2020 |
| ASRock        | 870 Extreme3 R2.0           | [1c146f1cd6](https://linux-hardware.org/?probe=1c146f1cd6) | Nov 15, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cfe6d18879](https://linux-hardware.org/?probe=cfe6d18879) | Nov 15, 2020 |
| Dell          | 042P49 A00                  | [e88a5663df](https://linux-hardware.org/?probe=e88a5663df) | Nov 15, 2020 |
| ASRock        | X570M Pro4                  | [a898d5f094](https://linux-hardware.org/?probe=a898d5f094) | Nov 13, 2020 |
| ASUSTek       | P5B-V                       | [304644e229](https://linux-hardware.org/?probe=304644e229) | Nov 13, 2020 |
| ASUSTek       | B150M-C                     | [db1931d498](https://linux-hardware.org/?probe=db1931d498) | Nov 13, 2020 |
| Gigabyte      | Z97N-WIFI                   | [7b36788150](https://linux-hardware.org/?probe=7b36788150) | Nov 13, 2020 |
| MSI           | Z77A-GD65                   | [ec5dc55eee](https://linux-hardware.org/?probe=ec5dc55eee) | Nov 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6d86d3d7fd](https://linux-hardware.org/?probe=6d86d3d7fd) | Nov 12, 2020 |
| ASRock        | A55M-HVS                    | [5ad44f96db](https://linux-hardware.org/?probe=5ad44f96db) | Nov 10, 2020 |
| ASUSTek       | F2A85-M                     | [ab0866908c](https://linux-hardware.org/?probe=ab0866908c) | Nov 10, 2020 |
| Wistron       | ProLiant ML110 G6           | [a396b6d4f5](https://linux-hardware.org/?probe=a396b6d4f5) | Nov 10, 2020 |
| Megaware      | MW-H61H2-M2                 | [5fcb4ebbca](https://linux-hardware.org/?probe=5fcb4ebbca) | Nov 09, 2020 |
| Dell          | 0HN7XN A01                  | [fcb80e4af9](https://linux-hardware.org/?probe=fcb80e4af9) | Nov 09, 2020 |
| Gigabyte      | B250M-D3H-CF                | [7266773030](https://linux-hardware.org/?probe=7266773030) | Nov 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [f33a623bd5](https://linux-hardware.org/?probe=f33a623bd5) | Nov 08, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [78feb68c0c](https://linux-hardware.org/?probe=78feb68c0c) | Nov 06, 2020 |
| Dell          | 0HN7XN A01                  | [cd12fff60a](https://linux-hardware.org/?probe=cd12fff60a) | Nov 06, 2020 |
| ASUSTek       | M4N98TD EVO                 | [6c7624949a](https://linux-hardware.org/?probe=6c7624949a) | Nov 05, 2020 |
| ASRock        | 980DE3/U3S3                 | [be31445735](https://linux-hardware.org/?probe=be31445735) | Nov 05, 2020 |
| ASRock        | 980DE3/U3S3                 | [8083dfc89f](https://linux-hardware.org/?probe=8083dfc89f) | Nov 05, 2020 |
| Gigabyte      | B250M-D3H-CF                | [0a7ea62580](https://linux-hardware.org/?probe=0a7ea62580) | Nov 05, 2020 |
| Pegatron      | Benicia                     | [b424851832](https://linux-hardware.org/?probe=b424851832) | Nov 01, 2020 |
| Gigabyte      | 945GCM-S2L                  | [aad577e0e5](https://linux-hardware.org/?probe=aad577e0e5) | Oct 31, 2020 |
| ASRock        | 939A785GMH/128M             | [e5b7c1b0d3](https://linux-hardware.org/?probe=e5b7c1b0d3) | Oct 30, 2020 |
| Dell          | 0WX729                      | [e44b28e9c9](https://linux-hardware.org/?probe=e44b28e9c9) | Oct 29, 2020 |
| MSI           | Z87 MPOWER MAX              | [beeb97510d](https://linux-hardware.org/?probe=beeb97510d) | Oct 29, 2020 |
| ASRockRack    | X399D8A-2T                  | [069e75c80b](https://linux-hardware.org/?probe=069e75c80b) | Oct 28, 2020 |
| ASRockRack    | X399D8A-2T                  | [b8a8dbd1aa](https://linux-hardware.org/?probe=b8a8dbd1aa) | Oct 28, 2020 |
| ASUSTek       | P6T DELUXE V2               | [0283516646](https://linux-hardware.org/?probe=0283516646) | Oct 27, 2020 |
| ASUSTek       | H170M-PLUS                  | [d7ad752c1b](https://linux-hardware.org/?probe=d7ad752c1b) | Oct 27, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [c2f5389d87](https://linux-hardware.org/?probe=c2f5389d87) | Oct 27, 2020 |
| Gigabyte      | B250M-D3H-CF                | [fb20b8ea23](https://linux-hardware.org/?probe=fb20b8ea23) | Oct 26, 2020 |
| Acer          | JM11-MS                     | [069625e15a](https://linux-hardware.org/?probe=069625e15a) | Oct 25, 2020 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [51a8e7def6](https://linux-hardware.org/?probe=51a8e7def6) | Oct 23, 2020 |
| Gigabyte      | GA-MA74GM-S2                | [0db1128411](https://linux-hardware.org/?probe=0db1128411) | Oct 22, 2020 |
| Intel         | DG31PR AAE58249-302         | [ba629e15c8](https://linux-hardware.org/?probe=ba629e15c8) | Oct 22, 2020 |
| Gigabyte      | G33M-S2                     | [4d9dc543e1](https://linux-hardware.org/?probe=4d9dc543e1) | Oct 21, 2020 |
| ASUSTek       | PRIME B460M-A               | [54531ec292](https://linux-hardware.org/?probe=54531ec292) | Oct 21, 2020 |
| ASUSTek       | PRIME X470-PRO              | [2872b539f1](https://linux-hardware.org/?probe=2872b539f1) | Oct 19, 2020 |
| ASRock        | B450M Pro4                  | [09c5a76d3d](https://linux-hardware.org/?probe=09c5a76d3d) | Oct 18, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [531f62fbbc](https://linux-hardware.org/?probe=531f62fbbc) | Oct 18, 2020 |
| Positivo      | POS-RIB360EC 11136256       | [267fefb15d](https://linux-hardware.org/?probe=267fefb15d) | Oct 18, 2020 |
| Positivo      | POS-RIB360EC 11136256       | [a45a40ef0b](https://linux-hardware.org/?probe=a45a40ef0b) | Oct 18, 2020 |
| Unknown       | Wandboard i.MX6 Quad Boa... | [be678ef068](https://linux-hardware.org/?probe=be678ef068) | Oct 17, 2020 |
| HP            | 2820h                       | [8694668041](https://linux-hardware.org/?probe=8694668041) | Oct 17, 2020 |
| MSI           | Z97A GAMING 9 ACK           | [b5e973e4f0](https://linux-hardware.org/?probe=b5e973e4f0) | Oct 16, 2020 |
| Intel         | DH67CL AAG10212-207         | [12e9069f62](https://linux-hardware.org/?probe=12e9069f62) | Oct 16, 2020 |
| ASUSTek       | M2A-VM                      | [1c0ef6e25d](https://linux-hardware.org/?probe=1c0ef6e25d) | Oct 16, 2020 |
| ASUSTek       | M2A-VM                      | [b8a0c6dc95](https://linux-hardware.org/?probe=b8a0c6dc95) | Oct 16, 2020 |
| Foxconn       | 2ABF                        | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| MSI           | 760GM-P23                   | [677c251a9b](https://linux-hardware.org/?probe=677c251a9b) | Oct 15, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [a22472ccb2](https://linux-hardware.org/?probe=a22472ccb2) | Oct 15, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [15a5096b73](https://linux-hardware.org/?probe=15a5096b73) | Oct 15, 2020 |
| Gigabyte      | H87M-HD3                    | [877cf6e54f](https://linux-hardware.org/?probe=877cf6e54f) | Oct 14, 2020 |
| Acer          | Aspire X3400                | [4f32e6a1ff](https://linux-hardware.org/?probe=4f32e6a1ff) | Oct 13, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [afa3aae782](https://linux-hardware.org/?probe=afa3aae782) | Oct 13, 2020 |
| Dell          | 08NPPY A00                  | [77ee3ecf22](https://linux-hardware.org/?probe=77ee3ecf22) | Oct 13, 2020 |
| Dell          | 08NPPY A00                  | [fa2e953405](https://linux-hardware.org/?probe=fa2e953405) | Oct 13, 2020 |
| ASUSTek       | P5Q-EM                      | [858523dac6](https://linux-hardware.org/?probe=858523dac6) | Oct 13, 2020 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [c8b5ea0da0](https://linux-hardware.org/?probe=c8b5ea0da0) | Oct 13, 2020 |
| Unknown       | SKYBAY                      | [fe4f23059b](https://linux-hardware.org/?probe=fe4f23059b) | Oct 13, 2020 |
| Medion        | MS-7848                     | [7fac92ad6e](https://linux-hardware.org/?probe=7fac92ad6e) | Oct 13, 2020 |
| HP            | 3397                        | [ad8f96cd61](https://linux-hardware.org/?probe=ad8f96cd61) | Oct 12, 2020 |
| Gigabyte      | MZBSWAP-00                  | [5b56790b14](https://linux-hardware.org/?probe=5b56790b14) | Oct 12, 2020 |
| ASUSTek       | P8H61-M LE                  | [cadcc85a1e](https://linux-hardware.org/?probe=cadcc85a1e) | Oct 12, 2020 |
| MSI           | MEG Z490 UNIFY              | [a4189eceb8](https://linux-hardware.org/?probe=a4189eceb8) | Oct 09, 2020 |
| Acer          | Aspire X3400                | [d3e4761754](https://linux-hardware.org/?probe=d3e4761754) | Oct 09, 2020 |
| Foxconn       | 2ABF                        | [2c77c76b2b](https://linux-hardware.org/?probe=2c77c76b2b) | Oct 09, 2020 |
| Gigabyte      | 970A-DS3P                   | [943240cc2a](https://linux-hardware.org/?probe=943240cc2a) | Oct 09, 2020 |
| ASRock        | FM2A88M-HD+                 | [a77811a56d](https://linux-hardware.org/?probe=a77811a56d) | Oct 09, 2020 |
| ASUSTek       | M2N                         | [0356749684](https://linux-hardware.org/?probe=0356749684) | Oct 09, 2020 |
| Intel         | DQ67EP AAG12529-309         | [5ccd8517ea](https://linux-hardware.org/?probe=5ccd8517ea) | Oct 07, 2020 |
| Intel         | DQ67EP AAG12529-309         | [9dda3c79bf](https://linux-hardware.org/?probe=9dda3c79bf) | Oct 07, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [2f9245f3ab](https://linux-hardware.org/?probe=2f9245f3ab) | Oct 05, 2020 |
| ASRock        | A320M-HDV R3.0              | [c4ccc34194](https://linux-hardware.org/?probe=c4ccc34194) | Oct 05, 2020 |
| Foxconn       | M61PMV FAB A1               | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| HP            | 339A                        | [92af508797](https://linux-hardware.org/?probe=92af508797) | Oct 04, 2020 |
| Intel         | D945GCNL AAD97184-102       | [4a43e3fa8c](https://linux-hardware.org/?probe=4a43e3fa8c) | Oct 03, 2020 |
| Intel         | D945GCNL AAD97184-102       | [db86d15d03](https://linux-hardware.org/?probe=db86d15d03) | Oct 03, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [605fe21a48](https://linux-hardware.org/?probe=605fe21a48) | Oct 03, 2020 |
| ASUSTek       | P8P67 LE                    | [ead5ba8555](https://linux-hardware.org/?probe=ead5ba8555) | Oct 02, 2020 |
| Dell          | 06D7TR A00                  | [b03897d3e4](https://linux-hardware.org/?probe=b03897d3e4) | Oct 01, 2020 |
| ASRock        | FM2A88M-HD+                 | [94f8834aad](https://linux-hardware.org/?probe=94f8834aad) | Oct 01, 2020 |
| ASUSTek       | Crosshair IV Formula        | [148be00ebb](https://linux-hardware.org/?probe=148be00ebb) | Sep 29, 2020 |
| MSI           | X399 GAMING PRO CARBON A... | [3b92d6cc85](https://linux-hardware.org/?probe=3b92d6cc85) | Sep 29, 2020 |
| Dell          | 096JG8 A01                  | [a7a177814c](https://linux-hardware.org/?probe=a7a177814c) | Sep 28, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | [77c33537e5](https://linux-hardware.org/?probe=77c33537e5) | Sep 28, 2020 |
| Gigabyte      | EP41-UD3L                   | [ac9a3861d4](https://linux-hardware.org/?probe=ac9a3861d4) | Sep 28, 2020 |
| MSI           | B75MA-S01                   | [ebdad249a2](https://linux-hardware.org/?probe=ebdad249a2) | Sep 27, 2020 |
| HP            | 3396                        | [621f4fa508](https://linux-hardware.org/?probe=621f4fa508) | Sep 23, 2020 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ff4751f413](https://linux-hardware.org/?probe=ff4751f413) | Sep 22, 2020 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [1d3784b506](https://linux-hardware.org/?probe=1d3784b506) | Sep 22, 2020 |
| ASRock        | A320M-HDV R3.0              | [70911dd742](https://linux-hardware.org/?probe=70911dd742) | Sep 18, 2020 |
| HP            | 0A64h                       | [f329c9fbec](https://linux-hardware.org/?probe=f329c9fbec) | Sep 16, 2020 |
| Intel         | DH87RL AAG74240-403         | [afa08a0ab9](https://linux-hardware.org/?probe=afa08a0ab9) | Sep 16, 2020 |
| Intel         | DH87RL AAG74240-403         | [1f8ed93153](https://linux-hardware.org/?probe=1f8ed93153) | Sep 16, 2020 |
| HP            | 1497                        | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Intel         | DQ35JO AAD82085-807         | [18f66cd9d7](https://linux-hardware.org/?probe=18f66cd9d7) | Sep 14, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [40ea341aaf](https://linux-hardware.org/?probe=40ea341aaf) | Sep 13, 2020 |
| ASRock        | A300M-STX                   | [7365686a0b](https://linux-hardware.org/?probe=7365686a0b) | Sep 13, 2020 |
| ASRock        | A320M-HDV R3.0              | [c9cdefc34c](https://linux-hardware.org/?probe=c9cdefc34c) | Sep 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09611dd419](https://linux-hardware.org/?probe=09611dd419) | Sep 13, 2020 |
| ASRock        | A320M-HDV R3.0              | [d33962bb92](https://linux-hardware.org/?probe=d33962bb92) | Sep 13, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [e26825872a](https://linux-hardware.org/?probe=e26825872a) | Sep 12, 2020 |
| MSI           | Z68A-G43                    | [55f0c0df73](https://linux-hardware.org/?probe=55f0c0df73) | Sep 11, 2020 |
| Gigabyte      | P67A-UD5-B3                 | [b822c2d996](https://linux-hardware.org/?probe=b822c2d996) | Sep 11, 2020 |
| Biostar       | T41 HD                      | [39b5b4656c](https://linux-hardware.org/?probe=39b5b4656c) | Sep 11, 2020 |
| AZW           | Gemini X55                  | [b109444fe7](https://linux-hardware.org/?probe=b109444fe7) | Sep 10, 2020 |
| AZW           | Gemini X55                  | [2ba4c8e41a](https://linux-hardware.org/?probe=2ba4c8e41a) | Sep 09, 2020 |
| ASRock        | 960GM/U3S3 FX               | [68d855db3a](https://linux-hardware.org/?probe=68d855db3a) | Sep 09, 2020 |
| ASUSTek       | X99-PRO/USB                 | [231f0afb76](https://linux-hardware.org/?probe=231f0afb76) | Sep 09, 2020 |
| Lenovo        | 3098 0B98401 PRO            | [ea6ae6b2f9](https://linux-hardware.org/?probe=ea6ae6b2f9) | Sep 08, 2020 |
| ASUSTek       | M4A77                       | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| Lenovo        | ThinkCentre M55 88088NU     | [43451ccbfa](https://linux-hardware.org/?probe=43451ccbfa) | Sep 06, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [40c30fec1b](https://linux-hardware.org/?probe=40c30fec1b) | Sep 06, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [1a1ea49dab](https://linux-hardware.org/?probe=1a1ea49dab) | Sep 06, 2020 |
| AZW           | AP35                        | [57c2508765](https://linux-hardware.org/?probe=57c2508765) | Sep 06, 2020 |
| Gigabyte      | F2A78M-HD2                  | [07113893e5](https://linux-hardware.org/?probe=07113893e5) | Sep 05, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [1333ab42d5](https://linux-hardware.org/?probe=1333ab42d5) | Sep 04, 2020 |
| ASUSTek       | NODUSM3                     | [f8d3ca460a](https://linux-hardware.org/?probe=f8d3ca460a) | Sep 04, 2020 |
| Gigabyte      | GA-G41M-ES2L                | [5398d4f86b](https://linux-hardware.org/?probe=5398d4f86b) | Sep 04, 2020 |
| ASRock        | H61M-VG4                    | [f6179be2ef](https://linux-hardware.org/?probe=f6179be2ef) | Sep 04, 2020 |
| MSI           | B350M MORTAR                | [ebcd809d62](https://linux-hardware.org/?probe=ebcd809d62) | Sep 03, 2020 |
| Gigabyte      | Z97N-WIFI                   | [71bba21fc9](https://linux-hardware.org/?probe=71bba21fc9) | Sep 03, 2020 |
| Supermicro    | X9DRFR                      | [1f3561aa7d](https://linux-hardware.org/?probe=1f3561aa7d) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD3H                   | [000a7af3ea](https://linux-hardware.org/?probe=000a7af3ea) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD3H                   | [d3c695771b](https://linux-hardware.org/?probe=d3c695771b) | Sep 03, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [a153048697](https://linux-hardware.org/?probe=a153048697) | Sep 01, 2020 |
| ASRock        | X570 Pro4                   | [665b7470ff](https://linux-hardware.org/?probe=665b7470ff) | Sep 01, 2020 |
| ASRock        | X570 Pro4                   | [9afa25f7bb](https://linux-hardware.org/?probe=9afa25f7bb) | Aug 31, 2020 |
| Fujitsu Si... | D2348-A3 S26361-D2348-A3    | [843ea33bcc](https://linux-hardware.org/?probe=843ea33bcc) | Aug 30, 2020 |
| Dell          | 042P49 A00                  | [3ec693eea3](https://linux-hardware.org/?probe=3ec693eea3) | Aug 29, 2020 |
| Dell          | 042P49 A00                  | [acac2f44bc](https://linux-hardware.org/?probe=acac2f44bc) | Aug 29, 2020 |
| Foxconn       | 2AB1                        | [ecb7d026d5](https://linux-hardware.org/?probe=ecb7d026d5) | Aug 29, 2020 |
| Biostar       | T41 HD                      | [83871efe98](https://linux-hardware.org/?probe=83871efe98) | Aug 28, 2020 |
| Lenovo        | 7033EW4                     | [c072a212c4](https://linux-hardware.org/?probe=c072a212c4) | Aug 28, 2020 |
| Lenovo        | 7033EW4                     | [fea8f87952](https://linux-hardware.org/?probe=fea8f87952) | Aug 28, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [5ef7a4cb4f](https://linux-hardware.org/?probe=5ef7a4cb4f) | Aug 24, 2020 |
| Shuttle       | FH61V                       | [e6c5ae10a4](https://linux-hardware.org/?probe=e6c5ae10a4) | Aug 22, 2020 |
| ASUSTek       | Pro WS X570-ACE             | [6134825d43](https://linux-hardware.org/?probe=6134825d43) | Aug 21, 2020 |
| Unknown       | Unknown                     | [3afed2a8bc](https://linux-hardware.org/?probe=3afed2a8bc) | Aug 20, 2020 |
| Dell          | 09M8Y8 A01                  | [0da4fd7184](https://linux-hardware.org/?probe=0da4fd7184) | Aug 19, 2020 |
| ASRock        | J4105-ITX                   | [48444a47de](https://linux-hardware.org/?probe=48444a47de) | Aug 19, 2020 |
| ASUSTek       | PRIME H310M-K R2.0          | [6fa3c39e79](https://linux-hardware.org/?probe=6fa3c39e79) | Aug 19, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [ff30cd0d5c](https://linux-hardware.org/?probe=ff30cd0d5c) | Aug 12, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [4219c82d3b](https://linux-hardware.org/?probe=4219c82d3b) | Aug 12, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [6423f78c3c](https://linux-hardware.org/?probe=6423f78c3c) | Aug 11, 2020 |
| ASUSTek       | A88XM-A                     | [936b2a7000](https://linux-hardware.org/?probe=936b2a7000) | Aug 08, 2020 |
| MSI           | MAG B365M MORTAR            | [556e62e1a3](https://linux-hardware.org/?probe=556e62e1a3) | Aug 07, 2020 |
| ASUSTek       | P9X79                       | [16796af2c3](https://linux-hardware.org/?probe=16796af2c3) | Aug 06, 2020 |
| ASRock        | FM2A88M Extreme4+           | [5e02d66bbf](https://linux-hardware.org/?probe=5e02d66bbf) | Aug 05, 2020 |
| ASUSTek       | P6X58D-E                    | [5c731d7021](https://linux-hardware.org/?probe=5c731d7021) | Aug 04, 2020 |
| ASUSTek       | H81M-C/BR                   | [8308308816](https://linux-hardware.org/?probe=8308308816) | Aug 04, 2020 |
| ASRock        | Wolfdale1333-D667           | [28f833cf16](https://linux-hardware.org/?probe=28f833cf16) | Aug 03, 2020 |
| ASRock        | Wolfdale1333-D667           | [c8ecc77711](https://linux-hardware.org/?probe=c8ecc77711) | Aug 03, 2020 |
| Intel         | D54250WYK H13922-303        | [887f56c31c](https://linux-hardware.org/?probe=887f56c31c) | Aug 01, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e5610b0d56](https://linux-hardware.org/?probe=e5610b0d56) | Jul 31, 2020 |
| ASRock        | H97 Anniversary             | [ce5e83f744](https://linux-hardware.org/?probe=ce5e83f744) | Jul 28, 2020 |
| PCWare        | IPMH81G1                    | [fec3e4c639](https://linux-hardware.org/?probe=fec3e4c639) | Jul 26, 2020 |
| PCWare        | IPMH81G1                    | [5b8888c7c7](https://linux-hardware.org/?probe=5b8888c7c7) | Jul 26, 2020 |
| Gigabyte      | G31M-S2C                    | [ac6ef957ff](https://linux-hardware.org/?probe=ac6ef957ff) | Jul 26, 2020 |
| ASUSTek       | P9X79                       | [b5e0ef963b](https://linux-hardware.org/?probe=b5e0ef963b) | Jul 26, 2020 |
| Gigabyte      | X99-Gaming 7 WIFI           | [e340cdaf55](https://linux-hardware.org/?probe=e340cdaf55) | Jul 26, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f34a4c062d](https://linux-hardware.org/?probe=f34a4c062d) | Jul 26, 2020 |
| ASUSTek       | P9X79                       | [def2e542ec](https://linux-hardware.org/?probe=def2e542ec) | Jul 25, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [1d18d6d402](https://linux-hardware.org/?probe=1d18d6d402) | Jul 25, 2020 |
| Positivo      | POS-EINM10CB NEOPC          | [f5365923ba](https://linux-hardware.org/?probe=f5365923ba) | Jul 25, 2020 |
| Positivo      | POS-EINM10CB NEOPC          | [ff4d854b6d](https://linux-hardware.org/?probe=ff4d854b6d) | Jul 25, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [8b1a09da3b](https://linux-hardware.org/?probe=8b1a09da3b) | Jul 24, 2020 |
| ASUSTek       | Rampage V EXTREME           | [1e863840a3](https://linux-hardware.org/?probe=1e863840a3) | Jul 24, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [1cbb1e8894](https://linux-hardware.org/?probe=1cbb1e8894) | Jul 24, 2020 |
| ASUSTek       | ET2221I-B85                 | [d2acbc27c0](https://linux-hardware.org/?probe=d2acbc27c0) | Jul 23, 2020 |
| ASUSTek       | ET2221I-B85                 | [351c9c2459](https://linux-hardware.org/?probe=351c9c2459) | Jul 23, 2020 |
| ASUSTek       | SABERTOOTH X79              | [beef04bbd6](https://linux-hardware.org/?probe=beef04bbd6) | Jul 23, 2020 |
| Gigabyte      | H67M-D2-B3                  | [4fb81f4249](https://linux-hardware.org/?probe=4fb81f4249) | Jul 22, 2020 |
| Dell          | 06D7TR A00                  | [84faf62b94](https://linux-hardware.org/?probe=84faf62b94) | Jul 21, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [3434e8ac4d](https://linux-hardware.org/?probe=3434e8ac4d) | Jul 19, 2020 |
| Dell          | 0R230R A00                  | [fcfb060cfe](https://linux-hardware.org/?probe=fcfb060cfe) | Jul 18, 2020 |
| ASUSTek       | P7H55D-M EVO                | [298e558310](https://linux-hardware.org/?probe=298e558310) | Jul 18, 2020 |
| AZW           | AP35                        | [129c6a151a](https://linux-hardware.org/?probe=129c6a151a) | Jul 15, 2020 |
| Gigabyte      | 970A-DS3P                   | [ee918422af](https://linux-hardware.org/?probe=ee918422af) | Jul 14, 2020 |
| Gigabyte      | B250M-D3H-CF                | [c0ff1007eb](https://linux-hardware.org/?probe=c0ff1007eb) | Jul 13, 2020 |
| ASUSTek       | SABERTOOTH X79              | [915bc88656](https://linux-hardware.org/?probe=915bc88656) | Jul 09, 2020 |
| Lenovo        | ThinkCentre M58 7359WQR     | [73e0df5013](https://linux-hardware.org/?probe=73e0df5013) | Jul 09, 2020 |
| Gigabyte      | 990FXA-UD3                  | [0200066f05](https://linux-hardware.org/?probe=0200066f05) | Jul 09, 2020 |
| ASUSTek       | H110M-E                     | [9597e47aa0](https://linux-hardware.org/?probe=9597e47aa0) | Jul 08, 2020 |
| HP            | ProLiant ML10 v2            | [b0cc993430](https://linux-hardware.org/?probe=b0cc993430) | Jul 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f680a985bf](https://linux-hardware.org/?probe=f680a985bf) | Jul 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [333fcb65b5](https://linux-hardware.org/?probe=333fcb65b5) | Jul 04, 2020 |
| Gigabyte      | EP45-UD3P                   | [f5fe7c30a0](https://linux-hardware.org/?probe=f5fe7c30a0) | Jul 04, 2020 |
| ASUSTek       | TUF Z270 MARK 1             | [bd34c715b3](https://linux-hardware.org/?probe=bd34c715b3) | Jul 04, 2020 |
| HP            | ProLiant ML10 v2            | [c95159e99f](https://linux-hardware.org/?probe=c95159e99f) | Jul 02, 2020 |
| Dell          | 0KWVT8 A00                  | [96c2bd275e](https://linux-hardware.org/?probe=96c2bd275e) | Jun 30, 2020 |
| NetGear       | ReadyDATA 5200              | [318b1cbacd](https://linux-hardware.org/?probe=318b1cbacd) | Jun 26, 2020 |
| AZW           | AP35                        | [6166c5d0ee](https://linux-hardware.org/?probe=6166c5d0ee) | Jun 25, 2020 |
| ASRock        | AB350M Pro4                 | [14e2fc82a2](https://linux-hardware.org/?probe=14e2fc82a2) | Jun 25, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [cc020f58cc](https://linux-hardware.org/?probe=cc020f58cc) | Jun 22, 2020 |
| Gigabyte      | TRX40 AORUS MASTER          | [445689e793](https://linux-hardware.org/?probe=445689e793) | Jun 19, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [eea45be825](https://linux-hardware.org/?probe=eea45be825) | Jun 19, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | [b6322296ad](https://linux-hardware.org/?probe=b6322296ad) | Jun 18, 2020 |
| ASUSTek       | Z87-C                       | [21183e7df5](https://linux-hardware.org/?probe=21183e7df5) | Jun 17, 2020 |
| Dell          | 0GN6JF A01                  | [452e0f2712](https://linux-hardware.org/?probe=452e0f2712) | Jun 16, 2020 |
| Alienware     | 07JNH0 A00                  | [2951b9c787](https://linux-hardware.org/?probe=2951b9c787) | Jun 16, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [34b79180ca](https://linux-hardware.org/?probe=34b79180ca) | Jun 16, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ab1920d3ae](https://linux-hardware.org/?probe=ab1920d3ae) | Jun 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a01cc45fc9](https://linux-hardware.org/?probe=a01cc45fc9) | Jun 15, 2020 |
| MSI           | B350M GAMING PRO            | [e4e55c9086](https://linux-hardware.org/?probe=e4e55c9086) | Jun 13, 2020 |
| ASRock        | D1800B-ITX                  | [2dd5ff6c79](https://linux-hardware.org/?probe=2dd5ff6c79) | Jun 13, 2020 |
| Gigabyte      | B450M S2H                   | [4e6a9e5117](https://linux-hardware.org/?probe=4e6a9e5117) | Jun 12, 2020 |
| ASRock        | N3160-NUC IPC               | [a0ad92a904](https://linux-hardware.org/?probe=a0ad92a904) | Jun 12, 2020 |
| ASRock        | H370M-ITX/ac                | [1013a7bdeb](https://linux-hardware.org/?probe=1013a7bdeb) | Jun 10, 2020 |
| Dell          | 0CT017                      | [cc9a2bc165](https://linux-hardware.org/?probe=cc9a2bc165) | Jun 08, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [2251f26205](https://linux-hardware.org/?probe=2251f26205) | Jun 08, 2020 |
| ASUSTek       | Z97-PRO                     | [f59d1dadad](https://linux-hardware.org/?probe=f59d1dadad) | Jun 07, 2020 |
| Gigabyte      | H170-D3H-CF                 | [103c052e67](https://linux-hardware.org/?probe=103c052e67) | Jun 06, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4e7221a789](https://linux-hardware.org/?probe=4e7221a789) | Jun 06, 2020 |
| ASUSTek       | M5A97 R2.0                  | [feebe9e438](https://linux-hardware.org/?probe=feebe9e438) | Jun 03, 2020 |
| CCE           | G31T-M7                     | [761d76fe04](https://linux-hardware.org/?probe=761d76fe04) | Jun 02, 2020 |
| Gigabyte      | 945GCM-S2L                  | [8250560eee](https://linux-hardware.org/?probe=8250560eee) | May 30, 2020 |
| ASUSTek       | M5A97 R2.0                  | [d6fdecb2a8](https://linux-hardware.org/?probe=d6fdecb2a8) | May 29, 2020 |
| ASUSTek       | M5A97 R2.0                  | [fccd6d2acb](https://linux-hardware.org/?probe=fccd6d2acb) | May 29, 2020 |
| ECS           | G41T-M7                     | [60100d83b7](https://linux-hardware.org/?probe=60100d83b7) | May 29, 2020 |
| ASUSTek       | Pro WS X570-ACE             | [652cd0cd19](https://linux-hardware.org/?probe=652cd0cd19) | May 29, 2020 |
| ASUSTek       | P8H61-M LE                  | [d225118544](https://linux-hardware.org/?probe=d225118544) | May 28, 2020 |
| ASUSTek       | P8H61-M LE                  | [cc579e4b79](https://linux-hardware.org/?probe=cc579e4b79) | May 28, 2020 |
| ASUSTek       | SABERTOOTH X79              | [6972e59328](https://linux-hardware.org/?probe=6972e59328) | May 27, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Gigabyte      | F2A78M-HD2                  | [621ff023c5](https://linux-hardware.org/?probe=621ff023c5) | May 26, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [06a5779a21](https://linux-hardware.org/?probe=06a5779a21) | May 26, 2020 |
| ASUSTek       | P9X79 PRO                   | [8d60a2ddb8](https://linux-hardware.org/?probe=8d60a2ddb8) | May 25, 2020 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [e525642f48](https://linux-hardware.org/?probe=e525642f48) | May 24, 2020 |
| Gigabyte      | EX58-UD4P                   | [e837590e78](https://linux-hardware.org/?probe=e837590e78) | May 23, 2020 |
| Unknown       | Unknown                     | [dd319b8387](https://linux-hardware.org/?probe=dd319b8387) | May 23, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| ASUSTek       | K31CD-K                     | [099aab330b](https://linux-hardware.org/?probe=099aab330b) | May 22, 2020 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [365dfa9b0d](https://linux-hardware.org/?probe=365dfa9b0d) | May 21, 2020 |
| Gigabyte      | C1037UN-EU                  | [afe6e909ce](https://linux-hardware.org/?probe=afe6e909ce) | May 20, 2020 |
| Gigabyte      | C1037UN-EU                  | [bfef5156aa](https://linux-hardware.org/?probe=bfef5156aa) | May 20, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [2b1062016d](https://linux-hardware.org/?probe=2b1062016d) | May 20, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [70944d71b9](https://linux-hardware.org/?probe=70944d71b9) | May 18, 2020 |
| ASUSTek       | V-P8H67E                    | [4edb22da2d](https://linux-hardware.org/?probe=4edb22da2d) | May 18, 2020 |
| Dell          | 088DT1 A01                  | [56e4f7c82b](https://linux-hardware.org/?probe=56e4f7c82b) | May 18, 2020 |
| ASRock        | EP2C602-4L/D16              | [00900576c2](https://linux-hardware.org/?probe=00900576c2) | May 17, 2020 |
| ASUSTek       | Pro WS X570-ACE             | [92b2805d92](https://linux-hardware.org/?probe=92b2805d92) | May 16, 2020 |
| Apple         | Mac-F221BEC8                | [54afc0d91b](https://linux-hardware.org/?probe=54afc0d91b) | May 16, 2020 |
| ASRock        | X570 Extreme4               | [f27120c647](https://linux-hardware.org/?probe=f27120c647) | May 15, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [8558e7f816](https://linux-hardware.org/?probe=8558e7f816) | May 15, 2020 |
| AZW           | AP35                        | [6ff418c22d](https://linux-hardware.org/?probe=6ff418c22d) | May 13, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [4316a8db1f](https://linux-hardware.org/?probe=4316a8db1f) | May 13, 2020 |
| AZW           | AP35                        | [5b4d6e509e](https://linux-hardware.org/?probe=5b4d6e509e) | May 10, 2020 |
| AZW           | AP35                        | [6ecbc4dec2](https://linux-hardware.org/?probe=6ecbc4dec2) | May 10, 2020 |
| ASRock        | D1800B-ITX                  | [6fea6011bd](https://linux-hardware.org/?probe=6fea6011bd) | May 10, 2020 |
| ONDA          | A68V+                       | [2e1e0d1c4f](https://linux-hardware.org/?probe=2e1e0d1c4f) | May 08, 2020 |
| Gigabyte      | M61SME-S2                   | [e29bc9ac9d](https://linux-hardware.org/?probe=e29bc9ac9d) | May 06, 2020 |
| Intel         | DG31PR AAE58249-302         | [5127f7350b](https://linux-hardware.org/?probe=5127f7350b) | May 05, 2020 |
| ASUSTek       | P5QL                        | [ee2cb4e2d9](https://linux-hardware.org/?probe=ee2cb4e2d9) | May 05, 2020 |
| Gigabyte      | MZBSWBP-00                  | [186b619a5e](https://linux-hardware.org/?probe=186b619a5e) | May 04, 2020 |
| HP            | ProLiant MicroServer Gen... | [d61527d0ac](https://linux-hardware.org/?probe=d61527d0ac) | May 03, 2020 |
| ASRock        | D1800B-ITX                  | [c370b45af1](https://linux-hardware.org/?probe=c370b45af1) | May 01, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [30806c27ea](https://linux-hardware.org/?probe=30806c27ea) | May 01, 2020 |
| Dell          | Inspiron 5676               | [a0bfceb399](https://linux-hardware.org/?probe=a0bfceb399) | May 01, 2020 |
| ASRock        | D1800B-ITX                  | [c6e7ca8fe8](https://linux-hardware.org/?probe=c6e7ca8fe8) | May 01, 2020 |
| Gigabyte      | M61SME-S2                   | [dd84ddfb9e](https://linux-hardware.org/?probe=dd84ddfb9e) | Apr 30, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1d554422a9](https://linux-hardware.org/?probe=1d554422a9) | Apr 29, 2020 |
| Gigabyte      | N3050ND3H                   | [3f7cfb988e](https://linux-hardware.org/?probe=3f7cfb988e) | Apr 29, 2020 |
| MSI           | Creator TRX40               | [7539da519d](https://linux-hardware.org/?probe=7539da519d) | Apr 29, 2020 |
| MSI           | Creator TRX40               | [a363b3b103](https://linux-hardware.org/?probe=a363b3b103) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| Gigabyte      | GA-880GMA-UD2H              | [bddaf3c123](https://linux-hardware.org/?probe=bddaf3c123) | Apr 28, 2020 |
| MSI           | KA790GX MS-7551             | [0b976bce4c](https://linux-hardware.org/?probe=0b976bce4c) | Apr 27, 2020 |
| ASUSTek       | P6T SE                      | [cb688ef5cb](https://linux-hardware.org/?probe=cb688ef5cb) | Apr 25, 2020 |
| MSI           | Z97 GAMING 9 ACK            | [7b9e17c081](https://linux-hardware.org/?probe=7b9e17c081) | Apr 25, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [1a9077ab60](https://linux-hardware.org/?probe=1a9077ab60) | Apr 24, 2020 |
| HP            | 18E7                        | [12eba05e5a](https://linux-hardware.org/?probe=12eba05e5a) | Apr 23, 2020 |
| Fujitsu Si... | D2314-A3 S26361-D2314-A3    | [f626d15b06](https://linux-hardware.org/?probe=f626d15b06) | Apr 23, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [48acf05b1b](https://linux-hardware.org/?probe=48acf05b1b) | Apr 23, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [a9c93eb1de](https://linux-hardware.org/?probe=a9c93eb1de) | Apr 22, 2020 |
| HP            | 18E7                        | [94a4d96ad2](https://linux-hardware.org/?probe=94a4d96ad2) | Apr 21, 2020 |
| HP            | 18E7                        | [746f956b7b](https://linux-hardware.org/?probe=746f956b7b) | Apr 21, 2020 |
| ASUSTek       | Z87-DELUXE/DUAL             | [07707e74b7](https://linux-hardware.org/?probe=07707e74b7) | Apr 21, 2020 |
| ASRock        | X570M Pro4                  | [84162d8ef3](https://linux-hardware.org/?probe=84162d8ef3) | Apr 21, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | [17a06687d4](https://linux-hardware.org/?probe=17a06687d4) | Apr 20, 2020 |
| ASUSTek       | Z87-DELUXE/DUAL             | [6f8aef578d](https://linux-hardware.org/?probe=6f8aef578d) | Apr 20, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [a90f89123d](https://linux-hardware.org/?probe=a90f89123d) | Apr 20, 2020 |
| ASUSTek       | P5B                         | [436080c949](https://linux-hardware.org/?probe=436080c949) | Apr 20, 2020 |
| Pegatron      | Benicia                     | [8ac933db04](https://linux-hardware.org/?probe=8ac933db04) | Apr 20, 2020 |
| Dell          | 0X7967                      | [265584a6eb](https://linux-hardware.org/?probe=265584a6eb) | Apr 19, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [a516406a6a](https://linux-hardware.org/?probe=a516406a6a) | Apr 19, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [ebd71cc64d](https://linux-hardware.org/?probe=ebd71cc64d) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bbd20923db](https://linux-hardware.org/?probe=bbd20923db) | Apr 18, 2020 |
| Gigabyte      | 945GCM-S2L                  | [73d24cd7c3](https://linux-hardware.org/?probe=73d24cd7c3) | Apr 16, 2020 |
| ASUSTek       | A88XM-A                     | [4f9ab2d6f2](https://linux-hardware.org/?probe=4f9ab2d6f2) | Apr 14, 2020 |
| Dell          | 0CU409                      | [017b9137d9](https://linux-hardware.org/?probe=017b9137d9) | Apr 14, 2020 |
| ASUSTek       | SABERTOOTH X79              | [2a9bc14a46](https://linux-hardware.org/?probe=2a9bc14a46) | Apr 11, 2020 |
| Supermicro    | X10SDE-DF                   | [ae18373146](https://linux-hardware.org/?probe=ae18373146) | Apr 10, 2020 |
| Intel         | DG31PR AAE58249-302         | [16ba90975a](https://linux-hardware.org/?probe=16ba90975a) | Apr 08, 2020 |
| MSI           | Z77A-GD65                   | [216bf075a1](https://linux-hardware.org/?probe=216bf075a1) | Apr 07, 2020 |
| ASUSTek       | B85M-G                      | [c506d10d4d](https://linux-hardware.org/?probe=c506d10d4d) | Apr 07, 2020 |
| Dell          | 0WMJ54 A01                  | [915652c132](https://linux-hardware.org/?probe=915652c132) | Apr 07, 2020 |
| Gigabyte      | B450M S2H                   | [1d19709a92](https://linux-hardware.org/?probe=1d19709a92) | Apr 07, 2020 |
| HP            | 3048h                       | [e136ae12ae](https://linux-hardware.org/?probe=e136ae12ae) | Apr 04, 2020 |
| ASUSTek       | M4A78LT-M-LE                | [8620bfc9e4](https://linux-hardware.org/?probe=8620bfc9e4) | Apr 04, 2020 |
| ASUSTek       | B85M-G                      | [e397d91aee](https://linux-hardware.org/?probe=e397d91aee) | Apr 03, 2020 |
| ASUSTek       | P6X58D-E                    | [3defa9e6eb](https://linux-hardware.org/?probe=3defa9e6eb) | Mar 31, 2020 |
| Gigabyte      | AX370-Gaming 5              | [c854817725](https://linux-hardware.org/?probe=c854817725) | Mar 26, 2020 |
| ASUSTek       | P5KPL-C                     | [5baf2a0615](https://linux-hardware.org/?probe=5baf2a0615) | Mar 20, 2020 |
| ASRock        | FM2A88M Extreme4+           | [97c83d338f](https://linux-hardware.org/?probe=97c83d338f) | Mar 20, 2020 |
| Huanan        | X99-TF                      | [1238d1e4bd](https://linux-hardware.org/?probe=1238d1e4bd) | Mar 20, 2020 |
| Intel         | DH87RL AAG74240-402         | [fce111bb71](https://linux-hardware.org/?probe=fce111bb71) | Mar 19, 2020 |
| ASUSTek       | P5KPL-C                     | [d08bc065dd](https://linux-hardware.org/?probe=d08bc065dd) | Mar 19, 2020 |
| Gigabyte      | 945GCM-S2L                  | [8ffecb57de](https://linux-hardware.org/?probe=8ffecb57de) | Mar 13, 2020 |
| Gigabyte      | 945GCM-S2L                  | [83f0e4eb31](https://linux-hardware.org/?probe=83f0e4eb31) | Mar 13, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [d084073730](https://linux-hardware.org/?probe=d084073730) | Mar 10, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [cae9974b1f](https://linux-hardware.org/?probe=cae9974b1f) | Mar 10, 2020 |
| Gigabyte      | C1037UN-EU                  | [96c7fa2c31](https://linux-hardware.org/?probe=96c7fa2c31) | Mar 10, 2020 |
| ASUSTek       | M4A78 PRO                   | [6c44f6ec75](https://linux-hardware.org/?probe=6c44f6ec75) | Mar 09, 2020 |
| ASRock        | H61M-DGS                    | [007b26edd9](https://linux-hardware.org/?probe=007b26edd9) | Mar 09, 2020 |
| ASRock        | H61M-DGS                    | [96ac9746cc](https://linux-hardware.org/?probe=96ac9746cc) | Mar 09, 2020 |
| ASRock        | B450M Pro4                  | [a195b04c6f](https://linux-hardware.org/?probe=a195b04c6f) | Mar 06, 2020 |
| ASUSTek       | A55BM-A/USB3                | [b2b7d123b3](https://linux-hardware.org/?probe=b2b7d123b3) | Mar 06, 2020 |
| Gigabyte      | B360HD3PLM-CF               | [34c631206e](https://linux-hardware.org/?probe=34c631206e) | Mar 04, 2020 |
| ONDA          | A68V+                       | [9461b7acb7](https://linux-hardware.org/?probe=9461b7acb7) | Mar 04, 2020 |
| Quanta        | 2AF5 011                    | [7d17193eb2](https://linux-hardware.org/?probe=7d17193eb2) | Mar 02, 2020 |
| Quanta        | 2AF5 011                    | [c627d32a50](https://linux-hardware.org/?probe=c627d32a50) | Mar 02, 2020 |
| ASUSTek       | SABERTOOTH X79              | [b3b2e57a0c](https://linux-hardware.org/?probe=b3b2e57a0c) | Mar 02, 2020 |
| ASRock        | H81M-HDS                    | [1a513b0c25](https://linux-hardware.org/?probe=1a513b0c25) | Mar 01, 2020 |
| Dell          | 07PR60 A02                  | [15fdd27177](https://linux-hardware.org/?probe=15fdd27177) | Feb 29, 2020 |
| eMachines     | EL1852G                     | [6dc390f029](https://linux-hardware.org/?probe=6dc390f029) | Feb 28, 2020 |
| Intel         | DQ67OW AAG28716-306         | [07dc216d1d](https://linux-hardware.org/?probe=07dc216d1d) | Feb 28, 2020 |
| ASUSTek       | F2A85-M                     | [9f9146180c](https://linux-hardware.org/?probe=9f9146180c) | Feb 28, 2020 |
| ONDA          | A68V+                       | [302d697cc7](https://linux-hardware.org/?probe=302d697cc7) | Feb 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [54e8f78903](https://linux-hardware.org/?probe=54e8f78903) | Feb 27, 2020 |
| MSI           | Z97 PC Mate                 | [fdbae3b74b](https://linux-hardware.org/?probe=fdbae3b74b) | Feb 26, 2020 |
| ASUSTek       | P5P43TD                     | [6e8447b532](https://linux-hardware.org/?probe=6e8447b532) | Feb 26, 2020 |
| ASUSTek       | H81M-K                      | [6adb3339f8](https://linux-hardware.org/?probe=6adb3339f8) | Feb 26, 2020 |
| ASUSTek       | H81M-K                      | [fd72ac39b0](https://linux-hardware.org/?probe=fd72ac39b0) | Feb 26, 2020 |
| Gigabyte      | H310M S2H x.x               | [0d5a6662a3](https://linux-hardware.org/?probe=0d5a6662a3) | Feb 26, 2020 |
| ASRock        | B450M Pro4                  | [3bb0f856d1](https://linux-hardware.org/?probe=3bb0f856d1) | Feb 25, 2020 |
| ASUSTek       | P7H55D-M EVO                | [a98e2fc045](https://linux-hardware.org/?probe=a98e2fc045) | Feb 24, 2020 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0bb9d36743](https://linux-hardware.org/?probe=0bb9d36743) | Feb 19, 2020 |
| ASUSTek       | P5K                         | [b611ac37b9](https://linux-hardware.org/?probe=b611ac37b9) | Feb 16, 2020 |
| Dell          | 091WRN A00                  | [604d4514c7](https://linux-hardware.org/?probe=604d4514c7) | Feb 13, 2020 |
| Gigabyte      | H110M-DS2 DDR3-CF           | [e2a558c35b](https://linux-hardware.org/?probe=e2a558c35b) | Feb 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e027a09767](https://linux-hardware.org/?probe=e027a09767) | Feb 06, 2020 |
| Acer          | H81H3-AD V:1.0              | [1e00926631](https://linux-hardware.org/?probe=1e00926631) | Feb 04, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [05caf5a068](https://linux-hardware.org/?probe=05caf5a068) | Feb 02, 2020 |
| AZW           | AP35                        | [59c1ca6f4a](https://linux-hardware.org/?probe=59c1ca6f4a) | Feb 02, 2020 |
| Gigabyte      | Z97P-D3                     | [f151961dd1](https://linux-hardware.org/?probe=f151961dd1) | Feb 01, 2020 |
| Gigabyte      | MSH87TN-00                  | [2cbd2a678b](https://linux-hardware.org/?probe=2cbd2a678b) | Jan 31, 2020 |
| Hardkernel    | ODROID-H2                   | [1f57f70942](https://linux-hardware.org/?probe=1f57f70942) | Jan 29, 2020 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [77fb75b9cd](https://linux-hardware.org/?probe=77fb75b9cd) | Jan 29, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_10/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 4.19.0-14-amd64        | 54       | 6.27%   |
| 4.19.0-6-amd64         | 53       | 6.16%   |
| 4.19.0-16-amd64        | 52       | 6.04%   |
| 4.19.0-13-amd64        | 50       | 5.81%   |
| 4.19.0-9-amd64         | 48       | 5.57%   |
| 4.19.0-8-amd64         | 47       | 5.46%   |
| 4.19.0-17-amd64        | 47       | 5.46%   |
| 4.19.0-12-amd64        | 38       | 4.41%   |
| 4.19.0-10-amd64        | 34       | 3.95%   |
| 5.6.0-2-amd64          | 17       | 1.97%   |
| 4.19.0-5-amd64         | 16       | 1.86%   |
| 4.19.0-11-amd64        | 16       | 1.86%   |
| 5.10.0-0.bpo.3-amd64   | 13       | 1.51%   |
| 4.19.0-18-amd64        | 13       | 1.51%   |
| 5.10.0-0.bpo.5-amd64   | 11       | 1.28%   |
| 5.8.0-3-amd64          | 10       | 1.16%   |
| 5.8.0-0.bpo.2-amd64    | 10       | 1.16%   |
| 5.4.106-1-pve          | 10       | 1.16%   |
| 5.9.0-0.bpo.2-amd64    | 9        | 1.05%   |
| 5.7.0-0.bpo.2-amd64    | 9        | 1.05%   |
| 5.10.0-0.bpo.7-amd64   | 8        | 0.93%   |
| 4.19.0-20-amd64        | 8        | 0.93%   |
| 5.4.44-2-pve           | 7        | 0.81%   |
| 5.4.65-1-pve           | 6        | 0.7%    |
| 5.4.0-0.bpo.4-amd64    | 6        | 0.7%    |
| 5.10.0-5mx-amd64       | 6        | 0.7%    |
| 4.19.147-rivoreo-amd64 | 6        | 0.7%    |
| 4.19.0-22-amd64        | 6        | 0.7%    |
| 5.9.0-1-amd64          | 5        | 0.58%   |
| 5.8.0-2-amd64          | 5        | 0.58%   |
| 4.19.0-23-amd64        | 5        | 0.58%   |
| 4.19.0-21-amd64        | 5        | 0.58%   |
| 5.9.0-0.bpo.5-amd64    | 4        | 0.46%   |
| 5.6.0-1-amd64          | 4        | 0.46%   |
| 5.6.0-0.bpo.2-amd64    | 4        | 0.46%   |
| 5.5.0-0.bpo.2-amd64    | 4        | 0.46%   |
| 5.4.41-1-pve           | 4        | 0.46%   |
| 5.4.119-1-pve          | 4        | 0.46%   |
| 5.4.0-0.bpo.2-amd64    | 4        | 0.46%   |
| 5.10.0-0.bpo.9-amd64   | 4        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.0   | 503      | 61.95%  |
| 5.10.0   | 48       | 5.91%   |
| 5.8.0    | 28       | 3.45%   |
| 5.6.0    | 28       | 3.45%   |
| 5.9.0    | 23       | 2.83%   |
| 5.4.0    | 21       | 2.59%   |
| 5.7.0    | 17       | 2.09%   |
| 5.4.106  | 10       | 1.23%   |
| 5.3.0    | 10       | 1.23%   |
| 5.5.0    | 7        | 0.86%   |
| 5.4.44   | 7        | 0.86%   |
| 5.4.65   | 6        | 0.74%   |
| 4.19.147 | 6        | 0.74%   |
| 5.4.78   | 4        | 0.49%   |
| 5.4.41   | 4        | 0.49%   |
| 5.4.119  | 4        | 0.49%   |
| 5.2.0    | 4        | 0.49%   |
| 5.0.21   | 4        | 0.49%   |
| 4.9.0    | 4        | 0.49%   |
| 5.4.28   | 3        | 0.37%   |
| 5.4.114  | 3        | 0.37%   |
| 5.3.6    | 3        | 0.37%   |
| 5.3.13   | 3        | 0.37%   |
| 5.8.16   | 2        | 0.25%   |
| 5.6.10   | 2        | 0.25%   |
| 5.4.73   | 2        | 0.25%   |
| 5.4.60   | 2        | 0.25%   |
| 5.4.203  | 2        | 0.25%   |
| 5.4.128  | 2        | 0.25%   |
| 5.4.103  | 2        | 0.25%   |
| 5.3.18   | 2        | 0.25%   |
| 5.3.10   | 2        | 0.25%   |
| 5.17.0   | 2        | 0.25%   |
| 5.15.62  | 2        | 0.25%   |
| 5.11.22  | 2        | 0.25%   |
| 5.11.17  | 2        | 0.25%   |
| 6.7.0    | 1        | 0.12%   |
| 6.1.38   | 1        | 0.12%   |
| 5.9.8    | 1        | 0.12%   |
| 5.8.10   | 1        | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 511      | 63.56%  |
| 5.4     | 74       | 9.2%    |
| 5.10    | 52       | 6.47%   |
| 5.8     | 31       | 3.86%   |
| 5.6     | 31       | 3.86%   |
| 5.9     | 24       | 2.99%   |
| 5.3     | 22       | 2.74%   |
| 5.7     | 18       | 2.24%   |
| 5.5     | 8        | 1%      |
| 5.11    | 7        | 0.87%   |
| 5.0     | 6        | 0.75%   |
| 4.9     | 5        | 0.62%   |
| 5.2     | 4        | 0.5%    |
| 5.15    | 3        | 0.37%   |
| 5.17    | 2        | 0.25%   |
| 6.7     | 1        | 0.12%   |
| 6.1     | 1        | 0.12%   |
| 5.14    | 1        | 0.12%   |
| 5.12    | 1        | 0.12%   |
| 5.1     | 1        | 0.12%   |
| 4.20    | 1        | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 735      | 95.83%  |
| i686    | 24       | 3.13%   |
| armv7l  | 4        | 0.52%   |
| aarch64 | 2        | 0.26%   |
| mips64  | 1        | 0.13%   |
| i586    | 1        | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 239      | 30.37%  |
| GNOME            | 144      | 18.3%   |
| XFCE             | 127      | 16.14%  |
| KDE              | 65       | 8.26%   |
| KDE5             | 61       | 7.75%   |
| MATE             | 41       | 5.21%   |
| X-Cinnamon       | 26       | 3.3%    |
| Cinnamon         | 22       | 2.8%    |
| LXDE             | 18       | 2.29%   |
| LXQt             | 12       | 1.52%   |
| Openbox          | 7        | 0.89%   |
| GNOME Flashback  | 6        | 0.76%   |
| GNOME Classic    | 6        | 0.76%   |
| fluxbox          | 4        | 0.51%   |
| lightdm-xsession | 3        | 0.38%   |
| i3               | 3        | 0.38%   |
| trinity          | 1        | 0.13%   |
| i3-with-shmlog   | 1        | 0.13%   |
| Budgie           | 1        | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 511      | 65.35%  |
| Tty     | 136      | 17.39%  |
| Unknown | 78       | 9.97%   |
| Wayland | 57       | 7.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 471      | 60.54%  |
| TDM     | 89       | 11.44%  |
| GDM     | 79       | 10.15%  |
| SDDM    | 67       | 8.61%   |
| LightDM | 54       | 6.94%   |
| GDM3    | 8        | 1.03%   |
| XDM     | 3        | 0.39%   |
| SLiM    | 2        | 0.26%   |
| NODM    | 2        | 0.26%   |
| WDM     | 1        | 0.13%   |
| Ly      | 1        | 0.13%   |
| KDM     | 1        | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 288      | 36.97%  |
| Unknown | 98       | 12.58%  |
| de_DE   | 53       | 6.8%    |
| fr_FR   | 45       | 5.78%   |
| ru_RU   | 43       | 5.52%   |
| pt_BR   | 40       | 5.13%   |
| en_GB   | 40       | 5.13%   |
| es_ES   | 25       | 3.21%   |
| it_IT   | 21       | 2.7%    |
| en_CA   | 13       | 1.67%   |
| C       | 11       | 1.41%   |
| en_AU   | 10       | 1.28%   |
| en_IN   | 9        | 1.16%   |
| pl_PL   | 8        | 1.03%   |
| en_IE   | 7        | 0.9%    |
| zh_CN   | 4        | 0.51%   |
| pt_PT   | 4        | 0.51%   |
| hu_HU   | 4        | 0.51%   |
| de_AT   | 4        | 0.51%   |
| sv_SE   | 3        | 0.39%   |
| ru_UA   | 3        | 0.39%   |
| nl_NL   | 3        | 0.39%   |
| en_DK   | 3        | 0.39%   |
| zh_TW   | 2        | 0.26%   |
| tt_RU   | 2        | 0.26%   |
| nl_BE   | 2        | 0.26%   |
| ja_JP   | 2        | 0.26%   |
| eu_ES   | 2        | 0.26%   |
| es_AR   | 2        | 0.26%   |
| de_CH   | 2        | 0.26%   |
| cs_CZ   | 2        | 0.26%   |
| uk_UA   | 1        | 0.13%   |
| sr_RS   | 1        | 0.13%   |
| sk_SK   | 1        | 0.13%   |
| ro_RO   | 1        | 0.13%   |
| lt_LT   | 1        | 0.13%   |
| ko_KR   | 1        | 0.13%   |
| hr_HR   | 1        | 0.13%   |
| he_IL   | 1        | 0.13%   |
| fr_CH   | 1        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 559      | 72.13%  |
| EFI  | 216      | 27.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 637      | 82.09%  |
| Btrfs   | 35       | 4.51%   |
| Unknown | 29       | 3.74%   |
| Zfs     | 28       | 3.61%   |
| Xfs     | 16       | 2.06%   |
| Overlay | 13       | 1.68%   |
| Tmpfs   | 6        | 0.77%   |
| Ext2    | 5        | 0.64%   |
| Ext3    | 4        | 0.52%   |
| Rootfs  | 1        | 0.13%   |
| F2fs    | 1        | 0.13%   |
| Aufs    | 1        | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 318      | 40.56%  |
| GPT     | 296      | 37.76%  |
| MBR     | 170      | 21.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 611      | 78.74%  |
| Yes       | 165      | 21.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 591      | 76.26%  |
| Yes       | 184      | 23.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 203      | 26.47%  |
| Gigabyte Technology | 119      | 15.51%  |
| ASRock              | 86       | 11.21%  |
| Dell                | 64       | 8.34%   |
| MSI                 | 57       | 7.43%   |
| Hewlett-Packard     | 45       | 5.87%   |
| Lenovo              | 32       | 4.17%   |
| Intel               | 28       | 3.65%   |
| Unknown             | 17       | 2.22%   |
| Supermicro          | 15       | 1.96%   |
| Acer                | 10       | 1.3%    |
| AZW                 | 7        | 0.91%   |
| Fujitsu             | 6        | 0.78%   |
| ASRockRack          | 6        | 0.78%   |
| Pegatron            | 5        | 0.65%   |
| Foxconn             | 5        | 0.65%   |
| Positivo            | 4        | 0.52%   |
| Fujitsu Siemens     | 4        | 0.52%   |
| Shuttle             | 3        | 0.39%   |
| ECS                 | 3        | 0.39%   |
| Biostar             | 3        | 0.39%   |
| Apple               | 3        | 0.39%   |
| YANYU               | 2        | 0.26%   |
| Wistron             | 2        | 0.26%   |
| PCWare              | 2        | 0.26%   |
| Medion              | 2        | 0.26%   |
| Intel X79           | 2        | 0.26%   |
| IBM                 | 2        | 0.26%   |
| Huanan              | 2        | 0.26%   |
| Hardkernel          | 2        | 0.26%   |
| Google              | 2        | 0.26%   |
| Alienware           | 2        | 0.26%   |
| Wincor Nixdorf      | 1        | 0.13%   |
| TYAN Computer       | 1        | 0.13%   |
| SolidRun            | 1        | 0.13%   |
| SixForOne           | 1        | 0.13%   |
| retsamarret         | 1        | 0.13%   |
| Quanta              | 1        | 0.13%   |
| Qbex                | 1        | 0.13%   |
| Packard Bell        | 1        | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 26       | 3.39%   |
| Unknown                          | 21       | 2.74%   |
| Dell OptiPlex 7010               | 6        | 0.78%   |
| Dell OptiPlex 3010               | 5        | 0.65%   |
| AZW AP35                         | 5        | 0.65%   |
| ASUS PRIME X370-PRO              | 5        | 0.65%   |
| ASRock B450M Pro4                | 5        | 0.65%   |
| Gigabyte X470 AORUS ULTRA GAMING | 4        | 0.52%   |
| Gigabyte B450M DS3H              | 4        | 0.52%   |
| ASUS TUF Gaming X570-PLUS        | 4        | 0.52%   |
| ASUS M5A97 R2.0                  | 4        | 0.52%   |
| ASUS M5A78L-M/USB3               | 4        | 0.52%   |
| Supermicro SYS-5039MC-H8TRF      | 3        | 0.39%   |
| MSI MS-7B79                      | 3        | 0.39%   |
| Gigabyte F2A88XM-D3H             | 3        | 0.39%   |
| Dell OptiPlex 760                | 3        | 0.39%   |
| Dell OptiPlex 3020               | 3        | 0.39%   |
| Dell Inspiron 5675               | 3        | 0.39%   |
| ASUS PRIME B450-PLUS             | 3        | 0.39%   |
| ASUS PRIME A320M-K               | 3        | 0.39%   |
| ASUS P5K                         | 3        | 0.39%   |
| ASUS M5A78L-M LX/BR              | 3        | 0.39%   |
| ASRock J4105-ITX                 | 3        | 0.39%   |
| ASRock FM2A88M Extreme4+         | 3        | 0.39%   |
| ASRock B450 Pro4                 | 3        | 0.39%   |
| ASRock A300M-STX                 | 3        | 0.39%   |
| Wistron ProLiant ML110 G6        | 2        | 0.26%   |
| Supermicro X9SCL/X9SCM           | 2        | 0.26%   |
| Supermicro X8STi                 | 2        | 0.26%   |
| Supermicro SYS-530MT-H8TNR       | 2        | 0.26%   |
| Shuttle XH61V                    | 2        | 0.26%   |
| MSI MS-7C75                      | 2        | 0.26%   |
| MSI MS-7C37                      | 2        | 0.26%   |
| MSI MS-7B85                      | 2        | 0.26%   |
| MSI MS-7A34                      | 2        | 0.26%   |
| MSI MS-7926                      | 2        | 0.26%   |
| MSI MS-7850                      | 2        | 0.26%   |
| MSI MS-7758                      | 2        | 0.26%   |
| MSI MS-7721                      | 2        | 0.26%   |
| MSI MS-7693                      | 2        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS PRIME                  | 39       | 5.08%   |
| Dell OptiPlex               | 38       | 4.95%   |
| ASUS All                    | 26       | 3.39%   |
| Unknown                     | 21       | 2.74%   |
| Lenovo ThinkCentre          | 14       | 1.83%   |
| ASUS ROG                    | 14       | 1.83%   |
| HP Compaq                   | 13       | 1.69%   |
| ASUS TUF                    | 12       | 1.56%   |
| Dell Precision              | 9        | 1.17%   |
| ASUS M5A78L-M               | 9        | 1.17%   |
| ASRock B450M                | 8        | 1.04%   |
| Lenovo IdeaCentre           | 7        | 0.91%   |
| Acer Aspire                 | 7        | 0.91%   |
| Lenovo ThinkStation         | 6        | 0.78%   |
| HP EliteDesk                | 6        | 0.78%   |
| Gigabyte B450M              | 6        | 0.78%   |
| Dell Inspiron               | 6        | 0.78%   |
| Gigabyte X470               | 5        | 0.65%   |
| AZW AP35                    | 5        | 0.65%   |
| ASRock B450                 | 5        | 0.65%   |
| HP t620                     | 4        | 0.52%   |
| HP ProLiant                 | 4        | 0.52%   |
| HP ProDesk                  | 4        | 0.52%   |
| Gigabyte B450               | 4        | 0.52%   |
| Fujitsu Siemens ESPRIMO     | 4        | 0.52%   |
| Dell Vostro                 | 4        | 0.52%   |
| ASUS Rampage                | 4        | 0.52%   |
| ASUS P9X79                  | 4        | 0.52%   |
| ASUS M5A97                  | 4        | 0.52%   |
| ASRock X570                 | 4        | 0.52%   |
| ASRock X370                 | 4        | 0.52%   |
| Supermicro SYS-5039MC-H8TRF | 3        | 0.39%   |
| MSI MS-7B79                 | 3        | 0.39%   |
| Gigabyte Z390               | 3        | 0.39%   |
| Gigabyte X570               | 3        | 0.39%   |
| Gigabyte GA-78LMT-USB3      | 3        | 0.39%   |
| Gigabyte F2A88XM-D3H        | 3        | 0.39%   |
| ASUS P8Z68-V                | 3        | 0.39%   |
| ASUS P8H61-M                | 3        | 0.39%   |
| ASUS P5K                    | 3        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 84       | 10.95%  |
| 2019    | 80       | 10.43%  |
| 2012    | 80       | 10.43%  |
| 2011    | 69       | 9%      |
| 2013    | 68       | 8.87%   |
| 2017    | 51       | 6.65%   |
| 2014    | 46       | 6%      |
| 2015    | 44       | 5.74%   |
| 2009    | 41       | 5.35%   |
| 2010    | 38       | 4.95%   |
| 2020    | 34       | 4.43%   |
| 2008    | 32       | 4.17%   |
| 2016    | 27       | 3.52%   |
| 2007    | 27       | 3.52%   |
| 2006    | 14       | 1.83%   |
| 2021    | 9        | 1.17%   |
| 2022    | 8        | 1.04%   |
| Unknown | 7        | 0.91%   |
| 2005    | 5        | 0.65%   |
| 2004    | 2        | 0.26%   |
| 2023    | 1        | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 767      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 760      | 98.96%  |
| Enabled  | 8        | 1.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 764      | 99.61%  |
| Yes  | 3        | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 174      | 22.37%  |
| 8.01-16.0       | 156      | 20.05%  |
| 3.01-4.0        | 130      | 16.71%  |
| 32.01-64.0      | 101      | 12.98%  |
| 4.01-8.0        | 79       | 10.15%  |
| 64.01-256.0     | 57       | 7.33%   |
| 24.01-32.0      | 24       | 3.08%   |
| 1.01-2.0        | 22       | 2.83%   |
| 2.01-3.0        | 13       | 1.67%   |
| Unknown         | 8        | 1.03%   |
| 0.51-1.0        | 7        | 0.9%    |
| 0.01-0.5        | 4        | 0.51%   |
| More than 256.0 | 3        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 207      | 24.53%  |
| 2.01-3.0    | 169      | 20.02%  |
| 4.01-8.0    | 135      | 16%     |
| 3.01-4.0    | 96       | 11.37%  |
| 8.01-16.0   | 75       | 8.89%   |
| 0.51-1.0    | 74       | 8.77%   |
| 0.01-0.5    | 38       | 4.5%    |
| 16.01-24.0  | 22       | 2.61%   |
| 32.01-64.0  | 12       | 1.42%   |
| Unknown     | 8        | 0.95%   |
| 24.01-32.0  | 6        | 0.71%   |
| 64.01-256.0 | 2        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 257      | 32.7%   |
| 2       | 224      | 28.5%   |
| 3       | 115      | 14.63%  |
| 4       | 84       | 10.69%  |
| 5       | 43       | 5.47%   |
| 6       | 24       | 3.05%   |
| 7       | 15       | 1.91%   |
| 0       | 6        | 0.76%   |
| 9       | 5        | 0.64%   |
| 8       | 5        | 0.64%   |
| 17      | 1        | 0.13%   |
| 16      | 1        | 0.13%   |
| 14      | 1        | 0.13%   |
| 13      | 1        | 0.13%   |
| 12      | 1        | 0.13%   |
| 11      | 1        | 0.13%   |
| 10      | 1        | 0.13%   |
| Unknown | 1        | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 448      | 58.03%  |
| Yes       | 324      | 41.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 760      | 99.09%  |
| No        | 7        | 0.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 514      | 66.49%  |
| Yes       | 259      | 33.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 581      | 74.87%  |
| Yes       | 195      | 25.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 114      | 14.84%  |
| Russia       | 88       | 11.46%  |
| Germany      | 78       | 10.16%  |
| Brazil       | 61       | 7.94%   |
| France       | 58       | 7.55%   |
| Spain        | 44       | 5.73%   |
| Italy        | 33       | 4.3%    |
| UK           | 25       | 3.26%   |
| Netherlands  | 20       | 2.6%    |
| Canada       | 18       | 2.34%   |
| Australia    | 14       | 1.82%   |
| Poland       | 13       | 1.69%   |
| Hungary      | 12       | 1.56%   |
| Ukraine      | 11       | 1.43%   |
| Switzerland  | 11       | 1.43%   |
| India        | 11       | 1.43%   |
| China        | 11       | 1.43%   |
| Austria      | 11       | 1.43%   |
| Sweden       | 9        | 1.17%   |
| Finland      | 7        | 0.91%   |
| Belgium      | 7        | 0.91%   |
| Turkey       | 6        | 0.78%   |
| Pakistan     | 6        | 0.78%   |
| Romania      | 5        | 0.65%   |
| New Zealand  | 5        | 0.65%   |
| Czechia      | 5        | 0.65%   |
| Saudi Arabia | 4        | 0.52%   |
| Portugal     | 4        | 0.52%   |
| Norway       | 4        | 0.52%   |
| Croatia      | 4        | 0.52%   |
| Belarus      | 4        | 0.52%   |
| Vietnam      | 3        | 0.39%   |
| Venezuela    | 3        | 0.39%   |
| Slovakia     | 3        | 0.39%   |
| Serbia       | 3        | 0.39%   |
| Mexico       | 3        | 0.39%   |
| Denmark      | 3        | 0.39%   |
| Cyprus       | 3        | 0.39%   |
| UAE          | 2        | 0.26%   |
| Taiwan       | 2        | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| St Petersburg  | 21       | 2.63%   |
| Moscow         | 19       | 2.38%   |
| Sao Paulo      | 14       | 1.75%   |
| Paris          | 11       | 1.38%   |
| Amsterdam      | 10       | 1.25%   |
| Madrid         | 7        | 0.88%   |
| Yekaterinburg  | 6        | 0.75%   |
| Vienna         | 6        | 0.75%   |
| Perm           | 6        | 0.75%   |
| Budapest       | 6        | 0.75%   |
| Berlin         | 6        | 0.75%   |
| Sydney         | 5        | 0.63%   |
| Seville        | 5        | 0.63%   |
| Lahore         | 5        | 0.63%   |
| Kyiv           | 5        | 0.63%   |
| Voronezh       | 4        | 0.5%    |
| Porto Alegre   | 4        | 0.5%    |
| New York       | 4        | 0.5%    |
| Naples         | 4        | 0.5%    |
| Nanhao         | 4        | 0.5%    |
| Minsk          | 4        | 0.5%    |
| Milan          | 4        | 0.5%    |
| Hamburg        | 4        | 0.5%    |
| Falkenstein    | 4        | 0.5%    |
| Dallas         | 4        | 0.5%    |
| Brasília      | 4        | 0.5%    |
| Bieligutai     | 4        | 0.5%    |
| Auckland       | 4        | 0.5%    |
| Szeged         | 3        | 0.38%   |
| Roubaix        | 3        | 0.38%   |
| Rostov-on-Don  | 3        | 0.38%   |
| Riyadh         | 3        | 0.38%   |
| Rio de Janeiro | 3        | 0.38%   |
| Nuremberg      | 3        | 0.38%   |
| Nicosia        | 3        | 0.38%   |
| Munich         | 3        | 0.38%   |
| Mason          | 3        | 0.38%   |
| Koprivnica     | 3        | 0.38%   |
| Karlsruhe      | 3        | 0.38%   |
| Helsinki       | 3        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 301      | 556    | 20.39%  |
| Seagate             | 279      | 490    | 18.9%   |
| Samsung Electronics | 201      | 317    | 13.62%  |
| Toshiba             | 96       | 174    | 6.5%    |
| Kingston            | 85       | 116    | 5.76%   |
| Crucial             | 77       | 108    | 5.22%   |
| Hitachi             | 52       | 87     | 3.52%   |
| SanDisk             | 45       | 69     | 3.05%   |
| Unknown             | 28       | 42     | 1.9%    |
| A-DATA Technology   | 28       | 38     | 1.9%    |
| HGST                | 26       | 46     | 1.76%   |
| Intel               | 23       | 33     | 1.56%   |
| Maxtor              | 16       | 19     | 1.08%   |
| OCZ                 | 15       | 18     | 1.02%   |
| China               | 15       | 16     | 1.02%   |
| Phison              | 14       | 23     | 0.95%   |
| Corsair             | 11       | 12     | 0.75%   |
| Transcend           | 10       | 12     | 0.68%   |
| Hewlett-Packard     | 10       | 17     | 0.68%   |
| SPCC                | 7        | 7      | 0.47%   |
| Patriot             | 7        | 9      | 0.47%   |
| KingDian            | 6        | 7      | 0.41%   |
| Intenso             | 6        | 8      | 0.41%   |
| GOODRAM             | 5        | 5      | 0.34%   |
| ASMT                | 5        | 8      | 0.34%   |
| SK hynix            | 4        | 4      | 0.27%   |
| Silicon Motion      | 4        | 5      | 0.27%   |
| Plextor             | 4        | 6      | 0.27%   |
| Micron Technology   | 4        | 5      | 0.27%   |
| LITEON              | 4        | 5      | 0.27%   |
| PNY                 | 3        | 5      | 0.2%    |
| LITEONIT            | 3        | 3      | 0.2%    |
| Lite-On             | 3        | 3      | 0.2%    |
| Lexar               | 3        | 3      | 0.2%    |
| LaCie               | 3        | 3      | 0.2%    |
| Hajaan              | 3        | 3      | 0.2%    |
| Gigabyte Technology | 3        | 6      | 0.2%    |
| Zheino              | 2        | 4      | 0.14%   |
| TO Exter            | 2        | 2      | 0.14%   |
| Team                | 2        | 3      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 20       | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB   | 20       | 1.13%   |
| Kingston SA400S37240G 240GB SSD  | 16       | 0.91%   |
| Samsung SSD 850 EVO 250GB        | 15       | 0.85%   |
| Crucial CT500MX500SSD1 500GB     | 15       | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 12       | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB   | 12       | 0.68%   |
| Kingston SV300S37A120G 120GB SSD | 12       | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB   | 11       | 0.62%   |
| Samsung SSD 860 EVO 500GB        | 11       | 0.62%   |
| Samsung SSD 860 EVO 1TB          | 11       | 0.62%   |
| Samsung SSD 850 EVO 500GB        | 11       | 0.62%   |
| Kingston SA400S37120G 120GB SSD  | 11       | 0.62%   |
| Toshiba HDWD120 2TB              | 10       | 0.57%   |
| Toshiba DT01ACA100 1TB           | 10       | 0.57%   |
| Toshiba DT01ACA050 500GB         | 10       | 0.57%   |
| Seagate ST2000DM006-2DM164 2TB   | 10       | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB   | 10       | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB         | 9        | 0.51%   |
| Toshiba HDWD110 1TB              | 9        | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB   | 9        | 0.51%   |
| Kingston SA400S37480G 480GB SSD  | 9        | 0.51%   |
| Crucial CT250MX500SSD1 250GB     | 9        | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB         | 8        | 0.45%   |
| Toshiba DT01ACA200 2TB           | 8        | 0.45%   |
| Seagate ST4000VN008-2DR166 4TB   | 8        | 0.45%   |
| Seagate ST4000DM000-1F2168 4TB   | 8        | 0.45%   |
| Seagate ST31000528AS 1TB         | 8        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB   | 8        | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB         | 7        | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB         | 7        | 0.4%    |
| WDC WD1002FAEX-00Z3A0 1TB        | 7        | 0.4%    |
| Seagate ST3500418AS 500GB        | 7        | 0.4%    |
| Seagate Expansion Desk 5TB       | 7        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB     | 7        | 0.4%    |
| Samsung SSD 850 PRO 256GB        | 7        | 0.4%    |
| Kingston SUV400S37240G 240GB SSD | 7        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB      | 7        | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 6        | 0.34%   |
| WDC WD20EARX-00PASB0 2TB         | 6        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 273      | 481    | 34%     |
| WDC                 | 271      | 507    | 33.75%  |
| Toshiba             | 82       | 149    | 10.21%  |
| Hitachi             | 52       | 87     | 6.48%   |
| Samsung Electronics | 46       | 65     | 5.73%   |
| HGST                | 26       | 46     | 3.24%   |
| Maxtor              | 16       | 19     | 1.99%   |
| ASMT                | 5        | 8      | 0.62%   |
| Unknown             | 4        | 5      | 0.5%    |
| Hewlett-Packard     | 4        | 8      | 0.5%    |
| TO Exter            | 2        | 2      | 0.25%   |
| SABRENT             | 2        | 3      | 0.25%   |
| JMicron Technology  | 2        | 2      | 0.25%   |
| HPE                 | 2        | 2      | 0.25%   |
| Fujitsu             | 2        | 2      | 0.25%   |
| ASMedia             | 2        | 2      | 0.25%   |
| USB 3.0             | 1        | 2      | 0.12%   |
| Unknown (CF)        | 1        | 1      | 0.12%   |
| Quantum             | 1        | 1      | 0.12%   |
| Pear 2TB            | 1        | 1      | 0.12%   |
| LIO-ORG             | 1        | 8      | 0.12%   |
| LaCie               | 1        | 1      | 0.12%   |
| Intenso             | 1        | 1      | 0.12%   |
| Innodisk            | 1        | 1      | 0.12%   |
| Inateck             | 1        | 1      | 0.12%   |
| ExcelStor           | 1        | 1      | 0.12%   |
| DAS                 | 1        | 1      | 0.12%   |
| Apple               | 1        | 2      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 111      | 155    | 21.68%  |
| Kingston            | 79       | 104    | 15.43%  |
| Crucial             | 70       | 99     | 13.67%  |
| SanDisk             | 35       | 54     | 6.84%   |
| WDC                 | 34       | 39     | 6.64%   |
| A-DATA Technology   | 23       | 33     | 4.49%   |
| Intel               | 16       | 22     | 3.13%   |
| OCZ                 | 15       | 18     | 2.93%   |
| China               | 15       | 16     | 2.93%   |
| Toshiba             | 11       | 15     | 2.15%   |
| Transcend           | 10       | 12     | 1.95%   |
| Patriot             | 6        | 8      | 1.17%   |
| Corsair             | 6        | 6      | 1.17%   |
| SPCC                | 5        | 5      | 0.98%   |
| KingDian            | 5        | 6      | 0.98%   |
| Intenso             | 5        | 7      | 0.98%   |
| GOODRAM             | 4        | 4      | 0.78%   |
| SK hynix            | 3        | 3      | 0.59%   |
| Seagate             | 3        | 3      | 0.59%   |
| PNY                 | 3        | 5      | 0.59%   |
| Plextor             | 3        | 5      | 0.59%   |
| LITEONIT            | 3        | 3      | 0.59%   |
| Hajaan              | 3        | 3      | 0.59%   |
| Zheino              | 2        | 4      | 0.39%   |
| Micron Technology   | 2        | 3      | 0.39%   |
| LITEON              | 2        | 3      | 0.39%   |
| Lexar               | 2        | 2      | 0.39%   |
| Hewlett-Packard     | 2        | 2      | 0.39%   |
| Gigabyte Technology | 2        | 4      | 0.39%   |
| ZHITAI              | 1        | 1      | 0.2%    |
| Verbatim            | 1        | 4      | 0.2%    |
| Vaseky              | 1        | 1      | 0.2%    |
| VALK                | 1        | 1      | 0.2%    |
| Unknown             | 1        | 1      | 0.2%    |
| ULTIMATE            | 1        | 2      | 0.2%    |
| THU                 | 1        | 2      | 0.2%    |
| Team                | 1        | 2      | 0.2%    |
| TCSUNBOW            | 1        | 1      | 0.2%    |
| Pear                | 1        | 1      | 0.2%    |
| OCZ-VERTEX3         | 1        | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 584      | 1409   | 49.08%  |
| SSD     | 419      | 684    | 35.21%  |
| NVMe    | 156      | 237    | 13.11%  |
| Unknown | 19       | 34     | 1.6%    |
| MMC     | 12       | 16     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 722      | 2017   | 76.08%  |
| NVMe | 156      | 237    | 16.44%  |
| SAS  | 59       | 110    | 6.22%   |
| MMC  | 12       | 16     | 1.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 550      | 981    | 48.46%  |
| 0.51-1.0   | 286      | 477    | 25.2%   |
| 1.01-2.0   | 136      | 251    | 11.98%  |
| 3.01-4.0   | 67       | 163    | 5.9%    |
| 4.01-10.0  | 46       | 115    | 4.05%   |
| 2.01-3.0   | 43       | 91     | 3.79%   |
| 10.01-20.0 | 7        | 15     | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 155      | 19.38%  |
| 251-500        | 123      | 15.38%  |
| More than 3000 | 101      | 12.63%  |
| 501-1000       | 101      | 12.63%  |
| 1001-2000      | 90       | 11.25%  |
| Unknown        | 75       | 9.38%   |
| 51-100         | 61       | 7.63%   |
| 2001-3000      | 43       | 5.38%   |
| 21-50          | 27       | 3.38%   |
| 1-20           | 24       | 3%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 210      | 25.52%  |
| 101-250        | 102      | 12.39%  |
| 21-50          | 85       | 10.33%  |
| 51-100         | 76       | 9.23%   |
| Unknown        | 75       | 9.11%   |
| 251-500        | 73       | 8.87%   |
| 501-1000       | 71       | 8.63%   |
| 1001-2000      | 65       | 7.9%    |
| More than 3000 | 46       | 5.59%   |
| 2001-3000      | 20       | 2.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD10EADS-00M2B0 1TB           | 4        | 4      | 2.45%   |
| WDC WD20EFRX-68EUZN0 2TB          | 3        | 9      | 1.84%   |
| Samsung Electronics HD103UJ 1TB   | 3        | 4      | 1.84%   |
| A-DATA Technology SU800 256GB SSD | 3        | 4      | 1.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 2      | 1.23%   |
| WDC WD5000AAKX-003CA0 500GB       | 2        | 2      | 1.23%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 1.23%   |
| Seagate ST4000DM000-1F2168 4TB    | 2        | 2      | 1.23%   |
| Seagate ST3500418AS 500GB         | 2        | 4      | 1.23%   |
| Seagate ST3250410AS 250GB         | 2        | 2      | 1.23%   |
| Seagate ST31000528AS 1TB          | 2        | 3      | 1.23%   |
| Seagate ST2000DM008-2FR1 2TB      | 2        | 2      | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 3      | 1.23%   |
| Samsung Electronics HD753LJ 752GB | 2        | 3      | 1.23%   |
| Samsung Electronics HD154UI 1TB   | 2        | 3      | 1.23%   |
| Maxtor STM3250310AS 250GB         | 2        | 2      | 1.23%   |
| Kingston SH103S3120G 120GB SSD    | 2        | 2      | 1.23%   |
| Hitachi HDS721050CLA660 500GB     | 2        | 2      | 1.23%   |
| WDC WD7500AACS-65D6B0 752GB       | 1        | 1      | 0.61%   |
| WDC WD7500AACS-00ZJB0 752GB       | 1        | 1      | 0.61%   |
| WDC WD5002ABYS-02B1B0 500GB       | 1        | 1      | 0.61%   |
| WDC WD5001FZWX-00ZHUA0 5TB        | 1        | 4      | 0.61%   |
| WDC WD5000HHTZ-04N21V0 500GB      | 1        | 1      | 0.61%   |
| WDC WD5000AAKX-00U6AA0 500GB      | 1        | 1      | 0.61%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 0.61%   |
| WDC WD5000AAKS-08V0A0 500GB       | 1        | 1      | 0.61%   |
| WDC WD5000AAJS-22A8B0 500GB       | 1        | 1      | 0.61%   |
| WDC WD40EZRX-00SPEB0 4TB          | 1        | 1      | 0.61%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1        | 2      | 0.61%   |
| WDC WD3200AVJS-63B6A0 320GB       | 1        | 1      | 0.61%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 0.61%   |
| WDC WD30EFRX-68AX9N0 3TB          | 1        | 1      | 0.61%   |
| WDC WD2500JD-00HBC0 250GB         | 1        | 1      | 0.61%   |
| WDC WD2500AAKX-60U6AA0 250GB      | 1        | 1      | 0.61%   |
| WDC WD2500AAKX-001CA0 250GB       | 1        | 1      | 0.61%   |
| WDC WD2500AAJS-00V4A0 250GB       | 1        | 1      | 0.61%   |
| WDC WD2500AAJS-00L7A0 250GB       | 1        | 1      | 0.61%   |
| WDC WD2002FAEX-007BA0 2TB         | 1        | 2      | 0.61%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 1      | 0.61%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 56     | 28.03%  |
| WDC                 | 36       | 50     | 22.93%  |
| Samsung Electronics | 21       | 26     | 13.38%  |
| Hitachi             | 10       | 11     | 6.37%   |
| Crucial             | 7        | 7      | 4.46%   |
| Toshiba             | 6        | 8      | 3.82%   |
| Maxtor              | 6        | 6      | 3.82%   |
| Kingston            | 4        | 4      | 2.55%   |
| Intel               | 4        | 4      | 2.55%   |
| SanDisk             | 3        | 6      | 1.91%   |
| OCZ                 | 3        | 4      | 1.91%   |
| A-DATA Technology   | 3        | 4      | 1.91%   |
| KingDian            | 2        | 2      | 1.27%   |
| Plextor             | 1        | 2      | 0.64%   |
| LITEONIT            | 1        | 1      | 0.64%   |
| LITEON              | 1        | 1      | 0.64%   |
| Hypertec            | 1        | 1      | 0.64%   |
| HP Phison           | 1        | 1      | 0.64%   |
| HGST                | 1        | 1      | 0.64%   |
| Corsair             | 1        | 1      | 0.64%   |
| ASMT                | 1        | 2      | 0.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 56     | 37.29%  |
| WDC                 | 34       | 48     | 28.81%  |
| Samsung Electronics | 16       | 21     | 13.56%  |
| Hitachi             | 10       | 11     | 8.47%   |
| Toshiba             | 6        | 8      | 5.08%   |
| Maxtor              | 6        | 6      | 5.08%   |
| HGST                | 1        | 1      | 0.85%   |
| ASMT                | 1        | 2      | 0.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 108      | 153    | 73.47%  |
| SSD  | 36       | 42     | 24.49%  |
| NVMe | 3        | 3      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 25%     |
| Seagate ST1000NM0011 1TB        | 1        | 1      | 25%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 25%     |
| Crucial CT1000P1SSD8 1TB        | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 50%     |
| Samsung Electronics | 1        | 1      | 25%     |
| Crucial             | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 418      | 1158   | 44.75%  |
| Detected | 373      | 1020   | 39.94%  |
| Malfunc  | 139      | 198    | 14.88%  |
| Failed   | 4        | 4      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 499      | 47.03%  |
| AMD                           | 230      | 21.68%  |
| Samsung Electronics           | 62       | 5.84%   |
| ASMedia Technology            | 47       | 4.43%   |
| Marvell Technology Group      | 38       | 3.58%   |
| JMicron Technology            | 27       | 2.54%   |
| Phison Electronics            | 23       | 2.17%   |
| Nvidia                        | 22       | 2.07%   |
| SanDisk                       | 17       | 1.6%    |
| LSI Logic / Symbios Logic     | 13       | 1.23%   |
| Silicon Motion                | 11       | 1.04%   |
| Micron/Crucial Technology     | 10       | 0.94%   |
| Kingston Technology Company   | 9        | 0.85%   |
| Broadcom / LSI                | 8        | 0.75%   |
| ADATA Technology              | 8        | 0.75%   |
| VIA Technologies              | 6        | 0.57%   |
| Silicon Image                 | 5        | 0.47%   |
| Lite-On Technology            | 5        | 0.47%   |
| Toshiba America Info Systems  | 4        | 0.38%   |
| Adaptec                       | 4        | 0.38%   |
| Seagate Technology            | 3        | 0.28%   |
| Realtek Semiconductor         | 2        | 0.19%   |
| Micron Technology             | 2        | 0.19%   |
| Toshiba                       | 1        | 0.09%   |
| SK hynix                      | 1        | 0.09%   |
| Netac Technology              | 1        | 0.09%   |
| Loongson Technology           | 1        | 0.09%   |
| KIOXIA                        | 1        | 0.09%   |
| Integrated Technology Express | 1        | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 152      | 11.05%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 60       | 4.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 56       | 4.07%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 43       | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 42       | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 42       | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 39       | 2.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 35       | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34       | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 32       | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 31       | 2.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 30       | 2.18%   |
| Intel SATA Controller [RAID mode]                                                       | 29       | 2.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 29       | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 25       | 1.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22       | 1.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 19       | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17       | 1.24%   |
| AMD X370 Series Chipset SATA Controller                                                 | 17       | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 16       | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 15       | 1.09%   |
| Phison E12 NVMe Controller                                                              | 14       | 1.02%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 14       | 1.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 14       | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 12       | 0.87%   |
| AMD FCH IDE Controller                                                                  | 12       | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 11       | 0.8%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 11       | 0.8%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 11       | 0.8%    |
| Nvidia MCP61 SATA Controller                                                            | 10       | 0.73%   |
| Nvidia MCP61 IDE                                                                        | 10       | 0.73%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 10       | 0.73%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 10       | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9        | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 8        | 0.58%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 8        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 8        | 0.58%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 607      | 58.09%  |
| IDE  | 213      | 20.38%  |
| NVMe | 155      | 14.83%  |
| RAID | 45       | 4.31%   |
| SAS  | 19       | 1.82%   |
| SCSI | 6        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 508      | 66.23%  |
| AMD                   | 251      | 32.72%  |
| ARM                   | 4        | 0.52%   |
| Unknown               | 2        | 0.26%   |
| Marvell Semiconductor | 1        | 0.13%   |
| CentaurHauls          | 1        | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 14       | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 14       | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 13       | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 12       | 1.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11       | 1.43%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 11       | 1.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 10       | 1.3%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 9        | 1.17%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 8        | 1.04%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 8        | 1.04%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 8        | 1.04%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 7        | 0.91%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 7        | 0.91%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 7        | 0.91%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 7        | 0.91%   |
| AMD FX-8350 Eight-Core Processor              | 7        | 0.91%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 6        | 0.78%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 6        | 0.78%   |
| Intel Core i7-3930K CPU @ 3.20GHz             | 6        | 0.78%   |
| Intel Celeron CPU J3355 @ 2.00GHz             | 6        | 0.78%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 6        | 0.78%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 5        | 0.65%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 5        | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 5        | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5        | 0.65%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 5        | 0.65%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 5        | 0.65%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 5        | 0.65%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 5        | 0.65%   |
| AMD FX-8320 Eight-Core Processor              | 5        | 0.65%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 5        | 0.65%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 4        | 0.52%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 4        | 0.52%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 4        | 0.52%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4        | 0.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4        | 0.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 4        | 0.52%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 4        | 0.52%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 4        | 0.52%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 4        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 109      | 14.17%  |
| Intel Core i7           | 105      | 13.65%  |
| Intel Core i3           | 64       | 8.32%   |
| Intel Xeon              | 62       | 8.06%   |
| AMD Ryzen 5             | 55       | 7.15%   |
| AMD Ryzen 7             | 48       | 6.24%   |
| Intel Celeron           | 46       | 5.98%   |
| Intel Core 2 Duo        | 30       | 3.9%    |
| AMD FX                  | 26       | 3.38%   |
| Intel Core 2 Quad       | 20       | 2.6%    |
| Intel Pentium           | 19       | 2.47%   |
| Other                   | 15       | 1.95%   |
| AMD Athlon II X2        | 11       | 1.43%   |
| Intel Core 2            | 10       | 1.3%    |
| AMD Ryzen 3             | 10       | 1.3%    |
| AMD Phenom II X4        | 10       | 1.3%    |
| AMD A8                  | 10       | 1.3%    |
| Intel Atom              | 9        | 1.17%   |
| AMD Ryzen 9             | 9        | 1.17%   |
| AMD A10                 | 9        | 1.17%   |
| AMD Athlon 64 X2        | 7        | 0.91%   |
| Intel Pentium Dual-Core | 6        | 0.78%   |
| Intel Pentium Gold      | 5        | 0.65%   |
| Intel Pentium Dual      | 5        | 0.65%   |
| Intel Pentium 4         | 5        | 0.65%   |
| Intel Core i9           | 5        | 0.65%   |
| AMD Ryzen Threadripper  | 5        | 0.65%   |
| AMD Phenom II X6        | 5        | 0.65%   |
| AMD Athlon II X4        | 5        | 0.65%   |
| AMD Athlon 64           | 5        | 0.65%   |
| AMD Sempron             | 4        | 0.52%   |
| AMD GX                  | 4        | 0.52%   |
| AMD E                   | 4        | 0.52%   |
| AMD Athlon              | 4        | 0.52%   |
| AMD E1                  | 3        | 0.39%   |
| Intel Pentium D         | 2        | 0.26%   |
| AMD Ryzen 5 PRO         | 2        | 0.26%   |
| AMD Phenom              | 2        | 0.26%   |
| AMD Athlon X4           | 2        | 0.26%   |
| AMD A6                  | 2        | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 305      | 39.61%  |
| 2      | 227      | 29.48%  |
| 6      | 89       | 11.56%  |
| 8      | 76       | 9.87%   |
| 1      | 32       | 4.16%   |
| 12     | 16       | 2.08%   |
| 3      | 8        | 1.04%   |
| 16     | 7        | 0.91%   |
| 10     | 3        | 0.39%   |
| 24     | 2        | 0.26%   |
| 64     | 1        | 0.13%   |
| 44     | 1        | 0.13%   |
| 32     | 1        | 0.13%   |
| 22     | 1        | 0.13%   |
| 18     | 1        | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 750      | 97.78%  |
| 2      | 16       | 2.09%   |
| 16     | 1        | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 410      | 53.39%  |
| 1      | 358      | 46.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 735      | 95.58%  |
| Unknown        | 27       | 3.51%   |
| 32-bit         | 7        | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 298      | 37.72%  |
| 0x306c3    | 51       | 6.46%   |
| 0x206a7    | 38       | 4.81%   |
| 0x306a9    | 30       | 3.8%    |
| 0x1067a    | 25       | 3.16%   |
| 0x08701021 | 19       | 2.41%   |
| 0x0800820d | 16       | 2.03%   |
| 0x906e9    | 14       | 1.77%   |
| 0x506e3    | 13       | 1.65%   |
| 0x08701013 | 13       | 1.65%   |
| 0x906ed    | 11       | 1.39%   |
| 0x906ea    | 11       | 1.39%   |
| 0x010000c8 | 11       | 1.39%   |
| 0x08108109 | 9        | 1.14%   |
| 0x306e4    | 8        | 1.01%   |
| 0x206d7    | 8        | 1.01%   |
| 0xa0653    | 7        | 0.89%   |
| 0x106e5    | 7        | 0.89%   |
| 0x08001137 | 7        | 0.89%   |
| 0x06003106 | 7        | 0.89%   |
| 0x06001119 | 7        | 0.89%   |
| 0xa0655    | 6        | 0.76%   |
| 0x706a1    | 6        | 0.76%   |
| 0x406c3    | 6        | 0.76%   |
| 0x306f2    | 6        | 0.76%   |
| 0x906eb    | 5        | 0.63%   |
| 0x6fd      | 5        | 0.63%   |
| 0x6fb      | 5        | 0.63%   |
| 0x6f6      | 5        | 0.63%   |
| 0x106a5    | 5        | 0.63%   |
| 0x0800820b | 5        | 0.63%   |
| 0xa0671    | 4        | 0.51%   |
| 0x206c2    | 4        | 0.51%   |
| 0x20652    | 4        | 0.51%   |
| 0x106c2    | 4        | 0.51%   |
| 0x10676    | 4        | 0.51%   |
| 0x08101016 | 4        | 0.51%   |
| 0x08001138 | 4        | 0.51%   |
| 0x06000852 | 4        | 0.51%   |
| 0x0600081c | 4        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 95       | 12.35%  |
| SandyBridge      | 69       | 8.97%   |
| KabyLake         | 62       | 8.06%   |
| IvyBridge        | 56       | 7.28%   |
| Zen+             | 50       | 6.5%    |
| Penryn           | 50       | 6.5%    |
| Zen 2            | 45       | 5.85%   |
| Zen              | 36       | 4.68%   |
| K10              | 35       | 4.55%   |
| Skylake          | 34       | 4.42%   |
| Core             | 33       | 4.29%   |
| Piledriver       | 31       | 4.03%   |
| Silvermont       | 17       | 2.21%   |
| Nehalem          | 17       | 2.21%   |
| K8 Hammer        | 17       | 2.21%   |
| CometLake        | 15       | 1.95%   |
| Westmere         | 14       | 1.82%   |
| Unknown          | 12       | 1.56%   |
| Steamroller      | 10       | 1.3%    |
| NetBurst         | 9        | 1.17%   |
| Goldmont plus    | 9        | 1.17%   |
| Bonnell          | 8        | 1.04%   |
| Goldmont         | 7        | 0.91%   |
| Bulldozer        | 6        | 0.78%   |
| Broadwell        | 6        | 0.78%   |
| Bobcat           | 6        | 0.78%   |
| Jaguar           | 5        | 0.65%   |
| Excavator        | 4        | 0.52%   |
| Zen 3            | 3        | 0.39%   |
| K10 Llano        | 2        | 0.26%   |
| Alderlake Hybrid | 2        | 0.26%   |
| Tremont          | 1        | 0.13%   |
| K6               | 1        | 0.13%   |
| Icelake          | 1        | 0.13%   |
| Geode            | 1        | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 290      | 36.66%  |
| Intel                      | 270      | 34.13%  |
| AMD                        | 198      | 25.03%  |
| ASPEED Technology          | 15       | 1.9%    |
| Matrox Electronics Systems | 14       | 1.77%   |
| VIA Technologies           | 3        | 0.38%   |
| Loongson Technology        | 1        | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38       | 4.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 30       | 3.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25       | 3.06%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 22       | 2.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20       | 2.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18       | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17       | 2.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 16       | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15       | 1.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15       | 1.83%   |
| Intel HD Graphics 530                                                                    | 15       | 1.83%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 15       | 1.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 14       | 1.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 12       | 1.47%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 12       | 1.47%   |
| Intel HD Graphics 630                                                                    | 10       | 1.22%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 9        | 1.1%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 1.1%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 9        | 1.1%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 8        | 0.98%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 8        | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8        | 0.98%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 8        | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8        | 0.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8        | 0.98%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7        | 0.86%   |
| Intel HD Graphics 500                                                                    | 7        | 0.86%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 6        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6        | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 6        | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 6        | 0.73%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 6        | 0.73%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 5        | 0.61%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 5        | 0.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5        | 0.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 269      | 34.84%  |
| 1 x Intel               | 242      | 31.35%  |
| 1 x AMD                 | 177      | 22.93%  |
| 1 x Matrox              | 14       | 1.81%   |
| 1 x ASPEED              | 14       | 1.81%   |
| Other                   | 13       | 1.68%   |
| 2 x AMD                 | 13       | 1.68%   |
| Intel + Nvidia          | 12       | 1.55%   |
| 2 x Nvidia              | 5        | 0.65%   |
| Intel + AMD             | 5        | 0.65%   |
| 1 x VIA                 | 3        | 0.39%   |
| AMD + Nvidia            | 3        | 0.39%   |
| 2 x Loongson Technology | 1        | 0.13%   |
| Nvidia + ASPEED         | 1        | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 528      | 67.87%  |
| Proprietary | 175      | 22.49%  |
| Unknown     | 75       | 9.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 442      | 56.52%  |
| 0.51-1.0   | 89       | 11.38%  |
| 1.01-2.0   | 79       | 10.1%   |
| 0.01-0.5   | 53       | 6.78%   |
| 3.01-4.0   | 46       | 5.88%   |
| 7.01-8.0   | 32       | 4.09%   |
| 5.01-6.0   | 19       | 2.43%   |
| 2.01-3.0   | 15       | 1.92%   |
| 8.01-16.0  | 7        | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 126      | 17.36%  |
| Dell                 | 85       | 11.71%  |
| Goldstar             | 66       | 9.09%   |
| BenQ                 | 51       | 7.02%   |
| Hewlett-Packard      | 45       | 6.2%    |
| Acer                 | 42       | 5.79%   |
| Philips              | 40       | 5.51%   |
| AOC                  | 35       | 4.82%   |
| Ancor Communications | 28       | 3.86%   |
| ViewSonic            | 21       | 2.89%   |
| Iiyama               | 20       | 2.75%   |
| Unknown              | 17       | 2.34%   |
| LG Electronics       | 16       | 2.2%    |
| Fujitsu Siemens      | 9        | 1.24%   |
| Lenovo               | 7        | 0.96%   |
| HannStar             | 6        | 0.83%   |
| Sony                 | 5        | 0.69%   |
| NEC Computers        | 5        | 0.69%   |
| Apple                | 5        | 0.69%   |
| Medion               | 4        | 0.55%   |
| HPN                  | 4        | 0.55%   |
| Eizo                 | 4        | 0.55%   |
| Belinea              | 4        | 0.55%   |
| Vizio                | 3        | 0.41%   |
| Targa Visionary      | 3        | 0.41%   |
| ASUSTek Computer     | 3        | 0.41%   |
| Sun                  | 2        | 0.28%   |
| SNC                  | 2        | 0.28%   |
| Sharp                | 2        | 0.28%   |
| Panasonic            | 2        | 0.28%   |
| Orion                | 2        | 0.28%   |
| ONN                  | 2        | 0.28%   |
| MStar                | 2        | 0.28%   |
| ITE                  | 2        | 0.28%   |
| Idek Iiyama          | 2        | 0.28%   |
| Hannspree            | 2        | 0.28%   |
| Gateway              | 2        | 0.28%   |
| CHR                  | 2        | 0.28%   |
| BOE                  | 2        | 0.28%   |
| AUS                  | 2        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch             | 6        | 0.77%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 5        | 0.64%   |
| Fujitsu Siemens LL 3190T FUS07A3 1366x768 430x255mm 19.7-inch        | 5        | 0.64%   |
| AOC 2350 AOC2350 1920x1080 509x286mm 23.0-inch                       | 5        | 0.64%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                    | 4        | 0.51%   |
| Targa Visionary LCD Monitor TAR0C35 1280x1024 380x300mm 19.1-inch    | 3        | 0.38%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 3        | 0.38%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 3        | 0.38%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 546x352mm 25.6-inch          | 3        | 0.38%   |
| HannStar HannsG HS191D HSD0013 1280x1024 376x301mm 19.0-inch         | 3        | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 3        | 0.38%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 3        | 0.38%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 3        | 0.38%   |
| BenQ GL2706PQ BNQ78E0 2560x1440 597x336mm 27.0-inch                  | 3        | 0.38%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch     | 3        | 0.38%   |
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                  | 2        | 0.26%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 2        | 0.26%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch        | 2        | 0.26%   |
| ViewSonic VA2216w-2 VSC2920 1680x1050 495x291mm 22.6-inch            | 2        | 0.26%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 2        | 0.26%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 2        | 0.26%   |
| Samsung Electronics T24D391 SAM0DAF 1920x1080 520x290mm 23.4-inch    | 2        | 0.26%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch | 2        | 0.26%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 2        | 0.26%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 2        | 0.26%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2        | 0.26%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch   | 2        | 0.26%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch    | 2        | 0.26%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 2        | 0.26%   |
| Samsung Electronics LCD Monitor SyncMaster 1440x900                  | 2        | 0.26%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 2        | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 2        | 0.26%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 521x293mm 23.5-inch              | 2        | 0.26%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2        | 0.26%   |
| Philips PH107C/F/H/T6 PHLE01C 1280x960 306x230mm 15.1-inch           | 2        | 0.26%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                   | 2        | 0.26%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2        | 0.26%   |
| Orion ORION ORN1209 1920x540                                         | 2        | 0.26%   |
| LG Electronics LCD Monitor LG TV                                     | 2        | 0.26%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                      | 2        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 295      | 40.52%  |
| 1280x1024 (SXGA)   | 72       | 9.89%   |
| 3840x2160 (4K)     | 49       | 6.73%   |
| 1680x1050 (WSXGA+) | 48       | 6.59%   |
| 1920x1200 (WUXGA)  | 34       | 4.67%   |
| 1366x768 (WXGA)    | 34       | 4.67%   |
| 2560x1440 (QHD)    | 33       | 4.53%   |
| Unknown            | 32       | 4.4%    |
| 1600x900 (HD+)     | 22       | 3.02%   |
| 1440x900 (WXGA+)   | 20       | 2.75%   |
| 3440x1440          | 11       | 1.51%   |
| 2560x1080          | 11       | 1.51%   |
| 3840x1080          | 10       | 1.37%   |
| 1024x768 (XGA)     | 10       | 1.37%   |
| 1360x768           | 9        | 1.24%   |
| 3200x1080          | 4        | 0.55%   |
| 2560x1600          | 4        | 0.55%   |
| 1600x1200          | 4        | 0.55%   |
| 1280x720 (HD)      | 4        | 0.55%   |
| 5760x2160          | 3        | 0.41%   |
| 1920x540           | 3        | 0.41%   |
| 4480x1440          | 2        | 0.27%   |
| 7680x2160          | 1        | 0.14%   |
| 7680x1440          | 1        | 0.14%   |
| 5760x1200          | 1        | 0.14%   |
| 5120x1200          | 1        | 0.14%   |
| 4880x1080          | 1        | 0.14%   |
| 4160x1440          | 1        | 0.14%   |
| 4093x4093          | 1        | 0.14%   |
| 3640x1920          | 1        | 0.14%   |
| 3600x1080          | 1        | 0.14%   |
| 3200x900           | 1        | 0.14%   |
| 2880x1200          | 1        | 0.14%   |
| 2560x1024          | 1        | 0.14%   |
| 2048x1536          | 1        | 0.14%   |
| 2048x1152          | 1        | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 114      | 15.92%  |
| 24      | 93       | 12.99%  |
| 23      | 83       | 11.59%  |
| 21      | 70       | 9.78%   |
| 27      | 68       | 9.5%    |
| 19      | 59       | 8.24%   |
| 22      | 30       | 4.19%   |
| 17      | 28       | 3.91%   |
| 20      | 24       | 3.35%   |
| 18      | 24       | 3.35%   |
| 15      | 20       | 2.79%   |
| 34      | 16       | 2.23%   |
| 31      | 16       | 2.23%   |
| 84      | 12       | 1.68%   |
| 25      | 7        | 0.98%   |
| 72      | 6        | 0.84%   |
| 29      | 6        | 0.84%   |
| 26      | 6        | 0.84%   |
| 40      | 5        | 0.7%    |
| 16      | 4        | 0.56%   |
| 52      | 3        | 0.42%   |
| 32      | 3        | 0.42%   |
| 65      | 2        | 0.28%   |
| 54      | 2        | 0.28%   |
| 38      | 2        | 0.28%   |
| 12      | 2        | 0.28%   |
| 58      | 1        | 0.14%   |
| 49      | 1        | 0.14%   |
| 48      | 1        | 0.14%   |
| 46      | 1        | 0.14%   |
| 43      | 1        | 0.14%   |
| 42      | 1        | 0.14%   |
| 35      | 1        | 0.14%   |
| 30      | 1        | 0.14%   |
| 28      | 1        | 0.14%   |
| 14      | 1        | 0.14%   |
| 13      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 235      | 33.81%  |
| 401-500     | 161      | 23.17%  |
| Unknown     | 114      | 16.4%   |
| 301-350     | 48       | 6.91%   |
| 351-400     | 43       | 6.19%   |
| 601-700     | 32       | 4.6%    |
| 701-800     | 19       | 2.73%   |
| 1501-2000   | 18       | 2.59%   |
| 1001-1500   | 11       | 1.58%   |
| 801-900     | 8        | 1.15%   |
| 201-300     | 4        | 0.58%   |
| 901-1000    | 2        | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 364      | 54.01%  |
| Unknown | 102      | 15.13%  |
| 16/10   | 96       | 14.24%  |
| 5/4     | 65       | 9.64%   |
| 4/3     | 21       | 3.12%   |
| 21/9    | 18       | 2.67%   |
| 3/2     | 4        | 0.59%   |
| 6/5     | 3        | 0.45%   |
| 1.96    | 1        | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 223      | 31.72%  |
| Unknown        | 114      | 16.22%  |
| 151-200        | 97       | 13.8%   |
| 301-350        | 71       | 10.1%   |
| 141-150        | 46       | 6.54%   |
| 351-500        | 42       | 5.97%   |
| 251-300        | 42       | 5.97%   |
| More than 1000 | 28       | 3.98%   |
| 101-110        | 17       | 2.42%   |
| 501-1000       | 10       | 1.42%   |
| 111-120        | 4        | 0.57%   |
| 131-140        | 3        | 0.43%   |
| 121-130        | 3        | 0.43%   |
| 71-80          | 2        | 0.28%   |
| 81-90          | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 402      | 59.73%  |
| Unknown       | 114      | 16.94%  |
| 101-120       | 104      | 15.45%  |
| 1-50          | 22       | 3.27%   |
| 121-160       | 20       | 2.97%   |
| 161-240       | 10       | 1.49%   |
| More than 240 | 1        | 0.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 508      | 65.55%  |
| 0     | 135      | 17.42%  |
| 2     | 121      | 15.61%  |
| 3     | 11       | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 442      | 41.66%  |
| Intel                                  | 324      | 30.54%  |
| Qualcomm Atheros                       | 76       | 7.16%   |
| Broadcom                               | 34       | 3.2%    |
| Ralink Technology                      | 26       | 2.45%   |
| Nvidia                                 | 18       | 1.7%    |
| Ralink                                 | 11       | 1.04%   |
| Marvell Technology Group               | 11       | 1.04%   |
| TP-Link                                | 10       | 0.94%   |
| Broadcom Limited                       | 6        | 0.57%   |
| ASIX Electronics                       | 6        | 0.57%   |
| Huawei Technologies                    | 5        | 0.47%   |
| D-Link System                          | 5        | 0.47%   |
| ASUSTek Computer                       | 5        | 0.47%   |
| Aquantia                               | 5        | 0.47%   |
| VIA Technologies                       | 4        | 0.38%   |
| Sundance Technology Inc / IC Plus      | 4        | 0.38%   |
| Samsung Electronics                    | 3        | 0.28%   |
| Microsoft                              | 3        | 0.28%   |
| Edimax Technology                      | 3        | 0.28%   |
| D-Link                                 | 3        | 0.28%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.19%   |
| NetGear                                | 2        | 0.19%   |
| Mellanox Technologies                  | 2        | 0.19%   |
| MediaTek                               | 2        | 0.19%   |
| Linksys                                | 2        | 0.19%   |
| Insyde Software                        | 2        | 0.19%   |
| Gemtek                                 | 2        | 0.19%   |
| American Megatrends                    | 2        | 0.19%   |
| ZyDAS                                  | 1        | 0.09%   |
| ZEPHYR                                 | 1        | 0.09%   |
| YiHiEcigar                             | 1        | 0.09%   |
| Xilinx                                 | 1        | 0.09%   |
| Xiaomi                                 | 1        | 0.09%   |
| Wilocity                               | 1        | 0.09%   |
| TRENDnet                               | 1        | 0.09%   |
| Texas Instruments                      | 1        | 0.09%   |
| SysKonnect                             | 1        | 0.09%   |
| Spreadtrum Communications              | 1        | 0.09%   |
| Solarflare Communications              | 1        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 379      | 31.77%  |
| Intel I211 Gigabit Network Connection                                  | 54       | 4.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 33       | 2.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 28       | 2.35%   |
| Intel 82579V Gigabit Network Connection                                | 22       | 1.84%   |
| Intel 82574L Gigabit Network Connection                                | 22       | 1.84%   |
| Intel Wi-Fi 6 AX200                                                    | 15       | 1.26%   |
| Intel Ethernet Connection (2) I218-V                                   | 14       | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13       | 1.09%   |
| Ralink MT7601U Wireless Adapter                                        | 13       | 1.09%   |
| Intel I210 Gigabit Network Connection                                  | 13       | 1.09%   |
| Intel Ethernet Connection I217-V                                       | 13       | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 13       | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12       | 1.01%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 12       | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                   | 12       | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 12       | 1.01%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 12       | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 11       | 0.92%   |
| Intel I350 Gigabit Network Connection                                  | 11       | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 10       | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9        | 0.75%   |
| Nvidia MCP61 Ethernet                                                  | 9        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8        | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8        | 0.67%   |
| Intel Wireless 3165                                                    | 8        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7        | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6        | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 6        | 0.5%    |
| Intel Wireless 7260                                                    | 6        | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 5        | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5        | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 5        | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5        | 0.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 5        | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 0.34%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 4        | 0.34%   |
| Realtek 802.11ac NIC                                                   | 4        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 74       | 27.72%  |
| Realtek Semiconductor                 | 62       | 23.22%  |
| Qualcomm Atheros                      | 46       | 17.23%  |
| Ralink Technology                     | 26       | 9.74%   |
| Broadcom                              | 12       | 4.49%   |
| Ralink                                | 11       | 4.12%   |
| TP-Link                               | 8        | 3%      |
| ASUSTek Computer                      | 5        | 1.87%   |
| Edimax Technology                     | 3        | 1.12%   |
| D-Link                                | 3        | 1.12%   |
| NetGear                               | 2        | 0.75%   |
| Microsoft                             | 2        | 0.75%   |
| Linksys                               | 2        | 0.75%   |
| Gemtek                                | 2        | 0.75%   |
| D-Link System                         | 2        | 0.75%   |
| ZyDAS                                 | 1        | 0.37%   |
| Wilocity                              | 1        | 0.37%   |
| TRENDnet                              | 1        | 0.37%   |
| Qualcomm Atheros Communications       | 1        | 0.37%   |
| Marvell Technology Group              | 1        | 0.37%   |
| IMC Networks                          | 1        | 0.37%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 15       | 5.54%   |
| Ralink MT7601U Wireless Adapter                                     | 13       | 4.8%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]             | 12       | 4.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 12       | 4.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 9        | 3.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 8        | 2.95%   |
| Intel Wireless 3165                                                 | 8        | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 7        | 2.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 6        | 2.21%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 6        | 2.21%   |
| Intel Wireless 7260                                                 | 6        | 2.21%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 5        | 1.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 5        | 1.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 5        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 5        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 4        | 1.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 4        | 1.48%   |
| Realtek 802.11ac NIC                                                | 4        | 1.48%   |
| Ralink RT5370 Wireless Adapter                                      | 4        | 1.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 3        | 1.11%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller           | 3        | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3        | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 3        | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 3        | 1.11%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 3        | 1.11%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter        | 3        | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                       | 3        | 1.11%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 2        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.74%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 2        | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2        | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 2        | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 0.74%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 2        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 0.74%   |
| Realtek RTL8187 Wireless Adapter                                    | 2        | 0.74%   |
| Ralink RT2501/RT2573 Wireless Adapter                               | 2        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 417      | 48.83%  |
| Intel                                  | 290      | 33.96%  |
| Qualcomm Atheros                       | 32       | 3.75%   |
| Broadcom                               | 22       | 2.58%   |
| Nvidia                                 | 18       | 2.11%   |
| Marvell Technology Group               | 10       | 1.17%   |
| Broadcom Limited                       | 6        | 0.7%    |
| ASIX Electronics                       | 6        | 0.7%    |
| Huawei Technologies                    | 5        | 0.59%   |
| Aquantia                               | 5        | 0.59%   |
| VIA Technologies                       | 4        | 0.47%   |
| Sundance Technology Inc / IC Plus      | 4        | 0.47%   |
| D-Link System                          | 3        | 0.35%   |
| TP-Link                                | 2        | 0.23%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.23%   |
| Samsung Electronics                    | 2        | 0.23%   |
| Mellanox Technologies                  | 2        | 0.23%   |
| MediaTek                               | 2        | 0.23%   |
| Insyde Software                        | 2        | 0.23%   |
| American Megatrends                    | 2        | 0.23%   |
| Xiaomi                                 | 1        | 0.12%   |
| SysKonnect                             | 1        | 0.12%   |
| Spreadtrum Communications              | 1        | 0.12%   |
| Solarflare Communications              | 1        | 0.12%   |
| Qualcomm                               | 1        | 0.12%   |
| QLogic                                 | 1        | 0.12%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.12%   |
| Motorola PCS                           | 1        | 0.12%   |
| Microsoft                              | 1        | 0.12%   |
| Linux 3.4.39 with sunxi_usb_udc        | 1        | 0.12%   |
| Lenovo                                 | 1        | 0.12%   |
| JMicron Technology                     | 1        | 0.12%   |
| HTC (High Tech Computer)               | 1        | 0.12%   |
| GCT Semiconductor                      | 1        | 0.12%   |
| Emulex                                 | 1        | 0.12%   |
| Apple                                  | 1        | 0.12%   |
| Altair Semiconductor                   | 1        | 0.12%   |
| 3Com                                   | 1        | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 379      | 41.97%  |
| Intel I211 Gigabit Network Connection                                          | 54       | 5.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 33       | 3.65%   |
| Intel Ethernet Connection (2) I219-V                                           | 28       | 3.1%    |
| Intel 82579V Gigabit Network Connection                                        | 22       | 2.44%   |
| Intel 82574L Gigabit Network Connection                                        | 22       | 2.44%   |
| Intel Ethernet Connection (2) I218-V                                           | 14       | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                              | 13       | 1.44%   |
| Intel I210 Gigabit Network Connection                                          | 13       | 1.44%   |
| Intel Ethernet Connection I217-V                                               | 13       | 1.44%   |
| Intel Ethernet Connection I217-LM                                              | 13       | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12       | 1.33%   |
| Intel Ethernet Connection (7) I219-V                                           | 12       | 1.33%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 12       | 1.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 11       | 1.22%   |
| Intel I350 Gigabit Network Connection                                          | 11       | 1.22%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 10       | 1.11%   |
| Nvidia MCP61 Ethernet                                                          | 9        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8        | 0.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 5        | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4        | 0.44%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 4        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4        | 0.44%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 4        | 0.44%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 4        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3        | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 3        | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3        | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3        | 0.33%   |
| Nvidia MCP77 Ethernet                                                          | 3        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 0.33%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 0.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 3        | 0.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 3        | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3        | 0.33%   |
| Intel 82566DM Gigabit Network Connection                                       | 3        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 760      | 73.5%   |
| WiFi     | 257      | 24.85%  |
| Modem    | 14       | 1.35%   |
| Unknown  | 3        | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 657      | 84.99%  |
| WiFi     | 116      | 15.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 470      | 61.04%  |
| 2     | 228      | 29.61%  |
| 3     | 42       | 5.45%   |
| 4     | 16       | 2.08%   |
| 0     | 8        | 1.04%   |
| 6     | 3        | 0.39%   |
| 5     | 2        | 0.26%   |
| 21    | 1        | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 711      | 91.27%  |
| Yes  | 68       | 8.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 67       | 33.5%   |
| Cambridge Silicon Radio         | 48       | 24%     |
| ASUSTek Computer                | 26       | 13%     |
| Realtek Semiconductor           | 18       | 9%      |
| Qualcomm Atheros Communications | 15       | 7.5%    |
| Broadcom                        | 15       | 7.5%    |
| IMC Networks                    | 2        | 1%      |
| Belkin Components               | 2        | 1%      |
| Apple                           | 2        | 1%      |
| TP-Link                         | 1        | 0.5%    |
| Kensington                      | 1        | 0.5%    |
| Integrated System Solution      | 1        | 0.5%    |
| Foxconn / Hon Hai               | 1        | 0.5%    |
| Com One                         | 1        | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 48       | 24%     |
| Intel Bluetooth wireless interface                    | 18       | 9%      |
| Intel AX200 Bluetooth                                 | 15       | 7.5%    |
| Realtek Bluetooth Radio                               | 14       | 7%      |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 13       | 6.5%    |
| Intel Wireless-AC 3168 Bluetooth                      | 11       | 5.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 7        | 3.5%    |
| ASUS Bluetooth Adapter                                | 7        | 3.5%    |
| Qualcomm Atheros  Bluetooth Device                    | 6        | 3%      |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 6        | 3%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5        | 2.5%    |
| ASUS BCM20702A0                                       | 4        | 2%      |
| Realtek RTL8821A Bluetooth                            | 3        | 1.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3        | 1.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 2        | 1%      |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)       | 2        | 1%      |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 1%      |
| Intel AX211 Bluetooth                                 | 2        | 1%      |
| Intel AX201 Bluetooth                                 | 2        | 1%      |
| IMC Networks Bluetooth Device                         | 2        | 1%      |
| Broadcom Bluetooth 2.0+eDR dongle                     | 2        | 1%      |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 1%      |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 1%      |
| ASUS Bluetooth Radio                                  | 2        | 1%      |
| ASUS Bluetooth Device                                 | 2        | 1%      |
| Apple Bluetooth HCI                                   | 2        | 1%      |
| TP-Link TP-Link Bluetooth USB Adapter                 | 1        | 0.5%    |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.5%    |
| Kensington Bluetooth EDR Dongle                       | 1        | 0.5%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.5%    |
| Integrated System Solution Bluetooth Device           | 1        | 0.5%    |
| Foxconn / Hon Hai Acer Bluetooth module               | 1        | 0.5%    |
| Com One Bluetooth Device                              | 1        | 0.5%    |
| Broadcom HP Portable Bumble Bee                       | 1        | 0.5%    |
| Broadcom Bluetooth 3.0 Dongle                         | 1        | 0.5%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 0.5%    |
| Belkin Components F8T012 Bluetooth Adapter            | 1        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 449      | 40.16%  |
| AMD                                             | 279      | 24.96%  |
| Nvidia                                          | 266      | 23.79%  |
| C-Media Electronics                             | 18       | 1.61%   |
| Creative Labs                                   | 14       | 1.25%   |
| Logitech                                        | 10       | 0.89%   |
| Kingston Technology                             | 6        | 0.54%   |
| GN Netcom                                       | 5        | 0.45%   |
| Dell                                            | 5        | 0.45%   |
| Creative Technology                             | 5        | 0.45%   |
| VIA Technologies                                | 4        | 0.36%   |
| Plantronics                                     | 4        | 0.36%   |
| JMTek                                           | 4        | 0.36%   |
| Samsung Electronics                             | 3        | 0.27%   |
| Generalplus Technology                          | 3        | 0.27%   |
| Corsair                                         | 3        | 0.27%   |
| Texas Instruments                               | 2        | 0.18%   |
| Musical Fidelity                                | 2        | 0.18%   |
| Microsoft                                       | 2        | 0.18%   |
| Micro Star International                        | 2        | 0.18%   |
| DSEA A/S                                        | 2        | 0.18%   |
| BEHRINGER International                         | 2        | 0.18%   |
| Astro Gaming                                    | 2        | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.09%   |
| Yamaha                                          | 1        | 0.09%   |
| XMOS                                            | 1        | 0.09%   |
| Tenx Technology                                 | 1        | 0.09%   |
| SteelSeries ApS                                 | 1        | 0.09%   |
| Shure                                           | 1        | 0.09%   |
| Shenzhen Riitek Technology                      | 1        | 0.09%   |
| Samson Technologies                             | 1        | 0.09%   |
| RODE Microphones                                | 1        | 0.09%   |
| Quanta                                          | 1        | 0.09%   |
| Numark                                          | 1        | 0.09%   |
| Native Instruments                              | 1        | 0.09%   |
| Loongson Technology                             | 1        | 0.09%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.09%   |
| Lenovo                                          | 1        | 0.09%   |
| Giga-Byte Technology                            | 1        | 0.09%   |
| Focusrite-Novation                              | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 58       | 4.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 58       | 4.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 53       | 4.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 53       | 4.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 49       | 3.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 47       | 3.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 39       | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 35       | 2.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 33       | 2.53%   |
| Intel 200 Series PCH HD Audio                                                     | 32       | 2.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 31       | 2.38%   |
| AMD FCH Azalia Controller                                                         | 28       | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 27       | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 26       | 2%      |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 26       | 2%      |
| Nvidia High Definition Audio Controller                                           | 24       | 1.84%   |
| Nvidia GP106 High Definition Audio Controller                                     | 22       | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 20       | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 20       | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 19       | 1.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 18       | 1.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 17       | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 16       | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 16       | 1.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 15       | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                                | 14       | 1.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 14       | 1.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 14       | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 13       | 1%      |
| Nvidia GF108 High Definition Audio Controller                                     | 13       | 1%      |
| Intel C610/X99 series chipset HD Audio Controller                                 | 12       | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                     | 11       | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                                     | 11       | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                                     | 11       | 0.84%   |
| Nvidia MCP61 High Definition Audio                                                | 10       | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 10       | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 10       | 0.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 10       | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                     | 9        | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                                | 9        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 129      | 22.67%  |
| Unknown             | 115      | 20.21%  |
| Samsung Electronics | 62       | 10.9%   |
| Corsair             | 52       | 9.14%   |
| Crucial             | 49       | 8.61%   |
| SK hynix            | 43       | 7.56%   |
| G.Skill             | 41       | 7.21%   |
| Micron Technology   | 17       | 2.99%   |
| Transcend           | 7        | 1.23%   |
| Unknown (ABCD)      | 6        | 1.05%   |
| A-DATA Technology   | 6        | 1.05%   |
| Patriot             | 4        | 0.7%    |
| Elpida              | 4        | 0.7%    |
| Ramaxel Technology  | 3        | 0.53%   |
| Nanya Technology    | 3        | 0.53%   |
| AMD                 | 3        | 0.53%   |
| Team                | 2        | 0.35%   |
| Qimonda             | 2        | 0.35%   |
| Hewlett-Packard     | 2        | 0.35%   |
| GeIL                | 2        | 0.35%   |
| Unknown (AB)        | 1        | 0.18%   |
| Toshiba-0098        | 1        | 0.18%   |
| Timetec             | 1        | 0.18%   |
| Teikon              | 1        | 0.18%   |
| Swissbit            | 1        | 0.18%   |
| Smart               | 1        | 0.18%   |
| SHARETRONIC         | 1        | 0.18%   |
| Qumo                | 1        | 0.18%   |
| Positivo            | 1        | 0.18%   |
| OCZ                 | 1        | 0.18%   |
| Goodram             | 1        | 0.18%   |
| EVGA                | 1        | 0.18%   |
| CSX                 | 1        | 0.18%   |
| AVEXIR              | 1        | 0.18%   |
| Avant               | 1        | 0.18%   |
| Atermiter           | 1        | 0.18%   |
| Apacer              | 1        | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 9        | 1.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 6        | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 6        | 0.95%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 6        | 0.95%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 5        | 0.79%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 3000MT/s          | 5        | 0.79%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 5        | 0.79%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 4        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 4        | 0.63%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 4        | 0.63%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                       | 4        | 0.63%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 4        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 4        | 0.63%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3600MT/s         | 4        | 0.63%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 4        | 0.63%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s          | 4        | 0.63%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 4        | 0.63%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s        | 4        | 0.63%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s        | 4        | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 4        | 0.63%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                      | 3        | 0.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 3        | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 3        | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 3        | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3        | 0.47%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 3        | 0.47%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 3        | 0.47%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s          | 3        | 0.47%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 3        | 0.47%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s         | 3        | 0.47%   |
| Kingston RAM KHX1600C10D3/ 8192MB DIMM DDR3 1600MT/s         | 3        | 0.47%   |
| Kingston RAM 9905584-032.A01LF 4096MB DIMM DDR3 1600MT/s     | 3        | 0.47%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s     | 3        | 0.47%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s          | 3        | 0.47%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s       | 3        | 0.47%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                      | 2        | 0.32%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 2        | 0.32%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 2        | 0.32%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                  | 2        | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s               | 2        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 199      | 38.94%  |
| DDR4    | 197      | 38.55%  |
| DDR2    | 43       | 8.41%   |
| Unknown | 34       | 6.65%   |
| SDRAM   | 24       | 4.7%    |
| DDR     | 7        | 1.37%   |
| LPDDR4  | 6        | 1.17%   |
| DRAM    | 1        | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 456      | 90.84%  |
| SODIMM  | 44       | 8.76%   |
| FB-DIMM | 1        | 0.2%    |
| Unknown | 1        | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 176      | 31.6%   |
| 4096  | 143      | 25.67%  |
| 16384 | 101      | 18.13%  |
| 2048  | 93       | 16.7%   |
| 1024  | 26       | 4.67%   |
| 32768 | 15       | 2.69%   |
| 512   | 3        | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 133      | 23.58%  |
| 1333    | 58       | 10.28%  |
| 2400    | 44       | 7.8%    |
| 3200    | 39       | 6.91%   |
| 2133    | 31       | 5.5%    |
| 3600    | 27       | 4.79%   |
| 800     | 27       | 4.79%   |
| 2667    | 24       | 4.26%   |
| 667     | 22       | 3.9%    |
| 3000    | 15       | 2.66%   |
| Unknown | 15       | 2.66%   |
| 1866    | 12       | 2.13%   |
| 1867    | 10       | 1.77%   |
| 1066    | 9        | 1.6%    |
| 2933    | 8        | 1.42%   |
| 3733    | 7        | 1.24%   |
| 2666    | 7        | 1.24%   |
| 1800    | 5        | 0.89%   |
| 533     | 5        | 0.89%   |
| 400     | 5        | 0.89%   |
| 3466    | 4        | 0.71%   |
| 3400    | 4        | 0.71%   |
| 3334    | 4        | 0.71%   |
| 2800    | 4        | 0.71%   |
| 1067    | 4        | 0.71%   |
| 3800    | 3        | 0.53%   |
| 3500    | 3        | 0.53%   |
| 3151    | 3        | 0.53%   |
| 1639    | 3        | 0.53%   |
| 4000    | 2        | 0.35%   |
| 3333    | 2        | 0.35%   |
| 3100    | 2        | 0.35%   |
| 3066    | 2        | 0.35%   |
| 2200    | 2        | 0.35%   |
| 2048    | 2        | 0.35%   |
| 1334    | 2        | 0.35%   |
| 1332    | 2        | 0.35%   |
| 333     | 2        | 0.35%   |
| 49926   | 1        | 0.18%   |
| 8400    | 1        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 10       | 30.3%   |
| Brother Industries    | 6        | 18.18%  |
| Samsung Electronics   | 4        | 12.12%  |
| Canon                 | 4        | 12.12%  |
| Seiko Epson           | 2        | 6.06%   |
| Zebra                 | 1        | 3.03%   |
| Prolific Technology   | 1        | 3.03%   |
| Oki Data              | 1        | 3.03%   |
| Lexmark International | 1        | 3.03%   |
| Kyocera               | 1        | 3.03%   |
| Dell                  | 1        | 3.03%   |
| Datamax-O'Neil        | 1        | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Brother HL-52x0 series               | 3        | 9.09%   |
| HP LaserJet 1020                     | 2        | 6.06%   |
| Zebra ZTC S4M-200dpi ZPL             | 1        | 3.03%   |
| Seiko Epson XP-15000 Series          | 1        | 3.03%   |
| Seiko Epson Printer                  | 1        | 3.03%   |
| Samsung SCX-4600 Series              | 1        | 3.03%   |
| Samsung SCX-3400 Series              | 1        | 3.03%   |
| Samsung ML-216x Series Laser Printer | 1        | 3.03%   |
| Samsung M2020 Series                 | 1        | 3.03%   |
| Prolific PL2305 Parallel Port        | 1        | 3.03%   |
| Oki Data MC363 Multifunction Printer | 1        | 3.03%   |
| Lexmark International CS417dn        | 1        | 3.03%   |
| Kyocera FS-1120D                     | 1        | 3.03%   |
| HP PhotoSmart P1000                  | 1        | 3.03%   |
| HP HP LaserJet Pro M404-M405         | 1        | 3.03%   |
| HP HP LaserJet M14-M17               | 1        | 3.03%   |
| HP ENVY Photo 6200 series            | 1        | 3.03%   |
| HP DeskJet Plus 4100 series          | 1        | 3.03%   |
| HP DeskJet 5850c                     | 1        | 3.03%   |
| HP DeskJet 2700 series               | 1        | 3.03%   |
| HP Deskjet 1050 J410                 | 1        | 3.03%   |
| Dell B1160w Mono Laser Printer       | 1        | 3.03%   |
| Datamax-O'Neil Datamax E-4304        | 1        | 3.03%   |
| Canon TS6400 series                  | 1        | 3.03%   |
| Canon PIXMA MG3600 Series            | 1        | 3.03%   |
| Canon PIXMA MG2500 Series            | 1        | 3.03%   |
| Canon MB5300 series                  | 1        | 3.03%   |
| Brother HL-L2300D series             | 1        | 3.03%   |
| Brother HL-5350DN series             | 1        | 3.03%   |
| Brother HL-2220 series               | 1        | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 6        | 50%     |
| Seiko Epson        | 4        | 33.33%  |
| Ultima Electronics | 1        | 8.33%   |
| Mustek Systems     | 1        | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 2        | 16.67%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 8.33%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 8.33%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 8.33%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 8.33%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 8.33%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1        | 8.33%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1        | 8.33%   |
| Canon CanoScan LiDE 210                                                               | 1        | 8.33%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 61       | 48.03%  |
| Microdia                               | 12       | 9.45%   |
| Microsoft                              | 7        | 5.51%   |
| Sunplus Innovation Technology          | 5        | 3.94%   |
| Z-Star Microelectronics                | 4        | 3.15%   |
| Samsung Electronics                    | 4        | 3.15%   |
| Jieli Technology                       | 4        | 3.15%   |
| Generalplus Technology                 | 4        | 3.15%   |
| Huawei Technologies                    | 3        | 2.36%   |
| Hewlett-Packard                        | 2        | 1.57%   |
| Genesys Logic                          | 2        | 1.57%   |
| GEMBIRD                                | 2        | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 1.57%   |
| Apple                                  | 2        | 1.57%   |
| Trust                                  | 1        | 0.79%   |
| Syntek                                 | 1        | 0.79%   |
| Quanta                                 | 1        | 0.79%   |
| Pixart Imaging                         | 1        | 0.79%   |
| Philips (or NXP)                       | 1        | 0.79%   |
| OmniVision Technologies                | 1        | 0.79%   |
| MacroSilicon                           | 1        | 0.79%   |
| lihappe8                               | 1        | 0.79%   |
| Cubeternet                             | 1        | 0.79%   |
| Creative Technology                    | 1        | 0.79%   |
| Chicony Electronics                    | 1        | 0.79%   |
| Aveo Technology                        | 1        | 0.79%   |
| ARC International                      | 1        | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                 | 13       | 10.24%  |
| Logitech HD Pro Webcam C920                                          | 13       | 10.24%  |
| Microdia USB 2.0 Camera                                              | 6        | 4.72%   |
| Microsoft LifeCam HD-3000                                            | 5        | 3.94%   |
| Logitech HD Webcam C525                                              | 5        | 3.94%   |
| Logitech C922 Pro Stream Webcam                                      | 5        | 3.94%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 4        | 3.15%   |
| Logitech Webcam C170                                                 | 4        | 3.15%   |
| Jieli USB PHY 2.0                                                    | 4        | 3.15%   |
| Sunplus FULL HD webcam                                               | 3        | 2.36%   |
| Logitech HD Webcam C910                                              | 3        | 2.36%   |
| Huawei HiCamera                                                      | 3        | 2.36%   |
| Generalplus GENERAL WEBCAM                                           | 3        | 2.36%   |
| Z-Star Venus USB2.0 Camera                                           | 2        | 1.57%   |
| Microdia MSI Starcam Racer                                           | 2        | 1.57%   |
| Microdia Integrated Camera                                           | 2        | 1.57%   |
| Microdia Camera                                                      | 2        | 1.57%   |
| Logitech Webcam C930e                                                | 2        | 1.57%   |
| Logitech Webcam C310                                                 | 2        | 1.57%   |
| Logitech Webcam C210                                                 | 2        | 1.57%   |
| Logitech Webcam C200                                                 | 2        | 1.57%   |
| Logitech HD Webcam C615                                              | 2        | 1.57%   |
| Logitech BRIO Ultra HD Webcam                                        | 2        | 1.57%   |
| HP Webcam 3110                                                       | 2        | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 2        | 1.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                   | 2        | 1.57%   |
| Z-Star Vimicro USB Camera (Altair)                                   | 1        | 0.79%   |
| Z-Star A4 TECH USB2.0 PC Camera J                                    | 1        | 0.79%   |
| Trust WB-6250X Webcam                                                | 1        | 0.79%   |
| Syntek Integrated RGB Camera                                         | 1        | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1        | 0.79%   |
| Sunplus HK 5M WebCAM                                                 | 1        | 0.79%   |
| Quanta FV TouchCam N1 (Video)                                        | 1        | 0.79%   |
| Pixart Imaging Multimedia audio controller                           | 1        | 0.79%   |
| Philips (or NXP) Webcam SPC530NC                                     | 1        | 0.79%   |
| OmniVision USB Camera-OV580                                          | 1        | 0.79%   |
| Microsoft LifeCam HD-5000                                            | 1        | 0.79%   |
| Microsoft LifeCam Cinema                                             | 1        | 0.79%   |
| MacroSilicon USB Video                                               | 1        | 0.79%   |
| Logitech Webcam C600                                                 | 1        | 0.79%   |

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
| Alcor Micro               | 3        | 21.43%  |
| SCM Microsystems          | 2        | 14.29%  |
| Clay Logic                | 2        | 14.29%  |
| Yubico.com                | 1        | 7.14%   |
| Reiner SCT Kartensysteme  | 1        | 7.14%   |
| Realtek Semiconductor     | 1        | 7.14%   |
| Chicony Electronics       | 1        | 7.14%   |
| CHERRY                    | 1        | 7.14%   |
| Aladdin Knowledge Systems | 1        | 7.14%   |
| Advanced Card Systems     | 1        | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 21.43%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 7.14%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 7.14%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 7.14%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 7.14%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 7.14%   |
| Clay Logic Nitrokey Start                                                  | 1        | 7.14%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 7.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 7.14%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                | 1        | 7.14%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 7.14%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 594      | 76.55%  |
| 1     | 142      | 18.3%   |
| 2     | 31       | 3.99%   |
| 3     | 7        | 0.9%    |
| 6     | 2        | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 98       | 44.75%  |
| Net/wireless             | 27       | 12.33%  |
| Communication controller | 23       | 10.5%   |
| Unassigned class         | 18       | 8.22%   |
| Multimedia controller    | 14       | 6.39%   |
| Net/ethernet             | 7        | 3.2%    |
| Chipcard                 | 7        | 3.2%    |
| Sound                    | 6        | 2.74%   |
| Card reader              | 5        | 2.28%   |
| Storage/ide              | 3        | 1.37%   |
| Bluetooth                | 3        | 1.37%   |
| Network                  | 2        | 0.91%   |
| Camera                   | 2        | 0.91%   |
| Storage/raid             | 1        | 0.46%   |
| Modem                    | 1        | 0.46%   |
| Firewire controller      | 1        | 0.46%   |
| Fingerprint reader       | 1        | 0.46%   |

