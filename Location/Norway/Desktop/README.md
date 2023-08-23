Linux in Norway - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

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

Total: 813

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X570 AORUS ELITE            | [0c0df32662](https://linux-hardware.org/?probe=0c0df32662) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASRock        | H77M-ITX                    | [01dc3bfc4b](https://linux-hardware.org/?probe=01dc3bfc4b) | Aug 09, 2023 |
| MSI           | X99A RAIDER                 | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| MSI           | X99S SLI PLUS               | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| MSI           | X99A RAIDER                 | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [f4e52f14b5](https://linux-hardware.org/?probe=f4e52f14b5) | Jul 22, 2023 |
| Dell          | 0CRH6C A02                  | [abf1be3307](https://linux-hardware.org/?probe=abf1be3307) | Jul 16, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [e241cdbe45](https://linux-hardware.org/?probe=e241cdbe45) | Jul 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f99bab3454](https://linux-hardware.org/?probe=f99bab3454) | Jul 12, 2023 |
| Dell          | 0CRH6C A02                  | [333813fa10](https://linux-hardware.org/?probe=333813fa10) | Jul 11, 2023 |
| Dell          | 0CRH6C A02                  | [66fb93438f](https://linux-hardware.org/?probe=66fb93438f) | Jul 11, 2023 |
| MSI           | X99A RAIDER                 | [30658f7ab7](https://linux-hardware.org/?probe=30658f7ab7) | Jul 09, 2023 |
| MSI           | B550M PRO-VDH               | [220629a068](https://linux-hardware.org/?probe=220629a068) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | [f86f946540](https://linux-hardware.org/?probe=f86f946540) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | [40ca2e97cc](https://linux-hardware.org/?probe=40ca2e97cc) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| Unknown       | Unknown                     | [556867d0f2](https://linux-hardware.org/?probe=556867d0f2) | Jul 02, 2023 |
| Unknown       | Unknown                     | [b36612c9e4](https://linux-hardware.org/?probe=b36612c9e4) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | [c2b529a2ee](https://linux-hardware.org/?probe=c2b529a2ee) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | [d7efa66a54](https://linux-hardware.org/?probe=d7efa66a54) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| MSI           | X99A RAIDER                 | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Dell          | 0CRH6C A02                  | [7ce8bcbc26](https://linux-hardware.org/?probe=7ce8bcbc26) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| MSI           | X299 TOMAHAWK               | [aa2a65c324](https://linux-hardware.org/?probe=aa2a65c324) | Jun 19, 2023 |
| Dell          | 0CRH6C A02                  | [3dc796f9d3](https://linux-hardware.org/?probe=3dc796f9d3) | Jun 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [87cd6547ad](https://linux-hardware.org/?probe=87cd6547ad) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| MSI           | P67A-C45                    | [4f3aa2017f](https://linux-hardware.org/?probe=4f3aa2017f) | Jun 13, 2023 |
| MSI           | X99A RAIDER                 | [1fd265b6d8](https://linux-hardware.org/?probe=1fd265b6d8) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c5e1b092a](https://linux-hardware.org/?probe=1c5e1b092a) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | [4ab556e4b8](https://linux-hardware.org/?probe=4ab556e4b8) | Jun 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| MSI           | P67A-C45                    | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| MSI           | X99A RAIDER                 | [d70fe31101](https://linux-hardware.org/?probe=d70fe31101) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| MSI           | X99A RAIDER                 | [36173d5a42](https://linux-hardware.org/?probe=36173d5a42) | Jun 05, 2023 |
| MSI           | B550M PRO-VDH               | [d09ba05086](https://linux-hardware.org/?probe=d09ba05086) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | [9f13a5184c](https://linux-hardware.org/?probe=9f13a5184c) | Jun 03, 2023 |
| MSI           | X99A RAIDER                 | [b951e6223c](https://linux-hardware.org/?probe=b951e6223c) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| MSI           | X99A RAIDER                 | [3404cb6c67](https://linux-hardware.org/?probe=3404cb6c67) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8b96413dfd](https://linux-hardware.org/?probe=8b96413dfd) | May 30, 2023 |
| MSI           | X99A RAIDER                 | [ffe895debc](https://linux-hardware.org/?probe=ffe895debc) | May 30, 2023 |
| MSI           | X99A RAIDER                 | [0b7f7fb99a](https://linux-hardware.org/?probe=0b7f7fb99a) | May 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [38936854c8](https://linux-hardware.org/?probe=38936854c8) | May 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| MSI           | B550M PRO-VDH               | [f7fddb36e8](https://linux-hardware.org/?probe=f7fddb36e8) | May 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [362ad8bcaf](https://linux-hardware.org/?probe=362ad8bcaf) | May 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec7d8d12e1](https://linux-hardware.org/?probe=ec7d8d12e1) | May 23, 2023 |
| MSI           | X99A RAIDER                 | [1b7089a58b](https://linux-hardware.org/?probe=1b7089a58b) | May 23, 2023 |
| MSI           | X99A RAIDER                 | [1fd2d41164](https://linux-hardware.org/?probe=1fd2d41164) | May 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ecc77ee7a9](https://linux-hardware.org/?probe=ecc77ee7a9) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B550M PRO-VDH               | [3f5a6968d4](https://linux-hardware.org/?probe=3f5a6968d4) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [9b29aafd95](https://linux-hardware.org/?probe=9b29aafd95) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4344603b6](https://linux-hardware.org/?probe=d4344603b6) | May 15, 2023 |
| MSI           | X99A RAIDER                 | [14928b0276](https://linux-hardware.org/?probe=14928b0276) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | [903ece310a](https://linux-hardware.org/?probe=903ece310a) | May 14, 2023 |
| MSI           | X99A RAIDER                 | [2d942e3436](https://linux-hardware.org/?probe=2d942e3436) | May 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6bfe747b4d](https://linux-hardware.org/?probe=6bfe747b4d) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | X99A RAIDER                 | [2e2b57870b](https://linux-hardware.org/?probe=2e2b57870b) | May 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4243b6a57b](https://linux-hardware.org/?probe=4243b6a57b) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| MSI           | X99A RAIDER                 | [08adc44b64](https://linux-hardware.org/?probe=08adc44b64) | May 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [e985d1beac](https://linux-hardware.org/?probe=e985d1beac) | May 12, 2023 |
| MSI           | X99A RAIDER                 | [dfdc7713b6](https://linux-hardware.org/?probe=dfdc7713b6) | May 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [e2bbbffe45](https://linux-hardware.org/?probe=e2bbbffe45) | May 09, 2023 |
| MSI           | X99A RAIDER                 | [bc30b63ce3](https://linux-hardware.org/?probe=bc30b63ce3) | May 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [53c03d6942](https://linux-hardware.org/?probe=53c03d6942) | May 08, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [98008481eb](https://linux-hardware.org/?probe=98008481eb) | May 07, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| MSI           | X299 SLI PLUS               | [db983da641](https://linux-hardware.org/?probe=db983da641) | May 04, 2023 |
| MSI           | MS-7025                     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [513f1e9efb](https://linux-hardware.org/?probe=513f1e9efb) | May 02, 2023 |
| MSI           | X99A RAIDER                 | [51c2405640](https://linux-hardware.org/?probe=51c2405640) | May 02, 2023 |
| MSI           | X99A RAIDER                 | [f2c73a1fbb](https://linux-hardware.org/?probe=f2c73a1fbb) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| MSI           | X99A RAIDER                 | [606b173cab](https://linux-hardware.org/?probe=606b173cab) | Apr 30, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| MSI           | X99A RAIDER                 | [d6bf052a2f](https://linux-hardware.org/?probe=d6bf052a2f) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e14205d01a](https://linux-hardware.org/?probe=e14205d01a) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| MSI           | X99A RAIDER                 | [71983d0574](https://linux-hardware.org/?probe=71983d0574) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| Gigabyte      | GA-970A-UD3                 | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0f678c5ded](https://linux-hardware.org/?probe=0f678c5ded) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [ee48e89e45](https://linux-hardware.org/?probe=ee48e89e45) | Apr 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | [57cc389eff](https://linux-hardware.org/?probe=57cc389eff) | Apr 14, 2023 |
| MSI           | B550M PRO-VDH               | [0d0a704eae](https://linux-hardware.org/?probe=0d0a704eae) | Apr 12, 2023 |
| MSI           | P67A-C45                    | [25a90d2595](https://linux-hardware.org/?probe=25a90d2595) | Apr 10, 2023 |
| MSI           | X99A RAIDER                 | [35d855a901](https://linux-hardware.org/?probe=35d855a901) | Apr 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| MSI           | X99A RAIDER                 | [3f8d1c6a26](https://linux-hardware.org/?probe=3f8d1c6a26) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| MSI           | X99A RAIDER                 | [d6f7c92fc7](https://linux-hardware.org/?probe=d6f7c92fc7) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| MSI           | X99A RAIDER                 | [50e745e72a](https://linux-hardware.org/?probe=50e745e72a) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASRock        | Z87 Extreme11/ac            | [283593a105](https://linux-hardware.org/?probe=283593a105) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Acer          | Predator G3-605             | [8a1a55a1da](https://linux-hardware.org/?probe=8a1a55a1da) | Mar 29, 2023 |
| MSI           | X99A RAIDER                 | [761f7d71db](https://linux-hardware.org/?probe=761f7d71db) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [0730a39a3a](https://linux-hardware.org/?probe=0730a39a3a) | Mar 26, 2023 |
| MSI           | X99A RAIDER                 | [dd6b3f7e44](https://linux-hardware.org/?probe=dd6b3f7e44) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| MSI           | X99A RAIDER                 | [8892fdfdf9](https://linux-hardware.org/?probe=8892fdfdf9) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| MSI           | X99A RAIDER                 | [f842840cc9](https://linux-hardware.org/?probe=f842840cc9) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | X99A RAIDER                 | [c919e2da37](https://linux-hardware.org/?probe=c919e2da37) | Mar 12, 2023 |
| MSI           | X99A RAIDER                 | [089cafb799](https://linux-hardware.org/?probe=089cafb799) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| MSI           | P67A-C45                    | [52e013338c](https://linux-hardware.org/?probe=52e013338c) | Mar 07, 2023 |
| MSI           | X99A RAIDER                 | [2246ef48c8](https://linux-hardware.org/?probe=2246ef48c8) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| MSI           | X99A RAIDER                 | [46d39caf5c](https://linux-hardware.org/?probe=46d39caf5c) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | [b20cfbdfa1](https://linux-hardware.org/?probe=b20cfbdfa1) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| HP            | ProLiant ML110 Gen9         | [2ac4801793](https://linux-hardware.org/?probe=2ac4801793) | Mar 03, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| MSI           | X99A RAIDER                 | [989eed6d5f](https://linux-hardware.org/?probe=989eed6d5f) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | [ba4afa4d3b](https://linux-hardware.org/?probe=ba4afa4d3b) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| MSI           | X99A RAIDER                 | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| HP            | 3397                        | [a1840ee53d](https://linux-hardware.org/?probe=a1840ee53d) | Feb 26, 2023 |
| MSI           | B85M-E45                    | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [142a12ded0](https://linux-hardware.org/?probe=142a12ded0) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [06138e952c](https://linux-hardware.org/?probe=06138e952c) | Feb 22, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [31d92eed57](https://linux-hardware.org/?probe=31d92eed57) | Feb 21, 2023 |
| MSI           | Z77A-GD65                   | [b5aebe4c92](https://linux-hardware.org/?probe=b5aebe4c92) | Feb 21, 2023 |
| HP            | 0AECh D                     | [e844a614ec](https://linux-hardware.org/?probe=e844a614ec) | Feb 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| Acer          | Aspire XC-230               | [e01d812902](https://linux-hardware.org/?probe=e01d812902) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | [52b4d00a5a](https://linux-hardware.org/?probe=52b4d00a5a) | Feb 17, 2023 |
| MSI           | X99A RAIDER                 | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| MSI           | B450-A PRO                  | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| MSI           | X99A RAIDER                 | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| ASRock        | A300M-STX                   | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| HP            | 3397                        | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c91d5b265b](https://linux-hardware.org/?probe=c91d5b265b) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| Apple         | Mac-F221BEC8                | [d8de82d8c4](https://linux-hardware.org/?probe=d8de82d8c4) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| HP            | 8597                        | [8cc851783e](https://linux-hardware.org/?probe=8cc851783e) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Gigabyte      | B360HD3                     | [a9b7912b52](https://linux-hardware.org/?probe=a9b7912b52) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| HP            | 3397                        | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [cc16045ed3](https://linux-hardware.org/?probe=cc16045ed3) | Jan 16, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [79eb90321f](https://linux-hardware.org/?probe=79eb90321f) | Jan 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| MSI           | X99A RAIDER                 | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| MSI           | P67A-C45                    | [625a573f22](https://linux-hardware.org/?probe=625a573f22) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| HP            | 8299                        | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ec34483710](https://linux-hardware.org/?probe=ec34483710) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| MSI           | X99A RAIDER                 | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| HP            | 8643 SMVB                   | [5187413460](https://linux-hardware.org/?probe=5187413460) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| MSI           | X99A RAIDER                 | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| HP            | ProLiant ML110 Gen9         | [ea9aef1e8d](https://linux-hardware.org/?probe=ea9aef1e8d) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| HP            | ProLiant ML110 Gen9         | [728793a92a](https://linux-hardware.org/?probe=728793a92a) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | ProLiant ML110 Gen9         | [90bb379f4e](https://linux-hardware.org/?probe=90bb379f4e) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [23f2e15649](https://linux-hardware.org/?probe=23f2e15649) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [17630a4351](https://linux-hardware.org/?probe=17630a4351) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6a731c5c9b](https://linux-hardware.org/?probe=6a731c5c9b) | Dec 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [cc8dd14279](https://linux-hardware.org/?probe=cc8dd14279) | Dec 19, 2022 |
| MSI           | X99A RAIDER                 | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [226bab8281](https://linux-hardware.org/?probe=226bab8281) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| MSI           | X99A RAIDER                 | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| HP            | ProLiant ML110 Gen9         | [3326c90617](https://linux-hardware.org/?probe=3326c90617) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| HP            | ProLiant ML110 Gen9         | [7924d2f347](https://linux-hardware.org/?probe=7924d2f347) | Dec 12, 2022 |
| HP            | ProLiant ML110 Gen9         | [37b8d2824f](https://linux-hardware.org/?probe=37b8d2824f) | Dec 11, 2022 |
| Dell          | 0KG317                      | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| MSI           | P67A-C45                    | [44c8da681d](https://linux-hardware.org/?probe=44c8da681d) | Dec 07, 2022 |
| ASRock        | AB350M                      | [95a14fd558](https://linux-hardware.org/?probe=95a14fd558) | Dec 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| ASRock        | H77M-ITX                    | [b2b1b1649a](https://linux-hardware.org/?probe=b2b1b1649a) | Dec 03, 2022 |
| MSI           | X99A RAIDER                 | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| MSI           | X99A RAIDER                 | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [7917cbbd8c](https://linux-hardware.org/?probe=7917cbbd8c) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| MSI           | X99A RAIDER                 | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [653a03dee6](https://linux-hardware.org/?probe=653a03dee6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9bdccc90c4](https://linux-hardware.org/?probe=9bdccc90c4) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | [0036848bf2](https://linux-hardware.org/?probe=0036848bf2) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| Gigabyte      | X99-UD7 WIFI-CF             | [9c484b6d22](https://linux-hardware.org/?probe=9c484b6d22) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [80a70e8f6e](https://linux-hardware.org/?probe=80a70e8f6e) | Oct 03, 2022 |
| ASRock        | Z97 Pro4                    | [d0465080bf](https://linux-hardware.org/?probe=d0465080bf) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [fca2e4409a](https://linux-hardware.org/?probe=fca2e4409a) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [3553d42d14](https://linux-hardware.org/?probe=3553d42d14) | Sep 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| HP            | 8594                        | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| HP            | 805D                        | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| MSI           | Z97M-G43                    | [706804a4e2](https://linux-hardware.org/?probe=706804a4e2) | Sep 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| MSI           | P67A-C45                    | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| Dell          | 0NW6H5 A00                  | [d4de10030b](https://linux-hardware.org/?probe=d4de10030b) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eba231b7db](https://linux-hardware.org/?probe=eba231b7db) | Aug 30, 2022 |
| MSI           | P67A-C45                    | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff55a7dbf1](https://linux-hardware.org/?probe=ff55a7dbf1) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f80abd07f3](https://linux-hardware.org/?probe=f80abd07f3) | Aug 25, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3f83c9e402](https://linux-hardware.org/?probe=3f83c9e402) | Aug 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1298facab1](https://linux-hardware.org/?probe=1298facab1) | Aug 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [91a2943c51](https://linux-hardware.org/?probe=91a2943c51) | Aug 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [244025d59e](https://linux-hardware.org/?probe=244025d59e) | Aug 08, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9320816ca5](https://linux-hardware.org/?probe=9320816ca5) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | [48606f92a6](https://linux-hardware.org/?probe=48606f92a6) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | [c55f1b0a46](https://linux-hardware.org/?probe=c55f1b0a46) | Aug 05, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b224ef1b8d](https://linux-hardware.org/?probe=b224ef1b8d) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [015ec264f5](https://linux-hardware.org/?probe=015ec264f5) | Aug 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| ASUSTek       | VC65                        | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| ASRock        | H77M-ITX                    | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5a835b2aa6](https://linux-hardware.org/?probe=5a835b2aa6) | Jun 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [838e0b8e42](https://linux-hardware.org/?probe=838e0b8e42) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cb07ae6e24](https://linux-hardware.org/?probe=cb07ae6e24) | Jun 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| Unknown       | Unknown                     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| Unknown       | Unknown                     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| ASUSTek       | Z170-A                      | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [afac7f7fb3](https://linux-hardware.org/?probe=afac7f7fb3) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME X399-A                | [e595903b64](https://linux-hardware.org/?probe=e595903b64) | Apr 18, 2022 |
| ASUSTek       | PRIME X399-A                | [b2fe9a09fd](https://linux-hardware.org/?probe=b2fe9a09fd) | Apr 17, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| Dell          | 0MN1TX A02                  | [cf2e65caf4](https://linux-hardware.org/?probe=cf2e65caf4) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| Acer          | Aspire X3400                | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| ASUSTek       | M2R-FVM                     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | [76ec39764b](https://linux-hardware.org/?probe=76ec39764b) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| ASUSTek       | M2R-FVM                     | [eaaef17c19](https://linux-hardware.org/?probe=eaaef17c19) | Mar 25, 2022 |
| ASUSTek       | X99-A                       | [b071309501](https://linux-hardware.org/?probe=b071309501) | Mar 23, 2022 |
| ASUSTek       | M2R-FVM                     | [eb934cc46a](https://linux-hardware.org/?probe=eb934cc46a) | Mar 23, 2022 |
| Dell          | 0YNVJG A01                  | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| MSI           | Z170A PC MATE               | [56c1c58549](https://linux-hardware.org/?probe=56c1c58549) | Mar 15, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Gigabyte      | 970A-DS3P                   | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [54ae8c7668](https://linux-hardware.org/?probe=54ae8c7668) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | [ad43671e4c](https://linux-hardware.org/?probe=ad43671e4c) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [9670ab829e](https://linux-hardware.org/?probe=9670ab829e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [d61754bba9](https://linux-hardware.org/?probe=d61754bba9) | Feb 26, 2022 |
| MSI           | 990FXA-GD65                 | [290919912c](https://linux-hardware.org/?probe=290919912c) | Feb 26, 2022 |
| Lenovo        | 0B98401 PRO                 | [c332efa9f8](https://linux-hardware.org/?probe=c332efa9f8) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| ASUSTek       | SABERTOOTH P67              | [2ad209abc4](https://linux-hardware.org/?probe=2ad209abc4) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [ef92dfd4f1](https://linux-hardware.org/?probe=ef92dfd4f1) | Feb 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ccd7847b28](https://linux-hardware.org/?probe=ccd7847b28) | Jan 30, 2022 |
| ASRock        | ION3D-HT                    | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Intel         | D54250WYK H13922-303        | [8b6b3d70bf](https://linux-hardware.org/?probe=8b6b3d70bf) | Jan 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASRock        | Z87 Killer                  | [6931f1ca2f](https://linux-hardware.org/?probe=6931f1ca2f) | Jan 17, 2022 |
| MSI           | P67A-C45                    | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| ASUSTek       | P5L8L-SE                    | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [7921e32637](https://linux-hardware.org/?probe=7921e32637) | Jan 14, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [7b12fb3749](https://linux-hardware.org/?probe=7b12fb3749) | Jan 14, 2022 |
| Acer          | Aspire X3400                | [6833137bc8](https://linux-hardware.org/?probe=6833137bc8) | Jan 02, 2022 |
| MSI           | H110M PRO-VH                | [a32495b8e4](https://linux-hardware.org/?probe=a32495b8e4) | Jan 02, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| ASUSTek       | SABERTOOTH P67              | [af2732b8a5](https://linux-hardware.org/?probe=af2732b8a5) | Dec 15, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| ASRockRack    | ROMED8-2T                   | [87b9d0f1e5](https://linux-hardware.org/?probe=87b9d0f1e5) | Dec 04, 2021 |
| ASRockRack    | ROMED8-2T                   | [071e272398](https://linux-hardware.org/?probe=071e272398) | Dec 04, 2021 |
| ASRock        | B450M Steel Legend          | [5c0f6b8395](https://linux-hardware.org/?probe=5c0f6b8395) | Nov 28, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [fb92bb54af](https://linux-hardware.org/?probe=fb92bb54af) | Nov 28, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7c0e3a92a5](https://linux-hardware.org/?probe=7c0e3a92a5) | Nov 26, 2021 |
| ASUSTek       | ROG Maximus Z690 HERO       | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [846877b55f](https://linux-hardware.org/?probe=846877b55f) | Nov 25, 2021 |
| MSI           | H170 GAMING M3              | [e9a754ed5c](https://linux-hardware.org/?probe=e9a754ed5c) | Nov 24, 2021 |
| Gigabyte      | Z170-Gaming K3              | [496b525711](https://linux-hardware.org/?probe=496b525711) | Nov 24, 2021 |
| ASRock        | X99M Extreme4               | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [756684e469](https://linux-hardware.org/?probe=756684e469) | Nov 20, 2021 |
| Acer          | EG43M                       | [03dc3c8d61](https://linux-hardware.org/?probe=03dc3c8d61) | Nov 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| HP            | 8056                        | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| Gigabyte      | H87N-WIFI                   | [b19a68b774](https://linux-hardware.org/?probe=b19a68b774) | Nov 13, 2021 |
| MSI           | B75MA-P45                   | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [4615791bf1](https://linux-hardware.org/?probe=4615791bf1) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [0cc8ca1a78](https://linux-hardware.org/?probe=0cc8ca1a78) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [ccce1ad4e4](https://linux-hardware.org/?probe=ccce1ad4e4) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [a96916c86f](https://linux-hardware.org/?probe=a96916c86f) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| MSI           | Z77A-GD65                   | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [f4442e94e7](https://linux-hardware.org/?probe=f4442e94e7) | Oct 21, 2021 |
| HP            | 1998                        | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Pegatron      | 2AC3                        | [ae8b02d9cb](https://linux-hardware.org/?probe=ae8b02d9cb) | Oct 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| Packard Be... | IXTREME M5120               | [315bbefc53](https://linux-hardware.org/?probe=315bbefc53) | Oct 06, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c9022127a9](https://linux-hardware.org/?probe=c9022127a9) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [99b237ae08](https://linux-hardware.org/?probe=99b237ae08) | Oct 02, 2021 |
| HP            | 8056                        | [2199f7a715](https://linux-hardware.org/?probe=2199f7a715) | Sep 26, 2021 |
| ASUSTek       | PRIME B350M-A               | [3808823182](https://linux-hardware.org/?probe=3808823182) | Sep 23, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [f28906612f](https://linux-hardware.org/?probe=f28906612f) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [17ad477c6f](https://linux-hardware.org/?probe=17ad477c6f) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a122cb5006](https://linux-hardware.org/?probe=a122cb5006) | Sep 19, 2021 |
| Acer          | EG43M                       | [03cff58061](https://linux-hardware.org/?probe=03cff58061) | Sep 17, 2021 |
| HP            | 8056                        | [61c50556d0](https://linux-hardware.org/?probe=61c50556d0) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | [630fec5a83](https://linux-hardware.org/?probe=630fec5a83) | Sep 11, 2021 |
| Gigabyte      | J3455N-D3H                  | [24bc89b42a](https://linux-hardware.org/?probe=24bc89b42a) | Aug 31, 2021 |
| HP            | 0B40h                       | [da95bc989c](https://linux-hardware.org/?probe=da95bc989c) | Aug 30, 2021 |
| Supermicro    | X10DAI                      | [078ab4c114](https://linux-hardware.org/?probe=078ab4c114) | Aug 24, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | [5909ea8d8d](https://linux-hardware.org/?probe=5909ea8d8d) | Aug 20, 2021 |
| HP            | 802E                        | [35a2f000fd](https://linux-hardware.org/?probe=35a2f000fd) | Aug 19, 2021 |
| ASUSTek       | B150M-C                     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [eaac722778](https://linux-hardware.org/?probe=eaac722778) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [a24db8e84d](https://linux-hardware.org/?probe=a24db8e84d) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [51b28dbd02](https://linux-hardware.org/?probe=51b28dbd02) | Aug 16, 2021 |
| Acer          | Aspire X3400                | [0a158e8bce](https://linux-hardware.org/?probe=0a158e8bce) | Aug 13, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [034630b7f9](https://linux-hardware.org/?probe=034630b7f9) | Aug 11, 2021 |
| Acer          | Aspire X3400                | [6836f60d13](https://linux-hardware.org/?probe=6836f60d13) | Aug 11, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| HP            | 3397                        | [d5add95307](https://linux-hardware.org/?probe=d5add95307) | Aug 05, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Wibtek        | TH61G-S                     | [346ae2c85d](https://linux-hardware.org/?probe=346ae2c85d) | Jul 29, 2021 |
| HP            | 87D6 SMVB                   | [77f9eee003](https://linux-hardware.org/?probe=77f9eee003) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| ASRock        | B450 Gaming K4              | [563a58b492](https://linux-hardware.org/?probe=563a58b492) | Jul 24, 2021 |
| ASRock        | X570 Steel Legend           | [6f026a93d1](https://linux-hardware.org/?probe=6f026a93d1) | Jul 17, 2021 |
| ASRock        | X570 Steel Legend           | [af12b529b0](https://linux-hardware.org/?probe=af12b529b0) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS MASTER           | [35bf19b527](https://linux-hardware.org/?probe=35bf19b527) | Jul 13, 2021 |
| HP            | 872B                        | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [ef051fc485](https://linux-hardware.org/?probe=ef051fc485) | Jul 04, 2021 |
| HP            | 1998                        | [8f095c8449](https://linux-hardware.org/?probe=8f095c8449) | Jul 01, 2021 |
| ASUSTek       | P5G41T-M                    | [8553d8a919](https://linux-hardware.org/?probe=8553d8a919) | Jun 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | [04c4ddf9b0](https://linux-hardware.org/?probe=04c4ddf9b0) | Jun 29, 2021 |
| Acer          | EG43LMK                     | [5df39d6ba0](https://linux-hardware.org/?probe=5df39d6ba0) | Jun 26, 2021 |
| MSI           | B85M-E45                    | [5508d6a84e](https://linux-hardware.org/?probe=5508d6a84e) | Jun 23, 2021 |
| MSI           | B75MA-P45                   | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Dell          | 02YYK5 A01                  | [74a4b076a9](https://linux-hardware.org/?probe=74a4b076a9) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| ASUSTek       | X99-DELUXE                  | [382c24055c](https://linux-hardware.org/?probe=382c24055c) | Jun 09, 2021 |
| Lenovo        | SDK0E50510 WIN              | [9cfdd32388](https://linux-hardware.org/?probe=9cfdd32388) | Jun 04, 2021 |
| ASUSTek       | PRIME B460M-A               | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f0145b568f](https://linux-hardware.org/?probe=f0145b568f) | May 27, 2021 |
| ASUSTek       | Maximus VIII HERO           | [4550202db3](https://linux-hardware.org/?probe=4550202db3) | May 15, 2021 |
| Gigabyte      | GA-970A-UD3                 | [1cf830acd9](https://linux-hardware.org/?probe=1cf830acd9) | May 13, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [87d92ce1b4](https://linux-hardware.org/?probe=87d92ce1b4) | May 08, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [766557aeb8](https://linux-hardware.org/?probe=766557aeb8) | May 07, 2021 |
| Dell          | 0M9KCM A02                  | [c016fc8897](https://linux-hardware.org/?probe=c016fc8897) | May 03, 2021 |
| ASUSTek       | PRIME Z490-A                | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| Dell          | 02YYK5 A01                  | [bd1254fe8d](https://linux-hardware.org/?probe=bd1254fe8d) | Apr 28, 2021 |
| MSI           | Z97S SLI Krait Edition      | [afb9057dda](https://linux-hardware.org/?probe=afb9057dda) | Apr 16, 2021 |
| ASRock        | X470 Taichi Ultimate        | [7ab07ae1e9](https://linux-hardware.org/?probe=7ab07ae1e9) | Apr 11, 2021 |
| ASRock        | X470 Taichi Ultimate        | [174dc97643](https://linux-hardware.org/?probe=174dc97643) | Apr 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2116d4313c](https://linux-hardware.org/?probe=2116d4313c) | Apr 11, 2021 |
| Dell          | 0WMJ54 A01                  | [59c7b4d6ff](https://linux-hardware.org/?probe=59c7b4d6ff) | Apr 10, 2021 |
| ASUSTek       | F2A85-M                     | [9548d9f0c6](https://linux-hardware.org/?probe=9548d9f0c6) | Apr 06, 2021 |
| ASUSTek       | PRIME Z490-A                | [9db70676f4](https://linux-hardware.org/?probe=9db70676f4) | Apr 05, 2021 |
| HP            | 1790                        | [d03e7a12c6](https://linux-hardware.org/?probe=d03e7a12c6) | Apr 04, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [393b9a2647](https://linux-hardware.org/?probe=393b9a2647) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [6a1ee4ca94](https://linux-hardware.org/?probe=6a1ee4ca94) | Mar 31, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [394a2510d4](https://linux-hardware.org/?probe=394a2510d4) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| ASRock        | B450M Pro4-F                | [c7223020fe](https://linux-hardware.org/?probe=c7223020fe) | Mar 25, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASUSTek       | M4A79T Deluxe               | [2ccff038d2](https://linux-hardware.org/?probe=2ccff038d2) | Mar 16, 2021 |
| HP            | 802F                        | [9ea8632891](https://linux-hardware.org/?probe=9ea8632891) | Mar 14, 2021 |
| MSI           | X99A RAIDER                 | [6f27ffd7aa](https://linux-hardware.org/?probe=6f27ffd7aa) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [9625a9c184](https://linux-hardware.org/?probe=9625a9c184) | Feb 26, 2021 |
| Dell          | 0NK70N A03                  | [5354c0cb90](https://linux-hardware.org/?probe=5354c0cb90) | Feb 22, 2021 |
| HP            | 2B35                        | [ab5c723699](https://linux-hardware.org/?probe=ab5c723699) | Feb 20, 2021 |
| MSI           | MEG X570 UNIFY              | [455cf08e86](https://linux-hardware.org/?probe=455cf08e86) | Feb 20, 2021 |
| Dell          | 0MN1TX A01                  | [ebc826cccc](https://linux-hardware.org/?probe=ebc826cccc) | Feb 18, 2021 |
| Acer          | Predator G3-605             | [f1a8ae2c26](https://linux-hardware.org/?probe=f1a8ae2c26) | Feb 17, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [c445cf637b](https://linux-hardware.org/?probe=c445cf637b) | Feb 15, 2021 |
| MSI           | X299 SLI PLUS               | [1499657b8c](https://linux-hardware.org/?probe=1499657b8c) | Feb 13, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [743d5820cc](https://linux-hardware.org/?probe=743d5820cc) | Feb 13, 2021 |
| ASRock        | X570 Taichi                 | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| ASUSTek       | P8Z77-M                     | [d60b967710](https://linux-hardware.org/?probe=d60b967710) | Jan 22, 2021 |
| Dell          | 00V62H A00                  | [3d8b11fbf3](https://linux-hardware.org/?probe=3d8b11fbf3) | Jan 20, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [7a840d41b2](https://linux-hardware.org/?probe=7a840d41b2) | Jan 19, 2021 |
| MSI           | MAG B550M MORTAR            | [0900f71645](https://linux-hardware.org/?probe=0900f71645) | Jan 17, 2021 |
| ASUSTek       | PRIME Z270-P                | [d3150c1175](https://linux-hardware.org/?probe=d3150c1175) | Jan 14, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [0d39b0f1de](https://linux-hardware.org/?probe=0d39b0f1de) | Jan 10, 2021 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | [656256db83](https://linux-hardware.org/?probe=656256db83) | Dec 22, 2020 |
| Gigabyte      | B550 AORUS PRO              | [1520dcde71](https://linux-hardware.org/?probe=1520dcde71) | Dec 20, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03fbf815fb](https://linux-hardware.org/?probe=03fbf815fb) | Dec 19, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [6cff41d0d5](https://linux-hardware.org/?probe=6cff41d0d5) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [3673aeec97](https://linux-hardware.org/?probe=3673aeec97) | Dec 07, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e9fb942639](https://linux-hardware.org/?probe=e9fb942639) | Dec 04, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [38c026cbb9](https://linux-hardware.org/?probe=38c026cbb9) | Nov 28, 2020 |
| Lenovo        | 0800-E3G                    | [82f0cc6d73](https://linux-hardware.org/?probe=82f0cc6d73) | Nov 24, 2020 |
| Lenovo        | 0800-E3G                    | [f7a3cae158](https://linux-hardware.org/?probe=f7a3cae158) | Nov 24, 2020 |
| HP            | 0AA8h                       | [5b9abc7e6e](https://linux-hardware.org/?probe=5b9abc7e6e) | Nov 21, 2020 |
| ASUSTek       | SABERTOOTH Z77              | [4497d1907e](https://linux-hardware.org/?probe=4497d1907e) | Nov 21, 2020 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [1945ae5a25](https://linux-hardware.org/?probe=1945ae5a25) | Nov 16, 2020 |
| ASUSTek       | P9X79 LE                    | [535bb960c8](https://linux-hardware.org/?probe=535bb960c8) | Nov 09, 2020 |
| ASUSTek       | PRIME X370-PRO              | [8cc1c3b402](https://linux-hardware.org/?probe=8cc1c3b402) | Nov 05, 2020 |
| ASUSTek       | PRIME X570-P                | [7cc067fb03](https://linux-hardware.org/?probe=7cc067fb03) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [2a45f74eda](https://linux-hardware.org/?probe=2a45f74eda) | Nov 02, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [d44d323649](https://linux-hardware.org/?probe=d44d323649) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [1e3afeadf1](https://linux-hardware.org/?probe=1e3afeadf1) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [c36062c763](https://linux-hardware.org/?probe=c36062c763) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [509ec4584c](https://linux-hardware.org/?probe=509ec4584c) | Oct 31, 2020 |
| ASUSTek       | P8Z77-M                     | [ca7e76d821](https://linux-hardware.org/?probe=ca7e76d821) | Oct 30, 2020 |
| ASUSTek       | PRIME X370-PRO              | [01bfabd117](https://linux-hardware.org/?probe=01bfabd117) | Oct 29, 2020 |
| Gigabyte      | 970A-DS3P                   | [4c38164a20](https://linux-hardware.org/?probe=4c38164a20) | Oct 21, 2020 |
| ASRock        | X570 Extreme4               | [40e091c5f4](https://linux-hardware.org/?probe=40e091c5f4) | Oct 16, 2020 |
| Dell          | 00V62H A01                  | [d246c4d7c9](https://linux-hardware.org/?probe=d246c4d7c9) | Oct 15, 2020 |
| ASRock        | FM2A75M-HD+                 | [eb66178779](https://linux-hardware.org/?probe=eb66178779) | Oct 13, 2020 |
| ASRock        | X570 Extreme4               | [cad3c5d0ba](https://linux-hardware.org/?probe=cad3c5d0ba) | Oct 13, 2020 |
| Gigabyte      | MQLP5AP-00                  | [bec4249ac9](https://linux-hardware.org/?probe=bec4249ac9) | Oct 12, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [80b8079281](https://linux-hardware.org/?probe=80b8079281) | Oct 02, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fa10cd09d](https://linux-hardware.org/?probe=4fa10cd09d) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [07fab4cd26](https://linux-hardware.org/?probe=07fab4cd26) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [7e8f9659ac](https://linux-hardware.org/?probe=7e8f9659ac) | Sep 28, 2020 |
| Gigabyte      | H310N                       | [af0cc1312f](https://linux-hardware.org/?probe=af0cc1312f) | Sep 28, 2020 |
| MSI           | X99A RAIDER                 | [dad099d968](https://linux-hardware.org/?probe=dad099d968) | Sep 28, 2020 |
| ASRock        | X570 Taichi                 | [60d17efc7c](https://linux-hardware.org/?probe=60d17efc7c) | Sep 25, 2020 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [a7176bb601](https://linux-hardware.org/?probe=a7176bb601) | Sep 15, 2020 |
| ASUSTek       | P9X79 LE                    | [6cb5707322](https://linux-hardware.org/?probe=6cb5707322) | Sep 15, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [576daf4d41](https://linux-hardware.org/?probe=576daf4d41) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [726f3b1370](https://linux-hardware.org/?probe=726f3b1370) | Sep 14, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [d6885cac52](https://linux-hardware.org/?probe=d6885cac52) | Sep 14, 2020 |
| ASUSTek       | NARRA2                      | [54160f4cb5](https://linux-hardware.org/?probe=54160f4cb5) | Sep 10, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [f604a231fa](https://linux-hardware.org/?probe=f604a231fa) | Sep 10, 2020 |
| ASUSTek       | PRIME X570-P                | [08210e360a](https://linux-hardware.org/?probe=08210e360a) | Sep 10, 2020 |
| ASUSTek       | X99-E WS                    | [e37af5c1c2](https://linux-hardware.org/?probe=e37af5c1c2) | Sep 05, 2020 |
| Gigabyte      | 970A-DS3P                   | [b1248e2b3b](https://linux-hardware.org/?probe=b1248e2b3b) | Sep 05, 2020 |
| MSI           | B350 TOMAHAWK               | [cf16a05fb6](https://linux-hardware.org/?probe=cf16a05fb6) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f3f962b06](https://linux-hardware.org/?probe=8f3f962b06) | Sep 03, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [b3bb6fe3dc](https://linux-hardware.org/?probe=b3bb6fe3dc) | Aug 27, 2020 |
| MSI           | Z97S SLI Krait Edition      | [c4b10f778e](https://linux-hardware.org/?probe=c4b10f778e) | Aug 25, 2020 |
| ASUSTek       | X99-E WS                    | [ed9d8c885d](https://linux-hardware.org/?probe=ed9d8c885d) | Aug 25, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [a59b0acdfe](https://linux-hardware.org/?probe=a59b0acdfe) | Aug 24, 2020 |
| ASUSTek       | PRIME Z270-P                | [904934805a](https://linux-hardware.org/?probe=904934805a) | Aug 19, 2020 |
| ASUSTek       | Z170-P                      | [b15339e143](https://linux-hardware.org/?probe=b15339e143) | Aug 17, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [c6d5a14495](https://linux-hardware.org/?probe=c6d5a14495) | Aug 12, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [143846fb82](https://linux-hardware.org/?probe=143846fb82) | Aug 12, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [e0855b4bf3](https://linux-hardware.org/?probe=e0855b4bf3) | Aug 09, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9b4f4dc28b](https://linux-hardware.org/?probe=9b4f4dc28b) | Aug 07, 2020 |
| MSI           | Z87-G45 GAMING              | [edfa113106](https://linux-hardware.org/?probe=edfa113106) | Aug 03, 2020 |
| ASUSTek       | B85M-G                      | [917bed383b](https://linux-hardware.org/?probe=917bed383b) | Jul 26, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [552295571e](https://linux-hardware.org/?probe=552295571e) | Jul 26, 2020 |
| MSI           | Z87-G45 GAMING              | [c91081e069](https://linux-hardware.org/?probe=c91081e069) | Jul 26, 2020 |
| ASUSTek       | B85M-G                      | [475dbf0ad7](https://linux-hardware.org/?probe=475dbf0ad7) | Jul 25, 2020 |
| MSI           | Z87-G45 GAMING              | [cd32144f93](https://linux-hardware.org/?probe=cd32144f93) | Jul 25, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [c6f296962b](https://linux-hardware.org/?probe=c6f296962b) | Jul 23, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [76fb21829c](https://linux-hardware.org/?probe=76fb21829c) | Jul 07, 2020 |
| ASRock        | KBL-NUC                     | [0fb87b772d](https://linux-hardware.org/?probe=0fb87b772d) | Jul 05, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [e6aca4abae](https://linux-hardware.org/?probe=e6aca4abae) | Jul 01, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [3662f6e30e](https://linux-hardware.org/?probe=3662f6e30e) | Jul 01, 2020 |
| ASUSTek       | PRIME X570-P                | [d7dfd2a0d2](https://linux-hardware.org/?probe=d7dfd2a0d2) | Jun 30, 2020 |
| ASUSTek       | X99-E WS                    | [b1bdbcd5d8](https://linux-hardware.org/?probe=b1bdbcd5d8) | Jun 24, 2020 |
| Dell          | 02K9CR A01                  | [823eca4894](https://linux-hardware.org/?probe=823eca4894) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASUSTek       | PRIME X570-P                | [392a2f214f](https://linux-hardware.org/?probe=392a2f214f) | Jun 20, 2020 |
| ASUSTek       | Z170-P                      | [7bbf45616d](https://linux-hardware.org/?probe=7bbf45616d) | Jun 11, 2020 |
| ASUSTek       | SABERTOOTH X58              | [b96a58003f](https://linux-hardware.org/?probe=b96a58003f) | Jun 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | [f83c6bc99a](https://linux-hardware.org/?probe=f83c6bc99a) | May 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | [4479197ed4](https://linux-hardware.org/?probe=4479197ed4) | May 23, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [0580ffcbce](https://linux-hardware.org/?probe=0580ffcbce) | May 18, 2020 |
| ASUSTek       | SABERTOOTH X58              | [0ac27b4c34](https://linux-hardware.org/?probe=0ac27b4c34) | May 18, 2020 |
| ASUSTek       | SABERTOOTH X58              | [bc5ccb2621](https://linux-hardware.org/?probe=bc5ccb2621) | May 18, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [386740675c](https://linux-hardware.org/?probe=386740675c) | May 13, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [98d3987a61](https://linux-hardware.org/?probe=98d3987a61) | May 06, 2020 |
| ASUSTek       | H81I-PLUS                   | [33d922e46d](https://linux-hardware.org/?probe=33d922e46d) | May 05, 2020 |
| ASUSTek       | P8H77-I                     | [cd6981fca0](https://linux-hardware.org/?probe=cd6981fca0) | Apr 28, 2020 |
| ASUSTek       | P8H77-I                     | [9fdad4ca4b](https://linux-hardware.org/?probe=9fdad4ca4b) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5cae2ee3d0](https://linux-hardware.org/?probe=5cae2ee3d0) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a5bf0d9b6b](https://linux-hardware.org/?probe=a5bf0d9b6b) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4e2748672a](https://linux-hardware.org/?probe=4e2748672a) | Apr 28, 2020 |
| HP            | 3397                        | [e6727c485f](https://linux-hardware.org/?probe=e6727c485f) | Apr 27, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [6a5b331028](https://linux-hardware.org/?probe=6a5b331028) | Apr 11, 2020 |
| ASRock        | X99M Extreme4               | [45030fab5d](https://linux-hardware.org/?probe=45030fab5d) | Apr 11, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [a71754c00c](https://linux-hardware.org/?probe=a71754c00c) | Apr 07, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [2557527190](https://linux-hardware.org/?probe=2557527190) | Apr 06, 2020 |
| ASUSTek       | X99-E WS                    | [cab8397e58](https://linux-hardware.org/?probe=cab8397e58) | Apr 05, 2020 |
| HP            | 0A68h                       | [21961765f3](https://linux-hardware.org/?probe=21961765f3) | Apr 04, 2020 |
| ASUSTek       | X99-E WS                    | [535aa9a5c6](https://linux-hardware.org/?probe=535aa9a5c6) | Apr 01, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [83594d554f](https://linux-hardware.org/?probe=83594d554f) | Mar 26, 2020 |
| HP            | 0A68h                       | [e48c1d8956](https://linux-hardware.org/?probe=e48c1d8956) | Mar 21, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [a5c1f26d9c](https://linux-hardware.org/?probe=a5c1f26d9c) | Mar 21, 2020 |
| MSI           | B450M BAZOOKA               | [a97b201643](https://linux-hardware.org/?probe=a97b201643) | Mar 19, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [731ed47f34](https://linux-hardware.org/?probe=731ed47f34) | Mar 17, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [b5a0ec3283](https://linux-hardware.org/?probe=b5a0ec3283) | Mar 16, 2020 |
| Gigabyte      | B450 AORUS M                | [3c6e4bca36](https://linux-hardware.org/?probe=3c6e4bca36) | Mar 13, 2020 |
| Shuttle       | FS35V4                      | [c52e6f6535](https://linux-hardware.org/?probe=c52e6f6535) | Mar 02, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [5d7f28b50a](https://linux-hardware.org/?probe=5d7f28b50a) | Feb 29, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [c89b46d092](https://linux-hardware.org/?probe=c89b46d092) | Feb 25, 2020 |
| Shuttle       | FS35V4                      | [86b9422986](https://linux-hardware.org/?probe=86b9422986) | Feb 23, 2020 |
| Pegatron      | 2AB5                        | [8cd66072e1](https://linux-hardware.org/?probe=8cd66072e1) | Feb 21, 2020 |
| Gigabyte      | Z270N-WIFI-CF               | [765c227e7c](https://linux-hardware.org/?probe=765c227e7c) | Feb 21, 2020 |
| ASRock        | H81M-ITX/WiFi               | [4b746c7d20](https://linux-hardware.org/?probe=4b746c7d20) | Feb 19, 2020 |
| Gigabyte      | GA-970A-UD3                 | [9d30831796](https://linux-hardware.org/?probe=9d30831796) | Feb 17, 2020 |
| Gigabyte      | GA-970A-UD3                 | [3d45ca6f5b](https://linux-hardware.org/?probe=3d45ca6f5b) | Feb 17, 2020 |
| Dell          | 0DF42J A00                  | [315459c675](https://linux-hardware.org/?probe=315459c675) | Feb 16, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [0be68258a3](https://linux-hardware.org/?probe=0be68258a3) | Feb 11, 2020 |
| Acer          | FRS690L                     | [da0aa833d2](https://linux-hardware.org/?probe=da0aa833d2) | Feb 07, 2020 |
| Acer          | FRS690L                     | [d2f7944838](https://linux-hardware.org/?probe=d2f7944838) | Feb 07, 2020 |
| Acer          | FRS690L                     | [52e677d939](https://linux-hardware.org/?probe=52e677d939) | Feb 07, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [174e1402cf](https://linux-hardware.org/?probe=174e1402cf) | Feb 03, 2020 |
| Dell          | 0MN1TX A02                  | [5c482e9676](https://linux-hardware.org/?probe=5c482e9676) | Jan 18, 2020 |
| Dell          | 0MN1TX A02                  | [5f652869cd](https://linux-hardware.org/?probe=5f652869cd) | Jan 18, 2020 |
| ASRock        | H81M-ITX/WiFi               | [b4fc494391](https://linux-hardware.org/?probe=b4fc494391) | Dec 30, 2019 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6df8cd9ddd](https://linux-hardware.org/?probe=6df8cd9ddd) | Dec 20, 2019 |
| ASUSTek       | P7P55D                      | [a630b7494e](https://linux-hardware.org/?probe=a630b7494e) | Dec 07, 2019 |
| ASUSTek       | Z170-A                      | [23b0f48535](https://linux-hardware.org/?probe=23b0f48535) | Nov 24, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2581a2d661](https://linux-hardware.org/?probe=2581a2d661) | Nov 16, 2019 |
| Dell          | 06X1TJ A01                  | [9da4eeda28](https://linux-hardware.org/?probe=9da4eeda28) | Nov 05, 2019 |
| ASUSTek       | P9D WS                      | [549ecf66d0](https://linux-hardware.org/?probe=549ecf66d0) | Oct 23, 2019 |
| HP            | 2AE2                        | [ac16964bc3](https://linux-hardware.org/?probe=ac16964bc3) | Oct 15, 2019 |
| HP            | 2AE2                        | [ea13e02e53](https://linux-hardware.org/?probe=ea13e02e53) | Oct 01, 2019 |
| ASUSTek       | A8NE-FM                     | [741f8cff05](https://linux-hardware.org/?probe=741f8cff05) | Sep 29, 2019 |
| ASUSTek       | H87I-PLUS                   | [b74b1c5ad4](https://linux-hardware.org/?probe=b74b1c5ad4) | Sep 05, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [7c2f30c389](https://linux-hardware.org/?probe=7c2f30c389) | Aug 25, 2019 |
| MSI           | 2AE0                        | [e8c2927bde](https://linux-hardware.org/?probe=e8c2927bde) | Aug 03, 2019 |
| MSI           | B450-A PRO                  | [b1e465082e](https://linux-hardware.org/?probe=b1e465082e) | Aug 02, 2019 |
| MSI           | B450-A PRO                  | [a1382a1557](https://linux-hardware.org/?probe=a1382a1557) | Jul 30, 2019 |
| ASRock        | Z390 Taichi Ultimate        | [62a28aa523](https://linux-hardware.org/?probe=62a28aa523) | Jul 30, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [cdc565d73d](https://linux-hardware.org/?probe=cdc565d73d) | Jul 23, 2019 |
| MSI           | Z97-G43 GAMING              | [5c83686f9c](https://linux-hardware.org/?probe=5c83686f9c) | Jul 14, 2019 |
| MSI           | H87I                        | [b0be456a64](https://linux-hardware.org/?probe=b0be456a64) | Jul 10, 2019 |
| ASUSTek       | B85M-G                      | [08d84a1ff9](https://linux-hardware.org/?probe=08d84a1ff9) | Jul 09, 2019 |
| HP            | 2AE2                        | [7827916e15](https://linux-hardware.org/?probe=7827916e15) | Jul 01, 2019 |
| HP            | 2AE2                        | [b999d6bd6d](https://linux-hardware.org/?probe=b999d6bd6d) | Jun 17, 2019 |
| ASUSTek       | SABERTOOTH P67              | [0eef21306d](https://linux-hardware.org/?probe=0eef21306d) | Jun 17, 2019 |
| Dell          | 06X1TJ A01                  | [9a78ee6839](https://linux-hardware.org/?probe=9a78ee6839) | May 28, 2019 |
| MSI           | X299 SLI PLUS               | [692c95368a](https://linux-hardware.org/?probe=692c95368a) | May 06, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [fc59e7df18](https://linux-hardware.org/?probe=fc59e7df18) | May 04, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [106016dd36](https://linux-hardware.org/?probe=106016dd36) | Apr 28, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [2786657449](https://linux-hardware.org/?probe=2786657449) | Apr 12, 2019 |
| Intel         | DG45FC AAE27730-308         | [459dc2d57f](https://linux-hardware.org/?probe=459dc2d57f) | Apr 08, 2019 |
| Gigabyte      | Z97MX-Gaming 5              | [d94ade2c40](https://linux-hardware.org/?probe=d94ade2c40) | Mar 27, 2019 |
| Dell          | 0K240Y A01                  | [4683a284a4](https://linux-hardware.org/?probe=4683a284a4) | Mar 26, 2019 |
| MSI           | 2AE0                        | [5585935586](https://linux-hardware.org/?probe=5585935586) | Mar 25, 2019 |
| Dell          | 0HN7XN A01                  | [0b8a535d2a](https://linux-hardware.org/?probe=0b8a535d2a) | Mar 16, 2019 |
| ASUSTek       | SABERTOOTH P67              | [eaa09576b4](https://linux-hardware.org/?probe=eaa09576b4) | Mar 12, 2019 |
| Pegatron      | 2A72h                       | [aa54b4c1d3](https://linux-hardware.org/?probe=aa54b4c1d3) | Mar 07, 2019 |
| MSI           | Z68A-GD65                   | [883872e8b0](https://linux-hardware.org/?probe=883872e8b0) | Feb 18, 2019 |
| ASUSTek       | B85M-G                      | [b45f44a0f7](https://linux-hardware.org/?probe=b45f44a0f7) | Jan 23, 2019 |
| Lenovo        | 36EF SDK0J40700 WIN 3258... | [b077a03fb3](https://linux-hardware.org/?probe=b077a03fb3) | Jan 07, 2019 |
| HP            | 0B54h D                     | [1456dd6d91](https://linux-hardware.org/?probe=1456dd6d91) | Jan 06, 2019 |
| Dell          | 0RW203                      | [7773935ee9](https://linux-hardware.org/?probe=7773935ee9) | Dec 23, 2018 |
| Dell          | 0RW203                      | [bb86cab506](https://linux-hardware.org/?probe=bb86cab506) | Dec 23, 2018 |
| ASUSTek       | SABERTOOTH Z77              | [41b6e4c6b2](https://linux-hardware.org/?probe=41b6e4c6b2) | Dec 06, 2018 |
| ASUSTek       | EB1501P                     | [4a6eb1071a](https://linux-hardware.org/?probe=4a6eb1071a) | Oct 21, 2018 |
| Gigabyte      | F2A75M-D3H                  | [41a0eb1b0d](https://linux-hardware.org/?probe=41a0eb1b0d) | Oct 06, 2018 |
| ASUSTek       | AM1I-A                      | [e6a8378a5b](https://linux-hardware.org/?probe=e6a8378a5b) | Jun 15, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Norway/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 40       | 10.28%  |
| Ubuntu 18.04                 | 22       | 5.66%   |
| Debian 11                    | 15       | 3.86%   |
| Ubuntu 22.04                 | 14       | 3.6%    |
| Pop!_OS 22.04                | 14       | 3.6%    |
| Arch Rolling                 | 14       | 3.6%    |
| Zorin 16                     | 11       | 2.83%   |
| ArcoLinux Rolling            | 10       | 2.57%   |
| Ubuntu 18.10                 | 8        | 2.06%   |
| OpenMandriva 4.3             | 8        | 2.06%   |
| OpenMandriva 4.2             | 8        | 2.06%   |
| Arch                         | 8        | 2.06%   |
| Ubuntu 19.10                 | 7        | 1.8%    |
| Fedora 36                    | 7        | 1.8%    |
| Fedora 35                    | 7        | 1.8%    |
| Pop!_OS 21.04                | 6        | 1.54%   |
| Manjaro                      | 6        | 1.54%   |
| Fedora 32                    | 6        | 1.54%   |
| Ubuntu 20.10                 | 5        | 1.29%   |
| Pop!_OS 20.04                | 5        | 1.29%   |
| Linux Mint 21.1              | 5        | 1.29%   |
| Fedora 38                    | 5        | 1.29%   |
| Fedora 37                    | 5        | 1.29%   |
| Zorin 15                     | 4        | 1.03%   |
| Ubuntu 21.10                 | 4        | 1.03%   |
| Ubuntu 19.04                 | 4        | 1.03%   |
| Pop!_OS 21.10                | 4        | 1.03%   |
| Pop!_OS 20.10                | 4        | 1.03%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.03%   |
| OpenMandriva 23.03           | 4        | 1.03%   |
| OpenMandriva 23.01           | 4        | 1.03%   |
| Linux Mint 20.2              | 4        | 1.03%   |
| Linux Mint 20.1              | 4        | 1.03%   |
| KDE neon 20.04               | 4        | 1.03%   |
| Fedora 34                    | 4        | 1.03%   |
| Fedora 33                    | 4        | 1.03%   |
| Debian 10                    | 4        | 1.03%   |
| Ubuntu 21.04                 | 3        | 0.77%   |
| OpenMandriva 4.50            | 3        | 0.77%   |
| Manjaro 20.1                 | 3        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 105      | 28.61%  |
| Fedora        | 33       | 8.99%   |
| Pop!_OS       | 29       | 7.9%    |
| OpenMandriva  | 27       | 7.36%   |
| Linux Mint    | 24       | 6.54%   |
| Debian        | 23       | 6.27%   |
| Arch          | 22       | 5.99%   |
| Manjaro       | 19       | 5.18%   |
| Zorin         | 15       | 4.09%   |
| ArcoLinux     | 10       | 2.72%   |
| openSUSE      | 7        | 1.91%   |
| KDE neon      | 7        | 1.91%   |
| Xubuntu       | 6        | 1.63%   |
| Kubuntu       | 6        | 1.63%   |
| Gentoo        | 5        | 1.36%   |
| Clear Linux   | 4        | 1.09%   |
| ROSA          | 3        | 0.82%   |
| Garuda Linux  | 3        | 0.82%   |
| Ubuntu Budgie | 2        | 0.54%   |
| EndeavourOS   | 2        | 0.54%   |
| Elementary    | 2        | 0.54%   |
| CentOS        | 2        | 0.54%   |
| Alpine        | 2        | 0.54%   |
| Ubuntu Studio | 1        | 0.27%   |
| Ubuntu MATE   | 1        | 0.27%   |
| Solus         | 1        | 0.27%   |
| Rocky Linux   | 1        | 0.27%   |
| Nobara        | 1        | 0.27%   |
| LMDE          | 1        | 0.27%   |
| Kali          | 1        | 0.27%   |
| Feren OS      | 1        | 0.27%   |
| ChimeraOS     | 1        | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 8        | 1.82%   |
| 5.10.14-desktop-1omv4002 | 8        | 1.82%   |
| 4.18.0-16-generic        | 6        | 1.36%   |
| 5.11.0-38-generic        | 5        | 1.14%   |
| 6.2.6-desktop-1omv2390   | 4        | 0.91%   |
| 6.1.1-desktop-1omv2290   | 4        | 0.91%   |
| 5.4.0-47-generic         | 4        | 0.91%   |
| 5.4.0-42-generic         | 4        | 0.91%   |
| 5.19.0-76051900-generic  | 4        | 0.91%   |
| 5.15.0-56-generic        | 4        | 0.91%   |
| 5.15.0-41-generic        | 4        | 0.91%   |
| 6.0.12-76060006-generic  | 3        | 0.68%   |
| 5.8.0-7630-generic       | 3        | 0.68%   |
| 5.4.0-74-generic         | 3        | 0.68%   |
| 5.4.0-51-generic         | 3        | 0.68%   |
| 5.4.0-29-generic         | 3        | 0.68%   |
| 5.3.0-28-generic         | 3        | 0.68%   |
| 5.3.0-18-generic         | 3        | 0.68%   |
| 5.15.7-arch1-1           | 3        | 0.68%   |
| 5.15.0-58-generic        | 3        | 0.68%   |
| 5.13.0-40-generic        | 3        | 0.68%   |
| 5.13.0-21-generic        | 3        | 0.68%   |
| 5.11.0-7620-generic      | 3        | 0.68%   |
| 5.11.0-27-generic        | 3        | 0.68%   |
| 5.0.0-20-generic         | 3        | 0.68%   |
| 6.3.9-arch1-1            | 2        | 0.45%   |
| 6.2.9-1-pve              | 2        | 0.45%   |
| 6.2.8-1-default          | 2        | 0.45%   |
| 6.1.11-76060111-generic  | 2        | 0.45%   |
| 5.9.16-1-MANJARO         | 2        | 0.45%   |
| 5.8.0-48-generic         | 2        | 0.45%   |
| 5.8.0-43-generic         | 2        | 0.45%   |
| 5.8.0-26-generic         | 2        | 0.45%   |
| 5.7.9-arch1-1            | 2        | 0.45%   |
| 5.5.5-200.fc31.x86_64    | 2        | 0.45%   |
| 5.4.0-91-generic         | 2        | 0.45%   |
| 5.4.0-89-generic         | 2        | 0.45%   |
| 5.4.0-80-generic         | 2        | 0.45%   |
| 5.4.0-77-generic         | 2        | 0.45%   |
| 5.4.0-7642-generic       | 2        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 50       | 12.05%  |
| 5.15.0  | 26       | 6.27%   |
| 5.11.0  | 20       | 4.82%   |
| 5.3.0   | 16       | 3.86%   |
| 4.18.0  | 16       | 3.86%   |
| 5.8.0   | 15       | 3.61%   |
| 5.13.0  | 15       | 3.61%   |
| 5.19.0  | 12       | 2.89%   |
| 5.10.0  | 12       | 2.89%   |
| 4.15.0  | 11       | 2.65%   |
| 5.0.0   | 9        | 2.17%   |
| 5.16.7  | 8        | 1.93%   |
| 5.10.14 | 8        | 1.93%   |
| 6.2.6   | 6        | 1.45%   |
| 5.16.0  | 5        | 1.2%    |
| 4.19.0  | 5        | 1.2%    |
| 6.1.1   | 4        | 0.96%   |
| 6.1.11  | 3        | 0.72%   |
| 6.0.12  | 3        | 0.72%   |
| 5.9.16  | 3        | 0.72%   |
| 5.17.5  | 3        | 0.72%   |
| 5.15.7  | 3        | 0.72%   |
| 5.15.4  | 3        | 0.72%   |
| 5.14.10 | 3        | 0.72%   |
| 6.3.9   | 2        | 0.48%   |
| 6.3.4   | 2        | 0.48%   |
| 6.3.1   | 2        | 0.48%   |
| 6.2.9   | 2        | 0.48%   |
| 6.2.8   | 2        | 0.48%   |
| 6.2.10  | 2        | 0.48%   |
| 6.2.0   | 2        | 0.48%   |
| 6.1.9   | 2        | 0.48%   |
| 6.1.0   | 2        | 0.48%   |
| 6.0.10  | 2        | 0.48%   |
| 6.0.0   | 2        | 0.48%   |
| 5.9.11  | 2        | 0.48%   |
| 5.8.6   | 2        | 0.48%   |
| 5.8.12  | 2        | 0.48%   |
| 5.7.9   | 2        | 0.48%   |
| 5.7.17  | 2        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 13.41%  |
| 5.15    | 46       | 11.22%  |
| 5.8     | 24       | 5.85%   |
| 5.11    | 23       | 5.61%   |
| 5.10    | 23       | 5.61%   |
| 5.13    | 22       | 5.37%   |
| 5.19    | 21       | 5.12%   |
| 5.16    | 19       | 4.63%   |
| 6.2     | 17       | 4.15%   |
| 5.3     | 17       | 4.15%   |
| 6.1     | 16       | 3.9%    |
| 4.18    | 16       | 3.9%    |
| 6.0     | 12       | 2.93%   |
| 5.17    | 11       | 2.68%   |
| 4.15    | 11       | 2.68%   |
| 5.0     | 10       | 2.44%   |
| 5.9     | 9        | 2.2%    |
| 5.7     | 8        | 1.95%   |
| 6.3     | 7        | 1.71%   |
| 5.14    | 7        | 1.71%   |
| 5.5     | 6        | 1.46%   |
| 5.18    | 6        | 1.46%   |
| 5.12    | 6        | 1.46%   |
| 4.19    | 5        | 1.22%   |
| 5.6     | 4        | 0.98%   |
| 6.4     | 3        | 0.73%   |
| 4.9     | 1        | 0.24%   |
| 4.4     | 1        | 0.24%   |
| 4.12    | 1        | 0.24%   |
| 4.10    | 1        | 0.24%   |
| 4.1     | 1        | 0.24%   |
| 3.10    | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 353      | 99.44%  |
| i686   | 2        | 0.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 160      | 43.36%  |
| KDE5            | 68       | 18.43%  |
| Unknown         | 59       | 15.99%  |
| XFCE            | 25       | 6.78%   |
| X-Cinnamon      | 15       | 4.07%   |
| KDE             | 11       | 2.98%   |
| i3              | 7        | 1.9%    |
| MATE            | 5        | 1.36%   |
| Budgie          | 4        | 1.08%   |
| Cinnamon        | 3        | 0.81%   |
| Pantheon        | 2        | 0.54%   |
| LXDE            | 2        | 0.54%   |
| dwm             | 2        | 0.54%   |
| qtile           | 1        | 0.27%   |
| LeftWM          | 1        | 0.27%   |
| KDE4            | 1        | 0.27%   |
| i3-with-shmlog  | 1        | 0.27%   |
| Hyprland        | 1        | 0.27%   |
| GNOME Flashback | 1        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 275      | 74.32%  |
| Wayland | 51       | 13.78%  |
| Tty     | 22       | 5.95%   |
| Unknown | 22       | 5.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 200      | 53.91%  |
| SDDM    | 58       | 15.63%  |
| GDM     | 41       | 11.05%  |
| GDM3    | 32       | 8.63%   |
| LightDM | 29       | 7.82%   |
| TDM     | 8        | 2.16%   |
| XDM     | 1        | 0.27%   |
| Ly      | 1        | 0.27%   |
| KDM     | 1        | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 182      | 50%     |
| nb_NO   | 73       | 20.05%  |
| Unknown | 42       | 11.54%  |
| en_GB   | 30       | 8.24%   |
| C       | 8        | 2.2%    |
| nn_NO   | 6        | 1.65%   |
| en_DK   | 6        | 1.65%   |
| de_DE   | 5        | 1.37%   |
| pl_PL   | 2        | 0.55%   |
| fr_FR   | 2        | 0.55%   |
| ru_RU   | 1        | 0.27%   |
| pt_PT   | 1        | 0.27%   |
| POSIX   | 1        | 0.27%   |
| it_IT   | 1        | 0.27%   |
| es_ES   | 1        | 0.27%   |
| en_CA   | 1        | 0.27%   |
| en_AG   | 1        | 0.27%   |
| da_DK   | 1        | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 182      | 50.14%  |
| EFI  | 181      | 49.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 266      | 73.68%  |
| Btrfs   | 48       | 13.3%   |
| Overlay | 21       | 5.82%   |
| Unknown | 9        | 2.49%   |
| Xfs     | 7        | 1.94%   |
| Zfs     | 3        | 0.83%   |
| Tmpfs   | 3        | 0.83%   |
| Ext2    | 3        | 0.83%   |
| F2fs    | 1        | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 190      | 52.2%   |
| GPT     | 145      | 39.84%  |
| MBR     | 29       | 7.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 288      | 78.69%  |
| Yes       | 78       | 21.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 243      | 66.39%  |
| Yes       | 123      | 33.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 150      | 42.25%  |
| Gigabyte Technology | 48       | 13.52%  |
| MSI                 | 42       | 11.83%  |
| Hewlett-Packard     | 26       | 7.32%   |
| ASRock              | 24       | 6.76%   |
| Dell                | 21       | 5.92%   |
| Lenovo              | 15       | 4.23%   |
| Acer                | 7        | 1.97%   |
| Unknown             | 4        | 1.13%   |
| Pegatron            | 3        | 0.85%   |
| Intel               | 3        | 0.85%   |
| Wibtek              | 1        | 0.28%   |
| Supermicro          | 1        | 0.28%   |
| Shuttle             | 1        | 0.28%   |
| Packard Bell        | 1        | 0.28%   |
| Lenovo Product      | 1        | 0.28%   |
| Fujitsu Siemens     | 1        | 0.28%   |
| Fujitsu             | 1        | 0.28%   |
| Cisco Systems       | 1        | 0.28%   |
| BESSTAR Tech        | 1        | 0.28%   |
| ASRockRack          | 1        | 0.28%   |
| Apple               | 1        | 0.28%   |
| Acidanthera         | 1        | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 14       | 3.94%   |
| ASUS KomplettPC                 | 7        | 1.97%   |
| ASUS ROG STRIX B360-F GAMING    | 5        | 1.41%   |
| MSI MS-7885                     | 4        | 1.13%   |
| Gigabyte GA-970A-UD3            | 4        | 1.13%   |
| ASUS ROG STRIX X570-F GAMING    | 4        | 1.13%   |
| ASUS ROG CROSSHAIR VIII HERO    | 4        | 1.13%   |
| ASUS M2R-FVM                    | 4        | 1.13%   |
| Unknown                         | 4        | 1.13%   |
| MSI MS-7B86                     | 3        | 0.85%   |
| HP Compaq Elite 8300 SFF        | 3        | 0.85%   |
| Dell OptiPlex 9020              | 3        | 0.85%   |
| Dell OptiPlex 7010              | 3        | 0.85%   |
| ASUS Z170 PRO GAMING            | 3        | 0.85%   |
| ASUS SABERTOOTH P67             | 3        | 0.85%   |
| ASUS ROG STRIX X470-F GAMING    | 3        | 0.85%   |
| ASUS ROG STRIX B550-I GAMING    | 3        | 0.85%   |
| ASUS ROG STRIX B550-E GAMING    | 3        | 0.85%   |
| ASUS ROG STRIX B450-F GAMING    | 3        | 0.85%   |
| ASUS PRIME X570-P               | 3        | 0.85%   |
| ASUS P9X79 LE                   | 3        | 0.85%   |
| MSI MS-7A93                     | 2        | 0.56%   |
| MSI MS-7A37                     | 2        | 0.56%   |
| MSI MS-7971                     | 2        | 0.56%   |
| MSI MS-7817                     | 2        | 0.56%   |
| HP EliteDesk 705 G4 DM 65W      | 2        | 0.56%   |
| Gigabyte Z490I AORUS ULTRA      | 2        | 0.56%   |
| Gigabyte X570 AORUS ELITE       | 2        | 0.56%   |
| Gigabyte B550 AORUS MASTER      | 2        | 0.56%   |
| Gigabyte 970A-DS3P              | 2        | 0.56%   |
| ASUS TUF Gaming X670E-PLUS WIFI | 2        | 0.56%   |
| ASUS TUF Gaming B550-PRO        | 2        | 0.56%   |
| ASUS SABERTOOTH Z77             | 2        | 0.56%   |
| ASUS ROG STRIX B460-F GAMING    | 2        | 0.56%   |
| ASUS PRIME Z270-P               | 2        | 0.56%   |
| ASUS PRIME X370-PRO             | 2        | 0.56%   |
| ASUS PRIME B350-PLUS            | 2        | 0.56%   |
| ASUS P8Z77-V LX                 | 2        | 0.56%   |
| ASUS Maximus VIII HERO          | 2        | 0.56%   |
| ASUS M5A97 R2.0                 | 2        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 42       | 11.83%  |
| ASUS PRIME           | 23       | 6.48%   |
| Dell OptiPlex        | 14       | 3.94%   |
| ASUS All             | 14       | 3.94%   |
| ASUS TUF             | 9        | 2.54%   |
| Lenovo ThinkCentre   | 8        | 2.25%   |
| HP EliteDesk         | 7        | 1.97%   |
| ASUS KomplettPC      | 7        | 1.97%   |
| Gigabyte X570        | 6        | 1.69%   |
| ASUS SABERTOOTH      | 6        | 1.69%   |
| Gigabyte B550        | 5        | 1.41%   |
| Gigabyte B450        | 5        | 1.41%   |
| Dell Precision       | 5        | 1.41%   |
| MSI MS-7885          | 4        | 1.13%   |
| HP Compaq            | 4        | 1.13%   |
| Gigabyte GA-970A-UD3 | 4        | 1.13%   |
| ASUS STRIX           | 4        | 1.13%   |
| ASUS P9X79           | 4        | 1.13%   |
| ASUS P8Z77-V         | 4        | 1.13%   |
| ASUS M2R-FVM         | 4        | 1.13%   |
| ASUS CROSSHAIR       | 4        | 1.13%   |
| ASRock X570          | 4        | 1.13%   |
| Unknown              | 4        | 1.13%   |
| MSI MS-7B86          | 3        | 0.85%   |
| Lenovo IdeaCentre    | 3        | 0.85%   |
| ASUS Z170            | 3        | 0.85%   |
| ASUS Maximus         | 3        | 0.85%   |
| ASUS M5A97           | 3        | 0.85%   |
| Acer Aspire          | 3        | 0.85%   |
| MSI MS-7A93          | 2        | 0.56%   |
| MSI MS-7A37          | 2        | 0.56%   |
| MSI MS-7971          | 2        | 0.56%   |
| MSI MS-7817          | 2        | 0.56%   |
| HP Z240              | 2        | 0.56%   |
| HP ProDesk           | 2        | 0.56%   |
| HP Pavilion          | 2        | 0.56%   |
| Gigabyte Z490I       | 2        | 0.56%   |
| Gigabyte Z370        | 2        | 0.56%   |
| Gigabyte 970A-DS3P   | 2        | 0.56%   |
| ASUS EX-A320M-GAMING | 2        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 43       | 12.11%  |
| 2019 | 41       | 11.55%  |
| 2020 | 35       | 9.86%   |
| 2012 | 30       | 8.45%   |
| 2015 | 29       | 8.17%   |
| 2013 | 28       | 7.89%   |
| 2017 | 25       | 7.04%   |
| 2014 | 23       | 6.48%   |
| 2021 | 19       | 5.35%   |
| 2016 | 16       | 4.51%   |
| 2011 | 16       | 4.51%   |
| 2022 | 12       | 3.38%   |
| 2010 | 12       | 3.38%   |
| 2009 | 8        | 2.25%   |
| 2006 | 6        | 1.69%   |
| 2008 | 3        | 0.85%   |
| 2007 | 3        | 0.85%   |
| 2005 | 3        | 0.85%   |
| 2023 | 2        | 0.56%   |
| 2001 | 1        | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 355      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 342      | 95.26%  |
| Enabled  | 17       | 4.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 355      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 107      | 29.56%  |
| 32.01-64.0      | 100      | 27.62%  |
| 8.01-16.0       | 44       | 12.15%  |
| 4.01-8.0        | 36       | 9.94%   |
| 64.01-256.0     | 32       | 8.84%   |
| 3.01-4.0        | 24       | 6.63%   |
| 24.01-32.0      | 12       | 3.31%   |
| 1.01-2.0        | 3        | 0.83%   |
| More than 256.0 | 2        | 0.55%   |
| 2.01-3.0        | 1        | 0.28%   |
| 0.01-0.5        | 1        | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 100      | 24.27%  |
| 4.01-8.0    | 95       | 23.06%  |
| 2.01-3.0    | 76       | 18.45%  |
| 3.01-4.0    | 63       | 15.29%  |
| 8.01-16.0   | 36       | 8.74%   |
| 0.51-1.0    | 19       | 4.61%   |
| 16.01-24.0  | 9        | 2.18%   |
| 0.01-0.5    | 5        | 1.21%   |
| 32.01-64.0  | 4        | 0.97%   |
| 24.01-32.0  | 4        | 0.97%   |
| 64.01-256.0 | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 108      | 29.11%  |
| 2      | 92       | 24.8%   |
| 3      | 60       | 16.17%  |
| 4      | 49       | 13.21%  |
| 5      | 22       | 5.93%   |
| 6      | 19       | 5.12%   |
| 7      | 7        | 1.89%   |
| 0      | 6        | 1.62%   |
| 8      | 4        | 1.08%   |
| 11     | 2        | 0.54%   |
| 9      | 2        | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 64.44%  |
| Yes       | 128      | 35.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 352      | 99.15%  |
| No        | 3        | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 179      | 50%     |
| No        | 179      | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 218      | 60.56%  |
| Yes       | 142      | 39.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Norway  | 355      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Oslo         | 76       | 19.84%  |
| Trondheim    | 26       | 6.79%   |
| Stavanger    | 14       | 3.66%   |
| Bergen       | 13       | 3.39%   |
| Kristiansand | 11       | 2.87%   |
| Sandefjord   | 10       | 2.61%   |
| Ålesund     | 9        | 2.35%   |
| Skien        | 6        | 1.57%   |
| Drammen      | 6        | 1.57%   |
| Kongsberg    | 5        | 1.31%   |
| Fornebu      | 5        | 1.31%   |
| Asker        | 5        | 1.31%   |
| Tromsø      | 4        | 1.04%   |
| Nesttun      | 4        | 1.04%   |
| Fetsund      | 4        | 1.04%   |
| Arendal      | 4        | 1.04%   |
| Vennesla     | 3        | 0.78%   |
| Sarpsborg    | 3        | 0.78%   |
| Sandnes      | 3        | 0.78%   |
| Notodden     | 3        | 0.78%   |
| Narvik       | 3        | 0.78%   |
| Mo i Rana    | 3        | 0.78%   |
| Lillestrøm  | 3        | 0.78%   |
| Lillehammer  | 3        | 0.78%   |
| Honefoss     | 3        | 0.78%   |
| Heimdal      | 3        | 0.78%   |
| Harstad      | 3        | 0.78%   |
| Egersund     | 3        | 0.78%   |
| Bo           | 3        | 0.78%   |
| Vollen       | 2        | 0.52%   |
| Vanse        | 2        | 0.52%   |
| Storebo      | 2        | 0.52%   |
| Stokmarknes  | 2        | 0.52%   |
| Stjordal     | 2        | 0.52%   |
| Soreide      | 2        | 0.52%   |
| Ramfjordbotn | 2        | 0.52%   |
| Porsgrunn    | 2        | 0.52%   |
| Mysen        | 2        | 0.52%   |
| Mjondalen    | 2        | 0.52%   |
| Lillesand    | 2        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives  | Percent |
|-----------------------------|----------|---------|---------|
| Samsung Electronics         | 180      | 334     | 25.42%  |
| Seagate                     | 133      | 280     | 18.79%  |
| WDC                         | 102      | 261     | 14.41%  |
| Kingston                    | 69       | 102     | 9.75%   |
| Toshiba                     | 25       | 30      | 3.53%   |
| Intel                       | 25       | 39      | 3.53%   |
| Crucial                     | 25       | 55      | 3.53%   |
| Corsair                     | 21       | 33      | 2.97%   |
| Hitachi                     | 18       | 24      | 2.54%   |
| Sandisk                     | 16       | 24      | 2.26%   |
| Phison                      | 13       | 17      | 1.84%   |
| HGST                        | 13       | 21      | 1.84%   |
| OCZ                         | 11       | 11      | 1.55%   |
| Micron Technology           | 6        | 8       | 0.85%   |
| PNY                         | 4        | 7       | 0.56%   |
| Phison Electronics          | 4        | 11      | 0.56%   |
| LITEONIT                    | 4        | 4       | 0.56%   |
| Kingston Technology Company | 4        | 6       | 0.56%   |
| Apple                       | 4        | 5       | 0.56%   |
| Unknown                     | 3        | 3       | 0.42%   |
| LITEON                      | 3        | 3       | 0.42%   |
| Intenso                     | 3        | 3       | 0.42%   |
| A-DATA Technology           | 3        | 3       | 0.42%   |
| SK hynix                    | 2        | 2       | 0.28%   |
| Silicon Motion              | 2        | 3       | 0.28%   |
| Unknown                     | 2        | 3       | 0.28%   |
| SPCC                        | 1        | 1       | 0.14%   |
| SandForce                   | 1        | 2       | 0.14%   |
| Radeon                      | 1        | 1       | 0.14%   |
| Netac                       | 1        | 1       | 0.14%   |
| MBED                        | 1        | 1       | 0.14%   |
| LDLC                        | 1        | 1       | 0.14%   |
| KingSpec                    | 1        | 2       | 0.14%   |
| KingFast                    | 1        | 1       | 0.14%   |
| JMicron Technology          | 1        | Unknown | 0.14%   |
| IET                         | 1        | 2       | 0.14%   |
| Goodram                     | 1        | 1       | 0.14%   |
| China                       | 1        | 1       | 0.14%   |
| Advantech                   | 1        | 1       | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 14       | 1.57%   |
| Samsung SSD 860 EVO 1TB                             | 13       | 1.46%   |
| Samsung SSD 840 EVO 250GB                           | 11       | 1.23%   |
| Samsung SSD 860 EVO 500GB                           | 10       | 1.12%   |
| Samsung SSD 850 EVO 500GB                           | 10       | 1.12%   |
| Kingston SV300S37A120G 120GB SSD                    | 10       | 1.12%   |
| Seagate ST4000DM004-2CV104 4TB                      | 9        | 1.01%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 8        | 0.9%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 8        | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB                      | 8        | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB                        | 8        | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB                      | 7        | 0.78%   |
| Samsung NVMe SSD Drive 500GB                        | 7        | 0.78%   |
| Samsung NVMe SSD Drive 1TB                          | 7        | 0.78%   |
| Kingston NVMe SSD Drive 1TB                         | 7        | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                     | 6        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6        | 0.67%   |
| Samsung SSD 860 EVO 250GB                           | 6        | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 6        | 0.67%   |
| Seagate ST8000VN004-2M2101 8TB                      | 5        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5        | 0.56%   |
| Seagate Expansion 1TB                               | 5        | 0.56%   |
| Seagate Backup+ Hub BK 8TB                          | 5        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                      | 5        | 0.56%   |
| Samsung SSD 840 EVO 120GB                           | 5        | 0.56%   |
| Samsung NVMe SSD Drive 256GB                        | 5        | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 5        | 0.56%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                | 5        | 0.56%   |
| Phison NVMe SSD Drive 1TB                           | 5        | 0.56%   |
| Kingston SV300S37A240G 240GB SSD                    | 5        | 0.56%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 4        | 0.45%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.45%   |
| Seagate ST4000VN008-2DR166 4TB                      | 4        | 0.45%   |
| Seagate ST4000DM000-1F2168 4TB                      | 4        | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB                      | 4        | 0.45%   |
| Seagate ST2000DM001-9YN164 2TB                      | 4        | 0.45%   |
| Seagate BUP Slim BK 2TB                             | 4        | 0.45%   |
| Samsung SSD 960 PRO 1TB                             | 4        | 0.45%   |
| Samsung SSD 960 EVO 500GB                           | 4        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 4        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 129      | 274    | 42.86%  |
| WDC                 | 86       | 215    | 28.57%  |
| Samsung Electronics | 26       | 42     | 8.64%   |
| Toshiba             | 20       | 22     | 6.64%   |
| Hitachi             | 18       | 24     | 5.98%   |
| HGST                | 13       | 21     | 4.32%   |
| Apple               | 4        | 5      | 1.33%   |
| Unknown             | 2        | 2      | 0.66%   |
| Intenso             | 1        | 1      | 0.33%   |
| IET                 | 1        | 2      | 0.33%   |
| Unknown             | 1        | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 111      | 173    | 41.11%  |
| Kingston            | 47       | 67     | 17.41%  |
| Crucial             | 23       | 53     | 8.52%   |
| Intel               | 17       | 28     | 6.3%    |
| WDC                 | 15       | 34     | 5.56%   |
| OCZ                 | 11       | 11     | 4.07%   |
| Corsair             | 11       | 15     | 4.07%   |
| SanDisk             | 6        | 6      | 2.22%   |
| PNY                 | 4        | 7      | 1.48%   |
| LITEONIT            | 4        | 4      | 1.48%   |
| Micron Technology   | 3        | 5      | 1.11%   |
| LITEON              | 3        | 3      | 1.11%   |
| A-DATA Technology   | 3        | 3      | 1.11%   |
| Toshiba             | 1        | 1      | 0.37%   |
| SPCC                | 1        | 1      | 0.37%   |
| SK hynix            | 1        | 1      | 0.37%   |
| SandForce           | 1        | 2      | 0.37%   |
| Radeon              | 1        | 1      | 0.37%   |
| LDLC                | 1        | 1      | 0.37%   |
| KingSpec            | 1        | 2      | 0.37%   |
| KingFast            | 1        | 1      | 0.37%   |
| Intenso             | 1        | 1      | 0.37%   |
| Goodram             | 1        | 1      | 0.37%   |
| China               | 1        | 1      | 0.37%   |
| Unknown             | 1        | 2      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 223      | 609    | 37.29%  |
| SSD     | 216      | 424    | 36.12%  |
| NVMe    | 151      | 266    | 25.25%  |
| Unknown | 8        | 8      | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 299      | 986    | 61.65%  |
| NVMe | 151      | 266    | 31.13%  |
| SAS  | 35       | 55     | 7.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 226      | 441    | 43.8%   |
| 0.51-1.0   | 132      | 225    | 25.58%  |
| 1.01-2.0   | 57       | 111    | 11.05%  |
| 3.01-4.0   | 38       | 65     | 7.36%   |
| 2.01-3.0   | 32       | 85     | 6.2%    |
| 4.01-10.0  | 29       | 103    | 5.62%   |
| 10.01-20.0 | 2        | 3      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 80       | 20.94%  |
| More than 3000 | 71       | 18.59%  |
| 501-1000       | 55       | 14.4%   |
| 251-500        | 53       | 13.87%  |
| 1001-2000      | 48       | 12.57%  |
| 2001-3000      | 24       | 6.28%   |
| 1-20           | 18       | 4.71%   |
| Unknown        | 17       | 4.45%   |
| 51-100         | 11       | 2.88%   |
| 21-50          | 5        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 113      | 28.18%  |
| 101-250        | 46       | 11.47%  |
| 501-1000       | 41       | 10.22%  |
| 51-100         | 35       | 8.73%   |
| 251-500        | 34       | 8.48%   |
| 21-50          | 34       | 8.48%   |
| More than 3000 | 33       | 8.23%   |
| 1001-2000      | 33       | 8.23%   |
| Unknown        | 17       | 4.24%   |
| 2001-3000      | 14       | 3.49%   |
| 0              | 1        | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Desktops | Drives | Percent |
|----------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB           | 2        | 5      | 4.08%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2        | 2      | 4.08%   |
| Seagate ST31000524AS 1TB               | 2        | 2      | 4.08%   |
| Hitachi HTS543216L9SA00 160GB          | 2        | 2      | 4.08%   |
| Hitachi HDS722020ALA330 2TB            | 2        | 2      | 4.08%   |
| WDC WD800JB-00CRA1 80GB                | 1        | 1      | 2.04%   |
| WDC WD800BB-00CAA1 80GB                | 1        | 1      | 2.04%   |
| WDC WD6400AAKS-75A7B0 640GB            | 1        | 2      | 2.04%   |
| WDC WD60EFRX-68L0BN1 6TB               | 1        | 1      | 2.04%   |
| WDC WD5000AAJS-00YFA0 500GB            | 1        | 1      | 2.04%   |
| WDC WD3200AAKS-00V1A0 320GB            | 1        | 1      | 2.04%   |
| WDC WD10EALX-009BA0 1TB                | 1        | 1      | 2.04%   |
| WDC WD10EADS-114BB1 1TB                | 1        | 1      | 2.04%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 1        | 1      | 2.04%   |
| Toshiba HDWD110 1TB                    | 1        | 1      | 2.04%   |
| Seagate ST9250827AS 250GB              | 1        | 1      | 2.04%   |
| Seagate ST4000VN008-2DR166 4TB         | 1        | 1      | 2.04%   |
| Seagate ST4000LM024-2AN17V 4TB         | 1        | 1      | 2.04%   |
| Seagate ST3500630AS 500GB              | 1        | 1      | 2.04%   |
| Seagate ST3500418AS 500GB              | 1        | 1      | 2.04%   |
| Seagate ST31000528AS 1TB               | 1        | 1      | 2.04%   |
| Seagate ST3000DM008-2DM166 3TB         | 1        | 1      | 2.04%   |
| Seagate ST3000DM001-1CH166 3TB         | 1        | 18     | 2.04%   |
| Seagate ST2000DX002-2DV164 2TB         | 1        | 2      | 2.04%   |
| Seagate ST2000DM008-2FR102 2TB         | 1        | 1      | 2.04%   |
| Seagate ST2000DM001-1E6164 2TB         | 1        | 1      | 2.04%   |
| Seagate ST1000DM010-2EP102 1TB         | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB         | 1        | 1      | 2.04%   |
| SanDisk SSD PLUS 1000GB                | 1        | 1      | 2.04%   |
| Samsung Electronics SSD 970 EVO 500GB  | 1        | 1      | 2.04%   |
| Samsung Electronics SSD 840 EVO 250GB  | 1        | 1      | 2.04%   |
| Samsung Electronics SP1614C 160GB      | 1        | 1      | 2.04%   |
| Samsung Electronics HD501LJ 500GB      | 1        | 1      | 2.04%   |
| OCZ VERTEX3 240GB SSD                  | 1        | 1      | 2.04%   |
| LITEON LCH-256V2S-11 2.5 7mm 256GB SSD | 1        | 1      | 2.04%   |
| LITEON IT LCS-256L9S-HP 256GB SSD      | 1        | 1      | 2.04%   |
| Kingston SHFS37A120G 120GB SSD         | 1        | 1      | 2.04%   |
| Intel SSDSC2CT120A3 120GB              | 1        | 1      | 2.04%   |
| Intel SSDSC2BF180A4H 180GB             | 1        | 1      | 2.04%   |
| Intel SSDPEKKW256G7 256GB              | 1        | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 33     | 29.79%  |
| WDC                 | 12       | 17     | 25.53%  |
| Hitachi             | 5        | 5      | 10.64%  |
| Samsung Electronics | 4        | 4      | 8.51%   |
| Intel               | 3        | 3      | 6.38%   |
| LITEON              | 2        | 2      | 4.26%   |
| HGST                | 2        | 3      | 4.26%   |
| Toshiba             | 1        | 1      | 2.13%   |
| SanDisk             | 1        | 1      | 2.13%   |
| OCZ                 | 1        | 1      | 2.13%   |
| Kingston            | 1        | 1      | 2.13%   |
| Crucial             | 1        | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 33     | 38.89%  |
| WDC                 | 12       | 17     | 33.33%  |
| Hitachi             | 5        | 5      | 13.89%  |
| Samsung Electronics | 2        | 2      | 5.56%   |
| HGST                | 2        | 3      | 5.56%   |
| Toshiba             | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 61     | 75%     |
| SSD  | 8        | 8      | 18.18%  |
| NVMe | 3        | 3      | 6.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB    | 3        | 3      | 75%     |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Apple    | 3        | 3      | 75%     |
| Kingston | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 213      | 731    | 52.08%  |
| Works    | 150      | 500    | 36.67%  |
| Malfunc  | 42       | 72     | 10.27%  |
| Failed   | 4        | 4      | 0.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 208      | 36.49%  |
| AMD                              | 143      | 25.09%  |
| Samsung Electronics              | 78       | 13.68%  |
| Kingston Technology Company      | 29       | 5.09%   |
| Phison Electronics               | 26       | 4.56%   |
| ASMedia Technology               | 24       | 4.21%   |
| SanDisk                          | 19       | 3.33%   |
| LSI Logic / Symbios Logic        | 7        | 1.23%   |
| Nvidia                           | 6        | 1.05%   |
| JMicron Technology               | 5        | 0.88%   |
| Toshiba America Info Systems     | 4        | 0.7%    |
| Marvell Technology Group         | 4        | 0.7%    |
| Micron Technology                | 3        | 0.53%   |
| Broadcom / LSI                   | 3        | 0.53%   |
| Silicon Motion                   | 2        | 0.35%   |
| Seagate Technology               | 2        | 0.35%   |
| Micron/Crucial Technology        | 2        | 0.35%   |
| SK hynix                         | 1        | 0.18%   |
| Silicon Integrated Systems [SiS] | 1        | 0.18%   |
| Silicon Image                    | 1        | 0.18%   |
| ADATA Technology                 | 1        | 0.18%   |
| Adaptec                          | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 92       | 13.47%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 42       | 6.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29       | 4.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 27       | 3.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26       | 3.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 24       | 3.51%   |
| AMD 500 Series Chipset SATA Controller                                         | 23       | 3.37%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 22       | 3.22%   |
| Intel SATA Controller [RAID mode]                                              | 21       | 3.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21       | 3.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 19       | 2.78%   |
| Kingston Company A2000 NVMe SSD                                                | 14       | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 14       | 2.05%   |
| Phison E16 PCIe4 NVMe Controller                                               | 13       | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12       | 1.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 11       | 1.61%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 11       | 1.61%   |
| Phison E12 NVMe Controller                                                     | 10       | 1.46%   |
| AMD 300 Series Chipset SATA Controller                                         | 10       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9        | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 8        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 1.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6        | 0.88%   |
| AMD X370 Series Chipset SATA Controller                                        | 6        | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 5        | 0.73%   |
| Intel SSD 660P Series                                                          | 5        | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5        | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 0.73%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 5        | 0.73%   |
| AMD SB600 IDE                                                                  | 5        | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4        | 0.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4        | 0.59%   |
| Kingston Company NVMe Controller                                               | 4        | 0.59%   |
| Kingston Company KC3000/Renegade NVMe SSD                                      | 4        | 0.59%   |
| Kingston Company KC2000/KC2500 NVMe SSD                                        | 4        | 0.59%   |
| JMicron JMB362 SATA Controller                                                 | 4        | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 316      | 57.88%  |
| NVMe | 152      | 27.84%  |
| IDE  | 40       | 7.33%   |
| RAID | 29       | 5.31%   |
| SCSI | 5        | 0.92%   |
| SAS  | 4        | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 204      | 57.46%  |
| AMD    | 151      | 42.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor        | 13       | 3.63%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 11       | 3.07%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 9        | 2.51%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 9        | 2.51%   |
| AMD Ryzen 5 3600 6-Core Processor          | 8        | 2.23%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 7        | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 6        | 1.68%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 6        | 1.68%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 6        | 1.68%   |
| Intel Core i7-5820K CPU @ 3.30GHz          | 5        | 1.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz           | 5        | 1.4%    |
| AMD Ryzen 9 5900X 12-Core Processor        | 5        | 1.4%    |
| AMD Ryzen 5 1600 Six-Core Processor        | 5        | 1.4%    |
| Intel Core i7-3770K CPU @ 3.50GHz          | 4        | 1.12%   |
| Intel Core i7-2600K CPU @ 3.40GHz          | 4        | 1.12%   |
| Intel Core i5-4460 CPU @ 3.20GHz           | 4        | 1.12%   |
| AMD Ryzen 7 1700 Eight-Core Processor      | 4        | 1.12%   |
| AMD Athlon 64 X2 Dual Core Processor 5400+ | 4        | 1.12%   |
| Intel Core i9-9900K CPU @ 3.60GHz          | 3        | 0.84%   |
| Intel Core i7-9700K CPU @ 3.60GHz          | 3        | 0.84%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 3        | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 3        | 0.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 3        | 0.84%   |
| Intel Core i7-6800K CPU @ 3.40GHz          | 3        | 0.84%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 3        | 0.84%   |
| Intel Core i7-3820 CPU @ 3.60GHz           | 3        | 0.84%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 3        | 0.84%   |
| Intel Core i5-6600K CPU @ 3.50GHz          | 3        | 0.84%   |
| Intel Core i5-6400 CPU @ 2.70GHz           | 3        | 0.84%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 3        | 0.84%   |
| Intel Core i5-3570 CPU @ 3.40GHz           | 3        | 0.84%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 3        | 0.84%   |
| AMD FX-8350 Eight-Core Processor           | 3        | 0.84%   |
| AMD FX-6300 Six-Core Processor             | 3        | 0.84%   |
| AMD A10-6800K APU with Radeon HD Graphics  | 3        | 0.84%   |
| Intel Xeon CPU E5620 @ 2.40GHz             | 2        | 0.56%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz        | 2        | 0.56%   |
| Intel Core i9-10900 CPU @ 2.80GHz          | 2        | 0.56%   |
| Intel Core i7-7820X CPU @ 3.60GHz          | 2        | 0.56%   |
| Intel Core i7-4771 CPU @ 3.50GHz           | 2        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 70       | 19.61%  |
| Intel Core i5           | 62       | 17.37%  |
| AMD Ryzen 7             | 38       | 10.64%  |
| AMD Ryzen 5             | 35       | 9.8%    |
| AMD Ryzen 9             | 31       | 8.68%   |
| Intel Xeon              | 16       | 4.48%   |
| Intel Core i3           | 15       | 4.2%    |
| Other                   | 11       | 3.08%   |
| AMD FX                  | 11       | 3.08%   |
| Intel Core i9           | 10       | 2.8%    |
| AMD Athlon 64 X2        | 6        | 1.68%   |
| Intel Pentium           | 5        | 1.4%    |
| AMD A10                 | 5        | 1.4%    |
| Intel Celeron           | 4        | 1.12%   |
| AMD Phenom II X4        | 4        | 1.12%   |
| Intel Pentium Dual-Core | 2        | 0.56%   |
| Intel Core 2 Duo        | 2        | 0.56%   |
| Intel Core 2            | 2        | 0.56%   |
| Intel Atom              | 2        | 0.56%   |
| AMD Ryzen Threadripper  | 2        | 0.56%   |
| AMD Ryzen 5 PRO         | 2        | 0.56%   |
| AMD Athlon II X4        | 2        | 0.56%   |
| AMD Athlon              | 2        | 0.56%   |
| AMD A8                  | 2        | 0.56%   |
| AMD A4                  | 2        | 0.56%   |
| Intel Pentium III       | 1        | 0.28%   |
| Intel Pentium Dual      | 1        | 0.28%   |
| Intel Pentium D         | 1        | 0.28%   |
| Intel Core 2 Quad       | 1        | 0.28%   |
| AMD Sempron             | 1        | 0.28%   |
| AMD Ryzen 7 PRO         | 1        | 0.28%   |
| AMD Ryzen 3             | 1        | 0.28%   |
| AMD Phenom II X6        | 1        | 0.28%   |
| AMD EPYC                | 1        | 0.28%   |
| AMD Dual Core Opteron   | 1        | 0.28%   |
| AMD Athlon II X2        | 1        | 0.28%   |
| AMD Athlon Dual Core    | 1        | 0.28%   |
| AMD Athlon 64           | 1        | 0.28%   |
| AMD A6                  | 1        | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 122      | 34.08%  |
| 6      | 70       | 19.55%  |
| 8      | 55       | 15.36%  |
| 2      | 52       | 14.53%  |
| 12     | 23       | 6.42%   |
| 16     | 13       | 3.63%   |
| 10     | 6        | 1.68%   |
| 3      | 6        | 1.68%   |
| 1      | 6        | 1.68%   |
| 32     | 1        | 0.28%   |
| 28     | 1        | 0.28%   |
| 24     | 1        | 0.28%   |
| 18     | 1        | 0.28%   |
| 14     | 1        | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 348      | 98.03%  |
| 2      | 7        | 1.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 250      | 70.03%  |
| 1      | 107      | 29.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 350      | 98.59%  |
| Unknown        | 4        | 1.13%   |
| 32-bit         | 1        | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 109      | 29.3%   |
| 0x306c3    | 28       | 7.53%   |
| 0x306a9    | 20       | 5.38%   |
| 0x08701021 | 20       | 5.38%   |
| 0x506e3    | 17       | 4.57%   |
| 0x906e9    | 12       | 3.23%   |
| 0x08701013 | 9        | 2.42%   |
| 0x906ea    | 8        | 2.15%   |
| 0x306f2    | 8        | 2.15%   |
| 0x206a7    | 8        | 2.15%   |
| 0x0a201016 | 8        | 2.15%   |
| 0x0800820d | 7        | 1.88%   |
| 0x0a601203 | 6        | 1.61%   |
| 0x06000852 | 6        | 1.61%   |
| 0x0a201009 | 5        | 1.34%   |
| 0x06001119 | 5        | 1.34%   |
| 0x906ed    | 4        | 1.08%   |
| 0x406f1    | 4        | 1.08%   |
| 0x206d7    | 4        | 1.08%   |
| 0x1067a    | 4        | 1.08%   |
| 0x0a201204 | 4        | 1.08%   |
| 0x906ec    | 3        | 0.81%   |
| 0x50654    | 3        | 0.81%   |
| 0x0a20120a | 3        | 0.81%   |
| 0x08101016 | 3        | 0.81%   |
| 0x08001138 | 3        | 0.81%   |
| 0x010000c8 | 3        | 0.81%   |
| 0xa0655    | 2        | 0.54%   |
| 0xa0653    | 2        | 0.54%   |
| 0x90672    | 2        | 0.54%   |
| 0x6fb      | 2        | 0.54%   |
| 0x6f6      | 2        | 0.54%   |
| 0x106e5    | 2        | 0.54%   |
| 0x106ca    | 2        | 0.54%   |
| 0x0a50000c | 2        | 0.54%   |
| 0x08001129 | 2        | 0.54%   |
| 0x06003104 | 2        | 0.54%   |
| 0x0600063e | 2        | 0.54%   |
| 0xf65      | 1        | 0.27%   |
| 0xa0671    | 1        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 45       | 12.68%  |
| Zen 2            | 40       | 11.27%  |
| KabyLake         | 39       | 10.99%  |
| Zen 3            | 32       | 9.01%   |
| Skylake          | 30       | 8.45%   |
| IvyBridge        | 24       | 6.76%   |
| Zen+             | 17       | 4.79%   |
| Zen              | 16       | 4.51%   |
| Piledriver       | 15       | 4.23%   |
| SandyBridge      | 14       | 3.94%   |
| Unknown          | 11       | 3.1%    |
| K8 Hammer        | 10       | 2.82%   |
| CometLake        | 9        | 2.54%   |
| K10              | 8        | 2.25%   |
| Broadwell        | 7        | 1.97%   |
| Westmere         | 5        | 1.41%   |
| Core             | 5        | 1.41%   |
| Penryn           | 4        | 1.13%   |
| Nehalem          | 4        | 1.13%   |
| Bulldozer        | 3        | 0.85%   |
| Alderlake Hybrid | 3        | 0.85%   |
| TigerLake        | 2        | 0.56%   |
| Steamroller      | 2        | 0.56%   |
| Silvermont       | 2        | 0.56%   |
| Bonnell          | 2        | 0.56%   |
| Puma             | 1        | 0.28%   |
| P6               | 1        | 0.28%   |
| NetBurst         | 1        | 0.28%   |
| Jaguar           | 1        | 0.28%   |
| Icelake          | 1        | 0.28%   |
| Goldmont         | 1        | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 170      | 44.74%  |
| AMD                        | 123      | 32.37%  |
| Intel                      | 84       | 22.11%  |
| Matrox Electronics Systems | 3        | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23       | 5.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 18       | 4.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 15       | 3.87%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 3.09%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 2.84%   |
| Intel HD Graphics 530                                                       | 10       | 2.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 2.32%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 2.32%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 8        | 2.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 7        | 1.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 1.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 1.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.55%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 1.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.55%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.55%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 6        | 1.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.29%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 1.29%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.29%   |
| AMD Raphael                                                                 | 5        | 1.29%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.03%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 1.03%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.03%   |
| Intel HD Graphics 630                                                       | 4        | 1.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.77%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 3        | 0.77%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.77%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 3        | 0.77%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.77%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.77%   |
| AMD Renoir                                                                  | 3        | 0.77%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 3        | 0.77%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 3        | 0.77%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 155      | 42.94%  |
| 1 x AMD              | 111      | 30.75%  |
| 1 x Intel            | 70       | 19.39%  |
| Intel + Nvidia       | 5        | 1.39%   |
| AMD + Nvidia         | 5        | 1.39%   |
| 2 x Nvidia           | 3        | 0.83%   |
| 2 x AMD              | 3        | 0.83%   |
| Intel + AMD          | 3        | 0.83%   |
| Other                | 2        | 0.55%   |
| 1 x Matrox           | 2        | 0.55%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.28%   |
| Nvidia + Matrox      | 1        | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 228      | 62.3%   |
| Proprietary | 119      | 32.51%  |
| Unknown     | 19       | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 142      | 38.48%  |
| 7.01-8.0   | 61       | 16.53%  |
| 1.01-2.0   | 46       | 12.47%  |
| 3.01-4.0   | 29       | 7.86%   |
| 8.01-16.0  | 22       | 5.96%   |
| 0.01-0.5   | 22       | 5.96%   |
| 0.51-1.0   | 17       | 4.61%   |
| 5.01-6.0   | 16       | 4.34%   |
| 2.01-3.0   | 10       | 2.71%   |
| 4.01-5.0   | 2        | 0.54%   |
| 16.01-24.0 | 2        | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 83       | 20.49%  |
| Dell                 | 48       | 11.85%  |
| AOC                  | 37       | 9.14%   |
| BenQ                 | 34       | 8.4%    |
| Acer                 | 33       | 8.15%   |
| Ancor Communications | 26       | 6.42%   |
| Philips              | 22       | 5.43%   |
| Hewlett-Packard      | 16       | 3.95%   |
| ASUSTek Computer     | 13       | 3.21%   |
| Lenovo               | 12       | 2.96%   |
| Goldstar             | 12       | 2.96%   |
| NEC Computers        | 6        | 1.48%   |
| Unknown              | 5        | 1.23%   |
| Eizo                 | 5        | 1.23%   |
| LG Electronics       | 4        | 0.99%   |
| Iiyama               | 3        | 0.74%   |
| HVR                  | 3        | 0.74%   |
| Grundig              | 3        | 0.74%   |
| Fujitsu Siemens      | 3        | 0.74%   |
| Denver               | 3        | 0.74%   |
| AUS                  | 3        | 0.74%   |
| VOXICON              | 2        | 0.49%   |
| Vestel Elektronik    | 2        | 0.49%   |
| Sony                 | 2        | 0.49%   |
| Sharp                | 2        | 0.49%   |
| Panasonic            | 2        | 0.49%   |
| Gigabyte Technology  | 2        | 0.49%   |
| Unknown              | 2        | 0.49%   |
| ViewSonic            | 1        | 0.25%   |
| Vestel               | 1        | 0.25%   |
| Toshiba              | 1        | 0.25%   |
| Positivo             | 1        | 0.25%   |
| Pioneer Electronic   | 1        | 0.25%   |
| Packard Bell         | 1        | 0.25%   |
| MSI                  | 1        | 0.25%   |
| Medion               | 1        | 0.25%   |
| Matrox               | 1        | 0.25%   |
| Lenovo Group Limited | 1        | 0.25%   |
| LaCie                | 1        | 0.25%   |
| ITE                  | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 5        | 1.14%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 5        | 1.14%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch    | 4        | 0.91%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch            | 4        | 0.91%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                         | 4        | 0.91%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                          | 4        | 0.91%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch   | 4        | 0.91%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 3        | 0.68%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 3        | 0.68%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch              | 3        | 0.68%   |
| Grundig WUXGA GRU4448 1920x1080                                         | 3        | 0.68%   |
| Fujitsu Siemens P27T-6 IPS FUS07EE 2560x1440 597x336mm 27.0-inch        | 3        | 0.68%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                      | 3        | 0.68%   |
| Dell 2007FP DELA021 1600x1200 410x310mm 20.2-inch                       | 3        | 0.68%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                      | 3        | 0.68%   |
| AOC AG273QS4R4 AOC2730 2560x1440 597x336mm 27.0-inch                    | 3        | 0.68%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 3        | 0.68%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch        | 3        | 0.68%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch   | 3        | 0.68%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                        | 2        | 0.46%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 460x300mm 21.6-inch    | 2        | 0.46%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch        | 2        | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.46%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch       | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0F0B 1920x1080 708x398mm 32.0-inch   | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0C00 3840x2160 1872x1053mm 84.6-inch | 2        | 0.46%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 2        | 0.46%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch      | 2        | 0.46%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch       | 2        | 0.46%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch       | 2        | 0.46%   |
| Philips LCD Monitor FTV 1920x1080                                       | 2        | 0.46%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 2        | 0.46%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                    | 2        | 0.46%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch                | 2        | 0.46%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch               | 2        | 0.46%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 2        | 0.46%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch          | 2        | 0.46%   |
| Eizo S2402W ENC1996 1920x1200 519x324mm 24.1-inch                       | 2        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 152      | 38.48%  |
| 3840x2160 (4K)     | 58       | 14.68%  |
| 2560x1440 (QHD)    | 54       | 13.67%  |
| 3440x1440          | 27       | 6.84%   |
| 1920x1200 (WUXGA)  | 26       | 6.58%   |
| 1680x1050 (WSXGA+) | 13       | 3.29%   |
| Unknown            | 11       | 2.78%   |
| 3840x1080          | 10       | 2.53%   |
| 1600x1200          | 7        | 1.77%   |
| 1280x1024 (SXGA)   | 7        | 1.77%   |
| 3840x1600          | 5        | 1.27%   |
| 2560x1080          | 5        | 1.27%   |
| 2288x1287          | 3        | 0.76%   |
| 2160x1200          | 3        | 0.76%   |
| 5120x1440          | 2        | 0.51%   |
| 4480x1440          | 2        | 0.51%   |
| 1360x768           | 2        | 0.51%   |
| 7680x1440          | 1        | 0.25%   |
| 7680x1080          | 1        | 0.25%   |
| 5760x2160          | 1        | 0.25%   |
| 5360x1440          | 1        | 0.25%   |
| 3840x1200          | 1        | 0.25%   |
| 3840x1024          | 1        | 0.25%   |
| 2560x1600          | 1        | 0.25%   |
| 1280x720 (HD)      | 1        | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 92       | 23.17%  |
| 27      | 83       | 20.91%  |
| Unknown | 53       | 13.35%  |
| 23      | 31       | 7.81%   |
| 34      | 27       | 6.8%    |
| 31      | 16       | 4.03%   |
| 21      | 13       | 3.27%   |
| 84      | 11       | 2.77%   |
| 22      | 10       | 2.52%   |
| 48      | 7        | 1.76%   |
| 25      | 6        | 1.51%   |
| 19      | 6        | 1.51%   |
| 54      | 5        | 1.26%   |
| 37      | 5        | 1.26%   |
| 20      | 5        | 1.26%   |
| 35      | 4        | 1.01%   |
| 32      | 4        | 1.01%   |
| 142     | 3        | 0.76%   |
| 33      | 2        | 0.5%    |
| 18      | 2        | 0.5%    |
| 72      | 1        | 0.25%   |
| 65      | 1        | 0.25%   |
| 60      | 1        | 0.25%   |
| 55      | 1        | 0.25%   |
| 44      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 42      | 1        | 0.25%   |
| 40      | 1        | 0.25%   |
| 39      | 1        | 0.25%   |
| 30      | 1        | 0.25%   |
| 26      | 1        | 0.25%   |
| 13      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 177      | 47.97%  |
| Unknown        | 53       | 14.36%  |
| 701-800        | 32       | 8.67%   |
| 601-700        | 27       | 7.32%   |
| 401-500        | 27       | 7.32%   |
| 1001-1500      | 15       | 4.07%   |
| 801-900        | 12       | 3.25%   |
| 1501-2000      | 12       | 3.25%   |
| 351-400        | 7        | 1.9%    |
| More than 2000 | 3        | 0.81%   |
| 201-300        | 2        | 0.54%   |
| 901-1000       | 2        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 212      | 58.56%  |
| 16/10   | 44       | 12.15%  |
| Unknown | 43       | 11.88%  |
| 21/9    | 36       | 9.94%   |
| 32/9    | 7        | 1.93%   |
| 5/4     | 6        | 1.66%   |
| 4/3     | 5        | 1.38%   |
| 3/2     | 3        | 0.83%   |
| 1.00    | 3        | 0.83%   |
| 6/5     | 1        | 0.28%   |
| 3.76    | 1        | 0.28%   |
| 0.80    | 1        | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 101      | 26.23%  |
| 301-350        | 84       | 21.82%  |
| 351-500        | 54       | 14.03%  |
| Unknown        | 53       | 13.77%  |
| 251-300        | 39       | 10.13%  |
| More than 1000 | 23       | 5.97%   |
| 151-200        | 16       | 4.16%   |
| 501-1000       | 14       | 3.64%   |
| 71-80          | 1        | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 194      | 52.29%  |
| 101-120 | 79       | 21.29%  |
| Unknown | 53       | 14.29%  |
| 121-160 | 19       | 5.12%   |
| 1-50    | 14       | 3.77%   |
| 161-240 | 12       | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 242      | 65.94%  |
| 2     | 82       | 22.34%  |
| 0     | 26       | 7.08%   |
| 3     | 15       | 4.09%   |
| 4     | 2        | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel                                  | 211      | 40.42%  |
| Realtek Semiconductor                  | 163      | 31.23%  |
| Qualcomm Atheros                       | 23       | 4.41%   |
| Broadcom                               | 23       | 4.41%   |
| NetGear                                | 11       | 2.11%   |
| Ralink                                 | 8        | 1.53%   |
| Ralink Technology                      | 7        | 1.34%   |
| MediaTek                               | 7        | 1.34%   |
| Nvidia                                 | 6        | 1.15%   |
| Aquantia                               | 6        | 1.15%   |
| TP-Link                                | 5        | 0.96%   |
| ASUSTek Computer                       | 5        | 0.96%   |
| Samsung Electronics                    | 4        | 0.77%   |
| Motorola PCS                           | 4        | 0.77%   |
| Microsoft                              | 4        | 0.77%   |
| Linksys                                | 4        | 0.77%   |
| Microchip Technology                   | 3        | 0.57%   |
| Marvell Technology Group               | 3        | 0.57%   |
| Chu Yuen Enterprise                    | 3        | 0.57%   |
| ASIX Electronics                       | 3        | 0.57%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.38%   |
| Sigma Designs                          | 2        | 0.38%   |
| Qualcomm Atheros Communications        | 2        | 0.38%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.38%   |
| Winbond Electronics                    | 1        | 0.19%   |
| Wacom                                  | 1        | 0.19%   |
| SEGGER                                 | 1        | 0.19%   |
| Huawei Technologies                    | 1        | 0.19%   |
| Holtek Semiconductor                   | 1        | 0.19%   |
| DisplayLink                            | 1        | 0.19%   |
| D-Link                                 | 1        | 0.19%   |
| Cisco Systems                          | 1        | 0.19%   |
| ATEN International                     | 1        | 0.19%   |
| Arduino SA                             | 1        | 0.19%   |
| 3Com                                   | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119      | 19.35%  |
| Intel I211 Gigabit Network Connection                             | 50       | 8.13%   |
| Intel Wi-Fi 6 AX200                                               | 37       | 6.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 4.39%   |
| Intel Ethernet Connection (2) I219-V                              | 25       | 4.07%   |
| Intel Ethernet Controller I225-V                                  | 22       | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 2.11%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 11       | 1.79%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.79%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 9        | 1.46%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 8        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 1.14%   |
| Intel Wireless-AC 9260                                            | 6        | 0.98%   |
| Intel I210 Gigabit Network Connection                             | 6        | 0.98%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 0.81%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 4        | 0.65%   |
| Motorola PCS Moto G Play                                          | 4        | 0.65%   |
| Intel Wireless 7265                                               | 4        | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.65%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 4        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.49%   |
| Microsoft Xbox 360 Wireless Adapter                               | 3        | 0.49%   |
| Microchip HTC Hub Controller                                      | 3        | 0.49%   |
| Intel Wireless 8260                                               | 3        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.49%   |
| Intel Centrino Wireless-N 2230                                    | 3        | 0.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 84       | 44.44%  |
| Realtek Semiconductor           | 23       | 12.17%  |
| Broadcom                        | 14       | 7.41%   |
| Qualcomm Atheros                | 11       | 5.82%   |
| NetGear                         | 11       | 5.82%   |
| Ralink                          | 8        | 4.23%   |
| Ralink Technology               | 7        | 3.7%    |
| MediaTek                        | 7        | 3.7%    |
| TP-Link                         | 5        | 2.65%   |
| ASUSTek Computer                | 5        | 2.65%   |
| Microsoft                       | 4        | 2.12%   |
| Linksys                         | 3        | 1.59%   |
| Chu Yuen Enterprise             | 3        | 1.59%   |
| Qualcomm Atheros Communications | 2        | 1.06%   |
| Wacom                           | 1        | 0.53%   |
| D-Link                          | 1        | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 37       | 19.58%  |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 9        | 4.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 8        | 4.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7        | 3.7%    |
| Intel Wireless-AC 9260                                         | 6        | 3.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5        | 2.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5        | 2.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 4        | 2.12%   |
| Intel Wireless 7265                                            | 4        | 2.12%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 4        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3        | 1.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3        | 1.59%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3        | 1.59%   |
| Intel Wireless 8260                                            | 3        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 1.59%   |
| Intel Centrino Wireless-N 2230                                 | 3        | 1.59%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3        | 1.59%   |
| Chu Yuen Enterprise GN-WB32L 802.11n USB WLAN Card             | 3        | 1.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 1.06%   |
| Realtek 802.11ac NIC                                           | 2        | 1.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 1.06%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.06%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 2        | 1.06%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2        | 1.06%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2        | 1.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2        | 1.06%   |
| Linksys WUSB6400M                                              | 2        | 1.06%   |
| Intel Wireless 8265 / 8275                                     | 2        | 1.06%   |
| Intel Wireless 7260                                            | 2        | 1.06%   |
| Intel Wireless 3165                                            | 2        | 1.06%   |
| Intel Wireless 3160                                            | 2        | 1.06%   |
| Intel Centrino Advanced-N 6235                                 | 2        | 1.06%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                       | 1        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel                                  | 185      | 47.31%  |
| Realtek Semiconductor                  | 154      | 39.39%  |
| Qualcomm Atheros                       | 14       | 3.58%   |
| Broadcom                               | 9        | 2.3%    |
| Nvidia                                 | 6        | 1.53%   |
| Aquantia                               | 6        | 1.53%   |
| Samsung Electronics                    | 3        | 0.77%   |
| Marvell Technology Group               | 3        | 0.77%   |
| ASIX Electronics                       | 3        | 0.77%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.26%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.26%   |
| Linksys                                | 1        | 0.26%   |
| Huawei Technologies                    | 1        | 0.26%   |
| DisplayLink                            | 1        | 0.26%   |
| Cisco Systems                          | 1        | 0.26%   |
| ATEN International                     | 1        | 0.26%   |
| 3Com                                   | 1        | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119      | 29.02%  |
| Intel I211 Gigabit Network Connection                             | 50       | 12.2%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 6.59%   |
| Intel Ethernet Connection (2) I219-V                              | 25       | 6.1%    |
| Intel Ethernet Controller I225-V                                  | 22       | 5.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 3.17%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 2.93%   |
| Intel Ethernet Connection I217-LM                                 | 11       | 2.68%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 2.68%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 2.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 1.71%   |
| Intel I210 Gigabit Network Connection                             | 6        | 1.46%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.22%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 1.22%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.73%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.49%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.49%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.49%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.49%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.49%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 0.49%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.49%   |
| ASIX AX88772                                                      | 2        | 0.49%   |
| Sony Ericsson Mobile AB XQ-CC54                                   | 1        | 0.24%   |
| Realtek RTL-8129                                                  | 1        | 0.24%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.24%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 352      | 64.35%  |
| WiFi     | 179      | 32.72%  |
| Modem    | 9        | 1.65%   |
| Unknown  | 7        | 1.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 277      | 75.68%  |
| WiFi     | 88       | 24.04%  |
| Unknown  | 1        | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 192      | 53.48%  |
| 2     | 136      | 37.88%  |
| 3     | 27       | 7.52%   |
| 0     | 3        | 0.84%   |
| 4     | 1        | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 320      | 87.91%  |
| Yes  | 44       | 12.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 73       | 51.05%  |
| Cambridge Silicon Radio         | 25       | 17.48%  |
| ASUSTek Computer                | 14       | 9.79%   |
| Realtek Semiconductor           | 6        | 4.2%    |
| MediaTek                        | 5        | 3.5%    |
| IMC Networks                    | 5        | 3.5%    |
| Belkin Components               | 4        | 2.8%    |
| HTC (High Tech Computer)        | 3        | 2.1%    |
| Broadcom                        | 3        | 2.1%    |
| Qualcomm Atheros Communications | 1        | 0.7%    |
| Integrated System Solution      | 1        | 0.7%    |
| Foxconn / Hon Hai               | 1        | 0.7%    |
| Apple                           | 1        | 0.7%    |
| Actions                         | 1        | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 31       | 21.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 25       | 17.36%  |
| Intel Bluetooth wireless interface                                   | 15       | 10.42%  |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 4.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 6        | 4.17%   |
| Realtek Bluetooth Radio                                              | 5        | 3.47%   |
| MediaTek Wireless_Device                                             | 5        | 3.47%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 5        | 3.47%   |
| Intel AX210 Bluetooth                                                | 5        | 3.47%   |
| Intel AX201 Bluetooth                                                | 5        | 3.47%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 2.78%   |
| IMC Networks Bluetooth Radio                                         | 3        | 2.08%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 2.08%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3        | 2.08%   |
| ASUS Bluetooth Radio                                                 | 3        | 2.08%   |
| IMC Networks BCM20702A0                                              | 2        | 1.39%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 1.39%   |
| ASUS ASUS USB-BT500                                                  | 2        | 1.39%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.69%   |
| Intel Bluetooth Device                                               | 1        | 0.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 0.69%   |
| Integrated System Solution Bluetooth Device                          | 1        | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 0.69%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 0.69%   |
| Broadcom Bluetooth 2.1 Device                                        | 1        | 0.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 0.69%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.69%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.69%   |
| Actions general adapter                                              | 1        | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 196      | 27.45%  |
| AMD                                          | 185      | 25.91%  |
| Nvidia                                       | 169      | 23.67%  |
| C-Media Electronics                          | 26       | 3.64%   |
| SteelSeries ApS                              | 16       | 2.24%   |
| Logitech                                     | 14       | 1.96%   |
| Kingston Technology                          | 9        | 1.26%   |
| Blue Microphones                             | 8        | 1.12%   |
| ASUSTek Computer                             | 7        | 0.98%   |
| Texas Instruments                            | 5        | 0.7%    |
| Creative Labs                                | 5        | 0.7%    |
| Corsair                                      | 5        | 0.7%    |
| SAVITECH                                     | 4        | 0.56%   |
| GN Netcom                                    | 4        | 0.56%   |
| Focusrite-Novation                           | 4        | 0.56%   |
| XMOS                                         | 3        | 0.42%   |
| Realtek Semiconductor                        | 3        | 0.42%   |
| Razer USA                                    | 3        | 0.42%   |
| FiiO Electronics Technology                  | 3        | 0.42%   |
| Creative Technology                          | 3        | 0.42%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.28%   |
| Yamaha                                       | 2        | 0.28%   |
| Scarlett                                     | 2        | 0.28%   |
| RODE Microphones                             | 2        | 0.28%   |
| Plantronics                                  | 2        | 0.28%   |
| Musical Fidelity                             | 2        | 0.28%   |
| M-Audio                                      | 2        | 0.28%   |
| GYROCOM C&C                                  | 2        | 0.28%   |
| Asahi Kasei Microsystems                     | 2        | 0.28%   |
| www.hirestech.com 2012 REV 1.8               | 1        | 0.14%   |
| Sony                                         | 1        | 0.14%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.14%   |
| Shenzhen Riitek Technology                   | 1        | 0.14%   |
| Schiit Audio                                 | 1        | 0.14%   |
| Samson Technologies                          | 1        | 0.14%   |
| ROCCAT                                       | 1        | 0.14%   |
| PS Audio                                     | 1        | 0.14%   |
| Nordic Semiconductor ASA                     | 1        | 0.14%   |
| Nektar                                       | 1        | 0.14%   |
| Micronas                                     | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 66       | 7.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 3.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26       | 3.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25       | 3.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 23       | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23       | 2.78%   |
| Intel 200 Series PCH HD Audio                                              | 23       | 2.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23       | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22       | 2.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21       | 2.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 19       | 2.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 18       | 2.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 17       | 2.06%   |
| AMD Navi 10 HDMI Audio                                                     | 15       | 1.82%   |
| Nvidia GA104 High Definition Audio Controller                              | 14       | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 12       | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 11       | 1.33%   |
| AMD FCH Azalia Controller                                                  | 11       | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 1.21%   |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 1.09%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 9        | 1.09%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 8        | 0.97%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 0.97%   |
| Nvidia TU104 HD Audio Controller                                           | 7        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 0.85%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7        | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 7        | 0.85%   |
| Kingston Technology HyperX 7.1 Audio                                       | 7        | 0.85%   |
| Blue Microphones Yeti Stereo Microphone                                    | 7        | 0.85%   |
| Nvidia GP102 HDMI Audio Controller                                         | 6        | 0.73%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 0.73%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 6        | 0.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 5        | 0.61%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 54       | 24.66%  |
| Corsair             | 48       | 21.92%  |
| Crucial             | 28       | 12.79%  |
| Unknown             | 20       | 9.13%   |
| SK hynix            | 19       | 8.68%   |
| G.Skill             | 19       | 8.68%   |
| Samsung Electronics | 14       | 6.39%   |
| Micron Technology   | 6        | 2.74%   |
| Ramaxel Technology  | 3        | 1.37%   |
| Patriot             | 2        | 0.91%   |
| Hewlett-Packard     | 1        | 0.46%   |
| GeIL                | 1        | 0.46%   |
| Elpida              | 1        | 0.46%   |
| Apacer              | 1        | 0.46%   |
| A-DATA Technology   | 1        | 0.46%   |
| Unknown             | 1        | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s | 8        | 3.46%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 5        | 2.16%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 5        | 2.16%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 5        | 2.16%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 5        | 2.16%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 4        | 1.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 4        | 1.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 3        | 1.3%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s    | 3        | 1.3%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 3        | 1.3%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 3        | 1.3%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 3        | 1.3%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s     | 3        | 1.3%    |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s      | 3        | 1.3%    |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s      | 2        | 0.87%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s      | 2        | 0.87%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2        | 0.87%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 2        | 0.87%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s      | 2        | 0.87%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 0.87%   |
| G.Skill RAM F4-3600C16-16GTZN 16GB DIMM DDR4 3733MT/s     | 2        | 0.87%   |
| G.Skill RAM F4-3200C16-16GSXWB 16GB DIMM DDR4 3200MT/s    | 2        | 0.87%   |
| Crucial RAM CT16G4SFD824A.M16FR 16GB SODIMM DDR4 2400MT/s | 2        | 0.87%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s     | 2        | 0.87%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s  | 2        | 0.87%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s       | 2        | 0.87%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s    | 2        | 0.87%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 2        | 0.87%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 0.43%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                  | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM                            | 1        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1        | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                  | 1        | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s             | 1        | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                  | 1        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 114      | 58.76%  |
| DDR3    | 53       | 27.32%  |
| DDR2    | 10       | 5.15%   |
| DDR5    | 6        | 3.09%   |
| Unknown | 6        | 3.09%   |
| SDRAM   | 3        | 1.55%   |
| DDR     | 2        | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 180      | 93.26%  |
| SODIMM | 13       | 6.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 84       | 40.58%  |
| 16384 | 59       | 28.5%   |
| 4096  | 36       | 17.39%  |
| 2048  | 14       | 6.76%   |
| 32768 | 8        | 3.86%   |
| 1024  | 4        | 1.93%   |
| 512   | 1        | 0.48%   |
| 128   | 1        | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 13.95%  |
| 3600    | 21       | 9.77%   |
| 3200    | 18       | 8.37%   |
| 2400    | 18       | 8.37%   |
| 1333    | 17       | 7.91%   |
| 3400    | 15       | 6.98%   |
| 2133    | 11       | 5.12%   |
| 667     | 10       | 4.65%   |
| 1800    | 8        | 3.72%   |
| 3000    | 7        | 3.26%   |
| 3466    | 5        | 2.33%   |
| 3733    | 4        | 1.86%   |
| 3533    | 4        | 1.86%   |
| 2800    | 4        | 1.86%   |
| 3866    | 3        | 1.4%    |
| 2667    | 3        | 1.4%    |
| 1867    | 3        | 1.4%    |
| 6400    | 2        | 0.93%   |
| 6000    | 2        | 0.93%   |
| 4800    | 2        | 0.93%   |
| 4000    | 2        | 0.93%   |
| 3333    | 2        | 0.93%   |
| 3151    | 2        | 0.93%   |
| 3100    | 2        | 0.93%   |
| 2933    | 2        | 0.93%   |
| 2733    | 2        | 0.93%   |
| 2666    | 2        | 0.93%   |
| 2000    | 2        | 0.93%   |
| 1066    | 2        | 0.93%   |
| 800     | 2        | 0.93%   |
| Unknown | 2        | 0.93%   |
| 3800    | 1        | 0.47%   |
| 3266    | 1        | 0.47%   |
| 2187    | 1        | 0.47%   |
| 2048    | 1        | 0.47%   |
| 1331    | 1        | 0.47%   |
| 100     | 1        | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 40%     |
| Brother Industries  | 3        | 30%     |
| Samsung Electronics | 1        | 10%     |
| Pantum              | 1        | 10%     |
| Canon               | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung M2020 Series                 | 1        | 10%     |
| Pantum P2500W series                 | 1        | 10%     |
| HP LaserJet Professional P 1102w     | 1        | 10%     |
| HP ENVY Photo 6200 series            | 1        | 10%     |
| HP DeskJet F300 series               | 1        | 10%     |
| HP Deskjet 2540 series               | 1        | 10%     |
| Canon PIXMA MX530 Series             | 1        | 10%     |
| Brother QL-800 P-touch Label Printer | 1        | 10%     |
| Brother QL-550 printer               | 1        | 10%     |
| Brother DCP-8085DN                   | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 4        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Canon CanoScan 9000F Mark II | 2        | 50%     |
| Canon CanoScan LiDE 200      | 1        | 25%     |
| Canon CanoScan LiDE 110      | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 43       | 53.09%  |
| Creative Technology           | 7        | 8.64%   |
| Microsoft                     | 5        | 6.17%   |
| Microdia                      | 5        | 6.17%   |
| Sunplus Innovation Technology | 3        | 3.7%    |
| Razer USA                     | 2        | 2.47%   |
| MacroSilicon                  | 2        | 2.47%   |
| Cubeternet                    | 2        | 2.47%   |
| Chicony Electronics           | 2        | 2.47%   |
| Apple                         | 2        | 2.47%   |
| Z-Star Microelectronics       | 1        | 1.23%   |
| Technologies                  | 1        | 1.23%   |
| Samsung Electronics           | 1        | 1.23%   |
| Novatek Microelectronics      | 1        | 1.23%   |
| Magewell                      | 1        | 1.23%   |
| Elgato Systems                | 1        | 1.23%   |
| ARC International             | 1        | 1.23%   |
| Alcor Micro                   | 1        | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 8        | 9.64%   |
| Logitech Webcam C270                                                | 6        | 7.23%   |
| Logitech C922 Pro Stream Webcam                                     | 6        | 7.23%   |
| Microsoft LifeCam Cinema                                            | 3        | 3.61%   |
| Logitech Webcam C930e                                               | 3        | 3.61%   |
| Logitech HD Webcam C525                                             | 3        | 3.61%   |
| Logitech B525 HD Webcam                                             | 3        | 3.61%   |
| Creative Live! Cam Chat HD [VF0700]                                 | 3        | 3.61%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]                          | 3        | 3.61%   |
| Sunplus HD 720P webcam                                              | 2        | 2.41%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 2        | 2.41%   |
| Microdia Camera                                                     | 2        | 2.41%   |
| MacroSilicon USB Video                                              | 2        | 2.41%   |
| Logitech Webcam C925e                                               | 2        | 2.41%   |
| Logitech Webcam C170                                                | 2        | 2.41%   |
| Logitech QuickCam Pro 9000                                          | 2        | 2.41%   |
| Logitech HD Webcam C615                                             | 2        | 2.41%   |
| Logitech BRIO Ultra HD Webcam                                       | 2        | 2.41%   |
| Logitech BRIO 4K Stream Edition                                     | 2        | 2.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                     | 2        | 2.41%   |
| Z-Star Lenovo ThinkCentre Web Camera                                | 1        | 1.2%    |
| Technologies ZED 2i                                                 | 1        | 1.2%    |
| Sunplus Sandberg USB Webcam Pro                                     | 1        | 1.2%    |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 1.2%    |
| Novatek HP High Definition 2MP Webcam                               | 1        | 1.2%    |
| Microsoft LifeCam Studio                                            | 1        | 1.2%    |
| Microsoft LifeCam HD-3000                                           | 1        | 1.2%    |
| Microdia WEBCAM PCYES RAZA FHD-03                                   | 1        | 1.2%    |
| Microdia USB 2.0 Camera                                             | 1        | 1.2%    |
| Microdia PC Microscope camera                                       | 1        | 1.2%    |
| Magewell USB Capture HDMI+                                          | 1        | 1.2%    |
| Logitech Webcam C310                                                | 1        | 1.2%    |
| Logitech StreamCam                                                  | 1        | 1.2%    |
| Logitech QuickCam E 3500                                            | 1        | 1.2%    |
| Logitech C920 PRO HD Webcam                                         | 1        | 1.2%    |
| Elgato Systems Elgato Facecam                                       | 1        | 1.2%    |
| Cubeternet Live Streaming USB Device                                | 1        | 1.2%    |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.2%    |
| Creative Live! Cam Optia                                            | 1        | 1.2%    |
| Chicony USB2.0 FHD UVC WebCam                                       | 1        | 1.2%    |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| OmniKey    | 2        | 66.67%  |
| Yubico.com | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121 | 2        | 66.67%  |
| Yubico.com Yubikey 4/5 CCID | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 282      | 78.77%  |
| 1     | 61       | 17.04%  |
| 2     | 11       | 3.07%   |
| 3     | 4        | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 28       | 31.82%  |
| Graphics card            | 22       | 25%     |
| Unassigned class         | 16       | 18.18%  |
| Sound                    | 5        | 5.68%   |
| Wireless                 | 4        | 4.55%   |
| Net/ethernet             | 3        | 3.41%   |
| Bluetooth                | 3        | 3.41%   |
| Chipcard                 | 2        | 2.27%   |
| Storage/raid             | 1        | 1.14%   |
| Multimedia controller    | 1        | 1.14%   |
| Dvb card                 | 1        | 1.14%   |
| Communication controller | 1        | 1.14%   |
| Camera                   | 1        | 1.14%   |

