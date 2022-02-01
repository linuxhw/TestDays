Lubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_20.04/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [e6c4f7b650](https://linux-hardware.org/?probe=e6c4f7b650) | Aug 30, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | 0CN7X8 A05                  | Server      | [e5766c8331](https://linux-hardware.org/?probe=e5766c8331) | Jul 22, 2021 |
| HP            | 0A1Ch E                     | Desktop     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2383fe9425](https://linux-hardware.org/?probe=2383fe9425) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [e09b0ac6cf](https://linux-hardware.org/?probe=e09b0ac6cf) | Jun 30, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [caa1dadc98](https://linux-hardware.org/?probe=caa1dadc98) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| Samsung       | RC512                       | Notebook    | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | Notebook    | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| ASUSTek       | K8N                         | Desktop     | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | Desktop     | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| HP            | 09C4h                       | Desktop     | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Dell          | 0HY175 A03                  | Desktop     | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | Desktop     | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | Desktop     | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [aa3fceee37](https://linux-hardware.org/?probe=aa3fceee37) | May 17, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| MSI           | H61M-E33                    | Desktop     | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| ASUSTek       | K8N                         | Desktop     | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| HP            | Notebook                    | Notebook    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | imedia S1350                | Desktop     | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [82eb222c26](https://linux-hardware.org/?probe=82eb222c26) | Apr 23, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [f03d856fe1](https://linux-hardware.org/?probe=f03d856fe1) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | Notebook    | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | Notebook    | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [e366c8c206](https://linux-hardware.org/?probe=e366c8c206) | Mar 24, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [0baf745232](https://linux-hardware.org/?probe=0baf745232) | Mar 21, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | S10-3                       | Notebook    | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | XPS 15Z                     | Notebook    | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| ASUSTek       | P53E                        | Notebook    | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Toshiba       | Satellite A660              | Notebook    | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | Notebook    | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | Desktop     | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | Notebook    | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | Notebook    | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | Notebook    | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| HP            | 3048h                       | Desktop     | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | Notebook    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | Notebook    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [304fa83224](https://linux-hardware.org/?probe=304fa83224) | Jan 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [09c2da07b2](https://linux-hardware.org/?probe=09c2da07b2) | Jan 21, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [057c04b2ae](https://linux-hardware.org/?probe=057c04b2ae) | Jan 11, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | Notebook    | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | Board                       | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | Desktop     | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | Notebook    | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | Notebook    | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [f45926d7a7](https://linux-hardware.org/?probe=f45926d7a7) | Dec 11, 2020 |
| Dell          | 0WG864                      | Desktop     | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | Notebook    | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [1c0400a8c0](https://linux-hardware.org/?probe=1c0400a8c0) | Dec 10, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Panasonic     | CF-52PGNBE2M                | Notebook    | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| HP            | 2820h                       | Desktop     | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Pegatron      | Narra6                      | Desktop     | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| Positivo      | S14BW01                     | Notebook    | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | 09F8h                       | Desktop     | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [e6edfc8360](https://linux-hardware.org/?probe=e6edfc8360) | Nov 06, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [2139a80238](https://linux-hardware.org/?probe=2139a80238) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | Notebook    | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | Desktop     | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | Notebook    | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | Notebook    | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | Notebook    | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | Notebook    | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | Notebook    | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | Notebook    | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Acer          | Extensa 4620                | Notebook    | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| ASRock        | G41M-GS3                    | Desktop     | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c1a4649fc7](https://linux-hardware.org/?probe=c1a4649fc7) | Oct 20, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | Notebook    | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | Notebook    | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| MSI           | H97M-E35                    | Desktop     | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [53ecc0af0c](https://linux-hardware.org/?probe=53ecc0af0c) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [9a5387bb3b](https://linux-hardware.org/?probe=9a5387bb3b) | Oct 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [c30f194de1](https://linux-hardware.org/?probe=c30f194de1) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [5c305017e8](https://linux-hardware.org/?probe=5c305017e8) | Sep 13, 2020 |
| Acer          | Aspire 3050                 | Notebook    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| ASRock        | A320M-DGS                   | Desktop     | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Acer          | Aspire 3050                 | Notebook    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | Notebook    | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | Notebook    | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | Notebook    | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | Notebook    | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Google        | Gandof                      | Notebook    | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| Acer          | Aspire ES1-522              | Notebook    | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5e37d8f34b](https://linux-hardware.org/?probe=5e37d8f34b) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [607ce70f10](https://linux-hardware.org/?probe=607ce70f10) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8dcd639b58](https://linux-hardware.org/?probe=8dcd639b58) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50f1173d1b](https://linux-hardware.org/?probe=50f1173d1b) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [95dde54ab4](https://linux-hardware.org/?probe=95dde54ab4) | Aug 24, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1c32470733](https://linux-hardware.org/?probe=1c32470733) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| ASUSTek       | K50C                        | Notebook    | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| Lenovo        | Board                       | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [29919d9aa9](https://linux-hardware.org/?probe=29919d9aa9) | Jul 30, 2020 |
| Lenovo        | SDK0E50515 STD              | Desktop     | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| HP            | ProBook 445 G7              | Notebook    | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| Acer          | V5-171                      | Notebook    | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | Desktop     | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| Positivo      | H14BT58                     | Notebook    | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [a10d8d5d4f](https://linux-hardware.org/?probe=a10d8d5d4f) | Jul 22, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [d9470e64f2](https://linux-hardware.org/?probe=d9470e64f2) | Jul 22, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| IBM           | Board                       | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Dell          | Studio 1555                 | Notebook    | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | Notebook    | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | Q302LA                      | Notebook    | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | Notebook    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | Notebook    | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| HP            | 3396                        | Desktop     | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| Acer          | Swift SF314-52G             | Notebook    | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | Notebook    | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | Notebook    | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | Notebook    | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| HP            | Compaq 615                  | Notebook    | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| MSI           | 0A48                        | Desktop     | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Acer          | Aspire 5734Z                | Notebook    | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| HP            | Pavilion dv5                | Notebook    | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [6e0b7c86d5](https://linux-hardware.org/?probe=6e0b7c86d5) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [9a4a664a94](https://linux-hardware.org/?probe=9a4a664a94) | May 30, 2020 |
| Positivo      | S14CT01                     | Notebook    | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [acacfa8d27](https://linux-hardware.org/?probe=acacfa8d27) | May 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | Notebook    | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| Packard Be... | EN Butterfly s              | Notebook    | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | Desktop     | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| Acer          | Aspire XC-703G              | Desktop     | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | Notebook                    | Notebook    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| HP            | 17E2                        | Mini pc     | [fe57173b3f](https://linux-hardware.org/?probe=fe57173b3f) | May 01, 2020 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [2e3821b18f](https://linux-hardware.org/?probe=2e3821b18f) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 31        | 8.64%   |
| 5.4.0-52-generic           | 22        | 6.13%   |
| 5.4.0-48-generic           | 12        | 3.34%   |
| 5.4.0-47-generic           | 12        | 3.34%   |
| 5.4.0-26-generic           | 12        | 3.34%   |
| 5.4.0-40-generic           | 11        | 3.06%   |
| 5.4.0-29-generic           | 10        | 2.79%   |
| 5.11.0-27-generic          | 10        | 2.79%   |
| 5.4.0-54-generic           | 9         | 2.51%   |
| 5.4.0-33-generic           | 9         | 2.51%   |
| 5.8.0-50-generic           | 8         | 2.23%   |
| 5.11.0-38-generic          | 8         | 2.23%   |
| 5.4.0-65-generic           | 7         | 1.95%   |
| 5.4.0-37-generic           | 7         | 1.95%   |
| 5.8.0-53-generic           | 6         | 1.67%   |
| 5.8.0-41-generic           | 6         | 1.67%   |
| 5.4.0-73-generic           | 6         | 1.67%   |
| 5.4.0-72-generic           | 6         | 1.67%   |
| 5.4.0-67-generic           | 6         | 1.67%   |
| 5.4.0-51-generic           | 6         | 1.67%   |
| 5.11.0-43-generic          | 6         | 1.67%   |
| 5.8.0-45-generic           | 5         | 1.39%   |
| 5.4.0-89-generic           | 5         | 1.39%   |
| 5.4.0-60-generic           | 5         | 1.39%   |
| 5.4.0-58-generic           | 5         | 1.39%   |
| 5.11.0-37-generic          | 5         | 1.39%   |
| 5.8.0-63-generic           | 4         | 1.11%   |
| 5.8.0-59-generic           | 4         | 1.11%   |
| 5.8.0-55-generic           | 4         | 1.11%   |
| 5.4.0-91-generic           | 4         | 1.11%   |
| 5.4.0-77-generic           | 4         | 1.11%   |
| 5.4.0-66-generic           | 4         | 1.11%   |
| 5.4.0-59-generic           | 4         | 1.11%   |
| 5.4.0-56-generic           | 4         | 1.11%   |
| 5.4.0-45-generic           | 4         | 1.11%   |
| 5.4.0-31-generic           | 4         | 1.11%   |
| 5.13.0-27-generic          | 4         | 1.11%   |
| 5.8.0-49-generic           | 3         | 0.84%   |
| 5.8.0-48-generic           | 3         | 0.84%   |
| 5.8.0-43-generic           | 3         | 0.84%   |
| 5.4.0-81-generic           | 3         | 0.84%   |
| 5.4.0-74-generic           | 3         | 0.84%   |
| 5.4.0-62-generic           | 3         | 0.84%   |
| 5.11.0-41-generic          | 3         | 0.84%   |
| 5.11.0-40-generic          | 3         | 0.84%   |
| 5.11.0-34-generic          | 3         | 0.84%   |
| 5.11.0-25-generic          | 3         | 0.84%   |
| 5.4.0-90-generic           | 2         | 0.56%   |
| 5.4.0-80-generic           | 2         | 0.56%   |
| 5.4.0-70-generic           | 2         | 0.56%   |
| 5.4.0-64-generic           | 2         | 0.56%   |
| 5.4.0-39-generic           | 2         | 0.56%   |
| 5.11.0-46-generic          | 2         | 0.56%   |
| 5.11.0-36-generic          | 2         | 0.56%   |
| 5.9.0-050900rc6-lowlatency | 1         | 0.28%   |
| 5.8.0-7630-generic         | 1         | 0.28%   |
| 5.8.0-44-generic           | 1         | 0.28%   |
| 5.8.0-29-lowlatency        | 1         | 0.28%   |
| 5.8.0-29-generic           | 1         | 0.28%   |
| 5.8.0-050800-generic       | 1         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 220       | 66.27%  |
| 5.8.0   | 50        | 15.06%  |
| 5.11.0  | 46        | 13.86%  |
| 5.13.0  | 6         | 1.81%   |
| 5.6.0   | 2         | 0.6%    |
| 5.9.0   | 1         | 0.3%    |
| 5.7.9   | 1         | 0.3%    |
| 5.6.15  | 1         | 0.3%    |
| 5.5.2   | 1         | 0.3%    |
| 5.4.30  | 1         | 0.3%    |
| 5.3.18  | 1         | 0.3%    |
| 5.14.0  | 1         | 0.3%    |
| 5.10.0  | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 221       | 66.57%  |
| 5.8     | 50        | 15.06%  |
| 5.11    | 46        | 13.86%  |
| 5.13    | 6         | 1.81%   |
| 5.6     | 3         | 0.9%    |
| 5.9     | 1         | 0.3%    |
| 5.7     | 1         | 0.3%    |
| 5.5     | 1         | 0.3%    |
| 5.3     | 1         | 0.3%    |
| 5.14    | 1         | 0.3%    |
| 5.10    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 329       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 314       | 94.86%  |
| LXDE       | 6         | 1.81%   |
| GNOME      | 4         | 1.21%   |
| Cinnamon   | 2         | 0.6%    |
| X-Cinnamon | 1         | 0.3%    |
| MATE       | 1         | 0.3%    |
| KDE5       | 1         | 0.3%    |
| KDE        | 1         | 0.3%    |
| i3         | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 310       | 93.94%  |
| Tty     | 17        | 5.15%   |
| Wayland | 2         | 0.61%   |
| Unknown | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 167       | 49.7%   |
| Unknown | 118       | 35.12%  |
| GDM     | 21        | 6.25%   |
| TDM     | 18        | 5.36%   |
| LightDM | 9         | 2.68%   |
| LXDM    | 2         | 0.6%    |
| GDM3    | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 99        | 30.09%  |
| fr_FR   | 36        | 10.94%  |
| pt_BR   | 30        | 9.12%   |
| it_IT   | 19        | 5.78%   |
| de_DE   | 19        | 5.78%   |
| C       | 17        | 5.17%   |
| en_GB   | 16        | 4.86%   |
| ru_RU   | 13        | 3.95%   |
| en_AU   | 9         | 2.74%   |
| es_ES   | 8         | 2.43%   |
| pl_PL   | 5         | 1.52%   |
| ja_JP   | 4         | 1.22%   |
| hu_HU   | 4         | 1.22%   |
| en_IE   | 4         | 1.22%   |
| nl_NL   | 3         | 0.91%   |
| es_MX   | 3         | 0.91%   |
| es_AR   | 3         | 0.91%   |
| en_ZA   | 3         | 0.91%   |
| en_CA   | 3         | 0.91%   |
| cs_CZ   | 3         | 0.91%   |
| fr_CH   | 2         | 0.61%   |
| fr_BE   | 2         | 0.61%   |
| es_CR   | 2         | 0.61%   |
| es_CL   | 2         | 0.61%   |
| en_SG   | 2         | 0.61%   |
| en_IN   | 2         | 0.61%   |
| el_GR   | 2         | 0.61%   |
| sv_SE   | 1         | 0.3%    |
| ru_UA   | 1         | 0.3%    |
| nl_BE   | 1         | 0.3%    |
| lt_LT   | 1         | 0.3%    |
| fi_FI   | 1         | 0.3%    |
| es_UY   | 1         | 0.3%    |
| es_PE   | 1         | 0.3%    |
| es_CO   | 1         | 0.3%    |
| en_PH   | 1         | 0.3%    |
| en_NZ   | 1         | 0.3%    |
| en_DE   | 1         | 0.3%    |
| de_CH   | 1         | 0.3%    |
| de_AT   | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 190       | 57.75%  |
| EFI  | 139       | 42.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 302       | 91.79%  |
| Overlay | 17        | 5.17%   |
| Btrfs   | 6         | 1.82%   |
| Xfs     | 2         | 0.61%   |
| F2fs    | 1         | 0.3%    |
| Ext2    | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 128       | 38.55%  |
| GPT     | 114       | 34.34%  |
| MBR     | 90        | 27.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 295       | 89.39%  |
| Yes       | 35        | 10.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 235       | 71%     |
| Yes       | 96        | 29%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 58        | 17.63%  |
| Lenovo                      | 45        | 13.68%  |
| Dell                        | 40        | 12.16%  |
| ASUSTek Computer            | 39        | 11.85%  |
| Acer                        | 20        | 6.08%   |
| MSI                         | 15        | 4.56%   |
| Toshiba                     | 11        | 3.34%   |
| Gigabyte Technology         | 11        | 3.34%   |
| ASRock                      | 10        | 3.04%   |
| Samsung Electronics         | 9         | 2.74%   |
| Positivo                    | 7         | 2.13%   |
| Intel                       | 7         | 2.13%   |
| Notebook                    | 5         | 1.52%   |
| Apple                       | 5         | 1.52%   |
| Sony                        | 4         | 1.22%   |
| Pegatron                    | 3         | 0.91%   |
| Packard Bell                | 3         | 0.91%   |
| Google                      | 3         | 0.91%   |
| Fujitsu                     | 3         | 0.91%   |
| ZOTAC                       | 2         | 0.61%   |
| Foxconn                     | 2         | 0.61%   |
| AMI                         | 2         | 0.61%   |
| AAEON                       | 2         | 0.61%   |
| Unknown                     | 2         | 0.61%   |
| UNOWHY                      | 1         | 0.3%    |
| Timi                        | 1         | 0.3%    |
| Supermicro                  | 1         | 0.3%    |
| Prestigio                   | 1         | 0.3%    |
| Panasonic                   | 1         | 0.3%    |
| Mediacom                    | 1         | 0.3%    |
| Lanix                       | 1         | 0.3%    |
| LAMINA                      | 1         | 0.3%    |
| Itautec                     | 1         | 0.3%    |
| IBM                         | 1         | 0.3%    |
| I-Life Digital Technologies | 1         | 0.3%    |
| Hungaro Flotta Kft          | 1         | 0.3%    |
| HUAWEI                      | 1         | 0.3%    |
| Huanan                      | 1         | 0.3%    |
| HARDKERNEL                  | 1         | 0.3%    |
| GTZS                        | 1         | 0.3%    |
| Gateway                     | 1         | 0.3%    |
| Fujitsu Siemens             | 1         | 0.3%    |
| Dixonsxp                    | 1         | 0.3%    |
| Digibras                    | 1         | 0.3%    |
| Biostar                     | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| HP Notebook                        | 5         | 1.52%   |
| Unknown                            | 5         | 1.52%   |
| HP Pavilion dv6                    | 3         | 0.91%   |
| Positivo H14BT58                   | 2         | 0.61%   |
| MSI MS-7B89                        | 2         | 0.61%   |
| Lenovo IdeaPad 320-15AST 80XV      | 2         | 0.61%   |
| HP ProBook 440 G7                  | 2         | 0.61%   |
| HP Pavilion x2 Detachable          | 2         | 0.61%   |
| HP Compaq 6000 Pro SFF PC          | 2         | 0.61%   |
| Dell OptiPlex 790                  | 2         | 0.61%   |
| Dell Latitude D630                 | 2         | 0.61%   |
| Dell Inspiron 15-3567              | 2         | 0.61%   |
| ASUS 1015BX                        | 2         | 0.61%   |
| ASRock N68-VS3 UCC                 | 2         | 0.61%   |
| Apple MacBookPro8,1                | 2         | 0.61%   |
| AAEON MF-001                       | 2         | 0.61%   |
| ZOTAC ZBOX-CI323NANO               | 1         | 0.3%    |
| ZOTAC NM10                         | 1         | 0.3%    |
| UNOWHY Y13G010S4EI                 | 1         | 0.3%    |
| Toshiba Satellite Pro U400         | 1         | 0.3%    |
| Toshiba Satellite L840             | 1         | 0.3%    |
| Toshiba Satellite L755D            | 1         | 0.3%    |
| Toshiba Satellite L70-B            | 1         | 0.3%    |
| Toshiba Satellite L305             | 1         | 0.3%    |
| Toshiba Satellite C855D            | 1         | 0.3%    |
| Toshiba Satellite C70D-B           | 1         | 0.3%    |
| Toshiba Satellite C55D-A           | 1         | 0.3%    |
| Toshiba Satellite A660             | 1         | 0.3%    |
| Toshiba Satellite A205             | 1         | 0.3%    |
| Toshiba NB510                      | 1         | 0.3%    |
| Timi TM1612                        | 1         | 0.3%    |
| Supermicro X8DA3                   | 1         | 0.3%    |
| Sony VPCSB1V9E                     | 1         | 0.3%    |
| Sony VPCEJ1E1E                     | 1         | 0.3%    |
| Sony VGN-SZ670AN                   | 1         | 0.3%    |
| Sony VGN-CR11Z_R                   | 1         | 0.3%    |
| Samsung RV415/RV515                | 1         | 0.3%    |
| Samsung RV410/RV510/S3510/E3510    | 1         | 0.3%    |
| Samsung RV408/RV508                | 1         | 0.3%    |
| Samsung RC512                      | 1         | 0.3%    |
| Samsung R530/R730/P530             | 1         | 0.3%    |
| Samsung R520/R522/R620             | 1         | 0.3%    |
| Samsung R40/R41                    | 1         | 0.3%    |
| Samsung 300E4M/300E4S/300E4L       | 1         | 0.3%    |
| Samsung 275E4E/275E5E              | 1         | 0.3%    |
| Prestigio PSB141C01BFH             | 1         | 0.3%    |
| Positivo S14CT01                   | 1         | 0.3%    |
| Positivo S14BW01                   | 1         | 0.3%    |
| Positivo POS-MI945AA               | 1         | 0.3%    |
| Positivo POS-EIH61CE               | 1         | 0.3%    |
| Positivo N600                      | 1         | 0.3%    |
| Pegatron NC689AA-ABA s3700y        | 1         | 0.3%    |
| Pegatron FL308AA-ABD IQ512de       | 1         | 0.3%    |
| Pegatron AY652AA-ABA s5310y        | 1         | 0.3%    |
| Panasonic CF-52PGNBE2M             | 1         | 0.3%    |
| Packard Bell imedia S1350          | 1         | 0.3%    |
| Packard Bell EN Butterfly s        | 1         | 0.3%    |
| Packard Bell EasyNote_ST85-M-010FR | 1         | 0.3%    |
| Notebook W740SU                    | 1         | 0.3%    |
| Notebook W54_W94_W955TU,-T,-C      | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 4.86%   |
| Acer Aspire            | 16        | 4.86%   |
| Lenovo IdeaPad         | 14        | 4.26%   |
| Dell Inspiron          | 13        | 3.95%   |
| HP Pavilion            | 12        | 3.65%   |
| HP Compaq              | 12        | 3.65%   |
| HP ProBook             | 11        | 3.34%   |
| Toshiba Satellite      | 10        | 3.04%   |
| HP Notebook            | 5         | 1.52%   |
| Dell XPS               | 5         | 1.52%   |
| Dell OptiPlex          | 5         | 1.52%   |
| Dell Latitude          | 5         | 1.52%   |
| Unknown                | 5         | 1.52%   |
| Lenovo ThinkCentre     | 4         | 1.22%   |
| Dell Vostro            | 4         | 1.22%   |
| ASUS VivoBook          | 4         | 1.22%   |
| Positivo H14BT58       | 2         | 0.61%   |
| Notebook W54           | 2         | 0.61%   |
| MSI MS-7B89            | 2         | 0.61%   |
| HP t620                | 2         | 0.61%   |
| HP Spectre             | 2         | 0.61%   |
| HP Presario            | 2         | 0.61%   |
| HP EliteBook           | 2         | 0.61%   |
| Dell Studio            | 2         | 0.61%   |
| Dell PowerEdge         | 2         | 0.61%   |
| ASUS 1015BX            | 2         | 0.61%   |
| ASRock N68-VS3         | 2         | 0.61%   |
| Apple MacBookPro8      | 2         | 0.61%   |
| AAEON MF-001           | 2         | 0.61%   |
| ZOTAC ZBOX-CI323NANO   | 1         | 0.3%    |
| ZOTAC NM10             | 1         | 0.3%    |
| UNOWHY Y13G010S4EI     | 1         | 0.3%    |
| Toshiba NB510          | 1         | 0.3%    |
| Timi TM1612            | 1         | 0.3%    |
| Supermicro X8DA3       | 1         | 0.3%    |
| Sony VPCSB1V9E         | 1         | 0.3%    |
| Sony VPCEJ1E1E         | 1         | 0.3%    |
| Sony VGN-SZ670AN       | 1         | 0.3%    |
| Sony VGN-CR11Z         | 1         | 0.3%    |
| Samsung RV415          | 1         | 0.3%    |
| Samsung RV410          | 1         | 0.3%    |
| Samsung RV408          | 1         | 0.3%    |
| Samsung RC512          | 1         | 0.3%    |
| Samsung R530           | 1         | 0.3%    |
| Samsung R520           | 1         | 0.3%    |
| Samsung R40            | 1         | 0.3%    |
| Samsung 300E4M         | 1         | 0.3%    |
| Samsung 275E4E         | 1         | 0.3%    |
| Prestigio PSB141C01BFH | 1         | 0.3%    |
| Positivo S14CT01       | 1         | 0.3%    |
| Positivo S14BW01       | 1         | 0.3%    |
| Positivo POS-MI945AA   | 1         | 0.3%    |
| Positivo POS-EIH61CE   | 1         | 0.3%    |
| Positivo N600          | 1         | 0.3%    |
| Pegatron NC689AA-ABA   | 1         | 0.3%    |
| Pegatron FL308AA-ABD   | 1         | 0.3%    |
| Pegatron AY652AA-ABA   | 1         | 0.3%    |
| Panasonic CF-52PGNBE2M | 1         | 0.3%    |
| Packard Bell imedia    | 1         | 0.3%    |
| Packard Bell EN        | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 28        | 8.51%   |
| 2011 | 28        | 8.51%   |
| 2012 | 27        | 8.21%   |
| 2008 | 25        | 7.6%    |
| 2016 | 23        | 6.99%   |
| 2010 | 23        | 6.99%   |
| 2014 | 22        | 6.69%   |
| 2007 | 22        | 6.69%   |
| 2020 | 20        | 6.08%   |
| 2013 | 20        | 6.08%   |
| 2009 | 20        | 6.08%   |
| 2015 | 19        | 5.78%   |
| 2017 | 17        | 5.17%   |
| 2018 | 13        | 3.95%   |
| 2006 | 10        | 3.04%   |
| 2021 | 7         | 2.13%   |
| 2005 | 4         | 1.22%   |
| 2004 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 201       | 61.09%  |
| Desktop     | 112       | 34.04%  |
| Convertible | 5         | 1.52%   |
| Mini pc     | 5         | 1.52%   |
| Server      | 4         | 1.22%   |
| Tablet      | 1         | 0.3%    |
| All in one  | 1         | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 308       | 93.33%  |
| Enabled  | 22        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 326       | 99.09%  |
| Yes  | 3         | 0.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 104       | 31.42%  |
| 4.01-8.0        | 67        | 20.24%  |
| 1.01-2.0        | 52        | 15.71%  |
| 8.01-16.0       | 46        | 13.9%   |
| 16.01-24.0      | 35        | 10.57%  |
| 32.01-64.0      | 12        | 3.63%   |
| 2.01-3.0        | 7         | 2.11%   |
| 0.51-1.0        | 3         | 0.91%   |
| More than 256.0 | 2         | 0.6%    |
| 24.01-32.0      | 2         | 0.6%    |
| 64.01-256.0     | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 170       | 48.71%  |
| 0.51-1.0   | 58        | 16.62%  |
| 2.01-3.0   | 53        | 15.19%  |
| 4.01-8.0   | 35        | 10.03%  |
| 3.01-4.0   | 20        | 5.73%   |
| 0.01-0.5   | 8         | 2.29%   |
| 8.01-16.0  | 4         | 1.15%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 215       | 64.76%  |
| 2      | 86        | 25.9%   |
| 4      | 10        | 3.01%   |
| 3      | 10        | 3.01%   |
| 5      | 6         | 1.81%   |
| 0      | 2         | 0.6%    |
| 14     | 1         | 0.3%    |
| 7      | 1         | 0.3%    |
| 6      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 51.96%  |
| No        | 159       | 48.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 295       | 89.39%  |
| No        | 35        | 10.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 75.38%  |
| No        | 81        | 24.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 54.95%  |
| Yes       | 150       | 45.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 48        | 14.5%   |
| France       | 37        | 11.18%  |
| Brazil       | 36        | 10.88%  |
| Italy        | 26        | 7.85%   |
| Germany      | 26        | 7.85%   |
| Russia       | 17        | 5.14%   |
| UK           | 10        | 3.02%   |
| Spain        | 10        | 3.02%   |
| Australia    | 9         | 2.72%   |
| Netherlands  | 8         | 2.42%   |
| Poland       | 7         | 2.11%   |
| Hungary      | 7         | 2.11%   |
| Switzerland  | 6         | 1.81%   |
| Mexico       | 5         | 1.51%   |
| Finland      | 5         | 1.51%   |
| Czechia      | 5         | 1.51%   |
| Ukraine      | 4         | 1.21%   |
| Japan        | 4         | 1.21%   |
| Belgium      | 4         | 1.21%   |
| South Africa | 3         | 0.91%   |
| Romania      | 3         | 0.91%   |
| Ireland      | 3         | 0.91%   |
| Greece       | 3         | 0.91%   |
| Canada       | 3         | 0.91%   |
| Argentina    | 3         | 0.91%   |
| Slovenia     | 2         | 0.6%    |
| Singapore    | 2         | 0.6%    |
| Puerto Rico  | 2         | 0.6%    |
| New Zealand  | 2         | 0.6%    |
| Indonesia    | 2         | 0.6%    |
| India        | 2         | 0.6%    |
| Costa Rica   | 2         | 0.6%    |
| Colombia     | 2         | 0.6%    |
| Chile        | 2         | 0.6%    |
| Vietnam      | 1         | 0.3%    |
| Uruguay      | 1         | 0.3%    |
| Turkey       | 1         | 0.3%    |
| Tunisia      | 1         | 0.3%    |
| Sweden       | 1         | 0.3%    |
| Slovakia     | 1         | 0.3%    |
| Serbia       | 1         | 0.3%    |
| Philippines  | 1         | 0.3%    |
| Peru         | 1         | 0.3%    |
| Norway       | 1         | 0.3%    |
| Martinique   | 1         | 0.3%    |
| Malaysia     | 1         | 0.3%    |
| Luxembourg   | 1         | 0.3%    |
| Lithuania    | 1         | 0.3%    |
| Lebanon      | 1         | 0.3%    |
| Israel       | 1         | 0.3%    |
| Iran         | 1         | 0.3%    |
| Ecuador      | 1         | 0.3%    |
| Bulgaria     | 1         | 0.3%    |
| Belarus      | 1         | 0.3%    |
| Austria      | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Rome                   | 7         | 2.03%   |
| Milan                  | 6         | 1.74%   |
| Paris                  | 4         | 1.16%   |
| Helsinki               | 4         | 1.16%   |
| Salvador               | 3         | 0.87%   |
| Munich                 | 3         | 0.87%   |
| Moscow                 | 3         | 0.87%   |
| Eger                   | 3         | 0.87%   |
| Budapest               | 3         | 0.87%   |
| Brasília              | 3         | 0.87%   |
| Windsor                | 2         | 0.58%   |
| Westwood               | 2         | 0.58%   |
| Warsaw                 | 2         | 0.58%   |
| Vicosa                 | 2         | 0.58%   |
| Stuttgart              | 2         | 0.58%   |
| Singapore              | 2         | 0.58%   |
| Ronnenberg             | 2         | 0.58%   |
| Prague                 | 2         | 0.58%   |
| Oradea                 | 2         | 0.58%   |
| Omsk                   | 2         | 0.58%   |
| Lille                  | 2         | 0.58%   |
| Krakow                 | 2         | 0.58%   |
| Houston                | 2         | 0.58%   |
| Heredia                | 2         | 0.58%   |
| Greene                 | 2         | 0.58%   |
| Frankfurt am Main      | 2         | 0.58%   |
| Fortaleza              | 2         | 0.58%   |
| Curitiba               | 2         | 0.58%   |
| Cuernavaca             | 2         | 0.58%   |
| Cayey                  | 2         | 0.58%   |
| Cape Town              | 2         | 0.58%   |
| Berlin                 | 2         | 0.58%   |
| Austin                 | 2         | 0.58%   |
| Augsburg               | 2         | 0.58%   |
| Athens                 | 2         | 0.58%   |
| Annecy                 | 2         | 0.58%   |
| Zwanenburg             | 1         | 0.29%   |
| Zurich                 | 1         | 0.29%   |
| Zhovta Rika            | 1         | 0.29%   |
| Zborowice              | 1         | 0.29%   |
| Zabrze                 | 1         | 0.29%   |
| Yelizovo               | 1         | 0.29%   |
| Yekaterinburg          | 1         | 0.29%   |
| Wollongong             | 1         | 0.29%   |
| Woburn                 | 1         | 0.29%   |
| Wigan                  | 1         | 0.29%   |
| Wiesbaden              | 1         | 0.29%   |
| West Babylon           | 1         | 0.29%   |
| Wellington             | 1         | 0.29%   |
| Wadsworth              | 1         | 0.29%   |
| Wadi Maliz             | 1         | 0.29%   |
| Vladivostok            | 1         | 0.29%   |
| Vlaardingen            | 1         | 0.29%   |
| Vitry-sur-Seine        | 1         | 0.29%   |
| Villaricca             | 1         | 0.29%   |
| Vienna                 | 1         | 0.29%   |
| Verdun                 | 1         | 0.29%   |
| Velilla de San Antonio | 1         | 0.29%   |
| Vaxjo                  | 1         | 0.29%   |
| Varna                  | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 114    | 21.02%  |
| WDC                 | 78        | 114    | 18.01%  |
| Samsung Electronics | 47        | 61     | 10.85%  |
| Toshiba             | 28        | 30     | 6.47%   |
| Unknown             | 26        | 31     | 6%      |
| Hitachi             | 22        | 26     | 5.08%   |
| Kingston            | 21        | 22     | 4.85%   |
| Crucial             | 14        | 15     | 3.23%   |
| SanDisk             | 12        | 16     | 2.77%   |
| Intel               | 9         | 10     | 2.08%   |
| HGST                | 7         | 9      | 1.62%   |
| China               | 7         | 7      | 1.62%   |
| A-DATA Technology   | 7         | 8      | 1.62%   |
| Fujitsu             | 6         | 6      | 1.39%   |
| SK Hynix            | 5         | 5      | 1.15%   |
| PNY                 | 4         | 4      | 0.92%   |
| Apacer              | 4         | 4      | 0.92%   |
| Micron Technology   | 3         | 3      | 0.69%   |
| MAXTOR              | 3         | 3      | 0.69%   |
| KIOXIA              | 3         | 3      | 0.69%   |
| JMicron             | 3         | 3      | 0.69%   |
| USB                 | 2         | 2      | 0.46%   |
| Transcend           | 2         | 2      | 0.46%   |
| Team                | 2         | 2      | 0.46%   |
| OCZ                 | 2         | 2      | 0.46%   |
| LITEONIT            | 2         | 2      | 0.46%   |
| LDLC                | 2         | 2      | 0.46%   |
| TO Exter            | 1         | 1      | 0.23%   |
| TCSUNBOW            | 1         | 1      | 0.23%   |
| PNY USB             | 1         | 1      | 0.23%   |
| Phison Electronics  | 1         | 1      | 0.23%   |
| LONDISK             | 1         | 1      | 0.23%   |
| LITEON              | 1         | 1      | 0.23%   |
| Lexar               | 1         | 1      | 0.23%   |
| Leven               | 1         | 2      | 0.23%   |
| LaCie               | 1         | 2      | 0.23%   |
| KingDian            | 1         | 1      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |
| Integral            | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 6      | 0.23%   |
| GOODRAM             | 1         | 1      | 0.23%   |
| Gigabyte Technology | 1         | 1      | 0.23%   |
| General             | 1         | 1      | 0.23%   |
| External            | 1         | 1      | 0.23%   |
| EMTEC               | 1         | 1      | 0.23%   |
| Corsair             | 1         | 1      | 0.23%   |
| Apple               | 1         | 3      | 0.23%   |
| Unknown             | 1         | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 7         | 1.52%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 1.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 6         | 1.3%    |
| Toshiba MQ01ABF050 500GB             | 4         | 0.87%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.87%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.87%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.87%   |
| A-DATA SU650 240GB SSD               | 4         | 0.87%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.65%   |
| Unknown SD/MMC/MS PRO 128GB          | 3         | 0.65%   |
| Seagate ST9500325AS 500GB            | 3         | 0.65%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 0.65%   |
| Seagate Backup+ Hub BK 8TB           | 3         | 0.65%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.43%   |
| WDC WD7500BPVX-55JC3T3 752GB         | 2         | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.43%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.43%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.43%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 2         | 0.43%   |
| USB 3.0 120GB                        | 2         | 0.43%   |
| Unknown MMC Card  128GB              | 2         | 0.43%   |
| Unknown M52516  16GB                 | 2         | 0.43%   |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.43%   |
| Seagate ST9250410AS 250GB            | 2         | 0.43%   |
| Seagate ST9160412AS 160GB            | 2         | 0.43%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 2         | 0.43%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.43%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.43%   |
| Seagate ST380815AS 80GB              | 2         | 0.43%   |
| Seagate ST3500418AS 500GB            | 2         | 0.43%   |
| Seagate ST3360320AS 360GB            | 2         | 0.43%   |
| Seagate ST3250410AS 250GB            | 2         | 0.43%   |
| Seagate ST3250310AS 250GB            | 2         | 0.43%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.43%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 0.43%   |
| Seagate ST31000528AS 1TB             | 2         | 0.43%   |
| Seagate ST31000524AS 1TB             | 2         | 0.43%   |
| Seagate ST2000LX001-1RG174 2TB       | 2         | 0.43%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.43%   |
| Seagate ST1000DM003-9YN162 1TB       | 2         | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.43%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.43%   |
| Samsung SSD 860 QVO 1TB              | 2         | 0.43%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.43%   |
| Samsung HD161HJ 160GB                | 2         | 0.43%   |
| Samsung HD080HJ/ 80GB                | 2         | 0.43%   |
| PNY CS900 240GB SSD                  | 2         | 0.43%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.43%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.43%   |
| JMicron Tech 250GB                   | 2         | 0.43%   |
| Intel SSDSC2BW120A4 120GB            | 2         | 0.43%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.43%   |
| Hitachi HTS542512K9SA00 120GB        | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 114    | 37.45%  |
| WDC                 | 68        | 99     | 27.98%  |
| Hitachi             | 22        | 26     | 9.05%   |
| Toshiba             | 21        | 23     | 8.64%   |
| Samsung Electronics | 17        | 18     | 7%      |
| HGST                | 7         | 9      | 2.88%   |
| Fujitsu             | 6         | 6      | 2.47%   |
| Unknown             | 3         | 3      | 1.23%   |
| MAXTOR              | 3         | 3      | 1.23%   |
| USB                 | 2         | 2      | 0.82%   |
| TO Exter            | 1         | 1      | 0.41%   |
| LaCie               | 1         | 1      | 0.41%   |
| External            | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 27     | 17.69%  |
| Kingston            | 18        | 18     | 13.85%  |
| Crucial             | 14        | 15     | 10.77%  |
| WDC                 | 10        | 13     | 7.69%   |
| SanDisk             | 8         | 12     | 6.15%   |
| Intel               | 7         | 8      | 5.38%   |
| China               | 7         | 7      | 5.38%   |
| A-DATA Technology   | 5         | 6      | 3.85%   |
| Toshiba             | 4         | 4      | 3.08%   |
| PNY                 | 4         | 4      | 3.08%   |
| Apacer              | 4         | 4      | 3.08%   |
| Transcend           | 2         | 2      | 1.54%   |
| Team                | 2         | 2      | 1.54%   |
| OCZ                 | 2         | 2      | 1.54%   |
| LITEONIT            | 2         | 2      | 1.54%   |
| LDLC                | 2         | 2      | 1.54%   |
| Unknown             | 1         | 1      | 0.77%   |
| TCSUNBOW            | 1         | 1      | 0.77%   |
| SK Hynix            | 1         | 1      | 0.77%   |
| PNY USB             | 1         | 1      | 0.77%   |
| Micron Technology   | 1         | 1      | 0.77%   |
| LONDISK             | 1         | 1      | 0.77%   |
| LITEON              | 1         | 1      | 0.77%   |
| Lexar               | 1         | 1      | 0.77%   |
| Leven               | 1         | 2      | 0.77%   |
| KingDian            | 1         | 1      | 0.77%   |
| Intenso             | 1         | 1      | 0.77%   |
| Integral            | 1         | 1      | 0.77%   |
| Hewlett-Packard     | 1         | 6      | 0.77%   |
| GOODRAM             | 1         | 1      | 0.77%   |
| Corsair             | 1         | 1      | 0.77%   |
| Apple               | 1         | 3      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 209       | 306    | 52.78%  |
| SSD     | 126       | 152    | 31.82%  |
| NVMe    | 31        | 42     | 7.83%   |
| MMC     | 25        | 32     | 6.31%   |
| Unknown | 5         | 5      | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 285       | 437    | 79.39%  |
| NVMe | 30        | 41     | 8.36%   |
| MMC  | 25        | 32     | 6.96%   |
| SAS  | 19        | 27     | 5.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 227       | 307    | 68.37%  |
| 0.51-1.0   | 80        | 110    | 24.1%   |
| 1.01-2.0   | 13        | 19     | 3.92%   |
| 3.01-4.0   | 5         | 13     | 1.51%   |
| 2.01-3.0   | 4         | 5      | 1.2%    |
| 4.01-10.0  | 3         | 4      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 91        | 27.33%  |
| 251-500        | 82        | 24.62%  |
| 501-1000       | 42        | 12.61%  |
| 51-100         | 27        | 8.11%   |
| 1001-2000      | 24        | 7.21%   |
| 1-20           | 22        | 6.61%   |
| 21-50          | 19        | 5.71%   |
| More than 3000 | 17        | 5.11%   |
| 2001-3000      | 8         | 2.4%    |
| Unknown        | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 146       | 42.94%  |
| 21-50          | 55        | 16.18%  |
| 101-250        | 44        | 12.94%  |
| 51-100         | 29        | 8.53%   |
| 251-500        | 24        | 7.06%   |
| 501-1000       | 20        | 5.88%   |
| 1001-2000      | 9         | 2.65%   |
| More than 3000 | 8         | 2.35%   |
| 2001-3000      | 4         | 1.18%   |
| Unknown        | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2      | 4.35%   |
| Seagate ST1000DM003-9YN162 1TB             | 2         | 2      | 4.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 2.17%   |
| WDC WD800BEVS-60RST0 80GB                  | 1         | 1      | 2.17%   |
| WDC WD5000AAKX-003CA0 500GB                | 1         | 1      | 2.17%   |
| WDC WD400EB-00CPF0 40GB                    | 1         | 1      | 2.17%   |
| WDC WD3200BPVT-80ZEST0 320GB               | 1         | 1      | 2.17%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 2      | 2.17%   |
| WDC WD1600AAJS-60B4A0 160GB                | 1         | 2      | 2.17%   |
| TCSUNBOW X1 32GB SSD                       | 1         | 1      | 2.17%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 2.17%   |
| Seagate ST9320325AS 320GB                  | 1         | 1      | 2.17%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 2.17%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 2.17%   |
| Seagate ST500DM002-1BD142 500GB            | 1         | 1      | 2.17%   |
| Seagate ST380815AS 80GB                    | 1         | 1      | 2.17%   |
| Seagate ST3360320AS 360GB                  | 1         | 1      | 2.17%   |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 2.17%   |
| Seagate ST3160318AS 160GB                  | 1         | 1      | 2.17%   |
| Seagate ST2000DX002-2DV164 2TB             | 1         | 1      | 2.17%   |
| Seagate ST1000NM0095-2DC10C 1TB            | 1         | 6      | 2.17%   |
| Seagate ST1000DX001-1CM162 1TB             | 1         | 1      | 2.17%   |
| Seagate ST1000DM003-1ER162 1TB             | 1         | 1      | 2.17%   |
| Samsung Electronics HM160JI 160GB          | 1         | 1      | 2.17%   |
| Samsung Electronics HM121HI 120GB          | 1         | 1      | 2.17%   |
| MAXTOR STM3300622A 304GB                   | 1         | 1      | 2.17%   |
| MAXTOR 6Y080L0 82GB                        | 1         | 1      | 2.17%   |
| MAXTOR 6B200M0 208GB                       | 1         | 1      | 2.17%   |
| LDLC SSD 120GB                             | 1         | 1      | 2.17%   |
| Kingston SHFS37A120G 120GB SSD             | 1         | 1      | 2.17%   |
| Kingston SA400S37120G 120GB SSD            | 1         | 1      | 2.17%   |
| Hitachi HTS722012K9SA00 120GB              | 1         | 1      | 2.17%   |
| Hitachi HTS542512K9SA00 120GB              | 1         | 1      | 2.17%   |
| Hitachi HTS541616J9SA00 160GB              | 1         | 1      | 2.17%   |
| Hitachi HCP725050GLAT80 500GB              | 1         | 1      | 2.17%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1      | 2.17%   |
| HGST HTS541075A9E680 752GB                 | 1         | 1      | 2.17%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 2.17%   |
| Fujitsu MHZ2160BH G2 160GB                 | 1         | 1      | 2.17%   |
| Crucial CT960M500SSD1 960GB                | 1         | 1      | 2.17%   |
| Crucial CT120M500SSD3 120GB                | 1         | 1      | 2.17%   |
| Crucial CT120M500SSD1 120GB                | 1         | 1      | 2.17%   |
| Apacer 16GB SATA Flash Drive SSD           | 1         | 1      | 2.17%   |
| A-DATA Technology IM2S3334-256GD 256GB SSD | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 34.78%  |
| WDC                 | 7         | 9      | 15.22%  |
| Hitachi             | 4         | 4      | 8.7%    |
| MAXTOR              | 3         | 3      | 6.52%   |
| HGST                | 3         | 3      | 6.52%   |
| Crucial             | 3         | 3      | 6.52%   |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Kingston            | 2         | 2      | 4.35%   |
| TCSUNBOW            | 1         | 1      | 2.17%   |
| SK Hynix            | 1         | 1      | 2.17%   |
| LDLC                | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |
| Apacer              | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 45.71%  |
| WDC                 | 6         | 8      | 17.14%  |
| Hitachi             | 4         | 4      | 11.43%  |
| MAXTOR              | 3         | 3      | 8.57%   |
| HGST                | 3         | 3      | 8.57%   |
| Samsung Electronics | 2         | 2      | 5.71%   |
| Fujitsu             | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 42     | 75.56%  |
| SSD  | 11        | 11     | 24.44%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 50%     |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 160       | 237    | 44.69%  |
| Detected | 152       | 244    | 42.46%  |
| Malfunc  | 44        | 53     | 12.29%  |
| Failed   | 2         | 3      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 229       | 65.43%  |
| AMD                              | 58        | 16.57%  |
| Nvidia                           | 16        | 4.57%   |
| Samsung Electronics              | 7         | 2%      |
| JMicron Technology               | 5         | 1.43%   |
| Sandisk                          | 4         | 1.14%   |
| Marvell Technology Group         | 4         | 1.14%   |
| Toshiba America Info Systems     | 3         | 0.86%   |
| LSI Logic / Symbios Logic        | 3         | 0.86%   |
| KIOXIA                           | 3         | 0.86%   |
| Kingston Technology Company      | 3         | 0.86%   |
| VIA Technologies                 | 2         | 0.57%   |
| SK Hynix                         | 2         | 0.57%   |
| Micron Technology                | 2         | 0.57%   |
| ASMedia Technology               | 2         | 0.57%   |
| ADATA Technology                 | 2         | 0.57%   |
| Solid State Storage Technology   | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Phison Electronics               | 1         | 0.29%   |
| Hewlett-Packard                  | 1         | 0.29%   |
| Broadcom / LSI                   | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 37        | 8.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 18        | 4.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 17        | 3.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 3.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 3.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12        | 2.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9         | 2.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 2.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 1.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 1.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.61%   |
| Nvidia MCP61 SATA Controller                                                            | 6         | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.38%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6         | 1.38%   |
| Nvidia MCP61 IDE                                                                        | 5         | 1.15%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.15%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 5         | 1.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 0.92%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.92%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 0.92%   |
| AMD IXP SB4x0 IDE Controller                                                            | 4         | 0.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 0.92%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.69%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 3         | 0.69%   |
| Nvidia CK804 Serial ATA Controller                                                      | 3         | 0.69%   |
| Nvidia CK804 IDE                                                                        | 3         | 0.69%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.69%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.69%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 3         | 0.69%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 0.46%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 0.46%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.46%   |
| Nvidia MCP51 IDE                                                                        | 2         | 0.46%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.46%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2         | 0.46%   |
| Intel SSD 660P Series                                                                   | 2         | 0.46%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 0.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.46%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2         | 0.46%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.46%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 235       | 63.17%  |
| IDE  | 87        | 23.39%  |
| NVMe | 29        | 7.8%    |
| RAID | 19        | 5.11%   |
| SCSI | 2         | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 254       | 77.2%   |
| AMD    | 75        | 22.8%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz            | 6         | 1.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 5         | 1.52%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 5         | 1.52%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz  | 4         | 1.22%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 4         | 1.22%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 4         | 1.22%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 3         | 0.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 3         | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 0.91%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 3         | 0.91%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 3         | 0.91%   |
| AMD Ryzen 7 4700U with Radeon Graphics       | 3         | 0.91%   |
| AMD Ryzen 5 3600 6-Core Processor            | 3         | 0.91%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 0.91%   |
| Intel Xeon CPU E5620 @ 2.40GHz               | 2         | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 2         | 0.61%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 2         | 0.61%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz  | 2         | 0.61%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 2         | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i7-2640M CPU @ 2.80GHz            | 2         | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 0.61%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 2         | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 2         | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 0.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 2         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 2         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 0.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 2         | 0.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i5 CPU 650 @ 3.20GHz              | 2         | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.61%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 2         | 0.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 2         | 0.61%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz         | 2         | 0.61%   |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 2         | 0.61%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz  | 2         | 0.61%   |
| Intel Celeron CPU N2807 @ 1.58GHz            | 2         | 0.61%   |
| Intel Celeron CPU J3455 @ 1.50GHz            | 2         | 0.61%   |
| Intel Celeron CPU J1900 @ 1.99GHz            | 2         | 0.61%   |
| Intel Atom CPU Z3735F @ 1.33GHz              | 2         | 0.61%   |
| Intel Atom CPU N450 @ 1.66GHz                | 2         | 0.61%   |
| Intel Atom CPU N2600 @ 1.60GHz               | 2         | 0.61%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics   | 2         | 0.61%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2         | 0.61%   |
| AMD E-450 APU with Radeon HD Graphics        | 2         | 0.61%   |
| AMD Athlon II X2 250 Processor               | 2         | 0.61%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+   | 2         | 0.61%   |
| AMD Athlon 64 Processor 3000+                | 2         | 0.61%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 0.61%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 2         | 0.61%   |
| AMD A10-6800K APU with Radeon HD Graphics    | 2         | 0.61%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz          | 1         | 0.3%    |
| Intel Xeon CPU E5-2650L v2 @ 1.70GHz         | 1         | 0.3%    |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz           | 1         | 0.3%    |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz          | 1         | 0.3%    |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz          | 1         | 0.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 56        | 17.02%  |
| Intel Core i3                  | 31        | 9.42%   |
| Intel Core i7                  | 30        | 9.12%   |
| Intel Core 2 Duo               | 30        | 9.12%   |
| Intel Celeron                  | 27        | 8.21%   |
| Intel Atom                     | 22        | 6.69%   |
| Intel Pentium Dual-Core        | 10        | 3.04%   |
| Intel Xeon                     | 8         | 2.43%   |
| Intel Pentium                  | 8         | 2.43%   |
| Intel Core 2                   | 8         | 2.43%   |
| AMD Ryzen 5                    | 8         | 2.43%   |
| Other                          | 7         | 2.13%   |
| AMD Ryzen 7                    | 7         | 2.13%   |
| Intel Pentium Dual             | 6         | 1.82%   |
| AMD E                          | 6         | 1.82%   |
| AMD Athlon 64 X2               | 6         | 1.82%   |
| Intel Core 2 Quad              | 4         | 1.22%   |
| AMD E1                         | 4         | 1.22%   |
| AMD Athlon II X2               | 4         | 1.22%   |
| AMD Athlon 64                  | 3         | 0.91%   |
| AMD A6                         | 3         | 0.91%   |
| AMD A10                        | 3         | 0.91%   |
| Intel Pentium Silver           | 2         | 0.61%   |
| Intel Pentium 4                | 2         | 0.61%   |
| Intel Celeron Dual-Core        | 2         | 0.61%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.61%   |
| AMD Sempron                    | 2         | 0.61%   |
| AMD Ryzen 7 PRO                | 2         | 0.61%   |
| AMD GX                         | 2         | 0.61%   |
| AMD Athlon X2                  | 2         | 0.61%   |
| AMD A4                         | 2         | 0.61%   |
| Intel Pentium Gold             | 1         | 0.3%    |
| Intel Genuine                  | 1         | 0.3%    |
| Intel Core m3                  | 1         | 0.3%    |
| Intel Core 2 Solo              | 1         | 0.3%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.3%    |
| AMD Ryzen Threadripper         | 1         | 0.3%    |
| AMD Ryzen 3                    | 1         | 0.3%    |
| AMD Quad-Core Opteron          | 1         | 0.3%    |
| AMD Phenom II X3               | 1         | 0.3%    |
| AMD Opteron                    | 1         | 0.3%    |
| AMD Mobile Sempron             | 1         | 0.3%    |
| AMD G                          | 1         | 0.3%    |
| AMD FX                         | 1         | 0.3%    |
| AMD Embedded                   | 1         | 0.3%    |
| AMD C-60                       | 1         | 0.3%    |
| AMD C-50                       | 1         | 0.3%    |
| AMD C-30                       | 1         | 0.3%    |
| AMD Athlon X4                  | 1         | 0.3%    |
| AMD Athlon II X4               | 1         | 0.3%    |
| AMD A8                         | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 202       | 61.4%   |
| 4      | 83        | 25.23%  |
| 1      | 16        | 4.86%   |
| 8      | 12        | 3.65%   |
| 6      | 11        | 3.34%   |
| 12     | 2         | 0.61%   |
| 64     | 1         | 0.3%    |
| 20     | 1         | 0.3%    |
| 3      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 324       | 98.48%  |
| 2      | 5         | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 56.23%  |
| 2      | 144       | 43.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 329       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 9.34%   |
| 0x206a7    | 30        | 9.04%   |
| 0x1067a    | 19        | 5.72%   |
| 0x6fd      | 16        | 4.82%   |
| 0x306c3    | 14        | 4.22%   |
| 0x406e3    | 12        | 3.61%   |
| 0x306a9    | 11        | 3.31%   |
| 0x806ec    | 10        | 3.01%   |
| 0x40651    | 9         | 2.71%   |
| 0x30678    | 9         | 2.71%   |
| 0x10676    | 9         | 2.71%   |
| 0x406c3    | 8         | 2.41%   |
| 0x05000119 | 8         | 2.41%   |
| 0x406c4    | 7         | 2.11%   |
| 0x20655    | 7         | 2.11%   |
| 0x6f6      | 6         | 1.81%   |
| 0x306d4    | 6         | 1.81%   |
| 0x06006705 | 6         | 1.81%   |
| 0x706a1    | 5         | 1.51%   |
| 0x6fb      | 5         | 1.51%   |
| 0x20652    | 5         | 1.51%   |
| 0x106ca    | 5         | 1.51%   |
| 0x906e9    | 4         | 1.2%    |
| 0x906ea    | 3         | 0.9%    |
| 0x806eb    | 3         | 0.9%    |
| 0x806e9    | 3         | 0.9%    |
| 0x30661    | 3         | 0.9%    |
| 0x08701021 | 3         | 0.9%    |
| 0x08600106 | 3         | 0.9%    |
| 0x07030105 | 3         | 0.9%    |
| 0x0700010f | 3         | 0.9%    |
| 0x06001119 | 3         | 0.9%    |
| 0x05000029 | 3         | 0.9%    |
| 0x010000c8 | 3         | 0.9%    |
| 0x806c1    | 2         | 0.6%    |
| 0x706e5    | 2         | 0.6%    |
| 0x6fa      | 2         | 0.6%    |
| 0x506e3    | 2         | 0.6%    |
| 0x506c9    | 2         | 0.6%    |
| 0x306e4    | 2         | 0.6%    |
| 0x10661    | 2         | 0.6%    |
| 0x08701013 | 2         | 0.6%    |
| 0x08600103 | 2         | 0.6%    |
| 0x08108102 | 2         | 0.6%    |
| 0x0800820d | 2         | 0.6%    |
| 0x07030106 | 2         | 0.6%    |
| 0x02000057 | 2         | 0.6%    |
| 0xf65      | 1         | 0.3%    |
| 0xf4a      | 1         | 0.3%    |
| 0xa0655    | 1         | 0.3%    |
| 0xa0653    | 1         | 0.3%    |
| 0x906ed    | 1         | 0.3%    |
| 0x806ea    | 1         | 0.3%    |
| 0x806d1    | 1         | 0.3%    |
| 0x706a8    | 1         | 0.3%    |
| 0x6f7      | 1         | 0.3%    |
| 0x6f2      | 1         | 0.3%    |
| 0x506ca    | 1         | 0.3%    |
| 0x406f1    | 1         | 0.3%    |
| 0x40661    | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Core            | 34        | 10.33%  |
| SandyBridge     | 32        | 9.73%   |
| Penryn          | 30        | 9.12%   |
| Silvermont      | 26        | 7.9%    |
| Haswell         | 26        | 7.9%    |
| KabyLake        | 25        | 7.6%    |
| Skylake         | 17        | 5.17%   |
| Westmere        | 15        | 4.56%   |
| K8 Hammer       | 14        | 4.26%   |
| IvyBridge       | 13        | 3.95%   |
| Zen 2           | 12        | 3.65%   |
| Bobcat          | 11        | 3.34%   |
| K10             | 8         | 2.43%   |
| Bonnell         | 8         | 2.43%   |
| Broadwell       | 7         | 2.13%   |
| Puma            | 6         | 1.82%   |
| Goldmont plus   | 6         | 1.82%   |
| Excavator       | 6         | 1.82%   |
| Zen+            | 5         | 1.52%   |
| Piledriver      | 4         | 1.22%   |
| TigerLake       | 3         | 0.91%   |
| K8 & K10 hybrid | 3         | 0.91%   |
| Jaguar          | 3         | 0.91%   |
| IceLake         | 3         | 0.91%   |
| Goldmont        | 3         | 0.91%   |
| CometLake       | 3         | 0.91%   |
| NetBurst        | 2         | 0.61%   |
| Zen 3           | 1         | 0.3%    |
| Zen             | 1         | 0.3%    |
| Steamroller     | 1         | 0.3%    |
| Nehalem         | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 200       | 55.1%   |
| AMD                              | 89        | 24.52%  |
| Nvidia                           | 70        | 19.28%  |
| Matrox Electronics Systems       | 3         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 6.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 3.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 3.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 3.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 3.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 2.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.55%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.55%   |
| AMD Renoir                                                                               | 6         | 1.55%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1.29%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.03%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 4         | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.03%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.03%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 1.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.78%   |
| Intel HD Graphics 500                                                                    | 3         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.78%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.78%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.78%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.78%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.78%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.52%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.52%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.52%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.52%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.52%   |
| Intel HD Graphics 620                                                                    | 2         | 0.52%   |
| Intel HD Graphics 530                                                                    | 2         | 0.52%   |
| Intel HD Graphics 520                                                                    | 2         | 0.52%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.52%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.52%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 2         | 0.52%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.52%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.52%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2         | 0.52%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2         | 0.52%   |
| AMD Richland [Radeon HD 8670D]                                                           | 2         | 0.52%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.52%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2         | 0.52%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 170       | 51.52%  |
| 1 x AMD        | 72        | 21.82%  |
| 1 x Nvidia     | 47        | 14.24%  |
| Intel + Nvidia | 19        | 5.76%   |
| Intel + AMD    | 10        | 3.03%   |
| 2 x AMD        | 5         | 1.52%   |
| 1 x Matrox     | 3         | 0.91%   |
| AMD + Nvidia   | 2         | 0.61%   |
| 2 x Nvidia     | 1         | 0.3%    |
| 1 x SiS        | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 291       | 88.18%  |
| Proprietary | 36        | 10.91%  |
| Unknown     | 3         | 0.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 188       | 56.8%   |
| 0.01-0.5   | 73        | 22.05%  |
| 0.51-1.0   | 29        | 8.76%   |
| 1.01-2.0   | 24        | 7.25%   |
| 3.01-4.0   | 9         | 2.72%   |
| 7.01-8.0   | 3         | 0.91%   |
| 2.01-3.0   | 3         | 0.91%   |
| 8.01-16.0  | 2         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 12.39%  |
| Samsung Electronics     | 41        | 12.09%  |
| LG Display              | 31        | 9.14%   |
| BOE                     | 28        | 8.26%   |
| Chimei Innolux          | 26        | 7.67%   |
| Dell                    | 21        | 6.19%   |
| Goldstar                | 17        | 5.01%   |
| Acer                    | 15        | 4.42%   |
| Hewlett-Packard         | 13        | 3.83%   |
| Lenovo                  | 11        | 3.24%   |
| Chi Mei Optoelectronics | 7         | 2.06%   |
| Philips                 | 6         | 1.77%   |
| Apple                   | 6         | 1.77%   |
| Vizio                   | 5         | 1.47%   |
| LG Philips              | 5         | 1.47%   |
| Sharp                   | 4         | 1.18%   |
| InfoVision              | 4         | 1.18%   |
| BenQ                    | 4         | 1.18%   |
| AOC                     | 4         | 1.18%   |
| Ancor Communications    | 4         | 1.18%   |
| Unknown                 | 3         | 0.88%   |
| Sony                    | 3         | 0.88%   |
| NEC Computers           | 3         | 0.88%   |
| Iiyama                  | 3         | 0.88%   |
| HannStar                | 3         | 0.88%   |
| PANDA                   | 2         | 0.59%   |
| LG Electronics          | 2         | 0.59%   |
| Lenovo Group Limited    | 2         | 0.59%   |
| InnoLux Display         | 2         | 0.59%   |
| Eizo                    | 2         | 0.59%   |
| CVT                     | 2         | 0.59%   |
| ___                     | 1         | 0.29%   |
| Videoseven              | 1         | 0.29%   |
| Unknown (ADA)           | 1         | 0.29%   |
| Sceptre Tech            | 1         | 0.29%   |
| Plain Tree Systems      | 1         | 0.29%   |
| MOT                     | 1         | 0.29%   |
| Lite-On                 | 1         | 0.29%   |
| KDC                     | 1         | 0.29%   |
| IOD                     | 1         | 0.29%   |
| IBM                     | 1         | 0.29%   |
| Hitachi                 | 1         | 0.29%   |
| GDH                     | 1         | 0.29%   |
| Fujitsu Siemens         | 1         | 0.29%   |
| Element                 | 1         | 0.29%   |
| DENON                   | 1         | 0.29%   |
| CPT                     | 1         | 0.29%   |
| Compaq Computer         | 1         | 0.29%   |
| Arnos Instruments       | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.87%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 3         | 0.87%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.87%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2         | 0.58%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch  | 2         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 2         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 2         | 0.58%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 2         | 0.58%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2         | 0.58%   |
| Lenovo LCD Monitor LEN4031 1280x800 286x179mm 13.3-inch               | 2         | 0.58%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 2         | 0.58%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 2         | 0.58%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch             | 2         | 0.58%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2         | 0.58%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                     | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 2         | 0.58%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.58%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.58%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                  | 2         | 0.58%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                  | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.58%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.58%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2         | 0.58%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.29%   |
| ___ LCDTV16 ___0101 1360x768                                          | 1         | 0.29%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1         | 0.29%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 1         | 0.29%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                    | 1         | 0.29%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1         | 0.29%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                    | 1         | 0.29%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.29%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1         | 0.29%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.29%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1         | 0.29%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.29%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1         | 0.29%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1         | 0.29%   |
| Sony TV SNYAA01 1920x1080 880x490mm 39.7-inch                         | 1         | 0.29%   |
| Sony TV SNYA401 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.29%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1         | 0.29%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP146A 1920x1080 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp HDMI SHP0FFD 1920x1080 820x460mm 37.0-inch                      | 1         | 0.29%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 0.29%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x290mm 23.1-inch  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 94        | 28.23%  |
| 1920x1080 (FHD)    | 91        | 27.33%  |
| 1280x1024 (SXGA)   | 26        | 7.81%   |
| 1280x800 (WXGA)    | 25        | 7.51%   |
| 1600x900 (HD+)     | 19        | 5.71%   |
| 1680x1050 (WSXGA+) | 16        | 4.8%    |
| 1440x900 (WXGA+)   | 12        | 3.6%    |
| 1920x1200 (WUXGA)  | 10        | 3%      |
| 3840x2160 (4K)     | 8         | 2.4%    |
| 2560x1440 (QHD)    | 8         | 2.4%    |
| 1024x768 (XGA)     | 6         | 1.8%    |
| 2560x1600          | 3         | 0.9%    |
| 1024x600           | 3         | 0.9%    |
| 2560x1080          | 2         | 0.6%    |
| 3840x2400          | 1         | 0.3%    |
| 3600x1200          | 1         | 0.3%    |
| 3440x1440          | 1         | 0.3%    |
| 2288x1287          | 1         | 0.3%    |
| 2048x1152          | 1         | 0.3%    |
| 1920x540           | 1         | 0.3%    |
| 1600x1200          | 1         | 0.3%    |
| 1360x768           | 1         | 0.3%    |
| 1280x720 (HD)      | 1         | 0.3%    |
| Unknown            | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 92        | 27.06%  |
| 13      | 39        | 11.47%  |
| 14      | 33        | 9.71%   |
| 17      | 31        | 9.12%   |
| 27      | 16        | 4.71%   |
| 19      | 16        | 4.71%   |
| 24      | 15        | 4.41%   |
| 23      | 15        | 4.41%   |
| 21      | 12        | 3.53%   |
| Unknown | 11        | 3.24%   |
| 22      | 10        | 2.94%   |
| 20      | 8         | 2.35%   |
| 11      | 8         | 2.35%   |
| 18      | 5         | 1.47%   |
| 10      | 5         | 1.47%   |
| 12      | 4         | 1.18%   |
| 72      | 3         | 0.88%   |
| 41      | 2         | 0.59%   |
| 39      | 2         | 0.59%   |
| 37      | 2         | 0.59%   |
| 34      | 2         | 0.59%   |
| 31      | 2         | 0.59%   |
| 84      | 1         | 0.29%   |
| 38      | 1         | 0.29%   |
| 33      | 1         | 0.29%   |
| 32      | 1         | 0.29%   |
| 29      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 7       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 155       | 46.13%  |
| 501-600     | 46        | 13.69%  |
| 401-500     | 39        | 11.61%  |
| 201-300     | 34        | 10.12%  |
| 351-400     | 32        | 9.52%   |
| Unknown     | 11        | 3.27%   |
| 801-900     | 5         | 1.49%   |
| 701-800     | 4         | 1.19%   |
| 1501-2000   | 4         | 1.19%   |
| 601-700     | 3         | 0.89%   |
| 901-1000    | 2         | 0.6%    |
| 101-200     | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 213       | 67.83%  |
| 16/10   | 56        | 17.83%  |
| 5/4     | 23        | 7.32%   |
| Unknown | 9         | 2.87%   |
| 4/3     | 7         | 2.23%   |
| 21/9    | 3         | 0.96%   |
| 6/5     | 2         | 0.64%   |
| 3/2     | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 91        | 26.92%  |
| 81-90          | 59        | 17.46%  |
| 201-250        | 42        | 12.43%  |
| 151-200        | 27        | 7.99%   |
| 301-350        | 17        | 5.03%   |
| 141-150        | 17        | 5.03%   |
| 71-80          | 14        | 4.14%   |
| 121-130        | 13        | 3.85%   |
| Unknown        | 11        | 3.25%   |
| 51-60          | 8         | 2.37%   |
| 251-300        | 8         | 2.37%   |
| 501-1000       | 7         | 2.07%   |
| 351-500        | 6         | 1.78%   |
| 41-50          | 5         | 1.48%   |
| More than 1000 | 4         | 1.18%   |
| 131-140        | 4         | 1.18%   |
| 61-70          | 3         | 0.89%   |
| 1-40           | 1         | 0.3%    |
| 111-120        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 119       | 36.39%  |
| 101-120       | 118       | 36.09%  |
| 121-160       | 62        | 18.96%  |
| Unknown       | 11        | 3.36%   |
| 161-240       | 10        | 3.06%   |
| 1-50          | 4         | 1.22%   |
| More than 240 | 3         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 282       | 84.68%  |
| 2     | 41        | 12.31%  |
| 0     | 6         | 1.8%    |
| 3     | 3         | 0.9%    |
| 4     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 175       | 35.07%  |
| Intel                             | 130       | 26.05%  |
| Qualcomm Atheros                  | 72        | 14.43%  |
| Broadcom                          | 38        | 7.62%   |
| Marvell Technology Group          | 15        | 3.01%   |
| Nvidia                            | 14        | 2.81%   |
| Ralink Technology                 | 12        | 2.4%    |
| Broadcom Limited                  | 11        | 2.2%    |
| Ralink                            | 6         | 1.2%    |
| TP-Link                           | 5         | 1%      |
| Samsung Electronics               | 3         | 0.6%    |
| NetGear                           | 2         | 0.4%    |
| Attansic Technology               | 2         | 0.4%    |
| ASIX Electronics                  | 2         | 0.4%    |
| ZyXEL Communications              | 1         | 0.2%    |
| Xiaomi                            | 1         | 0.2%    |
| VIA Technologies                  | 1         | 0.2%    |
| U-Blox                            | 1         | 0.2%    |
| Tenda                             | 1         | 0.2%    |
| Sitecom Europe                    | 1         | 0.2%    |
| Seeed                             | 1         | 0.2%    |
| Huawei Technologies               | 1         | 0.2%    |
| Ericsson Business Mobile Networks | 1         | 0.2%    |
| Belkin Components                 | 1         | 0.2%    |
| Aquantia                          | 1         | 0.2%    |
| ADMtek                            | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 100       | 17.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 38        | 6.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.26%   |
| Intel Wireless 7260                                                     | 11        | 1.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.22%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.04%   |
| Nvidia MCP61 Ethernet                                                   | 6         | 1.04%   |
| Intel Wireless 3160                                                     | 6         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.87%   |
| Intel Wireless 8260                                                     | 5         | 0.87%   |
| Intel Wireless 7265                                                     | 5         | 0.87%   |
| Intel Wireless 3165                                                     | 5         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                    | 5         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 4         | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.52%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.52%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.52%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.52%   |
| Intel 82574L Gigabit Network Connection                                 | 3         | 0.52%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 3         | 0.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 3         | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.35%   |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.35%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 2         | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.35%   |
| Ralink RT5572 Wireless Adapter                                          | 2         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 97        | 37.45%  |
| Qualcomm Atheros      | 62        | 23.94%  |
| Realtek Semiconductor | 45        | 17.37%  |
| Broadcom              | 22        | 8.49%   |
| Ralink Technology     | 12        | 4.63%   |
| Ralink                | 6         | 2.32%   |
| TP-Link               | 5         | 1.93%   |
| Broadcom Limited      | 4         | 1.54%   |
| NetGear               | 2         | 0.77%   |
| ZyXEL Communications  | 1         | 0.39%   |
| Tenda                 | 1         | 0.39%   |
| Sitecom Europe        | 1         | 0.39%   |
| Belkin Components     | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 5.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 5%      |
| Intel Wireless 7260                                                     | 11        | 4.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 3.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.08%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 2.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 2.31%   |
| Intel Wireless 3160                                                     | 6         | 2.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.92%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.92%   |
| Intel Wireless 8260                                                     | 5         | 1.92%   |
| Intel Wireless 7265                                                     | 5         | 1.92%   |
| Intel Wireless 3165                                                     | 5         | 1.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.15%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.15%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.77%   |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.77%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.77%   |
| Ralink RT5572 Wireless Adapter                                          | 2         | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.77%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.77%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.77%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.77%   |
| Intel WiFi Link 5100                                                    | 2         | 0.77%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.77%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.77%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.77%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.77%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 2         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.77%   |
| ZyXEL ZyAIR G-202 802.11bg                                              | 1         | 0.38%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 1         | 0.38%   |
| Tenda U12                                                               | 1         | 0.38%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                         | 1         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 157       | 51.64%  |
| Intel                    | 57        | 18.75%  |
| Broadcom                 | 23        | 7.57%   |
| Qualcomm Atheros         | 19        | 6.25%   |
| Marvell Technology Group | 15        | 4.93%   |
| Nvidia                   | 14        | 4.61%   |
| Broadcom Limited         | 7         | 2.3%    |
| Samsung Electronics      | 3         | 0.99%   |
| Attansic Technology      | 2         | 0.66%   |
| ASIX Electronics         | 2         | 0.66%   |
| Xiaomi                   | 1         | 0.33%   |
| VIA Technologies         | 1         | 0.33%   |
| Huawei Technologies      | 1         | 0.33%   |
| Aquantia                 | 1         | 0.33%   |
| ADMtek                   | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 100       | 32.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 38        | 12.18%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 2.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.24%   |
| Nvidia MCP61 Ethernet                                                          | 6         | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.6%    |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.6%    |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.28%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 1.28%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.96%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.96%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.96%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 0.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 3         | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.64%   |
| Nvidia MCP51 Ethernet Controller                                               | 2         | 0.64%   |
| Nvidia CK804 Ethernet Controller                                               | 2         | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.64%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 0.64%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 2         | 0.64%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.64%   |
| Intel 82562V-2 10/100 Network Connection                                       | 2         | 0.64%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 2         | 0.64%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.64%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.64%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.32%   |
| Nvidia MCP73 Ethernet                                                          | 1         | 0.32%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.32%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.32%   |
| Nvidia CK8S Ethernet Controller                                                | 1         | 0.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.32%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.32%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.32%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 295       | 53.93%  |
| WiFi     | 249       | 45.52%  |
| Modem    | 3         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 218       | 50.23%  |
| Ethernet | 216       | 49.77%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 189       | 57.45%  |
| 1     | 120       | 36.47%  |
| 0     | 11        | 3.34%   |
| 3     | 7         | 2.13%   |
| 4     | 2         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 292       | 87.69%  |
| Yes  | 41        | 12.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 43.79%  |
| Qualcomm Atheros Communications | 14        | 9.15%   |
| Cambridge Silicon Radio         | 14        | 9.15%   |
| Broadcom                        | 13        | 8.5%    |
| Realtek Semiconductor           | 10        | 6.54%   |
| Lite-On Technology              | 9         | 5.88%   |
| IMC Networks                    | 5         | 3.27%   |
| Apple                           | 5         | 3.27%   |
| Hewlett-Packard                 | 4         | 2.61%   |
| Dell                            | 3         | 1.96%   |
| Ralink Technology               | 2         | 1.31%   |
| ASUSTek Computer                | 2         | 1.31%   |
| Alps Electric                   | 2         | 1.31%   |
| Toshiba                         | 1         | 0.65%   |
| Foxconn / Hon Hai               | 1         | 0.65%   |
| Chicony Electronics             | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 39        | 25.49%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 14        | 9.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 7.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 5.23%   |
| Realtek Bluetooth Radio                                                             | 7         | 4.58%   |
| Intel Bluetooth wireless interface                                                  | 7         | 4.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.96%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.96%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.96%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.31%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.31%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.31%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.31%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.31%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.31%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.65%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.65%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.65%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.65%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.65%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.65%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.65%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.65%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.65%   |
| Broadcom Bluetooth Device                                                           | 1         | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.65%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.65%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.65%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.65%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.65%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.65%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.65%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 231       | 59.08%  |
| AMD                               | 79        | 20.2%   |
| Nvidia                            | 56        | 14.32%  |
| C-Media Electronics               | 5         | 1.28%   |
| Creative Labs                     | 4         | 1.02%   |
| Logitech                          | 3         | 0.77%   |
| GN Netcom                         | 3         | 0.77%   |
| XMOS                              | 2         | 0.51%   |
| VIA Technologies                  | 1         | 0.26%   |
| Unknown                           | 1         | 0.26%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.26%   |
| Focusrite-Novation                | 1         | 0.26%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.26%   |
| Creative Technology               | 1         | 0.26%   |
| BEHRINGER International           | 1         | 0.26%   |
| Asahi Kasei Microsystems          | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 5.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 4.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 4.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 3.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 16        | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 16        | 3.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 3%      |
| Nvidia High Definition Audio Controller                                                           | 12        | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 2.36%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 11        | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.93%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.93%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 1.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 1.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.5%    |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.28%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.28%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.07%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.07%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 1.07%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.86%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.64%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.64%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 3         | 0.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.64%   |
| XMOS Mayfield Audio                                                                               | 2         | 0.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 2         | 0.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.43%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.43%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 2         | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.43%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2         | 0.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.43%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                                | 1         | 0.21%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 21.83%  |
| SK Hynix            | 44        | 17.46%  |
| Unknown             | 40        | 15.87%  |
| Micron Technology   | 21        | 8.33%   |
| Kingston            | 17        | 6.75%   |
| Crucial             | 13        | 5.16%   |
| Nanya Technology    | 9         | 3.57%   |
| Corsair             | 9         | 3.57%   |
| A-DATA Technology   | 7         | 2.78%   |
| Smart               | 4         | 1.59%   |
| Patriot             | 4         | 1.59%   |
| G.Skill             | 4         | 1.59%   |
| Unknown (ABCD)      | 3         | 1.19%   |
| Team                | 3         | 1.19%   |
| Qimonda             | 2         | 0.79%   |
| Elpida              | 2         | 0.79%   |
| Unifosa             | 1         | 0.4%    |
| Transcend           | 1         | 0.4%    |
| TIMETEC             | 1         | 0.4%    |
| Teikon              | 1         | 0.4%    |
| Sesame              | 1         | 0.4%    |
| Ramaxel Technology  | 1         | 0.4%    |
| PNY                 | 1         | 0.4%    |
| Multilaser          | 1         | 0.4%    |
| Goldkey             | 1         | 0.4%    |
| e2e4                | 1         | 0.4%    |
| DigiBoard           | 1         | 0.4%    |
| Avant               | 1         | 0.4%    |
| ASint Technology    | 1         | 0.4%    |
| Apacer              | 1         | 0.4%    |
| 48spaces            | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s       | 4         | 1.48%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s        | 4         | 1.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 3         | 1.11%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 3         | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.11%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 2         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 2         | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 2         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 2         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 2         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 2         | 0.74%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                | 2         | 0.74%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.74%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 2         | 0.74%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.74%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 2         | 0.74%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                | 2         | 0.74%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 0.74%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 2         | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.74%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.74%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s       | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 0.74%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.74%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s      | 2         | 0.74%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 2         | 0.74%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s           | 2         | 0.74%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 2         | 0.74%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 2         | 0.74%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.74%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 2         | 0.74%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 2         | 0.74%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s         | 1         | 0.37%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                   | 1         | 0.37%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 512MB DIMM 333MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.37%   |
| Unknown RAM Module 4096MB DIMM SDRAM                           | 1         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1         | 0.37%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                   | 1         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM LPDDR4 2400MT/s               | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM LPDDR4 1600MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 1         | 0.37%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                  | 1         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 2MT/s                    | 1         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 1MT/s                    | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 103       | 47.25%  |
| DDR4    | 57        | 26.15%  |
| DDR2    | 30        | 13.76%  |
| SDRAM   | 8         | 3.67%   |
| Unknown | 6         | 2.75%   |
| LPDDR4  | 5         | 2.29%   |
| LPDDR3  | 5         | 2.29%   |
| DDR     | 4         | 1.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 138       | 64.19%  |
| DIMM         | 69        | 32.09%  |
| Row Of Chips | 7         | 3.26%   |
| Chip         | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 81        | 33.2%   |
| 2048  | 63        | 25.82%  |
| 8192  | 61        | 25%     |
| 1024  | 19        | 7.79%   |
| 16384 | 14        | 5.74%   |
| 512   | 3         | 1.23%   |
| 32768 | 2         | 0.82%   |
| 65536 | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 59        | 24.69%  |
| 1333    | 22        | 9.21%   |
| 2400    | 21        | 8.79%   |
| 1334    | 18        | 7.53%   |
| 2667    | 17        | 7.11%   |
| 800     | 15        | 6.28%   |
| 3200    | 14        | 5.86%   |
| 667     | 14        | 5.86%   |
| 2133    | 10        | 4.18%   |
| Unknown | 7         | 2.93%   |
| 2048    | 6         | 2.51%   |
| 1867    | 5         | 2.09%   |
| 1066    | 5         | 2.09%   |
| 1866    | 4         | 1.67%   |
| 400     | 4         | 1.67%   |
| 533     | 3         | 1.26%   |
| 3600    | 2         | 0.84%   |
| 3266    | 2         | 0.84%   |
| 3000    | 2         | 0.84%   |
| 1067    | 2         | 0.84%   |
| 49926   | 1         | 0.42%   |
| 4267    | 1         | 0.42%   |
| 2733    | 1         | 0.42%   |
| 1200    | 1         | 0.42%   |
| 333     | 1         | 0.42%   |
| 2       | 1         | 0.42%   |
| 1       | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 20%     |
| HP Deskjet 3520 series  | 1         | 20%     |
| HP Deskjet 1050 J410    | 1         | 20%     |
| Brother PTUSB Printing  | 1         | 20%     |
| Brother DCP-7055W       | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 26.32%  |
| Acer                                   | 18        | 9.47%   |
| Realtek Semiconductor                  | 16        | 8.42%   |
| IMC Networks                           | 13        | 6.84%   |
| Microdia                               | 10        | 5.26%   |
| Suyin                                  | 9         | 4.74%   |
| Quanta                                 | 8         | 4.21%   |
| Alcor Micro                            | 8         | 4.21%   |
| Sunplus Innovation Technology          | 5         | 2.63%   |
| Silicon Motion                         | 5         | 2.63%   |
| Ricoh                                  | 4         | 2.11%   |
| Logitech                               | 4         | 2.11%   |
| Apple                                  | 4         | 2.11%   |
| Z-Star Microelectronics                | 3         | 1.58%   |
| Samsung Electronics                    | 3         | 1.58%   |
| Lenovo                                 | 3         | 1.58%   |
| Importek                               | 3         | 1.58%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.58%   |
| Syntek                                 | 2         | 1.05%   |
| SJ-180517-N                            | 2         | 1.05%   |
| Lite-On Technology                     | 2         | 1.05%   |
| Generalplus Technology                 | 2         | 1.05%   |
| OmniVision Technologies                | 1         | 0.53%   |
| Nintendo                               | 1         | 0.53%   |
| Microsoft                              | 1         | 0.53%   |
| Luxvisions Innotech Limited            | 1         | 0.53%   |
| KYE Systems (Mouse Systems)            | 1         | 0.53%   |
| Guillemot                              | 1         | 0.53%   |
| Genesys Logic                          | 1         | 0.53%   |
| GEMBIRD                                | 1         | 0.53%   |
| DLUPCA1UIFL9ZS                         | 1         | 0.53%   |
| DJEDDA19IE51V5                         | 1         | 0.53%   |
| DigiTech                               | 1         | 0.53%   |
| ARC International                      | 1         | 0.53%   |
| ALi                                    | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 4.19%   |
| Realtek Integrated_Webcam_HD                        | 7         | 3.66%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 2.09%   |
| Alcor Micro USB 2.0 Web Camera                      | 4         | 2.09%   |
| Acer Lenovo EasyCamera                              | 4         | 2.09%   |
| Acer HD WebCam                                      | 4         | 2.09%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 1.57%   |
| Realtek Integrated Webcam                           | 3         | 1.57%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 1.57%   |
| Chicony HP HD Camera                                | 3         | 1.57%   |
| Chicony EasyCamera                                  | 3         | 1.57%   |
| Apple FaceTime HD Camera                            | 3         | 1.57%   |
| Alcor Micro Asus Integrated Webcam                  | 3         | 1.57%   |
| Sunplus HD WebCam                                   | 2         | 1.05%   |
| SJ-180517-N 1080P Webcam                            | 2         | 1.05%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.05%   |
| Quanta VGA WebCam                                   | 2         | 1.05%   |
| Quanta HP Webcam                                    | 2         | 1.05%   |
| Quanta HP HD Camera                                 | 2         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 1.05%   |
| Logitech Webcam C270                                | 2         | 1.05%   |
| Importek TOSHIBA Web Camera - HD                    | 2         | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.05%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 1.05%   |
| IMC Networks USB 2.0 UVC VGA WebCam                 | 2         | 1.05%   |
| IMC Networks Integrated Camera                      | 2         | 1.05%   |
| Chicony USB 2.0 Camera                              | 2         | 1.05%   |
| Chicony HD WebCam (Acer)                            | 2         | 1.05%   |
| Chicony HD WebCam                                   | 2         | 1.05%   |
| Acer USB 2.0 Camera                                 | 2         | 1.05%   |
| Acer Integrated Camera                              | 2         | 1.05%   |
| Acer BisonCam,NB Pro                                | 2         | 1.05%   |
| Z-Star Webcam                                       | 1         | 0.52%   |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.52%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.52%   |
| Syntek Integrated Camera                            | 1         | 0.52%   |
| Syntek EasyCamera                                   | 1         | 0.52%   |
| Suyin WebCam                                        | 1         | 0.52%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.52%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 0.52%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.52%   |
| Suyin HP Webcam-101                                 | 1         | 0.52%   |
| Suyin HP Webcam                                     | 1         | 0.52%   |
| Suyin HP TrueVision Full HD                         | 1         | 0.52%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.52%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.52%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 0.52%   |
| Sunplus HP Truevision Full HD                       | 1         | 0.52%   |
| Sunplus Full HD webcam                              | 1         | 0.52%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 0.52%   |
| Silicon Motion WebCam SC-10HDD12636N                | 1         | 0.52%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.52%   |
| Silicon Motion Web Camera                           | 1         | 0.52%   |
| Silicon Motion Lenovo EasyCamera                    | 1         | 0.52%   |
| Ricoh Webcam 1000                                   | 1         | 0.52%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.52%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 1         | 0.52%   |
| Ricoh Integrated_Webcam_1.3M                        | 1         | 0.52%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.52%   |
| Realtek USB Camera                                  | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 44%     |
| AuthenTec                  | 6         | 24%     |
| Shenzhen Goodix Technology | 3         | 12%     |
| Upek                       | 2         | 8%      |
| Synaptics                  | 1         | 4%      |
| STMicroelectronics         | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 2         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 8%      |
| AuthenTec AES2810                                         | 2         | 8%      |
| AuthenTec AES2501 Fingerprint Sensor                      | 2         | 8%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 4%      |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 4%      |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 4%      |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 4%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| STMicroelectronics Fingerprint Reader                     | 1         | 4%      |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 4%      |
| Shenzhen Goodix FingerPrint                               | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 4%      |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 4%      |
| AuthenTec AES1600                                         | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 42.86%  |
| O2 Micro    | 2         | 28.57%  |
| Upek        | 1         | 14.29%  |
| Broadcom    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 266       | 80.36%  |
| 1     | 53        | 16.01%  |
| 2     | 12        | 3.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 25        | 34.25%  |
| Graphics card            | 12        | 16.44%  |
| Net/wireless             | 10        | 13.7%   |
| Chipcard                 | 7         | 9.59%   |
| Communication controller | 4         | 5.48%   |
| Unassigned class         | 3         | 4.11%   |
| Camera                   | 3         | 4.11%   |
| Storage                  | 2         | 2.74%   |
| Sound                    | 2         | 2.74%   |
| Multimedia controller    | 2         | 2.74%   |
| Net/ethernet             | 1         | 1.37%   |
| Flash memory             | 1         | 1.37%   |
| Dvb card                 | 1         | 1.37%   |

