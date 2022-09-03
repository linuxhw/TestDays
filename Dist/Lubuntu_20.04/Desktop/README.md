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

Total: 178

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | A520M-HVS                   | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| MSI           | X399 SLI PLUS               | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| MSI           | AMETHYST-M                  | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| MSI           | H510I PRO WIFI              | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| MSI           | A88XM-E35                   | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| HP            | 3397                        | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
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
| Hardkernel    | ODROID-H2                   | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
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
| 5.4.0-52-generic      | 8        | 5.44%   |
| 5.4.0-42-generic      | 8        | 5.44%   |
| 5.11.0-27-generic     | 7        | 4.76%   |
| 5.8.0-50-generic      | 6        | 4.08%   |
| 5.4.0-54-generic      | 5        | 3.4%    |
| 5.13.0-28-generic     | 5        | 3.4%    |
| 5.4.0-67-generic      | 4        | 2.72%   |
| 5.4.0-40-generic      | 4        | 2.72%   |
| 5.4.0-29-generic      | 4        | 2.72%   |
| 5.4.0-122-generic     | 4        | 2.72%   |
| 5.4.0-77-generic      | 3        | 2.04%   |
| 5.4.0-73-generic      | 3        | 2.04%   |
| 5.4.0-48-generic      | 3        | 2.04%   |
| 5.4.0-47-generic      | 3        | 2.04%   |
| 5.4.0-37-generic      | 3        | 2.04%   |
| 5.4.0-33-generic      | 3        | 2.04%   |
| 5.4.0-26-generic      | 3        | 2.04%   |
| 5.8.0-63-generic      | 2        | 1.36%   |
| 5.8.0-59-generic      | 2        | 1.36%   |
| 5.8.0-53-generic      | 2        | 1.36%   |
| 5.8.0-45-generic      | 2        | 1.36%   |
| 5.8.0-41-generic      | 2        | 1.36%   |
| 5.4.0-96-generic      | 2        | 1.36%   |
| 5.4.0-90-generic      | 2        | 1.36%   |
| 5.4.0-72-generic      | 2        | 1.36%   |
| 5.4.0-66-generic      | 2        | 1.36%   |
| 5.4.0-60-generic      | 2        | 1.36%   |
| 5.4.0-109-generic     | 2        | 1.36%   |
| 5.13.0-27-generic     | 2        | 1.36%   |
| 5.11.0-43-generic     | 2        | 1.36%   |
| 5.11.0-38-generic     | 2        | 1.36%   |
| 5.11.0-34-generic     | 2        | 1.36%   |
| 5.8.0-7630-generic    | 1        | 0.68%   |
| 5.8.0-55-generic      | 1        | 0.68%   |
| 5.8.0-48-generic      | 1        | 0.68%   |
| 5.8.0-43-generic      | 1        | 0.68%   |
| 5.8.0-29-lowlatency   | 1        | 0.68%   |
| 5.6.15-050615-generic | 1        | 0.68%   |
| 5.6.0-1052-oem        | 1        | 0.68%   |
| 5.4.30-dli            | 1        | 0.68%   |
| 5.4.0-99-generic      | 1        | 0.68%   |
| 5.4.0-91-generic      | 1        | 0.68%   |
| 5.4.0-89-generic      | 1        | 0.68%   |
| 5.4.0-88-generic      | 1        | 0.68%   |
| 5.4.0-81-generic      | 1        | 0.68%   |
| 5.4.0-75-generic      | 1        | 0.68%   |
| 5.4.0-65-generic      | 1        | 0.68%   |
| 5.4.0-64-generic      | 1        | 0.68%   |
| 5.4.0-59-generic      | 1        | 0.68%   |
| 5.4.0-58-generic      | 1        | 0.68%   |
| 5.4.0-53-generic      | 1        | 0.68%   |
| 5.4.0-31-generic      | 1        | 0.68%   |
| 5.4.0-120-generic     | 1        | 0.68%   |
| 5.4.0-113-generic     | 1        | 0.68%   |
| 5.4.0-107-generic     | 1        | 0.68%   |
| 5.4.0-105-generic     | 1        | 0.68%   |
| 5.4.0-104-generic     | 1        | 0.68%   |
| 5.4.0-100-generic     | 1        | 0.68%   |
| 5.3.18-dli            | 1        | 0.68%   |
| 5.16.5-051605-generic | 1        | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 80       | 57.55%  |
| 5.8.0   | 21       | 15.11%  |
| 5.11.0  | 18       | 12.95%  |
| 5.13.0  | 13       | 9.35%   |
| 5.6.15  | 1        | 0.72%   |
| 5.6.0   | 1        | 0.72%   |
| 5.4.30  | 1        | 0.72%   |
| 5.3.18  | 1        | 0.72%   |
| 5.16.5  | 1        | 0.72%   |
| 5.15.0  | 1        | 0.72%   |
| 5.14.0  | 1        | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 81       | 58.27%  |
| 5.8     | 21       | 15.11%  |
| 5.11    | 18       | 12.95%  |
| 5.13    | 13       | 9.35%   |
| 5.6     | 2        | 1.44%   |
| 5.3     | 1        | 0.72%   |
| 5.16    | 1        | 0.72%   |
| 5.15    | 1        | 0.72%   |
| 5.14    | 1        | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 138      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 128      | 92.75%  |
| LXDE       | 4        | 2.9%    |
| GNOME      | 3        | 2.17%   |
| XFCE       | 1        | 0.72%   |
| X-Cinnamon | 1        | 0.72%   |
| i3         | 1        | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 131      | 94.93%  |
| Tty     | 6        | 4.35%   |
| Unknown | 1        | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 74       | 52.11%  |
| Unknown | 41       | 28.87%  |
| LightDM | 10       | 7.04%   |
| GDM     | 9        | 6.34%   |
| TDM     | 6        | 4.23%   |
| LXDM    | 1        | 0.7%    |
| GDM3    | 1        | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 34       | 24.64%  |
| fr_FR   | 19       | 13.77%  |
| de_DE   | 13       | 9.42%   |
| pt_BR   | 11       | 7.97%   |
| it_IT   | 9        | 6.52%   |
| C       | 7        | 5.07%   |
| ru_RU   | 5        | 3.62%   |
| ja_JP   | 4        | 2.9%    |
| en_GB   | 4        | 2.9%    |
| en_AU   | 4        | 2.9%    |
| fi_FI   | 3        | 2.17%   |
| es_ES   | 3        | 2.17%   |
| hu_HU   | 2        | 1.45%   |
| en_ZA   | 2        | 1.45%   |
| en_CA   | 2        | 1.45%   |
| de_CH   | 2        | 1.45%   |
| cs_CZ   | 2        | 1.45%   |
| Unknown | 2        | 1.45%   |
| sv_SE   | 1        | 0.72%   |
| nl_NL   | 1        | 0.72%   |
| fr_CA   | 1        | 0.72%   |
| es_PE   | 1        | 0.72%   |
| es_MX   | 1        | 0.72%   |
| es_CR   | 1        | 0.72%   |
| es_CO   | 1        | 0.72%   |
| en_SG   | 1        | 0.72%   |
| en_NZ   | 1        | 0.72%   |
| el_GR   | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 93       | 67.39%  |
| EFI  | 45       | 32.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 126      | 91.3%   |
| Overlay | 7        | 5.07%   |
| Xfs     | 2        | 1.45%   |
| Zfs     | 1        | 0.72%   |
| F2fs    | 1        | 0.72%   |
| Btrfs   | 1        | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 55       | 39.57%  |
| MBR     | 46       | 33.09%  |
| GPT     | 38       | 27.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 112      | 81.16%  |
| Yes       | 26       | 18.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 68.35%  |
| Yes       | 44       | 31.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 22       | 15.94%  |
| MSI                 | 16       | 11.59%  |
| Hewlett-Packard     | 16       | 11.59%  |
| Gigabyte Technology | 15       | 10.87%  |
| ASRock              | 15       | 10.87%  |
| Dell                | 14       | 10.14%  |
| Lenovo              | 8        | 5.8%    |
| Intel               | 6        | 4.35%   |
| Pegatron            | 4        | 2.9%    |
| Acer                | 4        | 2.9%    |
| AAEON               | 3        | 2.17%   |
| Positivo            | 2        | 1.45%   |
| Foxconn             | 2        | 1.45%   |
| Biostar             | 2        | 1.45%   |
| ZOTAC               | 1        | 0.72%   |
| Packard Bell        | 1        | 0.72%   |
| IBM                 | 1        | 0.72%   |
| Huanan              | 1        | 0.72%   |
| Hardkernel          | 1        | 0.72%   |
| Fujitsu Siemens     | 1        | 0.72%   |
| Fujitsu             | 1        | 0.72%   |
| AMI                 | 1        | 0.72%   |
| Unknown             | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| AAEON MF-001                                                 | 3        | 2.17%   |
| MSI MS-7C37                                                  | 2        | 1.45%   |
| MSI MS-7B89                                                  | 2        | 1.45%   |
| HP Compaq 6000 Pro SFF PC                                    | 2        | 1.45%   |
| Dell OptiPlex 790                                            | 2        | 1.45%   |
| ASUS M5A97 R2.0                                              | 2        | 1.45%   |
| ASRock N68-VS3 UCC                                           | 2        | 1.45%   |
| ASRock FM2A85X Extreme6                                      | 2        | 1.45%   |
| ZOTAC NM10                                                   | 1        | 0.72%   |
| Positivo POS-MI945AA                                         | 1        | 0.72%   |
| Positivo POS-EIH61CE                                         | 1        | 0.72%   |
| Pegatron WE216AA-ABF CQ5335FR                                | 1        | 0.72%   |
| Pegatron NC689AA-ABA s3700y                                  | 1        | 0.72%   |
| Pegatron FL308AA-ABD IQ512de                                 | 1        | 0.72%   |
| Pegatron AY652AA-ABA s5310y                                  | 1        | 0.72%   |
| Packard Bell IMEDIA S1350                                    | 1        | 0.72%   |
| MSI MS-7D16                                                  | 1        | 0.72%   |
| MSI MS-7B86                                                  | 1        | 0.72%   |
| MSI MS-7B09                                                  | 1        | 0.72%   |
| MSI MS-7994                                                  | 1        | 0.72%   |
| MSI MS-7846                                                  | 1        | 0.72%   |
| MSI MS-7721                                                  | 1        | 0.72%   |
| MSI MS-7680                                                  | 1        | 0.72%   |
| MSI MS-7640                                                  | 1        | 0.72%   |
| MSI MS-7592                                                  | 1        | 0.72%   |
| MSI MS-7309                                                  | 1        | 0.72%   |
| MSI ER883AA-ABA M7470N                                       | 1        | 0.72%   |
| MSI Compaq dx2200 MT                                         | 1        | 0.72%   |
| Lenovo ThinkStation P620 30E0CTO1WW                          | 1        | 0.72%   |
| Lenovo ThinkCentre M93z 10AD002DMZ                           | 1        | 0.72%   |
| Lenovo ThinkCentre M73 10AXS0HN00                            | 1        | 0.72%   |
| Lenovo ThinkCentre M58p 7220W21                              | 1        | 0.72%   |
| Lenovo ThinkCentre M58p 6136A66                              | 1        | 0.72%   |
| Lenovo ThinkCentre M55p 8811VQV                              | 1        | 0.72%   |
| Lenovo H50-50 90B60081IX                                     | 1        | 0.72%   |
| Lenovo H50-30g 90AS0002BR                                    | 1        | 0.72%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V304 | 1        | 0.72%   |
| Intel STK1AW32SC                                             | 1        | 0.72%   |
| Intel H55                                                    | 1        | 0.72%   |
| Intel DN2800MT AAG23738-801                                  | 1        | 0.72%   |
| Intel DG31PR AAD97573-302                                    | 1        | 0.72%   |
| Intel ChiefRiver                                             | 1        | 0.72%   |
| IBM eServer x3105 -[434722J]-                                | 1        | 0.72%   |
| Huanan X99-TF                                                | 1        | 0.72%   |
| HP Z230 Tower Workstation                                    | 1        | 0.72%   |
| HP xw9400 Workstation                                        | 1        | 0.72%   |
| HP xw9300 Workstation                                        | 1        | 0.72%   |
| HP t620 Quad Core TC                                         | 1        | 0.72%   |
| HP t620 Dual Core TC                                         | 1        | 0.72%   |
| HP ProDesk 600 G1 DM                                         | 1        | 0.72%   |
| HP EliteDesk 800 G3 SFF                                      | 1        | 0.72%   |
| HP Compaq Elite 8300 CMT                                     | 1        | 0.72%   |
| HP Compaq dc7800 Small Form Factor                           | 1        | 0.72%   |
| HP Compaq dc7600 Small Form Factor                           | 1        | 0.72%   |
| HP Compaq dc5800 Microtower                                  | 1        | 0.72%   |
| HP Compaq 8200 Elite SFF PC                                  | 1        | 0.72%   |
| HP Compaq 8000 Elite CMT PC                                  | 1        | 0.72%   |
| HP 500-203a                                                  | 1        | 0.72%   |
| Hardkernel ODROID-H2                                         | 1        | 0.72%   |
| Gigabyte Z370P D3                                            | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 8        | 5.8%    |
| Dell OptiPlex         | 6        | 4.35%   |
| Lenovo ThinkCentre    | 5        | 3.62%   |
| Acer Aspire           | 4        | 2.9%    |
| AAEON MF-001          | 3        | 2.17%   |
| MSI MS-7C37           | 2        | 1.45%   |
| MSI MS-7B89           | 2        | 1.45%   |
| HP t620               | 2        | 1.45%   |
| Gigabyte B450M        | 2        | 1.45%   |
| Dell Inspiron         | 2        | 1.45%   |
| ASUS M5A97            | 2        | 1.45%   |
| ASRock N68-VS3        | 2        | 1.45%   |
| ASRock FM2A85X        | 2        | 1.45%   |
| ZOTAC NM10            | 1        | 0.72%   |
| Positivo POS-MI945AA  | 1        | 0.72%   |
| Positivo POS-EIH61CE  | 1        | 0.72%   |
| Pegatron WE216AA-ABF  | 1        | 0.72%   |
| Pegatron NC689AA-ABA  | 1        | 0.72%   |
| Pegatron FL308AA-ABD  | 1        | 0.72%   |
| Pegatron AY652AA-ABA  | 1        | 0.72%   |
| Packard Bell IMEDIA   | 1        | 0.72%   |
| MSI MS-7D16           | 1        | 0.72%   |
| MSI MS-7B86           | 1        | 0.72%   |
| MSI MS-7B09           | 1        | 0.72%   |
| MSI MS-7994           | 1        | 0.72%   |
| MSI MS-7846           | 1        | 0.72%   |
| MSI MS-7721           | 1        | 0.72%   |
| MSI MS-7680           | 1        | 0.72%   |
| MSI MS-7640           | 1        | 0.72%   |
| MSI MS-7592           | 1        | 0.72%   |
| MSI MS-7309           | 1        | 0.72%   |
| MSI ER883AA-ABA       | 1        | 0.72%   |
| MSI Compaq            | 1        | 0.72%   |
| Lenovo ThinkStation   | 1        | 0.72%   |
| Lenovo H50-50         | 1        | 0.72%   |
| Lenovo H50-30g        | 1        | 0.72%   |
| Intel X79             | 1        | 0.72%   |
| Intel STK1AW32SC      | 1        | 0.72%   |
| Intel H55             | 1        | 0.72%   |
| Intel DN2800MT        | 1        | 0.72%   |
| Intel DG31PR          | 1        | 0.72%   |
| Intel ChiefRiver      | 1        | 0.72%   |
| IBM eServer           | 1        | 0.72%   |
| Huanan X99-TF         | 1        | 0.72%   |
| HP Z230               | 1        | 0.72%   |
| HP xw9400             | 1        | 0.72%   |
| HP xw9300             | 1        | 0.72%   |
| HP ProDesk            | 1        | 0.72%   |
| HP EliteDesk          | 1        | 0.72%   |
| HP 500-203a           | 1        | 0.72%   |
| Hardkernel ODROID-H2  | 1        | 0.72%   |
| Gigabyte Z370P        | 1        | 0.72%   |
| Gigabyte X570         | 1        | 0.72%   |
| Gigabyte K8M800-8237  | 1        | 0.72%   |
| Gigabyte H97-D3H      | 1        | 0.72%   |
| Gigabyte H81M-DS2     | 1        | 0.72%   |
| Gigabyte H61M-DS2H    | 1        | 0.72%   |
| Gigabyte GA-MA69G-S3H | 1        | 0.72%   |
| Gigabyte GA-870A-UD3  | 1        | 0.72%   |
| Gigabyte G41M-Combo   | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 12       | 8.7%    |
| 2007 | 12       | 8.7%    |
| 2011 | 11       | 7.97%   |
| 2009 | 11       | 7.97%   |
| 2013 | 10       | 7.25%   |
| 2008 | 10       | 7.25%   |
| 2017 | 9        | 6.52%   |
| 2014 | 9        | 6.52%   |
| 2010 | 9        | 6.52%   |
| 2019 | 8        | 5.8%    |
| 2006 | 7        | 5.07%   |
| 2020 | 6        | 4.35%   |
| 2015 | 6        | 4.35%   |
| 2021 | 5        | 3.62%   |
| 2018 | 5        | 3.62%   |
| 2005 | 4        | 2.9%    |
| 2016 | 3        | 2.17%   |
| 2004 | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 138      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 134      | 97.1%   |
| Enabled  | 4        | 2.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 40       | 28.78%  |
| 8.01-16.0       | 21       | 15.11%  |
| 1.01-2.0        | 19       | 13.67%  |
| 4.01-8.0        | 18       | 12.95%  |
| 16.01-24.0      | 17       | 12.23%  |
| 32.01-64.0      | 11       | 7.91%   |
| 24.01-32.0      | 4        | 2.88%   |
| 2.01-3.0        | 3        | 2.16%   |
| 64.01-256.0     | 3        | 2.16%   |
| 0.51-1.0        | 2        | 1.44%   |
| More than 256.0 | 1        | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 68       | 47.55%  |
| 2.01-3.0   | 26       | 18.18%  |
| 0.51-1.0   | 21       | 14.69%  |
| 4.01-8.0   | 15       | 10.49%  |
| 3.01-4.0   | 6        | 4.2%    |
| 0.01-0.5   | 3        | 2.1%    |
| 8.01-16.0  | 2        | 1.4%    |
| 32.01-64.0 | 1        | 0.7%    |
| 16.01-24.0 | 1        | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 49.64%  |
| 2      | 41       | 29.5%   |
| 4      | 11       | 7.91%   |
| 3      | 8        | 5.76%   |
| 5      | 5        | 3.6%    |
| 17     | 1        | 0.72%   |
| 14     | 1        | 0.72%   |
| 7      | 1        | 0.72%   |
| 6      | 1        | 0.72%   |
| 0      | 1        | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 87       | 62.14%  |
| No        | 53       | 37.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 137      | 99.28%  |
| No        | 1        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 60.14%  |
| Yes       | 55       | 39.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 83.33%  |
| Yes       | 23       | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 20       | 14.29%  |
| France       | 19       | 13.57%  |
| Germany      | 15       | 10.71%  |
| Brazil       | 12       | 8.57%   |
| Italy        | 9        | 6.43%   |
| Switzerland  | 6        | 4.29%   |
| Russia       | 5        | 3.57%   |
| Hungary      | 5        | 3.57%   |
| Spain        | 4        | 2.86%   |
| Japan        | 4        | 2.86%   |
| Finland      | 4        | 2.86%   |
| Australia    | 4        | 2.86%   |
| Netherlands  | 3        | 2.14%   |
| Czechia      | 3        | 2.14%   |
| Canada       | 3        | 2.14%   |
| South Africa | 2        | 1.43%   |
| Puerto Rico  | 2        | 1.43%   |
| New Zealand  | 2        | 1.43%   |
| Mexico       | 2        | 1.43%   |
| Greece       | 2        | 1.43%   |
| Belgium      | 2        | 1.43%   |
| UK           | 1        | 0.71%   |
| Sweden       | 1        | 0.71%   |
| Slovenia     | 1        | 0.71%   |
| Slovakia     | 1        | 0.71%   |
| Singapore    | 1        | 0.71%   |
| Romania      | 1        | 0.71%   |
| Peru         | 1        | 0.71%   |
| Malaysia     | 1        | 0.71%   |
| Ireland      | 1        | 0.71%   |
| Costa Rica   | 1        | 0.71%   |
| Colombia     | 1        | 0.71%   |
| Belarus      | 1        | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Wellington            | 3        | 2.1%    |
| Melbourne             | 3        | 2.1%    |
| Zurich                | 2        | 1.4%    |
| Rome                  | 2        | 1.4%    |
| Raahe                 | 2        | 1.4%    |
| Pécs                 | 2        | 1.4%    |
| Figeac                | 2        | 1.4%    |
| Cuernavaca            | 2        | 1.4%    |
| Cayey                 | 2        | 1.4%    |
| Bern                  | 2        | 1.4%    |
| Zwevegem              | 1        | 0.7%    |
| Zeuthen               | 1        | 0.7%    |
| Wraysbury             | 1        | 0.7%    |
| Winsen                | 1        | 0.7%    |
| Wiesbaden             | 1        | 0.7%    |
| West Chester          | 1        | 0.7%    |
| Vinhedo               | 1        | 0.7%    |
| Vilyuchinsk           | 1        | 0.7%    |
| Villejuif             | 1        | 0.7%    |
| Vilabella             | 1        | 0.7%    |
| Vaxjo                 | 1        | 0.7%    |
| Vanderbijlpark        | 1        | 0.7%    |
| Valencia              | 1        | 0.7%    |
| Turku                 | 1        | 0.7%    |
| Trebur                | 1        | 0.7%    |
| Toulouse              | 1        | 0.7%    |
| Toronto               | 1        | 0.7%    |
| Tokorozawa            | 1        | 0.7%    |
| Stockton              | 1        | 0.7%    |
| Stedesand             | 1        | 0.7%    |
| Spokane               | 1        | 0.7%    |
| Sora                  | 1        | 0.7%    |
| Schiedam              | 1        | 0.7%    |
| Sautron               | 1        | 0.7%    |
| Sao Paulo             | 1        | 0.7%    |
| Sandorfalva           | 1        | 0.7%    |
| Salzgitter            | 1        | 0.7%    |
| Saint-Pair-sur-Mer    | 1        | 0.7%    |
| Saint-Michel-sur-Orge | 1        | 0.7%    |
| Saint Paul            | 1        | 0.7%    |
| Roseburg              | 1        | 0.7%    |
| Roquecourbe           | 1        | 0.7%    |
| Ronnenberg            | 1        | 0.7%    |
| Rio de Janeiro        | 1        | 0.7%    |
| Raleigh               | 1        | 0.7%    |
| Racconigi             | 1        | 0.7%    |
| Prague                | 1        | 0.7%    |
| Portorož             | 1        | 0.7%    |
| Portbail              | 1        | 0.7%    |
| Poisy                 | 1        | 0.7%    |
| Passos                | 1        | 0.7%    |
| Pacatuba              | 1        | 0.7%    |
| Oradea                | 1        | 0.7%    |
| Omsk                  | 1        | 0.7%    |
| Ōita                 | 1        | 0.7%    |
| Oceanside             | 1        | 0.7%    |
| Novy Jicin            | 1        | 0.7%    |
| Nitra                 | 1        | 0.7%    |
| Neuville-en-Ferrain   | 1        | 0.7%    |
| Neuchatel             | 1        | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 65     | 24.42%  |
| WDC                 | 50       | 80     | 23.04%  |
| Samsung Electronics | 27       | 46     | 12.44%  |
| Kingston            | 9        | 9      | 4.15%   |
| Hitachi             | 9        | 12     | 4.15%   |
| Toshiba             | 8        | 8      | 3.69%   |
| Unknown             | 7        | 8      | 3.23%   |
| Crucial             | 7        | 19     | 3.23%   |
| SanDisk             | 4        | 4      | 1.84%   |
| Maxtor              | 4        | 4      | 1.84%   |
| China               | 4        | 4      | 1.84%   |
| A-DATA Technology   | 4        | 5      | 1.84%   |
| Team                | 3        | 3      | 1.38%   |
| Corsair             | 3        | 3      | 1.38%   |
| PNY                 | 2        | 2      | 0.92%   |
| LDLC                | 2        | 2      | 0.92%   |
| JMicron Technology  | 2        | 2      | 0.92%   |
| Intenso             | 2        | 2      | 0.92%   |
| Intel               | 2        | 2      | 0.92%   |
| Transcend           | 1        | 1      | 0.46%   |
| TO Exter            | 1        | 1      | 0.46%   |
| PNY USB             | 1        | 1      | 0.46%   |
| Patriot             | 1        | 1      | 0.46%   |
| ORTIAL              | 1        | 1      | 0.46%   |
| OCZ                 | 1        | 1      | 0.46%   |
| Londisk             | 1        | 1      | 0.46%   |
| Lexar               | 1        | 1      | 0.46%   |
| Leven               | 1        | 2      | 0.46%   |
| KingFast            | 1        | 1      | 0.46%   |
| HGST                | 1        | 1      | 0.46%   |
| Hewlett-Packard     | 1        | 6      | 0.46%   |
| GOODRAM             | 1        | 1      | 0.46%   |
| Fujitsu             | 1        | 1      | 0.46%   |
| External            | 1        | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 1.63%   |
| Samsung HD502IJ 500GB               | 3        | 1.22%   |
| Samsung HD103SJ 1TB                 | 3        | 1.22%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.82%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.82%   |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.82%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.82%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.82%   |
| WDC WD2500AAKX-07U6AA1 250GB        | 2        | 0.82%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.82%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.82%   |
| WDC WD10EACS-00D6B0 1TB             | 2        | 0.82%   |
| Unknown M52516  16GB                | 2        | 0.82%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.82%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.82%   |
| Seagate ST380815AS 80GB             | 2        | 0.82%   |
| Seagate ST3500418AS 500GB           | 2        | 0.82%   |
| Seagate ST3360320AS 360GB           | 2        | 0.82%   |
| Seagate ST3250410AS 250GB           | 2        | 0.82%   |
| Seagate ST3250310AS 250GB           | 2        | 0.82%   |
| Seagate ST31000528AS 1TB            | 2        | 0.82%   |
| Seagate ST3000DM008-2DM166 3TB      | 2        | 0.82%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.82%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.82%   |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 0.82%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 0.82%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.82%   |
| Samsung SSD 850 EVO 250GB           | 2        | 0.82%   |
| Samsung HD161HJ 160GB               | 2        | 0.82%   |
| Samsung HD103SI 1TB                 | 2        | 0.82%   |
| Samsung HD080HJ 80GB                | 2        | 0.82%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 0.82%   |
| Crucial CT1000BX500SSD1 1TB         | 2        | 0.82%   |
| Corsair Force LS SSD 120GB          | 2        | 0.82%   |
| China SATA SSD 512GB                | 2        | 0.82%   |
| A-DATA SU650 240GB SSD              | 2        | 0.82%   |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.41%   |
| WDC WDS200T2B0A-00SM50 2TB SSD      | 1        | 0.41%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.41%   |
| WDC WD800JD-75JNA0 80GB             | 1        | 0.41%   |
| WDC WD7501AALS-00J7B1 752GB         | 1        | 0.41%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.41%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.41%   |
| WDC WD5000BPKX-66HPJT0 500GB        | 1        | 0.41%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.41%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 0.41%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.41%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.41%   |
| WDC WD50 00AAKS-00V1A 500GB         | 1        | 0.41%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 0.41%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.41%   |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.41%   |
| WDC WD3200JS-22PDB0 320GB           | 1        | 0.41%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1        | 0.41%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1        | 0.41%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.41%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 0.41%   |
| WDC WD2500JS-75NCB3 250GB           | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 65     | 39.55%  |
| WDC                 | 44       | 70     | 32.84%  |
| Samsung Electronics | 16       | 20     | 11.94%  |
| Hitachi             | 9        | 12     | 6.72%   |
| Toshiba             | 6        | 6      | 4.48%   |
| Maxtor              | 3        | 3      | 2.24%   |
| Unknown             | 1        | 1      | 0.75%   |
| HGST                | 1        | 1      | 0.75%   |
| Fujitsu             | 1        | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 12.86%  |
| WDC                 | 8        | 10     | 11.43%  |
| Kingston            | 8        | 8      | 11.43%  |
| Crucial             | 7        | 19     | 10%     |
| SanDisk             | 4        | 4      | 5.71%   |
| China               | 4        | 4      | 5.71%   |
| Team                | 3        | 3      | 4.29%   |
| Corsair             | 3        | 3      | 4.29%   |
| A-DATA Technology   | 3        | 4      | 4.29%   |
| Toshiba             | 2        | 2      | 2.86%   |
| PNY                 | 2        | 2      | 2.86%   |
| Intenso             | 2        | 2      | 2.86%   |
| Transcend           | 1        | 1      | 1.43%   |
| TO Exter            | 1        | 1      | 1.43%   |
| PNY USB             | 1        | 1      | 1.43%   |
| Patriot             | 1        | 1      | 1.43%   |
| ORTIAL              | 1        | 1      | 1.43%   |
| OCZ                 | 1        | 1      | 1.43%   |
| Maxtor              | 1        | 1      | 1.43%   |
| Londisk             | 1        | 1      | 1.43%   |
| Lexar               | 1        | 1      | 1.43%   |
| Leven               | 1        | 2      | 1.43%   |
| LDLC                | 1        | 1      | 1.43%   |
| JMicron Technology  | 1        | 1      | 1.43%   |
| Intel               | 1        | 1      | 1.43%   |
| Hewlett-Packard     | 1        | 6      | 1.43%   |
| GOODRAM             | 1        | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 101      | 179    | 56.42%  |
| SSD     | 62       | 94     | 34.64%  |
| NVMe    | 8        | 19     | 4.47%   |
| MMC     | 6        | 7      | 3.35%   |
| Unknown | 2        | 2      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 128      | 265    | 85.91%  |
| SAS  | 8        | 11     | 5.37%   |
| NVMe | 7        | 18     | 4.7%    |
| MMC  | 6        | 7      | 4.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 104      | 158    | 61.18%  |
| 0.51-1.0   | 46       | 83     | 27.06%  |
| 1.01-2.0   | 11       | 15     | 6.47%   |
| 3.01-4.0   | 4        | 12     | 2.35%   |
| 2.01-3.0   | 4        | 4      | 2.35%   |
| 4.01-10.0  | 1        | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 25.71%  |
| 251-500        | 29       | 20.71%  |
| 501-1000       | 16       | 11.43%  |
| 1001-2000      | 15       | 10.71%  |
| More than 3000 | 14       | 10%     |
| 51-100         | 13       | 9.29%   |
| 1-20           | 7        | 5%      |
| 2001-3000      | 6        | 4.29%   |
| 21-50          | 3        | 2.14%   |
| Unknown        | 1        | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 38.3%   |
| 21-50          | 25       | 17.73%  |
| 101-250        | 14       | 9.93%   |
| 501-1000       | 11       | 7.8%    |
| 51-100         | 10       | 7.09%   |
| 251-500        | 9        | 6.38%   |
| 1001-2000      | 8        | 5.67%   |
| More than 3000 | 5        | 3.55%   |
| 2001-3000      | 4        | 2.84%   |
| Unknown        | 1        | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB    | 2        | 2      | 7.14%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 1      | 3.57%   |
| WDC WD400EB-00CPF0 40GB           | 1        | 1      | 3.57%   |
| WDC WD2500AAJS-75M0A0 250GB       | 1        | 1      | 3.57%   |
| WDC WD1600AAJS-60B4A0 160GB       | 1        | 2      | 3.57%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 3.57%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 3.57%   |
| Seagate ST360012A 64GB            | 1        | 1      | 3.57%   |
| Seagate ST3360320AS 360GB         | 1        | 1      | 3.57%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 3.57%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 3.57%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 3.57%   |
| Seagate ST1000DX001-1CM162 1TB    | 1        | 1      | 3.57%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 3.57%   |
| SanDisk SSD PLUS 120GB            | 1        | 1      | 3.57%   |
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 3.57%   |
| Maxtor STM3300622A 304GB          | 1        | 1      | 3.57%   |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 3.57%   |
| Maxtor 6B200M0 208GB              | 1        | 1      | 3.57%   |
| LDLC SSD 120GB                    | 1        | 1      | 3.57%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 3.57%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 3.57%   |
| Hitachi HDS721075CLA332 752GB     | 1        | 1      | 3.57%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 3.57%   |
| Hitachi HCP725050GLAT80 500GB     | 1        | 1      | 3.57%   |
| Fujitsu MHZ2160BH G2 160GB        | 1        | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 11     | 40.74%  |
| WDC                 | 5        | 6      | 18.52%  |
| Maxtor              | 3        | 3      | 11.11%  |
| Kingston            | 2        | 2      | 7.41%   |
| Hitachi             | 2        | 3      | 7.41%   |
| SanDisk             | 1        | 1      | 3.7%    |
| Samsung Electronics | 1        | 1      | 3.7%    |
| LDLC                | 1        | 1      | 3.7%    |
| Fujitsu             | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 11     | 47.83%  |
| WDC                 | 5        | 6      | 21.74%  |
| Maxtor              | 3        | 3      | 13.04%  |
| Hitachi             | 2        | 3      | 8.7%    |
| Samsung Electronics | 1        | 1      | 4.35%   |
| Fujitsu             | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 25     | 83.33%  |
| SSD  | 4        | 4      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics SSD 850 250GB | 1        | 1      | 50%     |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 68       | 134    | 43.59%  |
| Detected | 64       | 136    | 41.03%  |
| Malfunc  | 22       | 29     | 14.1%   |
| Failed   | 2        | 2      | 1.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 80       | 51.95%  |
| AMD                         | 35       | 22.73%  |
| Nvidia                      | 16       | 10.39%  |
| Marvell Technology Group    | 5        | 3.25%   |
| JMicron Technology          | 5        | 3.25%   |
| Samsung Electronics         | 3        | 1.95%   |
| ASMedia Technology          | 3        | 1.95%   |
| VIA Technologies            | 2        | 1.3%    |
| LSI Logic / Symbios Logic   | 2        | 1.3%    |
| Silicon Motion              | 1        | 0.65%   |
| Kingston Technology Company | 1        | 0.65%   |
| ADATA Technology            | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 10.19%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 4.63%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.7%    |
| Nvidia MCP61 IDE                                                                        | 6        | 2.78%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 2.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.31%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 2.31%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.31%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.85%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.39%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.39%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.39%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.93%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.93%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.93%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.93%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.93%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2        | 0.93%   |
| AMD SB600 IDE                                                                           | 2        | 0.93%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 0.93%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 0.93%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 0.93%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.46%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.46%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.46%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 0.46%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.46%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.46%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.46%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.46%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.46%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.46%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.46%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 0.46%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.46%   |
| Marvell Group 88SE9480 SAS/SATA 6Gb/s RAID controller                                   | 1        | 0.46%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 84       | 51.85%  |
| IDE  | 60       | 37.04%  |
| RAID | 9        | 5.56%   |
| NVMe | 7        | 4.32%   |
| SCSI | 2        | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 88       | 63.77%  |
| AMD    | 50       | 36.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.17%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3        | 2.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.17%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3        | 2.17%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.45%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.45%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.45%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.45%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.45%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.45%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 1.45%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.45%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.45%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.72%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.72%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1        | 0.72%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.72%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.72%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.72%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.72%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.72%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.72%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.72%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.72%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.72%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.72%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 0.72%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.72%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.72%   |
| Intel Core i5-4440S CPU @ 2.80GHz           | 1        | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 0.72%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 0.72%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.72%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 0.72%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.72%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.72%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 0.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.72%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 0.72%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 0.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 0.72%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 0.72%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 22       | 15.94%  |
| Intel Core 2 Duo        | 12       | 8.7%    |
| Intel Core i3           | 9        | 6.52%   |
| Intel Atom              | 8        | 5.8%    |
| Intel Core i7           | 6        | 4.35%   |
| Intel Celeron           | 6        | 4.35%   |
| AMD Ryzen 5             | 6        | 4.35%   |
| AMD Athlon II X2        | 6        | 4.35%   |
| AMD Athlon 64 X2        | 6        | 4.35%   |
| Intel Xeon              | 5        | 3.62%   |
| Intel Core 2 Quad       | 5        | 3.62%   |
| Intel Core 2            | 5        | 3.62%   |
| AMD Ryzen 7             | 5        | 3.62%   |
| AMD A10                 | 5        | 3.62%   |
| Intel Pentium Dual-Core | 4        | 2.9%    |
| AMD FX                  | 3        | 2.17%   |
| AMD Athlon 64           | 3        | 2.17%   |
| Intel Pentium Dual      | 2        | 1.45%   |
| Intel Pentium 4         | 2        | 1.45%   |
| AMD Sempron             | 2        | 1.45%   |
| AMD Ryzen Threadripper  | 2        | 1.45%   |
| AMD Ryzen 3             | 2        | 1.45%   |
| AMD GX                  | 2        | 1.45%   |
| Intel Pentium Gold      | 1        | 0.72%   |
| Intel Pentium           | 1        | 0.72%   |
| AMD Quad-Core Opteron   | 1        | 0.72%   |
| AMD Phenom II X4        | 1        | 0.72%   |
| AMD Phenom II X3        | 1        | 0.72%   |
| AMD Opteron             | 1        | 0.72%   |
| AMD E                   | 1        | 0.72%   |
| AMD Athlon X4           | 1        | 0.72%   |
| AMD Athlon II X4        | 1        | 0.72%   |
| AMD A8                  | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 64       | 46.38%  |
| 4      | 46       | 33.33%  |
| 6      | 9        | 6.52%   |
| 1      | 8        | 5.8%    |
| 8      | 7        | 5.07%   |
| 64     | 1        | 0.72%   |
| 16     | 1        | 0.72%   |
| 12     | 1        | 0.72%   |
| 3      | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 98.55%  |
| 2      | 2        | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 63.04%  |
| 2      | 51       | 36.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 138      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 15.22%  |
| 0x206a7    | 12       | 8.7%    |
| 0x306c3    | 10       | 7.25%   |
| 0x1067a    | 10       | 7.25%   |
| 0x06001119 | 6        | 4.35%   |
| 0x906e9    | 4        | 2.9%    |
| 0x6fd      | 4        | 2.9%    |
| 0x6fb      | 4        | 2.9%    |
| 0x406c4    | 4        | 2.9%    |
| 0x306a9    | 4        | 2.9%    |
| 0x010000c8 | 4        | 2.9%    |
| 0x6f6      | 3        | 2.17%   |
| 0x10676    | 3        | 2.17%   |
| 0x08701021 | 3        | 2.17%   |
| 0x0800820d | 3        | 2.17%   |
| 0x06000852 | 3        | 2.17%   |
| 0xa0653    | 2        | 1.45%   |
| 0x6f2      | 2        | 1.45%   |
| 0x506e3    | 2        | 1.45%   |
| 0x30678    | 2        | 1.45%   |
| 0x206d7    | 2        | 1.45%   |
| 0x20655    | 2        | 1.45%   |
| 0x106ca    | 2        | 1.45%   |
| 0x0a50000c | 2        | 1.45%   |
| 0x08701013 | 2        | 1.45%   |
| 0x0700010f | 2        | 1.45%   |
| 0x010000c7 | 2        | 1.45%   |
| 0xf65      | 1        | 0.72%   |
| 0xf4a      | 1        | 0.72%   |
| 0xa0655    | 1        | 0.72%   |
| 0x906ea    | 1        | 0.72%   |
| 0x706a1    | 1        | 0.72%   |
| 0x6f7      | 1        | 0.72%   |
| 0x406c3    | 1        | 0.72%   |
| 0x306f2    | 1        | 0.72%   |
| 0x306e4    | 1        | 0.72%   |
| 0x30661    | 1        | 0.72%   |
| 0x106e5    | 1        | 0.72%   |
| 0x10677    | 1        | 0.72%   |
| 0x0830104d | 1        | 0.72%   |
| 0x08108109 | 1        | 0.72%   |
| 0x06003106 | 1        | 0.72%   |
| 0x05000119 | 1        | 0.72%   |
| 0x010000db | 1        | 0.72%   |
| 0x01000095 | 1        | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 14       | 10.14%  |
| Penryn        | 14       | 10.14%  |
| Core          | 14       | 10.14%  |
| Haswell       | 13       | 9.42%   |
| K8 Hammer     | 11       | 7.97%   |
| K10           | 11       | 7.97%   |
| Piledriver    | 9        | 6.52%   |
| Zen 2         | 7        | 5.07%   |
| Silvermont    | 7        | 5.07%   |
| Zen+          | 6        | 4.35%   |
| KabyLake      | 5        | 3.62%   |
| IvyBridge     | 5        | 3.62%   |
| CometLake     | 4        | 2.9%    |
| Skylake       | 3        | 2.17%   |
| Bonnell       | 3        | 2.17%   |
| Zen 3         | 2        | 1.45%   |
| Westmere      | 2        | 1.45%   |
| NetBurst      | 2        | 1.45%   |
| Jaguar        | 2        | 1.45%   |
| Steamroller   | 1        | 0.72%   |
| Nehalem       | 1        | 0.72%   |
| Goldmont plus | 1        | 0.72%   |
| Bobcat        | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 54       | 37.76%  |
| Intel  | 47       | 32.87%  |
| AMD    | 42       | 29.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 6.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 4.03%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.36%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5        | 3.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 3.36%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 2.68%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 2.68%   |
| Intel HD Graphics 530                                                                    | 3        | 2.01%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.01%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.01%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 2.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.34%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 1.34%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.34%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.34%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.34%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.34%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.34%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.34%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.34%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.34%   |
| AMD Cezanne                                                                              | 2        | 1.34%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.34%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.67%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.67%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.67%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.67%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.67%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.67%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.67%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.67%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.67%   |
| Nvidia GP107GL [Quadro P400]                                                             | 1        | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.67%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.67%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 0.67%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.67%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.67%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.67%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.67%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.67%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.67%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.67%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1        | 0.67%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 0.67%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.67%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 1        | 0.67%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.67%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.67%   |
| Intel HD Graphics 630                                                                    | 1        | 0.67%   |
| Intel HD Graphics 610                                                                    | 1        | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 51       | 36.69%  |
| 1 x Intel    | 45       | 32.37%  |
| 1 x AMD      | 37       | 26.62%  |
| 2 x AMD      | 4        | 2.88%   |
| 2 x Nvidia   | 1        | 0.72%   |
| AMD + Nvidia | 1        | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 109      | 78.99%  |
| Proprietary | 27       | 19.57%  |
| Unknown     | 2        | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 52       | 37.41%  |
| 0.01-0.5   | 35       | 25.18%  |
| 0.51-1.0   | 22       | 15.83%  |
| 1.01-2.0   | 15       | 10.79%  |
| 3.01-4.0   | 9        | 6.47%   |
| 7.01-8.0   | 3        | 2.16%   |
| 8.01-16.0  | 2        | 1.44%   |
| 2.01-3.0   | 1        | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 19       | 13.97%  |
| Dell                    | 17       | 12.5%   |
| Goldstar                | 15       | 11.03%  |
| Acer                    | 11       | 8.09%   |
| Hewlett-Packard         | 9        | 6.62%   |
| BenQ                    | 6        | 4.41%   |
| Philips                 | 5        | 3.68%   |
| Lenovo                  | 5        | 3.68%   |
| Iiyama                  | 5        | 3.68%   |
| Vizio                   | 4        | 2.94%   |
| Ancor Communications    | 4        | 2.94%   |
| Unknown                 | 3        | 2.21%   |
| AOC                     | 3        | 2.21%   |
| Sony                    | 2        | 1.47%   |
| LG Electronics          | 2        | 1.47%   |
| IOD                     | 2        | 1.47%   |
| FL_                     | 2        | 1.47%   |
| ___                     | 1        | 0.74%   |
| ViewSonic               | 1        | 0.74%   |
| Unknown (ADA)           | 1        | 0.74%   |
| SHD                     | 1        | 0.74%   |
| Sceptre Tech            | 1        | 0.74%   |
| Proview                 | 1        | 0.74%   |
| Plain Tree Systems      | 1        | 0.74%   |
| NEC Computers           | 1        | 0.74%   |
| MOT                     | 1        | 0.74%   |
| Lite-On                 | 1        | 0.74%   |
| LG Display              | 1        | 0.74%   |
| Lenovo Group Limited    | 1        | 0.74%   |
| IBM                     | 1        | 0.74%   |
| Hitachi                 | 1        | 0.74%   |
| HannStar                | 1        | 0.74%   |
| GDH                     | 1        | 0.74%   |
| Fujitsu Siemens         | 1        | 0.74%   |
| Element                 | 1        | 0.74%   |
| CVT                     | 1        | 0.74%   |
| Compaq Computer         | 1        | 0.74%   |
| Chi Mei Optoelectronics | 1        | 0.74%   |
| Arnos Instruments       | 1        | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 1.42%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 1.42%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2        | 1.42%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 1.42%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 1.42%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2        | 1.42%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 1.42%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.71%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1        | 0.71%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.71%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1        | 0.71%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                    | 1        | 0.71%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                    | 1        | 0.71%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch              | 1        | 0.71%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.71%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.71%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.71%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.71%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.71%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.71%   |
| Sony TV SNYAA01 1360x768                                              | 1        | 0.71%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.71%   |
| SHD 701Lite SHD02BD 1920x1080 110x62mm 5.0-inch                       | 1        | 0.71%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1        | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.71%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x257mm 19.1-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1        | 0.71%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.71%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.71%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.71%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                   | 1        | 0.71%   |
| Samsung Electronics LCD Monitor C27F390 1920x1080                     | 1        | 0.71%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1        | 0.71%   |
| Proview MA782KC PEB030E 1280x1024 338x270mm 17.0-inch                 | 1        | 0.71%   |
| Plain Tree Systems FULL HDTV PTS00EC 1920x1080 520x290mm 23.4-inch    | 1        | 0.71%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch               | 1        | 0.71%   |
| Philips HDMI PHLC194 1920x1080 700x390mm 31.5-inch                    | 1        | 0.71%   |
| Philips 271P4 PHL08C3 1920x1080 597x336mm 27.0-inch                   | 1        | 0.71%   |
| Philips 190B PHL081A 1280x1024 376x301mm 19.0-inch                    | 1        | 0.71%   |
| Philips 170C5 PHLC00B 1280x1024 338x270mm 17.0-inch                   | 1        | 0.71%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 340x270mm 17.1-inch         | 1        | 0.71%   |
| MOT MotoAttach MOT3DC4 1366x768 260x140mm 11.6-inch                   | 1        | 0.71%   |
| Lite-On GC150AT/ATA LTN020E 1024x768 304x228mm 15.0-inch              | 1        | 0.71%   |
| LG Electronics LCD Monitor W2220                                      | 1        | 0.71%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 0.71%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1        | 0.71%   |
| Lenovo LEN-M93z-B LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 0.71%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1        | 0.71%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1        | 0.71%   |
| Lenovo Group Limited LCD Monitor LEN L24q-30 1920x1200                | 1        | 0.71%   |
| IOD LCD-A153G IOD0F46 1024x768 304x228mm 15.0-inch                    | 1        | 0.71%   |
| IOD EX-LD2381D IOD180C 1920x1080 530x300mm 24.0-inch                  | 1        | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 30.66%  |
| 1280x1024 (SXGA)   | 25       | 18.25%  |
| 1680x1050 (WSXGA+) | 17       | 12.41%  |
| 1366x768 (WXGA)    | 10       | 7.3%    |
| 1440x900 (WXGA+)   | 9        | 6.57%   |
| 2560x1440 (QHD)    | 8        | 5.84%   |
| 1024x768 (XGA)     | 6        | 4.38%   |
| 3840x2160 (4K)     | 4        | 2.92%   |
| 1600x900 (HD+)     | 3        | 2.19%   |
| 3440x1440          | 2        | 1.46%   |
| 2560x1080          | 2        | 1.46%   |
| 1280x800 (WXGA)    | 2        | 1.46%   |
| 3600x1200          | 1        | 0.73%   |
| 2560x1600          | 1        | 0.73%   |
| 2288x1287          | 1        | 0.73%   |
| 1920x1200 (WUXGA)  | 1        | 0.73%   |
| 1600x1200          | 1        | 0.73%   |
| 1360x768           | 1        | 0.73%   |
| Unknown            | 1        | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 18       | 13.14%  |
| 27      | 13       | 9.49%   |
| 19      | 13       | 9.49%   |
| 23      | 11       | 8.03%   |
| 21      | 11       | 8.03%   |
| Unknown | 11       | 8.03%   |
| 24      | 10       | 7.3%    |
| 22      | 10       | 7.3%    |
| 20      | 8        | 5.84%   |
| 15      | 7        | 5.11%   |
| 18      | 6        | 4.38%   |
| 34      | 3        | 2.19%   |
| 41      | 2        | 1.46%   |
| 39      | 2        | 1.46%   |
| 31      | 2        | 1.46%   |
| 72      | 1        | 0.73%   |
| 52      | 1        | 0.73%   |
| 48      | 1        | 0.73%   |
| 47      | 1        | 0.73%   |
| 38      | 1        | 0.73%   |
| 29      | 1        | 0.73%   |
| 14      | 1        | 0.73%   |
| 11      | 1        | 0.73%   |
| 7       | 1        | 0.73%   |
| 5       | 1        | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 39       | 28.89%  |
| 501-600     | 33       | 24.44%  |
| 301-350     | 24       | 17.78%  |
| Unknown     | 11       | 8.15%   |
| 351-400     | 9        | 6.67%   |
| 601-700     | 4        | 2.96%   |
| 801-900     | 3        | 2.22%   |
| 701-800     | 3        | 2.22%   |
| 1001-1500   | 3        | 2.22%   |
| 101-200     | 2        | 1.48%   |
| 901-1000    | 2        | 1.48%   |
| 201-300     | 1        | 0.74%   |
| 1501-2000   | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 63       | 48.09%  |
| 5/4     | 23       | 17.56%  |
| 16/10   | 22       | 16.79%  |
| Unknown | 10       | 7.63%   |
| 4/3     | 6        | 4.58%   |
| 21/9    | 4        | 3.05%   |
| 6/5     | 2        | 1.53%   |
| 3/2     | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 27.41%  |
| 151-200        | 24       | 17.78%  |
| 141-150        | 21       | 15.56%  |
| 301-350        | 14       | 10.37%  |
| Unknown        | 11       | 8.15%   |
| 101-110        | 7        | 5.19%   |
| 501-1000       | 6        | 4.44%   |
| 351-500        | 5        | 3.7%    |
| More than 1000 | 3        | 2.22%   |
| 1-40           | 2        | 1.48%   |
| 251-300        | 2        | 1.48%   |
| 81-90          | 1        | 0.74%   |
| 51-60          | 1        | 0.74%   |
| 131-140        | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 90       | 68.7%   |
| 101-120       | 16       | 12.21%  |
| Unknown       | 11       | 8.4%    |
| 121-160       | 7        | 5.34%   |
| 1-50          | 4        | 3.05%   |
| 161-240       | 2        | 1.53%   |
| More than 240 | 1        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 121      | 87.68%  |
| 2     | 10       | 7.25%   |
| 0     | 5        | 3.62%   |
| 4     | 1        | 0.72%   |
| 3     | 1        | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 81       | 42.41%  |
| Intel                    | 45       | 23.56%  |
| Nvidia                   | 14       | 7.33%   |
| Ralink Technology        | 11       | 5.76%   |
| Qualcomm Atheros         | 11       | 5.76%   |
| Ralink                   | 5        | 2.62%   |
| Broadcom                 | 4        | 2.09%   |
| Marvell Technology Group | 3        | 1.57%   |
| TP-Link                  | 2        | 1.05%   |
| Samsung Electronics      | 2        | 1.05%   |
| Broadcom Limited         | 2        | 1.05%   |
| ZyXEL Communications     | 1        | 0.52%   |
| VIA Technologies         | 1        | 0.52%   |
| U-Blox                   | 1        | 0.52%   |
| Sitecom Europe           | 1        | 0.52%   |
| NetGear                  | 1        | 0.52%   |
| Logitec                  | 1        | 0.52%   |
| Huawei Technologies      | 1        | 0.52%   |
| Belkin Components        | 1        | 0.52%   |
| ASIX Electronics         | 1        | 0.52%   |
| Aquantia                 | 1        | 0.52%   |
| ADMtek                   | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60       | 28.99%  |
| Nvidia MCP61 Ethernet                                             | 8        | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.93%   |
| Ralink RT5572 Wireless Adapter                                    | 3        | 1.45%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.45%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.97%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.97%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.97%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.97%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.97%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.97%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.97%   |
| Intel Wireless-AC 9260                                            | 2        | 0.97%   |
| Intel Wireless 7260                                               | 2        | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.97%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.97%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.48%   |
| U-Blox GNSS receiver                                              | 1        | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.48%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.48%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.48%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.48%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.48%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.48%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.48%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.48%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.48%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.48%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.48%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.48%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.48%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.48%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.48%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 23.21%  |
| Ralink Technology     | 11       | 19.64%  |
| Intel                 | 11       | 19.64%  |
| Qualcomm Atheros      | 8        | 14.29%  |
| Ralink                | 5        | 8.93%   |
| TP-Link               | 2        | 3.57%   |
| ZyXEL Communications  | 1        | 1.79%   |
| Sitecom Europe        | 1        | 1.79%   |
| NetGear               | 1        | 1.79%   |
| Logitec               | 1        | 1.79%   |
| Broadcom              | 1        | 1.79%   |
| Belkin Components     | 1        | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                    | 5        | 8.93%   |
| Ralink RT5572 Wireless Adapter                                                         | 3        | 5.36%   |
| Ralink MT7601U Wireless Adapter                                                        | 3        | 5.36%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                             | 3        | 5.36%   |
| Realtek RTL8187 Wireless Adapter                                                       | 2        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                  | 2        | 3.57%   |
| Ralink RT2561/RT61 802.11g PCI                                                         | 2        | 3.57%   |
| Intel Wireless-AC 9260                                                                 | 2        | 3.57%   |
| Intel Wireless 7260                                                                    | 2        | 3.57%   |
| ZyXEL ZyAIR G-202 802.11bg                                                             | 1        | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                            | 1        | 1.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                             | 1        | 1.79%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                        | 1        | 1.79%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                        | 1        | 1.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                 | 1        | 1.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 1        | 1.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                  | 1        | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 1        | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                | 1        | 1.79%   |
| Ralink RT5372 Wireless Adapter                                                         | 1        | 1.79%   |
| Ralink RT5370 Wireless Adapter                                                         | 1        | 1.79%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                  | 1        | 1.79%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                            | 1        | 1.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                              | 1        | 1.79%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                              | 1        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                       | 1        | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                       | 1        | 1.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                         | 1        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 1        | 1.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                       | 1        | 1.79%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                            | 1        | 1.79%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                                              | 1        | 1.79%   |
| Intel Wireless 7265                                                                    | 1        | 1.79%   |
| Intel Wireless 3165                                                                    | 1        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                 | 1        | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                                         | 1        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                       | 1        | 1.79%   |
| Intel Centrino Advanced-N 6235                                                         | 1        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                           | 1        | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                    | 1        | 1.79%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 73       | 51.05%  |
| Intel                    | 36       | 25.17%  |
| Nvidia                   | 14       | 9.79%   |
| Qualcomm Atheros         | 4        | 2.8%    |
| Broadcom                 | 4        | 2.8%    |
| Marvell Technology Group | 3        | 2.1%    |
| Samsung Electronics      | 2        | 1.4%    |
| Broadcom Limited         | 2        | 1.4%    |
| VIA Technologies         | 1        | 0.7%    |
| Huawei Technologies      | 1        | 0.7%    |
| ASIX Electronics         | 1        | 0.7%    |
| Aquantia                 | 1        | 0.7%    |
| ADMtek                   | 1        | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60       | 40%     |
| Nvidia MCP61 Ethernet                                             | 8        | 5.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.67%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.67%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2%      |
| Intel 82574L Gigabit Network Connection                           | 3        | 2%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.33%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.33%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.33%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.67%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.67%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.67%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.67%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.67%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.67%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.67%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.67%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.67%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.67%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.67%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.67%   |
| Huawei JNY-LX1                                                    | 1        | 0.67%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.67%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.67%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.67%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.67%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.67%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 70.98%  |
| WiFi     | 55       | 28.5%   |
| Modem    | 1        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 78.47%  |
| WiFi     | 31       | 21.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 103      | 74.64%  |
| 2     | 30       | 21.74%  |
| 3     | 4        | 2.9%    |
| 0     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 112      | 80.58%  |
| Yes  | 27       | 19.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 43.48%  |
| Cambridge Silicon Radio | 7        | 30.43%  |
| Broadcom                | 3        | 13.04%  |
| Ralink                  | 1        | 4.35%   |
| Lite-On Technology      | 1        | 4.35%   |
| Hewlett-Packard         | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 30.43%  |
| Intel Bluetooth wireless interface                  | 4        | 17.39%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 8.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 8.7%    |
| Ralink RT3290 Bluetooth                             | 1        | 4.35%   |
| Lite-On Bluetooth Device                            | 1        | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4.35%   |
| Intel AX210 Bluetooth                               | 1        | 4.35%   |
| Intel AX201 Bluetooth                               | 1        | 4.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 4.35%   |
| Broadcom Bluetooth Device                           | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 79       | 40.1%   |
| Nvidia                   | 51       | 25.89%  |
| AMD                      | 49       | 24.87%  |
| Creative Labs            | 4        | 2.03%   |
| C-Media Electronics      | 4        | 2.03%   |
| XMOS                     | 2        | 1.02%   |
| VIA Technologies         | 1        | 0.51%   |
| Unknown                  | 1        | 0.51%   |
| Logitech                 | 1        | 0.51%   |
| GN Netcom                | 1        | 0.51%   |
| Focusrite-Novation       | 1        | 0.51%   |
| Creative Technology      | 1        | 0.51%   |
| ASUSTek Computer         | 1        | 0.51%   |
| Asahi Kasei Microsystems | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                 | 11       | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller              | 11       | 4.89%   |
| Nvidia High Definition Audio Controller                                                 | 10       | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                     | 9        | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                                            | 9        | 4%      |
| AMD FCH Azalia Controller                                                               | 9        | 4%      |
| Nvidia MCP61 High Definition Audio                                                      | 8        | 3.56%   |
| Nvidia GP107GL High Definition Audio Controller                                         | 7        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                        | 7        | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                          | 6        | 2.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                     | 6        | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                                | 6        | 2.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                     | 5        | 2.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                          | 5        | 2.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                           | 4        | 1.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                   | 4        | 1.78%   |
| Nvidia GK107 HDMI Audio Controller                                                      | 4        | 1.78%   |
| Intel 200 Series PCH HD Audio                                                           | 4        | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                         | 4        | 1.78%   |
| AMD Trinity HDMI Audio Controller                                                       | 4        | 1.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                 | 4        | 1.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                     | 4        | 1.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                  | 4        | 1.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                                       | 3        | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                | 3        | 1.33%   |
| AMD Family 17h/19h HD Audio Controller                                                  | 3        | 1.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]       | 3        | 1.33%   |
| XMOS Mayfield Audio                                                                     | 2        | 0.89%   |
| Nvidia GK106 HDMI Audio Controller                                                      | 2        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                           | 2        | 0.89%   |
| Nvidia CK804 AC'97 Audio Controller                                                     | 2        | 0.89%   |
| Intel Audio device                                                                      | 2        | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller              | 2        | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                        | 2        | 0.89%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                              | 2        | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                        | 2        | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                      | 2        | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                | 2        | 0.89%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                          | 2        | 0.89%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                      | 1        | 0.44%   |
| Unknown Realtek USB Audio Rear                                                          | 1        | 0.44%   |
| Unknown Realtek USB Audio Front                                                         | 1        | 0.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                          | 1        | 0.44%   |
| Nvidia TU104 HD Audio Controller                                                        | 1        | 0.44%   |
| Nvidia TU102 High Definition Audio Controller                                           | 1        | 0.44%   |
| Nvidia MCP73 High Definition Audio                                                      | 1        | 0.44%   |
| Nvidia MCP67 High Definition Audio                                                      | 1        | 0.44%   |
| Nvidia MCP51 High Definition Audio                                                      | 1        | 0.44%   |
| Nvidia GM206 High Definition Audio Controller                                           | 1        | 0.44%   |
| Nvidia GM204 High Definition Audio Controller                                           | 1        | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                      | 1        | 0.44%   |
| Nvidia GF119 HDMI Audio Controller                                                      | 1        | 0.44%   |
| Nvidia GF116 High Definition Audio Controller                                           | 1        | 0.44%   |
| Logitech EasyCall Speakerphone                                                          | 1        | 0.44%   |
| Intel Comet Lake PCH-V cAVS                                                             | 1        | 0.44%   |
| Intel Comet Lake PCH cAVS                                                               | 1        | 0.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                            | 1        | 0.44%   |
| Intel C610/X99 series chipset HD Audio Controller                                       | 1        | 0.44%   |
| Intel C600/X79 series chipset High Definition Audio Controller                          | 1        | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio | 1        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 19       | 18.81%  |
| Samsung Electronics | 18       | 17.82%  |
| SK hynix            | 16       | 15.84%  |
| Kingston            | 9        | 8.91%   |
| G.Skill             | 8        | 7.92%   |
| Micron Technology   | 5        | 4.95%   |
| Crucial             | 5        | 4.95%   |
| Corsair             | 5        | 4.95%   |
| Nanya Technology    | 3        | 2.97%   |
| Timetec             | 2        | 1.98%   |
| Patriot             | 2        | 1.98%   |
| Elpida              | 2        | 1.98%   |
| Unknown (ABCD)      | 1        | 0.99%   |
| Unifosa             | 1        | 0.99%   |
| Team                | 1        | 0.99%   |
| Ramaxel Technology  | 1        | 0.99%   |
| Qimonda             | 1        | 0.99%   |
| e2e4                | 1        | 0.99%   |
| 48spaces            | 1        | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                | 4        | 3.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 2        | 1.82%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                       | 2        | 1.82%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 2        | 1.82%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s           | 2        | 1.82%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                 | 1        | 0.91%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                       | 1        | 0.91%   |
| Unknown RAM Module 512MB DIMM 400MT/s                        | 1        | 0.91%   |
| Unknown RAM Module 512MB DIMM 333MT/s                        | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                 | 1        | 0.91%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1        | 0.91%   |
| Unknown RAM Module 2048MB DIMM DDR2                          | 1        | 0.91%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 1        | 0.91%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                   | 1        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 1        | 0.91%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s            | 1        | 0.91%   |
| Timetec RAM UD3-1600 8192MB DIMM DDR3 1600MT/s               | 1        | 0.91%   |
| Timetec RAM SD3-1600 8192MB SODIMM DDR3 1600MT/s             | 1        | 0.91%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s           | 1        | 0.91%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 0.91%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 0.91%   |
| SK hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s       | 1        | 0.91%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1        | 0.91%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1        | 0.91%   |
| SK hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s      | 1        | 0.91%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.91%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s      | 1        | 0.91%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s      | 1        | 0.91%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1        | 0.91%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s         | 1        | 0.91%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 0.91%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 1        | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.91%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1        | 0.91%   |
| Samsung RAM M471B1G73AH0-CK0 4096MB SODIMM DDR3 1333MT/s     | 1        | 0.91%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s    | 1        | 0.91%   |
| Samsung RAM M4 70T2864FB3-CF7 1024MB SODIMM DDR2 667MT/s     | 1        | 0.91%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1600MT/s       | 1        | 0.91%   |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s         | 1        | 0.91%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 1        | 0.91%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.91%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s          | 1        | 0.91%   |
| Samsung RAM M378B5273BH1-CF8 4096MB DIMM 1066MT/s            | 1        | 0.91%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s          | 1        | 0.91%   |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s       | 1        | 0.91%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s          | 1        | 0.91%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s          | 1        | 0.91%   |
| Samsung RAM M3 78T2863RZS-CE6 1024MB DIMM DDR2 667MT/s       | 1        | 0.91%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM SDRAM 1639MT/s        | 1        | 0.91%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s       | 1        | 0.91%   |
| Samsung RAM M3 12L2920CZ3-CCC 1024MB DIMM DDR 400MT/s        | 1        | 0.91%   |
| Ramaxel RAM RML1040EG38D6F-533 512MB DIMM DDR2 533MT/s       | 1        | 0.91%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s             | 1        | 0.91%   |
| Patriot RAM PSD44G213341 4096MB DIMM DDR4 3000MT/s           | 1        | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 36       | 39.13%  |
| DDR4    | 20       | 21.74%  |
| DDR2    | 15       | 16.3%   |
| SDRAM   | 10       | 10.87%  |
| Unknown | 8        | 8.7%    |
| DDR     | 2        | 2.17%   |
| LPDDR4  | 1        | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 76       | 87.36%  |
| SODIMM | 11       | 12.64%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 30       | 31.91%  |
| 8192  | 22       | 23.4%   |
| 4096  | 21       | 22.34%  |
| 1024  | 8        | 8.51%   |
| 16384 | 7        | 7.45%   |
| 512   | 3        | 3.19%   |
| 32768 | 2        | 2.13%   |
| 65536 | 1        | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 21%     |
| 1333    | 11       | 11%     |
| 800     | 9        | 9%      |
| 2133    | 8        | 8%      |
| 667     | 6        | 6%      |
| 2400    | 5        | 5%      |
| 400     | 5        | 5%      |
| 3200    | 4        | 4%      |
| 1866    | 4        | 4%      |
| Unknown | 4        | 4%      |
| 2667    | 3        | 3%      |
| 2048    | 3        | 3%      |
| 1066    | 3        | 3%      |
| 3600    | 2        | 2%      |
| 3000    | 2        | 2%      |
| 1867    | 2        | 2%      |
| 49926   | 1        | 1%      |
| 3466    | 1        | 1%      |
| 3066    | 1        | 1%      |
| 2733    | 1        | 1%      |
| 1639    | 1        | 1%      |
| 1334    | 1        | 1%      |
| 533     | 1        | 1%      |
| 333     | 1        | 1%      |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Desktops | Percent |
|-----------------|----------|---------|
| HP scanjet 8270 | 1        | 100%    |

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
| Sunplus Innovation Technology | 1        | 5.56%   |
| SJ-180517-N                   | 1        | 5.56%   |
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
| Generalplus GENERAL WEBCAM                | 2        | 11.11%  |
| Z-Star Sirius USB2.0 Camera               | 1        | 5.56%   |
| Sunplus Full HD webcam                    | 1        | 5.56%   |
| SJ-180517-N 1080P Webcam                  | 1        | 5.56%   |
| Samsung Galaxy series, misc. (MTP mode)   | 1        | 5.56%   |
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
| 0     | 115      | 83.33%  |
| 1     | 21       | 15.22%  |
| 2     | 2        | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 27.27%  |
| Communication controller | 4        | 18.18%  |
| Sound                    | 3        | 13.64%  |
| Net/wireless             | 3        | 13.64%  |
| Unassigned class         | 2        | 9.09%   |
| Net/ethernet             | 1        | 4.55%   |
| Multimedia controller    | 1        | 4.55%   |
| Dvb card                 | 1        | 4.55%   |
| Bluetooth                | 1        | 4.55%   |

