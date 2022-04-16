Lubuntu - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 430

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASRock        | G31M-S                      | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Unknown       | Unknown                     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| ASUSTek       | M4N68T-M LE                 | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| ASRock        | Q1900M                      | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| ASUSTek       | M2N-SLI                     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| HP            | 339A                        | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 2AF7                        | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Dell          | 0DR845                      | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Pegatron      | Narra6                      | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| ASUSTek       | Puffer                      | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Gigabyte      | B450M S2H                   | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Dell          | 0TW904 A01                  | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| Unknown       | K8Upgrade-1689              | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| ASRock        | B450M Pro4 R2.0             | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| Acer          | WG43M                       | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| ASUSTek       | P8P67 DELUXE                | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| Dell          | 032W55 A03                  | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Biostar       | A68N-2100                   | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| ASUSTek       | A8N5X                       | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| HP            | 090Ch                       | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| AMI           | Cherry Trail Tablet         | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Dell          | 0J3C2F A02                  | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6719bb7131](https://linux-hardware.org/?probe=6719bb7131) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| ASUSTek       | CM1435                      | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | G31M-S2C                    | [0598f63a64](https://linux-hardware.org/?probe=0598f63a64) | Nov 25, 2021 |
| Gigabyte      | G31M-S2C                    | [4528ddf31d](https://linux-hardware.org/?probe=4528ddf31d) | Nov 25, 2021 |
| MSI           | Boston                      | [71b7b63020](https://linux-hardware.org/?probe=71b7b63020) | Nov 25, 2021 |
| Gigabyte      | A520I AC                    | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Acer          | Aspire XC600 v1.0           | [2f1bc07165](https://linux-hardware.org/?probe=2f1bc07165) | Nov 17, 2021 |
| Dell          | 0T568R A00                  | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Acer          | Aspire X1700                | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Acer          | Aspire X1700                | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Foxconn       | 2AA9h                       | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Medion        | MS-7728                     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| ASUSTek       | PRIME H410M-E               | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| MSI           | MS-7309                     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| ASUSTek       | H170M-PLUS                  | [15969208ae](https://linux-hardware.org/?probe=15969208ae) | Oct 18, 2021 |
| Unknown       | X99-D8                      | [e335225bdb](https://linux-hardware.org/?probe=e335225bdb) | Oct 17, 2021 |
| AAEON         | MF-001 V1.0                 | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| Acer          | Aspire X1700                | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | [acbc75f1b8](https://linux-hardware.org/?probe=acbc75f1b8) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| Gigabyte      | P35-DS3L                    | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| Pegatron      | Acacia                      | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| ZOTAC         | NM10                        | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Foxconn       | Priv                        | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| ASRock        | Z590M-ITX/ax                | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASUSTek       | P6T SE                      | [b50449f73f](https://linux-hardware.org/?probe=b50449f73f) | Sep 14, 2021 |
| Dell          | 0M5DCD A00                  | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| MSI           | AMETHYST-M                  | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| MSI           | AMETHYST-M                  | [e6c4f7b650](https://linux-hardware.org/?probe=e6c4f7b650) | Aug 30, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [0fa53c65bb](https://linux-hardware.org/?probe=0fa53c65bb) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| MSI           | Boston                      | [d706f54222](https://linux-hardware.org/?probe=d706f54222) | Aug 16, 2021 |
| MSI           | Boston                      | [2a5e7f9687](https://linux-hardware.org/?probe=2a5e7f9687) | Aug 12, 2021 |
| MSI           | Boston                      | [c61c0e3351](https://linux-hardware.org/?probe=c61c0e3351) | Aug 05, 2021 |
| HP            | 8299                        | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| Huanan        | X99-TF V2.0                 | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| ASUSTek       | H110M-A/M.2                 | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| Intel         | DG965SS AAD41678-307        | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |
| HP            | 1495                        | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| HP            | 0A1Ch E                     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Gigabyte      | Z77X-UD3H                   | [572b814c9a](https://linux-hardware.org/?probe=572b814c9a) | Jul 11, 2021 |
| HP            | 3397                        | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| Positivo      | POS-MI945AA                 | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| ASUSTek       | P5K                         | [11fed8f8ae](https://linux-hardware.org/?probe=11fed8f8ae) | Jul 03, 2021 |
| Biostar       | A68N-2100                   | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Dell          | 0TW904 A01                  | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Intel         | DG41WV AAE90316-102         | [c04c0fcc65](https://linux-hardware.org/?probe=c04c0fcc65) | Jun 25, 2021 |
| Gigabyte      | B550M AORUS PRO             | [5d8e8c301f](https://linux-hardware.org/?probe=5d8e8c301f) | Jun 24, 2021 |
| IBM           | 8183V6D                     | [d5c4e8c76b](https://linux-hardware.org/?probe=d5c4e8c76b) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| Gigabyte      | B550M AORUS PRO             | [b14314b1d4](https://linux-hardware.org/?probe=b14314b1d4) | Jun 12, 2021 |
| ASUSTek       | PRIME H410M-E               | [0eb8caf654](https://linux-hardware.org/?probe=0eb8caf654) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f4ce6e2f6a](https://linux-hardware.org/?probe=f4ce6e2f6a) | Jun 02, 2021 |
| MSI           | B350M GAMING PRO            | [52c67d407d](https://linux-hardware.org/?probe=52c67d407d) | May 31, 2021 |
| ASUSTek       | K8N                         | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| HP            | 09C4h                       | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| HP            | 21B4 A01                    | [b2a7cbbc72](https://linux-hardware.org/?probe=b2a7cbbc72) | May 23, 2021 |
| Dell          | 0HY175 A03                  | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Dell          | 0D441T A03                  | [c23a919651](https://linux-hardware.org/?probe=c23a919651) | May 18, 2021 |
| MSI           | H61M-E33                    | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ASUSTek       | K8N                         | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| Unknown       | Unknown                     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | H110I-PLUS                  | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| IBM           | 8183V6D                     | [0df40278d1](https://linux-hardware.org/?probe=0df40278d1) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| AAEON         | MF-001 V1.0                 | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | imedia S1350                | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| ASRock        | FM2A88M Extreme4+           | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| Intel         | SHARKBAY                    | [cf6ec831df](https://linux-hardware.org/?probe=cf6ec831df) | Apr 25, 2021 |
| ASUSTek       | P5Q DELUXE                  | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Intel         | DX58SO AAE29331-404         | [e4f384c278](https://linux-hardware.org/?probe=e4f384c278) | Apr 24, 2021 |
| ASUSTek       | H110M-A/M.2                 | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| Intel         | D525MW AAE93082-401         | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| ASUSTek       | P7P55 LX                    | [219757d806](https://linux-hardware.org/?probe=219757d806) | Apr 11, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| MSI           | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP            | 1589                        | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| HP            | 8054                        | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| ASUSTek       | Z97-K                       | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Dell          | 09M8Y8 A01                  | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| ASRock        | N68C-S UCC                  | [8ae162d330](https://linux-hardware.org/?probe=8ae162d330) | Mar 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASRock        | N68C-S UCC                  | [e099627755](https://linux-hardware.org/?probe=e099627755) | Mar 15, 2021 |
| ASRock        | N68C-S UCC                  | [2abee1f31e](https://linux-hardware.org/?probe=2abee1f31e) | Mar 14, 2021 |
| ASRock        | 775Dual-VSTA                | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| MSI           | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| Gigabyte      | H81M-DS2                    | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | [47d5daa739](https://linux-hardware.org/?probe=47d5daa739) | Feb 25, 2021 |
| ASRock        | 775VM800                    | [5b04151216](https://linux-hardware.org/?probe=5b04151216) | Feb 15, 2021 |
| ASRock        | 775VM800                    | [d292f6ac7b](https://linux-hardware.org/?probe=d292f6ac7b) | Feb 12, 2021 |
| Intel         | ChiefRiver                  | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| Intel         | D945GTP AAC97834-305        | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | M2A-MX                      | [1541b0dbe1](https://linux-hardware.org/?probe=1541b0dbe1) | Feb 09, 2021 |
| ASUSTek       | M2A-MX                      | [391d63e436](https://linux-hardware.org/?probe=391d63e436) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [7c78d0efc3](https://linux-hardware.org/?probe=7c78d0efc3) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [beddd7c01d](https://linux-hardware.org/?probe=beddd7c01d) | Feb 09, 2021 |
| ASUSTek       | P5G41T-M LE                 | [f08dd9c298](https://linux-hardware.org/?probe=f08dd9c298) | Feb 08, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | [a8af34d0ee](https://linux-hardware.org/?probe=a8af34d0ee) | Feb 08, 2021 |
| ASUSTek       | P5G41T-M LE                 | [32061cad93](https://linux-hardware.org/?probe=32061cad93) | Feb 08, 2021 |
| HP            | 3048h                       | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Gigabyte      | B550M AORUS PRO             | [0528f0d3fa](https://linux-hardware.org/?probe=0528f0d3fa) | Jan 28, 2021 |
| Gigabyte      | B550M AORUS PRO             | [8b9ca2262c](https://linux-hardware.org/?probe=8b9ca2262c) | Jan 28, 2021 |
| Dell          | 0TP406                      | [8d298a20d5](https://linux-hardware.org/?probe=8d298a20d5) | Jan 28, 2021 |
| Lenovo        | ThinkCentre XXXX 9632AU8    | [cdc139f77e](https://linux-hardware.org/?probe=cdc139f77e) | Jan 24, 2021 |
| MSI           | MS-7270                     | [9e5fa11934](https://linux-hardware.org/?probe=9e5fa11934) | Jan 24, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [fdc50253da](https://linux-hardware.org/?probe=fdc50253da) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [3761191ef4](https://linux-hardware.org/?probe=3761191ef4) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [5446971c89](https://linux-hardware.org/?probe=5446971c89) | Jan 20, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [71a9d08996](https://linux-hardware.org/?probe=71a9d08996) | Jan 14, 2021 |
| MSI           | AMETHYST-M                  | [057c04b2ae](https://linux-hardware.org/?probe=057c04b2ae) | Jan 11, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [55f1890303](https://linux-hardware.org/?probe=55f1890303) | Jan 11, 2021 |
| Pegatron      | NARRA3                      | [ebb1428c72](https://linux-hardware.org/?probe=ebb1428c72) | Jan 11, 2021 |
| ASUSTek       | P8Z68-V LX                  | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| Gigabyte      | Z77N-WIFI                   | [653ea393e6](https://linux-hardware.org/?probe=653ea393e6) | Jan 06, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| AMI           | Cherry Trail CR             | [4fe52138ff](https://linux-hardware.org/?probe=4fe52138ff) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | [d86f56eaf3](https://linux-hardware.org/?probe=d86f56eaf3) | Jan 04, 2021 |
| MSI           | MS-7250                     | [72950b548d](https://linux-hardware.org/?probe=72950b548d) | Jan 04, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [48edae2fa9](https://linux-hardware.org/?probe=48edae2fa9) | Jan 04, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [73f8eb43d6](https://linux-hardware.org/?probe=73f8eb43d6) | Jan 01, 2021 |
| Gigabyte      | H81M-HD3                    | [5df1b1d371](https://linux-hardware.org/?probe=5df1b1d371) | Dec 30, 2020 |
| Gigabyte      | B550M AORUS PRO             | [c9e03e6b85](https://linux-hardware.org/?probe=c9e03e6b85) | Dec 25, 2020 |
| ASRock        | FM2A88X Pro3+               | [a57902b2df](https://linux-hardware.org/?probe=a57902b2df) | Dec 23, 2020 |
| Lenovo        | Board                       | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | [cdc016f9d1](https://linux-hardware.org/?probe=cdc016f9d1) | Dec 18, 2020 |
| HP            | 3031h                       | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [43ba858067](https://linux-hardware.org/?probe=43ba858067) | Dec 16, 2020 |
| Dell          | 0WG864                      | [f45926d7a7](https://linux-hardware.org/?probe=f45926d7a7) | Dec 11, 2020 |
| Dell          | 0WG864                      | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gigabyte      | H77M-D3H                    | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| ASRock        | FM2A85X Extreme6            | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | [19e0a468d5](https://linux-hardware.org/?probe=19e0a468d5) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | [c76fe73c42](https://linux-hardware.org/?probe=c76fe73c42) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [174de8e1d6](https://linux-hardware.org/?probe=174de8e1d6) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [7b85d35e4d](https://linux-hardware.org/?probe=7b85d35e4d) | Nov 29, 2020 |
| MSI           | P55-GD80                    | [409cb71474](https://linux-hardware.org/?probe=409cb71474) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | 2820h                       | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [63776843ec](https://linux-hardware.org/?probe=63776843ec) | Nov 21, 2020 |
| Pegatron      | Narra6                      | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| MSI           | MS-7250                     | [8f408a7fec](https://linux-hardware.org/?probe=8f408a7fec) | Nov 17, 2020 |
| HP            | 09F8h                       | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| Foxconn       | 2AA9                        | [dbe623f2ad](https://linux-hardware.org/?probe=dbe623f2ad) | Nov 14, 2020 |
| ECS           | Iris8                       | [1614d7d736](https://linux-hardware.org/?probe=1614d7d736) | Nov 14, 2020 |
| IBM           | 8183V6D                     | [7784e64311](https://linux-hardware.org/?probe=7784e64311) | Nov 14, 2020 |
| ECS           | Iris8                       | [c2d76cebd4](https://linux-hardware.org/?probe=c2d76cebd4) | Nov 14, 2020 |
| MSI           | G41M-P28                    | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| ASRock        | 4Core1600-GLAN              | [e6edfc8360](https://linux-hardware.org/?probe=e6edfc8360) | Nov 06, 2020 |
| ASRock        | 4Core1600-GLAN              | [2139a80238](https://linux-hardware.org/?probe=2139a80238) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| IBM           | 8183V6D                     | [440a6a1057](https://linux-hardware.org/?probe=440a6a1057) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Dell          | 0J3C2F A02                  | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| ASRock        | G41M-GS3                    | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| Biostar       | A68N-2100                   | [116ce8b261](https://linux-hardware.org/?probe=116ce8b261) | Oct 20, 2020 |
| ASUSTek       | P5S800-VM                   | [abb4e0e0c2](https://linux-hardware.org/?probe=abb4e0e0c2) | Oct 17, 2020 |
| ASUSTek       | PRIME H310M-K               | [706aa7bb74](https://linux-hardware.org/?probe=706aa7bb74) | Oct 13, 2020 |
| ASUSTek       | PRIME H310M-K               | [132e2b687c](https://linux-hardware.org/?probe=132e2b687c) | Oct 13, 2020 |
| Dell          | 0KRC95 A01                  | [a6576290b5](https://linux-hardware.org/?probe=a6576290b5) | Oct 10, 2020 |
| MSI           | H97M-E35                    | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| MSI           | H110M ECO                   | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [bcac6bcfaf](https://linux-hardware.org/?probe=bcac6bcfaf) | Oct 03, 2020 |
| Biostar       | N61PC-M2S                   | [f41fe9205d](https://linux-hardware.org/?probe=f41fe9205d) | Sep 30, 2020 |
| Gigabyte      | Z370P D3-CF                 | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [426bdc3586](https://linux-hardware.org/?probe=426bdc3586) | Sep 24, 2020 |
| Gateway       | SX2185                      | [7404f09683](https://linux-hardware.org/?probe=7404f09683) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| ASRock        | A320M-DGS                   | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| HP            | 0A50h                       | [ace0e3fed5](https://linux-hardware.org/?probe=ace0e3fed5) | Sep 13, 2020 |
| HP            | 0A50h                       | [f70b1ce07f](https://linux-hardware.org/?probe=f70b1ce07f) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| ASUSTek       | V-P8H67E                    | [a86b68e7e2](https://linux-hardware.org/?probe=a86b68e7e2) | Sep 05, 2020 |
| Dell          | 0CU409                      | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| Biostar       | A68N-2100                   | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| PCChips       | A13G                        | [d3bc7edc49](https://linux-hardware.org/?probe=d3bc7edc49) | Aug 09, 2020 |
| Lenovo        | Board                       | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Philco        | 14F                         | [8fce6fc79b](https://linux-hardware.org/?probe=8fce6fc79b) | Jul 31, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [10a2f3c16b](https://linux-hardware.org/?probe=10a2f3c16b) | Jul 30, 2020 |
| Lenovo        | SDK0E50515 STD              | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| HP            | 085Ch                       | [c22eb5394a](https://linux-hardware.org/?probe=c22eb5394a) | Jul 22, 2020 |
| HP            | 085Ch                       | [a6b75813e8](https://linux-hardware.org/?probe=a6b75813e8) | Jul 20, 2020 |
| IBM           | Board                       | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| MSI           | B450M MORTAR MAX            | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Gigabyte      | H61M-S1                     | [03b6eef668](https://linux-hardware.org/?probe=03b6eef668) | Jul 16, 2020 |
| Gigabyte      | H61M-S1                     | [61727004f5](https://linux-hardware.org/?probe=61727004f5) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [b97000d1d8](https://linux-hardware.org/?probe=b97000d1d8) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [94cba10ae4](https://linux-hardware.org/?probe=94cba10ae4) | Jul 15, 2020 |
| ASUSTek       | P5S800-VM                   | [214ec41334](https://linux-hardware.org/?probe=214ec41334) | Jul 14, 2020 |
| Biostar       | A68N-2100                   | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | 3396                        | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | [66d4b86237](https://linux-hardware.org/?probe=66d4b86237) | Jul 01, 2020 |
| MSI           | X570-A PRO                  | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| HP            | 304Ah                       | [196b570551](https://linux-hardware.org/?probe=196b570551) | Jun 23, 2020 |
| HP            | 304Ah                       | [bfe838c10f](https://linux-hardware.org/?probe=bfe838c10f) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| Intel         | DG31PR AAE58249-306         | [ee1eb9d6fb](https://linux-hardware.org/?probe=ee1eb9d6fb) | Jun 18, 2020 |
| ASUSTek       | M2R-FVM                     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| HP            | 09E0h                       | [4979e74209](https://linux-hardware.org/?probe=4979e74209) | Jun 18, 2020 |
| MSI           | 0A48                        | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| HP            | 09E0h                       | [3fbd5af0ab](https://linux-hardware.org/?probe=3fbd5af0ab) | Jun 16, 2020 |
| Intel         | DG31PR AAE58249-306         | [9e786bc6e0](https://linux-hardware.org/?probe=9e786bc6e0) | Jun 12, 2020 |
| ASUSTek       | ET1612I                     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Qbex          | HDC-M                       | [5d547380f0](https://linux-hardware.org/?probe=5d547380f0) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| Biostar       | GF7025-M2                   | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| ASUSTek       | A8N-SLI                     | [5ccefc89ce](https://linux-hardware.org/?probe=5ccefc89ce) | May 23, 2020 |
| ASUSTek       | A8N-SLI                     | [2c0867a9ec](https://linux-hardware.org/?probe=2c0867a9ec) | May 23, 2020 |
| ASUSTek       | P8H67-M LX                  | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Gigabyte      | GA-870A-UD3                 | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| ASUSTek       | P5S800-VM                   | [d491ba4166](https://linux-hardware.org/?probe=d491ba4166) | May 20, 2020 |
| ASUSTek       | P5S800-VM                   | [7d4f750922](https://linux-hardware.org/?probe=7d4f750922) | May 20, 2020 |
| HP            | 21B4 A01                    | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| Gigabyte      | 8I865G775-G                 | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [13f705413c](https://linux-hardware.org/?probe=13f705413c) | May 15, 2020 |
| Unknown       | P4M800Pro-8237              | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| VIA Techno... | P4X266-8233                 | [0bf3b29d80](https://linux-hardware.org/?probe=0bf3b29d80) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [58b07f389d](https://linux-hardware.org/?probe=58b07f389d) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [47c81c501b](https://linux-hardware.org/?probe=47c81c501b) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [2ae542835d](https://linux-hardware.org/?probe=2ae542835d) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [597e6a2b14](https://linux-hardware.org/?probe=597e6a2b14) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| ASUSTek       | P5N-E SLI                   | [7af6f2c4d4](https://linux-hardware.org/?probe=7af6f2c4d4) | May 11, 2020 |
| ASUSTek       | P5S800-VM                   | [a4020f35b9](https://linux-hardware.org/?probe=a4020f35b9) | May 10, 2020 |
| ASUSTek       | P5B-Deluxe                  | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Acer          | Aspire XC-703G              | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | 090Ch                       | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| Gigabyte      | GA-K8NF-9                   | [70a90ff062](https://linux-hardware.org/?probe=70a90ff062) | May 04, 2020 |
| ASUSTek       | P5G41C-M LX                 | [180e7f281b](https://linux-hardware.org/?probe=180e7f281b) | May 03, 2020 |
| VIA Techno... | P4X266-8233                 | [069ba04b1c](https://linux-hardware.org/?probe=069ba04b1c) | May 02, 2020 |
| Intel         | DN2800MT AAG23738-801       | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| ASUSTek       | VM40B                       | [acf2922656](https://linux-hardware.org/?probe=acf2922656) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | [2fc777ae6a](https://linux-hardware.org/?probe=2fc777ae6a) | Apr 26, 2020 |
| MSI           | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Acer          | Aspire X1800                | [beb70c1fc5](https://linux-hardware.org/?probe=beb70c1fc5) | Apr 19, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [c263eac3e9](https://linux-hardware.org/?probe=c263eac3e9) | Apr 13, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [75fff2a0a6](https://linux-hardware.org/?probe=75fff2a0a6) | Apr 13, 2020 |
| eMachines     | EL1360G                     | [53d061d3b2](https://linux-hardware.org/?probe=53d061d3b2) | Apr 11, 2020 |
| Dell          | 0MM599                      | [19e2d2af44](https://linux-hardware.org/?probe=19e2d2af44) | Apr 11, 2020 |
| Intel         | DN2820FYK H24582-204        | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| Gigabyte      | nForce                      | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [7759201b72](https://linux-hardware.org/?probe=7759201b72) | Apr 03, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [8e8dbf13fb](https://linux-hardware.org/?probe=8e8dbf13fb) | Mar 30, 2020 |
| Dell          | 0WG864                      | [092ae3a8ca](https://linux-hardware.org/?probe=092ae3a8ca) | Mar 27, 2020 |
| Gigabyte      | 945GCM-S2L                  | [548577276f](https://linux-hardware.org/?probe=548577276f) | Mar 27, 2020 |
| ASUSTek       | A8V-MQ                      | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | FM2A85X Extreme6            | [e4588ca61a](https://linux-hardware.org/?probe=e4588ca61a) | Mar 21, 2020 |
| Dell          | 0T287N A03                  | [02ebc6d299](https://linux-hardware.org/?probe=02ebc6d299) | Mar 16, 2020 |
| ASRock        | ConRoe865GV                 | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| ASRock        | B450M Pro4                  | [d7eb29abd9](https://linux-hardware.org/?probe=d7eb29abd9) | Mar 13, 2020 |
| ASRock        | ConRoe865GV                 | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [3746f6db56](https://linux-hardware.org/?probe=3746f6db56) | Mar 12, 2020 |
| Gigabyte      | P67A-D3-B3                  | [c00f70d6a6](https://linux-hardware.org/?probe=c00f70d6a6) | Mar 10, 2020 |
| ASUSTek       | H81M-E                      | [709a2484bc](https://linux-hardware.org/?probe=709a2484bc) | Mar 09, 2020 |
| ASRock        | B450M Pro4                  | [168bd28370](https://linux-hardware.org/?probe=168bd28370) | Feb 27, 2020 |
| ASUSTek       | CUSL2-M                     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| Dell          | 08HPGT A01                  | [64e6dd4ba1](https://linux-hardware.org/?probe=64e6dd4ba1) | Feb 20, 2020 |
| HP            | 0A64h                       | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | [ded9dbdb6b](https://linux-hardware.org/?probe=ded9dbdb6b) | Feb 07, 2020 |
| HP            | 0A64h                       | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| ASRock        | N73V-S                      | [80b08d6e38](https://linux-hardware.org/?probe=80b08d6e38) | Jan 27, 2020 |
| ASRock        | N73V-S                      | [1f67c1102b](https://linux-hardware.org/?probe=1f67c1102b) | Jan 26, 2020 |
| Gigabyte      | GA-K8NF-9                   | [2b8833407a](https://linux-hardware.org/?probe=2b8833407a) | Jan 25, 2020 |
| MSI           | MS-7369                     | [5c6d33ae36](https://linux-hardware.org/?probe=5c6d33ae36) | Jan 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | [cc1a05b68f](https://linux-hardware.org/?probe=cc1a05b68f) | Jan 24, 2020 |
| Dell          | 0GY6Y8 A03                  | [88961c610a](https://linux-hardware.org/?probe=88961c610a) | Jan 23, 2020 |
| ASUSTek       | P5QD TURBO                  | [d96168ded2](https://linux-hardware.org/?probe=d96168ded2) | Jan 12, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [947354716f](https://linux-hardware.org/?probe=947354716f) | Jan 07, 2020 |
| HP            | 0AA8h                       | [77b5333591](https://linux-hardware.org/?probe=77b5333591) | Jan 04, 2020 |
| ASUSTek       | V-P8H67E                    | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| ASUSTek       | V-P8H67E                    | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| AAEON         | MF-001 V1.0                 | [08480474f8](https://linux-hardware.org/?probe=08480474f8) | Dec 08, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [70309e8b8e](https://linux-hardware.org/?probe=70309e8b8e) | Dec 02, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [36a930502d](https://linux-hardware.org/?probe=36a930502d) | Nov 30, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [3bf663653b](https://linux-hardware.org/?probe=3bf663653b) | Nov 23, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Acer          | Aspire XC-703               | [5e3493c08f](https://linux-hardware.org/?probe=5e3493c08f) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [d31b932863](https://linux-hardware.org/?probe=d31b932863) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [e4ae098bfc](https://linux-hardware.org/?probe=e4ae098bfc) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [0a5f0a6adc](https://linux-hardware.org/?probe=0a5f0a6adc) | Nov 11, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [ccf33cd499](https://linux-hardware.org/?probe=ccf33cd499) | Oct 02, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [d7fb0ff803](https://linux-hardware.org/?probe=d7fb0ff803) | Oct 01, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [8b551f88e3](https://linux-hardware.org/?probe=8b551f88e3) | Oct 01, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [4bfb294198](https://linux-hardware.org/?probe=4bfb294198) | Oct 01, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [351b3bfda7](https://linux-hardware.org/?probe=351b3bfda7) | Sep 19, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [55480cd067](https://linux-hardware.org/?probe=55480cd067) | Sep 05, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [59fbd049bb](https://linux-hardware.org/?probe=59fbd049bb) | Aug 25, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [0b0497458b](https://linux-hardware.org/?probe=0b0497458b) | Aug 22, 2019 |
| ASUSTek       | Z97-A                       | [d85c2d26cb](https://linux-hardware.org/?probe=d85c2d26cb) | Jul 26, 2019 |
| ASRock        | AD525PV3                    | [682bc26535](https://linux-hardware.org/?probe=682bc26535) | Jul 03, 2019 |
| ASUSTek       | P5VD2-VM                    | [b99ee7c099](https://linux-hardware.org/?probe=b99ee7c099) | Apr 02, 2019 |
| ASUSTek       | M2N4-SLI                    | [84abf7384b](https://linux-hardware.org/?probe=84abf7384b) | Mar 24, 2019 |
| Unknown       | Unknown                     | [52b4b037a1](https://linux-hardware.org/?probe=52b4b037a1) | Feb 01, 2019 |
| Unknown       | Unknown                     | [f9908c15ca](https://linux-hardware.org/?probe=f9908c15ca) | Feb 01, 2019 |
| ASRock        | B75M-DGS R2.0               | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| PCWare        | IPX1800G2                   | [1721a635e2](https://linux-hardware.org/?probe=1721a635e2) | Nov 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Lubuntu 20.04 | 127      | 45.36%  |
| Lubuntu 18.04 | 63       | 22.5%   |
| Lubuntu 21.10 | 23       | 8.21%   |
| Lubuntu 19.10 | 17       | 6.07%   |
| Lubuntu 20.10 | 14       | 5%      |
| Lubuntu 21.04 | 12       | 4.29%   |
| Lubuntu 16.04 | 12       | 4.29%   |
| Lubuntu 18.10 | 4        | 1.43%   |
| Lubuntu 22.04 | 3        | 1.07%   |
| Lubuntu 19.04 | 2        | 0.71%   |
| Lubuntu 16.10 | 2        | 0.71%   |
| Lubuntu 17.04 | 1        | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Lubuntu | 276      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.4.0-42-generic   | 10       | 3.27%   |
| 5.4.0-52-generic   | 8        | 2.61%   |
| 5.8.0-50-generic   | 7        | 2.29%   |
| 5.11.0-27-generic  | 7        | 2.29%   |
| 5.13.0-19-generic  | 6        | 1.96%   |
| 5.4.0-54-generic   | 5        | 1.63%   |
| 5.13.0-28-generic  | 5        | 1.63%   |
| 5.8.0-59-generic   | 4        | 1.31%   |
| 5.4.0-67-generic   | 4        | 1.31%   |
| 5.4.0-48-generic   | 4        | 1.31%   |
| 5.4.0-47-generic   | 4        | 1.31%   |
| 5.4.0-40-generic   | 4        | 1.31%   |
| 5.4.0-29-generic   | 4        | 1.31%   |
| 4.15.0-74-generic  | 4        | 1.31%   |
| 4.15.0-106-generic | 4        | 1.31%   |
| 5.8.0-49-generic   | 3        | 0.98%   |
| 5.8.0-41-generic   | 3        | 0.98%   |
| 5.4.0-91-generic   | 3        | 0.98%   |
| 5.4.0-77-generic   | 3        | 0.98%   |
| 5.4.0-73-generic   | 3        | 0.98%   |
| 5.4.0-72-generic   | 3        | 0.98%   |
| 5.4.0-66-generic   | 3        | 0.98%   |
| 5.4.0-60-generic   | 3        | 0.98%   |
| 5.4.0-37-generic   | 3        | 0.98%   |
| 5.4.0-33-generic   | 3        | 0.98%   |
| 5.4.0-26-generic   | 3        | 0.98%   |
| 5.3.0-42-generic   | 3        | 0.98%   |
| 5.3.0-40-generic   | 3        | 0.98%   |
| 5.13.0-30-generic  | 3        | 0.98%   |
| 5.13.0-27-generic  | 3        | 0.98%   |
| 4.18.0-10-generic  | 3        | 0.98%   |
| 4.15.0-96-generic  | 3        | 0.98%   |
| 4.15.0-91-generic  | 3        | 0.98%   |
| 4.15.0-88-generic  | 3        | 0.98%   |
| 4.15.0-58-generic  | 3        | 0.98%   |
| 5.8.0-63-generic   | 2        | 0.65%   |
| 5.8.0-53-generic   | 2        | 0.65%   |
| 5.8.0-45-generic   | 2        | 0.65%   |
| 5.8.0-43-generic   | 2        | 0.65%   |
| 5.4.0-96-generic   | 2        | 0.65%   |
| 5.4.0-90-generic   | 2        | 0.65%   |
| 5.4.0-64-generic   | 2        | 0.65%   |
| 5.4.0-59-generic   | 2        | 0.65%   |
| 5.4.0-58-generic   | 2        | 0.65%   |
| 5.4.0-53-generic   | 2        | 0.65%   |
| 5.3.0-51-generic   | 2        | 0.65%   |
| 5.3.0-46-generic   | 2        | 0.65%   |
| 5.3.0-18-generic   | 2        | 0.65%   |
| 5.13.0-39-generic  | 2        | 0.65%   |
| 5.13.0-35-generic  | 2        | 0.65%   |
| 5.13.0-25-generic  | 2        | 0.65%   |
| 5.13.0-20-generic  | 2        | 0.65%   |
| 5.11.0-43-generic  | 2        | 0.65%   |
| 5.11.0-40-generic  | 2        | 0.65%   |
| 5.11.0-38-generic  | 2        | 0.65%   |
| 5.11.0-37-generic  | 2        | 0.65%   |
| 5.11.0-34-generic  | 2        | 0.65%   |
| 5.11.0-17-generic  | 2        | 0.65%   |
| 5.11.0-16-generic  | 2        | 0.65%   |
| 5.0.0-37-generic   | 2        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 87       | 31.07%  |
| 4.15.0  | 49       | 17.5%   |
| 5.8.0   | 35       | 12.5%   |
| 5.13.0  | 33       | 11.79%  |
| 5.11.0  | 28       | 10%     |
| 5.3.0   | 20       | 7.14%   |
| 5.0.0   | 5        | 1.79%   |
| 4.4.0   | 4        | 1.43%   |
| 4.18.0  | 4        | 1.43%   |
| 5.15.0  | 3        | 1.07%   |
| 4.8.0   | 2        | 0.71%   |
| 5.6.15  | 1        | 0.36%   |
| 5.6.0   | 1        | 0.36%   |
| 5.4.30  | 1        | 0.36%   |
| 5.3.18  | 1        | 0.36%   |
| 5.16.5  | 1        | 0.36%   |
| 5.15.5  | 1        | 0.36%   |
| 5.14.0  | 1        | 0.36%   |
| 5.12.1  | 1        | 0.36%   |
| 4.15.18 | 1        | 0.36%   |
| 4.10.0  | 1        | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 88       | 31.43%  |
| 4.15    | 50       | 17.86%  |
| 5.8     | 35       | 12.5%   |
| 5.13    | 33       | 11.79%  |
| 5.11    | 28       | 10%     |
| 5.3     | 21       | 7.5%    |
| 5.0     | 5        | 1.79%   |
| 5.15    | 4        | 1.43%   |
| 4.4     | 4        | 1.43%   |
| 4.18    | 4        | 1.43%   |
| 5.6     | 2        | 0.71%   |
| 4.8     | 2        | 0.71%   |
| 5.16    | 1        | 0.36%   |
| 5.14    | 1        | 0.36%   |
| 5.12    | 1        | 0.36%   |
| 4.10    | 1        | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 243      | 88.04%  |
| i686   | 32       | 11.59%  |
| ppc64  | 1        | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| LXQt            | 192      | 68.82%  |
| LXDE            | 68       | 24.37%  |
| GNOME           | 7        | 2.51%   |
| Unknown         | 6        | 2.15%   |
| Openbox         | 2        | 0.72%   |
| X-Cinnamon      | 1        | 0.36%   |
| KDE5            | 1        | 0.36%   |
| i3              | 1        | 0.36%   |
| GNOME Flashback | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 266      | 95.68%  |
| Tty         | 8        | 2.88%   |
| Unknown     | 2        | 0.72%   |
| Wayland     | 1        | 0.36%   |
| Unspecified | 1        | 0.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 118      | 42.14%  |
| SDDM    | 101      | 36.07%  |
| TDM     | 25       | 8.93%   |
| LightDM | 22       | 7.86%   |
| GDM     | 10       | 3.57%   |
| LXDM    | 2        | 0.71%   |
| XDM     | 1        | 0.36%   |
| GDM3    | 1        | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 64       | 23.02%  |
| fr_FR   | 24       | 8.63%   |
| pt_BR   | 21       | 7.55%   |
| it_IT   | 18       | 6.47%   |
| de_DE   | 17       | 6.12%   |
| C       | 15       | 5.4%    |
| ru_RU   | 14       | 5.04%   |
| en_GB   | 13       | 4.68%   |
| Unknown | 13       | 4.68%   |
| en_CA   | 11       | 3.96%   |
| es_ES   | 6        | 2.16%   |
| en_AU   | 6        | 2.16%   |
| ja_JP   | 4        | 1.44%   |
| hu_HU   | 4        | 1.44%   |
| es_AR   | 4        | 1.44%   |
| cs_CZ   | 4        | 1.44%   |
| pl_PL   | 3        | 1.08%   |
| nl_NL   | 3        | 1.08%   |
| tr_TR   | 2        | 0.72%   |
| pt_PT   | 2        | 0.72%   |
| fr_CA   | 2        | 0.72%   |
| fi_FI   | 2        | 0.72%   |
| es_UY   | 2        | 0.72%   |
| es_PE   | 2        | 0.72%   |
| es_MX   | 2        | 0.72%   |
| es_CO   | 2        | 0.72%   |
| en_ZA   | 2        | 0.72%   |
| el_GR   | 2        | 0.72%   |
| bg_BG   | 2        | 0.72%   |
| sv_SE   | 1        | 0.36%   |
| hr_HR   | 1        | 0.36%   |
| es_GT   | 1        | 0.36%   |
| es_EC   | 1        | 0.36%   |
| es_CR   | 1        | 0.36%   |
| es_CL   | 1        | 0.36%   |
| en_SG   | 1        | 0.36%   |
| en_NZ   | 1        | 0.36%   |
| en_IN   | 1        | 0.36%   |
| en_HK   | 1        | 0.36%   |
| de_CH   | 1        | 0.36%   |
| cv_RU   | 1        | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 207      | 75%     |
| EFI  | 69       | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 253      | 91.67%  |
| Overlay | 15       | 5.43%   |
| Xfs     | 3        | 1.09%   |
| Btrfs   | 2        | 0.72%   |
| Unknown | 2        | 0.72%   |
| F2fs    | 1        | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 143      | 51.62%  |
| MBR     | 78       | 28.16%  |
| GPT     | 56       | 20.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 235      | 84.84%  |
| Yes       | 42       | 15.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 185      | 66.79%  |
| Yes       | 92       | 33.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 54       | 19.57%  |
| Gigabyte Technology | 35       | 12.68%  |
| Hewlett-Packard     | 32       | 11.59%  |
| ASRock              | 25       | 9.06%   |
| Dell                | 23       | 8.33%   |
| MSI                 | 21       | 7.61%   |
| Intel               | 15       | 5.43%   |
| Lenovo              | 11       | 3.99%   |
| Acer                | 9        | 3.26%   |
| Unknown             | 9        | 3.26%   |
| Pegatron            | 6        | 2.17%   |
| Foxconn             | 6        | 2.17%   |
| Biostar             | 5        | 1.81%   |
| AAEON               | 4        | 1.45%   |
| Positivo            | 2        | 0.72%   |
| IBM                 | 2        | 0.72%   |
| eMachines           | 2        | 0.72%   |
| AMI                 | 2        | 0.72%   |
| ZOTAC               | 1        | 0.36%   |
| VIA Technologies    | 1        | 0.36%   |
| Qbex                | 1        | 0.36%   |
| Philco              | 1        | 0.36%   |
| PCWare              | 1        | 0.36%   |
| PCChips             | 1        | 0.36%   |
| Packard Bell        | 1        | 0.36%   |
| Medion              | 1        | 0.36%   |
| Huanan              | 1        | 0.36%   |
| HARDKERNEL          | 1        | 0.36%   |
| Gateway             | 1        | 0.36%   |
| Fujitsu Siemens     | 1        | 0.36%   |
| ECS                 | 1        | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 9        | 3.26%   |
| AAEON MF-001                        | 4        | 1.45%   |
| Dell OptiPlex 790                   | 3        | 1.09%   |
| ASUS V-P8H67E                       | 3        | 1.09%   |
| ASUS All Series                     | 3        | 1.09%   |
| MSI MS-7B89                         | 2        | 0.72%   |
| HP t620 Quad Core TC                | 2        | 0.72%   |
| HP Compaq dc7800 Small Form Factor  | 2        | 0.72%   |
| HP Compaq 6000 Pro SFF PC           | 2        | 0.72%   |
| Gigabyte H81M-DS2                   | 2        | 0.72%   |
| Dell OptiPlex 7010                  | 2        | 0.72%   |
| Dell DM061                          | 2        | 0.72%   |
| ASUS PRIME H410M-E                  | 2        | 0.72%   |
| ASRock N68-VS3 UCC                  | 2        | 0.72%   |
| ASRock FM2A85X Extreme6             | 2        | 0.72%   |
| ASRock 775Dual-VSTA                 | 2        | 0.72%   |
| ZOTAC NM10                          | 1        | 0.36%   |
| VIA P4X266-8233                     | 1        | 0.36%   |
| Qbex QBEX-HDC-M                     | 1        | 0.36%   |
| Positivo POS-MI945AA                | 1        | 0.36%   |
| Positivo POS-EIH61CE                | 1        | 0.36%   |
| Philco 14F                          | 1        | 0.36%   |
| Pegatron WE216AA-ABF CQ5335FR       | 1        | 0.36%   |
| Pegatron NC689AA-ABA s3700y         | 1        | 0.36%   |
| Pegatron FQ425AA-ABA a6655f         | 1        | 0.36%   |
| Pegatron FL308AA-ABD IQ512de        | 1        | 0.36%   |
| Pegatron AY652AA-ABA s5310y         | 1        | 0.36%   |
| Pegatron 2AD5                       | 1        | 0.36%   |
| PCWare IPX1800G2                    | 1        | 0.36%   |
| PCChips A13G                        | 1        | 0.36%   |
| Packard Bell imedia S1350           | 1        | 0.36%   |
| MSI MS-7C82                         | 1        | 0.36%   |
| MSI MS-7C80                         | 1        | 0.36%   |
| MSI MS-7C37                         | 1        | 0.36%   |
| MSI MS-7B86                         | 1        | 0.36%   |
| MSI MS-7B36                         | 1        | 0.36%   |
| MSI MS-7A39                         | 1        | 0.36%   |
| MSI MS-7994                         | 1        | 0.36%   |
| MSI MS-7846                         | 1        | 0.36%   |
| MSI MS-7680                         | 1        | 0.36%   |
| MSI MS-7640                         | 1        | 0.36%   |
| MSI MS-7592                         | 1        | 0.36%   |
| MSI MS-7581                         | 1        | 0.36%   |
| MSI MS-7369                         | 1        | 0.36%   |
| MSI MS-7309                         | 1        | 0.36%   |
| MSI MS-7270                         | 1        | 0.36%   |
| MSI MS-7250                         | 1        | 0.36%   |
| MSI KT541AA-UUB a6528hk             | 1        | 0.36%   |
| MSI ER883AA-ABA M7470N              | 1        | 0.36%   |
| MSI Compaq dx2200 MT                | 1        | 0.36%   |
| Medion MS-7728                      | 1        | 0.36%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 0.36%   |
| Lenovo ThinkCentre XXXX 9632AU8     | 1        | 0.36%   |
| Lenovo ThinkCentre M93z 10AD002DMZ  | 1        | 0.36%   |
| Lenovo ThinkCentre M92p 3227BL8     | 1        | 0.36%   |
| Lenovo ThinkCentre M83 10ANS05500   | 1        | 0.36%   |
| Lenovo ThinkCentre M73 10AXS0HN00   | 1        | 0.36%   |
| Lenovo ThinkCentre M58p 7220W21     | 1        | 0.36%   |
| Lenovo ThinkCentre M58p 6136A66     | 1        | 0.36%   |
| Lenovo ThinkCentre M55p 8811VQV     | 1        | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 17       | 6.16%   |
| Dell OptiPlex        | 12       | 4.35%   |
| Acer Aspire          | 9        | 3.26%   |
| Unknown              | 9        | 3.26%   |
| Lenovo ThinkCentre   | 8        | 2.9%    |
| ASUS PRIME           | 5        | 1.81%   |
| AAEON MF-001         | 4        | 1.45%   |
| HP t620              | 3        | 1.09%   |
| ASUS V-P8H67E        | 3        | 1.09%   |
| ASUS All             | 3        | 1.09%   |
| MSI MS-7B89          | 2        | 0.72%   |
| Intel DG31PR         | 2        | 0.72%   |
| HP EliteDesk         | 2        | 0.72%   |
| HP dc5000            | 2        | 0.72%   |
| Gigabyte H81M-DS2    | 2        | 0.72%   |
| Gigabyte B450M       | 2        | 0.72%   |
| Dell Vostro          | 2        | 0.72%   |
| Dell Precision       | 2        | 0.72%   |
| Dell Inspiron        | 2        | 0.72%   |
| Dell DM061           | 2        | 0.72%   |
| ASRock N68-VS3       | 2        | 0.72%   |
| ASRock FM2A85X       | 2        | 0.72%   |
| ASRock B450M         | 2        | 0.72%   |
| ASRock 775Dual-VSTA  | 2        | 0.72%   |
| ZOTAC NM10           | 1        | 0.36%   |
| VIA P4X266-8233      | 1        | 0.36%   |
| Qbex QBEX-HDC-M      | 1        | 0.36%   |
| Positivo POS-MI945AA | 1        | 0.36%   |
| Positivo POS-EIH61CE | 1        | 0.36%   |
| Philco 14F           | 1        | 0.36%   |
| Pegatron WE216AA-ABF | 1        | 0.36%   |
| Pegatron NC689AA-ABA | 1        | 0.36%   |
| Pegatron FQ425AA-ABA | 1        | 0.36%   |
| Pegatron FL308AA-ABD | 1        | 0.36%   |
| Pegatron AY652AA-ABA | 1        | 0.36%   |
| Pegatron 2AD5        | 1        | 0.36%   |
| PCWare IPX1800G2     | 1        | 0.36%   |
| PCChips A13G         | 1        | 0.36%   |
| Packard Bell imedia  | 1        | 0.36%   |
| MSI MS-7C82          | 1        | 0.36%   |
| MSI MS-7C80          | 1        | 0.36%   |
| MSI MS-7C37          | 1        | 0.36%   |
| MSI MS-7B86          | 1        | 0.36%   |
| MSI MS-7B36          | 1        | 0.36%   |
| MSI MS-7A39          | 1        | 0.36%   |
| MSI MS-7994          | 1        | 0.36%   |
| MSI MS-7846          | 1        | 0.36%   |
| MSI MS-7680          | 1        | 0.36%   |
| MSI MS-7640          | 1        | 0.36%   |
| MSI MS-7592          | 1        | 0.36%   |
| MSI MS-7581          | 1        | 0.36%   |
| MSI MS-7369          | 1        | 0.36%   |
| MSI MS-7309          | 1        | 0.36%   |
| MSI MS-7270          | 1        | 0.36%   |
| MSI MS-7250          | 1        | 0.36%   |
| MSI KT541AA-UUB      | 1        | 0.36%   |
| MSI ER883AA-ABA      | 1        | 0.36%   |
| MSI Compaq           | 1        | 0.36%   |
| Medion MS-7728       | 1        | 0.36%   |
| Lenovo ThinkStation  | 1        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2007    | 30       | 10.87%  |
| 2012    | 25       | 9.06%   |
| 2009    | 25       | 9.06%   |
| 2011    | 24       | 8.7%    |
| 2008    | 20       | 7.25%   |
| 2010    | 18       | 6.52%   |
| 2013    | 17       | 6.16%   |
| 2006    | 16       | 5.8%    |
| 2014    | 15       | 5.43%   |
| 2017    | 14       | 5.07%   |
| 2005    | 13       | 4.71%   |
| 2020    | 12       | 4.35%   |
| 2015    | 11       | 3.99%   |
| 2019    | 9        | 3.26%   |
| 2018    | 7        | 2.54%   |
| 2021    | 6        | 2.17%   |
| 2016    | 5        | 1.81%   |
| 2004    | 4        | 1.45%   |
| Unknown | 2        | 0.72%   |
| 2003    | 1        | 0.36%   |
| 2001    | 1        | 0.36%   |
| 2000    | 1        | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 276      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 271      | 98.19%  |
| Enabled  | 5        | 1.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 276      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 75       | 26.6%   |
| 4.01-8.0        | 43       | 15.25%  |
| 1.01-2.0        | 43       | 15.25%  |
| 8.01-16.0       | 38       | 13.48%  |
| 16.01-24.0      | 36       | 12.77%  |
| 32.01-64.0      | 14       | 4.96%   |
| 2.01-3.0        | 13       | 4.61%   |
| 0.51-1.0        | 9        | 3.19%   |
| 0.01-0.5        | 5        | 1.77%   |
| 24.01-32.0      | 4        | 1.42%   |
| More than 256.0 | 1        | 0.35%   |
| 64.01-256.0     | 1        | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 128      | 43.39%  |
| 0.51-1.0   | 71       | 24.07%  |
| 2.01-3.0   | 44       | 14.92%  |
| 4.01-8.0   | 19       | 6.44%   |
| 0.01-0.5   | 19       | 6.44%   |
| 3.01-4.0   | 9        | 3.05%   |
| 8.01-16.0  | 4        | 1.36%   |
| 16.01-24.0 | 1        | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 157      | 56.27%  |
| 2      | 77       | 27.6%   |
| 4      | 16       | 5.73%   |
| 3      | 14       | 5.02%   |
| 5      | 8        | 2.87%   |
| 0      | 3        | 1.08%   |
| 14     | 1        | 0.36%   |
| 10     | 1        | 0.36%   |
| 7      | 1        | 0.36%   |
| 6      | 1        | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 151      | 54.51%  |
| No        | 126      | 45.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 271      | 98.19%  |
| No        | 5        | 1.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 62.72%  |
| Yes       | 104      | 37.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 236      | 85.2%   |
| Yes       | 41       | 14.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 34       | 12.27%  |
| Brazil                 | 27       | 9.75%   |
| France                 | 24       | 8.66%   |
| Italy                  | 21       | 7.58%   |
| Germany                | 20       | 7.22%   |
| Russia                 | 17       | 6.14%   |
| Canada                 | 15       | 5.42%   |
| Spain                  | 7        | 2.53%   |
| Netherlands            | 7        | 2.53%   |
| Hungary                | 7        | 2.53%   |
| UK                     | 6        | 2.17%   |
| Switzerland            | 6        | 2.17%   |
| Finland                | 6        | 2.17%   |
| Australia              | 6        | 2.17%   |
| Czechia                | 5        | 1.81%   |
| Poland                 | 4        | 1.44%   |
| Japan                  | 4        | 1.44%   |
| Argentina              | 4        | 1.44%   |
| Turkey                 | 3        | 1.08%   |
| South Africa           | 3        | 1.08%   |
| Mexico                 | 3        | 1.08%   |
| Greece                 | 3        | 1.08%   |
| Colombia               | 3        | 1.08%   |
| Bulgaria               | 3        | 1.08%   |
| Belgium                | 3        | 1.08%   |
| Uruguay                | 2        | 0.72%   |
| Romania                | 2        | 0.72%   |
| Puerto Rico            | 2        | 0.72%   |
| Peru                   | 2        | 0.72%   |
| New Zealand            | 2        | 0.72%   |
| Malaysia               | 2        | 0.72%   |
| India                  | 2        | 0.72%   |
| Sweden                 | 1        | 0.36%   |
| South Korea            | 1        | 0.36%   |
| Slovenia               | 1        | 0.36%   |
| Slovakia               | 1        | 0.36%   |
| Singapore              | 1        | 0.36%   |
| Portugal               | 1        | 0.36%   |
| Morocco                | 1        | 0.36%   |
| Luxembourg             | 1        | 0.36%   |
| Latvia                 | 1        | 0.36%   |
| Kazakhstan             | 1        | 0.36%   |
| Iran                   | 1        | 0.36%   |
| Indonesia              | 1        | 0.36%   |
| Hong Kong              | 1        | 0.36%   |
| Guatemala              | 1        | 0.36%   |
| Ecuador                | 1        | 0.36%   |
| Denmark                | 1        | 0.36%   |
| Croatia                | 1        | 0.36%   |
| Costa Rica             | 1        | 0.36%   |
| Chile                  | 1        | 0.36%   |
| Bosnia and Herzegovina | 1        | 0.36%   |
| Belarus                | 1        | 0.36%   |
| Austria                | 1        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Rome              | 7        | 2.49%   |
| Milan             | 5        | 1.78%   |
| Oshawa            | 4        | 1.42%   |
| Helsinki          | 4        | 1.42%   |
| Zurich            | 3        | 1.07%   |
| Windsor           | 3        | 1.07%   |
| Voronezh          | 3        | 1.07%   |
| Rio de Janeiro    | 3        | 1.07%   |
| Wellington        | 2        | 0.71%   |
| Valinhos          | 2        | 0.71%   |
| Toronto           | 2        | 0.71%   |
| St Petersburg     | 2        | 0.71%   |
| Springfield       | 2        | 0.71%   |
| Spokane           | 2        | 0.71%   |
| Sofia             | 2        | 0.71%   |
| Preston           | 2        | 0.71%   |
| Prague            | 2        | 0.71%   |
| Novo Gama         | 2        | 0.71%   |
| Naples            | 2        | 0.71%   |
| Moscow            | 2        | 0.71%   |
| Montreal          | 2        | 0.71%   |
| Lyon              | 2        | 0.71%   |
| Kuala Lumpur      | 2        | 0.71%   |
| Kirov             | 2        | 0.71%   |
| Istanbul          | 2        | 0.71%   |
| Frankfurt am Main | 2        | 0.71%   |
| Eger              | 2        | 0.71%   |
| Dallas            | 2        | 0.71%   |
| Cuernavaca        | 2        | 0.71%   |
| Cayey             | 2        | 0.71%   |
| Cape Town         | 2        | 0.71%   |
| Birmingham        | 2        | 0.71%   |
| Augsburg          | 2        | 0.71%   |
| Athens            | 2        | 0.71%   |
| Annecy            | 2        | 0.71%   |
| Zwolle            | 1        | 0.36%   |
| Zagreb            | 1        | 0.36%   |
| Yuzhno-Sakhalinsk | 1        | 0.36%   |
| Yelizovo          | 1        | 0.36%   |
| Winsen            | 1        | 0.36%   |
| Williams Lake     | 1        | 0.36%   |
| Wiesbaden         | 1        | 0.36%   |
| Warsaw            | 1        | 0.36%   |
| Vlaardingen       | 1        | 0.36%   |
| ViГ±a del Mar   | 1        | 0.36%   |
| Vitry-sur-Seine   | 1        | 0.36%   |
| Villemomble       | 1        | 0.36%   |
| Vaxjo             | 1        | 0.36%   |
| Vanderbijlpark    | 1        | 0.36%   |
| Valls             | 1        | 0.36%   |
| Valencia          | 1        | 0.36%   |
| Trujillo          | 1        | 0.36%   |
| Treviso           | 1        | 0.36%   |
| Tourcoing         | 1        | 0.36%   |
| Tokorozawa        | 1        | 0.36%   |
| Thunder Bay       | 1        | 0.36%   |
| The Hague         | 1        | 0.36%   |
| TehrДЃn         | 1        | 0.36%   |
| SГЈo LuГ­s    | 1        | 0.36%   |
| Sydney            | 1        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 98       | 136    | 24.38%  |
| WDC                 | 95       | 132    | 23.63%  |
| Samsung Electronics | 41       | 70     | 10.2%   |
| Kingston            | 21       | 21     | 5.22%   |
| Hitachi             | 20       | 26     | 4.98%   |
| Toshiba             | 16       | 16     | 3.98%   |
| MAXTOR              | 14       | 15     | 3.48%   |
| Unknown             | 12       | 15     | 2.99%   |
| SanDisk             | 9        | 10     | 2.24%   |
| Crucial             | 6        | 6      | 1.49%   |
| Intel               | 5        | 5      | 1.24%   |
| HGST                | 5        | 7      | 1.24%   |
| A-DATA Technology   | 5        | 7      | 1.24%   |
| Micron Technology   | 4        | 4      | 1%      |
| SPCC                | 3        | 6      | 0.75%   |
| Intenso             | 3        | 3      | 0.75%   |
| China               | 3        | 3      | 0.75%   |
| TO Exter            | 2        | 2      | 0.5%    |
| Team                | 2        | 2      | 0.5%    |
| Silicon Motion      | 2        | 3      | 0.5%    |
| PNY                 | 2        | 2      | 0.5%    |
| PLEXTOR             | 2        | 4      | 0.5%    |
| OCZ                 | 2        | 2      | 0.5%    |
| Lexar               | 2        | 2      | 0.5%    |
| LDLC                | 2        | 2      | 0.5%    |
| JMicron             | 2        | 2      | 0.5%    |
| Fujitsu             | 2        | 2      | 0.5%    |
| Corsair             | 2        | 2      | 0.5%    |
| TSA                 | 1        | 1      | 0.25%   |
| Transcend           | 1        | 1      | 0.25%   |
| Smartbuy            | 1        | 1      | 0.25%   |
| ShiJi               | 1        | 1      | 0.25%   |
| PNY USB             | 1        | 1      | 0.25%   |
| Mushkin             | 1        | 1      | 0.25%   |
| MaxDigital          | 1        | 1      | 0.25%   |
| LONDISK             | 1        | 1      | 0.25%   |
| LITEONIT            | 1        | 1      | 0.25%   |
| Leven               | 1        | 2      | 0.25%   |
| Kston               | 1        | 2      | 0.25%   |
| KLEVV               | 1        | 1      | 0.25%   |
| KingFast            | 1        | 1      | 0.25%   |
| HS-SSD-E100         | 1        | 1      | 0.25%   |
| Hikvision           | 1        | 1      | 0.25%   |
| Hewlett-Packard     | 1        | 6      | 0.25%   |
| GOODRAM             | 1        | 1      | 0.25%   |
| FORESEE             | 1        | 1      | 0.25%   |
| External            | 1        | 1      | 0.25%   |
| ASMT                | 1        | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5        | 1.12%   |
| Seagate ST3500418AS 500GB           | 5        | 1.12%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB      | 4        | 0.89%   |
| Samsung SSD 850 EVO 500GB           | 4        | 0.89%   |
| Kingston SA400S37120G 120GB SSD     | 4        | 0.89%   |
| Unknown M52516  16GB                | 3        | 0.67%   |
| Seagate ST500DM002-1BD142 500GB     | 3        | 0.67%   |
| Seagate ST4000DM004-2CV104 4TB      | 3        | 0.67%   |
| Seagate ST3500312CS 500GB           | 3        | 0.67%   |
| Seagate ST3250410AS 250GB           | 3        | 0.67%   |
| Seagate ST3250310AS 250GB           | 3        | 0.67%   |
| Seagate ST3160318AS 160GB           | 3        | 0.67%   |
| Seagate ST31000528AS 1TB            | 3        | 0.67%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB      | 3        | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB      | 3        | 0.67%   |
| Seagate Expansion 1TB               | 3        | 0.67%   |
| Samsung SSD 850 EVO 250GB           | 3        | 0.67%   |
| Samsung HD322HJ 320GB               | 3        | 0.67%   |
| Samsung HD161HJ 160GB               | 3        | 0.67%   |
| Samsung HD103SJ 1TB                 | 3        | 0.67%   |
| A-DATA SU650 240GB SSD              | 3        | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.45%   |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.45%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.45%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2        | 0.45%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 2        | 0.45%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.45%   |
| WDC WD400BB-60DGA0 40GB             | 2        | 0.45%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 2        | 0.45%   |
| WDC WD2500JS-75NCB3 250GB           | 2        | 0.45%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 0.45%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 0.45%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.45%   |
| WDC WD10EARX-00N0YB0 1TB            | 2        | 0.45%   |
| WDC WD10EADS-00L5B1 1TB             | 2        | 0.45%   |
| Unknown SD/MMC/MS PRO 394GB         | 2        | 0.45%   |
| Unknown MMC Card  32GB              | 2        | 0.45%   |
| Toshiba DT01ACA050 500GB            | 2        | 0.45%   |
| TO Exter nal USB 3.0 1024GB         | 2        | 0.45%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.45%   |
| Seagate ST380815AS 80GB             | 2        | 0.45%   |
| Seagate ST380013AS 80GB             | 2        | 0.45%   |
| Seagate ST380011A 80GB              | 2        | 0.45%   |
| Seagate ST3360320AS 360GB           | 2        | 0.45%   |
| Seagate ST3320620AS 320GB           | 2        | 0.45%   |
| Seagate ST3250318AS 250GB           | 2        | 0.45%   |
| Seagate ST3200826AS 200GB           | 2        | 0.45%   |
| Seagate ST3160023AS 160GB           | 2        | 0.45%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.45%   |
| Seagate ST1000DM003-1SB10C 1TB      | 2        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.45%   |
| SanDisk SDSSDP128G 128GB            | 2        | 0.45%   |
| SanDisk SDSSDA120G 120GB            | 2        | 0.45%   |
| Samsung HM321HI 320GB               | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 98       | 136    | 36.84%  |
| WDC                 | 87       | 120    | 32.71%  |
| Samsung Electronics | 26       | 37     | 9.77%   |
| Hitachi             | 20       | 26     | 7.52%   |
| Toshiba             | 13       | 13     | 4.89%   |
| MAXTOR              | 13       | 14     | 4.89%   |
| HGST                | 5        | 7      | 1.88%   |
| Unknown             | 2        | 2      | 0.75%   |
| Fujitsu             | 2        | 2      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 21       | 21     | 17.95%  |
| Samsung Electronics | 15       | 21     | 12.82%  |
| WDC                 | 10       | 12     | 8.55%   |
| SanDisk             | 8        | 9      | 6.84%   |
| Crucial             | 6        | 6      | 5.13%   |
| Micron Technology   | 4        | 4      | 3.42%   |
| Intel               | 4        | 4      | 3.42%   |
| A-DATA Technology   | 4        | 6      | 3.42%   |
| Toshiba             | 3        | 3      | 2.56%   |
| Intenso             | 3        | 3      | 2.56%   |
| China               | 3        | 3      | 2.56%   |
| TO Exter            | 2        | 2      | 1.71%   |
| Team                | 2        | 2      | 1.71%   |
| PNY                 | 2        | 2      | 1.71%   |
| PLEXTOR             | 2        | 4      | 1.71%   |
| OCZ                 | 2        | 2      | 1.71%   |
| Lexar               | 2        | 2      | 1.71%   |
| Corsair             | 2        | 2      | 1.71%   |
| Unknown             | 1        | 1      | 0.85%   |
| TSA                 | 1        | 1      | 0.85%   |
| Transcend           | 1        | 1      | 0.85%   |
| SPCC                | 1        | 1      | 0.85%   |
| Smartbuy            | 1        | 1      | 0.85%   |
| PNY USB             | 1        | 1      | 0.85%   |
| Mushkin             | 1        | 1      | 0.85%   |
| MAXTOR              | 1        | 1      | 0.85%   |
| LONDISK             | 1        | 1      | 0.85%   |
| LITEONIT            | 1        | 1      | 0.85%   |
| Leven               | 1        | 2      | 0.85%   |
| LDLC                | 1        | 1      | 0.85%   |
| Kston               | 1        | 2      | 0.85%   |
| KLEVV               | 1        | 1      | 0.85%   |
| JMicron             | 1        | 1      | 0.85%   |
| HS-SSD-E100         | 1        | 1      | 0.85%   |
| Hikvision           | 1        | 1      | 0.85%   |
| Hewlett-Packard     | 1        | 6      | 0.85%   |
| GOODRAM             | 1        | 1      | 0.85%   |
| FORESEE             | 1        | 1      | 0.85%   |
| External            | 1        | 1      | 0.85%   |
| ASMT                | 1        | 1      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 209      | 357    | 61.29%  |
| SSD     | 108      | 137    | 31.67%  |
| NVMe    | 12       | 25     | 3.52%   |
| MMC     | 8        | 9      | 2.35%   |
| Unknown | 4        | 6      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 261      | 478    | 88.18%  |
| SAS  | 15       | 22     | 5.07%   |
| NVMe | 12       | 25     | 4.05%   |
| MMC  | 8        | 9      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 226      | 340    | 68.9%   |
| 0.51-1.0   | 64       | 96     | 19.51%  |
| 1.01-2.0   | 20       | 25     | 6.1%    |
| 3.01-4.0   | 11       | 25     | 3.35%   |
| 2.01-3.0   | 4        | 4      | 1.22%   |
| 4.01-10.0  | 3        | 4      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 90       | 32.37%  |
| 251-500        | 57       | 20.5%   |
| 501-1000       | 28       | 10.07%  |
| 51-100         | 24       | 8.63%   |
| 1001-2000      | 20       | 7.19%   |
| More than 3000 | 18       | 6.47%   |
| 1-20           | 17       | 6.12%   |
| 21-50          | 12       | 4.32%   |
| 2001-3000      | 11       | 3.96%   |
| Unknown        | 1        | 0.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 128      | 44.44%  |
| 21-50          | 52       | 18.06%  |
| 101-250        | 33       | 11.46%  |
| 51-100         | 21       | 7.29%   |
| 251-500        | 16       | 5.56%   |
| 1001-2000      | 13       | 4.51%   |
| 501-1000       | 12       | 4.17%   |
| More than 3000 | 7        | 2.43%   |
| 2001-3000      | 5        | 1.74%   |
| Unknown        | 1        | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB    | 3        | 3      | 7.32%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 1      | 2.44%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 1      | 2.44%   |
| WDC WD400EB-00CPF0 40GB           | 1        | 1      | 2.44%   |
| WDC WD2500HHTZ-04N21V0 250GB      | 1        | 1      | 2.44%   |
| WDC WD2500AAJS-75M0A0 250GB       | 1        | 1      | 2.44%   |
| WDC WD1600AAJS-60B4A0 160GB       | 1        | 2      | 2.44%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 2.44%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 1      | 2.44%   |
| Seagate ST9500420AS 500GB         | 1        | 1      | 2.44%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.44%   |
| Seagate ST9250315AS 250GB         | 1        | 1      | 2.44%   |
| Seagate ST9160310AS 160GB         | 1        | 1      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 2.44%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1      | 2.44%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 2.44%   |
| Seagate ST380011A 80GB            | 1        | 1      | 2.44%   |
| Seagate ST3360320AS 360GB         | 1        | 1      | 2.44%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 2.44%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 2.44%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 2.44%   |
| Seagate ST1000DX001-1CM162 1TB    | 1        | 1      | 2.44%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 2.44%   |
| Samsung Electronics HD253GJ 250GB | 1        | 1      | 2.44%   |
| Mushkin MKNSSDCR60GB-7 64GB       | 1        | 1      | 2.44%   |
| MAXTOR STM3300622A 304GB          | 1        | 1      | 2.44%   |
| MAXTOR 6Y080L0 82GB               | 1        | 1      | 2.44%   |
| MAXTOR 6B200M0 208GB              | 1        | 1      | 2.44%   |
| LDLC SSD 120GB                    | 1        | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 2.44%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 2.44%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 1      | 2.44%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 2.44%   |
| Intel SSDSA1M160G2HP 160GB        | 1        | 1      | 2.44%   |
| Hitachi HTS722080K9A300 80GB      | 1        | 1      | 2.44%   |
| Hitachi HDS721075CLA332 752GB     | 1        | 1      | 2.44%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 2.44%   |
| Hitachi HCP725050GLAT80 500GB     | 1        | 1      | 2.44%   |
| Fujitsu MHZ2160BH G2 160GB        | 1        | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 17     | 41.03%  |
| WDC                 | 8        | 9      | 20.51%  |
| Kingston            | 4        | 4      | 10.26%  |
| MAXTOR              | 3        | 3      | 7.69%   |
| Hitachi             | 3        | 4      | 7.69%   |
| Samsung Electronics | 1        | 1      | 2.56%   |
| Mushkin             | 1        | 1      | 2.56%   |
| LDLC                | 1        | 1      | 2.56%   |
| Intel               | 1        | 1      | 2.56%   |
| Fujitsu             | 1        | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 17     | 50%     |
| WDC                 | 8        | 9      | 25%     |
| MAXTOR              | 3        | 3      | 9.38%   |
| Hitachi             | 3        | 4      | 9.38%   |
| Samsung Electronics | 1        | 1      | 3.13%   |
| Fujitsu             | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 35     | 81.08%  |
| SSD  | 7        | 7      | 18.92%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Samsung Electronics HD080HJ 80GB | 1        | 1      | 50%     |
| Intel SSDSA1M160G2HP 160GB       | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Intel               | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 154      | 272    | 50.83%  |
| Works    | 112      | 218    | 36.96%  |
| Malfunc  | 35       | 42     | 11.55%  |
| Failed   | 2        | 2      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 167      | 53.7%   |
| AMD                              | 55       | 17.68%  |
| Nvidia                           | 34       | 10.93%  |
| JMicron Technology               | 13       | 4.18%   |
| Marvell Technology Group         | 9        | 2.89%   |
| VIA Technologies                 | 8        | 2.57%   |
| Silicon Motion                   | 5        | 1.61%   |
| ASMedia Technology               | 5        | 1.61%   |
| Samsung Electronics              | 3        | 0.96%   |
| ULi Electronics                  | 2        | 0.64%   |
| Silicon Image                    | 2        | 0.64%   |
| LSI Logic / Symbios Logic        | 2        | 0.64%   |
| Silicon Integrated Systems [SiS] | 1        | 0.32%   |
| Sandisk                          | 1        | 0.32%   |
| Phison Electronics               | 1        | 0.32%   |
| Broadcom                         | 1        | 0.32%   |
| ADATA Technology                 | 1        | 0.32%   |
| Adaptec                          | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 6.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 5.84%   |
| Nvidia MCP61 SATA Controller                                                            | 15       | 3.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.92%   |
| Nvidia MCP61 IDE                                                                        | 12       | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 2.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.25%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 9        | 2.02%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 8        | 1.8%    |
| Nvidia CK804 Serial ATA Controller                                                      | 7        | 1.57%   |
| Nvidia CK804 IDE                                                                        | 7        | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 1.57%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 1.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 1.57%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 1.35%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 1.12%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 1.12%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 5        | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.12%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 5        | 1.12%   |
| AMD SB600 IDE                                                                           | 5        | 1.12%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.12%   |
| Nvidia MCP73 IDE Controller                                                             | 4        | 0.9%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.9%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 4        | 0.9%    |
| Intel 82801EB (ICH5) SATA Controller                                                    | 4        | 0.9%    |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 0.67%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.67%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 0.67%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.67%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2        | 0.45%   |
| ULi M5229 IDE                                                                           | 2        | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.45%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 2        | 0.45%   |
| Nvidia MCP55 SATA Controller                                                            | 2        | 0.45%   |
| Nvidia MCP55 IDE                                                                        | 2        | 0.45%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 0.45%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 2        | 0.45%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 2        | 0.45%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.45%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.45%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 148      | 45.68%  |
| IDE  | 144      | 44.44%  |
| RAID | 16       | 4.94%   |
| NVMe | 12       | 3.7%    |
| SCSI | 3        | 0.93%   |
| SAS  | 1        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Intel       | 187      | 67.75%  |
| AMD         | 88       | 31.88%  |
| PowerMac7,2 | 1        | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 5        | 1.81%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 5        | 1.81%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 1.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 1.81%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 5        | 1.81%   |
| Intel Pentium 4 CPU 2.80GHz                 | 4        | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.45%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.45%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 1.45%   |
| AMD Athlon II X2 250 Processor              | 4        | 1.45%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 4        | 1.45%   |
| AMD Athlon 64 Processor 3000+               | 4        | 1.45%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 3        | 1.09%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.09%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 1.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.09%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.09%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.09%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 1.09%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 1.09%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.09%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.09%   |
| AMD Athlon II X2 215 Processor              | 3        | 1.09%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 3        | 1.09%   |
| AMD Athlon 64 X2 Dual Core Processor 4000+  | 3        | 1.09%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 2        | 0.72%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 0.72%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.72%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2        | 0.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.72%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 0.72%   |
| Intel Celeron CPU 2.66GHz                   | 2        | 0.72%   |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 0.72%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 0.72%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 2        | 0.72%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.72%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+  | 2        | 0.72%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 0.72%   |
| AMD Athlon 64 Processor 3500+               | 2        | 0.72%   |
| AMD Athlon 64 Processor 3200+               | 2        | 0.72%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 2        | 0.72%   |
| PowerMac7,2 PPC970, altivec supported       | 1        | 0.36%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.36%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 0.36%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 1        | 0.36%   |
| Intel Xeon CPU E5-1603 0 @ 2.80GHz          | 1        | 0.36%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 0.36%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.36%   |
| Intel Pentium III (Coppermine)              | 1        | 0.36%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.36%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.36%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.36%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 13.77%  |
| Intel Core 2 Duo        | 21       | 7.61%   |
| Intel Core i7           | 20       | 7.25%   |
| AMD Athlon 64 X2        | 16       | 5.8%    |
| Intel Core i3           | 15       | 5.43%   |
| Intel Celeron           | 15       | 5.43%   |
| Intel Pentium 4         | 13       | 4.71%   |
| Intel Atom              | 13       | 4.71%   |
| AMD Ryzen 5             | 10       | 3.62%   |
| AMD Athlon II X2        | 10       | 3.62%   |
| Intel Pentium Dual-Core | 9        | 3.26%   |
| Intel Core 2 Quad       | 9        | 3.26%   |
| Intel Xeon              | 8        | 2.9%    |
| Intel Pentium Dual      | 8        | 2.9%    |
| Intel Core 2            | 8        | 2.9%    |
| AMD Athlon 64           | 8        | 2.9%    |
| AMD Ryzen 7             | 5        | 1.81%   |
| AMD A10                 | 5        | 1.81%   |
| Intel Pentium           | 4        | 1.45%   |
| AMD Ryzen 3             | 4        | 1.45%   |
| AMD FX                  | 4        | 1.45%   |
| AMD GX                  | 3        | 1.09%   |
| Intel Pentium D         | 2        | 0.72%   |
| AMD Sempron             | 2        | 0.72%   |
| AMD Phenom II X4        | 2        | 0.72%   |
| AMD E1                  | 2        | 0.72%   |
| AMD E                   | 2        | 0.72%   |
| AMD Athlon X4           | 2        | 0.72%   |
| Other                   | 1        | 0.36%   |
| Intel Pentium III       | 1        | 0.36%   |
| Intel Pentium Gold      | 1        | 0.36%   |
| Intel Genuine           | 1        | 0.36%   |
| Intel Core i9           | 1        | 0.36%   |
| AMD Ryzen Threadripper  | 1        | 0.36%   |
| AMD Quad-Core Opteron   | 1        | 0.36%   |
| AMD Phenom II X3        | 1        | 0.36%   |
| AMD Phenom              | 1        | 0.36%   |
| AMD Opteron             | 1        | 0.36%   |
| AMD C-70                | 1        | 0.36%   |
| AMD C-50                | 1        | 0.36%   |
| AMD Athlon X2           | 1        | 0.36%   |
| AMD Athlon II X4        | 1        | 0.36%   |
| AMD Athlon II X3        | 1        | 0.36%   |
| AMD Athlon              | 1        | 0.36%   |
| AMD A4                  | 1        | 0.36%   |
| AMD A12                 | 1        | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 126      | 45.65%  |
| 4      | 91       | 32.97%  |
| 1      | 34       | 12.32%  |
| 6      | 11       | 3.99%   |
| 8      | 7        | 2.54%   |
| 3      | 3        | 1.09%   |
| 12     | 2        | 0.72%   |
| 64     | 1        | 0.36%   |
| 10     | 1        | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 273      | 98.91%  |
| 2      | 3        | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 186      | 67.39%  |
| 2      | 89       | 32.25%  |
| 8      | 1        | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 266      | 96.38%  |
| 32-bit         | 8        | 2.9%    |
| Unknown        | 2        | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 24.19%  |
| 0x206a7    | 20       | 7.22%   |
| 0x1067a    | 19       | 6.86%   |
| 0x306c3    | 13       | 4.69%   |
| 0x306a9    | 11       | 3.97%   |
| 0x6fd      | 9        | 3.25%   |
| 0x6fb      | 8        | 2.89%   |
| 0x6f2      | 5        | 1.81%   |
| 0x406c4    | 5        | 1.81%   |
| 0x30678    | 5        | 1.81%   |
| 0x08701021 | 5        | 1.81%   |
| 0x06001119 | 5        | 1.81%   |
| 0x010000c8 | 5        | 1.81%   |
| 0xf41      | 4        | 1.44%   |
| 0x906e9    | 4        | 1.44%   |
| 0x20655    | 4        | 1.44%   |
| 0x10676    | 4        | 1.44%   |
| 0x0700010f | 4        | 1.44%   |
| 0x06000852 | 4        | 1.44%   |
| 0xf65      | 3        | 1.08%   |
| 0xf49      | 3        | 1.08%   |
| 0x6f6      | 3        | 1.08%   |
| 0x106ca    | 3        | 1.08%   |
| 0x05000119 | 3        | 1.08%   |
| 0x010000db | 3        | 1.08%   |
| 0x010000c7 | 3        | 1.08%   |
| 0xf43      | 2        | 0.72%   |
| 0xf29      | 2        | 0.72%   |
| 0xa0655    | 2        | 0.72%   |
| 0xa0653    | 2        | 0.72%   |
| 0x506e3    | 2        | 0.72%   |
| 0x306f2    | 2        | 0.72%   |
| 0x206d7    | 2        | 0.72%   |
| 0x08701013 | 2        | 0.72%   |
| 0x0800820d | 2        | 0.72%   |
| 0x06003106 | 2        | 0.72%   |
| 0xf64      | 1        | 0.36%   |
| 0xf4a      | 1        | 0.36%   |
| 0xf34      | 1        | 0.36%   |
| 0xf33      | 1        | 0.36%   |
| 0xf12      | 1        | 0.36%   |
| 0x906eb    | 1        | 0.36%   |
| 0x906ea    | 1        | 0.36%   |
| 0x806ea    | 1        | 0.36%   |
| 0x706a8    | 1        | 0.36%   |
| 0x706a1    | 1        | 0.36%   |
| 0x6f7      | 1        | 0.36%   |
| 0x681      | 1        | 0.36%   |
| 0x406c3    | 1        | 0.36%   |
| 0x40651    | 1        | 0.36%   |
| 0x306e4    | 1        | 0.36%   |
| 0x30661    | 1        | 0.36%   |
| 0x106e5    | 1        | 0.36%   |
| 0x106c2    | 1        | 0.36%   |
| 0x106a5    | 1        | 0.36%   |
| 0x106a4    | 1        | 0.36%   |
| 0x10677    | 1        | 0.36%   |
| 0x0a50000c | 1        | 0.36%   |
| 0x0a201009 | 1        | 0.36%   |
| 0x08600103 | 1        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Core          | 29       | 10.51%  |
| Penryn        | 27       | 9.78%   |
| K8 Hammer     | 27       | 9.78%   |
| SandyBridge   | 25       | 9.06%   |
| Haswell       | 22       | 7.97%   |
| NetBurst      | 19       | 6.88%   |
| K10           | 19       | 6.88%   |
| IvyBridge     | 18       | 6.52%   |
| Silvermont    | 12       | 4.35%   |
| Zen 2         | 9        | 3.26%   |
| Piledriver    | 9        | 3.26%   |
| Zen+          | 7        | 2.54%   |
| KabyLake      | 7        | 2.54%   |
| CometLake     | 6        | 2.17%   |
| Bonnell       | 6        | 2.17%   |
| Skylake       | 5        | 1.81%   |
| Jaguar        | 5        | 1.81%   |
| Westmere      | 4        | 1.45%   |
| Nehalem       | 4        | 1.45%   |
| Bobcat        | 4        | 1.45%   |
| Zen 3         | 2        | 0.72%   |
| Zen           | 2        | 0.72%   |
| Steamroller   | 2        | 0.72%   |
| Goldmont plus | 2        | 0.72%   |
| Excavator     | 2        | 0.72%   |
| P6            | 1        | 0.36%   |
| Unknown       | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 97       | 33.8%   |
| Nvidia                           | 95       | 33.1%   |
| AMD                              | 90       | 31.36%  |
| VIA Technologies                 | 3        | 1.05%   |
| Silicon Integrated Systems [SiS] | 1        | 0.35%   |
| Matrox Electronics Systems       | 1        | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15       | 4.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9        | 2.98%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 8        | 2.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 7        | 2.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 2.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7        | 2.32%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7        | 2.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6        | 1.99%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5        | 1.66%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5        | 1.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 1.66%   |
| Intel 82865G Integrated Graphics Controller                                              | 5        | 1.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 1.66%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 1.66%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4        | 1.32%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.32%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 1.32%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 1.32%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 4        | 1.32%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3        | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 0.99%   |
| Intel HD Graphics 530                                                                    | 3        | 0.99%   |
| AMD RV370 [Radeon X300]                                                                  | 3        | 0.99%   |
| AMD RV370 [Radeon X300 SE]                                                               | 3        | 0.99%   |
| AMD RS690 [Radeon X1200]                                                                 | 3        | 0.99%   |
| AMD Richland [Radeon HD 8670D]                                                           | 3        | 0.99%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 2        | 0.66%   |
| Nvidia NV44A [GeForce 6200]                                                              | 2        | 0.66%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.66%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.66%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2        | 0.66%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 0.66%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 2        | 0.66%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 2        | 0.66%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 2        | 0.66%   |
| Nvidia C73 [GeForce 7100 / nForce 620i]                                                  | 2        | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.66%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 0.66%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 0.66%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.66%   |
| Intel 82G965 Integrated Graphics Controller                                              | 2        | 0.66%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.66%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.66%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2        | 0.66%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 0.66%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 2        | 0.66%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 2        | 0.66%   |
| AMD RV350 [Radeon 9550/9600/X1050 Series]                                                | 2        | 0.66%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 0.66%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 0.66%   |
| AMD RS780 [Radeon HD 3200]                                                               | 2        | 0.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.66%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 0.66%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 0.66%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 93       | 33.45%  |
| 1 x Nvidia   | 88       | 31.65%  |
| 1 x AMD      | 76       | 27.34%  |
| 2 x AMD      | 12       | 4.32%   |
| 1 x VIA      | 3        | 1.08%   |
| 2 x Nvidia   | 2        | 0.72%   |
| AMD + Nvidia | 2        | 0.72%   |
| 1 x SiS      | 1        | 0.36%   |
| 1 x Matrox   | 1        | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 225      | 80.65%  |
| Proprietary | 40       | 14.34%  |
| Unknown     | 14       | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 104      | 37.28%  |
| 0.01-0.5   | 82       | 29.39%  |
| 0.51-1.0   | 37       | 13.26%  |
| 1.01-2.0   | 33       | 11.83%  |
| 3.01-4.0   | 11       | 3.94%   |
| 7.01-8.0   | 5        | 1.79%   |
| 2.01-3.0   | 3        | 1.08%   |
| 8.01-16.0  | 3        | 1.08%   |
| 5.01-6.0   | 1        | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 49       | 18.63%  |
| Dell                    | 31       | 11.79%  |
| Goldstar                | 23       | 8.75%   |
| Acer                    | 19       | 7.22%   |
| Hewlett-Packard         | 15       | 5.7%    |
| AOC                     | 14       | 5.32%   |
| Philips                 | 12       | 4.56%   |
| BenQ                    | 11       | 4.18%   |
| Ancor Communications    | 9        | 3.42%   |
| Vizio                   | 6        | 2.28%   |
| Unknown                 | 6        | 2.28%   |
| Lenovo                  | 6        | 2.28%   |
| Iiyama                  | 4        | 1.52%   |
| Sony                    | 3        | 1.14%   |
| NEC Computers           | 3        | 1.14%   |
| LG Electronics          | 3        | 1.14%   |
| ___                     | 2        | 0.76%   |
| Sceptre Tech            | 2        | 0.76%   |
| Positivo                | 2        | 0.76%   |
| Plain Tree Systems      | 2        | 0.76%   |
| LG Display              | 2        | 0.76%   |
| IOD                     | 2        | 0.76%   |
| Fujitsu Siemens         | 2        | 0.76%   |
| FL_                     | 2        | 0.76%   |
| Elo Touch               | 2        | 0.76%   |
| Eizo                    | 2        | 0.76%   |
| Vestel                  | 1        | 0.38%   |
| Unknown (ADA)           | 1        | 0.38%   |
| Toshiba                 | 1        | 0.38%   |
| STD                     | 1        | 0.38%   |
| Proview                 | 1        | 0.38%   |
| Pioneer                 | 1        | 0.38%   |
| Panasonic               | 1        | 0.38%   |
| MSI                     | 1        | 0.38%   |
| MOT                     | 1        | 0.38%   |
| Lite-On                 | 1        | 0.38%   |
| Lenovo Group Limited    | 1        | 0.38%   |
| InfoVision              | 1        | 0.38%   |
| IBM                     | 1        | 0.38%   |
| HVR                     | 1        | 0.38%   |
| HPN                     | 1        | 0.38%   |
| Hitachi                 | 1        | 0.38%   |
| HannStar Display        | 1        | 0.38%   |
| HannStar                | 1        | 0.38%   |
| GDH                     | 1        | 0.38%   |
| Gateway                 | 1        | 0.38%   |
| Element                 | 1        | 0.38%   |
| DPL                     | 1        | 0.38%   |
| CVT                     | 1        | 0.38%   |
| Compaq Computer         | 1        | 0.38%   |
| Chi Mei Optoelectronics | 1        | 0.38%   |
| BLS                     | 1        | 0.38%   |
| ASUSTek Computer        | 1        | 0.38%   |
| Arnos Instruments       | 1        | 0.38%   |
| Apple                   | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 3        | 1.12%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 3        | 1.12%   |
| ___ LCDTV16 ___0101 1360x768                                          | 2        | 0.74%   |
| Vizio D39h-D0 VIZ1002 1366x768 853x479mm 38.5-inch                    | 2        | 0.74%   |
| Samsung Electronics SyncMaster SAM0119 1280x1024 352x264mm 17.3-inch  | 2        | 0.74%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 0.74%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 0.74%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 2        | 0.74%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 2        | 0.74%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 0.74%   |
| Elo Touch elotouch.com ELO1925 1280x1024 376x301mm 19.0-inch          | 2        | 0.74%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 0.74%   |
| Dell ST2410 DELA05D 1920x1080 531x299mm 24.0-inch                     | 2        | 0.74%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                     | 2        | 0.74%   |
| BenQ GW2450H BNQ78C1 1920x1080 530x300mm 24.0-inch                    | 2        | 0.74%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 2        | 0.74%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                        | 2        | 0.74%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 0.74%   |
| Acer AL1716 ACR06B4 1280x1024 338x271mm 17.1-inch                     | 2        | 0.74%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.37%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1        | 0.37%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 1        | 0.37%   |
| Vizio E471VLE VIZ0090 1920x1080 1040x590mm 47.1-inch                  | 1        | 0.37%   |
| Vizio D32h-F0 VIZ1028 1366x768 700x390mm 31.5-inch                    | 1        | 0.37%   |
| Vestel LCD Monitor 49UHD_LCD_TV 3840x2160                             | 1        | 0.37%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.37%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.37%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.37%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.37%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.37%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.37%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                            | 1        | 0.37%   |
| Unknown LCD Monitor 2160 1920x1080 360x270mm 17.7-inch                | 1        | 0.37%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.37%   |
| Toshiba 50UHD_LCD_TV TSB3700 1920x1080 1360x768mm 61.5-inch           | 1        | 0.37%   |
| STD Monitor STD0001 1920x1080                                         | 1        | 0.37%   |
| Sony TV SNYAA01 1360x768                                              | 1        | 0.37%   |
| Sony TV SNY4803 1920x1080 1107x623mm 50.0-inch                        | 1        | 0.37%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.37%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1        | 0.37%   |
| Sceptre Tech E325BV-HDH SPT0C84 1360x768 700x390mm 31.5-inch          | 1        | 0.37%   |
| Samsung Electronics T24C350 SAM0ABF 1920x1080 530x300mm 24.0-inch     | 1        | 0.37%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0427 1920x1200                      | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM030C 1680x1050 474x296mm 22.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM01DF 1280x1024 376x301mm 19.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 90       | 34.09%  |
| 1280x1024 (SXGA)   | 51       | 19.32%  |
| 1680x1050 (WSXGA+) | 23       | 8.71%   |
| 1366x768 (WXGA)    | 20       | 7.58%   |
| 1440x900 (WXGA+)   | 12       | 4.55%   |
| 2560x1440 (QHD)    | 11       | 4.17%   |
| 1600x900 (HD+)     | 9        | 3.41%   |
| 1024x768 (XGA)     | 9        | 3.41%   |
| 1920x1200 (WUXGA)  | 7        | 2.65%   |
| 3840x2160 (4K)     | 5        | 1.89%   |
| 1360x768           | 5        | 1.89%   |
| Unknown            | 3        | 1.14%   |
| 3600x1200          | 2        | 0.76%   |
| 3440x1440          | 2        | 0.76%   |
| 2560x1080          | 2        | 0.76%   |
| 2048x1536          | 2        | 0.76%   |
| 1280x800 (WXGA)    | 2        | 0.76%   |
| 1280x720 (HD)      | 2        | 0.76%   |
| 5760x2160          | 1        | 0.38%   |
| 2560x1600          | 1        | 0.38%   |
| 2288x1287          | 1        | 0.38%   |
| 2160x1200          | 1        | 0.38%   |
| 1600x1200          | 1        | 0.38%   |
| 1280x768           | 1        | 0.38%   |
| 1152x864           | 1        | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 33       | 12.6%   |
| 24      | 32       | 12.21%  |
| 19      | 26       | 9.92%   |
| Unknown | 24       | 9.16%   |
| 21      | 23       | 8.78%   |
| 23      | 20       | 7.63%   |
| 15      | 16       | 6.11%   |
| 22      | 15       | 5.73%   |
| 20      | 14       | 5.34%   |
| 27      | 13       | 4.96%   |
| 18      | 13       | 4.96%   |
| 31      | 5        | 1.91%   |
| 72      | 3        | 1.15%   |
| 34      | 3        | 1.15%   |
| 14      | 3        | 1.15%   |
| 41      | 2        | 0.76%   |
| 39      | 2        | 0.76%   |
| 38      | 2        | 0.76%   |
| 84      | 1        | 0.38%   |
| 65      | 1        | 0.38%   |
| 55      | 1        | 0.38%   |
| 47      | 1        | 0.38%   |
| 43      | 1        | 0.38%   |
| 42      | 1        | 0.38%   |
| 40      | 1        | 0.38%   |
| 32      | 1        | 0.38%   |
| 29      | 1        | 0.38%   |
| 26      | 1        | 0.38%   |
| 13      | 1        | 0.38%   |
| 11      | 1        | 0.38%   |
| 7       | 1        | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 66       | 25.58%  |
| 501-600     | 65       | 25.19%  |
| 301-350     | 45       | 17.44%  |
| 351-400     | 27       | 10.47%  |
| Unknown     | 24       | 9.3%    |
| 601-700     | 7        | 2.71%   |
| 801-900     | 5        | 1.94%   |
| 701-800     | 4        | 1.55%   |
| 1501-2000   | 4        | 1.55%   |
| 901-1000    | 4        | 1.55%   |
| 201-300     | 3        | 1.16%   |
| 1001-1500   | 3        | 1.16%   |
| 101-200     | 1        | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 124      | 49.21%  |
| 5/4     | 48       | 19.05%  |
| 16/10   | 38       | 15.08%  |
| Unknown | 20       | 7.94%   |
| 4/3     | 15       | 5.95%   |
| 21/9    | 4        | 1.59%   |
| 6/5     | 2        | 0.79%   |
| 3/2     | 1        | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 77       | 29.73%  |
| 151-200        | 49       | 18.92%  |
| 141-150        | 37       | 14.29%  |
| Unknown        | 24       | 9.27%   |
| 101-110        | 16       | 6.18%   |
| 301-350        | 15       | 5.79%   |
| 501-1000       | 10       | 3.86%   |
| 351-500        | 9        | 3.47%   |
| 251-300        | 7        | 2.7%    |
| More than 1000 | 6        | 2.32%   |
| 81-90          | 2        | 0.77%   |
| 131-140        | 2        | 0.77%   |
| 51-60          | 1        | 0.39%   |
| 1-40           | 1        | 0.39%   |
| 121-130        | 1        | 0.39%   |
| 111-120        | 1        | 0.39%   |
| 91-100         | 1        | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 169      | 66.8%   |
| 101-120 | 36       | 14.23%  |
| Unknown | 24       | 9.49%   |
| 1-50    | 11       | 4.35%   |
| 121-160 | 11       | 4.35%   |
| 161-240 | 2        | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 244      | 87.46%  |
| 2     | 18       | 6.45%   |
| 0     | 14       | 5.02%   |
| 3     | 2        | 0.72%   |
| 4     | 1        | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 156      | 39%     |
| Intel                           | 76       | 19%     |
| Nvidia                          | 30       | 7.5%    |
| Qualcomm Atheros                | 28       | 7%      |
| Ralink Technology               | 24       | 6%      |
| Broadcom                        | 11       | 2.75%   |
| Samsung Electronics             | 8        | 2%      |
| Broadcom Limited                | 8        | 2%      |
| VIA Technologies                | 6        | 1.5%    |
| TP-Link                         | 6        | 1.5%    |
| Ralink                          | 6        | 1.5%    |
| Marvell Technology Group        | 5        | 1.25%   |
| D-Link System                   | 4        | 1%      |
| Qualcomm Atheros Communications | 3        | 0.75%   |
| Huawei Technologies             | 3        | 0.75%   |
| D-Link                          | 3        | 0.75%   |
| Belkin Components               | 3        | 0.75%   |
| ULi Electronics                 | 2        | 0.5%    |
| 3Com                            | 2        | 0.5%    |
| ZyXEL Communications            | 1        | 0.25%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.25%   |
| U-Blox                          | 1        | 0.25%   |
| T & A Mobile Phones             | 1        | 0.25%   |
| Sitecom Europe                  | 1        | 0.25%   |
| NetGear                         | 1        | 0.25%   |
| Motorola PCS                    | 1        | 0.25%   |
| LSI                             | 1        | 0.25%   |
| Logitec                         | 1        | 0.25%   |
| JMicron Technology              | 1        | 0.25%   |
| Intersil                        | 1        | 0.25%   |
| ASUSTek Computer                | 1        | 0.25%   |
| ASIX Electronics                | 1        | 0.25%   |
| Aquantia                        | 1        | 0.25%   |
| Apple                           | 1        | 0.25%   |
| ADMtek                          | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 111      | 26.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16       | 3.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 15       | 3.57%   |
| Nvidia MCP61 Ethernet                                                   | 14       | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10       | 2.38%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 7        | 1.67%   |
| Ralink MT7601U Wireless Adapter                                         | 7        | 1.67%   |
| Nvidia CK804 Ethernet Controller                                        | 6        | 1.43%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 6        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5        | 1.19%   |
| Ralink RT5370 Wireless Adapter                                          | 5        | 1.19%   |
| Intel Ethernet Connection I217-LM                                       | 5        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                    | 5        | 1.19%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 5        | 1.19%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 4        | 0.95%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 4        | 0.95%   |
| Ralink RT5572 Wireless Adapter                                          | 4        | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4        | 0.95%   |
| Nvidia MCP73 Ethernet                                                   | 4        | 0.95%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                       | 4        | 0.95%   |
| Intel Wireless 7260                                                     | 4        | 0.95%   |
| Realtek RTL8187 Wireless Adapter                                        | 3        | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3        | 0.71%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 3        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3        | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3        | 0.71%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3        | 0.71%   |
| Intel Ethernet Connection I217-V                                        | 3        | 0.71%   |
| Intel 82579V Gigabit Network Connection                                 | 3        | 0.71%   |
| Intel 82574L Gigabit Network Connection                                 | 3        | 0.71%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                     | 3        | 0.71%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 2        | 0.48%   |
| ULi ULi 1689,1573 integrated ethernet.                                  | 2        | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2        | 0.48%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 2        | 0.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2        | 0.48%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 2        | 0.48%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2        | 0.48%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 2        | 0.48%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2        | 0.48%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 2        | 0.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2        | 0.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2        | 0.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2        | 0.48%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 2        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2        | 0.48%   |
| Nvidia MCP55 Ethernet                                                   | 2        | 0.48%   |
| Nvidia CK8S Ethernet Controller                                         | 2        | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 2        | 0.48%   |
| Intel Wireless-AC 9260                                                  | 2        | 0.48%   |
| Intel Wireless 7265                                                     | 2        | 0.48%   |
| Intel 82566DM Gigabit Network Connection                                | 2        | 0.48%   |
| Intel 82562V-2 10/100 Network Connection                                | 2        | 0.48%   |
| Huawei JAT-LX1                                                          | 2        | 0.48%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                         | 2        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 2        | 0.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2        | 0.48%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU] | 2        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 24       | 22.02%  |
| Realtek Semiconductor           | 21       | 19.27%  |
| Qualcomm Atheros                | 17       | 15.6%   |
| Intel                           | 13       | 11.93%  |
| TP-Link                         | 6        | 5.5%    |
| Ralink                          | 6        | 5.5%    |
| Broadcom                        | 4        | 3.67%   |
| Qualcomm Atheros Communications | 3        | 2.75%   |
| Belkin Components               | 3        | 2.75%   |
| D-Link System                   | 2        | 1.83%   |
| D-Link                          | 2        | 1.83%   |
| Broadcom Limited                | 2        | 1.83%   |
| ZyXEL Communications            | 1        | 0.92%   |
| Sitecom Europe                  | 1        | 0.92%   |
| Samsung Electronics             | 1        | 0.92%   |
| NetGear                         | 1        | 0.92%   |
| Logitec                         | 1        | 0.92%   |
| ASUSTek Computer                | 1        | 0.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                | 7        | 6.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 5        | 4.59%   |
| Ralink RT5370 Wireless Adapter                                                 | 5        | 4.59%   |
| Ralink RT5572 Wireless Adapter                                                 | 4        | 3.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 4        | 3.67%   |
| Intel Wireless 7260                                                            | 4        | 3.67%   |
| Realtek RTL8187 Wireless Adapter                                               | 3        | 2.75%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3        | 2.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 3        | 2.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 2        | 1.83%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                          | 2        | 1.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2        | 1.83%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 2        | 1.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 1.83%   |
| Ralink RT2501/RT2573 Wireless Adapter                                          | 2        | 1.83%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 2        | 1.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2        | 1.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 2        | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.83%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 1.83%   |
| Intel Wireless-AC 9260                                                         | 2        | 1.83%   |
| Intel Wireless 7265                                                            | 2        | 1.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 2        | 1.83%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU]        | 2        | 1.83%   |
| ZyXEL ZyAIR G-202 802.11bg                                                     | 1        | 0.92%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1        | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.92%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                | 1        | 0.92%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                               | 1        | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.92%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                | 1        | 0.92%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1        | 0.92%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                        | 1        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.92%   |
| Realtek 802.11ac NIC                                                           | 1        | 0.92%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 0.92%   |
| Ralink RT2070 Wireless Adapter                                                 | 1        | 0.92%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                    | 1        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1        | 0.92%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                           | 1        | 0.92%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1        | 0.92%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 0.92%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 0.92%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                    | 1        | 0.92%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                                      | 1        | 0.92%   |
| Intel Wireless 3165                                                            | 1        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1        | 0.92%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 0.92%   |
| Intel Centrino Advanced-N 6235                                                 | 1        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1        | 0.92%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]              | 1        | 0.92%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]     | 1        | 0.92%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                  | 1        | 0.92%   |
| D-Link 11ac adapter                                                            | 1        | 0.92%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                        | 1        | 0.92%   |
| Broadcom Limited BCM4306 802.11b/g Wireless LAN Controller                     | 1        | 0.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 1        | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 144      | 47.68%  |
| Intel                      | 65       | 21.52%  |
| Nvidia                     | 30       | 9.93%   |
| Qualcomm Atheros           | 13       | 4.3%    |
| Broadcom                   | 8        | 2.65%   |
| Samsung Electronics        | 7        | 2.32%   |
| VIA Technologies           | 6        | 1.99%   |
| Broadcom Limited           | 6        | 1.99%   |
| Marvell Technology Group   | 5        | 1.66%   |
| Huawei Technologies        | 3        | 0.99%   |
| ULi Electronics            | 2        | 0.66%   |
| D-Link System              | 2        | 0.66%   |
| 3Com                       | 2        | 0.66%   |
| ZTE WCDMA Technologies MSM | 1        | 0.33%   |
| T & A Mobile Phones        | 1        | 0.33%   |
| Motorola PCS               | 1        | 0.33%   |
| JMicron Technology         | 1        | 0.33%   |
| D-Link                     | 1        | 0.33%   |
| ASIX Electronics           | 1        | 0.33%   |
| Aquantia                   | 1        | 0.33%   |
| Apple                      | 1        | 0.33%   |
| ADMtek                     | 1        | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 111      | 36.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16       | 5.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15       | 4.87%   |
| Nvidia MCP61 Ethernet                                             | 14       | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 3.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 2.27%   |
| Nvidia CK804 Ethernet Controller                                  | 6        | 1.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 1.62%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.62%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5        | 1.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 1.3%    |
| Nvidia MCP73 Ethernet                                             | 4        | 1.3%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 4        | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 0.97%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.97%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.97%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 3        | 0.97%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.65%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 2        | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.65%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.65%   |
| Nvidia CK8S Ethernet Controller                                   | 2        | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.65%   |
| Intel 82566DM Gigabit Network Connection                          | 2        | 0.65%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.65%   |
| Huawei JAT-LX1                                                    | 2        | 0.65%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 2        | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 0.65%   |
| ZTE WCDMA MSM Z6201V                                              | 1        | 0.32%   |
| T & A Mobile Phones 9010X                                         | 1        | 0.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.32%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.32%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.32%   |
| Motorola PCS XT1058                                               | 1        | 0.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.32%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.32%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.32%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.32%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.32%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.32%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.32%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.32%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.32%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.32%   |
| Intel 82567LM-2 Gigabit Network Connection                        | 1        | 0.32%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.32%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 271      | 71.69%  |
| WiFi     | 104      | 27.51%  |
| Modem    | 2        | 0.53%   |
| Unknown  | 1        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 240      | 76.19%  |
| WiFi     | 75       | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 206      | 74.64%  |
| 2     | 59       | 21.38%  |
| 3     | 7        | 2.54%   |
| 0     | 3        | 1.09%   |
| 6     | 1        | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 241      | 87%     |
| Yes  | 36       | 13%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 16       | 39.02%  |
| Intel                           | 11       | 26.83%  |
| Broadcom                        | 4        | 9.76%   |
| Qualcomm Atheros Communications | 2        | 4.88%   |
| Ralink                          | 1        | 2.44%   |
| Lite-On Technology              | 1        | 2.44%   |
| Integrated System Solution      | 1        | 2.44%   |
| HTC (High Tech Computer)        | 1        | 2.44%   |
| Hewlett-Packard                 | 1        | 2.44%   |
| Fujitsu                         | 1        | 2.44%   |
| Dynex                           | 1        | 2.44%   |
| ASUSTek Computer                | 1        | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 16       | 39.02%  |
| Intel Bluetooth wireless interface                                   | 6        | 14.63%  |
| Qualcomm Atheros AR3011 Bluetooth                                    | 2        | 4.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 4.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 4.88%   |
| Ralink RT3290 Bluetooth                                              | 1        | 2.44%   |
| Lite-On Bluetooth Device                                             | 1        | 2.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 2.44%   |
| Intel AX210 Bluetooth                                                | 1        | 2.44%   |
| Intel AX200 Bluetooth                                                | 1        | 2.44%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 2.44%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1        | 2.44%   |
| Fujitsu Bluetooth Device                                             | 1        | 2.44%   |
| Dynex BCM20702A0                                                     | 1        | 2.44%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 2.44%   |
| Broadcom Bluetooth Device                                            | 1        | 2.44%   |
| ASUS Bluetooth Radio                                                 | 1        | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 155      | 40.26%  |
| AMD                                          | 89       | 23.12%  |
| Nvidia                                       | 86       | 22.34%  |
| C-Media Electronics                          | 11       | 2.86%   |
| Creative Labs                                | 9        | 2.34%   |
| VIA Technologies                             | 8        | 2.08%   |
| XMOS                                         | 3        | 0.78%   |
| ULi Electronics                              | 2        | 0.52%   |
| Texas Instruments                            | 2        | 0.52%   |
| Logitech                                     | 2        | 0.52%   |
| Generalplus Technology                       | 2        | 0.52%   |
| Creative Technology                          | 2        | 0.52%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.26%   |
| Unknown                                      | 1        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.26%   |
| Razer USA                                    | 1        | 0.26%   |
| KORG                                         | 1        | 0.26%   |
| Guillemot                                    | 1        | 0.26%   |
| GN Netcom                                    | 1        | 0.26%   |
| Focusrite-Novation                           | 1        | 0.26%   |
| ESI                                          | 1        | 0.26%   |
| Elgato Systems                               | 1        | 0.26%   |
| Cirrus Logic                                 | 1        | 0.26%   |
| BEHRINGER International                      | 1        | 0.26%   |
| ASUSTek Computer                             | 1        | 0.26%   |
| Asahi Kasei Microsystems                     | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 26       | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 21       | 4.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 20       | 4.58%   |
| Nvidia MCP61 High Definition Audio                                                | 15       | 3.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15       | 3.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 15       | 3.43%   |
| Nvidia High Definition Audio Controller                                           | 14       | 3.2%    |
| AMD FCH Azalia Controller                                                         | 12       | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 2.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 10       | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 10       | 2.29%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 1.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 1.6%    |
| AMD Kabini HDMI/DP Audio                                                          | 7        | 1.6%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 1.37%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5        | 1.14%   |
| Nvidia CK804 AC'97 Audio Controller                                               | 5        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.14%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 5        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.14%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 4        | 0.92%   |
| Nvidia MCP73 High Definition Audio                                                | 4        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 0.92%   |
| AMD Wrestler HDMI Audio                                                           | 4        | 0.92%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 0.92%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 4        | 0.92%   |
| XMOS Mayfield Audio                                                               | 3        | 0.69%   |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 0.69%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 0.69%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 3        | 0.69%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 3        | 0.69%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.69%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                            | 3        | 0.69%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 2        | 0.46%   |
| Nvidia MCP51 High Definition Audio                                                | 2        | 0.46%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 0.46%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.46%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.46%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.46%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.46%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2        | 0.46%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.46%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.46%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 2        | 0.46%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 0.46%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 0.46%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 50       | 26.32%  |
| Samsung Electronics | 28       | 14.74%  |
| Kingston            | 27       | 14.21%  |
| SK Hynix            | 19       | 10%     |
| Crucial             | 10       | 5.26%   |
| G.Skill             | 9        | 4.74%   |
| Corsair             | 9        | 4.74%   |
| Micron Technology   | 7        | 3.68%   |
| Nanya Technology    | 6        | 3.16%   |
| A-DATA Technology   | 3        | 1.58%   |
| TIMETEC             | 2        | 1.05%   |
| Patriot             | 2        | 1.05%   |
| Elpida              | 2        | 1.05%   |
| Unknown (ABCD)      | 1        | 0.53%   |
| Unknown (07FB)      | 1        | 0.53%   |
| Unifosa             | 1        | 0.53%   |
| Transcend           | 1        | 0.53%   |
| Teikon              | 1        | 0.53%   |
| Team                | 1        | 0.53%   |
| Smart               | 1        | 0.53%   |
| Ramaxel Technology  | 1        | 0.53%   |
| Qimonda             | 1        | 0.53%   |
| PRINCETON           | 1        | 0.53%   |
| Infineon            | 1        | 0.53%   |
| Golden Empire       | 1        | 0.53%   |
| e2e4                | 1        | 0.53%   |
| ASint Technology    | 1        | 0.53%   |
| 48spaces            | 1        | 0.53%   |
| Unknown             | 1        | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 4        | 1.92%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 3        | 1.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 2        | 0.96%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 2        | 0.96%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 2        | 0.96%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 2        | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 2        | 0.96%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 2        | 0.96%   |
| Samsung RAM M3 78T6553EZS-CE6 512MB DIMM DDR 667MT/s           | 2        | 0.96%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s             | 2        | 0.96%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                   | 2        | 0.96%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s         | 2        | 0.96%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 0.96%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 2        | 0.96%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.48%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                   | 1        | 0.48%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1        | 0.48%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                     | 1        | 0.48%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1        | 0.48%   |
| Unknown RAM Module 512MB DIMM 333MT/s                          | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM SDRAM                           | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM                                 | 1        | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 1333MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 1        | 0.48%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1        | 0.48%   |
| Unknown RAM Module 256MB DIMM DRAM                             | 1        | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s                    | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                   | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                    | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM 41632MT/s                       | 1        | 0.48%   |
| Unknown RAM Module 2048MB DIMM                                 | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR 800MT/s                        | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM                                    | 1        | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                    | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR                             | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1        | 0.48%   |
| Unknown RAM Module 1024MB DIMM                                 | 1        | 0.48%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s       | 1        | 0.48%   |
| Unknown RAM CS4S2666D19161C 16GB SODIMM DDR4 2667MT/s          | 1        | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.48%   |
| Unknown (07FB) RAM GSA16G4SCL196P-26 16GB SODIMM DDR4 2667MT/s | 1        | 0.48%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 1        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 59       | 35.54%  |
| DDR4    | 32       | 19.28%  |
| DDR2    | 29       | 17.47%  |
| Unknown | 19       | 11.45%  |
| SDRAM   | 15       | 9.04%   |
| DDR     | 10       | 6.02%   |
| LPDDR4  | 1        | 0.6%    |
| DRAM    | 1        | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 144      | 89.44%  |
| SODIMM | 17       | 10.56%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 60       | 33.33%  |
| 8192  | 39       | 21.67%  |
| 4096  | 35       | 19.44%  |
| 1024  | 22       | 12.22%  |
| 16384 | 10       | 5.56%   |
| 512   | 7        | 3.89%   |
| 256   | 4        | 2.22%   |
| 65536 | 1        | 0.56%   |
| 32768 | 1        | 0.56%   |
| 128   | 1        | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 35       | 19.55%  |
| 1333    | 19       | 10.61%  |
| 800     | 19       | 10.61%  |
| Unknown | 12       | 6.7%    |
| 2133    | 10       | 5.59%   |
| 667     | 10       | 5.59%   |
| 400     | 8        | 4.47%   |
| 3200    | 7        | 3.91%   |
| 2667    | 6        | 3.35%   |
| 2400    | 5        | 2.79%   |
| 1066    | 5        | 2.79%   |
| 533     | 5        | 2.79%   |
| 3600    | 4        | 2.23%   |
| 2048    | 4        | 2.23%   |
| 1867    | 4        | 2.23%   |
| 333     | 4        | 2.23%   |
| 49926   | 3        | 1.68%   |
| 1067    | 3        | 1.68%   |
| 3466    | 2        | 1.12%   |
| 3000    | 2        | 1.12%   |
| 1866    | 2        | 1.12%   |
| 266     | 2        | 1.12%   |
| 41632   | 1        | 0.56%   |
| 3151    | 1        | 0.56%   |
| 2800    | 1        | 0.56%   |
| 2733    | 1        | 0.56%   |
| 2666    | 1        | 0.56%   |
| 1800    | 1        | 0.56%   |
| 1639    | 1        | 0.56%   |
| 1334    | 1        | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 50%     |
| Samsung Electronics | 3        | 37.5%   |
| Brother Industries  | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 12.5%   |
| Samsung SCX-3400 Series                 | 1        | 12.5%   |
| Samsung M2020 Series                    | 1        | 12.5%   |
| HP PSC 1500 series                      | 1        | 12.5%   |
| HP OfficeJet 4650 series                | 1        | 12.5%   |
| HP DeskJet D2460                        | 1        | 12.5%   |
| HP DeskJet 3630 series                  | 1        | 12.5%   |
| Brother Printer                         | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 66.67%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet 2400c        | 1        | 33.33%  |
| HP HP4470C              | 1        | 33.33%  |
| Canon CanoScan LiDE 220 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 20.59%  |
| Microsoft                     | 3        | 8.82%   |
| Samsung Electronics           | 2        | 5.88%   |
| KYE Systems (Mouse Systems)   | 2        | 5.88%   |
| Generalplus Technology        | 2        | 5.88%   |
| GEMBIRD                       | 2        | 5.88%   |
| Chicony Electronics           | 2        | 5.88%   |
| ARC International             | 2        | 5.88%   |
| Apple                         | 2        | 5.88%   |
| Z-Star Microelectronics       | 1        | 2.94%   |
| Sunplus Innovation Technology | 1        | 2.94%   |
| SJ-180517-N                   | 1        | 2.94%   |
| Microdia                      | 1        | 2.94%   |
| LG Electronics                | 1        | 2.94%   |
| Huawei Technologies           | 1        | 2.94%   |
| Guillemot                     | 1        | 2.94%   |
| GEO Semi                      | 1        | 2.94%   |
| Genesys Logic                 | 1        | 2.94%   |
| Acer                          | 1        | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                             | 3        | 8.82%   |
| Samsung Galaxy A5 (MTP)                               | 2        | 5.88%   |
| Logitech Webcam C270                                  | 2        | 5.88%   |
| Logitech HD Webcam C525                               | 2        | 5.88%   |
| Generalplus GENERAL WEBCAM                            | 2        | 5.88%   |
| ARC International Camera                              | 2        | 5.88%   |
| Apple iPhone 5/5C/5S/6/SE                             | 2        | 5.88%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 2.94%   |
| Sunplus Full HD webcam                                | 1        | 2.94%   |
| SJ-180517-N 1080P Webcam                              | 1        | 2.94%   |
| Microdia Webcam Vitade AF                             | 1        | 2.94%   |
| Logitech Webcam C300                                  | 1        | 2.94%   |
| Logitech QuickCam Zoom                                | 1        | 2.94%   |
| Logitech HD Webcam C615                               | 1        | 2.94%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 2.94%   |
| KYE Systems (Mouse Systems) Genius eFace 1325R        | 1        | 2.94%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 1        | 2.94%   |
| Huawei UVC Camera                                     | 1        | 2.94%   |
| Guillemot Hercules HD Sunset                          | 1        | 2.94%   |
| GEO Semi Condor                                       | 1        | 2.94%   |
| Genesys Logic Camera                                  | 1        | 2.94%   |
| GEMBIRD USB2.0 PC CAMERA                              | 1        | 2.94%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 1        | 2.94%   |
| Chicony CNF7042                                       | 1        | 2.94%   |
| Chicony ASUS USB2.0 Webcam                            | 1        | 2.94%   |
| Acer Integrated Camera                                | 1        | 2.94%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| OmniKey     | 1        | 50%     |
| Alcor Micro | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121         | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 231      | 82.5%   |
| 1     | 42       | 15%     |
| 2     | 7        | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 35.85%  |
| Net/wireless             | 9        | 16.98%  |
| Communication controller | 6        | 11.32%  |
| Multimedia controller    | 4        | 7.55%   |
| Unassigned class         | 3        | 5.66%   |
| Sound                    | 3        | 5.66%   |
| Net/ethernet             | 2        | 3.77%   |
| Chipcard                 | 2        | 3.77%   |
| Bluetooth                | 2        | 3.77%   |
| Modem                    | 1        | 1.89%   |
| Dvb card                 | 1        | 1.89%   |
| Camera                   | 1        | 1.89%   |

