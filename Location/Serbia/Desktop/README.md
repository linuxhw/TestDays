Linux in Serbia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

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

Total: 777

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MAG B550 TOMAHAWK           | [8ae82d1a94](https://linux-hardware.org/?probe=8ae82d1a94) | Jan 03, 2026 |
| MSI           | MAG B550 TOMAHAWK           | [7a41f2433d](https://linux-hardware.org/?probe=7a41f2433d) | Jan 03, 2026 |
| ASUSTek       | PRIME A320M-K               | [a202127500](https://linux-hardware.org/?probe=a202127500) | Jan 03, 2026 |
| ASUSTek       | PRIME B360M-K               | [240414693b](https://linux-hardware.org/?probe=240414693b) | Jan 03, 2026 |
| Gigabyte      | A520M K V2                  | [6a63cf2a4a](https://linux-hardware.org/?probe=6a63cf2a4a) | Dec 25, 2025 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [ad7fdaf936](https://linux-hardware.org/?probe=ad7fdaf936) | Dec 24, 2025 |
| Dell          | 040DDP A01                  | [19a7f7f720](https://linux-hardware.org/?probe=19a7f7f720) | Dec 19, 2025 |
| MSI           | PRO A620M-B                 | [a7021339f5](https://linux-hardware.org/?probe=a7021339f5) | Dec 10, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [1ba06b803c](https://linux-hardware.org/?probe=1ba06b803c) | Dec 08, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [bf2a86b672](https://linux-hardware.org/?probe=bf2a86b672) | Dec 07, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [810fcd5291](https://linux-hardware.org/?probe=810fcd5291) | Dec 07, 2025 |
| Biostar       | A320MH                      | [a74bb24d0c](https://linux-hardware.org/?probe=a74bb24d0c) | Dec 06, 2025 |
| MSI           | X570-A PRO                  | [04f301b2a4](https://linux-hardware.org/?probe=04f301b2a4) | Dec 05, 2025 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [02419caa02](https://linux-hardware.org/?probe=02419caa02) | Nov 23, 2025 |
| Gigabyte      | A520M K V2                  | [fe5de0b7a1](https://linux-hardware.org/?probe=fe5de0b7a1) | Nov 22, 2025 |
| ASUSTek       | M4A89TD PRO USB3            | [f382111e45](https://linux-hardware.org/?probe=f382111e45) | Nov 22, 2025 |
| Gigabyte      | A520M K V2                  | [a79b0fabe7](https://linux-hardware.org/?probe=a79b0fabe7) | Nov 21, 2025 |
| Gigabyte      | GA-MA770T-UD3P              | [4544f05395](https://linux-hardware.org/?probe=4544f05395) | Nov 17, 2025 |
| ASUSTek       | PRIME A320M-K               | [5c4b92ca28](https://linux-hardware.org/?probe=5c4b92ca28) | Nov 06, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [570ced0ee1](https://linux-hardware.org/?probe=570ced0ee1) | Nov 05, 2025 |
| Gigabyte      | 970A-DS3P                   | [5e8311413c](https://linux-hardware.org/?probe=5e8311413c) | Nov 01, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [6f79f5a202](https://linux-hardware.org/?probe=6f79f5a202) | Nov 01, 2025 |
| Gigabyte      | A520M K V2                  | [2411bfde61](https://linux-hardware.org/?probe=2411bfde61) | Oct 31, 2025 |
| Gigabyte      | A520M K V2                  | [a976f77803](https://linux-hardware.org/?probe=a976f77803) | Oct 31, 2025 |
| Gigabyte      | P55-UD3L                    | [270a1fbb73](https://linux-hardware.org/?probe=270a1fbb73) | Oct 26, 2025 |
| ASUSTek       | PRIME X299-A                | [b587ee1ade](https://linux-hardware.org/?probe=b587ee1ade) | Oct 24, 2025 |
| HP            | 3047h                       | [803e9d9f32](https://linux-hardware.org/?probe=803e9d9f32) | Oct 20, 2025 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | [e0a766d68e](https://linux-hardware.org/?probe=e0a766d68e) | Oct 16, 2025 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | [3bd9b95b4c](https://linux-hardware.org/?probe=3bd9b95b4c) | Oct 16, 2025 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [85db833299](https://linux-hardware.org/?probe=85db833299) | Oct 12, 2025 |
| Gigabyte      | H61M-S2PV                   | [22991cb906](https://linux-hardware.org/?probe=22991cb906) | Oct 06, 2025 |
| Gigabyte      | H61M-S2PV                   | [69417b2c40](https://linux-hardware.org/?probe=69417b2c40) | Oct 06, 2025 |
| MSI           | G41M-P23                    | [ef935d9e4d](https://linux-hardware.org/?probe=ef935d9e4d) | Oct 03, 2025 |
| MSI           | X570-A PRO                  | [f68ab931ce](https://linux-hardware.org/?probe=f68ab931ce) | Oct 03, 2025 |
| MSI           | B450M BAZOOKA MAX WIFI      | [6807cd8456](https://linux-hardware.org/?probe=6807cd8456) | Oct 03, 2025 |
| MSI           | G41M-P23                    | [26f65abd84](https://linux-hardware.org/?probe=26f65abd84) | Sep 23, 2025 |
| Biostar       | A32M2                       | [a36156c315](https://linux-hardware.org/?probe=a36156c315) | Sep 22, 2025 |
| Gigabyte      | 970A-DS3P                   | [7d186dde36](https://linux-hardware.org/?probe=7d186dde36) | Sep 22, 2025 |
| ASUSTek       | PRIME Z590-P                | [2fed1aaaee](https://linux-hardware.org/?probe=2fed1aaaee) | Sep 22, 2025 |
| ASRock        | A520M-HVS                   | [cae4821288](https://linux-hardware.org/?probe=cae4821288) | Sep 16, 2025 |
| Gigabyte      | A520M K V2                  | [4ef7b60bdb](https://linux-hardware.org/?probe=4ef7b60bdb) | Sep 16, 2025 |
| ASRock        | B450 Pro4                   | [404d9b19d5](https://linux-hardware.org/?probe=404d9b19d5) | Sep 14, 2025 |
| Gigabyte      | 970A-DS3P                   | [a8c1f85116](https://linux-hardware.org/?probe=a8c1f85116) | Sep 10, 2025 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | [95ac54b38e](https://linux-hardware.org/?probe=95ac54b38e) | Sep 08, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [88cc856d53](https://linux-hardware.org/?probe=88cc856d53) | Sep 08, 2025 |
| Gigabyte      | A520M K V2                  | [42125e3b26](https://linux-hardware.org/?probe=42125e3b26) | Sep 04, 2025 |
| MSI           | G41M-P23                    | [dd16dd0207](https://linux-hardware.org/?probe=dd16dd0207) | Sep 01, 2025 |
| MSI           | G41M-P23                    | [147762c09b](https://linux-hardware.org/?probe=147762c09b) | Aug 25, 2025 |
| MSI           | 970 GAMING                  | [11aa9e5ac1](https://linux-hardware.org/?probe=11aa9e5ac1) | Aug 21, 2025 |
| ASUSTek       | M5A78L-M LX3                | [84dbbd366f](https://linux-hardware.org/?probe=84dbbd366f) | Aug 10, 2025 |
| ASRock        | B450M-HDV R4.0              | [1deba8e5c6](https://linux-hardware.org/?probe=1deba8e5c6) | Jul 31, 2025 |
| GMKtec        | NucBox K6                   | [db6090e269](https://linux-hardware.org/?probe=db6090e269) | Jul 28, 2025 |
| Lenovo        | ThinkCentre M81 5049D7G     | [f68a03b430](https://linux-hardware.org/?probe=f68a03b430) | Jul 21, 2025 |
| MSI           | MS-7369                     | [101559a840](https://linux-hardware.org/?probe=101559a840) | Jul 21, 2025 |
| HP            | 8876 11                     | [25f187c55e](https://linux-hardware.org/?probe=25f187c55e) | Jul 21, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f33811f1e0](https://linux-hardware.org/?probe=f33811f1e0) | Jul 21, 2025 |
| ASUSTek       | TUF Gaming B550M-E          | [2f899494da](https://linux-hardware.org/?probe=2f899494da) | Jul 19, 2025 |
| ASUSTek       | PRIME A320M-K               | [de98f68147](https://linux-hardware.org/?probe=de98f68147) | Jul 18, 2025 |
| ASUSTek       | TUF Gaming B550M-E          | [f85283eb56](https://linux-hardware.org/?probe=f85283eb56) | Jul 18, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [da0812321b](https://linux-hardware.org/?probe=da0812321b) | Jul 15, 2025 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d33f4f2308](https://linux-hardware.org/?probe=d33f4f2308) | Jul 12, 2025 |
| Gigabyte      | B650M GAMING X AX           | [9935d9bd79](https://linux-hardware.org/?probe=9935d9bd79) | Jul 10, 2025 |
| ASRock        | H510M-HDV/M.2 SE            | [7bde003bf5](https://linux-hardware.org/?probe=7bde003bf5) | Jul 09, 2025 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [e3c38a64dd](https://linux-hardware.org/?probe=e3c38a64dd) | Jul 07, 2025 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [fdb4281629](https://linux-hardware.org/?probe=fdb4281629) | Jul 04, 2025 |
| Gigabyte      | B650M AORUS ELITE AX        | [868ba7a6bd](https://linux-hardware.org/?probe=868ba7a6bd) | Jul 01, 2025 |
| Gigabyte      | X870E AORUS XTREME AI TO... | [044594ef18](https://linux-hardware.org/?probe=044594ef18) | Jun 28, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [40e49873de](https://linux-hardware.org/?probe=40e49873de) | Jun 25, 2025 |
| Gigabyte      | B560M H                     | [2e437e2c3d](https://linux-hardware.org/?probe=2e437e2c3d) | Jun 14, 2025 |
| Alienware     | 0VDT73 A00                  | [60ba2df3ea](https://linux-hardware.org/?probe=60ba2df3ea) | Jun 13, 2025 |
| ASRock        | B650M Pro RS                | [84328a5747](https://linux-hardware.org/?probe=84328a5747) | Jun 04, 2025 |
| Gigabyte      | B550 AORUS PRO AC           | [ec03624f11](https://linux-hardware.org/?probe=ec03624f11) | May 30, 2025 |
| ASUSTek       | H81M-R                      | [40ce4669c4](https://linux-hardware.org/?probe=40ce4669c4) | May 12, 2025 |
| ASUSTek       | PRIME A520M-K               | [22d312b398](https://linux-hardware.org/?probe=22d312b398) | May 09, 2025 |
| ASRock        | A320M-DGS                   | [37831c5591](https://linux-hardware.org/?probe=37831c5591) | May 08, 2025 |
| MSI           | B450M PRO-VDH PLUS          | [5c0e6cfa15](https://linux-hardware.org/?probe=5c0e6cfa15) | May 07, 2025 |
| HP            | 18E5                        | [c736cbc8e9](https://linux-hardware.org/?probe=c736cbc8e9) | Apr 30, 2025 |
| ASUSTek       | P5K PRO                     | [6261bed97c](https://linux-hardware.org/?probe=6261bed97c) | Apr 28, 2025 |
| ASUSTek       | PRIME B550M-K ARGB          | [9b2d8d26e8](https://linux-hardware.org/?probe=9b2d8d26e8) | Apr 27, 2025 |
| Gigabyte      | B450M S2H                   | [2f8863eb81](https://linux-hardware.org/?probe=2f8863eb81) | Apr 27, 2025 |
| Gigabyte      | Z170-D3H-CF                 | [937c1b0b4f](https://linux-hardware.org/?probe=937c1b0b4f) | Apr 20, 2025 |
| ASRock        | B450 Gaming K4              | [a5c093e256](https://linux-hardware.org/?probe=a5c093e256) | Apr 10, 2025 |
| MSI           | C847MS-E33                  | [46cd07a997](https://linux-hardware.org/?probe=46cd07a997) | Apr 07, 2025 |
| Gigabyte      | A520I AC                    | [2f84124859](https://linux-hardware.org/?probe=2f84124859) | Apr 07, 2025 |
| Gigabyte      | Z97X-Gaming 3               | [79ff36bf59](https://linux-hardware.org/?probe=79ff36bf59) | Apr 06, 2025 |
| MSI           | B450 TOMAHAWK MAX           | [fccb44b1a4](https://linux-hardware.org/?probe=fccb44b1a4) | Mar 31, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [3152745e0c](https://linux-hardware.org/?probe=3152745e0c) | Mar 28, 2025 |
| ASUSTek       | A55BM-K                     | [4aa3fc7e2b](https://linux-hardware.org/?probe=4aa3fc7e2b) | Mar 27, 2025 |
| ASRock        | A520M-HVS                   | [cfcf828918](https://linux-hardware.org/?probe=cfcf828918) | Mar 26, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [7e550e8391](https://linux-hardware.org/?probe=7e550e8391) | Mar 24, 2025 |
| ASUSTek       | H81M-K                      | [d4b535e26e](https://linux-hardware.org/?probe=d4b535e26e) | Mar 14, 2025 |
| Gigabyte      | P61-S3-B3                   | [bd438c67b1](https://linux-hardware.org/?probe=bd438c67b1) | Mar 14, 2025 |
| ASUSTek       | AM1M-A                      | [172821f926](https://linux-hardware.org/?probe=172821f926) | Mar 14, 2025 |
| Gigabyte      | 970A-DS3P                   | [b3efa14e34](https://linux-hardware.org/?probe=b3efa14e34) | Mar 13, 2025 |
| Techvision    | TVI7309X B0                 | [8db6e99e2d](https://linux-hardware.org/?probe=8db6e99e2d) | Mar 05, 2025 |
| LattePanda    | 3 Delta LP-BS-7-S70JR200... | [431bcafcec](https://linux-hardware.org/?probe=431bcafcec) | Mar 05, 2025 |
| ASUSTek       | ProArt B550-CREATOR         | [0b9668b151](https://linux-hardware.org/?probe=0b9668b151) | Mar 05, 2025 |
| ASUSTek       | ProArt B550-CREATOR         | [c13e4e967b](https://linux-hardware.org/?probe=c13e4e967b) | Mar 05, 2025 |
| LattePanda    | 3 Delta LP-BS-7-S70JR200... | [21305dabd1](https://linux-hardware.org/?probe=21305dabd1) | Feb 20, 2025 |
| Dell          | 0D24M8 A01                  | [c6a8cebbaa](https://linux-hardware.org/?probe=c6a8cebbaa) | Feb 18, 2025 |
| Dell          | 0D24M8 A01                  | [b42e74427c](https://linux-hardware.org/?probe=b42e74427c) | Feb 18, 2025 |
| ASRock        | B650 PG Lightning           | [784766b416](https://linux-hardware.org/?probe=784766b416) | Feb 17, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [5affcd0d4d](https://linux-hardware.org/?probe=5affcd0d4d) | Feb 04, 2025 |
| ASRock        | A520M-HVS                   | [9319f87279](https://linux-hardware.org/?probe=9319f87279) | Feb 04, 2025 |
| ASUSTek       | AM1M-A                      | [5656890cf9](https://linux-hardware.org/?probe=5656890cf9) | Feb 02, 2025 |
| ASUSTek       | AM1M-A                      | [18899f774f](https://linux-hardware.org/?probe=18899f774f) | Feb 02, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [4a3c2707ef](https://linux-hardware.org/?probe=4a3c2707ef) | Feb 01, 2025 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [6cdf3062d3](https://linux-hardware.org/?probe=6cdf3062d3) | Jan 31, 2025 |
| Gigabyte      | B450M DS3H-CF               | [dc86672f8e](https://linux-hardware.org/?probe=dc86672f8e) | Jan 30, 2025 |
| ASUSTek       | A55BM-K                     | [4e65923ff3](https://linux-hardware.org/?probe=4e65923ff3) | Jan 27, 2025 |
| Lenovo        | H420                        | [09594b0e4e](https://linux-hardware.org/?probe=09594b0e4e) | Jan 25, 2025 |
| ASRock        | B450 Pro4                   | [f355dd7eac](https://linux-hardware.org/?probe=f355dd7eac) | Jan 24, 2025 |
| Gigabyte      | B760 GAMING X DDR4          | [84f8adf577](https://linux-hardware.org/?probe=84f8adf577) | Jan 23, 2025 |
| Gigabyte      | A520M K V2                  | [f8d949489b](https://linux-hardware.org/?probe=f8d949489b) | Jan 23, 2025 |
| Gigabyte      | B450M DS3H-CF               | [6240db0196](https://linux-hardware.org/?probe=6240db0196) | Jan 20, 2025 |
| ASUSTek       | ProArt B760-CREATOR         | [ab8f335bfa](https://linux-hardware.org/?probe=ab8f335bfa) | Jan 20, 2025 |
| MSI           | X370 GAMING PRO             | [41c1ed2419](https://linux-hardware.org/?probe=41c1ed2419) | Jan 19, 2025 |
| Gigabyte      | B450 AORUS PRO-CF           | [5bd7bc7466](https://linux-hardware.org/?probe=5bd7bc7466) | Jan 12, 2025 |
| ASUSTek       | PRIME A320M-K               | [90cd9b97ea](https://linux-hardware.org/?probe=90cd9b97ea) | Jan 11, 2025 |
| MSI           | B450M-A PRO MAX II          | [3461c8acc3](https://linux-hardware.org/?probe=3461c8acc3) | Jan 09, 2025 |
| Biostar       | TA970 Plus                  | [afb51cfe18](https://linux-hardware.org/?probe=afb51cfe18) | Jan 06, 2025 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [b2b5aa8eec](https://linux-hardware.org/?probe=b2b5aa8eec) | Jan 05, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | [315981955a](https://linux-hardware.org/?probe=315981955a) | Jan 03, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | [118b96c4df](https://linux-hardware.org/?probe=118b96c4df) | Jan 03, 2025 |
| Gigabyte      | H61M-S2PV                   | [58be9bacfd](https://linux-hardware.org/?probe=58be9bacfd) | Dec 29, 2024 |
| Lenovo        | ThinkCentre M81 5049D7G     | [2434fa6399](https://linux-hardware.org/?probe=2434fa6399) | Dec 27, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | [049870e2b4](https://linux-hardware.org/?probe=049870e2b4) | Dec 26, 2024 |
| HP            | 3396                        | [c26082be18](https://linux-hardware.org/?probe=c26082be18) | Dec 23, 2024 |
| HP            | 3396                        | [a2eda9a830](https://linux-hardware.org/?probe=a2eda9a830) | Dec 23, 2024 |
| ASRock        | N68-GS4 FX                  | [e21e961747](https://linux-hardware.org/?probe=e21e961747) | Dec 22, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [54970d3023](https://linux-hardware.org/?probe=54970d3023) | Dec 20, 2024 |
| Gigabyte      | H81M-S                      | [68e2f55258](https://linux-hardware.org/?probe=68e2f55258) | Dec 13, 2024 |
| Huanan        | X99-TF                      | [8fd5cc725c](https://linux-hardware.org/?probe=8fd5cc725c) | Dec 10, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [f3e2067835](https://linux-hardware.org/?probe=f3e2067835) | Dec 10, 2024 |
| MSI           | G41M-P28                    | [1b74dfddb0](https://linux-hardware.org/?probe=1b74dfddb0) | Dec 04, 2024 |
| MSI           | G41M-P28                    | [971098953a](https://linux-hardware.org/?probe=971098953a) | Dec 02, 2024 |
| ASUSTek       | PRIME Z590-P                | [2e9144632c](https://linux-hardware.org/?probe=2e9144632c) | Dec 02, 2024 |
| MSI           | 770-C45                     | [02a86ec1fe](https://linux-hardware.org/?probe=02a86ec1fe) | Nov 29, 2024 |
| ASUSTek       | PRIME Z590-P                | [5b66a14834](https://linux-hardware.org/?probe=5b66a14834) | Nov 20, 2024 |
| Acer          | Veriton S6610G              | [07703559d2](https://linux-hardware.org/?probe=07703559d2) | Nov 18, 2024 |
| MSI           | G41M-P28                    | [6883386504](https://linux-hardware.org/?probe=6883386504) | Nov 15, 2024 |
| MSI           | G41M-P28                    | [e0db0a9627](https://linux-hardware.org/?probe=e0db0a9627) | Nov 09, 2024 |
| Gigabyte      | Z97X-Gaming 3               | [2cb55cd612](https://linux-hardware.org/?probe=2cb55cd612) | Nov 09, 2024 |
| Gigabyte      | Z97X-Gaming 3               | [6fd033b535](https://linux-hardware.org/?probe=6fd033b535) | Nov 09, 2024 |
| ASRock        | B450M-HDV R4.0              | [05a19e97e0](https://linux-hardware.org/?probe=05a19e97e0) | Nov 07, 2024 |
| ASUSTek       | P5Q SE2                     | [9a4a8316c4](https://linux-hardware.org/?probe=9a4a8316c4) | Nov 05, 2024 |
| Dell          | 0F6X5P A00                  | [7277892ee3](https://linux-hardware.org/?probe=7277892ee3) | Nov 03, 2024 |
| Dell          | 0F6X5P A00                  | [009ebdabc7](https://linux-hardware.org/?probe=009ebdabc7) | Nov 03, 2024 |
| Gigabyte      | Z68P-DS3                    | [27bd6c0cf8](https://linux-hardware.org/?probe=27bd6c0cf8) | Nov 03, 2024 |
| Medion        | MS-7366                     | [0fe38a33d1](https://linux-hardware.org/?probe=0fe38a33d1) | Oct 31, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [6027aa7a82](https://linux-hardware.org/?probe=6027aa7a82) | Oct 29, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [0846a29ce4](https://linux-hardware.org/?probe=0846a29ce4) | Oct 29, 2024 |
| Medion        | MS-7366                     | [786514f25e](https://linux-hardware.org/?probe=786514f25e) | Oct 27, 2024 |
| ASUSTek       | PRIME A320M-K               | [dd1a2d866e](https://linux-hardware.org/?probe=dd1a2d866e) | Oct 19, 2024 |
| ASUSTek       | PRIME A320M-K               | [d167d5b4b6](https://linux-hardware.org/?probe=d167d5b4b6) | Oct 19, 2024 |
| HP            | 802F                        | [5553cbd4ca](https://linux-hardware.org/?probe=5553cbd4ca) | Oct 17, 2024 |
| Micro Comp... | HX100G                      | [2e97a25812](https://linux-hardware.org/?probe=2e97a25812) | Oct 11, 2024 |
| Huanan        | X99-F8                      | [619b6f5845](https://linux-hardware.org/?probe=619b6f5845) | Oct 02, 2024 |
| Gigabyte      | H110M-S2-CF                 | [458b6c459d](https://linux-hardware.org/?probe=458b6c459d) | Sep 29, 2024 |
| Gigabyte      | H110M-S2-CF                 | [a44ff28e8a](https://linux-hardware.org/?probe=a44ff28e8a) | Sep 29, 2024 |
| Medion        | MS-7366                     | [d3f9e281e9](https://linux-hardware.org/?probe=d3f9e281e9) | Sep 23, 2024 |
| Gigabyte      | H110-D3A-CF                 | [dd3a3a163e](https://linux-hardware.org/?probe=dd3a3a163e) | Sep 22, 2024 |
| MACHINIST     | X99-RS9 V1.11               | [845631b912](https://linux-hardware.org/?probe=845631b912) | Sep 17, 2024 |
| Acer          | Aspire M3970                | [5c1577174f](https://linux-hardware.org/?probe=5c1577174f) | Sep 06, 2024 |
| HP            | 802F                        | [7c43df09f7](https://linux-hardware.org/?probe=7c43df09f7) | Sep 02, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [099d384a90](https://linux-hardware.org/?probe=099d384a90) | Aug 22, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [1dbcd28c43](https://linux-hardware.org/?probe=1dbcd28c43) | Aug 20, 2024 |
| Biostar       | TA970 Plus                  | [377448fd65](https://linux-hardware.org/?probe=377448fd65) | Aug 18, 2024 |
| Biostar       | TA970 Plus                  | [acb6724986](https://linux-hardware.org/?probe=acb6724986) | Aug 18, 2024 |
| ASUSTek       | PRIME B360M-K               | [404b2b9643](https://linux-hardware.org/?probe=404b2b9643) | Aug 11, 2024 |
| ASUSTek       | A88X-PRO                    | [f21a622ef1](https://linux-hardware.org/?probe=f21a622ef1) | Aug 08, 2024 |
| ASRock        | B650M-HDV/M.2               | [c7526a6b65](https://linux-hardware.org/?probe=c7526a6b65) | Aug 06, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | [6436b82f92](https://linux-hardware.org/?probe=6436b82f92) | Aug 03, 2024 |
| Biostar       | TA970 Plus                  | [b9ca2cb935](https://linux-hardware.org/?probe=b9ca2cb935) | Aug 02, 2024 |
| ASUSTek       | PRIME Z590-P                | [caf4309fbe](https://linux-hardware.org/?probe=caf4309fbe) | Aug 02, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [0208f0ca86](https://linux-hardware.org/?probe=0208f0ca86) | Aug 01, 2024 |
| ASUSTek       | PRIME B360M-K               | [d64109dd83](https://linux-hardware.org/?probe=d64109dd83) | Jul 27, 2024 |
| ASUSTek       | PRIME B350M-A               | [7eca7458ea](https://linux-hardware.org/?probe=7eca7458ea) | Jul 26, 2024 |
| Dell          | 0XPDFK A01                  | [dd90b71690](https://linux-hardware.org/?probe=dd90b71690) | Jul 23, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | [b392840045](https://linux-hardware.org/?probe=b392840045) | Jul 22, 2024 |
| Lenovo        | 312A NOK                    | [3f3e891da0](https://linux-hardware.org/?probe=3f3e891da0) | Jul 22, 2024 |
| MSI           | GF615M-P33 V2               | [1fdecde171](https://linux-hardware.org/?probe=1fdecde171) | Jul 19, 2024 |
| Gigabyte      | X570 AORUS PRO              | [04b16c05af](https://linux-hardware.org/?probe=04b16c05af) | Jul 09, 2024 |
| ASUSTek       | A58M-E                      | [fd43969147](https://linux-hardware.org/?probe=fd43969147) | Jul 08, 2024 |
| ASUSTek       | PRIME A320M-K               | [32be2b30f2](https://linux-hardware.org/?probe=32be2b30f2) | Jul 05, 2024 |
| MSI           | H81M-P33                    | [51486f85b1](https://linux-hardware.org/?probe=51486f85b1) | Jul 04, 2024 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [8fefff6140](https://linux-hardware.org/?probe=8fefff6140) | Jul 03, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [86f612102d](https://linux-hardware.org/?probe=86f612102d) | Jun 19, 2024 |
| ASUSTek       | PRIME A320M-K               | [5f188d375a](https://linux-hardware.org/?probe=5f188d375a) | Jun 14, 2024 |
| ASUSTek       | PRIME A320M-K               | [172e6fc98d](https://linux-hardware.org/?probe=172e6fc98d) | Jun 14, 2024 |
| ASUSTek       | PRIME B360M-K               | [765ca44aab](https://linux-hardware.org/?probe=765ca44aab) | Jun 09, 2024 |
| MSI           | H61M-P20                    | [4577901498](https://linux-hardware.org/?probe=4577901498) | May 31, 2024 |
| HP            | 8918                        | [1004c84bae](https://linux-hardware.org/?probe=1004c84bae) | May 30, 2024 |
| Dell          | 0DR845                      | [a1c98b014b](https://linux-hardware.org/?probe=a1c98b014b) | May 28, 2024 |
| Dell          | 0PJDGF A02                  | [51a5de7770](https://linux-hardware.org/?probe=51a5de7770) | May 26, 2024 |
| Dell          | 05XGC8 A01                  | [4b62db7f29](https://linux-hardware.org/?probe=4b62db7f29) | May 21, 2024 |
| Gigabyte      | M61PME-S2                   | [e84ce47888](https://linux-hardware.org/?probe=e84ce47888) | May 20, 2024 |
| Dell          | 0M5DCD A00                  | [79c4c910aa](https://linux-hardware.org/?probe=79c4c910aa) | May 16, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [c7cb63d9fb](https://linux-hardware.org/?probe=c7cb63d9fb) | May 12, 2024 |
| Medion        | MS-7366                     | [0c36270a48](https://linux-hardware.org/?probe=0c36270a48) | May 06, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [e5f565474a](https://linux-hardware.org/?probe=e5f565474a) | May 05, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | [32ad893888](https://linux-hardware.org/?probe=32ad893888) | May 02, 2024 |
| ASUSTek       | M4A89GTD-PRO                | [d40738eda7](https://linux-hardware.org/?probe=d40738eda7) | Apr 28, 2024 |
| Fujitsu       | D3167-A1 S26361-D3167-A1    | [5182ad8bd7](https://linux-hardware.org/?probe=5182ad8bd7) | Apr 27, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [11d418a07c](https://linux-hardware.org/?probe=11d418a07c) | Apr 22, 2024 |
| ASRock        | H81 Pro BTC                 | [93fdc2cae0](https://linux-hardware.org/?probe=93fdc2cae0) | Apr 22, 2024 |
| ASUSTek       | PRIME B360M-K               | [2231063264](https://linux-hardware.org/?probe=2231063264) | Apr 19, 2024 |
| ASUSTek       | PRIME B360M-K               | [aeef377b48](https://linux-hardware.org/?probe=aeef377b48) | Apr 19, 2024 |
| ASUSTek       | PRIME Z270-P                | [aaed2b7478](https://linux-hardware.org/?probe=aaed2b7478) | Apr 14, 2024 |
| Dell          | 0YC9KY A00                  | [d97e9bda3d](https://linux-hardware.org/?probe=d97e9bda3d) | Apr 12, 2024 |
| Dell          | 0YC9KY A00                  | [250b239ec8](https://linux-hardware.org/?probe=250b239ec8) | Apr 12, 2024 |
| ASUSTek       | PRIME A320M-K               | [17dac6592c](https://linux-hardware.org/?probe=17dac6592c) | Apr 06, 2024 |
| ASUSTek       | PRIME A320M-K               | [7238741c32](https://linux-hardware.org/?probe=7238741c32) | Apr 05, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [6d4eaf0bc7](https://linux-hardware.org/?probe=6d4eaf0bc7) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [0bd97f775d](https://linux-hardware.org/?probe=0bd97f775d) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [d952efad38](https://linux-hardware.org/?probe=d952efad38) | Apr 01, 2024 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [fd422008e5](https://linux-hardware.org/?probe=fd422008e5) | Mar 26, 2024 |
| ASUSTek       | PRIME A320M-K               | [052a56e30a](https://linux-hardware.org/?probe=052a56e30a) | Mar 23, 2024 |
| ASUSTek       | PRIME Z590-P                | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| ASUSTek       | PRIME Z270-P                | [12f62966ac](https://linux-hardware.org/?probe=12f62966ac) | Mar 19, 2024 |
| Gigabyte      | B550M DS3H                  | [d61cccde04](https://linux-hardware.org/?probe=d61cccde04) | Mar 17, 2024 |
| Gigabyte      | B550M DS3H                  | [aeb84570e9](https://linux-hardware.org/?probe=aeb84570e9) | Mar 17, 2024 |
| MSI           | B75MA-E33                   | [ef665444e1](https://linux-hardware.org/?probe=ef665444e1) | Mar 07, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | [5e2bacbc0c](https://linux-hardware.org/?probe=5e2bacbc0c) | Mar 02, 2024 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [ae1b4fe578](https://linux-hardware.org/?probe=ae1b4fe578) | Feb 28, 2024 |
| ASUSTek       | PRIME B250M-K               | [01587cc1ed](https://linux-hardware.org/?probe=01587cc1ed) | Feb 24, 2024 |
| Gigabyte      | Z390 UD                     | [81ce4601b2](https://linux-hardware.org/?probe=81ce4601b2) | Feb 21, 2024 |
| ASUSTek       | PRIME Z270-P                | [03c4445d03](https://linux-hardware.org/?probe=03c4445d03) | Feb 20, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [1c432f8df1](https://linux-hardware.org/?probe=1c432f8df1) | Feb 11, 2024 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [b8338080c9](https://linux-hardware.org/?probe=b8338080c9) | Feb 08, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [a0c3cd5ffd](https://linux-hardware.org/?probe=a0c3cd5ffd) | Feb 04, 2024 |
| Huanan        | X99-8M-F V1.4               | [7625188b91](https://linux-hardware.org/?probe=7625188b91) | Jan 31, 2024 |
| MSI           | 970A-G46                    | [9a7594f5ae](https://linux-hardware.org/?probe=9a7594f5ae) | Jan 29, 2024 |
| Gigabyte      | GA-MA770T-UD3P              | [13d6b2dc0a](https://linux-hardware.org/?probe=13d6b2dc0a) | Jan 27, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [f17f689f78](https://linux-hardware.org/?probe=f17f689f78) | Jan 27, 2024 |
| Huanan        | X99-8M-F V1.4               | [65388b76e1](https://linux-hardware.org/?probe=65388b76e1) | Jan 25, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [8d46c388c2](https://linux-hardware.org/?probe=8d46c388c2) | Jan 22, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [c5f32d31a4](https://linux-hardware.org/?probe=c5f32d31a4) | Jan 06, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [9867b126a0](https://linux-hardware.org/?probe=9867b126a0) | Jan 05, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [84614ee22e](https://linux-hardware.org/?probe=84614ee22e) | Dec 28, 2023 |
| MSI           | B450M PRO-M2                | [5b0afba8bf](https://linux-hardware.org/?probe=5b0afba8bf) | Dec 27, 2023 |
| Gigabyte      | Z170-HD3-CF                 | [99e618d817](https://linux-hardware.org/?probe=99e618d817) | Dec 26, 2023 |
| Dell          | 0XPDFK A01                  | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9362181823](https://linux-hardware.org/?probe=9362181823) | Dec 14, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [f2efee9279](https://linux-hardware.org/?probe=f2efee9279) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [0e23ff0a06](https://linux-hardware.org/?probe=0e23ff0a06) | Dec 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [ec3c3d632c](https://linux-hardware.org/?probe=ec3c3d632c) | Dec 11, 2023 |
| MSI           | MS-7309                     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | [73890cb8c3](https://linux-hardware.org/?probe=73890cb8c3) | Dec 05, 2023 |
| Dell          | 0XPDFK A01                  | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| ASRock        | B450M-HDV                   | [d59279f095](https://linux-hardware.org/?probe=d59279f095) | Dec 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | [53fc7f6723](https://linux-hardware.org/?probe=53fc7f6723) | Nov 30, 2023 |
| Medion        | MS-7621                     | [18f32a871d](https://linux-hardware.org/?probe=18f32a871d) | Nov 28, 2023 |
| MSI           | B450M PRO-M2                | [aa2febcb00](https://linux-hardware.org/?probe=aa2febcb00) | Nov 25, 2023 |
| Gigabyte      | H77N-WIFI                   | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| MSI           | B450M-A PRO MAX             | [d300ce9afc](https://linux-hardware.org/?probe=d300ce9afc) | Nov 19, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cdc5e8d8dc](https://linux-hardware.org/?probe=cdc5e8d8dc) | Nov 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b740ed00c5](https://linux-hardware.org/?probe=b740ed00c5) | Nov 15, 2023 |
| ASUSTek       | AM1M-A                      | [4029b9094e](https://linux-hardware.org/?probe=4029b9094e) | Nov 15, 2023 |
| Gigabyte      | Z390 UD                     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [8f08acd434](https://linux-hardware.org/?probe=8f08acd434) | Nov 12, 2023 |
| ASUSTek       | M5A87                       | [40a4f6c6f0](https://linux-hardware.org/?probe=40a4f6c6f0) | Nov 11, 2023 |
| Gigabyte      | A320M-H-CF                  | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| ASRock        | B450 Pro4 R2.0              | [c950f24711](https://linux-hardware.org/?probe=c950f24711) | Nov 01, 2023 |
| Gigabyte      | B450M H                     | [102b9b2a5b](https://linux-hardware.org/?probe=102b9b2a5b) | Oct 25, 2023 |
| ASUSTek       | A68HM-K                     | [d8abffeee6](https://linux-hardware.org/?probe=d8abffeee6) | Oct 18, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | [c593fd76c4](https://linux-hardware.org/?probe=c593fd76c4) | Oct 16, 2023 |
| ASUSTek       | PRIME B450M-K               | [89b9e4e457](https://linux-hardware.org/?probe=89b9e4e457) | Oct 10, 2023 |
| MSI           | A320M-A PRO MAX             | [21bc791bbd](https://linux-hardware.org/?probe=21bc791bbd) | Oct 10, 2023 |
| ASUSTek       | B85-PRO GAMER               | [10baa7a046](https://linux-hardware.org/?probe=10baa7a046) | Oct 06, 2023 |
| Lenovo        | ThinkCentre M57 6075Y3W     | [8e39080ed3](https://linux-hardware.org/?probe=8e39080ed3) | Sep 28, 2023 |
| Gigabyte      | EX58-UD5                    | [060deb4c88](https://linux-hardware.org/?probe=060deb4c88) | Sep 26, 2023 |
| ASRock        | X370 Pro4                   | [1939307392](https://linux-hardware.org/?probe=1939307392) | Sep 25, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [1752297c85](https://linux-hardware.org/?probe=1752297c85) | Sep 22, 2023 |
| Biostar       | A68N-2100                   | [c035c2e73b](https://linux-hardware.org/?probe=c035c2e73b) | Sep 22, 2023 |
| Gigabyte      | H61M-D2-B3                  | [d8f04cd109](https://linux-hardware.org/?probe=d8f04cd109) | Sep 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [04d60f1b2d](https://linux-hardware.org/?probe=04d60f1b2d) | Sep 06, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [d66af7c01e](https://linux-hardware.org/?probe=d66af7c01e) | Sep 05, 2023 |
| ASRock        | B450M-HDV R4.0              | [b87e106b6b](https://linux-hardware.org/?probe=b87e106b6b) | Sep 04, 2023 |
| HP            | 1497                        | [32a8075d02](https://linux-hardware.org/?probe=32a8075d02) | Aug 25, 2023 |
| Lenovo        | 312A NOK                    | [88533268cf](https://linux-hardware.org/?probe=88533268cf) | Aug 23, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| ASUSTek       | PRIME Z270-P                | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| ASUSTek       | PRIME Z590-P                | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| HP            | 8918                        | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| ASUSTek       | H81M-R                      | [12561e59a4](https://linux-hardware.org/?probe=12561e59a4) | Jul 07, 2023 |
| ASUSTek       | H81M-R                      | [48526cd359](https://linux-hardware.org/?probe=48526cd359) | Jul 07, 2023 |
| Gigabyte      | H61M-S1                     | [b6be2d7f9f](https://linux-hardware.org/?probe=b6be2d7f9f) | Jun 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [ec846958c9](https://linux-hardware.org/?probe=ec846958c9) | Jun 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [310342d290](https://linux-hardware.org/?probe=310342d290) | Jun 30, 2023 |
| Gigabyte      | X79-UP4                     | [c269ef3dd7](https://linux-hardware.org/?probe=c269ef3dd7) | Jun 24, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| Gigabyte      | H77-D3H                     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [eeb6dfe9be](https://linux-hardware.org/?probe=eeb6dfe9be) | Jun 18, 2023 |
| ASRock        | A320M-HDV R4.0              | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Gigabyte      | B450M DS3H V2               | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| ASUSTek       | M5A99X EVO                  | [45094360f2](https://linux-hardware.org/?probe=45094360f2) | Jun 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [57fcd66521](https://linux-hardware.org/?probe=57fcd66521) | Jun 11, 2023 |
| Dell          | 0D883F A06                  | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| Acer          | Predator G3600              | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| ASRock        | A320M-HDV R4.0              | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Gigabyte      | X79-UP4                     | [e3fd506f5e](https://linux-hardware.org/?probe=e3fd506f5e) | Jun 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| Gigabyte      | Z97-HD3                     | [8505864d45](https://linux-hardware.org/?probe=8505864d45) | May 30, 2023 |
| ASUSTek       | A88X-PRO                    | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| Intel         | DG31PR AAD97573-302         | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| Gigabyte      | F2A55M-S1                   | [59ede76205](https://linux-hardware.org/?probe=59ede76205) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | [a5c1b4eecd](https://linux-hardware.org/?probe=a5c1b4eecd) | May 22, 2023 |
| Acer          | Aspire XC-705               | [bdd393edd7](https://linux-hardware.org/?probe=bdd393edd7) | May 21, 2023 |
| ASUSTek       | PRIME Z270-P                | [e826ca7941](https://linux-hardware.org/?probe=e826ca7941) | May 11, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [b1fb1bdecf](https://linux-hardware.org/?probe=b1fb1bdecf) | May 06, 2023 |
| ASUSTek       | A88X-PRO                    | [faabff7b74](https://linux-hardware.org/?probe=faabff7b74) | May 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3a7e1532da](https://linux-hardware.org/?probe=3a7e1532da) | May 03, 2023 |
| ASUSTek       | P5B-Deluxe                  | [d0d3458299](https://linux-hardware.org/?probe=d0d3458299) | Apr 29, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| ASUSTek       | P5B-MX                      | [3770e032b4](https://linux-hardware.org/?probe=3770e032b4) | Apr 21, 2023 |
| Gigabyte      | F2A68HM-S1                  | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| Gigabyte      | A320M-H-CF                  | [6ac890debf](https://linux-hardware.org/?probe=6ac890debf) | Apr 12, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| ASUSTek       | M2N4-SLI                    | [870bba0c09](https://linux-hardware.org/?probe=870bba0c09) | Apr 03, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| MSI           | H61M-P20                    | [18409d7178](https://linux-hardware.org/?probe=18409d7178) | Mar 28, 2023 |
| ASUSTek       | PRIME A320M-K               | [8d0ef2d912](https://linux-hardware.org/?probe=8d0ef2d912) | Mar 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b48ee031b3](https://linux-hardware.org/?probe=b48ee031b3) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Medion        | MS-7800                     | [fcd708adc0](https://linux-hardware.org/?probe=fcd708adc0) | Mar 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [25e3173dc4](https://linux-hardware.org/?probe=25e3173dc4) | Mar 01, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e8e3f57eef](https://linux-hardware.org/?probe=e8e3f57eef) | Feb 26, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| Lenovo        | 3138 NO DPK                 | [2beb8f24f3](https://linux-hardware.org/?probe=2beb8f24f3) | Feb 20, 2023 |
| Lenovo        | 3138 NO DPK                 | [992af7508c](https://linux-hardware.org/?probe=992af7508c) | Feb 20, 2023 |
| MSI           | B450M PRO-M2                | [eb1d201d1c](https://linux-hardware.org/?probe=eb1d201d1c) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| Biostar       | A68N-2100                   | [a0ebf68180](https://linux-hardware.org/?probe=a0ebf68180) | Feb 10, 2023 |
| NCR           | Pocono                      | [1a1c878e10](https://linux-hardware.org/?probe=1a1c878e10) | Jan 31, 2023 |
| ASRock        | FM2A68M-DG3+                | [7fb4a85c09](https://linux-hardware.org/?probe=7fb4a85c09) | Jan 30, 2023 |
| Lenovo        | 312A NOK                    | [ef4e303beb](https://linux-hardware.org/?probe=ef4e303beb) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [b20da22e41](https://linux-hardware.org/?probe=b20da22e41) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| ASUSTek       | A68HM-K                     | [770d2f3bb4](https://linux-hardware.org/?probe=770d2f3bb4) | Jan 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [bc8b02043e](https://linux-hardware.org/?probe=bc8b02043e) | Jan 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [61a73fa103](https://linux-hardware.org/?probe=61a73fa103) | Jan 12, 2023 |
| Medion        | MS-7621                     | [da2d61d475](https://linux-hardware.org/?probe=da2d61d475) | Jan 07, 2023 |
| ASRock        | X570 Pro4                   | [db00fde012](https://linux-hardware.org/?probe=db00fde012) | Jan 07, 2023 |
| Gigabyte      | A320M-H-CF                  | [b4511daea8](https://linux-hardware.org/?probe=b4511daea8) | Dec 30, 2022 |
| Gigabyte      | A320M-H-CF                  | [aff2b93aa5](https://linux-hardware.org/?probe=aff2b93aa5) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f51a366bc2](https://linux-hardware.org/?probe=f51a366bc2) | Dec 26, 2022 |
| NCR           | Pocono                      | [d50ad710fb](https://linux-hardware.org/?probe=d50ad710fb) | Dec 26, 2022 |
| Gigabyte      | B450M S2H                   | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [73c8ec2eb1](https://linux-hardware.org/?probe=73c8ec2eb1) | Dec 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [caaddcd344](https://linux-hardware.org/?probe=caaddcd344) | Dec 18, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [45eafa4ade](https://linux-hardware.org/?probe=45eafa4ade) | Dec 17, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | [1fb1bc61c1](https://linux-hardware.org/?probe=1fb1bc61c1) | Dec 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | [4cfe094684](https://linux-hardware.org/?probe=4cfe094684) | Dec 10, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [def749869a](https://linux-hardware.org/?probe=def749869a) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9789efe96c](https://linux-hardware.org/?probe=9789efe96c) | Dec 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9b5a24a1a2](https://linux-hardware.org/?probe=9b5a24a1a2) | Dec 07, 2022 |
| ASUSTek       | P7P55D DELUXE               | [a0864dbdc7](https://linux-hardware.org/?probe=a0864dbdc7) | Dec 06, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ecb93d2406](https://linux-hardware.org/?probe=ecb93d2406) | Dec 06, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [3fb8809375](https://linux-hardware.org/?probe=3fb8809375) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | [a15aba2f94](https://linux-hardware.org/?probe=a15aba2f94) | Dec 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [660b9b7529](https://linux-hardware.org/?probe=660b9b7529) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9d7fdf83b6](https://linux-hardware.org/?probe=9d7fdf83b6) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-K               | [944ade9560](https://linux-hardware.org/?probe=944ade9560) | Nov 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [37b51f19ef](https://linux-hardware.org/?probe=37b51f19ef) | Nov 27, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| HP            | 212B                        | [d2ccd70744](https://linux-hardware.org/?probe=d2ccd70744) | Nov 05, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASUSTek       | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| Gigabyte      | F2A88X-D3H                  | [7290b40608](https://linux-hardware.org/?probe=7290b40608) | Oct 27, 2022 |
| MSI           | MS-7309                     | [fe0fae3528](https://linux-hardware.org/?probe=fe0fae3528) | Oct 26, 2022 |
| MSI           | MS-7309                     | [2db582d6dd](https://linux-hardware.org/?probe=2db582d6dd) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| MSI           | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek       | P5B-Deluxe                  | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| ASUSTek       | H61M-K                      | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [24c93934d4](https://linux-hardware.org/?probe=24c93934d4) | Sep 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [29f2bd4304](https://linux-hardware.org/?probe=29f2bd4304) | Sep 25, 2022 |
| Biostar       | TB250-BTC                   | [0a4522a059](https://linux-hardware.org/?probe=0a4522a059) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [815fe42722](https://linux-hardware.org/?probe=815fe42722) | Sep 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| ASUSTek       | P5Q PRO TURBO               | [96564b490b](https://linux-hardware.org/?probe=96564b490b) | Sep 15, 2022 |
| ASUSTek       | P5Q PRO TURBO               | [846849e46c](https://linux-hardware.org/?probe=846849e46c) | Sep 15, 2022 |
| Foxconn       | 2AA9                        | [b671b09c1a](https://linux-hardware.org/?probe=b671b09c1a) | Sep 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb47ce6e71](https://linux-hardware.org/?probe=cb47ce6e71) | Sep 09, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a355222b61](https://linux-hardware.org/?probe=a355222b61) | Sep 07, 2022 |
| HP            | 304Bh                       | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| Gigabyte      | 965P-DS3                    | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| HP            | 0980h                       | [1b4bdc2dd3](https://linux-hardware.org/?probe=1b4bdc2dd3) | Aug 25, 2022 |
| HP            | 0980h                       | [28433ca1db](https://linux-hardware.org/?probe=28433ca1db) | Aug 25, 2022 |
| HP            | 304Bh                       | [1e3d59e493](https://linux-hardware.org/?probe=1e3d59e493) | Aug 21, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [bbeebdd421](https://linux-hardware.org/?probe=bbeebdd421) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [0c4f85c70e](https://linux-hardware.org/?probe=0c4f85c70e) | Jul 13, 2022 |
| MSI           | H61M-P20                    | [c86cefdaa6](https://linux-hardware.org/?probe=c86cefdaa6) | Jun 26, 2022 |
| ASUSTek       | H110M-R                     | [74d3cc8728](https://linux-hardware.org/?probe=74d3cc8728) | Jun 14, 2022 |
| ASRock        | G41C-GS                     | [c498f6f3bd](https://linux-hardware.org/?probe=c498f6f3bd) | Jun 13, 2022 |
| Gigabyte      | GA-H310TN-R2                | [2fecd41e0b](https://linux-hardware.org/?probe=2fecd41e0b) | Jun 03, 2022 |
| Gigabyte      | X570 GAMING X               | [2dba625d78](https://linux-hardware.org/?probe=2dba625d78) | May 28, 2022 |
| ASUSTek       | B85-PLUS                    | [ea1d17f234](https://linux-hardware.org/?probe=ea1d17f234) | May 27, 2022 |
| ASUSTek       | B85-PLUS                    | [e1efc36540](https://linux-hardware.org/?probe=e1efc36540) | May 27, 2022 |
| ASRock        | X570 Pro4                   | [da35dd6295](https://linux-hardware.org/?probe=da35dd6295) | May 22, 2022 |
| Gigabyte      | Z97P-D3                     | [1b7bdd0f65](https://linux-hardware.org/?probe=1b7bdd0f65) | May 21, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [2fdd079ebc](https://linux-hardware.org/?probe=2fdd079ebc) | May 21, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| Gigabyte      | H110M-DS2-CF                | [7166bb5a53](https://linux-hardware.org/?probe=7166bb5a53) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [bc84347b65](https://linux-hardware.org/?probe=bc84347b65) | May 11, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| HP            | 3396                        | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4f8108d1e](https://linux-hardware.org/?probe=f4f8108d1e) | Apr 25, 2022 |
| ASUSTek       | P7H55                       | [d619f35fb8](https://linux-hardware.org/?probe=d619f35fb8) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| ASUSTek       | B150-PRO                    | [1ebe5f0e99](https://linux-hardware.org/?probe=1ebe5f0e99) | Apr 15, 2022 |
| Gigabyte      | 945PL-S3                    | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [55568ec828](https://linux-hardware.org/?probe=55568ec828) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| ASRock        | B560M Steel Legend          | [8caaa96b19](https://linux-hardware.org/?probe=8caaa96b19) | Mar 28, 2022 |
| HP            | 3398                        | [b84864ecc4](https://linux-hardware.org/?probe=b84864ecc4) | Mar 25, 2022 |
| HP            | 3032h                       | [e57d52908c](https://linux-hardware.org/?probe=e57d52908c) | Mar 21, 2022 |
| HP            | 3398                        | [5f018df1dd](https://linux-hardware.org/?probe=5f018df1dd) | Mar 17, 2022 |
| ASUSTek       | M5A99X EVO                  | [117ebec9fc](https://linux-hardware.org/?probe=117ebec9fc) | Mar 15, 2022 |
| MSI           | AM1I                        | [f19c9ef173](https://linux-hardware.org/?probe=f19c9ef173) | Mar 14, 2022 |
| MSI           | A68HM-E33 V2                | [9f17c99bb5](https://linux-hardware.org/?probe=9f17c99bb5) | Mar 06, 2022 |
| MSI           | B450M PRO-M2                | [723ab179b6](https://linux-hardware.org/?probe=723ab179b6) | Mar 06, 2022 |
| Gigabyte      | H81M-S2PH                   | [4a1c505260](https://linux-hardware.org/?probe=4a1c505260) | Mar 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [65b41a7a67](https://linux-hardware.org/?probe=65b41a7a67) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1f607a3c8c](https://linux-hardware.org/?probe=1f607a3c8c) | Feb 21, 2022 |
| Gigabyte      | MJPLNCB-00                  | [d9a5169bbc](https://linux-hardware.org/?probe=d9a5169bbc) | Feb 16, 2022 |
| MSI           | A55M-P33                    | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| MSI           | GF615M-P33 V2               | [b5bfcbf8dc](https://linux-hardware.org/?probe=b5bfcbf8dc) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [1eb72bde90](https://linux-hardware.org/?probe=1eb72bde90) | Feb 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d6c5c1a6d2](https://linux-hardware.org/?probe=d6c5c1a6d2) | Feb 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | [a530f2976f](https://linux-hardware.org/?probe=a530f2976f) | Feb 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | [5480f2aa6c](https://linux-hardware.org/?probe=5480f2aa6c) | Feb 10, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [b28eb819f0](https://linux-hardware.org/?probe=b28eb819f0) | Feb 09, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [1c829ba8dd](https://linux-hardware.org/?probe=1c829ba8dd) | Feb 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [80b24c2689](https://linux-hardware.org/?probe=80b24c2689) | Feb 03, 2022 |
| ASUSTek       | PRIME B450M-K               | [d644756f37](https://linux-hardware.org/?probe=d644756f37) | Feb 03, 2022 |
| MSI           | B450 TOMAHAWK               | [b5ae920f3b](https://linux-hardware.org/?probe=b5ae920f3b) | Feb 02, 2022 |
| ASRock        | P75 Pro3                    | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| Gigabyte      | 970A-DS3P                   | [b50f284364](https://linux-hardware.org/?probe=b50f284364) | Jan 23, 2022 |
| ASUSTek       | PRIME B450M-K               | [fa62cb2996](https://linux-hardware.org/?probe=fa62cb2996) | Jan 11, 2022 |
| Biostar       | TB250-BTC+                  | [ef57a01461](https://linux-hardware.org/?probe=ef57a01461) | Jan 06, 2022 |
| ASUSTek       | H110M-R                     | [8b6fab3f89](https://linux-hardware.org/?probe=8b6fab3f89) | Jan 05, 2022 |
| ASRock        | X570 Pro4                   | [0396ef9c72](https://linux-hardware.org/?probe=0396ef9c72) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6324598512](https://linux-hardware.org/?probe=6324598512) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [38dda4af6b](https://linux-hardware.org/?probe=38dda4af6b) | Dec 30, 2021 |
| Gigabyte      | B550M DS3H                  | [9fb08ebeb4](https://linux-hardware.org/?probe=9fb08ebeb4) | Dec 26, 2021 |
| Gigabyte      | MJPLNCB-00                  | [fe81720eae](https://linux-hardware.org/?probe=fe81720eae) | Dec 23, 2021 |
| ASUSTek       | A68HM-K                     | [a6fc4a2adb](https://linux-hardware.org/?probe=a6fc4a2adb) | Dec 22, 2021 |
| MSI           | A55M-P33                    | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| MSI           | FM2-A55M-E33                | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [048c623b7a](https://linux-hardware.org/?probe=048c623b7a) | Dec 12, 2021 |
| Biostar       | NF520-A2 TE                 | [5878187120](https://linux-hardware.org/?probe=5878187120) | Dec 07, 2021 |
| MSI           | H61M-P20                    | [614ffcb196](https://linux-hardware.org/?probe=614ffcb196) | Dec 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [19fbf0d287](https://linux-hardware.org/?probe=19fbf0d287) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [478ab590ac](https://linux-hardware.org/?probe=478ab590ac) | Dec 01, 2021 |
| ASUSTek       | P8B75-M LE                  | [7a8c29f7ba](https://linux-hardware.org/?probe=7a8c29f7ba) | Nov 23, 2021 |
| ASUSTek       | P8Z68-V LX                  | [0415c0798f](https://linux-hardware.org/?probe=0415c0798f) | Nov 18, 2021 |
| MSI           | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| MSI           | G41M-P23                    | [ce4c8636f0](https://linux-hardware.org/?probe=ce4c8636f0) | Nov 04, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [b6338a1294](https://linux-hardware.org/?probe=b6338a1294) | Oct 25, 2021 |
| Gigabyte      | B450M S2H                   | [71c19b42fc](https://linux-hardware.org/?probe=71c19b42fc) | Oct 21, 2021 |
| Lenovo        | ThinkCentre M57 6075Y3W     | [a5e2419919](https://linux-hardware.org/?probe=a5e2419919) | Oct 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f1fc83e719](https://linux-hardware.org/?probe=f1fc83e719) | Oct 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2802b3ba4f](https://linux-hardware.org/?probe=2802b3ba4f) | Oct 17, 2021 |
| Gigabyte      | P35-S3G                     | [0582e2316b](https://linux-hardware.org/?probe=0582e2316b) | Oct 12, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [c8b4b9444e](https://linux-hardware.org/?probe=c8b4b9444e) | Oct 11, 2021 |
| ASRock        | QC5000-ITX/WiFi             | [74391da331](https://linux-hardware.org/?probe=74391da331) | Oct 09, 2021 |
| Biostar       | A320MH                      | [85950c5033](https://linux-hardware.org/?probe=85950c5033) | Sep 25, 2021 |
| ASUSTek       | H81M-R                      | [dfe4dc9048](https://linux-hardware.org/?probe=dfe4dc9048) | Sep 22, 2021 |
| MSI           | MS-7309                     | [f2ac6eb80a](https://linux-hardware.org/?probe=f2ac6eb80a) | Sep 18, 2021 |
| Lenovo        | ThinkCentre M57 6075Y3W     | [f133dd54a3](https://linux-hardware.org/?probe=f133dd54a3) | Sep 18, 2021 |
| HP            | 212B                        | [9a7f2627a3](https://linux-hardware.org/?probe=9a7f2627a3) | Sep 15, 2021 |
| HP            | 212B                        | [289f117cde](https://linux-hardware.org/?probe=289f117cde) | Sep 14, 2021 |
| ASUSTek       | H81M-R                      | [6a9795f23f](https://linux-hardware.org/?probe=6a9795f23f) | Sep 13, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [67285c1d5d](https://linux-hardware.org/?probe=67285c1d5d) | Sep 11, 2021 |
| ASUSTek       | AM1M-A                      | [ab6a989deb](https://linux-hardware.org/?probe=ab6a989deb) | Sep 09, 2021 |
| ASRock        | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| ASUSTek       | AM1M-A                      | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| MSI           | 740GM-P25                   | [e1d245e0a3](https://linux-hardware.org/?probe=e1d245e0a3) | Aug 19, 2021 |
| ASUSTek       | AM1M-A                      | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| ASRock        | X570 Pro4                   | [3f122964da](https://linux-hardware.org/?probe=3f122964da) | Aug 14, 2021 |
| Gigabyte      | H61M-S2PV                   | [3985c521c2](https://linux-hardware.org/?probe=3985c521c2) | Aug 12, 2021 |
| ASUSTek       | M5A97 PLUS                  | [bf5a5f589f](https://linux-hardware.org/?probe=bf5a5f589f) | Aug 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [fda988dc8a](https://linux-hardware.org/?probe=fda988dc8a) | Jul 30, 2021 |
| Gigabyte      | H61M-S2PV                   | [766df6d543](https://linux-hardware.org/?probe=766df6d543) | Jul 30, 2021 |
| ASUSTek       | B75M-A                      | [d86a526a9b](https://linux-hardware.org/?probe=d86a526a9b) | Jul 28, 2021 |
| Gigabyte      | P31-DS3L                    | [48b32724e2](https://linux-hardware.org/?probe=48b32724e2) | Jul 27, 2021 |
| ASUSTek       | B75M-A                      | [25113d73cc](https://linux-hardware.org/?probe=25113d73cc) | Jul 21, 2021 |
| ASUSTek       | M2N-MX                      | [b5def43240](https://linux-hardware.org/?probe=b5def43240) | Jun 23, 2021 |
| MSI           | 760GM-P23                   | [2a7524175d](https://linux-hardware.org/?probe=2a7524175d) | Jun 20, 2021 |
| MSI           | 970A-G43                    | [447e2a364c](https://linux-hardware.org/?probe=447e2a364c) | Jun 18, 2021 |
| ASUSTek       | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| MSI           | 970A-G43                    | [009fc99fc0](https://linux-hardware.org/?probe=009fc99fc0) | Jun 11, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [09f134f35d](https://linux-hardware.org/?probe=09f134f35d) | Jun 11, 2021 |
| Gigabyte      | 945PL-S3                    | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| MSI           | 970A-G43                    | [c0523d2ed9](https://linux-hardware.org/?probe=c0523d2ed9) | Jun 08, 2021 |
| Gigabyte      | H61M-DS2                    | [b527e6a2a9](https://linux-hardware.org/?probe=b527e6a2a9) | Jun 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock        | A320M-HDV R4.0              | [094ade14ae](https://linux-hardware.org/?probe=094ade14ae) | May 27, 2021 |
| ASRock        | B450M Pro4                  | [229b36f7f9](https://linux-hardware.org/?probe=229b36f7f9) | May 25, 2021 |
| Dell          | 0C27VV A01                  | [5824a76242](https://linux-hardware.org/?probe=5824a76242) | May 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [631e15df6a](https://linux-hardware.org/?probe=631e15df6a) | May 18, 2021 |
| ASRock        | H110 Pro BTC+               | [ff29bdd7f7](https://linux-hardware.org/?probe=ff29bdd7f7) | May 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [7b5519e189](https://linux-hardware.org/?probe=7b5519e189) | May 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [5ea8612591](https://linux-hardware.org/?probe=5ea8612591) | May 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [e3f1850f8e](https://linux-hardware.org/?probe=e3f1850f8e) | May 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | [211622d161](https://linux-hardware.org/?probe=211622d161) | May 05, 2021 |
| Gigabyte      | A320M-H-CF                  | [07a49be491](https://linux-hardware.org/?probe=07a49be491) | May 03, 2021 |
| Gigabyte      | H61M-S2PV                   | [325c441d47](https://linux-hardware.org/?probe=325c441d47) | Apr 27, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [15e01ddb68](https://linux-hardware.org/?probe=15e01ddb68) | Apr 27, 2021 |
| Inventec      | R CLASS A02                 | [d678a44af1](https://linux-hardware.org/?probe=d678a44af1) | Apr 18, 2021 |
| Lenovo        | 312A NOK                    | [5db737f928](https://linux-hardware.org/?probe=5db737f928) | Apr 16, 2021 |
| Gigabyte      | EP43-UD3L                   | [9988abc6d1](https://linux-hardware.org/?probe=9988abc6d1) | Mar 30, 2021 |
| HP            | 3032h                       | [04ae8fc721](https://linux-hardware.org/?probe=04ae8fc721) | Mar 26, 2021 |
| Acer          | FIH57                       | [ddb03d82a0](https://linux-hardware.org/?probe=ddb03d82a0) | Mar 24, 2021 |
| ASRock        | QC5000-ITX/WiFi             | [7940fddf34](https://linux-hardware.org/?probe=7940fddf34) | Mar 24, 2021 |
| HP            | 1497                        | [8a761041cb](https://linux-hardware.org/?probe=8a761041cb) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK               | [9d190d0899](https://linux-hardware.org/?probe=9d190d0899) | Mar 17, 2021 |
| ASRock        | Z390 Pro4                   | [5fe5bdf357](https://linux-hardware.org/?probe=5fe5bdf357) | Mar 16, 2021 |
| MSI           | 880GM-E41                   | [4f6b84a8c0](https://linux-hardware.org/?probe=4f6b84a8c0) | Mar 15, 2021 |
| MSI           | H61M-P20                    | [6c184c27d1](https://linux-hardware.org/?probe=6c184c27d1) | Mar 15, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [9aea38338d](https://linux-hardware.org/?probe=9aea38338d) | Mar 15, 2021 |
| Gigabyte      | H61M-D2H-USB3               | [7e3e20bba4](https://linux-hardware.org/?probe=7e3e20bba4) | Mar 15, 2021 |
| ASUSTek       | M5A88-V EVO                 | [3163da0fc6](https://linux-hardware.org/?probe=3163da0fc6) | Mar 12, 2021 |
| Intel         | 945                         | [87a90ecd5e](https://linux-hardware.org/?probe=87a90ecd5e) | Mar 11, 2021 |
| Intel         | 945                         | [4644c2d3dd](https://linux-hardware.org/?probe=4644c2d3dd) | Mar 10, 2021 |
| Intel         | 945                         | [bdcdd4c2c9](https://linux-hardware.org/?probe=bdcdd4c2c9) | Mar 09, 2021 |
| ASUSTek       | M5A88-V EVO                 | [54b1a7993c](https://linux-hardware.org/?probe=54b1a7993c) | Mar 09, 2021 |
| ASUSTek       | M5A88-V EVO                 | [20dd877fba](https://linux-hardware.org/?probe=20dd877fba) | Mar 09, 2021 |
| MSI           | MS-7369                     | [6b76ab1b0c](https://linux-hardware.org/?probe=6b76ab1b0c) | Mar 06, 2021 |
| MSI           | MS-7369                     | [c26816dad0](https://linux-hardware.org/?probe=c26816dad0) | Mar 06, 2021 |
| Supermicro    | X8SIL                       | [5750984770](https://linux-hardware.org/?probe=5750984770) | Mar 05, 2021 |
| Supermicro    | X8SIL                       | [c79eedd353](https://linux-hardware.org/?probe=c79eedd353) | Mar 04, 2021 |
| Lenovo        | 312A NOK                    | [10e16e0f14](https://linux-hardware.org/?probe=10e16e0f14) | Mar 02, 2021 |
| Gigabyte      | G31M-S2C                    | [a10534e0ba](https://linux-hardware.org/?probe=a10534e0ba) | Mar 02, 2021 |
| Supermicro    | X8SIL                       | [325e488c16](https://linux-hardware.org/?probe=325e488c16) | Feb 28, 2021 |
| Supermicro    | X8SIL                       | [58108e8eb1](https://linux-hardware.org/?probe=58108e8eb1) | Feb 28, 2021 |
| MSI           | 0A90                        | [36e73df6d5](https://linux-hardware.org/?probe=36e73df6d5) | Feb 26, 2021 |
| Intel         | 945                         | [de9b7b0ef0](https://linux-hardware.org/?probe=de9b7b0ef0) | Feb 25, 2021 |
| Intel         | 945                         | [d0b22beef3](https://linux-hardware.org/?probe=d0b22beef3) | Feb 25, 2021 |
| ASRock        | M3N78D                      | [c40a449681](https://linux-hardware.org/?probe=c40a449681) | Feb 23, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [888ff52208](https://linux-hardware.org/?probe=888ff52208) | Feb 21, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d2b9f26b16](https://linux-hardware.org/?probe=d2b9f26b16) | Feb 15, 2021 |
| ASUSTek       | P8B75-M LX                  | [dc49777ce8](https://linux-hardware.org/?probe=dc49777ce8) | Feb 14, 2021 |
| ASUSTek       | P5G41T-M LX3                | [d282a8d18c](https://linux-hardware.org/?probe=d282a8d18c) | Feb 14, 2021 |
| MSI           | 0A90                        | [bb71cea5b4](https://linux-hardware.org/?probe=bb71cea5b4) | Feb 09, 2021 |
| ASUSTek       | M4N78-AM                    | [4c528f55f3](https://linux-hardware.org/?probe=4c528f55f3) | Feb 07, 2021 |
| Gigabyte      | P31-ES3G                    | [5aca50689e](https://linux-hardware.org/?probe=5aca50689e) | Jan 29, 2021 |
| ASUSTek       | P5Q-EM                      | [e67f35f505](https://linux-hardware.org/?probe=e67f35f505) | Jan 28, 2021 |
| ASUSTek       | P5Q-EM                      | [d3ee3b13ef](https://linux-hardware.org/?probe=d3ee3b13ef) | Jan 28, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [c7807c2ac4](https://linux-hardware.org/?probe=c7807c2ac4) | Jan 10, 2021 |
| ASRock        | B450M Steel Legend          | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| Gigabyte      | B85M-HD3                    | [e3a87784d6](https://linux-hardware.org/?probe=e3a87784d6) | Dec 29, 2020 |
| Biostar       | A320MH                      | [42b6908594](https://linux-hardware.org/?probe=42b6908594) | Dec 29, 2020 |
| Gigabyte      | Z87-HD3                     | [2f46386da3](https://linux-hardware.org/?probe=2f46386da3) | Dec 27, 2020 |
| Biostar       | NF520D3                     | [12a6b07515](https://linux-hardware.org/?probe=12a6b07515) | Dec 27, 2020 |
| Biostar       | NF520D3                     | [c78780427f](https://linux-hardware.org/?probe=c78780427f) | Dec 27, 2020 |
| Biostar       | NF520D3                     | [60a378a184](https://linux-hardware.org/?probe=60a378a184) | Dec 27, 2020 |
| ASUSTek       | M4N78-AM                    | [9973c728ba](https://linux-hardware.org/?probe=9973c728ba) | Dec 26, 2020 |
| MSI           | K9N6PGM2-V2                 | [e62cf453c7](https://linux-hardware.org/?probe=e62cf453c7) | Dec 26, 2020 |
| MSI           | MAG B550M BAZOOKA           | [a5084b2336](https://linux-hardware.org/?probe=a5084b2336) | Dec 26, 2020 |
| ASUSTek       | H110M-R                     | [3d6c26aa3c](https://linux-hardware.org/?probe=3d6c26aa3c) | Dec 18, 2020 |
| HP            | 1497                        | [b93a804d52](https://linux-hardware.org/?probe=b93a804d52) | Dec 09, 2020 |
| Gigabyte      | H310M S2H x.x               | [5fe883b8c8](https://linux-hardware.org/?probe=5fe883b8c8) | Dec 06, 2020 |
| Gigabyte      | E3000N                      | [2861121763](https://linux-hardware.org/?probe=2861121763) | Dec 03, 2020 |
| HP            | 1495                        | [260725df5b](https://linux-hardware.org/?probe=260725df5b) | Dec 02, 2020 |
| MSI           | H110M ECO                   | [d848b46f0e](https://linux-hardware.org/?probe=d848b46f0e) | Nov 29, 2020 |
| MSI           | H110M ECO                   | [3789cd7ccf](https://linux-hardware.org/?probe=3789cd7ccf) | Nov 29, 2020 |
| MSI           | 880GMS-E35                  | [821743caaa](https://linux-hardware.org/?probe=821743caaa) | Nov 29, 2020 |
| MSI           | A320M-A PRO                 | [ce774acedc](https://linux-hardware.org/?probe=ce774acedc) | Nov 27, 2020 |
| Gigabyte      | G31M-S2C                    | [d09ca3fed0](https://linux-hardware.org/?probe=d09ca3fed0) | Nov 24, 2020 |
| Dell          | 0F6X5P A00                  | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | H81M-R                      | [10a0831d44](https://linux-hardware.org/?probe=10a0831d44) | Nov 19, 2020 |
| ASUSTek       | PRIME A320M-K               | [546d681a51](https://linux-hardware.org/?probe=546d681a51) | Nov 18, 2020 |
| Dell          | 0KRC95 A02                  | [fb7486ffb1](https://linux-hardware.org/?probe=fb7486ffb1) | Nov 16, 2020 |
| Unknown       | MCP61                       | [c4aa33a4dc](https://linux-hardware.org/?probe=c4aa33a4dc) | Nov 16, 2020 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [dc19b696c9](https://linux-hardware.org/?probe=dc19b696c9) | Nov 15, 2020 |
| ASRock        | A320M-HDV R4.0              | [c15d88af85](https://linux-hardware.org/?probe=c15d88af85) | Nov 12, 2020 |
| ASUSTek       | A55BM-K                     | [bff939ac49](https://linux-hardware.org/?probe=bff939ac49) | Nov 09, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [579d5eed69](https://linux-hardware.org/?probe=579d5eed69) | Nov 07, 2020 |
| Supermicro    | X8SIL                       | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| MSI           | H110M ECO                   | [bc31d5e177](https://linux-hardware.org/?probe=bc31d5e177) | Nov 01, 2020 |
| Supermicro    | X8SIL                       | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASUSTek       | PRIME A320M-K               | [4c29ca1b5a](https://linux-hardware.org/?probe=4c29ca1b5a) | Oct 31, 2020 |
| Supermicro    | X8SIL                       | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| Gigabyte      | 945PL-S3P                   | [b72f72f621](https://linux-hardware.org/?probe=b72f72f621) | Oct 26, 2020 |
| Intel         | D946GZIS AAD66165-302       | [ba9fec911f](https://linux-hardware.org/?probe=ba9fec911f) | Oct 20, 2020 |
| Dell          | 0GM819                      | [e0cbe10449](https://linux-hardware.org/?probe=e0cbe10449) | Oct 17, 2020 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a5f35bd977](https://linux-hardware.org/?probe=a5f35bd977) | Oct 12, 2020 |
| ASUSTek       | PRIME A320M-K               | [ca6c1b562d](https://linux-hardware.org/?probe=ca6c1b562d) | Oct 05, 2020 |
| MSI           | H87-G41 PC Mate             | [ee0ab6bf04](https://linux-hardware.org/?probe=ee0ab6bf04) | Oct 02, 2020 |
| Biostar       | A320MH                      | [ee41403938](https://linux-hardware.org/?probe=ee41403938) | Oct 02, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [3e7beef386](https://linux-hardware.org/?probe=3e7beef386) | Sep 30, 2020 |
| Gigabyte      | B360M DS3H                  | [61dcf65bfa](https://linux-hardware.org/?probe=61dcf65bfa) | Sep 30, 2020 |
| Gigabyte      | G31M-S2C                    | [d73874f616](https://linux-hardware.org/?probe=d73874f616) | Sep 29, 2020 |
| Gigabyte      | G31M-S2C                    | [d662ed85f8](https://linux-hardware.org/?probe=d662ed85f8) | Sep 29, 2020 |
| Gigabyte      | F2A68HM-S1                  | [b886a607be](https://linux-hardware.org/?probe=b886a607be) | Sep 28, 2020 |
| MSI           | 760GM-P21                   | [b23305b1f3](https://linux-hardware.org/?probe=b23305b1f3) | Sep 12, 2020 |
| ASUSTek       | H97-PLUS                    | [a5726bfa80](https://linux-hardware.org/?probe=a5726bfa80) | Sep 10, 2020 |
| Gigabyte      | F2A58M-DS2H                 | [41b9e1526c](https://linux-hardware.org/?probe=41b9e1526c) | Sep 10, 2020 |
| MSI           | 970 GAMING                  | [44041b729e](https://linux-hardware.org/?probe=44041b729e) | Sep 06, 2020 |
| HP            | 2AF3                        | [75f15238ce](https://linux-hardware.org/?probe=75f15238ce) | Aug 31, 2020 |
| ASRock        | X570 Pro4                   | [0d7778cc62](https://linux-hardware.org/?probe=0d7778cc62) | Aug 29, 2020 |
| MSI           | K9N6PGM2-V2                 | [cb65aa7264](https://linux-hardware.org/?probe=cb65aa7264) | Aug 25, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [6bb8820098](https://linux-hardware.org/?probe=6bb8820098) | Aug 22, 2020 |
| HP            | 3398                        | [8590b22254](https://linux-hardware.org/?probe=8590b22254) | Aug 15, 2020 |
| Dell          | 0DR845                      | [a4ddbdc998](https://linux-hardware.org/?probe=a4ddbdc998) | Aug 11, 2020 |
| MSI           | GF615M-P33                  | [b5c3471e8b](https://linux-hardware.org/?probe=b5c3471e8b) | Aug 09, 2020 |
| MSI           | GF615M-P33                  | [50b0587266](https://linux-hardware.org/?probe=50b0587266) | Aug 09, 2020 |
| HP            | 3032h                       | [9abca57bf3](https://linux-hardware.org/?probe=9abca57bf3) | Aug 06, 2020 |
| ASUSTek       | PRIME X570-P                | [801277e6be](https://linux-hardware.org/?probe=801277e6be) | Aug 05, 2020 |
| ECS           | H61H2-M12                   | [2ac9b3f866](https://linux-hardware.org/?probe=2ac9b3f866) | Aug 02, 2020 |
| ASUSTek       | H110M-R                     | [09dac438f3](https://linux-hardware.org/?probe=09dac438f3) | Jul 31, 2020 |
| ASUSTek       | A58M-E                      | [6cb4e9e3e5](https://linux-hardware.org/?probe=6cb4e9e3e5) | Jul 30, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [200bdd5138](https://linux-hardware.org/?probe=200bdd5138) | Jul 25, 2020 |
| Gigabyte      | 970A-DS3P                   | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| Gigabyte      | Z77X-UD5H                   | [4f0031f39f](https://linux-hardware.org/?probe=4f0031f39f) | Jul 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | [9bdd60ecdf](https://linux-hardware.org/?probe=9bdd60ecdf) | Jul 19, 2020 |
| Gigabyte      | H61M-S2P                    | [a30442ec07](https://linux-hardware.org/?probe=a30442ec07) | Jul 19, 2020 |
| Gigabyte      | H61M-S2P                    | [57b85cdafa](https://linux-hardware.org/?probe=57b85cdafa) | Jul 19, 2020 |
| MSI           | GF615M-P33 V2               | [64d092bac7](https://linux-hardware.org/?probe=64d092bac7) | Jul 18, 2020 |
| MSI           | GF615M-P33 V2               | [ca930a9e05](https://linux-hardware.org/?probe=ca930a9e05) | Jul 17, 2020 |
| ASUSTek       | H110M-R                     | [26e1de29bc](https://linux-hardware.org/?probe=26e1de29bc) | Jul 14, 2020 |
| HP            | 1497                        | [c26aebcc5f](https://linux-hardware.org/?probe=c26aebcc5f) | Jul 13, 2020 |
| Gigabyte      | Z77X-UD5H                   | [dbc59ac760](https://linux-hardware.org/?probe=dbc59ac760) | Jul 12, 2020 |
| Dell          | 0GTK4K A02                  | [d40a7e2ced](https://linux-hardware.org/?probe=d40a7e2ced) | Jul 11, 2020 |
| Dell          | 0GTK4K A02                  | [085d13e046](https://linux-hardware.org/?probe=085d13e046) | Jul 11, 2020 |
| HP            | 18E7                        | [d277840c01](https://linux-hardware.org/?probe=d277840c01) | Jul 03, 2020 |
| Gigabyte      | F2A58M-DS2H                 | [3ed1463dd4](https://linux-hardware.org/?probe=3ed1463dd4) | Jun 17, 2020 |
| Pegatron      | 2AB6                        | [f886c11963](https://linux-hardware.org/?probe=f886c11963) | Jun 12, 2020 |
| Pegatron      | 2AB6                        | [c9954b4a26](https://linux-hardware.org/?probe=c9954b4a26) | Jun 11, 2020 |
| ASUSTek       | H110M-R                     | [c201f6d857](https://linux-hardware.org/?probe=c201f6d857) | Jun 11, 2020 |
| MSI           | G41M-P28                    | [b0ce30ab32](https://linux-hardware.org/?probe=b0ce30ab32) | Jun 11, 2020 |
| ASUSTek       | A58M-K                      | [117bf5197f](https://linux-hardware.org/?probe=117bf5197f) | Jun 10, 2020 |
| ASUSTek       | A58M-K                      | [f8f58eaad6](https://linux-hardware.org/?probe=f8f58eaad6) | Jun 09, 2020 |
| ASUSTek       | P5Q-VM DO                   | [346628ed49](https://linux-hardware.org/?probe=346628ed49) | Jun 09, 2020 |
| MSI           | G31TM-P21                   | [a63d6c107a](https://linux-hardware.org/?probe=a63d6c107a) | Jun 08, 2020 |
| MSI           | MS-7519                     | [27185a4dad](https://linux-hardware.org/?probe=27185a4dad) | Jun 05, 2020 |
| MSI           | B75MA-E33                   | [e7156806db](https://linux-hardware.org/?probe=e7156806db) | May 25, 2020 |
| MSI           | B75MA-E33                   | [508ff9a8bd](https://linux-hardware.org/?probe=508ff9a8bd) | May 25, 2020 |
| ASUSTek       | P5N73-AM                    | [3258ee8b5d](https://linux-hardware.org/?probe=3258ee8b5d) | May 23, 2020 |
| ASUSTek       | P7H55-M LX                  | [9799c4742b](https://linux-hardware.org/?probe=9799c4742b) | May 23, 2020 |
| ASUSTek       | P5QL PRO                    | [c8e5e768fd](https://linux-hardware.org/?probe=c8e5e768fd) | May 21, 2020 |
| Gigabyte      | P55-USB3                    | [59982dc231](https://linux-hardware.org/?probe=59982dc231) | May 14, 2020 |
| Gigabyte      | P31-DS3L                    | [507a4c1c74](https://linux-hardware.org/?probe=507a4c1c74) | May 12, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [9de43ba1db](https://linux-hardware.org/?probe=9de43ba1db) | May 07, 2020 |
| HP            | 3398                        | [86c6f07f18](https://linux-hardware.org/?probe=86c6f07f18) | May 06, 2020 |
| Gigabyte      | P31-DS3L                    | [63fea1c9cd](https://linux-hardware.org/?probe=63fea1c9cd) | May 03, 2020 |
| ASUSTek       | A58M-K                      | [b40e7fdbef](https://linux-hardware.org/?probe=b40e7fdbef) | May 03, 2020 |
| Gigabyte      | P31-ES3G                    | [33279e03d0](https://linux-hardware.org/?probe=33279e03d0) | Apr 30, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [4cae21a722](https://linux-hardware.org/?probe=4cae21a722) | Apr 22, 2020 |
| ASUSTek       | P5Q-VM DO                   | [fc60d56b77](https://linux-hardware.org/?probe=fc60d56b77) | Apr 19, 2020 |
| ASUSTek       | A58M-K                      | [c86917f5cc](https://linux-hardware.org/?probe=c86917f5cc) | Apr 17, 2020 |
| MSI           | FM2-A55M-E33                | [2e15f64ca6](https://linux-hardware.org/?probe=2e15f64ca6) | Apr 14, 2020 |
| Pegatron      | 2AB5                        | [b041763dea](https://linux-hardware.org/?probe=b041763dea) | Apr 11, 2020 |
| ASUSTek       | PRIME A320M-K               | [1418f2501e](https://linux-hardware.org/?probe=1418f2501e) | Apr 10, 2020 |
| Biostar       | TB250-BTC                   | [fd92f418b8](https://linux-hardware.org/?probe=fd92f418b8) | Apr 08, 2020 |
| HP            | 18E7                        | [4d9f332c70](https://linux-hardware.org/?probe=4d9f332c70) | Apr 08, 2020 |
| HP            | 18E7                        | [6f953f68bd](https://linux-hardware.org/?probe=6f953f68bd) | Apr 08, 2020 |
| Gigabyte      | P31-DS3L                    | [b713dcca4f](https://linux-hardware.org/?probe=b713dcca4f) | Apr 08, 2020 |
| ASUSTek       | PRIME A320M-K               | [a34d2ffc57](https://linux-hardware.org/?probe=a34d2ffc57) | Apr 08, 2020 |
| ASUSTek       | A58M-K                      | [2d7bcf65f9](https://linux-hardware.org/?probe=2d7bcf65f9) | Apr 07, 2020 |
| ASUSTek       | A58M-K                      | [7db11256da](https://linux-hardware.org/?probe=7db11256da) | Apr 05, 2020 |
| ASUSTek       | P5Q-VM DO                   | [f1dcc22829](https://linux-hardware.org/?probe=f1dcc22829) | Apr 05, 2020 |
| MSI           | 760GM-P23                   | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [d51cbbf880](https://linux-hardware.org/?probe=d51cbbf880) | Mar 07, 2020 |
| Gigabyte      | F2A55M-DS2                  | [a82780cd8c](https://linux-hardware.org/?probe=a82780cd8c) | Mar 04, 2020 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [68b9561775](https://linux-hardware.org/?probe=68b9561775) | Mar 03, 2020 |
| ASUSTek       | P8B75-M LE                  | [6140664ce7](https://linux-hardware.org/?probe=6140664ce7) | Feb 26, 2020 |
| Gigabyte      | F2A55M-DS2                  | [d79a2cce0d](https://linux-hardware.org/?probe=d79a2cce0d) | Feb 25, 2020 |
| ASUSTek       | H110M-R                     | [2d9562d0e1](https://linux-hardware.org/?probe=2d9562d0e1) | Feb 24, 2020 |
| ASUSTek       | P5Q                         | [f22209135d](https://linux-hardware.org/?probe=f22209135d) | Feb 22, 2020 |
| ASUSTek       | P5Q                         | [6d0cd87c90](https://linux-hardware.org/?probe=6d0cd87c90) | Feb 22, 2020 |
| Biostar       | TB85                        | [ee5bd25897](https://linux-hardware.org/?probe=ee5bd25897) | Feb 13, 2020 |
| MSI           | MS-7309                     | [3a6ec44dd2](https://linux-hardware.org/?probe=3a6ec44dd2) | Feb 11, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [034e07f7f9](https://linux-hardware.org/?probe=034e07f7f9) | Jan 28, 2020 |
| Gigabyte      | B360M DS3H                  | [eab9be2c36](https://linux-hardware.org/?probe=eab9be2c36) | Jan 25, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [a292515c70](https://linux-hardware.org/?probe=a292515c70) | Jan 24, 2020 |
| ASUSTek       | P5B                         | [149a63defe](https://linux-hardware.org/?probe=149a63defe) | Jan 15, 2020 |
| ASUSTek       | TUF X299 MARK 2             | [afa0b93a9a](https://linux-hardware.org/?probe=afa0b93a9a) | Jan 13, 2020 |
| ASUSTek       | TUF X299 MARK 2             | [3b4ed71c09](https://linux-hardware.org/?probe=3b4ed71c09) | Jan 13, 2020 |
| Gigabyte      | GA-880GA-UD3H               | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| MSI           | A55M-P33                    | [96778949af](https://linux-hardware.org/?probe=96778949af) | Jan 12, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e722d70419](https://linux-hardware.org/?probe=e722d70419) | Dec 26, 2019 |
| ASUSTek       | M2V-MX SE                   | [476f99ff1b](https://linux-hardware.org/?probe=476f99ff1b) | Dec 25, 2019 |
| ASUSTek       | M2V-MX SE                   | [b3a4634787](https://linux-hardware.org/?probe=b3a4634787) | Dec 11, 2019 |
| HP            | 18E7                        | [df3ebe7dbd](https://linux-hardware.org/?probe=df3ebe7dbd) | Dec 05, 2019 |
| ASUSTek       | PRIME A320M-K               | [3d62acc94f](https://linux-hardware.org/?probe=3d62acc94f) | Nov 23, 2019 |
| Gigabyte      | Z170-D3H-CF                 | [38d61517b0](https://linux-hardware.org/?probe=38d61517b0) | Nov 18, 2019 |
| Gigabyte      | Z170-D3H-CF                 | [5e619cb47c](https://linux-hardware.org/?probe=5e619cb47c) | Nov 14, 2019 |
| Gigabyte      | H61M-S2PV                   | [e4374eaa46](https://linux-hardware.org/?probe=e4374eaa46) | Nov 13, 2019 |
| ASUSTek       | P5VD2-VM                    | [be44322d10](https://linux-hardware.org/?probe=be44322d10) | Nov 10, 2019 |
| HP            | 18E7                        | [92ce2d6aee](https://linux-hardware.org/?probe=92ce2d6aee) | Nov 01, 2019 |
| HP            | 18E7                        | [bddfdd0942](https://linux-hardware.org/?probe=bddfdd0942) | Oct 30, 2019 |
| ASUSTek       | H81M-PLUS                   | [dab482c9fe](https://linux-hardware.org/?probe=dab482c9fe) | Oct 17, 2019 |
| Gigabyte      | EX58-UD5                    | [e9b8af35f1](https://linux-hardware.org/?probe=e9b8af35f1) | Sep 18, 2019 |
| HP            | 0AECh D                     | [269249911a](https://linux-hardware.org/?probe=269249911a) | Sep 12, 2019 |
| HP            | 0AECh D                     | [ba5eb5e765](https://linux-hardware.org/?probe=ba5eb5e765) | Sep 10, 2019 |
| HP            | 0AECh D                     | [ced13a5341](https://linux-hardware.org/?probe=ced13a5341) | Sep 10, 2019 |
| HP            | 0AECh D                     | [a21951a4db](https://linux-hardware.org/?probe=a21951a4db) | Sep 10, 2019 |
| MSI           | K9A2 Neo2                   | [282a00eec9](https://linux-hardware.org/?probe=282a00eec9) | Sep 09, 2019 |
| ASUSTek       | STRIX B250F GAMING          | [8310a10125](https://linux-hardware.org/?probe=8310a10125) | Sep 04, 2019 |
| ASUSTek       | STRIX B250F GAMING          | [7dfedd3f65](https://linux-hardware.org/?probe=7dfedd3f65) | Sep 04, 2019 |
| Gigabyte      | Z77X-UD5H                   | [9795f4c856](https://linux-hardware.org/?probe=9795f4c856) | Aug 08, 2019 |
| MSI           | G31TM-P21                   | [95c164bfe9](https://linux-hardware.org/?probe=95c164bfe9) | Jul 09, 2019 |
| HP            | 18E7                        | [9f42078526](https://linux-hardware.org/?probe=9f42078526) | Jun 17, 2019 |
| Gigabyte      | Z370N WIFI-CF               | [1920d53d00](https://linux-hardware.org/?probe=1920d53d00) | Jun 14, 2019 |
| Gigabyte      | nForce                      | [bb385761f8](https://linux-hardware.org/?probe=bb385761f8) | Jun 13, 2019 |
| Gigabyte      | nForce                      | [8f095ad1ed](https://linux-hardware.org/?probe=8f095ad1ed) | Jun 13, 2019 |
| Aquarius      | AQH310CM                    | [8f1cfe4955](https://linux-hardware.org/?probe=8f1cfe4955) | May 17, 2019 |
| Gigabyte      | H77-DS3H                    | [2c88acf8c6](https://linux-hardware.org/?probe=2c88acf8c6) | May 09, 2019 |
| ASUSTek       | Z87-PRO                     | [d4224e0573](https://linux-hardware.org/?probe=d4224e0573) | May 07, 2019 |
| ASUSTek       | P5KPL-AM                    | [93fe493cc6](https://linux-hardware.org/?probe=93fe493cc6) | May 05, 2019 |
| Gigabyte      | Z68X-UD3H-B3                | [df39cb5ee3](https://linux-hardware.org/?probe=df39cb5ee3) | May 02, 2019 |
| ASUSTek       | P5KPL-AM                    | [b9c9d59c4d](https://linux-hardware.org/?probe=b9c9d59c4d) | Apr 29, 2019 |
| ASUSTek       | P5KPL-AM                    | [7e9b6e595f](https://linux-hardware.org/?probe=7e9b6e595f) | Apr 27, 2019 |
| ASUSTek       | P5KPL-AM                    | [cd90126cd9](https://linux-hardware.org/?probe=cd90126cd9) | Apr 27, 2019 |
| Gigabyte      | 945GZM-S2                   | [9b7c085767](https://linux-hardware.org/?probe=9b7c085767) | Apr 19, 2019 |
| ASRock        | Z370 Pro4                   | [4e2a505f4c](https://linux-hardware.org/?probe=4e2a505f4c) | Apr 14, 2019 |
| Biostar       | A320MH                      | [ec3de6c8f3](https://linux-hardware.org/?probe=ec3de6c8f3) | Apr 14, 2019 |
| HP            | 3397                        | [de1f50edc6](https://linux-hardware.org/?probe=de1f50edc6) | Apr 10, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [d0387d6f7f](https://linux-hardware.org/?probe=d0387d6f7f) | Feb 14, 2019 |
| HP            | 304Bh                       | [d0e9c381f4](https://linux-hardware.org/?probe=d0e9c381f4) | Jan 30, 2019 |
| HP            | 304Bh                       | [20b87b0499](https://linux-hardware.org/?probe=20b87b0499) | Jan 30, 2019 |
| Gigabyte      | GA-M55PLUS-S3G              | [00e0d03d08](https://linux-hardware.org/?probe=00e0d03d08) | Dec 31, 2018 |
| Gigabyte      | GA-M55PLUS-S3G              | [bee5cfec2b](https://linux-hardware.org/?probe=bee5cfec2b) | Dec 31, 2018 |
| ASUSTek       | H81M-K                      | [feb3df641a](https://linux-hardware.org/?probe=feb3df641a) | Dec 30, 2018 |
| Sapphire      | PI-AM3RS785G                | [056357df30](https://linux-hardware.org/?probe=056357df30) | Nov 23, 2018 |
| Gigabyte      | GA-MA790XT-UD4P             | [4dc8527429](https://linux-hardware.org/?probe=4dc8527429) | Oct 18, 2018 |
| Gigabyte      | B360M DS3H                  | [28d5f5c509](https://linux-hardware.org/?probe=28d5f5c509) | Jun 07, 2018 |
| ASUSTek       | P5G41T-M LX                 | [5af7396727](https://linux-hardware.org/?probe=5af7396727) | May 09, 2018 |
| ASUSTek       | P5KPL-SE                    | [89e7fd236e](https://linux-hardware.org/?probe=89e7fd236e) | May 06, 2018 |
| ASUSTek       | P5K PRO                     | [56d1969bce](https://linux-hardware.org/?probe=56d1969bce) | Apr 17, 2018 |
| HP            | 18E7                        | [271b2e5f68](https://linux-hardware.org/?probe=271b2e5f68) | Mar 30, 2018 |
| HP            | 18E7                        | [5a5c8eb33e](https://linux-hardware.org/?probe=5a5c8eb33e) | Mar 09, 2018 |
| MSI           | Z77A-G41                    | [b153017c21](https://linux-hardware.org/?probe=b153017c21) | Dec 06, 2017 |
| Gigabyte      | EX58-UD5                    | [fa09aec26e](https://linux-hardware.org/?probe=fa09aec26e) | Nov 14, 2017 |
| ASUSTek       | P5KPL-SE                    | [28a8c15f9f](https://linux-hardware.org/?probe=28a8c15f9f) | Oct 05, 2017 |
| MSI           | Z77A-G41                    | [f58e7ca8f5](https://linux-hardware.org/?probe=f58e7ca8f5) | Jun 08, 2017 |
| MSI           | Z77A-G41                    | [c8b35c8a55](https://linux-hardware.org/?probe=c8b35c8a55) | May 14, 2017 |
| MSI           | Z77A-G41                    | [38f8ac507c](https://linux-hardware.org/?probe=38f8ac507c) | May 14, 2017 |
| Gigabyte      | M68MT-S2                    | [22698f1708](https://linux-hardware.org/?probe=22698f1708) | May 09, 2017 |
| Gigabyte      | H61M-S2PV                   | [1f46bc5de5](https://linux-hardware.org/?probe=1f46bc5de5) | May 01, 2017 |
| MSI           | A68HM-E33                   | [10a8c09f6f](https://linux-hardware.org/?probe=10a8c09f6f) | Feb 01, 2017 |
| Gigabyte      | EX58-UD5                    | [e05aaad3af](https://linux-hardware.org/?probe=e05aaad3af) | Jan 06, 2017 |
| MSI           | A68HM-E33                   | [d8ef39f103](https://linux-hardware.org/?probe=d8ef39f103) | Dec 23, 2016 |
| HP            | 18E7                        | [1c4f5fdfe5](https://linux-hardware.org/?probe=1c4f5fdfe5) | Nov 07, 2016 |
| HP            | 18E7                        | [b4c03f5538](https://linux-hardware.org/?probe=b4c03f5538) | Nov 07, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Serbia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 50       | 8.88%   |
| Ubuntu 22.04                 | 25       | 4.44%   |
| Ubuntu 18.04                 | 22       | 3.91%   |
| OpenMandriva 4.2             | 19       | 3.37%   |
| OpenMandriva 4.3             | 17       | 3.02%   |
| Ubuntu 24.04                 | 16       | 2.84%   |
| Zorin 16                     | 14       | 2.49%   |
| Arch Rolling                 | 11       | 1.95%   |
| Fedora 41                    | 10       | 1.78%   |
| Debian 12                    | 10       | 1.78%   |
| BlackPanther 18.1            | 10       | 1.78%   |
| OpenMandriva 23.01           | 8        | 1.42%   |
| KDE neon 20.04               | 8        | 1.42%   |
| Fedora 40                    | 8        | 1.42%   |
| ROSA R10                     | 7        | 1.24%   |
| Pop!_OS 22.04                | 7        | 1.24%   |
| OpenMandriva 25.90           | 6        | 1.07%   |
| OpenMandriva 25.06           | 6        | 1.07%   |
| OpenMandriva 24.12           | 6        | 1.07%   |
| OpenMandriva 23.08           | 6        | 1.07%   |
| Linux Mint 20                | 6        | 1.07%   |
| EndeavourOS Rolling          | 6        | 1.07%   |
| ArcoLinux Rolling            | 6        | 1.07%   |
| Zorin 17                     | 5        | 0.89%   |
| Ubuntu 21.10                 | 5        | 0.89%   |
| Pop!_OS 20.04                | 5        | 0.89%   |
| OpenMandriva 5.0             | 5        | 0.89%   |
| Fedora 38                    | 5        | 0.89%   |
| Bazzite 42                   | 5        | 0.89%   |
| Arch                         | 5        | 0.89%   |
| Zorin 18                     | 4        | 0.71%   |
| Ubuntu 22.10                 | 4        | 0.71%   |
| Ubuntu 21.04                 | 4        | 0.71%   |
| Ubuntu 19.10                 | 4        | 0.71%   |
| ROSA R8                      | 4        | 0.71%   |
| ROSA R11.1                   | 4        | 0.71%   |
| ROSA R11                     | 4        | 0.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 0.71%   |
| OpenMandriva 24.07           | 4        | 0.71%   |
| Manjaro                      | 4        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 137      | 26.5%   |
| OpenMandriva     | 84       | 16.25%  |
| Fedora           | 35       | 6.77%   |
| Linux Mint       | 33       | 6.38%   |
| Zorin            | 27       | 5.22%   |
| ROSA             | 21       | 4.06%   |
| Debian           | 19       | 3.68%   |
| Pop!_OS          | 16       | 3.09%   |
| Arch             | 16       | 3.09%   |
| Kubuntu          | 12       | 2.32%   |
| KDE neon         | 11       | 2.13%   |
| BlackPanther     | 11       | 2.13%   |
| Manjaro          | 10       | 1.93%   |
| Bazzite          | 9        | 1.74%   |
| ArcoLinux        | 8        | 1.55%   |
| openSUSE         | 7        | 1.35%   |
| Xubuntu          | 6        | 1.16%   |
| EndeavourOS      | 6        | 1.16%   |
| MX               | 5        | 0.97%   |
| Kali             | 4        | 0.77%   |
| CachyOS          | 4        | 0.77%   |
| Ubuntu Unity     | 3        | 0.58%   |
| Nobara           | 3        | 0.58%   |
| LMDE             | 3        | 0.58%   |
| Endless          | 3        | 0.58%   |
| Clear Linux      | 3        | 0.58%   |
| PCLinuxOS        | 2        | 0.39%   |
| org.kde.Platform | 2        | 0.39%   |
| LinuxFX          | 2        | 0.39%   |
| Linux Lite       | 2        | 0.39%   |
| CentOS           | 2        | 0.39%   |
| Ubuntu Budgie    | 1        | 0.19%   |
| Slackware        | 1        | 0.19%   |
| Serbian          | 1        | 0.19%   |
| Reborn OS        | 1        | 0.19%   |
| Peppermint       | 1        | 0.19%   |
| NixOS            | 1        | 0.19%   |
| Lubuntu          | 1        | 0.19%   |
| Gentoo           | 1        | 0.19%   |
| Garuda Linux     | 1        | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 19       | 3.11%   |
| 5.16.7-desktop-1omv4003         | 15       | 2.46%   |
| 6.14.2-desktop-3omv2590         | 13       | 2.13%   |
| 5.4.0-42-generic                | 12       | 1.97%   |
| 6.1.1-desktop-1omv2290          | 8        | 1.31%   |
| 4.18.16-desktop-1bP             | 8        | 1.31%   |
| 6.6.2-desktop-1omv2390          | 6        | 0.98%   |
| 6.12.1-desktop-1omv2490         | 6        | 0.98%   |
| 6.4.11-desktop-1omv2390         | 5        | 0.82%   |
| 5.15.0-56-generic               | 5        | 0.82%   |
| 5.15.0-53-generic               | 5        | 0.82%   |
| 5.4.0-91-generic                | 4        | 0.66%   |
| 5.13.0-28-generic               | 4        | 0.66%   |
| 4.18.0-17-generic               | 4        | 0.66%   |
| 6.8.0-52-generic                | 3        | 0.49%   |
| 6.8.0-49-generic                | 3        | 0.49%   |
| 6.14.0-36-generic               | 3        | 0.49%   |
| 6.14.0-33-generic               | 3        | 0.49%   |
| 5.4.0-54-generic                | 3        | 0.49%   |
| 5.4.0-48-generic                | 3        | 0.49%   |
| 5.4.0-40-generic                | 3        | 0.49%   |
| 5.4.0-31-generic                | 3        | 0.49%   |
| 5.4.0-26-generic                | 3        | 0.49%   |
| 5.3.0-46-generic                | 3        | 0.49%   |
| 5.11.0-34-generic               | 3        | 0.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 0.49%   |
| 6.9.7-desktop-1omv2490          | 2        | 0.33%   |
| 6.9.3-76060903-generic          | 2        | 0.33%   |
| 6.8.0-51-generic                | 2        | 0.33%   |
| 6.8.0-48-generic                | 2        | 0.33%   |
| 6.8.0-47-generic                | 2        | 0.33%   |
| 6.8.0-45-generic                | 2        | 0.33%   |
| 6.8.0-31-generic                | 2        | 0.33%   |
| 6.5.0-35-generic                | 2        | 0.33%   |
| 6.5.0-28-generic                | 2        | 0.33%   |
| 6.5.0-26-generic                | 2        | 0.33%   |
| 6.5.0-18-generic                | 2        | 0.33%   |
| 6.4.8-desktop-2omv2390          | 2        | 0.33%   |
| 6.3.5-desktop-3omv2390          | 2        | 0.33%   |
| 6.2.6-desktop-1omv2390          | 2        | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 62       | 10.84%  |
| 5.15.0  | 37       | 6.47%   |
| 6.8.0   | 24       | 4.2%    |
| 4.15.0  | 22       | 3.85%   |
| 5.10.14 | 19       | 3.32%   |
| 5.11.0  | 16       | 2.8%    |
| 6.14.2  | 15       | 2.62%   |
| 5.8.0   | 15       | 2.62%   |
| 5.16.7  | 15       | 2.62%   |
| 6.1.0   | 14       | 2.45%   |
| 5.13.0  | 14       | 2.45%   |
| 6.5.0   | 13       | 2.27%   |
| 6.14.0  | 10       | 1.75%   |
| 5.3.0   | 10       | 1.75%   |
| 5.19.0  | 10       | 1.75%   |
| 6.2.0   | 9        | 1.57%   |
| 6.1.1   | 9        | 1.57%   |
| 6.11.0  | 8        | 1.4%    |
| 4.18.16 | 8        | 1.4%    |
| 4.18.0  | 7        | 1.22%   |
| 6.6.2   | 6        | 1.05%   |
| 6.4.11  | 6        | 1.05%   |
| 6.12.1  | 6        | 1.05%   |
| 6.2.6   | 4        | 0.7%    |
| 6.12.9  | 4        | 0.7%    |
| 5.0.0   | 4        | 0.7%    |
| 4.9.60  | 4        | 0.7%    |
| 4.19.0  | 4        | 0.7%    |
| 6.9.7   | 3        | 0.52%   |
| 6.4.8   | 3        | 0.52%   |
| 6.17.7  | 3        | 0.52%   |
| 6.16.4  | 3        | 0.52%   |
| 6.15.6  | 3        | 0.52%   |
| 5.7.8   | 3        | 0.52%   |
| 4.9.20  | 3        | 0.52%   |
| 6.9.3   | 2        | 0.35%   |
| 6.9.12  | 2        | 0.35%   |
| 6.6.7   | 2        | 0.35%   |
| 6.3.5   | 2        | 0.35%   |
| 6.13.9  | 2        | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 69       | 12.23%  |
| 5.15    | 42       | 7.45%   |
| 6.8     | 30       | 5.32%   |
| 6.14    | 29       | 5.14%   |
| 6.1     | 28       | 4.96%   |
| 5.10    | 25       | 4.43%   |
| 4.15    | 22       | 3.9%    |
| 6.12    | 21       | 3.72%   |
| 5.16    | 18       | 3.19%   |
| 5.11    | 18       | 3.19%   |
| 6.2     | 17       | 3.01%   |
| 5.19    | 17       | 3.01%   |
| 5.8     | 16       | 2.84%   |
| 5.13    | 16       | 2.84%   |
| 6.5     | 15       | 2.66%   |
| 5.3     | 15       | 2.66%   |
| 4.18    | 15       | 2.66%   |
| 6.6     | 13       | 2.3%    |
| 6.11    | 11       | 1.95%   |
| 6.4     | 10       | 1.77%   |
| 4.9     | 10       | 1.77%   |
| 6.9     | 9        | 1.6%    |
| 6.17    | 8        | 1.42%   |
| 6.13    | 7        | 1.24%   |
| 6.0     | 7        | 1.24%   |
| 5.6     | 7        | 1.24%   |
| 6.3     | 6        | 1.06%   |
| 5.9     | 6        | 1.06%   |
| 5.7     | 6        | 1.06%   |
| 5.0     | 6        | 1.06%   |
| 4.19    | 6        | 1.06%   |
| 6.16    | 5        | 0.89%   |
| 6.10    | 5        | 0.89%   |
| 6.15    | 4        | 0.71%   |
| 5.14    | 4        | 0.71%   |
| 4.1     | 4        | 0.71%   |
| 5.17    | 3        | 0.53%   |
| 6.7     | 2        | 0.35%   |
| 5.2     | 2        | 0.35%   |
| 5.18    | 2        | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 481      | 98.36%  |
| i686   | 8        | 1.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 198      | 38.45%  |
| KDE5            | 110      | 21.36%  |
| KDE6            | 52       | 10.1%   |
| Unknown         | 38       | 7.38%   |
| XFCE            | 37       | 7.18%   |
| X-Cinnamon      | 30       | 5.83%   |
| KDE4            | 13       | 2.52%   |
| KDE             | 11       | 2.14%   |
| Cinnamon        | 5        | 0.97%   |
| Unity           | 3        | 0.58%   |
| LXQt            | 3        | 0.58%   |
| i3              | 3        | 0.58%   |
| MATE            | 2        | 0.39%   |
| LXDE            | 2        | 0.39%   |
| qtile           | 1        | 0.19%   |
| Pantheon        | 1        | 0.19%   |
| niri            | 1        | 0.19%   |
| i3-with-shmlog  | 1        | 0.19%   |
| GNOME Flashback | 1        | 0.19%   |
| GNOME Classic   | 1        | 0.19%   |
| Deepin          | 1        | 0.19%   |
| Budgie          | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 364      | 70.41%  |
| Wayland | 134      | 25.92%  |
| Tty     | 10       | 1.93%   |
| Unknown | 9        | 1.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 234      | 45.44%  |
| SDDM    | 133      | 25.83%  |
| GDM3    | 59       | 11.46%  |
| LightDM | 42       | 8.16%   |
| GDM     | 27       | 5.24%   |
| KDM     | 11       | 2.14%   |
| TDM     | 6        | 1.17%   |
| XDM     | 1        | 0.19%   |
| MDM     | 1        | 0.19%   |
| Ly      | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 358      | 70.61%  |
| Unknown     | 55       | 10.85%  |
| sr_RS       | 41       | 8.09%   |
| hu_HU       | 12       | 2.37%   |
| sr_RS@latin | 10       | 1.97%   |
| C           | 9        | 1.78%   |
| en_GB       | 7        | 1.38%   |
| de_DE       | 4        | 0.79%   |
| ru_RU       | 3        | 0.59%   |
| en_BW       | 2        | 0.39%   |
| en_AU       | 2        | 0.39%   |
| Default     | 2        | 0.39%   |
| sk_SK       | 1        | 0.2%    |
| hr_HR       | 1        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 311      | 61.95%  |
| EFI  | 191      | 38.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 326      | 62.69%  |
| Overlay | 74       | 14.23%  |
| Btrfs   | 55       | 10.58%  |
| Tmpfs   | 33       | 6.35%   |
| Unknown | 18       | 3.46%   |
| Xfs     | 6        | 1.15%   |
| Zfs     | 5        | 0.96%   |
| Ext2    | 2        | 0.38%   |
| Ext3    | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 238      | 46.76%  |
| GPT     | 192      | 37.72%  |
| MBR     | 79       | 15.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 406      | 80.72%  |
| Yes       | 97       | 19.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 322      | 63.89%  |
| Yes       | 182      | 36.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Gigabyte Technology              | 140      | 28.69%  |
| ASUSTek Computer                 | 136      | 27.87%  |
| MSI                              | 75       | 15.37%  |
| ASRock                           | 34       | 6.97%   |
| Hewlett-Packard                  | 23       | 4.71%   |
| Dell                             | 16       | 3.28%   |
| Biostar                          | 14       | 2.87%   |
| Fujitsu                          | 10       | 2.05%   |
| Lenovo                           | 8        | 1.64%   |
| Acer                             | 5        | 1.02%   |
| Medion                           | 3        | 0.61%   |
| Intel                            | 3        | 0.61%   |
| Huanan                           | 3        | 0.61%   |
| Pegatron                         | 2        | 0.41%   |
| Techvision                       | 1        | 0.2%    |
| Supermicro                       | 1        | 0.2%    |
| Sapphire                         | 1        | 0.2%    |
| NCR                              | 1        | 0.2%    |
| Micro Computer (HK) Tech Limited | 1        | 0.2%    |
| MACHINIST                        | 1        | 0.2%    |
| LattePanda                       | 1        | 0.2%    |
| Inventec                         | 1        | 0.2%    |
| GMKtec                           | 1        | 0.2%    |
| Fujitsu Siemens                  | 1        | 0.2%    |
| Foxconn                          | 1        | 0.2%    |
| ECS                              | 1        | 0.2%    |
| Aquarius                         | 1        | 0.2%    |
| Apple                            | 1        | 0.2%    |
| Alienware                        | 1        | 0.2%    |
| Unknown                          | 1        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME A320M-K       | 24       | 4.92%   |
| ASUS All Series          | 15       | 3.07%   |
| Gigabyte B450M DS3H      | 8        | 1.64%   |
| MSI MS-7309              | 6        | 1.23%   |
| Gigabyte H61M-S2PV       | 6        | 1.23%   |
| Gigabyte 970A-DS3P       | 5        | 1.02%   |
| Biostar A320MH           | 5        | 1.02%   |
| MSI MS-7C52              | 4        | 0.82%   |
| MSI MS-7C02              | 4        | 0.82%   |
| MSI MS-7788              | 4        | 0.82%   |
| MSI MS-7693              | 4        | 0.82%   |
| MSI MS-7641              | 4        | 0.82%   |
| MSI MS-7592              | 4        | 0.82%   |
| Gigabyte A320M-H         | 4        | 0.82%   |
| MSI MS-7C84              | 3        | 0.61%   |
| MSI MS-7721              | 3        | 0.61%   |
| MSI MS-7597              | 3        | 0.61%   |
| Gigabyte GA-890GPA-UD3H  | 3        | 0.61%   |
| Gigabyte F2A68HM-S1      | 3        | 0.61%   |
| Gigabyte EX58-UD5        | 3        | 0.61%   |
| Gigabyte B450M S2H       | 3        | 0.61%   |
| Gigabyte A520M K V2      | 3        | 0.61%   |
| Dell OptiPlex 755        | 3        | 0.61%   |
| Dell OptiPlex 390        | 3        | 0.61%   |
| ASUS H110M-R             | 3        | 0.61%   |
| ASUS A68HM-K             | 3        | 0.61%   |
| ASRock B450M-HDV R4.0    | 3        | 0.61%   |
| MSI MS-7E12              | 2        | 0.41%   |
| MSI MS-7808              | 2        | 0.41%   |
| MSI MS-7786              | 2        | 0.41%   |
| MSI MS-7623              | 2        | 0.41%   |
| MSI MS-7529              | 2        | 0.41%   |
| HP Z800 Workstation      | 2        | 0.41%   |
| HP Z440 Workstation      | 2        | 0.41%   |
| HP ProDesk 600 G1 TWR    | 2        | 0.41%   |
| HP Compaq Elite 8300 CMT | 2        | 0.41%   |
| HP Compaq 6200 Pro MT PC | 2        | 0.41%   |
| Gigabyte Z97X-Gaming 3   | 2        | 0.41%   |
| Gigabyte Z77X-UD5H       | 2        | 0.41%   |
| Gigabyte Z170-D3H        | 2        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 37       | 7.58%   |
| ASUS All                | 15       | 3.07%   |
| Gigabyte B450M          | 13       | 2.66%   |
| Dell OptiPlex           | 13       | 2.66%   |
| HP Compaq               | 11       | 2.25%   |
| ASUS ROG                | 11       | 2.25%   |
| ASUS TUF                | 9        | 1.84%   |
| Fujitsu ESPRIMO         | 8        | 1.64%   |
| MSI MS-7309             | 6        | 1.23%   |
| Lenovo ThinkCentre      | 6        | 1.23%   |
| Gigabyte H61M-S2PV      | 6        | 1.23%   |
| Gigabyte 970A-DS3P      | 5        | 1.02%   |
| Biostar A320MH          | 5        | 1.02%   |
| MSI MS-7C52             | 4        | 0.82%   |
| MSI MS-7C02             | 4        | 0.82%   |
| MSI MS-7788             | 4        | 0.82%   |
| MSI MS-7693             | 4        | 0.82%   |
| MSI MS-7641             | 4        | 0.82%   |
| MSI MS-7592             | 4        | 0.82%   |
| Gigabyte X570           | 4        | 0.82%   |
| Gigabyte B550           | 4        | 0.82%   |
| Gigabyte A320M-H        | 4        | 0.82%   |
| ASRock B450M-HDV        | 4        | 0.82%   |
| ASRock B450             | 4        | 0.82%   |
| MSI MS-7C84             | 3        | 0.61%   |
| MSI MS-7721             | 3        | 0.61%   |
| MSI MS-7597             | 3        | 0.61%   |
| Gigabyte Z390           | 3        | 0.61%   |
| Gigabyte GA-890GPA-UD3H | 3        | 0.61%   |
| Gigabyte F2A68HM-S1     | 3        | 0.61%   |
| Gigabyte EX58-UD5       | 3        | 0.61%   |
| Gigabyte B550M          | 3        | 0.61%   |
| Gigabyte B450           | 3        | 0.61%   |
| Gigabyte A520M          | 3        | 0.61%   |
| ASUS P5Q                | 3        | 0.61%   |
| ASUS P5KPL-AM           | 3        | 0.61%   |
| ASUS M5A78L-M           | 3        | 0.61%   |
| ASUS M4A89GTD-PRO       | 3        | 0.61%   |
| ASUS H110M-R            | 3        | 0.61%   |
| ASUS A68HM-K            | 3        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 56       | 11.48%  |
| 2012 | 44       | 9.02%   |
| 2017 | 41       | 8.4%    |
| 2014 | 40       | 8.2%    |
| 2013 | 34       | 6.97%   |
| 2011 | 32       | 6.56%   |
| 2010 | 32       | 6.56%   |
| 2009 | 30       | 6.15%   |
| 2019 | 26       | 5.33%   |
| 2020 | 24       | 4.92%   |
| 2007 | 21       | 4.3%    |
| 2023 | 19       | 3.89%   |
| 2008 | 19       | 3.89%   |
| 2022 | 15       | 3.07%   |
| 2021 | 13       | 2.66%   |
| 2016 | 13       | 2.66%   |
| 2006 | 13       | 2.66%   |
| 2015 | 10       | 2.05%   |
| 2024 | 4        | 0.82%   |
| 2025 | 1        | 0.2%    |
| 2004 | 1        | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 488      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 474      | 97.13%  |
| Enabled  | 14       | 2.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 488      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 134      | 26.38%  |
| 16.01-24.0  | 93       | 18.31%  |
| 4.01-8.0    | 79       | 15.55%  |
| 3.01-4.0    | 76       | 14.96%  |
| 32.01-64.0  | 66       | 12.99%  |
| 1.01-2.0    | 19       | 3.74%   |
| 24.01-32.0  | 18       | 3.54%   |
| 64.01-256.0 | 15       | 2.95%   |
| 0.51-1.0    | 5        | 0.98%   |
| 2.01-3.0    | 3        | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 191      | 33.75%  |
| 2.01-3.0   | 133      | 23.5%   |
| 4.01-8.0   | 87       | 15.37%  |
| 3.01-4.0   | 70       | 12.37%  |
| 0.51-1.0   | 43       | 7.6%    |
| 8.01-16.0  | 21       | 3.71%   |
| 0.01-0.5   | 11       | 1.94%   |
| 16.01-24.0 | 7        | 1.24%   |
| 24.01-32.0 | 3        | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 197      | 38.4%   |
| 2       | 143      | 27.88%  |
| 3       | 87       | 16.96%  |
| 4       | 47       | 9.16%   |
| 5       | 17       | 3.31%   |
| 0       | 9        | 1.75%   |
| 7       | 5        | 0.97%   |
| 6       | 4        | 0.78%   |
| Unknown | 2        | 0.39%   |
| 10      | 1        | 0.19%   |
| 8       | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 320      | 63.49%  |
| Yes       | 184      | 36.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 481      | 98.57%  |
| No        | 7        | 1.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 340      | 68.97%  |
| Yes       | 153      | 31.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 383      | 77.85%  |
| Yes       | 109      | 22.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Serbia  | 488      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Belgrade           | 260      | 48.87%  |
| Novi Sad           | 58       | 10.9%   |
| Niš               | 26       | 4.89%   |
| Subotica           | 15       | 2.82%   |
| Kragujevac         | 11       | 2.07%   |
| Zrenjanin          | 9        | 1.69%   |
| Pančevo           | 8        | 1.5%    |
| Požarevac         | 7        | 1.32%   |
| Leskovac           | 5        | 0.94%   |
| Becej              | 5        | 0.94%   |
| Backa Topola       | 5        | 0.94%   |
| Semlin             | 4        | 0.75%   |
| Kraljevo           | 4        | 0.75%   |
| Karloca            | 4        | 0.75%   |
| Senta              | 3        | 0.56%   |
| Ruma               | 3        | 0.56%   |
| Pirot              | 3        | 0.56%   |
| Palanka            | 3        | 0.56%   |
| Obrenovac          | 3        | 0.56%   |
| Kruševac          | 3        | 0.56%   |
| Jagodina           | 3        | 0.56%   |
| Cuprija            | 3        | 0.56%   |
| Banatsko Novo Selo | 3        | 0.56%   |
| Ada                | 3        | 0.56%   |
| Zvecka             | 2        | 0.38%   |
| Zajecar            | 2        | 0.38%   |
| Tutin              | 2        | 0.38%   |
| Sremska Mitrovica  | 2        | 0.38%   |
| Smederevo          | 2        | 0.38%   |
| Sabac              | 2        | 0.38%   |
| Rumenka            | 2        | 0.38%   |
| Novi Knezevac      | 2        | 0.38%   |
| New Belgrade       | 2        | 0.38%   |
| Lazarevac          | 2        | 0.38%   |
| Crvenka            | 2        | 0.38%   |
| Bor                | 2        | 0.38%   |
| Basaid             | 2        | 0.38%   |
| Arilje             | 2        | 0.38%   |
| Zabari             | 1        | 0.19%   |
| Vrnjacka Banja     | 1        | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 170      | 295    | 18.97%  |
| Kingston                    | 111      | 166    | 12.39%  |
| Seagate                     | 102      | 156    | 11.38%  |
| Samsung Electronics         | 93       | 161    | 10.38%  |
| Toshiba                     | 73       | 106    | 8.15%   |
| Hitachi                     | 38       | 60     | 4.24%   |
| SPCC                        | 36       | 52     | 4.02%   |
| Patriot                     | 25       | 29     | 2.79%   |
| SanDisk                     | 23       | 37     | 2.57%   |
| Gigabyte Technology         | 20       | 28     | 2.23%   |
| Biostar                     | 17       | 21     | 1.9%    |
| Transcend                   | 16       | 23     | 1.79%   |
| A-DATA Technology           | 15       | 15     | 1.67%   |
| Maxtor                      | 13       | 14     | 1.45%   |
| Kingston Technology Company | 13       | 23     | 1.45%   |
| Crucial                     | 13       | 15     | 1.45%   |
| Silicon Motion              | 9        | 19     | 1%      |
| Apacer                      | 9        | 11     | 1%      |
| Phison Electronics          | 8        | 13     | 0.89%   |
| Intel                       | 8        | 11     | 0.89%   |
| ADATA Technology            | 7        | 8      | 0.78%   |
| HGST                        | 6        | 10     | 0.67%   |
| Verbatim                    | 5        | 6      | 0.56%   |
| China                       | 5        | 10     | 0.56%   |
| Realtek Semiconductor       | 4        | 4      | 0.45%   |
| MAXIO Technology (Hangzhou) | 4        | 5      | 0.45%   |
| Unknown                     | 4        | 10     | 0.45%   |
| Unknown                     | 3        | 6      | 0.33%   |
| StoreJet                    | 3        | 4      | 0.33%   |
| Lexar                       | 3        | 7      | 0.33%   |
| GeIL                        | 3        | 4      | 0.33%   |
| ExcelStor                   | 3        | 3      | 0.33%   |
| Team                        | 2        | 4      | 0.22%   |
| PNY                         | 2        | 7      | 0.22%   |
| Phison                      | 2        | 9      | 0.22%   |
| OCZ                         | 2        | 3      | 0.22%   |
| Lenovo                      | 2        | 3      | 0.22%   |
| Intenso                     | 2        | 2      | 0.22%   |
| AMD                         | 2        | 2      | 0.22%   |
| Vi550                       | 1        | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD                       | 26       | 2.55%   |
| Kingston SA400S37240G 240GB SSD                       | 22       | 2.15%   |
| Toshiba DT01ACA100 1TB                                | 20       | 1.96%   |
| Kingston SA400S37480G 480GB SSD                       | 16       | 1.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 13       | 1.27%   |
| Toshiba DT01ACA050 500GB                              | 12       | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 1.08%   |
| Seagate ST1000DM003-1ER162 1TB                        | 11       | 1.08%   |
| WDC WD5000AAKX-001CA0 500GB                           | 10       | 0.98%   |
| Samsung SSD 860 EVO 250GB                             | 10       | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 10       | 0.98%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD                  | 10       | 0.98%   |
| Toshiba HDWD110 1TB                                   | 8        | 0.78%   |
| SPCC Solid State Disk 256GB                           | 8        | 0.78%   |
| SPCC Solid State Disk 512GB                           | 7        | 0.69%   |
| Samsung SSD 850 EVO 250GB                             | 7        | 0.69%   |
| Hitachi HDS721050CLA362 500GB                         | 7        | 0.69%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                  | 7        | 0.69%   |
| Biostar S100-120GB SSD                                | 7        | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 6        | 0.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 6        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                          | 6        | 0.59%   |
| Patriot Burst 240GB SSD                               | 6        | 0.59%   |
| Kingston SNVS500G 500GB                               | 6        | 0.59%   |
| Kingston SKC3000S1024G 1TB                            | 6        | 0.59%   |
| WDC WD3200AAJS-56B4A0 320GB                           | 5        | 0.49%   |
| Toshiba DT01ACA200 2TB                                | 5        | 0.49%   |
| SPCC Solid State Disk 128GB                           | 5        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5        | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5        | 0.49%   |
| Samsung SSD 860 EVO 500GB                             | 5        | 0.49%   |
| Samsung HD502HJ 500GB                                 | 5        | 0.49%   |
| Kingston SNV2S500G 500GB                              | 5        | 0.49%   |
| Kingston SHFS37A120G 120GB SSD                        | 5        | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 4        | 0.39%   |
| WDC WD1600AAJS-00L7A0 160GB                           | 4        | 0.39%   |
| WDC WD10EZRX-00A8LB0 1TB                              | 4        | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB                               | 4        | 0.39%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 4        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 164      | 282    | 38.95%  |
| Seagate             | 97       | 149    | 23.04%  |
| Toshiba             | 70       | 103    | 16.63%  |
| Hitachi             | 38       | 60     | 9.03%   |
| Samsung Electronics | 23       | 31     | 5.46%   |
| Maxtor              | 13       | 14     | 3.09%   |
| HGST                | 6        | 10     | 1.43%   |
| ExcelStor           | 3        | 3      | 0.71%   |
| Intenso             | 2        | 2      | 0.48%   |
| Unknown             | 1        | 1      | 0.24%   |
| QUANTUM             | 1        | 1      | 0.24%   |
| JMicron Technology  | 1        | 1      | 0.24%   |
| Fujitsu             | 1        | 2      | 0.24%   |
| Apple               | 1        | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 87       | 130    | 25.36%  |
| Samsung Electronics | 39       | 52     | 11.37%  |
| SPCC                | 35       | 51     | 10.2%   |
| Patriot             | 23       | 27     | 6.71%   |
| Gigabyte Technology | 19       | 26     | 5.54%   |
| Transcend           | 16       | 23     | 4.66%   |
| Biostar             | 16       | 20     | 4.66%   |
| SanDisk             | 14       | 27     | 4.08%   |
| Crucial             | 13       | 15     | 3.79%   |
| A-DATA Technology   | 13       | 13     | 3.79%   |
| WDC                 | 8        | 10     | 2.33%   |
| Apacer              | 8        | 10     | 2.33%   |
| Intel               | 7        | 10     | 2.04%   |
| Verbatim            | 5        | 6      | 1.46%   |
| China               | 5        | 10     | 1.46%   |
| StoreJet            | 3        | 4      | 0.87%   |
| Lexar               | 3        | 7      | 0.87%   |
| GeIL                | 3        | 4      | 0.87%   |
| Unknown             | 3        | 8      | 0.87%   |
| Team                | 2        | 4      | 0.58%   |
| Seagate             | 2        | 2      | 0.58%   |
| PNY                 | 2        | 7      | 0.58%   |
| OCZ                 | 2        | 3      | 0.58%   |
| AMD                 | 2        | 2      | 0.58%   |
| Vi550               | 1        | 1      | 0.29%   |
| TwinMOS             | 1        | 1      | 0.29%   |
| Toshiba             | 1        | 1      | 0.29%   |
| TECHLEAF-SSD        | 1        | 1      | 0.29%   |
| PHD 3.0             | 1        | 2      | 0.29%   |
| Mushkin             | 1        | 1      | 0.29%   |
| LITEON              | 1        | 1      | 0.29%   |
| Leven               | 1        | 1      | 0.29%   |
| Lenovo              | 1        | 1      | 0.29%   |
| KingDian            | 1        | 1      | 0.29%   |
| Go-Infinity         | 1        | 1      | 0.29%   |
| Corsair             | 1        | 1      | 0.29%   |
| ADATA SU            | 1        | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 325      | 660    | 43.62%  |
| SSD     | 277      | 485    | 37.18%  |
| NVMe    | 136      | 228    | 18.26%  |
| Unknown | 6        | 10     | 0.81%   |
| MMC     | 1        | 2      | 0.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 434      | 1129   | 73.19%  |
| NVMe | 136      | 228    | 22.93%  |
| SAS  | 22       | 26     | 3.71%   |
| MMC  | 1        | 2      | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 361      | 703    | 57.85%  |
| 0.51-1.0   | 170      | 268    | 27.24%  |
| 1.01-2.0   | 57       | 101    | 9.13%   |
| 3.01-4.0   | 15       | 25     | 2.4%    |
| 2.01-3.0   | 10       | 23     | 1.6%    |
| 4.01-10.0  | 8        | 16     | 1.28%   |
| 10.01-20.0 | 3        | 9      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 126      | 23.33%  |
| 251-500        | 92       | 17.04%  |
| 501-1000       | 72       | 13.33%  |
| 1001-2000      | 59       | 10.93%  |
| 1-20           | 51       | 9.44%   |
| Unknown        | 33       | 6.11%   |
| More than 3000 | 29       | 5.37%   |
| 2001-3000      | 27       | 5%      |
| 51-100         | 26       | 4.81%   |
| 21-50          | 25       | 4.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 194      | 34.83%  |
| 21-50          | 75       | 13.46%  |
| 101-250        | 71       | 12.75%  |
| 251-500        | 49       | 8.8%    |
| 51-100         | 47       | 8.44%   |
| 501-1000       | 34       | 6.1%    |
| Unknown        | 33       | 5.92%   |
| 1001-2000      | 32       | 5.75%   |
| 2001-3000      | 11       | 1.97%   |
| More than 3000 | 8        | 1.44%   |
| 0              | 3        | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB     | 3        | 3      | 3.61%   |
| WDC WD2002FAEX-007BA0 2TB       | 2        | 3      | 2.41%   |
| WDC WD10EARS-00Y5B1 1TB         | 2        | 2      | 2.41%   |
| WDC WD10EALX-009BA0 1TB         | 2        | 3      | 2.41%   |
| WDC WD1003FZEX-00MK2A0 1TB      | 2        | 2      | 2.41%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 5      | 2.41%   |
| Seagate ST380815AS 80GB         | 2        | 2      | 2.41%   |
| Seagate ST2000DM006-2DM164 2TB  | 2        | 2      | 2.41%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 2      | 2.41%   |
| Maxtor STM3250310AS 250GB       | 2        | 2      | 2.41%   |
| Intel SSDSC2CW120A3 120GB       | 2        | 2      | 2.41%   |
| Hitachi HDP725050GLA360 500GB   | 2        | 2      | 2.41%   |
| Hitachi HCP725032GLA380 320GB   | 2        | 3      | 2.41%   |
| WDC WD5002AALX-00J37A0 500GB    | 1        | 1      | 1.2%    |
| WDC WD5000LPVX-22V0TT0 500GB    | 1        | 1      | 1.2%    |
| WDC WD5000AAKX-603CA0 500GB     | 1        | 1      | 1.2%    |
| WDC WD5000AAKX-329BA0 500GB     | 1        | 1      | 1.2%    |
| WDC WD5000AAKX-07U6AA0 500GB    | 1        | 1      | 1.2%    |
| WDC WD5000AAKS-65A7B0 500GB     | 1        | 1      | 1.2%    |
| WDC WD5000AAKS-00UU3A0 500GB    | 1        | 1      | 1.2%    |
| WDC WD5000AAKS-00TMA0 500GB     | 1        | 1      | 1.2%    |
| WDC WD40EZRX-00SPEB0 4TB        | 1        | 1      | 1.2%    |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 1      | 1.2%    |
| WDC WD3200BEKT-60PVMT0 320GB    | 1        | 1      | 1.2%    |
| WDC WD3200AVVS-63L2B0 320GB     | 1        | 1      | 1.2%    |
| WDC WD3200AVVS-56L2B0 320GB     | 1        | 1      | 1.2%    |
| WDC WD20EARX-00PASB0 2TB        | 1        | 1      | 1.2%    |
| WDC WD2003FYYS-05T9B0 2TB       | 1        | 1      | 1.2%    |
| WDC WD2002FAEX-00MJRA0 2TB      | 1        | 1      | 1.2%    |
| WDC WD1600AAJS-00PSA0 160GB     | 1        | 1      | 1.2%    |
| WDC WD1600AAJS-00L7A0 160GB     | 1        | 1      | 1.2%    |
| WDC WD15EARS-00Z5B1 1TB         | 1        | 1      | 1.2%    |
| WDC WD15EARS-00MVWB0 1TB        | 1        | 1      | 1.2%    |
| WDC WD10EZEX-75WN4A0 1TB        | 1        | 1      | 1.2%    |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 1      | 1.2%    |
| WDC WD10EZEX-00RKKA0 1TB        | 1        | 1      | 1.2%    |
| WDC WD10EZEX-00BN5A0 1TB        | 1        | 1      | 1.2%    |
| WDC WD10EARS-22Y5B1 1TB         | 1        | 1      | 1.2%    |
| WDC WD10EADS-00M2B0 1TB         | 1        | 2      | 1.2%    |
| WDC WD1001FALS-00J7B1 1TB       | 1        | 1      | 1.2%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 33       | 41     | 42.86%  |
| Seagate               | 10       | 14     | 12.99%  |
| Samsung Electronics   | 9        | 12     | 11.69%  |
| Hitachi               | 6        | 8      | 7.79%   |
| Maxtor                | 5        | 6      | 6.49%   |
| Toshiba               | 3        | 3      | 3.9%    |
| Intel                 | 2        | 2      | 2.6%    |
| Verbatim              | 1        | 1      | 1.3%    |
| SPCC                  | 1        | 1      | 1.3%    |
| Realtek Semiconductor | 1        | 1      | 1.3%    |
| Kingston              | 1        | 1      | 1.3%    |
| HGST                  | 1        | 1      | 1.3%    |
| Fujitsu               | 1        | 1      | 1.3%    |
| ExcelStor             | 1        | 1      | 1.3%    |
| Crucial               | 1        | 1      | 1.3%    |
| A-DATA Technology     | 1        | 1      | 1.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 33       | 41     | 50%     |
| Seagate             | 10       | 14     | 15.15%  |
| Samsung Electronics | 6        | 7      | 9.09%   |
| Hitachi             | 6        | 8      | 9.09%   |
| Maxtor              | 5        | 6      | 7.58%   |
| Toshiba             | 3        | 3      | 4.55%   |
| HGST                | 1        | 1      | 1.52%   |
| Fujitsu             | 1        | 1      | 1.52%   |
| ExcelStor           | 1        | 1      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 57       | 82     | 83.82%  |
| SSD  | 8        | 10     | 11.76%  |
| NVMe | 3        | 3      | 4.41%   |

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
| Detected | 282      | 821    | 52.03%  |
| Works    | 194      | 469    | 35.79%  |
| Malfunc  | 66       | 95     | 12.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 235      | 34.16%  |
| AMD                          | 221      | 32.12%  |
| Samsung Electronics          | 49       | 7.12%   |
| Kingston Technology Company  | 41       | 5.96%   |
| Nvidia                       | 26       | 3.78%   |
| JMicron Technology           | 24       | 3.49%   |
| ASMedia Technology           | 17       | 2.47%   |
| Silicon Motion               | 11       | 1.6%    |
| Phison Electronics           | 11       | 1.6%    |
| Marvell Technology Group     | 11       | 1.6%    |
| SanDisk                      | 9        | 1.31%   |
| ADATA Technology             | 7        | 1.02%   |
| Realtek Semiconductor        | 5        | 0.73%   |
| VIA Technologies             | 4        | 0.58%   |
| MAXIO Technology (Hangzhou)  | 4        | 0.58%   |
| Toshiba America Info Systems | 2        | 0.29%   |
| Seagate Technology           | 2        | 0.29%   |
| LSI Logic / Symbios Logic    | 2        | 0.29%   |
| Transcend                    | 1        | 0.15%   |
| Shenzhen Longsys Electronics | 1        | 0.15%   |
| Micron/Crucial Technology    | 1        | 0.15%   |
| Micron Technology            | 1        | 0.15%   |
| Lenovo                       | 1        | 0.15%   |
| KIOXIA                       | 1        | 0.15%   |
| Broadcom / LSI               | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 107      | 11.96%  |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 41       | 4.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 41       | 4.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28       | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 28       | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 28       | 3.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25       | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 24       | 2.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23       | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21       | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.12%   |
| AMD 600 Series Chipset SATA Controller                                                  | 18       | 2.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 17       | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17       | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16       | 1.79%   |
| Nvidia MCP61 SATA Controller                                                            | 15       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 1.68%   |
| Nvidia MCP61 IDE                                                                        | 14       | 1.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 14       | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 1.56%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 1.34%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 10       | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 1.12%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 9        | 1.01%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.01%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9        | 1.01%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 8        | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.78%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 7        | 0.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 0.67%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 6        | 0.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.67%   |
| JMicron JMB361 AHCI/IDE                                                                 | 5        | 0.56%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 5        | 0.56%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 382      | 56.51%  |
| IDE  | 142      | 21.01%  |
| NVMe | 136      | 20.12%  |
| RAID | 13       | 1.92%   |
| SCSI | 2        | 0.3%    |
| SAS  | 1        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 247      | 50.61%  |
| Intel  | 241      | 49.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 12       | 2.45%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 10       | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 8        | 1.63%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 1.43%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 7        | 1.43%   |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 1.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.22%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 6        | 1.22%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 6        | 1.22%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.22%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 5        | 1.02%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 1.02%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 1.02%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 5        | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 1.02%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 5        | 1.02%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 1.02%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 1.02%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.02%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 5        | 1.02%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 4        | 0.82%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 0.82%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 4        | 0.82%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.82%   |
| AMD Ryzen 7 7700 8-Core Processor           | 4        | 0.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.82%   |
| AMD FX-8320 Eight-Core Processor            | 4        | 0.82%   |
| AMD Athlon X4 750K Quad Core Processor      | 4        | 0.82%   |
| AMD A4-4020 APU with Radeon HD Graphics     | 4        | 0.82%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 3        | 0.61%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 0.61%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 3        | 0.61%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 0.61%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 3        | 0.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 0.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.61%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 68       | 13.88%  |
| Intel Core i5           | 55       | 11.22%  |
| Intel Core i3           | 40       | 8.16%   |
| Intel Core i7           | 32       | 6.53%   |
| AMD Ryzen 7             | 31       | 6.33%   |
| Intel Core 2 Duo        | 26       | 5.31%   |
| Intel Celeron           | 21       | 4.29%   |
| AMD Ryzen 3             | 21       | 4.29%   |
| AMD FX                  | 20       | 4.08%   |
| Intel Xeon              | 18       | 3.67%   |
| AMD Ryzen 9             | 15       | 3.06%   |
| AMD Phenom II X4        | 12       | 2.45%   |
| AMD Athlon II X2        | 11       | 2.24%   |
| Other                   | 10       | 2.04%   |
| Intel Core 2 Quad       | 10       | 2.04%   |
| AMD Athlon X4           | 10       | 2.04%   |
| Intel Pentium Dual-Core | 9        | 1.84%   |
| Intel Pentium           | 9        | 1.84%   |
| AMD Athlon 64 X2        | 7        | 1.43%   |
| AMD A4                  | 7        | 1.43%   |
| AMD Ryzen 5 PRO         | 6        | 1.22%   |
| AMD Athlon II X4        | 6        | 1.22%   |
| AMD Athlon II X3        | 5        | 1.02%   |
| AMD Athlon              | 5        | 1.02%   |
| Intel Pentium Gold      | 4        | 0.82%   |
| AMD A10                 | 4        | 0.82%   |
| Intel Core i9           | 3        | 0.61%   |
| AMD Phenom II X6        | 3        | 0.61%   |
| AMD A8                  | 3        | 0.61%   |
| Intel Core 2            | 2        | 0.41%   |
| AMD Sempron             | 2        | 0.41%   |
| AMD Ryzen Threadripper  | 2        | 0.41%   |
| AMD Ryzen 3 PRO         | 2        | 0.41%   |
| AMD Phenom II X2        | 2        | 0.41%   |
| AMD Phenom              | 2        | 0.41%   |
| AMD A6                  | 2        | 0.41%   |
| Intel Pentium Dual      | 1        | 0.2%    |
| Intel Pentium D         | 1        | 0.2%    |
| Intel Pentium 4         | 1        | 0.2%    |
| AMD E2                  | 1        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 178      | 36.25%  |
| 2       | 144      | 29.33%  |
| 6       | 74       | 15.07%  |
| 8       | 40       | 8.15%   |
| 1       | 14       | 2.85%   |
| 12      | 12       | 2.44%   |
| 3       | 11       | 2.24%   |
| 16      | 8        | 1.63%   |
| 10      | 4        | 0.81%   |
| 14      | 3        | 0.61%   |
| 32      | 1        | 0.2%    |
| 24      | 1        | 0.2%    |
| Unknown | 1        | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 486      | 99.59%  |
| 2      | 2        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 260      | 53.06%  |
| 1       | 229      | 46.73%  |
| Unknown | 1        | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 484      | 99.18%  |
| Unknown        | 4        | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 226      | 43.55%  |
| 0x1067a    | 23       | 4.43%   |
| 0x306c3    | 22       | 4.24%   |
| 0x306a9    | 19       | 3.66%   |
| 0x206a7    | 19       | 3.66%   |
| 0x0800820d | 17       | 3.28%   |
| 0x08108109 | 11       | 2.12%   |
| 0x010000c8 | 11       | 2.12%   |
| 0x06001119 | 10       | 1.93%   |
| 0x906ea    | 8        | 1.54%   |
| 0x906e9    | 8        | 1.54%   |
| 0x6fd      | 8        | 1.54%   |
| 0x08101016 | 8        | 1.54%   |
| 0x08701021 | 7        | 1.35%   |
| 0x506e3    | 6        | 1.16%   |
| 0x106e5    | 6        | 1.16%   |
| 0x06003106 | 6        | 1.16%   |
| 0x6fb      | 5        | 0.96%   |
| 0x10676    | 5        | 0.96%   |
| 0x08001138 | 5        | 0.96%   |
| 0x06000852 | 5        | 0.96%   |
| 0x010000db | 5        | 0.96%   |
| 0x906eb    | 4        | 0.77%   |
| 0x906c0    | 4        | 0.77%   |
| 0x0a50000d | 4        | 0.77%   |
| 0x08701013 | 4        | 0.77%   |
| 0x0a50000c | 3        | 0.58%   |
| 0x0a201016 | 3        | 0.58%   |
| 0x08001137 | 3        | 0.58%   |
| 0x0700010b | 3        | 0.58%   |
| 0xa0671    | 2        | 0.39%   |
| 0x306f2    | 2        | 0.39%   |
| 0x206c2    | 2        | 0.39%   |
| 0x106a4    | 2        | 0.39%   |
| 0x0a201204 | 2        | 0.39%   |
| 0x0a201009 | 2        | 0.39%   |
| 0x0700010f | 2        | 0.39%   |
| 0x06000822 | 2        | 0.39%   |
| 0x03000027 | 2        | 0.39%   |
| 0x010000dc | 2        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 42       | 8.57%   |
| Haswell          | 41       | 8.37%   |
| K10              | 40       | 8.16%   |
| Penryn           | 39       | 7.96%   |
| Zen 3            | 36       | 7.35%   |
| KabyLake         | 34       | 6.94%   |
| SandyBridge      | 33       | 6.73%   |
| Piledriver       | 33       | 6.73%   |
| IvyBridge        | 28       | 5.71%   |
| Zen              | 26       | 5.31%   |
| Unknown          | 24       | 4.9%    |
| Zen 2            | 22       | 4.49%   |
| Core             | 16       | 3.27%   |
| Skylake          | 15       | 3.06%   |
| Nehalem          | 11       | 2.24%   |
| Steamroller      | 9        | 1.84%   |
| K8 Hammer        | 9        | 1.84%   |
| Jaguar           | 6        | 1.22%   |
| Alderlake Hybrid | 5        | 1.02%   |
| Westmere         | 4        | 0.82%   |
| Tremont          | 4        | 0.82%   |
| NetBurst         | 2        | 0.41%   |
| K10 Llano        | 2        | 0.41%   |
| Icelake          | 2        | 0.41%   |
| CometLake        | 2        | 0.41%   |
| Bulldozer        | 2        | 0.41%   |
| Silvermont       | 1        | 0.2%    |
| Excavator        | 1        | 0.2%    |
| Broadwell        | 1        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 258      | 49.05%  |
| Nvidia | 168      | 31.94%  |
| Intel  | 100      | 19.01%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 38       | 6.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 17       | 3.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14       | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 2.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 1.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 1.82%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 10       | 1.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 10       | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.64%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 9        | 1.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 9        | 1.64%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 1.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 1.46%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 8        | 1.46%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 8        | 1.46%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.28%   |
| AMD Raphael                                                                 | 7        | 1.28%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 7        | 1.28%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 7        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 1.09%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 1.09%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.09%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 6        | 1.09%   |
| AMD Granite Ridge [Radeon Graphics]                                         | 6        | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.91%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 5        | 0.91%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 5        | 0.91%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 5        | 0.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.73%   |
| Nvidia AD107 [GeForce RTX 4060]                                             | 4        | 0.73%   |
| Intel JasperLake [UHD Graphics]                                             | 4        | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 0.73%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 4        | 0.73%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 4        | 0.73%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4        | 0.73%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 4        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 228      | 45.97%  |
| 1 x Nvidia     | 154      | 31.05%  |
| 1 x Intel      | 78       | 15.73%  |
| 2 x AMD        | 15       | 3.02%   |
| AMD + Nvidia   | 8        | 1.61%   |
| Intel + Nvidia | 6        | 1.21%   |
| Intel + AMD    | 6        | 1.21%   |
| 2 x Nvidia     | 1        | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 394      | 78.8%   |
| Proprietary | 87       | 17.4%   |
| Unknown     | 19       | 3.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 199      | 38.49%  |
| 1.01-2.0   | 83       | 16.05%  |
| 0.51-1.0   | 64       | 12.38%  |
| 0.01-0.5   | 63       | 12.19%  |
| 3.01-4.0   | 45       | 8.7%    |
| 7.01-8.0   | 36       | 6.96%   |
| 8.01-16.0  | 12       | 2.32%   |
| 5.01-6.0   | 11       | 2.13%   |
| 2.01-3.0   | 4        | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 73       | 14.43%  |
| Goldstar             | 67       | 13.24%  |
| Dell                 | 65       | 12.85%  |
| Philips              | 53       | 10.47%  |
| Hewlett-Packard      | 29       | 5.73%   |
| Acer                 | 27       | 5.34%   |
| BenQ                 | 24       | 4.74%   |
| AOC                  | 20       | 3.95%   |
| Ancor Communications | 20       | 3.95%   |
| ViewSonic            | 16       | 3.16%   |
| Lenovo               | 14       | 2.77%   |
| ASUSTek Computer     | 13       | 2.57%   |
| LG Electronics       | 8        | 1.58%   |
| Unknown              | 6        | 1.19%   |
| Belinea              | 6        | 1.19%   |
| Gigabyte Technology  | 5        | 0.99%   |
| Vestel Elektronik    | 4        | 0.79%   |
| OEM                  | 4        | 0.79%   |
| Fujitsu Siemens      | 4        | 0.79%   |
| Toshiba              | 3        | 0.59%   |
| RTK                  | 3        | 0.59%   |
| KTC                  | 3        | 0.59%   |
| Iiyama               | 3        | 0.59%   |
| HIC                  | 3        | 0.59%   |
| CHD                  | 3        | 0.59%   |
| SUNNY                | 2        | 0.4%    |
| Panasonic            | 2        | 0.4%    |
| Medion               | 2        | 0.4%    |
| Eizo                 | 2        | 0.4%    |
| Unknown              | 2        | 0.4%    |
| VIE                  | 1        | 0.2%    |
| Vestel               | 1        | 0.2%    |
| Unknown (XXX)        | 1        | 0.2%    |
| TEL                  | 1        | 0.2%    |
| Sony                 | 1        | 0.2%    |
| SKY                  | 1        | 0.2%    |
| RGT                  | 1        | 0.2%    |
| NCS                  | 1        | 0.2%    |
| MStar                | 1        | 0.2%    |
| LED                  | 1        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 7        | 1.29%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 480x270mm 21.7-inch             | 6        | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6        | 1.1%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch | 4        | 0.74%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 4        | 0.74%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 4        | 0.74%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 4        | 0.74%   |
| Goldstar W2240 GSM57A0 1920x1080 477x268mm 21.5-inch                 | 4        | 0.74%   |
| Toshiba TV TSB0108 1920x1080 698x393mm 31.5-inch                     | 3        | 0.55%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 3        | 0.55%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch | 3        | 0.55%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch    | 3        | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3        | 0.55%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch              | 3        | 0.55%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                      | 3        | 0.55%   |
| HIC LCD Monitor HIC0001 1920x1080 256x192mm 12.6-inch                | 3        | 0.55%   |
| Hewlett-Packard V24e HPN36AC 1920x1080 527x296mm 23.8-inch           | 3        | 0.55%   |
| Goldstar W2252 GSM567E 1680x1050 474x296mm 22.0-inch                 | 3        | 0.55%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                 | 3        | 0.55%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 3        | 0.55%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                | 3        | 0.55%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 3        | 0.55%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                   | 3        | 0.55%   |
| Acer V196HQL ACR033D 1366x768 410x230mm 18.5-inch                    | 3        | 0.55%   |
| SUNNY SUNNY SNN0002 1920x1080 708x398mm 32.0-inch                    | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 2        | 0.37%   |
| Samsung Electronics SMBX2440 SAM068B 1920x1080 530x300mm 24.0-inch   | 2        | 0.37%   |
| Samsung Electronics S24R65x SAM1027 1920x1080 527x296mm 23.8-inch    | 2        | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2        | 0.37%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch    | 2        | 0.37%   |
| Samsung Electronics S23C350 SAM0A35 1920x1080 510x287mm 23.0-inch    | 2        | 0.37%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch               | 2        | 0.37%   |
| Philips PHL 328P6A PHL0913 2560x1440 698x393mm 31.5-inch             | 2        | 0.37%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                  | 2        | 0.37%   |
| Philips 220E PHLC02E 1920x1080 476x268mm 21.5-inch                   | 2        | 0.37%   |
| Philips 192E PHLC032 1366x768 413x234mm 18.7-inch                    | 2        | 0.37%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 527x296mm 23.8-inch             | 2        | 0.37%   |
| Lenovo L32p-30 LEN66C9 3840x2160 697x392mm 31.5-inch                 | 2        | 0.37%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                 | 2        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 257      | 52.24%  |
| 1280x1024 (SXGA)   | 47       | 9.55%   |
| 3840x2160 (4K)     | 39       | 7.93%   |
| 2560x1440 (QHD)    | 29       | 5.89%   |
| 1680x1050 (WSXGA+) | 21       | 4.27%   |
| 1366x768 (WXGA)    | 18       | 3.66%   |
| 1920x1200 (WUXGA)  | 16       | 3.25%   |
| 1440x900 (WXGA+)   | 16       | 3.25%   |
| 1920x540           | 7        | 1.42%   |
| 2560x1080          | 6        | 1.22%   |
| 1360x768           | 5        | 1.02%   |
| Unknown            | 5        | 1.02%   |
| 3840x1080          | 4        | 0.81%   |
| 2288x1287          | 4        | 0.81%   |
| 3440x1440          | 3        | 0.61%   |
| 1600x900 (HD+)     | 3        | 0.61%   |
| 1600x1200          | 3        | 0.61%   |
| 1280x720 (HD)      | 2        | 0.41%   |
| 1024x768 (XGA)     | 2        | 0.41%   |
| 7680x2160          | 1        | 0.2%    |
| 2560x1600          | 1        | 0.2%    |
| 1834x1031          | 1        | 0.2%    |
| 1400x1050          | 1        | 0.2%    |
| 1280x768           | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 82       | 16.05%  |
| 21      | 79       | 15.46%  |
| 23      | 70       | 13.7%   |
| 27      | 62       | 12.13%  |
| Unknown | 33       | 6.46%   |
| 19      | 29       | 5.68%   |
| 17      | 28       | 5.48%   |
| 18      | 26       | 5.09%   |
| 31      | 17       | 3.33%   |
| 22      | 17       | 3.33%   |
| 34      | 8        | 1.57%   |
| 20      | 7        | 1.37%   |
| 84      | 6        | 1.17%   |
| 72      | 5        | 0.98%   |
| 26      | 5        | 0.98%   |
| 142     | 4        | 0.78%   |
| 52      | 4        | 0.78%   |
| 15      | 4        | 0.78%   |
| 46      | 3        | 0.59%   |
| 32      | 3        | 0.59%   |
| 12      | 3        | 0.59%   |
| 54      | 2        | 0.39%   |
| 40      | 2        | 0.39%   |
| 25      | 2        | 0.39%   |
| 14      | 2        | 0.39%   |
| 65      | 1        | 0.2%    |
| 64      | 1        | 0.2%    |
| 63      | 1        | 0.2%    |
| 47      | 1        | 0.2%    |
| 43      | 1        | 0.2%    |
| 42      | 1        | 0.2%    |
| 33      | 1        | 0.2%    |
| 16      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 197      | 40.12%  |
| 401-500        | 135      | 27.49%  |
| Unknown        | 33       | 6.72%   |
| 301-350        | 30       | 6.11%   |
| 601-700        | 24       | 4.89%   |
| 351-400        | 24       | 4.89%   |
| 1001-1500      | 13       | 2.65%   |
| 701-800        | 12       | 2.44%   |
| 1501-2000      | 11       | 2.24%   |
| More than 2000 | 4        | 0.81%   |
| 201-300        | 4        | 0.81%   |
| 801-900        | 2        | 0.41%   |
| 901-1000       | 2        | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 319      | 67.73%  |
| 16/10   | 48       | 10.19%  |
| 5/4     | 43       | 9.13%   |
| Unknown | 29       | 6.16%   |
| 4/3     | 12       | 2.55%   |
| 21/9    | 8        | 1.7%    |
| 3/2     | 6        | 1.27%   |
| 1.00    | 4        | 0.85%   |
| 6/5     | 1        | 0.21%   |
| 32/9    | 1        | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 202      | 40.56%  |
| 301-350        | 64       | 12.85%  |
| 151-200        | 54       | 10.84%  |
| 141-150        | 46       | 9.24%   |
| Unknown        | 33       | 6.63%   |
| 351-500        | 29       | 5.82%   |
| 251-300        | 27       | 5.42%   |
| More than 1000 | 24       | 4.82%   |
| 501-1000       | 8        | 1.61%   |
| 101-110        | 5        | 1%      |
| 71-80          | 3        | 0.6%    |
| 111-120        | 2        | 0.4%    |
| 121-130        | 1        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 295      | 61.97%  |
| 101-120 | 101      | 21.22%  |
| Unknown | 33       | 6.93%   |
| 1-50    | 22       | 4.62%   |
| 121-160 | 15       | 3.15%   |
| 161-240 | 10       | 2.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 397      | 78.61%  |
| 2     | 73       | 14.46%  |
| 0     | 25       | 4.95%   |
| 3     | 9        | 1.78%   |
| 4     | 1        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 352      | 55.78%  |
| Intel                                 | 111      | 17.59%  |
| Qualcomm Atheros                      | 41       | 6.5%    |
| TP-Link                               | 26       | 4.12%   |
| Nvidia                                | 17       | 2.69%   |
| MediaTek                              | 13       | 2.06%   |
| Ralink Technology                     | 12       | 1.9%    |
| Qualcomm Atheros Communications       | 12       | 1.9%    |
| Broadcom                              | 7        | 1.11%   |
| Ralink                                | 5        | 0.79%   |
| ASUSTek Computer                      | 4        | 0.63%   |
| Marvell Technology Group              | 3        | 0.48%   |
| Edimax Technology                     | 3        | 0.48%   |
| VIA Technologies                      | 2        | 0.32%   |
| OPPO Electronics                      | 2        | 0.32%   |
| D-Link System                         | 2        | 0.32%   |
| D-Link                                | 2        | 0.32%   |
| ZyXEL Communications                  | 1        | 0.16%   |
| Xiaomi                                | 1        | 0.16%   |
| Texas Instruments                     | 1        | 0.16%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.16%   |
| Sigma Designs                         | 1        | 0.16%   |
| Qualcomm Technologies                 | 1        | 0.16%   |
| OnePlus Technology (Shenzhen)         | 1        | 0.16%   |
| NetGear                               | 1        | 0.16%   |
| Mercucys                              | 1        | 0.16%   |
| LSI                                   | 1        | 0.16%   |
| IMC Networks                          | 1        | 0.16%   |
| DisplayLink                           | 1        | 0.16%   |
| ASIX Electronics                      | 1        | 0.16%   |
| Aquantia                              | 1        | 0.16%   |
| ADMtek                                | 1        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.16%   |
| Unknown                               | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 289      | 42.88%  |
| Realtek RTL8125 2.5GbE Controller                                             | 31       | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14       | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 12       | 1.78%   |
| Intel I211 Gigabit Network Connection                                         | 12       | 1.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 11       | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 11       | 1.63%   |
| Qualcomm Atheros AR9271 802.11n                                               | 8        | 1.19%   |
| Nvidia MCP61 Ethernet                                                         | 8        | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7        | 1.04%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.04%   |
| Intel Ethernet Controller I225-V                                              | 7        | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 6        | 0.89%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                          | 6        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 5        | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 5        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 5        | 0.74%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 5        | 0.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 5        | 0.74%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 4        | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4        | 0.59%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 4        | 0.59%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 4        | 0.59%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 4        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4        | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 0.59%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                   | 3        | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3        | 0.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 3        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3        | 0.45%   |
| Intel Wireless 8265 / 8275                                                    | 3        | 0.45%   |
| Intel Ethernet Controller I226-V                                              | 3        | 0.45%   |
| Intel Ethernet Connection I217-V                                              | 3        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 29       | 18.35%  |
| Intel                                 | 28       | 17.72%  |
| TP-Link                               | 26       | 16.46%  |
| Qualcomm Atheros                      | 19       | 12.03%  |
| Ralink Technology                     | 12       | 7.59%   |
| Qualcomm Atheros Communications       | 12       | 7.59%   |
| MediaTek                              | 10       | 6.33%   |
| Ralink                                | 5        | 3.16%   |
| ASUSTek Computer                      | 4        | 2.53%   |
| Edimax Technology                     | 3        | 1.9%    |
| D-Link                                | 2        | 1.27%   |
| ZyXEL Communications                  | 1        | 0.63%   |
| Qualcomm Technologies                 | 1        | 0.63%   |
| NetGear                               | 1        | 0.63%   |
| Mercucys                              | 1        | 0.63%   |
| IMC Networks                          | 1        | 0.63%   |
| D-Link System                         | 1        | 0.63%   |
| Broadcom                              | 1        | 0.63%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 11       | 6.96%   |
| Qualcomm Atheros AR9271 802.11n                                               | 8        | 5.06%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 4.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 6        | 3.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 5        | 3.16%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 5        | 3.16%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 3.16%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 5        | 3.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 5        | 3.16%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 4        | 2.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4        | 2.53%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 4        | 2.53%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 4        | 2.53%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                   | 3        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3        | 1.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3        | 1.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 1.9%    |
| Intel Wireless 8265 / 8275                                                    | 3        | 1.9%    |
| Intel 700 Series Chipset CNVi WiFi                                            | 3        | 1.9%    |
| Edimax Edimax AC600 USB                                                       | 3        | 1.9%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 2        | 1.27%   |
| TP-Link 802.11n NIC                                                           | 2        | 1.27%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 2        | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2        | 1.27%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.27%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2               | 2        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 2        | 1.27%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                                    | 1        | 0.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.63%   |
| TP-Link Archer T4UH v2 [Realtek RTL8812AU]                                    | 1        | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1        | 0.63%   |
| Realtek 802.11ac NIC                                                          | 1        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 343      | 68.74%  |
| Intel                             | 92       | 18.44%  |
| Qualcomm Atheros                  | 24       | 4.81%   |
| Nvidia                            | 17       | 3.41%   |
| Broadcom                          | 6        | 1.2%    |
| Marvell Technology Group          | 3        | 0.6%    |
| VIA Technologies                  | 2        | 0.4%    |
| OPPO Electronics                  | 2        | 0.4%    |
| MediaTek                          | 2        | 0.4%    |
| Xiaomi                            | 1        | 0.2%    |
| Sundance Technology Inc / IC Plus | 1        | 0.2%    |
| OnePlus Technology (Shenzhen)     | 1        | 0.2%    |
| DisplayLink                       | 1        | 0.2%    |
| D-Link System                     | 1        | 0.2%    |
| ASIX Electronics                  | 1        | 0.2%    |
| Aquantia                          | 1        | 0.2%    |
| ADMtek                            | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 289      | 56.56%  |
| Realtek RTL8125 2.5GbE Controller                                          | 31       | 6.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 14       | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 12       | 2.35%   |
| Intel I211 Gigabit Network Connection                                      | 12       | 2.35%   |
| Intel Ethernet Connection (2) I219-V                                       | 11       | 2.15%   |
| Nvidia MCP61 Ethernet                                                      | 8        | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 1.37%   |
| Intel Ethernet Controller I225-V                                           | 7        | 1.37%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 1.17%   |
| Intel Ethernet Connection (7) I219-V                                       | 6        | 1.17%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 1.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 5        | 0.98%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 4        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 4        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 3        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 3        | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 0.59%   |
| Intel Ethernet Controller I226-V                                           | 3        | 0.59%   |
| Intel Ethernet Connection I217-V                                           | 3        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                      | 3        | 0.59%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 3        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.39%   |
| Realtek RTL8126 5GbE Controller                                            | 2        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2        | 0.39%   |
| OPPO Ace 3V                                                                | 2        | 0.39%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.39%   |
| Nvidia MCP73 Ethernet                                                      | 2        | 0.39%   |
| Nvidia MCP65 Ethernet                                                      | 2        | 0.39%   |
| MediaTek Infinix HOT 50i                                                   | 2        | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.39%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.2%    |
| VIA VT6105/VT6106S [Rhine-III]                                             | 1        | 0.2%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.2%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 481      | 75.39%  |
| WiFi     | 153      | 23.98%  |
| Modem    | 3        | 0.47%   |
| Unknown  | 1        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 404      | 80.8%   |
| WiFi     | 96       | 19.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 384      | 78.53%  |
| 2     | 88       | 18%     |
| 3     | 9        | 1.84%   |
| 0     | 5        | 1.02%   |
| 5     | 2        | 0.41%   |
| 4     | 1        | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 468      | 95.51%  |
| Yes  | 22       | 4.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 39       | 34.82%  |
| Intel                   | 28       | 25%     |
| ASUSTek Computer        | 13       | 11.61%  |
| Realtek Semiconductor   | 7        | 6.25%   |
| MediaTek                | 7        | 6.25%   |
| IMC Networks            | 5        | 4.46%   |
| TP-Link                 | 4        | 3.57%   |
| Lite-On Technology      | 3        | 2.68%   |
| Foxconn / Hon Hai       | 3        | 2.68%   |
| Unknown                 | 2        | 1.79%   |
| Apple                   | 1        | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39       | 34.82%  |
| MediaTek Wireless_Device                            | 7        | 6.25%   |
| Intel AX200 Bluetooth                               | 7        | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 6        | 5.36%   |
| Realtek Bluetooth Radio                             | 5        | 4.46%   |
| Intel AX210 Bluetooth                               | 5        | 4.46%   |
| Intel AX201 Bluetooth                               | 5        | 4.46%   |
| ASUS ASUS USB-BT500                                 | 5        | 4.46%   |
| TP-Link TP-T@- UB500 Adapter                        | 4        | 3.57%   |
| Intel Bluetooth wireless interface                  | 4        | 3.57%   |
| Intel Bluetooth Device                              | 3        | 2.68%   |
| IMC Networks Bluetooth Radio                        | 3        | 2.68%   |
| Realtek Bluetooth 5.4 Radio                         | 2        | 1.79%   |
| Lite-On Bluetooth Device                            | 2        | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 1.79%   |
| IMC Networks Wireless_Device                        | 2        | 1.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 1.79%   |
| Unknown                                             | 2        | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1        | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 0.89%   |
| ASUS Bluetooth Radio                                | 1        | 0.89%   |
| ASUS Bluetooth Device                               | 1        | 0.89%   |
| Apple Bluetooth HCI                                 | 1        | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 310      | 39.04%  |
| Intel                                           | 234      | 29.47%  |
| Nvidia                                          | 166      | 20.91%  |
| C-Media Electronics                             | 13       | 1.64%   |
| Creative Labs                                   | 8        | 1.01%   |
| Logitech                                        | 6        | 0.76%   |
| ASUSTek Computer                                | 5        | 0.63%   |
| Generalplus Technology                          | 4        | 0.5%    |
| Focusrite-Novation                              | 4        | 0.5%    |
| VIA Technologies                                | 3        | 0.38%   |
| Micro Star International                        | 3        | 0.38%   |
| Hewlett-Packard                                 | 3        | 0.38%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.25%   |
| Tenx Technology                                 | 2        | 0.25%   |
| Sony                                            | 2        | 0.25%   |
| RODE Microphones                                | 2        | 0.25%   |
| Plantronics                                     | 2        | 0.25%   |
| Microsoft                                       | 2        | 0.25%   |
| JMTek                                           | 2        | 0.25%   |
| JBL                                             | 2        | 0.25%   |
| XMOS                                            | 1        | 0.13%   |
| Veho                                            | 1        | 0.13%   |
| Valve Software                                  | 1        | 0.13%   |
| Unknown                                         | 1        | 0.13%   |
| Turtle Beach                                    | 1        | 0.13%   |
| Syntek                                          | 1        | 0.13%   |
| Razer USA                                       | 1        | 0.13%   |
| PreSonus Audio Electronics                      | 1        | 0.13%   |
| Orbbec 3D Technology International              | 1        | 0.13%   |
| Oculus VR                                       | 1        | 0.13%   |
| Native Instruments                              | 1        | 0.13%   |
| Meizu                                           | 1        | 0.13%   |
| M-Audio                                         | 1        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.13%   |
| Kingston Technology                             | 1        | 0.13%   |
| Ensoniq                                         | 1        | 0.13%   |
| Dell                                            | 1        | 0.13%   |
| Blue Microphones                                | 1        | 0.13%   |
| BigBen Interactive                              | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                                     | 61       | 6.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 43       | 4.34%   |
| AMD Starship/Matisse HD Audio Controller                                          | 42       | 4.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 38       | 3.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 38       | 3.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 38       | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 37       | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 32       | 3.23%   |
| AMD FCH Azalia Controller                                                         | 31       | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 27       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 24       | 2.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 21       | 2.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 20       | 2.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 18       | 1.82%   |
| Intel 200 Series PCH HD Audio                                                     | 17       | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16       | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                        | 16       | 1.62%   |
| Nvidia MCP61 High Definition Audio                                                | 15       | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                                     | 15       | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 15       | 1.52%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 15       | 1.52%   |
| AMD Radeon High Definition Audio Controller                                       | 15       | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 14       | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 13       | 1.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 13       | 1.31%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 12       | 1.21%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 11       | 1.11%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 11       | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                                     | 10       | 1.01%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 10       | 1.01%   |
| Nvidia High Definition Audio Controller                                           | 9        | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                     | 7        | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                                     | 7        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                     | 7        | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7        | 0.71%   |
| AMD Navi 31 HDMI/DP Audio                                                         | 7        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                     | 6        | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6        | 0.61%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 111      | 37.25%  |
| Unknown             | 54       | 18.12%  |
| Samsung Electronics | 21       | 7.05%   |
| SK hynix            | 16       | 5.37%   |
| Patriot             | 16       | 5.37%   |
| Corsair             | 12       | 4.03%   |
| Crucial             | 11       | 3.69%   |
| G.Skill             | 7        | 2.35%   |
| Apacer              | 7        | 2.35%   |
| Transcend           | 6        | 2.01%   |
| Nanya Technology    | 6        | 2.01%   |
| Micron Technology   | 5        | 1.68%   |
| Silicon Power       | 4        | 1.34%   |
| A-DATA Technology   | 4        | 1.34%   |
| GeIL                | 3        | 1.01%   |
| Unknown             | 3        | 1.01%   |
| Elpida              | 2        | 0.67%   |
| Unifosa             | 1        | 0.34%   |
| Swissbit            | 1        | 0.34%   |
| Ramos Technology    | 1        | 0.34%   |
| Ramaxel Technology  | 1        | 0.34%   |
| Qimonda             | 1        | 0.34%   |
| Patriot Memory      | 1        | 0.34%   |
| Mushkin             | 1        | 0.34%   |
| KETECH              | 1        | 0.34%   |
| Exceleram           | 1        | 0.34%   |
| Aeneon              | 1        | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s     | 8        | 2.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 6        | 1.76%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 6        | 1.76%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s     | 6        | 1.76%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 5        | 1.47%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 4        | 1.18%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s | 4        | 1.18%   |
| Patriot RAM 3000 C16 Series 8GB DIMM DDR4 3200MT/s       | 4        | 1.18%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s    | 4        | 1.18%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 3        | 0.88%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                | 3        | 0.88%   |
| Samsung RAM M393B1K70CH0-CH9 8GB DIMM 1333MT/s           | 3        | 0.88%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s       | 3        | 0.88%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s     | 3        | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s       | 3        | 0.88%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s      | 3        | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 0.88%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s    | 3        | 0.88%   |
| Unknown                                                  | 3        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 0.59%   |
| Unknown RAM Module 4GB DIMM 667MT/s                      | 2        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 2        | 0.59%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 1GB DIMM 800MT/s                      | 2        | 0.59%   |
| Transcend RAM TS512MLK64V6H 4GB DIMM DDR3 1600MT/s       | 2        | 0.59%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s        | 2        | 0.59%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.59%   |
| Samsung RAM M393B1K70DH0-CH9 8GB DIMM DDR3 1333MT/s      | 2        | 0.59%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 2        | 0.59%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3               | 2        | 0.59%   |
| Patriot RAM PSD34G133381 4GB DIMM DDR3 1333MT/s          | 2        | 0.59%   |
| Micron RAM 9KSF25672AZ-1G4M1 2GB DIMM DDR3 1333MT/s      | 2        | 0.59%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 2        | 0.59%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 2        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 109      | 42.41%  |
| DDR3    | 82       | 31.91%  |
| Unknown | 28       | 10.89%  |
| DDR2    | 15       | 5.84%   |
| DDR5    | 13       | 5.06%   |
| SDRAM   | 6        | 2.33%   |
| DDR     | 3        | 1.17%   |
| LPDDR4  | 1        | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 242      | 95.65%  |
| SODIMM       | 9        | 3.56%   |
| Row Of Chips | 1        | 0.4%    |
| FB-DIMM      | 1        | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 90       | 30.61%  |
| 4096  | 73       | 24.83%  |
| 16384 | 50       | 17.01%  |
| 2048  | 47       | 15.99%  |
| 32768 | 19       | 6.46%   |
| 1024  | 13       | 4.42%   |
| 512   | 2        | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 46       | 15.28%  |
| 1600    | 44       | 14.62%  |
| 3600    | 21       | 6.98%   |
| 2667    | 19       | 6.31%   |
| 3200    | 18       | 5.98%   |
| 2400    | 17       | 5.65%   |
| 3733    | 16       | 5.32%   |
| 800     | 16       | 5.32%   |
| 2133    | 13       | 4.32%   |
| 667     | 12       | 3.99%   |
| 3400    | 11       | 3.65%   |
| 1866    | 8        | 2.66%   |
| 6000    | 6        | 1.99%   |
| 2666    | 6        | 1.99%   |
| 6400    | 3        | 1%      |
| 3933    | 3        | 1%      |
| 3466    | 3        | 1%      |
| 400     | 3        | 1%      |
| 5600    | 2        | 0.66%   |
| 4000    | 2        | 0.66%   |
| 3333    | 2        | 0.66%   |
| 3151    | 2        | 0.66%   |
| 3000    | 2        | 0.66%   |
| 2933    | 2        | 0.66%   |
| 2800    | 2        | 0.66%   |
| 1867    | 2        | 0.66%   |
| 1800    | 2        | 0.66%   |
| 1648    | 2        | 0.66%   |
| 1067    | 2        | 0.66%   |
| Unknown | 2        | 0.66%   |
| 6200    | 1        | 0.33%   |
| 5200    | 1        | 0.33%   |
| 4333    | 1        | 0.33%   |
| 3800    | 1        | 0.33%   |
| 3334    | 1        | 0.33%   |
| 2734    | 1        | 0.33%   |
| 2733    | 1        | 0.33%   |
| 2465    | 1        | 0.33%   |
| 2048    | 1        | 0.33%   |
| 2000    | 1        | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 10       | 50%     |
| Samsung Electronics   | 4        | 20%     |
| Canon                 | 3        | 15%     |
| Xerox                 | 1        | 5%      |
| Seiko Epson           | 1        | 5%      |
| Lexmark International | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| HP LaserJet 1010                           | 2        | 10%     |
| Xerox Phaser 3140 and 3155                 | 1        | 5%      |
| Seiko Epson L365 Series                    | 1        | 5%      |
| Samsung SCX-4623 Series                    | 1        | 5%      |
| Samsung SCX-3400 Series                    | 1        | 5%      |
| Samsung ML-216x Series Laser Printer       | 1        | 5%      |
| Samsung ML-1660 Series                     | 1        | 5%      |
| Lexmark International InkJet Color Printer | 1        | 5%      |
| HP LaserJet P2015 series                   | 1        | 5%      |
| HP LaserJet P2014                          | 1        | 5%      |
| HP LaserJet P1005                          | 1        | 5%      |
| HP LaserJet M14-M17                        | 1        | 5%      |
| HP LaserJet CP 1025                        | 1        | 5%      |
| HP LaserJet 1200                           | 1        | 5%      |
| HP LaserJet 1018                           | 1        | 5%      |
| HP HP LaserJet M101-M106                   | 1        | 5%      |
| Canon LiDE 300                             | 1        | 5%      |
| Canon LBP810                               | 1        | 5%      |
| Canon LBP2900                              | 1        | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 5        | 55.56%  |
| Mustek Systems     | 2        | 22.22%  |
| Ultima Electronics | 1        | 11.11%  |
| Hewlett-Packard    | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2        | 22.22%  |
| Canon CanoScan LiDE 100                                                               | 2        | 22.22%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 11.11%  |
| HP ScanJet 2200c                                                                      | 1        | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                                                         | 1        | 11.11%  |
| Canon CanoScan LiDE 210                                                               | 1        | 11.11%  |
| Canon CanoScan LiDE 120                                                               | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech                           | 33       | 39.76%  |
| Microdia                           | 10       | 12.05%  |
| KYE Systems (Mouse Systems)        | 8        | 9.64%   |
| Hewlett-Packard                    | 3        | 3.61%   |
| Aveo Technology                    | 3        | 3.61%   |
| Z-Star Microelectronics            | 2        | 2.41%   |
| Realtek Semiconductor              | 2        | 2.41%   |
| GEMBIRD                            | 2        | 2.41%   |
| Cubeternet                         | 2        | 2.41%   |
| Chicony Electronics                | 2        | 2.41%   |
| Arkmicro Technologies              | 2        | 2.41%   |
| YGTek                              | 1        | 1.2%    |
| Valve Software                     | 1        | 1.2%    |
| USB CAMERA                         | 1        | 1.2%    |
| Trust                              | 1        | 1.2%    |
| Sweex                              | 1        | 1.2%    |
| Sony                               | 1        | 1.2%    |
| Orbbec 3D Technology International | 1        | 1.2%    |
| NZXT                               | 1        | 1.2%    |
| Nokia Mobile Phones                | 1        | 1.2%    |
| Microsoft                          | 1        | 1.2%    |
| Dell                               | 1        | 1.2%    |
| Asuscom Network                    | 1        | 1.2%    |
| ARC International                  | 1        | 1.2%    |
| Apple                              | 1        | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 8        | 9.64%   |
| Microdia Camera                                   | 7        | 8.43%   |
| Logitech Webcam C170                              | 6        | 7.23%   |
| KYE Systems (Mouse Systems) FaceCam 1000X         | 3        | 3.61%   |
| Z-Star Venus USB2.0 Camera                        | 2        | 2.41%   |
| Realtek Thronmax Stream Go Pro Webcam             | 2        | 2.41%   |
| Microdia Webcam Vitade AF                         | 2        | 2.41%   |
| Logitech Webcam C200                              | 2        | 2.41%   |
| Logitech QuickCam Orbit/Sphere AF                 | 2        | 2.41%   |
| Logitech QuickCam Communicate MP/S5500            | 2        | 2.41%   |
| Logitech HD Webcam C525                           | 2        | 2.41%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 2.41%   |
| Logitech BRIO Ultra HD Webcam                     | 2        | 2.41%   |
| KYE Systems (Mouse Systems) Genius Webcam         | 2        | 2.41%   |
| HP HD-4110 Webcam                                 | 2        | 2.41%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 2        | 2.41%   |
| Aveo USB2.0 Camera                                | 2        | 2.41%   |
| Arkmicro USB2.0 PC CAMERA                         | 2        | 2.41%   |
| YGTek Webcam                                      | 1        | 1.2%    |
| Valve Software 3D Camera                          | 1        | 1.2%    |
| USB CAMERA USB CAMERA                             | 1        | 1.2%    |
| Trust Full HD Webcam                              | 1        | 1.2%    |
| Sweex USB keyboard                                | 1        | 1.2%    |
| Sony CEVCECM                                      | 1        | 1.2%    |
| Orbbec 3D International Astra Pro HD Camera       | 1        | 1.2%    |
| NZXT NZXT Signal HD60 Video                       | 1        | 1.2%    |
| Nokia Mobile Phones Lumia 640 Phone               | 1        | 1.2%    |
| Microsoft LifeCam VX-800                          | 1        | 1.2%    |
| Microdia USB 2.0 Camera                           | 1        | 1.2%    |
| Logitech Webcam Pro 9000                          | 1        | 1.2%    |
| Logitech Webcam C310                              | 1        | 1.2%    |
| Logitech Webcam C210                              | 1        | 1.2%    |
| Logitech Webcam C110                              | 1        | 1.2%    |
| Logitech StreamCam                                | 1        | 1.2%    |
| Logitech HD Webcam C615                           | 1        | 1.2%    |
| Logitech C920 PRO HD Webcam                       | 1        | 1.2%    |
| KYE Systems (Mouse Systems) Genius FaceCam 320    | 1        | 1.2%    |
| KYE Systems (Mouse Systems) FaceCam 2020          | 1        | 1.2%    |
| KYE Systems (Mouse Systems) Eye 320               | 1        | 1.2%    |
| HP Webcam HD 3300                                 | 1        | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 1        | 50%     |
| Microsoft | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Synaptics  WBDI              | 1        | 50%     |
| Microsoft Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 14       | 77.78%  |
| Alcor Micro           | 2        | 11.11%  |
| Precise Biometrics    | 1        | 5.56%   |
| OmniKey               | 1        | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 14       | 77.78%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2        | 11.11%  |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader | 1        | 5.56%   |
| OmniKey CardMan 3021 / 3121                                | 1        | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 434      | 86.8%   |
| 1     | 60       | 12%     |
| 2     | 5        | 1%      |
| 3     | 1        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 23       | 32.86%  |
| Chipcard                 | 14       | 20%     |
| Net/wireless             | 13       | 18.57%  |
| Unassigned class         | 4        | 5.71%   |
| Sound                    | 2        | 2.86%   |
| Fingerprint reader       | 2        | 2.86%   |
| Communication controller | 2        | 2.86%   |
| Card reader              | 2        | 2.86%   |
| Camera                   | 2        | 2.86%   |
| Storage/ide              | 1        | 1.43%   |
| Network                  | 1        | 1.43%   |
| Multimedia controller    | 1        | 1.43%   |
| Modem                    | 1        | 1.43%   |
| Dvb card                 | 1        | 1.43%   |
| Bluetooth                | 1        | 1.43%   |

