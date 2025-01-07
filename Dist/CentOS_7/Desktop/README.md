CentOS 7 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 7.

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

Total: 322

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Boston                      | [e3b05b98e0](https://linux-hardware.org/?probe=e3b05b98e0) | Jun 29, 2024 |
| MAXSUN        | MS-N3150 Quad               | [9661180b64](https://linux-hardware.org/?probe=9661180b64) | Jun 29, 2024 |
| MAXSUN        | MS-N3150 Quad               | [4bd7010223](https://linux-hardware.org/?probe=4bd7010223) | Jun 29, 2024 |
| MSI           | Boston                      | [125700081d](https://linux-hardware.org/?probe=125700081d) | Jun 27, 2024 |
| Unknown       | Unknown                     | [6fa8e3254c](https://linux-hardware.org/?probe=6fa8e3254c) | May 17, 2024 |
| Unknown       | Unknown                     | [b0dca146c5](https://linux-hardware.org/?probe=b0dca146c5) | May 16, 2024 |
| HP            | ProLiant ML10 v2            | [6f3897abd9](https://linux-hardware.org/?probe=6f3897abd9) | Mar 15, 2024 |
| Gigabyte      | EP45-DS3L                   | [7c90f3665f](https://linux-hardware.org/?probe=7c90f3665f) | Jan 27, 2024 |
| Gigabyte      | EP45-DS3L                   | [7cf925bed4](https://linux-hardware.org/?probe=7cf925bed4) | Dec 23, 2023 |
| Gigabyte      | B360M HD3                   | [9acf6baf05](https://linux-hardware.org/?probe=9acf6baf05) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [55109c1bbc](https://linux-hardware.org/?probe=55109c1bbc) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [bbd22340fc](https://linux-hardware.org/?probe=bbd22340fc) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | [6911b47a19](https://linux-hardware.org/?probe=6911b47a19) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [fd80bdeaed](https://linux-hardware.org/?probe=fd80bdeaed) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [ac7383c630](https://linux-hardware.org/?probe=ac7383c630) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [7b862a6a81](https://linux-hardware.org/?probe=7b862a6a81) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [17dd42b383](https://linux-hardware.org/?probe=17dd42b383) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | [e50bd82756](https://linux-hardware.org/?probe=e50bd82756) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [2194b0ad9c](https://linux-hardware.org/?probe=2194b0ad9c) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [c334514b1f](https://linux-hardware.org/?probe=c334514b1f) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PV                   | [761eebee94](https://linux-hardware.org/?probe=761eebee94) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PH                   | [b6608c7603](https://linux-hardware.org/?probe=b6608c7603) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [33bccf75e0](https://linux-hardware.org/?probe=33bccf75e0) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [59b5ebb0c3](https://linux-hardware.org/?probe=59b5ebb0c3) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [0c51eb213d](https://linux-hardware.org/?probe=0c51eb213d) | Dec 22, 2023 |
| Gigabyte      | B250M-HD3-CF                | [347eec7ee9](https://linux-hardware.org/?probe=347eec7ee9) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [561a4c0809](https://linux-hardware.org/?probe=561a4c0809) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [27115feb62](https://linux-hardware.org/?probe=27115feb62) | Dec 22, 2023 |
| Gigabyte      | B560M AORUS PRO             | [3ce597e06a](https://linux-hardware.org/?probe=3ce597e06a) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [be34427eb1](https://linux-hardware.org/?probe=be34427eb1) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [496ad2d93b](https://linux-hardware.org/?probe=496ad2d93b) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | [d0bce14740](https://linux-hardware.org/?probe=d0bce14740) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [5fb5668250](https://linux-hardware.org/?probe=5fb5668250) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [caad19d314](https://linux-hardware.org/?probe=caad19d314) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | [b1c0126e05](https://linux-hardware.org/?probe=b1c0126e05) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [d1c63c1a0b](https://linux-hardware.org/?probe=d1c63c1a0b) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [a42bd5e717](https://linux-hardware.org/?probe=a42bd5e717) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [a75998d2da](https://linux-hardware.org/?probe=a75998d2da) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [b55f33d76e](https://linux-hardware.org/?probe=b55f33d76e) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [49e9a2f26f](https://linux-hardware.org/?probe=49e9a2f26f) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [8c3370c21e](https://linux-hardware.org/?probe=8c3370c21e) | Dec 22, 2023 |
| Gigabyte      | B560M AORUS PRO             | [94de79174c](https://linux-hardware.org/?probe=94de79174c) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [59bc9b5d02](https://linux-hardware.org/?probe=59bc9b5d02) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | [87af1005b8](https://linux-hardware.org/?probe=87af1005b8) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [55570e65a7](https://linux-hardware.org/?probe=55570e65a7) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | [eea4397d45](https://linux-hardware.org/?probe=eea4397d45) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [b32df5066d](https://linux-hardware.org/?probe=b32df5066d) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [a949e7fa06](https://linux-hardware.org/?probe=a949e7fa06) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [e2b4e10140](https://linux-hardware.org/?probe=e2b4e10140) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [87c9436145](https://linux-hardware.org/?probe=87c9436145) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [b3a3b91d1d](https://linux-hardware.org/?probe=b3a3b91d1d) | Dec 22, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [0ae8561f0a](https://linux-hardware.org/?probe=0ae8561f0a) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PV                   | [2f23b66d3b](https://linux-hardware.org/?probe=2f23b66d3b) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [617899113a](https://linux-hardware.org/?probe=617899113a) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PV                   | [3092182d1d](https://linux-hardware.org/?probe=3092182d1d) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [3f48c50868](https://linux-hardware.org/?probe=3f48c50868) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | [cac98c44ed](https://linux-hardware.org/?probe=cac98c44ed) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [6d0e82b783](https://linux-hardware.org/?probe=6d0e82b783) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | [afd422517d](https://linux-hardware.org/?probe=afd422517d) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | [1db23ed649](https://linux-hardware.org/?probe=1db23ed649) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | [8ed791bd6d](https://linux-hardware.org/?probe=8ed791bd6d) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [5a63cf039d](https://linux-hardware.org/?probe=5a63cf039d) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [46e2b13b34](https://linux-hardware.org/?probe=46e2b13b34) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | [d09a9c1d0b](https://linux-hardware.org/?probe=d09a9c1d0b) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [9181bd8696](https://linux-hardware.org/?probe=9181bd8696) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [67188e1b67](https://linux-hardware.org/?probe=67188e1b67) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | [75e2601753](https://linux-hardware.org/?probe=75e2601753) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | [83d6013a05](https://linux-hardware.org/?probe=83d6013a05) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [86e58bba42](https://linux-hardware.org/?probe=86e58bba42) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [6b6c41afa2](https://linux-hardware.org/?probe=6b6c41afa2) | Dec 22, 2023 |
| Gigabyte      | B360M HD3                   | [635fdfc9be](https://linux-hardware.org/?probe=635fdfc9be) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [057ea7f38a](https://linux-hardware.org/?probe=057ea7f38a) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [0318224393](https://linux-hardware.org/?probe=0318224393) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | [6f2b8275b2](https://linux-hardware.org/?probe=6f2b8275b2) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | [4cd5825edf](https://linux-hardware.org/?probe=4cd5825edf) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | [3e070bb5d3](https://linux-hardware.org/?probe=3e070bb5d3) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | [c3140237d9](https://linux-hardware.org/?probe=c3140237d9) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | [2169da8737](https://linux-hardware.org/?probe=2169da8737) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | [968400d838](https://linux-hardware.org/?probe=968400d838) | Dec 22, 2023 |
| Dell          | 09PR9H A03                  | [25d5c9ce02](https://linux-hardware.org/?probe=25d5c9ce02) | Dec 13, 2023 |
| Dell          | 0N820C                      | [fe88368da2](https://linux-hardware.org/?probe=fe88368da2) | Nov 09, 2023 |
| Dell          | 03TJ75 A00                  | [e082a50dde](https://linux-hardware.org/?probe=e082a50dde) | Nov 02, 2023 |
| Gigabyte      | EP45-DS3L                   | [8b5e97d193](https://linux-hardware.org/?probe=8b5e97d193) | Oct 21, 2023 |
| Gigabyte      | EP45-DS3L                   | [2867e39109](https://linux-hardware.org/?probe=2867e39109) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8d59e8d305](https://linux-hardware.org/?probe=8d59e8d305) | Sep 20, 2023 |
| Gigabyte      | H270M-D3H-CF                | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Gigabyte      | EP45-DS3L                   | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| Supermicro    | X7DWE                       | [a35080b0e5](https://linux-hardware.org/?probe=a35080b0e5) | Jul 31, 2023 |
| MSI           | 870-G45                     | [af7442187f](https://linux-hardware.org/?probe=af7442187f) | Jul 20, 2023 |
| MSI           | 870-G45                     | [9fff23ac6a](https://linux-hardware.org/?probe=9fff23ac6a) | Jul 14, 2023 |
| Gigabyte      | EP45-DS3L                   | [49c764507c](https://linux-hardware.org/?probe=49c764507c) | Jul 01, 2023 |
| Intel         | DG35EC AAE29266-209         | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Supermicro    | X9DAi                       | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| Supermicro    | X10DRG-Q                    | [c03c5ea1b9](https://linux-hardware.org/?probe=c03c5ea1b9) | Jun 08, 2023 |
| Gigabyte      | EP45-DS3L                   | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| AZW           | U59                         | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| MSI           | Z77A-GD80                   | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| MSI           | Z77A-GD80                   | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| Dell          | 03TJ75 A00                  | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| Supermicro    | X10DAI                      | [b777ed256f](https://linux-hardware.org/?probe=b777ed256f) | Mar 01, 2023 |
| HP            | 0AECh D                     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| ASUSTek       | H97M-PLUS                   | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [3406527d4b](https://linux-hardware.org/?probe=3406527d4b) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [e112bdfd74](https://linux-hardware.org/?probe=e112bdfd74) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [df9a9f0b90](https://linux-hardware.org/?probe=df9a9f0b90) | Feb 14, 2023 |
| Supermicro    | X9DAi                       | [546ea7c2e8](https://linux-hardware.org/?probe=546ea7c2e8) | Feb 09, 2023 |
| HP            | 1494                        | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| MSI           | 870-G45                     | [92b840c75e](https://linux-hardware.org/?probe=92b840c75e) | Feb 04, 2023 |
| MSI           | 870-G45                     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| Gigabyte      | EP45-DS3L                   | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| PCChips       | P49G                        | [24a7d0e02b](https://linux-hardware.org/?probe=24a7d0e02b) | Jan 24, 2023 |
| MSI           | H510M PRO-E                 | [762142dfbb](https://linux-hardware.org/?probe=762142dfbb) | Jan 06, 2023 |
| Gigabyte      | EP45-DS3L                   | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [164a07eda1](https://linux-hardware.org/?probe=164a07eda1) | Dec 08, 2022 |
| Gigabyte      | D525TUD                     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| ABIT          | I-45CV                      | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [74e3fe80fd](https://linux-hardware.org/?probe=74e3fe80fd) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [efd2a439bd](https://linux-hardware.org/?probe=efd2a439bd) | Nov 21, 2022 |
| Dell          | 09D2HH A00                  | [4cafe39785](https://linux-hardware.org/?probe=4cafe39785) | Nov 19, 2022 |
| MSI           | 870-G45                     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| Gigabyte      | EP45-DS3L                   | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| HP            | 8717                        | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| MSI           | 870-G45                     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| HP            | 8717                        | [00cbc9cd2a](https://linux-hardware.org/?probe=00cbc9cd2a) | Nov 03, 2022 |
| Unknown       | Unknown                     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| Gigabyte      | H310M S2H x.x               | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| NORCO         | BPC-7951                    | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| Unknown       | Unknown                     | [f4ce3cf768](https://linux-hardware.org/?probe=f4ce3cf768) | Oct 13, 2022 |
| Dell          | 082WXT A03                  | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| MSI           | 870-G45                     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| MSI           | 870-G45                     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| Unknown       | Unknown                     | [e61dc9628f](https://linux-hardware.org/?probe=e61dc9628f) | Sep 17, 2022 |
| Dell          | 03TJ75 A00                  | [70ef579566](https://linux-hardware.org/?probe=70ef579566) | Sep 15, 2022 |
| Dell          | 0F5C5X A00                  | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| ASRock        | X299 Professional Gaming... | [759afd2f9a](https://linux-hardware.org/?probe=759afd2f9a) | Aug 04, 2022 |
| Dell          | 0KJCC5 A00                  | [4eec45d964](https://linux-hardware.org/?probe=4eec45d964) | Jul 21, 2022 |
| HP            | 0B4Ch D                     | [15e71f4f03](https://linux-hardware.org/?probe=15e71f4f03) | Jul 21, 2022 |
| Gigabyte      | EP45-DS3L                   | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| Intel         | D410PT AAE76528-404         | [b7c62fc4a8](https://linux-hardware.org/?probe=b7c62fc4a8) | Jun 29, 2022 |
| HP            | 3397                        | [f2e8417afc](https://linux-hardware.org/?probe=f2e8417afc) | Jun 04, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [0353933c85](https://linux-hardware.org/?probe=0353933c85) | Jun 02, 2022 |
| HP            | 1998                        | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Gigabyte      | EP45-DS3L                   | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Dell          | 0K068D A00                  | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Dell          | 0Y2YM6 A01                  | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| HP            | 0AECh D                     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| MiTAC         | UltraPoint                  | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| HP            | 0A9Ch                       | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| ASUSTek       | X99-DELUXE                  | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| Gigabyte      | EP45-DS3L                   | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [a355e13859](https://linux-hardware.org/?probe=a355e13859) | Jan 11, 2022 |
| Gigabyte      | G41M-ES2L                   | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| HP            | 3397                        | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [a810f7c0fb](https://linux-hardware.org/?probe=a810f7c0fb) | Dec 28, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| ASUSTek       | Pro Q570M-C                 | [d868c52b5a](https://linux-hardware.org/?probe=d868c52b5a) | Dec 15, 2021 |
| Gigabyte      | H97N-WIFI                   | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| HP            | 8717                        | [a00d17d8c4](https://linux-hardware.org/?probe=a00d17d8c4) | Nov 25, 2021 |
| Dell          | 02K9CR A01                  | [36c6a137fb](https://linux-hardware.org/?probe=36c6a137fb) | Nov 23, 2021 |
| Gigabyte      | B360HD3                     | [71a92047fb](https://linux-hardware.org/?probe=71a92047fb) | Nov 23, 2021 |
| Dell          | 02K9CR A01                  | [7d558b813e](https://linux-hardware.org/?probe=7d558b813e) | Nov 17, 2021 |
| Dell          | 04YP6J A02                  | [6c41e1551e](https://linux-hardware.org/?probe=6c41e1551e) | Nov 09, 2021 |
| Dell          | 04YP6J A02                  | [736e182a15](https://linux-hardware.org/?probe=736e182a15) | Nov 09, 2021 |
| ASRock        | Z77 Extreme4                | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| ASRock        | Z77 Extreme4                | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| Huanan        | X79                         | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| Dell          | 0Y7WYT A00                  | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| Gigabyte      | B85M-D3PH                   | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| HP            | 8751                        | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [8ddb489f03](https://linux-hardware.org/?probe=8ddb489f03) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [d19976dabe](https://linux-hardware.org/?probe=d19976dabe) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [d56fdac07b](https://linux-hardware.org/?probe=d56fdac07b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [3eb59a276c](https://linux-hardware.org/?probe=3eb59a276c) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [3d0db6b81f](https://linux-hardware.org/?probe=3d0db6b81f) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [1fc2375e54](https://linux-hardware.org/?probe=1fc2375e54) | Aug 05, 2021 |
| Dell          | 0YNVJG A01                  | [7952948421](https://linux-hardware.org/?probe=7952948421) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [a653e9beb2](https://linux-hardware.org/?probe=a653e9beb2) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [9a5d8276bf](https://linux-hardware.org/?probe=9a5d8276bf) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [2165980dd3](https://linux-hardware.org/?probe=2165980dd3) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [4a2adade2a](https://linux-hardware.org/?probe=4a2adade2a) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [78c5e3532b](https://linux-hardware.org/?probe=78c5e3532b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [10bdaec1ef](https://linux-hardware.org/?probe=10bdaec1ef) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [70fc6a65ef](https://linux-hardware.org/?probe=70fc6a65ef) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [80244f2809](https://linux-hardware.org/?probe=80244f2809) | Aug 05, 2021 |
| HP            | 8591                        | [6794bdb00e](https://linux-hardware.org/?probe=6794bdb00e) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [f209feb9c8](https://linux-hardware.org/?probe=f209feb9c8) | Aug 05, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [40b8d28af0](https://linux-hardware.org/?probe=40b8d28af0) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | [597de4e10b](https://linux-hardware.org/?probe=597de4e10b) | Aug 01, 2021 |
| ASUSTek       | SABERTOOTH X79              | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| HP            | 2B34                        | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Dell          | 09KPNV A01                  | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| HP            | 1494                        | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Intel         | E98683-353                  | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| HP            | 1589                        | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| ASRock        | J3710M                      | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | 8594                        | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 1825                        | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| HP            | 8591                        | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| HP            | 213D A01                    | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| Gigabyte      | EP43-DS3                    | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| Dell          | 0MWYPT A02                  | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| Gigabyte      | EP45-DS3L                   | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| Gigabyte      | D525TUD                     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| ASUSTek       | PRIME B360M-D               | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| Dell          | 0HHV7N A00                  | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| Gigabyte      | D525TUD                     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| Intel         | DQ67OW AAG12528-309         | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASUSTek       | X99-DELUXE                  | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Gigabyte      | Z77-D3H                     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| Gigabyte      | D525TUD                     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| Dell          | 01NP3N A00                  | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASUSTek       | F2A55-M LE                  | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| ECS           | H61H2-MV                    | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 0AECh D                     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| Zenith        | Orion                       | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| ASUSTek       | P7P55D                      | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| Lenovo        | ThinkServer TS140           | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| Dell          | 08HPGT A02                  | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Gigabyte      | B360M DS3H                  | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| HP            | 0AECh D                     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| HP            | 1589                        | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| ASUSTek       | SABERTOOTH X99              | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Gigabyte      | P85-D3                      | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| ASUSTek       | Crosshair IV Formula        | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| Supermicro    | X10DRG-H                    | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| MSI           | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| Dell          | 0VRWRC A00                  | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| ASRock        | AM1B-ITX                    | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| ASUSTek       | CM1740                      | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Gigabyte      | EP45-DS3L                   | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| HP            | 1495                        | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Supermicro    | X10SDE-DF                   | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| ASUSTek       | Rampage V EXTREME           | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASRock        | X399 Professional Gaming    | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| Gigabyte      | EP45-DS3L                   | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| Dell          | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Gigabyte      | Z170X-UD3-CF                | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| Foxconn       | 2ABF                        | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| ASUSTek       | AT4NM10T-I                  | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| HP            | 18E4                        | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| HP            | 0A98h                       | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| Dell          | 09KPNV A01                  | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Gigabyte      | B150M-D3H-CF                | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| ECS           | H55H-M                      | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Gigabyte      | B360HD3PLM-CF               | [05d00cc5d7](https://linux-hardware.org/?probe=05d00cc5d7) | Sep 09, 2019 |
| Gigabyte      | 970A-D3P                    | [6e3666d8c9](https://linux-hardware.org/?probe=6e3666d8c9) | Sep 04, 2019 |
| AMI           | Cherry Trail CR             | [fe652a02c9](https://linux-hardware.org/?probe=fe652a02c9) | Jul 25, 2019 |
| Dell          | 09KPNV A00                  | [a72c60b73b](https://linux-hardware.org/?probe=a72c60b73b) | Jul 24, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [b2fac79afd](https://linux-hardware.org/?probe=b2fac79afd) | Jun 27, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [44eb4c1fed](https://linux-hardware.org/?probe=44eb4c1fed) | Jun 25, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [4bb11d6dc0](https://linux-hardware.org/?probe=4bb11d6dc0) | Jun 07, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [3fb7cc0574](https://linux-hardware.org/?probe=3fb7cc0574) | Jun 07, 2019 |
| AAEON         | MF-001 V1.0                 | [19f89f5d4e](https://linux-hardware.org/?probe=19f89f5d4e) | Jun 05, 2019 |
| HP            | 8054                        | [8409fbc1c6](https://linux-hardware.org/?probe=8409fbc1c6) | May 28, 2019 |
| Intel         | SHARKBAY                    | [8418bef88a](https://linux-hardware.org/?probe=8418bef88a) | May 15, 2019 |
| ASUSTek       | P5G41T-M LX                 | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Intel         | SHARKBAY                    | [58607accae](https://linux-hardware.org/?probe=58607accae) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | [5e5b4e25a0](https://linux-hardware.org/?probe=5e5b4e25a0) | Apr 08, 2019 |
| ASUSTek       | F1A75-M LE                  | [f8301ffe57](https://linux-hardware.org/?probe=f8301ffe57) | Mar 26, 2019 |
| ASRock        | Z87 Extreme6                | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 81C5 MVB                    | [46ea2e591e](https://linux-hardware.org/?probe=46ea2e591e) | Mar 18, 2019 |
| MSI           | X299 RAIDER                 | [f06f57dde9](https://linux-hardware.org/?probe=f06f57dde9) | Mar 07, 2019 |
| Lenovo        | 4030                        | [10455104fd](https://linux-hardware.org/?probe=10455104fd) | Mar 01, 2019 |
| Gigabyte      | 970A-DS3P                   | [9c8b01fc94](https://linux-hardware.org/?probe=9c8b01fc94) | Dec 22, 2018 |
| Gigabyte      | 970A-DS3P                   | [3b0d00f6c9](https://linux-hardware.org/?probe=3b0d00f6c9) | Dec 22, 2018 |
| Dell          | 0CD6TV A01                  | [7f702ee88f](https://linux-hardware.org/?probe=7f702ee88f) | Oct 29, 2018 |
| Dell          | 0CD6TV A01                  | [46e3d4f4d9](https://linux-hardware.org/?probe=46e3d4f4d9) | Oct 29, 2018 |
| ASRock        | H77 Pro4/MVP                | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 3.10.0-1160.102.1.el7.x86_64 | 45       | 16.67%  |
| 3.10.0-1160.45.1.el7.x86_64  | 13       | 4.81%   |
| 3.10.0-1160.90.1.el7.x86_64  | 12       | 4.44%   |
| 3.10.0-1160.31.1.el7.x86_64  | 12       | 4.44%   |
| 3.10.0-1160.25.1.el7.x86_64  | 9        | 3.33%   |
| 3.10.0-1160.95.1.el7.x86_64  | 8        | 2.96%   |
| 3.10.0-1062.el7.x86_64       | 8        | 2.96%   |
| 3.10.0-1160.83.1.el7.x86_64  | 7        | 2.59%   |
| 3.10.0-957.10.1.el7.x86_64   | 6        | 2.22%   |
| 3.10.0-1160.76.1.el7.x86_64  | 6        | 2.22%   |
| 3.10.0-1160.66.1.el7.x86_64  | 6        | 2.22%   |
| 3.10.0-1160.15.2.el7.x86_64  | 6        | 2.22%   |
| 3.10.0-1062.12.1.el7.x86_64  | 6        | 2.22%   |
| 3.10.0-1160.el7.x86_64       | 5        | 1.85%   |
| 3.10.0-1160.6.1.el7.x86_64   | 5        | 1.85%   |
| 3.10.0-1160.36.2.el7.x86_64  | 5        | 1.85%   |
| 3.10.0-1062.9.1.el7.x86_64   | 5        | 1.85%   |
| 3.10.0-957.27.2.el7.x86_64   | 4        | 1.48%   |
| 3.10.0-1160.88.1.el7.x86_64  | 4        | 1.48%   |
| 3.10.0-1160.59.1.el7.x86_64  | 4        | 1.48%   |
| 3.10.0-1127.el7.x86_64       | 4        | 1.48%   |
| 3.10.0-957.5.1.el7.x86_64    | 3        | 1.11%   |
| 3.10.0-957.1.3.el7.x86_64    | 3        | 1.11%   |
| 3.10.0-1160.49.1.el7.x86_64  | 3        | 1.11%   |
| 3.10.0-1160.24.1.el7.x86_64  | 3        | 1.11%   |
| 3.10.0-1160.21.1.el7.x86_64  | 3        | 1.11%   |
| 3.10.0-1127.19.1.el7.x86_64  | 3        | 1.11%   |
| 3.10.0-1127.13.1.el7.x86_64  | 3        | 1.11%   |
| 3.10.0-957.el7.x86_64        | 2        | 0.74%   |
| 3.10.0-957.12.2.el7.x86_64   | 2        | 0.74%   |
| 3.10.0-693.21.1.el7.x86_64   | 2        | 0.74%   |
| 3.10.0-1160.81.1.el7.x86_64  | 2        | 0.74%   |
| 3.10.0-1160.71.1.el7.x86_64  | 2        | 0.74%   |
| 3.10.0-1160.62.1.el7.x86_64  | 2        | 0.74%   |
| 3.10.0-1160.53.1.el7.x86_64  | 2        | 0.74%   |
| 3.10.0-1160.11.1.el7.x86_64  | 2        | 0.74%   |
| 3.10.0-1160.108.1.el7.x86_64 | 2        | 0.74%   |
| 3.10.0-1160.105.1.el7.x86_64 | 2        | 0.74%   |
| 3.10.0-1127.10.1.el7.x86_64  | 2        | 0.74%   |
| 3.10.0-1062.18.1.el7.x86_64  | 2        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 3.10.0   | 221      | 90.57%  |
| 6.2.2    | 1        | 0.41%   |
| 6.1.1    | 1        | 0.41%   |
| 5.8.0    | 1        | 0.41%   |
| 5.7.7    | 1        | 0.41%   |
| 5.7.10   | 1        | 0.41%   |
| 5.6.10   | 1        | 0.41%   |
| 5.5.0    | 1        | 0.41%   |
| 5.4.96   | 1        | 0.41%   |
| 5.4.234  | 1        | 0.41%   |
| 5.4.142  | 1        | 0.41%   |
| 5.4.119  | 1        | 0.41%   |
| 5.4.118  | 1        | 0.41%   |
| 5.4.113  | 1        | 0.41%   |
| 5.3.11   | 1        | 0.41%   |
| 5.1.19   | 1        | 0.41%   |
| 4.9.188  | 1        | 0.41%   |
| 4.9.182  | 1        | 0.41%   |
| 4.9.180  | 1        | 0.41%   |
| 4.9.179  | 1        | 0.41%   |
| 4.4.229  | 1        | 0.41%   |
| 4.20.4   | 1        | 0.41%   |
| 4.19.187 | 1        | 0.41%   |
| 4.14.35  | 1        | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 3.10    | 221      | 90.57%  |
| 5.4     | 6        | 2.46%   |
| 4.9     | 4        | 1.64%   |
| 5.7     | 2        | 0.82%   |
| 6.2     | 1        | 0.41%   |
| 6.1     | 1        | 0.41%   |
| 5.8     | 1        | 0.41%   |
| 5.6     | 1        | 0.41%   |
| 5.5     | 1        | 0.41%   |
| 5.3     | 1        | 0.41%   |
| 5.1     | 1        | 0.41%   |
| 4.4     | 1        | 0.41%   |
| 4.20    | 1        | 0.41%   |
| 4.19    | 1        | 0.41%   |
| 4.14    | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 243      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 120      | 49.18%  |
| Unknown       | 73       | 29.92%  |
| KDE4          | 20       | 8.2%    |
| GNOME Classic | 17       | 6.97%   |
| MATE          | 9        | 3.69%   |
| Cinnamon      | 3        | 1.23%   |
| Xpra          | 1        | 0.41%   |
| X-Cinnamon    | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 215      | 88.48%  |
| Unknown | 27       | 11.11%  |
| Web     | 1        | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 150      | 61.48%  |
| Unknown | 82       | 33.61%  |
| LightDM | 10       | 4.1%    |
| TDM     | 1        | 0.41%   |
| SDDM    | 1        | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 102      | 41.63%  |
| en_US       | 76       | 31.02%  |
| C           | 15       | 6.12%   |
| ru_RU       | 6        | 2.45%   |
| en_GB       | 6        | 2.45%   |
| en_AU       | 6        | 2.45%   |
| en_CA       | 5        | 2.04%   |
| fr_FR       | 4        | 1.63%   |
| en_IN       | 4        | 1.63%   |
| zh_CN       | 3        | 1.22%   |
| pt_BR       | 3        | 1.22%   |
| de_DE       | 3        | 1.22%   |
| de_AT       | 3        | 1.22%   |
| es_EC       | 2        | 0.82%   |
| pl_PL       | 1        | 0.41%   |
| ko_KR       | 1        | 0.41%   |
| fr_CA       | 1        | 0.41%   |
| fi_FI       | 1        | 0.41%   |
| es_MX       | 1        | 0.41%   |
| en_US.utf-8 | 1        | 0.41%   |
| en_SG       | 1        | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 139      | 57.2%   |
| BIOS | 104      | 42.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 120      | 49.38%  |
| Ext4    | 83       | 34.16%  |
| Ext3    | 32       | 13.17%  |
| Unknown | 7        | 2.88%   |
| Tmpfs   | 1        | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 156      | 63.67%  |
| MBR     | 68       | 27.76%  |
| Unknown | 21       | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 203      | 82.86%  |
| Yes       | 42       | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 218      | 89.71%  |
| Yes       | 25       | 10.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 49       | 20.16%  |
| MSI                 | 43       | 17.7%   |
| Dell                | 39       | 16.05%  |
| ASUSTek Computer    | 33       | 13.58%  |
| Hewlett-Packard     | 27       | 11.11%  |
| Supermicro          | 8        | 3.29%   |
| ASRock              | 7        | 2.88%   |
| Intel               | 6        | 2.47%   |
| Unknown             | 6        | 2.47%   |
| ASRockRack          | 3        | 1.23%   |
| MiTAC               | 2        | 0.82%   |
| Lenovo              | 2        | 0.82%   |
| Fujitsu             | 2        | 0.82%   |
| ECS                 | 2        | 0.82%   |
| AMI                 | 2        | 0.82%   |
| Zenith              | 1        | 0.41%   |
| PCChips             | 1        | 0.41%   |
| NORCO               | 1        | 0.41%   |
| MAXSUN              | 1        | 0.41%   |
| Huanan              | 1        | 0.41%   |
| Foxconn             | 1        | 0.41%   |
| eMachines           | 1        | 0.41%   |
| Cisco Systems       | 1        | 0.41%   |
| AZW                 | 1        | 0.41%   |
| AEWIN               | 1        | 0.41%   |
| ABIT                | 1        | 0.41%   |
| AAEON               | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7C31                        | 15       | 6.17%   |
| Gigabyte H81M-S2H                  | 15       | 6.17%   |
| MSI MS-7A15                        | 9        | 3.7%    |
| Dell OptiPlex 7040                 | 8        | 3.29%   |
| Dell OptiPlex 9020                 | 7        | 2.88%   |
| MSI MS-7B53                        | 6        | 2.47%   |
| MSI MS-7A74                        | 6        | 2.47%   |
| Unknown                            | 6        | 2.47%   |
| Gigabyte H81M-DS2                  | 4        | 1.65%   |
| ASUS H110M-K                       | 4        | 1.65%   |
| ASUS All Series                    | 4        | 1.65%   |
| HP Z800 Workstation                | 3        | 1.23%   |
| HP ProDesk 400 G7 Microtower PC    | 3        | 1.23%   |
| HP Compaq Elite 8300 SFF           | 3        | 1.23%   |
| Gigabyte H81M-S2PV                 | 3        | 1.23%   |
| Dell Precision WorkStation T3500   | 3        | 1.23%   |
| ASRockRack E3C242D4U2-2T           | 3        | 1.23%   |
| HP Z420 Workstation                | 2        | 0.82%   |
| Gigabyte GA-78LMT-USB3             | 2        | 0.82%   |
| Gigabyte B560M AORUS PRO           | 2        | 0.82%   |
| Gigabyte B360M-HD3                 | 2        | 0.82%   |
| Fujitsu D3401-H1                   | 2        | 0.82%   |
| Dell OptiPlex 7010                 | 2        | 0.82%   |
| ASUS M5A78L-M PLUS/USB3            | 2        | 0.82%   |
| Zenith Orion                       | 1        | 0.41%   |
| Supermicro X9DAi                   | 1        | 0.41%   |
| Supermicro X7DWE                   | 1        | 0.41%   |
| Supermicro X10DAi                  | 1        | 0.41%   |
| Supermicro SYS-E200-8D             | 1        | 0.41%   |
| Supermicro SYS-7048GR-TR           | 1        | 0.41%   |
| Supermicro SYS-6017B-MTF           | 1        | 0.41%   |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1        | 0.41%   |
| Supermicro SYS-1028GR-TR           | 1        | 0.41%   |
| PCChips P49G                       | 1        | 0.41%   |
| NORCO BPC-7951                     | 1        | 0.41%   |
| MSI NY542AA-ABL s5220f             | 1        | 0.41%   |
| MSI MS-7D23                        | 1        | 0.41%   |
| MSI MS-7B89                        | 1        | 0.41%   |
| MSI MS-7A94                        | 1        | 0.41%   |
| MSI MS-7978                        | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Dell OptiPlex                      | 24       | 9.88%   |
| MSI MS-7C31                        | 15       | 6.17%   |
| Gigabyte H81M-S2H                  | 15       | 6.17%   |
| Dell Precision                     | 11       | 4.53%   |
| MSI MS-7A15                        | 9        | 3.7%    |
| MSI MS-7B53                        | 6        | 2.47%   |
| MSI MS-7A74                        | 6        | 2.47%   |
| Unknown                            | 6        | 2.47%   |
| HP EliteDesk                       | 5        | 2.06%   |
| HP Compaq                          | 5        | 2.06%   |
| ASUS PRIME                         | 5        | 2.06%   |
| Gigabyte H81M-DS2                  | 4        | 1.65%   |
| ASUS M5A78L-M                      | 4        | 1.65%   |
| ASUS H110M-K                       | 4        | 1.65%   |
| ASUS All                           | 4        | 1.65%   |
| HP Z800                            | 3        | 1.23%   |
| HP ProDesk                         | 3        | 1.23%   |
| Gigabyte H81M-S2PV                 | 3        | 1.23%   |
| ASRockRack E3C242D4U2-2T           | 3        | 1.23%   |
| HP Z420                            | 2        | 0.82%   |
| Gigabyte GA-78LMT-USB3             | 2        | 0.82%   |
| Gigabyte B560M                     | 2        | 0.82%   |
| Gigabyte B360M-HD3                 | 2        | 0.82%   |
| Gigabyte B360                      | 2        | 0.82%   |
| Fujitsu D3401-H1                   | 2        | 0.82%   |
| Dell Inspiron                      | 2        | 0.82%   |
| ASUS ROG                           | 2        | 0.82%   |
| Zenith Orion                       | 1        | 0.41%   |
| Supermicro X9DAi                   | 1        | 0.41%   |
| Supermicro X7DWE                   | 1        | 0.41%   |
| Supermicro X10DAi                  | 1        | 0.41%   |
| Supermicro SYS-E200-8D             | 1        | 0.41%   |
| Supermicro SYS-7048GR-TR           | 1        | 0.41%   |
| Supermicro SYS-6017B-MTF           | 1        | 0.41%   |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1        | 0.41%   |
| Supermicro SYS-1028GR-TR           | 1        | 0.41%   |
| PCChips P49G                       | 1        | 0.41%   |
| NORCO BPC-7951                     | 1        | 0.41%   |
| MSI NY542AA-ABL                    | 1        | 0.41%   |
| MSI MS-7D23                        | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 32       | 13.17%  |
| 2016    | 30       | 12.35%  |
| 2019    | 28       | 11.52%  |
| 2018    | 23       | 9.47%   |
| 2013    | 20       | 8.23%   |
| 2015    | 18       | 7.41%   |
| 2012    | 16       | 6.58%   |
| 2017    | 15       | 6.17%   |
| 2010    | 14       | 5.76%   |
| 2011    | 12       | 4.94%   |
| 2021    | 11       | 4.53%   |
| 2008    | 9        | 3.7%    |
| 2020    | 7        | 2.88%   |
| 2009    | 5        | 2.06%   |
| Unknown | 2        | 0.82%   |
| 2024    | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 243      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 240      | 98.77%  |
| Enabled  | 3        | 1.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 242      | 99.59%  |
| Yes  | 1        | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 112      | 46.09%  |
| 32.01-64.0      | 34       | 13.99%  |
| 16.01-24.0      | 25       | 10.29%  |
| 64.01-256.0     | 23       | 9.47%   |
| 8.01-16.0       | 17       | 7%      |
| 3.01-4.0        | 15       | 6.17%   |
| 1.01-2.0        | 9        | 3.7%    |
| 24.01-32.0      | 3        | 1.23%   |
| More than 256.0 | 2        | 0.82%   |
| 0.51-1.0        | 2        | 0.82%   |
| 2.01-3.0        | 1        | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 79       | 31.6%   |
| 0.51-1.0    | 53       | 21.2%   |
| 2.01-3.0    | 38       | 15.2%   |
| 4.01-8.0    | 27       | 10.8%   |
| 3.01-4.0    | 17       | 6.8%    |
| 8.01-16.0   | 15       | 6%      |
| 0.01-0.5    | 12       | 4.8%    |
| 16.01-24.0  | 4        | 1.6%    |
| 24.01-32.0  | 3        | 1.2%    |
| 64.01-256.0 | 2        | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 140      | 56.45%  |
| 2      | 48       | 19.35%  |
| 3      | 23       | 9.27%   |
| 4      | 12       | 4.84%   |
| 6      | 6        | 2.42%   |
| 5      | 5        | 2.02%   |
| 10     | 3        | 1.21%   |
| 0      | 3        | 1.21%   |
| 7      | 2        | 0.81%   |
| 71     | 1        | 0.4%    |
| 68     | 1        | 0.4%    |
| 26     | 1        | 0.4%    |
| 15     | 1        | 0.4%    |
| 12     | 1        | 0.4%    |
| 9      | 1        | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 167      | 68.16%  |
| Yes       | 78       | 31.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 241      | 99.18%  |
| No        | 2        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 209      | 86.01%  |
| Yes       | 34       | 13.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 219      | 90.12%  |
| Yes       | 24       | 9.88%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Australia    | 76       | 31.28%  |
| USA          | 45       | 18.52%  |
| Russia       | 17       | 7%      |
| Canada       | 15       | 6.17%   |
| France       | 11       | 4.53%   |
| UK           | 10       | 4.12%   |
| Brazil       | 9        | 3.7%    |
| India        | 8        | 3.29%   |
| Germany      | 8        | 3.29%   |
| China        | 7        | 2.88%   |
| Switzerland  | 3        | 1.23%   |
| South Korea  | 3        | 1.23%   |
| Finland      | 3        | 1.23%   |
| Ecuador      | 3        | 1.23%   |
| Spain        | 2        | 0.82%   |
| Israel       | 2        | 0.82%   |
| Czechia      | 2        | 0.82%   |
| Bulgaria     | 2        | 0.82%   |
| Belgium      | 2        | 0.82%   |
| Ukraine      | 1        | 0.41%   |
| Taiwan       | 1        | 0.41%   |
| Sweden       | 1        | 0.41%   |
| South Africa | 1        | 0.41%   |
| Singapore    | 1        | 0.41%   |
| Romania      | 1        | 0.41%   |
| Poland       | 1        | 0.41%   |
| Pakistan     | 1        | 0.41%   |
| Norway       | 1        | 0.41%   |
| Netherlands  | 1        | 0.41%   |
| Mexico       | 1        | 0.41%   |
| Japan        | 1        | 0.41%   |
| Italy        | 1        | 0.41%   |
| Hong Kong    | 1        | 0.41%   |
| Unknown      | 1        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Melbourne            | 69       | 27.71%  |
| Rochester            | 16       | 6.43%   |
| Moscow               | 8        | 3.21%   |
| Sydney               | 5        | 2.01%   |
| Paris                | 4        | 1.61%   |
| London               | 4        | 1.61%   |
| Guwahati             | 4        | 1.61%   |
| Frankfurt am Main    | 4        | 1.61%   |
| Alexandria           | 4        | 1.61%   |
| Victoria             | 3        | 1.2%    |
| Vancouver            | 3        | 1.2%    |
| St Petersburg        | 3        | 1.2%    |
| Montreal             | 3        | 1.2%    |
| Guayaquil            | 3        | 1.2%    |
| Wahroonga            | 2        | 0.8%    |
| Tampa                | 2        | 0.8%    |
| Helsinki             | 2        | 0.8%    |
| Brno                 | 2        | 0.8%    |
| Brandon              | 2        | 0.8%    |
| Blanzy-la-Salonnaise | 2        | 0.8%    |
| Xuhui                | 1        | 0.4%    |
| Wheeling             | 1        | 0.4%    |
| Waxhaw               | 1        | 0.4%    |
| Varna                | 1        | 0.4%    |
| UniversitГЎrio     | 1        | 0.4%    |
| Tyumentsevo          | 1        | 0.4%    |
| Tyumen               | 1        | 0.4%    |
| Tuscaloosa           | 1        | 0.4%    |
| Tucson               | 1        | 0.4%    |
| Tours                | 1        | 0.4%    |
| Tokyo                | 1        | 0.4%    |
| Tharwa               | 1        | 0.4%    |
| Tel Aviv             | 1        | 0.4%    |
| Taishan              | 1        | 0.4%    |
| Surgut               | 1        | 0.4%    |
| Sundbyberg           | 1        | 0.4%    |
| St Andrews           | 1        | 0.4%    |
| Springfield          | 1        | 0.4%    |
| Sofia                | 1        | 0.4%    |
| Singapore            | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 124      | 176    | 35.94%  |
| Seagate                   | 67       | 255    | 19.42%  |
| Samsung Electronics       | 37       | 142    | 10.72%  |
| Toshiba                   | 20       | 28     | 5.8%    |
| Kingston                  | 16       | 21     | 4.64%   |
| Hitachi                   | 14       | 44     | 4.06%   |
| SanDisk                   | 10       | 13     | 2.9%    |
| Intel                     | 9        | 33     | 2.61%   |
| Unknown                   | 5        | 14     | 1.45%   |
| HGST                      | 5        | 71     | 1.45%   |
| SK hynix                  | 3        | 3      | 0.87%   |
| A-DATA Technology         | 3        | 4      | 0.87%   |
| SPCC                      | 2        | 2      | 0.58%   |
| OCZ                       | 2        | 6      | 0.58%   |
| Micron Technology         | 2        | 3      | 0.58%   |
| KingDian                  | 2        | 6      | 0.58%   |
| Hewlett-Packard           | 2        | 3      | 0.58%   |
| Crucial                   | 2        | 3      | 0.58%   |
| UNIC2                     | 1        | 1      | 0.29%   |
| Transcend                 | 1        | 1      | 0.29%   |
| Sun                       | 1        | 3      | 0.29%   |
| Phison Electronics        | 1        | 2      | 0.29%   |
| OWC                       | 1        | 1      | 0.29%   |
| NVMe                      | 1        | 1      | 0.29%   |
| NORCO                     | 1        | 1      | 0.29%   |
| Micron/Crucial Technology | 1        | 1      | 0.29%   |
| Maxtor                    | 1        | 1      | 0.29%   |
| LITEONIT                  | 1        | 1      | 0.29%   |
| Lenovo                    | 1        | 2      | 0.29%   |
| Kingston Technologies     | 1        | 1      | 0.29%   |
| KingSpec                  | 1        | 1      | 0.29%   |
| GLOWAY                    | 1        | 1      | 0.29%   |
| Gigabyte Technology       | 1        | 1      | 0.29%   |
| Fujitsu                   | 1        | 1      | 0.29%   |
| Corsair                   | 1        | 1      | 0.29%   |
| China                     | 1        | 1      | 0.29%   |
| BIWIN                     | 1        | 1      | 0.29%   |
| ADATA Technology          | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB          | 33       | 8.05%   |
| WDC WD10EZEX-00MFCA0 1TB          | 18       | 4.39%   |
| WDC WD10EZEX-00WN4A0 1TB          | 10       | 2.44%   |
| Toshiba DT01ACA050 500GB          | 7        | 1.71%   |
| Seagate ST500DM002-1BD142 500GB   | 7        | 1.71%   |
| Seagate ST1000DM010-2EP102 1TB    | 7        | 1.71%   |
| Seagate ST500DM002-1SB10A 500GB   | 6        | 1.46%   |
| WDC WD10EZEX-75WN4A0 1TB          | 4        | 0.98%   |
| WDC WD10EZEX-60WN4A0 1TB          | 4        | 0.98%   |
| Toshiba DT01ACA100 1TB            | 4        | 0.98%   |
| Samsung SSD 860 EVO 250GB         | 4        | 0.98%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 3        | 0.73%   |
| WDC WD10EZEX-22MFCA0 1TB          | 3        | 0.73%   |
| WDC WD10EZEX-00BBHA0 1TB          | 3        | 0.73%   |
| Seagate ST6000NM0095 6TB          | 3        | 0.73%   |
| Seagate ST6000NM0034 6TB          | 3        | 0.73%   |
| Seagate ST6000NM0014 6TB          | 3        | 0.73%   |
| Seagate ST4000NXCLAR4000 4TB      | 3        | 0.73%   |
| Seagate ST4000NM0023 4TB          | 3        | 0.73%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 2        | 0.49%   |
| WDC WD3200AAKS-75L9A0 320GB       | 2        | 0.49%   |
| WDC WD30PURX-64P6ZY0 3TB          | 2        | 0.49%   |
| WDC WD30EZRX-00MMMB0 3TB          | 2        | 0.49%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 0.49%   |
| WDC WD1001FALS-00J7B1 1TB         | 2        | 0.49%   |
| Unknown HUH728080ALE601 8TB       | 2        | 0.49%   |
| Toshiba DT01ACA200 2TB            | 2        | 0.49%   |
| SK hynix SHGS31-500GS-2 500GB SSD | 2        | 0.49%   |
| Seagate ST4000VM000-2AF166 4TB    | 2        | 0.49%   |
| Seagate ST4000DM000-1F2168 4TB    | 2        | 0.49%   |
| Seagate ST3000NC002-1DY166 3TB    | 2        | 0.49%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.49%   |
| Seagate ST2000DM001-1CH164 2TB    | 2        | 0.49%   |
| Seagate ST16000NM001G-2KK103 16TB | 2        | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.49%   |
| SanDisk WDC WDS100T2B0C 1TB       | 2        | 0.49%   |
| SanDisk WDC CL SN720 SDA 512GB    | 2        | 0.49%   |
| Samsung SSD 850 EVO 250GB         | 2        | 0.49%   |
| Samsung HD322HJ 320GB             | 2        | 0.49%   |
| Samsung HD103SJ 1TB               | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 121      | 166    | 49.79%  |
| Seagate             | 67       | 254    | 27.57%  |
| Toshiba             | 20       | 28     | 8.23%   |
| Hitachi             | 14       | 44     | 5.76%   |
| Samsung Electronics | 9        | 106    | 3.7%    |
| HGST                | 5        | 24     | 2.06%   |
| Unknown             | 2        | 11     | 0.82%   |
| Sun                 | 1        | 3      | 0.41%   |
| Maxtor              | 1        | 1      | 0.41%   |
| Lenovo              | 1        | 2      | 0.41%   |
| Hewlett-Packard     | 1        | 2      | 0.41%   |
| Fujitsu             | 1        | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 25     | 24.39%  |
| Kingston            | 16       | 21     | 19.51%  |
| Intel               | 9        | 32     | 10.98%  |
| WDC                 | 7        | 10     | 8.54%   |
| SanDisk             | 4        | 4      | 4.88%   |
| SK hynix            | 3        | 3      | 3.66%   |
| A-DATA Technology   | 3        | 4      | 3.66%   |
| SPCC                | 2        | 2      | 2.44%   |
| OCZ                 | 2        | 6      | 2.44%   |
| KingDian            | 2        | 6      | 2.44%   |
| Crucial             | 2        | 3      | 2.44%   |
| UNIC2               | 1        | 1      | 1.22%   |
| Transcend           | 1        | 1      | 1.22%   |
| Seagate             | 1        | 1      | 1.22%   |
| OWC                 | 1        | 1      | 1.22%   |
| NORCO               | 1        | 1      | 1.22%   |
| Micron Technology   | 1        | 2      | 1.22%   |
| LITEONIT            | 1        | 1      | 1.22%   |
| Hewlett-Packard     | 1        | 1      | 1.22%   |
| GLOWAY              | 1        | 1      | 1.22%   |
| Corsair             | 1        | 1      | 1.22%   |
| China               | 1        | 1      | 1.22%   |
| BIWIN               | 1        | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 201      | 642    | 66.78%  |
| SSD     | 73       | 129    | 24.25%  |
| NVMe    | 20       | 28     | 6.64%   |
| MMC     | 4        | 4      | 1.33%   |
| Unknown | 3        | 48     | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 222      | 598    | 85.38%  |
| NVMe | 20       | 28     | 7.69%   |
| SAS  | 14       | 221    | 5.38%   |
| MMC  | 4        | 4      | 1.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 133      | 157    | 43.18%  |
| 0.01-0.5   | 105      | 283    | 34.09%  |
| 1.01-2.0   | 24       | 65     | 7.79%   |
| 3.01-4.0   | 15       | 113    | 4.87%   |
| 2.01-3.0   | 13       | 28     | 4.22%   |
| 4.01-10.0  | 12       | 86     | 3.9%    |
| 10.01-20.0 | 6        | 39     | 1.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 96       | 38.71%  |
| 251-500        | 46       | 18.55%  |
| More than 3000 | 29       | 11.69%  |
| 101-250        | 26       | 10.48%  |
| 1001-2000      | 13       | 5.24%   |
| Unknown        | 11       | 4.44%   |
| 21-50          | 8        | 3.23%   |
| 2001-3000      | 7        | 2.82%   |
| 1-20           | 6        | 2.42%   |
| 51-100         | 6        | 2.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 80       | 32.65%  |
| 101-250        | 52       | 21.22%  |
| 51-100         | 29       | 11.84%  |
| More than 3000 | 17       | 6.94%   |
| 251-500        | 17       | 6.94%   |
| 501-1000       | 16       | 6.53%   |
| 21-50          | 14       | 5.71%   |
| Unknown        | 11       | 4.49%   |
| 1001-2000      | 5        | 2.04%   |
| 2001-3000      | 3        | 1.22%   |
| 0              | 1        | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB             | 3        | 3      | 6.25%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 2        | 2      | 4.17%   |
| WDC WD1001FALS-00J7B1 1TB                   | 2        | 2      | 4.17%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-08U6AA0 500GB                | 1        | 1      | 2.08%   |
| WDC WD3200AAKS-75L9A0 320GB                 | 1        | 1      | 2.08%   |
| WDC WD30PURX-64P6ZY0 3TB                    | 1        | 1      | 2.08%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 1        | 3      | 2.08%   |
| WDC WD2500HHTZ-04N21V0 250GB                | 1        | 1      | 2.08%   |
| WDC WD20EARX-00PASB0 2TB                    | 1        | 1      | 2.08%   |
| WDC WD20EARS-00MVWB0 2TB                    | 1        | 2      | 2.08%   |
| WDC WD10EZEX-60WN4A1 1TB                    | 1        | 1      | 2.08%   |
| WDC WD10EADS-00L5B1 1TB                     | 1        | 1      | 2.08%   |
| Seagate ST380211AS 80GB                     | 1        | 1      | 2.08%   |
| Seagate ST380013AS 80GB                     | 1        | 1      | 2.08%   |
| Seagate ST3250620NS 250GB                   | 1        | 2      | 2.08%   |
| Seagate ST31000524NS 1TB                    | 1        | 1      | 2.08%   |
| Seagate ST31000520AS 1TB                    | 1        | 1      | 2.08%   |
| Seagate ST31000340AS 1TB                    | 1        | 1      | 2.08%   |
| Seagate ST3000DM001-1ER166 3TB              | 1        | 1      | 2.08%   |
| Seagate ST3000DM001-1CH166 3TB              | 1        | 1      | 2.08%   |
| Seagate ST2000DM001-9YN164 2TB              | 1        | 1      | 2.08%   |
| Seagate ST2000DM001-1CH164 2TB              | 1        | 1      | 2.08%   |
| Seagate ST1000NX0313 1TB                    | 1        | 1      | 2.08%   |
| SanDisk SDSSDX240GG25 240GB                 | 1        | 1      | 2.08%   |
| Samsung Electronics SSD SM871 2.5 7mm 512GB | 1        | 1      | 2.08%   |
| Samsung Electronics SSD 870 EVO 500GB       | 1        | 3      | 2.08%   |
| Samsung Electronics HD154UI 1TB             | 1        | 1      | 2.08%   |
| Samsung Electronics HD103UI 1TB             | 1        | 1      | 2.08%   |
| Maxtor 6Y080L0 82GB                         | 1        | 1      | 2.08%   |
| LITEONIT LCT-256M3S 256GB SSD               | 1        | 1      | 2.08%   |
| Kingston SV100S264G 64GB SSD                | 1        | 1      | 2.08%   |
| Kingston SNS4151S316G 16GB SSD              | 1        | 1      | 2.08%   |
| Kingston SHFS37A120G 120GB SSD              | 1        | 1      | 2.08%   |
| Intel SSDSCKKW256G8 256GB                   | 1        | 1      | 2.08%   |
| Intel SSDSC2KG480G8 480GB                   | 1        | 2      | 2.08%   |
| Intel SSDSA2M120G2GC 120GB                  | 1        | 1      | 2.08%   |
| Intel SSDSA2M080G2LE 80GB                   | 1        | 19     | 2.08%   |
| Hitachi HTS542512K9A300 120GB               | 1        | 1      | 2.08%   |
| Hitachi HDS728080PLA380 82GB                | 1        | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 28.26%  |
| Seagate             | 13       | 15     | 28.26%  |
| Samsung Electronics | 4        | 6      | 8.7%    |
| Intel               | 4        | 23     | 8.7%    |
| Hitachi             | 4        | 4      | 8.7%    |
| Kingston            | 3        | 3      | 6.52%   |
| SanDisk             | 1        | 1      | 2.17%   |
| Maxtor              | 1        | 1      | 2.17%   |
| LITEONIT            | 1        | 1      | 2.17%   |
| HGST                | 1        | 1      | 2.17%   |
| Crucial             | 1        | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 38.24%  |
| Seagate             | 13       | 15     | 38.24%  |
| Hitachi             | 4        | 4      | 11.76%  |
| Samsung Electronics | 2        | 2      | 5.88%   |
| Maxtor              | 1        | 1      | 2.94%   |
| HGST                | 1        | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 40     | 70%     |
| SSD  | 12       | 33     | 30%     |

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
| Works    | 200      | 514    | 72.46%  |
| Detected | 38       | 264    | 13.77%  |
| Malfunc  | 38       | 73     | 13.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 212      | 70.9%   |
| AMD                         | 22       | 7.36%   |
| Samsung Electronics         | 11       | 3.68%   |
| ASMedia Technology          | 11       | 3.68%   |
| LSI Logic / Symbios Logic   | 8        | 2.68%   |
| SanDisk                     | 5        | 1.67%   |
| Marvell Technology Group    | 5        | 1.67%   |
| JMicron Technology          | 5        | 1.67%   |
| Broadcom / LSI              | 5        | 1.67%   |
| Adaptec                     | 5        | 1.67%   |
| VIA Technologies            | 1        | 0.33%   |
| SK hynix                    | 1        | 0.33%   |
| Silicon Image               | 1        | 0.33%   |
| Phison Electronics          | 1        | 0.33%   |
| Nvidia                      | 1        | 0.33%   |
| Micron/Crucial Technology   | 1        | 0.33%   |
| Micron Technology           | 1        | 0.33%   |
| Kingston Technology Company | 1        | 0.33%   |
| ADATA Technology            | 1        | 0.33%   |
| 3ware                       | 1        | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43       | 12.01%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29       | 8.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 24       | 6.7%    |
| Intel SATA Controller [RAID mode]                                                       | 19       | 5.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19       | 5.31%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 2.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 2.51%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 8        | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 1.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 1.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 1.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 1.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.4%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.4%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.12%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 3        | 0.84%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 3        | 0.84%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.84%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.84%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 0.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 0.84%   |
| Adaptec AAC-RAID                                                                        | 3        | 0.84%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 2        | 0.56%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 0.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2        | 0.56%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 2        | 0.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.56%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 2        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 191      | 63.46%  |
| IDE  | 41       | 13.62%  |
| RAID | 34       | 11.3%   |
| NVMe | 20       | 6.64%   |
| SAS  | 10       | 3.32%   |
| SCSI | 5        | 1.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 221      | 90.95%  |
| AMD    | 22       | 9.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel Core i5-4460 CPU @ 3.20GHz     | 22       | 9.05%   |
| Intel Core i5-9400 CPU @ 2.90GHz     | 21       | 8.64%   |
| Intel Core i5-7400 CPU @ 3.00GHz     | 17       | 7%      |
| Intel Core i7-6700 CPU @ 3.40GHz     | 11       | 4.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz     | 9        | 3.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz     | 6        | 2.47%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 4        | 1.65%   |
| AMD FX-6300 Six-Core Processor       | 4        | 1.65%   |
| Intel Xeon E-2136 CPU @ 3.30GHz      | 3        | 1.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 3        | 1.23%   |
| Intel Core i5-10500 CPU @ 3.10GHz    | 3        | 1.23%   |
| Intel Core i5-10400 CPU @ 2.90GHz    | 3        | 1.23%   |
| Intel Core i3-4160 CPU @ 3.60GHz     | 3        | 1.23%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz | 3        | 1.23%   |
| Intel Xeon CPU X5680 @ 3.33GHz       | 2        | 0.82%   |
| Intel Xeon CPU W3530 @ 2.80GHz       | 2        | 0.82%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz   | 2        | 0.82%   |
| Intel Core i9-10900K CPU @ 3.70GHz   | 2        | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz     | 2        | 0.82%   |
| Intel Core i5-9500 CPU @ 3.00GHz     | 2        | 0.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz     | 2        | 0.82%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz | 2        | 0.82%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz    | 2        | 0.82%   |
| Intel Atom CPU D525 @ 1.80GHz        | 2        | 0.82%   |
| AMD Ryzen 5 1600 Six-Core Processor  | 2        | 0.82%   |
| AMD Phenom II X6 1090T Processor     | 2        | 0.82%   |
| Intel Xeon W-2155 CPU @ 3.30GHz      | 1        | 0.41%   |
| Intel Xeon W-2125 CPU @ 4.00GHz      | 1        | 0.41%   |
| Intel Xeon W-1290 CPU @ 3.20GHz      | 1        | 0.41%   |
| Intel Xeon CPU X5660 @ 2.80GHz       | 1        | 0.41%   |
| Intel Xeon CPU X5650 @ 2.67GHz       | 1        | 0.41%   |
| Intel Xeon CPU X5450 @ 3.00GHz       | 1        | 0.41%   |
| Intel Xeon CPU W3680 @ 3.33GHz       | 1        | 0.41%   |
| Intel Xeon CPU E5620 @ 2.40GHz       | 1        | 0.41%   |
| Intel Xeon CPU E5440 @ 2.83GHz       | 1        | 0.41%   |
| Intel Xeon CPU E5410 @ 2.33GHz       | 1        | 0.41%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz  | 1        | 0.41%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz  | 1        | 0.41%   |
| Intel Xeon CPU E5-2687W v3 @ 3.10GHz | 1        | 0.41%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz   | 1        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 89       | 36.63%  |
| Intel Core i7           | 46       | 18.93%  |
| Intel Xeon              | 36       | 14.81%  |
| Intel Core i3           | 12       | 4.94%   |
| AMD FX                  | 8        | 3.29%   |
| Intel Core 2 Duo        | 7        | 2.88%   |
| Intel Atom              | 7        | 2.88%   |
| Intel Pentium           | 5        | 2.06%   |
| Intel Core i9           | 5        | 2.06%   |
| Intel Pentium Dual-Core | 4        | 1.65%   |
| Intel Celeron           | 4        | 1.65%   |
| AMD Ryzen 5             | 4        | 1.65%   |
| Other                   | 3        | 1.23%   |
| Intel Core 2 Quad       | 2        | 0.82%   |
| AMD Phenom II X6        | 2        | 0.82%   |
| Intel Pentium Dual      | 1        | 0.41%   |
| AMD Ryzen Threadripper  | 1        | 0.41%   |
| AMD Ryzen 7             | 1        | 0.41%   |
| AMD Ryzen 3             | 1        | 0.41%   |
| AMD GX                  | 1        | 0.41%   |
| AMD E2                  | 1        | 0.41%   |
| AMD Athlon              | 1        | 0.41%   |
| AMD A8                  | 1        | 0.41%   |
| AMD A10                 | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 119      | 48.97%  |
| 6      | 53       | 21.81%  |
| 2      | 34       | 13.99%  |
| 8      | 10       | 4.12%   |
| 12     | 6        | 2.47%   |
| 3      | 5        | 2.06%   |
| 10     | 4        | 1.65%   |
| 16     | 3        | 1.23%   |
| 1      | 3        | 1.23%   |
| 20     | 2        | 0.82%   |
| 28     | 1        | 0.41%   |
| 24     | 1        | 0.41%   |
| 18     | 1        | 0.41%   |
| 14     | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 229      | 94.24%  |
| 2      | 13       | 5.35%   |
| 0      | 1        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 131      | 53.91%  |
| 2      | 112      | 46.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 235      | 96.71%  |
| Unknown        | 8        | 3.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 46       | 18.78%  |
| 0x906ea    | 25       | 10.2%   |
| 0x906e9    | 25       | 10.2%   |
| Unknown    | 18       | 7.35%   |
| 0x506e3    | 13       | 5.31%   |
| 0x1067a    | 10       | 4.08%   |
| 0x206a7    | 9        | 3.67%   |
| 0x306a9    | 8        | 3.27%   |
| 0xa0653    | 6        | 2.45%   |
| 0x306f2    | 6        | 2.45%   |
| 0x206d7    | 6        | 2.45%   |
| 0xa0655    | 5        | 2.04%   |
| 0x906ed    | 5        | 2.04%   |
| 0x906ec    | 5        | 2.04%   |
| 0x50654    | 5        | 2.04%   |
| 0x206c2    | 5        | 2.04%   |
| 0x06000852 | 5        | 2.04%   |
| 0x106ca    | 4        | 1.63%   |
| 0x406c4    | 3        | 1.22%   |
| 0x406f1    | 2        | 0.82%   |
| 0x406c3    | 2        | 0.82%   |
| 0x106e5    | 2        | 0.82%   |
| 0x106a5    | 2        | 0.82%   |
| 0x10676    | 2        | 0.82%   |
| 0x08701013 | 2        | 0.82%   |
| 0x08001137 | 2        | 0.82%   |
| 0x03000027 | 2        | 0.82%   |
| 0x010000dc | 2        | 0.82%   |
| 0xa0671    | 1        | 0.41%   |
| 0x906eb    | 1        | 0.41%   |
| 0x906c0    | 1        | 0.41%   |
| 0x90675    | 1        | 0.41%   |
| 0x90672    | 1        | 0.41%   |
| 0x6fd      | 1        | 0.41%   |
| 0x6fb      | 1        | 0.41%   |
| 0x506ca    | 1        | 0.41%   |
| 0x50663    | 1        | 0.41%   |
| 0x406e3    | 1        | 0.41%   |
| 0x40651    | 1        | 0.41%   |
| 0x30678    | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 61       | 25.1%   |
| Haswell     | 54       | 22.22%  |
| Skylake     | 21       | 8.64%   |
| SandyBridge | 16       | 6.58%   |
| Penryn      | 15       | 6.17%   |
| CometLake   | 11       | 4.53%   |
| IvyBridge   | 10       | 4.12%   |
| Piledriver  | 8        | 3.29%   |
| Westmere    | 6        | 2.47%   |
| Silvermont  | 6        | 2.47%   |
| Broadwell   | 6        | 2.47%   |
| Nehalem     | 4        | 1.65%   |
| Bonnell     | 4        | 1.65%   |
| Unknown     | 4        | 1.65%   |
| Zen 2       | 3        | 1.23%   |
| Zen+        | 2        | 0.82%   |
| Zen         | 2        | 0.82%   |
| K10 Llano   | 2        | 0.82%   |
| K10         | 2        | 0.82%   |
| Jaguar      | 2        | 0.82%   |
| Core        | 2        | 0.82%   |
| Goldmont    | 1        | 0.41%   |
| Bulldozer   | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 144      | 57.37%  |
| Nvidia                                       | 54       | 21.51%  |
| AMD                                          | 40       | 15.94%  |
| ASPEED Technology                            | 7        | 2.79%   |
| Matrox Electronics Systems                   | 3        | 1.2%    |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.8%    |
| Silicon Motion                               | 1        | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 32       | 12.45%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30       | 11.67%  |
| Intel HD Graphics 630                                                                    | 23       | 8.95%   |
| Intel HD Graphics 530                                                                    | 8        | 3.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 8        | 3.11%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8        | 3.11%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 2.72%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7        | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.95%   |
| Nvidia GP107GL [Quadro P400]                                                             | 4        | 1.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 1.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 1.56%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 3        | 1.17%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 1.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.17%   |
| AMD RS780L [Radeon 3000]                                                                 | 3        | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 1.17%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.78%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 2        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2        | 0.78%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.78%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.39%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                           | 1        | 0.39%   |
| Silicon Motion SM712 LynxEM+                                                             | 1        | 0.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.39%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.39%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1        | 0.39%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1        | 0.39%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.39%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.39%   |
| Nvidia GP106GL [Quadro P2200]                                                            | 1        | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 136      | 55.97%  |
| 1 x Nvidia              | 46       | 18.93%  |
| 1 x AMD                 | 38       | 15.64%  |
| 1 x ASPEED              | 5        | 2.06%   |
| 2 x Nvidia              | 3        | 1.23%   |
| 1 x Matrox              | 3        | 1.23%   |
| Intel + Nvidia          | 3        | 1.23%   |
| Other                   | 2        | 0.82%   |
| 1 x XGI                 | 2        | 0.82%   |
| 3 x Nvidia + 1 x ASPEED | 1        | 0.41%   |
| 2 x AMD                 | 1        | 0.41%   |
| 1 x Silicon Motion      | 1        | 0.41%   |
| Nvidia + ASPEED         | 1        | 0.41%   |
| Intel + AMD             | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 178      | 72.36%  |
| Unknown     | 39       | 15.85%  |
| Proprietary | 29       | 11.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 154      | 63.11%  |
| 1.01-2.0   | 29       | 11.89%  |
| 0.51-1.0   | 24       | 9.84%   |
| 7.01-8.0   | 11       | 4.51%   |
| 0.01-0.5   | 11       | 4.51%   |
| 3.01-4.0   | 9        | 3.69%   |
| 4.01-5.0   | 3        | 1.23%   |
| 5.01-6.0   | 1        | 0.41%   |
| 2.01-3.0   | 1        | 0.41%   |
| 16.01-24.0 | 1        | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 39       | 28.26%  |
| Samsung Electronics     | 19       | 13.77%  |
| Hewlett-Packard         | 13       | 9.42%   |
| AOC                     | 11       | 7.97%   |
| Goldstar                | 9        | 6.52%   |
| Philips                 | 8        | 5.8%    |
| Ancor Communications    | 7        | 5.07%   |
| Acer                    | 7        | 5.07%   |
| BenQ                    | 4        | 2.9%    |
| ___                     | 2        | 1.45%   |
| ViewSonic               | 2        | 1.45%   |
| Unknown                 | 2        | 1.45%   |
| NEC Computers           | 2        | 1.45%   |
| Eizo                    | 2        | 1.45%   |
| Toshiba                 | 1        | 0.72%   |
| Sceptre Tech            | 1        | 0.72%   |
| Packard Bell            | 1        | 0.72%   |
| NME                     | 1        | 0.72%   |
| LG Electronics          | 1        | 0.72%   |
| Lenovo                  | 1        | 0.72%   |
| Iiyama                  | 1        | 0.72%   |
| GVV                     | 1        | 0.72%   |
| Founder                 | 1        | 0.72%   |
| Chi Mei Optoelectronics | 1        | 0.72%   |
| AMW                     | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 6        | 3.95%   |
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                    | 6        | 3.95%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 4        | 2.63%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 3        | 1.97%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 2        | 1.32%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2        | 1.32%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch        | 2        | 1.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 1.32%   |
| Dell P2417H DELA0DA 1920x1080 527x296mm 23.8-inch                    | 2        | 1.32%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                    | 2        | 1.32%   |
| ___ LCDTV16 ___0101 1920x1080                                        | 1        | 0.66%   |
| ___ LCD TV ___9000 1360x768                                          | 1        | 0.66%   |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch               | 1        | 0.66%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 495x291mm 22.6-inch            | 1        | 0.66%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1        | 0.66%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                  | 1        | 0.66%   |
| Toshiba LCD Monitor 1 1 5" LCD000D 1024x768 304x228mm 15.0-inch      | 1        | 0.66%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch       | 1        | 0.66%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch    | 1        | 0.66%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 0.66%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 0.66%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch   | 1        | 0.66%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch    | 1        | 0.66%   |
| Samsung Electronics S27E391 SAM0C16 1920x1080 598x336mm 27.0-inch    | 1        | 0.66%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch     | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1080                 | 1        | 0.66%   |
| Samsung Electronics LCD Monitor C27F591 1440x900                     | 1        | 0.66%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 1        | 0.66%   |
| Philips PHL 284E5 PHLC0DE 1920x1080 621x341mm 27.9-inch              | 1        | 0.66%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch              | 1        | 0.66%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 0.66%   |
| Philips PHL 241V8B PHLC314 1920x1080 527x296mm 23.8-inch             | 1        | 0.66%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch              | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 48.57%  |
| 1366x768 (WXGA)    | 9        | 6.43%   |
| 3840x2160 (4K)     | 8        | 5.71%   |
| 2560x1440 (QHD)    | 8        | 5.71%   |
| 1680x1050 (WSXGA+) | 8        | 5.71%   |
| 1280x1024 (SXGA)   | 8        | 5.71%   |
| 1920x1200 (WUXGA)  | 7        | 5%      |
| 1440x900 (WXGA+)   | 5        | 3.57%   |
| Unknown            | 5        | 3.57%   |
| 1600x900 (HD+)     | 3        | 2.14%   |
| 3840x1200          | 2        | 1.43%   |
| 3840x1080          | 2        | 1.43%   |
| 1600x1200          | 2        | 1.43%   |
| 1024x768 (XGA)     | 2        | 1.43%   |
| 5760x1080          | 1        | 0.71%   |
| 1680x1080          | 1        | 0.71%   |
| 1360x768           | 1        | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 31       | 22.3%   |
| 23      | 22       | 15.83%  |
| 21      | 20       | 14.39%  |
| Unknown | 13       | 9.35%   |
| 27      | 12       | 8.63%   |
| 22      | 7        | 5.04%   |
| 19      | 7        | 5.04%   |
| 18      | 7        | 5.04%   |
| 20      | 4        | 2.88%   |
| 15      | 4        | 2.88%   |
| 17      | 3        | 2.16%   |
| 72      | 2        | 1.44%   |
| 31      | 2        | 1.44%   |
| 42      | 1        | 0.72%   |
| 32      | 1        | 0.72%   |
| 26      | 1        | 0.72%   |
| 25      | 1        | 0.72%   |
| 16      | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 62       | 46.27%  |
| 401-500     | 39       | 29.1%   |
| Unknown     | 13       | 9.7%    |
| 301-350     | 7        | 5.22%   |
| 351-400     | 5        | 3.73%   |
| 601-700     | 4        | 2.99%   |
| 1501-2000   | 2        | 1.49%   |
| 701-800     | 1        | 0.75%   |
| 901-1000    | 1        | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 87       | 66.41%  |
| 16/10   | 21       | 16.03%  |
| Unknown | 11       | 8.4%    |
| 5/4     | 7        | 5.34%   |
| 4/3     | 5        | 3.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 65       | 47.45%  |
| 151-200        | 15       | 10.95%  |
| Unknown        | 13       | 9.49%   |
| 301-350        | 12       | 8.76%   |
| 251-300        | 12       | 8.76%   |
| 141-150        | 9        | 6.57%   |
| 101-110        | 4        | 2.92%   |
| 351-500        | 3        | 2.19%   |
| More than 1000 | 2        | 1.46%   |
| 111-120        | 1        | 0.73%   |
| 501-1000       | 1        | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 87       | 65.41%  |
| 101-120 | 25       | 18.8%   |
| Unknown | 13       | 9.77%   |
| 121-160 | 5        | 3.76%   |
| 1-50    | 2        | 1.5%    |
| 161-240 | 1        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 119      | 47.79%  |
| 1     | 108      | 43.37%  |
| 2     | 20       | 8.03%   |
| 3     | 2        | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Realtek Semiconductor       | 136      | 44.74%  |
| Intel                       | 100      | 32.89%  |
| Broadcom                    | 17       | 5.59%   |
| Qualcomm Atheros            | 7        | 2.3%    |
| Ralink Technology           | 6        | 1.97%   |
| TP-Link                     | 5        | 1.64%   |
| D-Link System               | 3        | 0.99%   |
| Mellanox Technologies       | 2        | 0.66%   |
| Marvell Technology Group    | 2        | 0.66%   |
| D-Link                      | 2        | 0.66%   |
| Broadcom Limited            | 2        | 0.66%   |
| Aquantia                    | 2        | 0.66%   |
| 3Com                        | 2        | 0.66%   |
| Xilinx                      | 1        | 0.33%   |
| Xiaomi                      | 1        | 0.33%   |
| VIA Technologies            | 1        | 0.33%   |
| Sierra Wireless             | 1        | 0.33%   |
| Samsung Electronics         | 1        | 0.33%   |
| NetGear                     | 1        | 0.33%   |
| MYRICOM                     | 1        | 0.33%   |
| MediaTek                    | 1        | 0.33%   |
| LSI                         | 1        | 0.33%   |
| Linux 2.6.31.6 with s3c-udc | 1        | 0.33%   |
| Linksys                     | 1        | 0.33%   |
| ICS Advent                  | 1        | 0.33%   |
| Huawei Technologies         | 1        | 0.33%   |
| Exar                        | 1        | 0.33%   |
| Dresden Elektronik          | 1        | 0.33%   |
| Cisco Systems               | 1        | 0.33%   |
| ASIX Electronics            | 1        | 0.33%   |
| Apple                       | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 121      | 35.91%  |
| Intel Ethernet Connection (2) I219-LM                                          | 15       | 4.45%   |
| Intel Ethernet Connection I217-LM                                              | 14       | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 3.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7        | 2.08%   |
| Intel I211 Gigabit Network Connection                                          | 7        | 2.08%   |
| Intel Ethernet Connection (2) I219-V                                           | 7        | 2.08%   |
| Intel 82574L Gigabit Network Connection                                        | 6        | 1.78%   |
| Intel I350 Gigabit Network Connection                                          | 5        | 1.48%   |
| Intel Ethernet Connection (7) I219-LM                                          | 5        | 1.48%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5        | 1.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5        | 1.48%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 1.19%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3        | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                                | 3        | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 0.89%   |
| Intel Ethernet Controller X550                                                 | 3        | 0.89%   |
| Intel Ethernet Controller I225-V                                               | 3        | 0.89%   |
| Intel 82580 Gigabit Network Connection                                         | 3        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 0.59%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 0.59%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 2        | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 2        | 0.59%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.59%   |
| Xilinx Network controller                                                      | 1        | 0.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1        | 0.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1        | 0.3%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]            | 1        | 0.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.3%    |
| TP-Link 802.11ac WLAN Adapter                                                  | 1        | 0.3%    |
| TP-Link 802.11ac NIC                                                           | 1        | 0.3%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                | 1        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 21.05%  |
| Intel                 | 7        | 18.42%  |
| Ralink Technology     | 6        | 15.79%  |
| TP-Link               | 5        | 13.16%  |
| Qualcomm Atheros      | 3        | 7.89%   |
| D-Link                | 2        | 5.26%   |
| Broadcom              | 2        | 5.26%   |
| Sierra Wireless       | 1        | 2.63%   |
| NetGear               | 1        | 2.63%   |
| MediaTek              | 1        | 2.63%   |
| Linksys               | 1        | 2.63%   |
| D-Link System         | 1        | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 7.69%   |
| Ralink MT7601U Wireless Adapter                                      | 3        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 5.13%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2        | 5.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 2.56%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]  | 1        | 2.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 2.56%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 2.56%   |
| TP-Link 802.11ac NIC                                                 | 1        | 2.56%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                      | 1        | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 2.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 2.56%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 2.56%   |
| Ralink RT5572 Wireless Adapter                                       | 1        | 2.56%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 2.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 2.56%   |
| NetGear A6150                                                        | 1        | 2.56%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                   | 1        | 2.56%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]  | 1        | 2.56%   |
| Intel Wireless 7260                                                  | 1        | 2.56%   |
| Intel Wireless 3165                                                  | 1        | 2.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 2.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 2.56%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]    | 1        | 2.56%   |
| D-Link DWA-160 Xtreme N Dual Band USB Adapter(rev.C1)                | 1        | 2.56%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 2.56%   |
| D-Link 802.11 n WLAN                                                 | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 135      | 49.82%  |
| Intel                    | 97       | 35.79%  |
| Broadcom                 | 15       | 5.54%   |
| Qualcomm Atheros         | 4        | 1.48%   |
| Marvell Technology Group | 2        | 0.74%   |
| D-Link System            | 2        | 0.74%   |
| Broadcom Limited         | 2        | 0.74%   |
| Aquantia                 | 2        | 0.74%   |
| 3Com                     | 2        | 0.74%   |
| Xiaomi                   | 1        | 0.37%   |
| VIA Technologies         | 1        | 0.37%   |
| Samsung Electronics      | 1        | 0.37%   |
| MYRICOM                  | 1        | 0.37%   |
| Mellanox Technologies    | 1        | 0.37%   |
| ICS Advent               | 1        | 0.37%   |
| Huawei Technologies      | 1        | 0.37%   |
| Cisco Systems            | 1        | 0.37%   |
| ASIX Electronics         | 1        | 0.37%   |
| Apple                    | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 121      | 41.44%  |
| Intel Ethernet Connection (2) I219-LM                                          | 15       | 5.14%   |
| Intel Ethernet Connection I217-LM                                              | 14       | 4.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7        | 2.4%    |
| Intel I211 Gigabit Network Connection                                          | 7        | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                           | 7        | 2.4%    |
| Intel 82574L Gigabit Network Connection                                        | 6        | 2.05%   |
| Intel I350 Gigabit Network Connection                                          | 5        | 1.71%   |
| Intel Ethernet Connection (7) I219-LM                                          | 5        | 1.71%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5        | 1.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5        | 1.71%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 1.37%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4        | 1.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 1.03%   |
| Intel Ethernet Controller X550                                                 | 3        | 1.03%   |
| Intel Ethernet Controller I225-V                                               | 3        | 1.03%   |
| Intel 82580 Gigabit Network Connection                                         | 3        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.68%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 0.68%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 2        | 0.68%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.34%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.34%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.34%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                             | 1        | 0.34%   |
| Mellanox MT27520 Family [ConnectX-3 Pro]                                       | 1        | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.34%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1        | 0.34%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                               | 1        | 0.34%   |
| Intel Ethernet Controller I226-LM                                              | 1        | 0.34%   |
| Intel Ethernet Controller I219-LM                                              | 1        | 0.34%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 241      | 85.77%  |
| WiFi     | 34       | 12.1%   |
| Modem    | 4        | 1.42%   |
| Unknown  | 2        | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 229      | 95.82%  |
| WiFi     | 10       | 4.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 123      | 50.62%  |
| 2     | 96       | 39.51%  |
| 3     | 12       | 4.94%   |
| 4     | 6        | 2.47%   |
| 5     | 2        | 0.82%   |
| 0     | 2        | 0.82%   |
| 8     | 1        | 0.41%   |
| 6     | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 225      | 92.21%  |
| Yes  | 19       | 7.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 28%     |
| Intel                           | 5        | 20%     |
| Broadcom                        | 4        | 16%     |
| Realtek Semiconductor           | 3        | 12%     |
| Qualcomm Atheros Communications | 3        | 12%     |
| ASUSTek Computer                | 2        | 8%      |
| Dynex                           | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 7        | 28%     |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 12%     |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 8%      |
| Intel Bluetooth wireless interface                       | 2        | 8%      |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 8%      |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 8%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1        | 4%      |
| Intel AX210 Bluetooth                                    | 1        | 4%      |
| Intel AX201 Bluetooth                                    | 1        | 4%      |
| Intel AX200 Bluetooth                                    | 1        | 4%      |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 4%      |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 4%      |
| Broadcom ANYCOM Blue USB-200/250                         | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 189      | 62.38%  |
| AMD                  | 50       | 16.5%   |
| Nvidia               | 49       | 16.17%  |
| Logitech             | 3        | 0.99%   |
| C-Media Electronics  | 3        | 0.99%   |
| Texas Instruments    | 2        | 0.66%   |
| Creative Labs        | 2        | 0.66%   |
| KTMicro              | 1        | 0.33%   |
| Harman International | 1        | 0.33%   |
| GN Netcom            | 1        | 0.33%   |
| Ensoniq              | 1        | 0.33%   |
| ASUSTek Computer     | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 43       | 12.08%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 35       | 9.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 31       | 8.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 29       | 8.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 17       | 4.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15       | 4.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10       | 2.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9        | 2.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8        | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 2.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6        | 1.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 6        | 1.69%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 6        | 1.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6        | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6        | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 1.4%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 5        | 1.4%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 5        | 1.4%    |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 5        | 1.4%    |
| AMD FCH Azalia Controller                                                                         | 5        | 1.4%    |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4        | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4        | 1.12%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3        | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3        | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 0.84%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 0.84%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 2        | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 0.56%   |
| Logitech Headset H390                                                                             | 2        | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.56%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2        | 0.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2        | 0.56%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 2        | 0.56%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 54       | 22.22%  |
| Samsung Electronics | 34       | 13.99%  |
| Crucial             | 29       | 11.93%  |
| SK hynix            | 28       | 11.52%  |
| Unknown             | 27       | 11.11%  |
| Micron Technology   | 18       | 7.41%   |
| G.Skill             | 16       | 6.58%   |
| GeIL                | 9        | 3.7%    |
| Corsair             | 6        | 2.47%   |
| A-DATA Technology   | 5        | 2.06%   |
| Team                | 4        | 1.65%   |
| Patriot             | 4        | 1.65%   |
| PNY                 | 2        | 0.82%   |
| Transcend           | 1        | 0.41%   |
| Nanya Technology    | 1        | 0.41%   |
| Mushkin             | 1        | 0.41%   |
| Kingmax             | 1        | 0.41%   |
| Hewlett-Packard     | 1        | 0.41%   |
| Elpida              | 1        | 0.41%   |
| Apacer              | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM CL16-16-16 D4-2400 8GB DIMM DDR4 2400MT/s     | 9        | 3.4%    |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s         | 9        | 3.4%    |
| G.Skill RAM F4-2666C19-8GIS 8192MB DIMM DDR4 3200MT/s      | 9        | 3.4%    |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3                 | 6        | 2.26%   |
| Kingston RAM 9905678-173.A00G 8GB DIMM DDR4 2400MT/s       | 5        | 1.89%   |
| Crucial RAM CT8G4DFD8213.C16FBD2 8192MB DIMM DDR4 2500MT/s | 5        | 1.89%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s         | 4        | 1.51%   |
| Samsung RAM Module 8192MB DIMM DDR4 3200MT/s               | 4        | 1.51%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s        | 4        | 1.51%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 4        | 1.51%   |
| Crucial RAM CT8G4DFS8213.C8FDD1 8GB DIMM DDR4 2400MT/s     | 4        | 1.51%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 3000MT/s   | 4        | 1.51%   |
| Kingston RAM 99U5471-058.A00LF 8GB DIMM DDR3 1600MT/s      | 3        | 1.13%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s      | 3        | 1.13%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 2        | 0.75%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 2        | 0.75%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s              | 2        | 0.75%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 2        | 0.75%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 2        | 0.75%   |
| PNY RAM M4U08S681LJJJ43-12 8GB DIMM DDR4 2666MT/s          | 2        | 0.75%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s             | 2        | 0.75%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2666MT/s         | 2        | 0.75%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s       | 2        | 0.75%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s        | 2        | 0.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s        | 2        | 0.75%   |
| Crucial RAM CT8G4DFS8266.C8FN 8GB DIMM DDR4 2667MT/s       | 2        | 0.75%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s    | 2        | 0.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s               | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                     | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                    | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s               | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM 800MT/s                     | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM                             | 1        | 0.38%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                 | 1        | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR3 800MT/s              | 1        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 103      | 46.19%  |
| DDR3         | 89       | 39.91%  |
| Unknown      | 12       | 5.38%   |
| DDR2         | 10       | 4.48%   |
| DRAM         | 4        | 1.79%   |
| SDRAM        | 2        | 0.9%    |
| LPDDR4       | 1        | 0.45%   |
| DDR2 FB-DIMM | 1        | 0.45%   |
| DDR          | 1        | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 208      | 93.69%  |
| SODIMM | 12       | 5.41%   |
| RIMM   | 2        | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 110      | 46.22%  |
| 4096  | 51       | 21.43%  |
| 16384 | 41       | 17.23%  |
| 2048  | 23       | 9.66%   |
| 32768 | 7        | 2.94%   |
| 1024  | 6        | 2.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 58       | 24.17%  |
| 2400    | 41       | 17.08%  |
| 1333    | 27       | 11.25%  |
| 3200    | 21       | 8.75%   |
| 2667    | 15       | 6.25%   |
| 2133    | 13       | 5.42%   |
| 800     | 12       | 5%      |
| 667     | 6        | 2.5%    |
| 3000    | 5        | 2.08%   |
| 2666    | 5        | 2.08%   |
| 2500    | 5        | 2.08%   |
| 2800    | 4        | 1.67%   |
| Unknown | 4        | 1.67%   |
| 1800    | 3        | 1.25%   |
| 3600    | 2        | 0.83%   |
| 2134    | 2        | 0.83%   |
| 2000    | 2        | 0.83%   |
| 1648    | 2        | 0.83%   |
| 65535   | 1        | 0.42%   |
| 4333    | 1        | 0.42%   |
| 3933    | 1        | 0.42%   |
| 3500    | 1        | 0.42%   |
| 3466    | 1        | 0.42%   |
| 2933    | 1        | 0.42%   |
| 2866    | 1        | 0.42%   |
| 2465    | 1        | 0.42%   |
| 1867    | 1        | 0.42%   |
| 1866    | 1        | 0.42%   |
| 1336    | 1        | 0.42%   |
| 1067    | 1        | 0.42%   |
| 400     | 1        | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 3        | 50%     |
| Star Micronics     | 1        | 16.67%  |
| Canon              | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Star Micronics TSP100ECO/TSP100II | 1        | 16.67%  |
| HP LaserJet 400 M401n             | 1        | 16.67%  |
| HP LaserJet 3030                  | 1        | 16.67%  |
| HP LaserJet 1020                  | 1        | 16.67%  |
| Canon MF210 Series                | 1        | 16.67%  |
| Brother MFC-9130CW                | 1        | 16.67%  |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 2        | 25%     |
| Z-Star Microelectronics  | 1        | 12.5%   |
| WaveRider Communications | 1        | 12.5%   |
| Samsung Electronics      | 1        | 12.5%   |
| Realtek Semiconductor    | 1        | 12.5%   |
| Microsoft                | 1        | 12.5%   |
| Generalplus Technology   | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera               | 1        | 12.5%   |
| WaveRider USB 2.0 Camera                 | 1        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 12.5%   |
| Realtek Web Camera                       | 1        | 12.5%   |
| Microsoft LifeCam HD-5000                | 1        | 12.5%   |
| Logitech Webcam C310                     | 1        | 12.5%   |
| Logitech HD Pro Webcam C920              | 1        | 12.5%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 12.5%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 178      | 72.06%  |
| 1     | 44       | 17.81%  |
| 2     | 13       | 5.26%   |
| 4     | 8        | 3.24%   |
| 3     | 4        | 1.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 39       | 37.14%  |
| Communication controller | 28       | 26.67%  |
| Net/wireless             | 15       | 14.29%  |
| Unassigned class         | 9        | 8.57%   |
| Net/ethernet             | 9        | 8.57%   |
| Storage/raid             | 1        | 0.95%   |
| Sound                    | 1        | 0.95%   |
| Network                  | 1        | 0.95%   |
| Multimedia controller    | 1        | 0.95%   |
| Modem                    | 1        | 0.95%   |

