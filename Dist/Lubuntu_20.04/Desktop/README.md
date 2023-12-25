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

Total: 207

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| AAEON         | MF-001 V1.0                 | [9e7c59246d](https://linux-hardware.org/?probe=9e7c59246d) | Dec 19, 2023 |
| XFX           | MI-9300-7AS9                | [a3015ca40c](https://linux-hardware.org/?probe=a3015ca40c) | Dec 14, 2023 |
| Dell          | 0PU052                      | [4a653cc26a](https://linux-hardware.org/?probe=4a653cc26a) | Dec 02, 2023 |
| Acer          | Predator G3610              | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| Gigabyte      | B560 HD3                    | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Unknown       | SCHNEIDER                   | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
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
| 5.4.0-52-generic   | 8        | 4.76%   |
| 5.4.0-42-generic   | 8        | 4.76%   |
| 5.11.0-27-generic  | 7        | 4.17%   |
| 5.8.0-50-generic   | 6        | 3.57%   |
| 5.4.0-54-generic   | 5        | 2.98%   |
| 5.13.0-28-generic  | 5        | 2.98%   |
| 5.4.0-67-generic   | 4        | 2.38%   |
| 5.4.0-40-generic   | 4        | 2.38%   |
| 5.4.0-29-generic   | 4        | 2.38%   |
| 5.4.0-122-generic  | 4        | 2.38%   |
| 5.8.0-53-generic   | 3        | 1.79%   |
| 5.4.0-77-generic   | 3        | 1.79%   |
| 5.4.0-73-generic   | 3        | 1.79%   |
| 5.4.0-48-generic   | 3        | 1.79%   |
| 5.4.0-47-generic   | 3        | 1.79%   |
| 5.4.0-37-generic   | 3        | 1.79%   |
| 5.4.0-33-generic   | 3        | 1.79%   |
| 5.4.0-26-generic   | 3        | 1.79%   |
| 5.8.0-63-generic   | 2        | 1.19%   |
| 5.8.0-59-generic   | 2        | 1.19%   |
| 5.8.0-45-generic   | 2        | 1.19%   |
| 5.8.0-41-generic   | 2        | 1.19%   |
| 5.4.30-dli         | 2        | 1.19%   |
| 5.4.0-96-generic   | 2        | 1.19%   |
| 5.4.0-91-generic   | 2        | 1.19%   |
| 5.4.0-90-generic   | 2        | 1.19%   |
| 5.4.0-72-generic   | 2        | 1.19%   |
| 5.4.0-66-generic   | 2        | 1.19%   |
| 5.4.0-60-generic   | 2        | 1.19%   |
| 5.4.0-131-generic  | 2        | 1.19%   |
| 5.4.0-109-generic  | 2        | 1.19%   |
| 5.15.0-60-generic  | 2        | 1.19%   |
| 5.15.0-53-generic  | 2        | 1.19%   |
| 5.13.0-27-generic  | 2        | 1.19%   |
| 5.11.0-43-generic  | 2        | 1.19%   |
| 5.11.0-38-generic  | 2        | 1.19%   |
| 5.11.0-34-generic  | 2        | 1.19%   |
| 5.8.0-7630-generic | 1        | 0.6%    |
| 5.8.0-55-generic   | 1        | 0.6%    |
| 5.8.0-48-generic   | 1        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 86       | 53.75%  |
| 5.8.0   | 22       | 13.75%  |
| 5.11.0  | 19       | 11.88%  |
| 5.15.0  | 13       | 8.13%   |
| 5.13.0  | 13       | 8.13%   |
| 5.4.30  | 2        | 1.25%   |
| 5.6.15  | 1        | 0.63%   |
| 5.6.0   | 1        | 0.63%   |
| 5.3.18  | 1        | 0.63%   |
| 5.16.5  | 1        | 0.63%   |
| 5.14.0  | 1        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 88       | 55%     |
| 5.8     | 22       | 13.75%  |
| 5.11    | 19       | 11.88%  |
| 5.15    | 13       | 8.13%   |
| 5.13    | 13       | 8.13%   |
| 5.6     | 2        | 1.25%   |
| 5.3     | 1        | 0.63%   |
| 5.16    | 1        | 0.63%   |
| 5.14    | 1        | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 158      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| LXQt       | 147      | 93.04%  |
| LXDE       | 5        | 3.16%   |
| GNOME      | 3        | 1.9%    |
| XFCE       | 1        | 0.63%   |
| X-Cinnamon | 1        | 0.63%   |
| i3         | 1        | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 149      | 94.3%   |
| Tty     | 7        | 4.43%   |
| Wayland | 1        | 0.63%   |
| Unknown | 1        | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 89       | 54.94%  |
| Unknown | 43       | 26.54%  |
| LightDM | 12       | 7.41%   |
| GDM     | 10       | 6.17%   |
| TDM     | 6        | 3.7%    |
| LXDM    | 1        | 0.62%   |
| GDM3    | 1        | 0.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 42       | 26.58%  |
| fr_FR   | 26       | 16.46%  |
| de_DE   | 14       | 8.86%   |
| pt_BR   | 12       | 7.59%   |
| it_IT   | 11       | 6.96%   |
| C       | 8        | 5.06%   |
| ru_RU   | 5        | 3.16%   |
| ja_JP   | 4        | 2.53%   |
| en_GB   | 4        | 2.53%   |
| en_AU   | 4        | 2.53%   |
| fi_FI   | 3        | 1.9%    |
| es_ES   | 3        | 1.9%    |
| hu_HU   | 2        | 1.27%   |
| en_ZA   | 2        | 1.27%   |
| en_CA   | 2        | 1.27%   |
| de_CH   | 2        | 1.27%   |
| cs_CZ   | 2        | 1.27%   |
| Unknown | 2        | 1.27%   |
| sv_SE   | 1        | 0.63%   |
| nl_NL   | 1        | 0.63%   |
| fr_CA   | 1        | 0.63%   |
| es_PE   | 1        | 0.63%   |
| es_MX   | 1        | 0.63%   |
| es_CR   | 1        | 0.63%   |
| es_CO   | 1        | 0.63%   |
| en_SG   | 1        | 0.63%   |
| en_NZ   | 1        | 0.63%   |
| el_GR   | 1        | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 105      | 66.46%  |
| EFI  | 53       | 33.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 146      | 92.41%  |
| Overlay | 7        | 4.43%   |
| Xfs     | 2        | 1.27%   |
| Zfs     | 1        | 0.63%   |
| F2fs    | 1        | 0.63%   |
| Btrfs   | 1        | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 35.63%  |
| MBR     | 54       | 33.75%  |
| GPT     | 49       | 30.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 81.01%  |
| Yes       | 30       | 18.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 69.81%  |
| Yes       | 48       | 30.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 15.82%  |
| Hewlett-Packard     | 18       | 11.39%  |
| Gigabyte Technology | 17       | 10.76%  |
| MSI                 | 16       | 10.13%  |
| Dell                | 15       | 9.49%   |
| ASRock              | 15       | 9.49%   |
| Lenovo              | 9        | 5.7%    |
| Intel               | 9        | 5.7%    |
| Pegatron            | 5        | 3.16%   |
| Acer                | 5        | 3.16%   |
| AAEON               | 4        | 2.53%   |
| Unknown             | 3        | 1.9%    |
| Positivo            | 2        | 1.27%   |
| Foxconn             | 2        | 1.27%   |
| Biostar             | 2        | 1.27%   |
| AMI                 | 2        | 1.27%   |
| ZOTAC               | 1        | 0.63%   |
| XFX                 | 1        | 0.63%   |
| Packard Bell        | 1        | 0.63%   |
| IBM                 | 1        | 0.63%   |
| Huanan              | 1        | 0.63%   |
| Hardkernel          | 1        | 0.63%   |
| Fujitsu Siemens     | 1        | 0.63%   |
| Fujitsu             | 1        | 0.63%   |
| AOpen               | 1        | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| AAEON MF-001                         | 4        | 2.53%   |
| Unknown                              | 3        | 1.9%    |
| MSI MS-7C37                          | 2        | 1.27%   |
| MSI MS-7B89                          | 2        | 1.27%   |
| HP t620 Quad Core TC                 | 2        | 1.27%   |
| HP Compaq 6000 Pro SFF PC            | 2        | 1.27%   |
| Dell OptiPlex 790                    | 2        | 1.27%   |
| ASUS M5A97 R2.0                      | 2        | 1.27%   |
| ASRock N68-VS3 UCC                   | 2        | 1.27%   |
| ASRock FM2A85X Extreme6              | 2        | 1.27%   |
| ZOTAC NM10                           | 1        | 0.63%   |
| XFX MI-9300-7AS9                     | 1        | 0.63%   |
| Positivo POS-MI945AA                 | 1        | 0.63%   |
| Positivo POS-EIH61CE                 | 1        | 0.63%   |
| Pegatron WE216AA-ABF CQ5335FR        | 1        | 0.63%   |
| Pegatron NC689AA-ABA s3700y          | 1        | 0.63%   |
| Pegatron FL308AA-ABD IQ512de         | 1        | 0.63%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.63%   |
| Pegatron AY652AA-ABA s5310y          | 1        | 0.63%   |
| Packard Bell IMEDIA S1350            | 1        | 0.63%   |
| MSI MS-7D16                          | 1        | 0.63%   |
| MSI MS-7B86                          | 1        | 0.63%   |
| MSI MS-7B09                          | 1        | 0.63%   |
| MSI MS-7994                          | 1        | 0.63%   |
| MSI MS-7846                          | 1        | 0.63%   |
| MSI MS-7721                          | 1        | 0.63%   |
| MSI MS-7680                          | 1        | 0.63%   |
| MSI MS-7640                          | 1        | 0.63%   |
| MSI MS-7592                          | 1        | 0.63%   |
| MSI MS-7309                          | 1        | 0.63%   |
| MSI ER883AA-ABA M7470N               | 1        | 0.63%   |
| MSI Compaq dx2200 MT                 | 1        | 0.63%   |
| Lenovo ThinkStation P620 30E0CTO1WW  | 1        | 0.63%   |
| Lenovo ThinkCentre M93z 10AD002DMZ   | 1        | 0.63%   |
| Lenovo ThinkCentre M73 10AXS0HN00    | 1        | 0.63%   |
| Lenovo ThinkCentre M58p 7220W21      | 1        | 0.63%   |
| Lenovo ThinkCentre M58p 6136A66      | 1        | 0.63%   |
| Lenovo ThinkCentre M55p 8811VQV      | 1        | 0.63%   |
| Lenovo ThinkCentre E73 10AU003JFR    | 1        | 0.63%   |
| Lenovo H50-50 90B60081IX             | 1        | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 9        | 5.7%    |
| Dell OptiPlex        | 7        | 4.43%   |
| Lenovo ThinkCentre   | 6        | 3.8%    |
| Acer Aspire          | 4        | 2.53%   |
| AAEON MF-001         | 4        | 2.53%   |
| HP t620              | 3        | 1.9%    |
| Unknown              | 3        | 1.9%    |
| MSI MS-7C37          | 2        | 1.27%   |
| MSI MS-7B89          | 2        | 1.27%   |
| Gigabyte B450M       | 2        | 1.27%   |
| Dell Inspiron        | 2        | 1.27%   |
| ASUS M5A97           | 2        | 1.27%   |
| ASRock N68-VS3       | 2        | 1.27%   |
| ASRock FM2A85X       | 2        | 1.27%   |
| ZOTAC NM10           | 1        | 0.63%   |
| XFX MI-9300-7AS9     | 1        | 0.63%   |
| Positivo POS-MI945AA | 1        | 0.63%   |
| Positivo POS-EIH61CE | 1        | 0.63%   |
| Pegatron WE216AA-ABF | 1        | 0.63%   |
| Pegatron NC689AA-ABA | 1        | 0.63%   |
| Pegatron FL308AA-ABD | 1        | 0.63%   |
| Pegatron Compaq      | 1        | 0.63%   |
| Pegatron AY652AA-ABA | 1        | 0.63%   |
| Packard Bell IMEDIA  | 1        | 0.63%   |
| MSI MS-7D16          | 1        | 0.63%   |
| MSI MS-7B86          | 1        | 0.63%   |
| MSI MS-7B09          | 1        | 0.63%   |
| MSI MS-7994          | 1        | 0.63%   |
| MSI MS-7846          | 1        | 0.63%   |
| MSI MS-7721          | 1        | 0.63%   |
| MSI MS-7680          | 1        | 0.63%   |
| MSI MS-7640          | 1        | 0.63%   |
| MSI MS-7592          | 1        | 0.63%   |
| MSI MS-7309          | 1        | 0.63%   |
| MSI ER883AA-ABA      | 1        | 0.63%   |
| MSI Compaq           | 1        | 0.63%   |
| Lenovo ThinkStation  | 1        | 0.63%   |
| Lenovo H50-50        | 1        | 0.63%   |
| Lenovo H50-30g       | 1        | 0.63%   |
| Intel X79            | 1        | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 15       | 9.49%   |
| 2012 | 13       | 8.23%   |
| 2009 | 13       | 8.23%   |
| 2014 | 12       | 7.59%   |
| 2013 | 12       | 7.59%   |
| 2008 | 12       | 7.59%   |
| 2007 | 12       | 7.59%   |
| 2017 | 11       | 6.96%   |
| 2010 | 11       | 6.96%   |
| 2006 | 9        | 5.7%    |
| 2020 | 7        | 4.43%   |
| 2015 | 7        | 4.43%   |
| 2021 | 6        | 3.8%    |
| 2019 | 6        | 3.8%    |
| 2018 | 4        | 2.53%   |
| 2005 | 4        | 2.53%   |
| 2016 | 3        | 1.9%    |
| 2004 | 1        | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 158      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 154      | 97.47%  |
| Enabled  | 4        | 2.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 158      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 45       | 28.13%  |
| 1.01-2.0        | 24       | 15%     |
| 4.01-8.0        | 23       | 14.38%  |
| 8.01-16.0       | 23       | 14.38%  |
| 16.01-24.0      | 20       | 12.5%   |
| 32.01-64.0      | 12       | 7.5%    |
| 24.01-32.0      | 4        | 2.5%    |
| 2.01-3.0        | 3        | 1.88%   |
| 64.01-256.0     | 3        | 1.88%   |
| 0.51-1.0        | 2        | 1.25%   |
| More than 256.0 | 1        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 79       | 48.17%  |
| 2.01-3.0   | 28       | 17.07%  |
| 0.51-1.0   | 24       | 14.63%  |
| 4.01-8.0   | 17       | 10.37%  |
| 3.01-4.0   | 8        | 4.88%   |
| 8.01-16.0  | 3        | 1.83%   |
| 0.01-0.5   | 3        | 1.83%   |
| 32.01-64.0 | 1        | 0.61%   |
| 16.01-24.0 | 1        | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 84       | 52.83%  |
| 2      | 43       | 27.04%  |
| 4      | 11       | 6.92%   |
| 3      | 8        | 5.03%   |
| 5      | 7        | 4.4%    |
| 6      | 2        | 1.26%   |
| 17     | 1        | 0.63%   |
| 14     | 1        | 0.63%   |
| 7      | 1        | 0.63%   |
| 0      | 1        | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 98       | 60.87%  |
| No        | 63       | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 157      | 99.37%  |
| No        | 1        | 0.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 58.23%  |
| Yes       | 66       | 41.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 81.65%  |
| Yes       | 29       | 18.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 26       | 16.25%  |
| France       | 26       | 16.25%  |
| Germany      | 16       | 10%     |
| Brazil       | 13       | 8.13%   |
| Italy        | 11       | 6.88%   |
| Switzerland  | 6        | 3.75%   |
| Russia       | 6        | 3.75%   |
| Hungary      | 5        | 3.13%   |
| Spain        | 4        | 2.5%    |
| Japan        | 4        | 2.5%    |
| Finland      | 4        | 2.5%    |
| Australia    | 4        | 2.5%    |
| Netherlands  | 3        | 1.88%   |
| Greece       | 3        | 1.88%   |
| Czechia      | 3        | 1.88%   |
| Canada       | 3        | 1.88%   |
| South Africa | 2        | 1.25%   |
| Puerto Rico  | 2        | 1.25%   |
| New Zealand  | 2        | 1.25%   |
| Mexico       | 2        | 1.25%   |
| Belgium      | 2        | 1.25%   |
| UK           | 1        | 0.63%   |
| Sweden       | 1        | 0.63%   |
| Slovenia     | 1        | 0.63%   |
| Slovakia     | 1        | 0.63%   |
| Singapore    | 1        | 0.63%   |
| Romania      | 1        | 0.63%   |
| Peru         | 1        | 0.63%   |
| Martinique   | 1        | 0.63%   |
| Malaysia     | 1        | 0.63%   |
| Ireland      | 1        | 0.63%   |
| Costa Rica   | 1        | 0.63%   |
| Colombia     | 1        | 0.63%   |
| Belarus      | 1        | 0.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Wellington     | 3        | 1.83%   |
| Melbourne      | 3        | 1.83%   |
| Zurich         | 2        | 1.22%   |
| Sao Paulo      | 2        | 1.22%   |
| Rome           | 2        | 1.22%   |
| Raahe          | 2        | 1.22%   |
| Pécs          | 2        | 1.22%   |
| Milan          | 2        | 1.22%   |
| Figeac         | 2        | 1.22%   |
| Cuernavaca     | 2        | 1.22%   |
| Cayey          | 2        | 1.22%   |
| Bern           | 2        | 1.22%   |
| Athens         | 2        | 1.22%   |
| Zwevegem       | 1        | 0.61%   |
| Zeuthen        | 1        | 0.61%   |
| Wraysbury      | 1        | 0.61%   |
| Winsen         | 1        | 0.61%   |
| Wiesbaden      | 1        | 0.61%   |
| West Chester   | 1        | 0.61%   |
| Waren          | 1        | 0.61%   |
| Vinhedo        | 1        | 0.61%   |
| Vilyuchinsk    | 1        | 0.61%   |
| Villejuif      | 1        | 0.61%   |
| Vilabella      | 1        | 0.61%   |
| Vaxjo          | 1        | 0.61%   |
| Vannes         | 1        | 0.61%   |
| Vanderbijlpark | 1        | 0.61%   |
| Valencia       | 1        | 0.61%   |
| Ufa            | 1        | 0.61%   |
| Turku          | 1        | 0.61%   |
| Trebur         | 1        | 0.61%   |
| Toulouse       | 1        | 0.61%   |
| Toronto        | 1        | 0.61%   |
| Tokorozawa     | 1        | 0.61%   |
| Stockton       | 1        | 0.61%   |
| Stedesand      | 1        | 0.61%   |
| Spokane        | 1        | 0.61%   |
| Sora           | 1        | 0.61%   |
| Schiedam       | 1        | 0.61%   |
| Sautron        | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 60       | 73     | 24.39%  |
| WDC                 | 55       | 88     | 22.36%  |
| Samsung Electronics | 30       | 52     | 12.2%   |
| Hitachi             | 11       | 14     | 4.47%   |
| Kingston            | 10       | 10     | 4.07%   |
| Unknown             | 9        | 10     | 3.66%   |
| Toshiba             | 9        | 10     | 3.66%   |
| Crucial             | 9        | 22     | 3.66%   |
| SanDisk             | 5        | 5      | 2.03%   |
| Maxtor              | 5        | 5      | 2.03%   |
| China               | 4        | 4      | 1.63%   |
| A-DATA Technology   | 4        | 5      | 1.63%   |
| Team                | 3        | 3      | 1.22%   |
| Corsair             | 3        | 3      | 1.22%   |
| PNY                 | 2        | 2      | 0.81%   |
| ORTIAL              | 2        | 2      | 0.81%   |
| LDLC                | 2        | 2      | 0.81%   |
| JMicron Technology  | 2        | 2      | 0.81%   |
| Intenso             | 2        | 2      | 0.81%   |
| Intel               | 2        | 2      | 0.81%   |
| Hewlett-Packard     | 2        | 7      | 0.81%   |
| Unknown             | 2        | 2      | 0.81%   |
| Transcend           | 1        | 1      | 0.41%   |
| TO Exter            | 1        | 1      | 0.41%   |
| PNY USB             | 1        | 1      | 0.41%   |
| Patriot             | 1        | 1      | 0.41%   |
| OCZ                 | 1        | 1      | 0.41%   |
| Londisk             | 1        | 1      | 0.41%   |
| Lexar               | 1        | 1      | 0.41%   |
| Leven               | 1        | 2      | 0.41%   |
| KingFast            | 1        | 1      | 0.41%   |
| HGST                | 1        | 1      | 0.41%   |
| GOODRAM             | 1        | 1      | 0.41%   |
| Fujitsu             | 1        | 1      | 0.41%   |
| External            | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB           | 4        | 1.43%   |
| Unknown M52516  16GB                | 3        | 1.08%   |
| Seagate ST3250310AS 250GB           | 3        | 1.08%   |
| Samsung HD502IJ 500GB               | 3        | 1.08%   |
| Samsung HD103SJ 1TB                 | 3        | 1.08%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.72%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.72%   |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.72%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.72%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.72%   |
| WDC WD2500AAKX-07U6AA1 250GB        | 2        | 0.72%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.72%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.72%   |
| WDC WD10EACS-00D6B0 1TB             | 2        | 0.72%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 0.72%   |
| Seagate ST380815AS 80GB             | 2        | 0.72%   |
| Seagate ST3500418AS 500GB           | 2        | 0.72%   |
| Seagate ST3360320AS 360GB           | 2        | 0.72%   |
| Seagate ST3250410AS 250GB           | 2        | 0.72%   |
| Seagate ST31000528AS 1TB            | 2        | 0.72%   |
| Seagate ST3000DM008-2DM166 3TB      | 2        | 0.72%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.72%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.72%   |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 0.72%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 0.72%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.72%   |
| Samsung SSD 850 EVO 250GB           | 2        | 0.72%   |
| Samsung HD161HJ 160GB               | 2        | 0.72%   |
| Samsung HD103SI 1TB                 | 2        | 0.72%   |
| Samsung HD080HJ 80GB                | 2        | 0.72%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 0.72%   |
| Crucial CT1000BX500SSD1 1TB         | 2        | 0.72%   |
| Corsair Force LS SSD 120GB          | 2        | 0.72%   |
| China SATA SSD 512GB                | 2        | 0.72%   |
| A-DATA SU650 240GB SSD              | 2        | 0.72%   |
| Unknown                             | 2        | 0.72%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 60       | 73     | 39.22%  |
| WDC                 | 49       | 76     | 32.03%  |
| Samsung Electronics | 16       | 20     | 10.46%  |
| Hitachi             | 11       | 14     | 7.19%   |
| Toshiba             | 7        | 8      | 4.58%   |
| Maxtor              | 4        | 4      | 2.61%   |
| Unknown             | 1        | 1      | 0.65%   |
| TO Exter            | 1        | 1      | 0.65%   |
| HGST                | 1        | 1      | 0.65%   |
| Hewlett-Packard     | 1        | 1      | 0.65%   |
| Fujitsu             | 1        | 1      | 0.65%   |
| External            | 1        | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 17     | 14.47%  |
| WDC                 | 9        | 11     | 11.84%  |
| Kingston            | 9        | 9      | 11.84%  |
| Crucial             | 8        | 21     | 10.53%  |
| SanDisk             | 5        | 5      | 6.58%   |
| China               | 4        | 4      | 5.26%   |
| Team                | 3        | 3      | 3.95%   |
| Corsair             | 3        | 3      | 3.95%   |
| A-DATA Technology   | 3        | 4      | 3.95%   |
| Toshiba             | 2        | 2      | 2.63%   |
| PNY                 | 2        | 2      | 2.63%   |
| ORTIAL              | 2        | 2      | 2.63%   |
| Intenso             | 2        | 2      | 2.63%   |
| Transcend           | 1        | 1      | 1.32%   |
| PNY USB             | 1        | 1      | 1.32%   |
| Patriot             | 1        | 1      | 1.32%   |
| OCZ                 | 1        | 1      | 1.32%   |
| Maxtor              | 1        | 1      | 1.32%   |
| Londisk             | 1        | 1      | 1.32%   |
| Lexar               | 1        | 1      | 1.32%   |
| Leven               | 1        | 2      | 1.32%   |
| LDLC                | 1        | 1      | 1.32%   |
| JMicron Technology  | 1        | 1      | 1.32%   |
| Intel               | 1        | 1      | 1.32%   |
| Hewlett-Packard     | 1        | 6      | 1.32%   |
| GOODRAM             | 1        | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 115      | 201    | 56.65%  |
| SSD     | 69       | 104    | 33.99%  |
| MMC     | 9        | 11     | 4.43%   |
| NVMe    | 8        | 21     | 3.94%   |
| Unknown | 2        | 2      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 145      | 295    | 84.8%   |
| SAS  | 9        | 12     | 5.26%   |
| MMC  | 9        | 11     | 5.26%   |
| NVMe | 8        | 21     | 4.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 118      | 178    | 61.46%  |
| 0.51-1.0   | 49       | 85     | 25.52%  |
| 1.01-2.0   | 14       | 23     | 7.29%   |
| 3.01-4.0   | 5        | 13     | 2.6%    |
| 2.01-3.0   | 4        | 4      | 2.08%   |
| 4.01-10.0  | 2        | 2      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 43       | 26.54%  |
| 251-500        | 33       | 20.37%  |
| 501-1000       | 20       | 12.35%  |
| 1001-2000      | 17       | 10.49%  |
| More than 3000 | 15       | 9.26%   |
| 51-100         | 15       | 9.26%   |
| 1-20           | 8        | 4.94%   |
| 2001-3000      | 6        | 3.7%    |
| 21-50          | 3        | 1.85%   |
| Unknown        | 2        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 62       | 38.04%  |
| 21-50          | 28       | 17.18%  |
| 101-250        | 16       | 9.82%   |
| 501-1000       | 13       | 7.98%   |
| 51-100         | 12       | 7.36%   |
| 251-500        | 11       | 6.75%   |
| 1001-2000      | 9        | 5.52%   |
| More than 3000 | 6        | 3.68%   |
| 2001-3000      | 4        | 2.45%   |
| Unknown        | 2        | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB    | 2        | 2      | 6.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 1      | 3.03%   |
| WDC WD400EB-00CPF0 40GB           | 1        | 1      | 3.03%   |
| WDC WD2500AAJS-75M0A0 250GB       | 1        | 1      | 3.03%   |
| WDC WD1600AAJS-60B4A0 160GB       | 1        | 2      | 3.03%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 1      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 3.03%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 3.03%   |
| Seagate ST360012A 64GB            | 1        | 1      | 3.03%   |
| Seagate ST3360320AS 360GB         | 1        | 1      | 3.03%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 3.03%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 3.03%   |
| Seagate ST3160812AS 160GB         | 1        | 1      | 3.03%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 3.03%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 1      | 3.03%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 3.03%   |
| Seagate ST1000DX001-1CM162 1TB    | 1        | 1      | 3.03%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 3.03%   |
| SanDisk SSD PLUS 120GB            | 1        | 1      | 3.03%   |
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 3.03%   |
| ORTIAL SSD 128GB                  | 1        | 1      | 3.03%   |
| Maxtor STM3300622A 304GB          | 1        | 1      | 3.03%   |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 3.03%   |
| Maxtor 6B200M0 208GB              | 1        | 1      | 3.03%   |
| LDLC SSD 120GB                    | 1        | 1      | 3.03%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 3.03%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 3.03%   |
| Hitachi HDS721075CLA332 752GB     | 1        | 1      | 3.03%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 3.03%   |
| Hitachi HCP725050GLAT80 500GB     | 1        | 1      | 3.03%   |
| Fujitsu MHZ2160BH G2 160GB        | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 14     | 43.75%  |
| WDC                 | 6        | 7      | 18.75%  |
| Maxtor              | 3        | 3      | 9.38%   |
| Kingston            | 2        | 2      | 6.25%   |
| Hitachi             | 2        | 3      | 6.25%   |
| SanDisk             | 1        | 1      | 3.13%   |
| Samsung Electronics | 1        | 1      | 3.13%   |
| ORTIAL              | 1        | 1      | 3.13%   |
| LDLC                | 1        | 1      | 3.13%   |
| Fujitsu             | 1        | 1      | 3.13%   |

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
| HDD  | 23       | 28     | 79.31%  |
| SSD  | 6        | 6      | 20.69%  |

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
| Works    | 77       | 149    | 43.02%  |
| Detected | 73       | 154    | 40.78%  |
| Malfunc  | 27       | 34     | 15.08%  |
| Failed   | 2        | 2      | 1.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 52.54%  |
| AMD                         | 37       | 20.9%   |
| Nvidia                      | 19       | 10.73%  |
| JMicron Technology          | 6        | 3.39%   |
| Marvell Technology Group    | 5        | 2.82%   |
| Samsung Electronics         | 4        | 2.26%   |
| ASMedia Technology          | 4        | 2.26%   |
| VIA Technologies            | 2        | 1.13%   |
| LSI Logic / Symbios Logic   | 2        | 1.13%   |
| Silicon Motion              | 1        | 0.56%   |
| SanDisk                     | 1        | 0.56%   |
| Micron Technology           | 1        | 0.56%   |
| Kingston Technology Company | 1        | 0.56%   |
| ADATA Technology            | 1        | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23       | 9.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 4.47%   |
| Nvidia MCP61 SATA Controller                                                            | 9        | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 3.66%   |
| Nvidia MCP61 IDE                                                                        | 7        | 2.85%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 2.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 2.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 2.44%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 2.44%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 2.03%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 2.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.63%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3        | 1.22%   |
| Nvidia CK804 IDE                                                                        | 3        | 1.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.22%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 1.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.22%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.22%   |
| AMD FCH IDE Controller                                                                  | 3        | 1.22%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.81%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 0.81%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.81%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.81%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 96       | 51.89%  |
| IDE  | 68       | 36.76%  |
| RAID | 11       | 5.95%   |
| NVMe | 8        | 4.32%   |
| SCSI | 2        | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 104      | 65.82%  |
| AMD    | 54       | 34.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 3.8%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 5        | 3.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.9%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.9%    |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.9%    |
| AMD A10-6800K APU with Radeon HD Graphics   | 3        | 1.9%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.27%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.27%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.27%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.27%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.27%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 1.27%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.27%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 2        | 1.27%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.27%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.27%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 2        | 1.27%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 1.27%   |
| AMD Athlon 64 Processor 3000+               | 2        | 1.27%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.63%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.63%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1        | 0.63%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.63%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.63%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.63%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.63%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.63%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.63%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.63%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.63%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.63%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.63%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 14.56%  |
| Intel Core 2 Duo        | 16       | 10.13%  |
| Intel Core i3           | 11       | 6.96%   |
| Intel Atom              | 10       | 6.33%   |
| Intel Core i7           | 8        | 5.06%   |
| Intel Celeron           | 8        | 5.06%   |
| AMD Athlon 64 X2        | 7        | 4.43%   |
| AMD Ryzen 5             | 6        | 3.8%    |
| AMD Athlon II X2        | 6        | 3.8%    |
| Intel Xeon              | 5        | 3.16%   |
| Intel Pentium Dual-Core | 5        | 3.16%   |
| Intel Core 2 Quad       | 5        | 3.16%   |
| Intel Core 2            | 5        | 3.16%   |
| AMD Ryzen 7             | 5        | 3.16%   |
| AMD A10                 | 5        | 3.16%   |
| AMD GX                  | 3        | 1.9%    |
| AMD FX                  | 3        | 1.9%    |
| AMD Athlon 64           | 3        | 1.9%    |
| Intel Pentium Dual      | 2        | 1.27%   |
| Intel Pentium 4         | 2        | 1.27%   |
| Intel Pentium           | 2        | 1.27%   |
| AMD Sempron             | 2        | 1.27%   |
| AMD Ryzen Threadripper  | 2        | 1.27%   |
| AMD Ryzen 3             | 2        | 1.27%   |
| AMD A8                  | 2        | 1.27%   |
| Other                   | 1        | 0.63%   |
| Intel Pentium Gold      | 1        | 0.63%   |
| AMD Quad-Core Opteron   | 1        | 0.63%   |
| AMD Phenom II X6        | 1        | 0.63%   |
| AMD Phenom II X4        | 1        | 0.63%   |
| AMD Phenom II X3        | 1        | 0.63%   |
| AMD Opteron             | 1        | 0.63%   |
| AMD E                   | 1        | 0.63%   |
| AMD Athlon X4           | 1        | 0.63%   |
| AMD Athlon II X4        | 1        | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 74       | 46.84%  |
| 4      | 53       | 33.54%  |
| 6      | 11       | 6.96%   |
| 1      | 9        | 5.7%    |
| 8      | 7        | 4.43%   |
| 64     | 1        | 0.63%   |
| 16     | 1        | 0.63%   |
| 12     | 1        | 0.63%   |
| 3      | 1        | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 156      | 98.73%  |
| 2      | 2        | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 101      | 63.92%  |
| 2      | 57       | 36.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 158      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 15.09%  |
| 0x206a7    | 13       | 8.18%   |
| 0x1067a    | 13       | 8.18%   |
| 0x306c3    | 11       | 6.92%   |
| 0x306a9    | 7        | 4.4%    |
| 0x406c4    | 6        | 3.77%   |
| 0x06001119 | 6        | 3.77%   |
| 0x10676    | 5        | 3.14%   |
| 0x906e9    | 4        | 2.52%   |
| 0x6fd      | 4        | 2.52%   |
| 0x6fb      | 4        | 2.52%   |
| 0x010000c8 | 4        | 2.52%   |
| 0x6f6      | 3        | 1.89%   |
| 0x20655    | 3        | 1.89%   |
| 0x08701021 | 3        | 1.89%   |
| 0x0800820d | 3        | 1.89%   |
| 0x06000852 | 3        | 1.89%   |
| 0xa0653    | 2        | 1.26%   |
| 0x6f2      | 2        | 1.26%   |
| 0x506e3    | 2        | 1.26%   |
| 0x30678    | 2        | 1.26%   |
| 0x206d7    | 2        | 1.26%   |
| 0x106ca    | 2        | 1.26%   |
| 0x0a50000c | 2        | 1.26%   |
| 0x08701013 | 2        | 1.26%   |
| 0x0700010f | 2        | 1.26%   |
| 0x010000c7 | 2        | 1.26%   |
| 0xf65      | 1        | 0.63%   |
| 0xf4a      | 1        | 0.63%   |
| 0xa0671    | 1        | 0.63%   |
| 0xa0655    | 1        | 0.63%   |
| 0x906ea    | 1        | 0.63%   |
| 0x706a1    | 1        | 0.63%   |
| 0x6f7      | 1        | 0.63%   |
| 0x506c9    | 1        | 0.63%   |
| 0x406c3    | 1        | 0.63%   |
| 0x306f2    | 1        | 0.63%   |
| 0x306e4    | 1        | 0.63%   |
| 0x30661    | 1        | 0.63%   |
| 0x106e5    | 1        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 19       | 12.03%  |
| SandyBridge   | 16       | 10.13%  |
| Haswell       | 14       | 8.86%   |
| Core          | 14       | 8.86%   |
| K8 Hammer     | 12       | 7.59%   |
| K10           | 12       | 7.59%   |
| Silvermont    | 9        | 5.7%    |
| Piledriver    | 9        | 5.7%    |
| IvyBridge     | 8        | 5.06%   |
| Zen 2         | 7        | 4.43%   |
| Zen+          | 6        | 3.8%    |
| KabyLake      | 5        | 3.16%   |
| CometLake     | 4        | 2.53%   |
| Westmere      | 3        | 1.9%    |
| Skylake       | 3        | 1.9%    |
| Jaguar        | 3        | 1.9%    |
| Bonnell       | 3        | 1.9%    |
| Zen 3         | 2        | 1.27%   |
| NetBurst      | 2        | 1.27%   |
| Steamroller   | 1        | 0.63%   |
| Nehalem       | 1        | 0.63%   |
| K10 Llano     | 1        | 0.63%   |
| Icelake       | 1        | 0.63%   |
| Goldmont plus | 1        | 0.63%   |
| Goldmont      | 1        | 0.63%   |
| Bobcat        | 1        | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 59       | 35.98%  |
| Intel  | 59       | 35.98%  |
| AMD    | 46       | 28.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 5.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7        | 4.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 3.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 3.51%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 3.51%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5        | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 2.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.34%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 2.34%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 2.34%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4        | 2.34%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 3        | 1.75%   |
| Intel HD Graphics 530                                                                    | 3        | 1.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 1.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.17%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 1.17%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.17%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 1.17%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.17%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 1.17%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 1.17%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 1.17%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.17%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.17%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2        | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.17%   |
| Nvidia TU117 [GeForce GTX 1630]                                                          | 1        | 0.58%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.58%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.58%   |
| Nvidia NV43GL [Quadro FX 540]                                                            | 1        | 0.58%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1        | 0.58%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.58%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.58%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.58%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 56       | 35.22%  |
| 1 x Intel    | 56       | 35.22%  |
| 1 x AMD      | 40       | 25.16%  |
| 2 x AMD      | 4        | 2.52%   |
| 2 x Nvidia   | 1        | 0.63%   |
| Intel + AMD  | 1        | 0.63%   |
| AMD + Nvidia | 1        | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 127      | 80.38%  |
| Proprietary | 29       | 18.35%  |
| Unknown     | 2        | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 39.62%  |
| 0.01-0.5   | 40       | 25.16%  |
| 0.51-1.0   | 24       | 15.09%  |
| 1.01-2.0   | 16       | 10.06%  |
| 3.01-4.0   | 10       | 6.29%   |
| 7.01-8.0   | 3        | 1.89%   |
| 8.01-16.0  | 2        | 1.26%   |
| 2.01-3.0   | 1        | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 22       | 14.38%  |
| Dell                    | 22       | 14.38%  |
| Goldstar                | 14       | 9.15%   |
| Acer                    | 12       | 7.84%   |
| Hewlett-Packard         | 9        | 5.88%   |
| Philips                 | 7        | 4.58%   |
| Iiyama                  | 7        | 4.58%   |
| BenQ                    | 7        | 4.58%   |
| Lenovo                  | 5        | 3.27%   |
| Vizio                   | 4        | 2.61%   |
| Ancor Communications    | 4        | 2.61%   |
| Unknown                 | 3        | 1.96%   |
| AOC                     | 3        | 1.96%   |
| Sony                    | 2        | 1.31%   |
| LG Electronics          | 2        | 1.31%   |
| IOD                     | 2        | 1.31%   |
| Fujitsu Siemens         | 2        | 1.31%   |
| FL_                     | 2        | 1.31%   |
| Compaq Computer         | 2        | 1.31%   |
| ___                     | 1        | 0.65%   |
| ViewSonic               | 1        | 0.65%   |
| Unknown (ADA)           | 1        | 0.65%   |
| SHD                     | 1        | 0.65%   |
| Sceptre Tech            | 1        | 0.65%   |
| RS                      | 1        | 0.65%   |
| Proview                 | 1        | 0.65%   |
| Plain Tree Systems      | 1        | 0.65%   |
| NEC Computers           | 1        | 0.65%   |
| MOT                     | 1        | 0.65%   |
| Lite-On                 | 1        | 0.65%   |
| LG Display              | 1        | 0.65%   |
| Lenovo Group Limited    | 1        | 0.65%   |
| IBM                     | 1        | 0.65%   |
| Hitachi                 | 1        | 0.65%   |
| HannStar                | 1        | 0.65%   |
| GDH                     | 1        | 0.65%   |
| Element                 | 1        | 0.65%   |
| CVT                     | 1        | 0.65%   |
| Chi Mei Optoelectronics | 1        | 0.65%   |
| Belinea                 | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 1.27%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 1.27%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                 | 2        | 1.27%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2        | 1.27%   |
| FL_ HDMI4K FL_2801 2560x1440 480x270mm 21.7-inch                      | 2        | 1.27%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 1.27%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 2        | 1.27%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 1.27%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.63%   |
| ___ LCD TV ___0101 1920x1080                                          | 1        | 0.63%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                 | 1        | 0.63%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.63%   |
| Vizio E421VO VIZ0090 1920x1080 930x530mm 42.1-inch                    | 1        | 0.63%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 1        | 0.63%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch              | 1        | 0.63%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.63%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.63%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.63%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.63%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.63%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.63%   |
| Sony TV SNYAA01 1920x1080 880x490mm 39.7-inch                         | 1        | 0.63%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.63%   |
| SHD 701Lite SHD02BD 1920x1080 110x62mm 5.0-inch                       | 1        | 0.63%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1        | 0.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.63%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x290mm 23.1-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x257mm 19.1-inch   | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM0218 1280x1024 376x301mm 19.0-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1        | 0.63%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.63%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 50       | 32.47%  |
| 1280x1024 (SXGA)   | 27       | 17.53%  |
| 1680x1050 (WSXGA+) | 20       | 12.99%  |
| 1366x768 (WXGA)    | 11       | 7.14%   |
| 1440x900 (WXGA+)   | 10       | 6.49%   |
| 2560x1440 (QHD)    | 8        | 5.19%   |
| 1024x768 (XGA)     | 6        | 3.9%    |
| 3840x2160 (4K)     | 5        | 3.25%   |
| 1600x900 (HD+)     | 3        | 1.95%   |
| 3440x1440          | 2        | 1.3%    |
| 2560x1080          | 2        | 1.3%    |
| 1600x1200          | 2        | 1.3%    |
| 1280x800 (WXGA)    | 2        | 1.3%    |
| 3600x1200          | 1        | 0.65%   |
| 2560x1600          | 1        | 0.65%   |
| 2288x1287          | 1        | 0.65%   |
| 1920x1200 (WUXGA)  | 1        | 0.65%   |
| 1360x768           | 1        | 0.65%   |
| Unknown            | 1        | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 17       | 11.26%  |
| 23      | 16       | 10.6%   |
| 19      | 15       | 9.93%   |
| 24      | 12       | 7.95%   |
| 21      | 12       | 7.95%   |
| Unknown | 12       | 7.95%   |
| 27      | 11       | 7.28%   |
| 22      | 11       | 7.28%   |
| 20      | 10       | 6.62%   |
| 18      | 7        | 4.64%   |
| 15      | 7        | 4.64%   |
| 34      | 3        | 1.99%   |
| 47      | 2        | 1.32%   |
| 39      | 2        | 1.32%   |
| 31      | 2        | 1.32%   |
| 84      | 1        | 0.66%   |
| 72      | 1        | 0.66%   |
| 52      | 1        | 0.66%   |
| 48      | 1        | 0.66%   |
| 41      | 1        | 0.66%   |
| 40      | 1        | 0.66%   |
| 38      | 1        | 0.66%   |
| 29      | 1        | 0.66%   |
| 14      | 1        | 0.66%   |
| 11      | 1        | 0.66%   |
| 7       | 1        | 0.66%   |
| 5       | 1        | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 45       | 30%     |
| 501-600     | 38       | 25.33%  |
| 301-350     | 23       | 15.33%  |
| Unknown     | 12       | 8%      |
| 351-400     | 11       | 7.33%   |
| 801-900     | 4        | 2.67%   |
| 601-700     | 4        | 2.67%   |
| 1001-1500   | 4        | 2.67%   |
| 701-800     | 3        | 2%      |
| 1501-2000   | 2        | 1.33%   |
| 101-200     | 2        | 1.33%   |
| 201-300     | 1        | 0.67%   |
| 901-1000    | 1        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 73       | 49.32%  |
| 16/10   | 26       | 17.57%  |
| 5/4     | 25       | 16.89%  |
| Unknown | 10       | 6.76%   |
| 4/3     | 7        | 4.73%   |
| 21/9    | 4        | 2.7%    |
| 6/5     | 2        | 1.35%   |
| 3/2     | 1        | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 45       | 30.2%   |
| 151-200        | 29       | 19.46%  |
| 141-150        | 21       | 14.09%  |
| 301-350        | 12       | 8.05%   |
| Unknown        | 12       | 8.05%   |
| 101-110        | 7        | 4.7%    |
| 501-1000       | 7        | 4.7%    |
| 351-500        | 5        | 3.36%   |
| More than 1000 | 4        | 2.68%   |
| 1-40           | 2        | 1.34%   |
| 251-300        | 2        | 1.34%   |
| 81-90          | 1        | 0.67%   |
| 51-60          | 1        | 0.67%   |
| 131-140        | 1        | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 102      | 69.86%  |
| 101-120       | 18       | 12.33%  |
| Unknown       | 12       | 8.22%   |
| 121-160       | 7        | 4.79%   |
| 1-50          | 5        | 3.42%   |
| More than 240 | 1        | 0.68%   |
| 161-240       | 1        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 87.34%  |
| 2     | 13       | 8.23%   |
| 0     | 5        | 3.16%   |
| 4     | 1        | 0.63%   |
| 3     | 1        | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 96       | 42.86%  |
| Intel                    | 52       | 23.21%  |
| Nvidia                   | 16       | 7.14%   |
| Ralink Technology        | 13       | 5.8%    |
| Qualcomm Atheros         | 13       | 5.8%    |
| Ralink                   | 6        | 2.68%   |
| Broadcom                 | 5        | 2.23%   |
| Marvell Technology Group | 4        | 1.79%   |
| Broadcom Limited         | 3        | 1.34%   |
| TP-Link                  | 2        | 0.89%   |
| Samsung Electronics      | 2        | 0.89%   |
| ZyXEL Communications     | 1        | 0.45%   |
| VIA Technologies         | 1        | 0.45%   |
| U-Blox                   | 1        | 0.45%   |
| Sitecom Europe           | 1        | 0.45%   |
| NetGear                  | 1        | 0.45%   |
| Logitec                  | 1        | 0.45%   |
| Huawei Technologies      | 1        | 0.45%   |
| Belkin Components        | 1        | 0.45%   |
| ASIX Electronics         | 1        | 0.45%   |
| Aquantia                 | 1        | 0.45%   |
| ADMtek                   | 1        | 0.45%   |
| Accton Technology        | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70       | 29.05%  |
| Nvidia MCP61 Ethernet                                             | 9        | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 2.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 2.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 2.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.66%   |
| Ralink RT5572 Wireless Adapter                                    | 4        | 1.66%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.66%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 1.66%   |
| Realtek RTL8187 Wireless Adapter                                  | 3        | 1.24%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 1.24%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.24%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.83%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.83%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.83%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.83%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.83%   |
| Intel Wireless-AC 9260                                            | 2        | 0.83%   |
| Intel Wireless 7260                                               | 2        | 0.83%   |
| Intel Wireless 3165                                               | 2        | 0.83%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.83%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.83%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.41%   |
| U-Blox GNSS receiver                                              | 1        | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.41%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                   | 1        | 0.41%   |
| Realtek RTL8812AU-VS 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 17       | 25%     |
| Ralink Technology        | 13       | 19.12%  |
| Intel                    | 13       | 19.12%  |
| Qualcomm Atheros         | 8        | 11.76%  |
| Ralink                   | 6        | 8.82%   |
| TP-Link                  | 2        | 2.94%   |
| Broadcom                 | 2        | 2.94%   |
| ZyXEL Communications     | 1        | 1.47%   |
| Sitecom Europe           | 1        | 1.47%   |
| NetGear                  | 1        | 1.47%   |
| Marvell Technology Group | 1        | 1.47%   |
| Logitec                  | 1        | 1.47%   |
| Broadcom Limited         | 1        | 1.47%   |
| Belkin Components        | 1        | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 7.35%   |
| Ralink RT5572 Wireless Adapter                                 | 4        | 5.88%   |
| Ralink MT7601U Wireless Adapter                                | 4        | 5.88%   |
| Realtek RTL8187 Wireless Adapter                               | 3        | 4.41%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 3        | 4.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 2.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 2.94%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 2.94%   |
| Intel Wireless-AC 9260                                         | 2        | 2.94%   |
| Intel Wireless 7260                                            | 2        | 2.94%   |
| Intel Wireless 3165                                            | 2        | 2.94%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 1.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 1.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 1.47%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                | 1        | 1.47%   |
| Realtek RTL8812AU-VS 802.11a/b/g/n/ac 2T2R DB WLAN Adapter     | 1        | 1.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 1.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 1.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 1.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 1.47%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1        | 1.47%   |
| Ralink RT5372 Wireless Adapter                                 | 1        | 1.47%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 1.47%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1        | 1.47%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.47%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 1.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 1.47%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 1.47%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 1.47%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless            | 1        | 1.47%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                      | 1        | 1.47%   |
| Intel Wireless 7265                                            | 1        | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 84       | 50.91%  |
| Intel                    | 42       | 25.45%  |
| Nvidia                   | 16       | 9.7%    |
| Qualcomm Atheros         | 6        | 3.64%   |
| Broadcom                 | 4        | 2.42%   |
| Marvell Technology Group | 3        | 1.82%   |
| Samsung Electronics      | 2        | 1.21%   |
| Broadcom Limited         | 2        | 1.21%   |
| VIA Technologies         | 1        | 0.61%   |
| Huawei Technologies      | 1        | 0.61%   |
| ASIX Electronics         | 1        | 0.61%   |
| Aquantia                 | 1        | 0.61%   |
| ADMtek                   | 1        | 0.61%   |
| Accton Technology        | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70       | 40.7%   |
| Nvidia MCP61 Ethernet                                             | 9        | 5.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 3.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 3.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.74%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.74%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.16%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.16%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.16%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.16%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 1.16%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.58%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.58%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.58%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.58%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.58%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.58%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.58%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.58%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.58%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.58%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 1        | 0.58%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 157      | 70.09%  |
| WiFi     | 66       | 29.46%  |
| Modem    | 1        | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 128      | 77.58%  |
| WiFi     | 37       | 22.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 72.78%  |
| 2     | 37       | 23.42%  |
| 3     | 5        | 3.16%   |
| 0     | 1        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 76.73%  |
| Yes  | 37       | 23.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 36.67%  |
| Cambridge Silicon Radio | 9        | 30%     |
| Broadcom                | 4        | 13.33%  |
| ASUSTek Computer        | 2        | 6.67%   |
| Ralink                  | 1        | 3.33%   |
| Logitech                | 1        | 3.33%   |
| Lite-On Technology      | 1        | 3.33%   |
| Hewlett-Packard         | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 30%     |
| Intel Bluetooth wireless interface                  | 5        | 16.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 6.67%   |
| Ralink RT3290 Bluetooth                             | 1        | 3.33%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 3.33%   |
| Lite-On Bluetooth Device                            | 1        | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 3.33%   |
| Intel AX210 Bluetooth                               | 1        | 3.33%   |
| Intel AX201 Bluetooth                               | 1        | 3.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 3.33%   |
| Broadcom Bluetooth Device                           | 1        | 3.33%   |
| Broadcom BCM20702A0                                 | 1        | 3.33%   |
| ASUS BCM20702A0                                     | 1        | 3.33%   |
| ASUS ASUS USB-BT500                                 | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 92       | 41.63%  |
| Nvidia                   | 56       | 25.34%  |
| AMD                      | 53       | 23.98%  |
| Creative Labs            | 4        | 1.81%   |
| C-Media Electronics      | 4        | 1.81%   |
| XMOS                     | 3        | 1.36%   |
| VIA Technologies         | 1        | 0.45%   |
| Texas Instruments        | 1        | 0.45%   |
| Setek Elektronik         | 1        | 0.45%   |
| Logitech                 | 1        | 0.45%   |
| GN Netcom                | 1        | 0.45%   |
| Focusrite-Novation       | 1        | 0.45%   |
| Creative Technology      | 1        | 0.45%   |
| ASUSTek Computer         | 1        | 0.45%   |
| Asahi Kasei Microsystems | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 14       | 5.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12       | 4.74%   |
| Nvidia High Definition Audio Controller                                           | 11       | 4.35%   |
| AMD FCH Azalia Controller                                                         | 11       | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10       | 3.95%   |
| Nvidia MCP61 High Definition Audio                                                | 9        | 3.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 9        | 3.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 3.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 2.77%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 2.37%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5        | 1.98%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 5        | 1.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 1.58%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 1.58%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.58%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 1.58%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 1.58%   |
| XMOS Mayfield Audio                                                               | 3        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 1.19%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.19%   |
| Nvidia MCP51 High Definition Audio                                                | 2        | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.79%   |
| Nvidia CK804 AC'97 Audio Controller                                               | 2        | 0.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 2        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 0.79%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 0.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 23       | 19.33%  |
| Samsung Electronics | 20       | 16.81%  |
| SK hynix            | 18       | 15.13%  |
| Kingston            | 11       | 9.24%   |
| G.Skill             | 8        | 6.72%   |
| Crucial             | 7        | 5.88%   |
| Corsair             | 6        | 5.04%   |
| Micron Technology   | 5        | 4.2%    |
| Nanya Technology    | 4        | 3.36%   |
| Unknown (ABCD)      | 2        | 1.68%   |
| Timetec             | 2        | 1.68%   |
| Patriot             | 2        | 1.68%   |
| Elpida              | 2        | 1.68%   |
| Unifosa             | 1        | 0.84%   |
| Team                | 1        | 0.84%   |
| Ramaxel Technology  | 1        | 0.84%   |
| Qimonda             | 1        | 0.84%   |
| PNY                 | 1        | 0.84%   |
| e2e4                | 1        | 0.84%   |
| Avant               | 1        | 0.84%   |
| 48spaces            | 1        | 0.84%   |
| Unknown             | 1        | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                     | 5        | 3.91%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 2        | 1.56%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                            | 2        | 1.56%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2        | 1.56%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                     | 2        | 1.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s               | 2        | 1.56%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s             | 2        | 1.56%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                      | 1        | 0.78%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                            | 1        | 0.78%   |
| Unknown RAM Module 512MB DIMM 400MT/s                             | 1        | 0.78%   |
| Unknown RAM Module 512MB DIMM 333MT/s                             | 1        | 0.78%   |
| Unknown RAM Module 4GB DIMM 400MT/s                               | 1        | 0.78%   |
| Unknown RAM Module 4096MB DIMM SDRAM                              | 1        | 0.78%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                      | 1        | 0.78%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                      | 1        | 0.78%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                           | 1        | 0.78%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1        | 0.78%   |
| Unknown RAM Module 2048MB DIMM DDR2                               | 1        | 0.78%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                            | 1        | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                     | 1        | 0.78%   |
| Unknown RAM Module 1024MB DIMM SDRAM                              | 1        | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                       | 1        | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                       | 1        | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2                               | 1        | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                        | 1        | 0.78%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s              | 1        | 0.78%   |
| Timetec RAM UD3-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.78%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                     | 1        | 0.78%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s                | 1        | 0.78%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                     | 1        | 0.78%   |
| SK hynix RAM HYMP525P72CP4-Y5 2048MB DIMM DDR2 667MT/s            | 1        | 0.78%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s             | 1        | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1        | 0.78%   |
| SK hynix RAM HMT451R7AFR8C-RD 4GB DIMM DDR3 1866MT/s              | 1        | 0.78%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s              | 1        | 0.78%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1        | 0.78%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s              | 1        | 0.78%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s            | 1        | 0.78%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s           | 1        | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 43       | 39.45%  |
| DDR4    | 21       | 19.27%  |
| DDR2    | 17       | 15.6%   |
| SDRAM   | 14       | 12.84%  |
| Unknown | 10       | 9.17%   |
| LPDDR4  | 2        | 1.83%   |
| DDR     | 2        | 1.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 90       | 87.38%  |
| SODIMM | 13       | 12.62%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 34       | 30.91%  |
| 8192  | 25       | 22.73%  |
| 4096  | 24       | 21.82%  |
| 1024  | 12       | 10.91%  |
| 16384 | 8        | 7.27%   |
| 32768 | 3        | 2.73%   |
| 512   | 3        | 2.73%   |
| 65536 | 1        | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 20.69%  |
| 1333    | 12       | 10.34%  |
| 800     | 11       | 9.48%   |
| 2133    | 8        | 6.9%    |
| 1066    | 6        | 5.17%   |
| 667     | 6        | 5.17%   |
| 400     | 6        | 5.17%   |
| 2400    | 5        | 4.31%   |
| Unknown | 5        | 4.31%   |
| 3200    | 4        | 3.45%   |
| 2048    | 4        | 3.45%   |
| 1866    | 4        | 3.45%   |
| 1867    | 3        | 2.59%   |
| 3600    | 2        | 1.72%   |
| 3000    | 2        | 1.72%   |
| 2733    | 2        | 1.72%   |
| 2667    | 2        | 1.72%   |
| 533     | 2        | 1.72%   |
| 49926   | 1        | 0.86%   |
| 3933    | 1        | 0.86%   |
| 3866    | 1        | 0.86%   |
| 3066    | 1        | 0.86%   |
| 2933    | 1        | 0.86%   |
| 1639    | 1        | 0.86%   |
| 1334    | 1        | 0.86%   |
| 333     | 1        | 0.86%   |

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
| Logitech                      | 5        | 25%     |
| Sunplus Innovation Technology | 2        | 10%     |
| Generalplus Technology        | 2        | 10%     |
| Chicony Electronics           | 2        | 10%     |
| Z-Star Microelectronics       | 1        | 5%      |
| SunplusIT                     | 1        | 5%      |
| Samsung Electronics           | 1        | 5%      |
| Microsoft                     | 1        | 5%      |
| KYE Systems (Mouse Systems)   | 1        | 5%      |
| Guillemot                     | 1        | 5%      |
| Genesys Logic                 | 1        | 5%      |
| Bison Electronics             | 1        | 5%      |
| ARC International             | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 2        | 10%     |
| Generalplus GENERAL WEBCAM                | 2        | 10%     |
| Z-Star Sirius USB2.0 Camera               | 1        | 5%      |
| SunplusIT USB 2.0 Camera                  | 1        | 5%      |
| Sunplus WEBCAM ESSENTIELB W1              | 1        | 5%      |
| Sunplus FHD Camera                        | 1        | 5%      |
| Samsung Galaxy series, misc. (MTP mode)   | 1        | 5%      |
| Microsoft LifeCam HD-3000                 | 1        | 5%      |
| Logitech Webcam B500                      | 1        | 5%      |
| Logitech QuickCam Zoom                    | 1        | 5%      |
| Logitech HD Webcam C525                   | 1        | 5%      |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 5%      |
| Guillemot Hercules HD Sunset              | 1        | 5%      |
| Genesys Logic Camera                      | 1        | 5%      |
| Chicony CNF7042                           | 1        | 5%      |
| Chicony ASUS USB2.0 Webcam                | 1        | 5%      |
| Bison Integrated Camera                   | 1        | 5%      |
| ARC International Camera                  | 1        | 5%      |

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
| 0     | 132      | 83.54%  |
| 1     | 23       | 14.56%  |
| 2     | 3        | 1.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 26.92%  |
| Net/wireless             | 5        | 19.23%  |
| Communication controller | 4        | 15.38%  |
| Sound                    | 3        | 11.54%  |
| Unassigned class         | 2        | 7.69%   |
| Dvb card                 | 2        | 7.69%   |
| Net/ethernet             | 1        | 3.85%   |
| Multimedia controller    | 1        | 3.85%   |
| Bluetooth                | 1        | 3.85%   |

