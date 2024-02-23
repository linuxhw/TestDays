Fedora 38 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 1371

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B560M-ITX/ac                | [9ed6c67efe](https://linux-hardware.org/?probe=9ed6c67efe) | Feb 02, 2024 |
| ASUSTek       | PRIME B450M-A II            | [abdcd1a804](https://linux-hardware.org/?probe=abdcd1a804) | Jan 30, 2024 |
| Dell          | 0HHV7N A00                  | [38b1e0aa62](https://linux-hardware.org/?probe=38b1e0aa62) | Jan 23, 2024 |
| Dell          | 0HHV7N A00                  | [d6aeeb6ece](https://linux-hardware.org/?probe=d6aeeb6ece) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [a27ea5cca3](https://linux-hardware.org/?probe=a27ea5cca3) | Jan 20, 2024 |
| Lenovo        | ThinkServer TS140           | [8ccec416bf](https://linux-hardware.org/?probe=8ccec416bf) | Jan 17, 2024 |
| ASUSTek       | Leonite2                    | [70605195c6](https://linux-hardware.org/?probe=70605195c6) | Jan 16, 2024 |
| ASUSTek       | Leonite2                    | [a4f9390786](https://linux-hardware.org/?probe=a4f9390786) | Jan 15, 2024 |
| ASRock        | B560M-ITX/ac                | [0ab95fc3f5](https://linux-hardware.org/?probe=0ab95fc3f5) | Jan 14, 2024 |
| ASRock        | B550 PG Riptide             | [5221601add](https://linux-hardware.org/?probe=5221601add) | Jan 10, 2024 |
| ASUSTek       | PRIME X570-P                | [4b2d921c9b](https://linux-hardware.org/?probe=4b2d921c9b) | Jan 10, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [c832a7e8f5](https://linux-hardware.org/?probe=c832a7e8f5) | Jan 08, 2024 |
| MSI           | H81M-E33                    | [cced2d2e95](https://linux-hardware.org/?probe=cced2d2e95) | Jan 07, 2024 |
| ASRock        | B550M PG Riptide            | [681b82b48a](https://linux-hardware.org/?probe=681b82b48a) | Jan 06, 2024 |
| ASRock        | B550M PG Riptide            | [bbbedbf6f4](https://linux-hardware.org/?probe=bbbedbf6f4) | Jan 06, 2024 |
| MSI           | MS-7142                     | [679ea97c9a](https://linux-hardware.org/?probe=679ea97c9a) | Jan 04, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | [f4db017a3f](https://linux-hardware.org/?probe=f4db017a3f) | Jan 03, 2024 |
| ASUSTek       | P8H77-M                     | [518d80f081](https://linux-hardware.org/?probe=518d80f081) | Jan 02, 2024 |
| ASRock        | B85M Pro3                   | [f61d357d7f](https://linux-hardware.org/?probe=f61d357d7f) | Dec 29, 2023 |
| ASRock        | 990FX Killer                | [1003211f6d](https://linux-hardware.org/?probe=1003211f6d) | Dec 26, 2023 |
| ASRock        | 990FX Killer                | [034adc4ac8](https://linux-hardware.org/?probe=034adc4ac8) | Dec 26, 2023 |
| Gigabyte      | D525TUD                     | [357709050e](https://linux-hardware.org/?probe=357709050e) | Dec 25, 2023 |
| MSI           | X99A RAIDER                 | [bd10b63ca1](https://linux-hardware.org/?probe=bd10b63ca1) | Dec 25, 2023 |
| MSI           | X99A RAIDER                 | [b150280df5](https://linux-hardware.org/?probe=b150280df5) | Dec 24, 2023 |
| Gigabyte      | D525TUD                     | [dd2248530b](https://linux-hardware.org/?probe=dd2248530b) | Dec 23, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [85087e0568](https://linux-hardware.org/?probe=85087e0568) | Dec 20, 2023 |
| ASRock        | B650M Pro RS                | [df96c996dd](https://linux-hardware.org/?probe=df96c996dd) | Dec 18, 2023 |
| HP            | 8643 SMVB                   | [70ece5f797](https://linux-hardware.org/?probe=70ece5f797) | Dec 18, 2023 |
| MSI           | X99A RAIDER                 | [84c183a024](https://linux-hardware.org/?probe=84c183a024) | Dec 18, 2023 |
| HP            | 8643 SMVB                   | [5082c6046e](https://linux-hardware.org/?probe=5082c6046e) | Dec 18, 2023 |
| MSI           | X99A RAIDER                 | [047995ad80](https://linux-hardware.org/?probe=047995ad80) | Dec 17, 2023 |
| Gigabyte      | D525TUD                     | [34a66d3cef](https://linux-hardware.org/?probe=34a66d3cef) | Dec 15, 2023 |
| Gigabyte      | D525TUD                     | [12c2204715](https://linux-hardware.org/?probe=12c2204715) | Dec 12, 2023 |
| Foxconn       | 2A8C                        | [a467dabfb7](https://linux-hardware.org/?probe=a467dabfb7) | Dec 10, 2023 |
| Foxconn       | 2A8C                        | [78cb902abe](https://linux-hardware.org/?probe=78cb902abe) | Dec 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [665a5984d2](https://linux-hardware.org/?probe=665a5984d2) | Dec 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [dc05a32f3d](https://linux-hardware.org/?probe=dc05a32f3d) | Dec 06, 2023 |
| Lenovo        | ThinkServer TS140           | [c53a3bf5e8](https://linux-hardware.org/?probe=c53a3bf5e8) | Dec 05, 2023 |
| ASUSTek       | Z170-A                      | [8a8bfb131c](https://linux-hardware.org/?probe=8a8bfb131c) | Dec 04, 2023 |
| Dell          | 0WR7PY A01                  | [67b1cc2f69](https://linux-hardware.org/?probe=67b1cc2f69) | Dec 03, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [80be39f0d4](https://linux-hardware.org/?probe=80be39f0d4) | Dec 01, 2023 |
| ASRock        | 970 Extreme4                | [5dd27edbe4](https://linux-hardware.org/?probe=5dd27edbe4) | Nov 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [130735940f](https://linux-hardware.org/?probe=130735940f) | Nov 28, 2023 |
| MSI           | H61M-P31/W8                 | [b74cd41faf](https://linux-hardware.org/?probe=b74cd41faf) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [648a453b3f](https://linux-hardware.org/?probe=648a453b3f) | Nov 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [5693d24a8d](https://linux-hardware.org/?probe=5693d24a8d) | Nov 26, 2023 |
| Dell          | 06D7TR A00                  | [d979c6298f](https://linux-hardware.org/?probe=d979c6298f) | Nov 24, 2023 |
| ASUSTek       | PRIME X370-A                | [27f6e938d0](https://linux-hardware.org/?probe=27f6e938d0) | Nov 23, 2023 |
| MSI           | 760GMA-P34                  | [ebab9eb8e2](https://linux-hardware.org/?probe=ebab9eb8e2) | Nov 23, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [bc7df67b84](https://linux-hardware.org/?probe=bc7df67b84) | Nov 22, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | [7930532d04](https://linux-hardware.org/?probe=7930532d04) | Nov 21, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [84df454a40](https://linux-hardware.org/?probe=84df454a40) | Nov 21, 2023 |
| MSI           | X99A RAIDER                 | [3844682c90](https://linux-hardware.org/?probe=3844682c90) | Nov 21, 2023 |
| Apple         | Mac-F221BEC8                | [7a09806e41](https://linux-hardware.org/?probe=7a09806e41) | Nov 20, 2023 |
| MSI           | X99A RAIDER                 | [fd4876bdbc](https://linux-hardware.org/?probe=fd4876bdbc) | Nov 20, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f8778aa9e9](https://linux-hardware.org/?probe=f8778aa9e9) | Nov 20, 2023 |
| MSI           | Z270I GAMING PRO CARBON ... | [855aed38cb](https://linux-hardware.org/?probe=855aed38cb) | Nov 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [09070d5842](https://linux-hardware.org/?probe=09070d5842) | Nov 18, 2023 |
| ASRock        | X99X Killer                 | [954fe7c236](https://linux-hardware.org/?probe=954fe7c236) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [9503e14877](https://linux-hardware.org/?probe=9503e14877) | Nov 14, 2023 |
| Gigabyte      | H77N-WIFI                   | [c33072abbc](https://linux-hardware.org/?probe=c33072abbc) | Nov 14, 2023 |
| Gigabyte      | Z77MX-D3H                   | [121f68381f](https://linux-hardware.org/?probe=121f68381f) | Nov 14, 2023 |
| eMachines     | EMCP73VT-PM                 | [cd7b8b7a84](https://linux-hardware.org/?probe=cd7b8b7a84) | Nov 14, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [2ed7720fa6](https://linux-hardware.org/?probe=2ed7720fa6) | Nov 13, 2023 |
| HP            | 339B                        | [a3b2a52a12](https://linux-hardware.org/?probe=a3b2a52a12) | Nov 13, 2023 |
| MSI           | B350 GAMING PLUS            | [ffb3d9547e](https://linux-hardware.org/?probe=ffb3d9547e) | Nov 13, 2023 |
| MSI           | B350 GAMING PLUS            | [fb5cb725d6](https://linux-hardware.org/?probe=fb5cb725d6) | Nov 13, 2023 |
| Unknown       | T3 MRD                      | [ae1a1c1e9b](https://linux-hardware.org/?probe=ae1a1c1e9b) | Nov 13, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [edf208cfd3](https://linux-hardware.org/?probe=edf208cfd3) | Nov 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4779217105](https://linux-hardware.org/?probe=4779217105) | Nov 11, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [5cc12c788a](https://linux-hardware.org/?probe=5cc12c788a) | Nov 10, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | [ea4b644bef](https://linux-hardware.org/?probe=ea4b644bef) | Nov 10, 2023 |
| Gigabyte      | A520M DS3H                  | [431101ce2f](https://linux-hardware.org/?probe=431101ce2f) | Nov 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [5c243dae6b](https://linux-hardware.org/?probe=5c243dae6b) | Nov 09, 2023 |
| Gigabyte      | J1900M-D2P                  | [b1610ff76c](https://linux-hardware.org/?probe=b1610ff76c) | Nov 09, 2023 |
| MSI           | H110M ECO                   | [850e3ac421](https://linux-hardware.org/?probe=850e3ac421) | Nov 08, 2023 |
| ASRock        | Z68 Pro3                    | [dbe90ad5d6](https://linux-hardware.org/?probe=dbe90ad5d6) | Nov 08, 2023 |
| ASRock        | 890GM Pro3                  | [e00099e8c5](https://linux-hardware.org/?probe=e00099e8c5) | Nov 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [9e3d070f39](https://linux-hardware.org/?probe=9e3d070f39) | Nov 08, 2023 |
| ASRock        | B550M-C                     | [7d79d732ed](https://linux-hardware.org/?probe=7d79d732ed) | Nov 08, 2023 |
| MSI           | Z370-A PRO                  | [e79bc70a0d](https://linux-hardware.org/?probe=e79bc70a0d) | Nov 07, 2023 |
| MSI           | X99A RAIDER                 | [722c36be7f](https://linux-hardware.org/?probe=722c36be7f) | Nov 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [d63435f6d0](https://linux-hardware.org/?probe=d63435f6d0) | Nov 06, 2023 |
| Lenovo        | 3750 SDK0T76461 WIN 3422... | [995234c08b](https://linux-hardware.org/?probe=995234c08b) | Nov 06, 2023 |
| MSI           | H55M-E33                    | [09ba697574](https://linux-hardware.org/?probe=09ba697574) | Nov 06, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [d57d789e77](https://linux-hardware.org/?probe=d57d789e77) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05a8c22a35](https://linux-hardware.org/?probe=05a8c22a35) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | 1494                        | [93e0e0302f](https://linux-hardware.org/?probe=93e0e0302f) | Nov 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [4998a82a6b](https://linux-hardware.org/?probe=4998a82a6b) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-A II            | [539d8551fc](https://linux-hardware.org/?probe=539d8551fc) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [a9ad2b542a](https://linux-hardware.org/?probe=a9ad2b542a) | Nov 05, 2023 |
| Pegatron      | 2AD5                        | [f8860a91a3](https://linux-hardware.org/?probe=f8860a91a3) | Nov 05, 2023 |
| Gigabyte      | B550M S2H                   | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| Unknown       | Unknown                     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | [2ab63a2fb6](https://linux-hardware.org/?probe=2ab63a2fb6) | Nov 04, 2023 |
| ASUSTek       | H81M-C                      | [cfb51ce306](https://linux-hardware.org/?probe=cfb51ce306) | Nov 03, 2023 |
| HP            | 859C                        | [7928158950](https://linux-hardware.org/?probe=7928158950) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbe345cd5d](https://linux-hardware.org/?probe=bbe345cd5d) | Nov 02, 2023 |
| ASRock        | B760M PG SONIC WiFi         | [71e1e69f30](https://linux-hardware.org/?probe=71e1e69f30) | Nov 02, 2023 |
| MSI           | IONA                        | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| ASUSTek       | M52AD_M12AD                 | [a75715ee4a](https://linux-hardware.org/?probe=a75715ee4a) | Nov 01, 2023 |
| ASRock        | H97M Anniversary            | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [168597b33e](https://linux-hardware.org/?probe=168597b33e) | Nov 01, 2023 |
| HP            | 8767 A                      | [618323a058](https://linux-hardware.org/?probe=618323a058) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| MSI           | B450M PRO-M2 V2             | [7296b22122](https://linux-hardware.org/?probe=7296b22122) | Oct 31, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3b79851103](https://linux-hardware.org/?probe=3b79851103) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3179102373](https://linux-hardware.org/?probe=3179102373) | Oct 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [53e53337bb](https://linux-hardware.org/?probe=53e53337bb) | Oct 30, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [624a99186e](https://linux-hardware.org/?probe=624a99186e) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| ASRock        | 890GM Pro3                  | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [7d0eb8f922](https://linux-hardware.org/?probe=7d0eb8f922) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | [ff941d75c9](https://linux-hardware.org/?probe=ff941d75c9) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | [307134fa91](https://linux-hardware.org/?probe=307134fa91) | Oct 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [deef4da5dc](https://linux-hardware.org/?probe=deef4da5dc) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| ASRock        | X399 Taichi                 | [78ab56301b](https://linux-hardware.org/?probe=78ab56301b) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| ASRock        | Z370 Professional Gaming... | [f589e0c914](https://linux-hardware.org/?probe=f589e0c914) | Oct 28, 2023 |
| HP            | 8053                        | [352cc1bad8](https://linux-hardware.org/?probe=352cc1bad8) | Oct 28, 2023 |
| HP            | 8053                        | [25f2c6e830](https://linux-hardware.org/?probe=25f2c6e830) | Oct 28, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [4562f80268](https://linux-hardware.org/?probe=4562f80268) | Oct 28, 2023 |
| Gigabyte      | Z77-D3H                     | [77541125c0](https://linux-hardware.org/?probe=77541125c0) | Oct 28, 2023 |
| Gigabyte      | D525TUD                     | [944bb2ecb2](https://linux-hardware.org/?probe=944bb2ecb2) | Oct 28, 2023 |
| Gigabyte      | B550 VISION D-P             | [d78b4f6222](https://linux-hardware.org/?probe=d78b4f6222) | Oct 28, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [b18bbae606](https://linux-hardware.org/?probe=b18bbae606) | Oct 27, 2023 |
| HP            | 843F                        | [c39418a5fe](https://linux-hardware.org/?probe=c39418a5fe) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [4eacfc5dd8](https://linux-hardware.org/?probe=4eacfc5dd8) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | [a576bfd0b1](https://linux-hardware.org/?probe=a576bfd0b1) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [fff464540a](https://linux-hardware.org/?probe=fff464540a) | Oct 26, 2023 |
| Dell          | 0KJCC5 A00                  | [f4f5605117](https://linux-hardware.org/?probe=f4f5605117) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ca40b148a0](https://linux-hardware.org/?probe=ca40b148a0) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| HP            | 8433 11                     | [902343e220](https://linux-hardware.org/?probe=902343e220) | Oct 25, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Dell          | 0C27VV A02                  | [7a88945a88](https://linux-hardware.org/?probe=7a88945a88) | Oct 25, 2023 |
| Supermicro    | X8SAX                       | [5d90e1af8c](https://linux-hardware.org/?probe=5d90e1af8c) | Oct 25, 2023 |
| ASRock        | FM2A88X+ Killer             | [c9b5ffd5b8](https://linux-hardware.org/?probe=c9b5ffd5b8) | Oct 24, 2023 |
| ASRock        | B450 Pro4                   | [d4a28890a5](https://linux-hardware.org/?probe=d4a28890a5) | Oct 24, 2023 |
| MSI           | B550-A PRO                  | [ed696b1c52](https://linux-hardware.org/?probe=ed696b1c52) | Oct 24, 2023 |
| ASUSTek       | P5Q3                        | [660547e520](https://linux-hardware.org/?probe=660547e520) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [4e13c711c7](https://linux-hardware.org/?probe=4e13c711c7) | Oct 24, 2023 |
| Acer          | Aspire X1900                | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [4440cac740](https://linux-hardware.org/?probe=4440cac740) | Oct 23, 2023 |
| MSI           | X370 SLI PLUS               | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [7c86d9f1e5](https://linux-hardware.org/?probe=7c86d9f1e5) | Oct 23, 2023 |
| ASRock        | D1800M                      | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [eb9bba4f5c](https://linux-hardware.org/?probe=eb9bba4f5c) | Oct 23, 2023 |
| Gigabyte      | Z77MX-D3H                   | [1f16388df7](https://linux-hardware.org/?probe=1f16388df7) | Oct 23, 2023 |
| MSI           | IONA                        | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| AZW           | SER V1                      | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| MSI           | X99A RAIDER                 | [3ba4cde45a](https://linux-hardware.org/?probe=3ba4cde45a) | Oct 22, 2023 |
| HP            | 83E9                        | [c324d1ee0a](https://linux-hardware.org/?probe=c324d1ee0a) | Oct 22, 2023 |
| HP            | 83E9                        | [8102d00cdc](https://linux-hardware.org/?probe=8102d00cdc) | Oct 22, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [7c383004b6](https://linux-hardware.org/?probe=7c383004b6) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| Shenzhen M... | F6BFC                       | [64148c88c0](https://linux-hardware.org/?probe=64148c88c0) | Oct 21, 2023 |
| MSI           | B450M MORTAR MAX            | [c1ad18b5c9](https://linux-hardware.org/?probe=c1ad18b5c9) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| MSI           | X99A RAIDER                 | [edefe667a4](https://linux-hardware.org/?probe=edefe667a4) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [8290e4c160](https://linux-hardware.org/?probe=8290e4c160) | Oct 20, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [984eba244a](https://linux-hardware.org/?probe=984eba244a) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | [b02f1b04e3](https://linux-hardware.org/?probe=b02f1b04e3) | Oct 19, 2023 |
| MACHINIST     | X99 G7 V1.0                 | [caca14cc52](https://linux-hardware.org/?probe=caca14cc52) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [064dc574bb](https://linux-hardware.org/?probe=064dc574bb) | Oct 18, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [305b104f83](https://linux-hardware.org/?probe=305b104f83) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [0566ab2287](https://linux-hardware.org/?probe=0566ab2287) | Oct 18, 2023 |
| HP            | 2B52                        | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [bb941b90f8](https://linux-hardware.org/?probe=bb941b90f8) | Oct 18, 2023 |
| Gigabyte      | H77N-WIFI                   | [0c16d31374](https://linux-hardware.org/?probe=0c16d31374) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d531813a7a](https://linux-hardware.org/?probe=d531813a7a) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| HP            | 1589                        | [9fca3eb994](https://linux-hardware.org/?probe=9fca3eb994) | Oct 17, 2023 |
| AZW           | SER V1                      | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [8422037a50](https://linux-hardware.org/?probe=8422037a50) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [6f8e6d4251](https://linux-hardware.org/?probe=6f8e6d4251) | Oct 17, 2023 |
| MSI           | MS-1T31                     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| ASUSTek       | PRIME H510M-E               | [375e62bbf4](https://linux-hardware.org/?probe=375e62bbf4) | Oct 17, 2023 |
| HP            | 8AB6 SMVB                   | [e88f9153df](https://linux-hardware.org/?probe=e88f9153df) | Oct 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [3f87e6216a](https://linux-hardware.org/?probe=3f87e6216a) | Oct 16, 2023 |
| MSI           | PRO B650-P WIFI             | [55d07d6ee2](https://linux-hardware.org/?probe=55d07d6ee2) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [66c28b84cf](https://linux-hardware.org/?probe=66c28b84cf) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [982543f4bc](https://linux-hardware.org/?probe=982543f4bc) | Oct 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [d294330c51](https://linux-hardware.org/?probe=d294330c51) | Oct 16, 2023 |
| ASRock        | A320M-HDV R4.0              | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [37983381b0](https://linux-hardware.org/?probe=37983381b0) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5330b349cb](https://linux-hardware.org/?probe=5330b349cb) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [8bbdd141fe](https://linux-hardware.org/?probe=8bbdd141fe) | Oct 15, 2023 |
| HP            | 1589                        | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| MSI           | PRO B660M-P DDR4            | [364fd8849a](https://linux-hardware.org/?probe=364fd8849a) | Oct 15, 2023 |
| Gigabyte      | J1900M-D2P                  | [27881eaaac](https://linux-hardware.org/?probe=27881eaaac) | Oct 15, 2023 |
| Dell          | 0TY915                      | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [7e4e4b6a5d](https://linux-hardware.org/?probe=7e4e4b6a5d) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | [b5d7147862](https://linux-hardware.org/?probe=b5d7147862) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | [642ecadbd2](https://linux-hardware.org/?probe=642ecadbd2) | Oct 15, 2023 |
| Dell          | 0Y2K8N A01                  | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [70b85fc17d](https://linux-hardware.org/?probe=70b85fc17d) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [039e898b5d](https://linux-hardware.org/?probe=039e898b5d) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [2edd75be93](https://linux-hardware.org/?probe=2edd75be93) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| ASRock        | H87 Performance             | [5d1713de03](https://linux-hardware.org/?probe=5d1713de03) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f24ebc31a5](https://linux-hardware.org/?probe=f24ebc31a5) | Oct 13, 2023 |
| Dell          | 0WR7PY A03                  | [f59286c03f](https://linux-hardware.org/?probe=f59286c03f) | Oct 13, 2023 |
| MSI           | A68HM-E33                   | [71c8888ea4](https://linux-hardware.org/?probe=71c8888ea4) | Oct 12, 2023 |
| Gigabyte      | X570S UD                    | [c7b68dbfe1](https://linux-hardware.org/?probe=c7b68dbfe1) | Oct 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| HP            | 843B                        | [652027900b](https://linux-hardware.org/?probe=652027900b) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [3ceccfff97](https://linux-hardware.org/?probe=3ceccfff97) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Gigabyte      | J1900M-D2P                  | [8091bb0ceb](https://linux-hardware.org/?probe=8091bb0ceb) | Oct 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [19f6294d43](https://linux-hardware.org/?probe=19f6294d43) | Oct 10, 2023 |
| HP            | 89B5 A                      | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| ASRock        | B365M IB-R                  | [c1ac8c374a](https://linux-hardware.org/?probe=c1ac8c374a) | Oct 10, 2023 |
| Techvision    | TVI7309X B0                 | [5954b70bb9](https://linux-hardware.org/?probe=5954b70bb9) | Oct 10, 2023 |
| MSI           | A320M-A PRO                 | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Dell          | 0DF42J A00                  | [830730801b](https://linux-hardware.org/?probe=830730801b) | Oct 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7aa0b01da6](https://linux-hardware.org/?probe=7aa0b01da6) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [b249985c20](https://linux-hardware.org/?probe=b249985c20) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [90b88ff378](https://linux-hardware.org/?probe=90b88ff378) | Oct 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7070641150](https://linux-hardware.org/?probe=7070641150) | Oct 08, 2023 |
| Gigabyte      | F2A55M-DS2                  | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [26708ac497](https://linux-hardware.org/?probe=26708ac497) | Oct 08, 2023 |
| Gigabyte      | H310M S2H x.x               | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| Gigabyte      | B550 VISION D-P             | [b0a2980430](https://linux-hardware.org/?probe=b0a2980430) | Oct 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [d43dc626c0](https://linux-hardware.org/?probe=d43dc626c0) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [998f01f73b](https://linux-hardware.org/?probe=998f01f73b) | Oct 08, 2023 |
| HP            | 158A                        | [a1c0d51b9d](https://linux-hardware.org/?probe=a1c0d51b9d) | Oct 08, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [0d980c4a61](https://linux-hardware.org/?probe=0d980c4a61) | Oct 07, 2023 |
| Acer          | Aspire X1900                | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| Gigabyte      | H81M-D2V                    | [a41f086304](https://linux-hardware.org/?probe=a41f086304) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6bf5869cab](https://linux-hardware.org/?probe=6bf5869cab) | Oct 06, 2023 |
| Dell          | 0N4YC8 A00                  | [76c6fdfad6](https://linux-hardware.org/?probe=76c6fdfad6) | Oct 06, 2023 |
| MSI           | B450M MORTAR MAX            | [a2fb75cc3e](https://linux-hardware.org/?probe=a2fb75cc3e) | Oct 06, 2023 |
| Medion        | MS-7707                     | [42bc6357f7](https://linux-hardware.org/?probe=42bc6357f7) | Oct 05, 2023 |
| HP            | 8906 SMVB                   | [010c54ccaf](https://linux-hardware.org/?probe=010c54ccaf) | Oct 05, 2023 |
| Dell          | 0478VN A00                  | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9948b7ed73](https://linux-hardware.org/?probe=9948b7ed73) | Oct 05, 2023 |
| Dell          | 0N4YC8 A00                  | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [d8f9e7b32a](https://linux-hardware.org/?probe=d8f9e7b32a) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [ae798c007e](https://linux-hardware.org/?probe=ae798c007e) | Oct 05, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [0aa9a5ddc3](https://linux-hardware.org/?probe=0aa9a5ddc3) | Oct 05, 2023 |
| ASRock        | AD2700-ITX                  | [3aea9e7d2f](https://linux-hardware.org/?probe=3aea9e7d2f) | Oct 05, 2023 |
| Shenzhen M... | HX90G                       | [135859015c](https://linux-hardware.org/?probe=135859015c) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [08f5cef7f3](https://linux-hardware.org/?probe=08f5cef7f3) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| Dell          | 0DF42J A00                  | [a98397577c](https://linux-hardware.org/?probe=a98397577c) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [400e01b1bf](https://linux-hardware.org/?probe=400e01b1bf) | Oct 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [b225569c1d](https://linux-hardware.org/?probe=b225569c1d) | Oct 02, 2023 |
| Dell          | 0YJPT1 A00                  | [59f53b1488](https://linux-hardware.org/?probe=59f53b1488) | Oct 02, 2023 |
| Dell          | 07PR60 A01                  | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| Unknown       | Unknown                     | [1f2e2a6b13](https://linux-hardware.org/?probe=1f2e2a6b13) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| Intel         | H110                        | [eaf6f0f81c](https://linux-hardware.org/?probe=eaf6f0f81c) | Oct 02, 2023 |
| Acer          | Aspire X1900                | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| MSI           | X99A RAIDER                 | [5442de3655](https://linux-hardware.org/?probe=5442de3655) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b27cfa6ad6](https://linux-hardware.org/?probe=b27cfa6ad6) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [45b94d86b5](https://linux-hardware.org/?probe=45b94d86b5) | Oct 02, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [10e1561364](https://linux-hardware.org/?probe=10e1561364) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| ASUSTek       | PRIME B450M-A               | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| HP            | 8055                        | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Intel         | H61                         | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Intel         | H61                         | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| Dell          | 0YJPT1 A00                  | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Gigabyte      | B550M S2H                   | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Gigabyte      | B550M DS3H                  | [3bb1109d44](https://linux-hardware.org/?probe=3bb1109d44) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [4b0aff27e8](https://linux-hardware.org/?probe=4b0aff27e8) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| ASRock        | B450M Steel Legend          | [ccb7f736f6](https://linux-hardware.org/?probe=ccb7f736f6) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| MSI           | X99A RAIDER                 | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| ASUSTek       | P9D WS                      | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b7dae6ef48](https://linux-hardware.org/?probe=b7dae6ef48) | Sep 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [f4d45948eb](https://linux-hardware.org/?probe=f4d45948eb) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [1b8b856469](https://linux-hardware.org/?probe=1b8b856469) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [23d9e87224](https://linux-hardware.org/?probe=23d9e87224) | Sep 24, 2023 |
| Gigabyte      | X570S UD                    | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | [7c0eb47c16](https://linux-hardware.org/?probe=7c0eb47c16) | Sep 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5ed3f9381a](https://linux-hardware.org/?probe=5ed3f9381a) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| ASRock        | N68C-S UCC                  | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f59df7021c](https://linux-hardware.org/?probe=f59df7021c) | Sep 23, 2023 |
| Gigabyte      | MZGLKBP-00                  | [678c17756d](https://linux-hardware.org/?probe=678c17756d) | Sep 23, 2023 |
| ASRock        | H61M/U3S3                   | [1d397abb90](https://linux-hardware.org/?probe=1d397abb90) | Sep 23, 2023 |
| Gigabyte      | B85-HD3                     | [5da83e8683](https://linux-hardware.org/?probe=5da83e8683) | Sep 23, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [5629e161ab](https://linux-hardware.org/?probe=5629e161ab) | Sep 23, 2023 |
| MSI           | MS-7388                     | [f5ee235af0](https://linux-hardware.org/?probe=f5ee235af0) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | [1a81f24fbb](https://linux-hardware.org/?probe=1a81f24fbb) | Sep 23, 2023 |
| Dell          | 0KWVT8 A03                  | [c6f224508a](https://linux-hardware.org/?probe=c6f224508a) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | [3b9bbcebb0](https://linux-hardware.org/?probe=3b9bbcebb0) | Sep 23, 2023 |
| MSI           | H110M PRO-D                 | [40380b4dce](https://linux-hardware.org/?probe=40380b4dce) | Sep 22, 2023 |
| HP            | 834F                        | [b69b667f2c](https://linux-hardware.org/?probe=b69b667f2c) | Sep 22, 2023 |
| Gigabyte      | H61M-S2PV                   | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| ASUSTek       | PRIME X570-P                | [21b73523cf](https://linux-hardware.org/?probe=21b73523cf) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [80c7b750ea](https://linux-hardware.org/?probe=80c7b750ea) | Sep 21, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [609a91b51f](https://linux-hardware.org/?probe=609a91b51f) | Sep 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| Intel         | B75                         | [37b59e6605](https://linux-hardware.org/?probe=37b59e6605) | Sep 21, 2023 |
| HP            | 1495                        | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| HP            | 3047h                       | [cb19fdc589](https://linux-hardware.org/?probe=cb19fdc589) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| Gigabyte      | B360M D3H-CF                | [875f4f3f2a](https://linux-hardware.org/?probe=875f4f3f2a) | Sep 21, 2023 |
| ASUSTek       | V230IC                      | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| MSI           | Z270M MORTAR                | [ec0adfb60f](https://linux-hardware.org/?probe=ec0adfb60f) | Sep 21, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [5e05853c00](https://linux-hardware.org/?probe=5e05853c00) | Sep 20, 2023 |
| HP            | 3397                        | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| Dell          | 0WN7Y6 A01                  | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | [624ebbd6c1](https://linux-hardware.org/?probe=624ebbd6c1) | Sep 20, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [238224ef08](https://linux-hardware.org/?probe=238224ef08) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Dell          | 06HR05 A00                  | [a01d6b8630](https://linux-hardware.org/?probe=a01d6b8630) | Sep 20, 2023 |
| MSI           | A320M-A PRO MAX             | [411b34f287](https://linux-hardware.org/?probe=411b34f287) | Sep 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [56d2a67030](https://linux-hardware.org/?probe=56d2a67030) | Sep 19, 2023 |
| Gigabyte      | J1900M-D2P                  | [1bd6653d3e](https://linux-hardware.org/?probe=1bd6653d3e) | Sep 19, 2023 |
| Positivo      | POS-EIH610EX 11187943       | [10fbe8fd9b](https://linux-hardware.org/?probe=10fbe8fd9b) | Sep 18, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [39d6e8a728](https://linux-hardware.org/?probe=39d6e8a728) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [7e05f3299f](https://linux-hardware.org/?probe=7e05f3299f) | Sep 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [517795acfd](https://linux-hardware.org/?probe=517795acfd) | Sep 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5597daf348](https://linux-hardware.org/?probe=5597daf348) | Sep 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [b0de1885b9](https://linux-hardware.org/?probe=b0de1885b9) | Sep 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8566235f94](https://linux-hardware.org/?probe=8566235f94) | Sep 17, 2023 |
| Dell          | 0MGK50 A02                  | [ec87c19874](https://linux-hardware.org/?probe=ec87c19874) | Sep 17, 2023 |
| ASRock        | B450 Pro4                   | [2e8cd612d8](https://linux-hardware.org/?probe=2e8cd612d8) | Sep 17, 2023 |
| ASUSTek       | PRIME H270-PRO              | [394d932643](https://linux-hardware.org/?probe=394d932643) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [83c2fb6018](https://linux-hardware.org/?probe=83c2fb6018) | Sep 16, 2023 |
| Intel         | DQ45CB AAE30148-207         | [2c74d735db](https://linux-hardware.org/?probe=2c74d735db) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| HP            | 3397                        | [3cf175e939](https://linux-hardware.org/?probe=3cf175e939) | Sep 14, 2023 |
| MSI           | 2A9C                        | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| ASRock        | B450M-HDV R4.0              | [305679af22](https://linux-hardware.org/?probe=305679af22) | Sep 14, 2023 |
| HP            | 8459                        | [e7cbc6d34d](https://linux-hardware.org/?probe=e7cbc6d34d) | Sep 14, 2023 |
| Dell          | 0YXT71 A02                  | [f462fe5985](https://linux-hardware.org/?probe=f462fe5985) | Sep 14, 2023 |
| Intel         | DH87MC AAG74242-401         | [6c37cc0b51](https://linux-hardware.org/?probe=6c37cc0b51) | Sep 14, 2023 |
| HP            | 843B                        | [08ce9ca0eb](https://linux-hardware.org/?probe=08ce9ca0eb) | Sep 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | [746f94b75d](https://linux-hardware.org/?probe=746f94b75d) | Sep 13, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [035fb7f099](https://linux-hardware.org/?probe=035fb7f099) | Sep 13, 2023 |
| MSI           | MAG B460M MORTAR            | [c0980eee03](https://linux-hardware.org/?probe=c0980eee03) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | [20ec05f55b](https://linux-hardware.org/?probe=20ec05f55b) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [a7e93922ce](https://linux-hardware.org/?probe=a7e93922ce) | Sep 13, 2023 |
| Acer          | F690GVM                     | [a9a370c528](https://linux-hardware.org/?probe=a9a370c528) | Sep 13, 2023 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [fd4e189b56](https://linux-hardware.org/?probe=fd4e189b56) | Sep 12, 2023 |
| Gigabyte      | B450M S2H                   | [9099ebc0a7](https://linux-hardware.org/?probe=9099ebc0a7) | Sep 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | [e1eea73611](https://linux-hardware.org/?probe=e1eea73611) | Sep 12, 2023 |
| HP            | 3397                        | [ed9caadb58](https://linux-hardware.org/?probe=ed9caadb58) | Sep 12, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [f5b3cd74bc](https://linux-hardware.org/?probe=f5b3cd74bc) | Sep 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [baeb174dc3](https://linux-hardware.org/?probe=baeb174dc3) | Sep 10, 2023 |
| ASRock        | B550M Pro4                  | [92eb1e3aa7](https://linux-hardware.org/?probe=92eb1e3aa7) | Sep 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [6dc842bbb4](https://linux-hardware.org/?probe=6dc842bbb4) | Sep 10, 2023 |
| Dell          | 042P49 A01                  | [fc47b9c2f4](https://linux-hardware.org/?probe=fc47b9c2f4) | Sep 10, 2023 |
| Acer          | Veriton M2631 V:1.0         | [ec947814d1](https://linux-hardware.org/?probe=ec947814d1) | Sep 10, 2023 |
| ASRock        | H570M Pro4                  | [4124ca4b35](https://linux-hardware.org/?probe=4124ca4b35) | Sep 10, 2023 |
| Dell          | 084J0R A00                  | [25d0f0d7ef](https://linux-hardware.org/?probe=25d0f0d7ef) | Sep 10, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [7b441b9b50](https://linux-hardware.org/?probe=7b441b9b50) | Sep 10, 2023 |
| MSI           | MPG Z790I EDGE WIFI         | [1225463e4a](https://linux-hardware.org/?probe=1225463e4a) | Sep 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [7d3f7effe2](https://linux-hardware.org/?probe=7d3f7effe2) | Sep 09, 2023 |
| Unknown       | Unknown                     | [aa67f256bc](https://linux-hardware.org/?probe=aa67f256bc) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c8e3d0d7f9](https://linux-hardware.org/?probe=c8e3d0d7f9) | Sep 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [b15cd2d6e5](https://linux-hardware.org/?probe=b15cd2d6e5) | Sep 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [d6302862b1](https://linux-hardware.org/?probe=d6302862b1) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [fc7937d763](https://linux-hardware.org/?probe=fc7937d763) | Sep 09, 2023 |
| ASRock        | B450M Pro4                  | [a47195331c](https://linux-hardware.org/?probe=a47195331c) | Sep 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [b5081191af](https://linux-hardware.org/?probe=b5081191af) | Sep 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6e57fc6cf2](https://linux-hardware.org/?probe=6e57fc6cf2) | Sep 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [03a233a395](https://linux-hardware.org/?probe=03a233a395) | Sep 08, 2023 |
| HP            | ProLiant ML110 G7           | [5f806b31b4](https://linux-hardware.org/?probe=5f806b31b4) | Sep 08, 2023 |
| Gigabyte      | G41MT-D3                    | [0940dc7ebd](https://linux-hardware.org/?probe=0940dc7ebd) | Sep 08, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [860985ecc0](https://linux-hardware.org/?probe=860985ecc0) | Sep 08, 2023 |
| MSI           | X99A RAIDER                 | [362b2dadfc](https://linux-hardware.org/?probe=362b2dadfc) | Sep 08, 2023 |
| HP            | 1497                        | [1729554f58](https://linux-hardware.org/?probe=1729554f58) | Sep 07, 2023 |
| Dell          | 0J37VM A01                  | [7781be38be](https://linux-hardware.org/?probe=7781be38be) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d98f5a5a06](https://linux-hardware.org/?probe=d98f5a5a06) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [35b6b3a9dd](https://linux-hardware.org/?probe=35b6b3a9dd) | Sep 07, 2023 |
| Dell          | 0NDYHG A01                  | [250bc7b8ea](https://linux-hardware.org/?probe=250bc7b8ea) | Sep 07, 2023 |
| NZXT          | N7 Z370                     | [34a23bdc5f](https://linux-hardware.org/?probe=34a23bdc5f) | Sep 07, 2023 |
| Dell          | 088DT1 A01                  | [e7d12d040e](https://linux-hardware.org/?probe=e7d12d040e) | Sep 07, 2023 |
| MSI           | X99A RAIDER                 | [0434d08b59](https://linux-hardware.org/?probe=0434d08b59) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [b17a5edce5](https://linux-hardware.org/?probe=b17a5edce5) | Sep 06, 2023 |
| Pegatron      | 2AB6                        | [40b17904fa](https://linux-hardware.org/?probe=40b17904fa) | Sep 06, 2023 |
| HP            | 3047h                       | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| HP            | 3047h                       | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Pegatron      | TRUCKEE                     | [145414b8e3](https://linux-hardware.org/?probe=145414b8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [7b99e058ff](https://linux-hardware.org/?probe=7b99e058ff) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| MSI           | A320M PRO-VH PLUS           | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| MSI           | X99A RAIDER                 | [c06fdd0648](https://linux-hardware.org/?probe=c06fdd0648) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| ASRock        | H310M-STX                   | [5585353638](https://linux-hardware.org/?probe=5585353638) | Sep 04, 2023 |
| ASUSTek       | X99-M WS                    | [f324b3dd33](https://linux-hardware.org/?probe=f324b3dd33) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [d99ec42689](https://linux-hardware.org/?probe=d99ec42689) | Sep 04, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [59b20fdfab](https://linux-hardware.org/?probe=59b20fdfab) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| MSI           | X99A RAIDER                 | [6bf9db20f8](https://linux-hardware.org/?probe=6bf9db20f8) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [2252b35243](https://linux-hardware.org/?probe=2252b35243) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [dd19cc0d48](https://linux-hardware.org/?probe=dd19cc0d48) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [fc0731667e](https://linux-hardware.org/?probe=fc0731667e) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [5e3f2f01d4](https://linux-hardware.org/?probe=5e3f2f01d4) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [926751fb6e](https://linux-hardware.org/?probe=926751fb6e) | Sep 03, 2023 |
| Gigabyte      | X79-UP4                     | [3593994f4e](https://linux-hardware.org/?probe=3593994f4e) | Sep 03, 2023 |
| Dell          | 0HHV7N A00                  | [9ae746229d](https://linux-hardware.org/?probe=9ae746229d) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [c4c911d725](https://linux-hardware.org/?probe=c4c911d725) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [bc7e99e576](https://linux-hardware.org/?probe=bc7e99e576) | Sep 02, 2023 |
| Gigabyte      | MZGLKBP-00                  | [e6c5ae208f](https://linux-hardware.org/?probe=e6c5ae208f) | Sep 02, 2023 |
| Dell          | 0GY6Y8 A01                  | [f592e65a04](https://linux-hardware.org/?probe=f592e65a04) | Sep 02, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [d7fcde026e](https://linux-hardware.org/?probe=d7fcde026e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| HP            | 89B5 A                      | [3b6a46c308](https://linux-hardware.org/?probe=3b6a46c308) | Sep 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [90be513b41](https://linux-hardware.org/?probe=90be513b41) | Sep 01, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [62d1008e3a](https://linux-hardware.org/?probe=62d1008e3a) | Sep 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [81e9e055de](https://linux-hardware.org/?probe=81e9e055de) | Sep 01, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a4ee14b9ac](https://linux-hardware.org/?probe=a4ee14b9ac) | Sep 01, 2023 |
| Unknown       | H110M2                      | [bff031410a](https://linux-hardware.org/?probe=bff031410a) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| Gigabyte      | Z270X-Gaming K5             | [189647b3df](https://linux-hardware.org/?probe=189647b3df) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | [f5aaee7de3](https://linux-hardware.org/?probe=f5aaee7de3) | Aug 31, 2023 |
| ASUSTek       | PHOENIX                     | [5fa96dfd97](https://linux-hardware.org/?probe=5fa96dfd97) | Aug 31, 2023 |
| Gigabyte      | MZGLKBP-00                  | [2ed0efb0a0](https://linux-hardware.org/?probe=2ed0efb0a0) | Aug 31, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [04d647ae08](https://linux-hardware.org/?probe=04d647ae08) | Aug 30, 2023 |
| Dell          | 0J2J3Y A00                  | [57ac609885](https://linux-hardware.org/?probe=57ac609885) | Aug 30, 2023 |
| Gigabyte      | Z270X-Gaming K5             | [193a50f761](https://linux-hardware.org/?probe=193a50f761) | Aug 30, 2023 |
| MSI           | H110M PRO-VD PLUS           | [a75e60a457](https://linux-hardware.org/?probe=a75e60a457) | Aug 30, 2023 |
| ASUSTek       | PRIME Z490-A                | [3cfa79235e](https://linux-hardware.org/?probe=3cfa79235e) | Aug 30, 2023 |
| MSI           | Z270M MORTAR                | [416723b60c](https://linux-hardware.org/?probe=416723b60c) | Aug 30, 2023 |
| Gigabyte      | G41MT-D3                    | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [1fd98a124f](https://linux-hardware.org/?probe=1fd98a124f) | Aug 29, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7674d12aa5](https://linux-hardware.org/?probe=7674d12aa5) | Aug 28, 2023 |
| Fujitsu       | D3817-A1 S26361-D3817-A1... | [50e64dbfa2](https://linux-hardware.org/?probe=50e64dbfa2) | Aug 28, 2023 |
| ASRock        | Z690 Pro RS                 | [b68e4634b7](https://linux-hardware.org/?probe=b68e4634b7) | Aug 28, 2023 |
| Gigabyte      | EP45-DS3L                   | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Acer          | Veriton X2631G V:1.0        | [47b9d876af](https://linux-hardware.org/?probe=47b9d876af) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| MSI           | MS-7388                     | [42530086f2](https://linux-hardware.org/?probe=42530086f2) | Aug 27, 2023 |
| Dell          | 04Y8V0 A02                  | [629b07f8bc](https://linux-hardware.org/?probe=629b07f8bc) | Aug 27, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f71c3553e6](https://linux-hardware.org/?probe=f71c3553e6) | Aug 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [08748d2c86](https://linux-hardware.org/?probe=08748d2c86) | Aug 27, 2023 |
| ASUSTek       | Z170-P                      | [9e90f8b308](https://linux-hardware.org/?probe=9e90f8b308) | Aug 26, 2023 |
| AZW           | U59                         | [ea7bf087cc](https://linux-hardware.org/?probe=ea7bf087cc) | Aug 26, 2023 |
| AZW           | U59                         | [d35717e2e4](https://linux-hardware.org/?probe=d35717e2e4) | Aug 26, 2023 |
| ASRock        | B560 Steel Legend           | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [771adfa310](https://linux-hardware.org/?probe=771adfa310) | Aug 25, 2023 |
| MSI           | MS-7388                     | [5c1e4b0c2b](https://linux-hardware.org/?probe=5c1e4b0c2b) | Aug 25, 2023 |
| Acer          | Veriton N4640G              | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| HP            | 3047h                       | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Dell          | 088DT1 A01                  | [0d9ddb7de2](https://linux-hardware.org/?probe=0d9ddb7de2) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [ba401056e8](https://linux-hardware.org/?probe=ba401056e8) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [d51fb378a1](https://linux-hardware.org/?probe=d51fb378a1) | Aug 24, 2023 |
| MSI           | A320M-A PRO                 | [25dc707bff](https://linux-hardware.org/?probe=25dc707bff) | Aug 24, 2023 |
| ASRock        | B560M-ITX/ac                | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| AZW           | GTR V02                     | [6c91212b1a](https://linux-hardware.org/?probe=6c91212b1a) | Aug 24, 2023 |
| ASRock        | FP6D4-P1                    | [722789f2ac](https://linux-hardware.org/?probe=722789f2ac) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| MSI           | B550-A PRO                  | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| Gigabyte      | B85M-D3V-A                  | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| MSI           | Z370-OC PRO                 | [4ee0bb1c63](https://linux-hardware.org/?probe=4ee0bb1c63) | Aug 23, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [64f3da359d](https://linux-hardware.org/?probe=64f3da359d) | Aug 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [73a003bf4b](https://linux-hardware.org/?probe=73a003bf4b) | Aug 22, 2023 |
| MSI           | Z370-OC PRO                 | [bbd85c94d6](https://linux-hardware.org/?probe=bbd85c94d6) | Aug 22, 2023 |
| ASUSTek       | B460M-N                     | [382640772b](https://linux-hardware.org/?probe=382640772b) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [05c761f480](https://linux-hardware.org/?probe=05c761f480) | Aug 22, 2023 |
| Intel         | DH77EB AAG39073-304         | [70399bc4c6](https://linux-hardware.org/?probe=70399bc4c6) | Aug 21, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [fdfc3b92f9](https://linux-hardware.org/?probe=fdfc3b92f9) | Aug 21, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [09d57c6701](https://linux-hardware.org/?probe=09d57c6701) | Aug 21, 2023 |
| HP            | 3048h                       | [959637abde](https://linux-hardware.org/?probe=959637abde) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [735e03f0f9](https://linux-hardware.org/?probe=735e03f0f9) | Aug 21, 2023 |
| MSI           | PRO B650M-A WIFI            | [da3f4808a1](https://linux-hardware.org/?probe=da3f4808a1) | Aug 20, 2023 |
| ASRock        | A520M-HDV                   | [cb333c6fae](https://linux-hardware.org/?probe=cb333c6fae) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | [c3a8668cee](https://linux-hardware.org/?probe=c3a8668cee) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | [7da89c9360](https://linux-hardware.org/?probe=7da89c9360) | Aug 20, 2023 |
| MSI           | H310M PRO-VDH               | [c6f278a589](https://linux-hardware.org/?probe=c6f278a589) | Aug 20, 2023 |
| HP            | 3032h                       | [f3292df409](https://linux-hardware.org/?probe=f3292df409) | Aug 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [1b7a1416fc](https://linux-hardware.org/?probe=1b7a1416fc) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | [645bd9ed6b](https://linux-hardware.org/?probe=645bd9ed6b) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [978af80f5a](https://linux-hardware.org/?probe=978af80f5a) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [06daace50c](https://linux-hardware.org/?probe=06daace50c) | Aug 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [a15e796833](https://linux-hardware.org/?probe=a15e796833) | Aug 19, 2023 |
| ASUSTek       | M4A77                       | [89bb5a2821](https://linux-hardware.org/?probe=89bb5a2821) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [c99b76f9fe](https://linux-hardware.org/?probe=c99b76f9fe) | Aug 19, 2023 |
| Gigabyte      | B450M H                     | [722707e986](https://linux-hardware.org/?probe=722707e986) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Dell          | 06D7TR A00                  | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| ASUSTek       | Z97-PRO                     | [607356bb8f](https://linux-hardware.org/?probe=607356bb8f) | Aug 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [8958908392](https://linux-hardware.org/?probe=8958908392) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [4b8894823c](https://linux-hardware.org/?probe=4b8894823c) | Aug 17, 2023 |
| ASUSTek       | Pro B550M-C                 | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [ae88c56896](https://linux-hardware.org/?probe=ae88c56896) | Aug 17, 2023 |
| ASRock        | A320M-HD R4.0               | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Dell          | 0VRWRC A00                  | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [725cdd1013](https://linux-hardware.org/?probe=725cdd1013) | Aug 16, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [1ff9bff198](https://linux-hardware.org/?probe=1ff9bff198) | Aug 15, 2023 |
| HP            | 3047h                       | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [4ac83eed41](https://linux-hardware.org/?probe=4ac83eed41) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [6e7b731daa](https://linux-hardware.org/?probe=6e7b731daa) | Aug 15, 2023 |
| Medion        | MS-7800                     | [afab92f1e4](https://linux-hardware.org/?probe=afab92f1e4) | Aug 14, 2023 |
| MSI           | H510M PRO                   | [df350cd466](https://linux-hardware.org/?probe=df350cd466) | Aug 14, 2023 |
| Lenovo        | 1046 SBB1C50531 WIN 3556... | [f24668bfd7](https://linux-hardware.org/?probe=f24668bfd7) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [cc343d2dce](https://linux-hardware.org/?probe=cc343d2dce) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A               | [361ad7057c](https://linux-hardware.org/?probe=361ad7057c) | Aug 13, 2023 |
| MSI           | X99A RAIDER                 | [88056b62e3](https://linux-hardware.org/?probe=88056b62e3) | Aug 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [45cb1198bb](https://linux-hardware.org/?probe=45cb1198bb) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [57a63573fc](https://linux-hardware.org/?probe=57a63573fc) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [22690b9d65](https://linux-hardware.org/?probe=22690b9d65) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Unknown       | Unknown                     | [4b174f07d2](https://linux-hardware.org/?probe=4b174f07d2) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [7da6954bc5](https://linux-hardware.org/?probe=7da6954bc5) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| Unknown       | Unknown                     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [466419add0](https://linux-hardware.org/?probe=466419add0) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Unknown       | HX90                        | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| Gigabyte      | H510M S2H                   | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| HP            | 3397                        | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| ASUSTek       | PHOENIX                     | [388bcf4158](https://linux-hardware.org/?probe=388bcf4158) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3d4073bb1d](https://linux-hardware.org/?probe=3d4073bb1d) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [932391bfea](https://linux-hardware.org/?probe=932391bfea) | Aug 06, 2023 |
| Gateway       | SX2185                      | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40bc2f506a](https://linux-hardware.org/?probe=40bc2f506a) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [364b15d850](https://linux-hardware.org/?probe=364b15d850) | Aug 05, 2023 |
| Intel         | B75                         | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| ASUSTek       | PHOENIX                     | [193262b7ea](https://linux-hardware.org/?probe=193262b7ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| AZW           | GTR V02                     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| Dell          | 05XGC8 A01                  | [de1c7d119e](https://linux-hardware.org/?probe=de1c7d119e) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [c0a4bb6c7e](https://linux-hardware.org/?probe=c0a4bb6c7e) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| HP            | 1791                        | [61285d3724](https://linux-hardware.org/?probe=61285d3724) | Aug 03, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [2d10ecdff1](https://linux-hardware.org/?probe=2d10ecdff1) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3f5df1b569](https://linux-hardware.org/?probe=3f5df1b569) | Aug 03, 2023 |
| ASRock        | Z170 Gaming K4              | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c66b1ed22c](https://linux-hardware.org/?probe=c66b1ed22c) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| MSI           | B450M BAZOOKA V2            | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| Unknown       | Unknown                     | [7a5ef06c39](https://linux-hardware.org/?probe=7a5ef06c39) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [afbf5d75c1](https://linux-hardware.org/?probe=afbf5d75c1) | Jul 31, 2023 |
| ASRock        | H110M-HG4                   | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a3bbf1ecd0](https://linux-hardware.org/?probe=a3bbf1ecd0) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| HP            | 8056                        | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| HP            | 0AECh D                     | [50c84d005e](https://linux-hardware.org/?probe=50c84d005e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| HP            | 8617                        | [0c3ee28cd8](https://linux-hardware.org/?probe=0c3ee28cd8) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| HP            | 3397                        | [98e4e362d9](https://linux-hardware.org/?probe=98e4e362d9) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| ASRock        | H110M-HG4                   | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Gigabyte      | B550 GAMING X V2            | [dcd24dfdc7](https://linux-hardware.org/?probe=dcd24dfdc7) | Jul 28, 2023 |
| ASUSTek       | WS C246 PRO                 | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [2e0e88694a](https://linux-hardware.org/?probe=2e0e88694a) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [f7c6565b62](https://linux-hardware.org/?probe=f7c6565b62) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [49daa98623](https://linux-hardware.org/?probe=49daa98623) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| ASUSTek       | PHOENIX                     | [aad7b03818](https://linux-hardware.org/?probe=aad7b03818) | Jul 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [02cf19407b](https://linux-hardware.org/?probe=02cf19407b) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| MSI           | A520M-A PRO                 | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [0ecaae8a05](https://linux-hardware.org/?probe=0ecaae8a05) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| Unknown       | Unknown                     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| ASUSTek       | PHOENIX                     | [66ab03991c](https://linux-hardware.org/?probe=66ab03991c) | Jul 24, 2023 |
| Gigabyte      | B75M-D2V                    | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [b892c011a8](https://linux-hardware.org/?probe=b892c011a8) | Jul 24, 2023 |
| ASRock        | Z690 Pro RS                 | [2afa2c2afe](https://linux-hardware.org/?probe=2afa2c2afe) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [e1f3c75353](https://linux-hardware.org/?probe=e1f3c75353) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z370-A                | [9a2136d9ef](https://linux-hardware.org/?probe=9a2136d9ef) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Dell          | 06D7TR A00                  | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [51ca7593a6](https://linux-hardware.org/?probe=51ca7593a6) | Jul 22, 2023 |
| Kllisre       | X99-B5 V1.1                 | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [8c79a454ff](https://linux-hardware.org/?probe=8c79a454ff) | Jul 21, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| MSI           | PRO B550-VC                 | [5439295c30](https://linux-hardware.org/?probe=5439295c30) | Jul 20, 2023 |
| ASUSTek       | PRIME Z270-P                | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| ASRock        | B450M Pro4 R2.0             | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [0296e5fd5c](https://linux-hardware.org/?probe=0296e5fd5c) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3618885533](https://linux-hardware.org/?probe=3618885533) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| MSI           | IONA                        | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [bb84df2364](https://linux-hardware.org/?probe=bb84df2364) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [b8caf7c9a3](https://linux-hardware.org/?probe=b8caf7c9a3) | Jul 18, 2023 |
| HP            | 3048h                       | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [49e298a314](https://linux-hardware.org/?probe=49e298a314) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [d8595efd58](https://linux-hardware.org/?probe=d8595efd58) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| Dell          | 0WMJ54 A01                  | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| MSI           | 2A9C                        | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| HP            | ProLiant ML110 G7           | [2278b34727](https://linux-hardware.org/?probe=2278b34727) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| ASRock        | Z690 Pro RS                 | [3becbb23af](https://linux-hardware.org/?probe=3becbb23af) | Jul 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [14bae4d3e7](https://linux-hardware.org/?probe=14bae4d3e7) | Jul 15, 2023 |
| Gateway       | SX2185                      | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| ASRock        | X670E Steel Legend          | [f25464fb37](https://linux-hardware.org/?probe=f25464fb37) | Jul 15, 2023 |
| ASUSTek       | A88XM-A                     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| ASUSTek       | PRIME B365M-A               | [62099e9da7](https://linux-hardware.org/?probe=62099e9da7) | Jul 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [065aed3358](https://linux-hardware.org/?probe=065aed3358) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [96921926b1](https://linux-hardware.org/?probe=96921926b1) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| MSI           | MAG B550M BAZOOKA           | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| ASRock        | B550M Pro4                  | [18a8fc202c](https://linux-hardware.org/?probe=18a8fc202c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2b544082c2](https://linux-hardware.org/?probe=2b544082c2) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| ASUSTek       | PRIME B250M-D               | [304630d909](https://linux-hardware.org/?probe=304630d909) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| Pegatron      | 2AD5                        | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eca6eabcb2](https://linux-hardware.org/?probe=eca6eabcb2) | Jul 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| ASUSTek       | PHOENIX                     | [88c02f40e7](https://linux-hardware.org/?probe=88c02f40e7) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| ASUSTek       | PRIME H310M-K               | [e7c0c87a14](https://linux-hardware.org/?probe=e7c0c87a14) | Jul 09, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d9880a123f](https://linux-hardware.org/?probe=d9880a123f) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Dell          | 00F82W A00                  | [603d370b5c](https://linux-hardware.org/?probe=603d370b5c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| MSI           | PRO Z690-A DDR4             | [f8aa10b5cb](https://linux-hardware.org/?probe=f8aa10b5cb) | Jul 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [1027217195](https://linux-hardware.org/?probe=1027217195) | Jul 08, 2023 |
| ECS           | P43T-AD3                    | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| HP            | 0AECh D                     | [c3d2867e48](https://linux-hardware.org/?probe=c3d2867e48) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [09c80a40ac](https://linux-hardware.org/?probe=09c80a40ac) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [f12b531ae3](https://linux-hardware.org/?probe=f12b531ae3) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [cc54a5a0bf](https://linux-hardware.org/?probe=cc54a5a0bf) | Jul 07, 2023 |
| HP            | 3397                        | [45bc734b0b](https://linux-hardware.org/?probe=45bc734b0b) | Jul 07, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| ASRock        | Z370 Professional Gaming... | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [2eb6b1bb05](https://linux-hardware.org/?probe=2eb6b1bb05) | Jul 07, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [4068c56cd3](https://linux-hardware.org/?probe=4068c56cd3) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS PRO              | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| MSI           | MS-7142                     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | H510M PRO-E                 | [598f789eb0](https://linux-hardware.org/?probe=598f789eb0) | Jul 06, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| HP            | 82FE 11                     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| AZW           | U59                         | [0b59408438](https://linux-hardware.org/?probe=0b59408438) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| Dell          | 06D7TR A00                  | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [ed520a330d](https://linux-hardware.org/?probe=ed520a330d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dd020d65e5](https://linux-hardware.org/?probe=dd020d65e5) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [06b0f38502](https://linux-hardware.org/?probe=06b0f38502) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-K               | [65cc87f2f0](https://linux-hardware.org/?probe=65cc87f2f0) | Jul 05, 2023 |
| Shenzhen M... | F7BFC                       | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [d816bd723e](https://linux-hardware.org/?probe=d816bd723e) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Gigabyte      | P85-D3                      | [6b4a40a1db](https://linux-hardware.org/?probe=6b4a40a1db) | Jul 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| HP            | 212B                        | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| ASUSTek       | H110M-E/M.2                 | [234c36d2ba](https://linux-hardware.org/?probe=234c36d2ba) | Jul 04, 2023 |
| MSI           | PRO Z690-A DDR4             | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Kupi deshe... | X99Z-V102 Date 27052020     | [0cdbbfe5b3](https://linux-hardware.org/?probe=0cdbbfe5b3) | Jul 03, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| HP            | 861A                        | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [dc77810d67](https://linux-hardware.org/?probe=dc77810d67) | Jul 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [bdbf0fa0c3](https://linux-hardware.org/?probe=bdbf0fa0c3) | Jul 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [590efa4873](https://linux-hardware.org/?probe=590efa4873) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| ASUSTek       | X99-M WS                    | [4f9ad96681](https://linux-hardware.org/?probe=4f9ad96681) | Jul 02, 2023 |
| AZW           | MINI S                      | [fb96f8d7bf](https://linux-hardware.org/?probe=fb96f8d7bf) | Jul 02, 2023 |
| ASUSTek       | PRIME B550M-A               | [740a0dad30](https://linux-hardware.org/?probe=740a0dad30) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| ASRock        | B560M-ITX/ac                | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| HP            | 8061                        | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| HP            | 8054                        | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [246d688f1c](https://linux-hardware.org/?probe=246d688f1c) | Jul 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [cfdff3114c](https://linux-hardware.org/?probe=cfdff3114c) | Jul 01, 2023 |
| Gigabyte      | H410M S2H V3                | [e539937c27](https://linux-hardware.org/?probe=e539937c27) | Jun 30, 2023 |
| Acer          | Predator PO5-640            | [416b01c954](https://linux-hardware.org/?probe=416b01c954) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [3749bda51b](https://linux-hardware.org/?probe=3749bda51b) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [6ee8476c0e](https://linux-hardware.org/?probe=6ee8476c0e) | Jun 30, 2023 |
| AZW           | MINI S 10                   | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| AZW           | MINI S 10                   | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [95fb20193a](https://linux-hardware.org/?probe=95fb20193a) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [5bb4af3f8b](https://linux-hardware.org/?probe=5bb4af3f8b) | Jun 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASRock        | H510M-HVS                   | [b90f532588](https://linux-hardware.org/?probe=b90f532588) | Jun 28, 2023 |
| HP            | 802F                        | [585f9bf338](https://linux-hardware.org/?probe=585f9bf338) | Jun 27, 2023 |
| HP            | 802F                        | [efceba0028](https://linux-hardware.org/?probe=efceba0028) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Dell          | 0R6PCT A01                  | [2fd7aa28db](https://linux-hardware.org/?probe=2fd7aa28db) | Jun 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3486e43434](https://linux-hardware.org/?probe=3486e43434) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| ASUSTek       | P9X79 PRO                   | [3d1eeda7fa](https://linux-hardware.org/?probe=3d1eeda7fa) | Jun 24, 2023 |
| Dell          | 088DT1 A01                  | [755d1f8c03](https://linux-hardware.org/?probe=755d1f8c03) | Jun 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1c0d2d86f3](https://linux-hardware.org/?probe=1c0d2d86f3) | Jun 24, 2023 |
| ASUSTek       | P8Z77-V LK                  | [bcfc1fe2de](https://linux-hardware.org/?probe=bcfc1fe2de) | Jun 23, 2023 |
| ASRock        | B450 Pro4                   | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c9f86c15b7](https://linux-hardware.org/?probe=c9f86c15b7) | Jun 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [52bcb712ec](https://linux-hardware.org/?probe=52bcb712ec) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| Unknown       | Unknown                     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| Dell          | 09KPNV A01                  | [eaa3017d03](https://linux-hardware.org/?probe=eaa3017d03) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [a5e833c54e](https://linux-hardware.org/?probe=a5e833c54e) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [52e2d1b77a](https://linux-hardware.org/?probe=52e2d1b77a) | Jun 21, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e7bb42d6d4](https://linux-hardware.org/?probe=e7bb42d6d4) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [2fe4bf8ad2](https://linux-hardware.org/?probe=2fe4bf8ad2) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| MSI           | B75MA-P45                   | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| Dell          | 0C2XKD A01                  | [15331b91ed](https://linux-hardware.org/?probe=15331b91ed) | Jun 18, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [924b6e8d54](https://linux-hardware.org/?probe=924b6e8d54) | Jun 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [231a3aeb2e](https://linux-hardware.org/?probe=231a3aeb2e) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cd87a6b19f](https://linux-hardware.org/?probe=cd87a6b19f) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ae4661e26f](https://linux-hardware.org/?probe=ae4661e26f) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [c555238190](https://linux-hardware.org/?probe=c555238190) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [7e135be518](https://linux-hardware.org/?probe=7e135be518) | Jun 17, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [84b103464e](https://linux-hardware.org/?probe=84b103464e) | Jun 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [3b83e2ea48](https://linux-hardware.org/?probe=3b83e2ea48) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [aad3ead710](https://linux-hardware.org/?probe=aad3ead710) | Jun 16, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9c3bb21706](https://linux-hardware.org/?probe=9c3bb21706) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| MSI           | Z170A GAMING M5             | [a0d460b4a3](https://linux-hardware.org/?probe=a0d460b4a3) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR            | [9604c6211e](https://linux-hardware.org/?probe=9604c6211e) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5a1e944af2](https://linux-hardware.org/?probe=5a1e944af2) | Jun 15, 2023 |
| MSI           | PRO B550M-VC WIFI           | [64e0ce279b](https://linux-hardware.org/?probe=64e0ce279b) | Jun 15, 2023 |
| Gigabyte      | B85M-D3V-A                  | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| ASUSTek       | P5G41C-M LX                 | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| MSI           | H510M PRO                   | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| MSI           | IONA                        | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| MSI           | Z77A-G45                    | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Gigabyte      | B560M DS3H V2               | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| ASRock        | Z390 Pro4                   | [067d0e5da5](https://linux-hardware.org/?probe=067d0e5da5) | Jun 12, 2023 |
| Shenzhen M... | F7BFD                       | [8f43ad0e76](https://linux-hardware.org/?probe=8f43ad0e76) | Jun 12, 2023 |
| ASUSTek       | PRIME H310M-K               | [f1614bb08f](https://linux-hardware.org/?probe=f1614bb08f) | Jun 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [57fcd66521](https://linux-hardware.org/?probe=57fcd66521) | Jun 11, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [abd31d2f92](https://linux-hardware.org/?probe=abd31d2f92) | Jun 10, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 6.2.9-300.fc38.x86_64        | 100      | 9.41%   |
| 6.4.15-200.fc38.x86_64       | 73       | 6.87%   |
| 6.2.15-300.fc38.x86_64       | 72       | 6.77%   |
| 6.3.8-200.fc38.x86_64        | 71       | 6.68%   |
| 6.5.5-200.fc38.x86_64        | 60       | 5.64%   |
| 6.2.14-300.fc38.x86_64       | 48       | 4.52%   |
| 6.5.6-200.fc38.x86_64        | 40       | 3.76%   |
| 6.3.12-200.fc38.x86_64       | 40       | 3.76%   |
| 6.5.7-200.fc38.x86_64        | 38       | 3.57%   |
| 6.4.11-200.fc38.x86_64       | 37       | 3.48%   |
| 6.2.11-300.fc38.x86_64       | 33       | 3.1%    |
| 6.3.11-200.fc38.x86_64       | 32       | 3.01%   |
| 6.5.8-200.fc38.x86_64        | 31       | 2.92%   |
| 6.4.6-200.fc38.x86_64        | 29       | 2.73%   |
| 6.4.12-200.fc38.x86_64       | 27       | 2.54%   |
| 6.4.13-200.fc38.x86_64       | 24       | 2.26%   |
| 6.3.5-200.fc38.x86_64        | 24       | 2.26%   |
| 6.3.4-201.fc38.x86_64        | 22       | 2.07%   |
| 6.2.12-300.fc38.x86_64       | 22       | 2.07%   |
| 6.4.7-200.fc38.x86_64        | 21       | 1.98%   |
| 6.4.14-200.fc38.x86_64       | 19       | 1.79%   |
| 6.3.7-200.fc38.x86_64        | 19       | 1.79%   |
| 6.4.4-200.fc38.x86_64        | 18       | 1.69%   |
| 6.4.10-200.fc38.x86_64       | 17       | 1.6%    |
| 6.2.13-300.fc38.x86_64       | 17       | 1.6%    |
| 6.5.10-200.fc38.x86_64       | 14       | 1.32%   |
| 6.3.6-200.fc38.x86_64        | 13       | 1.22%   |
| 6.4.9-200.fc38.x86_64        | 12       | 1.13%   |
| 6.5.9-200.fc38.x86_64        | 9        | 0.85%   |
| 6.5.12-200.fc38.x86_64       | 6        | 0.56%   |
| 6.6.9-100.fc38.x86_64        | 5        | 0.47%   |
| 6.4.8-200.fc38.x86_64        | 5        | 0.47%   |
| 6.2.6-300.fc38.x86_64        | 5        | 0.47%   |
| 6.2.8-300.fc38.x86_64        | 4        | 0.38%   |
| 6.2.15-703.inttf.fc38.x86_64 | 4        | 0.38%   |
| 6.6.8-100.fc38.x86_64        | 3        | 0.28%   |
| 6.6.11-100.fc38.x86_64       | 3        | 0.28%   |
| 6.3.3-200.fc38.x86_64        | 3        | 0.28%   |
| 6.2.7-300.fc38.x86_64        | 3        | 0.28%   |
| 6.6.2-101.fc38.x86_64        | 2        | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.9   | 100      | 9.41%   |
| 6.2.15  | 76       | 7.15%   |
| 6.4.15  | 73       | 6.87%   |
| 6.3.8   | 72       | 6.77%   |
| 6.5.5   | 60       | 5.64%   |
| 6.2.14  | 48       | 4.52%   |
| 6.5.6   | 40       | 3.76%   |
| 6.3.12  | 40       | 3.76%   |
| 6.5.7   | 38       | 3.57%   |
| 6.4.11  | 37       | 3.48%   |
| 6.2.11  | 33       | 3.1%    |
| 6.3.11  | 32       | 3.01%   |
| 6.5.8   | 31       | 2.92%   |
| 6.4.6   | 29       | 2.73%   |
| 6.4.12  | 27       | 2.54%   |
| 6.4.13  | 24       | 2.26%   |
| 6.3.5   | 24       | 2.26%   |
| 6.3.4   | 22       | 2.07%   |
| 6.2.12  | 22       | 2.07%   |
| 6.4.7   | 21       | 1.98%   |
| 6.4.4   | 19       | 1.79%   |
| 6.4.14  | 19       | 1.79%   |
| 6.3.7   | 19       | 1.79%   |
| 6.4.10  | 17       | 1.6%    |
| 6.2.13  | 17       | 1.6%    |
| 6.5.10  | 14       | 1.32%   |
| 6.3.6   | 13       | 1.22%   |
| 6.4.9   | 12       | 1.13%   |
| 6.5.9   | 9        | 0.85%   |
| 6.5.12  | 6        | 0.56%   |
| 6.6.9   | 5        | 0.47%   |
| 6.4.8   | 5        | 0.47%   |
| 6.2.6   | 5        | 0.47%   |
| 6.2.8   | 4        | 0.38%   |
| 6.6.8   | 3        | 0.28%   |
| 6.6.11  | 3        | 0.28%   |
| 6.3.3   | 3        | 0.28%   |
| 6.2.7   | 3        | 0.28%   |
| 6.2.2   | 3        | 0.28%   |
| 6.2.0   | 3        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 303      | 29.68%  |
| 6.4     | 276      | 27.03%  |
| 6.3     | 218      | 21.35%  |
| 6.5     | 195      | 19.1%   |
| 6.6     | 18       | 1.76%   |
| 6.1     | 6        | 0.59%   |
| 6.0     | 3        | 0.29%   |
| 5.19    | 1        | 0.1%    |
| 5.15    | 1        | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 915      | 99.78%  |
| ppc64le     | 1        | 0.11%   |
| loongarch64 | 1        | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 677      | 72.95%  |
| KDE5          | 158      | 17.03%  |
| Unknown       | 20       | 2.16%   |
| Cinnamon      | 18       | 1.94%   |
| XFCE          | 12       | 1.29%   |
| GNOME Classic | 10       | 1.08%   |
| X-Cinnamon    | 9        | 0.97%   |
| sway          | 5        | 0.54%   |
| MATE          | 5        | 0.54%   |
| Hyprland      | 3        | 0.32%   |
| Budgie        | 3        | 0.32%   |
| LXDE          | 2        | 0.22%   |
| openbox       | 1        | 0.11%   |
| LXQt          | 1        | 0.11%   |
| KDE           | 1        | 0.11%   |
| i3            | 1        | 0.11%   |
| e16-session   | 1        | 0.11%   |
| Deepin        | 1        | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 681      | 72.99%  |
| X11     | 205      | 21.97%  |
| Tty     | 40       | 4.29%   |
| Unknown | 7        | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 608      | 65.87%  |
| GDM     | 189      | 20.48%  |
| SDDM    | 76       | 8.23%   |
| LightDM | 48       | 5.2%    |
| LXDM    | 2        | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 441      | 47.88%  |
| en_GB   | 55       | 5.97%   |
| ru_RU   | 51       | 5.54%   |
| de_DE   | 48       | 5.21%   |
| pt_BR   | 42       | 4.56%   |
| en_AU   | 42       | 4.56%   |
| en_CA   | 38       | 4.13%   |
| es_ES   | 24       | 2.61%   |
| it_IT   | 22       | 2.39%   |
| fr_FR   | 22       | 2.39%   |
| pl_PL   | 12       | 1.3%    |
| es_MX   | 10       | 1.09%   |
| es_AR   | 10       | 1.09%   |
| es_CO   | 6        | 0.65%   |
| tr_TR   | 5        | 0.54%   |
| Unknown | 5        | 0.54%   |
| zh_TW   | 4        | 0.43%   |
| zh_CN   | 4        | 0.43%   |
| nl_NL   | 4        | 0.43%   |
| nl_BE   | 4        | 0.43%   |
| en_NZ   | 4        | 0.43%   |
| en_IN   | 4        | 0.43%   |
| en_DK   | 4        | 0.43%   |
| de_AT   | 4        | 0.43%   |
| pt_PT   | 3        | 0.33%   |
| hr_HR   | 3        | 0.33%   |
| fi_FI   | 3        | 0.33%   |
| es_CL   | 3        | 0.33%   |
| en_IE   | 3        | 0.33%   |
| de_CH   | 3        | 0.33%   |
| cs_CZ   | 3        | 0.33%   |
| sv_SE   | 2        | 0.22%   |
| hu_HU   | 2        | 0.22%   |
| fr_CA   | 2        | 0.22%   |
| en_PH   | 2        | 0.22%   |
| en_BW   | 2        | 0.22%   |
| da_DK   | 2        | 0.22%   |
| zh_SG   | 1        | 0.11%   |
| sr_RS   | 1        | 0.11%   |
| pa_IN   | 1        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 664      | 72.17%  |
| BIOS | 256      | 27.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 732      | 79.48%  |
| Ext4    | 148      | 16.07%  |
| Xfs     | 35       | 3.8%    |
| Zfs     | 2        | 0.22%   |
| Overlay | 2        | 0.22%   |
| F2fs    | 1        | 0.11%   |
| Ext3    | 1        | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 590      | 63.99%  |
| GPT     | 299      | 32.43%  |
| MBR     | 33       | 3.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 816      | 88.03%  |
| Yes       | 111      | 11.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 763      | 82.93%  |
| Yes       | 157      | 17.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 229      | 24.97%  |
| MSI                                  | 168      | 18.32%  |
| Gigabyte Technology                  | 166      | 18.1%   |
| ASRock                               | 92       | 10.03%  |
| Dell                                 | 66       | 7.2%    |
| Hewlett-Packard                      | 62       | 6.76%   |
| Lenovo                               | 29       | 3.16%   |
| Unknown                              | 13       | 1.42%   |
| Intel                                | 11       | 1.2%    |
| Pegatron                             | 10       | 1.09%   |
| Acer                                 | 9        | 0.98%   |
| AZW                                  | 7        | 0.76%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.55%   |
| Huanan                               | 5        | 0.55%   |
| Fujitsu                              | 5        | 0.55%   |
| Itautec                              | 4        | 0.44%   |
| Techvision                           | 2        | 0.22%   |
| Packard Bell                         | 2        | 0.22%   |
| Medion                               | 2        | 0.22%   |
| MACHINIST                            | 2        | 0.22%   |
| HPE                                  | 2        | 0.22%   |
| Foxconn                              | 2        | 0.22%   |
| Biostar                              | 2        | 0.22%   |
| Apple                                | 2        | 0.22%   |
| Supermicro                           | 1        | 0.11%   |
| Positivo                             | 1        | 0.11%   |
| PCWare                               | 1        | 0.11%   |
| NZXT                                 | 1        | 0.11%   |
| Loongson                             | 1        | 0.11%   |
| LattePanda                           | 1        | 0.11%   |
| Kupi deshego edition                 | 1        | 0.11%   |
| Kllisre                              | 1        | 0.11%   |
| iRU                                  | 1        | 0.11%   |
| Gateway                              | 1        | 0.11%   |
| GALAX                                | 1        | 0.11%   |
| Fujitsu Siemens                      | 1        | 0.11%   |
| Fill By OEM                          | 1        | 0.11%   |
| eMachines                            | 1        | 0.11%   |
| ECS                                  | 1        | 0.11%   |
| Colorful Technology                  | 1        | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| ASUS All Series                           | 16       | 1.74%   |
| Unknown                                   | 13       | 1.42%   |
| Dell OptiPlex 7010                        | 10       | 1.09%   |
| MSI MS-7C37                               | 7        | 0.76%   |
| MSI MS-7C95                               | 6        | 0.65%   |
| MSI MS-7C91                               | 6        | 0.65%   |
| MSI MS-7C56                               | 6        | 0.65%   |
| MSI MS-7B89                               | 6        | 0.65%   |
| Gigabyte X570 I AORUS PRO WIFI            | 6        | 0.65%   |
| MSI MS-7C02                               | 5        | 0.55%   |
| Gigabyte B550 GAMING X V2                 | 5        | 0.55%   |
| Dell OptiPlex 9020                        | 5        | 0.55%   |
| ASUS TUF Gaming X570-PRO                  | 5        | 0.55%   |
| ASUS TUF Gaming X570-PLUS                 | 5        | 0.55%   |
| ASUS ROG STRIX X670E-I GAMING WIFI        | 5        | 0.55%   |
| ASRock B450M Pro4                         | 5        | 0.55%   |
| MSI MS-7C52                               | 4        | 0.44%   |
| MSI MS-7B79                               | 4        | 0.44%   |
| MSI MS-7A38                               | 4        | 0.44%   |
| Gigabyte B550M DS3H                       | 4        | 0.44%   |
| Gigabyte B450M DS3H                       | 4        | 0.44%   |
| Gigabyte 970A-DS3P                        | 4        | 0.44%   |
| ASUS ROG STRIX X570-F GAMING              | 4        | 0.44%   |
| ASUS ROG STRIX B550-I GAMING              | 4        | 0.44%   |
| ASUS PRIME X570-P                         | 4        | 0.44%   |
| MSI MS-7D43                               | 3        | 0.33%   |
| MSI MS-7C94                               | 3        | 0.33%   |
| MSI MS-7B85                               | 3        | 0.33%   |
| MSI MS-7B78                               | 3        | 0.33%   |
| MSI MS-7B48                               | 3        | 0.33%   |
| MSI MS-7B17                               | 3        | 0.33%   |
| Itautec Infoway ST-4265                   | 3        | 0.33%   |
| HP Z800 Workstation                       | 3        | 0.33%   |
| HP Z420 Workstation                       | 3        | 0.33%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 3        | 0.33%   |
| HP Compaq Elite 8300 SFF                  | 3        | 0.33%   |
| HP Compaq 6005 Pro SFF PC                 | 3        | 0.33%   |
| Gigabyte GA-880GM-UD2H                    | 3        | 0.33%   |
| Gigabyte B650 AORUS ELITE AX              | 3        | 0.33%   |
| Gigabyte B550M AORUS ELITE                | 3        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 59       | 6.43%   |
| ASUS ROG              | 51       | 5.56%   |
| Dell OptiPlex         | 43       | 4.69%   |
| ASUS TUF              | 41       | 4.47%   |
| Lenovo ThinkCentre    | 16       | 1.74%   |
| HP Compaq             | 16       | 1.74%   |
| ASUS All              | 16       | 1.74%   |
| Unknown               | 13       | 1.42%   |
| Gigabyte X570         | 11       | 1.2%    |
| Gigabyte B550M        | 11       | 1.2%    |
| Gigabyte B550         | 11       | 1.2%    |
| HP EliteDesk          | 10       | 1.09%   |
| Dell Precision        | 10       | 1.09%   |
| ASRock B450M          | 10       | 1.09%   |
| Gigabyte B450M        | 9        | 0.98%   |
| MSI MS-7C37           | 7        | 0.76%   |
| Gigabyte B450         | 7        | 0.76%   |
| MSI MS-7C95           | 6        | 0.65%   |
| MSI MS-7C91           | 6        | 0.65%   |
| MSI MS-7C56           | 6        | 0.65%   |
| MSI MS-7B89           | 6        | 0.65%   |
| HP ProDesk            | 6        | 0.65%   |
| HP Pavilion           | 6        | 0.65%   |
| MSI MS-7C02           | 5        | 0.55%   |
| Lenovo ThinkStation   | 5        | 0.55%   |
| Lenovo IdeaCentre     | 5        | 0.55%   |
| Dell XPS              | 5        | 0.55%   |
| Dell Inspiron         | 5        | 0.55%   |
| ASRock X570           | 5        | 0.55%   |
| ASRock B450           | 5        | 0.55%   |
| Acer Aspire           | 5        | 0.55%   |
| MSI MS-7C52           | 4        | 0.44%   |
| MSI MS-7B79           | 4        | 0.44%   |
| MSI MS-7A38           | 4        | 0.44%   |
| Gigabyte X570S        | 4        | 0.44%   |
| Gigabyte H310M        | 4        | 0.44%   |
| Gigabyte B560M        | 4        | 0.44%   |
| Gigabyte AB350-Gaming | 4        | 0.44%   |
| Gigabyte 970A-DS3P    | 4        | 0.44%   |
| ASUS ProArt           | 4        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 125      | 13.63%  |
| 2020    | 121      | 13.2%   |
| 2021    | 89       | 9.71%   |
| 2022    | 86       | 9.38%   |
| 2019    | 82       | 8.94%   |
| 2013    | 59       | 6.43%   |
| 2017    | 57       | 6.22%   |
| 2012    | 52       | 5.67%   |
| 2023    | 38       | 4.14%   |
| 2014    | 38       | 4.14%   |
| 2015    | 36       | 3.93%   |
| 2016    | 33       | 3.6%    |
| 2010    | 32       | 3.49%   |
| 2011    | 30       | 3.27%   |
| 2009    | 17       | 1.85%   |
| 2008    | 10       | 1.09%   |
| 2007    | 6        | 0.65%   |
| 2006    | 3        | 0.33%   |
| Unknown | 2        | 0.22%   |
| 2005    | 1        | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 917      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 807      | 87.53%  |
| Enabled  | 115      | 12.47%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 917      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 282      | 30.39%  |
| 32.01-64.0      | 223      | 24.03%  |
| 8.01-16.0       | 112      | 12.07%  |
| 64.01-256.0     | 110      | 11.85%  |
| 4.01-8.0        | 99       | 10.67%  |
| 24.01-32.0      | 48       | 5.17%   |
| 3.01-4.0        | 47       | 5.06%   |
| 2.01-3.0        | 3        | 0.32%   |
| 1.01-2.0        | 3        | 0.32%   |
| More than 256.0 | 1        | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 325      | 32.96%  |
| 2.01-3.0    | 229      | 23.23%  |
| 3.01-4.0    | 212      | 21.5%   |
| 8.01-16.0   | 93       | 9.43%   |
| 1.01-2.0    | 89       | 9.03%   |
| 16.01-24.0  | 16       | 1.62%   |
| 0.51-1.0    | 15       | 1.52%   |
| 32.01-64.0  | 5        | 0.51%   |
| 24.01-32.0  | 1        | 0.1%    |
| 64.01-256.0 | 1        | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 313      | 33.09%  |
| 1      | 282      | 29.81%  |
| 3      | 181      | 19.13%  |
| 4      | 89       | 9.41%   |
| 5      | 44       | 4.65%   |
| 6      | 24       | 2.54%   |
| 7      | 6        | 0.63%   |
| 8      | 3        | 0.32%   |
| 11     | 1        | 0.11%   |
| 10     | 1        | 0.11%   |
| 9      | 1        | 0.11%   |
| 0      | 1        | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 657      | 71.26%  |
| Yes       | 265      | 28.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 910      | 99.13%  |
| No        | 8        | 0.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 519      | 56.17%  |
| No        | 405      | 43.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 478      | 51.9%   |
| Yes       | 443      | 48.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 203      | 22.11%  |
| Brazil      | 73       | 7.95%   |
| Germany     | 67       | 7.3%    |
| Russia      | 50       | 5.45%   |
| Canada      | 45       | 4.9%    |
| Australia   | 45       | 4.9%    |
| Italy       | 35       | 3.81%   |
| Spain       | 29       | 3.16%   |
| UK          | 27       | 2.94%   |
| Netherlands | 24       | 2.61%   |
| France      | 23       | 2.51%   |
| Poland      | 21       | 2.29%   |
| Mexico      | 19       | 2.07%   |
| Sweden      | 14       | 1.53%   |
| Argentina   | 14       | 1.53%   |
| Colombia    | 11       | 1.2%    |
| India       | 10       | 1.09%   |
| Belgium     | 10       | 1.09%   |
| Belarus     | 10       | 1.09%   |
| Austria     | 10       | 1.09%   |
| Thailand    | 8        | 0.87%   |
| Switzerland | 7        | 0.76%   |
| Norway      | 7        | 0.76%   |
| Hungary     | 7        | 0.76%   |
| Turkey      | 6        | 0.65%   |
| Portugal    | 6        | 0.65%   |
| Denmark     | 6        | 0.65%   |
| Czechia     | 6        | 0.65%   |
| Bulgaria    | 6        | 0.65%   |
| Serbia      | 5        | 0.54%   |
| New Zealand | 5        | 0.54%   |
| Indonesia   | 5        | 0.54%   |
| China       | 5        | 0.54%   |
| Chile       | 5        | 0.54%   |
| Ukraine     | 4        | 0.44%   |
| Taiwan      | 4        | 0.44%   |
| Singapore   | 4        | 0.44%   |
| Ireland     | 4        | 0.44%   |
| Finland     | 4        | 0.44%   |
| Croatia     | 4        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 24       | 2.58%   |
| Moscow         | 11       | 1.18%   |
| Sao Paulo      | 9        | 0.97%   |
| Palmas         | 9        | 0.97%   |
| Minsk          | 9        | 0.97%   |
| Vienna         | 8        | 0.86%   |
| Seattle        | 6        | 0.64%   |
| Milan          | 6        | 0.64%   |
| Los Angeles    | 6        | 0.64%   |
| Brisbane       | 6        | 0.64%   |
| Warsaw         | 5        | 0.54%   |
| Toronto        | 5        | 0.54%   |
| St Petersburg  | 5        | 0.54%   |
| Mexico City    | 5        | 0.54%   |
| Melbourne      | 5        | 0.54%   |
| Brussels       | 5        | 0.54%   |
| Winnipeg       | 4        | 0.43%   |
| Singapore      | 4        | 0.43%   |
| San José      | 4        | 0.43%   |
| Rostov-on-Don  | 4        | 0.43%   |
| Rio de Janeiro | 4        | 0.43%   |
| Porto Alegre   | 4        | 0.43%   |
| Ottawa         | 4        | 0.43%   |
| Montreal       | 4        | 0.43%   |
| Madrid         | 4        | 0.43%   |
| Budapest       | 4        | 0.43%   |
| Brasília      | 4        | 0.43%   |
| Berlin         | 4        | 0.43%   |
| Belgrade       | 4        | 0.43%   |
| Barcelona      | 4        | 0.43%   |
| Bangkok        | 4        | 0.43%   |
| Amsterdam      | 4        | 0.43%   |
| The Hague      | 3        | 0.32%   |
| Somerville     | 3        | 0.32%   |
| Sofia          | 3        | 0.32%   |
| Santiago       | 3        | 0.32%   |
| Rome           | 3        | 0.32%   |
| Rochester      | 3        | 0.32%   |
| Riga           | 3        | 0.32%   |
| Prague         | 3        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 329      | 573    | 18.25%  |
| Seagate                      | 251      | 380    | 13.92%  |
| WDC                          | 242      | 394    | 13.42%  |
| Sandisk                      | 126      | 163    | 6.99%   |
| Kingston                     | 110      | 134    | 6.1%    |
| Crucial                      | 98       | 133    | 5.44%   |
| Toshiba                      | 85       | 106    | 4.71%   |
| Intel                        | 39       | 62     | 2.16%   |
| Phison Electronics           | 38       | 55     | 2.11%   |
| Hitachi                      | 38       | 55     | 2.11%   |
| Micron/Crucial Technology    | 35       | 41     | 1.94%   |
| A-DATA Technology            | 27       | 31     | 1.5%    |
| Silicon Motion               | 25       | 29     | 1.39%   |
| Kingston Technology Company  | 23       | 29     | 1.28%   |
| HGST                         | 18       | 19     | 1%      |
| Patriot                      | 16       | 22     | 0.89%   |
| Micron Technology            | 15       | 15     | 0.83%   |
| China                        | 15       | 21     | 0.83%   |
| ADATA Technology             | 15       | 19     | 0.83%   |
| PNY                          | 13       | 17     | 0.72%   |
| SK hynix                     | 12       | 15     | 0.67%   |
| Realtek Semiconductor        | 12       | 16     | 0.67%   |
| Unknown                      | 11       | 17     | 0.61%   |
| SPCC                         | 11       | 13     | 0.61%   |
| Netac                        | 9        | 9      | 0.5%    |
| MAXIO Technology (Hangzhou)  | 8        | 11     | 0.44%   |
| Intenso                      | 8        | 9      | 0.44%   |
| Team                         | 7        | 10     | 0.39%   |
| KingSpec                     | 7        | 7      | 0.39%   |
| OCZ                          | 6        | 10     | 0.33%   |
| AMD                          | 6        | 10     | 0.33%   |
| Transcend                    | 5        | 6      | 0.28%   |
| ASMT                         | 5        | 6      | 0.28%   |
| Shenzhen Longsys Electronics | 4        | 4      | 0.22%   |
| Seagate Technology           | 4        | 5      | 0.22%   |
| SABRENT                      | 4        | 4      | 0.22%   |
| Mushkin                      | 4        | 4      | 0.22%   |
| Maxtor                       | 4        | 4      | 0.22%   |
| LITEONIT                     | 4        | 4      | 0.22%   |
| Lexar                        | 4        | 4      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 85       | 4.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB              | 54       | 2.6%    |
| Crucial CT500MX500SSD1 500GB                                    | 26       | 1.25%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 23       | 1.11%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                             | 22       | 1.06%   |
| Samsung SSD 850 EVO 250GB                                       | 20       | 0.96%   |
| Kingston SA400S37480G 480GB SSD                                 | 20       | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB           | 19       | 0.92%   |
| Samsung SSD 860 EVO 1TB                                         | 19       | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB             | 19       | 0.92%   |
| Kingston SA400S37240G 240GB SSD                                 | 19       | 0.92%   |
| Seagate ST500DM002-1BD142 500GB                                 | 18       | 0.87%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 18       | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 18       | 0.87%   |
| Phison E12 NVMe Controller 1TB                                  | 18       | 0.87%   |
| Toshiba DT01ACA100 1TB                                          | 17       | 0.82%   |
| Samsung SSD 860 EVO 500GB                                       | 17       | 0.82%   |
| Samsung SSD 870 EVO 1TB                                         | 16       | 0.77%   |
| Samsung SSD 980 1TB                                             | 15       | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 14       | 0.67%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                            | 14       | 0.67%   |
| Kingston SA400S37120G 120GB SSD                                 | 13       | 0.63%   |
| Crucial CT1000MX500SSD1 1TB                                     | 13       | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 12       | 0.58%   |
| Samsung SSD 850 EVO 500GB                                       | 12       | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                | 11       | 0.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 10       | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 9        | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                                  | 9        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 9        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller 2TB                            | 9        | 0.43%   |
| Crucial CT2000MX500SSD1 2TB                                     | 9        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 8        | 0.39%   |
| Sandisk WD_BLACK SN770 1TB                                      | 8        | 0.39%   |
| Sandisk WD Black SN850 1024GB                                   | 8        | 0.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                | 8        | 0.39%   |
| Samsung SSD 860 EVO 250GB                                       | 8        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                                | 8        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                                    | 8        | 0.39%   |
| Unknown SD/MMC/MS PRO 256GB                                     | 7        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 242      | 361    | 39.22%  |
| WDC                 | 204      | 325    | 33.06%  |
| Toshiba             | 68       | 83     | 11.02%  |
| Hitachi             | 38       | 55     | 6.16%   |
| Samsung Electronics | 24       | 33     | 3.89%   |
| HGST                | 18       | 19     | 2.92%   |
| Unknown             | 7        | 7      | 1.13%   |
| Maxtor              | 3        | 3      | 0.49%   |
| TO Exter            | 2        | 2      | 0.32%   |
| QNAP                | 2        | 2      | 0.32%   |
| JMicron Technology  | 2        | 2      | 0.32%   |
| ASMT                | 2        | 3      | 0.32%   |
| USB                 | 1        | 1      | 0.16%   |
| Mercury             | 1        | 1      | 0.16%   |
| Maxone              | 1        | 1      | 0.16%   |
| Intenso             | 1        | 1      | 0.16%   |
| Apple               | 1        | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 167      | 261    | 24.06%  |
| Crucial             | 96       | 128    | 13.83%  |
| Kingston            | 84       | 102    | 12.1%   |
| SanDisk             | 50       | 62     | 7.2%    |
| WDC                 | 49       | 67     | 7.06%   |
| A-DATA Technology   | 27       | 31     | 3.89%   |
| Intel               | 24       | 41     | 3.46%   |
| Patriot             | 16       | 22     | 2.31%   |
| China               | 15       | 21     | 2.16%   |
| PNY                 | 13       | 17     | 1.87%   |
| SPCC                | 11       | 13     | 1.59%   |
| Toshiba             | 10       | 15     | 1.44%   |
| Micron Technology   | 8        | 8      | 1.15%   |
| Team                | 7        | 10     | 1.01%   |
| KingSpec            | 7        | 7      | 1.01%   |
| OCZ                 | 6        | 10     | 0.86%   |
| Transcend           | 5        | 6      | 0.72%   |
| Netac               | 5        | 5      | 0.72%   |
| Intenso             | 5        | 5      | 0.72%   |
| SABRENT             | 4        | 4      | 0.58%   |
| Mushkin             | 4        | 4      | 0.58%   |
| LITEONIT            | 4        | 4      | 0.58%   |
| Lexar               | 4        | 4      | 0.58%   |
| GOODRAM             | 4        | 6      | 0.58%   |
| Emtec               | 4        | 5      | 0.58%   |
| AMD                 | 4        | 4      | 0.58%   |
| Hewlett-Packard     | 3        | 3      | 0.43%   |
| Gigabyte Technology | 3        | 4      | 0.43%   |
| Apacer              | 3        | 4      | 0.43%   |
| Unknown             | 3        | 5      | 0.43%   |
| XrayDisk            | 2        | 2      | 0.29%   |
| SK hynix            | 2        | 2      | 0.29%   |
| NGFF                | 2        | 2      | 0.29%   |
| LITEON              | 2        | 2      | 0.29%   |
| Fanxiang            | 2        | 2      | 0.29%   |
| Corsair             | 2        | 2      | 0.29%   |
| Colorful            | 2        | 2      | 0.29%   |
| Acer                | 2        | 5      | 0.29%   |
| ZOTAC               | 1        | 1      | 0.14%   |
| Vaseky              | 1        | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 558      | 938    | 35.54%  |
| HDD     | 507      | 900    | 32.29%  |
| NVMe    | 470      | 714    | 29.94%  |
| Unknown | 33       | 39     | 2.1%    |
| MMC     | 2        | 4      | 0.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 753      | 1789   | 58.33%  |
| NVMe | 469      | 711    | 36.33%  |
| SAS  | 67       | 91     | 5.19%   |
| MMC  | 2        | 4      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 510      | 908    | 45.37%  |
| 0.51-1.0   | 342      | 516    | 30.43%  |
| 1.01-2.0   | 154      | 225    | 13.7%   |
| 3.01-4.0   | 62       | 92     | 5.52%   |
| 4.01-10.0  | 29       | 62     | 2.58%   |
| 2.01-3.0   | 22       | 26     | 1.96%   |
| 10.01-20.0 | 5        | 9      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 199      | 20.9%   |
| 1001-2000      | 188      | 19.75%  |
| More than 3000 | 146      | 15.34%  |
| 251-500        | 131      | 13.76%  |
| 101-250        | 106      | 11.13%  |
| 2001-3000      | 78       | 8.19%   |
| 1-20           | 37       | 3.89%   |
| Unknown        | 34       | 3.57%   |
| 51-100         | 19       | 2%      |
| 21-50          | 13       | 1.37%   |
| 0              | 1        | 0.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 215      | 22.14%  |
| 21-50          | 146      | 15.04%  |
| 101-250        | 114      | 11.74%  |
| 251-500        | 113      | 11.64%  |
| 501-1000       | 101      | 10.4%   |
| 51-100         | 97       | 9.99%   |
| 1001-2000      | 79       | 8.14%   |
| More than 3000 | 36       | 3.71%   |
| 2001-3000      | 35       | 3.6%    |
| Unknown        | 34       | 3.5%    |
| 0              | 1        | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4        | 5      | 4.4%    |
| Intel SSDSC2CT120A3 120GB             | 3        | 8      | 3.3%    |
| WDC WD20EZRX-00D8PB0 2TB              | 2        | 2      | 2.2%    |
| Toshiba MQ01ABD100 1TB                | 2        | 2      | 2.2%    |
| Seagate ST31000524AS 1TB              | 2        | 2      | 2.2%    |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 2      | 2.2%    |
| Samsung Electronics SSD 840 EVO 250GB | 2        | 2      | 2.2%    |
| Crucial CT120M500SSD1 120GB           | 2        | 7      | 2.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 1      | 1.1%    |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1        | 1      | 1.1%    |
| WDC WD5000AVCS-632DY1 500GB           | 1        | 3      | 1.1%    |
| WDC WD5000AAKX-603CA0 500GB           | 1        | 1      | 1.1%    |
| WDC WD5000AAKS-00UU3A0 500GB          | 1        | 1      | 1.1%    |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 1.1%    |
| WDC WD40PURX-64GVNY0 4TB              | 1        | 1      | 1.1%    |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 1      | 1.1%    |
| WDC WD30EZRX-00SPEB0 3TB              | 1        | 1      | 1.1%    |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 2      | 1.1%    |
| WDC WD2500BEVT-80A23T0 250GB          | 1        | 1      | 1.1%    |
| WDC WD20EZRZ-22Z5HB0 2TB              | 1        | 1      | 1.1%    |
| WDC WD20EARS-00J2GB0 2TB              | 1        | 1      | 1.1%    |
| WDC WD10JPVT-60A1YT0 1TB              | 1        | 1      | 1.1%    |
| WDC WD10EZRZ-00HTKB0 1TB              | 1        | 1      | 1.1%    |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.1%    |
| WDC WD1002FAEX-00Y9A0 1TB             | 1        | 1      | 1.1%    |
| Toshiba MQ02ABD100H 1TB               | 1        | 1      | 1.1%    |
| Toshiba DT01ACA200 2TB                | 1        | 2      | 1.1%    |
| SPCC Solid State Disk 128GB           | 1        | 1      | 1.1%    |
| Seagate ST9250827AS 250GB             | 1        | 1      | 1.1%    |
| Seagate ST9160412AS 160GB             | 1        | 1      | 1.1%    |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 2      | 1.1%    |
| Seagate ST3750528AS 752GB             | 1        | 1      | 1.1%    |
| Seagate ST3500630NS 500GB             | 1        | 1      | 1.1%    |
| Seagate ST3500418AS 500GB             | 1        | 3      | 1.1%    |
| Seagate ST3320613AS 320GB             | 1        | 1      | 1.1%    |
| Seagate ST3250410AS 250GB             | 1        | 1      | 1.1%    |
| Seagate ST2000VX000-1CU164 2TB        | 1        | 1      | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 1.1%    |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.1%    |
| Seagate ST1000LX015-1U7172 1TB        | 1        | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 20       | 26     | 23.26%  |
| WDC                         | 16       | 22     | 18.6%   |
| Samsung Electronics         | 12       | 18     | 13.95%  |
| Intel                       | 6        | 11     | 6.98%   |
| Hitachi                     | 6        | 6      | 6.98%   |
| Toshiba                     | 4        | 5      | 4.65%   |
| SanDisk                     | 3        | 3      | 3.49%   |
| Kingston                    | 3        | 4      | 3.49%   |
| Crucial                     | 3        | 8      | 3.49%   |
| Maxtor                      | 2        | 2      | 2.33%   |
| A-DATA Technology           | 2        | 2      | 2.33%   |
| SPCC                        | 1        | 1      | 1.16%   |
| Micron/Crucial Technology   | 1        | 1      | 1.16%   |
| Micron Technology           | 1        | 1      | 1.16%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 1.16%   |
| LITEONIT                    | 1        | 1      | 1.16%   |
| Intenso                     | 1        | 1      | 1.16%   |
| HPE                         | 1        | 1      | 1.16%   |
| HGST                        | 1        | 1      | 1.16%   |
| China                       | 1        | 1      | 1.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 26     | 38.46%  |
| WDC                 | 15       | 20     | 28.85%  |
| Hitachi             | 6        | 6      | 11.54%  |
| Toshiba             | 4        | 5      | 7.69%   |
| Samsung Electronics | 4        | 9      | 7.69%   |
| Maxtor              | 2        | 2      | 3.85%   |
| HGST                | 1        | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 47       | 69     | 58.75%  |
| SSD  | 29       | 43     | 36.25%  |
| NVMe | 4        | 4      | 5%      |

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
| Detected | 622      | 1640   | 61.83%  |
| Works    | 308      | 839    | 30.62%  |
| Malfunc  | 76       | 116    | 7.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 486      | 31.87%  |
| AMD                              | 417      | 27.34%  |
| Samsung Electronics              | 195      | 12.79%  |
| SanDisk                          | 82       | 5.38%   |
| ASMedia Technology               | 55       | 3.61%   |
| Kingston Technology Company      | 52       | 3.41%   |
| Phison Electronics               | 39       | 2.56%   |
| Micron/Crucial Technology        | 37       | 2.43%   |
| Silicon Motion                   | 25       | 1.64%   |
| Marvell Technology Group         | 20       | 1.31%   |
| ADATA Technology                 | 15       | 0.98%   |
| Realtek Semiconductor            | 12       | 0.79%   |
| Seagate Technology               | 10       | 0.66%   |
| JMicron Technology               | 10       | 0.66%   |
| SK hynix                         | 9        | 0.59%   |
| MAXIO Technology (Hangzhou)      | 8        | 0.52%   |
| Toshiba America Info Systems     | 7        | 0.46%   |
| Micron Technology                | 7        | 0.46%   |
| VIA Technologies                 | 4        | 0.26%   |
| Shenzhen Longsys Electronics     | 4        | 0.26%   |
| Netac Technology                 | 4        | 0.26%   |
| Nvidia                           | 3        | 0.2%    |
| LSI Logic / Symbios Logic        | 3        | 0.2%    |
| KIOXIA                           | 3        | 0.2%    |
| Broadcom / LSI                   | 3        | 0.2%    |
| Silicon Image                    | 2        | 0.13%   |
| INNOGRIT                         | 2        | 0.13%   |
| Adaptec                          | 2        | 0.13%   |
| Yangtze Memory Technologies      | 1        | 0.07%   |
| Union Memory (Shenzhen)          | 1        | 0.07%   |
| ULi Electronics                  | 1        | 0.07%   |
| Solid State Storage Technology   | 1        | 0.07%   |
| Silicon Integrated Systems [SiS] | 1        | 0.07%   |
| PMC-Sierra                       | 1        | 0.07%   |
| Loongson Technology              | 1        | 0.07%   |
| Hosin Global Electronics         | 1        | 0.07%   |
| Biwin Storage Technology         | 1        | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 184      | 10.39%  |
| AMD 500 Series Chipset SATA Controller                                                  | 93       | 5.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 89       | 5.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 88       | 4.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 58       | 3.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 52       | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 52       | 2.94%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 50       | 2.82%   |
| AMD 600 Series Chipset SATA Controller                                                  | 50       | 2.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 49       | 2.77%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 46       | 2.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 42       | 2.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 39       | 2.2%    |
| Intel SATA Controller [RAID mode]                                                       | 36       | 2.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 27       | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 26       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 26       | 1.47%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 24       | 1.36%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 23       | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 22       | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 20       | 1.13%   |
| AMD 300 Series Chipset SATA Controller                                                  | 20       | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 19       | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 19       | 1.07%   |
| AMD FCH SATA Controller D                                                               | 19       | 1.07%   |
| Phison E12 NVMe Controller                                                              | 18       | 1.02%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 15       | 0.85%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 15       | 0.85%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 14       | 0.79%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 14       | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 0.79%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 13       | 0.73%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 11       | 0.62%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 10       | 0.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 10       | 0.56%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 9        | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 0.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 8        | 0.45%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 8        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 832      | 56.79%  |
| NVMe | 469      | 32.01%  |
| IDE  | 82       | 5.6%    |
| RAID | 70       | 4.78%   |
| SAS  | 6        | 0.41%   |
| SCSI | 6        | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 489      | 53.33%  |
| AMD                      | 426      | 46.46%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.11%   |
| Loongson                 | 1        | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 28       | 3.05%   |
| AMD Ryzen 5 3600 6-Core Processor           | 25       | 2.72%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 19       | 2.07%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 1.96%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 15       | 1.63%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 15       | 1.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 1.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 1.53%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 14       | 1.53%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 13       | 1.42%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 13       | 1.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 12       | 1.31%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 12       | 1.31%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 11       | 1.2%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 11       | 1.2%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 11       | 1.2%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 10       | 1.09%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 1.09%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 10       | 1.09%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 9        | 0.98%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 8        | 0.87%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7        | 0.76%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 0.76%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 7        | 0.76%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 7        | 0.76%   |
| Intel 12th Gen Core i5-12400F               | 7        | 0.76%   |
| AMD Ryzen 9 7950X3D 16-Core Processor       | 7        | 0.76%   |
| AMD Ryzen 7 7700X 8-Core Processor          | 7        | 0.76%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 0.65%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 6        | 0.65%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 6        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 0.65%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 0.65%   |
| Intel 12th Gen Core i5-12600K               | 6        | 0.65%   |
| Intel 12th Gen Core i5-12400                | 6        | 0.65%   |
| AMD Ryzen 5 5600 6-Core Processor           | 6        | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 5        | 0.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 5        | 0.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 5        | 0.54%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 147      | 16.03%  |
| AMD Ryzen 5             | 144      | 15.7%   |
| Intel Core i7           | 111      | 12.1%   |
| AMD Ryzen 7             | 109      | 11.89%  |
| AMD Ryzen 9             | 76       | 8.29%   |
| Other                   | 73       | 7.96%   |
| Intel Xeon              | 50       | 5.45%   |
| Intel Core i3           | 42       | 4.58%   |
| AMD FX                  | 22       | 2.4%    |
| Intel Celeron           | 19       | 2.07%   |
| AMD Phenom II X4        | 13       | 1.42%   |
| Intel Core i9           | 12       | 1.31%   |
| Intel Core 2 Quad       | 10       | 1.09%   |
| AMD Ryzen 3             | 10       | 1.09%   |
| AMD Ryzen Threadripper  | 8        | 0.87%   |
| AMD A10                 | 7        | 0.76%   |
| Intel Pentium Gold      | 5        | 0.55%   |
| Intel Core 2 Duo        | 5        | 0.55%   |
| AMD Ryzen 5 PRO         | 5        | 0.55%   |
| AMD Athlon              | 5        | 0.55%   |
| Intel Pentium Dual-Core | 4        | 0.44%   |
| Intel Pentium           | 4        | 0.44%   |
| Intel Atom              | 4        | 0.44%   |
| AMD A4                  | 4        | 0.44%   |
| AMD Ryzen 7 PRO         | 3        | 0.33%   |
| AMD Phenom II X6        | 3        | 0.33%   |
| AMD Phenom II X2        | 3        | 0.33%   |
| AMD A8                  | 3        | 0.33%   |
| Intel Pentium Dual      | 2        | 0.22%   |
| Intel Core 2            | 2        | 0.22%   |
| AMD Athlon II X2        | 2        | 0.22%   |
| AMD Athlon 64 X2        | 2        | 0.22%   |
| AMD A6                  | 2        | 0.22%   |
| Intel Pentium Silver    | 1        | 0.11%   |
| Intel Genuine           | 1        | 0.11%   |
| AMD Turion 64 X2 Mobile | 1        | 0.11%   |
| AMD Sempron             | 1        | 0.11%   |
| AMD Opteron             | 1        | 0.11%   |
| AMD E2                  | 1        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 302      | 32.93%  |
| 6      | 225      | 24.54%  |
| 8      | 148      | 16.14%  |
| 2      | 98       | 10.69%  |
| 12     | 53       | 5.78%   |
| 16     | 50       | 5.45%   |
| 10     | 16       | 1.74%   |
| 24     | 6        | 0.65%   |
| 3      | 6        | 0.65%   |
| 14     | 5        | 0.55%   |
| 1      | 5        | 0.55%   |
| 36     | 1        | 0.11%   |
| 32     | 1        | 0.11%   |
| 18     | 1        | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 905      | 98.69%  |
| 2      | 12       | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 662      | 72.19%  |
| 1      | 254      | 27.7%   |
| 4      | 1        | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 915      | 99.78%  |
| Unknown        | 2        | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 519      | 56.23%  |
| 0x0a20120a | 45       | 4.88%   |
| 0x0a601203 | 44       | 4.77%   |
| 0x08701021 | 40       | 4.33%   |
| 0x0800820d | 31       | 3.36%   |
| 0x0a50000d | 25       | 2.71%   |
| 0x0a201016 | 20       | 2.17%   |
| 0x08701030 | 18       | 1.95%   |
| 0x08108109 | 18       | 1.95%   |
| 0x0a50000c | 12       | 1.3%    |
| 0x010000c8 | 10       | 1.08%   |
| 0x08701013 | 8        | 0.87%   |
| 0x06000822 | 8        | 0.87%   |
| 0x0a201205 | 7        | 0.76%   |
| 0x0a201025 | 7        | 0.76%   |
| 0x0a201009 | 7        | 0.76%   |
| 0x08600106 | 7        | 0.76%   |
| 0x06000852 | 7        | 0.76%   |
| 0x08001137 | 6        | 0.65%   |
| 0x08001138 | 5        | 0.54%   |
| 0x06001119 | 5        | 0.54%   |
| 0x010000b6 | 5        | 0.54%   |
| 0x0a404102 | 4        | 0.43%   |
| 0x0a201204 | 4        | 0.43%   |
| 0x08101016 | 4        | 0.43%   |
| 0x0a601201 | 3        | 0.33%   |
| 0x0800820c | 3        | 0.33%   |
| 0x08001129 | 3        | 0.33%   |
| 0x0600611a | 3        | 0.33%   |
| 0x06003106 | 3        | 0.33%   |
| 0x010000bf | 3        | 0.33%   |
| 0x00000000 | 3        | 0.33%   |
| 0x0a20120e | 2        | 0.22%   |
| 0x08600109 | 2        | 0.22%   |
| 0x0600081c | 2        | 0.22%   |
| 0x06000629 | 2        | 0.22%   |
| 0x906ea    | 1        | 0.11%   |
| 0x706a1    | 1        | 0.11%   |
| 0x20652    | 1        | 0.11%   |
| 0x0a704101 | 1        | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 143      | 15.58%  |
| KabyLake         | 104      | 11.33%  |
| Zen 2            | 81       | 8.82%   |
| Haswell          | 76       | 8.28%   |
| Unknown          | 61       | 6.64%   |
| IvyBridge        | 58       | 6.32%   |
| Zen+             | 55       | 5.99%   |
| Alderlake Hybrid | 53       | 5.77%   |
| Skylake          | 49       | 5.34%   |
| SandyBridge      | 32       | 3.49%   |
| CometLake        | 30       | 3.27%   |
| Zen              | 24       | 2.61%   |
| Piledriver       | 24       | 2.61%   |
| K10              | 21       | 2.29%   |
| Penryn           | 17       | 1.85%   |
| Westmere         | 16       | 1.74%   |
| Icelake          | 14       | 1.53%   |
| Core             | 8        | 0.87%   |
| Broadwell        | 6        | 0.65%   |
| Tremont          | 5        | 0.54%   |
| Silvermont       | 5        | 0.54%   |
| Bulldozer        | 5        | 0.54%   |
| Steamroller      | 4        | 0.44%   |
| Nehalem          | 4        | 0.44%   |
| K8 Hammer        | 4        | 0.44%   |
| Excavator        | 4        | 0.44%   |
| Bonnell          | 4        | 0.44%   |
| Gracemont        | 3        | 0.33%   |
| Goldmont plus    | 3        | 0.33%   |
| K10 Llano        | 2        | 0.22%   |
| Jaguar           | 2        | 0.22%   |
| TigerLake        | 1        | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 400      | 40.44%  |
| Nvidia                           | 360      | 36.4%   |
| Intel                            | 223      | 22.55%  |
| Matrox Electronics Systems       | 2        | 0.2%    |
| VIA Technologies                 | 1        | 0.1%    |
| Silicon Integrated Systems [SiS] | 1        | 0.1%    |
| Loongson Technology              | 1        | 0.1%    |
| ASPEED Technology                | 1        | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 54       | 5.21%   |
| AMD Raphael                                                                 | 37       | 3.57%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 36       | 3.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 33       | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 30       | 2.89%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 30       | 2.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 28       | 2.7%    |
| Intel HD Graphics 530                                                       | 27       | 2.6%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 26       | 2.51%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 25       | 2.41%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 19       | 1.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 19       | 1.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 17       | 1.64%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 14       | 1.35%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 14       | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13       | 1.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 12       | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 12       | 1.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 11       | 1.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 0.96%   |
| Intel HD Graphics 630                                                       | 10       | 0.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 10       | 0.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 9        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 0.87%   |
| Intel AlderLake-S GT1                                                       | 9        | 0.87%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 9        | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 9        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 8        | 0.77%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 8        | 0.77%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 8        | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 0.68%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 7        | 0.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 0.68%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 7        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 6        | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 6        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x AMD                 | 338      | 36.62%  |
| 1 x Nvidia              | 311      | 33.69%  |
| 1 x Intel               | 169      | 18.31%  |
| 2 x AMD                 | 36       | 3.9%    |
| Intel + Nvidia          | 26       | 2.82%   |
| AMD + Nvidia            | 15       | 1.63%   |
| Intel + AMD             | 12       | 1.3%    |
| 2 x Nvidia              | 7        | 0.76%   |
| 2 x Intel               | 2        | 0.22%   |
| 1 x VIA                 | 1        | 0.11%   |
| 1 x SiS                 | 1        | 0.11%   |
| Nvidia + Matrox         | 1        | 0.11%   |
| 1 x Matrox              | 1        | 0.11%   |
| 1 x Loongson Technology | 1        | 0.11%   |
| Intel + 2 x AMD         | 1        | 0.11%   |
| 1 x ASPEED              | 1        | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 714      | 77.19%  |
| Proprietary | 180      | 19.46%  |
| Unknown     | 31       | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 303      | 32.44%  |
| 7.01-8.0   | 166      | 17.77%  |
| 3.01-4.0   | 98       | 10.49%  |
| 1.01-2.0   | 93       | 9.96%   |
| 8.01-16.0  | 85       | 9.1%    |
| 0.51-1.0   | 68       | 7.28%   |
| 0.01-0.5   | 67       | 7.17%   |
| 5.01-6.0   | 21       | 2.25%   |
| 16.01-24.0 | 21       | 2.25%   |
| 2.01-3.0   | 11       | 1.18%   |
| 4.01-5.0   | 1        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 177      | 16.53%  |
| Goldstar             | 170      | 15.87%  |
| Dell                 | 132      | 12.32%  |
| Hewlett-Packard      | 75       | 7%      |
| Acer                 | 67       | 6.26%   |
| AOC                  | 47       | 4.39%   |
| Philips              | 46       | 4.3%    |
| BenQ                 | 39       | 3.64%   |
| Ancor Communications | 35       | 3.27%   |
| Lenovo               | 30       | 2.8%    |
| ASUSTek Computer     | 28       | 2.61%   |
| ViewSonic            | 18       | 1.68%   |
| Sceptre Tech         | 16       | 1.49%   |
| Iiyama               | 16       | 1.49%   |
| MSI                  | 13       | 1.21%   |
| Gigabyte Technology  | 13       | 1.21%   |
| Unknown              | 11       | 1.03%   |
| Sony                 | 9        | 0.84%   |
| Mi                   | 7        | 0.65%   |
| Fujitsu Siemens      | 5        | 0.47%   |
| Eizo                 | 5        | 0.47%   |
| Belinea              | 5        | 0.47%   |
| Vizio                | 4        | 0.37%   |
| HUAWEI               | 4        | 0.37%   |
| Vestel Elektronik    | 3        | 0.28%   |
| Toshiba              | 3        | 0.28%   |
| Panasonic            | 3        | 0.28%   |
| LG Electronics       | 3        | 0.28%   |
| GreenWood            | 3        | 0.28%   |
| ___                  | 2        | 0.19%   |
| Unknown (XXX)        | 2        | 0.19%   |
| TCT                  | 2        | 0.19%   |
| STD                  | 2        | 0.19%   |
| SGT                  | 2        | 0.19%   |
| RTK                  | 2        | 0.19%   |
| JVC                  | 2        | 0.19%   |
| Huion                | 2        | 0.19%   |
| HKC                  | 2        | 0.19%   |
| Hitachi              | 2        | 0.19%   |
| HannStar             | 2        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10       | 0.88%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 8        | 0.7%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8        | 0.7%    |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 8        | 0.7%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6        | 0.53%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6        | 0.53%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 6        | 0.53%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 5        | 0.44%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5        | 0.44%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5        | 0.44%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 5        | 0.44%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 5        | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4        | 0.35%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 700x400mm 31.7-inch    | 4        | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.35%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 4        | 0.35%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 0.35%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 4        | 0.35%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 4        | 0.35%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 4        | 0.35%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 4        | 0.35%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                    | 4        | 0.35%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 3        | 0.26%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.26%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3        | 0.26%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch | 3        | 0.26%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch | 3        | 0.26%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 3        | 0.26%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 3        | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.26%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 3        | 0.26%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.26%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 338x270mm 17.0-inch              | 3        | 0.26%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 3        | 0.26%   |
| GreenWood ARZOPA GWD1580 1920x1080 350x200mm 15.9-inch                | 3        | 0.26%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 697x392mm 31.5-inch              | 3        | 0.26%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 3        | 0.26%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                | 3        | 0.26%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 3        | 0.26%   |
| Gigabyte Technology M32U GBT3204 3840x2160 697x392mm 31.5-inch        | 3        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 456      | 44.1%   |
| 3840x2160 (4K)     | 146      | 14.12%  |
| 2560x1440 (QHD)    | 146      | 14.12%  |
| 3440x1440          | 45       | 4.35%   |
| 1680x1050 (WSXGA+) | 36       | 3.48%   |
| 1280x1024 (SXGA)   | 35       | 3.38%   |
| 1600x900 (HD+)     | 30       | 2.9%    |
| 1366x768 (WXGA)    | 23       | 2.22%   |
| 2560x1080          | 21       | 2.03%   |
| 1920x1200 (WUXGA)  | 21       | 2.03%   |
| 1440x900 (WXGA+)   | 16       | 1.55%   |
| 1360x768           | 14       | 1.35%   |
| 3840x1080          | 9        | 0.87%   |
| 2288x1287          | 8        | 0.77%   |
| 1920x540           | 4        | 0.39%   |
| Unknown            | 4        | 0.39%   |
| 2048x1152          | 3        | 0.29%   |
| 1600x1200          | 3        | 0.29%   |
| 3840x2560          | 2        | 0.19%   |
| 2560x1600          | 2        | 0.19%   |
| 1024x768 (XGA)     | 2        | 0.19%   |
| 3840x1600          | 1        | 0.1%    |
| 3280x1050          | 1        | 0.1%    |
| 2200x1650          | 1        | 0.1%    |
| 1920x1440          | 1        | 0.1%    |
| 14320x2640         | 1        | 0.1%    |
| 1280x960           | 1        | 0.1%    |
| 1280x768           | 1        | 0.1%    |
| 1280x720 (HD)      | 1        | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 231      | 21.39%  |
| 24      | 159      | 14.72%  |
| 23      | 124      | 11.48%  |
| 21      | 110      | 10.19%  |
| 31      | 81       | 7.5%    |
| 34      | 62       | 5.74%   |
| 19      | 38       | 3.52%   |
| 20      | 35       | 3.24%   |
| 22      | 29       | 2.69%   |
| 18      | 25       | 2.31%   |
| Unknown | 22       | 2.04%   |
| 84      | 16       | 1.48%   |
| 72      | 15       | 1.39%   |
| 32      | 12       | 1.11%   |
| 15      | 12       | 1.11%   |
| 17      | 11       | 1.02%   |
| 48      | 10       | 0.93%   |
| 54      | 9        | 0.83%   |
| 142     | 8        | 0.74%   |
| 26      | 8        | 0.74%   |
| 40      | 7        | 0.65%   |
| 28      | 7        | 0.65%   |
| 25      | 7        | 0.65%   |
| 52      | 4        | 0.37%   |
| 49      | 4        | 0.37%   |
| 42      | 4        | 0.37%   |
| 35      | 4        | 0.37%   |
| 65      | 3        | 0.28%   |
| 29      | 3        | 0.28%   |
| 38      | 2        | 0.19%   |
| 33      | 2        | 0.19%   |
| 16      | 2        | 0.19%   |
| 13      | 2        | 0.19%   |
| 86      | 1        | 0.09%   |
| 69      | 1        | 0.09%   |
| 63      | 1        | 0.09%   |
| 60      | 1        | 0.09%   |
| 57      | 1        | 0.09%   |
| 47      | 1        | 0.09%   |
| 43      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 456      | 44.31%  |
| 401-500        | 207      | 20.12%  |
| 601-700        | 122      | 11.86%  |
| 701-800        | 77       | 7.48%   |
| 1001-1500      | 33       | 3.21%   |
| 1501-2000      | 32       | 3.11%   |
| 351-400        | 27       | 2.62%   |
| 301-350        | 22       | 2.14%   |
| Unknown        | 22       | 2.14%   |
| 801-900        | 16       | 1.55%   |
| More than 2000 | 8        | 0.78%   |
| 901-1000       | 5        | 0.49%   |
| 201-300        | 2        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 712      | 74.79%  |
| 16/10   | 97       | 10.19%  |
| 21/9    | 67       | 7.04%   |
| 5/4     | 29       | 3.05%   |
| 32/9    | 11       | 1.16%   |
| 1.00    | 9        | 0.95%   |
| Unknown | 9        | 0.95%   |
| 4/3     | 7        | 0.74%   |
| 6/5     | 6        | 0.63%   |
| 3/2     | 2        | 0.21%   |
| 0.56    | 2        | 0.21%   |
| 2.12    | 1        | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 320      | 30.39%  |
| 301-350        | 234      | 22.22%  |
| 351-500        | 167      | 15.86%  |
| 151-200        | 114      | 10.83%  |
| More than 1000 | 63       | 5.98%   |
| 251-300        | 59       | 5.6%    |
| 141-150        | 29       | 2.75%   |
| 501-1000       | 28       | 2.66%   |
| Unknown        | 22       | 2.09%   |
| 101-110        | 12       | 1.14%   |
| 121-130        | 2        | 0.19%   |
| 81-90          | 1        | 0.09%   |
| 71-80          | 1        | 0.09%   |
| 91-100         | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 574      | 57.86%  |
| 101-120       | 246      | 24.8%   |
| 121-160       | 68       | 6.85%   |
| 1-50          | 50       | 5.04%   |
| 161-240       | 30       | 3.02%   |
| Unknown       | 22       | 2.22%   |
| More than 240 | 2        | 0.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 665      | 71.28%  |
| 2     | 211      | 22.62%  |
| 0     | 32       | 3.43%   |
| 3     | 20       | 2.14%   |
| 4     | 4        | 0.43%   |
| 5     | 1        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 571      | 41.59%  |
| Intel                                  | 449      | 32.7%   |
| Qualcomm Atheros                       | 64       | 4.66%   |
| MediaTek                               | 55       | 4.01%   |
| Broadcom                               | 44       | 3.2%    |
| TP-Link                                | 34       | 2.48%   |
| Microsoft                              | 19       | 1.38%   |
| Ralink                                 | 17       | 1.24%   |
| Ralink Technology                      | 14       | 1.02%   |
| Aquantia                               | 14       | 1.02%   |
| Samsung Electronics                    | 7        | 0.51%   |
| NetGear                                | 7        | 0.51%   |
| DisplayLink                            | 6        | 0.44%   |
| Qualcomm Atheros Communications        | 5        | 0.36%   |
| Google                                 | 5        | 0.36%   |
| Mellanox Technologies                  | 4        | 0.29%   |
| Marvell Technology Group               | 4        | 0.29%   |
| D-Link                                 | 4        | 0.29%   |
| ASUSTek Computer                       | 4        | 0.29%   |
| Xiaomi                                 | 3        | 0.22%   |
| ASIX Electronics                       | 3        | 0.22%   |
| Wilocity                               | 2        | 0.15%   |
| VIA Technologies                       | 2        | 0.15%   |
| STMicroelectronics                     | 2        | 0.15%   |
| Nvidia                                 | 2        | 0.15%   |
| Motorola PCS                           | 2        | 0.15%   |
| ICS Advent                             | 2        | 0.15%   |
| D-Link System                          | 2        | 0.15%   |
| Broadcom Limited                       | 2        | 0.15%   |
| 3Com                                   | 2        | 0.15%   |
| ZyDAS                                  | 1        | 0.07%   |
| Wacom                                  | 1        | 0.07%   |
| Tehuti Networks                        | 1        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.07%   |
| Qualcomm                               | 1        | 0.07%   |
| OPPO Electronics                       | 1        | 0.07%   |
| Microchip Technology                   | 1        | 0.07%   |
| Mercucys                               | 1        | 0.07%   |
| MCS                                    | 1        | 0.07%   |
| Linksys                                | 1        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 424      | 26.48%  |
| Realtek RTL8125 2.5GbE Controller                                               | 98       | 6.12%   |
| Intel Wi-Fi 6 AX200                                                             | 84       | 5.25%   |
| Intel Ethernet Controller I225-V                                                | 69       | 4.31%   |
| Intel I211 Gigabit Network Connection                                           | 66       | 4.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 33       | 2.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 32       | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 30       | 1.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 28       | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                            | 28       | 1.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                | 22       | 1.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 20       | 1.25%   |
| Intel Ethernet Connection I217-LM                                               | 19       | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                            | 18       | 1.12%   |
| Microsoft Xbox Wireless Adapter for Windows                                     | 16       | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 14       | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                           | 14       | 0.87%   |
| Realtek 802.11ac NIC                                                            | 12       | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                            | 12       | 0.75%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                    | 12       | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 11       | 0.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 11       | 0.69%   |
| Intel 82574L Gigabit Network Connection                                         | 10       | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 9        | 0.56%   |
| Intel Ethernet Connection I217-V                                                | 9        | 0.56%   |
| Intel Ethernet Connection (14) I219-V                                           | 9        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                              | 8        | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 8        | 0.5%    |
| Intel 82579V Gigabit Network Connection                                         | 8        | 0.5%    |
| Ralink MT7601U Wireless Adapter                                                 | 7        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 7        | 0.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 7        | 0.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                | 7        | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 7        | 0.44%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 7        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 6        | 0.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                           | 6        | 0.37%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 6        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 6        | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 6        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 227      | 41.35%  |
| Realtek Semiconductor                 | 89       | 16.21%  |
| MediaTek                              | 55       | 10.02%  |
| Qualcomm Atheros                      | 39       | 7.1%    |
| TP-Link                               | 34       | 6.19%   |
| Broadcom                              | 25       | 4.55%   |
| Microsoft                             | 18       | 3.28%   |
| Ralink                                | 17       | 3.1%    |
| Ralink Technology                     | 14       | 2.55%   |
| NetGear                               | 7        | 1.28%   |
| Qualcomm Atheros Communications       | 5        | 0.91%   |
| ASUSTek Computer                      | 4        | 0.73%   |
| Wilocity                              | 2        | 0.36%   |
| D-Link                                | 2        | 0.36%   |
| ZyDAS                                 | 1        | 0.18%   |
| Wacom                                 | 1        | 0.18%   |
| Mercucys                              | 1        | 0.18%   |
| Linksys                               | 1        | 0.18%   |
| IMC Networks                          | 1        | 0.18%   |
| Edimax Technology                     | 1        | 0.18%   |
| D-Link System                         | 1        | 0.18%   |
| Broadcom Limited                      | 1        | 0.18%   |
| Belkin Components                     | 1        | 0.18%   |
| AVM                                   | 1        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 84       | 15.19%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 32       | 5.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 30       | 5.42%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 28       | 5.06%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 22       | 3.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 20       | 3.62%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 16       | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 14       | 2.53%   |
| Realtek 802.11ac NIC                                          | 12       | 2.17%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 12       | 2.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 11       | 1.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 9        | 1.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 8        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 8        | 1.45%   |
| Ralink MT7601U Wireless Adapter                               | 7        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 7        | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 7        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 7        | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 6        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 6        | 1.08%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 6        | 1.08%   |
| TP-Link Archer T4U ver.3                                      | 5        | 0.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 5        | 0.9%    |
| TP-Link 802.11ac NIC                                          | 5        | 0.9%    |
| Ralink RT2800 802.11n PCI                                     | 5        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5        | 0.9%    |
| Intel Wireless 7265                                           | 5        | 0.9%    |
| Intel Wireless 3165                                           | 5        | 0.9%    |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter  | 5        | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 4        | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 4        | 0.72%   |
| TP-Link 802.11ac WLAN Adapter                                 | 4        | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4        | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 4        | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                     | 4        | 0.72%   |
| Intel Wireless 8265 / 8275                                    | 4        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4        | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 3        | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.54%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 543      | 54.35%  |
| Intel                                  | 342      | 34.23%  |
| Qualcomm Atheros                       | 30       | 3%      |
| Broadcom                               | 18       | 1.8%    |
| Aquantia                               | 14       | 1.4%    |
| Samsung Electronics                    | 7        | 0.7%    |
| DisplayLink                            | 6        | 0.6%    |
| Google                                 | 5        | 0.5%    |
| Marvell Technology Group               | 4        | 0.4%    |
| Xiaomi                                 | 3        | 0.3%    |
| Mellanox Technologies                  | 3        | 0.3%    |
| ASIX Electronics                       | 3        | 0.3%    |
| VIA Technologies                       | 2        | 0.2%    |
| Nvidia                                 | 2        | 0.2%    |
| ICS Advent                             | 2        | 0.2%    |
| D-Link                                 | 2        | 0.2%    |
| 3Com                                   | 2        | 0.2%    |
| Tehuti Networks                        | 1        | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.1%    |
| Qualcomm                               | 1        | 0.1%    |
| OPPO Electronics                       | 1        | 0.1%    |
| Motorola PCS                           | 1        | 0.1%    |
| Microsoft                              | 1        | 0.1%    |
| Huawei Technologies                    | 1        | 0.1%    |
| HMD Global                             | 1        | 0.1%    |
| Hewlett-Packard                        | 1        | 0.1%    |
| D-Link System                          | 1        | 0.1%    |
| Broadcom Limited                       | 1        | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 424      | 40.89%  |
| Realtek RTL8125 2.5GbE Controller                                               | 98       | 9.45%   |
| Intel Ethernet Controller I225-V                                                | 69       | 6.65%   |
| Intel I211 Gigabit Network Connection                                           | 66       | 6.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 33       | 3.18%   |
| Intel Ethernet Connection (2) I219-V                                            | 28       | 2.7%    |
| Intel Ethernet Connection I217-LM                                               | 19       | 1.83%   |
| Intel Ethernet Connection (7) I219-V                                            | 18       | 1.74%   |
| Intel Ethernet Connection (2) I219-LM                                           | 14       | 1.35%   |
| Intel Ethernet Connection (2) I218-V                                            | 12       | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 11       | 1.06%   |
| Intel 82574L Gigabit Network Connection                                         | 10       | 0.96%   |
| Intel Ethernet Connection I217-V                                                | 9        | 0.87%   |
| Intel Ethernet Connection (14) I219-V                                           | 9        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                         | 8        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 7        | 0.68%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 7        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 6        | 0.58%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 6        | 0.58%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 6        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 6        | 0.58%   |
| Intel I210 Gigabit Network Connection                                           | 6        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                           | 6        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                      | 6        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                | 6        | 0.58%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 6        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 5        | 0.48%   |
| Intel Ethernet Connection (17) I219-V                                           | 5        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                 | 4        | 0.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 4        | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 4        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 4        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 4        | 0.39%   |
| Intel Ethernet Controller I226-V                                                | 4        | 0.39%   |
| Google Pixel 8                                                                  | 4        | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                               | 4        | 0.39%   |
| Intel Ethernet Connection (11) I219-LM                                          | 3        | 0.29%   |
| Intel 82575EB Gigabit Network Connection                                        | 3        | 0.29%   |
| Intel 82546GB Gigabit Ethernet Controller                                       | 3        | 0.29%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 3        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 910      | 63.24%  |
| WiFi     | 518      | 36%     |
| Modem    | 8        | 0.56%   |
| Unknown  | 3        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 695      | 70.85%  |
| WiFi     | 286      | 29.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 465      | 50.27%  |
| 2     | 389      | 42.05%  |
| 3     | 50       | 5.41%   |
| 4     | 12       | 1.3%    |
| 0     | 7        | 0.76%   |
| 6     | 1        | 0.11%   |
| 5     | 1        | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 632      | 67.52%  |
| Yes  | 304      | 32.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 218      | 47.39%  |
| Cambridge Silicon Radio         | 61       | 13.26%  |
| Realtek Semiconductor           | 45       | 9.78%   |
| MediaTek                        | 38       | 8.26%   |
| ASUSTek Computer                | 21       | 4.57%   |
| Broadcom                        | 14       | 3.04%   |
| Qualcomm Atheros Communications | 13       | 2.83%   |
| IMC Networks                    | 12       | 2.61%   |
| TP-Link                         | 11       | 2.39%   |
| Foxconn / Hon Hai               | 9        | 1.96%   |
| Apple                           | 4        | 0.87%   |
| Lite-On Technology              | 3        | 0.65%   |
| Realtek                         | 2        | 0.43%   |
| Unknown                         | 2        | 0.43%   |
| Mobile Action Technology        | 1        | 0.22%   |
| Hewlett-Packard                 | 1        | 0.22%   |
| Foxconn International           | 1        | 0.22%   |
| Edimax Technology               | 1        | 0.22%   |
| Dynex                           | 1        | 0.22%   |
| D-Link                          | 1        | 0.22%   |
| Actions                         | 1        | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 80       | 17.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 61       | 13.26%  |
| MediaTek Wireless_Device                              | 38       | 8.26%   |
| Realtek Bluetooth Radio                               | 35       | 7.61%   |
| Intel AX210 Bluetooth                                 | 32       | 6.96%   |
| Intel Wireless-AC 3168 Bluetooth                      | 30       | 6.52%   |
| Intel AX201 Bluetooth                                 | 22       | 4.78%   |
| Intel Bluetooth wireless interface                    | 19       | 4.13%   |
| TP-Link UB500 Adapter                                 | 11       | 2.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 11       | 2.39%   |
| Intel Bluetooth Device                                | 11       | 2.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10       | 2.17%   |
| Foxconn / Hon Hai Wireless_Device                     | 9        | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                        | 8        | 1.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 8        | 1.74%   |
| ASUS ASUS USB-BT500                                   | 8        | 1.74%   |
| Qualcomm Atheros  Bluetooth Device                    | 6        | 1.3%    |
| IMC Networks Wireless_Device                          | 6        | 1.3%    |
| IMC Networks Bluetooth Radio                          | 4        | 0.87%   |
| ASUS BCM20702A0                                       | 4        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 0.65%   |
| Broadcom Bluetooth 3.0 Dongle                         | 3        | 0.65%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3        | 0.65%   |
| Realtek Bluetooth 5.3 Radio                           | 2        | 0.43%   |
| Realtek Bluetooth Radio                               | 2        | 0.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2        | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 2        | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 2        | 0.43%   |
| IMC Networks Bluetooth Device                         | 2        | 0.43%   |
| ASUS Bluetooth Radio                                  | 2        | 0.43%   |
| ASUS Bluetooth Device                                 | 2        | 0.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2        | 0.43%   |
| Apple Bluetooth Host Controller                       | 2        | 0.43%   |
| Unknown                                               | 2        | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1        | 0.22%   |
| Mobile Action MA-730/MA-730G Bluetooth Adapter        | 1        | 0.22%   |
| Lite-On Bluetooth Radio                               | 1        | 0.22%   |
| Lite-On Bluetooth Device                              | 1        | 0.22%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1        | 0.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 510      | 29.67%  |
| Intel                                           | 469      | 27.28%  |
| Nvidia                                          | 349      | 20.3%   |
| C-Media Electronics                             | 61       | 3.55%   |
| Logitech                                        | 29       | 1.69%   |
| ASUSTek Computer                                | 21       | 1.22%   |
| Kingston Technology                             | 19       | 1.11%   |
| Micro Star International                        | 17       | 0.99%   |
| SteelSeries ApS                                 | 16       | 0.93%   |
| JMTek                                           | 15       | 0.87%   |
| Creative Labs                                   | 15       | 0.87%   |
| Razer USA                                       | 13       | 0.76%   |
| Generalplus Technology                          | 12       | 0.7%    |
| Focusrite-Novation                              | 11       | 0.64%   |
| Texas Instruments                               | 7        | 0.41%   |
| GN Netcom                                       | 7        | 0.41%   |
| Creative Technology                             | 7        | 0.41%   |
| RODE Microphones                                | 6        | 0.35%   |
| Plantronics                                     | 6        | 0.35%   |
| Corsair                                         | 6        | 0.35%   |
| Sony                                            | 5        | 0.29%   |
| Realtek Semiconductor                           | 5        | 0.29%   |
| KTMicro                                         | 5        | 0.29%   |
| Hewlett-Packard                                 | 5        | 0.29%   |
| Dell                                            | 5        | 0.29%   |
| Zoran Co. Personal Media Division (Nogatech)    | 4        | 0.23%   |
| FIFINE Microphones                              | 4        | 0.23%   |
| Audio-Technica                                  | 4        | 0.23%   |
| Schiit Audio                                    | 3        | 0.17%   |
| Samson Technologies                             | 3        | 0.17%   |
| Microsoft                                       | 3        | 0.17%   |
| JBL                                             | 3        | 0.17%   |
| BEHRINGER International                         | 3        | 0.17%   |
| Astro Gaming                                    | 3        | 0.17%   |
| Yamaha                                          | 2        | 0.12%   |
| XMOS                                            | 2        | 0.12%   |
| VIA Technologies                                | 2        | 0.12%   |
| Unknown                                         | 2        | 0.12%   |
| SAVITECH                                        | 2        | 0.12%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 167      | 7.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 117      | 5.59%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 109      | 5.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 60       | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 57       | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 53       | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 52       | 2.48%   |
| Intel 200 Series PCH HD Audio                                              | 51       | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50       | 2.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 48       | 2.29%   |
| Intel Alder Lake-S HD Audio Controller                                     | 44       | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 42       | 2.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 42       | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 41       | 1.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 39       | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36       | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35       | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 31       | 1.48%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 29       | 1.39%   |
| Nvidia GP104 High Definition Audio Controller                              | 28       | 1.34%   |
| Nvidia GA106 High Definition Audio Controller                              | 25       | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 24       | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                              | 23       | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23       | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 23       | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 21       | 1%      |
| ASUSTek Computer USB Audio                                                 | 18       | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 17       | 0.81%   |
| Micro Star International USB Audio                                         | 16       | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 15       | 0.72%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 15       | 0.72%   |
| AMD FCH Azalia Controller                                                  | 15       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 14       | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 0.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13       | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12       | 0.57%   |
| Nvidia GA102 High Definition Audio Controller                              | 12       | 0.57%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 12       | 0.57%   |
| Intel Comet Lake PCH cAVS                                                  | 12       | 0.57%   |
| Generalplus Technology USB Audio Device                                    | 12       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 75       | 19.58%  |
| Kingston                     | 60       | 15.67%  |
| G.Skill                      | 55       | 14.36%  |
| Unknown                      | 30       | 7.83%   |
| Samsung Electronics          | 27       | 7.05%   |
| Crucial                      | 26       | 6.79%   |
| A-DATA Technology            | 18       | 4.7%    |
| SK hynix                     | 17       | 4.44%   |
| Micron Technology            | 17       | 4.44%   |
| Unknown                      | 10       | 2.61%   |
| Smart                        | 7        | 1.83%   |
| Team                         | 6        | 1.57%   |
| Apacer                       | 4        | 1.04%   |
| Patriot                      | 3        | 0.78%   |
| Silicon Power                | 2        | 0.52%   |
| Ramaxel Technology           | 2        | 0.52%   |
| PNY                          | 2        | 0.52%   |
| Nanya Technology             | 2        | 0.52%   |
| GOODRAM                      | 2        | 0.52%   |
| Unknown (ABCD)               | 1        | 0.26%   |
| Unknown (8A02)               | 1        | 0.26%   |
| Unknown (0x5846)             | 1        | 0.26%   |
| Unknown (0x0E9D)             | 1        | 0.26%   |
| Transcend                    | 1        | 0.26%   |
| Timetec                      | 1        | 0.26%   |
| Sesame                       | 1        | 0.26%   |
| Qumo                         | 1        | 0.26%   |
| Patriot Memory (PDP Systems) | 1        | 0.26%   |
| Mushkin                      | 1        | 0.26%   |
| Lexar                        | 1        | 0.26%   |
| GIGA-BYTE                    | 1        | 0.26%   |
| GeIL                         | 1        | 0.26%   |
| EVGA                         | 1        | 0.26%   |
| CSX                          | 1        | 0.26%   |
| Atermiter                    | 1        | 0.26%   |
| AMD                          | 1        | 0.26%   |
| 89450000830B                 | 1        | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 10       | 2.45%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 9        | 2.21%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 8        | 1.96%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 6        | 1.47%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s             | 5        | 1.23%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s     | 4        | 0.98%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 4        | 0.98%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s  | 4        | 0.98%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 3        | 0.74%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s    | 3        | 0.74%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 0.74%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 3        | 0.74%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s    | 3        | 0.74%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s  | 3        | 0.74%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s  | 3        | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 2        | 0.49%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s      | 2        | 0.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.49%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s  | 2        | 0.49%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 2        | 0.49%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 2        | 0.49%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 2        | 0.49%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s     | 2        | 0.49%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 6400MT/s        | 2        | 0.49%   |
| Kingston RAM KF548C38-32 32GB DIMM DDR5 4800MT/s        | 2        | 0.49%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 0.49%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.49%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1333MT/s   | 2        | 0.49%   |
| G.Skill RAM F5-6000J3238G32G 32GB DIMM DDR5 4800MT/s    | 2        | 0.49%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s    | 2        | 0.49%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s    | 2        | 0.49%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s   | 2        | 0.49%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 2        | 0.49%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 0.49%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 2        | 0.49%   |
| Corsair RAM CMV8GX4M1A2133C15 8192MB DIMM DDR4 2733MT/s | 2        | 0.49%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s    | 2        | 0.49%   |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s    | 2        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 207      | 60.7%   |
| DDR3    | 66       | 19.35%  |
| DDR5    | 35       | 10.26%  |
| Unknown | 13       | 3.81%   |
| DDR2    | 9        | 2.64%   |
| SDRAM   | 7        | 2.05%   |
| DDR     | 2        | 0.59%   |
| LPDDR4  | 1        | 0.29%   |
| DRAM    | 1        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 309      | 91.96%  |
| SODIMM | 25       | 7.44%   |
| RIMM   | 2        | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 137      | 37.74%  |
| 16384 | 99       | 27.27%  |
| 4096  | 45       | 12.4%   |
| 32768 | 44       | 12.12%  |
| 2048  | 28       | 7.71%   |
| 1024  | 9        | 2.48%   |
| 49152 | 1        | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 61       | 16.27%  |
| 3600    | 42       | 11.2%   |
| 1600    | 42       | 11.2%   |
| 1333    | 21       | 5.6%    |
| 2400    | 19       | 5.07%   |
| 2667    | 18       | 4.8%    |
| 4800    | 13       | 3.47%   |
| 2133    | 12       | 3.2%    |
| 3733    | 11       | 2.93%   |
| 3800    | 10       | 2.67%   |
| 3400    | 9        | 2.4%    |
| 3534    | 8        | 2.13%   |
| 6400    | 6        | 1.6%    |
| 6000    | 6        | 1.6%    |
| 3000    | 6        | 1.6%    |
| 1800    | 6        | 1.6%    |
| 667     | 6        | 1.6%    |
| 5600    | 5        | 1.33%   |
| 1866    | 5        | 1.33%   |
| 800     | 5        | 1.33%   |
| Unknown | 5        | 1.33%   |
| 3866    | 4        | 1.07%   |
| 3666    | 4        | 1.07%   |
| 2666    | 4        | 1.07%   |
| 1867    | 4        | 1.07%   |
| 3066    | 3        | 0.8%    |
| 2933    | 3        | 0.8%    |
| 2733    | 3        | 0.8%    |
| 1067    | 3        | 0.8%    |
| 5800    | 2        | 0.53%   |
| 5200    | 2        | 0.53%   |
| 3466    | 2        | 0.53%   |
| 3334    | 2        | 0.53%   |
| 3266    | 2        | 0.53%   |
| 2800    | 2        | 0.53%   |
| 2448    | 2        | 0.53%   |
| 1639    | 2        | 0.53%   |
| 1400    | 2        | 0.53%   |
| 400     | 2        | 0.53%   |
| 12800   | 1        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 14       | 46.67%  |
| Brother Industries  | 5        | 16.67%  |
| Seiko Epson         | 3        | 10%     |
| Dymo-CoStar         | 3        | 10%     |
| Canon               | 3        | 10%     |
| Samsung Electronics | 1        | 3.33%   |
| Pantum              | 1        | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 2        | 6.67%   |
| Seiko Epson WF-2860 Series             | 1        | 3.33%   |
| Seiko Epson L120 Series                | 1        | 3.33%   |
| Seiko Epson AL-M310DN                  | 1        | 3.33%   |
| Samsung M2070 Series                   | 1        | 3.33%   |
| Pantum M6500W-series                   | 1        | 3.33%   |
| HP LaserJet Professional P1102w        | 1        | 3.33%   |
| HP LaserJet Pro M148-M149              | 1        | 3.33%   |
| HP LaserJet P1102                      | 1        | 3.33%   |
| HP LaserJet 1020                       | 1        | 3.33%   |
| HP LaserJet 1010                       | 1        | 3.33%   |
| HP ENVY Photo 7800 series              | 1        | 3.33%   |
| HP ENVY Inspire 7200 series            | 1        | 3.33%   |
| HP ENVY 5000 series                    | 1        | 3.33%   |
| HP DeskJet 5810 series                 | 1        | 3.33%   |
| HP DeskJet 5650c                       | 1        | 3.33%   |
| HP DeskJet 3700 series                 | 1        | 3.33%   |
| HP DeskJet 35xx                        | 1        | 3.33%   |
| HP DeskJet 2700 series                 | 1        | 3.33%   |
| HP Deskjet 2050 J510                   | 1        | 3.33%   |
| Dymo-CoStar LabelWriter 400            | 1        | 3.33%   |
| Canon TR4500 series                    | 1        | 3.33%   |
| Canon PIXMA MP250                      | 1        | 3.33%   |
| Canon MF3010                           | 1        | 3.33%   |
| Brother HL-L2390DW                     | 1        | 3.33%   |
| Brother HL-2270DW Laser Printer        | 1        | 3.33%   |
| Brother HL-2130 series                 | 1        | 3.33%   |
| Brother HL-1440 Laser Printer          | 1        | 3.33%   |
| Brother DCP-L3550CDW                   | 1        | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 8        | 80%     |
| Seiko Epson | 2        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                       | 4        | 40%     |
| Seiko Epson GT-X770 [Perfection V500]         | 1        | 10%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 10%     |
| Canon CanoScan LiDE 700F                      | 1        | 10%     |
| Canon CanoScan LiDE 220                       | 1        | 10%     |
| Canon CanoScan LiDE 110                       | 1        | 10%     |
| Canon CanoScan 4400F                          | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 101      | 44.69%  |
| Microdia                               | 15       | 6.64%   |
| Microsoft                              | 13       | 5.75%   |
| Apple                                  | 8        | 3.54%   |
| Sunplus Innovation Technology          | 7        | 3.1%    |
| Samsung Electronics                    | 6        | 2.65%   |
| Realtek Semiconductor                  | 5        | 2.21%   |
| Razer USA                              | 5        | 2.21%   |
| webcamvendor                           | 4        | 1.77%   |
| Trust                                  | 4        | 1.77%   |
| Generalplus Technology                 | 4        | 1.77%   |
| Chicony Electronics                    | 4        | 1.77%   |
| AVerMedia Technologies                 | 4        | 1.77%   |
| ARC International                      | 4        | 1.77%   |
| Jieli Technology                       | 3        | 1.33%   |
| Google                                 | 3        | 1.33%   |
| Cubeternet                             | 3        | 1.33%   |
| Unknown                                | 3        | 1.33%   |
| Z-Star Microelectronics                | 2        | 0.88%   |
| XHT-211220-ZW                          | 2        | 0.88%   |
| Tobii Technology AB                    | 2        | 0.88%   |
| MacroSilicon                           | 2        | 0.88%   |
| KYE Systems (Mouse Systems)            | 2        | 0.88%   |
| Bison Electronics                      | 2        | 0.88%   |
| Valve Software                         | 1        | 0.44%   |
| Sunplus IT                             | 1        | 0.44%   |
| Sonix Technology                       | 1        | 0.44%   |
| Ruision                                | 1        | 0.44%   |
| Pixart Imaging                         | 1        | 0.44%   |
| LG Electronics                         | 1        | 0.44%   |
| Insta360                               | 1        | 0.44%   |
| Hewlett-Packard                        | 1        | 0.44%   |
| GEMBIRD                                | 1        | 0.44%   |
| Fuzhou Rockchip Electronics Company    | 1        | 0.44%   |
| ezcap                                  | 1        | 0.44%   |
| Elecom                                 | 1        | 0.44%   |
| Dell                                   | 1        | 0.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.44%   |
| Aveo Technology                        | 1        | 0.44%   |
| Asuscom Network                        | 1        | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 15       | 6.64%   |
| Logitech HD Pro Webcam C920             | 14       | 6.19%   |
| Logitech HD Webcam C525                 | 8        | 3.54%   |
| Logitech C920 PRO HD Webcam             | 8        | 3.54%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 8        | 3.54%   |
| Logitech Webcam C170                    | 7        | 3.1%    |
| Logitech C922 Pro Stream Webcam         | 7        | 3.1%    |
| Samsung Galaxy series, misc. (MTP mode) | 6        | 2.65%   |
| Logitech BRIO Ultra HD Webcam           | 6        | 2.65%   |
| Microsoft LifeCam HD-3000               | 5        | 2.21%   |
| Logitech C505 HD Webcam                 | 5        | 2.21%   |
| webcamvendor webcamproduct              | 4        | 1.77%   |
| Microdia Webcam Vitade AF               | 4        | 1.77%   |
| Microdia USB 2.0 Camera                 | 4        | 1.77%   |
| Logitech HD Webcam C615                 | 4        | 1.77%   |
| Generalplus GENERAL WEBCAM              | 4        | 1.77%   |
| AVerMedia Live Streamer CAM 313         | 4        | 1.77%   |
| ARC International Camera                | 4        | 1.77%   |
| Trust USB Camera                        | 3        | 1.33%   |
| Microdia Integrated Camera              | 3        | 1.33%   |
| Logitech Webcam C310                    | 3        | 1.33%   |
| Logitech StreamCam                      | 3        | 1.33%   |
| Logitech HD Webcam C910                 | 3        | 1.33%   |
| Jieli USB PHY 2.0                       | 3        | 1.33%   |
| Unknown                                 | 3        | 1.33%   |
| XHT-211220-ZW Photry PC230A QHD Webcam  | 2        | 0.88%   |
| Tobii AB EyeChip                        | 2        | 0.88%   |
| Sunplus HD 720P webcam                  | 2        | 0.88%   |
| Realtek Full HD webcam                  | 2        | 0.88%   |
| Razer USA Razer Kiyo Pro                | 2        | 0.88%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 0.88%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 2        | 0.88%   |
| Microsoft LifeCam VX-2000               | 2        | 0.88%   |
| Logitech Webcam C925e                   | 2        | 0.88%   |
| Logitech Webcam B500                    | 2        | 0.88%   |
| Logitech HD Webcam C510                 | 2        | 0.88%   |
| Logitech BRIO 4K Stream Edition         | 2        | 0.88%   |
| Google HD USB Camera                    | 2        | 0.88%   |
| Cubeternet GL-UPC822 UVC WebCam         | 2        | 0.88%   |
| Z-Star Vega USB 2.0 Camera              | 1        | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 40%     |
| Synaptics             | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| AuthenTec             | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor                | 2        | 40%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 20%     |
| AuthenTec Fingerprint Sensor                 | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 1        | 14.29%  |
| VASCO Data Security International | 1        | 14.29%  |
| Realtek Semiconductor             | 1        | 14.29%  |
| Gemalto (was Gemplus)             | 1        | 14.29%  |
| Cherry                            | 1        | 14.29%  |
| Bit4id                            | 1        | 14.29%  |
| Aladdin Knowledge Systems         | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 1        | 14.29%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 14.29%  |
| Realtek Semiconductor Smart Card Reader Interface               | 1        | 14.29%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 1        | 14.29%  |
| Cherry Smart Terminal XX44                                      | 1        | 14.29%  |
| Bit4id miniLector EVO                                           | 1        | 14.29%  |
| Aladdin Knowledge Systems Token JC                              | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 786      | 84.7%   |
| 1     | 123      | 13.25%  |
| 2     | 12       | 1.29%   |
| 4     | 3        | 0.32%   |
| 3     | 3        | 0.32%   |
| 6     | 1        | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 53       | 33.33%  |
| Net/wireless             | 45       | 28.3%   |
| Unassigned class         | 15       | 9.43%   |
| Multimedia controller    | 8        | 5.03%   |
| Camera                   | 8        | 5.03%   |
| Sound                    | 7        | 4.4%    |
| Communication controller | 6        | 3.77%   |
| Net/ethernet             | 5        | 3.14%   |
| Fingerprint reader       | 5        | 3.14%   |
| Firewire controller      | 2        | 1.26%   |
| Card reader              | 2        | 1.26%   |
| Storage/raid             | 1        | 0.63%   |
| Storage/nvme             | 1        | 0.63%   |
| Bluetooth                | 1        | 0.63%   |

