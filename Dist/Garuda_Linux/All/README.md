Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

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

Total: 476

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [2a5b05500a](https://linux-hardware.org/?probe=2a5b05500a) | Nov 11, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [f0b3051737](https://linux-hardware.org/?probe=f0b3051737) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | Notebook    | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | Desktop     | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [1c50c72b71](https://linux-hardware.org/?probe=1c50c72b71) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | Notebook    | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | Notebook    | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f9fbb00a0b](https://linux-hardware.org/?probe=f9fbb00a0b) | Aug 23, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [822e93c1db](https://linux-hardware.org/?probe=822e93c1db) | Aug 02, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [e8770aea50](https://linux-hardware.org/?probe=e8770aea50) | Jul 14, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f44445fbe2](https://linux-hardware.org/?probe=f44445fbe2) | Jul 13, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [9ade46617e](https://linux-hardware.org/?probe=9ade46617e) | Jul 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [042c11425c](https://linux-hardware.org/?probe=042c11425c) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Samsung       | 730QDA                      | Convertible | [c46de205cd](https://linux-hardware.org/?probe=c46de205cd) | May 17, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Razer         | Blade                       | Notebook    | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| Unknown       | Unknown                     | Notebook    | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | Notebook    | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [646d26abf7](https://linux-hardware.org/?probe=646d26abf7) | Sep 08, 2021 |
| Razer         | Blade                       | Notebook    | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | Notebook    | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [e4593929ff](https://linux-hardware.org/?probe=e4593929ff) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Google        | Kindred                     | Notebook    | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Acer          | IPMBW-BR                    | All in one  | [a2ef77ad47](https://linux-hardware.org/?probe=a2ef77ad47) | Aug 03, 2021 |
| ASUSTek       | G750JZ                      | Notebook    | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cfaf6bb9ab](https://linux-hardware.org/?probe=cfaf6bb9ab) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | Notebook    | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | Desktop     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | Notebook    | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [aa8934716b](https://linux-hardware.org/?probe=aa8934716b) | May 13, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | Desktop     | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | Desktop     | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| Alienware     | 17 R3                       | Notebook    | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| HP            | 2B3B                        | All in one  | [1a5d2c36ec](https://linux-hardware.org/?probe=1a5d2c36ec) | Apr 06, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| HP            | 2AF7                        | Desktop     | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | Desktop     | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| HP            | 1825                        | Desktop     | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | Desktop     | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | Notebook    | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| HP            | 18E7                        | Desktop     | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |
| HP            | 450                         | Notebook    | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 204       | 61.45%  |
| Garuda Linux         | 107       | 32.23%  |
| Garuda Linux Rolling | 21        | 6.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 325       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 6.0.2-zen1-1-zen   | 9         | 2.36%   |
| 5.17.1-zen1-1-zen  | 9         | 2.36%   |
| 5.15.2-zen1-1-zen  | 7         | 1.83%   |
| 5.14.14-zen1-1-zen | 7         | 1.83%   |
| 5.17.9-zen1-1-zen  | 6         | 1.57%   |
| 5.16.4-zen1-1-zen  | 6         | 1.57%   |
| 6.0.8-zen1-1-zen   | 5         | 1.31%   |
| 5.18.16-zen1-1-zen | 5         | 1.31%   |
| 5.15.7-zen1-1-zen  | 5         | 1.31%   |
| 5.15.13-zen1-1-zen | 5         | 1.31%   |
| 5.15.12-zen1-1-zen | 5         | 1.31%   |
| 5.13.9-zen1-1-zen  | 5         | 1.31%   |
| 5.13.13-zen1-1-zen | 5         | 1.31%   |
| 5.11.16-zen1-1-zen | 5         | 1.31%   |
| 5.11.11-zen1-1-zen | 5         | 1.31%   |
| 6.0.9-zen1-1-zen   | 4         | 1.05%   |
| 5.19.7-zen2-1-zen  | 4         | 1.05%   |
| 5.18.6-zen1-1-zen  | 4         | 1.05%   |
| 5.18.12-zen1-1-zen | 4         | 1.05%   |
| 5.18.1-zen1-1-zen  | 4         | 1.05%   |
| 5.17.3-zen1-1-zen  | 4         | 1.05%   |
| 5.16.2-zen1-1-zen  | 4         | 1.05%   |
| 5.16.16-zen1-1-zen | 4         | 1.05%   |
| 5.15.6-zen2-1-zen  | 4         | 1.05%   |
| 5.10.4-107-tkg-bmq | 4         | 1.05%   |
| 5.10.1-103-tkg-bmq | 4         | 1.05%   |
| 6.0.6-zen1-1-zen   | 3         | 0.79%   |
| 5.9.10-zen1-1-zen  | 3         | 0.79%   |
| 5.9.1-zen2-1-zen   | 3         | 0.79%   |
| 5.19.5-zen1-1-zen  | 3         | 0.79%   |
| 5.19.2-zen1-1-zen  | 3         | 0.79%   |
| 5.19.13-zen1-1-zen | 3         | 0.79%   |
| 5.19.10-zen1-1-zen | 3         | 0.79%   |
| 5.18.3-zen1-1-zen  | 3         | 0.79%   |
| 5.18.14-zen1-1-zen | 3         | 0.79%   |
| 5.17.5-zen1-1-zen  | 3         | 0.79%   |
| 5.16.5-zen1-1-zen  | 3         | 0.79%   |
| 5.16.14-zen1-1-zen | 3         | 0.79%   |
| 5.16.11-zen1-1-zen | 3         | 0.79%   |
| 5.15.5-zen1-1-zen  | 3         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 11        | 2.88%   |
| 6.0.2   | 10        | 2.62%   |
| 5.15.2  | 7         | 1.83%   |
| 5.14.14 | 7         | 1.83%   |
| 6.0.8   | 6         | 1.57%   |
| 5.18.16 | 6         | 1.57%   |
| 5.17.9  | 6         | 1.57%   |
| 5.17.5  | 6         | 1.57%   |
| 5.17.3  | 6         | 1.57%   |
| 5.16.4  | 6         | 1.57%   |
| 5.15.7  | 6         | 1.57%   |
| 5.11.11 | 6         | 1.57%   |
| 5.10.4  | 6         | 1.57%   |
| 5.19.7  | 5         | 1.31%   |
| 5.16.5  | 5         | 1.31%   |
| 5.16.2  | 5         | 1.31%   |
| 5.15.13 | 5         | 1.31%   |
| 5.15.12 | 5         | 1.31%   |
| 5.13.9  | 5         | 1.31%   |
| 5.13.13 | 5         | 1.31%   |
| 5.11.16 | 5         | 1.31%   |
| 6.0.9   | 4         | 1.05%   |
| 5.19.2  | 4         | 1.05%   |
| 5.18.6  | 4         | 1.05%   |
| 5.18.3  | 4         | 1.05%   |
| 5.18.12 | 4         | 1.05%   |
| 5.18.1  | 4         | 1.05%   |
| 5.16.8  | 4         | 1.05%   |
| 5.16.16 | 4         | 1.05%   |
| 5.15.6  | 4         | 1.05%   |
| 5.15.5  | 4         | 1.05%   |
| 5.12.13 | 4         | 1.05%   |
| 5.10.15 | 4         | 1.05%   |
| 5.10.1  | 4         | 1.05%   |
| 6.0.6   | 3         | 0.79%   |
| 6.0.1   | 3         | 0.79%   |
| 5.9.10  | 3         | 0.79%   |
| 5.9.1   | 3         | 0.79%   |
| 5.19.5  | 3         | 0.79%   |
| 5.19.13 | 3         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 49        | 13.32%  |
| 5.16    | 41        | 11.14%  |
| 5.18    | 36        | 9.78%   |
| 5.10    | 36        | 9.78%   |
| 5.19    | 32        | 8.7%    |
| 5.17    | 31        | 8.42%   |
| 6.0     | 29        | 7.88%   |
| 5.14    | 27        | 7.34%   |
| 5.12    | 23        | 6.25%   |
| 5.11    | 23        | 6.25%   |
| 5.13    | 21        | 5.71%   |
| 5.9     | 13        | 3.53%   |
| 5.8     | 5         | 1.36%   |
| 5.6     | 1         | 0.27%   |
| 5.4     | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 325       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 212       | 64.05%  |
| GNOME             | 46        | 13.9%   |
| KDE               | 34        | 10.27%  |
| XFCE              | 10        | 3.02%   |
| X-Cinnamon        | 7         | 2.11%   |
| sway              | 6         | 1.81%   |
| Deepin            | 3         | 0.91%   |
| qtile-default     | 2         | 0.6%    |
| i3                | 2         | 0.6%    |
| Unknown           | 2         | 0.6%    |
| Yaru:ubuntu:GNOME | 1         | 0.3%    |
| Unity             | 1         | 0.3%    |
| MATE              | 1         | 0.3%    |
| LXQt              | 1         | 0.3%    |
| Cinnamon          | 1         | 0.3%    |
| Budgie            | 1         | 0.3%    |
| awesome           | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 295       | 89.39%  |
| Wayland | 25        | 7.58%   |
| Unknown | 7         | 2.12%   |
| Tty     | 3         | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 155       | 47.11%  |
| Unknown | 123       | 37.39%  |
| LightDM | 25        | 7.6%    |
| GDM     | 22        | 6.69%   |
| GREETD  | 4         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 166       | 50.61%  |
| en_GB   | 35        | 10.67%  |
| de_DE   | 24        | 7.32%   |
| en_IN   | 18        | 5.49%   |
| it_IT   | 10        | 3.05%   |
| en_CA   | 9         | 2.74%   |
| pt_BR   | 8         | 2.44%   |
| es_ES   | 6         | 1.83%   |
| ru_RU   | 5         | 1.52%   |
| nl_NL   | 4         | 1.22%   |
| es_MX   | 4         | 1.22%   |
| en_AU   | 4         | 1.22%   |
| pl_PL   | 3         | 0.91%   |
| sv_SE   | 2         | 0.61%   |
| fr_FR   | 2         | 0.61%   |
| fr_BE   | 2         | 0.61%   |
| fi_FI   | 2         | 0.61%   |
| es_VE   | 2         | 0.61%   |
| es_CO   | 2         | 0.61%   |
| en_ZA   | 2         | 0.61%   |
| en_AG   | 2         | 0.61%   |
| uk_UA   | 1         | 0.3%    |
| tr_TR   | 1         | 0.3%    |
| sk_SK   | 1         | 0.3%    |
| nl_BE   | 1         | 0.3%    |
| nb_NO   | 1         | 0.3%    |
| ko_KR   | 1         | 0.3%    |
| ja_JP   | 1         | 0.3%    |
| iu_CA   | 1         | 0.3%    |
| es_EC   | 1         | 0.3%    |
| es_AR   | 1         | 0.3%    |
| en_DK   | 1         | 0.3%    |
| en_DE   | 1         | 0.3%    |
| el_GR   | 1         | 0.3%    |
| de_AT   | 1         | 0.3%    |
| da_DK   | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 199       | 60.86%  |
| BIOS | 128       | 39.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 317       | 97.54%  |
| Overlay | 4         | 1.23%   |
| Ext4    | 2         | 0.62%   |
| XXXXX   | 1         | 0.31%   |
| F2fs    | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 190       | 58.1%   |
| Unknown | 122       | 37.31%  |
| MBR     | 15        | 4.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 287       | 86.97%  |
| Yes       | 43        | 13.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 224       | 68.09%  |
| Yes       | 105       | 31.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 61        | 18.77%  |
| Lenovo              | 52        | 16%     |
| Hewlett-Packard     | 46        | 14.15%  |
| MSI                 | 31        | 9.54%   |
| Dell                | 31        | 9.54%   |
| Gigabyte Technology | 23        | 7.08%   |
| Acer                | 22        | 6.77%   |
| ASRock              | 13        | 4%      |
| Samsung Electronics | 4         | 1.23%   |
| Apple               | 4         | 1.23%   |
| Unknown             | 4         | 1.23%   |
| Razer               | 3         | 0.92%   |
| Notebook            | 3         | 0.92%   |
| Medion              | 3         | 0.92%   |
| Fujitsu             | 3         | 0.92%   |
| Toshiba             | 2         | 0.62%   |
| Pegatron            | 2         | 0.62%   |
| HUAWEI              | 2         | 0.62%   |
| Alienware           | 2         | 0.62%   |
| T-bao               | 1         | 0.31%   |
| Sony                | 1         | 0.31%   |
| PC Specialist       | 1         | 0.31%   |
| Panasonic           | 1         | 0.31%   |
| OEM                 | 1         | 0.31%   |
| Microsoft           | 1         | 0.31%   |
| Kogan               | 1         | 0.31%   |
| HONOR               | 1         | 0.31%   |
| GPU Company         | 1         | 0.31%   |
| Google              | 1         | 0.31%   |
| Fujitsu Siemens     | 1         | 0.31%   |
| Chuwi               | 1         | 0.31%   |
| Casper              | 1         | 0.31%   |
| Biostar             | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 6         | 1.85%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 5         | 1.54%   |
| ASUS TUF Gaming X570-PLUS                  | 4         | 1.23%   |
| MSI MS-7C91                                | 2         | 0.62%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.62%   |
| HP ProBook 640 G1                          | 2         | 0.62%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.62%   |
| HP Notebook                                | 2         | 0.62%   |
| Gigabyte X570 AORUS PRO WIFI               | 2         | 0.62%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.62%   |
| Dell XPS 15 9500                           | 2         | 0.62%   |
| Dell Latitude E6420                        | 2         | 0.62%   |
| Dell Inspiron 3668                         | 2         | 0.62%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.62%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.62%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.62%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.62%   |
| ASUS All Series                            | 2         | 0.62%   |
| Acer Nitro AN515-44                        | 2         | 0.62%   |
| Acer Aspire A515-51G                       | 2         | 0.62%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.31%   |
| Toshiba Satellite C55-A                    | 1         | 0.31%   |
| T-bao MINI PC                              | 1         | 0.31%   |
| Sony VPCSB1C5E                             | 1         | 0.31%   |
| Samsung 730QDA                             | 1         | 0.31%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.31%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.31%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.31%   |
| Razer Blade 17 (Mid 2021) - RZ09-0406      | 1         | 0.31%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.31%   |
| Razer Blade                                | 1         | 0.31%   |
| Pegatron p7-1030                           | 1         | 0.31%   |
| Pegatron h9-1301es                         | 1         | 0.31%   |
| PC Specialist GK5NPFO                      | 1         | 0.31%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.31%   |
| Notebook W54_W550SU2                       | 1         | 0.31%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.31%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.31%   |
| MSI Sword 15 A11UD                         | 1         | 0.31%   |
| MSI MS-7D16                                | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 17        | 5.23%   |
| Lenovo ThinkPad       | 15        | 4.62%   |
| ASUS ROG              | 15        | 4.62%   |
| Dell Inspiron         | 13        | 4%      |
| Acer Aspire           | 12        | 3.69%   |
| HP Pavilion           | 11        | 3.38%   |
| ASUS VivoBook         | 9         | 2.77%   |
| Dell Latitude         | 8         | 2.46%   |
| ASUS PRIME            | 8         | 2.46%   |
| Lenovo Legion         | 7         | 2.15%   |
| HP Laptop             | 7         | 2.15%   |
| ASUS TUF              | 6         | 1.85%   |
| Unknown               | 6         | 1.85%   |
| Dell XPS              | 5         | 1.54%   |
| HP OMEN               | 4         | 1.23%   |
| Acer Swift            | 4         | 1.23%   |
| Acer Nitro            | 4         | 1.23%   |
| Razer Blade           | 3         | 0.92%   |
| Lenovo Yoga           | 3         | 0.92%   |
| Lenovo ThinkCentre    | 3         | 0.92%   |
| HP EliteBook          | 3         | 0.92%   |
| Gigabyte X570         | 3         | 0.92%   |
| Gigabyte B550         | 3         | 0.92%   |
| Gigabyte B450         | 3         | 0.92%   |
| Toshiba Satellite     | 2         | 0.62%   |
| MSI MS-7C91           | 2         | 0.62%   |
| MSI GF63              | 2         | 0.62%   |
| HP ProBook            | 2         | 0.62%   |
| HP Notebook           | 2         | 0.62%   |
| HP ENVY               | 2         | 0.62%   |
| Gigabyte AB350-Gaming | 2         | 0.62%   |
| Dell Precision        | 2         | 0.62%   |
| Dell OptiPlex         | 2         | 0.62%   |
| ASUS Maximus          | 2         | 0.62%   |
| ASUS ASUS             | 2         | 0.62%   |
| ASUS All              | 2         | 0.62%   |
| T-bao MINI            | 1         | 0.31%   |
| Sony VPCSB1C5E        | 1         | 0.31%   |
| Samsung 730QDA        | 1         | 0.31%   |
| Samsung 550XCJ        | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 60        | 18.46%  |
| 2021 | 43        | 13.23%  |
| 2019 | 38        | 11.69%  |
| 2018 | 34        | 10.46%  |
| 2017 | 30        | 9.23%   |
| 2013 | 23        | 7.08%   |
| 2016 | 19        | 5.85%   |
| 2014 | 19        | 5.85%   |
| 2012 | 16        | 4.92%   |
| 2015 | 12        | 3.69%   |
| 2011 | 11        | 3.38%   |
| 2010 | 6         | 1.85%   |
| 2022 | 5         | 1.54%   |
| 2009 | 5         | 1.54%   |
| 2008 | 2         | 0.62%   |
| 2007 | 2         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 188       | 57.85%  |
| Desktop     | 118       | 36.31%  |
| Convertible | 11        | 3.38%   |
| All in one  | 4         | 1.23%   |
| Tablet      | 3         | 0.92%   |
| Mini pc     | 1         | 0.31%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 325       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 324       | 99.69%  |
| Yes  | 1         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 85        | 25.84%  |
| 4.01-8.0    | 80        | 24.32%  |
| 8.01-16.0   | 74        | 22.49%  |
| 32.01-64.0  | 48        | 14.59%  |
| 3.01-4.0    | 20        | 6.08%   |
| 24.01-32.0  | 13        | 3.95%   |
| 64.01-256.0 | 8         | 2.43%   |
| 2.01-3.0    | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 126       | 35.8%   |
| 3.01-4.0   | 81        | 23.01%  |
| 2.01-3.0   | 81        | 23.01%  |
| 8.01-16.0  | 35        | 9.94%   |
| 1.01-2.0   | 21        | 5.97%   |
| 16.01-24.0 | 6         | 1.7%    |
| 32.01-64.0 | 1         | 0.28%   |
| 0.51-1.0   | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 148       | 44.05%  |
| 2      | 100       | 29.76%  |
| 3      | 43        | 12.8%   |
| 4      | 22        | 6.55%   |
| 5      | 13        | 3.87%   |
| 6      | 4         | 1.19%   |
| 9      | 3         | 0.89%   |
| 14     | 1         | 0.3%    |
| 7      | 1         | 0.3%    |
| 0      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 245       | 74.47%  |
| Yes       | 84        | 25.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 270       | 82.82%  |
| No        | 56        | 17.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 270       | 82.07%  |
| No        | 59        | 17.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 74.7%   |
| No        | 83        | 25.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 101       | 30.79%  |
| Germany      | 34        | 10.37%  |
| UK           | 20        | 6.1%    |
| India        | 20        | 6.1%    |
| Italy        | 18        | 5.49%   |
| Canada       | 14        | 4.27%   |
| Brazil       | 11        | 3.35%   |
| Poland       | 10        | 3.05%   |
| Netherlands  | 8         | 2.44%   |
| Spain        | 6         | 1.83%   |
| Russia       | 6         | 1.83%   |
| Romania      | 6         | 1.83%   |
| Mexico       | 6         | 1.83%   |
| Sweden       | 5         | 1.52%   |
| France       | 5         | 1.52%   |
| Belgium      | 5         | 1.52%   |
| Australia    | 5         | 1.52%   |
| Latvia       | 3         | 0.91%   |
| Finland      | 3         | 0.91%   |
| Denmark      | 3         | 0.91%   |
| Venezuela    | 2         | 0.61%   |
| Turkey       | 2         | 0.61%   |
| South Africa | 2         | 0.61%   |
| Singapore    | 2         | 0.61%   |
| Puerto Rico  | 2         | 0.61%   |
| Kuwait       | 2         | 0.61%   |
| Colombia     | 2         | 0.61%   |
| Ukraine      | 1         | 0.3%    |
| Switzerland  | 1         | 0.3%    |
| South Korea  | 1         | 0.3%    |
| Slovenia     | 1         | 0.3%    |
| Slovakia     | 1         | 0.3%    |
| Serbia       | 1         | 0.3%    |
| Portugal     | 1         | 0.3%    |
| Philippines  | 1         | 0.3%    |
| Oman         | 1         | 0.3%    |
| Norway       | 1         | 0.3%    |
| Luxembourg   | 1         | 0.3%    |
| Lithuania    | 1         | 0.3%    |
| Kenya        | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Milan             | 5         | 1.46%   |
| London            | 5         | 1.46%   |
| Berlin            | 5         | 1.46%   |
| San Jose          | 3         | 0.87%   |
| Riga              | 3         | 0.87%   |
| Portland          | 3         | 0.87%   |
| Mumbai            | 3         | 0.87%   |
| Dallas            | 3         | 0.87%   |
| Chicago           | 3         | 0.87%   |
| Wroclaw           | 2         | 0.58%   |
| Wasmes            | 2         | 0.58%   |
| Warsaw            | 2         | 0.58%   |
| Turin             | 2         | 0.58%   |
| Toronto           | 2         | 0.58%   |
| Timișoara        | 2         | 0.58%   |
| Sydney            | 2         | 0.58%   |
| St Louis          | 2         | 0.58%   |
| Singapore         | 2         | 0.58%   |
| Seattle           | 2         | 0.58%   |
| Sao Paulo         | 2         | 0.58%   |
| Pune              | 2         | 0.58%   |
| Puebla City       | 2         | 0.58%   |
| Peterborough      | 2         | 0.58%   |
| Oklahoma City     | 2         | 0.58%   |
| Noida             | 2         | 0.58%   |
| Montreal          | 2         | 0.58%   |
| Melbourne         | 2         | 0.58%   |
| Los Angeles       | 2         | 0.58%   |
| Kuwait City       | 2         | 0.58%   |
| Krakow            | 2         | 0.58%   |
| Kingsport         | 2         | 0.58%   |
| Kansas City       | 2         | 0.58%   |
| Helsinki          | 2         | 0.58%   |
| Hamburg           | 2         | 0.58%   |
| Frankfurt am Main | 2         | 0.58%   |
| Florence          | 2         | 0.58%   |
| Düsseldorf       | 2         | 0.58%   |
| Dortmund          | 2         | 0.58%   |
| Denver            | 2         | 0.58%   |
| Delhi             | 2         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 99        | 175    | 16.67%  |
| WDC                         | 86        | 117    | 14.48%  |
| Seagate                     | 84        | 120    | 14.14%  |
| SanDisk                     | 34        | 47     | 5.72%   |
| Toshiba                     | 30        | 36     | 5.05%   |
| Crucial                     | 26        | 36     | 4.38%   |
| SK hynix                    | 22        | 28     | 3.7%    |
| Kingston                    | 22        | 30     | 3.7%    |
| Intel                       | 18        | 25     | 3.03%   |
| Unknown                     | 16        | 16     | 2.69%   |
| Hitachi                     | 13        | 13     | 2.19%   |
| HGST                        | 13        | 13     | 2.19%   |
| Phison                      | 10        | 11     | 1.68%   |
| SPCC                        | 8         | 8      | 1.35%   |
| Silicon Motion              | 8         | 8      | 1.35%   |
| Micron Technology           | 8         | 8      | 1.35%   |
| A-DATA Technology           | 7         | 10     | 1.18%   |
| PNY                         | 6         | 6      | 1.01%   |
| KIOXIA                      | 6         | 8      | 1.01%   |
| China                       | 5         | 7      | 0.84%   |
| Phison Electronics          | 4         | 4      | 0.67%   |
| Micron/Crucial Technology   | 4         | 7      | 0.67%   |
| LITEON                      | 4         | 4      | 0.67%   |
| Corsair                     | 4         | 7      | 0.67%   |
| XPG                         | 3         | 4      | 0.51%   |
| OCZ                         | 3         | 3      | 0.51%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.34%   |
| Transcend                   | 2         | 2      | 0.34%   |
| Team                        | 2         | 3      | 0.34%   |
| Mushkin                     | 2         | 2      | 0.34%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.34%   |
| LITEONIT                    | 2         | 2      | 0.34%   |
| JMicron Technology          | 2         | 2      | 0.34%   |
| Intenso                     | 2         | 3      | 0.34%   |
| Emtec                       | 2         | 4      | 0.34%   |
| Unknown                     | 2         | 2      | 0.34%   |
| Yangtze Memory Technologies | 1         | 1      | 0.17%   |
| WODPOSIT                    | 1         | 2      | 0.17%   |
| WDC WDS                     | 1         | 1      | 0.17%   |
| WD MediaMax                 | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                        | 12        | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB                    | 9         | 1.34%   |
| Samsung SSD 860 EVO 1TB                           | 7         | 1.04%   |
| Crucial CT1000MX500SSD1 1TB                       | 7         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 0.89%   |
| Samsung SSD 970 EVO Plus 500GB                    | 6         | 0.89%   |
| Samsung SSD 860 EVO 500GB                         | 6         | 0.89%   |
| Samsung SSD 850 EVO 250GB                         | 6         | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 0.74%   |
| Seagate ST1000LM049-2GH172 1TB                    | 5         | 0.74%   |
| Samsung NVMe SSD Drive 500GB                      | 5         | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5         | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                    | 4         | 0.6%    |
| SanDisk SSD PLUS 1000GB                           | 4         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB                        | 4         | 0.6%    |
| Samsung NVMe SSD Drive 1024GB                     | 4         | 0.6%    |
| Intel SSD 660P Series 512GB                       | 4         | 0.6%    |
| HGST HTS721010A9E630 1TB                          | 4         | 0.6%    |
| WDC WD10EZEX-60WN4A0 1TB                          | 3         | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3         | 0.45%   |
| Unknown SD/MMC/MS PRO 8GB                         | 3         | 0.45%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 0.45%   |
| Toshiba DT01ACA100 1TB                            | 3         | 0.45%   |
| SPCC Solid State Disk 512GB                       | 3         | 0.45%   |
| SK hynix NVMe SSD Drive 512GB                     | 3         | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                    | 3         | 0.45%   |
| Seagate ST3000DM001-1ER166 3TB                    | 3         | 0.45%   |
| Seagate ST2000DL003-9VT166 2TB                    | 3         | 0.45%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 3         | 0.45%   |
| Seagate Portable 5TB                              | 3         | 0.45%   |
| Seagate Expansion Desk 8TB                        | 3         | 0.45%   |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 0.45%   |
| SanDisk NVMe SSD Drive 500GB                      | 3         | 0.45%   |
| Samsung SSD 970 EVO 250GB                         | 3         | 0.45%   |
| Samsung SSD 870 EVO 500GB                         | 3         | 0.45%   |
| Samsung SSD 860 EVO 250GB                         | 3         | 0.45%   |
| Samsung SSD 850 EVO 500GB                         | 3         | 0.45%   |
| PNY ELITE PSSD 240GB                              | 3         | 0.45%   |
| Micron/Crucial NVMe SSD Drive 1TB                 | 3         | 0.45%   |
| Kingston SA400S37240G 240GB SSD                   | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 115    | 41.75%  |
| WDC                 | 56        | 83     | 28.87%  |
| Toshiba             | 20        | 23     | 10.31%  |
| Hitachi             | 13        | 13     | 6.7%    |
| HGST                | 13        | 13     | 6.7%    |
| Samsung Electronics | 4         | 4      | 2.06%   |
| Unknown             | 3         | 3      | 1.55%   |
| Intenso             | 1         | 2      | 0.52%   |
| Inateck             | 1         | 1      | 0.52%   |
| ASMT                | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 70     | 25.93%  |
| Crucial             | 21        | 29     | 11.11%  |
| Kingston            | 17        | 23     | 8.99%   |
| SanDisk             | 16        | 25     | 8.47%   |
| WDC                 | 13        | 14     | 6.88%   |
| SPCC                | 7         | 7      | 3.7%    |
| A-DATA Technology   | 7         | 10     | 3.7%    |
| SK hynix            | 5         | 6      | 2.65%   |
| PNY                 | 5         | 5      | 2.65%   |
| China               | 5         | 7      | 2.65%   |
| Toshiba             | 4         | 7      | 2.12%   |
| LITEON              | 4         | 4      | 2.12%   |
| OCZ                 | 3         | 3      | 1.59%   |
| Micron Technology   | 3         | 3      | 1.59%   |
| Transcend           | 2         | 2      | 1.06%   |
| Team                | 2         | 3      | 1.06%   |
| Mushkin             | 2         | 2      | 1.06%   |
| LITEONIT            | 2         | 2      | 1.06%   |
| Emtec               | 2         | 4      | 1.06%   |
| WODPOSIT            | 1         | 2      | 0.53%   |
| WDC WDS             | 1         | 1      | 0.53%   |
| VisionTek           | 1         | 2      | 0.53%   |
| USB30               | 1         | 2      | 0.53%   |
| Unknown             | 1         | 1      | 0.53%   |
| TO Exter            | 1         | 1      | 0.53%   |
| T-FORCE             | 1         | 1      | 0.53%   |
| Qumo                | 1         | 1      | 0.53%   |
| PNY CS90            | 1         | 1      | 0.53%   |
| Plextor             | 1         | 1      | 0.53%   |
| Netac               | 1         | 1      | 0.53%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| Intenso             | 1         | 1      | 0.53%   |
| HS-SSD-C100         | 1         | 1      | 0.53%   |
| FORESEE             | 1         | 1      | 0.53%   |
| Corsair             | 1         | 1      | 0.53%   |
| ASMedia             | 1         | 2      | 0.53%   |
| ADATA SU            | 1         | 1      | 0.53%   |
| Unknown             | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 172       | 280    | 34.06%  |
| SSD     | 155       | 250    | 30.69%  |
| HDD     | 154       | 259    | 30.5%   |
| MMC     | 12        | 12     | 2.38%   |
| Unknown | 12        | 12     | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 225       | 469    | 50.56%  |
| NVMe | 172       | 278    | 38.65%  |
| SAS  | 36        | 54     | 8.09%   |
| MMC  | 12        | 12     | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 146       | 230    | 42.07%  |
| 0.51-1.0   | 124       | 170    | 35.73%  |
| 1.01-2.0   | 43        | 63     | 12.39%  |
| 2.01-3.0   | 11        | 18     | 3.17%   |
| 3.01-4.0   | 10        | 12     | 2.88%   |
| 4.01-10.0  | 10        | 11     | 2.88%   |
| 10.01-20.0 | 3         | 5      | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 131       | 39.22%  |
| 1001-2000      | 69        | 20.66%  |
| 501-1000       | 56        | 16.77%  |
| 2001-3000      | 37        | 11.08%  |
| 251-500        | 16        | 4.79%   |
| Unknown        | 14        | 4.19%   |
| 1-20           | 8         | 2.4%    |
| 101-250        | 3         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 80        | 23.05%  |
| 251-500        | 67        | 19.31%  |
| 501-1000       | 55        | 15.85%  |
| 1001-2000      | 45        | 12.97%  |
| 51-100         | 34        | 9.8%    |
| 2001-3000      | 21        | 6.05%   |
| More than 3000 | 19        | 5.48%   |
| Unknown        | 14        | 4.03%   |
| 1-20           | 9         | 2.59%   |
| 21-50          | 3         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 2.94%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 2.94%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1         | 1      | 2.94%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 2.94%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 2.94%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 2.94%   |
| WDC WD10EALX-009BA0 1TB               | 1         | 1      | 2.94%   |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 2.94%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 2.94%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 2.94%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 2.94%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 2.94%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 1      | 2.94%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 2.94%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 980 1TB       | 1         | 6      | 2.94%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 5      | 2.94%   |
| OCZ TRION100 480GB SSD                | 1         | 1      | 2.94%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 2.94%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1      | 2.94%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 2.94%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 2.94%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 2.94%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 2.94%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 2.94%   |
| Hewlett-Packard SSD EX900 500GB       | 1         | 1      | 2.94%   |
| Crucial CT960M500SSD1 960GB           | 1         | 1      | 2.94%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 2.94%   |
| A-DATA Technology SU800 1TB SSD       | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 27.27%  |
| Seagate             | 8         | 8      | 24.24%  |
| Hitachi             | 3         | 3      | 9.09%   |
| HGST                | 3         | 3      | 9.09%   |
| Kingston            | 2         | 2      | 6.06%   |
| SK hynix            | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 11     | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 9      | 37.5%   |
| Seagate | 8         | 8      | 33.33%  |
| Hitachi | 3         | 3      | 12.5%   |
| HGST    | 3         | 3      | 12.5%   |
| Apple   | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 24     | 71.88%  |
| SSD  | 6         | 6      | 18.75%  |
| NVMe | 3         | 13     | 9.38%   |

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
| Detected | 176       | 412    | 46.56%  |
| Works    | 171       | 358    | 45.24%  |
| Malfunc  | 31        | 43     | 8.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 186       | 39.16%  |
| AMD                            | 102       | 21.47%  |
| Samsung Electronics            | 54        | 11.37%  |
| SanDisk                        | 34        | 7.16%   |
| Phison Electronics             | 18        | 3.79%   |
| SK hynix                       | 17        | 3.58%   |
| Silicon Motion                 | 10        | 2.11%   |
| Micron/Crucial Technology      | 8         | 1.68%   |
| Kingston Technology Company    | 6         | 1.26%   |
| Toshiba America Info Systems   | 5         | 1.05%   |
| KIOXIA                         | 5         | 1.05%   |
| ASMedia Technology             | 5         | 1.05%   |
| Union Memory (Shenzhen)        | 4         | 0.84%   |
| Micron Technology              | 4         | 0.84%   |
| Marvell Technology Group       | 4         | 0.84%   |
| ADATA Technology               | 3         | 0.63%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.42%   |
| JMicron Technology             | 2         | 0.42%   |
| Yangtze Memory Technologies    | 1         | 0.21%   |
| Solid State Storage Technology | 1         | 0.21%   |
| Shenzhen Longsys Electronics   | 1         | 0.21%   |
| Realtek Semiconductor          | 1         | 0.21%   |
| Nvidia                         | 1         | 0.21%   |
| Lenovo                         | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 75        | 14.07%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 42        | 7.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 3.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 3.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 17        | 3.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 14        | 2.63%   |
| AMD 500 Series Chipset SATA Controller                                         | 14        | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 2.44%   |
| Phison E12 NVMe Controller                                                     | 12        | 2.25%   |
| Intel SSD 660P Series                                                          | 9         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.5%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 7         | 1.31%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.31%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.13%   |
| Intel Non-Volatile memory controller                                           | 6         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 5         | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 0.94%   |
| SanDisk Non-Volatile memory controller                                         | 5         | 0.94%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 0.94%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 4         | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 4         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 0.75%   |
| Micron Non-Volatile memory controller                                          | 4         | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 244       | 53.16%  |
| NVMe | 171       | 37.25%  |
| RAID | 31        | 6.75%   |
| IDE  | 13        | 2.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 196       | 60.31%  |
| AMD    | 129       | 39.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 2.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 2.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 1.84%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 1.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.53%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 5         | 1.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.53%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.23%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.92%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.92%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.92%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.92%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.92%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 0.92%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.92%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.92%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.92%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3         | 0.92%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.61%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.61%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.61%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 68        | 20.92%  |
| Intel Core i5           | 60        | 18.46%  |
| AMD Ryzen 7             | 41        | 12.62%  |
| AMD Ryzen 5             | 40        | 12.31%  |
| Intel Core i3           | 29        | 8.92%   |
| Other                   | 18        | 5.54%   |
| AMD Ryzen 9             | 13        | 4%      |
| Intel Celeron           | 8         | 2.46%   |
| AMD Ryzen 3             | 7         | 2.15%   |
| AMD A8                  | 5         | 1.54%   |
| Intel Xeon              | 4         | 1.23%   |
| AMD FX                  | 4         | 1.23%   |
| AMD A10                 | 4         | 1.23%   |
| AMD Ryzen Threadripper  | 3         | 0.92%   |
| Intel Pentium Silver    | 2         | 0.62%   |
| Intel Pentium Dual-Core | 2         | 0.62%   |
| Intel Pentium           | 2         | 0.62%   |
| Intel Core 2 Duo        | 2         | 0.62%   |
| AMD Ryzen 7 PRO         | 2         | 0.62%   |
| AMD A4                  | 2         | 0.62%   |
| Intel Core m3           | 1         | 0.31%   |
| Intel Core i9           | 1         | 0.31%   |
| Intel Core 2 Quad       | 1         | 0.31%   |
| AMD Turion              | 1         | 0.31%   |
| AMD Phenom II X6        | 1         | 0.31%   |
| AMD Phenom II X4        | 1         | 0.31%   |
| AMD Phenom II X2        | 1         | 0.31%   |
| AMD Athlon X4           | 1         | 0.31%   |
| AMD A6                  | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 109       | 33.54%  |
| 2      | 96        | 29.54%  |
| 6      | 57        | 17.54%  |
| 8      | 49        | 15.08%  |
| 12     | 7         | 2.15%   |
| 16     | 4         | 1.23%   |
| 24     | 1         | 0.31%   |
| 14     | 1         | 0.31%   |
| 10     | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 325       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 270       | 83.08%  |
| 1      | 55        | 16.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 325       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 149       | 44.74%  |
| 0x306a9    | 14        | 4.2%    |
| 0x306c3    | 11        | 3.3%    |
| 0x0a50000c | 11        | 3.3%    |
| 0x08108109 | 10        | 3%      |
| 0x906ea    | 9         | 2.7%    |
| 0x08701021 | 9         | 2.7%    |
| 0x806c1    | 8         | 2.4%    |
| 0x206a7    | 8         | 2.4%    |
| 0x906e9    | 6         | 1.8%    |
| 0x08600106 | 6         | 1.8%    |
| 0x0800820d | 6         | 1.8%    |
| 0xa0652    | 5         | 1.5%    |
| 0x806ea    | 5         | 1.5%    |
| 0x506e3    | 5         | 1.5%    |
| 0x806e9    | 4         | 1.2%    |
| 0x08600103 | 4         | 1.2%    |
| 0x406e3    | 3         | 0.9%    |
| 0x08608103 | 3         | 0.9%    |
| 0x08600104 | 3         | 0.9%    |
| 0x08108102 | 3         | 0.9%    |
| 0xa0653    | 2         | 0.6%    |
| 0x806ec    | 2         | 0.6%    |
| 0x40651    | 2         | 0.6%    |
| 0x106e5    | 2         | 0.6%    |
| 0x1067a    | 2         | 0.6%    |
| 0x0a50000b | 2         | 0.6%    |
| 0x0810100b | 2         | 0.6%    |
| 0x08101007 | 2         | 0.6%    |
| 0x08001137 | 2         | 0.6%    |
| 0x06006705 | 2         | 0.6%    |
| 0xa0660    | 1         | 0.3%    |
| 0xa0655    | 1         | 0.3%    |
| 0x906ed    | 1         | 0.3%    |
| 0x906ec    | 1         | 0.3%    |
| 0x906eb    | 1         | 0.3%    |
| 0x806d1    | 1         | 0.3%    |
| 0x706e5    | 1         | 0.3%    |
| 0x706a8    | 1         | 0.3%    |
| 0x706a1    | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 56        | 17.18%  |
| Zen 2           | 40        | 12.27%  |
| Zen 3           | 27        | 8.28%   |
| Zen+            | 26        | 7.98%   |
| Haswell         | 25        | 7.67%   |
| IvyBridge       | 20        | 6.13%   |
| Skylake         | 17        | 5.21%   |
| CometLake       | 17        | 5.21%   |
| SandyBridge     | 15        | 4.6%    |
| Zen             | 10        | 3.07%   |
| TigerLake       | 10        | 3.07%   |
| Unknown         | 9         | 2.76%   |
| Broadwell       | 8         | 2.45%   |
| Piledriver      | 6         | 1.84%   |
| Penryn          | 5         | 1.53%   |
| Steamroller     | 4         | 1.23%   |
| Puma            | 4         | 1.23%   |
| IceLake         | 4         | 1.23%   |
| Excavator       | 4         | 1.23%   |
| Westmere        | 3         | 0.92%   |
| Silvermont      | 3         | 0.92%   |
| Nehalem         | 3         | 0.92%   |
| K10             | 3         | 0.92%   |
| Goldmont plus   | 3         | 0.92%   |
| Goldmont        | 2         | 0.61%   |
| K8 & K10 hybrid | 1         | 0.31%   |
| Jaguar          | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 156       | 36.36%  |
| Nvidia | 148       | 34.5%   |
| AMD    | 125       | 29.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 20        | 4.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 16        | 3.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 14        | 3.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13        | 2.95%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 12        | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 11        | 2.49%   |
| Intel UHD Graphics 620                                                      | 10        | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 9         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 9         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 9         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8         | 1.81%   |
| Intel HD Graphics 620                                                       | 8         | 1.81%   |
| Nvidia TU117M                                                               | 7         | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 7         | 1.59%   |
| Intel HD Graphics 630                                                       | 7         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 6         | 1.36%   |
| Intel HD Graphics 5500                                                      | 6         | 1.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 6         | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 6         | 1.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 5         | 1.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 5         | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 1.13%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5         | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5         | 1.13%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 5         | 1.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5         | 1.13%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 4         | 0.91%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 0.91%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 0.91%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4         | 0.91%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3         | 0.68%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 3         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                | 3         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 3         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 3         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 86        | 26.22%  |
| 1 x Intel          | 82        | 25%     |
| 1 x Nvidia         | 58        | 17.68%  |
| Intel + Nvidia     | 57        | 17.38%  |
| AMD + Nvidia       | 29        | 8.84%   |
| Intel + AMD        | 7         | 2.13%   |
| 2 x AMD            | 5         | 1.52%   |
| 2 x Nvidia         | 2         | 0.61%   |
| Intel + 2 x Nvidia | 2         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 210       | 63.83%  |
| Proprietary | 119       | 36.17%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 56.42%  |
| 0.01-0.5   | 38        | 11.34%  |
| 1.01-2.0   | 28        | 8.36%   |
| 7.01-8.0   | 25        | 7.46%   |
| 3.01-4.0   | 22        | 6.57%   |
| 5.01-6.0   | 11        | 3.28%   |
| 0.51-1.0   | 11        | 3.28%   |
| 8.01-16.0  | 8         | 2.39%   |
| 2.01-3.0   | 2         | 0.6%    |
| 16.01-24.0 | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 50        | 12.47%  |
| Samsung Electronics  | 49        | 12.22%  |
| BOE                  | 35        | 8.73%   |
| LG Display           | 34        | 8.48%   |
| Chimei Innolux       | 31        | 7.73%   |
| Dell                 | 22        | 5.49%   |
| Goldstar             | 19        | 4.74%   |
| Acer                 | 19        | 4.74%   |
| AOC                  | 13        | 3.24%   |
| Hewlett-Packard      | 12        | 2.99%   |
| Sharp                | 11        | 2.74%   |
| PANDA                | 10        | 2.49%   |
| BenQ                 | 10        | 2.49%   |
| Ancor Communications | 9         | 2.24%   |
| Unknown              | 6         | 1.5%    |
| Lenovo               | 6         | 1.5%    |
| Philips              | 5         | 1.25%   |
| ASUSTek Computer     | 5         | 1.25%   |
| Sony                 | 4         | 1%      |
| MSI                  | 4         | 1%      |
| Gigabyte Technology  | 4         | 1%      |
| Vizio                | 3         | 0.75%   |
| Mi                   | 3         | 0.75%   |
| InfoVision           | 3         | 0.75%   |
| CSO                  | 3         | 0.75%   |
| Apple                | 3         | 0.75%   |
| NEC Computers        | 2         | 0.5%    |
| Iiyama               | 2         | 0.5%    |
| Unknown              | 2         | 0.5%    |
| Xiaomi               | 1         | 0.25%   |
| ViewSonic            | 1         | 0.25%   |
| Toshiba              | 1         | 0.25%   |
| OUT                  | 1         | 0.25%   |
| ONN                  | 1         | 0.25%   |
| MStar                | 1         | 0.25%   |
| MiTAC                | 1         | 0.25%   |
| Microstep            | 1         | 0.25%   |
| LTM                  | 1         | 0.25%   |
| LG Electronics       | 1         | 0.25%   |
| Lenovo Group Limited | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 4         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 4         | 0.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 3         | 0.72%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                       | 3         | 0.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.72%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 2         | 0.48%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 2         | 0.48%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 2         | 0.48%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.48%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.48%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch            | 2         | 0.48%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                | 2         | 0.48%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.48%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch       | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 0.48%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                  | 2         | 0.48%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                  | 2         | 0.48%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch          | 2         | 0.48%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2         | 0.48%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2         | 0.48%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                     | 2         | 0.48%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2         | 0.48%   |
| Unknown                                                                | 2         | 0.48%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                     | 1         | 0.24%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 195       | 51.32%  |
| 1366x768 (WXGA)    | 41        | 10.79%  |
| 3840x2160 (4K)     | 29        | 7.63%   |
| 2560x1440 (QHD)    | 17        | 4.47%   |
| 1600x900 (HD+)     | 15        | 3.95%   |
| 3440x1440          | 11        | 2.89%   |
| 1680x1050 (WSXGA+) | 9         | 2.37%   |
| Unknown            | 9         | 2.37%   |
| 1920x1200 (WUXGA)  | 7         | 1.84%   |
| 2560x1080          | 6         | 1.58%   |
| 3840x1080          | 5         | 1.32%   |
| 2560x1600          | 5         | 1.32%   |
| 1440x900 (WXGA+)   | 4         | 1.05%   |
| 1280x1024 (SXGA)   | 4         | 1.05%   |
| 7680x2160          | 2         | 0.53%   |
| 2256x1504          | 2         | 0.53%   |
| 1360x768           | 2         | 0.53%   |
| 1280x800 (WXGA)    | 2         | 0.53%   |
| 9600x2160          | 1         | 0.26%   |
| 4480x1440          | 1         | 0.26%   |
| 3840x2400          | 1         | 0.26%   |
| 3840x1200          | 1         | 0.26%   |
| 3200x1800 (QHD+)   | 1         | 0.26%   |
| 2880x1800          | 1         | 0.26%   |
| 2880x1440          | 1         | 0.26%   |
| 2736x1824          | 1         | 0.26%   |
| 2160x1440          | 1         | 0.26%   |
| 2048x1152          | 1         | 0.26%   |
| 1920x540           | 1         | 0.26%   |
| 1680x945           | 1         | 0.26%   |
| 1600x1200          | 1         | 0.26%   |
| 1280x768           | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 116       | 29.59%  |
| 27      | 40        | 10.2%   |
| 14      | 31        | 7.91%   |
| 24      | 28        | 7.14%   |
| Unknown | 27        | 6.89%   |
| 13      | 24        | 6.12%   |
| 23      | 21        | 5.36%   |
| 17      | 15        | 3.83%   |
| 34      | 11        | 2.81%   |
| 21      | 11        | 2.81%   |
| 31      | 8         | 2.04%   |
| 22      | 8         | 2.04%   |
| 19      | 8         | 2.04%   |
| 16      | 6         | 1.53%   |
| 20      | 5         | 1.28%   |
| 72      | 4         | 1.02%   |
| 18      | 4         | 1.02%   |
| 49      | 3         | 0.77%   |
| 54      | 2         | 0.51%   |
| 43      | 2         | 0.51%   |
| 40      | 2         | 0.51%   |
| 28      | 2         | 0.51%   |
| 12      | 2         | 0.51%   |
| 11      | 2         | 0.51%   |
| 85      | 1         | 0.26%   |
| 58      | 1         | 0.26%   |
| 52      | 1         | 0.26%   |
| 48      | 1         | 0.26%   |
| 47      | 1         | 0.26%   |
| 35      | 1         | 0.26%   |
| 33      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |
| 26      | 1         | 0.26%   |
| 25      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 159       | 41.51%  |
| 501-600     | 80        | 20.89%  |
| 401-500     | 32        | 8.36%   |
| Unknown     | 27        | 7.05%   |
| 351-400     | 19        | 4.96%   |
| 201-300     | 19        | 4.96%   |
| 601-700     | 15        | 3.92%   |
| 701-800     | 13        | 3.39%   |
| 1001-1500   | 9         | 2.35%   |
| 1501-2000   | 5         | 1.31%   |
| 801-900     | 3         | 0.78%   |
| 901-1000    | 2         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 269       | 76.64%  |
| 16/10   | 32        | 9.12%   |
| Unknown | 23        | 6.55%   |
| 21/9    | 13        | 3.7%    |
| 5/4     | 4         | 1.14%   |
| 3/2     | 4         | 1.14%   |
| 32/9    | 3         | 0.85%   |
| 4/3     | 2         | 0.57%   |
| 2.00    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 117       | 30.39%  |
| 201-250        | 55        | 14.29%  |
| 81-90          | 43        | 11.17%  |
| 301-350        | 41        | 10.65%  |
| Unknown        | 27        | 7.01%   |
| 351-500        | 23        | 5.97%   |
| 121-130        | 14        | 3.64%   |
| 151-200        | 13        | 3.38%   |
| More than 1000 | 11        | 2.86%   |
| 71-80          | 11        | 2.86%   |
| 251-300        | 9         | 2.34%   |
| 501-1000       | 7         | 1.82%   |
| 141-150        | 5         | 1.3%    |
| 111-120        | 3         | 0.78%   |
| 61-70          | 2         | 0.52%   |
| 51-60          | 2         | 0.52%   |
| 131-140        | 1         | 0.26%   |
| 91-100         | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 128       | 34.59%  |
| 51-100        | 98        | 26.49%  |
| 101-120       | 75        | 20.27%  |
| Unknown       | 27        | 7.3%    |
| 161-240       | 22        | 5.95%   |
| 1-50          | 11        | 2.97%   |
| More than 240 | 9         | 2.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 234       | 70.27%  |
| 2     | 84        | 25.23%  |
| 3     | 11        | 3.3%    |
| 0     | 4         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 195       | 38.01%  |
| Intel                             | 171       | 33.33%  |
| Qualcomm Atheros                  | 53        | 10.33%  |
| Broadcom                          | 20        | 3.9%    |
| MediaTek                          | 11        | 2.14%   |
| TP-Link                           | 6         | 1.17%   |
| Ralink Technology                 | 6         | 1.17%   |
| NetGear                           | 6         | 1.17%   |
| Samsung Electronics               | 5         | 0.97%   |
| ASIX Electronics                  | 4         | 0.78%   |
| Microsoft                         | 3         | 0.58%   |
| Linksys                           | 3         | 0.58%   |
| DisplayLink                       | 3         | 0.58%   |
| Aquantia                          | 3         | 0.58%   |
| Ralink                            | 2         | 0.39%   |
| Qualcomm                          | 2         | 0.39%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.39%   |
| ASUSTek Computer                  | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.19%   |
| Xiaomi                            | 1         | 0.19%   |
| Wacom                             | 1         | 0.19%   |
| Sierra Wireless                   | 1         | 0.19%   |
| Nvidia                            | 1         | 0.19%   |
| Motorola PCS                      | 1         | 0.19%   |
| Lenovo                            | 1         | 0.19%   |
| InterBiometrics                   | 1         | 0.19%   |
| Holtek Semiconductor              | 1         | 0.19%   |
| Google                            | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Dell                              | 1         | 0.19%   |
| Broadcom Limited                  | 1         | 0.19%   |
| Belkin Components                 | 1         | 0.19%   |
| Alteon Networks                   | 1         | 0.19%   |
| Accton Technology                 | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 137       | 23.18%  |
| Intel Wi-Fi 6 AX200                                               | 30        | 5.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.71%   |
| Intel I211 Gigabit Network Connection                             | 15        | 2.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 1.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.52%   |
| Intel Wireless 7265                                               | 9         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 1.18%   |
| Intel Wireless-AC 9260                                            | 7         | 1.18%   |
| Intel Wireless 3165                                               | 7         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.02%   |
| Intel Wireless 7260                                               | 6         | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.02%   |
| Intel Wireless 8260                                               | 5         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 49.66%  |
| Realtek Semiconductor | 51        | 17.59%  |
| Qualcomm Atheros      | 39        | 13.45%  |
| Broadcom              | 15        | 5.17%   |
| MediaTek              | 9         | 3.1%    |
| Ralink Technology     | 6         | 2.07%   |
| NetGear               | 6         | 2.07%   |
| TP-Link               | 5         | 1.72%   |
| Microsoft             | 3         | 1.03%   |
| Linksys               | 3         | 1.03%   |
| Ralink                | 2         | 0.69%   |
| ASUSTek Computer      | 2         | 0.69%   |
| Wacom                 | 1         | 0.34%   |
| Sierra Wireless       | 1         | 0.34%   |
| Dell                  | 1         | 0.34%   |
| Broadcom Limited      | 1         | 0.34%   |
| Accton Technology     | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 30        | 10.27%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 16        | 5.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 11        | 3.77%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 11        | 3.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 9         | 3.08%   |
| Intel Wireless 8265 / 8275                                          | 9         | 3.08%   |
| Intel Wireless 7265                                                 | 9         | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 9         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 8         | 2.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 8         | 2.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 7         | 2.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 7         | 2.4%    |
| Intel Wireless-AC 9260                                              | 7         | 2.4%    |
| Intel Wireless 3165                                                 | 7         | 2.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 7         | 2.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 6         | 2.05%   |
| Intel Wireless 7260                                                 | 6         | 2.05%   |
| Intel Wi-Fi 6 AX201                                                 | 6         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 6         | 2.05%   |
| Intel Wireless 8260                                                 | 5         | 1.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 4         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 4         | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 3         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 3         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 3         | 1.03%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                       | 3         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 3         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 2         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                     | 2         | 0.68%   |
| NetGear A6210                                                       | 2         | 0.68%   |
| Microsoft XBOX ACC                                                  | 2         | 0.68%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 172       | 58.9%   |
| Intel                         | 64        | 21.92%  |
| Qualcomm Atheros              | 20        | 6.85%   |
| Broadcom                      | 8         | 2.74%   |
| Samsung Electronics           | 5         | 1.71%   |
| ASIX Electronics              | 4         | 1.37%   |
| DisplayLink                   | 3         | 1.03%   |
| Aquantia                      | 3         | 1.03%   |
| Qualcomm                      | 2         | 0.68%   |
| MediaTek                      | 2         | 0.68%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.34%   |
| Xiaomi                        | 1         | 0.34%   |
| TP-Link                       | 1         | 0.34%   |
| OnePlus Technology (Shenzhen) | 1         | 0.34%   |
| Nvidia                        | 1         | 0.34%   |
| Lenovo                        | 1         | 0.34%   |
| Google                        | 1         | 0.34%   |
| Belkin Components             | 1         | 0.34%   |
| Alteon Networks               | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 137       | 46.6%   |
| Intel I211 Gigabit Network Connection                             | 15        | 5.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 3.74%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.04%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.04%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.68%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.68%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.34%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.34%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.34%   |
| Qualcomm OnePlus 6                                                | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.34%   |
| OnePlus (Shenzhen) AC2003                                         | 1         | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 269       | 49.54%  |
| Ethernet | 269       | 49.54%  |
| Unknown  | 3         | 0.55%   |
| Modem    | 2         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 207       | 62.35%  |
| Ethernet | 125       | 37.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 179       | 54.91%  |
| 1     | 133       | 40.8%   |
| 3     | 9         | 2.76%   |
| 0     | 4         | 1.23%   |
| 4     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 248       | 75.38%  |
| Yes  | 81        | 24.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 51.21%  |
| Realtek Semiconductor           | 34        | 13.71%  |
| Qualcomm Atheros Communications | 25        | 10.08%  |
| IMC Networks                    | 12        | 4.84%   |
| Cambridge Silicon Radio         | 12        | 4.84%   |
| Foxconn / Hon Hai               | 8         | 3.23%   |
| Broadcom                        | 8         | 3.23%   |
| Lite-On Technology              | 5         | 2.02%   |
| ASUSTek Computer                | 5         | 2.02%   |
| Apple                           | 4         | 1.61%   |
| Hewlett-Packard                 | 2         | 0.81%   |
| Dell                            | 2         | 0.81%   |
| Realtek                         | 1         | 0.4%    |
| Edimax Technology               | 1         | 0.4%    |
| Dynex                           | 1         | 0.4%    |
| AboCom Systems                  | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 32        | 12.9%   |
| Intel AX200 Bluetooth                                                               | 30        | 12.1%   |
| Intel AX201 Bluetooth                                                               | 23        | 9.27%   |
| Realtek Bluetooth Radio                                                             | 19        | 7.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 6.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 5.24%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 4.84%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 7         | 2.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 2.42%   |
| Intel AX210 Bluetooth                                                               | 6         | 2.42%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 2.42%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.21%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 1.21%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.21%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.81%   |
| ASUS Bluetooth Radio                                                                | 2         | 0.81%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.4%    |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.4%    |
| Lite-On Bluetooth Device                                                            | 1         | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.4%    |
| Intel Bluetooth Device                                                              | 1         | 0.4%    |
| IMC Networks Bluetooth Device                                                       | 1         | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.4%    |
| Edimax Bluetooth Adapter                                                            | 1         | 0.4%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.4%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 195       | 38.92%  |
| AMD                       | 139       | 27.74%  |
| Nvidia                    | 100       | 19.96%  |
| C-Media Electronics       | 11        | 2.2%    |
| Logitech                  | 9         | 1.8%    |
| Sony                      | 3         | 0.6%    |
| Kingston Technology       | 3         | 0.6%    |
| JMTek                     | 3         | 0.6%    |
| Blue Microphones          | 3         | 0.6%    |
| Trust                     | 2         | 0.4%    |
| RODE Microphones          | 2         | 0.4%    |
| Generalplus Technology    | 2         | 0.4%    |
| DSEA A/S                  | 2         | 0.4%    |
| Creative Technology       | 2         | 0.4%    |
| Creative Labs             | 2         | 0.4%    |
| Corsair                   | 2         | 0.4%    |
| Yamaha                    | 1         | 0.2%    |
| WL80                      | 1         | 0.2%    |
| Turtle Beach              | 1         | 0.2%    |
| Texas Instruments         | 1         | 0.2%    |
| Tenx Technology           | 1         | 0.2%    |
| SteelSeries ApS           | 1         | 0.2%    |
| Sennheiser Communications | 1         | 0.2%    |
| Samson Technologies       | 1         | 0.2%    |
| ROCCAT                    | 1         | 0.2%    |
| Realtek Semiconductor     | 1         | 0.2%    |
| Plantronics               | 1         | 0.2%    |
| Phison Electronics        | 1         | 0.2%    |
| Huawei Technologies       | 1         | 0.2%    |
| Hewlett-Packard           | 1         | 0.2%    |
| Harman International      | 1         | 0.2%    |
| GN Netcom                 | 1         | 0.2%    |
| Focusrite-Novation        | 1         | 0.2%    |
| EVGA                      | 1         | 0.2%    |
| DigiTech                  | 1         | 0.2%    |
| Audio-Technica            | 1         | 0.2%    |
| Alesis                    | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 61        | 9.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 31        | 4.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 29        | 4.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 3.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 3.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13        | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13        | 2.08%   |
| Intel Comet Lake PCH cAVS                                                  | 12        | 1.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.76%   |
| AMD FCH Azalia Controller                                                  | 11        | 1.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10        | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 9         | 1.44%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                              | 7         | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.12%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.12%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.12%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 0.96%   |
| Intel CM238 HD Audio Controller                                            | 6         | 0.96%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 0.8%    |
| C-Media Electronics USB Audio Device                                       | 5         | 0.8%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5         | 0.8%    |
| AMD Navi 10 HDMI Audio                                                     | 5         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 58        | 23.77%  |
| SK hynix                     | 41        | 16.8%   |
| Micron Technology            | 24        | 9.84%   |
| Crucial                      | 20        | 8.2%    |
| G.Skill                      | 19        | 7.79%   |
| Kingston                     | 14        | 5.74%   |
| Corsair                      | 14        | 5.74%   |
| Ramaxel Technology           | 9         | 3.69%   |
| Unknown                      | 7         | 2.87%   |
| Patriot                      | 7         | 2.87%   |
| A-DATA Technology            | 7         | 2.87%   |
| Team                         | 4         | 1.64%   |
| Smart                        | 3         | 1.23%   |
| Nanya Technology             | 3         | 1.23%   |
| Unknown (ABCD)               | 2         | 0.82%   |
| Timetec                      | 2         | 0.82%   |
| Elpida                       | 2         | 0.82%   |
| Transcend                    | 1         | 0.41%   |
| Patriot Memory (PDP Systems) | 1         | 0.41%   |
| GOODRAM                      | 1         | 0.41%   |
| CSX                          | 1         | 0.41%   |
| Avant                        | 1         | 0.41%   |
| Apacer                       | 1         | 0.41%   |
| 48spaces                     | 1         | 0.41%   |
| Unknown                      | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 3.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 2.28%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 2.28%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 1.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.14%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.14%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 1.14%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 3         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.76%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 2         | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.76%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.76%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s               | 2         | 0.76%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 0.76%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 0.76%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.76%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 0.76%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.76%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.76%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.76%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.76%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 140       | 66.67%  |
| DDR3    | 54        | 25.71%  |
| LPDDR4  | 8         | 3.81%   |
| LPDDR3  | 3         | 1.43%   |
| Unknown | 3         | 1.43%   |
| DDR2    | 2         | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 137       | 64.62%  |
| DIMM         | 60        | 28.3%   |
| Row Of Chips | 13        | 6.13%   |
| Chip         | 1         | 0.47%   |
| Unknown      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 122       | 52.36%  |
| 4096  | 62        | 26.61%  |
| 16384 | 39        | 16.74%  |
| 2048  | 6         | 2.58%   |
| 32768 | 3         | 1.29%   |
| 1024  | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 58        | 24.89%  |
| 1600  | 42        | 18.03%  |
| 2667  | 40        | 17.17%  |
| 2400  | 22        | 9.44%   |
| 3600  | 17        | 7.3%    |
| 2133  | 7         | 3%      |
| 3466  | 4         | 1.72%   |
| 3266  | 4         | 1.72%   |
| 2666  | 4         | 1.72%   |
| 1334  | 4         | 1.72%   |
| 4266  | 3         | 1.29%   |
| 1867  | 3         | 1.29%   |
| 1333  | 3         | 1.29%   |
| 3866  | 2         | 0.86%   |
| 3733  | 2         | 0.86%   |
| 1866  | 2         | 0.86%   |
| 1800  | 2         | 0.86%   |
| 800   | 2         | 0.86%   |
| 667   | 2         | 0.86%   |
| 8400  | 1         | 0.43%   |
| 4267  | 1         | 0.43%   |
| 4200  | 1         | 0.43%   |
| 4000  | 1         | 0.43%   |
| 3800  | 1         | 0.43%   |
| 3000  | 1         | 0.43%   |
| 2933  | 1         | 0.43%   |
| 2200  | 1         | 0.43%   |
| 1200  | 1         | 0.43%   |
| 1066  | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Dymo-CoStar         | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Kyocera             | 1         | 11.11%  |
| Fuji Xerox          | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450      | 2         | 22.22%  |
| Samsung M337x 387x 407x Series   | 1         | 11.11%  |
| Kyocera FS-1030D printer         | 1         | 11.11%  |
| HP OfficeJet Pro 8020 series     | 1         | 11.11%  |
| HP LaserJet 200 colorMFP M275nw  | 1         | 11.11%  |
| HP DeskJet Plus 4100 series      | 1         | 11.11%  |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 11.11%  |
| Brother HL-5370DW series         | 1         | 11.11%  |

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
| Chicony Electronics                    | 47        | 21.96%  |
| IMC Networks                           | 30        | 14.02%  |
| Logitech                               | 21        | 9.81%   |
| Microdia                               | 14        | 6.54%   |
| Realtek Semiconductor                  | 12        | 5.61%   |
| Acer                                   | 12        | 5.61%   |
| Sunplus Innovation Technology          | 11        | 5.14%   |
| Quanta                                 | 11        | 5.14%   |
| Syntek                                 | 7         | 3.27%   |
| Microsoft                              | 7         | 3.27%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.8%    |
| Suyin                                  | 5         | 2.34%   |
| Luxvisions Innotech Limited            | 5         | 2.34%   |
| Lite-On Technology                     | 4         | 1.87%   |
| Apple                                  | 4         | 1.87%   |
| Silicon Motion                         | 3         | 1.4%    |
| Jieli Technology                       | 2         | 0.93%   |
| Z-Star Microelectronics                | 1         | 0.47%   |
| WaveRider Communications               | 1         | 0.47%   |
| Unknown                                | 1         | 0.47%   |
| Sonix Technology                       | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| Razer USA                              | 1         | 0.47%   |
| MacroSilicon                           | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| Importek                               | 1         | 0.47%   |
| Genesys Logic                          | 1         | 0.47%   |
| GEMBIRD                                | 1         | 0.47%   |
| DJKANA19IDX53W                         | 1         | 0.47%   |
| Creative Technology                    | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 15        | 6.94%   |
| IMC Networks Integrated Camera                      | 10        | 4.63%   |
| Chicony HD WebCam                                   | 8         | 3.7%    |
| Microdia Integrated_Webcam_HD                       | 7         | 3.24%   |
| Chicony Integrated Camera                           | 7         | 3.24%   |
| Syntek Integrated Camera                            | 5         | 2.31%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.85%   |
| Logitech Webcam C270                                | 4         | 1.85%   |
| Logitech HD Pro Webcam C920                         | 4         | 1.85%   |
| Chicony HP Wide Vision HD Camera                    | 4         | 1.85%   |
| Chicony HD User Facing                              | 4         | 1.85%   |
| Acer HD Webcam                                      | 4         | 1.85%   |
| Quanta HP Wide Vision HD Camera                     | 3         | 1.39%   |
| Logitech BRIO                                       | 3         | 1.39%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 1.39%   |
| Acer Integrated Camera                              | 3         | 1.39%   |
| Silicon Motion Web Camera                           | 2         | 0.93%   |
| Realtek Integrated_Webcam_HD                        | 2         | 0.93%   |
| Realtek HD WebCam                                   | 2         | 0.93%   |
| Quanta HD User Facing                               | 2         | 0.93%   |
| Microsoft LifeCam HD-5000                           | 2         | 0.93%   |
| Microsoft LifeCam HD-3000                           | 2         | 0.93%   |
| Microdia Webcam Vitade AF                           | 2         | 0.93%   |
| Logitech Webcam C930e                               | 2         | 0.93%   |
| Logitech HD Webcam C910                             | 2         | 0.93%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 0.93%   |
| Jieli USB PHY 2.0                                   | 2         | 0.93%   |
| IMC Networks HD Camera                              | 2         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 0.93%   |
| Chicony USB2.0 Camera                               | 2         | 0.93%   |
| Chicony USB 2.0 Camera                              | 2         | 0.93%   |
| Chicony HP Truevision HD                            | 2         | 0.93%   |
| Chicony EasyCamera                                  | 2         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 0.93%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 0.46%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.46%   |
| Unknown 720p HD Camera                              | 1         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 25%     |
| Synaptics                  | 9         | 22.5%   |
| Elan Microelectronics      | 7         | 17.5%   |
| Shenzhen Goodix Technology | 6         | 15%     |
| LighTuning Technology      | 4         | 10%     |
| AuthenTec                  | 2         | 5%      |
| Samsung Electronics        | 1         | 2.5%    |
| Focal-systems.Corp         | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 4         | 10%     |
| Unknown                                                                    | 4         | 10%     |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 7.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 7.5%    |
| Elan ELAN:ARM-M4                                                           | 3         | 7.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5%      |
| Validity Sensors Synaptics WBDI                                            | 2         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 5%      |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 5%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.5%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.5%    |
| Synaptics WBDI Device                                                      | 1         | 2.5%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.5%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.5%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 2.5%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.5%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.5%    |
| AuthenTec AES2810                                                          | 1         | 2.5%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 10        | 62.5%   |
| Alcor Micro      | 2         | 12.5%   |
| Upek             | 1         | 6.25%   |
| SCM Microsystems | 1         | 6.25%   |
| O2 Micro         | 1         | 6.25%   |
| Lenovo           | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 18.75%  |
| Broadcom 5880                                                                | 3         | 18.75%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.25%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 158       | 47.59%  |
| 0     | 107       | 32.23%  |
| 2     | 56        | 16.87%  |
| 3     | 10        | 3.01%   |
| 4     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 186       | 60.78%  |
| Fingerprint reader       | 40        | 13.07%  |
| Graphics card            | 20        | 6.54%   |
| Net/wireless             | 16        | 5.23%   |
| Chipcard                 | 15        | 4.9%    |
| Net/ethernet             | 8         | 2.61%   |
| Multimedia controller    | 7         | 2.29%   |
| Camera                   | 7         | 2.29%   |
| Storage                  | 3         | 0.98%   |
| Wireless                 | 1         | 0.33%   |
| Unassigned class         | 1         | 0.33%   |
| Network                  | 1         | 0.33%   |
| Bluetooth                | 1         | 0.33%   |

