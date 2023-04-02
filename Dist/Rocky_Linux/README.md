Rocky Linux - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Rocky_Linux/Desktop/README.md) and [notebooks](/Dist/Rocky_Linux/Notebook/README.md).

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

Total: 162

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | C621-WD12-IPMI M18907       | Server      | [030b77c94d](https://linux-hardware.org/?probe=030b77c94d) | Mar 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| Dell          | Inspiron 7573               | Convertible | [c89a114562](https://linux-hardware.org/?probe=c89a114562) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fd875a6058](https://linux-hardware.org/?probe=fd875a6058) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [5b55ac3757](https://linux-hardware.org/?probe=5b55ac3757) | Mar 15, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| AZW           | GTR V02                     | Desktop     | [fcd41fbe77](https://linux-hardware.org/?probe=fcd41fbe77) | Mar 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [154f8780de](https://linux-hardware.org/?probe=154f8780de) | Feb 28, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | Desktop     | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [b82d6321ef](https://linux-hardware.org/?probe=b82d6321ef) | Feb 19, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S8B500    | Notebook    | [b4cbe5bf11](https://linux-hardware.org/?probe=b4cbe5bf11) | Feb 16, 2023 |
| HP            | 1587h                       | Desktop     | [312effb7b7](https://linux-hardware.org/?probe=312effb7b7) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5420               | Notebook    | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [bf2c6ebd43](https://linux-hardware.org/?probe=bf2c6ebd43) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Positivo      | Mobile                      | Notebook    | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [b735bbde51](https://linux-hardware.org/?probe=b735bbde51) | Jan 29, 2023 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Lenovo        | NOK                         | Desktop     | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [784e2db087](https://linux-hardware.org/?probe=784e2db087) | Jan 25, 2023 |
| HP            | 8952                        | Mini pc     | [e49754f551](https://linux-hardware.org/?probe=e49754f551) | Jan 23, 2023 |
| HP            | 8881                        | Mini pc     | [d9864f2860](https://linux-hardware.org/?probe=d9864f2860) | Jan 23, 2023 |
| HP            | 8952                        | Mini pc     | [c025c38b83](https://linux-hardware.org/?probe=c025c38b83) | Jan 23, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| Dell          | Precision M6800             | Notebook    | [bcd98b78c4](https://linux-hardware.org/?probe=bcd98b78c4) | Jan 19, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ff9464407f](https://linux-hardware.org/?probe=ff9464407f) | Jan 15, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4ce3e32165](https://linux-hardware.org/?probe=4ce3e32165) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [26089f2f9b](https://linux-hardware.org/?probe=26089f2f9b) | Jan 12, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [ae26f02480](https://linux-hardware.org/?probe=ae26f02480) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [42f45d59d2](https://linux-hardware.org/?probe=42f45d59d2) | Dec 29, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | 805D                        | Desktop     | [cf88e571df](https://linux-hardware.org/?probe=cf88e571df) | Dec 28, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| HP            | ProBook 640 G3              | Notebook    | [03eba7b664](https://linux-hardware.org/?probe=03eba7b664) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [ede2606ad1](https://linux-hardware.org/?probe=ede2606ad1) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Intel         | D33217GKE G69901-202        | Desktop     | [f10d00e42a](https://linux-hardware.org/?probe=f10d00e42a) | Nov 12, 2022 |
| HP            | 8054                        | Desktop     | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | Desktop     | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | Desktop     | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [6d994999c9](https://linux-hardware.org/?probe=6d994999c9) | Nov 01, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| AZW           | GTR V01                     | Mini pc     | [40c181376b](https://linux-hardware.org/?probe=40c181376b) | Oct 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [4638cc7f7b](https://linux-hardware.org/?probe=4638cc7f7b) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Dell          | Latitude 5430               | Notebook    | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [79c81eef28](https://linux-hardware.org/?probe=79c81eef28) | Aug 23, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [ce5ca74472](https://linux-hardware.org/?probe=ce5ca74472) | Jul 17, 2022 |
| Unknown       | Unknown                     | Tablet      | [bf70ad93f5](https://linux-hardware.org/?probe=bf70ad93f5) | Jul 06, 2022 |
| Unknown       | Unknown                     | Tablet      | [6edba7f033](https://linux-hardware.org/?probe=6edba7f033) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| Unknown       | X31_ICH7                    | Desktop     | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 072T6D A01                  | Server      | [4b88759a98](https://linux-hardware.org/?probe=4b88759a98) | May 06, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1             | Desktop     | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| IBM           | 4367 SVT                    | Server      | [3d7400ea9b](https://linux-hardware.org/?probe=3d7400ea9b) | Mar 11, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Supermicro    | X11SSH-CTF                  | Server      | [7a720a4e41](https://linux-hardware.org/?probe=7a720a4e41) | Mar 10, 2022 |
| Dell          | Latitude 5500               | Notebook    | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| Supermicro    | X11SPW-TF                   | Server      | [a76bb2e30d](https://linux-hardware.org/?probe=a76bb2e30d) | Feb 07, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [02e5c56a80](https://linux-hardware.org/?probe=02e5c56a80) | Feb 03, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [4aa06b4edd](https://linux-hardware.org/?probe=4aa06b4edd) | Feb 03, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6               | Desktop     | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| Dell          | 0X3D66 A07                  | Server      | [d5c4ef93c4](https://linux-hardware.org/?probe=d5c4ef93c4) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c7f9478d55](https://linux-hardware.org/?probe=c7f9478d55) | Jan 03, 2022 |
| AZW           | Gemini M                    | Desktop     | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                    | Desktop     | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Panther                     | Desktop     | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo        | ThinkPad W540 20BGCTO1WW    | Notebook    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d7947a5a8](https://linux-hardware.org/?probe=9d7947a5a8) | Nov 06, 2021 |
| Toshiba       | TECRA W50-A                 | Notebook    | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Dell          | 0N4YC8 A00                  | Desktop     | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| Intel         | S2600WFT H48104-850         | Server      | [36c4acac2d](https://linux-hardware.org/?probe=36c4acac2d) | Sep 14, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406132G       | Notebook    | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| HP            | 0B54h D                     | Desktop     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |
| Acer          | Aspire VN7-591G             | Notebook    | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Rocky Linux 9.1 | 35        | 27.78%  |
| Rocky Linux 8.5 | 31        | 24.6%   |
| Rocky Linux 9.0 | 19        | 15.08%  |
| Rocky Linux 8.4 | 19        | 15.08%  |
| Rocky Linux 8.6 | 11        | 8.73%   |
| Rocky Linux 8.7 | 9         | 7.14%   |
| Rocky Linux 8.3 | 2         | 1.59%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 124       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 17        | 13.18%  |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 10.08%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 6.2%    |
| 5.14.0-162.18.1.el9_1.x86_64     | 6         | 4.65%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 4.65%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 5         | 3.88%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 3.88%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 5         | 3.88%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 3.1%    |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 3.1%    |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 3.1%    |
| 5.14.0-162.6.1.el9_1.x86_64      | 3         | 2.33%   |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 2.33%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 3         | 2.33%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 3         | 2.33%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 3         | 2.33%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 2.33%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 2         | 1.55%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 1.55%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 1.55%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 1.55%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 1.55%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 1.55%   |
| 4.18.0-305.el8.x86_64            | 2         | 1.55%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 1.55%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 1.55%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 1.55%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 1.55%   |
| 6.1.8-1.el9.elrepo.x86_64        | 1         | 0.78%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1         | 0.78%   |
| 6.0.10_tkg_bmq                   | 1         | 0.78%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1         | 0.78%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 0.78%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 0.78%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 0.78%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 0.78%   |
| 5.10.89-1.el8.x86_64             | 1         | 0.78%   |
| 5.10.52-v8.1.el8                 | 1         | 0.78%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 0.78%   |
| 4.18.0-348.23.1.el8_5.x86_64     | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 65        | 52%     |
| 5.14.0  | 51        | 40.8%   |
| 6.0.10  | 2         | 1.6%    |
| 6.1.8   | 1         | 0.8%    |
| 6.1.6   | 1         | 0.8%    |
| 5.4.157 | 1         | 0.8%    |
| 5.16.15 | 1         | 0.8%    |
| 5.14.1  | 1         | 0.8%    |
| 5.10.89 | 1         | 0.8%    |
| 5.10.52 | 1         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 65        | 52%     |
| 5.14    | 52        | 41.6%   |
| 6.1     | 2         | 1.6%    |
| 6.0     | 2         | 1.6%    |
| 5.10    | 2         | 1.6%    |
| 5.4     | 1         | 0.8%    |
| 5.16    | 1         | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 123       | 99.19%  |
| aarch64 | 1         | 0.81%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 85        | 68.55%  |
| Unknown       | 17        | 13.71%  |
| KDE5          | 9         | 7.26%   |
| MATE          | 5         | 4.03%   |
| GNOME Classic | 4         | 3.23%   |
| XFCE          | 3         | 2.42%   |
| X-Cinnamon    | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 69        | 54.33%  |
| X11     | 40        | 31.5%   |
| Tty     | 8         | 6.3%    |
| Unknown | 7         | 5.51%   |
| Web     | 3         | 2.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 57        | 45.97%  |
| GDM     | 55        | 44.35%  |
| SDDM    | 8         | 6.45%   |
| LightDM | 4         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 78        | 62.9%   |
| ru_RU   | 6         | 4.84%   |
| en_CA   | 5         | 4.03%   |
| en_AU   | 5         | 4.03%   |
| en_IL   | 3         | 2.42%   |
| C       | 3         | 2.42%   |
| Unknown | 3         | 2.42%   |
| en_ZA   | 2         | 1.61%   |
| en_SG   | 2         | 1.61%   |
| de_DE   | 2         | 1.61%   |
| de_AT   | 2         | 1.61%   |
| pt_BR   | 1         | 0.81%   |
| pl_PL   | 1         | 0.81%   |
| ko_KR   | 1         | 0.81%   |
| ja_JP   | 1         | 0.81%   |
| it_IT   | 1         | 0.81%   |
| hu_HU   | 1         | 0.81%   |
| fr_FR   | 1         | 0.81%   |
| es_ES   | 1         | 0.81%   |
| es_CO   | 1         | 0.81%   |
| es_AR   | 1         | 0.81%   |
| en_IE   | 1         | 0.81%   |
| en_GB   | 1         | 0.81%   |
| af_ZA   | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 81        | 64.8%   |
| BIOS | 44        | 35.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 102       | 82.26%  |
| Ext4 | 21        | 16.94%  |
| Ext3 | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 64        | 51.61%  |
| Unknown | 40        | 32.26%  |
| MBR     | 20        | 16.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 80.65%  |
| Yes       | 24        | 19.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 84.68%  |
| Yes       | 19        | 15.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 26        | 20.97%  |
| Lenovo                  | 22        | 17.74%  |
| ASUSTek Computer        | 19        | 15.32%  |
| Hewlett-Packard         | 18        | 14.52%  |
| MSI                     | 7         | 5.65%   |
| Gigabyte Technology     | 7         | 5.65%   |
| Intel                   | 3         | 2.42%   |
| AZW                     | 3         | 2.42%   |
| Unknown                 | 3         | 2.42%   |
| Toshiba                 | 2         | 1.61%   |
| Supermicro              | 2         | 1.61%   |
| ASRock                  | 2         | 1.61%   |
| Sapphire                | 1         | 0.81%   |
| Raspberry Pi Foundation | 1         | 0.81%   |
| Positivo                | 1         | 0.81%   |
| NCR                     | 1         | 0.81%   |
| IBM                     | 1         | 0.81%   |
| HUAWEI                  | 1         | 0.81%   |
| Google                  | 1         | 0.81%   |
| BESSTAR Tech            | 1         | 0.81%   |
| BANGHO                  | 1         | 0.81%   |
| Acer                    | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 2.42%   |
| Dell PowerEdge R610                    | 2         | 1.61%   |
| Dell OptiPlex 9020                     | 2         | 1.61%   |
| AZW GTR                                | 2         | 1.61%   |
| Toshiba TECRA W50-A                    | 1         | 0.81%   |
| Toshiba Satellite E45-B                | 1         | 0.81%   |
| Supermicro SYS-5029P-WTR               | 1         | 0.81%   |
| Supermicro Super Server                | 1         | 0.81%   |
| Sapphire PE-AM2RS690V2                 | 1         | 0.81%   |
| RPi Raspberry Pi                       | 1         | 0.81%   |
| Positivo Mobile                        | 1         | 0.81%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 0.81%   |
| MSI MS-7D46                            | 1         | 0.81%   |
| MSI MS-7D25                            | 1         | 0.81%   |
| MSI MS-7B89                            | 1         | 0.81%   |
| MSI MS-7B78                            | 1         | 0.81%   |
| MSI MS-7A94                            | 1         | 0.81%   |
| MSI MS-7917                            | 1         | 0.81%   |
| MSI H510M PRO-E                        | 1         | 0.81%   |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 0.81%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 0.81%   |
| Lenovo ThinkPad W500 406132G           | 1         | 0.81%   |
| Lenovo ThinkPad T480 20L6S8B500        | 1         | 0.81%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 0.81%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 0.81%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 0.81%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 0.81%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK    | 1         | 0.81%   |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 0.81%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 0.81%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.81%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 0.81%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.81%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 0.81%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 0.81%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 0.81%   |
| Lenovo IdeaPad S210 Touch 20257        | 1         | 0.81%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.81%   |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 9         | 7.26%   |
| ASUS PRIME               | 9         | 7.26%   |
| Lenovo IdeaPad           | 7         | 5.65%   |
| Dell Precision           | 5         | 4.03%   |
| Dell PowerEdge           | 5         | 4.03%   |
| Dell OptiPlex            | 4         | 3.23%   |
| Dell Latitude            | 4         | 3.23%   |
| HP ZBook                 | 3         | 2.42%   |
| HP EliteBook             | 3         | 2.42%   |
| Dell XPS                 | 3         | 2.42%   |
| Dell Inspiron            | 3         | 2.42%   |
| Unknown                  | 3         | 2.42%   |
| Lenovo Legion            | 2         | 1.61%   |
| Lenovo IdeaPadFlex       | 2         | 1.61%   |
| HP ProLiant              | 2         | 1.61%   |
| HP Laptop                | 2         | 1.61%   |
| HP EliteDesk             | 2         | 1.61%   |
| Dell Vostro              | 2         | 1.61%   |
| AZW GTR                  | 2         | 1.61%   |
| ASUS ROG                 | 2         | 1.61%   |
| ASUS ASUS                | 2         | 1.61%   |
| Toshiba TECRA            | 1         | 0.81%   |
| Toshiba Satellite        | 1         | 0.81%   |
| Supermicro SYS-5029P-WTR | 1         | 0.81%   |
| Supermicro Super         | 1         | 0.81%   |
| Sapphire PE-AM2RS690V2   | 1         | 0.81%   |
| RPi Raspberry            | 1         | 0.81%   |
| Positivo Mobile          | 1         | 0.81%   |
| NCR xxxx-xxxx-xxxx       | 1         | 0.81%   |
| MSI MS-7D46              | 1         | 0.81%   |
| MSI MS-7D25              | 1         | 0.81%   |
| MSI MS-7B89              | 1         | 0.81%   |
| MSI MS-7B78              | 1         | 0.81%   |
| MSI MS-7A94              | 1         | 0.81%   |
| MSI MS-7917              | 1         | 0.81%   |
| MSI H510M                | 1         | 0.81%   |
| Lenovo ThinkStation      | 1         | 0.81%   |
| Lenovo ThinkCentre       | 1         | 0.81%   |
| Intel S2600WFT           | 1         | 0.81%   |
| Intel PRO412081          | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 21        | 16.94%  |
| 2020    | 16        | 12.9%   |
| 2018    | 14        | 11.29%  |
| 2022    | 10        | 8.06%   |
| 2019    | 10        | 8.06%   |
| 2011    | 10        | 8.06%   |
| 2013    | 9         | 7.26%   |
| 2014    | 8         | 6.45%   |
| 2015    | 7         | 5.65%   |
| 2012    | 5         | 4.03%   |
| 2010    | 4         | 3.23%   |
| 2008    | 3         | 2.42%   |
| 2017    | 2         | 1.61%   |
| 2016    | 2         | 1.61%   |
| 2009    | 2         | 1.61%   |
| Unknown | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 55        | 44.35%  |
| Notebook       | 48        | 38.71%  |
| Server         | 12        | 9.68%   |
| Mini pc        | 4         | 3.23%   |
| Convertible    | 3         | 2.42%   |
| System on chip | 1         | 0.81%   |
| Tablet         | 1         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 110       | 88.71%  |
| Enabled  | 14        | 11.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 99.19%  |
| Yes  | 1         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 33        | 26.4%   |
| 4.01-8.0        | 23        | 18.4%   |
| 32.01-64.0      | 23        | 18.4%   |
| 16.01-24.0      | 16        | 12.8%   |
| 64.01-256.0     | 10        | 8%      |
| 3.01-4.0        | 7         | 5.6%    |
| More than 256.0 | 4         | 3.2%    |
| 1.01-2.0        | 4         | 3.2%    |
| 24.01-32.0      | 3         | 2.4%    |
| 2.01-3.0        | 2         | 1.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 34        | 26.36%  |
| 4.01-8.0   | 29        | 22.48%  |
| 3.01-4.0   | 25        | 19.38%  |
| 1.01-2.0   | 20        | 15.5%   |
| 8.01-16.0  | 8         | 6.2%    |
| 0.51-1.0   | 6         | 4.65%   |
| 32.01-64.0 | 2         | 1.55%   |
| 16.01-24.0 | 2         | 1.55%   |
| 0.01-0.5   | 2         | 1.55%   |
| 24.01-32.0 | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 56.8%   |
| 2      | 22        | 17.6%   |
| 3      | 11        | 8.8%    |
| 4      | 9         | 7.2%    |
| 6      | 3         | 2.4%    |
| 5      | 2         | 1.6%    |
| 19     | 1         | 0.8%    |
| 18     | 1         | 0.8%    |
| 17     | 1         | 0.8%    |
| 16     | 1         | 0.8%    |
| 14     | 1         | 0.8%    |
| 9      | 1         | 0.8%    |
| 8      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 70.97%  |
| Yes       | 36        | 29.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 88.8%   |
| No        | 14        | 11.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 58.4%   |
| No        | 52        | 41.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 50.4%   |
| Yes       | 62        | 49.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 33        | 26.61%  |
| Canada       | 8         | 6.45%   |
| Russia       | 7         | 5.65%   |
| Germany      | 6         | 4.84%   |
| Australia    | 6         | 4.84%   |
| Italy        | 4         | 3.23%   |
| Czechia      | 4         | 3.23%   |
| UK           | 3         | 2.42%   |
| South Africa | 3         | 2.42%   |
| Singapore    | 3         | 2.42%   |
| Poland       | 3         | 2.42%   |
| Israel       | 3         | 2.42%   |
| Sweden       | 2         | 1.61%   |
| South Korea  | 2         | 1.61%   |
| Netherlands  | 2         | 1.61%   |
| Mexico       | 2         | 1.61%   |
| Indonesia    | 2         | 1.61%   |
| India        | 2         | 1.61%   |
| Hungary      | 2         | 1.61%   |
| France       | 2         | 1.61%   |
| Brazil       | 2         | 1.61%   |
| Belgium      | 2         | 1.61%   |
| Argentina    | 2         | 1.61%   |
| Uzbekistan   | 1         | 0.81%   |
| UAE          | 1         | 0.81%   |
| Turkey       | 1         | 0.81%   |
| Switzerland  | 1         | 0.81%   |
| Spain        | 1         | 0.81%   |
| Slovakia     | 1         | 0.81%   |
| Saudi Arabia | 1         | 0.81%   |
| Portugal     | 1         | 0.81%   |
| Pakistan     | 1         | 0.81%   |
| Norway       | 1         | 0.81%   |
| Malaysia     | 1         | 0.81%   |
| Kazakhstan   | 1         | 0.81%   |
| Japan        | 1         | 0.81%   |
| Ireland      | 1         | 0.81%   |
| Finland      | 1         | 0.81%   |
| Croatia      | 1         | 0.81%   |
| Colombia     | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 2.42%   |
| Melbourne              | 3         | 2.42%   |
| Toronto                | 2         | 1.61%   |
| Prague                 | 2         | 1.61%   |
| Moscow                 | 2         | 1.61%   |
| Mirfield               | 2         | 1.61%   |
| Krakow                 | 2         | 1.61%   |
| Haifa                  | 2         | 1.61%   |
| Centurion              | 2         | 1.61%   |
| Budapest               | 2         | 1.61%   |
| Berlin                 | 2         | 1.61%   |
| Adelaide               | 2         | 1.61%   |
| Žilina                | 1         | 0.81%   |
| Yogyakarta             | 1         | 0.81%   |
| Yekaterinburg          | 1         | 0.81%   |
| Xi'an                  | 1         | 0.81%   |
| Woodridge              | 1         | 0.81%   |
| Wells                  | 1         | 0.81%   |
| Washington             | 1         | 0.81%   |
| Waltham                | 1         | 0.81%   |
| Voronezh               | 1         | 0.81%   |
| Vienna                 | 1         | 0.81%   |
| Vancouver              | 1         | 0.81%   |
| Urbana                 | 1         | 0.81%   |
| Torrington             | 1         | 0.81%   |
| Tlaxcala City          | 1         | 0.81%   |
| Syracuse               | 1         | 0.81%   |
| St. John's             | 1         | 0.81%   |
| St Petersburg          | 1         | 0.81%   |
| Split                  | 1         | 0.81%   |
| Sobral de Monte Agraco | 1         | 0.81%   |
| Smolensk               | 1         | 0.81%   |
| Senigallia             | 1         | 0.81%   |
| Semarang               | 1         | 0.81%   |
| Scarborough            | 1         | 0.81%   |
| San Miguel de Tucumán | 1         | 0.81%   |
| Rotterdam              | 1         | 0.81%   |
| Riyadh                 | 1         | 0.81%   |
| Rehovot                | 1         | 0.81%   |
| Rawalpindi             | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 34        | 46     | 17.99%  |
| Seagate                     | 28        | 82     | 14.81%  |
| WDC                         | 26        | 52     | 13.76%  |
| Toshiba                     | 14        | 17     | 7.41%   |
| Intel                       | 8         | 10     | 4.23%   |
| Hitachi                     | 8         | 12     | 4.23%   |
| SanDisk                     | 7         | 9      | 3.7%    |
| Kingston                    | 7         | 7      | 3.7%    |
| SK hynix                    | 5         | 7      | 2.65%   |
| Crucial                     | 5         | 6      | 2.65%   |
| Unknown                     | 4         | 4      | 2.12%   |
| Phison                      | 3         | 3      | 1.59%   |
| HGST                        | 3         | 3      | 1.59%   |
| Micron Technology           | 2         | 2      | 1.06%   |
| LITEONIT                    | 2         | 2      | 1.06%   |
| Lexar                       | 2         | 2      | 1.06%   |
| Corsair                     | 2         | 2      | 1.06%   |
| A-DATA Technology           | 2         | 2      | 1.06%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.53%   |
| UMIS                        | 1         | 1      | 0.53%   |
| Team                        | 1         | 1      | 0.53%   |
| StoreJet                    | 1         | 1      | 0.53%   |
| PNY                         | 1         | 1      | 0.53%   |
| Phison Electronics          | 1         | 16     | 0.53%   |
| MyDigitalSSD                | 1         | 1      | 0.53%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.53%   |
| LITEON                      | 1         | 1      | 0.53%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.53%   |
| Kingston Technology Company | 1         | 1      | 0.53%   |
| KingFast                    | 1         | 1      | 0.53%   |
| JMicron Technology          | 1         | 1      | 0.53%   |
| INDMEM                      | 1         | 1      | 0.53%   |
| IBM                         | 1         | 1      | 0.53%   |
| HS-SSD-C100                 | 1         | 1      | 0.53%   |
| Hewlett-Packard             | 1         | 1      | 0.53%   |
| GOODRAM                     | 1         | 1      | 0.53%   |
| Gigabyte Technology         | 1         | 1      | 0.53%   |
| Fujitsu                     | 1         | 1      | 0.53%   |
| Dogfish                     | 1         | 1      | 0.53%   |
| Digma                       | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3         | 1.37%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2         | 0.91%   |
| Unknown MMC Card  64GB           | 2         | 0.91%   |
| Seagate ST9320325AS 320GB        | 2         | 0.91%   |
| Seagate ST300MP0005 304GB        | 2         | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.91%   |
| Samsung SSD 870 EVO 1TB          | 2         | 0.91%   |
| Samsung SSD 860 EVO 1TB          | 2         | 0.91%   |
| Lexar 512GB SSD                  | 2         | 0.91%   |
| Crucial CT1000MX500SSD1 1TB      | 2         | 0.91%   |
| A-DATA SWORDFISH 1TB             | 2         | 0.91%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1         | 0.46%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.46%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1         | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.46%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1         | 0.46%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD   | 1         | 0.46%   |
| WDC WDBNCE0010PNC 1TB SSD        | 1         | 0.46%   |
| WDC WD80EZZX-11CSGA0 8TB         | 1         | 0.46%   |
| WDC WD80EMAZ-00WJTA0 8TB         | 1         | 0.46%   |
| WDC WD80EDAZ-11TA3A0 8TB         | 1         | 0.46%   |
| WDC WD60EFAX-68JH4N1 6TB         | 1         | 0.46%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.46%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 0.46%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 1         | 0.46%   |
| WDC WD5000BPVT-00A1YT0 500GB     | 1         | 0.46%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1         | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 0.46%   |
| WDC WD5000AAKS-402AA0 500GB      | 1         | 0.46%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1         | 0.46%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1         | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.46%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1         | 0.46%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1         | 0.46%   |
| WDC WD20EFZX-68AWUN0 2TB         | 1         | 0.46%   |
| WDC WD2002FAEX-007BA0 2TB        | 1         | 0.46%   |
| WDC WD120EDAZ-11F3RA0 12TB       | 1         | 0.46%   |
| WDC WD10SPCX-24HWST1 1TB         | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 82     | 40%     |
| WDC                 | 19        | 39     | 27.14%  |
| Hitachi             | 8         | 12     | 11.43%  |
| Toshiba             | 7         | 9      | 10%     |
| Samsung Electronics | 2         | 3      | 2.86%   |
| HGST                | 2         | 2      | 2.86%   |
| Unknown             | 1         | 1      | 1.43%   |
| StoreJet            | 1         | 1      | 1.43%   |
| IBM                 | 1         | 1      | 1.43%   |
| Fujitsu             | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 25%     |
| WDC                 | 7         | 10     | 11.67%  |
| Toshiba             | 5         | 5      | 8.33%   |
| SanDisk             | 5         | 6      | 8.33%   |
| Kingston            | 4         | 4      | 6.67%   |
| Crucial             | 4         | 5      | 6.67%   |
| SK hynix            | 2         | 2      | 3.33%   |
| LITEONIT            | 2         | 2      | 3.33%   |
| Intel               | 2         | 3      | 3.33%   |
| Team                | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| MyDigitalSSD        | 1         | 1      | 1.67%   |
| LITEON              | 1         | 1      | 1.67%   |
| Lexar               | 1         | 1      | 1.67%   |
| KingFast            | 1         | 1      | 1.67%   |
| INDMEM              | 1         | 1      | 1.67%   |
| GOODRAM             | 1         | 1      | 1.67%   |
| Gigabyte Technology | 1         | 1      | 1.67%   |
| Dogfish             | 1         | 1      | 1.67%   |
| Corsair             | 1         | 1      | 1.67%   |
| China               | 1         | 1      | 1.67%   |
| Apacer              | 1         | 1      | 1.67%   |
| ADATA SU            | 1         | 1      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 52        | 82     | 32.1%   |
| HDD     | 52        | 151    | 32.1%   |
| SSD     | 50        | 70     | 30.86%  |
| Unknown | 5         | 5      | 3.09%   |
| MMC     | 3         | 3      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 83        | 211    | 55.7%   |
| NVMe | 52        | 82     | 34.9%   |
| SAS  | 11        | 15     | 7.38%   |
| MMC  | 3         | 3      | 2.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 83     | 46.85%  |
| 0.51-1.0   | 34        | 71     | 30.63%  |
| 1.01-2.0   | 14        | 24     | 12.61%  |
| 3.01-4.0   | 6         | 25     | 5.41%   |
| 10.01-20.0 | 2         | 3      | 1.8%    |
| 4.01-10.0  | 2         | 14     | 1.8%    |
| 2.01-3.0   | 1         | 1      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 33        | 26.4%   |
| 251-500        | 29        | 23.2%   |
| 501-1000       | 19        | 15.2%   |
| 1001-2000      | 16        | 12.8%   |
| More than 3000 | 8         | 6.4%    |
| 2001-3000      | 7         | 5.6%    |
| 51-100         | 7         | 5.6%    |
| Unknown        | 4         | 3.2%    |
| 1-20           | 2         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 35.43%  |
| 21-50          | 28        | 22.05%  |
| 51-100         | 14        | 11.02%  |
| 101-250        | 11        | 8.66%   |
| 501-1000       | 10        | 7.87%   |
| 251-500        | 7         | 5.51%   |
| More than 3000 | 4         | 3.15%   |
| Unknown        | 4         | 3.15%   |
| 1001-2000      | 3         | 2.36%   |
| 2001-3000      | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 6.67%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 2      | 6.67%   |
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 6.67%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 6.67%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 6.67%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 6.67%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 6.67%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 6.67%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 6.67%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 6.67%   |
| Hitachi HDS725050KLA360 500GB         | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 6.67%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 16     | 40%     |
| WDC     | 3         | 7      | 20%     |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |
| IBM     | 1         | 1      | 6.67%   |
| Corsair | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 16     | 42.86%  |
| WDC     | 3         | 7      | 21.43%  |
| Hitachi | 3         | 3      | 21.43%  |
| Toshiba | 1         | 1      | 7.14%   |
| IBM     | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 28     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 81        | 202    | 57.04%  |
| Detected | 47        | 79     | 33.1%   |
| Malfunc  | 13        | 29     | 9.15%   |
| Failed   | 1         | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 81        | 47.37%  |
| AMD                          | 26        | 15.2%   |
| Samsung Electronics          | 18        | 10.53%  |
| Phison Electronics           | 5         | 2.92%   |
| LSI Logic / Symbios Logic    | 5         | 2.92%   |
| SanDisk                      | 4         | 2.34%   |
| Kingston Technology Company  | 4         | 2.34%   |
| SK hynix                     | 3         | 1.75%   |
| Broadcom / LSI               | 3         | 1.75%   |
| ASMedia Technology           | 3         | 1.75%   |
| Toshiba America Info Systems | 2         | 1.17%   |
| Realtek Semiconductor        | 2         | 1.17%   |
| Micron Technology            | 2         | 1.17%   |
| Hewlett-Packard              | 2         | 1.17%   |
| VIA Technologies             | 1         | 0.58%   |
| Union Memory (Shenzhen)      | 1         | 0.58%   |
| Silicon Motion               | 1         | 0.58%   |
| Shenzhen Longsys Electronics | 1         | 0.58%   |
| Micron/Crucial Technology    | 1         | 0.58%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.58%   |
| Marvell Technology Group     | 1         | 0.58%   |
| KIOXIA                       | 1         | 0.58%   |
| JMicron Technology           | 1         | 0.58%   |
| ADATA Technology             | 1         | 0.58%   |
| Adaptec                      | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 8.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 4.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 4.02%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 3.02%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 3.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 2.01%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 2.01%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.51%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.51%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 1.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.51%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.51%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 1.51%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 1.01%   |
| Realtek NVMe Controller                                                                 | 2         | 1.01%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 1.01%   |
| Micron NVMe Storage Controller                                                          | 2         | 1.01%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 1.01%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 1.01%   |
| Intel SSD 660P Series                                                                   | 2         | 1.01%   |
| Intel Non-Volatile memory controller                                                    | 2         | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.01%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.01%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.01%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.01%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.01%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 44.07%  |
| NVMe | 52        | 29.38%  |
| RAID | 21        | 11.86%  |
| IDE  | 20        | 11.3%   |
| SAS  | 5         | 2.82%   |
| SCSI | 1         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 73.39%  |
| AMD    | 32        | 25.81%  |
| ARM    | 1         | 0.81%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 3.23%   |
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 1.61%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 2         | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 1.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.61%   |
| Intel 12th Gen Core i5-12400F               | 2         | 1.61%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.61%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.61%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 0.81%   |
| Intel Xeon Platinum 8124M CPU @ 3.00GHz     | 1         | 0.81%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 0.81%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.81%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.81%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.81%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 0.81%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.81%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.81%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1         | 0.81%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 0.81%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 0.81%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.81%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.81%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.81%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.81%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 0.81%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.81%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.81%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.81%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.81%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.81%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.81%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 27        | 21.77%  |
| Other                   | 19        | 15.32%  |
| Intel Core i5           | 15        | 12.1%   |
| Intel Xeon              | 14        | 11.29%  |
| AMD Ryzen 7             | 7         | 5.65%   |
| AMD Ryzen 5             | 7         | 5.65%   |
| Intel Core i3           | 6         | 4.84%   |
| Intel Celeron           | 4         | 3.23%   |
| AMD Ryzen 9             | 4         | 3.23%   |
| AMD FX                  | 3         | 2.42%   |
| AMD Ryzen Threadripper  | 2         | 1.61%   |
| AMD Ryzen 5 PRO         | 2         | 1.61%   |
| Intel Xeon Silver       | 1         | 0.81%   |
| Intel Xeon Platinum     | 1         | 0.81%   |
| Intel Xeon Gold         | 1         | 0.81%   |
| Intel Pentium Silver    | 1         | 0.81%   |
| Intel Pentium Dual-Core | 1         | 0.81%   |
| Intel Pentium Dual      | 1         | 0.81%   |
| Intel Core i9           | 1         | 0.81%   |
| Intel Core 2 Quad       | 1         | 0.81%   |
| Intel Core 2 Duo        | 1         | 0.81%   |
| AMD Ryzen Embedded      | 1         | 0.81%   |
| AMD Ryzen 7 PRO         | 1         | 0.81%   |
| AMD Ryzen 3             | 1         | 0.81%   |
| AMD Phenom II X6        | 1         | 0.81%   |
| AMD A8                  | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 45        | 36.29%  |
| 2      | 23        | 18.55%  |
| 6      | 20        | 16.13%  |
| 8      | 18        | 14.52%  |
| 12     | 5         | 4.03%   |
| 16     | 4         | 3.23%   |
| 10     | 2         | 1.61%   |
| 36     | 1         | 0.81%   |
| 32     | 1         | 0.81%   |
| 28     | 1         | 0.81%   |
| 24     | 1         | 0.81%   |
| 14     | 1         | 0.81%   |
| 3      | 1         | 0.81%   |
| 1      | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 114       | 91.94%  |
| 2      | 10        | 8.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 97        | 78.23%  |
| 1      | 27        | 21.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 124       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 12        | 9.68%   |
| 0x806c1    | 7         | 5.65%   |
| 0x306a9    | 6         | 4.84%   |
| 0x206a7    | 6         | 4.84%   |
| 0x806ec    | 5         | 4.03%   |
| 0x506e3    | 5         | 4.03%   |
| 0x0a50000c | 4         | 3.23%   |
| 0xa0652    | 3         | 2.42%   |
| 0x806ea    | 3         | 2.42%   |
| 0x50654    | 3         | 2.42%   |
| Unknown    | 3         | 2.42%   |
| 0xa0671    | 2         | 1.61%   |
| 0xa0655    | 2         | 1.61%   |
| 0x906a3    | 2         | 1.61%   |
| 0x90675    | 2         | 1.61%   |
| 0x90672    | 2         | 1.61%   |
| 0x706a8    | 2         | 1.61%   |
| 0x406f1    | 2         | 1.61%   |
| 0x40651    | 2         | 1.61%   |
| 0x306e4    | 2         | 1.61%   |
| 0x206d7    | 2         | 1.61%   |
| 0x206c2    | 2         | 1.61%   |
| 0x106a5    | 2         | 1.61%   |
| 0x10676    | 2         | 1.61%   |
| 0x08608103 | 2         | 1.61%   |
| 0x08600106 | 2         | 1.61%   |
| 0x08600104 | 2         | 1.61%   |
| 0x0800820d | 2         | 1.61%   |
| 0x06000852 | 2         | 1.61%   |
| 0xa0653    | 1         | 0.81%   |
| 0x906ed    | 1         | 0.81%   |
| 0x906ea    | 1         | 0.81%   |
| 0x906a4    | 1         | 0.81%   |
| 0x806e9    | 1         | 0.81%   |
| 0x706a1    | 1         | 0.81%   |
| 0x6fd      | 1         | 0.81%   |
| 0x50657    | 1         | 0.81%   |
| 0x406e3    | 1         | 0.81%   |
| 0x306f2    | 1         | 0.81%   |
| 0x20655    | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 16        | 12.9%   |
| KabyLake         | 11        | 8.87%   |
| Skylake          | 10        | 8.06%   |
| SandyBridge      | 9         | 7.26%   |
| Zen 3            | 8         | 6.45%   |
| IvyBridge        | 8         | 6.45%   |
| Zen 2            | 7         | 5.65%   |
| TigerLake        | 7         | 5.65%   |
| Alderlake Hybrid | 7         | 5.65%   |
| CometLake        | 6         | 4.84%   |
| Unknown          | 5         | 4.03%   |
| Zen+             | 4         | 3.23%   |
| Piledriver       | 4         | 3.23%   |
| Penryn           | 4         | 3.23%   |
| Westmere         | 3         | 2.42%   |
| Goldmont plus    | 3         | 2.42%   |
| Zen              | 2         | 1.61%   |
| Nehalem          | 2         | 1.61%   |
| K10              | 2         | 1.61%   |
| Icelake          | 2         | 1.61%   |
| Broadwell        | 2         | 1.61%   |
| Excavator        | 1         | 0.81%   |
| Core             | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 62        | 40.79%  |
| Nvidia                     | 51        | 33.55%  |
| AMD                        | 28        | 18.42%  |
| Matrox Electronics Systems | 6         | 3.95%   |
| ASPEED Technology          | 5         | 3.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 4.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 3.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 3.25%   |
| ASPEED Technology ASPEED Graphics Family                                    | 5         | 3.25%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4         | 2.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.6%    |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 1.95%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3         | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.95%   |
| Intel UHD Graphics 620                                                      | 3         | 1.95%   |
| Intel HD Graphics 530                                                       | 3         | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.95%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.95%   |
| AMD Renoir                                                                  | 3         | 1.95%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 1.3%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.3%    |
| Nvidia GP107GL [Quadro P400]                                                | 2         | 1.3%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.3%    |
| Matrox Electronics Systems G200eR2                                          | 2         | 1.3%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 1.3%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 1.3%    |
| AMD Rembrandt [Radeon 680M]                                                 | 2         | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.3%    |
| AMD Lucienne                                                                | 2         | 1.3%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.3%    |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.65%   |
| Nvidia TU117GL [T600]                                                       | 1         | 0.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 41        | 33.06%  |
| 1 x Nvidia      | 26        | 20.97%  |
| 1 x AMD         | 19        | 15.32%  |
| Intel + Nvidia  | 18        | 14.52%  |
| 1 x Matrox      | 5         | 4.03%   |
| AMD + Nvidia    | 4         | 3.23%   |
| 1 x ASPEED      | 3         | 2.42%   |
| 2 x AMD         | 2         | 1.61%   |
| Intel + AMD     | 2         | 1.61%   |
| Other           | 1         | 0.81%   |
| Nvidia + Matrox | 1         | 0.81%   |
| Nvidia + ASPEED | 1         | 0.81%   |
| AMD + ASPEED    | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 98        | 79.03%  |
| Proprietary | 19        | 15.32%  |
| Unknown     | 7         | 5.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 50.4%   |
| 0.01-0.5   | 17        | 13.6%   |
| 1.01-2.0   | 16        | 12.8%   |
| 3.01-4.0   | 11        | 8.8%    |
| 0.51-1.0   | 8         | 6.4%    |
| 7.01-8.0   | 3         | 2.4%    |
| 5.01-6.0   | 3         | 2.4%    |
| 8.01-16.0  | 2         | 1.6%    |
| 32.01-64.0 | 1         | 0.8%    |
| 2.01-3.0   | 1         | 0.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 17        | 13.08%  |
| Samsung Electronics  | 13        | 10%     |
| LG Display           | 12        | 9.23%   |
| BOE                  | 10        | 7.69%   |
| AU Optronics         | 10        | 7.69%   |
| Goldstar             | 7         | 5.38%   |
| Chimei Innolux       | 7         | 5.38%   |
| Acer                 | 6         | 4.62%   |
| Philips              | 5         | 3.85%   |
| BenQ                 | 4         | 3.08%   |
| AOC                  | 4         | 3.08%   |
| Ancor Communications | 4         | 3.08%   |
| Sharp                | 3         | 2.31%   |
| Iiyama               | 3         | 2.31%   |
| Hewlett-Packard      | 3         | 2.31%   |
| ViewSonic            | 2         | 1.54%   |
| SGT                  | 2         | 1.54%   |
| InfoVision           | 2         | 1.54%   |
| ASUSTek Computer     | 2         | 1.54%   |
| Vizio                | 1         | 0.77%   |
| Sony                 | 1         | 0.77%   |
| Sceptre Tech         | 1         | 0.77%   |
| PANDA                | 1         | 0.77%   |
| Panasonic            | 1         | 0.77%   |
| OEM                  | 1         | 0.77%   |
| NEC Computers        | 1         | 0.77%   |
| Lenovo               | 1         | 0.77%   |
| IBM                  | 1         | 0.77%   |
| HUAWEI               | 1         | 0.77%   |
| HCL                  | 1         | 0.77%   |
| Gigabyte Technology  | 1         | 0.77%   |
| Eizo                 | 1         | 0.77%   |
| ADR                  | 1         | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                   | 2         | 1.49%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.49%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.75%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch            | 1         | 0.75%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1         | 0.75%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1         | 0.75%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.75%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.75%   |
| Sharp LCD Monitor SHP1491 3840x2160 346x194mm 15.6-inch               | 1         | 0.75%   |
| SGT HS160PC SGT1600 1920x1080 354x199mm 16.0-inch                     | 1         | 0.75%   |
| SGT HS156PC SGT1560 1920x1080 345x194mm 15.6-inch                     | 1         | 0.75%   |
| Sceptre Tech X240-CNC SPT0978 1920x1080 880x490mm 39.7-inch           | 1         | 0.75%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 0.75%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1         | 0.75%   |
| Samsung Electronics S24F350 SAM0D22 1920x1080 521x293mm 23.5-inch     | 1         | 0.75%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.75%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 698x393mm 31.5-inch    | 1         | 0.75%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 0.75%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 0.75%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.75%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch              | 1         | 0.75%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.75%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 0.75%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 0.75%   |
| Philips 32 LCD TV PHL4650 1280x1024 760x450mm 34.8-inch               | 1         | 0.75%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.75%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 1         | 0.75%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 0.75%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1         | 0.75%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 46.34%  |
| 1366x768 (WXGA)    | 10        | 8.13%   |
| 2560x1440 (QHD)    | 8         | 6.5%    |
| 3840x2160 (4K)     | 7         | 5.69%   |
| 1280x1024 (SXGA)   | 7         | 5.69%   |
| 3440x1440          | 5         | 4.07%   |
| 1920x1200 (WUXGA)  | 5         | 4.07%   |
| 1600x900 (HD+)     | 5         | 4.07%   |
| 3840x1080          | 3         | 2.44%   |
| 1680x1050 (WSXGA+) | 3         | 2.44%   |
| 2560x1080          | 2         | 1.63%   |
| 1920x540           | 2         | 1.63%   |
| 1440x900 (WXGA+)   | 2         | 1.63%   |
| Unknown            | 2         | 1.63%   |
| 3840x2400          | 1         | 0.81%   |
| 2240x1400          | 1         | 0.81%   |
| 2160x1440          | 1         | 0.81%   |
| 1280x768           | 1         | 0.81%   |
| 1024x768 (XGA)     | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 20.93%  |
| 14      | 15        | 11.63%  |
| 27      | 14        | 10.85%  |
| 24      | 14        | 10.85%  |
| 17      | 9         | 6.98%   |
| 34      | 7         | 5.43%   |
| 23      | 6         | 4.65%   |
| 21      | 6         | 4.65%   |
| 13      | 6         | 4.65%   |
| 31      | 5         | 3.88%   |
| 19      | 5         | 3.88%   |
| 22      | 2         | 1.55%   |
| 20      | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |
| 65      | 1         | 0.78%   |
| 49      | 1         | 0.78%   |
| 48      | 1         | 0.78%   |
| 40      | 1         | 0.78%   |
| 39      | 1         | 0.78%   |
| 28      | 1         | 0.78%   |
| 25      | 1         | 0.78%   |
| 18      | 1         | 0.78%   |
| 16      | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 37.5%   |
| 501-600     | 33        | 25.78%  |
| 401-500     | 15        | 11.72%  |
| 351-400     | 8         | 6.25%   |
| 701-800     | 7         | 5.47%   |
| 601-700     | 6         | 4.69%   |
| 201-300     | 4         | 3.13%   |
| 1001-1500   | 3         | 2.34%   |
| 801-900     | 2         | 1.56%   |
| Unknown     | 2         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 73.91%  |
| 16/10   | 10        | 8.7%    |
| 5/4     | 7         | 6.09%   |
| 21/9    | 6         | 5.22%   |
| 3/2     | 3         | 2.61%   |
| 32/9    | 2         | 1.74%   |
| 4/3     | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 22.05%  |
| 201-250        | 23        | 18.11%  |
| 81-90          | 19        | 14.96%  |
| 301-350        | 14        | 11.02%  |
| 351-500        | 12        | 9.45%   |
| 151-200        | 8         | 6.3%    |
| 141-150        | 5         | 3.94%   |
| 121-130        | 5         | 3.94%   |
| 501-1000       | 5         | 3.94%   |
| 251-300        | 3         | 2.36%   |
| Unknown        | 2         | 1.57%   |
| More than 1000 | 1         | 0.79%   |
| 71-80          | 1         | 0.79%   |
| 91-100         | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 52        | 40.94%  |
| 121-160       | 38        | 29.92%  |
| 101-120       | 22        | 17.32%  |
| 161-240       | 7         | 5.51%   |
| More than 240 | 4         | 3.15%   |
| 1-50          | 2         | 1.57%   |
| Unknown       | 2         | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 81        | 65.32%  |
| 2     | 20        | 16.13%  |
| 0     | 19        | 15.32%  |
| 3     | 3         | 2.42%   |
| 4     | 1         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 79        | 44.13%  |
| Realtek Semiconductor     | 52        | 29.05%  |
| Broadcom                  | 9         | 5.03%   |
| Qualcomm Atheros          | 8         | 4.47%   |
| MediaTek                  | 7         | 3.91%   |
| Mellanox Technologies     | 3         | 1.68%   |
| Broadcom Limited          | 3         | 1.68%   |
| Ralink Technology         | 2         | 1.12%   |
| Marvell Technology Group  | 2         | 1.12%   |
| Linksys                   | 2         | 1.12%   |
| TP-Link                   | 1         | 0.56%   |
| Solarflare Communications | 1         | 0.56%   |
| Ralink                    | 1         | 0.56%   |
| Qualcomm                  | 1         | 0.56%   |
| Microsoft                 | 1         | 0.56%   |
| Lenovo                    | 1         | 0.56%   |
| JMicron Technology        | 1         | 0.56%   |
| Dell                      | 1         | 0.56%   |
| D-Link                    | 1         | 0.56%   |
| BUFFALO                   | 1         | 0.56%   |
| Aquantia                  | 1         | 0.56%   |
| American Megatrends       | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 36        | 16.98%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 7         | 3.3%    |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 7         | 3.3%    |
| Intel Wireless 7260                                                                                                    | 6         | 2.83%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6         | 2.83%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 5         | 2.36%   |
| Intel Ethernet Controller I225-V                                                                                       | 5         | 2.36%   |
| Intel I211 Gigabit Network Connection                                                                                  | 4         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 3         | 1.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 3         | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 1.42%   |
| Intel Wireless 8265 / 8275                                                                                             | 3         | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 3         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 3         | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 3         | 1.42%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 1.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 2         | 0.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 2         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 2         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 2         | 0.94%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 0.94%   |
| Intel Wireless 8260                                                                                                    | 2         | 0.94%   |
| Intel Wireless 7265                                                                                                    | 2         | 0.94%   |
| Intel Wireless 3165                                                                                                    | 2         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                                 | 2         | 0.94%   |
| Intel I210 Gigabit Network Connection                                                                                  | 2         | 0.94%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 0.94%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                                                                                   | 2         | 0.94%   |
| Intel Ethernet Connection (17) I219-V                                                                                  | 2         | 0.94%   |
| Intel Ethernet Connection (14) I219-V                                                                                  | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 2         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 2         | 0.94%   |
| Intel 82574L Gigabit Network Connection                                                                                | 2         | 0.94%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                                                | 2         | 0.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 58.44%  |
| Realtek Semiconductor | 7         | 9.09%   |
| Qualcomm Atheros      | 7         | 9.09%   |
| MediaTek              | 7         | 9.09%   |
| Ralink Technology     | 2         | 2.6%    |
| Linksys               | 2         | 2.6%    |
| TP-Link               | 1         | 1.3%    |
| Ralink                | 1         | 1.3%    |
| Microsoft             | 1         | 1.3%    |
| Dell                  | 1         | 1.3%    |
| BUFFALO               | 1         | 1.3%    |
| Broadcom Limited      | 1         | 1.3%    |
| Broadcom              | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                                                | 6         | 7.59%   |
| Intel Wi-Fi 6 AX200                                                                                                | 6         | 7.59%   |
| Intel Wi-Fi 6 AX201                                                                                                | 5         | 6.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                            | 3         | 3.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 3.8%    |
| Intel Wireless 8265 / 8275                                                                                         | 3         | 3.8%    |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 3         | 3.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 3         | 3.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 3         | 3.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                 | 2         | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 2         | 2.53%   |
| Ralink MT7601U Wireless Adapter                                                                                    | 2         | 2.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 2.53%   |
| Intel Wireless 8260                                                                                                | 2         | 2.53%   |
| Intel Wireless 7265                                                                                                | 2         | 2.53%   |
| Intel Wireless 3165                                                                                                | 2         | 2.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                             | 2         | 2.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 2         | 2.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 2.53%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                                | 1         | 1.27%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                            | 1         | 1.27%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 1.27%   |
| Realtek 802.11ac NIC                                                                                               | 1         | 1.27%   |
| Ralink RT3071 Wireless Adapter                                                                                     | 1         | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                   | 1         | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                   | 1         | 1.27%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                | 1         | 1.27%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter                                                           | 1         | 1.27%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                | 1         | 1.27%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                                     | 1         | 1.27%   |
| Intel Wireless 3160                                                                                                | 1         | 1.27%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.27%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.27%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.27%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                                                           | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 54        | 43.2%   |
| Realtek Semiconductor     | 49        | 39.2%   |
| Broadcom                  | 9         | 7.2%    |
| Marvell Technology Group  | 2         | 1.6%    |
| Broadcom Limited          | 2         | 1.6%    |
| Solarflare Communications | 1         | 0.8%    |
| Qualcomm Atheros          | 1         | 0.8%    |
| Qualcomm                  | 1         | 0.8%    |
| Mellanox Technologies     | 1         | 0.8%    |
| Lenovo                    | 1         | 0.8%    |
| JMicron Technology        | 1         | 0.8%    |
| D-Link                    | 1         | 0.8%    |
| Aquantia                  | 1         | 0.8%    |
| American Megatrends       | 1         | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 27.48%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 5.34%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 5.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 5.34%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.82%   |
| Intel I211 Gigabit Network Connection                             | 4         | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.29%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.53%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.53%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 1.53%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.53%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.53%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 1.53%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.53%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.53%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 2         | 1.53%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.76%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.76%   |
| Mellanox MT27700 Family [ConnectX-4]                              | 1         | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.76%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.76%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.76%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.76%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.76%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.76%   |
| Intel Ethernet Controller X550                                    | 1         | 0.76%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.76%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.76%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.76%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.76%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 59.46%  |
| WiFi     | 73        | 39.46%  |
| Unknown  | 2         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 80        | 62.02%  |
| WiFi     | 49        | 37.98%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 55        | 44.35%  |
| 1     | 53        | 42.74%  |
| 3     | 7         | 5.65%   |
| 5     | 3         | 2.42%   |
| 4     | 2         | 1.61%   |
| 0     | 2         | 1.61%   |
| 66    | 1         | 0.81%   |
| 8     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 77.42%  |
| Yes  | 28        | 22.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 59.68%  |
| Qualcomm Atheros Communications | 4         | 6.45%   |
| Foxconn / Hon Hai               | 4         | 6.45%   |
| Realtek Semiconductor           | 3         | 4.84%   |
| MediaTek                        | 3         | 4.84%   |
| Cambridge Silicon Radio         | 3         | 4.84%   |
| IMC Networks                    | 2         | 3.23%   |
| Broadcom                        | 2         | 3.23%   |
| Ralink                          | 1         | 1.61%   |
| Integrated System Solution      | 1         | 1.61%   |
| Hewlett-Packard                 | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 15        | 24.19%  |
| Intel AX201 Bluetooth                                 | 10        | 16.13%  |
| Intel AX200 Bluetooth                                 | 6         | 9.68%   |
| Foxconn / Hon Hai Wireless_Device                     | 4         | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 4.84%   |
| MediaTek Wireless_Device                              | 3         | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3         | 4.84%   |
| Realtek Bluetooth Radio                               | 2         | 3.23%   |
| Intel Bluetooth Device                                | 2         | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.61%   |
| Ralink RT3290 Bluetooth                               | 1         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 1.61%   |
| Intel AX210 Bluetooth                                 | 1         | 1.61%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.61%   |
| IMC Networks Wireless_Device                          | 1         | 1.61%   |
| IMC Networks Bluetooth Device                         | 1         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.61%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 79        | 45.66%  |
| Nvidia              | 40        | 23.12%  |
| AMD                 | 34        | 19.65%  |
| C-Media Electronics | 4         | 2.31%   |
| Logitech            | 3         | 1.73%   |
| GN Netcom           | 2         | 1.16%   |
| Creative Technology | 2         | 1.16%   |
| Conexant Systems    | 2         | 1.16%   |
| Setek Elektronik    | 1         | 0.58%   |
| Saitek              | 1         | 0.58%   |
| Nektar              | 1         | 0.58%   |
| Huawei Technologies | 1         | 0.58%   |
| Hewlett-Packard     | 1         | 0.58%   |
| GYROCOM C&C         | 1         | 0.58%   |
| ASUSTek Computer    | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 15        | 7.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12        | 5.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 10        | 4.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9         | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8         | 3.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 7         | 3.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 2.48%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 2.48%   |
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 2.48%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5         | 2.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4         | 1.98%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4         | 1.98%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 1.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4         | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 1.49%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3         | 1.49%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3         | 1.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 3         | 1.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3         | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 0.99%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 0.99%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 0.99%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 0.99%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2         | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 0.99%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.99%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.99%   |
| C-Media Electronics USB PnP Audio Device                                          | 2         | 0.99%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2         | 0.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 0.99%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 21.51%  |
| Micron Technology   | 14        | 15.05%  |
| SK hynix            | 11        | 11.83%  |
| Kingston            | 8         | 8.6%    |
| Corsair             | 8         | 8.6%    |
| Unknown             | 6         | 6.45%   |
| G.Skill             | 6         | 6.45%   |
| Crucial             | 6         | 6.45%   |
| A-DATA Technology   | 2         | 2.15%   |
| Unknown (ABCD)      | 1         | 1.08%   |
| Team                | 1         | 1.08%   |
| Smart               | 1         | 1.08%   |
| Ramaxel Technology  | 1         | 1.08%   |
| PNY                 | 1         | 1.08%   |
| Patriot             | 1         | 1.08%   |
| Magnum Tech         | 1         | 1.08%   |
| Lexar Co Limited    | 1         | 1.08%   |
| Lexar               | 1         | 1.08%   |
| Hewlett-Packard     | 1         | 1.08%   |
| Gold Key            | 1         | 1.08%   |
| Unknown             | 1         | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 2.08%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                        | 1         | 1.04%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.04%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.04%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 1.04%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.04%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 1.04%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.04%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 1.04%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT325U7EFR8A-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.04%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.04%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.04%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.04%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.04%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s             | 1         | 1.04%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 1.04%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 1.04%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.04%   |
| Samsung RAM M393A4K40BB2-CTD 32GB DIMM DDR4 2666MT/s             | 1         | 1.04%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s              | 1         | 1.04%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 1.04%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.04%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s             | 1         | 1.04%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 57.83%  |
| DDR3    | 24        | 28.92%  |
| LPDDR4  | 3         | 3.61%   |
| DDR5    | 3         | 3.61%   |
| DDR2    | 3         | 3.61%   |
| LPDDR5  | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 44        | 52.38%  |
| SODIMM       | 34        | 40.48%  |
| Row Of Chips | 5         | 5.95%   |
| RIMM         | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 39        | 44.32%  |
| 16384 | 15        | 17.05%  |
| 4096  | 12        | 13.64%  |
| 32768 | 11        | 12.5%   |
| 1024  | 6         | 6.82%   |
| 2048  | 5         | 5.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 21        | 23.6%   |
| 2667  | 12        | 13.48%  |
| 1600  | 12        | 13.48%  |
| 2400  | 7         | 7.87%   |
| 1333  | 5         | 5.62%   |
| 2133  | 4         | 4.49%   |
| 4800  | 3         | 3.37%   |
| 2666  | 3         | 3.37%   |
| 667   | 3         | 3.37%   |
| 1066  | 2         | 2.25%   |
| 6400  | 1         | 1.12%   |
| 4267  | 1         | 1.12%   |
| 4266  | 1         | 1.12%   |
| 3733  | 1         | 1.12%   |
| 3666  | 1         | 1.12%   |
| 3600  | 1         | 1.12%   |
| 3534  | 1         | 1.12%   |
| 3400  | 1         | 1.12%   |
| 3333  | 1         | 1.12%   |
| 3266  | 1         | 1.12%   |
| 3100  | 1         | 1.12%   |
| 3000  | 1         | 1.12%   |
| 2800  | 1         | 1.12%   |
| 2200  | 1         | 1.12%   |
| 2048  | 1         | 1.12%   |
| 1866  | 1         | 1.12%   |
| 1800  | 1         | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series    | 1         | 33.33%  |
| Seiko Epson Printer           | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP OfficeJet 6110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 18.18%  |
| IMC Networks                           | 8         | 14.55%  |
| Microdia                               | 5         | 9.09%   |
| Syntek                                 | 4         | 7.27%   |
| Logitech                               | 4         | 7.27%   |
| Sunplus Innovation Technology          | 3         | 5.45%   |
| Realtek Semiconductor                  | 3         | 5.45%   |
| Luxvisions Innotech Limited            | 3         | 5.45%   |
| Generalplus Technology                 | 2         | 3.64%   |
| Bison Electronics                      | 2         | 3.64%   |
| webcam                                 | 1         | 1.82%   |
| Suyin                                  | 1         | 1.82%   |
| Quanta                                 | 1         | 1.82%   |
| Lite-On Technology                     | 1         | 1.82%   |
| Lenovo                                 | 1         | 1.82%   |
| KYE Systems (Mouse Systems)            | 1         | 1.82%   |
| Intel                                  | 1         | 1.82%   |
| Huawei Technologies                    | 1         | 1.82%   |
| Elgato Systems                         | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.82%   |
| Apple                                  | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 6         | 10.91%  |
| Microdia Integrated_Webcam_HD                                              | 4         | 7.27%   |
| IMC Networks Integrated Camera                                             | 3         | 5.45%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.64%   |
| Syntek Integrated Camera                                                   | 2         | 3.64%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.64%   |
| Logitech HD Pro Webcam C920                                                | 2         | 3.64%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 3.64%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 3.64%   |
| Chicony HP HD Camera                                                       | 2         | 3.64%   |
| webcam webcam                                                              | 1         | 1.82%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 1.82%   |
| Sunplus WEMISS CM-A1                                                       | 1         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.82%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.82%   |
| Realtek EasyCamera                                                         | 1         | 1.82%   |
| Quanta HP Webcam                                                           | 1         | 1.82%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.82%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.82%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.82%   |
| Logitech Webcam C270                                                       | 1         | 1.82%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 1.82%   |
| Lite-On HP HD Webcam                                                       | 1         | 1.82%   |
| Lenovo UVC Camera                                                          | 1         | 1.82%   |
| KYE Systems (Mouse Systems) PC-W3 Camera                                   | 1         | 1.82%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 1.82%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 1.82%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.82%   |
| IMC Networks HD Camera                                                     | 1         | 1.82%   |
| Huawei UVC Camera                                                          | 1         | 1.82%   |
| Elgato Systems Elgato Facecam                                              | 1         | 1.82%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.82%   |
| Chicony HD WebCam                                                          | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.82%   |
| Bison Integrated RGB Camera                                                | 1         | 1.82%   |
| Bison Integrated Camera                                                    | 1         | 1.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 31.58%  |
| Synaptics                  | 6         | 31.58%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| LighTuning Technology      | 3         | 15.79%  |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 10.53%  |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 10.53%  |
| LighTuning Fingerprint Sensor                                              | 2         | 10.53%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics WBDI                                                             | 1         | 5.26%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 5.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 5.26%   |
| AuthenTec AES2810                                                          | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 20%     |
| Broadcom 58200                                                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 69        | 55.65%  |
| 1     | 40        | 32.26%  |
| 2     | 10        | 8.06%   |
| 5     | 2         | 1.61%   |
| 3     | 2         | 1.61%   |
| 4     | 1         | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 26.39%  |
| Graphics card            | 14        | 19.44%  |
| Net/wireless             | 9         | 12.5%   |
| Unassigned class         | 7         | 9.72%   |
| Communication controller | 6         | 8.33%   |
| Net/ethernet             | 3         | 4.17%   |
| Chipcard                 | 3         | 4.17%   |
| Network                  | 2         | 2.78%   |
| Multimedia controller    | 2         | 2.78%   |
| Storage/raid             | 1         | 1.39%   |
| Storage                  | 1         | 1.39%   |
| Sound                    | 1         | 1.39%   |
| Firewire controller      | 1         | 1.39%   |
| Dvb card                 | 1         | 1.39%   |
| Card reader              | 1         | 1.39%   |
| Bluetooth                | 1         | 1.39%   |

