SteamOS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for SteamOS.

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

Total: 387

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [4a16cabb34](https://linux-hardware.org/?probe=4a16cabb34) | Dec 31, 2025 |
| Intel         | X99                         | [47b3587e79](https://linux-hardware.org/?probe=47b3587e79) | Dec 26, 2025 |
| ASUSTek       | B650E MAX GAMING WIFI       | [e90c22bad5](https://linux-hardware.org/?probe=e90c22bad5) | Dec 21, 2025 |
| Intel         | X99                         | [c5d974af69](https://linux-hardware.org/?probe=c5d974af69) | Dec 19, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [73c1604cc2](https://linux-hardware.org/?probe=73c1604cc2) | Dec 18, 2025 |
| JGINYUE       | B650I Night Devil Ver:      | [47e8b9dad6](https://linux-hardware.org/?probe=47e8b9dad6) | Dec 17, 2025 |
| GEEKOM        | A8                          | [5b70209376](https://linux-hardware.org/?probe=5b70209376) | Dec 17, 2025 |
| ASRock        | X870 Pro RS WiFi            | [3300b18294](https://linux-hardware.org/?probe=3300b18294) | Dec 16, 2025 |
| Gigabyte      | H110M-S2H-CF                | [1b15fa788c](https://linux-hardware.org/?probe=1b15fa788c) | Dec 16, 2025 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [8729442363](https://linux-hardware.org/?probe=8729442363) | Dec 14, 2025 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [ae587fc91d](https://linux-hardware.org/?probe=ae587fc91d) | Dec 11, 2025 |
| GEEKOM        | A8                          | [797f34749e](https://linux-hardware.org/?probe=797f34749e) | Dec 10, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | [c7b9a0ba42](https://linux-hardware.org/?probe=c7b9a0ba42) | Dec 06, 2025 |
| Dell          | 0WMJ54 A00                  | [75775e7ec0](https://linux-hardware.org/?probe=75775e7ec0) | Dec 02, 2025 |
| Dell          | 0WMJ54 A00                  | [f42c5d52a5](https://linux-hardware.org/?probe=f42c5d52a5) | Dec 02, 2025 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [32f8ed103f](https://linux-hardware.org/?probe=32f8ed103f) | Dec 01, 2025 |
| ASUSTek       | ROG STRIX B850-I GAMING ... | [90319259f1](https://linux-hardware.org/?probe=90319259f1) | Dec 01, 2025 |
| MSI           | A520M-A PRO                 | [f586fe0edc](https://linux-hardware.org/?probe=f586fe0edc) | Nov 30, 2025 |
| JGINYUE       | B550i-GAMING                | [207cee83f7](https://linux-hardware.org/?probe=207cee83f7) | Nov 29, 2025 |
| Shenzhen M... | DRFXI                       | [a38c3b9d67](https://linux-hardware.org/?probe=a38c3b9d67) | Nov 29, 2025 |
| ASRock        | B450M Steel Legend          | [3b46b84c5a](https://linux-hardware.org/?probe=3b46b84c5a) | Nov 28, 2025 |
| Unknown       | Unknown                     | [418a3a32d5](https://linux-hardware.org/?probe=418a3a32d5) | Nov 28, 2025 |
| MSI           | B760 GAMING PLUS WIFI       | [302266c401](https://linux-hardware.org/?probe=302266c401) | Nov 26, 2025 |
| BCM Advanc... | MX610H                      | [e01c007db7](https://linux-hardware.org/?probe=e01c007db7) | Nov 26, 2025 |
| Gigabyte      | Z97-D3H-CF                  | [ed51c183cb](https://linux-hardware.org/?probe=ed51c183cb) | Nov 26, 2025 |
| ASRock        | A320M-HD                    | [93730d237f](https://linux-hardware.org/?probe=93730d237f) | Nov 25, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [2364d1426d](https://linux-hardware.org/?probe=2364d1426d) | Nov 23, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [5abdb520b1](https://linux-hardware.org/?probe=5abdb520b1) | Nov 23, 2025 |
| Gigabyte      | Z97MX-Gaming 5              | [0867935d51](https://linux-hardware.org/?probe=0867935d51) | Nov 22, 2025 |
| Gigabyte      | Z97MX-Gaming 5              | [3448eb22e1](https://linux-hardware.org/?probe=3448eb22e1) | Nov 22, 2025 |
| Gigabyte      | B560 AORUS PRO AX           | [c0f3137beb](https://linux-hardware.org/?probe=c0f3137beb) | Nov 21, 2025 |
| ASUSTek       | TUF Gaming B650-E WIFI      | [ac686e165a](https://linux-hardware.org/?probe=ac686e165a) | Nov 19, 2025 |
| MSI           | B150M Night Elf             | [ef694ca58f](https://linux-hardware.org/?probe=ef694ca58f) | Nov 18, 2025 |
| SZQFTX        | MI2-SC                      | [0cfd60f82b](https://linux-hardware.org/?probe=0cfd60f82b) | Nov 16, 2025 |
| SZQFTX        | MI2-SC                      | [6cde1b6385](https://linux-hardware.org/?probe=6cde1b6385) | Nov 15, 2025 |
| Gigabyte      | A520M K V2                  | [5745301eda](https://linux-hardware.org/?probe=5745301eda) | Nov 15, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [048590a8e2](https://linux-hardware.org/?probe=048590a8e2) | Nov 14, 2025 |
| ASUSTek       | P8Z77-I DELUXE/WD           | [17e343b434](https://linux-hardware.org/?probe=17e343b434) | Nov 14, 2025 |
| Gigabyte      | B550M K                     | [809be47443](https://linux-hardware.org/?probe=809be47443) | Nov 12, 2025 |
| ASRock        | A520M-ITX/ac                | [722d690bbe](https://linux-hardware.org/?probe=722d690bbe) | Oct 30, 2025 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [02b749447c](https://linux-hardware.org/?probe=02b749447c) | Oct 29, 2025 |
| AZW           | SER V1.0                    | [7f7f994bbb](https://linux-hardware.org/?probe=7f7f994bbb) | Oct 28, 2025 |
| Gigabyte      | AB350M-DS3H-CF              | [633d347475](https://linux-hardware.org/?probe=633d347475) | Oct 23, 2025 |
| Gigabyte      | A520M K V2                  | [172cf40949](https://linux-hardware.org/?probe=172cf40949) | Oct 22, 2025 |
| Gigabyte      | A520M K V2                  | [ec251888a2](https://linux-hardware.org/?probe=ec251888a2) | Oct 22, 2025 |
| ASRock        | B850 Steel Legend WiFi      | [33b0097bba](https://linux-hardware.org/?probe=33b0097bba) | Oct 17, 2025 |
| ASRock        | B850 Steel Legend WiFi      | [7080e65869](https://linux-hardware.org/?probe=7080e65869) | Oct 17, 2025 |
| ASUSTek       | Maximus VII RANGER          | [cb820ad801](https://linux-hardware.org/?probe=cb820ad801) | Oct 04, 2025 |
| ASRock        | X300-ITX                    | [dd16eb8170](https://linux-hardware.org/?probe=dd16eb8170) | Sep 24, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [87d2d3beac](https://linux-hardware.org/?probe=87d2d3beac) | Sep 20, 2025 |
| ASRock        | AB350M Pro4                 | [fdd91a2583](https://linux-hardware.org/?probe=fdd91a2583) | Sep 03, 2025 |
| Gigabyte      | MD90-FS0-ZB V102            | [7a4288dd07](https://linux-hardware.org/?probe=7a4288dd07) | Aug 30, 2025 |
| Gigabyte      | MD90-FS0-ZB V102            | [1ddc1dc063](https://linux-hardware.org/?probe=1ddc1dc063) | Aug 30, 2025 |
| ASUSTek       | Pro B550M-C                 | [0ba93b65c5](https://linux-hardware.org/?probe=0ba93b65c5) | Aug 23, 2025 |
| ASUSTek       | PRIME B450M-K II            | [42df288e33](https://linux-hardware.org/?probe=42df288e33) | Aug 21, 2025 |
| ASUSTek       | PRIME B450M-K II            | [34c67fdaee](https://linux-hardware.org/?probe=34c67fdaee) | Aug 21, 2025 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [48bc848051](https://linux-hardware.org/?probe=48bc848051) | Aug 19, 2025 |
| Apple         | Mac-F221BEC8                | [02f2c66f3b](https://linux-hardware.org/?probe=02f2c66f3b) | Aug 10, 2025 |
| MSI           | X470 GAMING PLUS MAX        | [690ec667f5](https://linux-hardware.org/?probe=690ec667f5) | Aug 10, 2025 |
| Apple         | Mac-F221BEC8                | [a1300c7e25](https://linux-hardware.org/?probe=a1300c7e25) | Aug 10, 2025 |
| Intel         | B360                        | [8e246fde4d](https://linux-hardware.org/?probe=8e246fde4d) | Aug 08, 2025 |
| ASUSTek       | PRIME B450M-K II            | [c70418950f](https://linux-hardware.org/?probe=c70418950f) | Aug 07, 2025 |
| ASUSTek       | PRIME H510M-A               | [576ca33a27](https://linux-hardware.org/?probe=576ca33a27) | Aug 06, 2025 |
| ASUSTek       | PRIME H510M-A               | [90d167cc49](https://linux-hardware.org/?probe=90d167cc49) | Aug 06, 2025 |
| Shenzhen M... | DRBAA                       | [3835a9f0e1](https://linux-hardware.org/?probe=3835a9f0e1) | Aug 04, 2025 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [7ba6274a3e](https://linux-hardware.org/?probe=7ba6274a3e) | Aug 03, 2025 |
| Shenzhen M... | DRFXI                       | [5c6dec04be](https://linux-hardware.org/?probe=5c6dec04be) | Aug 03, 2025 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [c21d3122a0](https://linux-hardware.org/?probe=c21d3122a0) | Aug 03, 2025 |
| Gigabyte      | B550M AORUS ELITE           | [f27ff982b9](https://linux-hardware.org/?probe=f27ff982b9) | Aug 02, 2025 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2112268268](https://linux-hardware.org/?probe=2112268268) | Jul 29, 2025 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [4267812a01](https://linux-hardware.org/?probe=4267812a01) | Jul 29, 2025 |
| Gigabyte      | A320M-S2H V2-CF             | [48f4f8bef0](https://linux-hardware.org/?probe=48f4f8bef0) | Jul 22, 2025 |
| ASUSTek       | PRIME X399-A                | [c5b6159145](https://linux-hardware.org/?probe=c5b6159145) | Jul 20, 2025 |
| ASUSTek       | CROSSHAIR VI HERO           | [01b5323940](https://linux-hardware.org/?probe=01b5323940) | Jul 19, 2025 |
| Unknown       | Unknown                     | [39ef429300](https://linux-hardware.org/?probe=39ef429300) | Jul 18, 2025 |
| HP            | 8399                        | [0d7754f120](https://linux-hardware.org/?probe=0d7754f120) | Jul 14, 2025 |
| HP            | 8399                        | [5e100cf2bb](https://linux-hardware.org/?probe=5e100cf2bb) | Jul 13, 2025 |
| ASRock        | B550M Pro4                  | [1f3f32f6a8](https://linux-hardware.org/?probe=1f3f32f6a8) | Jul 11, 2025 |
| ASRock        | B550M Pro4                  | [07c244fff5](https://linux-hardware.org/?probe=07c244fff5) | Jul 11, 2025 |
| Unknown       | Unknown                     | [f0fbca2cd7](https://linux-hardware.org/?probe=f0fbca2cd7) | Jul 10, 2025 |
| Gigabyte      | B450M GAMING                | [c776575009](https://linux-hardware.org/?probe=c776575009) | Jul 04, 2025 |
| ASUSTek       | Maximus VII RANGER          | [4c3c9aed8f](https://linux-hardware.org/?probe=4c3c9aed8f) | Jun 29, 2025 |
| NZXT          | N7 B550                     | [dd7aee4838](https://linux-hardware.org/?probe=dd7aee4838) | Jun 28, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [8e9faeaf93](https://linux-hardware.org/?probe=8e9faeaf93) | Jun 28, 2025 |
| Gigabyte      | X299 AORUS Gaming 7         | [205b632be8](https://linux-hardware.org/?probe=205b632be8) | Jun 27, 2025 |
| MSI           | X470 GAMING PLUS MAX        | [d8db2c6474](https://linux-hardware.org/?probe=d8db2c6474) | Jun 26, 2025 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5cb951c929](https://linux-hardware.org/?probe=5cb951c929) | Jun 26, 2025 |
| ASRock        | X570 Phantom Gaming-ITX/... | [315dd31abe](https://linux-hardware.org/?probe=315dd31abe) | Jun 24, 2025 |
| MSI           | X470 GAMING PLUS MAX        | [90bcc018e4](https://linux-hardware.org/?probe=90bcc018e4) | Jun 23, 2025 |
| ASUSTek       | TUF Gaming B460-PLUS        | [7fe5bf1cd3](https://linux-hardware.org/?probe=7fe5bf1cd3) | Jun 23, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | [f0c49d6bf5](https://linux-hardware.org/?probe=f0c49d6bf5) | Jun 20, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | [8172c02004](https://linux-hardware.org/?probe=8172c02004) | Jun 20, 2025 |
| Gigabyte      | A320M-H-CF                  | [f24ef2df9a](https://linux-hardware.org/?probe=f24ef2df9a) | Jun 19, 2025 |
| ASUSTek       | Pro WS X570-ACE             | [4e64fed9f5](https://linux-hardware.org/?probe=4e64fed9f5) | Jun 19, 2025 |
| ASUSTek       | Pro WS X570-ACE             | [4bfd156e03](https://linux-hardware.org/?probe=4bfd156e03) | Jun 18, 2025 |
| Gigabyte      | Z490M GAMING X              | [4acc0b7472](https://linux-hardware.org/?probe=4acc0b7472) | Jun 17, 2025 |
| MSI           | B850 GAMING PLUS WIFI       | [9236035d01](https://linux-hardware.org/?probe=9236035d01) | Jun 17, 2025 |
| MSI           | X570-A PRO                  | [0e08d996a1](https://linux-hardware.org/?probe=0e08d996a1) | Jun 14, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [b2c7cc6a93](https://linux-hardware.org/?probe=b2c7cc6a93) | Jun 12, 2025 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [08a817eb9b](https://linux-hardware.org/?probe=08a817eb9b) | Jun 10, 2025 |
| MSI           | A520M PRO                   | [f0ae8405e4](https://linux-hardware.org/?probe=f0ae8405e4) | Jun 09, 2025 |
| MSI           | A520M PRO                   | [0c51e08e21](https://linux-hardware.org/?probe=0c51e08e21) | Jun 08, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [45a6cfb759](https://linux-hardware.org/?probe=45a6cfb759) | Jun 08, 2025 |
| HP            | 8949 11                     | [df435e7379](https://linux-hardware.org/?probe=df435e7379) | Jun 08, 2025 |
| HP            | 8949 11                     | [c4fac816a8](https://linux-hardware.org/?probe=c4fac816a8) | Jun 08, 2025 |
| ASUSTek       | PRIME X399-A                | [4007eebb2b](https://linux-hardware.org/?probe=4007eebb2b) | Jun 05, 2025 |
| Unknown       | Unknown                     | [f2034596cd](https://linux-hardware.org/?probe=f2034596cd) | Jun 05, 2025 |
| Intel         | HM570                       | [3a14072ee1](https://linux-hardware.org/?probe=3a14072ee1) | Jun 03, 2025 |
| Gigabyte      | B550 GAMING X V2            | [bdc6ea4bce](https://linux-hardware.org/?probe=bdc6ea4bce) | May 31, 2025 |
| Intel         | H61                         | [88855a96a5](https://linux-hardware.org/?probe=88855a96a5) | May 19, 2025 |
| ASRock        | B650 PG Lightning           | [9f3a36a83f](https://linux-hardware.org/?probe=9f3a36a83f) | May 17, 2025 |
| ASRock        | B450M Pro4 R2.0             | [3a9f8fff17](https://linux-hardware.org/?probe=3a9f8fff17) | May 04, 2025 |
| Shenzhen M... | F7BFC                       | [f7a397ee79](https://linux-hardware.org/?probe=f7a397ee79) | May 04, 2025 |
| ASRock        | B550M Pro4                  | [412b8c06ae](https://linux-hardware.org/?probe=412b8c06ae) | Apr 29, 2025 |
| Shenzhen M... | DRBAA                       | [546bb2e19d](https://linux-hardware.org/?probe=546bb2e19d) | Apr 24, 2025 |
| Unknown       | DELTA-H61M2K                | [60ba0d4cb5](https://linux-hardware.org/?probe=60ba0d4cb5) | Apr 21, 2025 |
| Gigabyte      | B550 GAMING X V2            | [3ecdb71df0](https://linux-hardware.org/?probe=3ecdb71df0) | Apr 19, 2025 |
| Gigabyte      | B550 GAMING X V2            | [63cb935086](https://linux-hardware.org/?probe=63cb935086) | Apr 18, 2025 |
| ASUSTek       | Maximus VII RANGER          | [9d3c2e81e6](https://linux-hardware.org/?probe=9d3c2e81e6) | Apr 15, 2025 |
| Medion        | H77H2-EM V1.0               | [eb131dbd89](https://linux-hardware.org/?probe=eb131dbd89) | Apr 13, 2025 |
| MSI           | B450M PRO-VDH MAX           | [6dab48b31a](https://linux-hardware.org/?probe=6dab48b31a) | Apr 12, 2025 |
| ASRock        | B650I Lightning WiFi        | [9d6979249a](https://linux-hardware.org/?probe=9d6979249a) | Apr 09, 2025 |
| ASRock        | B650I Lightning WiFi        | [dc728dec0e](https://linux-hardware.org/?probe=dc728dec0e) | Apr 09, 2025 |
| Gigabyte      | H370 HD3-CF                 | [447c926b8d](https://linux-hardware.org/?probe=447c926b8d) | Apr 09, 2025 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [1d8c101bf4](https://linux-hardware.org/?probe=1d8c101bf4) | Apr 04, 2025 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [75b1e9a3ab](https://linux-hardware.org/?probe=75b1e9a3ab) | Apr 04, 2025 |
| Gigabyte      | B550M AORUS ELITE           | [c7970f2d37](https://linux-hardware.org/?probe=c7970f2d37) | Apr 02, 2025 |
| MACHINIST     | X99 PR9                     | [8fa8bfd058](https://linux-hardware.org/?probe=8fa8bfd058) | Mar 31, 2025 |
| ASUSTek       | ROG Maximus XI CODE         | [8a0ddfbcb1](https://linux-hardware.org/?probe=8a0ddfbcb1) | Mar 29, 2025 |
| ASRock        | B460M-HDV                   | [8f0c5498b4](https://linux-hardware.org/?probe=8f0c5498b4) | Mar 28, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [a4e602c833](https://linux-hardware.org/?probe=a4e602c833) | Mar 27, 2025 |
| ASUSTek       | Z87-K                       | [0206d6854b](https://linux-hardware.org/?probe=0206d6854b) | Mar 24, 2025 |
| Colorful T... | H410M-T PRO V20             | [5c452e1155](https://linux-hardware.org/?probe=5c452e1155) | Mar 20, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS        | [2b659c9684](https://linux-hardware.org/?probe=2b659c9684) | Mar 16, 2025 |
| ASRock        | B450M Steel Legend          | [3eb48dabcc](https://linux-hardware.org/?probe=3eb48dabcc) | Mar 15, 2025 |
| GMKtec        | NucBox K8 Plus              | [9d8e871230](https://linux-hardware.org/?probe=9d8e871230) | Mar 13, 2025 |
| ASRock        | X300M-STX                   | [6c18f177fc](https://linux-hardware.org/?probe=6c18f177fc) | Mar 06, 2025 |
| ASUSTek       | PRIME X399-A                | [6fc4077f0d](https://linux-hardware.org/?probe=6fc4077f0d) | Feb 17, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a2becd0f1d](https://linux-hardware.org/?probe=a2becd0f1d) | Feb 11, 2025 |
| ASRock        | AB350M-HDV R3.0             | [ed028711a5](https://linux-hardware.org/?probe=ed028711a5) | Feb 04, 2025 |
| ASRock        | AB350M-HDV R3.0             | [4cdaef61ed](https://linux-hardware.org/?probe=4cdaef61ed) | Feb 02, 2025 |
| ASRock        | AB350M Pro4                 | [2143ee6d5f](https://linux-hardware.org/?probe=2143ee6d5f) | Jan 27, 2025 |
| ASUSTek       | PRIME B550M-A               | [23d9b50780](https://linux-hardware.org/?probe=23d9b50780) | Jan 26, 2025 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [291a2fd88a](https://linux-hardware.org/?probe=291a2fd88a) | Jan 26, 2025 |
| ASRock        | Z270 Taichi                 | [43fe7ef6b7](https://linux-hardware.org/?probe=43fe7ef6b7) | Jan 25, 2025 |
| ASUSTek       | PRIME B350-PLUS             | [a9556c41f1](https://linux-hardware.org/?probe=a9556c41f1) | Jan 13, 2025 |
| ASUSTek       | PRIME B350-PLUS             | [b4ce556e1a](https://linux-hardware.org/?probe=b4ce556e1a) | Jan 11, 2025 |
| ASUSTek       | PRIME B350-PLUS             | [cb38e7215b](https://linux-hardware.org/?probe=cb38e7215b) | Dec 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [14584a3f16](https://linux-hardware.org/?probe=14584a3f16) | Dec 01, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [b1fc0f41f0](https://linux-hardware.org/?probe=b1fc0f41f0) | Nov 19, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [db873cebfd](https://linux-hardware.org/?probe=db873cebfd) | Nov 08, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [6481acc825](https://linux-hardware.org/?probe=6481acc825) | Oct 10, 2024 |
| Dell          | 0FDY5C A00                  | [2975c3986e](https://linux-hardware.org/?probe=2975c3986e) | Oct 02, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9e6105fdd5](https://linux-hardware.org/?probe=9e6105fdd5) | Sep 27, 2024 |
| Lenovo        | SDK0E50510 WIN 262507025... | [26d5a61655](https://linux-hardware.org/?probe=26d5a61655) | Sep 25, 2024 |
| ASUSTek       | PRIME B450M-A II            | [07dc4c9a19](https://linux-hardware.org/?probe=07dc4c9a19) | Sep 20, 2024 |
| QIYIDA        | ED4 V1.1                    | [57a88e488a](https://linux-hardware.org/?probe=57a88e488a) | Sep 19, 2024 |
| ASUSTek       | GR8 II-K                    | [d7a4d66200](https://linux-hardware.org/?probe=d7a4d66200) | Sep 16, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [72fe68b845](https://linux-hardware.org/?probe=72fe68b845) | Sep 12, 2024 |
| Unknown       | Unknown                     | [0e77bc77fb](https://linux-hardware.org/?probe=0e77bc77fb) | Sep 09, 2024 |
| Unknown       | Unknown                     | [6ea3fd02fa](https://linux-hardware.org/?probe=6ea3fd02fa) | Sep 09, 2024 |
| Dell          | 0KWVT8 A03                  | [737215a158](https://linux-hardware.org/?probe=737215a158) | Sep 06, 2024 |
| Intel         | X99                         | [cb1938142e](https://linux-hardware.org/?probe=cb1938142e) | Sep 04, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [709c1de688](https://linux-hardware.org/?probe=709c1de688) | Sep 03, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [07e82620c8](https://linux-hardware.org/?probe=07e82620c8) | Sep 01, 2024 |
| ASRock        | AB350M Pro4                 | [cb21643ddb](https://linux-hardware.org/?probe=cb21643ddb) | Sep 01, 2024 |
| ASRock        | AB350M Pro4                 | [07d5926eb0](https://linux-hardware.org/?probe=07d5926eb0) | Aug 31, 2024 |
| MSI           | MPG Z790I EDGE WIFI         | [befece1a07](https://linux-hardware.org/?probe=befece1a07) | Aug 28, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [ff71054b4c](https://linux-hardware.org/?probe=ff71054b4c) | Aug 20, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [1cceda0c67](https://linux-hardware.org/?probe=1cceda0c67) | Aug 20, 2024 |
| MSI           | MAG B550M MORTAR            | [b573981587](https://linux-hardware.org/?probe=b573981587) | Aug 19, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [0182b82b41](https://linux-hardware.org/?probe=0182b82b41) | Aug 17, 2024 |
| Gigabyte      | B550M DS3H                  | [6866176fe2](https://linux-hardware.org/?probe=6866176fe2) | Aug 14, 2024 |
| Gigabyte      | B550M DS3H                  | [bdd81784d4](https://linux-hardware.org/?probe=bdd81784d4) | Aug 14, 2024 |
| JGINYUE       | B450I-GAMING Ver:1.1        | [a51ecd44f8](https://linux-hardware.org/?probe=a51ecd44f8) | Aug 05, 2024 |
| Shenzhen M... | F7BAA                       | [f997d4444d](https://linux-hardware.org/?probe=f997d4444d) | Aug 04, 2024 |
| ASRock        | B550M-C                     | [ff06ba744d](https://linux-hardware.org/?probe=ff06ba744d) | Aug 02, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [b84f2e45ff](https://linux-hardware.org/?probe=b84f2e45ff) | Aug 02, 2024 |
| Lenovo        | 364A                        | [133e44eaa4](https://linux-hardware.org/?probe=133e44eaa4) | Jul 29, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a3a0bfc94d](https://linux-hardware.org/?probe=a3a0bfc94d) | Jul 23, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fc4b11232b](https://linux-hardware.org/?probe=fc4b11232b) | Jul 20, 2024 |
| ASRock        | B650M Pro RS WiFi           | [361baaba70](https://linux-hardware.org/?probe=361baaba70) | Jul 20, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [1b64f2a6c6](https://linux-hardware.org/?probe=1b64f2a6c6) | Jul 19, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e53dd4acab](https://linux-hardware.org/?probe=e53dd4acab) | Jul 19, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [6f8fcf391e](https://linux-hardware.org/?probe=6f8fcf391e) | Jul 19, 2024 |
| Gigabyte      | B85M-D3H                    | [2050081e07](https://linux-hardware.org/?probe=2050081e07) | Jul 15, 2024 |
| Gigabyte      | B85M-D3H                    | [78db81d92d](https://linux-hardware.org/?probe=78db81d92d) | Jul 15, 2024 |
| Shenzhen M... | F7BAA                       | [47f43bfb0b](https://linux-hardware.org/?probe=47f43bfb0b) | Jul 12, 2024 |
| ASRock        | B360M Xtreme                | [77c855ffba](https://linux-hardware.org/?probe=77c855ffba) | Jul 10, 2024 |
| Gigabyte      | B450M GAMING                | [18ea2c08bb](https://linux-hardware.org/?probe=18ea2c08bb) | Jul 09, 2024 |
| MSI           | B450 TOMAHAWK               | [2938398b92](https://linux-hardware.org/?probe=2938398b92) | Jul 08, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dcb993f549](https://linux-hardware.org/?probe=dcb993f549) | Jul 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [70a230bac1](https://linux-hardware.org/?probe=70a230bac1) | Jul 02, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8b7d65a86c](https://linux-hardware.org/?probe=8b7d65a86c) | Jul 02, 2024 |
| ASUSTek       | PRIME A320M-K               | [5f9980bb04](https://linux-hardware.org/?probe=5f9980bb04) | Jun 25, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1758fea944](https://linux-hardware.org/?probe=1758fea944) | Jun 24, 2024 |
| Intel         | X79v2.72 KD V2.0            | [3e1bbdccc8](https://linux-hardware.org/?probe=3e1bbdccc8) | Jun 20, 2024 |
| ASRock        | B660M PG Riptide            | [0eb75d61c6](https://linux-hardware.org/?probe=0eb75d61c6) | May 22, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [810351e380](https://linux-hardware.org/?probe=810351e380) | May 19, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [e10a369f92](https://linux-hardware.org/?probe=e10a369f92) | May 14, 2024 |
| Gigabyte      | B450M GAMING                | [dc7364667b](https://linux-hardware.org/?probe=dc7364667b) | May 05, 2024 |
| ASRock        | B760M PG Lightning/D4       | [50c91b7d78](https://linux-hardware.org/?probe=50c91b7d78) | May 03, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [4ffacbaeac](https://linux-hardware.org/?probe=4ffacbaeac) | Apr 25, 2024 |
| ASUSTek       | PRIME A320M-K               | [97e9e0c7a1](https://linux-hardware.org/?probe=97e9e0c7a1) | Apr 13, 2024 |
| Gigabyte      | B450M GAMING                | [d0241d517a](https://linux-hardware.org/?probe=d0241d517a) | Apr 08, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | [d0447bf92e](https://linux-hardware.org/?probe=d0447bf92e) | Apr 06, 2024 |
| ASRock        | B450M Pro4-F                | [c70e4f20eb](https://linux-hardware.org/?probe=c70e4f20eb) | Apr 05, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3fe2ef5687](https://linux-hardware.org/?probe=3fe2ef5687) | Apr 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [24108983ab](https://linux-hardware.org/?probe=24108983ab) | Apr 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | [1fb1798295](https://linux-hardware.org/?probe=1fb1798295) | Mar 30, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [1cda914d9f](https://linux-hardware.org/?probe=1cda914d9f) | Mar 27, 2024 |
| Gigabyte      | A620M GAMING X AX           | [95dabe0b93](https://linux-hardware.org/?probe=95dabe0b93) | Mar 17, 2024 |
| Gigabyte      | A620M GAMING X AX           | [ac8a1cf30d](https://linux-hardware.org/?probe=ac8a1cf30d) | Mar 16, 2024 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [853a2babec](https://linux-hardware.org/?probe=853a2babec) | Mar 16, 2024 |
| QIYIDA        | ED4 V1.1                    | [cbfcb37d83](https://linux-hardware.org/?probe=cbfcb37d83) | Mar 06, 2024 |
| ASRock        | B550M Steel Legend          | [ff01bc4e69](https://linux-hardware.org/?probe=ff01bc4e69) | Mar 03, 2024 |
| ASUSTek       | Z170-A                      | [5c7cfb2969](https://linux-hardware.org/?probe=5c7cfb2969) | Mar 02, 2024 |
| Dell          | 042P49 A02                  | [721c874400](https://linux-hardware.org/?probe=721c874400) | Mar 02, 2024 |
| Gigabyte      | H170M-DS3H-CF               | [e9d405fea6](https://linux-hardware.org/?probe=e9d405fea6) | Mar 02, 2024 |
| Gigabyte      | H170M-DS3H-CF               | [c95130db9f](https://linux-hardware.org/?probe=c95130db9f) | Mar 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [b8d705b208](https://linux-hardware.org/?probe=b8d705b208) | Feb 23, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [04b45ee685](https://linux-hardware.org/?probe=04b45ee685) | Feb 21, 2024 |
| Gigabyte      | A520I AC                    | [e0d169ccee](https://linux-hardware.org/?probe=e0d169ccee) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2c5e1e36f8](https://linux-hardware.org/?probe=2c5e1e36f8) | Feb 12, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [63ed84550f](https://linux-hardware.org/?probe=63ed84550f) | Feb 08, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [1e4f204b76](https://linux-hardware.org/?probe=1e4f204b76) | Feb 08, 2024 |
| QIYIDA        | ED4 V1.1                    | [3583de3c82](https://linux-hardware.org/?probe=3583de3c82) | Jan 30, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [b4510875e8](https://linux-hardware.org/?probe=b4510875e8) | Jan 28, 2024 |
| ASUSTek       | SABERTOOTH Z170 S           | [953ea23870](https://linux-hardware.org/?probe=953ea23870) | Jan 19, 2024 |
| MSI           | H310M PRO-VD                | [3cdbce90e0](https://linux-hardware.org/?probe=3cdbce90e0) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [ffe6ae701f](https://linux-hardware.org/?probe=ffe6ae701f) | Jan 15, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [79504ec34b](https://linux-hardware.org/?probe=79504ec34b) | Jan 09, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [9c61eb5bab](https://linux-hardware.org/?probe=9c61eb5bab) | Jan 07, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [c6cd1c43ba](https://linux-hardware.org/?probe=c6cd1c43ba) | Dec 29, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [b5b5857360](https://linux-hardware.org/?probe=b5b5857360) | Dec 26, 2023 |
| ASRock        | AB350M-HDV                  | [2860ba102d](https://linux-hardware.org/?probe=2860ba102d) | Dec 18, 2023 |
| ASRock        | AB350M-HDV                  | [8d45a13b61](https://linux-hardware.org/?probe=8d45a13b61) | Dec 17, 2023 |
| Gigabyte      | B560M DS3H V2               | [2fa2dbdf4a](https://linux-hardware.org/?probe=2fa2dbdf4a) | Dec 06, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [a0e082b7d2](https://linux-hardware.org/?probe=a0e082b7d2) | Dec 01, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [532f8ccb97](https://linux-hardware.org/?probe=532f8ccb97) | Nov 27, 2023 |
| HP            | 89D8 SMVB                   | [e5bd9d36f3](https://linux-hardware.org/?probe=e5bd9d36f3) | Nov 25, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [829e6fdd78](https://linux-hardware.org/?probe=829e6fdd78) | Nov 23, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [887bb8aabe](https://linux-hardware.org/?probe=887bb8aabe) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [32e985afeb](https://linux-hardware.org/?probe=32e985afeb) | Nov 21, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [e723e12a01](https://linux-hardware.org/?probe=e723e12a01) | Nov 19, 2023 |
| Gigabyte      | B450M GAMING                | [33064ccfdf](https://linux-hardware.org/?probe=33064ccfdf) | Nov 14, 2023 |
| MSI           | Z270 PC MATE                | [e53ba2625b](https://linux-hardware.org/?probe=e53ba2625b) | Nov 09, 2023 |
| Gigabyte      | B450M GAMING                | [d788a3221f](https://linux-hardware.org/?probe=d788a3221f) | Nov 08, 2023 |
| ASRock        | B550M Pro4                  | [665120f441](https://linux-hardware.org/?probe=665120f441) | Nov 07, 2023 |
| ASRock        | B450 Gaming K4              | [166a9aee87](https://linux-hardware.org/?probe=166a9aee87) | Nov 06, 2023 |
| HP            | 89D8 SMVB                   | [3672a7681b](https://linux-hardware.org/?probe=3672a7681b) | Oct 24, 2023 |
| Shenzhen M... | F7BRC                       | [f61616bfcb](https://linux-hardware.org/?probe=f61616bfcb) | Oct 22, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ac47775d14](https://linux-hardware.org/?probe=ac47775d14) | Oct 17, 2023 |
| Gigabyte      | B550M S2H                   | [92cf4d1df2](https://linux-hardware.org/?probe=92cf4d1df2) | Oct 03, 2023 |
| Gigabyte      | B550M S2H                   | [d7efd8ecaa](https://linux-hardware.org/?probe=d7efd8ecaa) | Oct 03, 2023 |
| Dell          | 0Y56T3 A01                  | [bfc1d1dd13](https://linux-hardware.org/?probe=bfc1d1dd13) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [3e29eb1d63](https://linux-hardware.org/?probe=3e29eb1d63) | Sep 26, 2023 |
| Dell          | 0KRC95 A01                  | [bfed5cdd27](https://linux-hardware.org/?probe=bfed5cdd27) | Sep 24, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [6f73b0398c](https://linux-hardware.org/?probe=6f73b0398c) | Sep 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [7b10a3651b](https://linux-hardware.org/?probe=7b10a3651b) | Sep 16, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2956ecb7bf](https://linux-hardware.org/?probe=2956ecb7bf) | Aug 25, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ac041357b0](https://linux-hardware.org/?probe=ac041357b0) | Aug 21, 2023 |
| Gigabyte      | B560M DS3H V2               | [131535162e](https://linux-hardware.org/?probe=131535162e) | Aug 14, 2023 |
| Gigabyte      | X570 UD                     | [c693096b39](https://linux-hardware.org/?probe=c693096b39) | Jul 26, 2023 |
| MSI           | H410M PRO                   | [881d77ac47](https://linux-hardware.org/?probe=881d77ac47) | Jul 04, 2023 |
| ASRock        | H310CM-DVS                  | [46429ac6ae](https://linux-hardware.org/?probe=46429ac6ae) | Jun 29, 2023 |
| ASUSTek       | H110M-D                     | [f95d5e83f5](https://linux-hardware.org/?probe=f95d5e83f5) | Jun 25, 2023 |
| MAXSUN        | MS-H81IL TR M.2             | [72c79949e0](https://linux-hardware.org/?probe=72c79949e0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [9493891426](https://linux-hardware.org/?probe=9493891426) | Jun 18, 2023 |
| Gigabyte      | Z170X-Gaming 6              | [21eaab076a](https://linux-hardware.org/?probe=21eaab076a) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc54139aa6](https://linux-hardware.org/?probe=cc54139aa6) | Jun 08, 2023 |
| HP            | 8617                        | [7f5df3475c](https://linux-hardware.org/?probe=7f5df3475c) | Jun 06, 2023 |
| Dell          | 0J3C2F A00                  | [b7d801d9e5](https://linux-hardware.org/?probe=b7d801d9e5) | May 24, 2023 |
| Gigabyte      | B560M DS3H V2               | [47f3dabdb0](https://linux-hardware.org/?probe=47f3dabdb0) | May 14, 2023 |
| ASUSTek       | Z97-DELUXE                  | [c47205c3cb](https://linux-hardware.org/?probe=c47205c3cb) | May 06, 2023 |
| ASUSTek       | X99-A                       | [1adc932507](https://linux-hardware.org/?probe=1adc932507) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD5H                   | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| Gigabyte      | H77N-WIFI                   | [10e158aabd](https://linux-hardware.org/?probe=10e158aabd) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [2391458529](https://linux-hardware.org/?probe=2391458529) | Apr 15, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1146ed168f](https://linux-hardware.org/?probe=1146ed168f) | Apr 14, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [7c32eb6bf9](https://linux-hardware.org/?probe=7c32eb6bf9) | Apr 11, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [cabf7adac2](https://linux-hardware.org/?probe=cabf7adac2) | Apr 11, 2023 |
| HP            | 89D8 SMVB                   | [a9980f1194](https://linux-hardware.org/?probe=a9980f1194) | Apr 04, 2023 |
| Acer          | Nitro N50-610               | [937d1bc73a](https://linux-hardware.org/?probe=937d1bc73a) | Mar 29, 2023 |
| ASRock        | X300M-STX                   | [0393d25a9d](https://linux-hardware.org/?probe=0393d25a9d) | Mar 23, 2023 |
| ASRock        | X300M-STX                   | [296411b749](https://linux-hardware.org/?probe=296411b749) | Mar 23, 2023 |
| HP            | 83E9                        | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [a77d320c80](https://linux-hardware.org/?probe=a77d320c80) | Mar 18, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270M-PLUS            | [5cb3c60db6](https://linux-hardware.org/?probe=5cb3c60db6) | Mar 14, 2023 |
| HP            | 89D8 SMVB                   | [6b3f831210](https://linux-hardware.org/?probe=6b3f831210) | Mar 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [e2d3c4e17e](https://linux-hardware.org/?probe=e2d3c4e17e) | Mar 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | AX370-Gaming-CF se1         | [79f1c1822c](https://linux-hardware.org/?probe=79f1c1822c) | Mar 09, 2023 |
| Gigabyte      | B450 AORUS M                | [e67eb9d235](https://linux-hardware.org/?probe=e67eb9d235) | Mar 06, 2023 |
| ASUSTek       | PRIME A320I-K               | [88e6308c0a](https://linux-hardware.org/?probe=88e6308c0a) | Mar 05, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [53d547f79c](https://linux-hardware.org/?probe=53d547f79c) | Mar 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [3e3368d913](https://linux-hardware.org/?probe=3e3368d913) | Feb 28, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [0195132360](https://linux-hardware.org/?probe=0195132360) | Feb 28, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [8cd8d4b833](https://linux-hardware.org/?probe=8cd8d4b833) | Feb 28, 2023 |
| Biostar       | A320MH                      | [b6f7ef6e4a](https://linux-hardware.org/?probe=b6f7ef6e4a) | Feb 23, 2023 |
| Biostar       | A320MH                      | [e80f86a0bf](https://linux-hardware.org/?probe=e80f86a0bf) | Feb 23, 2023 |
| ASRock        | B760M-ITX/D4 WiFi           | [8a29735d16](https://linux-hardware.org/?probe=8a29735d16) | Feb 16, 2023 |
| HP            | 83EC                        | [4757525f5d](https://linux-hardware.org/?probe=4757525f5d) | Feb 15, 2023 |
| Shenzhen M... | F7BFC                       | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [abfd3f65af](https://linux-hardware.org/?probe=abfd3f65af) | Feb 10, 2023 |
| ASRock        | B560 Pro4                   | [0243fe3621](https://linux-hardware.org/?probe=0243fe3621) | Feb 07, 2023 |
| MSI           | B450M MORTAR MAX            | [2f0810d441](https://linux-hardware.org/?probe=2f0810d441) | Feb 05, 2023 |
| Gigabyte      | B450 AORUS M                | [c35fa9b7f5](https://linux-hardware.org/?probe=c35fa9b7f5) | Feb 05, 2023 |
| Gigabyte      | B85M-D3H                    | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte      | B85M-D3H                    | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Dell          | 0F3KHR A00                  | [a088ccf72c](https://linux-hardware.org/?probe=a088ccf72c) | Feb 02, 2023 |
| Dell          | 0F3KHR A00                  | [6c793de699](https://linux-hardware.org/?probe=6c793de699) | Feb 01, 2023 |
| Dell          | 0D6H9T A00                  | [2c34aba28a](https://linux-hardware.org/?probe=2c34aba28a) | Jan 30, 2023 |
| HP            | 8906 SMVB                   | [625d54930d](https://linux-hardware.org/?probe=625d54930d) | Jan 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3b92dd60cf](https://linux-hardware.org/?probe=3b92dd60cf) | Jan 11, 2023 |
| Gigabyte      | B450 AORUS M                | [0851440887](https://linux-hardware.org/?probe=0851440887) | Jan 11, 2023 |
| Gigabyte      | B550M DS3H                  | [3d656e7bfd](https://linux-hardware.org/?probe=3d656e7bfd) | Jan 05, 2023 |
| MSI           | H81M-P33                    | [041ee2fde1](https://linux-hardware.org/?probe=041ee2fde1) | Jan 03, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [59bf36837d](https://linux-hardware.org/?probe=59bf36837d) | Dec 18, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [d5279b915a](https://linux-hardware.org/?probe=d5279b915a) | Dec 17, 2022 |
| Dell          | 0KC9NP A01                  | [0e70489d5c](https://linux-hardware.org/?probe=0e70489d5c) | Dec 16, 2022 |
| ASUSTek       | M80CJ-O                     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [65ccd1da0e](https://linux-hardware.org/?probe=65ccd1da0e) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c2c53a959d](https://linux-hardware.org/?probe=c2c53a959d) | Dec 03, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [3f642a7844](https://linux-hardware.org/?probe=3f642a7844) | Dec 02, 2022 |
| Gigabyte      | B450M DS3H V2               | [f00a357dbe](https://linux-hardware.org/?probe=f00a357dbe) | Nov 29, 2022 |
| MSI           | 970A-G46                    | [3cd88e88d3](https://linux-hardware.org/?probe=3cd88e88d3) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c278b19567](https://linux-hardware.org/?probe=c278b19567) | Nov 20, 2022 |
| HP            | 8626                        | [f2098a2414](https://linux-hardware.org/?probe=f2098a2414) | Nov 19, 2022 |
| HP            | 8626                        | [05ebc14932](https://linux-hardware.org/?probe=05ebc14932) | Nov 19, 2022 |
| Gigabyte      | 970A-DS3P FX                | [85ef5eaf43](https://linux-hardware.org/?probe=85ef5eaf43) | Nov 12, 2022 |
| MSI           | X370 GAMING PLUS            | [a0b134897f](https://linux-hardware.org/?probe=a0b134897f) | Nov 05, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f23e197251](https://linux-hardware.org/?probe=f23e197251) | Nov 05, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| Gigabyte      | B550 GAMING X V2            | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [59904b8a87](https://linux-hardware.org/?probe=59904b8a87) | Oct 19, 2022 |
| HP            | 8433 11                     | [fed45efc8d](https://linux-hardware.org/?probe=fed45efc8d) | Oct 12, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [9873ba1845](https://linux-hardware.org/?probe=9873ba1845) | Oct 09, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2e6852099a](https://linux-hardware.org/?probe=2e6852099a) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [aee559f8bf](https://linux-hardware.org/?probe=aee559f8bf) | Oct 04, 2022 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | [5746aa7609](https://linux-hardware.org/?probe=5746aa7609) | Sep 29, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| MSI           | X399 SLI PLUS               | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| MSI           | X470 GAMING PLUS            | [9919cebdfe](https://linux-hardware.org/?probe=9919cebdfe) | Sep 15, 2022 |
| MSI           | 970A-G46                    | [5f7482fe88](https://linux-hardware.org/?probe=5f7482fe88) | Sep 11, 2022 |
| ASUSTek       | H81M-PLUS                   | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS M                | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Dell          | 0HHV7N A00                  | [f4142b2ff8](https://linux-hardware.org/?probe=f4142b2ff8) | Sep 02, 2022 |
| ASUSTek       | PRIME A320M-K               | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Gigabyte      | X570 GAMING X               | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| MSI           | MS-B9351                    | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| Dell          | 00F82W A00                  | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Gigabyte      | H310M S2V                   | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| ASRock        | A520M-ITX/ac                | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock        | B450M-HDV R4.0              | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Gigabyte      | H170N-WIFI-CF               | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Alienware     | 02XRCM A01                  | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| ASUSTek       | H61M-K                      | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock        | B550 PG Velocita            | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock        | B365M Pro4-F                | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | B560M AORUS PRO             | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| SteamOS 3.4                   | 54       | 17.76%  |
| SteamOS 4                     | 30       | 9.87%   |
| SteamOS 3.3                   | 25       | 8.22%   |
| SteamOS 3.7.13                | 21       | 6.91%   |
| SteamOS 3.7.17                | 18       | 5.92%   |
| SteamOS 1.3-mesa-fixes        | 17       | 5.59%   |
| SteamOS 3.7.8                 | 16       | 5.26%   |
| SteamOS 3.5.7                 | 15       | 4.93%   |
| SteamOS 3.6.24                | 9        | 2.96%   |
| SteamOS 3.7.15                | 8        | 2.63%   |
| SteamOS 3.5.19                | 8        | 2.63%   |
| SteamOS 3.2 (steamdeck-main)  | 7        | 2.3%    |
| SteamOS 3.9                   | 6        | 1.97%   |
| SteamOS 3.6.20                | 6        | 1.97%   |
| SteamOS                       | 6        | 1.97%   |
| SteamOS 3.6.22                | 5        | 1.64%   |
| SteamOS Rolling               | 4        | 1.32%   |
| SteamOS 1.5-next-fixes        | 4        | 1.32%   |
| SteamOS 1.1.6-prefinal_fixups | 4        | 1.32%   |
| SteamOS 1.1.2                 | 4        | 1.32%   |
| SteamOS Snapshot              | 3        | 0.99%   |
| SteamOS 1.1.4                 | 3        | 0.99%   |
| SteamOS 3.7.19                | 2        | 0.66%   |
| SteamOS 3.7.14                | 2        | 0.66%   |
| SteamOS 3.7.12                | 2        | 0.66%   |
| SteamOS 3.5.17                | 2        | 0.66%   |
| SteamOS 1.4-intel-fixes       | 2        | 0.66%   |
| SteamOS 1.1.9_beta-final      | 2        | 0.66%   |
| SteamOS 1.1.3                 | 2        | 0.66%   |
| SteamOS 1.01-dev_nv           | 2        | 0.66%   |
| SteamOS 3.8                   | 1        | 0.33%   |
| SteamOS 3.7.9                 | 1        | 0.33%   |
| SteamOS 3.7.7                 | 1        | 0.33%   |
| SteamOS 3.7.2                 | 1        | 0.33%   |
| SteamOS 3.7.18                | 1        | 0.33%   |
| SteamOS 3.7.0                 | 1        | 0.33%   |
| SteamOS 3.6.23                | 1        | 0.33%   |
| SteamOS 3.2                   | 1        | 0.33%   |
| SteamOS 20250407.2232         | 1        | 0.33%   |
| SteamOS 20250204.1110         | 1        | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 288      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 43       | 14.29%  |
| 6.3.7-zen1-1-zen                                   | 26       | 8.64%   |
| 6.11.11-valve24-2-neptune-611-gfd0dd251480d        | 26       | 8.64%   |
| 6.11.11-valve19-1-neptune-611-g88b36d49a5e3        | 25       | 8.31%   |
| 6.8.5-1-lljy-CFS-gcd11c870c00c                     | 22       | 7.31%   |
| 6.5.0-valve23-1-neptune-65-g385b5e207ae2           | 16       | 5.32%   |
| 6.1.52-valve9-1-neptune-61                         | 15       | 4.98%   |
| 6.11.11-valve14-1-neptune-611-g96885212a919        | 14       | 4.65%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 11       | 3.65%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 3.65%   |
| 6.1.52-valve16-1-neptune-61                        | 10       | 3.32%   |
| 6.4.12-zen1-1-zen                                  | 9        | 2.99%   |
| 6.7.4-holoiso-beta_lljy-kernel-lljy-g76a2d2abfbba  | 7        | 2.33%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 7        | 2.33%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 2.33%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e           | 5        | 1.66%   |
| 6.11.11-valve26-1-neptune-611-gb3afa9aa9ae7        | 5        | 1.66%   |
| 6.8.8-zen1-1-zen                                   | 3        | 1%      |
| 6.16.12-valve4-1-neptune-616-g366ccd8ab040         | 3        | 1%      |
| 6.1.21-valve1-1-neptune-61                         | 3        | 1%      |
| 5.13.0-valve36-1-neptune                           | 3        | 1%      |
| 6.16.12-valve6-1-neptune-616-g37101e112292         | 2        | 0.66%   |
| 6.11.11-valve20-1-neptune-611-gd35c3ed359a0        | 2        | 0.66%   |
| 6.11.11-valve17-1-neptune-611-g027868a0ac03        | 2        | 0.66%   |
| 6.1.21-valve1-3-neptune-61                         | 2        | 0.66%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 0.66%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 2        | 0.66%   |
| 6.3.9-arch1-1                                      | 1        | 0.33%   |
| 6.16.12-valve5-1-neptune-616-ga9fcc52b276a         | 1        | 0.33%   |
| 6.16.12-valve2-1-neptune-616-g8a732b312b58         | 1        | 0.33%   |
| 6.13.10-1                                          | 1        | 0.33%   |
| 6.12.12-1                                          | 1        | 0.33%   |
| 6.11.11-valve8-1-neptune-611-g9b073eb8166e         | 1        | 0.33%   |
| 6.11.11-valve10-1-neptune-611-gb69e902b4338        | 1        | 0.33%   |
| 6.10.7-1-lljy-g2fd7b345494a                        | 1        | 0.33%   |
| 6.10.10-5                                          | 1        | 0.33%   |
| 6.1.29-valve4-1-neptune-61                         | 1        | 0.33%   |
| 6.1.12-valve2-1-neptune-61                         | 1        | 0.33%   |
| 6.0.9-valve1-2-neptune-60                          | 1        | 0.33%   |
| 5.15.93-1-lts                                      | 1        | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 82       | 27.42%  |
| 6.11.11 | 74       | 24.75%  |
| 6.3.7   | 26       | 8.7%    |
| 6.1.52  | 25       | 8.36%   |
| 6.8.5   | 22       | 7.36%   |
| 6.5.0   | 21       | 7.02%   |
| 6.4.12  | 9        | 3.01%   |
| 6.7.4   | 7        | 2.34%   |
| 6.16.12 | 7        | 2.34%   |
| 5.18.1  | 7        | 2.34%   |
| 6.1.21  | 5        | 1.67%   |
| 6.8.8   | 3        | 1%      |
| 6.3.9   | 1        | 0.33%   |
| 6.13.10 | 1        | 0.33%   |
| 6.12.12 | 1        | 0.33%   |
| 6.10.7  | 1        | 0.33%   |
| 6.10.10 | 1        | 0.33%   |
| 6.1.29  | 1        | 0.33%   |
| 6.1.12  | 1        | 0.33%   |
| 6.0.9   | 1        | 0.33%   |
| 5.15.93 | 1        | 0.33%   |
| 5.15.79 | 1        | 0.33%   |
| 5.15.60 | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 82       | 27.42%  |
| 6.11    | 74       | 24.75%  |
| 6.1     | 32       | 10.7%   |
| 6.3     | 27       | 9.03%   |
| 6.8     | 25       | 8.36%   |
| 6.5     | 21       | 7.02%   |
| 6.4     | 9        | 3.01%   |
| 6.7     | 7        | 2.34%   |
| 6.16    | 7        | 2.34%   |
| 5.18    | 7        | 2.34%   |
| 5.15    | 3        | 1%      |
| 6.10    | 2        | 0.67%   |
| 6.13    | 1        | 0.33%   |
| 6.12    | 1        | 0.33%   |
| 6.0     | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 288      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 209      | 71.82%  |
| KDE6    | 80       | 27.49%  |
| GNOME   | 1        | 0.34%   |
| Unknown | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 283      | 98.26%  |
| Wayland | 5        | 1.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 285      | 98.96%  |
| SDDM    | 3        | 1.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 199      | 68.38%  |
| C     | 34       | 11.68%  |
| pt_BR | 11       | 3.78%   |
| ru_RU | 10       | 3.44%   |
| fr_FR | 8        | 2.75%   |
| de_DE | 7        | 2.41%   |
| it_IT | 4        | 1.37%   |
| es_ES | 4        | 1.37%   |
| ja_JP | 2        | 0.69%   |
| en_GB | 2        | 0.69%   |
| zh_TW | 1        | 0.34%   |
| pt_PT | 1        | 0.34%   |
| pl_PL | 1        | 0.34%   |
| n_US  | 1        | 0.34%   |
| hu_HU | 1        | 0.34%   |
| en_IN | 1        | 0.34%   |
| en_IE | 1        | 0.34%   |
| en_DE | 1        | 0.34%   |
| en_AG | 1        | 0.34%   |
| de_AT | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 285      | 98.96%  |
| EFI  | 3        | 1.04%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 282      | 97.92%  |
| Tmpfs | 6        | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 285      | 98.62%  |
| GPT     | 4        | 1.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 288      | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 286      | 99.31%  |
| Yes       | 2        | 0.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 82       | 28.47%  |
| Gigabyte Technology                  | 62       | 21.53%  |
| ASRock                               | 43       | 14.93%  |
| MSI                                  | 36       | 12.5%   |
| Dell                                 | 11       | 3.82%   |
| Hewlett-Packard                      | 10       | 3.47%   |
| Shenzhen Meigao Electronic Equipment | 8        | 2.78%   |
| Intel                                | 6        | 2.08%   |
| Unknown                              | 5        | 1.74%   |
| Lenovo                               | 4        | 1.39%   |
| Apple                                | 4        | 1.39%   |
| MACHINIST                            | 2        | 0.69%   |
| JGINYUE                              | 2        | 0.69%   |
| SZQFTX                               | 1        | 0.35%   |
| QIYIDA                               | 1        | 0.35%   |
| NZXT                                 | 1        | 0.35%   |
| Medion                               | 1        | 0.35%   |
| MAXSUN                               | 1        | 0.35%   |
| GMKtec                               | 1        | 0.35%   |
| GEEKOM                               | 1        | 0.35%   |
| Colorful Technology                  | 1        | 0.35%   |
| Biostar                              | 1        | 0.35%   |
| BCM Advanced Research                | 1        | 0.35%   |
| AZW                                  | 1        | 0.35%   |
| Alienware                            | 1        | 0.35%   |
| Acer                                 | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| ASUS All Series                                       | 8        | 2.78%   |
| Unknown                                               | 5        | 1.74%   |
| Gigabyte B550 GAMING X V2                             | 4        | 1.39%   |
| Gigabyte B450M GAMING                                 | 4        | 1.39%   |
| Gigabyte B450 AORUS M                                 | 4        | 1.39%   |
| ASUS PRIME A320M-K                                    | 4        | 1.39%   |
| MSI MS-7C91                                           | 3        | 1.04%   |
| MSI MS-7C37                                           | 3        | 1.04%   |
| MSI MS-7C02                                           | 3        | 1.04%   |
| MSI MS-7B79                                           | 3        | 1.04%   |
| ASUS TUF Gaming X570-PLUS                             | 3        | 1.04%   |
| ASUS ROG STRIX B550-I GAMING                          | 3        | 1.04%   |
| ASUS ROG STRIX B550-F GAMING                          | 3        | 1.04%   |
| ASRock B550M Pro4                                     | 3        | 1.04%   |
| ASRock B450 Gaming-ITX/ac                             | 3        | 1.04%   |
| Apple MacPro5,1                                       | 3        | 1.04%   |
| Shenzhen Meigao Electronic Equipment AtomMan G Series | 2        | 0.69%   |
| MSI MS-7C95                                           | 2        | 0.69%   |
| Intel X99                                             | 2        | 0.69%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx             | 2        | 0.69%   |
| Gigabyte B550M DS3H                                   | 2        | 0.69%   |
| Gigabyte B550M AORUS ELITE                            | 2        | 0.69%   |
| Gigabyte A520M K V2                                   | 2        | 0.69%   |
| Dell OptiPlex 9010                                    | 2        | 0.69%   |
| ASUS PRIME B450M-K II                                 | 2        | 0.69%   |
| ASUS PRIME B450M-A II                                 | 2        | 0.69%   |
| ASUS PRIME B350-PLUS                                  | 2        | 0.69%   |
| ASUS CROSSHAIR VI HERO                                | 2        | 0.69%   |
| ASRock X570 Phantom Gaming-ITX/TB3                    | 2        | 0.69%   |
| ASRock X300M-STX                                      | 2        | 0.69%   |
| ASRock B450M Steel Legend                             | 2        | 0.69%   |
| ASRock AB350M Pro4                                    | 2        | 0.69%   |
| ASRock A520M-ITX/ac                                   | 2        | 0.69%   |
| SZQFTX MN56                                           | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment Venus series     | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment Uranus Series    | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment UM690            | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment Series           | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment Mercury series   | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment HX99G            | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| ASUS PRIME                                   | 24       | 8.33%   |
| ASUS ROG                                     | 19       | 6.6%    |
| ASUS TUF                                     | 15       | 5.21%   |
| Dell OptiPlex                                | 8        | 2.78%   |
| ASUS All                                     | 8        | 2.78%   |
| Gigabyte B450M                               | 7        | 2.43%   |
| Gigabyte B450                                | 7        | 2.43%   |
| Gigabyte B550M                               | 6        | 2.08%   |
| Unknown                                      | 5        | 1.74%   |
| Gigabyte B550                                | 4        | 1.39%   |
| ASRock B550M                                 | 4        | 1.39%   |
| ASRock B450                                  | 4        | 1.39%   |
| MSI MS-7C91                                  | 3        | 1.04%   |
| MSI MS-7C37                                  | 3        | 1.04%   |
| MSI MS-7C02                                  | 3        | 1.04%   |
| MSI MS-7B79                                  | 3        | 1.04%   |
| Gigabyte X570                                | 3        | 1.04%   |
| ASRock X570                                  | 3        | 1.04%   |
| ASRock B450M                                 | 3        | 1.04%   |
| Apple MacPro5                                | 3        | 1.04%   |
| Shenzhen Meigao Electronic Equipment AtomMan | 2        | 0.69%   |
| MSI MS-7C95                                  | 2        | 0.69%   |
| Lenovo ThinkStation                          | 2        | 0.69%   |
| Intel X99                                    | 2        | 0.69%   |
| HP Victus                                    | 2        | 0.69%   |
| HP ProDesk                                   | 2        | 0.69%   |
| HP Pavilion                                  | 2        | 0.69%   |
| HP EliteDesk                                 | 2        | 0.69%   |
| Gigabyte B560M                               | 2        | 0.69%   |
| Gigabyte A520M                               | 2        | 0.69%   |
| Gigabyte A320M-S2H                           | 2        | 0.69%   |
| Dell Precision                               | 2        | 0.69%   |
| ASUS Pro                                     | 2        | 0.69%   |
| ASUS CROSSHAIR                               | 2        | 0.69%   |
| ASRock X300M-STX                             | 2        | 0.69%   |
| ASRock B550                                  | 2        | 0.69%   |
| ASRock AB350M-HDV                            | 2        | 0.69%   |
| ASRock AB350M                                | 2        | 0.69%   |
| ASRock A520M-ITX                             | 2        | 0.69%   |
| SZQFTX MN56                                  | 1        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 56       | 19.44%  |
| 2018 | 44       | 15.28%  |
| 2019 | 29       | 10.07%  |
| 2022 | 24       | 8.33%   |
| 2021 | 23       | 7.99%   |
| 2017 | 23       | 7.99%   |
| 2023 | 19       | 6.6%    |
| 2024 | 16       | 5.56%   |
| 2016 | 11       | 3.82%   |
| 2014 | 11       | 3.82%   |
| 2012 | 8        | 2.78%   |
| 2015 | 7        | 2.43%   |
| 2013 | 7        | 2.43%   |
| 2025 | 5        | 1.74%   |
| 2011 | 2        | 0.69%   |
| 2010 | 2        | 0.69%   |
| 2009 | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 288      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 288      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 288      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 95       | 32.65%  |
| 16.01-24.0  | 86       | 29.55%  |
| 8.01-16.0   | 46       | 15.81%  |
| 24.01-32.0  | 35       | 12.03%  |
| 64.01-256.0 | 18       | 6.19%   |
| 4.01-8.0    | 11       | 3.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 114      | 38.26%  |
| 3.01-4.0  | 93       | 31.21%  |
| 2.01-3.0  | 67       | 22.48%  |
| 8.01-16.0 | 15       | 5.03%   |
| 1.01-2.0  | 9        | 3.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 31.97%  |
| 2      | 87       | 29.59%  |
| 3      | 59       | 20.07%  |
| 4      | 30       | 10.2%   |
| 5      | 14       | 4.76%   |
| 6      | 5        | 1.7%    |
| 8      | 2        | 0.68%   |
| 7      | 2        | 0.68%   |
| 11     | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 254      | 88.19%  |
| Yes       | 34       | 11.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 285      | 98.96%  |
| No        | 3        | 1.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 186      | 64.36%  |
| No        | 103      | 35.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 182      | 62.54%  |
| No        | 109      | 37.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 93       | 32.07%  |
| Brazil       | 22       | 7.59%   |
| Germany      | 18       | 6.21%   |
| UK           | 16       | 5.52%   |
| France       | 14       | 4.83%   |
| Russia       | 11       | 3.79%   |
| Italy        | 10       | 3.45%   |
| Australia    | 8        | 2.76%   |
| Poland       | 7        | 2.41%   |
| Spain        | 6        | 2.07%   |
| Netherlands  | 6        | 2.07%   |
| Canada       | 6        | 2.07%   |
| Israel       | 4        | 1.38%   |
| Ireland      | 4        | 1.38%   |
| South Africa | 3        | 1.03%   |
| Romania      | 3        | 1.03%   |
| Philippines  | 3        | 1.03%   |
| Japan        | 3        | 1.03%   |
| Argentina    | 3        | 1.03%   |
| Taiwan       | 2        | 0.69%   |
| Sweden       | 2        | 0.69%   |
| Saudi Arabia | 2        | 0.69%   |
| Portugal     | 2        | 0.69%   |
| Norway       | 2        | 0.69%   |
| Indonesia    | 2        | 0.69%   |
| Iceland      | 2        | 0.69%   |
| Hong Kong    | 2        | 0.69%   |
| Denmark      | 2        | 0.69%   |
| Czechia      | 2        | 0.69%   |
| Cambodia     | 2        | 0.69%   |
| Belgium      | 2        | 0.69%   |
| Austria      | 2        | 0.69%   |
| Vietnam      | 1        | 0.34%   |
| Uzbekistan   | 1        | 0.34%   |
| Uruguay      | 1        | 0.34%   |
| Turkey       | 1        | 0.34%   |
| Thailand     | 1        | 0.34%   |
| Switzerland  | 1        | 0.34%   |
| Slovakia     | 1        | 0.34%   |
| Singapore    | 1        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Sao Paulo       | 5        | 1.71%   |
| Sydney          | 4        | 1.37%   |
| Moscow          | 4        | 1.37%   |
| Tel Aviv        | 3        | 1.02%   |
| Rome            | 3        | 1.02%   |
| San Jose        | 2        | 0.68%   |
| Reykjavik       | 2        | 0.68%   |
| Porto Alegre    | 2        | 0.68%   |
| Portland        | 2        | 0.68%   |
| Phnom Penh      | 2        | 0.68%   |
| Oklahoma City   | 2        | 0.68%   |
| Muskego         | 2        | 0.68%   |
| Jersey City     | 2        | 0.68%   |
| Henderson       | 2        | 0.68%   |
| Gujan-Mestras   | 2        | 0.68%   |
| Dallas          | 2        | 0.68%   |
| Cleveland       | 2        | 0.68%   |
| Central         | 2        | 0.68%   |
| Brasília       | 2        | 0.68%   |
| Zwolle          | 1        | 0.34%   |
| Zevio           | 1        | 0.34%   |
| Zejtun          | 1        | 0.34%   |
| Yingge District | 1        | 0.34%   |
| Woodway         | 1        | 0.34%   |
| Winssen         | 1        | 0.34%   |
| Winchester      | 1        | 0.34%   |
| Williamson      | 1        | 0.34%   |
| West Bloomfield | 1        | 0.34%   |
| Watford         | 1        | 0.34%   |
| Warsaw          | 1        | 0.34%   |
| Walsall         | 1        | 0.34%   |
| Violaines       | 1        | 0.34%   |
| Ville Platte    | 1        | 0.34%   |
| Vilas           | 1        | 0.34%   |
| Vila Velha      | 1        | 0.34%   |
| Viganello       | 1        | 0.34%   |
| Victoria        | 1        | 0.34%   |
| Tyumen          | 1        | 0.34%   |
| Tuttlingen      | 1        | 0.34%   |
| Tula            | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 88       | 151    | 14.67%  |
| Seagate                      | 76       | 96     | 12.67%  |
| WDC                          | 62       | 76     | 10.33%  |
| Sandisk                      | 49       | 60     | 8.17%   |
| Kingston                     | 41       | 46     | 6.83%   |
| Crucial                      | 31       | 41     | 5.17%   |
| Toshiba                      | 26       | 29     | 4.33%   |
| Micron/Crucial Technology    | 24       | 24     | 4%      |
| Phison Electronics           | 23       | 35     | 3.83%   |
| MAXIO Technology (Hangzhou)  | 16       | 18     | 2.67%   |
| Silicon Motion               | 11       | 13     | 1.83%   |
| A-DATA Technology            | 10       | 10     | 1.67%   |
| PNY                          | 9        | 12     | 1.5%    |
| Kingston Technology Company  | 9        | 10     | 1.5%    |
| Intel                        | 8        | 10     | 1.33%   |
| China                        | 8        | 12     | 1.33%   |
| SK hynix                     | 7        | 8      | 1.17%   |
| Realtek Semiconductor        | 7        | 7      | 1.17%   |
| Micron Technology            | 6        | 7      | 1%      |
| Unknown                      | 6        | 7      | 1%      |
| Shenzhen Longsys Electronics | 5        | 6      | 0.83%   |
| Phison                       | 5        | 6      | 0.83%   |
| Patriot                      | 5        | 5      | 0.83%   |
| ADATA Technology             | 5        | 6      | 0.83%   |
| Realtek                      | 4        | 4      | 0.67%   |
| Hitachi                      | 4        | 4      | 0.67%   |
| Unknown                      | 3        | 3      | 0.5%    |
| SPCC                         | 3        | 5      | 0.5%    |
| KIOXIA                       | 3        | 3      | 0.5%    |
| SOLIDIGM                     | 2        | 2      | 0.33%   |
| Mushkin                      | 2        | 2      | 0.33%   |
| JMicron Technology           | 2        | 2      | 0.33%   |
| Intenso                      | 2        | 2      | 0.33%   |
| HUSKY                        | 2        | 2      | 0.33%   |
| HGST                         | 2        | 2      | 0.33%   |
| Apple                        | 2        | 6      | 0.33%   |
| Viper                        | 1        | 1      | 0.17%   |
| Verbatim                     | 1        | 1      | 0.17%   |
| USB                          | 1        | 1      | 0.17%   |
| Union Memory (Shenzhen)      | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 20       | 2.99%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB      | 13       | 1.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 10       | 1.5%    |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 9        | 1.35%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 8        | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 8        | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 8        | 1.2%    |
| Samsung SSD 850 EVO 250GB                             | 7        | 1.05%   |
| Toshiba DT01ACA100 1TB                                | 6        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB                        | 6        | 0.9%    |
| Samsung SSD 980 1TB                                   | 6        | 0.9%    |
| Kingston SA400S37240G 240GB SSD                       | 6        | 0.9%    |
| Crucial CT500MX500SSD1 500GB                          | 6        | 0.9%    |
| Crucial CT1000BX500SSD1 1TB                           | 6        | 0.9%    |
| Unknown                                               | 6        | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 5        | 0.75%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 5        | 0.75%   |
| Phison E12 NVMe Controller 1TB                        | 5        | 0.75%   |
| Kingston SA400S37120G 120GB SSD                       | 5        | 0.75%   |
| Sandisk WD_BLACK SN770 1TB                            | 4        | 0.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 4        | 0.6%    |
| Phison PS5013 E13 NVMe Controller 500GB               | 4        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 4        | 0.6%    |
| Seagate ST500DM002-1BD142 500GB                       | 3        | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 3        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB                        | 3        | 0.45%   |
| Sandisk WD Blue SN570 1TB                             | 3        | 0.45%   |
| Samsung SSD 870 EVO 4TB                               | 3        | 0.45%   |
| Samsung NVMe SSD Drive 1TB                            | 3        | 0.45%   |
| Realtek RTS5763DL NVMe SSD Controller 512GB           | 3        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                      | 3        | 0.45%   |
| Kingston SNVS500G 500GB                               | 3        | 0.45%   |
| Kingston SKC3000D2048G 2TB                            | 3        | 0.45%   |
| Kingston SA400S37960G 960GB SSD                       | 3        | 0.45%   |
| Intel SSD 660P Series 512GB                           | 3        | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                           | 3        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB                          | 2        | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2        | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 74       | 93     | 45.4%   |
| WDC                 | 46       | 55     | 28.22%  |
| Toshiba             | 23       | 26     | 14.11%  |
| Samsung Electronics | 5        | 5      | 3.07%   |
| Hitachi             | 4        | 4      | 2.45%   |
| JMicron Technology  | 2        | 2      | 1.23%   |
| HGST                | 2        | 2      | 1.23%   |
| Unknown             | 1        | 1      | 0.61%   |
| T-FORCE             | 1        | 1      | 0.61%   |
| Maxtor              | 1        | 1      | 0.61%   |
| LaCie               | 1        | 1      | 0.61%   |
| Intenso             | 1        | 1      | 0.61%   |
| HGST HTS            | 1        | 1      | 0.61%   |
| Apple               | 1        | 5      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 42       | 59     | 21.88%  |
| Crucial             | 31       | 41     | 16.15%  |
| Kingston            | 28       | 31     | 14.58%  |
| WDC                 | 20       | 21     | 10.42%  |
| SanDisk             | 14       | 15     | 7.29%   |
| A-DATA Technology   | 10       | 10     | 5.21%   |
| PNY                 | 9        | 12     | 4.69%   |
| China               | 8        | 12     | 4.17%   |
| SPCC                | 3        | 5      | 1.56%   |
| Patriot             | 3        | 3      | 1.56%   |
| Mushkin             | 2        | 2      | 1.04%   |
| Micron Technology   | 2        | 3      | 1.04%   |
| HUSKY               | 2        | 2      | 1.04%   |
| Verbatim            | 1        | 1      | 0.52%   |
| Transcend           | 1        | 1      | 0.52%   |
| Team                | 1        | 2      | 0.52%   |
| SK hynix            | 1        | 1      | 0.52%   |
| Seagate             | 1        | 1      | 0.52%   |
| Ramsta              | 1        | 1      | 0.52%   |
| KODAK               | 1        | 1      | 0.52%   |
| Intenso             | 1        | 1      | 0.52%   |
| Intel               | 1        | 1      | 0.52%   |
| Hewlett-Packard     | 1        | 1      | 0.52%   |
| GOODRAM             | 1        | 2      | 0.52%   |
| Gigastone           | 1        | 1      | 0.52%   |
| Gigabyte Technology | 1        | 1      | 0.52%   |
| Corsair             | 1        | 1      | 0.52%   |
| Colorful            | 1        | 1      | 0.52%   |
| BIWIN               | 1        | 1      | 0.52%   |
| Apacer              | 1        | 1      | 0.52%   |
| 2.5                 | 1        | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 214      | 320    | 42.63%  |
| SSD     | 149      | 236    | 29.68%  |
| HDD     | 127      | 198    | 25.3%   |
| Unknown | 12       | 13     | 2.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 214      | 309    | 48.31%  |
| SATA | 201      | 419    | 45.37%  |
| SAS  | 28       | 39     | 6.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 133      | 195    | 43.61%  |
| 0.51-1.0   | 97       | 137    | 31.8%   |
| 1.01-2.0   | 34       | 53     | 11.15%  |
| 3.01-4.0   | 23       | 28     | 7.54%   |
| 4.01-10.0  | 7        | 7      | 2.3%    |
| 10.01-20.0 | 6        | 7      | 1.97%   |
| 2.01-3.0   | 5        | 7      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 69       | 23.47%  |
| 101-250        | 64       | 21.77%  |
| 1001-2000      | 60       | 20.41%  |
| 251-500        | 45       | 15.31%  |
| More than 3000 | 32       | 10.88%  |
| 2001-3000      | 15       | 5.1%    |
| Unknown        | 3        | 1.02%   |
| 21-50          | 2        | 0.68%   |
| 1-20           | 2        | 0.68%   |
| 51-100         | 2        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 77       | 25.67%  |
| 101-250        | 52       | 17.33%  |
| 51-100         | 40       | 13.33%  |
| 501-1000       | 34       | 11.33%  |
| 21-50          | 31       | 10.33%  |
| 251-500        | 26       | 8.67%   |
| 1001-2000      | 19       | 6.33%   |
| More than 3000 | 10       | 3.33%   |
| 2001-3000      | 8        | 2.67%   |
| Unknown        | 3        | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WDS250G2B0A-00SM50 250GB SSD | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 100%    |

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
| Detected | 286      | 761    | 98.28%  |
| Works    | 4        | 5      | 1.37%   |
| Malfunc  | 1        | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 168      | 31.94%  |
| Intel                          | 103      | 19.58%  |
| Samsung Electronics            | 55       | 10.46%  |
| Sandisk                        | 38       | 7.22%   |
| Phison Electronics             | 28       | 5.32%   |
| Micron/Crucial Technology      | 24       | 4.56%   |
| Kingston Technology Company    | 22       | 4.18%   |
| MAXIO Technology (Hangzhou)    | 16       | 3.04%   |
| Silicon Motion                 | 11       | 2.09%   |
| ASMedia Technology             | 10       | 1.9%    |
| Realtek Semiconductor          | 7        | 1.33%   |
| SK hynix                       | 6        | 1.14%   |
| Shenzhen Longsys Electronics   | 5        | 0.95%   |
| ADATA Technology               | 5        | 0.95%   |
| Micron Technology              | 4        | 0.76%   |
| Toshiba America Info Systems   | 3        | 0.57%   |
| Marvell Technology Group       | 3        | 0.57%   |
| KIOXIA                         | 3        | 0.57%   |
| Solidigm                       | 2        | 0.38%   |
| Seagate Technology             | 2        | 0.38%   |
| INNOGRIT                       | 2        | 0.38%   |
| Hosin Global Electronics       | 2        | 0.38%   |
| Union Memory (Shenzhen)        | 1        | 0.19%   |
| Transcend                      | 1        | 0.19%   |
| TenaFe                         | 1        | 0.19%   |
| Solid State Storage Technology | 1        | 0.19%   |
| O2 Micro                       | 1        | 0.19%   |
| Biwin Storage Technology       | 1        | 0.19%   |
| Apple                          | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 79       | 12.95%  |
| AMD 500 Series Chipset SATA Controller                                         | 45       | 7.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 43       | 7.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23       | 3.77%   |
| AMD 600 Series Chipset SATA Controller                                         | 23       | 3.77%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13       | 2.13%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 13       | 2.13%   |
| AMD 300 Series Chipset SATA Controller                                         | 13       | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 12       | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 10       | 1.64%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10       | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10       | 1.64%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10       | 1.64%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 10       | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9        | 1.48%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 8        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8        | 1.31%   |
| Intel SATA Controller [RAID mode]                                              | 8        | 1.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8        | 1.31%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 7        | 1.15%   |
| Phison E12 NVMe Controller                                                     | 7        | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7        | 1.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6        | 0.98%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 5        | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5        | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                               | 5        | 0.82%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 5        | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5        | 0.82%   |
| AMD X370 Series Chipset SATA Controller                                        | 5        | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 4        | 0.66%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 4        | 0.66%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4        | 0.66%   |
| Phison E18 PCIe4 NVMe Controller                                               | 4        | 0.66%   |
| Micron/Crucial P3 Plus NVMe PCIe SSD (DRAM-less)                               | 4        | 0.66%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 4        | 0.66%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 4        | 0.66%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 4        | 0.66%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 253      | 51.84%  |
| NVMe | 214      | 43.85%  |
| RAID | 16       | 3.28%   |
| IDE  | 4        | 0.82%   |
| SAS  | 1        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 185      | 64.24%  |
| Intel  | 103      | 35.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics  | 17       | 5.9%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 11       | 3.82%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 7        | 2.43%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 7        | 2.43%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 7        | 2.43%   |
| AMD Ryzen 5 3600 6-Core Processor       | 7        | 2.43%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 7        | 2.43%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 7        | 2.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 6        | 2.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 5        | 1.74%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 5        | 1.74%   |
| AMD Ryzen 5 7600X 6-Core Processor      | 5        | 1.74%   |
| AMD Ryzen 5 5600 6-Core Processor       | 5        | 1.74%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 4        | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 4        | 1.39%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 4        | 1.39%   |
| AMD Ryzen 7 9800X3D 8-Core Processor    | 4        | 1.39%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 4        | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4        | 1.39%   |
| AMD Ryzen 5 5500                        | 4        | 1.39%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 4        | 1.39%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 4        | 1.39%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 3        | 1.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3        | 1.04%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 3        | 1.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 3        | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3        | 1.04%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 3        | 1.04%   |
| AMD Ryzen 9 7950X 16-Core Processor     | 3        | 1.04%   |
| AMD Ryzen 9 6900HX with Radeon Graphics | 3        | 1.04%   |
| AMD Ryzen 7 7800X3D 8-Core Processor    | 3        | 1.04%   |
| AMD Ryzen 5 4500 6-Core Processor       | 3        | 1.04%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 2        | 0.69%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz     | 2        | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2        | 0.69%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 2        | 0.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2        | 0.69%   |
| Intel 13th Gen Core i5-13600K           | 2        | 0.69%   |
| Intel 12th Gen Core i3-12100F           | 2        | 0.69%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz | 2        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 87       | 30.21%  |
| AMD Ryzen 7            | 48       | 16.67%  |
| Intel Core i7          | 34       | 11.81%  |
| AMD Ryzen 9            | 30       | 10.42%  |
| Intel Core i5          | 29       | 10.07%  |
| Other                  | 16       | 5.56%   |
| Intel Xeon             | 16       | 5.56%   |
| Intel Core i3          | 5        | 1.74%   |
| AMD Ryzen 5 PRO        | 5        | 1.74%   |
| AMD Ryzen 3            | 5        | 1.74%   |
| AMD Ryzen Threadripper | 3        | 1.04%   |
| AMD FX                 | 3        | 1.04%   |
| Intel Core i9          | 2        | 0.69%   |
| Intel Celeron          | 1        | 0.35%   |
| AMD Ryzen 7 PRO        | 1        | 0.35%   |
| AMD E                  | 1        | 0.35%   |
| AMD Athlon X4          | 1        | 0.35%   |
| AMD Athlon             | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 106      | 36.81%  |
| 4      | 67       | 23.26%  |
| 8      | 64       | 22.22%  |
| 12     | 27       | 9.38%   |
| 16     | 10       | 3.47%   |
| 14     | 4        | 1.39%   |
| 2      | 4        | 1.39%   |
| 3      | 2        | 0.69%   |
| 32     | 1        | 0.35%   |
| 28     | 1        | 0.35%   |
| 24     | 1        | 0.35%   |
| 18     | 1        | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 281      | 97.57%  |
| 2      | 7        | 2.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 250      | 86.81%  |
| 1      | 38       | 13.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 288      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 287      | 99.65%  |
| 0x08701021 | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 65       | 22.57%  |
| Unknown          | 56       | 19.44%  |
| Zen+             | 31       | 10.76%  |
| Zen 2            | 30       | 10.42%  |
| KabyLake         | 25       | 8.68%   |
| Haswell          | 22       | 7.64%   |
| Zen              | 15       | 5.21%   |
| Skylake          | 11       | 3.82%   |
| IvyBridge        | 8        | 2.78%   |
| CometLake        | 8        | 2.78%   |
| SandyBridge      | 5        | 1.74%   |
| Broadwell        | 4        | 1.39%   |
| Westmere         | 3        | 1.04%   |
| Piledriver       | 3        | 1.04%   |
| Steamroller      | 1        | 0.35%   |
| Alderlake Hybrid | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 236      | 74.21%  |
| Nvidia | 56       | 17.61%  |
| Intel  | 26       | 8.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 37       | 10.76%  |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 24       | 6.98%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 19       | 5.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 19       | 5.52%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 18       | 5.23%   |
| AMD Raphael                                                                 | 14       | 4.07%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]       | 14       | 4.07%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 12       | 3.49%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 11       | 3.2%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 10       | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 2.62%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 8        | 2.33%   |
| AMD Rembrandt [Radeon 680M]                                                 | 7        | 2.03%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 7        | 2.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 2.03%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 6        | 1.74%   |
| AMD Navi 48 [Radeon RX 9070/9070 XT/9070 GRE]                               | 6        | 1.74%   |
| AMD Granite Ridge [Radeon Graphics]                                         | 6        | 1.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.45%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 5        | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.16%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.16%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 4        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.16%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.87%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 0.87%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 3        | 0.87%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 3        | 0.87%   |
| AMD HawkPoint1                                                              | 3        | 0.87%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 0.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.58%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 198      | 68.04%  |
| 1 x Nvidia     | 42       | 14.43%  |
| 2 x AMD        | 25       | 8.59%   |
| AMD + Nvidia   | 10       | 3.44%   |
| 1 x Intel      | 7        | 2.41%   |
| Intel + AMD    | 5        | 1.72%   |
| Intel + Nvidia | 4        | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 261      | 90.63%  |
| Proprietary | 27       | 9.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 261      | 90.31%  |
| 7.01-8.0   | 10       | 3.46%   |
| 3.01-4.0   | 9        | 3.11%   |
| 5.01-6.0   | 3        | 1.04%   |
| 16.01-24.0 | 2        | 0.69%   |
| 8.01-16.0  | 2        | 0.69%   |
| 2.01-3.0   | 1        | 0.35%   |
| 1.01-2.0   | 1        | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 45       | 15.1%   |
| Goldstar             | 36       | 12.08%  |
| Dell                 | 18       | 6.04%   |
| AOC                  | 17       | 5.7%    |
| Acer                 | 17       | 5.7%    |
| ASUSTek Computer     | 15       | 5.03%   |
| Hewlett-Packard      | 13       | 4.36%   |
| MSI                  | 11       | 3.69%   |
| Ancor Communications | 11       | 3.69%   |
| Philips              | 10       | 3.36%   |
| ViewSonic            | 8        | 2.68%   |
| Sony                 | 7        | 2.35%   |
| Lenovo               | 6        | 2.01%   |
| Toshiba              | 5        | 1.68%   |
| Hitachi              | 5        | 1.68%   |
| Gigabyte Technology  | 4        | 1.34%   |
| BenQ                 | 4        | 1.34%   |
| Unknown (XXX)        | 3        | 1.01%   |
| Sceptre Tech         | 3        | 1.01%   |
| Pixio                | 3        | 1.01%   |
| Mi                   | 3        | 1.01%   |
| Valve                | 2        | 0.67%   |
| Unknown              | 2        | 0.67%   |
| SAC                  | 2        | 0.67%   |
| RTK                  | 2        | 0.67%   |
| Roku                 | 2        | 0.67%   |
| Panasonic            | 2        | 0.67%   |
| ONN                  | 2        | 0.67%   |
| Onkyo                | 2        | 0.67%   |
| MStar                | 2        | 0.67%   |
| Iiyama               | 2        | 0.67%   |
| HKC                  | 2        | 0.67%   |
| HannStar             | 2        | 0.67%   |
| ___                  | 1        | 0.34%   |
| Xiaomi               | 1        | 0.34%   |
| WIT                  | 1        | 0.34%   |
| Wacom                | 1        | 0.34%   |
| VIE                  | 1        | 0.34%   |
| Vestel Elektronik    | 1        | 0.34%   |
| TCL                  | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 4        | 1.3%    |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 3        | 0.97%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 3        | 0.97%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                  | 3        | 0.97%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 3        | 0.97%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 2        | 0.65%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 2        | 0.65%   |
| Valve Index HMD VLV91A8                                                 | 2        | 0.65%   |
| Toshiba TV TSB0206 1920x1080                                            | 2        | 0.65%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.65%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2        | 0.65%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 2        | 0.65%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch      | 2        | 0.65%   |
| Pixio SFP2702G FHD WAM2700 1920x1080 597x336mm 27.0-inch                | 2        | 0.65%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 2        | 0.65%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 2        | 0.65%   |
| MSI G273Q MSI3CA8 2560x1440 597x336mm 27.0-inch                         | 2        | 0.65%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch                | 2        | 0.65%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 0.65%   |
| Dell U3415W DELA0A6 3440x1440 798x335mm 34.1-inch                       | 2        | 0.65%   |
| Dell S3220DGF DELD0F2 2560x1440 697x392mm 31.5-inch                     | 2        | 0.65%   |
| ASUSTek Computer XG438 AUS43E1 3840x2160 940x530mm 42.5-inch            | 2        | 0.65%   |
| AOC 32G2WG3 AOC3202 1920x1080 698x393mm 31.5-inch                       | 2        | 0.65%   |
| AOC 32G1WG4 AOC3201 1920x1080 697x392mm 31.5-inch                       | 2        | 0.65%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                        | 2        | 0.65%   |
| ___ LCD TV ___9000 1360x768                                             | 1        | 0.32%   |
| Xiaomi Mi TV XMD0076 3840x2160 1110x620mm 50.1-inch                     | 1        | 0.32%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                          | 1        | 0.32%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 0.32%   |
| ViewSonic XG270QG VSCF838 2560x1440 608x355mm 27.7-inch                 | 1        | 0.32%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch              | 1        | 0.32%   |
| ViewSonic VX2758-C-MH VSC35DD 1920x1080 597x336mm 27.0-inch             | 1        | 0.32%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch           | 1        | 0.32%   |
| VIE ATHEN V3 27 VIE2700 1920x1080 597x236mm 25.3-inch                   | 1        | 0.32%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch    | 1        | 0.32%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                        | 1        | 0.32%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 0.32%   |
| Toshiba TV TSB0205 1360x765                                             | 1        | 0.32%   |
| Toshiba TV TSB010E 1920x1080 1036x585mm 46.8-inch                       | 1        | 0.32%   |
| Toshiba SANTEC SLM LCD1000 1920x1080 870x520mm 39.9-inch                | 1        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 123      | 42.86%  |
| 3840x2160 (4K)     | 72       | 25.09%  |
| 2560x1440 (QHD)    | 38       | 13.24%  |
| 3440x1440          | 11       | 3.83%   |
| 2560x1080          | 11       | 3.83%   |
| 3840x1080          | 7        | 2.44%   |
| 1366x768 (WXGA)    | 6        | 2.09%   |
| 1680x1050 (WSXGA+) | 3        | 1.05%   |
| 1920x1200 (WUXGA)  | 2        | 0.7%    |
| 1600x900 (HD+)     | 2        | 0.7%    |
| 1440x900 (WXGA+)   | 2        | 0.7%    |
| 1360x768           | 2        | 0.7%    |
| 1280x1024 (SXGA)   | 2        | 0.7%    |
| Unknown            | 2        | 0.7%    |
| 2560x1600          | 1        | 0.35%   |
| 2160x1440          | 1        | 0.35%   |
| 1400x1050          | 1        | 0.35%   |
| 1024x768 (XGA)     | 1        | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 53       | 17.79%  |
| 31      | 40       | 13.42%  |
| 24      | 39       | 13.09%  |
| 23      | 31       | 10.4%   |
| 34      | 17       | 5.7%    |
| 84      | 14       | 4.7%    |
| 21      | 14       | 4.7%    |
| 72      | 10       | 3.36%   |
| 63      | 7        | 2.35%   |
| 18      | 6        | 2.01%   |
| 15      | 6        | 2.01%   |
| Unknown | 5        | 1.68%   |
| 65      | 4        | 1.34%   |
| 48      | 4        | 1.34%   |
| 52      | 3        | 1.01%   |
| 49      | 3        | 1.01%   |
| 46      | 3        | 1.01%   |
| 32      | 3        | 1.01%   |
| 28      | 3        | 1.01%   |
| 22      | 3        | 1.01%   |
| 19      | 3        | 1.01%   |
| 74      | 2        | 0.67%   |
| 54      | 2        | 0.67%   |
| 43      | 2        | 0.67%   |
| 42      | 2        | 0.67%   |
| 39      | 2        | 0.67%   |
| 29      | 2        | 0.67%   |
| 26      | 2        | 0.67%   |
| 20      | 2        | 0.67%   |
| 85      | 1        | 0.34%   |
| 82      | 1        | 0.34%   |
| 75      | 1        | 0.34%   |
| 64      | 1        | 0.34%   |
| 58      | 1        | 0.34%   |
| 57      | 1        | 0.34%   |
| 47      | 1        | 0.34%   |
| 40      | 1        | 0.34%   |
| 35      | 1        | 0.34%   |
| 25      | 1        | 0.34%   |
| 16      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 109      | 37.72%  |
| 601-700     | 54       | 18.69%  |
| 1001-1500   | 31       | 10.73%  |
| 1501-2000   | 29       | 10.03%  |
| 401-500     | 23       | 7.96%   |
| 701-800     | 19       | 6.57%   |
| 301-350     | 7        | 2.42%   |
| 801-900     | 5        | 1.73%   |
| Unknown     | 5        | 1.73%   |
| 351-400     | 4        | 1.38%   |
| 901-1000    | 3        | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 226      | 82.78%  |
| 21/9    | 21       | 7.69%   |
| 16/10   | 13       | 4.76%   |
| 32/9    | 7        | 2.56%   |
| 5/4     | 2        | 0.73%   |
| Unknown | 2        | 0.73%   |
| 6/5     | 1        | 0.37%   |
| 4/3     | 1        | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 70       | 23.81%  |
| 351-500        | 63       | 21.43%  |
| 301-350        | 56       | 19.05%  |
| More than 1000 | 47       | 15.99%  |
| 501-1000       | 16       | 5.44%   |
| 251-300        | 14       | 4.76%   |
| 151-200        | 11       | 3.74%   |
| 101-110        | 6        | 2.04%   |
| Unknown        | 5        | 1.7%    |
| 141-150        | 4        | 1.36%   |
| 131-140        | 1        | 0.34%   |
| 111-120        | 1        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 174      | 63.27%  |
| 101-120 | 49       | 17.82%  |
| 1-50    | 24       | 8.73%   |
| 121-160 | 19       | 6.91%   |
| Unknown | 5        | 1.82%   |
| 161-240 | 4        | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 249      | 85.57%  |
| 2     | 39       | 13.4%   |
| 3     | 3        | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 198      | 43.42%  |
| Intel                                  | 134      | 29.39%  |
| MediaTek                               | 30       | 6.58%   |
| Broadcom                               | 18       | 3.95%   |
| TP-Link                                | 17       | 3.73%   |
| Microsoft                              | 12       | 2.63%   |
| Qualcomm Atheros                       | 10       | 2.19%   |
| Samsung Electronics                    | 5        | 1.1%    |
| Xiaomi                                 | 3        | 0.66%   |
| Ralink Technology                      | 3        | 0.66%   |
| OPPO Electronics                       | 3        | 0.66%   |
| Motorola PCS                           | 2        | 0.44%   |
| Google                                 | 2        | 0.44%   |
| D-Link                                 | 2        | 0.44%   |
| Broadcom Limited                       | 2        | 0.44%   |
| ASUSTek Computer                       | 2        | 0.44%   |
| Aquantia                               | 2        | 0.44%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.22%   |
| Sitecom Europe                         | 1        | 0.22%   |
| Realtek                                | 1        | 0.22%   |
| QinHeng Electronics                    | 1        | 0.22%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.22%   |
| Linksys                                | 1        | 0.22%   |
| Huawei Technologies                    | 1        | 0.22%   |
| Espressif                              | 1        | 0.22%   |
| Belkin Components                      | 1        | 0.22%   |
| Apple                                  | 1        | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 146      | 27.29%  |
| Realtek RTL8125 2.5GbE Controller                                               | 39       | 7.29%   |
| Intel Wi-Fi 6 AX200                                                             | 30       | 5.61%   |
| Intel I211 Gigabit Network Connection                                           | 21       | 3.93%   |
| Intel Ethernet Controller I225-V                                                | 19       | 3.55%   |
| Intel Ethernet Connection (2) I219-V                                            | 16       | 2.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 12       | 2.24%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                    | 11       | 2.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 10       | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 10       | 1.87%   |
| Intel Ethernet Controller I226-V                                                | 9        | 1.68%   |
| Realtek 802.11ac NIC                                                            | 7        | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 6        | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 6        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 6        | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 5        | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 5        | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 5        | 0.93%   |
| Microsoft Xbox Wireless Adapter for Windows                                     | 5        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                            | 5        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                                            | 5        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                     | 4        | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                              | 4        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 4        | 0.75%   |
| Microsoft Xbox 360 Wireless Adapter                                             | 4        | 0.75%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 4        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 4        | 0.75%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 4        | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 3        | 0.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                             | 3        | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 3        | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 3        | 0.56%   |
| Microsoft Wireless XBox Controller Dongle                                       | 3        | 0.56%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]            | 3        | 0.56%   |
| Intel Wireless 8260                                                             | 3        | 0.56%   |
| Intel Wireless 7265                                                             | 3        | 0.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 3        | 0.56%   |
| Intel Ethernet Connection I217-V                                                | 3        | 0.56%   |
| Intel Ethernet Connection (12) I219-V                                           | 3        | 0.56%   |
| Intel 82574L Gigabit Network Connection                                         | 3        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 74       | 37.37%  |
| Realtek Semiconductor                 | 30       | 15.15%  |
| MediaTek                              | 26       | 13.13%  |
| Broadcom                              | 18       | 9.09%   |
| TP-Link                               | 17       | 8.59%   |
| Microsoft                             | 12       | 6.06%   |
| Qualcomm Atheros                      | 7        | 3.54%   |
| Ralink Technology                     | 3        | 1.52%   |
| D-Link                                | 2        | 1.01%   |
| Broadcom Limited                      | 2        | 1.01%   |
| ASUSTek Computer                      | 2        | 1.01%   |
| Sitecom Europe                        | 1        | 0.51%   |
| Realtek                               | 1        | 0.51%   |
| Linksys                               | 1        | 0.51%   |
| Belkin Components                     | 1        | 0.51%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 30       | 14.93%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 11       | 5.47%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 11       | 5.47%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 10       | 4.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 10       | 4.98%   |
| Realtek 802.11ac NIC                                                                          | 7        | 3.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 6        | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 2.49%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 5        | 2.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 4        | 1.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 1.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 1.99%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 4        | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4        | 1.99%   |
| Intel 700 Series Chipset CNVi WiFi                                                            | 4        | 1.99%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 3        | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 3        | 1.49%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 3        | 1.49%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]                          | 3        | 1.49%   |
| Intel Wireless 8260                                                                           | 3        | 1.49%   |
| Intel Wireless 7265                                                                           | 3        | 1.49%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 3        | 1.49%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                                  | 3        | 1.49%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2        | 1%      |
| TP-Link 802.11ac WLAN Adapter                                                                 | 2        | 1%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 2        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 1%      |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 1%      |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360]               | 2        | 1%      |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                                                        | 2        | 1%      |
| Intel Wireless 7260                                                                           | 2        | 1%      |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 2        | 1%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.5%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 0.5%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.5%    |
| TP-Link 802.11n NIC                                                                           | 1        | 0.5%    |
| Sitecom Europe 802.11n WLAN Adapter                                                           | 1        | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 193      | 60.5%   |
| Intel                         | 97       | 30.41%  |
| Qualcomm Atheros              | 6        | 1.88%   |
| Samsung Electronics           | 5        | 1.57%   |
| MediaTek                      | 4        | 1.25%   |
| Xiaomi                        | 3        | 0.94%   |
| OPPO Electronics              | 3        | 0.94%   |
| Motorola PCS                  | 2        | 0.63%   |
| Google                        | 2        | 0.63%   |
| Aquantia                      | 2        | 0.63%   |
| OnePlus Technology (Shenzhen) | 1        | 0.31%   |
| Huawei Technologies           | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 146      | 44.24%  |
| Realtek RTL8125 2.5GbE Controller                                               | 39       | 11.82%  |
| Intel I211 Gigabit Network Connection                                           | 21       | 6.36%   |
| Intel Ethernet Controller I225-V                                                | 19       | 5.76%   |
| Intel Ethernet Connection (2) I219-V                                            | 16       | 4.85%   |
| Intel Ethernet Controller I226-V                                                | 9        | 2.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 6        | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 6        | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 5        | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                            | 5        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                                            | 5        | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 3        | 0.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 3        | 0.91%   |
| Intel Ethernet Connection I217-V                                                | 3        | 0.91%   |
| Intel Ethernet Connection (12) I219-V                                           | 3        | 0.91%   |
| Intel 82574L Gigabit Network Connection                                         | 3        | 0.91%   |
| Realtek RTL8126 5GbE Controller                                                 | 2        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 2        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 2        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 2        | 0.61%   |
| OPPO Ace 3V                                                                     | 2        | 0.61%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 2        | 0.61%   |
| Intel Ethernet Connection I217-LM                                               | 2        | 0.61%   |
| Intel Ethernet Connection (14) I219-V                                           | 2        | 0.61%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 2        | 0.61%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter                        | 1        | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 1        | 0.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 1        | 0.3%    |
| OPPO RMX3741                                                                    | 1        | 0.3%    |
| OnePlus (Shenzhen) BE2029                                                       | 1        | 0.3%    |
| Motorola PCS motorola one 5G ace                                                | 1        | 0.3%    |
| Motorola PCS moto g100 pro                                                      | 1        | 0.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 1        | 0.3%    |
| MediaTek A015                                                                   | 1        | 0.3%    |
| Intel I210 Gigabit Network Connection                                           | 1        | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                                           | 1        | 0.3%    |
| Intel Ethernet Connection (5) I219-V                                            | 1        | 0.3%    |
| Intel Ethernet Connection (2) I218-LM                                           | 1        | 0.3%    |
| Intel Ethernet Connection (17) I219-V                                           | 1        | 0.3%    |
| Intel Ethernet Connection (17) I219-LM                                          | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 286      | 60.34%  |
| WiFi     | 184      | 38.82%  |
| Modem    | 3        | 0.63%   |
| Unknown  | 1        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 224      | 74.92%  |
| WiFi     | 75       | 25.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 137      | 47.4%   |
| 2     | 131      | 45.33%  |
| 3     | 19       | 6.57%   |
| 0     | 2        | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 186      | 64.36%  |
| Yes  | 103      | 35.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 71       | 37.17%  |
| Cambridge Silicon Radio         | 25       | 13.09%  |
| Realtek Semiconductor           | 19       | 9.95%   |
| MediaTek                        | 13       | 6.81%   |
| IMC Networks                    | 12       | 6.28%   |
| Foxconn / Hon Hai               | 11       | 5.76%   |
| TP-Link                         | 9        | 4.71%   |
| ASUSTek Computer                | 8        | 4.19%   |
| Apple                           | 7        | 3.66%   |
| Qualcomm Atheros Communications | 5        | 2.62%   |
| Broadcom                        | 3        | 1.57%   |
| Unknown                         | 3        | 1.57%   |
| Realtek                         | 1        | 0.52%   |
| Integrated System Solution      | 1        | 0.52%   |
| HTC (High Tech Computer)        | 1        | 0.52%   |
| Dynex                           | 1        | 0.52%   |
| Cypress Semiconductor           | 1        | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 28       | 14.66%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 25       | 13.09%  |
| Realtek Bluetooth Radio                                              | 17       | 8.9%    |
| MediaTek Wireless_Device                                             | 13       | 6.81%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 10       | 5.24%   |
| Intel AX210 Bluetooth                                                | 10       | 5.24%   |
| TP-Link TP-T@- UB500 Adapter                                         | 9        | 4.71%   |
| Intel Bluetooth wireless interface                                   | 9        | 4.71%   |
| Foxconn / Hon Hai Wireless_Device                                    | 9        | 4.71%   |
| IMC Networks Wireless_Device                                         | 8        | 4.19%   |
| Apple Bluetooth Host Controller                                      | 6        | 3.14%   |
| Intel Bluetooth Device                                               | 4        | 2.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 2.09%   |
| ASUS ASUS USB-BT500                                                  | 4        | 2.09%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 1.57%   |
| Intel AX201 Bluetooth                                                | 3        | 1.57%   |
| IMC Networks Bluetooth Radio                                         | 3        | 1.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3        | 1.57%   |
| Unknown                                                              | 3        | 1.57%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 1.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.05%   |
| Realtek Bluetooth Radio                                              | 1        | 0.52%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.52%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.52%   |
| IMC Networks Bluetooth Device                                        | 1        | 0.52%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.52%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                      | 1        | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1        | 0.52%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.52%   |
| Cypress CYW20704A2                                                   | 1        | 0.52%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.52%   |
| ASUS BCM20702A0                                                      | 1        | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 251      | 47.72%  |
| Intel                                        | 101      | 19.2%   |
| Nvidia                                       | 56       | 10.65%  |
| Logitech                                     | 19       | 3.61%   |
| C-Media Electronics                          | 13       | 2.47%   |
| SteelSeries ApS                              | 7        | 1.33%   |
| ASUSTek Computer                             | 7        | 1.33%   |
| JMTek                                        | 6        | 1.14%   |
| Hewlett-Packard                              | 4        | 0.76%   |
| Focusrite-Novation                           | 4        | 0.76%   |
| Creative Labs                                | 4        | 0.76%   |
| Valve Software                               | 3        | 0.57%   |
| Realtek Semiconductor                        | 3        | 0.57%   |
| Razer USA                                    | 3        | 0.57%   |
| Micro Star International                     | 3        | 0.57%   |
| Medeli Electronics                           | 3        | 0.57%   |
| Kingston Technology                          | 3        | 0.57%   |
| Corsair                                      | 3        | 0.57%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.38%   |
| Sony                                         | 2        | 0.38%   |
| GN Netcom                                    | 2        | 0.38%   |
| Bose                                         | 2        | 0.38%   |
| Apple                                        | 2        | 0.38%   |
| Weltrend Semiconductor                       | 1        | 0.19%   |
| Texas Instruments                            | 1        | 0.19%   |
| Tenx Technology                              | 1        | 0.19%   |
| TC Electronic                                | 1        | 0.19%   |
| Sterling                                     | 1        | 0.19%   |
| Setek Elektronik                             | 1        | 0.19%   |
| Schiit Audio                                 | 1        | 0.19%   |
| RODE Microphones                             | 1        | 0.19%   |
| Quanta                                       | 1        | 0.19%   |
| QinHeng Electronics                          | 1        | 0.19%   |
| PreSonus Audio Electronics                   | 1        | 0.19%   |
| Onkyo                                        | 1        | 0.19%   |
| Maono                                        | 1        | 0.19%   |
| Lenovo                                       | 1        | 0.19%   |
| Jieli Technology                             | 1        | 0.19%   |
| Giga-Byte Technology                         | 1        | 0.19%   |
| FiiO Electronics Technology                  | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 80       | 10.9%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 70       | 9.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 56       | 7.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 42       | 5.72%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 36       | 4.9%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 33       | 4.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 32       | 4.36%   |
| AMD Radeon High Definition Audio Controller                                | 31       | 4.22%   |
| AMD Navi 10 HDMI Audio                                                     | 26       | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 1.77%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12       | 1.63%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.36%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 1.09%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 0.95%   |
| ASUSTek Computer USB Audio                                                 | 7        | 0.95%   |
| AMD Navi 48 HDMI/DP Audio Controller                                       | 7        | 0.95%   |
| JMTek USB PnP Audio Device                                                 | 6        | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 0.82%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 6        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 0.68%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5        | 0.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.54%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.54%   |
| Nvidia AD102 High Definition Audio Controller                              | 4        | 0.54%   |
| Logitech G435 Wireless Gaming Headset                                      | 4        | 0.54%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.54%   |
| C-Media Electronics USB Audio Device                                       | 4        | 0.54%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 3        | 0.41%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| G.Skill | 2        | 66.67%  |
| Unknown | 1        | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3600MT/s | 1        | 33.33%  |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1867MT/s  | 1        | 33.33%  |
| Unknown                                            | 1        | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR5 | 1        | 33.33%  |
| DDR4 | 1        | 33.33%  |
| DDR3 | 1        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 2        | 66.67%  |
| SODIMM | 1        | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2        | 66.67%  |
| 32768 | 1        | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 5600  | 1        | 33.33%  |
| 3600  | 1        | 33.33%  |
| 1867  | 1        | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 51.52%  |
| Valve Software                | 3        | 9.09%   |
| Tobii Technology AB           | 2        | 6.06%   |
| Sunplus Innovation Technology | 2        | 6.06%   |
| Microdia                      | 2        | 6.06%   |
| Realtek Semiconductor         | 1        | 3.03%   |
| Razer USA                     | 1        | 3.03%   |
| Quanta                        | 1        | 3.03%   |
| Magic Control Technology      | 1        | 3.03%   |
| IPEVO                         | 1        | 3.03%   |
| Generalplus Technology        | 1        | 3.03%   |
| Apple                         | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 4        | 11.76%  |
| Valve Software 3D Camera        | 3        | 8.82%   |
| Logitech HD Pro Webcam C920     | 3        | 8.82%   |
| Tobii AB EyeChip                | 2        | 5.88%   |
| Microdia Webcam Vitade AF       | 2        | 5.88%   |
| Logitech BRIO Ultra HD Webcam   | 2        | 5.88%   |
| Sunplus USB 2.0 Camera          | 1        | 2.94%   |
| Sunplus NexiGo N940P 2K Webcam  | 1        | 2.94%   |
| Realtek USB Camera              | 1        | 2.94%   |
| Razer USA Razer Kiyo Pro        | 1        | 2.94%   |
| Quanta HD Camera                | 1        | 2.94%   |
| Magic Control j5 WebCam JVCU100 | 1        | 2.94%   |
| Logitech Webcam C930e           | 1        | 2.94%   |
| Logitech HD Webcam C910         | 1        | 2.94%   |
| Logitech HD Webcam C615         | 1        | 2.94%   |
| Logitech HD Webcam C525         | 1        | 2.94%   |
| Logitech HD Webcam B910         | 1        | 2.94%   |
| Logitech CrystalCam             | 1        | 2.94%   |
| Logitech C922 Pro Stream Webcam | 1        | 2.94%   |
| Logitech C920 PRO HD Webcam     | 1        | 2.94%   |
| Logitech B525 HD Webcam         | 1        | 2.94%   |
| IPEVO IPEVO V4K                 | 1        | 2.94%   |
| Generalplus GENERAL WEBCAM      | 1        | 2.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 221      | 76.21%  |
| 1     | 56       | 19.31%  |
| 2     | 12       | 4.14%   |
| 4     | 1        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 41       | 49.4%   |
| Unassigned class         | 9        | 10.84%  |
| Multimedia controller    | 9        | 10.84%  |
| Graphics card            | 9        | 10.84%  |
| Net/ethernet             | 4        | 4.82%   |
| Network                  | 3        | 3.61%   |
| Sound                    | 2        | 2.41%   |
| Bluetooth                | 2        | 2.41%   |
| Storage/raid             | 1        | 1.2%    |
| Fingerprint reader       | 1        | 1.2%    |
| Communication controller | 1        | 1.2%    |
| Camera                   | 1        | 1.2%    |

