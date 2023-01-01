Peppermint 10 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Peppermint 10.

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

Total: 126

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B450-I GAMING  | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING  | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING  | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING  | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASUSTek       | M5A78L-M LE              | [a7209bb34a](https://linux-hardware.org/?probe=a7209bb34a) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE              | [5f7c38d0d5](https://linux-hardware.org/?probe=5f7c38d0d5) | Jan 22, 2022 |
| Intel         | D865GSA AAD52278-203     | [9b874becf9](https://linux-hardware.org/?probe=9b874becf9) | Dec 01, 2021 |
| Intel         | D865GSA AAD52278-203     | [ae2963be56](https://linux-hardware.org/?probe=ae2963be56) | Dec 01, 2021 |
| ECS           | Nettle3                  | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| ASUSTek       | P5GC-MX/1333             | [def67fa4e7](https://linux-hardware.org/?probe=def67fa4e7) | Nov 16, 2021 |
| Intel         | H61                      | [f1d3a975c0](https://linux-hardware.org/?probe=f1d3a975c0) | Oct 26, 2021 |
| ECS           | MCP61PM-GM               | [1d13b80285](https://linux-hardware.org/?probe=1d13b80285) | Oct 13, 2021 |
| ASRock        | P4VM8                    | [5797c27ef8](https://linux-hardware.org/?probe=5797c27ef8) | Oct 10, 2021 |
| ASRock        | P4VM8                    | [84c50aca4b](https://linux-hardware.org/?probe=84c50aca4b) | Oct 10, 2021 |
| AAEON         | MF-001 V1.0              | [c5492b6d2f](https://linux-hardware.org/?probe=c5492b6d2f) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0              | [522a137a4e](https://linux-hardware.org/?probe=522a137a4e) | Oct 05, 2021 |
| MSI           | MS-7211                  | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| ASUSTek       | A88XM-A                  | [b1f8d57cae](https://linux-hardware.org/?probe=b1f8d57cae) | Sep 09, 2021 |
| HP            | 2AE3                     | [6780c45f7c](https://linux-hardware.org/?probe=6780c45f7c) | Aug 02, 2021 |
| Pegatron      | 2ACC                     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASRock        | 970M Pro3                | [9c2c0af05f](https://linux-hardware.org/?probe=9c2c0af05f) | May 27, 2021 |
| ASRock        | 970M Pro3                | [0a5e45a21e](https://linux-hardware.org/?probe=0a5e45a21e) | May 27, 2021 |
| Pegatron      | Benicia                  | [7b1f7c7edf](https://linux-hardware.org/?probe=7b1f7c7edf) | Apr 15, 2021 |
| ASUSTek       | P4VP-MX                  | [ce116189a9](https://linux-hardware.org/?probe=ce116189a9) | Mar 19, 2021 |
| ASUSTek       | P4VP-MX                  | [1f7de7a842](https://linux-hardware.org/?probe=1f7de7a842) | Mar 19, 2021 |
| ASUSTek       | Acacia                   | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Gateway       | MCP61SM2MA FAB1.0        | [efab4d96e9](https://linux-hardware.org/?probe=efab4d96e9) | Mar 10, 2021 |
| Gateway       | MCP61SM2MA FAB1.0        | [514d4c99a1](https://linux-hardware.org/?probe=514d4c99a1) | Mar 10, 2021 |
| Dell          | Dimension E521           | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | 0C522T A01               | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| HP            | 3032h                    | [50914ba2f5](https://linux-hardware.org/?probe=50914ba2f5) | Mar 04, 2021 |
| ASUSTek       | P5N-E SLI                | [236a4d5753](https://linux-hardware.org/?probe=236a4d5753) | Feb 23, 2021 |
| ASUSTek       | P5N-E SLI                | [27f148966a](https://linux-hardware.org/?probe=27f148966a) | Feb 23, 2021 |
| Dell          | Dimension E521           | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Dimension E521           | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
| ASUSTek       | SABERTOOTH Z77           | [f7fc4d663b](https://linux-hardware.org/?probe=f7fc4d663b) | Feb 08, 2021 |
| Dell          | 0TP406                   | [0980bfcfe9](https://linux-hardware.org/?probe=0980bfcfe9) | Jan 28, 2021 |
| Dell          | 0K216C                   | [c1cf70d814](https://linux-hardware.org/?probe=c1cf70d814) | Jan 19, 2021 |
| Gigabyte      | 945GCM-S2L               | [b0f061dfba](https://linux-hardware.org/?probe=b0f061dfba) | Jan 08, 2021 |
| Gigabyte      | 945GCM-S2L               | [da98de1775](https://linux-hardware.org/?probe=da98de1775) | Jan 08, 2021 |
| ASUSTek       | ROG Maximus X HERO       | [5494aa2859](https://linux-hardware.org/?probe=5494aa2859) | Jan 04, 2021 |
| HP            | 3032h                    | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| MSI           | MS-7211                  | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Dell          | 0T656F A02               | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Nvidia        | MCP7A 2                  | [c18fd136a9](https://linux-hardware.org/?probe=c18fd136a9) | Nov 24, 2020 |
| ASUSTek       | P5G41T-M LE              | [ff9f1e3bc5](https://linux-hardware.org/?probe=ff9f1e3bc5) | Nov 22, 2020 |
| ASUSTek       | P5G41T-M LE              | [41517af8ad](https://linux-hardware.org/?probe=41517af8ad) | Nov 22, 2020 |
| Gigabyte      | J1800M-D3P               | [9ab6ea275f](https://linux-hardware.org/?probe=9ab6ea275f) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | J1800M-D3P               | [ae71ad880b](https://linux-hardware.org/?probe=ae71ad880b) | Nov 10, 2020 |
| ASUSTek       | A88XM-A                  | [c02b06f51f](https://linux-hardware.org/?probe=c02b06f51f) | Oct 31, 2020 |
| Dell          | 0C2KJT A00               | [37cf119697](https://linux-hardware.org/?probe=37cf119697) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                  | [d822785861](https://linux-hardware.org/?probe=d822785861) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                  | [b0a785eecd](https://linux-hardware.org/?probe=b0a785eecd) | Sep 30, 2020 |
| Intel         | 945GCT-M                 | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                 | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Dell          | 09KPNV A00               | [7a9366d7a0](https://linux-hardware.org/?probe=7a9366d7a0) | Sep 04, 2020 |
| HP            | 8265                     | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| HP            | 0A54h                    | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| ASRock        | N68-S3 FX                | [cbf919cfd5](https://linux-hardware.org/?probe=cbf919cfd5) | Jul 30, 2020 |
| HP            | 18E7                     | [4b13141bdb](https://linux-hardware.org/?probe=4b13141bdb) | Jul 30, 2020 |
| Gigabyte      | 990FXA-UD3               | [dc82f8cf6b](https://linux-hardware.org/?probe=dc82f8cf6b) | Jul 15, 2020 |
| MSI           | MS-7211                  | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                  | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Gigabyte      | 990XA-UD3                | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| ASUSTek       | K8N4-E Deluxe            | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Fujitsu       | D3171-A1 S26361-D3171-A1 | [a514be4e22](https://linux-hardware.org/?probe=a514be4e22) | Jun 06, 2020 |
| MSI           | MS-7267                  | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Dell          | 02YRK5 A02               | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Dell          | 02YRK5 A02               | [4fa188ca3e](https://linux-hardware.org/?probe=4fa188ca3e) | May 15, 2020 |
| ECS           | Alhena5                  | [be2ff7b4dc](https://linux-hardware.org/?probe=be2ff7b4dc) | May 15, 2020 |
| Gigabyte      | 990FXA-UD3               | [a0112b2478](https://linux-hardware.org/?probe=a0112b2478) | May 14, 2020 |
| Gigabyte      | Z87X-UD5H-CF             | [39798ff3d6](https://linux-hardware.org/?probe=39798ff3d6) | May 05, 2020 |
| ASUSTek       | Amberine M               | [c948d7fd76](https://linux-hardware.org/?probe=c948d7fd76) | Apr 29, 2020 |
| ASUSTek       | Amberine M               | [595c810650](https://linux-hardware.org/?probe=595c810650) | Apr 29, 2020 |
| ASUSTek       | Amberine M               | [f1fc9b4580](https://linux-hardware.org/?probe=f1fc9b4580) | Apr 29, 2020 |
| Gigabyte      | EQ45M-S2                 | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                 | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Dell          | 0Y958C A00               | [131e2c31a9](https://linux-hardware.org/?probe=131e2c31a9) | Apr 26, 2020 |
| ASUSTek       | M3A78-EM                 | [f9944d9361](https://linux-hardware.org/?probe=f9944d9361) | Apr 25, 2020 |
| Dell          | 0WF810                   | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| Gigabyte      | VM900M                   | [8554ccddc2](https://linux-hardware.org/?probe=8554ccddc2) | Apr 03, 2020 |
| HP            | 0A5Ch                    | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                    | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Unknown       | G41 Series               | [597b5edb76](https://linux-hardware.org/?probe=597b5edb76) | Mar 20, 2020 |
| HP            | 0AA8h                    | [881008d596](https://linux-hardware.org/?probe=881008d596) | Mar 11, 2020 |
| Acer          | MCP73PV NVIDIA MCP73     | [97b8e03710](https://linux-hardware.org/?probe=97b8e03710) | Mar 04, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3         | [8b516d50ef](https://linux-hardware.org/?probe=8b516d50ef) | Mar 03, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3         | [c67fe8542c](https://linux-hardware.org/?probe=c67fe8542c) | Mar 01, 2020 |
| ECS           | Alhena5                  | [89c17f438e](https://linux-hardware.org/?probe=89c17f438e) | Feb 28, 2020 |
| Fujitsu Si... | D1931 S26361-D1931       | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| Fujitsu Si... | D1931 S26361-D1931       | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931       | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| HP            | 0AA8h                    | [c5721d223f](https://linux-hardware.org/?probe=c5721d223f) | Feb 05, 2020 |
| Lenovo        | 31900058 STD             | [4d8db6ee1f](https://linux-hardware.org/?probe=4d8db6ee1f) | Jan 22, 2020 |
| Lenovo        | 31900058 STD             | [6320c5f50f](https://linux-hardware.org/?probe=6320c5f50f) | Jan 22, 2020 |
| ASUSTek       | P8H61-MX                 | [c7c5cc3339](https://linux-hardware.org/?probe=c7c5cc3339) | Jan 17, 2020 |
| ASUSTek       | P8H61-MX                 | [4e6cff6c0e](https://linux-hardware.org/?probe=4e6cff6c0e) | Jan 17, 2020 |
| Gigabyte      | F2A55M-HD2               | [75648daef1](https://linux-hardware.org/?probe=75648daef1) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408      | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASUSTek       | P5SD2-VM                 | [db8eaef3e7](https://linux-hardware.org/?probe=db8eaef3e7) | Jan 09, 2020 |
| Gigabyte      | P35-DS3R                 | [847cb4544c](https://linux-hardware.org/?probe=847cb4544c) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                 | [cf7e7bc433](https://linux-hardware.org/?probe=cf7e7bc433) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                 | [d7442beee0](https://linux-hardware.org/?probe=d7442beee0) | Dec 23, 2019 |
| HP            | 0A54h                    | [3a37dfd543](https://linux-hardware.org/?probe=3a37dfd543) | Dec 05, 2019 |
| Gigabyte      | F2A55M-HD2               | [f30cd368d8](https://linux-hardware.org/?probe=f30cd368d8) | Dec 02, 2019 |
| Gigabyte      | F2A55M-HD2               | [86b1a4acd7](https://linux-hardware.org/?probe=86b1a4acd7) | Dec 02, 2019 |
| Intel         | D945GCLF2 AAE46416-106   | [f2817e5306](https://linux-hardware.org/?probe=f2817e5306) | Nov 29, 2019 |
| Biostar       | A68N-5600E               | [d91042148c](https://linux-hardware.org/?probe=d91042148c) | Nov 27, 2019 |
| Gigabyte      | F2A55M-HD2               | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                  | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Dell          | 042P49 A01               | [b7c0226ab5](https://linux-hardware.org/?probe=b7c0226ab5) | Nov 10, 2019 |
| ASUSTek       | X99-A/USB                | [40ea4505b9](https://linux-hardware.org/?probe=40ea4505b9) | Nov 09, 2019 |
| eMachines     | EL1850                   | [c2b6c642fb](https://linux-hardware.org/?probe=c2b6c642fb) | Nov 09, 2019 |
| Lenovo        | 31900058 STD             | [ee0395fcb1](https://linux-hardware.org/?probe=ee0395fcb1) | Oct 25, 2019 |
| Gigabyte      | H61M-S1                  | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                  | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                  | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                  | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| ASUSTek       | K8N4-E Deluxe            | [dee3d2bdaa](https://linux-hardware.org/?probe=dee3d2bdaa) | Sep 04, 2019 |
| ASUSTek       | K8N4-E Deluxe            | [cfaaae942a](https://linux-hardware.org/?probe=cfaaae942a) | Aug 27, 2019 |
| Foxconn       | 2AB7                     | [f1f1f7133a](https://linux-hardware.org/?probe=f1f1f7133a) | Aug 18, 2019 |
| ASUSTek       | P5K-VM                   | [e2d3942d30](https://linux-hardware.org/?probe=e2d3942d30) | Jul 25, 2019 |
| Intel         | DX58SO AAE29331-702      | [d1b680dc39](https://linux-hardware.org/?probe=d1b680dc39) | Jul 05, 2019 |
| Dell          | 0C2KJT A00               | [986146d6eb](https://linux-hardware.org/?probe=986146d6eb) | Jul 01, 2019 |
| Dell          | 0C2KJT A00               | [ee64cbe6b5](https://linux-hardware.org/?probe=ee64cbe6b5) | Jun 28, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.0.0-37-generic     | 15       | 16.48%  |
| 5.3.0-46-generic     | 4        | 4.4%    |
| 5.0.0-36-generic     | 4        | 4.4%    |
| 5.4.0-87-generic     | 3        | 3.3%    |
| 5.4.0-66-generic     | 3        | 3.3%    |
| 5.4.0-52-generic     | 3        | 3.3%    |
| 5.4.0-42-generic     | 3        | 3.3%    |
| 5.3.0-51-generic     | 3        | 3.3%    |
| 5.3.0-40-generic     | 3        | 3.3%    |
| 5.0.0-32-generic     | 3        | 3.3%    |
| 4.18.0-25-generic    | 3        | 3.3%    |
| 4.18.0-18-generic    | 3        | 3.3%    |
| 5.4.0-67-generic     | 2        | 2.2%    |
| 5.4.0-58-generic     | 2        | 2.2%    |
| 5.4.0-54-generic     | 2        | 2.2%    |
| 5.4.0-48-generic     | 2        | 2.2%    |
| 5.3.0-59-generic     | 2        | 2.2%    |
| 5.3.0-28-generic     | 2        | 2.2%    |
| 5.0.0-29-generic     | 2        | 2.2%    |
| 5.0.0-25-generic     | 2        | 2.2%    |
| 5.7.1-050701-generic | 1        | 1.1%    |
| 5.6.7-050607-generic | 1        | 1.1%    |
| 5.4.0-96-generic     | 1        | 1.1%    |
| 5.4.0-91-generic     | 1        | 1.1%    |
| 5.4.0-90-generic     | 1        | 1.1%    |
| 5.4.0-89-generic     | 1        | 1.1%    |
| 5.4.0-81-generic     | 1        | 1.1%    |
| 5.4.0-80-generic     | 1        | 1.1%    |
| 5.4.0-70-generic     | 1        | 1.1%    |
| 5.4.0-65-generic     | 1        | 1.1%    |
| 5.4.0-62-generic     | 1        | 1.1%    |
| 5.4.0-60-generic     | 1        | 1.1%    |
| 5.4.0-56-generic     | 1        | 1.1%    |
| 5.4.0-49-generic     | 1        | 1.1%    |
| 5.4.0-45-generic     | 1        | 1.1%    |
| 5.4.0-125-generic    | 1        | 1.1%    |
| 5.4.0-113-generic    | 1        | 1.1%    |
| 5.4.0-105-generic    | 1        | 1.1%    |
| 5.3.9-050309-generic | 1        | 1.1%    |
| 5.3.6-050306-generic | 1        | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 38.1%   |
| 5.0.0   | 25       | 29.76%  |
| 5.3.0   | 17       | 20.24%  |
| 4.18.0  | 6        | 7.14%   |
| 5.7.1   | 1        | 1.19%   |
| 5.6.7   | 1        | 1.19%   |
| 5.3.9   | 1        | 1.19%   |
| 5.3.6   | 1        | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 38.1%   |
| 5.0     | 25       | 29.76%  |
| 5.3     | 19       | 22.62%  |
| 4.18    | 6        | 7.14%   |
| 5.7     | 1        | 1.19%   |
| 5.6     | 1        | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 55       | 68.75%  |
| i686   | 25       | 31.25%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LXDE    | 65       | 80.25%  |
| Unknown | 13       | 16.05%  |
| GNOME   | 3        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 79       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 72       | 88.89%  |
| LightDM | 5        | 6.17%   |
| TDM     | 4        | 4.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 32.93%  |
| Unknown | 11       | 13.41%  |
| it_IT   | 7        | 8.54%   |
| pt_BR   | 5        | 6.1%    |
| de_DE   | 5        | 6.1%    |
| en_IN   | 4        | 4.88%   |
| en_GB   | 4        | 4.88%   |
| ru_RU   | 2        | 2.44%   |
| fi_FI   | 2        | 2.44%   |
| C       | 2        | 2.44%   |
| ro_RO   | 1        | 1.22%   |
| pl_PL   | 1        | 1.22%   |
| fr_FR   | 1        | 1.22%   |
| es_PE   | 1        | 1.22%   |
| es_MX   | 1        | 1.22%   |
| es_ES   | 1        | 1.22%   |
| es_EC   | 1        | 1.22%   |
| es_AR   | 1        | 1.22%   |
| en_PH   | 1        | 1.22%   |
| en_NZ   | 1        | 1.22%   |
| en_IE   | 1        | 1.22%   |
| en_CA   | 1        | 1.22%   |
| en_AU   | 1        | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 69       | 86.25%  |
| EFI  | 11       | 13.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 70       | 85.37%  |
| Unknown | 8        | 9.76%   |
| Overlay | 2        | 2.44%   |
| Xfs     | 1        | 1.22%   |
| Ext2    | 1        | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 76       | 96.2%   |
| GPT     | 2        | 2.53%   |
| MBR     | 1        | 1.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 90%     |
| Yes       | 8        | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 84.81%  |
| Yes       | 12       | 15.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 22.78%  |
| Gigabyte Technology | 11       | 13.92%  |
| Dell                | 11       | 13.92%  |
| Hewlett-Packard     | 9        | 11.39%  |
| Intel               | 6        | 7.59%   |
| ECS                 | 3        | 3.8%    |
| ASRock              | 3        | 3.8%    |
| Pegatron            | 2        | 2.53%   |
| MSI                 | 2        | 2.53%   |
| Fujitsu Siemens     | 2        | 2.53%   |
| eMachines           | 2        | 2.53%   |
| Acer                | 2        | 2.53%   |
| Nvidia              | 1        | 1.27%   |
| Lenovo              | 1        | 1.27%   |
| Gateway             | 1        | 1.27%   |
| Fujitsu             | 1        | 1.27%   |
| Foxconn             | 1        | 1.27%   |
| Biostar             | 1        | 1.27%   |
| AAEON               | 1        | 1.27%   |
| Unknown             | 1        | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP Compaq dc7900 Convertible Minitower | 2        | 2.53%   |
| Fujitsu Siemens D1931                  | 2        | 2.53%   |
| Pegatron FR502AA-ABZ m9355.it          | 1        | 1.27%   |
| Pegatron CQ1506LA                      | 1        | 1.27%   |
| Nvidia MCP7A                           | 1        | 1.27%   |
| MSI MS-7267                            | 1        | 1.27%   |
| MSI MS-7211                            | 1        | 1.27%   |
| Lenovo IdeaCentre Q190 10115           | 1        | 1.27%   |
| Intel H61                              | 1        | 1.27%   |
| Intel Energy Systems                   | 1        | 1.27%   |
| Intel DP55WG AAE57269-408              | 1        | 1.27%   |
| Intel D945GCLF2 AAE46416-106           | 1        | 1.27%   |
| Intel D865GSA AAD52278-203             | 1        | 1.27%   |
| Intel 945GCT-M                         | 1        | 1.27%   |
| HP ProDesk 600 G1 SFF                  | 1        | 1.27%   |
| HP EliteDesk 705 G3 MT                 | 1        | 1.27%   |
| HP CQ2930EA                            | 1        | 1.27%   |
| HP Compaq dc7800 Small Form Factor     | 1        | 1.27%   |
| HP Compaq dc7700p Small Form Factor    | 1        | 1.27%   |
| HP Compaq dc7700 Ultra-slim Desktop    | 1        | 1.27%   |
| HP Compaq dc7700 Small Form Factor     | 1        | 1.27%   |
| Gigabyte Z87X-UD5H                     | 1        | 1.27%   |
| Gigabyte P35-DS3R                      | 1        | 1.27%   |
| Gigabyte J1800M-D3P                    | 1        | 1.27%   |
| Gigabyte H61M-S1                       | 1        | 1.27%   |
| Gigabyte GA-VM900M                     | 1        | 1.27%   |
| Gigabyte F2A55M-HD2                    | 1        | 1.27%   |
| Gigabyte EQ45M-S2                      | 1        | 1.27%   |
| Gigabyte B450M S2H                     | 1        | 1.27%   |
| Gigabyte 990XA-UD3                     | 1        | 1.27%   |
| Gigabyte 990FXA-UD3                    | 1        | 1.27%   |
| Gigabyte 945GCM-S2L                    | 1        | 1.27%   |
| Gateway T5246                          | 1        | 1.27%   |
| Fujitsu ESPRIMO P510                   | 1        | 1.27%   |
| Foxconn s5610f                         | 1        | 1.27%   |
| eMachines EL1850                       | 1        | 1.27%   |
| eMachines EL1600                       | 1        | 1.27%   |
| ECS RR493AA-ABE SR2109ES               | 1        | 1.27%   |
| ECS NC686AA-ABA a6700y                 | 1        | 1.27%   |
| ECS ET1161-03                          | 1        | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 6        | 7.59%   |
| Dell OptiPlex         | 5        | 6.33%   |
| Dell Inspiron         | 3        | 3.8%    |
| Fujitsu Siemens D1931 | 2        | 2.53%   |
| ASUS ROG              | 2        | 2.53%   |
| Acer Aspire           | 2        | 2.53%   |
| Pegatron FR502AA-ABZ  | 1        | 1.27%   |
| Pegatron CQ1506LA     | 1        | 1.27%   |
| Nvidia MCP7A          | 1        | 1.27%   |
| MSI MS-7267           | 1        | 1.27%   |
| MSI MS-7211           | 1        | 1.27%   |
| Lenovo IdeaCentre     | 1        | 1.27%   |
| Intel H61             | 1        | 1.27%   |
| Intel Energy          | 1        | 1.27%   |
| Intel DP55WG          | 1        | 1.27%   |
| Intel D945GCLF2       | 1        | 1.27%   |
| Intel D865GSA         | 1        | 1.27%   |
| Intel 945GCT-M        | 1        | 1.27%   |
| HP ProDesk            | 1        | 1.27%   |
| HP EliteDesk          | 1        | 1.27%   |
| HP CQ2930EA           | 1        | 1.27%   |
| Gigabyte Z87X-UD5H    | 1        | 1.27%   |
| Gigabyte P35-DS3R     | 1        | 1.27%   |
| Gigabyte J1800M-D3P   | 1        | 1.27%   |
| Gigabyte H61M-S1      | 1        | 1.27%   |
| Gigabyte GA-VM900M    | 1        | 1.27%   |
| Gigabyte F2A55M-HD2   | 1        | 1.27%   |
| Gigabyte EQ45M-S2     | 1        | 1.27%   |
| Gigabyte B450M        | 1        | 1.27%   |
| Gigabyte 990XA-UD3    | 1        | 1.27%   |
| Gigabyte 990FXA-UD3   | 1        | 1.27%   |
| Gigabyte 945GCM-S2L   | 1        | 1.27%   |
| Gateway T5246         | 1        | 1.27%   |
| Fujitsu ESPRIMO       | 1        | 1.27%   |
| Foxconn s5610f        | 1        | 1.27%   |
| eMachines EL1850      | 1        | 1.27%   |
| eMachines EL1600      | 1        | 1.27%   |
| ECS RR493AA-ABE       | 1        | 1.27%   |
| ECS NC686AA-ABA       | 1        | 1.27%   |
| ECS ET1161-03         | 1        | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 14       | 17.72%  |
| 2008 | 9        | 11.39%  |
| 2013 | 8        | 10.13%  |
| 2006 | 7        | 8.86%   |
| 2011 | 6        | 7.59%   |
| 2010 | 6        | 7.59%   |
| 2012 | 5        | 6.33%   |
| 2009 | 5        | 6.33%   |
| 2005 | 5        | 6.33%   |
| 2019 | 3        | 3.8%    |
| 2015 | 3        | 3.8%    |
| 2018 | 2        | 2.53%   |
| 2017 | 2        | 2.53%   |
| 2004 | 2        | 2.53%   |
| 2020 | 1        | 1.27%   |
| 2014 | 1        | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 79       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 78       | 98.73%  |
| Enabled  | 1        | 1.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 79       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 26       | 31.71%  |
| 1.01-2.0   | 20       | 24.39%  |
| 8.01-16.0  | 11       | 13.41%  |
| 4.01-8.0   | 6        | 7.32%   |
| 2.01-3.0   | 6        | 7.32%   |
| 16.01-24.0 | 6        | 7.32%   |
| 32.01-64.0 | 3        | 3.66%   |
| 0.51-1.0   | 3        | 3.66%   |
| 24.01-32.0 | 1        | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 37       | 42.53%  |
| 1.01-2.0  | 32       | 36.78%  |
| 2.01-3.0  | 6        | 6.9%    |
| 0.01-0.5  | 4        | 4.6%    |
| 4.01-8.0  | 3        | 3.45%   |
| 3.01-4.0  | 3        | 3.45%   |
| 8.01-16.0 | 2        | 2.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 61.73%  |
| 2      | 20       | 24.69%  |
| 3      | 7        | 8.64%   |
| 7      | 1        | 1.23%   |
| 6      | 1        | 1.23%   |
| 5      | 1        | 1.23%   |
| 4      | 1        | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 68.75%  |
| No        | 25       | 31.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 97.47%  |
| No        | 2        | 2.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 44       | 55.7%   |
| No        | 35       | 44.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 78.48%  |
| Yes       | 17       | 21.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 26       | 32.5%   |
| Italy       | 7        | 8.75%   |
| Germany     | 6        | 7.5%    |
| India       | 5        | 6.25%   |
| Brazil      | 5        | 6.25%   |
| UK          | 4        | 5%      |
| Finland     | 3        | 3.75%   |
| Russia      | 2        | 2.5%    |
| Romania     | 2        | 2.5%    |
| Canada      | 2        | 2.5%    |
| Argentina   | 2        | 2.5%    |
| Ukraine     | 1        | 1.25%   |
| Sweden      | 1        | 1.25%   |
| Spain       | 1        | 1.25%   |
| Portugal    | 1        | 1.25%   |
| Poland      | 1        | 1.25%   |
| Philippines | 1        | 1.25%   |
| Peru        | 1        | 1.25%   |
| New Zealand | 1        | 1.25%   |
| Netherlands | 1        | 1.25%   |
| Mexico      | 1        | 1.25%   |
| Ireland     | 1        | 1.25%   |
| Greece      | 1        | 1.25%   |
| Ecuador     | 1        | 1.25%   |
| Belgium     | 1        | 1.25%   |
| Australia   | 1        | 1.25%   |
| Algeria     | 1        | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Villingen-Schwenningen | 3        | 3.66%   |
| Bengaluru              | 2        | 2.44%   |
| Wroclaw                | 1        | 1.22%   |
| Wassenaar              | 1        | 1.22%   |
| Washington             | 1        | 1.22%   |
| Vitória               | 1        | 1.22%   |
| Van Vleck              | 1        | 1.22%   |
| Turin                  | 1        | 1.22%   |
| Tsarskoye Selo         | 1        | 1.22%   |
| Thatcher               | 1        | 1.22%   |
| Taranto                | 1        | 1.22%   |
| Talala                 | 1        | 1.22%   |
| Tahlequah              | 1        | 1.22%   |
| Swidnica               | 1        | 1.22%   |
| Stockholm              | 1        | 1.22%   |
| Spokane                | 1        | 1.22%   |
| South Jordan           | 1        | 1.22%   |
| Seville                | 1        | 1.22%   |
| Seattle                | 1        | 1.22%   |
| Saratov                | 1        | 1.22%   |
| Santa Barbara          | 1        | 1.22%   |
| Sankt Augustin         | 1        | 1.22%   |
| Rock Hill              | 1        | 1.22%   |
| Roanoke                | 1        | 1.22%   |
| Rio de Janeiro         | 1        | 1.22%   |
| Rio                    | 1        | 1.22%   |
| Reggio Emilia          | 1        | 1.22%   |
| Quezon City            | 1        | 1.22%   |
| Pune                   | 1        | 1.22%   |
| Prevost                | 1        | 1.22%   |
| Popesti-Leordeni       | 1        | 1.22%   |
| Ponchatoula            | 1        | 1.22%   |
| Philadelphia           | 1        | 1.22%   |
| Perth                  | 1        | 1.22%   |
| Peristeri              | 1        | 1.22%   |
| Pensacola              | 1        | 1.22%   |
| Parral                 | 1        | 1.22%   |
| Oulu                   | 1        | 1.22%   |
| Nelson                 | 1        | 1.22%   |
| Mumbai                 | 1        | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 46     | 26.13%  |
| Seagate             | 20       | 22     | 18.02%  |
| Hitachi             | 15       | 22     | 13.51%  |
| Samsung Electronics | 14       | 19     | 12.61%  |
| Maxtor              | 8        | 10     | 7.21%   |
| Kingston            | 6        | 8      | 5.41%   |
| SanDisk             | 3        | 3      | 2.7%    |
| Toshiba             | 2        | 2      | 1.8%    |
| Intel               | 2        | 2      | 1.8%    |
| WD MediaMax         | 1        | 1      | 0.9%    |
| Unknown             | 1        | 1      | 0.9%    |
| PNY                 | 1        | 2      | 0.9%    |
| Phison Electronics  | 1        | 1      | 0.9%    |
| Phison              | 1        | 2      | 0.9%    |
| OCZ                 | 1        | 1      | 0.9%    |
| Intenso             | 1        | 1      | 0.9%    |
| GAMER               | 1        | 1      | 0.9%    |
| Fujitsu             | 1        | 1      | 0.9%    |
| Crucial             | 1        | 2      | 0.9%    |
| China               | 1        | 1      | 0.9%    |
| ASMT                | 1        | 1      | 0.9%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD  | 3        | 2.52%   |
| Hitachi HDT721016SLA380 160GB    | 3        | 2.52%   |
| Seagate ST3500418AS 500GB        | 2        | 1.68%   |
| Seagate ST3250310AS 250GB        | 2        | 1.68%   |
| Seagate ST3160813AS 160GB        | 2        | 1.68%   |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 1.68%   |
| SanDisk SDSSDA120G 120GB         | 2        | 1.68%   |
| Samsung SSD 860 EVO 1TB          | 2        | 1.68%   |
| Maxtor STM3160215AS 160GB        | 2        | 1.68%   |
| Hitachi HDS721050CLA362 500GB    | 2        | 1.68%   |
| Hitachi HDP725050GLA360 500GB    | 2        | 1.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.84%   |
| WDC WD800JD-75MSA1 80GB          | 1        | 0.84%   |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.84%   |
| WDC WD800JD-00MSA1 80GB          | 1        | 0.84%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.84%   |
| WDC WD5000LPVT-24G33T1 500GB     | 1        | 0.84%   |
| WDC WD5000AAKX-753CA1 500GB      | 1        | 0.84%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 0.84%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.84%   |
| WDC WD4000AAJS-00YFA0 400GB      | 1        | 0.84%   |
| WDC WD3200JS-22PDB0 320GB        | 1        | 0.84%   |
| WDC WD3200AVVS-63L2B0 320GB      | 1        | 0.84%   |
| WDC WD3200AVJB-63WKA0 320GB      | 1        | 0.84%   |
| WDC WD3200AAJS-56B4A0 320GB      | 1        | 0.84%   |
| WDC WD30EFZX-68AWUN0 3TB         | 1        | 0.84%   |
| WDC WD2500BEVT-22A23T0 250GB     | 1        | 0.84%   |
| WDC WD2500AVJB-63WKA0 250GB      | 1        | 0.84%   |
| WDC WD2500AAJS-75M0A0 249GB      | 1        | 0.84%   |
| WDC WD2500AAJS-00VTA0 250GB      | 1        | 0.84%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.84%   |
| WDC WD20EURS-63S48Y0 2TB         | 1        | 0.84%   |
| WDC WD2000JS-60NCB1 200GB        | 1        | 0.84%   |
| WDC WD1600JS-00NCB1 160GB        | 1        | 0.84%   |
| WDC WD1600AAJS-75M0A0 160GB      | 1        | 0.84%   |
| WDC WD1200BB-53DWA0 120GB        | 1        | 0.84%   |
| WDC WD10JPVX-08JC3T5 1TB         | 1        | 0.84%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 0.84%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 0.84%   |
| WDC WD10EURX-63C57Y0 1TB         | 1        | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 45     | 33.73%  |
| Seagate             | 20       | 22     | 24.1%   |
| Hitachi             | 15       | 22     | 18.07%  |
| Samsung Electronics | 8        | 11     | 9.64%   |
| Maxtor              | 8        | 10     | 9.64%   |
| Toshiba             | 2        | 2      | 2.41%   |
| WD MediaMax         | 1        | 1      | 1.2%    |
| Fujitsu             | 1        | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 8      | 26.09%  |
| Samsung Electronics | 5        | 7      | 21.74%  |
| SanDisk             | 3        | 3      | 13.04%  |
| Intel               | 2        | 2      | 8.7%    |
| WDC                 | 1        | 1      | 4.35%   |
| PNY                 | 1        | 2      | 4.35%   |
| OCZ                 | 1        | 1      | 4.35%   |
| GAMER               | 1        | 1      | 4.35%   |
| Crucial             | 1        | 2      | 4.35%   |
| China               | 1        | 1      | 4.35%   |
| ASMT                | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 66       | 114    | 70.97%  |
| SSD     | 23       | 29     | 24.73%  |
| NVMe    | 2        | 4      | 2.15%   |
| MMC     | 1        | 1      | 1.08%   |
| Unknown | 1        | 1      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 142    | 93.9%   |
| SAS  | 2        | 2      | 2.44%   |
| NVMe | 2        | 4      | 2.44%   |
| MMC  | 1        | 1      | 1.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 69       | 108    | 72.63%  |
| 0.51-1.0   | 19       | 24     | 20%     |
| 1.01-2.0   | 5        | 7      | 5.26%   |
| 2.01-3.0   | 1        | 3      | 1.05%   |
| 4.01-10.0  | 1        | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 34       | 40.96%  |
| 251-500        | 12       | 14.46%  |
| 501-1000       | 12       | 14.46%  |
| 51-100         | 10       | 12.05%  |
| 21-50          | 6        | 7.23%   |
| 1001-2000      | 4        | 4.82%   |
| Unknown        | 2        | 2.41%   |
| More than 3000 | 1        | 1.2%    |
| 2001-3000      | 1        | 1.2%    |
| 1-20           | 1        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 47       | 56.63%  |
| 21-50     | 17       | 20.48%  |
| 101-250   | 7        | 8.43%   |
| 51-100    | 6        | 7.23%   |
| 501-1000  | 2        | 2.41%   |
| Unknown   | 2        | 2.41%   |
| 251-500   | 1        | 1.2%    |
| 1001-2000 | 1        | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB | 1        | 1      | 50%     |
| Seagate ST31500341AS 1TB  | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 76       | 142    | 93.83%  |
| Works    | 3        | 5      | 3.7%    |
| Malfunc  | 2        | 2      | 2.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 47       | 51.65%  |
| AMD                              | 15       | 16.48%  |
| Nvidia                           | 10       | 10.99%  |
| JMicron Technology               | 5        | 5.49%   |
| VIA Technologies                 | 4        | 4.4%    |
| Marvell Technology Group         | 3        | 3.3%    |
| ULi Electronics                  | 1        | 1.1%    |
| Silicon Integrated Systems [SiS] | 1        | 1.1%    |
| Silicon Image                    | 1        | 1.1%    |
| Samsung Electronics              | 1        | 1.1%    |
| Phison Electronics               | 1        | 1.1%    |
| LSI Logic / Symbios Logic        | 1        | 1.1%    |
| ASMedia Technology               | 1        | 1.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10       | 7.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9        | 6.38%   |
| Nvidia MCP61 SATA Controller                                                   | 5        | 3.55%   |
| Nvidia MCP61 IDE                                                               | 5        | 3.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 3.55%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 3.55%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 4        | 2.84%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4        | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 2.84%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 4        | 2.84%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 2.13%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 3        | 2.13%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 3        | 2.13%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 2.13%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 2        | 1.42%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2        | 1.42%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 1.42%   |
| JMicron JMB368 IDE controller                                                  | 2        | 1.42%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 1.42%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                  | 2        | 1.42%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2        | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 1.42%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.42%   |
| VIA VT8237/8251 Serial ATA Controller                                          | 1        | 0.71%   |
| ULi ULi 5287 SATA                                                              | 1        | 0.71%   |
| ULi M5229 IDE                                                                  | 1        | 0.71%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 0.71%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 0.71%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.71%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.71%   |
| Nvidia MCP79 AHCI Controller                                                   | 1        | 0.71%   |
| Nvidia MCP73 SATA RAID Controller                                              | 1        | 0.71%   |
| Nvidia MCP73 IDE Controller                                                    | 1        | 0.71%   |
| Nvidia MCP51 IDE                                                               | 1        | 0.71%   |
| Nvidia CK804 Serial ATA Controller                                             | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 50       | 53.19%  |
| SATA | 34       | 36.17%  |
| RAID | 7        | 7.45%   |
| NVMe | 2        | 2.13%   |
| SAS  | 1        | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 73.42%  |
| AMD    | 21       | 26.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4        | 5.06%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 3.8%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 3.8%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 2.53%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.53%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2        | 2.53%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 2        | 2.53%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 2.53%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.27%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 1.27%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 1.27%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.27%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.27%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.27%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.27%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.27%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 1.27%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.27%   |
| Intel Pentium CPU G6960 @ 2.93GHz           | 1        | 1.27%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.27%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.27%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 1.27%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 1.27%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.27%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1        | 1.27%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.27%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.27%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.27%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.27%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.27%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.27%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.27%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 1        | 1.27%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 1.27%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 1.27%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.27%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 1        | 1.27%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1        | 1.27%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1        | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core 2 Quad       | 8        | 10.13%  |
| Intel Celeron           | 7        | 8.86%   |
| Intel Core i5           | 6        | 7.59%   |
| AMD Athlon 64 X2        | 6        | 7.59%   |
| Intel Pentium Dual-Core | 5        | 6.33%   |
| Intel Pentium 4         | 5        | 6.33%   |
| Intel Core 2 Duo        | 5        | 6.33%   |
| Intel Atom              | 4        | 5.06%   |
| Intel Xeon              | 3        | 3.8%    |
| Intel Pentium           | 3        | 3.8%    |
| Intel Core i7           | 3        | 3.8%    |
| Intel Core 2            | 3        | 3.8%    |
| Other                   | 2        | 2.53%   |
| Intel Pentium Dual      | 2        | 2.53%   |
| Intel Pentium D         | 2        | 2.53%   |
| Intel Core i3           | 2        | 2.53%   |
| AMD FX                  | 2        | 2.53%   |
| AMD Sempron             | 1        | 1.27%   |
| AMD Ryzen 5             | 1        | 1.27%   |
| AMD Ryzen 3             | 1        | 1.27%   |
| AMD Phenom II X4        | 1        | 1.27%   |
| AMD Phenom              | 1        | 1.27%   |
| AMD E1                  | 1        | 1.27%   |
| AMD Athlon II X4        | 1        | 1.27%   |
| AMD Athlon II X2        | 1        | 1.27%   |
| AMD Athlon 64           | 1        | 1.27%   |
| AMD A6                  | 1        | 1.27%   |
| AMD A4                  | 1        | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 35       | 44.3%   |
| 4      | 22       | 27.85%  |
| 1      | 17       | 21.52%  |
| 6      | 4        | 5.06%   |
| 3      | 1        | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 70.89%  |
| 2      | 23       | 29.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 69       | 86.25%  |
| Unknown        | 7        | 8.75%   |
| 32-bit         | 4        | 5%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 11       | 13.75%  |
| Unknown    | 11       | 13.75%  |
| 0xf41      | 4        | 5%      |
| 0x306a9    | 4        | 5%      |
| 0x6fd      | 3        | 3.75%   |
| 0x6fb      | 3        | 3.75%   |
| 0x206a7    | 3        | 3.75%   |
| 0x10661    | 3        | 3.75%   |
| 0x010000c8 | 3        | 3.75%   |
| 0x6f6      | 2        | 2.5%    |
| 0x306c3    | 2        | 2.5%    |
| 0x20655    | 2        | 2.5%    |
| 0x106c2    | 2        | 2.5%    |
| 0x06001119 | 2        | 2.5%    |
| 0xf65      | 1        | 1.25%   |
| 0xf62      | 1        | 1.25%   |
| 0xf47      | 1        | 1.25%   |
| 0xf43      | 1        | 1.25%   |
| 0xf33      | 1        | 1.25%   |
| 0x906ea    | 1        | 1.25%   |
| 0x6f2      | 1        | 1.25%   |
| 0x406c4    | 1        | 1.25%   |
| 0x306f2    | 1        | 1.25%   |
| 0x30678    | 1        | 1.25%   |
| 0x206c2    | 1        | 1.25%   |
| 0x20652    | 1        | 1.25%   |
| 0x106ca    | 1        | 1.25%   |
| 0x106a5    | 1        | 1.25%   |
| 0x10677    | 1        | 1.25%   |
| 0x10676    | 1        | 1.25%   |
| 0x0a50000b | 1        | 1.25%   |
| 0x08701013 | 1        | 1.25%   |
| 0x08108109 | 1        | 1.25%   |
| 0x07030106 | 1        | 1.25%   |
| 0x0600611a | 1        | 1.25%   |
| 0x06000852 | 1        | 1.25%   |
| 0x06000822 | 1        | 1.25%   |
| 0x05000119 | 1        | 1.25%   |
| 0x01000083 | 1        | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 14       | 17.72%  |
| Core        | 12       | 15.19%  |
| NetBurst    | 9        | 11.39%  |
| K8 Hammer   | 7        | 8.86%   |
| K10         | 5        | 6.33%   |
| IvyBridge   | 5        | 6.33%   |
| Westmere    | 4        | 5.06%   |
| Piledriver  | 4        | 5.06%   |
| Haswell     | 4        | 5.06%   |
| SandyBridge | 3        | 3.8%    |
| Bonnell     | 3        | 3.8%    |
| Silvermont  | 2        | 2.53%   |
| Zen+        | 1        | 1.27%   |
| Zen 2       | 1        | 1.27%   |
| Puma        | 1        | 1.27%   |
| Nehalem     | 1        | 1.27%   |
| KabyLake    | 1        | 1.27%   |
| Excavator   | 1        | 1.27%   |
| Bobcat      | 1        | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 32       | 39.02%  |
| Nvidia           | 24       | 29.27%  |
| AMD              | 24       | 29.27%  |
| VIA Technologies | 2        | 2.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 7.14%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 5        | 5.95%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 3.57%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 3.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 2.38%   |
| Nvidia G94 [GeForce 9600 GS]                                                             | 2        | 2.38%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 2        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 2.38%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 2.38%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 2        | 2.38%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 2.38%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1        | 1.19%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1        | 1.19%   |
| Nvidia NV43 [GeForce 6600 LE]                                                            | 1        | 1.19%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 1.19%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 1.19%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.19%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.19%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.19%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 1.19%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1        | 1.19%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1        | 1.19%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 1.19%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 1.19%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.19%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.19%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1        | 1.19%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1        | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.19%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.19%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.19%   |
| Intel 82865G Integrated Graphics Controller                                              | 1        | 1.19%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 29       | 36.71%  |
| 1 x AMD        | 24       | 30.38%  |
| 1 x Nvidia     | 22       | 27.85%  |
| 1 x VIA        | 2        | 2.53%   |
| Intel + Nvidia | 2        | 2.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 66       | 82.5%   |
| Proprietary | 11       | 13.75%  |
| Unknown     | 3        | 3.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 45.57%  |
| 0.01-0.5   | 21       | 26.58%  |
| 0.51-1.0   | 11       | 13.92%  |
| 1.01-2.0   | 7        | 8.86%   |
| 3.01-4.0   | 2        | 2.53%   |
| 7.01-8.0   | 1        | 1.27%   |
| 8.01-16.0  | 1        | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 16%     |
| Acer                 | 12       | 16%     |
| Dell                 | 9        | 12%     |
| Goldstar             | 8        | 10.67%  |
| Hewlett-Packard      | 5        | 6.67%   |
| BenQ                 | 5        | 6.67%   |
| AOC                  | 3        | 4%      |
| Sony                 | 2        | 2.67%   |
| Sharp                | 2        | 2.67%   |
| LG Electronics       | 2        | 2.67%   |
| Ancor Communications | 2        | 2.67%   |
| VIZ                  | 1        | 1.33%   |
| ViewSonic            | 1        | 1.33%   |
| Vestel Elektronik    | 1        | 1.33%   |
| Toshiba              | 1        | 1.33%   |
| Sceptre Tech         | 1        | 1.33%   |
| Panasonic            | 1        | 1.33%   |
| MPI                  | 1        | 1.33%   |
| Lite-On              | 1        | 1.33%   |
| Lenovo               | 1        | 1.33%   |
| KTC                  | 1        | 1.33%   |
| FUS                  | 1        | 1.33%   |
| Fujitsu Siemens      | 1        | 1.33%   |
| CPT                  | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                       | 2        | 2.56%   |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                        | 2        | 2.56%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                       | 2        | 2.56%   |
| VIZ LCD Monitor D50-D1 1920x1080                                        | 1        | 1.28%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch                | 1        | 1.28%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch    | 1        | 1.28%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1        | 1.28%   |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                     | 1        | 1.28%   |
| Sony LCD Monitor TV                                                     | 1        | 1.28%   |
| Sharp LCD SHP1047 1920x1080                                             | 1        | 1.28%   |
| Sharp LCD SHP0FF0 1360x768                                              | 1        | 1.28%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 521x293mm 23.5-inch    | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch    | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch    | 1        | 1.28%   |
| Samsung Electronics SME1920 SAM06B7 1360x768 410x230mm 18.5-inch        | 1        | 1.28%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch       | 1        | 1.28%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch       | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SyncMaster 2624x1200                    | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SMB1930NW 1440x900                      | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                       | 1        | 1.28%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1        | 1.28%   |
| Panasonic TH-42PD25U MEIA023 1920x540 920x518mm 41.6-inch               | 1        | 1.28%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                        | 1        | 1.28%   |
| Lite-On B17MTF LTN022A 1280x768 369x221mm 16.9-inch                     | 1        | 1.28%   |
| LG Electronics LCD Monitor M227WD 1920x1080                             | 1        | 1.28%   |
| LG Electronics LCD Monitor FLATRON 795FT Plus 1600x1200                 | 1        | 1.28%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch                | 1        | 1.28%   |
| KTC 32T72-H-AN KTC3200 1360x768 698x392mm 31.5-inch                     | 1        | 1.28%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 1        | 1.28%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1        | 1.28%   |
| Hewlett-Packard LCD Monitor 2711 1920x1080                              | 1        | 1.28%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch             | 1        | 1.28%   |
| Hewlett-Packard L1506 HWP265B 1024x768 304x228mm 15.0-inch              | 1        | 1.28%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 1        | 1.28%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                     | 1        | 1.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 1        | 1.28%   |
| Goldstar L196WTQ GSM4B4F 1440x900 408x255mm 18.9-inch                   | 1        | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 23       | 30.67%  |
| 1280x1024 (SXGA)   | 12       | 16%     |
| 1366x768 (WXGA)    | 5        | 6.67%   |
| 2560x1440 (QHD)    | 4        | 5.33%   |
| 1680x1050 (WSXGA+) | 4        | 5.33%   |
| 1600x900 (HD+)     | 4        | 5.33%   |
| 1440x900 (WXGA+)   | 4        | 5.33%   |
| 1360x768           | 3        | 4%      |
| 1024x768 (XGA)     | 3        | 4%      |
| 3840x2160 (4K)     | 2        | 2.67%   |
| 2560x1080          | 2        | 2.67%   |
| Unknown            | 2        | 2.67%   |
| 3840x1080          | 1        | 1.33%   |
| 2624x1200          | 1        | 1.33%   |
| 2048x1152          | 1        | 1.33%   |
| 1920x540           | 1        | 1.33%   |
| 1600x1200          | 1        | 1.33%   |
| 1280x768           | 1        | 1.33%   |
| 1280x720 (HD)      | 1        | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 17.11%  |
| 19      | 9        | 11.84%  |
| 17      | 7        | 9.21%   |
| 27      | 5        | 6.58%   |
| 18      | 5        | 6.58%   |
| 15      | 5        | 6.58%   |
| 22      | 4        | 5.26%   |
| 21      | 4        | 5.26%   |
| 31      | 3        | 3.95%   |
| 24      | 3        | 3.95%   |
| 23      | 3        | 3.95%   |
| 20      | 3        | 3.95%   |
| 84      | 2        | 2.63%   |
| 34      | 2        | 2.63%   |
| 74      | 1        | 1.32%   |
| 41      | 1        | 1.32%   |
| 40      | 1        | 1.32%   |
| 32      | 1        | 1.32%   |
| 26      | 1        | 1.32%   |
| 16      | 1        | 1.32%   |
| 14      | 1        | 1.32%   |
| 8       | 1        | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 18       | 24%     |
| Unknown     | 13       | 17.33%  |
| 501-600     | 11       | 14.67%  |
| 301-350     | 11       | 14.67%  |
| 351-400     | 9        | 12%     |
| 701-800     | 3        | 4%      |
| 601-700     | 3        | 4%      |
| 1501-2000   | 3        | 4%      |
| 801-900     | 1        | 1.33%   |
| 201-300     | 1        | 1.33%   |
| 101-200     | 1        | 1.33%   |
| 901-1000    | 1        | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 36       | 49.32%  |
| Unknown | 10       | 13.7%   |
| 5/4     | 9        | 12.33%  |
| 16/10   | 8        | 10.96%  |
| 4/3     | 4        | 5.48%   |
| 6/5     | 3        | 4.11%   |
| 21/9    | 2        | 2.74%   |
| 1.98    | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 16       | 21.33%  |
| Unknown        | 13       | 17.33%  |
| 201-250        | 10       | 13.33%  |
| 141-150        | 10       | 13.33%  |
| 351-500        | 6        | 8%      |
| 301-350        | 5        | 6.67%   |
| 101-110        | 5        | 6.67%   |
| More than 1000 | 3        | 4%      |
| 251-300        | 2        | 2.67%   |
| 501-1000       | 2        | 2.67%   |
| 1-40           | 1        | 1.33%   |
| 131-140        | 1        | 1.33%   |
| 121-130        | 1        | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 47       | 65.28%  |
| Unknown | 13       | 18.06%  |
| 101-120 | 8        | 11.11%  |
| 1-50    | 3        | 4.17%   |
| 161-240 | 1        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 87.34%  |
| 2     | 6        | 7.59%   |
| 0     | 3        | 3.8%    |
| 3     | 1        | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 42       | 33.87%  |
| Intel                           | 21       | 16.94%  |
| Qualcomm Atheros                | 10       | 8.06%   |
| Nvidia                          | 9        | 7.26%   |
| Ralink Technology               | 8        | 6.45%   |
| Broadcom                        | 6        | 4.84%   |
| VIA Technologies                | 3        | 2.42%   |
| Qualcomm Atheros Communications | 3        | 2.42%   |
| Gemtek                          | 3        | 2.42%   |
| D-Link                          | 3        | 2.42%   |
| Ralink                          | 2        | 1.61%   |
| Marvell Technology Group        | 2        | 1.61%   |
| Broadcom Limited                | 2        | 1.61%   |
| ASUSTek Computer                | 2        | 1.61%   |
| 3Com                            | 2        | 1.61%   |
| Xiaomi                          | 1        | 0.81%   |
| TP-Link                         | 1        | 0.81%   |
| Samsung Electronics             | 1        | 0.81%   |
| NetGear                         | 1        | 0.81%   |
| Belkin Components               | 1        | 0.81%   |
| ADMtek                          | 1        | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 22       | 16.79%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 3.82%   |
| Nvidia MCP61 Ethernet                                                         | 5        | 3.82%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 3.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 2.29%   |
| Ralink RT5370 Wireless Adapter                                                | 3        | 2.29%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 2.29%   |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 2.29%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                             | 3        | 2.29%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 2        | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 1.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 2        | 1.53%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 2        | 1.53%   |
| Realtek 802.11ac NIC                                                          | 2        | 1.53%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.53%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.53%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 2        | 1.53%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                               | 2        | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.76%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                  | 1        | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.76%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                              | 1        | 0.76%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.76%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.76%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.76%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1        | 0.76%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.76%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 0.76%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1        | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 14       | 29.17%  |
| Ralink Technology               | 8        | 16.67%  |
| Qualcomm Atheros                | 6        | 12.5%   |
| Qualcomm Atheros Communications | 3        | 6.25%   |
| Gemtek                          | 3        | 6.25%   |
| D-Link                          | 3        | 6.25%   |
| Ralink                          | 2        | 4.17%   |
| ASUSTek Computer                | 2        | 4.17%   |
| VIA Technologies                | 1        | 2.08%   |
| TP-Link                         | 1        | 2.08%   |
| Samsung Electronics             | 1        | 2.08%   |
| NetGear                         | 1        | 2.08%   |
| Marvell Technology Group        | 1        | 2.08%   |
| Intel                           | 1        | 2.08%   |
| Belkin Components               | 1        | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                    | 3        | 6.25%   |
| Ralink RT5370 Wireless Adapter                                                         | 3        | 6.25%   |
| Ralink MT7601U Wireless Adapter                                                        | 3        | 6.25%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                      | 3        | 6.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                        | 2        | 4.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 2        | 4.17%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                              | 2        | 4.17%   |
| Realtek 802.11ac NIC                                                                   | 2        | 4.17%   |
| Qualcomm Atheros AR9271 802.11n                                                        | 2        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                       | 2        | 4.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                       | 2        | 4.17%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                           | 1        | 2.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                            | 1        | 2.08%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                       | 1        | 2.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                 | 1        | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 1        | 2.08%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                               | 1        | 2.08%   |
| Ralink RT5572 Wireless Adapter                                                         | 1        | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                  | 1        | 2.08%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                   | 1        | 2.08%   |
| Ralink RT2561/RT61 rev B 802.11g                                                       | 1        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1        | 2.08%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271]          | 1        | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                         | 1        | 2.08%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                                    | 1        | 2.08%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                                    | 1        | 2.08%   |
| Intel Wi-Fi 6 AX200                                                                    | 1        | 2.08%   |
| D-Link DWP-156                                                                         | 1        | 2.08%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                   | 1        | 2.08%   |
| D-Link 802.11ac NIC                                                                    | 1        | 2.08%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 2.08%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                        | 1        | 2.08%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                     | 1        | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 34       | 41.46%  |
| Intel                    | 20       | 24.39%  |
| Nvidia                   | 9        | 10.98%  |
| Broadcom                 | 6        | 7.32%   |
| Qualcomm Atheros         | 4        | 4.88%   |
| VIA Technologies         | 2        | 2.44%   |
| Broadcom Limited         | 2        | 2.44%   |
| 3Com                     | 2        | 2.44%   |
| Xiaomi                   | 1        | 1.22%   |
| Marvell Technology Group | 1        | 1.22%   |
| ADMtek                   | 1        | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22       | 26.51%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 7.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 6.02%   |
| Nvidia MCP61 Ethernet                                             | 5        | 6.02%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 4.82%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 3.61%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 2.41%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.41%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 2.41%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2        | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.2%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.2%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.2%    |
| Nvidia MCP79 Ethernet                                             | 1        | 1.2%    |
| Nvidia MCP73 Ethernet                                             | 1        | 1.2%    |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 1.2%    |
| Nvidia CK804 Ethernet Controller                                  | 1        | 1.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.2%    |
| Intel I211 Gigabit Network Connection                             | 1        | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 1        | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 1        | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.2%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.2%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.2%    |
| Intel 82567LM-2 Gigabit Network Connection                        | 1        | 1.2%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.2%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.2%    |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.2%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.2%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.2%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.2%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.2%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.2%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 1.2%    |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 63.33%  |
| WiFi     | 44       | 36.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 62.34%  |
| WiFi     | 29       | 37.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 69.62%  |
| 2     | 20       | 25.32%  |
| 0     | 3        | 3.8%    |
| 3     | 1        | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 93.67%  |
| Yes  | 5        | 6.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 41.18%  |
| Broadcom                        | 3        | 17.65%  |
| Qualcomm Atheros Communications | 2        | 11.76%  |
| ASUSTek Computer                | 2        | 11.76%  |
| Primax Electronics              | 1        | 5.88%   |
| Kensington                      | 1        | 5.88%   |
| Intel                           | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 41.18%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 11.76%  |
| ASUS Bluetooth Radio                                | 2        | 11.76%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 5.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5.88%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1        | 5.88%   |
| Kensington Bluetooth EDR Dongle                     | 1        | 5.88%   |
| Intel AX200 Bluetooth                               | 1        | 5.88%   |
| Broadcom Bluetooth Controller                       | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 46       | 42.59%  |
| AMD                                             | 24       | 22.22%  |
| Nvidia                                          | 20       | 18.52%  |
| C-Media Electronics                             | 5        | 4.63%   |
| VIA Technologies                                | 4        | 3.7%    |
| Creative Labs                                   | 4        | 3.7%    |
| ULi Electronics                                 | 1        | 0.93%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.93%   |
| Generalplus Technology                          | 1        | 0.93%   |
| Creative Technology                             | 1        | 0.93%   |
| Corsair                                         | 1        | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 8.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 5.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 4.88%   |
| Nvidia MCP61 High Definition Audio                                         | 5        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 4.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.25%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 3.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4        | 3.25%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 3        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.44%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 2.44%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 2.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.63%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2        | 1.63%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 2        | 1.63%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 1.63%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.63%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 1.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.63%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.81%   |
| ULi Electronics HD Audio Controller                                        | 1        | 0.81%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.81%   |
| Nvidia MCP73 High Definition Audio                                         | 1        | 0.81%   |
| Nvidia MCP51 High Definition Audio                                         | 1        | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.81%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.81%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.81%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.81%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.81%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.81%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 0.81%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter   | 1        | 0.81%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 20%     |
| Micron Technology   | 3        | 20%     |
| SK hynix            | 2        | 13.33%  |
| Samsung Electronics | 2        | 13.33%  |
| Nanya Technology    | 1        | 6.67%   |
| Kingston            | 1        | 6.67%   |
| G.Skill             | 1        | 6.67%   |
| Crucial             | 1        | 6.67%   |
| Unknown             | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2                       | 1        | 5.56%   |
| Unknown RAM Module 1GB DIMM DDR2                       | 1        | 5.56%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 1        | 5.56%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s               | 1        | 5.56%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 5.56%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s   | 1        | 5.56%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s           | 1        | 5.56%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 1        | 5.56%   |
| Samsung RAM M378B2873FHS-CH9 1024MB DIMM DDR3 1333MT/s | 1        | 5.56%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s     | 1        | 5.56%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s            | 1        | 5.56%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 1        | 5.56%   |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s     | 1        | 5.56%   |
| Kingston RAM 9905734-019.A00G 16GB DIMM DDR4 2400MT/s  | 1        | 5.56%   |
| Kingston RAM 9905713-017.A00G 4GB DIMM DDR4 2866MT/s   | 1        | 5.56%   |
| G.Skill RAM F3-1866C10-8GAB 8GB DIMM DDR3 1867MT/s     | 1        | 5.56%   |
| Crucial RAM BLS8G3D18ADS3 8GB DIMM DDR3 1866MT/s       | 1        | 5.56%   |
| Unknown                                                | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 50%     |
| DDR2    | 2        | 14.29%  |
| Unknown | 2        | 14.29%  |
| SDRAM   | 1        | 7.14%   |
| DDR4    | 1        | 7.14%   |
| DDR     | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 13       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 1024  | 6        | 37.5%   |
| 2048  | 5        | 31.25%  |
| 8192  | 2        | 12.5%   |
| 4096  | 2        | 12.5%   |
| 16384 | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 20%     |
| 1333    | 3        | 20%     |
| 800     | 2        | 13.33%  |
| 41632   | 1        | 6.67%   |
| 2866    | 1        | 6.67%   |
| 2400    | 1        | 6.67%   |
| 1867    | 1        | 6.67%   |
| 1866    | 1        | 6.67%   |
| 320     | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 40%     |
| Seiko Epson         | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson XP-243 245 247 Series    | 1        | 20%     |
| Samsung ML-216x Series Laser Printer | 1        | 20%     |
| HP OfficeJet 5200 series             | 1        | 20%     |
| Brother HL-L2350DW series            | 1        | 20%     |
| Brother HL-L2340D series             | 1        | 20%     |

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
| Logitech                      | 2        | 25%     |
| Cubeternet                    | 2        | 25%     |
| Sunplus Innovation Technology | 1        | 12.5%   |
| Samsung Electronics           | 1        | 12.5%   |
| GEO Semi                      | 1        | 12.5%   |
| Aveo Technology               | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sunplus SPCA2281 Web Camera                                         | 1        | 12.5%   |
| Samsung Galaxy A5 (MTP)                                             | 1        | 12.5%   |
| Logitech Webcam C270                                                | 1        | 12.5%   |
| Logitech Webcam C210                                                | 1        | 12.5%   |
| GEO Semi Condor                                                     | 1        | 12.5%   |
| Cubeternet USB2.0 Camera                                            | 1        | 12.5%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 12.5%   |
| Aveo Camera                                                         | 1        | 12.5%   |

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
| 0     | 62       | 76.54%  |
| 1     | 16       | 19.75%  |
| 2     | 3        | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 7        | 33.33%  |
| Graphics card            | 5        | 23.81%  |
| Communication controller | 5        | 23.81%  |
| Unassigned class         | 1        | 4.76%   |
| Sound                    | 1        | 4.76%   |
| Net/ethernet             | 1        | 4.76%   |
| Camera                   | 1        | 4.76%   |

