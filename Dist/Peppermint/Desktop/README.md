Peppermint - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Peppermint.

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

Total: 156

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X470 GAMING PLUS MAX        | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| Foxconn       | Napa HP P/N                 | [a74b7b2a85](https://linux-hardware.org/?probe=a74b7b2a85) | May 28, 2023 |
| ASUSTek       | SABERTOOTH X58              | [9408c33828](https://linux-hardware.org/?probe=9408c33828) | Jan 14, 2023 |
| ASUSTek       | P5K SE/EPU                  | [6eed1ad6e5](https://linux-hardware.org/?probe=6eed1ad6e5) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | [ea64c817e2](https://linux-hardware.org/?probe=ea64c817e2) | Dec 28, 2022 |
| ASUSTek       | P5K SE/EPU                  | [b1c95f1d21](https://linux-hardware.org/?probe=b1c95f1d21) | Dec 28, 2022 |
| ASUSTek       | P5K SE/EPU                  | [6e816fc83e](https://linux-hardware.org/?probe=6e816fc83e) | Dec 24, 2022 |
| ASUSTek       | LEUCITE3                    | [f51161d005](https://linux-hardware.org/?probe=f51161d005) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [4c4e1b6871](https://linux-hardware.org/?probe=4c4e1b6871) | Oct 29, 2022 |
| Acer          | MCP7A                       | [c14a31f6ab](https://linux-hardware.org/?probe=c14a31f6ab) | Oct 28, 2022 |
| Dell          | 0RD203                      | [b427b55c0b](https://linux-hardware.org/?probe=b427b55c0b) | Oct 28, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASRock        | J4125B-ITX                  | [6e4ca6823f](https://linux-hardware.org/?probe=6e4ca6823f) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASRock        | N68-S3 FX                   | [f3e67de15e](https://linux-hardware.org/?probe=f3e67de15e) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | [78676e017b](https://linux-hardware.org/?probe=78676e017b) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M LE                 | [a7209bb34a](https://linux-hardware.org/?probe=a7209bb34a) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE                 | [5f7c38d0d5](https://linux-hardware.org/?probe=5f7c38d0d5) | Jan 22, 2022 |
| Intel         | D865GSA AAD52278-203        | [9b874becf9](https://linux-hardware.org/?probe=9b874becf9) | Dec 01, 2021 |
| Intel         | D865GSA AAD52278-203        | [ae2963be56](https://linux-hardware.org/?probe=ae2963be56) | Dec 01, 2021 |
| ECS           | 945GCT-M3                   | [a81a27ac47](https://linux-hardware.org/?probe=a81a27ac47) | Nov 25, 2021 |
| ECS           | Nettle3                     | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| ASUSTek       | P5GC-MX/1333                | [def67fa4e7](https://linux-hardware.org/?probe=def67fa4e7) | Nov 16, 2021 |
| Intel         | H61                         | [f1d3a975c0](https://linux-hardware.org/?probe=f1d3a975c0) | Oct 26, 2021 |
| ECS           | MCP61PM-GM                  | [1d13b80285](https://linux-hardware.org/?probe=1d13b80285) | Oct 13, 2021 |
| ASRock        | P4VM8                       | [5797c27ef8](https://linux-hardware.org/?probe=5797c27ef8) | Oct 10, 2021 |
| ASRock        | P4VM8                       | [84c50aca4b](https://linux-hardware.org/?probe=84c50aca4b) | Oct 10, 2021 |
| AAEON         | MF-001 V1.0                 | [c5492b6d2f](https://linux-hardware.org/?probe=c5492b6d2f) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | [522a137a4e](https://linux-hardware.org/?probe=522a137a4e) | Oct 05, 2021 |
| MSI           | MS-7211                     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| ASUSTek       | A88XM-A                     | [b1f8d57cae](https://linux-hardware.org/?probe=b1f8d57cae) | Sep 09, 2021 |
| HP            | 2AE3                        | [6780c45f7c](https://linux-hardware.org/?probe=6780c45f7c) | Aug 02, 2021 |
| Pegatron      | 2ACC                        | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASRock        | 970M Pro3                   | [9c2c0af05f](https://linux-hardware.org/?probe=9c2c0af05f) | May 27, 2021 |
| ASRock        | 970M Pro3                   | [0a5e45a21e](https://linux-hardware.org/?probe=0a5e45a21e) | May 27, 2021 |
| Pegatron      | Benicia                     | [7b1f7c7edf](https://linux-hardware.org/?probe=7b1f7c7edf) | Apr 15, 2021 |
| Dell          | 05DN3X A00                  | [14c65221b8](https://linux-hardware.org/?probe=14c65221b8) | Mar 20, 2021 |
| ASUSTek       | P4VP-MX                     | [ce116189a9](https://linux-hardware.org/?probe=ce116189a9) | Mar 19, 2021 |
| ASUSTek       | P4VP-MX                     | [1f7de7a842](https://linux-hardware.org/?probe=1f7de7a842) | Mar 19, 2021 |
| ASUSTek       | Acacia                      | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | [efab4d96e9](https://linux-hardware.org/?probe=efab4d96e9) | Mar 10, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | [514d4c99a1](https://linux-hardware.org/?probe=514d4c99a1) | Mar 10, 2021 |
| Dell          | 05DN3X A00                  | [2407fc2f7a](https://linux-hardware.org/?probe=2407fc2f7a) | Mar 09, 2021 |
| Dell          | Dimension E521              | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | 0C522T A01                  | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| HP            | 3032h                       | [50914ba2f5](https://linux-hardware.org/?probe=50914ba2f5) | Mar 04, 2021 |
| ASUSTek       | P5N-E SLI                   | [236a4d5753](https://linux-hardware.org/?probe=236a4d5753) | Feb 23, 2021 |
| ASUSTek       | P5N-E SLI                   | [27f148966a](https://linux-hardware.org/?probe=27f148966a) | Feb 23, 2021 |
| Dell          | Dimension E521              | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Dimension E521              | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [f7fc4d663b](https://linux-hardware.org/?probe=f7fc4d663b) | Feb 08, 2021 |
| Dell          | 0TP406                      | [0980bfcfe9](https://linux-hardware.org/?probe=0980bfcfe9) | Jan 28, 2021 |
| Dell          | 0K216C                      | [c1cf70d814](https://linux-hardware.org/?probe=c1cf70d814) | Jan 19, 2021 |
| Gigabyte      | 945GCM-S2L                  | [b0f061dfba](https://linux-hardware.org/?probe=b0f061dfba) | Jan 08, 2021 |
| Gigabyte      | 945GCM-S2L                  | [da98de1775](https://linux-hardware.org/?probe=da98de1775) | Jan 08, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [5494aa2859](https://linux-hardware.org/?probe=5494aa2859) | Jan 04, 2021 |
| HP            | 3032h                       | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| MSI           | MS-7211                     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Dell          | 0T656F A02                  | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Nvidia        | MCP7A 2                     | [c18fd136a9](https://linux-hardware.org/?probe=c18fd136a9) | Nov 24, 2020 |
| ASUSTek       | P5G41T-M LE                 | [ff9f1e3bc5](https://linux-hardware.org/?probe=ff9f1e3bc5) | Nov 22, 2020 |
| ASUSTek       | P5G41T-M LE                 | [41517af8ad](https://linux-hardware.org/?probe=41517af8ad) | Nov 22, 2020 |
| Gigabyte      | J1800M-D3P                  | [9ab6ea275f](https://linux-hardware.org/?probe=9ab6ea275f) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | J1800M-D3P                  | [ae71ad880b](https://linux-hardware.org/?probe=ae71ad880b) | Nov 10, 2020 |
| ASUSTek       | A88XM-A                     | [c02b06f51f](https://linux-hardware.org/?probe=c02b06f51f) | Oct 31, 2020 |
| Dell          | 0C2KJT A00                  | [37cf119697](https://linux-hardware.org/?probe=37cf119697) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | [d822785861](https://linux-hardware.org/?probe=d822785861) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | [b0a785eecd](https://linux-hardware.org/?probe=b0a785eecd) | Sep 30, 2020 |
| Intel         | 945GCT-M                    | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| HP            | 1494                        | [3d33e5eb9e](https://linux-hardware.org/?probe=3d33e5eb9e) | Sep 20, 2020 |
| Dell          | 09KPNV A00                  | [7a9366d7a0](https://linux-hardware.org/?probe=7a9366d7a0) | Sep 04, 2020 |
| HP            | 8265                        | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| ASUSTek       | CROSSHAIR II FORMULA        | [fc54031f7e](https://linux-hardware.org/?probe=fc54031f7e) | Aug 12, 2020 |
| HP            | 0A54h                       | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| ASRock        | N68-S3 FX                   | [cbf919cfd5](https://linux-hardware.org/?probe=cbf919cfd5) | Jul 30, 2020 |
| HP            | 18E7                        | [4b13141bdb](https://linux-hardware.org/?probe=4b13141bdb) | Jul 30, 2020 |
| Gigabyte      | 990FXA-UD3                  | [dc82f8cf6b](https://linux-hardware.org/?probe=dc82f8cf6b) | Jul 15, 2020 |
| MSI           | MS-7211                     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Gigabyte      | 990XA-UD3                   | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| HP            | 1494                        | [69ad46d94d](https://linux-hardware.org/?probe=69ad46d94d) | Jun 11, 2020 |
| ASUSTek       | K8N4-E Deluxe               | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [a514be4e22](https://linux-hardware.org/?probe=a514be4e22) | Jun 06, 2020 |
| MSI           | MS-7267                     | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Dell          | 02YRK5 A02                  | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Dell          | 02YRK5 A02                  | [4fa188ca3e](https://linux-hardware.org/?probe=4fa188ca3e) | May 15, 2020 |
| ECS           | Alhena5                     | [be2ff7b4dc](https://linux-hardware.org/?probe=be2ff7b4dc) | May 15, 2020 |
| Gigabyte      | 990FXA-UD3                  | [a0112b2478](https://linux-hardware.org/?probe=a0112b2478) | May 14, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | [39798ff3d6](https://linux-hardware.org/?probe=39798ff3d6) | May 05, 2020 |
| Dell          | 05DN3X A00                  | [9957230890](https://linux-hardware.org/?probe=9957230890) | Apr 30, 2020 |
| ASUSTek       | Amberine M                  | [c948d7fd76](https://linux-hardware.org/?probe=c948d7fd76) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | [595c810650](https://linux-hardware.org/?probe=595c810650) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | [f1fc9b4580](https://linux-hardware.org/?probe=f1fc9b4580) | Apr 29, 2020 |
| Gigabyte      | EQ45M-S2                    | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Dell          | 0Y958C A00                  | [131e2c31a9](https://linux-hardware.org/?probe=131e2c31a9) | Apr 26, 2020 |
| ASUSTek       | M3A78-EM                    | [f9944d9361](https://linux-hardware.org/?probe=f9944d9361) | Apr 25, 2020 |
| Dell          | 0WF810                      | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| ECS           | P4S5A/DX+                   | [e4cfc413e7](https://linux-hardware.org/?probe=e4cfc413e7) | Apr 08, 2020 |
| Gigabyte      | VM900M                      | [8554ccddc2](https://linux-hardware.org/?probe=8554ccddc2) | Apr 03, 2020 |
| HP            | 1494                        | [b34629c804](https://linux-hardware.org/?probe=b34629c804) | Mar 28, 2020 |
| HP            | 0A5Ch                       | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| ECS           | P4S5A/DX+                   | [a16a39037a](https://linux-hardware.org/?probe=a16a39037a) | Mar 24, 2020 |
| ECS           | P4S5A/DX+                   | [f5dcbfaa11](https://linux-hardware.org/?probe=f5dcbfaa11) | Mar 24, 2020 |
| Unknown       | G41 Series                  | [597b5edb76](https://linux-hardware.org/?probe=597b5edb76) | Mar 20, 2020 |
| HP            | 0AA8h                       | [881008d596](https://linux-hardware.org/?probe=881008d596) | Mar 11, 2020 |
| Acer          | MCP73PV NVIDIA MCP73        | [97b8e03710](https://linux-hardware.org/?probe=97b8e03710) | Mar 04, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [8b516d50ef](https://linux-hardware.org/?probe=8b516d50ef) | Mar 03, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [c67fe8542c](https://linux-hardware.org/?probe=c67fe8542c) | Mar 01, 2020 |
| ECS           | Alhena5                     | [89c17f438e](https://linux-hardware.org/?probe=89c17f438e) | Feb 28, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| HP            | 0AA8h                       | [c5721d223f](https://linux-hardware.org/?probe=c5721d223f) | Feb 05, 2020 |
| Dell          | 0F0TGN A00                  | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Lenovo        | 31900058 STD                | [4d8db6ee1f](https://linux-hardware.org/?probe=4d8db6ee1f) | Jan 22, 2020 |
| Lenovo        | 31900058 STD                | [6320c5f50f](https://linux-hardware.org/?probe=6320c5f50f) | Jan 22, 2020 |
| ASUSTek       | P8H61-MX                    | [c7c5cc3339](https://linux-hardware.org/?probe=c7c5cc3339) | Jan 17, 2020 |
| ASUSTek       | P8H61-MX                    | [4e6cff6c0e](https://linux-hardware.org/?probe=4e6cff6c0e) | Jan 17, 2020 |
| Gigabyte      | F2A55M-HD2                  | [75648daef1](https://linux-hardware.org/?probe=75648daef1) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASUSTek       | P5SD2-VM                    | [db8eaef3e7](https://linux-hardware.org/?probe=db8eaef3e7) | Jan 09, 2020 |
| Gigabyte      | P35-DS3R                    | [847cb4544c](https://linux-hardware.org/?probe=847cb4544c) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | [cf7e7bc433](https://linux-hardware.org/?probe=cf7e7bc433) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | [d7442beee0](https://linux-hardware.org/?probe=d7442beee0) | Dec 23, 2019 |
| HP            | 0A54h                       | [3a37dfd543](https://linux-hardware.org/?probe=3a37dfd543) | Dec 05, 2019 |
| Gigabyte      | F2A55M-HD2                  | [f30cd368d8](https://linux-hardware.org/?probe=f30cd368d8) | Dec 02, 2019 |
| Gigabyte      | F2A55M-HD2                  | [86b1a4acd7](https://linux-hardware.org/?probe=86b1a4acd7) | Dec 02, 2019 |
| Intel         | D945GCLF2 AAE46416-106      | [f2817e5306](https://linux-hardware.org/?probe=f2817e5306) | Nov 29, 2019 |
| Biostar       | A68N-5600E                  | [d91042148c](https://linux-hardware.org/?probe=d91042148c) | Nov 27, 2019 |
| Gigabyte      | F2A55M-HD2                  | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                     | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Dell          | 042P49 A01                  | [b7c0226ab5](https://linux-hardware.org/?probe=b7c0226ab5) | Nov 10, 2019 |
| ASUSTek       | X99-A/USB                   | [40ea4505b9](https://linux-hardware.org/?probe=40ea4505b9) | Nov 09, 2019 |
| eMachines     | EL1850                      | [c2b6c642fb](https://linux-hardware.org/?probe=c2b6c642fb) | Nov 09, 2019 |
| Lenovo        | 31900058 STD                | [ee0395fcb1](https://linux-hardware.org/?probe=ee0395fcb1) | Oct 25, 2019 |
| Gigabyte      | H61M-S1                     | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| ASUSTek       | K8N4-E Deluxe               | [dee3d2bdaa](https://linux-hardware.org/?probe=dee3d2bdaa) | Sep 04, 2019 |
| ASUSTek       | K8N4-E Deluxe               | [cfaaae942a](https://linux-hardware.org/?probe=cfaaae942a) | Aug 27, 2019 |
| Foxconn       | 2AB7                        | [f1f1f7133a](https://linux-hardware.org/?probe=f1f1f7133a) | Aug 18, 2019 |
| ASUSTek       | P5K-VM                      | [e2d3942d30](https://linux-hardware.org/?probe=e2d3942d30) | Jul 25, 2019 |
| Intel         | DX58SO AAE29331-702         | [d1b680dc39](https://linux-hardware.org/?probe=d1b680dc39) | Jul 05, 2019 |
| Dell          | 0C2KJT A00                  | [986146d6eb](https://linux-hardware.org/?probe=986146d6eb) | Jul 01, 2019 |
| Dell          | 0C2KJT A00                  | [ee64cbe6b5](https://linux-hardware.org/?probe=ee64cbe6b5) | Jun 28, 2019 |
| Pegatron      | NARRA5                      | [123cff15b7](https://linux-hardware.org/?probe=123cff15b7) | May 04, 2019 |
| Intel         | D945GNT AAC96324-402        | [23bac57788](https://linux-hardware.org/?probe=23bac57788) | Apr 07, 2019 |
| Dell          | 05DN3X A00                  | [81ec6c8fb1](https://linux-hardware.org/?probe=81ec6c8fb1) | Apr 04, 2019 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [11425d1746](https://linux-hardware.org/?probe=11425d1746) | Jan 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Peppermint 10   | 80       | 82.47%  |
| Peppermint 9    | 10       | 10.31%  |
| Peppermint 11.4 | 3        | 3.09%   |
| Peppermint      | 3        | 3.09%   |
| Peppermint 11.1 | 1        | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Peppermint | 97       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.0.0-37-generic     | 15       | 13.51%  |
| 5.3.0-46-generic     | 4        | 3.6%    |
| 5.10.0-16-amd64      | 4        | 3.6%    |
| 5.0.0-36-generic     | 4        | 3.6%    |
| 5.4.0-87-generic     | 3        | 2.7%    |
| 5.4.0-66-generic     | 3        | 2.7%    |
| 5.4.0-52-generic     | 3        | 2.7%    |
| 5.4.0-42-generic     | 3        | 2.7%    |
| 5.3.0-51-generic     | 3        | 2.7%    |
| 5.3.0-40-generic     | 3        | 2.7%    |
| 5.0.0-32-generic     | 3        | 2.7%    |
| 4.18.0-25-generic    | 3        | 2.7%    |
| 4.18.0-18-generic    | 3        | 2.7%    |
| 5.4.0-67-generic     | 2        | 1.8%    |
| 5.4.0-58-generic     | 2        | 1.8%    |
| 5.4.0-54-generic     | 2        | 1.8%    |
| 5.4.0-48-generic     | 2        | 1.8%    |
| 5.3.0-59-generic     | 2        | 1.8%    |
| 5.3.0-28-generic     | 2        | 1.8%    |
| 5.0.0-29-generic     | 2        | 1.8%    |
| 5.0.0-25-generic     | 2        | 1.8%    |
| 4.15.0-43-generic    | 2        | 1.8%    |
| 5.7.1-050701-generic | 1        | 0.9%    |
| 5.6.7-050607-generic | 1        | 0.9%    |
| 5.4.0-96-generic     | 1        | 0.9%    |
| 5.4.0-91-generic     | 1        | 0.9%    |
| 5.4.0-90-generic     | 1        | 0.9%    |
| 5.4.0-89-generic     | 1        | 0.9%    |
| 5.4.0-81-generic     | 1        | 0.9%    |
| 5.4.0-80-generic     | 1        | 0.9%    |
| 5.4.0-70-generic     | 1        | 0.9%    |
| 5.4.0-65-generic     | 1        | 0.9%    |
| 5.4.0-62-generic     | 1        | 0.9%    |
| 5.4.0-60-generic     | 1        | 0.9%    |
| 5.4.0-56-generic     | 1        | 0.9%    |
| 5.4.0-49-generic     | 1        | 0.9%    |
| 5.4.0-45-generic     | 1        | 0.9%    |
| 5.4.0-149-generic    | 1        | 0.9%    |
| 5.4.0-125-generic    | 1        | 0.9%    |
| 5.4.0-113-generic    | 1        | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 32.35%  |
| 5.0.0   | 25       | 24.51%  |
| 5.3.0   | 17       | 16.67%  |
| 4.15.0  | 10       | 9.8%    |
| 5.10.0  | 7        | 6.86%   |
| 4.18.0  | 6        | 5.88%   |
| 5.7.1   | 1        | 0.98%   |
| 5.6.7   | 1        | 0.98%   |
| 5.3.9   | 1        | 0.98%   |
| 5.3.6   | 1        | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 33       | 32.35%  |
| 5.0     | 25       | 24.51%  |
| 5.3     | 19       | 18.63%  |
| 4.15    | 10       | 9.8%    |
| 5.10    | 7        | 6.86%   |
| 4.18    | 6        | 5.88%   |
| 5.7     | 1        | 0.98%   |
| 5.6     | 1        | 0.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 70       | 71.43%  |
| i686   | 28       | 28.57%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXDE       | 72       | 72%     |
| Unknown    | 17       | 17%     |
| XFCE       | 7        | 7%      |
| GNOME      | 3        | 3%      |
| Peppermint | 1        | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 97       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 86.87%  |
| LightDM | 9        | 9.09%   |
| TDM     | 4        | 4.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 37       | 36.63%  |
| Unknown | 15       | 14.85%  |
| it_IT   | 7        | 6.93%   |
| pt_BR   | 6        | 5.94%   |
| de_DE   | 6        | 5.94%   |
| en_GB   | 5        | 4.95%   |
| en_IN   | 4        | 3.96%   |
| ru_RU   | 2        | 1.98%   |
| fr_FR   | 2        | 1.98%   |
| fi_FI   | 2        | 1.98%   |
| es_MX   | 2        | 1.98%   |
| C       | 2        | 1.98%   |
| ro_RO   | 1        | 0.99%   |
| pl_PL   | 1        | 0.99%   |
| es_PE   | 1        | 0.99%   |
| es_ES   | 1        | 0.99%   |
| es_EC   | 1        | 0.99%   |
| es_AR   | 1        | 0.99%   |
| en_PH   | 1        | 0.99%   |
| en_NZ   | 1        | 0.99%   |
| en_IE   | 1        | 0.99%   |
| en_CA   | 1        | 0.99%   |
| en_AU   | 1        | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 84       | 85.71%  |
| EFI  | 14       | 14.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 86       | 86%     |
| Unknown | 8        | 8%      |
| Overlay | 4        | 4%      |
| Xfs     | 1        | 1%      |
| Ext2    | 1        | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 92.78%  |
| MBR     | 4        | 4.12%   |
| GPT     | 3        | 3.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 87.88%  |
| Yes       | 12       | 12.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 82.47%  |
| Yes       | 17       | 17.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 21.65%  |
| Dell                | 14       | 14.43%  |
| Hewlett-Packard     | 11       | 11.34%  |
| Gigabyte Technology | 11       | 11.34%  |
| Intel               | 7        | 7.22%   |
| ECS                 | 5        | 5.15%   |
| ASRock              | 5        | 5.15%   |
| Pegatron            | 3        | 3.09%   |
| MSI                 | 3        | 3.09%   |
| Acer                | 3        | 3.09%   |
| Lenovo              | 2        | 2.06%   |
| Fujitsu Siemens     | 2        | 2.06%   |
| Foxconn             | 2        | 2.06%   |
| eMachines           | 2        | 2.06%   |
| Nvidia              | 1        | 1.03%   |
| Gateway             | 1        | 1.03%   |
| Fujitsu             | 1        | 1.03%   |
| Biostar             | 1        | 1.03%   |
| AAEON               | 1        | 1.03%   |
| Unknown             | 1        | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP Compaq dc7900 Convertible Minitower | 2        | 2.06%   |
| HP Compaq 8200 Elite CMT PC            | 2        | 2.06%   |
| Fujitsu Siemens D1931                  | 2        | 2.06%   |
| ASRock N68-S3 FX                       | 2        | 2.06%   |
| Pegatron FR502AA-ABZ m9355.it          | 1        | 1.03%   |
| Pegatron CQ1506LA                      | 1        | 1.03%   |
| Pegatron AY627AA-ABA a4313w            | 1        | 1.03%   |
| Nvidia MCP7A                           | 1        | 1.03%   |
| MSI MS-7B79                            | 1        | 1.03%   |
| MSI MS-7267                            | 1        | 1.03%   |
| MSI MS-7211                            | 1        | 1.03%   |
| Lenovo ThinkCentre M78 10BR0005US      | 1        | 1.03%   |
| Lenovo IdeaCentre Q190 10115           | 1        | 1.03%   |
| Intel H61                              | 1        | 1.03%   |
| Intel Energy Systems                   | 1        | 1.03%   |
| Intel DP55WG AAE57269-408              | 1        | 1.03%   |
| Intel D945GNT AAC96324-402             | 1        | 1.03%   |
| Intel D945GCLF2 AAE46416-106           | 1        | 1.03%   |
| Intel D865GSA AAD52278-203             | 1        | 1.03%   |
| Intel 945GCT-M                         | 1        | 1.03%   |
| HP ProDesk 600 G1 SFF                  | 1        | 1.03%   |
| HP EliteDesk 705 G3 MT                 | 1        | 1.03%   |
| HP CQ2930EA                            | 1        | 1.03%   |
| HP Compaq dc7800 Small Form Factor     | 1        | 1.03%   |
| HP Compaq dc7700p Small Form Factor    | 1        | 1.03%   |
| HP Compaq dc7700 Ultra-slim Desktop    | 1        | 1.03%   |
| HP Compaq dc7700 Small Form Factor     | 1        | 1.03%   |
| Gigabyte Z87X-UD5H                     | 1        | 1.03%   |
| Gigabyte P35-DS3R                      | 1        | 1.03%   |
| Gigabyte J1800M-D3P                    | 1        | 1.03%   |
| Gigabyte H61M-S1                       | 1        | 1.03%   |
| Gigabyte GA-VM900M                     | 1        | 1.03%   |
| Gigabyte F2A55M-HD2                    | 1        | 1.03%   |
| Gigabyte EQ45M-S2                      | 1        | 1.03%   |
| Gigabyte B450M S2H                     | 1        | 1.03%   |
| Gigabyte 990XA-UD3                     | 1        | 1.03%   |
| Gigabyte 990FXA-UD3                    | 1        | 1.03%   |
| Gigabyte 945GCM-S2L                    | 1        | 1.03%   |
| Gateway T5246                          | 1        | 1.03%   |
| Fujitsu ESPRIMO P510                   | 1        | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 8        | 8.25%   |
| Dell OptiPlex         | 6        | 6.19%   |
| Dell Inspiron         | 3        | 3.09%   |
| Acer Aspire           | 3        | 3.09%   |
| Fujitsu Siemens D1931 | 2        | 2.06%   |
| ASUS SABERTOOTH       | 2        | 2.06%   |
| ASUS ROG              | 2        | 2.06%   |
| ASRock N68-S3         | 2        | 2.06%   |
| Pegatron FR502AA-ABZ  | 1        | 1.03%   |
| Pegatron CQ1506LA     | 1        | 1.03%   |
| Pegatron AY627AA-ABA  | 1        | 1.03%   |
| Nvidia MCP7A          | 1        | 1.03%   |
| MSI MS-7B79           | 1        | 1.03%   |
| MSI MS-7267           | 1        | 1.03%   |
| MSI MS-7211           | 1        | 1.03%   |
| Lenovo ThinkCentre    | 1        | 1.03%   |
| Lenovo IdeaCentre     | 1        | 1.03%   |
| Intel H61             | 1        | 1.03%   |
| Intel Energy          | 1        | 1.03%   |
| Intel DP55WG          | 1        | 1.03%   |
| Intel D945GNT         | 1        | 1.03%   |
| Intel D945GCLF2       | 1        | 1.03%   |
| Intel D865GSA         | 1        | 1.03%   |
| Intel 945GCT-M        | 1        | 1.03%   |
| HP ProDesk            | 1        | 1.03%   |
| HP EliteDesk          | 1        | 1.03%   |
| HP CQ2930EA           | 1        | 1.03%   |
| Gigabyte Z87X-UD5H    | 1        | 1.03%   |
| Gigabyte P35-DS3R     | 1        | 1.03%   |
| Gigabyte J1800M-D3P   | 1        | 1.03%   |
| Gigabyte H61M-S1      | 1        | 1.03%   |
| Gigabyte GA-VM900M    | 1        | 1.03%   |
| Gigabyte F2A55M-HD2   | 1        | 1.03%   |
| Gigabyte EQ45M-S2     | 1        | 1.03%   |
| Gigabyte B450M        | 1        | 1.03%   |
| Gigabyte 990XA-UD3    | 1        | 1.03%   |
| Gigabyte 990FXA-UD3   | 1        | 1.03%   |
| Gigabyte 945GCM-S2L   | 1        | 1.03%   |
| Gateway T5246         | 1        | 1.03%   |
| Fujitsu ESPRIMO       | 1        | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 15       | 15.46%  |
| 2011 | 10       | 10.31%  |
| 2008 | 10       | 10.31%  |
| 2006 | 9        | 9.28%   |
| 2013 | 8        | 8.25%   |
| 2010 | 8        | 8.25%   |
| 2009 | 8        | 8.25%   |
| 2005 | 6        | 6.19%   |
| 2012 | 5        | 5.15%   |
| 2019 | 4        | 4.12%   |
| 2015 | 3        | 3.09%   |
| 2020 | 2        | 2.06%   |
| 2018 | 2        | 2.06%   |
| 2017 | 2        | 2.06%   |
| 2014 | 2        | 2.06%   |
| 2004 | 2        | 2.06%   |
| 2001 | 1        | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 97       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 96       | 98.97%  |
| Enabled  | 1        | 1.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 30       | 30%     |
| 1.01-2.0   | 24       | 24%     |
| 8.01-16.0  | 15       | 15%     |
| 4.01-8.0   | 8        | 8%      |
| 2.01-3.0   | 7        | 7%      |
| 16.01-24.0 | 6        | 6%      |
| 32.01-64.0 | 4        | 4%      |
| 0.51-1.0   | 4        | 4%      |
| 24.01-32.0 | 2        | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 43       | 39.81%  |
| 1.01-2.0  | 40       | 37.04%  |
| 2.01-3.0  | 7        | 6.48%   |
| 3.01-4.0  | 6        | 5.56%   |
| 4.01-8.0  | 5        | 4.63%   |
| 0.01-0.5  | 5        | 4.63%   |
| 8.01-16.0 | 2        | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 63.64%  |
| 2      | 24       | 24.24%  |
| 3      | 8        | 8.08%   |
| 7      | 1        | 1.01%   |
| 6      | 1        | 1.01%   |
| 5      | 1        | 1.01%   |
| 4      | 1        | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 66       | 67.35%  |
| No        | 32       | 32.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 95       | 97.94%  |
| No        | 2        | 2.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 53.61%  |
| No        | 45       | 46.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 80.41%  |
| Yes       | 19       | 19.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 35       | 35.71%  |
| Italy       | 9        | 9.18%   |
| Germany     | 8        | 8.16%   |
| Brazil      | 6        | 6.12%   |
| UK          | 5        | 5.1%    |
| India       | 5        | 5.1%    |
| Finland     | 3        | 3.06%   |
| Russia      | 2        | 2.04%   |
| Romania     | 2        | 2.04%   |
| Mexico      | 2        | 2.04%   |
| Greece      | 2        | 2.04%   |
| Canada      | 2        | 2.04%   |
| Argentina   | 2        | 2.04%   |
| Algeria     | 2        | 2.04%   |
| Ukraine     | 1        | 1.02%   |
| Sweden      | 1        | 1.02%   |
| Spain       | 1        | 1.02%   |
| Portugal    | 1        | 1.02%   |
| Poland      | 1        | 1.02%   |
| Philippines | 1        | 1.02%   |
| Peru        | 1        | 1.02%   |
| New Zealand | 1        | 1.02%   |
| Netherlands | 1        | 1.02%   |
| Ireland     | 1        | 1.02%   |
| Ecuador     | 1        | 1.02%   |
| Belgium     | 1        | 1.02%   |
| Australia   | 1        | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Villingen-Schwenningen | 3        | 2.97%   |
| New York               | 3        | 2.97%   |
| Spokane                | 2        | 1.98%   |
| Cavallino              | 2        | 1.98%   |
| Bengaluru              | 2        | 1.98%   |
| Wroclaw                | 1        | 0.99%   |
| Wassenaar              | 1        | 0.99%   |
| Washington             | 1        | 0.99%   |
| Vitória               | 1        | 0.99%   |
| Van Vleck              | 1        | 0.99%   |
| Turin                  | 1        | 0.99%   |
| Tsarskoye Selo         | 1        | 0.99%   |
| Thatcher               | 1        | 0.99%   |
| Taranto                | 1        | 0.99%   |
| Talala                 | 1        | 0.99%   |
| Tahlequah              | 1        | 0.99%   |
| Swidnica               | 1        | 0.99%   |
| Sun Prairie            | 1        | 0.99%   |
| Stoke-on-Trent         | 1        | 0.99%   |
| Stockholm              | 1        | 0.99%   |
| South Jordan           | 1        | 0.99%   |
| Seville                | 1        | 0.99%   |
| Seattle                | 1        | 0.99%   |
| Saratov                | 1        | 0.99%   |
| Santa Barbara          | 1        | 0.99%   |
| Sankt Augustin         | 1        | 0.99%   |
| Rock Hill              | 1        | 0.99%   |
| Roanoke                | 1        | 0.99%   |
| Rio de Janeiro         | 1        | 0.99%   |
| Rio                    | 1        | 0.99%   |
| Reggio Emilia          | 1        | 0.99%   |
| Quezon City            | 1        | 0.99%   |
| Pune                   | 1        | 0.99%   |
| Prevost                | 1        | 0.99%   |
| Popesti-Leordeni       | 1        | 0.99%   |
| Ponchatoula            | 1        | 0.99%   |
| Philadelphia           | 1        | 0.99%   |
| Perth                  | 1        | 0.99%   |
| Peristeri              | 1        | 0.99%   |
| Pensacola              | 1        | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 35       | 54     | 25.93%  |
| Seagate                     | 28       | 33     | 20.74%  |
| Samsung Electronics         | 15       | 20     | 11.11%  |
| Hitachi                     | 15       | 22     | 11.11%  |
| Maxtor                      | 10       | 12     | 7.41%   |
| Kingston                    | 7        | 9      | 5.19%   |
| SanDisk                     | 3        | 3      | 2.22%   |
| Toshiba                     | 2        | 2      | 1.48%   |
| PNY                         | 2        | 3      | 1.48%   |
| Intel                       | 2        | 2      | 1.48%   |
| WD MediaMax                 | 1        | 1      | 0.74%   |
| USB3.0                      | 1        | 1      | 0.74%   |
| Unknown                     | 1        | 1      | 0.74%   |
| Phison Electronics          | 1        | 1      | 0.74%   |
| Phison                      | 1        | 2      | 0.74%   |
| OCZ                         | 1        | 1      | 0.74%   |
| Lexar                       | 1        | 1      | 0.74%   |
| Kingston Technology Company | 1        | 1      | 0.74%   |
| Intenso                     | 1        | 1      | 0.74%   |
| GAMER                       | 1        | 1      | 0.74%   |
| Fujitsu                     | 1        | 1      | 0.74%   |
| Dogfish                     | 1        | 1      | 0.74%   |
| Crucial                     | 1        | 2      | 0.74%   |
| China                       | 1        | 1      | 0.74%   |
| ASMT                        | 1        | 1      | 0.74%   |
| ADATA Technology            | 1        | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST3500418AS 500GB           | 3        | 2.08%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 2.08%   |
| Hitachi HDT721016SLA380 160GB       | 3        | 2.08%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 1.39%   |
| Seagate ST3250310AS 250GB           | 2        | 1.39%   |
| Seagate ST3160813AS 160GB           | 2        | 1.39%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 1.39%   |
| SanDisk SDSSDA120G 120GB            | 2        | 1.39%   |
| Samsung SSD 860 EVO 1TB             | 2        | 1.39%   |
| Maxtor STM3160215AS 160GB           | 2        | 1.39%   |
| Kingston SA400S37240G 240GB SSD     | 2        | 1.39%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 1.39%   |
| Hitachi HDP725050GLA360 500GB       | 2        | 1.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.69%   |
| WDC WD800JD-75MSA1 80GB             | 1        | 0.69%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.69%   |
| WDC WD800JD-00MSA1 80GB             | 1        | 0.69%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.69%   |
| WDC WD5000LPVT-24G33T1 500GB        | 1        | 0.69%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.69%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.69%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 0.69%   |
| WDC WD4000AAJS-22TKA0 400GB         | 1        | 0.69%   |
| WDC WD4000AAJS-00YFA0 400GB         | 1        | 0.69%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.69%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1        | 0.69%   |
| WDC WD3200AVJB-63WKA0 320GB         | 1        | 0.69%   |
| WDC WD3200AAJS-65M0A0 320GB         | 1        | 0.69%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1        | 0.69%   |
| WDC WD30EFZX-68AWUN0 3TB            | 1        | 0.69%   |
| WDC WD2500JS-60NCB1 250GB           | 1        | 0.69%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1        | 0.69%   |
| WDC WD2500AVJB-63WKA0 250GB         | 1        | 0.69%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 0.69%   |
| WDC WD2500AAJS-00VTA0 250GB         | 1        | 0.69%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.69%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 0.69%   |
| WDC WD2000JS-60NCB1 200GB           | 1        | 0.69%   |
| WDC WD1600JS-00NCB1 160GB           | 1        | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 53     | 33.66%  |
| Seagate             | 28       | 33     | 27.72%  |
| Hitachi             | 15       | 22     | 14.85%  |
| Maxtor              | 10       | 12     | 9.9%    |
| Samsung Electronics | 9        | 12     | 8.91%   |
| Toshiba             | 2        | 2      | 1.98%   |
| WD MediaMax         | 1        | 1      | 0.99%   |
| USB3.0              | 1        | 1      | 0.99%   |
| Fujitsu             | 1        | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 9      | 25.93%  |
| Samsung Electronics | 5        | 7      | 18.52%  |
| SanDisk             | 3        | 3      | 11.11%  |
| PNY                 | 2        | 3      | 7.41%   |
| Intel               | 2        | 2      | 7.41%   |
| WDC                 | 1        | 1      | 3.7%    |
| OCZ                 | 1        | 1      | 3.7%    |
| Lexar               | 1        | 1      | 3.7%    |
| GAMER               | 1        | 1      | 3.7%    |
| Dogfish             | 1        | 1      | 3.7%    |
| Crucial             | 1        | 2      | 3.7%    |
| China               | 1        | 1      | 3.7%    |
| ASMT                | 1        | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 84       | 137    | 72.41%  |
| SSD     | 27       | 33     | 23.28%  |
| NVMe    | 3        | 6      | 2.59%   |
| MMC     | 1        | 1      | 0.86%   |
| Unknown | 1        | 1      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 95       | 168    | 93.14%  |
| SAS  | 3        | 3      | 2.94%   |
| NVMe | 3        | 6      | 2.94%   |
| MMC  | 1        | 1      | 0.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 83       | 124    | 70.94%  |
| 0.51-1.0   | 23       | 29     | 19.66%  |
| 1.01-2.0   | 9        | 13     | 7.69%   |
| 2.01-3.0   | 1        | 3      | 0.85%   |
| 4.01-10.0  | 1        | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 37       | 36.27%  |
| 251-500        | 15       | 14.71%  |
| 501-1000       | 14       | 13.73%  |
| 51-100         | 14       | 13.73%  |
| 1001-2000      | 8        | 7.84%   |
| 21-50          | 6        | 5.88%   |
| 1-20           | 3        | 2.94%   |
| 2001-3000      | 2        | 1.96%   |
| Unknown        | 2        | 1.96%   |
| More than 3000 | 1        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 53       | 51.96%  |
| 21-50     | 19       | 18.63%  |
| 101-250   | 12       | 11.76%  |
| 51-100    | 7        | 6.86%   |
| 501-1000  | 4        | 3.92%   |
| 1001-2000 | 3        | 2.94%   |
| 251-500   | 2        | 1.96%   |
| Unknown   | 2        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB      | 1        | 1      | 33.33%  |
| Seagate ST31500341AS 1TB       | 1        | 1      | 33.33%  |
| Seagate ST2000DM008-2FR102 2TB | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

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
| Detected | 91       | 166    | 90.1%   |
| Works    | 7        | 9      | 6.93%   |
| Malfunc  | 3        | 3      | 2.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 57       | 50.44%  |
| AMD                              | 17       | 15.04%  |
| Nvidia                           | 15       | 13.27%  |
| JMicron Technology               | 6        | 5.31%   |
| VIA Technologies                 | 4        | 3.54%   |
| Marvell Technology Group         | 4        | 3.54%   |
| Silicon Integrated Systems [SiS] | 2        | 1.77%   |
| ULi Electronics                  | 1        | 0.88%   |
| Silicon Image                    | 1        | 0.88%   |
| Samsung Electronics              | 1        | 0.88%   |
| Phison Electronics               | 1        | 0.88%   |
| LSI Logic / Symbios Logic        | 1        | 0.88%   |
| Kingston Technology Company      | 1        | 0.88%   |
| ASMedia Technology               | 1        | 0.88%   |
| ADATA Technology                 | 1        | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14       | 8.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14       | 8.19%   |
| Nvidia MCP61 SATA Controller                                                   | 7        | 4.09%   |
| Nvidia MCP61 IDE                                                               | 6        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 3.51%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 2.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 4        | 2.34%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4        | 2.34%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 4        | 2.34%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 1.75%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 3        | 1.75%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 3        | 1.75%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 1.75%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 1.75%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 2        | 1.17%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2        | 1.17%   |
| Nvidia MCP79 AHCI Controller                                                   | 2        | 1.17%   |
| Nvidia MCP73 IDE Controller                                                    | 2        | 1.17%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2        | 1.17%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 1.17%   |
| JMicron JMB368 IDE controller                                                  | 2        | 1.17%   |
| JMicron JMB362 SATA Controller                                                 | 2        | 1.17%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 1.17%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                  | 2        | 1.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2        | 1.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 1.17%   |
| VIA VT8237/8251 Serial ATA Controller                                          | 1        | 0.58%   |
| ULi ULi 5287 SATA                                                              | 1        | 0.58%   |
| ULi M5229 IDE                                                                  | 1        | 0.58%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 0.58%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.58%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.58%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 60       | 52.63%  |
| SATA | 42       | 36.84%  |
| RAID | 8        | 7.02%   |
| NVMe | 3        | 2.63%   |
| SAS  | 1        | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 71       | 73.2%   |
| AMD    | 26       | 26.8%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4        | 4.12%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 3.09%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 3.09%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 2.06%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 2.06%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2        | 2.06%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 2.06%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.06%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2        | 2.06%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 2        | 2.06%   |
| Intel Atom CPU 230 @ 1.60GHz                | 2        | 2.06%   |
| AMD Phenom II X4 840 Processor              | 2        | 2.06%   |
| AMD Athlon II X2 250 Processor              | 2        | 2.06%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 2.06%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.03%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 1.03%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 1.03%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.03%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.03%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.03%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1        | 1.03%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.03%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.03%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 1.03%   |
| Intel Pentium CPU G6960 @ 2.93GHz           | 1        | 1.03%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.03%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.03%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 1.03%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 1.03%   |
| Intel Pentium 4 CPU 2.40GHz                 | 1        | 1.03%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.03%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1        | 1.03%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.03%   |
| Intel Core i7 CPU X 980 @ 3.33GHz           | 1        | 1.03%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.03%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.03%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 1.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.03%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 8        | 8.25%   |
| Intel Core 2 Quad       | 8        | 8.25%   |
| Intel Celeron           | 8        | 8.25%   |
| Intel Core i7           | 7        | 7.22%   |
| Intel Core 2 Duo        | 7        | 7.22%   |
| Intel Core i5           | 6        | 6.19%   |
| AMD Athlon 64 X2        | 6        | 6.19%   |
| Intel Pentium Dual-Core | 5        | 5.15%   |
| Intel Atom              | 5        | 5.15%   |
| Intel Xeon              | 3        | 3.09%   |
| Intel Pentium Dual      | 3        | 3.09%   |
| Intel Pentium D         | 3        | 3.09%   |
| Intel Pentium           | 3        | 3.09%   |
| Intel Core 2            | 3        | 3.09%   |
| AMD Phenom II X4        | 3        | 3.09%   |
| Other                   | 2        | 2.06%   |
| Intel Core i3           | 2        | 2.06%   |
| AMD FX                  | 2        | 2.06%   |
| AMD Athlon II X2        | 2        | 2.06%   |
| AMD Sempron             | 1        | 1.03%   |
| AMD Ryzen 7             | 1        | 1.03%   |
| AMD Ryzen 5             | 1        | 1.03%   |
| AMD Ryzen 3             | 1        | 1.03%   |
| AMD Phenom              | 1        | 1.03%   |
| AMD E1                  | 1        | 1.03%   |
| AMD Athlon II X4        | 1        | 1.03%   |
| AMD Athlon 64           | 1        | 1.03%   |
| AMD A8                  | 1        | 1.03%   |
| AMD A6                  | 1        | 1.03%   |
| AMD A4                  | 1        | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 42.27%  |
| 4      | 28       | 28.87%  |
| 1      | 21       | 21.65%  |
| 6      | 5        | 5.15%   |
| 8      | 1        | 1.03%   |
| 3      | 1        | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 97       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 67.01%  |
| 2      | 32       | 32.99%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 86       | 87.76%  |
| Unknown        | 7        | 7.14%   |
| 32-bit         | 5        | 5.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 15.31%  |
| 0x1067a    | 12       | 12.24%  |
| 0x6fd      | 5        | 5.1%    |
| 0x206a7    | 5        | 5.1%    |
| 0xf41      | 4        | 4.08%   |
| 0x306a9    | 4        | 4.08%   |
| 0x010000c8 | 4        | 4.08%   |
| 0x6fb      | 3        | 3.06%   |
| 0x106c2    | 3        | 3.06%   |
| 0x10661    | 3        | 3.06%   |
| 0xf65      | 2        | 2.04%   |
| 0xf47      | 2        | 2.04%   |
| 0x6f6      | 2        | 2.04%   |
| 0x306c3    | 2        | 2.04%   |
| 0x206c2    | 2        | 2.04%   |
| 0x20655    | 2        | 2.04%   |
| 0x106a5    | 2        | 2.04%   |
| 0x06001119 | 2        | 2.04%   |
| 0xf62      | 1        | 1.02%   |
| 0xf43      | 1        | 1.02%   |
| 0xf33      | 1        | 1.02%   |
| 0xf27      | 1        | 1.02%   |
| 0x906ea    | 1        | 1.02%   |
| 0x706a8    | 1        | 1.02%   |
| 0x6f2      | 1        | 1.02%   |
| 0x406c4    | 1        | 1.02%   |
| 0x306f2    | 1        | 1.02%   |
| 0x30678    | 1        | 1.02%   |
| 0x20652    | 1        | 1.02%   |
| 0x106ca    | 1        | 1.02%   |
| 0x10677    | 1        | 1.02%   |
| 0x10676    | 1        | 1.02%   |
| 0x0a50000b | 1        | 1.02%   |
| 0x08701013 | 1        | 1.02%   |
| 0x08108109 | 1        | 1.02%   |
| 0x07030106 | 1        | 1.02%   |
| 0x0600611a | 1        | 1.02%   |
| 0x06000852 | 1        | 1.02%   |
| 0x06000822 | 1        | 1.02%   |
| 0x05000119 | 1        | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 15       | 15.46%  |
| Core          | 14       | 14.43%  |
| NetBurst      | 13       | 13.4%   |
| K10           | 8        | 8.25%   |
| K8 Hammer     | 7        | 7.22%   |
| Westmere      | 5        | 5.15%   |
| SandyBridge   | 5        | 5.15%   |
| Piledriver    | 5        | 5.15%   |
| IvyBridge     | 5        | 5.15%   |
| Haswell       | 4        | 4.12%   |
| Bonnell       | 4        | 4.12%   |
| Silvermont    | 2        | 2.06%   |
| Nehalem       | 2        | 2.06%   |
| Zen+          | 1        | 1.03%   |
| Zen 3         | 1        | 1.03%   |
| Zen 2         | 1        | 1.03%   |
| Puma          | 1        | 1.03%   |
| KabyLake      | 1        | 1.03%   |
| Goldmont plus | 1        | 1.03%   |
| Excavator     | 1        | 1.03%   |
| Bobcat        | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 37       | 36.63%  |
| Nvidia           | 36       | 35.64%  |
| AMD              | 26       | 25.74%  |
| VIA Technologies | 2        | 1.98%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 6.8%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 6        | 5.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.91%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3        | 2.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.94%   |
| Nvidia G94 [GeForce 9600 GS]                                                | 2        | 1.94%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 2        | 1.94%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                     | 2        | 1.94%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.94%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.94%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.94%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                        | 2        | 1.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.94%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 1.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.94%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 0.97%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]           | 1        | 0.97%   |
| Nvidia NV44A [GeForce 6200]                                                 | 1        | 0.97%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                       | 1        | 0.97%   |
| Nvidia NV43 [GeForce 6600 LE]                                               | 1        | 0.97%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 0.97%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.97%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.97%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.97%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.97%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.97%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.97%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.97%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.97%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 0.97%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.97%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 0.97%   |
| Nvidia G72 [GeForce 7500 LE]                                                | 1        | 0.97%   |
| Nvidia C79 [ION]                                                            | 1        | 0.97%   |
| Nvidia C77 [nForce 780a/980a SLI]                                           | 1        | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 34       | 35.05%  |
| 1 x Nvidia     | 33       | 34.02%  |
| 1 x AMD        | 26       | 26.8%   |
| 1 x VIA        | 2        | 2.06%   |
| Intel + Nvidia | 2        | 2.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 82       | 83.67%  |
| Proprietary | 13       | 13.27%  |
| Unknown     | 3        | 3.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 41.24%  |
| 0.01-0.5   | 29       | 29.9%   |
| 0.51-1.0   | 12       | 12.37%  |
| 1.01-2.0   | 11       | 11.34%  |
| 3.01-4.0   | 3        | 3.09%   |
| 7.01-8.0   | 1        | 1.03%   |
| 8.01-16.0  | 1        | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 14.13%  |
| Acer                 | 13       | 14.13%  |
| Dell                 | 12       | 13.04%  |
| Goldstar             | 9        | 9.78%   |
| Hewlett-Packard      | 7        | 7.61%   |
| BenQ                 | 5        | 5.43%   |
| LG Electronics       | 3        | 3.26%   |
| AOC                  | 3        | 3.26%   |
| Ancor Communications | 3        | 3.26%   |
| ___                  | 2        | 2.17%   |
| Unknown              | 2        | 2.17%   |
| Sony                 | 2        | 2.17%   |
| Sharp                | 2        | 2.17%   |
| Lenovo               | 2        | 2.17%   |
| VIZ                  | 1        | 1.09%   |
| ViewSonic            | 1        | 1.09%   |
| Vestel Elektronik    | 1        | 1.09%   |
| Toshiba              | 1        | 1.09%   |
| Sceptre Tech         | 1        | 1.09%   |
| Panasonic            | 1        | 1.09%   |
| MPI                  | 1        | 1.09%   |
| Lite-On              | 1        | 1.09%   |
| KTC                  | 1        | 1.09%   |
| Hitachi              | 1        | 1.09%   |
| HannStar             | 1        | 1.09%   |
| FUS                  | 1        | 1.09%   |
| Fujitsu Siemens      | 1        | 1.09%   |
| CPT                  | 1        | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ___ LCDTV16 ___0101 1920x1080                                           | 2        | 2.11%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                     | 2        | 2.11%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                       | 2        | 2.11%   |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                        | 2        | 2.11%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                       | 2        | 2.11%   |
| VIZ LCD Monitor D50-D1 1920x1080                                        | 1        | 1.05%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch                | 1        | 1.05%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch    | 1        | 1.05%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                      | 1        | 1.05%   |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                     | 1        | 1.05%   |
| Sony LCD Monitor TV                                                     | 1        | 1.05%   |
| Sharp LCD SHP1047 1920x1080                                             | 1        | 1.05%   |
| Sharp LCD SHP0FF0 1360x768                                              | 1        | 1.05%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                   | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch    | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch    | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch    | 1        | 1.05%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch        | 1        | 1.05%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch       | 1        | 1.05%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch       | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SyncMaster 2624x1200                    | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SMB1930NW 1440x900                      | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                       | 1        | 1.05%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1        | 1.05%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1        | 1.05%   |
| Panasonic TH-42PD25U MEIA023 1920x540 920x518mm 41.6-inch               | 1        | 1.05%   |
| MPI MPI7002 MPI7002 1280x1024 255x255mm 14.2-inch                       | 1        | 1.05%   |
| Lite-On B17MTF LTN022A 1280x768 369x221mm 16.9-inch                     | 1        | 1.05%   |
| LG Electronics LCD Monitor M227WD 1920x1080                             | 1        | 1.05%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                      | 1        | 1.05%   |
| LG Electronics LCD Monitor FLATRON 795FT Plus 1600x1200                 | 1        | 1.05%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch                | 1        | 1.05%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                   | 1        | 1.05%   |
| KTC Q3202S KTC3200 2560x1440 698x392mm 31.5-inch                        | 1        | 1.05%   |
| Hitachi 40E31 HTC0139 1920x1080 575x323mm 26.0-inch                     | 1        | 1.05%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 510x290mm 23.1-inch            | 1        | 1.05%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 1        | 1.05%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1        | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 34.44%  |
| 1280x1024 (SXGA)   | 15       | 16.67%  |
| 1440x900 (WXGA+)   | 5        | 5.56%   |
| 1366x768 (WXGA)    | 5        | 5.56%   |
| 2560x1440 (QHD)    | 4        | 4.44%   |
| 1680x1050 (WSXGA+) | 4        | 4.44%   |
| 1600x900 (HD+)     | 4        | 4.44%   |
| 1360x768           | 4        | 4.44%   |
| 1024x768 (XGA)     | 4        | 4.44%   |
| 3840x2160 (4K)     | 2        | 2.22%   |
| 2560x1080          | 2        | 2.22%   |
| Unknown            | 2        | 2.22%   |
| 3840x1080          | 1        | 1.11%   |
| 2624x1200          | 1        | 1.11%   |
| 2048x1152          | 1        | 1.11%   |
| 1920x540           | 1        | 1.11%   |
| 1920x1200 (WUXGA)  | 1        | 1.11%   |
| 1600x1200          | 1        | 1.11%   |
| 1280x768           | 1        | 1.11%   |
| 1280x720 (HD)      | 1        | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 15.22%  |
| 19      | 11       | 11.96%  |
| 17      | 9        | 9.78%   |
| 27      | 7        | 7.61%   |
| 21      | 6        | 6.52%   |
| 18      | 6        | 6.52%   |
| 15      | 6        | 6.52%   |
| 23      | 5        | 5.43%   |
| 24      | 4        | 4.35%   |
| 22      | 4        | 4.35%   |
| 31      | 3        | 3.26%   |
| 20      | 3        | 3.26%   |
| 84      | 2        | 2.17%   |
| 72      | 2        | 2.17%   |
| 34      | 2        | 2.17%   |
| 14      | 2        | 2.17%   |
| 74      | 1        | 1.09%   |
| 41      | 1        | 1.09%   |
| 40      | 1        | 1.09%   |
| 32      | 1        | 1.09%   |
| 26      | 1        | 1.09%   |
| 16      | 1        | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 22       | 23.91%  |
| 501-600     | 16       | 17.39%  |
| 301-350     | 14       | 15.22%  |
| Unknown     | 14       | 15.22%  |
| 351-400     | 10       | 10.87%  |
| 1501-2000   | 5        | 5.43%   |
| 601-700     | 4        | 4.35%   |
| 701-800     | 3        | 3.26%   |
| 201-300     | 2        | 2.17%   |
| 801-900     | 1        | 1.09%   |
| 901-1000    | 1        | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 50.57%  |
| 5/4     | 11       | 12.64%  |
| Unknown | 11       | 12.64%  |
| 16/10   | 10       | 11.49%  |
| 6/5     | 4        | 4.6%    |
| 4/3     | 4        | 4.6%    |
| 21/9    | 2        | 2.3%    |
| 1.00    | 1        | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 18       | 19.78%  |
| 201-250        | 14       | 15.38%  |
| Unknown        | 14       | 15.38%  |
| 141-150        | 13       | 14.29%  |
| 301-350        | 7        | 7.69%   |
| 101-110        | 7        | 7.69%   |
| 351-500        | 6        | 6.59%   |
| More than 1000 | 5        | 5.49%   |
| 251-300        | 3        | 3.3%    |
| 501-1000       | 2        | 2.2%    |
| 131-140        | 1        | 1.1%    |
| 121-130        | 1        | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 65.88%  |
| Unknown | 14       | 16.47%  |
| 101-120 | 10       | 11.76%  |
| 1-50    | 5        | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 86.6%   |
| 2     | 8        | 8.25%   |
| 0     | 3        | 3.09%   |
| 3     | 2        | 2.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 49       | 32.24%  |
| Intel                           | 25       | 16.45%  |
| Nvidia                          | 14       | 9.21%   |
| Qualcomm Atheros                | 12       | 7.89%   |
| Broadcom                        | 10       | 6.58%   |
| Ralink Technology               | 9        | 5.92%   |
| VIA Technologies                | 3        | 1.97%   |
| Qualcomm Atheros Communications | 3        | 1.97%   |
| Marvell Technology Group        | 3        | 1.97%   |
| Gemtek                          | 3        | 1.97%   |
| D-Link                          | 3        | 1.97%   |
| TP-Link                         | 2        | 1.32%   |
| Samsung Electronics             | 2        | 1.32%   |
| Ralink                          | 2        | 1.32%   |
| Broadcom Limited                | 2        | 1.32%   |
| ASUSTek Computer                | 2        | 1.32%   |
| 3Com                            | 2        | 1.32%   |
| Xiaomi                          | 1        | 0.66%   |
| NetGear                         | 1        | 0.66%   |
| Motorola PCS                    | 1        | 0.66%   |
| D-Link System                   | 1        | 0.66%   |
| Belkin Components               | 1        | 0.66%   |
| ADMtek                          | 1        | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 16.15%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 4.97%   |
| Nvidia MCP61 Ethernet                                             | 7        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.11%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.48%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.86%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 3        | 1.86%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 1.86%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3        | 1.86%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 1.86%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                 | 3        | 1.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.24%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 1.24%   |
| Realtek 802.11ac NIC                                              | 2        | 1.24%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.24%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 1.24%   |
| Nvidia MCP79 Ethernet                                             | 2        | 1.24%   |
| Nvidia MCP73 Ethernet                                             | 2        | 1.24%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.24%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 1.24%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 1.24%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2        | 1.24%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.62%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                      | 1        | 0.62%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.62%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.62%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                  | 1        | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.62%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.62%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.62%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.62%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 28.57%  |
| Ralink Technology               | 9        | 16.07%  |
| Qualcomm Atheros                | 8        | 14.29%  |
| Qualcomm Atheros Communications | 3        | 5.36%   |
| Gemtek                          | 3        | 5.36%   |
| D-Link                          | 3        | 5.36%   |
| TP-Link                         | 2        | 3.57%   |
| Ralink                          | 2        | 3.57%   |
| ASUSTek Computer                | 2        | 3.57%   |
| VIA Technologies                | 1        | 1.79%   |
| Samsung Electronics             | 1        | 1.79%   |
| NetGear                         | 1        | 1.79%   |
| Marvell Technology Group        | 1        | 1.79%   |
| Intel                           | 1        | 1.79%   |
| D-Link System                   | 1        | 1.79%   |
| Broadcom                        | 1        | 1.79%   |
| Belkin Components               | 1        | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                        | 4        | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                    | 3        | 5.36%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                              | 3        | 5.36%   |
| Ralink RT5370 Wireless Adapter                                                         | 3        | 5.36%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                      | 3        | 5.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                        | 2        | 3.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 2        | 3.57%   |
| Realtek 802.11ac NIC                                                                   | 2        | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                                        | 2        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                       | 2        | 3.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                       | 2        | 3.57%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                           | 1        | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                            | 1        | 1.79%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                  | 1        | 1.79%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                       | 1        | 1.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                               | 1        | 1.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                 | 1        | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 1        | 1.79%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                               | 1        | 1.79%   |
| Ralink RT5572 Wireless Adapter                                                         | 1        | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                  | 1        | 1.79%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                   | 1        | 1.79%   |
| Ralink RT2561/RT61 rev B 802.11g                                                       | 1        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1        | 1.79%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271]          | 1        | 1.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                         | 1        | 1.79%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]         | 1        | 1.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                | 1        | 1.79%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                                    | 1        | 1.79%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                                    | 1        | 1.79%   |
| Intel Wi-Fi 6 AX200                                                                    | 1        | 1.79%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072]                   | 1        | 1.79%   |
| D-Link DWP-156                                                                         | 1        | 1.79%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                   | 1        | 1.79%   |
| D-Link 802.11ac NIC                                                                    | 1        | 1.79%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                                     | 1        | 1.79%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 1.79%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                        | 1        | 1.79%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                     | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 41       | 40.2%   |
| Intel                    | 24       | 23.53%  |
| Nvidia                   | 14       | 13.73%  |
| Broadcom                 | 9        | 8.82%   |
| Qualcomm Atheros         | 4        | 3.92%   |
| VIA Technologies         | 2        | 1.96%   |
| Marvell Technology Group | 2        | 1.96%   |
| Broadcom Limited         | 2        | 1.96%   |
| 3Com                     | 2        | 1.96%   |
| Xiaomi                   | 1        | 0.98%   |
| ADMtek                   | 1        | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 25.24%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 7.77%   |
| Nvidia MCP61 Ethernet                                             | 7        | 6.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 4.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.88%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3        | 2.91%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 2.91%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 1.94%   |
| Nvidia MCP79 Ethernet                                             | 2        | 1.94%   |
| Nvidia MCP73 Ethernet                                             | 2        | 1.94%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.94%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.94%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 1.94%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 1.94%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2        | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.97%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.97%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.97%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.97%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.97%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.97%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.97%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.97%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.97%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.97%   |
| Intel 82567LM-2 Gigabit Network Connection                        | 1        | 0.97%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.97%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.97%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.97%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.97%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 63.51%  |
| WiFi     | 52       | 35.14%  |
| Modem    | 1        | 0.68%   |
| Unknown  | 1        | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 59       | 62.77%  |
| WiFi     | 35       | 37.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 67.01%  |
| 2     | 27       | 27.84%  |
| 0     | 3        | 3.09%   |
| 3     | 2        | 2.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 90       | 92.78%  |
| Yes  | 7        | 7.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 9        | 47.37%  |
| Broadcom                        | 3        | 15.79%  |
| Qualcomm Atheros Communications | 2        | 10.53%  |
| ASUSTek Computer                | 2        | 10.53%  |
| Primax Electronics              | 1        | 5.26%   |
| Kensington                      | 1        | 5.26%   |
| Intel                           | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 47.37%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 10.53%  |
| ASUS Bluetooth Radio                                | 2        | 10.53%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 5.26%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5.26%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1        | 5.26%   |
| Kensington Bluetooth EDR Dongle                     | 1        | 5.26%   |
| Intel AX200 Bluetooth                               | 1        | 5.26%   |
| Broadcom Bluetooth Controller                       | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 57       | 42.22%  |
| Nvidia                                          | 28       | 20.74%  |
| AMD                                             | 27       | 20%     |
| C-Media Electronics                             | 7        | 5.19%   |
| Creative Labs                                   | 6        | 4.44%   |
| VIA Technologies                                | 4        | 2.96%   |
| ULi Electronics                                 | 1        | 0.74%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.74%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.74%   |
| Generalplus Technology                          | 1        | 0.74%   |
| Creative Technology                             | 1        | 0.74%   |
| Corsair                                         | 1        | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 9.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 4.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 4.64%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 3.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 3.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 2.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 2.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 2.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4        | 2.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 2.65%   |
| AMD FCH Azalia Controller                                                  | 4        | 2.65%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 3        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.99%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.99%   |
| Nvidia MCP79 High Definition Audio                                         | 2        | 1.32%   |
| Nvidia MCP73 High Definition Audio                                         | 2        | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.32%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2        | 1.32%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 2        | 1.32%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 1.32%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 1.32%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 1.32%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.66%   |
| ULi Electronics HD Audio Controller                                        | 1        | 0.66%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 0.66%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.66%   |
| Nvidia MCP51 High Definition Audio                                         | 1        | 0.66%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.66%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 23.81%  |
| Micron Technology   | 4        | 19.05%  |
| Samsung Electronics | 3        | 14.29%  |
| SK hynix            | 2        | 9.52%   |
| Nanya Technology    | 2        | 9.52%   |
| Kingston            | 1        | 4.76%   |
| Goldkey             | 1        | 4.76%   |
| G.Skill             | 1        | 4.76%   |
| Crucial             | 1        | 4.76%   |
| Unknown             | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 2        | 8.33%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s             | 2        | 8.33%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM DDR2                        | 1        | 4.17%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 4.17%   |
| Unknown RAM Module 1GB DIMM DDR2                        | 1        | 4.17%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 4.17%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s                | 1        | 4.17%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s              | 1        | 4.17%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 4.17%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s            | 1        | 4.17%   |
| Samsung RAM M378B2873FHS-CH9 1GB DIMM 1600MT/s          | 1        | 4.17%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s      | 1        | 4.17%   |
| Nanya RAM NT1GT64UH8D0FN-AD 1GB DIMM DDR2 2048MT/s      | 1        | 4.17%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 1        | 4.17%   |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s      | 1        | 4.17%   |
| Kingston RAM 9905734-019.A00G 16GB DIMM DDR4 2400MT/s   | 1        | 4.17%   |
| Kingston RAM 9905713-017.A00G 4GB DIMM DDR4 2866MT/s    | 1        | 4.17%   |
| Goldkey RAM GKE400SO51208-2400 4GB SODIMM DDR4 2400MT/s | 1        | 4.17%   |
| G.Skill RAM F3-1866C10-8GAB 8GB DIMM DDR3 1867MT/s      | 1        | 4.17%   |
| Crucial RAM BLS8G3D18ADS3 8GB DIMM DDR3 1866MT/s        | 1        | 4.17%   |
| Unknown                                                 | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 40%     |
| DDR2    | 4        | 20%     |
| Unknown | 3        | 15%     |
| SDRAM   | 2        | 10%     |
| DDR4    | 2        | 10%     |
| DDR     | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 94.74%  |
| SODIMM | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 7        | 31.82%  |
| 1024  | 7        | 31.82%  |
| 4096  | 5        | 22.73%  |
| 8192  | 2        | 9.09%   |
| 16384 | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 20%     |
| 1333    | 3        | 15%     |
| 2400    | 2        | 10%     |
| 800     | 2        | 10%     |
| 41632   | 1        | 5%      |
| 2866    | 1        | 5%      |
| 2048    | 1        | 5%      |
| 1867    | 1        | 5%      |
| 1866    | 1        | 5%      |
| 1066    | 1        | 5%      |
| 533     | 1        | 5%      |
| 320     | 1        | 5%      |
| Unknown | 1        | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 3        | 37.5%   |
| Hewlett-Packard     | 2        | 25%     |
| Seiko Epson         | 1        | 12.5%   |
| Samsung Electronics | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson XP-243 245 247 Series    | 1        | 12.5%   |
| Samsung ML-216x Series Laser Printer | 1        | 12.5%   |
| HP OfficeJet 5200 series             | 1        | 12.5%   |
| HP DeskJet 1220C                     | 1        | 12.5%   |
| Canon TS3300 series                  | 1        | 12.5%   |
| Brother HL-L2360D series             | 1        | 12.5%   |
| Brother HL-L2350DW series            | 1        | 12.5%   |
| Brother HL-L2340D series             | 1        | 12.5%   |

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
| Logitech                      | 2        | 22.22%  |
| Cubeternet                    | 2        | 22.22%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| Samsung Electronics           | 1        | 11.11%  |
| LG Electronics                | 1        | 11.11%  |
| GEO Semi                      | 1        | 11.11%  |
| Aveo Technology               | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sunplus SPCA2281 Web Camera                                         | 1        | 11.11%  |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 11.11%  |
| Logitech Webcam C270                                                | 1        | 11.11%  |
| Logitech Webcam C210                                                | 1        | 11.11%  |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)               | 1        | 11.11%  |
| GEO Semi Condor                                                     | 1        | 11.11%  |
| Cubeternet USB2.0 Camera                                            | 1        | 11.11%  |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 11.11%  |
| Aveo Camera                                                         | 1        | 11.11%  |

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
| 0     | 76       | 76%     |
| 1     | 21       | 21%     |
| 2     | 3        | 3%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 29.63%  |
| Communication controller | 8        | 29.63%  |
| Graphics card            | 6        | 22.22%  |
| Camera                   | 2        | 7.41%   |
| Unassigned class         | 1        | 3.7%    |
| Sound                    | 1        | 3.7%    |
| Net/ethernet             | 1        | 3.7%    |

