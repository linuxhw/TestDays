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

Total: 200

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 21B4 A01                    | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| Unknown       | Phitronics N68C-M           | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Gigabyte      | B450M S2H                   | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Gigabyte      | B450M S2H                   | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| Lenovo        | 0B98401 PRO                 | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| HP            | 3048h                       | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | M2NPV-VM                    | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| AMI           | Cherry Trail CR             | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| Intel         | D33217GKE G76540-203        | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| AOpen         | D1007 0BBA                  | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
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


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.4.0-52-generic   | 8        | 4.97%   |
| 5.4.0-42-generic   | 8        | 4.97%   |
| 5.11.0-27-generic  | 7        | 4.35%   |
| 5.8.0-50-generic   | 6        | 3.73%   |
| 5.4.0-54-generic   | 5        | 3.11%   |
| 5.13.0-28-generic  | 5        | 3.11%   |
| 5.4.0-67-generic   | 4        | 2.48%   |
| 5.4.0-40-generic   | 4        | 2.48%   |
| 5.4.0-29-generic   | 4        | 2.48%   |
| 5.4.0-122-generic  | 4        | 2.48%   |
| 5.4.0-77-generic   | 3        | 1.86%   |
| 5.4.0-73-generic   | 3        | 1.86%   |
| 5.4.0-48-generic   | 3        | 1.86%   |
| 5.4.0-47-generic   | 3        | 1.86%   |
| 5.4.0-37-generic   | 3        | 1.86%   |
| 5.4.0-33-generic   | 3        | 1.86%   |
| 5.4.0-26-generic   | 3        | 1.86%   |
| 5.8.0-63-generic   | 2        | 1.24%   |
| 5.8.0-59-generic   | 2        | 1.24%   |
| 5.8.0-53-generic   | 2        | 1.24%   |
| 5.8.0-45-generic   | 2        | 1.24%   |
| 5.8.0-41-generic   | 2        | 1.24%   |
| 5.4.0-96-generic   | 2        | 1.24%   |
| 5.4.0-91-generic   | 2        | 1.24%   |
| 5.4.0-90-generic   | 2        | 1.24%   |
| 5.4.0-72-generic   | 2        | 1.24%   |
| 5.4.0-66-generic   | 2        | 1.24%   |
| 5.4.0-60-generic   | 2        | 1.24%   |
| 5.4.0-131-generic  | 2        | 1.24%   |
| 5.4.0-109-generic  | 2        | 1.24%   |
| 5.15.0-60-generic  | 2        | 1.24%   |
| 5.15.0-53-generic  | 2        | 1.24%   |
| 5.13.0-27-generic  | 2        | 1.24%   |
| 5.11.0-43-generic  | 2        | 1.24%   |
| 5.11.0-38-generic  | 2        | 1.24%   |
| 5.11.0-34-generic  | 2        | 1.24%   |
| 5.8.0-7630-generic | 1        | 0.62%   |
| 5.8.0-55-generic   | 1        | 0.62%   |
| 5.8.0-48-generic   | 1        | 0.62%   |
| 5.8.0-43-generic   | 1        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 86       | 56.21%  |
| 5.8.0   | 21       | 13.73%  |
| 5.11.0  | 18       | 11.76%  |
| 5.13.0  | 13       | 8.5%    |
| 5.15.0  | 9        | 5.88%   |
| 5.6.15  | 1        | 0.65%   |
| 5.6.0   | 1        | 0.65%   |
| 5.4.30  | 1        | 0.65%   |
| 5.3.18  | 1        | 0.65%   |
| 5.16.5  | 1        | 0.65%   |
| 5.14.0  | 1        | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 87       | 56.86%  |
| 5.8     | 21       | 13.73%  |
| 5.11    | 18       | 11.76%  |
| 5.13    | 13       | 8.5%    |
| 5.15    | 9        | 5.88%   |
| 5.6     | 2        | 1.31%   |
| 5.3     | 1        | 0.65%   |
| 5.16    | 1        | 0.65%   |
| 5.14    | 1        | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 151      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 140      | 92.72%  |
| LXDE       | 5        | 3.31%   |
| GNOME      | 3        | 1.99%   |
| XFCE       | 1        | 0.66%   |
| X-Cinnamon | 1        | 0.66%   |
| i3         | 1        | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 142      | 94.04%  |
| Tty     | 7        | 4.64%   |
| Wayland | 1        | 0.66%   |
| Unknown | 1        | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 83       | 53.55%  |
| Unknown | 43       | 27.74%  |
| LightDM | 11       | 7.1%    |
| GDM     | 10       | 6.45%   |
| TDM     | 6        | 3.87%   |
| LXDM    | 1        | 0.65%   |
| GDM3    | 1        | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 39       | 25.83%  |
| fr_FR   | 24       | 15.89%  |
| de_DE   | 14       | 9.27%   |
| pt_BR   | 12       | 7.95%   |
| it_IT   | 10       | 6.62%   |
| C       | 7        | 4.64%   |
| ru_RU   | 5        | 3.31%   |
| ja_JP   | 4        | 2.65%   |
| en_GB   | 4        | 2.65%   |
| en_AU   | 4        | 2.65%   |
| fi_FI   | 3        | 1.99%   |
| es_ES   | 3        | 1.99%   |
| hu_HU   | 2        | 1.32%   |
| en_ZA   | 2        | 1.32%   |
| en_CA   | 2        | 1.32%   |
| de_CH   | 2        | 1.32%   |
| cs_CZ   | 2        | 1.32%   |
| Unknown | 2        | 1.32%   |
| sv_SE   | 1        | 0.66%   |
| nl_NL   | 1        | 0.66%   |
| fr_CA   | 1        | 0.66%   |
| es_PE   | 1        | 0.66%   |
| es_MX   | 1        | 0.66%   |
| es_CR   | 1        | 0.66%   |
| es_CO   | 1        | 0.66%   |
| en_SG   | 1        | 0.66%   |
| en_NZ   | 1        | 0.66%   |
| el_GR   | 1        | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 101      | 66.89%  |
| EFI  | 50       | 33.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 139      | 92.05%  |
| Overlay | 7        | 4.64%   |
| Xfs     | 2        | 1.32%   |
| Zfs     | 1        | 0.66%   |
| F2fs    | 1        | 0.66%   |
| Btrfs   | 1        | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 37.25%  |
| MBR     | 51       | 33.33%  |
| GPT     | 45       | 29.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 80.79%  |
| Yes       | 29       | 19.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 69.74%  |
| Yes       | 46       | 30.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 16.56%  |
| Hewlett-Packard     | 18       | 11.92%  |
| MSI                 | 16       | 10.6%   |
| Gigabyte Technology | 15       | 9.93%   |
| ASRock              | 15       | 9.93%   |
| Dell                | 14       | 9.27%   |
| Lenovo              | 9        | 5.96%   |
| Intel               | 9        | 5.96%   |
| Pegatron            | 5        | 3.31%   |
| Acer                | 4        | 2.65%   |
| AAEON               | 3        | 1.99%   |
| Positivo            | 2        | 1.32%   |
| Foxconn             | 2        | 1.32%   |
| Biostar             | 2        | 1.32%   |
| AMI                 | 2        | 1.32%   |
| Unknown             | 2        | 1.32%   |
| ZOTAC               | 1        | 0.66%   |
| Packard Bell        | 1        | 0.66%   |
| IBM                 | 1        | 0.66%   |
| Huanan              | 1        | 0.66%   |
| Hardkernel          | 1        | 0.66%   |
| Fujitsu Siemens     | 1        | 0.66%   |
| Fujitsu             | 1        | 0.66%   |
| AOpen               | 1        | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| AAEON MF-001                         | 3        | 1.99%   |
| MSI MS-7C37                          | 2        | 1.32%   |
| MSI MS-7B89                          | 2        | 1.32%   |
| HP t620 Quad Core TC                 | 2        | 1.32%   |
| HP Compaq 6000 Pro SFF PC            | 2        | 1.32%   |
| Dell OptiPlex 790                    | 2        | 1.32%   |
| ASUS M5A97 R2.0                      | 2        | 1.32%   |
| ASRock N68-VS3 UCC                   | 2        | 1.32%   |
| ASRock FM2A85X Extreme6              | 2        | 1.32%   |
| Unknown                              | 2        | 1.32%   |
| ZOTAC NM10                           | 1        | 0.66%   |
| Positivo POS-MI945AA                 | 1        | 0.66%   |
| Positivo POS-EIH61CE                 | 1        | 0.66%   |
| Pegatron WE216AA-ABF CQ5335FR        | 1        | 0.66%   |
| Pegatron NC689AA-ABA s3700y          | 1        | 0.66%   |
| Pegatron FL308AA-ABD IQ512de         | 1        | 0.66%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.66%   |
| Pegatron AY652AA-ABA s5310y          | 1        | 0.66%   |
| Packard Bell IMEDIA S1350            | 1        | 0.66%   |
| MSI MS-7D16                          | 1        | 0.66%   |
| MSI MS-7B86                          | 1        | 0.66%   |
| MSI MS-7B09                          | 1        | 0.66%   |
| MSI MS-7994                          | 1        | 0.66%   |
| MSI MS-7846                          | 1        | 0.66%   |
| MSI MS-7721                          | 1        | 0.66%   |
| MSI MS-7680                          | 1        | 0.66%   |
| MSI MS-7640                          | 1        | 0.66%   |
| MSI MS-7592                          | 1        | 0.66%   |
| MSI MS-7309                          | 1        | 0.66%   |
| MSI ER883AA-ABA M7470N               | 1        | 0.66%   |
| MSI Compaq dx2200 MT                 | 1        | 0.66%   |
| Lenovo ThinkStation P620 30E0CTO1WW  | 1        | 0.66%   |
| Lenovo ThinkCentre M93z 10AD002DMZ   | 1        | 0.66%   |
| Lenovo ThinkCentre M73 10AXS0HN00    | 1        | 0.66%   |
| Lenovo ThinkCentre M58p 7220W21      | 1        | 0.66%   |
| Lenovo ThinkCentre M58p 6136A66      | 1        | 0.66%   |
| Lenovo ThinkCentre M55p 8811VQV      | 1        | 0.66%   |
| Lenovo ThinkCentre E73 10AU003JFR    | 1        | 0.66%   |
| Lenovo H50-50 90B60081IX             | 1        | 0.66%   |
| Lenovo H50-30g 90AS0002BR            | 1        | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 9        | 5.96%   |
| Lenovo ThinkCentre   | 6        | 3.97%   |
| Dell OptiPlex        | 6        | 3.97%   |
| Acer Aspire          | 4        | 2.65%   |
| HP t620              | 3        | 1.99%   |
| AAEON MF-001         | 3        | 1.99%   |
| MSI MS-7C37          | 2        | 1.32%   |
| MSI MS-7B89          | 2        | 1.32%   |
| Gigabyte B450M       | 2        | 1.32%   |
| Dell Inspiron        | 2        | 1.32%   |
| ASUS M5A97           | 2        | 1.32%   |
| ASRock N68-VS3       | 2        | 1.32%   |
| ASRock FM2A85X       | 2        | 1.32%   |
| Unknown              | 2        | 1.32%   |
| ZOTAC NM10           | 1        | 0.66%   |
| Positivo POS-MI945AA | 1        | 0.66%   |
| Positivo POS-EIH61CE | 1        | 0.66%   |
| Pegatron WE216AA-ABF | 1        | 0.66%   |
| Pegatron NC689AA-ABA | 1        | 0.66%   |
| Pegatron FL308AA-ABD | 1        | 0.66%   |
| Pegatron Compaq      | 1        | 0.66%   |
| Pegatron AY652AA-ABA | 1        | 0.66%   |
| Packard Bell IMEDIA  | 1        | 0.66%   |
| MSI MS-7D16          | 1        | 0.66%   |
| MSI MS-7B86          | 1        | 0.66%   |
| MSI MS-7B09          | 1        | 0.66%   |
| MSI MS-7994          | 1        | 0.66%   |
| MSI MS-7846          | 1        | 0.66%   |
| MSI MS-7721          | 1        | 0.66%   |
| MSI MS-7680          | 1        | 0.66%   |
| MSI MS-7640          | 1        | 0.66%   |
| MSI MS-7592          | 1        | 0.66%   |
| MSI MS-7309          | 1        | 0.66%   |
| MSI ER883AA-ABA      | 1        | 0.66%   |
| MSI Compaq           | 1        | 0.66%   |
| Lenovo ThinkStation  | 1        | 0.66%   |
| Lenovo H50-50        | 1        | 0.66%   |
| Lenovo H50-30g       | 1        | 0.66%   |
| Intel X79            | 1        | 0.66%   |
| Intel STK1AW32SC     | 1        | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 14       | 9.27%   |
| 2009 | 13       | 8.61%   |
| 2013 | 12       | 7.95%   |
| 2011 | 12       | 7.95%   |
| 2010 | 11       | 7.28%   |
| 2008 | 11       | 7.28%   |
| 2007 | 11       | 7.28%   |
| 2017 | 10       | 6.62%   |
| 2014 | 10       | 6.62%   |
| 2006 | 9        | 5.96%   |
| 2019 | 8        | 5.3%    |
| 2015 | 7        | 4.64%   |
| 2020 | 6        | 3.97%   |
| 2021 | 5        | 3.31%   |
| 2018 | 4        | 2.65%   |
| 2005 | 4        | 2.65%   |
| 2016 | 3        | 1.99%   |
| 2004 | 1        | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 151      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 147      | 97.35%  |
| Enabled  | 4        | 2.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 42       | 27.45%  |
| 1.01-2.0        | 23       | 15.03%  |
| 8.01-16.0       | 23       | 15.03%  |
| 4.01-8.0        | 21       | 13.73%  |
| 16.01-24.0      | 20       | 13.07%  |
| 32.01-64.0      | 11       | 7.19%   |
| 24.01-32.0      | 4        | 2.61%   |
| 2.01-3.0        | 3        | 1.96%   |
| 64.01-256.0     | 3        | 1.96%   |
| 0.51-1.0        | 2        | 1.31%   |
| More than 256.0 | 1        | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 74       | 47.13%  |
| 2.01-3.0   | 27       | 17.2%   |
| 0.51-1.0   | 24       | 15.29%  |
| 4.01-8.0   | 16       | 10.19%  |
| 3.01-4.0   | 8        | 5.1%    |
| 8.01-16.0  | 3        | 1.91%   |
| 0.01-0.5   | 3        | 1.91%   |
| 32.01-64.0 | 1        | 0.64%   |
| 16.01-24.0 | 1        | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 51.97%  |
| 2      | 43       | 28.29%  |
| 4      | 11       | 7.24%   |
| 3      | 8        | 5.26%   |
| 5      | 5        | 3.29%   |
| 6      | 2        | 1.32%   |
| 17     | 1        | 0.66%   |
| 14     | 1        | 0.66%   |
| 7      | 1        | 0.66%   |
| 0      | 1        | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 62.34%  |
| No        | 58       | 37.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 150      | 99.34%  |
| No        | 1        | 0.66%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 58.28%  |
| Yes       | 63       | 41.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 82.12%  |
| Yes       | 27       | 17.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 24       | 15.69%  |
| France       | 24       | 15.69%  |
| Germany      | 16       | 10.46%  |
| Brazil       | 13       | 8.5%    |
| Italy        | 10       | 6.54%   |
| Switzerland  | 6        | 3.92%   |
| Russia       | 5        | 3.27%   |
| Hungary      | 5        | 3.27%   |
| Spain        | 4        | 2.61%   |
| Japan        | 4        | 2.61%   |
| Finland      | 4        | 2.61%   |
| Australia    | 4        | 2.61%   |
| Netherlands  | 3        | 1.96%   |
| Czechia      | 3        | 1.96%   |
| Canada       | 3        | 1.96%   |
| South Africa | 2        | 1.31%   |
| Puerto Rico  | 2        | 1.31%   |
| New Zealand  | 2        | 1.31%   |
| Mexico       | 2        | 1.31%   |
| Greece       | 2        | 1.31%   |
| Belgium      | 2        | 1.31%   |
| UK           | 1        | 0.65%   |
| Sweden       | 1        | 0.65%   |
| Slovenia     | 1        | 0.65%   |
| Slovakia     | 1        | 0.65%   |
| Singapore    | 1        | 0.65%   |
| Romania      | 1        | 0.65%   |
| Peru         | 1        | 0.65%   |
| Martinique   | 1        | 0.65%   |
| Malaysia     | 1        | 0.65%   |
| Ireland      | 1        | 0.65%   |
| Costa Rica   | 1        | 0.65%   |
| Colombia     | 1        | 0.65%   |
| Belarus      | 1        | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Wellington         | 3        | 1.91%   |
| Melbourne          | 3        | 1.91%   |
| Zurich             | 2        | 1.27%   |
| Sao Paulo          | 2        | 1.27%   |
| Rome               | 2        | 1.27%   |
| Raahe              | 2        | 1.27%   |
| Pécs              | 2        | 1.27%   |
| Figeac             | 2        | 1.27%   |
| Cuernavaca         | 2        | 1.27%   |
| Cayey              | 2        | 1.27%   |
| Bern               | 2        | 1.27%   |
| Zwevegem           | 1        | 0.64%   |
| Zeuthen            | 1        | 0.64%   |
| Wraysbury          | 1        | 0.64%   |
| Winsen             | 1        | 0.64%   |
| Wiesbaden          | 1        | 0.64%   |
| West Chester       | 1        | 0.64%   |
| Waren              | 1        | 0.64%   |
| Vinhedo            | 1        | 0.64%   |
| Vilyuchinsk        | 1        | 0.64%   |
| Villejuif          | 1        | 0.64%   |
| Vilabella          | 1        | 0.64%   |
| Vaxjo              | 1        | 0.64%   |
| Vannes             | 1        | 0.64%   |
| Vanderbijlpark     | 1        | 0.64%   |
| Valencia           | 1        | 0.64%   |
| Turku              | 1        | 0.64%   |
| Trebur             | 1        | 0.64%   |
| Toulouse           | 1        | 0.64%   |
| Toronto            | 1        | 0.64%   |
| Tokorozawa         | 1        | 0.64%   |
| Stockton           | 1        | 0.64%   |
| Stedesand          | 1        | 0.64%   |
| Spokane            | 1        | 0.64%   |
| Sora               | 1        | 0.64%   |
| Schiedam           | 1        | 0.64%   |
| Sautron            | 1        | 0.64%   |
| Sandorfalva        | 1        | 0.64%   |
| Salzgitter         | 1        | 0.64%   |
| Saint-Pair-sur-Mer | 1        | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 59       | 71     | 25.11%  |
| WDC                 | 51       | 81     | 21.7%   |
| Samsung Electronics | 29       | 51     | 12.34%  |
| Hitachi             | 11       | 14     | 4.68%   |
| Kingston            | 10       | 10     | 4.26%   |
| Toshiba             | 9        | 10     | 3.83%   |
| Unknown             | 8        | 9      | 3.4%    |
| Crucial             | 8        | 21     | 3.4%    |
| SanDisk             | 5        | 5      | 2.13%   |
| Maxtor              | 4        | 4      | 1.7%    |
| China               | 4        | 4      | 1.7%    |
| A-DATA Technology   | 4        | 5      | 1.7%    |
| Team                | 3        | 3      | 1.28%   |
| Corsair             | 3        | 3      | 1.28%   |
| PNY                 | 2        | 2      | 0.85%   |
| LDLC                | 2        | 2      | 0.85%   |
| JMicron Technology  | 2        | 2      | 0.85%   |
| Intenso             | 2        | 2      | 0.85%   |
| Intel               | 2        | 2      | 0.85%   |
| Hewlett-Packard     | 2        | 7      | 0.85%   |
| Transcend           | 1        | 1      | 0.43%   |
| TO Exter            | 1        | 1      | 0.43%   |
| PNY USB             | 1        | 1      | 0.43%   |
| Patriot             | 1        | 1      | 0.43%   |
| ORTIAL              | 1        | 1      | 0.43%   |
| OCZ                 | 1        | 1      | 0.43%   |
| Londisk             | 1        | 1      | 0.43%   |
| Lexar               | 1        | 1      | 0.43%   |
| Leven               | 1        | 2      | 0.43%   |
| KingFast            | 1        | 1      | 0.43%   |
| HGST                | 1        | 1      | 0.43%   |
| GOODRAM             | 1        | 1      | 0.43%   |
| Fujitsu             | 1        | 1      | 0.43%   |
| External            | 1        | 1      | 0.43%   |
| Unknown             | 1        | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 1.52%   |
| Seagate ST3250310AS 250GB           | 3        | 1.14%   |
| Samsung HD502IJ 500GB               | 3        | 1.14%   |
| Samsung HD103SJ 1TB                 | 3        | 1.14%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.76%   |
| WDC WDS120G2G0A-00JH30 128GB SSD    | 2        | 0.76%   |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.76%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.76%   |
| WDC WD2500AAKX-07U6AA1 250GB        | 2        | 0.76%   |
| WDC WD2500AAJS-75M0A0 249GB         | 2        | 0.76%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.76%   |
| WDC WD10EACS-00D6B0 1TB             | 2        | 0.76%   |
| Unknown M52516  16GB                | 2        | 0.76%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.76%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 0.76%   |
| Seagate ST380815AS 80GB             | 2        | 0.76%   |
| Seagate ST3500418AS 500GB           | 2        | 0.76%   |
| Seagate ST3360320AS 360GB           | 2        | 0.76%   |
| Seagate ST3250410AS 250GB           | 2        | 0.76%   |
| Seagate ST31000528AS 1TB            | 2        | 0.76%   |
| Seagate ST3000DM008-2DM166 3TB      | 2        | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.76%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.76%   |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 0.76%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.76%   |
| Samsung SSD 850 EVO 250GB           | 2        | 0.76%   |
| Samsung HD161HJ 160GB               | 2        | 0.76%   |
| Samsung HD103SI 1TB                 | 2        | 0.76%   |
| Samsung HD080HJ/ 80GB               | 2        | 0.76%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 0.76%   |
| Crucial CT1000BX500SSD1 1TB         | 2        | 0.76%   |
| Corsair Force LS SSD 120GB          | 2        | 0.76%   |
| China SATA SSD 512GB                | 2        | 0.76%   |
| A-DATA SU650 240GB SSD              | 2        | 0.76%   |
| WDC WDS250G2B0B-00YS70 250GB SSD    | 1        | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 59       | 71     | 40.69%  |
| WDC                 | 45       | 71     | 31.03%  |
| Samsung Electronics | 16       | 20     | 11.03%  |
| Hitachi             | 11       | 14     | 7.59%   |
| Toshiba             | 7        | 8      | 4.83%   |
| Maxtor              | 3        | 3      | 2.07%   |
| Unknown             | 1        | 1      | 0.69%   |
| HGST                | 1        | 1      | 0.69%   |
| Hewlett-Packard     | 1        | 1      | 0.69%   |
| Fujitsu             | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 17     | 14.67%  |
| Kingston            | 9        | 9      | 12%     |
| WDC                 | 8        | 10     | 10.67%  |
| Crucial             | 8        | 21     | 10.67%  |
| SanDisk             | 5        | 5      | 6.67%   |
| China               | 4        | 4      | 5.33%   |
| Team                | 3        | 3      | 4%      |
| Corsair             | 3        | 3      | 4%      |
| A-DATA Technology   | 3        | 4      | 4%      |
| Toshiba             | 2        | 2      | 2.67%   |
| PNY                 | 2        | 2      | 2.67%   |
| Intenso             | 2        | 2      | 2.67%   |
| Transcend           | 1        | 1      | 1.33%   |
| TO Exter            | 1        | 1      | 1.33%   |
| PNY USB             | 1        | 1      | 1.33%   |
| Patriot             | 1        | 1      | 1.33%   |
| ORTIAL              | 1        | 1      | 1.33%   |
| OCZ                 | 1        | 1      | 1.33%   |
| Maxtor              | 1        | 1      | 1.33%   |
| Londisk             | 1        | 1      | 1.33%   |
| Lexar               | 1        | 1      | 1.33%   |
| Leven               | 1        | 2      | 1.33%   |
| LDLC                | 1        | 1      | 1.33%   |
| Intel               | 1        | 1      | 1.33%   |
| Hewlett-Packard     | 1        | 6      | 1.33%   |
| GOODRAM             | 1        | 1      | 1.33%   |
| External            | 1        | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 110      | 191    | 56.7%   |
| SSD     | 67       | 103    | 34.54%  |
| NVMe    | 8        | 19     | 4.12%   |
| MMC     | 7        | 9      | 3.61%   |
| Unknown | 2        | 2      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 140      | 286    | 86.42%  |
| SAS  | 8        | 11     | 4.94%   |
| NVMe | 7        | 18     | 4.32%   |
| MMC  | 7        | 9      | 4.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 112      | 172    | 61.54%  |
| 0.51-1.0   | 50       | 90     | 27.47%  |
| 1.01-2.0   | 11       | 15     | 6.04%   |
| 3.01-4.0   | 4        | 12     | 2.2%    |
| 2.01-3.0   | 4        | 4      | 2.2%    |
| 4.01-10.0  | 1        | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 26.45%  |
| 251-500        | 33       | 21.29%  |
| 501-1000       | 18       | 11.61%  |
| 1001-2000      | 17       | 10.97%  |
| More than 3000 | 14       | 9.03%   |
| 51-100         | 14       | 9.03%   |
| 1-20           | 7        | 4.52%   |
| 2001-3000      | 6        | 3.87%   |
| 21-50          | 3        | 1.94%   |
| Unknown        | 2        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 59       | 37.82%  |
| 21-50          | 27       | 17.31%  |
| 101-250        | 16       | 10.26%  |
| 501-1000       | 12       | 7.69%   |
| 251-500        | 11       | 7.05%   |
| 51-100         | 11       | 7.05%   |
| 1001-2000      | 9        | 5.77%   |
| More than 3000 | 5        | 3.21%   |
| 2001-3000      | 4        | 2.56%   |
| Unknown        | 2        | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB    | 2        | 2      | 6.45%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 1      | 3.23%   |
| WDC WD400EB-00CPF0 40GB           | 1        | 1      | 3.23%   |
| WDC WD2500AAJS-75M0A0 249GB       | 1        | 1      | 3.23%   |
| WDC WD1600AAJS-60B4A0 160GB       | 1        | 2      | 3.23%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 1      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 3.23%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 3.23%   |
| Seagate ST360012A 64GB            | 1        | 1      | 3.23%   |
| Seagate ST3360320AS 360GB         | 1        | 1      | 3.23%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 3.23%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 3.23%   |
| Seagate ST3160812AS 160GB         | 1        | 1      | 3.23%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 3.23%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 1      | 3.23%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 3.23%   |
| Seagate ST1000DX001-1CM162 1TB    | 1        | 1      | 3.23%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 3.23%   |
| SanDisk SSD PLUS 120GB            | 1        | 1      | 3.23%   |
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 3.23%   |
| Maxtor STM3300622A 304GB          | 1        | 1      | 3.23%   |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 3.23%   |
| Maxtor 6B200M0 200GB              | 1        | 1      | 3.23%   |
| LDLC SSD 120GB                    | 1        | 1      | 3.23%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 3.23%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 3.23%   |
| Hitachi HDS721075CLA332 752GB     | 1        | 1      | 3.23%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 3.23%   |
| Hitachi HCP725050GLAT80 500GB     | 1        | 1      | 3.23%   |
| Fujitsu MHZ2160BH G2 160GB        | 1        | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 14     | 46.67%  |
| WDC                 | 5        | 6      | 16.67%  |
| Maxtor              | 3        | 3      | 10%     |
| Kingston            | 2        | 2      | 6.67%   |
| Hitachi             | 2        | 3      | 6.67%   |
| SanDisk             | 1        | 1      | 3.33%   |
| Samsung Electronics | 1        | 1      | 3.33%   |
| LDLC                | 1        | 1      | 3.33%   |
| Fujitsu             | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 14     | 53.85%  |
| WDC                 | 5        | 6      | 19.23%  |
| Maxtor              | 3        | 3      | 11.54%  |
| Hitachi             | 2        | 3      | 7.69%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| Fujitsu             | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 28     | 85.19%  |
| SSD  | 4        | 4      | 14.81%  |

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
| Works    | 72       | 139    | 42.6%   |
| Detected | 70       | 151    | 41.42%  |
| Malfunc  | 25       | 32     | 14.79%  |
| Failed   | 2        | 2      | 1.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 88       | 52.69%  |
| AMD                         | 37       | 22.16%  |
| Nvidia                      | 18       | 10.78%  |
| Marvell Technology Group    | 5        | 2.99%   |
| JMicron Technology          | 5        | 2.99%   |
| ASMedia Technology          | 4        | 2.4%    |
| Samsung Electronics         | 3        | 1.8%    |
| VIA Technologies            | 2        | 1.2%    |
| LSI Logic / Symbios Logic   | 2        | 1.2%    |
| Silicon Motion              | 1        | 0.6%    |
| Kingston Technology Company | 1        | 0.6%    |
| ADATA Technology            | 1        | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23       | 9.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 4.7%    |
| Nvidia MCP61 SATA Controller                                                            | 9        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 3.85%   |
| Nvidia MCP61 IDE                                                                        | 7        | 2.99%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 2.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.99%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.56%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 2.56%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6        | 2.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.14%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.71%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.28%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.28%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.28%   |
| AMD FCH IDE Controller                                                                  | 3        | 1.28%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.85%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 0.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.85%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.85%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.85%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.85%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2        | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 92       | 52.57%  |
| IDE  | 65       | 37.14%  |
| RAID | 9        | 5.14%   |
| NVMe | 7        | 4%      |
| SCSI | 2        | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 64.24%  |
| AMD    | 54       | 35.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 3.31%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 4        | 2.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.99%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.99%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.99%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.99%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3        | 1.99%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.32%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.32%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.32%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.32%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.32%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.32%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 2        | 1.32%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.32%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.32%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 1.32%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.32%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.32%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.66%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.66%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1        | 0.66%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.66%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.66%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.66%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.66%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.66%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.66%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.66%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.66%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.66%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.66%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.66%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.66%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.66%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 15.23%  |
| Intel Core 2 Duo        | 14       | 9.27%   |
| Intel Core i3           | 11       | 7.28%   |
| Intel Atom              | 9        | 5.96%   |
| Intel Core i7           | 7        | 4.64%   |
| AMD Athlon 64 X2        | 7        | 4.64%   |
| Intel Celeron           | 6        | 3.97%   |
| AMD Ryzen 5             | 6        | 3.97%   |
| AMD Athlon II X2        | 6        | 3.97%   |
| Intel Xeon              | 5        | 3.31%   |
| Intel Pentium Dual-Core | 5        | 3.31%   |
| Intel Core 2 Quad       | 5        | 3.31%   |
| Intel Core 2            | 5        | 3.31%   |
| AMD Ryzen 7             | 5        | 3.31%   |
| AMD A10                 | 5        | 3.31%   |
| AMD GX                  | 3        | 1.99%   |
| AMD FX                  | 3        | 1.99%   |
| AMD Athlon 64           | 3        | 1.99%   |
| Intel Pentium Dual      | 2        | 1.32%   |
| Intel Pentium 4         | 2        | 1.32%   |
| Intel Pentium           | 2        | 1.32%   |
| AMD Sempron             | 2        | 1.32%   |
| AMD Ryzen Threadripper  | 2        | 1.32%   |
| AMD Ryzen 3             | 2        | 1.32%   |
| AMD A8                  | 2        | 1.32%   |
| Intel Pentium Gold      | 1        | 0.66%   |
| AMD Quad-Core Opteron   | 1        | 0.66%   |
| AMD Phenom II X6        | 1        | 0.66%   |
| AMD Phenom II X4        | 1        | 0.66%   |
| AMD Phenom II X3        | 1        | 0.66%   |
| AMD Opteron             | 1        | 0.66%   |
| AMD E                   | 1        | 0.66%   |
| AMD Athlon X4           | 1        | 0.66%   |
| AMD Athlon II X4        | 1        | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 71       | 47.02%  |
| 4      | 51       | 33.77%  |
| 6      | 10       | 6.62%   |
| 1      | 8        | 5.3%    |
| 8      | 7        | 4.64%   |
| 64     | 1        | 0.66%   |
| 16     | 1        | 0.66%   |
| 12     | 1        | 0.66%   |
| 3      | 1        | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 149      | 98.68%  |
| 2      | 2        | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 97       | 64.24%  |
| 2      | 54       | 35.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 151      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 15.13%  |
| 0x206a7    | 12       | 7.89%   |
| 0x1067a    | 12       | 7.89%   |
| 0x306c3    | 11       | 7.24%   |
| 0x306a9    | 7        | 4.61%   |
| 0x06001119 | 6        | 3.95%   |
| 0x406c4    | 5        | 3.29%   |
| 0x906e9    | 4        | 2.63%   |
| 0x6fd      | 4        | 2.63%   |
| 0x6fb      | 4        | 2.63%   |
| 0x10676    | 4        | 2.63%   |
| 0x010000c8 | 4        | 2.63%   |
| 0x6f6      | 3        | 1.97%   |
| 0x20655    | 3        | 1.97%   |
| 0x08701021 | 3        | 1.97%   |
| 0x0800820d | 3        | 1.97%   |
| 0x06000852 | 3        | 1.97%   |
| 0xa0653    | 2        | 1.32%   |
| 0x6f2      | 2        | 1.32%   |
| 0x506e3    | 2        | 1.32%   |
| 0x30678    | 2        | 1.32%   |
| 0x206d7    | 2        | 1.32%   |
| 0x106ca    | 2        | 1.32%   |
| 0x0a50000c | 2        | 1.32%   |
| 0x08701013 | 2        | 1.32%   |
| 0x0700010f | 2        | 1.32%   |
| 0x010000c7 | 2        | 1.32%   |
| 0xf65      | 1        | 0.66%   |
| 0xf4a      | 1        | 0.66%   |
| 0xa0655    | 1        | 0.66%   |
| 0x906ea    | 1        | 0.66%   |
| 0x706a1    | 1        | 0.66%   |
| 0x6f7      | 1        | 0.66%   |
| 0x406c3    | 1        | 0.66%   |
| 0x306f2    | 1        | 0.66%   |
| 0x306e4    | 1        | 0.66%   |
| 0x30661    | 1        | 0.66%   |
| 0x106e5    | 1        | 0.66%   |
| 0x10677    | 1        | 0.66%   |
| 0x0830104d | 1        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 17       | 11.26%  |
| SandyBridge   | 14       | 9.27%   |
| Haswell       | 14       | 9.27%   |
| Core          | 14       | 9.27%   |
| K8 Hammer     | 12       | 7.95%   |
| K10           | 12       | 7.95%   |
| Piledriver    | 9        | 5.96%   |
| Silvermont    | 8        | 5.3%    |
| IvyBridge     | 8        | 5.3%    |
| Zen 2         | 7        | 4.64%   |
| Zen+          | 6        | 3.97%   |
| KabyLake      | 5        | 3.31%   |
| CometLake     | 4        | 2.65%   |
| Westmere      | 3        | 1.99%   |
| Skylake       | 3        | 1.99%   |
| Jaguar        | 3        | 1.99%   |
| Bonnell       | 3        | 1.99%   |
| Zen 3         | 2        | 1.32%   |
| NetBurst      | 2        | 1.32%   |
| Steamroller   | 1        | 0.66%   |
| Nehalem       | 1        | 0.66%   |
| K10 Llano     | 1        | 0.66%   |
| Goldmont plus | 1        | 0.66%   |
| Bobcat        | 1        | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 56       | 35.67%  |
| Intel  | 55       | 35.03%  |
| AMD    | 46       | 29.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 5.49%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 3.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 3.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6        | 3.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 3.66%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5        | 3.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 3.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.44%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 2.44%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 2.44%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4        | 2.44%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 3        | 1.83%   |
| Intel HD Graphics 530                                                                    | 3        | 1.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.22%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 1.22%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.22%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.22%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.22%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.22%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.22%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.22%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.22%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.22%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.61%   |
| Nvidia TU117 [GeForce GTX 1630]                                                          | 1        | 0.61%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.61%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.61%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.61%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.61%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.61%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.61%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.61%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 53       | 34.87%  |
| 1 x Intel    | 52       | 34.21%  |
| 1 x AMD      | 40       | 26.32%  |
| 2 x AMD      | 4        | 2.63%   |
| 2 x Nvidia   | 1        | 0.66%   |
| Intel + AMD  | 1        | 0.66%   |
| AMD + Nvidia | 1        | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 121      | 80.13%  |
| Proprietary | 28       | 18.54%  |
| Unknown     | 2        | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 38.82%  |
| 0.01-0.5   | 39       | 25.66%  |
| 0.51-1.0   | 24       | 15.79%  |
| 1.01-2.0   | 15       | 9.87%   |
| 3.01-4.0   | 9        | 5.92%   |
| 7.01-8.0   | 3        | 1.97%   |
| 8.01-16.0  | 2        | 1.32%   |
| 2.01-3.0   | 1        | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 22       | 14.97%  |
| Dell                    | 20       | 13.61%  |
| Goldstar                | 14       | 9.52%   |
| Acer                    | 11       | 7.48%   |
| Hewlett-Packard         | 9        | 6.12%   |
| Iiyama                  | 7        | 4.76%   |
| BenQ                    | 7        | 4.76%   |
| Philips                 | 6        | 4.08%   |
| Lenovo                  | 5        | 3.4%    |
| Vizio                   | 4        | 2.72%   |
| Ancor Communications    | 4        | 2.72%   |
| Unknown                 | 3        | 2.04%   |
| AOC                     | 3        | 2.04%   |
| Sony                    | 2        | 1.36%   |
| LG Electronics          | 2        | 1.36%   |
| IOD                     | 2        | 1.36%   |
| FL_                     | 2        | 1.36%   |
| Compaq Computer         | 2        | 1.36%   |
| ___                     | 1        | 0.68%   |
| ViewSonic               | 1        | 0.68%   |
| Unknown (ADA)           | 1        | 0.68%   |
| SHD                     | 1        | 0.68%   |
| Sceptre Tech            | 1        | 0.68%   |
| Proview                 | 1        | 0.68%   |
| Plain Tree Systems      | 1        | 0.68%   |
| NEC Computers           | 1        | 0.68%   |
| MOT                     | 1        | 0.68%   |
| Lite-On                 | 1        | 0.68%   |
| LG Display              | 1        | 0.68%   |
| Lenovo Group Limited    | 1        | 0.68%   |
| IBM                     | 1        | 0.68%   |
| Hitachi                 | 1        | 0.68%   |
| HannStar                | 1        | 0.68%   |
| GDH                     | 1        | 0.68%   |
| Fujitsu Siemens         | 1        | 0.68%   |
| Element                 | 1        | 0.68%   |
| CVT                     | 1        | 0.68%   |
| Chi Mei Optoelectronics | 1        | 0.68%   |
| Belinea                 | 1        | 0.68%   |
| Arnos Instruments       | 1        | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 1.32%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 1.32%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                 | 2        | 1.32%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2        | 1.32%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 1.32%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 1.32%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                     | 2        | 1.32%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 410x260mm 19.1-inch | 2        | 1.32%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.66%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1        | 0.66%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                 | 1        | 0.66%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.66%   |
| Vizio E421VO VIZ0090 1920x1080 930x530mm 42.1-inch                    | 1        | 0.66%   |
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                   | 1        | 0.66%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch              | 1        | 0.66%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.66%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.66%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.66%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.66%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.66%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.66%   |
| Sony TV SNYAA01 1360x768                                              | 1        | 0.66%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.66%   |
| SHD 701Lite SHD02BD 1920x1080 110x62mm 5.0-inch                       | 1        | 0.66%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1        | 0.66%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.66%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x257mm 19.1-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0218 1280x1024 376x301mm 19.0-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1        | 0.66%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.66%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.66%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 48       | 32.21%  |
| 1280x1024 (SXGA)   | 26       | 17.45%  |
| 1680x1050 (WSXGA+) | 18       | 12.08%  |
| 1366x768 (WXGA)    | 11       | 7.38%   |
| 1440x900 (WXGA+)   | 10       | 6.71%   |
| 2560x1440 (QHD)    | 8        | 5.37%   |
| 1024x768 (XGA)     | 6        | 4.03%   |
| 3840x2160 (4K)     | 5        | 3.36%   |
| 1600x900 (HD+)     | 3        | 2.01%   |
| 3440x1440          | 2        | 1.34%   |
| 2560x1080          | 2        | 1.34%   |
| 1600x1200          | 2        | 1.34%   |
| 1280x800 (WXGA)    | 2        | 1.34%   |
| 3600x1200          | 1        | 0.67%   |
| 2560x1600          | 1        | 0.67%   |
| 2288x1287          | 1        | 0.67%   |
| 1920x1200 (WUXGA)  | 1        | 0.67%   |
| 1360x768           | 1        | 0.67%   |
| Unknown            | 1        | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 17       | 11.56%  |
| 23      | 14       | 9.52%   |
| 19      | 14       | 9.52%   |
| 24      | 12       | 8.16%   |
| 21      | 12       | 8.16%   |
| Unknown | 12       | 8.16%   |
| 27      | 11       | 7.48%   |
| 20      | 10       | 6.8%    |
| 22      | 9        | 6.12%   |
| 18      | 8        | 5.44%   |
| 15      | 7        | 4.76%   |
| 34      | 3        | 2.04%   |
| 47      | 2        | 1.36%   |
| 39      | 2        | 1.36%   |
| 31      | 2        | 1.36%   |
| 84      | 1        | 0.68%   |
| 72      | 1        | 0.68%   |
| 52      | 1        | 0.68%   |
| 48      | 1        | 0.68%   |
| 41      | 1        | 0.68%   |
| 40      | 1        | 0.68%   |
| 38      | 1        | 0.68%   |
| 29      | 1        | 0.68%   |
| 14      | 1        | 0.68%   |
| 11      | 1        | 0.68%   |
| 7       | 1        | 0.68%   |
| 5       | 1        | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 43       | 29.66%  |
| 501-600     | 36       | 24.83%  |
| 301-350     | 23       | 15.86%  |
| Unknown     | 12       | 8.28%   |
| 351-400     | 10       | 6.9%    |
| 801-900     | 4        | 2.76%   |
| 601-700     | 4        | 2.76%   |
| 1001-1500   | 4        | 2.76%   |
| 701-800     | 3        | 2.07%   |
| 1501-2000   | 2        | 1.38%   |
| 101-200     | 2        | 1.38%   |
| 201-300     | 1        | 0.69%   |
| 901-1000    | 1        | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 49.65%  |
| 5/4     | 24       | 16.78%  |
| 16/10   | 24       | 16.78%  |
| Unknown | 10       | 6.99%   |
| 4/3     | 7        | 4.9%    |
| 21/9    | 4        | 2.8%    |
| 6/5     | 2        | 1.4%    |
| 3/2     | 1        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 41       | 28.47%  |
| 151-200        | 28       | 19.44%  |
| 141-150        | 21       | 14.58%  |
| 301-350        | 12       | 8.33%   |
| Unknown        | 12       | 8.33%   |
| 101-110        | 7        | 4.86%   |
| 501-1000       | 7        | 4.86%   |
| 351-500        | 5        | 3.47%   |
| More than 1000 | 4        | 2.78%   |
| 1-40           | 2        | 1.39%   |
| 251-300        | 2        | 1.39%   |
| 81-90          | 1        | 0.69%   |
| 51-60          | 1        | 0.69%   |
| 131-140        | 1        | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 97       | 68.79%  |
| 101-120       | 18       | 12.77%  |
| Unknown       | 12       | 8.51%   |
| 121-160       | 7        | 4.96%   |
| 1-50          | 5        | 3.55%   |
| More than 240 | 1        | 0.71%   |
| 161-240       | 1        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 132      | 87.42%  |
| 2     | 12       | 7.95%   |
| 0     | 5        | 3.31%   |
| 4     | 1        | 0.66%   |
| 3     | 1        | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 91       | 42.72%  |
| Intel                    | 50       | 23.47%  |
| Nvidia                   | 16       | 7.51%   |
| Ralink Technology        | 12       | 5.63%   |
| Qualcomm Atheros         | 12       | 5.63%   |
| Ralink                   | 5        | 2.35%   |
| Broadcom                 | 5        | 2.35%   |
| Marvell Technology Group | 4        | 1.88%   |
| Broadcom Limited         | 3        | 1.41%   |
| TP-Link                  | 2        | 0.94%   |
| Samsung Electronics      | 2        | 0.94%   |
| ZyXEL Communications     | 1        | 0.47%   |
| VIA Technologies         | 1        | 0.47%   |
| U-Blox                   | 1        | 0.47%   |
| Sitecom Europe           | 1        | 0.47%   |
| NetGear                  | 1        | 0.47%   |
| Logitec                  | 1        | 0.47%   |
| Huawei Technologies      | 1        | 0.47%   |
| Belkin Components        | 1        | 0.47%   |
| ASIX Electronics         | 1        | 0.47%   |
| Aquantia                 | 1        | 0.47%   |
| ADMtek                   | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65       | 28.26%  |
| Nvidia MCP61 Ethernet                                             | 9        | 3.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 2.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 2.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.74%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.74%   |
| Realtek RTL8187 Wireless Adapter                                  | 3        | 1.3%    |
| Ralink RT5572 Wireless Adapter                                    | 3        | 1.3%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.3%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.87%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.87%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.87%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.87%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.87%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.87%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.87%   |
| Intel Wireless-AC 9260                                            | 2        | 0.87%   |
| Intel Wireless 7260                                               | 2        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.87%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.87%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.43%   |
| U-Blox GNSS receiver                                              | 1        | 0.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.43%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.43%   |
| Realtek RTL8812AU-VS 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.43%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 17       | 26.15%  |
| Ralink Technology        | 12       | 18.46%  |
| Intel                    | 12       | 18.46%  |
| Qualcomm Atheros         | 8        | 12.31%  |
| Ralink                   | 5        | 7.69%   |
| TP-Link                  | 2        | 3.08%   |
| Broadcom                 | 2        | 3.08%   |
| ZyXEL Communications     | 1        | 1.54%   |
| Sitecom Europe           | 1        | 1.54%   |
| NetGear                  | 1        | 1.54%   |
| Marvell Technology Group | 1        | 1.54%   |
| Logitec                  | 1        | 1.54%   |
| Broadcom Limited         | 1        | 1.54%   |
| Belkin Components        | 1        | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 7.69%   |
| Ralink MT7601U Wireless Adapter                                | 4        | 6.15%   |
| Realtek RTL8187 Wireless Adapter                               | 3        | 4.62%   |
| Ralink RT5572 Wireless Adapter                                 | 3        | 4.62%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 3        | 4.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 3.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 3.08%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 3.08%   |
| Intel Wireless-AC 9260                                         | 2        | 3.08%   |
| Intel Wireless 7260                                            | 2        | 3.08%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 1.54%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 1.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 1.54%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 1.54%   |
| Realtek RTL8812AU-VS 802.11a/b/g/n/ac 2T2R DB WLAN Adapter     | 1        | 1.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 1.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 1.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 1.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 1.54%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1        | 1.54%   |
| Ralink RT5372 Wireless Adapter                                 | 1        | 1.54%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 1.54%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 1.54%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.54%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 1.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 1.54%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 1.54%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless            | 1        | 1.54%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                      | 1        | 1.54%   |
| Intel Wireless 7265                                            | 1        | 1.54%   |
| Intel Wireless 3165                                            | 1        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 79       | 50.32%  |
| Intel                    | 41       | 26.11%  |
| Nvidia                   | 16       | 10.19%  |
| Qualcomm Atheros         | 5        | 3.18%   |
| Broadcom                 | 4        | 2.55%   |
| Marvell Technology Group | 3        | 1.91%   |
| Samsung Electronics      | 2        | 1.27%   |
| Broadcom Limited         | 2        | 1.27%   |
| VIA Technologies         | 1        | 0.64%   |
| Huawei Technologies      | 1        | 0.64%   |
| ASIX Electronics         | 1        | 0.64%   |
| Aquantia                 | 1        | 0.64%   |
| ADMtek                   | 1        | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65       | 39.63%  |
| Nvidia MCP61 Ethernet                                             | 9        | 5.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 3.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 3.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.44%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.83%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.83%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.83%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.22%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.22%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.22%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.22%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.22%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.61%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.61%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.61%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.61%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.61%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.61%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.61%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.61%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.61%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 1        | 0.61%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 150      | 70.09%  |
| WiFi     | 63       | 29.44%  |
| Modem    | 1        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 123      | 77.85%  |
| WiFi     | 35       | 22.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 111      | 73.51%  |
| 2     | 34       | 22.52%  |
| 3     | 5        | 3.31%   |
| 0     | 1        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 117      | 76.97%  |
| Yes  | 35       | 23.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 35.71%  |
| Cambridge Silicon Radio | 8        | 28.57%  |
| Broadcom                | 4        | 14.29%  |
| ASUSTek Computer        | 2        | 7.14%   |
| Ralink                  | 1        | 3.57%   |
| Logitech                | 1        | 3.57%   |
| Lite-On Technology      | 1        | 3.57%   |
| Hewlett-Packard         | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 28.57%  |
| Intel Bluetooth wireless interface                  | 4        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 7.14%   |
| Ralink RT3290 Bluetooth                             | 1        | 3.57%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 3.57%   |
| Lite-On Bluetooth Device                            | 1        | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 3.57%   |
| Intel AX210 Bluetooth                               | 1        | 3.57%   |
| Intel AX201 Bluetooth                               | 1        | 3.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 3.57%   |
| Broadcom Bluetooth Device                           | 1        | 3.57%   |
| Broadcom BCM20702A0                                 | 1        | 3.57%   |
| ASUS BCM20702A0                                     | 1        | 3.57%   |
| ASUS ASUS USB-BT500                                 | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 87       | 41.04%  |
| Nvidia                   | 53       | 25%     |
| AMD                      | 53       | 25%     |
| Creative Labs            | 4        | 1.89%   |
| C-Media Electronics      | 4        | 1.89%   |
| XMOS                     | 2        | 0.94%   |
| VIA Technologies         | 1        | 0.47%   |
| Texas Instruments        | 1        | 0.47%   |
| Setek Elektronik         | 1        | 0.47%   |
| Scarlett                 | 1        | 0.47%   |
| Logitech                 | 1        | 0.47%   |
| GN Netcom                | 1        | 0.47%   |
| Creative Technology      | 1        | 0.47%   |
| ASUSTek Computer         | 1        | 0.47%   |
| Asahi Kasei Microsystems | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12       | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12       | 4.92%   |
| Nvidia High Definition Audio Controller                                           | 11       | 4.51%   |
| AMD FCH Azalia Controller                                                         | 11       | 4.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10       | 4.1%    |
| Nvidia MCP61 High Definition Audio                                                | 9        | 3.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 9        | 3.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 3.28%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 2.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 2.87%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 2.46%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5        | 2.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 5        | 2.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 1.64%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 1.64%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.64%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 1.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 1.23%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 1.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.23%   |
| XMOS Mayfield Audio                                                               | 2        | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 0.82%   |
| Nvidia MCP51 High Definition Audio                                                | 2        | 0.82%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.82%   |
| Nvidia CK804 AC'97 Audio Controller                                               | 2        | 0.82%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 2        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 0.82%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 0.82%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 22       | 19.82%  |
| Samsung Electronics | 20       | 18.02%  |
| SK hynix            | 17       | 15.32%  |
| Kingston            | 9        | 8.11%   |
| G.Skill             | 8        | 7.21%   |
| Crucial             | 6        | 5.41%   |
| Corsair             | 6        | 5.41%   |
| Micron Technology   | 5        | 4.5%    |
| Nanya Technology    | 4        | 3.6%    |
| Timetec             | 2        | 1.8%    |
| Patriot             | 2        | 1.8%    |
| Elpida              | 2        | 1.8%    |
| Unknown (ABCD)      | 1        | 0.9%    |
| Unifosa             | 1        | 0.9%    |
| Team                | 1        | 0.9%    |
| Ramaxel Technology  | 1        | 0.9%    |
| Qimonda             | 1        | 0.9%    |
| PNY                 | 1        | 0.9%    |
| e2e4                | 1        | 0.9%    |
| 48spaces            | 1        | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 4        | 3.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 2        | 1.67%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 2        | 1.67%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                  | 2        | 1.67%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 2        | 1.67%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s             | 2        | 1.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                   | 1        | 0.83%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                         | 1        | 0.83%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1        | 0.83%   |
| Unknown RAM Module 512MB DIMM 333MT/s                          | 1        | 0.83%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.83%   |
| Unknown RAM Module 4096MB DIMM SDRAM                           | 1        | 0.83%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.83%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1        | 0.83%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1        | 0.83%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1        | 0.83%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 1        | 0.83%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1        | 0.83%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 1        | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                    | 1        | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1        | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 1        | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.83%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 1        | 0.83%   |
| Timetec RAM UD3-1600 8GB DIMM DDR3 1600MT/s                    | 1        | 0.83%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                  | 1        | 0.83%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s         | 1        | 0.83%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                  | 1        | 0.83%   |
| SK hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s         | 1        | 0.83%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 1        | 0.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.83%   |
| SK hynix RAM HMT451R7AFR8C-RD 4GB DIMM DDR3 1866MT/s           | 1        | 0.83%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.83%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s        | 1        | 0.83%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1        | 0.83%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 0.83%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 1        | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 41       | 40.2%   |
| DDR4    | 20       | 19.61%  |
| DDR2    | 16       | 15.69%  |
| SDRAM   | 13       | 12.75%  |
| Unknown | 9        | 8.82%   |
| DDR     | 2        | 1.96%   |
| LPDDR4  | 1        | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 83       | 86.46%  |
| SODIMM | 13       | 13.54%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 32       | 31.07%  |
| 8192  | 25       | 24.27%  |
| 4096  | 22       | 21.36%  |
| 1024  | 11       | 10.68%  |
| 16384 | 7        | 6.8%    |
| 512   | 3        | 2.91%   |
| 32768 | 2        | 1.94%   |
| 65536 | 1        | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 21.1%   |
| 1333    | 11       | 10.09%  |
| 800     | 11       | 10.09%  |
| 2133    | 8        | 7.34%   |
| 667     | 6        | 5.5%    |
| 400     | 6        | 5.5%    |
| 2400    | 5        | 4.59%   |
| 1066    | 5        | 4.59%   |
| 1866    | 4        | 3.67%   |
| Unknown | 4        | 3.67%   |
| 3200    | 3        | 2.75%   |
| 2048    | 3        | 2.75%   |
| 1867    | 3        | 2.75%   |
| 3600    | 2        | 1.83%   |
| 3000    | 2        | 1.83%   |
| 2667    | 2        | 1.83%   |
| 533     | 2        | 1.83%   |
| 49926   | 1        | 0.92%   |
| 3933    | 1        | 0.92%   |
| 3866    | 1        | 0.92%   |
| 3066    | 1        | 0.92%   |
| 2933    | 1        | 0.92%   |
| 2733    | 1        | 0.92%   |
| 1639    | 1        | 0.92%   |
| 1334    | 1        | 0.92%   |
| 333     | 1        | 0.92%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Dymo-CoStar     | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP DeskJet 3630 series                 | 1        | 50%     |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 50%     |

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
| Logitech                      | 5        | 26.32%  |
| Generalplus Technology        | 2        | 10.53%  |
| Chicony Electronics           | 2        | 10.53%  |
| Z-Star Microelectronics       | 1        | 5.26%   |
| Sunplus IT                    | 1        | 5.26%   |
| Sunplus Innovation Technology | 1        | 5.26%   |
| Samsung Electronics           | 1        | 5.26%   |
| Microsoft                     | 1        | 5.26%   |
| KYE Systems (Mouse Systems)   | 1        | 5.26%   |
| Guillemot                     | 1        | 5.26%   |
| Genesys Logic                 | 1        | 5.26%   |
| ARC International             | 1        | 5.26%   |
| Acer                          | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 2        | 10.53%  |
| Generalplus GENERAL WEBCAM                | 2        | 10.53%  |
| Z-Star Sirius USB2.0 Camera               | 1        | 5.26%   |
| Sunplus IT 1080P Webcam                   | 1        | 5.26%   |
| Sunplus Full HD webcam                    | 1        | 5.26%   |
| Samsung Galaxy A5 (MTP)                   | 1        | 5.26%   |
| Microsoft LifeCam HD-3000                 | 1        | 5.26%   |
| Logitech Webcam B500                      | 1        | 5.26%   |
| Logitech QuickCam Zoom                    | 1        | 5.26%   |
| Logitech HD Webcam C525                   | 1        | 5.26%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 5.26%   |
| Guillemot Hercules HD Sunset              | 1        | 5.26%   |
| Genesys Logic Camera                      | 1        | 5.26%   |
| Chicony CNF7042                           | 1        | 5.26%   |
| Chicony ASUS USB2.0 Webcam                | 1        | 5.26%   |
| ARC International Camera                  | 1        | 5.26%   |
| Acer Integrated Camera                    | 1        | 5.26%   |

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
| 0     | 126      | 83.44%  |
| 1     | 22       | 14.57%  |
| 2     | 3        | 1.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 24%     |
| Net/wireless             | 5        | 20%     |
| Communication controller | 4        | 16%     |
| Sound                    | 3        | 12%     |
| Unassigned class         | 2        | 8%      |
| Dvb card                 | 2        | 8%      |
| Net/ethernet             | 1        | 4%      |
| Multimedia controller    | 1        | 4%      |
| Bluetooth                | 1        | 4%      |

