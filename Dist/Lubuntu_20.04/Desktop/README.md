Lubuntu 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MSI           | AMETHYST-M                  | [e6c4f7b650](https://linux-hardware.org/?probe=e6c4f7b650) | Aug 30, 2021 |
| ASRock        | FM2A68M-DG3+                | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| HP            | 8299                        | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| Huanan        | X99-TF V2.0                 | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| ASUSTek       | H110M-A/M.2                 | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
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
| Packard Be... | imedia S1350                | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| ASRock        | FM2A88M Extreme4+           | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
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
| MSI           | AMETHYST-M                  | [057c04b2ae](https://linux-hardware.org/?probe=057c04b2ae) | Jan 11, 2021 |
| ASUSTek       | P8Z68-V LX                  | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | Board                       | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Dell          | 0WG864                      | [f45926d7a7](https://linux-hardware.org/?probe=f45926d7a7) | Dec 11, 2020 |
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
| ASRock        | 4Core1600-GLAN              | [e6edfc8360](https://linux-hardware.org/?probe=e6edfc8360) | Nov 06, 2020 |
| ASRock        | 4Core1600-GLAN              | [2139a80238](https://linux-hardware.org/?probe=2139a80238) | Nov 03, 2020 |
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
| Lenovo        | Board                       | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Lenovo        | SDK0E50515 STD              | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| IBM           | Board                       | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
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
| 5.4.0-52-generic      | 8        | 6.25%   |
| 5.4.0-42-generic      | 8        | 6.25%   |
| 5.8.0-50-generic      | 6        | 4.69%   |
| 5.11.0-27-generic     | 6        | 4.69%   |
| 5.4.0-54-generic      | 5        | 3.91%   |
| 5.13.0-28-generic     | 5        | 3.91%   |
| 5.4.0-67-generic      | 4        | 3.13%   |
| 5.4.0-40-generic      | 4        | 3.13%   |
| 5.4.0-29-generic      | 4        | 3.13%   |
| 5.4.0-77-generic      | 3        | 2.34%   |
| 5.4.0-73-generic      | 3        | 2.34%   |
| 5.4.0-48-generic      | 3        | 2.34%   |
| 5.4.0-47-generic      | 3        | 2.34%   |
| 5.4.0-37-generic      | 3        | 2.34%   |
| 5.4.0-33-generic      | 3        | 2.34%   |
| 5.4.0-26-generic      | 3        | 2.34%   |
| 5.8.0-63-generic      | 2        | 1.56%   |
| 5.8.0-59-generic      | 2        | 1.56%   |
| 5.8.0-53-generic      | 2        | 1.56%   |
| 5.8.0-45-generic      | 2        | 1.56%   |
| 5.8.0-41-generic      | 2        | 1.56%   |
| 5.4.0-90-generic      | 2        | 1.56%   |
| 5.4.0-72-generic      | 2        | 1.56%   |
| 5.4.0-66-generic      | 2        | 1.56%   |
| 5.4.0-60-generic      | 2        | 1.56%   |
| 5.13.0-27-generic     | 2        | 1.56%   |
| 5.11.0-43-generic     | 2        | 1.56%   |
| 5.11.0-38-generic     | 2        | 1.56%   |
| 5.11.0-34-generic     | 2        | 1.56%   |
| 5.8.0-7630-generic    | 1        | 0.78%   |
| 5.8.0-55-generic      | 1        | 0.78%   |
| 5.8.0-48-generic      | 1        | 0.78%   |
| 5.8.0-43-generic      | 1        | 0.78%   |
| 5.8.0-29-lowlatency   | 1        | 0.78%   |
| 5.6.15-050615-generic | 1        | 0.78%   |
| 5.6.0-1052-oem        | 1        | 0.78%   |
| 5.4.30-dli            | 1        | 0.78%   |
| 5.4.0-99-generic      | 1        | 0.78%   |
| 5.4.0-96-generic      | 1        | 0.78%   |
| 5.4.0-91-generic      | 1        | 0.78%   |
| 5.4.0-89-generic      | 1        | 0.78%   |
| 5.4.0-88-generic      | 1        | 0.78%   |
| 5.4.0-81-generic      | 1        | 0.78%   |
| 5.4.0-75-generic      | 1        | 0.78%   |
| 5.4.0-70-lowlatency   | 1        | 0.78%   |
| 5.4.0-65-generic      | 1        | 0.78%   |
| 5.4.0-64-generic      | 1        | 0.78%   |
| 5.4.0-59-generic      | 1        | 0.78%   |
| 5.4.0-58-generic      | 1        | 0.78%   |
| 5.4.0-53-generic      | 1        | 0.78%   |
| 5.4.0-31-generic      | 1        | 0.78%   |
| 5.3.18-dli            | 1        | 0.78%   |
| 5.16.5-051605-generic | 1        | 0.78%   |
| 5.14.0-051400-generic | 1        | 0.78%   |
| 5.13.0-30-generic     | 1        | 0.78%   |
| 5.13.0-1008-intel     | 1        | 0.78%   |
| 5.11.0-46-generic     | 1        | 0.78%   |
| 5.11.0-40-generic     | 1        | 0.78%   |
| 5.11.0-37-generic     | 1        | 0.78%   |
| 5.11.0-36-generic     | 1        | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 70       | 57.38%  |
| 5.8.0   | 21       | 17.21%  |
| 5.11.0  | 16       | 13.11%  |
| 5.13.0  | 9        | 7.38%   |
| 5.6.15  | 1        | 0.82%   |
| 5.6.0   | 1        | 0.82%   |
| 5.4.30  | 1        | 0.82%   |
| 5.3.18  | 1        | 0.82%   |
| 5.16.5  | 1        | 0.82%   |
| 5.14.0  | 1        | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 71       | 58.2%   |
| 5.8     | 21       | 17.21%  |
| 5.11    | 16       | 13.11%  |
| 5.13    | 9        | 7.38%   |
| 5.6     | 2        | 1.64%   |
| 5.3     | 1        | 0.82%   |
| 5.16    | 1        | 0.82%   |
| 5.14    | 1        | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 121      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 114      | 94.21%  |
| LXDE       | 3        | 2.48%   |
| GNOME      | 2        | 1.65%   |
| X-Cinnamon | 1        | 0.83%   |
| i3         | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 114      | 94.21%  |
| Tty     | 6        | 4.96%   |
| Unknown | 1        | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 62       | 50%     |
| Unknown | 39       | 31.45%  |
| GDM     | 8        | 6.45%   |
| TDM     | 7        | 5.65%   |
| LightDM | 6        | 4.84%   |
| LXDM    | 1        | 0.81%   |
| GDM3    | 1        | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 30       | 24.79%  |
| fr_FR   | 17       | 14.05%  |
| pt_BR   | 9        | 7.44%   |
| it_IT   | 9        | 7.44%   |
| de_DE   | 9        | 7.44%   |
| C       | 7        | 5.79%   |
| ru_RU   | 5        | 4.13%   |
| ja_JP   | 4        | 3.31%   |
| en_GB   | 4        | 3.31%   |
| en_AU   | 4        | 3.31%   |
| hu_HU   | 2        | 1.65%   |
| es_ES   | 2        | 1.65%   |
| en_ZA   | 2        | 1.65%   |
| en_CA   | 2        | 1.65%   |
| cs_CZ   | 2        | 1.65%   |
| Unknown | 2        | 1.65%   |
| sv_SE   | 1        | 0.83%   |
| nl_NL   | 1        | 0.83%   |
| fi_FI   | 1        | 0.83%   |
| es_PE   | 1        | 0.83%   |
| es_MX   | 1        | 0.83%   |
| es_CR   | 1        | 0.83%   |
| es_CO   | 1        | 0.83%   |
| en_SG   | 1        | 0.83%   |
| en_NZ   | 1        | 0.83%   |
| el_GR   | 1        | 0.83%   |
| de_CH   | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 79       | 65.29%  |
| EFI  | 42       | 34.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 111      | 91.74%  |
| Overlay | 6        | 4.96%   |
| Xfs     | 2        | 1.65%   |
| F2fs    | 1        | 0.83%   |
| Btrfs   | 1        | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 36.89%  |
| MBR     | 42       | 34.43%  |
| GPT     | 35       | 28.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 84.3%   |
| Yes       | 19       | 15.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 66.94%  |
| Yes       | 40       | 33.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 17.36%  |
| Hewlett-Packard     | 15       | 12.4%   |
| Gigabyte Technology | 14       | 11.57%  |
| Dell                | 12       | 9.92%   |
| MSI                 | 11       | 9.09%   |
| ASRock              | 11       | 9.09%   |
| Lenovo              | 7        | 5.79%   |
| Intel               | 5        | 4.13%   |
| Pegatron            | 4        | 3.31%   |
| Acer                | 4        | 3.31%   |
| AAEON               | 3        | 2.48%   |
| Positivo            | 2        | 1.65%   |
| Foxconn             | 2        | 1.65%   |
| Biostar             | 2        | 1.65%   |
| ZOTAC               | 1        | 0.83%   |
| Packard Bell        | 1        | 0.83%   |
| IBM                 | 1        | 0.83%   |
| Huanan              | 1        | 0.83%   |
| HARDKERNEL          | 1        | 0.83%   |
| Fujitsu Siemens     | 1        | 0.83%   |
| AMI                 | 1        | 0.83%   |
| Unknown             | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| AAEON MF-001                        | 3        | 2.48%   |
| MSI MS-7B89                         | 2        | 1.65%   |
| HP Compaq 6000 Pro SFF PC           | 2        | 1.65%   |
| Dell OptiPlex 790                   | 2        | 1.65%   |
| ASRock N68-VS3 UCC                  | 2        | 1.65%   |
| ZOTAC NM10                          | 1        | 0.83%   |
| Positivo POS-MI945AA                | 1        | 0.83%   |
| Positivo POS-EIH61CE                | 1        | 0.83%   |
| Pegatron WE216AA-ABF CQ5335FR       | 1        | 0.83%   |
| Pegatron NC689AA-ABA s3700y         | 1        | 0.83%   |
| Pegatron FL308AA-ABD IQ512de        | 1        | 0.83%   |
| Pegatron AY652AA-ABA s5310y         | 1        | 0.83%   |
| Packard Bell imedia S1350           | 1        | 0.83%   |
| MSI MS-7C37                         | 1        | 0.83%   |
| MSI MS-7B86                         | 1        | 0.83%   |
| MSI MS-7994                         | 1        | 0.83%   |
| MSI MS-7846                         | 1        | 0.83%   |
| MSI MS-7680                         | 1        | 0.83%   |
| MSI MS-7592                         | 1        | 0.83%   |
| MSI MS-7309                         | 1        | 0.83%   |
| MSI ER883AA-ABA M7470N              | 1        | 0.83%   |
| MSI Compaq dx2200 MT                | 1        | 0.83%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 0.83%   |
| Lenovo ThinkCentre M93z 10AD002DMZ  | 1        | 0.83%   |
| Lenovo ThinkCentre M73 10AXS0HN00   | 1        | 0.83%   |
| Lenovo ThinkCentre M58p 7220W21     | 1        | 0.83%   |
| Lenovo ThinkCentre M58p 6136A66     | 1        | 0.83%   |
| Lenovo H50-50 90B60081IX            | 1        | 0.83%   |
| Lenovo H50-30g 90AS0002BR           | 1        | 0.83%   |
| Intel STK1AW32SC                    | 1        | 0.83%   |
| Intel H55                           | 1        | 0.83%   |
| Intel DN2800MT AAG23738-801         | 1        | 0.83%   |
| Intel DG31PR AAD97573-302           | 1        | 0.83%   |
| Intel ChiefRiver                    | 1        | 0.83%   |
| IBM eServer x3105 -[434722J]-       | 1        | 0.83%   |
| Huanan X99-TF                       | 1        | 0.83%   |
| HP Z230 Tower Workstation           | 1        | 0.83%   |
| HP xw9400 Workstation               | 1        | 0.83%   |
| HP xw9300 Workstation               | 1        | 0.83%   |
| HP t620 Quad Core TC                | 1        | 0.83%   |
| HP t620 Dual Core TC                | 1        | 0.83%   |
| HP ProDesk 600 G1 DM                | 1        | 0.83%   |
| HP EliteDesk 800 G3 SFF             | 1        | 0.83%   |
| HP Compaq Elite 8300 CMT            | 1        | 0.83%   |
| HP Compaq dc7800 Small Form Factor  | 1        | 0.83%   |
| HP Compaq dc7600 Small Form Factor  | 1        | 0.83%   |
| HP Compaq dc5800 Microtower         | 1        | 0.83%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 0.83%   |
| HP 500-203a                         | 1        | 0.83%   |
| HARDKERNEL ODROID-H2                | 1        | 0.83%   |
| Gigabyte Z370P D3                   | 1        | 0.83%   |
| Gigabyte X570 GAMING X              | 1        | 0.83%   |
| Gigabyte K8M800-8237                | 1        | 0.83%   |
| Gigabyte H81M-DS2                   | 1        | 0.83%   |
| Gigabyte H61M-DS2H                  | 1        | 0.83%   |
| Gigabyte GA-MA69G-S3H               | 1        | 0.83%   |
| Gigabyte GA-870A-UD3                | 1        | 0.83%   |
| Gigabyte G41M-Combo                 | 1        | 0.83%   |
| Gigabyte F2A88XM-HD3                | 1        | 0.83%   |
| Gigabyte B450M S2H                  | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 7        | 5.79%   |
| Dell OptiPlex           | 5        | 4.13%   |
| Lenovo ThinkCentre      | 4        | 3.31%   |
| Acer Aspire             | 4        | 3.31%   |
| AAEON MF-001            | 3        | 2.48%   |
| MSI MS-7B89             | 2        | 1.65%   |
| HP t620                 | 2        | 1.65%   |
| Gigabyte B450M          | 2        | 1.65%   |
| ASRock N68-VS3          | 2        | 1.65%   |
| ZOTAC NM10              | 1        | 0.83%   |
| Positivo POS-MI945AA    | 1        | 0.83%   |
| Positivo POS-EIH61CE    | 1        | 0.83%   |
| Pegatron WE216AA-ABF    | 1        | 0.83%   |
| Pegatron NC689AA-ABA    | 1        | 0.83%   |
| Pegatron FL308AA-ABD    | 1        | 0.83%   |
| Pegatron AY652AA-ABA    | 1        | 0.83%   |
| Packard Bell imedia     | 1        | 0.83%   |
| MSI MS-7C37             | 1        | 0.83%   |
| MSI MS-7B86             | 1        | 0.83%   |
| MSI MS-7994             | 1        | 0.83%   |
| MSI MS-7846             | 1        | 0.83%   |
| MSI MS-7680             | 1        | 0.83%   |
| MSI MS-7592             | 1        | 0.83%   |
| MSI MS-7309             | 1        | 0.83%   |
| MSI ER883AA-ABA         | 1        | 0.83%   |
| MSI Compaq              | 1        | 0.83%   |
| Lenovo ThinkStation     | 1        | 0.83%   |
| Lenovo H50-50           | 1        | 0.83%   |
| Lenovo H50-30g          | 1        | 0.83%   |
| Intel STK1AW32SC        | 1        | 0.83%   |
| Intel H55               | 1        | 0.83%   |
| Intel DN2800MT          | 1        | 0.83%   |
| Intel DG31PR            | 1        | 0.83%   |
| Intel ChiefRiver        | 1        | 0.83%   |
| IBM eServer             | 1        | 0.83%   |
| Huanan X99-TF           | 1        | 0.83%   |
| HP Z230                 | 1        | 0.83%   |
| HP xw9400               | 1        | 0.83%   |
| HP xw9300               | 1        | 0.83%   |
| HP ProDesk              | 1        | 0.83%   |
| HP EliteDesk            | 1        | 0.83%   |
| HP 500-203a             | 1        | 0.83%   |
| HARDKERNEL ODROID-H2    | 1        | 0.83%   |
| Gigabyte Z370P          | 1        | 0.83%   |
| Gigabyte X570           | 1        | 0.83%   |
| Gigabyte K8M800-8237    | 1        | 0.83%   |
| Gigabyte H81M-DS2       | 1        | 0.83%   |
| Gigabyte H61M-DS2H      | 1        | 0.83%   |
| Gigabyte GA-MA69G-S3H   | 1        | 0.83%   |
| Gigabyte GA-870A-UD3    | 1        | 0.83%   |
| Gigabyte G41M-Combo     | 1        | 0.83%   |
| Gigabyte F2A88XM-HD3    | 1        | 0.83%   |
| Gigabyte B250M-D3H      | 1        | 0.83%   |
| Gigabyte A520I          | 1        | 0.83%   |
| Gigabyte 965P-DS3       | 1        | 0.83%   |
| Fujitsu Siemens ESPRIMO | 1        | 0.83%   |
| Foxconn WU115EA-AKB     | 1        | 0.83%   |
| Foxconn Pro             | 1        | 0.83%   |
| Dell XPS                | 1        | 0.83%   |
| Dell Vostro             | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 12       | 9.92%   |
| 2011 | 11       | 9.09%   |
| 2012 | 10       | 8.26%   |
| 2009 | 9        | 7.44%   |
| 2014 | 8        | 6.61%   |
| 2010 | 8        | 6.61%   |
| 2008 | 8        | 6.61%   |
| 2019 | 7        | 5.79%   |
| 2017 | 7        | 5.79%   |
| 2015 | 7        | 5.79%   |
| 2013 | 6        | 4.96%   |
| 2006 | 6        | 4.96%   |
| 2020 | 5        | 4.13%   |
| 2021 | 4        | 3.31%   |
| 2018 | 4        | 3.31%   |
| 2016 | 4        | 3.31%   |
| 2005 | 4        | 3.31%   |
| 2004 | 1        | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 121      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 118      | 97.52%  |
| Enabled  | 3        | 2.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 121      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 38       | 31.15%  |
| 16.01-24.0      | 18       | 14.75%  |
| 8.01-16.0       | 18       | 14.75%  |
| 1.01-2.0        | 17       | 13.93%  |
| 4.01-8.0        | 15       | 12.3%   |
| 32.01-64.0      | 9        | 7.38%   |
| 2.01-3.0        | 2        | 1.64%   |
| 0.51-1.0        | 2        | 1.64%   |
| More than 256.0 | 1        | 0.82%   |
| 24.01-32.0      | 1        | 0.82%   |
| 64.01-256.0     | 1        | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 63       | 50%     |
| 2.01-3.0   | 22       | 17.46%  |
| 0.51-1.0   | 18       | 14.29%  |
| 4.01-8.0   | 12       | 9.52%   |
| 3.01-4.0   | 5        | 3.97%   |
| 8.01-16.0  | 3        | 2.38%   |
| 0.01-0.5   | 2        | 1.59%   |
| 16.01-24.0 | 1        | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 51.24%  |
| 2      | 39       | 32.23%  |
| 4      | 7        | 5.79%   |
| 3      | 6        | 4.96%   |
| 5      | 4        | 3.31%   |
| 14     | 1        | 0.83%   |
| 7      | 1        | 0.83%   |
| 0      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 64.75%  |
| No        | 43       | 35.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 120      | 99.17%  |
| No        | 1        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 58.68%  |
| Yes       | 50       | 41.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 82.64%  |
| Yes       | 21       | 17.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| France       | 17       | 13.93%  |
| USA          | 16       | 13.11%  |
| Germany      | 12       | 9.84%   |
| Brazil       | 10       | 8.2%    |
| Italy        | 9        | 7.38%   |
| Switzerland  | 5        | 4.1%    |
| Russia       | 5        | 4.1%    |
| Hungary      | 5        | 4.1%    |
| Japan        | 4        | 3.28%   |
| Australia    | 4        | 3.28%   |
| Spain        | 3        | 2.46%   |
| Netherlands  | 3        | 2.46%   |
| Czechia      | 3        | 2.46%   |
| South Africa | 2        | 1.64%   |
| Puerto Rico  | 2        | 1.64%   |
| New Zealand  | 2        | 1.64%   |
| Mexico       | 2        | 1.64%   |
| Greece       | 2        | 1.64%   |
| Finland      | 2        | 1.64%   |
| Canada       | 2        | 1.64%   |
| Belgium      | 2        | 1.64%   |
| UK           | 1        | 0.82%   |
| Sweden       | 1        | 0.82%   |
| Slovenia     | 1        | 0.82%   |
| Singapore    | 1        | 0.82%   |
| Romania      | 1        | 0.82%   |
| Peru         | 1        | 0.82%   |
| Malaysia     | 1        | 0.82%   |
| Costa Rica   | 1        | 0.82%   |
| Colombia     | 1        | 0.82%   |
| Belarus      | 1        | 0.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Rome                  | 4        | 3.25%   |
| Zurich                | 2        | 1.63%   |
| Windsor               | 2        | 1.63%   |
| Wellington            | 2        | 1.63%   |
| Prague                | 2        | 1.63%   |
| Milan                 | 2        | 1.63%   |
| Eger                  | 2        | 1.63%   |
| Cuernavaca            | 2        | 1.63%   |
| Cayey                 | 2        | 1.63%   |
| Augsburg              | 2        | 1.63%   |
| Annecy                | 2        | 1.63%   |
| Yelizovo              | 1        | 0.81%   |
| Winsen                | 1        | 0.81%   |
| Wiesbaden             | 1        | 0.81%   |
| Vlaardingen           | 1        | 0.81%   |
| Vitry-sur-Seine       | 1        | 0.81%   |
| Vaxjo                 | 1        | 0.81%   |
| Vanderbijlpark        | 1        | 0.81%   |
| Valls                 | 1        | 0.81%   |
| Valinhos              | 1        | 0.81%   |
| Valencia              | 1        | 0.81%   |
| Treviso               | 1        | 0.81%   |
| Tourcoing             | 1        | 0.81%   |
| Toronto               | 1        | 0.81%   |
| Tokorozawa            | 1        | 0.81%   |
| The Hague             | 1        | 0.81%   |
| Springfield           | 1        | 0.81%   |
| Spokane               | 1        | 0.81%   |
| Sora                  | 1        | 0.81%   |
| Singapore             | 1        | 0.81%   |
| Sandorfalva           | 1        | 0.81%   |
| Roseburg              | 1        | 0.81%   |
| Roquecourbe           | 1        | 0.81%   |
| Ronnenberg            | 1        | 0.81%   |
| Rio de Janeiro        | 1        | 0.81%   |
| Ramonville-Saint-Agne | 1        | 0.81%   |
| Raleigh               | 1        | 0.81%   |
| PortoroÅ¾           | 1        | 0.81%   |
| Porto Alegre          | 1        | 0.81%   |
| Portbail              | 1        | 0.81%   |
| Periers               | 1        | 0.81%   |
| PÃ©cs               | 1        | 0.81%   |
| Passos                | 1        | 0.81%   |
| Pacatuba              | 1        | 0.81%   |
| Oradea                | 1        | 0.81%   |
| Omsk                  | 1        | 0.81%   |
| Oceanside             | 1        | 0.81%   |
| Novy Jicin            | 1        | 0.81%   |
| Neuchatel             | 1        | 0.81%   |
| Munich                | 1        | 0.81%   |
| Mount Waverley        | 1        | 0.81%   |
| Moscow                | 1        | 0.81%   |
| Moordrecht            | 1        | 0.81%   |
| Montross              | 1        | 0.81%   |
| Montlhery             | 1        | 0.81%   |
| Mogilev               | 1        | 0.81%   |
| Mobile                | 1        | 0.81%   |
| Menen                 | 1        | 0.81%   |
| MedellÃ­n           | 1        | 0.81%   |
| Marlow                | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 47       | 57     | 25.82%  |
| WDC                 | 45       | 70     | 24.73%  |
| Samsung Electronics | 22       | 35     | 12.09%  |
| Toshiba             | 8        | 8      | 4.4%    |
| Kingston            | 8        | 8      | 4.4%    |
| Unknown             | 7        | 8      | 3.85%   |
| Hitachi             | 6        | 7      | 3.3%    |
| SanDisk             | 3        | 3      | 1.65%   |
| MAXTOR              | 3        | 3      | 1.65%   |
| Crucial             | 3        | 3      | 1.65%   |
| China               | 3        | 3      | 1.65%   |
| A-DATA Technology   | 3        | 4      | 1.65%   |
| Team                | 2        | 2      | 1.1%    |
| PNY                 | 2        | 2      | 1.1%    |
| LDLC                | 2        | 2      | 1.1%    |
| JMicron             | 2        | 2      | 1.1%    |
| Intel               | 2        | 2      | 1.1%    |
| Transcend           | 1        | 1      | 0.55%   |
| TO Exter            | 1        | 1      | 0.55%   |
| PNY USB             | 1        | 1      | 0.55%   |
| OCZ                 | 1        | 1      | 0.55%   |
| LONDISK             | 1        | 1      | 0.55%   |
| Lexar               | 1        | 1      | 0.55%   |
| Leven               | 1        | 2      | 0.55%   |
| Intenso             | 1        | 1      | 0.55%   |
| HGST                | 1        | 1      | 0.55%   |
| Hewlett-Packard     | 1        | 6      | 0.55%   |
| GOODRAM             | 1        | 1      | 0.55%   |
| Fujitsu             | 1        | 1      | 0.55%   |
| External            | 1        | 1      | 0.55%   |
| Corsair             | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 2.02%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 1.01%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 1.01%   |
| WDC WD800JD-60LSA5 80GB             | 2        | 1.01%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 1.01%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 1.01%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 1.01%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 1.01%   |
| Unknown M52516  16GB                | 2        | 1.01%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 1.01%   |
| Seagate ST380815AS 80GB             | 2        | 1.01%   |
| Seagate ST3500418AS 500GB           | 2        | 1.01%   |
| Seagate ST3360320AS 360GB           | 2        | 1.01%   |
| Seagate ST3250410AS 250GB           | 2        | 1.01%   |
| Seagate ST3250310AS 250GB           | 2        | 1.01%   |
| Seagate ST31000528AS 1TB            | 2        | 1.01%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 1.01%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 1.01%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 1.01%   |
| Samsung SSD 850 EVO 250GB           | 2        | 1.01%   |
| Samsung HD161HJ 160GB               | 2        | 1.01%   |
| Samsung HD080HJ/ 80GB               | 2        | 1.01%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.01%   |
| China SATA SSD 512GB                | 2        | 1.01%   |
| A-DATA SU650 240GB SSD              | 2        | 1.01%   |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.51%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.51%   |
| WDC WD800JD-75JNA0 80GB             | 1        | 0.51%   |
| WDC WD7501AALS-00J7B1 752GB         | 1        | 0.51%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.51%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.51%   |
| WDC WD5000BPKX-66HPJT0 500GB        | 1        | 0.51%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.51%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.51%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.51%   |
| WDC WD50 00AAKS-00V1A 500GB         | 1        | 0.51%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 0.51%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.51%   |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.51%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.51%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1        | 0.51%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1        | 0.51%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.51%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 0.51%   |
| WDC WD2500JS-75NCB3 250GB           | 1        | 0.51%   |
| WDC WD2500JD-00HBB0 250GB           | 1        | 0.51%   |
| WDC WD2500AAKX-07U6AA0 250GB        | 1        | 0.51%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.51%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.51%   |
| WDC WD1600BB-00RDA0 160GB           | 1        | 0.51%   |
| WDC WD1600AAJS-60B4A0 160GB         | 1        | 0.51%   |
| WDC WD15EARS-22MVWB0 1TB            | 1        | 0.51%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1        | 0.51%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 0.51%   |
| WDC WD10EAVS-14M4B0 1TB             | 1        | 0.51%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 0.51%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 47       | 57     | 40.52%  |
| WDC                 | 40       | 61     | 34.48%  |
| Samsung Electronics | 11       | 12     | 9.48%   |
| Toshiba             | 6        | 6      | 5.17%   |
| Hitachi             | 6        | 7      | 5.17%   |
| MAXTOR              | 3        | 3      | 2.59%   |
| Unknown             | 1        | 1      | 0.86%   |
| HGST                | 1        | 1      | 0.86%   |
| Fujitsu             | 1        | 1      | 0.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 16.67%  |
| Kingston            | 8        | 8      | 14.81%  |
| WDC                 | 7        | 9      | 12.96%  |
| SanDisk             | 3        | 3      | 5.56%   |
| Crucial             | 3        | 3      | 5.56%   |
| China               | 3        | 3      | 5.56%   |
| Toshiba             | 2        | 2      | 3.7%    |
| Team                | 2        | 2      | 3.7%    |
| PNY                 | 2        | 2      | 3.7%    |
| A-DATA Technology   | 2        | 3      | 3.7%    |
| Transcend           | 1        | 1      | 1.85%   |
| TO Exter            | 1        | 1      | 1.85%   |
| PNY USB             | 1        | 1      | 1.85%   |
| OCZ                 | 1        | 1      | 1.85%   |
| LONDISK             | 1        | 1      | 1.85%   |
| Lexar               | 1        | 1      | 1.85%   |
| Leven               | 1        | 2      | 1.85%   |
| LDLC                | 1        | 1      | 1.85%   |
| Intenso             | 1        | 1      | 1.85%   |
| Intel               | 1        | 1      | 1.85%   |
| Hewlett-Packard     | 1        | 6      | 1.85%   |
| GOODRAM             | 1        | 1      | 1.85%   |
| Corsair             | 1        | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 90       | 149    | 58.06%  |
| SSD     | 51       | 66     | 32.9%   |
| NVMe    | 7        | 16     | 4.52%   |
| MMC     | 6        | 7      | 3.87%   |
| Unknown | 1        | 1      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 112      | 208    | 86.15%  |
| SAS  | 7        | 10     | 5.38%   |
| MMC  | 6        | 7      | 4.62%   |
| NVMe | 5        | 14     | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 91       | 132    | 63.64%  |
| 0.51-1.0   | 37       | 57     | 25.87%  |
| 1.01-2.0   | 7        | 10     | 4.9%    |
| 3.01-4.0   | 4        | 12     | 2.8%    |
| 2.01-3.0   | 3        | 3      | 2.1%    |
| 4.01-10.0  | 1        | 1      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 32       | 26.23%  |
| 251-500        | 26       | 21.31%  |
| 501-1000       | 15       | 12.3%   |
| 1001-2000      | 13       | 10.66%  |
| More than 3000 | 11       | 9.02%   |
| 51-100         | 9        | 7.38%   |
| 2001-3000      | 6        | 4.92%   |
| 1-20           | 6        | 4.92%   |
| 21-50          | 3        | 2.46%   |
| Unknown        | 1        | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 48       | 39.02%  |
| 21-50          | 19       | 15.45%  |
| 101-250        | 15       | 12.2%   |
| 251-500        | 9        | 7.32%   |
| 51-100         | 9        | 7.32%   |
| 501-1000       | 8        | 6.5%    |
| 1001-2000      | 7        | 5.69%   |
| More than 3000 | 4        | 3.25%   |
| 2001-3000      | 3        | 2.44%   |
| Unknown        | 1        | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB  | 2        | 2      | 8.7%    |
| WDC WD5000AAKX-003CA0 500GB     | 1        | 1      | 4.35%   |
| WDC WD400EB-00CPF0 40GB         | 1        | 1      | 4.35%   |
| WDC WD2500AAJS-75M0A0 250GB     | 1        | 1      | 4.35%   |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 2      | 4.35%   |
| WDC WD10EADS-65M2B0 1TB         | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 4.35%   |
| Seagate ST380815AS 80GB         | 1        | 1      | 4.35%   |
| Seagate ST3360320AS 360GB       | 1        | 1      | 4.35%   |
| Seagate ST3200822AS 200GB       | 1        | 1      | 4.35%   |
| Seagate ST3160318AS 160GB       | 1        | 1      | 4.35%   |
| Seagate ST2000DX002-2DV164 2TB  | 1        | 1      | 4.35%   |
| Seagate ST1000DX001-1CM162 1TB  | 1        | 1      | 4.35%   |
| Seagate ST1000DM003-1ER162 1TB  | 1        | 1      | 4.35%   |
| MAXTOR STM3300622A 304GB        | 1        | 1      | 4.35%   |
| MAXTOR 6Y080L0 81GB             | 1        | 1      | 4.35%   |
| MAXTOR 6B200M0 208GB            | 1        | 1      | 4.35%   |
| LDLC SSD 120GB                  | 1        | 1      | 4.35%   |
| Kingston SHFS37A120G 120GB SSD  | 1        | 1      | 4.35%   |
| Kingston SA400S37120G 120GB SSD | 1        | 1      | 4.35%   |
| Hitachi HCP725050GLAT80 500GB   | 1        | 1      | 4.35%   |
| Fujitsu MHZ2160BH G2 160GB      | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 10       | 10     | 43.48%  |
| WDC      | 5        | 6      | 21.74%  |
| MAXTOR   | 3        | 3      | 13.04%  |
| Kingston | 2        | 2      | 8.7%    |
| LDLC     | 1        | 1      | 4.35%   |
| Hitachi  | 1        | 1      | 4.35%   |
| Fujitsu  | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 10     | 50%     |
| WDC     | 5        | 6      | 25%     |
| MAXTOR  | 3        | 3      | 15%     |
| Hitachi | 1        | 1      | 5%      |
| Fujitsu | 1        | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 21     | 85.71%  |
| SSD  | 3        | 3      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 100%    |

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
| Works    | 61       | 121    | 44.85%  |
| Detected | 54       | 93     | 39.71%  |
| Malfunc  | 20       | 24     | 14.71%  |
| Failed   | 1        | 1      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 72       | 54.14%  |
| AMD                       | 27       | 20.3%   |
| Nvidia                    | 15       | 11.28%  |
| JMicron Technology        | 5        | 3.76%   |
| Marvell Technology Group  | 4        | 3.01%   |
| VIA Technologies          | 2        | 1.5%    |
| Samsung Electronics       | 2        | 1.5%    |
| LSI Logic / Symbios Logic | 2        | 1.5%    |
| ASMedia Technology        | 2        | 1.5%    |
| Silicon Motion            | 1        | 0.75%   |
| ADATA Technology          | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 9.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 5.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.23%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 3.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 3.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.17%   |
| Nvidia MCP61 IDE                                                                        | 5        | 2.65%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.65%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.12%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.12%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.12%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.59%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.59%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.59%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 1.06%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.06%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.06%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.06%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.06%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2        | 1.06%   |
| AMD SB600 IDE                                                                           | 2        | 1.06%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 1.06%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 1.06%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.53%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.53%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.53%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.53%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.53%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.53%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.53%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.53%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.53%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.53%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.53%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.53%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.53%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.53%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.53%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.53%   |
| Intel SSD 660P Series                                                                   | 1        | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.53%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.53%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 70       | 51.09%  |
| IDE  | 55       | 40.15%  |
| RAID | 5        | 3.65%   |
| NVMe | 5        | 3.65%   |
| SCSI | 2        | 1.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 80       | 66.12%  |
| AMD    | 41       | 33.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3        | 2.48%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.48%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.65%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.65%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.65%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.65%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.65%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.65%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 1.65%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.65%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.65%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 2        | 1.65%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.83%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.83%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.83%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.83%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.83%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.83%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.83%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.83%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.83%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.83%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.83%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.83%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 0.83%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.83%   |
| Intel Core i5-4440S CPU @ 2.80GHz           | 1        | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.83%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 0.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 0.83%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.83%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 0.83%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.83%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.83%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.83%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 0.83%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 0.83%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 0.83%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 0.83%   |
| Intel Core 2 Quad CPU @ 2.40GHz             | 1        | 0.83%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1        | 0.83%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 0.83%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 0.83%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 0.83%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 0.83%   |
| Intel Core 2 Duo CPU E6850 @ 3.00GHz        | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 17.36%  |
| Intel Core 2 Duo        | 11       | 9.09%   |
| Intel Atom              | 8        | 6.61%   |
| Intel Core i3           | 7        | 5.79%   |
| Intel Core i7           | 6        | 4.96%   |
| AMD Ryzen 5             | 6        | 4.96%   |
| AMD Athlon 64 X2        | 6        | 4.96%   |
| Intel Core 2 Quad       | 5        | 4.13%   |
| Intel Celeron           | 5        | 4.13%   |
| AMD Athlon II X2        | 5        | 4.13%   |
| Intel Xeon              | 4        | 3.31%   |
| Intel Core 2            | 4        | 3.31%   |
| AMD A10                 | 4        | 3.31%   |
| Intel Pentium Dual-Core | 3        | 2.48%   |
| AMD Ryzen 7             | 3        | 2.48%   |
| AMD Athlon 64           | 3        | 2.48%   |
| Intel Pentium Dual      | 2        | 1.65%   |
| Intel Pentium 4         | 2        | 1.65%   |
| AMD Sempron             | 2        | 1.65%   |
| AMD Ryzen 3             | 2        | 1.65%   |
| AMD GX                  | 2        | 1.65%   |
| Intel Pentium Gold      | 1        | 0.83%   |
| Intel Pentium           | 1        | 0.83%   |
| AMD Ryzen Threadripper  | 1        | 0.83%   |
| AMD Quad-Core Opteron   | 1        | 0.83%   |
| AMD Phenom II X3        | 1        | 0.83%   |
| AMD Opteron             | 1        | 0.83%   |
| AMD FX                  | 1        | 0.83%   |
| AMD E                   | 1        | 0.83%   |
| AMD Athlon X4           | 1        | 0.83%   |
| AMD Athlon II X4        | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 57       | 47.11%  |
| 4      | 40       | 33.06%  |
| 6      | 8        | 6.61%   |
| 1      | 8        | 6.61%   |
| 8      | 5        | 4.13%   |
| 64     | 1        | 0.83%   |
| 12     | 1        | 0.83%   |
| 3      | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 119      | 98.35%  |
| 2      | 2        | 1.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 80       | 66.12%  |
| 2      | 41       | 33.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 121      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 15.7%   |
| 0x206a7    | 12       | 9.92%   |
| 0x306c3    | 10       | 8.26%   |
| 0x1067a    | 8        | 6.61%   |
| 0x906e9    | 4        | 3.31%   |
| 0x6fd      | 4        | 3.31%   |
| 0x6fb      | 4        | 3.31%   |
| 0x406c4    | 4        | 3.31%   |
| 0x06001119 | 4        | 3.31%   |
| 0x6f6      | 3        | 2.48%   |
| 0x306a9    | 3        | 2.48%   |
| 0x10676    | 3        | 2.48%   |
| 0x08701021 | 3        | 2.48%   |
| 0x010000c8 | 3        | 2.48%   |
| 0x506e3    | 2        | 1.65%   |
| 0x20655    | 2        | 1.65%   |
| 0x106ca    | 2        | 1.65%   |
| 0x08701013 | 2        | 1.65%   |
| 0x0800820d | 2        | 1.65%   |
| 0x0700010f | 2        | 1.65%   |
| 0xf65      | 1        | 0.83%   |
| 0xf4a      | 1        | 0.83%   |
| 0xa0655    | 1        | 0.83%   |
| 0xa0653    | 1        | 0.83%   |
| 0x906ea    | 1        | 0.83%   |
| 0x706a1    | 1        | 0.83%   |
| 0x6f7      | 1        | 0.83%   |
| 0x6f2      | 1        | 0.83%   |
| 0x406c3    | 1        | 0.83%   |
| 0x306f2    | 1        | 0.83%   |
| 0x306e4    | 1        | 0.83%   |
| 0x30678    | 1        | 0.83%   |
| 0x30661    | 1        | 0.83%   |
| 0x206d7    | 1        | 0.83%   |
| 0x106e5    | 1        | 0.83%   |
| 0x10677    | 1        | 0.83%   |
| 0x0a50000c | 1        | 0.83%   |
| 0x0830104d | 1        | 0.83%   |
| 0x08108109 | 1        | 0.83%   |
| 0x06003106 | 1        | 0.83%   |
| 0x06000852 | 1        | 0.83%   |
| 0x05000119 | 1        | 0.83%   |
| 0x010000db | 1        | 0.83%   |
| 0x010000c7 | 1        | 0.83%   |
| 0x01000095 | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 13       | 10.74%  |
| Core          | 13       | 10.74%  |
| Penryn        | 12       | 9.92%   |
| Haswell       | 12       | 9.92%   |
| K8 Hammer     | 11       | 9.09%   |
| K10           | 9        | 7.44%   |
| Zen 2         | 6        | 4.96%   |
| Silvermont    | 6        | 4.96%   |
| Zen+          | 5        | 4.13%   |
| Piledriver    | 5        | 4.13%   |
| KabyLake      | 5        | 4.13%   |
| IvyBridge     | 4        | 3.31%   |
| Skylake       | 3        | 2.48%   |
| CometLake     | 3        | 2.48%   |
| Bonnell       | 3        | 2.48%   |
| Westmere      | 2        | 1.65%   |
| NetBurst      | 2        | 1.65%   |
| Jaguar        | 2        | 1.65%   |
| Zen 3         | 1        | 0.83%   |
| Steamroller   | 1        | 0.83%   |
| Nehalem       | 1        | 0.83%   |
| Goldmont plus | 1        | 0.83%   |
| Bobcat        | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 45       | 36%     |
| Intel  | 41       | 32.8%   |
| AMD    | 39       | 31.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 6.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.82%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5        | 3.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 3.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 3.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 2.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.29%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.29%   |
| AMD Richland [Radeon HD 8670D]                                                           | 3        | 2.29%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 2.29%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.53%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.53%   |
| Intel HD Graphics 530                                                                    | 2        | 1.53%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.53%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.53%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.53%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.53%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.53%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.76%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.76%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.76%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.76%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.76%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.76%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.76%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.76%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.76%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.76%   |
| Nvidia GP107GL [Quadro P400]                                                             | 1        | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.76%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 0.76%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.76%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.76%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.76%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.76%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.76%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.76%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1        | 0.76%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.76%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.76%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.76%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 0.76%   |
| Intel HD Graphics 630                                                                    | 1        | 0.76%   |
| Intel HD Graphics 610                                                                    | 1        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.76%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 1        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.76%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.76%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.76%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 0.76%   |
| AMD Turks [Radeon HD 7600 Series]                                                        | 1        | 0.76%   |
| AMD RV770 [Radeon HD 4850]                                                               | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 42       | 34.43%  |
| 1 x Intel    | 40       | 32.79%  |
| 1 x AMD      | 34       | 27.87%  |
| 2 x AMD      | 4        | 3.28%   |
| 2 x Nvidia   | 1        | 0.82%   |
| AMD + Nvidia | 1        | 0.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 97       | 80.17%  |
| Proprietary | 23       | 19.01%  |
| Unknown     | 1        | 0.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 38.52%  |
| 0.01-0.5   | 31       | 25.41%  |
| 0.51-1.0   | 18       | 14.75%  |
| 1.01-2.0   | 13       | 10.66%  |
| 3.01-4.0   | 7        | 5.74%   |
| 7.01-8.0   | 3        | 2.46%   |
| 8.01-16.0  | 2        | 1.64%   |
| 2.01-3.0   | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 17       | 14.05%  |
| Samsung Electronics     | 16       | 13.22%  |
| Goldstar                | 13       | 10.74%  |
| Acer                    | 9        | 7.44%   |
| Hewlett-Packard         | 8        | 6.61%   |
| Lenovo                  | 5        | 4.13%   |
| Vizio                   | 4        | 3.31%   |
| Philips                 | 4        | 3.31%   |
| BenQ                    | 4        | 3.31%   |
| Ancor Communications    | 4        | 3.31%   |
| Unknown                 | 3        | 2.48%   |
| Iiyama                  | 3        | 2.48%   |
| AOC                     | 3        | 2.48%   |
| Sony                    | 2        | 1.65%   |
| LG Electronics          | 2        | 1.65%   |
| IOD                     | 2        | 1.65%   |
| FL_                     | 2        | 1.65%   |
| ___                     | 1        | 0.83%   |
| Unknown (ADA)           | 1        | 0.83%   |
| Sceptre Tech            | 1        | 0.83%   |
| Plain Tree Systems      | 1        | 0.83%   |
| NEC Computers           | 1        | 0.83%   |
| MOT                     | 1        | 0.83%   |
| Lite-On                 | 1        | 0.83%   |
| LG Display              | 1        | 0.83%   |
| Lenovo Group Limited    | 1        | 0.83%   |
| IBM                     | 1        | 0.83%   |
| Hitachi                 | 1        | 0.83%   |
| HannStar                | 1        | 0.83%   |
| GDH                     | 1        | 0.83%   |
| Fujitsu Siemens         | 1        | 0.83%   |
| Element                 | 1        | 0.83%   |
| Eizo                    | 1        | 0.83%   |
| CVT                     | 1        | 0.83%   |
| Compaq Computer         | 1        | 0.83%   |
| Chi Mei Optoelectronics | 1        | 0.83%   |
| Arnos Instruments       | 1        | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 1.59%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 1.59%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 1.59%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 1.59%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2        | 1.59%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 1.59%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.79%   |
| ___ LCDTV16 ___0101 1360x768                                          | 1        | 0.79%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1        | 0.79%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 1        | 0.79%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                    | 1        | 0.79%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                    | 1        | 0.79%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.79%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.79%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.79%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.79%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.79%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.79%   |
| Sony TV SNYAA01 1360x768                                              | 1        | 0.79%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.79%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1        | 0.79%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1        | 0.79%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.79%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.79%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.79%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                   | 1        | 0.79%   |
| Samsung Electronics LCD Monitor C27F390 1920x1080                     | 1        | 0.79%   |
| Plain Tree Systems FULL HDTV PTS00EC 1920x1080 520x290mm 23.4-inch    | 1        | 0.79%   |
| Philips PHL 322M7C PHLC194 1920x1080 698x393mm 31.5-inch              | 1        | 0.79%   |
| Philips 271P4 PHL08C3 1920x1080 597x336mm 27.0-inch                   | 1        | 0.79%   |
| Philips 190B PHL081A 1280x1024 376x301mm 19.0-inch                    | 1        | 0.79%   |
| Philips 170C5 PHLC00B 1280x1024 338x270mm 17.0-inch                   | 1        | 0.79%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 340x270mm 17.1-inch         | 1        | 0.79%   |
| MOT MotoAttach MOT3DC4 1366x768 260x140mm 11.6-inch                   | 1        | 0.79%   |
| Lite-On GC150AT/ATA LTN020E 1024x768 304x228mm 15.0-inch              | 1        | 0.79%   |
| LG Electronics LCD Monitor W2220                                      | 1        | 0.79%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 0.79%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1        | 0.79%   |
| Lenovo LEN-M93z-B LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 0.79%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1        | 0.79%   |
| Lenovo LEN L1700pC LEN24C9 1280x1024 338x270mm 17.0-inch              | 1        | 0.79%   |
| Lenovo Group Limited LCD Monitor LEN L24q-30 1920x1200                | 1        | 0.79%   |
| IOD LCD-A153G IOD0F46 1024x768 304x228mm 15.0-inch                    | 1        | 0.79%   |
| IOD EX-LD2381D IOD180C 1920x1080 530x300mm 24.0-inch                  | 1        | 0.79%   |
| IOD DIOS-MF241X IOD180A 1920x1080 530x300mm 24.0-inch                 | 1        | 0.79%   |
| Iiyama PL2792H IVM6638 1920x1080 600x340mm 27.2-inch                  | 1        | 0.79%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                  | 1        | 0.79%   |
| Iiyama PL2006W IVM539A 1680x1050 430x240mm 19.4-inch                  | 1        | 0.79%   |
| IBM L150 IBM19EC 1024x768 304x228mm 15.0-inch                         | 1        | 0.79%   |
| Hitachi X224W D-sub HIT700B 1680x1050 473x296mm 22.0-inch             | 1        | 0.79%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch         | 1        | 0.79%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 37       | 30.33%  |
| 1280x1024 (SXGA)   | 24       | 19.67%  |
| 1680x1050 (WSXGA+) | 13       | 10.66%  |
| 1366x768 (WXGA)    | 9        | 7.38%   |
| 2560x1440 (QHD)    | 8        | 6.56%   |
| 1440x900 (WXGA+)   | 7        | 5.74%   |
| 1024x768 (XGA)     | 6        | 4.92%   |
| 1600x900 (HD+)     | 3        | 2.46%   |
| 3840x2160 (4K)     | 2        | 1.64%   |
| 2560x1080          | 2        | 1.64%   |
| 1920x1200 (WUXGA)  | 2        | 1.64%   |
| 1280x800 (WXGA)    | 2        | 1.64%   |
| 3600x1200          | 1        | 0.82%   |
| 3440x1440          | 1        | 0.82%   |
| 2560x1600          | 1        | 0.82%   |
| 2288x1287          | 1        | 0.82%   |
| 1600x1200          | 1        | 0.82%   |
| 1360x768           | 1        | 0.82%   |
| Unknown            | 1        | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 16       | 13.11%  |
| 19      | 13       | 10.66%  |
| 24      | 11       | 9.02%   |
| 21      | 11       | 9.02%   |
| 27      | 10       | 8.2%    |
| 23      | 10       | 8.2%    |
| Unknown | 10       | 8.2%    |
| 22      | 8        | 6.56%   |
| 15      | 7        | 5.74%   |
| 20      | 6        | 4.92%   |
| 18      | 4        | 3.28%   |
| 41      | 2        | 1.64%   |
| 39      | 2        | 1.64%   |
| 34      | 2        | 1.64%   |
| 31      | 2        | 1.64%   |
| 72      | 1        | 0.82%   |
| 38      | 1        | 0.82%   |
| 37      | 1        | 0.82%   |
| 32      | 1        | 0.82%   |
| 29      | 1        | 0.82%   |
| 14      | 1        | 0.82%   |
| 11      | 1        | 0.82%   |
| 7       | 1        | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 32       | 26.67%  |
| 501-600     | 31       | 25.83%  |
| 301-350     | 22       | 18.33%  |
| 351-400     | 10       | 8.33%   |
| Unknown     | 10       | 8.33%   |
| 801-900     | 4        | 3.33%   |
| 701-800     | 3        | 2.5%    |
| 601-700     | 3        | 2.5%    |
| 901-1000    | 2        | 1.67%   |
| 201-300     | 1        | 0.83%   |
| 1501-2000   | 1        | 0.83%   |
| 101-200     | 1        | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 55       | 47.41%  |
| 5/4     | 22       | 18.97%  |
| 16/10   | 18       | 15.52%  |
| Unknown | 9        | 7.76%   |
| 4/3     | 6        | 5.17%   |
| 21/9    | 3        | 2.59%   |
| 6/5     | 2        | 1.72%   |
| 3/2     | 1        | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 28.33%  |
| 151-200        | 21       | 17.5%   |
| 141-150        | 18       | 15%     |
| 301-350        | 11       | 9.17%   |
| Unknown        | 10       | 8.33%   |
| 101-110        | 7        | 5.83%   |
| 501-1000       | 6        | 5%      |
| 351-500        | 5        | 4.17%   |
| 251-300        | 3        | 2.5%    |
| More than 1000 | 1        | 0.83%   |
| 81-90          | 1        | 0.83%   |
| 51-60          | 1        | 0.83%   |
| 1-40           | 1        | 0.83%   |
| 131-140        | 1        | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 78       | 68.42%  |
| 101-120 | 15       | 13.16%  |
| Unknown | 10       | 8.77%   |
| 121-160 | 7        | 6.14%   |
| 1-50    | 2        | 1.75%   |
| 161-240 | 2        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 86.78%  |
| 2     | 10       | 8.26%   |
| 0     | 4        | 3.31%   |
| 4     | 1        | 0.83%   |
| 3     | 1        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 69       | 40.83%  |
| Intel                    | 39       | 23.08%  |
| Nvidia                   | 13       | 7.69%   |
| Qualcomm Atheros         | 11       | 6.51%   |
| Ralink Technology        | 10       | 5.92%   |
| Ralink                   | 5        | 2.96%   |
| Broadcom                 | 4        | 2.37%   |
| Marvell Technology Group | 3        | 1.78%   |
| TP-Link                  | 2        | 1.18%   |
| Samsung Electronics      | 2        | 1.18%   |
| Broadcom Limited         | 2        | 1.18%   |
| ZyXEL Communications     | 1        | 0.59%   |
| VIA Technologies         | 1        | 0.59%   |
| U-Blox                   | 1        | 0.59%   |
| Sitecom Europe           | 1        | 0.59%   |
| NetGear                  | 1        | 0.59%   |
| Logitec                  | 1        | 0.59%   |
| Huawei Technologies      | 1        | 0.59%   |
| Aquantia                 | 1        | 0.59%   |
| ADMtek                   | 1        | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 26.78%  |
| Nvidia MCP61 Ethernet                                             | 7        | 3.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.73%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.19%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.19%   |
| Ralink RT5572 Wireless Adapter                                    | 3        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.64%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.09%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 1.09%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.09%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.09%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.09%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.09%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 1.09%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.09%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.09%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.09%   |
| Intel Wireless-AC 9260                                            | 2        | 1.09%   |
| Intel Wireless 7260                                               | 2        | 1.09%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.09%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.55%   |
| U-Blox GNSS receiver                                              | 1        | 0.55%   |
| TP-Link TL WN823N RTL8192EU                                       | 1        | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.55%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.55%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.55%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.55%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.55%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.55%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.55%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.55%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.55%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.55%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 23.53%  |
| Ralink Technology     | 10       | 19.61%  |
| Intel                 | 9        | 17.65%  |
| Qualcomm Atheros      | 8        | 15.69%  |
| Ralink                | 5        | 9.8%    |
| TP-Link               | 2        | 3.92%   |
| ZyXEL Communications  | 1        | 1.96%   |
| Sitecom Europe        | 1        | 1.96%   |
| NetGear               | 1        | 1.96%   |
| Logitec               | 1        | 1.96%   |
| Broadcom              | 1        | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 9.8%    |
| Ralink RT5572 Wireless Adapter                                 | 3        | 5.88%   |
| Realtek RTL8187 Wireless Adapter                               | 2        | 3.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 3.92%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 3.92%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 3.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2        | 3.92%   |
| Intel Wireless-AC 9260                                         | 2        | 3.92%   |
| Intel Wireless 7260                                            | 2        | 3.92%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 1.96%   |
| TP-Link TL WN823N RTL8192EU                                    | 1        | 1.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 1.96%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 1.96%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 1.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 1.96%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 1.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 1.96%   |
| Ralink RT5372 Wireless Adapter                                 | 1        | 1.96%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 1.96%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 1.96%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.96%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 1.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 1.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 1.96%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 1.96%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 1.96%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                      | 1        | 1.96%   |
| Intel Wireless 7265                                            | 1        | 1.96%   |
| Intel Wireless 3165                                            | 1        | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 1.96%   |
| Intel Centrino Advanced-N 6235                                 | 1        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 61       | 48.8%   |
| Intel                    | 32       | 25.6%   |
| Nvidia                   | 13       | 10.4%   |
| Qualcomm Atheros         | 4        | 3.2%    |
| Broadcom                 | 4        | 3.2%    |
| Marvell Technology Group | 3        | 2.4%    |
| Samsung Electronics      | 2        | 1.6%    |
| Broadcom Limited         | 2        | 1.6%    |
| VIA Technologies         | 1        | 0.8%    |
| Huawei Technologies      | 1        | 0.8%    |
| Aquantia                 | 1        | 0.8%    |
| ADMtek                   | 1        | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 37.4%   |
| Nvidia MCP61 Ethernet                                             | 7        | 5.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 3.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.05%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.29%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.29%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.53%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.53%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.53%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.76%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.76%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.76%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.76%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.76%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.76%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.76%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.76%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.76%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.76%   |
| Huawei INE-LX2                                                    | 1        | 0.76%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.76%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.76%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.76%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.76%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 0.76%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.76%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 70.18%  |
| WiFi     | 50       | 29.24%  |
| Modem    | 1        | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 112      | 76.19%  |
| WiFi     | 35       | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 72.73%  |
| 2     | 28       | 23.14%  |
| 3     | 4        | 3.31%   |
| 0     | 1        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 99       | 81.15%  |
| Yes  | 23       | 18.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 38.1%   |
| Cambridge Silicon Radio | 7        | 33.33%  |
| Broadcom                | 3        | 14.29%  |
| Ralink                  | 1        | 4.76%   |
| Lite-On Technology      | 1        | 4.76%   |
| Hewlett-Packard         | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 33.33%  |
| Intel Bluetooth wireless interface                  | 4        | 19.05%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 9.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 9.52%   |
| Ralink RT3290 Bluetooth                             | 1        | 4.76%   |
| Lite-On Bluetooth Device                            | 1        | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4.76%   |
| Intel Bluetooth Device                              | 1        | 4.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 4.76%   |
| Broadcom Bluetooth Device                           | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 71       | 40.57%  |
| Nvidia                   | 44       | 25.14%  |
| AMD                      | 41       | 23.43%  |
| Creative Labs            | 4        | 2.29%   |
| C-Media Electronics      | 4        | 2.29%   |
| XMOS                     | 2        | 1.14%   |
| Logitech                 | 2        | 1.14%   |
| VIA Technologies         | 1        | 0.57%   |
| Unknown                  | 1        | 0.57%   |
| GN Netcom                | 1        | 0.57%   |
| Focusrite-Novation       | 1        | 0.57%   |
| Creative Technology      | 1        | 0.57%   |
| BEHRINGER International  | 1        | 0.57%   |
| Asahi Kasei Microsystems | 1        | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                 | 11       | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller              | 11       | 5.47%   |
| Nvidia High Definition Audio Controller                                                 | 10       | 4.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                     | 9        | 4.48%   |
| Nvidia MCP61 High Definition Audio                                                      | 7        | 3.48%   |
| AMD FCH Azalia Controller                                                               | 7        | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                        | 6        | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                          | 6        | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                            | 6        | 2.99%   |
| Nvidia GP107GL High Definition Audio Controller                                         | 5        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                         | 5        | 2.49%   |
| AMD Starship/Matisse HD Audio Controller                                                | 5        | 2.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                           | 4        | 1.99%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                     | 4        | 1.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                          | 4        | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                     | 4        | 1.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                  | 4        | 1.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                   | 3        | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                | 3        | 1.49%   |
| Intel 200 Series PCH HD Audio                                                           | 3        | 1.49%   |
| AMD Trinity HDMI Audio Controller                                                       | 3        | 1.49%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                 | 3        | 1.49%   |
| AMD Family 17h/19h HD Audio Controller                                                  | 3        | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                     | 3        | 1.49%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]       | 3        | 1.49%   |
| XMOS Mayfield Audio                                                                     | 2        | 1%      |
| Nvidia GK107 HDMI Audio Controller                                                      | 2        | 1%      |
| Nvidia GK106 HDMI Audio Controller                                                      | 2        | 1%      |
| Nvidia GF108 High Definition Audio Controller                                           | 2        | 1%      |
| Nvidia CK804 AC'97 Audio Controller                                                     | 2        | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                                       | 2        | 1%      |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                              | 2        | 1%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                        | 2        | 1%      |
| AMD Kabini HDMI/DP Audio                                                                | 2        | 1%      |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                          | 2        | 1%      |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                      | 1        | 0.5%    |
| Unknown Realtek USB Audio Rear                                                          | 1        | 0.5%    |
| Unknown Realtek USB Audio Front                                                         | 1        | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                          | 1        | 0.5%    |
| Nvidia TU104 HD Audio Controller                                                        | 1        | 0.5%    |
| Nvidia TU102 High Definition Audio Controller                                           | 1        | 0.5%    |
| Nvidia MCP73 High Definition Audio                                                      | 1        | 0.5%    |
| Nvidia MCP67 High Definition Audio                                                      | 1        | 0.5%    |
| Nvidia MCP51 High Definition Audio                                                      | 1        | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                                           | 1        | 0.5%    |
| Nvidia GM204 High Definition Audio Controller                                           | 1        | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                                      | 1        | 0.5%    |
| Nvidia GF116 High Definition Audio Controller                                           | 1        | 0.5%    |
| Logitech Headset H390                                                                   | 1        | 0.5%    |
| Logitech EasyCall Speakerphone                                                          | 1        | 0.5%    |
| Intel Comet Lake PCH-V cAVS                                                             | 1        | 0.5%    |
| Intel Comet Lake PCH cAVS                                                               | 1        | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                            | 1        | 0.5%    |
| Intel C610/X99 series chipset HD Audio Controller                                       | 1        | 0.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller                          | 1        | 0.5%    |
| Intel Audio device                                                                      | 1        | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio | 1        | 0.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller              | 1        | 0.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                        | 1        | 0.5%    |
| GN Netcom Jabra EVOLVE LINK MS                                                          | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 17       | 18.48%  |
| Samsung Electronics | 16       | 17.39%  |
| SK Hynix            | 15       | 16.3%   |
| Kingston            | 8        | 8.7%    |
| Crucial             | 6        | 6.52%   |
| Micron Technology   | 5        | 5.43%   |
| G.Skill             | 5        | 5.43%   |
| Corsair             | 5        | 5.43%   |
| Nanya Technology    | 3        | 3.26%   |
| TIMETEC             | 2        | 2.17%   |
| Patriot             | 2        | 2.17%   |
| Unknown (ABCD)      | 1        | 1.09%   |
| Unifosa             | 1        | 1.09%   |
| Team                | 1        | 1.09%   |
| Ramaxel Technology  | 1        | 1.09%   |
| Qimonda             | 1        | 1.09%   |
| Elpida              | 1        | 1.09%   |
| e2e4                | 1        | 1.09%   |
| 48spaces            | 1        | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                | 4        | 4%      |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 2        | 2%      |
| Unknown RAM Module 2048MB DIMM 400MT/s                       | 2        | 2%      |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 2        | 2%      |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s           | 2        | 2%      |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                 | 1        | 1%      |
| Unknown RAM Module 512MB DIMM 400MT/s                        | 1        | 1%      |
| Unknown RAM Module 512MB DIMM 333MT/s                        | 1        | 1%      |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 1        | 1%      |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1        | 1%      |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                 | 1        | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1        | 1%      |
| Unknown RAM Module 2048MB DIMM DDR2                          | 1        | 1%      |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 1        | 1%      |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1        | 1%      |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 1        | 1%      |
| Unknown RAM Module 1024MB DIMM DDR2                          | 1        | 1%      |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                   | 1        | 1%      |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 1%      |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s            | 1        | 1%      |
| TIMETEC RAM UD3-1600 8192MB DIMM DDR3 1600MT/s               | 1        | 1%      |
| TIMETEC RAM SD3-1600 8192MB SODIMM DDR3 1600MT/s             | 1        | 1%      |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s           | 1        | 1%      |
| SK Hynix RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 1%      |
| SK Hynix RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 1%      |
| SK Hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s       | 1        | 1%      |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1        | 1%      |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 1%      |
| SK Hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s      | 1        | 1%      |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s         | 1        | 1%      |
| SK Hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s      | 1        | 1%      |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s         | 1        | 1%      |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1        | 1%      |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s         | 1        | 1%      |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 1        | 1%      |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1        | 1%      |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1        | 1%      |
| Samsung RAM M471B1G73AH0-CK0 4096MB SODIMM DDR3 1333MT/s     | 1        | 1%      |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s    | 1        | 1%      |
| Samsung RAM M4 70T2864FB3-CF7 1024MB SODIMM DDR2 667MT/s     | 1        | 1%      |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1600MT/s       | 1        | 1%      |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s         | 1        | 1%      |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s               | 1        | 1%      |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s          | 1        | 1%      |
| Samsung RAM M378B5273BH1-CF8 4096MB DIMM 1066MT/s            | 1        | 1%      |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s       | 1        | 1%      |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s          | 1        | 1%      |
| Samsung RAM M3 78T2863RZS-CE6 1024MB DIMM DDR2 667MT/s       | 1        | 1%      |
| Samsung RAM M3 78T2863QZS-CE6 1024MB DIMM DDR2 667MT/s       | 1        | 1%      |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s       | 1        | 1%      |
| Samsung RAM M3 12L2920CZ3-CCC 1024MB DIMM DDR 400MT/s        | 1        | 1%      |
| Ramaxel RAM RML1040EG38D6F-533 512MB DIMM DDR2 533MT/s       | 1        | 1%      |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s          | 1        | 1%      |
| Patriot RAM PSD44G213341 4096MB DIMM DDR4 3000MT/s           | 1        | 1%      |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s           | 1        | 1%      |
| Nanya RAM NT4GC64B8HB0NF-CG 4096MB DIMM DDR3 1333MT/s        | 1        | 1%      |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s          | 1        | 1%      |
| Micron RAM 8JTF25664AZ-1G4D1 2048MB SODIMM DDR3 1333MT/s     | 1        | 1%      |
| Micron RAM 36JSF1G72PZ-1 8192MB DIMM DDR3 1600MT/s           | 1        | 1%      |
| Micron RAM 16JTF51264AZ-1G4M1 4096MB DIMM DDR3 1333MT/s      | 1        | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 34       | 41.98%  |
| DDR4    | 17       | 20.99%  |
| DDR2    | 15       | 18.52%  |
| SDRAM   | 6        | 7.41%   |
| Unknown | 6        | 7.41%   |
| DDR     | 2        | 2.47%   |
| LPDDR4  | 1        | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 68       | 86.08%  |
| SODIMM | 11       | 13.92%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 28       | 32.94%  |
| 8192  | 20       | 23.53%  |
| 4096  | 19       | 22.35%  |
| 1024  | 7        | 8.24%   |
| 16384 | 6        | 7.06%   |
| 512   | 3        | 3.53%   |
| 65536 | 1        | 1.18%   |
| 32768 | 1        | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 23.6%   |
| 1333    | 9        | 10.11%  |
| 800     | 9        | 10.11%  |
| 2133    | 7        | 7.87%   |
| 667     | 5        | 5.62%   |
| 400     | 5        | 5.62%   |
| 2400    | 4        | 4.49%   |
| Unknown | 4        | 4.49%   |
| 3200    | 3        | 3.37%   |
| 2667    | 3        | 3.37%   |
| 2048    | 3        | 3.37%   |
| 1066    | 3        | 3.37%   |
| 3600    | 2        | 2.25%   |
| 3000    | 2        | 2.25%   |
| 1866    | 2        | 2.25%   |
| 49926   | 1        | 1.12%   |
| 3466    | 1        | 1.12%   |
| 2733    | 1        | 1.12%   |
| 1867    | 1        | 1.12%   |
| 1334    | 1        | 1.12%   |
| 533     | 1        | 1.12%   |
| 333     | 1        | 1.12%   |

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
| Logitech                      | 4        | 23.53%  |
| Chicony Electronics           | 2        | 11.76%  |
| Z-Star Microelectronics       | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| SJ-180517-N                   | 1        | 5.88%   |
| Samsung Electronics           | 1        | 5.88%   |
| Microsoft                     | 1        | 5.88%   |
| KYE Systems (Mouse Systems)   | 1        | 5.88%   |
| Guillemot                     | 1        | 5.88%   |
| Genesys Logic                 | 1        | 5.88%   |
| Generalplus Technology        | 1        | 5.88%   |
| ARC International             | 1        | 5.88%   |
| Acer                          | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 2        | 11.76%  |
| Z-Star Sirius USB2.0 Camera               | 1        | 5.88%   |
| Sunplus Full HD webcam                    | 1        | 5.88%   |
| SJ-180517-N 1080P Webcam                  | 1        | 5.88%   |
| Samsung Galaxy A5 (MTP)                   | 1        | 5.88%   |
| Microsoft LifeCam HD-3000                 | 1        | 5.88%   |
| Logitech QuickCam Zoom                    | 1        | 5.88%   |
| Logitech HD Webcam C525                   | 1        | 5.88%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 5.88%   |
| Guillemot Hercules HD Sunset              | 1        | 5.88%   |
| Genesys Logic Camera                      | 1        | 5.88%   |
| Generalplus GENERAL WEBCAM                | 1        | 5.88%   |
| Chicony CNF7042                           | 1        | 5.88%   |
| Chicony ASUS USB2.0 Webcam                | 1        | 5.88%   |
| ARC International Camera                  | 1        | 5.88%   |
| Acer Integrated Camera                    | 1        | 5.88%   |

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
| 0     | 101      | 83.47%  |
| 1     | 19       | 15.7%   |
| 2     | 1        | 0.83%   |

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

