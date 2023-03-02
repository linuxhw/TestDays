Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 4823

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z77X-UP4 TH                 | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [0e0b3360ba](https://linux-hardware.org/?probe=0e0b3360ba) | Feb 28, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [7f53a53eba](https://linux-hardware.org/?probe=7f53a53eba) | Feb 28, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Dell          | 03KWTV A02                  | [8b6eae9fd5](https://linux-hardware.org/?probe=8b6eae9fd5) | Feb 26, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| MSI           | B450-A PRO MAX              | [f081452f55](https://linux-hardware.org/?probe=f081452f55) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [42fe607d11](https://linux-hardware.org/?probe=42fe607d11) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| ZOTAC         | MEK1                        | [a61a52d794](https://linux-hardware.org/?probe=a61a52d794) | Feb 24, 2023 |
| HP            | 8433 11                     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [59d0e692ef](https://linux-hardware.org/?probe=59d0e692ef) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27a3c3c4c1](https://linux-hardware.org/?probe=27a3c3c4c1) | Feb 24, 2023 |
| Dell          | 0M6C7G A00                  | [8d8af65e26](https://linux-hardware.org/?probe=8d8af65e26) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | [f8f5ea8885](https://linux-hardware.org/?probe=f8f5ea8885) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | [ea890b85f3](https://linux-hardware.org/?probe=ea890b85f3) | Feb 22, 2023 |
| Gigabyte      | H81M-HD3                    | [d19e079879](https://linux-hardware.org/?probe=d19e079879) | Feb 22, 2023 |
| ASRock        | B550 Extreme4               | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [7dd9134373](https://linux-hardware.org/?probe=7dd9134373) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [fafea002be](https://linux-hardware.org/?probe=fafea002be) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| Alienware     | 0NWN7M A00                  | [eef5c2f68f](https://linux-hardware.org/?probe=eef5c2f68f) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [2ea45a0d80](https://linux-hardware.org/?probe=2ea45a0d80) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| ASRock        | A520M-HVS                   | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| ASRock        | H87 Performance             | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [8df8fe9ae8](https://linux-hardware.org/?probe=8df8fe9ae8) | Feb 19, 2023 |
| Lenovo        | 1036 NO DPK                 | [b99541f6ad](https://linux-hardware.org/?probe=b99541f6ad) | Feb 19, 2023 |
| Dell          | 0NNNCT A01                  | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| HP            | 8437                        | [f8f0f71bf5](https://linux-hardware.org/?probe=f8f0f71bf5) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c82882e708](https://linux-hardware.org/?probe=c82882e708) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [2ca590a85e](https://linux-hardware.org/?probe=2ca590a85e) | Feb 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [27c2ee6ee0](https://linux-hardware.org/?probe=27c2ee6ee0) | Feb 14, 2023 |
| Dell          | 0Y7WYT A00                  | [d94084bbee](https://linux-hardware.org/?probe=d94084bbee) | Feb 12, 2023 |
| ASRock        | B550M Steel Legend          | [2a6f501cb1](https://linux-hardware.org/?probe=2a6f501cb1) | Feb 12, 2023 |
| Dell          | 08WKV3 A00                  | [89ba42b53e](https://linux-hardware.org/?probe=89ba42b53e) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [687ecdce15](https://linux-hardware.org/?probe=687ecdce15) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [2c1562b21f](https://linux-hardware.org/?probe=2c1562b21f) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | [b82ab8816d](https://linux-hardware.org/?probe=b82ab8816d) | Feb 11, 2023 |
| HP            | 18E4                        | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [0b14ee6551](https://linux-hardware.org/?probe=0b14ee6551) | Feb 11, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [181c0e03e2](https://linux-hardware.org/?probe=181c0e03e2) | Feb 10, 2023 |
| Dell          | 0Y7WYT A00                  | [e4369afe1e](https://linux-hardware.org/?probe=e4369afe1e) | Feb 10, 2023 |
| ASUSTek       | A55BM-PLUS                  | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Samsung       | DeskTop System              | [2437c4afda](https://linux-hardware.org/?probe=2437c4afda) | Feb 10, 2023 |
| Biostar       | H81MHV3 5.0                 | [390c8dd03a](https://linux-hardware.org/?probe=390c8dd03a) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [17bf959fd0](https://linux-hardware.org/?probe=17bf959fd0) | Feb 09, 2023 |
| Acer          | Aspire M3970                | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [1c07b901bb](https://linux-hardware.org/?probe=1c07b901bb) | Feb 08, 2023 |
| HP            | 2129                        | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d8dcaddb54](https://linux-hardware.org/?probe=d8dcaddb54) | Feb 08, 2023 |
| ASRock        | B660 Pro-C/ax               | [31e10f0e68](https://linux-hardware.org/?probe=31e10f0e68) | Feb 07, 2023 |
| ASRock        | FM2A68M-HD+                 | [8588a36683](https://linux-hardware.org/?probe=8588a36683) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Gigabyte      | F2A55M-HD2                  | [fe95bfe3d3](https://linux-hardware.org/?probe=fe95bfe3d3) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [03a392d41f](https://linux-hardware.org/?probe=03a392d41f) | Feb 07, 2023 |
| Dell          | 02GDWG A00                  | [c0660c15fb](https://linux-hardware.org/?probe=c0660c15fb) | Feb 07, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [25fbfe1d66](https://linux-hardware.org/?probe=25fbfe1d66) | Feb 07, 2023 |
| System76      | Thelio thelio-r2            | [4cdf7d2895](https://linux-hardware.org/?probe=4cdf7d2895) | Feb 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [42dba6bdb3](https://linux-hardware.org/?probe=42dba6bdb3) | Feb 06, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a9bfc9669d](https://linux-hardware.org/?probe=a9bfc9669d) | Feb 06, 2023 |
| ASUSTek       | H81M-K                      | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| HP            | 8054                        | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [cd9d867630](https://linux-hardware.org/?probe=cd9d867630) | Feb 04, 2023 |
| Biostar       | H81MHV3 5.0                 | [084eee2317](https://linux-hardware.org/?probe=084eee2317) | Feb 03, 2023 |
| HP            | 834F                        | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [6d4ee8a3c6](https://linux-hardware.org/?probe=6d4ee8a3c6) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ffabf45521](https://linux-hardware.org/?probe=ffabf45521) | Feb 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [33ae030343](https://linux-hardware.org/?probe=33ae030343) | Jan 31, 2023 |
| MSI           | PRO Z690-P DDR4             | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3d555e69f7](https://linux-hardware.org/?probe=3d555e69f7) | Jan 30, 2023 |
| Intel         | H61                         | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [b07e189d3c](https://linux-hardware.org/?probe=b07e189d3c) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASUSTek       | GA35DX                      | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| ASUSTek       | PRIME B560M-K               | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [55d50f6d18](https://linux-hardware.org/?probe=55d50f6d18) | Jan 27, 2023 |
| HP            | 1495                        | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [df315d8050](https://linux-hardware.org/?probe=df315d8050) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [14a0252d88](https://linux-hardware.org/?probe=14a0252d88) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | [0b70a364b7](https://linux-hardware.org/?probe=0b70a364b7) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | [a42ba7ef9e](https://linux-hardware.org/?probe=a42ba7ef9e) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [e32b0f2c79](https://linux-hardware.org/?probe=e32b0f2c79) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| Acer          | Aspire M3970                | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3221475cc8](https://linux-hardware.org/?probe=3221475cc8) | Jan 24, 2023 |
| MSI           | B450M MORTAR MAX            | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [75acbba6b1](https://linux-hardware.org/?probe=75acbba6b1) | Jan 23, 2023 |
| ASRock        | AM1H-ITX                    | [82b094a66b](https://linux-hardware.org/?probe=82b094a66b) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [bfb889f5d5](https://linux-hardware.org/?probe=bfb889f5d5) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| MSI           | H81M-E34                    | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | [758ea69493](https://linux-hardware.org/?probe=758ea69493) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [d1b63bbd2d](https://linux-hardware.org/?probe=d1b63bbd2d) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [ebab459512](https://linux-hardware.org/?probe=ebab459512) | Jan 22, 2023 |
| ASUSTek       | G10DK                       | [1a27b660c2](https://linux-hardware.org/?probe=1a27b660c2) | Jan 21, 2023 |
| ASUSTek       | P8H77-V LE                  | [6dd531590e](https://linux-hardware.org/?probe=6dd531590e) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| Dell          | 0KC9NP A01                  | [ce0ba337df](https://linux-hardware.org/?probe=ce0ba337df) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| ASUSTek       | P8Z77-V LK                  | [a10fc5f5a9](https://linux-hardware.org/?probe=a10fc5f5a9) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | [ebc45fdfd5](https://linux-hardware.org/?probe=ebc45fdfd5) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | [0eae2f92fa](https://linux-hardware.org/?probe=0eae2f92fa) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | [f908807ed9](https://linux-hardware.org/?probe=f908807ed9) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6e8f360d6e](https://linux-hardware.org/?probe=6e8f360d6e) | Jan 17, 2023 |
| ASRock        | H87 Performance             | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H AC               | [22fca13d2b](https://linux-hardware.org/?probe=22fca13d2b) | Jan 17, 2023 |
| Gigabyte      | B450M S2H                   | [2ba8d32a71](https://linux-hardware.org/?probe=2ba8d32a71) | Jan 17, 2023 |
| Gateway       | WG43M                       | [af3a009366](https://linux-hardware.org/?probe=af3a009366) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | [48cc2e0e69](https://linux-hardware.org/?probe=48cc2e0e69) | Jan 17, 2023 |
| Gateway       | WG43M                       | [b0aa3af22f](https://linux-hardware.org/?probe=b0aa3af22f) | Jan 17, 2023 |
| ASRock        | H87 Performance             | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| ASRock        | B450 Pro4                   | [2e65fc8357](https://linux-hardware.org/?probe=2e65fc8357) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ba736834cd](https://linux-hardware.org/?probe=ba736834cd) | Jan 16, 2023 |
| HC            | HCAR357-MI V1.0             | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| ASRock        | B550 Extreme4               | [01f850d2fb](https://linux-hardware.org/?probe=01f850d2fb) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | [82f04ecd77](https://linux-hardware.org/?probe=82f04ecd77) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | [25db796fd6](https://linux-hardware.org/?probe=25db796fd6) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [d3896698c8](https://linux-hardware.org/?probe=d3896698c8) | Jan 14, 2023 |
| ASUSTek       | G10DK                       | [a92296f2e7](https://linux-hardware.org/?probe=a92296f2e7) | Jan 14, 2023 |
| Acer          | Aspire XC-603G              | [21e24944ad](https://linux-hardware.org/?probe=21e24944ad) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| ASUSTek       | P9X79-E WS                  | [e868d6909e](https://linux-hardware.org/?probe=e868d6909e) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [1921b19009](https://linux-hardware.org/?probe=1921b19009) | Jan 13, 2023 |
| HP            | 8299                        | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| ASUSTek       | H61M-E                      | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M71e 3157W8B    | [70078ceabd](https://linux-hardware.org/?probe=70078ceabd) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [ae12526ceb](https://linux-hardware.org/?probe=ae12526ceb) | Jan 11, 2023 |
| ASUSTek       | P9X79-E WS                  | [f3b4e5135f](https://linux-hardware.org/?probe=f3b4e5135f) | Jan 10, 2023 |
| HP            | 8433 11                     | [5e26cba33b](https://linux-hardware.org/?probe=5e26cba33b) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3982bc570e](https://linux-hardware.org/?probe=3982bc570e) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| MSI           | B350M BAZOOKA               | [e7d2bcfcfb](https://linux-hardware.org/?probe=e7d2bcfcfb) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [1b055dc79d](https://linux-hardware.org/?probe=1b055dc79d) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [0b85968e35](https://linux-hardware.org/?probe=0b85968e35) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| HP            | 2B4B                        | [57273c7b72](https://linux-hardware.org/?probe=57273c7b72) | Jan 07, 2023 |
| Dell          | 04GJJT A00                  | [85142569a6](https://linux-hardware.org/?probe=85142569a6) | Jan 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2024a8808](https://linux-hardware.org/?probe=f2024a8808) | Jan 06, 2023 |
| Acer          | Aspire M3970                | [2ef35b6d4b](https://linux-hardware.org/?probe=2ef35b6d4b) | Jan 05, 2023 |
| MSI           | B250M PRO-VD                | [0abf746107](https://linux-hardware.org/?probe=0abf746107) | Jan 05, 2023 |
| Intel         | HM570                       | [8728d2372a](https://linux-hardware.org/?probe=8728d2372a) | Jan 05, 2023 |
| AZW           | GTR V02                     | [2cf7a814cb](https://linux-hardware.org/?probe=2cf7a814cb) | Jan 05, 2023 |
| Gigabyte      | X570S AERO G                | [04ca884448](https://linux-hardware.org/?probe=04ca884448) | Jan 05, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [98fafd877d](https://linux-hardware.org/?probe=98fafd877d) | Jan 04, 2023 |
| HP            | 3047h                       | [2c75b0b4ee](https://linux-hardware.org/?probe=2c75b0b4ee) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| System76      | Thelio Mira thelio-mira-... | [78367dd37f](https://linux-hardware.org/?probe=78367dd37f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| ASRock        | B550M Steel Legend          | [e8ad216a59](https://linux-hardware.org/?probe=e8ad216a59) | Jan 02, 2023 |
| ASUSTek       | P6T                         | [e648b2523e](https://linux-hardware.org/?probe=e648b2523e) | Jan 02, 2023 |
| Acer          | Aspire XC-603G              | [b2e25a20de](https://linux-hardware.org/?probe=b2e25a20de) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| Win elemen... | M600                        | [5d4320db68](https://linux-hardware.org/?probe=5d4320db68) | Jan 02, 2023 |
| MSI           | PRO B550-VC                 | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Acer          | Aspire XC-603G              | [660548d31c](https://linux-hardware.org/?probe=660548d31c) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | B250M BAZOOKA               | [5b204eade4](https://linux-hardware.org/?probe=5b204eade4) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [ad32666c8c](https://linux-hardware.org/?probe=ad32666c8c) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [17fc3a4abc](https://linux-hardware.org/?probe=17fc3a4abc) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| ASUSTek       | Z87-PLUS                    | [85bfa942e6](https://linux-hardware.org/?probe=85bfa942e6) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [17f72460f6](https://linux-hardware.org/?probe=17f72460f6) | Dec 29, 2022 |
| Intel         | DP55WB AAE64798-206         | [2373b5141b](https://linux-hardware.org/?probe=2373b5141b) | Dec 29, 2022 |
| Acer          | Aspire XC-603G              | [08dc8ac6b7](https://linux-hardware.org/?probe=08dc8ac6b7) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Dell          | 0NNGP2 A00                  | [12638171d9](https://linux-hardware.org/?probe=12638171d9) | Dec 28, 2022 |
| Lenovo        | No DPK                      | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASRock        | Z790M-ITX WiFi              | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 00CV7F A00                  | [49a36278c4](https://linux-hardware.org/?probe=49a36278c4) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| HP            | 2B4B                        | [b07e2ecc23](https://linux-hardware.org/?probe=b07e2ecc23) | Dec 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1522e4a536](https://linux-hardware.org/?probe=1522e4a536) | Dec 28, 2022 |
| Acer          | Aspire XC-603G              | [e8adbb63a4](https://linux-hardware.org/?probe=e8adbb63a4) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ee1658b320](https://linux-hardware.org/?probe=ee1658b320) | Dec 27, 2022 |
| HP            | 876C SMVB                   | [7926807626](https://linux-hardware.org/?probe=7926807626) | Dec 27, 2022 |
| ASUSTek       | Z87-K                       | [9c65749eb1](https://linux-hardware.org/?probe=9c65749eb1) | Dec 27, 2022 |
| MSI           | B450M PRO-M2                | [89d9265559](https://linux-hardware.org/?probe=89d9265559) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [c49123106a](https://linux-hardware.org/?probe=c49123106a) | Dec 24, 2022 |
| Gigabyte      | MJPLNBB-00                  | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| ASUSTek       | P7P55D PRO                  | [7402ac8671](https://linux-hardware.org/?probe=7402ac8671) | Dec 22, 2022 |
| MSI           | B85M-E45                    | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| Dell          | 02GDWG A00                  | [d20f5b0751](https://linux-hardware.org/?probe=d20f5b0751) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| Supermicro    | X9DR3-F                     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
| HP            | 18E7                        | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03dfcb8079](https://linux-hardware.org/?probe=03dfcb8079) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1f6885ef2f](https://linux-hardware.org/?probe=1f6885ef2f) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d179359230](https://linux-hardware.org/?probe=d179359230) | Dec 18, 2022 |
| HP            | 8433 11                     | [4368b19d60](https://linux-hardware.org/?probe=4368b19d60) | Dec 18, 2022 |
| Gigabyte      | B550 VISION D-P             | [163b883ce2](https://linux-hardware.org/?probe=163b883ce2) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | [d7e869aded](https://linux-hardware.org/?probe=d7e869aded) | Dec 17, 2022 |
| Unknown       | Unknown                     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | [f12e6b75b5](https://linux-hardware.org/?probe=f12e6b75b5) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | [b31e9dfa64](https://linux-hardware.org/?probe=b31e9dfa64) | Dec 16, 2022 |
| MSI           | X370 GAMING PLUS            | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| Intel         | X79M-S                      | [f99b1f2b67](https://linux-hardware.org/?probe=f99b1f2b67) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | [9cff930a2e](https://linux-hardware.org/?probe=9cff930a2e) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| ASUSTek       | M51BC                       | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [60848aa48e](https://linux-hardware.org/?probe=60848aa48e) | Dec 16, 2022 |
| ASUSTek       | PRIME X570-PRO              | [af4e397bbe](https://linux-hardware.org/?probe=af4e397bbe) | Dec 16, 2022 |
| System76      | Thelio thelio-r2            | [d2065497b9](https://linux-hardware.org/?probe=d2065497b9) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| MSI           | Z170A PC MATE               | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [cdc6f36d8c](https://linux-hardware.org/?probe=cdc6f36d8c) | Dec 11, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | [8f45bcde64](https://linux-hardware.org/?probe=8f45bcde64) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | [229065f67f](https://linux-hardware.org/?probe=229065f67f) | Dec 11, 2022 |
| MSI           | A55M-E33                    | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | [5cea05fe88](https://linux-hardware.org/?probe=5cea05fe88) | Dec 11, 2022 |
| Apple         | Mac-F221BEC8                | [55a5f34bf0](https://linux-hardware.org/?probe=55a5f34bf0) | Dec 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [05f65af47e](https://linux-hardware.org/?probe=05f65af47e) | Dec 10, 2022 |
| Supermicro    | C7Q67 V1.01                 | [8f571548fd](https://linux-hardware.org/?probe=8f571548fd) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [e8d8a922a2](https://linux-hardware.org/?probe=e8d8a922a2) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| Dell          | 0HY9JP A02                  | [94a6153aeb](https://linux-hardware.org/?probe=94a6153aeb) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | [1b848d1587](https://linux-hardware.org/?probe=1b848d1587) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1280df2c5d](https://linux-hardware.org/?probe=1280df2c5d) | Dec 08, 2022 |
| MSI           | PRO Z790-A WIFI             | [9dfb20d74f](https://linux-hardware.org/?probe=9dfb20d74f) | Dec 08, 2022 |
| ASRock        | Z97 Extreme6                | [f000ea7b78](https://linux-hardware.org/?probe=f000ea7b78) | Dec 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [d2c01d70df](https://linux-hardware.org/?probe=d2c01d70df) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c376825cca](https://linux-hardware.org/?probe=c376825cca) | Dec 07, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3c65af8425](https://linux-hardware.org/?probe=3c65af8425) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d66311f833](https://linux-hardware.org/?probe=d66311f833) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K               | [7e82777792](https://linux-hardware.org/?probe=7e82777792) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| MSI           | 760GM-P23                   | [df9ebcbba6](https://linux-hardware.org/?probe=df9ebcbba6) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69cc6b3ad3](https://linux-hardware.org/?probe=69cc6b3ad3) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| MSI           | B350 TOMAHAWK               | [2607a15d58](https://linux-hardware.org/?probe=2607a15d58) | Dec 03, 2022 |
| ASRock        | Z370 Pro4                   | [76cd787c24](https://linux-hardware.org/?probe=76cd787c24) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [dd1874248c](https://linux-hardware.org/?probe=dd1874248c) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [eaf129dcfe](https://linux-hardware.org/?probe=eaf129dcfe) | Dec 02, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [8e317647dc](https://linux-hardware.org/?probe=8e317647dc) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [953943c231](https://linux-hardware.org/?probe=953943c231) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| System76      | Thelio thelio-r2            | [a7ae37f43e](https://linux-hardware.org/?probe=a7ae37f43e) | Dec 01, 2022 |
| Unknown       | 1.0                         | [c8cfeaf2be](https://linux-hardware.org/?probe=c8cfeaf2be) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| ASRock        | H77M                        | [ffa3496b0d](https://linux-hardware.org/?probe=ffa3496b0d) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Acer          | Nitro N50-610               | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| MSI           | Z97A GAMING 7               | [74341c948b](https://linux-hardware.org/?probe=74341c948b) | Nov 27, 2022 |
| MSI           | B350 GAMING PLUS            | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| Dell          | 06NWYK A01                  | [3afe7122f3](https://linux-hardware.org/?probe=3afe7122f3) | Nov 26, 2022 |
| Gigabyte      | Z77-HD3                     | [e3b7bbc736](https://linux-hardware.org/?probe=e3b7bbc736) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASRock        | Z170 Gaming K6              | [de7addf17b](https://linux-hardware.org/?probe=de7addf17b) | Nov 25, 2022 |
| ASRock        | B550M-ITX/ac                | [c72c157583](https://linux-hardware.org/?probe=c72c157583) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | [bd50429870](https://linux-hardware.org/?probe=bd50429870) | Nov 24, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [880f8b9c45](https://linux-hardware.org/?probe=880f8b9c45) | Nov 23, 2022 |
| HP            | 8309                        | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASRock        | H310CM-HG4                  | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [eed1e72aba](https://linux-hardware.org/?probe=eed1e72aba) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| MSI           | 2AE0                        | [cfb41eba48](https://linux-hardware.org/?probe=cfb41eba48) | Nov 19, 2022 |
| Gigabyte      | B550M DS3H                  | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Gigabyte      | 990FXA-UD3                  | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| HP            | 805D                        | [cb811984e0](https://linux-hardware.org/?probe=cb811984e0) | Nov 17, 2022 |
| Dell          | 0KWVT8 A03                  | [b696d9eae7](https://linux-hardware.org/?probe=b696d9eae7) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [c6f5c91413](https://linux-hardware.org/?probe=c6f5c91413) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [9b870d8287](https://linux-hardware.org/?probe=9b870d8287) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [2f6204153a](https://linux-hardware.org/?probe=2f6204153a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| Dell          | 0KWVT8 A03                  | [965a35d0b0](https://linux-hardware.org/?probe=965a35d0b0) | Nov 15, 2022 |
| HP            | 1998                        | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| System76      | Thelio thelio-r2            | [1ce532916f](https://linux-hardware.org/?probe=1ce532916f) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| System76      | Thelio thelio-r2            | [0c282237ab](https://linux-hardware.org/?probe=0c282237ab) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [fa94f8afc5](https://linux-hardware.org/?probe=fa94f8afc5) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Intel         | P61A-D3                     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bad7b9a014](https://linux-hardware.org/?probe=bad7b9a014) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [4abe56ea2e](https://linux-hardware.org/?probe=4abe56ea2e) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [5b939b71c7](https://linux-hardware.org/?probe=5b939b71c7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | X399 Taichi                 | [99f51ff157](https://linux-hardware.org/?probe=99f51ff157) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| Colorful T... | A320M-K PRO YV14            | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [42edcc018a](https://linux-hardware.org/?probe=42edcc018a) | Nov 03, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| ASUSTek       | H110M-D                     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| MSI           | B85-G43                     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | 970A-G46                    | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| ASUSTek       | A88X-PLUS                   | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| HP            | 339A                        | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| ASRock        | X570 Taichi                 | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Pegatron      | 2AD5                        | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3462676a1d](https://linux-hardware.org/?probe=3462676a1d) | Oct 10, 2022 |
| Dell          | 0GM819                      | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Dell          | 0J3C2F A01                  | [d1001275c6](https://linux-hardware.org/?probe=d1001275c6) | Oct 09, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [324f177fa7](https://linux-hardware.org/?probe=324f177fa7) | Oct 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [8ad48ccaec](https://linux-hardware.org/?probe=8ad48ccaec) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| ASUSTek       | PRIME X570-PRO              | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| ASRock        | B450M/ac                    | [af66fef71a](https://linux-hardware.org/?probe=af66fef71a) | Oct 06, 2022 |
| HP            | 3398                        | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| Intel         | DQ35JO AAD82085-801         | [4056c37c50](https://linux-hardware.org/?probe=4056c37c50) | Oct 04, 2022 |
| ASUSTek       | Maximus VII HERO            | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| Dell          | 0KWVT8 A03                  | [ae706e478d](https://linux-hardware.org/?probe=ae706e478d) | Oct 02, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [692b59019a](https://linux-hardware.org/?probe=692b59019a) | Oct 01, 2022 |
| ASUSTek       | GRYPHON Z87                 | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [7a2f334861](https://linux-hardware.org/?probe=7a2f334861) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | 0NDYHG A01                  | [7a5df20f28](https://linux-hardware.org/?probe=7a5df20f28) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| HP            | 83E9                        | [c24faa3c5b](https://linux-hardware.org/?probe=c24faa3c5b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [fbc760a09c](https://linux-hardware.org/?probe=fbc760a09c) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASRock        | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| MSI           | Z97-G55 SLI                 | [dc60d66502](https://linux-hardware.org/?probe=dc60d66502) | Sep 24, 2022 |
| System76      | Thelio Mira                 | [2e9601d2a2](https://linux-hardware.org/?probe=2e9601d2a2) | Sep 24, 2022 |
| ASRock        | X570M Pro4                  | [9e8207dfb7](https://linux-hardware.org/?probe=9e8207dfb7) | Sep 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | Z97-G55 SLI                 | [27b47d5592](https://linux-hardware.org/?probe=27b47d5592) | Sep 23, 2022 |
| Dell          | 0HHV7N A00                  | [cda6d76f04](https://linux-hardware.org/?probe=cda6d76f04) | Sep 22, 2022 |
| ASRock        | 4X4-V1000                   | [e73062fe01](https://linux-hardware.org/?probe=e73062fe01) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| HP            | 1589                        | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| ASRock        | AB350 Pro4                  | [61a4ab7c20](https://linux-hardware.org/?probe=61a4ab7c20) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a0d6f208fb](https://linux-hardware.org/?probe=a0d6f208fb) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [83b0a59729](https://linux-hardware.org/?probe=83b0a59729) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7ddbf9f7](https://linux-hardware.org/?probe=bd7ddbf9f7) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| Minix         | NEO Z83-4 V1.1              | [545552c43e](https://linux-hardware.org/?probe=545552c43e) | Sep 16, 2022 |
| NZXT          | N7 B550                     | [7deb3849db](https://linux-hardware.org/?probe=7deb3849db) | Sep 16, 2022 |
| ASRock        | Z97 Extreme6                | [2c90f58ae4](https://linux-hardware.org/?probe=2c90f58ae4) | Sep 16, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [89fb49d843](https://linux-hardware.org/?probe=89fb49d843) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [a385e1220b](https://linux-hardware.org/?probe=a385e1220b) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| ECS           | Nettle3                     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| System76      | Thelio thelio-r2            | [2f6745bad5](https://linux-hardware.org/?probe=2f6745bad5) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ce4fc6576c](https://linux-hardware.org/?probe=ce4fc6576c) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [29da7835e4](https://linux-hardware.org/?probe=29da7835e4) | Sep 10, 2022 |
| ASUSTek       | M4N72-E                     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| Unknown       | Unknown                     | [87f754ac29](https://linux-hardware.org/?probe=87f754ac29) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [1be1b9b040](https://linux-hardware.org/?probe=1be1b9b040) | Sep 09, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Dell          | 0TTDMJ A00                  | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| ASRock        | B450M/ac                    | [efb78c5d25](https://linux-hardware.org/?probe=efb78c5d25) | Sep 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [483a414289](https://linux-hardware.org/?probe=483a414289) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Acer          | 1.0                         | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| Gigabyte      | Z77-D3H                     | [47d065ed5c](https://linux-hardware.org/?probe=47d065ed5c) | Sep 06, 2022 |
| Dell          | 088DT1 A01                  | [c17c4d475f](https://linux-hardware.org/?probe=c17c4d475f) | Sep 05, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8b964572d7](https://linux-hardware.org/?probe=8b964572d7) | Sep 04, 2022 |
| Alienware     | 0NWN7M A00                  | [e254b049c3](https://linux-hardware.org/?probe=e254b049c3) | Sep 04, 2022 |
| Dell          | 0KWVT8 A03                  | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [81eb6e9f4e](https://linux-hardware.org/?probe=81eb6e9f4e) | Sep 03, 2022 |
| ASUSTek       | M5A97                       | [de7dc826b0](https://linux-hardware.org/?probe=de7dc826b0) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7b914b0347](https://linux-hardware.org/?probe=7b914b0347) | Sep 03, 2022 |
| HP            | 1497                        | [a8566c45a9](https://linux-hardware.org/?probe=a8566c45a9) | Sep 03, 2022 |
| MSI           | MEG Z390 ACE                | [1f702cfc06](https://linux-hardware.org/?probe=1f702cfc06) | Sep 03, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [39cb364d6f](https://linux-hardware.org/?probe=39cb364d6f) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS            | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| HP            | 87D6 SMVB                   | [8efd1ba4e0](https://linux-hardware.org/?probe=8efd1ba4e0) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | 1497                        | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| ASRock        | B560 Steel Legend           | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASRock        | X570 Creator                | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| Dell          | 0KWVT8 A03                  | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| System76      | Thelio thelio-r2            | [6eb968883d](https://linux-hardware.org/?probe=6eb968883d) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
| MSI           | FM2-A55M-E33                | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| MSI           | Z170A PC MATE               | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [93c5d7b0f9](https://linux-hardware.org/?probe=93c5d7b0f9) | Aug 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7af77fd850](https://linux-hardware.org/?probe=7af77fd850) | Aug 18, 2022 |
| Gigabyte      | X299 AORUS MASTER           | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8a1a495053](https://linux-hardware.org/?probe=8a1a495053) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [169469e8b6](https://linux-hardware.org/?probe=169469e8b6) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [8441adcca9](https://linux-hardware.org/?probe=8441adcca9) | Aug 17, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5c2c3d81ef](https://linux-hardware.org/?probe=5c2c3d81ef) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0a5775d3a8](https://linux-hardware.org/?probe=0a5775d3a8) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| MSI           | B360-A PRO                  | [a5505919b5](https://linux-hardware.org/?probe=a5505919b5) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5a5538ce52](https://linux-hardware.org/?probe=5a5538ce52) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| MSI           | Z87-G45 GAMING              | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| ASRock        | A320M                       | [1e0a574078](https://linux-hardware.org/?probe=1e0a574078) | Aug 12, 2022 |
| ASUSTek       | H97-PLUS                    | [4ca1b1050d](https://linux-hardware.org/?probe=4ca1b1050d) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| HP            | 3397                        | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [80bb75a792](https://linux-hardware.org/?probe=80bb75a792) | Aug 07, 2022 |
| ASUSTek       | Z87-K                       | [d1954b42ae](https://linux-hardware.org/?probe=d1954b42ae) | Aug 06, 2022 |
| HP            | 1998                        | [5164a156e2](https://linux-hardware.org/?probe=5164a156e2) | Aug 05, 2022 |
| Intel         | D955XBK AAC96732-501        | [d6463d7629](https://linux-hardware.org/?probe=d6463d7629) | Aug 05, 2022 |
| MSI           | 970A-G43                    | [a77e1878ae](https://linux-hardware.org/?probe=a77e1878ae) | Aug 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [585bf3495e](https://linux-hardware.org/?probe=585bf3495e) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2d017b110e](https://linux-hardware.org/?probe=2d017b110e) | Aug 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | [14447cf212](https://linux-hardware.org/?probe=14447cf212) | Aug 04, 2022 |
| ASUSTek       | P8Z77-V LK                  | [9878a3365c](https://linux-hardware.org/?probe=9878a3365c) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| Gigabyte      | A520I AC                    | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | 0TP412                      | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| HP            | 2215                        | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e3dc0a4c49](https://linux-hardware.org/?probe=e3dc0a4c49) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [36e0686495](https://linux-hardware.org/?probe=36e0686495) | Jul 28, 2022 |
| MSI           | X370 GAMING PLUS            | [a39ccd24ff](https://linux-hardware.org/?probe=a39ccd24ff) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [71f25aa9f5](https://linux-hardware.org/?probe=71f25aa9f5) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| MSI           | Z490-A PRO                  | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| HP            | 8433 11                     | [a66fb85e77](https://linux-hardware.org/?probe=a66fb85e77) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| Positivo      | POS-PIQ77CL                 | [ce9a0fdbbc](https://linux-hardware.org/?probe=ce9a0fdbbc) | Jul 20, 2022 |
| MSI           | Z590-A PRO                  | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| Lenovo        | MAHOBAY                     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Gigabyte      | B75M-D3H                    | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [618141855c](https://linux-hardware.org/?probe=618141855c) | Jul 11, 2022 |
| MSI           | P67A-C43                    | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| ASUSTek       | P5Q-PRO                     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| Positivo      | POS-PIQ77CL                 | [1a40c954fc](https://linux-hardware.org/?probe=1a40c954fc) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| MSI           | B360-A PRO                  | [4534101418](https://linux-hardware.org/?probe=4534101418) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [82fe9f31c7](https://linux-hardware.org/?probe=82fe9f31c7) | Jul 04, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HP            | 18E7                        | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| HP            | 18E7                        | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | 0HHV7N A00                  | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| ASUSTek       | B85M-E/BR                   | [adfbbd03b6](https://linux-hardware.org/?probe=adfbbd03b6) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [3bceb0a396](https://linux-hardware.org/?probe=3bceb0a396) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| ASRock        | N68-S                       | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [c5a5527f1d](https://linux-hardware.org/?probe=c5a5527f1d) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASRock        | B450 Gaming K4              | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| HP            | 158B                        | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| MSI           | B550-A PRO                  | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Unknown       | Unknown                     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [e92127f694](https://linux-hardware.org/?probe=e92127f694) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| PCWare        | IPX4105G Pro                | [72ac2cedad](https://linux-hardware.org/?probe=72ac2cedad) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| PCWare        | IPX4105G Pro                | [ffccee6734](https://linux-hardware.org/?probe=ffccee6734) | Jun 07, 2022 |
| ASRock        | B365M Pro4                  | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Dell          | 0Y2MRG A00                  | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| Dell          | 0R790T A00                  | [f9388b2163](https://linux-hardware.org/?probe=f9388b2163) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [57a20bde9f](https://linux-hardware.org/?probe=57a20bde9f) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [084dab5bd4](https://linux-hardware.org/?probe=084dab5bd4) | May 26, 2022 |
| ASUSTek       | P5KPL-SE                    | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| ASRock        | H670M-ITX/ax                | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | MAHOBAY                     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [5ebbcedcc1](https://linux-hardware.org/?probe=5ebbcedcc1) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| ASUSTek       | H110M-R                     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | H110M-A/DP                  | [9e2c754ed6](https://linux-hardware.org/?probe=9e2c754ed6) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [3f9a21ddc1](https://linux-hardware.org/?probe=3f9a21ddc1) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Supermicro    | X8SIL                       | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | GA15DH                      | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| ASUSTek       | Z87-K                       | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| ASUSTek       | H170M-PLUS                  | [c1f5cb662f](https://linux-hardware.org/?probe=c1f5cb662f) | May 15, 2022 |
| ASUSTek       | Z87-K                       | [bb296e5f39](https://linux-hardware.org/?probe=bb296e5f39) | May 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| MSI           | CSM-B85M-E45                | [85abf64cf5](https://linux-hardware.org/?probe=85abf64cf5) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASRock        | B450M Pro4-F                | [423fbd3a54](https://linux-hardware.org/?probe=423fbd3a54) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Gigabyte      | B75M-D3H                    | [cfae917826](https://linux-hardware.org/?probe=cfae917826) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| Acer          | RS780HVF                    | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [17e7dcafe2](https://linux-hardware.org/?probe=17e7dcafe2) | May 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 20.04 | 859      | 24.97%  |
| Pop!_OS 22.04 | 747      | 21.72%  |
| Pop!_OS 21.04 | 717      | 20.84%  |
| Pop!_OS 20.10 | 671      | 19.51%  |
| Pop!_OS 21.10 | 420      | 12.21%  |
| Pop!_OS 19.10 | 15       | 0.44%   |
| Pop!_OS 19.04 | 6        | 0.17%   |
| Pop!_OS 18.04 | 4        | 0.12%   |
| Pop!_OS 18.10 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 3232     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-7620-generic      | 339      | 9.14%   |
| 5.8.0-7630-generic       | 315      | 8.49%   |
| 5.4.0-7634-generic       | 281      | 7.57%   |
| 5.8.0-7642-generic       | 203      | 5.47%   |
| 5.13.0-7614-generic      | 203      | 5.47%   |
| 5.4.0-7642-generic       | 187      | 5.04%   |
| 5.11.0-7614-generic      | 180      | 4.85%   |
| 5.17.5-76051705-generic  | 177      | 4.77%   |
| 5.13.0-7620-generic      | 171      | 4.61%   |
| 6.0.12-76060006-generic  | 160      | 4.31%   |
| 5.19.0-76051900-generic  | 142      | 3.83%   |
| 5.16.11-76051611-generic | 111      | 2.99%   |
| 5.15.15-76051515-generic | 109      | 2.94%   |
| 6.0.6-76060006-generic   | 101      | 2.72%   |
| 5.15.5-76051505-generic  | 92       | 2.48%   |
| 5.11.0-7612-generic      | 87       | 2.34%   |
| 5.8.0-7625-generic       | 77       | 2.07%   |
| 5.18.10-76051810-generic | 74       | 1.99%   |
| 5.11.0-7633-generic      | 71       | 1.91%   |
| 5.17.15-76051715-generic | 68       | 1.83%   |
| 5.16.19-76051619-generic | 65       | 1.75%   |
| 5.15.8-76051508-generic  | 63       | 1.7%    |
| 5.16.15-76051615-generic | 56       | 1.51%   |
| 5.15.11-76051511-generic | 47       | 1.27%   |
| 5.4.0-7626-generic       | 43       | 1.16%   |
| 5.15.23-76051523-generic | 29       | 0.78%   |
| 6.0.2-76060002-generic   | 24       | 0.65%   |
| 5.4.0-7625-generic       | 24       | 0.65%   |
| 5.4.0-7629-generic       | 21       | 0.57%   |
| 5.19.16-76051916-generic | 18       | 0.49%   |
| 6.0.3-76060003-generic   | 14       | 0.38%   |
| 6.1.11-76060111-generic  | 9        | 0.24%   |
| 5.3.0-7629-generic       | 5        | 0.13%   |
| 5.3.0-7625-generic       | 5        | 0.13%   |
| 5.8.5-xanmod1            | 4        | 0.11%   |
| 5.8.5-050805-generic     | 4        | 0.11%   |
| 5.8.12-xanmod1           | 4        | 0.11%   |
| 5.7.8-050708-generic     | 3        | 0.08%   |
| 5.4.0-7624-generic       | 3        | 0.08%   |
| 5.3.0-7648-generic       | 3        | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 649      | 17.92%  |
| 5.8.0   | 567      | 15.66%  |
| 5.4.0   | 537      | 14.83%  |
| 5.13.0  | 371      | 10.25%  |
| 5.17.5  | 177      | 4.89%   |
| 6.0.12  | 161      | 4.45%   |
| 5.19.0  | 142      | 3.92%   |
| 5.16.11 | 111      | 3.07%   |
| 5.15.15 | 110      | 3.04%   |
| 6.0.6   | 102      | 2.82%   |
| 5.15.5  | 92       | 2.54%   |
| 5.18.10 | 74       | 2.04%   |
| 5.17.15 | 68       | 1.88%   |
| 5.16.19 | 65       | 1.8%    |
| 5.15.8  | 63       | 1.74%   |
| 5.16.15 | 56       | 1.55%   |
| 5.15.11 | 47       | 1.3%    |
| 5.15.23 | 29       | 0.8%    |
| 6.0.2   | 25       | 0.69%   |
| 5.19.16 | 18       | 0.5%    |
| 5.3.0   | 17       | 0.47%   |
| 6.0.3   | 14       | 0.39%   |
| 6.1.11  | 9        | 0.25%   |
| 5.8.5   | 8        | 0.22%   |
| 5.0.0   | 6        | 0.17%   |
| 5.8.12  | 5        | 0.14%   |
| 6.1.0   | 3        | 0.08%   |
| 5.7.8   | 3        | 0.08%   |
| 5.7.0   | 3        | 0.08%   |
| 5.6.16  | 3        | 0.08%   |
| 5.15.0  | 3        | 0.08%   |
| 5.9.1   | 2        | 0.06%   |
| 5.8.6   | 2        | 0.06%   |
| 5.8.18  | 2        | 0.06%   |
| 5.7.16  | 2        | 0.06%   |
| 5.7.12  | 2        | 0.06%   |
| 5.16.0  | 2        | 0.06%   |
| 5.15.7  | 2        | 0.06%   |
| 5.15.22 | 2        | 0.06%   |
| 5.13.12 | 2        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 651      | 18.17%  |
| 5.8     | 589      | 16.44%  |
| 5.4     | 539      | 15.04%  |
| 5.13    | 376      | 10.49%  |
| 5.15    | 343      | 9.57%   |
| 6.0     | 299      | 8.34%   |
| 5.17    | 243      | 6.78%   |
| 5.16    | 223      | 6.22%   |
| 5.19    | 160      | 4.47%   |
| 5.18    | 76       | 2.12%   |
| 5.3     | 17       | 0.47%   |
| 6.1     | 15       | 0.42%   |
| 5.7     | 14       | 0.39%   |
| 5.6     | 8        | 0.22%   |
| 5.10    | 8        | 0.22%   |
| 5.0     | 6        | 0.17%   |
| 5.9     | 5        | 0.14%   |
| 5.14    | 5        | 0.14%   |
| 5.12    | 4        | 0.11%   |
| 4.18    | 1        | 0.03%   |
| 4.15    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3232     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3125     | 96.12%  |
| KDE             | 33       | 1.02%   |
| KDE5            | 29       | 0.89%   |
| X-Cinnamon      | 16       | 0.49%   |
| Unknown         | 14       | 0.43%   |
| MATE            | 9        | 0.28%   |
| XFCE            | 7        | 0.22%   |
| Cinnamon        | 5        | 0.15%   |
| GNOME Flashback | 4        | 0.12%   |
| LXQt            | 3        | 0.09%   |
| i3              | 2        | 0.06%   |
| Budgie          | 2        | 0.06%   |
| Unity           | 1        | 0.03%   |
| Pantheon        | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3182     | 98.12%  |
| Wayland | 50       | 1.54%   |
| Tty     | 6        | 0.19%   |
| Unknown | 5        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2788     | 85.68%  |
| GDM     | 342      | 10.51%  |
| GDM3    | 112      | 3.44%   |
| SDDM    | 7        | 0.22%   |
| TDM     | 3        | 0.09%   |
| LightDM | 2        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1836     | 56.37%  |
| en_GB   | 251      | 7.71%   |
| pt_BR   | 240      | 7.37%   |
| de_DE   | 168      | 5.16%   |
| C       | 113      | 3.47%   |
| en_AU   | 99       | 3.04%   |
| en_CA   | 96       | 2.95%   |
| fr_FR   | 65       | 2%      |
| it_IT   | 41       | 1.26%   |
| ru_RU   | 38       | 1.17%   |
| es_ES   | 37       | 1.14%   |
| pl_PL   | 31       | 0.95%   |
| nl_NL   | 27       | 0.83%   |
| sv_SE   | 21       | 0.64%   |
| Unknown | 18       | 0.55%   |
| fi_FI   | 14       | 0.43%   |
| pt_PT   | 12       | 0.37%   |
| fr_CA   | 8        | 0.25%   |
| es_AR   | 8        | 0.25%   |
| zh_TW   | 7        | 0.21%   |
| nl_BE   | 7        | 0.21%   |
| es_CL   | 7        | 0.21%   |
| en_DK   | 7        | 0.21%   |
| sk_SK   | 6        | 0.18%   |
| ja_JP   | 6        | 0.18%   |
| en_ZA   | 6        | 0.18%   |
| en_NZ   | 6        | 0.18%   |
| en_IN   | 6        | 0.18%   |
| da_DK   | 6        | 0.18%   |
| es_MX   | 5        | 0.15%   |
| cs_CZ   | 5        | 0.15%   |
| tr_TR   | 4        | 0.12%   |
| nb_NO   | 4        | 0.12%   |
| hu_HU   | 4        | 0.12%   |
| hr_HR   | 4        | 0.12%   |
| fr_CH   | 4        | 0.12%   |
| zh_CN   | 3        | 0.09%   |
| uk_UA   | 3        | 0.09%   |
| ro_RO   | 3        | 0.09%   |
| en_IL   | 3        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2644     | 80.91%  |
| EFI  | 624      | 19.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3112     | 95.96%  |
| Overlay | 59       | 1.82%   |
| Btrfs   | 54       | 1.67%   |
| Xfs     | 8        | 0.25%   |
| Unknown | 6        | 0.19%   |
| Zfs     | 4        | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2779     | 85.46%  |
| GPT     | 406      | 12.48%  |
| MBR     | 67       | 2.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3143     | 96.77%  |
| Yes       | 105      | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2967     | 91.32%  |
| Yes       | 282      | 8.68%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 915      | 28.31%  |
| Gigabyte Technology | 631      | 19.52%  |
| MSI                 | 480      | 14.85%  |
| ASRock              | 333      | 10.3%   |
| Dell                | 247      | 7.64%   |
| Hewlett-Packard     | 163      | 5.04%   |
| Lenovo              | 81       | 2.51%   |
| Intel               | 60       | 1.86%   |
| System76            | 31       | 0.96%   |
| Acer                | 28       | 0.87%   |
| Pegatron            | 24       | 0.74%   |
| Unknown             | 20       | 0.62%   |
| Alienware           | 18       | 0.56%   |
| Biostar             | 17       | 0.53%   |
| Foxconn             | 16       | 0.5%    |
| ECS                 | 15       | 0.46%   |
| Fujitsu             | 13       | 0.4%    |
| Apple               | 11       | 0.34%   |
| Medion              | 10       | 0.31%   |
| Huanan              | 10       | 0.31%   |
| Supermicro          | 9        | 0.28%   |
| Positivo            | 9        | 0.28%   |
| PCWare              | 8        | 0.25%   |
| Gateway             | 7        | 0.22%   |
| Minix               | 5        | 0.15%   |
| MACHINIST           | 5        | 0.15%   |
| EVGA                | 5        | 0.15%   |
| BESSTAR Tech        | 5        | 0.15%   |
| OEM                 | 3        | 0.09%   |
| MAXSUN              | 3        | 0.09%   |
| TYAN Computer       | 2        | 0.06%   |
| T-bao               | 2        | 0.06%   |
| Shuttle             | 2        | 0.06%   |
| NZXT                | 2        | 0.06%   |
| Megaware            | 2        | 0.06%   |
| Login Informatica   | 2        | 0.06%   |
| Google              | 2        | 0.06%   |
| Fujitsu Siemens     | 2        | 0.06%   |
| eMachines           | 2        | 0.06%   |
| Colorful Technology | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 83       | 2.57%   |
| ASUS TUF Gaming X570-PLUS      | 39       | 1.21%   |
| Gigabyte B450M DS3H            | 34       | 1.05%   |
| MSI MS-7C02                    | 30       | 0.93%   |
| ASUS ROG STRIX B450-F GAMING   | 27       | 0.84%   |
| MSI MS-7C37                    | 26       | 0.8%    |
| MSI MS-7B86                    | 26       | 0.8%    |
| ASUS ROG STRIX B550-F GAMING   | 23       | 0.71%   |
| ASUS PRIME B450M-A             | 22       | 0.68%   |
| Dell OptiPlex 9020             | 21       | 0.65%   |
| Unknown                        | 21       | 0.65%   |
| System76 Thelio                | 20       | 0.62%   |
| Gigabyte X570 AORUS ELITE      | 20       | 0.62%   |
| ASRock B450M Pro4              | 16       | 0.5%    |
| Dell OptiPlex 7010             | 15       | 0.46%   |
| ASRock B450M Steel Legend      | 15       | 0.46%   |
| Gigabyte A320M-S2H             | 14       | 0.43%   |
| MSI MS-7C91                    | 13       | 0.4%    |
| Gigabyte B450 I AORUS PRO WIFI | 13       | 0.4%    |
| Gigabyte X570 AORUS MASTER     | 12       | 0.37%   |
| Gigabyte B450 AORUS PRO WIFI   | 12       | 0.37%   |
| Gigabyte B450 AORUS M          | 12       | 0.37%   |
| ASUS ROG STRIX B550-I GAMING   | 12       | 0.37%   |
| ASUS PRIME B450M-GAMING/BR     | 12       | 0.37%   |
| MSI MS-7B89                    | 11       | 0.34%   |
| MSI MS-7B79                    | 11       | 0.34%   |
| Gigabyte B75M-D3H              | 11       | 0.34%   |
| Dell OptiPlex 3010             | 11       | 0.34%   |
| ASUS TUF Gaming X570-PRO       | 11       | 0.34%   |
| ASUS TUF Gaming B550-PLUS      | 11       | 0.34%   |
| ASUS ROG STRIX X570-E GAMING   | 11       | 0.34%   |
| MSI MS-7C84                    | 10       | 0.31%   |
| MSI MS-7817                    | 10       | 0.31%   |
| HP Compaq 8200 Elite SFF PC    | 10       | 0.31%   |
| Gigabyte B550I AORUS PRO AX    | 10       | 0.31%   |
| Dell OptiPlex 790              | 10       | 0.31%   |
| ASUS TUF Gaming B550M-PLUS     | 10       | 0.31%   |
| ASUS ROG STRIX B350-F GAMING   | 10       | 0.31%   |
| System76 Thelio Major          | 9        | 0.28%   |
| MSI MS-7C56                    | 9        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 205      | 6.34%   |
| ASUS PRIME             | 171      | 5.29%   |
| Dell OptiPlex          | 135      | 4.18%   |
| ASUS TUF               | 115      | 3.56%   |
| ASUS All               | 83       | 2.57%   |
| Gigabyte X570          | 69       | 2.13%   |
| HP Compaq              | 53       | 1.64%   |
| Gigabyte B450          | 50       | 1.55%   |
| Gigabyte B450M         | 47       | 1.45%   |
| Lenovo ThinkCentre     | 46       | 1.42%   |
| Dell Precision         | 44       | 1.36%   |
| ASRock B450M           | 37       | 1.14%   |
| ASRock X570            | 32       | 0.99%   |
| System76 Thelio        | 31       | 0.96%   |
| MSI MS-7C02            | 30       | 0.93%   |
| Gigabyte B550          | 27       | 0.84%   |
| Dell Inspiron          | 27       | 0.84%   |
| MSI MS-7C37            | 26       | 0.8%    |
| MSI MS-7B86            | 26       | 0.8%    |
| ASRock B450            | 22       | 0.68%   |
| ASUS SABERTOOTH        | 21       | 0.65%   |
| Unknown                | 21       | 0.65%   |
| HP EliteDesk           | 19       | 0.59%   |
| Dell XPS               | 18       | 0.56%   |
| Acer Aspire            | 18       | 0.56%   |
| Gigabyte A320M-S2H     | 17       | 0.53%   |
| Gigabyte Z390          | 16       | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 16       | 0.5%    |
| ASUS M5A97             | 16       | 0.5%    |
| ASUS P8Z77-V           | 15       | 0.46%   |
| ASUS M5A78L-M          | 15       | 0.46%   |
| MSI MS-7C91            | 13       | 0.4%    |
| ASUS CROSSHAIR         | 13       | 0.4%    |
| Lenovo IdeaCentre      | 12       | 0.37%   |
| HP ProDesk             | 12       | 0.37%   |
| Gigabyte B550M         | 12       | 0.37%   |
| ASUS Maximus           | 12       | 0.37%   |
| Alienware Aurora       | 12       | 0.37%   |
| MSI MS-7B89            | 11       | 0.34%   |
| MSI MS-7B79            | 11       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 518      | 16.03%  |
| 2019    | 392      | 12.13%  |
| 2020    | 374      | 11.57%  |
| 2012    | 268      | 8.29%   |
| 2017    | 241      | 7.46%   |
| 2013    | 225      | 6.96%   |
| 2011    | 198      | 6.13%   |
| 2014    | 186      | 5.75%   |
| 2021    | 161      | 4.98%   |
| 2015    | 136      | 4.21%   |
| 2016    | 128      | 3.96%   |
| 2010    | 122      | 3.77%   |
| 2009    | 111      | 3.43%   |
| 2008    | 63       | 1.95%   |
| 2007    | 52       | 1.61%   |
| 2022    | 43       | 1.33%   |
| 2006    | 12       | 0.37%   |
| 2023    | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3232     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3230     | 99.91%  |
| Enabled  | 3        | 0.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3230     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1077     | 32.67%  |
| 32.01-64.0      | 690      | 20.93%  |
| 8.01-16.0       | 609      | 18.47%  |
| 4.01-8.0        | 317      | 9.61%   |
| 3.01-4.0        | 252      | 7.64%   |
| 64.01-256.0     | 200      | 6.07%   |
| 24.01-32.0      | 103      | 3.12%   |
| 1.01-2.0        | 29       | 0.88%   |
| 2.01-3.0        | 11       | 0.33%   |
| More than 256.0 | 8        | 0.24%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 989      | 27.84%  |
| 1.01-2.0    | 911      | 25.65%  |
| 4.01-8.0    | 766      | 21.57%  |
| 3.01-4.0    | 643      | 18.1%   |
| 8.01-16.0   | 176      | 4.95%   |
| 16.01-24.0  | 33       | 0.93%   |
| 32.01-64.0  | 12       | 0.34%   |
| 24.01-32.0  | 12       | 0.34%   |
| 0.51-1.0    | 7        | 0.2%    |
| 64.01-256.0 | 3        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1092     | 32.71%  |
| 2      | 1004     | 30.08%  |
| 3      | 599      | 17.94%  |
| 4      | 353      | 10.58%  |
| 5      | 152      | 4.55%   |
| 6      | 64       | 1.92%   |
| 7      | 25       | 0.75%   |
| 0      | 18       | 0.54%   |
| 8      | 8        | 0.24%   |
| 11     | 7        | 0.21%   |
| 9      | 7        | 0.21%   |
| 10     | 3        | 0.09%   |
| 23     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 19     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |
| 12     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2176     | 66.71%  |
| Yes       | 1086     | 33.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3190     | 98.67%  |
| No        | 43       | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1728     | 52.86%  |
| No        | 1541     | 47.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1978     | 60.45%  |
| Yes       | 1294     | 39.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1118     | 34.43%  |
| Brazil       | 296      | 9.12%   |
| Germany      | 230      | 7.08%   |
| Canada       | 180      | 5.54%   |
| UK           | 179      | 5.51%   |
| Australia    | 120      | 3.7%    |
| Netherlands  | 78       | 2.4%    |
| Italy        | 73       | 2.25%   |
| France       | 69       | 2.13%   |
| Sweden       | 58       | 1.79%   |
| Poland       | 55       | 1.69%   |
| Russia       | 45       | 1.39%   |
| South Africa | 37       | 1.14%   |
| Spain        | 36       | 1.11%   |
| Finland      | 35       | 1.08%   |
| India        | 34       | 1.05%   |
| Switzerland  | 29       | 0.89%   |
| Romania      | 28       | 0.86%   |
| Norway       | 27       | 0.83%   |
| Austria      | 25       | 0.77%   |
| New Zealand  | 24       | 0.74%   |
| Greece       | 24       | 0.74%   |
| Portugal     | 23       | 0.71%   |
| Mexico       | 23       | 0.71%   |
| Belgium      | 22       | 0.68%   |
| Denmark      | 21       | 0.65%   |
| Argentina    | 21       | 0.65%   |
| Philippines  | 20       | 0.62%   |
| Czechia      | 17       | 0.52%   |
| Bulgaria     | 15       | 0.46%   |
| Hungary      | 14       | 0.43%   |
| Chile        | 14       | 0.43%   |
| Japan        | 13       | 0.4%    |
| Ireland      | 13       | 0.4%    |
| Slovakia     | 12       | 0.37%   |
| Serbia       | 12       | 0.37%   |
| Ukraine      | 11       | 0.34%   |
| Malaysia     | 11       | 0.34%   |
| Lithuania    | 10       | 0.31%   |
| Israel       | 10       | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 38       | 1.13%   |
| Sydney         | 33       | 0.98%   |
| Berlin         | 26       | 0.77%   |
| Melbourne      | 24       | 0.71%   |
| Rio de Janeiro | 19       | 0.57%   |
| Miami          | 19       | 0.57%   |
| Brisbane       | 19       | 0.57%   |
| Helsinki       | 18       | 0.54%   |
| Vienna         | 16       | 0.48%   |
| Browning       | 15       | 0.45%   |
| Warsaw         | 14       | 0.42%   |
| Seattle        | 14       | 0.42%   |
| Denver         | 14       | 0.42%   |
| Milan          | 13       | 0.39%   |
| Chicago        | 13       | 0.39%   |
| Phoenix        | 12       | 0.36%   |
| Perth          | 12       | 0.36%   |
| Moscow         | 12       | 0.36%   |
| London         | 12       | 0.36%   |
| Dallas         | 12       | 0.36%   |
| Auckland       | 12       | 0.36%   |
| St Louis       | 11       | 0.33%   |
| Edmonton       | 11       | 0.33%   |
| Calgary        | 11       | 0.33%   |
| Athens         | 11       | 0.33%   |
| Amsterdam      | 11       | 0.33%   |
| Adelaide       | 11       | 0.33%   |
| Washington     | 10       | 0.3%    |
| Toronto        | 10       | 0.3%    |
| Sofia          | 10       | 0.3%    |
| Montreal       | 10       | 0.3%    |
| Cape Town      | 10       | 0.3%    |
| Paris          | 9        | 0.27%   |
| Johannesburg   | 9        | 0.27%   |
| Jacksonville   | 9        | 0.27%   |
| Hamburg        | 9        | 0.27%   |
| Budapest       | 9        | 0.27%   |
| Bucharest      | 9        | 0.27%   |
| Atlanta        | 9        | 0.27%   |
| Vancouver      | 8        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 1118     | 1748   | 17.66%  |
| Samsung Electronics       | 1101     | 1863   | 17.39%  |
| WDC                       | 1074     | 1634   | 16.97%  |
| SanDisk                   | 395      | 522    | 6.24%   |
| Kingston                  | 386      | 509    | 6.1%    |
| Crucial                   | 293      | 413    | 4.63%   |
| Toshiba                   | 273      | 347    | 4.31%   |
| Hitachi                   | 156      | 201    | 2.46%   |
| Phison                    | 148      | 221    | 2.34%   |
| Intel                     | 133      | 187    | 2.1%    |
| A-DATA Technology         | 96       | 123    | 1.52%   |
| PNY                       | 76       | 100    | 1.2%    |
| Silicon Motion            | 74       | 104    | 1.17%   |
| Micron/Crucial Technology | 71       | 93     | 1.12%   |
| China                     | 67       | 98     | 1.06%   |
| Unknown                   | 54       | 84     | 0.85%   |
| HGST                      | 45       | 61     | 0.71%   |
| SK hynix                  | 44       | 63     | 0.7%    |
| OCZ                       | 42       | 58     | 0.66%   |
| XPG                       | 38       | 51     | 0.6%    |
| Micron Technology         | 33       | 48     | 0.52%   |
| SPCC                      | 32       | 42     | 0.51%   |
| Maxtor                    | 31       | 32     | 0.49%   |
| Realtek Semiconductor     | 30       | 35     | 0.47%   |
| Corsair                   | 30       | 41     | 0.47%   |
| Phison Electronics        | 29       | 40     | 0.46%   |
| Patriot                   | 28       | 41     | 0.44%   |
| Team                      | 24       | 29     | 0.38%   |
| Intenso                   | 20       | 22     | 0.32%   |
| Lexar                     | 16       | 17     | 0.25%   |
| Hewlett-Packard           | 15       | 20     | 0.24%   |
| JMicron Technology        | 13       | 23     | 0.21%   |
| Gigabyte Technology       | 13       | 13     | 0.21%   |
| GOODRAM                   | 12       | 13     | 0.19%   |
| KingSpec                  | 11       | 14     | 0.17%   |
| Transcend                 | 10       | 12     | 0.16%   |
| SABRENT                   | 10       | 10     | 0.16%   |
| T-FORCE                   | 9        | 11     | 0.14%   |
| ASMT                      | 9        | 13     | 0.14%   |
| Apacer                    | 9        | 12     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 131      | 1.78%   |
| Samsung NVMe SSD Drive 500GB                        | 117      | 1.59%   |
| Kingston SA400S37240G 240GB SSD                     | 102      | 1.38%   |
| Seagate ST2000DM008-2FR102 2TB                      | 97       | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB                      | 91       | 1.23%   |
| Samsung SSD 850 EVO 250GB                           | 83       | 1.13%   |
| Seagate ST500DM002-1BD142 500GB                     | 75       | 1.02%   |
| Samsung SSD 850 EVO 500GB                           | 75       | 1.02%   |
| Samsung SSD 860 EVO 500GB                           | 71       | 0.96%   |
| Samsung SSD 860 EVO 1TB                             | 69       | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 65       | 0.88%   |
| SanDisk NVMe SSD Drive 500GB                        | 65       | 0.88%   |
| SanDisk NVMe SSD Drive 1TB                          | 65       | 0.88%   |
| Kingston SA400S37120G 120GB SSD                     | 59       | 0.8%    |
| Kingston SA400S37480G 480GB SSD                     | 49       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                         | 49       | 0.66%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 47       | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB                      | 45       | 0.61%   |
| Seagate ST4000DM004-2CV104 4TB                      | 43       | 0.58%   |
| Phison NVMe SSD Drive 1TB                           | 43       | 0.58%   |
| Toshiba DT01ACA100 1TB                              | 40       | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 39       | 0.53%   |
| Kingston SV300S37A120G 120GB SSD                    | 38       | 0.52%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 37       | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB                      | 36       | 0.49%   |
| Samsung SSD 860 EVO 250GB                           | 33       | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 33       | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 33       | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB                      | 29       | 0.39%   |
| Samsung NVMe SSD Drive 2TB                          | 29       | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 28       | 0.38%   |
| Toshiba HDWD110 1TB                                 | 28       | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 28       | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB                      | 27       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB                      | 27       | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                        | 27       | 0.37%   |
| Samsung SSD 860 QVO 1TB                             | 27       | 0.37%   |
| Phison NVMe SSD Drive 2TB                           | 27       | 0.37%   |
| Toshiba DT01ACA200 2TB                              | 26       | 0.35%   |
| Seagate ST3500418AS 500GB                           | 26       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1087     | 1664   | 40.64%  |
| WDC                 | 934      | 1384   | 34.92%  |
| Toshiba             | 243      | 308    | 9.08%   |
| Hitachi             | 156      | 201    | 5.83%   |
| Samsung Electronics | 107      | 130    | 4%      |
| HGST                | 45       | 61     | 1.68%   |
| Maxtor              | 27       | 28     | 1.01%   |
| Unknown             | 20       | 29     | 0.75%   |
| SABRENT             | 10       | 10     | 0.37%   |
| JMicron Technology  | 8        | 13     | 0.3%    |
| ASMT                | 7        | 10     | 0.26%   |
| Apple               | 7        | 9      | 0.26%   |
| Fujitsu             | 4        | 5      | 0.15%   |
| USB                 | 3        | 4      | 0.11%   |
| Hewlett-Packard     | 3        | 5      | 0.11%   |
| ExcelStor           | 3        | 3      | 0.11%   |
| Magnetic Data       | 2        | 2      | 0.07%   |
| RSH-339             | 1        | 1      | 0.04%   |
| Quantum             | 1        | 1      | 0.04%   |
| OEM                 | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 2      | 0.04%   |
| LaCie               | 1        | 1      | 0.04%   |
| HGST HTS            | 1        | 1      | 0.04%   |
| H/W                 | 1        | 1      | 0.04%   |
| Glyph               | 1        | 2      | 0.04%   |
| ASMT109x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 621      | 967    | 26.73%  |
| Kingston            | 330      | 432    | 14.21%  |
| Crucial             | 272      | 380    | 11.71%  |
| SanDisk             | 209      | 271    | 9%      |
| WDC                 | 167      | 215    | 7.19%   |
| A-DATA Technology   | 85       | 110    | 3.66%   |
| PNY                 | 75       | 99     | 3.23%   |
| China               | 66       | 97     | 2.84%   |
| Intel               | 58       | 76     | 2.5%    |
| OCZ                 | 41       | 54     | 1.76%   |
| SPCC                | 29       | 34     | 1.25%   |
| Patriot             | 28       | 41     | 1.21%   |
| SK hynix            | 25       | 39     | 1.08%   |
| Team                | 23       | 28     | 0.99%   |
| Corsair             | 23       | 29     | 0.99%   |
| Micron Technology   | 21       | 25     | 0.9%    |
| Toshiba             | 17       | 18     | 0.73%   |
| Seagate             | 17       | 31     | 0.73%   |
| Lexar               | 15       | 16     | 0.65%   |
| Intenso             | 13       | 15     | 0.56%   |
| KingSpec            | 11       | 14     | 0.47%   |
| Hewlett-Packard     | 11       | 14     | 0.47%   |
| Transcend           | 10       | 12     | 0.43%   |
| Goodram             | 10       | 11     | 0.43%   |
| Apacer              | 9        | 12     | 0.39%   |
| LITEONIT            | 8        | 8      | 0.34%   |
| Gigabyte Technology | 8        | 8      | 0.34%   |
| Plextor             | 7        | 9      | 0.3%    |
| Netac               | 7        | 7      | 0.3%    |
| TO Exter            | 6        | 9      | 0.26%   |
| Mushkin             | 6        | 8      | 0.26%   |
| LITEON              | 6        | 11     | 0.26%   |
| KingDian            | 5        | 6      | 0.22%   |
| Maxtor              | 4        | 4      | 0.17%   |
| XPG                 | 3        | 4      | 0.13%   |
| PNY USB             | 3        | 10     | 0.13%   |
| OWC                 | 3        | 12     | 0.13%   |
| Dogfish             | 3        | 4      | 0.13%   |
| Verbatim            | 2        | 3      | 0.09%   |
| TCSUNBOW            | 2        | 2      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2093     | 3877   | 39.26%  |
| SSD     | 1880     | 3225   | 35.27%  |
| NVMe    | 1219     | 2009   | 22.87%  |
| Unknown | 124      | 184    | 2.33%   |
| MMC     | 15       | 19     | 0.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2852     | 6887   | 65.68%  |
| NVMe | 1218     | 2001   | 28.05%  |
| SAS  | 257      | 407    | 5.92%   |
| MMC  | 15       | 19     | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2098     | 3602   | 48.37%  |
| 0.51-1.0   | 1258     | 1964   | 29.01%  |
| 1.01-2.0   | 531      | 775    | 12.24%  |
| 3.01-4.0   | 174      | 296    | 4.01%   |
| 2.01-3.0   | 135      | 198    | 3.11%   |
| 4.01-10.0  | 127      | 226    | 2.93%   |
| 10.01-20.0 | 14       | 41     | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 786      | 23.17%  |
| 251-500        | 681      | 20.07%  |
| 501-1000       | 664      | 19.57%  |
| 1001-2000      | 456      | 13.44%  |
| More than 3000 | 338      | 9.96%   |
| 2001-3000      | 198      | 5.84%   |
| 51-100         | 112      | 3.3%    |
| 1-20           | 80       | 2.36%   |
| 21-50          | 57       | 1.68%   |
| Unknown        | 21       | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1134     | 32.09%  |
| 21-50          | 597      | 16.89%  |
| 101-250        | 428      | 12.11%  |
| 51-100         | 370      | 10.47%  |
| 251-500        | 335      | 9.48%   |
| 501-1000       | 256      | 7.24%   |
| 1001-2000      | 200      | 5.66%   |
| More than 3000 | 122      | 3.45%   |
| 2001-3000      | 71       | 2.01%   |
| Unknown        | 21       | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 4      | 2.9%    |
| Seagate ST500DM002-1BD142 500GB    | 3        | 3      | 2.17%   |
| Seagate ST1500DL003-9VT16L 1TB     | 3        | 4      | 2.17%   |
| Seagate ST1000DM003-9YN162 1TB     | 3        | 3      | 2.17%   |
| Samsung Electronics HD502HI 500GB  | 3        | 4      | 2.17%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 5      | 2.17%   |
| Kingston SA400S37120G 120GB SSD    | 3        | 4      | 2.17%   |
| WDC WD3200AAKS-75B3A0 320GB        | 2        | 2      | 1.45%   |
| WDC WD10EZEX-60WN4A0 1TB           | 2        | 2      | 1.45%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2        | 2      | 1.45%   |
| Toshiba HDWD110 1TB                | 2        | 2      | 1.45%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2      | 1.45%   |
| Samsung Electronics HD103SJ 1TB    | 2        | 2      | 1.45%   |
| Hitachi HDP725050GLA360 500GB      | 2        | 2      | 1.45%   |
| Crucial CT525MX300SSD1 528GB       | 2        | 2      | 1.45%   |
| WDC WD7500BPVT-60HXZT1 752GB       | 1        | 1      | 0.72%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1        | 1      | 0.72%   |
| WDC WD6400AAKS-22A7B2 640GB        | 1        | 1      | 0.72%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 1      | 0.72%   |
| WDC WD5001AALS-00J7B1 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1        | 2      | 0.72%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1        | 2      | 0.72%   |
| WDC WD5000AVVS-63H0B1 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AAKS-41YGA1 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AADS-00M2B0 500GB        | 1        | 1      | 0.72%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 0.72%   |
| WDC WD30EZRX-00SPEB0 3TB           | 1        | 1      | 0.72%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 0.72%   |
| WDC WD20EFRX-68AX9N0 2TB           | 1        | 5      | 0.72%   |
| WDC WD2003FYYS-05T9B0 2TB          | 1        | 1      | 0.72%   |
| WDC WD15EVDS-73V9B0 1TB            | 1        | 1      | 0.72%   |
| WDC WD15EADS-11P8B1 1TB            | 1        | 1      | 0.72%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1        | 1      | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1        | 1      | 0.72%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 2      | 0.72%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1        | 1      | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 0.72%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1        | 1      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 45     | 27.61%  |
| WDC                 | 35       | 43     | 26.12%  |
| Samsung Electronics | 19       | 24     | 14.18%  |
| Kingston            | 8        | 11     | 5.97%   |
| Toshiba             | 7        | 7      | 5.22%   |
| Hitachi             | 5        | 6      | 3.73%   |
| HGST                | 5        | 5      | 3.73%   |
| Crucial             | 4        | 4      | 2.99%   |
| Intel               | 2        | 2      | 1.49%   |
| SPCC                | 1        | 1      | 0.75%   |
| SanDisk             | 1        | 1      | 0.75%   |
| SABRENT             | 1        | 1      | 0.75%   |
| S3+                 | 1        | 1      | 0.75%   |
| Plextor             | 1        | 1      | 0.75%   |
| Micron Technology   | 1        | 1      | 0.75%   |
| Maxtor              | 1        | 1      | 0.75%   |
| Intenso             | 1        | 1      | 0.75%   |
| China               | 1        | 1      | 0.75%   |
| BAITITON            | 1        | 1      | 0.75%   |
| ASMT                | 1        | 1      | 0.75%   |
| A-DATA Technology   | 1        | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 45     | 36.27%  |
| WDC                 | 35       | 43     | 34.31%  |
| Samsung Electronics | 10       | 11     | 9.8%    |
| Toshiba             | 7        | 7      | 6.86%   |
| Hitachi             | 5        | 6      | 4.9%    |
| HGST                | 5        | 5      | 4.9%    |
| SABRENT             | 1        | 1      | 0.98%   |
| Maxtor              | 1        | 1      | 0.98%   |
| ASMT                | 1        | 1      | 0.98%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 90       | 120    | 73.77%  |
| SSD  | 29       | 36     | 23.77%  |
| NVMe | 3        | 3      | 2.46%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Patriot Pyro SSD 120GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Patriot | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2810     | 7965   | 82.36%  |
| Works    | 485      | 1187   | 14.21%  |
| Malfunc  | 115      | 159    | 3.37%   |
| Failed   | 1        | 2      | 0.03%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1753     | 34.85%  |
| AMD                              | 1452     | 28.87%  |
| Samsung Electronics              | 545      | 10.83%  |
| SanDisk                          | 212      | 4.21%   |
| ASMedia Technology               | 191      | 3.8%    |
| Phison Electronics               | 186      | 3.7%    |
| Micron/Crucial Technology        | 92       | 1.83%   |
| Marvell Technology Group         | 81       | 1.61%   |
| Silicon Motion                   | 79       | 1.57%   |
| JMicron Technology               | 78       | 1.55%   |
| Kingston Technology Company      | 64       | 1.27%   |
| Nvidia                           | 59       | 1.17%   |
| ADATA Technology                 | 51       | 1.01%   |
| Realtek Semiconductor            | 36       | 0.72%   |
| Broadcom / LSI                   | 21       | 0.42%   |
| SK hynix                         | 19       | 0.38%   |
| Toshiba America Info Systems     | 16       | 0.32%   |
| Micron Technology                | 15       | 0.3%    |
| LSI Logic / Symbios Logic        | 14       | 0.28%   |
| Seagate Technology               | 13       | 0.26%   |
| VIA Technologies                 | 10       | 0.2%    |
| Lite-On Technology               | 8        | 0.16%   |
| Silicon Image                    | 6        | 0.12%   |
| Shenzhen Longsys Electronics     | 5        | 0.1%    |
| INNOGRIT                         | 4        | 0.08%   |
| Adaptec                          | 4        | 0.08%   |
| HighPoint Technologies           | 3        | 0.06%   |
| Silicon Integrated Systems [SiS] | 2        | 0.04%   |
| KIOXIA                           | 2        | 0.04%   |
| Hewlett-Packard                  | 2        | 0.04%   |
| Union Memory (Shenzhen)          | 1        | 0.02%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.02%   |
| Integrated Technology Express    | 1        | 0.02%   |
| Beijing Starblaze Technology     | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 957      | 15.45%  |
| AMD 400 Series Chipset SATA Controller                                                  | 427      | 6.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 349      | 5.63%   |
| AMD 500 Series Chipset SATA Controller                                                  | 207      | 3.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 196      | 3.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 183      | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 156      | 2.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 152      | 2.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 142      | 2.29%   |
| Intel SATA Controller [RAID mode]                                                       | 141      | 2.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 119      | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 104      | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 104      | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 99       | 1.6%    |
| Phison E12 NVMe Controller                                                              | 91       | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 79       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 76       | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                                  | 74       | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 73       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 73       | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 66       | 1.07%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 66       | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 65       | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 65       | 1.05%   |
| AMD FCH SATA Controller D                                                               | 65       | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 63       | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 58       | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 50       | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 50       | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 47       | 0.76%   |
| Samsung NVMe SSD Controller 980                                                         | 46       | 0.74%   |
| Intel SSD 660P Series                                                                   | 46       | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 46       | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 42       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 42       | 0.68%   |
| Nvidia MCP61 SATA Controller                                                            | 41       | 0.66%   |
| Kingston Company A2000 NVMe SSD                                                         | 41       | 0.66%   |
| AMD X370 Series Chipset SATA Controller                                                 | 39       | 0.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 34       | 0.55%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 34       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2752     | 57.61%  |
| NVMe | 1221     | 25.56%  |
| IDE  | 534      | 11.18%  |
| RAID | 227      | 4.75%   |
| SAS  | 32       | 0.67%   |
| SCSI | 11       | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1726     | 53.4%   |
| AMD    | 1506     | 46.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 145      | 4.46%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 111      | 3.41%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 67       | 2.06%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 63       | 1.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 55       | 1.69%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 54       | 1.66%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 50       | 1.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 46       | 1.41%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 45       | 1.38%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 43       | 1.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 42       | 1.29%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 42       | 1.29%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 40       | 1.23%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 38       | 1.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 36       | 1.11%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 34       | 1.05%   |
| AMD FX-8350 Eight-Core Processor            | 33       | 1.02%   |
| AMD FX-6300 Six-Core Processor              | 33       | 1.02%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 32       | 0.98%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 31       | 0.95%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 31       | 0.95%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 31       | 0.95%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 29       | 0.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 28       | 0.86%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 28       | 0.86%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 27       | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 25       | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 24       | 0.74%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 24       | 0.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 24       | 0.74%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 23       | 0.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.68%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 20       | 0.62%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 20       | 0.62%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 19       | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 19       | 0.58%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 19       | 0.58%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 18       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 538      | 16.57%  |
| AMD Ryzen 5             | 521      | 16.05%  |
| Intel Core i7           | 497      | 15.31%  |
| AMD Ryzen 7             | 340      | 10.47%  |
| AMD Ryzen 9             | 175      | 5.39%   |
| Intel Core i3           | 164      | 5.05%   |
| Intel Xeon              | 152      | 4.68%   |
| AMD FX                  | 117      | 3.6%    |
| Other                   | 68       | 2.09%   |
| AMD Ryzen 3             | 62       | 1.91%   |
| Intel Core i9           | 54       | 1.66%   |
| Intel Core 2 Duo        | 51       | 1.57%   |
| Intel Core 2 Quad       | 48       | 1.48%   |
| Intel Pentium           | 46       | 1.42%   |
| AMD Ryzen Threadripper  | 46       | 1.42%   |
| Intel Celeron           | 38       | 1.17%   |
| AMD Phenom II X4        | 31       | 0.96%   |
| Intel Pentium Dual-Core | 29       | 0.89%   |
| AMD A10                 | 28       | 0.86%   |
| AMD A8                  | 26       | 0.8%    |
| AMD Athlon II X2        | 21       | 0.65%   |
| AMD Athlon              | 17       | 0.52%   |
| Intel Core 2            | 16       | 0.49%   |
| AMD Athlon II X4        | 14       | 0.43%   |
| AMD A6                  | 14       | 0.43%   |
| AMD Phenom II X6        | 12       | 0.37%   |
| AMD A4                  | 12       | 0.37%   |
| AMD Athlon 64 X2        | 10       | 0.31%   |
| Intel Atom              | 9        | 0.28%   |
| AMD Phenom              | 9        | 0.28%   |
| Intel Pentium Dual      | 8        | 0.25%   |
| AMD Ryzen 5 PRO         | 8        | 0.25%   |
| AMD Athlon X4           | 7        | 0.22%   |
| Intel Pentium Gold      | 6        | 0.18%   |
| Intel Pentium D         | 5        | 0.15%   |
| AMD Sempron             | 5        | 0.15%   |
| AMD Ryzen 7 PRO         | 4        | 0.12%   |
| AMD Ryzen 3 PRO         | 4        | 0.12%   |
| AMD Athlon II X3        | 4        | 0.12%   |
| AMD Athlon 64           | 4        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1235     | 38.06%  |
| 6      | 687      | 21.17%  |
| 8      | 471      | 14.51%  |
| 2      | 466      | 14.36%  |
| 12     | 150      | 4.62%   |
| 16     | 76       | 2.34%   |
| 3      | 50       | 1.54%   |
| 10     | 35       | 1.08%   |
| 1      | 30       | 0.92%   |
| 24     | 18       | 0.55%   |
| 32     | 16       | 0.49%   |
| 64     | 4        | 0.12%   |
| 14     | 4        | 0.12%   |
| 36     | 1        | 0.03%   |
| 28     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3198     | 98.95%  |
| 2      | 34       | 1.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2201     | 67.95%  |
| 1      | 1038     | 32.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3228     | 99.88%  |
| Unknown        | 4        | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2339     | 70.66%  |
| 0x08701021 | 103      | 3.11%   |
| 0x306c3    | 75       | 2.27%   |
| 0x0800820d | 73       | 2.21%   |
| 0x08701013 | 72       | 2.18%   |
| 0x306a9    | 61       | 1.84%   |
| 0x206a7    | 50       | 1.51%   |
| 0x506e3    | 41       | 1.24%   |
| 0x906ea    | 38       | 1.15%   |
| 0x906e9    | 30       | 0.91%   |
| 0x1067a    | 27       | 0.82%   |
| 0x08001138 | 27       | 0.82%   |
| 0x0a201016 | 25       | 0.76%   |
| 0x08108109 | 24       | 0.73%   |
| 0x06000852 | 24       | 0.73%   |
| 0x906ec    | 15       | 0.45%   |
| 0x906ed    | 14       | 0.42%   |
| 0x0a201009 | 13       | 0.39%   |
| 0x08301039 | 13       | 0.39%   |
| 0x08001137 | 11       | 0.33%   |
| 0x06001119 | 11       | 0.33%   |
| 0xa0655    | 10       | 0.3%    |
| 0x010000c8 | 10       | 0.3%    |
| 0x306f2    | 9        | 0.27%   |
| 0x106a5    | 9        | 0.27%   |
| 0x06003106 | 9        | 0.27%   |
| 0xa0653    | 8        | 0.24%   |
| 0x206c2    | 8        | 0.24%   |
| 0xa0671    | 7        | 0.21%   |
| 0x906eb    | 7        | 0.21%   |
| 0x90672    | 6        | 0.18%   |
| 0x6fd      | 6        | 0.18%   |
| 0x206d7    | 6        | 0.18%   |
| 0x20655    | 6        | 0.18%   |
| 0x0a50000c | 6        | 0.18%   |
| 0x08101016 | 6        | 0.18%   |
| 0x6fb      | 5        | 0.15%   |
| 0x010000dc | 5        | 0.15%   |
| 0x50654    | 4        | 0.12%   |
| 0x306e4    | 4        | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 487      | 15.02%  |
| Haswell          | 336      | 10.36%  |
| KabyLake         | 291      | 8.97%   |
| Zen+             | 262      | 8.08%   |
| Zen 3            | 247      | 7.62%   |
| IvyBridge        | 230      | 7.09%   |
| SandyBridge      | 216      | 6.66%   |
| Zen              | 167      | 5.15%   |
| Skylake          | 164      | 5.06%   |
| Piledriver       | 143      | 4.41%   |
| Penryn           | 108      | 3.33%   |
| K10              | 101      | 3.11%   |
| CometLake        | 84       | 2.59%   |
| Nehalem          | 72       | 2.22%   |
| Unknown          | 69       | 2.13%   |
| Westmere         | 55       | 1.7%    |
| Core             | 55       | 1.7%    |
| Steamroller      | 25       | 0.77%   |
| Silvermont       | 21       | 0.65%   |
| K8 Hammer        | 18       | 0.56%   |
| Excavator        | 16       | 0.49%   |
| K10 Llano        | 13       | 0.4%    |
| Bulldozer        | 11       | 0.34%   |
| NetBurst         | 8        | 0.25%   |
| Icelake          | 7        | 0.22%   |
| Goldmont plus    | 7        | 0.22%   |
| Broadwell        | 7        | 0.22%   |
| Alderlake Hybrid | 7        | 0.22%   |
| Jaguar           | 6        | 0.19%   |
| Bobcat           | 4        | 0.12%   |
| Goldmont         | 3        | 0.09%   |
| Bonnell          | 2        | 0.06%   |
| Puma             | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1684     | 48.45%  |
| AMD                              | 1184     | 34.06%  |
| Intel                            | 601      | 17.29%  |
| Matrox Electronics Systems       | 5        | 0.14%   |
| Silicon Integrated Systems [SiS] | 2        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 238      | 6.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 113      | 3.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 113      | 3.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 104      | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 77       | 2.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 76       | 2.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 74       | 2.06%   |
| Nvidia GK208B [GeForce GT 710]                                              | 65       | 1.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 65       | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 63       | 1.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 61       | 1.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 54       | 1.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 54       | 1.5%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 48       | 1.34%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 47       | 1.31%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 46       | 1.28%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 44       | 1.22%   |
| Intel HD Graphics 530                                                       | 44       | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 41       | 1.14%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 40       | 1.11%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 38       | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 38       | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 37       | 1.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 34       | 0.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 34       | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 33       | 0.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 33       | 0.92%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 32       | 0.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 31       | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 30       | 0.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 30       | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 29       | 0.81%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 28       | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 28       | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                  | 28       | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 27       | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 27       | 0.75%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 26       | 0.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 26       | 0.72%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 26       | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1558     | 47.46%  |
| 1 x AMD              | 1078     | 32.84%  |
| 1 x Intel            | 442      | 13.46%  |
| Intel + Nvidia       | 47       | 1.43%   |
| 2 x AMD              | 46       | 1.4%    |
| AMD + Nvidia         | 39       | 1.19%   |
| 2 x Nvidia           | 33       | 1.01%   |
| Intel + AMD          | 25       | 0.76%   |
| 1 x Matrox           | 4        | 0.12%   |
| 1 x SiS              | 2        | 0.06%   |
| Intel + 2 x Nvidia   | 2        | 0.06%   |
| Other                | 1        | 0.03%   |
| 5 x Nvidia           | 1        | 0.03%   |
| 4 x Nvidia           | 1        | 0.03%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia     | 1        | 0.03%   |
| AMD + Matrox         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1716     | 52.32%  |
| Proprietary | 1368     | 41.71%  |
| Unknown     | 196      | 5.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1735     | 52.37%  |
| 7.01-8.0   | 445      | 13.43%  |
| 1.01-2.0   | 290      | 8.75%   |
| 3.01-4.0   | 274      | 8.27%   |
| 5.01-6.0   | 235      | 7.09%   |
| 8.01-16.0  | 137      | 4.14%   |
| 0.51-1.0   | 83       | 2.51%   |
| 2.01-3.0   | 48       | 1.45%   |
| 0.01-0.5   | 43       | 1.3%    |
| 16.01-24.0 | 18       | 0.54%   |
| 4.01-5.0   | 3        | 0.09%   |
| 32.01-64.0 | 1        | 0.03%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 594      | 16.49%  |
| Goldstar             | 427      | 11.85%  |
| Dell                 | 399      | 11.07%  |
| Acer                 | 319      | 8.85%   |
| Hewlett-Packard      | 219      | 6.08%   |
| AOC                  | 204      | 5.66%   |
| Ancor Communications | 181      | 5.02%   |
| BenQ                 | 167      | 4.64%   |
| ASUSTek Computer     | 121      | 3.36%   |
| Philips              | 104      | 2.89%   |
| ViewSonic            | 64       | 1.78%   |
| Lenovo               | 58       | 1.61%   |
| Iiyama               | 56       | 1.55%   |
| Sony                 | 48       | 1.33%   |
| MSI                  | 45       | 1.25%   |
| Sceptre Tech         | 39       | 1.08%   |
| Vizio                | 28       | 0.78%   |
| Toshiba              | 22       | 0.61%   |
| Gigabyte Technology  | 22       | 0.61%   |
| Unknown              | 21       | 0.58%   |
| Panasonic            | 17       | 0.47%   |
| Eizo                 | 16       | 0.44%   |
| Insignia             | 15       | 0.42%   |
| Fujitsu Siemens      | 15       | 0.42%   |
| NEC Computers        | 14       | 0.39%   |
| LG Electronics       | 13       | 0.36%   |
| MStar                | 12       | 0.33%   |
| Hitachi              | 12       | 0.33%   |
| Vestel Elektronik    | 11       | 0.31%   |
| HannStar             | 9        | 0.25%   |
| Viotek               | 8        | 0.22%   |
| Videoseven           | 8        | 0.22%   |
| Pixio                | 8        | 0.22%   |
| ONN                  | 8        | 0.22%   |
| Mi                   | 8        | 0.22%   |
| Valve                | 7        | 0.19%   |
| MiTAC                | 7        | 0.19%   |
| CVT                  | 7        | 0.19%   |
| ___                  | 6        | 0.17%   |
| Sharp                | 6        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 42       | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 28       | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 23       | 0.6%    |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 22       | 0.58%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 18       | 0.47%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 16       | 0.42%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                    | 15       | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 14       | 0.37%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 13       | 0.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 13       | 0.34%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 13       | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.31%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 12       | 0.31%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 12       | 0.31%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 12       | 0.31%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 11       | 0.29%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 11       | 0.29%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10       | 0.26%   |
| Panasonic TV MEIA296 3840x2160 1872x1053mm 84.6-inch                  | 10       | 0.26%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 10       | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 10       | 0.26%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 10       | 0.26%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                    | 10       | 0.26%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                       | 9        | 0.24%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 9        | 0.24%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 9        | 0.24%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch               | 8        | 0.21%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 8        | 0.21%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch   | 8        | 0.21%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 8        | 0.21%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 8        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8        | 0.21%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 8        | 0.21%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.21%   |
| AOC 2770G4 AOC2770 1920x1080 598x336mm 27.0-inch                      | 8        | 0.21%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8        | 0.21%   |
| AOC 2460G5 AOC0001 1920x1080 531x299mm 24.0-inch                      | 8        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 8        | 0.21%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 8        | 0.21%   |
| Valve LCD Monitor VLV91A8                                             | 7        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1575     | 45.99%  |
| 3840x2160 (4K)     | 426      | 12.44%  |
| 2560x1440 (QHD)    | 358      | 10.45%  |
| 1680x1050 (WSXGA+) | 136      | 3.97%   |
| 1280x1024 (SXGA)   | 133      | 3.88%   |
| 3440x1440          | 125      | 3.65%   |
| 1366x768 (WXGA)    | 113      | 3.3%    |
| 2560x1080          | 108      | 3.15%   |
| 1920x1200 (WUXGA)  | 83       | 2.42%   |
| 1440x900 (WXGA+)   | 81       | 2.36%   |
| 1600x900 (HD+)     | 73       | 2.13%   |
| 1360x768           | 41       | 1.2%    |
| 3840x1080          | 33       | 0.96%   |
| 1920x540           | 29       | 0.85%   |
| Unknown            | 26       | 0.76%   |
| 3840x1600          | 12       | 0.35%   |
| 1600x1200          | 10       | 0.29%   |
| 1280x720 (HD)      | 10       | 0.29%   |
| 1024x768 (XGA)     | 10       | 0.29%   |
| 2560x1600          | 7        | 0.2%    |
| 2048x1152          | 4        | 0.12%   |
| 4480x1440          | 3        | 0.09%   |
| 5120x1440          | 2        | 0.06%   |
| 3840x1200          | 2        | 0.06%   |
| 9840x3840          | 1        | 0.03%   |
| 8320x2160          | 1        | 0.03%   |
| 8160x4627          | 1        | 0.03%   |
| 7680x2160          | 1        | 0.03%   |
| 6400x1440          | 1        | 0.03%   |
| 5280x1080          | 1        | 0.03%   |
| 5200x2160          | 1        | 0.03%   |
| 4096x2160          | 1        | 0.03%   |
| 4080x2030          | 1        | 0.03%   |
| 4080x2026          | 1        | 0.03%   |
| 3360x1080          | 1        | 0.03%   |
| 3280x2048          | 1        | 0.03%   |
| 3280x1080          | 1        | 0.03%   |
| 3040x900           | 1        | 0.03%   |
| 2960x1050          | 1        | 0.03%   |
| 2880x1600          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 638      | 17.79%  |
| 24      | 539      | 15.03%  |
| 23      | 436      | 12.16%  |
| 21      | 343      | 9.56%   |
| 31      | 215      | 5.99%   |
| 34      | 197      | 5.49%   |
| 19      | 148      | 4.13%   |
| Unknown | 121      | 3.37%   |
| 22      | 101      | 2.82%   |
| 18      | 101      | 2.82%   |
| 20      | 80       | 2.23%   |
| 84      | 71       | 1.98%   |
| 17      | 68       | 1.9%    |
| 32      | 59       | 1.64%   |
| 72      | 55       | 1.53%   |
| 15      | 46       | 1.28%   |
| 40      | 33       | 0.92%   |
| 54      | 32       | 0.89%   |
| 26      | 28       | 0.78%   |
| 25      | 26       | 0.72%   |
| 48      | 24       | 0.67%   |
| 49      | 21       | 0.59%   |
| 35      | 20       | 0.56%   |
| 65      | 18       | 0.5%    |
| 28      | 18       | 0.5%    |
| 52      | 15       | 0.42%   |
| 37      | 13       | 0.36%   |
| 29      | 12       | 0.33%   |
| 46      | 11       | 0.31%   |
| 42      | 9        | 0.25%   |
| 33      | 9        | 0.25%   |
| 47      | 8        | 0.22%   |
| 36      | 7        | 0.2%    |
| 43      | 6        | 0.17%   |
| 74      | 5        | 0.14%   |
| 55      | 5        | 0.14%   |
| 12      | 5        | 0.14%   |
| 38      | 4        | 0.11%   |
| 11      | 4        | 0.11%   |
| 64      | 3        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1438     | 41.92%  |
| 401-500        | 679      | 19.8%   |
| 601-700        | 333      | 9.71%   |
| 701-800        | 266      | 7.76%   |
| 1001-1500      | 151      | 4.4%    |
| 1501-2000      | 134      | 3.91%   |
| Unknown        | 121      | 3.53%   |
| 301-350        | 103      | 3%      |
| 351-400        | 95       | 2.77%   |
| 801-900        | 77       | 2.24%   |
| 901-1000       | 19       | 0.55%   |
| 201-300        | 13       | 0.38%   |
| More than 2000 | 1        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2290     | 72.08%  |
| 16/10   | 352      | 11.08%  |
| 21/9    | 239      | 7.52%   |
| 5/4     | 130      | 4.09%   |
| Unknown | 72       | 2.27%   |
| 32/9    | 37       | 1.16%   |
| 4/3     | 33       | 1.04%   |
| 3/2     | 9        | 0.28%   |
| 6/5     | 7        | 0.22%   |
| 1.96    | 5        | 0.16%   |
| 3.20    | 2        | 0.06%   |
| 1.00    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1109     | 31.75%  |
| 301-350        | 653      | 18.69%  |
| 351-500        | 502      | 14.37%  |
| 151-200        | 332      | 9.5%    |
| More than 1000 | 228      | 6.53%   |
| 251-300        | 209      | 5.98%   |
| 141-150        | 136      | 3.89%   |
| 501-1000       | 135      | 3.86%   |
| Unknown        | 121      | 3.46%   |
| 101-110        | 36       | 1.03%   |
| 131-140        | 8        | 0.23%   |
| 71-80          | 7        | 0.2%    |
| 91-100         | 6        | 0.17%   |
| 51-60          | 4        | 0.11%   |
| 111-120        | 4        | 0.11%   |
| 121-130        | 3        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1994     | 60.94%  |
| 101-120       | 722      | 22.07%  |
| 1-50          | 182      | 5.56%   |
| 121-160       | 176      | 5.38%   |
| Unknown       | 121      | 3.7%    |
| 161-240       | 76       | 2.32%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2296     | 69.41%  |
| 2     | 690      | 20.86%  |
| 0     | 225      | 6.8%    |
| 3     | 86       | 2.6%    |
| 4     | 9        | 0.27%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1919     | 40.27%  |
| Intel                                 | 1564     | 32.82%  |
| Qualcomm Atheros                      | 282      | 5.92%   |
| Broadcom                              | 165      | 3.46%   |
| TP-Link                               | 96       | 2.01%   |
| Ralink Technology                     | 96       | 2.01%   |
| Microsoft                             | 63       | 1.32%   |
| Nvidia                                | 48       | 1.01%   |
| Ralink                                | 43       | 0.9%    |
| Samsung Electronics                   | 40       | 0.84%   |
| Qualcomm Atheros Communications       | 33       | 0.69%   |
| NetGear                               | 33       | 0.69%   |
| InterBiometrics                       | 33       | 0.69%   |
| Aquantia                              | 29       | 0.61%   |
| MediaTek                              | 27       | 0.57%   |
| Xiaomi                                | 22       | 0.46%   |
| Marvell Technology Group              | 20       | 0.42%   |
| D-Link                                | 18       | 0.38%   |
| Huawei Technologies                   | 17       | 0.36%   |
| Google                                | 17       | 0.36%   |
| Linksys                               | 14       | 0.29%   |
| Broadcom Limited                      | 14       | 0.29%   |
| ASUSTek Computer                      | 13       | 0.27%   |
| D-Link System                         | 11       | 0.23%   |
| ASIX Electronics                      | 11       | 0.23%   |
| Edimax Technology                     | 9        | 0.19%   |
| Belkin Components                     | 8        | 0.17%   |
| OnePlus Technology (Shenzhen)         | 7        | 0.15%   |
| Motorola PCS                          | 7        | 0.15%   |
| OPPO                                  | 6        | 0.13%   |
| DisplayLink                           | 6        | 0.13%   |
| AVM                                   | 6        | 0.13%   |
| VIA Technologies                      | 5        | 0.1%    |
| Sitecom Europe                        | 5        | 0.1%    |
| Gemtek                                | 5        | 0.1%    |
| Mercucys                              | 4        | 0.08%   |
| Mellanox Technologies                 | 4        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.08%   |
| Qualcomm                              | 3        | 0.06%   |
| Microchip Technology                  | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1503     | 27.11%  |
| Intel I211 Gigabit Network Connection                             | 382      | 6.89%   |
| Intel Wi-Fi 6 AX200                                               | 332      | 5.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 202      | 3.64%   |
| Intel Ethernet Connection (2) I219-V                              | 141      | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 122      | 2.2%    |
| Intel Ethernet Controller I225-V                                  | 120      | 2.16%   |
| Intel Wireless-AC 9260                                            | 98       | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 96       | 1.73%   |
| Intel Ethernet Connection (7) I219-V                              | 85       | 1.53%   |
| Intel Ethernet Connection I217-LM                                 | 71       | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 58       | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 52       | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 49       | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 48       | 0.87%   |
| Realtek 802.11ac NIC                                              | 46       | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                   | 40       | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 40       | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 36       | 0.65%   |
| Nvidia MCP61 Ethernet                                             | 35       | 0.63%   |
| InterBiometrics Io                                                | 32       | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.54%   |
| Microsoft XBOX ACC                                                | 30       | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29       | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29       | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 27       | 0.49%   |
| Intel Wireless 7265                                               | 27       | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25       | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25       | 0.45%   |
| Microsoft Xbox 360 Wireless Adapter                               | 24       | 0.43%   |
| Intel Wireless 8265 / 8275                                        | 24       | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 24       | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 23       | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23       | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 23       | 0.41%   |
| Intel Wireless 8260                                               | 22       | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 759      | 40.76%  |
| Realtek Semiconductor                 | 370      | 19.87%  |
| Qualcomm Atheros                      | 146      | 7.84%   |
| Ralink Technology                     | 96       | 5.16%   |
| Broadcom                              | 96       | 5.16%   |
| TP-Link                               | 92       | 4.94%   |
| Microsoft                             | 63       | 3.38%   |
| Ralink                                | 43       | 2.31%   |
| Qualcomm Atheros Communications       | 33       | 1.77%   |
| NetGear                               | 33       | 1.77%   |
| MediaTek                              | 23       | 1.24%   |
| D-Link                                | 17       | 0.91%   |
| Linksys                               | 13       | 0.7%    |
| ASUSTek Computer                      | 13       | 0.7%    |
| Edimax Technology                     | 9        | 0.48%   |
| Belkin Components                     | 8        | 0.43%   |
| D-Link System                         | 7        | 0.38%   |
| AVM                                   | 6        | 0.32%   |
| Sitecom Europe                        | 5        | 0.27%   |
| Gemtek                                | 5        | 0.27%   |
| Broadcom Limited                      | 5        | 0.27%   |
| Mercucys                              | 4        | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.21%   |
| IMC Networks                          | 3        | 0.16%   |
| ZyDAS                                 | 1        | 0.05%   |
| Wilocity                              | 1        | 0.05%   |
| TRENDnet                              | 1        | 0.05%   |
| Texas Instruments                     | 1        | 0.05%   |
| Samsung Electronics                   | 1        | 0.05%   |
| Ovislink                              | 1        | 0.05%   |
| Micro Star International              | 1        | 0.05%   |
| BUFFALO                               | 1        | 0.05%   |
| Accton Technology                     | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 332      | 17.63%  |
| Intel Wireless-AC 9260                                         | 98       | 5.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 96       | 5.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 58       | 3.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 52       | 2.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 48       | 2.55%   |
| Realtek 802.11ac NIC                                           | 46       | 2.44%   |
| Ralink MT7601U Wireless Adapter                                | 40       | 2.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 40       | 2.12%   |
| Microsoft XBOX ACC                                             | 30       | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29       | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29       | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                                | 27       | 1.43%   |
| Intel Wireless 7265                                            | 27       | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25       | 1.33%   |
| Microsoft Xbox 360 Wireless Adapter                            | 24       | 1.27%   |
| Intel Wireless 8265 / 8275                                     | 24       | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 23       | 1.22%   |
| Intel Wireless 8260                                            | 22       | 1.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 1.06%   |
| Intel Wireless 7260                                            | 20       | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19       | 1.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 19       | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19       | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 18       | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 17       | 0.9%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 16       | 0.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 15       | 0.8%    |
| Ralink RT5370 Wireless Adapter                                 | 15       | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15       | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 14       | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 14       | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14       | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 14       | 0.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 13       | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 13       | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13       | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13       | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 11       | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1774     | 50.6%   |
| Intel                            | 1231     | 35.11%  |
| Qualcomm Atheros                 | 146      | 4.16%   |
| Broadcom                         | 75       | 2.14%   |
| Nvidia                           | 48       | 1.37%   |
| Samsung Electronics              | 39       | 1.11%   |
| Aquantia                         | 29       | 0.83%   |
| Xiaomi                           | 22       | 0.63%   |
| Marvell Technology Group         | 20       | 0.57%   |
| Huawei Technologies              | 17       | 0.48%   |
| Google                           | 17       | 0.48%   |
| ASIX Electronics                 | 11       | 0.31%   |
| Broadcom Limited                 | 9        | 0.26%   |
| OPPO                             | 6        | 0.17%   |
| DisplayLink                      | 6        | 0.17%   |
| VIA Technologies                 | 5        | 0.14%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.14%   |
| Motorola PCS                     | 5        | 0.14%   |
| TP-Link                          | 4        | 0.11%   |
| MediaTek                         | 4        | 0.11%   |
| D-Link System                    | 4        | 0.11%   |
| Qualcomm                         | 3        | 0.09%   |
| Mellanox Technologies            | 3        | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.06%   |
| Lenovo                           | 2        | 0.06%   |
| ICS Advent                       | 2        | 0.06%   |
| 3Com                             | 2        | 0.06%   |
| Tehuti Networks                  | 1        | 0.03%   |
| T & A Mobile Phones              | 1        | 0.03%   |
| Solarflare Communications        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| QLogic                           | 1        | 0.03%   |
| Netchip Technology               | 1        | 0.03%   |
| Linksys                          | 1        | 0.03%   |
| LG Electronics                   | 1        | 0.03%   |
| JMicron Technology               | 1        | 0.03%   |
| HMD Global                       | 1        | 0.03%   |
| Hangzhou Silan Microelectronics  | 1        | 0.03%   |
| Emulex                           | 1        | 0.03%   |
| D-Link                           | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1503     | 41.8%   |
| Intel I211 Gigabit Network Connection                             | 382      | 10.62%  |
| Realtek RTL8125 2.5GbE Controller                                 | 202      | 5.62%   |
| Intel Ethernet Connection (2) I219-V                              | 141      | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 122      | 3.39%   |
| Intel Ethernet Controller I225-V                                  | 120      | 3.34%   |
| Intel Ethernet Connection (7) I219-V                              | 85       | 2.36%   |
| Intel Ethernet Connection I217-LM                                 | 71       | 1.97%   |
| Intel 82579V Gigabit Network Connection                           | 49       | 1.36%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 1.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 36       | 1%      |
| Nvidia MCP61 Ethernet                                             | 35       | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25       | 0.7%    |
| Intel 82574L Gigabit Network Connection                           | 24       | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23       | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 23       | 0.64%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21       | 0.58%   |
| Intel I210 Gigabit Network Connection                             | 20       | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 20       | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 18       | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 15       | 0.42%   |
| Huawei MLA-L11                                                    | 15       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15       | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 14       | 0.39%   |
| Google Nexus/Pixel Device (tether)                                | 14       | 0.39%   |
| Intel Ethernet Connection (14) I219-V                             | 12       | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11       | 0.31%   |
| Intel Ethernet Connection (2) I218-LM                             | 10       | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 9        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 9        | 0.25%   |
| Intel 82583V Gigabit Network Connection                           | 9        | 0.25%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 9        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3191     | 64.01%  |
| WiFi     | 1729     | 34.68%  |
| Modem    | 53       | 1.06%   |
| Unknown  | 12       | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2429     | 71.19%  |
| WiFi     | 981      | 28.75%  |
| Unknown  | 2        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1905     | 58.54%  |
| 2     | 1132     | 34.79%  |
| 3     | 154      | 4.73%   |
| 0     | 33       | 1.01%   |
| 4     | 22       | 0.68%   |
| 5     | 4        | 0.12%   |
| 10    | 2        | 0.06%   |
| 6     | 2        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2585     | 78.6%   |
| Yes  | 704      | 21.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 704      | 53.37%  |
| Cambridge Silicon Radio         | 272      | 20.62%  |
| ASUSTek Computer                | 79       | 5.99%   |
| Realtek Semiconductor           | 67       | 5.08%   |
| Broadcom                        | 60       | 4.55%   |
| Qualcomm Atheros Communications | 42       | 3.18%   |
| Apple                           | 22       | 1.67%   |
| MediaTek                        | 11       | 0.83%   |
| TP-Link                         | 9        | 0.68%   |
| Foxconn / Hon Hai               | 9        | 0.68%   |
| IMC Networks                    | 7        | 0.53%   |
| Dynex                           | 6        | 0.45%   |
| Lite-On Technology              | 4        | 0.3%    |
| HTC (High Tech Computer)        | 4        | 0.3%    |
| Integrated System Solution      | 3        | 0.23%   |
| SINO WEALTH                     | 2        | 0.15%   |
| Realtek                         | 2        | 0.15%   |
| Ralink                          | 2        | 0.15%   |
| Hewlett-Packard                 | 2        | 0.15%   |
| Dell                            | 2        | 0.15%   |
| Creative Technology             | 2        | 0.15%   |
| Conwise Technology              | 2        | 0.15%   |
| Belkin Components               | 2        | 0.15%   |
| Primax Electronics              | 1        | 0.08%   |
| Micro Star International        | 1        | 0.08%   |
| Logitech                        | 1        | 0.08%   |
| Edimax Technology               | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 310      | 23.45%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 272      | 20.57%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 94       | 7.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 93       | 7.03%   |
| Intel Bluetooth wireless interface                                   | 93       | 7.03%   |
| Realtek Bluetooth Radio                                              | 45       | 3.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 45       | 3.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 42       | 3.18%   |
| Intel AX201 Bluetooth                                                | 37       | 2.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 26       | 1.97%   |
| Intel AX210 Bluetooth                                                | 25       | 1.89%   |
| Qualcomm Atheros  Bluetooth Device                                   | 22       | 1.66%   |
| ASUS Bluetooth Radio                                                 | 21       | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 16       | 1.21%   |
| Apple Bluetooth USB Host Controller                                  | 12       | 0.91%   |
| MediaTek Wireless_Device                                             | 11       | 0.83%   |
| TP-Link TPuLink UB500 Adapter                                        | 9        | 0.68%   |
| ASUS ASUS USB-BT500                                                  | 9        | 0.68%   |
| Intel Bluetooth Device                                               | 8        | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.45%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.45%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.45%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.45%   |
| ASUS BCM20702A0                                                      | 6        | 0.45%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 5        | 0.38%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5        | 0.38%   |
| Realtek RTL8821A Bluetooth                                           | 4        | 0.3%    |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 4        | 0.3%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.3%    |
| Apple Bluetooth HCI                                                  | 4        | 0.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.23%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3        | 0.23%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 3        | 0.23%   |
| ASUS Bluetooth Device                                                | 3        | 0.23%   |
| ASUS Bluetooth Adapter                                               | 3        | 0.23%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 2        | 0.15%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 2        | 0.15%   |
| Realtek Bluetooth Radio                                              | 2        | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 1802     | 29.08%  |
| Intel                                           | 1635     | 26.39%  |
| Nvidia                                          | 1625     | 26.23%  |
| C-Media Electronics                             | 174      | 2.81%   |
| Logitech                                        | 86       | 1.39%   |
| Creative Labs                                   | 64       | 1.03%   |
| Razer USA                                       | 50       | 0.81%   |
| Kingston Technology                             | 48       | 0.77%   |
| JMTek                                           | 47       | 0.76%   |
| Corsair                                         | 47       | 0.76%   |
| Texas Instruments                               | 39       | 0.63%   |
| SteelSeries ApS                                 | 36       | 0.58%   |
| Focusrite-Novation                              | 36       | 0.58%   |
| ASUSTek Computer                                | 31       | 0.5%    |
| Creative Technology                             | 26       | 0.42%   |
| Blue Microphones                                | 26       | 0.42%   |
| Generalplus Technology                          | 22       | 0.36%   |
| Giga-Byte Technology                            | 16       | 0.26%   |
| Sony                                            | 15       | 0.24%   |
| Micro Star International                        | 15       | 0.24%   |
| Astro Gaming                                    | 15       | 0.24%   |
| GN Netcom                                       | 13       | 0.21%   |
| Samson Technologies                             | 12       | 0.19%   |
| Turtle Beach                                    | 11       | 0.18%   |
| Tenx Technology                                 | 11       | 0.18%   |
| Plantronics                                     | 11       | 0.18%   |
| M-Audio                                         | 11       | 0.18%   |
| Valve Software                                  | 10       | 0.16%   |
| SAVITECH                                        | 10       | 0.16%   |
| Realtek Semiconductor                           | 10       | 0.16%   |
| Yamaha                                          | 9        | 0.15%   |
| FiiO Electronics Technology                     | 9        | 0.15%   |
| Thesycon Systemsoftware & Consulting            | 8        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 8        | 0.13%   |
| BEHRINGER International                         | 8        | 0.13%   |
| DSEA A/S                                        | 7        | 0.11%   |
| Audio-Technica                                  | 7        | 0.11%   |
| Unknown                                         | 6        | 0.1%    |
| Sennheiser Communications                       | 6        | 0.1%    |
| VIA Technologies                                | 5        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 650      | 8.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 291      | 4.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 239      | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 223      | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 216      | 2.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 196      | 2.71%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 180      | 2.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 170      | 2.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 159      | 2.2%    |
| Intel 200 Series PCH HD Audio                                              | 159      | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 154      | 2.13%   |
| AMD Navi 10 HDMI Audio                                                     | 140      | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 138      | 1.91%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 130      | 1.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 127      | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 125      | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 119      | 1.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 115      | 1.59%   |
| Nvidia TU104 HD Audio Controller                                           | 101      | 1.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 100      | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 95       | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 92       | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 85       | 1.18%   |
| AMD FCH Azalia Controller                                                  | 85       | 1.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 83       | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 79       | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                              | 75       | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 75       | 1.04%   |
| Nvidia GM204 High Definition Audio Controller                              | 69       | 0.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 66       | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 63       | 0.87%   |
| Nvidia GA102 High Definition Audio Controller                              | 59       | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 56       | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                              | 53       | 0.73%   |
| Nvidia GP102 HDMI Audio Controller                                         | 49       | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                         | 49       | 0.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 48       | 0.66%   |
| Nvidia MCP61 High Definition Audio                                         | 41       | 0.57%   |
| Nvidia GP108 High Definition Audio Controller                              | 41       | 0.57%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 41       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 137      | 22.99%  |
| Kingston                     | 108      | 18.12%  |
| G.Skill                      | 88       | 14.77%  |
| Crucial                      | 58       | 9.73%   |
| Unknown                      | 51       | 8.56%   |
| Samsung Electronics          | 33       | 5.54%   |
| SK hynix                     | 27       | 4.53%   |
| Team                         | 22       | 3.69%   |
| Micron Technology            | 18       | 3.02%   |
| A-DATA Technology            | 15       | 2.52%   |
| Patriot                      | 8        | 1.34%   |
| Ramaxel Technology           | 3        | 0.5%    |
| Patriot Memory               | 2        | 0.34%   |
| OLOY                         | 2        | 0.34%   |
| Avant                        | 2        | 0.34%   |
| Unknown                      | 2        | 0.34%   |
| Unifosa                      | 1        | 0.17%   |
| Transcend                    | 1        | 0.17%   |
| Toshiba                      | 1        | 0.17%   |
| Teikon                       | 1        | 0.17%   |
| Smart                        | 1        | 0.17%   |
| Silicon Power                | 1        | 0.17%   |
| Patriot Memory (PDP Systems) | 1        | 0.17%   |
| Neo Forza                    | 1        | 0.17%   |
| Nanya Technology             | 1        | 0.17%   |
| HMD                          | 1        | 0.17%   |
| Goodram                      | 1        | 0.17%   |
| Goldkey                      | 1        | 0.17%   |
| GLOWAY                       | 1        | 0.17%   |
| GeIL                         | 1        | 0.17%   |
| EVGA                         | 1        | 0.17%   |
| Elpida                       | 1        | 0.17%   |
| CSX                          | 1        | 0.17%   |
| ASint Technology             | 1        | 0.17%   |
| Apacer                       | 1        | 0.17%   |
| AMD                          | 1        | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 20       | 3.17%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 12       | 1.9%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 12       | 1.9%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 9        | 1.43%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 8        | 1.27%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 7        | 1.11%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 6        | 0.95%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 6        | 0.95%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 6        | 0.95%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 5        | 0.79%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 5        | 0.79%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 5        | 0.79%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 5        | 0.79%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s     | 4        | 0.63%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 4        | 0.63%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 4        | 0.63%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s   | 4        | 0.63%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 4        | 0.63%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s    | 4        | 0.63%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s   | 4        | 0.63%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s             | 4        | 0.63%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s             | 4        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 3        | 0.48%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 3        | 0.48%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 3        | 0.48%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 3        | 0.48%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 3        | 0.48%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 3        | 0.48%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 3        | 0.48%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s      | 3        | 0.48%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s    | 3        | 0.48%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 3        | 0.48%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 3        | 0.48%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 3        | 0.48%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 3        | 0.48%   |
| Crucial RAM BLS8G4D26BFSEK.8FD 8GB DIMM DDR4 3000MT/s   | 3        | 0.48%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 3        | 0.48%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s   | 3        | 0.48%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 396      | 72.13%  |
| DDR3    | 115      | 20.95%  |
| Unknown | 15       | 2.73%   |
| DDR2    | 10       | 1.82%   |
| SDRAM   | 7        | 1.28%   |
| DDR5    | 3        | 0.55%   |
| DDR     | 2        | 0.36%   |
| LPDDR4  | 1        | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 528      | 96.88%  |
| SODIMM       | 15       | 2.75%   |
| Row Of Chips | 1        | 0.18%   |
| RIMM         | 1        | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 272      | 46.74%  |
| 16384 | 136      | 23.37%  |
| 4096  | 98       | 16.84%  |
| 32768 | 40       | 6.87%   |
| 2048  | 25       | 4.3%    |
| 1024  | 9        | 1.55%   |
| 512   | 2        | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 104      | 17.54%  |
| 3200    | 69       | 11.64%  |
| 1600    | 61       | 10.29%  |
| 1333    | 44       | 7.42%   |
| 2400    | 43       | 7.25%   |
| 3000    | 25       | 4.22%   |
| 2667    | 22       | 3.71%   |
| 2133    | 21       | 3.54%   |
| 3400    | 20       | 3.37%   |
| 3800    | 17       | 2.87%   |
| 3466    | 17       | 2.87%   |
| 3866    | 15       | 2.53%   |
| 1867    | 13       | 2.19%   |
| 2933    | 11       | 1.85%   |
| 3733    | 10       | 1.69%   |
| 2800    | 9        | 1.52%   |
| 2666    | 8        | 1.35%   |
| 800     | 8        | 1.35%   |
| 1866    | 7        | 1.18%   |
| 667     | 6        | 1.01%   |
| 3666    | 5        | 0.84%   |
| 3534    | 5        | 0.84%   |
| Unknown | 5        | 0.84%   |
| 3333    | 4        | 0.67%   |
| 1800    | 4        | 0.67%   |
| 4400    | 3        | 0.51%   |
| 4000    | 3        | 0.51%   |
| 3100    | 3        | 0.51%   |
| 4800    | 2        | 0.34%   |
| 4266    | 2        | 0.34%   |
| 3533    | 2        | 0.34%   |
| 3334    | 2        | 0.34%   |
| 3266    | 2        | 0.34%   |
| 3151    | 2        | 0.34%   |
| 3066    | 2        | 0.34%   |
| 2733    | 2        | 0.34%   |
| 2472    | 2        | 0.34%   |
| 2134    | 2        | 0.34%   |
| 1066    | 2        | 0.34%   |
| 49926   | 1        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 44       | 31.65%  |
| Brother Industries    | 28       | 20.14%  |
| Canon                 | 22       | 15.83%  |
| Samsung Electronics   | 16       | 11.51%  |
| Seiko Epson           | 13       | 9.35%   |
| Dymo-CoStar           | 4        | 2.88%   |
| Fuji Xerox            | 3        | 2.16%   |
| QinHeng Electronics   | 2        | 1.44%   |
| Xerox                 | 1        | 0.72%   |
| STMicroelectronics    | 1        | 0.72%   |
| Prolific Technology   | 1        | 0.72%   |
| Oki Data              | 1        | 0.72%   |
| Lexmark International | 1        | 0.72%   |
| Kyocera               | 1        | 0.72%   |
| Apple                 | 1        | 0.72%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP Deskjet 3050 J610 series                                | 4        | 2.86%   |
| Samsung SCX-3400 Series                                    | 3        | 2.14%   |
| Brother Printer                                            | 3        | 2.14%   |
| Brother HL-2130 series                                     | 3        | 2.14%   |
| Seiko Epson L396 Series                                    | 2        | 1.43%   |
| Seiko Epson L355 Series                                    | 2        | 1.43%   |
| Seiko Epson ET-2700 Series                                 | 2        | 1.43%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.43%   |
| Samsung M2070 Series                                       | 2        | 1.43%   |
| Samsung M2020 Series                                       | 2        | 1.43%   |
| QinHeng CH340S                                             | 2        | 1.43%   |
| HP LaserJet Professional P 1102w                           | 2        | 1.43%   |
| HP ENVY Photo 6200 series                                  | 2        | 1.43%   |
| HP ENVY 4500 series                                        | 2        | 1.43%   |
| HP DeskJet F4100 Printer series                            | 2        | 1.43%   |
| HP DeskJet 2620 All-in-One Printer                         | 2        | 1.43%   |
| HP Deskjet 1000 J110 series                                | 2        | 1.43%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2        | 1.43%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2        | 1.43%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.43%   |
| Canon PIXMA MG2500 Series                                  | 2        | 1.43%   |
| Brother HL-L3230CDW series                                 | 2        | 1.43%   |
| Brother HL-2270DW Laser Printer                            | 2        | 1.43%   |
| Brother HL-1110 series                                     | 2        | 1.43%   |
| Xerox Phaser 6000B                                         | 1        | 0.71%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.71%   |
| Seiko Epson WF-4830 Series                                 | 1        | 0.71%   |
| Seiko Epson WF-3520 Series                                 | 1        | 0.71%   |
| Seiko Epson L365 Series                                    | 1        | 0.71%   |
| Seiko Epson L3110 Series                                   | 1        | 0.71%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.71%   |
| Seiko Epson ET-3760 Series                                 | 1        | 0.71%   |
| Seiko Epson ET-2800 Series                                 | 1        | 0.71%   |
| Samsung SCX-4200 series                                    | 1        | 0.71%   |
| Samsung ML-2540 Series Laser Printer                       | 1        | 0.71%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1        | 0.71%   |
| Samsung ML-1670 Series                                     | 1        | 0.71%   |
| Samsung ML-1660 Series                                     | 1        | 0.71%   |
| Samsung Composite Device                                   | 1        | 0.71%   |
| Samsung C43x Series                                        | 1        | 0.71%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 66.67%  |
| Seiko Epson     | 2        | 13.33%  |
| Hewlett-Packard | 2        | 13.33%  |
| Mustek Systems  | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30          | 2        | 13.33%  |
| Canon CanoScan LiDE 210                | 2        | 13.33%  |
| Seiko Epson Scanner                    | 1        | 6.67%   |
| Seiko Epson GT-X700 [Perfection 4870]  | 1        | 6.67%   |
| Mustek Systems ScanExpress 1200 UB     | 1        | 6.67%   |
| HP Scanjet 300                         | 1        | 6.67%   |
| HP ScanJet 2400c                       | 1        | 6.67%   |
| Canon CanoScan N650U/N656U             | 1        | 6.67%   |
| Canon CanoScan LiDE 60                 | 1        | 6.67%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 6.67%   |
| Canon CanoScan LiDE 220                | 1        | 6.67%   |
| Canon CanoScan LiDE 200                | 1        | 6.67%   |
| Canon CanoScan LiDE 110                | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 273      | 44.46%  |
| Microdia                      | 47       | 7.65%   |
| Microsoft                     | 35       | 5.7%    |
| Sunplus Innovation Technology | 20       | 3.26%   |
| Generalplus Technology        | 17       | 2.77%   |
| Apple                         | 16       | 2.61%   |
| ARC International             | 15       | 2.44%   |
| Samsung Electronics           | 12       | 1.95%   |
| Realtek Semiconductor         | 12       | 1.95%   |
| Razer USA                     | 11       | 1.79%   |
| Chicony Electronics           | 11       | 1.79%   |
| Z-Star Microelectronics       | 10       | 1.63%   |
| MacroSilicon                  | 10       | 1.63%   |
| Valve Software                | 9        | 1.47%   |
| Jieli Technology              | 9        | 1.47%   |
| KYE Systems (Mouse Systems)   | 8        | 1.3%    |
| Creative Technology           | 8        | 1.3%    |
| Cubeternet                    | 6        | 0.98%   |
| LG Electronics                | 5        | 0.81%   |
| AVerMedia Technologies        | 5        | 0.81%   |
| Huawei Technologies           | 4        | 0.65%   |
| Hewlett-Packard               | 4        | 0.65%   |
| Aveo Technology               | 4        | 0.65%   |
| A4Tech                        | 3        | 0.49%   |
| 2M UVC CAMERA                 | 3        | 0.49%   |
| WCM_USB                       | 2        | 0.33%   |
| Unknown                       | 2        | 0.33%   |
| Trust                         | 2        | 0.33%   |
| Sunplus IT                    | 2        | 0.33%   |
| Novatek Microelectronics      | 2        | 0.33%   |
| Intel                         | 2        | 0.33%   |
| HTC (High Tech Computer)      | 2        | 0.33%   |
| HD WEBCAM                     | 2        | 0.33%   |
| GenesysLogic Technology       | 2        | 0.33%   |
| Genesys Logic                 | 2        | 0.33%   |
| GEMBIRD                       | 2        | 0.33%   |
| Alcor Micro                   | 2        | 0.33%   |
| Acer                          | 2        | 0.33%   |
| YSD-2053--200409              | 1        | 0.16%   |
| Yealink Network Technology    | 1        | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920           | 62       | 10.08%  |
| Logitech Webcam C270                  | 55       | 8.94%   |
| Logitech C922 Pro Stream Webcam       | 22       | 3.58%   |
| Microdia Webcam Vitade AF             | 19       | 3.09%   |
| ARC International Camera              | 15       | 2.44%   |
| Apple iPhone 5/5C/5S/6/SE             | 15       | 2.44%   |
| Microsoft LifeCam HD-3000             | 14       | 2.28%   |
| Logitech BRIO Ultra HD Webcam         | 14       | 2.28%   |
| Logitech HD Webcam C525               | 13       | 2.11%   |
| Generalplus GENERAL WEBCAM            | 13       | 2.11%   |
| Samsung Galaxy A5 (MTP)               | 12       | 1.95%   |
| Logitech HD Webcam C615               | 12       | 1.95%   |
| Valve Software 3D Camera              | 9        | 1.46%   |
| Razer USA Razer Kiyo                  | 9        | 1.46%   |
| Logitech Webcam C310                  | 9        | 1.46%   |
| Jieli USB PHY 2.0                     | 9        | 1.46%   |
| MacroSilicon USB Video                | 8        | 1.3%    |
| Logitech Webcam Pro 9000              | 8        | 1.3%    |
| Logitech Webcam C930e                 | 8        | 1.3%    |
| Logitech Webcam C925e                 | 8        | 1.3%    |
| Logitech Webcam C170                  | 8        | 1.3%    |
| Microsoft LifeCam Cinema              | 7        | 1.14%   |
| Logitech StreamCam                    | 7        | 1.14%   |
| Microdia USB 2.0 Camera               | 6        | 0.98%   |
| Microdia Integrated Camera            | 6        | 0.98%   |
| Logitech C920 PRO HD Webcam           | 6        | 0.98%   |
| Microdia CameraA                      | 5        | 0.81%   |
| Chicony HP High Definition 1MP Webcam | 5        | 0.81%   |
| AVerMedia Live Streamer CAM 313       | 5        | 0.81%   |
| Sunplus USB 2.0 Camera                | 4        | 0.65%   |
| Realtek FULL HD 1080P Webcam          | 4        | 0.65%   |
| Microdia Sonix USB 2.0 Camera         | 4        | 0.65%   |
| Microdia Camera                       | 4        | 0.65%   |
| Logitech Logi Webcam C920e            | 4        | 0.65%   |
| Logitech HD Webcam C910               | 4        | 0.65%   |
| Logitech HD Webcam C510               | 4        | 0.65%   |
| Huawei HD Webcam                      | 4        | 0.65%   |
| Z-Star Venus USB2.0 Camera            | 3        | 0.49%   |
| Sunplus SPCA2281 Web Camera           | 3        | 0.49%   |
| Microsoft MicrosoftÂ LifeCam Studio  | 3        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 28.57%  |
| Validity Sensors      | 1        | 14.29%  |
| LighTuning Technology | 1        | 14.29%  |
| Elan Microelectronics | 1        | 14.29%  |
| DigitalPersona        | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 28.57%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 14.29%  |
| LighTuning Fingerprint Sensor                               | 1        | 14.29%  |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 1        | 14.29%  |
| DigitalPersona Fingerprint Reader                           | 1        | 14.29%  |
| AuthenTec Fingerprint Sensor                                | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 6        | 40%     |
| OmniKey               | 3        | 20%     |
| Realtek Semiconductor | 2        | 13.33%  |
| Alcor Micro           | 2        | 13.33%  |
| Chicony Electronics   | 1        | 6.67%   |
| Advanced Card Systems | 1        | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 26.67%  |
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 13.33%  |
| OmniKey CardMan 3021 / 3121                            | 2        | 13.33%  |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 6.67%   |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 6.67%   |
| OmniKey CardMan 1021                                   | 1        | 6.67%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 6.67%   |
| Alcor Micro Watchdata W 1981                           | 1        | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 6.67%   |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2657     | 80.42%  |
| 1     | 577      | 17.46%  |
| 2     | 59       | 1.79%   |
| 3     | 8        | 0.24%   |
| 7     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |
| 4     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 263      | 37.2%   |
| Graphics card            | 243      | 34.37%  |
| Unassigned class         | 43       | 6.08%   |
| Sound                    | 23       | 3.25%   |
| Multimedia controller    | 20       | 2.83%   |
| Communication controller | 20       | 2.83%   |
| Bluetooth                | 19       | 2.69%   |
| Storage/raid             | 13       | 1.84%   |
| Net/ethernet             | 13       | 1.84%   |
| Chipcard                 | 12       | 1.7%    |
| Network                  | 11       | 1.56%   |
| Fingerprint reader       | 7        | 0.99%   |
| Camera                   | 6        | 0.85%   |
| Storage/ide              | 4        | 0.57%   |
| Card reader              | 4        | 0.57%   |
| Storage/nvme             | 3        | 0.42%   |
| Firewire controller      | 2        | 0.28%   |
| Dvb card                 | 1        | 0.14%   |

