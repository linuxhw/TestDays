Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 6025

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1720               | Notebook    | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4fe5238f21](https://linux-hardware.org/?probe=4fe5238f21) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [b4a67f9e6d](https://linux-hardware.org/?probe=b4a67f9e6d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7d1e95601c](https://linux-hardware.org/?probe=7d1e95601c) | Aug 09, 2023 |
| HP            | ProBook 4310s               | Notebook    | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [2a02492c01](https://linux-hardware.org/?probe=2a02492c01) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [509b979b88](https://linux-hardware.org/?probe=509b979b88) | Aug 09, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [8a6ead436f](https://linux-hardware.org/?probe=8a6ead436f) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [60a28c22c7](https://linux-hardware.org/?probe=60a28c22c7) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [9f044dbe9e](https://linux-hardware.org/?probe=9f044dbe9e) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [c1062b9705](https://linux-hardware.org/?probe=c1062b9705) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [46a7513850](https://linux-hardware.org/?probe=46a7513850) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [309b546405](https://linux-hardware.org/?probe=309b546405) | Aug 07, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7c6e6aaaea](https://linux-hardware.org/?probe=7c6e6aaaea) | Aug 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8ee3625d12](https://linux-hardware.org/?probe=8ee3625d12) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [eeb7f6e8fe](https://linux-hardware.org/?probe=eeb7f6e8fe) | Aug 06, 2023 |
| HP            | 829A                        | Mini pc     | [8d7ea68ded](https://linux-hardware.org/?probe=8d7ea68ded) | Aug 05, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [c157382bd3](https://linux-hardware.org/?probe=c157382bd3) | Aug 05, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [4a2c7a9f15](https://linux-hardware.org/?probe=4a2c7a9f15) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [32fd45f163](https://linux-hardware.org/?probe=32fd45f163) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [5636598221](https://linux-hardware.org/?probe=5636598221) | Aug 03, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [1318f4d842](https://linux-hardware.org/?probe=1318f4d842) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [79d26043a0](https://linux-hardware.org/?probe=79d26043a0) | Aug 03, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [deb7c70ef0](https://linux-hardware.org/?probe=deb7c70ef0) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [d5bb32f2de](https://linux-hardware.org/?probe=d5bb32f2de) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| Gigabyte      | P35-DS4                     | Desktop     | [9116e4042c](https://linux-hardware.org/?probe=9116e4042c) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fd9503645f](https://linux-hardware.org/?probe=fd9503645f) | Aug 01, 2023 |
| Dell          | Latitude E6440              | Notebook    | [57ce920c06](https://linux-hardware.org/?probe=57ce920c06) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [22e8927934](https://linux-hardware.org/?probe=22e8927934) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [046b3ffe68](https://linux-hardware.org/?probe=046b3ffe68) | Aug 01, 2023 |
| Dell          | OptiPlex 980                | Desktop     | [7ec85c3865](https://linux-hardware.org/?probe=7ec85c3865) | Aug 01, 2023 |
| HP            | 8924 0101                   | All in one  | [e2fa4d7d10](https://linux-hardware.org/?probe=e2fa4d7d10) | Jul 31, 2023 |
| Intel         | NUC7i7DNB J83500-207        | Mini pc     | [e18855dc59](https://linux-hardware.org/?probe=e18855dc59) | Jul 30, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f94bdf300](https://linux-hardware.org/?probe=4f94bdf300) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4d875892d6](https://linux-hardware.org/?probe=4d875892d6) | Jul 30, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4ff0e84129](https://linux-hardware.org/?probe=4ff0e84129) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [02383fb507](https://linux-hardware.org/?probe=02383fb507) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [ca01eab0e3](https://linux-hardware.org/?probe=ca01eab0e3) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [b322ef8e74](https://linux-hardware.org/?probe=b322ef8e74) | Jul 28, 2023 |
| HP            | 829D                        | Desktop     | [35b5c3a375](https://linux-hardware.org/?probe=35b5c3a375) | Jul 28, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d6855eabe2](https://linux-hardware.org/?probe=d6855eabe2) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Minix         | NEO Z83-4A                  | Notebook    | [3a884d55d3](https://linux-hardware.org/?probe=3a884d55d3) | Jul 26, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [864fcc639d](https://linux-hardware.org/?probe=864fcc639d) | Jul 25, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| Intel         | NUC5i5MYBE H47797-206       | Mini pc     | [393855b913](https://linux-hardware.org/?probe=393855b913) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7970e46266](https://linux-hardware.org/?probe=7970e46266) | Jul 25, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [12c8f156b9](https://linux-hardware.org/?probe=12c8f156b9) | Jul 25, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [52d2901ce2](https://linux-hardware.org/?probe=52d2901ce2) | Jul 25, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b30f6c221b](https://linux-hardware.org/?probe=b30f6c221b) | Jul 25, 2023 |
| ASUSTek       | T303UA                      | Tablet      | [19f4fde1e4](https://linux-hardware.org/?probe=19f4fde1e4) | Jul 24, 2023 |
| ASUSTek       | T303UA                      | Tablet      | [8e189305b3](https://linux-hardware.org/?probe=8e189305b3) | Jul 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [67585d0d00](https://linux-hardware.org/?probe=67585d0d00) | Jul 24, 2023 |
| HP            | 212B                        | Desktop     | [3e033bf376](https://linux-hardware.org/?probe=3e033bf376) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [02cae62d32](https://linux-hardware.org/?probe=02cae62d32) | Jul 24, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [684aa3a397](https://linux-hardware.org/?probe=684aa3a397) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [de58b924e1](https://linux-hardware.org/?probe=de58b924e1) | Jul 23, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [5215522010](https://linux-hardware.org/?probe=5215522010) | Jul 23, 2023 |
| AMI           | Intel                       | Desktop     | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Standard      | Unknown                     | Notebook    | [74acf0f707](https://linux-hardware.org/?probe=74acf0f707) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [f7218e4043](https://linux-hardware.org/?probe=f7218e4043) | Jul 20, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a55acd567e](https://linux-hardware.org/?probe=a55acd567e) | Jul 19, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [73bad4fbb8](https://linux-hardware.org/?probe=73bad4fbb8) | Jul 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [92efeaeef7](https://linux-hardware.org/?probe=92efeaeef7) | Jul 18, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [49a085a451](https://linux-hardware.org/?probe=49a085a451) | Jul 18, 2023 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| HP            | Notebook                    | Notebook    | [4498c757a7](https://linux-hardware.org/?probe=4498c757a7) | Jul 18, 2023 |
| Dell          | Latitude E5510              | Notebook    | [3b006db4ec](https://linux-hardware.org/?probe=3b006db4ec) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [19b0d02a1e](https://linux-hardware.org/?probe=19b0d02a1e) | Jul 17, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e22c4ba5ee](https://linux-hardware.org/?probe=e22c4ba5ee) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| ASRock        | H370 Performance            | Desktop     | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | Notebook    | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d553e03b18](https://linux-hardware.org/?probe=d553e03b18) | Jul 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a230ea3a4d](https://linux-hardware.org/?probe=a230ea3a4d) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [038a62a49f](https://linux-hardware.org/?probe=038a62a49f) | Jul 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4de092adb7](https://linux-hardware.org/?probe=4de092adb7) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| Dell          | Precision 7540              | Notebook    | [c862752535](https://linux-hardware.org/?probe=c862752535) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4dc6731c7a](https://linux-hardware.org/?probe=4dc6731c7a) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e32b594990](https://linux-hardware.org/?probe=e32b594990) | Jul 14, 2023 |
| MSI           | H170M PRO-VDH               | Desktop     | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [74ef14c05b](https://linux-hardware.org/?probe=74ef14c05b) | Jul 13, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [b937fd31a8](https://linux-hardware.org/?probe=b937fd31a8) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| HP            | ProBook 6570b               | Notebook    | [0c933d2dd8](https://linux-hardware.org/?probe=0c933d2dd8) | Jul 12, 2023 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [e160b642b4](https://linux-hardware.org/?probe=e160b642b4) | Jul 12, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ea5b457e85](https://linux-hardware.org/?probe=ea5b457e85) | Jul 11, 2023 |
| Acer          | Extensa 7630G               | Notebook    | [47c7ddbf85](https://linux-hardware.org/?probe=47c7ddbf85) | Jul 11, 2023 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [f7305d0265](https://linux-hardware.org/?probe=f7305d0265) | Jul 11, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [8ec23e64db](https://linux-hardware.org/?probe=8ec23e64db) | Jul 10, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [f60d21d84f](https://linux-hardware.org/?probe=f60d21d84f) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Acer          | TravelMate P2510-G2-M       | Notebook    | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| ECS           | P43T-AD3                    | Desktop     | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a3fd5e4b9d](https://linux-hardware.org/?probe=a3fd5e4b9d) | Jul 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3401b425ae](https://linux-hardware.org/?probe=3401b425ae) | Jul 07, 2023 |
| ASUSTek       | G73Jw                       | Notebook    | [79053de50e](https://linux-hardware.org/?probe=79053de50e) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | Notebook    | [b482f282a5](https://linux-hardware.org/?probe=b482f282a5) | Jul 06, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [55d33d8a40](https://linux-hardware.org/?probe=55d33d8a40) | Jul 06, 2023 |
| Notebook      | NJx0PU                      | Notebook    | [29ebf426d1](https://linux-hardware.org/?probe=29ebf426d1) | Jul 06, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [d759c2c726](https://linux-hardware.org/?probe=d759c2c726) | Jul 06, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4e88e96d9f](https://linux-hardware.org/?probe=4e88e96d9f) | Jul 06, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [d988a440f0](https://linux-hardware.org/?probe=d988a440f0) | Jul 05, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [4397540a82](https://linux-hardware.org/?probe=4397540a82) | Jul 05, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [a40b38a093](https://linux-hardware.org/?probe=a40b38a093) | Jul 05, 2023 |
| Dell          | 0WG261                      | Desktop     | [8ef0f126d5](https://linux-hardware.org/?probe=8ef0f126d5) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | 212B                        | Desktop     | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [2296d2e846](https://linux-hardware.org/?probe=2296d2e846) | Jul 03, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9330835392](https://linux-hardware.org/?probe=9330835392) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [6a51948293](https://linux-hardware.org/?probe=6a51948293) | Jul 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [5af51ee197](https://linux-hardware.org/?probe=5af51ee197) | Jul 03, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [e578144ebb](https://linux-hardware.org/?probe=e578144ebb) | Jul 02, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [83fd2dc626](https://linux-hardware.org/?probe=83fd2dc626) | Jul 02, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [e0810c9450](https://linux-hardware.org/?probe=e0810c9450) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| Packard Be... | EasyNote TJ67               | Notebook    | [92be4d3a56](https://linux-hardware.org/?probe=92be4d3a56) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| Dell          | 09T7VV A02                  | Server      | [a63b9c6851](https://linux-hardware.org/?probe=a63b9c6851) | Jul 01, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [e33c7b943c](https://linux-hardware.org/?probe=e33c7b943c) | Jul 01, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | Notebook    | [88b4565c0b](https://linux-hardware.org/?probe=88b4565c0b) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | Notebook    | [7e1b98b585](https://linux-hardware.org/?probe=7e1b98b585) | Jul 01, 2023 |
| HP            | 1998                        | Desktop     | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| Acer          | FRS780M                     | Desktop     | [3066c1772f](https://linux-hardware.org/?probe=3066c1772f) | Jul 01, 2023 |
| Acer          | FRS780M                     | Desktop     | [4f8ad26557](https://linux-hardware.org/?probe=4f8ad26557) | Jul 01, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [7b546735a4](https://linux-hardware.org/?probe=7b546735a4) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [64e81a22a5](https://linux-hardware.org/?probe=64e81a22a5) | Jun 29, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [b36ca5687c](https://linux-hardware.org/?probe=b36ca5687c) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | Notebook    | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Dell          | Latitude 7370               | Notebook    | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3ef19cf418](https://linux-hardware.org/?probe=3ef19cf418) | Jun 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [e39c7f5f6f](https://linux-hardware.org/?probe=e39c7f5f6f) | Jun 28, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [771e2e233a](https://linux-hardware.org/?probe=771e2e233a) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | Notebook    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [e1b714fdf1](https://linux-hardware.org/?probe=e1b714fdf1) | Jun 27, 2023 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [c73458700f](https://linux-hardware.org/?probe=c73458700f) | Jun 27, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f5e04da161](https://linux-hardware.org/?probe=f5e04da161) | Jun 26, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [554a954c22](https://linux-hardware.org/?probe=554a954c22) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [9c925666a5](https://linux-hardware.org/?probe=9c925666a5) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ea814b3f7b](https://linux-hardware.org/?probe=ea814b3f7b) | Jun 26, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [23c2fe2245](https://linux-hardware.org/?probe=23c2fe2245) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7e8503e88](https://linux-hardware.org/?probe=d7e8503e88) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [b33e52fa0a](https://linux-hardware.org/?probe=b33e52fa0a) | Jun 22, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [c63cf5f434](https://linux-hardware.org/?probe=c63cf5f434) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [7782ddf809](https://linux-hardware.org/?probe=7782ddf809) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| HP            | 0B40h                       | Desktop     | [ac50670d44](https://linux-hardware.org/?probe=ac50670d44) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [b34442d8c3](https://linux-hardware.org/?probe=b34442d8c3) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [f9bf8920f7](https://linux-hardware.org/?probe=f9bf8920f7) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [c436287876](https://linux-hardware.org/?probe=c436287876) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [bcd39f0607](https://linux-hardware.org/?probe=bcd39f0607) | Jun 19, 2023 |
| HP            | HDX18                       | Notebook    | [dec8492b2f](https://linux-hardware.org/?probe=dec8492b2f) | Jun 19, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [2fa7c42c59](https://linux-hardware.org/?probe=2fa7c42c59) | Jun 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7a4e69498](https://linux-hardware.org/?probe=b7a4e69498) | Jun 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [cb097e3c83](https://linux-hardware.org/?probe=cb097e3c83) | Jun 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [8b9ddcc1d8](https://linux-hardware.org/?probe=8b9ddcc1d8) | Jun 18, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [8f7aac560c](https://linux-hardware.org/?probe=8f7aac560c) | Jun 18, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [3f18a24757](https://linux-hardware.org/?probe=3f18a24757) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Dell          | Latitude 3189               | Notebook    | [c7f2d1b100](https://linux-hardware.org/?probe=c7f2d1b100) | Jun 17, 2023 |
| HP            | 3397                        | Desktop     | [b9fa9f9e43](https://linux-hardware.org/?probe=b9fa9f9e43) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [93bd9e7b0b](https://linux-hardware.org/?probe=93bd9e7b0b) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [36b0b1204f](https://linux-hardware.org/?probe=36b0b1204f) | Jun 17, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [a62dc4b2ed](https://linux-hardware.org/?probe=a62dc4b2ed) | Jun 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6e0568f0df](https://linux-hardware.org/?probe=6e0568f0df) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [d5d7c6ec90](https://linux-hardware.org/?probe=d5d7c6ec90) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| HP            | HDX18                       | Notebook    | [9a49d14af9](https://linux-hardware.org/?probe=9a49d14af9) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [6b73cb1d75](https://linux-hardware.org/?probe=6b73cb1d75) | Jun 15, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [a8cc966bac](https://linux-hardware.org/?probe=a8cc966bac) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [cc3d8c4659](https://linux-hardware.org/?probe=cc3d8c4659) | Jun 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [1f5318c2b4](https://linux-hardware.org/?probe=1f5318c2b4) | Jun 14, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| Samsung       | 750XED                      | Notebook    | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [39d97bb85b](https://linux-hardware.org/?probe=39d97bb85b) | Jun 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [aca09b2a54](https://linux-hardware.org/?probe=aca09b2a54) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [b815ac19d4](https://linux-hardware.org/?probe=b815ac19d4) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d2cb2b5360](https://linux-hardware.org/?probe=d2cb2b5360) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Dell          | Latitude 9420               | Convertible | [354adf0653](https://linux-hardware.org/?probe=354adf0653) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| Dell          | 0PU052                      | Desktop     | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | Latitude 9420               | Convertible | [593403cb67](https://linux-hardware.org/?probe=593403cb67) | Jun 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [7a36bdb92a](https://linux-hardware.org/?probe=7a36bdb92a) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Dell          | Precision 7540              | Notebook    | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | Notebook    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4895fe7746](https://linux-hardware.org/?probe=4895fe7746) | Jun 05, 2023 |
| Dell          | Precision 7540              | Notebook    | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [5e1bb16065](https://linux-hardware.org/?probe=5e1bb16065) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | Notebook    | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| HP            | 1906                        | Desktop     | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | Desktop     | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [06000e9b0e](https://linux-hardware.org/?probe=06000e9b0e) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [fa8eeaabff](https://linux-hardware.org/?probe=fa8eeaabff) | May 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [bf0674c0f0](https://linux-hardware.org/?probe=bf0674c0f0) | May 28, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| MSI           | CX700                       | Notebook    | [ecb1aaf9c1](https://linux-hardware.org/?probe=ecb1aaf9c1) | May 26, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Dell          | Latitude 5290               | Notebook    | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| AAEON         | UP-CHCR1 V0.4               | Desktop     | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | Precision 7540              | Notebook    | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [52b95d45ca](https://linux-hardware.org/?probe=52b95d45ca) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [b021476220](https://linux-hardware.org/?probe=b021476220) | May 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69f5bff4c0](https://linux-hardware.org/?probe=69f5bff4c0) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Dell          | Precision 7540              | Notebook    | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [50b46e4d8c](https://linux-hardware.org/?probe=50b46e4d8c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| AMI           | Intel                       | Desktop     | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [a655c52b88](https://linux-hardware.org/?probe=a655c52b88) | May 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | Desktop     | [0d2426a070](https://linux-hardware.org/?probe=0d2426a070) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Lenovo        | ThinkPad T410 2537V32       | Notebook    | [cece14e931](https://linux-hardware.org/?probe=cece14e931) | May 21, 2023 |
| HP            | 0A08h                       | Desktop     | [9d159d2637](https://linux-hardware.org/?probe=9d159d2637) | May 21, 2023 |
| AMI           | Intel                       | Desktop     | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b344b7ea03](https://linux-hardware.org/?probe=b344b7ea03) | May 21, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [1f2563578e](https://linux-hardware.org/?probe=1f2563578e) | May 20, 2023 |
| Dell          | Latitude 3120               | Convertible | [ac4bbe967d](https://linux-hardware.org/?probe=ac4bbe967d) | May 19, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [41342ea0f6](https://linux-hardware.org/?probe=41342ea0f6) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [97149ea35b](https://linux-hardware.org/?probe=97149ea35b) | May 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Acer          | Aspire 7535                 | Notebook    | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [215d88c8b6](https://linux-hardware.org/?probe=215d88c8b6) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [d452669f4a](https://linux-hardware.org/?probe=d452669f4a) | May 18, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [beacb75b2c](https://linux-hardware.org/?probe=beacb75b2c) | May 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Dell          | Latitude E5510              | Notebook    | [74ecc09f16](https://linux-hardware.org/?probe=74ecc09f16) | May 17, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [228fa2798d](https://linux-hardware.org/?probe=228fa2798d) | May 16, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32d4567b37](https://linux-hardware.org/?probe=32d4567b37) | May 16, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [de2456eae8](https://linux-hardware.org/?probe=de2456eae8) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3ca79ab5f8](https://linux-hardware.org/?probe=3ca79ab5f8) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [858590e655](https://linux-hardware.org/?probe=858590e655) | May 15, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1efefa9214](https://linux-hardware.org/?probe=1efefa9214) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| HP            | 829D                        | Desktop     | [a9358c228a](https://linux-hardware.org/?probe=a9358c228a) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Xiaomi        | Mipad2                      | Tablet      | [c3c41b0bae](https://linux-hardware.org/?probe=c3c41b0bae) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | Notebook    | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| HP            | EliteBook 720 G2            | Notebook    | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| Dell          | Latitude E7450              | Notebook    | [9dbbae1356](https://linux-hardware.org/?probe=9dbbae1356) | May 12, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [4318c51164](https://linux-hardware.org/?probe=4318c51164) | May 12, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [341a5673f2](https://linux-hardware.org/?probe=341a5673f2) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | 829A                        | Mini pc     | [e51b2da826](https://linux-hardware.org/?probe=e51b2da826) | May 12, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [eefa55009a](https://linux-hardware.org/?probe=eefa55009a) | May 11, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [1e8359a02c](https://linux-hardware.org/?probe=1e8359a02c) | May 11, 2023 |
| Notebook      | N14xWU                      | Notebook    | [0e4f386b46](https://linux-hardware.org/?probe=0e4f386b46) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [99af0c1e17](https://linux-hardware.org/?probe=99af0c1e17) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| Acer          | TravelMate P653-M           | Notebook    | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Dell          | XPS 9315                    | Notebook    | [291a190f04](https://linux-hardware.org/?probe=291a190f04) | May 10, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| Acer          | Aspire M1930                | Desktop     | [712a246ce4](https://linux-hardware.org/?probe=712a246ce4) | May 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [8e4cbc4837](https://linux-hardware.org/?probe=8e4cbc4837) | May 08, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [ec45ea6206](https://linux-hardware.org/?probe=ec45ea6206) | May 08, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| PC Special... | NP5x_NP6x_NP7xPNP           | Notebook    | [72d9dac16b](https://linux-hardware.org/?probe=72d9dac16b) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [148433c97e](https://linux-hardware.org/?probe=148433c97e) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dce7e41a72](https://linux-hardware.org/?probe=dce7e41a72) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [64db3d70f1](https://linux-hardware.org/?probe=64db3d70f1) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0d6a9b046a](https://linux-hardware.org/?probe=0d6a9b046a) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [bdafbe06aa](https://linux-hardware.org/?probe=bdafbe06aa) | May 07, 2023 |
| HP            | 829A                        | Mini pc     | [eba2b6ce4e](https://linux-hardware.org/?probe=eba2b6ce4e) | May 06, 2023 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [01e1d2ef02](https://linux-hardware.org/?probe=01e1d2ef02) | May 05, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| Unknown       | Cherry Trail CR             | Notebook    | [9569a530e8](https://linux-hardware.org/?probe=9569a530e8) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| Intel         | JSL MRD                     | Desktop     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Acer          | TravelMate P214-53          | Notebook    | [8e78c8d139](https://linux-hardware.org/?probe=8e78c8d139) | May 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [f839b22217](https://linux-hardware.org/?probe=f839b22217) | May 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a6a9a6675](https://linux-hardware.org/?probe=0a6a9a6675) | May 03, 2023 |
| Dell          | Latitude 7420               | Notebook    | [7986f6779d](https://linux-hardware.org/?probe=7986f6779d) | May 03, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [dfbf38e06f](https://linux-hardware.org/?probe=dfbf38e06f) | May 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f3b0efc277](https://linux-hardware.org/?probe=f3b0efc277) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| VIOS          | LTH17                       | Notebook    | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [3316360d7a](https://linux-hardware.org/?probe=3316360d7a) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Insyde        | M890BAP                     | Notebook    | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [bd3dba564e](https://linux-hardware.org/?probe=bd3dba564e) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [cab1aa59e0](https://linux-hardware.org/?probe=cab1aa59e0) | Apr 28, 2023 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [36175223a5](https://linux-hardware.org/?probe=36175223a5) | Apr 28, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [fa82c3b6ba](https://linux-hardware.org/?probe=fa82c3b6ba) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c416a3f44a](https://linux-hardware.org/?probe=c416a3f44a) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [589810ee4b](https://linux-hardware.org/?probe=589810ee4b) | Apr 28, 2023 |
| Dell          | Latitude 3301               | Notebook    | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [6b17eb81f8](https://linux-hardware.org/?probe=6b17eb81f8) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Acer          | Aspire X3995                | Desktop     | [877c9deb7a](https://linux-hardware.org/?probe=877c9deb7a) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [37cd92a7f0](https://linux-hardware.org/?probe=37cd92a7f0) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [0b966e7b88](https://linux-hardware.org/?probe=0b966e7b88) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [06fbe4d0b6](https://linux-hardware.org/?probe=06fbe4d0b6) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [2337ae230f](https://linux-hardware.org/?probe=2337ae230f) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [90db0063b0](https://linux-hardware.org/?probe=90db0063b0) | Apr 24, 2023 |
| BTO           | 17X1183                     | Notebook    | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | Notebook    | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | Notebook    | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b906572f4b](https://linux-hardware.org/?probe=b906572f4b) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [65ba6571a2](https://linux-hardware.org/?probe=65ba6571a2) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [2e828158e5](https://linux-hardware.org/?probe=2e828158e5) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | Notebook    | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | Notebook    | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| EVERCOM NE... | Unknown                     | Desktop     | [d36803f05d](https://linux-hardware.org/?probe=d36803f05d) | Apr 21, 2023 |
| HP            | 1494                        | Desktop     | [625373a1de](https://linux-hardware.org/?probe=625373a1de) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [e8332849a1](https://linux-hardware.org/?probe=e8332849a1) | Apr 20, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [bca816c594](https://linux-hardware.org/?probe=bca816c594) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [4e45f9c51f](https://linux-hardware.org/?probe=4e45f9c51f) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [abcb6ed7e8](https://linux-hardware.org/?probe=abcb6ed7e8) | Apr 19, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [213cd129cd](https://linux-hardware.org/?probe=213cd129cd) | Apr 18, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [ae7ea68877](https://linux-hardware.org/?probe=ae7ea68877) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Acer          | Iconia                      | Notebook    | [1ebc88d3ab](https://linux-hardware.org/?probe=1ebc88d3ab) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [6c08e40387](https://linux-hardware.org/?probe=6c08e40387) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [6c62f23970](https://linux-hardware.org/?probe=6c62f23970) | Apr 16, 2023 |
| HP            | 18E7                        | Desktop     | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [5994a04ee0](https://linux-hardware.org/?probe=5994a04ee0) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [ca89b451bd](https://linux-hardware.org/?probe=ca89b451bd) | Apr 15, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [df2e4c0c56](https://linux-hardware.org/?probe=df2e4c0c56) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2c7e1238eb](https://linux-hardware.org/?probe=2c7e1238eb) | Apr 15, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [fcf729207a](https://linux-hardware.org/?probe=fcf729207a) | Apr 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Medion        | MS-7857                     | Desktop     | [5d04997966](https://linux-hardware.org/?probe=5d04997966) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [7f4d0d2d91](https://linux-hardware.org/?probe=7f4d0d2d91) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [f3114cd0d7](https://linux-hardware.org/?probe=f3114cd0d7) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Wortmann      | TERRA_MOBILE_1160           | Notebook    | [d40eed27fd](https://linux-hardware.org/?probe=d40eed27fd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | Desktop     | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d2fbfe344c](https://linux-hardware.org/?probe=d2fbfe344c) | Apr 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3d0ccace69](https://linux-hardware.org/?probe=3d0ccace69) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | Notebook    | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [5a903505c7](https://linux-hardware.org/?probe=5a903505c7) | Apr 10, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Acer          | Aspire M1930                | Desktop     | [2bc158bf57](https://linux-hardware.org/?probe=2bc158bf57) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| Acer          | Spin SP314-51               | Convertible | [4b3e9e100d](https://linux-hardware.org/?probe=4b3e9e100d) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [10213d8aa1](https://linux-hardware.org/?probe=10213d8aa1) | Apr 05, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [b34f7e7ea6](https://linux-hardware.org/?probe=b34f7e7ea6) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [e8a69f8de9](https://linux-hardware.org/?probe=e8a69f8de9) | Apr 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [f211babaa5](https://linux-hardware.org/?probe=f211babaa5) | Apr 04, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ec3a161d36](https://linux-hardware.org/?probe=ec3a161d36) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [316e31eae5](https://linux-hardware.org/?probe=316e31eae5) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [088a09317e](https://linux-hardware.org/?probe=088a09317e) | Apr 04, 2023 |
| HP            | 3032h                       | Desktop     | [75792234b4](https://linux-hardware.org/?probe=75792234b4) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | Notebook    | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| Intel         | VALLEYVIEW C0 PLATFORM      | Tablet      | [3dcf212c95](https://linux-hardware.org/?probe=3dcf212c95) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [c1f349f579](https://linux-hardware.org/?probe=c1f349f579) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ca8ae50d80](https://linux-hardware.org/?probe=ca8ae50d80) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e18d9530c1](https://linux-hardware.org/?probe=e18d9530c1) | Mar 31, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [c3065ba2b6](https://linux-hardware.org/?probe=c3065ba2b6) | Mar 31, 2023 |
| Medion        | Iron238G                    | All in one  | [55cab5c7fa](https://linux-hardware.org/?probe=55cab5c7fa) | Mar 31, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [96107a824d](https://linux-hardware.org/?probe=96107a824d) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | 843F                        | Desktop     | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7edc7c9f47](https://linux-hardware.org/?probe=7edc7c9f47) | Mar 30, 2023 |
| Foxconn       | ETON                        | Desktop     | [52e92b5803](https://linux-hardware.org/?probe=52e92b5803) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39d6f86500](https://linux-hardware.org/?probe=39d6f86500) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | Desktop     | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ZOTAC         | AMD M1                      | Desktop     | [2b2c8fd4fa](https://linux-hardware.org/?probe=2b2c8fd4fa) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5fff36a878](https://linux-hardware.org/?probe=5fff36a878) | Mar 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [55f0bb1013](https://linux-hardware.org/?probe=55f0bb1013) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1ee3769d23](https://linux-hardware.org/?probe=1ee3769d23) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Acer          | Aspire M1930                | Desktop     | [228747d646](https://linux-hardware.org/?probe=228747d646) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | 1494                        | Desktop     | [e682c9975e](https://linux-hardware.org/?probe=e682c9975e) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Medion        | MS-7797                     | Desktop     | [180b0242e8](https://linux-hardware.org/?probe=180b0242e8) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Lenovo        | [3633AC1] STC               | Server      | [aef7266e33](https://linux-hardware.org/?probe=aef7266e33) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [9d7f6de46c](https://linux-hardware.org/?probe=9d7f6de46c) | Mar 19, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [149e050820](https://linux-hardware.org/?probe=149e050820) | Mar 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [5356d2a0ef](https://linux-hardware.org/?probe=5356d2a0ef) | Mar 18, 2023 |
| HP            | 198E                        | Desktop     | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [ba56245418](https://linux-hardware.org/?probe=ba56245418) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [7e2310fcf0](https://linux-hardware.org/?probe=7e2310fcf0) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edf7e8521c](https://linux-hardware.org/?probe=edf7e8521c) | Mar 17, 2023 |
| Dell          | 072T6D A01                  | Server      | [ba5febe33b](https://linux-hardware.org/?probe=ba5febe33b) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [07ac5c2647](https://linux-hardware.org/?probe=07ac5c2647) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [5f261fa554](https://linux-hardware.org/?probe=5f261fa554) | Mar 15, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [a78f938382](https://linux-hardware.org/?probe=a78f938382) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b3e091147a](https://linux-hardware.org/?probe=b3e091147a) | Mar 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [e6d2f2a3b4](https://linux-hardware.org/?probe=e6d2f2a3b4) | Mar 14, 2023 |
| Samsung       | 930QED                      | Convertible | [a3182e0455](https://linux-hardware.org/?probe=a3182e0455) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Dell          | 09N44V A05                  | Server      | [d1a141052c](https://linux-hardware.org/?probe=d1a141052c) | Mar 13, 2023 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [659e2861d9](https://linux-hardware.org/?probe=659e2861d9) | Mar 13, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [53357f1807](https://linux-hardware.org/?probe=53357f1807) | Mar 11, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [3283454c2d](https://linux-hardware.org/?probe=3283454c2d) | Mar 10, 2023 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [14bbc3a006](https://linux-hardware.org/?probe=14bbc3a006) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [49a012cecd](https://linux-hardware.org/?probe=49a012cecd) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f4dd257e1d](https://linux-hardware.org/?probe=f4dd257e1d) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c6119be13a](https://linux-hardware.org/?probe=c6119be13a) | Mar 07, 2023 |
| HP            | 3398                        | Desktop     | [024ce6b407](https://linux-hardware.org/?probe=024ce6b407) | Mar 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [52169be881](https://linux-hardware.org/?probe=52169be881) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [d841b24c32](https://linux-hardware.org/?probe=d841b24c32) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [76243066c7](https://linux-hardware.org/?probe=76243066c7) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [9667db85fc](https://linux-hardware.org/?probe=9667db85fc) | Mar 05, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| ASUSTek       | P5B-MX                      | Desktop     | [823575b2b0](https://linux-hardware.org/?probe=823575b2b0) | Mar 04, 2023 |
| Dell          | Studio XPS 1647             | Notebook    | [484c629656](https://linux-hardware.org/?probe=484c629656) | Mar 04, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b5b5f89ca1](https://linux-hardware.org/?probe=b5b5f89ca1) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Alienware     | m15                         | Notebook    | [180a0251f5](https://linux-hardware.org/?probe=180a0251f5) | Mar 02, 2023 |
| HP            | 3398                        | Desktop     | [6479dbaa0e](https://linux-hardware.org/?probe=6479dbaa0e) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [bbdc843fb2](https://linux-hardware.org/?probe=bbdc843fb2) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [5bc379ea65](https://linux-hardware.org/?probe=5bc379ea65) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | Notebook    | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [6bf890e60c](https://linux-hardware.org/?probe=6bf890e60c) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [323a03f1c6](https://linux-hardware.org/?probe=323a03f1c6) | Feb 27, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [f91140d700](https://linux-hardware.org/?probe=f91140d700) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [66b104fc61](https://linux-hardware.org/?probe=66b104fc61) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [7233b168b4](https://linux-hardware.org/?probe=7233b168b4) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [9398719812](https://linux-hardware.org/?probe=9398719812) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fa08c93ecd](https://linux-hardware.org/?probe=fa08c93ecd) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a3d9851893](https://linux-hardware.org/?probe=a3d9851893) | Feb 23, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [f348e93361](https://linux-hardware.org/?probe=f348e93361) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cd66af8994](https://linux-hardware.org/?probe=cd66af8994) | Feb 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | Notebook    | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [db95126414](https://linux-hardware.org/?probe=db95126414) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | Notebook    | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0a015cdb94](https://linux-hardware.org/?probe=0a015cdb94) | Feb 18, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [5857177f10](https://linux-hardware.org/?probe=5857177f10) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [38c3a4311b](https://linux-hardware.org/?probe=38c3a4311b) | Feb 16, 2023 |
| HP            | 870C                        | Desktop     | [76ae5c62cf](https://linux-hardware.org/?probe=76ae5c62cf) | Feb 15, 2023 |
| Medion        | MS-7616                     | Desktop     | [0655a4e58c](https://linux-hardware.org/?probe=0655a4e58c) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d2754bf08f](https://linux-hardware.org/?probe=d2754bf08f) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | Notebook    | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Acer          | Aspire M1930                | Desktop     | [3b78f6fb4e](https://linux-hardware.org/?probe=3b78f6fb4e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [ea169af948](https://linux-hardware.org/?probe=ea169af948) | Feb 13, 2023 |
| HP            | 843F                        | Desktop     | [3047a0ff5b](https://linux-hardware.org/?probe=3047a0ff5b) | Feb 13, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [672b71db3e](https://linux-hardware.org/?probe=672b71db3e) | Feb 12, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [f5a8290d38](https://linux-hardware.org/?probe=f5a8290d38) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| Dell          | Latitude 3120               | Convertible | [3bf2bfe867](https://linux-hardware.org/?probe=3bf2bfe867) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [0779ef912a](https://linux-hardware.org/?probe=0779ef912a) | Feb 08, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [bb851866ac](https://linux-hardware.org/?probe=bb851866ac) | Feb 08, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [e92a6b0131](https://linux-hardware.org/?probe=e92a6b0131) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [cdc1678cae](https://linux-hardware.org/?probe=cdc1678cae) | Feb 07, 2023 |
| Dell          | Latitude E6320              | Notebook    | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2e581dc622](https://linux-hardware.org/?probe=2e581dc622) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3b4320a91a](https://linux-hardware.org/?probe=3b4320a91a) | Feb 06, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [33639358ab](https://linux-hardware.org/?probe=33639358ab) | Feb 06, 2023 |
| Standard      | Unknown                     | Notebook    | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| MSI           | MS-7376                     | Desktop     | [5f62748624](https://linux-hardware.org/?probe=5f62748624) | Feb 04, 2023 |
| MSI           | MS-7376                     | Desktop     | [33fa767f72](https://linux-hardware.org/?probe=33fa767f72) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [04c5cc4aec](https://linux-hardware.org/?probe=04c5cc4aec) | Feb 04, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [82a573d8cd](https://linux-hardware.org/?probe=82a573d8cd) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b9e4e36496](https://linux-hardware.org/?probe=b9e4e36496) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [ac1f8787af](https://linux-hardware.org/?probe=ac1f8787af) | Feb 03, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [e68a009e8f](https://linux-hardware.org/?probe=e68a009e8f) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [66b96d9a0f](https://linux-hardware.org/?probe=66b96d9a0f) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4dbe55873b](https://linux-hardware.org/?probe=4dbe55873b) | Jan 31, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [30a093116e](https://linux-hardware.org/?probe=30a093116e) | Jan 30, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [fb0dcf8d7e](https://linux-hardware.org/?probe=fb0dcf8d7e) | Jan 28, 2023 |
| HP            | 17E2                        | Mini pc     | [41fdb27963](https://linux-hardware.org/?probe=41fdb27963) | Jan 28, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Dell          | 0599V5 A12                  | Server      | [14f503ae4a](https://linux-hardware.org/?probe=14f503ae4a) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [97d1ab1b7d](https://linux-hardware.org/?probe=97d1ab1b7d) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| HP            | 8055                        | Desktop     | [81fa44d8fa](https://linux-hardware.org/?probe=81fa44d8fa) | Jan 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b1079b0bf](https://linux-hardware.org/?probe=1b1079b0bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [ab38ecfb97](https://linux-hardware.org/?probe=ab38ecfb97) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [b5cb34ea4d](https://linux-hardware.org/?probe=b5cb34ea4d) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | Notebook    | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47ff2a2e42](https://linux-hardware.org/?probe=47ff2a2e42) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a3672f1d47](https://linux-hardware.org/?probe=a3672f1d47) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [7630683952](https://linux-hardware.org/?probe=7630683952) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0a3f1269f7](https://linux-hardware.org/?probe=0a3f1269f7) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [733770beaf](https://linux-hardware.org/?probe=733770beaf) | Jan 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [40cc1bf7d9](https://linux-hardware.org/?probe=40cc1bf7d9) | Jan 21, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [325f9e8310](https://linux-hardware.org/?probe=325f9e8310) | Jan 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [4a2292e809](https://linux-hardware.org/?probe=4a2292e809) | Jan 19, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [1a61029965](https://linux-hardware.org/?probe=1a61029965) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | Notebook    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [798a545fa8](https://linux-hardware.org/?probe=798a545fa8) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [411db3ea66](https://linux-hardware.org/?probe=411db3ea66) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f0ce1e8b3f](https://linux-hardware.org/?probe=f0ce1e8b3f) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [2cc8923eb1](https://linux-hardware.org/?probe=2cc8923eb1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | Notebook    | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [01c0e96288](https://linux-hardware.org/?probe=01c0e96288) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [85d6a0b721](https://linux-hardware.org/?probe=85d6a0b721) | Jan 13, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 582       | 13.47%  |
| Ubuntu 18.04                 | 305       | 7.06%   |
| Ubuntu 22.04                 | 243       | 5.62%   |
| OpenMandriva 4.3             | 196       | 4.54%   |
| Debian 11                    | 106       | 2.45%   |
| Zorin 16                     | 93        | 2.15%   |
| Linux Mint 20.3              | 78        | 1.81%   |
| Ubuntu 20.10                 | 66        | 1.53%   |
| Arch                         | 66        | 1.53%   |
| Arch Rolling                 | 63        | 1.46%   |
| Pop!_OS 22.04                | 61        | 1.41%   |
| Manjaro                      | 61        | 1.41%   |
| Linux Mint 21.1              | 61        | 1.41%   |
| Xubuntu 20.04                | 56        | 1.3%    |
| OpenMandriva 4.2             | 55        | 1.27%   |
| KDE neon 20.04               | 54        | 1.25%   |
| openSUSE Tumbleweed-XXXXXXXX | 53        | 1.23%   |
| Fedora 36                    | 53        | 1.23%   |
| Fedora 34                    | 53        | 1.23%   |
| Linux Mint 20.2              | 52        | 1.2%    |
| Ubuntu 21.10                 | 51        | 1.18%   |
| Fedora 37                    | 49        | 1.13%   |
| Ubuntu 21.04                 | 46        | 1.06%   |
| Linux Mint 20.1              | 46        | 1.06%   |
| Linux Mint 19.3              | 46        | 1.06%   |
| Fedora 38                    | 45        | 1.04%   |
| Fedora 35                    | 44        | 1.02%   |
| Ubuntu 19.10                 | 43        | 1%      |
| Pop!_OS 20.10                | 41        | 0.95%   |
| Fedora 33                    | 41        | 0.95%   |
| ArcoLinux Rolling            | 41        | 0.95%   |
| Pop!_OS 21.04                | 39        | 0.9%    |
| Pop!_OS 20.04                | 39        | 0.9%    |
| Zorin 15                     | 38        | 0.88%   |
| Linux Mint 20                | 38        | 0.88%   |
| Kubuntu 20.04                | 38        | 0.88%   |
| Fedora 31                    | 38        | 0.88%   |
| Ubuntu 22.10                 | 37        | 0.86%   |
| Ubuntu 19.04                 | 35        | 0.81%   |
| Pop!_OS 21.10                | 35        | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1400      | 34.15%  |
| Linux Mint    | 372       | 9.07%   |
| OpenMandriva  | 325       | 7.93%   |
| Fedora        | 325       | 7.93%   |
| Pop!_OS       | 207       | 5.05%   |
| Debian        | 173       | 4.22%   |
| Manjaro       | 160       | 3.9%    |
| Zorin         | 140       | 3.41%   |
| Arch          | 130       | 3.17%   |
| Xubuntu       | 98        | 2.39%   |
| Kubuntu       | 93        | 2.27%   |
| KDE neon      | 77        | 1.88%   |
| openSUSE      | 69        | 1.68%   |
| ArcoLinux     | 44        | 1.07%   |
| EndeavourOS   | 32        | 0.78%   |
| Gentoo        | 31        | 0.76%   |
| Kali          | 30        | 0.73%   |
| Elementary    | 30        | 0.73%   |
| ROSA          | 27        | 0.66%   |
| Lubuntu       | 26        | 0.63%   |
| Ubuntu Unity  | 23        | 0.56%   |
| Ubuntu MATE   | 21        | 0.51%   |
| SteamOS       | 21        | 0.51%   |
| Clear Linux   | 20        | 0.49%   |
| Parrot        | 16        | 0.39%   |
| Endless       | 16        | 0.39%   |
| Ubuntu Budgie | 14        | 0.34%   |
| LMDE          | 13        | 0.32%   |
| MX            | 12        | 0.29%   |
| Nobara        | 11        | 0.27%   |
| Garuda Linux  | 11        | 0.27%   |
| Solus         | 10        | 0.24%   |
| Raspbian      | 10        | 0.24%   |
| Peppermint    | 10        | 0.24%   |
| CentOS        | 10        | 0.24%   |
| BlackPanther  | 6         | 0.15%   |
| RHEL          | 5         | 0.12%   |
| Reborn OS     | 5         | 0.12%   |
| Void Linux    | 4         | 0.1%    |
| NixOS         | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 195       | 4.06%   |
| 5.4.0-42-generic         | 69        | 1.44%   |
| 5.10.14-desktop-1omv4002 | 54        | 1.12%   |
| 5.4.0-58-generic         | 43        | 0.89%   |
| 5.8.0-50-generic         | 42        | 0.87%   |
| 5.15.0-56-generic        | 39        | 0.81%   |
| 5.15.0-58-generic        | 37        | 0.77%   |
| 5.4.0-52-generic         | 36        | 0.75%   |
| 5.4.0-48-generic         | 35        | 0.73%   |
| 5.11.0-38-generic        | 33        | 0.69%   |
| 5.15.0-46-generic        | 30        | 0.62%   |
| 6.1.1-desktop-1omv2290   | 28        | 0.58%   |
| 6.2.6-desktop-1omv2390   | 27        | 0.56%   |
| 5.8.0-43-generic         | 26        | 0.54%   |
| 5.4.0-26-generic         | 26        | 0.54%   |
| 5.13.0-28-generic        | 26        | 0.54%   |
| 5.11.0-27-generic        | 26        | 0.54%   |
| 5.4.0-77-generic         | 25        | 0.52%   |
| 5.15.0-52-generic        | 25        | 0.52%   |
| 5.4.0-40-generic         | 24        | 0.5%    |
| 5.15.0-43-generic        | 24        | 0.5%    |
| 5.19.0-35-generic        | 23        | 0.48%   |
| 5.4.0-37-generic         | 22        | 0.46%   |
| 5.15.0-48-generic        | 22        | 0.46%   |
| 5.8.0-53-generic         | 21        | 0.44%   |
| 5.4.0-65-generic         | 21        | 0.44%   |
| 5.15.0-67-generic        | 21        | 0.44%   |
| 5.15.0-60-generic        | 21        | 0.44%   |
| 5.13.0-39-generic        | 21        | 0.44%   |
| 5.11.0-7620-generic      | 21        | 0.44%   |
| 5.8.0-7630-generic       | 20        | 0.42%   |
| 5.4.0-56-generic         | 20        | 0.42%   |
| 5.4.0-33-generic         | 20        | 0.42%   |
| 5.4.0-29-generic         | 20        | 0.42%   |
| 5.3.0-46-generic         | 19        | 0.4%    |
| 5.8.0-48-generic         | 18        | 0.37%   |
| 5.4.0-54-generic         | 18        | 0.37%   |
| 5.4.0-47-generic         | 18        | 0.37%   |
| 5.11.0-43-generic        | 18        | 0.37%   |
| 5.11.0-37-generic        | 18        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 721       | 16.01%  |
| 5.15.0  | 401       | 8.91%   |
| 5.8.0   | 285       | 6.33%   |
| 4.15.0  | 241       | 5.35%   |
| 5.11.0  | 236       | 5.24%   |
| 5.13.0  | 202       | 4.49%   |
| 5.16.7  | 198       | 4.4%    |
| 5.19.0  | 150       | 3.33%   |
| 5.3.0   | 141       | 3.13%   |
| 5.10.0  | 123       | 2.73%   |
| 5.0.0   | 106       | 2.35%   |
| 4.18.0  | 72        | 1.6%    |
| 5.10.14 | 57        | 1.27%   |
| 6.2.6   | 43        | 0.95%   |
| 6.2.0   | 37        | 0.82%   |
| 4.19.0  | 37        | 0.82%   |
| 6.1.1   | 32        | 0.71%   |
| 6.1.0   | 25        | 0.56%   |
| 5.14.0  | 24        | 0.53%   |
| 4.4.0   | 18        | 0.4%    |
| 5.6.0   | 16        | 0.36%   |
| 5.16.11 | 16        | 0.36%   |
| 5.17.5  | 15        | 0.33%   |
| 6.0.6   | 14        | 0.31%   |
| 5.9.16  | 14        | 0.31%   |
| 6.3.0   | 13        | 0.29%   |
| 6.3.8   | 12        | 0.27%   |
| 6.0.0   | 12        | 0.27%   |
| 5.3.18  | 11        | 0.24%   |
| 5.18.0  | 11        | 0.24%   |
| 5.17.1  | 11        | 0.24%   |
| 6.4.6   | 10        | 0.22%   |
| 6.0.12  | 10        | 0.22%   |
| 5.17.0  | 10        | 0.22%   |
| 5.16.0  | 10        | 0.22%   |
| 6.2.9   | 9         | 0.2%    |
| 6.2.8   | 9         | 0.2%    |
| 5.9.8   | 9         | 0.2%    |
| 5.9.0   | 9         | 0.2%    |
| 5.8.16  | 9         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 785       | 17.64%  |
| 5.15    | 514       | 11.55%  |
| 5.8     | 336       | 7.55%   |
| 5.11    | 282       | 6.34%   |
| 5.16    | 265       | 5.96%   |
| 5.10    | 246       | 5.53%   |
| 5.13    | 244       | 5.48%   |
| 4.15    | 242       | 5.44%   |
| 5.19    | 188       | 4.22%   |
| 5.3     | 173       | 3.89%   |
| 6.2     | 133       | 2.99%   |
| 6.1     | 130       | 2.92%   |
| 5.0     | 110       | 2.47%   |
| 4.18    | 86        | 1.93%   |
| 6.0     | 84        | 1.89%   |
| 6.3     | 70        | 1.57%   |
| 5.17    | 69        | 1.55%   |
| 5.14    | 63        | 1.42%   |
| 5.18    | 61        | 1.37%   |
| 5.9     | 56        | 1.26%   |
| 5.6     | 51        | 1.15%   |
| 4.19    | 50        | 1.12%   |
| 5.12    | 36        | 0.81%   |
| 5.7     | 32        | 0.72%   |
| 5.5     | 28        | 0.63%   |
| 6.4     | 27        | 0.61%   |
| 4.9     | 26        | 0.58%   |
| 4.4     | 20        | 0.45%   |
| 5.2     | 9         | 0.2%    |
| 4.16    | 5         | 0.11%   |
| 4.10    | 5         | 0.11%   |
| 4.20    | 4         | 0.09%   |
| 4.14    | 4         | 0.09%   |
| 4.12    | 4         | 0.09%   |
| 3.10    | 3         | 0.07%   |
| 4.1     | 2         | 0.04%   |
| 3.16    | 2         | 0.04%   |
| 5.17.1  | 1         | 0.02%   |
| 5.1     | 1         | 0.02%   |
| 4.7     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3827      | 96.16%  |
| i686    | 102       | 2.56%   |
| aarch64 | 42        | 1.06%   |
| armv7l  | 7         | 0.18%   |
| armv8l  | 1         | 0.03%   |
| armv6l  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1839      | 44.42%  |
| KDE5             | 724       | 17.49%  |
| Unknown          | 540       | 13.04%  |
| XFCE             | 291       | 7.03%   |
| X-Cinnamon       | 282       | 6.81%   |
| MATE             | 93        | 2.25%   |
| KDE              | 93        | 2.25%   |
| Cinnamon         | 37        | 0.89%   |
| Pantheon         | 30        | 0.72%   |
| LXQt             | 28        | 0.68%   |
| LXDE             | 27        | 0.65%   |
| i3               | 25        | 0.6%    |
| Budgie           | 25        | 0.6%    |
| Unity            | 23        | 0.56%   |
| KDE4             | 16        | 0.39%   |
| GNOME Flashback  | 12        | 0.29%   |
| Deepin           | 8         | 0.19%   |
| openbox          | 7         | 0.17%   |
| sway             | 6         | 0.14%   |
| ICEWM            | 5         | 0.12%   |
| Enlightenment    | 5         | 0.12%   |
| qtile            | 4         | 0.1%    |
| awesome          | 4         | 0.1%    |
| lightdm-xsession | 3         | 0.07%   |
| Trinity          | 2         | 0.05%   |
| GNOME Classic    | 2         | 0.05%   |
| xmonad           | 1         | 0.02%   |
| LeftWM           | 1         | 0.02%   |
| jwm              | 1         | 0.02%   |
| herbstluftwm     | 1         | 0.02%   |
| fluxbox          | 1         | 0.02%   |
| DWM              | 1         | 0.02%   |
| dusk             | 1         | 0.02%   |
| Core             | 1         | 0.02%   |
| bspwm            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3055      | 74.9%   |
| Wayland | 671       | 16.45%  |
| Unknown | 263       | 6.45%   |
| Tty     | 89        | 2.18%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2074      | 50.36%  |
| SDDM    | 607       | 14.74%  |
| GDM     | 475       | 11.53%  |
| GDM3    | 461       | 11.19%  |
| LightDM | 370       | 8.98%   |
| TDM     | 94        | 2.28%   |
| KDM     | 15        | 0.36%   |
| XDM     | 8         | 0.19%   |
| Ly      | 4         | 0.1%    |
| SLiM    | 3         | 0.07%   |
| GREETD  | 3         | 0.07%   |
| LXDM    | 2         | 0.05%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1968      | 48.26%  |
| nl_NL       | 1161      | 28.47%  |
| Unknown     | 433       | 10.62%  |
| en_GB       | 167       | 4.1%    |
| C           | 67        | 1.64%   |
| de_DE       | 43        | 1.05%   |
| pl_PL       | 34        | 0.83%   |
| ru_RU       | 29        | 0.71%   |
| fr_FR       | 15        | 0.37%   |
| en_IE       | 14        | 0.34%   |
| POSIX       | 13        | 0.32%   |
| en_NL       | 13        | 0.32%   |
| it_IT       | 8         | 0.2%    |
| es_ES       | 7         | 0.17%   |
| en_IN       | 7         | 0.17%   |
| en_CA       | 7         | 0.17%   |
| fr_BE       | 5         | 0.12%   |
| en_DK       | 5         | 0.12%   |
| en_AG       | 5         | 0.12%   |
| C.UTF8      | 5         | 0.12%   |
| sv_SE       | 4         | 0.1%    |
| sk_SK       | 4         | 0.1%    |
| ru_UA       | 4         | 0.1%    |
| pt_PT       | 4         | 0.1%    |
| nl_BE       | 4         | 0.1%    |
| es_MX       | 4         | 0.1%    |
| de_AT       | 4         | 0.1%    |
| nb_NO       | 3         | 0.07%   |
| hu_HU       | 3         | 0.07%   |
| en_US.utf-8 | 3         | 0.07%   |
| en_AU       | 3         | 0.07%   |
| cs_CZ       | 3         | 0.07%   |
| zh_CN       | 2         | 0.05%   |
| uk_UA       | 2         | 0.05%   |
| tr_TR       | 2         | 0.05%   |
| pt_BR       | 2         | 0.05%   |
| nl_AW       | 2         | 0.05%   |
| en_ZA       | 2         | 0.05%   |
| en_SG       | 2         | 0.05%   |
| ar_KW       | 2         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2107      | 51.91%  |
| BIOS | 1952      | 48.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3032      | 74.42%  |
| Btrfs   | 371       | 9.11%   |
| Overlay | 363       | 8.91%   |
| Unknown | 125       | 3.07%   |
| Tmpfs   | 63        | 1.55%   |
| Xfs     | 51        | 1.25%   |
| Zfs     | 41        | 1.01%   |
| Ext2    | 10        | 0.25%   |
| F2fs    | 9         | 0.22%   |
| Ext3    | 5         | 0.12%   |
| Aufs    | 3         | 0.07%   |
| Jfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2197      | 54.13%  |
| GPT     | 1517      | 37.37%  |
| MBR     | 345       | 8.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3458      | 85.45%  |
| Yes       | 589       | 14.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2841      | 70.51%  |
| Yes       | 1188      | 29.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 639       | 16.08%  |
| Hewlett-Packard         | 621       | 15.63%  |
| ASUSTek Computer        | 559       | 14.07%  |
| Lenovo                  | 451       | 11.35%  |
| Acer                    | 242       | 6.09%   |
| Gigabyte Technology     | 222       | 5.59%   |
| MSI                     | 220       | 5.54%   |
| ASRock                  | 164       | 4.13%   |
| Apple                   | 127       | 3.2%    |
| Intel                   | 88        | 2.21%   |
| Medion                  | 61        | 1.54%   |
| Toshiba                 | 57        | 1.43%   |
| Notebook                | 55        | 1.38%   |
| Raspberry Pi Foundation | 44        | 1.11%   |
| Unknown                 | 29        | 0.73%   |
| Packard Bell            | 28        | 0.7%    |
| Samsung Electronics     | 26        | 0.65%   |
| Fujitsu                 | 23        | 0.58%   |
| Google                  | 19        | 0.48%   |
| Valve                   | 18        | 0.45%   |
| Sony                    | 17        | 0.43%   |
| Microsoft               | 16        | 0.4%    |
| HUAWEI                  | 14        | 0.35%   |
| Fujitsu Siemens         | 13        | 0.33%   |
| Foxconn                 | 12        | 0.3%    |
| Alienware               | 10        | 0.25%   |
| Supermicro              | 9         | 0.23%   |
| Pegatron                | 9         | 0.23%   |
| Biostar                 | 7         | 0.18%   |
| BESSTAR Tech            | 7         | 0.18%   |
| AMI                     | 7         | 0.18%   |
| TUXEDO                  | 6         | 0.15%   |
| Timi                    | 6         | 0.15%   |
| Shuttle                 | 6         | 0.15%   |
| Insyde                  | 6         | 0.15%   |
| ZOTAC                   | 5         | 0.13%   |
| PC Specialist           | 5         | 0.13%   |
| Chuwi                   | 5         | 0.13%   |
| System76                | 4         | 0.1%    |
| SLIMBOOK                | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude 3120                  | 56        | 1.41%   |
| Dell Latitude 3190 2-in-1           | 41        | 1.03%   |
| Unknown                             | 41        | 1.03%   |
| Dell Latitude 3310                  | 32        | 0.81%   |
| ASUS All Series                     | 30        | 0.76%   |
| Valve Jupiter                       | 18        | 0.45%   |
| RPi Raspberry Pi                    | 17        | 0.43%   |
| Dell XPS 15 7590                    | 12        | 0.3%    |
| Dell OptiPlex 7010                  | 12        | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 10        | 0.25%   |
| MSI MS-7C02                         | 10        | 0.25%   |
| HP Notebook                         | 10        | 0.25%   |
| Apple MacBookPro9,2                 | 10        | 0.25%   |
| HP Pavilion dv7                     | 9         | 0.23%   |
| Dell XPS 15 9560                    | 9         | 0.23%   |
| MSI MS-7C37                         | 8         | 0.2%    |
| HP ZBook Studio G5                  | 8         | 0.2%    |
| HP Pavilion g7                      | 8         | 0.2%    |
| Dell OptiPlex 3020                  | 8         | 0.2%    |
| Dell Latitude E6410                 | 8         | 0.2%    |
| Dell Latitude 3300                  | 8         | 0.2%    |
| ASRock B450M Pro4                   | 8         | 0.2%    |
| MSI MS-7B86                         | 7         | 0.18%   |
| MSI MS-7817                         | 7         | 0.18%   |
| HP ProBook 6570b                    | 7         | 0.18%   |
| HP Pavilion Laptop 15-cw1xxx        | 7         | 0.18%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 7         | 0.18%   |
| HP Pavilion g6                      | 7         | 0.18%   |
| Dell XPS 15 9500                    | 7         | 0.18%   |
| Dell XPS 13 9310                    | 7         | 0.18%   |
| Dell Latitude 3189                  | 7         | 0.18%   |
| MSI MS-7721                         | 6         | 0.15%   |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 6         | 0.15%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 6         | 0.15%   |
| Intel NUC8i3BEH                     | 6         | 0.15%   |
| HP Pavilion dv6                     | 6         | 0.15%   |
| HP EliteBook 8570w                  | 6         | 0.15%   |
| HP EliteBook 8460p                  | 6         | 0.15%   |
| HP Compaq Elite 8300 SFF            | 6         | 0.15%   |
| HP Compaq dc7900 Small Form Factor  | 6         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 322       | 8.1%    |
| Lenovo ThinkPad       | 225       | 5.66%   |
| Acer Aspire           | 163       | 4.1%    |
| HP EliteBook          | 106       | 2.67%   |
| Dell XPS              | 105       | 2.64%   |
| HP Pavilion           | 104       | 2.62%   |
| HP Compaq             | 104       | 2.62%   |
| Lenovo IdeaPad        | 74        | 1.86%   |
| HP ProBook            | 70        | 1.76%   |
| Dell OptiPlex         | 67        | 1.69%   |
| ASUS PRIME            | 60        | 1.51%   |
| ASUS ROG              | 54        | 1.36%   |
| Toshiba Satellite     | 52        | 1.31%   |
| Dell Inspiron         | 51        | 1.28%   |
| RPi Raspberry         | 44        | 1.11%   |
| Unknown               | 41        | 1.03%   |
| HP ZBook              | 37        | 0.93%   |
| Dell Precision        | 37        | 0.93%   |
| Lenovo Yoga           | 32        | 0.81%   |
| ASUS All              | 30        | 0.76%   |
| Lenovo Legion         | 29        | 0.73%   |
| HP ENVY               | 29        | 0.73%   |
| ASUS VivoBook         | 23        | 0.58%   |
| ASUS TUF              | 22        | 0.55%   |
| Packard Bell EasyNote | 21        | 0.53%   |
| HP Laptop             | 21        | 0.53%   |
| Gigabyte X570         | 21        | 0.53%   |
| Valve Jupiter         | 18        | 0.45%   |
| Lenovo ThinkCentre    | 18        | 0.45%   |
| Lenovo ThinkBook      | 17        | 0.43%   |
| Microsoft Surface     | 16        | 0.4%    |
| Acer TravelMate       | 16        | 0.4%    |
| HP ProDesk            | 15        | 0.38%   |
| ASUS ZenBook          | 15        | 0.38%   |
| Acer Swift            | 14        | 0.35%   |
| Fujitsu LIFEBOOK      | 13        | 0.33%   |
| HP Spectre            | 12        | 0.3%    |
| HP EliteDesk          | 12        | 0.3%    |
| ASRock B450M          | 12        | 0.3%    |
| Dell Studio           | 11        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 459       | 11.55%  |
| 2018    | 351       | 8.83%   |
| 2020    | 311       | 7.83%   |
| 2021    | 300       | 7.55%   |
| 2012    | 297       | 7.48%   |
| 2011    | 263       | 6.62%   |
| 2013    | 254       | 6.39%   |
| 2017    | 237       | 5.97%   |
| 2014    | 215       | 5.41%   |
| 2010    | 203       | 5.11%   |
| 2016    | 197       | 4.96%   |
| 2015    | 192       | 4.83%   |
| 2008    | 156       | 3.93%   |
| 2009    | 155       | 3.9%    |
| 2022    | 135       | 3.4%    |
| 2007    | 114       | 2.87%   |
| 2006    | 50        | 1.26%   |
| Unknown | 46        | 1.16%   |
| 2023    | 15        | 0.38%   |
| 2005    | 13        | 0.33%   |
| 2004    | 6         | 0.15%   |
| 2003    | 3         | 0.08%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2111      | 53.13%  |
| Desktop        | 1391      | 35.01%  |
| Convertible    | 200       | 5.03%   |
| Mini pc        | 98        | 2.47%   |
| All in one     | 54        | 1.36%   |
| System on chip | 48        | 1.21%   |
| Tablet         | 42        | 1.06%   |
| Server         | 27        | 0.68%   |
| Phone          | 2         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3677      | 91.88%  |
| Enabled  | 325       | 8.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3948      | 99.37%  |
| Yes  | 25        | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 924       | 22.88%  |
| 16.01-24.0      | 845       | 20.92%  |
| 3.01-4.0        | 727       | 18%     |
| 8.01-16.0       | 680       | 16.84%  |
| 32.01-64.0      | 423       | 10.47%  |
| 1.01-2.0        | 150       | 3.71%   |
| 64.01-256.0     | 106       | 2.62%   |
| 24.01-32.0      | 74        | 1.83%   |
| 2.01-3.0        | 72        | 1.78%   |
| 0.51-1.0        | 36        | 0.89%   |
| More than 256.0 | 1         | 0.02%   |
| 0.01-0.5        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1587      | 36.23%  |
| 2.01-3.0    | 1021      | 23.31%  |
| 4.01-8.0    | 617       | 14.09%  |
| 3.01-4.0    | 558       | 12.74%  |
| 0.51-1.0    | 282       | 6.44%   |
| 8.01-16.0   | 218       | 4.98%   |
| 0.01-0.5    | 42        | 0.96%   |
| 16.01-24.0  | 39        | 0.89%   |
| 32.01-64.0  | 12        | 0.27%   |
| 24.01-32.0  | 3         | 0.07%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2402      | 58.96%  |
| 2       | 996       | 24.45%  |
| 3       | 314       | 7.71%   |
| 4       | 155       | 3.8%    |
| 5       | 79        | 1.94%   |
| 0       | 54        | 1.33%   |
| 6       | 33        | 0.81%   |
| 7       | 24        | 0.59%   |
| 8       | 6         | 0.15%   |
| 9       | 4         | 0.1%    |
| Unknown | 4         | 0.1%    |
| 28      | 1         | 0.02%   |
| 27      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2538      | 63.34%  |
| Yes       | 1469      | 36.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3320      | 83.29%  |
| No        | 666       | 16.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2951      | 73.92%  |
| No        | 1041      | 26.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2410      | 59.67%  |
| No        | 1629      | 40.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 3973      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 747       | 17.62%  |
| The Hague              | 208       | 4.91%   |
| Rotterdam              | 146       | 3.44%   |
| Schagen                | 142       | 3.35%   |
| Utrecht                | 103       | 2.43%   |
| Delft                  | 92        | 2.17%   |
| Haarlem                | 80        | 1.89%   |
| Groningen              | 71        | 1.67%   |
| Almere Stad            | 66        | 1.56%   |
| Eindhoven              | 60        | 1.42%   |
| Naaldwijk              | 54        | 1.27%   |
| Amersfoort             | 48        | 1.13%   |
| Tilburg                | 47        | 1.11%   |
| Enschede               | 45        | 1.06%   |
| Leiden                 | 42        | 0.99%   |
| Zoetermeer             | 35        | 0.83%   |
| Nijmegen               | 34        | 0.8%    |
| Arnhem                 | 34        | 0.8%    |
| Apeldoorn              | 32        | 0.75%   |
| Breda                  | 30        | 0.71%   |
| Almelo                 | 29        | 0.68%   |
| Zwolle                 | 25        | 0.59%   |
| Zeist                  | 24        | 0.57%   |
| Roosendaal             | 24        | 0.57%   |
| Hilversum              | 24        | 0.57%   |
| Lelystad               | 23        | 0.54%   |
| Capelle aan den IJssel | 23        | 0.54%   |
| Assen                  | 23        | 0.54%   |
| Maastricht             | 22        | 0.52%   |
| Heerlen                | 22        | 0.52%   |
| Dordrecht              | 22        | 0.52%   |
| Amstelveen             | 22        | 0.52%   |
| Purmerend              | 21        | 0.5%    |
| Alkmaar                | 21        | 0.5%    |
| 's-Hertogenbosch       | 20        | 0.47%   |
| Hoofddorp              | 19        | 0.45%   |
| Gouda                  | 19        | 0.45%   |
| Schiedam               | 18        | 0.42%   |
| Leeuwarden             | 18        | 0.42%   |
| Meppel                 | 17        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1316      | 2142   | 22.99%  |
| WDC                         | 752       | 1157   | 13.14%  |
| Seagate                     | 687       | 1082   | 12%     |
| Kingston                    | 344       | 456    | 6.01%   |
| Toshiba                     | 314       | 431    | 5.48%   |
| SanDisk                     | 261       | 348    | 4.56%   |
| Crucial                     | 249       | 322    | 4.35%   |
| Unknown                     | 241       | 301    | 4.21%   |
| SK hynix                    | 201       | 236    | 3.51%   |
| Intel                       | 170       | 227    | 2.97%   |
| Hitachi                     | 169       | 217    | 2.95%   |
| HGST                        | 96        | 120    | 1.68%   |
| Micron Technology           | 76        | 91     | 1.33%   |
| A-DATA Technology           | 63        | 69     | 1.1%    |
| KIOXIA                      | 55        | 69     | 0.96%   |
| Apple                       | 55        | 77     | 0.96%   |
| LITEON                      | 42        | 53     | 0.73%   |
| OCZ                         | 31        | 39     | 0.54%   |
| Maxtor                      | 31        | 43     | 0.54%   |
| China                       | 31        | 44     | 0.54%   |
| Phison                      | 28        | 41     | 0.49%   |
| Corsair                     | 27        | 36     | 0.47%   |
| PNY                         | 25        | 30     | 0.44%   |
| LITEONIT                    | 25        | 28     | 0.44%   |
| Transcend                   | 23        | 28     | 0.4%    |
| Kingston Technology Company | 22        | 25     | 0.38%   |
| Fujitsu                     | 21        | 23     | 0.37%   |
| SSSTC                       | 20        | 22     | 0.35%   |
| Intenso                     | 18        | 18     | 0.31%   |
| ASMT                        | 17        | 20     | 0.3%    |
| Micron/Crucial Technology   | 16        | 20     | 0.28%   |
| GOODRAM                     | 16        | 17     | 0.28%   |
| Gigabyte Technology         | 16        | 21     | 0.28%   |
| Unknown                     | 16        | 19     | 0.28%   |
| Patriot                     | 14        | 17     | 0.24%   |
| JMicron Technology          | 14        | 21     | 0.24%   |
| SPCC                        | 13        | 14     | 0.23%   |
| KingFast                    | 13        | 17     | 0.23%   |
| Phison Electronics          | 12        | 16     | 0.21%   |
| XPG                         | 9         | 11     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 96        | 1.49%   |
| Samsung SSD 860 EVO 500GB                           | 69        | 1.07%   |
| Samsung SSD 850 EVO 500GB                           | 68        | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 63        | 0.98%   |
| Samsung NVMe SSD Drive 500GB                        | 47        | 0.73%   |
| Kingston SA400S37240G 240GB SSD                     | 47        | 0.73%   |
| Samsung NVMe SSD Drive 1TB                          | 46        | 0.71%   |
| Unknown MMC Card  32GB                              | 44        | 0.68%   |
| Samsung SSD 840 EVO 250GB                           | 41        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 40        | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 36        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                        | 36        | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 35        | 0.54%   |
| Seagate Expansion 1TB                               | 33        | 0.51%   |
| Samsung SSD 840 EVO 120GB                           | 33        | 0.51%   |
| Kingston SV300S37A120G 120GB SSD                    | 33        | 0.51%   |
| Unknown MMC Card  64GB                              | 31        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                     | 30        | 0.47%   |
| Samsung SSD 980 1TB                                 | 30        | 0.47%   |
| Samsung SSD 970 EVO 1TB                             | 30        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                      | 29        | 0.45%   |
| Samsung NVMe SSD Drive 256GB                        | 28        | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB                      | 27        | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 25        | 0.39%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB                         | 25        | 0.39%   |
| Samsung SSD 860 QVO 1TB                             | 24        | 0.37%   |
| Toshiba MQ01ABF050 500GB                            | 23        | 0.36%   |
| Samsung SSD 870 QVO 1TB                             | 23        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                        | 23        | 0.36%   |
| SK hynix BC711 NVMe 128GB                           | 22        | 0.34%   |
| Seagate ST9500325AS 500GB                           | 22        | 0.34%   |
| Samsung NVMe SSD Drive 1024GB                       | 22        | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB                        | 21        | 0.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 20        | 0.31%   |
| SanDisk NVMe SSD Drive 512GB                        | 20        | 0.31%   |
| Toshiba MQ01ABD100 1TB                              | 19        | 0.29%   |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.29%   |
| Kingston SA400S37480G 480GB SSD                     | 18        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 674       | 1060   | 33.45%  |
| WDC                 | 608       | 947    | 30.17%  |
| Toshiba             | 214       | 303    | 10.62%  |
| Hitachi             | 169       | 217    | 8.39%   |
| Samsung Electronics | 137       | 219    | 6.8%    |
| HGST                | 96        | 120    | 4.76%   |
| Maxtor              | 31        | 43     | 1.54%   |
| Fujitsu             | 21        | 23     | 1.04%   |
| Apple               | 12        | 16     | 0.6%    |
| ASMT                | 11        | 14     | 0.55%   |
| Unknown             | 8         | 15     | 0.4%    |
| JMicron Technology  | 8         | 11     | 0.4%    |
| Intenso             | 3         | 3      | 0.15%   |
| HGST HTS            | 3         | 4      | 0.15%   |
| IBM/Hitachi         | 2         | 2      | 0.1%    |
| External            | 2         | 4      | 0.1%    |
| ExcelStor           | 2         | 2      | 0.1%    |
| ASMedia             | 2         | 4      | 0.1%    |
| Synology            | 1         | 1      | 0.05%   |
| SSK                 | 1         | 1      | 0.05%   |
| QNAP                | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| NAS                 | 1         | 10     | 0.05%   |
| Maxtor 6            | 1         | 2      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LIO-ORG             | 1         | 4      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| Inateck             | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 696       | 1043   | 34.07%  |
| Kingston            | 256       | 330    | 12.53%  |
| Crucial             | 238       | 311    | 11.65%  |
| SanDisk             | 163       | 203    | 7.98%   |
| WDC                 | 80        | 112    | 3.92%   |
| Intel               | 69        | 86     | 3.38%   |
| A-DATA Technology   | 52        | 58     | 2.55%   |
| SK hynix            | 47        | 60     | 2.3%    |
| Micron Technology   | 37        | 49     | 1.81%   |
| LITEON              | 34        | 45     | 1.66%   |
| OCZ                 | 31        | 39     | 1.52%   |
| China               | 31        | 44     | 1.52%   |
| Apple               | 31        | 39     | 1.52%   |
| Toshiba             | 28        | 35     | 1.37%   |
| PNY                 | 25        | 30     | 1.22%   |
| LITEONIT            | 25        | 28     | 1.22%   |
| Corsair             | 20        | 28     | 0.98%   |
| Transcend           | 19        | 24     | 0.93%   |
| GOODRAM             | 16        | 17     | 0.78%   |
| Patriot             | 14        | 17     | 0.69%   |
| SPCC                | 13        | 14     | 0.64%   |
| Intenso             | 13        | 13     | 0.64%   |
| Gigabyte Technology | 6         | 10     | 0.29%   |
| Netac               | 5         | 5      | 0.24%   |
| Mushkin             | 5         | 7      | 0.24%   |
| KingSpec            | 5         | 6      | 0.24%   |
| KingFast            | 5         | 6      | 0.24%   |
| ASMT                | 5         | 5      | 0.24%   |
| Apacer              | 4         | 4      | 0.2%    |
| ACASIS              | 4         | 4      | 0.2%    |
| Unknown             | 4         | 7      | 0.2%    |
| Unknown             | 3         | 3      | 0.15%   |
| Team                | 3         | 5      | 0.15%   |
| SSSTC               | 3         | 3      | 0.15%   |
| Plextor             | 3         | 4      | 0.15%   |
| Phison              | 3         | 6      | 0.15%   |
| Leven               | 3         | 3      | 0.15%   |
| Vaseky              | 2         | 2      | 0.1%    |
| Seagate             | 2         | 2      | 0.1%    |
| SAGE                | 2         | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1799      | 2754   | 34.71%  |
| HDD     | 1661      | 3032   | 32.05%  |
| NVMe    | 1423      | 2032   | 27.46%  |
| MMC     | 240       | 288    | 4.63%   |
| Unknown | 60        | 75     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2759      | 5493   | 59.26%  |
| NVMe | 1421      | 2026   | 30.52%  |
| MMC  | 240       | 288    | 5.15%   |
| SAS  | 236       | 374    | 5.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2243      | 3522   | 61.62%  |
| 0.51-1.0   | 900       | 1361   | 24.73%  |
| 1.01-2.0   | 275       | 453    | 7.55%   |
| 3.01-4.0   | 87        | 177    | 2.39%   |
| 4.01-10.0  | 69        | 169    | 1.9%    |
| 2.01-3.0   | 61        | 87     | 1.68%   |
| 10.01-20.0 | 4         | 16     | 0.11%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1100      | 26.13%  |
| 251-500        | 820       | 19.48%  |
| 501-1000       | 548       | 13.02%  |
| 1-20           | 433       | 10.29%  |
| 1001-2000      | 362       | 8.6%    |
| 51-100         | 274       | 6.51%   |
| More than 3000 | 247       | 5.87%   |
| 21-50          | 183       | 4.35%   |
| 2001-3000      | 127       | 3.02%   |
| Unknown        | 115       | 2.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1727      | 39.7%   |
| 21-50          | 653       | 15.01%  |
| 101-250        | 504       | 11.59%  |
| 51-100         | 465       | 10.69%  |
| 251-500        | 320       | 7.36%   |
| 501-1000       | 269       | 6.18%   |
| 1001-2000      | 139       | 3.2%    |
| Unknown        | 115       | 2.64%   |
| More than 3000 | 103       | 2.37%   |
| 2001-3000      | 53        | 1.22%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.61%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 1.61%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 1.61%   |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.2%    |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.2%    |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.2%    |
| Intel SSDSC2BW120A4 120GB             | 3         | 4      | 1.2%    |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.2%    |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 1.2%    |
| Crucial CT128MX100SSD1 128GB          | 3         | 3      | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.8%    |
| WDC WD60EFRX-68MYMN1 6TB              | 2         | 2      | 0.8%    |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 3      | 0.8%    |
| WDC WD1002FAEX-00Y9A0 1TB             | 2         | 2      | 0.8%    |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 0.8%    |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.8%    |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.8%    |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.8%    |
| Seagate ST380011A 80GB                | 2         | 2      | 0.8%    |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.8%    |
| Seagate ST31000524AS 1TB              | 2         | 2      | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 0.8%    |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.8%    |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 0.8%    |
| Samsung Electronics HD753LJ 752GB     | 2         | 2      | 0.8%    |
| Samsung Electronics HD103UJ 1TB       | 2         | 2      | 0.8%    |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.8%    |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.8%    |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 0.8%    |
| Intel SSDSA2M080G2GC 80GB             | 2         | 3      | 0.8%    |
| Hitachi HTS725050A7E630 500GB         | 2         | 2      | 0.8%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 3      | 0.8%    |
| Fujitsu MHZ2320BH G2 320GB            | 2         | 2      | 0.8%    |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.4%    |
| WDC WD800JD-00HKA0 80GB               | 1         | 1      | 0.4%    |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.4%    |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.4%    |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.4%    |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 59        | 72     | 24.08%  |
| Seagate                     | 45        | 60     | 18.37%  |
| Samsung Electronics         | 17        | 21     | 6.94%   |
| Hitachi                     | 16        | 17     | 6.53%   |
| Kingston                    | 15        | 17     | 6.12%   |
| Intel                       | 15        | 20     | 6.12%   |
| Toshiba                     | 12        | 13     | 4.9%    |
| Crucial                     | 12        | 20     | 4.9%    |
| HGST                        | 10        | 12     | 4.08%   |
| SanDisk                     | 8         | 8      | 3.27%   |
| SK hynix                    | 6         | 6      | 2.45%   |
| Micron Technology           | 4         | 4      | 1.63%   |
| Fujitsu                     | 4         | 4      | 1.63%   |
| Maxtor                      | 3         | 5      | 1.22%   |
| LITEON                      | 3         | 6      | 1.22%   |
| OCZ                         | 2         | 2      | 0.82%   |
| LITEONIT                    | 2         | 2      | 0.82%   |
| Corsair                     | 2         | 4      | 0.82%   |
| A-DATA Technology           | 2         | 2      | 0.82%   |
| Realtek                     | 1         | 1      | 0.41%   |
| Patriot                     | 1         | 1      | 0.41%   |
| Kingston Technology Company | 1         | 1      | 0.41%   |
| Intenso                     | 1         | 1      | 0.41%   |
| GOODRAM                     | 1         | 1      | 0.41%   |
| C-Series                    | 1         | 1      | 0.41%   |
| Apple                       | 1         | 1      | 0.41%   |
| Anobit                      | 1         | 1      | 0.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 56        | 69     | 36.36%  |
| Seagate             | 45        | 60     | 29.22%  |
| Hitachi             | 16        | 17     | 10.39%  |
| Toshiba             | 11        | 12     | 7.14%   |
| HGST                | 10        | 12     | 6.49%   |
| Samsung Electronics | 8         | 8      | 5.19%   |
| Fujitsu             | 4         | 4      | 2.6%    |
| Maxtor              | 3         | 5      | 1.95%   |
| Apple               | 1         | 1      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 144       | 188    | 61.28%  |
| SSD  | 81        | 99     | 34.47%  |
| NVMe | 10        | 16     | 4.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 12.5%   |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 12.5%   |
| Toshiba HDWG180 8TB               | 1         | 4      | 12.5%   |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 12.5%   |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 12.5%   |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 12.5%   |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 12.5%   |
| Apple HDD HTS541010A9E662 1TB     | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 25%     |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |
| Apple               | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2532      | 5323   | 59.8%   |
| Works    | 1469      | 2544   | 34.7%   |
| Malfunc  | 225       | 303    | 5.31%   |
| Failed   | 8         | 11     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2593      | 51.98%  |
| Samsung Electronics                     | 638       | 12.79%  |
| AMD                                     | 623       | 12.49%  |
| SanDisk                                 | 170       | 3.41%   |
| SK hynix                                | 152       | 3.05%   |
| Kingston Technology Company             | 108       | 2.17%   |
| Toshiba America Info Systems            | 85        | 1.7%    |
| ASMedia Technology                      | 78        | 1.56%   |
| JMicron Technology                      | 62        | 1.24%   |
| Nvidia                                  | 58        | 1.16%   |
| Marvell Technology Group                | 56        | 1.12%   |
| Phison Electronics                      | 54        | 1.08%   |
| KIOXIA                                  | 54        | 1.08%   |
| Micron Technology                       | 40        | 0.8%    |
| Micron/Crucial Technology               | 25        | 0.5%    |
| Solid State Storage Technology          | 19        | 0.38%   |
| ADATA Technology                        | 16        | 0.32%   |
| VIA Technologies                        | 15        | 0.3%    |
| Silicon Motion                          | 15        | 0.3%    |
| Silicon Integrated Systems [SiS]        | 15        | 0.3%    |
| Apple                                   | 13        | 0.26%   |
| Seagate Technology                      | 12        | 0.24%   |
| Lite-On Technology                      | 11        | 0.22%   |
| Broadcom / LSI                          | 11        | 0.22%   |
| Silicon Image                           | 8         | 0.16%   |
| Realtek Semiconductor                   | 8         | 0.16%   |
| LSI Logic / Symbios Logic               | 8         | 0.16%   |
| Union Memory (Shenzhen)                 | 7         | 0.14%   |
| O2 Micro                                | 6         | 0.12%   |
| Hewlett-Packard                         | 5         | 0.1%    |
| MAXIO Technology (Hangzhou)             | 3         | 0.06%   |
| Integrated Technology Express           | 3         | 0.06%   |
| Adaptec                                 | 3         | 0.06%   |
| ULi Electronics                         | 2         | 0.04%   |
| Transcend                               | 2         | 0.04%   |
| Promise Technology                      | 2         | 0.04%   |
| INNOGRIT                                | 2         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |
| Shenzhen Longsys Electronics            | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 401       | 6.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 318       | 5.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 183       | 3.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 181       | 3.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 172       | 2.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 156       | 2.71%   |
| Samsung NVMe SSD Controller 980                                                | 143       | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 111       | 1.93%   |
| AMD 400 Series Chipset SATA Controller                                         | 102       | 1.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 92        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 90        | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 77        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 76        | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 75        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 73        | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 73        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 73        | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 72        | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 72        | 1.25%   |
| Intel SATA Controller [RAID mode]                                              | 70        | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 69        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 66        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 65        | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 61        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 60        | 1.04%   |
| AMD 500 Series Chipset SATA Controller                                         | 60        | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 58        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 58        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 57        | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 55        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 54        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 54        | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                | 51        | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 51        | 0.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 48        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 48        | 0.83%   |
| Intel SSD 660P Series                                                          | 45        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 45        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 44        | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 43        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2671      | 52.95%  |
| NVMe | 1433      | 28.41%  |
| IDE  | 570       | 11.3%   |
| RAID | 355       | 7.04%   |
| SAS  | 8         | 0.16%   |
| SCSI | 7         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3117      | 78.45%  |
| AMD          | 803       | 20.21%  |
| ARM          | 50        | 1.26%   |
| CentaurHauls | 2         | 0.05%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 58        | 1.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 47        | 1.18%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 45        | 1.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 39        | 0.98%   |
| ARM Processor                                 | 39        | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor             | 39        | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 36        | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 35        | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 0.8%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 32        | 0.8%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 29        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 27        | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 0.6%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 24        | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 22        | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 20        | 0.5%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 20        | 0.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 20        | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 19        | 0.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.48%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 19        | 0.48%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 19        | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 19        | 0.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.48%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 18        | 0.45%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 18        | 0.45%   |
| AMD Custom APU 0405                           | 18        | 0.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 17        | 0.43%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 16        | 0.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 861       | 21.64%  |
| Intel Core i7           | 795       | 19.98%  |
| Intel Core i3           | 295       | 7.42%   |
| Other                   | 283       | 7.11%   |
| AMD Ryzen 5             | 191       | 4.8%    |
| AMD Ryzen 7             | 189       | 4.75%   |
| Intel Core 2 Duo        | 173       | 4.35%   |
| Intel Celeron           | 140       | 3.52%   |
| Intel Pentium Silver    | 106       | 2.66%   |
| Intel Atom              | 93        | 2.34%   |
| Intel Pentium           | 88        | 2.21%   |
| Intel Xeon              | 84        | 2.11%   |
| AMD Ryzen 9             | 61        | 1.53%   |
| Intel Pentium Dual-Core | 56        | 1.41%   |
| Intel Core 2 Quad       | 46        | 1.16%   |
| AMD FX                  | 37        | 0.93%   |
| Intel Core i9           | 33        | 0.83%   |
| Intel Core 2            | 29        | 0.73%   |
| Intel Pentium Dual      | 26        | 0.65%   |
| AMD A6                  | 26        | 0.65%   |
| AMD Ryzen 7 PRO         | 25        | 0.63%   |
| Intel Genuine           | 22        | 0.55%   |
| AMD A8                  | 22        | 0.55%   |
| AMD Ryzen 5 PRO         | 20        | 0.5%    |
| AMD Ryzen 3             | 19        | 0.48%   |
| AMD Athlon 64 X2        | 19        | 0.48%   |
| AMD Phenom II X4        | 17        | 0.43%   |
| AMD A4                  | 16        | 0.4%    |
| Intel Pentium 4         | 15        | 0.38%   |
| AMD A10                 | 15        | 0.38%   |
| Intel Pentium D         | 13        | 0.33%   |
| AMD E                   | 13        | 0.33%   |
| AMD Athlon II X2        | 13        | 0.33%   |
| ARM BCM                 | 10        | 0.25%   |
| AMD E1                  | 10        | 0.25%   |
| AMD Athlon II X4        | 8         | 0.2%    |
| AMD Athlon              | 8         | 0.2%    |
| AMD Ryzen Threadripper  | 7         | 0.18%   |
| Intel Core m3           | 6         | 0.15%   |
| AMD E2                  | 6         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1571      | 39.47%  |
| 2       | 1455      | 36.56%  |
| 6       | 390       | 9.8%    |
| 8       | 292       | 7.34%   |
| 1       | 91        | 2.29%   |
| 12      | 67        | 1.68%   |
| 10      | 38        | 0.95%   |
| 16      | 26        | 0.65%   |
| 14      | 21        | 0.53%   |
| 3       | 10        | 0.25%   |
| 24      | 8         | 0.2%    |
| Unknown | 7         | 0.18%   |
| 64      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3937      | 99.09%  |
| 2       | 29        | 0.73%   |
| Unknown | 5         | 0.13%   |
| 4       | 1         | 0.03%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2564      | 64.47%  |
| 1       | 1403      | 35.28%  |
| Unknown | 7         | 0.18%   |
| 16      | 1         | 0.03%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3857      | 96.84%  |
| Unknown        | 93        | 2.33%   |
| 32-bit         | 30        | 0.75%   |
| 64-bit         | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1094      | 26.55%  |
| 0x306a9    | 212       | 5.14%   |
| 0x206a7    | 199       | 4.83%   |
| 0x306c3    | 168       | 4.08%   |
| 0x1067a    | 142       | 3.45%   |
| 0x806ec    | 124       | 3.01%   |
| 0x906ea    | 114       | 2.77%   |
| 0x806c1    | 79        | 1.92%   |
| 0x806ea    | 77        | 1.87%   |
| 0x406e3    | 77        | 1.87%   |
| 0x506e3    | 74        | 1.8%    |
| 0x40651    | 71        | 1.72%   |
| 0x20655    | 67        | 1.63%   |
| 0x806e9    | 66        | 1.6%    |
| 0x906e9    | 61        | 1.48%   |
| 0x906c0    | 59        | 1.43%   |
| 0x6fd      | 59        | 1.43%   |
| 0x08701021 | 54        | 1.31%   |
| 0x306d4    | 47        | 1.14%   |
| 0x08600106 | 42        | 1.02%   |
| 0x706a8    | 41        | 0.99%   |
| 0x30678    | 41        | 0.99%   |
| 0x0a50000c | 41        | 0.99%   |
| 0x6fb      | 35        | 0.85%   |
| 0x08701013 | 33        | 0.8%    |
| 0x010000c8 | 33        | 0.8%    |
| 0x806eb    | 31        | 0.75%   |
| 0xa0652    | 28        | 0.68%   |
| 0x10676    | 28        | 0.68%   |
| 0x906ed    | 27        | 0.66%   |
| 0x706e5    | 27        | 0.66%   |
| 0x0800820d | 27        | 0.66%   |
| 0x20652    | 26        | 0.63%   |
| 0x106e5    | 26        | 0.63%   |
| 0x406c4    | 25        | 0.61%   |
| 0x706a1    | 24        | 0.58%   |
| 0x08108109 | 24        | 0.58%   |
| 0x506c9    | 23        | 0.56%   |
| 0x08108102 | 23        | 0.56%   |
| 0x06001119 | 23        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 686       | 17.24%  |
| Haswell          | 343       | 8.62%   |
| IvyBridge        | 283       | 7.11%   |
| SandyBridge      | 264       | 6.63%   |
| Skylake          | 215       | 5.4%    |
| Penryn           | 213       | 5.35%   |
| Zen 2            | 197       | 4.95%   |
| Unknown          | 164       | 4.12%   |
| Core             | 153       | 3.85%   |
| Westmere         | 135       | 3.39%   |
| Silvermont       | 131       | 3.29%   |
| Zen 3            | 125       | 3.14%   |
| TigerLake        | 108       | 2.71%   |
| Zen+             | 99        | 2.49%   |
| Broadwell        | 80        | 2.01%   |
| Goldmont plus    | 71        | 1.78%   |
| CometLake        | 70        | 1.76%   |
| Piledriver       | 59        | 1.48%   |
| Nehalem          | 59        | 1.48%   |
| K10              | 58        | 1.46%   |
| Alderlake Hybrid | 57        | 1.43%   |
| Zen              | 54        | 1.36%   |
| Tremont          | 52        | 1.31%   |
| IceLake          | 50        | 1.26%   |
| K8 Hammer        | 35        | 0.88%   |
| Goldmont         | 33        | 0.83%   |
| NetBurst         | 32        | 0.8%    |
| Excavator        | 23        | 0.58%   |
| Bonnell          | 21        | 0.53%   |
| Bobcat           | 21        | 0.53%   |
| K10 Llano        | 17        | 0.43%   |
| P6               | 16        | 0.4%    |
| Jaguar           | 16        | 0.4%    |
| Steamroller      | 12        | 0.3%    |
| Puma             | 10        | 0.25%   |
| K8 & K10 hybrid  | 9         | 0.23%   |
| Bulldozer        | 7         | 0.18%   |
| CannonLake       | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2344      | 50.75%  |
| Nvidia                           | 1280      | 27.71%  |
| AMD                              | 953       | 20.63%  |
| Matrox Electronics Systems       | 16        | 0.35%   |
| ASPEED Technology                | 10        | 0.22%   |
| Silicon Integrated Systems [SiS] | 8         | 0.17%   |
| VIA Technologies                 | 7         | 0.15%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 193       | 4.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 168       | 3.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 122       | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 114       | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 100       | 2.11%   |
| Intel UHD Graphics 620                                                                   | 90        | 1.9%    |
| AMD Renoir                                                                               | 82        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 1.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 74        | 1.56%   |
| Intel HD Graphics 620                                                                    | 74        | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 72        | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 67        | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 66        | 1.39%   |
| Intel HD Graphics 630                                                                    | 64        | 1.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 63        | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 63        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 63        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 62        | 1.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 59        | 1.24%   |
| Intel HD Graphics 530                                                                    | 58        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 58        | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 1.08%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 48        | 1.01%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 46        | 0.97%   |
| Intel HD Graphics 5500                                                                   | 46        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 41        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 36        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 35        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 32        | 0.68%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 32        | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 32        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 31        | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 26        | 0.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 25        | 0.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 23        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1718      | 42.9%   |
| 1 x AMD                  | 781       | 19.5%   |
| 1 x Nvidia               | 723       | 18.05%  |
| Intel + Nvidia           | 494       | 12.33%  |
| Intel + AMD              | 74        | 1.85%   |
| Other                    | 57        | 1.42%   |
| 2 x AMD                  | 48        | 1.2%    |
| AMD + Nvidia             | 48        | 1.2%    |
| 1 x Matrox               | 13        | 0.32%   |
| 2 x Nvidia               | 11        | 0.27%   |
| 1 x SiS                  | 8         | 0.2%    |
| 2 x Intel                | 7         | 0.17%   |
| 1 x VIA                  | 7         | 0.17%   |
| 1 x ASPEED               | 5         | 0.12%   |
| Nvidia + ASPEED          | 4         | 0.1%    |
| Nvidia + Matrox          | 2         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.05%   |
| Intel + 2 x AMD          | 1         | 0.02%   |
| AMD + Matrox             | 1         | 0.02%   |
| AMD + ASPEED             | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3170      | 78.45%  |
| Proprietary | 684       | 16.93%  |
| Unknown     | 187       | 4.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2397      | 58.65%  |
| 1.01-2.0   | 425       | 10.4%   |
| 0.01-0.5   | 397       | 9.71%   |
| 0.51-1.0   | 287       | 7.02%   |
| 3.01-4.0   | 261       | 6.39%   |
| 7.01-8.0   | 172       | 4.21%   |
| 5.01-6.0   | 83        | 2.03%   |
| 8.01-16.0  | 36        | 0.88%   |
| 2.01-3.0   | 25        | 0.61%   |
| 16.01-24.0 | 4         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 566       | 12.98%  |
| Samsung Electronics     | 546       | 12.53%  |
| LG Display              | 361       | 8.28%   |
| BOE                     | 336       | 7.71%   |
| Chimei Innolux          | 290       | 6.65%   |
| Dell                    | 242       | 5.55%   |
| Iiyama                  | 195       | 4.47%   |
| Goldstar                | 191       | 4.38%   |
| Philips                 | 190       | 4.36%   |
| Hewlett-Packard         | 150       | 3.44%   |
| Acer                    | 133       | 3.05%   |
| Apple                   | 113       | 2.59%   |
| Sharp                   | 99        | 2.27%   |
| AOC                     | 97        | 2.23%   |
| BenQ                    | 87        | 2%      |
| Chi Mei Optoelectronics | 60        | 1.38%   |
| Ancor Communications    | 55        | 1.26%   |
| Lenovo                  | 51        | 1.17%   |
| Sony                    | 35        | 0.8%    |
| LG Philips              | 34        | 0.78%   |
| Medion                  | 31        | 0.71%   |
| Idek Iiyama             | 29        | 0.67%   |
| InfoVision              | 28        | 0.64%   |
| LG Electronics          | 22        | 0.5%    |
| ASUSTek Computer        | 22        | 0.5%    |
| Eizo                    | 20        | 0.46%   |
| CSO                     | 20        | 0.46%   |
| PANDA                   | 19        | 0.44%   |
| MSI                     | 18        | 0.41%   |
| Unknown                 | 15        | 0.34%   |
| Valve                   | 14        | 0.32%   |
| Panasonic               | 14        | 0.32%   |
| ViewSonic               | 12        | 0.28%   |
| Gigabyte Technology     | 12        | 0.28%   |
| Fujitsu Siemens         | 12        | 0.28%   |
| Vestel Elektronik       | 11        | 0.25%   |
| Packard Bell            | 11        | 0.25%   |
| NEC Computers           | 11        | 0.25%   |
| Toshiba                 | 10        | 0.23%   |
| HannStar                | 10        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 33        | 0.73%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 26        | 0.57%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 23        | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 17        | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 16        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 16        | 0.35%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 15        | 0.33%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch            | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 12        | 0.26%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 11        | 0.24%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 11        | 0.24%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 11        | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 10        | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 10        | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 10        | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 9         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 8         | 0.18%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 8         | 0.18%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.18%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                      | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 8         | 0.18%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                      | 8         | 0.18%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 8         | 0.18%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 8         | 0.18%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                        | 8         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.15%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 7         | 0.15%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1756      | 41.72%  |
| 1366x768 (WXGA)    | 580       | 13.78%  |
| 3840x2160 (4K)     | 284       | 6.75%   |
| 2560x1440 (QHD)    | 259       | 6.15%   |
| 1600x900 (HD+)     | 179       | 4.25%   |
| 1280x1024 (SXGA)   | 149       | 3.54%   |
| 1680x1050 (WSXGA+) | 145       | 3.44%   |
| 1920x1200 (WUXGA)  | 118       | 2.8%    |
| 1280x800 (WXGA)    | 115       | 2.73%   |
| 1440x900 (WXGA+)   | 103       | 2.45%   |
| 3440x1440          | 71        | 1.69%   |
| Unknown            | 57        | 1.35%   |
| 2560x1080          | 45        | 1.07%   |
| 2560x1600          | 44        | 1.05%   |
| 1360x768           | 32        | 0.76%   |
| 3840x2400          | 30        | 0.71%   |
| 2880x1800          | 30        | 0.71%   |
| 3840x1080          | 20        | 0.48%   |
| 1024x768 (XGA)     | 18        | 0.43%   |
| 800x1280           | 14        | 0.33%   |
| 1920x540           | 13        | 0.31%   |
| 2736x1824          | 9         | 0.21%   |
| 1600x1200          | 9         | 0.21%   |
| 1280x720 (HD)      | 9         | 0.21%   |
| 3456x2160          | 7         | 0.17%   |
| 2160x1440          | 7         | 0.17%   |
| 3840x1600          | 6         | 0.14%   |
| 3840x1200          | 6         | 0.14%   |
| 3200x1800 (QHD+)   | 6         | 0.14%   |
| 3600x1080          | 5         | 0.12%   |
| 3000x2000          | 5         | 0.12%   |
| 2048x1152          | 5         | 0.12%   |
| 1400x1050          | 5         | 0.12%   |
| 1024x600           | 5         | 0.12%   |
| 7680x2160          | 4         | 0.1%    |
| 5760x1080          | 4         | 0.1%    |
| 2256x1504          | 4         | 0.1%    |
| 1280x960           | 4         | 0.1%    |
| 3072x1920          | 3         | 0.07%   |
| 1680x945           | 3         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 946       | 21.71%  |
| 13      | 378       | 8.67%   |
| 17      | 346       | 7.94%   |
| 27      | 319       | 7.32%   |
| 24      | 319       | 7.32%   |
| 14      | 266       | 6.1%    |
| 23      | 261       | 5.99%   |
| Unknown | 243       | 5.58%   |
| 21      | 203       | 4.66%   |
| 11      | 149       | 3.42%   |
| 19      | 112       | 2.57%   |
| 12      | 94        | 2.16%   |
| 34      | 93        | 2.13%   |
| 22      | 92        | 2.11%   |
| 31      | 79        | 1.81%   |
| 20      | 58        | 1.33%   |
| 18      | 45        | 1.03%   |
| 84      | 36        | 0.83%   |
| 16      | 36        | 0.83%   |
| 25      | 33        | 0.76%   |
| 72      | 27        | 0.62%   |
| 40      | 24        | 0.55%   |
| 54      | 16        | 0.37%   |
| 10      | 16        | 0.37%   |
| 65      | 15        | 0.34%   |
| 28      | 12        | 0.28%   |
| 32      | 11        | 0.25%   |
| 26      | 11        | 0.25%   |
| 7       | 11        | 0.25%   |
| 33      | 10        | 0.23%   |
| 29      | 10        | 0.23%   |
| 37      | 8         | 0.18%   |
| 35      | 7         | 0.16%   |
| 52      | 6         | 0.14%   |
| 46      | 6         | 0.14%   |
| 36      | 6         | 0.14%   |
| 58      | 5         | 0.11%   |
| 42      | 5         | 0.11%   |
| 39      | 5         | 0.11%   |
| 57      | 4         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1412      | 32.98%  |
| 501-600        | 855       | 19.97%  |
| 201-300        | 507       | 11.84%  |
| 401-500        | 424       | 9.9%    |
| 351-400        | 384       | 8.97%   |
| Unknown        | 243       | 5.68%   |
| 601-700        | 130       | 3.04%   |
| 701-800        | 117       | 2.73%   |
| 1001-1500      | 67        | 1.57%   |
| 1501-2000      | 66        | 1.54%   |
| 801-900        | 47        | 1.1%    |
| 1-100          | 14        | 0.33%   |
| 901-1000       | 12        | 0.28%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2787      | 70.45%  |
| 16/10   | 591       | 14.94%  |
| Unknown | 201       | 5.08%   |
| 5/4     | 141       | 3.56%   |
| 21/9    | 114       | 2.88%   |
| 3/2     | 44        | 1.11%   |
| 4/3     | 42        | 1.06%   |
| 6/5     | 11        | 0.28%   |
| 0.67    | 11        | 0.28%   |
| 32/9    | 7         | 0.18%   |
| 3.40    | 1         | 0.03%   |
| 3.33    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.80    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 931       | 21.53%  |
| 201-250        | 685       | 15.84%  |
| 81-90          | 442       | 10.22%  |
| 301-350        | 329       | 7.61%   |
| Unknown        | 243       | 5.62%   |
| 151-200        | 239       | 5.53%   |
| 121-130        | 225       | 5.2%    |
| 351-500        | 221       | 5.11%   |
| 71-80          | 210       | 4.86%   |
| 51-60          | 151       | 3.49%   |
| 251-300        | 145       | 3.35%   |
| More than 1000 | 120       | 2.78%   |
| 141-150        | 102       | 2.36%   |
| 61-70          | 81        | 1.87%   |
| 501-1000       | 67        | 1.55%   |
| 131-140        | 48        | 1.11%   |
| 111-120        | 47        | 1.09%   |
| 1-40           | 16        | 0.37%   |
| 41-50          | 15        | 0.35%   |
| 91-100         | 7         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1328      | 31.49%  |
| 121-160       | 1191      | 28.24%  |
| 101-120       | 916       | 21.72%  |
| 161-240       | 282       | 6.69%   |
| Unknown       | 243       | 5.76%   |
| More than 240 | 156       | 3.7%    |
| 1-50          | 101       | 2.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3138      | 77.06%  |
| 2     | 662       | 16.26%  |
| 0     | 196       | 4.81%   |
| 3     | 70        | 1.72%   |
| 4     | 5         | 0.12%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2117      | 36.3%   |
| Realtek Semiconductor                 | 1905      | 32.66%  |
| Qualcomm Atheros                      | 553       | 9.48%   |
| Broadcom                              | 369       | 6.33%   |
| Broadcom Limited                      | 85        | 1.46%   |
| TP-Link                               | 76        | 1.3%    |
| Marvell Technology Group              | 75        | 1.29%   |
| Ralink Technology                     | 69        | 1.18%   |
| Ralink                                | 59        | 1.01%   |
| MediaTek                              | 57        | 0.98%   |
| Nvidia                                | 45        | 0.77%   |
| ASIX Electronics                      | 38        | 0.65%   |
| DisplayLink                           | 31        | 0.53%   |
| Dell                                  | 30        | 0.51%   |
| Hewlett-Packard                       | 24        | 0.41%   |
| Microsoft                             | 16        | 0.27%   |
| Sitecom Europe                        | 15        | 0.26%   |
| Samsung Electronics                   | 14        | 0.24%   |
| NetGear                               | 13        | 0.22%   |
| Huawei Technologies                   | 13        | 0.22%   |
| Silicon Integrated Systems [SiS]      | 12        | 0.21%   |
| JMicron Technology                    | 12        | 0.21%   |
| Ericsson Business Mobile Networks     | 12        | 0.21%   |
| Sierra Wireless                       | 11        | 0.19%   |
| Lenovo                                | 11        | 0.19%   |
| IMC Networks                          | 11        | 0.19%   |
| ASUSTek Computer                      | 11        | 0.19%   |
| Qualcomm                              | 9         | 0.15%   |
| Aquantia                              | 9         | 0.15%   |
| VIA Technologies                      | 6         | 0.1%    |
| Gemtek                                | 6         | 0.1%    |
| D-Link                                | 6         | 0.1%    |
| Xiaomi                                | 5         | 0.09%   |
| Mellanox Technologies                 | 5         | 0.09%   |
| Edimax Technology                     | 5         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.09%   |
| U-Blox                                | 4         | 0.07%   |
| Sigma Designs                         | 4         | 0.07%   |
| Qualcomm Atheros Communications       | 4         | 0.07%   |
| Microchip Technology                  | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1363      | 19.96%  |
| Intel Wi-Fi 6 AX200                                               | 212       | 3.1%    |
| Intel Wireless 8265 / 8275                                        | 166       | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 159       | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 158       | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 142       | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 117       | 1.71%   |
| Intel Wireless 7265                                               | 98        | 1.43%   |
| Intel I211 Gigabit Network Connection                             | 97        | 1.42%   |
| Intel Wi-Fi 6 AX201                                               | 85        | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 78        | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 75        | 1.1%    |
| Intel Wireless 7260                                               | 73        | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 65        | 0.95%   |
| Intel Wireless 8260                                               | 64        | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 63        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 62        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 61        | 0.89%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 59        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 56        | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 54        | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 51        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 49        | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 47        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 47        | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 47        | 0.69%   |
| Intel Wireless 3165                                               | 46        | 0.67%   |
| Intel Wireless-AC 9260                                            | 45        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 45        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 45        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 43        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 39        | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 39        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 0.53%   |
| Intel Centrino Ultimate-N 6300                                    | 36        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 35        | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 35        | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 35        | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1626      | 52.3%   |
| Qualcomm Atheros                      | 438       | 14.09%  |
| Realtek Semiconductor                 | 362       | 11.64%  |
| Broadcom                              | 230       | 7.4%    |
| Ralink Technology                     | 69        | 2.22%   |
| TP-Link                               | 67        | 2.16%   |
| Ralink                                | 59        | 1.9%    |
| MediaTek                              | 55        | 1.77%   |
| Broadcom Limited                      | 43        | 1.38%   |
| Sitecom Europe                        | 15        | 0.48%   |
| Microsoft                             | 14        | 0.45%   |
| NetGear                               | 13        | 0.42%   |
| Marvell Technology Group              | 13        | 0.42%   |
| Dell                                  | 12        | 0.39%   |
| Sierra Wireless                       | 11        | 0.35%   |
| IMC Networks                          | 11        | 0.35%   |
| ASUSTek Computer                      | 11        | 0.35%   |
| Qualcomm                              | 6         | 0.19%   |
| Gemtek                                | 6         | 0.19%   |
| D-Link                                | 6         | 0.19%   |
| Edimax Technology                     | 5         | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.16%   |
| Qualcomm Atheros Communications       | 4         | 0.13%   |
| Linksys                               | 4         | 0.13%   |
| Hewlett-Packard                       | 4         | 0.13%   |
| Fibocom                               | 4         | 0.13%   |
| Belkin Components                     | 4         | 0.13%   |
| Senao                                 | 2         | 0.06%   |
| Sagem                                 | 2         | 0.06%   |
| CyberTAN Technology                   | 2         | 0.06%   |
| Wilocity                              | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Cinterion                             | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 212       | 6.79%   |
| Intel Wireless 8265 / 8275                                              | 166       | 5.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 117       | 3.75%   |
| Intel Wireless 7265                                                     | 98        | 3.14%   |
| Intel Wi-Fi 6 AX201                                                     | 85        | 2.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 75        | 2.4%    |
| Intel Wireless 7260                                                     | 73        | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 2.08%   |
| Intel Wireless 8260                                                     | 64        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 62        | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 61        | 1.95%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 59        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 56        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 54        | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 1.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 49        | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 47        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 47        | 1.5%    |
| Intel Wireless 3165                                                     | 46        | 1.47%   |
| Intel Wireless-AC 9260                                                  | 45        | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 45        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 39        | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 35        | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 1.06%   |
| Intel Wireless 3160                                                     | 32        | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 26        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 23        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 23        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 22        | 0.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 22        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1759      | 49.93%  |
| Intel                                  | 1039      | 29.49%  |
| Broadcom                               | 197       | 5.59%   |
| Qualcomm Atheros                       | 179       | 5.08%   |
| Marvell Technology Group               | 62        | 1.76%   |
| Nvidia                                 | 44        | 1.25%   |
| Broadcom Limited                       | 42        | 1.19%   |
| ASIX Electronics                       | 38        | 1.08%   |
| DisplayLink                            | 31        | 0.88%   |
| JMicron Technology                     | 12        | 0.34%   |
| Silicon Integrated Systems [SiS]       | 11        | 0.31%   |
| Lenovo                                 | 11        | 0.31%   |
| Samsung Electronics                    | 10        | 0.28%   |
| TP-Link                                | 9         | 0.26%   |
| Huawei Technologies                    | 9         | 0.26%   |
| Aquantia                               | 9         | 0.26%   |
| VIA Technologies                       | 6         | 0.17%   |
| Hewlett-Packard                        | 6         | 0.17%   |
| Xiaomi                                 | 5         | 0.14%   |
| Mellanox Technologies                  | 4         | 0.11%   |
| Standard Microsystems                  | 3         | 0.09%   |
| Qualcomm                               | 3         | 0.09%   |
| 3Com                                   | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.06%   |
| ULi Electronics                        | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| MosChip Semiconductor                  | 2         | 0.06%   |
| Microsoft                              | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Apple                                  | 2         | 0.06%   |
| Accton Technology                      | 2         | 0.06%   |
| Tenda                                  | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| Jolla Oy                               | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1363      | 37.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 159       | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 158       | 4.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 142       | 3.93%   |
| Intel I211 Gigabit Network Connection                             | 97        | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 78        | 2.16%   |
| Intel Ethernet Connection (2) I219-V                              | 63        | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 47        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 45        | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 1%      |
| Intel Ethernet Controller I225-V                                  | 35        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32        | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 32        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 32        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 31        | 0.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 30        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 27        | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 24        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 20        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17        | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                             | 17        | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 16        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15        | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3319      | 52.23%  |
| WiFi     | 2948      | 46.4%   |
| Modem    | 77        | 1.21%   |
| Unknown  | 10        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2239      | 53.82%  |
| Ethernet | 1920      | 46.15%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2066      | 51.84%  |
| 1     | 1705      | 42.79%  |
| 0     | 106       | 2.66%   |
| 3     | 79        | 1.98%   |
| 4     | 18        | 0.45%   |
| 5     | 4         | 0.1%    |
| 7     | 3         | 0.08%   |
| 6     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3199      | 78.62%  |
| Yes  | 870       | 21.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1302      | 53.49%  |
| Cambridge Silicon Radio         | 193       | 7.93%   |
| Realtek Semiconductor           | 161       | 6.61%   |
| Qualcomm Atheros Communications | 126       | 5.18%   |
| Apple                           | 114       | 4.68%   |
| Broadcom                        | 104       | 4.27%   |
| IMC Networks                    | 85        | 3.49%   |
| Foxconn / Hon Hai               | 66        | 2.71%   |
| Lite-On Technology              | 65        | 2.67%   |
| Hewlett-Packard                 | 44        | 1.81%   |
| ASUSTek Computer                | 44        | 1.81%   |
| Dell                            | 37        | 1.52%   |
| Toshiba                         | 19        | 0.78%   |
| MediaTek                        | 14        | 0.58%   |
| Marvell Semiconductor           | 13        | 0.53%   |
| Ralink                          | 10        | 0.41%   |
| TP-Link                         | 8         | 0.33%   |
| Realtek                         | 5         | 0.21%   |
| Alps Electric                   | 4         | 0.16%   |
| Ralink Technology               | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| USI                             | 2         | 0.08%   |
| Sitecom Europe                  | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Foxconn International           | 2         | 0.08%   |
| Roper                           | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 451       | 18.51%  |
| Intel AX201 Bluetooth                               | 243       | 9.97%   |
| Intel AX200 Bluetooth                               | 203       | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 193       | 7.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 190       | 7.8%    |
| Realtek Bluetooth Radio                             | 99        | 4.06%   |
| Intel Bluetooth Device                              | 52        | 2.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 1.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 44        | 1.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 1.81%   |
| Apple Bluetooth Host Controller                     | 44        | 1.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.76%   |
| IMC Networks Bluetooth Radio                        | 35        | 1.44%   |
| Apple Bluetooth USB Host Controller                 | 34        | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 32        | 1.31%   |
| Intel AX210 Bluetooth                               | 32        | 1.31%   |
| Lite-On Bluetooth Device                            | 29        | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 27        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 26        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 24        | 0.98%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.82%   |
| IMC Networks Bluetooth Device                       | 19        | 0.78%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.78%   |
| Broadcom HP Portable SoftSailing                    | 17        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.66%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 15        | 0.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 15        | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.57%   |
| IMC Networks Wireless_Device                        | 14        | 0.57%   |
| MediaTek Wireless_Device                            | 13        | 0.53%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.49%   |
| Apple Bluetooth HCI                                 | 12        | 0.49%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.45%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2919      | 53.37%  |
| AMD                              | 1023      | 18.71%  |
| Nvidia                           | 915       | 16.73%  |
| C-Media Electronics              | 81        | 1.48%   |
| Logitech                         | 44        | 0.8%    |
| Realtek Semiconductor            | 39        | 0.71%   |
| Creative Labs                    | 33        | 0.6%    |
| GN Netcom                        | 32        | 0.59%   |
| Texas Instruments                | 25        | 0.46%   |
| Focusrite-Novation               | 18        | 0.33%   |
| Hewlett-Packard                  | 15        | 0.27%   |
| Creative Technology              | 15        | 0.27%   |
| Silicon Integrated Systems [SiS] | 14        | 0.26%   |
| BEHRINGER International          | 13        | 0.24%   |
| SteelSeries ApS                  | 12        | 0.22%   |
| Plantronics                      | 12        | 0.22%   |
| Kingston Technology              | 12        | 0.22%   |
| VIA Technologies                 | 11        | 0.2%    |
| JMTek                            | 11        | 0.2%    |
| Corsair                          | 11        | 0.2%    |
| Generalplus Technology           | 9         | 0.16%   |
| Apple                            | 9         | 0.16%   |
| Sony                             | 8         | 0.15%   |
| GYROCOM C&C                      | 8         | 0.15%   |
| ASUSTek Computer                 | 8         | 0.15%   |
| Sennheiser Communications        | 7         | 0.13%   |
| RODE Microphones                 | 7         | 0.13%   |
| Lenovo                           | 7         | 0.13%   |
| Razer USA                        | 6         | 0.11%   |
| Yamaha                           | 5         | 0.09%   |
| Native Instruments               | 5         | 0.09%   |
| Micro Star International         | 5         | 0.09%   |
| Cambridge Silicon Radio          | 5         | 0.09%   |
| XMOS                             | 4         | 0.07%   |
| Schiit Audio                     | 4         | 0.07%   |
| SAVITECH                         | 4         | 0.07%   |
| Samson Technologies              | 4         | 0.07%   |
| Blue Microphones                 | 4         | 0.07%   |
| AKAI Professional M.I.           | 4         | 0.07%   |
| Valve Software                   | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 284       | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 282       | 4.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 277       | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 235       | 3.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 201       | 3.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 170       | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 161       | 2.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 154       | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 152       | 2.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 141       | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 139       | 2.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 126       | 1.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 117       | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 108       | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 106       | 1.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 98        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 88        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 85        | 1.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 83        | 1.3%    |
| Intel 8 Series HD Audio Controller                                         | 83        | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 77        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 75        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 72        | 1.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 71        | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 71        | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 70        | 1.1%    |
| Nvidia High Definition Audio Controller                                    | 69        | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 67        | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 67        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 66        | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 64        | 1%      |
| Intel Jasper Lake HD Audio                                                 | 63        | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 54        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 53        | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 53        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 52        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 52        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 49        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 48        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 503       | 22.26%  |
| Samsung Electronics | 443       | 19.6%   |
| Kingston            | 249       | 11.02%  |
| Micron Technology   | 233       | 10.31%  |
| Corsair             | 190       | 8.41%   |
| Unknown             | 167       | 7.39%   |
| Crucial             | 149       | 6.59%   |
| G.Skill             | 75        | 3.32%   |
| A-DATA Technology   | 33        | 1.46%   |
| Ramaxel Technology  | 32        | 1.42%   |
| Nanya Technology    | 32        | 1.42%   |
| Elpida              | 23        | 1.02%   |
| Unknown             | 14        | 0.62%   |
| Transcend           | 12        | 0.53%   |
| Unknown (ABCD)      | 10        | 0.44%   |
| Team                | 8         | 0.35%   |
| GOODRAM             | 8         | 0.35%   |
| Qimonda             | 7         | 0.31%   |
| ASint Technology    | 5         | 0.22%   |
| Patriot             | 4         | 0.18%   |
| 48spaces            | 4         | 0.18%   |
| Wilk                | 3         | 0.13%   |
| GeIL                | 3         | 0.13%   |
| Axiom               | 3         | 0.13%   |
| A Force             | 3         | 0.13%   |
| Toshiba             | 2         | 0.09%   |
| TakeMS              | 2         | 0.09%   |
| PNY                 | 2         | 0.09%   |
| Lexar               | 2         | 0.09%   |
| Goldkey             | 2         | 0.09%   |
| Avant               | 2         | 0.09%   |
| Atermiter           | 2         | 0.09%   |
| AMD                 | 2         | 0.09%   |
| A-DA                | 2         | 0.09%   |
| ZIFEI               | 1         | 0.04%   |
| zApacer             | 1         | 0.04%   |
| Unknown (AD8A)      | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x873E)    | 1         | 0.04%   |
| Unknown (08C8)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 43        | 1.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 31        | 1.29%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 27        | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 20        | 0.83%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 19        | 0.79%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s         | 17        | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 16        | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 14        | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 14        | 0.58%   |
| Unknown                                                        | 14        | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 13        | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 13        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s       | 13        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 13        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 12        | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 12        | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 12        | 0.5%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 12        | 0.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 12        | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 11        | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 11        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 11        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 10        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 9         | 0.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 9         | 0.37%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 8         | 0.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 8         | 0.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8         | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 8         | 0.33%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 8         | 0.33%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 8         | 0.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 8         | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 8         | 0.33%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s      | 8         | 0.33%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 7         | 0.29%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                    | 7         | 0.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 7         | 0.29%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 7         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 957       | 48.09%  |
| DDR3    | 606       | 30.45%  |
| LPDDR4  | 126       | 6.33%   |
| DDR2    | 83        | 4.17%   |
| LPDDR3  | 64        | 3.22%   |
| SDRAM   | 57        | 2.86%   |
| DDR5    | 34        | 1.71%   |
| Unknown | 29        | 1.46%   |
| LPDDR5  | 17        | 0.85%   |
| DDR     | 13        | 0.65%   |
| DRAM    | 3         | 0.15%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1139      | 57.26%  |
| DIMM         | 615       | 30.92%  |
| Row Of Chips | 213       | 10.71%  |
| Chip         | 9         | 0.45%   |
| Unknown      | 9         | 0.45%   |
| FB-DIMM      | 2         | 0.1%    |
| RIMM         | 1         | 0.05%   |
| DIP          | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 849       | 39.34%  |
| 4096  | 541       | 25.07%  |
| 16384 | 340       | 15.76%  |
| 2048  | 275       | 12.74%  |
| 1024  | 79        | 3.66%   |
| 32768 | 60        | 2.78%   |
| 512   | 11        | 0.51%   |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 1     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 367       | 17.3%   |
| 2667    | 312       | 14.7%   |
| 3200    | 310       | 14.61%  |
| 2400    | 164       | 7.73%   |
| 1333    | 135       | 6.36%   |
| 2133    | 112       | 5.28%   |
| 4267    | 93        | 4.38%   |
| 3600    | 63        | 2.97%   |
| 1334    | 61        | 2.87%   |
| 1867    | 51        | 2.4%    |
| 800     | 48        | 2.26%   |
| 667     | 45        | 2.12%   |
| Unknown | 33        | 1.56%   |
| 4800    | 23        | 1.08%   |
| 1066    | 21        | 0.99%   |
| 6400    | 19        | 0.9%    |
| 1067    | 17        | 0.8%    |
| 3400    | 15        | 0.71%   |
| 2933    | 15        | 0.71%   |
| 3266    | 14        | 0.66%   |
| 1866    | 13        | 0.61%   |
| 8400    | 12        | 0.57%   |
| 1800    | 12        | 0.57%   |
| 3000    | 11        | 0.52%   |
| 3866    | 10        | 0.47%   |
| 3533    | 10        | 0.47%   |
| 2048    | 10        | 0.47%   |
| 4199    | 9         | 0.42%   |
| 3733    | 9         | 0.42%   |
| 3800    | 8         | 0.38%   |
| 400     | 8         | 0.38%   |
| 4266    | 7         | 0.33%   |
| 1639    | 7         | 0.33%   |
| 533     | 7         | 0.33%   |
| 3466    | 6         | 0.28%   |
| 2666    | 6         | 0.28%   |
| 6000    | 5         | 0.24%   |
| 2800    | 5         | 0.24%   |
| 3666    | 4         | 0.19%   |
| 1648    | 4         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 28        | 29.47%  |
| Brother Industries    | 18        | 18.95%  |
| Canon                 | 16        | 16.84%  |
| Samsung Electronics   | 10        | 10.53%  |
| Seiko Epson           | 7         | 7.37%   |
| Dymo-CoStar           | 7         | 7.37%   |
| Citizen               | 4         | 4.21%   |
| Zebra                 | 1         | 1.05%   |
| STMicroelectronics    | 1         | 1.05%   |
| Ricoh                 | 1         | 1.05%   |
| Prolific Technology   | 1         | 1.05%   |
| Lexmark International | 1         | 1.05%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer                        | 4         | 4.21%   |
| Dymo-CoStar LabelWriter 450                               | 4         | 4.21%   |
| Citizen Thermal Receipt Printer [CT-E351]                 | 4         | 4.21%   |
| HP ENVY 5000 series                                       | 3         | 3.16%   |
| HP Deskjet 2540 series                                    | 3         | 3.16%   |
| Seiko Epson ET-2820 Series                                | 2         | 2.11%   |
| Samsung SCX-4600 Series                                   | 2         | 2.11%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 2.11%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 2.11%   |
| Canon TS3100 series                                       | 2         | 2.11%   |
| Canon PIXMA MX920 Series                                  | 2         | 2.11%   |
| Canon PIXMA MG2500 Series                                 | 2         | 2.11%   |
| Canon MG5600 series                                       | 2         | 2.11%   |
| Brother Printer                                           | 2         | 2.11%   |
| Brother HL-2030 Laser Printer                             | 2         | 2.11%   |
| Zebra Printer                                             | 1         | 1.05%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.05%   |
| Seiko Epson XP-4200 Series                                | 1         | 1.05%   |
| Seiko Epson XP-200 Series                                 | 1         | 1.05%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]              | 1         | 1.05%   |
| Seiko Epson Printer                                       | 1         | 1.05%   |
| Seiko Epson ET-2720 Series                                | 1         | 1.05%   |
| Samsung SCX-4300 Series                                   | 1         | 1.05%   |
| Samsung ML-2240 Series                                    | 1         | 1.05%   |
| Samsung C48x Series Color Laser Multifunction Printer     | 1         | 1.05%   |
| Samsung C43x Series                                       | 1         | 1.05%   |
| Ricoh Aficio SP 3510DN                                    | 1         | 1.05%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.05%   |
| Lexmark International MC3326adwe                          | 1         | 1.05%   |
| HP Printing Support                                       | 1         | 1.05%   |
| HP OfficeJet Pro 8020 series                              | 1         | 1.05%   |
| HP OfficeJet 8010 series                                  | 1         | 1.05%   |
| HP OfficeJet 6950                                         | 1         | 1.05%   |
| HP OfficeJet 3830 series                                  | 1         | 1.05%   |
| HP LaserJet Professional P1102w                           | 1         | 1.05%   |
| HP LaserJet P1005                                         | 1         | 1.05%   |
| HP LaserJet 1320                                          | 1         | 1.05%   |
| HP Laser 107w                                             | 1         | 1.05%   |
| HP DeskJet F2100 Printer series                           | 1         | 1.05%   |
| HP Deskjet D1500 series                                   | 1         | 1.05%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 62.16%  |
| Seiko Epson     | 7         | 18.92%  |
| Mustek Systems  | 4         | 10.81%  |
| Hewlett-Packard | 2         | 5.41%   |
| Plustek         | 1         | 2.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 10.53%  |
| Canon CanoScan LiDE 210                       | 4         | 10.53%  |
| Mustek Systems ScanExpress 1200 UB            | 3         | 7.89%   |
| Seiko Epson Scanner                           | 2         | 5.26%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 5.26%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 5.26%   |
| Canon CanoScan N650U/N656U                    | 2         | 5.26%   |
| Canon CanoScan LiDE 200                       | 2         | 5.26%   |
| Canon CanoScan LiDE 120                       | 2         | 5.26%   |
| Canon CanoScan LiDE 110                       | 2         | 5.26%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 2.63%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 2.63%   |
| Plustek 600dpi USB Scanner                    | 1         | 2.63%   |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 2.63%   |
| HP ScanJet 5590                               | 1         | 2.63%   |
| HP ScanJet 3300c                              | 1         | 2.63%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 2.63%   |
| Canon CanoScan LiDE 60                        | 1         | 2.63%   |
| Canon CanoScan FB630U                         | 1         | 2.63%   |
| Canon CanoScan 9000F Mark II                  | 1         | 2.63%   |
| Canon CanoScan 5600F                          | 1         | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 508       | 20.99%  |
| Microdia                               | 278       | 11.49%  |
| Realtek Semiconductor                  | 230       | 9.5%    |
| IMC Networks                           | 196       | 8.1%    |
| Sunplus Innovation Technology          | 164       | 6.78%   |
| Logitech                               | 158       | 6.53%   |
| Cheng Uei Precision Industry (Foxlink) | 102       | 4.21%   |
| Apple                                  | 101       | 4.17%   |
| Bison Electronics                      | 97        | 4.01%   |
| Quanta                                 | 80        | 3.31%   |
| Suyin                                  | 75        | 3.1%    |
| Acer                                   | 62        | 2.56%   |
| Lite-On Technology                     | 47        | 1.94%   |
| Syntek                                 | 31        | 1.28%   |
| Luxvisions Innotech Limited            | 28        | 1.16%   |
| Samsung Electronics                    | 23        | 0.95%   |
| Silicon Motion                         | 21        | 0.87%   |
| Ricoh                                  | 18        | 0.74%   |
| Microsoft                              | 18        | 0.74%   |
| Lenovo                                 | 16        | 0.66%   |
| Alcor Micro                            | 16        | 0.66%   |
| Primax Electronics                     | 13        | 0.54%   |
| Trust                                  | 10        | 0.41%   |
| Jieli Technology                       | 8         | 0.33%   |
| Importek                               | 8         | 0.33%   |
| Sonix Technology                       | 7         | 0.29%   |
| MacroSilicon                           | 7         | 0.29%   |
| Generalplus Technology                 | 6         | 0.25%   |
| ALi                                    | 5         | 0.21%   |
| Z-Star Microelectronics                | 4         | 0.17%   |
| Sweex                                  | 4         | 0.17%   |
| SunplusIT                              | 4         | 0.17%   |
| Creative Technology                    | 4         | 0.17%   |
| ARC International                      | 4         | 0.17%   |
| Y Media                                | 3         | 0.12%   |
| Valve Software                         | 3         | 0.12%   |
| Ruision                                | 3         | 0.12%   |
| OmniVision Technologies                | 3         | 0.12%   |
| LG Electronics                         | 3         | 0.12%   |
| Genesys Logic                          | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 170       | 6.87%   |
| Realtek Integrated_Webcam_HD                                               | 87        | 3.52%   |
| Chicony Integrated Camera                                                  | 82        | 3.31%   |
| IMC Networks Integrated Camera                                             | 71        | 2.87%   |
| Sunplus Integrated_Webcam_HD                                               | 70        | 2.83%   |
| Realtek Integrated_Webcam_5M                                               | 68        | 2.75%   |
| Chicony HD WebCam                                                          | 63        | 2.55%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 43        | 1.74%   |
| Chicony HP HD Camera                                                       | 36        | 1.46%   |
| Logitech Webcam C270                                                       | 31        | 1.25%   |
| Bison Integrated Camera                                                    | 31        | 1.25%   |
| Apple Built-in iSight                                                      | 31        | 1.25%   |
| Chicony USB2.0 Camera                                                      | 27        | 1.09%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 25        | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 23        | 0.93%   |
| Logitech HD Pro Webcam C920                                                | 23        | 0.93%   |
| Chicony HP Wide Vision HD Camera                                           | 22        | 0.89%   |
| Apple FaceTime HD Camera                                                   | 21        | 0.85%   |
| Acer BisonCam,NB Pro                                                       | 21        | 0.85%   |
| Sunplus HD WebCam                                                          | 20        | 0.81%   |
| Microdia Integrated_Webcam_5M                                              | 20        | 0.81%   |
| Apple FaceTime HD Camera (Built-in)                                        | 20        | 0.81%   |
| Acer Integrated Camera                                                     | 20        | 0.81%   |
| Syntek Integrated Camera                                                   | 19        | 0.77%   |
| Chicony USB 2.0 Camera                                                     | 19        | 0.77%   |
| Chicony TOSHIBA Web Camera - HD                                            | 18        | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 17        | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 17        | 0.69%   |
| Logitech Webcam C310                                                       | 16        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 16        | 0.65%   |
| Microdia Integrated Webcam                                                 | 14        | 0.57%   |
| Lite-On HP HD Camera                                                       | 14        | 0.57%   |
| Realtek USB Camera                                                         | 13        | 0.53%   |
| Quanta HD User Facing                                                      | 13        | 0.53%   |
| Chicony Integrated HP HD Webcam                                            | 13        | 0.53%   |
| Quanta HP Wide Vision HD Camera                                            | 12        | 0.49%   |
| Quanta HP HD Camera                                                        | 12        | 0.49%   |
| Logitech C922 Pro Stream Webcam                                            | 12        | 0.49%   |
| Lite-On Integrated Camera                                                  | 12        | 0.49%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 12        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 157       | 32.71%  |
| Synaptics                          | 155       | 32.29%  |
| Shenzhen Goodix Technology         | 63        | 13.13%  |
| AuthenTec                          | 33        | 6.88%   |
| Elan Microelectronics              | 25        | 5.21%   |
| LighTuning Technology              | 22        | 4.58%   |
| Upek                               | 20        | 4.17%   |
| STMicroelectronics                 | 3         | 0.63%   |
| Samsung Electronics                | 1         | 0.21%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 11.04%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 8.54%   |
| Shenzhen Goodix  Fingerprint Device                                        | 27        | 5.63%   |
| Synaptics UWP WBDI                                                         | 20        | 4.17%   |
| Shenzhen Goodix FingerPrint                                                | 20        | 4.17%   |
| Validity Sensors VFS491                                                    | 19        | 3.96%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 3.96%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 3.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 2.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 2.71%   |
| Elan ELAN:ARM-M4                                                           | 13        | 2.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.5%    |
| Synaptics  WBDI                                                            | 12        | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 2.5%    |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 2.5%    |
| Elan ELAN:Fingerprint                                                      | 12        | 2.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.5%    |
| Synaptics WBDI                                                             | 11        | 2.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.08%   |
| AuthenTec AES2810                                                          | 9         | 1.88%   |
| AuthenTec AES1600                                                          | 7         | 1.46%   |
| Unknown                                                                    | 7         | 1.46%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.25%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.25%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.04%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.04%   |
| Synaptics WBDI Device                                                      | 4         | 0.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.63%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.63%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.63%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 117       | 53.42%  |
| Alcor Micro                       | 56        | 25.57%  |
| O2 Micro                          | 23        | 10.5%   |
| Upek                              | 7         | 3.2%    |
| Lenovo                            | 6         | 2.74%   |
| Gemalto (was Gemplus)             | 2         | 0.91%   |
| Yubico.com                        | 1         | 0.46%   |
| VASCO Data Security International | 1         | 0.46%   |
| SCM Microsystems                  | 1         | 0.46%   |
| OmniKey                           | 1         | 0.46%   |
| Fujitsu Siemens Computers         | 1         | 0.46%   |
| Clay Logic                        | 1         | 0.46%   |
| Chicony Electronics               | 1         | 0.46%   |
| Advanced Card Systems             | 1         | 0.46%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 25.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 16.89%  |
| Broadcom 58200                                                               | 33        | 15.07%  |
| Broadcom 5880                                                                | 25        | 11.42%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 10.05%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 9.59%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.2%    |
| Lenovo Integrated Smart Card Reader                                          | 6         | 2.74%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.91%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.46%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.46%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.46%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.46%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.46%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.46%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.46%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.46%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.46%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.46%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2757      | 67.62%  |
| 1     | 1042      | 25.56%  |
| 2     | 224       | 5.49%   |
| 3     | 36        | 0.88%   |
| 4     | 10        | 0.25%   |
| 5     | 4         | 0.1%    |
| 6     | 3         | 0.07%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 475       | 29.58%  |
| Graphics card            | 333       | 20.73%  |
| Chipcard                 | 192       | 11.96%  |
| Net/wireless             | 159       | 9.9%    |
| Multimedia controller    | 156       | 9.71%   |
| Communication controller | 61        | 3.8%    |
| Camera                   | 50        | 3.11%   |
| Bluetooth                | 31        | 1.93%   |
| Unassigned class         | 30        | 1.87%   |
| Sound                    | 24        | 1.49%   |
| Storage                  | 21        | 1.31%   |
| Network                  | 16        | 1%      |
| Card reader              | 16        | 1%      |
| Net/ethernet             | 13        | 0.81%   |
| Flash memory             | 8         | 0.5%    |
| Storage/ide              | 5         | 0.31%   |
| Storage/ata              | 5         | 0.31%   |
| Modem                    | 3         | 0.19%   |
| Tv card                  | 2         | 0.12%   |
| Storage/raid             | 2         | 0.12%   |
| Storage/nvme             | 2         | 0.12%   |
| Firewire controller      | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

