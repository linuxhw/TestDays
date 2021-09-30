Lubuntu 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=lubuntu-20.04

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
| 5.4.0-52-generic      | 8        | 8.08%   |
| 5.4.0-42-generic      | 7        | 7.07%   |
| 5.8.0-50-generic      | 6        | 6.06%   |
| 5.4.0-54-generic      | 5        | 5.05%   |
| 5.4.0-67-generic      | 4        | 4.04%   |
| 5.4.0-40-generic      | 4        | 4.04%   |
| 5.4.0-29-generic      | 4        | 4.04%   |
| 5.11.0-27-generic     | 4        | 4.04%   |
| 5.4.0-77-generic      | 3        | 3.03%   |
| 5.4.0-73-generic      | 3        | 3.03%   |
| 5.4.0-48-generic      | 3        | 3.03%   |
| 5.4.0-47-generic      | 3        | 3.03%   |
| 5.4.0-37-generic      | 3        | 3.03%   |
| 5.4.0-33-generic      | 3        | 3.03%   |
| 5.4.0-26-generic      | 3        | 3.03%   |
| 5.8.0-63-generic      | 2        | 2.02%   |
| 5.8.0-59-generic      | 2        | 2.02%   |
| 5.8.0-53-generic      | 2        | 2.02%   |
| 5.8.0-45-generic      | 2        | 2.02%   |
| 5.8.0-41-generic      | 2        | 2.02%   |
| 5.4.0-72-generic      | 2        | 2.02%   |
| 5.4.0-66-generic      | 2        | 2.02%   |
| 5.4.0-60-generic      | 2        | 2.02%   |
| 5.11.0-34-generic     | 2        | 2.02%   |
| 5.8.0-7630-generic    | 1        | 1.01%   |
| 5.8.0-55-generic      | 1        | 1.01%   |
| 5.8.0-48-generic      | 1        | 1.01%   |
| 5.8.0-43-generic      | 1        | 1.01%   |
| 5.6.15-050615-generic | 1        | 1.01%   |
| 5.6.0-1052-oem        | 1        | 1.01%   |
| 5.4.30-dli            | 1        | 1.01%   |
| 5.4.0-81-generic      | 1        | 1.01%   |
| 5.4.0-75-generic      | 1        | 1.01%   |
| 5.4.0-70-lowlatency   | 1        | 1.01%   |
| 5.4.0-65-generic      | 1        | 1.01%   |
| 5.4.0-64-generic      | 1        | 1.01%   |
| 5.4.0-59-generic      | 1        | 1.01%   |
| 5.4.0-58-generic      | 1        | 1.01%   |
| 5.4.0-53-generic      | 1        | 1.01%   |
| 5.4.0-31-generic      | 1        | 1.01%   |
| 5.14.0-051400-generic | 1        | 1.01%   |
| 5.11.0-36-generic     | 1        | 1.01%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 64       | 67.37%  |
| 5.8.0   | 20       | 21.05%  |
| 5.11.0  | 7        | 7.37%   |
| 5.6.15  | 1        | 1.05%   |
| 5.6.0   | 1        | 1.05%   |
| 5.4.30  | 1        | 1.05%   |
| 5.14.0  | 1        | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 65       | 68.42%  |
| 5.8     | 20       | 21.05%  |
| 5.11    | 7        | 7.37%   |
| 5.6     | 2        | 2.11%   |
| 5.14    | 1        | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 95       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 91       | 95.79%  |
| LXDE       | 2        | 2.11%   |
| X-Cinnamon | 1        | 1.05%   |
| GNOME      | 1        | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 90       | 94.74%  |
| Tty     | 4        | 4.21%   |
| Unknown | 1        | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 42       | 43.75%  |
| Unknown | 39       | 40.63%  |
| TDM     | 7        | 7.29%   |
| GDM     | 6        | 6.25%   |
| LightDM | 2        | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 28.42%  |
| fr_FR   | 10       | 10.53%  |
| it_IT   | 9        | 9.47%   |
| pt_BR   | 8        | 8.42%   |
| ru_RU   | 4        | 4.21%   |
| en_GB   | 4        | 4.21%   |
| en_AU   | 4        | 4.21%   |
| de_DE   | 4        | 4.21%   |
| C       | 4        | 4.21%   |
| hu_HU   | 2        | 2.11%   |
| es_ES   | 2        | 2.11%   |
| en_ZA   | 2        | 2.11%   |
| cs_CZ   | 2        | 2.11%   |
| sv_SE   | 1        | 1.05%   |
| nl_NL   | 1        | 1.05%   |
| ja_JP   | 1        | 1.05%   |
| fi_FI   | 1        | 1.05%   |
| es_PE   | 1        | 1.05%   |
| es_MX   | 1        | 1.05%   |
| es_CR   | 1        | 1.05%   |
| es_CO   | 1        | 1.05%   |
| en_SG   | 1        | 1.05%   |
| en_CA   | 1        | 1.05%   |
| el_GR   | 1        | 1.05%   |
| de_CH   | 1        | 1.05%   |
| Unknown | 1        | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 66       | 69.47%  |
| EFI  | 29       | 30.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 88       | 92.63%  |
| Overlay | 4        | 4.21%   |
| Xfs     | 2        | 2.11%   |
| Btrfs   | 1        | 1.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 39.58%  |
| MBR     | 33       | 34.38%  |
| GPT     | 25       | 26.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 84.21%  |
| Yes       | 15       | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 69.47%  |
| Yes       | 29       | 30.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 17.89%  |
| Hewlett-Packard     | 13       | 13.68%  |
| MSI                 | 10       | 10.53%  |
| Gigabyte Technology | 10       | 10.53%  |
| ASRock              | 10       | 10.53%  |
| Dell                | 9        | 9.47%   |
| Lenovo              | 6        | 6.32%   |
| Intel               | 5        | 5.26%   |
| Positivo            | 2        | 2.11%   |
| Pegatron            | 2        | 2.11%   |
| Acer                | 2        | 2.11%   |
| ZOTAC               | 1        | 1.05%   |
| Packard Bell        | 1        | 1.05%   |
| IBM                 | 1        | 1.05%   |
| Huanan              | 1        | 1.05%   |
| HARDKERNEL          | 1        | 1.05%   |
| Fujitsu Siemens     | 1        | 1.05%   |
| Foxconn             | 1        | 1.05%   |
| Biostar             | 1        | 1.05%   |
| AAEON               | 1        | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7B89                         | 2        | 2.11%   |
| ASRock N68-VS3 UCC                  | 2        | 2.11%   |
| ZOTAC NM10                          | 1        | 1.05%   |
| Positivo POS-MI945AA                | 1        | 1.05%   |
| Positivo POS-EIH61CE                | 1        | 1.05%   |
| Pegatron NC689AA-ABA s3700y         | 1        | 1.05%   |
| Pegatron AY652AA-ABA s5310y         | 1        | 1.05%   |
| Packard Bell imedia S1350           | 1        | 1.05%   |
| MSI MS-7C37                         | 1        | 1.05%   |
| MSI MS-7B86                         | 1        | 1.05%   |
| MSI MS-7994                         | 1        | 1.05%   |
| MSI MS-7846                         | 1        | 1.05%   |
| MSI MS-7680                         | 1        | 1.05%   |
| MSI MS-7592                         | 1        | 1.05%   |
| MSI ER883AA-ABA M7470N              | 1        | 1.05%   |
| MSI Compaq dx2200 MT                | 1        | 1.05%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 1.05%   |
| Lenovo ThinkCentre M93z 10AD002DMZ  | 1        | 1.05%   |
| Lenovo ThinkCentre M58p 7220W21     | 1        | 1.05%   |
| Lenovo ThinkCentre M58p 6136A66     | 1        | 1.05%   |
| Lenovo H50-50 90B60081IX            | 1        | 1.05%   |
| Lenovo H50-30g 90AS0002BR           | 1        | 1.05%   |
| Intel STK1AW32SC                    | 1        | 1.05%   |
| Intel H55                           | 1        | 1.05%   |
| Intel DN2800MT AAG23738-801         | 1        | 1.05%   |
| Intel DG31PR AAD97573-302           | 1        | 1.05%   |
| Intel ChiefRiver                    | 1        | 1.05%   |
| IBM eServer x3105 -[434722J]-       | 1        | 1.05%   |
| Huanan X99-TF                       | 1        | 1.05%   |
| HP Z230 Tower Workstation           | 1        | 1.05%   |
| HP xw9400 Workstation               | 1        | 1.05%   |
| HP xw9300 Workstation               | 1        | 1.05%   |
| HP t620 Quad Core TC                | 1        | 1.05%   |
| HP t620 Dual Core TC                | 1        | 1.05%   |
| HP ProDesk 600 G1 DM                | 1        | 1.05%   |
| HP EliteDesk 800 G3 SFF             | 1        | 1.05%   |
| HP Compaq Elite 8300 CMT            | 1        | 1.05%   |
| HP Compaq dc7800 Small Form Factor  | 1        | 1.05%   |
| HP Compaq dc7600 Small Form Factor  | 1        | 1.05%   |
| HP Compaq dc5800 Microtower         | 1        | 1.05%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 1.05%   |
| HP Compaq 6000 Pro SFF PC           | 1        | 1.05%   |
| HARDKERNEL ODROID-H2                | 1        | 1.05%   |
| Gigabyte Z370P D3                   | 1        | 1.05%   |
| Gigabyte X570 GAMING X              | 1        | 1.05%   |
| Gigabyte K8M800-8237                | 1        | 1.05%   |
| Gigabyte H81M-DS2                   | 1        | 1.05%   |
| Gigabyte H61M-DS2H                  | 1        | 1.05%   |
| Gigabyte GA-870A-UD3                | 1        | 1.05%   |
| Gigabyte F2A88XM-HD3                | 1        | 1.05%   |
| Gigabyte B450M H                    | 1        | 1.05%   |
| Gigabyte B250M-D3H                  | 1        | 1.05%   |
| Gigabyte 965P-DS3                   | 1        | 1.05%   |
| Fujitsu Siemens ESPRIMO P5925       | 1        | 1.05%   |
| Foxconn WU115EA-AKB 100eu CZ100     | 1        | 1.05%   |
| Dell XPS 8300                       | 1        | 1.05%   |
| Dell Vostro 200                     | 1        | 1.05%   |
| Dell Precision T3610                | 1        | 1.05%   |
| Dell OptiPlex 790                   | 1        | 1.05%   |
| Dell OptiPlex 390                   | 1        | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 6        | 6.32%   |
| Lenovo ThinkCentre      | 3        | 3.16%   |
| Dell OptiPlex           | 3        | 3.16%   |
| MSI MS-7B89             | 2        | 2.11%   |
| HP t620                 | 2        | 2.11%   |
| ASRock N68-VS3          | 2        | 2.11%   |
| Acer Aspire             | 2        | 2.11%   |
| ZOTAC NM10              | 1        | 1.05%   |
| Positivo POS-MI945AA    | 1        | 1.05%   |
| Positivo POS-EIH61CE    | 1        | 1.05%   |
| Pegatron NC689AA-ABA    | 1        | 1.05%   |
| Pegatron AY652AA-ABA    | 1        | 1.05%   |
| Packard Bell imedia     | 1        | 1.05%   |
| MSI MS-7C37             | 1        | 1.05%   |
| MSI MS-7B86             | 1        | 1.05%   |
| MSI MS-7994             | 1        | 1.05%   |
| MSI MS-7846             | 1        | 1.05%   |
| MSI MS-7680             | 1        | 1.05%   |
| MSI MS-7592             | 1        | 1.05%   |
| MSI ER883AA-ABA         | 1        | 1.05%   |
| MSI Compaq              | 1        | 1.05%   |
| Lenovo ThinkStation     | 1        | 1.05%   |
| Lenovo H50-50           | 1        | 1.05%   |
| Lenovo H50-30g          | 1        | 1.05%   |
| Intel STK1AW32SC        | 1        | 1.05%   |
| Intel H55               | 1        | 1.05%   |
| Intel DN2800MT          | 1        | 1.05%   |
| Intel DG31PR            | 1        | 1.05%   |
| Intel ChiefRiver        | 1        | 1.05%   |
| IBM eServer             | 1        | 1.05%   |
| Huanan X99-TF           | 1        | 1.05%   |
| HP Z230                 | 1        | 1.05%   |
| HP xw9400               | 1        | 1.05%   |
| HP xw9300               | 1        | 1.05%   |
| HP ProDesk              | 1        | 1.05%   |
| HP EliteDesk            | 1        | 1.05%   |
| HARDKERNEL ODROID-H2    | 1        | 1.05%   |
| Gigabyte Z370P          | 1        | 1.05%   |
| Gigabyte X570           | 1        | 1.05%   |
| Gigabyte K8M800-8237    | 1        | 1.05%   |
| Gigabyte H81M-DS2       | 1        | 1.05%   |
| Gigabyte H61M-DS2H      | 1        | 1.05%   |
| Gigabyte GA-870A-UD3    | 1        | 1.05%   |
| Gigabyte F2A88XM-HD3    | 1        | 1.05%   |
| Gigabyte B450M          | 1        | 1.05%   |
| Gigabyte B250M-D3H      | 1        | 1.05%   |
| Gigabyte 965P-DS3       | 1        | 1.05%   |
| Fujitsu Siemens ESPRIMO | 1        | 1.05%   |
| Foxconn WU115EA-AKB     | 1        | 1.05%   |
| Dell XPS                | 1        | 1.05%   |
| Dell Vostro             | 1        | 1.05%   |
| Dell Precision          | 1        | 1.05%   |
| Dell Inspiron           | 1        | 1.05%   |
| Dell DM061              | 1        | 1.05%   |
| Dell Dimension          | 1        | 1.05%   |
| Biostar GF7025-M2       | 1        | 1.05%   |
| ASUS Z170               | 1        | 1.05%   |
| ASUS V-P8H67E           | 1        | 1.05%   |
| ASUS P8Z68-V            | 1        | 1.05%   |
| ASUS P8H61-M            | 1        | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 9        | 9.47%   |
| 2019 | 8        | 8.42%   |
| 2014 | 7        | 7.37%   |
| 2012 | 7        | 7.37%   |
| 2009 | 7        | 7.37%   |
| 2008 | 7        | 7.37%   |
| 2020 | 6        | 6.32%   |
| 2011 | 6        | 6.32%   |
| 2010 | 6        | 6.32%   |
| 2017 | 5        | 5.26%   |
| 2015 | 5        | 5.26%   |
| 2013 | 5        | 5.26%   |
| 2021 | 4        | 4.21%   |
| 2018 | 4        | 4.21%   |
| 2016 | 3        | 3.16%   |
| 2006 | 3        | 3.16%   |
| 2005 | 3        | 3.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 95       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 93       | 97.89%  |
| Enabled  | 2        | 2.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 30       | 31.25%  |
| 8.01-16.0       | 15       | 15.63%  |
| 1.01-2.0        | 14       | 14.58%  |
| 4.01-8.0        | 13       | 13.54%  |
| 16.01-24.0      | 12       | 12.5%   |
| 32.01-64.0      | 7        | 7.29%   |
| 0.51-1.0        | 2        | 2.08%   |
| More than 256.0 | 1        | 1.04%   |
| 24.01-32.0      | 1        | 1.04%   |
| 2.01-3.0        | 1        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 51       | 52.04%  |
| 2.01-3.0  | 19       | 19.39%  |
| 0.51-1.0  | 13       | 13.27%  |
| 4.01-8.0  | 8        | 8.16%   |
| 3.01-4.0  | 5        | 5.1%    |
| 8.01-16.0 | 2        | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 48.42%  |
| 2      | 31       | 32.63%  |
| 4      | 6        | 6.32%   |
| 3      | 6        | 6.32%   |
| 5      | 3        | 3.16%   |
| 14     | 1        | 1.05%   |
| 7      | 1        | 1.05%   |
| 0      | 1        | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 63.16%  |
| No        | 35       | 36.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 98.95%  |
| No        | 1        | 1.05%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 58.95%  |
| Yes       | 39       | 41.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 85.26%  |
| Yes       | 14       | 14.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 13       | 13.54%  |
| France       | 10       | 10.42%  |
| Italy        | 9        | 9.38%   |
| Brazil       | 9        | 9.38%   |
| Germany      | 6        | 6.25%   |
| Hungary      | 5        | 5.21%   |
| Switzerland  | 4        | 4.17%   |
| Russia       | 4        | 4.17%   |
| Australia    | 4        | 4.17%   |
| Spain        | 3        | 3.13%   |
| Netherlands  | 3        | 3.13%   |
| Czechia      | 3        | 3.13%   |
| South Africa | 2        | 2.08%   |
| Puerto Rico  | 2        | 2.08%   |
| Mexico       | 2        | 2.08%   |
| Greece       | 2        | 2.08%   |
| Finland      | 2        | 2.08%   |
| UK           | 1        | 1.04%   |
| Sweden       | 1        | 1.04%   |
| Singapore    | 1        | 1.04%   |
| Romania      | 1        | 1.04%   |
| Peru         | 1        | 1.04%   |
| New Zealand  | 1        | 1.04%   |
| Malaysia     | 1        | 1.04%   |
| Japan        | 1        | 1.04%   |
| Costa Rica   | 1        | 1.04%   |
| Colombia     | 1        | 1.04%   |
| Canada       | 1        | 1.04%   |
| Belgium      | 1        | 1.04%   |
| Belarus      | 1        | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Rome                | 4        | 4.12%   |
| Windsor             | 2        | 2.06%   |
| Prague              | 2        | 2.06%   |
| Milan               | 2        | 2.06%   |
| Eger                | 2        | 2.06%   |
| Cuernavaca          | 2        | 2.06%   |
| Cayey               | 2        | 2.06%   |
| Augsburg            | 2        | 2.06%   |
| Annecy              | 2        | 2.06%   |
| Zurich              | 1        | 1.03%   |
| Yelizovo            | 1        | 1.03%   |
| Wiesbaden           | 1        | 1.03%   |
| Wellington          | 1        | 1.03%   |
| Vlaardingen         | 1        | 1.03%   |
| Vitry-sur-Seine     | 1        | 1.03%   |
| Vaxjo               | 1        | 1.03%   |
| Vanderbijlpark      | 1        | 1.03%   |
| Valls               | 1        | 1.03%   |
| Valinhos            | 1        | 1.03%   |
| Valencia            | 1        | 1.03%   |
| Treviso             | 1        | 1.03%   |
| Tourcoing           | 1        | 1.03%   |
| Toronto             | 1        | 1.03%   |
| The Hague           | 1        | 1.03%   |
| Springfield         | 1        | 1.03%   |
| Spokane             | 1        | 1.03%   |
| Sora                | 1        | 1.03%   |
| Singapore           | 1        | 1.03%   |
| Sandorfalva         | 1        | 1.03%   |
| Roseburg            | 1        | 1.03%   |
| Raleigh             | 1        | 1.03%   |
| Porto Alegre        | 1        | 1.03%   |
| Portbail            | 1        | 1.03%   |
| Periers             | 1        | 1.03%   |
| P?�cs               | 1        | 1.03%   |
| Passos              | 1        | 1.03%   |
| Pacatuba            | 1        | 1.03%   |
| Oradea              | 1        | 1.03%   |
| Omsk                | 1        | 1.03%   |
| Oceanside           | 1        | 1.03%   |
| Novy Jicin          | 1        | 1.03%   |
| Neuchatel           | 1        | 1.03%   |
| Munich              | 1        | 1.03%   |
| Mount Waverley      | 1        | 1.03%   |
| Moordrecht          | 1        | 1.03%   |
| Montross            | 1        | 1.03%   |
| Montreuil           | 1        | 1.03%   |
| Montlhery           | 1        | 1.03%   |
| Mogilev             | 1        | 1.03%   |
| Mobile              | 1        | 1.03%   |
| Menen               | 1        | 1.03%   |
| Medellín           | 1        | 1.03%   |
| Marlow              | 1        | 1.03%   |
| Lovens              | 1        | 1.03%   |
| Le Mesnil-en-Thelle | 1        | 1.03%   |
| Langenhagen         | 1        | 1.03%   |
| Kuala Lumpur        | 1        | 1.03%   |
| Kozani              | 1        | 1.03%   |
| Kirov               | 1        | 1.03%   |
| Kabukicho           | 1        | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 38       | 63     | 26.39%  |
| Seagate             | 38       | 47     | 26.39%  |
| Samsung Electronics | 17       | 30     | 11.81%  |
| Kingston            | 8        | 8      | 5.56%   |
| Toshiba             | 7        | 7      | 4.86%   |
| Hitachi             | 5        | 6      | 3.47%   |
| Unknown             | 4        | 5      | 2.78%   |
| SanDisk             | 3        | 3      | 2.08%   |
| China               | 3        | 3      | 2.08%   |
| A-DATA Technology   | 3        | 3      | 2.08%   |
| PNY                 | 2        | 2      | 1.39%   |
| MAXTOR              | 2        | 2      | 1.39%   |
| Transcend           | 1        | 1      | 0.69%   |
| Team                | 1        | 1      | 0.69%   |
| PNY USB             | 1        | 1      | 0.69%   |
| OCZ                 | 1        | 1      | 0.69%   |
| LONDISK             | 1        | 1      | 0.69%   |
| Lexar               | 1        | 1      | 0.69%   |
| LDLC                | 1        | 1      | 0.69%   |
| JMicron             | 1        | 1      | 0.69%   |
| Intel               | 1        | 1      | 0.69%   |
| HGST                | 1        | 1      | 0.69%   |
| Hewlett-Packard     | 1        | 6      | 0.69%   |
| Fujitsu             | 1        | 1      | 0.69%   |
| Crucial             | 1        | 1      | 0.69%   |
| Corsair             | 1        | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 2.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 1.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 1.25%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 1.25%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 1.25%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 1.25%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 1.25%   |
| Seagate ST380815AS 80GB             | 2        | 1.25%   |
| Seagate ST3500418AS 500GB           | 2        | 1.25%   |
| Seagate ST3360320AS 360GB           | 2        | 1.25%   |
| Seagate ST3250410AS 250GB           | 2        | 1.25%   |
| Seagate ST3250310AS 250GB           | 2        | 1.25%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 1.25%   |
| Samsung SSD 850 EVO 250GB           | 2        | 1.25%   |
| Samsung HD161HJ 160GB               | 2        | 1.25%   |
| Samsung HD080HJ 80GB                | 2        | 1.25%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.25%   |
| China SATA SSD 512GB                | 2        | 1.25%   |
| A-DATA SU650 240GB SSD              | 2        | 1.25%   |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.63%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.63%   |
| WDC WD800JD-75JNA0 80GB             | 1        | 0.63%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.63%   |
| WDC WD7501AALS-00J7B1 752GB         | 1        | 0.63%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.63%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.63%   |
| WDC WD5000BPKX-66HPJT0 500GB        | 1        | 0.63%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.63%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.63%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.63%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.63%   |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.63%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.63%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.63%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 0.63%   |
| WDC WD2500JS-75NCB3 250GB           | 1        | 0.63%   |
| WDC WD2500JD-00HBB0 250GB           | 1        | 0.63%   |
| WDC WD2500AAKX-07U6AA0 250GB        | 1        | 0.63%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 0.63%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.63%   |
| WDC WD1600BB-00RDA0 160GB           | 1        | 0.63%   |
| WDC WD1600AAJS-60B4A0 160GB         | 1        | 0.63%   |
| WDC WD15EARS-22MVWB0 1TB            | 1        | 0.63%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1        | 0.63%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 0.63%   |
| WDC WD10EAVS-14M4B0 1TB             | 1        | 0.63%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 0.63%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 0.63%   |
| WDC WD10EALX-759BA1 1TB             | 1        | 0.63%   |
| WDC WD10EALS-00Z8A0 1TB             | 1        | 0.63%   |
| Unknown SD/MMC/MS PRO 128GB         | 1        | 0.63%   |
| Unknown MMC Card  32GB              | 1        | 0.63%   |
| Unknown MMC Card  128GB             | 1        | 0.63%   |
| Unknown M52516  16GB                | 1        | 0.63%   |
| Unknown CJTD4R  64GB                | 1        | 0.63%   |
| Transcend TS32GSSD370S 32GB         | 1        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 47     | 40.86%  |
| WDC                 | 33       | 54     | 35.48%  |
| Samsung Electronics | 7        | 8      | 7.53%   |
| Toshiba             | 5        | 5      | 5.38%   |
| Hitachi             | 5        | 6      | 5.38%   |
| MAXTOR              | 2        | 2      | 2.15%   |
| Unknown             | 1        | 1      | 1.08%   |
| HGST                | 1        | 1      | 1.08%   |
| Fujitsu             | 1        | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 19.57%  |
| Kingston            | 8        | 8      | 17.39%  |
| WDC                 | 7        | 9      | 15.22%  |
| SanDisk             | 3        | 3      | 6.52%   |
| China               | 3        | 3      | 6.52%   |
| Toshiba             | 2        | 2      | 4.35%   |
| PNY                 | 2        | 2      | 4.35%   |
| A-DATA Technology   | 2        | 2      | 4.35%   |
| Transcend           | 1        | 1      | 2.17%   |
| Team                | 1        | 1      | 2.17%   |
| PNY USB             | 1        | 1      | 2.17%   |
| OCZ                 | 1        | 1      | 2.17%   |
| LONDISK             | 1        | 1      | 2.17%   |
| Lexar               | 1        | 1      | 2.17%   |
| LDLC                | 1        | 1      | 2.17%   |
| Hewlett-Packard     | 1        | 6      | 2.17%   |
| Crucial             | 1        | 1      | 2.17%   |
| Corsair             | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 71       | 125    | 58.2%   |
| SSD  | 44       | 56     | 36.07%  |
| NVMe | 4        | 13     | 3.28%   |
| MMC  | 3        | 4      | 2.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 91       | 178    | 90.1%   |
| SAS  | 4        | 4      | 3.96%   |
| NVMe | 3        | 12     | 2.97%   |
| MMC  | 3        | 4      | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 77       | 113    | 66.38%  |
| 0.51-1.0   | 29       | 48     | 25%     |
| 3.01-4.0   | 4        | 12     | 3.45%   |
| 2.01-3.0   | 3        | 3      | 2.59%   |
| 1.01-2.0   | 3        | 5      | 2.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 27.08%  |
| 251-500        | 20       | 20.83%  |
| 1001-2000      | 12       | 12.5%   |
| 501-1000       | 10       | 10.42%  |
| 51-100         | 9        | 9.38%   |
| More than 3000 | 7        | 7.29%   |
| 2001-3000      | 5        | 5.21%   |
| 21-50          | 3        | 3.13%   |
| 1-20           | 3        | 3.13%   |
| Unknown        | 1        | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 36       | 37.5%   |
| 21-50          | 16       | 16.67%  |
| 101-250        | 13       | 13.54%  |
| 501-1000       | 8        | 8.33%   |
| 1001-2000      | 6        | 6.25%   |
| 51-100         | 6        | 6.25%   |
| 251-500        | 5        | 5.21%   |
| 2001-3000      | 3        | 3.13%   |
| More than 3000 | 2        | 2.08%   |
| Unknown        | 1        | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000AAKX-003CA0 500GB     | 1        | 1      | 6.25%   |
| WDC WD400EB-00CPF0 40GB         | 1        | 1      | 6.25%   |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 2      | 6.25%   |
| Seagate ST380815AS 80GB         | 1        | 1      | 6.25%   |
| Seagate ST3360320AS 360GB       | 1        | 1      | 6.25%   |
| Seagate ST3160318AS 160GB       | 1        | 1      | 6.25%   |
| Seagate ST1000DX001-1CM162 1TB  | 1        | 1      | 6.25%   |
| Seagate ST1000DM003-9YN162 1TB  | 1        | 1      | 6.25%   |
| Seagate ST1000DM003-1ER162 1TB  | 1        | 1      | 6.25%   |
| MAXTOR STM3300622A 304GB        | 1        | 1      | 6.25%   |
| MAXTOR 6Y080L0 82GB             | 1        | 1      | 6.25%   |
| LDLC SSD 120GB                  | 1        | 1      | 6.25%   |
| Kingston SHFS37A120G 120GB SSD  | 1        | 1      | 6.25%   |
| Kingston SA400S37120G 120GB SSD | 1        | 1      | 6.25%   |
| Hitachi HCP725050GLAT80 500GB   | 1        | 1      | 6.25%   |
| Fujitsu MHZ2160BH G2 160GB      | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 6        | 6      | 37.5%   |
| WDC      | 3        | 4      | 18.75%  |
| MAXTOR   | 2        | 2      | 12.5%   |
| Kingston | 2        | 2      | 12.5%   |
| LDLC     | 1        | 1      | 6.25%   |
| Hitachi  | 1        | 1      | 6.25%   |
| Fujitsu  | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 6      | 46.15%  |
| WDC     | 3        | 4      | 23.08%  |
| MAXTOR  | 2        | 2      | 15.38%  |
| Hitachi | 1        | 1      | 7.69%   |
| Fujitsu | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 14     | 80%     |
| SSD  | 3        | 3      | 20%     |

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
| Works    | 50       | 107    | 46.73%  |
| Detected | 42       | 73     | 39.25%  |
| Malfunc  | 14       | 17     | 13.08%  |
| Failed   | 1        | 1      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 60       | 55.56%  |
| AMD                       | 20       | 18.52%  |
| Nvidia                    | 11       | 10.19%  |
| JMicron Technology        | 5        | 4.63%   |
| Marvell Technology Group  | 4        | 3.7%    |
| VIA Technologies          | 2        | 1.85%   |
| LSI Logic / Symbios Logic | 2        | 1.85%   |
| ASMedia Technology        | 2        | 1.85%   |
| Samsung Electronics       | 1        | 0.93%   |
| ADATA Technology          | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 8.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 5.77%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 3.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 3.85%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 3.21%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 3.21%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 3.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.21%   |
| Nvidia MCP61 IDE                                                                        | 4        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.56%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.92%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 1.28%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 1.28%   |
| Nvidia CK804 IDE                                                                        | 2        | 1.28%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.28%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.28%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.28%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.28%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 1.28%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 1.28%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.28%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.64%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.64%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.64%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.64%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.64%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.64%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.64%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.64%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.64%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.64%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.64%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.64%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.64%   |
| Intel SSD 660P Series                                                                   | 1        | 0.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.64%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.64%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.64%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.64%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.64%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 0.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.64%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1        | 0.64%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 52       | 48.15%  |
| IDE  | 47       | 43.52%  |
| RAID | 4        | 3.7%    |
| NVMe | 3        | 2.78%   |
| SCSI | 2        | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 67.37%  |
| AMD    | 31       | 32.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 3.16%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 3.16%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3.16%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 2.11%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 2.11%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.11%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.11%   |
| AMD Athlon II X2 250 Processor              | 2        | 2.11%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 2.11%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 2        | 2.11%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.05%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 1.05%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 1.05%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.05%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.05%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1.05%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.05%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.05%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 1.05%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.05%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.05%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.05%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.05%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 1.05%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.05%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 1.05%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 1.05%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.05%   |
| Intel Core i5-4440S CPU @ 2.80GHz           | 1        | 1.05%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.05%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.05%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 1.05%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 1.05%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.05%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.05%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 1.05%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.05%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 1.05%   |
| Intel Core 2 Quad CPU @ 2.40GHz             | 1        | 1.05%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 1.05%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.05%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.05%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.05%   |
| Intel Core 2 Duo CPU E6850 @ 3.00GHz        | 1        | 1.05%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 1.05%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.05%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 1.05%   |
| Intel Core 2 CPU 6420 @ 2.13GHz             | 1        | 1.05%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1        | 1.05%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 1.05%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 1        | 1.05%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.05%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.05%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1        | 1.05%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 1        | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 1.05%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz           | 1        | 1.05%   |
| Intel Atom CPU N2800 @ 1.86GHz              | 1        | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 18.95%  |
| Intel Core 2 Duo        | 10       | 10.53%  |
| Intel Core i3           | 6        | 6.32%   |
| Intel Celeron           | 5        | 5.26%   |
| Intel Atom              | 5        | 5.26%   |
| AMD Ryzen 5             | 5        | 5.26%   |
| AMD Athlon 64 X2        | 5        | 5.26%   |
| Intel Core 2            | 4        | 4.21%   |
| Intel Xeon              | 3        | 3.16%   |
| Intel Core i7           | 3        | 3.16%   |
| Intel Core 2 Quad       | 3        | 3.16%   |
| AMD Ryzen 7             | 3        | 3.16%   |
| AMD Athlon II X2        | 3        | 3.16%   |
| Intel Pentium Dual-Core | 2        | 2.11%   |
| Intel Pentium Dual      | 2        | 2.11%   |
| Intel Pentium 4         | 2        | 2.11%   |
| AMD Sempron             | 2        | 2.11%   |
| AMD GX                  | 2        | 2.11%   |
| AMD Athlon 64           | 2        | 2.11%   |
| AMD A10                 | 2        | 2.11%   |
| Intel Pentium           | 1        | 1.05%   |
| AMD Ryzen Threadripper  | 1        | 1.05%   |
| AMD Quad-Core Opteron   | 1        | 1.05%   |
| AMD Phenom II X3        | 1        | 1.05%   |
| AMD Opteron             | 1        | 1.05%   |
| AMD FX                  | 1        | 1.05%   |
| AMD E                   | 1        | 1.05%   |
| AMD Athlon X4           | 1        | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 48       | 50.53%  |
| 4      | 27       | 28.42%  |
| 1      | 7        | 7.37%   |
| 6      | 6        | 6.32%   |
| 8      | 4        | 4.21%   |
| 64     | 1        | 1.05%   |
| 12     | 1        | 1.05%   |
| 3      | 1        | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 97.89%  |
| 2      | 2        | 2.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 66.32%  |
| 2      | 32       | 33.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 95       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 14.74%  |
| 0x206a7    | 11       | 11.58%  |
| 0x306c3    | 7        | 7.37%   |
| 0x1067a    | 7        | 7.37%   |
| 0x906e9    | 3        | 3.16%   |
| 0x6fd      | 3        | 3.16%   |
| 0x6fb      | 3        | 3.16%   |
| 0x6f6      | 3        | 3.16%   |
| 0x306a9    | 3        | 3.16%   |
| 0x10676    | 3        | 3.16%   |
| 0x08701021 | 3        | 3.16%   |
| 0x506e3    | 2        | 2.11%   |
| 0x406c4    | 2        | 2.11%   |
| 0x20655    | 2        | 2.11%   |
| 0x106ca    | 2        | 2.11%   |
| 0x08701013 | 2        | 2.11%   |
| 0x0800820d | 2        | 2.11%   |
| 0x0700010f | 2        | 2.11%   |
| 0x06001119 | 2        | 2.11%   |
| 0x010000c8 | 2        | 2.11%   |
| 0xf65      | 1        | 1.05%   |
| 0xf4a      | 1        | 1.05%   |
| 0x906ea    | 1        | 1.05%   |
| 0x706a1    | 1        | 1.05%   |
| 0x6f7      | 1        | 1.05%   |
| 0x6f2      | 1        | 1.05%   |
| 0x306f2    | 1        | 1.05%   |
| 0x306e4    | 1        | 1.05%   |
| 0x30678    | 1        | 1.05%   |
| 0x30661    | 1        | 1.05%   |
| 0x0830104d | 1        | 1.05%   |
| 0x06003106 | 1        | 1.05%   |
| 0x06000852 | 1        | 1.05%   |
| 0x05000119 | 1        | 1.05%   |
| 0x010000db | 1        | 1.05%   |
| 0x010000c7 | 1        | 1.05%   |
| 0x01000095 | 1        | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 11       | 11.58%  |
| Core          | 11       | 11.58%  |
| Penryn        | 10       | 10.53%  |
| K8 Hammer     | 9        | 9.47%   |
| Haswell       | 9        | 9.47%   |
| Zen 2         | 6        | 6.32%   |
| K10           | 6        | 6.32%   |
| KabyLake      | 4        | 4.21%   |
| IvyBridge     | 4        | 4.21%   |
| Zen+          | 3        | 3.16%   |
| Skylake       | 3        | 3.16%   |
| Silvermont    | 3        | 3.16%   |
| Piledriver    | 3        | 3.16%   |
| Bonnell       | 3        | 3.16%   |
| Westmere      | 2        | 2.11%   |
| NetBurst      | 2        | 2.11%   |
| Jaguar        | 2        | 2.11%   |
| Steamroller   | 1        | 1.05%   |
| Goldmont plus | 1        | 1.05%   |
| CometLake     | 1        | 1.05%   |
| Bobcat        | 1        | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 35       | 35.71%  |
| Intel  | 32       | 32.65%  |
| AMD    | 31       | 31.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 7.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 3.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 3.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.94%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 3        | 2.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 2.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 2.94%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.96%   |
| Intel HD Graphics 530                                                                    | 2        | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.96%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.96%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.96%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.96%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.96%   |
| AMD Richland [Radeon HD 8670D]                                                           | 2        | 1.96%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.96%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.98%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.98%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.98%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.98%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.98%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.98%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.98%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.98%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 0.98%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.98%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.98%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.98%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.98%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.98%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.98%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.98%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.98%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 0.98%   |
| Intel HD Graphics 630                                                                    | 1        | 0.98%   |
| Intel HD Graphics 610                                                                    | 1        | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.98%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.98%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.98%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.98%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 0.98%   |
| AMD RV770 [Radeon HD 4850]                                                               | 1        | 0.98%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 1        | 0.98%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1        | 0.98%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                                        | 1        | 0.98%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                                    | 1        | 0.98%   |
| AMD RV370 [Radeon X300]                                                                  | 1        | 0.98%   |
| AMD RV370 [Radeon X300 SE]                                                               | 1        | 0.98%   |
| AMD RS480 [Radeon Xpress 200 Series]                                                     | 1        | 0.98%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1        | 0.98%   |
| AMD Picasso                                                                              | 1        | 0.98%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1        | 0.98%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 1        | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 33       | 34.74%  |
| 1 x Intel    | 31       | 32.63%  |
| 1 x AMD      | 26       | 27.37%  |
| 2 x AMD      | 4        | 4.21%   |
| AMD + Nvidia | 1        | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 76.84%  |
| Proprietary | 21       | 22.11%  |
| Unknown     | 1        | 1.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 38.54%  |
| 0.01-0.5   | 21       | 21.88%  |
| 0.51-1.0   | 17       | 17.71%  |
| 1.01-2.0   | 10       | 10.42%  |
| 3.01-4.0   | 6        | 6.25%   |
| 7.01-8.0   | 3        | 3.13%   |
| 2.01-3.0   | 1        | 1.04%   |
| 8.01-16.0  | 1        | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 13       | 13.13%  |
| Dell                    | 13       | 13.13%  |
| Goldstar                | 12       | 12.12%  |
| Hewlett-Packard         | 7        | 7.07%   |
| Acer                    | 7        | 7.07%   |
| Vizio                   | 4        | 4.04%   |
| Philips                 | 4        | 4.04%   |
| Lenovo                  | 4        | 4.04%   |
| Unknown                 | 3        | 3.03%   |
| Iiyama                  | 3        | 3.03%   |
| BenQ                    | 3        | 3.03%   |
| AOC                     | 3        | 3.03%   |
| Ancor Communications    | 3        | 3.03%   |
| Sony                    | 2        | 2.02%   |
| LG Electronics          | 2        | 2.02%   |
| ___                     | 1        | 1.01%   |
| Unknown (ADA)           | 1        | 1.01%   |
| Sceptre Tech            | 1        | 1.01%   |
| Plain Tree Systems      | 1        | 1.01%   |
| NEC Computers           | 1        | 1.01%   |
| LG Display              | 1        | 1.01%   |
| Lenovo Group Limited    | 1        | 1.01%   |
| IBM                     | 1        | 1.01%   |
| Hitachi                 | 1        | 1.01%   |
| HannStar                | 1        | 1.01%   |
| GDH                     | 1        | 1.01%   |
| Fujitsu Siemens         | 1        | 1.01%   |
| Eizo                    | 1        | 1.01%   |
| CVT                     | 1        | 1.01%   |
| Chi Mei Optoelectronics | 1        | 1.01%   |
| Arnos Instruments       | 1        | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch                     | 2        | 1.96%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                              | 2        | 1.96%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                                     | 2        | 1.96%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch                 | 2        | 1.96%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 1        | 0.98%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                                    | 1        | 0.98%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch                             | 1        | 0.98%   |
| Vizio VO370M VIZ0050 1920x1080 820x460mm 37.0-inch                                    | 1        | 0.98%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                                    | 1        | 0.98%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                                    | 1        | 0.98%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                                | 1        | 0.98%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                                     | 1        | 0.98%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                                 | 1        | 0.98%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                                           | 1        | 0.98%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                                            | 1        | 0.98%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch                         | 1        | 0.98%   |
| Sony TV SNYAA01 1920x1080 880x490mm 39.7-inch                                         | 1        | 0.98%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                                     | 1        | 0.98%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch                        | 1        | 0.98%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch                     | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch                   | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch                  | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch                  | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch                  | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch                  | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch                  | 1        | 0.98%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch                     | 1        | 0.98%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch                     | 1        | 0.98%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch                     | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                                   | 1        | 0.98%   |
| Plain Tree Systems FULL HDTV PTS00EC 1920x1080 520x290mm 23.4-inch                    | 1        | 0.98%   |
| Philips PHL 322M7C PHLC194 1920x1080 698x393mm 31.5-inch                              | 1        | 0.98%   |
| Philips 271P4 PHL08C3 1920x1080 597x336mm 27.0-inch                                   | 1        | 0.98%   |
| Philips 190B PHL081A 1280x1024 376x301mm 19.0-inch                                    | 1        | 0.98%   |
| Philips 170C5 PHLC00B 1280x1024 338x270mm 17.0-inch                                   | 1        | 0.98%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 340x270mm 17.1-inch                         | 1        | 0.98%   |
| LG Electronics LCD Monitor W2220                                                      | 1        | 0.98%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                                       | 1        | 0.98%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch                           | 1        | 0.98%   |
| Lenovo LEN-E92I-C LEN0093 1920x1080 509x286mm 23.0-inch                               | 1        | 0.98%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                                | 1        | 0.98%   |
| Lenovo Group Limited LCD Monitor LEN L24q-30 1920x1200                                | 1        | 0.98%   |
| Iiyama PL2792H IVM6638 1920x1080 598x336mm 27.0-inch                                  | 1        | 0.98%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                                  | 1        | 0.98%   |
| Iiyama PL2006W IVM539A 1680x1050 430x240mm 19.4-inch                                  | 1        | 0.98%   |
| IBM L150 IBM19EC 1024x768 304x228mm 15.0-inch                                         | 1        | 0.98%   |
| Hitachi X224W D-sub HIT700B 1680x1050 473x296mm 22.0-inch                             | 1        | 0.98%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch                         | 1        | 0.98%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch                          | 1        | 0.98%   |
| Hewlett-Packard LCD Monitor LA1951 1280x1024                                          | 1        | 0.98%   |
| Hewlett-Packard LCD Monitor E241i 3600x1200                                           | 1        | 0.98%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 337x270mm 17.0-inch                           | 1        | 0.98%   |
| Hewlett-Packard E241i HWP3122 1920x1080 518x324mm 24.1-inch                           | 1        | 0.98%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch                             | 1        | 0.98%   |
| HannStar HU196D HSD899A 1280x1024 376x301mm 19.0-inch                                 | 1        | 0.98%   |
| Goldstar W2443 GSM571C 1920x1080 510x290mm 23.1-inch                                  | 1        | 0.98%   |
| Goldstar W2220 GSM577B 1680x1050 474x296mm 22.0-inch                                  | 1        | 0.98%   |
| Goldstar M2380A GSM57ED 1920x1080 509x286mm 23.0-inch                                 | 1        | 0.98%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                                 | 1        | 0.98%   |
| Goldstar M2262D GSM5755 1920x1080 598x336mm 27.0-inch                                 | 1        | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 31.31%  |
| 1280x1024 (SXGA)   | 20       | 20.2%   |
| 1680x1050 (WSXGA+) | 9        | 9.09%   |
| 1440x900 (WXGA+)   | 7        | 7.07%   |
| 1366x768 (WXGA)    | 7        | 7.07%   |
| 2560x1440 (QHD)    | 4        | 4.04%   |
| 1024x768 (XGA)     | 4        | 4.04%   |
| 1600x900 (HD+)     | 3        | 3.03%   |
| 3840x2160 (4K)     | 2        | 2.02%   |
| 2560x1080          | 2        | 2.02%   |
| 1920x1200 (WUXGA)  | 2        | 2.02%   |
| 1280x800 (WXGA)    | 2        | 2.02%   |
| 3600x1200          | 1        | 1.01%   |
| 2560x1600          | 1        | 1.01%   |
| 2288x1287          | 1        | 1.01%   |
| 1600x1200          | 1        | 1.01%   |
| 1360x768           | 1        | 1.01%   |
| Unknown            | 1        | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 14       | 14.14%  |
| 19      | 12       | 12.12%  |
| 24      | 9        | 9.09%   |
| 23      | 9        | 9.09%   |
| Unknown | 9        | 9.09%   |
| 27      | 8        | 8.08%   |
| 21      | 7        | 7.07%   |
| 20      | 6        | 6.06%   |
| 15      | 5        | 5.05%   |
| 22      | 4        | 4.04%   |
| 41      | 2        | 2.02%   |
| 39      | 2        | 2.02%   |
| 31      | 2        | 2.02%   |
| 18      | 2        | 2.02%   |
| 72      | 1        | 1.01%   |
| 38      | 1        | 1.01%   |
| 37      | 1        | 1.01%   |
| 34      | 1        | 1.01%   |
| 32      | 1        | 1.01%   |
| 29      | 1        | 1.01%   |
| 14      | 1        | 1.01%   |
| 7       | 1        | 1.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 26       | 26.8%   |
| 401-500     | 23       | 23.71%  |
| 301-350     | 18       | 18.56%  |
| Unknown     | 9        | 9.28%   |
| 351-400     | 8        | 8.25%   |
| 801-900     | 4        | 4.12%   |
| 601-700     | 3        | 3.09%   |
| 701-800     | 2        | 2.06%   |
| 901-1000    | 2        | 2.06%   |
| 1501-2000   | 1        | 1.03%   |
| 101-200     | 1        | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 47.31%  |
| 5/4     | 19       | 20.43%  |
| 16/10   | 14       | 15.05%  |
| Unknown | 8        | 8.6%    |
| 4/3     | 4        | 4.3%    |
| 21/9    | 2        | 2.15%   |
| 6/5     | 1        | 1.08%   |
| 3/2     | 1        | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 24.74%  |
| 151-200        | 18       | 18.56%  |
| 141-150        | 15       | 15.46%  |
| 301-350        | 9        | 9.28%   |
| Unknown        | 9        | 9.28%   |
| 501-1000       | 6        | 6.19%   |
| 101-110        | 5        | 5.15%   |
| 351-500        | 4        | 4.12%   |
| 251-300        | 3        | 3.09%   |
| More than 1000 | 1        | 1.03%   |
| 81-90          | 1        | 1.03%   |
| 1-40           | 1        | 1.03%   |
| 131-140        | 1        | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 65       | 70.65%  |
| 101-120 | 10       | 10.87%  |
| Unknown | 9        | 9.78%   |
| 121-160 | 4        | 4.35%   |
| 1-50    | 2        | 2.17%   |
| 161-240 | 2        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 85.26%  |
| 2     | 9        | 9.47%   |
| 0     | 3        | 3.16%   |
| 4     | 1        | 1.05%   |
| 3     | 1        | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 53       | 40.15%  |
| Intel                    | 32       | 24.24%  |
| Qualcomm Atheros         | 9        | 6.82%   |
| Nvidia                   | 9        | 6.82%   |
| Ralink Technology        | 7        | 5.3%    |
| Ralink                   | 3        | 2.27%   |
| Marvell Technology Group | 3        | 2.27%   |
| Broadcom                 | 3        | 2.27%   |
| TP-Link                  | 2        | 1.52%   |
| Samsung Electronics      | 2        | 1.52%   |
| Broadcom Limited         | 2        | 1.52%   |
| ZyXEL Communications     | 1        | 0.76%   |
| VIA Technologies         | 1        | 0.76%   |
| Sitecom Europe           | 1        | 0.76%   |
| NetGear                  | 1        | 0.76%   |
| Huawei Technologies      | 1        | 0.76%   |
| Aquantia                 | 1        | 0.76%   |
| ADMtek                   | 1        | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 24.83%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.45%   |
| Nvidia MCP61 Ethernet                                             | 5        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 2.76%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.07%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.07%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.07%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 2.07%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.38%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 1.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.38%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.38%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.38%   |
| Intel Wireless 7260                                               | 2        | 1.38%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.38%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.69%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.69%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.69%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.69%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.69%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.69%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.69%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 0.69%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.69%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.69%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.69%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.69%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.69%   |
| Intel Wireless-AC 9260                                            | 1        | 0.69%   |
| Intel Wireless 7265                                               | 1        | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.69%   |
| Intel Centrino Advanced-N 6235                                    | 1        | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 0.69%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 27.5%   |
| Ralink Technology     | 7        | 17.5%   |
| Intel                 | 7        | 17.5%   |
| Qualcomm Atheros      | 6        | 15%     |
| Ralink                | 3        | 7.5%    |
| TP-Link               | 2        | 5%      |
| ZyXEL Communications  | 1        | 2.5%    |
| Sitecom Europe        | 1        | 2.5%    |
| NetGear               | 1        | 2.5%    |
| Broadcom              | 1        | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 10%     |
| Realtek RTL8187 Wireless Adapter                               | 2        | 5%      |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 5%      |
| Ralink MT7601U Wireless Adapter                                | 2        | 5%      |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 5%      |
| Intel Wireless 7260                                            | 2        | 5%      |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 2.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 2.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 2.5%    |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 2.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 2.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 2.5%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 2.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 2.5%    |
| Ralink RT5572 Wireless Adapter                                 | 1        | 2.5%    |
| Ralink RT5370 Wireless Adapter                                 | 1        | 2.5%    |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 2.5%    |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 2.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 2.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 2.5%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1        | 2.5%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 2.5%    |
| Intel Wireless-AC 9260                                         | 1        | 2.5%    |
| Intel Wireless 7265                                            | 1        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.5%    |
| Intel Centrino Advanced-N 6235                                 | 1        | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 46       | 46.46%  |
| Intel                    | 27       | 27.27%  |
| Nvidia                   | 9        | 9.09%   |
| Qualcomm Atheros         | 3        | 3.03%   |
| Marvell Technology Group | 3        | 3.03%   |
| Broadcom                 | 3        | 3.03%   |
| Samsung Electronics      | 2        | 2.02%   |
| Broadcom Limited         | 2        | 2.02%   |
| VIA Technologies         | 1        | 1.01%   |
| Huawei Technologies      | 1        | 1.01%   |
| Aquantia                 | 1        | 1.01%   |
| ADMtek                   | 1        | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 34.29%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 4.76%   |
| Nvidia MCP61 Ethernet                                             | 5        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 3.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.86%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 2.86%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.9%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.9%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.9%    |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.95%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.95%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.95%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.95%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.95%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.95%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.95%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.95%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.95%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.95%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.95%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.95%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.95%   |
| Huawei SPN-AL00                                                   | 1        | 0.95%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.95%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.95%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.95%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.95%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 0.95%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.95%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 70.68%  |
| WiFi     | 39       | 29.32%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 87       | 76.99%  |
| WiFi     | 26       | 23.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 71.58%  |
| 2     | 22       | 23.16%  |
| 3     | 4        | 4.21%   |
| 0     | 1        | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 85       | 89.47%  |
| Yes  | 10       | 10.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 42.86%  |
| Cambridge Silicon Radio | 5        | 35.71%  |
| Broadcom                | 3        | 21.43%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 35.71%  |
| Intel Bluetooth Device                              | 3        | 21.43%  |
| Intel Bluetooth wireless interface                  | 2        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.14%   |
| Broadcom Bluetooth Device                           | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 59       | 42.14%  |
| Nvidia                   | 34       | 24.29%  |
| AMD                      | 31       | 22.14%  |
| Creative Labs            | 4        | 2.86%   |
| C-Media Electronics      | 3        | 2.14%   |
| XMOS                     | 1        | 0.71%   |
| VIA Technologies         | 1        | 0.71%   |
| Unknown                  | 1        | 0.71%   |
| Logitech                 | 1        | 0.71%   |
| GN Netcom                | 1        | 0.71%   |
| Focusrite-Novation       | 1        | 0.71%   |
| Creative Technology      | 1        | 0.71%   |
| BEHRINGER International  | 1        | 0.71%   |
| Asahi Kasei Microsystems | 1        | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                 | 10       | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller              | 9        | 5.7%    |
| Nvidia High Definition Audio Controller                                                 | 7        | 4.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                          | 6        | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                     | 6        | 3.8%    |
| Nvidia MCP61 High Definition Audio                                                      | 5        | 3.16%   |
| AMD Starship/Matisse HD Audio Controller                                                | 5        | 3.16%   |
| AMD FCH Azalia Controller                                                               | 5        | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                                         | 4        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                        | 4        | 2.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                     | 4        | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                         | 4        | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                            | 4        | 2.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                  | 4        | 2.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                   | 3        | 1.9%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                     | 3        | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                          | 3        | 1.9%    |
| Intel 200 Series PCH HD Audio                                                           | 3        | 1.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]       | 3        | 1.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                           | 2        | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                                      | 2        | 1.27%   |
| Nvidia GK106 HDMI Audio Controller                                                      | 2        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                           | 2        | 1.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                                       | 2        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                | 2        | 1.27%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                              | 2        | 1.27%   |
| AMD Trinity HDMI Audio Controller                                                       | 2        | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                 | 2        | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                | 2        | 1.27%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                          | 2        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                     | 2        | 1.27%   |
| XMOS HIFI DSD                                                                           | 1        | 0.63%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                      | 1        | 0.63%   |
| Unknown Realtek USB Audio Rear                                                          | 1        | 0.63%   |
| Unknown Realtek USB Audio Front                                                         | 1        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                          | 1        | 0.63%   |
| Nvidia TU104 HD Audio Controller                                                        | 1        | 0.63%   |
| Nvidia MCP67 High Definition Audio                                                      | 1        | 0.63%   |
| Nvidia MCP51 High Definition Audio                                                      | 1        | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                                           | 1        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                      | 1        | 0.63%   |
| Nvidia GF116 High Definition Audio Controller                                           | 1        | 0.63%   |
| Nvidia CK804 AC'97 Audio Controller                                                     | 1        | 0.63%   |
| Logitech Headset H390                                                                   | 1        | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                            | 1        | 0.63%   |
| Intel C610/X99 series chipset HD Audio Controller                                       | 1        | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                          | 1        | 0.63%   |
| Intel Audio device                                                                      | 1        | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio | 1        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller              | 1        | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                        | 1        | 0.63%   |
| GN Netcom Jabra EVOLVE Link MS                                                          | 1        | 0.63%   |
| Focusrite-Novation Scarlett 2i2 Camera                                                  | 1        | 0.63%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                            | 1        | 0.63%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                           | 1        | 0.63%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                      | 1        | 0.63%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                                  | 1        | 0.63%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                               | 1        | 0.63%   |
| C-Media Electronics Q9-1                                                                | 1        | 0.63%   |
| C-Media Electronics CM106 Like Sound Device                                             | 1        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 21.74%  |
| Samsung Electronics | 12       | 17.39%  |
| SK Hynix            | 10       | 14.49%  |
| Kingston            | 7        | 10.14%  |
| Crucial             | 5        | 7.25%   |
| Corsair             | 5        | 7.25%   |
| Micron Technology   | 3        | 4.35%   |
| G.Skill             | 3        | 4.35%   |
| Patriot             | 2        | 2.9%    |
| Unknown (ABCD)      | 1        | 1.45%   |
| Unifosa             | 1        | 1.45%   |
| Team                | 1        | 1.45%   |
| Ramaxel Technology  | 1        | 1.45%   |
| Qimonda             | 1        | 1.45%   |
| Nanya Technology    | 1        | 1.45%   |
| 48spaces            | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 2        | 2.63%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                     | 2        | 2.63%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s               | 2        | 2.63%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                      | 1        | 1.32%   |
| Unknown RAM Module 512MB DIMM 400MT/s                             | 1        | 1.32%   |
| Unknown RAM Module 4096MB DIMM SDRAM                              | 1        | 1.32%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                      | 1        | 1.32%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1        | 1.32%   |
| Unknown RAM Module 2048MB DIMM DDR2                               | 1        | 1.32%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                            | 1        | 1.32%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                            | 1        | 1.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                     | 1        | 1.32%   |
| Unknown RAM Module 1024MB DIMM SDRAM                              | 1        | 1.32%   |
| Unknown RAM Module 1024MB DIMM DDR2                               | 1        | 1.32%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                        | 1        | 1.32%   |
| Unknown RAM e2e4 8192MB DIMM DDR4 2400MT/s                        | 1        | 1.32%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM LPDDR4 2400MT/s | 1        | 1.32%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM 1333MT/s                   | 1        | 1.32%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s               | 1        | 1.32%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2133MT/s                     | 1        | 1.32%   |
| SK Hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s            | 1        | 1.32%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s             | 1        | 1.32%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1        | 1.32%   |
| SK Hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s           | 1        | 1.32%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s           | 1        | 1.32%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s           | 1        | 1.32%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s         | 1        | 1.32%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1        | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.32%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s          | 1        | 1.32%   |
| Samsung RAM M471B1G73AH0-CK0 4096MB SODIMM DDR3 1333MT/s          | 1        | 1.32%   |
| Samsung RAM M4 70T2864FB3-CF7 1024MB SODIMM DDR2 667MT/s          | 1        | 1.32%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1600MT/s            | 1        | 1.32%   |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s              | 1        | 1.32%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM DDR3 1867MT/s            | 1        | 1.32%   |
| Samsung RAM M378A5244CB0-CRC 4096MB DIMM DDR4 2400MT/s            | 1        | 1.32%   |
| Samsung RAM M3 78T2863RZS-CE6 1024MB DIMM DDR2 667MT/s            | 1        | 1.32%   |
| Samsung RAM M3 78T2863QZS-CE6 1024MB DIMM DDR2 667MT/s            | 1        | 1.32%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s            | 1        | 1.32%   |
| Samsung RAM M3 12L2920CZ3-CCC 1024MB DIMM DDR 400MT/s             | 1        | 1.32%   |
| Ramaxel RAM RML1040EG38D6F-533 512MB DIMM DDR2 533MT/s            | 1        | 1.32%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                  | 1        | 1.32%   |
| Patriot RAM PSD44G213341 4096MB DIMM DDR4 3000MT/s                | 1        | 1.32%   |
| Patriot RAM PSD34G1600L2S 4096MB SODIMM DDR3 1600MT/s             | 1        | 1.32%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s             | 1        | 1.32%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s               | 1        | 1.32%   |
| Micron RAM 8JTF25664AZ-1G4D1 2048MB SODIMM DDR3 1333MT/s          | 1        | 1.32%   |
| Micron RAM 16HTF25664AZ-800H1 2048MB DIMM DDR2 800MT/s            | 1        | 1.32%   |
| Kingston RAM SUPER KINGSTEK 2048MB DIMM DDR2 800MT/s              | 1        | 1.32%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1        | 1.32%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                      | 1        | 1.32%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1333MT/s                 | 1        | 1.32%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s            | 1        | 1.32%   |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1866MT/s            | 1        | 1.32%   |
| Kingston RAM 99U5471-052.A00LF 8192MB DIMM DDR3 1333MT/s          | 1        | 1.32%   |
| Kingston RAM 99U5429-007.A00LF 2048MB DIMM DDR2 800MT/s           | 1        | 1.32%   |
| Kingston RAM 9905471-011.A00LF 4096MB DIMM DDR3 1600MT/s          | 1        | 1.32%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s            | 1        | 1.32%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s           | 1        | 1.32%   |
| G.Skill RAM F3-1600C9-8GXM 8192MB DIMM DDR3 1600MT/s              | 1        | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 24       | 39.34%  |
| DDR2    | 14       | 22.95%  |
| DDR4    | 13       | 21.31%  |
| SDRAM   | 4        | 6.56%   |
| Unknown | 3        | 4.92%   |
| DDR     | 2        | 3.28%   |
| LPDDR4  | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 50       | 84.75%  |
| SODIMM | 9        | 15.25%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 20       | 31.75%  |
| 4096  | 15       | 23.81%  |
| 8192  | 14       | 22.22%  |
| 1024  | 7        | 11.11%  |
| 16384 | 4        | 6.35%   |
| 512   | 2        | 3.17%   |
| 65536 | 1        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 19.4%   |
| 800     | 9        | 13.43%  |
| 1333    | 7        | 10.45%  |
| 2133    | 6        | 8.96%   |
| 667     | 5        | 7.46%   |
| 2400    | 4        | 5.97%   |
| 400     | 4        | 5.97%   |
| Unknown | 4        | 5.97%   |
| 3600    | 2        | 2.99%   |
| 3200    | 2        | 2.99%   |
| 3000    | 2        | 2.99%   |
| 1866    | 2        | 2.99%   |
| 49926   | 1        | 1.49%   |
| 2667    | 1        | 1.49%   |
| 2048    | 1        | 1.49%   |
| 1867    | 1        | 1.49%   |
| 1334    | 1        | 1.49%   |
| 1066    | 1        | 1.49%   |
| 533     | 1        | 1.49%   |

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
| Logitech                      | 4        | 26.67%  |
| Z-Star Microelectronics       | 1        | 6.67%   |
| SunplusIT                     | 1        | 6.67%   |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Samsung Electronics           | 1        | 6.67%   |
| Microsoft                     | 1        | 6.67%   |
| KYE Systems (Mouse Systems)   | 1        | 6.67%   |
| Guillemot                     | 1        | 6.67%   |
| Genesys Logic                 | 1        | 6.67%   |
| Chicony Electronics           | 1        | 6.67%   |
| ARC International             | 1        | 6.67%   |
| Acer                          | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 2        | 13.33%  |
| Z-Star Sirius USB2.0 Camera               | 1        | 6.67%   |
| SunplusIT USB 2.0 Camera                  | 1        | 6.67%   |
| Sunplus NexiGo N930E FHD Webcam           | 1        | 6.67%   |
| Samsung Galaxy series, misc. (MTP mode)   | 1        | 6.67%   |
| Microsoft LifeCam HD-3000                 | 1        | 6.67%   |
| Logitech QuickCam Zoom                    | 1        | 6.67%   |
| Logitech HD Webcam C525                   | 1        | 6.67%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 6.67%   |
| Guillemot Hercules HD Sunset              | 1        | 6.67%   |
| Genesys Logic Camera                      | 1        | 6.67%   |
| Chicony ASUS USB2.0 Webcam                | 1        | 6.67%   |
| ARC International Camera                  | 1        | 6.67%   |
| Acer Integrated Camera                    | 1        | 6.67%   |

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
| 0     | 79       | 83.16%  |
| 1     | 15       | 15.79%  |
| 2     | 1        | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 33.33%  |
| Net/wireless             | 3        | 20%     |
| Unassigned class         | 2        | 13.33%  |
| Sound                    | 2        | 13.33%  |
| Communication controller | 2        | 13.33%  |
| Dvb card                 | 1        | 6.67%   |

