Linux in Kazakhstan - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Kazakhstan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Kazakhstan/Desktop/README.md) and [notebooks](/Location/Kazakhstan/Notebook/README.md).

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

Total: 1412

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [4cc7d78ce4](https://linux-hardware.org/?probe=4cc7d78ce4) | Jan 01, 2026 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [55922f5d0a](https://linux-hardware.org/?probe=55922f5d0a) | Jan 01, 2026 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8bcab2bbeb](https://linux-hardware.org/?probe=8bcab2bbeb) | Dec 19, 2025 |
| Gigabyte      | H510M K V2                  | Desktop     | [4a0f5f2d4c](https://linux-hardware.org/?probe=4a0f5f2d4c) | Dec 15, 2025 |
| ASRock        | B650M Pro RS                | Desktop     | [748112bf2d](https://linux-hardware.org/?probe=748112bf2d) | Dec 15, 2025 |
| Acer          | Nitro AN515-42              | Notebook    | [ec345ff5c1](https://linux-hardware.org/?probe=ec345ff5c1) | Dec 14, 2025 |
| Acer          | Nitro AN515-42              | Notebook    | [203a29b93e](https://linux-hardware.org/?probe=203a29b93e) | Dec 14, 2025 |
| Packard Be... | DOT S                       | Notebook    | [75f2f1d8b0](https://linux-hardware.org/?probe=75f2f1d8b0) | Dec 06, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [644673ff57](https://linux-hardware.org/?probe=644673ff57) | Dec 04, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [8f7db6a1c9](https://linux-hardware.org/?probe=8f7db6a1c9) | Dec 04, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [26bbde99c1](https://linux-hardware.org/?probe=26bbde99c1) | Dec 04, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [97d5ed2502](https://linux-hardware.org/?probe=97d5ed2502) | Dec 04, 2025 |
| Samsung       | 305V4A/305V5A               | Notebook    | [35697a0961](https://linux-hardware.org/?probe=35697a0961) | Dec 03, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c8eaa0a5f9](https://linux-hardware.org/?probe=c8eaa0a5f9) | Dec 02, 2025 |
| Intel         | Unknown                     | Desktop     | [8a2554c6a8](https://linux-hardware.org/?probe=8a2554c6a8) | Nov 30, 2025 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [0c17ace05a](https://linux-hardware.org/?probe=0c17ace05a) | Nov 26, 2025 |
| Intel         | X99                         | Desktop     | [b522fd578e](https://linux-hardware.org/?probe=b522fd578e) | Nov 23, 2025 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [062310dfd7](https://linux-hardware.org/?probe=062310dfd7) | Nov 20, 2025 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [7d18c77c61](https://linux-hardware.org/?probe=7d18c77c61) | Nov 20, 2025 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [dbd8a3cb13](https://linux-hardware.org/?probe=dbd8a3cb13) | Nov 12, 2025 |
| ASUSTek       | Z170-PREMIUM                | Desktop     | [c51602b8ba](https://linux-hardware.org/?probe=c51602b8ba) | Nov 12, 2025 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [a723a6a441](https://linux-hardware.org/?probe=a723a6a441) | Nov 11, 2025 |
| Dell          | XPS 15 9570                 | Notebook    | [f3f37c714d](https://linux-hardware.org/?probe=f3f37c714d) | Nov 03, 2025 |
| Gigabyte      | H610M K DDR4                | Desktop     | [3a07930e1c](https://linux-hardware.org/?probe=3a07930e1c) | Oct 27, 2025 |
| Gigabyte      | H610M K DDR4                | Desktop     | [488892fdc9](https://linux-hardware.org/?probe=488892fdc9) | Oct 27, 2025 |
| Shenzhen W... | Alder Lake N                | Notebook    | [3ffccd0702](https://linux-hardware.org/?probe=3ffccd0702) | Oct 14, 2025 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5b438ce21d](https://linux-hardware.org/?probe=5b438ce21d) | Oct 12, 2025 |
| Gigabyte      | B75M-D3V                    | Desktop     | [9ea60e62a7](https://linux-hardware.org/?probe=9ea60e62a7) | Oct 11, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1d420161b2](https://linux-hardware.org/?probe=1d420161b2) | Oct 10, 2025 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [f8b2e506f0](https://linux-hardware.org/?probe=f8b2e506f0) | Oct 05, 2025 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [11a3d5ae03](https://linux-hardware.org/?probe=11a3d5ae03) | Oct 05, 2025 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [784c30462f](https://linux-hardware.org/?probe=784c30462f) | Oct 04, 2025 |
| Acer          | Nitro ANV15-51              | Notebook    | [e656b438aa](https://linux-hardware.org/?probe=e656b438aa) | Oct 03, 2025 |
| Dell          | Inspiron 15 5510            | Notebook    | [ceb8b97cfc](https://linux-hardware.org/?probe=ceb8b97cfc) | Sep 29, 2025 |
| Unknown       | Unknown                     | Notebook    | [32d14b0a12](https://linux-hardware.org/?probe=32d14b0a12) | Sep 25, 2025 |
| ECS           | G31T-M7                     | Desktop     | [4b186b19c9](https://linux-hardware.org/?probe=4b186b19c9) | Sep 20, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [700f7de82e](https://linux-hardware.org/?probe=700f7de82e) | Sep 18, 2025 |
| HP            | ZBook Ultra G1a 14 inch ... | Notebook    | [a8a620fd6d](https://linux-hardware.org/?probe=a8a620fd6d) | Sep 15, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [158c872faa](https://linux-hardware.org/?probe=158c872faa) | Sep 15, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [6a280e61fc](https://linux-hardware.org/?probe=6a280e61fc) | Sep 15, 2025 |
| HP            | ENVY 15                     | Notebook    | [e3242f675e](https://linux-hardware.org/?probe=e3242f675e) | Sep 14, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [aca31ce319](https://linux-hardware.org/?probe=aca31ce319) | Sep 11, 2025 |
| Lenovo        | ThinkPad T420 4238W1M       | Notebook    | [09ffce0af0](https://linux-hardware.org/?probe=09ffce0af0) | Sep 04, 2025 |
| Acer          | Aspire A514-52K             | Notebook    | [d3d1557bb8](https://linux-hardware.org/?probe=d3d1557bb8) | Sep 02, 2025 |
| Acer          | Swift SF314-512             | Notebook    | [d0afac7205](https://linux-hardware.org/?probe=d0afac7205) | Aug 24, 2025 |
| Maibenben     | MaiBook X series            | Notebook    | [d7a79c442c](https://linux-hardware.org/?probe=d7a79c442c) | Aug 22, 2025 |
| ASUSTek       | H110M-R                     | Desktop     | [52767b2382](https://linux-hardware.org/?probe=52767b2382) | Aug 18, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [eb05ab55e4](https://linux-hardware.org/?probe=eb05ab55e4) | Aug 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [ecb9005c78](https://linux-hardware.org/?probe=ecb9005c78) | Aug 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [7f17d301e0](https://linux-hardware.org/?probe=7f17d301e0) | Aug 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [c7d8604448](https://linux-hardware.org/?probe=c7d8604448) | Aug 14, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [546a780f38](https://linux-hardware.org/?probe=546a780f38) | Aug 13, 2025 |
| Acer          | Aspire 5750G                | Notebook    | [46e2be3146](https://linux-hardware.org/?probe=46e2be3146) | Aug 13, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [d475de16a2](https://linux-hardware.org/?probe=d475de16a2) | Aug 11, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [138292c04a](https://linux-hardware.org/?probe=138292c04a) | Aug 05, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [3da4f09a29](https://linux-hardware.org/?probe=3da4f09a29) | Aug 05, 2025 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [03f5915467](https://linux-hardware.org/?probe=03f5915467) | Jul 28, 2025 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [4da4e999d0](https://linux-hardware.org/?probe=4da4e999d0) | Jul 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [a585d93f1a](https://linux-hardware.org/?probe=a585d93f1a) | Jul 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [b010a0dc76](https://linux-hardware.org/?probe=b010a0dc76) | Jul 17, 2025 |
| Timi          | TM1612                      | Notebook    | [f1b101cdbe](https://linux-hardware.org/?probe=f1b101cdbe) | Jul 12, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [ddc60aab80](https://linux-hardware.org/?probe=ddc60aab80) | Jul 12, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [4f591cd069](https://linux-hardware.org/?probe=4f591cd069) | Jul 09, 2025 |
| Foxconn       | 2ABF                        | Desktop     | [7c5954eb36](https://linux-hardware.org/?probe=7c5954eb36) | Jul 08, 2025 |
| Foxconn       | 2ABF                        | Desktop     | [36011c5e8a](https://linux-hardware.org/?probe=36011c5e8a) | Jul 08, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [6eb08ae357](https://linux-hardware.org/?probe=6eb08ae357) | Jul 07, 2025 |
| Lenovo        | G500 20236                  | Notebook    | [f5bfc0f410](https://linux-hardware.org/?probe=f5bfc0f410) | Jul 05, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [0803c65b36](https://linux-hardware.org/?probe=0803c65b36) | Jul 05, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [bac8e3bc70](https://linux-hardware.org/?probe=bac8e3bc70) | Jul 04, 2025 |
| ASRock        | Z790 Riptide WiFi           | Desktop     | [190fd8168c](https://linux-hardware.org/?probe=190fd8168c) | Jul 03, 2025 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [3a46647c62](https://linux-hardware.org/?probe=3a46647c62) | Jun 11, 2025 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [206f011826](https://linux-hardware.org/?probe=206f011826) | Jun 10, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [9a32ea36d2](https://linux-hardware.org/?probe=9a32ea36d2) | Jun 10, 2025 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6c12526bcf](https://linux-hardware.org/?probe=6c12526bcf) | Jun 02, 2025 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [fdba22c2de](https://linux-hardware.org/?probe=fdba22c2de) | Jun 02, 2025 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [1a90a9aa05](https://linux-hardware.org/?probe=1a90a9aa05) | May 20, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [985ea3bdcc](https://linux-hardware.org/?probe=985ea3bdcc) | May 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [158ec29c90](https://linux-hardware.org/?probe=158ec29c90) | May 17, 2025 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [e3460e0424](https://linux-hardware.org/?probe=e3460e0424) | May 16, 2025 |
| ASUSTek       | M2N-E                       | Desktop     | [fcc750192e](https://linux-hardware.org/?probe=fcc750192e) | May 15, 2025 |
| ASUSTek       | ROG Strix G834JY_G834JY     | Notebook    | [a7aa29b134](https://linux-hardware.org/?probe=a7aa29b134) | May 07, 2025 |
| XIAOMI        | REDMI Book Pro 16 2025      | Notebook    | [27d2b066b6](https://linux-hardware.org/?probe=27d2b066b6) | May 05, 2025 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [55fde62cf4](https://linux-hardware.org/?probe=55fde62cf4) | May 05, 2025 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [e620cb1623](https://linux-hardware.org/?probe=e620cb1623) | May 05, 2025 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [6f041a53f2](https://linux-hardware.org/?probe=6f041a53f2) | May 03, 2025 |
| ASUSTek       | H110M-C                     | Desktop     | [b435b870b5](https://linux-hardware.org/?probe=b435b870b5) | May 02, 2025 |
| HP            | EliteBook 820 G1            | Notebook    | [0f6df0b1db](https://linux-hardware.org/?probe=0f6df0b1db) | Apr 30, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [7d6dea7f57](https://linux-hardware.org/?probe=7d6dea7f57) | Apr 30, 2025 |
| ASUSTek       | Z790 GAMING WIFI7           | Desktop     | [f23f89d1b9](https://linux-hardware.org/?probe=f23f89d1b9) | Apr 27, 2025 |
| Chuwi         | HeroBox                     | Mini pc     | [510620d502](https://linux-hardware.org/?probe=510620d502) | Apr 24, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [c6cf7f16ba](https://linux-hardware.org/?probe=c6cf7f16ba) | Apr 24, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [238b0c801a](https://linux-hardware.org/?probe=238b0c801a) | Apr 23, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [480ab4d59b](https://linux-hardware.org/?probe=480ab4d59b) | Apr 23, 2025 |
| ASUSTek       | A6R                         | Notebook    | [e166025059](https://linux-hardware.org/?probe=e166025059) | Apr 17, 2025 |
| ASUSTek       | A6R                         | Notebook    | [9f28563322](https://linux-hardware.org/?probe=9f28563322) | Apr 17, 2025 |
| DERE          | X16                         | Notebook    | [07082d3edf](https://linux-hardware.org/?probe=07082d3edf) | Apr 15, 2025 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b4885a41f8](https://linux-hardware.org/?probe=b4885a41f8) | Apr 14, 2025 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [608d37fe3e](https://linux-hardware.org/?probe=608d37fe3e) | Apr 14, 2025 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2235bb0292](https://linux-hardware.org/?probe=2235bb0292) | Apr 12, 2025 |
| ASUSTek       | X540SAA                     | Notebook    | [5125876563](https://linux-hardware.org/?probe=5125876563) | Apr 06, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [79408cf3e7](https://linux-hardware.org/?probe=79408cf3e7) | Apr 05, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [803494a075](https://linux-hardware.org/?probe=803494a075) | Apr 04, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [d4d2a6fada](https://linux-hardware.org/?probe=d4d2a6fada) | Mar 30, 2025 |
| ASRock        | H61M-VG3                    | Desktop     | [decd6538d8](https://linux-hardware.org/?probe=decd6538d8) | Mar 29, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [d9b96829de](https://linux-hardware.org/?probe=d9b96829de) | Mar 29, 2025 |
| ASUSTek       | Zenbook UX3404VA_Q410VA     | Notebook    | [2fe1448eb1](https://linux-hardware.org/?probe=2fe1448eb1) | Mar 26, 2025 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | Notebook    | [38f27960d2](https://linux-hardware.org/?probe=38f27960d2) | Mar 26, 2025 |
| Acer          | Nitro AN515-56              | Notebook    | [d4a629a06d](https://linux-hardware.org/?probe=d4a629a06d) | Mar 26, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [e3a729ecc7](https://linux-hardware.org/?probe=e3a729ecc7) | Mar 25, 2025 |
| ASRock        | B460M Steel Legend          | Desktop     | [3d63781650](https://linux-hardware.org/?probe=3d63781650) | Mar 25, 2025 |
| ASRock        | B460M Steel Legend          | Desktop     | [c78ffc6dd0](https://linux-hardware.org/?probe=c78ffc6dd0) | Mar 25, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [e85e0784ef](https://linux-hardware.org/?probe=e85e0784ef) | Mar 24, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [7adf256258](https://linux-hardware.org/?probe=7adf256258) | Mar 24, 2025 |
| Google        | Vilboz                      | Notebook    | [53698e33be](https://linux-hardware.org/?probe=53698e33be) | Mar 22, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [d4c19069fa](https://linux-hardware.org/?probe=d4c19069fa) | Mar 22, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [bb383e0615](https://linux-hardware.org/?probe=bb383e0615) | Mar 21, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [79376664ec](https://linux-hardware.org/?probe=79376664ec) | Mar 20, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [b063ef3d1a](https://linux-hardware.org/?probe=b063ef3d1a) | Mar 20, 2025 |
| Lenovo        | 3733                        | Desktop     | [7355fd34e3](https://linux-hardware.org/?probe=7355fd34e3) | Mar 17, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [8b4d27b6b5](https://linux-hardware.org/?probe=8b4d27b6b5) | Mar 16, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [bf8af01c25](https://linux-hardware.org/?probe=bf8af01c25) | Mar 16, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [9ce8eaf9f4](https://linux-hardware.org/?probe=9ce8eaf9f4) | Mar 15, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [eae172b17b](https://linux-hardware.org/?probe=eae172b17b) | Mar 14, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | Desktop     | [16d37950cb](https://linux-hardware.org/?probe=16d37950cb) | Mar 13, 2025 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [2bcd1318d8](https://linux-hardware.org/?probe=2bcd1318d8) | Mar 09, 2025 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [2f824f91b7](https://linux-hardware.org/?probe=2f824f91b7) | Mar 09, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [4ef7c07d8a](https://linux-hardware.org/?probe=4ef7c07d8a) | Mar 06, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [e40bd608d7](https://linux-hardware.org/?probe=e40bd608d7) | Mar 05, 2025 |
| Acer          | Swift SFE16-44              | Notebook    | [50efb97558](https://linux-hardware.org/?probe=50efb97558) | Mar 03, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [0ad3b76eb3](https://linux-hardware.org/?probe=0ad3b76eb3) | Mar 03, 2025 |
| Acer          | Aspire E5-575G              | Notebook    | [94661721d1](https://linux-hardware.org/?probe=94661721d1) | Mar 01, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [6181a01bc6](https://linux-hardware.org/?probe=6181a01bc6) | Mar 01, 2025 |
| Acer          | Aspire V3-771               | Notebook    | [e360a517f2](https://linux-hardware.org/?probe=e360a517f2) | Feb 27, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [90231c569d](https://linux-hardware.org/?probe=90231c569d) | Feb 27, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [e2dc70785e](https://linux-hardware.org/?probe=e2dc70785e) | Feb 26, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [3a3a0c5aec](https://linux-hardware.org/?probe=3a3a0c5aec) | Feb 22, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [c1e03bddc9](https://linux-hardware.org/?probe=c1e03bddc9) | Feb 22, 2025 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [4e3e0d6cdd](https://linux-hardware.org/?probe=4e3e0d6cdd) | Feb 17, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [9aa4684000](https://linux-hardware.org/?probe=9aa4684000) | Feb 13, 2025 |
| Acer          | Aspire 5755G                | Notebook    | [645868042d](https://linux-hardware.org/?probe=645868042d) | Feb 12, 2025 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [b15e4a5767](https://linux-hardware.org/?probe=b15e4a5767) | Feb 11, 2025 |
| Acer          | Aspire 5755G                | Notebook    | [c6a9173823](https://linux-hardware.org/?probe=c6a9173823) | Feb 11, 2025 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [fd1376a6bc](https://linux-hardware.org/?probe=fd1376a6bc) | Feb 11, 2025 |
| Intel         | X99-P3 V5.21                | Desktop     | [4357eac9e9](https://linux-hardware.org/?probe=4357eac9e9) | Feb 10, 2025 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [eec47c4bc4](https://linux-hardware.org/?probe=eec47c4bc4) | Feb 10, 2025 |
| Intel         | Unknown                     | Desktop     | [34626d158d](https://linux-hardware.org/?probe=34626d158d) | Feb 08, 2025 |
| MSI           | P45-C51                     | Desktop     | [383fa2fef0](https://linux-hardware.org/?probe=383fa2fef0) | Feb 08, 2025 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [33e418c2a2](https://linux-hardware.org/?probe=33e418c2a2) | Feb 07, 2025 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [dcbf4dc05d](https://linux-hardware.org/?probe=dcbf4dc05d) | Feb 06, 2025 |
| Lenovo        | G505s 20255                 | Notebook    | [4f5cf1beb3](https://linux-hardware.org/?probe=4f5cf1beb3) | Feb 05, 2025 |
| Intel         | JSL MRD                     | Desktop     | [a35073ddc3](https://linux-hardware.org/?probe=a35073ddc3) | Jan 31, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [a1810f0ad6](https://linux-hardware.org/?probe=a1810f0ad6) | Jan 26, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [4ef455f6d0](https://linux-hardware.org/?probe=4ef455f6d0) | Jan 25, 2025 |
| HONOR         | DRA-XX                      | Notebook    | [a3e7d421d4](https://linux-hardware.org/?probe=a3e7d421d4) | Jan 24, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [9b4ef79837](https://linux-hardware.org/?probe=9b4ef79837) | Jan 24, 2025 |
| Acer          | Nitro AN515-54              | Notebook    | [47b66de1a2](https://linux-hardware.org/?probe=47b66de1a2) | Jan 23, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [790b2fbefb](https://linux-hardware.org/?probe=790b2fbefb) | Jan 23, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [ce14f86407](https://linux-hardware.org/?probe=ce14f86407) | Jan 22, 2025 |
| Lenovo        | G505s 20255                 | Notebook    | [d9bacf1c6e](https://linux-hardware.org/?probe=d9bacf1c6e) | Jan 22, 2025 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [7ebf225c2c](https://linux-hardware.org/?probe=7ebf225c2c) | Jan 21, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [16826dec7f](https://linux-hardware.org/?probe=16826dec7f) | Jan 21, 2025 |
| ASRock        | H61M-VG3                    | Desktop     | [9570ee0113](https://linux-hardware.org/?probe=9570ee0113) | Jan 20, 2025 |
| PIPO          | X9S                         | Notebook    | [fd01051c66](https://linux-hardware.org/?probe=fd01051c66) | Jan 20, 2025 |
| HUAWEI        | MDF-XX                      | Notebook    | [0c473f7dbb](https://linux-hardware.org/?probe=0c473f7dbb) | Jan 19, 2025 |
| ASUSTek       | ROG Strix G531GV_G531GV     | Notebook    | [b4588d047f](https://linux-hardware.org/?probe=b4588d047f) | Jan 18, 2025 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [29934f1cac](https://linux-hardware.org/?probe=29934f1cac) | Jan 15, 2025 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [62880b514e](https://linux-hardware.org/?probe=62880b514e) | Jan 15, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [efcd0d08e4](https://linux-hardware.org/?probe=efcd0d08e4) | Jan 14, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [3696cb17ce](https://linux-hardware.org/?probe=3696cb17ce) | Jan 13, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [67f531f84f](https://linux-hardware.org/?probe=67f531f84f) | Jan 13, 2025 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [320b8058a0](https://linux-hardware.org/?probe=320b8058a0) | Jan 13, 2025 |
| ASRock        | H61M-VG3                    | Desktop     | [494ede44c3](https://linux-hardware.org/?probe=494ede44c3) | Jan 13, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [294f1f750a](https://linux-hardware.org/?probe=294f1f750a) | Jan 12, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [6d90a41cfe](https://linux-hardware.org/?probe=6d90a41cfe) | Jan 12, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [4f81a72da4](https://linux-hardware.org/?probe=4f81a72da4) | Jan 12, 2025 |
| ASUSTek       | N751JK                      | Notebook    | [2da19c5b19](https://linux-hardware.org/?probe=2da19c5b19) | Jan 11, 2025 |
| ASUSTek       | N56VB                       | Notebook    | [e914a2ec7c](https://linux-hardware.org/?probe=e914a2ec7c) | Jan 11, 2025 |
| Acer          | Nitro ANV15-41              | Notebook    | [c00697f8ba](https://linux-hardware.org/?probe=c00697f8ba) | Jan 11, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [e692a8c012](https://linux-hardware.org/?probe=e692a8c012) | Jan 10, 2025 |
| ASRock        | H61M-VG3                    | Desktop     | [aa08664c78](https://linux-hardware.org/?probe=aa08664c78) | Jan 08, 2025 |
| ASRock        | 990FX Extreme4              | Desktop     | [4b37ae65f2](https://linux-hardware.org/?probe=4b37ae65f2) | Dec 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [ae4ac86e01](https://linux-hardware.org/?probe=ae4ac86e01) | Dec 27, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [10501c1c92](https://linux-hardware.org/?probe=10501c1c92) | Dec 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [51e8b5da5d](https://linux-hardware.org/?probe=51e8b5da5d) | Dec 23, 2024 |
| Rockchip      | RK3318 BOX                  | Soc         | [41d68fa34c](https://linux-hardware.org/?probe=41d68fa34c) | Dec 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4e38ddc9dc](https://linux-hardware.org/?probe=4e38ddc9dc) | Dec 18, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [95613c7635](https://linux-hardware.org/?probe=95613c7635) | Dec 18, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [c09f54f867](https://linux-hardware.org/?probe=c09f54f867) | Dec 17, 2024 |
| Intel         | Unknown                     | Desktop     | [fcbbdc5c06](https://linux-hardware.org/?probe=fcbbdc5c06) | Dec 16, 2024 |
| Foxconn       | H55MXV Series               | Desktop     | [cf67e7336a](https://linux-hardware.org/?probe=cf67e7336a) | Dec 14, 2024 |
| Foxconn       | H55MXV Series               | Desktop     | [6a647c4d4e](https://linux-hardware.org/?probe=6a647c4d4e) | Dec 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7831fe39d7](https://linux-hardware.org/?probe=7831fe39d7) | Dec 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [f5a32c5d75](https://linux-hardware.org/?probe=f5a32c5d75) | Dec 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8b5cf16f3c](https://linux-hardware.org/?probe=8b5cf16f3c) | Dec 13, 2024 |
| Gigabyte      | H410M H V2                  | Desktop     | [29d08f5d9c](https://linux-hardware.org/?probe=29d08f5d9c) | Dec 11, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [5da4d46242](https://linux-hardware.org/?probe=5da4d46242) | Dec 10, 2024 |
| MSI           | H81M-P33                    | Desktop     | [cac8c0b952](https://linux-hardware.org/?probe=cac8c0b952) | Dec 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [37cd91857a](https://linux-hardware.org/?probe=37cd91857a) | Dec 03, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [28717d8de7](https://linux-hardware.org/?probe=28717d8de7) | Dec 02, 2024 |
| Acer          | FI946GZG                    | Desktop     | [cd23a4d442](https://linux-hardware.org/?probe=cd23a4d442) | Nov 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [721db2016b](https://linux-hardware.org/?probe=721db2016b) | Nov 30, 2024 |
| Intel         | H61M-DS2                    | Desktop     | [dd01835023](https://linux-hardware.org/?probe=dd01835023) | Nov 30, 2024 |
| Acer          | FI946GZG                    | Desktop     | [51525dcf0b](https://linux-hardware.org/?probe=51525dcf0b) | Nov 30, 2024 |
| Acer          | FI946GZG                    | Desktop     | [7ca93acd40](https://linux-hardware.org/?probe=7ca93acd40) | Nov 30, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ee4dd3336d](https://linux-hardware.org/?probe=ee4dd3336d) | Nov 29, 2024 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [d31490c125](https://linux-hardware.org/?probe=d31490c125) | Nov 28, 2024 |
| Acer          | FI946GZG                    | Desktop     | [816946793f](https://linux-hardware.org/?probe=816946793f) | Nov 27, 2024 |
| Acer          | FI946GZG                    | Desktop     | [97bb957570](https://linux-hardware.org/?probe=97bb957570) | Nov 27, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [f82e692b05](https://linux-hardware.org/?probe=f82e692b05) | Nov 27, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c1421ece6a](https://linux-hardware.org/?probe=c1421ece6a) | Nov 27, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b30fc2534e](https://linux-hardware.org/?probe=b30fc2534e) | Nov 24, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [0677efd3fd](https://linux-hardware.org/?probe=0677efd3fd) | Nov 23, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [5c29a83065](https://linux-hardware.org/?probe=5c29a83065) | Nov 23, 2024 |
| Acer          | FI946GZG                    | Desktop     | [5dec70689d](https://linux-hardware.org/?probe=5dec70689d) | Nov 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a92920e53b](https://linux-hardware.org/?probe=a92920e53b) | Nov 21, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [410a568ba4](https://linux-hardware.org/?probe=410a568ba4) | Nov 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [62ca0ea99f](https://linux-hardware.org/?probe=62ca0ea99f) | Nov 19, 2024 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [1860ba92b8](https://linux-hardware.org/?probe=1860ba92b8) | Nov 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9533b58887](https://linux-hardware.org/?probe=9533b58887) | Nov 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4fdb624e0d](https://linux-hardware.org/?probe=4fdb624e0d) | Nov 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e8e51e4661](https://linux-hardware.org/?probe=e8e51e4661) | Nov 17, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c75747aebf](https://linux-hardware.org/?probe=c75747aebf) | Nov 16, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [b8fcc9f859](https://linux-hardware.org/?probe=b8fcc9f859) | Nov 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [a7f49035aa](https://linux-hardware.org/?probe=a7f49035aa) | Nov 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [9d9080e57a](https://linux-hardware.org/?probe=9d9080e57a) | Nov 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [0a4922fa4a](https://linux-hardware.org/?probe=0a4922fa4a) | Nov 16, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [561df0051a](https://linux-hardware.org/?probe=561df0051a) | Nov 15, 2024 |
| Acer          | Nitro ANV15-41              | Notebook    | [41a8d79a11](https://linux-hardware.org/?probe=41a8d79a11) | Nov 14, 2024 |
| Gigabyte      | GA-MA78GM-DS2H              | Desktop     | [5b63d6de06](https://linux-hardware.org/?probe=5b63d6de06) | Nov 12, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [2aeff0c8d3](https://linux-hardware.org/?probe=2aeff0c8d3) | Nov 12, 2024 |
| Acer          | FI946GZG                    | Desktop     | [839c93438e](https://linux-hardware.org/?probe=839c93438e) | Nov 11, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [249dbb7fd0](https://linux-hardware.org/?probe=249dbb7fd0) | Nov 11, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [bbee92fd3f](https://linux-hardware.org/?probe=bbee92fd3f) | Nov 10, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [bda8633651](https://linux-hardware.org/?probe=bda8633651) | Oct 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [938c450b38](https://linux-hardware.org/?probe=938c450b38) | Oct 30, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [ef0b873549](https://linux-hardware.org/?probe=ef0b873549) | Oct 29, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [ea7d1235b1](https://linux-hardware.org/?probe=ea7d1235b1) | Oct 28, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [e2d1e7a362](https://linux-hardware.org/?probe=e2d1e7a362) | Oct 27, 2024 |
| Acer          | FI946GZG                    | Desktop     | [02965ac18a](https://linux-hardware.org/?probe=02965ac18a) | Oct 26, 2024 |
| Acer          | FI946GZG                    | Desktop     | [aa985cb91e](https://linux-hardware.org/?probe=aa985cb91e) | Oct 26, 2024 |
| Acer          | FI946GZG                    | Desktop     | [2d4aa17377](https://linux-hardware.org/?probe=2d4aa17377) | Oct 26, 2024 |
| Acer          | FI946GZG                    | Desktop     | [5938a70edc](https://linux-hardware.org/?probe=5938a70edc) | Oct 26, 2024 |
| Acer          | FI946GZG                    | Desktop     | [57835df373](https://linux-hardware.org/?probe=57835df373) | Oct 26, 2024 |
| Gigabyte      | H510M H                     | Desktop     | [f9526923ef](https://linux-hardware.org/?probe=f9526923ef) | Oct 24, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3ee9dc7745](https://linux-hardware.org/?probe=3ee9dc7745) | Oct 22, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4d658d4db3](https://linux-hardware.org/?probe=4d658d4db3) | Oct 21, 2024 |
| Intel         | JSL MRD                     | Desktop     | [3e4834107b](https://linux-hardware.org/?probe=3e4834107b) | Oct 17, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e022107a17](https://linux-hardware.org/?probe=e022107a17) | Oct 14, 2024 |
| Supermicro    | X12DDW-A6                   | Server      | [e62d713f58](https://linux-hardware.org/?probe=e62d713f58) | Oct 14, 2024 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | Notebook    | [caabd0867c](https://linux-hardware.org/?probe=caabd0867c) | Oct 11, 2024 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [774e032ab6](https://linux-hardware.org/?probe=774e032ab6) | Oct 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [a0a836220b](https://linux-hardware.org/?probe=a0a836220b) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [63eb77aafd](https://linux-hardware.org/?probe=63eb77aafd) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [a2cff54f7a](https://linux-hardware.org/?probe=a2cff54f7a) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [28fcc08ddb](https://linux-hardware.org/?probe=28fcc08ddb) | Oct 09, 2024 |
| Acer          | FI946GZG                    | Desktop     | [dcb630a44e](https://linux-hardware.org/?probe=dcb630a44e) | Oct 09, 2024 |
| Acer          | FI946GZG                    | Desktop     | [92bd6f1fc1](https://linux-hardware.org/?probe=92bd6f1fc1) | Oct 09, 2024 |
| Acer          | FI946GZG                    | Desktop     | [535a355530](https://linux-hardware.org/?probe=535a355530) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0b15120456](https://linux-hardware.org/?probe=0b15120456) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [d0eaae2f60](https://linux-hardware.org/?probe=d0eaae2f60) | Oct 09, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [d7b987d600](https://linux-hardware.org/?probe=d7b987d600) | Oct 06, 2024 |
| MSI           | H81M-P33                    | Desktop     | [6c881211b4](https://linux-hardware.org/?probe=6c881211b4) | Oct 04, 2024 |
| Acer          | Predator PH317-56           | Notebook    | [96bdb2ab93](https://linux-hardware.org/?probe=96bdb2ab93) | Sep 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7a8f5aa1d9](https://linux-hardware.org/?probe=7a8f5aa1d9) | Sep 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [86c0fb1040](https://linux-hardware.org/?probe=86c0fb1040) | Sep 29, 2024 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [6490abb8dc](https://linux-hardware.org/?probe=6490abb8dc) | Sep 27, 2024 |
| Gigabyte      | P35-DS3L                    | Desktop     | [f514b39998](https://linux-hardware.org/?probe=f514b39998) | Sep 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d4b92bf589](https://linux-hardware.org/?probe=d4b92bf589) | Sep 21, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [8e686cf909](https://linux-hardware.org/?probe=8e686cf909) | Sep 21, 2024 |
| Acer          | FI946GZG                    | Desktop     | [5d3261cef9](https://linux-hardware.org/?probe=5d3261cef9) | Sep 20, 2024 |
| Acer          | FI946GZG                    | Desktop     | [38457fe3eb](https://linux-hardware.org/?probe=38457fe3eb) | Sep 20, 2024 |
| Acer          | FI946GZG                    | Desktop     | [6d2cb2830e](https://linux-hardware.org/?probe=6d2cb2830e) | Sep 20, 2024 |
| Acer          | FI946GZG                    | Desktop     | [7f888553ed](https://linux-hardware.org/?probe=7f888553ed) | Sep 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [43f6819239](https://linux-hardware.org/?probe=43f6819239) | Sep 19, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [4cec70b2ed](https://linux-hardware.org/?probe=4cec70b2ed) | Sep 16, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [72effb4ee2](https://linux-hardware.org/?probe=72effb4ee2) | Sep 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [09b425a119](https://linux-hardware.org/?probe=09b425a119) | Sep 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [99d35d63c7](https://linux-hardware.org/?probe=99d35d63c7) | Sep 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [f1be3f6c90](https://linux-hardware.org/?probe=f1be3f6c90) | Sep 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [6e8771695d](https://linux-hardware.org/?probe=6e8771695d) | Sep 07, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [dd3e8c49a7](https://linux-hardware.org/?probe=dd3e8c49a7) | Sep 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [ccf3202ad6](https://linux-hardware.org/?probe=ccf3202ad6) | Sep 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7a99ae7e13](https://linux-hardware.org/?probe=7a99ae7e13) | Sep 01, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7fb7f32904](https://linux-hardware.org/?probe=7fb7f32904) | Sep 01, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | Notebook    | [088c823b60](https://linux-hardware.org/?probe=088c823b60) | Aug 31, 2024 |
| Unknown       | YV16                        | Desktop     | [4a2a6e7bb9](https://linux-hardware.org/?probe=4a2a6e7bb9) | Aug 24, 2024 |
| TI            | AM335x BeagleBone Black     | Soc         | [28a2645f4c](https://linux-hardware.org/?probe=28a2645f4c) | Aug 22, 2024 |
| HUAWEI        | MCLF-XX                     | Notebook    | [8380049b51](https://linux-hardware.org/?probe=8380049b51) | Aug 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | Notebook    | [42e09214a4](https://linux-hardware.org/?probe=42e09214a4) | Aug 18, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9d1f60f81a](https://linux-hardware.org/?probe=9d1f60f81a) | Aug 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9a0fb7bb34](https://linux-hardware.org/?probe=9a0fb7bb34) | Aug 10, 2024 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [8f0cd17c6a](https://linux-hardware.org/?probe=8f0cd17c6a) | Aug 09, 2024 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [8ccc09e1a3](https://linux-hardware.org/?probe=8ccc09e1a3) | Aug 04, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | Notebook    | [e8511ac05e](https://linux-hardware.org/?probe=e8511ac05e) | Aug 02, 2024 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [babb217959](https://linux-hardware.org/?probe=babb217959) | Aug 01, 2024 |
| ASRock        | AB350M Pro4                 | Desktop     | [f587d9d0c8](https://linux-hardware.org/?probe=f587d9d0c8) | Jul 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1af01aa6b](https://linux-hardware.org/?probe=e1af01aa6b) | Jul 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d60f72815e](https://linux-hardware.org/?probe=d60f72815e) | Jul 23, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [183db55de5](https://linux-hardware.org/?probe=183db55de5) | Jul 22, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [433b535407](https://linux-hardware.org/?probe=433b535407) | Jul 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [f9f12288d6](https://linux-hardware.org/?probe=f9f12288d6) | Jul 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [72257b8e54](https://linux-hardware.org/?probe=72257b8e54) | Jul 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [2ddaa196cc](https://linux-hardware.org/?probe=2ddaa196cc) | Jul 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [48e91ef395](https://linux-hardware.org/?probe=48e91ef395) | Jul 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [32df4c1524](https://linux-hardware.org/?probe=32df4c1524) | Jul 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [2cf13b3ff1](https://linux-hardware.org/?probe=2cf13b3ff1) | Jul 17, 2024 |
| Acer          | FI946GZG                    | Desktop     | [d84975220f](https://linux-hardware.org/?probe=d84975220f) | Jul 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [de385cf02c](https://linux-hardware.org/?probe=de385cf02c) | Jul 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [f43f547c9f](https://linux-hardware.org/?probe=f43f547c9f) | Jul 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [6cf80479b6](https://linux-hardware.org/?probe=6cf80479b6) | Jul 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [f2f80972b8](https://linux-hardware.org/?probe=f2f80972b8) | Jul 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [d0ace49bcb](https://linux-hardware.org/?probe=d0ace49bcb) | Jul 16, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1cf68fe3d7](https://linux-hardware.org/?probe=1cf68fe3d7) | Jul 15, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c48f0cc1b2](https://linux-hardware.org/?probe=c48f0cc1b2) | Jul 15, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [34be774c07](https://linux-hardware.org/?probe=34be774c07) | Jul 15, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [226e301f3f](https://linux-hardware.org/?probe=226e301f3f) | Jul 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d815d3cac0](https://linux-hardware.org/?probe=d815d3cac0) | Jul 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cd4a6e8390](https://linux-hardware.org/?probe=cd4a6e8390) | Jul 14, 2024 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [0bdf8eae36](https://linux-hardware.org/?probe=0bdf8eae36) | Jul 12, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [ea59b7a384](https://linux-hardware.org/?probe=ea59b7a384) | Jul 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9ed3dc5799](https://linux-hardware.org/?probe=9ed3dc5799) | Jul 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7973ab8579](https://linux-hardware.org/?probe=7973ab8579) | Jul 09, 2024 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [49d27ce9db](https://linux-hardware.org/?probe=49d27ce9db) | Jul 04, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [9c8da1caab](https://linux-hardware.org/?probe=9c8da1caab) | Jul 04, 2024 |
| Lenovo        | LOQ 15AHP9 83DX             | Notebook    | [529a1bbe93](https://linux-hardware.org/?probe=529a1bbe93) | Jul 03, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [0a03d09839](https://linux-hardware.org/?probe=0a03d09839) | Jul 03, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4286f8b939](https://linux-hardware.org/?probe=4286f8b939) | Jul 02, 2024 |
| Acer          | FI946GZG                    | Desktop     | [16e04577b8](https://linux-hardware.org/?probe=16e04577b8) | Jul 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [005a7e8a09](https://linux-hardware.org/?probe=005a7e8a09) | Jul 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1829045278](https://linux-hardware.org/?probe=1829045278) | Jul 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [933fb00685](https://linux-hardware.org/?probe=933fb00685) | Jul 01, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [786651db97](https://linux-hardware.org/?probe=786651db97) | Jul 01, 2024 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [0302ee9878](https://linux-hardware.org/?probe=0302ee9878) | Jul 01, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [55dad946a3](https://linux-hardware.org/?probe=55dad946a3) | Jul 01, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [2b84f47ca4](https://linux-hardware.org/?probe=2b84f47ca4) | Jul 01, 2024 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [901ec74a46](https://linux-hardware.org/?probe=901ec74a46) | Jun 24, 2024 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [63db3bc9a9](https://linux-hardware.org/?probe=63db3bc9a9) | Jun 17, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0c8ae4204b](https://linux-hardware.org/?probe=0c8ae4204b) | Jun 15, 2024 |
| Intel         | H61 V1.6B                   | Desktop     | [930c36f35d](https://linux-hardware.org/?probe=930c36f35d) | Jun 15, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [d206663ba5](https://linux-hardware.org/?probe=d206663ba5) | Jun 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a3e379e1a2](https://linux-hardware.org/?probe=a3e379e1a2) | Jun 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d277357bb9](https://linux-hardware.org/?probe=d277357bb9) | Jun 13, 2024 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [1a4d2729dd](https://linux-hardware.org/?probe=1a4d2729dd) | Jun 12, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4578b34174](https://linux-hardware.org/?probe=4578b34174) | Jun 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc1ed9cea2](https://linux-hardware.org/?probe=cc1ed9cea2) | Jun 08, 2024 |
| HP            | Pavilion dv6                | Notebook    | [424bc18b37](https://linux-hardware.org/?probe=424bc18b37) | Jun 03, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [6e93011557](https://linux-hardware.org/?probe=6e93011557) | Jun 03, 2024 |
| Acer          | FI946GZG                    | Desktop     | [bf78acff25](https://linux-hardware.org/?probe=bf78acff25) | Jun 01, 2024 |
| Acer          | FI946GZG                    | Desktop     | [76cc9c0af8](https://linux-hardware.org/?probe=76cc9c0af8) | Jun 01, 2024 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [7f4f6359fb](https://linux-hardware.org/?probe=7f4f6359fb) | May 31, 2024 |
| YiFang        | NXW9QC132                   | Notebook    | [50d779752e](https://linux-hardware.org/?probe=50d779752e) | May 29, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [d69c669f73](https://linux-hardware.org/?probe=d69c669f73) | May 28, 2024 |
| Gigabyte      | B75-D3V                     | Desktop     | [cd299d8bd3](https://linux-hardware.org/?probe=cd299d8bd3) | May 28, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [3ffe3e7739](https://linux-hardware.org/?probe=3ffe3e7739) | May 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8dfef957ae](https://linux-hardware.org/?probe=8dfef957ae) | May 26, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [fa1dcc0c49](https://linux-hardware.org/?probe=fa1dcc0c49) | May 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b267b3c6f4](https://linux-hardware.org/?probe=b267b3c6f4) | May 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4f83e7cef4](https://linux-hardware.org/?probe=4f83e7cef4) | May 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c379eac7bb](https://linux-hardware.org/?probe=c379eac7bb) | May 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [bc60b72d92](https://linux-hardware.org/?probe=bc60b72d92) | May 24, 2024 |
| Acer          | FI946GZG                    | Desktop     | [1574023469](https://linux-hardware.org/?probe=1574023469) | May 24, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [6258c97cef](https://linux-hardware.org/?probe=6258c97cef) | May 23, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7a2d54bf01](https://linux-hardware.org/?probe=7a2d54bf01) | May 23, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [57eb434493](https://linux-hardware.org/?probe=57eb434493) | May 22, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [35f636e9ed](https://linux-hardware.org/?probe=35f636e9ed) | May 22, 2024 |
| Acer          | FI946GZG                    | Desktop     | [0cfa96d8b2](https://linux-hardware.org/?probe=0cfa96d8b2) | May 19, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [993a349828](https://linux-hardware.org/?probe=993a349828) | May 19, 2024 |
| Acer          | FI946GZG                    | Desktop     | [6abf4b2ff8](https://linux-hardware.org/?probe=6abf4b2ff8) | May 18, 2024 |
| Acer          | FI946GZG                    | Desktop     | [a4b0b80358](https://linux-hardware.org/?probe=a4b0b80358) | May 18, 2024 |
| Acer          | FI946GZG                    | Desktop     | [988cb72164](https://linux-hardware.org/?probe=988cb72164) | May 18, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [f573f86638](https://linux-hardware.org/?probe=f573f86638) | May 18, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [ddfc70b249](https://linux-hardware.org/?probe=ddfc70b249) | May 17, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [2caf89e61e](https://linux-hardware.org/?probe=2caf89e61e) | May 17, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [a652572cf4](https://linux-hardware.org/?probe=a652572cf4) | May 17, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0b1e0b780b](https://linux-hardware.org/?probe=0b1e0b780b) | May 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [c3fcc836d1](https://linux-hardware.org/?probe=c3fcc836d1) | May 16, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [2d06257f62](https://linux-hardware.org/?probe=2d06257f62) | May 13, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [763bcd2c5c](https://linux-hardware.org/?probe=763bcd2c5c) | May 12, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b0611b400c](https://linux-hardware.org/?probe=b0611b400c) | May 12, 2024 |
| Lenovo        | G575 20081                  | Notebook    | [581885ea87](https://linux-hardware.org/?probe=581885ea87) | May 11, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [9fd594f9ed](https://linux-hardware.org/?probe=9fd594f9ed) | May 11, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | Notebook    | [bf21e1d142](https://linux-hardware.org/?probe=bf21e1d142) | May 11, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [44c103ea9f](https://linux-hardware.org/?probe=44c103ea9f) | May 11, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [298d99acb6](https://linux-hardware.org/?probe=298d99acb6) | May 11, 2024 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [f566c56a9f](https://linux-hardware.org/?probe=f566c56a9f) | May 10, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9c7ba4a173](https://linux-hardware.org/?probe=9c7ba4a173) | May 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [91ed38bf6d](https://linux-hardware.org/?probe=91ed38bf6d) | May 08, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [7a48c1a73b](https://linux-hardware.org/?probe=7a48c1a73b) | May 07, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cb063ef0b2](https://linux-hardware.org/?probe=cb063ef0b2) | May 06, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4a08259d5e](https://linux-hardware.org/?probe=4a08259d5e) | May 05, 2024 |
| Gigabyte      | Z690 UD                     | Desktop     | [700cd9b859](https://linux-hardware.org/?probe=700cd9b859) | May 02, 2024 |
| ASRock        | Z68 Pro3                    | Desktop     | [2b254bcdbb](https://linux-hardware.org/?probe=2b254bcdbb) | May 02, 2024 |
| Dell          | Latitude 7490               | Notebook    | [5e80dec6c8](https://linux-hardware.org/?probe=5e80dec6c8) | May 01, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [4c7535b1ac](https://linux-hardware.org/?probe=4c7535b1ac) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [56f9ef0976](https://linux-hardware.org/?probe=56f9ef0976) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [57a68c0dec](https://linux-hardware.org/?probe=57a68c0dec) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4939bdb260](https://linux-hardware.org/?probe=4939bdb260) | Apr 30, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c31443d648](https://linux-hardware.org/?probe=c31443d648) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9f0eda367d](https://linux-hardware.org/?probe=9f0eda367d) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [06b56e10dc](https://linux-hardware.org/?probe=06b56e10dc) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [3e16c2d8c6](https://linux-hardware.org/?probe=3e16c2d8c6) | Apr 28, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [bf18be8805](https://linux-hardware.org/?probe=bf18be8805) | Apr 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [773cffce7f](https://linux-hardware.org/?probe=773cffce7f) | Apr 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7f54c26bc1](https://linux-hardware.org/?probe=7f54c26bc1) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e7a56f20f9](https://linux-hardware.org/?probe=e7a56f20f9) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8ed8b87e84](https://linux-hardware.org/?probe=8ed8b87e84) | Apr 25, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [45b756650e](https://linux-hardware.org/?probe=45b756650e) | Apr 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1086d184b6](https://linux-hardware.org/?probe=1086d184b6) | Apr 24, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fd94025498](https://linux-hardware.org/?probe=fd94025498) | Apr 23, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [4ffd3e632b](https://linux-hardware.org/?probe=4ffd3e632b) | Apr 22, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [0a9ede9e09](https://linux-hardware.org/?probe=0a9ede9e09) | Apr 22, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0b6a8b8487](https://linux-hardware.org/?probe=0b6a8b8487) | Apr 21, 2024 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [b8d6f42912](https://linux-hardware.org/?probe=b8d6f42912) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a1cc621a2f](https://linux-hardware.org/?probe=a1cc621a2f) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [5ff81fe9b8](https://linux-hardware.org/?probe=5ff81fe9b8) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [22ba7e810f](https://linux-hardware.org/?probe=22ba7e810f) | Apr 20, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [88986725e7](https://linux-hardware.org/?probe=88986725e7) | Apr 20, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [3022280b20](https://linux-hardware.org/?probe=3022280b20) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [018abcebe4](https://linux-hardware.org/?probe=018abcebe4) | Apr 19, 2024 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [71d2f1f549](https://linux-hardware.org/?probe=71d2f1f549) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e65c84d822](https://linux-hardware.org/?probe=e65c84d822) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d1cf256cf2](https://linux-hardware.org/?probe=d1cf256cf2) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1f8cb5a4d](https://linux-hardware.org/?probe=e1f8cb5a4d) | Apr 18, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [cfacf09dbe](https://linux-hardware.org/?probe=cfacf09dbe) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7cd3cf42ef](https://linux-hardware.org/?probe=7cd3cf42ef) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [fd99b7519e](https://linux-hardware.org/?probe=fd99b7519e) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9c51df5a4a](https://linux-hardware.org/?probe=9c51df5a4a) | Apr 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4b84c41edf](https://linux-hardware.org/?probe=4b84c41edf) | Apr 15, 2024 |
| HP            | Unknown                     | Notebook    | [9415eb2f3c](https://linux-hardware.org/?probe=9415eb2f3c) | Apr 14, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [c7a6c2d6ed](https://linux-hardware.org/?probe=c7a6c2d6ed) | Apr 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9f29571aab](https://linux-hardware.org/?probe=9f29571aab) | Apr 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [7259447d3b](https://linux-hardware.org/?probe=7259447d3b) | Apr 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [64eef30697](https://linux-hardware.org/?probe=64eef30697) | Apr 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [14ff2613c4](https://linux-hardware.org/?probe=14ff2613c4) | Apr 13, 2024 |
| MSI           | Z77MA-G45                   | Desktop     | [7a6ac2c320](https://linux-hardware.org/?probe=7a6ac2c320) | Apr 11, 2024 |
| Acer          | AO756                       | Notebook    | [79847ca0b1](https://linux-hardware.org/?probe=79847ca0b1) | Apr 11, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [bcb9300739](https://linux-hardware.org/?probe=bcb9300739) | Apr 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [79a4ac6c52](https://linux-hardware.org/?probe=79a4ac6c52) | Apr 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b2df81d7c6](https://linux-hardware.org/?probe=b2df81d7c6) | Apr 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a12df57269](https://linux-hardware.org/?probe=a12df57269) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [648e1cbe49](https://linux-hardware.org/?probe=648e1cbe49) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e41ebb7b08](https://linux-hardware.org/?probe=e41ebb7b08) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [c03a952f7a](https://linux-hardware.org/?probe=c03a952f7a) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [eeb5af4e4d](https://linux-hardware.org/?probe=eeb5af4e4d) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [45c3f7f796](https://linux-hardware.org/?probe=45c3f7f796) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1a32810f8](https://linux-hardware.org/?probe=e1a32810f8) | Mar 29, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9be524311b](https://linux-hardware.org/?probe=9be524311b) | Mar 29, 2024 |
| OEM           | H310C Ver:1.00              | Desktop     | [4b6ef4e649](https://linux-hardware.org/?probe=4b6ef4e649) | Mar 27, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1cda914d9f](https://linux-hardware.org/?probe=1cda914d9f) | Mar 27, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1652f0954c](https://linux-hardware.org/?probe=1652f0954c) | Mar 26, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e772c3db14](https://linux-hardware.org/?probe=e772c3db14) | Mar 26, 2024 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [36da9413fa](https://linux-hardware.org/?probe=36da9413fa) | Mar 25, 2024 |
| Acer          | One S1002                   | Notebook    | [801033acf2](https://linux-hardware.org/?probe=801033acf2) | Mar 25, 2024 |
| Acer          | One S1002                   | Notebook    | [7f3114ec4e](https://linux-hardware.org/?probe=7f3114ec4e) | Mar 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [433fee63bc](https://linux-hardware.org/?probe=433fee63bc) | Mar 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bbb4a23341](https://linux-hardware.org/?probe=bbb4a23341) | Mar 24, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [458c974b3b](https://linux-hardware.org/?probe=458c974b3b) | Mar 22, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e5613c8592](https://linux-hardware.org/?probe=e5613c8592) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [e1da52705a](https://linux-hardware.org/?probe=e1da52705a) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [99789095cd](https://linux-hardware.org/?probe=99789095cd) | Mar 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [faca2983cf](https://linux-hardware.org/?probe=faca2983cf) | Mar 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [2152124e4d](https://linux-hardware.org/?probe=2152124e4d) | Mar 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [d02fd3d860](https://linux-hardware.org/?probe=d02fd3d860) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [3bd52dc634](https://linux-hardware.org/?probe=3bd52dc634) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [35209a450e](https://linux-hardware.org/?probe=35209a450e) | Mar 17, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [12ebbdd41a](https://linux-hardware.org/?probe=12ebbdd41a) | Mar 15, 2024 |
| Foxconn       | B75M                        | Desktop     | [c8005ccd1d](https://linux-hardware.org/?probe=c8005ccd1d) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [9170891a99](https://linux-hardware.org/?probe=9170891a99) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1da99640ba](https://linux-hardware.org/?probe=1da99640ba) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [00e6d44f41](https://linux-hardware.org/?probe=00e6d44f41) | Mar 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [930838ef76](https://linux-hardware.org/?probe=930838ef76) | Mar 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1c8ceb24a1](https://linux-hardware.org/?probe=1c8ceb24a1) | Mar 14, 2024 |
| Foxconn       | B75M                        | Desktop     | [e1cf2eb1cd](https://linux-hardware.org/?probe=e1cf2eb1cd) | Mar 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [d75eaeebc0](https://linux-hardware.org/?probe=d75eaeebc0) | Mar 13, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [5391520be0](https://linux-hardware.org/?probe=5391520be0) | Mar 12, 2024 |
| IP3 Tech      | GB3                         | Mini pc     | [b396284786](https://linux-hardware.org/?probe=b396284786) | Mar 12, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1eecb13729](https://linux-hardware.org/?probe=1eecb13729) | Mar 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [79ca53b90b](https://linux-hardware.org/?probe=79ca53b90b) | Mar 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [3080527b19](https://linux-hardware.org/?probe=3080527b19) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [299b810e81](https://linux-hardware.org/?probe=299b810e81) | Mar 06, 2024 |
| Gigabyte      | B75-D3V                     | Desktop     | [3202bffb91](https://linux-hardware.org/?probe=3202bffb91) | Mar 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [34c6283f00](https://linux-hardware.org/?probe=34c6283f00) | Mar 05, 2024 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [eaa7dc4743](https://linux-hardware.org/?probe=eaa7dc4743) | Mar 03, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [aeee54cee7](https://linux-hardware.org/?probe=aeee54cee7) | Feb 27, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cd83a56af8](https://linux-hardware.org/?probe=cd83a56af8) | Feb 27, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [126dbc29f9](https://linux-hardware.org/?probe=126dbc29f9) | Feb 26, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [3015e2635f](https://linux-hardware.org/?probe=3015e2635f) | Feb 25, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [46e3558e2c](https://linux-hardware.org/?probe=46e3558e2c) | Feb 23, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [dc85539c15](https://linux-hardware.org/?probe=dc85539c15) | Feb 23, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [32aa95befd](https://linux-hardware.org/?probe=32aa95befd) | Feb 23, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [aabaa18698](https://linux-hardware.org/?probe=aabaa18698) | Feb 21, 2024 |
| Dell          | Latitude 5540               | Notebook    | [c5a3f8e55f](https://linux-hardware.org/?probe=c5a3f8e55f) | Feb 16, 2024 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [bb4aa86fa0](https://linux-hardware.org/?probe=bb4aa86fa0) | Feb 13, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [da0c61667c](https://linux-hardware.org/?probe=da0c61667c) | Feb 12, 2024 |
| Lenovo        | ThinkPad X240 20AMS1E201    | Notebook    | [469bc2a33d](https://linux-hardware.org/?probe=469bc2a33d) | Feb 11, 2024 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [16ea131211](https://linux-hardware.org/?probe=16ea131211) | Feb 10, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [004ab7b6d5](https://linux-hardware.org/?probe=004ab7b6d5) | Feb 10, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [7053f118d5](https://linux-hardware.org/?probe=7053f118d5) | Feb 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [48cf9448c1](https://linux-hardware.org/?probe=48cf9448c1) | Feb 09, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [22cd39d25b](https://linux-hardware.org/?probe=22cd39d25b) | Feb 06, 2024 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [05931d928d](https://linux-hardware.org/?probe=05931d928d) | Feb 03, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [9b2e938cb4](https://linux-hardware.org/?probe=9b2e938cb4) | Feb 02, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [b412a671e4](https://linux-hardware.org/?probe=b412a671e4) | Feb 02, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e94976b6d9](https://linux-hardware.org/?probe=e94976b6d9) | Feb 01, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [dbb897d3e1](https://linux-hardware.org/?probe=dbb897d3e1) | Jan 30, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [dd92e4a676](https://linux-hardware.org/?probe=dd92e4a676) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ffc3c06598](https://linux-hardware.org/?probe=ffc3c06598) | Jan 29, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [312fc3b893](https://linux-hardware.org/?probe=312fc3b893) | Jan 28, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [80c0bacde5](https://linux-hardware.org/?probe=80c0bacde5) | Jan 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [70a0ef842a](https://linux-hardware.org/?probe=70a0ef842a) | Jan 25, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1a19df4d59](https://linux-hardware.org/?probe=1a19df4d59) | Jan 23, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [5722aa300f](https://linux-hardware.org/?probe=5722aa300f) | Jan 21, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [91fd34a0da](https://linux-hardware.org/?probe=91fd34a0da) | Jan 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [bc8248af06](https://linux-hardware.org/?probe=bc8248af06) | Jan 21, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [17f186ad10](https://linux-hardware.org/?probe=17f186ad10) | Jan 20, 2024 |
| Acer          | Aspire E1-570               | Notebook    | [7def6b176c](https://linux-hardware.org/?probe=7def6b176c) | Jan 19, 2024 |
| Acer          | Aspire E1-570               | Notebook    | [47a1e9c03c](https://linux-hardware.org/?probe=47a1e9c03c) | Jan 19, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [99bcba4ae3](https://linux-hardware.org/?probe=99bcba4ae3) | Jan 17, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [196ce97a62](https://linux-hardware.org/?probe=196ce97a62) | Jan 16, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [bf7672b4a4](https://linux-hardware.org/?probe=bf7672b4a4) | Jan 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8a02dab1f4](https://linux-hardware.org/?probe=8a02dab1f4) | Jan 15, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cb5bd1f14f](https://linux-hardware.org/?probe=cb5bd1f14f) | Jan 14, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [2626e31d7a](https://linux-hardware.org/?probe=2626e31d7a) | Jan 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [439b30f633](https://linux-hardware.org/?probe=439b30f633) | Jan 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [35533bf402](https://linux-hardware.org/?probe=35533bf402) | Jan 14, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [783185e5af](https://linux-hardware.org/?probe=783185e5af) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1742e2e526](https://linux-hardware.org/?probe=1742e2e526) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [43ceb02173](https://linux-hardware.org/?probe=43ceb02173) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [6adea77d15](https://linux-hardware.org/?probe=6adea77d15) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cde9d2553f](https://linux-hardware.org/?probe=cde9d2553f) | Jan 12, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [6c82d498ba](https://linux-hardware.org/?probe=6c82d498ba) | Jan 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [96faa10437](https://linux-hardware.org/?probe=96faa10437) | Jan 11, 2024 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [15f0bd78f4](https://linux-hardware.org/?probe=15f0bd78f4) | Jan 10, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [975fff0a28](https://linux-hardware.org/?probe=975fff0a28) | Jan 10, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4d91095fa0](https://linux-hardware.org/?probe=4d91095fa0) | Jan 10, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [6909d543b0](https://linux-hardware.org/?probe=6909d543b0) | Jan 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [ec094665df](https://linux-hardware.org/?probe=ec094665df) | Jan 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [e08d38f8a0](https://linux-hardware.org/?probe=e08d38f8a0) | Jan 09, 2024 |
| ASRock        | Z77 Extreme3                | Desktop     | [5b6dee9bbe](https://linux-hardware.org/?probe=5b6dee9bbe) | Jan 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [a3fa43281d](https://linux-hardware.org/?probe=a3fa43281d) | Jan 09, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [ddc21e0978](https://linux-hardware.org/?probe=ddc21e0978) | Jan 08, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [40407d3445](https://linux-hardware.org/?probe=40407d3445) | Jan 08, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cb1ceea0b8](https://linux-hardware.org/?probe=cb1ceea0b8) | Jan 07, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [ca81fd63fd](https://linux-hardware.org/?probe=ca81fd63fd) | Jan 07, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [62a2d8032e](https://linux-hardware.org/?probe=62a2d8032e) | Jan 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [710f99bd78](https://linux-hardware.org/?probe=710f99bd78) | Jan 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [b98b78a3df](https://linux-hardware.org/?probe=b98b78a3df) | Jan 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [c192611a71](https://linux-hardware.org/?probe=c192611a71) | Jan 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [78696f8410](https://linux-hardware.org/?probe=78696f8410) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [c4f303d6a1](https://linux-hardware.org/?probe=c4f303d6a1) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [37999c37df](https://linux-hardware.org/?probe=37999c37df) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [1aec475668](https://linux-hardware.org/?probe=1aec475668) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8e8ffbd00e](https://linux-hardware.org/?probe=8e8ffbd00e) | Jan 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [11efc6aeb2](https://linux-hardware.org/?probe=11efc6aeb2) | Jan 04, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [beb2119db9](https://linux-hardware.org/?probe=beb2119db9) | Jan 03, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [8ea5e6198c](https://linux-hardware.org/?probe=8ea5e6198c) | Jan 03, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [5744834a9e](https://linux-hardware.org/?probe=5744834a9e) | Jan 03, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [4d0fa4b70d](https://linux-hardware.org/?probe=4d0fa4b70d) | Jan 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [243e9d1b27](https://linux-hardware.org/?probe=243e9d1b27) | Jan 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [edfe085e75](https://linux-hardware.org/?probe=edfe085e75) | Jan 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [5f34a26ab3](https://linux-hardware.org/?probe=5f34a26ab3) | Jan 01, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [edf3eae913](https://linux-hardware.org/?probe=edf3eae913) | Dec 31, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [00b52d9fa3](https://linux-hardware.org/?probe=00b52d9fa3) | Dec 30, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [cb13028da5](https://linux-hardware.org/?probe=cb13028da5) | Dec 28, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [7345f4357e](https://linux-hardware.org/?probe=7345f4357e) | Dec 28, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [de1329753d](https://linux-hardware.org/?probe=de1329753d) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7fdd8a3f38](https://linux-hardware.org/?probe=7fdd8a3f38) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a1fd8cc737](https://linux-hardware.org/?probe=a1fd8cc737) | Dec 26, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [7a4d238793](https://linux-hardware.org/?probe=7a4d238793) | Dec 25, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [d698ea94f5](https://linux-hardware.org/?probe=d698ea94f5) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [bfe0870fab](https://linux-hardware.org/?probe=bfe0870fab) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [d6c1f0d202](https://linux-hardware.org/?probe=d6c1f0d202) | Dec 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a7ad5fb789](https://linux-hardware.org/?probe=a7ad5fb789) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [775e2dfe26](https://linux-hardware.org/?probe=775e2dfe26) | Dec 19, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [736ba321d5](https://linux-hardware.org/?probe=736ba321d5) | Dec 18, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [ad7f762f22](https://linux-hardware.org/?probe=ad7f762f22) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [f4c923a84a](https://linux-hardware.org/?probe=f4c923a84a) | Dec 16, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [46178ea298](https://linux-hardware.org/?probe=46178ea298) | Dec 14, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [0f58876ad4](https://linux-hardware.org/?probe=0f58876ad4) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [f1860954b3](https://linux-hardware.org/?probe=f1860954b3) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [1ed13ea8f2](https://linux-hardware.org/?probe=1ed13ea8f2) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [eafb9ad287](https://linux-hardware.org/?probe=eafb9ad287) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [3504153caa](https://linux-hardware.org/?probe=3504153caa) | Dec 14, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [e2c79fa4d1](https://linux-hardware.org/?probe=e2c79fa4d1) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1668553525](https://linux-hardware.org/?probe=1668553525) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [89bef2fed5](https://linux-hardware.org/?probe=89bef2fed5) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0ed1d85207](https://linux-hardware.org/?probe=0ed1d85207) | Dec 13, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e21d372813](https://linux-hardware.org/?probe=e21d372813) | Dec 13, 2023 |
| Canyon        | I865P/PE                    | Desktop     | [68de5ab5cb](https://linux-hardware.org/?probe=68de5ab5cb) | Dec 12, 2023 |
| Samsung       | R428/P428                   | Notebook    | [bcfc7ba90f](https://linux-hardware.org/?probe=bcfc7ba90f) | Dec 09, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b3549a6dea](https://linux-hardware.org/?probe=b3549a6dea) | Dec 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c693deae3](https://linux-hardware.org/?probe=2c693deae3) | Dec 07, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6d0f07a930](https://linux-hardware.org/?probe=6d0f07a930) | Dec 05, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [622055b29a](https://linux-hardware.org/?probe=622055b29a) | Dec 02, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a5a00f200f](https://linux-hardware.org/?probe=a5a00f200f) | Nov 29, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [d5d85d7080](https://linux-hardware.org/?probe=d5d85d7080) | Nov 27, 2023 |
| ECS           | G41T-M5                     | Desktop     | [12302fb1a3](https://linux-hardware.org/?probe=12302fb1a3) | Nov 24, 2023 |
| ECS           | G41T-M5                     | Desktop     | [95038a0bab](https://linux-hardware.org/?probe=95038a0bab) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G834JY_G834JY     | Notebook    | [26a2d5750f](https://linux-hardware.org/?probe=26a2d5750f) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c6e62720db](https://linux-hardware.org/?probe=c6e62720db) | Nov 22, 2023 |
| ASRock        | G31M-VS                     | Desktop     | [90703790aa](https://linux-hardware.org/?probe=90703790aa) | Nov 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1aa00f4008](https://linux-hardware.org/?probe=1aa00f4008) | Nov 17, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Lenovo        | ThinkPad T430 23475H2       | Notebook    | [3dcdf3830e](https://linux-hardware.org/?probe=3dcdf3830e) | Nov 07, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [624a99186e](https://linux-hardware.org/?probe=624a99186e) | Oct 30, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [42e6514c85](https://linux-hardware.org/?probe=42e6514c85) | Oct 29, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [b18bbae606](https://linux-hardware.org/?probe=b18bbae606) | Oct 27, 2023 |
| Dell          | Latitude E7270              | Notebook    | [07d72d2a9d](https://linux-hardware.org/?probe=07d72d2a9d) | Oct 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1bd81ebf81](https://linux-hardware.org/?probe=1bd81ebf81) | Oct 24, 2023 |
| HP            | Pavilion Laptop 15-eh3xx... | Notebook    | [d2a1f0ba6e](https://linux-hardware.org/?probe=d2a1f0ba6e) | Oct 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ffeaa7da2f](https://linux-hardware.org/?probe=ffeaa7da2f) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| ASRock        | Z370 Taichi                 | Desktop     | [ca57155c40](https://linux-hardware.org/?probe=ca57155c40) | Oct 19, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [ae0eccc095](https://linux-hardware.org/?probe=ae0eccc095) | Oct 18, 2023 |
| Chuwi         | M01ALWR310-ADA90B           | Mini pc     | [4dbcbacf46](https://linux-hardware.org/?probe=4dbcbacf46) | Oct 18, 2023 |
| MSI           | G31M3-F V2                  | Desktop     | [9a26b22114](https://linux-hardware.org/?probe=9a26b22114) | Oct 14, 2023 |
| Acer          | Predator PH317-56           | Notebook    | [2089e200d9](https://linux-hardware.org/?probe=2089e200d9) | Oct 12, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [56bdc382d5](https://linux-hardware.org/?probe=56bdc382d5) | Oct 10, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Acer          | Predator PH317-56           | Notebook    | [3adaae9e9e](https://linux-hardware.org/?probe=3adaae9e9e) | Oct 06, 2023 |
| Acer          | Predator PH317-54           | Notebook    | [8745400c59](https://linux-hardware.org/?probe=8745400c59) | Oct 06, 2023 |
| HP            | 3031h                       | Desktop     | [a05ac19b87](https://linux-hardware.org/?probe=a05ac19b87) | Oct 03, 2023 |
| HP            | Notebook                    | Notebook    | [02403b0967](https://linux-hardware.org/?probe=02403b0967) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [7ebc133bf7](https://linux-hardware.org/?probe=7ebc133bf7) | Oct 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [b8ace5a2d6](https://linux-hardware.org/?probe=b8ace5a2d6) | Oct 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [11cbffaee6](https://linux-hardware.org/?probe=11cbffaee6) | Oct 02, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [64e8a0bcc2](https://linux-hardware.org/?probe=64e8a0bcc2) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [13a2717815](https://linux-hardware.org/?probe=13a2717815) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [14d87bfb5d](https://linux-hardware.org/?probe=14d87bfb5d) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [6f676cd559](https://linux-hardware.org/?probe=6f676cd559) | Sep 18, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [83021c4304](https://linux-hardware.org/?probe=83021c4304) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9ea0aa4b28](https://linux-hardware.org/?probe=9ea0aa4b28) | Sep 10, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [1c695a40ca](https://linux-hardware.org/?probe=1c695a40ca) | Sep 09, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [b002674315](https://linux-hardware.org/?probe=b002674315) | Sep 09, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [b3a181910f](https://linux-hardware.org/?probe=b3a181910f) | Sep 08, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [3a6cb86551](https://linux-hardware.org/?probe=3a6cb86551) | Sep 07, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [6ba5f1b344](https://linux-hardware.org/?probe=6ba5f1b344) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [ea096b699b](https://linux-hardware.org/?probe=ea096b699b) | Sep 04, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [f92734bf2b](https://linux-hardware.org/?probe=f92734bf2b) | Sep 03, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [29a4025447](https://linux-hardware.org/?probe=29a4025447) | Sep 02, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [53cd38e0c5](https://linux-hardware.org/?probe=53cd38e0c5) | Sep 02, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [7aa770bf00](https://linux-hardware.org/?probe=7aa770bf00) | Aug 30, 2023 |
| Supermicro    | X11DPG-QTA                  | Server      | [f2f86694d8](https://linux-hardware.org/?probe=f2f86694d8) | Aug 29, 2023 |
| Kobian        | PI945GCM ECS                | Desktop     | [85683b5fa3](https://linux-hardware.org/?probe=85683b5fa3) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [0140ea0642](https://linux-hardware.org/?probe=0140ea0642) | Aug 26, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [58afba6baf](https://linux-hardware.org/?probe=58afba6baf) | Aug 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d8caf086ad](https://linux-hardware.org/?probe=d8caf086ad) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [87c4730d07](https://linux-hardware.org/?probe=87c4730d07) | Aug 03, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [7d262746c9](https://linux-hardware.org/?probe=7d262746c9) | Jul 30, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ECS           | P43T-A2                     | Desktop     | [a25280247b](https://linux-hardware.org/?probe=a25280247b) | Jul 25, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9d3efe2fa2](https://linux-hardware.org/?probe=9d3efe2fa2) | Jul 18, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [77e5715691](https://linux-hardware.org/?probe=77e5715691) | Jul 12, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [4b611c264e](https://linux-hardware.org/?probe=4b611c264e) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [1327fb98ac](https://linux-hardware.org/?probe=1327fb98ac) | Jul 04, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4ec56be6a5](https://linux-hardware.org/?probe=4ec56be6a5) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [107c99d5ee](https://linux-hardware.org/?probe=107c99d5ee) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [0617f8b2f0](https://linux-hardware.org/?probe=0617f8b2f0) | Jul 02, 2023 |
| ECS           | P67H2-A3                    | Desktop     | [d23f1fda24](https://linux-hardware.org/?probe=d23f1fda24) | Jul 02, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2940c0be7d](https://linux-hardware.org/?probe=2940c0be7d) | Jul 01, 2023 |
| ECS           | P67H2-A3                    | Desktop     | [f35a6b0a66](https://linux-hardware.org/?probe=f35a6b0a66) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [8a833d8c52](https://linux-hardware.org/?probe=8a833d8c52) | Jun 25, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [0e6960c76b](https://linux-hardware.org/?probe=0e6960c76b) | Jun 22, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [981385c200](https://linux-hardware.org/?probe=981385c200) | Jun 22, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7d66d312d2](https://linux-hardware.org/?probe=7d66d312d2) | Jun 16, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [130605379e](https://linux-hardware.org/?probe=130605379e) | Jun 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dd2a8a9559](https://linux-hardware.org/?probe=dd2a8a9559) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [a6d6fdfe4f](https://linux-hardware.org/?probe=a6d6fdfe4f) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [bd06482a4e](https://linux-hardware.org/?probe=bd06482a4e) | May 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c73e482b69](https://linux-hardware.org/?probe=c73e482b69) | May 18, 2023 |
| HP            | Notebook                    | Notebook    | [3467291a26](https://linux-hardware.org/?probe=3467291a26) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8b36611a25](https://linux-hardware.org/?probe=8b36611a25) | May 02, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [a1b8584d65](https://linux-hardware.org/?probe=a1b8584d65) | May 01, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [88e7444fa5](https://linux-hardware.org/?probe=88e7444fa5) | Apr 30, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [763e7fa1b6](https://linux-hardware.org/?probe=763e7fa1b6) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| ASUSTek       | X55VD                       | Notebook    | [16ef8c0549](https://linux-hardware.org/?probe=16ef8c0549) | Apr 27, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | 374B No DPK                 | All in one  | [c87417466c](https://linux-hardware.org/?probe=c87417466c) | Apr 18, 2023 |
| Lenovo        | 374B No DPK                 | All in one  | [4a7133799c](https://linux-hardware.org/?probe=4a7133799c) | Apr 18, 2023 |
| ASUSTek       | GR6                         | Desktop     | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [ea0055d848](https://linux-hardware.org/?probe=ea0055d848) | Apr 14, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [99f214269f](https://linux-hardware.org/?probe=99f214269f) | Apr 13, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c961550658](https://linux-hardware.org/?probe=c961550658) | Apr 13, 2023 |
| Dell          | G5 5590                     | Notebook    | [9c1f2f432b](https://linux-hardware.org/?probe=9c1f2f432b) | Apr 11, 2023 |
| HP            | Notebook                    | Notebook    | [41f9931a45](https://linux-hardware.org/?probe=41f9931a45) | Apr 07, 2023 |
| HP            | Notebook                    | Notebook    | [a344d6edef](https://linux-hardware.org/?probe=a344d6edef) | Apr 05, 2023 |
| Biostar       | H61MLV                      | Desktop     | [db9714357e](https://linux-hardware.org/?probe=db9714357e) | Apr 01, 2023 |
| GPD           | G1621-02                    | Notebook    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| Dell          | 072T6D A01                  | Server      | [be75097d0f](https://linux-hardware.org/?probe=be75097d0f) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [252d340923](https://linux-hardware.org/?probe=252d340923) | Mar 30, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | X55VDR                      | Notebook    | [b4eb9dbf58](https://linux-hardware.org/?probe=b4eb9dbf58) | Mar 20, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [c49dee996b](https://linux-hardware.org/?probe=c49dee996b) | Mar 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| Intel         | H61                         | Desktop     | [7bc298c53d](https://linux-hardware.org/?probe=7bc298c53d) | Mar 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [169294f95f](https://linux-hardware.org/?probe=169294f95f) | Feb 28, 2023 |
| HP            | 1497                        | Desktop     | [bd24913452](https://linux-hardware.org/?probe=bd24913452) | Feb 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [aa1fb72fa5](https://linux-hardware.org/?probe=aa1fb72fa5) | Feb 15, 2023 |
| GPD           | G1621-02                    | Notebook    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [77e13c5748](https://linux-hardware.org/?probe=77e13c5748) | Feb 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [b644932b49](https://linux-hardware.org/?probe=b644932b49) | Feb 06, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [ba7531b9db](https://linux-hardware.org/?probe=ba7531b9db) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [72228118bb](https://linux-hardware.org/?probe=72228118bb) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| Unknown       | Unknown                     | Soc         | [8512c1d0cc](https://linux-hardware.org/?probe=8512c1d0cc) | Jan 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Gigabyte      | GA-73PVM-S2                 | Desktop     | [fcf91f09b4](https://linux-hardware.org/?probe=fcf91f09b4) | Jan 28, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [a746d3fd78](https://linux-hardware.org/?probe=a746d3fd78) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [52a02b4c4f](https://linux-hardware.org/?probe=52a02b4c4f) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [d2d30c8d6f](https://linux-hardware.org/?probe=d2d30c8d6f) | Jan 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [07cf342b4f](https://linux-hardware.org/?probe=07cf342b4f) | Jan 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [78791e5b9e](https://linux-hardware.org/?probe=78791e5b9e) | Jan 20, 2023 |
| ECS           | G41T-M7                     | Desktop     | [e6be57e3c3](https://linux-hardware.org/?probe=e6be57e3c3) | Jan 20, 2023 |
| ECS           | G41T-M7                     | Desktop     | [51a45a431a](https://linux-hardware.org/?probe=51a45a431a) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [242329daf8](https://linux-hardware.org/?probe=242329daf8) | Jan 15, 2023 |
| HP            | 84EE 1100                   | All in one  | [79c81fcfb5](https://linux-hardware.org/?probe=79c81fcfb5) | Jan 14, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [71f6d9b711](https://linux-hardware.org/?probe=71f6d9b711) | Jan 12, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6a873e3df8](https://linux-hardware.org/?probe=6a873e3df8) | Jan 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbd401e3c6](https://linux-hardware.org/?probe=cbd401e3c6) | Jan 11, 2023 |
| HP            | 87F9 A00                    | All in one  | [433fd99d94](https://linux-hardware.org/?probe=433fd99d94) | Jan 09, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [3111141139](https://linux-hardware.org/?probe=3111141139) | Dec 26, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [b53beddded](https://linux-hardware.org/?probe=b53beddded) | Dec 23, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [4fc8630d91](https://linux-hardware.org/?probe=4fc8630d91) | Dec 22, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [bbc48ee483](https://linux-hardware.org/?probe=bbc48ee483) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [8777d682b0](https://linux-hardware.org/?probe=8777d682b0) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [faf7ad4c29](https://linux-hardware.org/?probe=faf7ad4c29) | Dec 19, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [116b321e68](https://linux-hardware.org/?probe=116b321e68) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | Notebook    | [8290c7e597](https://linux-hardware.org/?probe=8290c7e597) | Dec 16, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [5f2e420614](https://linux-hardware.org/?probe=5f2e420614) | Dec 15, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [8a381fe525](https://linux-hardware.org/?probe=8a381fe525) | Dec 14, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [90b4e5f1b2](https://linux-hardware.org/?probe=90b4e5f1b2) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [11b83fa996](https://linux-hardware.org/?probe=11b83fa996) | Dec 14, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [1b1e1ae174](https://linux-hardware.org/?probe=1b1e1ae174) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [26828f578e](https://linux-hardware.org/?probe=26828f578e) | Dec 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ef6247e6fd](https://linux-hardware.org/?probe=ef6247e6fd) | Nov 28, 2022 |
| Dell          | Precision M6400             | Notebook    | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | Desktop     | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| GPD           | G1621-02                    | Notebook    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| GPD           | G1621-02                    | Notebook    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e08bf40900](https://linux-hardware.org/?probe=e08bf40900) | Nov 25, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [a636cfb9ff](https://linux-hardware.org/?probe=a636cfb9ff) | Nov 24, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [7ad1a412ae](https://linux-hardware.org/?probe=7ad1a412ae) | Nov 20, 2022 |
| Acer          | Swift SF314-58G             | Notebook    | [9e729e43a7](https://linux-hardware.org/?probe=9e729e43a7) | Nov 20, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [be2b867450](https://linux-hardware.org/?probe=be2b867450) | Nov 20, 2022 |
| Dell          | Latitude 5520               | Notebook    | [c658158f10](https://linux-hardware.org/?probe=c658158f10) | Nov 15, 2022 |
| Dell          | Latitude 5520               | Notebook    | [6e0490d1bf](https://linux-hardware.org/?probe=6e0490d1bf) | Nov 14, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [d584008808](https://linux-hardware.org/?probe=d584008808) | Nov 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [d7ae86ad73](https://linux-hardware.org/?probe=d7ae86ad73) | Nov 13, 2022 |
| Foxconn       | H77M/H77M-S                 | Desktop     | [bebf7f53f8](https://linux-hardware.org/?probe=bebf7f53f8) | Nov 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| Chuwi         | CoreBook XPro               | Notebook    | [0a0932246f](https://linux-hardware.org/?probe=0a0932246f) | Nov 09, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [d5c179046a](https://linux-hardware.org/?probe=d5c179046a) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [65ac5d12c7](https://linux-hardware.org/?probe=65ac5d12c7) | Nov 06, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [3ffeb18e56](https://linux-hardware.org/?probe=3ffeb18e56) | Nov 06, 2022 |
| ASRock        | B85M Pro4                   | Desktop     | [55da31d807](https://linux-hardware.org/?probe=55da31d807) | Nov 04, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [eaa9bcaadb](https://linux-hardware.org/?probe=eaa9bcaadb) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [7b016c85d8](https://linux-hardware.org/?probe=7b016c85d8) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [17faa0d40a](https://linux-hardware.org/?probe=17faa0d40a) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [8b68d25121](https://linux-hardware.org/?probe=8b68d25121) | Oct 26, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [244d93ab06](https://linux-hardware.org/?probe=244d93ab06) | Oct 21, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [dc26121480](https://linux-hardware.org/?probe=dc26121480) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4c95f64c92](https://linux-hardware.org/?probe=4c95f64c92) | Oct 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c8bb32147f](https://linux-hardware.org/?probe=c8bb32147f) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [2740d3c96e](https://linux-hardware.org/?probe=2740d3c96e) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | Notebook    | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [54d1a0ebb2](https://linux-hardware.org/?probe=54d1a0ebb2) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [7969631063](https://linux-hardware.org/?probe=7969631063) | Oct 11, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [f6d2b67f4a](https://linux-hardware.org/?probe=f6d2b67f4a) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f5e933eaac](https://linux-hardware.org/?probe=f5e933eaac) | Oct 10, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [6270245e93](https://linux-hardware.org/?probe=6270245e93) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [2ac8b7a157](https://linux-hardware.org/?probe=2ac8b7a157) | Oct 03, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| Sony          | VGN-FW245J                  | Notebook    | [ab3391f43e](https://linux-hardware.org/?probe=ab3391f43e) | Sep 18, 2022 |
| Chuwi         | UBook XPro                  | Notebook    | [b695b65d86](https://linux-hardware.org/?probe=b695b65d86) | Sep 10, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b592ce837a](https://linux-hardware.org/?probe=b592ce837a) | Aug 27, 2022 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [186a63fa9e](https://linux-hardware.org/?probe=186a63fa9e) | Aug 27, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d47bac5d9d](https://linux-hardware.org/?probe=d47bac5d9d) | Jul 26, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [46876a159f](https://linux-hardware.org/?probe=46876a159f) | Jul 26, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| Lenovo        | ThinkPad E470 20H1006HRT    | Notebook    | [ff4adb2f7d](https://linux-hardware.org/?probe=ff4adb2f7d) | Jul 20, 2022 |
| Sony          | VPCEA3M1R                   | Notebook    | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [3e417753cb](https://linux-hardware.org/?probe=3e417753cb) | Jul 16, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [24b5ba412b](https://linux-hardware.org/?probe=24b5ba412b) | Jul 16, 2022 |
| HP            | 871B                        | All in one  | [eb4b572a21](https://linux-hardware.org/?probe=eb4b572a21) | Jul 13, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [67182580cc](https://linux-hardware.org/?probe=67182580cc) | Jul 10, 2022 |
| HP            | ProBook 645 G3              | Notebook    | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [4e6539bf57](https://linux-hardware.org/?probe=4e6539bf57) | Jul 01, 2022 |
| Acer          | Aspire A315-55KG            | Notebook    | [223d853d4e](https://linux-hardware.org/?probe=223d853d4e) | Jun 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7877597b47](https://linux-hardware.org/?probe=7877597b47) | Jun 28, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [4b4944017c](https://linux-hardware.org/?probe=4b4944017c) | Jun 25, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [83c0821672](https://linux-hardware.org/?probe=83c0821672) | Jun 25, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [822554f0be](https://linux-hardware.org/?probe=822554f0be) | Jun 23, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [3ddae75872](https://linux-hardware.org/?probe=3ddae75872) | Jun 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [47b04cd99f](https://linux-hardware.org/?probe=47b04cd99f) | Jun 21, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [6b7dd54165](https://linux-hardware.org/?probe=6b7dd54165) | Jun 13, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Lenovo        | ThinkPad T430 2349NM8       | Notebook    | [44e08ed5c6](https://linux-hardware.org/?probe=44e08ed5c6) | Jun 04, 2022 |
| MSI           | G41M-SP20                   | Desktop     | [214a83fb6b](https://linux-hardware.org/?probe=214a83fb6b) | Jun 04, 2022 |
| Foxconn       | H77M/H77M-S                 | Desktop     | [eb5f9f873a](https://linux-hardware.org/?probe=eb5f9f873a) | Jun 03, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3709bf11a9](https://linux-hardware.org/?probe=3709bf11a9) | Jun 01, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [58566ab4b6](https://linux-hardware.org/?probe=58566ab4b6) | May 30, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [2540080e55](https://linux-hardware.org/?probe=2540080e55) | May 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9c2c8025ed](https://linux-hardware.org/?probe=9c2c8025ed) | May 26, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [e04f02de57](https://linux-hardware.org/?probe=e04f02de57) | May 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d0d6870830](https://linux-hardware.org/?probe=d0d6870830) | May 23, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [eb1685b47e](https://linux-hardware.org/?probe=eb1685b47e) | May 22, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [910cae5e1e](https://linux-hardware.org/?probe=910cae5e1e) | May 21, 2022 |
| IBM           | ThinkPad T43 2668F5G        | Notebook    | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [5f3fea62ab](https://linux-hardware.org/?probe=5f3fea62ab) | May 16, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [d60d62217c](https://linux-hardware.org/?probe=d60d62217c) | May 10, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [1c49000609](https://linux-hardware.org/?probe=1c49000609) | May 09, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [f115d870eb](https://linux-hardware.org/?probe=f115d870eb) | May 07, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [7e229f1bb3](https://linux-hardware.org/?probe=7e229f1bb3) | May 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [62b044e6e7](https://linux-hardware.org/?probe=62b044e6e7) | Apr 29, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [f7290e5680](https://linux-hardware.org/?probe=f7290e5680) | Apr 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [f0f822fa1b](https://linux-hardware.org/?probe=f0f822fa1b) | Apr 25, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [0ca4241f02](https://linux-hardware.org/?probe=0ca4241f02) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [0324fe4cc6](https://linux-hardware.org/?probe=0324fe4cc6) | Apr 23, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [37a57a968f](https://linux-hardware.org/?probe=37a57a968f) | Apr 19, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [5f4832051e](https://linux-hardware.org/?probe=5f4832051e) | Apr 14, 2022 |
| ASRock        | B250 Pro4                   | Desktop     | [cb77fb75b5](https://linux-hardware.org/?probe=cb77fb75b5) | Apr 14, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [ef0b36db62](https://linux-hardware.org/?probe=ef0b36db62) | Apr 11, 2022 |
| MSI           | MS-7365                     | Desktop     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | Desktop     | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| Dell          | Latitude 3520               | Notebook    | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| HP            | 0A08h                       | Desktop     | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [609849a9e7](https://linux-hardware.org/?probe=609849a9e7) | Apr 02, 2022 |
| MSI           | MS-7346                     | Desktop     | [207eda5f34](https://linux-hardware.org/?probe=207eda5f34) | Mar 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9acdb9482d](https://linux-hardware.org/?probe=9acdb9482d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d941ebafc6](https://linux-hardware.org/?probe=d941ebafc6) | Mar 28, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [27b65f8212](https://linux-hardware.org/?probe=27b65f8212) | Mar 23, 2022 |
| ASRock        | 890GX Extreme4              | Desktop     | [3c57e1ac31](https://linux-hardware.org/?probe=3c57e1ac31) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | Desktop     | [8c38c582bf](https://linux-hardware.org/?probe=8c38c582bf) | Mar 20, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [406c69d7cd](https://linux-hardware.org/?probe=406c69d7cd) | Mar 18, 2022 |
| MSI           | MS-7346                     | Desktop     | [2c94f0863d](https://linux-hardware.org/?probe=2c94f0863d) | Mar 16, 2022 |
| Dell          | 0V6XGW A01                  | Desktop     | [7b091c2035](https://linux-hardware.org/?probe=7b091c2035) | Mar 13, 2022 |
| MSI           | MS-7346                     | Desktop     | [0be963d491](https://linux-hardware.org/?probe=0be963d491) | Mar 13, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [59a21d0aa2](https://linux-hardware.org/?probe=59a21d0aa2) | Mar 11, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [6f53445c9d](https://linux-hardware.org/?probe=6f53445c9d) | Mar 05, 2022 |
| MSI           | MS-7346                     | Desktop     | [369821f3f9](https://linux-hardware.org/?probe=369821f3f9) | Feb 26, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [565ef5309f](https://linux-hardware.org/?probe=565ef5309f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [21e91da000](https://linux-hardware.org/?probe=21e91da000) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [38d5887ae2](https://linux-hardware.org/?probe=38d5887ae2) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| ECS           | G41T-R3                     | Desktop     | [ad4ba21957](https://linux-hardware.org/?probe=ad4ba21957) | Feb 13, 2022 |
| Lenovo        | ThinkPad T460 20FMS2TG0D    | Notebook    | [f51933de6d](https://linux-hardware.org/?probe=f51933de6d) | Feb 10, 2022 |
| Biostar       | H61MLV                      | Desktop     | [675b0c3faf](https://linux-hardware.org/?probe=675b0c3faf) | Feb 07, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [cd91d445e6](https://linux-hardware.org/?probe=cd91d445e6) | Jan 30, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [c1703ee8ee](https://linux-hardware.org/?probe=c1703ee8ee) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | Notebook    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a6a7106d83](https://linux-hardware.org/?probe=a6a7106d83) | Jan 26, 2022 |
| ASRock        | G31M-VS                     | Desktop     | [d456869dd7](https://linux-hardware.org/?probe=d456869dd7) | Jan 14, 2022 |
| Samsung       | N100SP                      | Notebook    | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| Acer          | Predator PO3-620            | Desktop     | [d33f608e2e](https://linux-hardware.org/?probe=d33f608e2e) | Dec 27, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| eMachines     | ET1850                      | Desktop     | [cffccff919](https://linux-hardware.org/?probe=cffccff919) | Dec 20, 2021 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [968b139684](https://linux-hardware.org/?probe=968b139684) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [b294d0719f](https://linux-hardware.org/?probe=b294d0719f) | Dec 14, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [38cf5730b3](https://linux-hardware.org/?probe=38cf5730b3) | Dec 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [4501078e9a](https://linux-hardware.org/?probe=4501078e9a) | Dec 08, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [985ed9e52c](https://linux-hardware.org/?probe=985ed9e52c) | Dec 05, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [16586b274a](https://linux-hardware.org/?probe=16586b274a) | Nov 20, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [83857e3215](https://linux-hardware.org/?probe=83857e3215) | Oct 29, 2021 |
| ASUSTek       | N56DP                       | Notebook    | [7332da68ec](https://linux-hardware.org/?probe=7332da68ec) | Oct 25, 2021 |
| Biostar       | H61MLV2                     | Desktop     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1c2a383c4f](https://linux-hardware.org/?probe=1c2a383c4f) | Oct 20, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e7abad8af5](https://linux-hardware.org/?probe=e7abad8af5) | Oct 20, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [10a67c9e23](https://linux-hardware.org/?probe=10a67c9e23) | Oct 16, 2021 |
| Acer          | Aspire A315-55KG            | Notebook    | [79534f4c8c](https://linux-hardware.org/?probe=79534f4c8c) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1103bd0a01](https://linux-hardware.org/?probe=1103bd0a01) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [008072f061](https://linux-hardware.org/?probe=008072f061) | Oct 05, 2021 |
| Athermiter... | X99 Beta vk.com/@2485616    | Desktop     | [6006da0a12](https://linux-hardware.org/?probe=6006da0a12) | Oct 01, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [79a5ef3dad](https://linux-hardware.org/?probe=79a5ef3dad) | Sep 22, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Lenovo        | ThinkPad T480 20L6SBGK00    | Notebook    | [fc6636e0b5](https://linux-hardware.org/?probe=fc6636e0b5) | Sep 09, 2021 |
| HP            | ProBook 4320s               | Notebook    | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [ea71d93f96](https://linux-hardware.org/?probe=ea71d93f96) | Aug 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [d35224de9f](https://linux-hardware.org/?probe=d35224de9f) | Aug 07, 2021 |
| HP            | Pavilion dm1                | Notebook    | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [d312398917](https://linux-hardware.org/?probe=d312398917) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | 635                         | Notebook    | [06f1ff97b5](https://linux-hardware.org/?probe=06f1ff97b5) | Jul 24, 2021 |
| Elenberg      | EL_T1011                    | Notebook    | [c2e05805b1](https://linux-hardware.org/?probe=c2e05805b1) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| HP            | 15                          | Notebook    | [fcc367258f](https://linux-hardware.org/?probe=fcc367258f) | Jul 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [b7fe3d0d08](https://linux-hardware.org/?probe=b7fe3d0d08) | Jul 16, 2021 |
| Lenovo        | ThinkPad T580 20L9S0D100    | Notebook    | [e7f9397916](https://linux-hardware.org/?probe=e7f9397916) | Jul 02, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [1d185733d4](https://linux-hardware.org/?probe=1d185733d4) | Jun 24, 2021 |
| Lenovo        | 0x36BF SDK0J40688 WIN 34... | All in one  | [5ee73859b3](https://linux-hardware.org/?probe=5ee73859b3) | Jun 21, 2021 |
| Lenovo        | 0x36BF SDK0J40688 WIN 34... | All in one  | [001cc3458f](https://linux-hardware.org/?probe=001cc3458f) | Jun 21, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [ad17a21f6e](https://linux-hardware.org/?probe=ad17a21f6e) | Jun 16, 2021 |
| Acer          | Mandolin                    | Notebook    | [c5a4b06851](https://linux-hardware.org/?probe=c5a4b06851) | Jun 13, 2021 |
| Biostar       | H81MHV3                     | Desktop     | [0a593d3966](https://linux-hardware.org/?probe=0a593d3966) | Jun 01, 2021 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | Notebook    | [6b37e8a34b](https://linux-hardware.org/?probe=6b37e8a34b) | May 25, 2021 |
| HP            | 8245 001                    | All in one  | [40434f824a](https://linux-hardware.org/?probe=40434f824a) | May 24, 2021 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1b292e7e77](https://linux-hardware.org/?probe=1b292e7e77) | May 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e74c6f6436](https://linux-hardware.org/?probe=e74c6f6436) | May 16, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [b79dcdb648](https://linux-hardware.org/?probe=b79dcdb648) | May 03, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [b02527f8e5](https://linux-hardware.org/?probe=b02527f8e5) | May 03, 2021 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [8cf2183901](https://linux-hardware.org/?probe=8cf2183901) | May 03, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1a6e48b6a6](https://linux-hardware.org/?probe=1a6e48b6a6) | Apr 29, 2021 |
| MSI           | P55-GD65                    | Desktop     | [773fc40103](https://linux-hardware.org/?probe=773fc40103) | Apr 24, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [b4f123b6df](https://linux-hardware.org/?probe=b4f123b6df) | Apr 20, 2021 |
| Acer          | AO722                       | Notebook    | [6d09f4a364](https://linux-hardware.org/?probe=6d09f4a364) | Apr 20, 2021 |
| ASUSTek       | X550LA                      | Notebook    | [69647941af](https://linux-hardware.org/?probe=69647941af) | Apr 20, 2021 |
| Acer          | AOHAPPY2                    | Notebook    | [1ab9a823ac](https://linux-hardware.org/?probe=1ab9a823ac) | Apr 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [895cfbdea8](https://linux-hardware.org/?probe=895cfbdea8) | Mar 31, 2021 |
| HP            | ENVY m6                     | Notebook    | [1f794c0fc3](https://linux-hardware.org/?probe=1f794c0fc3) | Mar 29, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [324235179d](https://linux-hardware.org/?probe=324235179d) | Mar 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e373906f4c](https://linux-hardware.org/?probe=e373906f4c) | Mar 17, 2021 |
| ASUSTek       | S301LA                      | Notebook    | [c8c4934145](https://linux-hardware.org/?probe=c8c4934145) | Mar 17, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af8d6ec07e](https://linux-hardware.org/?probe=af8d6ec07e) | Mar 17, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [003b473b29](https://linux-hardware.org/?probe=003b473b29) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| Acer          | Predator PH317-54           | Notebook    | [0e97801264](https://linux-hardware.org/?probe=0e97801264) | Mar 12, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c58e02d129](https://linux-hardware.org/?probe=c58e02d129) | Mar 07, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [d08f840a09](https://linux-hardware.org/?probe=d08f840a09) | Mar 07, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [676848c0ea](https://linux-hardware.org/?probe=676848c0ea) | Mar 01, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [4e22c88014](https://linux-hardware.org/?probe=4e22c88014) | Feb 18, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [7b39e6bd46](https://linux-hardware.org/?probe=7b39e6bd46) | Feb 15, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [19b6410050](https://linux-hardware.org/?probe=19b6410050) | Feb 12, 2021 |
| Unknown       | Unknown                     | Soc         | [15a8630182](https://linux-hardware.org/?probe=15a8630182) | Feb 06, 2021 |
| Sony          | VGN-NR430E                  | Notebook    | [62beb0a340](https://linux-hardware.org/?probe=62beb0a340) | Feb 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Kazakhstan/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R8.1                    | 56        | 6.91%   |
| ROSA R10                     | 56        | 6.91%   |
| ROSA R11                     | 51        | 6.3%    |
| ROSA R9                      | 31        | 3.83%   |
| Arch Rolling                 | 29        | 3.58%   |
| Ubuntu 22.04                 | 26        | 3.21%   |
| ROSA R11.1                   | 25        | 3.09%   |
| Ubuntu 20.04                 | 24        | 2.96%   |
| ROSA R8                      | 22        | 2.72%   |
| Ubuntu 24.04                 | 20        | 2.47%   |
| Debian 11                    | 19        | 2.35%   |
| Debian 12                    | 17        | 2.1%    |
| ROSA 12.4                    | 16        | 1.98%   |
| ROSA 12.2                    | 14        | 1.73%   |
| ROSA 12.5.1                  | 12        | 1.48%   |
| Ubuntu 18.04                 | 11        | 1.36%   |
| KDE neon 20.04               | 11        | 1.36%   |
| OpenMandriva 4.2             | 10        | 1.23%   |
| ROSA 12.3                    | 9         | 1.11%   |
| OpenMandriva 24.07           | 9         | 1.11%   |
| Fedora 39                    | 8         | 0.99%   |
| ROSA 13.0                    | 7         | 0.86%   |
| OpenMandriva 5.0             | 7         | 0.86%   |
| OpenMandriva 4.3             | 7         | 0.86%   |
| OpenMandriva 23.08           | 7         | 0.86%   |
| KDE neon 22.04               | 7         | 0.86%   |
| Slackware 15.0               | 6         | 0.74%   |
| OpenMandriva 25.90           | 6         | 0.74%   |
| Manjaro                      | 6         | 0.74%   |
| Fedora 38                    | 6         | 0.74%   |
| EndeavourOS Rolling          | 6         | 0.74%   |
| Pop!_OS 22.04                | 5         | 0.62%   |
| OpenMandriva 23.01           | 5         | 0.62%   |
| Fedora 40                    | 5         | 0.62%   |
| Debian 13                    | 5         | 0.62%   |
| Arch                         | 5         | 0.62%   |
| Ubuntu 23.10                 | 4         | 0.49%   |
| Ubuntu 23.04                 | 4         | 0.49%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.49%   |
| OpenMandriva 23.03           | 4         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| ROSA         | 278       | 36.92%  |
| Ubuntu       | 95        | 12.62%  |
| OpenMandriva | 67        | 8.9%    |
| Debian       | 42        | 5.58%   |
| Fedora       | 40        | 5.31%   |
| Arch         | 32        | 4.25%   |
| Linux Mint   | 27        | 3.59%   |
| Manjaro      | 24        | 3.19%   |
| KDE neon     | 21        | 2.79%   |
| Endless      | 18        | 2.39%   |
| Kubuntu      | 15        | 1.99%   |
| Pop!_OS      | 9         | 1.2%    |
| openSUSE     | 7         | 0.93%   |
| Slackware    | 6         | 0.8%    |
| EndeavourOS  | 6         | 0.8%    |
| Elementary   | 5         | 0.66%   |
| CentOS       | 5         | 0.66%   |
| SteamOS      | 4         | 0.53%   |
| NixOS        | 4         | 0.53%   |
| Zorin        | 3         | 0.4%    |
| Xubuntu      | 3         | 0.4%    |
| Nobara       | 3         | 0.4%    |
| Lubuntu      | 3         | 0.4%    |
| LMDE         | 3         | 0.4%    |
| Gentoo       | 3         | 0.4%    |
| ALT Linux    | 3         | 0.4%    |
| Ubuntu Unity | 2         | 0.27%   |
| Rocky Linux  | 2         | 0.27%   |
| Lunaos       | 2         | 0.27%   |
| Kali         | 2         | 0.27%   |
| Clear Linux  | 2         | 0.27%   |
| CachyOS      | 2         | 0.27%   |
| ArcoLinux    | 2         | 0.27%   |
| Ubuntu MATE  | 1         | 0.13%   |
| Trisquel     | 1         | 0.13%   |
| Solus        | 1         | 0.13%   |
| Peppermint   | 1         | 0.13%   |
| Parrot       | 1         | 0.13%   |
| Oracle Linux | 1         | 0.13%   |
| MX           | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-desktop-45.1rosa-x86_64      | 29        | 3.31%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 27        | 3.08%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 24        | 2.74%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 14        | 1.6%    |
| 5.10.74-generic-2rosa2021.1-x86_64  | 12        | 1.37%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 11        | 1.25%   |
| 6.14.2-desktop-3omv2590             | 10        | 1.14%   |
| 5.10.14-desktop-1omv4002            | 10        | 1.14%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 10        | 1.14%   |
| 6.6.27-generic-3rosa2021.1-x86_64   | 9         | 1.03%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 9         | 1.03%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 9         | 1.03%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 9         | 1.03%   |
| 6.6.2-desktop-1omv2390              | 8         | 0.91%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 8         | 0.91%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 8         | 0.91%   |
| 6.4.11-desktop-1omv2390             | 7         | 0.8%    |
| 6.1.20-generic-2rosa2021.1-x86_64   | 7         | 0.8%    |
| 5.16.7-desktop-1omv4003             | 7         | 0.8%    |
| 4.1.34-nrj-desktop-2rosa-i586       | 7         | 0.8%    |
| 6.8.0-49-generic                    | 6         | 0.68%   |
| 6.10.0-desktop-1omv2490             | 6         | 0.68%   |
| 5.4.32-generic-2rosa-x86_64         | 6         | 0.68%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 6         | 0.68%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 6         | 0.68%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 6         | 0.68%   |
| 4.15.0-desktop-45.1rosa-i586        | 6         | 0.68%   |
| 6.1.1-desktop-1omv2290              | 5         | 0.57%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 5         | 0.57%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 5         | 0.57%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 5         | 0.57%   |
| 6.8.0-51-generic                    | 4         | 0.46%   |
| 6.8.0-40-generic                    | 4         | 0.46%   |
| 6.2.6-desktop-1omv2390              | 4         | 0.46%   |
| 6.1.58-generic-1rosa2021.1-x86_64   | 4         | 0.46%   |
| 5.4.83-generic-2rosa-x86_64         | 4         | 0.46%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 4         | 0.46%   |
| 5.15.19                             | 4         | 0.46%   |
| 5.10.0-8-amd64                      | 4         | 0.46%   |
| 5.10.0-21-amd64                     | 4         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 64        | 7.39%   |
| 4.9.60  | 35        | 4.04%   |
| 4.9.20  | 33        | 3.81%   |
| 5.4.0   | 30        | 3.46%   |
| 6.8.0   | 25        | 2.89%   |
| 5.15.0  | 25        | 2.89%   |
| 5.10.0  | 18        | 2.08%   |
| 4.9.9   | 17        | 1.96%   |
| 4.1.38  | 17        | 1.96%   |
| 4.1.34  | 17        | 1.96%   |
| 6.1.0   | 16        | 1.85%   |
| 6.5.0   | 14        | 1.62%   |
| 6.2.0   | 13        | 1.5%    |
| 5.11.0  | 12        | 1.39%   |
| 5.10.74 | 12        | 1.39%   |
| 6.6.2   | 11        | 1.27%   |
| 4.9.155 | 11        | 1.27%   |
| 6.14.2  | 10        | 1.15%   |
| 5.10.14 | 10        | 1.15%   |
| 6.6.27  | 9         | 1.04%   |
| 5.19.0  | 9         | 1.04%   |
| 5.0.0   | 9         | 1.04%   |
| 4.9.124 | 9         | 1.04%   |
| 5.4.32  | 8         | 0.92%   |
| 5.3.0   | 8         | 0.92%   |
| 5.16.7  | 8         | 0.92%   |
| 6.4.11  | 7         | 0.81%   |
| 6.1.20  | 7         | 0.81%   |
| 5.13.0  | 7         | 0.81%   |
| 4.9.76  | 7         | 0.81%   |
| 4.9.41  | 7         | 0.81%   |
| 4.9.111 | 7         | 0.81%   |
| 4.18.0  | 7         | 0.81%   |
| 6.14.0  | 6         | 0.69%   |
| 6.11.0  | 6         | 0.69%   |
| 6.10.0  | 6         | 0.69%   |
| 6.1.1   | 6         | 0.69%   |
| 5.8.0   | 6         | 0.69%   |
| 6.9.7   | 5         | 0.58%   |
| 6.2.6   | 5         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 121       | 14.76%  |
| 4.15    | 64        | 7.8%    |
| 5.10    | 51        | 6.22%   |
| 6.1     | 50        | 6.1%    |
| 5.4     | 47        | 5.73%   |
| 5.15    | 45        | 5.49%   |
| 6.6     | 41        | 5%      |
| 4.1     | 37        | 4.51%   |
| 6.8     | 35        | 4.27%   |
| 6.5     | 25        | 3.05%   |
| 6.2     | 24        | 2.93%   |
| 6.12    | 23        | 2.8%    |
| 6.14    | 20        | 2.44%   |
| 6.11    | 16        | 1.95%   |
| 6.4     | 13        | 1.59%   |
| 5.8     | 13        | 1.59%   |
| 5.19    | 13        | 1.59%   |
| 6.9     | 12        | 1.46%   |
| 6.10    | 12        | 1.46%   |
| 5.11    | 12        | 1.46%   |
| 4.18    | 12        | 1.46%   |
| 5.0     | 10        | 1.22%   |
| 5.3     | 9         | 1.1%    |
| 5.16    | 9         | 1.1%    |
| 5.14    | 9         | 1.1%    |
| 5.13    | 9         | 1.1%    |
| 6.7     | 8         | 0.98%   |
| 6.17    | 8         | 0.98%   |
| 6.3     | 7         | 0.85%   |
| 6.0     | 7         | 0.85%   |
| 4.19    | 7         | 0.85%   |
| 5.17    | 6         | 0.73%   |
| 6.13    | 4         | 0.49%   |
| 5.18    | 4         | 0.49%   |
| 4.13    | 4         | 0.49%   |
| 5.9     | 3         | 0.37%   |
| 2.6     | 3         | 0.37%   |
| 6.16    | 2         | 0.24%   |
| 6.15    | 2         | 0.24%   |
| 5.7     | 2         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 665       | 91.1%   |
| i686    | 60        | 8.22%   |
| aarch64 | 3         | 0.41%   |
| armv7l  | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 191       | 24.77%  |
| KDE4             | 177       | 22.96%  |
| KDE5             | 175       | 22.7%   |
| Unknown          | 46        | 5.97%   |
| KDE6             | 42        | 5.45%   |
| XFCE             | 32        | 4.15%   |
| X-Cinnamon       | 25        | 3.24%   |
| KDE              | 22        | 2.85%   |
| LXQt             | 18        | 2.33%   |
| MATE             | 7         | 0.91%   |
| LXDE             | 7         | 0.91%   |
| Cinnamon         | 6         | 0.78%   |
| Pantheon         | 4         | 0.52%   |
| Hyprland         | 4         | 0.52%   |
| i3               | 3         | 0.39%   |
| Unity            | 2         | 0.26%   |
| sway             | 2         | 0.26%   |
| GNOME Classic    | 2         | 0.26%   |
| COSMIC           | 2         | 0.26%   |
| Openbox          | 1         | 0.13%   |
| lightdm-xsession | 1         | 0.13%   |
| GNOME Flashback  | 1         | 0.13%   |
| awesome          | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 523       | 69.46%  |
| Wayland | 199       | 26.43%  |
| Unknown | 19        | 2.52%   |
| Tty     | 12        | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| SDDM           | 219       | 28.52%  |
| KDM            | 178       | 23.18%  |
| Unknown        | 165       | 21.48%  |
| GDM            | 77        | 10.03%  |
| GDM3           | 64        | 8.33%   |
| LightDM        | 51        | 6.64%   |
| TDM            | 10        | 1.3%    |
| XDM            | 1         | 0.13%   |
| SLiM           | 1         | 0.13%   |
| GREETD         | 1         | 0.13%   |
| COSMIC-GREETER | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ru_RU       | 275       | 36.38%  |
| Unknown     | 237       | 31.35%  |
| en_US       | 213       | 28.17%  |
| C           | 11        | 1.46%   |
| en_GB       | 7         | 0.93%   |
| ru_RU.UTF_8 | 4         | 0.53%   |
| tr_TR       | 2         | 0.26%   |
| ru_KZ       | 2         | 0.26%   |
| kk_KZ       | 1         | 0.13%   |
| en_IN       | 1         | 0.13%   |
| en_IL       | 1         | 0.13%   |
| en_BW       | 1         | 0.13%   |
| de_DE       | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 393       | 53.11%  |
| EFI  | 347       | 46.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 445       | 58.55%  |
| Unknown | 145       | 19.08%  |
| Btrfs   | 79        | 10.39%  |
| Overlay | 62        | 8.16%   |
| Tmpfs   | 16        | 2.11%   |
| Xfs     | 7         | 0.92%   |
| Ext3    | 3         | 0.39%   |
| Zfs     | 2         | 0.26%   |
| F2fs    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 323       | 43.24%  |
| Unknown | 218       | 29.18%  |
| MBR     | 206       | 27.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 631       | 84.36%  |
| Yes       | 117       | 15.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 502       | 66.76%  |
| Yes       | 250       | 33.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 146       | 20.19%  |
| Lenovo                     | 102       | 14.11%  |
| Hewlett-Packard            | 88        | 12.17%  |
| Acer                       | 67        | 9.27%   |
| Gigabyte Technology        | 61        | 8.44%   |
| ASRock                     | 45        | 6.22%   |
| Dell                       | 35        | 4.84%   |
| MSI                        | 25        | 3.46%   |
| Intel                      | 19        | 2.63%   |
| ECS                        | 14        | 1.94%   |
| Unknown                    | 13        | 1.8%    |
| Foxconn                    | 10        | 1.38%   |
| Biostar                    | 10        | 1.38%   |
| Toshiba                    | 7         | 0.97%   |
| Sony                       | 7         | 0.97%   |
| Samsung Electronics        | 7         | 0.97%   |
| Fujitsu                    | 6         | 0.83%   |
| HUAWEI                     | 5         | 0.69%   |
| Fujitsu Siemens            | 5         | 0.69%   |
| Packard Bell               | 4         | 0.55%   |
| Chuwi                      | 4         | 0.55%   |
| Valve                      | 3         | 0.41%   |
| Huanan                     | 3         | 0.41%   |
| Supermicro                 | 2         | 0.28%   |
| OEM                        | 2         | 0.28%   |
| HPE                        | 2         | 0.28%   |
| HONOR                      | 2         | 0.28%   |
| eMachines                  | 2         | 0.28%   |
| AMI                        | 2         | 0.28%   |
| Acidanthera                | 2         | 0.28%   |
| YiFang                     | 1         | 0.14%   |
| XIAOMI                     | 1         | 0.14%   |
| Timi                       | 1         | 0.14%   |
| TI                         | 1         | 0.14%   |
| Shenzhen WEIBU Information | 1         | 0.14%   |
| Sapphire                   | 1         | 0.14%   |
| Rockchip                   | 1         | 0.14%   |
| Quanta                     | 1         | 0.14%   |
| PIPO                       | 1         | 0.14%   |
| Maibenben                  | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 17        | 2.35%   |
| ASUS All Series                          | 10        | 1.38%   |
| Lenovo G500 20236                        | 9         | 1.24%   |
| HP Pavilion g6                           | 5         | 0.69%   |
| Acer Aspire E5-575G                      | 5         | 0.69%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 4         | 0.55%   |
| Gigabyte P35-DS3L                        | 4         | 0.55%   |
| Acer Aspire 5750G                        | 4         | 0.55%   |
| Valve Jupiter                            | 3         | 0.41%   |
| Packard Bell DOT S                       | 3         | 0.41%   |
| Lenovo G510 20238                        | 3         | 0.41%   |
| HP Pavilion dv6                          | 3         | 0.41%   |
| Gigabyte EP45-DS3L                       | 3         | 0.41%   |
| Fujitsu LIFEBOOK AH531                   | 3         | 0.41%   |
| ECS G31T-M7                              | 3         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X1505VA_X1505VA | 3         | 0.41%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR     | 3         | 0.41%   |
| ASUS P5G41-M LE                          | 3         | 0.41%   |
| ASUS H61M-K                              | 3         | 0.41%   |
| ASRock H61M-VG3                          | 3         | 0.41%   |
| MSI MS-7817                              | 2         | 0.28%   |
| MSI MS-7788                              | 2         | 0.28%   |
| MSI MS-7592                              | 2         | 0.28%   |
| MSI MS-7529                              | 2         | 0.28%   |
| MSI MS-7519                              | 2         | 0.28%   |
| Lenovo ThinkPad Edge E530 3259CEG        | 2         | 0.28%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 2         | 0.28%   |
| Lenovo ThinkBook 14 G2 ITL 20VD          | 2         | 0.28%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 2         | 0.28%   |
| Lenovo Legion 5 15IAH7H 82RB             | 2         | 0.28%   |
| Lenovo IdeaPad Z570 HuronRiver Platform  | 2         | 0.28%   |
| Lenovo G505s 20255                       | 2         | 0.28%   |
| Intel DH61WW AAG23116-204                | 2         | 0.28%   |
| HP Victus by Laptop 16-e0xxx             | 2         | 0.28%   |
| HP ProLiant DL360 G5                     | 2         | 0.28%   |
| HP Presario CQ57                         | 2         | 0.28%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 2         | 0.28%   |
| HP Laptop 15s-eq2xxx                     | 2         | 0.28%   |
| HP ENVY x360 Convertible 15-eu0xxx       | 2         | 0.28%   |
| HP Compaq CQ58                           | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 39        | 5.39%   |
| ASUS VivoBook      | 30        | 4.15%   |
| Lenovo IdeaPad     | 27        | 3.73%   |
| HP Pavilion        | 20        | 2.77%   |
| Dell Inspiron      | 18        | 2.49%   |
| Unknown            | 17        | 2.35%   |
| Lenovo ThinkPad    | 16        | 2.21%   |
| ASUS ROG           | 14        | 1.94%   |
| Lenovo Legion      | 13        | 1.8%    |
| HP ProBook         | 11        | 1.52%   |
| ASUS ASUS          | 11        | 1.52%   |
| Acer Nitro         | 11        | 1.52%   |
| HP Laptop          | 10        | 1.38%   |
| ASUS All           | 10        | 1.38%   |
| Lenovo G500        | 9         | 1.24%   |
| HP Compaq          | 9         | 1.24%   |
| ASUS PRIME         | 9         | 1.24%   |
| Lenovo ThinkBook   | 8         | 1.11%   |
| HP ENVY            | 7         | 0.97%   |
| Dell Latitude      | 7         | 0.97%   |
| HP EliteBook       | 6         | 0.83%   |
| Fujitsu LIFEBOOK   | 5         | 0.69%   |
| Acer Swift         | 5         | 0.69%   |
| Toshiba Satellite  | 4         | 0.55%   |
| Gigabyte P35-DS3L  | 4         | 0.55%   |
| ASUS P8H61-M       | 4         | 0.55%   |
| Acer Predator      | 4         | 0.55%   |
| Valve Jupiter      | 3         | 0.41%   |
| Packard Bell DOT   | 3         | 0.41%   |
| Lenovo ThinkCentre | 3         | 0.41%   |
| Lenovo IdeaCentre  | 3         | 0.41%   |
| Lenovo G510        | 3         | 0.41%   |
| HP Victus          | 3         | 0.41%   |
| Gigabyte EP45-DS3L | 3         | 0.41%   |
| Foxconn G31MXP     | 3         | 0.41%   |
| ECS G31T-M7        | 3         | 0.41%   |
| Dell Vostro        | 3         | 0.41%   |
| ASUS Zenbook       | 3         | 0.41%   |
| ASUS TUF           | 3         | 0.41%   |
| ASUS P5G41-M       | 3         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 76        | 10.51%  |
| 2011    | 68        | 9.41%   |
| 2013    | 54        | 7.47%   |
| 2021    | 50        | 6.92%   |
| 2022    | 42        | 5.81%   |
| 2020    | 42        | 5.81%   |
| 2019    | 40        | 5.53%   |
| 2009    | 39        | 5.39%   |
| 2008    | 39        | 5.39%   |
| 2018    | 36        | 4.98%   |
| 2017    | 35        | 4.84%   |
| 2016    | 34        | 4.7%    |
| 2023    | 33        | 4.56%   |
| 2010    | 29        | 4.01%   |
| 2007    | 26        | 3.6%    |
| 2015    | 21        | 2.9%    |
| 2014    | 20        | 2.77%   |
| 2024    | 14        | 1.94%   |
| 2006    | 8         | 1.11%   |
| Unknown | 6         | 0.83%   |
| 2005    | 5         | 0.69%   |
| 2025    | 4         | 0.55%   |
| 2003    | 2         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 411       | 56.85%  |
| Desktop        | 278       | 38.45%  |
| All in one     | 10        | 1.38%   |
| Server         | 7         | 0.97%   |
| Mini pc        | 6         | 0.83%   |
| System on chip | 4         | 0.55%   |
| Convertible    | 4         | 0.55%   |
| Tablet         | 3         | 0.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 692       | 95.32%  |
| Enabled  | 34        | 4.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 722       | 99.86%  |
| Yes  | 1         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 169       | 22.78%  |
| 4.01-8.0        | 152       | 20.49%  |
| 8.01-16.0       | 135       | 18.19%  |
| 16.01-24.0      | 119       | 16.04%  |
| 32.01-64.0      | 49        | 6.6%    |
| 1.01-2.0        | 44        | 5.93%   |
| 2.01-3.0        | 29        | 3.91%   |
| 64.01-256.0     | 18        | 2.43%   |
| 24.01-32.0      | 13        | 1.75%   |
| 0.51-1.0        | 10        | 1.35%   |
| More than 256.0 | 2         | 0.27%   |
| 0.01-0.5        | 1         | 0.13%   |
| Unknown         | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 269       | 33.21%  |
| 0.51-1.0        | 156       | 19.26%  |
| 2.01-3.0        | 148       | 18.27%  |
| 4.01-8.0        | 97        | 11.98%  |
| 3.01-4.0        | 81        | 10%     |
| 8.01-16.0       | 37        | 4.57%   |
| 0.01-0.5        | 12        | 1.48%   |
| Unknown         | 4         | 0.49%   |
| 16.01-24.0      | 3         | 0.37%   |
| More than 256.0 | 1         | 0.12%   |
| 32.01-64.0      | 1         | 0.12%   |
| 64.01-256.0     | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 460       | 61.17%  |
| 2      | 192       | 25.53%  |
| 3      | 61        | 8.11%   |
| 4      | 20        | 2.66%   |
| 5      | 9         | 1.2%    |
| 0      | 5         | 0.66%   |
| 6      | 3         | 0.4%    |
| 27     | 1         | 0.13%   |
| 8      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 451       | 61.61%  |
| Yes       | 281       | 38.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 656       | 90.61%  |
| No        | 68        | 9.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 506       | 69.6%   |
| No        | 221       | 30.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 402       | 54.92%  |
| No        | 330       | 45.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Kazakhstan | 723       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Almaty          | 235       | 29.49%  |
| Nur-Sultan      | 78        | 9.79%   |
| Astana          | 60        | 7.53%   |
| Kostanay        | 48        | 6.02%   |
| Karaganda       | 43        | 5.4%    |
| Aktobe          | 38        | 4.77%   |
| Ust-Kamenogorsk | 36        | 4.52%   |
| Pavlodar        | 33        | 4.14%   |
| Taraz           | 27        | 3.39%   |
| Petropavl       | 18        | 2.26%   |
| Shymkent        | 15        | 1.88%   |
| Semey           | 15        | 1.88%   |
| Aktau           | 15        | 1.88%   |
| Kyzylorda       | 14        | 1.76%   |
| Atyrau          | 14        | 1.76%   |
| Rudnyy          | 13        | 1.63%   |
| Oral            | 11        | 1.38%   |
| Kokshetau       | 9         | 1.13%   |
| Temirtau        | 8         | 1%      |
| Ridder          | 8         | 1%      |
| Komsomol'skoe   | 6         | 0.75%   |
| Ekibastuz       | 6         | 0.75%   |
| Taldykorgan     | 4         | 0.5%    |
| Almaty Oblysy   | 4         | 0.5%    |
| Soran           | 3         | 0.38%   |
| Shchūchīnsk   | 3         | 0.38%   |
| Dzhezkazgan     | 3         | 0.38%   |
| Balqash         | 3         | 0.38%   |
| Tekeli          | 2         | 0.25%   |
| Taiynsha        | 2         | 0.25%   |
| Stepnogorsk     | 2         | 0.25%   |
| Sarkand         | 2         | 0.25%   |
| Makhambet       | 2         | 0.25%   |
| Zhezqazghan     | 1         | 0.13%   |
| Urzhar          | 1         | 0.13%   |
| Tobol           | 1         | 0.13%   |
| Shiyeli         | 1         | 0.13%   |
| Shemonaīkha    | 1         | 0.13%   |
| Satbayev        | 1         | 0.13%   |
| Līsakovsk      | 1         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 201       | 313    | 19.11%  |
| WDC                         | 135       | 189    | 12.83%  |
| Samsung Electronics         | 114       | 167    | 10.84%  |
| Toshiba                     | 90        | 135    | 8.56%   |
| Kingston                    | 78        | 154    | 7.41%   |
| Hitachi                     | 39        | 57     | 3.71%   |
| Unknown                     | 31        | 39     | 2.95%   |
| SanDisk                     | 31        | 32     | 2.95%   |
| Micron Technology           | 27        | 39     | 2.57%   |
| SK hynix                    | 24        | 29     | 2.28%   |
| Intel                       | 23        | 28     | 2.19%   |
| Transcend                   | 20        | 26     | 1.9%    |
| HGST                        | 19        | 21     | 1.81%   |
| Apacer                      | 18        | 25     | 1.71%   |
| Team                        | 12        | 14     | 1.14%   |
| A-DATA Technology           | 11        | 14     | 1.05%   |
| KIOXIA                      | 10        | 13     | 0.95%   |
| Kingston Technology Company | 10        | 14     | 0.95%   |
| Gigabyte Technology         | 10        | 11     | 0.95%   |
| Patriot                     | 9         | 10     | 0.86%   |
| Netac                       | 9         | 14     | 0.86%   |
| GeIL                        | 9         | 10     | 0.86%   |
| Plextor                     | 8         | 8      | 0.76%   |
| China                       | 8         | 8      | 0.76%   |
| KingSpec                    | 7         | 14     | 0.67%   |
| AMD                         | 7         | 7      | 0.67%   |
| Crucial                     | 5         | 5      | 0.48%   |
| ADATA Technology            | 5         | 6      | 0.48%   |
| Silicon Motion              | 4         | 4      | 0.38%   |
| MAXIO Technology (Hangzhou) | 4         | 4      | 0.38%   |
| Hikvision                   | 4         | 4      | 0.38%   |
| Fujitsu                     | 4         | 5      | 0.38%   |
| Unknown                     | 4         | 4      | 0.38%   |
| Phison Electronics          | 3         | 3      | 0.29%   |
| Phison                      | 3         | 3      | 0.29%   |
| HUAWEI                      | 3         | 3      | 0.29%   |
| Hewlett-Packard             | 3         | 14     | 0.29%   |
| SPCC                        | 2         | 2      | 0.19%   |
| OCZ                         | 2         | 2      | 0.19%   |
| KingDian                    | 2         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 19        | 1.68%   |
| Seagate ST500DM002-1BD142 500GB      | 16        | 1.42%   |
| Toshiba DT01ACA050 500GB             | 15        | 1.33%   |
| Kingston SA400S37480G 480GB SSD      | 15        | 1.33%   |
| Kingston SA400S37240G 240GB SSD      | 13        | 1.15%   |
| Toshiba HDWD110 1TB                  | 12        | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB       | 12        | 1.06%   |
| Seagate ST3500418AS 500GB            | 10        | 0.88%   |
| Toshiba MQ04ABF100 1TB               | 8         | 0.71%   |
| Toshiba MQ01ABD100 1TB               | 8         | 0.71%   |
| WDC WD5000AAKX-001CA0 500GB          | 7         | 0.62%   |
| Seagate ST3500413AS 500GB            | 7         | 0.62%   |
| Seagate ST3320620AS 320GB            | 7         | 0.62%   |
| Seagate ST3250310AS 250GB            | 7         | 0.62%   |
| Kingston SA400S37120G 120GB SSD      | 7         | 0.62%   |
| Intel SSDPEKNU512GZ 512GB            | 7         | 0.62%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 7         | 0.62%   |
| Toshiba MQ01ABF050 500GB             | 6         | 0.53%   |
| Toshiba DT01ACA100 1TB               | 6         | 0.53%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 6         | 0.53%   |
| SanDisk NVMe SSD Drive 512GB         | 6         | 0.53%   |
| HGST HTS541010A9E680 1TB             | 6         | 0.53%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 5         | 0.44%   |
| Toshiba DT01ACA200 2TB               | 5         | 0.44%   |
| Seagate ST9320325AS 320GB            | 5         | 0.44%   |
| Seagate ST3250318AS 250GB            | 5         | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB       | 5         | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB       | 5         | 0.44%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.44%   |
| Samsung HD502HJ 500GB                | 5         | 0.44%   |
| Patriot Burst 240GB SSD              | 5         | 0.44%   |
| Hitachi HTS547550A9E384 500GB        | 5         | 0.44%   |
| WDC WD10SPZX-21Z10T0 1TB             | 4         | 0.35%   |
| Unknown MMC Card  32GB               | 4         | 0.35%   |
| Transcend TS120GSSD220S 120GB        | 4         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 0.35%   |
| Seagate ST380011A 80GB               | 4         | 0.35%   |
| Seagate ST3320613AS 320GB            | 4         | 0.35%   |
| Seagate ST3250820AS 250GB            | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 199       | 310    | 37.98%  |
| WDC                 | 125       | 177    | 23.85%  |
| Toshiba             | 86        | 128    | 16.41%  |
| Samsung Electronics | 43        | 66     | 8.21%   |
| Hitachi             | 39        | 57     | 7.44%   |
| HGST                | 19        | 21     | 3.63%   |
| Fujitsu             | 4         | 5      | 0.76%   |
| Hewlett-Packard     | 3         | 14     | 0.57%   |
| Unknown             | 2         | 2      | 0.38%   |
| StoreJet            | 1         | 2      | 0.19%   |
| Maxtor              | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 1      | 0.19%   |
| HGST HTS            | 1         | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 60        | 126    | 23.26%  |
| Samsung Electronics | 26        | 37     | 10.08%  |
| Transcend           | 20        | 26     | 7.75%   |
| Apacer              | 17        | 24     | 6.59%   |
| Team                | 12        | 14     | 4.65%   |
| Gigabyte Technology | 10        | 11     | 3.88%   |
| SanDisk             | 9         | 9      | 3.49%   |
| Patriot             | 9         | 10     | 3.49%   |
| Plextor             | 8         | 8      | 3.1%    |
| China               | 8         | 8      | 3.1%    |
| Netac               | 7         | 12     | 2.71%   |
| KingSpec            | 7         | 14     | 2.71%   |
| AMD                 | 7         | 7      | 2.71%   |
| GeIL                | 6         | 7      | 2.33%   |
| Crucial             | 5         | 5      | 1.94%   |
| Intel               | 4         | 7      | 1.55%   |
| A-DATA Technology   | 4         | 5      | 1.55%   |
| WDC                 | 3         | 3      | 1.16%   |
| SK hynix            | 3         | 3      | 1.16%   |
| SPCC                | 2         | 2      | 0.78%   |
| OCZ                 | 2         | 2      | 0.78%   |
| Micron Technology   | 2         | 2      | 0.78%   |
| KingDian            | 2         | 2      | 0.78%   |
| Kingchuxing         | 2         | 4      | 0.78%   |
| HPE                 | 2         | 2      | 0.78%   |
| Verbatim            | 1         | 1      | 0.39%   |
| Unknown             | 1         | 1      | 0.39%   |
| TEKET               | 1         | 2      | 0.39%   |
| Smartbuy            | 1         | 1      | 0.39%   |
| Qumo                | 1         | 3      | 0.39%   |
| MG                  | 1         | 1      | 0.39%   |
| LVCARDS             | 1         | 1      | 0.39%   |
| Kingmax             | 1         | 1      | 0.39%   |
| KingFast            | 1         | 1      | 0.39%   |
| Kimtigo             | 1         | 1      | 0.39%   |
| HS-SSD-WAVE(N)      | 1         | 1      | 0.39%   |
| HS-SSD-E100N        | 1         | 1      | 0.39%   |
| HS-SSD-E100         | 1         | 1      | 0.39%   |
| Hikvision           | 1         | 1      | 0.39%   |
| GOODRAM             | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 442       | 785    | 47.89%  |
| SSD     | 223       | 375    | 24.16%  |
| NVMe    | 215       | 296    | 23.29%  |
| MMC     | 29        | 36     | 3.14%   |
| Unknown | 14        | 14     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 541       | 1129   | 66.79%  |
| NVMe | 215       | 295    | 26.54%  |
| MMC  | 29        | 36     | 3.58%   |
| SAS  | 25        | 46     | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 426       | 774    | 63.68%  |
| 0.51-1.0   | 194       | 287    | 29%     |
| 1.01-2.0   | 32        | 68     | 4.78%   |
| 4.01-10.0  | 7         | 20     | 1.05%   |
| 3.01-4.0   | 6         | 6      | 0.9%    |
| 2.01-3.0   | 4         | 5      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 188       | 23.5%   |
| 101-250        | 177       | 22.13%  |
| 501-1000       | 124       | 15.5%   |
| 1-20           | 91        | 11.38%  |
| 51-100         | 69        | 8.63%   |
| 1001-2000      | 57        | 7.13%   |
| 21-50          | 48        | 6%      |
| More than 3000 | 20        | 2.5%    |
| 2001-3000      | 13        | 1.63%   |
| Unknown        | 13        | 1.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 384       | 47.52%  |
| 21-50          | 110       | 13.61%  |
| 101-250        | 97        | 12%     |
| 51-100         | 76        | 9.41%   |
| 251-500        | 59        | 7.3%    |
| 501-1000       | 40        | 4.95%   |
| 1001-2000      | 20        | 2.48%   |
| Unknown        | 13        | 1.61%   |
| More than 3000 | 7         | 0.87%   |
| 2001-3000      | 2         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 9         | 12     | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB         | 5         | 5      | 2.42%   |
| Seagate ST3250310AS 250GB           | 5         | 5      | 2.42%   |
| Seagate ST3320613AS 320GB           | 4         | 4      | 1.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 1.93%   |
| Toshiba DT01ACA050 500GB            | 3         | 4      | 1.45%   |
| Seagate ST3802110A 80GB             | 3         | 4      | 1.45%   |
| Seagate ST3500418AS 500GB           | 3         | 6      | 1.45%   |
| Seagate ST3500413AS 500GB           | 3         | 3      | 1.45%   |
| Seagate ST3500320AS 500GB           | 3         | 3      | 1.45%   |
| Seagate ST3320620AS 320GB           | 3         | 6      | 1.45%   |
| Seagate ST3250820AS 250GB           | 3         | 3      | 1.45%   |
| Seagate ST3160215AS 160GB           | 3         | 3      | 1.45%   |
| Seagate ST1000DM003-9YN162 1TB      | 3         | 11     | 1.45%   |
| Samsung Electronics HD642JJ 640GB   | 3         | 5      | 1.45%   |
| Hitachi HTS547550A9E384 500GB       | 3         | 4      | 1.45%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 3      | 1.45%   |
| WDC WD800JD-60LSA0 80GB             | 2         | 2      | 0.97%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 2         | 4      | 0.97%   |
| WDC WD2000JS-60NCB1 200GB           | 2         | 3      | 0.97%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 0.97%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 0.97%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 0.97%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 0.97%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.97%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 9      | 0.97%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 4      | 0.97%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.97%   |
| Seagate ST380215AS 80GB             | 2         | 2      | 0.97%   |
| Seagate ST340014A 40GB              | 2         | 2      | 0.97%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 0.97%   |
| Seagate ST3160815AS 160GB           | 2         | 2      | 0.97%   |
| Samsung Electronics HM321HI 320GB   | 2         | 2      | 0.97%   |
| Samsung Electronics HD502HI 500GB   | 2         | 3      | 0.97%   |
| Hitachi HTS543216L9SA00 160GB       | 2         | 2      | 0.97%   |
| Hitachi HDP725016GLA380 160GB       | 2         | 3      | 0.97%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 0.97%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 0.97%   |
| Hewlett-Packard FB160C4081 160GB    | 2         | 2      | 0.97%   |
| China SSD 64GB                      | 2         | 2      | 0.97%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 84        | 121    | 42.42%  |
| WDC                 | 37        | 49     | 18.69%  |
| Hitachi             | 20        | 36     | 10.1%   |
| Toshiba             | 18        | 28     | 9.09%   |
| Samsung Electronics | 14        | 18     | 7.07%   |
| HGST                | 7         | 8      | 3.54%   |
| Kingston            | 3         | 3      | 1.52%   |
| Hewlett-Packard     | 2         | 2      | 1.01%   |
| China               | 2         | 2      | 1.01%   |
| ADATA Technology    | 2         | 2      | 1.01%   |
| Team                | 1         | 1      | 0.51%   |
| SK hynix            | 1         | 1      | 0.51%   |
| Plextor             | 1         | 1      | 0.51%   |
| Philips             | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| Maxtor              | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 4      | 0.51%   |
| Intel               | 1         | 1      | 0.51%   |
| AFOX                | 1         | 1      | 0.51%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 84        | 121    | 46.41%  |
| WDC                 | 37        | 49     | 20.44%  |
| Hitachi             | 20        | 36     | 11.05%  |
| Toshiba             | 18        | 28     | 9.94%   |
| Samsung Electronics | 12        | 16     | 6.63%   |
| HGST                | 7         | 8      | 3.87%   |
| Hewlett-Packard     | 2         | 2      | 1.1%    |
| Maxtor              | 1         | 1      | 0.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 163       | 261    | 90.56%  |
| SSD  | 12        | 15     | 6.67%   |
| NVMe | 5         | 5      | 2.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD322GJ 320GB                | 2         | 2      | 33.33%  |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 16.67%  |
| Seagate ST3250318AS 250GB                        | 1         | 2      | 16.67%  |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 16.67%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 50%     |
| Seagate             | 2         | 3      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 423       | 843    | 51.21%  |
| Detected | 223       | 375    | 27%     |
| Malfunc  | 174       | 281    | 21.07%  |
| Failed   | 6         | 7      | 0.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 542       | 60.02%  |
| AMD                           | 82        | 9.08%   |
| Samsung Electronics           | 51        | 5.65%   |
| Kingston Technology Company   | 28        | 3.1%    |
| SanDisk                       | 27        | 2.99%   |
| Micron Technology             | 25        | 2.77%   |
| JMicron Technology            | 24        | 2.66%   |
| SK hynix                      | 21        | 2.33%   |
| Marvell Technology Group      | 12        | 1.33%   |
| Nvidia                        | 10        | 1.11%   |
| KIOXIA                        | 9         | 1%      |
| ADATA Technology              | 9         | 1%      |
| Phison Electronics            | 7         | 0.78%   |
| MAXIO Technology (Hangzhou)   | 7         | 0.78%   |
| ASMedia Technology            | 7         | 0.78%   |
| Realtek Semiconductor         | 6         | 0.66%   |
| Toshiba America Info Systems  | 5         | 0.55%   |
| Silicon Motion                | 5         | 0.55%   |
| VIA Technologies              | 3         | 0.33%   |
| Solidigm                      | 3         | 0.33%   |
| Union Memory (Shenzhen)       | 2         | 0.22%   |
| Netac Technology              | 2         | 0.22%   |
| Integrated Technology Express | 2         | 0.22%   |
| Hewlett-Packard               | 2         | 0.22%   |
| Adaptec                       | 2         | 0.22%   |
| Yangtze Memory Technologies   | 1         | 0.11%   |
| ULi Electronics               | 1         | 0.11%   |
| Shenzhen Longsys Electronics  | 1         | 0.11%   |
| O2 Micro                      | 1         | 0.11%   |
| LSI Logic / Symbios Logic     | 1         | 0.11%   |
| Lite-On Technology            | 1         | 0.11%   |
| Lite-On IT Corp. / Plextor    | 1         | 0.11%   |
| INNOGRIT                      | 1         | 0.11%   |
| Biwin Storage Technology      | 1         | 0.11%   |
| Unknown                       | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 54        | 4.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 44        | 4.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 38        | 3.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 36        | 3.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 33        | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 28        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 28        | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 26        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 23        | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20        | 1.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 1.55%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 15        | 1.37%   |
| JMicron JMB368 IDE controller                                                           | 15        | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 14        | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 13        | 1.19%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 13        | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 1.1%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 11        | 1%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10        | 0.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 10        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 10        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 0.91%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 0.91%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                        | 9         | 0.82%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 9         | 0.82%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 9         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 9         | 0.82%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 9         | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8         | 0.73%   |
| Intel SSD 660P Series                                                                   | 8         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 8         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 459       | 51.34%  |
| NVMe | 215       | 24.05%  |
| IDE  | 157       | 17.56%  |
| RAID | 60        | 6.71%   |
| SAS  | 3         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 583       | 80.64%  |
| AMD     | 136       | 18.81%  |
| ARM     | 3         | 0.41%   |
| Unknown | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.38%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 8         | 1.1%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 0.83%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 0.83%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.83%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 0.83%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 5         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 5         | 0.69%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 5         | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.69%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 5         | 0.69%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 5         | 0.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 5         | 0.69%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 5         | 0.69%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 0.69%   |
| Intel 12th Gen Core i5-12500H                 | 5         | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.69%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.55%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.55%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 4         | 0.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 4         | 0.55%   |
| Intel 13th Gen Core i5-13500H                 | 4         | 0.55%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 4         | 0.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.55%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 3         | 0.41%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 3         | 0.41%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 3         | 0.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.41%   |
| Intel Pentium 4 CPU 3.00GHz                   | 3         | 0.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 141       | 19.45%  |
| Intel Core i7           | 80        | 11.03%  |
| Other                   | 78        | 10.76%  |
| Intel Core i3           | 72        | 9.93%   |
| Intel Celeron           | 45        | 6.21%   |
| Intel Core 2 Duo        | 40        | 5.52%   |
| AMD Ryzen 5             | 33        | 4.55%   |
| AMD Ryzen 7             | 32        | 4.41%   |
| Intel Pentium           | 31        | 4.28%   |
| Intel Xeon              | 24        | 3.31%   |
| Intel Pentium Dual-Core | 17        | 2.34%   |
| Intel Atom              | 17        | 2.34%   |
| AMD Ryzen 9             | 12        | 1.66%   |
| Intel Core 2 Quad       | 10        | 1.38%   |
| AMD Ryzen 3             | 7         | 0.97%   |
| Intel Pentium 4         | 6         | 0.83%   |
| Intel Pentium Dual      | 5         | 0.69%   |
| Intel Genuine           | 5         | 0.69%   |
| Intel Core 2            | 5         | 0.69%   |
| Intel Core              | 5         | 0.69%   |
| AMD E                   | 5         | 0.69%   |
| AMD A8                  | 5         | 0.69%   |
| AMD A4                  | 4         | 0.55%   |
| AMD A10                 | 4         | 0.55%   |
| Intel Pentium Gold      | 3         | 0.41%   |
| AMD Athlon II X2        | 3         | 0.41%   |
| AMD Athlon 64 X2        | 3         | 0.41%   |
| AMD A6                  | 3         | 0.41%   |
| Intel Xeon Silver       | 2         | 0.28%   |
| Intel Xeon Gold         | 2         | 0.28%   |
| Intel Pentium Silver    | 2         | 0.28%   |
| AMD Phenom II X4        | 2         | 0.28%   |
| AMD FX                  | 2         | 0.28%   |
| AMD E1                  | 2         | 0.28%   |
| Intel Pentium M         | 1         | 0.14%   |
| Intel Mobile Pentium 4  | 1         | 0.14%   |
| Intel Core m3           | 1         | 0.14%   |
| Intel Core i9           | 1         | 0.14%   |
| Intel Core Duo          | 1         | 0.14%   |
| Intel Core 2 Extreme    | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 307       | 42.23%  |
| 4       | 212       | 29.16%  |
| 6       | 54        | 7.43%   |
| 8       | 52        | 7.15%   |
| 1       | 21        | 2.89%   |
| Unknown | 21        | 2.89%   |
| 12      | 19        | 2.61%   |
| 10      | 15        | 2.06%   |
| 16      | 10        | 1.38%   |
| 14      | 5         | 0.69%   |
| 20      | 4         | 0.55%   |
| 24      | 3         | 0.41%   |
| 3       | 2         | 0.28%   |
| 36      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 711       | 98.34%  |
| 2       | 10        | 1.38%   |
| Unknown | 2         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 445       | 61.38%  |
| 1       | 259       | 35.72%  |
| Unknown | 21        | 2.9%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 701       | 96.96%  |
| Unknown        | 11        | 1.52%   |
| 32-bit         | 10        | 1.38%   |
| 64-bit         | 1         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 34.89%  |
| 0x306a9    | 54        | 7.19%   |
| 0x206a7    | 53        | 7.06%   |
| 0x1067a    | 44        | 5.86%   |
| 0x306c3    | 23        | 3.06%   |
| 0x806e9    | 14        | 1.86%   |
| 0x806c1    | 14        | 1.86%   |
| 0x906ea    | 12        | 1.6%    |
| 0x906e9    | 12        | 1.6%    |
| 0x6fd      | 11        | 1.46%   |
| 0x40651    | 10        | 1.33%   |
| 0x806ea    | 9         | 1.2%    |
| 0x20655    | 9         | 1.2%    |
| 0x10676    | 9         | 1.2%    |
| 0x06001119 | 9         | 1.2%    |
| 0x20652    | 8         | 1.07%   |
| 0x0a50000c | 8         | 1.07%   |
| 0x806ec    | 6         | 0.8%    |
| 0x706a1    | 6         | 0.8%    |
| 0x6fb      | 6         | 0.8%    |
| 0x406e3    | 6         | 0.8%    |
| 0x406c4    | 6         | 0.8%    |
| 0x30678    | 6         | 0.8%    |
| 0x08608103 | 6         | 0.8%    |
| 0xa0653    | 5         | 0.67%   |
| 0xa0652    | 5         | 0.67%   |
| 0x0a50000d | 5         | 0.67%   |
| 0x706e5    | 4         | 0.53%   |
| 0x30661    | 4         | 0.53%   |
| 0xf49      | 3         | 0.4%    |
| 0x906ed    | 3         | 0.4%    |
| 0x906a3    | 3         | 0.4%    |
| 0x6f6      | 3         | 0.4%    |
| 0x6e8      | 3         | 0.4%    |
| 0x506e3    | 3         | 0.4%    |
| 0x306d4    | 3         | 0.4%    |
| 0x10661    | 3         | 0.4%    |
| 0x0a404102 | 3         | 0.4%    |
| 0x08701021 | 3         | 0.4%    |
| 0x08108109 | 3         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KabyLake           | 85        | 11.71%  |
| IvyBridge          | 75        | 10.33%  |
| SandyBridge        | 68        | 9.37%   |
| Penryn             | 65        | 8.95%   |
| Unknown            | 58        | 7.99%   |
| Haswell            | 46        | 6.34%   |
| Core               | 32        | 4.41%   |
| Alderlake Hybrid   | 31        | 4.27%   |
| Zen 3              | 26        | 3.58%   |
| Silvermont         | 25        | 3.44%   |
| TigerLake          | 24        | 3.31%   |
| Skylake            | 22        | 3.03%   |
| CometLake          | 19        | 2.62%   |
| Westmere           | 18        | 2.48%   |
| Zen+               | 13        | 1.79%   |
| Zen 2              | 10        | 1.38%   |
| Piledriver         | 10        | 1.38%   |
| Zen                | 8         | 1.1%    |
| NetBurst           | 8         | 1.1%    |
| K10                | 8         | 1.1%    |
| IceLake            | 8         | 1.1%    |
| Goldmont plus      | 8         | 1.1%    |
| Broadwell          | 8         | 1.1%    |
| Bonnell            | 8         | 1.1%    |
| P6                 | 7         | 0.96%   |
| Nehalem            | 6         | 0.83%   |
| Bobcat             | 6         | 0.83%   |
| K8 Hammer          | 4         | 0.55%   |
| K10 Llano          | 4         | 0.55%   |
| Excavator          | 4         | 0.55%   |
| Puma               | 3         | 0.41%   |
| Tremont            | 2         | 0.28%   |
| Jaguar             | 2         | 0.28%   |
| Meteorlake Hybrid  | 1         | 0.14%   |
| Gracemont          | 1         | 0.14%   |
| Goldmont           | 1         | 0.14%   |
| Bulldozer          | 1         | 0.14%   |
| ArrowLake-H Hybrid | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 381       | 41.64%  |
| Nvidia                     | 344       | 37.6%   |
| AMD                        | 185       | 20.22%  |
| Matrox Electronics Systems | 3         | 0.33%   |
| ASPEED Technology          | 2         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 4.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 3.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 2.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.67%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 15        | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.15%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 11        | 1.15%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 11        | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 10        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.04%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 10        | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.04%   |
| AMD Rembrandt [Radeon 680M]                                                              | 10        | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.04%   |
| Nvidia GT218 [GeForce 210]                                                               | 9         | 0.94%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 9         | 0.94%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 9         | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 0.94%   |
| AMD Lucienne                                                                             | 9         | 0.94%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 8         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.73%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 7         | 0.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 0.73%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.73%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 7         | 0.73%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 7         | 0.73%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 6         | 0.63%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 6         | 0.63%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 6         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 222       | 30.33%  |
| 1 x Nvidia              | 201       | 27.46%  |
| Intel + Nvidia          | 115       | 15.71%  |
| 1 x AMD                 | 107       | 14.62%  |
| Intel + AMD             | 30        | 4.1%    |
| AMD + Nvidia            | 28        | 3.83%   |
| 2 x AMD                 | 19        | 2.6%    |
| Other                   | 4         | 0.55%   |
| 1 x Matrox              | 2         | 0.27%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.14%   |
| 2 x Intel               | 1         | 0.14%   |
| Nvidia + Matrox         | 1         | 0.14%   |
| Nvidia + ASPEED         | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 573       | 77.02%  |
| Proprietary | 129       | 17.34%  |
| Unknown     | 42        | 5.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 299       | 39.87%  |
| 1.01-2.0   | 158       | 21.07%  |
| 0.01-0.5   | 109       | 14.53%  |
| 0.51-1.0   | 91        | 12.13%  |
| 3.01-4.0   | 46        | 6.13%   |
| 7.01-8.0   | 24        | 3.2%    |
| 5.01-6.0   | 12        | 1.6%    |
| 8.01-16.0  | 7         | 0.93%   |
| 2.01-3.0   | 2         | 0.27%   |
| 16.01-24.0 | 2         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 137       | 18%     |
| AU Optronics            | 92        | 12.09%  |
| BOE                     | 72        | 9.46%   |
| LG Display              | 67        | 8.8%    |
| Chimei Innolux          | 59        | 7.75%   |
| Goldstar                | 54        | 7.1%    |
| Hewlett-Packard         | 37        | 4.86%   |
| Acer                    | 29        | 3.81%   |
| Philips                 | 28        | 3.68%   |
| Chi Mei Optoelectronics | 21        | 2.76%   |
| BenQ                    | 20        | 2.63%   |
| Dell                    | 15        | 1.97%   |
| AOC                     | 14        | 1.84%   |
| Lenovo                  | 13        | 1.71%   |
| ViewSonic               | 5         | 0.66%   |
| SAC                     | 5         | 0.66%   |
| Toshiba                 | 4         | 0.53%   |
| Sony                    | 4         | 0.53%   |
| Sharp                   | 4         | 0.53%   |
| PANDA                   | 4         | 0.53%   |
| Iiyama                  | 4         | 0.53%   |
| Fujitsu Siemens         | 4         | 0.53%   |
| Valve                   | 3         | 0.39%   |
| Unknown (XXX)           | 3         | 0.39%   |
| Unknown                 | 3         | 0.39%   |
| Quanta Display          | 3         | 0.39%   |
| Panasonic               | 3         | 0.39%   |
| Mi                      | 3         | 0.39%   |
| LG Philips              | 3         | 0.39%   |
| Gigabyte Technology     | 3         | 0.39%   |
| CSOT                    | 3         | 0.39%   |
| Arnos Instruments       | 3         | 0.39%   |
| VIE                     | 2         | 0.26%   |
| TMX                     | 2         | 0.26%   |
| TMA                     | 2         | 0.26%   |
| LG Electronics          | 2         | 0.26%   |
| InfoVision              | 2         | 0.26%   |
| HannStar                | 2         | 0.26%   |
| CSO                     | 2         | 0.26%   |
| CPT                     | 2         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 1.03%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                    | 6         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.77%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.77%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 340x270mm 17.1-inch     | 5         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 5         | 0.64%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.64%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch      | 4         | 0.51%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch     | 4         | 0.51%   |
| Samsung Electronics SyncMaster SAM0247 1280x1024 376x301mm 19.0-inch     | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.51%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.51%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.39%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch       | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch    | 3         | 0.39%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                    | 3         | 0.39%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch              | 3         | 0.39%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch                | 3         | 0.39%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch                | 3         | 0.39%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                     | 3         | 0.39%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 3         | 0.39%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                      | 3         | 0.39%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 3         | 0.39%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.39%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                         | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.39%   |
| BOE LCD Monitor BOE0A9B 2560x1600 344x215mm 16.0-inch                    | 3         | 0.39%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.39%   |
| BenQ E900W BNQ7905 1440x900 410x256mm 19.0-inch                          | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 291       | 39.43%  |
| 1366x768 (WXGA)    | 179       | 24.25%  |
| 1280x1024 (SXGA)   | 58        | 7.86%   |
| 1600x900 (HD+)     | 33        | 4.47%   |
| 2560x1440 (QHD)    | 24        | 3.25%   |
| 1680x1050 (WSXGA+) | 20        | 2.71%   |
| 3840x2160 (4K)     | 18        | 2.44%   |
| 1440x900 (WXGA+)   | 18        | 2.44%   |
| 2560x1600          | 13        | 1.76%   |
| 1920x1200 (WUXGA)  | 12        | 1.63%   |
| 1280x800 (WXGA)    | 12        | 1.63%   |
| 1360x768           | 7         | 0.95%   |
| 1024x600           | 6         | 0.81%   |
| 2560x1080          | 5         | 0.68%   |
| 3200x2000          | 4         | 0.54%   |
| 2880x1620          | 4         | 0.54%   |
| 800x1280           | 3         | 0.41%   |
| 2880x1800          | 3         | 0.41%   |
| 1920x540           | 3         | 0.41%   |
| 1024x768 (XGA)     | 3         | 0.41%   |
| Unknown            | 3         | 0.41%   |
| 3440x1440          | 2         | 0.27%   |
| 3072x1920          | 2         | 0.27%   |
| 2288x1287          | 2         | 0.27%   |
| 1400x1050          | 2         | 0.27%   |
| 1280x720 (HD)      | 2         | 0.27%   |
| 3840x1100          | 1         | 0.14%   |
| 3840x1080          | 1         | 0.14%   |
| 3600x1080          | 1         | 0.14%   |
| 3520x1080          | 1         | 0.14%   |
| 3200x1080          | 1         | 0.14%   |
| 2240x1400          | 1         | 0.14%   |
| 2160x1440          | 1         | 0.14%   |
| 1600x1200          | 1         | 0.14%   |
| 1280x960           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 256       | 33.51%  |
| 17      | 56        | 7.33%   |
| 21      | 53        | 6.94%   |
| 19      | 46        | 6.02%   |
| 27      | 40        | 5.24%   |
| 18      | 32        | 4.19%   |
| 14      | 32        | 4.19%   |
| 24      | 31        | 4.06%   |
| 23      | 30        | 3.93%   |
| 16      | 28        | 3.66%   |
| 13      | 24        | 3.14%   |
| Unknown | 24        | 3.14%   |
| 20      | 19        | 2.49%   |
| 31      | 17        | 2.23%   |
| 22      | 12        | 1.57%   |
| 12      | 8         | 1.05%   |
| 10      | 7         | 0.92%   |
| 11      | 6         | 0.79%   |
| 54      | 5         | 0.65%   |
| 34      | 5         | 0.65%   |
| 72      | 4         | 0.52%   |
| 32      | 4         | 0.52%   |
| 7       | 4         | 0.52%   |
| 84      | 3         | 0.39%   |
| 48      | 3         | 0.39%   |
| 142     | 2         | 0.26%   |
| 46      | 2         | 0.26%   |
| 43      | 2         | 0.26%   |
| 40      | 2         | 0.26%   |
| 28      | 2         | 0.26%   |
| 26      | 2         | 0.26%   |
| 64      | 1         | 0.13%   |
| 63      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 350       | 46.3%   |
| 401-500        | 130       | 17.2%   |
| 501-600        | 96        | 12.7%   |
| 351-400        | 66        | 8.73%   |
| 201-300        | 31        | 4.1%    |
| Unknown        | 24        | 3.17%   |
| 601-700        | 20        | 2.65%   |
| 1001-1500      | 12        | 1.59%   |
| 701-800        | 9         | 1.19%   |
| 1501-2000      | 7         | 0.93%   |
| 801-900        | 3         | 0.4%    |
| 1-100          | 3         | 0.4%    |
| More than 2000 | 2         | 0.26%   |
| 901-1000       | 2         | 0.26%   |
| 101-200        | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 529       | 74.3%   |
| 16/10   | 81        | 11.38%  |
| 5/4     | 58        | 8.15%   |
| Unknown | 17        | 2.39%   |
| 4/3     | 8         | 1.12%   |
| 3/2     | 5         | 0.7%    |
| 21/9    | 5         | 0.7%    |
| 0.67    | 3         | 0.42%   |
| 32/9    | 2         | 0.28%   |
| 1.00    | 2         | 0.28%   |
| 6/5     | 1         | 0.14%   |
| 3.40    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 257       | 33.77%  |
| 201-250        | 105       | 13.8%   |
| 151-200        | 77        | 10.12%  |
| 141-150        | 58        | 7.62%   |
| 81-90          | 44        | 5.78%   |
| 301-350        | 42        | 5.52%   |
| 351-500        | 28        | 3.68%   |
| 121-130        | 26        | 3.42%   |
| Unknown        | 24        | 3.15%   |
| 111-120        | 22        | 2.89%   |
| More than 1000 | 19        | 2.5%    |
| 71-80          | 11        | 1.45%   |
| 251-300        | 9         | 1.18%   |
| 51-60          | 7         | 0.92%   |
| 41-50          | 7         | 0.92%   |
| 501-1000       | 7         | 0.92%   |
| 61-70          | 6         | 0.79%   |
| 91-100         | 5         | 0.66%   |
| 1-40           | 4         | 0.53%   |
| 131-140        | 3         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 270       | 36.05%  |
| 101-120       | 211       | 28.17%  |
| 121-160       | 176       | 23.5%   |
| 161-240       | 42        | 5.61%   |
| Unknown       | 24        | 3.2%    |
| 1-50          | 22        | 2.94%   |
| More than 240 | 4         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 625       | 84.46%  |
| 2     | 81        | 10.95%  |
| 0     | 29        | 3.92%   |
| 3     | 5         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 482       | 43.19%  |
| Intel                             | 232       | 20.79%  |
| Qualcomm Atheros                  | 149       | 13.35%  |
| MediaTek                          | 46        | 4.12%   |
| Broadcom                          | 42        | 3.76%   |
| Ralink Technology                 | 20        | 1.79%   |
| Ralink                            | 18        | 1.61%   |
| Broadcom Limited                  | 18        | 1.61%   |
| TP-Link                           | 10        | 0.9%    |
| Qualcomm Atheros Communications   | 10        | 0.9%    |
| Marvell Technology Group          | 10        | 0.9%    |
| Xiaomi                            | 8         | 0.72%   |
| Nvidia                            | 8         | 0.72%   |
| Huawei Technologies               | 8         | 0.72%   |
| VIA Technologies                  | 5         | 0.45%   |
| ASIX Electronics                  | 5         | 0.45%   |
| Samsung Electronics               | 4         | 0.36%   |
| JMicron Technology                | 3         | 0.27%   |
| Hewlett-Packard                   | 3         | 0.27%   |
| D-Link                            | 3         | 0.27%   |
| Shenzhen Goodix Technology        | 2         | 0.18%   |
| Qualcomm Technologies             | 2         | 0.18%   |
| OPPO Electronics                  | 2         | 0.18%   |
| Mellanox Technologies             | 2         | 0.18%   |
| HTC (High Tech Computer)          | 2         | 0.18%   |
| Google                            | 2         | 0.18%   |
| DisplayLink                       | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| STMicroelectronics                | 1         | 0.09%   |
| Philips (or NXP)                  | 1         | 0.09%   |
| Microchip Technology              | 1         | 0.09%   |
| Marvell Semiconductor             | 1         | 0.09%   |
| Linux 2.6.38.8+ with at91_udc     | 1         | 0.09%   |
| Lenovo                            | 1         | 0.09%   |
| Insyde Software                   | 1         | 0.09%   |
| ICS Advent                        | 1         | 0.09%   |
| Fujitsu Siemens Computers         | 1         | 0.09%   |
| Fibocom                           | 1         | 0.09%   |
| Ericsson Business Mobile Networks | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 314       | 25.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 75        | 6%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 29        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 26        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 20        | 1.6%    |
| Intel Wi-Fi 6 AX201                                                    | 19        | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 1.44%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 18        | 1.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 16        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 16        | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 14        | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 14        | 1.12%   |
| Intel Wireless 8265 / 8275                                             | 13        | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 12        | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 11        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                        | 10        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 10        | 0.8%    |
| Intel Wi-Fi 6 AX200                                                    | 10        | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 9         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 9         | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 8         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                        | 8         | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 0.64%   |
| Ralink RT5370 Wireless Adapter                                         | 7         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.48%   |
| Intel Wireless 7260                                                    | 6         | 0.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.48%   |
| Intel Centrino Wireless-N 2230                                         | 6         | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 174       | 33.4%   |
| Qualcomm Atheros                | 115       | 22.07%  |
| Realtek Semiconductor           | 96        | 18.43%  |
| MediaTek                        | 35        | 6.72%   |
| Broadcom                        | 30        | 5.76%   |
| Ralink Technology               | 20        | 3.84%   |
| Ralink                          | 18        | 3.45%   |
| Qualcomm Atheros Communications | 10        | 1.92%   |
| TP-Link                         | 6         | 1.15%   |
| Broadcom Limited                | 6         | 1.15%   |
| D-Link                          | 3         | 0.58%   |
| Qualcomm Technologies           | 2         | 0.38%   |
| Philips (or NXP)                | 1         | 0.19%   |
| Fujitsu Siemens Computers       | 1         | 0.19%   |
| Fibocom                         | 1         | 0.19%   |
| Edimax Technology               | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |
| Accton Technology               | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 5.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 4.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 4.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 3.84%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 3.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 3.45%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 18        | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 3.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 2.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 2.69%   |
| Intel Wireless 8265 / 8275                                              | 13        | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 2.11%   |
| Ralink MT7601U Wireless Adapter                                         | 10        | 1.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 10        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 1.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.54%   |
| Ralink RT5370 Wireless Adapter                                          | 7         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.15%   |
| Intel Wireless 7260                                                     | 6         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.15%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.15%   |
| Broadcom BCM43227 802.11b/g/n                                           | 6         | 1.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.96%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 5         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.96%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 0.96%   |
| Intel Wireless 8260                                                     | 5         | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 0.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 5         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.96%   |
| Intel Centrino Wireless-N 135                                           | 5         | 0.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 438       | 62.57%  |
| Intel                    | 97        | 13.86%  |
| Qualcomm Atheros         | 57        | 8.14%   |
| Broadcom                 | 16        | 2.29%   |
| Broadcom Limited         | 13        | 1.86%   |
| MediaTek                 | 11        | 1.57%   |
| Marvell Technology Group | 10        | 1.43%   |
| Xiaomi                   | 8         | 1.14%   |
| Nvidia                   | 8         | 1.14%   |
| Huawei Technologies      | 6         | 0.86%   |
| VIA Technologies         | 5         | 0.71%   |
| ASIX Electronics         | 5         | 0.71%   |
| TP-Link                  | 4         | 0.57%   |
| Samsung Electronics      | 4         | 0.57%   |
| JMicron Technology       | 3         | 0.43%   |
| OPPO Electronics         | 2         | 0.29%   |
| Mellanox Technologies    | 2         | 0.29%   |
| HTC (High Tech Computer) | 2         | 0.29%   |
| Google                   | 2         | 0.29%   |
| DisplayLink              | 2         | 0.29%   |
| Marvell Semiconductor    | 1         | 0.14%   |
| Insyde Software          | 1         | 0.14%   |
| ICS Advent               | 1         | 0.14%   |
| Dell                     | 1         | 0.14%   |
| Android                  | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 314       | 44.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 75        | 10.53%  |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 2.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 14        | 1.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 12        | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 10        | 1.4%    |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 1.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 9         | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.12%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.98%   |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 0.84%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 0.7%    |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.7%    |
| Huawei E353/E3131                                                      | 5         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 4         | 0.56%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.56%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 3         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.42%   |
| MediaTek Infinix HOT 50i                                               | 3         | 0.42%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.42%   |
| Intel Ethernet Connection (23) I219-V                                  | 3         | 0.42%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                  | 3         | 0.42%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.42%   |
| Intel 82573L Gigabit Ethernet Controller                               | 3         | 0.42%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 3         | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 0.28%   |
| TP-Link USB 10/100 LAN                                                 | 2         | 0.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 654       | 55.56%  |
| WiFi     | 506       | 42.99%  |
| Modem    | 16        | 1.36%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 401       | 54.63%  |
| Ethernet | 332       | 45.23%  |
| Modem    | 1         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 389       | 53.8%   |
| 1     | 313       | 43.29%  |
| 0     | 10        | 1.38%   |
| 3     | 6         | 0.83%   |
| 4     | 4         | 0.55%   |
| 5     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 701       | 96.69%  |
| Yes  | 24        | 3.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 145       | 35.89%  |
| Realtek Semiconductor           | 50        | 12.38%  |
| IMC Networks                    | 50        | 12.38%  |
| Qualcomm Atheros Communications | 28        | 6.93%   |
| Foxconn / Hon Hai               | 25        | 6.19%   |
| Lite-On Technology              | 24        | 5.94%   |
| Broadcom                        | 20        | 4.95%   |
| Cambridge Silicon Radio         | 19        | 4.7%    |
| Ralink                          | 8         | 1.98%   |
| Hewlett-Packard                 | 8         | 1.98%   |
| Toshiba                         | 6         | 1.49%   |
| TP-Link                         | 3         | 0.74%   |
| MediaTek                        | 3         | 0.74%   |
| Foxconn International           | 3         | 0.74%   |
| ASUSTek Computer                | 3         | 0.74%   |
| Realtek                         | 2         | 0.5%    |
| Ralink Technology               | 2         | 0.5%    |
| Integrated System Solution      | 2         | 0.5%    |
| Logitech                        | 1         | 0.25%   |
| HTC (High Tech Computer)        | 1         | 0.25%   |
| Askey Computer                  | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 38        | 9.41%   |
| Intel Bluetooth wireless interface                  | 37        | 9.16%   |
| Intel AX201 Bluetooth                               | 37        | 9.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 5.2%    |
| IMC Networks Wireless_Device                        | 21        | 5.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19        | 4.7%    |
| Intel Bluetooth Device                              | 16        | 3.96%   |
| IMC Networks Bluetooth Radio                        | 16        | 3.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 3.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 2.72%   |
| Intel AX200 Bluetooth                               | 10        | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 2.23%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 2.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.98%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.98%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 1.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 1.49%   |
| Lite-On Bluetooth Device                            | 6         | 1.49%   |
| IMC Networks Bluetooth Device                       | 6         | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.24%   |
| Intel AX210 Bluetooth                               | 5         | 1.24%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 1.24%   |
| Broadcom HP Portable Valentine                      | 5         | 1.24%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.99%   |
| TP-Link TP-T@- UB500 Adapter                        | 3         | 0.74%   |
| Toshiba Integrated Bluetooth HCI                    | 3         | 0.74%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.74%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.74%   |
| MediaTek Wireless_Device                            | 3         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.74%   |
| Realtek Bluetooth Radio                             | 2         | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.5%    |
| Lite-On Wireless_Device                             | 2         | 0.5%    |
| Integrated System Solution Bluetooth Device         | 2         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 558       | 53.97%  |
| Nvidia                   | 240       | 23.21%  |
| AMD                      | 167       | 16.15%  |
| C-Media Electronics      | 16        | 1.55%   |
| Logitech                 | 5         | 0.48%   |
| Razer USA                | 4         | 0.39%   |
| Generalplus Technology   | 4         | 0.39%   |
| Focusrite-Novation       | 4         | 0.39%   |
| JMTek                    | 3         | 0.29%   |
| Hewlett-Packard          | 3         | 0.29%   |
| Creative Labs            | 3         | 0.29%   |
| ASUSTek Computer         | 3         | 0.29%   |
| VIA Technologies         | 2         | 0.19%   |
| Sony                     | 2         | 0.19%   |
| Realtek Semiconductor    | 2         | 0.19%   |
| Xilinx                   | 1         | 0.1%    |
| ULi Electronics          | 1         | 0.1%    |
| SAVITECH                 | 1         | 0.1%    |
| Plantronics              | 1         | 0.1%    |
| Pixart Imaging           | 1         | 0.1%    |
| Nordic Semiconductor ASA | 1         | 0.1%    |
| M-Audio                  | 1         | 0.1%    |
| KTMicro                  | 1         | 0.1%    |
| Kingston Technology      | 1         | 0.1%    |
| Huawei Technologies      | 1         | 0.1%    |
| GYROCOM C&C              | 1         | 0.1%    |
| ELMCU                    | 1         | 0.1%    |
| Elgato Systems           | 1         | 0.1%    |
| Blue Microphones         | 1         | 0.1%    |
| BEHRINGER International  | 1         | 0.1%    |
| Audio-Technica           | 1         | 0.1%    |
| Asahi Kasei Microsystems | 1         | 0.1%    |
| Unknown                  | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 72        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 71        | 6.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 69        | 5.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 55        | 4.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 3.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 41        | 3.48%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 33        | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 2.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 1.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 1.78%   |
| AMD Radeon High Definition Audio Controller                                                       | 21        | 1.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 19        | 1.61%   |
| AMD FCH Azalia Controller                                                                         | 18        | 1.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 17        | 1.44%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 16        | 1.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 14        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.02%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 12        | 1.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 1.02%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 0.76%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 9         | 0.76%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 9         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.76%   |
| AMD Trinity HDMI Audio Controller                                                                 | 9         | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 9         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 8         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 150       | 22.16%  |
| Samsung Electronics          | 118       | 17.43%  |
| SK hynix                     | 104       | 15.36%  |
| Kingston                     | 67        | 9.9%    |
| Micron Technology            | 45        | 6.65%   |
| Transcend                    | 18        | 2.66%   |
| A-DATA Technology            | 17        | 2.51%   |
| Ramaxel Technology           | 15        | 2.22%   |
| G.Skill                      | 15        | 2.22%   |
| Crucial                      | 15        | 2.22%   |
| Apacer                       | 12        | 1.77%   |
| GeIL                         | 11        | 1.62%   |
| Team                         | 10        | 1.48%   |
| Nanya Technology             | 9         | 1.33%   |
| Silicon Power                | 7         | 1.03%   |
| Patriot                      | 5         | 0.74%   |
| Corsair                      | 5         | 0.74%   |
| Unknown                      | 5         | 0.74%   |
| Unknown (ABCD)               | 4         | 0.59%   |
| Elpida                       | 4         | 0.59%   |
| Hikvision                    | 3         | 0.44%   |
| Super Talent                 | 2         | 0.3%    |
| SUPER KINGSTEK               | 2         | 0.3%    |
| Qimonda                      | 2         | 0.3%    |
| Patriot Memory (PDP Systems) | 2         | 0.3%    |
| Kingmax                      | 2         | 0.3%    |
| HPE                          | 2         | 0.3%    |
| GOODRAM                      | 2         | 0.3%    |
| Golden Empire                | 2         | 0.3%    |
| Atermiter                    | 2         | 0.3%    |
| ASint Technology             | 2         | 0.3%    |
| V-Color                      | 1         | 0.15%   |
| Unknown (D386)               | 1         | 0.15%   |
| Unknown (8CAB)               | 1         | 0.15%   |
| Unknown (0x0B92)             | 1         | 0.15%   |
| Unifosa                      | 1         | 0.15%   |
| Toshiba                      | 1         | 0.15%   |
| SHARETRONIC                  | 1         | 0.15%   |
| Qumo                         | 1         | 0.15%   |
| ProMos/Mosel Vitelic         | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 13        | 1.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 11        | 1.53%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 7         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.97%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 6         | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.83%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 6         | 0.83%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 5         | 0.7%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 5         | 0.7%    |
| Transcend RAM JM1333KLU-2G 2GB DIMM DDR3 1333MT/s                | 5         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 5         | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 5         | 0.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.7%    |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s          | 5         | 0.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.7%    |
| Unknown                                                          | 5         | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.56%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 4         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 0.56%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 4         | 0.56%   |
| GeIL RAM CL9-9-9 D3-1333 8GB DIMM DDR3 1333MT/s                  | 4         | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 3         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.42%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 3         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.42%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 3         | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.42%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.42%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 220       | 38.73%  |
| DDR4    | 172       | 30.28%  |
| SDRAM   | 39        | 6.87%   |
| DDR2    | 39        | 6.87%   |
| Unknown | 39        | 6.87%   |
| DDR5    | 25        | 4.4%    |
| LPDDR4  | 13        | 2.29%   |
| LPDDR5  | 9         | 1.58%   |
| DDR     | 9         | 1.58%   |
| LPDDR3  | 3         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 301       | 53.27%  |
| DIMM         | 235       | 41.59%  |
| Row Of Chips | 25        | 4.42%   |
| FB-DIMM      | 3         | 0.53%   |
| Unknown      | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 184       | 28.44%  |
| 4096  | 166       | 25.66%  |
| 2048  | 144       | 22.26%  |
| 16384 | 64        | 9.89%   |
| 1024  | 58        | 8.96%   |
| 32768 | 21        | 3.25%   |
| 512   | 7         | 1.08%   |
| 65536 | 1         | 0.15%   |
| 256   | 1         | 0.15%   |
| 16    | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 130       | 20.87%  |
| 3200    | 82        | 13.16%  |
| 1333    | 65        | 10.43%  |
| Unknown | 48        | 7.7%    |
| 2667    | 44        | 7.06%   |
| 800     | 32        | 5.14%   |
| 2400    | 31        | 4.98%   |
| 1334    | 24        | 3.85%   |
| 667     | 23        | 3.69%   |
| 4800    | 14        | 2.25%   |
| 2133    | 10        | 1.61%   |
| 1067    | 10        | 1.61%   |
| 2666    | 9         | 1.44%   |
| 5600    | 7         | 1.12%   |
| 3600    | 6         | 0.96%   |
| 1867    | 6         | 0.96%   |
| 1066    | 6         | 0.96%   |
| 533     | 6         | 0.96%   |
| 6400    | 5         | 0.8%    |
| 4267    | 5         | 0.8%    |
| 4199    | 4         | 0.64%   |
| 1866    | 4         | 0.64%   |
| 400     | 4         | 0.64%   |
| 8400    | 3         | 0.48%   |
| 6000    | 3         | 0.48%   |
| 4266    | 3         | 0.48%   |
| 3800    | 3         | 0.48%   |
| 3733    | 3         | 0.48%   |
| 3266    | 3         | 0.48%   |
| 2048    | 3         | 0.48%   |
| 8533    | 2         | 0.32%   |
| 5354    | 2         | 0.32%   |
| 3000    | 2         | 0.32%   |
| 975     | 2         | 0.32%   |
| 8000    | 1         | 0.16%   |
| 7500    | 1         | 0.16%   |
| 6800    | 1         | 0.16%   |
| 5200    | 1         | 0.16%   |
| 4000    | 1         | 0.16%   |
| 3400    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 9         | 39.13%  |
| Samsung Electronics    | 4         | 17.39%  |
| Canon                  | 4         | 17.39%  |
| Xerox                  | 3         | 13.04%  |
| Seiko Epson            | 1         | 4.35%   |
| Panasonic (Matsushita) | 1         | 4.35%   |
| Lexmark International  | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP LaserJet 1018                           | 3         | 13.04%  |
| HP LaserJet 1020                           | 2         | 8.7%    |
| Xerox WorkCentre 6015B                     | 1         | 4.35%   |
| Xerox Phaser 3160                          | 1         | 4.35%   |
| Xerox Phaser 3020                          | 1         | 4.35%   |
| Seiko Epson L805 Series                    | 1         | 4.35%   |
| Samsung Xerox Phaser 3117 Laser Printer    | 1         | 4.35%   |
| Samsung ML-1640 Series Laser Printer       | 1         | 4.35%   |
| Samsung M2020 Series                       | 1         | 4.35%   |
| Samsung CLX-3180 Series                    | 1         | 4.35%   |
| Panasonic (Matsushita) KX-MB1500RU         | 1         | 4.35%   |
| Lexmark International InkJet Color Printer | 1         | 4.35%   |
| HP LaserJet P1102                          | 1         | 4.35%   |
| HP LaserJet 1010                           | 1         | 4.35%   |
| HP DeskJet 5650c                           | 1         | 4.35%   |
| HP Deskjet 2520 series                     | 1         | 4.35%   |
| Canon LBP810                               | 1         | 4.35%   |
| Canon LBP6000                              | 1         | 4.35%   |
| Canon LBP2900                              | 1         | 4.35%   |
| Canon G3010 series                         | 1         | 4.35%   |

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


| Model          | Computers | Percent |
|----------------|-----------|---------|
| HP Scanjet 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 85        | 19.72%  |
| IMC Networks                           | 47        | 10.9%   |
| Quanta                                 | 41        | 9.51%   |
| Realtek Semiconductor                  | 26        | 6.03%   |
| Sunplus Innovation Technology          | 21        | 4.87%   |
| Bison Electronics                      | 21        | 4.87%   |
| Logitech                               | 18        | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 4.18%   |
| Microdia                               | 17        | 3.94%   |
| Suyin                                  | 16        | 3.71%   |
| Z-Star Microelectronics                | 14        | 3.25%   |
| Syntek                                 | 13        | 3.02%   |
| KYE Systems (Mouse Systems)            | 11        | 2.55%   |
| Sonix Technology                       | 9         | 2.09%   |
| Shinetech                              | 7         | 1.62%   |
| Lite-On Technology                     | 7         | 1.62%   |
| Luxvisions Innotech Limited            | 6         | 1.39%   |
| Silicon Motion                         | 5         | 1.16%   |
| Samsung Electronics                    | 5         | 1.16%   |
| Alcor Micro                            | 4         | 0.93%   |
| SiGma Micro                            | 3         | 0.7%    |
| Ricoh                                  | 3         | 0.7%    |
| Pixart Imaging                         | 3         | 0.7%    |
| GEMBIRD                                | 3         | 0.7%    |
| Apple                                  | 3         | 0.7%    |
| Primax Electronics                     | 2         | 0.46%   |
| Hewlett-Packard                        | 2         | 0.46%   |
| Generalplus Technology                 | 2         | 0.46%   |
| ALi                                    | 2         | 0.46%   |
| Y Media                                | 1         | 0.23%   |
| SunplusIT                              | 1         | 0.23%   |
| Shine-optics                           | 1         | 0.23%   |
| SenseTek                               | 1         | 0.23%   |
| OPPO Electronics                       | 1         | 0.23%   |
| Nebraska Furniture Mart                | 1         | 0.23%   |
| Lenovo                                 | 1         | 0.23%   |
| Jieli Technology                       | 1         | 0.23%   |
| Importek                               | 1         | 0.23%   |
| icSpring                               | 1         | 0.23%   |
| Goertek Electronics                    | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 16        | 3.7%    |
| IMC Networks USB2.0 VGA UVC WebCam            | 10        | 2.31%   |
| Chicony HD WebCam                             | 10        | 2.31%   |
| Quanta HD Webcam                              | 9         | 2.08%   |
| IMC Networks Integrated Camera                | 9         | 2.08%   |
| Z-Star Venus USB2.0 Camera                    | 8         | 1.85%   |
| Quanta HD User Facing                         | 8         | 1.85%   |
| Syntek Integrated Camera                      | 7         | 1.62%   |
| Chicony integrated camera                     | 7         | 1.62%   |
| Bison Integrated Camera                       | 7         | 1.62%   |
| Sunplus HD WebCam                             | 6         | 1.39%   |
| Realtek Lenovo EasyCamera                     | 6         | 1.39%   |
| Quanta HP Wide Vision HD Camera               | 6         | 1.39%   |
| Logitech Webcam C270                          | 6         | 1.39%   |
| Bison Lenovo Integrated Webcam                | 6         | 1.39%   |
| Suyin 1.3M HD WebCam                          | 5         | 1.16%   |
| Sonix USB2.0 FHD UVC WebCam                   | 5         | 1.16%   |
| Samsung Galaxy series, misc. (MTP mode)       | 5         | 1.16%   |
| Microdia Integrated_Webcam_HD                 | 5         | 1.16%   |
| Chicony Lenovo EasyCamera                     | 5         | 1.16%   |
| Syntek Lenovo EasyCamera                      | 4         | 0.93%   |
| Sunplus Asus Webcam                           | 4         | 0.93%   |
| Sonix USB2.0 HD UVC WebCam                    | 4         | 0.93%   |
| Shinetech USB2.0 FHD UVC WebCam               | 4         | 0.93%   |
| Quanta VGA WebCam                             | 4         | 0.93%   |
| Lite-On Integrated Camera                     | 4         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                 | 4         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)       | 4         | 0.93%   |
| Chicony HP Truevision HD                      | 4         | 0.93%   |
| Chicony Fujitsu Integrated Camera             | 4         | 0.93%   |
| Chicony EasyCamera                            | 4         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 4         | 0.93%   |
| Suyin HP Truevision HD                        | 3         | 0.69%   |
| SiGma Micro WebCam SiGma Micro                | 3         | 0.69%   |
| Realtek USB Camera                            | 3         | 0.69%   |
| Realtek Integrated_Webcam_HD                  | 3         | 0.69%   |
| Realtek Acer 640 x 480 laptop camera          | 3         | 0.69%   |
| Quanta HP TrueVision HD Camera                | 3         | 0.69%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro          | 3         | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD          | 3         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 16        | 25.81%  |
| Shenzhen Goodix Technology         | 9         | 14.52%  |
| Synaptics                          | 8         | 12.9%   |
| Elan Microelectronics              | 7         | 11.29%  |
| Upek                               | 6         | 9.68%   |
| AuthenTec                          | 6         | 9.68%   |
| STMicroelectronics                 | 4         | 6.45%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 4.84%   |
| LighTuning Technology              | 2         | 3.23%   |
| HOLTEK                             | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 9.68%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 6         | 9.68%   |
| Shenzhen Goodix  Fingerprint Device                             | 6         | 9.68%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 6.45%   |
| Elan ELAN:ARM-M4                                                | 4         | 6.45%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 3         | 4.84%   |
| Validity Sensors Fingerprint scanner                            | 3         | 4.84%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 4.84%   |
| Elan ELAN:Fingerprint                                           | 3         | 4.84%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 4.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 3.23%   |
| AuthenTec AES2810                                               | 2         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 1.61%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.61%   |
| Synaptics  WBDI                                                 | 1         | 1.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.61%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 1.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.61%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.61%   |
| HOLTEK FocalTech Fingerprint Device                             | 1         | 1.61%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 30.77%  |
| Alcor Micro           | 3         | 23.08%  |
| Upek                  | 1         | 7.69%   |
| O2 Micro              | 1         | 7.69%   |
| Lenovo                | 1         | 7.69%   |
| Feitian Technologies  | 1         | 7.69%   |
| Aktiv                 | 1         | 7.69%   |
| Advanced Card Systems | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                         | 3         | 23.08%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                  | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                        | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                         | 1         | 7.69%   |
| Feitian Technologies SCR301                                                 | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                              | 1         | 7.69%   |
| Broadcom 5880                                                               | 1         | 7.69%   |
| Aktiv KAZTOKEN                                                              | 1         | 7.69%   |
| Advanced Card Systems ACR38 SmartCard Reader                                | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 562       | 75.23%  |
| 1     | 150       | 20.08%  |
| 2     | 23        | 3.08%   |
| 3     | 10        | 1.34%   |
| 4     | 2         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 72        | 33.03%  |
| Fingerprint reader       | 62        | 28.44%  |
| Net/wireless             | 23        | 10.55%  |
| Communication controller | 14        | 6.42%   |
| Chipcard                 | 11        | 5.05%   |
| Bluetooth                | 10        | 4.59%   |
| Unassigned class         | 8         | 3.67%   |
| Multimedia controller    | 7         | 3.21%   |
| Camera                   | 7         | 3.21%   |
| Wireless                 | 1         | 0.46%   |
| Net/ethernet             | 1         | 0.46%   |
| Modem                    | 1         | 0.46%   |
| Card reader              | 1         | 0.46%   |

