Linux in Thailand - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 371

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450 AORUS ELITE V2         | [92d8a990de](https://linux-hardware.org/?probe=92d8a990de) | Apr 29, 2024 |
| Dell          | 088DT1 A01                  | [0d725519b9](https://linux-hardware.org/?probe=0d725519b9) | Apr 29, 2024 |
| ASRock        | B450 Steel Legend           | [eae63cf682](https://linux-hardware.org/?probe=eae63cf682) | Apr 15, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [11963d204b](https://linux-hardware.org/?probe=11963d204b) | Mar 21, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [908360069c](https://linux-hardware.org/?probe=908360069c) | Mar 21, 2024 |
| Gigabyte      | H81M-DS2                    | [dde5a90821](https://linux-hardware.org/?probe=dde5a90821) | Mar 12, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [3890a0c9b5](https://linux-hardware.org/?probe=3890a0c9b5) | Mar 09, 2024 |
| Gigabyte      | H61M-DS2                    | [68d8ddbe50](https://linux-hardware.org/?probe=68d8ddbe50) | Mar 04, 2024 |
| ASRock        | X299 Taichi                 | [5a5309bb52](https://linux-hardware.org/?probe=5a5309bb52) | Mar 03, 2024 |
| ASUSTek       | P8Z77-V LX                  | [dae19ec723](https://linux-hardware.org/?probe=dae19ec723) | Feb 18, 2024 |
| Dell          | 08WKV3 A00                  | [5bff5d79c2](https://linux-hardware.org/?probe=5bff5d79c2) | Feb 16, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [0fbc4b07a6](https://linux-hardware.org/?probe=0fbc4b07a6) | Feb 12, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c7ad65ef28](https://linux-hardware.org/?probe=c7ad65ef28) | Feb 10, 2024 |
| Dell          | 0VFD52 A00                  | [cc2714d2cf](https://linux-hardware.org/?probe=cc2714d2cf) | Feb 07, 2024 |
| MSI           | X99A SLI PLUS               | [216026fc45](https://linux-hardware.org/?probe=216026fc45) | Jan 30, 2024 |
| ASRock        | H470 Phantom Gaming 4       | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Gigabyte      | B560M AORUS PRO             | [93137ffd8d](https://linux-hardware.org/?probe=93137ffd8d) | Jan 21, 2024 |
| Gigabyte      | H310M DS2 x.x               | [dcbb993ea5](https://linux-hardware.org/?probe=dcbb993ea5) | Jan 18, 2024 |
| ASRock        | B450 Steel Legend           | [d01ee5a226](https://linux-hardware.org/?probe=d01ee5a226) | Jan 02, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [19be3bdc5b](https://linux-hardware.org/?probe=19be3bdc5b) | Dec 31, 2023 |
| HP            | 82B4                        | [02bcf6a9d1](https://linux-hardware.org/?probe=02bcf6a9d1) | Dec 31, 2023 |
| Gigabyte      | H310M DS2 x.x               | [47c95a8cc5](https://linux-hardware.org/?probe=47c95a8cc5) | Dec 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [3dee3cb4bf](https://linux-hardware.org/?probe=3dee3cb4bf) | Dec 19, 2023 |
| ASRock        | B550M Pro4                  | [a32cb7798b](https://linux-hardware.org/?probe=a32cb7798b) | Dec 19, 2023 |
| Dell          | 0HD5W2 A01                  | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [7866cd7449](https://linux-hardware.org/?probe=7866cd7449) | Dec 16, 2023 |
| MSI           | B450 TOMAHAWK               | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| Intel         | X99                         | [6988251bb1](https://linux-hardware.org/?probe=6988251bb1) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| ASRock        | B550M Steel Legend          | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | [284f7d2451](https://linux-hardware.org/?probe=284f7d2451) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [420d9baddf](https://linux-hardware.org/?probe=420d9baddf) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [ab7e55f5b9](https://linux-hardware.org/?probe=ab7e55f5b9) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [9d8548f39a](https://linux-hardware.org/?probe=9d8548f39a) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [36763f453f](https://linux-hardware.org/?probe=36763f453f) | Nov 13, 2023 |
| Google        | Tricky                      | [bd2af6ba92](https://linux-hardware.org/?probe=bd2af6ba92) | Nov 13, 2023 |
| HP            | 802F                        | [e5d90a5987](https://linux-hardware.org/?probe=e5d90a5987) | Nov 09, 2023 |
| Gigabyte      | A520M S2H                   | [701d46485b](https://linux-hardware.org/?probe=701d46485b) | Nov 09, 2023 |
| ASRock        | B550M Steel Legend          | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| Gigabyte      | H61MA-D3V                   | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| HP            | 802F                        | [d01e0550a3](https://linux-hardware.org/?probe=d01e0550a3) | Oct 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [e44d1b7e3c](https://linux-hardware.org/?probe=e44d1b7e3c) | Oct 14, 2023 |
| AMI           | Intel                       | [888a4e1a0f](https://linux-hardware.org/?probe=888a4e1a0f) | Oct 13, 2023 |
| ASRock        | H81M-DGS R2.0               | [4bb18fddab](https://linux-hardware.org/?probe=4bb18fddab) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [423d2de75a](https://linux-hardware.org/?probe=423d2de75a) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cce7c03059](https://linux-hardware.org/?probe=cce7c03059) | Sep 29, 2023 |
| Dell          | 00V62H A01                  | [f46006f6ce](https://linux-hardware.org/?probe=f46006f6ce) | Sep 28, 2023 |
| MiTAC         | PD10EHI                     | [29716ecb18](https://linux-hardware.org/?probe=29716ecb18) | Sep 27, 2023 |
| Dell          | 0D4MD1 A04                  | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Dell          | 0NW6H5 A00                  | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| Intel         | DN2820FYK H24582-204        | [bec0346d1d](https://linux-hardware.org/?probe=bec0346d1d) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Acer          | Veriton N4640G              | [73af90ca23](https://linux-hardware.org/?probe=73af90ca23) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| Dell          | 048DY8 A00                  | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| Google        | Tricky                      | [1adc816fcb](https://linux-hardware.org/?probe=1adc816fcb) | Sep 12, 2023 |
| Biostar       | TB360-BTC Expert            | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| Dell          | 088DT1 A00                  | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Acer          | Veriton N4640G              | [4ad00f4c17](https://linux-hardware.org/?probe=4ad00f4c17) | Sep 10, 2023 |
| Lenovo        | SHARKBAY NOK                | [a09c6ad4a9](https://linux-hardware.org/?probe=a09c6ad4a9) | Sep 08, 2023 |
| Biostar       | TB360-BTC Expert            | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [9d45d79cb0](https://linux-hardware.org/?probe=9d45d79cb0) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | NF6-GLAN                    | [80d9233886](https://linux-hardware.org/?probe=80d9233886) | Sep 04, 2023 |
| ViewSonic     | VPC14-WP                    | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| ECS           | A780GM-A                    | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 802F                        | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Acer          | Veriton N4640G              | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| ASRock        | B450 Steel Legend           | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| MiTAC         | PD10EHI                     | [972fe64be0](https://linux-hardware.org/?probe=972fe64be0) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c711cf46d7](https://linux-hardware.org/?probe=c711cf46d7) | Aug 14, 2023 |
| Dell          | 0HY9JP A01                  | [48d92d85c7](https://linux-hardware.org/?probe=48d92d85c7) | Aug 11, 2023 |
| HP            | 304Ah                       | [81682ebb2d](https://linux-hardware.org/?probe=81682ebb2d) | Jul 20, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| Apple         | Mac-F221BEC8                | [83e08e8aca](https://linux-hardware.org/?probe=83e08e8aca) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| HP            | 802F                        | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| HP            | 802F                        | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| ASRock        | B450 Steel Legend           | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| ASRock        | B450 Steel Legend           | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| Dell          | 07WP95 A01                  | [b9f3afed0c](https://linux-hardware.org/?probe=b9f3afed0c) | May 31, 2023 |
| ASRock        | B450M Steel Legend          | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| Dell          | 07WP95 A01                  | [a58adc500e](https://linux-hardware.org/?probe=a58adc500e) | May 30, 2023 |
| Lenovo        | SHARKBAY NOK                | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| Lenovo        | 313A NOK                    | [a1ffbc1e1e](https://linux-hardware.org/?probe=a1ffbc1e1e) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| Gigabyte      | A520M S2H                   | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| Acer          | Veriton M2610G              | [001e547ddf](https://linux-hardware.org/?probe=001e547ddf) | May 18, 2023 |
| ASUSTek       | D320SF                      | [bbfd29fb88](https://linux-hardware.org/?probe=bbfd29fb88) | May 08, 2023 |
| ASUSTek       | D320SF                      | [fdb3953309](https://linux-hardware.org/?probe=fdb3953309) | May 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [e35b234e43](https://linux-hardware.org/?probe=e35b234e43) | May 07, 2023 |
| Dell          | 0YXT71 A01                  | [bbe145a1a2](https://linux-hardware.org/?probe=bbe145a1a2) | May 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [2ebe14f5d0](https://linux-hardware.org/?probe=2ebe14f5d0) | May 04, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [71bf54960f](https://linux-hardware.org/?probe=71bf54960f) | May 02, 2023 |
| Dell          | 040DDP A01                  | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| Lenovo        | No DPK                      | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| ASRock        | B450 Steel Legend           | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| Acer          | Veriton N4630G              | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| ASUSTek       | PRIME B550M-K               | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| HP            | 802F                        | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [fda0ab85e6](https://linux-hardware.org/?probe=fda0ab85e6) | Mar 18, 2023 |
| ASUSTek       | Z97-K R2.0                  | [8c266d3142](https://linux-hardware.org/?probe=8c266d3142) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [2a40386fb8](https://linux-hardware.org/?probe=2a40386fb8) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [89194cffbe](https://linux-hardware.org/?probe=89194cffbe) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| Acer          | Aspire TC-390               | [2d092d008e](https://linux-hardware.org/?probe=2d092d008e) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASRock        | G41M-GS3                    | [388f28c258](https://linux-hardware.org/?probe=388f28c258) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| Dell          | 088DT1 A01                  | [715d043ec7](https://linux-hardware.org/?probe=715d043ec7) | Mar 01, 2023 |
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| Dell          | 088DT1 A01                  | [990ffa68f4](https://linux-hardware.org/?probe=990ffa68f4) | Feb 23, 2023 |
| Dell          | 088DT1 A01                  | [73dde5b3db](https://linux-hardware.org/?probe=73dde5b3db) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| Supermicro    | X10DRiB                     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| Dell          | 040DDP A01                  | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 054KM3 A00                  | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| Gigabyte      | B650M DS3H                  | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| HP            | 802F                        | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| Gigabyte      | 970A-D3                     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | H81M-C                      | [8b44a7deaa](https://linux-hardware.org/?probe=8b44a7deaa) | Nov 21, 2022 |
| ASUSTek       | H81M-C                      | [e60a1f8fc4](https://linux-hardware.org/?probe=e60a1f8fc4) | Nov 20, 2022 |
| HP            | 82F2 A01                    | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| ASRock        | B550M-ITX/ac                | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| Dell          | 0773VG A00                  | [576dfabbf6](https://linux-hardware.org/?probe=576dfabbf6) | Aug 29, 2022 |
| OEM           | Intel H81                   | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| OEM           | Intel H81                   | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| Gigabyte      | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Gigabyte      | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| HP            | 8062                        | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| Dell          | 088DT1 A01                  | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| ASUSTek       | ROG Maximus X APEX          | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [334719e6a2](https://linux-hardware.org/?probe=334719e6a2) | Jun 30, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| AFOX          | AF IH81-MA3 V1.0            | [4ce7ccc125](https://linux-hardware.org/?probe=4ce7ccc125) | Jun 24, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [e3bb4dee4b](https://linux-hardware.org/?probe=e3bb4dee4b) | Jun 17, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [3dbf1858d0](https://linux-hardware.org/?probe=3dbf1858d0) | May 27, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Intel         | D54250WYK H13922-305        | [6d1745c79b](https://linux-hardware.org/?probe=6d1745c79b) | May 11, 2022 |
| Dell          | 00V62H A00                  | [e765b34181](https://linux-hardware.org/?probe=e765b34181) | May 11, 2022 |
| HP            | 18E7                        | [52a59840d8](https://linux-hardware.org/?probe=52a59840d8) | May 09, 2022 |
| ASRock        | H370 Pro4                   | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| ASUSTek       | H81M-E                      | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| ASRock        | H410M-HDV R2.0              | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | Z170-K                      | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASRock        | M3A770DE                    | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| ASRock        | M3A770DE                    | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | 0YXT71 A02                  | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Gigabyte      | F2A68HM-DS2                 | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | 880GM-LE FX                 | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| ASUSTek       | M2N68-AM Plus               | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| ASUSTek       | H81M-A                      | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Dell          | 0D24M8 A00                  | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| ASRock        | B450M Steel Legend          | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| ASRock        | B450M Steel Legend          | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| ASRock        | H81M-HDS R2.0               | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| ASRock        | H110M-DVS R3.0              | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | B450M MORTAR MAX            | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| MSI           | A320M-A PRO MAX             | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| Intel         | H61M S1                     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| Acer          | Veriton X2665G              | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Huanan        | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| ASRock        | B450M Steel Legend          | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Gigabyte      | Z490 UD                     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Gigabyte      | F2A75M-HD2                  | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| HP            | 1998                        | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Dell          | 0F8096                      | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Dell          | 0F8096                      | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Acer          | Aspire M1935                | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| Fujitsu       | JIM76YK3                    | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| ASRock        | Z390 Pro4                   | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Unknown       | Unknown                     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASRock        | Z270 Killer SLI             | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Gigabyte      | F2A85XM-HD3                 | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| ASRock        | B460M Steel Legend          | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| ASRock        | B450M Steel Legend          | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Dell          | 0X8DXD A01                  | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| ASRock        | B450 Pro4                   | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| ASUSTek       | H61M-D                      | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | S340MF                      | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| Gigabyte      | Z390 UD                     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| ASUSTek       | Z170-P D3                   | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | M2N                         | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | Z170-P D3                   | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Unknown       | Unknown                     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Pegatron      | 2A99                        | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Packard Be... | IMEDIA S3720                | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Aspire XC-330               | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | 3048h                       | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| HP            | 2B15A                       | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| ASUSTek       | H110M-E/M.2                 | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| MSI           | H110M PRO-VD PLUS           | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| ASUSTek       | H81M-CS                     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| ASUSTek       | H81M-E                      | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| Gigabyte      | F2A88XM-HD3P                | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Biostar       | A10N-8800E                  | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| ASUSTek       | P7P55 LX                    | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| ASRock        | Z77 Pro4                    | [f0f2be33be](https://linux-hardware.org/?probe=f0f2be33be) | Apr 04, 2019 |
| ASRock        | Z77 Pro4                    | [04a8af85b2](https://linux-hardware.org/?probe=04a8af85b2) | Apr 03, 2019 |
| ASUSTek       | P8H61-M LE                  | [31229ee6d4](https://linux-hardware.org/?probe=31229ee6d4) | Feb 04, 2019 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [64fa4eaf5e](https://linux-hardware.org/?probe=64fa4eaf5e) | Nov 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 31       | 12.35%  |
| Ubuntu 18.04                 | 23       | 9.16%   |
| Ubuntu 22.04                 | 19       | 7.57%   |
| OpenMandriva 4.3             | 9        | 3.59%   |
| Fedora 38                    | 8        | 3.19%   |
| OpenMandriva 4.2             | 7        | 2.79%   |
| Manjaro                      | 7        | 2.79%   |
| Arch Rolling                 | 7        | 2.79%   |
| OpenMandriva 23.08           | 6        | 2.39%   |
| Debian 12                    | 5        | 1.99%   |
| ArcoLinux Rolling            | 5        | 1.99%   |
| OpenMandriva 23.01           | 4        | 1.59%   |
| Fedora 39                    | 4        | 1.59%   |
| Fedora 37                    | 4        | 1.59%   |
| Zorin 16                     | 3        | 1.2%    |
| Xubuntu 20.04                | 3        | 1.2%    |
| Xubuntu 18.04                | 3        | 1.2%    |
| Ubuntu 22.10                 | 3        | 1.2%    |
| Pop!_OS 22.04                | 3        | 1.2%    |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.2%    |
| KDE neon 20.04               | 3        | 1.2%    |
| Debian 11                    | 3        | 1.2%    |
| Zorin 15                     | 2        | 0.8%    |
| Ubuntu 21.10                 | 2        | 0.8%    |
| Ubuntu 21.04                 | 2        | 0.8%    |
| Ubuntu 19.10                 | 2        | 0.8%    |
| Reborn OS                    | 2        | 0.8%    |
| OpenMandriva 5.0             | 2        | 0.8%    |
| OpenMandriva 23.03           | 2        | 0.8%    |
| Linux Mint 21.2              | 2        | 0.8%    |
| Linux Mint 21                | 2        | 0.8%    |
| Linux Mint 20.3              | 2        | 0.8%    |
| Linux Mint 20                | 2        | 0.8%    |
| Linux Mint 19.3              | 2        | 0.8%    |
| Kubuntu 22.04                | 2        | 0.8%    |
| Fedora 40                    | 2        | 0.8%    |
| Fedora 36                    | 2        | 0.8%    |
| Endless 3.9.5                | 2        | 0.8%    |
| Endless 3.7.6                | 2        | 0.8%    |
| Arch                         | 2        | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 83       | 35.02%  |
| OpenMandriva  | 32       | 13.5%   |
| Fedora        | 21       | 8.86%   |
| Linux Mint    | 13       | 5.49%   |
| Debian        | 10       | 4.22%   |
| Arch          | 9        | 3.8%    |
| Xubuntu       | 7        | 2.95%   |
| Pop!_OS       | 7        | 2.95%   |
| Manjaro       | 7        | 2.95%   |
| Zorin         | 6        | 2.53%   |
| Endless       | 6        | 2.53%   |
| ArcoLinux     | 5        | 2.11%   |
| openSUSE      | 4        | 1.69%   |
| KDE neon      | 4        | 1.69%   |
| Reborn OS     | 2        | 0.84%   |
| Kubuntu       | 2        | 0.84%   |
| Kali          | 2        | 0.84%   |
| Elementary    | 2        | 0.84%   |
| Clear Linux   | 2        | 0.84%   |
| CentOS        | 2        | 0.84%   |
| Xero          | 1        | 0.42%   |
| UbuntuDDE     | 1        | 0.42%   |
| Ubuntu MATE   | 1        | 0.42%   |
| Ubuntu Budgie | 1        | 0.42%   |
| TUXEDO OS     | 1        | 0.42%   |
| SteamOS       | 1        | 0.42%   |
| Solus         | 1        | 0.42%   |
| Nobara        | 1        | 0.42%   |
| GNOME OS      | 1        | 0.42%   |
| BlackPanther  | 1        | 0.42%   |
| Archcraft     | 1        | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 7        | 2.55%   |
| 5.10.14-desktop-1omv4002 | 7        | 2.55%   |
| 6.4.11-desktop-1omv2390  | 6        | 2.18%   |
| 6.1.1-desktop-1omv2290   | 4        | 1.45%   |
| 5.4.0-48-generic         | 4        | 1.45%   |
| 5.15.0-56-generic        | 4        | 1.45%   |
| 5.15.0-46-generic        | 4        | 1.45%   |
| 6.2.0-32-generic         | 3        | 1.09%   |
| 5.8.0-14-generic         | 3        | 1.09%   |
| 5.4.0-42-generic         | 3        | 1.09%   |
| 5.15.0-43-generic        | 3        | 1.09%   |
| 6.6.2-desktop-1omv2390   | 2        | 0.73%   |
| 6.4.15-200.fc38.x86_64   | 2        | 0.73%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.73%   |
| 6.2.15-300.fc38.x86_64   | 2        | 0.73%   |
| 6.2.0-37-generic         | 2        | 0.73%   |
| 6.2.0-26-generic         | 2        | 0.73%   |
| 6.1.0-kali5-amd64        | 2        | 0.73%   |
| 6.1.0-12-amd64           | 2        | 0.73%   |
| 5.8.0-63-generic         | 2        | 0.73%   |
| 5.4.0-77-generic         | 2        | 0.73%   |
| 5.4.0-66-generic         | 2        | 0.73%   |
| 5.4.0-65-generic         | 2        | 0.73%   |
| 5.4.0-59-generic         | 2        | 0.73%   |
| 5.4.0-45-generic         | 2        | 0.73%   |
| 5.4.0-37-generic         | 2        | 0.73%   |
| 5.3.0-23-generic         | 2        | 0.73%   |
| 5.19.0-76051900-generic  | 2        | 0.73%   |
| 5.19.0-35-generic        | 2        | 0.73%   |
| 5.17.5-76051705-generic  | 2        | 0.73%   |
| 5.17.3-arch1-1           | 2        | 0.73%   |
| 5.16.13-desktop-1omv4003 | 2        | 0.73%   |
| 5.15.0-71-generic        | 2        | 0.73%   |
| 5.13.0-51-generic        | 2        | 0.73%   |
| 5.13.0-22-generic        | 2        | 0.73%   |
| 5.11.0-41-generic        | 2        | 0.73%   |
| 5.11.0-37-generic        | 2        | 0.73%   |
| 5.0.0-37-generic         | 2        | 0.73%   |
| 5.0.0-23-generic         | 2        | 0.73%   |
| 6.8.7-300.fc40.x86_64    | 1        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 34       | 12.64%  |
| 5.15.0  | 22       | 8.18%   |
| 5.8.0   | 12       | 4.46%   |
| 5.13.0  | 12       | 4.46%   |
| 4.15.0  | 11       | 4.09%   |
| 6.2.0   | 9        | 3.35%   |
| 6.5.0   | 8        | 2.97%   |
| 5.3.0   | 8        | 2.97%   |
| 6.4.11  | 7        | 2.6%    |
| 5.19.0  | 7        | 2.6%    |
| 5.16.7  | 7        | 2.6%    |
| 5.11.0  | 7        | 2.6%    |
| 5.10.14 | 7        | 2.6%    |
| 5.0.0   | 7        | 2.6%    |
| 6.1.0   | 6        | 2.23%   |
| 4.18.0  | 5        | 1.86%   |
| 6.1.1   | 4        | 1.49%   |
| 6.2.6   | 3        | 1.12%   |
| 5.17.5  | 3        | 1.12%   |
| 5.10.0  | 3        | 1.12%   |
| 6.8.0   | 2        | 0.74%   |
| 6.6.2   | 2        | 0.74%   |
| 6.6.1   | 2        | 0.74%   |
| 6.5.7   | 2        | 0.74%   |
| 6.5.5   | 2        | 0.74%   |
| 6.4.15  | 2        | 0.74%   |
| 6.2.15  | 2        | 0.74%   |
| 6.2.14  | 2        | 0.74%   |
| 6.0.12  | 2        | 0.74%   |
| 5.5.7   | 2        | 0.74%   |
| 5.17.3  | 2        | 0.74%   |
| 5.16.13 | 2        | 0.74%   |
| 6.8.7   | 1        | 0.37%   |
| 6.7.7   | 1        | 0.37%   |
| 6.7.3   | 1        | 0.37%   |
| 6.7.0   | 1        | 0.37%   |
| 6.6.8   | 1        | 0.37%   |
| 6.6.7   | 1        | 0.37%   |
| 6.6.4   | 1        | 0.37%   |
| 6.5.6   | 1        | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 13.91%  |
| 5.15    | 25       | 9.4%    |
| 6.2     | 19       | 7.14%   |
| 6.5     | 17       | 6.39%   |
| 5.13    | 15       | 5.64%   |
| 6.1     | 14       | 5.26%   |
| 5.16    | 14       | 5.26%   |
| 5.8     | 13       | 4.89%   |
| 5.10    | 11       | 4.14%   |
| 4.15    | 11       | 4.14%   |
| 6.4     | 10       | 3.76%   |
| 5.3     | 9        | 3.38%   |
| 5.19    | 8        | 3.01%   |
| 5.17    | 8        | 3.01%   |
| 5.0     | 8        | 3.01%   |
| 6.6     | 7        | 2.63%   |
| 5.11    | 7        | 2.63%   |
| 6.3     | 6        | 2.26%   |
| 4.18    | 5        | 1.88%   |
| 6.8     | 3        | 1.13%   |
| 6.7     | 3        | 1.13%   |
| 5.6     | 3        | 1.13%   |
| 6.0     | 2        | 0.75%   |
| 5.5     | 2        | 0.75%   |
| 5.14    | 2        | 0.75%   |
| 5.9     | 1        | 0.38%   |
| 5.7     | 1        | 0.38%   |
| 5.18    | 1        | 0.38%   |
| 5.12    | 1        | 0.38%   |
| 5.1     | 1        | 0.38%   |
| 4.4     | 1        | 0.38%   |
| 4.17    | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 224      | 99.56%  |
| i686   | 1        | 0.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 120      | 50.63%  |
| KDE5             | 42       | 17.72%  |
| Unknown          | 23       | 9.7%    |
| XFCE             | 16       | 6.75%   |
| X-Cinnamon       | 13       | 5.49%   |
| LXQt             | 4        | 1.69%   |
| MATE             | 3        | 1.27%   |
| KDE              | 3        | 1.27%   |
| Cinnamon         | 3        | 1.27%   |
| Pantheon         | 2        | 0.84%   |
| Deepin           | 2        | 0.84%   |
| Budgie           | 2        | 0.84%   |
| lightdm-xsession | 1        | 0.42%   |
| KDE6             | 1        | 0.42%   |
| i3               | 1        | 0.42%   |
| bspwm            | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 158      | 68.1%   |
| Wayland | 55       | 23.71%  |
| Unknown | 14       | 6.03%   |
| Tty     | 5        | 2.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 121      | 51.49%  |
| SDDM    | 42       | 17.87%  |
| GDM3    | 32       | 13.62%  |
| GDM     | 22       | 9.36%   |
| LightDM | 15       | 6.38%   |
| TDM     | 3        | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 165      | 71.43%  |
| Unknown | 16       | 6.93%   |
| th_TH   | 15       | 6.49%   |
| en_GB   | 12       | 5.19%   |
| de_DE   | 9        | 3.9%    |
| C       | 6        | 2.6%    |
| it_IT   | 3        | 1.3%    |
| fi_FI   | 2        | 0.87%   |
| sv_SE   | 1        | 0.43%   |
| fr_FR   | 1        | 0.43%   |
| de_CH   | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 133      | 56.84%  |
| EFI  | 101      | 43.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 156      | 66.38%  |
| Overlay | 26       | 11.06%  |
| Btrfs   | 26       | 11.06%  |
| Tmpfs   | 18       | 7.66%   |
| Xfs     | 4        | 1.7%    |
| Unknown | 4        | 1.7%    |
| Zfs     | 1        | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 128      | 54.7%   |
| GPT     | 92       | 39.32%  |
| MBR     | 14       | 5.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 78.45%  |
| Yes       | 50       | 21.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 149      | 64.5%   |
| Yes       | 82       | 35.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 49       | 21.78%  |
| ASUSTek Computer    | 42       | 18.67%  |
| ASRock              | 35       | 15.56%  |
| Dell                | 25       | 11.11%  |
| MSI                 | 17       | 7.56%   |
| Hewlett-Packard     | 13       | 5.78%   |
| Acer                | 12       | 5.33%   |
| Lenovo              | 4        | 1.78%   |
| Intel               | 4        | 1.78%   |
| Unknown             | 3        | 1.33%   |
| MiTAC               | 2        | 0.89%   |
| Huanan              | 2        | 0.89%   |
| Biostar             | 2        | 0.89%   |
| Apple               | 2        | 0.89%   |
| ViewSonic           | 1        | 0.44%   |
| VIA Technologies    | 1        | 0.44%   |
| Supermicro          | 1        | 0.44%   |
| SHARKBAY            | 1        | 0.44%   |
| Pegatron            | 1        | 0.44%   |
| Packard Bell        | 1        | 0.44%   |
| OEM                 | 1        | 0.44%   |
| Google              | 1        | 0.44%   |
| Fujitsu             | 1        | 0.44%   |
| ECS                 | 1        | 0.44%   |
| BESSTAR Tech        | 1        | 0.44%   |
| AMI                 | 1        | 0.44%   |
| AFOX                | 1        | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 7        | 3.11%   |
| Dell OptiPlex 7010         | 4        | 1.78%   |
| ASRock B450 Steel Legend   | 4        | 1.78%   |
| Unknown                    | 4        | 1.78%   |
| Dell Inspiron 3847         | 3        | 1.33%   |
| ASUS P8H61-M LE            | 3        | 1.33%   |
| HP Z240 Tower Workstation  | 2        | 0.89%   |
| HP EliteDesk 800 G1 SFF PC | 2        | 0.89%   |
| Gigabyte Z97X-UD3H-BK      | 2        | 0.89%   |
| Gigabyte H81M-DS2          | 2        | 0.89%   |
| Gigabyte H61M-DS2          | 2        | 0.89%   |
| Gigabyte H110M-DS2         | 2        | 0.89%   |
| Gigabyte F2A88XM-HD3P      | 2        | 0.89%   |
| Gigabyte F2A68HM-DS2       | 2        | 0.89%   |
| Gigabyte B250-HD3          | 2        | 0.89%   |
| Dell OptiPlex 9020         | 2        | 0.89%   |
| Dell OptiPlex 7050         | 2        | 0.89%   |
| Dell OptiPlex 3020         | 2        | 0.89%   |
| ASUS TUF Gaming B550M-E    | 2        | 0.89%   |
| ASUS H110M-E/M.2           | 2        | 0.89%   |
| ASRock B450M Steel Legend  | 2        | 0.89%   |
| Acer Veriton N4640G        | 2        | 0.89%   |
| Acer Aspire TC-885         | 2        | 0.89%   |
| ViewSonic VPC14-WP         | 1        | 0.44%   |
| VIA VX900                  | 1        | 0.44%   |
| Supermicro AT350 F3        | 1        | 0.44%   |
| Pegatron CQ3476L           | 1        | 0.44%   |
| Packard Bell IMEDIA S3720  | 1        | 0.44%   |
| OEM Intel H81              | 1        | 0.44%   |
| MSI Pro 3130 Microtower PC | 1        | 0.44%   |
| MSI Pro 2000/2080          | 1        | 0.44%   |
| MSI p6772l                 | 1        | 0.44%   |
| MSI MS-7C52                | 1        | 0.44%   |
| MSI MS-7C35                | 1        | 0.44%   |
| MSI MS-7C02                | 1        | 0.44%   |
| MSI MS-7B89                | 1        | 0.44%   |
| MSI MS-7B85                | 1        | 0.44%   |
| MSI MS-7A63                | 1        | 0.44%   |
| MSI MS-7A38                | 1        | 0.44%   |
| MSI MS-7A32                | 1        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 16       | 7.11%   |
| ASUS PRIME             | 8        | 3.56%   |
| ASUS All               | 7        | 3.11%   |
| ASRock B450            | 6        | 2.67%   |
| Acer Veriton           | 6        | 2.67%   |
| Acer Aspire            | 6        | 2.67%   |
| Dell Precision         | 4        | 1.78%   |
| ASUS ROG               | 4        | 1.78%   |
| ASRock B450M           | 4        | 1.78%   |
| Unknown                | 4        | 1.78%   |
| HP ProDesk             | 3        | 1.33%   |
| HP Compaq              | 3        | 1.33%   |
| Dell Inspiron          | 3        | 1.33%   |
| ASUS P8H61-M           | 3        | 1.33%   |
| ASUS M5A78L-M          | 3        | 1.33%   |
| MSI Pro                | 2        | 0.89%   |
| Lenovo ThinkCentre     | 2        | 0.89%   |
| Huanan X79             | 2        | 0.89%   |
| HP Z240                | 2        | 0.89%   |
| HP EliteDesk           | 2        | 0.89%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 0.89%   |
| Gigabyte Z390          | 2        | 0.89%   |
| Gigabyte H81M-DS2      | 2        | 0.89%   |
| Gigabyte H61M-DS2      | 2        | 0.89%   |
| Gigabyte H310M         | 2        | 0.89%   |
| Gigabyte H110M-DS2     | 2        | 0.89%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.89%   |
| Gigabyte F2A88XM-HD3P  | 2        | 0.89%   |
| Gigabyte F2A68HM-DS2   | 2        | 0.89%   |
| Gigabyte B550M         | 2        | 0.89%   |
| Gigabyte B450M         | 2        | 0.89%   |
| Gigabyte B450          | 2        | 0.89%   |
| Gigabyte B250-HD3      | 2        | 0.89%   |
| Dell Vostro            | 2        | 0.89%   |
| ASUS TUF               | 2        | 0.89%   |
| ASUS H110M-E           | 2        | 0.89%   |
| ASRock Z77             | 2        | 0.89%   |
| ASRock B550M           | 2        | 0.89%   |
| ViewSonic VPC14-WP     | 1        | 0.44%   |
| VIA VX900              | 1        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 28       | 12.44%  |
| 2013 | 24       | 10.67%  |
| 2020 | 23       | 10.22%  |
| 2016 | 18       | 8%      |
| 2014 | 18       | 8%      |
| 2019 | 17       | 7.56%   |
| 2012 | 17       | 7.56%   |
| 2017 | 16       | 7.11%   |
| 2011 | 12       | 5.33%   |
| 2021 | 10       | 4.44%   |
| 2009 | 10       | 4.44%   |
| 2015 | 8        | 3.56%   |
| 2010 | 7        | 3.11%   |
| 2008 | 7        | 3.11%   |
| 2023 | 4        | 1.78%   |
| 2022 | 2        | 0.89%   |
| 2006 | 2        | 0.89%   |
| 2007 | 1        | 0.44%   |
| 2005 | 1        | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 225      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 220      | 96.92%  |
| Enabled  | 7        | 3.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 224      | 99.56%  |
| Yes  | 1        | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 57       | 24.26%  |
| 8.01-16.0       | 48       | 20.43%  |
| 4.01-8.0        | 47       | 20%     |
| 3.01-4.0        | 36       | 15.32%  |
| 32.01-64.0      | 27       | 11.49%  |
| 1.01-2.0        | 8        | 3.4%    |
| 64.01-256.0     | 6        | 2.55%   |
| 24.01-32.0      | 4        | 1.7%    |
| More than 256.0 | 1        | 0.43%   |
| 0.51-1.0        | 1        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 95       | 36.68%  |
| 2.01-3.0   | 80       | 30.89%  |
| 3.01-4.0   | 31       | 11.97%  |
| 4.01-8.0   | 28       | 10.81%  |
| 0.51-1.0   | 12       | 4.63%   |
| 8.01-16.0  | 8        | 3.09%   |
| 16.01-24.0 | 3        | 1.16%   |
| 24.01-32.0 | 1        | 0.39%   |
| 0.01-0.5   | 1        | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 38.68%  |
| 2      | 72       | 29.63%  |
| 3      | 40       | 16.46%  |
| 4      | 15       | 6.17%   |
| 5      | 9        | 3.7%    |
| 0      | 5        | 2.06%   |
| 6      | 3        | 1.23%   |
| 7      | 2        | 0.82%   |
| 51     | 1        | 0.41%   |
| 32     | 1        | 0.41%   |
| 10     | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 64.47%  |
| Yes       | 81       | 35.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 220      | 97.78%  |
| No        | 5        | 2.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 52.38%  |
| No        | 110      | 47.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 150      | 64.38%  |
| Yes       | 83       | 35.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 225      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bangkok                  | 85       | 35.71%  |
| Chiang Mai               | 19       | 7.98%   |
| Khon Kaen                | 10       | 4.2%    |
| Phuket                   | 8        | 3.36%   |
| Nakhon Ratchasima        | 7        | 2.94%   |
| Nakhon Pathom            | 7        | 2.94%   |
| Chon Buri                | 6        | 2.52%   |
| Bang Lamung              | 6        | 2.52%   |
| Songkhla                 | 4        | 1.68%   |
| Mueang Samut Prakan      | 4        | 1.68%   |
| Ban Nong Sala            | 4        | 1.68%   |
| Surin                    | 3        | 1.26%   |
| Pattaya                  | 3        | 1.26%   |
| Nonthaburi               | 3        | 1.26%   |
| Ban Du                   | 3        | 1.26%   |
| Si Racha                 | 2        | 0.84%   |
| Phitsanulok              | 2        | 0.84%   |
| Pathum Thani             | 2        | 0.84%   |
| Pak Kret                 | 2        | 0.84%   |
| Lampang                  | 2        | 0.84%   |
| Hua Hin                  | 2        | 0.84%   |
| Bang Khae                | 2        | 0.84%   |
| Ban Phan Don             | 2        | 0.84%   |
| Ban Bang Tanot           | 2        | 0.84%   |
| Yarang                   | 1        | 0.42%   |
| Wihan Daeng              | 1        | 0.42%   |
| Wichian Buri             | 1        | 0.42%   |
| Trat                     | 1        | 0.42%   |
| Thung Song               | 1        | 0.42%   |
| Tha Tako                 | 1        | 0.42%   |
| Surat Thani              | 1        | 0.42%   |
| Suan Luang               | 1        | 0.42%   |
| Sawang Daen Din          | 1        | 0.42%   |
| Saraburi                 | 1        | 0.42%   |
| San Sai                  | 1        | 0.42%   |
| Samut Songkhram          | 1        | 0.42%   |
| Samphanthawong           | 1        | 0.42%   |
| Ron Phibun               | 1        | 0.42%   |
| Phrom Khiri              | 1        | 0.42%   |
| Phra Nakhon Si Ayutthaya | 1        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 96       | 171    | 23.3%   |
| Seagate                     | 72       | 128    | 17.48%  |
| Samsung Electronics         | 38       | 62     | 9.22%   |
| SanDisk                     | 29       | 49     | 7.04%   |
| Kingston                    | 22       | 23     | 5.34%   |
| Toshiba                     | 16       | 60     | 3.88%   |
| HS-SSD-C100                 | 9        | 19     | 2.18%   |
| Hitachi                     | 9        | 9      | 2.18%   |
| Crucial                     | 8        | 8      | 1.94%   |
| Apacer                      | 8        | 10     | 1.94%   |
| Unknown                     | 7        | 12     | 1.7%    |
| Hikvision                   | 7        | 7      | 1.7%    |
| China                       | 7        | 11     | 1.7%    |
| Phison                      | 5        | 10     | 1.21%   |
| MAXIO Technology (Hangzhou) | 5        | 6      | 1.21%   |
| Intel                       | 5        | 5      | 1.21%   |
| Silicon Motion              | 4        | 5      | 0.97%   |
| KingSpec                    | 4        | 6      | 0.97%   |
| USB3.0                      | 3        | 3      | 0.73%   |
| TO Exter                    | 3        | 3      | 0.73%   |
| JMicron Technology          | 3        | 3      | 0.73%   |
| HGST                        | 3        | 11     | 0.73%   |
| GALAX                       | 3        | 3      | 0.73%   |
| Colorful                    | 3        | 4      | 0.73%   |
| A-DATA Technology           | 3        | 3      | 0.73%   |
| WALRAM                      | 2        | 2      | 0.49%   |
| Transcend                   | 2        | 2      | 0.49%   |
| SPCC                        | 2        | 2      | 0.49%   |
| SK hynix                    | 2        | 3      | 0.49%   |
| Realtek Semiconductor       | 2        | 2      | 0.49%   |
| Plextor                     | 2        | 2      | 0.49%   |
| Phison Electronics          | 2        | 2      | 0.49%   |
| Micron Technology           | 2        | 2      | 0.49%   |
| Lexar                       | 2        | 3      | 0.49%   |
| Hewlett-Packard             | 2        | 4      | 0.49%   |
| External                    | 2        | 2      | 0.49%   |
| Corsair                     | 2        | 2      | 0.49%   |
| Acer                        | 2        | 6      | 0.49%   |
| Verbatim                    | 1        | 1      | 0.24%   |
| SPCC M.2                    | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 10       | 2.1%    |
| Seagate ST1000DM010-2EP102 1TB                      | 9        | 1.89%   |
| Seagate ST1000DM003-1ER162 1TB                      | 7        | 1.47%   |
| Seagate ST2000VX008-2E3164 2TB                      | 6        | 1.26%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 5        | 1.05%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 5        | 1.05%   |
| WDC WD20EZAZ-00GGJB0 2TB                            | 5        | 1.05%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 5        | 1.05%   |
| WDC WD10EZEX-00WN4A0 1TB                            | 5        | 1.05%   |
| Samsung HD103SJ 1TB                                 | 5        | 1.05%   |
| Kingston SUV400S37120G 120GB SSD                    | 5        | 1.05%   |
| Kingston SA400S37240G 240GB SSD                     | 5        | 1.05%   |
| HS-SSD-C100 240G                                    | 5        | 1.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4        | 0.84%   |
| Toshiba DT01ACA100 1TB                              | 4        | 0.84%   |
| SanDisk NVMe SSD Drive 1TB                          | 4        | 0.84%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 4        | 0.84%   |
| Crucial CT500MX500SSD1 500GB                        | 4        | 0.84%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 3        | 0.63%   |
| WDC WD5000AAKX-001CA0 500GB                         | 3        | 0.63%   |
| WDC WD2002FAEX-007BA0 2TB                           | 3        | 0.63%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 3        | 0.63%   |
| WDC WD10EZEX-00MFCA0 1TB                            | 3        | 0.63%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 3        | 0.63%   |
| USB3.0 Super Speed 240GB                            | 3        | 0.63%   |
| Unknown SD/MMC/MS PRO 128GB                         | 3        | 0.63%   |
| TO Exter nal USB 3.0 500GB                          | 3        | 0.63%   |
| Seagate ST3500418AS 500GB                           | 3        | 0.63%   |
| Seagate ST2000DX002-2DV164 2TB                      | 3        | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                  | 3        | 0.63%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 3        | 0.63%   |
| SanDisk SDSSDA120G 120GB                            | 3        | 0.63%   |
| SanDisk NVMe SSD Drive 250GB                        | 3        | 0.63%   |
| Samsung SSD 850 120GB                               | 3        | 0.63%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 3        | 0.63%   |
| Samsung HD502IJ 500GB                               | 3        | 0.63%   |
| Phison NVMe SSD Drive 240GB                         | 3        | 0.63%   |
| Kingston SV300S37A120G 120GB SSD                    | 3        | 0.63%   |
| Intel SSDSC2CT060A3 64GB                            | 3        | 0.63%   |
| HS-SSD-C100 120G                                    | 3        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 76       | 126    | 38.58%  |
| Seagate             | 70       | 122    | 35.53%  |
| Toshiba             | 15       | 59     | 7.61%   |
| Samsung Electronics | 12       | 18     | 6.09%   |
| Hitachi             | 9        | 9      | 4.57%   |
| Unknown             | 4        | 9      | 2.03%   |
| TO Exter            | 3        | 3      | 1.52%   |
| HGST                | 3        | 11     | 1.52%   |
| JMicron Technology  | 2        | 2      | 1.02%   |
| Hewlett-Packard     | 1        | 3      | 0.51%   |
| Fujitsu             | 1        | 2      | 0.51%   |
| ASMedia             | 1        | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 34     | 16.31%  |
| Samsung Electronics | 18       | 27     | 12.77%  |
| Kingston            | 16       | 17     | 11.35%  |
| SanDisk             | 11       | 20     | 7.8%    |
| Crucial             | 8        | 8      | 5.67%   |
| Apacer              | 8        | 10     | 5.67%   |
| China               | 7        | 11     | 4.96%   |
| Intel               | 5        | 5      | 3.55%   |
| Hikvision           | 5        | 5      | 3.55%   |
| KingSpec            | 4        | 6      | 2.84%   |
| USB3.0              | 3        | 3      | 2.13%   |
| GALAX               | 3        | 3      | 2.13%   |
| A-DATA Technology   | 3        | 3      | 2.13%   |
| SPCC                | 2        | 2      | 1.42%   |
| Plextor             | 2        | 2      | 1.42%   |
| Micron Technology   | 2        | 2      | 1.42%   |
| Lexar               | 2        | 3      | 1.42%   |
| External            | 2        | 2      | 1.42%   |
| Colorful            | 2        | 3      | 1.42%   |
| Acer                | 2        | 6      | 1.42%   |
| WALRAM              | 1        | 1      | 0.71%   |
| Verbatim            | 1        | 1      | 0.71%   |
| Transcend           | 1        | 1      | 0.71%   |
| SPCC M.2            | 1        | 1      | 0.71%   |
| SK hynix            | 1        | 2      | 0.71%   |
| Pioneer             | 1        | 1      | 0.71%   |
| OCZ                 | 1        | 1      | 0.71%   |
| Intenso             | 1        | 12     | 0.71%   |
| HS-SSD-E100         | 1        | 1      | 0.71%   |
| Hewlett-Packard     | 1        | 1      | 0.71%   |
| DGM                 | 1        | 1      | 0.71%   |
| Corsair             | 1        | 1      | 0.71%   |
| addlink             | 1        | 1      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 152      | 365    | 44.06%  |
| SSD     | 111      | 197    | 32.17%  |
| NVMe    | 64       | 97     | 18.55%  |
| Unknown | 18       | 32     | 5.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 208      | 552    | 69.33%  |
| NVMe | 64       | 97     | 21.33%  |
| SAS  | 28       | 42     | 9.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 151      | 270    | 50.84%  |
| 0.51-1.0   | 83       | 133    | 27.95%  |
| 1.01-2.0   | 38       | 57     | 12.79%  |
| 3.01-4.0   | 13       | 61     | 4.38%   |
| 2.01-3.0   | 5        | 13     | 1.68%   |
| 4.01-10.0  | 5        | 17     | 1.68%   |
| 10.01-20.0 | 2        | 11     | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 69       | 28.4%   |
| 251-500        | 36       | 14.81%  |
| 501-1000       | 35       | 14.4%   |
| 1-20           | 28       | 11.52%  |
| 1001-2000      | 22       | 9.05%   |
| 2001-3000      | 15       | 6.17%   |
| More than 3000 | 14       | 5.76%   |
| 51-100         | 11       | 4.53%   |
| 21-50          | 8        | 3.29%   |
| Unknown        | 5        | 2.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 96       | 37.94%  |
| 21-50          | 41       | 16.21%  |
| 101-250        | 30       | 11.86%  |
| 51-100         | 28       | 11.07%  |
| 501-1000       | 18       | 7.11%   |
| 251-500        | 14       | 5.53%   |
| More than 3000 | 9        | 3.56%   |
| 1001-2000      | 9        | 3.56%   |
| Unknown        | 5        | 1.98%   |
| 2001-3000      | 3        | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 3        | 3      | 11.11%  |
| Seagate ST500DM002-1BD14 500GB           | 2        | 3      | 7.41%   |
| Samsung Electronics SSD 830 Series 128GB | 2        | 2      | 7.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1        | 1      | 3.7%    |
| WDC WD6402AAEX-00Y9A0 640GB              | 1        | 1      | 3.7%    |
| WDC WD20EZRX-00DC0B0 2TB                 | 1        | 1      | 3.7%    |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 3.7%    |
| WDC WD10PURX-64E5EY0 1TB                 | 1        | 1      | 3.7%    |
| WDC WD10EZEX-00WN4A0 1TB                 | 1        | 1      | 3.7%    |
| WDC WD1002FAEX-00Y9A0 1TB                | 1        | 1      | 3.7%    |
| USB3.0 Super Speed 240GB                 | 1        | 1      | 3.7%    |
| Toshiba HDWL110 1TB                      | 1        | 1      | 3.7%    |
| Seagate ST9120822AS 120GB                | 1        | 1      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 3.7%    |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 3.7%    |
| Seagate ST3500418AS 500GB                | 1        | 2      | 3.7%    |
| Seagate ST1000LM014-1EJ164 1TB           | 1        | 1      | 3.7%    |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 3.7%    |
| Samsung Electronics HD253GJ 250GB        | 1        | 1      | 3.7%    |
| Samsung Electronics HD103SJ 1TB          | 1        | 1      | 3.7%    |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 3.7%    |
| Hitachi HTS541612J9SA00 120GB            | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 34.62%  |
| Seagate             | 8        | 10     | 30.77%  |
| Samsung Electronics | 5        | 6      | 19.23%  |
| USB3.0              | 1        | 1      | 3.85%   |
| Toshiba             | 1        | 1      | 3.85%   |
| Kingston            | 1        | 1      | 3.85%   |
| Hitachi             | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 38.1%   |
| Seagate             | 8        | 10     | 38.1%   |
| Samsung Electronics | 3        | 4      | 14.29%  |
| Toshiba             | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 25     | 80%     |
| SSD  | 5        | 5      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 2        | 2      | 100%    |

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
| Detected | 160      | 419    | 61.78%  |
| Works    | 74       | 240    | 28.57%  |
| Malfunc  | 23       | 30     | 8.88%   |
| Failed   | 2        | 2      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 148      | 47.44%  |
| AMD                          | 67       | 21.47%  |
| SanDisk                      | 26       | 8.33%   |
| ASMedia Technology           | 14       | 4.49%   |
| Samsung Electronics          | 10       | 3.21%   |
| Phison Electronics           | 8        | 2.56%   |
| MAXIO Technology (Hangzhou)  | 8        | 2.56%   |
| Nvidia                       | 7        | 2.24%   |
| Kingston Technology Company  | 7        | 2.24%   |
| Silicon Motion               | 4        | 1.28%   |
| VIA Technologies             | 2        | 0.64%   |
| Realtek Semiconductor        | 2        | 0.64%   |
| Marvell Technology Group     | 2        | 0.64%   |
| Broadcom / LSI               | 2        | 0.64%   |
| Toshiba America Info Systems | 1        | 0.32%   |
| SK hynix                     | 1        | 0.32%   |
| Micron/Crucial Technology    | 1        | 0.32%   |
| LSI Logic / Symbios Logic    | 1        | 0.32%   |
| JMicron Technology           | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36       | 9.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 6.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22       | 5.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 4.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13       | 3.43%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 3.17%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 11       | 2.9%    |
| Intel SATA Controller [RAID mode]                                                       | 10       | 2.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 2.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.37%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 8        | 2.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 1.85%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 6        | 1.58%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 6        | 1.58%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 1.06%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 1.06%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1.06%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 1.06%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 3        | 0.79%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.79%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.79%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.79%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 0.53%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.53%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 189      | 60.38%  |
| NVMe | 65       | 20.77%  |
| IDE  | 43       | 13.74%  |
| RAID | 14       | 4.47%   |
| SAS  | 1        | 0.32%   |
| SCSI | 1        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 152      | 67.56%  |
| AMD          | 72       | 32%     |
| CentaurHauls | 1        | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 6        | 2.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 6        | 2.64%   |
| AMD Ryzen 5 3600 6-Core Processor       | 5        | 2.2%    |
| Intel Core i7-6700 CPU @ 3.40GHz        | 4        | 1.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 4        | 1.76%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 4        | 1.76%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 4        | 1.76%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 3        | 1.32%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 3        | 1.32%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 3        | 1.32%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 3        | 1.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3        | 1.32%   |
| Intel Core i3-7100 CPU @ 3.90GHz        | 3        | 1.32%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 3        | 1.32%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 3        | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 3        | 1.32%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 3        | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3        | 1.32%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 0.88%   |
| Intel Core i5-6400T CPU @ 2.20GHz       | 2        | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 2        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 2        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2        | 0.88%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 2        | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 0.88%   |
| Intel Core i5 CPU 750 @ 2.67GHz         | 2        | 0.88%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 2        | 0.88%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2        | 0.88%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 0.88%   |
| Intel Core i3-10100F CPU @ 3.60GHz      | 2        | 0.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 2        | 0.88%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 2        | 0.88%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 2        | 0.88%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 2        | 0.88%   |
| AMD Ryzen 5 3500 6-Core Processor       | 2        | 0.88%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2        | 0.88%   |
| AMD Ryzen 3 4300GE with Radeon Graphics | 2        | 0.88%   |
| AMD Phenom II X6 1055T Processor        | 2        | 0.88%   |
| AMD Athlon II X2 270 Processor          | 2        | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 49       | 21.68%  |
| Intel Core i3           | 35       | 15.49%  |
| Intel Core i7           | 27       | 11.95%  |
| AMD Ryzen 5             | 25       | 11.06%  |
| Intel Xeon              | 14       | 6.19%   |
| AMD Ryzen 7             | 8        | 3.54%   |
| AMD Ryzen 3             | 6        | 2.65%   |
| Intel Pentium           | 5        | 2.21%   |
| AMD FX                  | 5        | 2.21%   |
| AMD Athlon II X2        | 5        | 2.21%   |
| Intel Core i9           | 4        | 1.77%   |
| Intel Core 2 Quad       | 4        | 1.77%   |
| AMD Ryzen 9             | 4        | 1.77%   |
| AMD Athlon 64 X2        | 4        | 1.77%   |
| AMD A10                 | 4        | 1.77%   |
| Intel Pentium Dual-Core | 3        | 1.33%   |
| Intel Celeron           | 3        | 1.33%   |
| AMD A6                  | 3        | 1.33%   |
| Other                   | 2        | 0.88%   |
| Intel Core 2 Duo        | 2        | 0.88%   |
| AMD Phenom II X6        | 2        | 0.88%   |
| AMD Phenom II X4        | 2        | 0.88%   |
| AMD A4                  | 2        | 0.88%   |
| Intel Pentium Dual      | 1        | 0.44%   |
| Intel Pentium D         | 1        | 0.44%   |
| Intel Pentium 4         | 1        | 0.44%   |
| Intel Atom              | 1        | 0.44%   |
| CentaurHauls VIA Eden   | 1        | 0.44%   |
| AMD Ryzen 3 PRO         | 1        | 0.44%   |
| AMD Phenom II X3        | 1        | 0.44%   |
| AMD Athlon              | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 89       | 39.38%  |
| 2      | 63       | 27.88%  |
| 6      | 38       | 16.81%  |
| 8      | 18       | 7.96%   |
| 12     | 7        | 3.1%    |
| 1      | 4        | 1.77%   |
| 10     | 2        | 0.88%   |
| 3      | 2        | 0.88%   |
| 40     | 1        | 0.44%   |
| 24     | 1        | 0.44%   |
| 14     | 1        | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 220      | 97.78%  |
| 2      | 5        | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 137      | 60.62%  |
| 1      | 89       | 39.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 225      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 36.93%  |
| 0x306c3    | 19       | 7.88%   |
| 0x206a7    | 11       | 4.56%   |
| 0x506e3    | 10       | 4.15%   |
| 0x906ea    | 7        | 2.9%    |
| 0x906e9    | 7        | 2.9%    |
| 0x306a9    | 7        | 2.9%    |
| 0x1067a    | 6        | 2.49%   |
| 0x0800820d | 6        | 2.49%   |
| 0x06001119 | 5        | 2.07%   |
| 0x08701021 | 4        | 1.66%   |
| 0x010000c8 | 4        | 1.66%   |
| 0xa0655    | 3        | 1.24%   |
| 0x906ec    | 3        | 1.24%   |
| 0x406f1    | 3        | 1.24%   |
| 0x20655    | 3        | 1.24%   |
| 0x08001138 | 3        | 1.24%   |
| 0x906eb    | 2        | 0.83%   |
| 0x40651    | 2        | 0.83%   |
| 0x106e5    | 2        | 0.83%   |
| 0x0a50000c | 2        | 0.83%   |
| 0x0a201009 | 2        | 0.83%   |
| 0x08600106 | 2        | 0.83%   |
| 0x08108109 | 2        | 0.83%   |
| 0x06003106 | 2        | 0.83%   |
| 0x06000852 | 2        | 0.83%   |
| 0xf65      | 1        | 0.41%   |
| 0xf49      | 1        | 0.41%   |
| 0xa0653    | 1        | 0.41%   |
| 0x906ed    | 1        | 0.41%   |
| 0x6fd      | 1        | 0.41%   |
| 0x6fb      | 1        | 0.41%   |
| 0x50654    | 1        | 0.41%   |
| 0x406c3    | 1        | 0.41%   |
| 0x306e4    | 1        | 0.41%   |
| 0x30678    | 1        | 0.41%   |
| 0x206c2    | 1        | 0.41%   |
| 0x106ca    | 1        | 0.41%   |
| 0x10677    | 1        | 0.41%   |
| 0x10676    | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 35       | 15.49%  |
| KabyLake         | 25       | 11.06%  |
| Skylake          | 20       | 8.85%   |
| Zen 2            | 17       | 7.52%   |
| IvyBridge        | 16       | 7.08%   |
| SandyBridge      | 15       | 6.64%   |
| Zen+             | 12       | 5.31%   |
| Zen 3            | 9        | 3.98%   |
| Piledriver       | 9        | 3.98%   |
| Penryn           | 9        | 3.98%   |
| K10              | 9        | 3.98%   |
| CometLake        | 9        | 3.98%   |
| Zen              | 6        | 2.65%   |
| Westmere         | 6        | 2.65%   |
| Silvermont       | 4        | 1.77%   |
| K8 Hammer        | 4        | 1.77%   |
| Unknown          | 4        | 1.77%   |
| Broadwell        | 3        | 1.33%   |
| Steamroller      | 2        | 0.88%   |
| NetBurst         | 2        | 0.88%   |
| Nehalem          | 2        | 0.88%   |
| Excavator        | 2        | 0.88%   |
| Core             | 2        | 0.88%   |
| K10 Llano        | 1        | 0.44%   |
| IceLake          | 1        | 0.44%   |
| Bonnell          | 1        | 0.44%   |
| Alderlake Hybrid | 1        | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 92       | 37.25%  |
| Intel             | 85       | 34.41%  |
| AMD               | 68       | 27.53%  |
| VIA Technologies  | 1        | 0.4%    |
| ASPEED Technology | 1        | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14       | 5.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13       | 5.06%   |
| Intel HD Graphics 530                                                                    | 13       | 5.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 3.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8        | 3.11%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7        | 2.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 2.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6        | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6        | 2.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6        | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 1.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 1.56%   |
| Intel HD Graphics 630                                                                    | 4        | 1.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 1.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3        | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 3        | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.17%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 2        | 0.78%   |
| Nvidia GP107GL [Quadro P620]                                                             | 2        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.78%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2        | 0.78%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 2        | 0.78%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.78%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.78%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.78%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 79       | 33.47%  |
| 1 x Intel            | 72       | 30.51%  |
| 1 x AMD              | 63       | 26.69%  |
| Intel + Nvidia       | 7        | 2.97%   |
| AMD + Nvidia         | 4        | 1.69%   |
| 2 x AMD              | 3        | 1.27%   |
| 3 x Nvidia           | 1        | 0.42%   |
| 2 x Nvidia           | 1        | 0.42%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.42%   |
| 1 x VIA              | 1        | 0.42%   |
| Intel + 2 x Nvidia   | 1        | 0.42%   |
| Intel + AMD          | 1        | 0.42%   |
| 1 x ASPEED           | 1        | 0.42%   |
| AMD + 2 x Nvidia     | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 178      | 76.39%  |
| Proprietary | 45       | 19.31%  |
| Unknown     | 10       | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 117      | 49.16%  |
| 1.01-2.0   | 32       | 13.45%  |
| 7.01-8.0   | 21       | 8.82%   |
| 0.51-1.0   | 20       | 8.4%    |
| 3.01-4.0   | 19       | 7.98%   |
| 0.01-0.5   | 17       | 7.14%   |
| 5.01-6.0   | 8        | 3.36%   |
| 4.01-5.0   | 1        | 0.42%   |
| 2.01-3.0   | 1        | 0.42%   |
| 16.01-24.0 | 1        | 0.42%   |
| 8.01-16.0  | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 47       | 20%     |
| Acer                 | 40       | 17.02%  |
| Goldstar             | 33       | 14.04%  |
| Dell                 | 18       | 7.66%   |
| Hewlett-Packard      | 16       | 6.81%   |
| AOC                  | 14       | 5.96%   |
| ViewSonic            | 6        | 2.55%   |
| LG Electronics       | 6        | 2.55%   |
| Lenovo               | 6        | 2.55%   |
| BenQ                 | 6        | 2.55%   |
| Unknown (XXX)        | 3        | 1.28%   |
| Ancor Communications | 3        | 1.28%   |
| Sharp                | 2        | 0.85%   |
| SGT                  | 2        | 0.85%   |
| Philips              | 2        | 0.85%   |
| MStar                | 2        | 0.85%   |
| MSI                  | 2        | 0.85%   |
| Microstep            | 2        | 0.85%   |
| IOD                  | 2        | 0.85%   |
| Fujitsu              | 2        | 0.85%   |
| Apple                | 2        | 0.85%   |
| ___                  | 1        | 0.43%   |
| Unknown              | 1        | 0.43%   |
| Toshiba              | 1        | 0.43%   |
| Sony                 | 1        | 0.43%   |
| SKY                  | 1        | 0.43%   |
| RTK                  | 1        | 0.43%   |
| MIG                  | 1        | 0.43%   |
| JRY                  | 1        | 0.43%   |
| ITE                  | 1        | 0.43%   |
| HUYINIUDA            | 1        | 0.43%   |
| HPN                  | 1        | 0.43%   |
| HJW                  | 1        | 0.43%   |
| Gateway              | 1        | 0.43%   |
| Fujitsu Siemens      | 1        | 0.43%   |
| Envision Peripherals | 1        | 0.43%   |
| CMT                  | 1        | 0.43%   |
| CHI                  | 1        | 0.43%   |
| ASUSTek Computer     | 1        | 0.43%   |
| Unknown              | 1        | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 4        | 1.59%   |
| Acer K222HQL ACR0512 1920x1080 477x268mm 21.5-inch                    | 4        | 1.59%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 1.19%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                      | 3        | 1.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 1.19%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 3        | 1.19%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 3        | 1.19%   |
| AOC 2381 AOC2381 1920x1080 509x286mm 23.0-inch                        | 3        | 1.19%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2        | 0.79%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2        | 0.79%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2        | 0.79%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 0.79%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch     | 2        | 0.79%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.79%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 2        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 2        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2        | 0.79%   |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                   | 2        | 0.79%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2        | 0.79%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2        | 0.79%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch            | 2        | 0.79%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.79%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.79%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 2        | 0.79%   |
| Goldstar E1940 GSM4BD7 1360x768 406x229mm 18.4-inch                   | 2        | 0.79%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2        | 0.79%   |
| Dell P2422H DELA1C4 1920x1080 530x300mm 24.0-inch                     | 2        | 0.79%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.79%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                      | 2        | 0.79%   |
| Acer S200HQL  ACR0359 1600x900 430x240mm 19.4-inch                    | 2        | 0.79%   |
| Acer P193WA ACR000C 1440x900 410x256mm 19.0-inch                      | 2        | 0.79%   |
| Acer K242HQL ACR042E 1920x1080 509x286mm 23.0-inch                    | 2        | 0.79%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.4%    |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                | 1        | 0.4%    |
| ViewSonic VA1703wSERIES VSC121F 1440x900 367x230mm 17.1-inch          | 1        | 0.4%    |
| ViewSonic LCD Monitor VX3276-QHD 5120x1440                            | 1        | 0.4%    |
| ViewSonic IFP7550 VSC36CD 3840x2160 1660x930mm 74.9-inch              | 1        | 0.4%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 0.4%    |
| Unknown (XXX) Union TV XXX2841 1920x1080 1210x680mm 54.6-inch         | 1        | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 111      | 48.26%  |
| 1600x900 (HD+)     | 20       | 8.7%    |
| 1366x768 (WXGA)    | 18       | 7.83%   |
| 3840x2160 (4K)     | 15       | 6.52%   |
| 2560x1440 (QHD)    | 11       | 4.78%   |
| 1440x900 (WXGA+)   | 11       | 4.78%   |
| 1680x1050 (WSXGA+) | 8        | 3.48%   |
| 1360x768           | 8        | 3.48%   |
| 2560x1080          | 5        | 2.17%   |
| 1280x1024 (SXGA)   | 5        | 2.17%   |
| Unknown            | 5        | 2.17%   |
| 3840x1080          | 2        | 0.87%   |
| 3440x1440          | 2        | 0.87%   |
| 1920x1200 (WUXGA)  | 2        | 0.87%   |
| 1600x1200          | 2        | 0.87%   |
| 5120x1440          | 1        | 0.43%   |
| 2732x768           | 1        | 0.43%   |
| 2560x1600          | 1        | 0.43%   |
| 1280x960           | 1        | 0.43%   |
| 1280x720 (HD)      | 1        | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 39       | 16.46%  |
| 21      | 28       | 11.81%  |
| 24      | 26       | 10.97%  |
| Unknown | 24       | 10.13%  |
| 27      | 22       | 9.28%   |
| 18      | 20       | 8.44%   |
| 20      | 19       | 8.02%   |
| 19      | 14       | 5.91%   |
| 34      | 7        | 2.95%   |
| 22      | 6        | 2.53%   |
| 17      | 4        | 1.69%   |
| 15      | 4        | 1.69%   |
| 84      | 3        | 1.27%   |
| 72      | 3        | 1.27%   |
| 54      | 3        | 1.27%   |
| 52      | 2        | 0.84%   |
| 32      | 2        | 0.84%   |
| 31      | 2        | 0.84%   |
| 26      | 2        | 0.84%   |
| 74      | 1        | 0.42%   |
| 60      | 1        | 0.42%   |
| 46      | 1        | 0.42%   |
| 40      | 1        | 0.42%   |
| 39      | 1        | 0.42%   |
| 29      | 1        | 0.42%   |
| 16      | 1        | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 84       | 37.33%  |
| 501-600     | 79       | 35.11%  |
| Unknown     | 24       | 10.67%  |
| 701-800     | 9        | 4%      |
| 301-350     | 8        | 3.56%   |
| 1001-1500   | 7        | 3.11%   |
| 1501-2000   | 6        | 2.67%   |
| 601-700     | 3        | 1.33%   |
| 351-400     | 3        | 1.33%   |
| 801-900     | 2        | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 157      | 72.35%  |
| 16/10   | 26       | 11.98%  |
| Unknown | 19       | 8.76%   |
| 21/9    | 7        | 3.23%   |
| 5/4     | 6        | 2.76%   |
| 4/3     | 1        | 0.46%   |
| 2.00    | 1        | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 36.32%  |
| 151-200        | 40       | 17.09%  |
| Unknown        | 24       | 10.26%  |
| 301-350        | 23       | 9.83%   |
| 141-150        | 20       | 8.55%   |
| More than 1000 | 12       | 5.13%   |
| 351-500        | 12       | 5.13%   |
| 251-300        | 8        | 3.42%   |
| 101-110        | 4        | 1.71%   |
| 501-1000       | 3        | 1.28%   |
| 131-140        | 2        | 0.85%   |
| 121-130        | 1        | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 132      | 61.68%  |
| 101-120 | 41       | 19.16%  |
| Unknown | 24       | 11.21%  |
| 1-50    | 9        | 4.21%   |
| 161-240 | 4        | 1.87%   |
| 121-160 | 4        | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 183      | 77.22%  |
| 2     | 32       | 13.5%   |
| 0     | 16       | 6.75%   |
| 3     | 6        | 2.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 154      | 44.9%   |
| Intel                           | 83       | 24.2%   |
| Qualcomm Atheros                | 25       | 7.29%   |
| Ralink Technology               | 13       | 3.79%   |
| TP-Link                         | 10       | 2.92%   |
| D-Link                          | 10       | 2.92%   |
| Broadcom                        | 10       | 2.92%   |
| Nvidia                          | 6        | 1.75%   |
| Edimax Technology               | 4        | 1.17%   |
| Ralink                          | 3        | 0.87%   |
| MediaTek                        | 3        | 0.87%   |
| D-Link System                   | 3        | 0.87%   |
| Broadcom Limited                | 3        | 0.87%   |
| Samsung Electronics             | 2        | 0.58%   |
| Mercucys                        | 2        | 0.58%   |
| ASUSTek Computer                | 2        | 0.58%   |
| Xiaomi                          | 1        | 0.29%   |
| VIA Technologies                | 1        | 0.29%   |
| Qualcomm Atheros Communications | 1        | 0.29%   |
| OPPO Electronics                | 1        | 0.29%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.29%   |
| Huawei Technologies             | 1        | 0.29%   |
| BUFFALO                         | 1        | 0.29%   |
| AVM                             | 1        | 0.29%   |
| Aquantia                        | 1        | 0.29%   |
| Adafruit                        | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 131      | 34.03%  |
| Intel Ethernet Connection I217-LM                                      | 9        | 2.34%   |
| Intel Wi-Fi 6 AX200                                                    | 8        | 2.08%   |
| Intel I211 Gigabit Network Connection                                  | 8        | 2.08%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 1.3%    |
| Ralink MT7601U Wireless Adapter                                        | 5        | 1.3%    |
| Intel Ethernet Connection I217-V                                       | 5        | 1.3%    |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]          | 5        | 1.3%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 4        | 1.04%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.04%   |
| Intel Wireless 7260                                                    | 4        | 1.04%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.04%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4        | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3        | 0.78%   |
| Realtek 802.11ac NIC                                                   | 3        | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.52%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 2        | 0.52%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 2        | 0.52%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                   | 2        | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.52%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 29       | 21.17%  |
| Intel                           | 29       | 21.17%  |
| Qualcomm Atheros                | 21       | 15.33%  |
| Ralink Technology               | 13       | 9.49%   |
| TP-Link                         | 10       | 7.3%    |
| D-Link                          | 10       | 7.3%    |
| Broadcom                        | 5        | 3.65%   |
| Edimax Technology               | 4        | 2.92%   |
| Ralink                          | 3        | 2.19%   |
| MediaTek                        | 3        | 2.19%   |
| Mercucys                        | 2        | 1.46%   |
| Broadcom Limited                | 2        | 1.46%   |
| ASUSTek Computer                | 2        | 1.46%   |
| Qualcomm Atheros Communications | 1        | 0.73%   |
| D-Link System                   | 1        | 0.73%   |
| BUFFALO                         | 1        | 0.73%   |
| AVM                             | 1        | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 8        | 5.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7        | 5.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6        | 4.32%   |
| Ralink MT7601U Wireless Adapter                                      | 5        | 3.6%    |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]        | 5        | 3.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 4        | 2.88%   |
| Intel Wireless 7260                                                  | 4        | 2.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 3        | 2.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 2.16%   |
| Realtek 802.11ac NIC                                                 | 3        | 2.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3        | 2.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 2.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2        | 1.44%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2        | 1.44%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 2        | 1.44%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 2        | 1.44%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 2        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 1.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 1.44%   |
| Mercucys 802.11n NIC                                                 | 2        | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2        | 1.44%   |
| Intel Wireless 7265                                                  | 2        | 1.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2        | 1.44%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2        | 1.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 2        | 1.44%   |
| D-Link 802.11 n WLAN                                                 | 2        | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2        | 1.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1        | 0.72%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 0.72%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                           | 1        | 0.72%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.72%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1        | 0.72%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 0.72%   |
| TP-Link 802.11n NIC                                                  | 1        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 144      | 60.76%  |
| Intel                         | 67       | 28.27%  |
| Nvidia                        | 6        | 2.53%   |
| Qualcomm Atheros              | 5        | 2.11%   |
| Broadcom                      | 5        | 2.11%   |
| Samsung Electronics           | 2        | 0.84%   |
| D-Link System                 | 2        | 0.84%   |
| Xiaomi                        | 1        | 0.42%   |
| VIA Technologies              | 1        | 0.42%   |
| OPPO Electronics              | 1        | 0.42%   |
| OnePlus Technology (Shenzhen) | 1        | 0.42%   |
| Broadcom Limited              | 1        | 0.42%   |
| Aquantia                      | 1        | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 131      | 53.69%  |
| Intel Ethernet Connection I217-LM                                      | 9        | 3.69%   |
| Intel I211 Gigabit Network Connection                                  | 8        | 3.28%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 3.28%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 2.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 2.05%   |
| Intel Ethernet Connection I217-V                                       | 5        | 2.05%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.64%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.64%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4        | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4        | 1.64%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.82%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 0.82%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.82%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 0.82%   |
| Xiaomi 100Mbps Network Card Adapter                                    | 1        | 0.41%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                      | 1        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.41%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1        | 0.41%   |
| OnePlus (Shenzhen) OnePlus                                             | 1        | 0.41%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.41%   |
| Intel I210 Gigabit Unprogrammed                                        | 1        | 0.41%   |
| Intel Ethernet Connection I218-V                                       | 1        | 0.41%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.41%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 0.41%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 220      | 64.33%  |
| WiFi     | 120      | 35.09%  |
| Modem    | 2        | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 149      | 63.68%  |
| WiFi     | 85       | 36.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 143      | 62.72%  |
| 2     | 71       | 31.14%  |
| 3     | 7        | 3.07%   |
| 0     | 4        | 1.75%   |
| 4     | 2        | 0.88%   |
| 5     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 161      | 68.51%  |
| Yes  | 74       | 31.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 32       | 35.16%  |
| Intel                           | 26       | 28.57%  |
| Qualcomm Atheros Communications | 5        | 5.49%   |
| Realtek Semiconductor           | 4        | 4.4%    |
| ASUSTek Computer                | 4        | 4.4%    |
| Apple                           | 4        | 4.4%    |
| TP-Link                         | 3        | 3.3%    |
| MediaTek                        | 3        | 3.3%    |
| Lite-On Technology              | 2        | 2.2%    |
| IMC Networks                    | 2        | 2.2%    |
| Actions                         | 2        | 2.2%    |
| Toshiba                         | 1        | 1.1%    |
| Foxconn International           | 1        | 1.1%    |
| Broadcom                        | 1        | 1.1%    |
| Unknown                         | 1        | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 32       | 35.16%  |
| Intel AX200 Bluetooth                               | 8        | 8.79%   |
| Intel Bluetooth wireless interface                  | 7        | 7.69%   |
| TP-Link UB500 Adapter                               | 3        | 3.3%    |
| Realtek Bluetooth Radio                             | 3        | 3.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 3.3%    |
| MediaTek Wireless_Device                            | 3        | 3.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 3.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 3.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2        | 2.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2        | 2.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.2%    |
| IMC Networks Bluetooth Device                       | 2        | 2.2%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 2.2%    |
| Apple Bluetooth USB Host Controller                 | 2        | 2.2%    |
| Actions general adapter                             | 2        | 2.2%    |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 1.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.1%    |
| Intel Bluetooth Device                              | 1        | 1.1%    |
| Intel AX210 Bluetooth                               | 1        | 1.1%    |
| Intel AX201 Bluetooth                               | 1        | 1.1%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1        | 1.1%    |
| Broadcom HP Portable Valentine                      | 1        | 1.1%    |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.1%    |
| ASUS Bluetooth Device                               | 1        | 1.1%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 1.1%    |
| Apple Bluetooth HCI                                 | 1        | 1.1%    |
| Unknown                                             | 1        | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 150      | 39.68%  |
| AMD                                  | 92       | 24.34%  |
| Nvidia                               | 85       | 22.49%  |
| C-Media Electronics                  | 12       | 3.17%   |
| Razer USA                            | 4        | 1.06%   |
| JMTek                                | 4        | 1.06%   |
| Generalplus Technology               | 4        | 1.06%   |
| Elan Microelectronics                | 3        | 0.79%   |
| Creative Labs                        | 3        | 0.79%   |
| SAVITECH                             | 2        | 0.53%   |
| Logitech                             | 2        | 0.53%   |
| VIA Technologies                     | 1        | 0.26%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.26%   |
| Texas Instruments                    | 1        | 0.26%   |
| Syntek                               | 1        | 0.26%   |
| Nordic Semiconductor ASA             | 1        | 0.26%   |
| Kingston Technology                  | 1        | 0.26%   |
| Hewlett-Packard                      | 1        | 0.26%   |
| Focusrite-Novation                   | 1        | 0.26%   |
| ESS Technology                       | 1        | 0.26%   |
| Ensoniq                              | 1        | 0.26%   |
| Earth Computer Technologies          | 1        | 0.26%   |
| Blue Microphones                     | 1        | 0.26%   |
| Barco Display Systems                | 1        | 0.26%   |
| Audio-Technica                       | 1        | 0.26%   |
| Audient                              | 1        | 0.26%   |
| ASUSTek Computer                     | 1        | 0.26%   |
| Apple                                | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26       | 5.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22       | 4.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18       | 3.94%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 3.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 3.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 3.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 2.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12       | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.19%   |
| Nvidia High Definition Audio Controller                                    | 9        | 1.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 1.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 1.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 1.75%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 1.53%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.31%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.88%   |
| JMTek USB PnP Audio Device                                                 | 4        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 0.88%   |
| Generalplus Technology USB Audio Device                                    | 4        | 0.88%   |
| C-Media Electronics USB Audio Device                                       | 4        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 0.88%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 4        | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.66%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 48       | 41.38%  |
| SK hynix            | 16       | 13.79%  |
| Unknown             | 14       | 12.07%  |
| Samsung Electronics | 11       | 9.48%   |
| Corsair             | 10       | 8.62%   |
| Team                | 2        | 1.72%   |
| Micron Technology   | 2        | 1.72%   |
| G.Skill             | 2        | 1.72%   |
| Apacer              | 2        | 1.72%   |
| A-DATA Technology   | 2        | 1.72%   |
| Unknown             | 2        | 1.72%   |
| Unknown (0x02BA)    | 1        | 0.86%   |
| Transcend           | 1        | 0.86%   |
| Ramaxel Technology  | 1        | 0.86%   |
| KingFast            | 1        | 0.86%   |
| Hikvision           | 1        | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 5        | 3.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 2.27%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 3        | 2.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 3        | 2.27%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 3        | 2.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 1.52%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s    | 2        | 1.52%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s    | 2        | 1.52%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 2        | 1.52%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 2        | 1.52%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s  | 2        | 1.52%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.52%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.52%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s          | 2        | 1.52%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s     | 2        | 1.52%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 2        | 1.52%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 2        | 1.52%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 1.52%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 2        | 1.52%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1333MT/s   | 2        | 1.52%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s     | 2        | 1.52%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 2        | 1.52%   |
| Unknown                                                 | 2        | 1.52%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.76%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.76%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1        | 0.76%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 0.76%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s | 1        | 0.76%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s        | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3200MT/s      | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s     | 1        | 0.76%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 48       | 47.52%  |
| DDR3    | 33       | 32.67%  |
| SDRAM   | 6        | 5.94%   |
| DDR2    | 4        | 3.96%   |
| Unknown | 4        | 3.96%   |
| DDR5    | 2        | 1.98%   |
| DDR     | 2        | 1.98%   |
| LPDDR4  | 1        | 0.99%   |
| DRAM    | 1        | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 86       | 89.58%  |
| SODIMM  | 8        | 8.33%   |
| RIMM    | 1        | 1.04%   |
| FB-DIMM | 1        | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 39.45%  |
| 4096  | 32       | 29.36%  |
| 2048  | 14       | 12.84%  |
| 16384 | 10       | 9.17%   |
| 1024  | 6        | 5.5%    |
| 32768 | 4        | 3.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 16.52%  |
| 1333    | 17       | 14.78%  |
| 2400    | 12       | 10.43%  |
| 3200    | 8        | 6.96%   |
| 2133    | 8        | 6.96%   |
| 3733    | 5        | 4.35%   |
| 3600    | 5        | 4.35%   |
| 2667    | 5        | 4.35%   |
| 3400    | 4        | 3.48%   |
| 1867    | 4        | 3.48%   |
| 3466    | 3        | 2.61%   |
| 3000    | 3        | 2.61%   |
| 2666    | 3        | 2.61%   |
| 1866    | 3        | 2.61%   |
| 3151    | 2        | 1.74%   |
| 1800    | 2        | 1.74%   |
| 667     | 2        | 1.74%   |
| 533     | 2        | 1.74%   |
| 6800    | 1        | 0.87%   |
| 5808    | 1        | 0.87%   |
| 3534    | 1        | 0.87%   |
| 3333    | 1        | 0.87%   |
| 2800    | 1        | 0.87%   |
| 800     | 1        | 0.87%   |
| 333     | 1        | 0.87%   |
| Unknown | 1        | 0.87%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 5        | 50%     |
| Seiko Epson        | 2        | 20%     |
| STMicroelectronics | 1        | 10%     |
| Pantum             | 1        | 10%     |
| Canon              | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| STMicroelectronics USB Printing Support | 1        | 10%     |
| Seiko Epson LQ-310                      | 1        | 10%     |
| Seiko Epson L360 Series                 | 1        | 10%     |
| Pantum P2500W series                    | 1        | 10%     |
| Canon E4200 series                      | 1        | 10%     |
| Brother HL-1110 series                  | 1        | 10%     |
| Brother DCP-T510W                       | 1        | 10%     |
| Brother DCP-T300                        | 1        | 10%     |
| Brother DCP-L3551CDW                    | 1        | 10%     |
| Brother DCP-1510                        | 1        | 10%     |

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
| Logitech                      | 9        | 24.32%  |
| Microdia                      | 5        | 13.51%  |
| Sunplus Innovation Technology | 3        | 8.11%   |
| Microsoft                     | 3        | 8.11%   |
| Generalplus Technology        | 3        | 8.11%   |
| Aveo Technology               | 3        | 8.11%   |
| MacroSilicon                  | 2        | 5.41%   |
| Apple                         | 2        | 5.41%   |
| Z-Star Microelectronics       | 1        | 2.7%    |
| WCM_USB                       | 1        | 2.7%    |
| Suyin                         | 1        | 2.7%    |
| Silicon Motion                | 1        | 2.7%    |
| Realtek Semiconductor         | 1        | 2.7%    |
| Owon                          | 1        | 2.7%    |
| Huawei Technologies           | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microsoft MicrosoftÂ LifeCam Cinema | 3        | 7.89%   |
| Microdia Camera                      | 3        | 7.89%   |
| MacroSilicon MiraBox Capture         | 2        | 5.26%   |
| Logitech Webcam C310                 | 2        | 5.26%   |
| Logitech Webcam C270                 | 2        | 5.26%   |
| Generalplus CAMERA - UVC             | 2        | 5.26%   |
| Aveo USB2.0 Camera                   | 2        | 5.26%   |
| Z-Star Venus USB2.0 Camera           | 1        | 2.63%   |
| WCM_USB WEB CAM                      | 1        | 2.63%   |
| Suyin HP Integrated Webcam           | 1        | 2.63%   |
| Sunplus SPCA2281 Web Camera          | 1        | 2.63%   |
| Sunplus Full HD webcam               | 1        | 2.63%   |
| Sunplus ABTWPDQ-0222-W               | 1        | 2.63%   |
| Silicon Motion 300k Pixel Camera     | 1        | 2.63%   |
| Realtek USB Camera                   | 1        | 2.63%   |
| Owon USB CAMERA                      | 1        | 2.63%   |
| Microdia Sonix USB 2.0 Camera        | 1        | 2.63%   |
| Microdia Integrated Camera           | 1        | 2.63%   |
| Logitech Webcam C600                 | 1        | 2.63%   |
| Logitech Mic (Notebooks Pro)         | 1        | 2.63%   |
| Logitech HD Webcam C525              | 1        | 2.63%   |
| Logitech HD Webcam C510              | 1        | 2.63%   |
| Logitech C922 Pro Stream Webcam      | 1        | 2.63%   |
| Huawei HiCamera                      | 1        | 2.63%   |
| Generalplus WEB CAM                  | 1        | 2.63%   |
| Generalplus GENERAL WEBCAM           | 1        | 2.63%   |
| Aveo UVC camera (Bresser microscope) | 1        | 2.63%   |
| Apple iSight in LED Cinema Display   | 1        | 2.63%   |
| Apple iPad 2 (3G; 64GB)              | 1        | 2.63%   |

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
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 191      | 83.77%  |
| 1     | 33       | 14.47%  |
| 2     | 2        | 0.88%   |
| 7     | 1        | 0.44%   |
| 5     | 1        | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 29.55%  |
| Graphics card            | 11       | 25%     |
| Sound                    | 6        | 13.64%  |
| Unassigned class         | 5        | 11.36%  |
| Communication controller | 4        | 9.09%   |
| Net/ethernet             | 2        | 4.55%   |
| Storage/raid             | 1        | 2.27%   |
| Network                  | 1        | 2.27%   |
| Chipcard                 | 1        | 2.27%   |

