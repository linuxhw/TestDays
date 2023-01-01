Linux in Peru - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

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

Total: 178

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ECS      | H61H2-M2                    | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| ASUSTek  | M5A97 R2.0                  | [951b5a453d](https://linux-hardware.org/?probe=951b5a453d) | Dec 11, 2022 |
| HP       | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| ASUSTek  | PRIME Z690-P WIFI           | [763f309094](https://linux-hardware.org/?probe=763f309094) | Nov 18, 2022 |
| ASUSTek  | PRIME B550M-A               | [8600d864a4](https://linux-hardware.org/?probe=8600d864a4) | Nov 13, 2022 |
| Deltron  | H81H3-M4                    | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| Dell     | 096JG8 A01                  | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| Unknown  | Unknown                     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| Dell     | 096JG8 A01                  | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell     | 096JG8 A01                  | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| Gigabyte | H81M-H                      | [0dd7c3989e](https://linux-hardware.org/?probe=0dd7c3989e) | Oct 12, 2022 |
| Gigabyte | 970A-DS3P                   | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| ASUSTek  | PRIME Z690-P WIFI           | [5e33c2b674](https://linux-hardware.org/?probe=5e33c2b674) | Oct 08, 2022 |
| Gigabyte | A520M H                     | [acf2f9d381](https://linux-hardware.org/?probe=acf2f9d381) | Sep 25, 2022 |
| Gigabyte | A520M H                     | [21407ce4a8](https://linux-hardware.org/?probe=21407ce4a8) | Sep 21, 2022 |
| Intel    | D945GCNL AAD97184-106       | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| Lenovo   | 3111 SDK0J40697 WIN 3305... | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| MSI      | X370 KRAIT GAMING           | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| ASUSTek  | PRIME X570-P                | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| ASUSTek  | PRIME X570-P                | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP       | 1493                        | [2ac16ddc1f](https://linux-hardware.org/?probe=2ac16ddc1f) | Aug 03, 2022 |
| ASUSTek  | M5A97                       | [e5b05f8e39](https://linux-hardware.org/?probe=e5b05f8e39) | Aug 02, 2022 |
| Gigabyte | AX370M-Gaming 3-CF          | [1c92a49cd4](https://linux-hardware.org/?probe=1c92a49cd4) | Aug 01, 2022 |
| Gigabyte | B365M DS3H                  | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| ASUSTek  | H110M-R                     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Intel    | DH61CR AAG14064-204         | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| Intel    | D102GGC2 AAD42789-204       | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| ASUSTek  | PRIME A320M-K               | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [c1db97e482](https://linux-hardware.org/?probe=c1db97e482) | May 31, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [c274a43a82](https://linux-hardware.org/?probe=c274a43a82) | May 30, 2022 |
| ASUSTek  | PRIME B450M-A               | [2ce35a0cba](https://linux-hardware.org/?probe=2ce35a0cba) | May 30, 2022 |
| Intel    | DP67BA AAG10219-300         | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Gigabyte | G1.Sniper B5-CF             | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| HP       | 8056                        | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| ASUSTek  | PRIME B450M-A               | [03581837bc](https://linux-hardware.org/?probe=03581837bc) | May 14, 2022 |
| ASUSTek  | PRIME B450M-A               | [e436a62479](https://linux-hardware.org/?probe=e436a62479) | May 13, 2022 |
| Dell     | 0773VG A02                  | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| ASUSTek  | PRIME B450M-A               | [358cadc7df](https://linux-hardware.org/?probe=358cadc7df) | May 09, 2022 |
| SZMZ     | X99 DUAL Z8                 | [f68946f3d4](https://linux-hardware.org/?probe=f68946f3d4) | May 06, 2022 |
| Gigabyte | G1.Sniper B5-CF             | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| Gigabyte | A520M H                     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| MSI      | A88XM-E45 V2                | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| Foxconn  | H61MXE                      | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| Gigabyte | G1.Sniper B5-CF             | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| Gigabyte | B365M DS3H                  | [ed62d97841](https://linux-hardware.org/?probe=ed62d97841) | Apr 18, 2022 |
| MSI      | H110M PRO-VH PLUS           | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| ASUSTek  | A68HM-E                     | [af6b7df94c](https://linux-hardware.org/?probe=af6b7df94c) | Apr 06, 2022 |
| Gigabyte | B75M-D3H                    | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Foxconn  | 2A8C                        | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| Intel    | DX79SR AAG57199-200         | [1ab5b833d9](https://linux-hardware.org/?probe=1ab5b833d9) | Mar 12, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [91e577540a](https://linux-hardware.org/?probe=91e577540a) | Feb 11, 2022 |
| Gigabyte | G1.Sniper B5-CF             | [15dd0e4767](https://linux-hardware.org/?probe=15dd0e4767) | Feb 08, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| ASRock   | X570 Pro4                   | [9dccdb1f45](https://linux-hardware.org/?probe=9dccdb1f45) | Nov 17, 2021 |
| Gigabyte | 970A-DS3P                   | [180b98585e](https://linux-hardware.org/?probe=180b98585e) | Nov 11, 2021 |
| ASUSTek  | PRIME B550M-K               | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte | H110M-M2-CF                 | [83ce5b471d](https://linux-hardware.org/?probe=83ce5b471d) | Nov 10, 2021 |
| MSI      | B560M PRO-VDH               | [140cf1defc](https://linux-hardware.org/?probe=140cf1defc) | Nov 09, 2021 |
| ASRock   | B460M-HDV                   | [f343673932](https://linux-hardware.org/?probe=f343673932) | Nov 08, 2021 |
| ASUSTek  | TUF Gaming X570-PLUS        | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| ASUSTek  | Z97-P                       | [9343a7aac0](https://linux-hardware.org/?probe=9343a7aac0) | Oct 13, 2021 |
| MSI      | H170A GAMING PRO            | [2a068afc0c](https://linux-hardware.org/?probe=2a068afc0c) | Oct 11, 2021 |
| Lenovo   | 3098 SDK0E50510 PRO or W... | [57fb928b65](https://linux-hardware.org/?probe=57fb928b65) | Oct 03, 2021 |
| ASUSTek  | A88XM-A                     | [72114a075d](https://linux-hardware.org/?probe=72114a075d) | Sep 24, 2021 |
| Dell     | 0773VG A02                  | [5b63f0fc0a](https://linux-hardware.org/?probe=5b63f0fc0a) | Sep 16, 2021 |
| Intel    | DH55TC AAE70932-302         | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Intel    | DG33BU AAD79951-413         | [9824fedcc4](https://linux-hardware.org/?probe=9824fedcc4) | Aug 16, 2021 |
| Gigabyte | M61PME-S2P                  | [46cd16e708](https://linux-hardware.org/?probe=46cd16e708) | Aug 13, 2021 |
| Gigabyte | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| Gigabyte | F2A68HM-H                   | [5b80d3040f](https://linux-hardware.org/?probe=5b80d3040f) | Jul 25, 2021 |
| Gigabyte | F2A68HM-H                   | [771ef872d9](https://linux-hardware.org/?probe=771ef872d9) | Jul 25, 2021 |
| MSI      | B460M-A PRO                 | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI      | B460M-A PRO                 | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| Gigabyte | B360 AORUS GAMING 3 WIFI... | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| ASUSTek  | Z97-P                       | [95fcf3868f](https://linux-hardware.org/?probe=95fcf3868f) | Jun 26, 2021 |
| HP       | 8054                        | [b0662fd84b](https://linux-hardware.org/?probe=b0662fd84b) | May 30, 2021 |
| HP       | 8054                        | [37f65c4171](https://linux-hardware.org/?probe=37f65c4171) | May 27, 2021 |
| Gigabyte | 970A-DS3P                   | [a1959c22e0](https://linux-hardware.org/?probe=a1959c22e0) | May 20, 2021 |
| MSI      | A88X-G45 GAMING             | [930993fd14](https://linux-hardware.org/?probe=930993fd14) | May 16, 2021 |
| MSI      | A88X-G45 GAMING             | [f7a3ab5c2f](https://linux-hardware.org/?probe=f7a3ab5c2f) | May 16, 2021 |
| Gigabyte | B550 AORUS ELITE            | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek  | Z97-P                       | [6eb605ae36](https://linux-hardware.org/?probe=6eb605ae36) | Apr 21, 2021 |
| ASUSTek  | Z97-P                       | [4bd5425a6b](https://linux-hardware.org/?probe=4bd5425a6b) | Apr 11, 2021 |
| Gigabyte | B550 AORUS ELITE            | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| MSI      | B75A-G43                    | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte | H110M-H-CF                  | [b02d3fa1c0](https://linux-hardware.org/?probe=b02d3fa1c0) | Apr 04, 2021 |
| Lenovo   | ThinkCentre M91 7516AD1     | [91ae7f221c](https://linux-hardware.org/?probe=91ae7f221c) | Apr 01, 2021 |
| Unknown  | Unknown                     | [860e86fde0](https://linux-hardware.org/?probe=860e86fde0) | Mar 19, 2021 |
| Unknown  | Unknown                     | [4d1099b04c](https://linux-hardware.org/?probe=4d1099b04c) | Mar 18, 2021 |
| Gigabyte | H81M-H                      | [96dd155871](https://linux-hardware.org/?probe=96dd155871) | Mar 07, 2021 |
| Intel    | H61                         | [77b62ac54a](https://linux-hardware.org/?probe=77b62ac54a) | Mar 05, 2021 |
| PCChips  | P49G                        | [a2f19ae622](https://linux-hardware.org/?probe=a2f19ae622) | Feb 17, 2021 |
| MSI      | A88X-G45 GAMING             | [05d5a888d4](https://linux-hardware.org/?probe=05d5a888d4) | Feb 16, 2021 |
| MSI      | A320M-A PRO MAX             | [c4f6a52387](https://linux-hardware.org/?probe=c4f6a52387) | Feb 13, 2021 |
| Intel    | D945GTP AAC97834-305        | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| Intel    | DP965LT AAD41694-209        | [c577103201](https://linux-hardware.org/?probe=c577103201) | Jan 02, 2021 |
| ASUSTek  | A88XM-A                     | [35757b1c8c](https://linux-hardware.org/?probe=35757b1c8c) | Dec 06, 2020 |
| Gigabyte | H110M-M2-CF                 | [228dc321d9](https://linux-hardware.org/?probe=228dc321d9) | Dec 05, 2020 |
| Foxconn  | 2A8C                        | [f0c3c358a0](https://linux-hardware.org/?probe=f0c3c358a0) | Dec 03, 2020 |
| Gigabyte | GA-MA790XT-UD4P             | [5837b78f0c](https://linux-hardware.org/?probe=5837b78f0c) | Nov 26, 2020 |
| Dell     | 0DR845                      | [80aa8797b0](https://linux-hardware.org/?probe=80aa8797b0) | Oct 29, 2020 |
| MSI      | B360M PRO-VH                | [d8eb2de621](https://linux-hardware.org/?probe=d8eb2de621) | Oct 21, 2020 |
| Gigabyte | 970A-DS3P                   | [943240cc2a](https://linux-hardware.org/?probe=943240cc2a) | Oct 09, 2020 |
| ASRock   | X570 Phantom Gaming 4       | [8987176239](https://linux-hardware.org/?probe=8987176239) | Sep 28, 2020 |
| Intel    | 945GCT-M                    | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel    | 945GCT-M                    | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| MSI      | H81M-E33                    | [313883253c](https://linux-hardware.org/?probe=313883253c) | Sep 07, 2020 |
| ASUSTek  | A88XM-A                     | [47c7bf1c93](https://linux-hardware.org/?probe=47c7bf1c93) | Aug 30, 2020 |
| ASRock   | X470 Master SLI/ac          | [3ac15dbee9](https://linux-hardware.org/?probe=3ac15dbee9) | Aug 28, 2020 |
| Gigabyte | 970A-DS3P                   | [31a8ca3766](https://linux-hardware.org/?probe=31a8ca3766) | Aug 18, 2020 |
| ASUSTek  | A88XM-A                     | [2adefb78ad](https://linux-hardware.org/?probe=2adefb78ad) | Aug 13, 2020 |
| Intel    | DG31PR AAD97573-206         | [02c231ca67](https://linux-hardware.org/?probe=02c231ca67) | Jul 27, 2020 |
| ASUSTek  | PRIME X570-P                | [4e0fee8549](https://linux-hardware.org/?probe=4e0fee8549) | Jul 20, 2020 |
| Intel    | DG31PR AAD97573-305         | [e3bd0984ee](https://linux-hardware.org/?probe=e3bd0984ee) | Jul 17, 2020 |
| Intel    | H61M-DS2                    | [2e847ac1d0](https://linux-hardware.org/?probe=2e847ac1d0) | Jul 16, 2020 |
| Gigabyte | X570 AORUS MASTER           | [4716a84af9](https://linux-hardware.org/?probe=4716a84af9) | Jul 03, 2020 |
| HP       | 09E8h                       | [d9b1f1bf60](https://linux-hardware.org/?probe=d9b1f1bf60) | Jun 28, 2020 |
| Gigabyte | GA-890FXA-UD5               | [f073723231](https://linux-hardware.org/?probe=f073723231) | Jun 27, 2020 |
| Gigabyte | GA-890FXA-UD5               | [7f8abda42c](https://linux-hardware.org/?probe=7f8abda42c) | Jun 27, 2020 |
| Intel    | H61M-DS2                    | [aef4861ab1](https://linux-hardware.org/?probe=aef4861ab1) | Jun 25, 2020 |
| HP       | 3397                        | [3421ad000d](https://linux-hardware.org/?probe=3421ad000d) | Jun 21, 2020 |
| HP       | 09E8h                       | [14e6514858](https://linux-hardware.org/?probe=14e6514858) | Jun 20, 2020 |
| Intel    | DG41WV AAE90316-104         | [3b021c1b62](https://linux-hardware.org/?probe=3b021c1b62) | Jun 17, 2020 |
| Intel    | DG41WV AAE90316-104         | [821a7a7b85](https://linux-hardware.org/?probe=821a7a7b85) | Jun 17, 2020 |
| Dell     | 0DR845                      | [cb4b80e381](https://linux-hardware.org/?probe=cb4b80e381) | Jun 14, 2020 |
| Dell     | 0DR845                      | [107ec57e94](https://linux-hardware.org/?probe=107ec57e94) | Jun 13, 2020 |
| Foxconn  | 45CMX/45GMX/45CMX-K         | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| Intel    | DH61WW AAG23116-302         | [615d9bbafb](https://linux-hardware.org/?probe=615d9bbafb) | Jun 07, 2020 |
| Intel    | DH61WW AAG23116-302         | [db6aa4b6fa](https://linux-hardware.org/?probe=db6aa4b6fa) | Jun 07, 2020 |
| Dell     | 0WMJ54 A01                  | [b803424e29](https://linux-hardware.org/?probe=b803424e29) | May 31, 2020 |
| MSI      | A68HM-E33 V2                | [ea48f46d27](https://linux-hardware.org/?probe=ea48f46d27) | May 27, 2020 |
| Foxconn  | H61MXE/-S/-V/-K             | [3d5fc4df20](https://linux-hardware.org/?probe=3d5fc4df20) | May 27, 2020 |
| Biostar  | GF7025-M2                   | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Dell     | 0WMJ54 A01                  | [4c93d3634b](https://linux-hardware.org/?probe=4c93d3634b) | May 24, 2020 |
| Gigabyte | G41MT-S2                    | [f8702707c6](https://linux-hardware.org/?probe=f8702707c6) | May 22, 2020 |
| Intel    | D945GCNL AAD97184-102       | [72691e43eb](https://linux-hardware.org/?probe=72691e43eb) | May 14, 2020 |
| Gigabyte | B450 GAMING X               | [404ef9032e](https://linux-hardware.org/?probe=404ef9032e) | May 12, 2020 |
| HP       | 0A58h                       | [a3a4679ef9](https://linux-hardware.org/?probe=a3a4679ef9) | May 05, 2020 |
| Intel    | DX58SO AAE29331-703         | [08c0779e95](https://linux-hardware.org/?probe=08c0779e95) | May 02, 2020 |
| Intel    | DH61WW AAG23116-204         | [eb77b46e2f](https://linux-hardware.org/?probe=eb77b46e2f) | Apr 30, 2020 |
| Gigabyte | GA-970A-D3                  | [32546cbd9d](https://linux-hardware.org/?probe=32546cbd9d) | Apr 26, 2020 |
| MSI      | A68HM-E33 V2                | [d88e072663](https://linux-hardware.org/?probe=d88e072663) | Apr 15, 2020 |
| ASRock   | X570 Phantom Gaming 4       | [71673b2f86](https://linux-hardware.org/?probe=71673b2f86) | Apr 09, 2020 |
| MSI      | A68HM-E33 V2                | [6277a6ec0b](https://linux-hardware.org/?probe=6277a6ec0b) | Apr 08, 2020 |
| HP       | 0A60h                       | [e929430fd0](https://linux-hardware.org/?probe=e929430fd0) | Apr 08, 2020 |
| PCChips  | P49G                        | [57f11f5c76](https://linux-hardware.org/?probe=57f11f5c76) | Apr 04, 2020 |
| HP       | 3397                        | [71764f18dd](https://linux-hardware.org/?probe=71764f18dd) | Mar 21, 2020 |
| HP       | 09E8h                       | [57904c47e1](https://linux-hardware.org/?probe=57904c47e1) | Mar 21, 2020 |
| HP       | 09E8h                       | [4c44586ba9](https://linux-hardware.org/?probe=4c44586ba9) | Mar 21, 2020 |
| PCChips  | P49G                        | [1cedc0a4f7](https://linux-hardware.org/?probe=1cedc0a4f7) | Mar 17, 2020 |
| Gigabyte | B450 GAMING X               | [145e6998fc](https://linux-hardware.org/?probe=145e6998fc) | Mar 06, 2020 |
| Gigabyte | G1.Sniper B5-CF             | [baaf155c68](https://linux-hardware.org/?probe=baaf155c68) | Mar 04, 2020 |
| Lenovo   | MAHOBAY                     | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo   | MAHOBAY                     | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Gigabyte | M68MT-S2                    | [6a5c6cf0dc](https://linux-hardware.org/?probe=6a5c6cf0dc) | Feb 23, 2020 |
| Gigabyte | G1.Sniper B5-CF             | [8a4a2a6066](https://linux-hardware.org/?probe=8a4a2a6066) | Feb 21, 2020 |
| Intel    | CM8V5CB8N K53774-201        | [4ba8cd9ca2](https://linux-hardware.org/?probe=4ba8cd9ca2) | Feb 16, 2020 |
| Intel    | CM8V5CB8N K53774-201        | [19086b2ac2](https://linux-hardware.org/?probe=19086b2ac2) | Feb 16, 2020 |
| MSI      | 970 GAMING                  | [7ae91dcf15](https://linux-hardware.org/?probe=7ae91dcf15) | Jan 21, 2020 |
| ASUSTek  | B85M-G R2.0                 | [12b760b696](https://linux-hardware.org/?probe=12b760b696) | Jan 20, 2020 |
| ASUSTek  | M5A97                       | [a381f0be23](https://linux-hardware.org/?probe=a381f0be23) | Jan 17, 2020 |
| Gigabyte | B75M-D3H                    | [5b67f6ed83](https://linux-hardware.org/?probe=5b67f6ed83) | Dec 26, 2019 |
| Dell     | 0G261D A00                  | [c05b5b48de](https://linux-hardware.org/?probe=c05b5b48de) | Dec 05, 2019 |
| Dell     | 0G261D A00                  | [3862b040a2](https://linux-hardware.org/?probe=3862b040a2) | Dec 04, 2019 |
| Dell     | 0G261D A00                  | [50ef5c54ef](https://linux-hardware.org/?probe=50ef5c54ef) | Nov 29, 2019 |
| Foxconn  | A76GMV                      | [ddfa1ad143](https://linux-hardware.org/?probe=ddfa1ad143) | Oct 22, 2019 |
| Gigabyte | EP35C-DS3R                  | [048c1a4f90](https://linux-hardware.org/?probe=048c1a4f90) | Jun 25, 2019 |
| Gigabyte | A55M-DS2                    | [9e2c603e49](https://linux-hardware.org/?probe=9e2c603e49) | Jun 23, 2019 |
| Gigabyte | Z77X-UD5H                   | [07dd5b8424](https://linux-hardware.org/?probe=07dd5b8424) | Jun 14, 2019 |
| Gigabyte | Z77X-UD5H                   | [5ca60ce3ac](https://linux-hardware.org/?probe=5ca60ce3ac) | Apr 06, 2019 |
| Gigabyte | Z77X-UD5H                   | [c7dd2b6e26](https://linux-hardware.org/?probe=c7dd2b6e26) | Mar 26, 2019 |
| AMI      | Cherry Trail CR             | [e248592999](https://linux-hardware.org/?probe=e248592999) | Nov 03, 2018 |
| MSI      | A68HM-E33 V2                | [765c79328e](https://linux-hardware.org/?probe=765c79328e) | Jun 26, 2018 |
| ECS      | MCP61M-M3                   | [a51a8c96df](https://linux-hardware.org/?probe=a51a8c96df) | Apr 08, 2018 |
| Intel    | DH55PJ AAE93812-303         | [4d498130d3](https://linux-hardware.org/?probe=4d498130d3) | Dec 24, 2016 |
| Intel    | DH55PJ AAE93812-303         | [58bc94c592](https://linux-hardware.org/?probe=58bc94c592) | Dec 24, 2016 |
| Intel    | DH55PJ AAE93812-303         | [7201ee94b8](https://linux-hardware.org/?probe=7201ee94b8) | Nov 07, 2016 |
| Intel    | DH55PJ AAE93812-303         | [4567d9bca4](https://linux-hardware.org/?probe=4567d9bca4) | Nov 02, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 23       | 17.69%  |
| Ubuntu 18.04                 | 11       | 8.46%   |
| OpenMandriva 4.3             | 9        | 6.92%   |
| Ubuntu 22.04                 | 8        | 6.15%   |
| OpenMandriva 4.2             | 7        | 5.38%   |
| Zorin 15                     | 4        | 3.08%   |
| Ubuntu 19.10                 | 4        | 3.08%   |
| Linux Mint 19.3              | 4        | 3.08%   |
| Ubuntu 21.10                 | 3        | 2.31%   |
| Manjaro                      | 3        | 2.31%   |
| Linux Mint 20.1              | 3        | 2.31%   |
| Kubuntu 20.04                | 3        | 2.31%   |
| Debian 11                    | 3        | 2.31%   |
| ROSA R9                      | 2        | 1.54%   |
| ROSA R8                      | 2        | 1.54%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.54%   |
| Linux Mint 19.2              | 2        | 1.54%   |
| KDE neon 20.04               | 2        | 1.54%   |
| Endless 3.5.7                | 2        | 1.54%   |
| CentOS 8                     | 2        | 1.54%   |
| Zorin 16                     | 1        | 0.77%   |
| Xubuntu 20.04                | 1        | 0.77%   |
| Xubuntu 18.04                | 1        | 0.77%   |
| Ubuntu Unity 18.04           | 1        | 0.77%   |
| Ubuntu MATE 22.04            | 1        | 0.77%   |
| Ubuntu MATE 21.04            | 1        | 0.77%   |
| Ubuntu MATE 20.10            | 1        | 0.77%   |
| Ubuntu MATE 18.04            | 1        | 0.77%   |
| Ubuntu MATE 16.04            | 1        | 0.77%   |
| ROSA R11.1                   | 1        | 0.77%   |
| ROSA R11                     | 1        | 0.77%   |
| Peppermint 10                | 1        | 0.77%   |
| openSUSE Leap-15.3           | 1        | 0.77%   |
| openSUSE Leap-15.2           | 1        | 0.77%   |
| OpenMandriva 4.90            | 1        | 0.77%   |
| OpenMandriva 4.50            | 1        | 0.77%   |
| Manjaro 21.2.6               | 1        | 0.77%   |
| Lubuntu 20.04                | 1        | 0.77%   |
| Lubuntu 18.04                | 1        | 0.77%   |
| Linux Mint 21                | 1        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 44       | 35.48%  |
| OpenMandriva | 18       | 14.52%  |
| Linux Mint   | 11       | 8.87%   |
| ROSA         | 6        | 4.84%   |
| Zorin        | 5        | 4.03%   |
| Ubuntu MATE  | 5        | 4.03%   |
| openSUSE     | 4        | 3.23%   |
| Manjaro      | 4        | 3.23%   |
| Debian       | 4        | 3.23%   |
| Linux Lite   | 3        | 2.42%   |
| Kubuntu      | 3        | 2.42%   |
| Fedora       | 3        | 2.42%   |
| Xubuntu      | 2        | 1.61%   |
| Lubuntu      | 2        | 1.61%   |
| KDE neon     | 2        | 1.61%   |
| Endless      | 2        | 1.61%   |
| CentOS       | 2        | 1.61%   |
| Ubuntu Unity | 1        | 0.81%   |
| Peppermint   | 1        | 0.81%   |
| Feren OS     | 1        | 0.81%   |
| Arch         | 1        | 0.81%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003         | 8        | 5.52%   |
| 5.10.14-desktop-1omv4002        | 7        | 4.83%   |
| 5.3.0-40-generic                | 5        | 3.45%   |
| 5.4.0-70-generic                | 3        | 2.07%   |
| 5.4.0-66-generic                | 3        | 2.07%   |
| 5.4.0-52-generic                | 3        | 2.07%   |
| 5.4.0-37-generic                | 3        | 2.07%   |
| 5.4.0-31-generic                | 3        | 2.07%   |
| 5.11.0-40-generic               | 3        | 2.07%   |
| 4.18.0-15-generic               | 3        | 2.07%   |
| 5.8.0-48-generic                | 2        | 1.38%   |
| 5.4.0-58-generic                | 2        | 1.38%   |
| 5.4.0-40-generic                | 2        | 1.38%   |
| 5.4.0-29-generic                | 2        | 1.38%   |
| 5.4.0-28-generic                | 2        | 1.38%   |
| 5.3.0-46-generic                | 2        | 1.38%   |
| 5.3.0-26-generic                | 2        | 1.38%   |
| 5.15.0-48-generic               | 2        | 1.38%   |
| 5.15.0-43-generic               | 2        | 1.38%   |
| 5.15.0-27-generic               | 2        | 1.38%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2        | 1.38%   |
| 4.15.0-54-generic               | 2        | 1.38%   |
| 4.15.0-112-generic              | 2        | 1.38%   |
| 6.0.5-200.fc36.x86_64           | 1        | 0.69%   |
| 6.0.10-300.fc37.x86_64          | 1        | 0.69%   |
| 5.9.11-3-MANJARO                | 1        | 0.69%   |
| 5.8.7-1-default                 | 1        | 0.69%   |
| 5.8.0-63-generic                | 1        | 0.69%   |
| 5.8.0-53-generic                | 1        | 0.69%   |
| 5.8.0-45-generic                | 1        | 0.69%   |
| 5.8.0-31-generic                | 1        | 0.69%   |
| 5.8.0-2-amd64                   | 1        | 0.69%   |
| 5.7.9-xanmod1                   | 1        | 0.69%   |
| 5.7.14-200.fc32.x86_64          | 1        | 0.69%   |
| 5.6.19-2-MANJARO                | 1        | 0.69%   |
| 5.6.0-1-default                 | 1        | 0.69%   |
| 5.4.83-generic-2rosa-x86_64     | 1        | 0.69%   |
| 5.4.118-1-MANJARO               | 1        | 0.69%   |
| 5.4.0-81-generic                | 1        | 0.69%   |
| 5.4.0-77-generic                | 1        | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 29       | 21.8%   |
| 5.3.0   | 11       | 8.27%   |
| 5.15.0  | 11       | 8.27%   |
| 4.15.0  | 10       | 7.52%   |
| 5.16.7  | 8        | 6.02%   |
| 5.10.14 | 7        | 5.26%   |
| 5.8.0   | 6        | 4.51%   |
| 5.13.0  | 6        | 4.51%   |
| 4.18.0  | 6        | 4.51%   |
| 5.11.0  | 5        | 3.76%   |
| 5.10.0  | 3        | 2.26%   |
| 5.3.18  | 2        | 1.5%    |
| 5.17.1  | 2        | 1.5%    |
| 4.9.20  | 2        | 1.5%    |
| 6.0.5   | 1        | 0.75%   |
| 6.0.10  | 1        | 0.75%   |
| 5.9.11  | 1        | 0.75%   |
| 5.8.7   | 1        | 0.75%   |
| 5.7.9   | 1        | 0.75%   |
| 5.7.14  | 1        | 0.75%   |
| 5.6.19  | 1        | 0.75%   |
| 5.6.0   | 1        | 0.75%   |
| 5.4.83  | 1        | 0.75%   |
| 5.4.118 | 1        | 0.75%   |
| 5.19.5  | 1        | 0.75%   |
| 5.19.15 | 1        | 0.75%   |
| 5.18.12 | 1        | 0.75%   |
| 5.17.5  | 1        | 0.75%   |
| 5.16.13 | 1        | 0.75%   |
| 5.16.0  | 1        | 0.75%   |
| 5.11.19 | 1        | 0.75%   |
| 5.10.52 | 1        | 0.75%   |
| 5.10.2  | 1        | 0.75%   |
| 5.0.0   | 1        | 0.75%   |
| 4.9.155 | 1        | 0.75%   |
| 4.8.0   | 1        | 0.75%   |
| 4.4.0   | 1        | 0.75%   |
| 4.1.34  | 1        | 0.75%   |
| 4.1.25  | 1        | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 31       | 23.31%  |
| 5.3     | 13       | 9.77%   |
| 5.10    | 12       | 9.02%   |
| 5.15    | 11       | 8.27%   |
| 5.16    | 10       | 7.52%   |
| 4.15    | 10       | 7.52%   |
| 5.8     | 7        | 5.26%   |
| 5.13    | 6        | 4.51%   |
| 5.11    | 6        | 4.51%   |
| 4.18    | 6        | 4.51%   |
| 5.17    | 3        | 2.26%   |
| 4.9     | 3        | 2.26%   |
| 6.0     | 2        | 1.5%    |
| 5.7     | 2        | 1.5%    |
| 5.6     | 2        | 1.5%    |
| 5.19    | 2        | 1.5%    |
| 4.1     | 2        | 1.5%    |
| 5.9     | 1        | 0.75%   |
| 5.18    | 1        | 0.75%   |
| 5.0     | 1        | 0.75%   |
| 4.8     | 1        | 0.75%   |
| 4.4     | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 112      | 93.33%  |
| i686   | 8        | 6.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 51       | 40.8%   |
| KDE5            | 26       | 20.8%   |
| XFCE            | 11       | 8.8%    |
| X-Cinnamon      | 9        | 7.2%    |
| Unknown         | 9        | 7.2%    |
| MATE            | 7        | 5.6%    |
| KDE4            | 5        | 4%      |
| LXDE            | 2        | 1.6%    |
| Unity           | 1        | 0.8%    |
| LXQt            | 1        | 0.8%    |
| KDE             | 1        | 0.8%    |
| GNOME Flashback | 1        | 0.8%    |
| awesome         | 1        | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 105      | 84.68%  |
| Wayland | 12       | 9.68%   |
| Unknown | 7        | 5.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 50.79%  |
| SDDM    | 24       | 19.05%  |
| GDM3    | 14       | 11.11%  |
| GDM     | 9        | 7.14%   |
| LightDM | 7        | 5.56%   |
| KDM     | 5        | 3.97%   |
| TDM     | 3        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_PE   | 67       | 55.37%  |
| en_US   | 27       | 22.31%  |
| Unknown | 11       | 9.09%   |
| es_ES   | 10       | 8.26%   |
| es_MX   | 2        | 1.65%   |
| es_US   | 1        | 0.83%   |
| en_GB   | 1        | 0.83%   |
| de_DE   | 1        | 0.83%   |
| C       | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 79       | 65.29%  |
| EFI  | 42       | 34.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 89       | 72.36%  |
| Overlay | 17       | 13.82%  |
| Unknown | 7        | 5.69%   |
| Btrfs   | 5        | 4.07%   |
| Xfs     | 3        | 2.44%   |
| Ext3    | 2        | 1.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 79       | 63.71%  |
| GPT     | 29       | 23.39%  |
| MBR     | 16       | 12.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 80.16%  |
| Yes       | 25       | 19.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 58.87%  |
| Yes       | 51       | 41.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 30       | 25%     |
| Intel               | 22       | 18.33%  |
| ASUSTek Computer    | 17       | 14.17%  |
| MSI                 | 14       | 11.67%  |
| Hewlett-Packard     | 8        | 6.67%   |
| Foxconn             | 6        | 5%      |
| Dell                | 6        | 5%      |
| Lenovo              | 4        | 3.33%   |
| ASRock              | 4        | 3.33%   |
| ECS                 | 2        | 1.67%   |
| Unknown             | 2        | 1.67%   |
| SZMZ                | 1        | 0.83%   |
| PCChips             | 1        | 0.83%   |
| Deltron             | 1        | 0.83%   |
| Biostar             | 1        | 0.83%   |
| AMI                 | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Gigabyte 970A-DS3P                  | 4        | 3.33%   |
| MSI MS-7721                         | 3        | 2.5%    |
| Intel DH55PJ AAE93812-303           | 2        | 1.67%   |
| Gigabyte Z77X-UD5H                  | 2        | 1.67%   |
| Gigabyte B75M-D3H                   | 2        | 1.67%   |
| Gigabyte A520M H                    | 2        | 1.67%   |
| Foxconn 500B Microtower             | 2        | 1.67%   |
| Dell OptiPlex 7010                  | 2        | 1.67%   |
| ASUS TUF Gaming B550M-PLUS          | 2        | 1.67%   |
| ASUS PRIME X570-P                   | 2        | 1.67%   |
| ASUS All Series                     | 2        | 1.67%   |
| Unknown                             | 2        | 1.67%   |
| SZMZ X99 DUAL Z8                    | 1        | 0.83%   |
| PCChips P49G                        | 1        | 0.83%   |
| MSI MS-7D18                         | 1        | 0.83%   |
| MSI MS-7C88                         | 1        | 0.83%   |
| MSI MS-7C52                         | 1        | 0.83%   |
| MSI MS-7B53                         | 1        | 0.83%   |
| MSI MS-7A33                         | 1        | 0.83%   |
| MSI MS-7A15                         | 1        | 0.83%   |
| MSI MS-7978                         | 1        | 0.83%   |
| MSI MS-7900                         | 1        | 0.83%   |
| MSI MS-7817                         | 1        | 0.83%   |
| MSI MS-7758                         | 1        | 0.83%   |
| MSI MS-7693                         | 1        | 0.83%   |
| Lenovo ThinkCentre M91 7516AD1      | 1        | 0.83%   |
| Lenovo ThinkCentre M73 10B7A0UD00   | 1        | 0.83%   |
| Lenovo ThinkCentre M72z 3548B2S     | 1        | 0.83%   |
| Lenovo ThinkCentre M710q 10MQSC0N00 | 1        | 0.83%   |
| Intel H61M-DS2                      | 1        | 0.83%   |
| Intel H61                           | 1        | 0.83%   |
| Intel DX79SR AAG57199-200           | 1        | 0.83%   |
| Intel DX58SO AAE29331-703           | 1        | 0.83%   |
| Intel DP965LT AAD41694-209          | 1        | 0.83%   |
| Intel DP67BA AAG10219-300           | 1        | 0.83%   |
| Intel DH61WW AAG23116-302           | 1        | 0.83%   |
| Intel DH61WW AAG23116-204           | 1        | 0.83%   |
| Intel DH61CR AAG14064-204           | 1        | 0.83%   |
| Intel DH55TC AAE70932-302           | 1        | 0.83%   |
| Intel DG41WV AAE90316-104           | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 7        | 5.83%   |
| Dell OptiPlex      | 6        | 5%      |
| HP Compaq          | 5        | 4.17%   |
| Lenovo ThinkCentre | 4        | 3.33%   |
| Gigabyte 970A-DS3P | 4        | 3.33%   |
| MSI MS-7721        | 3        | 2.5%    |
| ASUS TUF           | 3        | 2.5%    |
| Intel DH61WW       | 2        | 1.67%   |
| Intel DH55PJ       | 2        | 1.67%   |
| Intel DG31PR       | 2        | 1.67%   |
| Intel D945GCNL     | 2        | 1.67%   |
| HP EliteDesk       | 2        | 1.67%   |
| Gigabyte Z77X-UD5H | 2        | 1.67%   |
| Gigabyte B75M-D3H  | 2        | 1.67%   |
| Gigabyte A520M     | 2        | 1.67%   |
| Foxconn H61MXE     | 2        | 1.67%   |
| Foxconn 500B       | 2        | 1.67%   |
| ASUS M5A97         | 2        | 1.67%   |
| ASUS All           | 2        | 1.67%   |
| ASRock X570        | 2        | 1.67%   |
| Unknown            | 2        | 1.67%   |
| SZMZ X99           | 1        | 0.83%   |
| PCChips P49G       | 1        | 0.83%   |
| MSI MS-7D18        | 1        | 0.83%   |
| MSI MS-7C88        | 1        | 0.83%   |
| MSI MS-7C52        | 1        | 0.83%   |
| MSI MS-7B53        | 1        | 0.83%   |
| MSI MS-7A33        | 1        | 0.83%   |
| MSI MS-7A15        | 1        | 0.83%   |
| MSI MS-7978        | 1        | 0.83%   |
| MSI MS-7900        | 1        | 0.83%   |
| MSI MS-7817        | 1        | 0.83%   |
| MSI MS-7758        | 1        | 0.83%   |
| MSI MS-7693        | 1        | 0.83%   |
| Intel H61M-DS2     | 1        | 0.83%   |
| Intel H61          | 1        | 0.83%   |
| Intel DX79SR       | 1        | 0.83%   |
| Intel DX58SO       | 1        | 0.83%   |
| Intel DP965LT      | 1        | 0.83%   |
| Intel DP67BA       | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 15       | 12.5%   |
| 2012 | 13       | 10.83%  |
| 2010 | 12       | 10%     |
| 2019 | 10       | 8.33%   |
| 2013 | 10       | 8.33%   |
| 2015 | 8        | 6.67%   |
| 2011 | 8        | 6.67%   |
| 2007 | 7        | 5.83%   |
| 2018 | 6        | 5%      |
| 2014 | 6        | 5%      |
| 2008 | 6        | 5%      |
| 2017 | 5        | 4.17%   |
| 2016 | 5        | 4.17%   |
| 2009 | 4        | 3.33%   |
| 2021 | 2        | 1.67%   |
| 2006 | 2        | 1.67%   |
| 2004 | 1        | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 120      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 118      | 98.33%  |
| Enabled  | 2        | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 29       | 23.39%  |
| 8.01-16.0   | 26       | 20.97%  |
| 16.01-24.0  | 23       | 18.55%  |
| 4.01-8.0    | 20       | 16.13%  |
| 32.01-64.0  | 11       | 8.87%   |
| 1.01-2.0    | 6        | 4.84%   |
| 24.01-32.0  | 4        | 3.23%   |
| 2.01-3.0    | 2        | 1.61%   |
| 64.01-256.0 | 2        | 1.61%   |
| 0.51-1.0    | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 53       | 38.97%  |
| 2.01-3.0   | 30       | 22.06%  |
| 4.01-8.0   | 17       | 12.5%   |
| 0.51-1.0   | 17       | 12.5%   |
| 3.01-4.0   | 14       | 10.29%  |
| 8.01-16.0  | 4        | 2.94%   |
| 16.01-24.0 | 1        | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 48.8%   |
| 2      | 40       | 32%     |
| 3      | 15       | 12%     |
| 4      | 8        | 6.4%    |
| 5      | 1        | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 51.67%  |
| Yes       | 58       | 48.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 99.17%  |
| No        | 1        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 68.8%   |
| Yes       | 39       | 31.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 80.33%  |
| Yes       | 24       | 19.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Peru    | 120      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Lima             | 82       | 67.21%  |
| Trujillo         | 9        | 7.38%   |
| Arequipa         | 6        | 4.92%   |
| Tacna            | 4        | 3.28%   |
| Moquegua         | 3        | 2.46%   |
| Huancayo         | 3        | 2.46%   |
| Villa            | 2        | 1.64%   |
| Piura            | 2        | 1.64%   |
| Junin            | 2        | 1.64%   |
| Chiclayo         | 2        | 1.64%   |
| Puno             | 1        | 0.82%   |
| Pucallpa         | 1        | 0.82%   |
| Ica              | 1        | 0.82%   |
| Distrito de Lima | 1        | 0.82%   |
| Cusco            | 1        | 0.82%   |
| Barranco         | 1        | 0.82%   |
| Abancay          | 1        | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 58       | 96     | 32.22%  |
| WDC                       | 40       | 64     | 22.22%  |
| Kingston                  | 21       | 26     | 11.67%  |
| Samsung Electronics       | 17       | 22     | 9.44%   |
| Toshiba                   | 10       | 11     | 5.56%   |
| Crucial                   | 6        | 9      | 3.33%   |
| Hewlett-Packard           | 4        | 5      | 2.22%   |
| Sandisk                   | 3        | 4      | 1.67%   |
| PNY                       | 3        | 3      | 1.67%   |
| Micron/Crucial Technology | 3        | 3      | 1.67%   |
| A-DATA Technology         | 3        | 3      | 1.67%   |
| Team                      | 2        | 2      | 1.11%   |
| Silicon Motion            | 2        | 2      | 1.11%   |
| Hitachi                   | 2        | 4      | 1.11%   |
| WD MediaMax               | 1        | 1      | 0.56%   |
| Mushkin                   | 1        | 2      | 0.56%   |
| Maxone                    | 1        | 2      | 0.56%   |
| LITEON                    | 1        | 1      | 0.56%   |
| KESU                      | 1        | 1      | 0.56%   |
| Intel                     | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB   | 14       | 6.57%   |
| Seagate ST1000DM010-2EP102 1TB    | 7        | 3.29%   |
| Seagate ST3500418AS 500GB         | 5        | 2.35%   |
| Kingston SA400S37480G 480GB SSD   | 5        | 2.35%   |
| Seagate ST3500413AS 500GB         | 4        | 1.88%   |
| Seagate ST2000DM001-1ER164 2TB    | 4        | 1.88%   |
| Seagate ST1000LM035-1RK172 1TB    | 4        | 1.88%   |
| Kingston SA400S37120G 120GB SSD   | 4        | 1.88%   |
| WDC WD10EZEX-08WN4A0 1TB          | 3        | 1.41%   |
| Toshiba DT01ACA100 1TB            | 3        | 1.41%   |
| Seagate ST3500312CS 500GB         | 3        | 1.41%   |
| Seagate ST2000DM006-2DM164 2TB    | 3        | 1.41%   |
| Seagate ST2000DL003-9VT166 2TB    | 3        | 1.41%   |
| Seagate ST1000DM003-9YN162 1TB    | 3        | 1.41%   |
| Seagate ST1000DM003-1ER162 1TB    | 3        | 1.41%   |
| Seagate ST1000DM003-1CH162 1TB    | 3        | 1.41%   |
| Kingston SNVS250G 250GB           | 3        | 1.41%   |
| Kingston SA400S37240G 240GB SSD   | 3        | 1.41%   |
| Kingston NVMe SSD Drive 500GB     | 3        | 1.41%   |
| HP SSD S700 500GB                 | 3        | 1.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD  | 2        | 0.94%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 2        | 0.94%   |
| WDC WD80EFAX-68KNBN0 8TB          | 2        | 0.94%   |
| WDC WD3200BPVT-22ZEST0 320GB      | 2        | 0.94%   |
| WDC WD10EZEX-08M2NA0 1TB          | 2        | 0.94%   |
| WDC WD10EZEX-00WN4A0 1TB          | 2        | 0.94%   |
| Toshiba HDWD110 1TB               | 2        | 0.94%   |
| Seagate Expansion 4TB             | 2        | 0.94%   |
| Samsung HD322HJ 320GB             | 2        | 0.94%   |
| Samsung HD161HJ 160GB             | 2        | 0.94%   |
| Samsung HD080HJ/ 80GB             | 2        | 0.94%   |
| Micron/Crucial NVMe SSD Drive 1TB | 2        | 0.94%   |
| Kingston SV300S37A120G 120GB SSD  | 2        | 0.94%   |
| Kingston SNVS500G 500GB           | 2        | 0.94%   |
| Crucial CT1000P1SSD8 1TB          | 2        | 0.94%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD  | 1        | 0.47%   |
| WDC WDS250G2B0B 250GB SSD         | 1        | 0.47%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 1        | 0.47%   |
| WDC WDS250G2B0A 250GB SSD         | 1        | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD  | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 58       | 96     | 50.43%  |
| WDC                 | 32       | 44     | 27.83%  |
| Samsung Electronics | 12       | 16     | 10.43%  |
| Toshiba             | 10       | 11     | 8.7%    |
| Hitachi             | 2        | 4      | 1.74%   |
| KESU                | 1        | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 14       | 15     | 31.82%  |
| WDC                 | 10       | 16     | 22.73%  |
| Hewlett-Packard     | 4        | 4      | 9.09%   |
| Crucial             | 4        | 6      | 9.09%   |
| PNY                 | 3        | 3      | 6.82%   |
| A-DATA Technology   | 3        | 3      | 6.82%   |
| Team                | 2        | 2      | 4.55%   |
| Samsung Electronics | 1        | 1      | 2.27%   |
| Maxone              | 1        | 2      | 2.27%   |
| LITEON              | 1        | 1      | 2.27%   |
| Intel               | 1        | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 97       | 172    | 58.79%  |
| SSD     | 40       | 54     | 24.24%  |
| NVMe    | 26       | 34     | 15.76%  |
| MMC     | 1        | 1      | 0.61%   |
| Unknown | 1        | 1      | 0.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 113      | 224    | 79.02%  |
| NVMe | 26       | 34     | 18.18%  |
| SAS  | 3        | 3      | 2.1%    |
| MMC  | 1        | 1      | 0.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 85       | 138    | 57.43%  |
| 0.51-1.0   | 42       | 55     | 28.38%  |
| 1.01-2.0   | 13       | 22     | 8.78%   |
| 3.01-4.0   | 4        | 5      | 2.7%    |
| 4.01-10.0  | 3        | 5      | 2.03%   |
| 2.01-3.0   | 1        | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 37       | 28.03%  |
| 501-1000       | 21       | 15.91%  |
| 101-250        | 20       | 15.15%  |
| 51-100         | 11       | 8.33%   |
| 2001-3000      | 10       | 7.58%   |
| 1-20           | 10       | 7.58%   |
| 1001-2000      | 8        | 6.06%   |
| More than 3000 | 6        | 4.55%   |
| 21-50          | 5        | 3.79%   |
| Unknown        | 4        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 51       | 37.78%  |
| 21-50          | 20       | 14.81%  |
| 251-500        | 17       | 12.59%  |
| 101-250        | 14       | 10.37%  |
| 51-100         | 10       | 7.41%   |
| 501-1000       | 8        | 5.93%   |
| 1001-2000      | 7        | 5.19%   |
| More than 3000 | 4        | 2.96%   |
| Unknown        | 4        | 2.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 13.64%  |
| Seagate ST1000DM003-9YN162 1TB    | 3        | 3      | 13.64%  |
| Seagate ST3500418AS 500GB         | 2        | 2      | 9.09%   |
| WDC WD800BD-00MRA1 80GB           | 1        | 1      | 4.55%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 4.55%   |
| WDC WD3200AAJS-56M0A0 320GB       | 1        | 1      | 4.55%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 1      | 4.55%   |
| Seagate ST980811AS 80GB           | 1        | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 4.55%   |
| Seagate ST500DM002-9YN14C 500GB   | 1        | 1      | 4.55%   |
| Seagate ST3250820AS 250GB         | 1        | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB    | 1        | 1      | 4.55%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 4.55%   |
| Samsung Electronics SP1644N 160GB | 1        | 1      | 4.55%   |
| Samsung Electronics HD161HJ 160GB | 1        | 2      | 4.55%   |
| Hitachi HTS545032B9A300 320GB     | 1        | 1      | 4.55%   |
| A-DATA Technology SP550 240GB SSD | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 14     | 63.64%  |
| WDC                 | 4        | 4      | 18.18%  |
| Samsung Electronics | 2        | 3      | 9.09%   |
| Hitachi             | 1        | 1      | 4.55%   |
| A-DATA Technology   | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 14     | 66.67%  |
| WDC                 | 4        | 4      | 19.05%  |
| Samsung Electronics | 2        | 3      | 9.52%   |
| Hitachi             | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 22     | 94.74%  |
| SSD  | 1        | 1      | 5.26%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 74       | 160    | 54.81%  |
| Works    | 42       | 79     | 31.11%  |
| Malfunc  | 19       | 23     | 14.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 74       | 47.44%  |
| AMD                         | 41       | 26.28%  |
| Kingston Technology Company | 9        | 5.77%   |
| Marvell Technology Group    | 6        | 3.85%   |
| SanDisk                     | 5        | 3.21%   |
| Micron/Crucial Technology   | 5        | 3.21%   |
| Silicon Motion              | 4        | 2.56%   |
| Samsung Electronics         | 4        | 2.56%   |
| Nvidia                      | 4        | 2.56%   |
| JMicron Technology          | 3        | 1.92%   |
| LSI Logic / Symbios Logic   | 1        | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21       | 10.45%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12       | 5.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 4.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.98%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 3.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 3.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 3.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.99%   |
| Kingston Company Company Non-Volatile memory controller                                 | 5        | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.49%   |
| Micron/Crucial NVMe Controller                                                          | 4        | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.49%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.49%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.49%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 1.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 1%      |
| Nvidia MCP61 IDE                                                                        | 2        | 1%      |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1%      |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1%      |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 1%      |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 2        | 1%      |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1%      |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1%      |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 2        | 1%      |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 2        | 1%      |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1%      |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1%      |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1%      |
| AMD FCH SATA Controller D                                                               | 2        | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 87       | 55.06%  |
| IDE  | 41       | 25.95%  |
| NVMe | 26       | 16.46%  |
| RAID | 3        | 1.9%    |
| SCSI | 1        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 76       | 63.33%  |
| AMD    | 44       | 36.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 4.13%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 4.13%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 2.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 2.48%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 2.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.48%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 1.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.65%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.65%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.65%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.65%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 2        | 1.65%   |
| AMD Sempron 140 Processor                   | 2        | 1.65%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.65%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.65%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.65%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.65%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz         | 1        | 0.83%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.83%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.83%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 0.83%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.83%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.83%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.83%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.83%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 1        | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 0.83%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.83%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 17.5%   |
| Intel Core i7           | 14       | 11.67%  |
| Intel Core i3           | 8        | 6.67%   |
| AMD Ryzen 7             | 8        | 6.67%   |
| Intel Core 2 Duo        | 7        | 5.83%   |
| AMD Ryzen 5             | 7        | 5.83%   |
| AMD FX                  | 6        | 5%      |
| Intel Pentium           | 5        | 4.17%   |
| Intel Pentium Dual      | 4        | 3.33%   |
| AMD Ryzen 3             | 4        | 3.33%   |
| Intel Xeon              | 3        | 2.5%    |
| AMD A10                 | 3        | 2.5%    |
| Other                   | 2        | 1.67%   |
| Intel Pentium Dual-Core | 2        | 1.67%   |
| Intel Pentium 4         | 2        | 1.67%   |
| Intel Core 2 Quad       | 2        | 1.67%   |
| Intel Core 2            | 2        | 1.67%   |
| Intel Celeron           | 2        | 1.67%   |
| AMD Sempron             | 2        | 1.67%   |
| AMD Ryzen 9             | 2        | 1.67%   |
| AMD Phenom II X4        | 2        | 1.67%   |
| AMD A8                  | 2        | 1.67%   |
| Intel Pentium D         | 1        | 0.83%   |
| Intel Atom              | 1        | 0.83%   |
| AMD Phenom II X3        | 1        | 0.83%   |
| AMD Athlon X4           | 1        | 0.83%   |
| AMD Athlon II X3        | 1        | 0.83%   |
| AMD Athlon II X2        | 1        | 0.83%   |
| AMD Athlon 64 X2        | 1        | 0.83%   |
| AMD Athlon              | 1        | 0.83%   |
| AMD A6                  | 1        | 0.83%   |
| AMD A4                  | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 46       | 38.33%  |
| 2       | 38       | 31.67%  |
| 6       | 11       | 9.17%   |
| 8       | 10       | 8.33%   |
| 1       | 6        | 5%      |
| 3       | 4        | 3.33%   |
| 16      | 2        | 1.67%   |
| 20      | 1        | 0.83%   |
| 12      | 1        | 0.83%   |
| Unknown | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 120      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 62       | 51.67%  |
| 1       | 57       | 47.5%   |
| Unknown | 1        | 0.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 117      | 96.69%  |
| 64-bit         | 2        | 1.65%   |
| Unknown        | 2        | 1.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 12.1%   |
| 0x306a9    | 13       | 10.48%  |
| 0x306c3    | 8        | 6.45%   |
| 0x206a7    | 7        | 5.65%   |
| 0x08701021 | 7        | 5.65%   |
| 0x506e3    | 6        | 4.84%   |
| 0x1067a    | 6        | 4.84%   |
| 0x6fd      | 5        | 4.03%   |
| 0x06003106 | 4        | 3.23%   |
| 0x06000852 | 4        | 3.23%   |
| 0x010000c8 | 4        | 3.23%   |
| 0x6fb      | 3        | 2.42%   |
| 0xf64      | 2        | 1.61%   |
| 0xa0655    | 2        | 1.61%   |
| 0x906e9    | 2        | 1.61%   |
| 0x20655    | 2        | 1.61%   |
| 0x10676    | 2        | 1.61%   |
| 0x0a50000c | 2        | 1.61%   |
| 0x08701013 | 2        | 1.61%   |
| 0x08108109 | 2        | 1.61%   |
| 0x06001119 | 2        | 1.61%   |
| 0x010000c7 | 2        | 1.61%   |
| 0xf49      | 1        | 0.81%   |
| 0xa0671    | 1        | 0.81%   |
| 0xa0653    | 1        | 0.81%   |
| 0x906ed    | 1        | 0.81%   |
| 0x906ea    | 1        | 0.81%   |
| 0x806ec    | 1        | 0.81%   |
| 0x706a8    | 1        | 0.81%   |
| 0x6f6      | 1        | 0.81%   |
| 0x6f2      | 1        | 0.81%   |
| 0x406f1    | 1        | 0.81%   |
| 0x406c4    | 1        | 0.81%   |
| 0x206c2    | 1        | 0.81%   |
| 0x106e5    | 1        | 0.81%   |
| 0x0a201009 | 1        | 0.81%   |
| 0x08108102 | 1        | 0.81%   |
| 0x0810100b | 1        | 0.81%   |
| 0x0800820d | 1        | 0.81%   |
| 0x08001138 | 1        | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 13       | 10.83%  |
| Zen 2         | 11       | 9.17%   |
| Core          | 10       | 8.33%   |
| Penryn        | 9        | 7.5%    |
| SandyBridge   | 8        | 6.67%   |
| K10           | 8        | 6.67%   |
| Haswell       | 8        | 6.67%   |
| Piledriver    | 7        | 5.83%   |
| KabyLake      | 7        | 5.83%   |
| Skylake       | 6        | 5%      |
| Zen+          | 5        | 4.17%   |
| Steamroller   | 5        | 4.17%   |
| Zen 3         | 3        | 2.5%    |
| Westmere      | 3        | 2.5%    |
| NetBurst      | 3        | 2.5%    |
| CometLake     | 3        | 2.5%    |
| Zen           | 2        | 1.67%   |
| Silvermont    | 1        | 0.83%   |
| Nehalem       | 1        | 0.83%   |
| K8 Hammer     | 1        | 0.83%   |
| K10 Llano     | 1        | 0.83%   |
| Icelake       | 1        | 0.83%   |
| Goldmont plus | 1        | 0.83%   |
| Bulldozer     | 1        | 0.83%   |
| Broadwell     | 1        | 0.83%   |
| Unknown       | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 46       | 36.22%  |
| Nvidia | 42       | 33.07%  |
| AMD    | 39       | 30.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 5.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 4.58%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 3.05%   |
| Intel HD Graphics 530                                                       | 4        | 3.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.29%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.29%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.29%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 2.29%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 2.29%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.29%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2.29%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.53%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.53%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.53%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 2        | 1.53%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.53%   |
| Nvidia GF108 [GeForce GT 440]                                               | 2        | 1.53%   |
| Intel HD Graphics 610                                                       | 2        | 1.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.53%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.53%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.53%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.53%   |
| AMD RV370 [Radeon X300]                                                     | 2        | 1.53%   |
| AMD RV370 [Radeon X300 SE]                                                  | 2        | 1.53%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.53%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.53%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.76%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 40       | 33.06%  |
| 1 x Intel      | 39       | 32.23%  |
| 1 x AMD        | 35       | 28.93%  |
| 2 x AMD        | 3        | 2.48%   |
| Intel + Nvidia | 2        | 1.65%   |
| 2 x Intel      | 1        | 0.83%   |
| Intel + AMD    | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 100      | 82.64%  |
| Proprietary | 19       | 15.7%   |
| Unknown     | 2        | 1.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 40.98%  |
| 1.01-2.0   | 23       | 18.85%  |
| 0.51-1.0   | 15       | 12.3%   |
| 0.01-0.5   | 12       | 9.84%   |
| 3.01-4.0   | 9        | 7.38%   |
| 7.01-8.0   | 7        | 5.74%   |
| 5.01-6.0   | 5        | 4.1%    |
| 8.01-16.0  | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 29       | 25.66%  |
| Samsung Electronics  | 28       | 24.78%  |
| AOC                  | 12       | 10.62%  |
| Hewlett-Packard      | 8        | 7.08%   |
| ViewSonic            | 5        | 4.42%   |
| Unknown              | 4        | 3.54%   |
| Lenovo               | 4        | 3.54%   |
| Dell                 | 4        | 3.54%   |
| Sony                 | 3        | 2.65%   |
| BenQ                 | 3        | 2.65%   |
| LG Electronics       | 2        | 1.77%   |
| ASUSTek Computer     | 2        | 1.77%   |
| Viotek               | 1        | 0.88%   |
| Panasonic            | 1        | 0.88%   |
| NEW                  | 1        | 0.88%   |
| Lenovo Group Limited | 1        | 0.88%   |
| JRY                  | 1        | 0.88%   |
| Hyundai ImageQuest   | 1        | 0.88%   |
| Huion                | 1        | 0.88%   |
| Gigabyte Technology  | 1        | 0.88%   |
| Eizo                 | 1        | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5        | 4.24%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch   | 3        | 2.54%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch          | 2        | 1.69%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2        | 1.69%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch   | 2        | 1.69%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                       | 2        | 1.69%   |
| Hewlett-Packard LCD Monitor HWP285A 1920x1080 470x270mm 21.3-inch      | 2        | 1.69%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                   | 2        | 1.69%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 1.69%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                    | 2        | 1.69%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                    | 2        | 1.69%   |
| Dell 3008WFP DEL4036 2560x1600 641x400mm 29.7-inch                     | 2        | 1.69%   |
| AOC 2239 AOC2239 1920x1080 477x268mm 21.5-inch                         | 2        | 1.69%   |
| Viotek FI24D VTK0238 2560x1440 530x290mm 23.8-inch                     | 1        | 0.85%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch          | 1        | 0.85%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch          | 1        | 0.85%   |
| ViewSonic LCD Monitor VSC7B2E 1920x1080 480x270mm 21.7-inch            | 1        | 0.85%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.85%   |
| Unknown LCD Monitor OOO TE-3190N 2560x1440                             | 1        | 0.85%   |
| Unknown LCD Monitor OOO MA2224W 1920x1080                              | 1        | 0.85%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                              | 1        | 0.85%   |
| Sony TV SNY2601 1360x768 710x400mm 32.1-inch                           | 1        | 0.85%   |
| Sony LCD Monitor TV 1360x768                                           | 1        | 0.85%   |
| Sony LCD Monitor TV                                                    | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x287mm 23.0-inch   | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch    | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch    | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch    | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch   | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM022E 1024x768 267x200mm 13.1-inch    | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 1        | 0.85%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch     | 1        | 0.85%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch     | 1        | 0.85%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 1        | 0.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1        | 0.85%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch      | 1        | 0.85%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch       | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0E8C 1920x1080 950x540mm 43.0-inch  | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1        | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 48       | 43.24%  |
| 1600x900 (HD+)    | 15       | 13.51%  |
| 1360x768          | 9        | 8.11%   |
| 1366x768 (WXGA)   | 8        | 7.21%   |
| 3840x2160 (4K)    | 6        | 5.41%   |
| 2560x1440 (QHD)   | 5        | 4.5%    |
| 1440x900 (WXGA+)  | 4        | 3.6%    |
| 1024x768 (XGA)    | 4        | 3.6%    |
| 1280x1024 (SXGA)  | 3        | 2.7%    |
| 3840x1080         | 2        | 1.8%    |
| 2560x1600         | 2        | 1.8%    |
| Unknown           | 2        | 1.8%    |
| 3440x1440         | 1        | 0.9%    |
| 2560x1080         | 1        | 0.9%    |
| 1920x1200 (WUXGA) | 1        | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 29       | 25.66%  |
| 23      | 13       | 11.5%   |
| 20      | 11       | 9.73%   |
| 18      | 10       | 8.85%   |
| Unknown | 9        | 7.96%   |
| 27      | 7        | 6.19%   |
| 19      | 7        | 6.19%   |
| 31      | 4        | 3.54%   |
| 24      | 4        | 3.54%   |
| 17      | 4        | 3.54%   |
| 15      | 4        | 3.54%   |
| 48      | 3        | 2.65%   |
| 32      | 2        | 1.77%   |
| 30      | 2        | 1.77%   |
| 84      | 1        | 0.88%   |
| 43      | 1        | 0.88%   |
| 34      | 1        | 0.88%   |
| 13      | 1        | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 54       | 48.65%  |
| 501-600     | 23       | 20.72%  |
| Unknown     | 9        | 8.11%   |
| 301-350     | 7        | 6.31%   |
| 601-700     | 6        | 5.41%   |
| 701-800     | 3        | 2.7%    |
| 351-400     | 3        | 2.7%    |
| 1001-1500   | 3        | 2.7%    |
| 201-300     | 1        | 0.9%    |
| 1501-2000   | 1        | 0.9%    |
| 901-1000    | 1        | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 75.47%  |
| Unknown | 9        | 8.49%   |
| 16/10   | 7        | 6.6%    |
| 5/4     | 5        | 4.72%   |
| 4/3     | 4        | 3.77%   |
| 21/9    | 1        | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 33       | 30%     |
| 151-200        | 27       | 24.55%  |
| 141-150        | 13       | 11.82%  |
| 351-500        | 9        | 8.18%   |
| Unknown        | 9        | 8.18%   |
| 301-350        | 7        | 6.36%   |
| More than 1000 | 4        | 3.64%   |
| 101-110        | 4        | 3.64%   |
| 81-90          | 1        | 0.91%   |
| 251-300        | 1        | 0.91%   |
| 131-140        | 1        | 0.91%   |
| 501-1000       | 1        | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 53       | 49.07%  |
| 101-120 | 36       | 33.33%  |
| Unknown | 9        | 8.33%   |
| 1-50    | 8        | 7.41%   |
| 161-240 | 1        | 0.93%   |
| 121-160 | 1        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 89.34%  |
| 2     | 10       | 8.2%    |
| 0     | 2        | 1.64%   |
| 3     | 1        | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 77       | 48.73%  |
| Intel                           | 42       | 26.58%  |
| Qualcomm Atheros                | 11       | 6.96%   |
| TP-Link                         | 6        | 3.8%    |
| Ralink Technology               | 4        | 2.53%   |
| Qualcomm Atheros Communications | 4        | 2.53%   |
| Nvidia                          | 4        | 2.53%   |
| Huawei Technologies             | 2        | 1.27%   |
| D-Link System                   | 2        | 1.27%   |
| Broadcom Limited                | 2        | 1.27%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.63%   |
| Microsoft                       | 1        | 0.63%   |
| D-Link                          | 1        | 0.63%   |
| ASIX Electronics                | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 62       | 36.26%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 3.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 3.51%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 3.51%   |
| Intel I211 Gigabit Network Connection                                  | 5        | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 2.92%   |
| Qualcomm Atheros AR9271 802.11n                                        | 4        | 2.34%   |
| TP-Link 802.11n NIC                                                    | 3        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 1.75%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.75%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 1.75%   |
| Intel 82578DC Gigabit Network Connection                               | 3        | 1.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 1.17%   |
| Intel Wireless 7265                                                    | 2        | 1.17%   |
| Huawei STK-L21                                                         | 2        | 1.17%   |
| ZTE WCDMA MSM Spreadtrum Phone                                         | 1        | 0.58%   |
| TP-Link USB 10/100 LAN                                                 | 1        | 0.58%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                | 1        | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.58%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.58%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 1        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 0.58%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 0.58%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 0.58%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 1        | 0.58%   |
| Nvidia MCP67 Ethernet                                                  | 1        | 0.58%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 1        | 0.58%   |
| Intel Wireless 7260                                                    | 1        | 0.58%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 27.5%   |
| Qualcomm Atheros                | 7        | 17.5%   |
| Realtek Semiconductor           | 6        | 15%     |
| TP-Link                         | 5        | 12.5%   |
| Ralink Technology               | 4        | 10%     |
| Qualcomm Atheros Communications | 4        | 10%     |
| Microsoft                       | 1        | 2.5%    |
| D-Link System                   | 1        | 2.5%    |
| D-Link                          | 1        | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                        | 4        | 10%     |
| TP-Link 802.11n NIC                                                    | 3        | 7.5%    |
| Ralink MT7601U Wireless Adapter                                        | 3        | 7.5%    |
| Intel Wi-Fi 6 AX200                                                    | 3        | 7.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 5%      |
| Intel Wireless 7265                                                    | 2        | 5%      |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                | 1        | 2.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 2.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 2.5%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 1        | 2.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 2.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 2.5%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 2.5%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 1        | 2.5%    |
| Microsoft Xbox 360 Wireless Adapter                                    | 1        | 2.5%    |
| Intel Wireless 7260                                                    | 1        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 2.5%    |
| Intel Centrino Wireless-N 2230                                         | 1        | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 1        | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1        | 2.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 2.5%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]   | 1        | 2.5%    |
| D-Link DWL-G132 [Atheros AR5523]                                       | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 75       | 58.59%  |
| Intel                      | 36       | 28.13%  |
| Qualcomm Atheros           | 5        | 3.91%   |
| Nvidia                     | 4        | 3.13%   |
| Huawei Technologies        | 2        | 1.56%   |
| Broadcom Limited           | 2        | 1.56%   |
| ZTE WCDMA Technologies MSM | 1        | 0.78%   |
| TP-Link                    | 1        | 0.78%   |
| D-Link System              | 1        | 0.78%   |
| ASIX Electronics           | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62       | 47.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 4.58%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 4.58%   |
| Intel I211 Gigabit Network Connection                             | 5        | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 3.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 2.29%   |
| Nvidia MCP61 Ethernet                                             | 3        | 2.29%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 2.29%   |
| Intel 82578DC Gigabit Network Connection                          | 3        | 2.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.53%   |
| Huawei STK-L21                                                    | 2        | 1.53%   |
| ZTE WCDMA MSM Spreadtrum Phone                                    | 1        | 0.76%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.76%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.76%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                             | 1        | 0.76%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.76%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.76%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.76%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82567LM-2 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.76%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 0.76%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.76%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.76%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 0.76%   |
| ASIX AX88772A Fast Ethernet                                       | 1        | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 75.32%  |
| WiFi     | 39       | 24.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 101      | 80.16%  |
| WiFi     | 25       | 19.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 76.86%  |
| 2     | 26       | 21.49%  |
| 3     | 2        | 1.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 100      | 83.33%  |
| Yes  | 20       | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 10       | 41.67%  |
| Cambridge Silicon Radio    | 9        | 37.5%   |
| Realtek Semiconductor      | 2        | 8.33%   |
| TRENDnet                   | 1        | 4.17%   |
| TP-Link                    | 1        | 4.17%   |
| Integrated System Solution | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 9        | 37.5%   |
| Intel AX200 Bluetooth                                 | 3        | 12.5%   |
| Intel Bluetooth wireless interface                    | 2        | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 8.33%   |
| TRENDnet TBW-108UB USB Adapter                        | 1        | 4.17%   |
| TP-Link UB500 Adapter                                 | 1        | 4.17%   |
| Realtek RTL8723B Bluetooth                            | 1        | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 4.17%   |
| Intel AX201 Bluetooth                                 | 1        | 4.17%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 72       | 40.22%  |
| AMD                 | 53       | 29.61%  |
| Nvidia              | 43       | 24.02%  |
| Texas Instruments   | 2        | 1.12%   |
| Microsoft           | 2        | 1.12%   |
| C-Media Electronics | 2        | 1.12%   |
| Samson Technologies | 1        | 0.56%   |
| Logitech            | 1        | 0.56%   |
| Kingston Technology | 1        | 0.56%   |
| Creative Labs       | 1        | 0.56%   |
| Chicony Electronics | 1        | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12       | 5.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 5.26%   |
| AMD Starship/Matisse HD Audio Controller                                          | 11       | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 11       | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 3.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8        | 3.83%   |
| AMD FCH Azalia Controller                                                         | 8        | 3.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 3.35%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 3.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 3.35%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 2.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5        | 2.39%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.91%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.91%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.44%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3        | 1.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.44%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 3        | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.44%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 1.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.44%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 0.96%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.96%   |
| Microsoft LifeChat LX-3000 Headset                                                | 2        | 0.96%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.96%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 0.96%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.96%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 0.96%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.96%   |
| Samson Technologies Q2U handheld mic with XLR                                     | 1        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 32       | 46.38%  |
| Samsung Electronics          | 8        | 11.59%  |
| Unknown                      | 5        | 7.25%   |
| Corsair                      | 5        | 7.25%   |
| Micron Technology            | 4        | 5.8%    |
| SK hynix                     | 3        | 4.35%   |
| Team                         | 2        | 2.9%    |
| Crucial                      | 2        | 2.9%    |
| Unknown (0x7FA8000000000000) | 1        | 1.45%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 1.45%   |
| Qumo                         | 1        | 1.45%   |
| Princeton                    | 1        | 1.45%   |
| Nanya Technology             | 1        | 1.45%   |
| Hewlett-Packard              | 1        | 1.45%   |
| GeIL                         | 1        | 1.45%   |
| A-DATA Technology            | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 3        | 4%      |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s         | 2        | 2.67%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 2        | 2.67%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s             | 2        | 2.67%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s         | 2        | 2.67%   |
| Kingston RAM CL16-18-18 D4-3200 8192MB DIMM DDR4 3200MT/s       | 2        | 2.67%   |
| Kingston RAM 99U5403-436.A00LF 8GB DIMM DDR3 1333MT/s           | 2        | 2.67%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM DDR3 1333MT/s           | 2        | 2.67%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                      | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR2                                | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 1        | 1.33%   |
| Unknown RAM Module 1GB DIMM 800MT/s                             | 1        | 1.33%   |
| Unknown (0x7FA8000000000000) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 1.33%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s              | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s             | 1        | 1.33%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s            | 1        | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1        | 1.33%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                       | 1        | 1.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s             | 1        | 1.33%   |
| Samsung RAM M378B5673EH1-CF8 2GB DIMM DDR3 1067MT/s             | 1        | 1.33%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s          | 1        | 1.33%   |
| Samsung RAM M378B5173EB0 4096MB DIMM DDR3 1600MT/s              | 1        | 1.33%   |
| Samsung RAM M378B5173DB0 4GB DIMM DDR3 1600MT/s                 | 1        | 1.33%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s    | 1        | 1.33%   |
| Samsung RAM HMT351U6EFR8A-PB 8GB DIMM DDR3 1333MT/s             | 1        | 1.33%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                       | 1        | 1.33%   |
| Princeton RAM Module 512MB DIMM DDR2 533MT/s                    | 1        | 1.33%   |
| Nanya RAM Module 2GB DIMM DDR2 667MT/s                          | 1        | 1.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 1        | 1.33%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s             | 1        | 1.33%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s             | 1        | 1.33%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s           | 1        | 1.33%   |
| Kingston RAM Module 512MB DIMM DDR2 533MT/s                     | 1        | 1.33%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.33%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 1.33%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s          | 1        | 1.33%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s             | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 44.07%  |
| DDR4    | 23       | 38.98%  |
| DDR2    | 6        | 10.17%  |
| Unknown | 2        | 3.39%   |
| SDRAM   | 1        | 1.69%   |
| LPDDR3  | 1        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 56       | 94.92%  |
| SODIMM       | 2        | 3.39%   |
| Row Of Chips | 1        | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 37.88%  |
| 4096  | 17       | 25.76%  |
| 2048  | 12       | 18.18%  |
| 16384 | 6        | 9.09%   |
| 32768 | 2        | 3.03%   |
| 1024  | 2        | 3.03%   |
| 512   | 2        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 13       | 19.4%   |
| 1600    | 10       | 14.93%  |
| 2133    | 7        | 10.45%  |
| 3200    | 5        | 7.46%   |
| 3600    | 3        | 4.48%   |
| 3466    | 3        | 4.48%   |
| 2667    | 3        | 4.48%   |
| 2400    | 2        | 2.99%   |
| 1800    | 2        | 2.99%   |
| 800     | 2        | 2.99%   |
| 533     | 2        | 2.99%   |
| Unknown | 2        | 2.99%   |
| 3800    | 1        | 1.49%   |
| 3733    | 1        | 1.49%   |
| 3400    | 1        | 1.49%   |
| 3151    | 1        | 1.49%   |
| 3100    | 1        | 1.49%   |
| 2733    | 1        | 1.49%   |
| 2200    | 1        | 1.49%   |
| 2134    | 1        | 1.49%   |
| 1867    | 1        | 1.49%   |
| 1866    | 1        | 1.49%   |
| 1067    | 1        | 1.49%   |
| 667     | 1        | 1.49%   |
| 400     | 1        | 1.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 33.33%  |
| Star Micronics     | 1        | 16.67%  |
| Seiko Epson        | 1        | 16.67%  |
| Hewlett-Packard    | 1        | 16.67%  |
| Canon              | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Brother DCP-T310                  | 2        | 33.33%  |
| Star Micronics TUP592 (STR_T-001) | 1        | 16.67%  |
| Seiko Epson L3250 Series          | 1        | 16.67%  |
| HP PSC 1400                       | 1        | 16.67%  |
| Canon PIXMA MG3600 Series         | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP ScanJet 2400c       | 1        | 50%     |
| Canon CanoScan LIDE 25 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Microdia                | 6        | 21.43%  |
| Logitech                | 5        | 17.86%  |
| Z-Star Microelectronics | 4        | 14.29%  |
| Microsoft               | 4        | 14.29%  |
| Generalplus Technology  | 2        | 7.14%   |
| Cubeternet              | 2        | 7.14%   |
| Xiongmai                | 1        | 3.57%   |
| Samsung Electronics     | 1        | 3.57%   |
| Realtek Semiconductor   | 1        | 3.57%   |
| Aveo Technology         | 1        | 3.57%   |
| Apple                   | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                 | 2        | 7.14%   |
| Microdia USB 2.0 Camera                                             | 2        | 7.14%   |
| Microdia Camera                                                     | 2        | 7.14%   |
| Logitech C920 PRO HD Webcam                                         | 2        | 7.14%   |
| Generalplus GENERAL WEBCAM                                          | 2        | 7.14%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 2        | 7.14%   |
| Z-Star Vimicro USB Camera (Altair)                                  | 1        | 3.57%   |
| Z-Star Venus USB2.0 Camera                                          | 1        | 3.57%   |
| Z-Star Sirius USB2.0 Camera                                         | 1        | 3.57%   |
| Z-Star Integrated Camera                                            | 1        | 3.57%   |
| Xiongmai web camera                                                 | 1        | 3.57%   |
| Samsung Galaxy A5 (MTP)                                             | 1        | 3.57%   |
| Realtek Laptop_Integrated_Webcam_FHD                                | 1        | 3.57%   |
| Microsoft MicrosoftÂ LifeCam Cinema                                | 1        | 3.57%   |
| Microsoft LifeCam Cinema                                            | 1        | 3.57%   |
| Microdia Webcam Vitade AF                                           | 1        | 3.57%   |
| Microdia Defender G-Lens 2577 HD720p Camera                         | 1        | 3.57%   |
| Logitech Webcam C270                                                | 1        | 3.57%   |
| Logitech C505e HD Webcam                                            | 1        | 3.57%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 3.57%   |
| Aveo USB2.0 Camera                                                  | 1        | 3.57%   |
| Apple iPhone5/5C/5S/6                                               | 1        | 3.57%   |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Yubico.com | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 109      | 89.34%  |
| 1     | 10       | 8.2%    |
| 3     | 2        | 1.64%   |
| 2     | 1        | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Graphics card       | 5        | 38.46%  |
| Net/wireless        | 2        | 15.38%  |
| Unassigned class    | 1        | 7.69%   |
| Sound               | 1        | 7.69%   |
| Network             | 1        | 7.69%   |
| Net/ethernet        | 1        | 7.69%   |
| Firewire controller | 1        | 7.69%   |
| Camera              | 1        | 7.69%   |

