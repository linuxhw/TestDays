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
| 5.4.0-52-generic      | 8        | 7.69%   |
| 5.4.0-42-generic      | 7        | 6.73%   |
| 5.8.0-50-generic      | 6        | 5.77%   |
| 5.4.0-54-generic      | 5        | 4.81%   |
| 5.4.0-67-generic      | 4        | 3.85%   |
| 5.4.0-40-generic      | 4        | 3.85%   |
| 5.4.0-29-generic      | 4        | 3.85%   |
| 5.11.0-27-generic     | 4        | 3.85%   |
| 5.4.0-77-generic      | 3        | 2.88%   |
| 5.4.0-73-generic      | 3        | 2.88%   |
| 5.4.0-48-generic      | 3        | 2.88%   |
| 5.4.0-47-generic      | 3        | 2.88%   |
| 5.4.0-37-generic      | 3        | 2.88%   |
| 5.4.0-33-generic      | 3        | 2.88%   |
| 5.4.0-26-generic      | 3        | 2.88%   |
| 5.8.0-63-generic      | 2        | 1.92%   |
| 5.8.0-59-generic      | 2        | 1.92%   |
| 5.8.0-53-generic      | 2        | 1.92%   |
| 5.8.0-45-generic      | 2        | 1.92%   |
| 5.8.0-41-generic      | 2        | 1.92%   |
| 5.4.0-72-generic      | 2        | 1.92%   |
| 5.4.0-66-generic      | 2        | 1.92%   |
| 5.4.0-60-generic      | 2        | 1.92%   |
| 5.11.0-38-generic     | 2        | 1.92%   |
| 5.11.0-34-generic     | 2        | 1.92%   |
| 5.8.0-7630-generic    | 1        | 0.96%   |
| 5.8.0-55-generic      | 1        | 0.96%   |
| 5.8.0-48-generic      | 1        | 0.96%   |
| 5.8.0-43-generic      | 1        | 0.96%   |
| 5.6.15-050615-generic | 1        | 0.96%   |
| 5.6.0-1052-oem        | 1        | 0.96%   |
| 5.4.30-dli            | 1        | 0.96%   |
| 5.4.0-88-generic      | 1        | 0.96%   |
| 5.4.0-81-generic      | 1        | 0.96%   |
| 5.4.0-75-generic      | 1        | 0.96%   |
| 5.4.0-70-lowlatency   | 1        | 0.96%   |
| 5.4.0-65-generic      | 1        | 0.96%   |
| 5.4.0-64-generic      | 1        | 0.96%   |
| 5.4.0-59-generic      | 1        | 0.96%   |
| 5.4.0-58-generic      | 1        | 0.96%   |
| 5.4.0-53-generic      | 1        | 0.96%   |
| 5.4.0-31-generic      | 1        | 0.96%   |
| 5.3.18-dli            | 1        | 0.96%   |
| 5.14.0-051400-generic | 1        | 0.96%   |
| 5.11.0-37-generic     | 1        | 0.96%   |
| 5.11.0-36-generic     | 1        | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 65       | 65%     |
| 5.8.0   | 20       | 20%     |
| 5.11.0  | 10       | 10%     |
| 5.6.15  | 1        | 1%      |
| 5.6.0   | 1        | 1%      |
| 5.4.30  | 1        | 1%      |
| 5.3.18  | 1        | 1%      |
| 5.14.0  | 1        | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 66       | 66%     |
| 5.8     | 20       | 20%     |
| 5.11    | 10       | 10%     |
| 5.6     | 2        | 2%      |
| 5.3     | 1        | 1%      |
| 5.14    | 1        | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 100      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 96       | 96%     |
| LXDE       | 2        | 2%      |
| X-Cinnamon | 1        | 1%      |
| GNOME      | 1        | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 94       | 94%     |
| Tty     | 5        | 5%      |
| Unknown | 1        | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 46       | 45.54%  |
| Unknown | 39       | 38.61%  |
| TDM     | 7        | 6.93%   |
| GDM     | 6        | 5.94%   |
| LightDM | 3        | 2.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 27%     |
| fr_FR   | 11       | 11%     |
| pt_BR   | 9        | 9%      |
| it_IT   | 9        | 9%      |
| ru_RU   | 5        | 5%      |
| de_DE   | 5        | 5%      |
| C       | 5        | 5%      |
| en_GB   | 4        | 4%      |
| en_AU   | 4        | 4%      |
| hu_HU   | 2        | 2%      |
| es_ES   | 2        | 2%      |
| en_ZA   | 2        | 2%      |
| cs_CZ   | 2        | 2%      |
| sv_SE   | 1        | 1%      |
| nl_NL   | 1        | 1%      |
| ja_JP   | 1        | 1%      |
| fi_FI   | 1        | 1%      |
| es_PE   | 1        | 1%      |
| es_MX   | 1        | 1%      |
| es_CR   | 1        | 1%      |
| es_CO   | 1        | 1%      |
| en_SG   | 1        | 1%      |
| en_CA   | 1        | 1%      |
| el_GR   | 1        | 1%      |
| de_CH   | 1        | 1%      |
| Unknown | 1        | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 69       | 69%     |
| EFI  | 31       | 31%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 93       | 93%     |
| Overlay | 4        | 4%      |
| Xfs     | 2        | 2%      |
| Btrfs   | 1        | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 40.59%  |
| MBR     | 34       | 33.66%  |
| GPT     | 26       | 25.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 84%     |
| Yes       | 16       | 16%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 69%     |
| Yes       | 31       | 31%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 18%     |
| Hewlett-Packard     | 13       | 13%     |
| MSI                 | 11       | 11%     |
| Gigabyte Technology | 10       | 10%     |
| ASRock              | 10       | 10%     |
| Dell                | 9        | 9%      |
| Lenovo              | 6        | 6%      |
| Intel               | 5        | 5%      |
| Acer                | 3        | 3%      |
| Positivo            | 2        | 2%      |
| Pegatron            | 2        | 2%      |
| AAEON               | 2        | 2%      |
| ZOTAC               | 1        | 1%      |
| Packard Bell        | 1        | 1%      |
| IBM                 | 1        | 1%      |
| Huanan              | 1        | 1%      |
| HARDKERNEL          | 1        | 1%      |
| Fujitsu Siemens     | 1        | 1%      |
| Foxconn             | 1        | 1%      |
| Biostar             | 1        | 1%      |
| Unknown             | 1        | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7B89                         | 2        | 2%      |
| ASRock N68-VS3 UCC                  | 2        | 2%      |
| AAEON MF-001                        | 2        | 2%      |
| ZOTAC NM10                          | 1        | 1%      |
| Positivo POS-MI945AA                | 1        | 1%      |
| Positivo POS-EIH61CE                | 1        | 1%      |
| Pegatron NC689AA-ABA s3700y         | 1        | 1%      |
| Pegatron AY652AA-ABA s5310y         | 1        | 1%      |
| Packard Bell imedia S1350           | 1        | 1%      |
| MSI MS-7C37                         | 1        | 1%      |
| MSI MS-7B86                         | 1        | 1%      |
| MSI MS-7994                         | 1        | 1%      |
| MSI MS-7846                         | 1        | 1%      |
| MSI MS-7680                         | 1        | 1%      |
| MSI MS-7592                         | 1        | 1%      |
| MSI MS-7309                         | 1        | 1%      |
| MSI ER883AA-ABA M7470N              | 1        | 1%      |
| MSI Compaq dx2200 MT                | 1        | 1%      |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 1%      |
| Lenovo ThinkCentre M93z 10AD002DMZ  | 1        | 1%      |
| Lenovo ThinkCentre M58p 7220W21     | 1        | 1%      |
| Lenovo ThinkCentre M58p 6136A66     | 1        | 1%      |
| Lenovo H50-50 90B60081IX            | 1        | 1%      |
| Lenovo H50-30g 90AS0002BR           | 1        | 1%      |
| Intel STK1AW32SC                    | 1        | 1%      |
| Intel H55                           | 1        | 1%      |
| Intel DN2800MT AAG23738-801         | 1        | 1%      |
| Intel DG31PR AAD97573-302           | 1        | 1%      |
| Intel ChiefRiver                    | 1        | 1%      |
| IBM eServer x3105 -[434722J]-       | 1        | 1%      |
| Huanan X99-TF                       | 1        | 1%      |
| HP Z230 Tower Workstation           | 1        | 1%      |
| HP xw9400 Workstation               | 1        | 1%      |
| HP xw9300 Workstation               | 1        | 1%      |
| HP t620 Quad Core TC                | 1        | 1%      |
| HP t620 Dual Core TC                | 1        | 1%      |
| HP ProDesk 600 G1 DM                | 1        | 1%      |
| HP EliteDesk 800 G3 SFF             | 1        | 1%      |
| HP Compaq Elite 8300 CMT            | 1        | 1%      |
| HP Compaq dc7800 Small Form Factor  | 1        | 1%      |
| HP Compaq dc7600 Small Form Factor  | 1        | 1%      |
| HP Compaq dc5800 Microtower         | 1        | 1%      |
| HP Compaq 8200 Elite SFF PC         | 1        | 1%      |
| HP Compaq 6000 Pro SFF PC           | 1        | 1%      |
| HARDKERNEL ODROID-H2                | 1        | 1%      |
| Gigabyte Z370P D3                   | 1        | 1%      |
| Gigabyte X570 GAMING X              | 1        | 1%      |
| Gigabyte K8M800-8237                | 1        | 1%      |
| Gigabyte H81M-DS2                   | 1        | 1%      |
| Gigabyte H61M-DS2H                  | 1        | 1%      |
| Gigabyte GA-870A-UD3                | 1        | 1%      |
| Gigabyte F2A88XM-HD3                | 1        | 1%      |
| Gigabyte B450M H                    | 1        | 1%      |
| Gigabyte B250M-D3H                  | 1        | 1%      |
| Gigabyte 965P-DS3                   | 1        | 1%      |
| Fujitsu Siemens ESPRIMO P5925       | 1        | 1%      |
| Foxconn WU115EA-AKB 100eu CZ100     | 1        | 1%      |
| Dell XPS 8300                       | 1        | 1%      |
| Dell Vostro 200                     | 1        | 1%      |
| Dell Precision T3610                | 1        | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 6        | 6%      |
| Lenovo ThinkCentre      | 3        | 3%      |
| Dell OptiPlex           | 3        | 3%      |
| Acer Aspire             | 3        | 3%      |
| MSI MS-7B89             | 2        | 2%      |
| HP t620                 | 2        | 2%      |
| ASRock N68-VS3          | 2        | 2%      |
| AAEON MF-001            | 2        | 2%      |
| ZOTAC NM10              | 1        | 1%      |
| Positivo POS-MI945AA    | 1        | 1%      |
| Positivo POS-EIH61CE    | 1        | 1%      |
| Pegatron NC689AA-ABA    | 1        | 1%      |
| Pegatron AY652AA-ABA    | 1        | 1%      |
| Packard Bell imedia     | 1        | 1%      |
| MSI MS-7C37             | 1        | 1%      |
| MSI MS-7B86             | 1        | 1%      |
| MSI MS-7994             | 1        | 1%      |
| MSI MS-7846             | 1        | 1%      |
| MSI MS-7680             | 1        | 1%      |
| MSI MS-7592             | 1        | 1%      |
| MSI MS-7309             | 1        | 1%      |
| MSI ER883AA-ABA         | 1        | 1%      |
| MSI Compaq              | 1        | 1%      |
| Lenovo ThinkStation     | 1        | 1%      |
| Lenovo H50-50           | 1        | 1%      |
| Lenovo H50-30g          | 1        | 1%      |
| Intel STK1AW32SC        | 1        | 1%      |
| Intel H55               | 1        | 1%      |
| Intel DN2800MT          | 1        | 1%      |
| Intel DG31PR            | 1        | 1%      |
| Intel ChiefRiver        | 1        | 1%      |
| IBM eServer             | 1        | 1%      |
| Huanan X99-TF           | 1        | 1%      |
| HP Z230                 | 1        | 1%      |
| HP xw9400               | 1        | 1%      |
| HP xw9300               | 1        | 1%      |
| HP ProDesk              | 1        | 1%      |
| HP EliteDesk            | 1        | 1%      |
| HARDKERNEL ODROID-H2    | 1        | 1%      |
| Gigabyte Z370P          | 1        | 1%      |
| Gigabyte X570           | 1        | 1%      |
| Gigabyte K8M800-8237    | 1        | 1%      |
| Gigabyte H81M-DS2       | 1        | 1%      |
| Gigabyte H61M-DS2H      | 1        | 1%      |
| Gigabyte GA-870A-UD3    | 1        | 1%      |
| Gigabyte F2A88XM-HD3    | 1        | 1%      |
| Gigabyte B450M          | 1        | 1%      |
| Gigabyte B250M-D3H      | 1        | 1%      |
| Gigabyte 965P-DS3       | 1        | 1%      |
| Fujitsu Siemens ESPRIMO | 1        | 1%      |
| Foxconn WU115EA-AKB     | 1        | 1%      |
| Dell XPS                | 1        | 1%      |
| Dell Vostro             | 1        | 1%      |
| Dell Precision          | 1        | 1%      |
| Dell Inspiron           | 1        | 1%      |
| Dell DM061              | 1        | 1%      |
| Dell Dimension          | 1        | 1%      |
| Biostar GF7025-M2       | 1        | 1%      |
| ASUS Z170               | 1        | 1%      |
| ASUS V-P8H67E           | 1        | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 9%      |
| 2007 | 9        | 9%      |
| 2009 | 8        | 8%      |
| 2008 | 8        | 8%      |
| 2014 | 7        | 7%      |
| 2012 | 7        | 7%      |
| 2020 | 6        | 6%      |
| 2011 | 6        | 6%      |
| 2010 | 6        | 6%      |
| 2021 | 5        | 5%      |
| 2018 | 5        | 5%      |
| 2017 | 5        | 5%      |
| 2015 | 5        | 5%      |
| 2013 | 5        | 5%      |
| 2016 | 3        | 3%      |
| 2006 | 3        | 3%      |
| 2005 | 3        | 3%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 100      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 98       | 98%     |
| Enabled  | 2        | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 100      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 32       | 31.68%  |
| 1.01-2.0        | 15       | 14.85%  |
| 8.01-16.0       | 15       | 14.85%  |
| 16.01-24.0      | 14       | 13.86%  |
| 4.01-8.0        | 13       | 12.87%  |
| 32.01-64.0      | 7        | 6.93%   |
| 0.51-1.0        | 2        | 1.98%   |
| More than 256.0 | 1        | 0.99%   |
| 24.01-32.0      | 1        | 0.99%   |
| 2.01-3.0        | 1        | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 52       | 50.49%  |
| 2.01-3.0  | 19       | 18.45%  |
| 0.51-1.0  | 15       | 14.56%  |
| 4.01-8.0  | 9        | 8.74%   |
| 3.01-4.0  | 5        | 4.85%   |
| 8.01-16.0 | 2        | 1.94%   |
| 0.01-0.5  | 1        | 0.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 50%     |
| 2      | 32       | 32%     |
| 4      | 6        | 6%      |
| 3      | 6        | 6%      |
| 5      | 3        | 3%      |
| 14     | 1        | 1%      |
| 7      | 1        | 1%      |
| 0      | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 63       | 63%     |
| No        | 37       | 37%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 99       | 99%     |
| No        | 1        | 1%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 59%     |
| Yes       | 41       | 41%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 85%     |
| Yes       | 15       | 15%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 14       | 13.86%  |
| France       | 11       | 10.89%  |
| Brazil       | 10       | 9.9%    |
| Italy        | 9        | 8.91%   |
| Germany      | 7        | 6.93%   |
| Russia       | 5        | 4.95%   |
| Hungary      | 5        | 4.95%   |
| Switzerland  | 4        | 3.96%   |
| Australia    | 4        | 3.96%   |
| Spain        | 3        | 2.97%   |
| Netherlands  | 3        | 2.97%   |
| Czechia      | 3        | 2.97%   |
| South Africa | 2        | 1.98%   |
| Puerto Rico  | 2        | 1.98%   |
| Mexico       | 2        | 1.98%   |
| Greece       | 2        | 1.98%   |
| Finland      | 2        | 1.98%   |
| UK           | 1        | 0.99%   |
| Sweden       | 1        | 0.99%   |
| Singapore    | 1        | 0.99%   |
| Romania      | 1        | 0.99%   |
| Peru         | 1        | 0.99%   |
| New Zealand  | 1        | 0.99%   |
| Malaysia     | 1        | 0.99%   |
| Japan        | 1        | 0.99%   |
| Costa Rica   | 1        | 0.99%   |
| Colombia     | 1        | 0.99%   |
| Canada       | 1        | 0.99%   |
| Belgium      | 1        | 0.99%   |
| Belarus      | 1        | 0.99%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Rome                | 4        | 3.92%   |
| Windsor             | 2        | 1.96%   |
| Prague              | 2        | 1.96%   |
| Milan               | 2        | 1.96%   |
| Eger                | 2        | 1.96%   |
| Cuernavaca          | 2        | 1.96%   |
| Cayey               | 2        | 1.96%   |
| Augsburg            | 2        | 1.96%   |
| Annecy              | 2        | 1.96%   |
| Zurich              | 1        | 0.98%   |
| Yelizovo            | 1        | 0.98%   |
| Wiesbaden           | 1        | 0.98%   |
| Wellington          | 1        | 0.98%   |
| Vlaardingen         | 1        | 0.98%   |
| Vitry-sur-Seine     | 1        | 0.98%   |
| Vaxjo               | 1        | 0.98%   |
| Vanderbijlpark      | 1        | 0.98%   |
| Valls               | 1        | 0.98%   |
| Valinhos            | 1        | 0.98%   |
| Valencia            | 1        | 0.98%   |
| Treviso             | 1        | 0.98%   |
| Tourcoing           | 1        | 0.98%   |
| Toronto             | 1        | 0.98%   |
| The Hague           | 1        | 0.98%   |
| Springfield         | 1        | 0.98%   |
| Spokane             | 1        | 0.98%   |
| Sora                | 1        | 0.98%   |
| Singapore           | 1        | 0.98%   |
| Sandorfalva         | 1        | 0.98%   |
| Roseburg            | 1        | 0.98%   |
| Rio de Janeiro      | 1        | 0.98%   |
| Raleigh             | 1        | 0.98%   |
| Porto Alegre        | 1        | 0.98%   |
| Portbail            | 1        | 0.98%   |
| Periers             | 1        | 0.98%   |
| P?�cs               | 1        | 0.98%   |
| Passos              | 1        | 0.98%   |
| Pacatuba            | 1        | 0.98%   |
| Oradea              | 1        | 0.98%   |
| Omsk                | 1        | 0.98%   |
| Oceanside           | 1        | 0.98%   |
| Novy Jicin          | 1        | 0.98%   |
| Neuchatel           | 1        | 0.98%   |
| Munich              | 1        | 0.98%   |
| Mount Waverley      | 1        | 0.98%   |
| Moscow              | 1        | 0.98%   |
| Moordrecht          | 1        | 0.98%   |
| Montross            | 1        | 0.98%   |
| Montreuil           | 1        | 0.98%   |
| Montlhery           | 1        | 0.98%   |
| Mogilev             | 1        | 0.98%   |
| Mobile              | 1        | 0.98%   |
| Menen               | 1        | 0.98%   |
| Medellín           | 1        | 0.98%   |
| Marlow              | 1        | 0.98%   |
| Lovens              | 1        | 0.98%   |
| Le Mesnil-en-Thelle | 1        | 0.98%   |
| Le Chevain          | 1        | 0.98%   |
| Langenhagen         | 1        | 0.98%   |
| Kuala Lumpur        | 1        | 0.98%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 39       | 64     | 26%     |
| Seagate             | 39       | 48     | 26%     |
| Samsung Electronics | 18       | 31     | 12%     |
| Kingston            | 8        | 8      | 5.33%   |
| Toshiba             | 7        | 7      | 4.67%   |
| Unknown             | 5        | 6      | 3.33%   |
| Hitachi             | 5        | 6      | 3.33%   |
| SanDisk             | 3        | 3      | 2%      |
| China               | 3        | 3      | 2%      |
| A-DATA Technology   | 3        | 3      | 2%      |
| PNY                 | 2        | 2      | 1.33%   |
| MAXTOR              | 2        | 2      | 1.33%   |
| Transcend           | 1        | 1      | 0.67%   |
| Team                | 1        | 1      | 0.67%   |
| PNY USB             | 1        | 1      | 0.67%   |
| OCZ                 | 1        | 1      | 0.67%   |
| LONDISK             | 1        | 1      | 0.67%   |
| Lexar               | 1        | 1      | 0.67%   |
| Leven               | 1        | 1      | 0.67%   |
| LDLC                | 1        | 1      | 0.67%   |
| JMicron             | 1        | 1      | 0.67%   |
| Intel               | 1        | 1      | 0.67%   |
| HGST                | 1        | 1      | 0.67%   |
| Hewlett-Packard     | 1        | 6      | 0.67%   |
| GOODRAM             | 1        | 1      | 0.67%   |
| Fujitsu             | 1        | 1      | 0.67%   |
| Crucial             | 1        | 1      | 0.67%   |
| Corsair             | 1        | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 2.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 1.2%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 1.2%    |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 1.2%    |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 1.2%    |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 1.2%    |
| Unknown M52516  16GB                | 2        | 1.2%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 1.2%    |
| Seagate ST380815AS 80GB             | 2        | 1.2%    |
| Seagate ST3500418AS 500GB           | 2        | 1.2%    |
| Seagate ST3360320AS 360GB           | 2        | 1.2%    |
| Seagate ST3250410AS 250GB           | 2        | 1.2%    |
| Seagate ST3250310AS 250GB           | 2        | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 1.2%    |
| Samsung SSD 850 EVO 250GB           | 2        | 1.2%    |
| Samsung HD161HJ 160GB               | 2        | 1.2%    |
| Samsung HD080HJ 80GB                | 2        | 1.2%    |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.2%    |
| China SATA SSD 512GB                | 2        | 1.2%    |
| A-DATA SU650 240GB SSD              | 2        | 1.2%    |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.6%    |
| WDC WD800JD-75JNA0 80GB             | 1        | 0.6%    |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.6%    |
| WDC WD7501AALS-00J7B1 752GB         | 1        | 0.6%    |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.6%    |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.6%    |
| WDC WD5000BPKX-66HPJT0 500GB        | 1        | 0.6%    |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.6%    |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.6%    |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.6%    |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 0.6%    |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.6%    |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.6%    |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.6%    |
| WDC WD3200BEVT-60A23T0 320GB        | 1        | 0.6%    |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.6%    |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 0.6%    |
| WDC WD2500JS-75NCB3 250GB           | 1        | 0.6%    |
| WDC WD2500JD-00HBB0 250GB           | 1        | 0.6%    |
| WDC WD2500AAKX-07U6AA0 250GB        | 1        | 0.6%    |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 0.6%    |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.6%    |
| WDC WD1600BB-00RDA0 160GB           | 1        | 0.6%    |
| WDC WD1600AAJS-60B4A0 160GB         | 1        | 0.6%    |
| WDC WD15EARS-22MVWB0 1TB            | 1        | 0.6%    |
| WDC WD10EZRZ-00HTKB0 1TB            | 1        | 0.6%    |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 0.6%    |
| WDC WD10EAVS-14M4B0 1TB             | 1        | 0.6%    |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 0.6%    |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 0.6%    |
| WDC WD10EALX-759BA1 1TB             | 1        | 0.6%    |
| WDC WD10EALS-00Z8A0 1TB             | 1        | 0.6%    |
| Unknown SD/MMC/MS PRO 128GB         | 1        | 0.6%    |
| Unknown MMC Card  32GB              | 1        | 0.6%    |
| Unknown MMC Card  128GB             | 1        | 0.6%    |
| Unknown CJTD4R  64GB                | 1        | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 47     | 39.58%  |
| WDC                 | 34       | 55     | 35.42%  |
| Samsung Electronics | 8        | 9      | 8.33%   |
| Toshiba             | 5        | 5      | 5.21%   |
| Hitachi             | 5        | 6      | 5.21%   |
| MAXTOR              | 2        | 2      | 2.08%   |
| Unknown             | 1        | 1      | 1.04%   |
| JMicron             | 1        | 1      | 1.04%   |
| HGST                | 1        | 1      | 1.04%   |
| Fujitsu             | 1        | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 18.75%  |
| Kingston            | 8        | 8      | 16.67%  |
| WDC                 | 7        | 9      | 14.58%  |
| SanDisk             | 3        | 3      | 6.25%   |
| China               | 3        | 3      | 6.25%   |
| Toshiba             | 2        | 2      | 4.17%   |
| PNY                 | 2        | 2      | 4.17%   |
| A-DATA Technology   | 2        | 2      | 4.17%   |
| Transcend           | 1        | 1      | 2.08%   |
| Team                | 1        | 1      | 2.08%   |
| PNY USB             | 1        | 1      | 2.08%   |
| OCZ                 | 1        | 1      | 2.08%   |
| LONDISK             | 1        | 1      | 2.08%   |
| Lexar               | 1        | 1      | 2.08%   |
| Leven               | 1        | 1      | 2.08%   |
| LDLC                | 1        | 1      | 2.08%   |
| Hewlett-Packard     | 1        | 6      | 2.08%   |
| GOODRAM             | 1        | 1      | 2.08%   |
| Crucial             | 1        | 1      | 2.08%   |
| Corsair             | 1        | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 74       | 128    | 57.81%  |
| SSD     | 46       | 58     | 35.94%  |
| MMC     | 4        | 5      | 3.13%   |
| NVMe    | 3        | 12     | 2.34%   |
| Unknown | 1        | 1      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 95       | 182    | 88.79%  |
| SAS  | 5        | 5      | 4.67%   |
| MMC  | 4        | 5      | 3.74%   |
| NVMe | 3        | 12     | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 82       | 118    | 67.77%  |
| 0.51-1.0   | 29       | 48     | 23.97%  |
| 3.01-4.0   | 4        | 12     | 3.31%   |
| 2.01-3.0   | 3        | 3      | 2.48%   |
| 1.01-2.0   | 3        | 5      | 2.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 28.71%  |
| 251-500        | 21       | 20.79%  |
| 1001-2000      | 12       | 11.88%  |
| 501-1000       | 10       | 9.9%    |
| 51-100         | 9        | 8.91%   |
| More than 3000 | 8        | 7.92%   |
| 2001-3000      | 5        | 4.95%   |
| 21-50          | 3        | 2.97%   |
| 1-20           | 3        | 2.97%   |
| Unknown        | 1        | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 39       | 38.61%  |
| 21-50          | 17       | 16.83%  |
| 101-250        | 13       | 12.87%  |
| 501-1000       | 8        | 7.92%   |
| 1001-2000      | 6        | 5.94%   |
| 51-100         | 6        | 5.94%   |
| 251-500        | 5        | 4.95%   |
| More than 3000 | 3        | 2.97%   |
| 2001-3000      | 3        | 2.97%   |
| Unknown        | 1        | 0.99%   |

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
| Works    | 51       | 108    | 45.13%  |
| Detected | 47       | 78     | 41.59%  |
| Malfunc  | 14       | 17     | 12.39%  |
| Failed   | 1        | 1      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 62       | 55.36%  |
| AMD                       | 20       | 17.86%  |
| Nvidia                    | 13       | 11.61%  |
| JMicron Technology        | 5        | 4.46%   |
| Marvell Technology Group  | 4        | 3.57%   |
| VIA Technologies          | 2        | 1.79%   |
| LSI Logic / Symbios Logic | 2        | 1.79%   |
| ASMedia Technology        | 2        | 1.79%   |
| Samsung Electronics       | 1        | 0.89%   |
| ADATA Technology          | 1        | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 8.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 5.56%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 3.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 3.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 3.7%    |
| Nvidia MCP61 IDE                                                                        | 5        | 3.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 3.09%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 3.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.47%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.85%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 1.23%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 1.23%   |
| Nvidia CK804 IDE                                                                        | 2        | 1.23%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.23%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.23%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.23%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.23%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 1.23%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 1.23%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.23%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.62%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.62%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.62%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.62%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.62%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.62%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.62%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.62%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.62%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.62%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.62%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.62%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.62%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.62%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.62%   |
| Intel SSD 660P Series                                                                   | 1        | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.62%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.62%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.62%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.62%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.62%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 0.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 55       | 48.67%  |
| IDE  | 49       | 43.36%  |
| RAID | 4        | 3.54%   |
| NVMe | 3        | 2.65%   |
| SCSI | 2        | 1.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 68       | 68%     |
| AMD    | 32       | 32%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 3%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 3%      |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3%      |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 2%      |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 2%      |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 2%      |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2%      |
| AMD Athlon II X2 250 Processor              | 2        | 2%      |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 2%      |
| AMD A10-6800K APU with Radeon HD Graphics   | 2        | 2%      |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1%      |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 1%      |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 1%      |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 1%      |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1%      |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1%      |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1%      |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1%      |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 1%      |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1%      |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1%      |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1%      |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1%      |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 1%      |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1%      |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 1%      |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 1%      |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1%      |
| Intel Core i5-4440S CPU @ 2.80GHz           | 1        | 1%      |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1%      |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1%      |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 1%      |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 1%      |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1%      |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1%      |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 1%      |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1%      |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1%      |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 1%      |
| Intel Core 2 Quad CPU @ 2.40GHz             | 1        | 1%      |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E6850 @ 3.00GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1%      |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 1%      |
| Intel Core 2 CPU 6420 @ 2.13GHz             | 1        | 1%      |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1        | 1%      |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 1%      |
| Intel Celeron J4105 CPU @ 1.50GHz           | 1        | 1%      |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1%      |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1%      |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1        | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 18%     |
| Intel Core 2 Duo        | 10       | 10%     |
| Intel Core i3           | 6        | 6%      |
| Intel Atom              | 6        | 6%      |
| Intel Celeron           | 5        | 5%      |
| AMD Ryzen 5             | 5        | 5%      |
| AMD Athlon 64 X2        | 5        | 5%      |
| Intel Xeon              | 4        | 4%      |
| Intel Core 2 Quad       | 4        | 4%      |
| Intel Core 2            | 4        | 4%      |
| AMD Athlon II X2        | 4        | 4%      |
| Intel Core i7           | 3        | 3%      |
| AMD Ryzen 7             | 3        | 3%      |
| Intel Pentium Dual-Core | 2        | 2%      |
| Intel Pentium Dual      | 2        | 2%      |
| Intel Pentium 4         | 2        | 2%      |
| AMD Sempron             | 2        | 2%      |
| AMD GX                  | 2        | 2%      |
| AMD Athlon 64           | 2        | 2%      |
| AMD A10                 | 2        | 2%      |
| Intel Pentium Gold      | 1        | 1%      |
| Intel Pentium           | 1        | 1%      |
| AMD Ryzen Threadripper  | 1        | 1%      |
| AMD Quad-Core Opteron   | 1        | 1%      |
| AMD Phenom II X3        | 1        | 1%      |
| AMD Opteron             | 1        | 1%      |
| AMD FX                  | 1        | 1%      |
| AMD E                   | 1        | 1%      |
| AMD Athlon X4           | 1        | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 50       | 50%     |
| 4      | 29       | 29%     |
| 6      | 7        | 7%      |
| 1      | 7        | 7%      |
| 8      | 4        | 4%      |
| 64     | 1        | 1%      |
| 12     | 1        | 1%      |
| 3      | 1        | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 98%     |
| 2      | 2        | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 66%     |
| 2      | 34       | 34%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 100      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 15%     |
| 0x206a7    | 11       | 11%     |
| 0x306c3    | 7        | 7%      |
| 0x1067a    | 7        | 7%      |
| 0x906e9    | 3        | 3%      |
| 0x6fd      | 3        | 3%      |
| 0x6fb      | 3        | 3%      |
| 0x6f6      | 3        | 3%      |
| 0x406c4    | 3        | 3%      |
| 0x306a9    | 3        | 3%      |
| 0x10676    | 3        | 3%      |
| 0x08701021 | 3        | 3%      |
| 0x506e3    | 2        | 2%      |
| 0x20655    | 2        | 2%      |
| 0x106ca    | 2        | 2%      |
| 0x08701013 | 2        | 2%      |
| 0x0800820d | 2        | 2%      |
| 0x0700010f | 2        | 2%      |
| 0x06001119 | 2        | 2%      |
| 0x010000c8 | 2        | 2%      |
| 0xf65      | 1        | 1%      |
| 0xf4a      | 1        | 1%      |
| 0xa0653    | 1        | 1%      |
| 0x906ea    | 1        | 1%      |
| 0x706a1    | 1        | 1%      |
| 0x6f7      | 1        | 1%      |
| 0x6f2      | 1        | 1%      |
| 0x306f2    | 1        | 1%      |
| 0x306e4    | 1        | 1%      |
| 0x30678    | 1        | 1%      |
| 0x30661    | 1        | 1%      |
| 0x206d7    | 1        | 1%      |
| 0x10677    | 1        | 1%      |
| 0x0830104d | 1        | 1%      |
| 0x06003106 | 1        | 1%      |
| 0x06000852 | 1        | 1%      |
| 0x05000119 | 1        | 1%      |
| 0x010000db | 1        | 1%      |
| 0x010000c7 | 1        | 1%      |
| 0x01000095 | 1        | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 12       | 12%     |
| Penryn        | 11       | 11%     |
| Core          | 11       | 11%     |
| K8 Hammer     | 9        | 9%      |
| Haswell       | 9        | 9%      |
| K10           | 7        | 7%      |
| Zen 2         | 6        | 6%      |
| Silvermont    | 4        | 4%      |
| KabyLake      | 4        | 4%      |
| IvyBridge     | 4        | 4%      |
| Zen+          | 3        | 3%      |
| Skylake       | 3        | 3%      |
| Piledriver    | 3        | 3%      |
| Bonnell       | 3        | 3%      |
| Westmere      | 2        | 2%      |
| NetBurst      | 2        | 2%      |
| Jaguar        | 2        | 2%      |
| CometLake     | 2        | 2%      |
| Steamroller   | 1        | 1%      |
| Goldmont plus | 1        | 1%      |
| Bobcat        | 1        | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 38       | 36.89%  |
| Intel  | 34       | 33.01%  |
| AMD    | 31       | 30.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 7.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 3.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 3.74%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 4        | 3.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 2.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 2.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 2.8%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.87%   |
| Intel HD Graphics 530                                                                    | 2        | 1.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.87%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.87%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.87%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.87%   |
| AMD Richland [Radeon HD 8670D]                                                           | 2        | 1.87%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.87%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.87%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.93%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.93%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.93%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.93%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.93%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.93%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.93%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.93%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 0.93%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.93%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.93%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.93%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.93%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.93%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.93%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.93%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.93%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.93%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 0.93%   |
| Intel HD Graphics 630                                                                    | 1        | 0.93%   |
| Intel HD Graphics 610                                                                    | 1        | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.93%   |
| Intel Comet Lake UHD Graphics                                                            | 1        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.93%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.93%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.93%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 0.93%   |
| AMD RV770 [Radeon HD 4850]                                                               | 1        | 0.93%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 1        | 0.93%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1        | 0.93%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                                        | 1        | 0.93%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                                    | 1        | 0.93%   |
| AMD RV370 [Radeon X300]                                                                  | 1        | 0.93%   |
| AMD RV370 [Radeon X300 SE]                                                               | 1        | 0.93%   |
| AMD RS480 [Radeon Xpress 200 Series]                                                     | 1        | 0.93%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1        | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 36       | 36%     |
| 1 x Intel    | 33       | 33%     |
| 1 x AMD      | 26       | 26%     |
| 2 x AMD      | 4        | 4%      |
| AMD + Nvidia | 1        | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 78%     |
| Proprietary | 21       | 21%     |
| Unknown     | 1        | 1%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 38.61%  |
| 0.01-0.5   | 23       | 22.77%  |
| 0.51-1.0   | 17       | 16.83%  |
| 1.01-2.0   | 11       | 10.89%  |
| 3.01-4.0   | 6        | 5.94%   |
| 7.01-8.0   | 3        | 2.97%   |
| 2.01-3.0   | 1        | 0.99%   |
| 8.01-16.0  | 1        | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 13       | 12.62%  |
| Goldstar                | 13       | 12.62%  |
| Dell                    | 13       | 12.62%  |
| Hewlett-Packard         | 7        | 6.8%    |
| Acer                    | 7        | 6.8%    |
| Lenovo                  | 5        | 4.85%   |
| Vizio                   | 4        | 3.88%   |
| Philips                 | 4        | 3.88%   |
| Unknown                 | 3        | 2.91%   |
| Iiyama                  | 3        | 2.91%   |
| BenQ                    | 3        | 2.91%   |
| AOC                     | 3        | 2.91%   |
| Ancor Communications    | 3        | 2.91%   |
| Sony                    | 2        | 1.94%   |
| LG Electronics          | 2        | 1.94%   |
| ___                     | 1        | 0.97%   |
| Unknown (ADA)           | 1        | 0.97%   |
| Sceptre Tech            | 1        | 0.97%   |
| Plain Tree Systems      | 1        | 0.97%   |
| NEC Computers           | 1        | 0.97%   |
| MOT                     | 1        | 0.97%   |
| LG Display              | 1        | 0.97%   |
| Lenovo Group Limited    | 1        | 0.97%   |
| IBM                     | 1        | 0.97%   |
| Hitachi                 | 1        | 0.97%   |
| HannStar                | 1        | 0.97%   |
| GDH                     | 1        | 0.97%   |
| Fujitsu Siemens         | 1        | 0.97%   |
| Eizo                    | 1        | 0.97%   |
| CVT                     | 1        | 0.97%   |
| Compaq Computer         | 1        | 0.97%   |
| Chi Mei Optoelectronics | 1        | 0.97%   |
| Arnos Instruments       | 1        | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch                     | 2        | 1.89%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                              | 2        | 1.89%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                                     | 2        | 1.89%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch                 | 2        | 1.89%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 1        | 0.94%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                                    | 1        | 0.94%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch                             | 1        | 0.94%   |
| Vizio VO370M VIZ0050 1920x1080 820x460mm 37.0-inch                                    | 1        | 0.94%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                                    | 1        | 0.94%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                                    | 1        | 0.94%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                                | 1        | 0.94%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                                     | 1        | 0.94%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                                 | 1        | 0.94%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                                           | 1        | 0.94%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                                            | 1        | 0.94%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch                         | 1        | 0.94%   |
| Sony TV SNYAA01 1920x1080 880x490mm 39.7-inch                                         | 1        | 0.94%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                                     | 1        | 0.94%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch                        | 1        | 0.94%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch                     | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch                   | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch                  | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch                  | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch                  | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch                  | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch                  | 1        | 0.94%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch                     | 1        | 0.94%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch                     | 1        | 0.94%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch                     | 1        | 0.94%   |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                                   | 1        | 0.94%   |
| Plain Tree Systems FULL HDTV PTS00EC 1920x1080 520x290mm 23.4-inch                    | 1        | 0.94%   |
| Philips PHL 322M7C PHLC194 1920x1080 698x393mm 31.5-inch                              | 1        | 0.94%   |
| Philips 271P4 PHL08C3 1920x1080 597x336mm 27.0-inch                                   | 1        | 0.94%   |
| Philips 190B PHL081A 1280x1024 376x301mm 19.0-inch                                    | 1        | 0.94%   |
| Philips 170C5 PHLC00B 1280x1024 338x270mm 17.0-inch                                   | 1        | 0.94%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 340x270mm 17.1-inch                         | 1        | 0.94%   |
| MOT MotoAttach MOT3DC4 1366x768 260x140mm 11.6-inch                                   | 1        | 0.94%   |
| LG Electronics LCD Monitor W2220                                                      | 1        | 0.94%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                                       | 1        | 0.94%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch                           | 1        | 0.94%   |
| Lenovo LEN-E92I-C LEN0093 1920x1080 509x286mm 23.0-inch                               | 1        | 0.94%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch                            | 1        | 0.94%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                                | 1        | 0.94%   |
| Lenovo Group Limited LCD Monitor LEN L24q-30 1920x1200                                | 1        | 0.94%   |
| Iiyama PL2792H IVM6638 1920x1080 598x336mm 27.0-inch                                  | 1        | 0.94%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                                  | 1        | 0.94%   |
| Iiyama PL2006W IVM539A 1680x1050 430x240mm 19.4-inch                                  | 1        | 0.94%   |
| IBM L150 IBM19EC 1024x768 304x228mm 15.0-inch                                         | 1        | 0.94%   |
| Hitachi X224W D-sub HIT700B 1680x1050 473x296mm 22.0-inch                             | 1        | 0.94%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch                         | 1        | 0.94%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch                          | 1        | 0.94%   |
| Hewlett-Packard LCD Monitor LA1951 1280x1024                                          | 1        | 0.94%   |
| Hewlett-Packard LCD Monitor E241i 3600x1200                                           | 1        | 0.94%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 337x270mm 17.0-inch                           | 1        | 0.94%   |
| Hewlett-Packard E241i HWP3122 1920x1080 518x324mm 24.1-inch                           | 1        | 0.94%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch                             | 1        | 0.94%   |
| HannStar HU196D HSD899A 1280x1024 376x301mm 19.0-inch                                 | 1        | 0.94%   |
| Goldstar W2443 GSM571C 1920x1080 510x290mm 23.1-inch                                  | 1        | 0.94%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                                  | 1        | 0.94%   |
| Goldstar W2220 GSM577B 1680x1050 474x296mm 22.0-inch                                  | 1        | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 31.07%  |
| 1280x1024 (SXGA)   | 21       | 20.39%  |
| 1680x1050 (WSXGA+) | 10       | 9.71%   |
| 1366x768 (WXGA)    | 8        | 7.77%   |
| 1440x900 (WXGA+)   | 7        | 6.8%    |
| 2560x1440 (QHD)    | 4        | 3.88%   |
| 1024x768 (XGA)     | 4        | 3.88%   |
| 1600x900 (HD+)     | 3        | 2.91%   |
| 3840x2160 (4K)     | 2        | 1.94%   |
| 2560x1080          | 2        | 1.94%   |
| 1920x1200 (WUXGA)  | 2        | 1.94%   |
| 1280x800 (WXGA)    | 2        | 1.94%   |
| 3600x1200          | 1        | 0.97%   |
| 2560x1600          | 1        | 0.97%   |
| 2288x1287          | 1        | 0.97%   |
| 1600x1200          | 1        | 0.97%   |
| 1360x768           | 1        | 0.97%   |
| Unknown            | 1        | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 14       | 13.59%  |
| 19      | 12       | 11.65%  |
| 23      | 10       | 9.71%   |
| 24      | 9        | 8.74%   |
| Unknown | 9        | 8.74%   |
| 27      | 8        | 7.77%   |
| 21      | 7        | 6.8%    |
| 20      | 6        | 5.83%   |
| 22      | 5        | 4.85%   |
| 15      | 5        | 4.85%   |
| 18      | 3        | 2.91%   |
| 41      | 2        | 1.94%   |
| 39      | 2        | 1.94%   |
| 31      | 2        | 1.94%   |
| 72      | 1        | 0.97%   |
| 38      | 1        | 0.97%   |
| 37      | 1        | 0.97%   |
| 34      | 1        | 0.97%   |
| 32      | 1        | 0.97%   |
| 29      | 1        | 0.97%   |
| 14      | 1        | 0.97%   |
| 11      | 1        | 0.97%   |
| 7       | 1        | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 27       | 26.73%  |
| 401-500     | 24       | 23.76%  |
| 301-350     | 18       | 17.82%  |
| 351-400     | 9        | 8.91%   |
| Unknown     | 9        | 8.91%   |
| 801-900     | 4        | 3.96%   |
| 601-700     | 3        | 2.97%   |
| 701-800     | 2        | 1.98%   |
| 901-1000    | 2        | 1.98%   |
| 201-300     | 1        | 0.99%   |
| 1501-2000   | 1        | 0.99%   |
| 101-200     | 1        | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 47.42%  |
| 5/4     | 19       | 19.59%  |
| 16/10   | 15       | 15.46%  |
| Unknown | 8        | 8.25%   |
| 4/3     | 4        | 4.12%   |
| 6/5     | 2        | 2.06%   |
| 21/9    | 2        | 2.06%   |
| 3/2     | 1        | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 25.74%  |
| 151-200        | 19       | 18.81%  |
| 141-150        | 15       | 14.85%  |
| 301-350        | 9        | 8.91%   |
| Unknown        | 9        | 8.91%   |
| 501-1000       | 6        | 5.94%   |
| 101-110        | 5        | 4.95%   |
| 351-500        | 4        | 3.96%   |
| 251-300        | 3        | 2.97%   |
| More than 1000 | 1        | 0.99%   |
| 81-90          | 1        | 0.99%   |
| 51-60          | 1        | 0.99%   |
| 1-40           | 1        | 0.99%   |
| 131-140        | 1        | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 68       | 70.83%  |
| 101-120 | 10       | 10.42%  |
| Unknown | 9        | 9.38%   |
| 121-160 | 5        | 5.21%   |
| 1-50    | 2        | 2.08%   |
| 161-240 | 2        | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 86       | 86%     |
| 2     | 9        | 9%      |
| 0     | 3        | 3%      |
| 4     | 1        | 1%      |
| 3     | 1        | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 57       | 41.01%  |
| Intel                    | 32       | 23.02%  |
| Nvidia                   | 11       | 7.91%   |
| Qualcomm Atheros         | 9        | 6.47%   |
| Ralink Technology        | 8        | 5.76%   |
| Ralink                   | 3        | 2.16%   |
| Marvell Technology Group | 3        | 2.16%   |
| Broadcom                 | 3        | 2.16%   |
| Samsung Electronics      | 2        | 1.44%   |
| Broadcom Limited         | 2        | 1.44%   |
| ZyXEL Communications     | 1        | 0.72%   |
| VIA Technologies         | 1        | 0.72%   |
| TP-Link                  | 1        | 0.72%   |
| Sitecom Europe           | 1        | 0.72%   |
| Realtek                  | 1        | 0.72%   |
| NetGear                  | 1        | 0.72%   |
| Huawei Technologies      | 1        | 0.72%   |
| Aquantia                 | 1        | 0.72%   |
| ADMtek                   | 1        | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 25.66%  |
| Nvidia MCP61 Ethernet                                             | 6        | 3.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 3.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.97%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.97%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.97%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.97%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.32%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 1.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.32%   |
| Ralink RT5572 Wireless Adapter                                    | 2        | 1.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.32%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.32%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.32%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.32%   |
| Intel Wireless 7260                                               | 2        | 1.32%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.32%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.66%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.66%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.66%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.66%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.66%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.66%   |
| Realtek 802.11n NIC                                               | 1        | 0.66%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.66%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.66%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.66%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.66%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 0.66%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.66%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.66%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.66%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.66%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.66%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 0.66%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.66%   |
| Intel Wireless-AC 9260                                            | 1        | 0.66%   |
| Intel Wireless 7265                                               | 1        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.66%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.66%   |
| Intel Centrino Advanced-N 6235                                    | 1        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 28.57%  |
| Ralink Technology     | 8        | 19.05%  |
| Intel                 | 7        | 16.67%  |
| Qualcomm Atheros      | 6        | 14.29%  |
| Ralink                | 3        | 7.14%   |
| ZyXEL Communications  | 1        | 2.38%   |
| TP-Link               | 1        | 2.38%   |
| Sitecom Europe        | 1        | 2.38%   |
| Realtek               | 1        | 2.38%   |
| NetGear               | 1        | 2.38%   |
| Broadcom              | 1        | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 11.9%   |
| Realtek RTL8187 Wireless Adapter                               | 2        | 4.76%   |
| Ralink RT5572 Wireless Adapter                                 | 2        | 4.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 4.76%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 4.76%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 4.76%   |
| Intel Wireless 7260                                            | 2        | 4.76%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 2.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 2.38%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 2.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 2.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 2.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 2.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 2.38%   |
| Realtek 802.11n NIC                                            | 1        | 2.38%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 2.38%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 2.38%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 2.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 2.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 2.38%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1        | 2.38%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 2.38%   |
| Intel Wireless-AC 9260                                         | 1        | 2.38%   |
| Intel Wireless 7265                                            | 1        | 2.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.38%   |
| Intel Centrino Advanced-N 6235                                 | 1        | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 49       | 47.12%  |
| Intel                    | 27       | 25.96%  |
| Nvidia                   | 11       | 10.58%  |
| Qualcomm Atheros         | 3        | 2.88%   |
| Marvell Technology Group | 3        | 2.88%   |
| Broadcom                 | 3        | 2.88%   |
| Samsung Electronics      | 2        | 1.92%   |
| Broadcom Limited         | 2        | 1.92%   |
| VIA Technologies         | 1        | 0.96%   |
| Huawei Technologies      | 1        | 0.96%   |
| Aquantia                 | 1        | 0.96%   |
| ADMtek                   | 1        | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 35.45%  |
| Nvidia MCP61 Ethernet                                             | 6        | 5.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.73%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.73%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 2.73%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2.73%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.82%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.82%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.91%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.91%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.91%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.91%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.91%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.91%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.91%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.91%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.91%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.91%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.91%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.91%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.91%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.91%   |
| Huawei BLA-L29                                                    | 1        | 0.91%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.91%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.91%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.91%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.91%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 0.91%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.91%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 70.71%  |
| WiFi     | 41       | 29.29%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 77.12%  |
| WiFi     | 27       | 22.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 73       | 73%     |
| 2     | 22       | 22%     |
| 3     | 4        | 4%      |
| 0     | 1        | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 88       | 88%     |
| Yes  | 12       | 12%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 40%     |
| Cambridge Silicon Radio | 6        | 40%     |
| Broadcom                | 3        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 40%     |
| Intel Bluetooth wireless interface                  | 3        | 20%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 13.33%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.67%   |
| Intel Bluetooth Device                              | 1        | 6.67%   |
| Intel AX210 Bluetooth                               | 1        | 6.67%   |
| Broadcom Bluetooth Device                           | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 61       | 41.5%   |
| Nvidia                   | 37       | 25.17%  |
| AMD                      | 31       | 21.09%  |
| Creative Labs            | 4        | 2.72%   |
| C-Media Electronics      | 3        | 2.04%   |
| XMOS                     | 2        | 1.36%   |
| Logitech                 | 2        | 1.36%   |
| VIA Technologies         | 1        | 0.68%   |
| Unknown                  | 1        | 0.68%   |
| GN Netcom                | 1        | 0.68%   |
| Focusrite-Novation       | 1        | 0.68%   |
| Creative Technology      | 1        | 0.68%   |
| BEHRINGER International  | 1        | 0.68%   |
| Asahi Kasei Microsystems | 1        | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                 | 10       | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller              | 10       | 6.06%   |
| Nvidia High Definition Audio Controller                                                 | 7        | 4.24%   |
| Nvidia MCP61 High Definition Audio                                                      | 6        | 3.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                          | 6        | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                     | 6        | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                                | 5        | 3.03%   |
| AMD FCH Azalia Controller                                                               | 5        | 3.03%   |
| Nvidia GP107GL High Definition Audio Controller                                         | 4        | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                        | 4        | 2.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                     | 4        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                         | 4        | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                            | 4        | 2.42%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                  | 4        | 2.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                   | 3        | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                     | 3        | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                          | 3        | 1.82%   |
| Intel 200 Series PCH HD Audio                                                           | 3        | 1.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]       | 3        | 1.82%   |
| XMOS Mayfield Audio                                                                     | 2        | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                           | 2        | 1.21%   |
| Nvidia GK107 HDMI Audio Controller                                                      | 2        | 1.21%   |
| Nvidia GK106 HDMI Audio Controller                                                      | 2        | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                                           | 2        | 1.21%   |
| Intel 9 Series Chipset Family HD Audio Controller                                       | 2        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                | 2        | 1.21%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                              | 2        | 1.21%   |
| AMD Trinity HDMI Audio Controller                                                       | 2        | 1.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                 | 2        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                | 2        | 1.21%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                          | 2        | 1.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                     | 2        | 1.21%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                      | 1        | 0.61%   |
| Unknown Realtek USB Audio Rear                                                          | 1        | 0.61%   |
| Unknown Realtek USB Audio Front                                                         | 1        | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                          | 1        | 0.61%   |
| Nvidia TU104 HD Audio Controller                                                        | 1        | 0.61%   |
| Nvidia MCP73 High Definition Audio                                                      | 1        | 0.61%   |
| Nvidia MCP67 High Definition Audio                                                      | 1        | 0.61%   |
| Nvidia MCP51 High Definition Audio                                                      | 1        | 0.61%   |
| Nvidia GM206 High Definition Audio Controller                                           | 1        | 0.61%   |
| Nvidia GM204 High Definition Audio Controller                                           | 1        | 0.61%   |
| Nvidia GK104 HDMI Audio Controller                                                      | 1        | 0.61%   |
| Nvidia GF116 High Definition Audio Controller                                           | 1        | 0.61%   |
| Nvidia CK804 AC'97 Audio Controller                                                     | 1        | 0.61%   |
| Logitech Headset H390                                                                   | 1        | 0.61%   |
| Logitech EasyCall Speakerphone                                                          | 1        | 0.61%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                          | 1        | 0.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                            | 1        | 0.61%   |
| Intel C610/X99 series chipset HD Audio Controller                                       | 1        | 0.61%   |
| Intel C600/X79 series chipset High Definition Audio Controller                          | 1        | 0.61%   |
| Intel Audio device                                                                      | 1        | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio | 1        | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller              | 1        | 0.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                        | 1        | 0.61%   |
| GN Netcom Jabra EVOLVE Link MS                                                          | 1        | 0.61%   |
| Focusrite-Novation Scarlett 2i2 Camera                                                  | 1        | 0.61%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                            | 1        | 0.61%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                           | 1        | 0.61%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                      | 1        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 19.44%  |
| Samsung Electronics | 12       | 16.67%  |
| SK Hynix            | 11       | 15.28%  |
| Kingston            | 7        | 9.72%   |
| Crucial             | 5        | 6.94%   |
| Corsair             | 5        | 6.94%   |
| Micron Technology   | 4        | 5.56%   |
| G.Skill             | 3        | 4.17%   |
| Patriot             | 2        | 2.78%   |
| Nanya Technology    | 2        | 2.78%   |
| Unknown (ABCD)      | 1        | 1.39%   |
| Unifosa             | 1        | 1.39%   |
| Team                | 1        | 1.39%   |
| Ramaxel Technology  | 1        | 1.39%   |
| Qimonda             | 1        | 1.39%   |
| e2e4                | 1        | 1.39%   |
| 48spaces            | 1        | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                | 3        | 3.8%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 2        | 2.53%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 2        | 2.53%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s           | 2        | 2.53%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                 | 1        | 1.27%   |
| Unknown RAM Module 512MB DIMM 400MT/s                        | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                 | 1        | 1.27%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR2                          | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                       | 1        | 1.27%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                   | 1        | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 1        | 1.27%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM 1333MT/s              | 1        | 1.27%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s          | 1        | 1.27%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 1.27%   |
| SK Hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s       | 1        | 1.27%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1        | 1.27%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 1.27%   |
| SK Hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s      | 1        | 1.27%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s      | 1        | 1.27%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s      | 1        | 1.27%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1        | 1.27%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 1        | 1.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 1.27%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Samsung RAM M471B1G73AH0-CK0 4096MB SODIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Samsung RAM M4 70T2864FB3-CF7 1024MB SODIMM DDR2 667MT/s     | 1        | 1.27%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1600MT/s       | 1        | 1.27%   |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s         | 1        | 1.27%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM DDR3 1867MT/s       | 1        | 1.27%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s          | 1        | 1.27%   |
| Samsung RAM M3 78T2863RZS-CE6 1024MB DIMM DDR2 667MT/s       | 1        | 1.27%   |
| Samsung RAM M3 78T2863QZS-CE6 1024MB DIMM DDR2 667MT/s       | 1        | 1.27%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s       | 1        | 1.27%   |
| Samsung RAM M3 12L2920CZ3-CCC 1024MB DIMM DDR 400MT/s        | 1        | 1.27%   |
| Ramaxel RAM RML1040EG38D6F-533 512MB DIMM DDR2 533MT/s       | 1        | 1.27%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s             | 1        | 1.27%   |
| Patriot RAM PSD44G213341 4096MB DIMM DDR4 3000MT/s           | 1        | 1.27%   |
| Patriot RAM PSD34G1600L2S 4096MB SODIMM DDR3 1600MT/s        | 1        | 1.27%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s          | 1        | 1.27%   |
| Micron RAM 8JTF25664AZ-1G4D1 2048MB SODIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Micron RAM 36JSF1G72PZ-1 8192MB DIMM DDR3 1600MT/s           | 1        | 1.27%   |
| Micron RAM 16HTF25664AZ-800H1 2048MB DIMM DDR2 800MT/s       | 1        | 1.27%   |
| Kingston RAM SUPER KINGSTEK 2048MB DIMM DDR2 800MT/s         | 1        | 1.27%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1        | 1.27%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                 | 1        | 1.27%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1333MT/s            | 1        | 1.27%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s          | 1        | 1.27%   |
| Kingston RAM KHX1866C10D3/4G 8GB DIMM DDR3 1866MT/s          | 1        | 1.27%   |
| Kingston RAM 99U5471-052.A00LF 8192MB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Kingston RAM 99U5429-007.A00LF 2GB DIMM DDR2 800MT/s         | 1        | 1.27%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 1.27%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s          | 1        | 1.27%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s      | 1        | 1.27%   |
| G.Skill RAM F3-1600C9-8GXM 8192MB DIMM DDR3 1600MT/s         | 1        | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 40.63%  |
| DDR2    | 15       | 23.44%  |
| DDR4    | 13       | 20.31%  |
| SDRAM   | 4        | 6.25%   |
| Unknown | 3        | 4.69%   |
| DDR     | 2        | 3.13%   |
| LPDDR4  | 1        | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 53       | 85.48%  |
| SODIMM | 9        | 14.52%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 22       | 33.33%  |
| 8192  | 16       | 24.24%  |
| 4096  | 14       | 21.21%  |
| 1024  | 7        | 10.61%  |
| 16384 | 4        | 6.06%   |
| 512   | 2        | 3.03%   |
| 65536 | 1        | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 21.43%  |
| 800     | 9        | 12.86%  |
| 1333    | 7        | 10%     |
| 2133    | 6        | 8.57%   |
| 667     | 5        | 7.14%   |
| 2400    | 4        | 5.71%   |
| 400     | 4        | 5.71%   |
| Unknown | 4        | 5.71%   |
| 3600    | 2        | 2.86%   |
| 3200    | 2        | 2.86%   |
| 3000    | 2        | 2.86%   |
| 2048    | 2        | 2.86%   |
| 1866    | 2        | 2.86%   |
| 49926   | 1        | 1.43%   |
| 2667    | 1        | 1.43%   |
| 1867    | 1        | 1.43%   |
| 1334    | 1        | 1.43%   |
| 1066    | 1        | 1.43%   |
| 533     | 1        | 1.43%   |

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
| Sunplus IT                    | 1        | 6.67%   |
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
| Sunplus IT HD 1080P WebCam                | 1        | 6.67%   |
| Sunplus Full HD webcam                    | 1        | 6.67%   |
| Samsung Galaxy A5 (MTP)                   | 1        | 6.67%   |
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
| 0     | 83       | 83%     |
| 1     | 16       | 16%     |
| 2     | 1        | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 31.25%  |
| Net/wireless             | 3        | 18.75%  |
| Communication controller | 3        | 18.75%  |
| Unassigned class         | 2        | 12.5%   |
| Sound                    | 2        | 12.5%   |
| Dvb card                 | 1        | 6.25%   |

