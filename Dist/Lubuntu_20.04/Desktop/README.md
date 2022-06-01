Lubuntu 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

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

Total: 169

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | FM2A85X Extreme6            | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Dell          | 08NPPY A00                  | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| Dell          | 018D1Y A00                  | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| ASUSTek       | M4N68T-M LE                 | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| ASRock        | Q1900M                      | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| HP            | 3647h                       | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| HP            | 2AF7                        | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Pegatron      | Narra6                      | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Gigabyte      | B450M S2H                   | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Dell          | 0TW904 A01                  | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| Dell          | 032W55 A03                  | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| ASUSTek       | A8N5X                       | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| AMI           | Cherry Trail Tablet         | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Dell          | 0J3C2F A02                  | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| ASUSTek       | CM1435                      | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | A520I AC                    | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | 0T568R A00                  | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Acer          | Aspire X1700                | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Acer          | Aspire X1700                | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| Foxconn       | 2AA9h                       | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| ASUSTek       | PRIME H410M-E               | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| MSI           | MS-7309                     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| AAEON         | MF-001 V1.0                 | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| Acer          | Aspire X1700                | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| Unknown       | X79M2-Q                     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| Pegatron      | Acacia                      | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| Foxconn       | Priv                        | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| ASRock        | Z590M-ITX/ax                | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| Dell          | 0M5DCD A00                  | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| MSI           | AMETHYST-M                  | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| ASRock        | FM2A68M-DG3+                | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| HP            | 8299                        | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| Huanan        | X99-TF V2.0                 | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| HP            | 1495                        | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| HP            | 0A1Ch E                     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Positivo      | POS-MI945AA                 | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| Dell          | 0TW904 A01                  | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Dell          | 0TW904 A01                  | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| ASUSTek       | K8N                         | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| HP            | 09C4h                       | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| Dell          | 0HY175 A03                  | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| MSI           | H61M-E33                    | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ASUSTek       | K8N                         | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| ASUSTek       | P5GC-MX/1333                | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| AAEON         | MF-001 V1.0                 | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| ASRock        | FM2A88M Extreme4+           | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | Z97-K                       | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Dell          | 09M8Y8 A01                  | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASRock        | 775Dual-VSTA                | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Dell          | 09M8Y8 A01                  | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Intel         | ChiefRiver                  | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| HP            | 3048h                       | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| ASUSTek       | P8Z68-V LX                  | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | ThinkCentre M58p 6136A66    | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Dell          | 0WG864                      | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| ASRock        | FM2A85X Extreme6            | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | 2820h                       | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| Pegatron      | Narra6                      | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| HP            | 09F8h                       | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| MSI           | G41M-P28                    | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| ASRock        | 4Core1600-GLAN              | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Gigabyte      | B250M-D3H-CF                | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Dell          | 0J3C2F A02                  | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| ASRock        | G41M-GS3                    | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| MSI           | H97M-E35                    | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| MSI           | H110M ECO                   | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Gigabyte      | Z370P D3-CF                 | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| MSI           | B450M MORTAR MAX            | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| ASRock        | A320M-DGS                   | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Intel         | DG31PR AAD97573-302         | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Dell          | 0CU409                      | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Lenovo        | SDK0E50515 STD              | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| IBM           | eServer x3105 -[434722J]... | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| MSI           | B450M MORTAR MAX            | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| HP            | 3396                        | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| MSI           | X570-A PRO                  | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| ASUSTek       | M2R-FVM                     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| MSI           | 0A48                        | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| ASUSTek       | ET1612I                     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| ASUSTek       | ET1612I                     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| Biostar       | GF7025-M2                   | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Gigabyte      | GA-870A-UD3                 | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| ASUSTek       | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| ASUSTek       | P5B-Deluxe                  | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Acer          | Aspire XC-703G              | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| Intel         | DN2800MT AAG23738-801       | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.4.0-52-generic      | 8        | 5.76%   |
| 5.4.0-42-generic      | 8        | 5.76%   |
| 5.11.0-27-generic     | 7        | 5.04%   |
| 5.8.0-50-generic      | 6        | 4.32%   |
| 5.4.0-54-generic      | 5        | 3.6%    |
| 5.13.0-28-generic     | 5        | 3.6%    |
| 5.4.0-67-generic      | 4        | 2.88%   |
| 5.4.0-40-generic      | 4        | 2.88%   |
| 5.4.0-29-generic      | 4        | 2.88%   |
| 5.4.0-77-generic      | 3        | 2.16%   |
| 5.4.0-73-generic      | 3        | 2.16%   |
| 5.4.0-48-generic      | 3        | 2.16%   |
| 5.4.0-47-generic      | 3        | 2.16%   |
| 5.4.0-37-generic      | 3        | 2.16%   |
| 5.4.0-33-generic      | 3        | 2.16%   |
| 5.4.0-26-generic      | 3        | 2.16%   |
| 5.8.0-63-generic      | 2        | 1.44%   |
| 5.8.0-59-generic      | 2        | 1.44%   |
| 5.8.0-53-generic      | 2        | 1.44%   |
| 5.8.0-45-generic      | 2        | 1.44%   |
| 5.8.0-41-generic      | 2        | 1.44%   |
| 5.4.0-96-generic      | 2        | 1.44%   |
| 5.4.0-90-generic      | 2        | 1.44%   |
| 5.4.0-72-generic      | 2        | 1.44%   |
| 5.4.0-66-generic      | 2        | 1.44%   |
| 5.4.0-60-generic      | 2        | 1.44%   |
| 5.4.0-109-generic     | 2        | 1.44%   |
| 5.13.0-27-generic     | 2        | 1.44%   |
| 5.11.0-43-generic     | 2        | 1.44%   |
| 5.11.0-38-generic     | 2        | 1.44%   |
| 5.11.0-34-generic     | 2        | 1.44%   |
| 5.8.0-7630-generic    | 1        | 0.72%   |
| 5.8.0-55-generic      | 1        | 0.72%   |
| 5.8.0-48-generic      | 1        | 0.72%   |
| 5.8.0-43-generic      | 1        | 0.72%   |
| 5.8.0-29-lowlatency   | 1        | 0.72%   |
| 5.6.15-050615-generic | 1        | 0.72%   |
| 5.6.0-1052-oem        | 1        | 0.72%   |
| 5.4.30-dli            | 1        | 0.72%   |
| 5.4.0-99-generic      | 1        | 0.72%   |
| 5.4.0-91-generic      | 1        | 0.72%   |
| 5.4.0-89-generic      | 1        | 0.72%   |
| 5.4.0-88-generic      | 1        | 0.72%   |
| 5.4.0-81-generic      | 1        | 0.72%   |
| 5.4.0-75-generic      | 1        | 0.72%   |
| 5.4.0-65-generic      | 1        | 0.72%   |
| 5.4.0-64-generic      | 1        | 0.72%   |
| 5.4.0-59-generic      | 1        | 0.72%   |
| 5.4.0-58-generic      | 1        | 0.72%   |
| 5.4.0-53-generic      | 1        | 0.72%   |
| 5.4.0-31-generic      | 1        | 0.72%   |
| 5.4.0-107-generic     | 1        | 0.72%   |
| 5.4.0-105-generic     | 1        | 0.72%   |
| 5.4.0-100-generic     | 1        | 0.72%   |
| 5.3.18-dli            | 1        | 0.72%   |
| 5.16.5-051605-generic | 1        | 0.72%   |
| 5.14.0-051400-generic | 1        | 0.72%   |
| 5.13.0-41-generic     | 1        | 0.72%   |
| 5.13.0-40-generic     | 1        | 0.72%   |
| 5.13.0-37-generic     | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 75       | 56.39%  |
| 5.8.0   | 21       | 15.79%  |
| 5.11.0  | 18       | 13.53%  |
| 5.13.0  | 13       | 9.77%   |
| 5.6.15  | 1        | 0.75%   |
| 5.6.0   | 1        | 0.75%   |
| 5.4.30  | 1        | 0.75%   |
| 5.3.18  | 1        | 0.75%   |
| 5.16.5  | 1        | 0.75%   |
| 5.14.0  | 1        | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 76       | 57.14%  |
| 5.8     | 21       | 15.79%  |
| 5.11    | 18       | 13.53%  |
| 5.13    | 13       | 9.77%   |
| 5.6     | 2        | 1.5%    |
| 5.3     | 1        | 0.75%   |
| 5.16    | 1        | 0.75%   |
| 5.14    | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 132      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 124      | 93.94%  |
| LXDE       | 3        | 2.27%   |
| GNOME      | 2        | 1.52%   |
| XFCE       | 1        | 0.76%   |
| X-Cinnamon | 1        | 0.76%   |
| i3         | 1        | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 125      | 94.7%   |
| Tty     | 6        | 4.55%   |
| Unknown | 1        | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 69       | 51.11%  |
| Unknown | 41       | 30.37%  |
| LightDM | 9        | 6.67%   |
| GDM     | 8        | 5.93%   |
| TDM     | 6        | 4.44%   |
| LXDM    | 1        | 0.74%   |
| GDM3    | 1        | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 32       | 24.24%  |
| fr_FR   | 18       | 13.64%  |
| pt_BR   | 11       | 8.33%   |
| de_DE   | 11       | 8.33%   |
| it_IT   | 9        | 6.82%   |
| C       | 7        | 5.3%    |
| ru_RU   | 5        | 3.79%   |
| ja_JP   | 4        | 3.03%   |
| en_GB   | 4        | 3.03%   |
| en_AU   | 4        | 3.03%   |
| es_ES   | 3        | 2.27%   |
| hu_HU   | 2        | 1.52%   |
| fi_FI   | 2        | 1.52%   |
| en_ZA   | 2        | 1.52%   |
| en_CA   | 2        | 1.52%   |
| de_CH   | 2        | 1.52%   |
| cs_CZ   | 2        | 1.52%   |
| Unknown | 2        | 1.52%   |
| sv_SE   | 1        | 0.76%   |
| nl_NL   | 1        | 0.76%   |
| fr_CA   | 1        | 0.76%   |
| es_PE   | 1        | 0.76%   |
| es_MX   | 1        | 0.76%   |
| es_CR   | 1        | 0.76%   |
| es_CO   | 1        | 0.76%   |
| en_SG   | 1        | 0.76%   |
| en_NZ   | 1        | 0.76%   |
| el_GR   | 1        | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 89       | 67.42%  |
| EFI  | 43       | 32.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 121      | 91.67%  |
| Overlay | 7        | 5.3%    |
| Xfs     | 2        | 1.52%   |
| F2fs    | 1        | 0.76%   |
| Btrfs   | 1        | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 39.1%   |
| MBR     | 45       | 33.83%  |
| GPT     | 36       | 27.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 82.58%  |
| Yes       | 23       | 17.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 67.42%  |
| Yes       | 43       | 32.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 15.91%  |
| Hewlett-Packard     | 16       | 12.12%  |
| Gigabyte Technology | 15       | 11.36%  |
| Dell                | 14       | 10.61%  |
| MSI                 | 13       | 9.85%   |
| ASRock              | 13       | 9.85%   |
| Lenovo              | 8        | 6.06%   |
| Intel               | 6        | 4.55%   |
| Pegatron            | 4        | 3.03%   |
| Acer                | 4        | 3.03%   |
| AAEON               | 3        | 2.27%   |
| Positivo            | 2        | 1.52%   |
| Foxconn             | 2        | 1.52%   |
| Biostar             | 2        | 1.52%   |
| ZOTAC               | 1        | 0.76%   |
| Packard Bell        | 1        | 0.76%   |
| IBM                 | 1        | 0.76%   |
| Huanan              | 1        | 0.76%   |
| HARDKERNEL          | 1        | 0.76%   |
| Fujitsu Siemens     | 1        | 0.76%   |
| Fujitsu             | 1        | 0.76%   |
| AMI                 | 1        | 0.76%   |
| Unknown             | 1        | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| AAEON MF-001                                                 | 3        | 2.27%   |
| MSI MS-7C37                                                  | 2        | 1.52%   |
| MSI MS-7B89                                                  | 2        | 1.52%   |
| HP Compaq 6000 Pro SFF PC                                    | 2        | 1.52%   |
| Dell OptiPlex 790                                            | 2        | 1.52%   |
| ASRock N68-VS3 UCC                                           | 2        | 1.52%   |
| ASRock FM2A85X Extreme6                                      | 2        | 1.52%   |
| ZOTAC NM10                                                   | 1        | 0.76%   |
| Positivo POS-MI945AA                                         | 1        | 0.76%   |
| Positivo POS-EIH61CE                                         | 1        | 0.76%   |
| Pegatron WE216AA-ABF CQ5335FR                                | 1        | 0.76%   |
| Pegatron NC689AA-ABA s3700y                                  | 1        | 0.76%   |
| Pegatron FL308AA-ABD IQ512de                                 | 1        | 0.76%   |
| Pegatron AY652AA-ABA s5310y                                  | 1        | 0.76%   |
| Packard Bell IMEDIA S1350                                    | 1        | 0.76%   |
| MSI MS-7B86                                                  | 1        | 0.76%   |
| MSI MS-7994                                                  | 1        | 0.76%   |
| MSI MS-7846                                                  | 1        | 0.76%   |
| MSI MS-7680                                                  | 1        | 0.76%   |
| MSI MS-7640                                                  | 1        | 0.76%   |
| MSI MS-7592                                                  | 1        | 0.76%   |
| MSI MS-7309                                                  | 1        | 0.76%   |
| MSI ER883AA-ABA M7470N                                       | 1        | 0.76%   |
| MSI Compaq dx2200 MT                                         | 1        | 0.76%   |
| Lenovo ThinkStation P620 30E0CTO1WW                          | 1        | 0.76%   |
| Lenovo ThinkCentre M93z 10AD002DMZ                           | 1        | 0.76%   |
| Lenovo ThinkCentre M73 10AXS0HN00                            | 1        | 0.76%   |
| Lenovo ThinkCentre M58p 7220W21                              | 1        | 0.76%   |
| Lenovo ThinkCentre M58p 6136A66                              | 1        | 0.76%   |
| Lenovo ThinkCentre M55p 8811VQV                              | 1        | 0.76%   |
| Lenovo H50-50 90B60081IX                                     | 1        | 0.76%   |
| Lenovo H50-30g 90AS0002BR                                    | 1        | 0.76%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V304 | 1        | 0.76%   |
| Intel STK1AW32SC                                             | 1        | 0.76%   |
| Intel H55                                                    | 1        | 0.76%   |
| Intel DN2800MT AAG23738-801                                  | 1        | 0.76%   |
| Intel DG31PR AAD97573-302                                    | 1        | 0.76%   |
| Intel ChiefRiver                                             | 1        | 0.76%   |
| IBM eServer x3105 -[434722J]-                                | 1        | 0.76%   |
| Huanan X99-TF                                                | 1        | 0.76%   |
| HP Z230 Tower Workstation                                    | 1        | 0.76%   |
| HP xw9400 Workstation                                        | 1        | 0.76%   |
| HP xw9300 Workstation                                        | 1        | 0.76%   |
| HP t620 Quad Core TC                                         | 1        | 0.76%   |
| HP t620 Dual Core TC                                         | 1        | 0.76%   |
| HP ProDesk 600 G1 DM                                         | 1        | 0.76%   |
| HP EliteDesk 800 G3 SFF                                      | 1        | 0.76%   |
| HP Compaq Elite 8300 CMT                                     | 1        | 0.76%   |
| HP Compaq dc7800 Small Form Factor                           | 1        | 0.76%   |
| HP Compaq dc7600 Small Form Factor                           | 1        | 0.76%   |
| HP Compaq dc5800 Microtower                                  | 1        | 0.76%   |
| HP Compaq 8200 Elite SFF PC                                  | 1        | 0.76%   |
| HP Compaq 8000 Elite CMT PC                                  | 1        | 0.76%   |
| HP 500-203a                                                  | 1        | 0.76%   |
| HARDKERNEL ODROID-H2                                         | 1        | 0.76%   |
| Gigabyte Z370P D3                                            | 1        | 0.76%   |
| Gigabyte X570 GAMING X                                       | 1        | 0.76%   |
| Gigabyte K8M800-8237                                         | 1        | 0.76%   |
| Gigabyte H97-D3H                                             | 1        | 0.76%   |
| Gigabyte H81M-DS2                                            | 1        | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 8        | 6.06%   |
| Dell OptiPlex         | 6        | 4.55%   |
| Lenovo ThinkCentre    | 5        | 3.79%   |
| Acer Aspire           | 4        | 3.03%   |
| AAEON MF-001          | 3        | 2.27%   |
| MSI MS-7C37           | 2        | 1.52%   |
| MSI MS-7B89           | 2        | 1.52%   |
| HP t620               | 2        | 1.52%   |
| Gigabyte B450M        | 2        | 1.52%   |
| Dell Inspiron         | 2        | 1.52%   |
| ASRock N68-VS3        | 2        | 1.52%   |
| ASRock FM2A85X        | 2        | 1.52%   |
| ZOTAC NM10            | 1        | 0.76%   |
| Positivo POS-MI945AA  | 1        | 0.76%   |
| Positivo POS-EIH61CE  | 1        | 0.76%   |
| Pegatron WE216AA-ABF  | 1        | 0.76%   |
| Pegatron NC689AA-ABA  | 1        | 0.76%   |
| Pegatron FL308AA-ABD  | 1        | 0.76%   |
| Pegatron AY652AA-ABA  | 1        | 0.76%   |
| Packard Bell IMEDIA   | 1        | 0.76%   |
| MSI MS-7B86           | 1        | 0.76%   |
| MSI MS-7994           | 1        | 0.76%   |
| MSI MS-7846           | 1        | 0.76%   |
| MSI MS-7680           | 1        | 0.76%   |
| MSI MS-7640           | 1        | 0.76%   |
| MSI MS-7592           | 1        | 0.76%   |
| MSI MS-7309           | 1        | 0.76%   |
| MSI ER883AA-ABA       | 1        | 0.76%   |
| MSI Compaq            | 1        | 0.76%   |
| Lenovo ThinkStation   | 1        | 0.76%   |
| Lenovo H50-50         | 1        | 0.76%   |
| Lenovo H50-30g        | 1        | 0.76%   |
| Intel X79             | 1        | 0.76%   |
| Intel STK1AW32SC      | 1        | 0.76%   |
| Intel H55             | 1        | 0.76%   |
| Intel DN2800MT        | 1        | 0.76%   |
| Intel DG31PR          | 1        | 0.76%   |
| Intel ChiefRiver      | 1        | 0.76%   |
| IBM eServer           | 1        | 0.76%   |
| Huanan X99-TF         | 1        | 0.76%   |
| HP Z230               | 1        | 0.76%   |
| HP xw9400             | 1        | 0.76%   |
| HP xw9300             | 1        | 0.76%   |
| HP ProDesk            | 1        | 0.76%   |
| HP EliteDesk          | 1        | 0.76%   |
| HP 500-203a           | 1        | 0.76%   |
| HARDKERNEL ODROID-H2  | 1        | 0.76%   |
| Gigabyte Z370P        | 1        | 0.76%   |
| Gigabyte X570         | 1        | 0.76%   |
| Gigabyte K8M800-8237  | 1        | 0.76%   |
| Gigabyte H97-D3H      | 1        | 0.76%   |
| Gigabyte H81M-DS2     | 1        | 0.76%   |
| Gigabyte H61M-DS2H    | 1        | 0.76%   |
| Gigabyte GA-MA69G-S3H | 1        | 0.76%   |
| Gigabyte GA-870A-UD3  | 1        | 0.76%   |
| Gigabyte G41M-Combo   | 1        | 0.76%   |
| Gigabyte F2A88XM-HD3  | 1        | 0.76%   |
| Gigabyte B250M-D3H    | 1        | 0.76%   |
| Gigabyte A520I        | 1        | 0.76%   |
| Gigabyte 965P-DS3     | 1        | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 13       | 9.85%   |
| 2012 | 11       | 8.33%   |
| 2011 | 11       | 8.33%   |
| 2009 | 10       | 7.58%   |
| 2008 | 10       | 7.58%   |
| 2014 | 9        | 6.82%   |
| 2013 | 9        | 6.82%   |
| 2010 | 9        | 6.82%   |
| 2019 | 8        | 6.06%   |
| 2017 | 8        | 6.06%   |
| 2015 | 6        | 4.55%   |
| 2006 | 6        | 4.55%   |
| 2020 | 5        | 3.79%   |
| 2018 | 5        | 3.79%   |
| 2021 | 4        | 3.03%   |
| 2005 | 4        | 3.03%   |
| 2016 | 3        | 2.27%   |
| 2004 | 1        | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 132      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 128      | 96.97%  |
| Enabled  | 4        | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 132      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 40       | 30.08%  |
| 1.01-2.0        | 19       | 14.29%  |
| 8.01-16.0       | 19       | 14.29%  |
| 4.01-8.0        | 17       | 12.78%  |
| 16.01-24.0      | 17       | 12.78%  |
| 32.01-64.0      | 10       | 7.52%   |
| 24.01-32.0      | 3        | 2.26%   |
| 2.01-3.0        | 3        | 2.26%   |
| 64.01-256.0     | 2        | 1.5%    |
| 0.51-1.0        | 2        | 1.5%    |
| More than 256.0 | 1        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 67       | 49.26%  |
| 2.01-3.0   | 22       | 16.18%  |
| 0.51-1.0   | 20       | 14.71%  |
| 4.01-8.0   | 15       | 11.03%  |
| 3.01-4.0   | 6        | 4.41%   |
| 0.01-0.5   | 3        | 2.21%   |
| 8.01-16.0  | 2        | 1.47%   |
| 16.01-24.0 | 1        | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 51.52%  |
| 2      | 38       | 28.79%  |
| 4      | 11       | 8.33%   |
| 3      | 8        | 6.06%   |
| 5      | 4        | 3.03%   |
| 14     | 1        | 0.76%   |
| 7      | 1        | 0.76%   |
| 0      | 1        | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 84       | 63.16%  |
| No        | 49       | 36.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 131      | 99.24%  |
| No        | 1        | 0.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 59.09%  |
| Yes       | 54       | 40.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 83.33%  |
| Yes       | 22       | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 19       | 14.29%  |
| France       | 18       | 13.53%  |
| Germany      | 13       | 9.77%   |
| Brazil       | 12       | 9.02%   |
| Italy        | 9        | 6.77%   |
| Switzerland  | 6        | 4.51%   |
| Russia       | 5        | 3.76%   |
| Hungary      | 5        | 3.76%   |
| Spain        | 4        | 3.01%   |
| Japan        | 4        | 3.01%   |
| Australia    | 4        | 3.01%   |
| Netherlands  | 3        | 2.26%   |
| Finland      | 3        | 2.26%   |
| Czechia      | 3        | 2.26%   |
| Canada       | 3        | 2.26%   |
| South Africa | 2        | 1.5%    |
| Puerto Rico  | 2        | 1.5%    |
| New Zealand  | 2        | 1.5%    |
| Mexico       | 2        | 1.5%    |
| Greece       | 2        | 1.5%    |
| Belgium      | 2        | 1.5%    |
| UK           | 1        | 0.75%   |
| Sweden       | 1        | 0.75%   |
| Slovenia     | 1        | 0.75%   |
| Singapore    | 1        | 0.75%   |
| Romania      | 1        | 0.75%   |
| Peru         | 1        | 0.75%   |
| Malaysia     | 1        | 0.75%   |
| Costa Rica   | 1        | 0.75%   |
| Colombia     | 1        | 0.75%   |
| Belarus      | 1        | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Wellington            | 3        | 2.21%   |
| Melbourne             | 3        | 2.21%   |
| Zurich                | 2        | 1.47%   |
| Rome                  | 2        | 1.47%   |
| Pécs                 | 2        | 1.47%   |
| Cuernavaca            | 2        | 1.47%   |
| Cayey                 | 2        | 1.47%   |
| Bern                  | 2        | 1.47%   |
| Zwevegem              | 1        | 0.74%   |
| Wraysbury             | 1        | 0.74%   |
| Winsen                | 1        | 0.74%   |
| Wiesbaden             | 1        | 0.74%   |
| West Chester          | 1        | 0.74%   |
| Vinhedo               | 1        | 0.74%   |
| Vilyuchinsk           | 1        | 0.74%   |
| Villejuif             | 1        | 0.74%   |
| Vilabella             | 1        | 0.74%   |
| Vaxjo                 | 1        | 0.74%   |
| Vanderbijlpark        | 1        | 0.74%   |
| Valencia              | 1        | 0.74%   |
| Turku                 | 1        | 0.74%   |
| Trebur                | 1        | 0.74%   |
| Toulouse              | 1        | 0.74%   |
| Toronto               | 1        | 0.74%   |
| Tokorozawa            | 1        | 0.74%   |
| Stockton              | 1        | 0.74%   |
| Spokane               | 1        | 0.74%   |
| Sora                  | 1        | 0.74%   |
| Schiedam              | 1        | 0.74%   |
| Sautron               | 1        | 0.74%   |
| Sao Paulo             | 1        | 0.74%   |
| Sandorfalva           | 1        | 0.74%   |
| Salzgitter            | 1        | 0.74%   |
| Saint-Pair-sur-Mer    | 1        | 0.74%   |
| Saint-Michel-sur-Orge | 1        | 0.74%   |
| Roseburg              | 1        | 0.74%   |
| Roquecourbe           | 1        | 0.74%   |
| Ronnenberg            | 1        | 0.74%   |
| Rio de Janeiro        | 1        | 0.74%   |
| Raleigh               | 1        | 0.74%   |
| Racconigi             | 1        | 0.74%   |
| Raahe                 | 1        | 0.74%   |
| Prague                | 1        | 0.74%   |
| Portorož             | 1        | 0.74%   |
| Portbail              | 1        | 0.74%   |
| Poisy                 | 1        | 0.74%   |
| Passos                | 1        | 0.74%   |
| Pacatuba              | 1        | 0.74%   |
| Oradea                | 1        | 0.74%   |
| Omsk                  | 1        | 0.74%   |
| Ōita                 | 1        | 0.74%   |
| Oceanside             | 1        | 0.74%   |
| Novy Jicin            | 1        | 0.74%   |
| Neuville-en-Ferrain   | 1        | 0.74%   |
| Neuchatel             | 1        | 0.74%   |
| Nea Smyrni            | 1        | 0.74%   |
| Munich                | 1        | 0.74%   |
| Mount Vernon          | 1        | 0.74%   |
| Moscow                | 1        | 0.74%   |
| Moquegua              | 1        | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 50       | 62     | 25.13%  |
| WDC                 | 48       | 75     | 24.12%  |
| Samsung Electronics | 24       | 40     | 12.06%  |
| Toshiba             | 8        | 8      | 4.02%   |
| Kingston            | 8        | 8      | 4.02%   |
| Hitachi             | 8        | 10     | 4.02%   |
| Unknown             | 7        | 8      | 3.52%   |
| MAXTOR              | 4        | 4      | 2.01%   |
| Crucial             | 4        | 4      | 2.01%   |
| China               | 4        | 4      | 2.01%   |
| SanDisk             | 3        | 3      | 1.51%   |
| A-DATA Technology   | 3        | 4      | 1.51%   |
| Team                | 2        | 2      | 1.01%   |
| PNY                 | 2        | 2      | 1.01%   |
| LDLC                | 2        | 2      | 1.01%   |
| JMicron             | 2        | 2      | 1.01%   |
| Intel               | 2        | 2      | 1.01%   |
| Corsair             | 2        | 2      | 1.01%   |
| Transcend           | 1        | 1      | 0.5%    |
| TO Exter            | 1        | 1      | 0.5%    |
| PNY USB             | 1        | 1      | 0.5%    |
| Patriot             | 1        | 1      | 0.5%    |
| ORTIAL              | 1        | 1      | 0.5%    |
| OCZ                 | 1        | 1      | 0.5%    |
| LONDISK             | 1        | 1      | 0.5%    |
| Lexar               | 1        | 1      | 0.5%    |
| Leven               | 1        | 2      | 0.5%    |
| KingFast            | 1        | 1      | 0.5%    |
| Intenso             | 1        | 1      | 0.5%    |
| HGST                | 1        | 1      | 0.5%    |
| Hewlett-Packard     | 1        | 4      | 0.5%    |
| GOODRAM             | 1        | 1      | 0.5%    |
| Fujitsu             | 1        | 1      | 0.5%    |
| External            | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 1.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.9%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.9%    |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.9%    |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.9%    |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.9%    |
| WDC WD2500AAJS-75M0A0 249GB         | 2        | 0.9%    |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.9%    |
| Unknown M52516  16GB                | 2        | 0.9%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.9%    |
| Seagate ST380815AS 80GB             | 2        | 0.9%    |
| Seagate ST3500418AS 500GB           | 2        | 0.9%    |
| Seagate ST3360320AS 360GB           | 2        | 0.9%    |
| Seagate ST3250410AS 250GB           | 2        | 0.9%    |
| Seagate ST3250310AS 250GB           | 2        | 0.9%    |
| Seagate ST31000528AS 1TB            | 2        | 0.9%    |
| Seagate ST3000DM008-2DM166 3TB      | 2        | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.9%    |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 0.9%    |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.9%    |
| Samsung SSD 850 EVO 250GB           | 2        | 0.9%    |
| Samsung HD502IJ 500GB               | 2        | 0.9%    |
| Samsung HD161HJ 160GB               | 2        | 0.9%    |
| Samsung HD103SJ 1TB                 | 2        | 0.9%    |
| Samsung HD080HJ 80GB                | 2        | 0.9%    |
| Kingston SA400S37120G 120GB SSD     | 2        | 0.9%    |
| China SATA SSD 512GB                | 2        | 0.9%    |
| A-DATA SU650 240GB SSD              | 2        | 0.9%    |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.45%   |
| WDC WDS200T2B0A-00SM50 2TB SSD      | 1        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.45%   |
| WDC WD800JD-75JNA0 80GB             | 1        | 0.45%   |
| WDC WD7501AALS-00J7B1 752GB         | 1        | 0.45%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.45%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.45%   |
| WDC WD5000BPKX-66HPJT0 500GB        | 1        | 0.45%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.45%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 0.45%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.45%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.45%   |
| WDC WD50 00AAKS-00V1A 500GB         | 1        | 0.45%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 0.45%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.45%   |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.45%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.45%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1        | 0.45%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1        | 0.45%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.45%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 0.45%   |
| WDC WD2500JS-75NCB3 250GB           | 1        | 0.45%   |
| WDC WD2500JD-00HBB0 250GB           | 1        | 0.45%   |
| WDC WD2500AAKX-07U6AA1 250GB        | 1        | 0.45%   |
| WDC WD2500AAKX-07U6AA0 250GB        | 1        | 0.45%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.45%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.45%   |
| WDC WD1600BB-00RDA0 160GB           | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 50       | 62     | 39.68%  |
| WDC                 | 42       | 65     | 33.33%  |
| Samsung Electronics | 14       | 17     | 11.11%  |
| Hitachi             | 8        | 10     | 6.35%   |
| Toshiba             | 6        | 6      | 4.76%   |
| MAXTOR              | 3        | 3      | 2.38%   |
| Unknown             | 1        | 1      | 0.79%   |
| HGST                | 1        | 1      | 0.79%   |
| Fujitsu             | 1        | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 14.29%  |
| WDC                 | 8        | 10     | 12.7%   |
| Kingston            | 8        | 8      | 12.7%   |
| Crucial             | 4        | 4      | 6.35%   |
| China               | 4        | 4      | 6.35%   |
| SanDisk             | 3        | 3      | 4.76%   |
| Toshiba             | 2        | 2      | 3.17%   |
| Team                | 2        | 2      | 3.17%   |
| PNY                 | 2        | 2      | 3.17%   |
| Corsair             | 2        | 2      | 3.17%   |
| A-DATA Technology   | 2        | 3      | 3.17%   |
| Transcend           | 1        | 1      | 1.59%   |
| TO Exter            | 1        | 1      | 1.59%   |
| PNY USB             | 1        | 1      | 1.59%   |
| Patriot             | 1        | 1      | 1.59%   |
| ORTIAL              | 1        | 1      | 1.59%   |
| OCZ                 | 1        | 1      | 1.59%   |
| MAXTOR              | 1        | 1      | 1.59%   |
| LONDISK             | 1        | 1      | 1.59%   |
| Lexar               | 1        | 1      | 1.59%   |
| Leven               | 1        | 2      | 1.59%   |
| LDLC                | 1        | 1      | 1.59%   |
| JMicron             | 1        | 1      | 1.59%   |
| Intenso             | 1        | 1      | 1.59%   |
| Intel               | 1        | 1      | 1.59%   |
| Hewlett-Packard     | 1        | 4      | 1.59%   |
| GOODRAM             | 1        | 1      | 1.59%   |
| External            | 1        | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 97       | 166    | 58.43%  |
| SSD     | 56       | 73     | 33.73%  |
| MMC     | 6        | 7      | 3.61%   |
| NVMe    | 5        | 14     | 3.01%   |
| Unknown | 2        | 2      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 123      | 230    | 86.62%  |
| SAS  | 8        | 11     | 5.63%   |
| MMC  | 6        | 7      | 4.23%   |
| NVMe | 5        | 14     | 3.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 101      | 146    | 62.73%  |
| 0.51-1.0   | 42       | 63     | 26.09%  |
| 1.01-2.0   | 9        | 13     | 5.59%   |
| 3.01-4.0   | 4        | 12     | 2.48%   |
| 2.01-3.0   | 4        | 4      | 2.48%   |
| 4.01-10.0  | 1        | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 27.07%  |
| 251-500        | 28       | 21.05%  |
| 501-1000       | 15       | 11.28%  |
| 1001-2000      | 14       | 10.53%  |
| More than 3000 | 13       | 9.77%   |
| 51-100         | 10       | 7.52%   |
| 1-20           | 7        | 5.26%   |
| 2001-3000      | 6        | 4.51%   |
| 21-50          | 3        | 2.26%   |
| Unknown        | 1        | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 53       | 39.55%  |
| 21-50          | 22       | 16.42%  |
| 101-250        | 14       | 10.45%  |
| 51-100         | 10       | 7.46%   |
| 251-500        | 9        | 6.72%   |
| 501-1000       | 9        | 6.72%   |
| 1001-2000      | 7        | 5.22%   |
| More than 3000 | 5        | 3.73%   |
| 2001-3000      | 4        | 2.99%   |
| Unknown        | 1        | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB  | 2        | 2      | 8%      |
| WDC WD5000AAKX-003CA0 500GB     | 1        | 1      | 4%      |
| WDC WD400EB-00CPF0 40GB         | 1        | 1      | 4%      |
| WDC WD2500AAJS-75M0A0 249GB     | 1        | 1      | 4%      |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 2      | 4%      |
| WDC WD10EADS-65M2B0 1TB         | 1        | 1      | 4%      |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 4%      |
| Seagate ST380815AS 80GB         | 1        | 1      | 4%      |
| Seagate ST3360320AS 360GB       | 1        | 1      | 4%      |
| Seagate ST3200822AS 200GB       | 1        | 1      | 4%      |
| Seagate ST3160318AS 160GB       | 1        | 1      | 4%      |
| Seagate ST2000DX002-2DV164 2TB  | 1        | 1      | 4%      |
| Seagate ST1000DX001-1CM162 1TB  | 1        | 1      | 4%      |
| Seagate ST1000DM003-1ER162 1TB  | 1        | 1      | 4%      |
| MAXTOR STM3300622A 304GB        | 1        | 1      | 4%      |
| MAXTOR 6Y080L0 82GB             | 1        | 1      | 4%      |
| MAXTOR 6B200M0 208GB            | 1        | 1      | 4%      |
| LDLC SSD 120GB                  | 1        | 1      | 4%      |
| Kingston SHFS37A120G 120GB SSD  | 1        | 1      | 4%      |
| Kingston SA400S37120G 120GB SSD | 1        | 1      | 4%      |
| Hitachi HDS721075CLA332 752GB   | 1        | 1      | 4%      |
| Hitachi HDP725050GLA360 500GB   | 1        | 1      | 4%      |
| Hitachi HCP725050GLAT80 500GB   | 1        | 1      | 4%      |
| Fujitsu MHZ2160BH G2 160GB      | 1        | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 10       | 10     | 41.67%  |
| WDC      | 5        | 6      | 20.83%  |
| MAXTOR   | 3        | 3      | 12.5%   |
| Kingston | 2        | 2      | 8.33%   |
| Hitachi  | 2        | 3      | 8.33%   |
| LDLC     | 1        | 1      | 4.17%   |
| Fujitsu  | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 10     | 47.62%  |
| WDC     | 5        | 6      | 23.81%  |
| MAXTOR  | 3        | 3      | 14.29%  |
| Hitachi | 2        | 3      | 9.52%   |
| Fujitsu | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 23     | 86.36%  |
| SSD  | 3        | 3      | 13.64%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Samsung Electronics HD080HJ 80GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 65       | 127    | 43.62%  |
| Detected | 62       | 108    | 41.61%  |
| Malfunc  | 21       | 26     | 14.09%  |
| Failed   | 1        | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 79       | 54.48%  |
| AMD                       | 30       | 20.69%  |
| Nvidia                    | 16       | 11.03%  |
| JMicron Technology        | 5        | 3.45%   |
| Marvell Technology Group  | 4        | 2.76%   |
| ASMedia Technology        | 3        | 2.07%   |
| VIA Technologies          | 2        | 1.38%   |
| Samsung Electronics       | 2        | 1.38%   |
| LSI Logic / Symbios Logic | 2        | 1.38%   |
| Silicon Motion            | 1        | 0.69%   |
| ADATA Technology          | 1        | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 9.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 4.88%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 3.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.9%    |
| Nvidia MCP61 IDE                                                                        | 6        | 2.93%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 2.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.93%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.44%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 2.44%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.44%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 2.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.95%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.46%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.46%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.46%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.98%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.98%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.98%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.98%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.98%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2        | 0.98%   |
| AMD SB600 IDE                                                                           | 2        | 0.98%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 0.98%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 0.98%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.98%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.49%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.49%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.49%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.49%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.49%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.49%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.49%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.49%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.49%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.49%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.49%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.49%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.49%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.49%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.49%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.49%   |
| Intel SSD 660P Series                                                                   | 1        | 0.49%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 78       | 51.32%  |
| IDE  | 59       | 38.82%  |
| RAID | 8        | 5.26%   |
| NVMe | 5        | 3.29%   |
| SCSI | 2        | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 87       | 65.91%  |
| AMD    | 45       | 34.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 3.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.27%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3        | 2.27%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.27%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.27%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3        | 2.27%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.52%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.52%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.52%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 1.52%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.52%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.52%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.76%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1        | 0.76%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.76%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.76%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.76%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.76%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.76%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.76%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.76%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.76%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.76%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.76%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.76%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.76%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.76%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.76%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.76%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.76%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.76%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 0.76%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.76%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.76%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 0.76%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.76%   |
| Intel Core i5-4440S CPU @ 2.80GHz           | 1        | 0.76%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.76%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 0.76%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 0.76%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.76%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 0.76%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.76%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.76%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 0.76%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.76%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 0.76%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 0.76%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.76%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 0.76%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 0.76%   |
| Intel Core 2 Quad CPU @ 2.40GHz             | 1        | 0.76%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1        | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 22       | 16.67%  |
| Intel Core 2 Duo        | 12       | 9.09%   |
| Intel Core i3           | 8        | 6.06%   |
| Intel Atom              | 8        | 6.06%   |
| Intel Core i7           | 6        | 4.55%   |
| Intel Celeron           | 6        | 4.55%   |
| AMD Ryzen 5             | 6        | 4.55%   |
| AMD Athlon II X2        | 6        | 4.55%   |
| AMD Athlon 64 X2        | 6        | 4.55%   |
| Intel Xeon              | 5        | 3.79%   |
| Intel Core 2 Quad       | 5        | 3.79%   |
| Intel Core 2            | 5        | 3.79%   |
| AMD A10                 | 5        | 3.79%   |
| Intel Pentium Dual-Core | 4        | 3.03%   |
| AMD Ryzen 7             | 4        | 3.03%   |
| AMD Athlon 64           | 3        | 2.27%   |
| Intel Pentium Dual      | 2        | 1.52%   |
| Intel Pentium 4         | 2        | 1.52%   |
| AMD Sempron             | 2        | 1.52%   |
| AMD Ryzen 3             | 2        | 1.52%   |
| AMD GX                  | 2        | 1.52%   |
| AMD FX                  | 2        | 1.52%   |
| Intel Pentium Gold      | 1        | 0.76%   |
| Intel Pentium           | 1        | 0.76%   |
| AMD Ryzen Threadripper  | 1        | 0.76%   |
| AMD Quad-Core Opteron   | 1        | 0.76%   |
| AMD Phenom II X3        | 1        | 0.76%   |
| AMD Opteron             | 1        | 0.76%   |
| AMD E                   | 1        | 0.76%   |
| AMD Athlon X4           | 1        | 0.76%   |
| AMD Athlon II X4        | 1        | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 63       | 47.73%  |
| 4      | 43       | 32.58%  |
| 6      | 9        | 6.82%   |
| 1      | 8        | 6.06%   |
| 8      | 6        | 4.55%   |
| 64     | 1        | 0.76%   |
| 12     | 1        | 0.76%   |
| 3      | 1        | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 130      | 98.48%  |
| 2      | 2        | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 86       | 65.15%  |
| 2      | 46       | 34.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 132      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 15.91%  |
| 0x206a7    | 12       | 9.09%   |
| 0x306c3    | 10       | 7.58%   |
| 0x1067a    | 10       | 7.58%   |
| 0x06001119 | 5        | 3.79%   |
| 0x906e9    | 4        | 3.03%   |
| 0x6fd      | 4        | 3.03%   |
| 0x6fb      | 4        | 3.03%   |
| 0x406c4    | 4        | 3.03%   |
| 0x306a9    | 4        | 3.03%   |
| 0x6f6      | 3        | 2.27%   |
| 0x10676    | 3        | 2.27%   |
| 0x08701021 | 3        | 2.27%   |
| 0x010000c8 | 3        | 2.27%   |
| 0x6f2      | 2        | 1.52%   |
| 0x506e3    | 2        | 1.52%   |
| 0x30678    | 2        | 1.52%   |
| 0x206d7    | 2        | 1.52%   |
| 0x20655    | 2        | 1.52%   |
| 0x106ca    | 2        | 1.52%   |
| 0x08701013 | 2        | 1.52%   |
| 0x0800820d | 2        | 1.52%   |
| 0x0700010f | 2        | 1.52%   |
| 0x06000852 | 2        | 1.52%   |
| 0x010000c7 | 2        | 1.52%   |
| 0xf65      | 1        | 0.76%   |
| 0xf4a      | 1        | 0.76%   |
| 0xa0655    | 1        | 0.76%   |
| 0xa0653    | 1        | 0.76%   |
| 0x906ea    | 1        | 0.76%   |
| 0x706a1    | 1        | 0.76%   |
| 0x6f7      | 1        | 0.76%   |
| 0x406c3    | 1        | 0.76%   |
| 0x306f2    | 1        | 0.76%   |
| 0x306e4    | 1        | 0.76%   |
| 0x30661    | 1        | 0.76%   |
| 0x106e5    | 1        | 0.76%   |
| 0x10677    | 1        | 0.76%   |
| 0x0a50000c | 1        | 0.76%   |
| 0x0830104d | 1        | 0.76%   |
| 0x08108109 | 1        | 0.76%   |
| 0x06003106 | 1        | 0.76%   |
| 0x05000119 | 1        | 0.76%   |
| 0x010000db | 1        | 0.76%   |
| 0x01000095 | 1        | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 14       | 10.61%  |
| Penryn        | 14       | 10.61%  |
| Core          | 14       | 10.61%  |
| Haswell       | 13       | 9.85%   |
| K8 Hammer     | 11       | 8.33%   |
| K10           | 10       | 7.58%   |
| Zen 2         | 7        | 5.3%    |
| Silvermont    | 7        | 5.3%    |
| Piledriver    | 7        | 5.3%    |
| Zen+          | 5        | 3.79%   |
| KabyLake      | 5        | 3.79%   |
| IvyBridge     | 5        | 3.79%   |
| Skylake       | 3        | 2.27%   |
| CometLake     | 3        | 2.27%   |
| Bonnell       | 3        | 2.27%   |
| Westmere      | 2        | 1.52%   |
| NetBurst      | 2        | 1.52%   |
| Jaguar        | 2        | 1.52%   |
| Zen 3         | 1        | 0.76%   |
| Steamroller   | 1        | 0.76%   |
| Nehalem       | 1        | 0.76%   |
| Goldmont plus | 1        | 0.76%   |
| Bobcat        | 1        | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 50       | 36.5%   |
| Intel  | 47       | 34.31%  |
| AMD    | 40       | 29.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 6.29%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.5%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5        | 3.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 3.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 2.8%    |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 2.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.1%    |
| Intel HD Graphics 530                                                                    | 3        | 2.1%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.1%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 2.1%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.4%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.4%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2        | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.4%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.4%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.4%    |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.4%    |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.4%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.4%    |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.4%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.4%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.7%    |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.7%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.7%    |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.7%    |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.7%    |
| Nvidia GT218 [ION]                                                                       | 1        | 0.7%    |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.7%    |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.7%    |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.7%    |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.7%    |
| Nvidia GP107GL [Quadro P400]                                                             | 1        | 0.7%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.7%    |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.7%    |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 0.7%    |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.7%    |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 0.7%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.7%    |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.7%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.7%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.7%    |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.7%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.7%    |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1        | 0.7%    |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 0.7%    |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.7%    |
| Nvidia G92 [GeForce GTS 250]                                                             | 1        | 0.7%    |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.7%    |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.7%    |
| Intel HD Graphics 630                                                                    | 1        | 0.7%    |
| Intel HD Graphics 610                                                                    | 1        | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.7%    |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 1        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 47       | 35.34%  |
| 1 x Intel    | 45       | 33.83%  |
| 1 x AMD      | 35       | 26.32%  |
| 2 x AMD      | 4        | 3.01%   |
| 2 x Nvidia   | 1        | 0.75%   |
| AMD + Nvidia | 1        | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 107      | 81.06%  |
| Proprietary | 24       | 18.18%  |
| Unknown     | 1        | 0.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 38.35%  |
| 0.01-0.5   | 34       | 25.56%  |
| 0.51-1.0   | 21       | 15.79%  |
| 1.01-2.0   | 14       | 10.53%  |
| 3.01-4.0   | 7        | 5.26%   |
| 7.01-8.0   | 3        | 2.26%   |
| 8.01-16.0  | 2        | 1.5%    |
| 2.01-3.0   | 1        | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 18       | 13.74%  |
| Dell                    | 17       | 12.98%  |
| Goldstar                | 15       | 11.45%  |
| Acer                    | 10       | 7.63%   |
| Hewlett-Packard         | 9        | 6.87%   |
| Lenovo                  | 5        | 3.82%   |
| Iiyama                  | 5        | 3.82%   |
| BenQ                    | 5        | 3.82%   |
| Vizio                   | 4        | 3.05%   |
| Philips                 | 4        | 3.05%   |
| Ancor Communications    | 4        | 3.05%   |
| Unknown                 | 3        | 2.29%   |
| AOC                     | 3        | 2.29%   |
| Sony                    | 2        | 1.53%   |
| LG Electronics          | 2        | 1.53%   |
| IOD                     | 2        | 1.53%   |
| FL_                     | 2        | 1.53%   |
| ___                     | 1        | 0.76%   |
| ViewSonic               | 1        | 0.76%   |
| Unknown (ADA)           | 1        | 0.76%   |
| Sceptre Tech            | 1        | 0.76%   |
| Proview                 | 1        | 0.76%   |
| Plain Tree Systems      | 1        | 0.76%   |
| NEC Computers           | 1        | 0.76%   |
| MOT                     | 1        | 0.76%   |
| Lite-On                 | 1        | 0.76%   |
| LG Display              | 1        | 0.76%   |
| Lenovo Group Limited    | 1        | 0.76%   |
| IBM                     | 1        | 0.76%   |
| Hitachi                 | 1        | 0.76%   |
| HannStar                | 1        | 0.76%   |
| GDH                     | 1        | 0.76%   |
| Fujitsu Siemens         | 1        | 0.76%   |
| Element                 | 1        | 0.76%   |
| CVT                     | 1        | 0.76%   |
| Compaq Computer         | 1        | 0.76%   |
| Chi Mei Optoelectronics | 1        | 0.76%   |
| Arnos Instruments       | 1        | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 1.47%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 1.47%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2        | 1.47%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 1.47%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 1.47%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2        | 1.47%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 1.47%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.74%   |
| ___ LCDTV14 ___0101 1920x1080                                         | 1        | 0.74%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.74%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1        | 0.74%   |
| Vizio E471VLE VIZ0090 1920x1080 1040x590mm 47.1-inch                  | 1        | 0.74%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                    | 1        | 0.74%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch              | 1        | 0.74%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.74%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.74%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.74%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.74%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.74%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.74%   |
| Sony TV SNYAA01 1360x768                                              | 1        | 0.74%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.74%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1        | 0.74%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.74%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x257mm 19.1-inch   | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch  | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1        | 0.74%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.74%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.74%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 1        | 0.74%   |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                   | 1        | 0.74%   |
| Samsung Electronics LCD Monitor C27F390 1920x1080                     | 1        | 0.74%   |
| Proview MA782KC PEB030E 1280x1024 338x270mm 17.0-inch                 | 1        | 0.74%   |
| Plain Tree Systems FULL HDTV PTS00EC 1920x1080 520x290mm 23.4-inch    | 1        | 0.74%   |
| Philips HDMI PHLC194 1920x1080 700x390mm 31.5-inch                    | 1        | 0.74%   |
| Philips 271P4 PHL08C3 1920x1080 597x336mm 27.0-inch                   | 1        | 0.74%   |
| Philips 190B PHL081A 1280x1024 376x301mm 19.0-inch                    | 1        | 0.74%   |
| Philips 170C5 PHLC00B 1280x1024 338x270mm 17.0-inch                   | 1        | 0.74%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 340x270mm 17.1-inch         | 1        | 0.74%   |
| MOT MotoAttach MOT3DC4 1366x768 260x140mm 11.6-inch                   | 1        | 0.74%   |
| Lite-On GC150AT/ATA LTN020E 1024x768 304x228mm 15.0-inch              | 1        | 0.74%   |
| LG Electronics LCD Monitor W2220                                      | 1        | 0.74%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 0.74%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 1        | 0.74%   |
| Lenovo LEN-M93z-B LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 0.74%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1        | 0.74%   |
| Lenovo LCD Monitor LEN0BD0 1920x1080 510x290mm 23.1-inch              | 1        | 0.74%   |
| Lenovo Group Limited LCD Monitor LEN L24q-30 1920x1200                | 1        | 0.74%   |
| IOD LCD-A153G IOD0F46 1024x768 304x228mm 15.0-inch                    | 1        | 0.74%   |
| IOD EX-LD2381D IOD180C 1920x1080 530x300mm 24.0-inch                  | 1        | 0.74%   |
| IOD DIOS-MF241X IOD180A 1920x1080 530x300mm 24.0-inch                 | 1        | 0.74%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                 | 1        | 0.74%   |
| Iiyama PL2792H IVM6638 1920x1080 598x336mm 27.0-inch                  | 1        | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 29.55%  |
| 1280x1024 (SXGA)   | 25       | 18.94%  |
| 1680x1050 (WSXGA+) | 16       | 12.12%  |
| 1366x768 (WXGA)    | 10       | 7.58%   |
| 1440x900 (WXGA+)   | 9        | 6.82%   |
| 2560x1440 (QHD)    | 8        | 6.06%   |
| 1024x768 (XGA)     | 6        | 4.55%   |
| 3840x2160 (4K)     | 3        | 2.27%   |
| 1600x900 (HD+)     | 3        | 2.27%   |
| 3440x1440          | 2        | 1.52%   |
| 2560x1080          | 2        | 1.52%   |
| 1280x800 (WXGA)    | 2        | 1.52%   |
| 3600x1200          | 1        | 0.76%   |
| 2560x1600          | 1        | 0.76%   |
| 2288x1287          | 1        | 0.76%   |
| 1920x1200 (WUXGA)  | 1        | 0.76%   |
| 1600x1200          | 1        | 0.76%   |
| 1360x768           | 1        | 0.76%   |
| Unknown            | 1        | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 18       | 13.64%  |
| 19      | 13       | 9.85%   |
| 27      | 11       | 8.33%   |
| 23      | 11       | 8.33%   |
| 21      | 11       | 8.33%   |
| 24      | 10       | 7.58%   |
| 22      | 10       | 7.58%   |
| Unknown | 10       | 7.58%   |
| 20      | 8        | 6.06%   |
| 15      | 7        | 5.3%    |
| 18      | 6        | 4.55%   |
| 34      | 3        | 2.27%   |
| 41      | 2        | 1.52%   |
| 39      | 2        | 1.52%   |
| 31      | 2        | 1.52%   |
| 72      | 1        | 0.76%   |
| 47      | 1        | 0.76%   |
| 38      | 1        | 0.76%   |
| 32      | 1        | 0.76%   |
| 29      | 1        | 0.76%   |
| 14      | 1        | 0.76%   |
| 11      | 1        | 0.76%   |
| 7       | 1        | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 39       | 30%     |
| 501-600     | 31       | 23.85%  |
| 301-350     | 24       | 18.46%  |
| Unknown     | 10       | 7.69%   |
| 351-400     | 9        | 6.92%   |
| 701-800     | 4        | 3.08%   |
| 601-700     | 4        | 3.08%   |
| 801-900     | 3        | 2.31%   |
| 901-1000    | 2        | 1.54%   |
| 201-300     | 1        | 0.77%   |
| 1501-2000   | 1        | 0.77%   |
| 101-200     | 1        | 0.77%   |
| 1001-1500   | 1        | 0.77%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 59       | 46.83%  |
| 5/4     | 23       | 18.25%  |
| 16/10   | 22       | 17.46%  |
| Unknown | 9        | 7.14%   |
| 4/3     | 6        | 4.76%   |
| 21/9    | 4        | 3.17%   |
| 6/5     | 2        | 1.59%   |
| 3/2     | 1        | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 28.46%  |
| 151-200        | 24       | 18.46%  |
| 141-150        | 21       | 16.15%  |
| 301-350        | 12       | 9.23%   |
| Unknown        | 10       | 7.69%   |
| 101-110        | 7        | 5.38%   |
| 351-500        | 6        | 4.62%   |
| 501-1000       | 6        | 4.62%   |
| 251-300        | 2        | 1.54%   |
| More than 1000 | 1        | 0.77%   |
| 81-90          | 1        | 0.77%   |
| 51-60          | 1        | 0.77%   |
| 1-40           | 1        | 0.77%   |
| 131-140        | 1        | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 87       | 69.05%  |
| 101-120 | 16       | 12.7%   |
| Unknown | 10       | 7.94%   |
| 121-160 | 8        | 6.35%   |
| 1-50    | 3        | 2.38%   |
| 161-240 | 2        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 87.88%  |
| 2     | 10       | 7.58%   |
| 0     | 4        | 3.03%   |
| 4     | 1        | 0.76%   |
| 3     | 1        | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 76       | 41.3%   |
| Intel                    | 43       | 23.37%  |
| Nvidia                   | 14       | 7.61%   |
| Ralink Technology        | 11       | 5.98%   |
| Qualcomm Atheros         | 11       | 5.98%   |
| Ralink                   | 5        | 2.72%   |
| Broadcom                 | 4        | 2.17%   |
| Marvell Technology Group | 3        | 1.63%   |
| TP-Link                  | 2        | 1.09%   |
| Samsung Electronics      | 2        | 1.09%   |
| Broadcom Limited         | 2        | 1.09%   |
| ZyXEL Communications     | 1        | 0.54%   |
| VIA Technologies         | 1        | 0.54%   |
| U-Blox                   | 1        | 0.54%   |
| Sitecom Europe           | 1        | 0.54%   |
| NetGear                  | 1        | 0.54%   |
| Logitec                  | 1        | 0.54%   |
| Huawei Technologies      | 1        | 0.54%   |
| Belkin Components        | 1        | 0.54%   |
| ASIX Electronics         | 1        | 0.54%   |
| Aquantia                 | 1        | 0.54%   |
| ADMtek                   | 1        | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56       | 28%     |
| Nvidia MCP61 Ethernet                                             | 8        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2%      |
| Ralink RT5572 Wireless Adapter                                    | 3        | 1.5%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.5%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.5%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1%      |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 1%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1%      |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 1%      |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1%      |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1%      |
| Intel Wireless-AC 9260                                            | 2        | 1%      |
| Intel Wireless 7260                                               | 2        | 1%      |
| Intel Ethernet Connection I217-V                                  | 2        | 1%      |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1%      |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.5%    |
| U-Blox GNSS receiver                                              | 1        | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.5%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.5%    |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.5%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.5%    |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.5%    |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.5%    |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.5%    |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.5%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.5%    |
| Nvidia MCP73 Ethernet                                             | 1        | 0.5%    |
| Nvidia MCP67 Ethernet                                             | 1        | 0.5%    |
| Nvidia MCP55 Ethernet                                             | 1        | 0.5%    |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 23.64%  |
| Ralink Technology     | 11       | 20%     |
| Intel                 | 10       | 18.18%  |
| Qualcomm Atheros      | 8        | 14.55%  |
| Ralink                | 5        | 9.09%   |
| TP-Link               | 2        | 3.64%   |
| ZyXEL Communications  | 1        | 1.82%   |
| Sitecom Europe        | 1        | 1.82%   |
| NetGear               | 1        | 1.82%   |
| Logitec               | 1        | 1.82%   |
| Broadcom              | 1        | 1.82%   |
| Belkin Components     | 1        | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                    | 5        | 9.09%   |
| Ralink RT5572 Wireless Adapter                                                         | 3        | 5.45%   |
| Ralink MT7601U Wireless Adapter                                                        | 3        | 5.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                             | 3        | 5.45%   |
| Realtek RTL8187 Wireless Adapter                                                       | 2        | 3.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                  | 2        | 3.64%   |
| Ralink RT2561/RT61 802.11g PCI                                                         | 2        | 3.64%   |
| Intel Wireless-AC 9260                                                                 | 2        | 3.64%   |
| Intel Wireless 7260                                                                    | 2        | 3.64%   |
| ZyXEL ZyAIR G-202 802.11bg                                                             | 1        | 1.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                            | 1        | 1.82%   |
| TP-Link 802.11ac WLAN Adapter                                                          | 1        | 1.82%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                        | 1        | 1.82%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                        | 1        | 1.82%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                 | 1        | 1.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 1        | 1.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 1        | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 1        | 1.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                | 1        | 1.82%   |
| Ralink RT5372 Wireless Adapter                                                         | 1        | 1.82%   |
| Ralink RT5370 Wireless Adapter                                                         | 1        | 1.82%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                  | 1        | 1.82%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                            | 1        | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                              | 1        | 1.82%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                              | 1        | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                       | 1        | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                       | 1        | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                         | 1        | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 1        | 1.82%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                       | 1        | 1.82%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                            | 1        | 1.82%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                                              | 1        | 1.82%   |
| Intel Wireless 7265                                                                    | 1        | 1.82%   |
| Intel Wireless 3165                                                                    | 1        | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                 | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                       | 1        | 1.82%   |
| Intel Centrino Advanced-N 6235                                                         | 1        | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                           | 1        | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                    | 1        | 1.82%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 68       | 49.64%  |
| Intel                    | 35       | 25.55%  |
| Nvidia                   | 14       | 10.22%  |
| Qualcomm Atheros         | 4        | 2.92%   |
| Broadcom                 | 4        | 2.92%   |
| Marvell Technology Group | 3        | 2.19%   |
| Samsung Electronics      | 2        | 1.46%   |
| Broadcom Limited         | 2        | 1.46%   |
| VIA Technologies         | 1        | 0.73%   |
| Huawei Technologies      | 1        | 0.73%   |
| ASIX Electronics         | 1        | 0.73%   |
| Aquantia                 | 1        | 0.73%   |
| ADMtek                   | 1        | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56       | 38.89%  |
| Nvidia MCP61 Ethernet                                             | 8        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.08%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.39%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.39%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.39%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.39%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.69%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.69%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.69%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.69%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.69%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.69%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.69%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.69%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.69%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.69%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.69%   |
| Huawei MAR-LX1A                                                   | 1        | 0.69%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.69%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.69%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.69%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.69%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.69%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.69%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 70.43%  |
| WiFi     | 54       | 29.03%  |
| Modem    | 1        | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 108      | 78.26%  |
| WiFi     | 30       | 21.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 74.24%  |
| 2     | 29       | 21.97%  |
| 3     | 4        | 3.03%   |
| 0     | 1        | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 108      | 81.2%   |
| Yes  | 25       | 18.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 40.91%  |
| Cambridge Silicon Radio | 7        | 31.82%  |
| Broadcom                | 3        | 13.64%  |
| Ralink                  | 1        | 4.55%   |
| Lite-On Technology      | 1        | 4.55%   |
| Hewlett-Packard         | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 31.82%  |
| Intel Bluetooth wireless interface                  | 4        | 18.18%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 9.09%   |
| Ralink RT3290 Bluetooth                             | 1        | 4.55%   |
| Lite-On Bluetooth Device                            | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 4.55%   |
| Broadcom Bluetooth Device                           | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 78       | 41.71%  |
| Nvidia                   | 47       | 25.13%  |
| AMD                      | 44       | 23.53%  |
| Creative Labs            | 4        | 2.14%   |
| C-Media Electronics      | 4        | 2.14%   |
| XMOS                     | 2        | 1.07%   |
| VIA Technologies         | 1        | 0.53%   |
| Unknown                  | 1        | 0.53%   |
| Logitech                 | 1        | 0.53%   |
| GN Netcom                | 1        | 0.53%   |
| Focusrite-Novation       | 1        | 0.53%   |
| Creative Technology      | 1        | 0.53%   |
| ASUSTek Computer         | 1        | 0.53%   |
| Asahi Kasei Microsystems | 1        | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                 | 11       | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller              | 11       | 5.14%   |
| Nvidia High Definition Audio Controller                                                 | 10       | 4.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                     | 9        | 4.21%   |
| Nvidia MCP61 High Definition Audio                                                      | 8        | 3.74%   |
| AMD FCH Azalia Controller                                                               | 8        | 3.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                        | 7        | 3.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                            | 7        | 3.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                          | 6        | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                     | 6        | 2.8%    |
| AMD Starship/Matisse HD Audio Controller                                                | 6        | 2.8%    |
| Nvidia GP107GL High Definition Audio Controller                                         | 5        | 2.34%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                     | 5        | 2.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                          | 5        | 2.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                           | 4        | 1.87%   |
| Intel 200 Series PCH HD Audio                                                           | 4        | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                         | 4        | 1.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                 | 4        | 1.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                  | 4        | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                   | 3        | 1.4%    |
| Nvidia GK107 HDMI Audio Controller                                                      | 3        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                                       | 3        | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                | 3        | 1.4%    |
| AMD Trinity HDMI Audio Controller                                                       | 3        | 1.4%    |
| AMD Family 17h/19h HD Audio Controller                                                  | 3        | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                     | 3        | 1.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]       | 3        | 1.4%    |
| XMOS Mayfield Audio                                                                     | 2        | 0.93%   |
| Nvidia GK106 HDMI Audio Controller                                                      | 2        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                           | 2        | 0.93%   |
| Nvidia CK804 AC'97 Audio Controller                                                     | 2        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller              | 2        | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                        | 2        | 0.93%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                              | 2        | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                        | 2        | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                | 2        | 0.93%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                          | 2        | 0.93%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                      | 1        | 0.47%   |
| Unknown Realtek USB Audio Rear                                                          | 1        | 0.47%   |
| Unknown Realtek USB Audio Front                                                         | 1        | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                          | 1        | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                        | 1        | 0.47%   |
| Nvidia TU102 High Definition Audio Controller                                           | 1        | 0.47%   |
| Nvidia MCP73 High Definition Audio                                                      | 1        | 0.47%   |
| Nvidia MCP67 High Definition Audio                                                      | 1        | 0.47%   |
| Nvidia MCP51 High Definition Audio                                                      | 1        | 0.47%   |
| Nvidia GM206 High Definition Audio Controller                                           | 1        | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                                           | 1        | 0.47%   |
| Nvidia GK104 HDMI Audio Controller                                                      | 1        | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                      | 1        | 0.47%   |
| Nvidia GF116 High Definition Audio Controller                                           | 1        | 0.47%   |
| Logitech EasyCall Speakerphone                                                          | 1        | 0.47%   |
| Intel Comet Lake PCH-V cAVS                                                             | 1        | 0.47%   |
| Intel Comet Lake PCH cAVS                                                               | 1        | 0.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                            | 1        | 0.47%   |
| Intel C610/X99 series chipset HD Audio Controller                                       | 1        | 0.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                          | 1        | 0.47%   |
| Intel Audio device                                                                      | 1        | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio | 1        | 0.47%   |
| GN Netcom Jabra EVOLVE Link MS                                                          | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 18       | 18.37%  |
| Samsung Electronics | 18       | 18.37%  |
| SK Hynix            | 16       | 16.33%  |
| Kingston            | 9        | 9.18%   |
| G.Skill             | 6        | 6.12%   |
| Micron Technology   | 5        | 5.1%    |
| Crucial             | 5        | 5.1%    |
| Corsair             | 5        | 5.1%    |
| Nanya Technology    | 3        | 3.06%   |
| TIMETEC             | 2        | 2.04%   |
| Patriot             | 2        | 2.04%   |
| Elpida              | 2        | 2.04%   |
| Unknown (ABCD)      | 1        | 1.02%   |
| Unifosa             | 1        | 1.02%   |
| Team                | 1        | 1.02%   |
| Ramaxel Technology  | 1        | 1.02%   |
| Qimonda             | 1        | 1.02%   |
| e2e4                | 1        | 1.02%   |
| 48spaces            | 1        | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 4        | 3.74%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 2        | 1.87%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 2        | 1.87%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 2        | 1.87%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 2        | 1.87%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                   | 1        | 0.93%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1        | 0.93%   |
| Unknown RAM Module 512MB DIMM 333MT/s                          | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM SDRAM                           | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1        | 0.93%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 1        | 0.93%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1        | 0.93%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 0.93%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1        | 0.93%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 1        | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.93%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 1        | 0.93%   |
| TIMETEC RAM UD3-1600 8GB DIMM DDR3 1600MT/s                    | 1        | 0.93%   |
| TIMETEC RAM SD3-1600 8192MB SODIMM DDR3 1600MT/s               | 1        | 0.93%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s          | 1        | 0.93%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2133MT/s                  | 1        | 0.93%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1066MT/s                  | 1        | 0.93%   |
| SK Hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s         | 1        | 0.93%   |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s       | 1        | 0.93%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.93%   |
| SK Hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s        | 1        | 0.93%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.93%   |
| SK Hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s        | 1        | 0.93%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 1        | 0.93%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1        | 0.93%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 0.93%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s        | 1        | 0.93%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s          | 1        | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1        | 0.93%   |
| Samsung RAM M471B1G73AH0-CK0 4096MB SODIMM DDR3 1333MT/s       | 1        | 0.93%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s         | 1        | 0.93%   |
| Samsung RAM M4 70T2864FB3-CF7 1024MB SODIMM DDR2 667MT/s       | 1        | 0.93%   |
| Samsung RAM M393B1K70DH0-CK0 8GB DIMM DDR3 1600MT/s            | 1        | 0.93%   |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s           | 1        | 0.93%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s           | 1        | 0.93%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s         | 1        | 0.93%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM 1867MT/s              | 1        | 0.93%   |
| Samsung RAM M378B5273BH1-CF8 4096MB DIMM 1066MT/s              | 1        | 0.93%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s            | 1        | 0.93%   |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s         | 1        | 0.93%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 1        | 0.93%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 1        | 0.93%   |
| Samsung RAM M3 78T2863RZS-CE6 1024MB DIMM DDR2 667MT/s         | 1        | 0.93%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM SDRAM 1639MT/s          | 1        | 0.93%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s         | 1        | 0.93%   |
| Samsung RAM M3 12L2920CZ3-CCC 1024MB DIMM DDR 400MT/s          | 1        | 0.93%   |
| Ramaxel RAM RML1040EG38D6F-533 512MB DIMM DDR2 533MT/s         | 1        | 0.93%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s               | 1        | 0.93%   |
| Patriot RAM PSD44G213341 4096MB DIMM DDR4 3000MT/s             | 1        | 0.93%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s             | 1        | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 37       | 41.57%  |
| DDR4    | 18       | 20.22%  |
| DDR2    | 15       | 16.85%  |
| SDRAM   | 9        | 10.11%  |
| Unknown | 7        | 7.87%   |
| DDR     | 2        | 2.25%   |
| LPDDR4  | 1        | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 73       | 86.9%   |
| SODIMM | 11       | 13.1%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 30       | 32.97%  |
| 8192  | 21       | 23.08%  |
| 4096  | 20       | 21.98%  |
| 1024  | 8        | 8.79%   |
| 16384 | 6        | 6.59%   |
| 512   | 3        | 3.3%    |
| 32768 | 2        | 2.2%    |
| 65536 | 1        | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 23.71%  |
| 1333    | 11       | 11.34%  |
| 800     | 9        | 9.28%   |
| 2133    | 6        | 6.19%   |
| 667     | 5        | 5.15%   |
| 400     | 5        | 5.15%   |
| 3200    | 4        | 4.12%   |
| 2400    | 4        | 4.12%   |
| Unknown | 4        | 4.12%   |
| 2667    | 3        | 3.09%   |
| 2048    | 3        | 3.09%   |
| 1866    | 3        | 3.09%   |
| 1066    | 3        | 3.09%   |
| 3600    | 2        | 2.06%   |
| 3000    | 2        | 2.06%   |
| 1867    | 2        | 2.06%   |
| 49926   | 1        | 1.03%   |
| 3466    | 1        | 1.03%   |
| 3066    | 1        | 1.03%   |
| 2733    | 1        | 1.03%   |
| 1639    | 1        | 1.03%   |
| 1334    | 1        | 1.03%   |
| 533     | 1        | 1.03%   |
| 333     | 1        | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP DeskJet 3630 series | 1        | 100%    |

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
| Logitech                      | 4        | 22.22%  |
| Generalplus Technology        | 2        | 11.11%  |
| Chicony Electronics           | 2        | 11.11%  |
| Z-Star Microelectronics       | 1        | 5.56%   |
| SunplusIT                     | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Samsung Electronics           | 1        | 5.56%   |
| Microsoft                     | 1        | 5.56%   |
| KYE Systems (Mouse Systems)   | 1        | 5.56%   |
| Guillemot                     | 1        | 5.56%   |
| Genesys Logic                 | 1        | 5.56%   |
| ARC International             | 1        | 5.56%   |
| Acer                          | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 2        | 11.11%  |
| Generalplus CAMERA - UVC                  | 2        | 11.11%  |
| Z-Star Sirius USB2.0 Camera               | 1        | 5.56%   |
| SunplusIT USB 2.0 Camera                  | 1        | 5.56%   |
| Sunplus Canyon CNS-CWC5 Webcam            | 1        | 5.56%   |
| Samsung Galaxy A5 (MTP)                   | 1        | 5.56%   |
| Microsoft LifeCam HD-3000                 | 1        | 5.56%   |
| Logitech QuickCam Zoom                    | 1        | 5.56%   |
| Logitech HD Webcam C525                   | 1        | 5.56%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 5.56%   |
| Guillemot Hercules HD Sunset              | 1        | 5.56%   |
| Genesys Logic Camera                      | 1        | 5.56%   |
| Chicony CNF7042                           | 1        | 5.56%   |
| Chicony ASUS USB2.0 Webcam                | 1        | 5.56%   |
| ARC International Camera                  | 1        | 5.56%   |
| Acer Integrated Camera                    | 1        | 5.56%   |

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
| 0     | 112      | 84.85%  |
| 1     | 19       | 14.39%  |
| 2     | 1        | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 26.32%  |
| Net/wireless             | 3        | 15.79%  |
| Communication controller | 3        | 15.79%  |
| Unassigned class         | 2        | 10.53%  |
| Sound                    | 2        | 10.53%  |
| Net/ethernet             | 1        | 5.26%   |
| Multimedia controller    | 1        | 5.26%   |
| Dvb card                 | 1        | 5.26%   |
| Bluetooth                | 1        | 5.26%   |

