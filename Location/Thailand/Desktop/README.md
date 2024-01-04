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

Total: 352

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 31       | 13.14%  |
| Ubuntu 18.04                 | 23       | 9.75%   |
| Ubuntu 22.04                 | 17       | 7.2%    |
| OpenMandriva 4.3             | 9        | 3.81%   |
| Fedora 38                    | 8        | 3.39%   |
| OpenMandriva 4.2             | 7        | 2.97%   |
| Manjaro                      | 7        | 2.97%   |
| Arch Rolling                 | 7        | 2.97%   |
| OpenMandriva 23.08           | 5        | 2.12%   |
| OpenMandriva 23.01           | 4        | 1.69%   |
| Fedora 37                    | 4        | 1.69%   |
| ArcoLinux Rolling            | 4        | 1.69%   |
| Zorin 16                     | 3        | 1.27%   |
| Xubuntu 20.04                | 3        | 1.27%   |
| Ubuntu 22.10                 | 3        | 1.27%   |
| Pop!_OS 22.04                | 3        | 1.27%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.27%   |
| KDE neon 20.04               | 3        | 1.27%   |
| Fedora 39                    | 3        | 1.27%   |
| Debian 11                    | 3        | 1.27%   |
| Zorin 15                     | 2        | 0.85%   |
| Xubuntu 18.04                | 2        | 0.85%   |
| Ubuntu 21.10                 | 2        | 0.85%   |
| Ubuntu 21.04                 | 2        | 0.85%   |
| Ubuntu 19.10                 | 2        | 0.85%   |
| Reborn OS                    | 2        | 0.85%   |
| OpenMandriva 5.0             | 2        | 0.85%   |
| OpenMandriva 23.03           | 2        | 0.85%   |
| Linux Mint 21.2              | 2        | 0.85%   |
| Linux Mint 21                | 2        | 0.85%   |
| Linux Mint 20.3              | 2        | 0.85%   |
| Linux Mint 20                | 2        | 0.85%   |
| Linux Mint 19.3              | 2        | 0.85%   |
| Kubuntu 22.04                | 2        | 0.85%   |
| Fedora 36                    | 2        | 0.85%   |
| Endless 3.9.5                | 2        | 0.85%   |
| Endless 3.7.6                | 2        | 0.85%   |
| Debian 12                    | 2        | 0.85%   |
| Arch                         | 2        | 0.85%   |
| Xubuntu 21.10                | 1        | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 81       | 36.32%  |
| OpenMandriva  | 30       | 13.45%  |
| Fedora        | 18       | 8.07%   |
| Linux Mint    | 13       | 5.83%   |
| Arch          | 9        | 4.04%   |
| Pop!_OS       | 7        | 3.14%   |
| Manjaro       | 7        | 3.14%   |
| Debian        | 7        | 3.14%   |
| Xubuntu       | 6        | 2.69%   |
| Endless       | 6        | 2.69%   |
| Zorin         | 5        | 2.24%   |
| openSUSE      | 4        | 1.79%   |
| KDE neon      | 4        | 1.79%   |
| ArcoLinux     | 4        | 1.79%   |
| Reborn OS     | 2        | 0.9%    |
| Kubuntu       | 2        | 0.9%    |
| Kali          | 2        | 0.9%    |
| Elementary    | 2        | 0.9%    |
| Clear Linux   | 2        | 0.9%    |
| CentOS        | 2        | 0.9%    |
| Xero          | 1        | 0.45%   |
| UbuntuDDE     | 1        | 0.45%   |
| Ubuntu MATE   | 1        | 0.45%   |
| Ubuntu Budgie | 1        | 0.45%   |
| SteamOS       | 1        | 0.45%   |
| Solus         | 1        | 0.45%   |
| Nobara        | 1        | 0.45%   |
| GNOME OS      | 1        | 0.45%   |
| BlackPanther  | 1        | 0.45%   |
| Archcraft     | 1        | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 7        | 2.69%   |
| 5.10.14-desktop-1omv4002 | 7        | 2.69%   |
| 6.4.11-desktop-1omv2390  | 5        | 1.92%   |
| 6.1.1-desktop-1omv2290   | 4        | 1.54%   |
| 5.4.0-48-generic         | 4        | 1.54%   |
| 5.15.0-56-generic        | 4        | 1.54%   |
| 5.15.0-46-generic        | 4        | 1.54%   |
| 6.2.0-32-generic         | 3        | 1.15%   |
| 5.8.0-14-generic         | 3        | 1.15%   |
| 5.4.0-42-generic         | 3        | 1.15%   |
| 5.15.0-43-generic        | 3        | 1.15%   |
| 6.6.2-desktop-1omv2390   | 2        | 0.77%   |
| 6.4.15-200.fc38.x86_64   | 2        | 0.77%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.77%   |
| 6.2.15-300.fc38.x86_64   | 2        | 0.77%   |
| 6.2.0-37-generic         | 2        | 0.77%   |
| 6.2.0-26-generic         | 2        | 0.77%   |
| 6.1.0-kali5-amd64        | 2        | 0.77%   |
| 6.1.0-12-amd64           | 2        | 0.77%   |
| 5.8.0-63-generic         | 2        | 0.77%   |
| 5.4.0-77-generic         | 2        | 0.77%   |
| 5.4.0-66-generic         | 2        | 0.77%   |
| 5.4.0-65-generic         | 2        | 0.77%   |
| 5.4.0-59-generic         | 2        | 0.77%   |
| 5.4.0-45-generic         | 2        | 0.77%   |
| 5.4.0-37-generic         | 2        | 0.77%   |
| 5.4.0-144-generic        | 2        | 0.77%   |
| 5.3.0-23-generic         | 2        | 0.77%   |
| 5.19.0-76051900-generic  | 2        | 0.77%   |
| 5.19.0-35-generic        | 2        | 0.77%   |
| 5.17.5-76051705-generic  | 2        | 0.77%   |
| 5.17.3-arch1-1           | 2        | 0.77%   |
| 5.16.13-desktop-1omv4003 | 2        | 0.77%   |
| 5.15.0-71-generic        | 2        | 0.77%   |
| 5.13.0-51-generic        | 2        | 0.77%   |
| 5.13.0-22-generic        | 2        | 0.77%   |
| 5.11.0-41-generic        | 2        | 0.77%   |
| 5.11.0-37-generic        | 2        | 0.77%   |
| 5.0.0-37-generic         | 2        | 0.77%   |
| 5.0.0-23-generic         | 2        | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 35       | 13.78%  |
| 5.15.0  | 21       | 8.27%   |
| 5.8.0   | 12       | 4.72%   |
| 5.13.0  | 12       | 4.72%   |
| 4.15.0  | 11       | 4.33%   |
| 6.2.0   | 9        | 3.54%   |
| 5.3.0   | 8        | 3.15%   |
| 5.19.0  | 7        | 2.76%   |
| 5.16.7  | 7        | 2.76%   |
| 5.11.0  | 7        | 2.76%   |
| 5.10.14 | 7        | 2.76%   |
| 5.0.0   | 7        | 2.76%   |
| 6.4.11  | 6        | 2.36%   |
| 4.18.0  | 5        | 1.97%   |
| 6.1.1   | 4        | 1.57%   |
| 6.1.0   | 4        | 1.57%   |
| 6.5.0   | 3        | 1.18%   |
| 6.2.6   | 3        | 1.18%   |
| 5.17.5  | 3        | 1.18%   |
| 5.10.0  | 3        | 1.18%   |
| 6.6.2   | 2        | 0.79%   |
| 6.6.1   | 2        | 0.79%   |
| 6.5.7   | 2        | 0.79%   |
| 6.4.15  | 2        | 0.79%   |
| 6.2.15  | 2        | 0.79%   |
| 6.2.14  | 2        | 0.79%   |
| 6.0.12  | 2        | 0.79%   |
| 5.5.7   | 2        | 0.79%   |
| 5.17.3  | 2        | 0.79%   |
| 5.16.13 | 2        | 0.79%   |
| 6.7.0   | 1        | 0.39%   |
| 6.6.8   | 1        | 0.39%   |
| 6.6.7   | 1        | 0.39%   |
| 6.6.4   | 1        | 0.39%   |
| 6.5.6   | 1        | 0.39%   |
| 6.5.5   | 1        | 0.39%   |
| 6.5.4   | 1        | 0.39%   |
| 6.5.3   | 1        | 0.39%   |
| 6.5.12  | 1        | 0.39%   |
| 6.4.12  | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 14.74%  |
| 5.15    | 24       | 9.56%   |
| 6.2     | 19       | 7.57%   |
| 5.13    | 15       | 5.98%   |
| 5.16    | 14       | 5.58%   |
| 5.8     | 13       | 5.18%   |
| 6.1     | 12       | 4.78%   |
| 5.10    | 11       | 4.38%   |
| 4.15    | 11       | 4.38%   |
| 6.5     | 10       | 3.98%   |
| 6.4     | 9        | 3.59%   |
| 5.3     | 9        | 3.59%   |
| 5.19    | 8        | 3.19%   |
| 5.17    | 8        | 3.19%   |
| 5.0     | 8        | 3.19%   |
| 6.6     | 7        | 2.79%   |
| 5.11    | 7        | 2.79%   |
| 6.3     | 6        | 2.39%   |
| 4.18    | 5        | 1.99%   |
| 6.0     | 3        | 1.2%    |
| 5.6     | 3        | 1.2%    |
| 5.5     | 2        | 0.8%    |
| 5.14    | 2        | 0.8%    |
| 6.7     | 1        | 0.4%    |
| 5.9     | 1        | 0.4%    |
| 5.7     | 1        | 0.4%    |
| 5.18    | 1        | 0.4%    |
| 5.12    | 1        | 0.4%    |
| 5.1     | 1        | 0.4%    |
| 4.4     | 1        | 0.4%    |
| 4.17    | 1        | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 210      | 99.53%  |
| i686   | 1        | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 114      | 51.12%  |
| KDE5             | 39       | 17.49%  |
| Unknown          | 23       | 10.31%  |
| XFCE             | 15       | 6.73%   |
| X-Cinnamon       | 13       | 5.83%   |
| MATE             | 3        | 1.35%   |
| LXQt             | 3        | 1.35%   |
| KDE              | 3        | 1.35%   |
| Cinnamon         | 3        | 1.35%   |
| Pantheon         | 2        | 0.9%    |
| Deepin           | 2        | 0.9%    |
| Budgie           | 2        | 0.9%    |
| lightdm-xsession | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 149      | 68.35%  |
| Wayland | 50       | 22.94%  |
| Unknown | 14       | 6.42%   |
| Tty     | 5        | 2.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 115      | 52.27%  |
| SDDM    | 38       | 17.27%  |
| GDM3    | 29       | 13.18%  |
| GDM     | 22       | 10%     |
| LightDM | 13       | 5.91%   |
| TDM     | 3        | 1.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 151      | 69.91%  |
| Unknown | 16       | 7.41%   |
| th_TH   | 15       | 6.94%   |
| en_GB   | 12       | 5.56%   |
| de_DE   | 9        | 4.17%   |
| C       | 5        | 2.31%   |
| it_IT   | 3        | 1.39%   |
| fi_FI   | 2        | 0.93%   |
| sv_SE   | 1        | 0.46%   |
| fr_FR   | 1        | 0.46%   |
| de_CH   | 1        | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 127      | 57.47%  |
| EFI  | 94       | 42.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 148      | 67.27%  |
| Overlay | 26       | 11.82%  |
| Btrfs   | 23       | 10.45%  |
| Tmpfs   | 14       | 6.36%   |
| Xfs     | 4        | 1.82%   |
| Unknown | 4        | 1.82%   |
| Zfs     | 1        | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 122      | 55.71%  |
| GPT     | 83       | 37.9%   |
| MBR     | 14       | 6.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 79.17%  |
| Yes       | 45       | 20.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 63.72%  |
| Yes       | 78       | 36.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 44       | 20.85%  |
| ASUSTek Computer    | 40       | 18.96%  |
| ASRock              | 32       | 15.17%  |
| Dell                | 23       | 10.9%   |
| MSI                 | 16       | 7.58%   |
| Hewlett-Packard     | 13       | 6.16%   |
| Acer                | 12       | 5.69%   |
| Intel               | 4        | 1.9%    |
| Lenovo              | 3        | 1.42%   |
| Unknown             | 3        | 1.42%   |
| MiTAC               | 2        | 0.95%   |
| Huanan              | 2        | 0.95%   |
| Biostar             | 2        | 0.95%   |
| Apple               | 2        | 0.95%   |
| ViewSonic           | 1        | 0.47%   |
| VIA Technologies    | 1        | 0.47%   |
| Supermicro          | 1        | 0.47%   |
| SHARKBAY            | 1        | 0.47%   |
| Pegatron            | 1        | 0.47%   |
| Packard Bell        | 1        | 0.47%   |
| OEM                 | 1        | 0.47%   |
| Google              | 1        | 0.47%   |
| Fujitsu             | 1        | 0.47%   |
| ECS                 | 1        | 0.47%   |
| BESSTAR Tech        | 1        | 0.47%   |
| AMI                 | 1        | 0.47%   |
| AFOX                | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 7        | 3.32%   |
| Dell OptiPlex 7010         | 4        | 1.9%    |
| Unknown                    | 4        | 1.9%    |
| Dell Inspiron 3847         | 3        | 1.42%   |
| ASUS P8H61-M LE            | 3        | 1.42%   |
| ASRock B450 Steel Legend   | 3        | 1.42%   |
| HP Z240 Tower Workstation  | 2        | 0.95%   |
| HP EliteDesk 800 G1 SFF PC | 2        | 0.95%   |
| Gigabyte Z97X-UD3H-BK      | 2        | 0.95%   |
| Gigabyte H110M-DS2         | 2        | 0.95%   |
| Gigabyte F2A88XM-HD3P      | 2        | 0.95%   |
| Gigabyte F2A68HM-DS2       | 2        | 0.95%   |
| Gigabyte B250-HD3          | 2        | 0.95%   |
| Dell OptiPlex 9020         | 2        | 0.95%   |
| Dell OptiPlex 7050         | 2        | 0.95%   |
| Dell OptiPlex 3020         | 2        | 0.95%   |
| ASUS TUF Gaming B550M-E    | 2        | 0.95%   |
| ASUS H110M-E/M.2           | 2        | 0.95%   |
| ASRock B450M Steel Legend  | 2        | 0.95%   |
| Acer Veriton N4640G        | 2        | 0.95%   |
| Acer Aspire TC-885         | 2        | 0.95%   |
| ViewSonic VPC14-WP         | 1        | 0.47%   |
| VIA VX900                  | 1        | 0.47%   |
| Supermicro AT350 F3        | 1        | 0.47%   |
| Pegatron CQ3476L           | 1        | 0.47%   |
| Packard Bell IMEDIA S3720  | 1        | 0.47%   |
| OEM Intel H81              | 1        | 0.47%   |
| MSI Pro 3130 Microtower PC | 1        | 0.47%   |
| MSI Pro 2000/2080          | 1        | 0.47%   |
| MSI p6772l                 | 1        | 0.47%   |
| MSI MS-7C52                | 1        | 0.47%   |
| MSI MS-7C35                | 1        | 0.47%   |
| MSI MS-7C02                | 1        | 0.47%   |
| MSI MS-7B89                | 1        | 0.47%   |
| MSI MS-7B85                | 1        | 0.47%   |
| MSI MS-7A63                | 1        | 0.47%   |
| MSI MS-7A38                | 1        | 0.47%   |
| MSI MS-7A32                | 1        | 0.47%   |
| MSI MS-7A15                | 1        | 0.47%   |
| MSI MS-7978                | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 15       | 7.11%   |
| ASUS PRIME             | 7        | 3.32%   |
| ASUS All               | 7        | 3.32%   |
| Acer Veriton           | 6        | 2.84%   |
| Acer Aspire            | 6        | 2.84%   |
| ASRock B450            | 5        | 2.37%   |
| Dell Precision         | 4        | 1.9%    |
| ASUS ROG               | 4        | 1.9%    |
| ASRock B450M           | 4        | 1.9%    |
| Unknown                | 4        | 1.9%    |
| HP ProDesk             | 3        | 1.42%   |
| HP Compaq              | 3        | 1.42%   |
| Dell Inspiron          | 3        | 1.42%   |
| ASUS P8H61-M           | 3        | 1.42%   |
| ASUS M5A78L-M          | 3        | 1.42%   |
| MSI Pro                | 2        | 0.95%   |
| Huanan X79             | 2        | 0.95%   |
| HP Z240                | 2        | 0.95%   |
| HP EliteDesk           | 2        | 0.95%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 0.95%   |
| Gigabyte Z390          | 2        | 0.95%   |
| Gigabyte H310M         | 2        | 0.95%   |
| Gigabyte H110M-DS2     | 2        | 0.95%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.95%   |
| Gigabyte F2A88XM-HD3P  | 2        | 0.95%   |
| Gigabyte F2A68HM-DS2   | 2        | 0.95%   |
| Gigabyte B550M         | 2        | 0.95%   |
| Gigabyte B450M         | 2        | 0.95%   |
| Gigabyte B250-HD3      | 2        | 0.95%   |
| ASUS TUF               | 2        | 0.95%   |
| ASUS H110M-E           | 2        | 0.95%   |
| ASRock Z77             | 2        | 0.95%   |
| ASRock B550M           | 2        | 0.95%   |
| ViewSonic VPC14-WP     | 1        | 0.47%   |
| VIA VX900              | 1        | 0.47%   |
| Supermicro AT350       | 1        | 0.47%   |
| Pegatron CQ3476L       | 1        | 0.47%   |
| Packard Bell IMEDIA    | 1        | 0.47%   |
| OEM Intel              | 1        | 0.47%   |
| MSI p6772l             | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 28       | 13.27%  |
| 2013 | 23       | 10.9%   |
| 2020 | 21       | 9.95%   |
| 2014 | 17       | 8.06%   |
| 2019 | 16       | 7.58%   |
| 2016 | 16       | 7.58%   |
| 2017 | 15       | 7.11%   |
| 2012 | 15       | 7.11%   |
| 2011 | 12       | 5.69%   |
| 2009 | 10       | 4.74%   |
| 2021 | 9        | 4.27%   |
| 2015 | 7        | 3.32%   |
| 2010 | 7        | 3.32%   |
| 2008 | 7        | 3.32%   |
| 2023 | 3        | 1.42%   |
| 2006 | 2        | 0.95%   |
| 2022 | 1        | 0.47%   |
| 2007 | 1        | 0.47%   |
| 2005 | 1        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 211      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 206      | 96.71%  |
| Enabled  | 7        | 3.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 210      | 99.53%  |
| Yes  | 1        | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 51       | 23.08%  |
| 8.01-16.0       | 47       | 21.27%  |
| 4.01-8.0        | 45       | 20.36%  |
| 3.01-4.0        | 35       | 15.84%  |
| 32.01-64.0      | 25       | 11.31%  |
| 1.01-2.0        | 8        | 3.62%   |
| 64.01-256.0     | 5        | 2.26%   |
| 24.01-32.0      | 3        | 1.36%   |
| More than 256.0 | 1        | 0.45%   |
| 0.51-1.0        | 1        | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 93       | 38.11%  |
| 2.01-3.0   | 74       | 30.33%  |
| 3.01-4.0   | 30       | 12.3%   |
| 4.01-8.0   | 23       | 9.43%   |
| 0.51-1.0   | 11       | 4.51%   |
| 8.01-16.0  | 8        | 3.28%   |
| 16.01-24.0 | 3        | 1.23%   |
| 24.01-32.0 | 1        | 0.41%   |
| 0.01-0.5   | 1        | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 91       | 40.09%  |
| 2      | 63       | 27.75%  |
| 3      | 37       | 16.3%   |
| 4      | 15       | 6.61%   |
| 5      | 9        | 3.96%   |
| 0      | 5        | 2.2%    |
| 6      | 3        | 1.32%   |
| 51     | 1        | 0.44%   |
| 32     | 1        | 0.44%   |
| 10     | 1        | 0.44%   |
| 7      | 1        | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 64.02%  |
| Yes       | 77       | 35.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 206      | 97.63%  |
| No        | 5        | 2.37%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 51.15%  |
| No        | 106      | 48.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 146      | 66.67%  |
| Yes       | 73       | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 211      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bangkok                  | 77       | 34.53%  |
| Chiang Mai               | 19       | 8.52%   |
| Khon Kaen                | 10       | 4.48%   |
| Nakhon Ratchasima        | 7        | 3.14%   |
| Nakhon Pathom            | 7        | 3.14%   |
| Phuket                   | 6        | 2.69%   |
| Chon Buri                | 6        | 2.69%   |
| Bang Lamung              | 6        | 2.69%   |
| Songkhla                 | 4        | 1.79%   |
| Mueang Samut Prakan      | 4        | 1.79%   |
| Ban Nong Sala            | 4        | 1.79%   |
| Surin                    | 3        | 1.35%   |
| Pattaya                  | 3        | 1.35%   |
| Si Racha                 | 2        | 0.9%    |
| Phitsanulok              | 2        | 0.9%    |
| Pathum Thani             | 2        | 0.9%    |
| Pak Kret                 | 2        | 0.9%    |
| Nonthaburi               | 2        | 0.9%    |
| Lat Krabang              | 2        | 0.9%    |
| Lampang                  | 2        | 0.9%    |
| Hua Hin                  | 2        | 0.9%    |
| Bang Khae                | 2        | 0.9%    |
| Ban Phan Don             | 2        | 0.9%    |
| Ban Du                   | 2        | 0.9%    |
| Ban Bang Tanot           | 2        | 0.9%    |
| Yarang                   | 1        | 0.45%   |
| Wihan Daeng              | 1        | 0.45%   |
| Wichian Buri             | 1        | 0.45%   |
| Trat                     | 1        | 0.45%   |
| Thung Song               | 1        | 0.45%   |
| Tha Tako                 | 1        | 0.45%   |
| Surat Thani              | 1        | 0.45%   |
| Suan Luang               | 1        | 0.45%   |
| Sawang Daen Din          | 1        | 0.45%   |
| San Sai                  | 1        | 0.45%   |
| Samut Songkhram          | 1        | 0.45%   |
| Samphanthawong           | 1        | 0.45%   |
| Phrom Khiri              | 1        | 0.45%   |
| Phra Nakhon Si Ayutthaya | 1        | 0.45%   |
| Phetchaburi              | 1        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 88       | 158    | 23.04%  |
| Seagate                     | 65       | 113    | 17.02%  |
| Samsung Electronics         | 37       | 61     | 9.69%   |
| SanDisk                     | 23       | 42     | 6.02%   |
| Kingston                    | 21       | 22     | 5.5%    |
| Toshiba                     | 15       | 59     | 3.93%   |
| HS-SSD-C100                 | 8        | 17     | 2.09%   |
| Hitachi                     | 8        | 8      | 2.09%   |
| Crucial                     | 8        | 8      | 2.09%   |
| Apacer                      | 8        | 10     | 2.09%   |
| China                       | 7        | 10     | 1.83%   |
| Unknown                     | 6        | 11     | 1.57%   |
| Hikvision                   | 6        | 6      | 1.57%   |
| Phison                      | 5        | 10     | 1.31%   |
| Intel                       | 5        | 5      | 1.31%   |
| Silicon Motion              | 4        | 5      | 1.05%   |
| MAXIO Technology (Hangzhou) | 4        | 5      | 1.05%   |
| KingSpec                    | 4        | 6      | 1.05%   |
| USB3.0                      | 3        | 3      | 0.79%   |
| TO Exter                    | 3        | 3      | 0.79%   |
| JMicron Technology          | 3        | 3      | 0.79%   |
| HGST                        | 3        | 11     | 0.79%   |
| GALAX                       | 3        | 3      | 0.79%   |
| Colorful                    | 3        | 4      | 0.79%   |
| A-DATA Technology           | 3        | 3      | 0.79%   |
| Transcend                   | 2        | 2      | 0.52%   |
| SPCC                        | 2        | 2      | 0.52%   |
| SK hynix                    | 2        | 3      | 0.52%   |
| Realtek Semiconductor       | 2        | 2      | 0.52%   |
| Plextor                     | 2        | 2      | 0.52%   |
| Phison Electronics          | 2        | 2      | 0.52%   |
| Micron Technology           | 2        | 2      | 0.52%   |
| Lexar                       | 2        | 3      | 0.52%   |
| Hewlett-Packard             | 2        | 4      | 0.52%   |
| External                    | 2        | 2      | 0.52%   |
| Corsair                     | 2        | 2      | 0.52%   |
| Acer                        | 2        | 6      | 0.52%   |
| WALRAM                      | 1        | 1      | 0.26%   |
| Verbatim                    | 1        | 1      | 0.26%   |
| SPCC M.2                    | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                    | 10       | 2.26%   |
| Seagate ST1000DM010-2EP102 1TB                     | 9        | 2.03%   |
| Seagate ST1000DM003-1ER162 1TB                     | 6        | 1.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 5        | 1.13%   |
| WDC WD20EZAZ-00GGJB0 2TB                           | 5        | 1.13%   |
| WDC WD10EZEX-00WN4A0 1TB                           | 5        | 1.13%   |
| Seagate ST2000VX008-2E3164 2TB                     | 5        | 1.13%   |
| Samsung HD103SJ 1TB                                | 5        | 1.13%   |
| Kingston SUV400S37120G 120GB SSD                   | 5        | 1.13%   |
| Kingston SA400S37240G 240GB SSD                    | 5        | 1.13%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 4        | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 4        | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 4        | 0.9%    |
| Toshiba DT01ACA100 1TB                             | 4        | 0.9%    |
| SanDisk NVMe SSD Drive 1TB                         | 4        | 0.9%    |
| HS-SSD-C100 240G                                   | 4        | 0.9%    |
| Crucial CT500MX500SSD1 500GB                       | 4        | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB                       | 3        | 0.68%   |
| WDC WD5000AAKX-001CA0 500GB                        | 3        | 0.68%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 3        | 0.68%   |
| WDC WD10EZEX-00MFCA0 1TB                           | 3        | 0.68%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 3        | 0.68%   |
| USB3.0 Super Speed 1TB                             | 3        | 0.68%   |
| Unknown SD/MMC/MS PRO 512GB                        | 3        | 0.68%   |
| TO Exter nal USB 3.0 480GB                         | 3        | 0.68%   |
| Seagate ST3500418AS 500GB                          | 3        | 0.68%   |
| SanDisk SDSSDA120G 120GB                           | 3        | 0.68%   |
| SanDisk NVMe SSD Drive 250GB                       | 3        | 0.68%   |
| Samsung SSD 850 120GB                              | 3        | 0.68%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 3        | 0.68%   |
| Samsung HD502IJ 500GB                              | 3        | 0.68%   |
| Phison NVMe SSD Drive 240GB                        | 3        | 0.68%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 3        | 0.68%   |
| Kingston SV300S37A120G 120GB SSD                   | 3        | 0.68%   |
| Intel SSDSC2CT060A3 64GB                           | 3        | 0.68%   |
| HS-SSD-C100 120G                                   | 3        | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 2        | 0.45%   |
| WDC WDS250G3X0C-00SJG0 250GB                       | 2        | 0.45%   |
| WDC WD5000AADS-00S9B0 500GB                        | 2        | 0.45%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 70       | 117    | 37.63%  |
| Seagate             | 64       | 109    | 34.41%  |
| Toshiba             | 14       | 58     | 7.53%   |
| Samsung Electronics | 12       | 18     | 6.45%   |
| Hitachi             | 8        | 8      | 4.3%    |
| Unknown             | 4        | 9      | 2.15%   |
| USB3.0              | 3        | 3      | 1.61%   |
| TO Exter            | 3        | 3      | 1.61%   |
| HGST                | 3        | 11     | 1.61%   |
| External            | 2        | 2      | 1.08%   |
| JMicron Technology  | 1        | 1      | 0.54%   |
| Hewlett-Packard     | 1        | 3      | 0.54%   |
| Fujitsu             | 1        | 2      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 32     | 16.42%  |
| Samsung Electronics | 18       | 27     | 13.43%  |
| Kingston            | 15       | 16     | 11.19%  |
| SanDisk             | 9        | 17     | 6.72%   |
| Crucial             | 8        | 8      | 5.97%   |
| Apacer              | 8        | 10     | 5.97%   |
| China               | 7        | 10     | 5.22%   |
| Intel               | 5        | 5      | 3.73%   |
| Hikvision           | 5        | 5      | 3.73%   |
| KingSpec            | 4        | 6      | 2.99%   |
| GALAX               | 3        | 3      | 2.24%   |
| A-DATA Technology   | 3        | 3      | 2.24%   |
| SPCC                | 2        | 2      | 1.49%   |
| Plextor             | 2        | 2      | 1.49%   |
| Micron Technology   | 2        | 2      | 1.49%   |
| Lexar               | 2        | 3      | 1.49%   |
| Colorful            | 2        | 3      | 1.49%   |
| Acer                | 2        | 6      | 1.49%   |
| WALRAM              | 1        | 1      | 0.75%   |
| Verbatim            | 1        | 1      | 0.75%   |
| Transcend           | 1        | 1      | 0.75%   |
| SPCC M.2            | 1        | 1      | 0.75%   |
| SK hynix            | 1        | 2      | 0.75%   |
| Pioneer             | 1        | 1      | 0.75%   |
| OCZ                 | 1        | 1      | 0.75%   |
| JMicron Technology  | 1        | 1      | 0.75%   |
| Intenso             | 1        | 12     | 0.75%   |
| HS-SSD-E100         | 1        | 1      | 0.75%   |
| Hewlett-Packard     | 1        | 1      | 0.75%   |
| DGM                 | 1        | 1      | 0.75%   |
| Corsair             | 1        | 1      | 0.75%   |
| ASMedia             | 1        | 1      | 0.75%   |
| addlink             | 1        | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 142      | 344    | 44.79%  |
| SSD     | 106      | 187    | 33.44%  |
| NVMe    | 55       | 88     | 17.35%  |
| Unknown | 14       | 26     | 4.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 195      | 519    | 70.65%  |
| NVMe | 55       | 88     | 19.93%  |
| SAS  | 26       | 38     | 9.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 138      | 245    | 49.46%  |
| 0.51-1.0   | 79       | 132    | 28.32%  |
| 1.01-2.0   | 39       | 56     | 13.98%  |
| 3.01-4.0   | 13       | 61     | 4.66%   |
| 2.01-3.0   | 4        | 10     | 1.43%   |
| 10.01-20.0 | 3        | 12     | 1.08%   |
| 4.01-10.0  | 3        | 15     | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 62       | 27.31%  |
| 251-500        | 35       | 15.42%  |
| 501-1000       | 34       | 14.98%  |
| 1-20           | 28       | 12.33%  |
| 1001-2000      | 17       | 7.49%   |
| 2001-3000      | 15       | 6.61%   |
| More than 3000 | 14       | 6.17%   |
| 51-100         | 10       | 4.41%   |
| 21-50          | 7        | 3.08%   |
| Unknown        | 5        | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 93       | 39.08%  |
| 21-50          | 36       | 15.13%  |
| 101-250        | 29       | 12.18%  |
| 51-100         | 24       | 10.08%  |
| 501-1000       | 17       | 7.14%   |
| 251-500        | 14       | 5.88%   |
| More than 3000 | 9        | 3.78%   |
| 1001-2000      | 8        | 3.36%   |
| Unknown        | 5        | 2.1%    |
| 2001-3000      | 3        | 1.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 2        | 2      | 7.69%   |
| Seagate ST500DM002-1BD14 500GB           | 2        | 3      | 7.69%   |
| Samsung Electronics SSD 830 Series 128GB | 2        | 2      | 7.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1        | 1      | 3.85%   |
| WDC WD6402AAEX-00Y9A0 640GB              | 1        | 1      | 3.85%   |
| WDC WD20EZRX-00DC0B0 2TB                 | 1        | 1      | 3.85%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 3.85%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1        | 1      | 3.85%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 1        | 1      | 3.85%   |
| WDC WD1002FAEX-00Y9A0 1TB                | 1        | 1      | 3.85%   |
| USB3.0 Super Speed 1TB                   | 1        | 1      | 3.85%   |
| Toshiba HDWL110 1TB                      | 1        | 1      | 3.85%   |
| Seagate ST9120822AS 120GB                | 1        | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 3.85%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 3.85%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 3.85%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1        | 1      | 3.85%   |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 3.85%   |
| Samsung Electronics HD253GJ 250GB        | 1        | 1      | 3.85%   |
| Samsung Electronics HD103SJ 1TB          | 1        | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 3.85%   |
| Hitachi HTS541612J9SA00 120GB            | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 32%     |
| Seagate             | 8        | 10     | 32%     |
| Samsung Electronics | 5        | 6      | 20%     |
| USB3.0              | 1        | 1      | 4%      |
| Toshiba             | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 38.1%   |
| WDC                 | 7        | 8      | 33.33%  |
| Samsung Electronics | 3        | 4      | 14.29%  |
| USB3.0              | 1        | 1      | 4.76%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |

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
| Detected | 151      | 384    | 61.89%  |
| Works    | 69       | 230    | 28.28%  |
| Malfunc  | 22       | 29     | 9.02%   |
| Failed   | 2        | 2      | 0.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 137      | 47.74%  |
| AMD                          | 64       | 22.3%   |
| SanDisk                      | 20       | 6.97%   |
| ASMedia Technology           | 12       | 4.18%   |
| Samsung Electronics          | 9        | 3.14%   |
| Phison Electronics           | 8        | 2.79%   |
| Nvidia                       | 7        | 2.44%   |
| Kingston Technology Company  | 7        | 2.44%   |
| MAXIO Technology (Hangzhou)  | 6        | 2.09%   |
| Silicon Motion               | 4        | 1.39%   |
| VIA Technologies             | 2        | 0.7%    |
| Realtek Semiconductor        | 2        | 0.7%    |
| Marvell Technology Group     | 2        | 0.7%    |
| Broadcom / LSI               | 2        | 0.7%    |
| Toshiba America Info Systems | 1        | 0.35%   |
| SK hynix                     | 1        | 0.35%   |
| Micron/Crucial Technology    | 1        | 0.35%   |
| LSI Logic / Symbios Logic    | 1        | 0.35%   |
| JMicron Technology           | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35       | 10%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 6%      |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 5.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 4.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 3.43%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 3.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 2.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.57%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 2%      |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 5        | 1.43%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 5        | 1.43%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.43%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 5        | 1.43%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 1.14%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.14%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 3        | 0.86%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3        | 0.86%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.86%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 0.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.86%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.86%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 0.57%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.57%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 175      | 60.55%  |
| NVMe | 56       | 19.38%  |
| IDE  | 43       | 14.88%  |
| RAID | 13       | 4.5%    |
| SAS  | 1        | 0.35%   |
| SCSI | 1        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 141      | 66.82%  |
| AMD          | 69       | 32.7%   |
| CentaurHauls | 1        | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz          | 6        | 2.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz          | 6        | 2.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz          | 4        | 1.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz          | 4        | 1.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz          | 4        | 1.88%   |
| AMD Ryzen 5 3600 6-Core Processor         | 4        | 1.88%   |
| AMD Ryzen 5 2600 Six-Core Processor       | 4        | 1.88%   |
| Intel Core i9-9900K CPU @ 3.60GHz         | 3        | 1.41%   |
| Intel Core i7-4770K CPU @ 3.50GHz         | 3        | 1.41%   |
| Intel Core i7-4770 CPU @ 3.40GHz          | 3        | 1.41%   |
| Intel Core i3-4160 CPU @ 3.60GHz          | 3        | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz          | 3        | 1.41%   |
| AMD Ryzen 7 2700X Eight-Core Processor    | 3        | 1.41%   |
| AMD Ryzen 5 5600X 6-Core Processor        | 3        | 1.41%   |
| AMD Ryzen 5 5600G with Radeon Graphics    | 3        | 1.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz          | 2        | 0.94%   |
| Intel Core i5-6400T CPU @ 2.20GHz         | 2        | 0.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz          | 2        | 0.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz          | 2        | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz          | 2        | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 2        | 0.94%   |
| Intel Core i5-2500K CPU @ 3.30GHz         | 2        | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz          | 2        | 0.94%   |
| Intel Core i5 CPU 750 @ 2.67GHz           | 2        | 0.94%   |
| Intel Core i3-7100 CPU @ 3.90GHz          | 2        | 0.94%   |
| Intel Core i3-6100 CPU @ 3.70GHz          | 2        | 0.94%   |
| Intel Core i3-4150 CPU @ 3.50GHz          | 2        | 0.94%   |
| Intel Core i3-4130 CPU @ 3.40GHz          | 2        | 0.94%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz      | 2        | 0.94%   |
| AMD Ryzen 9 5900X 12-Core Processor       | 2        | 0.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor     | 2        | 0.94%   |
| AMD Ryzen 5 3600X 6-Core Processor        | 2        | 0.94%   |
| AMD Ryzen 3 4300GE with Radeon Graphics   | 2        | 0.94%   |
| AMD Phenom II X6 1055T Processor          | 2        | 0.94%   |
| AMD Athlon II X2 270 Processor            | 2        | 0.94%   |
| AMD A6-5400K APU with Radeon HD Graphics  | 2        | 0.94%   |
| AMD A10-5800K APU with Radeon HD Graphics | 2        | 0.94%   |
| Intel Xeon W-2145 CPU @ 3.70GHz           | 1        | 0.47%   |
| Intel Xeon CPU X5670 @ 2.93GHz            | 1        | 0.47%   |
| Intel Xeon CPU E5645 @ 2.40GHz            | 1        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 45       | 21.23%  |
| Intel Core i3           | 33       | 15.57%  |
| Intel Core i7           | 25       | 11.79%  |
| AMD Ryzen 5             | 22       | 10.38%  |
| Intel Xeon              | 13       | 6.13%   |
| AMD Ryzen 7             | 8        | 3.77%   |
| AMD Ryzen 3             | 6        | 2.83%   |
| Intel Pentium           | 5        | 2.36%   |
| AMD FX                  | 5        | 2.36%   |
| AMD Athlon II X2        | 5        | 2.36%   |
| Intel Core 2 Quad       | 4        | 1.89%   |
| AMD Ryzen 9             | 4        | 1.89%   |
| AMD Athlon 64 X2        | 4        | 1.89%   |
| AMD A10                 | 4        | 1.89%   |
| Intel Pentium Dual-Core | 3        | 1.42%   |
| Intel Core i9           | 3        | 1.42%   |
| Intel Celeron           | 3        | 1.42%   |
| AMD A6                  | 3        | 1.42%   |
| Intel Core 2 Duo        | 2        | 0.94%   |
| AMD Phenom II X6        | 2        | 0.94%   |
| AMD Phenom II X4        | 2        | 0.94%   |
| AMD A4                  | 2        | 0.94%   |
| Other                   | 1        | 0.47%   |
| Intel Pentium Dual      | 1        | 0.47%   |
| Intel Pentium D         | 1        | 0.47%   |
| Intel Pentium 4         | 1        | 0.47%   |
| Intel Atom              | 1        | 0.47%   |
| CentaurHauls VIA Eden   | 1        | 0.47%   |
| AMD Ryzen 3 PRO         | 1        | 0.47%   |
| AMD Phenom II X3        | 1        | 0.47%   |
| AMD Athlon              | 1        | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 84       | 39.62%  |
| 2      | 62       | 29.25%  |
| 6      | 33       | 15.57%  |
| 8      | 18       | 8.49%   |
| 12     | 6        | 2.83%   |
| 1      | 4        | 1.89%   |
| 3      | 2        | 0.94%   |
| 40     | 1        | 0.47%   |
| 24     | 1        | 0.47%   |
| 10     | 1        | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 206      | 97.63%  |
| 2      | 5        | 2.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 127      | 59.91%  |
| 1      | 85       | 40.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 211      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 33.92%  |
| 0x306c3    | 19       | 8.37%   |
| 0x206a7    | 11       | 4.85%   |
| 0x506e3    | 10       | 4.41%   |
| 0x906ea    | 7        | 3.08%   |
| 0x906e9    | 7        | 3.08%   |
| 0x306a9    | 7        | 3.08%   |
| 0x1067a    | 6        | 2.64%   |
| 0x0800820d | 6        | 2.64%   |
| 0x06001119 | 5        | 2.2%    |
| 0x010000c8 | 4        | 1.76%   |
| 0xa0655    | 3        | 1.32%   |
| 0x906ec    | 3        | 1.32%   |
| 0x406f1    | 3        | 1.32%   |
| 0x20655    | 3        | 1.32%   |
| 0x08701021 | 3        | 1.32%   |
| 0x08001138 | 3        | 1.32%   |
| 0x906eb    | 2        | 0.88%   |
| 0x40651    | 2        | 0.88%   |
| 0x106e5    | 2        | 0.88%   |
| 0x0a50000c | 2        | 0.88%   |
| 0x0a201009 | 2        | 0.88%   |
| 0x08600106 | 2        | 0.88%   |
| 0x08108109 | 2        | 0.88%   |
| 0x06003106 | 2        | 0.88%   |
| 0x06000852 | 2        | 0.88%   |
| 0xf65      | 1        | 0.44%   |
| 0xf49      | 1        | 0.44%   |
| 0xa0653    | 1        | 0.44%   |
| 0x906ed    | 1        | 0.44%   |
| 0x6fd      | 1        | 0.44%   |
| 0x6fb      | 1        | 0.44%   |
| 0x50654    | 1        | 0.44%   |
| 0x406c3    | 1        | 0.44%   |
| 0x306e4    | 1        | 0.44%   |
| 0x30678    | 1        | 0.44%   |
| 0x206c2    | 1        | 0.44%   |
| 0x106ca    | 1        | 0.44%   |
| 0x10677    | 1        | 0.44%   |
| 0x10676    | 1        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 32       | 15.09%  |
| KabyLake    | 24       | 11.32%  |
| Skylake     | 19       | 8.96%   |
| Zen 2       | 15       | 7.08%   |
| SandyBridge | 15       | 7.08%   |
| IvyBridge   | 14       | 6.6%    |
| Zen+        | 12       | 5.66%   |
| Zen 3       | 9        | 4.25%   |
| Piledriver  | 9        | 4.25%   |
| Penryn      | 9        | 4.25%   |
| K10         | 9        | 4.25%   |
| Westmere    | 6        | 2.83%   |
| CometLake   | 6        | 2.83%   |
| Zen         | 5        | 2.36%   |
| Silvermont  | 4        | 1.89%   |
| K8 Hammer   | 4        | 1.89%   |
| Unknown     | 4        | 1.89%   |
| Broadwell   | 3        | 1.42%   |
| Steamroller | 2        | 0.94%   |
| NetBurst    | 2        | 0.94%   |
| Nehalem     | 2        | 0.94%   |
| Excavator   | 2        | 0.94%   |
| Core        | 2        | 0.94%   |
| K10 Llano   | 1        | 0.47%   |
| IceLake     | 1        | 0.47%   |
| Bonnell     | 1        | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 85       | 36.96%  |
| Intel             | 78       | 33.91%  |
| AMD               | 65       | 28.26%  |
| VIA Technologies  | 1        | 0.43%   |
| ASPEED Technology | 1        | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 13       | 5.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12       | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 3.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8        | 3.33%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 2.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 2.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6        | 2.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 6        | 2.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6        | 2.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5        | 2.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 1.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.67%   |
| Intel HD Graphics 630                                                                    | 3        | 1.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 1.25%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3        | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.25%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 3        | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.25%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.83%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 2        | 0.83%   |
| Nvidia GP107GL [Quadro P620]                                                             | 2        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 0.83%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.83%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2        | 0.83%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 2        | 0.83%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.83%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.83%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 0.83%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 0.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.83%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 74       | 33.33%  |
| 1 x Intel            | 68       | 30.63%  |
| 1 x AMD              | 60       | 27.03%  |
| Intel + Nvidia       | 5        | 2.25%   |
| AMD + Nvidia         | 4        | 1.8%    |
| 2 x AMD              | 3        | 1.35%   |
| 3 x Nvidia           | 1        | 0.45%   |
| 2 x Nvidia           | 1        | 0.45%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.45%   |
| 1 x VIA              | 1        | 0.45%   |
| Intel + 2 x Nvidia   | 1        | 0.45%   |
| Intel + AMD          | 1        | 0.45%   |
| 1 x ASPEED           | 1        | 0.45%   |
| AMD + 2 x Nvidia     | 1        | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 168      | 76.71%  |
| Proprietary | 42       | 19.18%  |
| Unknown     | 9        | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 111      | 49.33%  |
| 1.01-2.0   | 32       | 14.22%  |
| 0.51-1.0   | 20       | 8.89%   |
| 3.01-4.0   | 17       | 7.56%   |
| 0.01-0.5   | 17       | 7.56%   |
| 7.01-8.0   | 16       | 7.11%   |
| 5.01-6.0   | 8        | 3.56%   |
| 4.01-5.0   | 1        | 0.44%   |
| 2.01-3.0   | 1        | 0.44%   |
| 16.01-24.0 | 1        | 0.44%   |
| 8.01-16.0  | 1        | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 42       | 19.18%  |
| Acer                 | 37       | 16.89%  |
| Goldstar             | 33       | 15.07%  |
| Dell                 | 16       | 7.31%   |
| Hewlett-Packard      | 15       | 6.85%   |
| AOC                  | 12       | 5.48%   |
| ViewSonic            | 6        | 2.74%   |
| LG Electronics       | 6        | 2.74%   |
| Lenovo               | 6        | 2.74%   |
| BenQ                 | 6        | 2.74%   |
| Unknown (XXX)        | 3        | 1.37%   |
| Ancor Communications | 3        | 1.37%   |
| Sharp                | 2        | 0.91%   |
| SGT                  | 2        | 0.91%   |
| Philips              | 2        | 0.91%   |
| MStar                | 2        | 0.91%   |
| MSI                  | 2        | 0.91%   |
| Microstep            | 2        | 0.91%   |
| Fujitsu              | 2        | 0.91%   |
| Apple                | 2        | 0.91%   |
| ___                  | 1        | 0.46%   |
| Unknown              | 1        | 0.46%   |
| Toshiba              | 1        | 0.46%   |
| Sony                 | 1        | 0.46%   |
| SKY                  | 1        | 0.46%   |
| RTK                  | 1        | 0.46%   |
| MIG                  | 1        | 0.46%   |
| JRY                  | 1        | 0.46%   |
| ITE                  | 1        | 0.46%   |
| IOD                  | 1        | 0.46%   |
| HUYINIUDA            | 1        | 0.46%   |
| HPN                  | 1        | 0.46%   |
| Gateway              | 1        | 0.46%   |
| Fujitsu Siemens      | 1        | 0.46%   |
| Envision Peripherals | 1        | 0.46%   |
| CHI                  | 1        | 0.46%   |
| ASUSTek Computer     | 1        | 0.46%   |
| Unknown              | 1        | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 4        | 1.72%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3        | 1.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 3        | 1.29%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 3        | 1.29%   |
| AOC 2381 AOC2381 1920x1080 509x286mm 23.0-inch                        | 3        | 1.29%   |
| Acer K222HQL ACR0512 1920x1080 477x268mm 21.5-inch                    | 3        | 1.29%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2        | 0.86%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2        | 0.86%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2        | 0.86%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 0.86%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.86%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 2        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                      | 2        | 0.86%   |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                   | 2        | 0.86%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2        | 0.86%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2        | 0.86%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch            | 2        | 0.86%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.86%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.86%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 2        | 0.86%   |
| Goldstar E1940 GSM4BD7 1360x768 406x229mm 18.4-inch                   | 2        | 0.86%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2        | 0.86%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 2        | 0.86%   |
| Acer X193W ACR000C 1440x900 410x256mm 19.0-inch                       | 2        | 0.86%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                      | 2        | 0.86%   |
| Acer S200HQL ACR0359 1600x900 432x239mm 19.4-inch                     | 2        | 0.86%   |
| Acer K242HQL ACR042E 1920x1080 509x286mm 23.0-inch                    | 2        | 0.86%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.43%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                | 1        | 0.43%   |
| ViewSonic VA1703wSERIES VSC121F 1440x900 367x230mm 17.1-inch          | 1        | 0.43%   |
| ViewSonic LCD Monitor VX3276-QHD 5120x1440                            | 1        | 0.43%   |
| ViewSonic IFP7550 VSC36CD 3840x2160 1660x930mm 74.9-inch              | 1        | 0.43%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 0.43%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1210x680mm 54.6-inch         | 1        | 0.43%   |
| Unknown (XXX) MS82P XXX001A 1360x768 330x210mm 15.4-inch              | 1        | 0.43%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch             | 1        | 0.43%   |
| Toshiba TV TSB0114 1920x1080 882x498mm 39.9-inch                      | 1        | 0.43%   |
| Sony TV SNY9402 1920x1080                                             | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 103      | 48.13%  |
| 1600x900 (HD+)     | 18       | 8.41%   |
| 1366x768 (WXGA)    | 18       | 8.41%   |
| 3840x2160 (4K)     | 13       | 6.07%   |
| 1440x900 (WXGA+)   | 10       | 4.67%   |
| 2560x1440 (QHD)    | 9        | 4.21%   |
| 1680x1050 (WSXGA+) | 8        | 3.74%   |
| 1360x768           | 7        | 3.27%   |
| 2560x1080          | 5        | 2.34%   |
| 1280x1024 (SXGA)   | 5        | 2.34%   |
| Unknown            | 5        | 2.34%   |
| 3840x1080          | 2        | 0.93%   |
| 3440x1440          | 2        | 0.93%   |
| 1920x1200 (WUXGA)  | 2        | 0.93%   |
| 1600x1200          | 2        | 0.93%   |
| 5120x1440          | 1        | 0.47%   |
| 2732x768           | 1        | 0.47%   |
| 2560x1600          | 1        | 0.47%   |
| 1280x960           | 1        | 0.47%   |
| 1280x720 (HD)      | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 35       | 15.91%  |
| 21      | 27       | 12.27%  |
| 24      | 24       | 10.91%  |
| Unknown | 23       | 10.45%  |
| 18      | 20       | 9.09%   |
| 27      | 18       | 8.18%   |
| 20      | 17       | 7.73%   |
| 19      | 13       | 5.91%   |
| 34      | 7        | 3.18%   |
| 22      | 6        | 2.73%   |
| 17      | 4        | 1.82%   |
| 15      | 4        | 1.82%   |
| 72      | 3        | 1.36%   |
| 54      | 3        | 1.36%   |
| 84      | 2        | 0.91%   |
| 52      | 2        | 0.91%   |
| 31      | 2        | 0.91%   |
| 26      | 2        | 0.91%   |
| 74      | 1        | 0.45%   |
| 60      | 1        | 0.45%   |
| 46      | 1        | 0.45%   |
| 40      | 1        | 0.45%   |
| 39      | 1        | 0.45%   |
| 32      | 1        | 0.45%   |
| 29      | 1        | 0.45%   |
| 16      | 1        | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 80       | 37.91%  |
| 501-600     | 72       | 34.12%  |
| Unknown     | 23       | 10.9%   |
| 701-800     | 8        | 3.79%   |
| 301-350     | 8        | 3.79%   |
| 1001-1500   | 7        | 3.32%   |
| 1501-2000   | 5        | 2.37%   |
| 601-700     | 3        | 1.42%   |
| 351-400     | 3        | 1.42%   |
| 801-900     | 2        | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 145      | 71.08%  |
| 16/10   | 25       | 12.25%  |
| Unknown | 19       | 9.31%   |
| 21/9    | 7        | 3.43%   |
| 5/4     | 6        | 2.94%   |
| 4/3     | 1        | 0.49%   |
| 2.00    | 1        | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 79       | 36.24%  |
| 151-200        | 37       | 16.97%  |
| Unknown        | 23       | 10.55%  |
| 141-150        | 20       | 9.17%   |
| 301-350        | 19       | 8.72%   |
| More than 1000 | 11       | 5.05%   |
| 351-500        | 11       | 5.05%   |
| 251-300        | 8        | 3.67%   |
| 101-110        | 4        | 1.83%   |
| 501-1000       | 3        | 1.38%   |
| 131-140        | 2        | 0.92%   |
| 121-130        | 1        | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 121      | 60.8%   |
| 101-120 | 38       | 19.1%   |
| Unknown | 23       | 11.56%  |
| 1-50    | 9        | 4.52%   |
| 161-240 | 4        | 2.01%   |
| 121-160 | 4        | 2.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 175      | 78.48%  |
| 2     | 28       | 12.56%  |
| 0     | 15       | 6.73%   |
| 3     | 5        | 2.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 146      | 45.63%  |
| Intel                           | 75       | 23.44%  |
| Qualcomm Atheros                | 24       | 7.5%    |
| Ralink Technology               | 13       | 4.06%   |
| Broadcom                        | 10       | 3.13%   |
| TP-Link                         | 9        | 2.81%   |
| D-Link                          | 9        | 2.81%   |
| Nvidia                          | 6        | 1.88%   |
| Edimax Technology               | 3        | 0.94%   |
| D-Link System                   | 3        | 0.94%   |
| Samsung Electronics             | 2        | 0.63%   |
| Ralink                          | 2        | 0.63%   |
| Mercucys                        | 2        | 0.63%   |
| MediaTek                        | 2        | 0.63%   |
| Broadcom Limited                | 2        | 0.63%   |
| ASUSTek Computer                | 2        | 0.63%   |
| Xiaomi                          | 1        | 0.31%   |
| VIA Technologies                | 1        | 0.31%   |
| Qualcomm Atheros Communications | 1        | 0.31%   |
| OPPO Electronics                | 1        | 0.31%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.31%   |
| Huawei Technologies             | 1        | 0.31%   |
| BUFFALO                         | 1        | 0.31%   |
| AVM                             | 1        | 0.31%   |
| Aquantia                        | 1        | 0.31%   |
| Adafruit                        | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 124      | 34.64%  |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 7        | 1.96%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 1.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.4%    |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.4%    |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.4%    |
| Intel Ethernet Connection I217-V                                  | 5        | 1.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 4        | 1.12%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.12%   |
| Intel Wireless 7260                                               | 4        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                             | 4        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 1.12%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]     | 4        | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.84%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.84%   |
| Realtek 802.11ac NIC                                              | 3        | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3        | 0.84%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.56%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2        | 0.56%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.56%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.56%   |
| Mercucys 802.11n NIC                                              | 2        | 0.56%   |
| Intel Wireless-AC 9260                                            | 2        | 0.56%   |
| Intel Wireless 7265                                               | 2        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 29       | 23.2%   |
| Intel                           | 24       | 19.2%   |
| Qualcomm Atheros                | 20       | 16%     |
| Ralink Technology               | 13       | 10.4%   |
| TP-Link                         | 9        | 7.2%    |
| D-Link                          | 9        | 7.2%    |
| Broadcom                        | 5        | 4%      |
| Edimax Technology               | 3        | 2.4%    |
| Ralink                          | 2        | 1.6%    |
| Mercucys                        | 2        | 1.6%    |
| MediaTek                        | 2        | 1.6%    |
| ASUSTek Computer                | 2        | 1.6%    |
| Qualcomm Atheros Communications | 1        | 0.8%    |
| D-Link System                   | 1        | 0.8%    |
| BUFFALO                         | 1        | 0.8%    |
| Broadcom Limited                | 1        | 0.8%    |
| AVM                             | 1        | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7        | 5.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6        | 4.72%   |
| Ralink MT7601U Wireless Adapter                                | 5        | 3.94%   |
| Intel Wi-Fi 6 AX200                                            | 5        | 3.94%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 4        | 3.15%   |
| Intel Wireless 7260                                            | 4        | 3.15%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]  | 4        | 3.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 2.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3        | 2.36%   |
| Realtek 802.11ac NIC                                           | 3        | 2.36%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3        | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 2.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 1.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 1.57%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 1.57%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 2        | 1.57%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2        | 1.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 1.57%   |
| Mercucys 802.11n NIC                                           | 2        | 1.57%   |
| Intel Wireless-AC 9260                                         | 2        | 1.57%   |
| Intel Wireless 7265                                            | 2        | 1.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 1.57%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2        | 1.57%   |
| D-Link 802.11 n WLAN                                           | 2        | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2        | 1.57%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.79%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1        | 0.79%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 1        | 0.79%   |
| TP-Link Archer T4U ver.3                                       | 1        | 0.79%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.79%   |
| TP-Link 802.11n NIC                                            | 1        | 0.79%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 0.79%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 136      | 60.99%  |
| Intel                         | 61       | 27.35%  |
| Nvidia                        | 6        | 2.69%   |
| Qualcomm Atheros              | 5        | 2.24%   |
| Broadcom                      | 5        | 2.24%   |
| Samsung Electronics           | 2        | 0.9%    |
| D-Link System                 | 2        | 0.9%    |
| Xiaomi                        | 1        | 0.45%   |
| VIA Technologies              | 1        | 0.45%   |
| OPPO Electronics              | 1        | 0.45%   |
| OnePlus Technology (Shenzhen) | 1        | 0.45%   |
| Broadcom Limited              | 1        | 0.45%   |
| Aquantia                      | 1        | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 124      | 54.15%  |
| Intel Ethernet Connection I217-LM                                 | 8        | 3.49%   |
| Intel I211 Gigabit Network Connection                             | 7        | 3.06%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 2.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.18%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.18%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 4        | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.87%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.87%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.87%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.87%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.87%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1        | 0.44%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.44%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.44%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 1        | 0.44%   |
| OnePlus (Shenzhen) Android                                        | 1        | 0.44%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.44%   |
| Intel I210 Gigabit Unprogrammed                                   | 1        | 0.44%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.44%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.44%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.44%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 206      | 64.78%  |
| WiFi     | 110      | 34.59%  |
| Modem    | 2        | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 141      | 64.38%  |
| WiFi     | 78       | 35.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 64.19%  |
| 2     | 64       | 29.77%  |
| 3     | 6        | 2.79%   |
| 0     | 4        | 1.86%   |
| 4     | 2        | 0.93%   |
| 5     | 1        | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 148      | 66.97%  |
| Yes  | 73       | 33.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 31       | 39.24%  |
| Intel                           | 21       | 26.58%  |
| Realtek Semiconductor           | 4        | 5.06%   |
| Qualcomm Atheros Communications | 4        | 5.06%   |
| ASUSTek Computer                | 4        | 5.06%   |
| Apple                           | 3        | 3.8%    |
| MediaTek                        | 2        | 2.53%   |
| Lite-On Technology              | 2        | 2.53%   |
| IMC Networks                    | 2        | 2.53%   |
| Actions                         | 2        | 2.53%   |
| TP-Link                         | 1        | 1.27%   |
| Toshiba                         | 1        | 1.27%   |
| Foxconn International           | 1        | 1.27%   |
| Broadcom                        | 1        | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31       | 39.24%  |
| Intel Bluetooth wireless interface                  | 8        | 10.13%  |
| Intel AX200 Bluetooth                               | 5        | 6.33%   |
| Realtek Bluetooth Radio                             | 3        | 3.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 3.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 2.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2        | 2.53%   |
| MediaTek Wireless_Device                            | 2        | 2.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2        | 2.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.53%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 2.53%   |
| IMC Networks Bluetooth Device                       | 2        | 2.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 2.53%   |
| Actions general adapter                             | 2        | 2.53%   |
| TP-Link UB500 Adapter                               | 1        | 1.27%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 1.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.27%   |
| Intel AX210 Bluetooth                               | 1        | 1.27%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1        | 1.27%   |
| Broadcom HP Portable Valentine                      | 1        | 1.27%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.27%   |
| ASUS Bluetooth Device                               | 1        | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 1.27%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.27%   |
| Apple Bluetooth HCI                                 | 1        | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 139      | 39.6%   |
| AMD                                  | 87       | 24.79%  |
| Nvidia                               | 79       | 22.51%  |
| C-Media Electronics                  | 12       | 3.42%   |
| JMTek                                | 4        | 1.14%   |
| Razer USA                            | 3        | 0.85%   |
| Generalplus Technology               | 3        | 0.85%   |
| Elan Microelectronics                | 3        | 0.85%   |
| Creative Labs                        | 3        | 0.85%   |
| SAVITECH                             | 2        | 0.57%   |
| VIA Technologies                     | 1        | 0.28%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.28%   |
| Texas Instruments                    | 1        | 0.28%   |
| Syntek                               | 1        | 0.28%   |
| Nordic Semiconductor ASA             | 1        | 0.28%   |
| Logitech                             | 1        | 0.28%   |
| Kingston Technology                  | 1        | 0.28%   |
| Focusrite-Novation                   | 1        | 0.28%   |
| ESS Technology                       | 1        | 0.28%   |
| Ensoniq                              | 1        | 0.28%   |
| Earth Computer Technologies          | 1        | 0.28%   |
| Blue Microphones                     | 1        | 0.28%   |
| Barco Display Systems                | 1        | 0.28%   |
| Audient                              | 1        | 0.28%   |
| ASUSTek Computer                     | 1        | 0.28%   |
| Apple                                | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24       | 5.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20       | 4.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 3.98%   |
| Intel 200 Series PCH HD Audio                                              | 15       | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 3.28%   |
| AMD Starship/Matisse HD Audio Controller                                   | 14       | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12       | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 2.81%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12       | 2.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 2.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.34%   |
| Nvidia High Definition Audio Controller                                    | 9        | 2.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 1.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 1.87%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.64%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 1.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 1.41%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.17%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.94%   |
| JMTek USB PnP Audio Device                                                 | 4        | 0.94%   |
| C-Media Electronics USB Audio Device                                       | 4        | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 0.94%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 4        | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 0.94%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.7%    |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.7%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.7%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.7%    |
| Generalplus Technology USB Audio Device                                    | 3        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 45       | 41.67%  |
| SK hynix            | 15       | 13.89%  |
| Unknown             | 14       | 12.96%  |
| Samsung Electronics | 10       | 9.26%   |
| Corsair             | 9        | 8.33%   |
| Team                | 2        | 1.85%   |
| Micron Technology   | 2        | 1.85%   |
| G.Skill             | 2        | 1.85%   |
| A-DATA Technology   | 2        | 1.85%   |
| Unknown             | 2        | 1.85%   |
| Unknown (0x02BA)    | 1        | 0.93%   |
| Transcend           | 1        | 0.93%   |
| Ramaxel Technology  | 1        | 0.93%   |
| Hikvision           | 1        | 0.93%   |
| Apacer              | 1        | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 5        | 4.03%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 2.42%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 3        | 2.42%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 3        | 2.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 1.61%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s    | 2        | 1.61%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 2        | 1.61%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 2        | 1.61%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s  | 2        | 1.61%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.61%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.61%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s          | 2        | 1.61%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 1.61%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s     | 2        | 1.61%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 2        | 1.61%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 2        | 1.61%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 1.61%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1333MT/s   | 2        | 1.61%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s     | 2        | 1.61%   |
| Unknown                                                 | 2        | 1.61%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.81%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.81%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 0.81%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s | 1        | 0.81%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s        | 1        | 0.81%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s      | 1        | 0.81%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 3000MT/s   | 1        | 0.81%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.81%   |
| SK hynix RAM Module 1024MB FB-DIMM DDR2 800MT/s         | 1        | 0.81%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.81%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s   | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 44       | 46.81%  |
| DDR3    | 32       | 34.04%  |
| SDRAM   | 6        | 6.38%   |
| DDR2    | 4        | 4.26%   |
| Unknown | 4        | 4.26%   |
| DDR     | 2        | 2.13%   |
| LPDDR4  | 1        | 1.06%   |
| DDR5    | 1        | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 79       | 88.76%  |
| SODIMM  | 8        | 8.99%   |
| RIMM    | 1        | 1.12%   |
| FB-DIMM | 1        | 1.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 39       | 38.61%  |
| 4096  | 30       | 29.7%   |
| 2048  | 14       | 13.86%  |
| 16384 | 9        | 8.91%   |
| 1024  | 6        | 5.94%   |
| 32768 | 3        | 2.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 16.82%  |
| 1333    | 17       | 15.89%  |
| 2400    | 11       | 10.28%  |
| 3200    | 7        | 6.54%   |
| 2133    | 7        | 6.54%   |
| 3733    | 5        | 4.67%   |
| 3600    | 4        | 3.74%   |
| 2667    | 4        | 3.74%   |
| 1867    | 4        | 3.74%   |
| 3400    | 3        | 2.8%    |
| 3000    | 3        | 2.8%    |
| 2666    | 3        | 2.8%    |
| 1866    | 3        | 2.8%    |
| 3466    | 2        | 1.87%   |
| 3151    | 2        | 1.87%   |
| 1800    | 2        | 1.87%   |
| 667     | 2        | 1.87%   |
| 533     | 2        | 1.87%   |
| 6800    | 1        | 0.93%   |
| 3534    | 1        | 0.93%   |
| 3333    | 1        | 0.93%   |
| 2933    | 1        | 0.93%   |
| 2800    | 1        | 0.93%   |
| 800     | 1        | 0.93%   |
| 333     | 1        | 0.93%   |
| Unknown | 1        | 0.93%   |

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
| Logitech                      | 7        | 21.21%  |
| Microdia                      | 5        | 15.15%  |
| Sunplus Innovation Technology | 3        | 9.09%   |
| Generalplus Technology        | 3        | 9.09%   |
| Aveo Technology               | 3        | 9.09%   |
| Microsoft                     | 2        | 6.06%   |
| Apple                         | 2        | 6.06%   |
| Z-Star Microelectronics       | 1        | 3.03%   |
| WCM_USB                       | 1        | 3.03%   |
| Suyin                         | 1        | 3.03%   |
| Silicon Motion                | 1        | 3.03%   |
| Realtek Semiconductor         | 1        | 3.03%   |
| Owon                          | 1        | 3.03%   |
| MacroSilicon                  | 1        | 3.03%   |
| Huawei Technologies           | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microdia Camera                      | 3        | 9.09%   |
| Microsoft MicrosoftÂ LifeCam Cinema | 2        | 6.06%   |
| Logitech Webcam C310                 | 2        | 6.06%   |
| Generalplus GENERAL WEBCAM           | 2        | 6.06%   |
| Aveo USB2.0 Camera                   | 2        | 6.06%   |
| Z-Star Venus USB2.0 Camera           | 1        | 3.03%   |
| WCM_USB WEB CAM                      | 1        | 3.03%   |
| Suyin HP Integrated Webcam           | 1        | 3.03%   |
| Sunplus Webcam                       | 1        | 3.03%   |
| Sunplus SPCA2281 Web Camera          | 1        | 3.03%   |
| Sunplus Full HD webcam               | 1        | 3.03%   |
| Silicon Motion 300k Pixel Camera     | 1        | 3.03%   |
| Realtek USB Camera                   | 1        | 3.03%   |
| Owon USB CAMERA                      | 1        | 3.03%   |
| Microdia Sonix USB 2.0 Camera        | 1        | 3.03%   |
| Microdia Integrated Camera           | 1        | 3.03%   |
| MacroSilicon USB3. 0 capture         | 1        | 3.03%   |
| Logitech Webcam C600                 | 1        | 3.03%   |
| Logitech Webcam C270                 | 1        | 3.03%   |
| Logitech Mic (Notebooks Pro)         | 1        | 3.03%   |
| Logitech HD Webcam C525              | 1        | 3.03%   |
| Logitech HD Webcam C510              | 1        | 3.03%   |
| Huawei HiCamera                      | 1        | 3.03%   |
| Generalplus WEB CAM                  | 1        | 3.03%   |
| Aveo UVC camera (Bresser microscope) | 1        | 3.03%   |
| Apple iSight in LED Cinema Display   | 1        | 3.03%   |
| Apple iPad 2 (3G; 64GB)              | 1        | 3.03%   |

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
| 0     | 181      | 84.58%  |
| 1     | 29       | 13.55%  |
| 2     | 2        | 0.93%   |
| 7     | 1        | 0.47%   |
| 5     | 1        | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 30%     |
| Graphics card            | 10       | 25%     |
| Sound                    | 6        | 15%     |
| Unassigned class         | 4        | 10%     |
| Communication controller | 4        | 10%     |
| Storage/raid             | 1        | 2.5%    |
| Network                  | 1        | 2.5%    |
| Net/ethernet             | 1        | 2.5%    |
| Chipcard                 | 1        | 2.5%    |

