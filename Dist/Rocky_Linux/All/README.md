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

Total: 131

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Rocky Linux 8.5 | 31        | 28.44%  |
| Rocky Linux 9.1 | 21        | 19.27%  |
| Rocky Linux 9.0 | 19        | 17.43%  |
| Rocky Linux 8.4 | 19        | 17.43%  |
| Rocky Linux 8.6 | 11        | 10.09%  |
| Rocky Linux 8.7 | 6         | 5.5%    |
| Rocky Linux 8.3 | 2         | 1.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 107       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 17        | 15.6%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 11.93%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 7.34%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 5.5%    |
| 5.14.0-70.26.1.el9_0.x86_64      | 5         | 4.59%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 4.59%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 3.67%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 3.67%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 3.67%   |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 2.75%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 2.75%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 2         | 1.83%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 1.83%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 2         | 1.83%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 1.83%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 1.83%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 1.83%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 1.83%   |
| 4.18.0-305.el8.x86_64            | 2         | 1.83%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 1.83%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 1.83%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 1.83%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 1.83%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1         | 0.92%   |
| 6.0.10_tkg_bmq                   | 1         | 0.92%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1         | 0.92%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 0.92%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 0.92%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 0.92%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 0.92%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 1         | 0.92%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 0.92%   |
| 5.10.89-1.el8.x86_64             | 1         | 0.92%   |
| 5.10.52-v8.1.el8                 | 1         | 0.92%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 0.92%   |
| 4.18.0-348.23.1.el8_5.x86_64     | 1         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 62        | 57.41%  |
| 5.14.0  | 38        | 35.19%  |
| 6.0.10  | 2         | 1.85%   |
| 6.1.6   | 1         | 0.93%   |
| 5.4.157 | 1         | 0.93%   |
| 5.16.15 | 1         | 0.93%   |
| 5.14.1  | 1         | 0.93%   |
| 5.10.89 | 1         | 0.93%   |
| 5.10.52 | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 62        | 57.41%  |
| 5.14    | 39        | 36.11%  |
| 6.0     | 2         | 1.85%   |
| 5.10    | 2         | 1.85%   |
| 6.1     | 1         | 0.93%   |
| 5.4     | 1         | 0.93%   |
| 5.16    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 106       | 99.07%  |
| aarch64 | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 76        | 71.03%  |
| Unknown       | 10        | 9.35%   |
| KDE5          | 9         | 8.41%   |
| MATE          | 5         | 4.67%   |
| XFCE          | 3         | 2.8%    |
| GNOME Classic | 3         | 2.8%    |
| X-Cinnamon    | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 62        | 56.88%  |
| X11     | 36        | 33.03%  |
| Unknown | 5         | 4.59%   |
| Tty     | 4         | 3.67%   |
| Web     | 2         | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 48        | 44.86%  |
| Unknown | 48        | 44.86%  |
| SDDM    | 8         | 7.48%   |
| LightDM | 3         | 2.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 68        | 63.55%  |
| ru_RU   | 6         | 5.61%   |
| en_AU   | 5         | 4.67%   |
| en_IL   | 3         | 2.8%    |
| en_CA   | 3         | 2.8%    |
| en_ZA   | 2         | 1.87%   |
| en_SG   | 2         | 1.87%   |
| de_DE   | 2         | 1.87%   |
| de_AT   | 2         | 1.87%   |
| C       | 2         | 1.87%   |
| pt_BR   | 1         | 0.93%   |
| pl_PL   | 1         | 0.93%   |
| ko_KR   | 1         | 0.93%   |
| ja_JP   | 1         | 0.93%   |
| it_IT   | 1         | 0.93%   |
| hu_HU   | 1         | 0.93%   |
| es_ES   | 1         | 0.93%   |
| es_CO   | 1         | 0.93%   |
| es_AR   | 1         | 0.93%   |
| en_IE   | 1         | 0.93%   |
| af_ZA   | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 68        | 63.55%  |
| BIOS | 39        | 36.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 87        | 81.31%  |
| Ext4 | 19        | 17.76%  |
| Ext3 | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 51        | 47.66%  |
| Unknown | 38        | 35.51%  |
| MBR     | 18        | 16.82%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 83.18%  |
| Yes       | 18        | 16.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 85.05%  |
| Yes       | 16        | 14.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 23        | 21.5%   |
| Lenovo                  | 19        | 17.76%  |
| ASUSTek Computer        | 18        | 16.82%  |
| Hewlett-Packard         | 15        | 14.02%  |
| MSI                     | 5         | 4.67%   |
| Gigabyte Technology     | 5         | 4.67%   |
| Intel                   | 3         | 2.8%    |
| Unknown                 | 3         | 2.8%    |
| Toshiba                 | 2         | 1.87%   |
| Supermicro              | 2         | 1.87%   |
| AZW                     | 2         | 1.87%   |
| ASRock                  | 2         | 1.87%   |
| Raspberry Pi Foundation | 1         | 0.93%   |
| NCR                     | 1         | 0.93%   |
| IBM                     | 1         | 0.93%   |
| HUAWEI                  | 1         | 0.93%   |
| Google                  | 1         | 0.93%   |
| BESSTAR Tech            | 1         | 0.93%   |
| BANGHO                  | 1         | 0.93%   |
| Acer                    | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 2.8%    |
| Dell PowerEdge R610                    | 2         | 1.87%   |
| Dell OptiPlex 9020                     | 2         | 1.87%   |
| Toshiba TECRA W50-A                    | 1         | 0.93%   |
| Toshiba Satellite E45-B                | 1         | 0.93%   |
| Supermicro SYS-5029P-WTR               | 1         | 0.93%   |
| Supermicro Super Server                | 1         | 0.93%   |
| RPi Raspberry Pi                       | 1         | 0.93%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 0.93%   |
| MSI MS-7D46                            | 1         | 0.93%   |
| MSI MS-7B89                            | 1         | 0.93%   |
| MSI MS-7A94                            | 1         | 0.93%   |
| MSI MS-7917                            | 1         | 0.93%   |
| MSI H510M PRO-E                        | 1         | 0.93%   |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 0.93%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 0.93%   |
| Lenovo ThinkPad W500 406132G           | 1         | 0.93%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK    | 1         | 0.93%   |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 0.93%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 0.93%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.93%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 0.93%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.93%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 0.93%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 0.93%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.93%   |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 0.93%   |
| Intel S2600WFT                         | 1         | 0.93%   |
| Intel PRO412081                        | 1         | 0.93%   |
| Intel NUC10i3FNK                       | 1         | 0.93%   |
| IBM System x3200 M2 -[4368IGS]-        | 1         | 0.93%   |
| HUAWEI KLVD-WXX9                       | 1         | 0.93%   |
| HP ZBook 15u G6                        | 1         | 0.93%   |
| HP ZBook 15 G3                         | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS PRIME               | 9         | 8.41%   |
| Lenovo ThinkPad          | 8         | 7.48%   |
| Lenovo IdeaPad           | 5         | 4.67%   |
| Dell Precision           | 4         | 3.74%   |
| Dell PowerEdge           | 4         | 3.74%   |
| Dell OptiPlex            | 4         | 3.74%   |
| Dell Latitude            | 4         | 3.74%   |
| HP ZBook                 | 3         | 2.8%    |
| Dell XPS                 | 3         | 2.8%    |
| Unknown                  | 3         | 2.8%    |
| Lenovo Legion            | 2         | 1.87%   |
| Lenovo IdeaPadFlex       | 2         | 1.87%   |
| HP Laptop                | 2         | 1.87%   |
| HP EliteDesk             | 2         | 1.87%   |
| HP EliteBook             | 2         | 1.87%   |
| Dell Vostro              | 2         | 1.87%   |
| Dell Inspiron            | 2         | 1.87%   |
| ASUS ASUS                | 2         | 1.87%   |
| Toshiba TECRA            | 1         | 0.93%   |
| Toshiba Satellite        | 1         | 0.93%   |
| Supermicro SYS-5029P-WTR | 1         | 0.93%   |
| Supermicro Super         | 1         | 0.93%   |
| RPi Raspberry            | 1         | 0.93%   |
| NCR xxxx-xxxx-xxxx       | 1         | 0.93%   |
| MSI MS-7D46              | 1         | 0.93%   |
| MSI MS-7B89              | 1         | 0.93%   |
| MSI MS-7A94              | 1         | 0.93%   |
| MSI MS-7917              | 1         | 0.93%   |
| MSI H510M                | 1         | 0.93%   |
| Lenovo ThinkStation      | 1         | 0.93%   |
| Lenovo ThinkCentre       | 1         | 0.93%   |
| Intel S2600WFT           | 1         | 0.93%   |
| Intel PRO412081          | 1         | 0.93%   |
| Intel NUC10i3FNK         | 1         | 0.93%   |
| IBM System               | 1         | 0.93%   |
| HUAWEI KLVD-WXX9         | 1         | 0.93%   |
| HP Z600                  | 1         | 0.93%   |
| HP ProLiant              | 1         | 0.93%   |
| HP ProDesk               | 1         | 0.93%   |
| HP ProBook               | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 19        | 17.76%  |
| 2020    | 15        | 14.02%  |
| 2019    | 10        | 9.35%   |
| 2018    | 9         | 8.41%   |
| 2022    | 8         | 7.48%   |
| 2014    | 8         | 7.48%   |
| 2011    | 8         | 7.48%   |
| 2015    | 7         | 6.54%   |
| 2013    | 7         | 6.54%   |
| 2012    | 4         | 3.74%   |
| 2010    | 3         | 2.8%    |
| 2017    | 2         | 1.87%   |
| 2016    | 2         | 1.87%   |
| 2009    | 2         | 1.87%   |
| 2008    | 2         | 1.87%   |
| Unknown | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 48        | 44.86%  |
| Notebook       | 42        | 39.25%  |
| Server         | 9         | 8.41%   |
| Mini pc        | 4         | 3.74%   |
| Convertible    | 2         | 1.87%   |
| System on chip | 1         | 0.93%   |
| Tablet         | 1         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 97        | 90.65%  |
| Enabled  | 10        | 9.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 29        | 27.1%   |
| 32.01-64.0      | 21        | 19.63%  |
| 4.01-8.0        | 19        | 17.76%  |
| 16.01-24.0      | 15        | 14.02%  |
| 64.01-256.0     | 7         | 6.54%   |
| 3.01-4.0        | 6         | 5.61%   |
| More than 256.0 | 3         | 2.8%    |
| 1.01-2.0        | 3         | 2.8%    |
| 24.01-32.0      | 2         | 1.87%   |
| 2.01-3.0        | 2         | 1.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 31        | 28.7%   |
| 4.01-8.0   | 24        | 22.22%  |
| 3.01-4.0   | 22        | 20.37%  |
| 1.01-2.0   | 18        | 16.67%  |
| 8.01-16.0  | 6         | 5.56%   |
| 0.51-1.0   | 4         | 3.7%    |
| 16.01-24.0 | 2         | 1.85%   |
| 0.01-0.5   | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 56.07%  |
| 2      | 20        | 18.69%  |
| 3      | 11        | 10.28%  |
| 4      | 8         | 7.48%   |
| 5      | 2         | 1.87%   |
| 18     | 1         | 0.93%   |
| 16     | 1         | 0.93%   |
| 14     | 1         | 0.93%   |
| 9      | 1         | 0.93%   |
| 8      | 1         | 0.93%   |
| 6      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 70.09%  |
| Yes       | 32        | 29.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 89.72%  |
| No        | 11        | 10.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 58.33%  |
| No        | 45        | 41.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 50.47%  |
| No        | 53        | 49.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 23.36%  |
| Russia       | 6         | 5.61%   |
| Germany      | 6         | 5.61%   |
| Canada       | 6         | 5.61%   |
| Australia    | 6         | 5.61%   |
| Italy        | 4         | 3.74%   |
| Czechia      | 4         | 3.74%   |
| South Africa | 3         | 2.8%    |
| Singapore    | 3         | 2.8%    |
| Israel       | 3         | 2.8%    |
| Sweden       | 2         | 1.87%   |
| South Korea  | 2         | 1.87%   |
| Poland       | 2         | 1.87%   |
| Netherlands  | 2         | 1.87%   |
| Mexico       | 2         | 1.87%   |
| Indonesia    | 2         | 1.87%   |
| India        | 2         | 1.87%   |
| Hungary      | 2         | 1.87%   |
| Belgium      | 2         | 1.87%   |
| Argentina    | 2         | 1.87%   |
| Uzbekistan   | 1         | 0.93%   |
| UK           | 1         | 0.93%   |
| UAE          | 1         | 0.93%   |
| Turkey       | 1         | 0.93%   |
| Switzerland  | 1         | 0.93%   |
| Spain        | 1         | 0.93%   |
| Slovakia     | 1         | 0.93%   |
| Saudi Arabia | 1         | 0.93%   |
| Portugal     | 1         | 0.93%   |
| Pakistan     | 1         | 0.93%   |
| Norway       | 1         | 0.93%   |
| Malaysia     | 1         | 0.93%   |
| Kazakhstan   | 1         | 0.93%   |
| Japan        | 1         | 0.93%   |
| Ireland      | 1         | 0.93%   |
| France       | 1         | 0.93%   |
| Finland      | 1         | 0.93%   |
| Colombia     | 1         | 0.93%   |
| China        | 1         | 0.93%   |
| Brazil       | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 2.8%    |
| Melbourne              | 3         | 2.8%    |
| Toronto                | 2         | 1.87%   |
| Prague                 | 2         | 1.87%   |
| Moscow                 | 2         | 1.87%   |
| Haifa                  | 2         | 1.87%   |
| Centurion              | 2         | 1.87%   |
| Budapest               | 2         | 1.87%   |
| Berlin                 | 2         | 1.87%   |
| Adelaide               | 2         | 1.87%   |
| Žilina                | 1         | 0.93%   |
| Yogyakarta             | 1         | 0.93%   |
| Xi'an                  | 1         | 0.93%   |
| Wells                  | 1         | 0.93%   |
| Waltham                | 1         | 0.93%   |
| Voronezh               | 1         | 0.93%   |
| Vienna                 | 1         | 0.93%   |
| Vancouver              | 1         | 0.93%   |
| Torrington             | 1         | 0.93%   |
| Tlaxcala City          | 1         | 0.93%   |
| Syracuse               | 1         | 0.93%   |
| St. John's             | 1         | 0.93%   |
| St Petersburg          | 1         | 0.93%   |
| Sobral de Monte Agraco | 1         | 0.93%   |
| Smolensk               | 1         | 0.93%   |
| Senigallia             | 1         | 0.93%   |
| Semarang               | 1         | 0.93%   |
| Scarborough            | 1         | 0.93%   |
| San Miguel de Tucumán | 1         | 0.93%   |
| Rotterdam              | 1         | 0.93%   |
| Riyadh                 | 1         | 0.93%   |
| Rehovot                | 1         | 0.93%   |
| Rawalpindi             | 1         | 0.93%   |
| Progresista            | 1         | 0.93%   |
| Philadelphia           | 1         | 0.93%   |
| Paris                  | 1         | 0.93%   |
| Ottignies              | 1         | 0.93%   |
| Ōtsu                  | 1         | 0.93%   |
| Oslo                   | 1         | 0.93%   |
| Örebro                | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 40     | 17.28%  |
| Seagate                     | 26        | 64     | 16.05%  |
| WDC                         | 22        | 44     | 13.58%  |
| Toshiba                     | 13        | 14     | 8.02%   |
| Intel                       | 8         | 10     | 4.94%   |
| Kingston                    | 6         | 6      | 3.7%    |
| SanDisk                     | 5         | 6      | 3.09%   |
| Hitachi                     | 5         | 6      | 3.09%   |
| Unknown                     | 4         | 4      | 2.47%   |
| SK hynix                    | 4         | 5      | 2.47%   |
| Crucial                     | 4         | 4      | 2.47%   |
| Phison                      | 3         | 3      | 1.85%   |
| Micron Technology           | 2         | 2      | 1.23%   |
| LITEONIT                    | 2         | 2      | 1.23%   |
| Lexar                       | 2         | 2      | 1.23%   |
| HGST                        | 2         | 2      | 1.23%   |
| Corsair                     | 2         | 2      | 1.23%   |
| A-DATA Technology           | 2         | 2      | 1.23%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.62%   |
| UMIS                        | 1         | 1      | 0.62%   |
| Team                        | 1         | 1      | 0.62%   |
| StoreJet                    | 1         | 1      | 0.62%   |
| PNY                         | 1         | 1      | 0.62%   |
| MyDigitalSSD                | 1         | 1      | 0.62%   |
| LITEON                      | 1         | 1      | 0.62%   |
| Kingston Technology Company | 1         | 1      | 0.62%   |
| KingFast                    | 1         | 1      | 0.62%   |
| JMicron Technology          | 1         | 1      | 0.62%   |
| INDMEM                      | 1         | 1      | 0.62%   |
| IBM                         | 1         | 1      | 0.62%   |
| HS-SSD-C100                 | 1         | 1      | 0.62%   |
| Gigabyte Technology         | 1         | 1      | 0.62%   |
| Fujitsu                     | 1         | 1      | 0.62%   |
| Dogfish                     | 1         | 1      | 0.62%   |
| Digma                       | 1         | 1      | 0.62%   |
| China                       | 1         | 1      | 0.62%   |
| Apacer                      | 1         | 1      | 0.62%   |
| AGI                         | 1         | 1      | 0.62%   |
| ADATA Technology            | 1         | 1      | 0.62%   |
| ADATA SU                    | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3         | 1.59%   |
| Unknown MMC Card  64GB           | 2         | 1.06%   |
| Seagate ST9320325AS 320GB        | 2         | 1.06%   |
| Seagate ST300MP0005 304GB        | 2         | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 1.06%   |
| Samsung SSD 870 EVO 1TB          | 2         | 1.06%   |
| Samsung SSD 860 EVO 1TB          | 2         | 1.06%   |
| Lexar 512GB SSD                  | 2         | 1.06%   |
| A-DATA SWORDFISH 1TB             | 2         | 1.06%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1         | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.53%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1         | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.53%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1         | 0.53%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD   | 1         | 0.53%   |
| WDC WDBNCE0010PNC 1TB SSD        | 1         | 0.53%   |
| WDC WD80EZZX-11CSGA0 8TB         | 1         | 0.53%   |
| WDC WD80EMAZ-00WJTA0 8TB         | 1         | 0.53%   |
| WDC WD80EDAZ-11TA3A0 8TB         | 1         | 0.53%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 0.53%   |
| WDC WD5000BPVT-00A1YT0 500GB     | 1         | 0.53%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1         | 0.53%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 0.53%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1         | 0.53%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1         | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.53%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1         | 0.53%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1         | 0.53%   |
| WDC WD20EFZX-68AWUN0 2TB         | 1         | 0.53%   |
| WDC WD2002FAEX-007BA0 2TB        | 1         | 0.53%   |
| WDC WD120EDAZ-11F3RA0 12TB       | 1         | 0.53%   |
| WDC WD10SPCX-24HWST1 1TB         | 1         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB         | 1         | 0.53%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1         | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1         | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1         | 0.53%   |
| WDC WD100EMAZ-00WJTA0 10TB       | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 64     | 41.94%  |
| WDC                 | 16        | 32     | 25.81%  |
| Toshiba             | 7         | 7      | 11.29%  |
| Hitachi             | 5         | 6      | 8.06%   |
| Samsung Electronics | 2         | 3      | 3.23%   |
| HGST                | 2         | 2      | 3.23%   |
| Unknown             | 1         | 1      | 1.61%   |
| StoreJet            | 1         | 1      | 1.61%   |
| IBM                 | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 23.53%  |
| WDC                 | 6         | 9      | 11.76%  |
| Toshiba             | 4         | 4      | 7.84%   |
| SanDisk             | 4         | 5      | 7.84%   |
| Kingston            | 3         | 3      | 5.88%   |
| Crucial             | 3         | 3      | 5.88%   |
| SK hynix            | 2         | 2      | 3.92%   |
| LITEONIT            | 2         | 2      | 3.92%   |
| Intel               | 2         | 3      | 3.92%   |
| Team                | 1         | 1      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| MyDigitalSSD        | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| Lexar               | 1         | 1      | 1.96%   |
| KingFast            | 1         | 1      | 1.96%   |
| INDMEM              | 1         | 1      | 1.96%   |
| Gigabyte Technology | 1         | 1      | 1.96%   |
| Dogfish             | 1         | 1      | 1.96%   |
| Corsair             | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| Apacer              | 1         | 1      | 1.96%   |
| ADATA SU            | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 45        | 55     | 32.37%  |
| HDD     | 44        | 118    | 31.65%  |
| SSD     | 43        | 60     | 30.94%  |
| Unknown | 4         | 4      | 2.88%   |
| MMC     | 3         | 3      | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 173    | 55.81%  |
| NVMe | 45        | 55     | 34.88%  |
| SAS  | 9         | 9      | 6.98%   |
| MMC  | 3         | 3      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 73     | 47.37%  |
| 0.51-1.0   | 28        | 46     | 29.47%  |
| 1.01-2.0   | 12        | 18     | 12.63%  |
| 3.01-4.0   | 6         | 25     | 6.32%   |
| 10.01-20.0 | 2         | 3      | 2.11%   |
| 2.01-3.0   | 1         | 1      | 1.05%   |
| 4.01-10.0  | 1         | 12     | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 27.1%   |
| 251-500        | 27        | 25.23%  |
| 501-1000       | 17        | 15.89%  |
| 1001-2000      | 12        | 11.21%  |
| More than 3000 | 8         | 7.48%   |
| 51-100         | 6         | 5.61%   |
| 2001-3000      | 5         | 4.67%   |
| Unknown        | 2         | 1.87%   |
| 1-20           | 1         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 38        | 35.19%  |
| 21-50          | 23        | 21.3%   |
| 51-100         | 13        | 12.04%  |
| 101-250        | 9         | 8.33%   |
| 501-1000       | 8         | 7.41%   |
| 251-500        | 7         | 6.48%   |
| More than 3000 | 4         | 3.7%    |
| 1001-2000      | 3         | 2.78%   |
| Unknown        | 2         | 1.85%   |
| 2001-3000      | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B1 1TB             | 1         | 2      | 7.14%   |
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 7.14%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 7.14%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 7.14%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 7.14%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 7.14%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 7.14%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 7.14%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 7.14%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 7.14%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 7.14%   |
| Hitachi HDS725050KLA360 500GB         | 1         | 1      | 7.14%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 7.14%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 16     | 42.86%  |
| Hitachi | 3         | 3      | 21.43%  |
| WDC     | 2         | 6      | 14.29%  |
| Toshiba | 1         | 1      | 7.14%   |
| IBM     | 1         | 1      | 7.14%   |
| Corsair | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 16     | 46.15%  |
| Hitachi | 3         | 3      | 23.08%  |
| WDC     | 2         | 6      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| IBM     | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 27     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 67        | 145    | 54.47%  |
| Detected | 43        | 66     | 34.96%  |
| Malfunc  | 12        | 28     | 9.76%   |
| Failed   | 1         | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 71        | 48.97%  |
| AMD                          | 22        | 15.17%  |
| Samsung Electronics          | 15        | 10.34%  |
| Phison Electronics           | 4         | 2.76%   |
| LSI Logic / Symbios Logic    | 4         | 2.76%   |
| Kingston Technology Company  | 4         | 2.76%   |
| SanDisk                      | 3         | 2.07%   |
| Broadcom / LSI               | 3         | 2.07%   |
| Toshiba America Info Systems | 2         | 1.38%   |
| SK hynix                     | 2         | 1.38%   |
| Realtek Semiconductor        | 2         | 1.38%   |
| Micron Technology            | 2         | 1.38%   |
| ASMedia Technology           | 2         | 1.38%   |
| VIA Technologies             | 1         | 0.69%   |
| Union Memory (Shenzhen)      | 1         | 0.69%   |
| Shenzhen Longsys Electronics | 1         | 0.69%   |
| Micron/Crucial Technology    | 1         | 0.69%   |
| Marvell Technology Group     | 1         | 0.69%   |
| JMicron Technology           | 1         | 0.69%   |
| Hewlett-Packard              | 1         | 0.69%   |
| ADATA Technology             | 1         | 0.69%   |
| Adaptec                      | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 8.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 4.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 4.22%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 3.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.41%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.81%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 1.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 1.2%    |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 1.2%    |
| Micron Non-Volatile memory controller                                                   | 2         | 1.2%    |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 1.2%    |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.2%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.2%    |
| Intel SSD 660P Series                                                                   | 2         | 1.2%    |
| Intel Non-Volatile memory controller                                                    | 2         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.2%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.2%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.2%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.2%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.2%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 1.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.2%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 68        | 45.95%  |
| NVMe | 45        | 30.41%  |
| RAID | 16        | 10.81%  |
| IDE  | 15        | 10.14%  |
| SAS  | 3         | 2.03%   |
| SCSI | 1         | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 79        | 73.83%  |
| AMD    | 27        | 25.23%  |
| ARM    | 1         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 3.74%   |
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 1.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.87%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.87%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 0.93%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 0.93%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.93%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.93%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.93%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 0.93%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1         | 0.93%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.93%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.93%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 0.93%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 0.93%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.93%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.93%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.93%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 0.93%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.93%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.93%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.93%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.93%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.93%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.93%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.93%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 0.93%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 0.93%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 0.93%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.93%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 24        | 22.43%  |
| Other                   | 16        | 14.95%  |
| Intel Core i5           | 14        | 13.08%  |
| Intel Xeon              | 11        | 10.28%  |
| AMD Ryzen 5             | 7         | 6.54%   |
| Intel Core i3           | 5         | 4.67%   |
| AMD Ryzen 7             | 5         | 4.67%   |
| Intel Celeron           | 3         | 2.8%    |
| AMD Ryzen 9             | 3         | 2.8%    |
| AMD Ryzen Threadripper  | 2         | 1.87%   |
| AMD Ryzen 5 PRO         | 2         | 1.87%   |
| AMD FX                  | 2         | 1.87%   |
| Intel Xeon Silver       | 1         | 0.93%   |
| Intel Xeon Gold         | 1         | 0.93%   |
| Intel Pentium Silver    | 1         | 0.93%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Pentium Dual      | 1         | 0.93%   |
| Intel Core i9           | 1         | 0.93%   |
| Intel Core 2 Quad       | 1         | 0.93%   |
| Intel Core 2 Duo        | 1         | 0.93%   |
| AMD Ryzen Embedded      | 1         | 0.93%   |
| AMD Ryzen 7 PRO         | 1         | 0.93%   |
| AMD Ryzen 3             | 1         | 0.93%   |
| AMD Phenom II X6        | 1         | 0.93%   |
| AMD A8                  | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 37        | 34.58%  |
| 2      | 20        | 18.69%  |
| 6      | 19        | 17.76%  |
| 8      | 15        | 14.02%  |
| 12     | 5         | 4.67%   |
| 16     | 3         | 2.8%    |
| 10     | 2         | 1.87%   |
| 32     | 1         | 0.93%   |
| 28     | 1         | 0.93%   |
| 24     | 1         | 0.93%   |
| 14     | 1         | 0.93%   |
| 3      | 1         | 0.93%   |
| 1      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 92.52%  |
| 2      | 8         | 7.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 84        | 78.5%   |
| 1      | 23        | 21.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 12        | 11.21%  |
| 0x806c1    | 6         | 5.61%   |
| 0x806ec    | 5         | 4.67%   |
| 0x506e3    | 5         | 4.67%   |
| 0x206a7    | 5         | 4.67%   |
| 0x306a9    | 4         | 3.74%   |
| 0x0a50000c | 4         | 3.74%   |
| 0xa0652    | 3         | 2.8%    |
| 0xa0671    | 2         | 1.87%   |
| 0xa0655    | 2         | 1.87%   |
| 0x906a3    | 2         | 1.87%   |
| 0x90675    | 2         | 1.87%   |
| 0x706a8    | 2         | 1.87%   |
| 0x50654    | 2         | 1.87%   |
| 0x406f1    | 2         | 1.87%   |
| 0x40651    | 2         | 1.87%   |
| 0x306e4    | 2         | 1.87%   |
| 0x206c2    | 2         | 1.87%   |
| 0x106a5    | 2         | 1.87%   |
| 0x10676    | 2         | 1.87%   |
| 0x08608103 | 2         | 1.87%   |
| 0x08600106 | 2         | 1.87%   |
| 0x08600104 | 2         | 1.87%   |
| 0x06000852 | 2         | 1.87%   |
| Unknown    | 2         | 1.87%   |
| 0xa0653    | 1         | 0.93%   |
| 0x906ed    | 1         | 0.93%   |
| 0x906ea    | 1         | 0.93%   |
| 0x906a4    | 1         | 0.93%   |
| 0x90672    | 1         | 0.93%   |
| 0x806e9    | 1         | 0.93%   |
| 0x706a1    | 1         | 0.93%   |
| 0x6fd      | 1         | 0.93%   |
| 0x50657    | 1         | 0.93%   |
| 0x406e3    | 1         | 0.93%   |
| 0x306f2    | 1         | 0.93%   |
| 0x206d7    | 1         | 0.93%   |
| 0x1067a    | 1         | 0.93%   |
| 0x10677    | 1         | 0.93%   |
| 0x0a50000d | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 16        | 14.95%  |
| Skylake          | 9         | 8.41%   |
| Zen 3            | 8         | 7.48%   |
| KabyLake         | 8         | 7.48%   |
| Zen 2            | 7         | 6.54%   |
| TigerLake        | 6         | 5.61%   |
| SandyBridge      | 6         | 5.61%   |
| IvyBridge        | 6         | 5.61%   |
| CometLake        | 6         | 5.61%   |
| Alderlake Hybrid | 6         | 5.61%   |
| Penryn           | 4         | 3.74%   |
| Zen+             | 3         | 2.8%    |
| Piledriver       | 3         | 2.8%    |
| Goldmont plus    | 3         | 2.8%    |
| Unknown          | 3         | 2.8%    |
| Zen              | 2         | 1.87%   |
| Westmere         | 2         | 1.87%   |
| Nehalem          | 2         | 1.87%   |
| Icelake          | 2         | 1.87%   |
| Broadwell        | 2         | 1.87%   |
| K10              | 1         | 0.93%   |
| Excavator        | 1         | 0.93%   |
| Core             | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 55        | 41.98%  |
| Nvidia                     | 45        | 34.35%  |
| AMD                        | 23        | 17.56%  |
| Matrox Electronics Systems | 4         | 3.05%   |
| ASPEED Technology          | 4         | 3.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 4.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 3.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.01%   |
| ASPEED Technology ASPEED Graphics Family                                    | 4         | 3.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 3.01%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3         | 2.26%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 2.26%   |
| Intel HD Graphics 530                                                       | 3         | 2.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 2.26%   |
| AMD Renoir                                                                  | 3         | 2.26%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 1.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.5%    |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 1.5%    |
| Matrox Electronics Systems G200eR2                                          | 2         | 1.5%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2         | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.5%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 1.5%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 1.5%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.5%    |
| AMD Lucienne                                                                | 2         | 1.5%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.5%    |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.75%   |
| Nvidia TU117GL [T600]                                                       | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.75%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 0.75%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.75%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 35        | 32.71%  |
| 1 x Nvidia      | 23        | 21.5%   |
| Intel + Nvidia  | 17        | 15.89%  |
| 1 x AMD         | 17        | 15.89%  |
| 1 x Matrox      | 3         | 2.8%    |
| 1 x ASPEED      | 3         | 2.8%    |
| 2 x AMD         | 2         | 1.87%   |
| Intel + AMD     | 2         | 1.87%   |
| AMD + Nvidia    | 2         | 1.87%   |
| Other           | 1         | 0.93%   |
| Nvidia + Matrox | 1         | 0.93%   |
| Nvidia + ASPEED | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 83        | 77.57%  |
| Proprietary | 17        | 15.89%  |
| Unknown     | 7         | 6.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 48.6%   |
| 0.01-0.5   | 16        | 14.95%  |
| 1.01-2.0   | 14        | 13.08%  |
| 3.01-4.0   | 10        | 9.35%   |
| 0.51-1.0   | 7         | 6.54%   |
| 5.01-6.0   | 3         | 2.8%    |
| 7.01-8.0   | 2         | 1.87%   |
| 8.01-16.0  | 2         | 1.87%   |
| 32.01-64.0 | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 15        | 13.16%  |
| Samsung Electronics  | 12        | 10.53%  |
| LG Display           | 10        | 8.77%   |
| AU Optronics         | 10        | 8.77%   |
| BOE                  | 8         | 7.02%   |
| Goldstar             | 7         | 6.14%   |
| Chimei Innolux       | 7         | 6.14%   |
| Acer                 | 6         | 5.26%   |
| Philips              | 5         | 4.39%   |
| AOC                  | 4         | 3.51%   |
| Ancor Communications | 4         | 3.51%   |
| Iiyama               | 3         | 2.63%   |
| Sharp                | 2         | 1.75%   |
| SGT                  | 2         | 1.75%   |
| Hewlett-Packard      | 2         | 1.75%   |
| BenQ                 | 2         | 1.75%   |
| ASUSTek Computer     | 2         | 1.75%   |
| Vizio                | 1         | 0.88%   |
| Sony                 | 1         | 0.88%   |
| PANDA                | 1         | 0.88%   |
| Panasonic            | 1         | 0.88%   |
| OEM                  | 1         | 0.88%   |
| NEC Computers        | 1         | 0.88%   |
| Lenovo               | 1         | 0.88%   |
| IBM                  | 1         | 0.88%   |
| HUAWEI               | 1         | 0.88%   |
| HCL                  | 1         | 0.88%   |
| Gigabyte Technology  | 1         | 0.88%   |
| Eizo                 | 1         | 0.88%   |
| ADR                  | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.69%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.85%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1         | 0.85%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| SGT HS160PC SGT1600 1920x1080 354x199mm 16.0-inch                     | 1         | 0.85%   |
| SGT HDMI SGT1560 1920x1080 330x220mm 15.6-inch                        | 1         | 0.85%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1         | 0.85%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1         | 0.85%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 0.85%   |
| Samsung Electronics LF27T35 SAM7080 1920x1080 598x337mm 27.0-inch     | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 0.85%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 0.85%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.85%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch              | 1         | 0.85%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.85%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 0.85%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 0.85%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 0.85%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 0.85%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 1         | 0.85%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1         | 0.85%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 46.73%  |
| 1366x768 (WXGA)    | 8         | 7.48%   |
| 2560x1440 (QHD)    | 7         | 6.54%   |
| 3840x2160 (4K)     | 5         | 4.67%   |
| 1920x1200 (WUXGA)  | 5         | 4.67%   |
| 1600x900 (HD+)     | 5         | 4.67%   |
| 1280x1024 (SXGA)   | 5         | 4.67%   |
| 3840x1080          | 3         | 2.8%    |
| 3440x1440          | 3         | 2.8%    |
| 1680x1050 (WSXGA+) | 3         | 2.8%    |
| 2560x1080          | 2         | 1.87%   |
| 1920x540           | 2         | 1.87%   |
| 1440x900 (WXGA+)   | 2         | 1.87%   |
| Unknown            | 2         | 1.87%   |
| 3840x2400          | 1         | 0.93%   |
| 2240x1400          | 1         | 0.93%   |
| 2160x1440          | 1         | 0.93%   |
| 1280x768           | 1         | 0.93%   |
| 1024x768 (XGA)     | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 21.24%  |
| 27      | 14        | 12.39%  |
| 24      | 12        | 10.62%  |
| 14      | 12        | 10.62%  |
| 17      | 8         | 7.08%   |
| 23      | 6         | 5.31%   |
| 13      | 6         | 5.31%   |
| 34      | 5         | 4.42%   |
| 21      | 5         | 4.42%   |
| 31      | 4         | 3.54%   |
| 19      | 3         | 2.65%   |
| 22      | 2         | 1.77%   |
| 20      | 2         | 1.77%   |
| Unknown | 2         | 1.77%   |
| 65      | 1         | 0.88%   |
| 49      | 1         | 0.88%   |
| 48      | 1         | 0.88%   |
| 40      | 1         | 0.88%   |
| 28      | 1         | 0.88%   |
| 25      | 1         | 0.88%   |
| 18      | 1         | 0.88%   |
| 16      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 37.5%   |
| 501-600     | 31        | 27.68%  |
| 401-500     | 14        | 12.5%   |
| 701-800     | 5         | 4.46%   |
| 601-700     | 5         | 4.46%   |
| 351-400     | 5         | 4.46%   |
| 201-300     | 4         | 3.57%   |
| 1001-1500   | 3         | 2.68%   |
| Unknown     | 2         | 1.79%   |
| 801-900     | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 74%     |
| 16/10   | 10        | 10%     |
| 5/4     | 5         | 5%      |
| 21/9    | 4         | 4%      |
| 3/2     | 3         | 3%      |
| 32/9    | 2         | 2%      |
| 4/3     | 1         | 1%      |
| Unknown | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 22.52%  |
| 201-250        | 20        | 18.02%  |
| 81-90          | 16        | 14.41%  |
| 301-350        | 14        | 12.61%  |
| 351-500        | 9         | 8.11%   |
| 151-200        | 6         | 5.41%   |
| 141-150        | 5         | 4.5%    |
| 121-130        | 4         | 3.6%    |
| 501-1000       | 4         | 3.6%    |
| 251-300        | 3         | 2.7%    |
| Unknown        | 2         | 1.8%    |
| More than 1000 | 1         | 0.9%    |
| 71-80          | 1         | 0.9%    |
| 91-100         | 1         | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 47        | 42.34%  |
| 121-160       | 34        | 30.63%  |
| 101-120       | 17        | 15.32%  |
| 161-240       | 6         | 5.41%   |
| More than 240 | 3         | 2.7%    |
| 1-50          | 2         | 1.8%    |
| Unknown       | 2         | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 65.42%  |
| 2     | 18        | 16.82%  |
| 0     | 15        | 14.02%  |
| 3     | 3         | 2.8%    |
| 4     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 68        | 44.44%  |
| Realtek Semiconductor     | 45        | 29.41%  |
| Qualcomm Atheros          | 7         | 4.58%   |
| Broadcom                  | 7         | 4.58%   |
| MediaTek                  | 5         | 3.27%   |
| Mellanox Technologies     | 3         | 1.96%   |
| Ralink Technology         | 2         | 1.31%   |
| Marvell Technology Group  | 2         | 1.31%   |
| Linksys                   | 2         | 1.31%   |
| Broadcom Limited          | 2         | 1.31%   |
| TP-Link                   | 1         | 0.65%   |
| Solarflare Communications | 1         | 0.65%   |
| Ralink                    | 1         | 0.65%   |
| Qualcomm                  | 1         | 0.65%   |
| Microsoft                 | 1         | 0.65%   |
| Lenovo                    | 1         | 0.65%   |
| Dell                      | 1         | 0.65%   |
| D-Link                    | 1         | 0.65%   |
| BUFFALO                   | 1         | 0.65%   |
| Aquantia                  | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 35        | 19.34%  |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 3.87%   |
| Intel Wireless 7260                                                                                                    | 6         | 3.31%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6         | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 5         | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 5         | 2.76%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 4         | 2.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 1.66%   |
| Intel I211 Gigabit Network Connection                                                                                  | 3         | 1.66%   |
| Intel Ethernet Controller I225-V                                                                                       | 3         | 1.66%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 3         | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 3         | 1.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 3         | 1.66%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 1.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 2         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 2         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 2         | 1.1%    |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 2         | 1.1%    |
| Intel Wireless 8260                                                                                                    | 2         | 1.1%    |
| Intel Wireless 3165                                                                                                    | 2         | 1.1%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 1.1%    |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 1.1%    |
| Intel Ethernet Connection (17) I219-V                                                                                  | 2         | 1.1%    |
| Intel Ethernet Connection (14) I219-V                                                                                  | 2         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 2         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 2         | 1.1%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                                    | 1         | 0.55%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                                | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 1         | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 1         | 0.55%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 0.55%   |
| Ralink RT3071 Wireless Adapter                                                                                         | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 58.21%  |
| Realtek Semiconductor | 6         | 8.96%   |
| Qualcomm Atheros      | 6         | 8.96%   |
| MediaTek              | 5         | 7.46%   |
| Ralink Technology     | 2         | 2.99%   |
| Linksys               | 2         | 2.99%   |
| TP-Link               | 1         | 1.49%   |
| Ralink                | 1         | 1.49%   |
| Microsoft             | 1         | 1.49%   |
| Dell                  | 1         | 1.49%   |
| BUFFALO               | 1         | 1.49%   |
| Broadcom Limited      | 1         | 1.49%   |
| Broadcom              | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                                                | 6         | 8.7%    |
| Intel Wi-Fi 6 AX200                                                                                                | 6         | 8.7%    |
| Intel Wi-Fi 6 AX201                                                                                                | 4         | 5.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 3         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 3         | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 3         | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                 | 2         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 2         | 2.9%    |
| Ralink MT7601U Wireless Adapter                                                                                    | 2         | 2.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 2.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                            | 2         | 2.9%    |
| Intel Wireless 8260                                                                                                | 2         | 2.9%    |
| Intel Wireless 3165                                                                                                | 2         | 2.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 2         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 2.9%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                                | 1         | 1.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                            | 1         | 1.45%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.45%   |
| Realtek 802.11ac NIC                                                                                               | 1         | 1.45%   |
| Ralink RT3071 Wireless Adapter                                                                                     | 1         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                   | 1         | 1.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                   | 1         | 1.45%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                | 1         | 1.45%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                | 1         | 1.45%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                                     | 1         | 1.45%   |
| Intel Wireless 8265 / 8275                                                                                         | 1         | 1.45%   |
| Intel Wireless 7265                                                                                                | 1         | 1.45%   |
| Intel Wireless 3160                                                                                                | 1         | 1.45%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.45%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.45%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.45%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                                                           | 1         | 1.45%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                                         | 1         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                                | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 45        | 43.69%  |
| Realtek Semiconductor     | 42        | 40.78%  |
| Broadcom                  | 7         | 6.8%    |
| Marvell Technology Group  | 2         | 1.94%   |
| Solarflare Communications | 1         | 0.97%   |
| Qualcomm Atheros          | 1         | 0.97%   |
| Qualcomm                  | 1         | 0.97%   |
| Lenovo                    | 1         | 0.97%   |
| D-Link                    | 1         | 0.97%   |
| Broadcom Limited          | 1         | 0.97%   |
| Aquantia                  | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 32.11%  |
| Intel Ethernet Connection I217-LM                                 | 7         | 6.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.59%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.75%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 2.75%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 1.83%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.83%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.83%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 1.83%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.83%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.92%   |
| Qualcomm FP3                                                      | 1         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.92%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.92%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.92%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.92%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.92%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.92%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.92%   |
| Intel Ethernet Controller X550                                    | 1         | 0.92%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.92%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.92%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.92%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.92%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.92%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.92%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.92%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 0.92%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 0.92%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.92%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 95        | 59.01%  |
| WiFi     | 63        | 39.13%  |
| Unknown  | 3         | 1.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 61.68%  |
| WiFi     | 40        | 37.38%  |
| Unknown  | 1         | 0.93%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 44.86%  |
| 1     | 46        | 42.99%  |
| 3     | 5         | 4.67%   |
| 5     | 3         | 2.8%    |
| 0     | 2         | 1.87%   |
| 66    | 1         | 0.93%   |
| 8     | 1         | 0.93%   |
| 4     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 86        | 80.37%  |
| Yes  | 21        | 19.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 61.11%  |
| Foxconn / Hon Hai               | 4         | 7.41%   |
| Realtek Semiconductor           | 3         | 5.56%   |
| Qualcomm Atheros Communications | 3         | 5.56%   |
| MediaTek                        | 2         | 3.7%    |
| Cambridge Silicon Radio         | 2         | 3.7%    |
| Broadcom                        | 2         | 3.7%    |
| Ralink                          | 1         | 1.85%   |
| Integrated System Solution      | 1         | 1.85%   |
| IMC Networks                    | 1         | 1.85%   |
| Hewlett-Packard                 | 1         | 1.85%   |
| Dell                            | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 13        | 24.07%  |
| Intel Bluetooth Device                                | 11        | 20.37%  |
| Intel AX200 Bluetooth                                 | 6         | 11.11%  |
| Foxconn / Hon Hai Wireless_Device                     | 4         | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 5.56%   |
| Realtek Bluetooth Radio                               | 2         | 3.7%    |
| MediaTek Wireless_Device                              | 2         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.85%   |
| Ralink RT3290 Bluetooth                               | 1         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 1.85%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.85%   |
| IMC Networks Bluetooth Device                         | 1         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.85%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 69        | 46%     |
| Nvidia              | 35        | 23.33%  |
| AMD                 | 29        | 19.33%  |
| C-Media Electronics | 4         | 2.67%   |
| Logitech            | 2         | 1.33%   |
| GN Netcom           | 2         | 1.33%   |
| Creative Technology | 2         | 1.33%   |
| Conexant Systems    | 2         | 1.33%   |
| Unknown             | 1         | 0.67%   |
| Nektar              | 1         | 0.67%   |
| Huawei Technologies | 1         | 0.67%   |
| Hewlett-Packard     | 1         | 0.67%   |
| ASUSTek Computer    | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 13        | 7.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12        | 6.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 10        | 5.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9         | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7         | 3.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 3.39%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 2.82%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5         | 2.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 2.26%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4         | 2.26%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 2.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3         | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 1.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 3         | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 1.69%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 1.13%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 1.13%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 1.13%   |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 1.13%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 1.13%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2         | 1.13%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2         | 1.13%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2         | 1.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 1.13%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2         | 1.13%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 1.13%   |
| C-Media Electronics TONOR TC-777 Audio Device                                     | 2         | 1.13%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 1.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 1.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.13%   |
| Unknown Realtek USB Audio Rear                                                    | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 23.68%  |
| Micron Technology   | 14        | 18.42%  |
| SK hynix            | 7         | 9.21%   |
| G.Skill             | 6         | 7.89%   |
| Corsair             | 6         | 7.89%   |
| Unknown             | 5         | 6.58%   |
| Kingston            | 5         | 6.58%   |
| Crucial             | 4         | 5.26%   |
| A-DATA Technology   | 2         | 2.63%   |
| Unknown (ABCD)      | 1         | 1.32%   |
| Team                | 1         | 1.32%   |
| Ramaxel Technology  | 1         | 1.32%   |
| PNY                 | 1         | 1.32%   |
| Patriot             | 1         | 1.32%   |
| Magnum Tech         | 1         | 1.32%   |
| Lexar Co Limited    | 1         | 1.32%   |
| Lexar               | 1         | 1.32%   |
| Gold Key            | 1         | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 2.53%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                        | 1         | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.27%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 1.27%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.27%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 1.27%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.27%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 1.27%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.27%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.27%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.27%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.27%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.27%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.27%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 1.27%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.27%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.27%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.27%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s             | 1         | 1.27%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 1.27%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 1.27%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.27%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s              | 1         | 1.27%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 1.27%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1.27%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s             | 1         | 1.27%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.27%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 1.27%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s             | 1         | 1.27%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s                 | 1         | 1.27%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.27%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.27%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                         | 1         | 1.27%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                         | 1         | 1.27%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s              | 1         | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 60.87%  |
| DDR3    | 18        | 26.09%  |
| LPDDR4  | 3         | 4.35%   |
| DDR5    | 2         | 2.9%    |
| DDR2    | 2         | 2.9%    |
| LPDDR5  | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 36        | 52.17%  |
| SODIMM       | 28        | 40.58%  |
| Row Of Chips | 4         | 5.8%    |
| RIMM         | 1         | 1.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 48.65%  |
| 16384 | 12        | 16.22%  |
| 32768 | 9         | 12.16%  |
| 4096  | 9         | 12.16%  |
| 1024  | 5         | 6.76%   |
| 2048  | 3         | 4.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 20        | 27.03%  |
| 2667  | 11        | 14.86%  |
| 1600  | 8         | 10.81%  |
| 2400  | 6         | 8.11%   |
| 2133  | 4         | 5.41%   |
| 1333  | 3         | 4.05%   |
| 667   | 3         | 4.05%   |
| 4800  | 2         | 2.7%    |
| 1066  | 2         | 2.7%    |
| 6400  | 1         | 1.35%   |
| 4267  | 1         | 1.35%   |
| 4266  | 1         | 1.35%   |
| 3733  | 1         | 1.35%   |
| 3666  | 1         | 1.35%   |
| 3600  | 1         | 1.35%   |
| 3400  | 1         | 1.35%   |
| 3333  | 1         | 1.35%   |
| 3266  | 1         | 1.35%   |
| 3100  | 1         | 1.35%   |
| 3000  | 1         | 1.35%   |
| 2666  | 1         | 1.35%   |
| 2200  | 1         | 1.35%   |
| 1866  | 1         | 1.35%   |
| 1800  | 1         | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series    | 1         | 33.33%  |
| Seiko Epson Printer           | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP OfficeJet 6110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 16%     |
| IMC Networks                           | 6         | 12%     |
| Microdia                               | 5         | 10%     |
| Syntek                                 | 4         | 8%      |
| Logitech                               | 4         | 8%      |
| Sunplus Innovation Technology          | 3         | 6%      |
| Luxvisions Innotech Limited            | 3         | 6%      |
| Realtek Semiconductor                  | 2         | 4%      |
| Generalplus Technology                 | 2         | 4%      |
| Acer                                   | 2         | 4%      |
| Suyin                                  | 1         | 2%      |
| Quanta                                 | 1         | 2%      |
| Lite-On Technology                     | 1         | 2%      |
| Lenovo                                 | 1         | 2%      |
| KYE Systems (Mouse Systems)            | 1         | 2%      |
| Intel                                  | 1         | 2%      |
| Huawei Technologies                    | 1         | 2%      |
| Elgato Systems                         | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2%      |
| Apple                                  | 1         | 2%      |
| 2M UVC CAMERA                          | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 5         | 10%     |
| Microdia Integrated_Webcam_HD                                              | 4         | 8%      |
| Syntek Lenovo EasyCamera                                                   | 2         | 4%      |
| Syntek Integrated Camera                                                   | 2         | 4%      |
| Logitech HD Pro Webcam C920                                                | 2         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 4%      |
| IMC Networks Integrated Camera                                             | 2         | 4%      |
| Generalplus GENERAL WEBCAM                                                 | 2         | 4%      |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2%      |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 2%      |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 2%      |
| Sunplus FHD Camera Microphone                                              | 1         | 2%      |
| Realtek Integrated_Webcam_HD                                               | 1         | 2%      |
| Realtek EasyCamera                                                         | 1         | 2%      |
| Quanta HP Webcam                                                           | 1         | 2%      |
| Microdia Integrated_Webcam_FHD                                             | 1         | 2%      |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 2%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2%      |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 2%      |
| Logitech Webcam C270                                                       | 1         | 2%      |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 2%      |
| Lite-On HP HD Webcam                                                       | 1         | 2%      |
| Lenovo UVC Camera                                                          | 1         | 2%      |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 1         | 2%      |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 2%      |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 2%      |
| IMC Networks HD Camera                                                     | 1         | 2%      |
| Huawei UVC Camera                                                          | 1         | 2%      |
| Elgato Systems Elgato Facecam                                              | 1         | 2%      |
| Chicony Integrated HP HD Webcam                                            | 1         | 2%      |
| Chicony HP HD Camera                                                       | 1         | 2%      |
| Chicony HD WebCam                                                          | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2%      |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 2%      |
| Acer Integrated RGB Camera                                                 | 1         | 2%      |
| Acer Integrated Camera                                                     | 1         | 2%      |
| 2M UVC CAMERA NexiGo N660 FHD Webcam                                       | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Synaptics                  | 5         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| LighTuning Technology      | 2         | 13.33%  |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 13.33%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 6.67%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                        | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 6.67%   |
| LighTuning Fingerprint Sensor                              | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 6.67%   |
| AuthenTec AES2810                                          | 1         | 6.67%   |
| Unknown                                                    | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 59        | 55.14%  |
| 1     | 34        | 31.78%  |
| 2     | 10        | 9.35%   |
| 3     | 2         | 1.87%   |
| 5     | 1         | 0.93%   |
| 4     | 1         | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 23.81%  |
| Graphics card            | 12        | 19.05%  |
| Net/wireless             | 9         | 14.29%  |
| Unassigned class         | 6         | 9.52%   |
| Communication controller | 5         | 7.94%   |
| Chipcard                 | 3         | 4.76%   |
| Network                  | 2         | 3.17%   |
| Net/ethernet             | 2         | 3.17%   |
| Multimedia controller    | 2         | 3.17%   |
| Storage/raid             | 1         | 1.59%   |
| Storage                  | 1         | 1.59%   |
| Sound                    | 1         | 1.59%   |
| Firewire controller      | 1         | 1.59%   |
| Dvb card                 | 1         | 1.59%   |
| Card reader              | 1         | 1.59%   |
| Bluetooth                | 1         | 1.59%   |

