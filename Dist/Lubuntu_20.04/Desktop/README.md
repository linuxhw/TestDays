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
| 5.4.0-52-generic      | 8        | 6.72%   |
| 5.4.0-42-generic      | 7        | 5.88%   |
| 5.8.0-50-generic      | 6        | 5.04%   |
| 5.11.0-27-generic     | 6        | 5.04%   |
| 5.4.0-54-generic      | 5        | 4.2%    |
| 5.4.0-67-generic      | 4        | 3.36%   |
| 5.4.0-40-generic      | 4        | 3.36%   |
| 5.4.0-29-generic      | 4        | 3.36%   |
| 5.4.0-77-generic      | 3        | 2.52%   |
| 5.4.0-73-generic      | 3        | 2.52%   |
| 5.4.0-48-generic      | 3        | 2.52%   |
| 5.4.0-47-generic      | 3        | 2.52%   |
| 5.4.0-37-generic      | 3        | 2.52%   |
| 5.4.0-33-generic      | 3        | 2.52%   |
| 5.4.0-26-generic      | 3        | 2.52%   |
| 5.8.0-63-generic      | 2        | 1.68%   |
| 5.8.0-59-generic      | 2        | 1.68%   |
| 5.8.0-53-generic      | 2        | 1.68%   |
| 5.8.0-45-generic      | 2        | 1.68%   |
| 5.8.0-41-generic      | 2        | 1.68%   |
| 5.4.0-90-generic      | 2        | 1.68%   |
| 5.4.0-72-generic      | 2        | 1.68%   |
| 5.4.0-66-generic      | 2        | 1.68%   |
| 5.4.0-60-generic      | 2        | 1.68%   |
| 5.13.0-27-generic     | 2        | 1.68%   |
| 5.11.0-43-generic     | 2        | 1.68%   |
| 5.11.0-38-generic     | 2        | 1.68%   |
| 5.11.0-34-generic     | 2        | 1.68%   |
| 5.8.0-7630-generic    | 1        | 0.84%   |
| 5.8.0-55-generic      | 1        | 0.84%   |
| 5.8.0-48-generic      | 1        | 0.84%   |
| 5.8.0-43-generic      | 1        | 0.84%   |
| 5.8.0-29-lowlatency   | 1        | 0.84%   |
| 5.6.15-050615-generic | 1        | 0.84%   |
| 5.6.0-1052-oem        | 1        | 0.84%   |
| 5.4.30-dli            | 1        | 0.84%   |
| 5.4.0-96-generic      | 1        | 0.84%   |
| 5.4.0-91-generic      | 1        | 0.84%   |
| 5.4.0-89-generic      | 1        | 0.84%   |
| 5.4.0-88-generic      | 1        | 0.84%   |
| 5.4.0-81-generic      | 1        | 0.84%   |
| 5.4.0-75-generic      | 1        | 0.84%   |
| 5.4.0-70-lowlatency   | 1        | 0.84%   |
| 5.4.0-65-generic      | 1        | 0.84%   |
| 5.4.0-64-generic      | 1        | 0.84%   |
| 5.4.0-59-generic      | 1        | 0.84%   |
| 5.4.0-58-generic      | 1        | 0.84%   |
| 5.4.0-53-generic      | 1        | 0.84%   |
| 5.4.0-31-generic      | 1        | 0.84%   |
| 5.3.18-dli            | 1        | 0.84%   |
| 5.14.0-051400-generic | 1        | 0.84%   |
| 5.13.0-1008-intel     | 1        | 0.84%   |
| 5.11.0-46-generic     | 1        | 0.84%   |
| 5.11.0-40-generic     | 1        | 0.84%   |
| 5.11.0-37-generic     | 1        | 0.84%   |
| 5.11.0-36-generic     | 1        | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 68       | 60.18%  |
| 5.8.0   | 21       | 18.58%  |
| 5.11.0  | 16       | 14.16%  |
| 5.13.0  | 3        | 2.65%   |
| 5.6.15  | 1        | 0.88%   |
| 5.6.0   | 1        | 0.88%   |
| 5.4.30  | 1        | 0.88%   |
| 5.3.18  | 1        | 0.88%   |
| 5.14.0  | 1        | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 69       | 61.06%  |
| 5.8     | 21       | 18.58%  |
| 5.11    | 16       | 14.16%  |
| 5.13    | 3        | 2.65%   |
| 5.6     | 2        | 1.77%   |
| 5.3     | 1        | 0.88%   |
| 5.14    | 1        | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 112      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 106      | 94.64%  |
| LXDE       | 3        | 2.68%   |
| X-Cinnamon | 1        | 0.89%   |
| i3         | 1        | 0.89%   |
| GNOME      | 1        | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 105      | 93.75%  |
| Tty     | 6        | 5.36%   |
| Unknown | 1        | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 55       | 47.83%  |
| Unknown | 39       | 33.91%  |
| TDM     | 7        | 6.09%   |
| GDM     | 7        | 6.09%   |
| LightDM | 5        | 4.35%   |
| LXDM    | 1        | 0.87%   |
| GDM3    | 1        | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 30       | 26.79%  |
| fr_FR   | 13       | 11.61%  |
| pt_BR   | 9        | 8.04%   |
| it_IT   | 9        | 8.04%   |
| de_DE   | 8        | 7.14%   |
| C       | 6        | 5.36%   |
| ru_RU   | 5        | 4.46%   |
| en_GB   | 4        | 3.57%   |
| en_AU   | 4        | 3.57%   |
| ja_JP   | 3        | 2.68%   |
| hu_HU   | 2        | 1.79%   |
| es_ES   | 2        | 1.79%   |
| en_ZA   | 2        | 1.79%   |
| en_CA   | 2        | 1.79%   |
| cs_CZ   | 2        | 1.79%   |
| sv_SE   | 1        | 0.89%   |
| nl_NL   | 1        | 0.89%   |
| fi_FI   | 1        | 0.89%   |
| es_PE   | 1        | 0.89%   |
| es_MX   | 1        | 0.89%   |
| es_CR   | 1        | 0.89%   |
| es_CO   | 1        | 0.89%   |
| en_SG   | 1        | 0.89%   |
| el_GR   | 1        | 0.89%   |
| de_CH   | 1        | 0.89%   |
| Unknown | 1        | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 75       | 66.96%  |
| EFI  | 37       | 33.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 103      | 91.96%  |
| Overlay | 5        | 4.46%   |
| Xfs     | 2        | 1.79%   |
| F2fs    | 1        | 0.89%   |
| Btrfs   | 1        | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 42       | 37.17%  |
| MBR     | 39       | 34.51%  |
| GPT     | 32       | 28.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 85.71%  |
| Yes       | 16       | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 66.96%  |
| Yes       | 37       | 33.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 18.75%  |
| Hewlett-Packard     | 14       | 12.5%   |
| Dell                | 12       | 10.71%  |
| MSI                 | 11       | 9.82%   |
| Gigabyte Technology | 11       | 9.82%   |
| ASRock              | 10       | 8.93%   |
| Lenovo              | 7        | 6.25%   |
| Intel               | 5        | 4.46%   |
| Pegatron            | 3        | 2.68%   |
| Acer                | 3        | 2.68%   |
| Positivo            | 2        | 1.79%   |
| Foxconn             | 2        | 1.79%   |
| AAEON               | 2        | 1.79%   |
| ZOTAC               | 1        | 0.89%   |
| Packard Bell        | 1        | 0.89%   |
| IBM                 | 1        | 0.89%   |
| Huanan              | 1        | 0.89%   |
| HARDKERNEL          | 1        | 0.89%   |
| Fujitsu Siemens     | 1        | 0.89%   |
| Biostar             | 1        | 0.89%   |
| AMI                 | 1        | 0.89%   |
| Unknown             | 1        | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7B89                         | 2        | 1.79%   |
| HP Compaq 6000 Pro SFF PC           | 2        | 1.79%   |
| Dell OptiPlex 790                   | 2        | 1.79%   |
| ASRock N68-VS3 UCC                  | 2        | 1.79%   |
| AAEON MF-001                        | 2        | 1.79%   |
| ZOTAC NM10                          | 1        | 0.89%   |
| Positivo POS-MI945AA                | 1        | 0.89%   |
| Positivo POS-EIH61CE                | 1        | 0.89%   |
| Pegatron NC689AA-ABA s3700y         | 1        | 0.89%   |
| Pegatron FL308AA-ABD IQ512de        | 1        | 0.89%   |
| Pegatron AY652AA-ABA s5310y         | 1        | 0.89%   |
| Packard Bell imedia S1350           | 1        | 0.89%   |
| MSI MS-7C37                         | 1        | 0.89%   |
| MSI MS-7B86                         | 1        | 0.89%   |
| MSI MS-7994                         | 1        | 0.89%   |
| MSI MS-7846                         | 1        | 0.89%   |
| MSI MS-7680                         | 1        | 0.89%   |
| MSI MS-7592                         | 1        | 0.89%   |
| MSI MS-7309                         | 1        | 0.89%   |
| MSI ER883AA-ABA M7470N              | 1        | 0.89%   |
| MSI Compaq dx2200 MT                | 1        | 0.89%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 0.89%   |
| Lenovo ThinkCentre M93z 10AD002DMZ  | 1        | 0.89%   |
| Lenovo ThinkCentre M73 10AXS0HN00   | 1        | 0.89%   |
| Lenovo ThinkCentre M58p 7220W21     | 1        | 0.89%   |
| Lenovo ThinkCentre M58p 6136A66     | 1        | 0.89%   |
| Lenovo H50-50 90B60081IX            | 1        | 0.89%   |
| Lenovo H50-30g 90AS0002BR           | 1        | 0.89%   |
| Intel STK1AW32SC                    | 1        | 0.89%   |
| Intel H55                           | 1        | 0.89%   |
| Intel DN2800MT AAG23738-801         | 1        | 0.89%   |
| Intel DG31PR AAD97573-302           | 1        | 0.89%   |
| Intel ChiefRiver                    | 1        | 0.89%   |
| IBM eServer x3105 -[434722J]-       | 1        | 0.89%   |
| Huanan X99-TF                       | 1        | 0.89%   |
| HP Z230 Tower Workstation           | 1        | 0.89%   |
| HP xw9400 Workstation               | 1        | 0.89%   |
| HP xw9300 Workstation               | 1        | 0.89%   |
| HP t620 Quad Core TC                | 1        | 0.89%   |
| HP t620 Dual Core TC                | 1        | 0.89%   |
| HP ProDesk 600 G1 DM                | 1        | 0.89%   |
| HP EliteDesk 800 G3 SFF             | 1        | 0.89%   |
| HP Compaq Elite 8300 CMT            | 1        | 0.89%   |
| HP Compaq dc7800 Small Form Factor  | 1        | 0.89%   |
| HP Compaq dc7600 Small Form Factor  | 1        | 0.89%   |
| HP Compaq dc5800 Microtower         | 1        | 0.89%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 0.89%   |
| HARDKERNEL ODROID-H2                | 1        | 0.89%   |
| Gigabyte Z370P D3                   | 1        | 0.89%   |
| Gigabyte X570 GAMING X              | 1        | 0.89%   |
| Gigabyte K8M800-8237                | 1        | 0.89%   |
| Gigabyte H81M-DS2                   | 1        | 0.89%   |
| Gigabyte H61M-DS2H                  | 1        | 0.89%   |
| Gigabyte GA-870A-UD3                | 1        | 0.89%   |
| Gigabyte F2A88XM-HD3                | 1        | 0.89%   |
| Gigabyte B450M H                    | 1        | 0.89%   |
| Gigabyte B250M-D3H                  | 1        | 0.89%   |
| Gigabyte A520I AC                   | 1        | 0.89%   |
| Gigabyte 965P-DS3                   | 1        | 0.89%   |
| Fujitsu Siemens ESPRIMO P5925       | 1        | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 7        | 6.25%   |
| Dell OptiPlex           | 5        | 4.46%   |
| Lenovo ThinkCentre      | 4        | 3.57%   |
| Acer Aspire             | 3        | 2.68%   |
| MSI MS-7B89             | 2        | 1.79%   |
| HP t620                 | 2        | 1.79%   |
| ASRock N68-VS3          | 2        | 1.79%   |
| AAEON MF-001            | 2        | 1.79%   |
| ZOTAC NM10              | 1        | 0.89%   |
| Positivo POS-MI945AA    | 1        | 0.89%   |
| Positivo POS-EIH61CE    | 1        | 0.89%   |
| Pegatron NC689AA-ABA    | 1        | 0.89%   |
| Pegatron FL308AA-ABD    | 1        | 0.89%   |
| Pegatron AY652AA-ABA    | 1        | 0.89%   |
| Packard Bell imedia     | 1        | 0.89%   |
| MSI MS-7C37             | 1        | 0.89%   |
| MSI MS-7B86             | 1        | 0.89%   |
| MSI MS-7994             | 1        | 0.89%   |
| MSI MS-7846             | 1        | 0.89%   |
| MSI MS-7680             | 1        | 0.89%   |
| MSI MS-7592             | 1        | 0.89%   |
| MSI MS-7309             | 1        | 0.89%   |
| MSI ER883AA-ABA         | 1        | 0.89%   |
| MSI Compaq              | 1        | 0.89%   |
| Lenovo ThinkStation     | 1        | 0.89%   |
| Lenovo H50-50           | 1        | 0.89%   |
| Lenovo H50-30g          | 1        | 0.89%   |
| Intel STK1AW32SC        | 1        | 0.89%   |
| Intel H55               | 1        | 0.89%   |
| Intel DN2800MT          | 1        | 0.89%   |
| Intel DG31PR            | 1        | 0.89%   |
| Intel ChiefRiver        | 1        | 0.89%   |
| IBM eServer             | 1        | 0.89%   |
| Huanan X99-TF           | 1        | 0.89%   |
| HP Z230                 | 1        | 0.89%   |
| HP xw9400               | 1        | 0.89%   |
| HP xw9300               | 1        | 0.89%   |
| HP ProDesk              | 1        | 0.89%   |
| HP EliteDesk            | 1        | 0.89%   |
| HARDKERNEL ODROID-H2    | 1        | 0.89%   |
| Gigabyte Z370P          | 1        | 0.89%   |
| Gigabyte X570           | 1        | 0.89%   |
| Gigabyte K8M800-8237    | 1        | 0.89%   |
| Gigabyte H81M-DS2       | 1        | 0.89%   |
| Gigabyte H61M-DS2H      | 1        | 0.89%   |
| Gigabyte GA-870A-UD3    | 1        | 0.89%   |
| Gigabyte F2A88XM-HD3    | 1        | 0.89%   |
| Gigabyte B450M          | 1        | 0.89%   |
| Gigabyte B250M-D3H      | 1        | 0.89%   |
| Gigabyte A520I          | 1        | 0.89%   |
| Gigabyte 965P-DS3       | 1        | 0.89%   |
| Fujitsu Siemens ESPRIMO | 1        | 0.89%   |
| Foxconn WU115EA-AKB     | 1        | 0.89%   |
| Foxconn Pro             | 1        | 0.89%   |
| Dell XPS                | 1        | 0.89%   |
| Dell Vostro             | 1        | 0.89%   |
| Dell Studio             | 1        | 0.89%   |
| Dell Precision          | 1        | 0.89%   |
| Dell Inspiron           | 1        | 0.89%   |
| Dell DM061              | 1        | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 11       | 9.82%   |
| 2007 | 11       | 9.82%   |
| 2012 | 10       | 8.93%   |
| 2009 | 8        | 7.14%   |
| 2008 | 8        | 7.14%   |
| 2019 | 7        | 6.25%   |
| 2015 | 7        | 6.25%   |
| 2010 | 7        | 6.25%   |
| 2014 | 6        | 5.36%   |
| 2006 | 6        | 5.36%   |
| 2020 | 5        | 4.46%   |
| 2017 | 5        | 4.46%   |
| 2013 | 5        | 4.46%   |
| 2021 | 4        | 3.57%   |
| 2016 | 4        | 3.57%   |
| 2005 | 4        | 3.57%   |
| 2018 | 3        | 2.68%   |
| 2004 | 1        | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 112      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 109      | 97.32%  |
| Enabled  | 3        | 2.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 112      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 36       | 31.86%  |
| 8.01-16.0       | 17       | 15.04%  |
| 16.01-24.0      | 16       | 14.16%  |
| 1.01-2.0        | 16       | 14.16%  |
| 4.01-8.0        | 14       | 12.39%  |
| 32.01-64.0      | 8        | 7.08%   |
| 0.51-1.0        | 2        | 1.77%   |
| More than 256.0 | 1        | 0.88%   |
| 24.01-32.0      | 1        | 0.88%   |
| 2.01-3.0        | 1        | 0.88%   |
| 64.01-256.0     | 1        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 57       | 48.72%  |
| 2.01-3.0   | 21       | 17.95%  |
| 0.51-1.0   | 17       | 14.53%  |
| 4.01-8.0   | 12       | 10.26%  |
| 3.01-4.0   | 5        | 4.27%   |
| 8.01-16.0  | 2        | 1.71%   |
| 0.01-0.5   | 2        | 1.71%   |
| 16.01-24.0 | 1        | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 50%     |
| 2      | 36       | 32.14%  |
| 4      | 7        | 6.25%   |
| 3      | 6        | 5.36%   |
| 5      | 4        | 3.57%   |
| 14     | 1        | 0.89%   |
| 7      | 1        | 0.89%   |
| 0      | 1        | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 62.83%  |
| No        | 42       | 37.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 99.11%  |
| No        | 1        | 0.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 60.71%  |
| Yes       | 44       | 39.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 83.93%  |
| Yes       | 18       | 16.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 16       | 14.16%  |
| France       | 13       | 11.5%   |
| Germany      | 11       | 9.73%   |
| Brazil       | 10       | 8.85%   |
| Italy        | 9        | 7.96%   |
| Russia       | 5        | 4.42%   |
| Hungary      | 5        | 4.42%   |
| Switzerland  | 4        | 3.54%   |
| Australia    | 4        | 3.54%   |
| Spain        | 3        | 2.65%   |
| Netherlands  | 3        | 2.65%   |
| Japan        | 3        | 2.65%   |
| Czechia      | 3        | 2.65%   |
| South Africa | 2        | 1.77%   |
| Puerto Rico  | 2        | 1.77%   |
| Mexico       | 2        | 1.77%   |
| Greece       | 2        | 1.77%   |
| Finland      | 2        | 1.77%   |
| Canada       | 2        | 1.77%   |
| UK           | 1        | 0.88%   |
| Sweden       | 1        | 0.88%   |
| Slovenia     | 1        | 0.88%   |
| Singapore    | 1        | 0.88%   |
| Romania      | 1        | 0.88%   |
| Peru         | 1        | 0.88%   |
| New Zealand  | 1        | 0.88%   |
| Malaysia     | 1        | 0.88%   |
| Costa Rica   | 1        | 0.88%   |
| Colombia     | 1        | 0.88%   |
| Belgium      | 1        | 0.88%   |
| Belarus      | 1        | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Rome                  | 4        | 3.51%   |
| Windsor               | 2        | 1.75%   |
| Prague                | 2        | 1.75%   |
| Milan                 | 2        | 1.75%   |
| Eger                  | 2        | 1.75%   |
| Cuernavaca            | 2        | 1.75%   |
| Cayey                 | 2        | 1.75%   |
| Augsburg              | 2        | 1.75%   |
| Annecy                | 2        | 1.75%   |
| Zurich                | 1        | 0.88%   |
| Yelizovo              | 1        | 0.88%   |
| Wiesbaden             | 1        | 0.88%   |
| Wellington            | 1        | 0.88%   |
| Vlaardingen           | 1        | 0.88%   |
| Vitry-sur-Seine       | 1        | 0.88%   |
| Vaxjo                 | 1        | 0.88%   |
| Vanderbijlpark        | 1        | 0.88%   |
| Valls                 | 1        | 0.88%   |
| Valinhos              | 1        | 0.88%   |
| Valencia              | 1        | 0.88%   |
| Treviso               | 1        | 0.88%   |
| Tourcoing             | 1        | 0.88%   |
| Toronto               | 1        | 0.88%   |
| The Hague             | 1        | 0.88%   |
| Springfield           | 1        | 0.88%   |
| Spokane               | 1        | 0.88%   |
| Sora                  | 1        | 0.88%   |
| Singapore             | 1        | 0.88%   |
| Sandorfalva           | 1        | 0.88%   |
| Roseburg              | 1        | 0.88%   |
| Ronnenberg            | 1        | 0.88%   |
| Rio de Janeiro        | 1        | 0.88%   |
| Ramonville-Saint-Agne | 1        | 0.88%   |
| Raleigh               | 1        | 0.88%   |
| Portoro??             | 1        | 0.88%   |
| Porto Alegre          | 1        | 0.88%   |
| Portbail              | 1        | 0.88%   |
| Periers               | 1        | 0.88%   |
| P?©cs                 | 1        | 0.88%   |
| Passos                | 1        | 0.88%   |
| Pacatuba              | 1        | 0.88%   |
| Oradea                | 1        | 0.88%   |
| Omsk                  | 1        | 0.88%   |
| Oceanside             | 1        | 0.88%   |
| Novy Jicin            | 1        | 0.88%   |
| Neuchatel             | 1        | 0.88%   |
| Munich                | 1        | 0.88%   |
| Mount Waverley        | 1        | 0.88%   |
| Moscow                | 1        | 0.88%   |
| Moordrecht            | 1        | 0.88%   |
| Montross              | 1        | 0.88%   |
| Montlhery             | 1        | 0.88%   |
| Mogilev               | 1        | 0.88%   |
| Mobile                | 1        | 0.88%   |
| Menen                 | 1        | 0.88%   |
| Medell?­n             | 1        | 0.88%   |
| Marlow                | 1        | 0.88%   |
| Lovens                | 1        | 0.88%   |
| Le Mesnil-en-Thelle   | 1        | 0.88%   |
| Le Chevain            | 1        | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 54     | 25.88%  |
| WDC                 | 42       | 67     | 24.71%  |
| Samsung Electronics | 22       | 35     | 12.94%  |
| Kingston            | 8        | 8      | 4.71%   |
| Toshiba             | 7        | 7      | 4.12%   |
| Unknown             | 6        | 7      | 3.53%   |
| Hitachi             | 5        | 6      | 2.94%   |
| SanDisk             | 3        | 3      | 1.76%   |
| MAXTOR              | 3        | 3      | 1.76%   |
| China               | 3        | 3      | 1.76%   |
| A-DATA Technology   | 3        | 4      | 1.76%   |
| Team                | 2        | 2      | 1.18%   |
| PNY                 | 2        | 2      | 1.18%   |
| JMicron             | 2        | 2      | 1.18%   |
| Intel               | 2        | 2      | 1.18%   |
| Transcend           | 1        | 1      | 0.59%   |
| TO Exter            | 1        | 1      | 0.59%   |
| PNY USB             | 1        | 1      | 0.59%   |
| OCZ                 | 1        | 1      | 0.59%   |
| LONDISK             | 1        | 1      | 0.59%   |
| Lexar               | 1        | 1      | 0.59%   |
| Leven               | 1        | 2      | 0.59%   |
| LDLC                | 1        | 1      | 0.59%   |
| Intenso             | 1        | 1      | 0.59%   |
| HGST                | 1        | 1      | 0.59%   |
| Hewlett-Packard     | 1        | 6      | 0.59%   |
| GOODRAM             | 1        | 1      | 0.59%   |
| Fujitsu             | 1        | 1      | 0.59%   |
| External            | 1        | 1      | 0.59%   |
| Crucial             | 1        | 1      | 0.59%   |
| Corsair             | 1        | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 2.15%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 1.08%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 1.08%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 1.08%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 1.08%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 1.08%   |
| Unknown M52516  16GB                | 2        | 1.08%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 1.08%   |
| Seagate ST380815AS 80GB             | 2        | 1.08%   |
| Seagate ST3500418AS 500GB           | 2        | 1.08%   |
| Seagate ST3360320AS 360GB           | 2        | 1.08%   |
| Seagate ST3250410AS 250GB           | 2        | 1.08%   |
| Seagate ST3250310AS 250GB           | 2        | 1.08%   |
| Seagate ST31000528AS 1TB            | 2        | 1.08%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 1.08%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 1.08%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 1.08%   |
| Samsung SSD 850 EVO 250GB           | 2        | 1.08%   |
| Samsung HD161HJ 160GB               | 2        | 1.08%   |
| Samsung HD080HJ/ 80GB               | 2        | 1.08%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.08%   |
| China SATA SSD 512GB                | 2        | 1.08%   |
| A-DATA SU650 240GB SSD              | 2        | 1.08%   |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.54%   |
| WDC WD800JD-75JNA0 80GB             | 1        | 0.54%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.54%   |
| WDC WD7501AALS-00J7B1 752GB         | 1        | 0.54%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.54%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.54%   |
| WDC WD5000BPKX-66HPJT0 500GB        | 1        | 0.54%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.54%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.54%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.54%   |
| WDC WD50 00AAKS-00V1A 500GB         | 1        | 0.54%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.54%   |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.54%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.54%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1        | 0.54%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1        | 0.54%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.54%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 0.54%   |
| WDC WD2500JS-75NCB3 250GB           | 1        | 0.54%   |
| WDC WD2500JD-00HBB0 250GB           | 1        | 0.54%   |
| WDC WD2500AAKX-07U6AA0 250GB        | 1        | 0.54%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.54%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.54%   |
| WDC WD1600BB-00RDA0 160GB           | 1        | 0.54%   |
| WDC WD1600AAJS-60B4A0 160GB         | 1        | 0.54%   |
| WDC WD15EARS-22MVWB0 1TB            | 1        | 0.54%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1        | 0.54%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 0.54%   |
| WDC WD10EAVS-14M4B0 1TB             | 1        | 0.54%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 0.54%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 54     | 40%     |
| WDC                 | 37       | 58     | 33.64%  |
| Samsung Electronics | 11       | 12     | 10%     |
| Toshiba             | 5        | 5      | 4.55%   |
| Hitachi             | 5        | 6      | 4.55%   |
| MAXTOR              | 3        | 3      | 2.73%   |
| Unknown             | 1        | 1      | 0.91%   |
| TO Exter            | 1        | 1      | 0.91%   |
| HGST                | 1        | 1      | 0.91%   |
| Fujitsu             | 1        | 1      | 0.91%   |
| External            | 1        | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 17.65%  |
| Kingston            | 8        | 8      | 15.69%  |
| WDC                 | 7        | 9      | 13.73%  |
| SanDisk             | 3        | 3      | 5.88%   |
| China               | 3        | 3      | 5.88%   |
| Toshiba             | 2        | 2      | 3.92%   |
| Team                | 2        | 2      | 3.92%   |
| PNY                 | 2        | 2      | 3.92%   |
| A-DATA Technology   | 2        | 3      | 3.92%   |
| Transcend           | 1        | 1      | 1.96%   |
| PNY USB             | 1        | 1      | 1.96%   |
| OCZ                 | 1        | 1      | 1.96%   |
| LONDISK             | 1        | 1      | 1.96%   |
| Lexar               | 1        | 1      | 1.96%   |
| Leven               | 1        | 2      | 1.96%   |
| LDLC                | 1        | 1      | 1.96%   |
| Intenso             | 1        | 1      | 1.96%   |
| Intel               | 1        | 1      | 1.96%   |
| Hewlett-Packard     | 1        | 6      | 1.96%   |
| GOODRAM             | 1        | 1      | 1.96%   |
| Crucial             | 1        | 1      | 1.96%   |
| Corsair             | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 83       | 143    | 58.04%  |
| SSD     | 49       | 63     | 34.27%  |
| MMC     | 5        | 6      | 3.5%    |
| NVMe    | 5        | 14     | 3.5%    |
| Unknown | 1        | 1      | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 104      | 198    | 86.67%  |
| SAS  | 7        | 10     | 5.83%   |
| MMC  | 5        | 6      | 4.17%   |
| NVMe | 4        | 13     | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 85       | 127    | 63.43%  |
| 0.51-1.0   | 36       | 55     | 26.87%  |
| 1.01-2.0   | 5        | 8      | 3.73%   |
| 3.01-4.0   | 4        | 12     | 2.99%   |
| 2.01-3.0   | 3        | 3      | 2.24%   |
| 4.01-10.0  | 1        | 1      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 30       | 26.55%  |
| 251-500        | 23       | 20.35%  |
| 1001-2000      | 13       | 11.5%   |
| 501-1000       | 13       | 11.5%   |
| More than 3000 | 10       | 8.85%   |
| 51-100         | 9        | 7.96%   |
| 2001-3000      | 6        | 5.31%   |
| 1-20           | 5        | 4.42%   |
| 21-50          | 3        | 2.65%   |
| Unknown        | 1        | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 43       | 37.72%  |
| 21-50          | 18       | 15.79%  |
| 101-250        | 14       | 12.28%  |
| 251-500        | 8        | 7.02%   |
| 501-1000       | 8        | 7.02%   |
| 51-100         | 8        | 7.02%   |
| 1001-2000      | 7        | 6.14%   |
| More than 3000 | 4        | 3.51%   |
| 2001-3000      | 3        | 2.63%   |
| Unknown        | 1        | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB  | 2        | 2      | 10%     |
| WDC WD5000AAKX-003CA0 500GB     | 1        | 1      | 5%      |
| WDC WD400EB-00CPF0 40GB         | 1        | 1      | 5%      |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 2      | 5%      |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 5%      |
| Seagate ST380815AS 80GB         | 1        | 1      | 5%      |
| Seagate ST3360320AS 360GB       | 1        | 1      | 5%      |
| Seagate ST3160318AS 160GB       | 1        | 1      | 5%      |
| Seagate ST2000DX002-2DV164 2TB  | 1        | 1      | 5%      |
| Seagate ST1000DX001-1CM162 1TB  | 1        | 1      | 5%      |
| Seagate ST1000DM003-1ER162 1TB  | 1        | 1      | 5%      |
| MAXTOR STM3300622A 304GB        | 1        | 1      | 5%      |
| MAXTOR 6Y080L0 82GB             | 1        | 1      | 5%      |
| MAXTOR 6B200M0 208GB            | 1        | 1      | 5%      |
| LDLC SSD 120GB                  | 1        | 1      | 5%      |
| Kingston SHFS37A120G 120GB SSD  | 1        | 1      | 5%      |
| Kingston SA400S37120G 120GB SSD | 1        | 1      | 5%      |
| Hitachi HCP725050GLAT80 500GB   | 1        | 1      | 5%      |
| Fujitsu MHZ2160BH G2 160GB      | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 9        | 9      | 45%     |
| WDC      | 3        | 4      | 15%     |
| MAXTOR   | 3        | 3      | 15%     |
| Kingston | 2        | 2      | 10%     |
| LDLC     | 1        | 1      | 5%      |
| Hitachi  | 1        | 1      | 5%      |
| Fujitsu  | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 9      | 52.94%  |
| WDC     | 3        | 4      | 17.65%  |
| MAXTOR  | 3        | 3      | 17.65%  |
| Hitachi | 1        | 1      | 5.88%   |
| Fujitsu | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 18     | 84.21%  |
| SSD  | 3        | 3      | 15.79%  |

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
| Works    | 58       | 117    | 45.67%  |
| Detected | 50       | 88     | 39.37%  |
| Malfunc  | 18       | 21     | 14.17%  |
| Failed   | 1        | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 69       | 55.65%  |
| AMD                       | 23       | 18.55%  |
| Nvidia                    | 14       | 11.29%  |
| JMicron Technology        | 5        | 4.03%   |
| Marvell Technology Group  | 4        | 3.23%   |
| VIA Technologies          | 2        | 1.61%   |
| Samsung Electronics       | 2        | 1.61%   |
| LSI Logic / Symbios Logic | 2        | 1.61%   |
| ASMedia Technology        | 2        | 1.61%   |
| ADATA Technology          | 1        | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 8.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 5.08%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 3.39%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 3.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.39%   |
| Nvidia MCP61 IDE                                                                        | 5        | 2.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.82%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.26%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.26%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.26%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.69%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.69%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 1.13%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.13%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.13%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.13%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.13%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 1.13%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 1.13%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.13%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.56%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.56%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.56%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.56%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.56%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.56%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.56%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.56%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.56%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.56%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.56%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.56%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.56%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.56%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.56%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.56%   |
| Intel SSD 660P Series                                                                   | 1        | 0.56%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.56%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.56%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 64       | 50.39%  |
| IDE  | 52       | 40.94%  |
| RAID | 5        | 3.94%   |
| NVMe | 4        | 3.15%   |
| SCSI | 2        | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 76       | 67.86%  |
| AMD    | 36       | 32.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.68%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.68%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.68%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.79%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.79%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 1.79%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.79%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.79%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.79%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.79%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 2        | 1.79%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.89%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.89%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.89%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.89%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.89%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.89%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.89%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.89%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.89%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.89%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.89%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.89%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.89%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.89%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.89%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.89%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.89%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.89%   |
| Intel Core i5-4440S CPU @ 2.80GHz           | 1        | 0.89%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.89%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 0.89%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 0.89%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.89%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 0.89%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.89%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.89%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.89%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 0.89%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 0.89%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.89%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 0.89%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 0.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 0.89%   |
| Intel Core 2 Quad CPU @ 2.40GHz             | 1        | 0.89%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E6850 @ 3.00GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 0.89%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 0.89%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 17.86%  |
| Intel Core 2 Duo        | 11       | 9.82%   |
| Intel Core i3           | 7        | 6.25%   |
| Intel Atom              | 7        | 6.25%   |
| AMD Ryzen 5             | 6        | 5.36%   |
| Intel Core i7           | 5        | 4.46%   |
| Intel Celeron           | 5        | 4.46%   |
| AMD Athlon 64 X2        | 5        | 4.46%   |
| Intel Xeon              | 4        | 3.57%   |
| Intel Core 2 Quad       | 4        | 3.57%   |
| Intel Core 2            | 4        | 3.57%   |
| AMD Athlon II X2        | 4        | 3.57%   |
| Intel Pentium Dual-Core | 3        | 2.68%   |
| AMD Ryzen 7             | 3        | 2.68%   |
| AMD Athlon 64           | 3        | 2.68%   |
| AMD A10                 | 3        | 2.68%   |
| Intel Pentium Dual      | 2        | 1.79%   |
| Intel Pentium 4         | 2        | 1.79%   |
| AMD Sempron             | 2        | 1.79%   |
| AMD GX                  | 2        | 1.79%   |
| Intel Pentium Gold      | 1        | 0.89%   |
| Intel Pentium           | 1        | 0.89%   |
| AMD Ryzen Threadripper  | 1        | 0.89%   |
| AMD Quad-Core Opteron   | 1        | 0.89%   |
| AMD Phenom II X3        | 1        | 0.89%   |
| AMD Opteron             | 1        | 0.89%   |
| AMD FX                  | 1        | 0.89%   |
| AMD E                   | 1        | 0.89%   |
| AMD Athlon X4           | 1        | 0.89%   |
| AMD Athlon II X4        | 1        | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 54       | 48.21%  |
| 4      | 34       | 30.36%  |
| 6      | 8        | 7.14%   |
| 1      | 8        | 7.14%   |
| 8      | 5        | 4.46%   |
| 64     | 1        | 0.89%   |
| 12     | 1        | 0.89%   |
| 3      | 1        | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 110      | 98.21%  |
| 2      | 2        | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 73       | 65.18%  |
| 2      | 39       | 34.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 112      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 14.29%  |
| 0x206a7    | 12       | 10.71%  |
| 0x306c3    | 8        | 7.14%   |
| 0x1067a    | 8        | 7.14%   |
| 0x906e9    | 4        | 3.57%   |
| 0x6fd      | 4        | 3.57%   |
| 0x6fb      | 3        | 2.68%   |
| 0x6f6      | 3        | 2.68%   |
| 0x406c4    | 3        | 2.68%   |
| 0x306a9    | 3        | 2.68%   |
| 0x10676    | 3        | 2.68%   |
| 0x08701021 | 3        | 2.68%   |
| 0x06001119 | 3        | 2.68%   |
| 0x010000c8 | 3        | 2.68%   |
| 0x506e3    | 2        | 1.79%   |
| 0x20655    | 2        | 1.79%   |
| 0x106ca    | 2        | 1.79%   |
| 0x08701013 | 2        | 1.79%   |
| 0x0800820d | 2        | 1.79%   |
| 0x0700010f | 2        | 1.79%   |
| 0xf65      | 1        | 0.89%   |
| 0xf4a      | 1        | 0.89%   |
| 0xa0655    | 1        | 0.89%   |
| 0xa0653    | 1        | 0.89%   |
| 0x906ea    | 1        | 0.89%   |
| 0x706a1    | 1        | 0.89%   |
| 0x6f7      | 1        | 0.89%   |
| 0x6f2      | 1        | 0.89%   |
| 0x406c3    | 1        | 0.89%   |
| 0x306f2    | 1        | 0.89%   |
| 0x306e4    | 1        | 0.89%   |
| 0x30678    | 1        | 0.89%   |
| 0x30661    | 1        | 0.89%   |
| 0x206d7    | 1        | 0.89%   |
| 0x106e5    | 1        | 0.89%   |
| 0x10677    | 1        | 0.89%   |
| 0x0a50000c | 1        | 0.89%   |
| 0x0830104d | 1        | 0.89%   |
| 0x06003106 | 1        | 0.89%   |
| 0x06000852 | 1        | 0.89%   |
| 0x05000119 | 1        | 0.89%   |
| 0x010000db | 1        | 0.89%   |
| 0x010000c7 | 1        | 0.89%   |
| 0x01000095 | 1        | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 13       | 11.61%  |
| Penryn        | 12       | 10.71%  |
| Core          | 12       | 10.71%  |
| K8 Hammer     | 10       | 8.93%   |
| Haswell       | 10       | 8.93%   |
| K10           | 8        | 7.14%   |
| Zen 2         | 6        | 5.36%   |
| Silvermont    | 5        | 4.46%   |
| KabyLake      | 5        | 4.46%   |
| Piledriver    | 4        | 3.57%   |
| IvyBridge     | 4        | 3.57%   |
| Zen+          | 3        | 2.68%   |
| Skylake       | 3        | 2.68%   |
| CometLake     | 3        | 2.68%   |
| Bonnell       | 3        | 2.68%   |
| Westmere      | 2        | 1.79%   |
| NetBurst      | 2        | 1.79%   |
| Jaguar        | 2        | 1.79%   |
| Zen 3         | 1        | 0.89%   |
| Steamroller   | 1        | 0.89%   |
| Nehalem       | 1        | 0.89%   |
| Goldmont plus | 1        | 0.89%   |
| Bobcat        | 1        | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 41       | 35.34%  |
| Intel  | 39       | 33.62%  |
| AMD    | 36       | 31.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 7.38%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 3.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 3.28%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 4        | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 3.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 3.28%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.46%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.46%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.46%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 2.46%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.64%   |
| Intel HD Graphics 530                                                                    | 2        | 1.64%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.64%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.64%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.64%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.64%   |
| AMD Richland [Radeon HD 8670D]                                                           | 2        | 1.64%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.82%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.82%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.82%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.82%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.82%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.82%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.82%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.82%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.82%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.82%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.82%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.82%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 0.82%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.82%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.82%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.82%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.82%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.82%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.82%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1        | 0.82%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.82%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.82%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.82%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 0.82%   |
| Intel HD Graphics 630                                                                    | 1        | 0.82%   |
| Intel HD Graphics 610                                                                    | 1        | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.82%   |
| Intel Comet Lake UHD Graphics                                                            | 1        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.82%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.82%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.82%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 0.82%   |
| AMD Turks [Radeon HD 7600 Series]                                                        | 1        | 0.82%   |
| AMD RV770 [Radeon HD 4850]                                                               | 1        | 0.82%   |
| AMD RV710 [Radeon HD 4550]                                                               | 1        | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 38       | 33.63%  |
| 1 x Intel    | 38       | 33.63%  |
| 1 x AMD      | 31       | 27.43%  |
| 2 x AMD      | 4        | 3.54%   |
| 2 x Nvidia   | 1        | 0.88%   |
| AMD + Nvidia | 1        | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 89       | 79.46%  |
| Proprietary | 22       | 19.64%  |
| Unknown     | 1        | 0.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 38.94%  |
| 0.01-0.5   | 28       | 24.78%  |
| 0.51-1.0   | 17       | 15.04%  |
| 1.01-2.0   | 12       | 10.62%  |
| 3.01-4.0   | 6        | 5.31%   |
| 7.01-8.0   | 3        | 2.65%   |
| 8.01-16.0  | 2        | 1.77%   |
| 2.01-3.0   | 1        | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 15       | 13.39%  |
| Samsung Electronics     | 13       | 11.61%  |
| Goldstar                | 13       | 11.61%  |
| Acer                    | 9        | 8.04%   |
| Hewlett-Packard         | 8        | 7.14%   |
| Lenovo                  | 5        | 4.46%   |
| Vizio                   | 4        | 3.57%   |
| Philips                 | 4        | 3.57%   |
| Ancor Communications    | 4        | 3.57%   |
| Unknown                 | 3        | 2.68%   |
| Iiyama                  | 3        | 2.68%   |
| BenQ                    | 3        | 2.68%   |
| AOC                     | 3        | 2.68%   |
| Sony                    | 2        | 1.79%   |
| LG Electronics          | 2        | 1.79%   |
| ___                     | 1        | 0.89%   |
| Unknown (ADA)           | 1        | 0.89%   |
| Sceptre Tech            | 1        | 0.89%   |
| Plain Tree Systems      | 1        | 0.89%   |
| NEC Computers           | 1        | 0.89%   |
| MOT                     | 1        | 0.89%   |
| Lite-On                 | 1        | 0.89%   |
| LG Display              | 1        | 0.89%   |
| Lenovo Group Limited    | 1        | 0.89%   |
| IOD                     | 1        | 0.89%   |
| IBM                     | 1        | 0.89%   |
| Hitachi                 | 1        | 0.89%   |
| HannStar                | 1        | 0.89%   |
| GDH                     | 1        | 0.89%   |
| Fujitsu Siemens         | 1        | 0.89%   |
| Element                 | 1        | 0.89%   |
| Eizo                    | 1        | 0.89%   |
| CVT                     | 1        | 0.89%   |
| Compaq Computer         | 1        | 0.89%   |
| Chi Mei Optoelectronics | 1        | 0.89%   |
| Arnos Instruments       | 1        | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 1.71%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 1.71%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 1.71%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                     | 2        | 1.71%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 1.71%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.85%   |
| ___ LCDTV16 ___0101 1360x768                                          | 1        | 0.85%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1        | 0.85%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 1        | 0.85%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                    | 1        | 0.85%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                    | 1        | 0.85%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.85%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.85%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.85%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.85%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.85%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.85%   |
| Sony TV SNYAA01 1920x1080 880x490mm 39.7-inch                         | 1        | 0.85%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.85%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1        | 0.85%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x290mm 23.1-inch  | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1        | 0.85%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.85%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                   | 1        | 0.85%   |
| Plain Tree Systems FULL HDTV PTS00EC 1920x1080 520x290mm 23.4-inch    | 1        | 0.85%   |
| Philips PHL 322M7C PHLC194 1920x1080 698x393mm 31.5-inch              | 1        | 0.85%   |
| Philips 271P4 PHL08C3 1920x1080 597x336mm 27.0-inch                   | 1        | 0.85%   |
| Philips 190B PHL081A 1280x1024 376x301mm 19.0-inch                    | 1        | 0.85%   |
| Philips 170C5 PHLC00B 1280x1024 338x270mm 17.0-inch                   | 1        | 0.85%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 340x270mm 17.1-inch         | 1        | 0.85%   |
| MOT MotoAttach MOT3DC4 1366x768 260x140mm 11.6-inch                   | 1        | 0.85%   |
| Lite-On GC150AT/ATA LTN020E 1024x768 304x228mm 15.0-inch              | 1        | 0.85%   |
| LG Electronics LCD Monitor W2220                                      | 1        | 0.85%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 0.85%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 1        | 0.85%   |
| Lenovo LEN-E92I-C LEN0093 1920x1080 509x286mm 23.0-inch               | 1        | 0.85%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1        | 0.85%   |
| Lenovo LEN L1700pC LEN24C9 1280x1024 338x270mm 17.0-inch              | 1        | 0.85%   |
| Lenovo Group Limited LCD Monitor LEN L24q-30 1920x1200                | 1        | 0.85%   |
| IOD EX-LD2381D IOD180C 1920x1080 530x300mm 24.0-inch                  | 1        | 0.85%   |
| IOD DIOS-MF241X IOD180A 1920x1080 530x300mm 24.0-inch                 | 1        | 0.85%   |
| Iiyama PL2792H IVM6638 1920x1080 600x340mm 27.2-inch                  | 1        | 0.85%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                  | 1        | 0.85%   |
| Iiyama PL2006W IVM539A 1680x1050 430x240mm 19.4-inch                  | 1        | 0.85%   |
| IBM L150 IBM19EC 1024x768 304x228mm 15.0-inch                         | 1        | 0.85%   |
| Hitachi X224W D-sub HIT700B 1680x1050 473x296mm 22.0-inch             | 1        | 0.85%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch         | 1        | 0.85%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 0.85%   |
| Hewlett-Packard LCD Monitor LA1951 1280x1024                          | 1        | 0.85%   |
| Hewlett-Packard LCD Monitor E241i 3600x1200                           | 1        | 0.85%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 337x270mm 17.0-inch           | 1        | 0.85%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 1        | 0.85%   |
| Hewlett-Packard Compaq W220q HWP2809 1680x1050 473x296mm 22.0-inch    | 1        | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 30.09%  |
| 1280x1024 (SXGA)   | 22       | 19.47%  |
| 1680x1050 (WSXGA+) | 12       | 10.62%  |
| 1366x768 (WXGA)    | 9        | 7.96%   |
| 1440x900 (WXGA+)   | 7        | 6.19%   |
| 2560x1440 (QHD)    | 6        | 5.31%   |
| 1024x768 (XGA)     | 5        | 4.42%   |
| 1600x900 (HD+)     | 3        | 2.65%   |
| 3840x2160 (4K)     | 2        | 1.77%   |
| 2560x1080          | 2        | 1.77%   |
| 1920x1200 (WUXGA)  | 2        | 1.77%   |
| 1280x800 (WXGA)    | 2        | 1.77%   |
| 3600x1200          | 1        | 0.88%   |
| 3440x1440          | 1        | 0.88%   |
| 2560x1600          | 1        | 0.88%   |
| 2288x1287          | 1        | 0.88%   |
| 1600x1200          | 1        | 0.88%   |
| 1360x768           | 1        | 0.88%   |
| Unknown            | 1        | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 15       | 13.27%  |
| 19      | 12       | 10.62%  |
| 27      | 10       | 8.85%   |
| 24      | 10       | 8.85%   |
| 23      | 10       | 8.85%   |
| Unknown | 9        | 7.96%   |
| 21      | 8        | 7.08%   |
| 22      | 7        | 6.19%   |
| 20      | 6        | 5.31%   |
| 15      | 6        | 5.31%   |
| 18      | 4        | 3.54%   |
| 41      | 2        | 1.77%   |
| 39      | 2        | 1.77%   |
| 34      | 2        | 1.77%   |
| 31      | 2        | 1.77%   |
| 72      | 1        | 0.88%   |
| 38      | 1        | 0.88%   |
| 37      | 1        | 0.88%   |
| 32      | 1        | 0.88%   |
| 29      | 1        | 0.88%   |
| 14      | 1        | 0.88%   |
| 11      | 1        | 0.88%   |
| 7       | 1        | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 30       | 27.03%  |
| 401-500     | 28       | 25.23%  |
| 301-350     | 20       | 18.02%  |
| 351-400     | 9        | 8.11%   |
| Unknown     | 9        | 8.11%   |
| 801-900     | 4        | 3.6%    |
| 701-800     | 3        | 2.7%    |
| 601-700     | 3        | 2.7%    |
| 901-1000    | 2        | 1.8%    |
| 201-300     | 1        | 0.9%    |
| 1501-2000   | 1        | 0.9%    |
| 101-200     | 1        | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 51       | 47.66%  |
| 5/4     | 20       | 18.69%  |
| 16/10   | 17       | 15.89%  |
| Unknown | 8        | 7.48%   |
| 4/3     | 5        | 4.67%   |
| 21/9    | 3        | 2.8%    |
| 6/5     | 2        | 1.87%   |
| 3/2     | 1        | 0.93%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 29       | 26.13%  |
| 151-200        | 20       | 18.02%  |
| 141-150        | 17       | 15.32%  |
| 301-350        | 11       | 9.91%   |
| Unknown        | 9        | 8.11%   |
| 101-110        | 6        | 5.41%   |
| 501-1000       | 6        | 5.41%   |
| 351-500        | 5        | 4.5%    |
| 251-300        | 3        | 2.7%    |
| More than 1000 | 1        | 0.9%    |
| 81-90          | 1        | 0.9%    |
| 51-60          | 1        | 0.9%    |
| 1-40           | 1        | 0.9%    |
| 131-140        | 1        | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 73       | 69.52%  |
| 101-120 | 14       | 13.33%  |
| Unknown | 9        | 8.57%   |
| 121-160 | 5        | 4.76%   |
| 1-50    | 2        | 1.9%    |
| 161-240 | 2        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 96       | 85.71%  |
| 2     | 10       | 8.93%   |
| 0     | 4        | 3.57%   |
| 4     | 1        | 0.89%   |
| 3     | 1        | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 62       | 40%     |
| Intel                    | 39       | 25.16%  |
| Nvidia                   | 12       | 7.74%   |
| Qualcomm Atheros         | 9        | 5.81%   |
| Ralink Technology        | 8        | 5.16%   |
| Ralink                   | 4        | 2.58%   |
| Broadcom                 | 4        | 2.58%   |
| Marvell Technology Group | 3        | 1.94%   |
| TP-Link                  | 2        | 1.29%   |
| Samsung Electronics      | 2        | 1.29%   |
| Broadcom Limited         | 2        | 1.29%   |
| ZyXEL Communications     | 1        | 0.65%   |
| VIA Technologies         | 1        | 0.65%   |
| U-Blox                   | 1        | 0.65%   |
| Sitecom Europe           | 1        | 0.65%   |
| NetGear                  | 1        | 0.65%   |
| Huawei Technologies      | 1        | 0.65%   |
| Aquantia                 | 1        | 0.65%   |
| ADMtek                   | 1        | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 25.6%   |
| Nvidia MCP61 Ethernet                                             | 6        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.98%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.79%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.19%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 1.19%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.19%   |
| Ralink RT5572 Wireless Adapter                                    | 2        | 1.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.19%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.19%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.19%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.19%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.19%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.19%   |
| Intel Wireless-AC 9260                                            | 2        | 1.19%   |
| Intel Wireless 7260                                               | 2        | 1.19%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.19%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.6%    |
| U-Blox GNSS receiver                                              | 1        | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.6%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.6%    |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.6%    |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.6%    |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.6%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.6%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.6%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 0.6%    |
| Nvidia MCP73 Ethernet                                             | 1        | 0.6%    |
| Nvidia MCP67 Ethernet                                             | 1        | 0.6%    |
| Nvidia MCP55 Ethernet                                             | 1        | 0.6%    |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.6%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 0.6%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.6%    |
| Intel Wireless 7265                                               | 1        | 0.6%    |
| Intel Wireless 3165                                               | 1        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 26.67%  |
| Intel                 | 9        | 20%     |
| Ralink Technology     | 8        | 17.78%  |
| Qualcomm Atheros      | 6        | 13.33%  |
| Ralink                | 4        | 8.89%   |
| TP-Link               | 2        | 4.44%   |
| ZyXEL Communications  | 1        | 2.22%   |
| Sitecom Europe        | 1        | 2.22%   |
| NetGear               | 1        | 2.22%   |
| Broadcom              | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 11.11%  |
| Realtek RTL8187 Wireless Adapter                               | 2        | 4.44%   |
| Ralink RT5572 Wireless Adapter                                 | 2        | 4.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 4.44%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 4.44%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 4.44%   |
| Intel Wireless-AC 9260                                         | 2        | 4.44%   |
| Intel Wireless 7260                                            | 2        | 4.44%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 2.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 2.22%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 2.22%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 2.22%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 2.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 2.22%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 2.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 2.22%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 2.22%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 2.22%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 2.22%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 2.22%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 2.22%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1        | 2.22%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 2.22%   |
| Intel Wireless 7265                                            | 1        | 2.22%   |
| Intel Wireless 3165                                            | 1        | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.22%   |
| Intel Centrino Advanced-N 6235                                 | 1        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 54       | 46.55%  |
| Intel                    | 32       | 27.59%  |
| Nvidia                   | 12       | 10.34%  |
| Broadcom                 | 4        | 3.45%   |
| Qualcomm Atheros         | 3        | 2.59%   |
| Marvell Technology Group | 3        | 2.59%   |
| Samsung Electronics      | 2        | 1.72%   |
| Broadcom Limited         | 2        | 1.72%   |
| VIA Technologies         | 1        | 0.86%   |
| Huawei Technologies      | 1        | 0.86%   |
| Aquantia                 | 1        | 0.86%   |
| ADMtek                   | 1        | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 35.25%  |
| Nvidia MCP61 Ethernet                                             | 6        | 4.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 4.1%    |
| Intel Ethernet Connection (2) I219-V                              | 5        | 4.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 3.28%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.46%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.64%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.64%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.64%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.82%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.82%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.82%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.82%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.82%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.82%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.82%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.82%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.82%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.82%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.82%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.82%   |
| Huawei SNE-LX1                                                    | 1        | 0.82%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.82%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.82%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.82%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.82%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 0.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.82%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 71.15%  |
| WiFi     | 44       | 28.21%  |
| Modem    | 1        | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 104      | 77.61%  |
| WiFi     | 30       | 22.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 82       | 73.21%  |
| 2     | 25       | 22.32%  |
| 3     | 4        | 3.57%   |
| 0     | 1        | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 94       | 83.19%  |
| Yes  | 19       | 16.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 44.44%  |
| Cambridge Silicon Radio | 6        | 33.33%  |
| Broadcom                | 3        | 16.67%  |
| Hewlett-Packard         | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 33.33%  |
| Intel Bluetooth Device                              | 4        | 22.22%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 11.11%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 5.56%   |
| Intel AX210 Bluetooth                               | 1        | 5.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 5.56%   |
| Broadcom Bluetooth Device                           | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 68       | 41.72%  |
| Nvidia                   | 40       | 24.54%  |
| AMD                      | 36       | 22.09%  |
| Creative Labs            | 4        | 2.45%   |
| C-Media Electronics      | 4        | 2.45%   |
| XMOS                     | 2        | 1.23%   |
| Logitech                 | 2        | 1.23%   |
| VIA Technologies         | 1        | 0.61%   |
| Unknown                  | 1        | 0.61%   |
| GN Netcom                | 1        | 0.61%   |
| Focusrite-Novation       | 1        | 0.61%   |
| Creative Technology      | 1        | 0.61%   |
| BEHRINGER International  | 1        | 0.61%   |
| Asahi Kasei Microsystems | 1        | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller              | 11       | 5.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                 | 10       | 5.38%   |
| Nvidia High Definition Audio Controller                                                 | 9        | 4.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                     | 7        | 3.76%   |
| Nvidia MCP61 High Definition Audio                                                      | 6        | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                          | 6        | 3.23%   |
| AMD FCH Azalia Controller                                                               | 6        | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                        | 5        | 2.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                         | 5        | 2.69%   |
| AMD Starship/Matisse HD Audio Controller                                                | 5        | 2.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                            | 5        | 2.69%   |
| Nvidia GP107GL High Definition Audio Controller                                         | 4        | 2.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                     | 4        | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                          | 4        | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                     | 4        | 2.15%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                  | 4        | 2.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                           | 3        | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                   | 3        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                | 3        | 1.61%   |
| Intel 200 Series PCH HD Audio                                                           | 3        | 1.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]       | 3        | 1.61%   |
| XMOS Mayfield Audio                                                                     | 2        | 1.08%   |
| Nvidia GK107 HDMI Audio Controller                                                      | 2        | 1.08%   |
| Nvidia GK106 HDMI Audio Controller                                                      | 2        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                           | 2        | 1.08%   |
| Nvidia CK804 AC'97 Audio Controller                                                     | 2        | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                                       | 2        | 1.08%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                              | 2        | 1.08%   |
| AMD Trinity HDMI Audio Controller                                                       | 2        | 1.08%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                        | 2        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                 | 2        | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                | 2        | 1.08%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                          | 2        | 1.08%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                     | 2        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                     | 2        | 1.08%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                      | 1        | 0.54%   |
| Unknown Realtek USB Audio Rear                                                          | 1        | 0.54%   |
| Unknown Realtek USB Audio Front                                                         | 1        | 0.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                          | 1        | 0.54%   |
| Nvidia TU104 HD Audio Controller                                                        | 1        | 0.54%   |
| Nvidia TU102 High Definition Audio Controller                                           | 1        | 0.54%   |
| Nvidia MCP73 High Definition Audio                                                      | 1        | 0.54%   |
| Nvidia MCP67 High Definition Audio                                                      | 1        | 0.54%   |
| Nvidia MCP51 High Definition Audio                                                      | 1        | 0.54%   |
| Nvidia GM206 High Definition Audio Controller                                           | 1        | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                                           | 1        | 0.54%   |
| Nvidia GK104 HDMI Audio Controller                                                      | 1        | 0.54%   |
| Nvidia GF116 High Definition Audio Controller                                           | 1        | 0.54%   |
| Logitech Headset H390                                                                   | 1        | 0.54%   |
| Logitech EasyCall Speakerphone                                                          | 1        | 0.54%   |
| Intel Comet Lake PCH-V cAVS                                                             | 1        | 0.54%   |
| Intel Comet Lake PCH cAVS                                                               | 1        | 0.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                            | 1        | 0.54%   |
| Intel C610/X99 series chipset HD Audio Controller                                       | 1        | 0.54%   |
| Intel C600/X79 series chipset High Definition Audio Controller                          | 1        | 0.54%   |
| Intel Audio device                                                                      | 1        | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio | 1        | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller              | 1        | 0.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                        | 1        | 0.54%   |
| GN Netcom Jabra EVOLVE Link MS                                                          | 1        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 19.05%  |
| Samsung Electronics | 15       | 17.86%  |
| SK Hynix            | 13       | 15.48%  |
| Kingston            | 8        | 9.52%   |
| Crucial             | 6        | 7.14%   |
| Micron Technology   | 5        | 5.95%   |
| Corsair             | 5        | 5.95%   |
| Nanya Technology    | 3        | 3.57%   |
| G.Skill             | 3        | 3.57%   |
| Patriot             | 2        | 2.38%   |
| Unknown (ABCD)      | 1        | 1.19%   |
| Unifosa             | 1        | 1.19%   |
| TIMETEC             | 1        | 1.19%   |
| Team                | 1        | 1.19%   |
| Ramaxel Technology  | 1        | 1.19%   |
| Qimonda             | 1        | 1.19%   |
| e2e4                | 1        | 1.19%   |
| 48spaces            | 1        | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 3        | 3.26%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 2        | 2.17%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 2        | 2.17%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 2        | 2.17%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                   | 1        | 1.09%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1        | 1.09%   |
| Unknown RAM Module 512MB DIMM 333MT/s                          | 1        | 1.09%   |
| Unknown RAM Module 4096MB DIMM SDRAM                           | 1        | 1.09%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 1.09%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1        | 1.09%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 1        | 1.09%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1        | 1.09%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 1.09%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1        | 1.09%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 1        | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1        | 1.09%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM 1333MT/s                | 1        | 1.09%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                  | 1        | 1.09%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s             | 1        | 1.09%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2133MT/s                  | 1        | 1.09%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1066MT/s                  | 1        | 1.09%   |
| SK Hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s         | 1        | 1.09%   |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s       | 1        | 1.09%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 1.09%   |
| SK Hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s        | 1        | 1.09%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 1.09%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 1        | 1.09%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1        | 1.09%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 1.09%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s       | 1        | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.09%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1        | 1.09%   |
| Samsung RAM M471B1G73AH0-CK0 4096MB SODIMM DDR3 1333MT/s       | 1        | 1.09%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s      | 1        | 1.09%   |
| Samsung RAM M4 70T2864FB3-CF7 1024MB SODIMM DDR2 667MT/s       | 1        | 1.09%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1600MT/s         | 1        | 1.09%   |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s           | 1        | 1.09%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.09%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM DDR3 1867MT/s         | 1        | 1.09%   |
| Samsung RAM M378B5273BH1-CF8 4096MB DIMM 1066MT/s              | 1        | 1.09%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s            | 1        | 1.09%   |
| Samsung RAM M3 78T2863RZS-CE6 1024MB DIMM DDR2 667MT/s         | 1        | 1.09%   |
| Samsung RAM M3 78T2863QZS-CE6 1024MB DIMM DDR2 667MT/s         | 1        | 1.09%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s         | 1        | 1.09%   |
| Samsung RAM M3 12L2920CZ3-CCC 1024MB DIMM DDR 400MT/s          | 1        | 1.09%   |
| Ramaxel RAM RML1040EG38D6F-533 512MB DIMM DDR2 533MT/s         | 1        | 1.09%   |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s            | 1        | 1.09%   |
| Patriot RAM PSD44G213341 4096MB DIMM DDR4 3000MT/s             | 1        | 1.09%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s             | 1        | 1.09%   |
| Nanya RAM NT4GC64B8HB0NF-CG 4096MB DIMM DDR3 1333MT/s          | 1        | 1.09%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s            | 1        | 1.09%   |
| Micron RAM 8JTF25664AZ-1G4D1 2048MB SODIMM DDR3 1333MT/s       | 1        | 1.09%   |
| Micron RAM 36JSF1G72PZ-1 8192MB DIMM DDR3 1600MT/s             | 1        | 1.09%   |
| Micron RAM 16JTF51264AZ-1G4M1 4096MB DIMM DDR3 1333MT/s        | 1        | 1.09%   |
| Micron RAM 16HTF25664AZ-800H1 2048MB DIMM DDR2 800MT/s         | 1        | 1.09%   |
| Kingston RAM SUPER KINGSTEK 2048MB DIMM DDR2 800MT/s           | 1        | 1.09%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s                | 1        | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 31       | 41.33%  |
| DDR4    | 16       | 21.33%  |
| DDR2    | 15       | 20%     |
| SDRAM   | 5        | 6.67%   |
| Unknown | 5        | 6.67%   |
| DDR     | 2        | 2.67%   |
| LPDDR4  | 1        | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 62       | 84.93%  |
| SODIMM | 11       | 15.07%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 25       | 31.65%  |
| 4096  | 19       | 24.05%  |
| 8192  | 18       | 22.78%  |
| 1024  | 7        | 8.86%   |
| 16384 | 5        | 6.33%   |
| 512   | 3        | 3.8%    |
| 65536 | 1        | 1.27%   |
| 32768 | 1        | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 21.95%  |
| 800     | 9        | 10.98%  |
| 1333    | 8        | 9.76%   |
| 2133    | 6        | 7.32%   |
| 2400    | 5        | 6.1%    |
| 667     | 5        | 6.1%    |
| 400     | 4        | 4.88%   |
| Unknown | 4        | 4.88%   |
| 3200    | 3        | 3.66%   |
| 2048    | 3        | 3.66%   |
| 1066    | 3        | 3.66%   |
| 3600    | 2        | 2.44%   |
| 3000    | 2        | 2.44%   |
| 2667    | 2        | 2.44%   |
| 1866    | 2        | 2.44%   |
| 49926   | 1        | 1.22%   |
| 2733    | 1        | 1.22%   |
| 1867    | 1        | 1.22%   |
| 1334    | 1        | 1.22%   |
| 533     | 1        | 1.22%   |
| 333     | 1        | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| 0     | 94       | 83.93%  |
| 1     | 17       | 15.18%  |
| 2     | 1        | 0.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 29.41%  |
| Net/wireless             | 3        | 17.65%  |
| Communication controller | 3        | 17.65%  |
| Unassigned class         | 2        | 11.76%  |
| Sound                    | 2        | 11.76%  |
| Multimedia controller    | 1        | 5.88%   |
| Dvb card                 | 1        | 5.88%   |

