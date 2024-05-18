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

Total: 249

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Intel    | MAHOBAY                     | [da659a0ae5](https://linux-hardware.org/?probe=da659a0ae5) | Apr 23, 2024 |
| Intel    | MAHOBAY                     | [9cd8f52e56](https://linux-hardware.org/?probe=9cd8f52e56) | Apr 23, 2024 |
| MSI      | PRO Z690-A DDR4             | [d60ebaaa13](https://linux-hardware.org/?probe=d60ebaaa13) | Apr 15, 2024 |
| Gigabyte | GA-880GM-USB3               | [77bf8490e6](https://linux-hardware.org/?probe=77bf8490e6) | Mar 28, 2024 |
| Quanta   | 2AC7 011                    | [b4886173ba](https://linux-hardware.org/?probe=b4886173ba) | Feb 24, 2024 |
| MSI      | MAG B550M MORTAR            | [01b17246ec](https://linux-hardware.org/?probe=01b17246ec) | Feb 23, 2024 |
| Gigabyte | B460M DS3H V2               | [c0d8b37026](https://linux-hardware.org/?probe=c0d8b37026) | Feb 21, 2024 |
| ASUSTek  | PRIME B250M-A               | [48be70ca91](https://linux-hardware.org/?probe=48be70ca91) | Feb 18, 2024 |
| Gigabyte | F2A68HM-H                   | [f8f33cacdf](https://linux-hardware.org/?probe=f8f33cacdf) | Feb 13, 2024 |
| Quanta   | 2AC7 011                    | [2fbec21ee5](https://linux-hardware.org/?probe=2fbec21ee5) | Feb 12, 2024 |
| ASRock   | Z390 Pro4                   | [aa34bf9cf1](https://linux-hardware.org/?probe=aa34bf9cf1) | Feb 07, 2024 |
| ASRock   | Z390 Pro4                   | [3ced2256f7](https://linux-hardware.org/?probe=3ced2256f7) | Feb 07, 2024 |
| Dell     | 05XGC8 A01                  | [29ae38936a](https://linux-hardware.org/?probe=29ae38936a) | Feb 02, 2024 |
| ASUSTek  | ROG STRIX B350-F GAMING     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| MSI      | PRO H610M-G DDR4            | [3f4325d337](https://linux-hardware.org/?probe=3f4325d337) | Jan 29, 2024 |
| Gigabyte | AX370M-Gaming 3-CF          | [ff5718cb34](https://linux-hardware.org/?probe=ff5718cb34) | Jan 20, 2024 |
| MSI      | MAG B650M MORTAR WIFI       | [947096fa7f](https://linux-hardware.org/?probe=947096fa7f) | Jan 16, 2024 |
| MSI      | H310M PRO-M2 PLUS           | [89b8dbd2bb](https://linux-hardware.org/?probe=89b8dbd2bb) | Jan 13, 2024 |
| ASRock   | X570 Taichi Razer Editio... | [08d900cdbb](https://linux-hardware.org/?probe=08d900cdbb) | Dec 27, 2023 |
| Gigabyte | AX370M-Gaming 3-CF          | [c4fe258ada](https://linux-hardware.org/?probe=c4fe258ada) | Dec 24, 2023 |
| Gigabyte | B75M-D3H                    | [f306ab4590](https://linux-hardware.org/?probe=f306ab4590) | Dec 17, 2023 |
| Gigabyte | F2A68HM-H                   | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| Gigabyte | B450M S2H                   | [5dcf20cb88](https://linux-hardware.org/?probe=5dcf20cb88) | Dec 04, 2023 |
| Gigabyte | B450M S2H                   | [2f07094763](https://linux-hardware.org/?probe=2f07094763) | Dec 04, 2023 |
| ASRock   | H310CM-HDV/M.2              | [4b91971e62](https://linux-hardware.org/?probe=4b91971e62) | Dec 01, 2023 |
| Gigabyte | B75M-D3H                    | [5be7c208c3](https://linux-hardware.org/?probe=5be7c208c3) | Nov 20, 2023 |
| HP       | 18E7                        | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP       | 18E7                        | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| MSI      | PRO B550M-P GEN3            | [8a9f37b293](https://linux-hardware.org/?probe=8a9f37b293) | Oct 31, 2023 |
| MSI      | B250M PRO-VDH               | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| Gigabyte | AX370M-Gaming 3-CF          | [dbc150b2b5](https://linux-hardware.org/?probe=dbc150b2b5) | Oct 13, 2023 |
| GIADA    | Braswell JHS60S             | [ed113a0bc0](https://linux-hardware.org/?probe=ed113a0bc0) | Oct 08, 2023 |
| ASRock   | G31M-S                      | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| ASUSTek  | V230IC                      | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [9d3a7e1014](https://linux-hardware.org/?probe=9d3a7e1014) | Sep 14, 2023 |
| HP       | 8433 11                     | [6160c13209](https://linux-hardware.org/?probe=6160c13209) | Sep 12, 2023 |
| HP       | 8433 11                     | [2fbe297e6c](https://linux-hardware.org/?probe=2fbe297e6c) | Sep 12, 2023 |
| ASUSTek  | ROG STRIX B460-H GAMING     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| Gigabyte | X570 AORUS MASTER           | [89e3ba3d7d](https://linux-hardware.org/?probe=89e3ba3d7d) | Aug 28, 2023 |
| Gigabyte | X570 AORUS MASTER           | [0150e826ac](https://linux-hardware.org/?probe=0150e826ac) | Aug 28, 2023 |
| Gigabyte | F2A68HM-H                   | [82923ee337](https://linux-hardware.org/?probe=82923ee337) | Aug 18, 2023 |
| ASRock   | B460M Pro4                  | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| MSI      | MAG B550M MORTAR            | [87d27d2a99](https://linux-hardware.org/?probe=87d27d2a99) | Aug 04, 2023 |
| Gigabyte | GA-880GM-UD2H               | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| HP       | 83EE                        | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| ASUSTek  | B85M-G R2.0                 | [477ec4d403](https://linux-hardware.org/?probe=477ec4d403) | Jul 11, 2023 |
| HP       | 1493                        | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| Gigabyte | GA-78LMT-USB3 SEx           | [99341c9ba0](https://linux-hardware.org/?probe=99341c9ba0) | Jun 23, 2023 |
| Gigabyte | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| AMI      | Cherry Trail CR             | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| Gigabyte | GA-78LMT-USB3 SEx           | [d981de6f45](https://linux-hardware.org/?probe=d981de6f45) | Jun 06, 2023 |
| ASUSTek  | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| HP       | 1493                        | [b7432a020a](https://linux-hardware.org/?probe=b7432a020a) | Jun 04, 2023 |
| MSI      | MAG B550 TOMAHAWK           | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| MSI      | A68HM-E33 V2                | [24775c04a5](https://linux-hardware.org/?probe=24775c04a5) | May 30, 2023 |
| MSI      | A68HM-E33 V2                | [d6a2216b0f](https://linux-hardware.org/?probe=d6a2216b0f) | May 30, 2023 |
| ASUSTek  | PRIME X299-A                | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| ASUSTek  | TUF B365M-PLUS GAMING       | [7c32eb6bf9](https://linux-hardware.org/?probe=7c32eb6bf9) | Apr 11, 2023 |
| ASUSTek  | TUF B365M-PLUS GAMING       | [cabf7adac2](https://linux-hardware.org/?probe=cabf7adac2) | Apr 11, 2023 |
| MSI      | A320M-A PRO MAX             | [8c33d7498d](https://linux-hardware.org/?probe=8c33d7498d) | Apr 05, 2023 |
| HP       | 1850                        | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| Gigabyte | B75M-D3H                    | [871c53d3f3](https://linux-hardware.org/?probe=871c53d3f3) | Mar 31, 2023 |
| ASUSTek  | PRIME A320M-K               | [a0ac521beb](https://linux-hardware.org/?probe=a0ac521beb) | Mar 07, 2023 |
| Gigabyte | B360M DS3H                  | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Gigabyte | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Intel    | H61                         | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| ASUSTek  | PRIME B550M-A               | [2e458676e4](https://linux-hardware.org/?probe=2e458676e4) | Feb 01, 2023 |
| Lenovo   | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| HP       | 1850                        | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| MSI      | B350M GAMING PRO            | [df317ef3c8](https://linux-hardware.org/?probe=df317ef3c8) | Jan 11, 2023 |
| Gigabyte | B450M S2H                   | [afd3f452a1](https://linux-hardware.org/?probe=afd3f452a1) | Jan 07, 2023 |
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
| Ubuntu 20.04                 | 24       | 12.97%  |
| Ubuntu 22.04                 | 12       | 6.49%   |
| Ubuntu 18.04                 | 11       | 5.95%   |
| OpenMandriva 4.3             | 9        | 4.86%   |
| OpenMandriva 4.2             | 7        | 3.78%   |
| Manjaro                      | 5        | 2.7%    |
| Zorin 15                     | 4        | 2.16%   |
| Ubuntu 19.10                 | 4        | 2.16%   |
| Linux Mint 20.1              | 4        | 2.16%   |
| Linux Mint 19.3              | 4        | 2.16%   |
| Debian 11                    | 4        | 2.16%   |
| Zorin 17                     | 3        | 1.62%   |
| Ubuntu 23.04                 | 3        | 1.62%   |
| Ubuntu 21.10                 | 3        | 1.62%   |
| Linux Mint 21.2              | 3        | 1.62%   |
| Kubuntu 20.04                | 3        | 1.62%   |
| KDE neon 22.04               | 3        | 1.62%   |
| Debian 12                    | 3        | 1.62%   |
| ROSA R9                      | 2        | 1.08%   |
| ROSA R8                      | 2        | 1.08%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.08%   |
| OpenMandriva 5.0             | 2        | 1.08%   |
| OpenMandriva 23.03           | 2        | 1.08%   |
| OpenMandriva 23.01           | 2        | 1.08%   |
| Linux Mint 19.2              | 2        | 1.08%   |
| Kubuntu 22.04                | 2        | 1.08%   |
| KDE neon 20.04               | 2        | 1.08%   |
| Fedora 38                    | 2        | 1.08%   |
| Endless 3.5.7                | 2        | 1.08%   |
| Debian                       | 2        | 1.08%   |
| CentOS 8                     | 2        | 1.08%   |
| Arch Rolling                 | 2        | 1.08%   |
| Zorin 16                     | 1        | 0.54%   |
| Xubuntu 23.04                | 1        | 0.54%   |
| Xubuntu 20.04                | 1        | 0.54%   |
| Xubuntu 18.04                | 1        | 0.54%   |
| Xero Rolling                 | 1        | 0.54%   |
| Ubuntu Unity 18.04           | 1        | 0.54%   |
| Ubuntu MATE 22.04            | 1        | 0.54%   |
| Ubuntu MATE 21.04            | 1        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 53       | 30.11%  |
| OpenMandriva | 24       | 13.64%  |
| Linux Mint   | 16       | 9.09%   |
| Debian       | 10       | 5.68%   |
| Zorin        | 8        | 4.55%   |
| ROSA         | 8        | 4.55%   |
| Manjaro      | 6        | 3.41%   |
| Kubuntu      | 6        | 3.41%   |
| Ubuntu MATE  | 5        | 2.84%   |
| KDE neon     | 5        | 2.84%   |
| Fedora       | 5        | 2.84%   |
| openSUSE     | 4        | 2.27%   |
| Xubuntu      | 3        | 1.7%    |
| Lubuntu      | 3        | 1.7%    |
| Linux Lite   | 3        | 1.7%    |
| Arch         | 3        | 1.7%    |
| Endless      | 2        | 1.14%   |
| CentOS       | 2        | 1.14%   |
| Xero         | 1        | 0.57%   |
| Ubuntu Unity | 1        | 0.57%   |
| SteamOS      | 1        | 0.57%   |
| Q4OS         | 1        | 0.57%   |
| Pop!_OS      | 1        | 0.57%   |
| Peppermint   | 1        | 0.57%   |
| Parrot       | 1        | 0.57%   |
| Feren OS     | 1        | 0.57%   |
| ArcoLinux    | 1        | 0.57%   |
| antiX        | 1        | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003         | 8        | 3.94%   |
| 5.10.14-desktop-1omv4002        | 7        | 3.45%   |
| 5.3.0-40-generic                | 5        | 2.46%   |
| 6.5.0-15-generic                | 4        | 1.97%   |
| 5.4.0-70-generic                | 3        | 1.48%   |
| 5.4.0-66-generic                | 3        | 1.48%   |
| 5.4.0-52-generic                | 3        | 1.48%   |
| 5.4.0-37-generic                | 3        | 1.48%   |
| 5.4.0-31-generic                | 3        | 1.48%   |
| 5.11.0-40-generic               | 3        | 1.48%   |
| 4.18.0-15-generic               | 3        | 1.48%   |
| 6.6.2-desktop-1omv2390          | 2        | 0.99%   |
| 6.2.6-desktop-1omv2390          | 2        | 0.99%   |
| 6.2.0-20-generic                | 2        | 0.99%   |
| 6.1.1-desktop-1omv2290          | 2        | 0.99%   |
| 5.8.0-48-generic                | 2        | 0.99%   |
| 5.4.0-58-generic                | 2        | 0.99%   |
| 5.4.0-40-generic                | 2        | 0.99%   |
| 5.4.0-29-generic                | 2        | 0.99%   |
| 5.4.0-28-generic                | 2        | 0.99%   |
| 5.3.0-46-generic                | 2        | 0.99%   |
| 5.3.0-26-generic                | 2        | 0.99%   |
| 5.15.0-48-generic               | 2        | 0.99%   |
| 5.15.0-43-generic               | 2        | 0.99%   |
| 5.15.0-27-generic               | 2        | 0.99%   |
| 5.10.0-21-amd64                 | 2        | 0.99%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2        | 0.99%   |
| 4.15.0-54-generic               | 2        | 0.99%   |
| 4.15.0-112-generic              | 2        | 0.99%   |
| 6.7.5-arch1-1                   | 1        | 0.49%   |
| 6.6.3-arch1-1                   | 1        | 0.49%   |
| 6.5.0-9-generic                 | 1        | 0.49%   |
| 6.5.0-5-amd64                   | 1        | 0.49%   |
| 6.5.0-28-generic                | 1        | 0.49%   |
| 6.5.0-26-generic                | 1        | 0.49%   |
| 6.5.0-17-generic                | 1        | 0.49%   |
| 6.5.0-14-generic                | 1        | 0.49%   |
| 6.5.0-1011-oem                  | 1        | 0.49%   |
| 6.4.6-200.fc38.x86_64           | 1        | 0.49%   |
| 6.4.6-1-liquorix-amd64          | 1        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 31       | 16.58%  |
| 5.15.0  | 17       | 9.09%   |
| 6.5.0   | 11       | 5.88%   |
| 5.3.0   | 11       | 5.88%   |
| 4.15.0  | 10       | 5.35%   |
| 5.16.7  | 8        | 4.28%   |
| 5.10.14 | 7        | 3.74%   |
| 5.8.0   | 6        | 3.21%   |
| 5.13.0  | 6        | 3.21%   |
| 4.18.0  | 6        | 3.21%   |
| 6.2.0   | 5        | 2.67%   |
| 5.11.0  | 5        | 2.67%   |
| 5.10.0  | 5        | 2.67%   |
| 6.2.6   | 3        | 1.6%    |
| 6.1.1   | 3        | 1.6%    |
| 5.19.0  | 3        | 1.6%    |
| 6.6.2   | 2        | 1.07%   |
| 6.4.6   | 2        | 1.07%   |
| 6.1.0   | 2        | 1.07%   |
| 5.3.18  | 2        | 1.07%   |
| 5.17.1  | 2        | 1.07%   |
| 4.9.20  | 2        | 1.07%   |
| 6.7.5   | 1        | 0.53%   |
| 6.6.3   | 1        | 0.53%   |
| 6.4.2   | 1        | 0.53%   |
| 6.4.15  | 1        | 0.53%   |
| 6.4.11  | 1        | 0.53%   |
| 6.3.5   | 1        | 0.53%   |
| 6.3.2   | 1        | 0.53%   |
| 6.3.0   | 1        | 0.53%   |
| 6.1.21  | 1        | 0.53%   |
| 6.1.20  | 1        | 0.53%   |
| 6.0.5   | 1        | 0.53%   |
| 6.0.10  | 1        | 0.53%   |
| 5.9.11  | 1        | 0.53%   |
| 5.8.7   | 1        | 0.53%   |
| 5.7.9   | 1        | 0.53%   |
| 5.7.14  | 1        | 0.53%   |
| 5.6.19  | 1        | 0.53%   |
| 5.6.0   | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 33       | 17.65%  |
| 5.15    | 18       | 9.63%   |
| 5.10    | 16       | 8.56%   |
| 5.3     | 13       | 6.95%   |
| 6.5     | 11       | 5.88%   |
| 5.16    | 10       | 5.35%   |
| 4.15    | 10       | 5.35%   |
| 6.2     | 8        | 4.28%   |
| 6.1     | 7        | 3.74%   |
| 5.8     | 7        | 3.74%   |
| 5.13    | 6        | 3.21%   |
| 5.11    | 6        | 3.21%   |
| 4.18    | 6        | 3.21%   |
| 6.4     | 5        | 2.67%   |
| 5.19    | 5        | 2.67%   |
| 6.6     | 3        | 1.6%    |
| 6.3     | 3        | 1.6%    |
| 5.17    | 3        | 1.6%    |
| 4.9     | 3        | 1.6%    |
| 6.0     | 2        | 1.07%   |
| 5.7     | 2        | 1.07%   |
| 5.6     | 2        | 1.07%   |
| 4.1     | 2        | 1.07%   |
| 6.7     | 1        | 0.53%   |
| 5.9     | 1        | 0.53%   |
| 5.18    | 1        | 0.53%   |
| 5.0     | 1        | 0.53%   |
| 4.8     | 1        | 0.53%   |
| 4.4     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 162      | 95.29%  |
| i686   | 8        | 4.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 69       | 39.2%   |
| KDE5            | 44       | 25%     |
| XFCE            | 14       | 7.95%   |
| X-Cinnamon      | 14       | 7.95%   |
| Unknown         | 9        | 5.11%   |
| MATE            | 8        | 4.55%   |
| KDE4            | 5        | 2.84%   |
| LXQt            | 2        | 1.14%   |
| LXDE            | 2        | 1.14%   |
| Unity           | 1        | 0.57%   |
| qtile           | 1        | 0.57%   |
| KDE             | 1        | 0.57%   |
| icewm           | 1        | 0.57%   |
| i3              | 1        | 0.57%   |
| Hyprland        | 1        | 0.57%   |
| GNOME Flashback | 1        | 0.57%   |
| Budgie          | 1        | 0.57%   |
| awesome         | 1        | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 140      | 80%     |
| Wayland | 28       | 16%     |
| Unknown | 7        | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 81       | 45.76%  |
| SDDM    | 38       | 21.47%  |
| GDM3    | 26       | 14.69%  |
| LightDM | 11       | 6.21%   |
| GDM     | 11       | 6.21%   |
| KDM     | 5        | 2.82%   |
| TDM     | 3        | 1.69%   |
| SLIMSKI | 1        | 0.56%   |
| LY-DM   | 1        | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_PE   | 92       | 53.18%  |
| en_US   | 40       | 23.12%  |
| es_ES   | 18       | 10.4%   |
| Unknown | 11       | 6.36%   |
| es_MX   | 4        | 2.31%   |
| en_GB   | 3        | 1.73%   |
| ru_RU   | 1        | 0.58%   |
| es_US   | 1        | 0.58%   |
| es_AR   | 1        | 0.58%   |
| de_DE   | 1        | 0.58%   |
| C       | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 104      | 60.12%  |
| EFI  | 69       | 39.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 125      | 71.02%  |
| Overlay | 20       | 11.36%  |
| Btrfs   | 14       | 7.95%   |
| Unknown | 7        | 3.98%   |
| Xfs     | 4        | 2.27%   |
| Tmpfs   | 4        | 2.27%   |
| Ext3    | 2        | 1.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 95       | 53.98%  |
| GPT     | 62       | 35.23%  |
| MBR     | 19       | 10.8%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 77.65%  |
| Yes       | 40       | 22.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 61.36%  |
| Yes       | 68       | 38.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 42       | 24.71%  |
| ASUSTek Computer    | 27       | 15.88%  |
| MSI                 | 24       | 14.12%  |
| Intel               | 24       | 14.12%  |
| Hewlett-Packard     | 13       | 7.65%   |
| ASRock              | 9        | 5.29%   |
| Dell                | 7        | 4.12%   |
| Foxconn             | 6        | 3.53%   |
| Lenovo              | 5        | 2.94%   |
| Quanta              | 2        | 1.18%   |
| ECS                 | 2        | 1.18%   |
| AMI                 | 2        | 1.18%   |
| Unknown             | 2        | 1.18%   |
| SZMZ                | 1        | 0.59%   |
| PCChips             | 1        | 0.59%   |
| GIADA               | 1        | 0.59%   |
| Deltron             | 1        | 0.59%   |
| Biostar             | 1        | 0.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| MSI MS-7721                | 4        | 2.35%   |
| Gigabyte B75M-D3H          | 4        | 2.35%   |
| Gigabyte 970A-DS3P         | 4        | 2.35%   |
| Gigabyte F2A68HM-H         | 3        | 1.76%   |
| ASUS All Series            | 3        | 1.76%   |
| Quanta 120-1016la          | 2        | 1.18%   |
| Intel H61                  | 2        | 1.18%   |
| Intel DH55PJ AAE93812-303  | 2        | 1.18%   |
| HP Compaq 4000 Pro SFF PC  | 2        | 1.18%   |
| Gigabyte Z77X-UD5H         | 2        | 1.18%   |
| Gigabyte X570 AORUS MASTER | 2        | 1.18%   |
| Gigabyte A520M H           | 2        | 1.18%   |
| Foxconn 500B Microtower    | 2        | 1.18%   |
| Dell OptiPlex 7010         | 2        | 1.18%   |
| ASUS TUF Gaming B550M-PLUS | 2        | 1.18%   |
| ASUS PRIME X570-P          | 2        | 1.18%   |
| ASUS PRIME A320M-K         | 2        | 1.18%   |
| AMI Z83-V                  | 2        | 1.18%   |
| Unknown                    | 2        | 1.18%   |
| SZMZ X99 DUAL Z8           | 1        | 0.59%   |
| PCChips P49G               | 1        | 0.59%   |
| MSI MS-7D95                | 1        | 0.59%   |
| MSI MS-7D76                | 1        | 0.59%   |
| MSI MS-7D46                | 1        | 0.59%   |
| MSI MS-7D25                | 1        | 0.59%   |
| MSI MS-7D18                | 1        | 0.59%   |
| MSI MS-7C94                | 1        | 0.59%   |
| MSI MS-7C91                | 1        | 0.59%   |
| MSI MS-7C88                | 1        | 0.59%   |
| MSI MS-7C52                | 1        | 0.59%   |
| MSI MS-7C08                | 1        | 0.59%   |
| MSI MS-7B53                | 1        | 0.59%   |
| MSI MS-7A70                | 1        | 0.59%   |
| MSI MS-7A39                | 1        | 0.59%   |
| MSI MS-7A33                | 1        | 0.59%   |
| MSI MS-7A15                | 1        | 0.59%   |
| MSI MS-7978                | 1        | 0.59%   |
| MSI MS-7900                | 1        | 0.59%   |
| MSI MS-7817                | 1        | 0.59%   |
| MSI MS-7758                | 1        | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 10       | 5.88%   |
| HP Compaq          | 7        | 4.12%   |
| Dell OptiPlex      | 7        | 4.12%   |
| MSI MS-7721        | 4        | 2.35%   |
| Lenovo ThinkCentre | 4        | 2.35%   |
| Gigabyte B75M-D3H  | 4        | 2.35%   |
| Gigabyte 970A-DS3P | 4        | 2.35%   |
| ASUS TUF           | 4        | 2.35%   |
| Gigabyte X570      | 3        | 1.76%   |
| Gigabyte F2A68HM-H | 3        | 1.76%   |
| ASUS ROG           | 3        | 1.76%   |
| ASUS All           | 3        | 1.76%   |
| ASRock X570        | 3        | 1.76%   |
| Quanta 120-1016la  | 2        | 1.18%   |
| Intel H61          | 2        | 1.18%   |
| Intel DH61WW       | 2        | 1.18%   |
| Intel DH55PJ       | 2        | 1.18%   |
| Intel DG31PR       | 2        | 1.18%   |
| Intel D945GCNL     | 2        | 1.18%   |
| HP ProDesk         | 2        | 1.18%   |
| HP EliteDesk       | 2        | 1.18%   |
| Gigabyte Z77X-UD5H | 2        | 1.18%   |
| Gigabyte A520M     | 2        | 1.18%   |
| Foxconn H61MXE     | 2        | 1.18%   |
| Foxconn 500B       | 2        | 1.18%   |
| ASUS M5A97         | 2        | 1.18%   |
| AMI Z83-V          | 2        | 1.18%   |
| Unknown            | 2        | 1.18%   |
| SZMZ X99           | 1        | 0.59%   |
| PCChips P49G       | 1        | 0.59%   |
| MSI MS-7D95        | 1        | 0.59%   |
| MSI MS-7D76        | 1        | 0.59%   |
| MSI MS-7D46        | 1        | 0.59%   |
| MSI MS-7D25        | 1        | 0.59%   |
| MSI MS-7D18        | 1        | 0.59%   |
| MSI MS-7C94        | 1        | 0.59%   |
| MSI MS-7C91        | 1        | 0.59%   |
| MSI MS-7C88        | 1        | 0.59%   |
| MSI MS-7C52        | 1        | 0.59%   |
| MSI MS-7C08        | 1        | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 22       | 12.94%  |
| 2012 | 15       | 8.82%   |
| 2010 | 14       | 8.24%   |
| 2019 | 13       | 7.65%   |
| 2018 | 13       | 7.65%   |
| 2017 | 12       | 7.06%   |
| 2011 | 12       | 7.06%   |
| 2014 | 11       | 6.47%   |
| 2013 | 11       | 6.47%   |
| 2015 | 10       | 5.88%   |
| 2016 | 9        | 5.29%   |
| 2008 | 7        | 4.12%   |
| 2007 | 6        | 3.53%   |
| 2009 | 4        | 2.35%   |
| 2022 | 3        | 1.76%   |
| 2021 | 3        | 1.76%   |
| 2006 | 3        | 1.76%   |
| 2023 | 1        | 0.59%   |
| 2004 | 1        | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 170      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 164      | 96.47%  |
| Enabled  | 6        | 3.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 170      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 36       | 20.57%  |
| 8.01-16.0   | 36       | 20.57%  |
| 3.01-4.0    | 33       | 18.86%  |
| 16.01-24.0  | 29       | 16.57%  |
| 32.01-64.0  | 16       | 9.14%   |
| 64.01-256.0 | 8        | 4.57%   |
| 1.01-2.0    | 8        | 4.57%   |
| 24.01-32.0  | 6        | 3.43%   |
| 2.01-3.0    | 2        | 1.14%   |
| 0.51-1.0    | 1        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 69       | 35.75%  |
| 2.01-3.0   | 45       | 23.32%  |
| 4.01-8.0   | 33       | 17.1%   |
| 3.01-4.0   | 21       | 10.88%  |
| 0.51-1.0   | 17       | 8.81%   |
| 8.01-16.0  | 6        | 3.11%   |
| 32.01-64.0 | 1        | 0.52%   |
| 16.01-24.0 | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 83       | 46.63%  |
| 2      | 58       | 32.58%  |
| 3      | 21       | 11.8%   |
| 4      | 10       | 5.62%   |
| 5      | 3        | 1.69%   |
| 6      | 2        | 1.12%   |
| 9      | 1        | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 56.07%  |
| Yes       | 76       | 43.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 166      | 97.65%  |
| No        | 4        | 2.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 63.07%  |
| Yes       | 65       | 36.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 136      | 79.07%  |
| Yes       | 36       | 20.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Peru    | 170      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Lima             | 119      | 68.39%  |
| Trujillo         | 11       | 6.32%   |
| Arequipa         | 6        | 3.45%   |
| Tacna            | 5        | 2.87%   |
| Piura            | 4        | 2.3%    |
| Chiclayo         | 4        | 2.3%    |
| Moquegua         | 3        | 1.72%   |
| Huancayo         | 3        | 1.72%   |
| Cusco            | 3        | 1.72%   |
| Villa            | 2        | 1.15%   |
| Junin            | 2        | 1.15%   |
| Ica              | 2        | 1.15%   |
| San Isidro       | 1        | 0.57%   |
| Puno             | 1        | 0.57%   |
| Pucallpa         | 1        | 0.57%   |
| Juliaca          | 1        | 0.57%   |
| Huancavelica     | 1        | 0.57%   |
| Distrito de Lima | 1        | 0.57%   |
| Cajamarca        | 1        | 0.57%   |
| Bellavista       | 1        | 0.57%   |
| Barranco         | 1        | 0.57%   |
| Abancay          | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 78       | 133    | 29.55%  |
| WDC                         | 64       | 110    | 24.24%  |
| Kingston                    | 33       | 41     | 12.5%   |
| Samsung Electronics         | 19       | 25     | 7.2%    |
| Toshiba                     | 15       | 16     | 5.68%   |
| SanDisk                     | 8        | 10     | 3.03%   |
| Crucial                     | 7        | 10     | 2.65%   |
| Hewlett-Packard             | 5        | 6      | 1.89%   |
| Micron/Crucial Technology   | 4        | 7      | 1.52%   |
| PNY                         | 3        | 3      | 1.14%   |
| Phison Electronics          | 3        | 3      | 1.14%   |
| Hitachi                     | 3        | 5      | 1.14%   |
| A-DATA Technology           | 3        | 3      | 1.14%   |
| Team                        | 2        | 2      | 0.76%   |
| Silicon Motion              | 2        | 2      | 0.76%   |
| Gigabyte Technology         | 2        | 2      | 0.76%   |
| WD MediaMax                 | 1        | 1      | 0.38%   |
| Unknown                     | 1        | 4      | 0.38%   |
| Netac                       | 1        | 1      | 0.38%   |
| Mushkin                     | 1        | 2      | 0.38%   |
| Maxone                      | 1        | 2      | 0.38%   |
| LITEON                      | 1        | 1      | 0.38%   |
| Lenovo                      | 1        | 1      | 0.38%   |
| KIOXIA                      | 1        | 1      | 0.38%   |
| Kingston Technology Company | 1        | 1      | 0.38%   |
| KESU                        | 1        | 1      | 0.38%   |
| Intel                       | 1        | 1      | 0.38%   |
| Apple                       | 1        | 1      | 0.38%   |
| Unknown                     | 1        | 3      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 15       | 4.73%   |
| Seagate ST1000DM010-2EP102 1TB   | 12       | 3.79%   |
| WDC WD10EZEX-08WN4A0 1TB         | 8        | 2.52%   |
| Kingston SA400S37240G 240GB SSD  | 7        | 2.21%   |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 1.89%   |
| Kingston SA400S37480G 480GB SSD  | 6        | 1.89%   |
| Kingston SA400S37120G 120GB SSD  | 6        | 1.89%   |
| Toshiba DT01ACA100 1TB           | 5        | 1.58%   |
| Seagate ST3500418AS 500GB        | 5        | 1.58%   |
| Seagate ST1000DM003-1CH162 1TB   | 5        | 1.58%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 4        | 1.26%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 4        | 1.26%   |
| Seagate ST3500413AS 500GB        | 4        | 1.26%   |
| Seagate ST3500312CS 500GB        | 4        | 1.26%   |
| Seagate ST2000DM006-2DM164 2TB   | 4        | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB   | 4        | 1.26%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 3        | 0.95%   |
| WDC WD5000AAKX-083CA1 500GB      | 3        | 0.95%   |
| WDC WD3200AAJS-56M0A0 320GB      | 3        | 0.95%   |
| Toshiba HDWD110 1TB              | 3        | 0.95%   |
| Seagate ST2000DL003-9VT166 2TB   | 3        | 0.95%   |
| Seagate ST1000DM003-9YN162 1TB   | 3        | 0.95%   |
| Seagate ST1000DM003-1ER162 1TB   | 3        | 0.95%   |
| Seagate Expansion 2TB            | 3        | 0.95%   |
| Kingston SNVS250G 250GB          | 3        | 0.95%   |
| Kingston NVMe SSD Drive 500GB    | 3        | 0.95%   |
| HP SSD S700 500GB                | 3        | 0.95%   |
| Crucial CT1000P1SSD8 1TB         | 3        | 0.95%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.63%   |
| WDC WD80EFAX-68KNBN0 8TB         | 2        | 0.63%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.63%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 0.63%   |
| WDC WD3200BPVT-22ZEST0 320GB     | 2        | 0.63%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.63%   |
| WDC WD10SPZX-08Z10 1TB           | 2        | 0.63%   |
| WDC WD10SPSX-08A6W 1TB           | 2        | 0.63%   |
| WDC WD10JPVX-00JC3T0 1TB         | 2        | 0.63%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.63%   |
| WDC WD10EZEX-00WN4A0 1TB         | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 78       | 133    | 48.45%  |
| WDC                 | 51       | 75     | 31.68%  |
| Toshiba             | 15       | 16     | 9.32%   |
| Samsung Electronics | 12       | 16     | 7.45%   |
| Hitachi             | 3        | 5      | 1.86%   |
| KESU                | 1        | 1      | 0.62%   |
| Apple               | 1        | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 25       | 28     | 36.76%  |
| WDC                 | 16       | 24     | 23.53%  |
| Hewlett-Packard     | 5        | 5      | 7.35%   |
| Crucial             | 4        | 6      | 5.88%   |
| PNY                 | 3        | 3      | 4.41%   |
| A-DATA Technology   | 3        | 3      | 4.41%   |
| Team                | 2        | 2      | 2.94%   |
| Samsung Electronics | 2        | 3      | 2.94%   |
| Gigabyte Technology | 2        | 2      | 2.94%   |
| SanDisk             | 1        | 1      | 1.47%   |
| Netac               | 1        | 1      | 1.47%   |
| Maxone              | 1        | 2      | 1.47%   |
| LITEON              | 1        | 1      | 1.47%   |
| Lenovo              | 1        | 1      | 1.47%   |
| Intel               | 1        | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 136      | 247    | 55.74%  |
| SSD     | 63       | 83     | 25.82%  |
| NVMe    | 40       | 58     | 16.39%  |
| Unknown | 3        | 8      | 1.23%   |
| MMC     | 2        | 2      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 156      | 330    | 76.85%  |
| NVMe | 40       | 58     | 19.7%   |
| SAS  | 5        | 8      | 2.46%   |
| MMC  | 2        | 2      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 114      | 184    | 53.52%  |
| 0.51-1.0   | 67       | 95     | 31.46%  |
| 1.01-2.0   | 22       | 36     | 10.33%  |
| 3.01-4.0   | 4        | 6      | 1.88%   |
| 2.01-3.0   | 3        | 3      | 1.41%   |
| 4.01-10.0  | 3        | 6      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 51       | 27.42%  |
| 501-1000       | 34       | 18.28%  |
| 101-250        | 28       | 15.05%  |
| 1001-2000      | 15       | 8.06%   |
| 1-20           | 14       | 7.53%   |
| 51-100         | 13       | 6.99%   |
| 2001-3000      | 10       | 5.38%   |
| More than 3000 | 9        | 4.84%   |
| 21-50          | 8        | 4.3%    |
| Unknown        | 4        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 70       | 36.84%  |
| 21-50          | 27       | 14.21%  |
| 101-250        | 24       | 12.63%  |
| 251-500        | 23       | 12.11%  |
| 501-1000       | 13       | 6.84%   |
| 51-100         | 13       | 6.84%   |
| 1001-2000      | 11       | 5.79%   |
| More than 3000 | 4        | 2.11%   |
| Unknown        | 4        | 2.11%   |
| 2001-3000      | 1        | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200AAJS-56M0A0 320GB       | 3        | 4      | 9.09%   |
| Seagate ST1000DM003-9YN162 1TB    | 3        | 3      | 9.09%   |
| Seagate ST1000DM003-1CH162 1TB    | 3        | 4      | 9.09%   |
| WDC WD5000AAKX-083CA1 500GB       | 2        | 2      | 6.06%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 6.06%   |
| Seagate ST3500418AS 500GB         | 2        | 2      | 6.06%   |
| WDC WD800BD-00MRA1 80GB           | 1        | 1      | 3.03%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 3.03%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 1      | 3.03%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 1      | 3.03%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 3.03%   |
| Toshiba MK6475GSX 640GB           | 1        | 1      | 3.03%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 3.03%   |
| Seagate ST980811AS 80GB           | 1        | 1      | 3.03%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 3.03%   |
| Seagate ST500DM002-9YN14C 500GB   | 1        | 2      | 3.03%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 3.03%   |
| Seagate ST3320820SCE 320GB        | 1        | 2      | 3.03%   |
| Seagate ST3250820AS 250GB         | 1        | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB    | 1        | 1      | 3.03%   |
| Samsung Electronics SP1644N 160GB | 1        | 1      | 3.03%   |
| Samsung Electronics HD161HJ 160GB | 1        | 2      | 3.03%   |
| Hitachi HTS545032B9A300 320GB     | 1        | 1      | 3.03%   |
| A-DATA Technology SP550 240GB SSD | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 51.52%  |
| WDC                 | 10       | 11     | 30.3%   |
| Toshiba             | 2        | 2      | 6.06%   |
| Samsung Electronics | 2        | 3      | 6.06%   |
| Hitachi             | 1        | 1      | 3.03%   |
| A-DATA Technology   | 1        | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 53.13%  |
| WDC                 | 10       | 11     | 31.25%  |
| Toshiba             | 2        | 2      | 6.25%   |
| Samsung Electronics | 2        | 3      | 6.25%   |
| Hitachi             | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 37     | 96.3%   |
| SSD  | 1        | 1      | 3.7%    |

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
| Detected | 98       | 222    | 50.78%  |
| Works    | 68       | 138    | 35.23%  |
| Malfunc  | 27       | 38     | 13.99%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 101      | 45.7%   |
| AMD                         | 63       | 28.51%  |
| SanDisk                     | 11       | 4.98%   |
| Kingston Technology Company | 11       | 4.98%   |
| Micron/Crucial Technology   | 7        | 3.17%   |
| Marvell Technology Group    | 6        | 2.71%   |
| Samsung Electronics         | 5        | 2.26%   |
| Silicon Motion              | 4        | 1.81%   |
| Nvidia                      | 4        | 1.81%   |
| Phison Electronics          | 3        | 1.36%   |
| JMicron Technology          | 3        | 1.36%   |
| LSI Logic / Symbios Logic   | 1        | 0.45%   |
| KIOXIA                      | 1        | 0.45%   |
| ASMedia Technology          | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 11.07%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 4.64%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 4.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 3.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10       | 3.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 3.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 3.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 2.5%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 6        | 2.14%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 5        | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.79%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 4        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.07%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 3        | 1.07%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.07%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 1.07%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.07%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.07%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.07%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.07%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.07%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.07%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.71%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.71%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.71%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 0.71%   |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                          | 2        | 0.71%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 2        | 0.71%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2        | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 2        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 134      | 59.03%  |
| IDE  | 47       | 20.7%   |
| NVMe | 40       | 17.62%  |
| RAID | 4        | 1.76%   |
| SAS  | 1        | 0.44%   |
| SCSI | 1        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 104      | 61.18%  |
| AMD    | 66       | 38.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz                | 5        | 2.92%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 5        | 2.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 4        | 2.34%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 3        | 1.75%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 3        | 1.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 3        | 1.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 3        | 1.75%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 3        | 1.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 3        | 1.75%   |
| AMD FX-8350 Eight-Core Processor                | 3        | 1.75%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 2        | 1.17%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 2        | 1.17%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 2        | 1.17%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 2        | 1.17%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 2        | 1.17%   |
| Intel Core i3-9100F CPU @ 3.60GHz               | 2        | 1.17%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2        | 1.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 2        | 1.17%   |
| Intel Core 2 CPU 6300 @ 1.86GHz                 | 2        | 1.17%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2        | 1.17%   |
| AMD Sempron 140 Processor                       | 2        | 1.17%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 2        | 1.17%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 1.17%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 2        | 1.17%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 1.17%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 2        | 1.17%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 2        | 1.17%   |
| AMD E-450 APU with Radeon HD Graphics           | 2        | 1.17%   |
| AMD A8-7650K Radeon R7, 10 Compute Cores 4C+6G  | 2        | 1.17%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.17%   |
| Intel Xeon CPU X5650 @ 2.67GHz                  | 1        | 0.58%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz             | 1        | 0.58%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz              | 1        | 0.58%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz              | 1        | 0.58%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1        | 0.58%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz          | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 0.58%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz          | 1        | 0.58%   |
| Intel Pentium D CPU 3.00GHz                     | 1        | 0.58%   |
| Intel Pentium CPU G620 @ 2.60GHz                | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 16.47%  |
| Intel Core i7           | 20       | 11.76%  |
| Intel Core i3           | 13       | 7.65%   |
| AMD Ryzen 7             | 13       | 7.65%   |
| AMD Ryzen 5             | 10       | 5.88%   |
| Intel Core 2 Duo        | 7        | 4.12%   |
| AMD FX                  | 7        | 4.12%   |
| Intel Pentium           | 5        | 2.94%   |
| AMD Ryzen 9             | 5        | 2.94%   |
| AMD Ryzen 3             | 5        | 2.94%   |
| Other                   | 4        | 2.35%   |
| Intel Xeon              | 4        | 2.35%   |
| Intel Pentium Dual-Core | 4        | 2.35%   |
| Intel Pentium Dual      | 4        | 2.35%   |
| AMD A10                 | 4        | 2.35%   |
| Intel Celeron           | 3        | 1.76%   |
| AMD Phenom II X4        | 3        | 1.76%   |
| AMD A8                  | 3        | 1.76%   |
| Intel Pentium Gold      | 2        | 1.18%   |
| Intel Pentium 4         | 2        | 1.18%   |
| Intel Core 2 Quad       | 2        | 1.18%   |
| Intel Core 2            | 2        | 1.18%   |
| Intel Atom              | 2        | 1.18%   |
| AMD Sempron             | 2        | 1.18%   |
| AMD E                   | 2        | 1.18%   |
| AMD A6                  | 2        | 1.18%   |
| AMD A4                  | 2        | 1.18%   |
| Intel Pentium D         | 1        | 0.59%   |
| Intel Core i9           | 1        | 0.59%   |
| AMD Ryzen 5 PRO         | 1        | 0.59%   |
| AMD Phenom II X3        | 1        | 0.59%   |
| AMD Phenom II X2        | 1        | 0.59%   |
| AMD Athlon X4           | 1        | 0.59%   |
| AMD Athlon II X3        | 1        | 0.59%   |
| AMD Athlon II X2        | 1        | 0.59%   |
| AMD Athlon 64 X2        | 1        | 0.59%   |
| AMD Athlon              | 1        | 0.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 63       | 37.06%  |
| 2       | 50       | 29.41%  |
| 8       | 18       | 10.59%  |
| 6       | 17       | 10%     |
| 1       | 8        | 4.71%   |
| 16      | 5        | 2.94%   |
| 3       | 4        | 2.35%   |
| 12      | 2        | 1.18%   |
| 20      | 1        | 0.59%   |
| 10      | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 170      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 92       | 54.12%  |
| 1       | 77       | 45.29%  |
| Unknown | 1        | 0.59%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 167      | 97.66%  |
| 64-bit         | 2        | 1.17%   |
| Unknown        | 2        | 1.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 25.57%  |
| 0x306a9    | 14       | 7.95%   |
| 0x306c3    | 8        | 4.55%   |
| 0x206a7    | 7        | 3.98%   |
| 0x1067a    | 7        | 3.98%   |
| 0x08701021 | 7        | 3.98%   |
| 0x506e3    | 6        | 3.41%   |
| 0x6fd      | 5        | 2.84%   |
| 0x06003106 | 5        | 2.84%   |
| 0x06000852 | 5        | 2.84%   |
| 0x010000c8 | 5        | 2.84%   |
| 0xa0655    | 3        | 1.7%    |
| 0x906e9    | 3        | 1.7%    |
| 0x6fb      | 3        | 1.7%    |
| 0xf64      | 2        | 1.14%   |
| 0x906ea    | 2        | 1.14%   |
| 0x20655    | 2        | 1.14%   |
| 0x10676    | 2        | 1.14%   |
| 0x0a50000c | 2        | 1.14%   |
| 0x0a201009 | 2        | 1.14%   |
| 0x08701013 | 2        | 1.14%   |
| 0x08108109 | 2        | 1.14%   |
| 0x0810100b | 2        | 1.14%   |
| 0x0800820d | 2        | 1.14%   |
| 0x06001119 | 2        | 1.14%   |
| 0x010000c7 | 2        | 1.14%   |
| 0xf49      | 1        | 0.57%   |
| 0xa0671    | 1        | 0.57%   |
| 0xa0653    | 1        | 0.57%   |
| 0x906ed    | 1        | 0.57%   |
| 0x90672    | 1        | 0.57%   |
| 0x806ec    | 1        | 0.57%   |
| 0x706a8    | 1        | 0.57%   |
| 0x6f6      | 1        | 0.57%   |
| 0x6f2      | 1        | 0.57%   |
| 0x406f1    | 1        | 0.57%   |
| 0x406c4    | 1        | 0.57%   |
| 0x206c2    | 1        | 0.57%   |
| 0x106e5    | 1        | 0.57%   |
| 0x0a601206 | 1        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 15       | 8.82%   |
| IvyBridge        | 15       | 8.82%   |
| Zen 2            | 13       | 7.65%   |
| SandyBridge      | 11       | 6.47%   |
| Penryn           | 11       | 6.47%   |
| Skylake          | 10       | 5.88%   |
| K10              | 10       | 5.88%   |
| Haswell          | 10       | 5.88%   |
| Core             | 10       | 5.88%   |
| Zen 3            | 9        | 5.29%   |
| Piledriver       | 9        | 5.29%   |
| Zen+             | 7        | 4.12%   |
| Steamroller      | 7        | 4.12%   |
| CometLake        | 6        | 3.53%   |
| Zen              | 4        | 2.35%   |
| Westmere         | 3        | 1.76%   |
| Silvermont       | 3        | 1.76%   |
| NetBurst         | 3        | 1.76%   |
| Unknown          | 3        | 1.76%   |
| Bobcat           | 2        | 1.18%   |
| Nehalem          | 1        | 0.59%   |
| K8 Hammer        | 1        | 0.59%   |
| K10 Llano        | 1        | 0.59%   |
| Icelake          | 1        | 0.59%   |
| Goldmont plus    | 1        | 0.59%   |
| Excavator        | 1        | 0.59%   |
| Bulldozer        | 1        | 0.59%   |
| Broadwell        | 1        | 0.59%   |
| Alderlake Hybrid | 1        | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 34.78%  |
| Nvidia | 60       | 32.61%  |
| AMD    | 60       | 32.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11       | 5.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 4.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7        | 3.68%   |
| Intel HD Graphics 530                                                                    | 6        | 3.16%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 2.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5        | 2.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.11%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 4        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 2.11%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4        | 2.11%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.58%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3        | 1.58%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 1.58%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.58%   |
| Intel HD Graphics 630                                                                    | 3        | 1.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.58%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.58%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3        | 1.58%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3        | 1.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.58%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 1.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.58%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.58%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                                      | 2        | 1.05%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 2        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 2        | 1.05%   |
| Intel HD Graphics 610                                                                    | 2        | 1.05%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 1.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.05%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 1.05%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 2        | 1.05%   |
| AMD RV370 [Radeon X300]                                                                  | 2        | 1.05%   |
| AMD RV370 [Radeon X300 SE]                                                               | 2        | 1.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 54       | 31.4%   |
| 1 x Nvidia     | 53       | 30.81%  |
| 1 x Intel      | 53       | 30.81%  |
| Intel + Nvidia | 5        | 2.91%   |
| 2 x AMD        | 3        | 1.74%   |
| AMD + Nvidia   | 2        | 1.16%   |
| 2 x Intel      | 1        | 0.58%   |
| Intel + AMD    | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 139      | 80.35%  |
| Proprietary | 31       | 17.92%  |
| Unknown     | 3        | 1.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 43.82%  |
| 1.01-2.0   | 29       | 16.29%  |
| 0.51-1.0   | 19       | 10.67%  |
| 0.01-0.5   | 17       | 9.55%   |
| 3.01-4.0   | 14       | 7.87%   |
| 7.01-8.0   | 13       | 7.3%    |
| 5.01-6.0   | 6        | 3.37%   |
| 8.01-16.0  | 2        | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 26.22%  |
| Goldstar             | 41       | 25%     |
| Hewlett-Packard      | 15       | 9.15%   |
| AOC                  | 12       | 7.32%   |
| Dell                 | 8        | 4.88%   |
| ViewSonic            | 6        | 3.66%   |
| BenQ                 | 5        | 3.05%   |
| Unknown              | 4        | 2.44%   |
| Lenovo               | 4        | 2.44%   |
| ASUSTek Computer     | 4        | 2.44%   |
| Sony                 | 3        | 1.83%   |
| LG Electronics       | 3        | 1.83%   |
| Lenovo Group Limited | 2        | 1.22%   |
| Ancor Communications | 2        | 1.22%   |
| Viotek               | 1        | 0.61%   |
| TopView              | 1        | 0.61%   |
| Panasonic            | 1        | 0.61%   |
| NEW                  | 1        | 0.61%   |
| MStar                | 1        | 0.61%   |
| MSD                  | 1        | 0.61%   |
| JRY                  | 1        | 0.61%   |
| Hyundai ImageQuest   | 1        | 0.61%   |
| Huion                | 1        | 0.61%   |
| Gigabyte Technology  | 1        | 0.61%   |
| Eizo                 | 1        | 0.61%   |
| Acer                 | 1        | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7        | 4.07%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch  | 3        | 1.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.74%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 1.74%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                   | 3        | 1.74%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3        | 1.74%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 2        | 1.16%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch  | 2        | 1.16%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch  | 2        | 1.16%   |
| Samsung Electronics S22A33x SAM7122 1920x1080 479x260mm 21.5-inch     | 2        | 1.16%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch      | 2        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 410x230mm 18.5-inch | 2        | 1.16%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch  | 2        | 1.16%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                      | 2        | 1.16%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch     | 2        | 1.16%   |
| Hewlett-Packard Omni 120 HWP4218 1600x900 440x250mm 19.9-inch         | 2        | 1.16%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 2        | 1.16%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 2        | 1.16%   |
| Goldstar M2380A GSM57EE 1920x1080 509x286mm 23.0-inch                 | 2        | 1.16%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 1.16%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 2        | 1.16%   |
| Goldstar FULL HD GSM5BDF 1920x1080 480x270mm 21.7-inch                | 2        | 1.16%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                   | 2        | 1.16%   |
| Dell 3008WFP DEL4036 2560x1600 641x400mm 29.7-inch                    | 2        | 1.16%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 2        | 1.16%   |
| AOC 2239 AOC2239 1920x1080 477x268mm 21.5-inch                        | 2        | 1.16%   |
| Viotek FI24D VTK0238 2560x1440 530x290mm 23.8-inch                    | 1        | 0.58%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1        | 0.58%   |
| ViewSonic VX2370 SERIES VSC342C 1920x1080 509x286mm 23.0-inch         | 1        | 0.58%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch         | 1        | 0.58%   |
| ViewSonic VA2249 Series VSC7B2E 1920x1080 476x268mm 21.5-inch         | 1        | 0.58%   |
| Unknown LCD Monitor RJT HDMI                                          | 1        | 0.58%   |
| Unknown LCD Monitor OOO TE-3190N 2560x1440                            | 1        | 0.58%   |
| Unknown LCD Monitor OOO MA2224W 1920x1080                             | 1        | 0.58%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                             | 1        | 0.58%   |
| TopView HDMI TOP0814 1600x900 430x270mm 20.0-inch                     | 1        | 0.58%   |
| Sony TV SNY2601 1360x768 710x400mm 32.1-inch                          | 1        | 0.58%   |
| Sony LCD Monitor TV 1360x768                                          | 1        | 0.58%   |
| Sony LCD Monitor TV                                                   | 1        | 0.58%   |
| Samsung Electronics V230IC SAME330 1920x1080 509x286mm 23.0-inch      | 1        | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 74       | 45.4%   |
| 1600x900 (HD+)    | 21       | 12.88%  |
| 1366x768 (WXGA)   | 15       | 9.2%    |
| 1360x768          | 11       | 6.75%   |
| 3840x2160 (4K)    | 8        | 4.91%   |
| 2560x1440 (QHD)   | 8        | 4.91%   |
| 1280x1024 (SXGA)  | 5        | 3.07%   |
| 1440x900 (WXGA+)  | 4        | 2.45%   |
| 1024x768 (XGA)    | 4        | 2.45%   |
| 3840x1080         | 3        | 1.84%   |
| Unknown           | 3        | 1.84%   |
| 2560x1600         | 2        | 1.23%   |
| 2560x1080         | 2        | 1.23%   |
| 3440x1440         | 1        | 0.61%   |
| 1920x1200 (WUXGA) | 1        | 0.61%   |
| 1280x720 (HD)     | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 43       | 26.22%  |
| 23      | 19       | 11.59%  |
| 20      | 16       | 9.76%   |
| 18      | 15       | 9.15%   |
| Unknown | 14       | 8.54%   |
| 27      | 10       | 6.1%    |
| 19      | 10       | 6.1%    |
| 24      | 8        | 4.88%   |
| 17      | 7        | 4.27%   |
| 31      | 5        | 3.05%   |
| 15      | 4        | 2.44%   |
| 48      | 3        | 1.83%   |
| 34      | 2        | 1.22%   |
| 32      | 2        | 1.22%   |
| 30      | 2        | 1.22%   |
| 84      | 1        | 0.61%   |
| 52      | 1        | 0.61%   |
| 43      | 1        | 0.61%   |
| 13      | 1        | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 80       | 49.69%  |
| 501-600     | 36       | 22.36%  |
| Unknown     | 14       | 8.7%    |
| 301-350     | 10       | 6.21%   |
| 601-700     | 7        | 4.35%   |
| 701-800     | 4        | 2.48%   |
| 1001-1500   | 4        | 2.48%   |
| 351-400     | 3        | 1.86%   |
| 201-300     | 1        | 0.62%   |
| 1501-2000   | 1        | 0.62%   |
| 901-1000    | 1        | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 118      | 76.62%  |
| Unknown | 13       | 8.44%   |
| 16/10   | 9        | 5.84%   |
| 5/4     | 8        | 5.19%   |
| 4/3     | 4        | 2.6%    |
| 21/9    | 2        | 1.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 53       | 33.13%  |
| 151-200        | 37       | 23.13%  |
| 141-150        | 20       | 12.5%   |
| Unknown        | 14       | 8.75%   |
| 351-500        | 11       | 6.88%   |
| 301-350        | 10       | 6.25%   |
| More than 1000 | 5        | 3.13%   |
| 101-110        | 4        | 2.5%    |
| 251-300        | 3        | 1.88%   |
| 81-90          | 1        | 0.63%   |
| 131-140        | 1        | 0.63%   |
| 501-1000       | 1        | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 80       | 51.28%  |
| 101-120 | 52       | 33.33%  |
| Unknown | 14       | 8.97%   |
| 1-50    | 9        | 5.77%   |
| 121-160 | 1        | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 153      | 87.93%  |
| 2     | 15       | 8.62%   |
| 0     | 4        | 2.3%    |
| 3     | 2        | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 114      | 50%     |
| Intel                           | 60       | 26.32%  |
| Qualcomm Atheros                | 11       | 4.82%   |
| TP-Link                         | 9        | 3.95%   |
| Ralink Technology               | 5        | 2.19%   |
| Qualcomm Atheros Communications | 4        | 1.75%   |
| Nvidia                          | 4        | 1.75%   |
| Broadcom Limited                | 3        | 1.32%   |
| Ralink                          | 2        | 0.88%   |
| Microsoft                       | 2        | 0.88%   |
| Huawei Technologies             | 2        | 0.88%   |
| D-Link System                   | 2        | 0.88%   |
| Broadcom                        | 2        | 0.88%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.44%   |
| Xiaomi                          | 1        | 0.44%   |
| Qualcomm                        | 1        | 0.44%   |
| OPPO Electronics                | 1        | 0.44%   |
| Motorola PCS                    | 1        | 0.44%   |
| MediaTek                        | 1        | 0.44%   |
| D-Link                          | 1        | 0.44%   |
| ASIX Electronics                | 1        | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 83       | 33.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11       | 4.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 4%      |
| Intel I211 Gigabit Network Connection                                  | 7        | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                   | 7        | 2.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 2.4%    |
| Intel Wi-Fi 6 AX200                                                    | 6        | 2.4%    |
| Intel 82579V Gigabit Network Connection                                | 6        | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 2.4%    |
| Ralink MT7601U Wireless Adapter                                        | 4        | 1.6%    |
| Qualcomm Atheros AR9271 802.11n                                        | 4        | 1.6%    |
| TP-Link 802.11n NIC                                                    | 3        | 1.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 1.2%    |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 1.2%    |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 1.2%    |
| Intel 82578DC Gigabit Network Connection                               | 3        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 2        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.8%    |
| Microsoft Xbox 360 Wireless Adapter                                    | 2        | 0.8%    |
| Intel Wireless 7265                                                    | 2        | 0.8%    |
| Intel Ethernet Controller I225-V                                       | 2        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.8%    |
| Intel 82567V-4 Gigabit Network Connection                              | 2        | 0.8%    |
| Huawei VTR-L09                                                         | 2        | 0.8%    |
| ZTE WCDMA MSM Unisoc Phone                                             | 1        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.4%    |
| TP-Link USB 10/100 LAN                                                 | 1        | 0.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.4%    |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                | 1        | 0.4%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.4%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 0.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 19       | 28.79%  |
| Intel                           | 14       | 21.21%  |
| TP-Link                         | 8        | 12.12%  |
| Qualcomm Atheros                | 7        | 10.61%  |
| Ralink Technology               | 5        | 7.58%   |
| Qualcomm Atheros Communications | 4        | 6.06%   |
| Ralink                          | 2        | 3.03%   |
| Microsoft                       | 2        | 3.03%   |
| Broadcom                        | 2        | 3.03%   |
| MediaTek                        | 1        | 1.52%   |
| D-Link System                   | 1        | 1.52%   |
| D-Link                          | 1        | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                    | 6        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 6.06%   |
| Qualcomm Atheros AR9271 802.11n                                        | 4        | 6.06%   |
| TP-Link 802.11n NIC                                                    | 3        | 4.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 3.03%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 3.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 2        | 3.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 3.03%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 2        | 3.03%   |
| Intel Wireless 7265                                                    | 2        | 3.03%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 1.52%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                | 1        | 1.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 1.52%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 1.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 1.52%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 1        | 1.52%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 1.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 1.52%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 1.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 1        | 1.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.52%   |
| Intel Wireless 7260                                                    | 1        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.52%   |
| Intel Centrino Wireless-N 2230                                         | 1        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 1        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1        | 1.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.52%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]   | 1        | 1.52%   |
| D-Link DWL-G132 [Atheros AR5523]                                       | 1        | 1.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 1        | 1.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 105      | 58.66%  |
| Intel                      | 53       | 29.61%  |
| Qualcomm Atheros           | 5        | 2.79%   |
| Nvidia                     | 4        | 2.23%   |
| Broadcom Limited           | 3        | 1.68%   |
| Huawei Technologies        | 2        | 1.12%   |
| ZTE WCDMA Technologies MSM | 1        | 0.56%   |
| Xiaomi                     | 1        | 0.56%   |
| TP-Link                    | 1        | 0.56%   |
| Qualcomm                   | 1        | 0.56%   |
| OPPO Electronics           | 1        | 0.56%   |
| D-Link System              | 1        | 0.56%   |
| ASIX Electronics           | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 83       | 45.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11       | 6.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 5.46%   |
| Intel I211 Gigabit Network Connection                                  | 7        | 3.83%   |
| Intel Ethernet Connection (2) I219-V                                   | 7        | 3.83%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 3.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 1.64%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 1.64%   |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 1.64%   |
| Intel 82578DC Gigabit Network Connection                               | 3        | 1.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 1.09%   |
| Intel Ethernet Controller I225-V                                       | 2        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 1.09%   |
| Intel 82567V-4 Gigabit Network Connection                              | 2        | 1.09%   |
| Huawei VTR-L09                                                         | 2        | 1.09%   |
| ZTE WCDMA MSM Unisoc Phone                                             | 1        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.55%   |
| TP-Link USB 10/100 LAN                                                 | 1        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.55%   |
| Qualcomm Nokia G42 5G                                                  | 1        | 0.55%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1        | 0.55%   |
| Nvidia MCP67 Ethernet                                                  | 1        | 0.55%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.55%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.55%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1        | 0.55%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.55%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.55%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 0.55%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.55%   |
| Intel 82567LM-2 Gigabit Network Connection                             | 1        | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.55%   |
| Intel 82566DM Gigabit Network Connection                               | 1        | 0.55%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 0.55%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 166      | 71.55%  |
| WiFi     | 65       | 28.02%  |
| Unknown  | 1        | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 78.74%  |
| WiFi     | 37       | 21.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 128      | 74.85%  |
| 2     | 35       | 20.47%  |
| 3     | 5        | 2.92%   |
| 0     | 3        | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 80.23%  |
| Yes  | 34       | 19.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 13       | 36.11%  |
| Cambridge Silicon Radio    | 13       | 36.11%  |
| TP-Link                    | 3        | 8.33%   |
| Realtek Semiconductor      | 3        | 8.33%   |
| TRENDnet                   | 1        | 2.78%   |
| MediaTek                   | 1        | 2.78%   |
| Integrated System Solution | 1        | 2.78%   |
| IMC Networks               | 1        | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 13       | 36.11%  |
| Intel AX200 Bluetooth                                 | 6        | 16.67%  |
| TP-Link UB500 Adapter                                 | 3        | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 5.56%   |
| Intel Bluetooth wireless interface                    | 2        | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 5.56%   |
| TRENDnet TBW-108UB USB Adapter                        | 1        | 2.78%   |
| Realtek RTL8723B Bluetooth                            | 1        | 2.78%   |
| MediaTek Wireless_Device                              | 1        | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.78%   |
| Intel AX201 Bluetooth                                 | 1        | 2.78%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.78%   |
| IMC Networks Bluetooth Radio                          | 1        | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 99       | 38.08%  |
| AMD                      | 80       | 30.77%  |
| Nvidia                   | 61       | 23.46%  |
| C-Media Electronics      | 5        | 1.92%   |
| Microsoft                | 3        | 1.15%   |
| Texas Instruments        | 2        | 0.77%   |
| Logitech                 | 2        | 0.77%   |
| BEHRINGER International  | 2        | 0.77%   |
| Tenx Technology          | 1        | 0.38%   |
| Samson Technologies      | 1        | 0.38%   |
| Micro Star International | 1        | 0.38%   |
| Kingston Technology      | 1        | 0.38%   |
| Creative Labs            | 1        | 0.38%   |
| Chicony Electronics      | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 5.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16       | 5.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13       | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 4.22%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 4.22%   |
| AMD FCH Azalia Controller                                                  | 12       | 3.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 3.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 2.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 8        | 2.6%    |
| Intel 200 Series PCH HD Audio                                              | 8        | 2.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.95%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 1.95%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.3%    |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 1.3%    |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.97%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.97%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.97%   |
| Microsoft LifeChat LX-3000 Headset                                         | 3        | 0.97%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.97%   |
| C-Media Electronics USB Audio Device                                       | 3        | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 0.97%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.97%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 47       | 44.34%  |
| Samsung Electronics          | 14       | 13.21%  |
| Corsair                      | 9        | 8.49%   |
| Unknown                      | 7        | 6.6%    |
| SK hynix                     | 7        | 6.6%    |
| Micron Technology            | 5        | 4.72%   |
| Crucial                      | 4        | 3.77%   |
| Team                         | 2        | 1.89%   |
| A-DATA Technology            | 2        | 1.89%   |
| Unknown (0x7FA8000000000000) | 1        | 0.94%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.94%   |
| S                            | 1        | 0.94%   |
| Qumo                         | 1        | 0.94%   |
| Princeton                    | 1        | 0.94%   |
| Nanya Technology             | 1        | 0.94%   |
| M                            | 1        | 0.94%   |
| Hewlett-Packard              | 1        | 0.94%   |
| GeIL                         | 1        | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 6        | 4.84%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s             | 4        | 3.23%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s             | 3        | 2.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 2        | 1.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 2        | 1.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s             | 2        | 1.61%   |
| Samsung RAM M378B5173EB0 4GB DIMM DDR3 1600MT/s                 | 2        | 1.61%   |
| Kingston RAM KHX3466C17D4/32GX 32GB DIMM DDR4 3466MT/s          | 2        | 1.61%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s          | 2        | 1.61%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s            | 2        | 1.61%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 3000MT/s          | 2        | 1.61%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s             | 2        | 1.61%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s               | 2        | 1.61%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s            | 2        | 1.61%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s           | 2        | 1.61%   |
| Kingston RAM CL16-18-18 D4-3200 16GB DIMM DDR4 3200MT/s         | 2        | 1.61%   |
| Kingston RAM 99U5403-436.A00LF 8GB DIMM DDR3 1333MT/s           | 2        | 1.61%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM 1333MT/s                | 2        | 1.61%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s          | 2        | 1.61%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                            | 1        | 0.81%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                      | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2                                | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM 800MT/s                             | 1        | 0.81%   |
| Unknown (0x7FA8000000000000) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 0.81%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1        | 0.81%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s             | 1        | 0.81%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s              | 1        | 0.81%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 0.81%   |
| SK hynix RAM HMT41GU6DFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1        | 0.81%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s            | 1        | 0.81%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1        | 0.81%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                       | 1        | 0.81%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                       | 1        | 0.81%   |
| Samsung RAM Module 16GB DIMM DDR4 2400MT/s                      | 1        | 0.81%   |
| Samsung RAM M471B5273DH0-CK0 4GB DIMM DDR3 1333MT/s             | 1        | 0.81%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s             | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 41       | 45.56%  |
| DDR3    | 36       | 40%     |
| DDR2    | 6        | 6.67%   |
| Unknown | 3        | 3.33%   |
| SDRAM   | 2        | 2.22%   |
| LPDDR3  | 1        | 1.11%   |
| DDR5    | 1        | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 87       | 96.67%  |
| SODIMM       | 2        | 2.22%   |
| Row Of Chips | 1        | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 40       | 38.1%   |
| 4096  | 26       | 24.76%  |
| 2048  | 15       | 14.29%  |
| 16384 | 14       | 13.33%  |
| 32768 | 5        | 4.76%   |
| 1024  | 3        | 2.86%   |
| 512   | 2        | 1.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 17       | 15.74%  |
| 1600    | 15       | 13.89%  |
| 2133    | 10       | 9.26%   |
| 3200    | 9        | 8.33%   |
| 3466    | 8        | 7.41%   |
| 2400    | 7        | 6.48%   |
| 3733    | 4        | 3.7%    |
| 2667    | 4        | 3.7%    |
| 3800    | 3        | 2.78%   |
| 3000    | 3        | 2.78%   |
| Unknown | 3        | 2.78%   |
| 3534    | 2        | 1.85%   |
| 3400    | 2        | 1.85%   |
| 1800    | 2        | 1.85%   |
| 800     | 2        | 1.85%   |
| 533     | 2        | 1.85%   |
| 5200    | 1        | 0.93%   |
| 3600    | 1        | 0.93%   |
| 3151    | 1        | 0.93%   |
| 3100    | 1        | 0.93%   |
| 3066    | 1        | 0.93%   |
| 2733    | 1        | 0.93%   |
| 2666    | 1        | 0.93%   |
| 2200    | 1        | 0.93%   |
| 2134    | 1        | 0.93%   |
| 1867    | 1        | 0.93%   |
| 1866    | 1        | 0.93%   |
| 1067    | 1        | 0.93%   |
| 1066    | 1        | 0.93%   |
| 667     | 1        | 0.93%   |
| 400     | 1        | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother Industries            | 3        | 33.33%  |
| Hewlett-Packard               | 2        | 22.22%  |
| Star Micronics                | 1        | 11.11%  |
| Seiko Epson                   | 1        | 11.11%  |
| Samsung Info. Systems America | 1        | 11.11%  |
| Canon                         | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Brother DCP-T310                              | 2        | 22.22%  |
| Star Micronics TUP592 (STR_T-001)             | 1        | 11.11%  |
| Seiko Epson L3250 Series                      | 1        | 11.11%  |
| Samsung Info. Systems America SAMSUNG SRP-270 | 1        | 11.11%  |
| HP PSC 1400                                   | 1        | 11.11%  |
| HP DeskJet 2700 series                        | 1        | 11.11%  |
| Canon PIXMA MG3600 Series                     | 1        | 11.11%  |
| Brother DCP-9020CDW                           | 1        | 11.11%  |

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
| Logitech                | 8        | 19.51%  |
| Microdia                | 7        | 17.07%  |
| Generalplus Technology  | 6        | 14.63%  |
| Microsoft               | 5        | 12.2%   |
| Z-Star Microelectronics | 4        | 9.76%   |
| Chicony Electronics     | 3        | 7.32%   |
| Cubeternet              | 2        | 4.88%   |
| Xiongmai                | 1        | 2.44%   |
| Samsung Electronics     | 1        | 2.44%   |
| Realtek Semiconductor   | 1        | 2.44%   |
| Jieli Technology        | 1        | 2.44%   |
| Aveo Technology         | 1        | 2.44%   |
| Apple                   | 1        | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Generalplus CAMERA - UVC                            | 4        | 9.76%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 2        | 4.88%   |
| Microdia USB 2.0 Camera                             | 2        | 4.88%   |
| Microdia Defender G-Lens 2577 HD720p Camera         | 2        | 4.88%   |
| Microdia Camera                                     | 2        | 4.88%   |
| Logitech C920 PRO HD Webcam                         | 2        | 4.88%   |
| Logitech BRIO Ultra HD Webcam                       | 2        | 4.88%   |
| Cubeternet USB2.0 Camera                            | 2        | 4.88%   |
| Chicony HP 0.3MP Webcam                             | 2        | 4.88%   |
| Z-Star Vimicro USB Camera (Altair)                  | 1        | 2.44%   |
| Z-Star Venus USB2.0 Camera                          | 1        | 2.44%   |
| Z-Star Sirius USB2.0 Camera                         | 1        | 2.44%   |
| Z-Star Integrated Camera                            | 1        | 2.44%   |
| Xiongmai web camera                                 | 1        | 2.44%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1        | 2.44%   |
| Realtek HD Camera                                   | 1        | 2.44%   |
| Microsoft MicrosoftÂ LifeCam Cinema                | 1        | 2.44%   |
| Microsoft LifeCam HD-3000                           | 1        | 2.44%   |
| Microsoft LifeCam Cinema                            | 1        | 2.44%   |
| Microdia Webcam Vitade AF                           | 1        | 2.44%   |
| Logitech Webcam C270                                | 1        | 2.44%   |
| Logitech Logi Webcam C920e                          | 1        | 2.44%   |
| Logitech HD Webcam C525                             | 1        | 2.44%   |
| Logitech C505e HD Webcam                            | 1        | 2.44%   |
| Jieli USB PHY 2.0                                   | 1        | 2.44%   |
| Generalplus GENERAL WEBCAM                          | 1        | 2.44%   |
| Generalplus 808 Camera                              | 1        | 2.44%   |
| Chicony HD WebCam (Asus N-series)                   | 1        | 2.44%   |
| Aveo USB2.0 Camera                                  | 1        | 2.44%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1        | 2.44%   |

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
| Yubico.com  | 1        | 50%     |
| Alcor Micro | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID     | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 151      | 87.28%  |
| 1     | 18       | 10.4%   |
| 3     | 2        | 1.16%   |
| 4     | 1        | 0.58%   |
| 2     | 1        | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 34.78%  |
| Net/wireless             | 4        | 17.39%  |
| Net/ethernet             | 3        | 13.04%  |
| Sound                    | 2        | 8.7%    |
| Unassigned class         | 1        | 4.35%   |
| Network                  | 1        | 4.35%   |
| Firewire controller      | 1        | 4.35%   |
| Communication controller | 1        | 4.35%   |
| Chipcard                 | 1        | 4.35%   |
| Camera                   | 1        | 4.35%   |

