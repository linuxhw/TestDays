Peppermint 10 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Peppermint 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=peppermint-10

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

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
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
| Dell          | Board                    | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | Board                    | [6c93eb4440](https://linux-hardware.org/?probe=6c93eb4440) | Mar 07, 2021 |
| Dell          | 0C522T A01               | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| HP            | 3032h                    | [50914ba2f5](https://linux-hardware.org/?probe=50914ba2f5) | Mar 04, 2021 |
| ASUSTek       | P5N-E SLI                | [236a4d5753](https://linux-hardware.org/?probe=236a4d5753) | Feb 23, 2021 |
| ASUSTek       | P5N-E SLI                | [27f148966a](https://linux-hardware.org/?probe=27f148966a) | Feb 23, 2021 |
| Dell          | Board                    | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Board                    | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
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
| ASUSTek       | A88XM-A                  | [831a02648f](https://linux-hardware.org/?probe=831a02648f) | Oct 31, 2020 |
| ASUSTek       | A88XM-A                  | [c2bab5c22b](https://linux-hardware.org/?probe=c2bab5c22b) | Oct 15, 2020 |
| ASUSTek       | A88XM-A                  | [c7104649d5](https://linux-hardware.org/?probe=c7104649d5) | Oct 15, 2020 |
| Dell          | 0C2KJT A00               | [37cf119697](https://linux-hardware.org/?probe=37cf119697) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                  | [d822785861](https://linux-hardware.org/?probe=d822785861) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                  | [b0a785eecd](https://linux-hardware.org/?probe=b0a785eecd) | Sep 30, 2020 |
| Intel         | 945GCT-M                 | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                 | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Dell          | 09KPNV A00               | [7a9366d7a0](https://linux-hardware.org/?probe=7a9366d7a0) | Sep 04, 2020 |
| HP            | 8265                     | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| MSI           | MS-7211                  | [98822d361e](https://linux-hardware.org/?probe=98822d361e) | Aug 17, 2020 |
| MSI           | MS-7211                  | [a07f95af54](https://linux-hardware.org/?probe=a07f95af54) | Aug 17, 2020 |
| HP            | 0A54h                    | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| ASRock        | N68-S3 FX                | [cbf919cfd5](https://linux-hardware.org/?probe=cbf919cfd5) | Jul 30, 2020 |
| HP            | 18E7                     | [4b13141bdb](https://linux-hardware.org/?probe=4b13141bdb) | Jul 30, 2020 |
| Gigabyte      | 990FXA-UD3               | [dc82f8cf6b](https://linux-hardware.org/?probe=dc82f8cf6b) | Jul 15, 2020 |
| MSI           | MS-7211                  | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                  | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Gigabyte      | 990XA-UD3                | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| ASUSTek       | K8N4-E Deluxe            | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Fujitsu       | D3171-A1 S26361-D3171-A1 | [a514be4e22](https://linux-hardware.org/?probe=a514be4e22) | Jun 06, 2020 |
| ASUSTek       | K8N4-E Deluxe            | [5fa350f8ac](https://linux-hardware.org/?probe=5fa350f8ac) | May 31, 2020 |
| MSI           | MS-7267                  | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Dell          | 02YRK5 A02               | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Dell          | 02YRK5 A02               | [82a7d47cf6](https://linux-hardware.org/?probe=82a7d47cf6) | May 15, 2020 |
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
| Fujitsu Si... | D1931 S26361-D1931       | [e5dda37f22](https://linux-hardware.org/?probe=e5dda37f22) | Feb 12, 2020 |
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
| Gigabyte      | F2A55M-HD2               | [ee80ea4e41](https://linux-hardware.org/?probe=ee80ea4e41) | Nov 24, 2019 |
| Gigabyte      | F2A55M-HD2               | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                  | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Dell          | 042P49 A01               | [b7c0226ab5](https://linux-hardware.org/?probe=b7c0226ab5) | Nov 10, 2019 |
| ASUSTek       | X99-A/USB                | [40ea4505b9](https://linux-hardware.org/?probe=40ea4505b9) | Nov 09, 2019 |
| eMachines     | EL1850                   | [c2b6c642fb](https://linux-hardware.org/?probe=c2b6c642fb) | Nov 09, 2019 |
| Lenovo        | 31900058 STD             | [ee0395fcb1](https://linux-hardware.org/?probe=ee0395fcb1) | Oct 25, 2019 |
| Gigabyte      | H61M-S1                  | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                  | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                  | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                  | [e0f3e1d46f](https://linux-hardware.org/?probe=e0f3e1d46f) | Sep 22, 2019 |
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
| 5.0.0-37-generic     | 14       | 16.47%  |
| 5.3.0-46-generic     | 4        | 4.71%   |
| 5.0.0-36-generic     | 4        | 4.71%   |
| 5.4.0-87-generic     | 3        | 3.53%   |
| 5.4.0-66-generic     | 3        | 3.53%   |
| 5.4.0-42-generic     | 3        | 3.53%   |
| 5.3.0-51-generic     | 3        | 3.53%   |
| 5.3.0-40-generic     | 3        | 3.53%   |
| 5.0.0-32-generic     | 3        | 3.53%   |
| 4.18.0-25-generic    | 3        | 3.53%   |
| 4.18.0-18-generic    | 3        | 3.53%   |
| 5.4.0-67-generic     | 2        | 2.35%   |
| 5.4.0-58-generic     | 2        | 2.35%   |
| 5.4.0-54-generic     | 2        | 2.35%   |
| 5.4.0-52-generic     | 2        | 2.35%   |
| 5.4.0-48-generic     | 2        | 2.35%   |
| 5.3.0-62-generic     | 2        | 2.35%   |
| 5.3.0-59-generic     | 2        | 2.35%   |
| 5.3.0-28-generic     | 2        | 2.35%   |
| 5.0.0-29-generic     | 2        | 2.35%   |
| 5.0.0-25-generic     | 2        | 2.35%   |
| 5.7.1-050701-generic | 1        | 1.18%   |
| 5.6.7-050607-generic | 1        | 1.18%   |
| 5.4.0-89-generic     | 1        | 1.18%   |
| 5.4.0-81-generic     | 1        | 1.18%   |
| 5.4.0-80-generic     | 1        | 1.18%   |
| 5.4.0-70-generic     | 1        | 1.18%   |
| 5.4.0-65-generic     | 1        | 1.18%   |
| 5.4.0-62-generic     | 1        | 1.18%   |
| 5.4.0-60-generic     | 1        | 1.18%   |
| 5.4.0-56-generic     | 1        | 1.18%   |
| 5.4.0-51-generic     | 1        | 1.18%   |
| 5.4.0-49-generic     | 1        | 1.18%   |
| 5.4.0-45-generic     | 1        | 1.18%   |
| 5.3.9-050309-generic | 1        | 1.18%   |
| 5.3.6-050306-generic | 1        | 1.18%   |
| 5.3.0-53-generic     | 1        | 1.18%   |
| 5.3.0-45-generic     | 1        | 1.18%   |
| 5.0.0-23-generic     | 1        | 1.18%   |
| 4.18.0-24-generic    | 1        | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 28       | 35.44%  |
| 5.0.0   | 24       | 30.38%  |
| 5.3.0   | 17       | 21.52%  |
| 4.18.0  | 6        | 7.59%   |
| 5.7.1   | 1        | 1.27%   |
| 5.6.7   | 1        | 1.27%   |
| 5.3.9   | 1        | 1.27%   |
| 5.3.6   | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 28       | 35.44%  |
| 5.0     | 24       | 30.38%  |
| 5.3     | 19       | 24.05%  |
| 4.18    | 6        | 7.59%   |
| 5.7     | 1        | 1.27%   |
| 5.6     | 1        | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 53       | 70.67%  |
| i686   | 22       | 29.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LXDE    | 60       | 78.95%  |
| Unknown | 13       | 17.11%  |
| GNOME   | 3        | 3.95%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 74       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 90.79%  |
| TDM     | 4        | 5.26%   |
| LightDM | 3        | 3.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24       | 31.17%  |
| Unknown | 11       | 14.29%  |
| it_IT   | 7        | 9.09%   |
| pt_BR   | 5        | 6.49%   |
| en_IN   | 4        | 5.19%   |
| en_GB   | 4        | 5.19%   |
| de_DE   | 4        | 5.19%   |
| ru_RU   | 2        | 2.6%    |
| fi_FI   | 2        | 2.6%    |
| C       | 2        | 2.6%    |
| ro_RO   | 1        | 1.3%    |
| pl_PL   | 1        | 1.3%    |
| fr_FR   | 1        | 1.3%    |
| es_PE   | 1        | 1.3%    |
| es_ES   | 1        | 1.3%    |
| es_EC   | 1        | 1.3%    |
| es_AR   | 1        | 1.3%    |
| en_PH   | 1        | 1.3%    |
| en_NZ   | 1        | 1.3%    |
| en_IE   | 1        | 1.3%    |
| en_CA   | 1        | 1.3%    |
| en_AU   | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 65       | 86.67%  |
| EFI  | 10       | 13.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 65       | 84.42%  |
| Unknown | 8        | 10.39%  |
| Overlay | 2        | 2.6%    |
| Xfs     | 1        | 1.3%    |
| Ext2    | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 71       | 95.95%  |
| GPT     | 2        | 2.7%    |
| MBR     | 1        | 1.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 89.33%  |
| Yes       | 8        | 10.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 83.78%  |
| Yes       | 12       | 16.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 20.27%  |
| Gigabyte Technology | 11       | 14.86%  |
| Dell                | 11       | 14.86%  |
| Hewlett-Packard     | 9        | 12.16%  |
| Intel               | 5        | 6.76%   |
| ASRock              | 3        | 4.05%   |
| Pegatron            | 2        | 2.7%    |
| MSI                 | 2        | 2.7%    |
| Fujitsu Siemens     | 2        | 2.7%    |
| eMachines           | 2        | 2.7%    |
| ECS                 | 2        | 2.7%    |
| Acer                | 2        | 2.7%    |
| Nvidia              | 1        | 1.35%   |
| Lenovo              | 1        | 1.35%   |
| Gateway             | 1        | 1.35%   |
| Fujitsu             | 1        | 1.35%   |
| Foxconn             | 1        | 1.35%   |
| Biostar             | 1        | 1.35%   |
| AAEON               | 1        | 1.35%   |
| Unknown             | 1        | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP Compaq dc7900 Convertible Minitower | 2        | 2.7%    |
| Fujitsu Siemens D1931                  | 2        | 2.7%    |
| Pegatron FR502AA-ABZ m9355.it          | 1        | 1.35%   |
| Pegatron CQ1506LA                      | 1        | 1.35%   |
| Nvidia MCP7A                           | 1        | 1.35%   |
| MSI MS-7267                            | 1        | 1.35%   |
| MSI MS-7211                            | 1        | 1.35%   |
| Lenovo IdeaCentre Q190 10115           | 1        | 1.35%   |
| Intel H61                              | 1        | 1.35%   |
| Intel Energy Systems                   | 1        | 1.35%   |
| Intel DP55WG AAE57269-408              | 1        | 1.35%   |
| Intel D945GCLF2 AAE46416-106           | 1        | 1.35%   |
| Intel 945GCT-M                         | 1        | 1.35%   |
| HP ProDesk 600 G1 SFF                  | 1        | 1.35%   |
| HP EliteDesk 705 G3 MT                 | 1        | 1.35%   |
| HP CQ2930EA                            | 1        | 1.35%   |
| HP Compaq dc7800 Small Form Factor     | 1        | 1.35%   |
| HP Compaq dc7700p Small Form Factor    | 1        | 1.35%   |
| HP Compaq dc7700 Ultra-slim Desktop    | 1        | 1.35%   |
| HP Compaq dc7700 Small Form Factor     | 1        | 1.35%   |
| Gigabyte Z87X-UD5H                     | 1        | 1.35%   |
| Gigabyte P35-DS3R                      | 1        | 1.35%   |
| Gigabyte J1800M-D3P                    | 1        | 1.35%   |
| Gigabyte H61M-S1                       | 1        | 1.35%   |
| Gigabyte GA-VM900M                     | 1        | 1.35%   |
| Gigabyte F2A55M-HD2                    | 1        | 1.35%   |
| Gigabyte EQ45M-S2                      | 1        | 1.35%   |
| Gigabyte B450M S2H                     | 1        | 1.35%   |
| Gigabyte 990XA-UD3                     | 1        | 1.35%   |
| Gigabyte 990FXA-UD3                    | 1        | 1.35%   |
| Gigabyte 945GCM-S2L                    | 1        | 1.35%   |
| Gateway T5246                          | 1        | 1.35%   |
| Fujitsu ESPRIMO P510                   | 1        | 1.35%   |
| Foxconn s5610f                         | 1        | 1.35%   |
| eMachines EL1850                       | 1        | 1.35%   |
| eMachines EL1600                       | 1        | 1.35%   |
| ECS RR493AA-ABE SR2109ES               | 1        | 1.35%   |
| ECS ET1161-03                          | 1        | 1.35%   |
| Dell XPS420                            | 1        | 1.35%   |
| Dell Precision WorkStation T3500       | 1        | 1.35%   |
| Dell OptiPlex 980                      | 1        | 1.35%   |
| Dell OptiPlex 960                      | 1        | 1.35%   |
| Dell OptiPlex 745                      | 1        | 1.35%   |
| Dell OptiPlex 360                      | 1        | 1.35%   |
| Dell OptiPlex 3010                     | 1        | 1.35%   |
| Dell Inspiron 580                      | 1        | 1.35%   |
| Dell Inspiron 530                      | 1        | 1.35%   |
| Dell Inspiron 3647                     | 1        | 1.35%   |
| Dell Dimension E521                    | 1        | 1.35%   |
| Biostar A68N-5600E                     | 1        | 1.35%   |
| ASUS WorkPro/MyPC 4E Series            | 1        | 1.35%   |
| ASUS SABERTOOTH Z77                    | 1        | 1.35%   |
| ASUS ROG Maximus X HERO                | 1        | 1.35%   |
| ASUS P8Z68-V PRO GEN3                  | 1        | 1.35%   |
| ASUS P8H61-MX                          | 1        | 1.35%   |
| ASUS P5SD2-VM                          | 1        | 1.35%   |
| ASUS P5N-E SLI                         | 1        | 1.35%   |
| ASUS P5K-VM                            | 1        | 1.35%   |
| ASUS P5G41T-M LE                       | 1        | 1.35%   |
| ASUS M3A78-EM                          | 1        | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 6        | 8.11%   |
| Dell OptiPlex         | 5        | 6.76%   |
| Dell Inspiron         | 3        | 4.05%   |
| Fujitsu Siemens D1931 | 2        | 2.7%    |
| Acer Aspire           | 2        | 2.7%    |
| Pegatron FR502AA-ABZ  | 1        | 1.35%   |
| Pegatron CQ1506LA     | 1        | 1.35%   |
| Nvidia MCP7A          | 1        | 1.35%   |
| MSI MS-7267           | 1        | 1.35%   |
| MSI MS-7211           | 1        | 1.35%   |
| Lenovo IdeaCentre     | 1        | 1.35%   |
| Intel H61             | 1        | 1.35%   |
| Intel Energy          | 1        | 1.35%   |
| Intel DP55WG          | 1        | 1.35%   |
| Intel D945GCLF2       | 1        | 1.35%   |
| Intel 945GCT-M        | 1        | 1.35%   |
| HP ProDesk            | 1        | 1.35%   |
| HP EliteDesk          | 1        | 1.35%   |
| HP CQ2930EA           | 1        | 1.35%   |
| Gigabyte Z87X-UD5H    | 1        | 1.35%   |
| Gigabyte P35-DS3R     | 1        | 1.35%   |
| Gigabyte J1800M-D3P   | 1        | 1.35%   |
| Gigabyte H61M-S1      | 1        | 1.35%   |
| Gigabyte GA-VM900M    | 1        | 1.35%   |
| Gigabyte F2A55M-HD2   | 1        | 1.35%   |
| Gigabyte EQ45M-S2     | 1        | 1.35%   |
| Gigabyte B450M        | 1        | 1.35%   |
| Gigabyte 990XA-UD3    | 1        | 1.35%   |
| Gigabyte 990FXA-UD3   | 1        | 1.35%   |
| Gigabyte 945GCM-S2L   | 1        | 1.35%   |
| Gateway T5246         | 1        | 1.35%   |
| Fujitsu ESPRIMO       | 1        | 1.35%   |
| Foxconn s5610f        | 1        | 1.35%   |
| eMachines EL1850      | 1        | 1.35%   |
| eMachines EL1600      | 1        | 1.35%   |
| ECS RR493AA-ABE       | 1        | 1.35%   |
| ECS ET1161-03         | 1        | 1.35%   |
| Dell XPS420           | 1        | 1.35%   |
| Dell Precision        | 1        | 1.35%   |
| Dell Dimension        | 1        | 1.35%   |
| Biostar A68N-5600E    | 1        | 1.35%   |
| ASUS WorkPro          | 1        | 1.35%   |
| ASUS SABERTOOTH       | 1        | 1.35%   |
| ASUS ROG              | 1        | 1.35%   |
| ASUS P8Z68-V          | 1        | 1.35%   |
| ASUS P8H61-MX         | 1        | 1.35%   |
| ASUS P5SD2-VM         | 1        | 1.35%   |
| ASUS P5N-E            | 1        | 1.35%   |
| ASUS P5K-VM           | 1        | 1.35%   |
| ASUS P5G41T-M         | 1        | 1.35%   |
| ASUS M3A78-EM         | 1        | 1.35%   |
| ASUS KP324AA-ABU      | 1        | 1.35%   |
| ASUS K8N4-E           | 1        | 1.35%   |
| ASUS ER950AA-ABA      | 1        | 1.35%   |
| ASUS All              | 1        | 1.35%   |
| ASUS A88XM-A          | 1        | 1.35%   |
| ASRock P4VM8          | 1        | 1.35%   |
| ASRock N68-S3         | 1        | 1.35%   |
| ASRock 970M           | 1        | 1.35%   |
| AAEON MF-001          | 1        | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 11       | 14.86%  |
| 2013 | 9        | 12.16%  |
| 2008 | 8        | 10.81%  |
| 2019 | 7        | 9.46%   |
| 2011 | 6        | 8.11%   |
| 2009 | 6        | 8.11%   |
| 2005 | 6        | 8.11%   |
| 2010 | 5        | 6.76%   |
| 2012 | 4        | 5.41%   |
| 2018 | 2        | 2.7%    |
| 2016 | 2        | 2.7%    |
| 2015 | 2        | 2.7%    |
| 2006 | 2        | 2.7%    |
| 2020 | 1        | 1.35%   |
| 2017 | 1        | 1.35%   |
| 2014 | 1        | 1.35%   |
| 2004 | 1        | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 74       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 73       | 98.65%  |
| Enabled  | 1        | 1.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 26       | 34.21%  |
| 1.01-2.0   | 19       | 25%     |
| 8.01-16.0  | 9        | 11.84%  |
| 4.01-8.0   | 6        | 7.89%   |
| 2.01-3.0   | 5        | 6.58%   |
| 16.01-24.0 | 5        | 6.58%   |
| 32.01-64.0 | 3        | 3.95%   |
| 0.51-1.0   | 2        | 2.63%   |
| 24.01-32.0 | 1        | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 35       | 43.21%  |
| 1.01-2.0  | 31       | 38.27%  |
| 2.01-3.0  | 6        | 7.41%   |
| 0.01-0.5  | 4        | 4.94%   |
| 4.01-8.0  | 2        | 2.47%   |
| 3.01-4.0  | 2        | 2.47%   |
| 8.01-16.0 | 1        | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 47       | 61.84%  |
| 2      | 18       | 23.68%  |
| 3      | 7        | 9.21%   |
| 7      | 1        | 1.32%   |
| 6      | 1        | 1.32%   |
| 5      | 1        | 1.32%   |
| 4      | 1        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 66.67%  |
| No        | 25       | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 72       | 97.3%   |
| No        | 2        | 2.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 55.41%  |
| No        | 33       | 44.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 79.73%  |
| Yes       | 15       | 20.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 26       | 34.67%  |
| Italy       | 7        | 9.33%   |
| Germany     | 5        | 6.67%   |
| Brazil      | 5        | 6.67%   |
| UK          | 4        | 5.33%   |
| India       | 4        | 5.33%   |
| Finland     | 3        | 4%      |
| Russia      | 2        | 2.67%   |
| Romania     | 2        | 2.67%   |
| Canada      | 2        | 2.67%   |
| Argentina   | 2        | 2.67%   |
| Spain       | 1        | 1.33%   |
| Portugal    | 1        | 1.33%   |
| Poland      | 1        | 1.33%   |
| Philippines | 1        | 1.33%   |
| Peru        | 1        | 1.33%   |
| New Zealand | 1        | 1.33%   |
| Netherlands | 1        | 1.33%   |
| Ireland     | 1        | 1.33%   |
| Greece      | 1        | 1.33%   |
| Ecuador     | 1        | 1.33%   |
| Belgium     | 1        | 1.33%   |
| Australia   | 1        | 1.33%   |
| Algeria     | 1        | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Villingen-Schwenningen | 3        | 3.85%   |
| Środa Śląska        | 1        | 1.28%   |
| Winfield               | 1        | 1.28%   |
| Welwyn Garden City     | 1        | 1.28%   |
| Wassenaar              | 1        | 1.28%   |
| Washington             | 1        | 1.28%   |
| Van Vleck              | 1        | 1.28%   |
| Turin                  | 1        | 1.28%   |
| Tsarskoye Selo         | 1        | 1.28%   |
| Thatcher               | 1        | 1.28%   |
| Taranto                | 1        | 1.28%   |
| Talala                 | 1        | 1.28%   |
| Tahlequah              | 1        | 1.28%   |
| Spokane                | 1        | 1.28%   |
| South Jordan           | 1        | 1.28%   |
| Somma Vesuviana        | 1        | 1.28%   |
| Seville                | 1        | 1.28%   |
| Saratov                | 1        | 1.28%   |
| Santa Barbara          | 1        | 1.28%   |
| Saint-Jerome           | 1        | 1.28%   |
| Rome                   | 1        | 1.28%   |
| Rock Hill              | 1        | 1.28%   |
| Roanoke                | 1        | 1.28%   |
| Rio de Janeiro         | 1        | 1.28%   |
| Reggio Emilia          | 1        | 1.28%   |
| Quezon City            | 1        | 1.28%   |
| Pune                   | 1        | 1.28%   |
| Popesti-Leordeni       | 1        | 1.28%   |
| Philadelphia           | 1        | 1.28%   |
| Perth                  | 1        | 1.28%   |
| Pensacola              | 1        | 1.28%   |
| Overland Park          | 1        | 1.28%   |
| Oulu                   | 1        | 1.28%   |
| Osterburken            | 1        | 1.28%   |
| Naples                 | 1        | 1.28%   |
| Mysore                 | 1        | 1.28%   |
| Mumbai                 | 1        | 1.28%   |
| Middlesboro            | 1        | 1.28%   |
| Metairie               | 1        | 1.28%   |
| Maywood Park           | 1        | 1.28%   |
| Manchester             | 1        | 1.28%   |
| Lugagnano Val d'Arda   | 1        | 1.28%   |
| Lourinhã              | 1        | 1.28%   |
| Lincoln                | 1        | 1.28%   |
| Lima                   | 1        | 1.28%   |
| Lake Charles           | 1        | 1.28%   |
| La Crosse              | 1        | 1.28%   |
| Krosnowice             | 1        | 1.28%   |
| Kielczow               | 1        | 1.28%   |
| Jacksonville           | 1        | 1.28%   |
| Ipiau                  | 1        | 1.28%   |
| Hitchin                | 1        | 1.28%   |
| Helsinki               | 1        | 1.28%   |
| Hammond                | 1        | 1.28%   |
| Hamburg                | 1        | 1.28%   |
| Guayaquil              | 1        | 1.28%   |
| Gmina Strzelin         | 1        | 1.28%   |
| Fitchburg              | 1        | 1.28%   |
| Espoo                  | 1        | 1.28%   |
| Dublin                 | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 46     | 26.92%  |
| Seagate             | 20       | 22     | 19.23%  |
| Hitachi             | 14       | 21     | 13.46%  |
| Samsung Electronics | 13       | 18     | 12.5%   |
| MAXTOR              | 7        | 10     | 6.73%   |
| Kingston            | 6        | 8      | 5.77%   |
| SanDisk             | 3        | 3      | 2.88%   |
| Toshiba             | 2        | 2      | 1.92%   |
| Intel               | 2        | 2      | 1.92%   |
| WD MediaMax         | 1        | 1      | 0.96%   |
| Unknown             | 1        | 1      | 0.96%   |
| PNY                 | 1        | 2      | 0.96%   |
| OCZ                 | 1        | 1      | 0.96%   |
| Intenso             | 1        | 1      | 0.96%   |
| GAMER               | 1        | 1      | 0.96%   |
| Fujitsu             | 1        | 1      | 0.96%   |
| Crucial             | 1        | 2      | 0.96%   |
| ASMT                | 1        | 1      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD     | 3        | 2.68%   |
| Hitachi HDT721016SLA380 160GB       | 3        | 2.68%   |
| Seagate ST3500418AS 500GB           | 2        | 1.79%   |
| Seagate ST3250310AS 250GB           | 2        | 1.79%   |
| Seagate ST3160813AS 160GB           | 2        | 1.79%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 1.79%   |
| SanDisk SDSSDA120G 120GB            | 2        | 1.79%   |
| Samsung SSD 860 EVO 1TB             | 2        | 1.79%   |
| MAXTOR STM3160215AS 160GB           | 2        | 1.79%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 1.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.89%   |
| WDC WD800JD-75MSA1 80GB             | 1        | 0.89%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.89%   |
| WDC WD800JD-00MSA1 80GB             | 1        | 0.89%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.89%   |
| WDC WD5000LPVT-24G33T1 500GB        | 1        | 0.89%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.89%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.89%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 0.89%   |
| WDC WD4000AAJS-00YFA0 400GB         | 1        | 0.89%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.89%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1        | 0.89%   |
| WDC WD3200AVJB-63WKA0 320GB         | 1        | 0.89%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1        | 0.89%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1        | 0.89%   |
| WDC WD2500AVJB-63WKA0 250GB         | 1        | 0.89%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 0.89%   |
| WDC WD2500AAJS-00VTA0 250GB         | 1        | 0.89%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.89%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 0.89%   |
| WDC WD2000JS-60NCB1 200GB           | 1        | 0.89%   |
| WDC WD1600JS-00NCB1 160GB           | 1        | 0.89%   |
| WDC WD1600AAJS-75M0A0 160GB         | 1        | 0.89%   |
| WDC WD1200BB-53DWA0 120GB           | 1        | 0.89%   |
| WDC WD10JPVX-08JC3T5 1TB            | 1        | 0.89%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1        | 0.89%   |
| WDC WD10EZEX-60M2NA0 1TB            | 1        | 0.89%   |
| WDC WD10EURX-63C57Y0 1TB            | 1        | 0.89%   |
| WDC WD1003FBYX-18Y7B0 1TB           | 1        | 0.89%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 0.89%   |
| WDC WD1001FALS-00J7B0 1TB           | 1        | 0.89%   |
| WD MediaMax WL120GBSATA             | 1        | 0.89%   |
| Unknown MMC Card  16GB              | 1        | 0.89%   |
| Toshiba MK3265GSXN 320GB            | 1        | 0.89%   |
| Toshiba MK2555GSXF 250GB            | 1        | 0.89%   |
| Seagate ST9160314AS 160GB           | 1        | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 0.89%   |
| Seagate ST5000LM000-2AN170 5TB      | 1        | 0.89%   |
| Seagate ST380013AS 80GB             | 1        | 0.89%   |
| Seagate ST3160215A 160GB            | 1        | 0.89%   |
| Seagate ST31500341AS 1TB            | 1        | 0.89%   |
| Seagate ST310005 28ASQ 1TB          | 1        | 0.89%   |
| Seagate ST2000DX002-2DV164 2TB      | 1        | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 0.89%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.89%   |
| Seagate ST1000VM002-1ET162 1TB      | 1        | 0.89%   |
| Seagate ST1000NM0018-2F2130 1TB     | 1        | 0.89%   |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 0.89%   |
| SanDisk SDSSDA240G 240GB            | 1        | 0.89%   |
| Samsung SSD SM841 2.5 7mm 256GB     | 1        | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 45     | 34.18%  |
| Seagate             | 20       | 22     | 25.32%  |
| Hitachi             | 14       | 21     | 17.72%  |
| Samsung Electronics | 7        | 10     | 8.86%   |
| MAXTOR              | 7        | 10     | 8.86%   |
| Toshiba             | 2        | 2      | 2.53%   |
| WD MediaMax         | 1        | 1      | 1.27%   |
| Fujitsu             | 1        | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 8      | 28.57%  |
| Samsung Electronics | 5        | 7      | 23.81%  |
| SanDisk             | 3        | 3      | 14.29%  |
| Intel               | 2        | 2      | 9.52%   |
| WDC                 | 1        | 1      | 4.76%   |
| PNY                 | 1        | 2      | 4.76%   |
| OCZ                 | 1        | 1      | 4.76%   |
| Crucial             | 1        | 2      | 4.76%   |
| ASMT                | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 62       | 112    | 71.26%  |
| SSD     | 21       | 27     | 24.14%  |
| Unknown | 2        | 2      | 2.3%    |
| MMC     | 1        | 1      | 1.15%   |
| NVMe    | 1        | 1      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72       | 139    | 94.74%  |
| SAS  | 2        | 2      | 2.63%   |
| NVMe | 1        | 1      | 1.32%   |
| MMC  | 1        | 1      | 1.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 64       | 107    | 71.91%  |
| 0.51-1.0   | 19       | 24     | 21.35%  |
| 1.01-2.0   | 5        | 7      | 5.62%   |
| 4.01-10.0  | 1        | 1      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 39.74%  |
| 501-1000       | 12       | 15.38%  |
| 251-500        | 11       | 14.1%   |
| 51-100         | 9        | 11.54%  |
| 21-50          | 6        | 7.69%   |
| 1001-2000      | 4        | 5.13%   |
| Unknown        | 2        | 2.56%   |
| More than 3000 | 1        | 1.28%   |
| 2001-3000      | 1        | 1.28%   |
| 1-20           | 1        | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 45       | 58.44%  |
| 21-50     | 14       | 18.18%  |
| 101-250   | 7        | 9.09%   |
| 51-100    | 5        | 6.49%   |
| 501-1000  | 2        | 2.6%    |
| Unknown   | 2        | 2.6%    |
| 251-500   | 1        | 1.3%    |
| 1001-2000 | 1        | 1.3%    |

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
| Detected | 71       | 136    | 93.42%  |
| Works    | 3        | 5      | 3.95%   |
| Malfunc  | 2        | 2      | 2.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 45       | 52.94%  |
| AMD                              | 13       | 15.29%  |
| Nvidia                           | 9        | 10.59%  |
| JMicron Technology               | 5        | 5.88%   |
| VIA Technologies                 | 4        | 4.71%   |
| Marvell Technology Group         | 3        | 3.53%   |
| ULi Electronics                  | 1        | 1.18%   |
| Silicon Integrated Systems [SiS] | 1        | 1.18%   |
| Silicon Image                    | 1        | 1.18%   |
| Samsung Electronics              | 1        | 1.18%   |
| LSI Logic / Symbios Logic        | 1        | 1.18%   |
| ASMedia Technology               | 1        | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 6.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 6.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 3.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4        | 3.05%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 3.05%   |
| Nvidia MCP61 IDE                                                                        | 4        | 3.05%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.05%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 3.05%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 3.05%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.29%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 2.29%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 2.29%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.29%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 2        | 1.53%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 1.53%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.53%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.53%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.53%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 2        | 1.53%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 2        | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.53%   |
| VIA VT8237/8251 Serial ATA Controller                                                   | 1        | 0.76%   |
| ULi ULi 5287 SATA                                                                       | 1        | 0.76%   |
| ULi M5229 IDE                                                                           | 1        | 0.76%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 0.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.76%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 0.76%   |
| Nvidia MCP73 SATA RAID Controller                                                       | 1        | 0.76%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.76%   |
| Nvidia MCP51 IDE                                                                        | 1        | 0.76%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1        | 0.76%   |
| Nvidia CK804 IDE                                                                        | 1        | 0.76%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.76%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1        | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.76%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.76%   |
| JMicron JMB360 AHCI Controller                                                          | 1        | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.76%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.76%   |
| Intel 82Q963/Q965 PT IDER Controller                                                    | 1        | 0.76%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.76%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.76%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.76%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.76%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 46       | 52.87%  |
| SATA | 32       | 36.78%  |
| RAID | 7        | 8.05%   |
| SAS  | 1        | 1.15%   |
| NVMe | 1        | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 56       | 75.68%  |
| AMD    | 18       | 24.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz        | 4        | 5.41%   |
| Intel Pentium 4 CPU 3.00GHz                  | 3        | 4.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 3        | 4.05%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz  | 2        | 2.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 2        | 2.7%    |
| Intel Core 2 CPU 6600 @ 2.40GHz              | 2        | 2.7%    |
| Intel Celeron CPU 430 @ 1.80GHz              | 2        | 2.7%    |
| AMD Athlon 64 X2 Dual Core Processor 5000+   | 2        | 2.7%    |
| Intel Xeon CPU X5660 @ 2.80GHz               | 1        | 1.35%   |
| Intel Xeon CPU W3530 @ 2.80GHz               | 1        | 1.35%   |
| Intel Xeon CPU E31270 @ 3.40GHz              | 1        | 1.35%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz  | 1        | 1.35%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz  | 1        | 1.35%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz       | 1        | 1.35%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz       | 1        | 1.35%   |
| Intel Pentium D CPU 3.00GHz                  | 1        | 1.35%   |
| Intel Pentium CPU G6960 @ 2.93GHz            | 1        | 1.35%   |
| Intel Pentium CPU G630 @ 2.70GHz             | 1        | 1.35%   |
| Intel Pentium CPU G2020 @ 2.90GHz            | 1        | 1.35%   |
| Intel Pentium 4 CPU 3.40GHz                  | 1        | 1.35%   |
| Intel Pentium 4 CPU 2.80GHz                  | 1        | 1.35%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 1        | 1.35%   |
| Intel Core i7-5930K CPU @ 3.50GHz            | 1        | 1.35%   |
| Intel Core i7-4770K CPU @ 3.50GHz            | 1        | 1.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz             | 1        | 1.35%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1        | 1.35%   |
| Intel Core i5-3470T CPU @ 2.90GHz            | 1        | 1.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1        | 1.35%   |
| Intel Core i5-2320 CPU @ 3.00GHz             | 1        | 1.35%   |
| Intel Core i5 CPU 650 @ 3.20GHz              | 1        | 1.35%   |
| Intel Core i3-4150 CPU @ 3.50GHz             | 1        | 1.35%   |
| Intel Core i3 CPU 530 @ 2.93GHz              | 1        | 1.35%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz        | 1        | 1.35%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz         | 1        | 1.35%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz         | 1        | 1.35%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz         | 1        | 1.35%   |
| Intel Core 2 CPU 6300 @ 1.86GHz              | 1        | 1.35%   |
| Intel Celeron CPU J1800 @ 2.41GHz            | 1        | 1.35%   |
| Intel Celeron CPU 450 @ 2.20GHz              | 1        | 1.35%   |
| Intel Celeron CPU 2.80GHz                    | 1        | 1.35%   |
| Intel Celeron CPU 2.53GHz                    | 1        | 1.35%   |
| Intel Celeron CPU 1017U @ 1.60GHz            | 1        | 1.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 1        | 1.35%   |
| Intel Atom CPU D525 @ 1.80GHz                | 1        | 1.35%   |
| Intel Atom CPU 330 @ 1.60GHz                 | 1        | 1.35%   |
| Intel Atom CPU 230 @ 1.60GHz                 | 1        | 1.35%   |
| AMD Sempron 145 Processor                    | 1        | 1.35%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics  | 1        | 1.35%   |
| AMD PRO A6-8570 R5, 8 COMPUTE CORES 2C+6G    | 1        | 1.35%   |
| AMD PRO A4-3350B APU with Radeon R4 Graphics | 1        | 1.35%   |
| AMD Phenom II X4 840 Processor               | 1        | 1.35%   |
| AMD FX-8370 Eight-Core Processor             | 1        | 1.35%   |
| AMD FX-6300 Six-Core Processor               | 1        | 1.35%   |
| AMD E1-1200 APU with Radeon HD Graphics      | 1        | 1.35%   |
| AMD Athlon II X2 250 Processor               | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+   | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+   | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+   | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 3600+   | 1        | 1.35%   |
| AMD Athlon 64 Processor 3000+                | 1        | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core 2 Quad       | 8        | 10.81%  |
| Intel Celeron           | 7        | 9.46%   |
| Intel Core i5           | 6        | 8.11%   |
| AMD Athlon 64 X2        | 6        | 8.11%   |
| Intel Pentium 4         | 5        | 6.76%   |
| Intel Core 2 Duo        | 5        | 6.76%   |
| Intel Pentium Dual-Core | 4        | 5.41%   |
| Intel Atom              | 4        | 5.41%   |
| Intel Xeon              | 3        | 4.05%   |
| Intel Pentium           | 3        | 4.05%   |
| Intel Core i7           | 3        | 4.05%   |
| Intel Core 2            | 3        | 4.05%   |
| Other                   | 2        | 2.7%    |
| Intel Pentium Dual      | 2        | 2.7%    |
| Intel Core i3           | 2        | 2.7%    |
| AMD FX                  | 2        | 2.7%    |
| Intel Pentium D         | 1        | 1.35%   |
| AMD Sempron             | 1        | 1.35%   |
| AMD Ryzen 3             | 1        | 1.35%   |
| AMD Phenom II X4        | 1        | 1.35%   |
| AMD E1                  | 1        | 1.35%   |
| AMD Athlon II X2        | 1        | 1.35%   |
| AMD Athlon 64           | 1        | 1.35%   |
| AMD A6                  | 1        | 1.35%   |
| AMD A4                  | 1        | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 45.95%  |
| 4      | 20       | 27.03%  |
| 1      | 16       | 21.62%  |
| 6      | 3        | 4.05%   |
| 3      | 1        | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 74       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 70.27%  |
| 2      | 22       | 29.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 64       | 85.33%  |
| Unknown        | 7        | 9.33%   |
| 32-bit         | 4        | 5.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 11       | 14.86%  |
| Unknown    | 10       | 13.51%  |
| 0xf41      | 4        | 5.41%   |
| 0x306a9    | 4        | 5.41%   |
| 0x6fd      | 3        | 4.05%   |
| 0x6fb      | 3        | 4.05%   |
| 0x206a7    | 3        | 4.05%   |
| 0x10661    | 3        | 4.05%   |
| 0x6f6      | 2        | 2.7%    |
| 0x306c3    | 2        | 2.7%    |
| 0x20655    | 2        | 2.7%    |
| 0x106c2    | 2        | 2.7%    |
| 0x06001119 | 2        | 2.7%    |
| 0x010000c8 | 2        | 2.7%    |
| 0xf65      | 1        | 1.35%   |
| 0xf62      | 1        | 1.35%   |
| 0xf43      | 1        | 1.35%   |
| 0xf33      | 1        | 1.35%   |
| 0x906ea    | 1        | 1.35%   |
| 0x6f2      | 1        | 1.35%   |
| 0x406c4    | 1        | 1.35%   |
| 0x306f2    | 1        | 1.35%   |
| 0x30678    | 1        | 1.35%   |
| 0x206c2    | 1        | 1.35%   |
| 0x20652    | 1        | 1.35%   |
| 0x106ca    | 1        | 1.35%   |
| 0x106a5    | 1        | 1.35%   |
| 0x10677    | 1        | 1.35%   |
| 0x10676    | 1        | 1.35%   |
| 0x08108109 | 1        | 1.35%   |
| 0x07030106 | 1        | 1.35%   |
| 0x0600611a | 1        | 1.35%   |
| 0x06000852 | 1        | 1.35%   |
| 0x06000822 | 1        | 1.35%   |
| 0x05000119 | 1        | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 13       | 17.57%  |
| Core        | 12       | 16.22%  |
| NetBurst    | 8        | 10.81%  |
| K8 Hammer   | 7        | 9.46%   |
| IvyBridge   | 5        | 6.76%   |
| Westmere    | 4        | 5.41%   |
| Piledriver  | 4        | 5.41%   |
| Haswell     | 4        | 5.41%   |
| SandyBridge | 3        | 4.05%   |
| K10         | 3        | 4.05%   |
| Bonnell     | 3        | 4.05%   |
| Silvermont  | 2        | 2.7%    |
| Zen+        | 1        | 1.35%   |
| Puma        | 1        | 1.35%   |
| Nehalem     | 1        | 1.35%   |
| KabyLake    | 1        | 1.35%   |
| Excavator   | 1        | 1.35%   |
| Bobcat      | 1        | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 30       | 38.96%  |
| AMD              | 23       | 29.87%  |
| Nvidia           | 22       | 28.57%  |
| VIA Technologies | 2        | 2.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 7.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 5.13%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 3.85%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 3.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 2.56%   |
| Nvidia G94 [GeForce 9600 GS]                                                             | 2        | 2.56%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 2        | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 2.56%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 2.56%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 2        | 2.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 2.56%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1        | 1.28%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1        | 1.28%   |
| Nvidia NV43 [GeForce 6600 LE]                                                            | 1        | 1.28%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 1.28%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 1.28%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.28%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.28%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.28%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.28%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 1.28%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1        | 1.28%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1        | 1.28%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 1.28%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 1.28%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.28%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1        | 1.28%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1        | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.28%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.28%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 1.28%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1        | 1.28%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1        | 1.28%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 1.28%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1        | 1.28%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1        | 1.28%   |
| AMD RV710 [Radeon HD 4550]                                                               | 1        | 1.28%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1        | 1.28%   |
| AMD RV620 LE [Radeon HD 3450 AGP]                                                        | 1        | 1.28%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 1        | 1.28%   |
| AMD RS780L [Radeon 3000]                                                                 | 1        | 1.28%   |
| AMD RS780 [Radeon HD 3200]                                                               | 1        | 1.28%   |
| AMD RS480 [Radeon Xpress 200 Series]                                                     | 1        | 1.28%   |
| AMD RS400 [Radeon Xpress 200]                                                            | 1        | 1.28%   |
| AMD RC410 [Radeon Xpress 200/1100]                                                       | 1        | 1.28%   |
| AMD Picasso                                                                              | 1        | 1.28%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1        | 1.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 1.28%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 1        | 1.28%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 27       | 36.49%  |
| 1 x AMD        | 23       | 31.08%  |
| 1 x Nvidia     | 20       | 27.03%  |
| 1 x VIA        | 2        | 2.7%    |
| Intel + Nvidia | 2        | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 81.33%  |
| Proprietary | 11       | 14.67%  |
| Unknown     | 3        | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 45.95%  |
| 0.01-0.5   | 19       | 25.68%  |
| 0.51-1.0   | 10       | 13.51%  |
| 1.01-2.0   | 7        | 9.46%   |
| 3.01-4.0   | 2        | 2.7%    |
| 7.01-8.0   | 1        | 1.35%   |
| 8.01-16.0  | 1        | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 12       | 16.9%   |
| Samsung Electronics  | 11       | 15.49%  |
| Dell                 | 9        | 12.68%  |
| Goldstar             | 8        | 11.27%  |
| Hewlett-Packard      | 5        | 7.04%   |
| BenQ                 | 5        | 7.04%   |
| AOC                  | 3        | 4.23%   |
| Sony                 | 2        | 2.82%   |
| LG Electronics       | 2        | 2.82%   |
| VIZ                  | 1        | 1.41%   |
| ViewSonic            | 1        | 1.41%   |
| Vestel Elektronik    | 1        | 1.41%   |
| Toshiba              | 1        | 1.41%   |
| Sharp                | 1        | 1.41%   |
| Sceptre Tech         | 1        | 1.41%   |
| Panasonic            | 1        | 1.41%   |
| MPI                  | 1        | 1.41%   |
| Lenovo               | 1        | 1.41%   |
| KTC                  | 1        | 1.41%   |
| FUS                  | 1        | 1.41%   |
| Fujitsu Siemens      | 1        | 1.41%   |
| CPT                  | 1        | 1.41%   |
| Ancor Communications | 1        | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                       | 2        | 2.7%    |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                        | 2        | 2.7%    |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                       | 2        | 2.7%    |
| VIZ LCD Monitor D50-D1 1920x1080                                        | 1        | 1.35%   |
| ViewSonic VG2230wm-EU VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 1.35%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1        | 1.35%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1        | 1.35%   |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                     | 1        | 1.35%   |
| Sony LCD Monitor TV                                                     | 1        | 1.35%   |
| Sharp LCD SHP0FF0 1360x768                                              | 1        | 1.35%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 521x293mm 23.5-inch    | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch    | 1        | 1.35%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch    | 1        | 1.35%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch        | 1        | 1.35%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch       | 1        | 1.35%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch       | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SyncMaster 2624x1200                    | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SMB1930NW 1440x900                      | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch | 1        | 1.35%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                       | 1        | 1.35%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1        | 1.35%   |
| Panasonic TH-42PD25U MEIA023 1920x540 920x518mm 41.6-inch               | 1        | 1.35%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                        | 1        | 1.35%   |
| LG Electronics LCD Monitor M227WD 1920x1080                             | 1        | 1.35%   |
| LG Electronics LCD Monitor FLATRON 795FT Plus 1600x1200                 | 1        | 1.35%   |
| Lenovo LEN LT1712p LEN13B7 1280x1024 338x270mm 17.0-inch                | 1        | 1.35%   |
| KTC 32T55-H-CS KTC3200 1360x768 698x392mm 31.5-inch                     | 1        | 1.35%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 1        | 1.35%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch              | 1        | 1.35%   |
| Hewlett-Packard LCD Monitor 2711 1920x1080                              | 1        | 1.35%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 376x301mm 19.0-inch             | 1        | 1.35%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch              | 1        | 1.35%   |
| Goldstar W1943 GSM4BAD 1024x768 410x230mm 18.5-inch                     | 1        | 1.35%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                     | 1        | 1.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch             | 1        | 1.35%   |
| Goldstar L196WTQ GSM4B4F 1440x900 408x255mm 18.9-inch                   | 1        | 1.35%   |
| Goldstar L1553S GSM3BB0 1024x768 304x228mm 15.0-inch                    | 1        | 1.35%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1        | 1.35%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                    | 1        | 1.35%   |
| Goldstar 27GN7 GSM5B8E 1920x1080 600x303mm 26.5-inch                    | 1        | 1.35%   |
| FUS LCD Monitor 383V FA                                                 | 1        | 1.35%   |
| Fujitsu Siemens P19-1 FUS0452 1280x1024 376x301mm 19.0-inch             | 1        | 1.35%   |
| Dell U2713HM DEL407D 1920x1200 600x340mm 27.2-inch                      | 1        | 1.35%   |
| Dell S1709W DELD018 1440x900 370x230mm 17.2-inch                        | 1        | 1.35%   |
| Dell P2213 DELF041 1680x1050 473x296mm 22.0-inch                        | 1        | 1.35%   |
| Dell LCD Monitor SE2417HG 1920x1080                                     | 1        | 1.35%   |
| Dell IN1910N DELA04C 1366x768 410x230mm 18.5-inch                       | 1        | 1.35%   |
| Dell E228WFP DELD015 1680x1050 473x296mm 22.0-inch                      | 1        | 1.35%   |
| Dell DEL 1908FPBLK DEL4047 1280x1024 376x301mm 19.0-inch                | 1        | 1.35%   |
| Dell 1703FP DEL3010 1280x1024 338x270mm 17.0-inch                       | 1        | 1.35%   |
| CPT CL-151G CPT1790 1024x768 304x228mm 15.0-inch                        | 1        | 1.35%   |
| CPT CL-151G CPT06FE 1024x768 300x230mm 14.9-inch                        | 1        | 1.35%   |
| BenQ RL2460H BNQ7F34 1920x1080 531x299mm 24.0-inch                      | 1        | 1.35%   |
| BenQ LCD Monitor GL2450H 1920x1080                                      | 1        | 1.35%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                      | 1        | 1.35%   |
| BenQ G610HDAL BNQ785B 1366x768 344x194mm 15.5-inch                      | 1        | 1.35%   |
| AOC AG322FWG4 AOC3220 1920x1080 698x393mm 31.5-inch                     | 1        | 1.35%   |
| AOC 2590G4 AOC2590 1920x1080 544x303mm 24.5-inch                        | 1        | 1.35%   |
| AOC 2080W AOC2080 1440x900 419x262mm 19.5-inch                          | 1        | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 22       | 30.99%  |
| 1280x1024 (SXGA)   | 12       | 16.9%   |
| 1680x1050 (WSXGA+) | 4        | 5.63%   |
| 1600x900 (HD+)     | 4        | 5.63%   |
| 1440x900 (WXGA+)   | 4        | 5.63%   |
| 1366x768 (WXGA)    | 4        | 5.63%   |
| 2560x1440 (QHD)    | 3        | 4.23%   |
| 1360x768           | 3        | 4.23%   |
| 1024x768 (XGA)     | 3        | 4.23%   |
| 3840x2160 (4K)     | 2        | 2.82%   |
| 2560x1080          | 2        | 2.82%   |
| Unknown            | 2        | 2.82%   |
| 3840x1080          | 1        | 1.41%   |
| 2624x1200          | 1        | 1.41%   |
| 2048x1152          | 1        | 1.41%   |
| 1920x540           | 1        | 1.41%   |
| 1600x1200          | 1        | 1.41%   |
| 1280x720 (HD)      | 1        | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 16.67%  |
| 19      | 9        | 12.5%   |
| 17      | 7        | 9.72%   |
| 18      | 5        | 6.94%   |
| 15      | 5        | 6.94%   |
| 27      | 4        | 5.56%   |
| 22      | 4        | 5.56%   |
| 21      | 4        | 5.56%   |
| 31      | 3        | 4.17%   |
| 24      | 3        | 4.17%   |
| 23      | 3        | 4.17%   |
| 20      | 3        | 4.17%   |
| 84      | 2        | 2.78%   |
| 34      | 2        | 2.78%   |
| 74      | 1        | 1.39%   |
| 41      | 1        | 1.39%   |
| 32      | 1        | 1.39%   |
| 26      | 1        | 1.39%   |
| 14      | 1        | 1.39%   |
| 8       | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 18       | 25.35%  |
| Unknown     | 12       | 16.9%   |
| 301-350     | 11       | 15.49%  |
| 501-600     | 10       | 14.08%  |
| 351-400     | 8        | 11.27%  |
| 701-800     | 3        | 4.23%   |
| 601-700     | 3        | 4.23%   |
| 1501-2000   | 3        | 4.23%   |
| 201-300     | 1        | 1.41%   |
| 101-200     | 1        | 1.41%   |
| 901-1000    | 1        | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32       | 46.38%  |
| 5/4     | 11       | 15.94%  |
| Unknown | 10       | 14.49%  |
| 16/10   | 8        | 11.59%  |
| 4/3     | 4        | 5.8%    |
| 21/9    | 2        | 2.9%    |
| 6/5     | 1        | 1.45%   |
| 1.98    | 1        | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 16       | 22.54%  |
| Unknown        | 12       | 16.9%   |
| 201-250        | 10       | 14.08%  |
| 141-150        | 10       | 14.08%  |
| 351-500        | 6        | 8.45%   |
| 101-110        | 5        | 7.04%   |
| 301-350        | 4        | 5.63%   |
| More than 1000 | 3        | 4.23%   |
| 251-300        | 2        | 2.82%   |
| 1-40           | 1        | 1.41%   |
| 131-140        | 1        | 1.41%   |
| 501-1000       | 1        | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 67.65%  |
| Unknown | 12       | 17.65%  |
| 101-120 | 7        | 10.29%  |
| 1-50    | 2        | 2.94%   |
| 161-240 | 1        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 86.49%  |
| 2     | 6        | 8.11%   |
| 0     | 3        | 4.05%   |
| 3     | 1        | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 38       | 33.04%  |
| Intel                           | 20       | 17.39%  |
| Qualcomm Atheros                | 9        | 7.83%   |
| Ralink Technology               | 8        | 6.96%   |
| Nvidia                          | 8        | 6.96%   |
| Broadcom                        | 6        | 5.22%   |
| VIA Technologies                | 3        | 2.61%   |
| Qualcomm Atheros Communications | 3        | 2.61%   |
| Ralink                          | 2        | 1.74%   |
| Marvell Technology Group        | 2        | 1.74%   |
| Gemtek                          | 2        | 1.74%   |
| D-Link                          | 2        | 1.74%   |
| Broadcom Limited                | 2        | 1.74%   |
| ASUSTek Computer                | 2        | 1.74%   |
| 3Com                            | 2        | 1.74%   |
| Xiaomi                          | 1        | 0.87%   |
| Samsung Electronics             | 1        | 0.87%   |
| Realtek                         | 1        | 0.87%   |
| NetGear                         | 1        | 0.87%   |
| Belkin Components               | 1        | 0.87%   |
| ADMtek                          | 1        | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 21       | 17.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 4.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 3.28%   |
| Nvidia MCP61 Ethernet                                                         | 4        | 3.28%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 3.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 2.46%   |
| Ralink RT5370 Wireless Adapter                                                | 3        | 2.46%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 2.46%   |
| Intel 82566DM Gigabit Network Connection                                      | 3        | 2.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 2        | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 2        | 1.64%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 2        | 1.64%   |
| Realtek 802.11ac NIC                                                          | 2        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.64%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.64%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                             | 2        | 1.64%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 2        | 1.64%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                               | 2        | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.82%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                  | 1        | 0.82%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                              | 1        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.82%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.82%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.82%   |
| Realtek 802.11n NIC                                                           | 1        | 0.82%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.82%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1        | 0.82%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.82%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1        | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.82%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.82%   |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.82%   |
| Nvidia MCP51 Ethernet Controller                                              | 1        | 0.82%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 0.82%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                           | 1        | 0.82%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                           | 1        | 0.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.82%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 0.82%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.82%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.82%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.82%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.82%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.82%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.82%   |
| Intel 82578DC Gigabit Network Connection                                      | 1        | 0.82%   |
| Intel 82567LM-2 Gigabit Network Connection                                    | 1        | 0.82%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.82%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.82%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.82%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 0.82%   |
| D-Link 802.11ac NIC                                                           | 1        | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 13       | 28.89%  |
| Ralink Technology               | 8        | 17.78%  |
| Qualcomm Atheros                | 6        | 13.33%  |
| Qualcomm Atheros Communications | 3        | 6.67%   |
| Ralink                          | 2        | 4.44%   |
| Gemtek                          | 2        | 4.44%   |
| D-Link                          | 2        | 4.44%   |
| ASUSTek Computer                | 2        | 4.44%   |
| VIA Technologies                | 1        | 2.22%   |
| Samsung Electronics             | 1        | 2.22%   |
| Realtek                         | 1        | 2.22%   |
| NetGear                         | 1        | 2.22%   |
| Marvell Technology Group        | 1        | 2.22%   |
| Intel                           | 1        | 2.22%   |
| Belkin Components               | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                    | 3        | 6.67%   |
| Ralink RT5370 Wireless Adapter                                                         | 3        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                                        | 3        | 6.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 2        | 4.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                              | 2        | 4.44%   |
| Realtek 802.11ac NIC                                                                   | 2        | 4.44%   |
| Qualcomm Atheros AR9271 802.11n                                                        | 2        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                       | 2        | 4.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                       | 2        | 4.44%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                      | 2        | 4.44%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                           | 1        | 2.22%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                       | 1        | 2.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                        | 1        | 2.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                 | 1        | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 1        | 2.22%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                               | 1        | 2.22%   |
| Realtek 802.11n NIC                                                                    | 1        | 2.22%   |
| Ralink RT5572 Wireless Adapter                                                         | 1        | 2.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                  | 1        | 2.22%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                   | 1        | 2.22%   |
| Ralink RT2561/RT61 rev B 802.11g                                                       | 1        | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1        | 2.22%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271]          | 1        | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                         | 1        | 2.22%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                                    | 1        | 2.22%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                                    | 1        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                                    | 1        | 2.22%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                   | 1        | 2.22%   |
| D-Link 802.11ac NIC                                                                    | 1        | 2.22%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 2.22%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                        | 1        | 2.22%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                     | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 31       | 40.79%  |
| Intel                    | 19       | 25%     |
| Nvidia                   | 8        | 10.53%  |
| Broadcom                 | 6        | 7.89%   |
| Qualcomm Atheros         | 3        | 3.95%   |
| VIA Technologies         | 2        | 2.63%   |
| Broadcom Limited         | 2        | 2.63%   |
| 3Com                     | 2        | 2.63%   |
| Xiaomi                   | 1        | 1.32%   |
| Marvell Technology Group | 1        | 1.32%   |
| ADMtek                   | 1        | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 27.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 6.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 5.19%   |
| Nvidia MCP61 Ethernet                                             | 4        | 5.19%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 5.19%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 3.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 2.6%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.6%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 2.6%    |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2        | 2.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.3%    |
| Nvidia MCP79 Ethernet                                             | 1        | 1.3%    |
| Nvidia MCP73 Ethernet                                             | 1        | 1.3%    |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 1.3%    |
| Nvidia CK804 Ethernet Controller                                  | 1        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 1        | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 1        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.3%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.3%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.3%    |
| Intel 82567LM-2 Gigabit Network Connection                        | 1        | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.3%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.3%    |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.3%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.3%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.3%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.3%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.3%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 1.3%    |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 71       | 63.39%  |
| WiFi     | 41       | 36.61%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 64.52%  |
| WiFi     | 33       | 35.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 52       | 70.27%  |
| 2     | 18       | 24.32%  |
| 0     | 3        | 4.05%   |
| 3     | 1        | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 94.59%  |
| Yes  | 4        | 5.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 6        | 40%     |
| Broadcom                        | 3        | 20%     |
| Qualcomm Atheros Communications | 2        | 13.33%  |
| Primax Electronics              | 1        | 6.67%   |
| Kensington                      | 1        | 6.67%   |
| Intel                           | 1        | 6.67%   |
| ASUSTek Computer                | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 40%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 13.33%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 6.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 6.67%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1        | 6.67%   |
| Kensington Bluetooth EDR Dongle                     | 1        | 6.67%   |
| Intel AX200 Bluetooth                               | 1        | 6.67%   |
| Broadcom Bluetooth Controller                       | 1        | 6.67%   |
| ASUS Bluetooth Radio                                | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 44       | 43.56%  |
| AMD                                             | 22       | 21.78%  |
| Nvidia                                          | 18       | 17.82%  |
| C-Media Electronics                             | 5        | 4.95%   |
| VIA Technologies                                | 4        | 3.96%   |
| Creative Labs                                   | 4        | 3.96%   |
| ULi Electronics                                 | 1        | 0.99%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.99%   |
| Creative Technology                             | 1        | 0.99%   |
| Corsair                                         | 1        | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 7.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 5.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 5.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 4.42%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 3.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 3.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4        | 3.54%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 3        | 2.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 2.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 2.65%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.77%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2        | 1.77%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 2        | 1.77%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 1.77%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.77%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 1.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.77%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.88%   |
| ULi Electronics HD Audio Controller                                        | 1        | 0.88%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.88%   |
| Nvidia MCP73 High Definition Audio                                         | 1        | 0.88%   |
| Nvidia MCP51 High Definition Audio                                         | 1        | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.88%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.88%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.88%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.88%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 0.88%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter   | 1        | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 0.88%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 0.88%   |
| Creative Technology SoundBlaster MP3+                                      | 1        | 0.88%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.88%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 0.88%   |
| Corsair Gaming H2100 Headset                                               | 1        | 0.88%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 0.88%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 0.88%   |
| C-Media Electronics Blue Snowball                                          | 1        | 0.88%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 0.88%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 0.88%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 0.88%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 0.88%   |
| AMD IXP SB400 AC'97 Audio Controller                                       | 1        | 0.88%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 21.43%  |
| Micron Technology   | 3        | 21.43%  |
| SK Hynix            | 2        | 14.29%  |
| Samsung Electronics | 2        | 14.29%  |
| Nanya Technology    | 1        | 7.14%   |
| Kingston            | 1        | 7.14%   |
| G.Skill             | 1        | 7.14%   |
| Crucial             | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2                         | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM DDR2                         | 1        | 5.88%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 1        | 5.88%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s                 | 1        | 5.88%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1600MT/s               | 1        | 5.88%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2048MB DIMM DDR3 1333MT/s  | 1        | 5.88%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 5.88%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 5.88%   |
| Samsung RAM M378B2873FHS-CH9 1024MB DIMM DDR3 1333MT/s   | 1        | 5.88%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s       | 1        | 5.88%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 5.88%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 5.88%   |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s       | 1        | 5.88%   |
| Kingston RAM 9905734-019.A00G 16384MB DIMM DDR4 2400MT/s | 1        | 5.88%   |
| Kingston RAM 9905713-017.A00G 4GB DIMM DDR4 2400MT/s     | 1        | 5.88%   |
| G.Skill RAM F3-1866C10-8GAB 8GB DIMM DDR3 1866MT/s       | 1        | 5.88%   |
| Crucial RAM BLS8G3D18ADS3 8192MB DIMM DDR3 1866MT/s      | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 53.85%  |
| DDR2    | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| SDRAM   | 1        | 7.69%   |
| DDR4    | 1        | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 12       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 5        | 33.33%  |
| 1024  | 5        | 33.33%  |
| 8192  | 2        | 13.33%  |
| 4096  | 2        | 13.33%  |
| 16384 | 1        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 23.08%  |
| 1333    | 3        | 23.08%  |
| 800     | 2        | 15.38%  |
| 41632   | 1        | 7.69%   |
| 2400    | 1        | 7.69%   |
| 1867    | 1        | 7.69%   |
| 1866    | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

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
| Seiko Epson XP-240 Series            | 1        | 20%     |
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
| 0     | 58       | 77.33%  |
| 1     | 14       | 18.67%  |
| 2     | 3        | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 7        | 36.84%  |
| Communication controller | 5        | 26.32%  |
| Graphics card            | 3        | 15.79%  |
| Unassigned class         | 1        | 5.26%   |
| Sound                    | 1        | 5.26%   |
| Net/ethernet             | 1        | 5.26%   |
| Camera                   | 1        | 5.26%   |

