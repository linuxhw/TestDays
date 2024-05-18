CentOS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for CentOS.

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

Total: 617

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H77N-WIFI                   | [3a99c46a79](https://linux-hardware.org/?probe=3a99c46a79) | Mar 30, 2024 |
| HP            | ProLiant ML10 v2            | [6f3897abd9](https://linux-hardware.org/?probe=6f3897abd9) | Mar 15, 2024 |
| Gigabyte      | B550M DS3H                  | [0bea57057c](https://linux-hardware.org/?probe=0bea57057c) | Mar 13, 2024 |
| Lenovo        | 32CB SDK0T76530 WIN 3556... | [c71cf6708c](https://linux-hardware.org/?probe=c71cf6708c) | Feb 19, 2024 |
| Gigabyte      | H77N-WIFI                   | [6c0119ee26](https://linux-hardware.org/?probe=6c0119ee26) | Feb 19, 2024 |
| AZW           | Green G4 10                 | [143e042311](https://linux-hardware.org/?probe=143e042311) | Feb 08, 2024 |
| Gigabyte      | EP45-DS3L                   | [7c90f3665f](https://linux-hardware.org/?probe=7c90f3665f) | Jan 27, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | [5a711c0ff0](https://linux-hardware.org/?probe=5a711c0ff0) | Jan 20, 2024 |
| ASUSTek       | AT4NM10T-I                  | [7adc9b4d41](https://linux-hardware.org/?probe=7adc9b4d41) | Jan 06, 2024 |
| MSI           | MAG B760M MORTAR WIFI       | [342164a6a4](https://linux-hardware.org/?probe=342164a6a4) | Dec 29, 2023 |
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
| SHANGZHAOY... | B85M-PRO V1.1               | [bd7c6e2693](https://linux-hardware.org/?probe=bd7c6e2693) | Dec 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [e8965075d3](https://linux-hardware.org/?probe=e8965075d3) | Dec 14, 2023 |
| Dell          | 09PR9H A03                  | [25d5c9ce02](https://linux-hardware.org/?probe=25d5c9ce02) | Dec 13, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [e9e5956d89](https://linux-hardware.org/?probe=e9e5956d89) | Dec 10, 2023 |
| Dell          | 0N820C                      | [fe88368da2](https://linux-hardware.org/?probe=fe88368da2) | Nov 09, 2023 |
| Dell          | 03TJ75 A00                  | [e082a50dde](https://linux-hardware.org/?probe=e082a50dde) | Nov 02, 2023 |
| MSI           | MEG Z790 ACE                | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| Gigabyte      | EP45-DS3L                   | [8b5e97d193](https://linux-hardware.org/?probe=8b5e97d193) | Oct 21, 2023 |
| Acer          | Aspire XC-830               | [21a3b6601a](https://linux-hardware.org/?probe=21a3b6601a) | Oct 10, 2023 |
| Acer          | Aspire XC-830               | [c7453db83a](https://linux-hardware.org/?probe=c7453db83a) | Oct 10, 2023 |
| Dell          | 088DT1 A00                  | [4e85b8e145](https://linux-hardware.org/?probe=4e85b8e145) | Oct 03, 2023 |
| Gigabyte      | EP45-DS3L                   | [2867e39109](https://linux-hardware.org/?probe=2867e39109) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8d59e8d305](https://linux-hardware.org/?probe=8d59e8d305) | Sep 20, 2023 |
| ASUSTek       | P8H61/USB3                  | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| Gigabyte      | H270M-D3H-CF                | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Gigabyte      | EP45-DS3L                   | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| ASUSTek       | AT4NM10T-I                  | [a650338ead](https://linux-hardware.org/?probe=a650338ead) | Aug 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Supermicro    | X7DWE                       | [a35080b0e5](https://linux-hardware.org/?probe=a35080b0e5) | Jul 31, 2023 |
| MSI           | 870-G45                     | [af7442187f](https://linux-hardware.org/?probe=af7442187f) | Jul 20, 2023 |
| ASUSTek       | P5QL-CM                     | [65fe34f4ce](https://linux-hardware.org/?probe=65fe34f4ce) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| MSI           | 870-G45                     | [9fff23ac6a](https://linux-hardware.org/?probe=9fff23ac6a) | Jul 14, 2023 |
| Gigabyte      | EP45-DS3L                   | [49c764507c](https://linux-hardware.org/?probe=49c764507c) | Jul 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [a7bcb95d10](https://linux-hardware.org/?probe=a7bcb95d10) | Jun 30, 2023 |
| Intel         | DG35EC AAE29266-209         | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Gateway       | H61H2-AD V1.0               | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| Supermicro    | X9DAi                       | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| Supermicro    | X10DRG-Q                    | [c03c5ea1b9](https://linux-hardware.org/?probe=c03c5ea1b9) | Jun 08, 2023 |
| Gigabyte      | H77N-WIFI                   | [8dce973d6b](https://linux-hardware.org/?probe=8dce973d6b) | Jun 02, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Gigabyte      | EP45-DS3L                   | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| Acer          | Predator G3-605             | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [8b0573684a](https://linux-hardware.org/?probe=8b0573684a) | Apr 12, 2023 |
| Dell          | 0MW50N A01                  | [dd68ce3b10](https://linux-hardware.org/?probe=dd68ce3b10) | Apr 11, 2023 |
| AZW           | U59                         | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| Gigabyte      | H77N-WIFI                   | [24b14fa9bb](https://linux-hardware.org/?probe=24b14fa9bb) | Mar 30, 2023 |
| MSI           | Z77A-GD80                   | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| Dell          | 0NDYHG A00                  | [f007ab3692](https://linux-hardware.org/?probe=f007ab3692) | Mar 20, 2023 |
| MSI           | Z77A-GD80                   | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| Dell          | 03TJ75 A00                  | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| ASUSTek       | AT4NM10T-I                  | [ca09a29082](https://linux-hardware.org/?probe=ca09a29082) | Mar 01, 2023 |
| Supermicro    | X10DAI                      | [b777ed256f](https://linux-hardware.org/?probe=b777ed256f) | Mar 01, 2023 |
| HP            | 0AECh D                     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| ASUSTek       | H97M-PLUS                   | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| Gigabyte      | H77N-WIFI                   | [f1b85863bc](https://linux-hardware.org/?probe=f1b85863bc) | Feb 20, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
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
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [164a07eda1](https://linux-hardware.org/?probe=164a07eda1) | Dec 08, 2022 |
| Dell          | 0NKW6Y A02                  | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| Gigabyte      | D525TUD                     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| MSI           | X470 GAMING PRO             | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| ABIT          | I-45CV                      | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [efecce0072](https://linux-hardware.org/?probe=efecce0072) | Nov 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [0149d91a8d](https://linux-hardware.org/?probe=0149d91a8d) | Nov 28, 2022 |
| Gigabyte      | 970A-D3                     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [74e3fe80fd](https://linux-hardware.org/?probe=74e3fe80fd) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [efd2a439bd](https://linux-hardware.org/?probe=efd2a439bd) | Nov 21, 2022 |
| Dell          | 09D2HH A00                  | [4cafe39785](https://linux-hardware.org/?probe=4cafe39785) | Nov 19, 2022 |
| MSI           | 870-G45                     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| Gigabyte      | EP45-DS3L                   | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| HP            | 8717                        | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| HP            | 3397                        | [9cb876048a](https://linux-hardware.org/?probe=9cb876048a) | Nov 05, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| MSI           | 870-G45                     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| HP            | 8717                        | [00cbc9cd2a](https://linux-hardware.org/?probe=00cbc9cd2a) | Nov 03, 2022 |
| Unknown       | Unknown                     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| Gigabyte      | H310M S2H x.x               | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| NORCO         | BPC-7951                    | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| Unknown       | Unknown                     | [f4ce3cf768](https://linux-hardware.org/?probe=f4ce3cf768) | Oct 13, 2022 |
| Intel         | D34010WYK H14771-303        | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| Dell          | 082WXT A03                  | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| MSI           | 870-G45                     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| MSI           | 870-G45                     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| Unknown       | Unknown                     | [e61dc9628f](https://linux-hardware.org/?probe=e61dc9628f) | Sep 17, 2022 |
| Dell          | 03TJ75 A00                  | [70ef579566](https://linux-hardware.org/?probe=70ef579566) | Sep 15, 2022 |
| ASUSTek       | Z87-A                       | [d57a581b09](https://linux-hardware.org/?probe=d57a581b09) | Sep 04, 2022 |
| Dell          | 0F5C5X A00                  | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| ASUSTek       | H81M-K                      | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASRock        | X299 Professional Gaming... | [759afd2f9a](https://linux-hardware.org/?probe=759afd2f9a) | Aug 04, 2022 |
| ASUSTek       | H81M-K                      | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| Dell          | 0KJCC5 A00                  | [4eec45d964](https://linux-hardware.org/?probe=4eec45d964) | Jul 21, 2022 |
| HP            | 0B4Ch D                     | [15e71f4f03](https://linux-hardware.org/?probe=15e71f4f03) | Jul 21, 2022 |
| NCR           | Pocono BIOS.6.0             | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | EP45-DS3L                   | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6069a015bb](https://linux-hardware.org/?probe=6069a015bb) | Jul 03, 2022 |
| Dell          | 0HD5W2 A01                  | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Intel         | D410PT AAE76528-404         | [b7c62fc4a8](https://linux-hardware.org/?probe=b7c62fc4a8) | Jun 29, 2022 |
| Gigabyte      | 970A-DS3P                   | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| Dell          | 0WN7Y6 A02                  | [3e2f6e6e1c](https://linux-hardware.org/?probe=3e2f6e6e1c) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Unknown       | G41 Series                  | [d257436f52](https://linux-hardware.org/?probe=d257436f52) | Jun 17, 2022 |
| Gigabyte      | H77N-WIFI                   | [a989dee1a0](https://linux-hardware.org/?probe=a989dee1a0) | Jun 06, 2022 |
| HP            | 3397                        | [f2e8417afc](https://linux-hardware.org/?probe=f2e8417afc) | Jun 04, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [0353933c85](https://linux-hardware.org/?probe=0353933c85) | Jun 02, 2022 |
| ASUSTek       | AT4NM10T-I                  | [c70d152830](https://linux-hardware.org/?probe=c70d152830) | May 29, 2022 |
| HP            | 1998                        | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Unknown       | G41 Series                  | [e9a273726a](https://linux-hardware.org/?probe=e9a273726a) | May 26, 2022 |
| Unknown       | G41 Series                  | [f0890bb556](https://linux-hardware.org/?probe=f0890bb556) | May 24, 2022 |
| Gigabyte      | EP45-DS3L                   | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| Unknown       | G41 Series                  | [94dcbec5e7](https://linux-hardware.org/?probe=94dcbec5e7) | May 20, 2022 |
| HP            | ProLiant MicroServer        | [eb3f9d541e](https://linux-hardware.org/?probe=eb3f9d541e) | May 17, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Dell          | 0K068D A00                  | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Unknown       | G41 Series                  | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Gigabyte      | H410M H V3                  | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Dell          | 0Y2YM6 A01                  | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Unknown       | G41 Series                  | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| HP            | 0AECh D                     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| MiTAC         | UltraPoint                  | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| ASUSTek       | PRIME X570-PRO              | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| HP            | 0A9Ch                       | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | [6d961af923](https://linux-hardware.org/?probe=6d961af923) | Mar 03, 2022 |
| ASUSTek       | X99-DELUXE                  | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| Intel         | X99                         | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |
| ASUSTek       | F1A55-M LX PLUS             | [706b5f2fab](https://linux-hardware.org/?probe=706b5f2fab) | Jan 27, 2022 |
| Unknown       | G41 Series                  | [28502ce22e](https://linux-hardware.org/?probe=28502ce22e) | Jan 27, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6d015ef040](https://linux-hardware.org/?probe=6d015ef040) | Jan 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [a355e13859](https://linux-hardware.org/?probe=a355e13859) | Jan 11, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| Gigabyte      | G41M-ES2L                   | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| MSI           | Z270 GAMING PLUS            | [bd96b37321](https://linux-hardware.org/?probe=bd96b37321) | Jan 07, 2022 |
| HP            | 3397                        | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| ASUSTek       | PRIME X370-PRO              | [a810f7c0fb](https://linux-hardware.org/?probe=a810f7c0fb) | Dec 28, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [aad21a9d66](https://linux-hardware.org/?probe=aad21a9d66) | Dec 21, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| ASUSTek       | Pro Q570M-C                 | [d868c52b5a](https://linux-hardware.org/?probe=d868c52b5a) | Dec 15, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [fe889c0a84](https://linux-hardware.org/?probe=fe889c0a84) | Dec 15, 2021 |
| Unknown       | G41 Series                  | [45a2524e2b](https://linux-hardware.org/?probe=45a2524e2b) | Dec 11, 2021 |
| Unknown       | G41 Series                  | [77c738bc15](https://linux-hardware.org/?probe=77c738bc15) | Dec 09, 2021 |
| Unknown       | G41 Series                  | [e9846d4aa5](https://linux-hardware.org/?probe=e9846d4aa5) | Dec 05, 2021 |
| Gigabyte      | H97N-WIFI                   | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| ASRock        | X570 Steel Legend           | [e5e357405c](https://linux-hardware.org/?probe=e5e357405c) | Nov 29, 2021 |
| Dell          | 0KC9NP A01                  | [cdc7bbd885](https://linux-hardware.org/?probe=cdc7bbd885) | Nov 29, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| HP            | 8717                        | [a00d17d8c4](https://linux-hardware.org/?probe=a00d17d8c4) | Nov 25, 2021 |
| Dell          | 02K9CR A01                  | [36c6a137fb](https://linux-hardware.org/?probe=36c6a137fb) | Nov 23, 2021 |
| Gigabyte      | B360HD3                     | [71a92047fb](https://linux-hardware.org/?probe=71a92047fb) | Nov 23, 2021 |
| Dell          | 0C2KJT A00                  | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| Gigabyte      | F2A55M-DS2                  | [c40447abe8](https://linux-hardware.org/?probe=c40447abe8) | Nov 20, 2021 |
| Dell          | 02K9CR A01                  | [7d558b813e](https://linux-hardware.org/?probe=7d558b813e) | Nov 17, 2021 |
| MSI           | A88X-G43                    | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| Dell          | 04YP6J A02                  | [6c41e1551e](https://linux-hardware.org/?probe=6c41e1551e) | Nov 09, 2021 |
| Dell          | 04YP6J A02                  | [736e182a15](https://linux-hardware.org/?probe=736e182a15) | Nov 09, 2021 |
| Dell          | 0R038D A00                  | [6b0833e390](https://linux-hardware.org/?probe=6b0833e390) | Nov 05, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [97ece593e1](https://linux-hardware.org/?probe=97ece593e1) | Nov 01, 2021 |
| ASRock        | Z77 Extreme4                | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| Gigabyte      | 970-GAMING                  | [9a9b258736](https://linux-hardware.org/?probe=9a9b258736) | Oct 22, 2021 |
| ASRock        | Z77 Extreme4                | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | KGPE-D16                    | [b5d2358b76](https://linux-hardware.org/?probe=b5d2358b76) | Oct 21, 2021 |
| Dell          | 0GTK4K A02                  | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| ASRock        | Z77 Extreme4                | [53b29edc51](https://linux-hardware.org/?probe=53b29edc51) | Oct 14, 2021 |
| ASRock        | Z77 Extreme4                | [0d69ee2560](https://linux-hardware.org/?probe=0d69ee2560) | Oct 10, 2021 |
| Huanan        | X79                         | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| Gigabyte      | 970-GAMING                  | [9a4c250f63](https://linux-hardware.org/?probe=9a4c250f63) | Oct 06, 2021 |
| MSI           | FM2-A55M-E33                | [2ff5df695f](https://linux-hardware.org/?probe=2ff5df695f) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | [f6ff6eebb3](https://linux-hardware.org/?probe=f6ff6eebb3) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [21d49c2826](https://linux-hardware.org/?probe=21d49c2826) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [cb940b924d](https://linux-hardware.org/?probe=cb940b924d) | Sep 30, 2021 |
| HP            | 0AACh                       | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| Unknown       | Unknown                     | [7baf2629b9](https://linux-hardware.org/?probe=7baf2629b9) | Sep 26, 2021 |
| ASRock        | Z77 Extreme4                | [b603b360a4](https://linux-hardware.org/?probe=b603b360a4) | Sep 25, 2021 |
| Dell          | 0FM586                      | [5ec44ec202](https://linux-hardware.org/?probe=5ec44ec202) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [976ca14e35](https://linux-hardware.org/?probe=976ca14e35) | Sep 19, 2021 |
| ASRock        | Z77 Extreme4                | [36129a77bf](https://linux-hardware.org/?probe=36129a77bf) | Sep 18, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [4720c56d37](https://linux-hardware.org/?probe=4720c56d37) | Sep 15, 2021 |
| Dell          | 0Y7WYT A00                  | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| HP            | 8750                        | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| ASRock        | Z77 Extreme4                | [5cda73f744](https://linux-hardware.org/?probe=5cda73f744) | Sep 05, 2021 |
| Intel         | DH55TC AAE70932-302         | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [5d701efa3e](https://linux-hardware.org/?probe=5d701efa3e) | Sep 03, 2021 |
| ASRock        | Z77 Extreme4                | [f754b0f478](https://linux-hardware.org/?probe=f754b0f478) | Sep 03, 2021 |
| ASUSTek       | P5L8L-SE                    | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| MSI           | MAG B550M MORTAR            | [5ae94fc78a](https://linux-hardware.org/?probe=5ae94fc78a) | Aug 28, 2021 |
| Supermicro    | X8SAX                       | [3795e4ab95](https://linux-hardware.org/?probe=3795e4ab95) | Aug 28, 2021 |
| Gigabyte      | B85M-D3PH                   | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| Gigabyte      | H97N-WIFI                   | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| HP            | 8751                        | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Gigabyte      | Z170MX-Gaming 5             | [461d550db6](https://linux-hardware.org/?probe=461d550db6) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3501d4479e](https://linux-hardware.org/?probe=3501d4479e) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [0cecab8e81](https://linux-hardware.org/?probe=0cecab8e81) | Aug 11, 2021 |
| ASRock        | A320M-HD                    | [d1e968eadd](https://linux-hardware.org/?probe=d1e968eadd) | Aug 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
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
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| ASUSTek       | SABERTOOTH X79              | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
| HP            | 2B34                        | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Dell          | 09KPNV A01                  | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [f4606d038d](https://linux-hardware.org/?probe=f4606d038d) | Jun 29, 2021 |
| ASRock        | A320M-HD                    | [e09e4e329c](https://linux-hardware.org/?probe=e09e4e329c) | Jun 14, 2021 |
| HP            | 1494                        | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Dell          | 0M5DCD A00                  | [00ce09b473](https://linux-hardware.org/?probe=00ce09b473) | May 31, 2021 |
| Intel         | E98683-353                  | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| HP            | 1589                        | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| Dell          | 0200DY A02                  | [340184fb36](https://linux-hardware.org/?probe=340184fb36) | May 23, 2021 |
| ASRock        | J3710M                      | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | 18E7                        | [3045530e64](https://linux-hardware.org/?probe=3045530e64) | May 17, 2021 |
| HP            | 8594                        | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 1825                        | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| MSI           | MAG B550M MORTAR            | [640c5adfc3](https://linux-hardware.org/?probe=640c5adfc3) | May 10, 2021 |
| ASUSTek       | PRIME X570-PRO              | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| HP            | 8591                        | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| HP            | 213D A01                    | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| ASUSTek       | Z97-E/USB                   | [8524f8f381](https://linux-hardware.org/?probe=8524f8f381) | Apr 16, 2021 |
| Gigabyte      | EP43-DS3                    | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| Dell          | 0MWYPT A02                  | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| ASRock        | X570 Steel Legend           | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
| Gigabyte      | Z490 GAMING X               | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| Dell          | 0XHGV1 A00                  | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Lenovo        | MAHOBAY                     | [3bce30311a](https://linux-hardware.org/?probe=3bce30311a) | Mar 23, 2021 |
| Gigabyte      | EP45-DS3L                   | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [c46179b0b2](https://linux-hardware.org/?probe=c46179b0b2) | Mar 22, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [0473f156a3](https://linux-hardware.org/?probe=0473f156a3) | Mar 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Dell          | 0NC2VH A01                  | [cc8791aaa6](https://linux-hardware.org/?probe=cc8791aaa6) | Mar 17, 2021 |
| ASUSTek       | PRIME A320M-R               | [adac87af3d](https://linux-hardware.org/?probe=adac87af3d) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| Gigabyte      | B75M-D3H                    | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Dell          | 0WR7PY A01                  | [ad06439414](https://linux-hardware.org/?probe=ad06439414) | Feb 19, 2021 |
| Gigabyte      | D525TUD                     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| Supermicro    | X9SCI/X9SCA                 | [28940aaa42](https://linux-hardware.org/?probe=28940aaa42) | Feb 16, 2021 |
| Dell          | 07T4MC A06                  | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| ASUSTek       | Z97-E/USB                   | [0cf9401181](https://linux-hardware.org/?probe=0cf9401181) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-D               | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| Gigabyte      | MZBSWMP-00                  | [754ea78372](https://linux-hardware.org/?probe=754ea78372) | Feb 09, 2021 |
| Gigabyte      | MZBSWMP-00                  | [5e6e46d3b1](https://linux-hardware.org/?probe=5e6e46d3b1) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| ASRock        | X570 Steel Legend           | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| ASUSTek       | GD30CI                      | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| Dell          | 0HHV7N A00                  | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
| Gigabyte      | D525TUD                     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| HP            | ProLiant MicroServer        | [edbd95264a](https://linux-hardware.org/?probe=edbd95264a) | Jan 02, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ac785c27e5](https://linux-hardware.org/?probe=ac785c27e5) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| Intel         | DQ67OW AAG12528-309         | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASRock        | X570 Steel Legend           | [c96512d726](https://linux-hardware.org/?probe=c96512d726) | Dec 25, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [2b7bb243da](https://linux-hardware.org/?probe=2b7bb243da) | Dec 23, 2020 |
| ASUSTek       | X99-DELUXE                  | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Gigabyte      | Z370 AORUS Gaming WIFI-C... | [5438d83866](https://linux-hardware.org/?probe=5438d83866) | Dec 14, 2020 |
| Gigabyte      | Z77-D3H                     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| Gigabyte      | D525TUD                     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| ASUSTek       | Z170-A                      | [b4e9865791](https://linux-hardware.org/?probe=b4e9865791) | Nov 25, 2020 |
| ASUSTek       | H87M-PLUS                   | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| ASRock        | Z390M-ITX/ac                | [3d5c6b679d](https://linux-hardware.org/?probe=3d5c6b679d) | Nov 22, 2020 |
| ASRock        | Z390M-ITX/ac                | [b3f3cd1511](https://linux-hardware.org/?probe=b3f3cd1511) | Nov 22, 2020 |
| HP            | 81C9                        | [ea900ff5b1](https://linux-hardware.org/?probe=ea900ff5b1) | Nov 19, 2020 |
| Rockwell A... | 6177R A1                    | [a12a2989fd](https://linux-hardware.org/?probe=a12a2989fd) | Nov 16, 2020 |
| ASUSTek       | PRIME X370-PRO              | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 1495                        | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Supermicro    | X8SIL                       | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| Supermicro    | X8SIL                       | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| ASUSTek       | PRIME X570-P                | [4e9d94747a](https://linux-hardware.org/?probe=4e9d94747a) | Oct 30, 2020 |
| Supermicro    | X8SIL                       | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| MSI           | A320M PRO-VD/S V2           | [56d1218104](https://linux-hardware.org/?probe=56d1218104) | Oct 25, 2020 |
| ASUSTek       | Z170-A                      | [e5b6274c3e](https://linux-hardware.org/?probe=e5b6274c3e) | Oct 22, 2020 |
| ASUSTek       | P9X79                       | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| HP            | 1495                        | [a678a5caf0](https://linux-hardware.org/?probe=a678a5caf0) | Oct 13, 2020 |
| Dell          | 01NP3N A00                  | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| ASUSTek       | F2A55-M LE                  | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| MSI           | B450I GAMING PLUS AC        | [ff2176937d](https://linux-hardware.org/?probe=ff2176937d) | Oct 03, 2020 |
| ASUSTek       | Berkeley                    | [8ead41d349](https://linux-hardware.org/?probe=8ead41d349) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [29fdcb6b00](https://linux-hardware.org/?probe=29fdcb6b00) | Sep 28, 2020 |
| ECS           | H61H2-MV                    | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Gigabyte      | A320M-S2H-CF                | [bcf59e135b](https://linux-hardware.org/?probe=bcf59e135b) | Sep 19, 2020 |
| Gigabyte      | A320M-S2H-CF                | [43d38ed1be](https://linux-hardware.org/?probe=43d38ed1be) | Sep 19, 2020 |
| HP            | 0AECh D                     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| Intel         | DH61WW AAG23116-204         | [5788667247](https://linux-hardware.org/?probe=5788667247) | Sep 12, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| HP            | 8053                        | [b00f600647](https://linux-hardware.org/?probe=b00f600647) | Sep 09, 2020 |
| Intel         | D54250WYK H13922-303        | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| Zenith        | Orion                       | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| HP            | 0B54h D                     | [b39f47faf8](https://linux-hardware.org/?probe=b39f47faf8) | Aug 26, 2020 |
| ASUSTek       | P7P55D                      | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [1c28fb67ab](https://linux-hardware.org/?probe=1c28fb67ab) | Aug 20, 2020 |
| ASUSTek       | Z97-E/USB                   | [2377cf4d5e](https://linux-hardware.org/?probe=2377cf4d5e) | Aug 19, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [eeaeff9e52](https://linux-hardware.org/?probe=eeaeff9e52) | Aug 12, 2020 |
| Lenovo        | ThinkServer TS140           | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| MSI           | B350M PRO-VDH               | [301fe36ff7](https://linux-hardware.org/?probe=301fe36ff7) | Aug 06, 2020 |
| Gigabyte      | A320M-S2H-CF                | [cbcae43afd](https://linux-hardware.org/?probe=cbcae43afd) | Aug 02, 2020 |
| Dell          | 08HPGT A02                  | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Gigabyte      | A320M-S2H-CF                | [08325f77c1](https://linux-hardware.org/?probe=08325f77c1) | Aug 01, 2020 |
| Gigabyte      | H97-HD3                     | [06c68b698e](https://linux-hardware.org/?probe=06c68b698e) | Jul 24, 2020 |
| Gigabyte      | B360M DS3H                  | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| HP            | 0AECh D                     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| ASUSTek       | Z97-E/USB                   | [f6f4d985ea](https://linux-hardware.org/?probe=f6f4d985ea) | Jul 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2244646450](https://linux-hardware.org/?probe=2244646450) | Jul 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [80c07a542a](https://linux-hardware.org/?probe=80c07a542a) | Jul 11, 2020 |
| HP            | 1589                        | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| Dell          | 0YXT71 A02                  | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| ASRockRack    | EP2C612 WS                  | [4392ed1437](https://linux-hardware.org/?probe=4392ed1437) | Jul 08, 2020 |
| Dell          | 073MMW A00                  | [115d71c055](https://linux-hardware.org/?probe=115d71c055) | Jul 06, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Gigabyte      | EP45-DS3R                   | [cfad3da667](https://linux-hardware.org/?probe=cfad3da667) | Jul 03, 2020 |
| ASUSTek       | SABERTOOTH X99              | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Unknown       | IPM31-AK                    | [acd334c9b0](https://linux-hardware.org/?probe=acd334c9b0) | Jun 28, 2020 |
| Gigabyte      | P85-D3                      | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| ASUSTek       | P8Z77-V                     | [f94256b581](https://linux-hardware.org/?probe=f94256b581) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [f9990a3c91](https://linux-hardware.org/?probe=f9990a3c91) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [6d4908178c](https://linux-hardware.org/?probe=6d4908178c) | Jun 22, 2020 |
| ASUSTek       | Crosshair IV Formula        | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | [56fa210d0c](https://linux-hardware.org/?probe=56fa210d0c) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | [b2d975c2e7](https://linux-hardware.org/?probe=b2d975c2e7) | Jun 20, 2020 |
| MSI           | 2A9C                        | [9af3bb0a4e](https://linux-hardware.org/?probe=9af3bb0a4e) | Jun 17, 2020 |
| Packard Be... | MCP73VT-PM                  | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| Supermicro    | X10DRG-H                    | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| ASRock        | X399 Professional Gaming    | [d313005743](https://linux-hardware.org/?probe=d313005743) | Jun 10, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| Intel         | DP45SG AAE27733-405         | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| Dell          | 0VRWRC A00                  | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
| Dell          | 0YXT71 A02                  | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| ASRock        | AM1B-ITX                    | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| Supermicro    | X10DAI                      | [c2d45e8975](https://linux-hardware.org/?probe=c2d45e8975) | May 21, 2020 |
| Gigabyte      | Z68P-DS3                    | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| ASUSTek       | CM1740                      | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Lenovo        | MAHOBAY                     | [3ad583ff3d](https://linux-hardware.org/?probe=3ad583ff3d) | May 14, 2020 |
| Gigabyte      | EP45-DS3L                   | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| HP            | 1495                        | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Foxconn       | 17A0                        | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Supermicro    | X10SDE-DF                   | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| Biostar       | A320MH                      | [bc6b5804c2](https://linux-hardware.org/?probe=bc6b5804c2) | Apr 24, 2020 |
| Foxconn       | 2A8C                        | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| ASRockRack    | EP2C612 WS                  | [22419b4efe](https://linux-hardware.org/?probe=22419b4efe) | Apr 20, 2020 |
| Dell          | 0C3YXR A01                  | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [cfed23f08f](https://linux-hardware.org/?probe=cfed23f08f) | Apr 18, 2020 |
| ASUSTek       | Rampage V EXTREME           | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| Dell          | 0YXT71 A02                  | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c670b78e38](https://linux-hardware.org/?probe=c670b78e38) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [5d17d05d00](https://linux-hardware.org/?probe=5d17d05d00) | Apr 11, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASRock        | X399 Professional Gaming    | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| HP            | 843F                        | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Dell          | 040DDP A01                  | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EP45-DS3L                   | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| Gigabyte      | EX58-EXTREME                | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| Dell          | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Gigabyte      | Z170X-UD3-CF                | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [54d3d863ad](https://linux-hardware.org/?probe=54d3d863ad) | Feb 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [72895d5cc3](https://linux-hardware.org/?probe=72895d5cc3) | Feb 23, 2020 |
| Gigabyte      | EX58-EXTREME                | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Supermicro    | X10DAI                      | [8bb87102a9](https://linux-hardware.org/?probe=8bb87102a9) | Feb 20, 2020 |
| Foxconn       | 2ABF                        | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| ASUSTek       | H87M-PLUS                   | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| ASUSTek       | AT4NM10T-I                  | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| Gigabyte      | Z77X-UD5H                   | [2c5e967e3a](https://linux-hardware.org/?probe=2c5e967e3a) | Jan 25, 2020 |
| HP            | 18E4                        | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| Gigabyte      | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Foxconn       | 2AA9                        | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [3c407e606c](https://linux-hardware.org/?probe=3c407e606c) | Dec 31, 2019 |
| Gigabyte      | EP45-DS4                    | [13acec4985](https://linux-hardware.org/?probe=13acec4985) | Dec 25, 2019 |
| ASUSTek       | PRIME Z390-P                | [0b771c098e](https://linux-hardware.org/?probe=0b771c098e) | Dec 20, 2019 |
| HP            | 0A98h                       | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| MSI           | H55M-E33                    | [48d4121155](https://linux-hardware.org/?probe=48d4121155) | Dec 10, 2019 |
| ASRock        | X79 Extreme11               | [1b28cc994f](https://linux-hardware.org/?probe=1b28cc994f) | Dec 07, 2019 |
| Dell          | 0PC5F7 A01                  | [ba442e31fa](https://linux-hardware.org/?probe=ba442e31fa) | Nov 24, 2019 |
| ASUSTek       | Benicia                     | [5d4f2621ec](https://linux-hardware.org/?probe=5d4f2621ec) | Nov 22, 2019 |
| Dell          | 09KPNV A01                  | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| HP            | ProLiant MicroServer        | [fdfa4ab709](https://linux-hardware.org/?probe=fdfa4ab709) | Nov 14, 2019 |
| Dell          | 07T4MC A06                  | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Lenovo        | MAHOBAY                     | [652157e27c](https://linux-hardware.org/?probe=652157e27c) | Nov 03, 2019 |
| Lenovo        | MAHOBAY                     | [fd672567d1](https://linux-hardware.org/?probe=fd672567d1) | Nov 03, 2019 |
| Gigabyte      | B150M-D3H-CF                | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| ASUSTek       | Benicia                     | [764ecc00c4](https://linux-hardware.org/?probe=764ecc00c4) | Oct 30, 2019 |
| ASUSTek       | Benicia                     | [c604466168](https://linux-hardware.org/?probe=c604466168) | Oct 26, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [17d03076df](https://linux-hardware.org/?probe=17d03076df) | Oct 16, 2019 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [11a89e3f6f](https://linux-hardware.org/?probe=11a89e3f6f) | Oct 13, 2019 |
| ECS           | H55H-M                      | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Supermicro    | X7DVL                       | [e4951bb84b](https://linux-hardware.org/?probe=e4951bb84b) | Oct 05, 2019 |
| Gigabyte      | X58A-UD5                    | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |
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
| TYAN Compu... | S5512                       | [67bfe1b221](https://linux-hardware.org/?probe=67bfe1b221) | Jun 30, 2018 |
| ASRock        | H77 Pro4/MVP                | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/CentOS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| CentOS 7      | 239      | 55.58%  |
| CentOS 8      | 159      | 36.98%  |
| CentOS 9      | 21       | 4.88%   |
| CentOS 6      | 8        | 1.86%   |
| CentOS Stream | 3        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| CentOS | 426      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 3.10.0-1160.102.1.el7.x86_64 | 45       | 9.18%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 13       | 2.65%   |
| 3.10.0-1160.45.1.el7.x86_64  | 13       | 2.65%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 12       | 2.45%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 12       | 2.45%   |
| 3.10.0-1160.90.1.el7.x86_64  | 12       | 2.45%   |
| 3.10.0-1160.31.1.el7.x86_64  | 12       | 2.45%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9        | 1.84%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 9        | 1.84%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 9        | 1.84%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 9        | 1.84%   |
| 3.10.0-1160.25.1.el7.x86_64  | 9        | 1.84%   |
| 3.10.0-1160.95.1.el7.x86_64  | 8        | 1.63%   |
| 3.10.0-1062.el7.x86_64       | 8        | 1.63%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7        | 1.43%   |
| 3.10.0-1160.83.1.el7.x86_64  | 7        | 1.43%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 6        | 1.22%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 6        | 1.22%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 6        | 1.22%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 6        | 1.22%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6        | 1.22%   |
| 3.10.0-957.10.1.el7.x86_64   | 6        | 1.22%   |
| 3.10.0-1160.76.1.el7.x86_64  | 6        | 1.22%   |
| 3.10.0-1160.66.1.el7.x86_64  | 6        | 1.22%   |
| 3.10.0-1160.15.2.el7.x86_64  | 6        | 1.22%   |
| 3.10.0-1062.12.1.el7.x86_64  | 6        | 1.22%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 5        | 1.02%   |
| 3.10.0-1160.6.1.el7.x86_64   | 5        | 1.02%   |
| 3.10.0-1160.36.2.el7.x86_64  | 5        | 1.02%   |
| 3.10.0-1062.9.1.el7.x86_64   | 5        | 1.02%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4        | 0.82%   |
| 4.18.0-301.1.el8.x86_64      | 4        | 0.82%   |
| 4.18.0-147.el8.x86_64        | 4        | 0.82%   |
| 3.10.0-957.27.2.el7.x86_64   | 4        | 0.82%   |
| 3.10.0-1160.el7.x86_64       | 4        | 0.82%   |
| 3.10.0-1160.88.1.el7.x86_64  | 4        | 0.82%   |
| 3.10.0-1160.59.1.el7.x86_64  | 4        | 0.82%   |
| 3.10.0-1127.el7.x86_64       | 4        | 0.82%   |
| 5.14.0-391.el9.x86_64        | 3        | 0.61%   |
| 4.18.0-358.el8.x86_64        | 3        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 3.10.0   | 219      | 50.93%  |
| 4.18.0   | 157      | 36.51%  |
| 5.14.0   | 19       | 4.42%   |
| 2.6.32   | 7        | 1.63%   |
| 6.2.2    | 1        | 0.23%   |
| 6.1.1    | 1        | 0.23%   |
| 5.8.0    | 1        | 0.23%   |
| 5.7.7    | 1        | 0.23%   |
| 5.7.10   | 1        | 0.23%   |
| 5.6.10   | 1        | 0.23%   |
| 5.5.0    | 1        | 0.23%   |
| 5.4.96   | 1        | 0.23%   |
| 5.4.234  | 1        | 0.23%   |
| 5.4.142  | 1        | 0.23%   |
| 5.4.119  | 1        | 0.23%   |
| 5.4.118  | 1        | 0.23%   |
| 5.4.113  | 1        | 0.23%   |
| 5.3.11   | 1        | 0.23%   |
| 5.18.0   | 1        | 0.23%   |
| 5.17.2   | 1        | 0.23%   |
| 5.13.11  | 1        | 0.23%   |
| 5.10.3   | 1        | 0.23%   |
| 5.10.10  | 1        | 0.23%   |
| 5.1.19   | 1        | 0.23%   |
| 4.9.188  | 1        | 0.23%   |
| 4.9.182  | 1        | 0.23%   |
| 4.9.180  | 1        | 0.23%   |
| 4.9.179  | 1        | 0.23%   |
| 4.20.4   | 1        | 0.23%   |
| 4.19.187 | 1        | 0.23%   |
| 4.17.11  | 1        | 0.23%   |
| 4.14.35  | 1        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 3.10    | 219      | 50.93%  |
| 4.18    | 157      | 36.51%  |
| 5.14    | 19       | 4.42%   |
| 2.6     | 7        | 1.63%   |
| 5.4     | 6        | 1.4%    |
| 4.9     | 4        | 0.93%   |
| 5.7     | 2        | 0.47%   |
| 5.10    | 2        | 0.47%   |
| 6.2     | 1        | 0.23%   |
| 6.1     | 1        | 0.23%   |
| 5.8     | 1        | 0.23%   |
| 5.6     | 1        | 0.23%   |
| 5.5     | 1        | 0.23%   |
| 5.3     | 1        | 0.23%   |
| 5.18    | 1        | 0.23%   |
| 5.17    | 1        | 0.23%   |
| 5.13    | 1        | 0.23%   |
| 5.1     | 1        | 0.23%   |
| 4.20    | 1        | 0.23%   |
| 4.19    | 1        | 0.23%   |
| 4.17    | 1        | 0.23%   |
| 4.14    | 1        | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 424      | 99.53%  |
| i686   | 2        | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 257      | 59.63%  |
| Unknown       | 96       | 22.27%  |
| GNOME Classic | 29       | 6.73%   |
| KDE4          | 19       | 4.41%   |
| MATE          | 10       | 2.32%   |
| XFCE          | 8        | 1.86%   |
| KDE5          | 6        | 1.39%   |
| Cinnamon      | 3        | 0.7%    |
| X-Cinnamon    | 2        | 0.46%   |
| Xpra          | 1        | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 294      | 67.43%  |
| Wayland | 90       | 20.64%  |
| Unknown | 49       | 11.24%  |
| Web     | 3        | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 212      | 49.3%   |
| Unknown | 200      | 46.51%  |
| LightDM | 13       | 3.02%   |
| SDDM    | 3        | 0.7%    |
| TDM     | 1        | 0.23%   |
| KDM     | 1        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 178      | 41.2%   |
| Unknown     | 117      | 27.08%  |
| en_GB       | 17       | 3.94%   |
| C           | 16       | 3.7%    |
| de_DE       | 14       | 3.24%   |
| ru_RU       | 10       | 2.31%   |
| en_AU       | 9        | 2.08%   |
| pt_BR       | 8        | 1.85%   |
| en_CA       | 8        | 1.85%   |
| pl_PL       | 7        | 1.62%   |
| fr_FR       | 7        | 1.62%   |
| en_IN       | 7        | 1.62%   |
| zh_CN       | 3        | 0.69%   |
| de_AT       | 3        | 0.69%   |
| ko_KR       | 2        | 0.46%   |
| ja_JP       | 2        | 0.46%   |
| it_IT       | 2        | 0.46%   |
| fr_CA       | 2        | 0.46%   |
| fi_FI       | 2        | 0.46%   |
| es_PE       | 2        | 0.46%   |
| es_EC       | 2        | 0.46%   |
| en_US.utf-8 | 2        | 0.46%   |
| uk_UA       | 1        | 0.23%   |
| tr_TR       | 1        | 0.23%   |
| sl_SI       | 1        | 0.23%   |
| ru_UA       | 1        | 0.23%   |
| ru_RU.UTF8  | 1        | 0.23%   |
| hu_HU       | 1        | 0.23%   |
| es_US       | 1        | 0.23%   |
| es_MX       | 1        | 0.23%   |
| en_SG       | 1        | 0.23%   |
| de_LU       | 1        | 0.23%   |
| de_CH       | 1        | 0.23%   |
| cs_CZ       | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 229      | 53.5%   |
| BIOS | 199      | 46.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 273      | 63.64%  |
| Ext4    | 111      | 25.87%  |
| Ext3    | 32       | 7.46%   |
| Unknown | 13       | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 212      | 48.96%  |
| Unknown | 130      | 30.02%  |
| MBR     | 91       | 21.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 365      | 84.88%  |
| Yes       | 65       | 15.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 384      | 89.51%  |
| Yes       | 45       | 10.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 86       | 20.19%  |
| ASUSTek Computer    | 82       | 19.25%  |
| Dell                | 64       | 15.02%  |
| MSI                 | 61       | 14.32%  |
| Hewlett-Packard     | 43       | 10.09%  |
| Supermicro          | 14       | 3.29%   |
| ASRock              | 13       | 3.05%   |
| Intel               | 12       | 2.82%   |
| Unknown             | 8        | 1.88%   |
| Lenovo              | 5        | 1.17%   |
| Fujitsu             | 4        | 0.94%   |
| Foxconn             | 4        | 0.94%   |
| ASRockRack          | 4        | 0.94%   |
| MiTAC               | 2        | 0.47%   |
| ECS                 | 2        | 0.47%   |
| AZW                 | 2        | 0.47%   |
| AMI                 | 2        | 0.47%   |
| Acer                | 2        | 0.47%   |
| Zenith              | 1        | 0.23%   |
| TYAN Computer       | 1        | 0.23%   |
| SHANGZHAOYUAN       | 1        | 0.23%   |
| PCChips             | 1        | 0.23%   |
| Packard Bell        | 1        | 0.23%   |
| NORCO               | 1        | 0.23%   |
| Huanan              | 1        | 0.23%   |
| Gateway             | 1        | 0.23%   |
| eMachines           | 1        | 0.23%   |
| Colorful Technology | 1        | 0.23%   |
| Cisco Systems       | 1        | 0.23%   |
| Biostar             | 1        | 0.23%   |
| Apple               | 1        | 0.23%   |
| AEWIN               | 1        | 0.23%   |
| ABIT                | 1        | 0.23%   |
| AAEON               | 1        | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C31                      | 15       | 3.52%   |
| Gigabyte H81M-S2H                | 15       | 3.52%   |
| MSI MS-7A15                      | 9        | 2.11%   |
| Dell OptiPlex 9020               | 9        | 2.11%   |
| Dell OptiPlex 7040               | 9        | 2.11%   |
| ASUS All Series                  | 8        | 1.88%   |
| Unknown                          | 8        | 1.88%   |
| MSI MS-7B53                      | 6        | 1.41%   |
| MSI MS-7A74                      | 6        | 1.41%   |
| HP Z800 Workstation              | 4        | 0.94%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.94%   |
| Gigabyte H81M-DS2                | 4        | 0.94%   |
| Dell OptiPlex 7010               | 4        | 0.94%   |
| ASUS H110M-K                     | 4        | 0.94%   |
| HP ProDesk 400 G7 Microtower PC  | 3        | 0.7%    |
| HP Compaq 8200 Elite SFF PC      | 3        | 0.7%    |
| Gigabyte H81M-S2PV               | 3        | 0.7%    |
| Dell Precision WorkStation T3500 | 3        | 0.7%    |
| ASUS M5A78L-M PLUS/USB3          | 3        | 0.7%    |
| ASRockRack E3C242D4U2-2T         | 3        | 0.7%    |
| Supermicro SYS-7048A-T           | 2        | 0.47%   |
| HP Z420 Workstation              | 2        | 0.47%   |
| HP Z2 Tower G5 Workstation       | 2        | 0.47%   |
| HP ProLiant MicroServer          | 2        | 0.47%   |
| Gigabyte X470 AORUS ULTRA GAMING | 2        | 0.47%   |
| Gigabyte H97N-WIFI               | 2        | 0.47%   |
| Gigabyte GA-78LMT-USB3           | 2        | 0.47%   |
| Gigabyte B560M AORUS PRO         | 2        | 0.47%   |
| Gigabyte B360M-HD3               | 2        | 0.47%   |
| Gigabyte A320M-S2H               | 2        | 0.47%   |
| Gigabyte 970A-DS3P               | 2        | 0.47%   |
| Fujitsu D3401-H1                 | 2        | 0.47%   |
| Dell PowerEdge T40               | 2        | 0.47%   |
| Dell OptiPlex 780                | 2        | 0.47%   |
| Dell OptiPlex 390                | 2        | 0.47%   |
| Dell OptiPlex 3020               | 2        | 0.47%   |
| ASUS TUF Gaming X570-PLUS        | 2        | 0.47%   |
| ASUS TUF B450M-PRO GAMING        | 2        | 0.47%   |
| ASUS PRIME X570-PRO              | 2        | 0.47%   |
| ASUS PRIME X570-P                | 2        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 36       | 8.45%   |
| MSI MS-7C31              | 15       | 3.52%   |
| Gigabyte H81M-S2H        | 15       | 3.52%   |
| Dell Precision           | 15       | 3.52%   |
| ASUS PRIME               | 15       | 3.52%   |
| MSI MS-7A15              | 9        | 2.11%   |
| HP Compaq                | 9        | 2.11%   |
| ASUS All                 | 8        | 1.88%   |
| Unknown                  | 8        | 1.88%   |
| ASUS TUF                 | 7        | 1.64%   |
| ASUS ROG                 | 7        | 1.64%   |
| MSI MS-7B53              | 6        | 1.41%   |
| MSI MS-7A74              | 6        | 1.41%   |
| HP EliteDesk             | 6        | 1.41%   |
| Dell Inspiron            | 6        | 1.41%   |
| ASUS M5A78L-M            | 6        | 1.41%   |
| HP ProDesk               | 5        | 1.17%   |
| HP Z800                  | 4        | 0.94%   |
| Gigabyte H81M-DS2        | 4        | 0.94%   |
| Dell PowerEdge           | 4        | 0.94%   |
| ASUS H110M-K             | 4        | 0.94%   |
| HP ProLiant              | 3        | 0.7%    |
| Gigabyte H81M-S2PV       | 3        | 0.7%    |
| Gigabyte GA-78LMT-USB3   | 3        | 0.7%    |
| ASUS P8Z77-V             | 3        | 0.7%    |
| ASRockRack E3C242D4U2-2T | 3        | 0.7%    |
| Supermicro SYS-7048A-T   | 2        | 0.47%   |
| Lenovo ThinkCentre       | 2        | 0.47%   |
| HP Z420                  | 2        | 0.47%   |
| HP Z2                    | 2        | 0.47%   |
| Gigabyte Z370            | 2        | 0.47%   |
| Gigabyte X570            | 2        | 0.47%   |
| Gigabyte X470            | 2        | 0.47%   |
| Gigabyte H97N-WIFI       | 2        | 0.47%   |
| Gigabyte B560M           | 2        | 0.47%   |
| Gigabyte B360M-HD3       | 2        | 0.47%   |
| Gigabyte B360            | 2        | 0.47%   |
| Gigabyte A320M-S2H       | 2        | 0.47%   |
| Gigabyte 970A-DS3P       | 2        | 0.47%   |
| Fujitsu D3401-H1         | 2        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 48       | 11.27%  |
| 2014    | 41       | 9.62%   |
| 2013    | 41       | 9.62%   |
| 2018    | 40       | 9.39%   |
| 2016    | 40       | 9.39%   |
| 2012    | 35       | 8.22%   |
| 2017    | 30       | 7.04%   |
| 2011    | 26       | 6.1%    |
| 2010    | 25       | 5.87%   |
| 2015    | 23       | 5.4%    |
| 2021    | 18       | 4.23%   |
| 2020    | 18       | 4.23%   |
| 2008    | 16       | 3.76%   |
| 2009    | 12       | 2.82%   |
| 2007    | 5        | 1.17%   |
| 2022    | 4        | 0.94%   |
| 2023    | 2        | 0.47%   |
| Unknown | 2        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 426      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 420      | 98.59%  |
| Enabled  | 6        | 1.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 425      | 99.77%  |
| Yes  | 1        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 150      | 35.13%  |
| 32.01-64.0      | 68       | 15.93%  |
| 16.01-24.0      | 64       | 14.99%  |
| 64.01-256.0     | 46       | 10.77%  |
| 8.01-16.0       | 40       | 9.37%   |
| 3.01-4.0        | 32       | 7.49%   |
| 1.01-2.0        | 12       | 2.81%   |
| 24.01-32.0      | 8        | 1.87%   |
| 2.01-3.0        | 3        | 0.7%    |
| More than 256.0 | 2        | 0.47%   |
| 0.51-1.0        | 2        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 110      | 23.91%  |
| 2.01-3.0    | 89       | 19.35%  |
| 4.01-8.0    | 67       | 14.57%  |
| 3.01-4.0    | 64       | 13.91%  |
| 0.51-1.0    | 61       | 13.26%  |
| 8.01-16.0   | 33       | 7.17%   |
| 0.01-0.5    | 14       | 3.04%   |
| 16.01-24.0  | 8        | 1.74%   |
| Unknown     | 7        | 1.52%   |
| 24.01-32.0  | 3        | 0.65%   |
| 32.01-64.0  | 2        | 0.43%   |
| 64.01-256.0 | 2        | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 204      | 46.9%   |
| 2       | 92       | 21.15%  |
| 3       | 56       | 12.87%  |
| 4       | 32       | 7.36%   |
| 6       | 12       | 2.76%   |
| 5       | 11       | 2.53%   |
| 7       | 5        | 1.15%   |
| 10      | 3        | 0.69%   |
| 9       | 3        | 0.69%   |
| 8       | 3        | 0.69%   |
| 0       | 3        | 0.69%   |
| 19      | 2        | 0.46%   |
| 15      | 2        | 0.46%   |
| Unknown | 2        | 0.46%   |
| 71      | 1        | 0.23%   |
| 68      | 1        | 0.23%   |
| 26      | 1        | 0.23%   |
| 13      | 1        | 0.23%   |
| 12      | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 280      | 65.27%  |
| Yes       | 149      | 34.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 424      | 99.53%  |
| No        | 2        | 0.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 330      | 76.92%  |
| Yes       | 99       | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 341      | 79.86%  |
| Yes       | 86       | 20.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 87       | 20.42%  |
| Australia    | 79       | 18.54%  |
| Russia       | 26       | 6.1%    |
| Germany      | 26       | 6.1%    |
| Canada       | 21       | 4.93%   |
| India        | 18       | 4.23%   |
| Brazil       | 18       | 4.23%   |
| UK           | 15       | 3.52%   |
| France       | 15       | 3.52%   |
| China        | 9        | 2.11%   |
| Poland       | 7        | 1.64%   |
| Switzerland  | 6        | 1.41%   |
| Finland      | 6        | 1.41%   |
| Ukraine      | 5        | 1.17%   |
| Italy        | 5        | 1.17%   |
| Czechia      | 5        | 1.17%   |
| Bulgaria     | 5        | 1.17%   |
| Sweden       | 4        | 0.94%   |
| South Korea  | 4        | 0.94%   |
| Netherlands  | 4        | 0.94%   |
| Belgium      | 4        | 0.94%   |
| Turkey       | 3        | 0.7%    |
| Romania      | 3        | 0.7%    |
| Japan        | 3        | 0.7%    |
| Hong Kong    | 3        | 0.7%    |
| Ecuador      | 3        | 0.7%    |
| Thailand     | 2        | 0.47%   |
| Taiwan       | 2        | 0.47%   |
| Spain        | 2        | 0.47%   |
| South Africa | 2        | 0.47%   |
| Portugal     | 2        | 0.47%   |
| Peru         | 2        | 0.47%   |
| Norway       | 2        | 0.47%   |
| Mexico       | 2        | 0.47%   |
| Israel       | 2        | 0.47%   |
| Indonesia    | 2        | 0.47%   |
| Hungary      | 2        | 0.47%   |
| Belarus      | 2        | 0.47%   |
| Slovenia     | 1        | 0.23%   |
| Slovakia     | 1        | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Melbourne         | 69       | 15.83%  |
| Rochester         | 16       | 3.67%   |
| Moscow            | 8        | 1.83%   |
| Sydney            | 7        | 1.61%   |
| Portland          | 5        | 1.15%   |
| Alexandria        | 5        | 1.15%   |
| Paris             | 4        | 0.92%   |
| Montreal          | 4        | 0.92%   |
| London            | 4        | 0.92%   |
| Guwahati          | 4        | 0.92%   |
| Frankfurt am Main | 4        | 0.92%   |
| Berlin            | 4        | 0.92%   |
| Victoria          | 3        | 0.69%   |
| Vancouver         | 3        | 0.69%   |
| St Petersburg     | 3        | 0.69%   |
| Sofia             | 3        | 0.69%   |
| Sao Paulo         | 3        | 0.69%   |
| Munich            | 3        | 0.69%   |
| Kyiv              | 3        | 0.69%   |
| Helsinki          | 3        | 0.69%   |
| Guayaquil         | 3        | 0.69%   |
| Central           | 3        | 0.69%   |
| Brno              | 3        | 0.69%   |
| Bengaluru         | 3        | 0.69%   |
| Waxhaw            | 2        | 0.46%   |
| Warsaw            | 2        | 0.46%   |
| Wahroonga         | 2        | 0.46%   |
| Vitebsk           | 2        | 0.46%   |
| Tyumen            | 2        | 0.46%   |
| Tampa             | 2        | 0.46%   |
| Sundbyberg        | 2        | 0.46%   |
| Shenzhen          | 2        | 0.46%   |
| Shanghai          | 2        | 0.46%   |
| Prague            | 2        | 0.46%   |
| Porto Alegre      | 2        | 0.46%   |
| Milan             | 2        | 0.46%   |
| Lima              | 2        | 0.46%   |
| Istanbul          | 2        | 0.46%   |
| Hyderabad         | 2        | 0.46%   |
| Ernakulam         | 2        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 204      | 434    | 29.65%  |
| Seagate                   | 124      | 381    | 18.02%  |
| Samsung Electronics       | 86       | 218    | 12.5%   |
| Kingston                  | 41       | 56     | 5.96%   |
| Toshiba                   | 33       | 53     | 4.8%    |
| Hitachi                   | 26       | 58     | 3.78%   |
| SanDisk                   | 23       | 37     | 3.34%   |
| Intel                     | 17       | 45     | 2.47%   |
| Crucial                   | 11       | 23     | 1.6%    |
| HGST                      | 10       | 102    | 1.45%   |
| Unknown                   | 9        | 27     | 1.31%   |
| A-DATA Technology         | 7        | 9      | 1.02%   |
| SK hynix                  | 6        | 7      | 0.87%   |
| SPCC                      | 5        | 10     | 0.73%   |
| Silicon Motion            | 5        | 5      | 0.73%   |
| Phison                    | 5        | 6      | 0.73%   |
| OCZ                       | 5        | 10     | 0.73%   |
| Micron Technology         | 5        | 8      | 0.73%   |
| Hewlett-Packard           | 5        | 7      | 0.73%   |
| Gigabyte Technology       | 4        | 5      | 0.58%   |
| Micron/Crucial Technology | 3        | 4      | 0.44%   |
| XPG                       | 2        | 2      | 0.29%   |
| Team                      | 2        | 3      | 0.29%   |
| PNY                       | 2        | 3      | 0.29%   |
| Plextor                   | 2        | 2      | 0.29%   |
| Phison Electronics        | 2        | 3      | 0.29%   |
| KIOXIA-EXCERIA            | 2        | 5      | 0.29%   |
| KingDian                  | 2        | 6      | 0.29%   |
| Fujitsu                   | 2        | 3      | 0.29%   |
| Dell                      | 2        | 4      | 0.29%   |
| China                     | 2        | 5      | 0.29%   |
| Apacer                    | 2        | 2      | 0.29%   |
| ADATA Technology          | 2        | 2      | 0.29%   |
| WD MediaMax               | 1        | 1      | 0.15%   |
| Verbatim                  | 1        | 1      | 0.15%   |
| V-GeN                     | 1        | 1      | 0.15%   |
| UNIC2                     | 1        | 1      | 0.15%   |
| Transcend                 | 1        | 1      | 0.15%   |
| Sun                       | 1        | 3      | 0.15%   |
| SSSTC                     | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB         | 38       | 4.5%    |
| WDC WD10EZEX-00MFCA0 1TB         | 18       | 2.13%   |
| Seagate ST1000DM010-2EP102 1TB   | 12       | 1.42%   |
| WDC WD10EZEX-00WN4A0 1TB         | 11       | 1.3%    |
| Toshiba DT01ACA100 1TB           | 10       | 1.18%   |
| Seagate ST500DM002-1BD142 500GB  | 10       | 1.18%   |
| Toshiba DT01ACA050 500GB         | 8        | 0.95%   |
| WDC WD20EARX-00PASB0 2TB         | 7        | 0.83%   |
| Seagate ST500DM002-1SB10A 500GB  | 7        | 0.83%   |
| Seagate ST1000DM003-1CH162 1TB   | 6        | 0.71%   |
| Kingston SA400S37240G 240GB SSD  | 6        | 0.71%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 5        | 0.59%   |
| WDC WD20EZRX-00D8PB0 2TB         | 5        | 0.59%   |
| Samsung SSD 850 EVO 250GB        | 5        | 0.59%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 4        | 0.47%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 4        | 0.47%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 4        | 0.47%   |
| WDC WD10EZEX-75WN4A0 1TB         | 4        | 0.47%   |
| WDC WD10EZEX-60WN4A0 1TB         | 4        | 0.47%   |
| WDC WD10EZEX-22MFCA0 1TB         | 4        | 0.47%   |
| Seagate ST31000528AS 1TB         | 4        | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB   | 4        | 0.47%   |
| Samsung SSD 860 EVO 250GB        | 4        | 0.47%   |
| Samsung HD103SJ 1TB              | 4        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.36%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 3        | 0.36%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 3        | 0.36%   |
| WDC WD40EFRX-68N32N0 4TB         | 3        | 0.36%   |
| WDC WD3200AAKS-75L9A0 320GB      | 3        | 0.36%   |
| WDC WD30PURX-64P6ZY0 3TB         | 3        | 0.36%   |
| WDC WD20EFRX-68EUZN0 2TB         | 3        | 0.36%   |
| WDC WD2002FAEX-007BA0 2TB        | 3        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 0.36%   |
| WDC WD10EZEX-00BBHA0 1TB         | 3        | 0.36%   |
| Unknown HUH728080ALE601 8TB      | 3        | 0.36%   |
| Toshiba DT01ACA200 2TB           | 3        | 0.36%   |
| Seagate ST6000NM0095 6TB         | 3        | 0.36%   |
| Seagate ST6000NM0034 6TB         | 3        | 0.36%   |
| Seagate ST6000NM0014 6TB         | 3        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 196      | 411    | 46.67%  |
| Seagate             | 121      | 376    | 28.81%  |
| Toshiba             | 33       | 53     | 7.86%   |
| Hitachi             | 26       | 58     | 6.19%   |
| Samsung Electronics | 17       | 114    | 4.05%   |
| HGST                | 10       | 55     | 2.38%   |
| Unknown             | 5        | 23     | 1.19%   |
| Hewlett-Packard     | 3        | 5      | 0.71%   |
| Fujitsu             | 2        | 3      | 0.48%   |
| Dell                | 2        | 4      | 0.48%   |
| WD MediaMax         | 1        | 1      | 0.24%   |
| Sun                 | 1        | 3      | 0.24%   |
| Maxtor              | 1        | 1      | 0.24%   |
| Lenovo              | 1        | 2      | 0.24%   |
| Apple               | 1        | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 51       | 73     | 25.5%   |
| Kingston            | 39       | 54     | 19.5%   |
| WDC                 | 16       | 23     | 8%      |
| Intel               | 15       | 40     | 7.5%    |
| SanDisk             | 11       | 16     | 5.5%    |
| Crucial             | 10       | 22     | 5%      |
| SK hynix            | 6        | 7      | 3%      |
| SPCC                | 5        | 10     | 2.5%    |
| OCZ                 | 5        | 10     | 2.5%    |
| A-DATA Technology   | 5        | 6      | 2.5%    |
| Micron Technology   | 3        | 5      | 1.5%    |
| Team                | 2        | 3      | 1%      |
| Seagate             | 2        | 2      | 1%      |
| PNY                 | 2        | 3      | 1%      |
| Plextor             | 2        | 2      | 1%      |
| KingDian            | 2        | 6      | 1%      |
| Hewlett-Packard     | 2        | 2      | 1%      |
| China               | 2        | 5      | 1%      |
| Apacer              | 2        | 2      | 1%      |
| Verbatim            | 1        | 1      | 0.5%    |
| V-GeN               | 1        | 1      | 0.5%    |
| UNIC2               | 1        | 1      | 0.5%    |
| Transcend           | 1        | 1      | 0.5%    |
| SATADOM-SL          | 1        | 1      | 0.5%    |
| Patriot             | 1        | 3      | 0.5%    |
| OWC                 | 1        | 1      | 0.5%    |
| NORCO               | 1        | 1      | 0.5%    |
| LITEONIT            | 1        | 1      | 0.5%    |
| Lexar               | 1        | 1      | 0.5%    |
| Leven               | 1        | 1      | 0.5%    |
| KIOXIA-EXCERIA      | 1        | 2      | 0.5%    |
| GOODRAM             | 1        | 1      | 0.5%    |
| GLOWAY              | 1        | 1      | 0.5%    |
| Gigabyte Technology | 1        | 2      | 0.5%    |
| Corsair             | 1        | 1      | 0.5%    |
| ASMT                | 1        | 1      | 0.5%    |
| Acer                | 1        | 3      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 326      | 1110   | 56.6%   |
| SSD     | 168      | 315    | 29.17%  |
| NVMe    | 73       | 103    | 12.67%  |
| Unknown | 5        | 50     | 0.87%   |
| MMC     | 4        | 4      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 386      | 1236   | 79.1%   |
| NVMe | 73       | 103    | 14.96%  |
| SAS  | 25       | 239    | 5.12%   |
| MMC  | 4        | 4      | 0.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 221      | 512    | 38.7%   |
| 0.51-1.0   | 208      | 316    | 36.43%  |
| 1.01-2.0   | 65       | 166    | 11.38%  |
| 3.01-4.0   | 28       | 179    | 4.9%    |
| 4.01-10.0  | 23       | 118    | 4.03%   |
| 2.01-3.0   | 18       | 73     | 3.15%   |
| 10.01-20.0 | 8        | 61     | 1.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 134      | 30.59%  |
| 251-500        | 80       | 18.26%  |
| 101-250        | 58       | 13.24%  |
| More than 3000 | 55       | 12.56%  |
| 1001-2000      | 44       | 10.05%  |
| Unknown        | 17       | 3.88%   |
| 21-50          | 13       | 2.97%   |
| 2001-3000      | 13       | 2.97%   |
| 51-100         | 13       | 2.97%   |
| 1-20           | 11       | 2.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 135      | 30.47%  |
| 101-250        | 78       | 17.61%  |
| 21-50          | 51       | 11.51%  |
| 51-100         | 49       | 11.06%  |
| 251-500        | 32       | 7.22%   |
| More than 3000 | 30       | 6.77%   |
| 501-1000       | 30       | 6.77%   |
| Unknown        | 17       | 3.84%   |
| 1001-2000      | 14       | 3.16%   |
| 2001-3000      | 6        | 1.35%   |
| 0              | 1        | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4        | 4      | 5%      |
| Seagate ST2000DM001-9YN164 2TB        | 3        | 3      | 3.75%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2        | 5      | 2.5%    |
| WDC WD10EZEX-08WN4A0 1TB              | 2        | 2      | 2.5%    |
| WDC WD1001FALS-00J7B1 1TB             | 2        | 2      | 2.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 1.25%   |
| WDC WD6400AADS-00M2B0 640GB           | 1        | 1      | 1.25%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1        | 1      | 1.25%   |
| WDC WD5000AVCS-632DY1 500GB           | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 1      | 1.25%   |
| WDC WD5000AACS-00G8B0 500GB           | 1        | 1      | 1.25%   |
| WDC WD3200AVVS-63L2B0 320GB           | 1        | 1      | 1.25%   |
| WDC WD3200AAKS-75L9A0 320GB           | 1        | 1      | 1.25%   |
| WDC WD30PURX-64P6ZY0 3TB              | 1        | 1      | 1.25%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 3      | 1.25%   |
| WDC WD2500HHTZ-04N21V0 250GB          | 1        | 1      | 1.25%   |
| WDC WD20PURX-64PFUY0 2TB              | 1        | 1      | 1.25%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 1.25%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 1.25%   |
| WDC WD20EARS-00MVWB0 2TB              | 1        | 2      | 1.25%   |
| WDC WD10PURX-64E5EY0 1TB              | 1        | 1      | 1.25%   |
| WDC WD10EZEX-60WN4A1 1TB              | 1        | 1      | 1.25%   |
| WDC WD10EZEX-60M2NA0 1TB              | 1        | 1      | 1.25%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 1      | 1.25%   |
| WDC WD1003FBYX-01Y7B0 1TB             | 1        | 1      | 1.25%   |
| WDC WD1002FBYS-18A6B0 1TB             | 1        | 1      | 1.25%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1        | 1      | 1.25%   |
| WDC RFT030VQFF-KRM5P7 3TB             | 1        | 1      | 1.25%   |
| Toshiba MK2561GSYN 250GB              | 1        | 1      | 1.25%   |
| Toshiba MK2552GSX 250GB               | 1        | 1      | 1.25%   |
| Toshiba MK1234GSX 118GB               | 1        | 1      | 1.25%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1        | 1      | 1.25%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 1.25%   |
| Seagate ST380211AS 80GB               | 1        | 1      | 1.25%   |
| Seagate ST380013AS 80GB               | 1        | 1      | 1.25%   |
| Seagate ST3400820AS 400GB             | 1        | 1      | 1.25%   |
| Seagate ST3250820AS 250GB             | 1        | 1      | 1.25%   |
| Seagate ST3250620NS 250GB             | 1        | 2      | 1.25%   |
| Seagate ST31000524NS 1TB              | 1        | 1      | 1.25%   |
| Seagate ST31000520AS 1TB              | 1        | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 35     | 32.43%  |
| Seagate             | 21       | 24     | 28.38%  |
| Hitachi             | 6        | 6      | 8.11%   |
| Samsung Electronics | 5        | 7      | 6.76%   |
| Intel               | 5        | 24     | 6.76%   |
| Toshiba             | 3        | 3      | 4.05%   |
| Kingston            | 3        | 3      | 4.05%   |
| HGST                | 2        | 3      | 2.7%    |
| SK hynix            | 1        | 1      | 1.35%   |
| SanDisk             | 1        | 1      | 1.35%   |
| Maxtor              | 1        | 1      | 1.35%   |
| LITEONIT            | 1        | 1      | 1.35%   |
| Crucial             | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 34     | 39.66%  |
| Seagate             | 21       | 24     | 36.21%  |
| Hitachi             | 6        | 6      | 10.34%  |
| Toshiba             | 3        | 3      | 5.17%   |
| Samsung Electronics | 2        | 2      | 3.45%   |
| HGST                | 2        | 3      | 3.45%   |
| Maxtor              | 1        | 1      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 50       | 73     | 75.76%  |
| SSD  | 16       | 37     | 24.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 279      | 868    | 57.17%  |
| Detected | 145      | 602    | 29.71%  |
| Malfunc  | 63       | 110    | 12.91%  |
| Failed   | 1        | 2      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 338      | 58.58%  |
| AMD                            | 78       | 13.52%  |
| Samsung Electronics            | 27       | 4.68%   |
| ASMedia Technology             | 24       | 4.16%   |
| LSI Logic / Symbios Logic      | 14       | 2.43%   |
| SanDisk                        | 13       | 2.25%   |
| Marvell Technology Group       | 12       | 2.08%   |
| JMicron Technology             | 12       | 2.08%   |
| Phison Electronics             | 9        | 1.56%   |
| Broadcom / LSI                 | 7        | 1.21%   |
| Silicon Motion                 | 6        | 1.04%   |
| Adaptec                        | 6        | 1.04%   |
| ADATA Technology               | 5        | 0.87%   |
| Kingston Technology Company    | 4        | 0.69%   |
| Silicon Image                  | 3        | 0.52%   |
| Micron/Crucial Technology      | 3        | 0.52%   |
| Micron Technology              | 3        | 0.52%   |
| Nvidia                         | 2        | 0.35%   |
| 3ware                          | 2        | 0.35%   |
| VIA Technologies               | 1        | 0.17%   |
| Toshiba America Info Systems   | 1        | 0.17%   |
| Solid State Storage Technology | 1        | 0.17%   |
| SK hynix                       | 1        | 0.17%   |
| Seagate Technology             | 1        | 0.17%   |
| Realtek Semiconductor          | 1        | 0.17%   |
| MAXIO Technology (Hangzhou)    | 1        | 0.17%   |
| KIOXIA                         | 1        | 0.17%   |
| Integrated Technology Express  | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 55       | 7.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 45       | 6.49%   |
| Intel SATA Controller [RAID mode]                                                       | 39       | 5.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 35       | 5.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28       | 4.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 24       | 3.46%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 20       | 2.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 1.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 1.59%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 10       | 1.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 10       | 1.44%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 9        | 1.3%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 1.3%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 8        | 1.15%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 7        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.01%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 0.87%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.72%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 0.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 0.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.72%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.58%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 4        | 0.58%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 4        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 326      | 58.21%  |
| IDE  | 75       | 13.39%  |
| NVMe | 73       | 13.04%  |
| RAID | 65       | 11.61%  |
| SAS  | 14       | 2.5%    |
| SCSI | 7        | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 348      | 81.69%  |
| AMD    | 78       | 18.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 5.15%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 21       | 4.92%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 17       | 3.98%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 13       | 3.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 2.11%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 8        | 1.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 1.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 1.41%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 1.41%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.41%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 1.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 1.17%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 0.94%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 4        | 0.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.94%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.94%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 3        | 0.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 0.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 0.7%    |
| Intel Core i5-9500 CPU @ 3.00GHz            | 3        | 0.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.7%    |
| Intel Core i5-10500 CPU @ 3.10GHz           | 3        | 0.7%    |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 0.7%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 0.7%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 0.7%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 3        | 0.7%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.7%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 0.7%    |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.7%    |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 2        | 0.47%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 2        | 0.47%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 2        | 0.47%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 2        | 0.47%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2        | 0.47%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 2        | 0.47%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 0.47%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 2        | 0.47%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 2        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 124      | 29.04%  |
| Intel Core i7           | 75       | 17.56%  |
| Intel Xeon              | 56       | 13.11%  |
| Intel Core i3           | 22       | 5.15%   |
| AMD FX                  | 18       | 4.22%   |
| AMD Ryzen 5             | 17       | 3.98%   |
| Intel Core 2 Duo        | 12       | 2.81%   |
| Other                   | 11       | 2.58%   |
| Intel Core 2 Quad       | 11       | 2.58%   |
| AMD Ryzen 9             | 10       | 2.34%   |
| Intel Pentium           | 9        | 2.11%   |
| AMD Ryzen 7             | 9        | 2.11%   |
| Intel Atom              | 8        | 1.87%   |
| Intel Core i9           | 6        | 1.41%   |
| Intel Pentium Dual-Core | 5        | 1.17%   |
| Intel Celeron           | 5        | 1.17%   |
| AMD Ryzen 3             | 5        | 1.17%   |
| AMD Ryzen Threadripper  | 4        | 0.94%   |
| Intel Pentium Dual      | 2        | 0.47%   |
| AMD Turion II Neo       | 2        | 0.47%   |
| AMD Ryzen 7 PRO         | 2        | 0.47%   |
| AMD Phenom II X6        | 2        | 0.47%   |
| AMD A8                  | 2        | 0.47%   |
| AMD A10                 | 2        | 0.47%   |
| Intel Pentium Gold      | 1        | 0.23%   |
| Intel Genuine           | 1        | 0.23%   |
| AMD Phenom II X4        | 1        | 0.23%   |
| AMD Opteron             | 1        | 0.23%   |
| AMD GX                  | 1        | 0.23%   |
| AMD E2                  | 1        | 0.23%   |
| AMD Athlon              | 1        | 0.23%   |
| AMD A4                  | 1        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 203      | 47.54%  |
| 6      | 78       | 18.27%  |
| 2      | 63       | 14.75%  |
| 8      | 27       | 6.32%   |
| 12     | 18       | 4.22%   |
| 16     | 13       | 3.04%   |
| 3      | 8        | 1.87%   |
| 10     | 6        | 1.41%   |
| 1      | 4        | 0.94%   |
| 24     | 2        | 0.47%   |
| 20     | 2        | 0.47%   |
| 28     | 1        | 0.23%   |
| 18     | 1        | 0.23%   |
| 14     | 1        | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 404      | 94.84%  |
| 2      | 21       | 4.93%   |
| 0      | 1        | 0.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 222      | 51.87%  |
| 1      | 206      | 48.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 414      | 97.18%  |
| Unknown        | 12       | 2.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 63       | 14.62%  |
| Unknown    | 37       | 8.58%   |
| 0x906ea    | 31       | 7.19%   |
| 0x906e9    | 29       | 6.73%   |
| 0x306a9    | 23       | 5.34%   |
| 0x206a7    | 21       | 4.87%   |
| 0x506e3    | 20       | 4.64%   |
| 0x1067a    | 16       | 3.71%   |
| 0x06000852 | 14       | 3.25%   |
| 0x08701021 | 12       | 2.78%   |
| 0x306f2    | 11       | 2.55%   |
| 0xa0655    | 9        | 2.09%   |
| 0xa0653    | 8        | 1.86%   |
| 0x206c2    | 8        | 1.86%   |
| 0x08701013 | 8        | 1.86%   |
| 0x0800820d | 8        | 1.86%   |
| 0x206d7    | 7        | 1.62%   |
| 0x106e5    | 7        | 1.62%   |
| 0x906ed    | 6        | 1.39%   |
| 0x906ec    | 5        | 1.16%   |
| 0x6fb      | 5        | 1.16%   |
| 0x50654    | 5        | 1.16%   |
| 0x6fd      | 4        | 0.93%   |
| 0x406c4    | 4        | 0.93%   |
| 0x106ca    | 4        | 0.93%   |
| 0x106a5    | 4        | 0.93%   |
| 0x10676    | 4        | 0.93%   |
| 0x08001137 | 4        | 0.93%   |
| 0xa0671    | 3        | 0.7%    |
| 0x90672    | 3        | 0.7%    |
| 0x406f1    | 3        | 0.7%    |
| 0x40651    | 3        | 0.7%    |
| 0x0a201009 | 3        | 0.7%    |
| 0x08101016 | 3        | 0.7%    |
| 0x03000027 | 3        | 0.7%    |
| 0x906eb    | 2        | 0.46%   |
| 0x10677    | 2        | 0.46%   |
| 0x06001119 | 2        | 0.46%   |
| 0x010000dc | 2        | 0.46%   |
| 0x010000c8 | 2        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 79       | 18.46%  |
| KabyLake         | 74       | 17.29%  |
| SandyBridge      | 32       | 7.48%   |
| Skylake          | 29       | 6.78%   |
| IvyBridge        | 27       | 6.31%   |
| Penryn           | 26       | 6.07%   |
| Zen 2            | 23       | 5.37%   |
| Piledriver       | 20       | 4.67%   |
| CometLake        | 17       | 3.97%   |
| Westmere         | 12       | 2.8%    |
| Nehalem          | 11       | 2.57%   |
| Zen              | 10       | 2.34%   |
| Zen+             | 9        | 2.1%    |
| Core             | 9        | 2.1%    |
| Broadwell        | 7        | 1.64%   |
| Silvermont       | 6        | 1.4%    |
| Alderlake Hybrid | 6        | 1.4%    |
| Zen 3            | 5        | 1.17%   |
| K10              | 5        | 1.17%   |
| Bonnell          | 5        | 1.17%   |
| Unknown          | 5        | 1.17%   |
| K10 Llano        | 3        | 0.7%    |
| Jaguar           | 2        | 0.47%   |
| Bulldozer        | 2        | 0.47%   |
| Icelake          | 1        | 0.23%   |
| Gracemont        | 1        | 0.23%   |
| Goldmont plus    | 1        | 0.23%   |
| Goldmont         | 1        | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 216      | 47.89%  |
| Nvidia                                       | 128      | 28.38%  |
| AMD                                          | 88       | 19.51%  |
| ASPEED Technology                            | 10       | 2.22%   |
| Matrox Electronics Systems                   | 4        | 0.89%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.44%   |
| S3 Graphics                                  | 2        | 0.44%   |
| Silicon Motion                               | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 45       | 9.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 34       | 7.39%   |
| Intel HD Graphics 630                                                                    | 26       | 5.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15       | 3.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14       | 3.04%   |
| Intel HD Graphics 530                                                                    | 14       | 3.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14       | 3.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 11       | 2.39%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 10       | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 1.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 8        | 1.74%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8        | 1.74%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7        | 1.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 1.3%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5        | 1.09%   |
| AMD RS780L [Radeon 3000]                                                                 | 5        | 1.09%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 0.87%   |
| Nvidia GP107GL [Quadro P400]                                                             | 4        | 0.87%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4        | 0.87%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 0.87%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 3        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 0.65%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 3        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.65%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 3        | 0.65%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3        | 0.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3        | 0.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 0.65%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 0.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2        | 0.43%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2        | 0.43%   |
| Nvidia GT218 [GeForce G210]                                                              | 2        | 0.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 197      | 46.03%  |
| 1 x Nvidia              | 115      | 26.87%  |
| 1 x AMD                 | 79       | 18.46%  |
| 1 x ASPEED              | 6        | 1.4%    |
| 1 x Matrox              | 4        | 0.93%   |
| Intel + Nvidia          | 4        | 0.93%   |
| Intel + AMD             | 4        | 0.93%   |
| 2 x Nvidia              | 3        | 0.7%    |
| 2 x AMD                 | 3        | 0.7%    |
| Other                   | 2        | 0.47%   |
| 1 x XGI                 | 2        | 0.47%   |
| 1 x S3 Graphics         | 2        | 0.47%   |
| Nvidia + ASPEED         | 2        | 0.47%   |
| 3 x Nvidia + 1 x ASPEED | 1        | 0.23%   |
| 2 x AMD + 1 x ASPEED    | 1        | 0.23%   |
| 1 x Silicon Motion      | 1        | 0.23%   |
| Intel + 2 x Nvidia      | 1        | 0.23%   |
| AMD + Nvidia            | 1        | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 314      | 72.02%  |
| Proprietary | 65       | 14.91%  |
| Unknown     | 57       | 13.07%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 239      | 54.57%  |
| 1.01-2.0   | 58       | 13.24%  |
| 0.51-1.0   | 47       | 10.73%  |
| 0.01-0.5   | 29       | 6.62%   |
| 7.01-8.0   | 26       | 5.94%   |
| 3.01-4.0   | 20       | 4.57%   |
| 5.01-6.0   | 6        | 1.37%   |
| 8.01-16.0  | 5        | 1.14%   |
| 4.01-5.0   | 4        | 0.91%   |
| 2.01-3.0   | 3        | 0.68%   |
| 16.01-24.0 | 1        | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 70       | 20.96%  |
| Samsung Electronics     | 50       | 14.97%  |
| Hewlett-Packard         | 33       | 9.88%   |
| Goldstar                | 33       | 9.88%   |
| Acer                    | 21       | 6.29%   |
| AOC                     | 15       | 4.49%   |
| Philips                 | 14       | 4.19%   |
| BenQ                    | 13       | 3.89%   |
| Ancor Communications    | 12       | 3.59%   |
| ViewSonic               | 10       | 2.99%   |
| LG Electronics          | 7        | 2.1%    |
| Iiyama                  | 7        | 2.1%    |
| Eizo                    | 7        | 2.1%    |
| Unknown                 | 4        | 1.2%    |
| Sony                    | 3        | 0.9%    |
| NEC Computers           | 3        | 0.9%    |
| Lenovo                  | 3        | 0.9%    |
| ___                     | 2        | 0.6%    |
| Xiaomi                  | 2        | 0.6%    |
| Sceptre Tech            | 2        | 0.6%    |
| MStar                   | 2        | 0.6%    |
| HPN                     | 2        | 0.6%    |
| HannStar                | 2        | 0.6%    |
| Xerox                   | 1        | 0.3%    |
| Unknown (XXX)           | 1        | 0.3%    |
| Toshiba                 | 1        | 0.3%    |
| Sun                     | 1        | 0.3%    |
| Packard Bell            | 1        | 0.3%    |
| NME                     | 1        | 0.3%    |
| Insignia                | 1        | 0.3%    |
| HKC                     | 1        | 0.3%    |
| HannStar Display        | 1        | 0.3%    |
| GVV                     | 1        | 0.3%    |
| Founder                 | 1        | 0.3%    |
| Chimei Innolux          | 1        | 0.3%    |
| Chi Mei Optoelectronics | 1        | 0.3%    |
| AUS                     | 1        | 0.3%    |
| ASUSTek Computer        | 1        | 0.3%    |
| Apple                   | 1        | 0.3%    |
| AMW                     | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                    | 7        | 1.85%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                    | 6        | 1.58%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 4        | 1.06%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 4        | 1.06%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 3        | 0.79%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 3        | 0.79%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3        | 0.79%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 3        | 0.79%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 2        | 0.53%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch | 2        | 0.53%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 2        | 0.53%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch  | 2        | 0.53%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2        | 0.53%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 0.53%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2        | 0.53%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 2        | 0.53%   |
| Iiyama PL2888H IVM7106 1920x1080 620x340mm 27.8-inch                 | 2        | 0.53%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch        | 2        | 0.53%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch         | 2        | 0.53%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch           | 2        | 0.53%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2        | 0.53%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 2        | 0.53%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch               | 2        | 0.53%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                | 2        | 0.53%   |
| Dell ST2410 DELA05D 1920x1080 531x299mm 24.0-inch                    | 2        | 0.53%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 2        | 0.53%   |
| Dell SE2216H DELF070 1920x1080 476x268mm 21.5-inch                   | 2        | 0.53%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                   | 2        | 0.53%   |
| Dell P2417H DELA0DA 1920x1080 527x296mm 23.8-inch                    | 2        | 0.53%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                    | 2        | 0.53%   |
| BenQ LCD Monitor GW2283 3840x1080                                    | 2        | 0.53%   |
| BenQ LCD Monitor GW2283                                              | 2        | 0.53%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                    | 2        | 0.53%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1        | 0.26%   |
| ___ LCD TV ___0101 1920x1080                                         | 1        | 0.26%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                  | 1        | 0.26%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch            | 1        | 0.26%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1        | 0.26%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.26%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch        | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 152      | 45.92%  |
| 3840x2160 (4K)     | 31       | 9.37%   |
| 1920x1200 (WUXGA)  | 20       | 6.04%   |
| 1680x1050 (WSXGA+) | 18       | 5.44%   |
| Unknown            | 17       | 5.14%   |
| 2560x1440 (QHD)    | 16       | 4.83%   |
| 1366x768 (WXGA)    | 13       | 3.93%   |
| 1280x1024 (SXGA)   | 13       | 3.93%   |
| 3840x1080          | 7        | 2.11%   |
| 1600x900 (HD+)     | 7        | 2.11%   |
| 1440x900 (WXGA+)   | 7        | 2.11%   |
| 1024x768 (XGA)     | 6        | 1.81%   |
| 1600x1200          | 5        | 1.51%   |
| 3840x1200          | 3        | 0.91%   |
| 3440x1440          | 3        | 0.91%   |
| 2560x1080          | 3        | 0.91%   |
| 7680x1080          | 1        | 0.3%    |
| 7280x2160          | 1        | 0.3%    |
| 5760x1080          | 1        | 0.3%    |
| 5520x2160          | 1        | 0.3%    |
| 3640x1920          | 1        | 0.3%    |
| 2560x1600          | 1        | 0.3%    |
| 1680x1080          | 1        | 0.3%    |
| 1400x1050          | 1        | 0.3%    |
| 1360x768           | 1        | 0.3%    |
| 1280x960           | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 62       | 18.29%  |
| 21      | 50       | 14.75%  |
| 27      | 49       | 14.45%  |
| 23      | 46       | 13.57%  |
| Unknown | 37       | 10.91%  |
| 19      | 13       | 3.83%   |
| 22      | 12       | 3.54%   |
| 20      | 12       | 3.54%   |
| 15      | 10       | 2.95%   |
| 18      | 8        | 2.36%   |
| 17      | 6        | 1.77%   |
| 31      | 5        | 1.47%   |
| 34      | 4        | 1.18%   |
| 25      | 4        | 1.18%   |
| 40      | 3        | 0.88%   |
| 32      | 3        | 0.88%   |
| 84      | 2        | 0.59%   |
| 72      | 2        | 0.59%   |
| 65      | 2        | 0.59%   |
| 52      | 2        | 0.59%   |
| 58      | 1        | 0.29%   |
| 49      | 1        | 0.29%   |
| 42      | 1        | 0.29%   |
| 38      | 1        | 0.29%   |
| 29      | 1        | 0.29%   |
| 26      | 1        | 0.29%   |
| 16      | 1        | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 139      | 43.44%  |
| 401-500     | 82       | 25.63%  |
| Unknown     | 37       | 11.56%  |
| 301-350     | 16       | 5%      |
| 601-700     | 15       | 4.69%   |
| 351-400     | 9        | 2.81%   |
| 701-800     | 7        | 2.19%   |
| 1001-1500   | 6        | 1.88%   |
| 801-900     | 4        | 1.25%   |
| 1501-2000   | 4        | 1.25%   |
| 901-1000    | 1        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 192      | 63.37%  |
| 16/10   | 46       | 15.18%  |
| Unknown | 34       | 11.22%  |
| 5/4     | 13       | 4.29%   |
| 4/3     | 13       | 4.29%   |
| 21/9    | 4        | 1.32%   |
| 3/2     | 1        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 130      | 39.63%  |
| 301-350        | 49       | 14.94%  |
| Unknown        | 37       | 11.28%  |
| 151-200        | 32       | 9.76%   |
| 251-300        | 28       | 8.54%   |
| 351-500        | 13       | 3.96%   |
| 141-150        | 13       | 3.96%   |
| More than 1000 | 10       | 3.05%   |
| 101-110        | 9        | 2.74%   |
| 501-1000       | 5        | 1.52%   |
| 111-120        | 2        | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 187      | 59.74%  |
| 101-120 | 64       | 20.45%  |
| Unknown | 37       | 11.82%  |
| 121-160 | 12       | 3.83%   |
| 161-240 | 7        | 2.24%   |
| 1-50    | 6        | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 223      | 50.68%  |
| 0     | 149      | 33.86%  |
| 2     | 57       | 12.95%  |
| 3     | 6        | 1.36%   |
| 4     | 4        | 0.91%   |
| 6     | 1        | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Realtek Semiconductor       | 241      | 42.06%  |
| Intel                       | 204      | 35.6%   |
| Broadcom                    | 28       | 4.89%   |
| Qualcomm Atheros            | 23       | 4.01%   |
| Ralink Technology           | 14       | 2.44%   |
| TP-Link                     | 9        | 1.57%   |
| Aquantia                    | 6        | 1.05%   |
| Mellanox Technologies       | 5        | 0.87%   |
| D-Link System               | 5        | 0.87%   |
| Broadcom Limited            | 4        | 0.7%    |
| D-Link                      | 3        | 0.52%   |
| Marvell Technology Group    | 2        | 0.35%   |
| ICS Advent                  | 2        | 0.35%   |
| DisplayLink                 | 2        | 0.35%   |
| ASIX Electronics            | 2        | 0.35%   |
| 3Com                        | 2        | 0.35%   |
| Xilinx                      | 1        | 0.17%   |
| Xiaomi                      | 1        | 0.17%   |
| VIA Technologies            | 1        | 0.17%   |
| U-Blox                      | 1        | 0.17%   |
| Spreadtrum Communications   | 1        | 0.17%   |
| Sierra Wireless             | 1        | 0.17%   |
| Samsung Electronics         | 1        | 0.17%   |
| Ralink                      | 1        | 0.17%   |
| NetGear                     | 1        | 0.17%   |
| MYRICOM                     | 1        | 0.17%   |
| MediaTek                    | 1        | 0.17%   |
| LSI                         | 1        | 0.17%   |
| Linux 2.6.31.6 with s3c-udc | 1        | 0.17%   |
| Linksys                     | 1        | 0.17%   |
| Huawei Technologies         | 1        | 0.17%   |
| Exar                        | 1        | 0.17%   |
| Dresden Elektronik          | 1        | 0.17%   |
| Cisco Systems               | 1        | 0.17%   |
| Ceton Technologies          | 1        | 0.17%   |
| Apple                       | 1        | 0.17%   |
| Accton Technology           | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 202      | 31.61%  |
| Intel I211 Gigabit Network Connection                                          | 25       | 3.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23       | 3.6%    |
| Intel Ethernet Connection I217-LM                                              | 20       | 3.13%   |
| Intel Ethernet Connection (2) I219-LM                                          | 18       | 2.82%   |
| Intel 82574L Gigabit Network Connection                                        | 16       | 2.5%    |
| Intel Ethernet Connection (2) I219-V                                           | 13       | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11       | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11       | 1.72%   |
| Intel Wi-Fi 6 AX200                                                            | 10       | 1.56%   |
| Intel 82579V Gigabit Network Connection                                        | 9        | 1.41%   |
| Intel I210 Gigabit Network Connection                                          | 8        | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 8        | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                                          | 7        | 1.1%    |
| Intel Ethernet Connection (2) I218-V                                           | 7        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6        | 0.94%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6        | 0.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 6        | 0.94%   |
| Ralink MT7601U Wireless Adapter                                                | 5        | 0.78%   |
| Intel I350 Gigabit Network Connection                                          | 5        | 0.78%   |
| Intel Ethernet Controller I225-V                                               | 5        | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5        | 0.78%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 5        | 0.78%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 0.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 4        | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 0.63%   |
| Ralink RT5370 Wireless Adapter                                                 | 4        | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 4        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3        | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3        | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3        | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 0.47%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 3        | 0.47%   |
| Intel Wireless 7260                                                            | 3        | 0.47%   |
| Intel Ethernet Controller X550                                                 | 3        | 0.47%   |
| Intel Ethernet Connection I217-V                                               | 3        | 0.47%   |
| Intel 82580 Gigabit Network Connection                                         | 3        | 0.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 3        | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 39       | 35.45%  |
| Realtek Semiconductor | 19       | 17.27%  |
| Ralink Technology     | 14       | 12.73%  |
| Qualcomm Atheros      | 13       | 11.82%  |
| TP-Link               | 9        | 8.18%   |
| Broadcom              | 7        | 6.36%   |
| D-Link                | 3        | 2.73%   |
| Sierra Wireless       | 1        | 0.91%   |
| Ralink                | 1        | 0.91%   |
| NetGear               | 1        | 0.91%   |
| MediaTek              | 1        | 0.91%   |
| Linksys               | 1        | 0.91%   |
| D-Link System         | 1        | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 10       | 9.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 8        | 7.21%   |
| Ralink MT7601U Wireless Adapter                                                               | 5        | 4.5%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 5        | 4.5%    |
| Ralink RT5370 Wireless Adapter                                                                | 4        | 3.6%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 4        | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3        | 2.7%    |
| Intel Wireless 7260                                                                           | 3        | 2.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.8%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 1.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 2        | 1.8%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 1.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 1.8%    |
| Realtek 802.11ac NIC                                                                          | 2        | 1.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 1.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 1.8%    |
| Intel Wireless 8265 / 8275                                                                    | 2        | 1.8%    |
| Intel Wireless 3165                                                                           | 2        | 1.8%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                                             | 2        | 1.8%    |
| D-Link 802.11 n WLAN                                                                          | 2        | 1.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.9%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.9%    |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.9%    |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.9%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                               | 1        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 0.9%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.9%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.9%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.9%    |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 0.9%    |
| Ralink RT2770 Wireless Adapter                                                                | 1        | 0.9%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 0.9%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 235      | 48.35%  |
| Intel                     | 185      | 38.07%  |
| Broadcom                  | 21       | 4.32%   |
| Qualcomm Atheros          | 10       | 2.06%   |
| Aquantia                  | 6        | 1.23%   |
| D-Link System             | 4        | 0.82%   |
| Broadcom Limited          | 4        | 0.82%   |
| Marvell Technology Group  | 2        | 0.41%   |
| ICS Advent                | 2        | 0.41%   |
| DisplayLink               | 2        | 0.41%   |
| ASIX Electronics          | 2        | 0.41%   |
| 3Com                      | 2        | 0.41%   |
| Xiaomi                    | 1        | 0.21%   |
| VIA Technologies          | 1        | 0.21%   |
| Spreadtrum Communications | 1        | 0.21%   |
| Samsung Electronics       | 1        | 0.21%   |
| MYRICOM                   | 1        | 0.21%   |
| Mellanox Technologies     | 1        | 0.21%   |
| Huawei Technologies       | 1        | 0.21%   |
| Cisco Systems             | 1        | 0.21%   |
| Ceton Technologies        | 1        | 0.21%   |
| Apple                     | 1        | 0.21%   |
| Accton Technology         | 1        | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 202      | 39%     |
| Intel I211 Gigabit Network Connection                                          | 25       | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23       | 4.44%   |
| Intel Ethernet Connection I217-LM                                              | 20       | 3.86%   |
| Intel Ethernet Connection (2) I219-LM                                          | 18       | 3.47%   |
| Intel 82574L Gigabit Network Connection                                        | 16       | 3.09%   |
| Intel Ethernet Connection (2) I219-V                                           | 13       | 2.51%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11       | 2.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11       | 2.12%   |
| Intel 82579V Gigabit Network Connection                                        | 9        | 1.74%   |
| Intel I210 Gigabit Network Connection                                          | 8        | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                                          | 7        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                                           | 7        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6        | 1.16%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6        | 1.16%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 6        | 1.16%   |
| Intel I350 Gigabit Network Connection                                          | 5        | 0.97%   |
| Intel Ethernet Controller I225-V                                               | 5        | 0.97%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5        | 0.97%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 4        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 0.58%   |
| Intel Ethernet Controller X550                                                 | 3        | 0.58%   |
| Intel Ethernet Connection I217-V                                               | 3        | 0.58%   |
| Intel 82580 Gigabit Network Connection                                         | 3        | 0.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 3        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2        | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.39%   |
| Intel Ethernet Connection I218-V                                               | 2        | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.39%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2        | 0.39%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2        | 0.39%   |
| Intel Ethernet Connection (11) I219-V                                          | 2        | 0.39%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 2        | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 0.39%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 2        | 0.39%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2        | 0.39%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 424      | 79.4%   |
| WiFi     | 100      | 18.73%  |
| Modem    | 5        | 0.94%   |
| Unknown  | 5        | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 399      | 92.36%  |
| WiFi     | 32       | 7.41%   |
| Unknown  | 1        | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 217      | 50.58%  |
| 2     | 163      | 38%     |
| 3     | 31       | 7.23%   |
| 4     | 7        | 1.63%   |
| 5     | 5        | 1.17%   |
| 0     | 3        | 0.7%    |
| 8     | 1        | 0.23%   |
| 7     | 1        | 0.23%   |
| 6     | 1        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 392      | 91.8%   |
| Yes  | 35       | 8.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 36       | 41.38%  |
| Cambridge Silicon Radio         | 21       | 24.14%  |
| Broadcom                        | 9        | 10.34%  |
| ASUSTek Computer                | 7        | 8.05%   |
| Realtek Semiconductor           | 5        | 5.75%   |
| Qualcomm Atheros Communications | 5        | 5.75%   |
| Lite-On Technology              | 1        | 1.15%   |
| IMC Networks                    | 1        | 1.15%   |
| Dynex                           | 1        | 1.15%   |
| Apple                           | 1        | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 21       | 24.14%  |
| Intel AX200 Bluetooth                                    | 10       | 11.49%  |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 6.9%    |
| Intel Bluetooth wireless interface                       | 6        | 6.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 6.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 4        | 4.6%    |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 3.45%   |
| Intel AX211 Bluetooth                                    | 3        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 3        | 3.45%   |
| Realtek Bluetooth Radio                                  | 2        | 2.3%    |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 2.3%    |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 2.3%    |
| Intel Bluetooth Device                                   | 2        | 2.3%    |
| Intel AX201 Bluetooth                                    | 2        | 2.3%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 2.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1        | 1.15%   |
| Lite-On Bluetooth Device                                 | 1        | 1.15%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 1.15%   |
| Intel AX210 Bluetooth                                    | 1        | 1.15%   |
| IMC Networks Bluetooth Device                            | 1        | 1.15%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.15%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 1.15%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1        | 1.15%   |
| Broadcom ANYCOM Blue USB-200/250                         | 1        | 1.15%   |
| ASUS Bluetooth Radio                                     | 1        | 1.15%   |
| ASUS BCM20702A0                                          | 1        | 1.15%   |
| Apple Bluetooth Host Controller                          | 1        | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 302      | 51.71%  |
| AMD                      | 120      | 20.55%  |
| Nvidia                   | 118      | 20.21%  |
| C-Media Electronics      | 7        | 1.2%    |
| Logitech                 | 6        | 1.03%   |
| Creative Labs            | 5        | 0.86%   |
| Texas Instruments        | 4        | 0.68%   |
| SteelSeries ApS          | 4        | 0.68%   |
| Plantronics              | 2        | 0.34%   |
| JMTek                    | 2        | 0.34%   |
| Creative Technology      | 2        | 0.34%   |
| TX                       | 1        | 0.17%   |
| NEC Computers            | 1        | 0.17%   |
| Micro Star International | 1        | 0.17%   |
| Lynx                     | 1        | 0.17%   |
| KTMicro                  | 1        | 0.17%   |
| Harman International     | 1        | 0.17%   |
| GN Netcom                | 1        | 0.17%   |
| Fry's Electronics        | 1        | 0.17%   |
| Ensoniq                  | 1        | 0.17%   |
| Corsair                  | 1        | 0.17%   |
| Avid Technology          | 1        | 0.17%   |
| ASUSTek Computer         | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 55       | 8.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 47       | 6.91%   |
| Intel 200 Series PCH HD Audio                                                     | 37       | 5.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 37       | 5.44%   |
| AMD Starship/Matisse HD Audio Controller                                          | 26       | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 24       | 3.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 23       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 21       | 3.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 21       | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 2.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 17       | 2.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 16       | 2.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 16       | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 15       | 2.21%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 12       | 1.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12       | 1.76%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 12       | 1.76%   |
| Nvidia High Definition Audio Controller                                           | 11       | 1.62%   |
| Intel Comet Lake PCH cAVS                                                         | 8        | 1.18%   |
| Nvidia TU104 HD Audio Controller                                                  | 7        | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                                     | 7        | 1.03%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 7        | 1.03%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 7        | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 7        | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7        | 1.03%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                | 6        | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                | 6        | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.74%   |
| Intel Alder Lake-S HD Audio Controller                                            | 5        | 0.74%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 0.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.59%   |
| Nvidia GF106 High Definition Audio Controller                                     | 4        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 71       | 20.46%  |
| Unknown             | 45       | 12.97%  |
| Samsung Electronics | 43       | 12.39%  |
| SK hynix            | 40       | 11.53%  |
| Crucial             | 40       | 11.53%  |
| G.Skill             | 25       | 7.2%    |
| Micron Technology   | 22       | 6.34%   |
| Corsair             | 17       | 4.9%    |
| Team                | 9        | 2.59%   |
| GeIL                | 9        | 2.59%   |
| A-DATA Technology   | 6        | 1.73%   |
| Patriot             | 5        | 1.44%   |
| Transcend           | 2        | 0.58%   |
| PNY                 | 2        | 0.58%   |
| Nanya Technology    | 2        | 0.58%   |
| Apacer              | 2        | 0.58%   |
| Unknown (9B0D)      | 1        | 0.29%   |
| TwinMOS             | 1        | 0.29%   |
| Ramaxel Technology  | 1        | 0.29%   |
| Mushkin             | 1        | 0.29%   |
| Hewlett-Packard     | 1        | 0.29%   |
| Elpida              | 1        | 0.29%   |
| Unknown             | 1        | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM CL16-16-16 D4-2400 8GB DIMM DDR4 2400MT/s     | 9        | 2.41%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM 1600MT/s              | 9        | 2.41%   |
| G.Skill RAM F4-2666C19-8GIS 8192MB DIMM DDR4 3200MT/s      | 9        | 2.41%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s        | 6        | 1.6%    |
| Crucial RAM CT8G4DFD8213.C16FBD2 8192MB DIMM DDR4 2500MT/s | 6        | 1.6%    |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s         | 5        | 1.34%   |
| Kingston RAM 9905678-173.A00G 8GB DIMM DDR4 2400MT/s       | 5        | 1.34%   |
| Samsung RAM Module 8192MB DIMM DDR4 3200MT/s               | 4        | 1.07%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s        | 4        | 1.07%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 4        | 1.07%   |
| Crucial RAM CT8G4DFS8213.C8FDD1 8GB DIMM DDR4 2400MT/s     | 4        | 1.07%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2667MT/s   | 4        | 1.07%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s      | 4        | 1.07%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 3        | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 3        | 0.8%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 3        | 0.8%    |
| Kingston RAM 99U5471-058.A00LF 8192MB DIMM DDR3 1600MT/s   | 3        | 0.8%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                       | 2        | 0.53%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 2        | 0.53%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 2        | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 2        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 2        | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 2        | 0.53%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                | 2        | 0.53%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s              | 2        | 0.53%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s                | 2        | 0.53%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 2        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2        | 0.53%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s       | 2        | 0.53%   |
| PNY RAM M4U08S681LJJJ43-12 8192MB DIMM DDR4 2666MT/s       | 2        | 0.53%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s         | 2        | 0.53%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s         | 2        | 0.53%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s       | 2        | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 2        | 0.53%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s        | 2        | 0.53%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 2        | 0.53%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 0.53%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s      | 2        | 0.53%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 2        | 0.53%   |
| Crucial RAM CT8G4DFS8266.C8FN 8GB DIMM DDR4 2667MT/s       | 2        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 139      | 44.27%  |
| DDR3         | 123      | 39.17%  |
| Unknown      | 21       | 6.69%   |
| DDR2         | 15       | 4.78%   |
| SDRAM        | 5        | 1.59%   |
| DRAM         | 5        | 1.59%   |
| DDR          | 3        | 0.96%   |
| LPDDR4       | 1        | 0.32%   |
| DDR5         | 1        | 0.32%   |
| DDR2 FB-DIMM | 1        | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 294      | 93.93%  |
| SODIMM | 17       | 5.43%   |
| RIMM   | 2        | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 137      | 40.9%   |
| 4096  | 79       | 23.58%  |
| 16384 | 58       | 17.31%  |
| 2048  | 35       | 10.45%  |
| 32768 | 15       | 4.48%   |
| 1024  | 10       | 2.99%   |
| 512   | 1        | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 79       | 23.37%  |
| 2400    | 49       | 14.5%   |
| 1333    | 43       | 12.72%  |
| 3200    | 28       | 8.28%   |
| 2667    | 25       | 7.4%    |
| 2133    | 17       | 5.03%   |
| 800     | 13       | 3.85%   |
| 667     | 12       | 3.55%   |
| 3600    | 9        | 2.66%   |
| 1800    | 7        | 2.07%   |
| Unknown | 7        | 2.07%   |
| 2500    | 6        | 1.78%   |
| 2666    | 5        | 1.48%   |
| 2800    | 4        | 1.18%   |
| 3466    | 2        | 0.59%   |
| 3000    | 2        | 0.59%   |
| 2933    | 2        | 0.59%   |
| 2134    | 2        | 0.59%   |
| 2000    | 2        | 0.59%   |
| 1867    | 2        | 0.59%   |
| 1866    | 2        | 0.59%   |
| 1648    | 2        | 0.59%   |
| 400     | 2        | 0.59%   |
| 65535   | 1        | 0.3%    |
| 5600    | 1        | 0.3%    |
| 4333    | 1        | 0.3%    |
| 4000    | 1        | 0.3%    |
| 3733    | 1        | 0.3%    |
| 3500    | 1        | 0.3%    |
| 3400    | 1        | 0.3%    |
| 3266    | 1        | 0.3%    |
| 3100    | 1        | 0.3%    |
| 3066    | 1        | 0.3%    |
| 2733    | 1        | 0.3%    |
| 2465    | 1        | 0.3%    |
| 2048    | 1        | 0.3%    |
| 1336    | 1        | 0.3%    |
| 1331    | 1        | 0.3%    |
| 1067    | 1        | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 6        | 50%     |
| Brother Industries | 3        | 25%     |
| Star Micronics     | 1        | 8.33%   |
| Kyocera            | 1        | 8.33%   |
| Canon              | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| HP DeskJet 2130 series            | 2        | 16.67%  |
| Star Micronics TSP100ECO/TSP100II | 1        | 8.33%   |
| Kyocera FS-1030D printer          | 1        | 8.33%   |
| HP LaserJet Professional P1606dn  | 1        | 8.33%   |
| HP LaserJet 400 M401dne           | 1        | 8.33%   |
| HP LaserJet 3030                  | 1        | 8.33%   |
| HP LaserJet 1020                  | 1        | 8.33%   |
| Canon MF210 Series                | 1        | 8.33%   |
| Brother MFC-J450DW                | 1        | 8.33%   |
| Brother MFC-9130CW                | 1        | 8.33%   |
| Brother HL-L2390DW                | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 40.54%  |
| Microdia                      | 5        | 13.51%  |
| Sunplus Innovation Technology | 2        | 5.41%   |
| Samsung Electronics           | 2        | 5.41%   |
| Realtek Semiconductor         | 2        | 5.41%   |
| Lenovo                        | 2        | 5.41%   |
| Z-Star Microelectronics       | 1        | 2.7%    |
| WaveRider Communications      | 1        | 2.7%    |
| Sunplus IT                    | 1        | 2.7%    |
| Microsoft                     | 1        | 2.7%    |
| KYE Systems                   | 1        | 2.7%    |
| Generalplus Technology        | 1        | 2.7%    |
| Cubeternet                    | 1        | 2.7%    |
| Creative Technology           | 1        | 2.7%    |
| Chicony Electronics           | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                 | 4        | 10.81%  |
| Logitech Webcam C270                        | 3        | 8.11%   |
| Logitech HD Webcam C615                     | 3        | 8.11%   |
| Sunplus Full HD webcam                      | 2        | 5.41%   |
| Samsung Galaxy series, misc. (MTP mode)     | 2        | 5.41%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 2        | 5.41%   |
| Microdia Camera                             | 2        | 5.41%   |
| Lenovo FHD Webcam                           | 2        | 5.41%   |
| Z-Star Venus USB2.0 Camera                  | 1        | 2.7%    |
| WaveRider USB 2.0 Camera                    | 1        | 2.7%    |
| Sunplus IT PC Camera                        | 1        | 2.7%    |
| Realtek USB Camera                          | 1        | 2.7%    |
| Realtek HD Camera                           | 1        | 2.7%    |
| Microsoft LifeCam HD-5000                   | 1        | 2.7%    |
| Microdia USB 2.0 Camera                     | 1        | 2.7%    |
| Logitech Webcam C930e                       | 1        | 2.7%    |
| Logitech Webcam C310                        | 1        | 2.7%    |
| Logitech Webcam C210                        | 1        | 2.7%    |
| Logitech StreamCam                          | 1        | 2.7%    |
| Logitech C922 Pro Stream Webcam             | 1        | 2.7%    |
| KYE Systems FaceCam 1320                    | 1        | 2.7%    |
| Generalplus 808 Camera                      | 1        | 2.7%    |
| Cubeternet USB2.0 Camera                    | 1        | 2.7%    |
| Creative Live! Cam Chat HD [VF0700/VF0790]  | 1        | 2.7%    |
| Chicony HP Integrated Webcam                | 1        | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Dell   | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Dell MS819 Dell Wired Mouse With Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SCM Microsystems    | 2        | 40%     |
| Giesecke & Devrient | 2        | 40%     |
| CHERRY              | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Giesecke & Devrient StarSign CUT S                         | 2        | 40%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader | 1        | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1        | 20%     |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 321      | 73.46%  |
| 1     | 80       | 18.31%  |
| 2     | 24       | 5.49%   |
| 4     | 7        | 1.6%    |
| 3     | 5        | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 59       | 36.42%  |
| Communication controller | 31       | 19.14%  |
| Net/wireless             | 23       | 14.2%   |
| Unassigned class         | 17       | 10.49%  |
| Net/ethernet             | 8        | 4.94%   |
| Storage/ide              | 7        | 4.32%   |
| Sound                    | 5        | 3.09%   |
| Network                  | 3        | 1.85%   |
| Storage/ata              | 2        | 1.23%   |
| Dvb card                 | 2        | 1.23%   |
| Storage/raid             | 1        | 0.62%   |
| Multimedia controller    | 1        | 0.62%   |
| Modem                    | 1        | 0.62%   |
| Card reader              | 1        | 0.62%   |
| Bluetooth                | 1        | 0.62%   |

