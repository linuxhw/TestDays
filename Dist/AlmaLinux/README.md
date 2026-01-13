AlmaLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/AlmaLinux/Desktop/README.md) and [notebooks](/Dist/AlmaLinux/Notebook/README.md).

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

Total: 582

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [c17e61aec6](https://linux-hardware.org/?probe=c17e61aec6) | Jan 03, 2026 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [ef5b64e46c](https://linux-hardware.org/?probe=ef5b64e46c) | Jan 03, 2026 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [bc03450267](https://linux-hardware.org/?probe=bc03450267) | Dec 31, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [f261d41a4d](https://linux-hardware.org/?probe=f261d41a4d) | Dec 31, 2025 |
| ASRock        | Z590 Phantom Gaming-ITX/... | Desktop     | [1421d2f645](https://linux-hardware.org/?probe=1421d2f645) | Dec 30, 2025 |
| Microsoft     | Surface Go 2                | Tablet      | [20565259aa](https://linux-hardware.org/?probe=20565259aa) | Dec 28, 2025 |
| Microsoft     | Surface Go 2                | Tablet      | [b63a87dcc1](https://linux-hardware.org/?probe=b63a87dcc1) | Dec 22, 2025 |
| ASUSTek       | PRIME Z790-V WIFI           | Desktop     | [305fb21e1d](https://linux-hardware.org/?probe=305fb21e1d) | Dec 18, 2025 |
| Dell          | Inspiron 3793               | Notebook    | [14ececb143](https://linux-hardware.org/?probe=14ececb143) | Dec 13, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [6bf0f0bba8](https://linux-hardware.org/?probe=6bf0f0bba8) | Dec 09, 2025 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [86333b650a](https://linux-hardware.org/?probe=86333b650a) | Dec 04, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [14a29d0611](https://linux-hardware.org/?probe=14a29d0611) | Dec 01, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [0718898011](https://linux-hardware.org/?probe=0718898011) | Nov 30, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [6386a90620](https://linux-hardware.org/?probe=6386a90620) | Nov 30, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [1c9df6be5b](https://linux-hardware.org/?probe=1c9df6be5b) | Nov 29, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [128ded3e9b](https://linux-hardware.org/?probe=128ded3e9b) | Nov 29, 2025 |
| Lenovo        | 333F SDK0T76461 WIN 3422... | Mini pc     | [86556eedd4](https://linux-hardware.org/?probe=86556eedd4) | Nov 20, 2025 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [fa0623e0eb](https://linux-hardware.org/?probe=fa0623e0eb) | Nov 17, 2025 |
| Mancer        | B450M-DA V1.1               | Desktop     | [b5cf104129](https://linux-hardware.org/?probe=b5cf104129) | Nov 16, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [75d74f1ae6](https://linux-hardware.org/?probe=75d74f1ae6) | Nov 16, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [d942296416](https://linux-hardware.org/?probe=d942296416) | Nov 14, 2025 |
| MSI           | Z77A-GD80                   | Desktop     | [045c98d53b](https://linux-hardware.org/?probe=045c98d53b) | Nov 11, 2025 |
| Raspberry ... | Raspberry Pi                | Soc         | [e60e2545f6](https://linux-hardware.org/?probe=e60e2545f6) | Nov 05, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [e4db30a73e](https://linux-hardware.org/?probe=e4db30a73e) | Nov 04, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [948f2cf6d9](https://linux-hardware.org/?probe=948f2cf6d9) | Nov 04, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [a4d954dc34](https://linux-hardware.org/?probe=a4d954dc34) | Nov 03, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [dadc86a477](https://linux-hardware.org/?probe=dadc86a477) | Nov 03, 2025 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [81b19f590a](https://linux-hardware.org/?probe=81b19f590a) | Nov 01, 2025 |
| Supermicro    | X10DRU-i+B                  | Desktop     | [8fae6555b0](https://linux-hardware.org/?probe=8fae6555b0) | Oct 30, 2025 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | Notebook    | [9eb8122f08](https://linux-hardware.org/?probe=9eb8122f08) | Oct 30, 2025 |
| MSI           | H310M PRO-VD                | Desktop     | [5cef1d2379](https://linux-hardware.org/?probe=5cef1d2379) | Oct 21, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [a99fb747fe](https://linux-hardware.org/?probe=a99fb747fe) | Oct 13, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [926c55586f](https://linux-hardware.org/?probe=926c55586f) | Oct 13, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [2e51e3c02c](https://linux-hardware.org/?probe=2e51e3c02c) | Oct 12, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [e93368eb13](https://linux-hardware.org/?probe=e93368eb13) | Oct 12, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [84227914e9](https://linux-hardware.org/?probe=84227914e9) | Oct 04, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [ac2a364593](https://linux-hardware.org/?probe=ac2a364593) | Oct 03, 2025 |
| HP            | 829A                        | Mini pc     | [aa9d825936](https://linux-hardware.org/?probe=aa9d825936) | Sep 30, 2025 |
| ASUSTek       | K14PA-U24 Series 60SB0B6... | Server      | [c303457ff4](https://linux-hardware.org/?probe=c303457ff4) | Sep 27, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [1dee33c97b](https://linux-hardware.org/?probe=1dee33c97b) | Sep 26, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [1b9eb825f1](https://linux-hardware.org/?probe=1b9eb825f1) | Sep 26, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [c3d29a2f3f](https://linux-hardware.org/?probe=c3d29a2f3f) | Sep 26, 2025 |
| Chuwi         | Hi10 X1                     | Tablet      | [099d99b4d3](https://linux-hardware.org/?probe=099d99b4d3) | Sep 24, 2025 |
| Gigabyte      | X570S UD                    | Desktop     | [6b0499293c](https://linux-hardware.org/?probe=6b0499293c) | Sep 23, 2025 |
| Dell          | Pro Max 16 MC16250          | Notebook    | [f17528762c](https://linux-hardware.org/?probe=f17528762c) | Sep 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [d24dccbf63](https://linux-hardware.org/?probe=d24dccbf63) | Sep 08, 2025 |
| Shenzhen M... | F7BSI                       | Mini pc     | [11bf7af406](https://linux-hardware.org/?probe=11bf7af406) | Sep 07, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [56e1b15636](https://linux-hardware.org/?probe=56e1b15636) | Sep 07, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [ef8623d425](https://linux-hardware.org/?probe=ef8623d425) | Sep 07, 2025 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [02d5b6d42b](https://linux-hardware.org/?probe=02d5b6d42b) | Sep 06, 2025 |
| ASUSTek       | Pro WS WRX90E-SAGE SE       | Desktop     | [744af99a4e](https://linux-hardware.org/?probe=744af99a4e) | Sep 06, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [3e3bb70743](https://linux-hardware.org/?probe=3e3bb70743) | Sep 06, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [75a5f59f24](https://linux-hardware.org/?probe=75a5f59f24) | Sep 06, 2025 |
| Unknown       | Unknown                     | Notebook    | [b4a7dc6dea](https://linux-hardware.org/?probe=b4a7dc6dea) | Aug 17, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [912f522590](https://linux-hardware.org/?probe=912f522590) | Aug 06, 2025 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f5ee8ddbd9](https://linux-hardware.org/?probe=f5ee8ddbd9) | Jul 23, 2025 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [3a2f253a7c](https://linux-hardware.org/?probe=3a2f253a7c) | Jul 18, 2025 |
| IBM           | Processor/Memory Card       | Server      | [2b92fac1a3](https://linux-hardware.org/?probe=2b92fac1a3) | Jul 16, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [465cc78655](https://linux-hardware.org/?probe=465cc78655) | Jul 15, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [55447de5cb](https://linux-hardware.org/?probe=55447de5cb) | Jul 15, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [b9691462b8](https://linux-hardware.org/?probe=b9691462b8) | Jul 14, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [efa2eb95a3](https://linux-hardware.org/?probe=efa2eb95a3) | Jul 14, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [f56ff87e49](https://linux-hardware.org/?probe=f56ff87e49) | Jul 13, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [c84c488b2c](https://linux-hardware.org/?probe=c84c488b2c) | Jul 13, 2025 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [0ea65635ee](https://linux-hardware.org/?probe=0ea65635ee) | Jul 10, 2025 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [e4862b2cfb](https://linux-hardware.org/?probe=e4862b2cfb) | Jul 10, 2025 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [49892ac27e](https://linux-hardware.org/?probe=49892ac27e) | Jun 22, 2025 |
| Lenovo        | G700 20251                  | Notebook    | [3abd3c98b9](https://linux-hardware.org/?probe=3abd3c98b9) | Jun 21, 2025 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [094c7d11b2](https://linux-hardware.org/?probe=094c7d11b2) | Jun 11, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [006860edf7](https://linux-hardware.org/?probe=006860edf7) | Jun 02, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [761621ff40](https://linux-hardware.org/?probe=761621ff40) | Jun 02, 2025 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [927f8d5adc](https://linux-hardware.org/?probe=927f8d5adc) | Jun 01, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [06d6849c2a](https://linux-hardware.org/?probe=06d6849c2a) | Jun 01, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [26d84872fa](https://linux-hardware.org/?probe=26d84872fa) | Jun 01, 2025 |
| Optimized ... | KVM                         | Desktop     | [7a5e8bbb73](https://linux-hardware.org/?probe=7a5e8bbb73) | May 23, 2025 |
| Optimized ... | KVM                         | Desktop     | [ba0da05513](https://linux-hardware.org/?probe=ba0da05513) | May 16, 2025 |
| Samsung       | R530/R730/P530              | Notebook    | [d673085045](https://linux-hardware.org/?probe=d673085045) | May 15, 2025 |
| Lenovo        | Legion Slim 5 16AHP9 83D... | Notebook    | [a62025ce3c](https://linux-hardware.org/?probe=a62025ce3c) | May 12, 2025 |
| Dell          | Inspiron 15 3520            | Notebook    | [88d2d390ab](https://linux-hardware.org/?probe=88d2d390ab) | May 08, 2025 |
| Gigabyte      | MFLP7IP-00                  | Desktop     | [95c9b5ef7e](https://linux-hardware.org/?probe=95c9b5ef7e) | May 06, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [74f075f311](https://linux-hardware.org/?probe=74f075f311) | May 03, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8050d74b71](https://linux-hardware.org/?probe=8050d74b71) | May 03, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [c12dadedbd](https://linux-hardware.org/?probe=c12dadedbd) | May 02, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [333314c522](https://linux-hardware.org/?probe=333314c522) | May 02, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [6fbe188c9d](https://linux-hardware.org/?probe=6fbe188c9d) | Apr 30, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [daa83797df](https://linux-hardware.org/?probe=daa83797df) | Apr 30, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [5386b50379](https://linux-hardware.org/?probe=5386b50379) | Apr 29, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [41eb9ecfe0](https://linux-hardware.org/?probe=41eb9ecfe0) | Apr 29, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [fd0f4cc032](https://linux-hardware.org/?probe=fd0f4cc032) | Apr 15, 2025 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [64afda3481](https://linux-hardware.org/?probe=64afda3481) | Apr 04, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [8b507bf4b9](https://linux-hardware.org/?probe=8b507bf4b9) | Mar 31, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b0546bd429](https://linux-hardware.org/?probe=b0546bd429) | Mar 31, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [db97f95319](https://linux-hardware.org/?probe=db97f95319) | Mar 30, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [c66504c6ac](https://linux-hardware.org/?probe=c66504c6ac) | Mar 30, 2025 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [3073ae0e1a](https://linux-hardware.org/?probe=3073ae0e1a) | Mar 21, 2025 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [c67c792e5b](https://linux-hardware.org/?probe=c67c792e5b) | Mar 16, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [aa0a261c34](https://linux-hardware.org/?probe=aa0a261c34) | Mar 15, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [f2a43704cd](https://linux-hardware.org/?probe=f2a43704cd) | Mar 15, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [c8ab59434c](https://linux-hardware.org/?probe=c8ab59434c) | Mar 14, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [c5664c3dd7](https://linux-hardware.org/?probe=c5664c3dd7) | Mar 14, 2025 |
| Toshiba       | Satellite C50-A             | Notebook    | [1a6125c8e8](https://linux-hardware.org/?probe=1a6125c8e8) | Mar 09, 2025 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [515442999b](https://linux-hardware.org/?probe=515442999b) | Feb 22, 2025 |
| Lenovo        | ThinkPad X201 3249PJ2       | Notebook    | [4f11732833](https://linux-hardware.org/?probe=4f11732833) | Feb 10, 2025 |
| Lenovo        | ThinkPad X201 3249PJ2       | Notebook    | [7abf14106c](https://linux-hardware.org/?probe=7abf14106c) | Feb 10, 2025 |
| Lenovo        | ThinkPad E490 20N80019RT    | Notebook    | [f390dac47e](https://linux-hardware.org/?probe=f390dac47e) | Feb 06, 2025 |
| Supermicro    | X9DR3-F                     | Desktop     | [ad9c3075c6](https://linux-hardware.org/?probe=ad9c3075c6) | Jan 30, 2025 |
| Lenovo        | Kabini CRB NOK              | Desktop     | [13d31c68c4](https://linux-hardware.org/?probe=13d31c68c4) | Jan 26, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [ab8c470d23](https://linux-hardware.org/?probe=ab8c470d23) | Jan 26, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [fe15cade67](https://linux-hardware.org/?probe=fe15cade67) | Jan 26, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [84a9e82b1b](https://linux-hardware.org/?probe=84a9e82b1b) | Jan 25, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [86bca86072](https://linux-hardware.org/?probe=86bca86072) | Jan 25, 2025 |
| Acer          | TravelMate 5735Z            | Notebook    | [661c43dfab](https://linux-hardware.org/?probe=661c43dfab) | Jan 23, 2025 |
| Supermicro    | X8DTT-H                     | Server      | [447e492b9c](https://linux-hardware.org/?probe=447e492b9c) | Jan 18, 2025 |
| Gigabyte      | B85M-D3H                    | Desktop     | [544dbadbcb](https://linux-hardware.org/?probe=544dbadbcb) | Jan 15, 2025 |
| ASRock        | G31M-S                      | Desktop     | [b4354eea8e](https://linux-hardware.org/?probe=b4354eea8e) | Jan 15, 2025 |
| Dell          | 0441XG A03                  | Server      | [f006061247](https://linux-hardware.org/?probe=f006061247) | Jan 14, 2025 |
| Supermicro    | H13SSWA                     | Desktop     | [b9b242c650](https://linux-hardware.org/?probe=b9b242c650) | Jan 10, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [b6fcb8b227](https://linux-hardware.org/?probe=b6fcb8b227) | Jan 08, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [ffc229a175](https://linux-hardware.org/?probe=ffc229a175) | Jan 07, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [7fa7e6f446](https://linux-hardware.org/?probe=7fa7e6f446) | Jan 07, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [726b65d6e8](https://linux-hardware.org/?probe=726b65d6e8) | Jan 06, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [ee0c91380e](https://linux-hardware.org/?probe=ee0c91380e) | Jan 06, 2025 |
| Pelco by S... | DS-SRV2 S584XF01            | Desktop     | [7ed2a57a58](https://linux-hardware.org/?probe=7ed2a57a58) | Jan 03, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [5dc2296b94](https://linux-hardware.org/?probe=5dc2296b94) | Jan 01, 2025 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [0adfc8ea5f](https://linux-hardware.org/?probe=0adfc8ea5f) | Jan 01, 2025 |
| Supermicro    | H12SSL-i                    | Server      | [e8ffdf8b2d](https://linux-hardware.org/?probe=e8ffdf8b2d) | Dec 31, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [14044c578b](https://linux-hardware.org/?probe=14044c578b) | Dec 31, 2024 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [4caf6d911a](https://linux-hardware.org/?probe=4caf6d911a) | Dec 23, 2024 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | Notebook    | [f05b1b8a31](https://linux-hardware.org/?probe=f05b1b8a31) | Dec 21, 2024 |
| Dell          | 0JP3NX A01                  | Desktop     | [8675954a59](https://linux-hardware.org/?probe=8675954a59) | Dec 20, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f160b8eebe](https://linux-hardware.org/?probe=f160b8eebe) | Dec 16, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [3b5445782a](https://linux-hardware.org/?probe=3b5445782a) | Dec 12, 2024 |
| Dell          | 02C2CP A01                  | Server      | [22ce816d89](https://linux-hardware.org/?probe=22ce816d89) | Dec 05, 2024 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [5bdb93a154](https://linux-hardware.org/?probe=5bdb93a154) | Dec 02, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [942f24447b](https://linux-hardware.org/?probe=942f24447b) | Nov 28, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [1e77f8e198](https://linux-hardware.org/?probe=1e77f8e198) | Nov 24, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4cc9afa3bf](https://linux-hardware.org/?probe=4cc9afa3bf) | Nov 24, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [359f4d3d30](https://linux-hardware.org/?probe=359f4d3d30) | Nov 23, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [5408129e26](https://linux-hardware.org/?probe=5408129e26) | Nov 23, 2024 |
| Optimized ... | KVM                         | Desktop     | [672aaf8ea5](https://linux-hardware.org/?probe=672aaf8ea5) | Nov 22, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [28a641e4dd](https://linux-hardware.org/?probe=28a641e4dd) | Nov 22, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [0a20cf1768](https://linux-hardware.org/?probe=0a20cf1768) | Nov 09, 2024 |
| HP            | Falco                       | Notebook    | [f270f62d2c](https://linux-hardware.org/?probe=f270f62d2c) | Nov 08, 2024 |
| ASUSTek       | ROG Zephyrus GX550LWS_GX... | Notebook    | [a73a429ab8](https://linux-hardware.org/?probe=a73a429ab8) | Oct 27, 2024 |
| Medion        | MS-7616                     | Desktop     | [0c544180a0](https://linux-hardware.org/?probe=0c544180a0) | Oct 23, 2024 |
| HP            | ProLiant DL360p Gen8        | Server      | [df440f3473](https://linux-hardware.org/?probe=df440f3473) | Oct 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V5.1       | Desktop     | [d7e2cffa85](https://linux-hardware.org/?probe=d7e2cffa85) | Oct 19, 2024 |
| HP            | 829E                        | Mini pc     | [c3ead56b7b](https://linux-hardware.org/?probe=c3ead56b7b) | Oct 19, 2024 |
| HP            | 829E                        | Mini pc     | [8099eae195](https://linux-hardware.org/?probe=8099eae195) | Oct 19, 2024 |
| Dell          | Latitude 7480               | Notebook    | [83e587119c](https://linux-hardware.org/?probe=83e587119c) | Oct 18, 2024 |
| Dell          | 0K2NWM A00                  | Desktop     | [465d3bfbda](https://linux-hardware.org/?probe=465d3bfbda) | Oct 17, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [217df1294e](https://linux-hardware.org/?probe=217df1294e) | Oct 13, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [daced3e3e7](https://linux-hardware.org/?probe=daced3e3e7) | Oct 13, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [d9e4d61ee0](https://linux-hardware.org/?probe=d9e4d61ee0) | Oct 12, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [2437961826](https://linux-hardware.org/?probe=2437961826) | Oct 12, 2024 |
| Supermicro    | H11SSL-i                    | Server      | [6a9553c435](https://linux-hardware.org/?probe=6a9553c435) | Oct 10, 2024 |
| MSI           | Boston                      | Desktop     | [8e086f2e70](https://linux-hardware.org/?probe=8e086f2e70) | Oct 02, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e21b766bf5](https://linux-hardware.org/?probe=e21b766bf5) | Sep 27, 2024 |
| HP            | 0AA0h                       | Desktop     | [056856286b](https://linux-hardware.org/?probe=056856286b) | Sep 26, 2024 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [550001d98f](https://linux-hardware.org/?probe=550001d98f) | Sep 20, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1f5d5dbaa3](https://linux-hardware.org/?probe=1f5d5dbaa3) | Sep 20, 2024 |
| HP            | ProLiant DL360p Gen8        | Server      | [6fef77f9b0](https://linux-hardware.org/?probe=6fef77f9b0) | Sep 18, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [9f6b43e99e](https://linux-hardware.org/?probe=9f6b43e99e) | Sep 13, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [fa1b825886](https://linux-hardware.org/?probe=fa1b825886) | Sep 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [9f2adb4d94](https://linux-hardware.org/?probe=9f2adb4d94) | Sep 10, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [554f4150cf](https://linux-hardware.org/?probe=554f4150cf) | Sep 08, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [c41f2cc6f8](https://linux-hardware.org/?probe=c41f2cc6f8) | Sep 08, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ca5b22a774](https://linux-hardware.org/?probe=ca5b22a774) | Sep 07, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [fffa16b61f](https://linux-hardware.org/?probe=fffa16b61f) | Sep 07, 2024 |
| Supermicro    | X8DTT-H                     | Server      | [3ebf716fae](https://linux-hardware.org/?probe=3ebf716fae) | Sep 05, 2024 |
| HP            | 1791                        | Desktop     | [1bd7f12e61](https://linux-hardware.org/?probe=1bd7f12e61) | Sep 05, 2024 |
| HP            | 1589                        | Desktop     | [a21e698c3c](https://linux-hardware.org/?probe=a21e698c3c) | Sep 05, 2024 |
| Supermicro    | X11DDW-NT                   | Server      | [a9b00d3d78](https://linux-hardware.org/?probe=a9b00d3d78) | Sep 02, 2024 |
| Dell          | 0JP3NX A01                  | Desktop     | [0353987388](https://linux-hardware.org/?probe=0353987388) | Aug 31, 2024 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [08fd89ae34](https://linux-hardware.org/?probe=08fd89ae34) | Aug 22, 2024 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [069e34f016](https://linux-hardware.org/?probe=069e34f016) | Aug 20, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [fdf15d2573](https://linux-hardware.org/?probe=fdf15d2573) | Aug 16, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [86f6e1d447](https://linux-hardware.org/?probe=86f6e1d447) | Aug 16, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [5685155a60](https://linux-hardware.org/?probe=5685155a60) | Aug 16, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [9285a26f03](https://linux-hardware.org/?probe=9285a26f03) | Aug 15, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [abc943616e](https://linux-hardware.org/?probe=abc943616e) | Aug 15, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [729a667d33](https://linux-hardware.org/?probe=729a667d33) | Aug 15, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [2a780be401](https://linux-hardware.org/?probe=2a780be401) | Aug 14, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [d5ba737682](https://linux-hardware.org/?probe=d5ba737682) | Aug 14, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [ecec20fc93](https://linux-hardware.org/?probe=ecec20fc93) | Aug 14, 2024 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [906cb59c42](https://linux-hardware.org/?probe=906cb59c42) | Aug 08, 2024 |
| Gigabyte      | GA-880GM-USB3L              | Desktop     | [a0a2b265e5](https://linux-hardware.org/?probe=a0a2b265e5) | Aug 06, 2024 |
| HP            | ENVY 15                     | Notebook    | [4b7e703303](https://linux-hardware.org/?probe=4b7e703303) | Jul 10, 2024 |
| Lenovo        | ThinkPad E470c 20H3A013C... | Notebook    | [3a0eb6920e](https://linux-hardware.org/?probe=3a0eb6920e) | Jul 08, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [e92ab633c2](https://linux-hardware.org/?probe=e92ab633c2) | Jul 08, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [92e71a5472](https://linux-hardware.org/?probe=92e71a5472) | Jul 08, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [dc13005f47](https://linux-hardware.org/?probe=dc13005f47) | Jul 07, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [51cbdd5f26](https://linux-hardware.org/?probe=51cbdd5f26) | Jul 07, 2024 |
| Lenovo        | ThinkPad W701 2541W12       | Notebook    | [85fd4bfe94](https://linux-hardware.org/?probe=85fd4bfe94) | Jul 06, 2024 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [3bf15e63ac](https://linux-hardware.org/?probe=3bf15e63ac) | Jun 21, 2024 |
| MSI           | Boston                      | Desktop     | [4b244032d0](https://linux-hardware.org/?probe=4b244032d0) | Jun 19, 2024 |
| MSI           | Boston                      | Desktop     | [5252f63696](https://linux-hardware.org/?probe=5252f63696) | Jun 19, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [ab084dfd84](https://linux-hardware.org/?probe=ab084dfd84) | Jun 19, 2024 |
| Lenovo        | ThinkPad X390 20Q00039CD    | Notebook    | [1a88d526f1](https://linux-hardware.org/?probe=1a88d526f1) | Jun 16, 2024 |
| HP            | ENVY 15                     | Notebook    | [a7591276ca](https://linux-hardware.org/?probe=a7591276ca) | Jun 09, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [bd9b9e958e](https://linux-hardware.org/?probe=bd9b9e958e) | Jun 09, 2024 |
| ASRock        | Z790 PG SONIC               | Desktop     | [b5098f47bc](https://linux-hardware.org/?probe=b5098f47bc) | Jun 09, 2024 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [98633fa042](https://linux-hardware.org/?probe=98633fa042) | Jun 08, 2024 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [78e8b0e68e](https://linux-hardware.org/?probe=78e8b0e68e) | Jun 07, 2024 |
| Lenovo        | Kabini CRB NOK              | Desktop     | [f1053f6b0e](https://linux-hardware.org/?probe=f1053f6b0e) | Jun 05, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [e29deb87ee](https://linux-hardware.org/?probe=e29deb87ee) | May 28, 2024 |
| Lenovo        | Kabini CRB NOK              | Desktop     | [f5c76261aa](https://linux-hardware.org/?probe=f5c76261aa) | May 12, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [0b3a3e7fb3](https://linux-hardware.org/?probe=0b3a3e7fb3) | May 10, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [7006277703](https://linux-hardware.org/?probe=7006277703) | May 10, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [d5cf0eca85](https://linux-hardware.org/?probe=d5cf0eca85) | May 09, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [236ac0d0ed](https://linux-hardware.org/?probe=236ac0d0ed) | May 09, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [c5f9a761a9](https://linux-hardware.org/?probe=c5f9a761a9) | May 05, 2024 |
| ASRockRack    | X570D4I-2T                  | Server      | [fd5c83c424](https://linux-hardware.org/?probe=fd5c83c424) | May 02, 2024 |
| Acer          | Aspire E1-571               | Notebook    | [0f3b954320](https://linux-hardware.org/?probe=0f3b954320) | May 02, 2024 |
| Lenovo        | Kabini CRB NOK              | Desktop     | [dfa3d8f2cd](https://linux-hardware.org/?probe=dfa3d8f2cd) | Apr 29, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [cabe5d7a20](https://linux-hardware.org/?probe=cabe5d7a20) | Apr 23, 2024 |
| Haier         | TIGD2-CI                    | Desktop     | [dc4f526a80](https://linux-hardware.org/?probe=dc4f526a80) | Apr 23, 2024 |
| Dell          | 0D441T A01                  | Desktop     | [98b14bc73d](https://linux-hardware.org/?probe=98b14bc73d) | Apr 10, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ded5f6b3ba](https://linux-hardware.org/?probe=ded5f6b3ba) | Apr 07, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4f14a1fb58](https://linux-hardware.org/?probe=4f14a1fb58) | Apr 07, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [f1de845101](https://linux-hardware.org/?probe=f1de845101) | Apr 06, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [271844c58a](https://linux-hardware.org/?probe=271844c58a) | Apr 06, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [f1c498121d](https://linux-hardware.org/?probe=f1c498121d) | Mar 13, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7db787716d](https://linux-hardware.org/?probe=7db787716d) | Mar 12, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [ffc080a6f0](https://linux-hardware.org/?probe=ffc080a6f0) | Mar 09, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [3a33a36874](https://linux-hardware.org/?probe=3a33a36874) | Mar 09, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [64c28ad883](https://linux-hardware.org/?probe=64c28ad883) | Mar 05, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [2229c82401](https://linux-hardware.org/?probe=2229c82401) | Mar 03, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [43522636f8](https://linux-hardware.org/?probe=43522636f8) | Mar 02, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [3ce277e7b9](https://linux-hardware.org/?probe=3ce277e7b9) | Feb 25, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [c58df8f5e4](https://linux-hardware.org/?probe=c58df8f5e4) | Feb 19, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4a75bbf769](https://linux-hardware.org/?probe=4a75bbf769) | Feb 19, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [6745442873](https://linux-hardware.org/?probe=6745442873) | Feb 18, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9a9a9f6fb3](https://linux-hardware.org/?probe=9a9a9f6fb3) | Feb 18, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [3d01ffb3f6](https://linux-hardware.org/?probe=3d01ffb3f6) | Feb 13, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [ac5fe15861](https://linux-hardware.org/?probe=ac5fe15861) | Feb 12, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [6db0b8a8f1](https://linux-hardware.org/?probe=6db0b8a8f1) | Feb 03, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [00056f1b48](https://linux-hardware.org/?probe=00056f1b48) | Feb 03, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [17031c6aac](https://linux-hardware.org/?probe=17031c6aac) | Feb 02, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [0fa43445d1](https://linux-hardware.org/?probe=0fa43445d1) | Feb 02, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [f206485d60](https://linux-hardware.org/?probe=f206485d60) | Feb 01, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b7bc0cf1ac](https://linux-hardware.org/?probe=b7bc0cf1ac) | Feb 01, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [6849639353](https://linux-hardware.org/?probe=6849639353) | Jan 31, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d67b24a21d](https://linux-hardware.org/?probe=d67b24a21d) | Jan 31, 2024 |
| HP            | Falco                       | Notebook    | [9a82a5b9e8](https://linux-hardware.org/?probe=9a82a5b9e8) | Jan 26, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [343e08f1a6](https://linux-hardware.org/?probe=343e08f1a6) | Jan 24, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [61f8c8c9e0](https://linux-hardware.org/?probe=61f8c8c9e0) | Jan 22, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [3c8308af97](https://linux-hardware.org/?probe=3c8308af97) | Jan 22, 2024 |
| HP            | ENVY 15                     | Notebook    | [95ec6d10d0](https://linux-hardware.org/?probe=95ec6d10d0) | Jan 19, 2024 |
| Acer          | TravelMate 5735Z            | Notebook    | [6d759892ab](https://linux-hardware.org/?probe=6d759892ab) | Jan 12, 2024 |
| Acer          | TravelMate 5735Z            | Notebook    | [2ad65584c2](https://linux-hardware.org/?probe=2ad65584c2) | Jan 11, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [8cf8ef7602](https://linux-hardware.org/?probe=8cf8ef7602) | Jan 11, 2024 |
| Optimized ... | KVM                         | Desktop     | [4fe928d059](https://linux-hardware.org/?probe=4fe928d059) | Jan 11, 2024 |
| HP            | Falco                       | Notebook    | [f6a8ee9181](https://linux-hardware.org/?probe=f6a8ee9181) | Jan 11, 2024 |
| Dell          | Precision 5680              | Notebook    | [82dc0a13bb](https://linux-hardware.org/?probe=82dc0a13bb) | Jan 10, 2024 |
| Supermicro    | X8DTT-H                     | Server      | [0fb61ad105](https://linux-hardware.org/?probe=0fb61ad105) | Jan 05, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ac848615a7](https://linux-hardware.org/?probe=ac848615a7) | Jan 03, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [0be3bb4773](https://linux-hardware.org/?probe=0be3bb4773) | Jan 03, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [454b403b53](https://linux-hardware.org/?probe=454b403b53) | Jan 02, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [a1095fd614](https://linux-hardware.org/?probe=a1095fd614) | Jan 02, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [0003baf54d](https://linux-hardware.org/?probe=0003baf54d) | Jan 01, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [cc645ac529](https://linux-hardware.org/?probe=cc645ac529) | Jan 01, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ae544239b5](https://linux-hardware.org/?probe=ae544239b5) | Dec 31, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b9db9c256b](https://linux-hardware.org/?probe=b9db9c256b) | Dec 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a5f60699ce](https://linux-hardware.org/?probe=a5f60699ce) | Dec 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b19b947d42](https://linux-hardware.org/?probe=b19b947d42) | Dec 25, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [df01343f10](https://linux-hardware.org/?probe=df01343f10) | Dec 24, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [346c422237](https://linux-hardware.org/?probe=346c422237) | Dec 24, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [aa11af3235](https://linux-hardware.org/?probe=aa11af3235) | Dec 20, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f504f4b8d5](https://linux-hardware.org/?probe=f504f4b8d5) | Dec 19, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f4707e0e75](https://linux-hardware.org/?probe=f4707e0e75) | Dec 19, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [27cd685574](https://linux-hardware.org/?probe=27cd685574) | Dec 18, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9a521bb0c9](https://linux-hardware.org/?probe=9a521bb0c9) | Dec 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3b37f8220f](https://linux-hardware.org/?probe=3b37f8220f) | Dec 17, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [91f9814da4](https://linux-hardware.org/?probe=91f9814da4) | Dec 17, 2023 |
| Timi          | TM1709                      | Notebook    | [f566951fd0](https://linux-hardware.org/?probe=f566951fd0) | Dec 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [230f41f6b5](https://linux-hardware.org/?probe=230f41f6b5) | Dec 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e5415e7df5](https://linux-hardware.org/?probe=e5415e7df5) | Dec 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [93675534e1](https://linux-hardware.org/?probe=93675534e1) | Dec 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [85c03e03e8](https://linux-hardware.org/?probe=85c03e03e8) | Dec 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [746c6adb3f](https://linux-hardware.org/?probe=746c6adb3f) | Dec 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [7eaae92099](https://linux-hardware.org/?probe=7eaae92099) | Dec 04, 2023 |
| AOCWEI        | A2                          | Notebook    | [ac8272a8a8](https://linux-hardware.org/?probe=ac8272a8a8) | Nov 26, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [d231a15a8f](https://linux-hardware.org/?probe=d231a15a8f) | Nov 22, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a2c80195ae](https://linux-hardware.org/?probe=a2c80195ae) | Nov 21, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [1d8266c67b](https://linux-hardware.org/?probe=1d8266c67b) | Nov 21, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [e8e233f240](https://linux-hardware.org/?probe=e8e233f240) | Nov 20, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4dbe82fc95](https://linux-hardware.org/?probe=4dbe82fc95) | Nov 20, 2023 |
| Intel         | X99                         | Desktop     | [c07799299c](https://linux-hardware.org/?probe=c07799299c) | Nov 19, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [ec6ef64584](https://linux-hardware.org/?probe=ec6ef64584) | Nov 18, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [a8349dda46](https://linux-hardware.org/?probe=a8349dda46) | Nov 16, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [e0bc805f38](https://linux-hardware.org/?probe=e0bc805f38) | Nov 16, 2023 |
| AOCWEI        | A2                          | Notebook    | [1006e22f22](https://linux-hardware.org/?probe=1006e22f22) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [056e939d6d](https://linux-hardware.org/?probe=056e939d6d) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [6c8040c314](https://linux-hardware.org/?probe=6c8040c314) | Nov 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49051e4c14](https://linux-hardware.org/?probe=49051e4c14) | Nov 07, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [fca6e5bc74](https://linux-hardware.org/?probe=fca6e5bc74) | Nov 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0bcc882e05](https://linux-hardware.org/?probe=0bcc882e05) | Nov 06, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [963acb5f2b](https://linux-hardware.org/?probe=963acb5f2b) | Nov 06, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [e3760a331a](https://linux-hardware.org/?probe=e3760a331a) | Oct 31, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [492563a83c](https://linux-hardware.org/?probe=492563a83c) | Oct 24, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3e4b32b047](https://linux-hardware.org/?probe=3e4b32b047) | Oct 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3880cb8ecf](https://linux-hardware.org/?probe=3880cb8ecf) | Oct 22, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [7cdd3de48b](https://linux-hardware.org/?probe=7cdd3de48b) | Oct 22, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8deecaac39](https://linux-hardware.org/?probe=8deecaac39) | Oct 21, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [a0ebc9b489](https://linux-hardware.org/?probe=a0ebc9b489) | Oct 21, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| Dell          | Precision 7760              | Notebook    | [4b42c6c7f1](https://linux-hardware.org/?probe=4b42c6c7f1) | Oct 14, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d9bbe8269c](https://linux-hardware.org/?probe=d9bbe8269c) | Oct 10, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [27ce5f6a61](https://linux-hardware.org/?probe=27ce5f6a61) | Oct 06, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [ccdf9d0cfa](https://linux-hardware.org/?probe=ccdf9d0cfa) | Oct 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [527518057b](https://linux-hardware.org/?probe=527518057b) | Oct 02, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [88e4c09c2f](https://linux-hardware.org/?probe=88e4c09c2f) | Oct 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [53fec3f094](https://linux-hardware.org/?probe=53fec3f094) | Oct 01, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9115ea465f](https://linux-hardware.org/?probe=9115ea465f) | Oct 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ce97609be](https://linux-hardware.org/?probe=6ce97609be) | Sep 30, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [da0e120624](https://linux-hardware.org/?probe=da0e120624) | Sep 30, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [1b72177563](https://linux-hardware.org/?probe=1b72177563) | Sep 26, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [2527f2a9fc](https://linux-hardware.org/?probe=2527f2a9fc) | Sep 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3e533c5366](https://linux-hardware.org/?probe=3e533c5366) | Sep 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d37c8958bf](https://linux-hardware.org/?probe=d37c8958bf) | Sep 25, 2023 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| Dell          | Latitude E5420              | Notebook    | [0b1b042a5b](https://linux-hardware.org/?probe=0b1b042a5b) | Sep 19, 2023 |
| HP            | Notebook                    | Notebook    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac96127f34](https://linux-hardware.org/?probe=ac96127f34) | Sep 08, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [779e2ad458](https://linux-hardware.org/?probe=779e2ad458) | Sep 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c0498360ff](https://linux-hardware.org/?probe=c0498360ff) | Sep 07, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [6cc92a61b2](https://linux-hardware.org/?probe=6cc92a61b2) | Sep 07, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f06bf24212](https://linux-hardware.org/?probe=f06bf24212) | Sep 05, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [167ab1eb1c](https://linux-hardware.org/?probe=167ab1eb1c) | Sep 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [dc9d1ca231](https://linux-hardware.org/?probe=dc9d1ca231) | Sep 04, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b980688633](https://linux-hardware.org/?probe=b980688633) | Sep 04, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| Dell          | Latitude 5490               | Notebook    | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Dell          | 00WGD1 A01                  | Server      | [d288d87ab5](https://linux-hardware.org/?probe=d288d87ab5) | Aug 14, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d61d7e9135](https://linux-hardware.org/?probe=d61d7e9135) | Aug 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d319474025](https://linux-hardware.org/?probe=d319474025) | Aug 13, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0b7f8d13d9](https://linux-hardware.org/?probe=0b7f8d13d9) | Aug 12, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8a896a42c0](https://linux-hardware.org/?probe=8a896a42c0) | Aug 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b7245ccb6f](https://linux-hardware.org/?probe=b7245ccb6f) | Aug 11, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [cff9e815b3](https://linux-hardware.org/?probe=cff9e815b3) | Aug 11, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [35b274571c](https://linux-hardware.org/?probe=35b274571c) | Aug 05, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [92d07e2cae](https://linux-hardware.org/?probe=92d07e2cae) | Aug 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [592e977971](https://linux-hardware.org/?probe=592e977971) | Aug 04, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d05269baea](https://linux-hardware.org/?probe=d05269baea) | Aug 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [e5659701d5](https://linux-hardware.org/?probe=e5659701d5) | Jul 26, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b84ef586e7](https://linux-hardware.org/?probe=b84ef586e7) | Jul 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [68cf987c86](https://linux-hardware.org/?probe=68cf987c86) | Jul 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8dc4e130f9](https://linux-hardware.org/?probe=8dc4e130f9) | Jul 25, 2023 |
| HP            | 17-ak041ur                  | Notebook    | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [058672ddad](https://linux-hardware.org/?probe=058672ddad) | Jul 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [757ed62cbc](https://linux-hardware.org/?probe=757ed62cbc) | Jul 14, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [41261aa128](https://linux-hardware.org/?probe=41261aa128) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ab93f5aa6e](https://linux-hardware.org/?probe=ab93f5aa6e) | Jul 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59f9ee3ee8](https://linux-hardware.org/?probe=59f9ee3ee8) | Jul 09, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2ee9eaf9d4](https://linux-hardware.org/?probe=2ee9eaf9d4) | Jul 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a686a6eed6](https://linux-hardware.org/?probe=a686a6eed6) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b7e8961ef5](https://linux-hardware.org/?probe=b7e8961ef5) | Jul 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da271abdd3](https://linux-hardware.org/?probe=da271abdd3) | Jul 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2beb4fa40d](https://linux-hardware.org/?probe=2beb4fa40d) | Jul 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92bf7e658e](https://linux-hardware.org/?probe=92bf7e658e) | Jul 02, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c86548f8aa](https://linux-hardware.org/?probe=c86548f8aa) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [57424619e8](https://linux-hardware.org/?probe=57424619e8) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70ed50862c](https://linux-hardware.org/?probe=70ed50862c) | Jun 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [52b4c086dc](https://linux-hardware.org/?probe=52b4c086dc) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c7e845c965](https://linux-hardware.org/?probe=c7e845c965) | Jun 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f36489e090](https://linux-hardware.org/?probe=f36489e090) | Jun 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d56f78f3ca](https://linux-hardware.org/?probe=d56f78f3ca) | Jun 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cf3b44c0b6](https://linux-hardware.org/?probe=cf3b44c0b6) | Jun 25, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2256046a01](https://linux-hardware.org/?probe=2256046a01) | Jun 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8738063b30](https://linux-hardware.org/?probe=8738063b30) | Jun 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15fb7b8736](https://linux-hardware.org/?probe=15fb7b8736) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a777ee9e06](https://linux-hardware.org/?probe=a777ee9e06) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7b384a40ce](https://linux-hardware.org/?probe=7b384a40ce) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [1243c65107](https://linux-hardware.org/?probe=1243c65107) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15e410d9f7](https://linux-hardware.org/?probe=15e410d9f7) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b1d9682c13](https://linux-hardware.org/?probe=b1d9682c13) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15d9c6fce4](https://linux-hardware.org/?probe=15d9c6fce4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5726f59661](https://linux-hardware.org/?probe=5726f59661) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9cc4cbef4a](https://linux-hardware.org/?probe=9cc4cbef4a) | May 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [40aa9853c4](https://linux-hardware.org/?probe=40aa9853c4) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8d933d6988](https://linux-hardware.org/?probe=8d933d6988) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f074512a99](https://linux-hardware.org/?probe=f074512a99) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [afd35343ad](https://linux-hardware.org/?probe=afd35343ad) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac5899bc10](https://linux-hardware.org/?probe=ac5899bc10) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [55af41b298](https://linux-hardware.org/?probe=55af41b298) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0f5dab42d2](https://linux-hardware.org/?probe=0f5dab42d2) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [028a3c3b0b](https://linux-hardware.org/?probe=028a3c3b0b) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [457abef5d3](https://linux-hardware.org/?probe=457abef5d3) | May 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [31789f9473](https://linux-hardware.org/?probe=31789f9473) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [be2089d630](https://linux-hardware.org/?probe=be2089d630) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9465aab832](https://linux-hardware.org/?probe=9465aab832) | Apr 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6eb92e0ea0](https://linux-hardware.org/?probe=6eb92e0ea0) | Apr 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9dd9a74143](https://linux-hardware.org/?probe=9dd9a74143) | Apr 12, 2023 |
| MSI           | B85-G43                     | Desktop     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac75c58117](https://linux-hardware.org/?probe=ac75c58117) | Apr 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d699519c30](https://linux-hardware.org/?probe=d699519c30) | Apr 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9ef8e7a3d6](https://linux-hardware.org/?probe=9ef8e7a3d6) | Apr 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fbd686e3e2](https://linux-hardware.org/?probe=fbd686e3e2) | Apr 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [61297d4bc4](https://linux-hardware.org/?probe=61297d4bc4) | Apr 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [586decd061](https://linux-hardware.org/?probe=586decd061) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [56d537b480](https://linux-hardware.org/?probe=56d537b480) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0fc5cf1944](https://linux-hardware.org/?probe=0fc5cf1944) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [173e6ad8bf](https://linux-hardware.org/?probe=173e6ad8bf) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [43b58e51b4](https://linux-hardware.org/?probe=43b58e51b4) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6b87ac7144](https://linux-hardware.org/?probe=6b87ac7144) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f98fe964b2](https://linux-hardware.org/?probe=f98fe964b2) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [da9d93a7ea](https://linux-hardware.org/?probe=da9d93a7ea) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [81c9f3a796](https://linux-hardware.org/?probe=81c9f3a796) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ff1f611cc9](https://linux-hardware.org/?probe=ff1f611cc9) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [975790ee68](https://linux-hardware.org/?probe=975790ee68) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3b0e50edda](https://linux-hardware.org/?probe=3b0e50edda) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [126100b078](https://linux-hardware.org/?probe=126100b078) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ecc72101c](https://linux-hardware.org/?probe=6ecc72101c) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cf977da464](https://linux-hardware.org/?probe=cf977da464) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0001e56a68](https://linux-hardware.org/?probe=0001e56a68) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [016e12b43e](https://linux-hardware.org/?probe=016e12b43e) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [4599836936](https://linux-hardware.org/?probe=4599836936) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | 8455                        | Desktop     | [ffc8587d29](https://linux-hardware.org/?probe=ffc8587d29) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [84ba50b16d](https://linux-hardware.org/?probe=84ba50b16d) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ee7dbe4f81](https://linux-hardware.org/?probe=ee7dbe4f81) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| AZW           | SER                         | Mini pc     | [dd0c654d95](https://linux-hardware.org/?probe=dd0c654d95) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a0f53917f9](https://linux-hardware.org/?probe=a0f53917f9) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [04a26e636e](https://linux-hardware.org/?probe=04a26e636e) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5b505d5d7a](https://linux-hardware.org/?probe=5b505d5d7a) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cca8d74416](https://linux-hardware.org/?probe=cca8d74416) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f0884ec1aa](https://linux-hardware.org/?probe=f0884ec1aa) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [89430aeb82](https://linux-hardware.org/?probe=89430aeb82) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6d079ed3ca](https://linux-hardware.org/?probe=6d079ed3ca) | Jan 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d81d33bda5](https://linux-hardware.org/?probe=d81d33bda5) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [091b3e37fb](https://linux-hardware.org/?probe=091b3e37fb) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49654976af](https://linux-hardware.org/?probe=49654976af) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d41a70cbf5](https://linux-hardware.org/?probe=d41a70cbf5) | Jan 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [af868046e3](https://linux-hardware.org/?probe=af868046e3) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7c026252d0](https://linux-hardware.org/?probe=7c026252d0) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [bd3f6fa130](https://linux-hardware.org/?probe=bd3f6fa130) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [477f1a3aad](https://linux-hardware.org/?probe=477f1a3aad) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | Falco                       | Notebook    | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [56758aeb6f](https://linux-hardware.org/?probe=56758aeb6f) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ec3b130618](https://linux-hardware.org/?probe=ec3b130618) | Jan 07, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| HP            | Falco                       | Notebook    | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4571b799f0](https://linux-hardware.org/?probe=4571b799f0) | Dec 20, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | TravelMate 5735Z            | Notebook    | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e56cce9c8](https://linux-hardware.org/?probe=7e56cce9c8) | Sep 17, 2022 |
| HP            | Falco                       | Notebook    | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP            | ENVY dv6                    | Notebook    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google        | Kohaku                      | Notebook    | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google        | Kohaku                      | Notebook    | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Dell          | 060K5C A06                  | Server      | [c8be539d80](https://linux-hardware.org/?probe=c8be539d80) | May 14, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| Dell          | 0R4CNN A02                  | Server      | [c701d3a15f](https://linux-hardware.org/?probe=c701d3a15f) | Feb 07, 2022 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [972f935578](https://linux-hardware.org/?probe=972f935578) | Aug 23, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/AlmaLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| AlmaLinux 9.4  | 28        | 11.91%  |
| AlmaLinux 8.10 | 22        | 9.36%   |
| AlmaLinux 9.1  | 21        | 8.94%   |
| AlmaLinux 9.6  | 20        | 8.51%   |
| AlmaLinux 9.3  | 20        | 8.51%   |
| AlmaLinux 9.2  | 20        | 8.51%   |
| AlmaLinux 9.5  | 19        | 8.09%   |
| AlmaLinux 10.0 | 12        | 5.11%   |
| AlmaLinux 8.8  | 11        | 4.68%   |
| AlmaLinux 8.6  | 11        | 4.68%   |
| AlmaLinux 8.9  | 10        | 4.26%   |
| AlmaLinux 8.7  | 10        | 4.26%   |
| AlmaLinux 9.0  | 9         | 3.83%   |
| AlmaLinux 8.4  | 9         | 3.83%   |
| AlmaLinux 8.3  | 4         | 1.7%    |
| AlmaLinux 10.1 | 4         | 1.7%    |
| AlmaLinux 8.5  | 3         | 1.28%   |
| AlmaLinux 9.7  | 1         | 0.43%   |
| AlmaLinux 10   | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 204       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-362.8.1.el9_3.x86_64   | 8         | 2.9%    |
| 5.14.0-284.30.1.el9_2.x86_64  | 8         | 2.9%    |
| 5.14.0-162.6.1.el9_1.x86_64   | 8         | 2.9%    |
| 4.18.0-553.16.1.el8_10.x86_64 | 8         | 2.9%    |
| 4.18.0-425.3.1.el8.x86_64     | 7         | 2.54%   |
| 5.14.0-162.12.1.el9_1.x86_64  | 6         | 2.17%   |
| 4.18.0-553.22.1.el8_10.x86_64 | 6         | 2.17%   |
| 4.18.0-477.27.2.el8_8.x86_64  | 6         | 2.17%   |
| 5.14.0-362.13.1.el9_3.x86_64  | 5         | 1.81%   |
| 5.14.0-284.25.1.el9_2.x86_64  | 5         | 1.81%   |
| 4.18.0-477.21.1.el8_8.x86_64  | 5         | 1.81%   |
| 5.14.0-570.44.1.el9_6.x86_64  | 4         | 1.45%   |
| 5.14.0-427.37.1.el9_4.x86_64  | 4         | 1.45%   |
| 5.14.0-427.28.1.el9_4.x86_64  | 4         | 1.45%   |
| 4.18.0-513.9.1.el8_9.x86_64   | 4         | 1.45%   |
| 4.18.0-477.13.1.el8_8.x86_64  | 4         | 1.45%   |
| 6.12.0-55.43.1.el10_0.x86_64  | 3         | 1.09%   |
| 6.12.0-124.8.1.el10_1.x86_64  | 3         | 1.09%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 1.09%   |
| 5.14.0-503.40.1.el9_5.x86_64  | 3         | 1.09%   |
| 5.14.0-503.15.1.el9_5.x86_64  | 3         | 1.09%   |
| 5.14.0-427.35.1.el9_4.x86_64  | 3         | 1.09%   |
| 5.14.0-427.22.1.el9_4.x86_64  | 3         | 1.09%   |
| 5.14.0-362.24.2.el9_3.x86_64  | 3         | 1.09%   |
| 5.14.0-362.18.1.el9_3.x86_64  | 3         | 1.09%   |
| 5.14.0-284.18.1.el9_2.x86_64  | 3         | 1.09%   |
| 5.14.0-284.11.1.el9_2.x86_64  | 3         | 1.09%   |
| 5.14.0-162.18.1.el9_1.x86_64  | 3         | 1.09%   |
| 4.18.0-553.89.1.el8_10.x86_64 | 3         | 1.09%   |
| 4.18.0-553.33.1.el8_10.x86_64 | 3         | 1.09%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 1.09%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 1.09%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 0.72%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 0.72%   |
| 5.14.0-570.46.1.el9_6.x86_64  | 2         | 0.72%   |
| 5.14.0-570.22.1.el9_6.x86_64  | 2         | 0.72%   |
| 5.14.0-503.34.1.el9_5.x86_64  | 2         | 0.72%   |
| 5.14.0-503.16.1.el9_5.x86_64  | 2         | 0.72%   |
| 5.14.0-503.11.1.el9_5.x86_64  | 2         | 0.72%   |
| 5.14.0-427.40.1.el9_4.x86_64  | 2         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 117       | 53.92%  |
| 4.18.0  | 61        | 28.11%  |
| 6.12.0  | 16        | 7.37%   |
| 6.9.3   | 1         | 0.46%   |
| 6.9.1   | 1         | 0.46%   |
| 6.8.8   | 1         | 0.46%   |
| 6.8.7   | 1         | 0.46%   |
| 6.6.51  | 1         | 0.46%   |
| 6.6.28  | 1         | 0.46%   |
| 6.4.0   | 1         | 0.46%   |
| 6.3.0   | 1         | 0.46%   |
| 6.15.9  | 1         | 0.46%   |
| 6.15.3  | 1         | 0.46%   |
| 6.13.3  | 1         | 0.46%   |
| 6.12.47 | 1         | 0.46%   |
| 6.12.11 | 1         | 0.46%   |
| 6.11.0  | 1         | 0.46%   |
| 6.1.92  | 1         | 0.46%   |
| 6.1.81  | 1         | 0.46%   |
| 6.1.31  | 1         | 0.46%   |
| 6.1.24  | 1         | 0.46%   |
| 6.1.120 | 1         | 0.46%   |
| 5.4.274 | 1         | 0.46%   |
| 5.4.175 | 1         | 0.46%   |
| 5.15.45 | 1         | 0.46%   |
| 5.10.60 | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 117       | 54.17%  |
| 4.18    | 61        | 28.24%  |
| 6.12    | 18        | 8.33%   |
| 6.1     | 4         | 1.85%   |
| 6.9     | 2         | 0.93%   |
| 6.8     | 2         | 0.93%   |
| 6.6     | 2         | 0.93%   |
| 6.15    | 2         | 0.93%   |
| 5.4     | 2         | 0.93%   |
| 6.4     | 1         | 0.46%   |
| 6.3     | 1         | 0.46%   |
| 6.13    | 1         | 0.46%   |
| 6.11    | 1         | 0.46%   |
| 5.15    | 1         | 0.46%   |
| 5.10    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 200       | 98.04%  |
| aarch64 | 4         | 1.96%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 124       | 59.9%   |
| Unknown         | 37        | 17.87%  |
| KDE5            | 19        | 9.18%   |
| XFCE            | 9         | 4.35%   |
| MATE            | 9         | 4.35%   |
| GNOME Classic   | 4         | 1.93%   |
| KDE6            | 2         | 0.97%   |
| X-Cinnamon      | 1         | 0.48%   |
| GNOME Flashback | 1         | 0.48%   |
| Cinnamon        | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Wayland     | 104       | 48.6%   |
| X11         | 67        | 31.31%  |
| Tty         | 23        | 10.75%  |
| Unknown     | 17        | 7.94%   |
| Unspecified | 2         | 0.93%   |
| Web         | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 59.42%  |
| GDM     | 63        | 30.43%  |
| SDDM    | 11        | 5.31%   |
| LightDM | 10        | 4.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 106       | 50.72%  |
| C       | 17        | 8.13%   |
| de_DE   | 15        | 7.18%   |
| en_GB   | 13        | 6.22%   |
| it_IT   | 8         | 3.83%   |
| pl_PL   | 6         | 2.87%   |
| fr_FR   | 6         | 2.87%   |
| ru_RU   | 5         | 2.39%   |
| pt_BR   | 5         | 2.39%   |
| en_CA   | 4         | 1.91%   |
| Unknown | 4         | 1.91%   |
| en_AU   | 3         | 1.44%   |
| hu_HU   | 2         | 0.96%   |
| fr_CA   | 2         | 0.96%   |
| zh_CN   | 1         | 0.48%   |
| uk_UA   | 1         | 0.48%   |
| ru_UA   | 1         | 0.48%   |
| nl_BE   | 1         | 0.48%   |
| ko_KR   | 1         | 0.48%   |
| ja_JP   | 1         | 0.48%   |
| fr_BE   | 1         | 0.48%   |
| es_VE   | 1         | 0.48%   |
| es_ES   | 1         | 0.48%   |
| en_IN   | 1         | 0.48%   |
| en_IE   | 1         | 0.48%   |
| da_DK   | 1         | 0.48%   |
| bg_BG   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 125       | 59.81%  |
| BIOS | 84        | 40.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 163       | 78.74%  |
| Ext4    | 36        | 17.39%  |
| Tmpfs   | 5         | 2.42%   |
| Overlay | 1         | 0.48%   |
| Ext3    | 1         | 0.48%   |
| Btrfs   | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 94        | 45.19%  |
| Unknown | 85        | 40.87%  |
| MBR     | 29        | 13.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 179       | 87.32%  |
| Yes       | 26        | 12.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 89.71%  |
| Yes       | 21        | 10.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 35        | 17.16%  |
| Hewlett-Packard                      | 32        | 15.69%  |
| Dell                                 | 26        | 12.75%  |
| ASUSTek Computer                     | 18        | 8.82%   |
| Gigabyte Technology                  | 15        | 7.35%   |
| MSI                                  | 13        | 6.37%   |
| Supermicro                           | 10        | 4.9%    |
| Intel                                | 8         | 3.92%   |
| ASRockRack                           | 6         | 2.94%   |
| Acer                                 | 5         | 2.45%   |
| ASRock                               | 4         | 1.96%   |
| Raspberry Pi Foundation              | 3         | 1.47%   |
| Toshiba                              | 2         | 0.98%   |
| Timi                                 | 2         | 0.98%   |
| Optimized Hosting                    | 2         | 0.98%   |
| Google                               | 2         | 0.98%   |
| Apple                                | 2         | 0.98%   |
| Unknown                              | 2         | 0.98%   |
| TUXEDO                               | 1         | 0.49%   |
| Techvision                           | 1         | 0.49%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.49%   |
| Samsung Electronics                  | 1         | 0.49%   |
| Pelco by Schneider Electric          | 1         | 0.49%   |
| Notebook                             | 1         | 0.49%   |
| Microsoft                            | 1         | 0.49%   |
| Medion                               | 1         | 0.49%   |
| Mancer                               | 1         | 0.49%   |
| Maibenben                            | 1         | 0.49%   |
| MACHINIST                            | 1         | 0.49%   |
| IBM                                  | 1         | 0.49%   |
| HUAWEI                               | 1         | 0.49%   |
| Haier                                | 1         | 0.49%   |
| Chuwi                                | 1         | 0.49%   |
| AZW                                  | 1         | 0.49%   |
| AOCWEI                               | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Supermicro Super Server                               | 3         | 1.47%   |
| RPi Raspberry Pi                                      | 3         | 1.47%   |
| HP ProLiant DL360p Gen8                               | 3         | 1.47%   |
| ASRockRack B650D4U-2L2T/BCM                           | 3         | 1.47%   |
| Optimized Hosting KVM                                 | 2         | 0.98%   |
| HP ProDesk 600 G3 DM                                  | 2         | 0.98%   |
| Gigabyte X570S UD                                     | 2         | 0.98%   |
| Unknown                                               | 2         | 0.98%   |
| TUXEDO Aura 15 Gen1                                   | 1         | 0.49%   |
| Toshiba Satellite L50-C                               | 1         | 0.49%   |
| Toshiba Satellite C50-A                               | 1         | 0.49%   |
| Timi TM1709                                           | 1         | 0.49%   |
| Timi RedmiBook 14-APCS                                | 1         | 0.49%   |
| Techvision TVI7309X                                   | 1         | 0.49%   |
| Supermicro X9DR3-F                                    | 1         | 0.49%   |
| Supermicro X8DTT-H                                    | 1         | 0.49%   |
| Supermicro SYS-6018U-TRT+                             | 1         | 0.49%   |
| Supermicro PIO-617R-TLN4F+-ST031                      | 1         | 0.49%   |
| Supermicro motherboard-H12 Series                     | 1         | 0.49%   |
| Supermicro AS -4125GS-TNRT2                           | 1         | 0.49%   |
| Supermicro AS -1115CS-TNR                             | 1         | 0.49%   |
| Shenzhen Meigao Electronic Equipment EliteMini Series | 1         | 0.49%   |
| Samsung R530/R730/P530                                | 1         | 0.49%   |
| Pelco by Schneider Electric E1-MGW-SVRP               | 1         | 0.49%   |
| Notebook NS50_70MU                                    | 1         | 0.49%   |
| MSI MS-7D91                                           | 1         | 0.49%   |
| MSI MS-7D07                                           | 1         | 0.49%   |
| MSI MS-7C95                                           | 1         | 0.49%   |
| MSI MS-7C56                                           | 1         | 0.49%   |
| MSI MS-7C52                                           | 1         | 0.49%   |
| MSI MS-7B89                                           | 1         | 0.49%   |
| MSI MS-7B33                                           | 1         | 0.49%   |
| MSI MS-7A15                                           | 1         | 0.49%   |
| MSI MS-7900                                           | 1         | 0.49%   |
| MSI MS-7816                                           | 1         | 0.49%   |
| MSI MS-7757                                           | 1         | 0.49%   |
| MSI KX624AA-ABZ SR5550IT                              | 1         | 0.49%   |
| MSI GL75 9SE                                          | 1         | 0.49%   |
| Microsoft Surface Go 2                                | 1         | 0.49%   |
| Medion MS-7616                                        | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo ThinkPad                                | 17        | 8.33%   |
| Dell OptiPlex                                  | 5         | 2.45%   |
| Dell Inspiron                                  | 5         | 2.45%   |
| Lenovo IdeaPad                                 | 4         | 1.96%   |
| HP ProLiant                                    | 4         | 1.96%   |
| HP EliteBook                                   | 4         | 1.96%   |
| Dell Precision                                 | 4         | 1.96%   |
| Dell PowerEdge                                 | 4         | 1.96%   |
| Dell Latitude                                  | 4         | 1.96%   |
| ASUS PRIME                                     | 4         | 1.96%   |
| Supermicro Super                               | 3         | 1.47%   |
| RPi Raspberry                                  | 3         | 1.47%   |
| Lenovo Legion                                  | 3         | 1.47%   |
| HP Laptop                                      | 3         | 1.47%   |
| ASRockRack B650D4U-2L2T                        | 3         | 1.47%   |
| Acer Aspire                                    | 3         | 1.47%   |
| Toshiba Satellite                              | 2         | 0.98%   |
| Supermicro AS                                  | 2         | 0.98%   |
| Optimized Hosting KVM                          | 2         | 0.98%   |
| HP ProDesk                                     | 2         | 0.98%   |
| HP ENVY                                        | 2         | 0.98%   |
| Gigabyte X570S                                 | 2         | 0.98%   |
| Dell XPS                                       | 2         | 0.98%   |
| ASUS Pro                                       | 2         | 0.98%   |
| Unknown                                        | 2         | 0.98%   |
| TUXEDO Aura                                    | 1         | 0.49%   |
| Timi TM1709                                    | 1         | 0.49%   |
| Timi RedmiBook                                 | 1         | 0.49%   |
| Techvision TVI7309X                            | 1         | 0.49%   |
| Supermicro X9DR3-F                             | 1         | 0.49%   |
| Supermicro X8DTT-H                             | 1         | 0.49%   |
| Supermicro SYS-6018U-TRT+                      | 1         | 0.49%   |
| Supermicro PIO-617R-TLN4F+-ST031               | 1         | 0.49%   |
| Supermicro motherboard-H12                     | 1         | 0.49%   |
| Shenzhen Meigao Electronic Equipment EliteMini | 1         | 0.49%   |
| Samsung R530                                   | 1         | 0.49%   |
| Pelco by Schneider Electric E1-MGW-SVRP        | 1         | 0.49%   |
| Notebook NS50                                  | 1         | 0.49%   |
| MSI MS-7D91                                    | 1         | 0.49%   |
| MSI MS-7D07                                    | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 32        | 15.69%  |
| 2012    | 19        | 9.31%   |
| 2018    | 17        | 8.33%   |
| 2019    | 16        | 7.84%   |
| 2022    | 15        | 7.35%   |
| 2021    | 13        | 6.37%   |
| 2023    | 12        | 5.88%   |
| 2017    | 11        | 5.39%   |
| 2024    | 10        | 4.9%    |
| 2013    | 10        | 4.9%    |
| 2014    | 8         | 3.92%   |
| 2010    | 8         | 3.92%   |
| 2015    | 7         | 3.43%   |
| 2011    | 7         | 3.43%   |
| 2016    | 6         | 2.94%   |
| 2025    | 4         | 1.96%   |
| 2009    | 3         | 1.47%   |
| 2008    | 3         | 1.47%   |
| Unknown | 3         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 80        | 39.22%  |
| Notebook       | 80        | 39.22%  |
| Server         | 22        | 10.78%  |
| Mini pc        | 12        | 5.88%   |
| Convertible    | 4         | 1.96%   |
| System on chip | 3         | 1.47%   |
| Tablet         | 3         | 1.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 186       | 90.29%  |
| Enabled  | 20        | 9.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 201       | 98.53%  |
| Yes  | 3         | 1.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 50        | 24.39%  |
| 4.01-8.0        | 48        | 23.41%  |
| 64.01-256.0     | 31        | 15.12%  |
| 32.01-64.0      | 22        | 10.73%  |
| 3.01-4.0        | 16        | 7.8%    |
| More than 256.0 | 13        | 6.34%   |
| 24.01-32.0      | 11        | 5.37%   |
| 16.01-24.0      | 10        | 4.88%   |
| 1.01-2.0        | 2         | 0.98%   |
| 0.51-1.0        | 2         | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 52        | 23.11%  |
| 4.01-8.0        | 41        | 18.22%  |
| 3.01-4.0        | 39        | 17.33%  |
| 1.01-2.0        | 36        | 16%     |
| 8.01-16.0       | 17        | 7.56%   |
| 0.51-1.0        | 13        | 5.78%   |
| 64.01-256.0     | 7         | 3.11%   |
| 32.01-64.0      | 6         | 2.67%   |
| More than 256.0 | 4         | 1.78%   |
| 24.01-32.0      | 4         | 1.78%   |
| 16.01-24.0      | 4         | 1.78%   |
| 0.01-0.5        | 2         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 47.6%   |
| 2      | 49        | 23.56%  |
| 3      | 20        | 9.62%   |
| 4      | 12        | 5.77%   |
| 6      | 6         | 2.88%   |
| 5      | 5         | 2.4%    |
| 12     | 2         | 0.96%   |
| 11     | 2         | 0.96%   |
| 10     | 2         | 0.96%   |
| 8      | 2         | 0.96%   |
| 0      | 2         | 0.96%   |
| 35     | 1         | 0.48%   |
| 21     | 1         | 0.48%   |
| 20     | 1         | 0.48%   |
| 18     | 1         | 0.48%   |
| 13     | 1         | 0.48%   |
| 9      | 1         | 0.48%   |
| 7      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 73.3%   |
| Yes       | 55        | 26.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 87.8%   |
| No        | 25        | 12.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 61.76%  |
| No        | 78        | 38.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 51.22%  |
| No        | 100       | 48.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 51        | 25%     |
| Canada       | 17        | 8.33%   |
| Germany      | 16        | 7.84%   |
| Russia       | 12        | 5.88%   |
| France       | 12        | 5.88%   |
| Italy        | 10        | 4.9%    |
| UK           | 8         | 3.92%   |
| Poland       | 7         | 3.43%   |
| Switzerland  | 6         | 2.94%   |
| China        | 6         | 2.94%   |
| Brazil       | 6         | 2.94%   |
| Netherlands  | 4         | 1.96%   |
| Indonesia    | 4         | 1.96%   |
| India        | 4         | 1.96%   |
| Hungary      | 4         | 1.96%   |
| Spain        | 3         | 1.47%   |
| South Africa | 3         | 1.47%   |
| Romania      | 3         | 1.47%   |
| Belgium      | 3         | 1.47%   |
| Australia    | 3         | 1.47%   |
| Ukraine      | 2         | 0.98%   |
| Thailand     | 2         | 0.98%   |
| Sweden       | 2         | 0.98%   |
| South Korea  | 2         | 0.98%   |
| Bulgaria     | 2         | 0.98%   |
| Bangladesh   | 2         | 0.98%   |
| Venezuela    | 1         | 0.49%   |
| Puerto Rico  | 1         | 0.49%   |
| Pakistan     | 1         | 0.49%   |
| Nigeria      | 1         | 0.49%   |
| Mexico       | 1         | 0.49%   |
| Japan        | 1         | 0.49%   |
| Greenland    | 1         | 0.49%   |
| Finland      | 1         | 0.49%   |
| Czechia      | 1         | 0.49%   |
| Austria      | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Hamburg       | 5         | 2.36%   |
| Newmarket     | 4         | 1.89%   |
| Warsaw        | 3         | 1.42%   |
| Moscow        | 3         | 1.42%   |
| Milan         | 3         | 1.42%   |
| Los Angeles   | 3         | 1.42%   |
| Beijing       | 3         | 1.42%   |
| Tunari        | 2         | 0.94%   |
| Tampa         | 2         | 0.94%   |
| Strasbourg    | 2         | 0.94%   |
| St Petersburg | 2         | 0.94%   |
| Sorel-Tracy   | 2         | 0.94%   |
| Saint-Brieuc  | 2         | 0.94%   |
| Queens        | 2         | 0.94%   |
| Montreal      | 2         | 0.94%   |
| Minneapolis   | 2         | 0.94%   |
| Milano        | 2         | 0.94%   |
| Johannesburg  | 2         | 0.94%   |
| Geneva        | 2         | 0.94%   |
| Dresden       | 2         | 0.94%   |
| Dallas        | 2         | 0.94%   |
| Budapest      | 2         | 0.94%   |
| Berlin        | 2         | 0.94%   |
| Bangkok       | 2         | 0.94%   |
| Zurich        | 1         | 0.47%   |
| Zaporizhzhia  | 1         | 0.47%   |
| Zandvoort     | 1         | 0.47%   |
| Yokohama      | 1         | 0.47%   |
| Yekaterinburg | 1         | 0.47%   |
| Winterswijk   | 1         | 0.47%   |
| Wilmington    | 1         | 0.47%   |
| Wejherowo     | 1         | 0.47%   |
| Wandlitz      | 1         | 0.47%   |
| Wallingford   | 1         | 0.47%   |
| Vienna        | 1         | 0.47%   |
| Vicenza       | 1         | 0.47%   |
| Varosfoeld    | 1         | 0.47%   |
| Uppsala       | 1         | 0.47%   |
| Tuusula       | 1         | 0.47%   |
| Trappes       | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 52        | 97     | 15.66%  |
| Samsung Electronics         | 49        | 72     | 14.76%  |
| WDC                         | 37        | 100    | 11.14%  |
| SanDisk                     | 14        | 18     | 4.22%   |
| Kingston                    | 14        | 18     | 4.22%   |
| SK hynix                    | 13        | 15     | 3.92%   |
| Intel                       | 10        | 16     | 3.01%   |
| Micron Technology           | 9         | 16     | 2.71%   |
| Crucial                     | 9         | 17     | 2.71%   |
| Toshiba                     | 8         | 12     | 2.41%   |
| KIOXIA                      | 8         | 12     | 2.41%   |
| Kingston Technology Company | 8         | 70     | 2.41%   |
| HGST                        | 8         | 39     | 2.41%   |
| Hitachi                     | 6         | 10     | 1.81%   |
| Unknown                     | 5         | 10     | 1.51%   |
| Phison Electronics          | 5         | 6      | 1.51%   |
| Hewlett-Packard             | 5         | 24     | 1.51%   |
| Patriot                     | 4         | 6      | 1.2%    |
| Micron/Crucial Technology   | 4         | 13     | 1.2%    |
| Silicon Motion              | 3         | 17     | 0.9%    |
| Netac                       | 3         | 3      | 0.9%    |
| A-DATA Technology           | 3         | 3      | 0.9%    |
| Realtek Semiconductor       | 2         | 2      | 0.6%    |
| QEMU                        | 2         | 4      | 0.6%    |
| Plextor                     | 2         | 2      | 0.6%    |
| Nextorage                   | 2         | 26     | 0.6%    |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.6%    |
| LITEONIT                    | 2         | 6      | 0.6%    |
| LITEON                      | 2         | 2      | 0.6%    |
| Dell                        | 2         | 3      | 0.6%    |
| Apple                       | 2         | 2      | 0.6%    |
| Unknown                     | 2         | 35     | 0.6%    |
| WUXIN                       | 1         | 1      | 0.3%    |
| Union Memory                | 1         | 1      | 0.3%    |
| Transcend                   | 1         | 1      | 0.3%    |
| Team                        | 1         | 1      | 0.3%    |
| T-FORCE                     | 1         | 2      | 0.3%    |
| Supermicro                  | 1         | 2      | 0.3%    |
| SSSTC                       | 1         | 1      | 0.3%    |
| SSK                         | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 9         | 2.29%   |
| SK hynix SC311 SATA 256GB                            | 4         | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 4         | 1.02%   |
| Kingston SA400S37480G 480GB SSD                      | 4         | 1.02%   |
| HP LOGICAL VOLUME 160GB                              | 4         | 1.02%   |
| WDC WD40EFRX-68N32N0 4TB                             | 3         | 0.76%   |
| Kingston SA400S37240G 240GB SSD                      | 3         | 0.76%   |
| Crucial CT240BX500SSD1 240GB                         | 3         | 0.76%   |
| WDC WD40EFAX-68JH4N1 4TB                             | 2         | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB                             | 2         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB                               | 2         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 2         | 0.51%   |
| Unknown SD/MMC/MS PRO 2GB                            | 2         | 0.51%   |
| Seagate ST500DM002-1SB10A 500GB                      | 2         | 0.51%   |
| Seagate ST4000DM000-1F2168 4TB                       | 2         | 0.51%   |
| Seagate ST320LT020-9YG142 320GB                      | 2         | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB                       | 2         | 0.51%   |
| Seagate ST2000DL003-9VT166 2TB                       | 2         | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 2         | 0.51%   |
| Seagate ST10000VN0008-2PJ103 10TB                    | 2         | 0.51%   |
| Seagate Expansion 2TB                                | 2         | 0.51%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 2         | 0.51%   |
| Samsung SSD 980 1TB                                  | 2         | 0.51%   |
| Samsung SSD 870 QVO 1TB                              | 2         | 0.51%   |
| Samsung SSD 870 EVO 500GB                            | 2         | 0.51%   |
| Samsung SSD 870 EVO 1TB                              | 2         | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 2         | 0.51%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB        | 2         | 0.51%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                       | 2         | 0.51%   |
| QEMU HARDDISK                                        | 2         | 0.51%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 2         | 0.51%   |
| Phison E12 NVMe Controller 1TB                       | 2         | 0.51%   |
| KIOXIA KXG8AZNV1T02 LA 1024GB                        | 2         | 0.51%   |
| Kingston Company SNV2S1000G 1TB                      | 2         | 0.51%   |
| Kingston Company KC2000 NVMe SSD 250GB               | 2         | 0.51%   |
| Kingston Company A2000 NVMe SSD 250GB                | 2         | 0.51%   |
| Hitachi HTS543232A7A384 320GB                        | 2         | 0.51%   |
| HGST HTS541010A9E680 1TB                             | 2         | 0.51%   |
| Unknown                                              | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 81     | 42.02%  |
| WDC                 | 34        | 87     | 28.57%  |
| Toshiba             | 8         | 12     | 6.72%   |
| HGST                | 8         | 37     | 6.72%   |
| Hitachi             | 6         | 10     | 5.04%   |
| Hewlett-Packard     | 4         | 23     | 3.36%   |
| Unknown             | 2         | 3      | 1.68%   |
| QEMU                | 2         | 4      | 1.68%   |
| T-FORCE             | 1         | 2      | 0.84%   |
| Samsung Electronics | 1         | 1      | 0.84%   |
| DELLBOSS            | 1         | 1      | 0.84%   |
| ASMT                | 1         | 2      | 0.84%   |
| Apple               | 1         | 1      | 0.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 25     | 18.28%  |
| Kingston            | 10        | 11     | 10.75%  |
| Crucial             | 8         | 15     | 8.6%    |
| SK hynix            | 6         | 8      | 6.45%   |
| SanDisk             | 5         | 6      | 5.38%   |
| Micron Technology   | 5         | 11     | 5.38%   |
| Intel               | 5         | 9      | 5.38%   |
| WDC                 | 4         | 11     | 4.3%    |
| Patriot             | 4         | 6      | 4.3%    |
| A-DATA Technology   | 3         | 3      | 3.23%   |
| Plextor             | 2         | 2      | 2.15%   |
| Netac               | 2         | 2      | 2.15%   |
| LITEONIT            | 2         | 6      | 2.15%   |
| LITEON              | 2         | 2      | 2.15%   |
| WUXIN               | 1         | 1      | 1.08%   |
| Team                | 1         | 1      | 1.08%   |
| Supermicro          | 1         | 2      | 1.08%   |
| SPCC                | 1         | 1      | 1.08%   |
| SATA SSD            | 1         | 1      | 1.08%   |
| Rayson              | 1         | 1      | 1.08%   |
| Mushkin             | 1         | 1      | 1.08%   |
| MidasForce          | 1         | 3      | 1.08%   |
| KingSpec            | 1         | 2      | 1.08%   |
| Intenso             | 1         | 1      | 1.08%   |
| IBM-207x            | 1         | 3      | 1.08%   |
| HJDK                | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 1      | 1.08%   |
| EVM                 | 1         | 7      | 1.08%   |
| Dell                | 1         | 2      | 1.08%   |
| Corsair             | 1         | 1      | 1.08%   |
| China               | 1         | 1      | 1.08%   |
| 2TB                 | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 103       | 325    | 35.4%   |
| HDD     | 96        | 264    | 32.99%  |
| SSD     | 82        | 148    | 28.18%  |
| Unknown | 7         | 10     | 2.41%   |
| MMC     | 3         | 7      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 141       | 371    | 53.41%  |
| NVMe | 103       | 323    | 39.02%  |
| SAS  | 17        | 53     | 6.44%   |
| MMC  | 3         | 7      | 1.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 153    | 45.1%   |
| 0.51-1.0   | 56        | 104    | 27.45%  |
| 1.01-2.0   | 21        | 31     | 10.29%  |
| 3.01-4.0   | 16        | 47     | 7.84%   |
| 4.01-10.0  | 11        | 30     | 5.39%   |
| 2.01-3.0   | 4         | 10     | 1.96%   |
| 10.01-20.0 | 3         | 33     | 1.47%   |
| 20.01-50.0 | 1         | 4      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 55        | 26.07%  |
| 501-1000       | 39        | 18.48%  |
| 251-500        | 37        | 17.54%  |
| More than 3000 | 21        | 9.95%   |
| 1001-2000      | 21        | 9.95%   |
| Unknown        | 11        | 5.21%   |
| 51-100         | 10        | 4.74%   |
| 2001-3000      | 6         | 2.84%   |
| 1-20           | 6         | 2.84%   |
| 21-50          | 5         | 2.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 33.03%  |
| 21-50          | 46        | 20.81%  |
| 101-250        | 29        | 13.12%  |
| 51-100         | 21        | 9.5%    |
| 251-500        | 17        | 7.69%   |
| Unknown        | 11        | 4.98%   |
| More than 3000 | 10        | 4.52%   |
| 501-1000       | 7         | 3.17%   |
| 1001-2000      | 5         | 2.26%   |
| 2001-3000      | 2         | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB                                    | 1         | 1      | 4.76%   |
| WDC WD2502ABYS-02B7A0 256GB                                   | 1         | 3      | 4.76%   |
| WDC WD20EFRX-68EUZN0 2TB                                      | 1         | 1      | 4.76%   |
| WDC WD20EARS-00J2GB0 2TB                                      | 1         | 1      | 4.76%   |
| WDC WD1003FBYX-01Y7B0 1TB                                     | 1         | 1      | 4.76%   |
| Supermicro SSD 128GB                                          | 1         | 2      | 4.76%   |
| SK hynix SH920 2.5 7MM 256GB SSD                              | 1         | 1      | 4.76%   |
| Seagate ST4000DM000-1F2168 4TB                                | 1         | 1      | 4.76%   |
| Seagate ST2000DL003-9VT166 2TB                                | 1         | 1      | 4.76%   |
| Seagate ST12000VN0007-2GS116 12TB                             | 1         | 1      | 4.76%   |
| Seagate ST1000DM010-2EP102 1TB                                | 1         | 2      | 4.76%   |
| Seagate ST10000VN0004-2GS11L 10TB                             | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 980 500GB                             | 1         | 1      | 4.76%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1      | 4.76%   |
| Samsung Electronics HD642JJ 640GB                             | 1         | 1      | 4.76%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                                | 1         | 5      | 4.76%   |
| Kingston SUV400S37240G 240GB SSD                              | 1         | 1      | 4.76%   |
| Hitachi HTS545050B9A300 500GB                                 | 1         | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB                                 | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                                    | 1         | 1      | 4.76%   |
| HGST HTS541010A9E680 1TB                                      | 1         | 2      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 7      | 25%     |
| Seagate             | 4         | 6      | 20%     |
| Samsung Electronics | 3         | 3      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| HGST                | 2         | 3      | 10%     |
| Supermicro          | 1         | 2      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| LITEONIT            | 1         | 5      | 5%      |
| Kingston            | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 7      | 35.71%  |
| Seagate             | 4         | 6      | 28.57%  |
| Hitachi             | 2         | 2      | 14.29%  |
| HGST                | 2         | 3      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 19     | 68.42%  |
| SSD  | 4         | 9      | 21.05%  |
| NVMe | 2         | 2      | 10.53%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                             | Computers | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| Kingston Technology Company KC2000 NVMe SSD 250GB | 1         | 10     | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Kingston Technology Company | 1         | 10     | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 110       | 428    | 47.01%  |
| Detected | 106       | 286    | 45.3%   |
| Malfunc  | 17        | 30     | 7.26%   |
| Failed   | 1         | 10     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 124       | 39.62%  |
| AMD                            | 47        | 15.02%  |
| Samsung Electronics            | 32        | 10.22%  |
| Kingston Technology Company    | 14        | 4.47%   |
| Sandisk                        | 10        | 3.19%   |
| ASMedia Technology             | 10        | 3.19%   |
| Broadcom / LSI                 | 8         | 2.56%   |
| KIOXIA                         | 7         | 2.24%   |
| SK hynix                       | 6         | 1.92%   |
| Phison Electronics             | 6         | 1.92%   |
| LSI Logic / Symbios Logic      | 6         | 1.92%   |
| Micron/Crucial Technology      | 5         | 1.6%    |
| Silicon Motion                 | 4         | 1.28%   |
| Seagate Technology             | 4         | 1.28%   |
| Micron Technology              | 4         | 1.28%   |
| Hewlett-Packard                | 4         | 1.28%   |
| Marvell Technology Group       | 3         | 0.96%   |
| Union Memory (Shenzhen)        | 2         | 0.64%   |
| Red Hat                        | 2         | 0.64%   |
| Realtek Semiconductor          | 2         | 0.64%   |
| Nextorage                      | 2         | 0.64%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.64%   |
| Toshiba America Info Systems   | 1         | 0.32%   |
| Solid State Storage Technology | 1         | 0.32%   |
| Shenzhen Longsys Electronics   | 1         | 0.32%   |
| Netac Technology               | 1         | 0.32%   |
| Lite-On Technology             | 1         | 0.32%   |
| Lenovo                         | 1         | 0.32%   |
| Apple                          | 1         | 0.32%   |
| ADATA Technology               | 1         | 0.32%   |
| 3ware                          | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 9.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 3.13%   |
| Intel SATA Controller [RAID mode]                                              | 11        | 3.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 1.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 1.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.7%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6         | 1.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 1.42%   |
| AMD 600 Series Chipset SATA Controller                                         | 5         | 1.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.14%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 4         | 1.14%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 4         | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.14%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 0.85%   |
| Seagate E18 PCIe SSD                                                           | 3         | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.85%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.85%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 3         | 0.85%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 3         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.85%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 3         | 0.85%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 3         | 0.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3         | 0.85%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 3         | 0.85%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.85%   |
| HP Smart Array Gen8 Controllers                                                | 3         | 0.85%   |
| ASMedia ASM1166 Serial ATA Controller                                          | 3         | 0.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 143       | 46.89%  |
| NVMe | 102       | 33.44%  |
| RAID | 32        | 10.49%  |
| IDE  | 14        | 4.59%   |
| SAS  | 12        | 3.93%   |
| SCSI | 2         | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 142       | 69.61%  |
| AMD    | 58        | 28.43%  |
| ARM    | 4         | 1.96%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.95%   |
| ARM Processor                           | 4         | 1.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.46%   |
| Intel Core i5-6500T CPU @ 2.50GHz       | 3         | 1.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 1.46%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 2         | 0.98%   |
| Intel N100                              | 2         | 0.98%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 2         | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 0.98%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 2         | 0.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.98%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.98%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 0.98%   |
| Intel 12th Gen Core i3-1215U            | 2         | 0.98%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 0.98%   |
| AMD Ryzen 5 3500X 6-Core Processor      | 2         | 0.98%   |
| AMD Ryzen 3 5300G with Radeon Graphics  | 2         | 0.98%   |
| AMD EPYC-Rome Processor                 | 2         | 0.98%   |
| AMD EPYC 7282 16-Core Processor         | 2         | 0.98%   |
| Intel Xeon W-2223 CPU @ 3.60GHz         | 1         | 0.49%   |
| Intel Xeon W-1350 @ 3.30GHz             | 1         | 0.49%   |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 0.49%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz    | 1         | 0.49%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 0.49%   |
| Intel Xeon Gold 6338N CPU @ 2.20GHz     | 1         | 0.49%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz     | 1         | 0.49%   |
| Intel Xeon E-2144G CPU @ 3.60GHz        | 1         | 0.49%   |
| Intel Xeon CPU X5550 @ 2.67GHz          | 1         | 0.49%   |
| Intel Xeon CPU L5520 @ 2.27GHz          | 1         | 0.49%   |
| Intel Xeon CPU E5540 @ 2.53GHz          | 1         | 0.49%   |
| Intel Xeon CPU E5-4657L v2 @ 2.40GHz    | 1         | 0.49%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1         | 0.49%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz      | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 17.16%  |
| Intel Core i7           | 29        | 14.22%  |
| Other                   | 28        | 13.73%  |
| Intel Xeon              | 23        | 11.27%  |
| AMD Ryzen 5             | 14        | 6.86%   |
| Intel Core i3           | 12        | 5.88%   |
| AMD EPYC                | 10        | 4.9%    |
| AMD Ryzen 9             | 7         | 3.43%   |
| AMD Ryzen 7             | 7         | 3.43%   |
| Intel Celeron           | 6         | 2.94%   |
| AMD Ryzen Threadripper  | 5         | 2.45%   |
| Intel Pentium           | 4         | 1.96%   |
| AMD Ryzen 3             | 3         | 1.47%   |
| Intel Xeon Silver       | 2         | 0.98%   |
| Intel Xeon Gold         | 2         | 0.98%   |
| Intel Core 2 Quad       | 2         | 0.98%   |
| Intel Atom              | 2         | 0.98%   |
| AMD FX                  | 2         | 0.98%   |
| AMD A12                 | 2         | 0.98%   |
| AMD A10                 | 2         | 0.98%   |
| Intel Pentium Dual-Core | 1         | 0.49%   |
| Intel Core 2 Duo        | 1         | 0.49%   |
| Intel Core              | 1         | 0.49%   |
| AMD Ryzen 7 PRO         | 1         | 0.49%   |
| AMD E2                  | 1         | 0.49%   |
| AMD A8                  | 1         | 0.49%   |
| AMD A6                  | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 69        | 33.66%  |
| 2       | 47        | 22.93%  |
| 6       | 24        | 11.71%  |
| 8       | 14        | 6.83%   |
| 16      | 12        | 5.85%   |
| 12      | 7         | 3.41%   |
| 32      | 6         | 2.93%   |
| 20      | 4         | 1.95%   |
| 48      | 3         | 1.46%   |
| 24      | 3         | 1.46%   |
| 14      | 3         | 1.46%   |
| 10      | 3         | 1.46%   |
| Unknown | 3         | 1.46%   |
| 64      | 2         | 0.98%   |
| 1       | 2         | 0.98%   |
| 192     | 1         | 0.49%   |
| 80      | 1         | 0.49%   |
| 28      | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 181       | 88.73%  |
| 2       | 17        | 8.33%   |
| 4       | 3         | 1.47%   |
| Unknown | 3         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 159       | 77.94%  |
| 1       | 42        | 20.59%  |
| Unknown | 3         | 1.47%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 98.54%  |
| Unknown        | 3         | 1.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 119       | 55.09%  |
| 0x306a9    | 6         | 2.78%   |
| 0x08701021 | 5         | 2.31%   |
| 0x806ec    | 4         | 1.85%   |
| 0x806c1    | 4         | 1.85%   |
| 0xa0671    | 3         | 1.39%   |
| 0x40651    | 3         | 1.39%   |
| 0x306c3    | 3         | 1.39%   |
| 0x206a7    | 3         | 1.39%   |
| 0x106a5    | 3         | 1.39%   |
| 0x906ea    | 2         | 0.93%   |
| 0x806ea    | 2         | 0.93%   |
| 0x806e9    | 2         | 0.93%   |
| 0x806d1    | 2         | 0.93%   |
| 0x50657    | 2         | 0.93%   |
| 0x406e3    | 2         | 0.93%   |
| 0x306e4    | 2         | 0.93%   |
| 0x0a50000d | 2         | 0.93%   |
| 0x0a101148 | 2         | 0.93%   |
| 0x08600106 | 2         | 0.93%   |
| 0x0830107a | 2         | 0.93%   |
| 0x08301055 | 2         | 0.93%   |
| 0x08108109 | 2         | 0.93%   |
| 0x0600611a | 2         | 0.93%   |
| 0x06000852 | 2         | 0.93%   |
| 0xb06a3    | 1         | 0.46%   |
| 0xa0655    | 1         | 0.46%   |
| 0xa0652    | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x906e9    | 1         | 0.46%   |
| 0x906a4    | 1         | 0.46%   |
| 0x506e3    | 1         | 0.46%   |
| 0x50654    | 1         | 0.46%   |
| 0x406c4    | 1         | 0.46%   |
| 0x306d4    | 1         | 0.46%   |
| 0x30678    | 1         | 0.46%   |
| 0x30673    | 1         | 0.46%   |
| 0x30661    | 1         | 0.46%   |
| 0x206d7    | 1         | 0.46%   |
| 0x20655    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 14.71%  |
| Unknown          | 23        | 11.27%  |
| Zen 2            | 18        | 8.82%   |
| IvyBridge        | 17        | 8.33%   |
| Skylake          | 14        | 6.86%   |
| Haswell          | 12        | 5.88%   |
| Zen 3            | 8         | 3.92%   |
| TigerLake        | 8         | 3.92%   |
| SandyBridge      | 8         | 3.92%   |
| Icelake          | 8         | 3.92%   |
| Alderlake Hybrid | 7         | 3.43%   |
| Nehalem          | 6         | 2.94%   |
| Excavator        | 6         | 2.94%   |
| Zen+             | 5         | 2.45%   |
| Silvermont       | 5         | 2.45%   |
| Broadwell        | 5         | 2.45%   |
| Westmere         | 4         | 1.96%   |
| CometLake        | 4         | 1.96%   |
| Zen              | 3         | 1.47%   |
| Penryn           | 3         | 1.47%   |
| Piledriver       | 2         | 0.98%   |
| Bonnell          | 2         | 0.98%   |
| Tremont          | 1         | 0.49%   |
| Steamroller      | 1         | 0.49%   |
| Jaguar           | 1         | 0.49%   |
| Gracemont        | 1         | 0.49%   |
| Goldmont plus    | 1         | 0.49%   |
| Core             | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 100       | 43.1%   |
| Nvidia                     | 58        | 25%     |
| AMD                        | 44        | 18.97%  |
| ASPEED Technology          | 16        | 6.9%    |
| Matrox Electronics Systems | 12        | 5.17%   |
| Technical                  | 1         | 0.43%   |
| Red Hat                    | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 6.84%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 7         | 2.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.56%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 5         | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.14%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.28%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 1.28%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 3         | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.28%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.28%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.85%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.85%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.85%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 2         | 0.85%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.85%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2         | 0.85%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 2         | 0.85%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.85%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2         | 0.85%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 2         | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.85%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 2         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 78        | 38.24%  |
| 1 x Nvidia      | 34        | 16.67%  |
| 1 x AMD         | 32        | 15.69%  |
| Intel + Nvidia  | 17        | 8.33%   |
| 1 x Matrox      | 11        | 5.39%   |
| 1 x ASPEED      | 11        | 5.39%   |
| Intel + AMD     | 4         | 1.96%   |
| Other           | 3         | 1.47%   |
| AMD + Nvidia    | 3         | 1.47%   |
| AMD + ASPEED    | 3         | 1.47%   |
| 2 x AMD         | 2         | 0.98%   |
| 2 x Nvidia      | 1         | 0.49%   |
| 1 x Technical   | 1         | 0.49%   |
| 1 x Red Hat     | 1         | 0.49%   |
| Nvidia + Matrox | 1         | 0.49%   |
| Nvidia + ASPEED | 1         | 0.49%   |
| Intel + ASPEED  | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 166       | 79.81%  |
| Unknown     | 22        | 10.58%  |
| Proprietary | 20        | 9.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 142       | 67.94%  |
| 0.01-0.5   | 18        | 8.61%   |
| 1.01-2.0   | 15        | 7.18%   |
| 0.51-1.0   | 10        | 4.78%   |
| 3.01-4.0   | 8         | 3.83%   |
| 5.01-6.0   | 7         | 3.35%   |
| 7.01-8.0   | 6         | 2.87%   |
| 32.01-64.0 | 1         | 0.48%   |
| 4.01-5.0   | 1         | 0.48%   |
| 16.01-24.0 | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 18        | 10.23%  |
| AU Optronics            | 17        | 9.66%   |
| Samsung Electronics     | 15        | 8.52%   |
| Dell                    | 15        | 8.52%   |
| LG Display              | 14        | 7.95%   |
| Goldstar                | 11        | 6.25%   |
| Chimei Innolux          | 10        | 5.68%   |
| Lenovo                  | 7         | 3.98%   |
| BenQ                    | 6         | 3.41%   |
| Philips                 | 5         | 2.84%   |
| PANDA                   | 5         | 2.84%   |
| Eizo                    | 5         | 2.84%   |
| InfoVision              | 4         | 2.27%   |
| Acer                    | 4         | 2.27%   |
| Sharp                   | 3         | 1.7%    |
| Chi Mei Optoelectronics | 3         | 1.7%    |
| AOC                     | 3         | 1.7%    |
| Ancor Communications    | 3         | 1.7%    |
| ___                     | 2         | 1.14%   |
| ViewSonic               | 2         | 1.14%   |
| Sony                    | 2         | 1.14%   |
| Panasonic               | 2         | 1.14%   |
| Iiyama                  | 2         | 1.14%   |
| HannStar                | 2         | 1.14%   |
| Vizio                   | 1         | 0.57%   |
| Unknown                 | 1         | 0.57%   |
| TopView                 | 1         | 0.57%   |
| STD                     | 1         | 0.57%   |
| Seiki                   | 1         | 0.57%   |
| RPL                     | 1         | 0.57%   |
| RHT                     | 1         | 0.57%   |
| NEC Computers           | 1         | 0.57%   |
| MiTAC                   | 1         | 0.57%   |
| Medion                  | 1         | 0.57%   |
| Hewlett-Packard         | 1         | 0.57%   |
| CZZ                     | 1         | 0.57%   |
| CSOT                    | 1         | 0.57%   |
| CHD                     | 1         | 0.57%   |
| BOE Technology Group    | 1         | 0.57%   |
| ASUSTek Computer        | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 1.67%   |
| ___ LCD TV ___9000 1360x768                                           | 2         | 1.11%   |
| Sony TV *00 SNYF503 1920x1080 1085x610mm 49.0-inch                    | 2         | 1.11%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.11%   |
| BenQ BL902 BNQ8008 1280x1024 376x301mm 19.0-inch                      | 2         | 1.11%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.11%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.11%   |
| Vizio E190VA VIZ0067 1920x1080 410x230mm 18.5-inch                    | 1         | 0.56%   |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch            | 1         | 0.56%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch         | 1         | 0.56%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.56%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                   | 1         | 0.56%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 0.56%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.56%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch               | 1         | 0.56%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                   | 1         | 0.56%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch     | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch  | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1         | 0.56%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 0.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4164 3840x2400 344x215mm 16.0-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 890x500mm 40.2-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor S32B80P                               | 1         | 0.56%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.56%   |
| RPL RPI MON156 RPL0100 1920x1080 350x190mm 15.7-inch                  | 1         | 0.56%   |
| RHT QEMU Monitor RHT1234 2048x1152 325x203mm 15.1-inch                | 1         | 0.56%   |
| Philips PHL 272B7QU PHL0926 2560x1440 597x336mm 27.0-inch             | 1         | 0.56%   |
| Philips PHL 271V8LB PHLC308 1920x1080 597x336mm 27.0-inch             | 1         | 0.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.56%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 51.45%  |
| 1366x768 (WXGA)    | 19        | 10.98%  |
| 3840x2160 (4K)     | 12        | 6.94%   |
| 1280x1024 (SXGA)   | 9         | 5.2%    |
| 1920x1200 (WUXGA)  | 7         | 4.05%   |
| 2560x1440 (QHD)    | 6         | 3.47%   |
| 1600x900 (HD+)     | 4         | 2.31%   |
| 2560x1600          | 3         | 1.73%   |
| 1680x1050 (WSXGA+) | 3         | 1.73%   |
| 3200x1800 (QHD+)   | 2         | 1.16%   |
| 1440x900 (WXGA+)   | 2         | 1.16%   |
| 1280x720 (HD)      | 2         | 1.16%   |
| 5760x2160          | 1         | 0.58%   |
| 3840x2400          | 1         | 0.58%   |
| 3840x1100          | 1         | 0.58%   |
| 3440x1440          | 1         | 0.58%   |
| 2736x1824          | 1         | 0.58%   |
| 2560x1397          | 1         | 0.58%   |
| 2560x1080          | 1         | 0.58%   |
| 2288x1287          | 1         | 0.58%   |
| 2160x1350          | 1         | 0.58%   |
| 1920x540           | 1         | 0.58%   |
| 1920x1280          | 1         | 0.58%   |
| 1600x1200          | 1         | 0.58%   |
| 1400x1050          | 1         | 0.58%   |
| 1280x800 (WXGA)    | 1         | 0.58%   |
| Unknown            | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 18.18%  |
| 13      | 17        | 9.66%   |
| 31      | 14        | 7.95%   |
| 17      | 14        | 7.95%   |
| 14      | 14        | 7.95%   |
| 27      | 12        | 6.82%   |
| 24      | 12        | 6.82%   |
| 23      | 10        | 5.68%   |
| 19      | 9         | 5.11%   |
| 21      | 8         | 4.55%   |
| Unknown | 6         | 3.41%   |
| 16      | 5         | 2.84%   |
| 11      | 3         | 1.7%    |
| 65      | 2         | 1.14%   |
| 34      | 2         | 1.14%   |
| 29      | 2         | 1.14%   |
| 20      | 2         | 1.14%   |
| 18      | 2         | 1.14%   |
| 12      | 2         | 1.14%   |
| 142     | 1         | 0.57%   |
| 84      | 1         | 0.57%   |
| 64      | 1         | 0.57%   |
| 40      | 1         | 0.57%   |
| 36      | 1         | 0.57%   |
| 32      | 1         | 0.57%   |
| 22      | 1         | 0.57%   |
| 10      | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 60        | 34.68%  |
| 501-600        | 31        | 17.92%  |
| 351-400        | 21        | 12.14%  |
| 601-700        | 16        | 9.25%   |
| 401-500        | 15        | 8.67%   |
| 201-300        | 14        | 8.09%   |
| Unknown        | 6         | 3.47%   |
| 701-800        | 4         | 2.31%   |
| 1001-1500      | 3         | 1.73%   |
| More than 2000 | 1         | 0.58%   |
| 801-900        | 1         | 0.58%   |
| 1501-2000      | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 128       | 76.65%  |
| 16/10   | 15        | 8.98%   |
| 5/4     | 9         | 5.39%   |
| 3/2     | 4         | 2.4%    |
| Unknown | 4         | 2.4%    |
| 4/3     | 2         | 1.2%    |
| 21/9    | 2         | 1.2%    |
| 6/5     | 1         | 0.6%    |
| 3.40    | 1         | 0.6%    |
| 1.00    | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 18.18%  |
| 201-250        | 27        | 15.34%  |
| 81-90          | 22        | 12.5%   |
| 351-500        | 19        | 10.8%   |
| 151-200        | 15        | 8.52%   |
| 301-350        | 12        | 6.82%   |
| 121-130        | 9         | 5.11%   |
| 71-80          | 8         | 4.55%   |
| Unknown        | 6         | 3.41%   |
| More than 1000 | 5         | 2.84%   |
| 51-60          | 5         | 2.84%   |
| 111-120        | 5         | 2.84%   |
| 131-140        | 3         | 1.7%    |
| 61-70          | 2         | 1.14%   |
| 251-300        | 2         | 1.14%   |
| 141-150        | 2         | 1.14%   |
| 501-1000       | 2         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 58        | 34.12%  |
| 121-160       | 54        | 31.76%  |
| 101-120       | 30        | 17.65%  |
| 161-240       | 10        | 5.88%   |
| More than 240 | 7         | 4.12%   |
| Unknown       | 6         | 3.53%   |
| 1-50          | 5         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 143       | 69.08%  |
| 0     | 44        | 21.26%  |
| 2     | 19        | 9.18%   |
| 3     | 1         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 37.1%   |
| Realtek Semiconductor           | 84        | 27.1%   |
| Qualcomm Atheros                | 25        | 8.06%   |
| Broadcom                        | 21        | 6.77%   |
| TP-Link                         | 9         | 2.9%    |
| Mellanox Technologies           | 7         | 2.26%   |
| Broadcom Limited                | 7         | 2.26%   |
| American Megatrends             | 7         | 2.26%   |
| Ralink Technology               | 5         | 1.61%   |
| Insyde Software                 | 4         | 1.29%   |
| MediaTek                        | 3         | 0.97%   |
| Samsung Electronics             | 2         | 0.65%   |
| Microchip Technology            | 2         | 0.65%   |
| Marvell Technology Group        | 2         | 0.65%   |
| Emulex                          | 2         | 0.65%   |
| Sigma Designs                   | 1         | 0.32%   |
| Sierra Wireless                 | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Qualcomm Technologies           | 1         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.32%   |
| Qualcomm                        | 1         | 0.32%   |
| NetGear                         | 1         | 0.32%   |
| Lenovo                          | 1         | 0.32%   |
| IBM                             | 1         | 0.32%   |
| Dell                            | 1         | 0.32%   |
| Cypress Semiconductor           | 1         | 0.32%   |
| Chelsio Communications          | 1         | 0.32%   |
| ASIX Electronics                | 1         | 0.32%   |
| Aquantia                        | 1         | 0.32%   |
| 3Com                            | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 55        | 14.25%  |
| Intel Wi-Fi 6 AX200                                                    | 9         | 2.33%   |
| Intel I350 Gigabit Network Connection                                  | 9         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.07%   |
| Intel Wireless 8265 / 8275                                             | 8         | 2.07%   |
| Intel I210 Gigabit Network Connection                                  | 8         | 2.07%   |
| Intel Ethernet Controller X550                                         | 8         | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.81%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 1.81%   |
| American Megatrends Virtual Ethernet.                                  | 7         | 1.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.3%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 5         | 1.3%    |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 5         | 1.3%    |
| Intel Wireless 7265                                                    | 4         | 1.04%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.04%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.04%   |
| Insyde Software RNDIS/Ethernet Gadget                                  | 4         | 1.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 4         | 1.04%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 3         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.78%   |
| Intel Wireless 8260                                                    | 3         | 0.78%   |
| Intel Wireless 7260                                                    | 3         | 0.78%   |
| Intel Wireless 3165                                                    | 3         | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.78%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 3         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.78%   |
| Intel Ethernet Connection (14) I219-LM                                 | 3         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.78%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 47.37%  |
| Realtek Semiconductor           | 21        | 15.79%  |
| Qualcomm Atheros                | 21        | 15.79%  |
| TP-Link                         | 7         | 5.26%   |
| Ralink Technology               | 5         | 3.76%   |
| Broadcom                        | 5         | 3.76%   |
| Broadcom Limited                | 3         | 2.26%   |
| MediaTek                        | 2         | 1.5%    |
| Sierra Wireless                 | 1         | 0.75%   |
| Ralink                          | 1         | 0.75%   |
| Qualcomm Technologies           | 1         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.75%   |
| Qualcomm                        | 1         | 0.75%   |
| NetGear                         | 1         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                         | 9         | 6.77%   |
| Intel Wireless 8265 / 8275                                  | 8         | 6.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 7         | 5.26%   |
| Intel Wi-Fi 6 AX201                                         | 7         | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 5         | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 5         | 3.76%   |
| Intel Wireless 7265                                         | 4         | 3.01%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                         | 3         | 2.26%   |
| Ralink MT7601U Wireless Adapter                             | 3         | 2.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 3         | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 3         | 2.26%   |
| Intel Wireless 8260                                         | 3         | 2.26%   |
| Intel Wireless 7260                                         | 3         | 2.26%   |
| Intel Wireless 3165                                         | 3         | 2.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 3         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 3         | 2.26%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 2         | 1.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 2         | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 2         | 1.5%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter         | 2         | 1.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 2         | 1.5%    |
| Intel Raptor Lake PCH CNVi WiFi                             | 2         | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                              | 2         | 1.5%    |
| Intel Centrino Ultimate-N 6300                              | 2         | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                             | 2         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                               | 2         | 1.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                | 1         | 0.75%   |
| TP-Link Archer T4U ver.3                                    | 1         | 0.75%   |
| Sierra Wireless EM7345 4G LTE                               | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                          | 1         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter    | 1         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 1         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 1         | 0.75%   |
| Realtek 802.11ax WLAN Adapter                               | 1         | 0.75%   |
| Ralink RT5572 Wireless Adapter                              | 1         | 0.75%   |
| Ralink RT3572 Wireless Adapter                              | 1         | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                   | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 79        | 36.07%  |
| Realtek Semiconductor    | 78        | 35.62%  |
| Broadcom                 | 17        | 7.76%   |
| American Megatrends      | 7         | 3.2%    |
| Qualcomm Atheros         | 6         | 2.74%   |
| Mellanox Technologies    | 6         | 2.74%   |
| Insyde Software          | 4         | 1.83%   |
| Broadcom Limited         | 4         | 1.83%   |
| TP-Link                  | 2         | 0.91%   |
| Samsung Electronics      | 2         | 0.91%   |
| Microchip Technology     | 2         | 0.91%   |
| Marvell Technology Group | 2         | 0.91%   |
| Emulex                   | 2         | 0.91%   |
| MediaTek                 | 1         | 0.46%   |
| Lenovo                   | 1         | 0.46%   |
| IBM                      | 1         | 0.46%   |
| Dell                     | 1         | 0.46%   |
| Chelsio Communications   | 1         | 0.46%   |
| ASIX Electronics         | 1         | 0.46%   |
| Aquantia                 | 1         | 0.46%   |
| 3Com                     | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 55        | 22%     |
| Intel I350 Gigabit Network Connection                                  | 9         | 3.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 3.2%    |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 3.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 3.2%    |
| Intel I210 Gigabit Network Connection                                  | 8         | 3.2%    |
| Intel Ethernet Controller X550                                         | 8         | 3.2%    |
| American Megatrends Virtual Ethernet.                                  | 7         | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.4%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 5         | 2%      |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 5         | 2%      |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.6%    |
| Intel Ethernet Controller I225-V                                       | 4         | 1.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.6%    |
| Insyde Software RNDIS/Ethernet Gadget                                  | 4         | 1.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 4         | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 1.2%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 3         | 1.2%    |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.2%    |
| Intel Ethernet Connection (14) I219-LM                                 | 3         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.2%    |
| Intel 82574L Gigabit Network Connection                                | 3         | 1.2%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 3         | 1.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.8%    |
| Microchip LAN7800                                                      | 2         | 0.8%    |
| Mellanox MT28800 Family [ConnectX-5 Ex]                                | 2         | 0.8%    |
| Mellanox MT27800 Family [ConnectX-5]                                   | 2         | 0.8%    |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                | 2         | 0.8%    |
| Intel Ethernet Controller X710 for 10GBASE-T                           | 2         | 0.8%    |
| Intel Ethernet Controller I226-V                                       | 2         | 0.8%    |
| Intel Ethernet Connection I219-V                                       | 2         | 0.8%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.8%    |
| Emulex OneConnect 10Gb NIC (be3)                                       | 2         | 0.8%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 181       | 58.39%  |
| WiFi     | 126       | 40.65%  |
| Modem    | 2         | 0.65%   |
| Unknown  | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 59.61%  |
| WiFi     | 82        | 40.39%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 99        | 48.06%  |
| 1     | 63        | 30.58%  |
| 4     | 19        | 9.22%   |
| 3     | 11        | 5.34%   |
| 0     | 6         | 2.91%   |
| 6     | 4         | 1.94%   |
| 5     | 2         | 0.97%   |
| 10    | 1         | 0.49%   |
| 8     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 149       | 70.95%  |
| Yes  | 61        | 29.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 53.77%  |
| Realtek Semiconductor           | 13        | 12.26%  |
| Qualcomm Atheros Communications | 9         | 8.49%   |
| IMC Networks                    | 6         | 5.66%   |
| Broadcom                        | 6         | 5.66%   |
| Foxconn / Hon Hai               | 4         | 3.77%   |
| Cambridge Silicon Radio         | 3         | 2.83%   |
| Lite-On Technology              | 2         | 1.89%   |
| ASUSTek Computer                | 2         | 1.89%   |
| TP-Link                         | 1         | 0.94%   |
| MediaTek                        | 1         | 0.94%   |
| Foxconn International           | 1         | 0.94%   |
| Apple                           | 1         | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 17.92%  |
| Intel AX201 Bluetooth                               | 14        | 13.21%  |
| Realtek Bluetooth Radio                             | 10        | 9.43%   |
| Intel AX200 Bluetooth                               | 9         | 8.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 6.6%    |
| Intel Bluetooth Device                              | 4         | 3.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.77%   |
| Intel AX210 Bluetooth                               | 3         | 2.83%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 2.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.83%   |
| IMC Networks Bluetooth Device                       | 2         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.89%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.94%   |
| Realtek Bluetooth 5.4 Radio                         | 1         | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.94%   |
| MediaTek Wireless_Device                            | 1         | 0.94%   |
| Lite-On Wireless_Device                             | 1         | 0.94%   |
| Lite-On Bluetooth Device                            | 1         | 0.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.94%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.94%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.94%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.94%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.94%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.94%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.94%   |
| Apple Bluetooth Host Controller                     | 1         | 0.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 128       | 49.04%  |
| AMD                      | 55        | 21.07%  |
| Nvidia                   | 49        | 18.77%  |
| C-Media Electronics      | 8         | 3.07%   |
| Generalplus Technology   | 3         | 1.15%   |
| Micro Star International | 2         | 0.77%   |
| Logitech                 | 2         | 0.77%   |
| Giga-Byte Technology     | 2         | 0.77%   |
| ASUSTek Computer         | 2         | 0.77%   |
| Apple                    | 2         | 0.77%   |
| Yamaha                   | 1         | 0.38%   |
| Plantronics              | 1         | 0.38%   |
| Kingston Technology      | 1         | 0.38%   |
| JMTek                    | 1         | 0.38%   |
| Harman International     | 1         | 0.38%   |
| Creative Technology      | 1         | 0.38%   |
| Conrad Electronic SE     | 1         | 0.38%   |
| Conexant Systems         | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 23        | 7.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 3.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 3.92%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 9         | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.61%   |
| AMD Radeon High Definition Audio Controller                                                       | 8         | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.63%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.63%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.63%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.31%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.31%   |
| C-Media Electronics C-Media USB Audio Device                                                      | 4         | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 0.98%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.98%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.98%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 22.38%  |
| SK hynix            | 27        | 18.88%  |
| Kingston            | 26        | 18.18%  |
| Micron Technology   | 13        | 9.09%   |
| Crucial             | 8         | 5.59%   |
| Unknown             | 5         | 3.5%    |
| Corsair             | 5         | 3.5%    |
| G.Skill             | 4         | 2.8%    |
| Elpida              | 3         | 2.1%    |
| Unknown             | 3         | 2.1%    |
| QEMU                | 2         | 1.4%    |
| Hewlett-Packard     | 2         | 1.4%    |
| Apacer              | 2         | 1.4%    |
| Unknown (0x0100)    | 1         | 0.7%    |
| Timetec             | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| Smart               | 1         | 0.7%    |
| Patriot             | 1         | 0.7%    |
| Nanya Technology    | 1         | 0.7%    |
| Micron/Elpida       | 1         | 0.7%    |
| Lexar Co Limited    | 1         | 0.7%    |
| GOODRAM             | 1         | 0.7%    |
| GLOWAY              | 1         | 0.7%    |
| GeIL                | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 3         | 1.9%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 1.27%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.27%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s        | 2         | 1.27%   |
| SK hynix RAM HMA82GR7AFR8N-UH 16GB DIMM DDR4 2400MT/s        | 2         | 1.27%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 1.27%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s          | 2         | 1.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s        | 2         | 1.27%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.27%   |
| QEMU RAM Module 8GB DIMM RAM                                 | 2         | 1.27%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 2         | 1.27%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s        | 2         | 1.27%   |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s        | 2         | 1.27%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 2         | 1.27%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1         | 0.63%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                         | 1         | 0.63%   |
| Unknown RAM Module 32GB DIMM DDR4 2400MT/s                   | 1         | 0.63%   |
| Unknown (0x0100) RAM R744G2133S1S 4GB SODIMM DDR4 1866MT/s   | 1         | 0.63%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.63%   |
| Team RAM TEAMGROUP-SD3-1333 8GB SODIMM DDR3 1334MT/s         | 1         | 0.63%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s        | 1         | 0.63%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.63%   |
| SK hynix RAM HMT42GR7MFR4C 16GB DIMM DDR3 1600MT/s           | 1         | 0.63%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s        | 1         | 0.63%   |
| SK hynix RAM HMT351U6AFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.63%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.63%   |
| SK hynix RAM HMCGM4MEBRB237N 96GB DIMM DDR5 4800MT/s         | 1         | 0.63%   |
| SK hynix RAM HMCG94MEBRA123N 64GB DIMM DDR5 4800MT/s         | 1         | 0.63%   |
| SK hynix RAM HMCG78AHBVA315N 16GB SODIMM DDR5 6400MT/s       | 1         | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.63%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 0.63%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2667MT/s        | 1         | 0.63%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1         | 0.63%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 63        | 53.85%  |
| DDR3    | 29        | 24.79%  |
| DDR5    | 9         | 7.69%   |
| LPDDR3  | 5         | 4.27%   |
| Unknown | 3         | 2.56%   |
| RAM     | 2         | 1.71%   |
| LPDDR5  | 2         | 1.71%   |
| LPDDR4  | 2         | 1.71%   |
| DRAM    | 1         | 0.85%   |
| DDR2    | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 58        | 49.15%  |
| SODIMM       | 50        | 42.37%  |
| Row Of Chips | 10        | 8.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 46        | 36.22%  |
| 4096  | 29        | 22.83%  |
| 16384 | 23        | 18.11%  |
| 32768 | 15        | 11.81%  |
| 65536 | 7         | 5.51%   |
| 2048  | 5         | 3.94%   |
| 98304 | 1         | 0.79%   |
| 49152 | 1         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 32        | 23.88%  |
| 1600    | 19        | 14.18%  |
| 2667    | 17        | 12.69%  |
| 2133    | 10        | 7.46%   |
| 2400    | 9         | 6.72%   |
| 1333    | 6         | 4.48%   |
| 4800    | 5         | 3.73%   |
| 1866    | 5         | 3.73%   |
| 6400    | 3         | 2.24%   |
| 3733    | 3         | 2.24%   |
| 1334    | 3         | 2.24%   |
| 1066    | 3         | 2.24%   |
| 4267    | 2         | 1.49%   |
| 2933    | 2         | 1.49%   |
| 1867    | 2         | 1.49%   |
| 800     | 2         | 1.49%   |
| Unknown | 2         | 1.49%   |
| 7500    | 1         | 0.75%   |
| 5600    | 1         | 0.75%   |
| 5200    | 1         | 0.75%   |
| 3933    | 1         | 0.75%   |
| 3466    | 1         | 0.75%   |
| 3151    | 1         | 0.75%   |
| 3066    | 1         | 0.75%   |
| 1067    | 1         | 0.75%   |
| 667     | 1         | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 18.75%  |
| Realtek Semiconductor                  | 10        | 10.42%  |
| IMC Networks                           | 9         | 9.38%   |
| Bison Electronics                      | 9         | 9.38%   |
| Microdia                               | 7         | 7.29%   |
| Logitech                               | 7         | 7.29%   |
| Sunplus Innovation Technology          | 4         | 4.17%   |
| Luxvisions Innotech Limited            | 4         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.17%   |
| Syntek                                 | 3         | 3.13%   |
| Suyin                                  | 3         | 3.13%   |
| Quanta                                 | 2         | 2.08%   |
| Microsoft                              | 2         | 2.08%   |
| Z-Star Microelectronics                | 1         | 1.04%   |
| XIFT                                   | 1         | 1.04%   |
| SunplusIT                              | 1         | 1.04%   |
| Ricoh                                  | 1         | 1.04%   |
| Novatek Microelectronics               | 1         | 1.04%   |
| MacroSilicon                           | 1         | 1.04%   |
| Lite-On Technology                     | 1         | 1.04%   |
| Jieli Technology                       | 1         | 1.04%   |
| Importek                               | 1         | 1.04%   |
| icSpring                               | 1         | 1.04%   |
| DigiTech                               | 1         | 1.04%   |
| Creative Technology                    | 1         | 1.04%   |
| Apple                                  | 1         | 1.04%   |
| Unknown                                | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                              | 6         | 6.12%   |
| Bison Integrated Camera                                     | 5         | 5.1%    |
| Syntek Integrated Camera                                    | 3         | 3.06%   |
| Realtek Integrated_Webcam_HD                                | 3         | 3.06%   |
| Logitech Webcam C270                                        | 3         | 3.06%   |
| Chicony Integrated Camera                                   | 3         | 3.06%   |
| Chicony HP Truevision HD                                    | 3         | 3.06%   |
| Realtek Integrated Webcam HD                                | 2         | 2.04%   |
| Microdia Integrated Webcam HD                               | 2         | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 2.04%   |
| Logitech HD Pro Webcam C920                                 | 2         | 2.04%   |
| Chicony Integrated HP HD Webcam                             | 2         | 2.04%   |
| Z-Star Vimicro USB Camera(358boot)                          | 1         | 1.02%   |
| XIFT Web Camera                                             | 1         | 1.02%   |
| Suyin HP Truevision HD                                      | 1         | 1.02%   |
| Suyin HD WebCam                                             | 1         | 1.02%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.02%   |
| SunplusIT HD Webcam                                         | 1         | 1.02%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.02%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.02%   |
| Sunplus HD WebCam                                           | 1         | 1.02%   |
| Sunplus ASUS Webcam                                         | 1         | 1.02%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 1.02%   |
| Realtek USB Camera                                          | 1         | 1.02%   |
| Realtek Integrated_Webcam_FHD                               | 1         | 1.02%   |
| Realtek Integrated Webcam_HD                                | 1         | 1.02%   |
| Realtek EasyCamera                                          | 1         | 1.02%   |
| Realtek Bluetooth Radio                                     | 1         | 1.02%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.02%   |
| Quanta HD Webcam                                            | 1         | 1.02%   |
| Novatek USB Camera                                          | 1         | 1.02%   |
| Microsoft LifeCam VX-700                                    | 1         | 1.02%   |
| Microsoft LifeCam HD-3000                                   | 1         | 1.02%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.02%   |
| Microdia Lenovo EasyCamera                                  | 1         | 1.02%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.02%   |
| Microdia Integrated Camera                                  | 1         | 1.02%   |
| Microdia Camera                                             | 1         | 1.02%   |
| MacroSilicon USB Video                                      | 1         | 1.02%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 52.38%  |
| Synaptics                  | 6         | 28.57%  |
| Upek                       | 2         | 9.52%   |
| Shenzhen Goodix Technology | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 9.52%   |
| Validity Sensors VFS491                                                    | 2         | 9.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 9.52%   |
| Synaptics UWP WBDI Device                                                  | 2         | 9.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 9.52%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 4.76%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 4.76%   |
| Synaptics WBDI                                                             | 1         | 4.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 4.76%   |
| Elan ELAN:ARM-M4                                                           | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 33.33%  |
| SCM Microsystems | 1         | 16.67%  |
| OmniKey          | 1         | 16.67%  |
| Lenovo           | 1         | 16.67%  |
| Alcor Micro      | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 16.67%  |
| OmniKey CardMan 3021 / 3121                            | 1         | 16.67%  |
| Lenovo Integrated Smart Card Reader                    | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 16.67%  |
| Broadcom 58200                                         | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 118       | 56.73%  |
| 1     | 69        | 33.17%  |
| 2     | 13        | 6.25%   |
| 3     | 3         | 1.44%   |
| 5     | 2         | 0.96%   |
| 4     | 2         | 0.96%   |
| 7     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 27        | 23.48%  |
| Fingerprint reader       | 21        | 18.26%  |
| Net/wireless             | 17        | 14.78%  |
| Multimedia controller    | 9         | 7.83%   |
| Unassigned class         | 8         | 6.96%   |
| Sound                    | 6         | 5.22%   |
| Communication controller | 6         | 5.22%   |
| Net/ethernet             | 4         | 3.48%   |
| Firewire controller      | 4         | 3.48%   |
| Network                  | 3         | 2.61%   |
| Bluetooth                | 3         | 2.61%   |
| Storage/raid             | 2         | 1.74%   |
| Chipcard                 | 2         | 1.74%   |
| Storage/ide              | 1         | 0.87%   |
| Storage                  | 1         | 0.87%   |
| Camera                   | 1         | 0.87%   |

