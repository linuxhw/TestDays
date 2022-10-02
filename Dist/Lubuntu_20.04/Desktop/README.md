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

Total: 181

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Maximus V FORMULA           | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
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
| 5.4.0-52-generic      | 8        | 5.37%   |
| 5.4.0-42-generic      | 8        | 5.37%   |
| 5.11.0-27-generic     | 7        | 4.7%    |
| 5.8.0-50-generic      | 6        | 4.03%   |
| 5.4.0-54-generic      | 5        | 3.36%   |
| 5.13.0-28-generic     | 5        | 3.36%   |
| 5.4.0-67-generic      | 4        | 2.68%   |
| 5.4.0-40-generic      | 4        | 2.68%   |
| 5.4.0-29-generic      | 4        | 2.68%   |
| 5.4.0-122-generic     | 4        | 2.68%   |
| 5.4.0-77-generic      | 3        | 2.01%   |
| 5.4.0-73-generic      | 3        | 2.01%   |
| 5.4.0-48-generic      | 3        | 2.01%   |
| 5.4.0-47-generic      | 3        | 2.01%   |
| 5.4.0-37-generic      | 3        | 2.01%   |
| 5.4.0-33-generic      | 3        | 2.01%   |
| 5.4.0-26-generic      | 3        | 2.01%   |
| 5.8.0-63-generic      | 2        | 1.34%   |
| 5.8.0-59-generic      | 2        | 1.34%   |
| 5.8.0-53-generic      | 2        | 1.34%   |
| 5.8.0-45-generic      | 2        | 1.34%   |
| 5.8.0-41-generic      | 2        | 1.34%   |
| 5.4.0-96-generic      | 2        | 1.34%   |
| 5.4.0-91-generic      | 2        | 1.34%   |
| 5.4.0-90-generic      | 2        | 1.34%   |
| 5.4.0-72-generic      | 2        | 1.34%   |
| 5.4.0-66-generic      | 2        | 1.34%   |
| 5.4.0-60-generic      | 2        | 1.34%   |
| 5.4.0-109-generic     | 2        | 1.34%   |
| 5.13.0-27-generic     | 2        | 1.34%   |
| 5.11.0-43-generic     | 2        | 1.34%   |
| 5.11.0-38-generic     | 2        | 1.34%   |
| 5.11.0-34-generic     | 2        | 1.34%   |
| 5.8.0-7630-generic    | 1        | 0.67%   |
| 5.8.0-55-generic      | 1        | 0.67%   |
| 5.8.0-48-generic      | 1        | 0.67%   |
| 5.8.0-43-generic      | 1        | 0.67%   |
| 5.8.0-29-lowlatency   | 1        | 0.67%   |
| 5.6.15-050615-generic | 1        | 0.67%   |
| 5.6.0-1052-oem        | 1        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 81       | 57.45%  |
| 5.8.0   | 21       | 14.89%  |
| 5.11.0  | 18       | 12.77%  |
| 5.13.0  | 13       | 9.22%   |
| 5.15.0  | 2        | 1.42%   |
| 5.6.15  | 1        | 0.71%   |
| 5.6.0   | 1        | 0.71%   |
| 5.4.30  | 1        | 0.71%   |
| 5.3.18  | 1        | 0.71%   |
| 5.16.5  | 1        | 0.71%   |
| 5.14.0  | 1        | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 82       | 58.16%  |
| 5.8     | 21       | 14.89%  |
| 5.11    | 18       | 12.77%  |
| 5.13    | 13       | 9.22%   |
| 5.6     | 2        | 1.42%   |
| 5.15    | 2        | 1.42%   |
| 5.3     | 1        | 0.71%   |
| 5.16    | 1        | 0.71%   |
| 5.14    | 1        | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 140      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 130      | 92.86%  |
| LXDE       | 4        | 2.86%   |
| GNOME      | 3        | 2.14%   |
| XFCE       | 1        | 0.71%   |
| X-Cinnamon | 1        | 0.71%   |
| i3         | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 133      | 95%     |
| Tty     | 6        | 4.29%   |
| Unknown | 1        | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 74       | 51.39%  |
| Unknown | 43       | 29.86%  |
| LightDM | 10       | 6.94%   |
| GDM     | 9        | 6.25%   |
| TDM     | 6        | 4.17%   |
| LXDM    | 1        | 0.69%   |
| GDM3    | 1        | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 36       | 25.71%  |
| fr_FR   | 19       | 13.57%  |
| de_DE   | 13       | 9.29%   |
| pt_BR   | 11       | 7.86%   |
| it_IT   | 9        | 6.43%   |
| C       | 7        | 5%      |
| ru_RU   | 5        | 3.57%   |
| ja_JP   | 4        | 2.86%   |
| en_GB   | 4        | 2.86%   |
| en_AU   | 4        | 2.86%   |
| fi_FI   | 3        | 2.14%   |
| es_ES   | 3        | 2.14%   |
| hu_HU   | 2        | 1.43%   |
| en_ZA   | 2        | 1.43%   |
| en_CA   | 2        | 1.43%   |
| de_CH   | 2        | 1.43%   |
| cs_CZ   | 2        | 1.43%   |
| Unknown | 2        | 1.43%   |
| sv_SE   | 1        | 0.71%   |
| nl_NL   | 1        | 0.71%   |
| fr_CA   | 1        | 0.71%   |
| es_PE   | 1        | 0.71%   |
| es_MX   | 1        | 0.71%   |
| es_CR   | 1        | 0.71%   |
| es_CO   | 1        | 0.71%   |
| en_SG   | 1        | 0.71%   |
| en_NZ   | 1        | 0.71%   |
| el_GR   | 1        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 94       | 67.14%  |
| EFI  | 46       | 32.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 128      | 91.43%  |
| Overlay | 7        | 5%      |
| Xfs     | 2        | 1.43%   |
| Zfs     | 1        | 0.71%   |
| F2fs    | 1        | 0.71%   |
| Btrfs   | 1        | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 40.43%  |
| MBR     | 46       | 32.62%  |
| GPT     | 38       | 26.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 81.43%  |
| Yes       | 26       | 18.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 68.79%  |
| Yes       | 44       | 31.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 23       | 16.43%  |
| MSI                 | 16       | 11.43%  |
| Hewlett-Packard     | 16       | 11.43%  |
| Gigabyte Technology | 15       | 10.71%  |
| ASRock              | 15       | 10.71%  |
| Dell                | 14       | 10%     |
| Lenovo              | 8        | 5.71%   |
| Intel               | 7        | 5%      |
| Pegatron            | 4        | 2.86%   |
| Acer                | 4        | 2.86%   |
| AAEON               | 3        | 2.14%   |
| Positivo            | 2        | 1.43%   |
| Foxconn             | 2        | 1.43%   |
| Biostar             | 2        | 1.43%   |
| ZOTAC               | 1        | 0.71%   |
| Packard Bell        | 1        | 0.71%   |
| IBM                 | 1        | 0.71%   |
| Huanan              | 1        | 0.71%   |
| Hardkernel          | 1        | 0.71%   |
| Fujitsu Siemens     | 1        | 0.71%   |
| Fujitsu             | 1        | 0.71%   |
| AMI                 | 1        | 0.71%   |
| Unknown             | 1        | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| AAEON MF-001                                                 | 3        | 2.14%   |
| MSI MS-7C37                                                  | 2        | 1.43%   |
| MSI MS-7B89                                                  | 2        | 1.43%   |
| HP Compaq 6000 Pro SFF PC                                    | 2        | 1.43%   |
| Dell OptiPlex 790                                            | 2        | 1.43%   |
| ASUS M5A97 R2.0                                              | 2        | 1.43%   |
| ASRock N68-VS3 UCC                                           | 2        | 1.43%   |
| ASRock FM2A85X Extreme6                                      | 2        | 1.43%   |
| ZOTAC NM10                                                   | 1        | 0.71%   |
| Positivo POS-MI945AA                                         | 1        | 0.71%   |
| Positivo POS-EIH61CE                                         | 1        | 0.71%   |
| Pegatron WE216AA-ABF CQ5335FR                                | 1        | 0.71%   |
| Pegatron NC689AA-ABA s3700y                                  | 1        | 0.71%   |
| Pegatron FL308AA-ABD IQ512de                                 | 1        | 0.71%   |
| Pegatron AY652AA-ABA s5310y                                  | 1        | 0.71%   |
| Packard Bell IMEDIA S1350                                    | 1        | 0.71%   |
| MSI MS-7D16                                                  | 1        | 0.71%   |
| MSI MS-7B86                                                  | 1        | 0.71%   |
| MSI MS-7B09                                                  | 1        | 0.71%   |
| MSI MS-7994                                                  | 1        | 0.71%   |
| MSI MS-7846                                                  | 1        | 0.71%   |
| MSI MS-7721                                                  | 1        | 0.71%   |
| MSI MS-7680                                                  | 1        | 0.71%   |
| MSI MS-7640                                                  | 1        | 0.71%   |
| MSI MS-7592                                                  | 1        | 0.71%   |
| MSI MS-7309                                                  | 1        | 0.71%   |
| MSI ER883AA-ABA M7470N                                       | 1        | 0.71%   |
| MSI Compaq dx2200 MT                                         | 1        | 0.71%   |
| Lenovo ThinkStation P620 30E0CTO1WW                          | 1        | 0.71%   |
| Lenovo ThinkCentre M93z 10AD002DMZ                           | 1        | 0.71%   |
| Lenovo ThinkCentre M73 10AXS0HN00                            | 1        | 0.71%   |
| Lenovo ThinkCentre M58p 7220W21                              | 1        | 0.71%   |
| Lenovo ThinkCentre M58p 6136A66                              | 1        | 0.71%   |
| Lenovo ThinkCentre M55p 8811VQV                              | 1        | 0.71%   |
| Lenovo H50-50 90B60081IX                                     | 1        | 0.71%   |
| Lenovo H50-30g 90AS0002BR                                    | 1        | 0.71%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V304 | 1        | 0.71%   |
| Intel STK1AW32SC                                             | 1        | 0.71%   |
| Intel H55                                                    | 1        | 0.71%   |
| Intel DN2800MT AAG23738-801                                  | 1        | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 8        | 5.71%   |
| Dell OptiPlex        | 6        | 4.29%   |
| Lenovo ThinkCentre   | 5        | 3.57%   |
| Acer Aspire          | 4        | 2.86%   |
| AAEON MF-001         | 3        | 2.14%   |
| MSI MS-7C37          | 2        | 1.43%   |
| MSI MS-7B89          | 2        | 1.43%   |
| HP t620              | 2        | 1.43%   |
| Gigabyte B450M       | 2        | 1.43%   |
| Dell Inspiron        | 2        | 1.43%   |
| ASUS M5A97           | 2        | 1.43%   |
| ASRock N68-VS3       | 2        | 1.43%   |
| ASRock FM2A85X       | 2        | 1.43%   |
| ZOTAC NM10           | 1        | 0.71%   |
| Positivo POS-MI945AA | 1        | 0.71%   |
| Positivo POS-EIH61CE | 1        | 0.71%   |
| Pegatron WE216AA-ABF | 1        | 0.71%   |
| Pegatron NC689AA-ABA | 1        | 0.71%   |
| Pegatron FL308AA-ABD | 1        | 0.71%   |
| Pegatron AY652AA-ABA | 1        | 0.71%   |
| Packard Bell IMEDIA  | 1        | 0.71%   |
| MSI MS-7D16          | 1        | 0.71%   |
| MSI MS-7B86          | 1        | 0.71%   |
| MSI MS-7B09          | 1        | 0.71%   |
| MSI MS-7994          | 1        | 0.71%   |
| MSI MS-7846          | 1        | 0.71%   |
| MSI MS-7721          | 1        | 0.71%   |
| MSI MS-7680          | 1        | 0.71%   |
| MSI MS-7640          | 1        | 0.71%   |
| MSI MS-7592          | 1        | 0.71%   |
| MSI MS-7309          | 1        | 0.71%   |
| MSI ER883AA-ABA      | 1        | 0.71%   |
| MSI Compaq           | 1        | 0.71%   |
| Lenovo ThinkStation  | 1        | 0.71%   |
| Lenovo H50-50        | 1        | 0.71%   |
| Lenovo H50-30g       | 1        | 0.71%   |
| Intel X79            | 1        | 0.71%   |
| Intel STK1AW32SC     | 1        | 0.71%   |
| Intel H55            | 1        | 0.71%   |
| Intel DN2800MT       | 1        | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 13       | 9.29%   |
| 2011 | 12       | 8.57%   |
| 2007 | 12       | 8.57%   |
| 2009 | 11       | 7.86%   |
| 2013 | 10       | 7.14%   |
| 2008 | 10       | 7.14%   |
| 2017 | 9        | 6.43%   |
| 2014 | 9        | 6.43%   |
| 2010 | 9        | 6.43%   |
| 2019 | 8        | 5.71%   |
| 2006 | 7        | 5%      |
| 2020 | 6        | 4.29%   |
| 2015 | 6        | 4.29%   |
| 2021 | 5        | 3.57%   |
| 2018 | 5        | 3.57%   |
| 2005 | 4        | 2.86%   |
| 2016 | 3        | 2.14%   |
| 2004 | 1        | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 140      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 136      | 97.14%  |
| Enabled  | 4        | 2.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 140      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 40       | 28.37%  |
| 8.01-16.0       | 22       | 15.6%   |
| 1.01-2.0        | 19       | 13.48%  |
| 4.01-8.0        | 18       | 12.77%  |
| 16.01-24.0      | 18       | 12.77%  |
| 32.01-64.0      | 11       | 7.8%    |
| 24.01-32.0      | 4        | 2.84%   |
| 2.01-3.0        | 3        | 2.13%   |
| 64.01-256.0     | 3        | 2.13%   |
| 0.51-1.0        | 2        | 1.42%   |
| More than 256.0 | 1        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 68       | 46.9%   |
| 2.01-3.0   | 26       | 17.93%  |
| 0.51-1.0   | 21       | 14.48%  |
| 4.01-8.0   | 16       | 11.03%  |
| 3.01-4.0   | 7        | 4.83%   |
| 0.01-0.5   | 3        | 2.07%   |
| 8.01-16.0  | 2        | 1.38%   |
| 32.01-64.0 | 1        | 0.69%   |
| 16.01-24.0 | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 49.65%  |
| 2      | 41       | 29.08%  |
| 4      | 11       | 7.8%    |
| 3      | 8        | 5.67%   |
| 5      | 5        | 3.55%   |
| 6      | 2        | 1.42%   |
| 17     | 1        | 0.71%   |
| 14     | 1        | 0.71%   |
| 7      | 1        | 0.71%   |
| 0      | 1        | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 87       | 61.27%  |
| No        | 55       | 38.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 139      | 99.29%  |
| No        | 1        | 0.71%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 60%     |
| Yes       | 56       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 116      | 82.86%  |
| Yes       | 24       | 17.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 22       | 15.49%  |
| France       | 19       | 13.38%  |
| Germany      | 15       | 10.56%  |
| Brazil       | 12       | 8.45%   |
| Italy        | 9        | 6.34%   |
| Switzerland  | 6        | 4.23%   |
| Russia       | 5        | 3.52%   |
| Hungary      | 5        | 3.52%   |
| Spain        | 4        | 2.82%   |
| Japan        | 4        | 2.82%   |
| Finland      | 4        | 2.82%   |
| Australia    | 4        | 2.82%   |
| Netherlands  | 3        | 2.11%   |
| Czechia      | 3        | 2.11%   |
| Canada       | 3        | 2.11%   |
| South Africa | 2        | 1.41%   |
| Puerto Rico  | 2        | 1.41%   |
| New Zealand  | 2        | 1.41%   |
| Mexico       | 2        | 1.41%   |
| Greece       | 2        | 1.41%   |
| Belgium      | 2        | 1.41%   |
| UK           | 1        | 0.7%    |
| Sweden       | 1        | 0.7%    |
| Slovenia     | 1        | 0.7%    |
| Slovakia     | 1        | 0.7%    |
| Singapore    | 1        | 0.7%    |
| Romania      | 1        | 0.7%    |
| Peru         | 1        | 0.7%    |
| Malaysia     | 1        | 0.7%    |
| Ireland      | 1        | 0.7%    |
| Costa Rica   | 1        | 0.7%    |
| Colombia     | 1        | 0.7%    |
| Belarus      | 1        | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Wellington            | 3        | 2.07%   |
| Melbourne             | 3        | 2.07%   |
| Zurich                | 2        | 1.38%   |
| Rome                  | 2        | 1.38%   |
| Raahe                 | 2        | 1.38%   |
| Pécs                 | 2        | 1.38%   |
| Figeac                | 2        | 1.38%   |
| Cuernavaca            | 2        | 1.38%   |
| Cayey                 | 2        | 1.38%   |
| Bern                  | 2        | 1.38%   |
| Zwevegem              | 1        | 0.69%   |
| Zeuthen               | 1        | 0.69%   |
| Wraysbury             | 1        | 0.69%   |
| Winsen                | 1        | 0.69%   |
| Wiesbaden             | 1        | 0.69%   |
| West Chester          | 1        | 0.69%   |
| Vinhedo               | 1        | 0.69%   |
| Vilyuchinsk           | 1        | 0.69%   |
| Villejuif             | 1        | 0.69%   |
| Vilabella             | 1        | 0.69%   |
| Vaxjo                 | 1        | 0.69%   |
| Vanderbijlpark        | 1        | 0.69%   |
| Valencia              | 1        | 0.69%   |
| Turku                 | 1        | 0.69%   |
| Trebur                | 1        | 0.69%   |
| Toulouse              | 1        | 0.69%   |
| Toronto               | 1        | 0.69%   |
| Tokorozawa            | 1        | 0.69%   |
| Stockton              | 1        | 0.69%   |
| Stedesand             | 1        | 0.69%   |
| Spokane               | 1        | 0.69%   |
| Sora                  | 1        | 0.69%   |
| Schiedam              | 1        | 0.69%   |
| Sautron               | 1        | 0.69%   |
| Sao Paulo             | 1        | 0.69%   |
| Sandorfalva           | 1        | 0.69%   |
| Salzgitter            | 1        | 0.69%   |
| Saint-Pair-sur-Mer    | 1        | 0.69%   |
| Saint-Michel-sur-Orge | 1        | 0.69%   |
| Saint Paul            | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 65     | 23.87%  |
| WDC                 | 51       | 81     | 22.97%  |
| Samsung Electronics | 28       | 49     | 12.61%  |
| Hitachi             | 11       | 14     | 4.95%   |
| Toshiba             | 9        | 9      | 4.05%   |
| Kingston            | 9        | 9      | 4.05%   |
| Unknown             | 7        | 8      | 3.15%   |
| Crucial             | 7        | 19     | 3.15%   |
| SanDisk             | 4        | 4      | 1.8%    |
| Maxtor              | 4        | 4      | 1.8%    |
| China               | 4        | 4      | 1.8%    |
| A-DATA Technology   | 4        | 5      | 1.8%    |
| Team                | 3        | 3      | 1.35%   |
| Corsair             | 3        | 3      | 1.35%   |
| PNY                 | 2        | 2      | 0.9%    |
| LDLC                | 2        | 2      | 0.9%    |
| JMicron Technology  | 2        | 2      | 0.9%    |
| Intenso             | 2        | 2      | 0.9%    |
| Intel               | 2        | 2      | 0.9%    |
| Transcend           | 1        | 1      | 0.45%   |
| TO Exter            | 1        | 1      | 0.45%   |
| PNY USB             | 1        | 1      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| ORTIAL              | 1        | 1      | 0.45%   |
| OCZ                 | 1        | 1      | 0.45%   |
| Londisk             | 1        | 1      | 0.45%   |
| Lexar               | 1        | 1      | 0.45%   |
| Leven               | 1        | 2      | 0.45%   |
| KingFast            | 1        | 1      | 0.45%   |
| HGST                | 1        | 1      | 0.45%   |
| Hewlett-Packard     | 1        | 6      | 0.45%   |
| GOODRAM             | 1        | 1      | 0.45%   |
| Fujitsu             | 1        | 1      | 0.45%   |
| External            | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 1.59%   |
| Samsung HD502IJ 500GB               | 3        | 1.2%    |
| Samsung HD103SJ 1TB                 | 3        | 1.2%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.8%    |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.8%    |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.8%    |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.8%    |
| WDC WD2500AAKX-07U6AA1 250GB        | 2        | 0.8%    |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.8%    |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.8%    |
| WDC WD10EACS-00D6B0 1TB             | 2        | 0.8%    |
| Unknown M52516  16GB                | 2        | 0.8%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.8%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.8%    |
| Seagate ST380815AS 80GB             | 2        | 0.8%    |
| Seagate ST3500418AS 500GB           | 2        | 0.8%    |
| Seagate ST3360320AS 360GB           | 2        | 0.8%    |
| Seagate ST3250410AS 250GB           | 2        | 0.8%    |
| Seagate ST3250310AS 250GB           | 2        | 0.8%    |
| Seagate ST31000528AS 1TB            | 2        | 0.8%    |
| Seagate ST3000DM008-2DM166 3TB      | 2        | 0.8%    |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.8%    |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 0.8%    |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 0.8%    |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.8%    |
| Samsung SSD 850 EVO 250GB           | 2        | 0.8%    |
| Samsung HD161HJ 160GB               | 2        | 0.8%    |
| Samsung HD103SI 1TB                 | 2        | 0.8%    |
| Samsung HD080HJ/ 80GB               | 2        | 0.8%    |
| Kingston SA400S37120G 120GB SSD     | 2        | 0.8%    |
| Crucial CT1000BX500SSD1 1TB         | 2        | 0.8%    |
| Corsair Force LS SSD 120GB          | 2        | 0.8%    |
| China SATA SSD 512GB                | 2        | 0.8%    |
| A-DATA SU650 240GB SSD              | 2        | 0.8%    |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.4%    |
| WDC WDS200T2B0A-00SM50 2TB SSD      | 1        | 0.4%    |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 65     | 38.41%  |
| WDC                 | 45       | 71     | 32.61%  |
| Samsung Electronics | 16       | 20     | 11.59%  |
| Hitachi             | 11       | 14     | 7.97%   |
| Toshiba             | 7        | 7      | 5.07%   |
| Maxtor              | 3        | 3      | 2.17%   |
| Unknown             | 1        | 1      | 0.72%   |
| HGST                | 1        | 1      | 0.72%   |
| Fujitsu             | 1        | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 15     | 14.29%  |
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
| Intel               | 1        | 1      | 1.43%   |
| Hewlett-Packard     | 1        | 6      | 1.43%   |
| GOODRAM             | 1        | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 103      | 183    | 56.28%  |
| SSD     | 63       | 96     | 34.43%  |
| NVMe    | 9        | 20     | 4.92%   |
| MMC     | 6        | 7      | 3.28%   |
| Unknown | 2        | 2      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 130      | 272    | 86.09%  |
| SAS  | 8        | 11     | 5.3%    |
| NVMe | 7        | 18     | 4.64%   |
| MMC  | 6        | 7      | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 106      | 165    | 61.99%  |
| 0.51-1.0   | 45       | 82     | 26.32%  |
| 1.01-2.0   | 11       | 15     | 6.43%   |
| 3.01-4.0   | 4        | 12     | 2.34%   |
| 2.01-3.0   | 4        | 4      | 2.34%   |
| 4.01-10.0  | 1        | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 38       | 26.76%  |
| 251-500        | 29       | 20.42%  |
| 501-1000       | 16       | 11.27%  |
| 1001-2000      | 15       | 10.56%  |
| More than 3000 | 14       | 9.86%   |
| 51-100         | 13       | 9.15%   |
| 1-20           | 7        | 4.93%   |
| 2001-3000      | 6        | 4.23%   |
| 21-50          | 3        | 2.11%   |
| Unknown        | 1        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 37.76%  |
| 21-50          | 26       | 18.18%  |
| 101-250        | 15       | 10.49%  |
| 501-1000       | 11       | 7.69%   |
| 51-100         | 10       | 6.99%   |
| 251-500        | 9        | 6.29%   |
| 1001-2000      | 8        | 5.59%   |
| More than 3000 | 5        | 3.5%    |
| 2001-3000      | 4        | 2.8%    |
| Unknown        | 1        | 0.7%    |

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
| Maxtor 6Y080L0 81GB               | 1        | 1      | 3.57%   |
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
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 50%     |

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
| Works    | 68       | 134    | 43.04%  |
| Detected | 66       | 143    | 41.77%  |
| Malfunc  | 22       | 29     | 13.92%  |
| Failed   | 2        | 2      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 82       | 52.23%  |
| AMD                         | 35       | 22.29%  |
| Nvidia                      | 16       | 10.19%  |
| Marvell Technology Group    | 5        | 3.18%   |
| JMicron Technology          | 5        | 3.18%   |
| ASMedia Technology          | 4        | 2.55%   |
| Samsung Electronics         | 3        | 1.91%   |
| VIA Technologies            | 2        | 1.27%   |
| LSI Logic / Symbios Logic   | 2        | 1.27%   |
| Silicon Motion              | 1        | 0.64%   |
| Kingston Technology Company | 1        | 0.64%   |
| ADATA Technology            | 1        | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 10.05%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 4.57%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 3.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.2%    |
| Nvidia MCP61 IDE                                                                        | 6        | 2.74%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.74%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 2.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.28%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 2.28%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.28%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.83%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.37%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.37%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.37%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.37%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.91%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.91%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.91%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.91%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.91%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2        | 0.91%   |
| AMD SB600 IDE                                                                           | 2        | 0.91%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 0.91%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 87       | 53.05%  |
| IDE  | 60       | 36.59%  |
| RAID | 8        | 4.88%   |
| NVMe | 7        | 4.27%   |
| SCSI | 2        | 1.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 90       | 64.29%  |
| AMD    | 50       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.86%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.14%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.14%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3        | 2.14%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.14%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.14%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3        | 2.14%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.43%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.43%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.43%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.43%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.43%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.43%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.43%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 1.43%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.43%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.43%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.71%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.71%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1        | 0.71%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.71%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.71%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.71%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.71%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.71%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.71%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.71%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.71%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.71%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.71%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.71%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.71%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.71%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.71%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.71%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 16.43%  |
| Intel Core 2 Duo        | 12       | 8.57%   |
| Intel Core i3           | 9        | 6.43%   |
| Intel Atom              | 8        | 5.71%   |
| Intel Core i7           | 7        | 5%      |
| Intel Celeron           | 6        | 4.29%   |
| AMD Ryzen 5             | 6        | 4.29%   |
| AMD Athlon II X2        | 6        | 4.29%   |
| AMD Athlon 64 X2        | 6        | 4.29%   |
| Intel Xeon              | 5        | 3.57%   |
| Intel Core 2 Quad       | 5        | 3.57%   |
| Intel Core 2            | 5        | 3.57%   |
| AMD Ryzen 7             | 5        | 3.57%   |
| AMD A10                 | 5        | 3.57%   |
| Intel Pentium Dual-Core | 4        | 2.86%   |
| AMD FX                  | 3        | 2.14%   |
| AMD Athlon 64           | 3        | 2.14%   |
| Intel Pentium Dual      | 2        | 1.43%   |
| Intel Pentium 4         | 2        | 1.43%   |
| AMD Sempron             | 2        | 1.43%   |
| AMD Ryzen Threadripper  | 2        | 1.43%   |
| AMD Ryzen 3             | 2        | 1.43%   |
| AMD GX                  | 2        | 1.43%   |
| Intel Pentium Gold      | 1        | 0.71%   |
| Intel Pentium           | 1        | 0.71%   |
| AMD Quad-Core Opteron   | 1        | 0.71%   |
| AMD Phenom II X4        | 1        | 0.71%   |
| AMD Phenom II X3        | 1        | 0.71%   |
| AMD Opteron             | 1        | 0.71%   |
| AMD E                   | 1        | 0.71%   |
| AMD Athlon X4           | 1        | 0.71%   |
| AMD Athlon II X4        | 1        | 0.71%   |
| AMD A8                  | 1        | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 64       | 45.71%  |
| 4      | 48       | 34.29%  |
| 6      | 9        | 6.43%   |
| 1      | 8        | 5.71%   |
| 8      | 7        | 5%      |
| 64     | 1        | 0.71%   |
| 16     | 1        | 0.71%   |
| 12     | 1        | 0.71%   |
| 3      | 1        | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 138      | 98.57%  |
| 2      | 2        | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 88       | 62.86%  |
| 2      | 52       | 37.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 140      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 15%     |
| 0x206a7    | 12       | 8.57%   |
| 0x306c3    | 10       | 7.14%   |
| 0x1067a    | 10       | 7.14%   |
| 0x306a9    | 6        | 4.29%   |
| 0x06001119 | 6        | 4.29%   |
| 0x906e9    | 4        | 2.86%   |
| 0x6fd      | 4        | 2.86%   |
| 0x6fb      | 4        | 2.86%   |
| 0x406c4    | 4        | 2.86%   |
| 0x010000c8 | 4        | 2.86%   |
| 0x6f6      | 3        | 2.14%   |
| 0x10676    | 3        | 2.14%   |
| 0x08701021 | 3        | 2.14%   |
| 0x0800820d | 3        | 2.14%   |
| 0x06000852 | 3        | 2.14%   |
| 0xa0653    | 2        | 1.43%   |
| 0x6f2      | 2        | 1.43%   |
| 0x506e3    | 2        | 1.43%   |
| 0x30678    | 2        | 1.43%   |
| 0x206d7    | 2        | 1.43%   |
| 0x20655    | 2        | 1.43%   |
| 0x106ca    | 2        | 1.43%   |
| 0x0a50000c | 2        | 1.43%   |
| 0x08701013 | 2        | 1.43%   |
| 0x0700010f | 2        | 1.43%   |
| 0x010000c7 | 2        | 1.43%   |
| 0xf65      | 1        | 0.71%   |
| 0xf4a      | 1        | 0.71%   |
| 0xa0655    | 1        | 0.71%   |
| 0x906ea    | 1        | 0.71%   |
| 0x706a1    | 1        | 0.71%   |
| 0x6f7      | 1        | 0.71%   |
| 0x406c3    | 1        | 0.71%   |
| 0x306f2    | 1        | 0.71%   |
| 0x306e4    | 1        | 0.71%   |
| 0x30661    | 1        | 0.71%   |
| 0x106e5    | 1        | 0.71%   |
| 0x10677    | 1        | 0.71%   |
| 0x0830104d | 1        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 14       | 10%     |
| Penryn        | 14       | 10%     |
| Core          | 14       | 10%     |
| Haswell       | 13       | 9.29%   |
| K8 Hammer     | 11       | 7.86%   |
| K10           | 11       | 7.86%   |
| Piledriver    | 9        | 6.43%   |
| Zen 2         | 7        | 5%      |
| Silvermont    | 7        | 5%      |
| IvyBridge     | 7        | 5%      |
| Zen+          | 6        | 4.29%   |
| KabyLake      | 5        | 3.57%   |
| CometLake     | 4        | 2.86%   |
| Skylake       | 3        | 2.14%   |
| Bonnell       | 3        | 2.14%   |
| Zen 3         | 2        | 1.43%   |
| Westmere      | 2        | 1.43%   |
| NetBurst      | 2        | 1.43%   |
| Jaguar        | 2        | 1.43%   |
| Steamroller   | 1        | 0.71%   |
| Nehalem       | 1        | 0.71%   |
| Goldmont plus | 1        | 0.71%   |
| Bobcat        | 1        | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 54       | 36.99%  |
| Intel  | 49       | 33.56%  |
| AMD    | 43       | 29.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 5.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 3.95%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.29%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5        | 3.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 3.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 2.63%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 2.63%   |
| Intel HD Graphics 530                                                                    | 3        | 1.97%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.32%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 1.32%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.32%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2        | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.32%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.32%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.32%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.32%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.32%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.32%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.32%   |
| AMD Cezanne                                                                              | 2        | 1.32%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.66%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.66%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.66%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.66%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.66%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.66%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.66%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.66%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.66%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.66%   |
| Nvidia GP107GL [Quadro P400]                                                             | 1        | 0.66%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 51       | 36.17%  |
| 1 x Intel    | 46       | 32.62%  |
| 1 x AMD      | 37       | 26.24%  |
| 2 x AMD      | 4        | 2.84%   |
| 2 x Nvidia   | 1        | 0.71%   |
| Intel + AMD  | 1        | 0.71%   |
| AMD + Nvidia | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 79.29%  |
| Proprietary | 27       | 19.29%  |
| Unknown     | 2        | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 37.59%  |
| 0.01-0.5   | 35       | 24.82%  |
| 0.51-1.0   | 23       | 16.31%  |
| 1.01-2.0   | 15       | 10.64%  |
| 3.01-4.0   | 9        | 6.38%   |
| 7.01-8.0   | 3        | 2.13%   |
| 8.01-16.0  | 2        | 1.42%   |
| 2.01-3.0   | 1        | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 20       | 14.49%  |
| Dell                    | 18       | 13.04%  |
| Goldstar                | 15       | 10.87%  |
| Acer                    | 11       | 7.97%   |
| Hewlett-Packard         | 9        | 6.52%   |
| BenQ                    | 6        | 4.35%   |
| Philips                 | 5        | 3.62%   |
| Lenovo                  | 5        | 3.62%   |
| Iiyama                  | 5        | 3.62%   |
| Vizio                   | 4        | 2.9%    |
| Ancor Communications    | 4        | 2.9%    |
| Unknown                 | 3        | 2.17%   |
| AOC                     | 3        | 2.17%   |
| Sony                    | 2        | 1.45%   |
| LG Electronics          | 2        | 1.45%   |
| IOD                     | 2        | 1.45%   |
| FL_                     | 2        | 1.45%   |
| ___                     | 1        | 0.72%   |
| ViewSonic               | 1        | 0.72%   |
| Unknown (ADA)           | 1        | 0.72%   |
| SHD                     | 1        | 0.72%   |
| Sceptre Tech            | 1        | 0.72%   |
| Proview                 | 1        | 0.72%   |
| Plain Tree Systems      | 1        | 0.72%   |
| NEC Computers           | 1        | 0.72%   |
| MOT                     | 1        | 0.72%   |
| Lite-On                 | 1        | 0.72%   |
| LG Display              | 1        | 0.72%   |
| Lenovo Group Limited    | 1        | 0.72%   |
| IBM                     | 1        | 0.72%   |
| Hitachi                 | 1        | 0.72%   |
| HannStar                | 1        | 0.72%   |
| GDH                     | 1        | 0.72%   |
| Fujitsu Siemens         | 1        | 0.72%   |
| Element                 | 1        | 0.72%   |
| CVT                     | 1        | 0.72%   |
| Compaq Computer         | 1        | 0.72%   |
| Chi Mei Optoelectronics | 1        | 0.72%   |
| Arnos Instruments       | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch       | 2        | 1.4%    |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                | 2        | 1.4%    |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                   | 2        | 1.4%    |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                        | 2        | 1.4%    |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                        | 2        | 1.4%    |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                       | 2        | 1.4%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch   | 2        | 1.4%    |
| ___ TV ___9000 1360x768                                                 | 1        | 0.7%    |
| ___ LCDTV16 ___0101 1920x1080                                           | 1        | 0.7%    |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch               | 1        | 0.7%    |
| Vizio VL320M VIZ0050 1920x1080 698x393mm 31.5-inch                      | 1        | 0.7%    |
| Vizio E500AR VIZ0090 1920x1080 477x268mm 21.5-inch                      | 1        | 0.7%    |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                      | 1        | 0.7%    |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch                | 1        | 0.7%    |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                  | 1        | 0.7%    |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                       | 1        | 0.7%    |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                   | 1        | 0.7%    |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                             | 1        | 0.7%    |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                              | 1        | 0.7%    |
| Unknown (ADA) LCD Monitor ADA0004 1024x600 150x100mm 7.1-inch           | 1        | 0.7%    |
| Sony TV SNYAA01 1360x768                                                | 1        | 0.7%    |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                       | 1        | 0.7%    |
| SHD 701Lite SHD02BD 1920x1080 110x62mm 5.0-inch                         | 1        | 0.7%    |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch          | 1        | 0.7%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 0.7%    |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch       | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch     | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x257mm 19.1-inch     | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1        | 0.7%    |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch       | 1        | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.7%    |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch       | 1        | 0.7%    |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch       | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SyncMaster 1024x768                     | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1        | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 30.22%  |
| 1280x1024 (SXGA)   | 25       | 17.99%  |
| 1680x1050 (WSXGA+) | 17       | 12.23%  |
| 1366x768 (WXGA)    | 10       | 7.19%   |
| 1440x900 (WXGA+)   | 9        | 6.47%   |
| 2560x1440 (QHD)    | 8        | 5.76%   |
| 1024x768 (XGA)     | 6        | 4.32%   |
| 3840x2160 (4K)     | 5        | 3.6%    |
| 1600x900 (HD+)     | 3        | 2.16%   |
| 3440x1440          | 2        | 1.44%   |
| 2560x1080          | 2        | 1.44%   |
| 1600x1200          | 2        | 1.44%   |
| 1280x800 (WXGA)    | 2        | 1.44%   |
| 3600x1200          | 1        | 0.72%   |
| 2560x1600          | 1        | 0.72%   |
| 2288x1287          | 1        | 0.72%   |
| 1920x1200 (WUXGA)  | 1        | 0.72%   |
| 1360x768           | 1        | 0.72%   |
| Unknown            | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 18       | 12.95%  |
| 27      | 13       | 9.35%   |
| 19      | 13       | 9.35%   |
| 23      | 11       | 7.91%   |
| 21      | 11       | 7.91%   |
| Unknown | 11       | 7.91%   |
| 24      | 10       | 7.19%   |
| 22      | 10       | 7.19%   |
| 20      | 9        | 6.47%   |
| 15      | 7        | 5.04%   |
| 18      | 6        | 4.32%   |
| 34      | 3        | 2.16%   |
| 41      | 2        | 1.44%   |
| 39      | 2        | 1.44%   |
| 31      | 2        | 1.44%   |
| 84      | 1        | 0.72%   |
| 72      | 1        | 0.72%   |
| 52      | 1        | 0.72%   |
| 48      | 1        | 0.72%   |
| 47      | 1        | 0.72%   |
| 38      | 1        | 0.72%   |
| 29      | 1        | 0.72%   |
| 14      | 1        | 0.72%   |
| 11      | 1        | 0.72%   |
| 7       | 1        | 0.72%   |
| 5       | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 40       | 29.2%   |
| 501-600     | 33       | 24.09%  |
| 301-350     | 24       | 17.52%  |
| Unknown     | 11       | 8.03%   |
| 351-400     | 9        | 6.57%   |
| 601-700     | 4        | 2.92%   |
| 801-900     | 3        | 2.19%   |
| 701-800     | 3        | 2.19%   |
| 1001-1500   | 3        | 2.19%   |
| 1501-2000   | 2        | 1.46%   |
| 101-200     | 2        | 1.46%   |
| 901-1000    | 2        | 1.46%   |
| 201-300     | 1        | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 64       | 48.12%  |
| 5/4     | 23       | 17.29%  |
| 16/10   | 22       | 16.54%  |
| Unknown | 10       | 7.52%   |
| 4/3     | 7        | 5.26%   |
| 21/9    | 4        | 3.01%   |
| 6/5     | 2        | 1.5%    |
| 3/2     | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 27.01%  |
| 151-200        | 25       | 18.25%  |
| 141-150        | 21       | 15.33%  |
| 301-350        | 14       | 10.22%  |
| Unknown        | 11       | 8.03%   |
| 101-110        | 7        | 5.11%   |
| 501-1000       | 6        | 4.38%   |
| 351-500        | 5        | 3.65%   |
| More than 1000 | 4        | 2.92%   |
| 1-40           | 2        | 1.46%   |
| 251-300        | 2        | 1.46%   |
| 81-90          | 1        | 0.73%   |
| 51-60          | 1        | 0.73%   |
| 131-140        | 1        | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 91       | 68.94%  |
| 101-120       | 16       | 12.12%  |
| Unknown       | 11       | 8.33%   |
| 121-160       | 7        | 5.3%    |
| 1-50          | 4        | 3.03%   |
| 161-240       | 2        | 1.52%   |
| More than 240 | 1        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 122      | 87.14%  |
| 2     | 11       | 7.86%   |
| 0     | 5        | 3.57%   |
| 4     | 1        | 0.71%   |
| 3     | 1        | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 82       | 42.05%  |
| Intel                    | 47       | 24.1%   |
| Nvidia                   | 14       | 7.18%   |
| Ralink Technology        | 11       | 5.64%   |
| Qualcomm Atheros         | 11       | 5.64%   |
| Ralink                   | 5        | 2.56%   |
| Broadcom                 | 5        | 2.56%   |
| Marvell Technology Group | 3        | 1.54%   |
| TP-Link                  | 2        | 1.03%   |
| Samsung Electronics      | 2        | 1.03%   |
| Broadcom Limited         | 2        | 1.03%   |
| ZyXEL Communications     | 1        | 0.51%   |
| VIA Technologies         | 1        | 0.51%   |
| U-Blox                   | 1        | 0.51%   |
| Sitecom Europe           | 1        | 0.51%   |
| NetGear                  | 1        | 0.51%   |
| Logitec                  | 1        | 0.51%   |
| Huawei Technologies      | 1        | 0.51%   |
| Belkin Components        | 1        | 0.51%   |
| ASIX Electronics         | 1        | 0.51%   |
| Aquantia                 | 1        | 0.51%   |
| ADMtek                   | 1        | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60       | 28.44%  |
| Nvidia MCP61 Ethernet                                             | 8        | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.9%    |
| Realtek RTL8187 Wireless Adapter                                  | 3        | 1.42%   |
| Ralink RT5572 Wireless Adapter                                    | 3        | 1.42%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.42%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 1.42%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.42%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.95%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.95%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.95%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.95%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.95%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.95%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.95%   |
| Intel Wireless-AC 9260                                            | 2        | 0.95%   |
| Intel Wireless 7260                                               | 2        | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.95%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.95%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.47%   |
| U-Blox GNSS receiver                                              | 1        | 0.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.47%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 24.14%  |
| Ralink Technology     | 11       | 18.97%  |
| Intel                 | 11       | 18.97%  |
| Qualcomm Atheros      | 8        | 13.79%  |
| Ralink                | 5        | 8.62%   |
| TP-Link               | 2        | 3.45%   |
| Broadcom              | 2        | 3.45%   |
| ZyXEL Communications  | 1        | 1.72%   |
| Sitecom Europe        | 1        | 1.72%   |
| NetGear               | 1        | 1.72%   |
| Logitec               | 1        | 1.72%   |
| Belkin Components     | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 8.62%   |
| Realtek RTL8187 Wireless Adapter                               | 3        | 5.17%   |
| Ralink RT5572 Wireless Adapter                                 | 3        | 5.17%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 5.17%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 3        | 5.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 3.45%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 3.45%   |
| Intel Wireless-AC 9260                                         | 2        | 3.45%   |
| Intel Wireless 7260                                            | 2        | 3.45%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 1.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 1.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 1.72%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 1.72%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 1.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 1.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 1.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 1.72%   |
| Ralink RT5372 Wireless Adapter                                 | 1        | 1.72%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 1.72%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 1.72%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 1.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 1.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 1.72%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 1.72%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                      | 1        | 1.72%   |
| Intel Wireless 7265                                            | 1        | 1.72%   |
| Intel Wireless 3165                                            | 1        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 1.72%   |
| Intel Centrino Advanced-N 6235                                 | 1        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 1.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 73       | 50.34%  |
| Intel                    | 38       | 26.21%  |
| Nvidia                   | 14       | 9.66%   |
| Qualcomm Atheros         | 4        | 2.76%   |
| Broadcom                 | 4        | 2.76%   |
| Marvell Technology Group | 3        | 2.07%   |
| Samsung Electronics      | 2        | 1.38%   |
| Broadcom Limited         | 2        | 1.38%   |
| VIA Technologies         | 1        | 0.69%   |
| Huawei Technologies      | 1        | 0.69%   |
| ASIX Electronics         | 1        | 0.69%   |
| Aquantia                 | 1        | 0.69%   |
| ADMtek                   | 1        | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60       | 39.47%  |
| Nvidia MCP61 Ethernet                                             | 8        | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.29%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 3.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.97%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.97%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.32%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.32%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.32%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.66%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.66%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.66%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.66%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.66%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.66%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.66%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.66%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.66%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.66%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.66%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.66%   |
| Huawei YAL-L21                                                    | 1        | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 70.92%  |
| WiFi     | 56       | 28.57%  |
| Modem    | 1        | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 115      | 78.77%  |
| WiFi     | 31       | 21.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 104      | 74.29%  |
| 2     | 31       | 22.14%  |
| 3     | 4        | 2.86%   |
| 0     | 1        | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 113      | 80.14%  |
| Yes  | 28       | 19.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 40%     |
| Cambridge Silicon Radio | 7        | 28%     |
| Broadcom                | 3        | 12%     |
| Ralink                  | 1        | 4%      |
| Logitech                | 1        | 4%      |
| Lite-On Technology      | 1        | 4%      |
| Hewlett-Packard         | 1        | 4%      |
| ASUSTek Computer        | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 28%     |
| Intel Bluetooth wireless interface                  | 4        | 16%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 8%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 8%      |
| Ralink RT3290 Bluetooth                             | 1        | 4%      |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4%      |
| Lite-On Bluetooth Device                            | 1        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4%      |
| Intel AX210 Bluetooth                               | 1        | 4%      |
| Intel AX201 Bluetooth                               | 1        | 4%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 4%      |
| Broadcom Bluetooth Device                           | 1        | 4%      |
| ASUS BCM20702A0                                     | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 81       | 40.5%   |
| Nvidia                   | 51       | 25.5%   |
| AMD                      | 50       | 25%     |
| Creative Labs            | 4        | 2%      |
| C-Media Electronics      | 4        | 2%      |
| XMOS                     | 2        | 1%      |
| VIA Technologies         | 1        | 0.5%    |
| Unknown                  | 1        | 0.5%    |
| Logitech                 | 1        | 0.5%    |
| GN Netcom                | 1        | 0.5%    |
| Focusrite-Novation       | 1        | 0.5%    |
| Creative Technology      | 1        | 0.5%    |
| ASUSTek Computer         | 1        | 0.5%    |
| Asahi Kasei Microsystems | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12       | 5.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 11       | 4.82%   |
| Nvidia High Definition Audio Controller                                           | 10       | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 3.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 9        | 3.95%   |
| AMD FCH Azalia Controller                                                         | 9        | 3.95%   |
| Nvidia MCP61 High Definition Audio                                                | 8        | 3.51%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 3.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 3.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 2.63%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 2.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5        | 2.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 1.75%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.75%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.75%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 1.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 1.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.32%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 1.32%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.32%   |
| XMOS HIFI DSD                                                                     | 2        | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.88%   |
| Nvidia CK804 AC'97 Audio Controller                                               | 2        | 0.88%   |
| Intel Audio device                                                                | 2        | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 0.88%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.88%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 2        | 0.88%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                | 1        | 0.44%   |

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


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                   | 4        | 3.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 2        | 1.82%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 2        | 1.82%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s             | 2        | 1.82%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s              | 2        | 1.82%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                    | 1        | 0.91%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                          | 1        | 0.91%   |
| Unknown RAM Module 512MB DIMM 400MT/s                           | 1        | 0.91%   |
| Unknown RAM Module 512MB DIMM 333MT/s                           | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM SDRAM                            | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                    | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1        | 0.91%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 1        | 0.91%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 0.91%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 1        | 0.91%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                   | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM DDR2                             | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                      | 1        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 1        | 0.91%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s               | 1        | 0.91%   |
| Timetec RAM UD3-1600 8192MB DIMM DDR3 1600MT/s                  | 1        | 0.91%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                   | 1        | 0.91%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2667MT/s          | 1        | 0.91%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                   | 1        | 0.91%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1        | 0.91%   |
| SK hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s          | 1        | 0.91%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s           | 1        | 0.91%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1        | 0.91%   |
| SK hynix RAM HMT451R7AFR8C-RD 4096MB DIMM DDR3 1866MT/s         | 1        | 0.91%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s            | 1        | 0.91%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s         | 1        | 0.91%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s            | 1        | 0.91%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1        | 0.91%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s         | 1        | 0.91%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s            | 1        | 0.91%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s           | 1        | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1        | 0.91%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1        | 0.91%   |

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
| Sunplus PAPALOOK_229AF                    | 1        | 5.56%   |
| SJ-180517-N 1080P Webcam                  | 1        | 5.56%   |
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
| 0     | 116      | 82.86%  |
| 1     | 21       | 15%     |
| 2     | 3        | 2.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 25%     |
| Net/wireless             | 4        | 16.67%  |
| Communication controller | 4        | 16.67%  |
| Sound                    | 3        | 12.5%   |
| Unassigned class         | 2        | 8.33%   |
| Dvb card                 | 2        | 8.33%   |
| Net/ethernet             | 1        | 4.17%   |
| Multimedia controller    | 1        | 4.17%   |
| Bluetooth                | 1        | 4.17%   |

