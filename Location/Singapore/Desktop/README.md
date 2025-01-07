Linux in Singapore - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

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

Total: 261

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | MAHOBAY NOK                 | [ed9753dfcf](https://linux-hardware.org/?probe=ed9753dfcf) | Jan 03, 2025 |
| ASRock        | A320M-HDV R4.0              | [b8d923b1af](https://linux-hardware.org/?probe=b8d923b1af) | Dec 30, 2024 |
| Unknown       | Unknown                     | [9dc841041f](https://linux-hardware.org/?probe=9dc841041f) | Dec 25, 2024 |
| MSI           | B450M PRO-VDH MAX           | [b095903374](https://linux-hardware.org/?probe=b095903374) | Dec 25, 2024 |
| HP            | 18E5                        | [252acd69a3](https://linux-hardware.org/?probe=252acd69a3) | Dec 16, 2024 |
| Gigabyte      | H310M S2P                   | [fb927e57a4](https://linux-hardware.org/?probe=fb927e57a4) | Dec 15, 2024 |
| Unknown       | Unknown                     | [ed65661387](https://linux-hardware.org/?probe=ed65661387) | Dec 12, 2024 |
| Dell          | 042P49 A00                  | [3aaa1e8304](https://linux-hardware.org/?probe=3aaa1e8304) | Dec 07, 2024 |
| MSI           | A520M-A PRO                 | [955e1ca8e6](https://linux-hardware.org/?probe=955e1ca8e6) | Nov 26, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | [6e3fdabcec](https://linux-hardware.org/?probe=6e3fdabcec) | Nov 21, 2024 |
| ASRock        | X570 Steel Legend           | [10d4c53800](https://linux-hardware.org/?probe=10d4c53800) | Nov 17, 2024 |
| Fisusen Te... | FSX-ALU4L2S Ver:1.2         | [1ad6062abc](https://linux-hardware.org/?probe=1ad6062abc) | Nov 12, 2024 |
| Fisusen Te... | FSX-ALU4L2S Ver:1.2         | [eaa81d85da](https://linux-hardware.org/?probe=eaa81d85da) | Nov 12, 2024 |
| Gigabyte      | Z490 UD AC                  | [bb999ebf42](https://linux-hardware.org/?probe=bb999ebf42) | Nov 07, 2024 |
| ASUSTek       | Pro WS W790E-SAGE SE        | [68f88e3b88](https://linux-hardware.org/?probe=68f88e3b88) | Nov 05, 2024 |
| ASUSTek       | Pro WS W790E-SAGE SE        | [5bbfb8e380](https://linux-hardware.org/?probe=5bbfb8e380) | Nov 03, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [fbbd1252dc](https://linux-hardware.org/?probe=fbbd1252dc) | Nov 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [86b687eb49](https://linux-hardware.org/?probe=86b687eb49) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ad78b8bf6e](https://linux-hardware.org/?probe=ad78b8bf6e) | Oct 24, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [77ef455f9e](https://linux-hardware.org/?probe=77ef455f9e) | Oct 23, 2024 |
| Gigabyte      | X570S AERO G                | [b7c7919aeb](https://linux-hardware.org/?probe=b7c7919aeb) | Oct 17, 2024 |
| Dell EMC      | VEP1485-ADVA-CPU A01        | [b5d215ce6f](https://linux-hardware.org/?probe=b5d215ce6f) | Oct 16, 2024 |
| Gigabyte      | B85M-D3H                    | [a4cd5134d0](https://linux-hardware.org/?probe=a4cd5134d0) | Oct 11, 2024 |
| ASUSTek       | E3M-ET V5 SERIES            | [829f56d82a](https://linux-hardware.org/?probe=829f56d82a) | Oct 07, 2024 |
| ASRock        | X670E Steel Legend          | [255badd442](https://linux-hardware.org/?probe=255badd442) | Sep 21, 2024 |
| ASUSTek       | PRIME X570-P                | [3d8a7a6b48](https://linux-hardware.org/?probe=3d8a7a6b48) | Sep 04, 2024 |
| Red Hat       | RHEL RHEL-9.4.0 PC          | [c90a458af8](https://linux-hardware.org/?probe=c90a458af8) | Aug 16, 2024 |
| MSI           | TRX40 PRO 10G               | [1c5ad9900e](https://linux-hardware.org/?probe=1c5ad9900e) | Aug 10, 2024 |
| ASUSTek       | E3M-ET V5 SERIES            | [221d2f10b1](https://linux-hardware.org/?probe=221d2f10b1) | Aug 10, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | [b03694ae0c](https://linux-hardware.org/?probe=b03694ae0c) | Aug 01, 2024 |
| HP            | 0B40h                       | [809fc3ea36](https://linux-hardware.org/?probe=809fc3ea36) | Jul 06, 2024 |
| Gigabyte      | X570S AERO G                | [52d3dc388b](https://linux-hardware.org/?probe=52d3dc388b) | Jun 03, 2024 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | [ae32a8e661](https://linux-hardware.org/?probe=ae32a8e661) | Jun 02, 2024 |
| Gigabyte      | B550M DS3H AC               | [15375b5d97](https://linux-hardware.org/?probe=15375b5d97) | May 04, 2024 |
| Gigabyte      | B85M-D2V                    | [40ae77d112](https://linux-hardware.org/?probe=40ae77d112) | May 01, 2024 |
| AZW           | MINI S 10                   | [45003dee9b](https://linux-hardware.org/?probe=45003dee9b) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [f48c5f02d8](https://linux-hardware.org/?probe=f48c5f02d8) | Apr 20, 2024 |
| Gigabyte      | X299 AORUS Gaming 9         | [49551d2a33](https://linux-hardware.org/?probe=49551d2a33) | Apr 18, 2024 |
| Unknown       | Unknown                     | [a9ac4edde2](https://linux-hardware.org/?probe=a9ac4edde2) | Apr 11, 2024 |
| Unknown       | Unknown                     | [a6ee0c5ce6](https://linux-hardware.org/?probe=a6ee0c5ce6) | Apr 11, 2024 |
| Gigabyte      | B85M-D3H                    | [69a0e2f77d](https://linux-hardware.org/?probe=69a0e2f77d) | Apr 06, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [66aa317734](https://linux-hardware.org/?probe=66aa317734) | Apr 03, 2024 |
| Dell          | 0XFWHV A00                  | [366d65567e](https://linux-hardware.org/?probe=366d65567e) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [fc7564f14d](https://linux-hardware.org/?probe=fc7564f14d) | Mar 08, 2024 |
| Unknown       | Unknown                     | [f582976129](https://linux-hardware.org/?probe=f582976129) | Mar 07, 2024 |
| ASRock        | B550M-ITX/ac                | [fdcb7825f9](https://linux-hardware.org/?probe=fdcb7825f9) | Feb 18, 2024 |
| MSI           | PRO Z790-P WIFI             | [e6f28cbfba](https://linux-hardware.org/?probe=e6f28cbfba) | Jan 29, 2024 |
| Intel         | AIder Lake PCH B660 M-AT... | [c577cab7c8](https://linux-hardware.org/?probe=c577cab7c8) | Jan 22, 2024 |
| Gigabyte      | X570S AERO G                | [15b13f2e8c](https://linux-hardware.org/?probe=15b13f2e8c) | Jan 18, 2024 |
| Unknown       | GB01                        | [33016aa27b](https://linux-hardware.org/?probe=33016aa27b) | Jan 11, 2024 |
| Unknown       | GB01                        | [551b27fa9b](https://linux-hardware.org/?probe=551b27fa9b) | Jan 11, 2024 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [7e1e7616dc](https://linux-hardware.org/?probe=7e1e7616dc) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [41ef8c725a](https://linux-hardware.org/?probe=41ef8c725a) | Jan 10, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [03e7ada99a](https://linux-hardware.org/?probe=03e7ada99a) | Jan 04, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [769bd9153a](https://linux-hardware.org/?probe=769bd9153a) | Jan 01, 2024 |
| KunPengDia... | Unknown                     | [574df96e17](https://linux-hardware.org/?probe=574df96e17) | Jan 01, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [ca4a3eaa00](https://linux-hardware.org/?probe=ca4a3eaa00) | Dec 31, 2023 |
| Lenovo        | 30BD NOK                    | [033b3c8abd](https://linux-hardware.org/?probe=033b3c8abd) | Dec 30, 2023 |
| HP            | 0B40h                       | [de46075b7e](https://linux-hardware.org/?probe=de46075b7e) | Dec 29, 2023 |
| JHZD          | BQM6                        | [fa041569a6](https://linux-hardware.org/?probe=fa041569a6) | Dec 28, 2023 |
| HP            | 0B40h                       | [e3ad55af3f](https://linux-hardware.org/?probe=e3ad55af3f) | Dec 24, 2023 |
| ASUSTek       | PRIME Z490-P                | [61724f27e7](https://linux-hardware.org/?probe=61724f27e7) | Dec 23, 2023 |
| MSI           | PRO H410M-B                 | [28d6a6092b](https://linux-hardware.org/?probe=28d6a6092b) | Dec 23, 2023 |
| Acer          | Veriton M4630G V:1.0        | [6e74b5d77f](https://linux-hardware.org/?probe=6e74b5d77f) | Dec 05, 2023 |
| ASRock        | X300TM-ITX                  | [6c74495d5f](https://linux-hardware.org/?probe=6c74495d5f) | Dec 03, 2023 |
| JINGSHA       | X99-D8I                     | [a142726fb0](https://linux-hardware.org/?probe=a142726fb0) | Dec 02, 2023 |
| JINGSHA       | X99-D8I                     | [52a45bbcdb](https://linux-hardware.org/?probe=52a45bbcdb) | Dec 02, 2023 |
| Unknown       | Intel BayTrail Series R1... | [6ab4075642](https://linux-hardware.org/?probe=6ab4075642) | Nov 29, 2023 |
| Unknown       | Unknown                     | [ada9cf1c70](https://linux-hardware.org/?probe=ada9cf1c70) | Nov 07, 2023 |
| Unknown       | Unknown                     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [d16f2b19b0](https://linux-hardware.org/?probe=d16f2b19b0) | Oct 30, 2023 |
| MACHINIST     | B75 PRO V1.0                | [8927fc6f11](https://linux-hardware.org/?probe=8927fc6f11) | Oct 27, 2023 |
| ASUSTek       | PRIME X570-P                | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| MSI           | B85M-E45                    | [acc8588daa](https://linux-hardware.org/?probe=acc8588daa) | Oct 16, 2023 |
| SZMZ          | X99M-G2                     | [1b0f7ae9a7](https://linux-hardware.org/?probe=1b0f7ae9a7) | Oct 15, 2023 |
| HP            | 82F2                        | [6a5c62ec30](https://linux-hardware.org/?probe=6a5c62ec30) | Oct 12, 2023 |
| HP            | 82F2                        | [ebf3c3339a](https://linux-hardware.org/?probe=ebf3c3339a) | Oct 12, 2023 |
| Shenzhen M... | HX90G                       | [a6e9f6c7fc](https://linux-hardware.org/?probe=a6e9f6c7fc) | Oct 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ce357bee14](https://linux-hardware.org/?probe=ce357bee14) | Sep 28, 2023 |
| Gigabyte      | B85M-D3H                    | [cfcdb2a961](https://linux-hardware.org/?probe=cfcdb2a961) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [816502caea](https://linux-hardware.org/?probe=816502caea) | Sep 21, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [62d1008e3a](https://linux-hardware.org/?probe=62d1008e3a) | Sep 01, 2023 |
| Huanan        | X99-4MT V1.0                | [b1ebbd0661](https://linux-hardware.org/?probe=b1ebbd0661) | Aug 29, 2023 |
| HP            | 0B4Ch D                     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| Dell          | 04Y8V0 A02                  | [645bd9ed6b](https://linux-hardware.org/?probe=645bd9ed6b) | Aug 20, 2023 |
| ASRock        | H71M-DGS                    | [c200c4f848](https://linux-hardware.org/?probe=c200c4f848) | Aug 14, 2023 |
| Foxconn       | 2A8Ch                       | [a936584caa](https://linux-hardware.org/?probe=a936584caa) | Aug 09, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| Dell          | 09M8Y8 A02                  | [4b57bbf30e](https://linux-hardware.org/?probe=4b57bbf30e) | Aug 04, 2023 |
| Intel         | JSL MRD                     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | PRIME X570-P                | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| Dell          | 00V62H A01                  | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| MECHREVO      | F7BFD V1.0                  | [f9be0fc5a7](https://linux-hardware.org/?probe=f9be0fc5a7) | Jul 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [556e4cd2c9](https://linux-hardware.org/?probe=556e4cd2c9) | Jul 21, 2023 |
| AZW           | Gemini J45                  | [0ed36a4286](https://linux-hardware.org/?probe=0ed36a4286) | Jul 18, 2023 |
| Shenzhen M... | HX90G                       | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| Gigabyte      | Z690 AERO D                 | [f42140d294](https://linux-hardware.org/?probe=f42140d294) | Jul 03, 2023 |
| Shenzhen M... | HX90G                       | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| ASUSTek       | PRIME H510M-E               | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| MSI           | B450M MORTAR                | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [f17ae033ef](https://linux-hardware.org/?probe=f17ae033ef) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| Dell          | 04Y8V0 A02                  | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| AZW           | MINI S 10                   | [c64432906e](https://linux-hardware.org/?probe=c64432906e) | May 10, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [64f08f10f3](https://linux-hardware.org/?probe=64f08f10f3) | May 10, 2023 |
| Dell          | 04Y8V0 A02                  | [d21ef87b63](https://linux-hardware.org/?probe=d21ef87b63) | May 10, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Gigabyte      | H61M-S2PH                   | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [7e0735056c](https://linux-hardware.org/?probe=7e0735056c) | Apr 12, 2023 |
| ASRock        | B450 Pro4                   | [ac4522914d](https://linux-hardware.org/?probe=ac4522914d) | Apr 02, 2023 |
| Pegatron      | 2ADC                        | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| Unknown       | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [c02aa4b9e1](https://linux-hardware.org/?probe=c02aa4b9e1) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| HP            | 1589                        | [2fc61ae7b4](https://linux-hardware.org/?probe=2fc61ae7b4) | Mar 09, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [63f1f6f5dd](https://linux-hardware.org/?probe=63f1f6f5dd) | Mar 08, 2023 |
| SZMZ          | X99M-G2                     | [e2244668d1](https://linux-hardware.org/?probe=e2244668d1) | Mar 02, 2023 |
| SZMZ          | X99M-G2                     | [4e45d95aa1](https://linux-hardware.org/?probe=4e45d95aa1) | Mar 01, 2023 |
| Novatte       | M20                         | [f3b00d12f2](https://linux-hardware.org/?probe=f3b00d12f2) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [de144d5025](https://linux-hardware.org/?probe=de144d5025) | Feb 12, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | [e7cc1c6b15](https://linux-hardware.org/?probe=e7cc1c6b15) | Feb 07, 2023 |
| HPE           | ProLiant MicroServer Gen... | [9a9b3eed69](https://linux-hardware.org/?probe=9a9b3eed69) | Feb 05, 2023 |
| Foxconn       | 17A0                        | [1a98ed31ed](https://linux-hardware.org/?probe=1a98ed31ed) | Feb 05, 2023 |
| Lenovo        | NOK                         | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2e6f75ca07](https://linux-hardware.org/?probe=2e6f75ca07) | Jan 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | [6dac0c0943](https://linux-hardware.org/?probe=6dac0c0943) | Dec 29, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| ASUSTek       | A88XM-A                     | [8633f00865](https://linux-hardware.org/?probe=8633f00865) | Dec 26, 2022 |
| ASUSTek       | A88XM-A                     | [802e7982de](https://linux-hardware.org/?probe=802e7982de) | Dec 26, 2022 |
| HP            | 8061                        | [4427032526](https://linux-hardware.org/?probe=4427032526) | Dec 24, 2022 |
| ASRock        | B75 Pro3-M                  | [e24692f75f](https://linux-hardware.org/?probe=e24692f75f) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | [61f064d35f](https://linux-hardware.org/?probe=61f064d35f) | Dec 22, 2022 |
| ASRock        | B450 Pro4                   | [d387b553bd](https://linux-hardware.org/?probe=d387b553bd) | Dec 22, 2022 |
| Foxconn       | 17A0                        | [58a3486afd](https://linux-hardware.org/?probe=58a3486afd) | Dec 20, 2022 |
| Foxconn       | 17A0                        | [be57227f43](https://linux-hardware.org/?probe=be57227f43) | Dec 17, 2022 |
| Foxconn       | 17A0                        | [b2185eeab5](https://linux-hardware.org/?probe=b2185eeab5) | Dec 16, 2022 |
| Foxconn       | 17A0                        | [4518247b07](https://linux-hardware.org/?probe=4518247b07) | Dec 14, 2022 |
| Foxconn       | 17A0                        | [2f3b2f9fbb](https://linux-hardware.org/?probe=2f3b2f9fbb) | Dec 07, 2022 |
| HP            | 8061                        | [6e4cb7cde8](https://linux-hardware.org/?probe=6e4cb7cde8) | Dec 07, 2022 |
| HP            | 8061                        | [9d30b0126f](https://linux-hardware.org/?probe=9d30b0126f) | Dec 05, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Acer          | RS880M05                    | [7adee2fd97](https://linux-hardware.org/?probe=7adee2fd97) | Oct 21, 2022 |
| ASUSTek       | Maximus IV Extreme          | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Gigabyte      | B550M DS3H AC               | [9ec02e49a3](https://linux-hardware.org/?probe=9ec02e49a3) | Oct 13, 2022 |
| Gigabyte      | X99-Ultra Gaming-CF         | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| ASUSTek       | X99-E WS                    | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| HP            | 843B                        | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Gigabyte      | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Gigabyte      | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| MSI           | Z87-G45 GAMING              | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| ASUSTek       | B85M-E                      | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| ASUSTek       | B85M-E                      | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek       | B85M-E                      | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| Dell          | 06CV2N A00                  | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Dell          | 0NK70N A03                  | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| HP            | 8054                        | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| Dell          | 09M8Y8 A02                  | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Dell          | 06CV2N A00                  | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte      | Z77-D3H                     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| ASRock        | B560M Pro4                  | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell          | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Dell          | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI           | Cherry Trail CR             | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell          | 0C96W1 A02                  | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte      | B365M GAMING HD             | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Dell          | 0XCR8D A03                  | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| MSI           | B450 TOMAHAWK               | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI           | A320M-A PRO MAX             | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI           | A320M-A PRO MAX             | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock        | Z77 Extreme3                | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo        | NOK                         | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Biostar       | TB250-BTC+                  | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell          | 0NKW6Y A00                  | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| LattePanda    | Alpha                       | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda    | Alpha                       | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| HP            | 198E                        | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Gigabyte      | H81M-DS2                    | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock        | HM55-MXM                    | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo        | ThinkCentre M90p 5864BM3    | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell          | 0D6H9T A00                  | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo        | SHARKBAY NOK                | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Dell          | 00V62H A01                  | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell          | 0D02VH A01                  | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Dell          | 0D441T A03                  | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| ASUSTek       | M4A78-EM-1394               | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock        | H110M-HDS R3.0              | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| ASRock        | 990FX Killer                | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| ASUSTek       | M3A78-EM                    | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| ASUSTek       | Z97M-PLUS                   | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Gigabyte      | 945GZM-S2                   | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Gigabyte      | 945GZM-S2                   | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| ASUSTek       | P8H77-V LE                  | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| ASRock        | HM55-MXM                    | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| ECS           | H61H2-MV                    | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| ASUSTek       | P8H77-V LE                  | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| ASUSTek       | H87I-PLUS                   | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock        | H110M-HDS R3.0              | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| ASUSTek       | H87I-PLUS                   | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| ASUSTek       | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock        | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek       | Berkeley                    | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek       | Berkeley                    | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| ASUSTek       | PRIME H310M-A               | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Dell          | 06D7TR A00                  | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Dell          | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell          | 00V62H A01                  | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell          | 00V62H A01                  | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Gigabyte      | Z270X-UD5-CF                | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer          | Aspire X3950                | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASRock        | Z370 Pro4                   | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell          | 0F3KHR A00                  | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| ASUSTek       | P8H67-M PRO                 | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| ASUSTek       | ET2020I                     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| MSI           | X299 RAIDER                 | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI           | X299 RAIDER                 | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI           | Boston                      | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 24       | 11.43%  |
| Ubuntu 22.04                 | 16       | 7.62%   |
| Ubuntu 18.04                 | 15       | 7.14%   |
| Arch Rolling                 | 11       | 5.24%   |
| Manjaro                      | 5        | 2.38%   |
| Linux Mint 21                | 5        | 2.38%   |
| Fedora 40                    | 5        | 2.38%   |
| Fedora 38                    | 5        | 2.38%   |
| Ubuntu 24.04                 | 4        | 1.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.9%    |
| OpenMandriva 24.12           | 4        | 1.9%    |
| KDE neon 20.04               | 4        | 1.9%    |
| Fedora 41                    | 4        | 1.9%    |
| Debian 12                    | 4        | 1.9%    |
| ArcoLinux Rolling            | 4        | 1.9%    |
| Ubuntu 23.10                 | 3        | 1.43%   |
| Pop!_OS 20.04                | 3        | 1.43%   |
| OpenMandriva 5.0             | 3        | 1.43%   |
| OpenMandriva 23.11           | 3        | 1.43%   |
| OpenMandriva 23.03           | 3        | 1.43%   |
| Linux Mint 21.2              | 3        | 1.43%   |
| Fedora 37                    | 3        | 1.43%   |
| Debian 11                    | 3        | 1.43%   |
| Zorin 17                     | 2        | 0.95%   |
| Ubuntu 21.04                 | 2        | 0.95%   |
| Rocky Linux 8.5              | 2        | 0.95%   |
| Pop!_OS 22.04                | 2        | 0.95%   |
| Pop!_OS 21.04                | 2        | 0.95%   |
| OpenMandriva 4.50            | 2        | 0.95%   |
| OpenMandriva 4.3             | 2        | 0.95%   |
| OpenMandriva 24.07           | 2        | 0.95%   |
| OpenMandriva 23.08           | 2        | 0.95%   |
| MX 21                        | 2        | 0.95%   |
| Linux Mint 20.3              | 2        | 0.95%   |
| Linux Mint 20                | 2        | 0.95%   |
| Fedora 33                    | 2        | 0.95%   |
| Arch                         | 2        | 0.95%   |
| Zorin 16                     | 1        | 0.48%   |
| Xubuntu 23.10                | 1        | 0.48%   |
| Xubuntu 23.04                | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 66       | 34.38%  |
| OpenMandriva  | 25       | 13.02%  |
| Fedora        | 15       | 7.81%   |
| Arch          | 13       | 6.77%   |
| Linux Mint    | 12       | 6.25%   |
| Pop!_OS       | 8        | 4.17%   |
| Debian        | 8        | 4.17%   |
| Manjaro       | 6        | 3.13%   |
| Rocky Linux   | 4        | 2.08%   |
| openSUSE      | 4        | 2.08%   |
| KDE neon      | 4        | 2.08%   |
| ArcoLinux     | 4        | 2.08%   |
| Zorin         | 3        | 1.56%   |
| Xubuntu       | 3        | 1.56%   |
| Ubuntu Unity  | 2        | 1.04%   |
| MX            | 2        | 1.04%   |
| Kubuntu       | 2        | 1.04%   |
| Ubuntu MATE   | 1        | 0.52%   |
| Ubuntu Kylin  | 1        | 0.52%   |
| Ubuntu Budgie | 1        | 0.52%   |
| NixOS         | 1        | 0.52%   |
| Lubuntu       | 1        | 0.52%   |
| Gentoo        | 1        | 0.52%   |
| Garuda Linux  | 1        | 0.52%   |
| EndeavourOS   | 1        | 0.52%   |
| CentOS        | 1        | 0.52%   |
| Bazzite       | 1        | 0.52%   |
| Atz           | 1        | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.15.0-56-generic                   | 7        | 3.1%    |
| 6.6.2-desktop-1omv2390              | 5        | 2.21%   |
| 6.12.1-desktop-1omv2490             | 4        | 1.77%   |
| 5.15.0-46-generic                   | 4        | 1.77%   |
| 6.2.6-desktop-1omv2390              | 3        | 1.33%   |
| 6.2.0-39-generic                    | 3        | 1.33%   |
| 5.4.0-29-generic                    | 3        | 1.33%   |
| 5.19.0-35-generic                   | 3        | 1.33%   |
| 5.15.0-58-generic                   | 3        | 1.33%   |
| 6.5.0-28-generic                    | 2        | 0.88%   |
| 6.5.0-14-generic                    | 2        | 0.88%   |
| 6.4.8-desktop-2omv2390              | 2        | 0.88%   |
| 6.3.8-zen1-1-zen                    | 2        | 0.88%   |
| 6.2.14-300.fc38.x86_64              | 2        | 0.88%   |
| 6.2.0-34-generic                    | 2        | 0.88%   |
| 6.2.0-31-generic                    | 2        | 0.88%   |
| 6.11.3-200.fc40.x86_64              | 2        | 0.88%   |
| 6.10.0-desktop-1omv2490             | 2        | 0.88%   |
| 6.0.15-300.fc37.x86_64              | 2        | 0.88%   |
| 5.9.8-200.fc33.x86_64               | 2        | 0.88%   |
| 5.4.0-7642-generic                  | 2        | 0.88%   |
| 5.4.0-70-generic                    | 2        | 0.88%   |
| 5.4.0-42-generic                    | 2        | 0.88%   |
| 5.4.0-40-generic                    | 2        | 0.88%   |
| 5.4.0-37-generic                    | 2        | 0.88%   |
| 5.3.0-51-generic                    | 2        | 0.88%   |
| 5.16.7-desktop-1omv4003             | 2        | 0.88%   |
| 5.15.0-91-generic                   | 2        | 0.88%   |
| 5.15.0-71-generic                   | 2        | 0.88%   |
| 5.15.0-52-generic                   | 2        | 0.88%   |
| 5.12.7-desktop-1omv4003             | 2        | 0.88%   |
| 5.11.0-27-generic                   | 2        | 0.88%   |
| 5.0.0-36-generic                    | 2        | 0.88%   |
| 4.18.0-348.12.2.el8_5.x86_64        | 2        | 0.88%   |
| 6.9.3-desktop-2omv2490              | 1        | 0.44%   |
| 6.8.4-arch1-1                       | 1        | 0.44%   |
| 6.8.12-2-pve                        | 1        | 0.44%   |
| 6.8.10-300.fc40.x86_64              | 1        | 0.44%   |
| 6.8.0-76060800daily20240311-generic | 1        | 0.44%   |
| 6.8.0-49-generic                    | 1        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 27       | 12.33%  |
| 5.4.0   | 24       | 10.96%  |
| 6.2.0   | 11       | 5.02%   |
| 6.5.0   | 7        | 3.2%    |
| 5.0.0   | 7        | 3.2%    |
| 6.8.0   | 6        | 2.74%   |
| 5.11.0  | 6        | 2.74%   |
| 6.6.2   | 5        | 2.28%   |
| 5.10.0  | 5        | 2.28%   |
| 4.18.0  | 5        | 2.28%   |
| 6.12.1  | 4        | 1.83%   |
| 4.15.0  | 4        | 1.83%   |
| 6.3.8   | 3        | 1.37%   |
| 6.2.6   | 3        | 1.37%   |
| 5.8.0   | 3        | 1.37%   |
| 5.3.0   | 3        | 1.37%   |
| 5.19.0  | 3        | 1.37%   |
| 6.5.9   | 2        | 0.91%   |
| 6.4.8   | 2        | 0.91%   |
| 6.3.9   | 2        | 0.91%   |
| 6.2.14  | 2        | 0.91%   |
| 6.11.3  | 2        | 0.91%   |
| 6.10.1  | 2        | 0.91%   |
| 6.10.0  | 2        | 0.91%   |
| 6.1.0   | 2        | 0.91%   |
| 6.0.15  | 2        | 0.91%   |
| 5.9.8   | 2        | 0.91%   |
| 5.16.7  | 2        | 0.91%   |
| 5.13.0  | 2        | 0.91%   |
| 5.12.7  | 2        | 0.91%   |
| 6.9.3   | 1        | 0.46%   |
| 6.8.4   | 1        | 0.46%   |
| 6.8.12  | 1        | 0.46%   |
| 6.8.10  | 1        | 0.46%   |
| 6.7.0   | 1        | 0.46%   |
| 6.6.7   | 1        | 0.46%   |
| 6.6.19  | 1        | 0.46%   |
| 6.6.13  | 1        | 0.46%   |
| 6.6.1   | 1        | 0.46%   |
| 6.5.8   | 1        | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 34       | 15.6%   |
| 5.4     | 24       | 11.01%  |
| 6.2     | 17       | 7.8%    |
| 6.5     | 10       | 4.59%   |
| 6.8     | 9        | 4.13%   |
| 6.6     | 9        | 4.13%   |
| 6.4     | 9        | 4.13%   |
| 6.3     | 9        | 4.13%   |
| 6.11    | 8        | 3.67%   |
| 6.1     | 8        | 3.67%   |
| 6.10    | 7        | 3.21%   |
| 5.11    | 7        | 3.21%   |
| 5.10    | 7        | 3.21%   |
| 5.0     | 7        | 3.21%   |
| 6.12    | 5        | 2.29%   |
| 4.18    | 5        | 2.29%   |
| 6.0     | 4        | 1.83%   |
| 5.8     | 4        | 1.83%   |
| 5.16    | 4        | 1.83%   |
| 5.13    | 4        | 1.83%   |
| 4.15    | 4        | 1.83%   |
| 5.9     | 3        | 1.38%   |
| 5.3     | 3        | 1.38%   |
| 5.19    | 3        | 1.38%   |
| 5.14    | 3        | 1.38%   |
| 5.12    | 3        | 1.38%   |
| 6.9     | 1        | 0.46%   |
| 6.7     | 1        | 0.46%   |
| 6.3.0   | 1        | 0.46%   |
| 5.18    | 1        | 0.46%   |
| 5.17    | 1        | 0.46%   |
| 4.16    | 1        | 0.46%   |
| 4.1     | 1        | 0.46%   |
| 3.10    | 1        | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 187      | 99.47%  |
| aarch64 | 1        | 0.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 76       | 38.58%  |
| Unknown       | 40       | 20.3%   |
| KDE5          | 32       | 16.24%  |
| X-Cinnamon    | 13       | 6.6%    |
| XFCE          | 10       | 5.08%   |
| LXQt          | 6        | 3.05%   |
| KDE6          | 5        | 2.54%   |
| i3            | 3        | 1.52%   |
| Unity         | 2        | 1.02%   |
| Cinnamon      | 2        | 1.02%   |
| Budgie        | 2        | 1.02%   |
| UKUI          | 1        | 0.51%   |
| niri          | 1        | 0.51%   |
| MATE          | 1        | 0.51%   |
| KDE           | 1        | 0.51%   |
| Hyprland      | 1        | 0.51%   |
| GNOME Classic | 1        | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 134      | 68.37%  |
| Wayland | 39       | 19.9%   |
| Unknown | 12       | 6.12%   |
| Tty     | 11       | 5.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 88       | 45.83%  |
| SDDM    | 42       | 21.88%  |
| GDM3    | 24       | 12.5%   |
| GDM     | 19       | 9.9%    |
| LightDM | 16       | 8.33%   |
| GREETD  | 2        | 1.04%   |
| TDM     | 1        | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 85       | 43.81%  |
| en_SG   | 67       | 34.54%  |
| Unknown | 14       | 7.22%   |
| zh_CN   | 9        | 4.64%   |
| C       | 5        | 2.58%   |
| en_AU   | 4        | 2.06%   |
| de_DE   | 4        | 2.06%   |
| en_GB   | 2        | 1.03%   |
| fr_FR   | 1        | 0.52%   |
| en_PH   | 1        | 0.52%   |
| en_IN   | 1        | 0.52%   |
| en_HK   | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 111      | 58.42%  |
| BIOS | 79       | 41.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 119      | 61.66%  |
| Btrfs   | 31       | 16.06%  |
| Overlay | 21       | 10.88%  |
| Xfs     | 12       | 6.22%   |
| Tmpfs   | 7        | 3.63%   |
| Unknown | 3        | 1.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 104      | 54.74%  |
| Unknown | 69       | 36.32%  |
| MBR     | 17       | 8.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 73.58%  |
| Yes       | 51       | 26.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 64.58%  |
| Yes       | 68       | 35.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 37       | 19.68%  |
| Gigabyte Technology                  | 33       | 17.55%  |
| MSI                                  | 24       | 12.77%  |
| Dell                                 | 19       | 10.11%  |
| ASRock                               | 19       | 10.11%  |
| Hewlett-Packard                      | 10       | 5.32%   |
| Unknown                              | 9        | 4.79%   |
| Lenovo                               | 8        | 4.26%   |
| Foxconn                              | 4        | 2.13%   |
| Acer                                 | 3        | 1.6%    |
| Intel                                | 2        | 1.06%   |
| AZW                                  | 2        | 1.06%   |
| SZMZ                                 | 1        | 0.53%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.53%   |
| Red Hat                              | 1        | 0.53%   |
| Pegatron                             | 1        | 0.53%   |
| Novatte                              | 1        | 0.53%   |
| MECHREVO                             | 1        | 0.53%   |
| MACHINIST                            | 1        | 0.53%   |
| LattePanda                           | 1        | 0.53%   |
| KunPengDianTong(KPDT)                | 1        | 0.53%   |
| JINGSHA                              | 1        | 0.53%   |
| JHZD                                 | 1        | 0.53%   |
| Huanan                               | 1        | 0.53%   |
| HPE                                  | 1        | 0.53%   |
| Fisusen Technology                   | 1        | 0.53%   |
| ECS                                  | 1        | 0.53%   |
| Dell EMC                             | 1        | 0.53%   |
| Biostar                              | 1        | 0.53%   |
| AMI                                  | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 10       | 5.32%   |
| ASUS All Series                            | 5        | 2.66%   |
| Gigabyte X570 AORUS PRO WIFI               | 4        | 2.13%   |
| MSI MS-7C84                                | 3        | 1.6%    |
| Foxconn Pro 3330 MT                        | 3        | 1.6%    |
| Dell OptiPlex 9020                         | 3        | 1.6%    |
| ASUS ROG STRIX B650E-I GAMING WIFI         | 3        | 1.6%    |
| MSI MS-7E06                                | 2        | 1.06%   |
| HP Z200 Workstation                        | 2        | 1.06%   |
| Gigabyte B85M-D3H                          | 2        | 1.06%   |
| Gigabyte B550M DS3H AC                     | 2        | 1.06%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 1.06%   |
| Dell OptiPlex 990                          | 2        | 1.06%   |
| ASUS ROG STRIX B550-I GAMING               | 2        | 1.06%   |
| ASRock B450 Pro4                           | 2        | 1.06%   |
| ASRock A320M-HDV R4.0                      | 2        | 1.06%   |
| SZMZ X99M-H2                               | 1        | 0.53%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.53%   |
| Red Hat KVM                                | 1        | 0.53%   |
| Pegatron 23-d018d                          | 1        | 0.53%   |
| Novatte M20                                | 1        | 0.53%   |
| MSI MS-7D82                                | 1        | 0.53%   |
| MSI MS-7D43                                | 1        | 0.53%   |
| MSI MS-7D42                                | 1        | 0.53%   |
| MSI MS-7D30                                | 1        | 0.53%   |
| MSI MS-7D25                                | 1        | 0.53%   |
| MSI MS-7C96                                | 1        | 0.53%   |
| MSI MS-7C95                                | 1        | 0.53%   |
| MSI MS-7C91                                | 1        | 0.53%   |
| MSI MS-7C60                                | 1        | 0.53%   |
| MSI MS-7C52                                | 1        | 0.53%   |
| MSI MS-7C02                                | 1        | 0.53%   |
| MSI MS-7B89                                | 1        | 0.53%   |
| MSI MS-7A94                                | 1        | 0.53%   |
| MSI MS-7A38                                | 1        | 0.53%   |
| MSI MS-7A32                                | 1        | 0.53%   |
| MSI MS-7821                                | 1        | 0.53%   |
| MSI MS-7817                                | 1        | 0.53%   |
| MSI MS-7721                                | 1        | 0.53%   |
| MSI KT308AA-AB4 SR5472CF                   | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 12       | 6.38%   |
| ASUS ROG                                   | 11       | 5.85%   |
| Unknown                                    | 10       | 5.32%   |
| ASUS PRIME                                 | 5        | 2.66%   |
| ASUS All                                   | 5        | 2.66%   |
| Lenovo ThinkCentre                         | 4        | 2.13%   |
| Gigabyte X570                              | 4        | 2.13%   |
| MSI MS-7C84                                | 3        | 1.6%    |
| Lenovo ThinkStation                        | 3        | 1.6%    |
| Foxconn Pro                                | 3        | 1.6%    |
| Dell Precision                             | 3        | 1.6%    |
| MSI MS-7E06                                | 2        | 1.06%   |
| HP Z200                                    | 2        | 1.06%   |
| HP ProDesk                                 | 2        | 1.06%   |
| HP EliteDesk                               | 2        | 1.06%   |
| Gigabyte X570S                             | 2        | 1.06%   |
| Gigabyte B85M-D3H                          | 2        | 1.06%   |
| Gigabyte B550M                             | 2        | 1.06%   |
| Gigabyte B550I                             | 2        | 1.06%   |
| Gigabyte B450M                             | 2        | 1.06%   |
| Gigabyte B365M                             | 2        | 1.06%   |
| Dell Vostro                                | 2        | 1.06%   |
| ASUS TUF                                   | 2        | 1.06%   |
| ASUS Pro                                   | 2        | 1.06%   |
| ASRock B450                                | 2        | 1.06%   |
| ASRock A320M-HDV                           | 2        | 1.06%   |
| Acer Veriton                               | 2        | 1.06%   |
| SZMZ X99M-H2                               | 1        | 0.53%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.53%   |
| Red Hat KVM                                | 1        | 0.53%   |
| Pegatron 23-d018d                          | 1        | 0.53%   |
| Novatte M20                                | 1        | 0.53%   |
| MSI MS-7D82                                | 1        | 0.53%   |
| MSI MS-7D43                                | 1        | 0.53%   |
| MSI MS-7D42                                | 1        | 0.53%   |
| MSI MS-7D30                                | 1        | 0.53%   |
| MSI MS-7D25                                | 1        | 0.53%   |
| MSI MS-7C96                                | 1        | 0.53%   |
| MSI MS-7C95                                | 1        | 0.53%   |
| MSI MS-7C91                                | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 24       | 12.77%  |
| 2013    | 19       | 10.11%  |
| 2018    | 18       | 9.57%   |
| 2019    | 17       | 9.04%   |
| 2021    | 15       | 7.98%   |
| 2022    | 14       | 7.45%   |
| 2012    | 13       | 6.91%   |
| 2023    | 11       | 5.85%   |
| 2017    | 11       | 5.85%   |
| 2014    | 9        | 4.79%   |
| 2010    | 9        | 4.79%   |
| 2011    | 8        | 4.26%   |
| 2016    | 6        | 3.19%   |
| 2015    | 5        | 2.66%   |
| 2008    | 3        | 1.6%    |
| 2024    | 2        | 1.06%   |
| 2007    | 2        | 1.06%   |
| 2009    | 1        | 0.53%   |
| Unknown | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 188      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 182      | 96.3%   |
| Enabled  | 7        | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 188      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 40       | 20.73%  |
| 32.01-64.0      | 38       | 19.69%  |
| 4.01-8.0        | 35       | 18.13%  |
| 8.01-16.0       | 27       | 13.99%  |
| 64.01-256.0     | 24       | 12.44%  |
| 3.01-4.0        | 12       | 6.22%   |
| 24.01-32.0      | 11       | 5.7%    |
| More than 256.0 | 3        | 1.55%   |
| 1.01-2.0        | 2        | 1.04%   |
| 0.51-1.0        | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 54       | 25.84%  |
| 2.01-3.0   | 46       | 22.01%  |
| 3.01-4.0   | 40       | 19.14%  |
| 4.01-8.0   | 33       | 15.79%  |
| 8.01-16.0  | 16       | 7.66%   |
| 0.51-1.0   | 10       | 4.78%   |
| 16.01-24.0 | 4        | 1.91%   |
| 32.01-64.0 | 2        | 0.96%   |
| 24.01-32.0 | 2        | 0.96%   |
| 0.01-0.5   | 2        | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 38.19%  |
| 2      | 53       | 26.63%  |
| 3      | 36       | 18.09%  |
| 4      | 18       | 9.05%   |
| 5      | 10       | 5.03%   |
| 0      | 4        | 2.01%   |
| 6      | 2        | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 72.49%  |
| Yes       | 52       | 27.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 186      | 98.94%  |
| No        | 2        | 1.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 106      | 54.64%  |
| No        | 88       | 45.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 56.08%  |
| Yes       | 83       | 43.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 188      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 180      | 95.24%  |
| Kampong Pasir Ris | 5        | 2.65%   |
| Jurong West       | 3        | 1.59%   |
| Queenstown Estate | 1        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 62       | 103    | 17.87%  |
| WDC                          | 46       | 84     | 13.26%  |
| Seagate                      | 45       | 57     | 12.97%  |
| Toshiba                      | 27       | 36     | 7.78%   |
| SanDisk                      | 26       | 33     | 7.49%   |
| Unknown                      | 12       | 15     | 3.46%   |
| Crucial                      | 11       | 17     | 3.17%   |
| Kingston                     | 10       | 14     | 2.88%   |
| Hitachi                      | 7        | 8      | 2.02%   |
| Silicon Motion               | 6        | 8      | 1.73%   |
| Micron/Crucial Technology    | 6        | 8      | 1.73%   |
| China                        | 5        | 6      | 1.44%   |
| A-DATA Technology            | 5        | 5      | 1.44%   |
| Transcend                    | 4        | 6      | 1.15%   |
| Phison Electronics           | 4        | 7      | 1.15%   |
| Kingston Technology Company  | 4        | 4      | 1.15%   |
| Intel                        | 4        | 5      | 1.15%   |
| Plextor                      | 3        | 3      | 0.86%   |
| Phison                       | 3        | 3      | 0.86%   |
| Lexar                        | 3        | 3      | 0.86%   |
| JMicron Technology           | 3        | 4      | 0.86%   |
| HGST                         | 3        | 5      | 0.86%   |
| Yangtze Memory Technologies  | 2        | 2      | 0.58%   |
| SK hynix                     | 2        | 2      | 0.58%   |
| Shenzhen Longsys Electronics | 2        | 4      | 0.58%   |
| Realtek Semiconductor        | 2        | 2      | 0.58%   |
| Maxtor                       | 2        | 2      | 0.58%   |
| MAXIO Technology (Hangzhou)  | 2        | 2      | 0.58%   |
| KLEVV                        | 2        | 2      | 0.58%   |
| KingSpec                     | 2        | 3      | 0.58%   |
| Hewlett-Packard              | 2        | 2      | 0.58%   |
| WALRAM                       | 1        | 1      | 0.29%   |
| Vaseky                       | 1        | 1      | 0.29%   |
| USB30                        | 1        | 1      | 0.29%   |
| TREK 256                     | 1        | 1      | 0.29%   |
| Teclast                      | 1        | 1      | 0.29%   |
| SSK                          | 1        | 1      | 0.29%   |
| SABRENT                      | 1        | 2      | 0.29%   |
| PNY                          | 1        | 1      | 0.29%   |
| Pioneer                      | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 10       | 2.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 8        | 2%      |
| Toshiba DT01ACA200 2TB                                | 7        | 1.75%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 5        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB                        | 5        | 1.25%   |
| Samsung SSD 980 PRO 1TB                               | 5        | 1.25%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 1.25%   |
| Samsung SSD 850 EVO 250GB                             | 5        | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4        | 1%      |
| Seagate ST500DM002-1BD142 500GB                       | 4        | 1%      |
| SanDisk NVMe SSD Drive 500GB                          | 4        | 1%      |
| Samsung SSD 980 500GB                                 | 4        | 1%      |
| Samsung SSD 860 EVO 500GB                             | 4        | 1%      |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 3        | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 0.75%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 3        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.75%   |
| SanDisk NVMe SSD Drive 1TB                            | 3        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 3        | 0.75%   |
| JMicron Generic 500GB                                 | 3        | 0.75%   |
| Crucial CT500MX500SSD1 500GB                          | 3        | 0.75%   |
| A-DATA HC660 1TB SSD                                  | 3        | 0.75%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 2        | 0.5%    |
| WDC WD5000AVDS-73U7B1 500GB                           | 2        | 0.5%    |
| Unknown NVMe SSD Drive 512GB                          | 2        | 0.5%    |
| Toshiba HDWD110 1TB                                   | 2        | 0.5%    |
| Toshiba DT01ACA050 500GB                              | 2        | 0.5%    |
| SK hynix SC311 SATA 128GB SSD                         | 2        | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.5%    |
| Seagate Expansion HDD 14TB                            | 2        | 0.5%    |
| Seagate BUP Portable 5TB                              | 2        | 0.5%    |
| Sandisk WD_BLACK SN850X 1000GB                        | 2        | 0.5%    |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 2        | 0.5%    |
| Sandisk WD Black SN850 2TB                            | 2        | 0.5%    |
| SanDisk SSD PLUS 480GB                                | 2        | 0.5%    |
| SanDisk SSD PLUS 1000GB                               | 2        | 0.5%    |
| SanDisk SDSSDA240G 240GB                              | 2        | 0.5%    |
| Samsung SSD 990 PRO 4TB                               | 2        | 0.5%    |
| Samsung SSD 980 1TB                                   | 2        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 55     | 33.85%  |
| WDC                 | 39       | 75     | 30%     |
| Toshiba             | 25       | 34     | 19.23%  |
| Hitachi             | 7        | 8      | 5.38%   |
| Samsung Electronics | 4        | 4      | 3.08%   |
| JMicron Technology  | 3        | 4      | 2.31%   |
| HGST                | 3        | 5      | 2.31%   |
| Maxtor              | 2        | 2      | 1.54%   |
| Unknown             | 1        | 1      | 0.77%   |
| SABRENT             | 1        | 2      | 0.77%   |
| MARVELL             | 1        | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 41     | 29.52%  |
| SanDisk             | 11       | 11     | 10.48%  |
| Crucial             | 8        | 14     | 7.62%   |
| Kingston            | 7        | 9      | 6.67%   |
| China               | 5        | 6      | 4.76%   |
| WDC                 | 4        | 4      | 3.81%   |
| Transcend           | 3        | 5      | 2.86%   |
| Plextor             | 3        | 3      | 2.86%   |
| A-DATA Technology   | 3        | 3      | 2.86%   |
| SK hynix            | 2        | 2      | 1.9%    |
| KingSpec            | 2        | 3      | 1.9%    |
| Intel               | 2        | 2      | 1.9%    |
| Hewlett-Packard     | 2        | 2      | 1.9%    |
| WALRAM              | 1        | 1      | 0.95%   |
| Vaseky              | 1        | 1      | 0.95%   |
| USB30               | 1        | 1      | 0.95%   |
| Unknown             | 1        | 1      | 0.95%   |
| TREK 256            | 1        | 1      | 0.95%   |
| Teclast             | 1        | 1      | 0.95%   |
| Pioneer             | 1        | 1      | 0.95%   |
| OCZ                 | 1        | 1      | 0.95%   |
| Micron Technology   | 1        | 1      | 0.95%   |
| LITEONIT            | 1        | 1      | 0.95%   |
| Lexar               | 1        | 1      | 0.95%   |
| Lenovo              | 1        | 1      | 0.95%   |
| KLEVV               | 1        | 1      | 0.95%   |
| Kingmax             | 1        | 1      | 0.95%   |
| KINGBANK            | 1        | 1      | 0.95%   |
| Indilinx            | 1        | 1      | 0.95%   |
| GAMER               | 1        | 1      | 0.95%   |
| GALAX               | 1        | 1      | 0.95%   |
| Fanxiang            | 1        | 1      | 0.95%   |
| BIWIN               | 1        | 1      | 0.95%   |
| Apacer              | 1        | 1      | 0.95%   |
| Unknown             | 1        | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 103      | 191    | 36.27%  |
| NVMe    | 86       | 157    | 30.28%  |
| SSD     | 84       | 127    | 29.58%  |
| Unknown | 6        | 9      | 2.11%   |
| MMC     | 5        | 5      | 1.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 143      | 302    | 56.08%  |
| NVMe | 86       | 156    | 33.73%  |
| SAS  | 21       | 26     | 8.24%   |
| MMC  | 5        | 5      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 92       | 134    | 43.6%   |
| 0.51-1.0   | 63       | 96     | 29.86%  |
| 1.01-2.0   | 28       | 39     | 13.27%  |
| 4.01-10.0  | 10       | 26     | 4.74%   |
| 3.01-4.0   | 9        | 12     | 4.27%   |
| 2.01-3.0   | 5        | 5      | 2.37%   |
| 10.01-20.0 | 4        | 6      | 1.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 41       | 20.71%  |
| 101-250        | 29       | 14.65%  |
| More than 3000 | 25       | 12.63%  |
| 1001-2000      | 24       | 12.12%  |
| 251-500        | 23       | 11.62%  |
| 1-20           | 20       | 10.1%   |
| 2001-3000      | 14       | 7.07%   |
| Unknown        | 14       | 7.07%   |
| 51-100         | 5        | 2.53%   |
| 21-50          | 3        | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 56       | 27.45%  |
| 21-50          | 32       | 15.69%  |
| 101-250        | 28       | 13.73%  |
| 251-500        | 21       | 10.29%  |
| 1001-2000      | 17       | 8.33%   |
| 51-100         | 15       | 7.35%   |
| Unknown        | 14       | 6.86%   |
| 501-1000       | 13       | 6.37%   |
| More than 3000 | 7        | 3.43%   |
| 2001-3000      | 1        | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB         | 5        | 9      | 18.52%  |
| WDC WD5000AVDS-73U7B1 500GB         | 2        | 2      | 7.41%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1        | 1      | 3.7%    |
| WDC WD5000AAKS-22V1A0 500GB         | 1        | 1      | 3.7%    |
| WDC WD50 EZRX-00MVLB1 5TB           | 1        | 1      | 3.7%    |
| WDC WD3200AAJS-65M0A0 320GB         | 1        | 1      | 3.7%    |
| WDC WD1600AAJS-65WAA0 160GB         | 1        | 1      | 3.7%    |
| WDC WD10EZEX-60M2NA0 1TB            | 1        | 1      | 3.7%    |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 3.7%    |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 1      | 3.7%    |
| Toshiba DT01ACA050 500GB            | 1        | 1      | 3.7%    |
| Teclast 480GB A800 SSD              | 1        | 1      | 3.7%    |
| Seagate ST8000NM0055-1RM112 8TB     | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.7%    |
| Seagate ST3160811AS 160GB           | 1        | 1      | 3.7%    |
| Seagate ST31500341AS 1TB            | 1        | 1      | 3.7%    |
| Seagate ST2000LM007-1R8174 2TB      | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 980 PRO 1TB | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 970 PRO 1TB | 1        | 1      | 3.7%    |
| Hitachi HDS721010CLA632 1TB         | 1        | 1      | 3.7%    |
| HGST HTS545050A7E380 500GB          | 1        | 1      | 3.7%    |
| Crucial CT120M500SSD1 120GB         | 1        | 6      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 19     | 52.17%  |
| Seagate             | 4        | 5      | 17.39%  |
| Samsung Electronics | 2        | 2      | 8.7%    |
| Toshiba             | 1        | 1      | 4.35%   |
| Teclast             | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| Crucial             | 1        | 6      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 12       | 19     | 63.16%  |
| Seagate | 4        | 5      | 21.05%  |
| Toshiba | 1        | 1      | 5.26%   |
| Hitachi | 1        | 1      | 5.26%   |
| HGST    | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 27     | 81.82%  |
| NVMe | 2        | 2      | 9.09%   |
| SSD  | 2        | 7      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD1002FAEX-00Z3A0 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 101      | 227    | 45.7%   |
| Works    | 97       | 225    | 43.89%  |
| Malfunc  | 22       | 36     | 9.95%   |
| Failed   | 1        | 1      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 118      | 38.06%  |
| AMD                          | 61       | 19.68%  |
| Samsung Electronics          | 40       | 12.9%   |
| SanDisk                      | 20       | 6.45%   |
| ASMedia Technology           | 10       | 3.23%   |
| Silicon Motion               | 8        | 2.58%   |
| Micron/Crucial Technology    | 8        | 2.58%   |
| Phison Electronics           | 7        | 2.26%   |
| Kingston Technology Company  | 6        | 1.94%   |
| Realtek Semiconductor        | 5        | 1.61%   |
| Shenzhen Longsys Electronics | 4        | 1.29%   |
| MAXIO Technology (Hangzhou)  | 3        | 0.97%   |
| Marvell Technology Group     | 3        | 0.97%   |
| Yangtze Memory Technologies  | 2        | 0.65%   |
| Toshiba America Info Systems | 2        | 0.65%   |
| Adaptec                      | 2        | 0.65%   |
| VIA Technologies             | 1        | 0.32%   |
| Transcend                    | 1        | 0.32%   |
| Seagate Technology           | 1        | 0.32%   |
| Red Hat                      | 1        | 0.32%   |
| Micron Technology            | 1        | 0.32%   |
| KIOXIA                       | 1        | 0.32%   |
| JMicron Technology           | 1        | 0.32%   |
| INNOGRIT                     | 1        | 0.32%   |
| Hosin Global Electronics     | 1        | 0.32%   |
| Broadcom / LSI               | 1        | 0.32%   |
| ADATA Technology             | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35       | 9.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20       | 5.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 4.8%    |
| Intel SATA Controller [RAID mode]                                                       | 11       | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 2.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 2.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 2.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 2.54%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 9        | 2.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 2.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 8        | 2.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.98%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 1.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 1.69%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.41%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 1.13%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 4        | 1.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.13%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4        | 1.13%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 4        | 1.13%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 1.13%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.13%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 3        | 0.85%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 3        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.85%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.85%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 3        | 0.85%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 2        | 0.56%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                       | 2        | 0.56%   |
| Shenzhen Longsys FORESEE XP2000, Lexar NM760 NVME SSD (DRAM-less)                       | 2        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 160      | 56.14%  |
| NVMe | 86       | 30.18%  |
| RAID | 17       | 5.96%   |
| IDE  | 17       | 5.96%   |
| SAS  | 4        | 1.4%    |
| SCSI | 1        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 124      | 65.96%  |
| AMD     | 63       | 33.51%  |
| Unknown | 1        | 0.53%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 7        | 3.7%    |
| Intel Core i5-8400 CPU @ 2.80GHz               | 5        | 2.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 4        | 2.12%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 4        | 2.12%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 4        | 2.12%   |
| Intel Core i9-14900K                           | 3        | 1.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 1.59%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 3        | 1.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.59%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 1.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 1.06%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 1.06%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 2        | 1.06%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 2        | 1.06%   |
| Intel Core i5-4690 CPU @ 3.50GHz               | 2        | 1.06%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 1.06%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 1.06%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 1.06%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 1.06%   |
| Intel Core i3 CPU 560 @ 3.33GHz                | 2        | 1.06%   |
| Intel Celeron CPU J1800 @ 2.41GHz              | 2        | 1.06%   |
| Intel 12th Gen Core i7-12700                   | 2        | 1.06%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 2        | 1.06%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 2        | 1.06%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 2        | 1.06%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 2        | 1.06%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 2        | 1.06%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 1.06%   |
| AMD Ryzen 5 3500X 6-Core Processor             | 2        | 1.06%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.06%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 2        | 1.06%   |
| Intel Xeon w9-3495X                            | 1        | 0.53%   |
| Intel Xeon W-2155 CPU @ 3.30GHz                | 1        | 0.53%   |
| Intel Xeon W-11855M CPU @ 3.20GHz              | 1        | 0.53%   |
| Intel Xeon CPU X3460 @ 2.80GHz                 | 1        | 0.53%   |
| Intel Xeon CPU W3680 @ 3.33GHz                 | 1        | 0.53%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2687W v3 @ 3.10GHz           | 1        | 0.53%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 42       | 22.22%  |
| AMD Ryzen 5            | 24       | 12.7%   |
| Intel Core i7          | 18       | 9.52%   |
| Intel Xeon             | 17       | 8.99%   |
| Other                  | 16       | 8.47%   |
| AMD Ryzen 7            | 13       | 6.88%   |
| Intel Core i3          | 10       | 5.29%   |
| AMD Ryzen 9            | 9        | 4.76%   |
| Intel Core i9          | 6        | 3.17%   |
| Intel Celeron          | 6        | 3.17%   |
| AMD Ryzen Threadripper | 4        | 2.12%   |
| Intel Pentium          | 2        | 1.06%   |
| Intel Core 2 Quad      | 2        | 1.06%   |
| Intel Atom             | 2        | 1.06%   |
| AMD Ryzen 3            | 2        | 1.06%   |
| AMD FX                 | 2        | 1.06%   |
| AMD Athlon             | 2        | 1.06%   |
| AMD A10                | 2        | 1.06%   |
| Intel Pentium Silver   | 1        | 0.53%   |
| Intel Pentium Gold     | 1        | 0.53%   |
| Intel Pentium Dual     | 1        | 0.53%   |
| Intel Pentium 4        | 1        | 0.53%   |
| Intel Core m3          | 1        | 0.53%   |
| AMD Ryzen 5 PRO        | 1        | 0.53%   |
| AMD PRO A10            | 1        | 0.53%   |
| AMD Phenom II X6       | 1        | 0.53%   |
| AMD Phenom II X4       | 1        | 0.53%   |
| AMD Opteron            | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 68       | 35.98%  |
| 6      | 36       | 19.05%  |
| 2      | 25       | 13.23%  |
| 8      | 20       | 10.58%  |
| 12     | 11       | 5.82%   |
| 16     | 8        | 4.23%   |
| 10     | 6        | 3.17%   |
| 24     | 4        | 2.12%   |
| 14     | 3        | 1.59%   |
| 32     | 2        | 1.06%   |
| 1      | 2        | 1.06%   |
| 56     | 1        | 0.53%   |
| 22     | 1        | 0.53%   |
| 20     | 1        | 0.53%   |
| 3      | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 185      | 98.4%   |
| 2      | 3        | 1.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 119      | 62.96%  |
| 1      | 70       | 37.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 187      | 99.47%  |
| Unknown        | 1        | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 80       | 40.2%   |
| 0x306c3    | 12       | 6.03%   |
| 0x306a9    | 9        | 4.52%   |
| 0x906ea    | 8        | 4.02%   |
| 0x506e3    | 7        | 3.52%   |
| 0x08701021 | 6        | 3.02%   |
| 0x206a7    | 5        | 2.51%   |
| 0x90672    | 4        | 2.01%   |
| 0x306e4    | 4        | 2.01%   |
| 0x20655    | 4        | 2.01%   |
| 0x50654    | 3        | 1.51%   |
| 0x0a601203 | 3        | 1.51%   |
| 0x0a20120a | 3        | 1.51%   |
| 0x0a201016 | 3        | 1.51%   |
| 0x08701013 | 3        | 1.51%   |
| 0x06003106 | 3        | 1.51%   |
| 0x906e9    | 2        | 1.01%   |
| 0x906c0    | 2        | 1.01%   |
| 0x406f1    | 2        | 1.01%   |
| 0x0a601206 | 2        | 1.01%   |
| 0x0a50000d | 2        | 1.01%   |
| 0x0a201009 | 2        | 1.01%   |
| 0x06000852 | 2        | 1.01%   |
| 0xf41      | 1        | 0.5%    |
| 0xb06e0    | 1        | 0.5%    |
| 0xb0671    | 1        | 0.5%    |
| 0xa0671    | 1        | 0.5%    |
| 0xa0655    | 1        | 0.5%    |
| 0x706a1    | 1        | 0.5%    |
| 0x6fd      | 1        | 0.5%    |
| 0x6fb      | 1        | 0.5%    |
| 0x1067a    | 1        | 0.5%    |
| 0x0a601201 | 1        | 0.5%    |
| 0x0a50000f | 1        | 0.5%    |
| 0x0a50000c | 1        | 0.5%    |
| 0x0a404102 | 1        | 0.5%    |
| 0x08600106 | 1        | 0.5%    |
| 0x0830107a | 1        | 0.5%    |
| 0x0830104d | 1        | 0.5%    |
| 0x08301039 | 1        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 22       | 11.58%  |
| IvyBridge        | 20       | 10.53%  |
| Zen 3            | 18       | 9.47%   |
| Zen 2            | 17       | 8.95%   |
| Unknown          | 16       | 8.42%   |
| KabyLake         | 15       | 7.89%   |
| Skylake          | 11       | 5.79%   |
| Alderlake Hybrid | 10       | 5.26%   |
| Westmere         | 7        | 3.68%   |
| SandyBridge      | 7        | 3.68%   |
| Zen+             | 6        | 3.16%   |
| Zen              | 5        | 2.63%   |
| CometLake        | 5        | 2.63%   |
| Silvermont       | 4        | 2.11%   |
| Steamroller      | 3        | 1.58%   |
| K10              | 3        | 1.58%   |
| Broadwell        | 3        | 1.58%   |
| Tremont          | 2        | 1.05%   |
| Piledriver       | 2        | 1.05%   |
| Gracemont        | 2        | 1.05%   |
| Goldmont         | 2        | 1.05%   |
| Core             | 2        | 1.05%   |
| TigerLake        | 1        | 0.53%   |
| Sapphire Rapids  | 1        | 0.53%   |
| Penryn           | 1        | 0.53%   |
| NetBurst         | 1        | 0.53%   |
| Nehalem          | 1        | 0.53%   |
| Icelake          | 1        | 0.53%   |
| Goldmont plus    | 1        | 0.53%   |
| Excavator        | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 81       | 37.16%  |
| Intel             | 75       | 34.4%   |
| AMD               | 60       | 27.52%  |
| Red Hat           | 1        | 0.46%   |
| ASPEED Technology | 1        | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 4.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 3.1%    |
| Intel HD Graphics 530                                                       | 6        | 2.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.65%   |
| AMD Raphael                                                                 | 6        | 2.65%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 2.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.77%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.77%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 1.77%   |
| Intel AlderLake-S GT1                                                       | 4        | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.33%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.33%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 3        | 1.33%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 1.33%   |
| Intel JasperLake [UHD Graphics]                                             | 3        | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 1.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.33%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 1.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.33%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.33%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 3        | 1.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.88%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.88%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.88%   |
| Nvidia GF119 [GeForce 605]                                                  | 2        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 2        | 0.88%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.88%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 0.88%   |
| Intel Raptor Lake-P [UHD Graphics]                                          | 2        | 0.88%   |
| Intel HD Graphics 630                                                       | 2        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 63       | 32.31%  |
| 1 x Intel            | 58       | 29.74%  |
| 1 x AMD              | 45       | 23.08%  |
| Intel + Nvidia       | 6        | 3.08%   |
| 2 x Nvidia           | 5        | 2.56%   |
| Intel + AMD          | 5        | 2.56%   |
| AMD + Nvidia         | 5        | 2.56%   |
| 2 x AMD              | 3        | 1.54%   |
| Other                | 2        | 1.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.51%   |
| 1 x Red Hat          | 1        | 0.51%   |
| Nvidia + ASPEED      | 1        | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 123      | 63.73%  |
| Proprietary | 56       | 29.02%  |
| Unknown     | 14       | 7.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 46.19%  |
| 1.01-2.0   | 22       | 11.17%  |
| 8.01-16.0  | 19       | 9.64%   |
| 7.01-8.0   | 17       | 8.63%   |
| 3.01-4.0   | 16       | 8.12%   |
| 0.51-1.0   | 12       | 6.09%   |
| 0.01-0.5   | 11       | 5.58%   |
| 5.01-6.0   | 6        | 3.05%   |
| 16.01-24.0 | 3        | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 49       | 25.79%  |
| Samsung Electronics  | 22       | 11.58%  |
| Hewlett-Packard      | 12       | 6.32%   |
| Goldstar             | 11       | 5.79%   |
| Acer                 | 11       | 5.79%   |
| Philips              | 9        | 4.74%   |
| AOC                  | 7        | 3.68%   |
| ViewSonic            | 5        | 2.63%   |
| Denver               | 5        | 2.63%   |
| PRISM+               | 4        | 2.11%   |
| Mi                   | 4        | 2.11%   |
| Pixio                | 3        | 1.58%   |
| LG Electronics       | 3        | 1.58%   |
| Lenovo               | 3        | 1.58%   |
| AU Optronics         | 3        | 1.58%   |
| ASUSTek Computer     | 3        | 1.58%   |
| Ancor Communications | 3        | 1.58%   |
| Unknown              | 3        | 1.58%   |
| Unknown (XXX)        | 2        | 1.05%   |
| Sharp                | 2        | 1.05%   |
| MSI                  | 2        | 1.05%   |
| Lenovo Group Limited | 2        | 1.05%   |
| Xiaomi               | 1        | 0.53%   |
| Wacom                | 1        | 0.53%   |
| Toshiba              | 1        | 0.53%   |
| Sony                 | 1        | 0.53%   |
| SGT                  | 1        | 0.53%   |
| SAC                  | 1        | 0.53%   |
| RTK                  | 1        | 0.53%   |
| RHT                  | 1        | 0.53%   |
| InnoView             | 1        | 0.53%   |
| IDV                  | 1        | 0.53%   |
| HPN                  | 1        | 0.53%   |
| HPD                  | 1        | 0.53%   |
| HKC                  | 1        | 0.53%   |
| GLE                  | 1        | 0.53%   |
| Fujitsu Siemens      | 1        | 0.53%   |
| Flipbook             | 1        | 0.53%   |
| CVT                  | 1        | 0.53%   |
| CHR                  | 1        | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 4        | 2%      |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                    | 4        | 2%      |
| Pixio HDMI WAM2700 2560x1440 597x336mm 27.0-inch                    | 3        | 1.5%    |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch               | 3        | 1.5%    |
| Dell D2015H DELF063 1920x1080 440x240mm 19.7-inch                   | 3        | 1.5%    |
| Unknown                                                             | 3        | 1.5%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch   | 2        | 1%      |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch | 2        | 1%      |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch   | 2        | 1%      |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch             | 2        | 1%      |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                 | 2        | 1%      |
| Denver VN24F165 LHC0236 1920x1080 598x336mm 27.0-inch               | 2        | 1%      |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                 | 2        | 1%      |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                 | 2        | 1%      |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                   | 2        | 1%      |
| Dell LCD Monitor P2217H 1920x1080                                   | 2        | 1%      |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                  | 2        | 1%      |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                   | 2        | 1%      |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                    | 2        | 1%      |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                  | 2        | 1%      |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                    | 2        | 1%      |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                 | 2        | 1%      |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                  | 1        | 0.5%    |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch            | 1        | 0.5%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch          | 1        | 0.5%    |
| ViewSonic VX2705-2KP VSC3B3A 2560x1440 597x336mm 27.0-inch          | 1        | 0.5%    |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 527x296mm 23.8-inch           | 1        | 0.5%    |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                           | 1        | 0.5%    |
| ViewSonic LCD Monitor VA2261 Series 3840x1080                       | 1        | 0.5%    |
| ViewSonic LCD Monitor VA2210-FHD                                    | 1        | 0.5%    |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch       | 1        | 0.5%    |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch      | 1        | 0.5%    |
| Toshiba TV TSB0110 1920x1080 706x398mm 31.9-inch                    | 1        | 0.5%    |
| Sony TV SNY2C02 1920x1080 886x498mm 40.0-inch                       | 1        | 0.5%    |
| Sharp HDMI SHP1197 1920x1080 1103x622mm 49.9-inch                   | 1        | 0.5%    |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                    | 1        | 0.5%    |
| SGT HDMI SGT0156 1920x1080 345x194mm 15.6-inch                      | 1        | 0.5%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch   | 1        | 0.5%    |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch   | 1        | 0.5%    |
| Samsung Electronics S22C300 SAM0A1D 1920x1080 477x268mm 21.5-inch   | 1        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 96       | 50.53%  |
| 2560x1440 (QHD)    | 32       | 16.84%  |
| 3840x2160 (4K)     | 27       | 14.21%  |
| 1600x900 (HD+)     | 14       | 7.37%   |
| 3440x1440          | 3        | 1.58%   |
| 3840x1080          | 2        | 1.05%   |
| 2560x1080          | 2        | 1.05%   |
| 1680x1050 (WSXGA+) | 2        | 1.05%   |
| 1366x768 (WXGA)    | 2        | 1.05%   |
| 1360x768           | 2        | 1.05%   |
| 1280x1024 (SXGA)   | 2        | 1.05%   |
| Unknown            | 2        | 1.05%   |
| 7680x2160          | 1        | 0.53%   |
| 2560x1600          | 1        | 0.53%   |
| 2048x1152          | 1        | 0.53%   |
| 1440x900 (WXGA+)   | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 35       | 18.72%  |
| 24      | 25       | 13.37%  |
| 23      | 23       | 12.3%   |
| Unknown | 23       | 12.3%   |
| 21      | 16       | 8.56%   |
| 31      | 10       | 5.35%   |
| 20      | 10       | 5.35%   |
| 19      | 8        | 4.28%   |
| 18      | 4        | 2.14%   |
| 54      | 3        | 1.6%    |
| 28      | 3        | 1.6%    |
| 15      | 3        | 1.6%    |
| 84      | 2        | 1.07%   |
| 49      | 2        | 1.07%   |
| 40      | 2        | 1.07%   |
| 34      | 2        | 1.07%   |
| 32      | 2        | 1.07%   |
| 22      | 2        | 1.07%   |
| 72      | 1        | 0.53%   |
| 65      | 1        | 0.53%   |
| 57      | 1        | 0.53%   |
| 55      | 1        | 0.53%   |
| 50      | 1        | 0.53%   |
| 39      | 1        | 0.53%   |
| 33      | 1        | 0.53%   |
| 25      | 1        | 0.53%   |
| 17      | 1        | 0.53%   |
| 16      | 1        | 0.53%   |
| 14      | 1        | 0.53%   |
| 13      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 79       | 42.93%  |
| 401-500     | 38       | 20.65%  |
| Unknown     | 23       | 12.5%   |
| 601-700     | 15       | 8.15%   |
| 1001-1500   | 9        | 4.89%   |
| 701-800     | 5        | 2.72%   |
| 301-350     | 5        | 2.72%   |
| 801-900     | 3        | 1.63%   |
| 351-400     | 3        | 1.63%   |
| 1501-2000   | 3        | 1.63%   |
| 201-300     | 1        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 142      | 80.23%  |
| Unknown | 21       | 11.86%  |
| 16/10   | 5        | 2.82%   |
| 21/9    | 4        | 2.26%   |
| 5/4     | 2        | 1.13%   |
| 32/9    | 2        | 1.13%   |
| 6/5     | 1        | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 54       | 29.03%  |
| 301-350        | 35       | 18.82%  |
| 151-200        | 23       | 12.37%  |
| Unknown        | 23       | 12.37%  |
| 351-500        | 17       | 9.14%   |
| More than 1000 | 10       | 5.38%   |
| 251-300        | 9        | 4.84%   |
| 501-1000       | 5        | 2.69%   |
| 141-150        | 4        | 2.15%   |
| 101-110        | 4        | 2.15%   |
| 81-90          | 1        | 0.54%   |
| 71-80          | 1        | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 97       | 51.05%  |
| 101-120 | 40       | 21.05%  |
| Unknown | 23       | 12.11%  |
| 121-160 | 14       | 7.37%   |
| 161-240 | 10       | 5.26%   |
| 1-50    | 6        | 3.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 157      | 80.51%  |
| 2     | 19       | 9.74%   |
| 0     | 17       | 8.72%   |
| 3     | 2        | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 112      | 39.3%   |
| Intel                     | 103      | 36.14%  |
| Qualcomm Atheros          | 15       | 5.26%   |
| MediaTek                  | 11       | 3.86%   |
| TP-Link                   | 8        | 2.81%   |
| Broadcom                  | 7        | 2.46%   |
| Aquantia                  | 7        | 2.46%   |
| Ralink Technology         | 5        | 1.75%   |
| ASUSTek Computer          | 3        | 1.05%   |
| Samsung Electronics       | 2        | 0.7%    |
| Xilinx                    | 1        | 0.35%   |
| Solarflare Communications | 1        | 0.35%   |
| Qualcomm                  | 1        | 0.35%   |
| Microsoft                 | 1        | 0.35%   |
| Mellanox Technologies     | 1        | 0.35%   |
| Linux Foundation          | 1        | 0.35%   |
| Linksys                   | 1        | 0.35%   |
| Hewlett-Packard           | 1        | 0.35%   |
| Fargo                     | 1        | 0.35%   |
| Exar                      | 1        | 0.35%   |
| Edimax Technology         | 1        | 0.35%   |
| ASIX Electronics          | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 86       | 25.6%   |
| Intel Wi-Fi 6 AX200                                                            | 19       | 5.65%   |
| Intel Ethernet Controller I225-V                                               | 17       | 5.06%   |
| Realtek RTL8125 2.5GbE Controller                                              | 16       | 4.76%   |
| Intel I211 Gigabit Network Connection                                          | 13       | 3.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 7        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7        | 2.08%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 5        | 1.49%   |
| Intel Ethernet Controller I226-V                                               | 5        | 1.49%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 1.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 5        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4        | 1.19%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 1.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4        | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4        | 1.19%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 4        | 1.19%   |
| Realtek 802.11ac NIC                                                           | 3        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3        | 0.89%   |
| Intel Wireless 8260                                                            | 3        | 0.89%   |
| Intel Wireless 3165                                                            | 3        | 0.89%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 3        | 0.89%   |
| Intel Ethernet Connection I217-V                                               | 3        | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3        | 0.89%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 0.89%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 3        | 0.89%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                | 3        | 0.89%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                     | 2        | 0.6%    |
| TP-Link Archer T4U ver.3                                                       | 2        | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                | 2        | 0.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2        | 0.6%    |
| Intel Wireless 7260                                                            | 2        | 0.6%    |
| Intel I350 Gigabit Network Connection                                          | 2        | 0.6%    |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 52       | 47.71%  |
| Realtek Semiconductor | 15       | 13.76%  |
| Qualcomm Atheros      | 10       | 9.17%   |
| MediaTek              | 9        | 8.26%   |
| TP-Link               | 8        | 7.34%   |
| Ralink Technology     | 5        | 4.59%   |
| Broadcom              | 4        | 3.67%   |
| ASUSTek Computer      | 3        | 2.75%   |
| Microsoft             | 1        | 0.92%   |
| Linksys               | 1        | 0.92%   |
| Edimax Technology     | 1        | 0.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 19       | 17.12%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 7        | 6.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 5        | 4.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                | 5        | 4.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 4        | 3.6%    |
| Ralink MT7601U Wireless Adapter                                 | 4        | 3.6%    |
| Realtek 802.11ac NIC                                            | 3        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 3        | 2.7%    |
| Intel Wireless 8260                                             | 3        | 2.7%    |
| Intel Wireless 3165                                             | 3        | 2.7%    |
| Intel Raptor Lake-S PCH CNVi WiFi                               | 3        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 3        | 2.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3        | 2.7%    |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3        | 2.7%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                      | 2        | 1.8%    |
| TP-Link Archer T4U ver.3                                        | 2        | 1.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 2        | 1.8%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                 | 2        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 2        | 1.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 2        | 1.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 2        | 1.8%    |
| Intel Wireless 7260                                             | 2        | 1.8%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 0.9%    |
| TP-Link 802.11ac WLAN Adapter                                   | 1        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 0.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 0.9%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 0.9%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 0.9%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter           | 1        | 0.9%    |
| Realtek 802.11be WLAN Adapter                                   | 1        | 0.9%    |
| Realtek 802.11ax WLAN Adapter                                   | 1        | 0.9%    |
| Realtek 802.11ac WLAN Adapter                                   | 1        | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1        | 0.9%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 0.9%    |
| Microsoft Xbox Wireless Adapter for Windows                     | 1        | 0.9%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter               | 1        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter   | 1        | 0.9%    |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter             | 1        | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 106      | 50.96%  |
| Intel                     | 76       | 36.54%  |
| Aquantia                  | 7        | 3.37%   |
| Qualcomm Atheros          | 6        | 2.88%   |
| Broadcom                  | 3        | 1.44%   |
| Samsung Electronics       | 2        | 0.96%   |
| MediaTek                  | 2        | 0.96%   |
| Xilinx                    | 1        | 0.48%   |
| Solarflare Communications | 1        | 0.48%   |
| Qualcomm                  | 1        | 0.48%   |
| Mellanox Technologies     | 1        | 0.48%   |
| Hewlett-Packard           | 1        | 0.48%   |
| ASIX Electronics          | 1        | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 86       | 38.74%  |
| Intel Ethernet Controller I225-V                                               | 17       | 7.66%   |
| Realtek RTL8125 2.5GbE Controller                                              | 16       | 7.21%   |
| Intel I211 Gigabit Network Connection                                          | 13       | 5.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7        | 3.15%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 2.7%    |
| Intel Ethernet Controller I226-V                                               | 5        | 2.25%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 2.25%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4        | 1.8%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 4        | 1.8%    |
| Intel Ethernet Connection I217-V                                               | 3        | 1.35%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 2        | 0.9%    |
| Intel I350 Gigabit Network Connection                                          | 2        | 0.9%    |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 0.9%    |
| Intel Ethernet Connection (2) I218-LM                                          | 2        | 0.9%    |
| Xilinx Ethernet controller                                                     | 1        | 0.45%   |
| Solarflare XtremeScale SFC9250 10/25/40/50/100G Ethernet Controller            | 1        | 0.45%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.45%   |
| Qualcomm POCO F3                                                               | 1        | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.45%   |
| Mellanox MT42822 BlueField-2 integrated ConnectX-6 Dx network controller       | 1        | 0.45%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                                        | 1        | 0.45%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                | 1        | 0.45%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                   | 1        | 0.45%   |
| Intel Ethernet Controller X550                                                 | 1        | 0.45%   |
| Intel Ethernet Connection X553 1GbE                                            | 1        | 0.45%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                     | 1        | 0.45%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 186      | 63.27%  |
| WiFi     | 105      | 35.71%  |
| Modem    | 2        | 0.68%   |
| Unknown  | 1        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 142      | 71.36%  |
| WiFi     | 56       | 28.14%  |
| Unknown  | 1        | 0.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 87       | 46.03%  |
| 1     | 85       | 44.97%  |
| 3     | 9        | 4.76%   |
| 0     | 3        | 1.59%   |
| 4     | 2        | 1.06%   |
| 9     | 1        | 0.53%   |
| 8     | 1        | 0.53%   |
| 6     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 173      | 92.02%  |
| Yes  | 15       | 7.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 50.56%  |
| Cambridge Silicon Radio         | 13       | 14.61%  |
| MediaTek                        | 6        | 6.74%   |
| TP-Link                         | 5        | 5.62%   |
| Realtek Semiconductor           | 5        | 5.62%   |
| Qualcomm Atheros Communications | 4        | 4.49%   |
| Foxconn / Hon Hai               | 4        | 4.49%   |
| IMC Networks                    | 2        | 2.25%   |
| Broadcom                        | 2        | 2.25%   |
| SINO WEALTH                     | 1        | 1.12%   |
| ASUSTek Computer                | 1        | 1.12%   |
| Unknown                         | 1        | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 15       | 16.85%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 14.61%  |
| Intel Bluetooth wireless interface                  | 9        | 10.11%  |
| MediaTek Wireless_Device                            | 6        | 6.74%   |
| Intel AX210 Bluetooth                               | 6        | 6.74%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 5        | 5.62%   |
| Intel AX211 Bluetooth                               | 4        | 4.49%   |
| Intel AX201 Bluetooth                               | 4        | 4.49%   |
| Realtek Bluetooth Radio                             | 3        | 3.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 3.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 3.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 2.25%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 2.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 2.25%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.12%   |
| Intel Bluetooth Device                              | 1        | 1.12%   |
| IMC Networks Wireless_Device                        | 1        | 1.12%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1        | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 1.12%   |
| ASUS ASUS USB-BT500                                 | 1        | 1.12%   |
| Unknown                                             | 1        | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 120      | 38.96%  |
| Nvidia                                       | 75       | 24.35%  |
| AMD                                          | 71       | 23.05%  |
| ASUSTek Computer                             | 5        | 1.62%   |
| C-Media Electronics                          | 4        | 1.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.65%   |
| TTGK Technology                              | 2        | 0.65%   |
| SteelSeries ApS                              | 2        | 0.65%   |
| Sony                                         | 2        | 0.65%   |
| Micro Star International                     | 2        | 0.65%   |
| Giga-Byte Technology                         | 2        | 0.65%   |
| Creative Labs                                | 2        | 0.65%   |
| XMOS                                         | 1        | 0.32%   |
| Xiaomi                                       | 1        | 0.32%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.32%   |
| Texas Instruments                            | 1        | 0.32%   |
| Tenx Technology                              | 1        | 0.32%   |
| Setek Elektronik                             | 1        | 0.32%   |
| SAVITECH                                     | 1        | 0.32%   |
| Samsung Electronics                          | 1        | 0.32%   |
| Samson Technologies                          | 1        | 0.32%   |
| RODE Microphones                             | 1        | 0.32%   |
| Realtek Semiconductor                        | 1        | 0.32%   |
| MV                                           | 1        | 0.32%   |
| Logitech                                     | 1        | 0.32%   |
| JMTek                                        | 1        | 0.32%   |
| Jieli Technology                             | 1        | 0.32%   |
| Huawei Technologies                          | 1        | 0.32%   |
| FiiO Electronics Technology                  | 1        | 0.32%   |
| DSEA A/S                                     | 1        | 0.32%   |
| Creative Technology                          | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 25       | 6.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 5.51%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 18       | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 3.31%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 2.75%   |
| Nvidia GA104 High Definition Audio Controller                              | 8        | 2.2%    |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7        | 1.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 1.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.38%   |
| Nvidia GA102 High Definition Audio Controller                              | 5        | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.1%    |
| Nvidia GP102 HDMI Audio Controller                                         | 4        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.1%    |
| Intel Raptor Lake High Definition Audio Controller                         | 4        | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.1%    |
| ASUSTek Computer USB Audio                                                 | 4        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.83%   |
| Nvidia AD102 High Definition Audio Controller                              | 3        | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 0.83%   |
| Intel Jasper Lake HD Audio                                                 | 3        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 22       | 15.71%  |
| Crucial                        | 15       | 10.71%  |
| Corsair                        | 15       | 10.71%  |
| G.Skill                        | 14       | 10%     |
| Samsung Electronics            | 13       | 9.29%   |
| Micron Technology              | 12       | 8.57%   |
| SK hynix                       | 10       | 7.14%   |
| KLEVV                          | 6        | 4.29%   |
| A-DATA Technology              | 5        | 3.57%   |
| Unknown                        | 3        | 2.14%   |
| Transcend                      | 3        | 2.14%   |
| Unknown (ABCD)                 | 2        | 1.43%   |
| Kingmax                        | 2        | 1.43%   |
| Unknown                        | 2        | 1.43%   |
| Unknown (0x0E9D)               | 1        | 0.71%   |
| Unknown (0x0E25)               | 1        | 0.71%   |
| Unknown (0x0B92)               | 1        | 0.71%   |
| Red Hat                        | 1        | 0.71%   |
| Ramos Technology               | 1        | 0.71%   |
| Qimonda                        | 1        | 0.71%   |
| Patriot                        | 1        | 0.71%   |
| Nanya Technology               | 1        | 0.71%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 0.71%   |
| Lexar                          | 1        | 0.71%   |
| Kingmax Semiconductor          | 1        | 0.71%   |
| Essencore Limited              | 1        | 0.71%   |
| Elpida                         | 1        | 0.71%   |
| ASint Technology               | 1        | 0.71%   |
| Apotop                         | 1        | 0.71%   |
| Apacer                         | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s           | 3        | 1.89%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 3        | 1.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 2        | 1.26%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s               | 2        | 1.26%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s              | 2        | 1.26%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s            | 2        | 1.26%   |
| Kingston RAM 9905471-021.A00LF 4GB DIMM DDR3 1333MT/s            | 2        | 1.26%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 2        | 1.26%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s           | 2        | 1.26%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s             | 2        | 1.26%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3600MT/s              | 2        | 1.26%   |
| Crucial RAM CT8G4DFS8213.C8FBD1 8GB DIMM DDR4 2133MT/s           | 2        | 1.26%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2        | 1.26%   |
| Unknown                                                          | 2        | 1.26%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1        | 0.63%   |
| Unknown RAM Module 32GB DIMM DDR4 2666MT/s                       | 1        | 0.63%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.63%   |
| Unknown (0x0E25) RAM HMA82GS6AFR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 0.63%   |
| Unknown (0x0B92) RAM Module 16GB DIMM DDR4 3200MT/s              | 1        | 0.63%   |
| Transcend RAM TS1GSH64V2B 8GB SODIMM DDR4 3200MT/s               | 1        | 0.63%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                 | 1        | 0.63%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                | 1        | 0.63%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                       | 1        | 0.63%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1        | 0.63%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s                  | 1        | 0.63%   |
| SK hynix RAM HMA84GL7MMR4N-TF 32GB DIMM DDR4 2133MT/s            | 1        | 0.63%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2400MT/s             | 1        | 0.63%   |
| SK hynix RAM HMA451U6AFR8N-TF 4096MB DIMM DDR4 2133MT/s          | 1        | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1        | 0.63%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1        | 0.63%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1        | 0.63%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s              | 1        | 0.63%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s            | 1        | 0.63%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s              | 1        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 64       | 50.79%  |
| DDR3    | 35       | 27.78%  |
| DDR5    | 15       | 11.9%   |
| SDRAM   | 6        | 4.76%   |
| LPDDR4  | 2        | 1.59%   |
| DDR2    | 2        | 1.59%   |
| RAM     | 1        | 0.79%   |
| Unknown | 1        | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 106      | 88.33%  |
| SODIMM | 14       | 11.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 32.09%  |
| 16384 | 38       | 28.36%  |
| 4096  | 25       | 18.66%  |
| 32768 | 16       | 11.94%  |
| 2048  | 9        | 6.72%   |
| 65536 | 1        | 0.75%   |
| 49152 | 1        | 0.75%   |
| 1024  | 1        | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 18.06%  |
| 3200    | 17       | 11.81%  |
| 2400    | 16       | 11.11%  |
| 3600    | 13       | 9.03%   |
| 2667    | 9        | 6.25%   |
| 1333    | 9        | 6.25%   |
| 2666    | 7        | 4.86%   |
| 2133    | 6        | 4.17%   |
| 6000    | 5        | 3.47%   |
| 5600    | 3        | 2.08%   |
| 4800    | 3        | 2.08%   |
| 6400    | 2        | 1.39%   |
| 3733    | 2        | 1.39%   |
| 3666    | 2        | 1.39%   |
| 3400    | 2        | 1.39%   |
| 2048    | 2        | 1.39%   |
| 1867    | 2        | 1.39%   |
| 1866    | 2        | 1.39%   |
| 1800    | 2        | 1.39%   |
| 7000    | 1        | 0.69%   |
| 5808    | 1        | 0.69%   |
| 5200    | 1        | 0.69%   |
| 4333    | 1        | 0.69%   |
| 4000    | 1        | 0.69%   |
| 3866    | 1        | 0.69%   |
| 3800    | 1        | 0.69%   |
| 3266    | 1        | 0.69%   |
| 2933    | 1        | 0.69%   |
| 2200    | 1        | 0.69%   |
| 2134    | 1        | 0.69%   |
| 1067    | 1        | 0.69%   |
| 667     | 1        | 0.69%   |
| Unknown | 1        | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 33.33%  |
| Philips (or NXP)    | 1        | 33.33%  |
| Brother Industries  | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung M2020 Series         | 1        | 33.33%  |
| Philips (or NXP) USB Printer | 1        | 33.33%  |
| Brother MFC-L2715DW series   | 1        | 33.33%  |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 8        | 44.44%  |
| Realtek Semiconductor    | 2        | 11.11%  |
| Microdia                 | 2        | 11.11%  |
| SN0002                   | 1        | 5.56%   |
| Samsung Electronics      | 1        | 5.56%   |
| Razer USA                | 1        | 5.56%   |
| Apple                    | 1        | 5.56%   |
| Alpha Imaging Technology | 1        | 5.56%   |
| Alcor Micro              | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 3        | 16.67%  |
| Logitech HD Webcam C615                 | 2        | 11.11%  |
| SN0002 2K USB Camera                    | 1        | 5.56%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 5.56%   |
| Realtek HP 1.0MP High Definition Webcam | 1        | 5.56%   |
| Realtek Asus laptop camera              | 1        | 5.56%   |
| Razer USA Razer Kiyo X                  | 1        | 5.56%   |
| Microdia Webcam Vitade AF               | 1        | 5.56%   |
| Microdia USB 2.0 Camera                 | 1        | 5.56%   |
| Logitech Webcam C310                    | 1        | 5.56%   |
| Logitech Webcam C270                    | 1        | 5.56%   |
| Logitech BRIO Ultra HD Webcam           | 1        | 5.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 1        | 5.56%   |
| Alpha Imaging HIK 4K Camera             | 1        | 5.56%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 100%    |

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
| 0     | 153      | 79.27%  |
| 1     | 37       | 19.17%  |
| 2     | 2        | 1.04%   |
| 6     | 1        | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 30.95%  |
| Net/wireless             | 11       | 26.19%  |
| Communication controller | 5        | 11.9%   |
| Unassigned class         | 4        | 9.52%   |
| Network                  | 2        | 4.76%   |
| Multimedia controller    | 2        | 4.76%   |
| Storage/raid             | 1        | 2.38%   |
| Storage                  | 1        | 2.38%   |
| Net/ethernet             | 1        | 2.38%   |
| Fingerprint reader       | 1        | 2.38%   |
| Dvb card                 | 1        | 2.38%   |

