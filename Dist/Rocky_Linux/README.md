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

Total: 184

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | G752VM                      | Notebook    | [b518236bd7](https://linux-hardware.org/?probe=b518236bd7) | Jun 21, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2310257292](https://linux-hardware.org/?probe=2310257292) | Jun 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ee6f9906b5](https://linux-hardware.org/?probe=ee6f9906b5) | Jun 19, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [47b86a7e60](https://linux-hardware.org/?probe=47b86a7e60) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [da8705e5a7](https://linux-hardware.org/?probe=da8705e5a7) | May 31, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [a2e80bffac](https://linux-hardware.org/?probe=a2e80bffac) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0633ac39d](https://linux-hardware.org/?probe=d0633ac39d) | May 19, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [f82952db4b](https://linux-hardware.org/?probe=f82952db4b) | May 14, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| Beelink       | BT3 PRO                     | Notebook    | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| AZW           | MINI S                      | Desktop     | [d7ee12a01b](https://linux-hardware.org/?probe=d7ee12a01b) | May 08, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [5cff94f71e](https://linux-hardware.org/?probe=5cff94f71e) | May 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Dell          | 0D735T A00                  | Desktop     | [3070f4e7da](https://linux-hardware.org/?probe=3070f4e7da) | May 02, 2023 |
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
| Rocky Linux 9.1 | 42        | 29.58%  |
| Rocky Linux 8.5 | 31        | 21.83%  |
| Rocky Linux 9.0 | 19        | 13.38%  |
| Rocky Linux 8.4 | 19        | 13.38%  |
| Rocky Linux 8.7 | 12        | 8.45%   |
| Rocky Linux 8.6 | 11        | 7.75%   |
| Rocky Linux 9.2 | 4         | 2.82%   |
| Rocky Linux 8.8 | 2         | 1.41%   |
| Rocky Linux 8.3 | 2         | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 140       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 17        | 11.56%  |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 8.84%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 5.44%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 7         | 4.76%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 6         | 4.08%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 4.08%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 3.4%    |
| 5.14.0-162.23.1.el9_1.x86_64     | 5         | 3.4%    |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 5         | 3.4%    |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 2.72%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 2.72%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 4         | 2.72%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 4         | 2.72%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 2.72%   |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 2.04%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 3         | 2.04%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 3         | 2.04%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 3         | 2.04%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 2.04%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 2         | 1.36%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 1.36%   |
| 4.18.0-425.19.2.el8_7.x86_64     | 2         | 1.36%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 1.36%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 1.36%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 1.36%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 1.36%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 1.36%   |
| 4.18.0-305.el8.x86_64            | 2         | 1.36%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 1.36%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 1.36%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 1.36%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 1.36%   |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 0.68%   |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 0.68%   |
| 6.1.8-1.el9.elrepo.x86_64        | 1         | 0.68%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1         | 0.68%   |
| 6.0.10_tkg_bmq                   | 1         | 0.68%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1         | 0.68%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 0.68%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 69        | 48.94%  |
| 5.14.0  | 61        | 43.26%  |
| 6.0.10  | 2         | 1.42%   |
| 6.2.12  | 1         | 0.71%   |
| 6.2.10  | 1         | 0.71%   |
| 6.1.8   | 1         | 0.71%   |
| 6.1.6   | 1         | 0.71%   |
| 5.4.157 | 1         | 0.71%   |
| 5.16.15 | 1         | 0.71%   |
| 5.14.1  | 1         | 0.71%   |
| 5.10.89 | 1         | 0.71%   |
| 5.10.52 | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 69        | 48.94%  |
| 5.14    | 62        | 43.97%  |
| 6.2     | 2         | 1.42%   |
| 6.1     | 2         | 1.42%   |
| 6.0     | 2         | 1.42%   |
| 5.10    | 2         | 1.42%   |
| 5.4     | 1         | 0.71%   |
| 5.16    | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 139       | 99.29%  |
| aarch64 | 1         | 0.71%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 98        | 70%     |
| Unknown       | 19        | 13.57%  |
| KDE5          | 10        | 7.14%   |
| MATE          | 5         | 3.57%   |
| GNOME Classic | 4         | 2.86%   |
| XFCE          | 3         | 2.14%   |
| X-Cinnamon    | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 79        | 55.24%  |
| X11     | 44        | 30.77%  |
| Unknown | 9         | 6.29%   |
| Tty     | 8         | 5.59%   |
| Web     | 3         | 2.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 64        | 45.71%  |
| Unknown | 63        | 45%     |
| SDDM    | 9         | 6.43%   |
| LightDM | 4         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 89        | 63.57%  |
| ru_RU   | 6         | 4.29%   |
| en_CA   | 6         | 4.29%   |
| en_AU   | 5         | 3.57%   |
| C       | 4         | 2.86%   |
| en_ZA   | 3         | 2.14%   |
| en_IL   | 3         | 2.14%   |
| Unknown | 3         | 2.14%   |
| en_SG   | 2         | 1.43%   |
| en_GB   | 2         | 1.43%   |
| de_DE   | 2         | 1.43%   |
| de_AT   | 2         | 1.43%   |
| zh_TW   | 1         | 0.71%   |
| pt_BR   | 1         | 0.71%   |
| pl_PL   | 1         | 0.71%   |
| ko_KR   | 1         | 0.71%   |
| ja_JP   | 1         | 0.71%   |
| it_IT   | 1         | 0.71%   |
| hu_HU   | 1         | 0.71%   |
| fr_FR   | 1         | 0.71%   |
| es_ES   | 1         | 0.71%   |
| es_CO   | 1         | 0.71%   |
| es_AR   | 1         | 0.71%   |
| en_IE   | 1         | 0.71%   |
| af_ZA   | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 92        | 65.25%  |
| BIOS | 49        | 34.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 118       | 84.29%  |
| Ext4 | 21        | 15%     |
| Ext3 | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 74        | 52.86%  |
| Unknown | 44        | 31.43%  |
| MBR     | 22        | 15.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 114       | 81.43%  |
| Yes       | 26        | 18.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 84.29%  |
| Yes       | 22        | 15.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 28        | 20%     |
| Lenovo                  | 24        | 17.14%  |
| ASUSTek Computer        | 22        | 15.71%  |
| Hewlett-Packard         | 20        | 14.29%  |
| Gigabyte Technology     | 8         | 5.71%   |
| MSI                     | 7         | 5%      |
| AZW                     | 4         | 2.86%   |
| Intel                   | 3         | 2.14%   |
| ASRock                  | 3         | 2.14%   |
| Unknown                 | 3         | 2.14%   |
| Toshiba                 | 2         | 1.43%   |
| Supermicro              | 2         | 1.43%   |
| Acer                    | 2         | 1.43%   |
| Techvision              | 1         | 0.71%   |
| Sapphire                | 1         | 0.71%   |
| Raspberry Pi Foundation | 1         | 0.71%   |
| Positivo                | 1         | 0.71%   |
| NCR                     | 1         | 0.71%   |
| IBM                     | 1         | 0.71%   |
| HUAWEI                  | 1         | 0.71%   |
| HPE                     | 1         | 0.71%   |
| Google                  | 1         | 0.71%   |
| BESSTAR Tech            | 1         | 0.71%   |
| Beelink                 | 1         | 0.71%   |
| BANGHO                  | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 2.14%   |
| Dell PowerEdge R610                    | 2         | 1.43%   |
| Dell OptiPlex 9020                     | 2         | 1.43%   |
| AZW GTR                                | 2         | 1.43%   |
| Toshiba TECRA W50-A                    | 1         | 0.71%   |
| Toshiba Satellite E45-B                | 1         | 0.71%   |
| Techvision TVI7309X                    | 1         | 0.71%   |
| Supermicro SYS-5029P-WTR               | 1         | 0.71%   |
| Supermicro Super Server                | 1         | 0.71%   |
| Sapphire PE-AM2RS690V2                 | 1         | 0.71%   |
| RPi Raspberry Pi                       | 1         | 0.71%   |
| Positivo Mobile                        | 1         | 0.71%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 0.71%   |
| MSI MS-7D46                            | 1         | 0.71%   |
| MSI MS-7D25                            | 1         | 0.71%   |
| MSI MS-7B89                            | 1         | 0.71%   |
| MSI MS-7B78                            | 1         | 0.71%   |
| MSI MS-7A94                            | 1         | 0.71%   |
| MSI MS-7917                            | 1         | 0.71%   |
| MSI H510M PRO-E                        | 1         | 0.71%   |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 0.71%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 0.71%   |
| Lenovo ThinkPad W500 406132G           | 1         | 0.71%   |
| Lenovo ThinkPad T480 20L6S8B500        | 1         | 0.71%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV   | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 0.71%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK    | 1         | 0.71%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB   | 1         | 0.71%   |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 0.71%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 0.71%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.71%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 0.71%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.71%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 0.71%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 0.71%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 7.86%   |
| ASUS PRIME               | 9         | 6.43%   |
| Lenovo IdeaPad           | 7         | 5%      |
| Dell Precision           | 5         | 3.57%   |
| Dell PowerEdge           | 5         | 3.57%   |
| Dell OptiPlex            | 5         | 3.57%   |
| HP EliteBook             | 4         | 2.86%   |
| Dell Latitude            | 4         | 2.86%   |
| HP ZBook                 | 3         | 2.14%   |
| Dell XPS                 | 3         | 2.14%   |
| Dell Vostro              | 3         | 2.14%   |
| Dell Inspiron            | 3         | 2.14%   |
| ASUS ASUS                | 3         | 2.14%   |
| Unknown                  | 3         | 2.14%   |
| Lenovo Legion            | 2         | 1.43%   |
| Lenovo IdeaPadFlex       | 2         | 1.43%   |
| HP ProLiant              | 2         | 1.43%   |
| HP ProBook               | 2         | 1.43%   |
| HP Laptop                | 2         | 1.43%   |
| HP EliteDesk             | 2         | 1.43%   |
| AZW GTR                  | 2         | 1.43%   |
| ASUS ROG                 | 2         | 1.43%   |
| Acer Aspire              | 2         | 1.43%   |
| Toshiba TECRA            | 1         | 0.71%   |
| Toshiba Satellite        | 1         | 0.71%   |
| Techvision TVI7309X      | 1         | 0.71%   |
| Supermicro SYS-5029P-WTR | 1         | 0.71%   |
| Supermicro Super         | 1         | 0.71%   |
| Sapphire PE-AM2RS690V2   | 1         | 0.71%   |
| RPi Raspberry            | 1         | 0.71%   |
| Positivo Mobile          | 1         | 0.71%   |
| NCR xxxx-xxxx-xxxx       | 1         | 0.71%   |
| MSI MS-7D46              | 1         | 0.71%   |
| MSI MS-7D25              | 1         | 0.71%   |
| MSI MS-7B89              | 1         | 0.71%   |
| MSI MS-7B78              | 1         | 0.71%   |
| MSI MS-7A94              | 1         | 0.71%   |
| MSI MS-7917              | 1         | 0.71%   |
| MSI H510M                | 1         | 0.71%   |
| Lenovo ThinkStation      | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 22        | 15.71%  |
| 2020    | 17        | 12.14%  |
| 2022    | 15        | 10.71%  |
| 2018    | 15        | 10.71%  |
| 2019    | 11        | 7.86%   |
| 2011    | 11        | 7.86%   |
| 2014    | 10        | 7.14%   |
| 2013    | 9         | 6.43%   |
| 2015    | 8         | 5.71%   |
| 2012    | 6         | 4.29%   |
| 2010    | 4         | 2.86%   |
| 2017    | 3         | 2.14%   |
| 2009    | 3         | 2.14%   |
| 2008    | 3         | 2.14%   |
| 2016    | 2         | 1.43%   |
| Unknown | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 62        | 44.29%  |
| Notebook       | 57        | 40.71%  |
| Server         | 12        | 8.57%   |
| Mini pc        | 4         | 2.86%   |
| Convertible    | 3         | 2.14%   |
| System on chip | 1         | 0.71%   |
| Tablet         | 1         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 124       | 88.57%  |
| Enabled  | 16        | 11.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 99.29%  |
| Yes  | 1         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 34        | 24.11%  |
| 4.01-8.0        | 30        | 21.28%  |
| 32.01-64.0      | 29        | 20.57%  |
| 16.01-24.0      | 17        | 12.06%  |
| 64.01-256.0     | 10        | 7.09%   |
| 3.01-4.0        | 8         | 5.67%   |
| More than 256.0 | 4         | 2.84%   |
| 1.01-2.0        | 4         | 2.84%   |
| 24.01-32.0      | 3         | 2.13%   |
| 2.01-3.0        | 2         | 1.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 37        | 25.17%  |
| 4.01-8.0   | 35        | 23.81%  |
| 3.01-4.0   | 27        | 18.37%  |
| 1.01-2.0   | 23        | 15.65%  |
| 8.01-16.0  | 9         | 6.12%   |
| 0.51-1.0   | 7         | 4.76%   |
| 16.01-24.0 | 3         | 2.04%   |
| 32.01-64.0 | 2         | 1.36%   |
| 24.01-32.0 | 2         | 1.36%   |
| 0.01-0.5   | 2         | 1.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 58.16%  |
| 2      | 24        | 17.02%  |
| 3      | 12        | 8.51%   |
| 4      | 11        | 7.8%    |
| 6      | 3         | 2.13%   |
| 5      | 2         | 1.42%   |
| 19     | 1         | 0.71%   |
| 18     | 1         | 0.71%   |
| 17     | 1         | 0.71%   |
| 16     | 1         | 0.71%   |
| 14     | 1         | 0.71%   |
| 9      | 1         | 0.71%   |
| 8      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 72.14%  |
| Yes       | 39        | 27.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 90.07%  |
| No        | 14        | 9.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 58.87%  |
| No        | 58        | 41.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 50.35%  |
| No        | 70        | 49.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 37        | 26.43%  |
| Canada       | 9         | 6.43%   |
| Russia       | 8         | 5.71%   |
| Germany      | 7         | 5%      |
| Australia    | 6         | 4.29%   |
| Italy        | 5         | 3.57%   |
| South Africa | 4         | 2.86%   |
| Poland       | 4         | 2.86%   |
| Czechia      | 4         | 2.86%   |
| UK           | 3         | 2.14%   |
| Singapore    | 3         | 2.14%   |
| Israel       | 3         | 2.14%   |
| Hungary      | 3         | 2.14%   |
| France       | 3         | 2.14%   |
| Sweden       | 2         | 1.43%   |
| Spain        | 2         | 1.43%   |
| South Korea  | 2         | 1.43%   |
| Netherlands  | 2         | 1.43%   |
| Mexico       | 2         | 1.43%   |
| Indonesia    | 2         | 1.43%   |
| India        | 2         | 1.43%   |
| Brazil       | 2         | 1.43%   |
| Belgium      | 2         | 1.43%   |
| Austria      | 2         | 1.43%   |
| Argentina    | 2         | 1.43%   |
| Uzbekistan   | 1         | 0.71%   |
| UAE          | 1         | 0.71%   |
| Turkey       | 1         | 0.71%   |
| Taiwan       | 1         | 0.71%   |
| Switzerland  | 1         | 0.71%   |
| Slovakia     | 1         | 0.71%   |
| Saudi Arabia | 1         | 0.71%   |
| Portugal     | 1         | 0.71%   |
| Pakistan     | 1         | 0.71%   |
| Norway       | 1         | 0.71%   |
| Malaysia     | 1         | 0.71%   |
| Kazakhstan   | 1         | 0.71%   |
| Japan        | 1         | 0.71%   |
| Ireland      | 1         | 0.71%   |
| Finland      | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toronto                | 3         | 2.13%   |
| Singapore              | 3         | 2.13%   |
| Melbourne              | 3         | 2.13%   |
| Budapest               | 3         | 2.13%   |
| Vienna                 | 2         | 1.42%   |
| Prague                 | 2         | 1.42%   |
| Moscow                 | 2         | 1.42%   |
| Krakow                 | 2         | 1.42%   |
| Haifa                  | 2         | 1.42%   |
| Chicago                | 2         | 1.42%   |
| Centurion              | 2         | 1.42%   |
| Buckley                | 2         | 1.42%   |
| Berlin                 | 2         | 1.42%   |
| Adelaide               | 2         | 1.42%   |
| Žilina                | 1         | 0.71%   |
| Yogyakarta             | 1         | 0.71%   |
| Yekaterinburg          | 1         | 0.71%   |
| Xi'an                  | 1         | 0.71%   |
| Willowbrook            | 1         | 0.71%   |
| Wells                  | 1         | 0.71%   |
| Washington             | 1         | 0.71%   |
| Waltham                | 1         | 0.71%   |
| Voronezh               | 1         | 0.71%   |
| Vancouver              | 1         | 0.71%   |
| Urbana                 | 1         | 0.71%   |
| Troisdorf              | 1         | 0.71%   |
| Torrington             | 1         | 0.71%   |
| Tlaxcala City          | 1         | 0.71%   |
| Taoyuan City           | 1         | 0.71%   |
| Syracuse               | 1         | 0.71%   |
| St. John's             | 1         | 0.71%   |
| St Petersburg          | 1         | 0.71%   |
| Spokane                | 1         | 0.71%   |
| Split                  | 1         | 0.71%   |
| Sofia                  | 1         | 0.71%   |
| Sobral de Monte Agraco | 1         | 0.71%   |
| Smolensk               | 1         | 0.71%   |
| Senigallia             | 1         | 0.71%   |
| Semarang               | 1         | 0.71%   |
| Scarborough            | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 38        | 51     | 17.92%  |
| Seagate                     | 32        | 91     | 15.09%  |
| WDC                         | 28        | 55     | 13.21%  |
| Toshiba                     | 14        | 17     | 6.6%    |
| SanDisk                     | 9         | 11     | 4.25%   |
| Intel                       | 9         | 11     | 4.25%   |
| Hitachi                     | 9         | 14     | 4.25%   |
| Kingston                    | 8         | 8      | 3.77%   |
| Crucial                     | 6         | 7      | 2.83%   |
| Unknown                     | 5         | 5      | 2.36%   |
| SK hynix                    | 5         | 7      | 2.36%   |
| Micron Technology           | 4         | 4      | 1.89%   |
| Phison                      | 3         | 4      | 1.42%   |
| HGST                        | 3         | 3      | 1.42%   |
| A-DATA Technology           | 3         | 3      | 1.42%   |
| LITEONIT                    | 2         | 2      | 0.94%   |
| Lexar                       | 2         | 2      | 0.94%   |
| Corsair                     | 2         | 2      | 0.94%   |
| China                       | 2         | 2      | 0.94%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.47%   |
| UMIS                        | 1         | 1      | 0.47%   |
| Team                        | 1         | 1      | 0.47%   |
| StoreJet                    | 1         | 1      | 0.47%   |
| PNY                         | 1         | 1      | 0.47%   |
| Phison Electronics          | 1         | 16     | 0.47%   |
| MyDigitalSSD                | 1         | 1      | 0.47%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.47%   |
| LITEON                      | 1         | 1      | 0.47%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.47%   |
| KIOXIA                      | 1         | 1      | 0.47%   |
| Kingston Technology Company | 1         | 1      | 0.47%   |
| KingFast                    | 1         | 1      | 0.47%   |
| JMicron Technology          | 1         | 1      | 0.47%   |
| INDMEM                      | 1         | 1      | 0.47%   |
| IBM                         | 1         | 1      | 0.47%   |
| HS-SSD-C100                 | 1         | 1      | 0.47%   |
| Hewlett-Packard             | 1         | 1      | 0.47%   |
| GOODRAM                     | 1         | 1      | 0.47%   |
| Gigabyte Technology         | 1         | 1      | 0.47%   |
| Fujitsu                     | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.63%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 2         | 0.82%   |
| WDC WD2002FAEX-007BA0 2TB                           | 2         | 0.82%   |
| Unknown MMC Card  64GB                              | 2         | 0.82%   |
| Seagate ST9320325AS 320GB                           | 2         | 0.82%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.82%   |
| Seagate ST300MP0005 304GB                           | 2         | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.82%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.82%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.82%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.82%   |
| Lexar 512GB SSD                                     | 2         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.82%   |
| A-DATA SWORDFISH 1TB                                | 2         | 0.82%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD                    | 1         | 0.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.41%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.41%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.41%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                      | 1         | 0.41%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.41%   |
| WDC WD80EZZX-11CSGA0 8TB                            | 1         | 0.41%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.41%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.41%   |
| WDC WD60EFAX-68JH4N1 6TB                            | 1         | 0.41%   |
| WDC WD5003ABYX-18WERA0 500GB                        | 1         | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.41%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 0.41%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 0.41%   |
| WDC WD5000AUDX-63WNHY0 500GB                        | 1         | 0.41%   |
| WDC WD5000AAKX-001CA0 500GB                         | 1         | 0.41%   |
| WDC WD5000AAKS-402AA0 500GB                         | 1         | 0.41%   |
| WDC WD40EZRZ-00WN9B0 4TB                            | 1         | 0.41%   |
| WDC WD30EZRX-00D8PB0 3TB                            | 1         | 0.41%   |
| WDC WD2500AAJS-22VTA0 250GB                         | 1         | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 0.41%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 0.41%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 91     | 41.03%  |
| WDC                 | 21        | 42     | 26.92%  |
| Hitachi             | 9         | 14     | 11.54%  |
| Toshiba             | 7         | 9      | 8.97%   |
| Samsung Electronics | 3         | 4      | 3.85%   |
| HGST                | 2         | 2      | 2.56%   |
| Unknown             | 1         | 1      | 1.28%   |
| StoreJet            | 1         | 1      | 1.28%   |
| IBM                 | 1         | 1      | 1.28%   |
| Fujitsu             | 1         | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 20     | 23.19%  |
| WDC                 | 7         | 10     | 10.14%  |
| SanDisk             | 7         | 8      | 10.14%  |
| Toshiba             | 5         | 5      | 7.25%   |
| Kingston            | 5         | 5      | 7.25%   |
| Crucial             | 5         | 6      | 7.25%   |
| SK hynix            | 2         | 2      | 2.9%    |
| LITEONIT            | 2         | 2      | 2.9%    |
| Intel               | 2         | 3      | 2.9%    |
| China               | 2         | 2      | 2.9%    |
| Team                | 1         | 1      | 1.45%   |
| PNY                 | 1         | 1      | 1.45%   |
| MyDigitalSSD        | 1         | 1      | 1.45%   |
| LITEON              | 1         | 1      | 1.45%   |
| Lexar               | 1         | 1      | 1.45%   |
| KingFast            | 1         | 1      | 1.45%   |
| INDMEM              | 1         | 1      | 1.45%   |
| GOODRAM             | 1         | 1      | 1.45%   |
| Gigabyte Technology | 1         | 1      | 1.45%   |
| Dogfish             | 1         | 1      | 1.45%   |
| Digma               | 1         | 1      | 1.45%   |
| Corsair             | 1         | 1      | 1.45%   |
| ASMT                | 1         | 1      | 1.45%   |
| Apacer              | 1         | 1      | 1.45%   |
| ADATA SU            | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 59        | 79     | 32.42%  |
| NVMe    | 58        | 90     | 31.87%  |
| HDD     | 57        | 166    | 31.32%  |
| MMC     | 4         | 4      | 2.2%    |
| Unknown | 4         | 4      | 2.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 93        | 233    | 56.02%  |
| NVMe | 58        | 90     | 34.94%  |
| SAS  | 11        | 16     | 6.63%   |
| MMC  | 4         | 4      | 2.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 96     | 48.06%  |
| 0.51-1.0   | 36        | 75     | 27.91%  |
| 1.01-2.0   | 16        | 27     | 12.4%   |
| 3.01-4.0   | 8         | 27     | 6.2%    |
| 4.01-10.0  | 3         | 15     | 2.33%   |
| 2.01-3.0   | 2         | 2      | 1.55%   |
| 10.01-20.0 | 2         | 3      | 1.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 26.76%  |
| 251-500        | 31        | 21.83%  |
| 501-1000       | 24        | 16.9%   |
| 1001-2000      | 17        | 11.97%  |
| More than 3000 | 10        | 7.04%   |
| 51-100         | 8         | 5.63%   |
| 2001-3000      | 7         | 4.93%   |
| Unknown        | 4         | 2.82%   |
| 1-20           | 3         | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 51        | 35.42%  |
| 21-50          | 31        | 21.53%  |
| 51-100         | 17        | 11.81%  |
| 101-250        | 13        | 9.03%   |
| 501-1000       | 10        | 6.94%   |
| 251-500        | 7         | 4.86%   |
| More than 3000 | 6         | 4.17%   |
| 1001-2000      | 4         | 2.78%   |
| Unknown        | 4         | 2.78%   |
| 2001-3000      | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 5.88%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 5.88%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 2      | 5.88%   |
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 5.88%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 5.88%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 5.88%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 5.88%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 5.88%   |
| Seagate ST31000528AS 1TB              | 1         | 2      | 5.88%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 5.88%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 5.88%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 5.88%   |
| Hitachi HDS725050KLA360 500GB         | 1         | 1      | 5.88%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 5.88%   |
| Crucial CT1050MX300SSD1 1050GB        | 1         | 1      | 5.88%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 17     | 35.29%  |
| WDC     | 4         | 8      | 23.53%  |
| Hitachi | 3         | 3      | 17.65%  |
| Toshiba | 1         | 1      | 5.88%   |
| IBM     | 1         | 1      | 5.88%   |
| Crucial | 1         | 1      | 5.88%   |
| Corsair | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 17     | 40%     |
| WDC     | 4         | 8      | 26.67%  |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |
| IBM     | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 30     | 86.67%  |
| SSD  | 2         | 2      | 13.33%  |

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
| Works    | 92        | 225    | 57.86%  |
| Detected | 52        | 85     | 32.7%   |
| Malfunc  | 14        | 32     | 8.81%   |
| Failed   | 1         | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 91        | 48.15%  |
| AMD                          | 28        | 14.81%  |
| Samsung Electronics          | 20        | 10.58%  |
| Phison Electronics           | 5         | 2.65%   |
| LSI Logic / Symbios Logic    | 5         | 2.65%   |
| SanDisk                      | 4         | 2.12%   |
| Micron Technology            | 4         | 2.12%   |
| Kingston Technology Company  | 4         | 2.12%   |
| ASMedia Technology           | 4         | 2.12%   |
| SK hynix                     | 3         | 1.59%   |
| Broadcom / LSI               | 3         | 1.59%   |
| Toshiba America Info Systems | 2         | 1.06%   |
| Realtek Semiconductor        | 2         | 1.06%   |
| KIOXIA                       | 2         | 1.06%   |
| Hewlett-Packard              | 2         | 1.06%   |
| VIA Technologies             | 1         | 0.53%   |
| Union Memory (Shenzhen)      | 1         | 0.53%   |
| Silicon Motion               | 1         | 0.53%   |
| Shenzhen Longsys Electronics | 1         | 0.53%   |
| Micron/Crucial Technology    | 1         | 0.53%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.53%   |
| Marvell Technology Group     | 1         | 0.53%   |
| JMicron Technology           | 1         | 0.53%   |
| ADATA Technology             | 1         | 0.53%   |
| Adaptec                      | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 8.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 4.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.62%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 2.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5         | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 2.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.26%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.81%   |
| Micron NVMe Storage Controller                                                          | 3         | 1.36%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.36%   |
| Intel Non-Volatile memory controller                                                    | 3         | 1.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.36%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.36%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 1.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.36%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.36%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.9%    |
| Realtek NVMe Controller                                                                 | 2         | 0.9%    |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.9%    |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 0.9%    |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 0.9%    |
| Intel SSD 660P Series                                                                   | 2         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.9%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2         | 0.9%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 0.9%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 0.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.9%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 0.9%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 87        | 44.85%  |
| NVMe | 58        | 29.9%   |
| IDE  | 22        | 11.34%  |
| RAID | 21        | 10.82%  |
| SAS  | 5         | 2.58%   |
| SCSI | 1         | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 105       | 75%     |
| AMD    | 34        | 24.29%  |
| ARM    | 1         | 0.71%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4         | 2.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 2.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 2.14%   |
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 1.43%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 2         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.43%   |
| Intel 12th Gen Core i5-12400F               | 2         | 1.43%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.43%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.43%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 0.71%   |
| Intel Xeon Platinum 8124M CPU @ 3.00GHz     | 1         | 0.71%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 0.71%   |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1         | 0.71%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.71%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 0.71%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.71%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.71%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1         | 0.71%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 0.71%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 0.71%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.71%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.71%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.71%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.71%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 0.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.71%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.71%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.71%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.71%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 32        | 22.86%  |
| Other                   | 23        | 16.43%  |
| Intel Core i5           | 16        | 11.43%  |
| Intel Xeon              | 15        | 10.71%  |
| AMD Ryzen 7             | 7         | 5%      |
| AMD Ryzen 5             | 7         | 5%      |
| Intel Core i3           | 6         | 4.29%   |
| Intel Celeron           | 6         | 4.29%   |
| AMD Ryzen 9             | 4         | 2.86%   |
| AMD FX                  | 3         | 2.14%   |
| AMD Ryzen Threadripper  | 2         | 1.43%   |
| AMD Ryzen 5 PRO         | 2         | 1.43%   |
| Intel Xeon Silver       | 1         | 0.71%   |
| Intel Xeon Platinum     | 1         | 0.71%   |
| Intel Xeon Gold         | 1         | 0.71%   |
| Intel Pentium Silver    | 1         | 0.71%   |
| Intel Pentium Dual-Core | 1         | 0.71%   |
| Intel Pentium Dual      | 1         | 0.71%   |
| Intel Core i9           | 1         | 0.71%   |
| Intel Core 2 Quad       | 1         | 0.71%   |
| Intel Core 2 Duo        | 1         | 0.71%   |
| Intel Atom              | 1         | 0.71%   |
| AMD Sempron             | 1         | 0.71%   |
| AMD Ryzen Embedded      | 1         | 0.71%   |
| AMD Ryzen 7 PRO         | 1         | 0.71%   |
| AMD Ryzen 3             | 1         | 0.71%   |
| AMD Phenom II X6        | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |
| AMD A10                 | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 54        | 38.57%  |
| 2      | 26        | 18.57%  |
| 6      | 20        | 14.29%  |
| 8      | 19        | 13.57%  |
| 12     | 5         | 3.57%   |
| 10     | 5         | 3.57%   |
| 16     | 4         | 2.86%   |
| 36     | 1         | 0.71%   |
| 32     | 1         | 0.71%   |
| 28     | 1         | 0.71%   |
| 24     | 1         | 0.71%   |
| 14     | 1         | 0.71%   |
| 3      | 1         | 0.71%   |
| 1      | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 130       | 92.86%  |
| 2      | 10        | 7.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 107       | 76.43%  |
| 1      | 33        | 23.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 140       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 12        | 8.57%   |
| 0x206a7    | 8         | 5.71%   |
| 0x806c1    | 7         | 5%      |
| 0x506e3    | 6         | 4.29%   |
| 0x306a9    | 6         | 4.29%   |
| 0x806ec    | 5         | 3.57%   |
| Unknown    | 5         | 3.57%   |
| 0x806ea    | 4         | 2.86%   |
| 0x0a50000c | 4         | 2.86%   |
| 0xa0652    | 3         | 2.14%   |
| 0x50654    | 3         | 2.14%   |
| 0xa0671    | 2         | 1.43%   |
| 0xa0655    | 2         | 1.43%   |
| 0x906ea    | 2         | 1.43%   |
| 0x906c0    | 2         | 1.43%   |
| 0x906a4    | 2         | 1.43%   |
| 0x906a3    | 2         | 1.43%   |
| 0x90675    | 2         | 1.43%   |
| 0x90672    | 2         | 1.43%   |
| 0x706a8    | 2         | 1.43%   |
| 0x406f1    | 2         | 1.43%   |
| 0x40651    | 2         | 1.43%   |
| 0x306e4    | 2         | 1.43%   |
| 0x206d7    | 2         | 1.43%   |
| 0x206c2    | 2         | 1.43%   |
| 0x106a5    | 2         | 1.43%   |
| 0x10676    | 2         | 1.43%   |
| 0x08608103 | 2         | 1.43%   |
| 0x08600106 | 2         | 1.43%   |
| 0x08600104 | 2         | 1.43%   |
| 0x0800820d | 2         | 1.43%   |
| 0x06000852 | 2         | 1.43%   |
| 0xa0653    | 1         | 0.71%   |
| 0x906ed    | 1         | 0.71%   |
| 0x806e9    | 1         | 0.71%   |
| 0x806d1    | 1         | 0.71%   |
| 0x706a1    | 1         | 0.71%   |
| 0x6fd      | 1         | 0.71%   |
| 0x50657    | 1         | 0.71%   |
| 0x406e3    | 1         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 16        | 11.43%  |
| KabyLake         | 13        | 9.29%   |
| Skylake          | 11        | 7.86%   |
| SandyBridge      | 11        | 7.86%   |
| Alderlake Hybrid | 10        | 7.14%   |
| Zen 3            | 8         | 5.71%   |
| IvyBridge        | 8         | 5.71%   |
| Zen 2            | 7         | 5%      |
| TigerLake        | 7         | 5%      |
| CometLake        | 6         | 4.29%   |
| Piledriver       | 5         | 3.57%   |
| Unknown          | 5         | 3.57%   |
| Zen+             | 4         | 2.86%   |
| Penryn           | 4         | 2.86%   |
| Westmere         | 3         | 2.14%   |
| Nehalem          | 3         | 2.14%   |
| Icelake          | 3         | 2.14%   |
| Goldmont plus    | 3         | 2.14%   |
| Broadwell        | 3         | 2.14%   |
| Zen              | 2         | 1.43%   |
| Tremont          | 2         | 1.43%   |
| K10              | 2         | 1.43%   |
| Silvermont       | 1         | 0.71%   |
| Jaguar           | 1         | 0.71%   |
| Excavator        | 1         | 0.71%   |
| Core             | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 72        | 41.86%  |
| Nvidia                     | 57        | 33.14%  |
| AMD                        | 32        | 18.6%   |
| Matrox Electronics Systems | 6         | 3.49%   |
| ASPEED Technology          | 5         | 2.91%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 4.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 2.87%   |
| ASPEED Technology ASPEED Graphics Family                                    | 5         | 2.87%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4         | 2.3%    |
| Intel UHD Graphics 620                                                      | 4         | 2.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.3%    |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 1.72%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.72%   |
| Intel HD Graphics 530                                                       | 3         | 1.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.72%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 3         | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.72%   |
| AMD Renoir                                                                  | 3         | 1.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 1.15%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.15%   |
| Nvidia GP107GL [Quadro P400]                                                | 2         | 1.15%   |
| Nvidia GM108M [GeForce 940M]                                                | 2         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.15%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 1.15%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2         | 1.15%   |
| Intel JasperLake [UHD Graphics]                                             | 2         | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.15%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 1.15%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 1.15%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2         | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.15%   |
| AMD Lucienne                                                                | 2         | 1.15%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.15%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.57%   |
| Nvidia TU117GL [T600]                                                       | 1         | 0.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 47        | 33.57%  |
| 1 x Nvidia      | 28        | 20%     |
| 1 x AMD         | 23        | 16.43%  |
| Intel + Nvidia  | 22        | 15.71%  |
| 1 x Matrox      | 5         | 3.57%   |
| AMD + Nvidia    | 4         | 2.86%   |
| 1 x ASPEED      | 3         | 2.14%   |
| 2 x AMD         | 2         | 1.43%   |
| Intel + AMD     | 2         | 1.43%   |
| Other           | 1         | 0.71%   |
| Nvidia + Matrox | 1         | 0.71%   |
| Nvidia + ASPEED | 1         | 0.71%   |
| AMD + ASPEED    | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 111       | 79.29%  |
| Proprietary | 20        | 14.29%  |
| Unknown     | 9         | 6.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 49.65%  |
| 1.01-2.0   | 20        | 14.18%  |
| 0.01-0.5   | 18        | 12.77%  |
| 3.01-4.0   | 12        | 8.51%   |
| 0.51-1.0   | 9         | 6.38%   |
| 7.01-8.0   | 4         | 2.84%   |
| 5.01-6.0   | 4         | 2.84%   |
| 8.01-16.0  | 2         | 1.42%   |
| 32.01-64.0 | 1         | 0.71%   |
| 2.01-3.0   | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 19        | 12.93%  |
| Samsung Electronics  | 15        | 10.2%   |
| LG Display           | 14        | 9.52%   |
| BOE                  | 11        | 7.48%   |
| AU Optronics         | 11        | 7.48%   |
| Chimei Innolux       | 9         | 6.12%   |
| Acer                 | 8         | 5.44%   |
| Goldstar             | 7         | 4.76%   |
| Philips              | 5         | 3.4%    |
| Hewlett-Packard      | 4         | 2.72%   |
| BenQ                 | 4         | 2.72%   |
| AOC                  | 4         | 2.72%   |
| Ancor Communications | 4         | 2.72%   |
| Sharp                | 3         | 2.04%   |
| InfoVision           | 3         | 2.04%   |
| Iiyama               | 3         | 2.04%   |
| ViewSonic            | 2         | 1.36%   |
| SGT                  | 2         | 1.36%   |
| Sceptre Tech         | 2         | 1.36%   |
| PANDA                | 2         | 1.36%   |
| ASUSTek Computer     | 2         | 1.36%   |
| Xiaomi               | 1         | 0.68%   |
| Vizio                | 1         | 0.68%   |
| Sony                 | 1         | 0.68%   |
| Panasonic            | 1         | 0.68%   |
| OEM                  | 1         | 0.68%   |
| NEC Computers        | 1         | 0.68%   |
| Lenovo               | 1         | 0.68%   |
| IBM                  | 1         | 0.68%   |
| HUAWEI               | 1         | 0.68%   |
| HCL                  | 1         | 0.68%   |
| Gigabyte Technology  | 1         | 0.68%   |
| Eizo                 | 1         | 0.68%   |
| ADR                  | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 2         | 1.32%   |
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                     | 2         | 1.32%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                       | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.32%   |
| Xiaomi Mi TV XMD00E1 3840x2160 950x540mm 43.0-inch                      | 1         | 0.66%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                     | 1         | 0.66%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1         | 0.66%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                  | 1         | 0.66%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                      | 1         | 0.66%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                 | 1         | 0.66%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.66%   |
| Sharp LCD Monitor SHP1491 3840x2160 346x194mm 15.6-inch                 | 1         | 0.66%   |
| SGT M156F01 SGT1600 1920x1080 345x194mm 15.6-inch                       | 1         | 0.66%   |
| SGT HS156PC SGT1560 1920x1080 345x194mm 15.6-inch                       | 1         | 0.66%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch          | 1         | 0.66%   |
| Sceptre Tech X240-CNC SPT0978 1920x1080 880x490mm 39.7-inch             | 1         | 0.66%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1         | 0.66%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch    | 1         | 0.66%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.66%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch     | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.66%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 700x400mm 31.7-inch      | 1         | 0.66%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch      | 1         | 0.66%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1         | 0.66%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch      | 1         | 0.66%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch       | 1         | 0.66%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch                | 1         | 0.66%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1         | 0.66%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch                | 1         | 0.66%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch                | 1         | 0.66%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch                | 1         | 0.66%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 0.66%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch            | 1         | 0.66%   |
| OEM 26_LCD_TV OEM3700 1920x1080                                         | 1         | 0.66%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch           | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 45.65%  |
| 1366x768 (WXGA)    | 12        | 8.7%    |
| 3840x2160 (4K)     | 9         | 6.52%   |
| 2560x1440 (QHD)    | 9         | 6.52%   |
| 1280x1024 (SXGA)   | 7         | 5.07%   |
| 1920x1200 (WUXGA)  | 6         | 4.35%   |
| 3440x1440          | 5         | 3.62%   |
| 1600x900 (HD+)     | 5         | 3.62%   |
| 1680x1050 (WSXGA+) | 4         | 2.9%    |
| 3840x1080          | 3         | 2.17%   |
| 3840x2400          | 2         | 1.45%   |
| 2560x1080          | 2         | 1.45%   |
| 1920x540           | 2         | 1.45%   |
| 1440x900 (WXGA+)   | 2         | 1.45%   |
| 1024x768 (XGA)     | 2         | 1.45%   |
| Unknown            | 2         | 1.45%   |
| 2240x1400          | 1         | 0.72%   |
| 2160x1440          | 1         | 0.72%   |
| 1280x768           | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 20.55%  |
| 14      | 18        | 12.33%  |
| 27      | 16        | 10.96%  |
| 24      | 14        | 9.59%   |
| 17      | 10        | 6.85%   |
| 34      | 7         | 4.79%   |
| 23      | 7         | 4.79%   |
| 21      | 7         | 4.79%   |
| 13      | 7         | 4.79%   |
| 31      | 6         | 4.11%   |
| 19      | 5         | 3.42%   |
| 22      | 3         | 2.05%   |
| 65      | 2         | 1.37%   |
| 20      | 2         | 1.37%   |
| 16      | 2         | 1.37%   |
| Unknown | 2         | 1.37%   |
| 84      | 1         | 0.68%   |
| 49      | 1         | 0.68%   |
| 48      | 1         | 0.68%   |
| 40      | 1         | 0.68%   |
| 39      | 1         | 0.68%   |
| 28      | 1         | 0.68%   |
| 25      | 1         | 0.68%   |
| 18      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 38.62%  |
| 501-600     | 36        | 24.83%  |
| 401-500     | 17        | 11.72%  |
| 351-400     | 9         | 6.21%   |
| 701-800     | 7         | 4.83%   |
| 601-700     | 7         | 4.83%   |
| 201-300     | 4         | 2.76%   |
| 1001-1500   | 4         | 2.76%   |
| 801-900     | 2         | 1.38%   |
| Unknown     | 2         | 1.38%   |
| 1501-2000   | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 73.44%  |
| 16/10   | 13        | 10.16%  |
| 5/4     | 7         | 5.47%   |
| 21/9    | 6         | 4.69%   |
| 3/2     | 3         | 2.34%   |
| 4/3     | 2         | 1.56%   |
| 32/9    | 2         | 1.56%   |
| Unknown | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 20.83%  |
| 201-250        | 26        | 18.06%  |
| 81-90          | 23        | 15.97%  |
| 301-350        | 16        | 11.11%  |
| 351-500        | 13        | 9.03%   |
| 151-200        | 8         | 5.56%   |
| 121-130        | 6         | 4.17%   |
| 141-150        | 5         | 3.47%   |
| 501-1000       | 5         | 3.47%   |
| More than 1000 | 3         | 2.08%   |
| 251-300        | 3         | 2.08%   |
| 111-120        | 2         | 1.39%   |
| Unknown        | 2         | 1.39%   |
| 71-80          | 1         | 0.69%   |
| 91-100         | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 59        | 41.26%  |
| 121-160       | 42        | 29.37%  |
| 101-120       | 25        | 17.48%  |
| 161-240       | 8         | 5.59%   |
| More than 240 | 5         | 3.5%    |
| 1-50          | 2         | 1.4%    |
| Unknown       | 2         | 1.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 89        | 63.57%  |
| 2     | 24        | 17.14%  |
| 0     | 23        | 16.43%  |
| 3     | 3         | 2.14%   |
| 4     | 1         | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 90        | 43.48%  |
| Realtek Semiconductor     | 63        | 30.43%  |
| Broadcom                  | 11        | 5.31%   |
| Qualcomm Atheros          | 9         | 4.35%   |
| MediaTek                  | 7         | 3.38%   |
| Mellanox Technologies     | 3         | 1.45%   |
| Broadcom Limited          | 3         | 1.45%   |
| Ralink Technology         | 2         | 0.97%   |
| Marvell Technology Group  | 2         | 0.97%   |
| Linksys                   | 2         | 0.97%   |
| Lenovo                    | 2         | 0.97%   |
| ASIX Electronics          | 2         | 0.97%   |
| TP-Link                   | 1         | 0.48%   |
| Solarflare Communications | 1         | 0.48%   |
| Ralink                    | 1         | 0.48%   |
| Qualcomm                  | 1         | 0.48%   |
| Microsoft                 | 1         | 0.48%   |
| JMicron Technology        | 1         | 0.48%   |
| Dell                      | 1         | 0.48%   |
| D-Link                    | 1         | 0.48%   |
| BUFFALO                   | 1         | 0.48%   |
| Aquantia                  | 1         | 0.48%   |
| American Megatrends       | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 44        | 18.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 9         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 8         | 3.29%   |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 2.88%   |
| Intel Wireless 7260                                                                                                    | 6         | 2.47%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6         | 2.47%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 5         | 2.06%   |
| Intel Ethernet Controller I225-V                                                                                       | 5         | 2.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 5         | 2.06%   |
| Intel Wireless 8265 / 8275                                                                                             | 4         | 1.65%   |
| Intel I211 Gigabit Network Connection                                                                                  | 4         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 3         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 3         | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 3         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 1.23%   |
| Intel Wireless 8260                                                                                                    | 3         | 1.23%   |
| Intel Wireless 3165                                                                                                    | 3         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                                 | 3         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 3         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 3         | 1.23%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 2         | 0.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 2         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 2         | 0.82%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 0.82%   |
| Intel Wireless 7265                                                                                                    | 2         | 0.82%   |
| Intel I350 Gigabit Network Connection                                                                                  | 2         | 0.82%   |
| Intel I210 Gigabit Network Connection                                                                                  | 2         | 0.82%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 0.82%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                                                                   | 2         | 0.82%   |
| Intel Ethernet Connection (17) I219-V                                                                                  | 2         | 0.82%   |
| Intel Ethernet Connection (16) I219-LM                                                                                 | 2         | 0.82%   |
| Intel Ethernet Connection (14) I219-V                                                                                  | 2         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 2         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 2         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 58.62%  |
| Realtek Semiconductor | 9         | 10.34%  |
| Qualcomm Atheros      | 8         | 9.2%    |
| MediaTek              | 7         | 8.05%   |
| Ralink Technology     | 2         | 2.3%    |
| Linksys               | 2         | 2.3%    |
| Broadcom              | 2         | 2.3%    |
| TP-Link               | 1         | 1.15%   |
| Ralink                | 1         | 1.15%   |
| Microsoft             | 1         | 1.15%   |
| Dell                  | 1         | 1.15%   |
| BUFFALO               | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 6         | 6.74%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 6.74%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 5.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 5.62%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 3.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 3.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 3.37%   |
| Intel Wireless 8260                                            | 3         | 3.37%   |
| Intel Wireless 3165                                            | 3         | 3.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 3.37%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.25%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.25%   |
| Intel Wireless 7265                                            | 2         | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.25%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.12%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.12%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.12%   |
| Realtek 802.11ac NIC                                           | 1         | 1.12%   |
| Ralink RT3071 Wireless Adapter                                 | 1         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.12%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.12%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1         | 1.12%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1         | 1.12%   |
| Intel Wireless 3160                                            | 1         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.12%   |
| Intel Centrino Wireless-N 135                                  | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 61        | 41.78%  |
| Realtek Semiconductor     | 59        | 40.41%  |
| Broadcom                  | 10        | 6.85%   |
| Marvell Technology Group  | 2         | 1.37%   |
| Lenovo                    | 2         | 1.37%   |
| Broadcom Limited          | 2         | 1.37%   |
| ASIX Electronics          | 2         | 1.37%   |
| Solarflare Communications | 1         | 0.68%   |
| Qualcomm Atheros          | 1         | 0.68%   |
| Qualcomm                  | 1         | 0.68%   |
| Mellanox Technologies     | 1         | 0.68%   |
| JMicron Technology        | 1         | 0.68%   |
| D-Link                    | 1         | 0.68%   |
| Aquantia                  | 1         | 0.68%   |
| American Megatrends       | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 28.95%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 5.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 4.61%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.29%   |
| Intel I211 Gigabit Network Connection                             | 4         | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.97%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 1.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.32%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.32%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.32%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.32%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 1.32%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 1.32%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.32%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.32%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 2         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.32%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.66%   |
| Qualcomm Nokia G400 5G                                            | 1         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.66%   |
| Mellanox MT27700 Family [ConnectX-4]                              | 1         | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.66%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.66%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.66%   |
| Lenovo USB-C to LAN                                               | 1         | 0.66%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.66%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.66%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.66%   |
| Intel Ethernet Controller X550                                    | 1         | 0.66%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.66%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.66%   |
| Intel Ethernet controller                                         | 1         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 126       | 59.72%  |
| WiFi     | 83        | 39.34%  |
| Unknown  | 2         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 93        | 63.27%  |
| WiFi     | 54        | 36.73%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 45%     |
| 1     | 58        | 41.43%  |
| 3     | 7         | 5%      |
| 5     | 4         | 2.86%   |
| 4     | 4         | 2.86%   |
| 0     | 2         | 1.43%   |
| 66    | 1         | 0.71%   |
| 8     | 1         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 110       | 78.57%  |
| Yes  | 30        | 21.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 60.56%  |
| Realtek Semiconductor           | 4         | 5.63%   |
| Qualcomm Atheros Communications | 4         | 5.63%   |
| Foxconn / Hon Hai               | 4         | 5.63%   |
| Cambridge Silicon Radio         | 4         | 5.63%   |
| MediaTek                        | 3         | 4.23%   |
| Broadcom                        | 3         | 4.23%   |
| IMC Networks                    | 2         | 2.82%   |
| Ralink                          | 1         | 1.41%   |
| Integrated System Solution      | 1         | 1.41%   |
| Hewlett-Packard                 | 1         | 1.41%   |
| Dell                            | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 18        | 25.35%  |
| Intel AX201 Bluetooth                                 | 11        | 15.49%  |
| Intel AX200 Bluetooth                                 | 6         | 8.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 5.63%   |
| Realtek Bluetooth Radio                               | 3         | 4.23%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 4.23%   |
| MediaTek Wireless_Device                              | 3         | 4.23%   |
| Intel Bluetooth Device                                | 3         | 4.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 3         | 4.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 2.82%   |
| Intel AX210 Bluetooth                                 | 2         | 2.82%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.41%   |
| Ralink RT3290 Bluetooth                               | 1         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 1.41%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.41%   |
| IMC Networks Wireless_Device                          | 1         | 1.41%   |
| IMC Networks Bluetooth Device                         | 1         | 1.41%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.41%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1         | 1.41%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 1.41%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 1.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 91        | 46.19%  |
| Nvidia              | 44        | 22.34%  |
| AMD                 | 38        | 19.29%  |
| C-Media Electronics | 4         | 2.03%   |
| Logitech            | 3         | 1.52%   |
| GN Netcom           | 2         | 1.02%   |
| Creative Technology | 2         | 1.02%   |
| Conexant Systems    | 2         | 1.02%   |
| ASUSTek Computer    | 2         | 1.02%   |
| Texas Instruments   | 1         | 0.51%   |
| Setek Elektronik    | 1         | 0.51%   |
| Saitek              | 1         | 0.51%   |
| Nektar              | 1         | 0.51%   |
| Lenovo              | 1         | 0.51%   |
| KTMicro             | 1         | 0.51%   |
| Huawei Technologies | 1         | 0.51%   |
| Hewlett-Packard     | 1         | 0.51%   |
| GYROCOM C&C         | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 6.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 5.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 3.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 3.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 2.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 2.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 2.18%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2.18%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4         | 1.75%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 1.31%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.31%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 1.31%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 1.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 1.31%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.87%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.87%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.87%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.87%   |
| C-Media Electronics BIRD UM1                                               | 2         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 22.43%  |
| SK hynix            | 14        | 13.08%  |
| Micron Technology   | 14        | 13.08%  |
| Kingston            | 9         | 8.41%   |
| Unknown             | 8         | 7.48%   |
| Crucial             | 8         | 7.48%   |
| Corsair             | 8         | 7.48%   |
| G.Skill             | 7         | 6.54%   |
| A-DATA Technology   | 2         | 1.87%   |
| Unknown (ABCD)      | 1         | 0.93%   |
| Team                | 1         | 0.93%   |
| Smart               | 1         | 0.93%   |
| Ramaxel Technology  | 1         | 0.93%   |
| PNY                 | 1         | 0.93%   |
| Patriot             | 1         | 0.93%   |
| Magnum Tech         | 1         | 0.93%   |
| Lexar Co Limited    | 1         | 0.93%   |
| Lexar               | 1         | 0.93%   |
| HPE                 | 1         | 0.93%   |
| Hewlett-Packard     | 1         | 0.93%   |
| Gold Key            | 1         | 0.93%   |
| Unknown             | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.82%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.82%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                        | 1         | 0.91%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.91%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.91%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.91%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.91%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 0.91%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                       | 1         | 0.91%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 0.91%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.91%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.91%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.91%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.91%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.91%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.91%   |
| SK hynix RAM HMT325U7EFR8A-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.91%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.91%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.91%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.91%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.91%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.91%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 0.91%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 0.91%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.91%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 0.91%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.91%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.91%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 0.91%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.91%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM 1600MT/s                  | 1         | 0.91%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 0.91%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s              | 1         | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 53        | 55.79%  |
| DDR3    | 28        | 29.47%  |
| DDR5    | 5         | 5.26%   |
| LPDDR4  | 3         | 3.16%   |
| DDR2    | 3         | 3.16%   |
| LPDDR5  | 1         | 1.05%   |
| LPDDR3  | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 47        | 48.96%  |
| SODIMM       | 42        | 43.75%  |
| Row Of Chips | 6         | 6.25%   |
| RIMM         | 1         | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 42        | 41.58%  |
| 16384 | 20        | 19.8%   |
| 4096  | 16        | 15.84%  |
| 32768 | 12        | 11.88%  |
| 1024  | 6         | 5.94%   |
| 2048  | 5         | 4.95%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 22        | 21.78%  |
| 2667  | 14        | 13.86%  |
| 1600  | 13        | 12.87%  |
| 2400  | 9         | 8.91%   |
| 1333  | 6         | 5.94%   |
| 4800  | 5         | 4.95%   |
| 2133  | 5         | 4.95%   |
| 2666  | 4         | 3.96%   |
| 1066  | 3         | 2.97%   |
| 667   | 3         | 2.97%   |
| 3600  | 2         | 1.98%   |
| 3534  | 2         | 1.98%   |
| 6400  | 1         | 0.99%   |
| 4267  | 1         | 0.99%   |
| 4266  | 1         | 0.99%   |
| 3733  | 1         | 0.99%   |
| 3666  | 1         | 0.99%   |
| 3266  | 1         | 0.99%   |
| 3100  | 1         | 0.99%   |
| 3000  | 1         | 0.99%   |
| 2800  | 1         | 0.99%   |
| 2200  | 1         | 0.99%   |
| 2048  | 1         | 0.99%   |
| 1866  | 1         | 0.99%   |
| 1800  | 1         | 0.99%   |

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
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP ScanJet 82x0C  | 1         | 50%     |
| HP OfficeJet 6110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 20%     |
| IMC Networks                           | 9         | 13.85%  |
| Microdia                               | 5         | 7.69%   |
| Syntek                                 | 4         | 6.15%   |
| Sunplus Innovation Technology          | 4         | 6.15%   |
| Realtek Semiconductor                  | 4         | 6.15%   |
| Luxvisions Innotech Limited            | 4         | 6.15%   |
| Logitech                               | 4         | 6.15%   |
| Quanta                                 | 2         | 3.08%   |
| Generalplus Technology                 | 2         | 3.08%   |
| 2M UVC CAMERA                          | 2         | 3.08%   |
| Suyin                                  | 1         | 1.54%   |
| Sonix Technology                       | 1         | 1.54%   |
| Lite-On Technology                     | 1         | 1.54%   |
| Lenovo                                 | 1         | 1.54%   |
| KYE Systems (Mouse Systems)            | 1         | 1.54%   |
| Intel                                  | 1         | 1.54%   |
| Huawei Technologies                    | 1         | 1.54%   |
| Elgato Systems                         | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.54%   |
| Bison Electronics                      | 1         | 1.54%   |
| Apple                                  | 1         | 1.54%   |
| Acer                                   | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 10.77%  |
| Microdia Integrated_Webcam_HD                       | 4         | 6.15%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4.62%   |
| IMC Networks Integrated Camera                      | 3         | 4.62%   |
| Syntek Lenovo EasyCamera                            | 2         | 3.08%   |
| Syntek Integrated Camera                            | 2         | 3.08%   |
| Realtek Integrated_Webcam_HD                        | 2         | 3.08%   |
| Logitech HD Pro Webcam C920                         | 2         | 3.08%   |
| Generalplus GENERAL WEBCAM                          | 2         | 3.08%   |
| Chicony HP HD Camera                                | 2         | 3.08%   |
| Chicony HD WebCam                                   | 2         | 3.08%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam                | 2         | 3.08%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.54%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.54%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.54%   |
| Sunplus Full HD webcam                              | 1         | 1.54%   |
| Sunplus FHD Camera Microphone                       | 1         | 1.54%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.54%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.54%   |
| Realtek EasyCamera                                  | 1         | 1.54%   |
| Quanta HP Webcam                                    | 1         | 1.54%   |
| Quanta HP 5MP Camera                                | 1         | 1.54%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.54%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 1.54%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.54%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.54%   |
| Logitech Webcam C270                                | 1         | 1.54%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 1.54%   |
| Lite-On HP HD Webcam                                | 1         | 1.54%   |
| Lenovo UVC Camera                                   | 1         | 1.54%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera    | 1         | 1.54%   |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.54%   |
| IMC Networks TOSHIBA Web Camera - HD                | 1         | 1.54%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.54%   |
| IMC Networks HD Camera                              | 1         | 1.54%   |
| Huawei UVC Camera                                   | 1         | 1.54%   |
| Elgato Systems Elgato Facecam                       | 1         | 1.54%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.54%   |
| Chicony HP HD Webcam                                | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 33.33%  |
| Validity Sensors           | 6         | 28.57%  |
| Shenzhen Goodix Technology | 3         | 14.29%  |
| LighTuning Technology      | 3         | 14.29%  |
| Elan Microelectronics      | 1         | 4.76%   |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 9.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 9.52%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 9.52%   |
| LighTuning Fingerprint Sensor                                              | 2         | 9.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 4.76%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Synaptics WBDI                                                             | 1         | 4.76%   |
| Synaptics UWP WBDI Device                                                  | 1         | 4.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 4.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.76%   |
| AuthenTec AES2810                                                          | 1         | 4.76%   |

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
| 0     | 79        | 56.43%  |
| 1     | 45        | 32.14%  |
| 2     | 10        | 7.14%   |
| 3     | 3         | 2.14%   |
| 5     | 2         | 1.43%   |
| 4     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 26.25%  |
| Graphics card            | 17        | 21.25%  |
| Net/wireless             | 10        | 12.5%   |
| Unassigned class         | 7         | 8.75%   |
| Communication controller | 6         | 7.5%    |
| Net/ethernet             | 4         | 5%      |
| Multimedia controller    | 3         | 3.75%   |
| Chipcard                 | 3         | 3.75%   |
| Network                  | 2         | 2.5%    |
| Storage/raid             | 1         | 1.25%   |
| Storage                  | 1         | 1.25%   |
| Sound                    | 1         | 1.25%   |
| Firewire controller      | 1         | 1.25%   |
| Dvb card                 | 1         | 1.25%   |
| Card reader              | 1         | 1.25%   |
| Bluetooth                | 1         | 1.25%   |

