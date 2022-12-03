OpenMandriva 4.3 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

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

Total: 1803

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Medion        | MS-7800                     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| HP            | 1589                        | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Foxconn       | 2A92                        | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Intel         | DG41TY AAE47335-302         | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| HP            | 3399                        | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| ECS           | G41T-M7                     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| ASUSTek       | H81M-A                      | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| HP            | 84FD                        | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| ASUSTek       | P5K SE/EPU                  | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | RS880M05                    | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire X1700                | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASRock        | Z170 Extreme4               | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| HP            | 2820h                       | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| ASUSTek       | H170I-PLUS D3               | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Acer          | Aspire X1430                | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| MSI           | P45 Platinum                | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| Unknown       | Unknown                     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Dell          | 0GX297                      | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Dell          | 02YYK5 A01                  | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| ASRock        | Z87 Pro3                    | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | 1850                        | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A II            | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| HP            | 1497                        | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| AMD           | A88                         | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Dell          | 0T656F A01                  | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Acer          | Aspire XC-230               | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| MSI           | A55M-P33                    | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Dell          | 01TKCC A01                  | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| MSI           | A75A-G35                    | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Biostar       | A75MG                       | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| MSI           | MS-7235                     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Acer          | Batman A01                  | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Acer          | Veriton M275                | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| Dell          | 0NV0M7 A02                  | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | 2B34                        | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| HP            | 1495                        | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Dell          | 0H8052                      | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | 158B                        | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| MSI           | B560M PRO                   | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| MSI           | 0A48                        | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Apple         | Mac-F221BEC8                | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Gigabyte      | A520M DS3H                  | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| ASRock        | Z170 Extreme4               | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| MSI           | B350M PRO-VDH               | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| HP            | 8076                        | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| HP            | 8767 A                      | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Unknown       | Intel X79                   | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| HP            | 8053                        | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| HP            | 0A60h                       | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| Dell          | 0RJ290                      | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| ICP / iEi     | B217 V1.0                   | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | 0YJPT1 A00                  | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ASUSTek       | Z87-C                       | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| ASUSTek       | P5KPL-VM                    | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| Gigabyte      | B450M S2H                   | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| Gigabyte      | H81M-S2PH                   | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H                  | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | 18E7                        | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Lenovo        | SHARKBAY NOK                | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| HP            | 1850                        | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| ASRock        | Z97M Pro4                   | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| Dell          | 07KY25 A00                  | [676025f81a](https://linux-hardware.org/?probe=676025f81a) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| MSI           | X470 GAMING M7 AC           | [58947090d5](https://linux-hardware.org/?probe=58947090d5) | Aug 09, 2022 |
| eMachines     | Veriton V2110               | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| ASRock        | AB350 Pro4                  | [2df31a9fbf](https://linux-hardware.org/?probe=2df31a9fbf) | Aug 09, 2022 |
| ASUSTek       | Z87-PRO                     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [642e31466d](https://linux-hardware.org/?probe=642e31466d) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| HP            | 304Bh                       | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| ASUSTek       | M3A78 PRO                   | [0b63e92a55](https://linux-hardware.org/?probe=0b63e92a55) | Aug 07, 2022 |
| HP            | 2215                        | [75304ada6c](https://linux-hardware.org/?probe=75304ada6c) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| MSI           | 2A9C                        | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| MSI           | Z87-G43 GAMING              | [490239de9e](https://linux-hardware.org/?probe=490239de9e) | Aug 05, 2022 |
| Dell          | 0GY6Y8 A01                  | [1ad9e54625](https://linux-hardware.org/?probe=1ad9e54625) | Aug 05, 2022 |
| ASUSTek       | M2N68-AM SE2                | [b68c110fde](https://linux-hardware.org/?probe=b68c110fde) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| Dell          | 0KG317                      | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| ASUSTek       | A68HM-K                     | [d5d981cf7b](https://linux-hardware.org/?probe=d5d981cf7b) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Unknown       | Unknown                     | [0725792da0](https://linux-hardware.org/?probe=0725792da0) | Aug 04, 2022 |
| Gigabyte      | B360M GAMING HD             | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| Lenovo        | 3102                        | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| HP            | 2B29                        | [5fcf3a8320](https://linux-hardware.org/?probe=5fcf3a8320) | Aug 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| Gigabyte      | H87-HD3                     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| HP            | 339A                        | [251a764917](https://linux-hardware.org/?probe=251a764917) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| MSI           | Z590-A PRO                  | [7051f56dda](https://linux-hardware.org/?probe=7051f56dda) | Aug 01, 2022 |
| MSI           | Z77A-GD65                   | [fcadad42a5](https://linux-hardware.org/?probe=fcadad42a5) | Aug 01, 2022 |
| HP            | 843F                        | [eeba83fecb](https://linux-hardware.org/?probe=eeba83fecb) | Aug 01, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [7e6cd7bcb3](https://linux-hardware.org/?probe=7e6cd7bcb3) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| MSI           | B85M-P33                    | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [cb7c9442d6](https://linux-hardware.org/?probe=cb7c9442d6) | Jul 31, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| ASUSTek       | Z97-A-USB31                 | [25db3983fe](https://linux-hardware.org/?probe=25db3983fe) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASRock        | J5040-ITX                   | [2cc4fd5d75](https://linux-hardware.org/?probe=2cc4fd5d75) | Jul 30, 2022 |
| ASUSTek       | M3A78 PRO                   | [c30fca013c](https://linux-hardware.org/?probe=c30fca013c) | Jul 30, 2022 |
| HP            | 2ADC                        | [86608333bc](https://linux-hardware.org/?probe=86608333bc) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| HP            | 0AA0h                       | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| HP            | 18E4                        | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Dell          | OptiPlex 780                | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| ASRock        | Z97 Anniversary             | [768b11cbe4](https://linux-hardware.org/?probe=768b11cbe4) | Jul 28, 2022 |
| MSI           | G31TM-P35                   | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| MSI           | AM1I                        | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| ASRock        | A320M-HDV                   | [cc72c3c914](https://linux-hardware.org/?probe=cc72c3c914) | Jul 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [24e94dd87e](https://linux-hardware.org/?probe=24e94dd87e) | Jul 28, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [0068653ca3](https://linux-hardware.org/?probe=0068653ca3) | Jul 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [d64175b64b](https://linux-hardware.org/?probe=d64175b64b) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| Acer          | Aspire X1930                | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Dell          | 09KPNV A00                  | [610282a0e6](https://linux-hardware.org/?probe=610282a0e6) | Jul 27, 2022 |
| Dell          | 0YF8P5 A00                  | [04ebe8cd88](https://linux-hardware.org/?probe=04ebe8cd88) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| HP            | 1495                        | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| ASUSTek       | Z97-P                       | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Gigabyte      | H55M-S2H                    | [a9a6ab85ac](https://linux-hardware.org/?probe=a9a6ab85ac) | Jul 27, 2022 |
| Dell          | 0NW6H5 A00                  | [b76e9e02fa](https://linux-hardware.org/?probe=b76e9e02fa) | Jul 27, 2022 |
| Gigabyte      | H81M-HD3                    | [0cfb15d654](https://linux-hardware.org/?probe=0cfb15d654) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [e487b063ea](https://linux-hardware.org/?probe=e487b063ea) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Dell          | 0C27VV A03                  | [c1c4edd1e5](https://linux-hardware.org/?probe=c1c4edd1e5) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| Acer          | Aspire XC-830               | [02572035c8](https://linux-hardware.org/?probe=02572035c8) | Jul 26, 2022 |
| Dell          | 04YP6J A02                  | [8161693c82](https://linux-hardware.org/?probe=8161693c82) | Jul 26, 2022 |
| Pegatron      | 2AE2                        | [772ded1d83](https://linux-hardware.org/?probe=772ded1d83) | Jul 25, 2022 |
| Dell          | 0V8WGR A01                  | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| Lenovo        | ThinkCentre M58p 6137B28    | [5473e97fa6](https://linux-hardware.org/?probe=5473e97fa6) | Jul 25, 2022 |
| Gigabyte      | H170M-D3H-GSM-CF            | [ace82a6273](https://linux-hardware.org/?probe=ace82a6273) | Jul 25, 2022 |
| Gigabyte      | G31M-S2L                    | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| Wistron       | ProLiant ML110 G5           | [fdb0300292](https://linux-hardware.org/?probe=fdb0300292) | Jul 24, 2022 |
| Dell          | 0VHWTR A01                  | [9796d6eca3](https://linux-hardware.org/?probe=9796d6eca3) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| ASRock        | AB350 Pro4                  | [7bb0cce634](https://linux-hardware.org/?probe=7bb0cce634) | Jul 24, 2022 |
| MSI           | X470 GAMING PLUS            | [ea3f7e3b48](https://linux-hardware.org/?probe=ea3f7e3b48) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| ASRock        | A300M-STX                   | [bad4adf823](https://linux-hardware.org/?probe=bad4adf823) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| Pegatron      | NARRA5                      | [368503425d](https://linux-hardware.org/?probe=368503425d) | Jul 23, 2022 |
| ASUSTek       | P7H55-M/USB3                | [7e7606e64d](https://linux-hardware.org/?probe=7e7606e64d) | Jul 23, 2022 |
| HP            | 0A68h                       | [cc4b39e6d0](https://linux-hardware.org/?probe=cc4b39e6d0) | Jul 22, 2022 |
| Lenovo        | MAHOBAY NOK                 | [8fc99169c3](https://linux-hardware.org/?probe=8fc99169c3) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Gigabyte      | Z87-HD3                     | [e6bf6ea62f](https://linux-hardware.org/?probe=e6bf6ea62f) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| HP            | 1998                        | [82c8302941](https://linux-hardware.org/?probe=82c8302941) | Jul 21, 2022 |
| Lenovo        | 1.0                         | [e520e716cf](https://linux-hardware.org/?probe=e520e716cf) | Jul 21, 2022 |
| ASUSTek       | H110M-R                     | [34942a8abc](https://linux-hardware.org/?probe=34942a8abc) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| Acer          | Veriton M290                | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| PCChips       | A15G                        | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| ASRock        | B450M-HDV                   | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [55fdb6713c](https://linux-hardware.org/?probe=55fdb6713c) | Jul 19, 2022 |
| Acer          | Veriton M2110G              | [060e101a26](https://linux-hardware.org/?probe=060e101a26) | Jul 19, 2022 |
| ASUSTek       | H110M-R                     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Gigabyte      | P31-DS3L                    | [3b8118fb89](https://linux-hardware.org/?probe=3b8118fb89) | Jul 19, 2022 |
| Gigabyte      | B365M H                     | [879d413452](https://linux-hardware.org/?probe=879d413452) | Jul 19, 2022 |
| Gigabyte      | Z590 GAMING X               | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASUSTek       | M4A78                       | [d04747e05b](https://linux-hardware.org/?probe=d04747e05b) | Jul 17, 2022 |
| HP            | 8906 SMVB                   | [3b89e3e952](https://linux-hardware.org/?probe=3b89e3e952) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [478e424482](https://linux-hardware.org/?probe=478e424482) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| ASUSTek       | P5QLD PRO                   | [fbf3a31304](https://linux-hardware.org/?probe=fbf3a31304) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| Intel         | DQ77MK AAG39642-500         | [7b6a43a9f1](https://linux-hardware.org/?probe=7b6a43a9f1) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [775050f5d9](https://linux-hardware.org/?probe=775050f5d9) | Jul 15, 2022 |
| MSI           | H110M PRO-VD PLUS           | [03eaa344c6](https://linux-hardware.org/?probe=03eaa344c6) | Jul 15, 2022 |
| MSI           | G41M-P28                    | [8bd39aa164](https://linux-hardware.org/?probe=8bd39aa164) | Jul 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [20ea8fab3f](https://linux-hardware.org/?probe=20ea8fab3f) | Jul 14, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [eebcfac8a3](https://linux-hardware.org/?probe=eebcfac8a3) | Jul 14, 2022 |
| MSI           | B250M PRO-VH                | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| Foxconn       | 945 7MD Series              | [30585b93f0](https://linux-hardware.org/?probe=30585b93f0) | Jul 13, 2022 |
| Dell          | 048DY8 A01                  | [aad36ba2cd](https://linux-hardware.org/?probe=aad36ba2cd) | Jul 13, 2022 |
| Intel         | DH55TC AAE70932-303         | [0005417882](https://linux-hardware.org/?probe=0005417882) | Jul 13, 2022 |
| Gigabyte      | A320M-H-CF                  | [9b24417251](https://linux-hardware.org/?probe=9b24417251) | Jul 12, 2022 |
| Gigabyte      | H310M S2H x.x               | [8dbe4d55a5](https://linux-hardware.org/?probe=8dbe4d55a5) | Jul 11, 2022 |
| Colorful T... | H310M-T PRO V21             | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| HP            | 339A                        | [a4606d9234](https://linux-hardware.org/?probe=a4606d9234) | Jul 10, 2022 |
| ASRock        | N68C-S UCC                  | [8c5338cc67](https://linux-hardware.org/?probe=8c5338cc67) | Jul 10, 2022 |
| ASRock        | AMCP7A-ION                  | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| Acer          | FMCP7AM                     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| ASUSTek       | A8N-VM CSM                  | [3cf6a895cd](https://linux-hardware.org/?probe=3cf6a895cd) | Jul 10, 2022 |
| Gigabyte      | GA-A75-UD4H                 | [eba82e4b87](https://linux-hardware.org/?probe=eba82e4b87) | Jul 10, 2022 |
| Gigabyte      | P35-DS3L                    | [67182580cc](https://linux-hardware.org/?probe=67182580cc) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ee629832da](https://linux-hardware.org/?probe=ee629832da) | Jul 09, 2022 |
| Gigabyte      | 945PL-S3                    | [72ffb35881](https://linux-hardware.org/?probe=72ffb35881) | Jul 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | [03f898f89a](https://linux-hardware.org/?probe=03f898f89a) | Jul 09, 2022 |
| ASRock        | A320M-HDV R4.0              | [a39b9bab73](https://linux-hardware.org/?probe=a39b9bab73) | Jul 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [96de3e0656](https://linux-hardware.org/?probe=96de3e0656) | Jul 08, 2022 |
| Dell          | 0R849J A01                  | [3ea68d63c3](https://linux-hardware.org/?probe=3ea68d63c3) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3                    | [195c60abeb](https://linux-hardware.org/?probe=195c60abeb) | Jul 08, 2022 |
| Gigabyte      | 990FXA-UD5                  | [9c7f4deae5](https://linux-hardware.org/?probe=9c7f4deae5) | Jul 08, 2022 |
| ASUSTek       | P5K                         | [31df9a51bc](https://linux-hardware.org/?probe=31df9a51bc) | Jul 08, 2022 |
| Gigabyte      | MBHM87P-00                  | [c02df16b43](https://linux-hardware.org/?probe=c02df16b43) | Jul 08, 2022 |
| ASUSTek       | P5B                         | [0c722e5ec0](https://linux-hardware.org/?probe=0c722e5ec0) | Jul 07, 2022 |
| MSI           | B250M PRO-VH                | [cab2cbb630](https://linux-hardware.org/?probe=cab2cbb630) | Jul 07, 2022 |
| ASUSTek       | ROG Maximus X APEX          | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| Intel         | X79Turbo V1.x               | [497c3810d8](https://linux-hardware.org/?probe=497c3810d8) | Jul 06, 2022 |
| Intel         | DQ35MP AAD82086-702         | [a0cae9f6a9](https://linux-hardware.org/?probe=a0cae9f6a9) | Jul 06, 2022 |
| Gigabyte      | H410M H V3                  | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| MSI           | G41M-P23                    | [8885c18d8c](https://linux-hardware.org/?probe=8885c18d8c) | Jul 06, 2022 |
| HP            | 843C                        | [5f218ccb19](https://linux-hardware.org/?probe=5f218ccb19) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| Biostar       | H310MHC2                    | [9fc3974ab1](https://linux-hardware.org/?probe=9fc3974ab1) | Jul 05, 2022 |
| Gigabyte      | H97M-D3H                    | [46d0a033ca](https://linux-hardware.org/?probe=46d0a033ca) | Jul 05, 2022 |
| ASRock        | H61M-VS                     | [c68e40b7eb](https://linux-hardware.org/?probe=c68e40b7eb) | Jul 05, 2022 |
| Intel         | H61                         | [da6d35599a](https://linux-hardware.org/?probe=da6d35599a) | Jul 04, 2022 |
| Gigabyte      | Z97X-UD5H                   | [8b5f0f789c](https://linux-hardware.org/?probe=8b5f0f789c) | Jul 04, 2022 |
| Dell          | 0Y5DDC A00                  | [e99c8ae46f](https://linux-hardware.org/?probe=e99c8ae46f) | Jul 04, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [440b013dd2](https://linux-hardware.org/?probe=440b013dd2) | Jul 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [98c7e055a3](https://linux-hardware.org/?probe=98c7e055a3) | Jul 03, 2022 |
| ASUSTek       | P5K-VM                      | [ad9d0f9183](https://linux-hardware.org/?probe=ad9d0f9183) | Jul 02, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| HP            | 212B                        | [bd8ef053fd](https://linux-hardware.org/?probe=bd8ef053fd) | Jul 02, 2022 |
| Intel         | DH67BL AAG10189-211         | [ef2f004b52](https://linux-hardware.org/?probe=ef2f004b52) | Jul 02, 2022 |
| ASRock        | Z390 Pro4                   | [25bd784ca6](https://linux-hardware.org/?probe=25bd784ca6) | Jul 02, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [924f16c3d0](https://linux-hardware.org/?probe=924f16c3d0) | Jul 02, 2022 |
| Pegatron      | IPM41-D3                    | [a7cc8d2654](https://linux-hardware.org/?probe=a7cc8d2654) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASUSTek       | P8H77-V LE                  | [0ecaca17cb](https://linux-hardware.org/?probe=0ecaca17cb) | Jun 30, 2022 |
| Gigabyte      | H470 HD3                    | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7a90f7795b](https://linux-hardware.org/?probe=7a90f7795b) | Jun 30, 2022 |
| Biostar       | A68N-5600E                  | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| ASUSTek       | PRIME Z270-A                | [da80c0d1cd](https://linux-hardware.org/?probe=da80c0d1cd) | Jun 29, 2022 |
| MSI           | A320M PRO-VD/S V2           | [fc5a5d812c](https://linux-hardware.org/?probe=fc5a5d812c) | Jun 29, 2022 |
| Gigabyte      | EP45-UD3                    | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| HP            | 18E9                        | [67a4877415](https://linux-hardware.org/?probe=67a4877415) | Jun 29, 2022 |
| Gigabyte      | X58A-UD3R                   | [c414829bec](https://linux-hardware.org/?probe=c414829bec) | Jun 28, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f2f78497e6](https://linux-hardware.org/?probe=f2f78497e6) | Jun 28, 2022 |
| Intel         | DP43BF AAE78171-302         | [0115160101](https://linux-hardware.org/?probe=0115160101) | Jun 28, 2022 |
| Dell          | 0KRC95 A00                  | [04aacdbccd](https://linux-hardware.org/?probe=04aacdbccd) | Jun 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [371c2586d6](https://linux-hardware.org/?probe=371c2586d6) | Jun 27, 2022 |
| HP            | 3047h                       | [32eb7049a1](https://linux-hardware.org/?probe=32eb7049a1) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| ASRock        | A320M-HDV                   | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| Gigabyte      | GA-880GM-USB3               | [4d48252e22](https://linux-hardware.org/?probe=4d48252e22) | Jun 26, 2022 |
| ASRock        | 990FX Killer                | [1e18ee882c](https://linux-hardware.org/?probe=1e18ee882c) | Jun 26, 2022 |
| MSI           | H81M-P33                    | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| Gigabyte      | Z690 UD                     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| Foxconn       | 945 7MC Series              | [16836e63f5](https://linux-hardware.org/?probe=16836e63f5) | Jun 25, 2022 |
| MSI           | A78M-E45                    | [ca217e0ccb](https://linux-hardware.org/?probe=ca217e0ccb) | Jun 25, 2022 |
| ASUSTek       | P5GC-MX/1333                | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| HP            | 3646h                       | [d27deccf27](https://linux-hardware.org/?probe=d27deccf27) | Jun 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6fd11970ae](https://linux-hardware.org/?probe=6fd11970ae) | Jun 22, 2022 |
| MSI           | Z170A KRAIT GAMING          | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Dell          | 0G919G A00                  | [753f0bf2a8](https://linux-hardware.org/?probe=753f0bf2a8) | Jun 21, 2022 |
| ASRock        | M3N78D                      | [8ae000afb6](https://linux-hardware.org/?probe=8ae000afb6) | Jun 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [73aff9ca4a](https://linux-hardware.org/?probe=73aff9ca4a) | Jun 21, 2022 |
| Gigabyte      | H410M S2 V3                 | [79ac3d3f38](https://linux-hardware.org/?probe=79ac3d3f38) | Jun 21, 2022 |
| ASUSTek       | M2NPV-VM                    | [818e78cbe0](https://linux-hardware.org/?probe=818e78cbe0) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ecc6e0f4ef](https://linux-hardware.org/?probe=ecc6e0f4ef) | Jun 21, 2022 |
| ASUSTek       | P8Z68-V LE                  | [5aa18e7ef9](https://linux-hardware.org/?probe=5aa18e7ef9) | Jun 20, 2022 |
| ASUSTek       | M5A97 PLUS                  | [bef449f943](https://linux-hardware.org/?probe=bef449f943) | Jun 20, 2022 |
| ASUSTek       | P8H61-M LE                  | [f3ceed4c58](https://linux-hardware.org/?probe=f3ceed4c58) | Jun 20, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a0d16e2b3c](https://linux-hardware.org/?probe=a0d16e2b3c) | Jun 20, 2022 |
| ASUSTek       | G10DK                       | [3882552921](https://linux-hardware.org/?probe=3882552921) | Jun 19, 2022 |
| Intel         | DH77KC AAG39641-401         | [3d2faf0e14](https://linux-hardware.org/?probe=3d2faf0e14) | Jun 19, 2022 |
| HP            | 843B                        | [21619041e8](https://linux-hardware.org/?probe=21619041e8) | Jun 19, 2022 |
| ASRock        | B365M Pro4                  | [1cc64b4898](https://linux-hardware.org/?probe=1cc64b4898) | Jun 19, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [ff71b93299](https://linux-hardware.org/?probe=ff71b93299) | Jun 19, 2022 |
| Acer          | Aspire TC-605               | [7356d9b33a](https://linux-hardware.org/?probe=7356d9b33a) | Jun 18, 2022 |
| ASUSTek       | PRIME A520M-K               | [e41f474842](https://linux-hardware.org/?probe=e41f474842) | Jun 18, 2022 |
| MSI           | 870-G45                     | [f116a1cf99](https://linux-hardware.org/?probe=f116a1cf99) | Jun 18, 2022 |
| Intel         | H61                         | [358da63cbc](https://linux-hardware.org/?probe=358da63cbc) | Jun 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [494419a571](https://linux-hardware.org/?probe=494419a571) | Jun 17, 2022 |
| ASRock        | QC6000M                     | [176afb6dcc](https://linux-hardware.org/?probe=176afb6dcc) | Jun 17, 2022 |
| Gigabyte      | F2A78M-HD2                  | [d6be55432d](https://linux-hardware.org/?probe=d6be55432d) | Jun 16, 2022 |
| ASUSTek       | P7H55                       | [eda50025d7](https://linux-hardware.org/?probe=eda50025d7) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [dab54fda61](https://linux-hardware.org/?probe=dab54fda61) | Jun 16, 2022 |
| ASUSTek       | P8B75-M                     | [9ab6f4690f](https://linux-hardware.org/?probe=9ab6f4690f) | Jun 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fb36d0a844](https://linux-hardware.org/?probe=fb36d0a844) | Jun 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H V2               | [684cf228c4](https://linux-hardware.org/?probe=684cf228c4) | Jun 15, 2022 |
| ASUSTek       | P5QPL-AM                    | [f67a5f860e](https://linux-hardware.org/?probe=f67a5f860e) | Jun 15, 2022 |
| MSI           | Z77A-G43                    | [ead05322dd](https://linux-hardware.org/?probe=ead05322dd) | Jun 15, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [88104c621b](https://linux-hardware.org/?probe=88104c621b) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | H81T                        | [6687cc21f3](https://linux-hardware.org/?probe=6687cc21f3) | Jun 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [0ca08532ce](https://linux-hardware.org/?probe=0ca08532ce) | Jun 14, 2022 |
| MSI           | A320M PRO-VH                | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| Packard Be... | MCP73                       | [0542e4233e](https://linux-hardware.org/?probe=0542e4233e) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | [8bb84d5aaf](https://linux-hardware.org/?probe=8bb84d5aaf) | Jun 14, 2022 |
| Gigabyte      | H510M H                     | [75fd209e13](https://linux-hardware.org/?probe=75fd209e13) | Jun 14, 2022 |
| MSI           | MS-7360                     | [fe6f5deaa0](https://linux-hardware.org/?probe=fe6f5deaa0) | Jun 13, 2022 |
| HP            | 18E7                        | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| Dell          | 09KPNV A00                  | [ed59551343](https://linux-hardware.org/?probe=ed59551343) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | [be77f2ffd4](https://linux-hardware.org/?probe=be77f2ffd4) | Jun 12, 2022 |
| Gigabyte      | P55A-UD3                    | [66062b5350](https://linux-hardware.org/?probe=66062b5350) | Jun 12, 2022 |
| MSI           | MS-7360                     | [df15dd80d4](https://linux-hardware.org/?probe=df15dd80d4) | Jun 12, 2022 |
| MSI           | H55M-E33                    | [1fa7005827](https://linux-hardware.org/?probe=1fa7005827) | Jun 12, 2022 |
| Gigabyte      | 990FXA-UD3                  | [df35df715a](https://linux-hardware.org/?probe=df35df715a) | Jun 12, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [4a67ad74b7](https://linux-hardware.org/?probe=4a67ad74b7) | Jun 12, 2022 |
| ASUSTek       | H110I-PLUS                  | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4e830e41ec](https://linux-hardware.org/?probe=4e830e41ec) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b0e6137115](https://linux-hardware.org/?probe=b0e6137115) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [576fc8e8ed](https://linux-hardware.org/?probe=576fc8e8ed) | Jun 11, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [6818c8dc03](https://linux-hardware.org/?probe=6818c8dc03) | Jun 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | [712464602f](https://linux-hardware.org/?probe=712464602f) | Jun 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [839663a1af](https://linux-hardware.org/?probe=839663a1af) | Jun 10, 2022 |
| Acer          | Aspire M3970                | [66016e2c0d](https://linux-hardware.org/?probe=66016e2c0d) | Jun 10, 2022 |
| ASUSTek       | M5A97 PLUS                  | [668b715efd](https://linux-hardware.org/?probe=668b715efd) | Jun 10, 2022 |
| Unknown       | SKYBAY                      | [ca3c55b50a](https://linux-hardware.org/?probe=ca3c55b50a) | Jun 10, 2022 |
| Acer          | TPDS05 R3700                | [0203dde7bd](https://linux-hardware.org/?probe=0203dde7bd) | Jun 09, 2022 |
| Lenovo        | ThinkCentre M58p 9965A5G    | [35ee376f8a](https://linux-hardware.org/?probe=35ee376f8a) | Jun 09, 2022 |
| MSI           | NF980-G65                   | [81348124ff](https://linux-hardware.org/?probe=81348124ff) | Jun 09, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [f498a9e83f](https://linux-hardware.org/?probe=f498a9e83f) | Jun 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| ASRock        | N68C-S UCC                  | [ca2987cf23](https://linux-hardware.org/?probe=ca2987cf23) | Jun 08, 2022 |
| Foxconn       | H55MXV-LE                   | [b1c70f54f5](https://linux-hardware.org/?probe=b1c70f54f5) | Jun 08, 2022 |
| Intel         | DG33FB AAD81072-306         | [78abe45a29](https://linux-hardware.org/?probe=78abe45a29) | Jun 08, 2022 |
| Foxconn       | 2ADA                        | [469b57fa93](https://linux-hardware.org/?probe=469b57fa93) | Jun 08, 2022 |
| Medion        | H110H4-CM2                  | [6c7f5da497](https://linux-hardware.org/?probe=6c7f5da497) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ffceb89203](https://linux-hardware.org/?probe=ffceb89203) | Jun 07, 2022 |
| HP            | 843F                        | [59bbcdff88](https://linux-hardware.org/?probe=59bbcdff88) | Jun 07, 2022 |
| Dell          | 088DT1 A00                  | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [74c4c38cae](https://linux-hardware.org/?probe=74c4c38cae) | Jun 07, 2022 |
| Lenovo        | 3140 NOK                    | [03619a223f](https://linux-hardware.org/?probe=03619a223f) | Jun 07, 2022 |
| Shuttle       | FL10J                       | [8c27549c9e](https://linux-hardware.org/?probe=8c27549c9e) | Jun 07, 2022 |
| Gigabyte      | G41MT-S2                    | [f1c3ae3db4](https://linux-hardware.org/?probe=f1c3ae3db4) | Jun 06, 2022 |
| ASUSTek       | PRIME A320M-K               | [ba86261552](https://linux-hardware.org/?probe=ba86261552) | Jun 06, 2022 |
| MSI           | A55M-P33                    | [7b11750186](https://linux-hardware.org/?probe=7b11750186) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| OEM           | H110                        | [d9bb28c841](https://linux-hardware.org/?probe=d9bb28c841) | Jun 05, 2022 |
| HP            | 8648                        | [155bf69660](https://linux-hardware.org/?probe=155bf69660) | Jun 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [1504d60bf5](https://linux-hardware.org/?probe=1504d60bf5) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [aca6d1da03](https://linux-hardware.org/?probe=aca6d1da03) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c0eb59d595](https://linux-hardware.org/?probe=c0eb59d595) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [80832b1c72](https://linux-hardware.org/?probe=80832b1c72) | Jun 05, 2022 |
| Dell          | 0GY6Y8 A03                  | [4668e3772e](https://linux-hardware.org/?probe=4668e3772e) | Jun 05, 2022 |
| ASRock        | 880GM-LE FX                 | [cd7a02b187](https://linux-hardware.org/?probe=cd7a02b187) | Jun 05, 2022 |
| Acer          | Veriton N4670G              | [0b85f95c4c](https://linux-hardware.org/?probe=0b85f95c4c) | Jun 05, 2022 |
| ASRock        | Z97 Anniversary             | [b6a332c085](https://linux-hardware.org/?probe=b6a332c085) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [4d3213676b](https://linux-hardware.org/?probe=4d3213676b) | Jun 04, 2022 |
| Gigabyte      | H110M-S2H-CF                | [7ccdf657a0](https://linux-hardware.org/?probe=7ccdf657a0) | Jun 04, 2022 |
| Gigabyte      | F2A88X-D3H                  | [5b7b255faf](https://linux-hardware.org/?probe=5b7b255faf) | Jun 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8ac5eb21ad](https://linux-hardware.org/?probe=8ac5eb21ad) | Jun 04, 2022 |
| ASUSTek       | P5B-VM                      | [0ee6de9e23](https://linux-hardware.org/?probe=0ee6de9e23) | Jun 03, 2022 |
| ASUSTek       | Z170-A                      | [ed86450031](https://linux-hardware.org/?probe=ed86450031) | Jun 03, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f011e99578](https://linux-hardware.org/?probe=f011e99578) | Jun 03, 2022 |
| HP            | 1998                        | [e1bd6ae3e1](https://linux-hardware.org/?probe=e1bd6ae3e1) | Jun 03, 2022 |
| ASRock        | Q1900B-ITX                  | [cec9d6d159](https://linux-hardware.org/?probe=cec9d6d159) | Jun 03, 2022 |
| Dell          | 040DDP A01                  | [208a2ee137](https://linux-hardware.org/?probe=208a2ee137) | Jun 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [eca3bd70a8](https://linux-hardware.org/?probe=eca3bd70a8) | Jun 02, 2022 |
| Dell          | 0GDG8Y A00                  | [ae659a73f9](https://linux-hardware.org/?probe=ae659a73f9) | Jun 02, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [536c6e19de](https://linux-hardware.org/?probe=536c6e19de) | Jun 01, 2022 |
| Dell          | 00V62H A00                  | [7622f595c6](https://linux-hardware.org/?probe=7622f595c6) | Jun 01, 2022 |
| HP            | 8054                        | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| Intel         | D2700DC AAG32420-602        | [a55bb5f425](https://linux-hardware.org/?probe=a55bb5f425) | Jun 01, 2022 |
| Dell          | 0J3C2F A02                  | [9ff329a1fd](https://linux-hardware.org/?probe=9ff329a1fd) | May 31, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| HP            | 3047h                       | [59affe5430](https://linux-hardware.org/?probe=59affe5430) | May 31, 2022 |
| Lenovo        | 3148 SDK0K13476 WIN 3306... | [5723328e24](https://linux-hardware.org/?probe=5723328e24) | May 31, 2022 |
| Gigabyte      | X570 AORUS PRO              | [c39f904361](https://linux-hardware.org/?probe=c39f904361) | May 30, 2022 |
| ASUSTek       | Maximus II Formula          | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| ASRock        | A88M-G                      | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| Lenovo        | ThinkCentre M90p 5536WAZ    | [c6c32dc36b](https://linux-hardware.org/?probe=c6c32dc36b) | May 30, 2022 |
| Intel         | DG43GT AAE62768-300         | [643ebac3b3](https://linux-hardware.org/?probe=643ebac3b3) | May 29, 2022 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | [2f5bdf6497](https://linux-hardware.org/?probe=2f5bdf6497) | May 29, 2022 |
| ASRock        | B85M-HDS                    | [54a1e6b445](https://linux-hardware.org/?probe=54a1e6b445) | May 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | [d1c4685112](https://linux-hardware.org/?probe=d1c4685112) | May 29, 2022 |
| MSI           | Z590-A PRO                  | [55a37b3d9c](https://linux-hardware.org/?probe=55a37b3d9c) | May 29, 2022 |
| ASUSTek       | AM1M-A/BR                   | [c8532fbb66](https://linux-hardware.org/?probe=c8532fbb66) | May 29, 2022 |
| HP            | 81C3                        | [7a57cdec90](https://linux-hardware.org/?probe=7a57cdec90) | May 28, 2022 |
| Gigabyte      | B560M H                     | [7e17227514](https://linux-hardware.org/?probe=7e17227514) | May 27, 2022 |
| MSI           | 785G-E53                    | [18ee1d0980](https://linux-hardware.org/?probe=18ee1d0980) | May 27, 2022 |
| Positivo      | POS-PIQ57BQA                | [f33ecab5de](https://linux-hardware.org/?probe=f33ecab5de) | May 27, 2022 |
| ASRock        | H270M-ITX/ac                | [e77300d74a](https://linux-hardware.org/?probe=e77300d74a) | May 27, 2022 |
| MSI           | Boston                      | [7e3c443fb1](https://linux-hardware.org/?probe=7e3c443fb1) | May 27, 2022 |
| BESSTAR Te... | UM350                       | [e4082f489e](https://linux-hardware.org/?probe=e4082f489e) | May 27, 2022 |
| HP            | 212B                        | [14db1a01c5](https://linux-hardware.org/?probe=14db1a01c5) | May 26, 2022 |
| Intel         | DP67BA AAG10219-300         | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [6cc0861cc3](https://linux-hardware.org/?probe=6cc0861cc3) | May 26, 2022 |
| Positivo      | POS-PIQ57BQA                | [2175bbae83](https://linux-hardware.org/?probe=2175bbae83) | May 26, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [ae17b83ca5](https://linux-hardware.org/?probe=ae17b83ca5) | May 26, 2022 |
| Gigabyte      | B85M-D3H-A                  | [36e5918bc8](https://linux-hardware.org/?probe=36e5918bc8) | May 25, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [93d4bd3b14](https://linux-hardware.org/?probe=93d4bd3b14) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [7260e3bf3b](https://linux-hardware.org/?probe=7260e3bf3b) | May 24, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [b3958742aa](https://linux-hardware.org/?probe=b3958742aa) | May 24, 2022 |
| ASUSTek       | B150M-A/M.2                 | [3aea6596c6](https://linux-hardware.org/?probe=3aea6596c6) | May 23, 2022 |
| Intel         | DH55HC AAE70933-505         | [6c27613f85](https://linux-hardware.org/?probe=6c27613f85) | May 23, 2022 |
| HP            | 1495                        | [68ead7bd6a](https://linux-hardware.org/?probe=68ead7bd6a) | May 23, 2022 |
| MSI           | B450I GAMING PLUS AC        | [dbc555961b](https://linux-hardware.org/?probe=dbc555961b) | May 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [ee4d26d407](https://linux-hardware.org/?probe=ee4d26d407) | May 23, 2022 |
| Unknown       | P4M800Pro-8237              | [31c80b1ea7](https://linux-hardware.org/?probe=31c80b1ea7) | May 23, 2022 |
| Foxconn       | 2A8C                        | [eda69f1faf](https://linux-hardware.org/?probe=eda69f1faf) | May 22, 2022 |
| Lenovo        | SDK0E50510 WIN              | [6efef2bd1e](https://linux-hardware.org/?probe=6efef2bd1e) | May 22, 2022 |
| MSI           | MS-7235                     | [cb9b6ded76](https://linux-hardware.org/?probe=cb9b6ded76) | May 22, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [da237b1570](https://linux-hardware.org/?probe=da237b1570) | May 21, 2022 |
| MSI           | B350M PRO-VD PLUS           | [6098005a1a](https://linux-hardware.org/?probe=6098005a1a) | May 21, 2022 |
| MSI           | MS-7235                     | [4dfaad64fd](https://linux-hardware.org/?probe=4dfaad64fd) | May 21, 2022 |
| Gigabyte      | Z77P-D3                     | [fc0a2b2595](https://linux-hardware.org/?probe=fc0a2b2595) | May 21, 2022 |
| MSI           | 970 GAMING                  | [082a1ac531](https://linux-hardware.org/?probe=082a1ac531) | May 21, 2022 |
| MSI           | MS-7309                     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [886a958a28](https://linux-hardware.org/?probe=886a958a28) | May 20, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Gigabyte      | A520M S2H                   | [74a45b7cec](https://linux-hardware.org/?probe=74a45b7cec) | May 19, 2022 |
| ASRock        | A88M-G                      | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| Lenovo        | ThinkCentre M57 9181A28     | [51ec46a243](https://linux-hardware.org/?probe=51ec46a243) | May 19, 2022 |
| Dell          | 05842Y A00                  | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| MSI           | B450-A PRO MAX              | [7b1a855704](https://linux-hardware.org/?probe=7b1a855704) | May 19, 2022 |
| Biostar       | A68N-5600E                  | [025e31f0d1](https://linux-hardware.org/?probe=025e31f0d1) | May 19, 2022 |
| EVGA          | 151-IB-E699                 | [7df0c6167d](https://linux-hardware.org/?probe=7df0c6167d) | May 18, 2022 |
| Gigabyte      | H55M-S2                     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| MSI           | Z97-G45 GAMING              | [1b02844b0b](https://linux-hardware.org/?probe=1b02844b0b) | May 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91638ab9be](https://linux-hardware.org/?probe=91638ab9be) | May 17, 2022 |
| Gigabyte      | B75N                        | [b3e561590b](https://linux-hardware.org/?probe=b3e561590b) | May 17, 2022 |
| ASUSTek       | P5QL PRO                    | [60e61a51df](https://linux-hardware.org/?probe=60e61a51df) | May 17, 2022 |
| ASUSTek       | P5Q                         | [614f6cf0c6](https://linux-hardware.org/?probe=614f6cf0c6) | May 16, 2022 |
| ASUSTek       | H110T                       | [e1d711b496](https://linux-hardware.org/?probe=e1d711b496) | May 16, 2022 |
| HP            | 8056                        | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| Dell          | 0Y2MRG A00                  | [1cf635a476](https://linux-hardware.org/?probe=1cf635a476) | May 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [39824d4e4d](https://linux-hardware.org/?probe=39824d4e4d) | May 15, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [528659dab4](https://linux-hardware.org/?probe=528659dab4) | May 15, 2022 |
| ASUSTek       | B85M-G                      | [dd305c13de](https://linux-hardware.org/?probe=dd305c13de) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| ASUSTek       | M2A-VM                      | [7708e385fb](https://linux-hardware.org/?probe=7708e385fb) | May 14, 2022 |
| ASUSTek       | H110M-K                     | [d0f043ff65](https://linux-hardware.org/?probe=d0f043ff65) | May 14, 2022 |
| Dell          | 0FM586                      | [82aefc332b](https://linux-hardware.org/?probe=82aefc332b) | May 14, 2022 |
| Gigabyte      | P55-UD3R                    | [638e77ebd8](https://linux-hardware.org/?probe=638e77ebd8) | May 13, 2022 |
| ASUSTek       | B85M-G                      | [6dee77b5ca](https://linux-hardware.org/?probe=6dee77b5ca) | May 13, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [434d2b0bec](https://linux-hardware.org/?probe=434d2b0bec) | May 13, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| ASUSTek       | NARRA3                      | [ca524c9e95](https://linux-hardware.org/?probe=ca524c9e95) | May 13, 2022 |
| ASRock        | H61M-HP4                    | [f0bda638ba](https://linux-hardware.org/?probe=f0bda638ba) | May 13, 2022 |
| ASUSTek       | H110M-R                     | [adbb3eb389](https://linux-hardware.org/?probe=adbb3eb389) | May 12, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| Biostar       | G31M+                       | [7440220607](https://linux-hardware.org/?probe=7440220607) | May 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [3494019436](https://linux-hardware.org/?probe=3494019436) | May 11, 2022 |
| HP            | 0AA8h                       | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| MSI           | 760GM-P34                   | [85bea22dfe](https://linux-hardware.org/?probe=85bea22dfe) | May 09, 2022 |
| HP            | 1998                        | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| Positivo      | POS-PIG41BA                 | [40a9a00430](https://linux-hardware.org/?probe=40a9a00430) | May 08, 2022 |
| ASUSTek       | PRIME B365M-A               | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d7c94f5e83](https://linux-hardware.org/?probe=d7c94f5e83) | May 07, 2022 |
| HP            | 802F                        | [5afe279c1b](https://linux-hardware.org/?probe=5afe279c1b) | May 07, 2022 |
| Lenovo        | SDK0E50510 WIN 262504835... | [5565a2f131](https://linux-hardware.org/?probe=5565a2f131) | May 07, 2022 |
| Positivo      | POS-PIH81DI                 | [f7b64e05f8](https://linux-hardware.org/?probe=f7b64e05f8) | May 06, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [76e6cc98aa](https://linux-hardware.org/?probe=76e6cc98aa) | May 05, 2022 |
| ASUSTek       | A68HM-PLUS                  | [149d1c8c87](https://linux-hardware.org/?probe=149d1c8c87) | May 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8f15e66f2d](https://linux-hardware.org/?probe=8f15e66f2d) | May 05, 2022 |
| ASRock        | QC5000-ITX/WiFi             | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| Gigabyte      | B150N-GSM-CF                | [b49d3deec3](https://linux-hardware.org/?probe=b49d3deec3) | May 05, 2022 |
| HP            | 18E7                        | [57194bb53c](https://linux-hardware.org/?probe=57194bb53c) | May 04, 2022 |
| HP            | 1998                        | [b35fc936e5](https://linux-hardware.org/?probe=b35fc936e5) | May 04, 2022 |
| MSI           | B360M PRO-VDH               | [23b80ec93e](https://linux-hardware.org/?probe=23b80ec93e) | May 04, 2022 |
| Dell          | 03NVJ6 A04                  | [ebacf887d7](https://linux-hardware.org/?probe=ebacf887d7) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| HP            | 2B47                        | [e7433db9d1](https://linux-hardware.org/?probe=e7433db9d1) | May 03, 2022 |
| ASUSTek       | PRIME X370-A                | [4d1f9886c2](https://linux-hardware.org/?probe=4d1f9886c2) | May 03, 2022 |
| Acer          | H57M01                      | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Dell          | 0M9KCM A01                  | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Acer          | Aspire XC-230               | [b80fa8b04f](https://linux-hardware.org/?probe=b80fa8b04f) | May 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [d874b5668c](https://linux-hardware.org/?probe=d874b5668c) | May 02, 2022 |
| Positivo      | POS-EIBTPDC                 | [a9a49f094d](https://linux-hardware.org/?probe=a9a49f094d) | May 01, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| MSI           | MS-7267                     | [12ef52bd6d](https://linux-hardware.org/?probe=12ef52bd6d) | May 01, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [18daf9705b](https://linux-hardware.org/?probe=18daf9705b) | Apr 30, 2022 |
| MSI           | A320M-A PRO MAX             | [dc1c0d091e](https://linux-hardware.org/?probe=dc1c0d091e) | Apr 30, 2022 |
| ASRock        | 880GM-LE FX                 | [f695420d7e](https://linux-hardware.org/?probe=f695420d7e) | Apr 30, 2022 |
| ASUSTek       | P5QL                        | [121da21f08](https://linux-hardware.org/?probe=121da21f08) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8fee79ec7](https://linux-hardware.org/?probe=e8fee79ec7) | Apr 30, 2022 |
| Lenovo        | ThinkCentre M58 7627AD5     | [05a686b922](https://linux-hardware.org/?probe=05a686b922) | Apr 30, 2022 |
| ASUSTek       | P5KPL-AM                    | [7c398e1d2b](https://linux-hardware.org/?probe=7c398e1d2b) | Apr 30, 2022 |
| HP            | 1497                        | [559a844943](https://linux-hardware.org/?probe=559a844943) | Apr 30, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [13fd8e249d](https://linux-hardware.org/?probe=13fd8e249d) | Apr 30, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [3b9e57fc42](https://linux-hardware.org/?probe=3b9e57fc42) | Apr 30, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [7dfb4ca9f5](https://linux-hardware.org/?probe=7dfb4ca9f5) | Apr 29, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [af2b0de49b](https://linux-hardware.org/?probe=af2b0de49b) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Intel         | X79 V2.72B                  | [396faf60b6](https://linux-hardware.org/?probe=396faf60b6) | Apr 29, 2022 |
| Foxconn       | 2A8C                        | [eb747a3063](https://linux-hardware.org/?probe=eb747a3063) | Apr 29, 2022 |
| ASUSTek       | B150M-A                     | [fa213f6681](https://linux-hardware.org/?probe=fa213f6681) | Apr 28, 2022 |
| ECS           | H61H2-CM                    | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Dell          | 0YJHYD A00                  | [6111a9976e](https://linux-hardware.org/?probe=6111a9976e) | Apr 27, 2022 |
| ASUSTek       | M51BC                       | [f997f2d1c1](https://linux-hardware.org/?probe=f997f2d1c1) | Apr 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [b15f34dd41](https://linux-hardware.org/?probe=b15f34dd41) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d354934f98](https://linux-hardware.org/?probe=d354934f98) | Apr 27, 2022 |
| Foxconn       | H61MXE                      | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [00728feb75](https://linux-hardware.org/?probe=00728feb75) | Apr 26, 2022 |
| Gigabyte      | B85M-D2V                    | [ca876d7b83](https://linux-hardware.org/?probe=ca876d7b83) | Apr 26, 2022 |
| Acer          | Aspire TC-780               | [501877dba5](https://linux-hardware.org/?probe=501877dba5) | Apr 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4f8108d1e](https://linux-hardware.org/?probe=f4f8108d1e) | Apr 25, 2022 |
| Intel         | DH61CR AAG14064-204         | [82d6475ef3](https://linux-hardware.org/?probe=82d6475ef3) | Apr 25, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [b0a2546f9f](https://linux-hardware.org/?probe=b0a2546f9f) | Apr 24, 2022 |
| Dell          | 08WKV3 A00                  | [e6ef37e2a0](https://linux-hardware.org/?probe=e6ef37e2a0) | Apr 24, 2022 |
| MSI           | G31M3 V2                    | [4c1d75729a](https://linux-hardware.org/?probe=4c1d75729a) | Apr 24, 2022 |
| Dell          | 0T1D10 A01                  | [660e4984f7](https://linux-hardware.org/?probe=660e4984f7) | Apr 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a1eaf40bdb](https://linux-hardware.org/?probe=a1eaf40bdb) | Apr 24, 2022 |
| HP            | 2820h                       | [3918640e67](https://linux-hardware.org/?probe=3918640e67) | Apr 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3d101a3380](https://linux-hardware.org/?probe=3d101a3380) | Apr 23, 2022 |
| ASUSTek       | M4A78-EM                    | [5ef7775195](https://linux-hardware.org/?probe=5ef7775195) | Apr 23, 2022 |
| Dell          | 0KJCC5 A00                  | [00181fd144](https://linux-hardware.org/?probe=00181fd144) | Apr 23, 2022 |
| MSI           | PRO B660-A DDR4             | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| HP            | 18E9                        | [36ff483a2f](https://linux-hardware.org/?probe=36ff483a2f) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| HP            | 8719                        | [7e0ae3d91f](https://linux-hardware.org/?probe=7e0ae3d91f) | Apr 22, 2022 |
| ASUSTek       | P5B                         | [223154e54d](https://linux-hardware.org/?probe=223154e54d) | Apr 22, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| MSI           | X470 GAMING PLUS            | [33bcd3ec01](https://linux-hardware.org/?probe=33bcd3ec01) | Apr 20, 2022 |
| Lenovo        | SDK0E50510 WIN              | [3d829a871e](https://linux-hardware.org/?probe=3d829a871e) | Apr 20, 2022 |
| ASUSTek       | P5G41T-M LX3                | [a21dad9ee4](https://linux-hardware.org/?probe=a21dad9ee4) | Apr 20, 2022 |
| Gigabyte      | MZAPLBP-00                  | [62b2cada75](https://linux-hardware.org/?probe=62b2cada75) | Apr 20, 2022 |
| Dell          | 0YF8P5 A00                  | [11d8a53dd0](https://linux-hardware.org/?probe=11d8a53dd0) | Apr 20, 2022 |
| ASRock        | B550 Pro4                   | [a1806b3e86](https://linux-hardware.org/?probe=a1806b3e86) | Apr 20, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | [61c0639dae](https://linux-hardware.org/?probe=61c0639dae) | Apr 19, 2022 |
| MSI           | B150 PC MATE                | [34c7fe45bc](https://linux-hardware.org/?probe=34c7fe45bc) | Apr 19, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [d162e9aa70](https://linux-hardware.org/?probe=d162e9aa70) | Apr 19, 2022 |
| Alienware     | 0VDT73 A00                  | [1053bd7904](https://linux-hardware.org/?probe=1053bd7904) | Apr 18, 2022 |
| ASUSTek       | M2N68-AM                    | [15c9b8ea76](https://linux-hardware.org/?probe=15c9b8ea76) | Apr 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [66ac59c0a3](https://linux-hardware.org/?probe=66ac59c0a3) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [874e39c8ef](https://linux-hardware.org/?probe=874e39c8ef) | Apr 18, 2022 |
| Gigabyte      | B85M-DS3H                   | [c278a421cd](https://linux-hardware.org/?probe=c278a421cd) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4c8ca0d53f](https://linux-hardware.org/?probe=4c8ca0d53f) | Apr 18, 2022 |
| ASRock        | Z68 Extreme4                | [36da46e911](https://linux-hardware.org/?probe=36da46e911) | Apr 18, 2022 |
| Gigabyte      | G41MT-ES2L                  | [fbeec44852](https://linux-hardware.org/?probe=fbeec44852) | Apr 18, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [3ef27dafd2](https://linux-hardware.org/?probe=3ef27dafd2) | Apr 17, 2022 |
| HP            | 86E9 A                      | [11004e6442](https://linux-hardware.org/?probe=11004e6442) | Apr 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [f940c46866](https://linux-hardware.org/?probe=f940c46866) | Apr 17, 2022 |
| HP            | 1850                        | [7c24268bc3](https://linux-hardware.org/?probe=7c24268bc3) | Apr 17, 2022 |
| Dell          | 08WKV3 A00                  | [f3afe20dae](https://linux-hardware.org/?probe=f3afe20dae) | Apr 16, 2022 |
| ASRock        | B560M Pro4                  | [2fe297dc4b](https://linux-hardware.org/?probe=2fe297dc4b) | Apr 16, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [65b68d5bb9](https://linux-hardware.org/?probe=65b68d5bb9) | Apr 16, 2022 |
| ASUSTek       | P8H67-M LX                  | [65116c3b59](https://linux-hardware.org/?probe=65116c3b59) | Apr 16, 2022 |
| Gigabyte      | EP31-DS3L                   | [a0a68f0980](https://linux-hardware.org/?probe=a0a68f0980) | Apr 15, 2022 |
| ASUSTek       | M2NPV-MX                    | [8192abd2c4](https://linux-hardware.org/?probe=8192abd2c4) | Apr 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bdc8f9b39e](https://linux-hardware.org/?probe=bdc8f9b39e) | Apr 15, 2022 |
| Dell          | 0HN7XN A01                  | [5a9ba12201](https://linux-hardware.org/?probe=5a9ba12201) | Apr 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [0a8d0e5302](https://linux-hardware.org/?probe=0a8d0e5302) | Apr 15, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [36d5c02824](https://linux-hardware.org/?probe=36d5c02824) | Apr 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [7cc9a1bbb7](https://linux-hardware.org/?probe=7cc9a1bbb7) | Apr 15, 2022 |
| MSI           | 790FX-GD70                  | [0a8776ac60](https://linux-hardware.org/?probe=0a8776ac60) | Apr 15, 2022 |
| GALAX         | A320M G10g                  | [958fc1bf94](https://linux-hardware.org/?probe=958fc1bf94) | Apr 14, 2022 |
| MSI           | A68HM-E33 V2                | [9f77473319](https://linux-hardware.org/?probe=9f77473319) | Apr 14, 2022 |
| Dell          | 0YC03K A04                  | [4fd6bd10ff](https://linux-hardware.org/?probe=4fd6bd10ff) | Apr 13, 2022 |
| Unknown       | Unknown                     | [4d5c3fc937](https://linux-hardware.org/?probe=4d5c3fc937) | Apr 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [c5c12d6818](https://linux-hardware.org/?probe=c5c12d6818) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M71e 5033A3U    | [9b0b83369e](https://linux-hardware.org/?probe=9b0b83369e) | Apr 12, 2022 |
| ASRock        | N68-VS3 UCC                 | [1ca06f94c7](https://linux-hardware.org/?probe=1ca06f94c7) | Apr 12, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [842cfcf606](https://linux-hardware.org/?probe=842cfcf606) | Apr 12, 2022 |
| ASUSTek       | M4A88T-M                    | [934e06ad74](https://linux-hardware.org/?probe=934e06ad74) | Apr 12, 2022 |
| ASUSTek       | PRIME X470-PRO              | [40d527cfe8](https://linux-hardware.org/?probe=40d527cfe8) | Apr 12, 2022 |
| ASUSTek       | A88XM-PLUS                  | [54f7cac3d4](https://linux-hardware.org/?probe=54f7cac3d4) | Apr 11, 2022 |
| Positivo      | POS-MI945AA                 | [581272b7c1](https://linux-hardware.org/?probe=581272b7c1) | Apr 11, 2022 |
| Itautec       | ST 4265                     | [b2facb728e](https://linux-hardware.org/?probe=b2facb728e) | Apr 10, 2022 |
| MSI           | H510M-A PRO                 | [d93ab23121](https://linux-hardware.org/?probe=d93ab23121) | Apr 10, 2022 |
| Dell          | 055H3G A01                  | [a41b7fbf00](https://linux-hardware.org/?probe=a41b7fbf00) | Apr 10, 2022 |
| Lenovo        | ThinkCentre M58p 7484ANU    | [2d7d0de436](https://linux-hardware.org/?probe=2d7d0de436) | Apr 10, 2022 |
| Gigabyte      | H81M-S2PV                   | [4c37e32ae6](https://linux-hardware.org/?probe=4c37e32ae6) | Apr 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| MSI           | H110M ECO                   | [c01d51d1f5](https://linux-hardware.org/?probe=c01d51d1f5) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b0840dd295](https://linux-hardware.org/?probe=b0840dd295) | Apr 09, 2022 |
| MSI           | MS-7369                     | [0a32c9427a](https://linux-hardware.org/?probe=0a32c9427a) | Apr 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [48c13b2a02](https://linux-hardware.org/?probe=48c13b2a02) | Apr 09, 2022 |
| ASRock        | Z170 Extreme6               | [616ea06acb](https://linux-hardware.org/?probe=616ea06acb) | Apr 09, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [8f7798d84a](https://linux-hardware.org/?probe=8f7798d84a) | Apr 08, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [1a031845b1](https://linux-hardware.org/?probe=1a031845b1) | Apr 08, 2022 |
| HP            | 3397                        | [d22ff33b0e](https://linux-hardware.org/?probe=d22ff33b0e) | Apr 08, 2022 |
| Gigabyte      | Z77M-D3H-MVP                | [8ee23e0e96](https://linux-hardware.org/?probe=8ee23e0e96) | Apr 08, 2022 |
| Biostar       | N68S3B                      | [9410ef1116](https://linux-hardware.org/?probe=9410ef1116) | Apr 07, 2022 |
| ASRock        | Z87 Extreme6                | [7d74be6897](https://linux-hardware.org/?probe=7d74be6897) | Apr 07, 2022 |
| HP            | 18E7                        | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS M                | [ff329f98b5](https://linux-hardware.org/?probe=ff329f98b5) | Apr 07, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [111167cacb](https://linux-hardware.org/?probe=111167cacb) | Apr 07, 2022 |
| Acer          | Aspire XC-605               | [201896f70b](https://linux-hardware.org/?probe=201896f70b) | Apr 06, 2022 |
| ASUSTek       | A88XM-A                     | [0f8ce13fb9](https://linux-hardware.org/?probe=0f8ce13fb9) | Apr 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [55568ec828](https://linux-hardware.org/?probe=55568ec828) | Apr 06, 2022 |
| ASRock        | FM2A78M-ITX+                | [63799d0adb](https://linux-hardware.org/?probe=63799d0adb) | Apr 06, 2022 |
| MSI           | Z97 PC Mate                 | [0e99e2c6cb](https://linux-hardware.org/?probe=0e99e2c6cb) | Apr 05, 2022 |
| ASUSTek       | VM62                        | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| Gigabyte      | H410M H V3                  | [afc10b77f7](https://linux-hardware.org/?probe=afc10b77f7) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [e7083be036](https://linux-hardware.org/?probe=e7083be036) | Apr 04, 2022 |
| Foxconn       | 2A8Ch                       | [6354cfe078](https://linux-hardware.org/?probe=6354cfe078) | Apr 04, 2022 |
| Gigabyte      | H55M-S2HP                   | [5079856030](https://linux-hardware.org/?probe=5079856030) | Apr 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e12e7fdd89](https://linux-hardware.org/?probe=e12e7fdd89) | Apr 04, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f067a2d929](https://linux-hardware.org/?probe=f067a2d929) | Apr 04, 2022 |
| ASUSTek       | H61M-D                      | [b9c2af0976](https://linux-hardware.org/?probe=b9c2af0976) | Apr 03, 2022 |
| EPoX Compu... | NF550/570 DDR2: AF550/57... | [2ad5eecadc](https://linux-hardware.org/?probe=2ad5eecadc) | Apr 03, 2022 |
| HP            | 1905                        | [6a3aaab7b9](https://linux-hardware.org/?probe=6a3aaab7b9) | Apr 03, 2022 |
| Gigabyte      | P35C-DS3R                   | [e8ed38bd3d](https://linux-hardware.org/?probe=e8ed38bd3d) | Apr 03, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [01c14c16ca](https://linux-hardware.org/?probe=01c14c16ca) | Apr 03, 2022 |
| Intel         | DH61WW AAG23116-204         | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [9919bf1e95](https://linux-hardware.org/?probe=9919bf1e95) | Apr 02, 2022 |
| Acer          | Aspire M1920                | [00d3df045a](https://linux-hardware.org/?probe=00d3df045a) | Apr 02, 2022 |
| Gigabyte      | H61M-S1                     | [4a26394306](https://linux-hardware.org/?probe=4a26394306) | Apr 02, 2022 |
| Dell          | 09KPNV A00                  | [fad7c9dda0](https://linux-hardware.org/?probe=fad7c9dda0) | Apr 02, 2022 |
| Gigabyte      | H97M-D3H                    | [72d527b649](https://linux-hardware.org/?probe=72d527b649) | Apr 02, 2022 |
| Intel         | H61                         | [47b28b972b](https://linux-hardware.org/?probe=47b28b972b) | Apr 01, 2022 |
| Intel         | DG45ID AAE27729-310         | [4a15651672](https://linux-hardware.org/?probe=4a15651672) | Apr 01, 2022 |
| ASUSTek       | P8H61-M PRO                 | [a30091eb45](https://linux-hardware.org/?probe=a30091eb45) | Mar 31, 2022 |
| Gigabyte      | GA-E6010N                   | [0ab26a135d](https://linux-hardware.org/?probe=0ab26a135d) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [abacf8ed50](https://linux-hardware.org/?probe=abacf8ed50) | Mar 30, 2022 |
| MSI           | MS-7388                     | [d5eabb8266](https://linux-hardware.org/?probe=d5eabb8266) | Mar 30, 2022 |
| Pegatron      | SM 3322                     | [5f56bb615a](https://linux-hardware.org/?probe=5f56bb615a) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| Pegatron      | IPMSB-GS                    | [57ed5ec512](https://linux-hardware.org/?probe=57ed5ec512) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| Dell          | 07N90W A02                  | [4fd59735d6](https://linux-hardware.org/?probe=4fd59735d6) | Mar 30, 2022 |
| Dell          | 0FR6WH A01                  | [3ebf09bc41](https://linux-hardware.org/?probe=3ebf09bc41) | Mar 30, 2022 |
| ASUSTek       | AM1M-A                      | [29e10859da](https://linux-hardware.org/?probe=29e10859da) | Mar 29, 2022 |
| Lenovo        | ThinkCentre M81 5049E7F     | [cfb0af9c1b](https://linux-hardware.org/?probe=cfb0af9c1b) | Mar 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [1c58a58ead](https://linux-hardware.org/?probe=1c58a58ead) | Mar 29, 2022 |
| ASUSTek       | PRIME B250M-K               | [2812792752](https://linux-hardware.org/?probe=2812792752) | Mar 28, 2022 |
| Intel         | DH61BF AAG81311-101         | [126de118c4](https://linux-hardware.org/?probe=126de118c4) | Mar 28, 2022 |
| Intel         | D2500HN AAG34776-402        | [990923b5a7](https://linux-hardware.org/?probe=990923b5a7) | Mar 28, 2022 |
| ASRock        | B560M Steel Legend          | [8caaa96b19](https://linux-hardware.org/?probe=8caaa96b19) | Mar 28, 2022 |
| Lenovo        | 0C48431 PRO                 | [5376a37772](https://linux-hardware.org/?probe=5376a37772) | Mar 28, 2022 |
| ASUSTek       | H97M-PLUS                   | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| Acer          | FMP55                       | [3464cd398f](https://linux-hardware.org/?probe=3464cd398f) | Mar 28, 2022 |
| Gigabyte      | A520M S2H                   | [eb0a725911](https://linux-hardware.org/?probe=eb0a725911) | Mar 28, 2022 |
| Gigabyte      | EP31-DS3L                   | [7a4dfc156e](https://linux-hardware.org/?probe=7a4dfc156e) | Mar 28, 2022 |
| ASUSTek       | AM1M-A                      | [2f7bece339](https://linux-hardware.org/?probe=2f7bece339) | Mar 27, 2022 |
| ASUSTek       | P7H55                       | [12a9db8849](https://linux-hardware.org/?probe=12a9db8849) | Mar 27, 2022 |
| Intel         | D945GCCR AAD78647-300       | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| Koloe         | X58                         | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| MSI           | MS-B1711                    | [29b3da3fb7](https://linux-hardware.org/?probe=29b3da3fb7) | Mar 27, 2022 |
| ASUSTek       | H81M-C/BR                   | [4d07e31cee](https://linux-hardware.org/?probe=4d07e31cee) | Mar 27, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b1645fed59](https://linux-hardware.org/?probe=b1645fed59) | Mar 26, 2022 |
| Biostar       | H81MLV3                     | [140139f958](https://linux-hardware.org/?probe=140139f958) | Mar 26, 2022 |
| ASRock        | 970 Pro3                    | [1b877e6f7a](https://linux-hardware.org/?probe=1b877e6f7a) | Mar 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003       | 1735     | 96.82%  |
| 5.16.13-desktop-1omv4003      | 48       | 2.68%   |
| 5.17.1-desktop-2omv4050       | 2        | 0.11%   |
| 5.16.5-desktop-2omv4003       | 2        | 0.11%   |
| 5.16.3-desktop-2omv4050       | 2        | 0.11%   |
| 5.17.7-desktop-1omv4090       | 1        | 0.06%   |
| 5.16.7-desktop-clang-1omv4003 | 1        | 0.06%   |
| 5.10.14-desktop-1omv4002      | 1        | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.7  | 1736     | 96.88%  |
| 5.16.13 | 48       | 2.68%   |
| 5.17.1  | 2        | 0.11%   |
| 5.16.5  | 2        | 0.11%   |
| 5.16.3  | 2        | 0.11%   |
| 5.17.7  | 1        | 0.06%   |
| 5.10.14 | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 1788     | 99.78%  |
| 5.17    | 3        | 0.17%   |
| 5.10    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1792     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 1787     | 99.72%  |
| Unknown | 3        | 0.17%   |
| LXQt    | 2        | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1773     | 98.94%  |
| Wayland | 19       | 1.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 1792     | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 1006     | 56.14%  |
| de_DE | 170      | 9.49%   |
| ru_RU | 122      | 6.81%   |
| pt_BR | 73       | 4.07%   |
| fr_FR | 73       | 4.07%   |
| pl_PL | 45       | 2.51%   |
| it_IT | 38       | 2.12%   |
| es_ES | 36       | 2.01%   |
| en_GB | 29       | 1.62%   |
| es_AR | 25       | 1.4%    |
| de_AT | 17       | 0.95%   |
| en_IN | 16       | 0.89%   |
| cs_CZ | 15       | 0.84%   |
| en_CA | 10       | 0.56%   |
| tr_TR | 9        | 0.5%    |
| hu_HU | 9        | 0.5%    |
| es_MX | 9        | 0.5%    |
| en_AU | 9        | 0.5%    |
| fr_CA | 7        | 0.39%   |
| de_CH | 6        | 0.33%   |
| ru_UA | 5        | 0.28%   |
| pt_PT | 5        | 0.28%   |
| nl_NL | 5        | 0.28%   |
| es_VE | 5        | 0.28%   |
| es_CO | 5        | 0.28%   |
| es_CL | 4        | 0.22%   |
| da_DK | 4        | 0.22%   |
| nb_NO | 3        | 0.17%   |
| fr_BE | 3        | 0.17%   |
| es_PE | 3        | 0.17%   |
| es_CR | 3        | 0.17%   |
| uk_UA | 2        | 0.11%   |
| es_UY | 2        | 0.11%   |
| es_SV | 2        | 0.11%   |
| en_ZA | 2        | 0.11%   |
| en_IL | 2        | 0.11%   |
| en_HK | 2        | 0.11%   |
| ar_SA | 2        | 0.11%   |
| ro_RO | 1        | 0.06%   |
| nl_BE | 1        | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 980      | 54.69%  |
| EFI  | 812      | 45.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 1550     | 86.5%   |
| Ext4     | 237      | 13.23%  |
| F2fs     | 2        | 0.11%   |
| Xfs      | 1        | 0.06%   |
| Reiserfs | 1        | 0.06%   |
| Btrfs    | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1099     | 61.33%  |
| MBR     | 677      | 37.78%  |
| Unknown | 16       | 0.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1122     | 62.61%  |
| No        | 670      | 37.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1020     | 56.92%  |
| No        | 772      | 43.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 412      | 22.99%  |
| Gigabyte Technology | 335      | 18.69%  |
| MSI                 | 200      | 11.16%  |
| ASRock              | 167      | 9.32%   |
| Hewlett-Packard     | 141      | 7.87%   |
| Dell                | 135      | 7.53%   |
| Lenovo              | 74       | 4.13%   |
| Intel               | 59       | 3.29%   |
| Acer                | 48       | 2.68%   |
| Fujitsu             | 25       | 1.4%    |
| Foxconn             | 24       | 1.34%   |
| Biostar             | 24       | 1.34%   |
| Pegatron            | 17       | 0.95%   |
| Medion              | 12       | 0.67%   |
| ECS                 | 12       | 0.67%   |
| Unknown             | 10       | 0.56%   |
| Positivo            | 9        | 0.5%    |
| Shuttle             | 6        | 0.33%   |
| AZW                 | 6        | 0.33%   |
| Fujitsu Siemens     | 5        | 0.28%   |
| BESSTAR Tech        | 5        | 0.28%   |
| Alienware           | 5        | 0.28%   |
| Packard Bell        | 4        | 0.22%   |
| MACHINIST           | 4        | 0.22%   |
| Wistron             | 3        | 0.17%   |
| PCWare              | 3        | 0.17%   |
| OEM                 | 3        | 0.17%   |
| Apple               | 3        | 0.17%   |
| Supermicro          | 2        | 0.11%   |
| Login Informatica   | 2        | 0.11%   |
| Itautec             | 2        | 0.11%   |
| Huanan              | 2        | 0.11%   |
| Gateway             | 2        | 0.11%   |
| VS Company          | 1        | 0.06%   |
| Vorke               | 1        | 0.06%   |
| TPV-INVENTA         | 1        | 0.06%   |
| Semp Toshiba        | 1        | 0.06%   |
| Proline             | 1        | 0.06%   |
| Philco              | 1        | 0.06%   |
| PCChips             | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 36       | 2.01%   |
| Gigabyte H410M H V3              | 27       | 1.51%   |
| ASUS SABERTOOTH Z77              | 19       | 1.06%   |
| Dell OptiPlex 7010               | 14       | 0.78%   |
| Unknown                          | 10       | 0.56%   |
| Intel H61                        | 9        | 0.5%    |
| Dell OptiPlex 780                | 9        | 0.5%    |
| ASUS PRIME B450M-A II            | 8        | 0.45%   |
| Dell OptiPlex 790                | 7        | 0.39%   |
| MSI MS-7C91                      | 6        | 0.33%   |
| MSI MS-7C37                      | 6        | 0.33%   |
| MSI MS-7A38                      | 6        | 0.33%   |
| MSI MS-7721                      | 6        | 0.33%   |
| HP EliteDesk 800 G1 SFF          | 6        | 0.33%   |
| HP Compaq Pro 6300 SFF           | 6        | 0.33%   |
| Gigabyte 970A-DS3P               | 6        | 0.33%   |
| Dell OptiPlex 9020               | 6        | 0.33%   |
| Dell OptiPlex 7020               | 6        | 0.33%   |
| ASUS ROG STRIX B550-F GAMING     | 6        | 0.33%   |
| MSI MS-7C84                      | 5        | 0.28%   |
| MSI MS-7C02                      | 5        | 0.28%   |
| MSI MS-7B79                      | 5        | 0.28%   |
| HP ProDesk 600 G1 SFF            | 5        | 0.28%   |
| HP Compaq 8100 Elite CMT PC      | 5        | 0.28%   |
| Gigabyte B550M AORUS PRO-P       | 5        | 0.28%   |
| Gigabyte B450M DS3H              | 5        | 0.28%   |
| Gigabyte A320M-S2H               | 5        | 0.28%   |
| Dell Precision WorkStation T3500 | 5        | 0.28%   |
| Dell OptiPlex 380                | 5        | 0.28%   |
| Dell OptiPlex 3020               | 5        | 0.28%   |
| ASUS TUF Gaming B550M-PLUS       | 5        | 0.28%   |
| ASUS TUF Gaming B550-PLUS        | 5        | 0.28%   |
| ASUS PRIME B450-PLUS             | 5        | 0.28%   |
| ASUS PRIME A320M-K               | 5        | 0.28%   |
| ASUS M5A78L-M/USB3               | 5        | 0.28%   |
| ASRock N68C-S UCC                | 5        | 0.28%   |
| ASRock B450M Steel Legend        | 5        | 0.28%   |
| ASRock A320M-HDV R4.0            | 5        | 0.28%   |
| MSI MS-7C56                      | 4        | 0.22%   |
| MSI MS-7B98                      | 4        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 92       | 5.13%   |
| ASUS PRIME             | 77       | 4.3%    |
| Lenovo ThinkCentre     | 51       | 2.85%   |
| HP Compaq              | 50       | 2.79%   |
| ASUS All               | 36       | 2.01%   |
| Acer Aspire            | 34       | 1.9%    |
| Gigabyte H410M         | 31       | 1.73%   |
| ASUS TUF               | 31       | 1.73%   |
| ASUS ROG               | 31       | 1.73%   |
| ASUS SABERTOOTH        | 25       | 1.4%    |
| HP EliteDesk           | 23       | 1.28%   |
| HP ProDesk             | 22       | 1.23%   |
| Fujitsu ESPRIMO        | 21       | 1.17%   |
| ASUS M5A78L-M          | 16       | 0.89%   |
| Dell Precision         | 15       | 0.84%   |
| Gigabyte B450M         | 12       | 0.67%   |
| Dell Inspiron          | 12       | 0.67%   |
| Intel H61              | 10       | 0.56%   |
| Gigabyte X570          | 10       | 0.56%   |
| ASUS M5A97             | 10       | 0.56%   |
| ASRock B450M           | 10       | 0.56%   |
| Unknown                | 10       | 0.56%   |
| HP Pavilion            | 9        | 0.5%    |
| Gigabyte Z390          | 9        | 0.5%    |
| Gigabyte B450          | 9        | 0.5%    |
| Acer Veriton           | 9        | 0.5%    |
| Gigabyte B550M         | 8        | 0.45%   |
| Dell Vostro            | 8        | 0.45%   |
| ASRock A320M-HDV       | 8        | 0.45%   |
| Lenovo IdeaCentre      | 7        | 0.39%   |
| Gigabyte GA-78LMT-USB3 | 7        | 0.39%   |
| ASUS P8H61-M           | 7        | 0.39%   |
| MSI MS-7C91            | 6        | 0.33%   |
| MSI MS-7C37            | 6        | 0.33%   |
| MSI MS-7A38            | 6        | 0.33%   |
| MSI MS-7721            | 6        | 0.33%   |
| Gigabyte 970A-DS3P     | 6        | 0.33%   |
| Dell XPS               | 6        | 0.33%   |
| ASUS P8B75-M           | 6        | 0.33%   |
| ASRock B450            | 6        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 193      | 10.77%  |
| 2013 | 166      | 9.26%   |
| 2018 | 161      | 8.98%   |
| 2011 | 143      | 7.98%   |
| 2020 | 130      | 7.25%   |
| 2021 | 129      | 7.2%    |
| 2010 | 128      | 7.14%   |
| 2014 | 123      | 6.86%   |
| 2019 | 109      | 6.08%   |
| 2009 | 96       | 5.36%   |
| 2008 | 83       | 4.63%   |
| 2017 | 79       | 4.41%   |
| 2016 | 72       | 4.02%   |
| 2015 | 67       | 3.74%   |
| 2007 | 55       | 3.07%   |
| 2006 | 40       | 2.23%   |
| 2022 | 14       | 0.78%   |
| 2005 | 4        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1792     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1792     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1792     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 410      | 22.88%  |
| 16.01-24.0      | 376      | 20.98%  |
| 4.01-8.0        | 360      | 20.09%  |
| 3.01-4.0        | 320      | 17.86%  |
| 32.01-64.0      | 182      | 10.16%  |
| 1.01-2.0        | 49       | 2.73%   |
| 64.01-256.0     | 38       | 2.12%   |
| 24.01-32.0      | 36       | 2.01%   |
| 2.01-3.0        | 16       | 0.89%   |
| 0.51-1.0        | 3        | 0.17%   |
| More than 256.0 | 2        | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 1209     | 67.47%  |
| 0.51-1.0  | 385      | 21.48%  |
| 2.01-3.0  | 125      | 6.98%   |
| 0.01-0.5  | 39       | 2.18%   |
| 3.01-4.0  | 19       | 1.06%   |
| 4.01-8.0  | 10       | 0.56%   |
| 8.01-16.0 | 5        | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 750      | 41.85%  |
| 2      | 494      | 27.57%  |
| 3      | 249      | 13.9%   |
| 4      | 145      | 8.09%   |
| 5      | 63       | 3.52%   |
| 0      | 42       | 2.34%   |
| 6      | 25       | 1.4%    |
| 7      | 9        | 0.5%    |
| 8      | 6        | 0.33%   |
| 9      | 4        | 0.22%   |
| 12     | 2        | 0.11%   |
| 15     | 1        | 0.06%   |
| 11     | 1        | 0.06%   |
| 10     | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1019     | 56.86%  |
| No        | 773      | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1776     | 99.11%  |
| No        | 16       | 0.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1174     | 65.51%  |
| Yes       | 618      | 34.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1398     | 78.01%  |
| Yes       | 394      | 21.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 233      | 13%     |
| USA          | 226      | 12.61%  |
| Russia       | 144      | 8.04%   |
| Brazil       | 120      | 6.7%    |
| France       | 111      | 6.19%   |
| Poland       | 91       | 5.08%   |
| Italy        | 66       | 3.68%   |
| Spain        | 48       | 2.68%   |
| Canada       | 48       | 2.68%   |
| UK           | 46       | 2.57%   |
| Australia    | 43       | 2.4%    |
| India        | 41       | 2.29%   |
| Argentina    | 28       | 1.56%   |
| Ukraine      | 26       | 1.45%   |
| Japan        | 26       | 1.45%   |
| Austria      | 26       | 1.45%   |
| Netherlands  | 24       | 1.34%   |
| Mexico       | 24       | 1.34%   |
| Czechia      | 24       | 1.34%   |
| Sweden       | 17       | 0.95%   |
| Turkey       | 16       | 0.89%   |
| Indonesia    | 16       | 0.89%   |
| Hungary      | 16       | 0.89%   |
| Switzerland  | 14       | 0.78%   |
| Serbia       | 14       | 0.78%   |
| Romania      | 13       | 0.73%   |
| Portugal     | 12       | 0.67%   |
| Egypt        | 12       | 0.67%   |
| Belgium      | 12       | 0.67%   |
| Israel       | 11       | 0.61%   |
| Uruguay      | 10       | 0.56%   |
| Venezuela    | 9        | 0.5%    |
| Finland      | 9        | 0.5%    |
| Algeria      | 9        | 0.5%    |
| Slovakia     | 8        | 0.45%   |
| Peru         | 8        | 0.45%   |
| Greece       | 8        | 0.45%   |
| Colombia     | 8        | 0.45%   |
| China        | 8        | 0.45%   |
| South Africa | 7        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Moscow               | 26       | 1.45%   |
| Gonikoppal           | 22       | 1.23%   |
| Strzyzow             | 17       | 0.95%   |
| Sao Paulo            | 15       | 0.84%   |
| Berlin               | 14       | 0.78%   |
| Vienna               | 13       | 0.73%   |
| St Petersburg        | 12       | 0.67%   |
| Warsaw               | 11       | 0.61%   |
| Sydney               | 10       | 0.56%   |
| Paris                | 9        | 0.5%    |
| Milan                | 9        | 0.5%    |
| Munich               | 8        | 0.45%   |
| Istanbul             | 8        | 0.45%   |
| Cairo                | 8        | 0.45%   |
| Brisbane             | 8        | 0.45%   |
| Rome                 | 7        | 0.39%   |
| Rio de Janeiro       | 7        | 0.39%   |
| Montevideo           | 7        | 0.39%   |
| Mexico City          | 7        | 0.39%   |
| Lima                 | 7        | 0.39%   |
| Jakarta              | 7        | 0.39%   |
| Buenos Aires         | 7        | 0.39%   |
| Belgrade             | 7        | 0.39%   |
| Yekaterinburg        | 6        | 0.33%   |
| Kyiv                 | 6        | 0.33%   |
| Hamburg              | 6        | 0.33%   |
| Zagreb               | 5        | 0.28%   |
| Wroclaw              | 5        | 0.28%   |
| Tel Aviv             | 5        | 0.28%   |
| San Marcos           | 5        | 0.28%   |
| San José            | 5        | 0.28%   |
| Rochester            | 5        | 0.28%   |
| Nizhniy Novgorod     | 5        | 0.28%   |
| Niterói             | 5        | 0.28%   |
| Marseille            | 5        | 0.28%   |
| Lexington            | 5        | 0.28%   |
| Duque de Caxias      | 5        | 0.28%   |
| Budapest             | 5        | 0.28%   |
| Vélizy-Villacoublay | 4        | 0.22%   |
| Skopje               | 4        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 602      | 779    | 19.51%  |
| Seagate             | 561      | 718    | 18.18%  |
| Samsung Electronics | 423      | 539    | 13.71%  |
| Kingston            | 189      | 208    | 6.13%   |
| Toshiba             | 168      | 184    | 5.45%   |
| Crucial             | 161      | 193    | 5.22%   |
| SanDisk             | 132      | 154    | 4.28%   |
| Hitachi             | 116      | 123    | 3.76%   |
| A-DATA Technology   | 91       | 97     | 2.95%   |
| China               | 38       | 44     | 1.23%   |
| Unknown             | 31       | 40     | 1%      |
| Maxtor              | 28       | 32     | 0.91%   |
| HGST                | 28       | 33     | 0.91%   |
| Intel               | 26       | 27     | 0.84%   |
| SPCC                | 23       | 26     | 0.75%   |
| PNY                 | 22       | 29     | 0.71%   |
| Patriot             | 21       | 23     | 0.68%   |
| GOODRAM             | 19       | 21     | 0.62%   |
| Gigabyte Technology | 19       | 19     | 0.62%   |
| OCZ                 | 17       | 17     | 0.55%   |
| Apacer              | 17       | 18     | 0.55%   |
| Unknown             | 17       | 17     | 0.55%   |
| Intenso             | 16       | 16     | 0.52%   |
| Corsair             | 16       | 17     | 0.52%   |
| Phison              | 14       | 16     | 0.45%   |
| Netac               | 14       | 15     | 0.45%   |
| SK hynix            | 13       | 13     | 0.42%   |
| JMicron Technology  | 13       | 14     | 0.42%   |
| Hewlett-Packard     | 13       | 16     | 0.42%   |
| ASMT                | 13       | 15     | 0.42%   |
| Team                | 12       | 12     | 0.39%   |
| Transcend           | 11       | 13     | 0.36%   |
| Micron Technology   | 11       | 11     | 0.36%   |
| XPG                 | 9        | 12     | 0.29%   |
| KingSpec            | 8        | 8      | 0.26%   |
| Silicon Motion      | 7        | 8      | 0.23%   |
| LITEON              | 7        | 7      | 0.23%   |
| KIOXIA-EXCERIA      | 7        | 7      | 0.23%   |
| KingFast            | 7        | 7      | 0.23%   |
| Apple               | 7        | 7      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 60       | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB   | 50       | 1.4%    |
| Kingston SA400S37240G 240GB SSD  | 40       | 1.12%   |
| WDC WD10EZEX-08WN4A0 1TB         | 33       | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB   | 32       | 0.9%    |
| Crucial CT500MX500SSD1 500GB     | 30       | 0.84%   |
| Toshiba DT01ACA100 1TB           | 29       | 0.81%   |
| Samsung SSD 860 EVO 250GB        | 29       | 0.81%   |
| Kingston SA400S37120G 120GB SSD  | 27       | 0.76%   |
| Toshiba DT01ACA050 500GB         | 26       | 0.73%   |
| Samsung SSD 860 EVO 500GB        | 26       | 0.73%   |
| Samsung SSD 850 EVO 250GB        | 26       | 0.73%   |
| Kingston SA400S37480G 480GB SSD  | 25       | 0.7%    |
| Seagate ST1000DM003-1ER162 1TB   | 23       | 0.65%   |
| A-DATA SU750 256GB SSD           | 22       | 0.62%   |
| Kingston SV300S37A120G 120GB SSD | 20       | 0.56%   |
| Crucial CT1000MX500SSD1 1TB      | 20       | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 18       | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB   | 18       | 0.51%   |
| Crucial CT480BX500SSD1 480GB     | 18       | 0.51%   |
| Crucial CT240BX500SSD1 240GB     | 18       | 0.51%   |
| Unknown SD/MMC/MS PRO 8GB        | 17       | 0.48%   |
| Toshiba HDWD110 1TB              | 17       | 0.48%   |
| Seagate ST1000DM003-1SB102 1TB   | 17       | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB   | 17       | 0.48%   |
| Unknown                          | 17       | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB   | 16       | 0.45%   |
| Seagate ST3500418AS 500GB        | 15       | 0.42%   |
| Seagate ST3500413AS 500GB        | 15       | 0.42%   |
| Samsung SSD 850 EVO 500GB        | 15       | 0.42%   |
| SanDisk SSD PLUS 240GB           | 14       | 0.39%   |
| SanDisk SDSSDA240G 240GB         | 14       | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB     | 14       | 0.39%   |
| Samsung HD502HJ 500GB            | 14       | 0.39%   |
| Samsung HD322HJ 320GB            | 14       | 0.39%   |
| Seagate ST31000528AS 1TB         | 13       | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB         | 12       | 0.34%   |
| Seagate Expansion 1TB            | 12       | 0.34%   |
| Samsung SSD 860 EVO 1TB          | 12       | 0.34%   |
| Samsung HD103SJ 1TB              | 12       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 552      | 701    | 34.39%  |
| WDC                 | 526      | 651    | 32.77%  |
| Toshiba             | 156      | 172    | 9.72%   |
| Samsung Electronics | 138      | 157    | 8.6%    |
| Hitachi             | 116      | 123    | 7.23%   |
| HGST                | 28       | 33     | 1.74%   |
| Maxtor              | 27       | 31     | 1.68%   |
| Unknown             | 18       | 18     | 1.12%   |
| Apple               | 7        | 7      | 0.44%   |
| Fujitsu             | 5        | 5      | 0.31%   |
| ASMT                | 5        | 7      | 0.31%   |
| WD MediaMax         | 3        | 4      | 0.19%   |
| Intenso             | 3        | 3      | 0.19%   |
| IBM/Hitachi         | 3        | 3      | 0.19%   |
| Magnetic Data       | 2        | 2      | 0.12%   |
| JMicron Technology  | 2        | 2      | 0.12%   |
| HPE                 | 2        | 2      | 0.12%   |
| Hewlett-Packard     | 2        | 2      | 0.12%   |
| Unknown             | 2        | 2      | 0.12%   |
| RSH-339             | 1        | 1      | 0.06%   |
| Quantum             | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 1      | 0.06%   |
| Initio              | 1        | 1      | 0.06%   |
| Inateck             | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| Config              | 1        | 1      | 0.06%   |
| China               | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 218      | 253    | 18.49%  |
| Kingston            | 161      | 174    | 13.66%  |
| Crucial             | 135      | 159    | 11.45%  |
| SanDisk             | 122      | 140    | 10.35%  |
| A-DATA Technology   | 74       | 74     | 6.28%   |
| WDC                 | 72       | 82     | 6.11%   |
| China               | 37       | 43     | 3.14%   |
| PNY                 | 18       | 23     | 1.53%   |
| SPCC                | 17       | 19     | 1.44%   |
| Patriot             | 17       | 19     | 1.44%   |
| OCZ                 | 17       | 17     | 1.44%   |
| Intel               | 17       | 18     | 1.44%   |
| GOODRAM             | 17       | 17     | 1.44%   |
| Apacer              | 16       | 16     | 1.36%   |
| Unknown             | 15       | 15     | 1.27%   |
| Team                | 12       | 12     | 1.02%   |
| Intenso             | 12       | 12     | 1.02%   |
| Gigabyte Technology | 12       | 12     | 1.02%   |
| Netac               | 11       | 12     | 0.93%   |
| Micron Technology   | 11       | 11     | 0.93%   |
| Transcend           | 9        | 10     | 0.76%   |
| Toshiba             | 9        | 9      | 0.76%   |
| KingSpec            | 8        | 8      | 0.68%   |
| JMicron Technology  | 8        | 9      | 0.68%   |
| Hewlett-Packard     | 8        | 10     | 0.68%   |
| ASMT                | 8        | 8      | 0.68%   |
| KingFast            | 7        | 7      | 0.59%   |
| LITEON              | 6        | 6      | 0.51%   |
| KIOXIA-EXCERIA      | 5        | 5      | 0.42%   |
| Corsair             | 5        | 5      | 0.42%   |
| SK hynix            | 4        | 4      | 0.34%   |
| Seagate             | 4        | 4      | 0.34%   |
| LITEONIT            | 4        | 4      | 0.34%   |
| KingDian            | 4        | 4      | 0.34%   |
| Colorful            | 4        | 4      | 0.34%   |
| TO Exter            | 3        | 3      | 0.25%   |
| Leven               | 3        | 3      | 0.25%   |
| Zheino              | 2        | 3      | 0.17%   |
| XrayDisk            | 2        | 2      | 0.17%   |
| USB3.0              | 2        | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1253     | 1933   | 49.23%  |
| SSD     | 930      | 1301   | 36.54%  |
| NVMe    | 328      | 418    | 12.89%  |
| Unknown | 28       | 39     | 1.1%    |
| MMC     | 6        | 7      | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1675     | 3111   | 78.05%  |
| NVMe | 324      | 410    | 15.1%   |
| SAS  | 141      | 170    | 6.57%   |
| MMC  | 6        | 7      | 0.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1347     | 1957   | 57.47%  |
| 0.51-1.0   | 640      | 840    | 27.3%   |
| 1.01-2.0   | 205      | 241    | 8.75%   |
| 2.01-3.0   | 54       | 62     | 2.3%    |
| 3.01-4.0   | 45       | 63     | 1.92%   |
| 4.01-10.0  | 44       | 62     | 1.88%   |
| 10.01-20.0 | 9        | 9      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 982      | 54.8%   |
| Unknown        | 242      | 13.5%   |
| 101-250        | 209      | 11.66%  |
| 251-500        | 127      | 7.09%   |
| 21-50          | 69       | 3.85%   |
| 501-1000       | 67       | 3.74%   |
| 51-100         | 52       | 2.9%    |
| 1001-2000      | 26       | 1.45%   |
| More than 3000 | 11       | 0.61%   |
| 2001-3000      | 7        | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1408     | 78.57%  |
| Unknown        | 242      | 13.5%   |
| 101-250        | 39       | 2.18%   |
| 21-50          | 26       | 1.45%   |
| 51-100         | 26       | 1.45%   |
| 251-500        | 19       | 1.06%   |
| 501-1000       | 19       | 1.06%   |
| 1001-2000      | 9        | 0.5%    |
| More than 3000 | 2        | 0.11%   |
| 2001-3000      | 2        | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 26       | 27     | 3.84%   |
| Samsung Electronics HD322HJ 320GB | 9        | 9      | 1.33%   |
| Seagate ST3500413AS 500GB         | 8        | 8      | 1.18%   |
| Seagate ST1000DM003-9YN162 1TB    | 8        | 8      | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB    | 7        | 7      | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 6        | 6      | 0.89%   |
| Kingston SV300S37A120G 120GB SSD  | 6        | 6      | 0.89%   |
| WDC WD5000AADS-00S9B0 500GB       | 5        | 5      | 0.74%   |
| Seagate ST9500325AS 500GB         | 5        | 5      | 0.74%   |
| Seagate ST3500418AS 500GB         | 5        | 5      | 0.74%   |
| Seagate ST3320418AS 320GB         | 5        | 5      | 0.74%   |
| Seagate ST1000DM003-1SB102 1TB    | 5        | 5      | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB    | 5        | 5      | 0.74%   |
| Samsung Electronics HD502HJ 500GB | 5        | 5      | 0.74%   |
| Hitachi HDS721050CLA362 500GB     | 5        | 5      | 0.74%   |
| GOODRAM SSD 120GB                 | 5        | 5      | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 4        | 4      | 0.59%   |
| WDC WD5000AAKS-00V1A0 500GB       | 4        | 4      | 0.59%   |
| WDC WD3200AAJS-00L7A0 320GB       | 4        | 4      | 0.59%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 4        | 4      | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 4      | 0.59%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 5      | 0.59%   |
| WDC WD10EALX-009BA0 1TB           | 4        | 4      | 0.59%   |
| Toshiba DT01ACA100 1TB            | 4        | 4      | 0.59%   |
| Toshiba DT01ACA050 500GB          | 4        | 4      | 0.59%   |
| Seagate ST92505610AS 250GB        | 4        | 4      | 0.59%   |
| Seagate ST380013AS 80GB           | 4        | 4      | 0.59%   |
| Seagate ST31000528AS 1TB          | 4        | 4      | 0.59%   |
| Seagate ST31000524AS 1TB          | 4        | 4      | 0.59%   |
| Seagate ST250DM000-1BD141 250GB   | 4        | 4      | 0.59%   |
| Seagate ST2000DM001-1CH164 2TB    | 4        | 4      | 0.59%   |
| SanDisk SSD PLUS 240GB            | 4        | 4      | 0.59%   |
| Samsung Electronics SP2504C 250GB | 4        | 4      | 0.59%   |
| Samsung Electronics HD753LJ 752GB | 4        | 4      | 0.59%   |
| Samsung Electronics HD502HI 500GB | 4        | 4      | 0.59%   |
| Samsung Electronics HD161HJ 160GB | 4        | 4      | 0.59%   |
| Samsung Electronics HD160JJ 160GB | 4        | 4      | 0.59%   |
| Hitachi HDS721010DLE630 1TB       | 4        | 4      | 0.59%   |
| HGST HTS545050A7E680 500GB        | 4        | 4      | 0.59%   |
| ASMT 2135 120GB SSD               | 4        | 4      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 193      | 210    | 29.97%  |
| WDC                 | 176      | 194    | 27.33%  |
| Samsung Electronics | 75       | 79     | 11.65%  |
| Hitachi             | 50       | 52     | 7.76%   |
| Toshiba             | 22       | 22     | 3.42%   |
| Maxtor              | 17       | 17     | 2.64%   |
| Kingston            | 17       | 17     | 2.64%   |
| SanDisk             | 15       | 15     | 2.33%   |
| HGST                | 11       | 12     | 1.71%   |
| Crucial             | 8        | 9      | 1.24%   |
| A-DATA Technology   | 7        | 7      | 1.09%   |
| Intel               | 6        | 6      | 0.93%   |
| GOODRAM             | 5        | 5      | 0.78%   |
| ASMT                | 4        | 4      | 0.62%   |
| OCZ                 | 3        | 3      | 0.47%   |
| Micron Technology   | 3        | 3      | 0.47%   |
| IBM/Hitachi         | 3        | 3      | 0.47%   |
| SPCC                | 2        | 2      | 0.31%   |
| Patriot             | 2        | 2      | 0.31%   |
| Fujitsu             | 2        | 2      | 0.31%   |
| Unknown             | 2        | 2      | 0.31%   |
| WDC WDS2            | 1        | 1      | 0.16%   |
| WD MediaMax         | 1        | 1      | 0.16%   |
| Transcend           | 1        | 1      | 0.16%   |
| TO Exter            | 1        | 1      | 0.16%   |
| TEXTORM             | 1        | 1      | 0.16%   |
| TCSUNBOW            | 1        | 1      | 0.16%   |
| RSH-339             | 1        | 1      | 0.16%   |
| Neo                 | 1        | 1      | 0.16%   |
| LITEONIT            | 1        | 1      | 0.16%   |
| LITEON              | 1        | 1      | 0.16%   |
| KingSpec            | 1        | 1      | 0.16%   |
| Kingmax             | 1        | 1      | 0.16%   |
| KingDian            | 1        | 1      | 0.16%   |
| INNOVATION IT       | 1        | 1      | 0.16%   |
| Initio              | 1        | 1      | 0.16%   |
| HPE                 | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 1      | 0.16%   |
| GLOWAY              | 1        | 1      | 0.16%   |
| ExcelStor           | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 193      | 210    | 35.81%  |
| WDC                 | 167      | 183    | 30.98%  |
| Samsung Electronics | 68       | 72     | 12.62%  |
| Hitachi             | 50       | 52     | 9.28%   |
| Toshiba             | 22       | 22     | 4.08%   |
| Maxtor              | 17       | 17     | 3.15%   |
| HGST                | 11       | 12     | 2.04%   |
| IBM/Hitachi         | 3        | 3      | 0.56%   |
| Fujitsu             | 2        | 2      | 0.37%   |
| WD MediaMax         | 1        | 1      | 0.19%   |
| RSH-339             | 1        | 1      | 0.19%   |
| Initio              | 1        | 1      | 0.19%   |
| HPE                 | 1        | 1      | 0.19%   |
| ExcelStor           | 1        | 1      | 0.19%   |
| Unknown             | 1        | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 474      | 579    | 82.15%  |
| SSD  | 100      | 105    | 17.33%  |
| NVMe | 3        | 3      | 0.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 13.64%  |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 13.64%  |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 4.55%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 4.55%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 4.55%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 4.55%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 4.55%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 4.55%   |
| Seagate ST3250318AS 250GB                        | 1        | 1      | 4.55%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 4.55%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 4.55%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 4.55%   |
| Samsung Electronics HD103UJ 1TB                  | 1        | 1      | 4.55%   |
| Hitachi HTS725050A7E630 500GB                    | 1        | 1      | 4.55%   |
| Hitachi HDS721010DLE630 1TB                      | 1        | 1      | 4.55%   |
| Hitachi HDP725050GLA360 500GB                    | 1        | 1      | 4.55%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1        | 1      | 4.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 7      | 31.82%  |
| Seagate             | 4        | 4      | 18.18%  |
| WDC                 | 3        | 3      | 13.64%  |
| Hitachi             | 3        | 3      | 13.64%  |
| Apple               | 3        | 3      | 13.64%  |
| Toshiba             | 1        | 1      | 4.55%   |
| GOODRAM             | 1        | 1      | 4.55%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1481     | 2833   | 67.53%  |
| Malfunc  | 559      | 687    | 25.49%  |
| Detected | 132      | 156    | 6.02%   |
| Failed   | 21       | 22     | 0.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1183     | 49.52%  |
| AMD                              | 539      | 22.56%  |
| Samsung Electronics              | 112      | 4.69%   |
| JMicron Technology               | 78       | 3.26%   |
| ASMedia Technology               | 68       | 2.85%   |
| Marvell Technology Group         | 63       | 2.64%   |
| Nvidia                           | 59       | 2.47%   |
| SanDisk                          | 53       | 2.22%   |
| Phison Electronics               | 44       | 1.84%   |
| Kingston Technology Company      | 32       | 1.34%   |
| Micron/Crucial Technology        | 30       | 1.26%   |
| Silicon Motion                   | 26       | 1.09%   |
| VIA Technologies                 | 20       | 0.84%   |
| ADATA Technology                 | 17       | 0.71%   |
| Realtek Semiconductor            | 11       | 0.46%   |
| SK hynix                         | 8        | 0.33%   |
| Seagate Technology               | 7        | 0.29%   |
| Integrated Technology Express    | 5        | 0.21%   |
| Broadcom / LSI                   | 5        | 0.21%   |
| Toshiba America Info Systems     | 4        | 0.17%   |
| Lite-On Technology               | 4        | 0.17%   |
| Micron Technology                | 3        | 0.13%   |
| LSI Logic / Symbios Logic        | 3        | 0.13%   |
| Union Memory (Shenzhen)          | 2        | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.08%   |
| KIOXIA                           | 2        | 0.08%   |
| Adaptec                          | 2        | 0.08%   |
| Yangtze Memory Technologies      | 1        | 0.04%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |
| Silicon Image                    | 1        | 0.04%   |
| Shenzhen Longsys Electronics     | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.04%   |
| INNOGRIT                         | 1        | 0.04%   |
| 3ware                            | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 265      | 8.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 167      | 5.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 107      | 3.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 101      | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 98       | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 97       | 3.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 88       | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 84       | 2.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 74       | 2.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 70       | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 69       | 2.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 67       | 2.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 65       | 2.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 63       | 2.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 62       | 2.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 57       | 1.87%   |
| Intel SATA Controller [RAID mode]                                                       | 56       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 56       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 56       | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 54       | 1.77%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 51       | 1.67%   |
| Nvidia MCP61 SATA Controller                                                            | 36       | 1.18%   |
| AMD FCH SATA Controller D                                                               | 36       | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 31       | 1.02%   |
| Nvidia MCP61 IDE                                                                        | 30       | 0.98%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 30       | 0.98%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 29       | 0.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 29       | 0.95%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 28       | 0.92%   |
| AMD FCH IDE Controller                                                                  | 27       | 0.88%   |
| Phison E12 NVMe Controller                                                              | 23       | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 21       | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 21       | 0.69%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 21       | 0.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 20       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 20       | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 19       | 0.62%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 19       | 0.62%   |
| Kingston Company A2000 NVMe SSD                                                         | 18       | 0.59%   |
| JMicron JMB368 IDE controller                                                           | 18       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1367     | 57.8%   |
| IDE  | 576      | 24.36%  |
| NVMe | 321      | 13.57%  |
| RAID | 89       | 3.76%   |
| SAS  | 8        | 0.34%   |
| SCSI | 4        | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1200     | 66.96%  |
| AMD    | 592      | 33.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400 CPU @ 2.90GHz           | 40       | 2.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 30       | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 24       | 1.34%   |
| AMD Ryzen 5 3600 6-Core Processor           | 23       | 1.28%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 22       | 1.23%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 22       | 1.23%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 21       | 1.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 21       | 1.17%   |
| AMD FX-8350 Eight-Core Processor            | 20       | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 19       | 1.06%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 1%      |
| Intel Core i5-4590 CPU @ 3.30GHz            | 17       | 0.95%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 17       | 0.95%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.89%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 16       | 0.89%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 15       | 0.84%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 15       | 0.84%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 14       | 0.78%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 14       | 0.78%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 14       | 0.78%   |
| AMD FX-6300 Six-Core Processor              | 14       | 0.78%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 13       | 0.73%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 13       | 0.73%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 12       | 0.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 12       | 0.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 12       | 0.67%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 12       | 0.67%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11       | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 11       | 0.61%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 11       | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 11       | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 10       | 0.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 10       | 0.56%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 10       | 0.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 10       | 0.56%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 10       | 0.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 10       | 0.56%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 10       | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 381      | 21.26%  |
| Intel Core i3           | 180      | 10.04%  |
| Intel Core i7           | 150      | 8.37%   |
| AMD Ryzen 5             | 118      | 6.58%   |
| Intel Core 2 Duo        | 81       | 4.52%   |
| AMD FX                  | 74       | 4.13%   |
| AMD Ryzen 7             | 70       | 3.91%   |
| Intel Celeron           | 68       | 3.79%   |
| Intel Pentium           | 64       | 3.57%   |
| Intel Xeon              | 63       | 3.52%   |
| Intel Core 2 Quad       | 58       | 3.24%   |
| Intel Pentium Dual-Core | 41       | 2.29%   |
| Other                   | 40       | 2.23%   |
| AMD Ryzen 3             | 35       | 1.95%   |
| AMD A8                  | 30       | 1.67%   |
| AMD Phenom II X4        | 28       | 1.56%   |
| AMD Athlon II X2        | 27       | 1.51%   |
| AMD A4                  | 21       | 1.17%   |
| AMD Athlon 64 X2        | 20       | 1.12%   |
| AMD Ryzen 9             | 19       | 1.06%   |
| AMD Athlon              | 19       | 1.06%   |
| AMD A10                 | 19       | 1.06%   |
| Intel Core 2            | 17       | 0.95%   |
| Intel Pentium Dual      | 15       | 0.84%   |
| Intel Core i9           | 13       | 0.73%   |
| AMD A6                  | 13       | 0.73%   |
| AMD Ryzen 5 PRO         | 10       | 0.56%   |
| AMD Athlon II X4        | 10       | 0.56%   |
| Intel Pentium Gold      | 9        | 0.5%    |
| AMD Athlon II X3        | 9        | 0.5%    |
| Intel Atom              | 8        | 0.45%   |
| AMD Phenom              | 8        | 0.45%   |
| AMD Athlon X4           | 8        | 0.45%   |
| Intel Pentium D         | 7        | 0.39%   |
| AMD Sempron             | 7        | 0.39%   |
| Intel Pentium 4         | 6        | 0.33%   |
| AMD Phenom II X2        | 6        | 0.33%   |
| AMD Ryzen 3 PRO         | 5        | 0.28%   |
| AMD Phenom II X6        | 5        | 0.28%   |
| AMD Athlon 64           | 5        | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 682      | 38.06%  |
| 2      | 625      | 34.88%  |
| 6      | 254      | 14.17%  |
| 8      | 108      | 6.03%   |
| 1      | 45       | 2.51%   |
| 3      | 33       | 1.84%   |
| 12     | 20       | 1.12%   |
| 16     | 14       | 0.78%   |
| 10     | 7        | 0.39%   |
| 14     | 2        | 0.11%   |
| 44     | 1        | 0.06%   |
| 20     | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1780     | 99.33%  |
| 2      | 12       | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 901      | 50.28%  |
| 2      | 889      | 49.61%  |
| 4      | 2        | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1791     | 99.94%  |
| Unknown        | 1        | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 197      | 10.99%  |
| 0x306a9    | 137      | 7.65%   |
| 0x1067a    | 136      | 7.59%   |
| 0x206a7    | 126      | 7.03%   |
| 0x08701021 | 64       | 3.57%   |
| 0x906ea    | 61       | 3.4%    |
| 0x506e3    | 58       | 3.24%   |
| Unknown    | 47       | 2.62%   |
| 0xa0655    | 46       | 2.57%   |
| 0x906e9    | 43       | 2.4%    |
| 0xa0653    | 35       | 1.95%   |
| 0x010000c8 | 34       | 1.9%    |
| 0x0800820d | 32       | 1.79%   |
| 0x6fb      | 31       | 1.73%   |
| 0x06001119 | 31       | 1.73%   |
| 0x08108109 | 28       | 1.56%   |
| 0x06000822 | 27       | 1.51%   |
| 0x0a50000c | 24       | 1.34%   |
| 0x106e5    | 23       | 1.28%   |
| 0x20655    | 21       | 1.17%   |
| 0x06003106 | 21       | 1.17%   |
| 0xa0671    | 20       | 1.12%   |
| 0x6fd      | 20       | 1.12%   |
| 0x08101016 | 20       | 1.12%   |
| 0x010000b6 | 20       | 1.12%   |
| 0x906eb    | 18       | 1%      |
| 0x10676    | 17       | 0.95%   |
| 0x0a201016 | 17       | 0.95%   |
| 0x08001138 | 14       | 0.78%   |
| 0x906ec    | 12       | 0.67%   |
| 0x106a5    | 12       | 0.67%   |
| 0x08600106 | 12       | 0.67%   |
| 0x03000027 | 12       | 0.67%   |
| 0x90672    | 11       | 0.61%   |
| 0x20652    | 11       | 0.61%   |
| 0x6f6      | 10       | 0.56%   |
| 0x206d7    | 10       | 0.56%   |
| 0x0700010b | 10       | 0.56%   |
| 0x0600081c | 10       | 0.56%   |
| 0x306f2    | 9        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 211      | 11.77%  |
| Penryn           | 162      | 9.04%   |
| KabyLake         | 150      | 8.37%   |
| IvyBridge        | 146      | 8.15%   |
| SandyBridge      | 138      | 7.7%    |
| K10              | 99       | 5.52%   |
| Piledriver       | 93       | 5.19%   |
| Zen 2            | 86       | 4.8%    |
| CometLake        | 81       | 4.52%   |
| Core             | 73       | 4.07%   |
| Zen+             | 68       | 3.79%   |
| Zen 3            | 62       | 3.46%   |
| Skylake          | 61       | 3.4%    |
| Zen              | 58       | 3.24%   |
| Westmere         | 40       | 2.23%   |
| Nehalem          | 37       | 2.06%   |
| K8 Hammer        | 29       | 1.62%   |
| Steamroller      | 26       | 1.45%   |
| Icelake          | 20       | 1.12%   |
| K10 Llano        | 17       | 0.95%   |
| NetBurst         | 15       | 0.84%   |
| Alderlake Hybrid | 15       | 0.84%   |
| Excavator        | 14       | 0.78%   |
| Bulldozer        | 14       | 0.78%   |
| Silvermont       | 12       | 0.67%   |
| Jaguar           | 12       | 0.67%   |
| Goldmont plus    | 12       | 0.67%   |
| Puma             | 10       | 0.56%   |
| Goldmont         | 8        | 0.45%   |
| Broadwell        | 7        | 0.39%   |
| Bonnell          | 7        | 0.39%   |
| Tremont          | 4        | 0.22%   |
| Bobcat           | 4        | 0.22%   |
| TigerLake        | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 644      | 34.87%  |
| Intel                      | 641      | 34.7%   |
| AMD                        | 556      | 30.1%   |
| VIA Technologies           | 3        | 0.16%   |
| Matrox Electronics Systems | 2        | 0.11%   |
| ATI Technologies           | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 107      | 5.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 79       | 4.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 64       | 3.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 59       | 3.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 56       | 2.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 52       | 2.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 52       | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 38       | 2.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 36       | 1.92%   |
| Intel HD Graphics 530                                                       | 34       | 1.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 32       | 1.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 31       | 1.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 30       | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 29       | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 27       | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 27       | 1.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 23       | 1.23%   |
| Intel HD Graphics 630                                                       | 22       | 1.18%   |
| Nvidia GF108 [GeForce GT 630]                                               | 19       | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 19       | 1.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 18       | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 17       | 0.91%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 16       | 0.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 15       | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 15       | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                         | 15       | 0.8%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 15       | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                               | 14       | 0.75%   |
| AMD Renoir                                                                  | 14       | 0.75%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 14       | 0.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 14       | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 12       | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 12       | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 12       | 0.64%   |
| AMD RS780L [Radeon 3000]                                                    | 12       | 0.64%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 12       | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 0.59%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 11       | 0.59%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 11       | 0.59%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 11       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 621      | 34.65%  |
| 1 x Intel      | 589      | 32.87%  |
| 1 x AMD        | 528      | 29.46%  |
| 2 x AMD        | 18       | 1%      |
| Intel + Nvidia | 15       | 0.84%   |
| Intel + AMD    | 7        | 0.39%   |
| 2 x Nvidia     | 5        | 0.28%   |
| 1 x VIA        | 3        | 0.17%   |
| AMD + Nvidia   | 3        | 0.17%   |
| 1 x Matrox     | 2        | 0.11%   |
| 3 x AMD        | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1718     | 95.87%  |
| Unknown     | 72       | 4.02%   |
| Proprietary | 2        | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 657      | 36.66%  |
| 1.01-2.0   | 316      | 17.63%  |
| 0.51-1.0   | 271      | 15.12%  |
| 0.01-0.5   | 223      | 12.44%  |
| 3.01-4.0   | 124      | 6.92%   |
| 7.01-8.0   | 113      | 6.31%   |
| 5.01-6.0   | 43       | 2.4%    |
| 2.01-3.0   | 25       | 1.4%    |
| 8.01-16.0  | 16       | 0.89%   |
| 16.01-24.0 | 4        | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 302      | 17.09%  |
| Goldstar             | 199      | 11.26%  |
| Dell                 | 170      | 9.62%   |
| Hewlett-Packard      | 160      | 9.05%   |
| Acer                 | 134      | 7.58%   |
| Philips              | 119      | 6.73%   |
| AOC                  | 109      | 6.17%   |
| BenQ                 | 72       | 4.07%   |
| Ancor Communications | 62       | 3.51%   |
| ViewSonic            | 54       | 3.06%   |
| Iiyama               | 29       | 1.64%   |
| Lenovo               | 24       | 1.36%   |
| ASUSTek Computer     | 20       | 1.13%   |
| Sony                 | 19       | 1.08%   |
| Eizo                 | 16       | 0.91%   |
| NEC Computers        | 15       | 0.85%   |
| Fujitsu Siemens      | 15       | 0.85%   |
| HannStar             | 13       | 0.74%   |
| Panasonic            | 11       | 0.62%   |
| Sceptre Tech         | 9        | 0.51%   |
| MSI                  | 8        | 0.45%   |
| Medion               | 8        | 0.45%   |
| Hitachi              | 8        | 0.45%   |
| Unknown              | 7        | 0.4%    |
| Toshiba              | 7        | 0.4%    |
| TCL                  | 7        | 0.4%    |
| ___                  | 6        | 0.34%   |
| Vestel Elektronik    | 6        | 0.34%   |
| Unknown (XXX)        | 6        | 0.34%   |
| Packard Bell         | 5        | 0.28%   |
| MiTAC                | 5        | 0.28%   |
| CHD                  | 5        | 0.28%   |
| Xiaomi               | 4        | 0.23%   |
| MStar                | 4        | 0.23%   |
| Mitsubishi           | 4        | 0.23%   |
| IOD                  | 4        | 0.23%   |
| GDH                  | 4        | 0.23%   |
| Vizio                | 3        | 0.17%   |
| Plain Tree Systems   | 3        | 0.17%   |
| Insignia             | 3        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                       | 22       | 1.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 15       | 0.83%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                  | 14       | 0.78%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 8        | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 7        | 0.39%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 7        | 0.39%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 7        | 0.39%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                        | 7        | 0.39%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 6        | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 6        | 0.33%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 6        | 0.33%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 6        | 0.33%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 6        | 0.33%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch   | 5        | 0.28%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 5        | 0.28%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch   | 5        | 0.28%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 5        | 0.28%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 5        | 0.28%   |
| Hewlett-Packard LCD Monitor HWP285A 1920x1080 470x270mm 21.3-inch      | 5        | 0.28%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 5        | 0.28%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 5        | 0.28%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch       | 5        | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch  | 5        | 0.28%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 4        | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 4        | 0.22%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 4        | 0.22%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                  | 4        | 0.22%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch             | 4        | 0.22%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 4        | 0.22%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 4        | 0.22%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4        | 0.22%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                     | 4        | 0.22%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                      | 4        | 0.22%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 4        | 0.22%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 4        | 0.22%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                         | 4        | 0.22%   |
| ___ LCDTV16 ___0101 1360x768                                           | 3        | 0.17%   |
| ___ LCD TV ___9000 1360x768                                            | 3        | 0.17%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                      | 3        | 0.17%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch          | 3        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 847      | 48.71%  |
| 1280x1024 (SXGA)   | 153      | 8.8%    |
| 3840x2160 (4K)     | 138      | 7.94%   |
| 1366x768 (WXGA)    | 105      | 6.04%   |
| 2560x1440 (QHD)    | 94       | 5.41%   |
| 1680x1050 (WSXGA+) | 94       | 5.41%   |
| 1440x900 (WXGA+)   | 69       | 3.97%   |
| 1600x900 (HD+)     | 64       | 3.68%   |
| 1920x1200 (WUXGA)  | 48       | 2.76%   |
| 1360x768           | 34       | 1.96%   |
| 3440x1440          | 22       | 1.27%   |
| 2560x1080          | 17       | 0.98%   |
| 1920x540           | 13       | 0.75%   |
| 1024x768 (XGA)     | 11       | 0.63%   |
| 1600x1200          | 7        | 0.4%    |
| 1280x720 (HD)      | 6        | 0.35%   |
| 1280x960           | 4        | 0.23%   |
| 2288x1287          | 3        | 0.17%   |
| 2048x1152          | 3        | 0.17%   |
| 2560x1600          | 2        | 0.12%   |
| 3840x1600          | 1        | 0.06%   |
| 3840x1200          | 1        | 0.06%   |
| 3840x1080          | 1        | 0.06%   |
| 1280x768           | 1        | 0.06%   |
| Unknown            | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 258      | 14.61%  |
| 21      | 248      | 14.04%  |
| 27      | 235      | 13.31%  |
| 24      | 202      | 11.44%  |
| 19      | 145      | 8.21%   |
| 18      | 105      | 5.95%   |
| 17      | 84       | 4.76%   |
| 31      | 78       | 4.42%   |
| 22      | 78       | 4.42%   |
| 20      | 59       | 3.34%   |
| 84      | 35       | 1.98%   |
| 34      | 35       | 1.98%   |
| 15      | 30       | 1.7%    |
| 32      | 23       | 1.3%    |
| Unknown | 21       | 1.19%   |
| 72      | 15       | 0.85%   |
| 54      | 13       | 0.74%   |
| 40      | 11       | 0.62%   |
| 25      | 11       | 0.62%   |
| 26      | 8        | 0.45%   |
| 65      | 7        | 0.4%    |
| 52      | 7        | 0.4%    |
| 39      | 6        | 0.34%   |
| 33      | 6        | 0.34%   |
| 48      | 5        | 0.28%   |
| 43      | 5        | 0.28%   |
| 46      | 4        | 0.23%   |
| 35      | 4        | 0.23%   |
| 29      | 4        | 0.23%   |
| 142     | 3        | 0.17%   |
| 47      | 3        | 0.17%   |
| 42      | 3        | 0.17%   |
| 28      | 3        | 0.17%   |
| 55      | 2        | 0.11%   |
| 37      | 2        | 0.11%   |
| 12      | 2        | 0.11%   |
| 60      | 1        | 0.06%   |
| 58      | 1        | 0.06%   |
| 50      | 1        | 0.06%   |
| 38      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 669      | 38.56%  |
| 401-500        | 560      | 32.28%  |
| 301-350        | 110      | 6.34%   |
| 601-700        | 102      | 5.88%   |
| 351-400        | 79       | 4.55%   |
| 701-800        | 63       | 3.63%   |
| 1501-2000      | 50       | 2.88%   |
| 1001-1500      | 45       | 2.59%   |
| 801-900        | 24       | 1.38%   |
| Unknown        | 21       | 1.21%   |
| 901-1000       | 7        | 0.4%    |
| More than 2000 | 3        | 0.17%   |
| 201-300        | 2        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1230     | 72.27%  |
| 16/10   | 236      | 13.87%  |
| 5/4     | 147      | 8.64%   |
| 21/9    | 39       | 2.29%   |
| 4/3     | 30       | 1.76%   |
| 3/2     | 8        | 0.47%   |
| 6/5     | 4        | 0.24%   |
| 1.00    | 3        | 0.18%   |
| 32/9    | 2        | 0.12%   |
| 3.20    | 1        | 0.06%   |
| 1.96    | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 640      | 36.7%   |
| 151-200        | 277      | 15.88%  |
| 301-350        | 241      | 13.82%  |
| 141-150        | 168      | 9.63%   |
| 351-500        | 146      | 8.37%   |
| More than 1000 | 88       | 5.05%   |
| 251-300        | 87       | 4.99%   |
| 501-1000       | 40       | 2.29%   |
| 101-110        | 22       | 1.26%   |
| Unknown        | 21       | 1.2%    |
| 111-120        | 7        | 0.4%    |
| 131-140        | 3        | 0.17%   |
| 71-80          | 2        | 0.11%   |
| 81-90          | 1        | 0.06%   |
| 91-100         | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1206     | 70.73%  |
| 101-120 | 333      | 19.53%  |
| 1-50    | 78       | 4.57%   |
| 121-160 | 47       | 2.76%   |
| Unknown | 21       | 1.23%   |
| 161-240 | 20       | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1605     | 89.56%  |
| 2     | 138      | 7.7%    |
| 0     | 35       | 1.95%   |
| 3     | 12       | 0.67%   |
| 7     | 1        | 0.06%   |
| 4     | 1        | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1162     | 49.32%  |
| Intel                             | 623      | 26.44%  |
| Qualcomm Atheros                  | 149      | 6.32%   |
| Ralink Technology                 | 73       | 3.1%    |
| Broadcom                          | 55       | 2.33%   |
| Nvidia                            | 48       | 2.04%   |
| TP-Link                           | 29       | 1.23%   |
| Ralink                            | 26       | 1.1%    |
| Marvell Technology Group          | 19       | 0.81%   |
| Broadcom Limited                  | 17       | 0.72%   |
| Qualcomm Atheros Communications   | 16       | 0.68%   |
| D-Link System                     | 12       | 0.51%   |
| NetGear                           | 10       | 0.42%   |
| D-Link                            | 10       | 0.42%   |
| VIA Technologies                  | 9        | 0.38%   |
| Huawei Technologies               | 9        | 0.38%   |
| Motorola PCS                      | 8        | 0.34%   |
| Samsung Electronics               | 7        | 0.3%    |
| Microsoft                         | 7        | 0.3%    |
| Aquantia                          | 6        | 0.25%   |
| MediaTek                          | 5        | 0.21%   |
| ASUSTek Computer                  | 5        | 0.21%   |
| IMC Networks                      | 4        | 0.17%   |
| Edimax Technology                 | 4        | 0.17%   |
| Belkin Components                 | 4        | 0.17%   |
| ASIX Electronics                  | 4        | 0.17%   |
| Xiaomi                            | 3        | 0.13%   |
| AVM                               | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.08%   |
| Chu Yuen Enterprise               | 2        | 0.08%   |
| 3Com                              | 2        | 0.08%   |
| ZyDAS                             | 1        | 0.04%   |
| U.S. Robotics                     | 1        | 0.04%   |
| TRENDnet                          | 1        | 0.04%   |
| T & A Mobile Phones               | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Spreadtrum Communications         | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.04%   |
| Sangoma Technologies              | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 971      | 37.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 2.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 58       | 2.24%   |
| Intel Ethernet Connection I217-LM                                 | 57       | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56       | 2.16%   |
| Intel I211 Gigabit Network Connection                             | 53       | 2.05%   |
| Intel Wi-Fi 6 AX200                                               | 48       | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 47       | 1.81%   |
| Intel 82579V Gigabit Network Connection                           | 36       | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 32       | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 1.24%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.16%   |
| Ralink MT7601U Wireless Adapter                                   | 29       | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 27       | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27       | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 26       | 1%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 23       | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21       | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.58%   |
| Intel Wireless-AC 9260                                            | 15       | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14       | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.54%   |
| Ralink RT5370 Wireless Adapter                                    | 13       | 0.5%    |
| Intel Wireless 7260                                               | 13       | 0.5%    |
| Intel Wireless 3165                                               | 13       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 13       | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12       | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 11       | 0.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 11       | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 11       | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 11       | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11       | 0.42%   |
| Intel Wireless 7265                                               | 11       | 0.42%   |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.42%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 10       | 0.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 188      | 29.28%  |
| Realtek Semiconductor                 | 156      | 24.3%   |
| Qualcomm Atheros                      | 81       | 12.62%  |
| Ralink Technology                     | 73       | 11.37%  |
| TP-Link                               | 28       | 4.36%   |
| Ralink                                | 26       | 4.05%   |
| Qualcomm Atheros Communications       | 16       | 2.49%   |
| NetGear                               | 10       | 1.56%   |
| D-Link                                | 10       | 1.56%   |
| Broadcom                              | 8        | 1.25%   |
| Microsoft                             | 7        | 1.09%   |
| D-Link System                         | 5        | 0.78%   |
| ASUSTek Computer                      | 5        | 0.78%   |
| MediaTek                              | 4        | 0.62%   |
| IMC Networks                          | 4        | 0.62%   |
| Edimax Technology                     | 4        | 0.62%   |
| Belkin Components                     | 4        | 0.62%   |
| AVM                                   | 3        | 0.47%   |
| Chu Yuen Enterprise                   | 2        | 0.31%   |
| Broadcom Limited                      | 2        | 0.31%   |
| ZyDAS                                 | 1        | 0.16%   |
| TRENDnet                              | 1        | 0.16%   |
| Philips (or NXP)                      | 1        | 0.16%   |
| Logitec                               | 1        | 0.16%   |
| Linksys                               | 1        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                         | 48       | 7.44%   |
| Ralink MT7601U Wireless Adapter                             | 29       | 4.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 27       | 4.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 27       | 4.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter            | 23       | 3.57%   |
| Intel Wireless-AC 9260                                      | 15       | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 14       | 2.17%   |
| Ralink RT5370 Wireless Adapter                              | 13       | 2.02%   |
| Intel Wireless 7260                                         | 13       | 2.02%   |
| Intel Wireless 3165                                         | 13       | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 12       | 1.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter             | 11       | 1.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                      | 11       | 1.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                  | 11       | 1.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                       | 11       | 1.71%   |
| Qualcomm Atheros AR9271 802.11n                             | 11       | 1.71%   |
| Intel Wireless 7265                                         | 11       | 1.71%   |
| Realtek RTL8188EE Wireless Network Adapter                  | 10       | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 10       | 1.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter    | 9        | 1.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter             | 9        | 1.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                     | 9        | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                      | 9        | 1.4%    |
| Realtek 802.11ac NIC                                        | 8        | 1.24%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                | 7        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                          | 7        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 7        | 1.09%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter            | 7        | 1.09%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                         | 6        | 0.93%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter    | 6        | 0.93%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                      | 6        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 6        | 0.93%   |
| Microsoft Xbox 360 Wireless Adapter                         | 6        | 0.93%   |
| Ralink RT5372 Wireless Adapter                              | 5        | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                   | 5        | 0.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                   | 5        | 0.78%   |
| Ralink RT2561/RT61 802.11g PCI                              | 5        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 5        | 0.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter  | 5        | 0.78%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU] | 5        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1108     | 58.81%  |
| Intel                             | 503      | 26.7%   |
| Qualcomm Atheros                  | 74       | 3.93%   |
| Nvidia                            | 48       | 2.55%   |
| Broadcom                          | 47       | 2.49%   |
| Marvell Technology Group          | 19       | 1.01%   |
| Broadcom Limited                  | 15       | 0.8%    |
| VIA Technologies                  | 9        | 0.48%   |
| Huawei Technologies               | 9        | 0.48%   |
| Samsung Electronics               | 7        | 0.37%   |
| D-Link System                     | 7        | 0.37%   |
| Aquantia                          | 6        | 0.32%   |
| Motorola PCS                      | 4        | 0.21%   |
| ASIX Electronics                  | 4        | 0.21%   |
| Xiaomi                            | 3        | 0.16%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.11%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.11%   |
| 3Com                              | 2        | 0.11%   |
| TP-Link                           | 1        | 0.05%   |
| T & A Mobile Phones               | 1        | 0.05%   |
| Sundance Technology Inc / IC Plus | 1        | 0.05%   |
| Spreadtrum Communications         | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.05%   |
| Qualcomm                          | 1        | 0.05%   |
| OPPO Electronics                  | 1        | 0.05%   |
| Netchip Technology                | 1        | 0.05%   |
| Mellanox Technologies             | 1        | 0.05%   |
| MediaTek                          | 1        | 0.05%   |
| JMicron Technology                | 1        | 0.05%   |
| HTC (High Tech Computer)          | 1        | 0.05%   |
| Emulex                            | 1        | 0.05%   |
| DisplayLink                       | 1        | 0.05%   |
| Adnaco Technology                 | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 971      | 50.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 3.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 58       | 2.99%   |
| Intel Ethernet Connection I217-LM                                 | 57       | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56       | 2.89%   |
| Intel I211 Gigabit Network Connection                             | 53       | 2.73%   |
| Intel Ethernet Connection (2) I219-V                              | 47       | 2.42%   |
| Intel 82579V Gigabit Network Connection                           | 36       | 1.86%   |
| Intel Ethernet Connection (7) I219-V                              | 32       | 1.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 1.65%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.55%   |
| Intel Ethernet Controller I225-V                                  | 26       | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21       | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 20       | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 13       | 0.67%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.62%   |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10       | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10       | 0.52%   |
| Intel 82578DC Gigabit Network Connection                          | 9        | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 8        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8        | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8        | 0.41%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 8        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 7        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 0.31%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6        | 0.31%   |
| Intel Ethernet Connection (2) I218-LM                             | 6        | 0.31%   |
| Intel Ethernet Connection (12) I219-V                             | 6        | 0.31%   |
| Intel Ethernet Connection (11) I219-V                             | 6        | 0.31%   |
| Intel 82567V-2 Gigabit Network Connection                         | 6        | 0.31%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 6        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1776     | 74%     |
| WiFi     | 618      | 25.75%  |
| Unknown  | 5        | 0.21%   |
| Modem    | 1        | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1516     | 85.89%  |
| WiFi     | 249      | 14.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1275     | 71.15%  |
| 2     | 455      | 25.39%  |
| 3     | 42       | 2.34%   |
| 0     | 16       | 0.89%   |
| 4     | 4        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1273     | 71.04%  |
| Yes  | 519      | 28.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 171      | 42.75%  |
| Cambridge Silicon Radio         | 110      | 27.5%   |
| Realtek Semiconductor           | 29       | 7.25%   |
| ASUSTek Computer                | 23       | 5.75%   |
| Qualcomm Atheros Communications | 18       | 4.5%    |
| Broadcom                        | 17       | 4.25%   |
| IMC Networks                    | 10       | 2.5%    |
| Lite-On Technology              | 3        | 0.75%   |
| Apple                           | 3        | 0.75%   |
| TP-Link                         | 2        | 0.5%    |
| MediaTek                        | 2        | 0.5%    |
| Unknown                         | 2        | 0.5%    |
| Unknown                         | 1        | 0.25%   |
| SINO WEALTH                     | 1        | 0.25%   |
| Ralink                          | 1        | 0.25%   |
| Primax Electronics              | 1        | 0.25%   |
| Integrated System Solution      | 1        | 0.25%   |
| Foxconn / Hon Hai               | 1        | 0.25%   |
| Edimax Technology               | 1        | 0.25%   |
| Dynex                           | 1        | 0.25%   |
| Dell                            | 1        | 0.25%   |
| Belkin Components               | 1        | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 110      | 27.5%   |
| Intel AX200 Bluetooth                                 | 47       | 11.75%  |
| Intel Bluetooth wireless interface                    | 46       | 11.5%   |
| Intel Wireless-AC 3168 Bluetooth                      | 24       | 6%      |
| Realtek Bluetooth Radio                               | 17       | 4.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 14       | 3.5%    |
| Intel AX201 Bluetooth                                 | 13       | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                        | 11       | 2.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 11       | 2.75%   |
| Intel AX210 Bluetooth                                 | 10       | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 9        | 2.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 9        | 2.25%   |
| IMC Networks Bluetooth Radio                          | 8        | 2%      |
| Qualcomm Atheros  Bluetooth Device                    | 7        | 1.75%   |
| ASUS ASUS USB-BT500                                   | 7        | 1.75%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 4        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver         | 4        | 1%      |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.75%   |
| TP-Link UB500 Adapter                                 | 2        | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2        | 0.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 2        | 0.5%    |
| MediaTek Wireless_Device                              | 2        | 0.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2        | 0.5%    |
| Intel Bluetooth Device                                | 2        | 0.5%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 2        | 0.5%    |
| ASUS Bluetooth Radio                                  | 2        | 0.5%    |
| ASUS Bluetooth Adapter                                | 2        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2        | 0.5%    |
| Unknown                                               | 2        | 0.5%    |
| Unknown Bluetooth Device                              | 1        | 0.25%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.25%   |
| Realtek Bluetooth 5.1 Radio                           | 1        | 0.25%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.25%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter         | 1        | 0.25%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1        | 0.25%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 0.25%   |
| IMC Networks Bluetooth Module                         | 1        | 0.25%   |
| IMC Networks Bluetooth Device                         | 1        | 0.25%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 0.25%   |
| Edimax Bluetooth Adapter                              | 1        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1155     | 41.7%   |
| AMD                                          | 731      | 26.39%  |
| Nvidia                                       | 597      | 21.55%  |
| C-Media Electronics                          | 68       | 2.45%   |
| Creative Labs                                | 46       | 1.66%   |
| Logitech                                     | 24       | 0.87%   |
| Texas Instruments                            | 16       | 0.58%   |
| Creative Technology                          | 11       | 0.4%    |
| ASUSTek Computer                             | 10       | 0.36%   |
| JMTek                                        | 9        | 0.32%   |
| VIA Technologies                             | 7        | 0.25%   |
| GN Netcom                                    | 7        | 0.25%   |
| Generalplus Technology                       | 6        | 0.22%   |
| XMOS                                         | 4        | 0.14%   |
| Tenx Technology                              | 4        | 0.14%   |
| Blue Microphones                             | 4        | 0.14%   |
| Sony                                         | 3        | 0.11%   |
| Razer USA                                    | 3        | 0.11%   |
| Plantronics                                  | 3        | 0.11%   |
| Kingston Technology                          | 3        | 0.11%   |
| Trust                                        | 2        | 0.07%   |
| SteelSeries ApS                              | 2        | 0.07%   |
| Samson Technologies                          | 2        | 0.07%   |
| ROCCAT                                       | 2        | 0.07%   |
| PreSonus Audio Electronics                   | 2        | 0.07%   |
| KTMicro                                      | 2        | 0.07%   |
| GYROCOM C&C                                  | 2        | 0.07%   |
| FiiO Electronics Technology                  | 2        | 0.07%   |
| Corsair                                      | 2        | 0.07%   |
| BEHRINGER International                      | 2        | 0.07%   |
| Audient                                      | 2        | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.04%   |
| ZOOM                                         | 1        | 0.04%   |
| Xilinx                                       | 1        | 0.04%   |
| WL80                                         | 1        | 0.04%   |
| Valve Software                               | 1        | 0.04%   |
| USB MICROPHONE                               | 1        | 0.04%   |
| Unknown                                      | 1        | 0.04%   |
| Sonuus Limited                               | 1        | 0.04%   |
| Silicon Labs                                 | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 168      | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 155      | 4.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 149      | 4.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 127      | 3.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 113      | 3.48%   |
| AMD Family 17h/19h HD Audio Controller                                            | 104      | 3.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 103      | 3.17%   |
| AMD FCH Azalia Controller                                                         | 101      | 3.11%   |
| AMD Starship/Matisse HD Audio Controller                                          | 95       | 2.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 91       | 2.8%    |
| Intel 200 Series PCH HD Audio                                                     | 71       | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 70       | 2.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 64       | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                        | 62       | 1.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 60       | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 58       | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 57       | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 55       | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 55       | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 52       | 1.6%    |
| Nvidia High Definition Audio Controller                                           | 51       | 1.57%   |
| Intel Audio device                                                                | 49       | 1.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 46       | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                     | 44       | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 39       | 1.2%    |
| Nvidia MCP61 High Definition Audio                                                | 35       | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 34       | 1.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 32       | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                | 30       | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 29       | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                     | 27       | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 24       | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                     | 23       | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                                     | 23       | 0.71%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 22       | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                          | 21       | 0.65%   |
| Intel Comet Lake PCH-V cAVS                                                       | 20       | 0.62%   |
| AMD Trinity HDMI Audio Controller                                                 | 20       | 0.62%   |
| AMD Navi 10 HDMI Audio                                                            | 20       | 0.62%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 20       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 392      | 18.44%  |
| Kingston            | 382      | 17.97%  |
| Samsung Electronics | 212      | 9.97%   |
| Corsair             | 167      | 7.86%   |
| SK hynix            | 156      | 7.34%   |
| Crucial             | 144      | 6.77%   |
| G.Skill             | 140      | 6.59%   |
| Micron Technology   | 113      | 5.32%   |
| A-DATA Technology   | 46       | 2.16%   |
| Unknown             | 41       | 1.93%   |
| Patriot             | 32       | 1.51%   |
| Ramaxel Technology  | 29       | 1.36%   |
| Nanya Technology    | 25       | 1.18%   |
| Team                | 23       | 1.08%   |
| Elpida              | 18       | 0.85%   |
| Transcend           | 17       | 0.8%    |
| Smart               | 17       | 0.8%    |
| GOODRAM             | 14       | 0.66%   |
| AMD                 | 9        | 0.42%   |
| Unknown (ABCD)      | 7        | 0.33%   |
| PNY                 | 7        | 0.33%   |
| Kingmax             | 7        | 0.33%   |
| GeIL                | 7        | 0.33%   |
| Unifosa             | 6        | 0.28%   |
| Silicon Power       | 6        | 0.28%   |
| CSX                 | 6        | 0.28%   |
| Apacer              | 6        | 0.28%   |
| Qimonda             | 5        | 0.24%   |
| OM Nanotech         | 4        | 0.19%   |
| Teikon              | 3        | 0.14%   |
| Ramos Technology    | 3        | 0.14%   |
| Kllisre             | 3        | 0.14%   |
| KLEVV               | 3        | 0.14%   |
| Wilk Elektronik     | 2        | 0.09%   |
| V-GeN               | 2        | 0.09%   |
| Unknown (2C0B)      | 2        | 0.09%   |
| Super Talent        | 2        | 0.09%   |
| Sesame              | 2        | 0.09%   |
| OCZ                 | 2        | 0.09%   |
| Novatech            | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 41       | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 30       | 1.28%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 28       | 1.2%    |
| Unknown RAM Module 2GB DIMM SDRAM                       | 28       | 1.2%    |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 23       | 0.98%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s   | 18       | 0.77%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 17       | 0.73%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s  | 17       | 0.73%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                | 17       | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 16       | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 16       | 0.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 16       | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 15       | 0.64%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 15       | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 14       | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 14       | 0.6%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s  | 14       | 0.6%    |
| Unknown RAM Module 1GB DIMM SDRAM                       | 13       | 0.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 13       | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 12       | 0.51%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 12       | 0.51%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 12       | 0.51%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 12       | 0.51%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 11       | 0.47%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 11       | 0.47%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 11       | 0.47%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 11       | 0.47%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 10       | 0.43%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 10       | 0.43%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 9        | 0.38%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 9        | 0.38%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 9        | 0.38%   |
| Unknown RAM Module 1GB DIMM 800MT/s                     | 9        | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 9        | 0.38%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 9        | 0.38%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 9        | 0.38%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s | 9        | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 9        | 0.38%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s   | 8        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s      | 8        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 743      | 40.91%  |
| DDR4    | 623      | 34.31%  |
| DDR2    | 151      | 8.31%   |
| Unknown | 149      | 8.2%    |
| SDRAM   | 116      | 6.39%   |
| DDR     | 22       | 1.21%   |
| LPDDR4  | 8        | 0.44%   |
| DDR5    | 3        | 0.17%   |
| DRAM    | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1672     | 94.09%  |
| SODIMM  | 102      | 5.74%   |
| RIMM    | 2        | 0.11%   |
| FB-DIMM | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 671      | 33.15%  |
| 4096  | 595      | 29.4%   |
| 2048  | 415      | 20.5%   |
| 16384 | 175      | 8.65%   |
| 1024  | 123      | 6.08%   |
| 32768 | 29       | 1.43%   |
| 512   | 16       | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 455      | 22.37%  |
| 1333    | 303      | 14.9%   |
| 3200    | 123      | 6.05%   |
| 800     | 117      | 5.75%   |
| 2400    | 112      | 5.51%   |
| 3600    | 101      | 4.97%   |
| 2667    | 99       | 4.87%   |
| 2133    | 86       | 4.23%   |
| 667     | 71       | 3.49%   |
| Unknown | 67       | 3.29%   |
| 2666    | 55       | 2.7%    |
| 1867    | 48       | 2.36%   |
| 1866    | 39       | 1.92%   |
| 3400    | 26       | 1.28%   |
| 3000    | 26       | 1.28%   |
| 1066    | 26       | 1.28%   |
| 1800    | 21       | 1.03%   |
| 400     | 21       | 1.03%   |
| 533     | 20       | 0.98%   |
| 1067    | 19       | 0.93%   |
| 3866    | 15       | 0.74%   |
| 2933    | 14       | 0.69%   |
| 3466    | 12       | 0.59%   |
| 3733    | 11       | 0.54%   |
| 2048    | 10       | 0.49%   |
| 2800    | 9        | 0.44%   |
| 1334    | 9        | 0.44%   |
| 3066    | 8        | 0.39%   |
| 49926   | 7        | 0.34%   |
| 333     | 7        | 0.34%   |
| 3800    | 6        | 0.29%   |
| 2000    | 6        | 0.29%   |
| 1648    | 6        | 0.29%   |
| 1639    | 5        | 0.25%   |
| 3666    | 4        | 0.2%    |
| 3334    | 4        | 0.2%    |
| 3007    | 4        | 0.2%    |
| 2465    | 4        | 0.2%    |
| 41632   | 3        | 0.15%   |
| 4800    | 3        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 46       | 39.66%  |
| Brother Industries    | 28       | 24.14%  |
| Canon                 | 14       | 12.07%  |
| Samsung Electronics   | 10       | 8.62%   |
| Seiko Epson           | 7        | 6.03%   |
| Lexmark International | 4        | 3.45%   |
| Xerox                 | 2        | 1.72%   |
| Kyocera               | 2        | 1.72%   |
| Ricoh                 | 1        | 0.86%   |
| QinHeng Electronics   | 1        | 0.86%   |
| NXP Semiconductors    | 1        | 0.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP LaserJet 1010                             | 3        | 2.59%   |
| Seiko Epson ET-4760 Series                   | 2        | 1.72%   |
| Samsung SCX-3400 Series                      | 2        | 1.72%   |
| Samsung M2070 Series                         | 2        | 1.72%   |
| Samsung M2020 Series                         | 2        | 1.72%   |
| Samsung CLP-310 Color Laser Printer          | 2        | 1.72%   |
| HP LaserJet P1005                            | 2        | 1.72%   |
| HP LaserJet 1020                             | 2        | 1.72%   |
| HP Ink Tank Wireless 410 series              | 2        | 1.72%   |
| HP ENVY 4520 series                          | 2        | 1.72%   |
| HP ENVY 4500 series                          | 2        | 1.72%   |
| HP Deskjet 1050 J410                         | 2        | 1.72%   |
| Brother MFC-L2710DW series                   | 2        | 1.72%   |
| Brother MFC-J470DW                           | 2        | 1.72%   |
| Brother DCP-T310                             | 2        | 1.72%   |
| Xerox Phaser 6510                            | 1        | 0.86%   |
| Xerox Phaser 6010N                           | 1        | 0.86%   |
| Seiko Epson XP-2100 Series                   | 1        | 0.86%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.86%   |
| Seiko Epson L365 Series                      | 1        | 0.86%   |
| Seiko Epson L120 Series                      | 1        | 0.86%   |
| Seiko Epson ET-3750 Series                   | 1        | 0.86%   |
| Samsung ML-2850 Series                       | 1        | 0.86%   |
| Samsung M267x 287x Series                    | 1        | 0.86%   |
| Ricoh SP 211                                 | 1        | 0.86%   |
| QinHeng CH340S                               | 1        | 0.86%   |
| NXP Semiconductors Printer-80                | 1        | 0.86%   |
| Lexmark International X364dn                 | 1        | 0.86%   |
| Lexmark International MS710                  | 1        | 0.86%   |
| Lexmark International CX410de                | 1        | 0.86%   |
| Lexmark International B2236dw                | 1        | 0.86%   |
| Kyocera ECOSYS P5021cdw                      | 1        | 0.86%   |
| Kyocera ECOSYS P2040dw                       | 1        | 0.86%   |
| HP PSC 1400                                  | 1        | 0.86%   |
| HP PhotoSmart P1000                          | 1        | 0.86%   |
| HP Officejet Pro 8100                        | 1        | 0.86%   |
| HP OfficeJet Pro 7740 series                 | 1        | 0.86%   |
| HP OfficeJet 8010 series                     | 1        | 0.86%   |
| HP OfficeJet 6950                            | 1        | 0.86%   |
| HP LaserJet Professional P1102w              | 1        | 0.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 68.75%  |
| Seiko Epson     | 2        | 12.5%   |
| Mustek Systems  | 2        | 12.5%   |
| Hewlett-Packard | 1        | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 2        | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2        | 12.5%   |
| Canon CanoScan N1240U/LiDE 30                 | 2        | 12.5%   |
| Canon CanoScan LiDE 110                       | 2        | 12.5%   |
| Canon CanoScan LiDE 100                       | 2        | 12.5%   |
| Mustek Systems SNAPSCAN e22                   | 1        | 6.25%   |
| Mustek Systems ScanExpress 1200 CU            | 1        | 6.25%   |
| HP ScanJet 2400c                              | 1        | 6.25%   |
| Canon CanoScan LiDE 210                       | 1        | 6.25%   |
| Canon CanoScan LiDE 120                       | 1        | 6.25%   |
| Canon CanoScan 5200F                          | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 95       | 41.3%   |
| Microsoft                     | 16       | 6.96%   |
| Microdia                      | 14       | 6.09%   |
| Generalplus Technology        | 8        | 3.48%   |
| Realtek Semiconductor         | 7        | 3.04%   |
| Z-Star Microelectronics       | 6        | 2.61%   |
| Sunplus Innovation Technology | 5        | 2.17%   |
| Samsung Electronics           | 5        | 2.17%   |
| KYE Systems (Mouse Systems)   | 5        | 2.17%   |
| Hewlett-Packard               | 5        | 2.17%   |
| Trust                         | 4        | 1.74%   |
| Cubeternet                    | 4        | 1.74%   |
| Chicony Electronics           | 4        | 1.74%   |
| Aveo Technology               | 4        | 1.74%   |
| ARC International             | 4        | 1.74%   |
| Apple                         | 4        | 1.74%   |
| Unknown                       | 3        | 1.3%    |
| Jieli Technology              | 3        | 1.3%    |
| Pixart Imaging                | 2        | 0.87%   |
| MacroSilicon                  | 2        | 0.87%   |
| IMC Networks                  | 2        | 0.87%   |
| Genesys Logic                 | 2        | 0.87%   |
| GEMBIRD                       | 2        | 0.87%   |
| Creative Technology           | 2        | 0.87%   |
| AVerMedia Technologies        | 2        | 0.87%   |
| WCM_USB                       | 1        | 0.43%   |
| Valve Software                | 1        | 0.43%   |
| Sonix Technology              | 1        | 0.43%   |
| SJ-180517-N                   | 1        | 0.43%   |
| Silicon Motion                | 1        | 0.43%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.43%   |
| Razer USA                     | 1        | 0.43%   |
| Novatek Microelectronics      | 1        | 0.43%   |
| Huawei Technologies           | 1        | 0.43%   |
| Guillemot                     | 1        | 0.43%   |
| eMeet-200611                  | 1        | 0.43%   |
| EC2U200                       | 1        | 0.43%   |
| CZUR Technology               | 1        | 0.43%   |
| CVT Electronics.Co.           | 1        | 0.43%   |
| Arkmicro Technologies         | 1        | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 26       | 11.26%  |
| Logitech HD Pro Webcam C920             | 11       | 4.76%   |
| Logitech HD Webcam C525                 | 10       | 4.33%   |
| Microsoft LifeCam HD-3000               | 9        | 3.9%    |
| Generalplus GENERAL WEBCAM              | 8        | 3.46%   |
| Logitech Webcam C170                    | 7        | 3.03%   |
| Logitech HD Webcam C615                 | 7        | 3.03%   |
| Samsung Galaxy series, misc. (MTP mode) | 5        | 2.16%   |
| Microdia Hy-HD-Camera                   | 4        | 1.73%   |
| Aveo USB2.0 Camera                      | 4        | 1.73%   |
| ARC International Camera                | 4        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE               | 4        | 1.73%   |
| Unknown HD camera                       | 3        | 1.3%    |
| Realtek USB Camera                      | 3        | 1.3%    |
| Microdia Webcam Vitade AF               | 3        | 1.3%    |
| Microdia Camera                         | 3        | 1.3%    |
| Logitech Webcam Pro 9000                | 3        | 1.3%    |
| Logitech Webcam C310                    | 3        | 1.3%    |
| Logitech C922 Pro Stream Webcam         | 3        | 1.3%    |
| Jieli USB PHY 2.0                       | 3        | 1.3%    |
| HP Webcam HD 2300                       | 3        | 1.3%    |
| Cubeternet USB2.0 Camera                | 3        | 1.3%    |
| Z-Star A4 TECH USB2.0 PC Camera J       | 2        | 0.87%   |
| Trust WB-6250X Webcam                   | 2        | 0.87%   |
| Sunplus HD 720P webcam                  | 2        | 0.87%   |
| Sunplus Full HD webcam                  | 2        | 0.87%   |
| Realtek WEB CAMERA M9 Pro               | 2        | 0.87%   |
| Microsoft LifeCam Cinema                | 2        | 0.87%   |
| MacroSilicon USB Video                  | 2        | 0.87%   |
| Logitech Webcam C930e                   | 2        | 0.87%   |
| Logitech Webcam C925e                   | 2        | 0.87%   |
| Logitech Webcam C250                    | 2        | 0.87%   |
| Logitech QuickCam Pro 9000              | 2        | 0.87%   |
| Logitech HD Webcam C910                 | 2        | 0.87%   |
| Logitech HD Webcam C510                 | 2        | 0.87%   |
| Logitech BRIO                           | 2        | 0.87%   |
| IMC Networks XHC Camera                 | 2        | 0.87%   |
| Genesys Logic Camera                    | 2        | 0.87%   |
| Z-Star Vimicro USB2.0 UVC PC Camera     | 1        | 0.43%   |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| LighTuning Technology | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 28.57%  |
| Gemalto (was Gemplus) | 2        | 28.57%  |
| SCM Microsystems      | 1        | 14.29%  |
| Cherry                | 1        | 14.29%  |
| BIT4ID                | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 28.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 28.57%  |
| SCM Microsystems CLOUD 2700 F Smart Card Reader   | 1        | 14.29%  |
| Cherry Smart Terminal XX44                        | 1        | 14.29%  |
| BIT4ID miniLector EVO                             | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1627     | 90.79%  |
| 1     | 155      | 8.65%   |
| 2     | 8        | 0.45%   |
| 7     | 1        | 0.06%   |
| 4     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 78       | 45.61%  |
| Net/wireless             | 35       | 20.47%  |
| Unassigned class         | 12       | 7.02%   |
| Communication controller | 11       | 6.43%   |
| Multimedia controller    | 7        | 4.09%   |
| Bluetooth                | 7        | 4.09%   |
| Chipcard                 | 6        | 3.51%   |
| Wireless                 | 3        | 1.75%   |
| Network                  | 3        | 1.75%   |
| Net/ethernet             | 2        | 1.17%   |
| Fingerprint reader       | 2        | 1.17%   |
| Card reader              | 2        | 1.17%   |
| Camera                   | 2        | 1.17%   |
| Storage/raid             | 1        | 0.58%   |

