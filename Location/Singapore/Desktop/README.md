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

Total: 305

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B650 GAMING X AX            | [a43d09ccc1](https://linux-hardware.org/?probe=a43d09ccc1) | Jan 02, 2026 |
| ASUSTek       | ROG STRIX B850-G GAMING ... | [93396a546d](https://linux-hardware.org/?probe=93396a546d) | Dec 21, 2025 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [d064c5d57c](https://linux-hardware.org/?probe=d064c5d57c) | Nov 28, 2025 |
| Unknown       | Unknown                     | [13e1fe170d](https://linux-hardware.org/?probe=13e1fe170d) | Nov 24, 2025 |
| Dell          | 06D7TR A00                  | [3d97437b73](https://linux-hardware.org/?probe=3d97437b73) | Nov 15, 2025 |
| MSI           | PRO A620M-E                 | [70d26dc564](https://linux-hardware.org/?probe=70d26dc564) | Nov 14, 2025 |
| Gigabyte      | B850M FORCE WIFI6E          | [5aaa0d6f63](https://linux-hardware.org/?probe=5aaa0d6f63) | Nov 01, 2025 |
| ASRock        | A520M-ITX/ac                | [722d690bbe](https://linux-hardware.org/?probe=722d690bbe) | Oct 30, 2025 |
| Gigabyte      | B850I AORUS PRO             | [559574682f](https://linux-hardware.org/?probe=559574682f) | Oct 26, 2025 |
| Gigabyte      | B850I AORUS PRO             | [9d79ea84ec](https://linux-hardware.org/?probe=9d79ea84ec) | Oct 26, 2025 |
| MSI           | PRO A620M-E                 | [aec15978f3](https://linux-hardware.org/?probe=aec15978f3) | Oct 20, 2025 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [65465c0fcd](https://linux-hardware.org/?probe=65465c0fcd) | Oct 15, 2025 |
| ASRock        | Z370M-ITX/ac                | [7f636defb3](https://linux-hardware.org/?probe=7f636defb3) | Oct 10, 2025 |
| ASRock        | A520M-ITX/ac                | [7df87d6736](https://linux-hardware.org/?probe=7df87d6736) | Sep 15, 2025 |
| ASUSTek       | B760M-AYW WIFI              | [51872d2bd2](https://linux-hardware.org/?probe=51872d2bd2) | Sep 11, 2025 |
| ASRock        | H71M-DGS                    | [4189223e78](https://linux-hardware.org/?probe=4189223e78) | Sep 08, 2025 |
| ASUSTek       | E3M-ET V5 SERIES            | [27f5d0880b](https://linux-hardware.org/?probe=27f5d0880b) | Sep 08, 2025 |
| Unknown       | G41 Series                  | [90199a413b](https://linux-hardware.org/?probe=90199a413b) | Sep 06, 2025 |
| JGINYUE       | B650I Night Devil Ver:      | [8708dbb004](https://linux-hardware.org/?probe=8708dbb004) | Sep 01, 2025 |
| ASRock        | B760 Pro RS/D4              | [3ef2062809](https://linux-hardware.org/?probe=3ef2062809) | Aug 27, 2025 |
| MSI           | PRO A620M-E                 | [e66e474b87](https://linux-hardware.org/?probe=e66e474b87) | Aug 12, 2025 |
| Gigabyte      | P75-D3P                     | [ad99467d1d](https://linux-hardware.org/?probe=ad99467d1d) | Aug 08, 2025 |
| Dell          | 0NW6H5 A00                  | [1cbca60644](https://linux-hardware.org/?probe=1cbca60644) | Jun 18, 2025 |
| Intel         | X99-DD31 V1.1               | [5dcd00cb57](https://linux-hardware.org/?probe=5dcd00cb57) | Jun 06, 2025 |
| ASRock        | Z270 Gaming K6              | [8e36114c05](https://linux-hardware.org/?probe=8e36114c05) | Jun 06, 2025 |
| ASUSTek       | E3M-ET V5 SERIES            | [d26e749216](https://linux-hardware.org/?probe=d26e749216) | May 30, 2025 |
| MSI           | PRO A620M-E                 | [714b654239](https://linux-hardware.org/?probe=714b654239) | May 29, 2025 |
| Gigabyte      | Z690 UD AX                  | [876e026a35](https://linux-hardware.org/?probe=876e026a35) | May 02, 2025 |
| ASUSTek       | Pro WS W790E-SAGE SE        | [870390b0c5](https://linux-hardware.org/?probe=870390b0c5) | Apr 17, 2025 |
| ASRock        | A320M-DGS                   | [ef0d53bd85](https://linux-hardware.org/?probe=ef0d53bd85) | Mar 29, 2025 |
| MSI           | X470 GAMING PRO             | [ac8b6efa68](https://linux-hardware.org/?probe=ac8b6efa68) | Mar 25, 2025 |
| ASRock        | B450M Steel Legend          | [beda3a889e](https://linux-hardware.org/?probe=beda3a889e) | Mar 23, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [e34fc06754](https://linux-hardware.org/?probe=e34fc06754) | Mar 14, 2025 |
| ASUSTek       | E3M-ET V5 SERIES            | [4919ae8bc9](https://linux-hardware.org/?probe=4919ae8bc9) | Mar 09, 2025 |
| Unknown       | Unknown                     | [cdb0d678f8](https://linux-hardware.org/?probe=cdb0d678f8) | Feb 25, 2025 |
| UGREEN        | DXP4800 Plus                | [b4d3ebcb90](https://linux-hardware.org/?probe=b4d3ebcb90) | Feb 25, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [b6fda2a1f1](https://linux-hardware.org/?probe=b6fda2a1f1) | Feb 25, 2025 |
| ASUSTek       | P8H61-M LX                  | [cb6de7afa0](https://linux-hardware.org/?probe=cb6de7afa0) | Feb 16, 2025 |
| HP            | 0B4Ch D                     | [81e16dc691](https://linux-hardware.org/?probe=81e16dc691) | Feb 15, 2025 |
| HP            | 0B4Ch D                     | [83b7108a86](https://linux-hardware.org/?probe=83b7108a86) | Feb 13, 2025 |
| ASUSTek       | E3M-ET V5 SERIES            | [874627fde8](https://linux-hardware.org/?probe=874627fde8) | Feb 06, 2025 |
| MSI           | MAG H670 TOMAHAWK WIFI D... | [9e8b80b31c](https://linux-hardware.org/?probe=9e8b80b31c) | Jan 24, 2025 |
| Gigabyte      | Z270-HD3P-CF                | [599fac64a3](https://linux-hardware.org/?probe=599fac64a3) | Jan 14, 2025 |
| ASRock        | B660 Steel Legend           | [535f1a93c4](https://linux-hardware.org/?probe=535f1a93c4) | Jan 09, 2025 |
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
| Ubuntu 20.04                 | 24       | 9.84%   |
| Ubuntu 22.04                 | 18       | 7.38%   |
| Ubuntu 18.04                 | 15       | 6.15%   |
| Arch Rolling                 | 13       | 5.33%   |
| Fedora 41                    | 8        | 3.28%   |
| Ubuntu 24.04                 | 7        | 2.87%   |
| Pop!_OS 22.04                | 5        | 2.05%   |
| OpenMandriva 24.12           | 5        | 2.05%   |
| Manjaro                      | 5        | 2.05%   |
| Linux Mint 21                | 5        | 2.05%   |
| Fedora 40                    | 5        | 2.05%   |
| Fedora 38                    | 5        | 2.05%   |
| Debian 12                    | 5        | 2.05%   |
| Zorin 17                     | 4        | 1.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.64%   |
| KDE neon 20.04               | 4        | 1.64%   |
| ArcoLinux Rolling            | 4        | 1.64%   |
| Ubuntu 23.10                 | 3        | 1.23%   |
| Pop!_OS 20.04                | 3        | 1.23%   |
| OpenMandriva 5.0             | 3        | 1.23%   |
| OpenMandriva 23.11           | 3        | 1.23%   |
| OpenMandriva 23.03           | 3        | 1.23%   |
| Linux Mint 21.2              | 3        | 1.23%   |
| Fedora 42                    | 3        | 1.23%   |
| Fedora 37                    | 3        | 1.23%   |
| Debian 11                    | 3        | 1.23%   |
| Ubuntu 25.04                 | 2        | 0.82%   |
| Ubuntu 21.04                 | 2        | 0.82%   |
| Rocky Linux 8.5              | 2        | 0.82%   |
| Pop!_OS 21.04                | 2        | 0.82%   |
| OpenMandriva 4.50            | 2        | 0.82%   |
| OpenMandriva 4.3             | 2        | 0.82%   |
| OpenMandriva 24.07           | 2        | 0.82%   |
| OpenMandriva 23.08           | 2        | 0.82%   |
| MX 21                        | 2        | 0.82%   |
| Linux Mint 20.3              | 2        | 0.82%   |
| Linux Mint 20                | 2        | 0.82%   |
| Kubuntu 24.04                | 2        | 0.82%   |
| Fedora 33                    | 2        | 0.82%   |
| EndeavourOS Rolling          | 2        | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 72       | 32.43%  |
| OpenMandriva  | 28       | 12.61%  |
| Fedora        | 20       | 9.01%   |
| Arch          | 15       | 6.76%   |
| Linux Mint    | 14       | 6.31%   |
| Pop!_OS       | 12       | 5.41%   |
| Debian        | 9        | 4.05%   |
| Manjaro       | 6        | 2.7%    |
| Zorin         | 5        | 2.25%   |
| Rocky Linux   | 4        | 1.8%    |
| openSUSE      | 4        | 1.8%    |
| KDE neon      | 4        | 1.8%    |
| ArcoLinux     | 4        | 1.8%    |
| Xubuntu       | 3        | 1.35%   |
| Kubuntu       | 3        | 1.35%   |
| Ubuntu Unity  | 2        | 0.9%    |
| MX            | 2        | 0.9%    |
| EndeavourOS   | 2        | 0.9%    |
| Ubuntu MATE   | 1        | 0.45%   |
| Ubuntu Kylin  | 1        | 0.45%   |
| Ubuntu Budgie | 1        | 0.45%   |
| SteamOS       | 1        | 0.45%   |
| Pikaos        | 1        | 0.45%   |
| Nobara        | 1        | 0.45%   |
| NixOS         | 1        | 0.45%   |
| Lubuntu       | 1        | 0.45%   |
| Gentoo        | 1        | 0.45%   |
| Garuda Linux  | 1        | 0.45%   |
| CentOS        | 1        | 0.45%   |
| Bazzite       | 1        | 0.45%   |
| Atz           | 1        | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.0-56-generic            | 7        | 2.62%   |
| 6.6.2-desktop-1omv2390       | 5        | 1.87%   |
| 6.12.1-desktop-1omv2490      | 5        | 1.87%   |
| 5.15.0-46-generic            | 4        | 1.5%    |
| 6.2.6-desktop-1omv2390       | 3        | 1.12%   |
| 6.2.0-39-generic             | 3        | 1.12%   |
| 5.4.0-29-generic             | 3        | 1.12%   |
| 5.19.0-35-generic            | 3        | 1.12%   |
| 5.15.0-58-generic            | 3        | 1.12%   |
| 6.9.3-76060903-generic       | 2        | 0.75%   |
| 6.8.0-60-generic             | 2        | 0.75%   |
| 6.8.0-52-generic             | 2        | 0.75%   |
| 6.5.0-28-generic             | 2        | 0.75%   |
| 6.5.0-14-generic             | 2        | 0.75%   |
| 6.4.8-desktop-2omv2390       | 2        | 0.75%   |
| 6.3.8-zen1-1-zen             | 2        | 0.75%   |
| 6.2.14-300.fc38.x86_64       | 2        | 0.75%   |
| 6.2.0-34-generic             | 2        | 0.75%   |
| 6.2.0-31-generic             | 2        | 0.75%   |
| 6.14.8-300.fc42.x86_64       | 2        | 0.75%   |
| 6.13.5-200.fc41.x86_64       | 2        | 0.75%   |
| 6.12.11-200.fc41.x86_64      | 2        | 0.75%   |
| 6.11.3-200.fc40.x86_64       | 2        | 0.75%   |
| 6.10.0-desktop-1omv2490      | 2        | 0.75%   |
| 6.0.15-300.fc37.x86_64       | 2        | 0.75%   |
| 5.9.8-200.fc33.x86_64        | 2        | 0.75%   |
| 5.4.0-7642-generic           | 2        | 0.75%   |
| 5.4.0-70-generic             | 2        | 0.75%   |
| 5.4.0-42-generic             | 2        | 0.75%   |
| 5.4.0-40-generic             | 2        | 0.75%   |
| 5.4.0-37-generic             | 2        | 0.75%   |
| 5.3.0-51-generic             | 2        | 0.75%   |
| 5.16.7-desktop-1omv4003      | 2        | 0.75%   |
| 5.15.0-91-generic            | 2        | 0.75%   |
| 5.15.0-71-generic            | 2        | 0.75%   |
| 5.15.0-52-generic            | 2        | 0.75%   |
| 5.12.7-desktop-1omv4003      | 2        | 0.75%   |
| 5.11.0-27-generic            | 2        | 0.75%   |
| 5.0.0-36-generic             | 2        | 0.75%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 27       | 10.38%  |
| 5.4.0   | 24       | 9.23%   |
| 6.8.0   | 13       | 5%      |
| 6.2.0   | 11       | 4.23%   |
| 6.5.0   | 7        | 2.69%   |
| 5.0.0   | 7        | 2.69%   |
| 6.14.0  | 6        | 2.31%   |
| 5.11.0  | 6        | 2.31%   |
| 6.6.2   | 5        | 1.92%   |
| 6.12.1  | 5        | 1.92%   |
| 5.10.0  | 5        | 1.92%   |
| 4.18.0  | 5        | 1.92%   |
| 4.15.0  | 4        | 1.54%   |
| 6.9.3   | 3        | 1.15%   |
| 6.3.8   | 3        | 1.15%   |
| 6.2.6   | 3        | 1.15%   |
| 5.8.0   | 3        | 1.15%   |
| 5.3.0   | 3        | 1.15%   |
| 5.19.0  | 3        | 1.15%   |
| 6.5.9   | 2        | 0.77%   |
| 6.4.8   | 2        | 0.77%   |
| 6.3.9   | 2        | 0.77%   |
| 6.2.14  | 2        | 0.77%   |
| 6.14.8  | 2        | 0.77%   |
| 6.13.5  | 2        | 0.77%   |
| 6.12.11 | 2        | 0.77%   |
| 6.11.3  | 2        | 0.77%   |
| 6.10.1  | 2        | 0.77%   |
| 6.10.0  | 2        | 0.77%   |
| 6.1.0   | 2        | 0.77%   |
| 6.0.15  | 2        | 0.77%   |
| 5.9.8   | 2        | 0.77%   |
| 5.16.7  | 2        | 0.77%   |
| 5.13.0  | 2        | 0.77%   |
| 5.12.7  | 2        | 0.77%   |
| 6.8.4   | 1        | 0.38%   |
| 6.8.12  | 1        | 0.38%   |
| 6.8.10  | 1        | 0.38%   |
| 6.7.0   | 1        | 0.38%   |
| 6.6.7   | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 34       | 13.18%  |
| 5.4     | 24       | 9.3%    |
| 6.2     | 17       | 6.59%   |
| 6.8     | 16       | 6.2%    |
| 6.12    | 12       | 4.65%   |
| 6.5     | 10       | 3.88%   |
| 6.14    | 10       | 3.88%   |
| 6.6     | 9        | 3.49%   |
| 6.4     | 9        | 3.49%   |
| 6.3     | 9        | 3.49%   |
| 6.11    | 9        | 3.49%   |
| 6.1     | 9        | 3.49%   |
| 6.10    | 7        | 2.71%   |
| 5.11    | 7        | 2.71%   |
| 5.10    | 7        | 2.71%   |
| 5.0     | 7        | 2.71%   |
| 4.18    | 5        | 1.94%   |
| 6.0     | 4        | 1.55%   |
| 5.8     | 4        | 1.55%   |
| 5.16    | 4        | 1.55%   |
| 5.13    | 4        | 1.55%   |
| 4.15    | 4        | 1.55%   |
| 6.9     | 3        | 1.16%   |
| 6.17    | 3        | 1.16%   |
| 6.16    | 3        | 1.16%   |
| 6.13    | 3        | 1.16%   |
| 5.9     | 3        | 1.16%   |
| 5.3     | 3        | 1.16%   |
| 5.19    | 3        | 1.16%   |
| 5.14    | 3        | 1.16%   |
| 5.12    | 3        | 1.16%   |
| 6.15    | 2        | 0.78%   |
| 6.7     | 1        | 0.39%   |
| 6.3.0   | 1        | 0.39%   |
| 6.18    | 1        | 0.39%   |
| 5.18    | 1        | 0.39%   |
| 5.17    | 1        | 0.39%   |
| 4.16    | 1        | 0.39%   |
| 4.1     | 1        | 0.39%   |
| 3.10    | 1        | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 216      | 99.54%  |
| aarch64 | 1        | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 91       | 40.09%  |
| Unknown       | 38       | 16.74%  |
| KDE5          | 33       | 14.54%  |
| KDE6          | 17       | 7.49%   |
| X-Cinnamon    | 15       | 6.61%   |
| XFCE          | 10       | 4.41%   |
| LXQt          | 6        | 2.64%   |
| i3            | 3        | 1.32%   |
| Unity         | 2        | 0.88%   |
| Cinnamon      | 2        | 0.88%   |
| Budgie        | 2        | 0.88%   |
| UKUI          | 1        | 0.44%   |
| niri          | 1        | 0.44%   |
| MATE          | 1        | 0.44%   |
| KDE4          | 1        | 0.44%   |
| KDE           | 1        | 0.44%   |
| Hyprland      | 1        | 0.44%   |
| GNOME Classic | 1        | 0.44%   |
| COSMIC        | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 145      | 63.88%  |
| Wayland | 55       | 24.23%  |
| Unknown | 14       | 6.17%   |
| Tty     | 13       | 5.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 103      | 46.4%   |
| SDDM    | 48       | 21.62%  |
| GDM3    | 31       | 13.96%  |
| GDM     | 21       | 9.46%   |
| LightDM | 16       | 7.21%   |
| GREETD  | 2        | 0.9%    |
| TDM     | 1        | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 100      | 44.64%  |
| en_SG   | 75       | 33.48%  |
| Unknown | 15       | 6.7%    |
| zh_CN   | 11       | 4.91%   |
| C       | 6        | 2.68%   |
| de_DE   | 5        | 2.23%   |
| en_GB   | 4        | 1.79%   |
| en_AU   | 4        | 1.79%   |
| fr_FR   | 1        | 0.45%   |
| en_PH   | 1        | 0.45%   |
| en_IN   | 1        | 0.45%   |
| en_HK   | 1        | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 122      | 55.45%  |
| BIOS | 98       | 44.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 133      | 59.64%  |
| Btrfs   | 40       | 17.94%  |
| Overlay | 24       | 10.76%  |
| Xfs     | 12       | 5.38%   |
| Tmpfs   | 11       | 4.93%   |
| Unknown | 3        | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 121      | 55.25%  |
| Unknown | 81       | 36.99%  |
| MBR     | 17       | 7.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 74.77%  |
| Yes       | 56       | 25.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 66.52%  |
| Yes       | 74       | 33.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 43       | 19.82%  |
| Gigabyte Technology                  | 38       | 17.51%  |
| MSI                                  | 27       | 12.44%  |
| ASRock                               | 25       | 11.52%  |
| Dell                                 | 21       | 9.68%   |
| Unknown                              | 12       | 5.53%   |
| Hewlett-Packard                      | 11       | 5.07%   |
| Lenovo                               | 8        | 3.69%   |
| Foxconn                              | 4        | 1.84%   |
| Intel                                | 3        | 1.38%   |
| Acer                                 | 3        | 1.38%   |
| AZW                                  | 2        | 0.92%   |
| UGREEN                               | 1        | 0.46%   |
| SZMZ                                 | 1        | 0.46%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.46%   |
| Red Hat                              | 1        | 0.46%   |
| Pegatron                             | 1        | 0.46%   |
| Novatte                              | 1        | 0.46%   |
| MECHREVO                             | 1        | 0.46%   |
| MACHINIST                            | 1        | 0.46%   |
| LattePanda                           | 1        | 0.46%   |
| KunPengDianTong(KPDT)                | 1        | 0.46%   |
| JINGSHA                              | 1        | 0.46%   |
| JHZD                                 | 1        | 0.46%   |
| JGINYUE                              | 1        | 0.46%   |
| Huanan                               | 1        | 0.46%   |
| HPE                                  | 1        | 0.46%   |
| Fisusen Technology                   | 1        | 0.46%   |
| ECS                                  | 1        | 0.46%   |
| Dell EMC                             | 1        | 0.46%   |
| Biostar                              | 1        | 0.46%   |
| AMI                                  | 1        | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 13       | 5.99%   |
| ASUS All Series                            | 5        | 2.3%    |
| Gigabyte X570 AORUS PRO WIFI               | 4        | 1.84%   |
| MSI MS-7C84                                | 3        | 1.38%   |
| Foxconn Pro 3330 MT                        | 3        | 1.38%   |
| Dell OptiPlex 990                          | 3        | 1.38%   |
| Dell OptiPlex 9020                         | 3        | 1.38%   |
| ASUS ROG STRIX B650E-I GAMING WIFI         | 3        | 1.38%   |
| MSI MS-7E06                                | 2        | 0.92%   |
| MSI MS-7D25                                | 2        | 0.92%   |
| HP Z400 Workstation                        | 2        | 0.92%   |
| HP Z200 Workstation                        | 2        | 0.92%   |
| Gigabyte B85M-D3H                          | 2        | 0.92%   |
| Gigabyte B550M DS3H AC                     | 2        | 0.92%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 0.92%   |
| ASUS ROG STRIX B550-I GAMING               | 2        | 0.92%   |
| ASRock B450M Steel Legend                  | 2        | 0.92%   |
| ASRock B450 Pro4                           | 2        | 0.92%   |
| ASRock A320M-HDV R4.0                      | 2        | 0.92%   |
| UGREEN DXP4800 Plus                        | 1        | 0.46%   |
| SZMZ X99M-H2                               | 1        | 0.46%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.46%   |
| Red Hat KVM                                | 1        | 0.46%   |
| Pegatron 23-d018d                          | 1        | 0.46%   |
| Novatte M20                                | 1        | 0.46%   |
| MSI MS-7E28                                | 1        | 0.46%   |
| MSI MS-7D82                                | 1        | 0.46%   |
| MSI MS-7D43                                | 1        | 0.46%   |
| MSI MS-7D42                                | 1        | 0.46%   |
| MSI MS-7D30                                | 1        | 0.46%   |
| MSI MS-7C96                                | 1        | 0.46%   |
| MSI MS-7C95                                | 1        | 0.46%   |
| MSI MS-7C91                                | 1        | 0.46%   |
| MSI MS-7C60                                | 1        | 0.46%   |
| MSI MS-7C52                                | 1        | 0.46%   |
| MSI MS-7C02                                | 1        | 0.46%   |
| MSI MS-7B89                                | 1        | 0.46%   |
| MSI MS-7B79                                | 1        | 0.46%   |
| MSI MS-7A94                                | 1        | 0.46%   |
| MSI MS-7A38                                | 1        | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 14       | 6.45%   |
| Unknown                                    | 13       | 5.99%   |
| ASUS ROG                                   | 12       | 5.53%   |
| ASUS PRIME                                 | 6        | 2.76%   |
| ASUS All                                   | 5        | 2.3%    |
| Lenovo ThinkCentre                         | 4        | 1.84%   |
| Gigabyte X570                              | 4        | 1.84%   |
| MSI MS-7C84                                | 3        | 1.38%   |
| Lenovo ThinkStation                        | 3        | 1.38%   |
| Foxconn Pro                                | 3        | 1.38%   |
| Dell Precision                             | 3        | 1.38%   |
| ASUS TUF                                   | 3        | 1.38%   |
| MSI MS-7E06                                | 2        | 0.92%   |
| MSI MS-7D25                                | 2        | 0.92%   |
| HP Z400                                    | 2        | 0.92%   |
| HP Z200                                    | 2        | 0.92%   |
| HP ProDesk                                 | 2        | 0.92%   |
| HP EliteDesk                               | 2        | 0.92%   |
| Gigabyte X570S                             | 2        | 0.92%   |
| Gigabyte B85M-D3H                          | 2        | 0.92%   |
| Gigabyte B550M                             | 2        | 0.92%   |
| Gigabyte B550I                             | 2        | 0.92%   |
| Gigabyte B450M                             | 2        | 0.92%   |
| Gigabyte B365M                             | 2        | 0.92%   |
| Dell Vostro                                | 2        | 0.92%   |
| ASUS ProArt                                | 2        | 0.92%   |
| ASUS Pro                                   | 2        | 0.92%   |
| ASRock B450M                               | 2        | 0.92%   |
| ASRock B450                                | 2        | 0.92%   |
| ASRock A320M-HDV                           | 2        | 0.92%   |
| Acer Veriton                               | 2        | 0.92%   |
| UGREEN DXP4800                             | 1        | 0.46%   |
| SZMZ X99M-H2                               | 1        | 0.46%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.46%   |
| Red Hat KVM                                | 1        | 0.46%   |
| Pegatron 23-d018d                          | 1        | 0.46%   |
| Novatte M20                                | 1        | 0.46%   |
| MSI MS-7E28                                | 1        | 0.46%   |
| MSI MS-7D82                                | 1        | 0.46%   |
| MSI MS-7D43                                | 1        | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 25       | 11.52%  |
| 2018    | 20       | 9.22%   |
| 2013    | 20       | 9.22%   |
| 2021    | 18       | 8.29%   |
| 2019    | 18       | 8.29%   |
| 2022    | 16       | 7.37%   |
| 2023    | 15       | 6.91%   |
| 2017    | 13       | 5.99%   |
| 2012    | 13       | 5.99%   |
| 2014    | 10       | 4.61%   |
| 2011    | 10       | 4.61%   |
| 2010    | 10       | 4.61%   |
| 2024    | 7        | 3.23%   |
| 2016    | 7        | 3.23%   |
| 2015    | 5        | 2.3%    |
| 2025    | 3        | 1.38%   |
| 2008    | 3        | 1.38%   |
| 2007    | 2        | 0.92%   |
| 2009    | 1        | 0.46%   |
| Unknown | 1        | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 217      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 210      | 95.89%  |
| Enabled  | 9        | 4.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 217      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 49       | 21.78%  |
| 32.01-64.0      | 45       | 20%     |
| 4.01-8.0        | 35       | 15.56%  |
| 8.01-16.0       | 31       | 13.78%  |
| 64.01-256.0     | 29       | 12.89%  |
| 24.01-32.0      | 16       | 7.11%   |
| 3.01-4.0        | 13       | 5.78%   |
| More than 256.0 | 4        | 1.78%   |
| 1.01-2.0        | 2        | 0.89%   |
| 0.51-1.0        | 1        | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 59       | 24.48%  |
| 2.01-3.0   | 51       | 21.16%  |
| 3.01-4.0   | 45       | 18.67%  |
| 4.01-8.0   | 44       | 18.26%  |
| 8.01-16.0  | 20       | 8.3%    |
| 0.51-1.0   | 10       | 4.15%   |
| 16.01-24.0 | 6        | 2.49%   |
| 32.01-64.0 | 2        | 0.83%   |
| 24.01-32.0 | 2        | 0.83%   |
| 0.01-0.5   | 2        | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 83       | 36.24%  |
| 2      | 64       | 27.95%  |
| 3      | 40       | 17.47%  |
| 4      | 21       | 9.17%   |
| 5      | 13       | 5.68%   |
| 0      | 4        | 1.75%   |
| 6      | 2        | 0.87%   |
| 8      | 1        | 0.44%   |
| 7      | 1        | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 72.48%  |
| Yes       | 60       | 27.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 215      | 99.08%  |
| No        | 2        | 0.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 124      | 55.11%  |
| No        | 101      | 44.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 54.59%  |
| Yes       | 99       | 45.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 217      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 209      | 95.87%  |
| Kampong Pasir Ris | 5        | 2.29%   |
| Jurong West       | 3        | 1.38%   |
| Queenstown Estate | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 68       | 120    | 16.46%  |
| WDC                          | 55       | 105    | 13.32%  |
| Seagate                      | 50       | 63     | 12.11%  |
| Toshiba                      | 32       | 49     | 7.75%   |
| SanDisk                      | 29       | 37     | 7.02%   |
| Unknown                      | 12       | 15     | 2.91%   |
| Crucial                      | 12       | 23     | 2.91%   |
| Kingston                     | 10       | 14     | 2.42%   |
| Micron/Crucial Technology    | 9        | 13     | 2.18%   |
| Silicon Motion               | 7        | 9      | 1.69%   |
| Phison Electronics           | 7        | 12     | 1.69%   |
| Intel                        | 7        | 9      | 1.69%   |
| Hitachi                      | 7        | 8      | 1.69%   |
| Lexar                        | 6        | 7      | 1.45%   |
| Kingston Technology Company  | 6        | 6      | 1.45%   |
| China                        | 6        | 7      | 1.45%   |
| Micron Technology            | 5        | 7      | 1.21%   |
| HGST                         | 5        | 8      | 1.21%   |
| A-DATA Technology            | 5        | 5      | 1.21%   |
| Transcend                    | 4        | 6      | 0.97%   |
| Shenzhen Longsys Electronics | 4        | 6      | 0.97%   |
| SK hynix                     | 3        | 3      | 0.73%   |
| Plextor                      | 3        | 3      | 0.73%   |
| Phison                       | 3        | 3      | 0.73%   |
| MAXIO Technology (Hangzhou)  | 3        | 3      | 0.73%   |
| JMicron Technology           | 3        | 4      | 0.73%   |
| Yangtze Memory Technologies  | 2        | 2      | 0.48%   |
| Team                         | 2        | 5      | 0.48%   |
| Realtek Semiconductor        | 2        | 2      | 0.48%   |
| Maxtor                       | 2        | 2      | 0.48%   |
| KLEVV                        | 2        | 2      | 0.48%   |
| KIOXIA-EXCERIA               | 2        | 2      | 0.48%   |
| KingSpec                     | 2        | 3      | 0.48%   |
| Hewlett-Packard              | 2        | 2      | 0.48%   |
| AGI                          | 2        | 2      | 0.48%   |
| ADATA Technology             | 2        | 4      | 0.48%   |
| WALRAM                       | 1        | 1      | 0.24%   |
| Vaseky                       | 1        | 1      | 0.24%   |
| V-GEN12S                     | 1        | 1      | 0.24%   |
| USB30                        | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 10       | 2.1%    |
| Toshiba DT01ACA200 2TB                                | 8        | 1.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 8        | 1.68%   |
| Samsung SSD 850 EVO 250GB                             | 7        | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB                        | 6        | 1.26%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 5        | 1.05%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5        | 1.05%   |
| Samsung SSD 980 PRO 1TB                               | 5        | 1.05%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 4        | 0.84%   |
| Seagate ST500DM002-1BD142 500GB                       | 4        | 0.84%   |
| Seagate ST2000DM008-2FR102 2TB                        | 4        | 0.84%   |
| SanDisk NVMe SSD Drive 500GB                          | 4        | 0.84%   |
| Samsung SSD 980 500GB                                 | 4        | 0.84%   |
| Samsung SSD 860 EVO 500GB                             | 4        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 4        | 0.84%   |
| Phison PS5013 E13 NVMe Controller 500GB               | 4        | 0.84%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 3        | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 0.63%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 3        | 0.63%   |
| Toshiba HDWD320 2TB                                   | 3        | 0.63%   |
| SanDisk NVMe SSD Drive 1TB                            | 3        | 0.63%   |
| Kingston Company SNV2S1000G 1TB                       | 3        | 0.63%   |
| JMicron Generic 320GB                                 | 3        | 0.63%   |
| Crucial CT500MX500SSD1 500GB                          | 3        | 0.63%   |
| Crucial CT1000MX500SSD1 1TB                           | 3        | 0.63%   |
| A-DATA HC660 1TB SSD                                  | 3        | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 2        | 0.42%   |
| WDC WD5000AVDS-73U7B1 500GB                           | 2        | 0.42%   |
| WDC WD40EFZX-68AWUN0 4TB                              | 2        | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB                              | 2        | 0.42%   |
| Unknown NVMe SSD Drive 512GB                          | 2        | 0.42%   |
| Toshiba HDWD120 2TB                                   | 2        | 0.42%   |
| Toshiba HDWD110 1TB                                   | 2        | 0.42%   |
| Toshiba DT01ACA050 500GB                              | 2        | 0.42%   |
| SK hynix SC311 SATA 128GB SSD                         | 2        | 0.42%   |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.42%   |
| Seagate Expansion HDD 4TB                             | 2        | 0.42%   |
| Seagate BUP Portable 5TB                              | 2        | 0.42%   |
| Sandisk WD_BLACK SN850X 1000GB                        | 2        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 61     | 32.45%  |
| WDC                 | 46       | 94     | 30.46%  |
| Toshiba             | 30       | 46     | 19.87%  |
| Hitachi             | 7        | 8      | 4.64%   |
| Samsung Electronics | 5        | 6      | 3.31%   |
| HGST                | 5        | 8      | 3.31%   |
| JMicron Technology  | 3        | 4      | 1.99%   |
| Maxtor              | 2        | 2      | 1.32%   |
| Unknown             | 1        | 1      | 0.66%   |
| SSK                 | 1        | 1      | 0.66%   |
| MARVELL             | 1        | 1      | 0.66%   |
| ExcelStor           | 1        | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 46     | 27.64%  |
| SanDisk             | 12       | 13     | 9.76%   |
| Crucial             | 9        | 20     | 7.32%   |
| Kingston            | 7        | 9      | 5.69%   |
| China               | 6        | 7      | 4.88%   |
| WDC                 | 5        | 5      | 4.07%   |
| Transcend           | 3        | 5      | 2.44%   |
| SK hynix            | 3        | 3      | 2.44%   |
| Plextor             | 3        | 3      | 2.44%   |
| Intel               | 3        | 3      | 2.44%   |
| A-DATA Technology   | 3        | 3      | 2.44%   |
| Team                | 2        | 5      | 1.63%   |
| Lexar               | 2        | 2      | 1.63%   |
| KingSpec            | 2        | 3      | 1.63%   |
| Hewlett-Packard     | 2        | 2      | 1.63%   |
| WALRAM              | 1        | 1      | 0.81%   |
| Vaseky              | 1        | 1      | 0.81%   |
| V-GEN12S            | 1        | 1      | 0.81%   |
| USB30               | 1        | 1      | 0.81%   |
| Unknown             | 1        | 1      | 0.81%   |
| TREK 256            | 1        | 1      | 0.81%   |
| tigo                | 1        | 1      | 0.81%   |
| Teclast             | 1        | 1      | 0.81%   |
| TAMMUZ              | 1        | 1      | 0.81%   |
| SABRENT             | 1        | 2      | 0.81%   |
| Pioneer             | 1        | 1      | 0.81%   |
| OCZ                 | 1        | 1      | 0.81%   |
| Micron Technology   | 1        | 1      | 0.81%   |
| LITEONIT            | 1        | 1      | 0.81%   |
| Lenovo              | 1        | 1      | 0.81%   |
| KLEVV               | 1        | 1      | 0.81%   |
| Kingmax             | 1        | 1      | 0.81%   |
| KINGBANK            | 1        | 1      | 0.81%   |
| Indilinx            | 1        | 1      | 0.81%   |
| Gigabyte Technology | 1        | 1      | 0.81%   |
| GAMER               | 1        | 1      | 0.81%   |
| GALAX               | 1        | 1      | 0.81%   |
| Fanxiang            | 1        | 1      | 0.81%   |
| BIWIN               | 1        | 1      | 0.81%   |
| Apacer              | 1        | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 117      | 233    | 35.03%  |
| NVMe    | 106      | 201    | 31.74%  |
| SSD     | 100      | 157    | 29.94%  |
| Unknown | 6        | 9      | 1.8%    |
| MMC     | 5        | 5      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 165      | 372    | 55.37%  |
| NVMe | 106      | 200    | 35.57%  |
| SAS  | 22       | 28     | 7.38%   |
| MMC  | 5        | 5      | 1.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 103      | 154    | 42.39%  |
| 0.51-1.0   | 72       | 113    | 29.63%  |
| 1.01-2.0   | 37       | 58     | 15.23%  |
| 3.01-4.0   | 14       | 22     | 5.76%   |
| 4.01-10.0  | 11       | 35     | 4.53%   |
| 2.01-3.0   | 5        | 5      | 2.06%   |
| 10.01-20.0 | 1        | 3      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 46       | 20.09%  |
| 101-250        | 36       | 15.72%  |
| More than 3000 | 30       | 13.1%   |
| 1001-2000      | 28       | 12.23%  |
| 251-500        | 25       | 10.92%  |
| 1-20           | 23       | 10.04%  |
| 2001-3000      | 16       | 6.99%   |
| Unknown        | 16       | 6.99%   |
| 51-100         | 6        | 2.62%   |
| 21-50          | 3        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 66       | 27.85%  |
| 21-50          | 38       | 16.03%  |
| 101-250        | 30       | 12.66%  |
| 251-500        | 22       | 9.28%   |
| 51-100         | 19       | 8.02%   |
| 1001-2000      | 18       | 7.59%   |
| Unknown        | 16       | 6.75%   |
| 501-1000       | 15       | 6.33%   |
| More than 3000 | 10       | 4.22%   |
| 2001-3000      | 3        | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB         | 5        | 9      | 16.67%  |
| WDC WD5000AVDS-73U7B1 500GB         | 2        | 2      | 6.67%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1        | 1      | 3.33%   |
| WDC WD5000AAKS-22V1A0 500GB         | 1        | 1      | 3.33%   |
| WDC WD50 EZRX-00MVLB1 5TB           | 1        | 1      | 3.33%   |
| WDC WD3200AAJS-65M0A0 320GB         | 1        | 1      | 3.33%   |
| WDC WD1600AAJS-65WAA0 160GB         | 1        | 1      | 3.33%   |
| WDC WD10EZEX-60M2NA0 1TB            | 1        | 1      | 3.33%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 3.33%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 1      | 3.33%   |
| Toshiba DT01ACA050 500GB            | 1        | 1      | 3.33%   |
| Teclast 480GB A800 SSD              | 1        | 1      | 3.33%   |
| Seagate ST9160821AS 160GB           | 1        | 1      | 3.33%   |
| Seagate ST8000NM0055-1RM112 8TB     | 1        | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.33%   |
| Seagate ST3160811AS 160GB           | 1        | 1      | 3.33%   |
| Seagate ST31500341AS 1TB            | 1        | 1      | 3.33%   |
| Seagate ST2000LM007-1R8174 2TB      | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 980 PRO 1TB | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 970 PRO 1TB | 1        | 1      | 3.33%   |
| Samsung Electronics HD103UJ 1TB     | 1        | 1      | 3.33%   |
| Hitachi HDS721010CLA632 1TB         | 1        | 1      | 3.33%   |
| HGST HTS545050A7E380 500GB          | 1        | 1      | 3.33%   |
| ExcelStor Technology J360 64GB      | 1        | 1      | 3.33%   |
| Crucial CT120M500SSD1 120GB         | 1        | 10     | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 19     | 46.15%  |
| Seagate             | 5        | 6      | 19.23%  |
| Samsung Electronics | 3        | 3      | 11.54%  |
| Toshiba             | 1        | 1      | 3.85%   |
| Teclast             | 1        | 1      | 3.85%   |
| Hitachi             | 1        | 1      | 3.85%   |
| HGST                | 1        | 1      | 3.85%   |
| ExcelStor           | 1        | 1      | 3.85%   |
| Crucial             | 1        | 10     | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 19     | 54.55%  |
| Seagate             | 5        | 6      | 22.73%  |
| Toshiba             | 1        | 1      | 4.55%   |
| Samsung Electronics | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| HGST                | 1        | 1      | 4.55%   |
| ExcelStor           | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 30     | 82.61%  |
| NVMe | 2        | 2      | 8.7%    |
| SSD  | 2        | 11     | 8.7%    |

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
| Detected | 118      | 283    | 47.01%  |
| Works    | 109      | 278    | 43.43%  |
| Malfunc  | 23       | 43     | 9.16%   |
| Failed   | 1        | 1      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 134      | 36.22%  |
| AMD                          | 73       | 19.73%  |
| Samsung Electronics          | 42       | 11.35%  |
| SanDisk                      | 23       | 6.22%   |
| ASMedia Technology           | 13       | 3.51%   |
| Micron/Crucial Technology    | 11       | 2.97%   |
| Phison Electronics           | 10       | 2.7%    |
| Silicon Motion               | 9        | 2.43%   |
| Shenzhen Longsys Electronics | 9        | 2.43%   |
| Kingston Technology Company  | 8        | 2.16%   |
| Realtek Semiconductor        | 5        | 1.35%   |
| Micron Technology            | 5        | 1.35%   |
| MAXIO Technology (Hangzhou)  | 4        | 1.08%   |
| Toshiba America Info Systems | 3        | 0.81%   |
| Marvell Technology Group     | 3        | 0.81%   |
| Yangtze Memory Technologies  | 2        | 0.54%   |
| KIOXIA                       | 2        | 0.54%   |
| JMicron Technology           | 2        | 0.54%   |
| Broadcom / LSI               | 2        | 0.54%   |
| ADATA Technology             | 2        | 0.54%   |
| Adaptec                      | 2        | 0.54%   |
| VIA Technologies             | 1        | 0.27%   |
| Transcend                    | 1        | 0.27%   |
| Seagate Technology           | 1        | 0.27%   |
| Red Hat                      | 1        | 0.27%   |
| INNOGRIT                     | 1        | 0.27%   |
| Hosin Global Electronics     | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36       | 8.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20       | 4.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 4.03%   |
| Intel SATA Controller [RAID mode]                                                       | 14       | 3.32%   |
| AMD 600 Series Chipset SATA Controller                                                  | 13       | 3.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 2.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 11       | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 2.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 2.37%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 2.37%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 8        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 1.66%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 6        | 1.42%   |
| Shenzhen Longsys Lexar NM790 / Patriot Viper VP4300 Lite NVMe SSD (DRAM-less)           | 5        | 1.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.18%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5        | 1.18%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.95%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 4        | 0.95%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 0.95%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 4        | 0.95%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4        | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 0.95%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.95%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 0.95%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 4        | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.71%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                        | 3        | 0.71%   |
| Intel RST Volume Management Device Controller                                           | 3        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.71%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 3        | 0.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 184      | 54.6%   |
| NVMe | 106      | 31.45%  |
| RAID | 22       | 6.53%   |
| IDE  | 19       | 5.64%   |
| SAS  | 5        | 1.48%   |
| SCSI | 1        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 141      | 64.98%  |
| AMD     | 75       | 34.56%  |
| Unknown | 1        | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 7        | 3.21%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 5        | 2.29%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 5        | 2.29%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 4        | 1.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 4        | 1.83%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 1.83%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 1.83%   |
| Intel Core i9-14900K                           | 3        | 1.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 1.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 3        | 1.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.38%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz            | 2        | 0.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 0.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 0.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 2        | 0.92%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 2        | 0.92%   |
| Intel Core i5-7600 CPU @ 3.50GHz               | 2        | 0.92%   |
| Intel Core i5-4690 CPU @ 3.50GHz               | 2        | 0.92%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 0.92%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 0.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 0.92%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 0.92%   |
| Intel Core i3 CPU 560 @ 3.33GHz                | 2        | 0.92%   |
| Intel Celeron CPU J1800 @ 2.41GHz              | 2        | 0.92%   |
| Intel 12th Gen Core i7-12700                   | 2        | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2        | 0.92%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 2        | 0.92%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 2        | 0.92%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 2        | 0.92%   |
| AMD Ryzen 7 7800X3D 8-Core Processor           | 2        | 0.92%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 2        | 0.92%   |
| AMD Ryzen 5 7600X 6-Core Processor             | 2        | 0.92%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 0.92%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 0.92%   |
| AMD Ryzen 5 3500X 6-Core Processor             | 2        | 0.92%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 0.92%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 2        | 0.92%   |
| Intel Xeon w9-3495X                            | 1        | 0.46%   |
| Intel Xeon W-2155 CPU @ 3.30GHz                | 1        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 47       | 21.56%  |
| AMD Ryzen 5            | 31       | 14.22%  |
| Other                  | 22       | 10.09%  |
| Intel Xeon             | 20       | 9.17%   |
| Intel Core i7          | 19       | 8.72%   |
| AMD Ryzen 7            | 16       | 7.34%   |
| AMD Ryzen 9            | 11       | 5.05%   |
| Intel Core i3          | 10       | 4.59%   |
| Intel Core i9          | 6        | 2.75%   |
| Intel Celeron          | 6        | 2.75%   |
| AMD Ryzen Threadripper | 4        | 1.83%   |
| Intel Core 2 Quad      | 3        | 1.38%   |
| Intel Pentium Gold     | 2        | 0.92%   |
| Intel Pentium          | 2        | 0.92%   |
| Intel Atom             | 2        | 0.92%   |
| AMD Ryzen 3            | 2        | 0.92%   |
| AMD FX                 | 2        | 0.92%   |
| AMD Athlon             | 2        | 0.92%   |
| AMD A10                | 2        | 0.92%   |
| Intel Pentium Silver   | 1        | 0.46%   |
| Intel Pentium Dual     | 1        | 0.46%   |
| Intel Pentium 4        | 1        | 0.46%   |
| Intel Core m3          | 1        | 0.46%   |
| AMD Ryzen 5 PRO        | 1        | 0.46%   |
| AMD PRO A10            | 1        | 0.46%   |
| AMD Phenom II X6       | 1        | 0.46%   |
| AMD Phenom II X4       | 1        | 0.46%   |
| AMD Opteron            | 1        | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 77       | 35.32%  |
| 6      | 45       | 20.64%  |
| 2      | 26       | 11.93%  |
| 8      | 23       | 10.55%  |
| 12     | 13       | 5.96%   |
| 16     | 8        | 3.67%   |
| 10     | 8        | 3.67%   |
| 24     | 4        | 1.83%   |
| 14     | 4        | 1.83%   |
| 32     | 2        | 0.92%   |
| 1      | 2        | 0.92%   |
| 56     | 1        | 0.46%   |
| 44     | 1        | 0.46%   |
| 22     | 1        | 0.46%   |
| 20     | 1        | 0.46%   |
| 5      | 1        | 0.46%   |
| 3      | 1        | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 213      | 98.16%  |
| 2      | 4        | 1.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 141      | 64.68%  |
| 1      | 77       | 35.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 216      | 99.54%  |
| Unknown        | 1        | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 109      | 47.6%   |
| 0x306c3    | 12       | 5.24%   |
| 0x306a9    | 9        | 3.93%   |
| 0x906ea    | 8        | 3.49%   |
| 0x506e3    | 7        | 3.06%   |
| 0x08701021 | 6        | 2.62%   |
| 0x206a7    | 5        | 2.18%   |
| 0x90672    | 4        | 1.75%   |
| 0x306e4    | 4        | 1.75%   |
| 0x20655    | 4        | 1.75%   |
| 0x50654    | 3        | 1.31%   |
| 0x0a601203 | 3        | 1.31%   |
| 0x0a20120a | 3        | 1.31%   |
| 0x0a201016 | 3        | 1.31%   |
| 0x08701013 | 3        | 1.31%   |
| 0x06003106 | 3        | 1.31%   |
| 0x906e9    | 2        | 0.87%   |
| 0x906c0    | 2        | 0.87%   |
| 0x406f1    | 2        | 0.87%   |
| 0x0a601206 | 2        | 0.87%   |
| 0x0a50000d | 2        | 0.87%   |
| 0x0a201009 | 2        | 0.87%   |
| 0x06000852 | 2        | 0.87%   |
| 0xf41      | 1        | 0.44%   |
| 0xb06e0    | 1        | 0.44%   |
| 0xb0671    | 1        | 0.44%   |
| 0xa0671    | 1        | 0.44%   |
| 0xa0655    | 1        | 0.44%   |
| 0x906a4    | 1        | 0.44%   |
| 0x706a1    | 1        | 0.44%   |
| 0x6fd      | 1        | 0.44%   |
| 0x6fb      | 1        | 0.44%   |
| 0x1067a    | 1        | 0.44%   |
| 0x0a601201 | 1        | 0.44%   |
| 0x0a50000f | 1        | 0.44%   |
| 0x0a50000c | 1        | 0.44%   |
| 0x0a404102 | 1        | 0.44%   |
| 0x08600106 | 1        | 0.44%   |
| 0x0830107a | 1        | 0.44%   |
| 0x0830104d | 1        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 26       | 11.87%  |
| Zen 3            | 22       | 10.05%  |
| Haswell          | 22       | 10.05%  |
| IvyBridge        | 21       | 9.59%   |
| Zen 2            | 19       | 8.68%   |
| KabyLake         | 18       | 8.22%   |
| Alderlake Hybrid | 13       | 5.94%   |
| Skylake          | 11       | 5.02%   |
| SandyBridge      | 9        | 4.11%   |
| Westmere         | 7        | 3.2%    |
| Zen+             | 6        | 2.74%   |
| Zen              | 5        | 2.28%   |
| CometLake        | 5        | 2.28%   |
| Silvermont       | 4        | 1.83%   |
| Broadwell        | 4        | 1.83%   |
| Steamroller      | 3        | 1.37%   |
| K10              | 3        | 1.37%   |
| Tremont          | 2        | 0.91%   |
| TigerLake        | 2        | 0.91%   |
| Piledriver       | 2        | 0.91%   |
| Penryn           | 2        | 0.91%   |
| Nehalem          | 2        | 0.91%   |
| Gracemont        | 2        | 0.91%   |
| Goldmont         | 2        | 0.91%   |
| Core             | 2        | 0.91%   |
| Sapphire Rapids  | 1        | 0.46%   |
| NetBurst         | 1        | 0.46%   |
| Icelake          | 1        | 0.46%   |
| Goldmont plus    | 1        | 0.46%   |
| Excavator        | 1        | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 96       | 37.5%   |
| Intel             | 87       | 33.98%  |
| AMD               | 71       | 27.73%  |
| Red Hat           | 1        | 0.39%   |
| ASPEED Technology | 1        | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 3.75%   |
| AMD Raphael                                                                 | 9        | 3.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 3%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.62%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 6        | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.25%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 2.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 1.87%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 5        | 1.87%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 5        | 1.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.5%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.5%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.5%    |
| Nvidia G96CGL [Quadro FX 580]                                               | 4        | 1.5%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.5%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.12%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 1.12%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 3        | 1.12%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 1.12%   |
| Intel JasperLake [UHD Graphics]                                             | 3        | 1.12%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.12%   |
| Intel Battlemage G21 [Arc B580]                                             | 3        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.12%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.12%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 3        | 1.12%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.12%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.12%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 3        | 1.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.75%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.75%   |
| Nvidia GF119 [GeForce 605]                                                  | 2        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 74       | 32.46%  |
| 1 x Intel            | 66       | 28.95%  |
| 1 x AMD              | 52       | 22.81%  |
| Intel + Nvidia       | 8        | 3.51%   |
| AMD + Nvidia         | 8        | 3.51%   |
| 2 x Nvidia           | 5        | 2.19%   |
| 2 x AMD              | 5        | 2.19%   |
| Intel + AMD          | 5        | 2.19%   |
| Other                | 2        | 0.88%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.44%   |
| 1 x Red Hat          | 1        | 0.44%   |
| Nvidia + ASPEED      | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 147      | 65.33%  |
| Proprietary | 59       | 26.22%  |
| Unknown     | 19       | 8.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 114      | 49.78%  |
| 1.01-2.0   | 22       | 9.61%   |
| 7.01-8.0   | 21       | 9.17%   |
| 8.01-16.0  | 21       | 9.17%   |
| 3.01-4.0   | 16       | 6.99%   |
| 0.01-0.5   | 14       | 6.11%   |
| 0.51-1.0   | 12       | 5.24%   |
| 5.01-6.0   | 6        | 2.62%   |
| 16.01-24.0 | 3        | 1.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 53       | 24.31%  |
| Samsung Electronics  | 23       | 10.55%  |
| Acer                 | 15       | 6.88%   |
| Philips              | 13       | 5.96%   |
| Hewlett-Packard      | 13       | 5.96%   |
| Goldstar             | 12       | 5.5%    |
| AOC                  | 9        | 4.13%   |
| Denver               | 7        | 3.21%   |
| ViewSonic            | 5        | 2.29%   |
| Lenovo               | 5        | 2.29%   |
| PRISM+               | 4        | 1.83%   |
| Pixio                | 4        | 1.83%   |
| Mi                   | 4        | 1.83%   |
| Ancor Communications | 4        | 1.83%   |
| MSI                  | 3        | 1.38%   |
| LG Electronics       | 3        | 1.38%   |
| AU Optronics         | 3        | 1.38%   |
| ASUSTek Computer     | 3        | 1.38%   |
| Unknown              | 3        | 1.38%   |
| Unknown (XXX)        | 2        | 0.92%   |
| Toshiba              | 2        | 0.92%   |
| Sharp                | 2        | 0.92%   |
| Lenovo Group Limited | 2        | 0.92%   |
| BenQ                 | 2        | 0.92%   |
| YMK                  | 1        | 0.46%   |
| Xiaomi               | 1        | 0.46%   |
| Wacom                | 1        | 0.46%   |
| Sony                 | 1        | 0.46%   |
| SGT                  | 1        | 0.46%   |
| SAC                  | 1        | 0.46%   |
| RTK                  | 1        | 0.46%   |
| RHT                  | 1        | 0.46%   |
| IPS                  | 1        | 0.46%   |
| InnoView             | 1        | 0.46%   |
| IDV                  | 1        | 0.46%   |
| HPN                  | 1        | 0.46%   |
| HPD                  | 1        | 0.46%   |
| HKC                  | 1        | 0.46%   |
| GLE                  | 1        | 0.46%   |
| Fujitsu Siemens      | 1        | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch               | 4        | 1.74%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 4        | 1.74%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                    | 4        | 1.74%   |
| Pixio SFP2702G FHD WAM2700 1920x1080 597x336mm 27.0-inch            | 3        | 1.3%    |
| Denver MO-HHS-32C LHCFFFF 1920x1080 699x393mm 31.6-inch             | 3        | 1.3%    |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                 | 3        | 1.3%    |
| Dell D2015H DELF063 1920x1080 435x239mm 19.5-inch                   | 3        | 1.3%    |
| Acer EB321HQU C ACR0507 2560x1440 699x393mm 31.6-inch               | 3        | 1.3%    |
| Unknown                                                             | 3        | 1.3%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch   | 2        | 0.87%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 521x293mm 23.5-inch | 2        | 0.87%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch   | 2        | 0.87%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch             | 2        | 0.87%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch          | 2        | 0.87%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                 | 2        | 0.87%   |
| Denver VN24F165 LHC0236 1920x1080 598x336mm 27.0-inch               | 2        | 0.87%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                  | 2        | 0.87%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                 | 2        | 0.87%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                   | 2        | 0.87%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                   | 2        | 0.87%   |
| Dell LCD Monitor P2217H 1920x1080                                   | 2        | 0.87%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                  | 2        | 0.87%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                   | 2        | 0.87%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                    | 2        | 0.87%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                    | 2        | 0.87%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                    | 2        | 0.87%   |
| YMK EM160 TOUCH YMK4A68 2880x1800 342x220mm 16.0-inch               | 1        | 0.43%   |
| Xiaomi Mi TV XMD004A 3840x2160 708x398mm 32.0-inch                  | 1        | 0.43%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch            | 1        | 0.43%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch          | 1        | 0.43%   |
| ViewSonic VX2705-2KP VSC3B3A 2560x1440 597x336mm 27.0-inch          | 1        | 0.43%   |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 527x296mm 23.8-inch           | 1        | 0.43%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                           | 1        | 0.43%   |
| ViewSonic LCD Monitor VA2261 Series 3840x1080                       | 1        | 0.43%   |
| ViewSonic LCD Monitor VA2210-FHD                                    | 1        | 0.43%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch       | 1        | 0.43%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch      | 1        | 0.43%   |
| Toshiba TV TSB0110 1920x1080 890x500mm 40.2-inch                    | 1        | 0.43%   |
| Toshiba T749-fHD720 TSB8801 1920x1080 708x398mm 32.0-inch           | 1        | 0.43%   |
| Sony TV SNY2C02 1920x1080 886x498mm 40.0-inch                       | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 111      | 51.39%  |
| 2560x1440 (QHD)    | 36       | 16.67%  |
| 3840x2160 (4K)     | 32       | 14.81%  |
| 1600x900 (HD+)     | 14       | 6.48%   |
| 3440x1440          | 3        | 1.39%   |
| 1360x768           | 3        | 1.39%   |
| 3840x1080          | 2        | 0.93%   |
| 2560x1080          | 2        | 0.93%   |
| 1680x1050 (WSXGA+) | 2        | 0.93%   |
| 1366x768 (WXGA)    | 2        | 0.93%   |
| 1280x1024 (SXGA)   | 2        | 0.93%   |
| Unknown            | 2        | 0.93%   |
| 7680x2160          | 1        | 0.46%   |
| 2880x1800          | 1        | 0.46%   |
| 2560x1600          | 1        | 0.46%   |
| 2560x1397          | 1        | 0.46%   |
| 1440x900 (WXGA+)   | 1        | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 39       | 18.06%  |
| 23      | 31       | 14.35%  |
| 24      | 30       | 13.89%  |
| Unknown | 23       | 10.65%  |
| 21      | 19       | 8.8%    |
| 31      | 13       | 6.02%   |
| 20      | 10       | 4.63%   |
| 19      | 8        | 3.7%    |
| 49      | 4        | 1.85%   |
| 32      | 4        | 1.85%   |
| 28      | 4        | 1.85%   |
| 18      | 4        | 1.85%   |
| 54      | 3        | 1.39%   |
| 84      | 2        | 0.93%   |
| 40      | 2        | 0.93%   |
| 34      | 2        | 0.93%   |
| 16      | 2        | 0.93%   |
| 15      | 2        | 0.93%   |
| 72      | 1        | 0.46%   |
| 65      | 1        | 0.46%   |
| 63      | 1        | 0.46%   |
| 57      | 1        | 0.46%   |
| 55      | 1        | 0.46%   |
| 50      | 1        | 0.46%   |
| 39      | 1        | 0.46%   |
| 33      | 1        | 0.46%   |
| 29      | 1        | 0.46%   |
| 25      | 1        | 0.46%   |
| 22      | 1        | 0.46%   |
| 17      | 1        | 0.46%   |
| 14      | 1        | 0.46%   |
| 13      | 1        | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 96       | 45.07%  |
| 401-500     | 40       | 18.78%  |
| Unknown     | 23       | 10.8%   |
| 601-700     | 20       | 9.39%   |
| 1001-1500   | 12       | 5.63%   |
| 701-800     | 7        | 3.29%   |
| 301-350     | 5        | 2.35%   |
| 801-900     | 3        | 1.41%   |
| 351-400     | 3        | 1.41%   |
| 1501-2000   | 3        | 1.41%   |
| 201-300     | 1        | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 165      | 81.28%  |
| Unknown | 21       | 10.34%  |
| 16/10   | 6        | 2.96%   |
| 32/9    | 4        | 1.97%   |
| 21/9    | 4        | 1.97%   |
| 5/4     | 2        | 0.99%   |
| 6/5     | 1        | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 65       | 30.52%  |
| 301-350        | 39       | 18.31%  |
| 351-500        | 24       | 11.27%  |
| 151-200        | 24       | 11.27%  |
| Unknown        | 23       | 10.8%   |
| More than 1000 | 11       | 5.16%   |
| 251-300        | 10       | 4.69%   |
| 501-1000       | 7        | 3.29%   |
| 141-150        | 4        | 1.88%   |
| 101-110        | 3        | 1.41%   |
| 81-90          | 1        | 0.47%   |
| 71-80          | 1        | 0.47%   |
| 111-120        | 1        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 113      | 52.31%  |
| 101-120 | 45       | 20.83%  |
| Unknown | 23       | 10.65%  |
| 121-160 | 15       | 6.94%   |
| 161-240 | 12       | 5.56%   |
| 1-50    | 8        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 182      | 80.89%  |
| 2     | 21       | 9.33%   |
| 0     | 20       | 8.89%   |
| 3     | 2        | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 131      | 39.58%  |
| Intel                     | 120      | 36.25%  |
| Qualcomm Atheros          | 15       | 4.53%   |
| MediaTek                  | 14       | 4.23%   |
| Aquantia                  | 9        | 2.72%   |
| TP-Link                   | 8        | 2.42%   |
| Broadcom                  | 8        | 2.42%   |
| Ralink Technology         | 5        | 1.51%   |
| Samsung Electronics       | 3        | 0.91%   |
| ASUSTek Computer          | 3        | 0.91%   |
| ASIX Electronics          | 2        | 0.6%    |
| Xilinx                    | 1        | 0.3%    |
| Solarflare Communications | 1        | 0.3%    |
| Qualcomm                  | 1        | 0.3%    |
| Microsoft                 | 1        | 0.3%    |
| Microchip Technology      | 1        | 0.3%    |
| Mellanox Technologies     | 1        | 0.3%    |
| Linux Foundation          | 1        | 0.3%    |
| Linksys                   | 1        | 0.3%    |
| Hewlett-Packard           | 1        | 0.3%    |
| Fargo                     | 1        | 0.3%    |
| Exar                      | 1        | 0.3%    |
| Edimax Technology         | 1        | 0.3%    |
| aicsemi                   | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 95       | 24.23%  |
| Realtek RTL8125 2.5GbE Controller                                              | 24       | 6.12%   |
| Intel Wi-Fi 6 AX200                                                            | 20       | 5.1%    |
| Intel Ethernet Controller I225-V                                               | 19       | 4.85%   |
| Intel I211 Gigabit Network Connection                                          | 14       | 3.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 12       | 3.06%   |
| Intel Ethernet Controller I226-V                                               | 8        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                                           | 8        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8        | 2.04%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 7        | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 5        | 1.28%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 5        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4        | 1.02%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 4        | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 0.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 0.77%   |
| Realtek 802.11ac NIC                                                           | 3        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3        | 0.77%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]           | 3        | 0.77%   |
| Intel Wireless 8260                                                            | 3        | 0.77%   |
| Intel Wireless 7260                                                            | 3        | 0.77%   |
| Intel Wireless 3165                                                            | 3        | 0.77%   |
| Intel Ethernet Connection I217-V                                               | 3        | 0.77%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 0.77%   |
| Intel 700 Series Chipset CNVi WiFi                                             | 3        | 0.77%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 3        | 0.77%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                | 3        | 0.77%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                     | 2        | 0.51%   |
| TP-Link Archer T4U ver.3                                                       | 2        | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 0.51%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter                       | 2        | 0.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 2        | 0.51%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                | 2        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 63       | 49.61%  |
| Realtek Semiconductor | 17       | 13.39%  |
| MediaTek              | 14       | 11.02%  |
| Qualcomm Atheros      | 10       | 7.87%   |
| TP-Link               | 8        | 6.3%    |
| Ralink Technology     | 5        | 3.94%   |
| Broadcom              | 4        | 3.15%   |
| ASUSTek Computer      | 3        | 2.36%   |
| Microsoft             | 1        | 0.79%   |
| Linksys               | 1        | 0.79%   |
| Edimax Technology     | 1        | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 20       | 15.5%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 12       | 9.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 6        | 4.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 5        | 3.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5        | 3.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 3.1%    |
| Ralink MT7601U Wireless Adapter                                      | 4        | 3.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4        | 3.1%    |
| Realtek 802.11ac NIC                                                 | 3        | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 3        | 2.33%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 3        | 2.33%   |
| Intel Wireless 8260                                                  | 3        | 2.33%   |
| Intel Wireless 7260                                                  | 3        | 2.33%   |
| Intel Wireless 3165                                                  | 3        | 2.33%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 3        | 2.33%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 3        | 2.33%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]      | 3        | 2.33%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                           | 2        | 1.55%   |
| TP-Link Archer T4U ver.3                                             | 2        | 1.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 2        | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2        | 1.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 1.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 0.78%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 0.78%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter             | 1        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1        | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.78%   |
| Realtek 802.11be WLAN Adapter                                        | 1        | 0.78%   |
| Realtek 802.11ax WLAN Adapter                                        | 1        | 0.78%   |
| Realtek 802.11ac WLAN Adapter                                        | 1        | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 0.78%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter      | 1        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 0.78%   |
| Microsoft Wireless XBox Controller Dongle                            | 1        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 124      | 51.67%  |
| Intel                     | 87       | 36.25%  |
| Aquantia                  | 9        | 3.75%   |
| Qualcomm Atheros          | 6        | 2.5%    |
| Broadcom                  | 4        | 1.67%   |
| Samsung Electronics       | 3        | 1.25%   |
| ASIX Electronics          | 2        | 0.83%   |
| Xilinx                    | 1        | 0.42%   |
| Solarflare Communications | 1        | 0.42%   |
| Qualcomm                  | 1        | 0.42%   |
| Mellanox Technologies     | 1        | 0.42%   |
| Hewlett-Packard           | 1        | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 95       | 36.82%  |
| Realtek RTL8125 2.5GbE Controller                                               | 24       | 9.3%    |
| Intel Ethernet Controller I225-V                                                | 19       | 7.36%   |
| Intel I211 Gigabit Network Connection                                           | 14       | 5.43%   |
| Intel Ethernet Controller I226-V                                                | 8        | 3.1%    |
| Intel Ethernet Connection (2) I219-V                                            | 8        | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 8        | 3.1%    |
| Intel Ethernet Connection I217-LM                                               | 5        | 1.94%   |
| Intel Ethernet Connection (2) I219-LM                                           | 4        | 1.55%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 4        | 1.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 3        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 3        | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 3        | 1.16%   |
| Intel Ethernet Connection I217-V                                                | 3        | 1.16%   |
| Intel 82578DM Gigabit Network Connection                                        | 3        | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 2        | 0.78%   |
| Intel I350 Gigabit Network Connection                                           | 2        | 0.78%   |
| Intel I210 Gigabit Network Connection                                           | 2        | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                                           | 2        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                            | 2        | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                                           | 2        | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                               | 2        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 2        | 0.78%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 2        | 0.78%   |
| Xilinx Ethernet controller                                                      | 1        | 0.39%   |
| Solarflare XtremeScale SFC9250 10/25/40/50/100G Ethernet Controller             | 1        | 0.39%   |
| Realtek USB 10/100/1G/2.5 LAN                                                   | 1        | 0.39%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter                        | 1        | 0.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 1        | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                 | 1        | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 1        | 0.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                      | 1        | 0.39%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                                 | 1        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 1        | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 1        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 1        | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 1        | 0.39%   |
| Mellanox MT42822 BlueField-2 integrated ConnectX-6 Dx network controller        | 1        | 0.39%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                                         | 1        | 0.39%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                    | 1        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 215      | 62.68%  |
| WiFi     | 123      | 35.86%  |
| Modem    | 3        | 0.87%   |
| Unknown  | 2        | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 161      | 70.61%  |
| WiFi     | 66       | 28.95%  |
| Unknown  | 1        | 0.44%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 105      | 47.51%  |
| 1     | 94       | 42.53%  |
| 3     | 12       | 5.43%   |
| 4     | 3        | 1.36%   |
| 0     | 3        | 1.36%   |
| 9     | 1        | 0.45%   |
| 8     | 1        | 0.45%   |
| 6     | 1        | 0.45%   |
| 5     | 1        | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 198      | 90.83%  |
| Yes  | 20       | 9.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 55       | 50.93%  |
| Cambridge Silicon Radio         | 14       | 12.96%  |
| MediaTek                        | 7        | 6.48%   |
| Realtek Semiconductor           | 6        | 5.56%   |
| TP-Link                         | 5        | 4.63%   |
| IMC Networks                    | 5        | 4.63%   |
| Foxconn / Hon Hai               | 5        | 4.63%   |
| Qualcomm Atheros Communications | 4        | 3.7%    |
| Unknown                         | 3        | 2.78%   |
| Broadcom                        | 2        | 1.85%   |
| SINO WEALTH                     | 1        | 0.93%   |
| ASUSTek Computer                | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 16       | 14.81%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 12.96%  |
| Intel AX210 Bluetooth                               | 11       | 10.19%  |
| Intel Bluetooth wireless interface                  | 10       | 9.26%   |
| MediaTek Wireless_Device                            | 7        | 6.48%   |
| Intel AX201 Bluetooth                               | 6        | 5.56%   |
| TP-Link TP-T@- UB500 Adapter                        | 5        | 4.63%   |
| Intel Bluetooth Device                              | 5        | 4.63%   |
| Realtek Bluetooth Radio                             | 4        | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 2.78%   |
| IMC Networks Bluetooth Radio                        | 3        | 2.78%   |
| Foxconn / Hon Hai Wireless_Device                   | 3        | 2.78%   |
| Unknown                                             | 3        | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 1.85%   |
| IMC Networks Wireless_Device                        | 2        | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 1.85%   |
| SINO WEALTH Bluetooth Keyboard                      | 1        | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 0.93%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1        | 0.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 0.93%   |
| ASUS ASUS USB-BT500                                 | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 136      | 37.16%  |
| Nvidia                                       | 89       | 24.32%  |
| AMD                                          | 86       | 23.5%   |
| C-Media Electronics                          | 5        | 1.37%   |
| ASUSTek Computer                             | 5        | 1.37%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.82%   |
| Tenx Technology                              | 3        | 0.82%   |
| Giga-Byte Technology                         | 3        | 0.82%   |
| Creative Labs                                | 3        | 0.82%   |
| TTGK Technology                              | 2        | 0.55%   |
| SteelSeries ApS                              | 2        | 0.55%   |
| Sony                                         | 2        | 0.55%   |
| Micro Star International                     | 2        | 0.55%   |
| Logitech                                     | 2        | 0.55%   |
| Hewlett-Packard                              | 2        | 0.55%   |
| Creative Technology                          | 2        | 0.55%   |
| XMOS                                         | 1        | 0.27%   |
| Xiaomi                                       | 1        | 0.27%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.27%   |
| Texas Instruments                            | 1        | 0.27%   |
| Setek Elektronik                             | 1        | 0.27%   |
| SAVITECH                                     | 1        | 0.27%   |
| Samsung Electronics                          | 1        | 0.27%   |
| Samson Technologies                          | 1        | 0.27%   |
| RODE Microphones                             | 1        | 0.27%   |
| Realtek Semiconductor                        | 1        | 0.27%   |
| MV                                           | 1        | 0.27%   |
| liyuany                                      | 1        | 0.27%   |
| JMTek                                        | 1        | 0.27%   |
| Jieli Technology                             | 1        | 0.27%   |
| Huawei Technologies                          | 1        | 0.27%   |
| Generalplus Technology                       | 1        | 0.27%   |
| Focusrite-Novation                           | 1        | 0.27%   |
| FiiO Electronics Technology                  | 1        | 0.27%   |
| DSEA A/S                                     | 1        | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 6.9%    |
| AMD Ryzen HD Audio Controller                                              | 25       | 5.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 4.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 2.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 12       | 2.76%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.76%   |
| AMD Radeon High Definition Audio Controller                                | 12       | 2.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 2.53%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 2.53%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 9        | 2.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.38%   |
| Intel Raptor Lake High Definition Audio Controller                         | 6        | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.15%   |
| Nvidia GA102 High Definition Audio Controller                              | 5        | 1.15%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.15%   |
| Nvidia GP102 HDMI Audio Controller                                         | 4        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 0.92%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 0.92%   |
| ASUSTek Computer USB Audio                                                 | 4        | 0.92%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4        | 0.92%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 0.92%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 3        | 0.69%   |
| Tenx Technology USB AUDIO                                                  | 3        | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 22       | 13.92%  |
| Corsair                        | 19       | 12.03%  |
| G.Skill                        | 16       | 10.13%  |
| Samsung Electronics            | 15       | 9.49%   |
| Micron Technology              | 15       | 9.49%   |
| Crucial                        | 15       | 9.49%   |
| SK hynix                       | 11       | 6.96%   |
| KLEVV                          | 6        | 3.8%    |
| A-DATA Technology              | 5        | 3.16%   |
| Unknown                        | 4        | 2.53%   |
| Transcend                      | 3        | 1.9%    |
| Patriot                        | 3        | 1.9%    |
| Unknown                        | 3        | 1.9%    |
| Unknown (ABCD)                 | 2        | 1.27%   |
| Kingmax                        | 2        | 1.27%   |
| Unknown (0x0E9D)               | 1        | 0.63%   |
| Unknown (0x0E25)               | 1        | 0.63%   |
| Unknown (0x0B92)               | 1        | 0.63%   |
| Unknown (00000000802C)         | 1        | 0.63%   |
| Red Hat                        | 1        | 0.63%   |
| Ramos Technology               | 1        | 0.63%   |
| Qimonda                        | 1        | 0.63%   |
| Patriot Memory                 | 1        | 0.63%   |
| Nanya Technology               | 1        | 0.63%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 0.63%   |
| Lexar                          | 1        | 0.63%   |
| Kingmax Semiconductor          | 1        | 0.63%   |
| Essencore Limited              | 1        | 0.63%   |
| Elpida                         | 1        | 0.63%   |
| ASint Technology               | 1        | 0.63%   |
| Apotop                         | 1        | 0.63%   |
| Apacer                         | 1        | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s              | 3        | 1.67%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 3        | 1.67%   |
| Unknown                                                          | 3        | 1.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 2        | 1.11%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2        | 1.11%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s            | 2        | 1.11%   |
| Patriot RAM 6400 Series 32GB DIMM DDR5 6400MT/s                  | 2        | 1.11%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s               | 2        | 1.11%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s              | 2        | 1.11%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s            | 2        | 1.11%   |
| Kingston RAM 9905471-021.A00LF 4GB DIMM DDR3 1333MT/s            | 2        | 1.11%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 2        | 1.11%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s           | 2        | 1.11%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s             | 2        | 1.11%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3600MT/s              | 2        | 1.11%   |
| Crucial RAM CT8G4DFS8213.C8FBD1 8GB DIMM DDR4 2133MT/s           | 2        | 1.11%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s           | 2        | 1.11%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                     | 2        | 1.11%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1        | 0.56%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1        | 0.56%   |
| Unknown RAM Module 32GB DIMM DDR4 2666MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1        | 0.56%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.56%   |
| Unknown (0x0E25) RAM HMA82GS6AFR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 0.56%   |
| Unknown (0x0B92) RAM Module 16GB DIMM DDR4 3200MT/s              | 1        | 0.56%   |
| Unknown (00000000802C) RAM AGI266608UD138 8GB DIMM DDR4 2667MT/s | 1        | 0.56%   |
| Transcend RAM TS1GSH64V2B 8GB SODIMM DDR4 3200MT/s               | 1        | 0.56%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                 | 1        | 0.56%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                | 1        | 0.56%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                       | 1        | 0.56%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB DIMM DDR3 1600MT/s             | 1        | 0.56%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1        | 0.56%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1        | 0.56%   |
| SK hynix RAM HMA84GL7MMR4N-TF 32GB DIMM DDR4 2133MT/s            | 1        | 0.56%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2400MT/s             | 1        | 0.56%   |
| SK hynix RAM HMA81GU6DJR8N-WM 8GB DIMM DDR4 3000MT/s             | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 50.35%  |
| DDR3    | 36       | 25.53%  |
| DDR5    | 21       | 14.89%  |
| SDRAM   | 7        | 4.96%   |
| LPDDR4  | 2        | 1.42%   |
| DDR2    | 2        | 1.42%   |
| RAM     | 1        | 0.71%   |
| Unknown | 1        | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 120      | 88.89%  |
| SODIMM | 15       | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 50       | 33.11%  |
| 16384 | 44       | 29.14%  |
| 4096  | 24       | 15.89%  |
| 32768 | 20       | 13.25%  |
| 2048  | 10       | 6.62%   |
| 65536 | 1        | 0.66%   |
| 49152 | 1        | 0.66%   |
| 1024  | 1        | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 27       | 16.77%  |
| 3200    | 19       | 11.8%   |
| 2400    | 16       | 9.94%   |
| 3600    | 14       | 8.7%    |
| 2667    | 11       | 6.83%   |
| 1333    | 9        | 5.59%   |
| 6000    | 7        | 4.35%   |
| 2666    | 7        | 4.35%   |
| 6400    | 6        | 3.73%   |
| 2133    | 6        | 3.73%   |
| 5600    | 4        | 2.48%   |
| 3733    | 4        | 2.48%   |
| 4800    | 3        | 1.86%   |
| 4000    | 3        | 1.86%   |
| 3400    | 2        | 1.24%   |
| 2048    | 2        | 1.24%   |
| 1867    | 2        | 1.24%   |
| 1866    | 2        | 1.24%   |
| 1800    | 2        | 1.24%   |
| Unknown | 2        | 1.24%   |
| 12800   | 1        | 0.62%   |
| 7000    | 1        | 0.62%   |
| 4333    | 1        | 0.62%   |
| 3866    | 1        | 0.62%   |
| 3800    | 1        | 0.62%   |
| 3666    | 1        | 0.62%   |
| 3266    | 1        | 0.62%   |
| 3000    | 1        | 0.62%   |
| 2933    | 1        | 0.62%   |
| 2200    | 1        | 0.62%   |
| 2134    | 1        | 0.62%   |
| 1067    | 1        | 0.62%   |
| 667     | 1        | 0.62%   |

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
| Logitech                 | 9        | 37.5%   |
| Realtek Semiconductor    | 2        | 8.33%   |
| Microdia                 | 2        | 8.33%   |
| XF                       | 1        | 4.17%   |
| USB CAMERA               | 1        | 4.17%   |
| SN0002                   | 1        | 4.17%   |
| Samsung Electronics      | 1        | 4.17%   |
| Razer USA                | 1        | 4.17%   |
| Jieli Technology         | 1        | 4.17%   |
| Hewlett-Packard          | 1        | 4.17%   |
| Apple                    | 1        | 4.17%   |
| Anker PowerConf C200     | 1        | 4.17%   |
| Alpha Imaging Technology | 1        | 4.17%   |
| Alcor Micro              | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech HD Webcam C615                   | 3        | 12.5%   |
| Logitech HD Pro Webcam C920               | 3        | 12.5%   |
| XF HDMI Capture                           | 1        | 4.17%   |
| USB CAMERA USB CAMERA                     | 1        | 4.17%   |
| SN0002 2K USB Camera                      | 1        | 4.17%   |
| Samsung Galaxy series, misc. (MTP mode)   | 1        | 4.17%   |
| Realtek HP 1.0MP High Definition Webcam   | 1        | 4.17%   |
| Realtek Asus laptop camera                | 1        | 4.17%   |
| Razer USA Razer Kiyo X                    | 1        | 4.17%   |
| Microdia Webcam Vitade AF                 | 1        | 4.17%   |
| Microdia USB 2.0 Camera                   | 1        | 4.17%   |
| Logitech Webcam C310                      | 1        | 4.17%   |
| Logitech Webcam C270                      | 1        | 4.17%   |
| Logitech BRIO Ultra HD Webcam             | 1        | 4.17%   |
| Jieli USB Composite Device                | 1        | 4.17%   |
| HP HP Webcam HD 3310                      | 1        | 4.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 1        | 4.17%   |
| Anker PowerConf C200 Anker PowerConf C200 | 1        | 4.17%   |
| Alpha Imaging HIK 4K Camera               | 1        | 4.17%   |
| Alcor Micro USB 2.0 PC Camera             | 1        | 4.17%   |

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
| 0     | 177      | 79.73%  |
| 1     | 39       | 17.57%  |
| 2     | 4        | 1.8%    |
| 6     | 2        | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 31.37%  |
| Net/wireless             | 15       | 29.41%  |
| Unassigned class         | 5        | 9.8%    |
| Communication controller | 5        | 9.8%    |
| Multimedia controller    | 3        | 5.88%   |
| Network                  | 2        | 3.92%   |
| Storage/raid             | 1        | 1.96%   |
| Storage                  | 1        | 1.96%   |
| Net/ethernet             | 1        | 1.96%   |
| Fingerprint reader       | 1        | 1.96%   |
| Dvb card                 | 1        | 1.96%   |

