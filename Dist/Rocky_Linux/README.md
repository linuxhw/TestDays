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

Total: 167

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 06D7TR A00                  | Desktop     | [6fe7179a50](https://linux-hardware.org/?probe=6fe7179a50) | May 01, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [5f765d4d9c](https://linux-hardware.org/?probe=5f765d4d9c) | Apr 29, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [62a4a8b0b5](https://linux-hardware.org/?probe=62a4a8b0b5) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
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
| Rocky Linux 9.1 | 37        | 28.91%  |
| Rocky Linux 8.5 | 31        | 24.22%  |
| Rocky Linux 9.0 | 19        | 14.84%  |
| Rocky Linux 8.4 | 19        | 14.84%  |
| Rocky Linux 8.6 | 11        | 8.59%   |
| Rocky Linux 8.7 | 9         | 7.03%   |
| Rocky Linux 8.3 | 2         | 1.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 126       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 17        | 12.78%  |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 9.77%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 6.02%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 7         | 5.26%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 4.51%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 5         | 3.76%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 3.76%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 5         | 3.76%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 3.01%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 3.01%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 3.01%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 3         | 2.26%   |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 2.26%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 3         | 2.26%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 3         | 2.26%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 3         | 2.26%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 2.26%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 2         | 1.5%    |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 2         | 1.5%    |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 1.5%    |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 1.5%    |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 1.5%    |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 1.5%    |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 1.5%    |
| 4.18.0-305.el8.x86_64            | 2         | 1.5%    |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 1.5%    |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 1.5%    |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 1.5%    |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 1.5%    |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 0.75%   |
| 6.1.8-1.el9.elrepo.x86_64        | 1         | 0.75%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1         | 0.75%   |
| 6.0.10_tkg_bmq                   | 1         | 0.75%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1         | 0.75%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 0.75%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 0.75%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 0.75%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 0.75%   |
| 5.10.89-1.el8.x86_64             | 1         | 0.75%   |
| 5.10.52-v8.1.el8                 | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 65        | 51.18%  |
| 5.14.0  | 52        | 40.94%  |
| 6.0.10  | 2         | 1.57%   |
| 6.2.12  | 1         | 0.79%   |
| 6.1.8   | 1         | 0.79%   |
| 6.1.6   | 1         | 0.79%   |
| 5.4.157 | 1         | 0.79%   |
| 5.16.15 | 1         | 0.79%   |
| 5.14.1  | 1         | 0.79%   |
| 5.10.89 | 1         | 0.79%   |
| 5.10.52 | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 65        | 51.18%  |
| 5.14    | 53        | 41.73%  |
| 6.1     | 2         | 1.57%   |
| 6.0     | 2         | 1.57%   |
| 5.10    | 2         | 1.57%   |
| 6.2     | 1         | 0.79%   |
| 5.4     | 1         | 0.79%   |
| 5.16    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 125       | 99.21%  |
| aarch64 | 1         | 0.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 87        | 69.05%  |
| Unknown       | 17        | 13.49%  |
| KDE5          | 9         | 7.14%   |
| MATE          | 5         | 3.97%   |
| GNOME Classic | 4         | 3.17%   |
| XFCE          | 3         | 2.38%   |
| X-Cinnamon    | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 71        | 55.04%  |
| X11     | 40        | 31.01%  |
| Tty     | 8         | 6.2%    |
| Unknown | 7         | 5.43%   |
| Web     | 3         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 57        | 45.24%  |
| Unknown | 57        | 45.24%  |
| SDDM    | 8         | 6.35%   |
| LightDM | 4         | 3.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 80        | 63.49%  |
| ru_RU   | 6         | 4.76%   |
| en_CA   | 5         | 3.97%   |
| en_AU   | 5         | 3.97%   |
| en_IL   | 3         | 2.38%   |
| C       | 3         | 2.38%   |
| Unknown | 3         | 2.38%   |
| en_ZA   | 2         | 1.59%   |
| en_SG   | 2         | 1.59%   |
| de_DE   | 2         | 1.59%   |
| de_AT   | 2         | 1.59%   |
| pt_BR   | 1         | 0.79%   |
| pl_PL   | 1         | 0.79%   |
| ko_KR   | 1         | 0.79%   |
| ja_JP   | 1         | 0.79%   |
| it_IT   | 1         | 0.79%   |
| hu_HU   | 1         | 0.79%   |
| fr_FR   | 1         | 0.79%   |
| es_ES   | 1         | 0.79%   |
| es_CO   | 1         | 0.79%   |
| es_AR   | 1         | 0.79%   |
| en_IE   | 1         | 0.79%   |
| en_GB   | 1         | 0.79%   |
| af_ZA   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 82        | 64.57%  |
| BIOS | 45        | 35.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 104       | 82.54%  |
| Ext4 | 21        | 16.67%  |
| Ext3 | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 65        | 51.59%  |
| Unknown | 40        | 31.75%  |
| MBR     | 21        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 80.95%  |
| Yes       | 24        | 19.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 84.13%  |
| Yes       | 20        | 15.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 27        | 21.43%  |
| Lenovo                  | 23        | 18.25%  |
| ASUSTek Computer        | 19        | 15.08%  |
| Hewlett-Packard         | 18        | 14.29%  |
| MSI                     | 7         | 5.56%   |
| Gigabyte Technology     | 7         | 5.56%   |
| Intel                   | 3         | 2.38%   |
| AZW                     | 3         | 2.38%   |
| Unknown                 | 3         | 2.38%   |
| Toshiba                 | 2         | 1.59%   |
| Supermicro              | 2         | 1.59%   |
| ASRock                  | 2         | 1.59%   |
| Sapphire                | 1         | 0.79%   |
| Raspberry Pi Foundation | 1         | 0.79%   |
| Positivo                | 1         | 0.79%   |
| NCR                     | 1         | 0.79%   |
| IBM                     | 1         | 0.79%   |
| HUAWEI                  | 1         | 0.79%   |
| Google                  | 1         | 0.79%   |
| BESSTAR Tech            | 1         | 0.79%   |
| BANGHO                  | 1         | 0.79%   |
| Acer                    | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 2.38%   |
| Dell PowerEdge R610                    | 2         | 1.59%   |
| Dell OptiPlex 9020                     | 2         | 1.59%   |
| AZW GTR                                | 2         | 1.59%   |
| Toshiba TECRA W50-A                    | 1         | 0.79%   |
| Toshiba Satellite E45-B                | 1         | 0.79%   |
| Supermicro SYS-5029P-WTR               | 1         | 0.79%   |
| Supermicro Super Server                | 1         | 0.79%   |
| Sapphire PE-AM2RS690V2                 | 1         | 0.79%   |
| RPi Raspberry Pi                       | 1         | 0.79%   |
| Positivo Mobile                        | 1         | 0.79%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 0.79%   |
| MSI MS-7D46                            | 1         | 0.79%   |
| MSI MS-7D25                            | 1         | 0.79%   |
| MSI MS-7B89                            | 1         | 0.79%   |
| MSI MS-7B78                            | 1         | 0.79%   |
| MSI MS-7A94                            | 1         | 0.79%   |
| MSI MS-7917                            | 1         | 0.79%   |
| MSI H510M PRO-E                        | 1         | 0.79%   |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 0.79%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 0.79%   |
| Lenovo ThinkPad W500 406132G           | 1         | 0.79%   |
| Lenovo ThinkPad T480 20L6S8B500        | 1         | 0.79%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 0.79%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 0.79%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 0.79%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 0.79%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK    | 1         | 0.79%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB   | 1         | 0.79%   |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 0.79%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 0.79%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.79%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 0.79%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.79%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 0.79%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 0.79%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 0.79%   |
| Lenovo IdeaPad S210 Touch 20257        | 1         | 0.79%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 10        | 7.94%   |
| ASUS PRIME               | 9         | 7.14%   |
| Lenovo IdeaPad           | 7         | 5.56%   |
| Dell Precision           | 5         | 3.97%   |
| Dell PowerEdge           | 5         | 3.97%   |
| Dell OptiPlex            | 5         | 3.97%   |
| Dell Latitude            | 4         | 3.17%   |
| HP ZBook                 | 3         | 2.38%   |
| HP EliteBook             | 3         | 2.38%   |
| Dell XPS                 | 3         | 2.38%   |
| Dell Inspiron            | 3         | 2.38%   |
| Unknown                  | 3         | 2.38%   |
| Lenovo Legion            | 2         | 1.59%   |
| Lenovo IdeaPadFlex       | 2         | 1.59%   |
| HP ProLiant              | 2         | 1.59%   |
| HP Laptop                | 2         | 1.59%   |
| HP EliteDesk             | 2         | 1.59%   |
| Dell Vostro              | 2         | 1.59%   |
| AZW GTR                  | 2         | 1.59%   |
| ASUS ROG                 | 2         | 1.59%   |
| ASUS ASUS                | 2         | 1.59%   |
| Toshiba TECRA            | 1         | 0.79%   |
| Toshiba Satellite        | 1         | 0.79%   |
| Supermicro SYS-5029P-WTR | 1         | 0.79%   |
| Supermicro Super         | 1         | 0.79%   |
| Sapphire PE-AM2RS690V2   | 1         | 0.79%   |
| RPi Raspberry            | 1         | 0.79%   |
| Positivo Mobile          | 1         | 0.79%   |
| NCR xxxx-xxxx-xxxx       | 1         | 0.79%   |
| MSI MS-7D46              | 1         | 0.79%   |
| MSI MS-7D25              | 1         | 0.79%   |
| MSI MS-7B89              | 1         | 0.79%   |
| MSI MS-7B78              | 1         | 0.79%   |
| MSI MS-7A94              | 1         | 0.79%   |
| MSI MS-7917              | 1         | 0.79%   |
| MSI H510M                | 1         | 0.79%   |
| Lenovo ThinkStation      | 1         | 0.79%   |
| Lenovo ThinkCentre       | 1         | 0.79%   |
| Intel S2600WFT           | 1         | 0.79%   |
| Intel PRO412081          | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 21        | 16.67%  |
| 2020    | 16        | 12.7%   |
| 2018    | 15        | 11.9%   |
| 2022    | 11        | 8.73%   |
| 2019    | 10        | 7.94%   |
| 2011    | 10        | 7.94%   |
| 2013    | 9         | 7.14%   |
| 2014    | 8         | 6.35%   |
| 2015    | 7         | 5.56%   |
| 2012    | 5         | 3.97%   |
| 2010    | 4         | 3.17%   |
| 2008    | 3         | 2.38%   |
| 2017    | 2         | 1.59%   |
| 2016    | 2         | 1.59%   |
| 2009    | 2         | 1.59%   |
| Unknown | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 56        | 44.44%  |
| Notebook       | 49        | 38.89%  |
| Server         | 12        | 9.52%   |
| Mini pc        | 4         | 3.17%   |
| Convertible    | 3         | 2.38%   |
| System on chip | 1         | 0.79%   |
| Tablet         | 1         | 0.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 112       | 88.89%  |
| Enabled  | 14        | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 125       | 99.21%  |
| Yes  | 1         | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 33        | 25.98%  |
| 4.01-8.0        | 24        | 18.9%   |
| 32.01-64.0      | 24        | 18.9%   |
| 16.01-24.0      | 16        | 12.6%   |
| 64.01-256.0     | 10        | 7.87%   |
| 3.01-4.0        | 7         | 5.51%   |
| More than 256.0 | 4         | 3.15%   |
| 1.01-2.0        | 4         | 3.15%   |
| 24.01-32.0      | 3         | 2.36%   |
| 2.01-3.0        | 2         | 1.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 36        | 27.07%  |
| 4.01-8.0   | 30        | 22.56%  |
| 3.01-4.0   | 26        | 19.55%  |
| 1.01-2.0   | 20        | 15.04%  |
| 8.01-16.0  | 8         | 6.02%   |
| 0.51-1.0   | 6         | 4.51%   |
| 32.01-64.0 | 2         | 1.5%    |
| 16.01-24.0 | 2         | 1.5%    |
| 0.01-0.5   | 2         | 1.5%    |
| 24.01-32.0 | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 56.69%  |
| 2      | 23        | 18.11%  |
| 3      | 11        | 8.66%   |
| 4      | 9         | 7.09%   |
| 6      | 3         | 2.36%   |
| 5      | 2         | 1.57%   |
| 19     | 1         | 0.79%   |
| 18     | 1         | 0.79%   |
| 17     | 1         | 0.79%   |
| 16     | 1         | 0.79%   |
| 14     | 1         | 0.79%   |
| 9      | 1         | 0.79%   |
| 8      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 71.43%  |
| Yes       | 36        | 28.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 88.98%  |
| No        | 14        | 11.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 59.06%  |
| No        | 52        | 40.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 50.39%  |
| Yes       | 63        | 49.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 34        | 26.98%  |
| Canada       | 8         | 6.35%   |
| Russia       | 7         | 5.56%   |
| Germany      | 6         | 4.76%   |
| Australia    | 6         | 4.76%   |
| Poland       | 4         | 3.17%   |
| Italy        | 4         | 3.17%   |
| Czechia      | 4         | 3.17%   |
| UK           | 3         | 2.38%   |
| South Africa | 3         | 2.38%   |
| Singapore    | 3         | 2.38%   |
| Israel       | 3         | 2.38%   |
| Sweden       | 2         | 1.59%   |
| South Korea  | 2         | 1.59%   |
| Netherlands  | 2         | 1.59%   |
| Mexico       | 2         | 1.59%   |
| Indonesia    | 2         | 1.59%   |
| India        | 2         | 1.59%   |
| Hungary      | 2         | 1.59%   |
| France       | 2         | 1.59%   |
| Brazil       | 2         | 1.59%   |
| Belgium      | 2         | 1.59%   |
| Argentina    | 2         | 1.59%   |
| Uzbekistan   | 1         | 0.79%   |
| UAE          | 1         | 0.79%   |
| Turkey       | 1         | 0.79%   |
| Switzerland  | 1         | 0.79%   |
| Spain        | 1         | 0.79%   |
| Slovakia     | 1         | 0.79%   |
| Saudi Arabia | 1         | 0.79%   |
| Portugal     | 1         | 0.79%   |
| Pakistan     | 1         | 0.79%   |
| Norway       | 1         | 0.79%   |
| Malaysia     | 1         | 0.79%   |
| Kazakhstan   | 1         | 0.79%   |
| Japan        | 1         | 0.79%   |
| Ireland      | 1         | 0.79%   |
| Finland      | 1         | 0.79%   |
| Croatia      | 1         | 0.79%   |
| Colombia     | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 2.36%   |
| Melbourne              | 3         | 2.36%   |
| Toronto                | 2         | 1.57%   |
| Prague                 | 2         | 1.57%   |
| Moscow                 | 2         | 1.57%   |
| Mirfield               | 2         | 1.57%   |
| Krakow                 | 2         | 1.57%   |
| Haifa                  | 2         | 1.57%   |
| Centurion              | 2         | 1.57%   |
| Budapest               | 2         | 1.57%   |
| Berlin                 | 2         | 1.57%   |
| Adelaide               | 2         | 1.57%   |
| Žilina                | 1         | 0.79%   |
| Yogyakarta             | 1         | 0.79%   |
| Yekaterinburg          | 1         | 0.79%   |
| Xi'an                  | 1         | 0.79%   |
| Woodridge              | 1         | 0.79%   |
| Wells                  | 1         | 0.79%   |
| Washington             | 1         | 0.79%   |
| Waltham                | 1         | 0.79%   |
| Voronezh               | 1         | 0.79%   |
| Vienna                 | 1         | 0.79%   |
| Vancouver              | 1         | 0.79%   |
| Urbana                 | 1         | 0.79%   |
| Torrington             | 1         | 0.79%   |
| Tlaxcala City          | 1         | 0.79%   |
| Syracuse               | 1         | 0.79%   |
| St. John's             | 1         | 0.79%   |
| St Petersburg          | 1         | 0.79%   |
| Split                  | 1         | 0.79%   |
| Sobral de Monte Agraco | 1         | 0.79%   |
| Smolensk               | 1         | 0.79%   |
| Senigallia             | 1         | 0.79%   |
| Semarang               | 1         | 0.79%   |
| Scarborough            | 1         | 0.79%   |
| San Miguel de Tucumán | 1         | 0.79%   |
| Rotterdam              | 1         | 0.79%   |
| Riyadh                 | 1         | 0.79%   |
| Rehovot                | 1         | 0.79%   |
| Rawalpindi             | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 34        | 46     | 17.71%  |
| Seagate                     | 28        | 85     | 14.58%  |
| WDC                         | 26        | 53     | 13.54%  |
| Toshiba                     | 14        | 17     | 7.29%   |
| Hitachi                     | 9         | 14     | 4.69%   |
| Intel                       | 8         | 10     | 4.17%   |
| Sandisk                     | 7         | 9      | 3.65%   |
| Kingston                    | 7         | 7      | 3.65%   |
| SK hynix                    | 5         | 7      | 2.6%    |
| Crucial                     | 5         | 6      | 2.6%    |
| Unknown                     | 4         | 4      | 2.08%   |
| Phison                      | 3         | 4      | 1.56%   |
| Micron Technology           | 3         | 3      | 1.56%   |
| HGST                        | 3         | 3      | 1.56%   |
| LITEONIT                    | 2         | 2      | 1.04%   |
| Lexar                       | 2         | 2      | 1.04%   |
| Corsair                     | 2         | 2      | 1.04%   |
| A-DATA Technology           | 2         | 2      | 1.04%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.52%   |
| UMIS                        | 1         | 1      | 0.52%   |
| Team                        | 1         | 1      | 0.52%   |
| StoreJet                    | 1         | 1      | 0.52%   |
| PNY                         | 1         | 1      | 0.52%   |
| Phison Electronics          | 1         | 16     | 0.52%   |
| MyDigitalSSD                | 1         | 1      | 0.52%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.52%   |
| LITEON                      | 1         | 1      | 0.52%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.52%   |
| Kingston Technology Company | 1         | 1      | 0.52%   |
| KingFast                    | 1         | 1      | 0.52%   |
| JMicron Technology          | 1         | 1      | 0.52%   |
| INDMEM                      | 1         | 1      | 0.52%   |
| IBM                         | 1         | 1      | 0.52%   |
| HS-SSD-C100                 | 1         | 1      | 0.52%   |
| Hewlett-Packard             | 1         | 1      | 0.52%   |
| GOODRAM                     | 1         | 1      | 0.52%   |
| Gigabyte Technology         | 1         | 1      | 0.52%   |
| Fujitsu                     | 1         | 1      | 0.52%   |
| Dogfish                     | 1         | 1      | 0.52%   |
| Digma                       | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3         | 1.35%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2         | 0.9%    |
| Unknown MMC Card  64GB           | 2         | 0.9%    |
| Seagate ST9320325AS 320GB        | 2         | 0.9%    |
| Seagate ST300MP0005 304GB        | 2         | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.9%    |
| Samsung SSD 870 EVO 1TB          | 2         | 0.9%    |
| Samsung SSD 860 EVO 1TB          | 2         | 0.9%    |
| Lexar 512GB SSD                  | 2         | 0.9%    |
| Crucial CT1000MX500SSD1 1TB      | 2         | 0.9%    |
| A-DATA SWORDFISH 1TB             | 2         | 0.9%    |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1         | 0.45%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.45%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1         | 0.45%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD   | 1         | 0.45%   |
| WDC WDBNCE0010PNC 1TB SSD        | 1         | 0.45%   |
| WDC WD80EZZX-11CSGA0 8TB         | 1         | 0.45%   |
| WDC WD80EMAZ-00WJTA0 8TB         | 1         | 0.45%   |
| WDC WD80EDAZ-11TA3A0 8TB         | 1         | 0.45%   |
| WDC WD60EFAX-68JH4N1 6TB         | 1         | 0.45%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.45%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 0.45%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 1         | 0.45%   |
| WDC WD5000BPVT-00A1YT0 500GB     | 1         | 0.45%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1         | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 0.45%   |
| WDC WD5000AAKS-402AA0 500GB      | 1         | 0.45%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1         | 0.45%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1         | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.45%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1         | 0.45%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1         | 0.45%   |
| WDC WD20EFZX-68AWUN0 2TB         | 1         | 0.45%   |
| WDC WD2002FAEX-007BA0 2TB        | 1         | 0.45%   |
| WDC WD120EDAZ-11F3RA0 12TB       | 1         | 0.45%   |
| WDC WD10SPCX-24HWST1 1TB         | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 85     | 39.44%  |
| WDC                 | 19        | 40     | 26.76%  |
| Hitachi             | 9         | 14     | 12.68%  |
| Toshiba             | 7         | 9      | 9.86%   |
| Samsung Electronics | 2         | 3      | 2.82%   |
| HGST                | 2         | 2      | 2.82%   |
| Unknown             | 1         | 1      | 1.41%   |
| StoreJet            | 1         | 1      | 1.41%   |
| IBM                 | 1         | 1      | 1.41%   |
| Fujitsu             | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 24.19%  |
| WDC                 | 7         | 10     | 11.29%  |
| Toshiba             | 5         | 5      | 8.06%   |
| SanDisk             | 5         | 6      | 8.06%   |
| Kingston            | 4         | 4      | 6.45%   |
| Crucial             | 4         | 5      | 6.45%   |
| SK hynix            | 2         | 2      | 3.23%   |
| LITEONIT            | 2         | 2      | 3.23%   |
| Intel               | 2         | 3      | 3.23%   |
| Team                | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| MyDigitalSSD        | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| Lexar               | 1         | 1      | 1.61%   |
| KingFast            | 1         | 1      | 1.61%   |
| INDMEM              | 1         | 1      | 1.61%   |
| GOODRAM             | 1         | 1      | 1.61%   |
| Gigabyte Technology | 1         | 1      | 1.61%   |
| Dogfish             | 1         | 1      | 1.61%   |
| Digma               | 1         | 1      | 1.61%   |
| Corsair             | 1         | 1      | 1.61%   |
| China               | 1         | 1      | 1.61%   |
| ASMT                | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |
| ADATA SU            | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 53        | 84     | 32.12%  |
| HDD     | 53        | 157    | 32.12%  |
| SSD     | 52        | 72     | 31.52%  |
| Unknown | 4         | 4      | 2.42%   |
| MMC     | 3         | 3      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 217    | 55.63%  |
| NVMe | 53        | 84     | 35.1%   |
| SAS  | 11        | 16     | 7.28%   |
| MMC  | 3         | 3      | 1.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 89     | 48.25%  |
| 0.51-1.0   | 34        | 74     | 29.82%  |
| 1.01-2.0   | 13        | 22     | 11.4%   |
| 3.01-4.0   | 7         | 26     | 6.14%   |
| 10.01-20.0 | 2         | 3      | 1.75%   |
| 4.01-10.0  | 2         | 14     | 1.75%   |
| 2.01-3.0   | 1         | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 26.56%  |
| 251-500        | 30        | 23.44%  |
| 501-1000       | 20        | 15.63%  |
| 1001-2000      | 16        | 12.5%   |
| More than 3000 | 8         | 6.25%   |
| 2001-3000      | 7         | 5.47%   |
| 51-100         | 7         | 5.47%   |
| Unknown        | 4         | 3.13%   |
| 1-20           | 2         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 36.15%  |
| 21-50          | 28        | 21.54%  |
| 51-100         | 15        | 11.54%  |
| 101-250        | 11        | 8.46%   |
| 501-1000       | 10        | 7.69%   |
| 251-500        | 7         | 5.38%   |
| More than 3000 | 4         | 3.08%   |
| Unknown        | 4         | 3.08%   |
| 1001-2000      | 3         | 2.31%   |
| 2001-3000      | 1         | 0.77%   |

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
| Seagate ST31000528AS 1TB              | 1         | 2      | 6.67%   |
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
| Seagate | 6         | 17     | 40%     |
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
| Seagate | 6         | 17     | 42.86%  |
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
| HDD  | 12        | 29     | 92.31%  |
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
| Works    | 83        | 210    | 57.64%  |
| Detected | 47        | 79     | 32.64%  |
| Malfunc  | 13        | 30     | 9.03%   |
| Failed   | 1         | 1      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 82        | 47.4%   |
| AMD                          | 26        | 15.03%  |
| Samsung Electronics          | 18        | 10.4%   |
| Phison Electronics           | 5         | 2.89%   |
| LSI Logic / Symbios Logic    | 5         | 2.89%   |
| SanDisk                      | 4         | 2.31%   |
| Kingston Technology Company  | 4         | 2.31%   |
| SK hynix                     | 3         | 1.73%   |
| Micron Technology            | 3         | 1.73%   |
| Broadcom / LSI               | 3         | 1.73%   |
| ASMedia Technology           | 3         | 1.73%   |
| Toshiba America Info Systems | 2         | 1.16%   |
| Realtek Semiconductor        | 2         | 1.16%   |
| Hewlett-Packard              | 2         | 1.16%   |
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
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 7.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 4.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.96%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 2.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 1.98%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.98%   |
| Micron NVMe Storage Controller                                                          | 3         | 1.49%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.49%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 1.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 1.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.99%   |
| Realtek NVMe Controller                                                                 | 2         | 0.99%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.99%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 0.99%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 0.99%   |
| Intel SSD 660P Series                                                                   | 2         | 0.99%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.99%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 0.99%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 0.99%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 0.99%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.99%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 0.99%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 43.82%  |
| NVMe | 53        | 29.78%  |
| IDE  | 21        | 11.8%   |
| RAID | 20        | 11.24%  |
| SAS  | 5         | 2.81%   |
| SCSI | 1         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 93        | 73.81%  |
| AMD    | 32        | 25.4%   |
| ARM    | 1         | 0.79%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 3.17%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3         | 2.38%   |
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 1.59%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 2         | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.59%   |
| Intel 12th Gen Core i5-12400F               | 2         | 1.59%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.59%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.59%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 0.79%   |
| Intel Xeon Platinum 8124M CPU @ 3.00GHz     | 1         | 0.79%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 0.79%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.79%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.79%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.79%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 0.79%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.79%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.79%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1         | 0.79%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 0.79%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 0.79%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.79%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.79%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.79%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.79%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.79%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.79%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.79%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.79%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.79%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.79%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.79%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 28        | 22.22%  |
| Other                   | 20        | 15.87%  |
| Intel Core i5           | 15        | 11.9%   |
| Intel Xeon              | 14        | 11.11%  |
| AMD Ryzen 7             | 7         | 5.56%   |
| AMD Ryzen 5             | 7         | 5.56%   |
| Intel Core i3           | 6         | 4.76%   |
| Intel Celeron           | 4         | 3.17%   |
| AMD Ryzen 9             | 4         | 3.17%   |
| AMD FX                  | 3         | 2.38%   |
| AMD Ryzen Threadripper  | 2         | 1.59%   |
| AMD Ryzen 5 PRO         | 2         | 1.59%   |
| Intel Xeon Silver       | 1         | 0.79%   |
| Intel Xeon Platinum     | 1         | 0.79%   |
| Intel Xeon Gold         | 1         | 0.79%   |
| Intel Pentium Silver    | 1         | 0.79%   |
| Intel Pentium Dual-Core | 1         | 0.79%   |
| Intel Pentium Dual      | 1         | 0.79%   |
| Intel Core i9           | 1         | 0.79%   |
| Intel Core 2 Quad       | 1         | 0.79%   |
| Intel Core 2 Duo        | 1         | 0.79%   |
| AMD Ryzen Embedded      | 1         | 0.79%   |
| AMD Ryzen 7 PRO         | 1         | 0.79%   |
| AMD Ryzen 3             | 1         | 0.79%   |
| AMD Phenom II X6        | 1         | 0.79%   |
| AMD A8                  | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 46        | 36.51%  |
| 2      | 23        | 18.25%  |
| 6      | 20        | 15.87%  |
| 8      | 18        | 14.29%  |
| 12     | 5         | 3.97%   |
| 16     | 4         | 3.17%   |
| 10     | 3         | 2.38%   |
| 36     | 1         | 0.79%   |
| 32     | 1         | 0.79%   |
| 28     | 1         | 0.79%   |
| 24     | 1         | 0.79%   |
| 14     | 1         | 0.79%   |
| 3      | 1         | 0.79%   |
| 1      | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 116       | 92.06%  |
| 2      | 10        | 7.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 99        | 78.57%  |
| 1      | 27        | 21.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 12        | 9.52%   |
| 0x806c1    | 7         | 5.56%   |
| 0x206a7    | 7         | 5.56%   |
| 0x306a9    | 6         | 4.76%   |
| 0x806ec    | 5         | 3.97%   |
| 0x506e3    | 5         | 3.97%   |
| 0x0a50000c | 4         | 3.17%   |
| Unknown    | 4         | 3.17%   |
| 0xa0652    | 3         | 2.38%   |
| 0x806ea    | 3         | 2.38%   |
| 0x50654    | 3         | 2.38%   |
| 0xa0671    | 2         | 1.59%   |
| 0xa0655    | 2         | 1.59%   |
| 0x906a3    | 2         | 1.59%   |
| 0x90675    | 2         | 1.59%   |
| 0x90672    | 2         | 1.59%   |
| 0x706a8    | 2         | 1.59%   |
| 0x406f1    | 2         | 1.59%   |
| 0x40651    | 2         | 1.59%   |
| 0x306e4    | 2         | 1.59%   |
| 0x206d7    | 2         | 1.59%   |
| 0x206c2    | 2         | 1.59%   |
| 0x106a5    | 2         | 1.59%   |
| 0x10676    | 2         | 1.59%   |
| 0x08608103 | 2         | 1.59%   |
| 0x08600106 | 2         | 1.59%   |
| 0x08600104 | 2         | 1.59%   |
| 0x0800820d | 2         | 1.59%   |
| 0x06000852 | 2         | 1.59%   |
| 0xa0653    | 1         | 0.79%   |
| 0x906ed    | 1         | 0.79%   |
| 0x906ea    | 1         | 0.79%   |
| 0x906a4    | 1         | 0.79%   |
| 0x806e9    | 1         | 0.79%   |
| 0x706a1    | 1         | 0.79%   |
| 0x6fd      | 1         | 0.79%   |
| 0x50657    | 1         | 0.79%   |
| 0x406e3    | 1         | 0.79%   |
| 0x306f2    | 1         | 0.79%   |
| 0x20655    | 1         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 16        | 12.7%   |
| KabyLake         | 11        | 8.73%   |
| Skylake          | 10        | 7.94%   |
| SandyBridge      | 10        | 7.94%   |
| Zen 3            | 8         | 6.35%   |
| IvyBridge        | 8         | 6.35%   |
| Alderlake Hybrid | 8         | 6.35%   |
| Zen 2            | 7         | 5.56%   |
| TigerLake        | 7         | 5.56%   |
| CometLake        | 6         | 4.76%   |
| Unknown          | 5         | 3.97%   |
| Zen+             | 4         | 3.17%   |
| Piledriver       | 4         | 3.17%   |
| Penryn           | 4         | 3.17%   |
| Westmere         | 3         | 2.38%   |
| Goldmont plus    | 3         | 2.38%   |
| Zen              | 2         | 1.59%   |
| Nehalem          | 2         | 1.59%   |
| K10              | 2         | 1.59%   |
| Icelake          | 2         | 1.59%   |
| Broadwell        | 2         | 1.59%   |
| Excavator        | 1         | 0.79%   |
| Core             | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 64        | 41.56%  |
| Nvidia                     | 51        | 33.12%  |
| AMD                        | 28        | 18.18%  |
| Matrox Electronics Systems | 6         | 3.9%    |
| ASPEED Technology          | 5         | 3.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 4.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 3.21%   |
| ASPEED Technology ASPEED Graphics Family                                    | 5         | 3.21%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4         | 2.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.56%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 1.92%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.92%   |
| Intel UHD Graphics 620                                                      | 3         | 1.92%   |
| Intel HD Graphics 530                                                       | 3         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.92%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.92%   |
| AMD Renoir                                                                  | 3         | 1.92%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 1.28%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.28%   |
| Nvidia GP107GL [Quadro P400]                                                | 2         | 1.28%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.28%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 1.28%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2         | 1.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.28%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 2         | 1.28%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 1.28%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 1.28%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2         | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.28%   |
| AMD Lucienne                                                                | 2         | 1.28%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.28%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.64%   |
| Nvidia TU117GL [T600]                                                       | 1         | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.64%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 43        | 34.13%  |
| 1 x Nvidia      | 26        | 20.63%  |
| 1 x AMD         | 19        | 15.08%  |
| Intel + Nvidia  | 18        | 14.29%  |
| 1 x Matrox      | 5         | 3.97%   |
| AMD + Nvidia    | 4         | 3.17%   |
| 1 x ASPEED      | 3         | 2.38%   |
| 2 x AMD         | 2         | 1.59%   |
| Intel + AMD     | 2         | 1.59%   |
| Other           | 1         | 0.79%   |
| Nvidia + Matrox | 1         | 0.79%   |
| Nvidia + ASPEED | 1         | 0.79%   |
| AMD + ASPEED    | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 100       | 79.37%  |
| Proprietary | 19        | 15.08%  |
| Unknown     | 7         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 51.18%  |
| 0.01-0.5   | 17        | 13.39%  |
| 1.01-2.0   | 16        | 12.6%   |
| 3.01-4.0   | 11        | 8.66%   |
| 0.51-1.0   | 8         | 6.3%    |
| 7.01-8.0   | 3         | 2.36%   |
| 5.01-6.0   | 3         | 2.36%   |
| 8.01-16.0  | 2         | 1.57%   |
| 32.01-64.0 | 1         | 0.79%   |
| 2.01-3.0   | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 17        | 12.78%  |
| Samsung Electronics  | 14        | 10.53%  |
| LG Display           | 12        | 9.02%   |
| AU Optronics         | 11        | 8.27%   |
| BOE                  | 10        | 7.52%   |
| Goldstar             | 7         | 5.26%   |
| Chimei Innolux       | 7         | 5.26%   |
| Acer                 | 7         | 5.26%   |
| Philips              | 5         | 3.76%   |
| BenQ                 | 4         | 3.01%   |
| AOC                  | 4         | 3.01%   |
| Ancor Communications | 4         | 3.01%   |
| Sharp                | 3         | 2.26%   |
| Iiyama               | 3         | 2.26%   |
| Hewlett-Packard      | 3         | 2.26%   |
| ViewSonic            | 2         | 1.5%    |
| SGT                  | 2         | 1.5%    |
| InfoVision           | 2         | 1.5%    |
| ASUSTek Computer     | 2         | 1.5%    |
| Vizio                | 1         | 0.75%   |
| Sony                 | 1         | 0.75%   |
| Sceptre Tech         | 1         | 0.75%   |
| PANDA                | 1         | 0.75%   |
| Panasonic            | 1         | 0.75%   |
| OEM                  | 1         | 0.75%   |
| NEC Computers        | 1         | 0.75%   |
| Lenovo               | 1         | 0.75%   |
| IBM                  | 1         | 0.75%   |
| HUAWEI               | 1         | 0.75%   |
| HCL                  | 1         | 0.75%   |
| Gigabyte Technology  | 1         | 0.75%   |
| Eizo                 | 1         | 0.75%   |
| ADR                  | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                    | 2         | 1.46%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                      | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.46%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.73%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch             | 1         | 0.73%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                 | 1         | 0.73%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                     | 1         | 0.73%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 0.73%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.73%   |
| Sharp LCD Monitor SHP1491 3840x2160 346x194mm 15.6-inch                | 1         | 0.73%   |
| SGT HS160PC SGT1600 1920x1080 354x199mm 16.0-inch                      | 1         | 0.73%   |
| SGT HS156PC SGT1560 1920x1080 345x194mm 15.6-inch                      | 1         | 0.73%   |
| Sceptre Tech X240-CNC SPT0978 1920x1080 880x490mm 39.7-inch            | 1         | 0.73%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1         | 0.73%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch   | 1         | 0.73%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.73%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch    | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 0.73%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 698x393mm 31.5-inch     | 1         | 0.73%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 1         | 0.73%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1         | 0.73%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch      | 1         | 0.73%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch               | 1         | 0.73%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1         | 0.73%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch               | 1         | 0.73%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch               | 1         | 0.73%   |
| Philips 32 LCD TV PHL4650 1280x1024 760x450mm 34.8-inch                | 1         | 0.73%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 1         | 0.73%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.73%   |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch           | 1         | 0.73%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1         | 0.73%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch          | 1         | 0.73%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch           | 1         | 0.73%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch           | 1         | 0.73%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 46.03%  |
| 1366x768 (WXGA)    | 10        | 7.94%   |
| 3840x2160 (4K)     | 8         | 6.35%   |
| 2560x1440 (QHD)    | 8         | 6.35%   |
| 1280x1024 (SXGA)   | 7         | 5.56%   |
| 3440x1440          | 5         | 3.97%   |
| 1920x1200 (WUXGA)  | 5         | 3.97%   |
| 1600x900 (HD+)     | 5         | 3.97%   |
| 1680x1050 (WSXGA+) | 4         | 3.17%   |
| 3840x1080          | 3         | 2.38%   |
| 2560x1080          | 2         | 1.59%   |
| 1920x540           | 2         | 1.59%   |
| 1440x900 (WXGA+)   | 2         | 1.59%   |
| Unknown            | 2         | 1.59%   |
| 3840x2400          | 1         | 0.79%   |
| 2240x1400          | 1         | 0.79%   |
| 2160x1440          | 1         | 0.79%   |
| 1280x768           | 1         | 0.79%   |
| 1024x768 (XGA)     | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 20.45%  |
| 14      | 16        | 12.12%  |
| 27      | 14        | 10.61%  |
| 24      | 14        | 10.61%  |
| 17      | 9         | 6.82%   |
| 34      | 7         | 5.3%    |
| 23      | 6         | 4.55%   |
| 21      | 6         | 4.55%   |
| 13      | 6         | 4.55%   |
| 31      | 5         | 3.79%   |
| 19      | 5         | 3.79%   |
| 22      | 3         | 2.27%   |
| 20      | 2         | 1.52%   |
| Unknown | 2         | 1.52%   |
| 84      | 1         | 0.76%   |
| 65      | 1         | 0.76%   |
| 49      | 1         | 0.76%   |
| 48      | 1         | 0.76%   |
| 40      | 1         | 0.76%   |
| 39      | 1         | 0.76%   |
| 28      | 1         | 0.76%   |
| 25      | 1         | 0.76%   |
| 18      | 1         | 0.76%   |
| 16      | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 37.4%   |
| 501-600     | 33        | 25.19%  |
| 401-500     | 16        | 12.21%  |
| 351-400     | 8         | 6.11%   |
| 701-800     | 7         | 5.34%   |
| 601-700     | 6         | 4.58%   |
| 201-300     | 4         | 3.05%   |
| 1001-1500   | 3         | 2.29%   |
| 801-900     | 2         | 1.53%   |
| Unknown     | 2         | 1.53%   |
| 1501-2000   | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 86        | 73.5%   |
| 16/10   | 11        | 9.4%    |
| 5/4     | 7         | 5.98%   |
| 21/9    | 6         | 5.13%   |
| 3/2     | 3         | 2.56%   |
| 32/9    | 2         | 1.71%   |
| 4/3     | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 21.54%  |
| 201-250        | 24        | 18.46%  |
| 81-90          | 20        | 15.38%  |
| 301-350        | 14        | 10.77%  |
| 351-500        | 12        | 9.23%   |
| 151-200        | 8         | 6.15%   |
| 141-150        | 5         | 3.85%   |
| 121-130        | 5         | 3.85%   |
| 501-1000       | 5         | 3.85%   |
| 251-300        | 3         | 2.31%   |
| More than 1000 | 2         | 1.54%   |
| Unknown        | 2         | 1.54%   |
| 71-80          | 1         | 0.77%   |
| 91-100         | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 53        | 41.09%  |
| 121-160       | 39        | 30.23%  |
| 101-120       | 22        | 17.05%  |
| 161-240       | 7         | 5.43%   |
| More than 240 | 4         | 3.1%    |
| 1-50          | 2         | 1.55%   |
| Unknown       | 2         | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 65.87%  |
| 2     | 20        | 15.87%  |
| 0     | 19        | 15.08%  |
| 3     | 3         | 2.38%   |
| 4     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 81        | 44.26%  |
| Realtek Semiconductor     | 54        | 29.51%  |
| Broadcom                  | 9         | 4.92%   |
| Qualcomm Atheros          | 8         | 4.37%   |
| MediaTek                  | 7         | 3.83%   |
| Mellanox Technologies     | 3         | 1.64%   |
| Broadcom Limited          | 3         | 1.64%   |
| Ralink Technology         | 2         | 1.09%   |
| Marvell Technology Group  | 2         | 1.09%   |
| Linksys                   | 2         | 1.09%   |
| TP-Link                   | 1         | 0.55%   |
| Solarflare Communications | 1         | 0.55%   |
| Ralink                    | 1         | 0.55%   |
| Qualcomm                  | 1         | 0.55%   |
| Microsoft                 | 1         | 0.55%   |
| Lenovo                    | 1         | 0.55%   |
| JMicron Technology        | 1         | 0.55%   |
| Dell                      | 1         | 0.55%   |
| D-Link                    | 1         | 0.55%   |
| BUFFALO                   | 1         | 0.55%   |
| Aquantia                  | 1         | 0.55%   |
| American Megatrends       | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 37        | 17.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 8         | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 7         | 3.23%   |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 3.23%   |
| Intel Wireless 7260                                                                                                    | 6         | 2.76%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6         | 2.76%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 5         | 2.3%    |
| Intel Ethernet Controller I225-V                                                                                       | 5         | 2.3%    |
| Intel I211 Gigabit Network Connection                                                                                  | 4         | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 3         | 1.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 3         | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 1.38%   |
| Intel Wireless 8265 / 8275                                                                                             | 3         | 1.38%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 3         | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 3         | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 3         | 1.38%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 2         | 0.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 2         | 0.92%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 2         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 2         | 0.92%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 0.92%   |
| Intel Wireless 8260                                                                                                    | 2         | 0.92%   |
| Intel Wireless 7265                                                                                                    | 2         | 0.92%   |
| Intel Wireless 3165                                                                                                    | 2         | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                                 | 2         | 0.92%   |
| Intel I210 Gigabit Network Connection                                                                                  | 2         | 0.92%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 0.92%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 0.92%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                                                                                   | 2         | 0.92%   |
| Intel Ethernet Connection (17) I219-V                                                                                  | 2         | 0.92%   |
| Intel Ethernet Connection (14) I219-V                                                                                  | 2         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 2         | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 2         | 0.92%   |
| Intel 82574L Gigabit Network Connection                                                                                | 2         | 0.92%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                                                | 2         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 56.96%  |
| Realtek Semiconductor | 9         | 11.39%  |
| Qualcomm Atheros      | 7         | 8.86%   |
| MediaTek              | 7         | 8.86%   |
| Ralink Technology     | 2         | 2.53%   |
| Linksys               | 2         | 2.53%   |
| TP-Link               | 1         | 1.27%   |
| Ralink                | 1         | 1.27%   |
| Microsoft             | 1         | 1.27%   |
| Dell                  | 1         | 1.27%   |
| BUFFALO               | 1         | 1.27%   |
| Broadcom Limited      | 1         | 1.27%   |
| Broadcom              | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 6         | 7.41%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 7.41%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 6.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 3.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 3.7%    |
| Intel Wireless 8265 / 8275                                     | 3         | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.47%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.47%   |
| Intel Wireless 8260                                            | 2         | 2.47%   |
| Intel Wireless 7265                                            | 2         | 2.47%   |
| Intel Wireless 3165                                            | 2         | 2.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.23%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.23%   |
| Realtek 802.11ac NIC                                           | 1         | 1.23%   |
| Ralink RT3071 Wireless Adapter                                 | 1         | 1.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.23%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter       | 1         | 1.23%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1         | 1.23%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1         | 1.23%   |
| Intel Wireless 3160                                            | 1         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.23%   |
| Intel Centrino Wireless-N 135                                  | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 56        | 43.75%  |
| Realtek Semiconductor     | 50        | 39.06%  |
| Broadcom                  | 9         | 7.03%   |
| Marvell Technology Group  | 2         | 1.56%   |
| Broadcom Limited          | 2         | 1.56%   |
| Solarflare Communications | 1         | 0.78%   |
| Qualcomm Atheros          | 1         | 0.78%   |
| Qualcomm                  | 1         | 0.78%   |
| Mellanox Technologies     | 1         | 0.78%   |
| Lenovo                    | 1         | 0.78%   |
| JMicron Technology        | 1         | 0.78%   |
| D-Link                    | 1         | 0.78%   |
| Aquantia                  | 1         | 0.78%   |
| American Megatrends       | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 27.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 5.22%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 5.22%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.73%   |
| Intel I211 Gigabit Network Connection                             | 4         | 2.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.24%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.24%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.49%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.49%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.49%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 1.49%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.49%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 2         | 1.49%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.75%   |
| Qualcomm Nokia XR20                                               | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.75%   |
| Mellanox MT27700 Family [ConnectX-4]                              | 1         | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.75%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.75%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.75%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.75%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.75%   |
| Intel Ethernet Controller X550                                    | 1         | 0.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.75%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.75%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.75%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.75%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 59.26%  |
| WiFi     | 75        | 39.68%  |
| Unknown  | 2         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 82        | 62.6%   |
| WiFi     | 49        | 37.4%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 45.24%  |
| 1     | 53        | 42.06%  |
| 3     | 7         | 5.56%   |
| 5     | 3         | 2.38%   |
| 4     | 2         | 1.59%   |
| 0     | 2         | 1.59%   |
| 66    | 1         | 0.79%   |
| 8     | 1         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 77.78%  |
| Yes  | 28        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 58.73%  |
| Realtek Semiconductor           | 4         | 6.35%   |
| Qualcomm Atheros Communications | 4         | 6.35%   |
| Foxconn / Hon Hai               | 4         | 6.35%   |
| MediaTek                        | 3         | 4.76%   |
| Cambridge Silicon Radio         | 3         | 4.76%   |
| IMC Networks                    | 2         | 3.17%   |
| Broadcom                        | 2         | 3.17%   |
| Ralink                          | 1         | 1.59%   |
| Integrated System Solution      | 1         | 1.59%   |
| Hewlett-Packard                 | 1         | 1.59%   |
| Dell                            | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 15        | 23.81%  |
| Intel AX201 Bluetooth                                 | 10        | 15.87%  |
| Intel AX200 Bluetooth                                 | 6         | 9.52%   |
| Realtek Bluetooth Radio                               | 3         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 4.76%   |
| MediaTek Wireless_Device                              | 3         | 4.76%   |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3         | 4.76%   |
| Intel Bluetooth Device                                | 2         | 3.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 3.17%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.59%   |
| Ralink RT3290 Bluetooth                               | 1         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 1.59%   |
| Intel AX210 Bluetooth                                 | 1         | 1.59%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.59%   |
| IMC Networks Wireless_Device                          | 1         | 1.59%   |
| IMC Networks Bluetooth Device                         | 1         | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.59%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1         | 1.59%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 1.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 81        | 46.29%  |
| Nvidia              | 40        | 22.86%  |
| AMD                 | 34        | 19.43%  |
| C-Media Electronics | 4         | 2.29%   |
| Logitech            | 3         | 1.71%   |
| GN Netcom           | 2         | 1.14%   |
| Creative Technology | 2         | 1.14%   |
| Conexant Systems    | 2         | 1.14%   |
| Setek Elektronik    | 1         | 0.57%   |
| Saitek              | 1         | 0.57%   |
| Nektar              | 1         | 0.57%   |
| Huawei Technologies | 1         | 0.57%   |
| Hewlett-Packard     | 1         | 0.57%   |
| GYROCOM C&C         | 1         | 0.57%   |
| ASUSTek Computer    | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 15        | 7.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12        | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 10        | 4.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9         | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 4.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 7         | 3.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 2.45%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 2.45%   |
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 2.45%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5         | 2.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4         | 1.96%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4         | 1.96%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 1.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 4         | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4         | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 1.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 1.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3         | 1.47%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3         | 1.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3         | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 1.47%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 0.98%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 0.98%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 0.98%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 0.98%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2         | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 0.98%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.98%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.98%   |
| C-Media Electronics BIRD UM1                                                      | 2         | 0.98%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2         | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 0.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.98%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 20.83%  |
| Micron Technology   | 14        | 14.58%  |
| SK hynix            | 12        | 12.5%   |
| Kingston            | 8         | 8.33%   |
| Corsair             | 8         | 8.33%   |
| G.Skill             | 7         | 7.29%   |
| Crucial             | 7         | 7.29%   |
| Unknown             | 6         | 6.25%   |
| A-DATA Technology   | 2         | 2.08%   |
| Unknown (ABCD)      | 1         | 1.04%   |
| Team                | 1         | 1.04%   |
| Smart               | 1         | 1.04%   |
| Ramaxel Technology  | 1         | 1.04%   |
| PNY                 | 1         | 1.04%   |
| Patriot             | 1         | 1.04%   |
| Magnum Tech         | 1         | 1.04%   |
| Lexar Co Limited    | 1         | 1.04%   |
| Lexar               | 1         | 1.04%   |
| Hewlett-Packard     | 1         | 1.04%   |
| Gold Key            | 1         | 1.04%   |
| Unknown             | 1         | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.02%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 2.02%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                        | 1         | 1.01%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.01%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.01%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 1.01%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.01%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 1.01%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.01%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 1.01%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.01%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.01%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 1.01%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.01%   |
| SK hynix RAM HMT325U7EFR8A-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.01%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.01%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.01%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.01%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.01%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.01%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.01%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 1.01%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.01%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.01%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.01%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.01%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s             | 1         | 1.01%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 1.01%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 1.01%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.01%   |
| Samsung RAM M393A4K40BB2-CTD 32GB DIMM DDR4 2666MT/s             | 1         | 1.01%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s              | 1         | 1.01%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 1.01%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.01%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s             | 1         | 1.01%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 49        | 57.65%  |
| DDR3    | 25        | 29.41%  |
| LPDDR4  | 3         | 3.53%   |
| DDR5    | 3         | 3.53%   |
| DDR2    | 3         | 3.53%   |
| LPDDR5  | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 45        | 52.33%  |
| SODIMM       | 35        | 40.7%   |
| Row Of Chips | 5         | 5.81%   |
| RIMM         | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 43.96%  |
| 16384 | 15        | 16.48%  |
| 4096  | 13        | 14.29%  |
| 32768 | 12        | 13.19%  |
| 1024  | 6         | 6.59%   |
| 2048  | 5         | 5.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 22        | 24.18%  |
| 2667  | 12        | 13.19%  |
| 1600  | 12        | 13.19%  |
| 2400  | 7         | 7.69%   |
| 1333  | 6         | 6.59%   |
| 2133  | 4         | 4.4%    |
| 4800  | 3         | 3.3%    |
| 2666  | 3         | 3.3%    |
| 667   | 3         | 3.3%    |
| 3600  | 2         | 2.2%    |
| 3534  | 2         | 2.2%    |
| 1066  | 2         | 2.2%    |
| 6400  | 1         | 1.1%    |
| 4267  | 1         | 1.1%    |
| 4266  | 1         | 1.1%    |
| 3733  | 1         | 1.1%    |
| 3666  | 1         | 1.1%    |
| 3266  | 1         | 1.1%    |
| 3100  | 1         | 1.1%    |
| 3000  | 1         | 1.1%    |
| 2800  | 1         | 1.1%    |
| 2200  | 1         | 1.1%    |
| 2048  | 1         | 1.1%    |
| 1866  | 1         | 1.1%    |
| 1800  | 1         | 1.1%    |

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
| Chicony Electronics                    | 11        | 19.3%   |
| IMC Networks                           | 8         | 14.04%  |
| Microdia                               | 5         | 8.77%   |
| Syntek                                 | 4         | 7.02%   |
| Logitech                               | 4         | 7.02%   |
| Sunplus Innovation Technology          | 3         | 5.26%   |
| Realtek Semiconductor                  | 3         | 5.26%   |
| Luxvisions Innotech Limited            | 3         | 5.26%   |
| Generalplus Technology                 | 2         | 3.51%   |
| Bison Electronics                      | 2         | 3.51%   |
| 2M UVC CAMERA                          | 2         | 3.51%   |
| Suyin                                  | 1         | 1.75%   |
| Quanta                                 | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |
| KYE Systems (Mouse Systems)            | 1         | 1.75%   |
| Intel                                  | 1         | 1.75%   |
| Huawei Technologies                    | 1         | 1.75%   |
| Elgato Systems                         | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.75%   |
| Apple                                  | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 7         | 12.28%  |
| Microdia Integrated_Webcam_HD                                              | 4         | 7.02%   |
| IMC Networks Integrated Camera                                             | 3         | 5.26%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.51%   |
| Syntek Integrated Camera                                                   | 2         | 3.51%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.51%   |
| Logitech HD Pro Webcam C920                                                | 2         | 3.51%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 3.51%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 3.51%   |
| Chicony HP HD Camera                                                       | 2         | 3.51%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam                                        | 2         | 3.51%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 1.75%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.75%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.75%   |
| Sunplus FHD Camera Microphone                                              | 1         | 1.75%   |
| Realtek EasyCamera                                                         | 1         | 1.75%   |
| Quanta HP Webcam                                                           | 1         | 1.75%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.75%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.75%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.75%   |
| Logitech Webcam C270                                                       | 1         | 1.75%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 1.75%   |
| Lite-On HP HD Webcam                                                       | 1         | 1.75%   |
| Lenovo UVC Camera                                                          | 1         | 1.75%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 1         | 1.75%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 1.75%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 1.75%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.75%   |
| IMC Networks HD Camera                                                     | 1         | 1.75%   |
| Huawei HiCamera                                                            | 1         | 1.75%   |
| Elgato Systems Elgato Facecam                                              | 1         | 1.75%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.75%   |
| Chicony HD WebCam                                                          | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.75%   |
| Bison Integrated RGB Camera                                                | 1         | 1.75%   |
| Bison Integrated Camera                                                    | 1         | 1.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 1.75%   |

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
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 10.53%  |
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
| 0     | 70        | 55.56%  |
| 1     | 41        | 32.54%  |
| 2     | 10        | 7.94%   |
| 5     | 2         | 1.59%   |
| 3     | 2         | 1.59%   |
| 4     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 26.03%  |
| Graphics card            | 14        | 19.18%  |
| Net/wireless             | 10        | 13.7%   |
| Unassigned class         | 7         | 9.59%   |
| Communication controller | 6         | 8.22%   |
| Net/ethernet             | 3         | 4.11%   |
| Chipcard                 | 3         | 4.11%   |
| Network                  | 2         | 2.74%   |
| Multimedia controller    | 2         | 2.74%   |
| Storage/raid             | 1         | 1.37%   |
| Storage                  | 1         | 1.37%   |
| Sound                    | 1         | 1.37%   |
| Firewire controller      | 1         | 1.37%   |
| Dvb card                 | 1         | 1.37%   |
| Card reader              | 1         | 1.37%   |
| Bluetooth                | 1         | 1.37%   |

