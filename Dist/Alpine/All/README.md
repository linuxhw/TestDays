Alpine - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Alpine/Desktop/README.md) and [notebooks](/Dist/Alpine/Notebook/README.md).

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

Total: 253

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [dc84848e79](https://linux-hardware.org/?probe=dc84848e79) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [d3a48ce5b5](https://linux-hardware.org/?probe=d3a48ce5b5) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [2fa13d832c](https://linux-hardware.org/?probe=2fa13d832c) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [3f6d4a63ee](https://linux-hardware.org/?probe=3f6d4a63ee) | Jan 09, 2024 |
| HP            | 3397                        | Desktop     | [c33a1d3b01](https://linux-hardware.org/?probe=c33a1d3b01) | Jan 09, 2024 |
| Wortmann      | M660SE                      | Notebook    | [225361b7c3](https://linux-hardware.org/?probe=225361b7c3) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [6f9241e288](https://linux-hardware.org/?probe=6f9241e288) | Jan 04, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [cf4135541d](https://linux-hardware.org/?probe=cf4135541d) | Jan 03, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [9d5aa2f8ae](https://linux-hardware.org/?probe=9d5aa2f8ae) | Jan 02, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [db0bed1921](https://linux-hardware.org/?probe=db0bed1921) | Jan 02, 2024 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [018238aa79](https://linux-hardware.org/?probe=018238aa79) | Jan 01, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [cee7f7036e](https://linux-hardware.org/?probe=cee7f7036e) | Dec 31, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d6121834a4](https://linux-hardware.org/?probe=d6121834a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [ea0b7cd870](https://linux-hardware.org/?probe=ea0b7cd870) | Dec 26, 2023 |
| Acer          | TDPS05                      | Desktop     | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| Acer          | TDPS05                      | Desktop     | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| Compaq        | 0684h                       | Desktop     | [54c2d84103](https://linux-hardware.org/?probe=54c2d84103) | Dec 02, 2023 |
| Compaq        | 0684h                       | Desktop     | [b2d96b48dc](https://linux-hardware.org/?probe=b2d96b48dc) | Dec 02, 2023 |
| ECS           | M789CG                      | Desktop     | [7c2e2de188](https://linux-hardware.org/?probe=7c2e2de188) | Dec 01, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ed82b4c1c7](https://linux-hardware.org/?probe=ed82b4c1c7) | Nov 12, 2023 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [bfd62247aa](https://linux-hardware.org/?probe=bfd62247aa) | Nov 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| ECS           | M789CG                      | Desktop     | [49edfe005c](https://linux-hardware.org/?probe=49edfe005c) | Nov 07, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | Desktop     | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | Desktop     | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Dell          | 0RY007                      | Desktop     | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ca65758798](https://linux-hardware.org/?probe=ca65758798) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2ea9aa9b27](https://linux-hardware.org/?probe=2ea9aa9b27) | Aug 02, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3dcdce4c6d](https://linux-hardware.org/?probe=3dcdce4c6d) | Aug 02, 2023 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [051aebd1a2](https://linux-hardware.org/?probe=051aebd1a2) | Jul 24, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASUSTek       | Z170-E                      | Desktop     | [8be9720ca6](https://linux-hardware.org/?probe=8be9720ca6) | Jun 29, 2023 |
| Toshiba       | Satellite Pro L50-A         | Notebook    | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Google        | Kefka                       | Notebook    | [c5d9002e23](https://linux-hardware.org/?probe=c5d9002e23) | Jun 23, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [b303b8ce0d](https://linux-hardware.org/?probe=b303b8ce0d) | Jun 07, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [8b904db6cf](https://linux-hardware.org/?probe=8b904db6cf) | Jun 06, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [0ad2309a50](https://linux-hardware.org/?probe=0ad2309a50) | Jun 05, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [374a3fef00](https://linux-hardware.org/?probe=374a3fef00) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [413d6e5373](https://linux-hardware.org/?probe=413d6e5373) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| UGREEN        | DX4600                      | Desktop     | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | Notebook    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | Notebook    | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | Desktop     | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ab9f37ab3a](https://linux-hardware.org/?probe=ab9f37ab3a) | Oct 27, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| HP            | 1493                        | Desktop     | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | Desktop     | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Sony          | VGN-UX27GN                  | Notebook    | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | Notebook    | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [a7f61e2b9b](https://linux-hardware.org/?probe=a7f61e2b9b) | May 28, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | Desktop     | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | Desktop     | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP            | ProBook 4310s               | Notebook    | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0671e360b](https://linux-hardware.org/?probe=f0671e360b) | Apr 25, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Haier         | U144S                       | Notebook    | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a72ab8595e](https://linux-hardware.org/?probe=a72ab8595e) | Jan 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6deddd3d32](https://linux-hardware.org/?probe=6deddd3d32) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP            | EliteBook 1040 G3 Notebo... | Notebook    | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f483ddc44f](https://linux-hardware.org/?probe=f483ddc44f) | Jan 01, 2022 |
| MSI           | GL72M 7REX                  | Notebook    | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Dell          | 02YRK5 A02                  | Desktop     | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | Notebook    | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Supermicro    | X10SLL-F                    | Server      | [84ed224f36](https://linux-hardware.org/?probe=84ed224f36) | Nov 24, 2021 |
| HP            | 21B4 A01                    | Desktop     | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [0297d0f732](https://linux-hardware.org/?probe=0297d0f732) | Oct 25, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [45b1bba577](https://linux-hardware.org/?probe=45b1bba577) | Oct 24, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [6f87d9f9b8](https://linux-hardware.org/?probe=6f87d9f9b8) | Oct 01, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [2668fd795b](https://linux-hardware.org/?probe=2668fd795b) | Oct 01, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [254589b0bd](https://linux-hardware.org/?probe=254589b0bd) | Sep 16, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [f5bdbbea34](https://linux-hardware.org/?probe=f5bdbbea34) | Sep 15, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Pegatron      | Deepcam                     | Notebook    | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM           | 264070A                     | Notebook    | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP            | Mini 110-3500               | Notebook    | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| Dell          | 0DPRKF A07                  | Server      | [dee1f70644](https://linux-hardware.org/?probe=dee1f70644) | Mar 28, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| F5 Network... | PCA-0377-05                 | Server      | [14c76e0c83](https://linux-hardware.org/?probe=14c76e0c83) | Feb 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0a01176cbe](https://linux-hardware.org/?probe=0a01176cbe) | Feb 23, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway       | MX3631m                     | Notebook    | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM           | 26446AG                     | Notebook    | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM           | 26446AG                     | Notebook    | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| HP            | 2B0D A01                    | All in one  | [5c13b7bb96](https://linux-hardware.org/?probe=5c13b7bb96) | Nov 03, 2020 |
| Google        | Samus                       | Notebook    | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | Desktop     | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Lenovo        | 314C SDK0J40697 WIN 3305... | Mini pc     | [0f66b49a44](https://linux-hardware.org/?probe=0f66b49a44) | Sep 17, 2020 |
| Dell          | 0PU052                      | Desktop     | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Supermicro    | X10SLL-F                    | Server      | [dfbdbb0676](https://linux-hardware.org/?probe=dfbdbb0676) | Aug 25, 2020 |
| ASUSTek       | TS10                        | Desktop     | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| ASRock        | J3455M                      | Desktop     | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| Lenovo        | ThinkPad 11e 20ED001HUS     | Notebook    | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | Desktop     | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| Intel         | Merrifield                  | Tablet      | [d1f5e15d8c](https://linux-hardware.org/?probe=d1f5e15d8c) | May 23, 2020 |
| HP            | ZBook 15 G5                 | Notebook    | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology      | DS1019+                     | Notebook    | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology      | DS1019+                     | Notebook    | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology      | DS1019+                     | Notebook    | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |
| Unknown       | i855GM/E-ITE8712            | Desktop     | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | Desktop     | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.12.0               | 11        | 6.29%   |
| Alpine 3.18.0               | 10        | 5.71%   |
| Alpine 3.15.0               | 10        | 5.71%   |
| Alpine 3.19.0               | 9         | 5.14%   |
| Alpine 3.16.0               | 9         | 5.14%   |
| Alpine 3.15.4               | 9         | 5.14%   |
| Alpine 3.18.3               | 7         | 4%      |
| Alpine 3.15.0_alpha20210804 | 7         | 4%      |
| Alpine 3.19_alpha20230901   | 6         | 3.43%   |
| Alpine 3.18.4               | 6         | 3.43%   |
| Alpine 3.17_alpha20220809   | 5         | 2.86%   |
| Alpine 3.17.2               | 5         | 2.86%   |
| Alpine 3.14.0               | 5         | 2.86%   |
| Alpine 3.18.5               | 4         | 2.29%   |
| Alpine 3.18.2               | 4         | 2.29%   |
| Alpine 3.17.1               | 4         | 2.29%   |
| Alpine 3.17.0               | 4         | 2.29%   |
| Alpine 3.16.1               | 4         | 2.29%   |
| Alpine 3.14.2               | 4         | 2.29%   |
| Alpine 3.13.0_alpha20200917 | 4         | 2.29%   |
| Alpine 3.13.0_alpha20200626 | 4         | 2.29%   |
| Alpine 3.11.2               | 4         | 2.29%   |
| Alpine 3.16.2               | 3         | 1.71%   |
| Alpine 3.13.1               | 3         | 1.71%   |
| Alpine 3.13.0_alpha20201218 | 3         | 1.71%   |
| Alpine 3.18_alpha20230329   | 2         | 1.14%   |
| Alpine 3.16.3               | 2         | 1.14%   |
| Alpine 3.15.6               | 2         | 1.14%   |
| Alpine 3.14.3               | 2         | 1.14%   |
| Alpine 3.13.5               | 2         | 1.14%   |
| Alpine 3.13.2               | 2         | 1.14%   |
| Alpine 3.12.3               | 2         | 1.14%   |
| Alpine 3.8.4                | 1         | 0.57%   |
| Alpine 3.20.0_alpha20231219 | 1         | 0.57%   |
| Alpine 3.19.0_rc2           | 1         | 0.57%   |
| Alpine 3.17.4               | 1         | 0.57%   |
| Alpine 3.17.3               | 1         | 0.57%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.57%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.57%   |
| Alpine 3.15.2               | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 162       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.4.43-1-lts     | 8         | 4.44%   |
| 6.1.57-0-lts     | 3         | 1.67%   |
| 6.1.32-0-lts     | 3         | 1.67%   |
| 5.15.86-0-lts    | 3         | 1.67%   |
| 5.15.60-0-lts    | 3         | 1.67%   |
| 5.15.16-0-lts    | 3         | 1.67%   |
| 5.10.61-0-lts    | 3         | 1.67%   |
| 6.6.7-0-lts      | 2         | 1.11%   |
| 6.6.12-0-lts     | 2         | 1.11%   |
| 6.6.1-0-edge     | 2         | 1.11%   |
| 6.1.62-0-lts     | 2         | 1.11%   |
| 6.1.55-0-lts     | 2         | 1.11%   |
| 6.1.51-0-lts     | 2         | 1.11%   |
| 6.1.28-2-lts     | 2         | 1.11%   |
| 5.4.84-0-lts     | 2         | 1.11%   |
| 5.4.83-0-lts     | 2         | 1.11%   |
| 5.17.9-0-edge    | 2         | 1.11%   |
| 5.15.74-0-lts    | 2         | 1.11%   |
| 5.15.59-0-lts    | 2         | 1.11%   |
| 5.15.47-0-lts    | 2         | 1.11%   |
| 5.15.46-1-lts    | 2         | 1.11%   |
| 5.15.41-0-lts    | 2         | 1.11%   |
| 5.15.4-0-lts     | 2         | 1.11%   |
| 5.15.12-0-lts    | 2         | 1.11%   |
| 5.10.68-0-lts    | 2         | 1.11%   |
| 5.10.16-0-lts    | 2         | 1.11%   |
| 6.6.9-0-lts      | 1         | 0.56%   |
| 6.6.8-0-lts      | 1         | 0.56%   |
| 6.6.6-0-lts      | 1         | 0.56%   |
| 6.6.4-0-lts      | 1         | 0.56%   |
| 6.6.10-0-lts     | 1         | 0.56%   |
| 6.4.4-0-edge     | 1         | 0.56%   |
| 6.3.3-0-edge     | 1         | 0.56%   |
| 6.2.0-39-generic | 1         | 0.56%   |
| 6.2.0-37-generic | 1         | 0.56%   |
| 6.2.0-36-generic | 1         | 0.56%   |
| 6.1.71-haos      | 1         | 0.56%   |
| 6.1.69-0-lts     | 1         | 0.56%   |
| 6.1.64-0-rpi     | 1         | 0.56%   |
| 6.1.64-0-lts     | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 4.52%   |
| 6.1.57  | 3         | 1.69%   |
| 6.1.55  | 3         | 1.69%   |
| 6.1.32  | 3         | 1.69%   |
| 5.15.86 | 3         | 1.69%   |
| 5.15.60 | 3         | 1.69%   |
| 5.15.16 | 3         | 1.69%   |
| 5.15.0  | 3         | 1.69%   |
| 5.10.61 | 3         | 1.69%   |
| 6.6.7   | 2         | 1.13%   |
| 6.6.12  | 2         | 1.13%   |
| 6.6.1   | 2         | 1.13%   |
| 6.2.0   | 2         | 1.13%   |
| 6.1.64  | 2         | 1.13%   |
| 6.1.62  | 2         | 1.13%   |
| 6.1.51  | 2         | 1.13%   |
| 6.1.34  | 2         | 1.13%   |
| 6.1.28  | 2         | 1.13%   |
| 5.4.84  | 2         | 1.13%   |
| 5.4.83  | 2         | 1.13%   |
| 5.19.0  | 2         | 1.13%   |
| 5.17.9  | 2         | 1.13%   |
| 5.15.74 | 2         | 1.13%   |
| 5.15.59 | 2         | 1.13%   |
| 5.15.47 | 2         | 1.13%   |
| 5.15.46 | 2         | 1.13%   |
| 5.15.41 | 2         | 1.13%   |
| 5.15.4  | 2         | 1.13%   |
| 5.15.12 | 2         | 1.13%   |
| 5.10.68 | 2         | 1.13%   |
| 5.10.16 | 2         | 1.13%   |
| 6.6.9   | 1         | 0.56%   |
| 6.6.8   | 1         | 0.56%   |
| 6.6.6   | 1         | 0.56%   |
| 6.6.4   | 1         | 0.56%   |
| 6.6.10  | 1         | 0.56%   |
| 6.4.4   | 1         | 0.56%   |
| 6.3.3   | 1         | 0.56%   |
| 6.1.71  | 1         | 0.56%   |
| 6.1.69  | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 51        | 29.82%  |
| 6.1     | 33        | 19.3%   |
| 5.4     | 23        | 13.45%  |
| 5.10    | 23        | 13.45%  |
| 6.6     | 11        | 6.43%   |
| 5.17    | 4         | 2.34%   |
| 3.10    | 3         | 1.75%   |
| 6.2     | 2         | 1.17%   |
| 5.8     | 2         | 1.17%   |
| 5.19    | 2         | 1.17%   |
| 5.14    | 2         | 1.17%   |
| 4.4     | 2         | 1.17%   |
| 3.18    | 2         | 1.17%   |
| 6.4     | 1         | 0.58%   |
| 6.3     | 1         | 0.58%   |
| 6.0     | 1         | 0.58%   |
| 5.7     | 1         | 0.58%   |
| 5.6     | 1         | 0.58%   |
| 5.18    | 1         | 0.58%   |
| 5.16    | 1         | 0.58%   |
| 5.13    | 1         | 0.58%   |
| 5.12    | 1         | 0.58%   |
| 4.20    | 1         | 0.58%   |
| 4.14    | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 134       | 82.72%  |
| i686    | 19        | 11.73%  |
| aarch64 | 4         | 2.47%   |
| armv7l  | 3         | 1.85%   |
| i586    | 1         | 0.62%   |
| armv6l  | 1         | 0.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 126       | 77.78%  |
| XFCE    | 17        | 10.49%  |
| GNOME   | 8         | 4.94%   |
| KDE5    | 5         | 3.09%   |
| sway    | 2         | 1.23%   |
| LXQt    | 2         | 1.23%   |
| KDE     | 1         | 0.62%   |
| i3      | 1         | 0.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 96        | 57.83%  |
| X11     | 56        | 33.73%  |
| Wayland | 13        | 7.83%   |
| Tty     | 1         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 130       | 79.75%  |
| LightDM | 22        | 13.5%   |
| SDDM    | 5         | 3.07%   |
| GDM     | 3         | 1.84%   |
| LXDM    | 2         | 1.23%   |
| XDM     | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 102       | 61.45%  |
| Unknown | 50        | 30.12%  |
| en_US   | 7         | 4.22%   |
| ru_RU   | 3         | 1.81%   |
| en_GB   | 2         | 1.2%    |
| pt_BR   | 1         | 0.6%    |
| es_NI   | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 105       | 64.02%  |
| EFI  | 59        | 35.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 78.31%  |
| Btrfs   | 11        | 6.63%   |
| Overlay | 10        | 6.02%   |
| Tmpfs   | 6         | 3.61%   |
| Unknown | 3         | 1.81%   |
| F2fs    | 2         | 1.2%    |
| Zfs     | 1         | 0.6%    |
| Rootfs  | 1         | 0.6%    |
| Fake    | 1         | 0.6%    |
| Ext2    | 1         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 62.5%   |
| GPT     | 45        | 26.79%  |
| MBR     | 18        | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 87.2%   |
| Yes       | 21        | 12.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 92.12%  |
| Yes       | 13        | 7.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 22        | 13.58%  |
| Hewlett-Packard         | 21        | 12.96%  |
| Lenovo                  | 18        | 11.11%  |
| ASUSTek Computer        | 18        | 11.11%  |
| ASRock                  | 8         | 4.94%   |
| Gigabyte Technology     | 7         | 4.32%   |
| Acer                    | 7         | 4.32%   |
| Unknown                 | 7         | 4.32%   |
| Intel                   | 6         | 3.7%    |
| Fujitsu                 | 5         | 3.09%   |
| Apple                   | 5         | 3.09%   |
| Toshiba                 | 3         | 1.85%   |
| Raspberry Pi Foundation | 3         | 1.85%   |
| MSI                     | 3         | 1.85%   |
| IBM                     | 3         | 1.85%   |
| Google                  | 3         | 1.85%   |
| ZOTAC                   | 2         | 1.23%   |
| Gateway                 | 2         | 1.23%   |
| Wortmann AG             | 1         | 0.62%   |
| VIA Technologies        | 1         | 0.62%   |
| UGREEN                  | 1         | 0.62%   |
| Synology                | 1         | 0.62%   |
| Supermicro              | 1         | 0.62%   |
| Sony                    | 1         | 0.62%   |
| Shuttle                 | 1         | 0.62%   |
| Pegatron                | 1         | 0.62%   |
| Olivetti                | 1         | 0.62%   |
| Notebook                | 1         | 0.62%   |
| LG Electronics          | 1         | 0.62%   |
| Inventec                | 1         | 0.62%   |
| Haier                   | 1         | 0.62%   |
| Fanless Mini PC         | 1         | 0.62%   |
| F5 Networks             | 1         | 0.62%   |
| eMachines               | 1         | 0.62%   |
| ECS                     | 1         | 0.62%   |
| Compaq                  | 1         | 0.62%   |
| AMI                     | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 4.94%   |
| Dell Dell Thin Client Desktop 3030 LT    | 3         | 1.85%   |
| ASUS All Series                          | 3         | 1.85%   |
| RPi Raspberry Pi                         | 2         | 1.23%   |
| HP ProLiant DL360 G6                     | 2         | 1.23%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.23%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K     | 1         | 0.62%   |
| Wortmann AG M660SE                       | 1         | 0.62%   |
| VIA KM266APro-835                        | 1         | 0.62%   |
| UGREEN DX4600                            | 1         | 0.62%   |
| Toshiba WT8-A                            | 1         | 0.62%   |
| Toshiba Satellite Pro L50-A              | 1         | 0.62%   |
| Toshiba Satellite M645                   | 1         | 0.62%   |
| Synology DS1019+                         | 1         | 0.62%   |
| Supermicro X10SLL-F                      | 1         | 0.62%   |
| Sony VGN-UX27GN                          | 1         | 0.62%   |
| Shuttle DS81D                            | 1         | 0.62%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.62%   |
| Pegatron Deepcam                         | 1         | 0.62%   |
| Olivetti Spring Peak                     | 1         | 0.62%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.62%   |
| MSI MS-7C82                              | 1         | 0.62%   |
| MSI MS-7877                              | 1         | 0.62%   |
| MSI GL72M 7REX                           | 1         | 0.62%   |
| LG LW25-B7HG                             | 1         | 0.62%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.62%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 0.62%   |
| Lenovo V15 G3 IAP 82TT                   | 1         | 0.62%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.62%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.62%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.62%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.62%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.62%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.62%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.62%   |
| Lenovo ThinkCentre M93p 10AB0016US       | 1         | 0.62%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 0.62%   |
| Lenovo MIIX 310-10ICR 80SG               | 1         | 0.62%   |
| Lenovo IdeaPad S145-15API 81V7           | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 8         | 4.94%   |
| Unknown             | 8         | 4.94%   |
| Lenovo ThinkPad     | 7         | 4.32%   |
| Acer Aspire         | 6         | 3.7%    |
| Dell OptiPlex       | 5         | 3.09%   |
| RPi Raspberry       | 3         | 1.85%   |
| HP ProLiant         | 3         | 1.85%   |
| HP EliteBook        | 3         | 1.85%   |
| HP Compaq           | 3         | 1.85%   |
| Dell Dell           | 3         | 1.85%   |
| ASUS All            | 3         | 1.85%   |
| Toshiba Satellite   | 2         | 1.23%   |
| Lenovo ThinkCentre  | 2         | 1.23%   |
| Lenovo IdeaPad      | 2         | 1.23%   |
| HP Presario         | 2         | 1.23%   |
| HP Laptop           | 2         | 1.23%   |
| Gigabyte Z490I      | 2         | 1.23%   |
| Fujitsu LIFEBOOK    | 2         | 1.23%   |
| Dell XPS            | 2         | 1.23%   |
| Dell Latitude       | 2         | 1.23%   |
| ASUS PRIME          | 2         | 1.23%   |
| ZOTAC ZBOX-EN1070   | 1         | 0.62%   |
| Wortmann AG M660SE  | 1         | 0.62%   |
| VIA KM266APro-835   | 1         | 0.62%   |
| UGREEN DX4600       | 1         | 0.62%   |
| Toshiba WT8-A       | 1         | 0.62%   |
| Synology DS1019+    | 1         | 0.62%   |
| Supermicro X10SLL-F | 1         | 0.62%   |
| Sony VGN-UX27GN     | 1         | 0.62%   |
| Shuttle DS81D       | 1         | 0.62%   |
| Pegatron Deepcam    | 1         | 0.62%   |
| Olivetti Spring     | 1         | 0.62%   |
| Notebook NV4XMB     | 1         | 0.62%   |
| MSI MS-7C82         | 1         | 0.62%   |
| MSI MS-7877         | 1         | 0.62%   |
| MSI GL72M           | 1         | 0.62%   |
| LG LW25-B7HG        | 1         | 0.62%   |
| Lenovo Yoga         | 1         | 0.62%   |
| Lenovo Y70-70       | 1         | 0.62%   |
| Lenovo V15          | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 19        | 11.73%  |
| 2012    | 14        | 8.64%   |
| 2010    | 12        | 7.41%   |
| 2019    | 11        | 6.79%   |
| 2018    | 11        | 6.79%   |
| 2016    | 10        | 6.17%   |
| 2013    | 10        | 6.17%   |
| Unknown | 10        | 6.17%   |
| 2017    | 9         | 5.56%   |
| 2020    | 8         | 4.94%   |
| 2021    | 7         | 4.32%   |
| 2011    | 6         | 3.7%    |
| 2009    | 6         | 3.7%    |
| 2006    | 6         | 3.7%    |
| 2015    | 5         | 3.09%   |
| 2007    | 5         | 3.09%   |
| 2022    | 4         | 2.47%   |
| 2023    | 2         | 1.23%   |
| 2005    | 2         | 1.23%   |
| 2001    | 2         | 1.23%   |
| 2008    | 1         | 0.62%   |
| 2004    | 1         | 0.62%   |
| 1999    | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 79        | 48.77%  |
| Desktop        | 56        | 34.57%  |
| Mini pc        | 11        | 6.79%   |
| System on chip | 5         | 3.09%   |
| Server         | 5         | 3.09%   |
| Tablet         | 3         | 1.85%   |
| All in one     | 2         | 1.23%   |
| Convertible    | 1         | 0.62%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 161       | 98.77%  |
| Enabled  | 2         | 1.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 159       | 98.15%  |
| Yes  | 3         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 33        | 19.53%  |
| 3.01-4.0        | 32        | 18.93%  |
| 16.01-24.0      | 27        | 15.98%  |
| 8.01-16.0       | 20        | 11.83%  |
| 1.01-2.0        | 14        | 8.28%   |
| 0.51-1.0        | 14        | 8.28%   |
| 32.01-64.0      | 12        | 7.1%    |
| 0.01-0.5        | 6         | 3.55%   |
| 2.01-3.0        | 5         | 2.96%   |
| 64.01-256.0     | 5         | 2.96%   |
| More than 256.0 | 1         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 49        | 28.65%  |
| 1.01-2.0  | 34        | 19.88%  |
| 0.51-1.0  | 32        | 18.71%  |
| 2.01-3.0  | 18        | 10.53%  |
| 3.01-4.0  | 13        | 7.6%    |
| 4.01-8.0  | 11        | 6.43%   |
| 8.01-16.0 | 5         | 2.92%   |
| 0         | 5         | 2.92%   |
| Unknown   | 4         | 2.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 63.47%  |
| 2      | 31        | 18.56%  |
| 3      | 10        | 5.99%   |
| 4      | 8         | 4.79%   |
| 5      | 4         | 2.4%    |
| 0      | 3         | 1.8%    |
| 14     | 2         | 1.2%    |
| 12     | 1         | 0.6%    |
| 10     | 1         | 0.6%    |
| 7      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 78.05%  |
| Yes       | 36        | 21.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 85.8%   |
| No        | 23        | 14.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 61.21%  |
| No        | 64        | 38.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 55.49%  |
| Yes       | 73        | 44.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 39        | 22.94%  |
| Germany      | 20        | 11.76%  |
| Canada       | 13        | 7.65%   |
| Russia       | 12        | 7.06%   |
| UK           | 9         | 5.29%   |
| Brazil       | 7         | 4.12%   |
| Sweden       | 5         | 2.94%   |
| Spain        | 5         | 2.94%   |
| Australia    | 4         | 2.35%   |
| Norway       | 3         | 1.76%   |
| France       | 3         | 1.76%   |
| China        | 3         | 1.76%   |
| Slovakia     | 2         | 1.18%   |
| Portugal     | 2         | 1.18%   |
| Poland       | 2         | 1.18%   |
| Netherlands  | 2         | 1.18%   |
| Mexico       | 2         | 1.18%   |
| Italy        | 2         | 1.18%   |
| Israel       | 2         | 1.18%   |
| Guatemala    | 2         | 1.18%   |
| Finland      | 2         | 1.18%   |
| Austria      | 2         | 1.18%   |
| Argentina    | 2         | 1.18%   |
| Vietnam      | 1         | 0.59%   |
| Venezuela    | 1         | 0.59%   |
| Ukraine      | 1         | 0.59%   |
| UAE          | 1         | 0.59%   |
| Thailand     | 1         | 0.59%   |
| Switzerland  | 1         | 0.59%   |
| South Korea  | 1         | 0.59%   |
| South Africa | 1         | 0.59%   |
| Romania      | 1         | 0.59%   |
| Puerto Rico  | 1         | 0.59%   |
| Philippines  | 1         | 0.59%   |
| Pakistan     | 1         | 0.59%   |
| Nicaragua    | 1         | 0.59%   |
| Kenya        | 1         | 0.59%   |
| Jamaica      | 1         | 0.59%   |
| Ireland      | 1         | 0.59%   |
| Indonesia    | 1         | 0.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Springfield       | 7         | 4.02%   |
| St Petersburg     | 6         | 3.45%   |
| Manitowoc         | 5         | 2.87%   |
| Vernon            | 4         | 2.3%    |
| Moscow            | 3         | 1.72%   |
| Traunstein        | 2         | 1.15%   |
| Sydney            | 2         | 1.15%   |
| Stuttgart         | 2         | 1.15%   |
| Stratford         | 2         | 1.15%   |
| Siegsdorf         | 2         | 1.15%   |
| Harrisonburg      | 2         | 1.15%   |
| Guatemala City    | 2         | 1.15%   |
| Gothenburg        | 2         | 1.15%   |
| Fulham            | 2         | 1.15%   |
| Frankfurt am Main | 2         | 1.15%   |
| As                | 2         | 1.15%   |
| Zurich            | 1         | 0.57%   |
| Zhangzhou         | 1         | 0.57%   |
| Yakima            | 1         | 0.57%   |
| Waukesha          | 1         | 0.57%   |
| Vienna            | 1         | 0.57%   |
| Ventura           | 1         | 0.57%   |
| Vejle             | 1         | 0.57%   |
| Vancouver         | 1         | 0.57%   |
| Tymovskoye        | 1         | 0.57%   |
| Tuusula           | 1         | 0.57%   |
| Turin             | 1         | 0.57%   |
| Topeka            | 1         | 0.57%   |
| Tinh Binh Duong   | 1         | 0.57%   |
| Thornhill         | 1         | 0.57%   |
| Thame             | 1         | 0.57%   |
| Tampa             | 1         | 0.57%   |
| Stockholm         | 1         | 0.57%   |
| Stillwater        | 1         | 0.57%   |
| Stewartstown      | 1         | 0.57%   |
| Sorgues           | 1         | 0.57%   |
| Somerset          | 1         | 0.57%   |
| Ski               | 1         | 0.57%   |
| Sisteron          | 1         | 0.57%   |
| Semily            | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 32        | 57     | 13.56%  |
| WDC                         | 27        | 59     | 11.44%  |
| Seagate                     | 24        | 58     | 10.17%  |
| Unknown                     | 22        | 28     | 9.32%   |
| Toshiba                     | 17        | 20     | 7.2%    |
| Hitachi                     | 12        | 12     | 5.08%   |
| Crucial                     | 11        | 20     | 4.66%   |
| Kingston                    | 10        | 14     | 4.24%   |
| HGST                        | 10        | 10     | 4.24%   |
| SanDisk                     | 8         | 11     | 3.39%   |
| A-DATA Technology           | 8         | 10     | 3.39%   |
| SK hynix                    | 7         | 9      | 2.97%   |
| Intel                       | 7         | 11     | 2.97%   |
| SPCC                        | 4         | 4      | 1.69%   |
| Micron Technology           | 4         | 5      | 1.69%   |
| Transcend                   | 2         | 2      | 0.85%   |
| LITEON                      | 2         | 2      | 0.85%   |
| Intenso                     | 2         | 2      | 0.85%   |
| Fujitsu                     | 2         | 2      | 0.85%   |
| STEC                        | 1         | 1      | 0.42%   |
| SINTECHI                    | 1         | 1      | 0.42%   |
| Secure                      | 1         | 1      | 0.42%   |
| PNY                         | 1         | 1      | 0.42%   |
| Plextor                     | 1         | 1      | 0.42%   |
| Phison Electronics          | 1         | 1      | 0.42%   |
| NETAPP                      | 1         | 1      | 0.42%   |
| Netac                       | 1         | 1      | 0.42%   |
| Maxtor                      | 1         | 1      | 0.42%   |
| Lexar                       | 1         | 1      | 0.42%   |
| KIOXIA                      | 1         | 1      | 0.42%   |
| Kingston Technology Company | 1         | 1      | 0.42%   |
| KingSpec                    | 1         | 1      | 0.42%   |
| Kingmax                     | 1         | 1      | 0.42%   |
| KC600                       | 1         | 1      | 0.42%   |
| JMicron Technology          | 1         | 1      | 0.42%   |
| INNOVATION IT               | 1         | 1      | 0.42%   |
| IBM                         | 1         | 1      | 0.42%   |
| Emtec                       | 1         | 1      | 0.42%   |
| Dell                        | 1         | 2      | 0.42%   |
| China                       | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                            | 5         | 1.79%   |
| Unknown MMC Card  4GB                             | 4         | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.43%   |
| Unknown MMC Card  64GB                            | 3         | 1.07%   |
| Unknown MMC Card  32GB                            | 3         | 1.07%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 3         | 1.07%   |
| Samsung SSD 870 EVO 1TB                           | 3         | 1.07%   |
| Crucial CT500MX500SSD1 500GB                      | 3         | 1.07%   |
| Crucial CT1000MX500SSD1 1TB                       | 3         | 1.07%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2         | 0.71%   |
| WDC WD3000BLFS-60YBU2 304GB                       | 2         | 0.71%   |
| Unknown SD/MMC/MS PRO 256GB                       | 2         | 0.71%   |
| Unknown MMC Card                                  | 2         | 0.71%   |
| Toshiba MQ01ABD100 1TB                            | 2         | 0.71%   |
| Toshiba MQ01ABD075 752GB                          | 2         | 0.71%   |
| Seagate ST4000VN008-2DR1 4TB                      | 2         | 0.71%   |
| Seagate ST380815AS 80GB                           | 2         | 0.71%   |
| Samsung SSD 980 PRO 1TB                           | 2         | 0.71%   |
| Samsung SSD 960 EVO 500GB                         | 2         | 0.71%   |
| Samsung SSD 870 QVO 1TB                           | 2         | 0.71%   |
| Samsung SSD 860 1TB                               | 2         | 0.71%   |
| Samsung NVMe SSD Drive 1024GB                     | 2         | 0.71%   |
| Kingston SV300S37A120G 120GB SSD                  | 2         | 0.71%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 0.71%   |
| Kingston SA400S3 120GB SSD                        | 2         | 0.71%   |
| Intenso SSD 128GB                                 | 2         | 0.71%   |
| Crucial CT120BX500SSD1 120GB                      | 2         | 0.71%   |
| A-DATA SU800 128GB SSD                            | 2         | 0.71%   |
| WDC WDS500G2X0C-00L350 500GB                      | 1         | 0.36%   |
| WDC WDS500G2B0A 500GB SSD                         | 1         | 0.36%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1         | 0.36%   |
| WDC WDS250G2B0B 250GB SSD                         | 1         | 0.36%   |
| WDC WDS250G2B0A 250GB SSD                         | 1         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1         | 0.36%   |
| WDC WD80EMAZ-00WJTA0 8TB                          | 1         | 0.36%   |
| WDC WD80EFAX-68LHPN0 8TB                          | 1         | 0.36%   |
| WDC WD800AAJS-00 80GB                             | 1         | 0.36%   |
| WDC WD7500BPKT-80PK4T0 752GB                      | 1         | 0.36%   |
| WDC WD5003ABYZ-0 500GB                            | 1         | 0.36%   |
| WDC WD5000BEVT-7 500GB                            | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 58     | 25.53%  |
| WDC                 | 21        | 48     | 22.34%  |
| Toshiba             | 14        | 16     | 14.89%  |
| Hitachi             | 12        | 12     | 12.77%  |
| HGST                | 10        | 10     | 10.64%  |
| Samsung Electronics | 5         | 9      | 5.32%   |
| Unknown             | 2         | 2      | 2.13%   |
| Fujitsu             | 2         | 2      | 2.13%   |
| SINTECHI            | 1         | 1      | 1.06%   |
| Maxtor              | 1         | 1      | 1.06%   |
| JMicron Technology  | 1         | 1      | 1.06%   |
| IBM                 | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 23     | 17.07%  |
| Crucial             | 11        | 20     | 13.41%  |
| Kingston            | 10        | 12     | 12.2%   |
| WDC                 | 5         | 7      | 6.1%    |
| Intel               | 5         | 7      | 6.1%    |
| A-DATA Technology   | 5         | 5      | 6.1%    |
| SPCC                | 4         | 4      | 4.88%   |
| SanDisk             | 4         | 5      | 4.88%   |
| Transcend           | 2         | 2      | 2.44%   |
| SK hynix            | 2         | 3      | 2.44%   |
| Micron Technology   | 2         | 2      | 2.44%   |
| LITEON              | 2         | 2      | 2.44%   |
| Intenso             | 2         | 2      | 2.44%   |
| Toshiba             | 1         | 1      | 1.22%   |
| Secure              | 1         | 1      | 1.22%   |
| PNY                 | 1         | 1      | 1.22%   |
| Plextor             | 1         | 1      | 1.22%   |
| Netac               | 1         | 1      | 1.22%   |
| Lexar               | 1         | 1      | 1.22%   |
| KingSpec            | 1         | 1      | 1.22%   |
| Kingmax             | 1         | 1      | 1.22%   |
| KC600               | 1         | 1      | 1.22%   |
| INNOVATION IT       | 1         | 1      | 1.22%   |
| Emtec               | 1         | 1      | 1.22%   |
| Dell                | 1         | 2      | 1.22%   |
| China               | 1         | 1      | 1.22%   |
| AMD                 | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 80        | 161    | 39.8%   |
| SSD     | 64        | 109    | 31.84%  |
| NVMe    | 35        | 64     | 17.41%  |
| MMC     | 20        | 27     | 9.95%   |
| Unknown | 2         | 3      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 119       | 262    | 65.38%  |
| NVMe | 35        | 64     | 19.23%  |
| MMC  | 20        | 27     | 10.99%  |
| SAS  | 8         | 11     | 4.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 160    | 65.75%  |
| 0.51-1.0   | 29        | 44     | 19.86%  |
| 3.01-4.0   | 6         | 17     | 4.11%   |
| 4.01-10.0  | 5         | 21     | 3.42%   |
| 1.01-2.0   | 4         | 8      | 2.74%   |
| 2.01-3.0   | 3         | 7      | 2.05%   |
| 10.01-20.0 | 3         | 13     | 2.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 33        | 19.76%  |
| Unknown        | 30        | 17.96%  |
| 1-20           | 28        | 16.77%  |
| 251-500        | 16        | 9.58%   |
| 501-1000       | 16        | 9.58%   |
| 21-50          | 13        | 7.78%   |
| More than 3000 | 11        | 6.59%   |
| 1001-2000      | 8         | 4.79%   |
| 51-100         | 8         | 4.79%   |
| 2001-3000      | 4         | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 90        | 54.22%  |
| Unknown        | 30        | 18.07%  |
| 21-50          | 12        | 7.23%   |
| 251-500        | 10        | 6.02%   |
| 51-100         | 10        | 6.02%   |
| 501-1000       | 5         | 3.01%   |
| 101-250        | 3         | 1.81%   |
| 1001-2000      | 3         | 1.81%   |
| 2001-3000      | 2         | 1.2%    |
| More than 3000 | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 7.41%   |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 3.7%    |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 3.7%    |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 3.7%    |
| Secure Net 256GB SSD                           | 1         | 1      | 3.7%    |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.7%    |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 3.7%    |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 3.7%    |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 3.7%    |
| Samsung Electronics SSD PM81 128GB             | 1         | 1      | 3.7%    |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 3.7%    |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 3.7%    |
| Netac SSD 256GB                                | 1         | 1      | 3.7%    |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 3.7%    |
| Maxtor 2B020H1 20GB                            | 1         | 1      | 3.7%    |
| Kingmax SSD 120G                               | 1         | 1      | 3.7%    |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 3.7%    |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 3.7%    |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 3.7%    |
| Hitachi HTS72101 99GB                          | 1         | 1      | 3.7%    |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 3.7%    |
| HGST HTS725050A7 500GB                         | 1         | 1      | 3.7%    |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 3.7%    |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 3.7%    |
| A-DATA Technology SU800 128GB SSD              | 1         | 1      | 3.7%    |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 18.52%  |
| WDC                 | 3         | 15     | 11.11%  |
| Seagate             | 3         | 3      | 11.11%  |
| Samsung Electronics | 3         | 5      | 11.11%  |
| HGST                | 3         | 3      | 11.11%  |
| Toshiba             | 2         | 2      | 7.41%   |
| A-DATA Technology   | 2         | 2      | 7.41%   |
| Secure              | 1         | 1      | 3.7%    |
| SanDisk             | 1         | 1      | 3.7%    |
| Netac               | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Maxtor              | 1         | 1      | 3.7%    |
| Kingmax             | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 26.32%  |
| WDC                 | 3         | 15     | 15.79%  |
| Seagate             | 3         | 3      | 15.79%  |
| HGST                | 3         | 3      | 15.79%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 4      | 10.53%  |
| Maxtor              | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 33     | 73.08%  |
| SSD  | 6         | 7      | 23.08%  |
| NVMe | 1         | 1      | 3.85%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 96        | 228    | 53.63%  |
| Detected | 59        | 95     | 32.96%  |
| Malfunc  | 24        | 41     | 13.41%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 107       | 56.91%  |
| AMD                          | 20        | 10.64%  |
| Samsung Electronics          | 17        | 9.04%   |
| SanDisk                      | 6         | 3.19%   |
| SK hynix                     | 4         | 2.13%   |
| LSI Logic / Symbios Logic    | 4         | 2.13%   |
| ADATA Technology             | 4         | 2.13%   |
| VIA Technologies             | 3         | 1.6%    |
| Nvidia                       | 3         | 1.6%    |
| Marvell Technology Group     | 3         | 1.6%    |
| ASMedia Technology           | 3         | 1.6%    |
| Micron Technology            | 2         | 1.06%   |
| KIOXIA                       | 2         | 1.06%   |
| Hewlett-Packard              | 2         | 1.06%   |
| Adaptec                      | 2         | 1.06%   |
| Toshiba America Info Systems | 1         | 0.53%   |
| Promise Technology           | 1         | 0.53%   |
| Phison Electronics           | 1         | 0.53%   |
| Micron/Crucial Technology    | 1         | 0.53%   |
| Kingston Technology Company  | 1         | 0.53%   |
| Broadcom / LSI               | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 6.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 5.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 4.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 2.16%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 1.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 1.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 1.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.73%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 3         | 1.3%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.3%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.3%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 1.3%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 0.87%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.87%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 0.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 0.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 104       | 57.14%  |
| NVMe | 34        | 18.68%  |
| IDE  | 26        | 14.29%  |
| RAID | 14        | 7.69%   |
| SAS  | 4         | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 130       | 79.27%  |
| AMD          | 24        | 14.63%  |
| ARM          | 7         | 4.27%   |
| iSH          | 1         | 0.61%   |
| CentaurHauls | 1         | 0.61%   |
| Unknown      | 1         | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N2807 @ 1.58GHz       | 3         | 1.76%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 2         | 1.18%   |
| Intel Pentium M processor 1.70GHz       | 2         | 1.18%   |
| Intel Pentium III (Coppermine)          | 2         | 1.18%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 2         | 1.18%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 1.18%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 2         | 1.18%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.18%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2         | 1.18%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 1.18%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 2         | 1.18%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 2         | 1.18%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 2         | 1.18%   |
| Intel Atom CPU N455 @ 1.66GHz           | 2         | 1.18%   |
| Intel Atom CPU D525 @ 1.80GHz           | 2         | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.18%   |
| ARM Processor                           | 2         | 1.18%   |
| ARM BCM2835 Processor                   | 2         | 1.18%   |
| AMD FX-8350 Eight-Core Processor        | 2         | 1.18%   |
| iSH Processor                           | 1         | 0.59%   |
| Intel Xeon Gold 6336Y CPU @ 2.40GHz     | 1         | 0.59%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1         | 0.59%   |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 0.59%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 0.59%   |
| Intel Xeon CPU L5630 @ 2.13GHz          | 1         | 0.59%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz    | 1         | 0.59%   |
| Intel Pentium M processor 1.60GHz       | 1         | 0.59%   |
| Intel Pentium M processor 1.50GHz       | 1         | 0.59%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1         | 0.59%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 0.59%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.59%   |
| Intel Pentium CPU E5700 @ 3.00GHz       | 1         | 0.59%   |
| Intel Pentium CPU D1508 @ 2.20GHz       | 1         | 0.59%   |
| Intel Mobile Pentium MMX                | 1         | 0.59%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 0.59%   |
| Intel Genuine CPU 4000 @ 500MHz         | 1         | 0.59%   |
| Intel Core Solo CPU U1500 @ 1.33GHz     | 1         | 0.59%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 32        | 19.16%  |
| Other                | 18        | 10.78%  |
| Intel Celeron        | 18        | 10.78%  |
| Intel Core i7        | 15        | 8.98%   |
| Intel Core i3        | 13        | 7.78%   |
| Intel Atom           | 12        | 7.19%   |
| Intel Xeon           | 6         | 3.59%   |
| AMD Ryzen 7          | 5         | 2.99%   |
| Intel Pentium M      | 4         | 2.4%    |
| Intel Pentium        | 4         | 2.4%    |
| Intel Core 2 Duo     | 4         | 2.4%    |
| Intel Core i9        | 3         | 1.8%    |
| AMD Ryzen 5          | 3         | 1.8%    |
| Intel Pentium III    | 2         | 1.2%    |
| Intel Genuine        | 2         | 1.2%    |
| Intel Core 2         | 2         | 1.2%    |
| ARM BCM              | 2         | 1.2%    |
| AMD FX               | 2         | 1.2%    |
| AMD A4               | 2         | 1.2%    |
| Intel Xeon Gold      | 1         | 0.6%    |
| Intel Pentium Dual   | 1         | 0.6%    |
| Intel Core Solo      | 1         | 0.6%    |
| Intel Core m3        | 1         | 0.6%    |
| Intel Core Duo       | 1         | 0.6%    |
| Intel Celeron M      | 1         | 0.6%    |
| ARM ARMv7            | 1         | 0.6%    |
| ARM AArch64          | 1         | 0.6%    |
| AMD Turion 64 Mobile | 1         | 0.6%    |
| AMD Sempron          | 1         | 0.6%    |
| AMD Ryzen 9          | 1         | 0.6%    |
| AMD Ryzen 3          | 1         | 0.6%    |
| AMD G                | 1         | 0.6%    |
| AMD E2               | 1         | 0.6%    |
| AMD E1               | 1         | 0.6%    |
| AMD A8               | 1         | 0.6%    |
| AMD A6               | 1         | 0.6%    |
| AMD A10              | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 65        | 38.92%  |
| 4       | 52        | 31.14%  |
| 1       | 18        | 10.78%  |
| 8       | 7         | 4.19%   |
| 6       | 7         | 4.19%   |
| Unknown | 6         | 3.59%   |
| 12      | 4         | 2.4%    |
| 10      | 2         | 1.2%    |
| 48      | 1         | 0.6%    |
| 32      | 1         | 0.6%    |
| 24      | 1         | 0.6%    |
| 16      | 1         | 0.6%    |
| 14      | 1         | 0.6%    |
| 3       | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 152       | 93.25%  |
| Unknown | 6         | 3.68%   |
| 2       | 4         | 2.45%   |
| 0       | 1         | 0.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 80        | 49.38%  |
| 2       | 76        | 46.91%  |
| Unknown | 6         | 3.7%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 87        | 52.73%  |
| 32-bit, 64-bit | 72        | 43.64%  |
| 32-bit         | 5         | 3.03%   |
| 64-bit         | 1         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 56.65%  |
| 0x306c3    | 8         | 4.62%   |
| 0x306a9    | 5         | 2.89%   |
| 0x30678    | 5         | 2.89%   |
| 0x906ea    | 4         | 2.31%   |
| 0x206c2    | 3         | 1.73%   |
| 0x20655    | 3         | 1.73%   |
| 0x106ca    | 3         | 1.73%   |
| 0x806eb    | 2         | 1.16%   |
| 0x806c1    | 2         | 1.16%   |
| 0x506e3    | 2         | 1.16%   |
| 0x506c9    | 2         | 1.16%   |
| 0x406c4    | 2         | 1.16%   |
| 0x206a7    | 2         | 1.16%   |
| 0x106e5    | 2         | 1.16%   |
| 0x1067a    | 2         | 1.16%   |
| 0x08108102 | 2         | 1.16%   |
| 0x06006704 | 2         | 1.16%   |
| 0xb0671    | 1         | 0.58%   |
| 0xa0671    | 1         | 0.58%   |
| 0xa0655    | 1         | 0.58%   |
| 0x906a3    | 1         | 0.58%   |
| 0x90672    | 1         | 0.58%   |
| 0x806ec    | 1         | 0.58%   |
| 0x806ea    | 1         | 0.58%   |
| 0x706e5    | 1         | 0.58%   |
| 0x6fd      | 1         | 0.58%   |
| 0x6f2      | 1         | 0.58%   |
| 0x6d8      | 1         | 0.58%   |
| 0x68a      | 1         | 0.58%   |
| 0x683      | 1         | 0.58%   |
| 0x606a6    | 1         | 0.58%   |
| 0x306d4    | 1         | 0.58%   |
| 0x0a20120e | 1         | 0.58%   |
| 0x08701021 | 1         | 0.58%   |
| 0x08608103 | 1         | 0.58%   |
| 0x08108109 | 1         | 0.58%   |
| 0x0810100b | 1         | 0.58%   |
| 0x0800820d | 1         | 0.58%   |
| 0x06000817 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 17        | 10.12%  |
| KabyLake         | 16        | 9.52%   |
| Haswell          | 15        | 8.93%   |
| Unknown          | 15        | 8.93%   |
| P6               | 10        | 5.95%   |
| IvyBridge        | 9         | 5.36%   |
| Westmere         | 8         | 4.76%   |
| Skylake          | 7         | 4.17%   |
| SandyBridge      | 7         | 4.17%   |
| Penryn           | 6         | 3.57%   |
| Bonnell          | 6         | 3.57%   |
| Goldmont         | 5         | 2.98%   |
| Zen+             | 4         | 2.38%   |
| IceLake          | 4         | 2.38%   |
| Broadwell        | 4         | 2.38%   |
| Alderlake Hybrid | 4         | 2.38%   |
| TigerLake        | 3         | 1.79%   |
| Piledriver       | 3         | 1.79%   |
| Excavator        | 3         | 1.79%   |
| Core             | 3         | 1.79%   |
| CometLake        | 3         | 1.79%   |
| Zen 3            | 2         | 1.19%   |
| Zen 2            | 2         | 1.19%   |
| Nehalem          | 2         | 1.19%   |
| Jaguar           | 2         | 1.19%   |
| Bobcat           | 2         | 1.19%   |
| Zen              | 1         | 0.6%    |
| Puma             | 1         | 0.6%    |
| K8 Hammer        | 1         | 0.6%    |
| K6               | 1         | 0.6%    |
| K10              | 1         | 0.6%    |
| Goldmont plus    | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 110       | 63.22%  |
| AMD                        | 34        | 19.54%  |
| Nvidia                     | 18        | 10.34%  |
| Matrox Electronics Systems | 4         | 2.3%    |
| VIA Technologies           | 3         | 1.72%   |
| Neomagic                   | 2         | 1.15%   |
| ASPEED Technology          | 2         | 1.15%   |
| S3 Graphics                | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 5.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 3.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 2.49%   |
| Intel HD Graphics 500                                                                    | 4         | 1.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.49%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.49%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.49%   |
| AMD ES1000                                                                               | 3         | 1.49%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 1%      |
| Intel UHD Graphics 620                                                                   | 2         | 1%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1%      |
| Intel Iris Plus Graphics G7                                                              | 2         | 1%      |
| Intel HD Graphics 630                                                                    | 2         | 1%      |
| Intel HD Graphics 620                                                                    | 2         | 1%      |
| Intel HD Graphics 530                                                                    | 2         | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1%      |
| Intel AlderLake-S GT1                                                                    | 2         | 1%      |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1%      |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1%      |
| AMD Lucienne                                                                             | 2         | 1%      |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 89        | 52.98%  |
| 1 x AMD         | 27        | 16.07%  |
| Other           | 10        | 5.95%   |
| Intel + Nvidia  | 9         | 5.36%   |
| 2 x Intel       | 8         | 4.76%   |
| 1 x Nvidia      | 7         | 4.17%   |
| Intel + AMD     | 4         | 2.38%   |
| 1 x Matrox      | 3         | 1.79%   |
| 1 x VIA         | 2         | 1.19%   |
| 1 x Neomagic    | 2         | 1.19%   |
| 1 x ASPEED      | 2         | 1.19%   |
| 2 x AMD         | 1         | 0.6%    |
| 1 x S3 Graphics | 1         | 0.6%    |
| Nvidia + Matrox | 1         | 0.6%    |
| AMD + VIA       | 1         | 0.6%    |
| AMD + Nvidia    | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 134       | 80.72%  |
| Unknown     | 28        | 16.87%  |
| Proprietary | 4         | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 84.76%  |
| 0.01-0.5   | 11        | 6.71%   |
| 1.01-2.0   | 4         | 2.44%   |
| 7.01-8.0   | 3         | 1.83%   |
| 0.51-1.0   | 3         | 1.83%   |
| 3.01-4.0   | 2         | 1.22%   |
| 2.01-3.0   | 1         | 0.61%   |
| 8.01-16.0  | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 11.51%  |
| LG Display              | 14        | 10.07%  |
| BOE                     | 11        | 7.91%   |
| Samsung Electronics     | 10        | 7.19%   |
| Dell                    | 10        | 7.19%   |
| Chimei Innolux          | 8         | 5.76%   |
| Goldstar                | 7         | 5.04%   |
| BenQ                    | 5         | 3.6%    |
| AOC                     | 5         | 3.6%    |
| Apple                   | 4         | 2.88%   |
| LG Philips              | 3         | 2.16%   |
| InfoVision              | 3         | 2.16%   |
| Hewlett-Packard         | 3         | 2.16%   |
| Chi Mei Optoelectronics | 3         | 2.16%   |
| Acer                    | 3         | 2.16%   |
| Vizio                   | 2         | 1.44%   |
| Sharp                   | 2         | 1.44%   |
| Philips                 | 2         | 1.44%   |
| PANDA                   | 2         | 1.44%   |
| Lenovo                  | 2         | 1.44%   |
| Jean                    | 2         | 1.44%   |
| HannStar                | 2         | 1.44%   |
| Belinea                 | 2         | 1.44%   |
| ViewSonic               | 1         | 0.72%   |
| Sony                    | 1         | 0.72%   |
| SKY                     | 1         | 0.72%   |
| Sceptre Tech            | 1         | 0.72%   |
| Quanta Display          | 1         | 0.72%   |
| ONN                     | 1         | 0.72%   |
| Mi                      | 1         | 0.72%   |
| KVM                     | 1         | 0.72%   |
| Huion                   | 1         | 0.72%   |
| Envision                | 1         | 0.72%   |
| Elo Touch               | 1         | 0.72%   |
| Element                 | 1         | 0.72%   |
| EDI                     | 1         | 0.72%   |
| DENON                   | 1         | 0.72%   |
| CTC                     | 1         | 0.72%   |
| CSO                     | 1         | 0.72%   |
| CPT                     | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 3         | 1.97%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 1.97%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.32%   |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                  | 2         | 1.32%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.32%   |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                  | 2         | 1.32%   |
| Vizio VX42L HDTV10A VIZ0030 1366x768 930x523mm 42.0-inch              | 1         | 0.66%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                  | 1         | 0.66%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.66%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.66%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 0.66%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.66%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.66%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1         | 0.66%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch    | 1         | 0.66%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.66%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.66%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.66%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.66%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch               | 1         | 0.66%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.66%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 0.66%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                      | 1         | 0.66%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.66%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.66%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.66%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.66%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.66%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.66%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 1         | 0.66%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.66%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 28.03%  |
| 1366x768 (WXGA)    | 29        | 21.97%  |
| 3840x2160 (4K)     | 7         | 5.3%    |
| 1680x1050 (WSXGA+) | 7         | 5.3%    |
| 1280x800 (WXGA)    | 7         | 5.3%    |
| 2560x1440 (QHD)    | 6         | 4.55%   |
| 1280x1024 (SXGA)   | 6         | 4.55%   |
| 1024x768 (XGA)     | 5         | 3.79%   |
| 3440x1440          | 4         | 3.03%   |
| 1920x1200 (WUXGA)  | 4         | 3.03%   |
| 1600x900 (HD+)     | 4         | 3.03%   |
| 1024x600           | 4         | 3.03%   |
| 1440x900 (WXGA+)   | 3         | 2.27%   |
| 2560x1080          | 2         | 1.52%   |
| 1360x768           | 2         | 1.52%   |
| 1280x768           | 2         | 1.52%   |
| 2880x1800          | 1         | 0.76%   |
| 2560x1700          | 1         | 0.76%   |
| 1280x960           | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 30        | 21.74%  |
| 14     | 13        | 9.42%   |
| 13     | 12        | 8.7%    |
| 17     | 11        | 7.97%   |
| 27     | 8         | 5.8%    |
| 23     | 7         | 5.07%   |
| 24     | 6         | 4.35%   |
| 20     | 5         | 3.62%   |
| 19     | 5         | 3.62%   |
| 11     | 5         | 3.62%   |
| 34     | 4         | 2.9%    |
| 21     | 4         | 2.9%    |
| 12     | 4         | 2.9%    |
| 10     | 4         | 2.9%    |
| 31     | 3         | 2.17%   |
| 22     | 3         | 2.17%   |
| 18     | 3         | 2.17%   |
| 40     | 2         | 1.45%   |
| 32     | 2         | 1.45%   |
| 72     | 1         | 0.72%   |
| 65     | 1         | 0.72%   |
| 60     | 1         | 0.72%   |
| 42     | 1         | 0.72%   |
| 29     | 1         | 0.72%   |
| 25     | 1         | 0.72%   |
| 16     | 1         | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 40.46%  |
| 501-600     | 19        | 14.5%   |
| 201-300     | 18        | 13.74%  |
| 401-500     | 15        | 11.45%  |
| 351-400     | 10        | 7.63%   |
| 701-800     | 5         | 3.82%   |
| 601-700     | 5         | 3.82%   |
| 801-900     | 2         | 1.53%   |
| 1001-1500   | 2         | 1.53%   |
| 1501-2000   | 1         | 0.76%   |
| 901-1000    | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 81        | 66.94%  |
| 16/10 | 22        | 18.18%  |
| 5/4   | 6         | 4.96%   |
| 4/3   | 5         | 4.13%   |
| 21/9  | 5         | 4.13%   |
| 6/5   | 1         | 0.83%   |
| 3/2   | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 21.97%  |
| 81-90          | 20        | 15.15%  |
| 201-250        | 15        | 11.36%  |
| 151-200        | 11        | 8.33%   |
| 301-350        | 9         | 6.82%   |
| 351-500        | 8         | 6.06%   |
| 71-80          | 6         | 4.55%   |
| 141-150        | 6         | 4.55%   |
| 51-60          | 5         | 3.79%   |
| 121-130        | 5         | 3.79%   |
| 41-50          | 4         | 3.03%   |
| More than 1000 | 3         | 2.27%   |
| 61-70          | 3         | 2.27%   |
| 501-1000       | 3         | 2.27%   |
| 251-300        | 2         | 1.52%   |
| 131-140        | 2         | 1.52%   |
| 111-120        | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 34.68%  |
| 101-120       | 35        | 28.23%  |
| 121-160       | 31        | 25%     |
| 1-50          | 8         | 6.45%   |
| 161-240       | 5         | 4.03%   |
| More than 240 | 2         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 65.87%  |
| 0     | 44        | 26.35%  |
| 2     | 11        | 6.59%   |
| 4     | 1         | 0.6%    |
| 3     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 83        | 34.02%  |
| Intel                           | 73        | 29.92%  |
| Qualcomm Atheros                | 24        | 9.84%   |
| Broadcom                        | 23        | 9.43%   |
| Xiaomi                          | 3         | 1.23%   |
| VIA Technologies                | 3         | 1.23%   |
| Marvell Technology Group        | 3         | 1.23%   |
| Broadcom Limited                | 3         | 1.23%   |
| TP-Link                         | 2         | 0.82%   |
| Qualcomm Atheros Communications | 2         | 0.82%   |
| Qualcomm                        | 2         | 0.82%   |
| Nvidia                          | 2         | 0.82%   |
| Microchip Technology            | 2         | 0.82%   |
| Mellanox Technologies           | 2         | 0.82%   |
| MediaTek                        | 2         | 0.82%   |
| LSI                             | 2         | 0.82%   |
| ASIX Electronics                | 2         | 0.82%   |
| T & A Mobile Phones             | 1         | 0.41%   |
| Sigma Designs                   | 1         | 0.41%   |
| Ralink Technology               | 1         | 0.41%   |
| NetGear                         | 1         | 0.41%   |
| Google                          | 1         | 0.41%   |
| Dresden Elektronik              | 1         | 0.41%   |
| DisplayLink                     | 1         | 0.41%   |
| D-Link System                   | 1         | 0.41%   |
| D-Link                          | 1         | 0.41%   |
| Belkin Components               | 1         | 0.41%   |
| AMD                             | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 17.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 3.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.99%   |
| Intel Ethernet Controller I225-V                                       | 5         | 1.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.33%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.33%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 1%      |
| Intel Wireless 7265                                                    | 3         | 1%      |
| Intel Wireless 3160                                                    | 3         | 1%      |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1%      |
| Intel I211 Gigabit Network Connection                                  | 3         | 1%      |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                        | 3         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.66%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.66%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 2         | 0.66%   |
| Intel Wireless 8260                                                    | 2         | 0.66%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 0.66%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.66%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 2         | 0.66%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.66%   |
| Intel Ethernet Connection (17) I219-LM                                 | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 42.34%  |
| Qualcomm Atheros                | 21        | 18.92%  |
| Broadcom                        | 16        | 14.41%  |
| Realtek Semiconductor           | 13        | 11.71%  |
| Broadcom Limited                | 3         | 2.7%    |
| TP-Link                         | 2         | 1.8%    |
| Qualcomm Atheros Communications | 2         | 1.8%    |
| MediaTek                        | 2         | 1.8%    |
| Ralink Technology               | 1         | 0.9%    |
| NetGear                         | 1         | 0.9%    |
| Marvell Technology Group        | 1         | 0.9%    |
| D-Link                          | 1         | 0.9%    |
| Belkin Components               | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 7.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 3.39%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 3.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.54%   |
| Intel Wireless 7265                                                                   | 3         | 2.54%   |
| Intel Wireless 3160                                                                   | 3         | 2.54%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 2.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 2.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 3         | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.69%   |
| Intel Wireless 8260                                                                   | 2         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 2         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 2         | 1.69%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 2         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 1.69%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 2         | 1.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1         | 0.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 1         | 0.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.85%   |
| Realtek RTL8187 Wireless Adapter                                                      | 1         | 0.85%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 76        | 47.5%   |
| Intel                    | 45        | 28.13%  |
| Broadcom                 | 12        | 7.5%    |
| Qualcomm Atheros         | 5         | 3.13%   |
| Xiaomi                   | 3         | 1.88%   |
| VIA Technologies         | 3         | 1.88%   |
| Qualcomm                 | 2         | 1.25%   |
| Nvidia                   | 2         | 1.25%   |
| Microchip Technology     | 2         | 1.25%   |
| Mellanox Technologies    | 2         | 1.25%   |
| Marvell Technology Group | 2         | 1.25%   |
| ASIX Electronics         | 2         | 1.25%   |
| T & A Mobile Phones      | 1         | 0.63%   |
| LSI                      | 1         | 0.63%   |
| DisplayLink              | 1         | 0.63%   |
| D-Link System            | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 30.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 6.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 3.47%   |
| Intel Ethernet Controller I225-V                                       | 5         | 2.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 2.31%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 2.31%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 1.73%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 1.73%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.73%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 1.73%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 1.16%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 2         | 1.16%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.16%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.16%   |
| Intel Ethernet Connection (17) I219-LM                                 | 2         | 1.16%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.16%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 2         | 1.16%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.58%   |
| T & A Mobile Phones TCL 20E                                            | 1         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.58%   |
| Qualcomm Redmi 9T                                                      | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.58%   |
| Qualcomm Android                                                       | 1         | 0.58%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.58%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.58%   |
| Mellanox MT28908 Family [ConnectX-6]                                   | 1         | 0.58%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1         | 0.58%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.58%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.58%   |
| LSI ET-131x PCI-E Ethernet Controller                                  | 1         | 0.58%   |
| Intel WiMAX Connection 2400m                                           | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 138       | 55.42%  |
| WiFi     | 101       | 40.56%  |
| Modem    | 8         | 3.21%   |
| Unknown  | 2         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 92        | 62.16%  |
| WiFi     | 56        | 37.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 82        | 50%     |
| 1     | 57        | 34.76%  |
| 0     | 15        | 9.15%   |
| 4     | 4         | 2.44%   |
| 3     | 4         | 2.44%   |
| 5     | 2         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 130       | 78.79%  |
| Yes  | 35        | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 39.02%  |
| Realtek Semiconductor           | 6         | 7.32%   |
| Apple                           | 6         | 7.32%   |
| Qualcomm Atheros Communications | 5         | 6.1%    |
| IMC Networks                    | 5         | 6.1%    |
| Cambridge Silicon Radio         | 5         | 6.1%    |
| Broadcom                        | 5         | 6.1%    |
| Lite-On Technology              | 3         | 3.66%   |
| Foxconn / Hon Hai               | 3         | 3.66%   |
| ASUSTek Computer                | 3         | 3.66%   |
| Toshiba                         | 1         | 1.22%   |
| MediaTek                        | 1         | 1.22%   |
| Marvell Semiconductor           | 1         | 1.22%   |
| Hewlett-Packard                 | 1         | 1.22%   |
| Edimax Technology               | 1         | 1.22%   |
| Dell                            | 1         | 1.22%   |
| Askey Computer                  | 1         | 1.22%   |
| Alps Electric                   | 1         | 1.22%   |
| Actions                         | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 14.46%  |
| Intel AX201 Bluetooth                               | 7         | 8.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 6.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 6.02%   |
| Realtek Bluetooth Radio                             | 4         | 4.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 3.61%   |
| Intel AX200 Bluetooth                               | 3         | 3.61%   |
| Apple Bluetooth Host Controller                     | 3         | 3.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.41%   |
| Intel Bluetooth Device                              | 2         | 2.41%   |
| IMC Networks Bluetooth Device                       | 2         | 2.41%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.41%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.41%   |
| Toshiba Bluetooth Device                            | 1         | 1.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.2%    |
| Realtek Bluetooth 5.3 Radio                         | 1         | 1.2%    |
| MediaTek Wireless_Device                            | 1         | 1.2%    |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.2%    |
| Intel AX210 Bluetooth                               | 1         | 1.2%    |
| IMC Networks Wireless_Device                        | 1         | 1.2%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.2%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.2%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.2%    |
| Edimax Bluetooth Adapter                            | 1         | 1.2%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.2%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.2%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.2%    |
| Broadcom BCM20702A0                                 | 1         | 1.2%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.2%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.2%    |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.2%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.2%    |
| ASUS BCM20702A0                                     | 1         | 1.2%    |
| Askey Bluetooth Device                              | 1         | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.2%    |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 111       | 64.91%  |
| AMD                                  | 30        | 17.54%  |
| Nvidia                               | 10        | 5.85%   |
| VIA Technologies                     | 3         | 1.75%   |
| C-Media Electronics                  | 3         | 1.75%   |
| Logitech                             | 2         | 1.17%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.58%   |
| Texas Instruments                    | 1         | 0.58%   |
| SteelSeries ApS                      | 1         | 0.58%   |
| Sennheiser Communications            | 1         | 0.58%   |
| RODE Microphones                     | 1         | 0.58%   |
| Realtek Semiconductor                | 1         | 0.58%   |
| Native Instruments                   | 1         | 0.58%   |
| Generalplus Technology               | 1         | 0.58%   |
| Focusrite-Novation                   | 1         | 0.58%   |
| Creative Labs                        | 1         | 0.58%   |
| Cirrus Logic                         | 1         | 0.58%   |
| Apple                                | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 3.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 3.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 3.15%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.15%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 2.25%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.35%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.35%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2         | 0.9%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.9%    |
| Intel DG2 Audio Controller                                                                        | 2         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.9%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 17.9%   |
| Unknown             | 27        | 16.67%  |
| SK hynix            | 24        | 14.81%  |
| Crucial             | 17        | 10.49%  |
| Micron Technology   | 15        | 9.26%   |
| Kingston            | 10        | 6.17%   |
| Elpida              | 10        | 6.17%   |
| Corsair             | 6         | 3.7%    |
| A-DATA Technology   | 4         | 2.47%   |
| Unknown (ABCD)      | 2         | 1.23%   |
| Nanya Technology    | 2         | 1.23%   |
| Unknown             | 2         | 1.23%   |
| Visipro             | 1         | 0.62%   |
| Transcend           | 1         | 0.62%   |
| Team                | 1         | 0.62%   |
| Smart Brazil        | 1         | 0.62%   |
| Ramaxel Technology  | 1         | 0.62%   |
| Qimonda             | 1         | 0.62%   |
| PNY                 | 1         | 0.62%   |
| Patriot             | 1         | 0.62%   |
| Novatech            | 1         | 0.62%   |
| Lexar               | 1         | 0.62%   |
| Hewlett-Packard     | 1         | 0.62%   |
| Gold Key            | 1         | 0.62%   |
| G.Skill             | 1         | 0.62%   |
| Cors                | 1         | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                                 | 3         | 1.61%   |
| Unknown RAM Module 1GB SODIMM DRAM                                  | 2         | 1.08%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 2         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.08%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 2         | 1.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.08%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.08%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s                 | 2         | 1.08%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s            | 2         | 1.08%   |
| Unknown                                                             | 2         | 1.08%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.54%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 0.54%   |
| Unknown RAM Module 512MB SODIMM DRAM                                | 1         | 0.54%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.54%   |
| Unknown RAM Module 512MB DIMM                                       | 1         | 0.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.54%   |
| Unknown RAM Module 4GB DIMM SDRAM                                   | 1         | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                 | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                       | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                            | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 1         | 0.54%   |
| Unknown RAM Module 256MB SODIMM DDR                                 | 1         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                         | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.54%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 128MB DIMM DRAM                                  | 1         | 0.54%   |
| Unknown RAM Module 128MB DIMM                                       | 1         | 0.54%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 1         | 0.54%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s                  | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 63        | 48.84%  |
| DDR4    | 33        | 25.58%  |
| SDRAM   | 8         | 6.2%    |
| LPDDR3  | 5         | 3.88%   |
| DDR2    | 5         | 3.88%   |
| LPDDR4  | 4         | 3.1%    |
| DDR     | 4         | 3.1%    |
| DRAM    | 3         | 2.33%   |
| DDR5    | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 55.04%  |
| DIMM         | 49        | 37.98%  |
| Row Of Chips | 7         | 5.43%   |
| Unknown      | 2         | 1.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 46        | 31.94%  |
| 4096  | 41        | 28.47%  |
| 2048  | 22        | 15.28%  |
| 1024  | 12        | 8.33%   |
| 16384 | 8         | 5.56%   |
| 512   | 6         | 4.17%   |
| 32768 | 5         | 3.47%   |
| 128   | 3         | 2.08%   |
| 256   | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 41        | 28.28%  |
| Unknown | 13        | 8.97%   |
| 2667    | 11        | 7.59%   |
| 2400    | 11        | 7.59%   |
| 1333    | 11        | 7.59%   |
| 3200    | 9         | 6.21%   |
| 1334    | 7         | 4.83%   |
| 2133    | 5         | 3.45%   |
| 3600    | 4         | 2.76%   |
| 1867    | 4         | 2.76%   |
| 667     | 4         | 2.76%   |
| 1067    | 3         | 2.07%   |
| 3800    | 2         | 1.38%   |
| 1866    | 2         | 1.38%   |
| 1066    | 2         | 1.38%   |
| 8400    | 1         | 0.69%   |
| 5808    | 1         | 0.69%   |
| 4800    | 1         | 0.69%   |
| 4267    | 1         | 0.69%   |
| 4199    | 1         | 0.69%   |
| 3666    | 1         | 0.69%   |
| 3266    | 1         | 0.69%   |
| 3066    | 1         | 0.69%   |
| 2200    | 1         | 0.69%   |
| 1800    | 1         | 0.69%   |
| 1400    | 1         | 0.69%   |
| 1331    | 1         | 0.69%   |
| 1200    | 1         | 0.69%   |
| 800     | 1         | 0.69%   |
| 533     | 1         | 0.69%   |
| 133     | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intermec Technologies | 1         | 33.33%  |
| Hewlett-Packard       | 1         | 33.33%  |
| Brother Industries    | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Intermec PC43t           | 1         | 25%     |
| HP LaserJet 1020         | 1         | 25%     |
| HP Deskjet 3050A         | 1         | 25%     |
| Brother HL-L2360D series | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 18.75%  |
| Realtek Semiconductor                  | 8         | 10%     |
| Microdia                               | 8         | 10%     |
| IMC Networks                           | 8         | 10%     |
| Bison Electronics                      | 7         | 8.75%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 6.25%   |
| Apple                                  | 5         | 6.25%   |
| Suyin                                  | 4         | 5%      |
| Quanta                                 | 3         | 3.75%   |
| Z-Star Microelectronics                | 2         | 2.5%    |
| Syntek                                 | 2         | 2.5%    |
| Sunplus Innovation Technology          | 2         | 2.5%    |
| Trust                                  | 1         | 1.25%   |
| Silicon Motion                         | 1         | 1.25%   |
| Samsung Electronics                    | 1         | 1.25%   |
| Ricoh                                  | 1         | 1.25%   |
| MacroSilicon                           | 1         | 1.25%   |
| Luxvisions Innotech Limited            | 1         | 1.25%   |
| Logitech                               | 1         | 1.25%   |
| Lite-On Technology                     | 1         | 1.25%   |
| Linux Foundation                       | 1         | 1.25%   |
| Lenovo                                 | 1         | 1.25%   |
| Alcor Micro                            | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 4.94%   |
| Microdia Integrated_Webcam_HD                       | 4         | 4.94%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.7%    |
| IMC Networks Integrated Camera                      | 3         | 3.7%    |
| Chicony HD Webcam                                   | 3         | 3.7%    |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.47%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 2.47%   |
| Chicony Integrated Camera                           | 2         | 2.47%   |
| Bison Lenovo EasyCamera                             | 2         | 2.47%   |
| Bison Integrated Camera                             | 2         | 2.47%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 2.47%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 1.23%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 1.23%   |
| Trust QHD Webcam                                    | 1         | 1.23%   |
| Syntek Integrated Camera                            | 1         | 1.23%   |
| Syntek EasyCamera                                   | 1         | 1.23%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.23%   |
| Suyin HP TrueVision HD                              | 1         | 1.23%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 1.23%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.23%   |
| Sunplus HP Universal Camera                         | 1         | 1.23%   |
| Sunplus HD WebCam                                   | 1         | 1.23%   |
| Silicon Motion NCM-G102                             | 1         | 1.23%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.23%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.23%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.23%   |
| Realtek USB Camera                                  | 1         | 1.23%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.23%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.23%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.23%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.23%   |
| Microdia Integrated Webcam                          | 1         | 1.23%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 1.23%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.23%   |
| Logitech Webcam C270                                | 1         | 1.23%   |
| Logitech Webcam C170                                | 1         | 1.23%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.23%   |
| Linux Foundation EEM Gadget                         | 1         | 1.23%   |
| Lenovo Integrated Webcam                            | 1         | 1.23%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| AuthenTec                  | 2         | 22.22%  |
| STMicroelectronics         | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                      | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 107       | 62.94%  |
| 1     | 36        | 21.18%  |
| 2     | 18        | 10.59%  |
| 4     | 4         | 2.35%   |
| 3     | 4         | 2.35%   |
| 7     | 1         | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 28        | 28.28%  |
| Communication controller | 14        | 14.14%  |
| Net/wireless             | 11        | 11.11%  |
| Fingerprint reader       | 8         | 8.08%   |
| Modem                    | 7         | 7.07%   |
| Camera                   | 5         | 5.05%   |
| Bluetooth                | 5         | 5.05%   |
| Multimedia controller    | 4         | 4.04%   |
| Network                  | 3         | 3.03%   |
| Unassigned class         | 2         | 2.02%   |
| Storage/ata              | 2         | 2.02%   |
| Sound                    | 2         | 2.02%   |
| Net/ethernet             | 2         | 2.02%   |
| Chipcard                 | 2         | 2.02%   |
| Unclassified device      | 1         | 1.01%   |
| Storage                  | 1         | 1.01%   |
| Flash memory             | 1         | 1.01%   |
| Card reader              | 1         | 1.01%   |

