OpenMandriva 4.2 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.2.

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

Total: 2448

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H81M-D2V                    | [aadc1a0c13](https://linux-hardware.org/?probe=aadc1a0c13) | Jan 06, 2025 |
| ASUSTek       | P8Z77-V LX                  | [69679c9a35](https://linux-hardware.org/?probe=69679c9a35) | Dec 31, 2024 |
| Gigabyte      | GA-MA770-DS3                | [d18eb4cf0d](https://linux-hardware.org/?probe=d18eb4cf0d) | Dec 31, 2024 |
| ASRock        | G31M-S                      | [983b928868](https://linux-hardware.org/?probe=983b928868) | Dec 23, 2024 |
| HP            | 304Ah                       | [9c4499ff99](https://linux-hardware.org/?probe=9c4499ff99) | Nov 30, 2024 |
| Gigabyte      | P35-DS3                     | [781f667e83](https://linux-hardware.org/?probe=781f667e83) | Nov 13, 2024 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [c96eaa6d8d](https://linux-hardware.org/?probe=c96eaa6d8d) | Oct 31, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [ecd1036622](https://linux-hardware.org/?probe=ecd1036622) | Oct 01, 2024 |
| Intel         | H61                         | [26ad2a6fdf](https://linux-hardware.org/?probe=26ad2a6fdf) | Sep 10, 2024 |
| ASUSTek       | H81M-PLUS                   | [7c0778ad12](https://linux-hardware.org/?probe=7c0778ad12) | Sep 05, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [00fa1b948c](https://linux-hardware.org/?probe=00fa1b948c) | Sep 04, 2024 |
| Gigabyte      | B75-D3V                     | [8287219a10](https://linux-hardware.org/?probe=8287219a10) | Aug 23, 2024 |
| ASUSTek       | TUF B360-PRO GAMING         | [c6abb7cd5f](https://linux-hardware.org/?probe=c6abb7cd5f) | Aug 21, 2024 |
| Gigabyte      | EP45-UD3R                   | [0f9529c85f](https://linux-hardware.org/?probe=0f9529c85f) | Aug 06, 2024 |
| ASUSTek       | P5KPL-AM                    | [7825be94bd](https://linux-hardware.org/?probe=7825be94bd) | Aug 02, 2024 |
| MSI           | H410M-A PRO                 | [bdfd7784ad](https://linux-hardware.org/?probe=bdfd7784ad) | Jul 22, 2024 |
| Gigabyte      | H81M-D2V                    | [bc079fea91](https://linux-hardware.org/?probe=bc079fea91) | Jul 05, 2024 |
| Dell          | 0HHV7N A00                  | [9313e32d5f](https://linux-hardware.org/?probe=9313e32d5f) | Jul 05, 2024 |
| MSI           | A78M-E45                    | [1a99381c4e](https://linux-hardware.org/?probe=1a99381c4e) | Jul 05, 2024 |
| HP            | 1850                        | [b09fbce140](https://linux-hardware.org/?probe=b09fbce140) | Jun 29, 2024 |
| Gigabyte      | H410M S2H V2                | [bc3d7aa23d](https://linux-hardware.org/?probe=bc3d7aa23d) | Jun 16, 2024 |
| Gigabyte      | F2A68HM-H                   | [569af375ef](https://linux-hardware.org/?probe=569af375ef) | Jun 05, 2024 |
| Intel         | DH67CF AAG10215-201         | [56c76e67fc](https://linux-hardware.org/?probe=56c76e67fc) | Jun 02, 2024 |
| Shuttle       | XS35V3                      | [85715a2083](https://linux-hardware.org/?probe=85715a2083) | May 24, 2024 |
| ASUSTek       | M4A78T-E                    | [2cee8d14ab](https://linux-hardware.org/?probe=2cee8d14ab) | May 06, 2024 |
| Packard Be... | 1.XX                        | [2f25beb1a1](https://linux-hardware.org/?probe=2f25beb1a1) | Apr 12, 2024 |
| ASRock        | G31M-S                      | [d9694d3f33](https://linux-hardware.org/?probe=d9694d3f33) | Apr 12, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [bc0f74721a](https://linux-hardware.org/?probe=bc0f74721a) | Apr 06, 2024 |
| Biostar       | A960D+V2                    | [1b995511d1](https://linux-hardware.org/?probe=1b995511d1) | Apr 06, 2024 |
| Gigabyte      | H61M-S1                     | [d9f5951310](https://linux-hardware.org/?probe=d9f5951310) | Mar 29, 2024 |
| Dell          | 0478VN A00                  | [7300a27a93](https://linux-hardware.org/?probe=7300a27a93) | Mar 29, 2024 |
| Dell          | 0RF705                      | [0af34bb0be](https://linux-hardware.org/?probe=0af34bb0be) | Mar 29, 2024 |
| Dell          | 0T10XW A01                  | [64d0600046](https://linux-hardware.org/?probe=64d0600046) | Mar 26, 2024 |
| ASUSTek       | PRIME A320M-K               | [e631f0ddf7](https://linux-hardware.org/?probe=e631f0ddf7) | Mar 17, 2024 |
| Dell          | 0M5DCD A00                  | [7bb33cf1e5](https://linux-hardware.org/?probe=7bb33cf1e5) | Feb 11, 2024 |
| ECS           | Iris8                       | [6fc3d3a721](https://linux-hardware.org/?probe=6fc3d3a721) | Feb 11, 2024 |
| Gigabyte      | EP45-UD3R                   | [45a5318a64](https://linux-hardware.org/?probe=45a5318a64) | Jan 31, 2024 |
| ECS           | Iris8                       | [91dd8156df](https://linux-hardware.org/?probe=91dd8156df) | Jan 24, 2024 |
| Gigabyte      | B75M-D3H                    | [5edf7a7923](https://linux-hardware.org/?probe=5edf7a7923) | Jan 11, 2024 |
| Acer          | Aspire XC-330               | [1b2d301d07](https://linux-hardware.org/?probe=1b2d301d07) | Dec 29, 2023 |
| Acer          | Aspire XC-704               | [37410da8b1](https://linux-hardware.org/?probe=37410da8b1) | Dec 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [f72b5c344b](https://linux-hardware.org/?probe=f72b5c344b) | Dec 25, 2023 |
| Gigabyte      | H510M H                     | [e21d372813](https://linux-hardware.org/?probe=e21d372813) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-DS2                 | [0c5f882efd](https://linux-hardware.org/?probe=0c5f882efd) | Dec 10, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [26ab67528e](https://linux-hardware.org/?probe=26ab67528e) | Dec 06, 2023 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | [73890cb8c3](https://linux-hardware.org/?probe=73890cb8c3) | Dec 05, 2023 |
| Acer          | Aspire TC-780               | [76cc38fcb0](https://linux-hardware.org/?probe=76cc38fcb0) | Nov 17, 2023 |
| Gigabyte      | B460M D3H                   | [45ff3557a5](https://linux-hardware.org/?probe=45ff3557a5) | Nov 11, 2023 |
| HP            | 2B36                        | [be86be4b09](https://linux-hardware.org/?probe=be86be4b09) | Nov 07, 2023 |
| Biostar       | B250MHC                     | [528c04a30a](https://linux-hardware.org/?probe=528c04a30a) | Nov 02, 2023 |
| AMI           | Intel                       | [c4587092bf](https://linux-hardware.org/?probe=c4587092bf) | Nov 01, 2023 |
| MSI           | GF615M-P33                  | [364be0dfae](https://linux-hardware.org/?probe=364be0dfae) | Oct 24, 2023 |
| Gigabyte      | G41MT-S2                    | [3df6a3e3e4](https://linux-hardware.org/?probe=3df6a3e3e4) | Oct 23, 2023 |
| ASRock        | N68-VGS3 FX                 | [2a39f005cb](https://linux-hardware.org/?probe=2a39f005cb) | Oct 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | [6edb73b1b7](https://linux-hardware.org/?probe=6edb73b1b7) | Oct 11, 2023 |
| Biostar       | A960D+V2                    | [61b27d4d00](https://linux-hardware.org/?probe=61b27d4d00) | Oct 01, 2023 |
| Gigabyte      | P31-ES3G                    | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [6bce0e41d9](https://linux-hardware.org/?probe=6bce0e41d9) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [9c9070da5f](https://linux-hardware.org/?probe=9c9070da5f) | Sep 26, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [16c22d9ead](https://linux-hardware.org/?probe=16c22d9ead) | Sep 25, 2023 |
| Lenovo        | Dory CRB                    | [4c136b6049](https://linux-hardware.org/?probe=4c136b6049) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | [9bacefd984](https://linux-hardware.org/?probe=9bacefd984) | Sep 04, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| ASUSTek       | H110M-D                     | [b0127b4bff](https://linux-hardware.org/?probe=b0127b4bff) | Sep 01, 2023 |
| Dell          | 0HR330                      | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| ASUSTek       | P8Q77-M                     | [8445b944a5](https://linux-hardware.org/?probe=8445b944a5) | Aug 25, 2023 |
| Dell          | 0200DY A00                  | [9b94c2313c](https://linux-hardware.org/?probe=9b94c2313c) | Aug 18, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| Pegatron      | EVANS                       | [323d6a7283](https://linux-hardware.org/?probe=323d6a7283) | Jul 29, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [ac8aab1d26](https://linux-hardware.org/?probe=ac8aab1d26) | Jul 29, 2023 |
| Biostar       | A68MDE                      | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Dell          | 048DY8 A00                  | [66c586dfe4](https://linux-hardware.org/?probe=66c586dfe4) | Jul 11, 2023 |
| Gigabyte      | GA-MA770-ES3                | [9af789d1d2](https://linux-hardware.org/?probe=9af789d1d2) | Jul 10, 2023 |
| ASRock        | N68-VS3 FX                  | [9934022e9b](https://linux-hardware.org/?probe=9934022e9b) | Jul 09, 2023 |
| Gigabyte      | B75-D3V                     | [a05a3f6ca0](https://linux-hardware.org/?probe=a05a3f6ca0) | Jul 01, 2023 |
| Lenovo        | ThinkCentre M90p 5450A26    | [78632c3242](https://linux-hardware.org/?probe=78632c3242) | Jun 26, 2023 |
| ASUSTek       | P5Q-PRO                     | [eb8a9d675b](https://linux-hardware.org/?probe=eb8a9d675b) | Jun 25, 2023 |
| Lenovo        | ThinkCentre M58p 3285A1G    | [d5e4ce2efa](https://linux-hardware.org/?probe=d5e4ce2efa) | Jun 25, 2023 |
| Intel         | D34010WYK H14771-302        | [acda87fcd6](https://linux-hardware.org/?probe=acda87fcd6) | Jun 21, 2023 |
| MSI           | Z97 PC Mate                 | [191a3b02ac](https://linux-hardware.org/?probe=191a3b02ac) | Jun 17, 2023 |
| ASRock        | 960GM-GS3 FX                | [72702690e5](https://linux-hardware.org/?probe=72702690e5) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [d94ba8fb27](https://linux-hardware.org/?probe=d94ba8fb27) | Jun 01, 2023 |
| Foxconn       | 2ABF                        | [ca4691fd95](https://linux-hardware.org/?probe=ca4691fd95) | May 31, 2023 |
| ASUSTek       | P5KPL-SE                    | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [80fa152a82](https://linux-hardware.org/?probe=80fa152a82) | May 17, 2023 |
| BESSTAR Te... | UM350                       | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| Intel         | WADE-8076-ST-WMS            | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| MSI           | A75A-G55                    | [6ecb91213c](https://linux-hardware.org/?probe=6ecb91213c) | May 05, 2023 |
| ASUSTek       | Maximus V GENE              | [1f49086889](https://linux-hardware.org/?probe=1f49086889) | May 03, 2023 |
| ASUSTek       | Z97-P                       | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Gigabyte      | 945GCM-S2L                  | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASUSTek       | PRIME H510M-K               | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [561b87c8b4](https://linux-hardware.org/?probe=561b87c8b4) | Apr 20, 2023 |
| eMachines     | E945GCU                     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| Dell          | 0RF705                      | [32dbb3206b](https://linux-hardware.org/?probe=32dbb3206b) | Apr 16, 2023 |
| ASUSTek       | P5K                         | [00a17a60bf](https://linux-hardware.org/?probe=00a17a60bf) | Apr 09, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [c76171c0a7](https://linux-hardware.org/?probe=c76171c0a7) | Apr 07, 2023 |
| ASRock        | A320M-DVS R4.0              | [c6e30ff3cc](https://linux-hardware.org/?probe=c6e30ff3cc) | Apr 06, 2023 |
| MSI           | B450-A PRO MAX              | [31d10a7e98](https://linux-hardware.org/?probe=31d10a7e98) | Apr 04, 2023 |
| Intel         | DZ87KLT75K AAG74721-304     | [4f97ce0a4b](https://linux-hardware.org/?probe=4f97ce0a4b) | Apr 03, 2023 |
| Medion        | B250H4-EM                   | [f569d44749](https://linux-hardware.org/?probe=f569d44749) | Mar 30, 2023 |
| Gigabyte      | B75M-D3V                    | [d3ae118e3b](https://linux-hardware.org/?probe=d3ae118e3b) | Mar 30, 2023 |
| Lenovo        | ThinkCentre M58p 6137A2U    | [cc740804d7](https://linux-hardware.org/?probe=cc740804d7) | Mar 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3ce94dae13](https://linux-hardware.org/?probe=3ce94dae13) | Mar 25, 2023 |
| Dell          | 0C2KJT A00                  | [54bdc4bbd0](https://linux-hardware.org/?probe=54bdc4bbd0) | Mar 21, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| Unknown       | Unknown                     | [d91eb1923c](https://linux-hardware.org/?probe=d91eb1923c) | Mar 17, 2023 |
| Dell          | 0HN7XN A01                  | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| Gigabyte      | P55-UD3R                    | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| Lenovo        | MAHOBAY                     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| MSI           | H110M PRO-VH PLUS           | [e4e66a8215](https://linux-hardware.org/?probe=e4e66a8215) | Mar 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | [3c4bf3c1bd](https://linux-hardware.org/?probe=3c4bf3c1bd) | Mar 05, 2023 |
| PCWare        | APM-A320G                   | [2bc24b8935](https://linux-hardware.org/?probe=2bc24b8935) | Mar 04, 2023 |
| Gigabyte      | H55M-S2H                    | [196ff8d0dc](https://linux-hardware.org/?probe=196ff8d0dc) | Mar 03, 2023 |
| Dell          | 0KC9NP A00                  | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| Acer          | Aspire X3995                | [eccac5b752](https://linux-hardware.org/?probe=eccac5b752) | Feb 28, 2023 |
| HP            | 3032h                       | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [92ac86c31b](https://linux-hardware.org/?probe=92ac86c31b) | Feb 25, 2023 |
| ASRock        | N68-VGS3 FX                 | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| ASUSTek       | M4N68T-M LE                 | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [4ccd4c2da2](https://linux-hardware.org/?probe=4ccd4c2da2) | Feb 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [2032f6e202](https://linux-hardware.org/?probe=2032f6e202) | Feb 13, 2023 |
| ASUSTek       | P6TD DELUXE                 | [f9cfe6d485](https://linux-hardware.org/?probe=f9cfe6d485) | Feb 13, 2023 |
| ASUSTek       | Z97-K                       | [afaaed1c36](https://linux-hardware.org/?probe=afaaed1c36) | Feb 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [91a070c2aa](https://linux-hardware.org/?probe=91a070c2aa) | Feb 03, 2023 |
| ASUSTek       | P8P67 PRO                   | [49d8a19239](https://linux-hardware.org/?probe=49d8a19239) | Feb 03, 2023 |
| MSI           | A520M-A PRO                 | [f7a88d0dea](https://linux-hardware.org/?probe=f7a88d0dea) | Feb 01, 2023 |
| Intel         | DH77EB AAG39073-304         | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7545ee3eb0](https://linux-hardware.org/?probe=7545ee3eb0) | Jan 22, 2023 |
| Gigabyte      | H61M-D2-B3                  | [e261893ec4](https://linux-hardware.org/?probe=e261893ec4) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [190d9b58b8](https://linux-hardware.org/?probe=190d9b58b8) | Jan 12, 2023 |
| HP            | 83F2                        | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| ASRock        | M3A770DE                    | [952caf04f8](https://linux-hardware.org/?probe=952caf04f8) | Jan 05, 2023 |
| ASUSTek       | M2N68 Plus                  | [12309f8c91](https://linux-hardware.org/?probe=12309f8c91) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | [5ea753453b](https://linux-hardware.org/?probe=5ea753453b) | Jan 03, 2023 |
| HP            | 304Bh                       | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [4ab759533b](https://linux-hardware.org/?probe=4ab759533b) | Dec 25, 2022 |
| Dell          | 0M863N A00                  | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Gigabyte      | EP43-DS3                    | [d0f0cd82f9](https://linux-hardware.org/?probe=d0f0cd82f9) | Dec 22, 2022 |
| ASRock        | M3A770DE                    | [2e6b1f9c2d](https://linux-hardware.org/?probe=2e6b1f9c2d) | Dec 13, 2022 |
| ASUSTek       | H110-PLUS                   | [57e0d3651c](https://linux-hardware.org/?probe=57e0d3651c) | Dec 08, 2022 |
| Gigabyte      | GA-MA770-ES3                | [70c1a43352](https://linux-hardware.org/?probe=70c1a43352) | Dec 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [a4a8d6dcec](https://linux-hardware.org/?probe=a4a8d6dcec) | Dec 03, 2022 |
| Gigabyte      | Z77-D3H                     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| Gigabyte      | G41MT-S2                    | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| Gigabyte      | GA-MA770-DS3                | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3f2ef35b32](https://linux-hardware.org/?probe=3f2ef35b32) | Nov 04, 2022 |
| MSI           | Z97-G43                     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| VS Company    | G31T-M                      | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| HP            | 21B4 A01                    | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Gigabyte      | G41M-ES2L                   | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | [69327d2615](https://linux-hardware.org/?probe=69327d2615) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | H110M-A                     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| HP            | 18E7                        | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| ASUSTek       | P7H55-M LX                  | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| HP            | 1998                        | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| ASUSTek       | B85M-E                      | [07477a078f](https://linux-hardware.org/?probe=07477a078f) | Sep 22, 2022 |
| ASUSTek       | P8P67                       | [a790b35cc1](https://linux-hardware.org/?probe=a790b35cc1) | Sep 17, 2022 |
| Intel         | H61                         | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| HP            | 82F2 A01                    | [f97faeff54](https://linux-hardware.org/?probe=f97faeff54) | Sep 16, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [d88e0026dc](https://linux-hardware.org/?probe=d88e0026dc) | Sep 14, 2022 |
| HP            | 3396                        | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| ASUSTek       | ET2040I                     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [5ba20eb04b](https://linux-hardware.org/?probe=5ba20eb04b) | Sep 01, 2022 |
| Lenovo        | ThinkCentre M58e 7408BA5    | [4384314f98](https://linux-hardware.org/?probe=4384314f98) | Sep 01, 2022 |
| Dell          | 040DDP A00                  | [09ffe165d3](https://linux-hardware.org/?probe=09ffe165d3) | Aug 30, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| HP            | 82B4                        | [e3200ae579](https://linux-hardware.org/?probe=e3200ae579) | Aug 22, 2022 |
| Packard Be... | PT890-8237A                 | [36a4120390](https://linux-hardware.org/?probe=36a4120390) | Aug 20, 2022 |
| Dell          | 0XHGV1 A01                  | [b05fac6451](https://linux-hardware.org/?probe=b05fac6451) | Aug 19, 2022 |
| Dell          | 0GM819                      | [f7745d3d3a](https://linux-hardware.org/?probe=f7745d3d3a) | Aug 16, 2022 |
| Dell          | 0C27VV A01                  | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [32bf5bd8b8](https://linux-hardware.org/?probe=32bf5bd8b8) | Aug 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Intel         | DH61WW AAG23116-204         | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| Gigabyte      | GA-M56S-S3                  | [cb93c45a3a](https://linux-hardware.org/?probe=cb93c45a3a) | Jul 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d85cd905fd](https://linux-hardware.org/?probe=d85cd905fd) | Jul 28, 2022 |
| Dell          | 0P301D A00                  | [48d1ed3099](https://linux-hardware.org/?probe=48d1ed3099) | Jul 28, 2022 |
| HP            | 1495                        | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Dell          | 04GJJT A00                  | [ab730a80b3](https://linux-hardware.org/?probe=ab730a80b3) | Jul 21, 2022 |
| ASUSTek       | P6T WS PRO                  | [4160bc427a](https://linux-hardware.org/?probe=4160bc427a) | Jul 03, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [0924d664a1](https://linux-hardware.org/?probe=0924d664a1) | Jun 30, 2022 |
| ASUSTek       | H110M-A/M.2                 | [98b2b138f4](https://linux-hardware.org/?probe=98b2b138f4) | Jun 20, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [8113862978](https://linux-hardware.org/?probe=8113862978) | Jun 18, 2022 |
| Gigabyte      | H61M-HD2                    | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [2dd49013ff](https://linux-hardware.org/?probe=2dd49013ff) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [17752552c6](https://linux-hardware.org/?probe=17752552c6) | Jun 02, 2022 |
| MSI           | MS-7255                     | [772cf64635](https://linux-hardware.org/?probe=772cf64635) | Jun 02, 2022 |
| ECS           | A58F2P-M4                   | [295c085967](https://linux-hardware.org/?probe=295c085967) | Jun 01, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Intel         | D2500HN AAG81480-500        | [bc39db0484](https://linux-hardware.org/?probe=bc39db0484) | May 24, 2022 |
| MSI           | B150M BAZOOKA               | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| Gigabyte      | Z68XP-UD3                   | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| Gigabyte      | GA-E6010N                   | [679cd1e540](https://linux-hardware.org/?probe=679cd1e540) | May 18, 2022 |
| Gigabyte      | X38-DQ6                     | [653ffc4014](https://linux-hardware.org/?probe=653ffc4014) | May 16, 2022 |
| Dell          | 0HD5W2 A00                  | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| ASUSTek       | CROSSHAIR                   | [39f623cf4d](https://linux-hardware.org/?probe=39f623cf4d) | May 08, 2022 |
| Positivo      | POS-PARS760GCD              | [dfc00dfd71](https://linux-hardware.org/?probe=dfc00dfd71) | May 05, 2022 |
| ASRock        | Z77 Pro3                    | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| Intel         | DG31PR AAE58249-306         | [53f6946eba](https://linux-hardware.org/?probe=53f6946eba) | May 01, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0e266b4987](https://linux-hardware.org/?probe=0e266b4987) | Apr 25, 2022 |
| Foxconn       | 945 7AD Series              | [04346c58f5](https://linux-hardware.org/?probe=04346c58f5) | Apr 23, 2022 |
| Pegatron      | EVANS                       | [118f512619](https://linux-hardware.org/?probe=118f512619) | Apr 21, 2022 |
| HP            | 304Ah                       | [08fbf0f311](https://linux-hardware.org/?probe=08fbf0f311) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| MSI           | Z170A GAMING M5             | [9cabfec30b](https://linux-hardware.org/?probe=9cabfec30b) | Apr 19, 2022 |
| Gigabyte      | G41MT-D3                    | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| Biostar       | H61MLV2                     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | 2215                        | [5acea5fa0a](https://linux-hardware.org/?probe=5acea5fa0a) | Apr 13, 2022 |
| MSI           | Z370-A PRO                  | [94fccb48fd](https://linux-hardware.org/?probe=94fccb48fd) | Apr 10, 2022 |
| Intel         | H81                         | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| ASRock        | Z270 Extreme4               | [526a5a16bd](https://linux-hardware.org/?probe=526a5a16bd) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ECS           | Nettle2                     | [65cedbb00d](https://linux-hardware.org/?probe=65cedbb00d) | Apr 07, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| Unknown       | P4M800CE-8237               | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Dell          | 0CT017                      | [27bdeec11d](https://linux-hardware.org/?probe=27bdeec11d) | Apr 04, 2022 |
| MSI           | X58M                        | [7484dce6ce](https://linux-hardware.org/?probe=7484dce6ce) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| Pegatron      | 2A73h                       | [1aff91c424](https://linux-hardware.org/?probe=1aff91c424) | Apr 02, 2022 |
| Gigabyte      | F2A78M-HD2                  | [1991a3f990](https://linux-hardware.org/?probe=1991a3f990) | Mar 28, 2022 |
| Lenovo        | SDK0E50510 WIN              | [996a5d269c](https://linux-hardware.org/?probe=996a5d269c) | Mar 28, 2022 |
| ASUSTek       | PRIME B350M-A               | [3839ca9677](https://linux-hardware.org/?probe=3839ca9677) | Mar 27, 2022 |
| Gigabyte      | Z87P-D3                     | [3313178485](https://linux-hardware.org/?probe=3313178485) | Mar 25, 2022 |
| ASRock        | X300M-STX                   | [0d7d21ac36](https://linux-hardware.org/?probe=0d7d21ac36) | Mar 24, 2022 |
| Dell          | 0XHGV1 A01                  | [f9fb419fef](https://linux-hardware.org/?probe=f9fb419fef) | Mar 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [91d5c07184](https://linux-hardware.org/?probe=91d5c07184) | Mar 22, 2022 |
| HP            | 81B3                        | [1924290221](https://linux-hardware.org/?probe=1924290221) | Mar 17, 2022 |
| Gigabyte      | GA-A75M-DS2                 | [7e23b31c1b](https://linux-hardware.org/?probe=7e23b31c1b) | Mar 17, 2022 |
| Dell          | 06X1TJ A00                  | [0480518e2e](https://linux-hardware.org/?probe=0480518e2e) | Mar 15, 2022 |
| Gigabyte      | H110M-DS2-CF                | [9cad95edc1](https://linux-hardware.org/?probe=9cad95edc1) | Mar 12, 2022 |
| ASRock        | FM2A55M-VG3                 | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| MSI           | A68HM-E33 V2                | [dfa0722637](https://linux-hardware.org/?probe=dfa0722637) | Mar 12, 2022 |
| Foxconn       | 2A8C                        | [9bcfd85a21](https://linux-hardware.org/?probe=9bcfd85a21) | Mar 07, 2022 |
| Foxconn       | 2A92                        | [d41fb8dda1](https://linux-hardware.org/?probe=d41fb8dda1) | Feb 28, 2022 |
| Acer          | RS880M05                    | [53e88a31a0](https://linux-hardware.org/?probe=53e88a31a0) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| MSI           | H410M PRO                   | [60cb5eed90](https://linux-hardware.org/?probe=60cb5eed90) | Feb 26, 2022 |
| MSI           | KA780G                      | [f6bc0eda57](https://linux-hardware.org/?probe=f6bc0eda57) | Feb 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| ASRock        | Q1900M                      | [428eb82cd0](https://linux-hardware.org/?probe=428eb82cd0) | Feb 23, 2022 |
| MSI           | 970 GAMING                  | [ceceebf84f](https://linux-hardware.org/?probe=ceceebf84f) | Feb 19, 2022 |
| Gigabyte      | Z97-HD3                     | [e9d45ff571](https://linux-hardware.org/?probe=e9d45ff571) | Feb 18, 2022 |
| ASRock        | N68C-S UCC                  | [87de36a11b](https://linux-hardware.org/?probe=87de36a11b) | Feb 17, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [740ff0ffcc](https://linux-hardware.org/?probe=740ff0ffcc) | Feb 17, 2022 |
| ASRock        | N68-GS                      | [06e4bc5238](https://linux-hardware.org/?probe=06e4bc5238) | Feb 16, 2022 |
| Lenovo        | ThinkCentre M58p 7630A38    | [5317cf122d](https://linux-hardware.org/?probe=5317cf122d) | Feb 15, 2022 |
| Huanan        | X79-ZD3 V2.3                | [c20523ee1f](https://linux-hardware.org/?probe=c20523ee1f) | Feb 15, 2022 |
| Dell          | 0TT708 A01                  | [4f615ac094](https://linux-hardware.org/?probe=4f615ac094) | Feb 15, 2022 |
| Dell          | 073MMW A02                  | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| Philco        | 10D                         | [2efb7555a1](https://linux-hardware.org/?probe=2efb7555a1) | Feb 14, 2022 |
| Positivo      | POS-PIH81DI                 | [64c37730f6](https://linux-hardware.org/?probe=64c37730f6) | Feb 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | [1bade168b7](https://linux-hardware.org/?probe=1bade168b7) | Feb 13, 2022 |
| HP            | 1998                        | [6b68df0b96](https://linux-hardware.org/?probe=6b68df0b96) | Feb 12, 2022 |
| Intel         | DG45ID AAE27729-308         | [91f90c2997](https://linux-hardware.org/?probe=91f90c2997) | Feb 12, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [b229af38f0](https://linux-hardware.org/?probe=b229af38f0) | Feb 12, 2022 |
| ASRock        | A320M-DVS R4.0              | [5356027467](https://linux-hardware.org/?probe=5356027467) | Feb 12, 2022 |
| MSI           | G31TM-P21                   | [d9dbe1d02f](https://linux-hardware.org/?probe=d9dbe1d02f) | Feb 11, 2022 |
| MouseCompu... | B75H2-M2                    | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| Dell          | 06NWYK A00                  | [a4654ee182](https://linux-hardware.org/?probe=a4654ee182) | Feb 11, 2022 |
| ASUSTek       | PRIME B450M-A               | [b23b568543](https://linux-hardware.org/?probe=b23b568543) | Feb 08, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [54ebd54640](https://linux-hardware.org/?probe=54ebd54640) | Feb 07, 2022 |
| ASUSTek       | P7H55                       | [1ac17e6259](https://linux-hardware.org/?probe=1ac17e6259) | Feb 07, 2022 |
| Intel         | DG41CN AAE82429-102         | [efb562bd96](https://linux-hardware.org/?probe=efb562bd96) | Feb 07, 2022 |
| ASUSTek       | P9X79                       | [2e55ebbf9f](https://linux-hardware.org/?probe=2e55ebbf9f) | Feb 06, 2022 |
| MSI           | 760GA-P43                   | [6212c219c8](https://linux-hardware.org/?probe=6212c219c8) | Feb 06, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | [f7d707147c](https://linux-hardware.org/?probe=f7d707147c) | Feb 06, 2022 |
| Dell          | 0C27VV A02                  | [f6bb9b0ffd](https://linux-hardware.org/?probe=f6bb9b0ffd) | Feb 06, 2022 |
| HP            | 3397                        | [5e842a74ac](https://linux-hardware.org/?probe=5e842a74ac) | Feb 06, 2022 |
| Dell          | 00V62H A01                  | [a5db2b8436](https://linux-hardware.org/?probe=a5db2b8436) | Feb 06, 2022 |
| Medion        | MS-7800                     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| ASUSTek       | M4N68T                      | [5052fa9dac](https://linux-hardware.org/?probe=5052fa9dac) | Feb 05, 2022 |
| ASUSTek       | H110M-K                     | [10c9ca0b26](https://linux-hardware.org/?probe=10c9ca0b26) | Feb 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [80996b75ff](https://linux-hardware.org/?probe=80996b75ff) | Feb 04, 2022 |
| MSI           | MS-7392                     | [e8f489c1fc](https://linux-hardware.org/?probe=e8f489c1fc) | Feb 04, 2022 |
| Dell          | 09PV3R A00                  | [23a9613450](https://linux-hardware.org/?probe=23a9613450) | Feb 04, 2022 |
| MSI           | Z170A GAMING M5             | [a9613de1e1](https://linux-hardware.org/?probe=a9613de1e1) | Feb 04, 2022 |
| Inventec      | Z CLASS A02                 | [32bbd0c80c](https://linux-hardware.org/?probe=32bbd0c80c) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| Pegatron      | 2AC2                        | [63c15e2642](https://linux-hardware.org/?probe=63c15e2642) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2L                  | [67e8645c04](https://linux-hardware.org/?probe=67e8645c04) | Feb 03, 2022 |
| HP            | 8105                        | [8e49155614](https://linux-hardware.org/?probe=8e49155614) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | H61M-E                      | [6075abc821](https://linux-hardware.org/?probe=6075abc821) | Feb 02, 2022 |
| Unknown       | X99H                        | [29bd27d08f](https://linux-hardware.org/?probe=29bd27d08f) | Feb 02, 2022 |
| Gigabyte      | Z87M-D3H                    | [71569beb05](https://linux-hardware.org/?probe=71569beb05) | Feb 02, 2022 |
| Gigabyte      | F2A55M-DS2                  | [bdb825e963](https://linux-hardware.org/?probe=bdb825e963) | Feb 02, 2022 |
| ASUSTek       | P8H67-M LX                  | [5e92f5c961](https://linux-hardware.org/?probe=5e92f5c961) | Feb 01, 2022 |
| Gigabyte      | A320M-HD2-CF                | [6ad345c1a5](https://linux-hardware.org/?probe=6ad345c1a5) | Feb 01, 2022 |
| Dell          | 0C522T A03                  | [b08503a021](https://linux-hardware.org/?probe=b08503a021) | Feb 01, 2022 |
| Acer          | RS880M05                    | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [5d06ba826f](https://linux-hardware.org/?probe=5d06ba826f) | Jan 31, 2022 |
| Gigabyte      | H81N                        | [9f53b79a7f](https://linux-hardware.org/?probe=9f53b79a7f) | Jan 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [83fbdbf54b](https://linux-hardware.org/?probe=83fbdbf54b) | Jan 29, 2022 |
| ASRock        | 970 Extreme4                | [f024dd97a0](https://linux-hardware.org/?probe=f024dd97a0) | Jan 29, 2022 |
| ASUSTek       | Z170-K                      | [33d0a3b270](https://linux-hardware.org/?probe=33d0a3b270) | Jan 29, 2022 |
| ASRock        | ION3D-HT                    | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| ASUSTek       | P5G41T-M LX PLUS            | [f3a447ef83](https://linux-hardware.org/?probe=f3a447ef83) | Jan 29, 2022 |
| ASUSTek       | P8H67-I PRO                 | [640b7e8450](https://linux-hardware.org/?probe=640b7e8450) | Jan 28, 2022 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [044e014d11](https://linux-hardware.org/?probe=044e014d11) | Jan 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e96d993823](https://linux-hardware.org/?probe=e96d993823) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| Dell          | 0N4YC8 A00                  | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Gigabyte      | GA-780T-D3L                 | [55f310b74b](https://linux-hardware.org/?probe=55f310b74b) | Jan 26, 2022 |
| Gigabyte      | H410M H                     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| Gigabyte      | H57M-USB3                   | [6210f4db07](https://linux-hardware.org/?probe=6210f4db07) | Jan 25, 2022 |
| Inventec      | DQ Class A02                | [71c6779d52](https://linux-hardware.org/?probe=71c6779d52) | Jan 24, 2022 |
| ASRock        | AM1B-ITX                    | [5f089eb5bf](https://linux-hardware.org/?probe=5f089eb5bf) | Jan 24, 2022 |
| MSI           | X58M                        | [cf092b7735](https://linux-hardware.org/?probe=cf092b7735) | Jan 24, 2022 |
| Medion        | MS-7713                     | [e3eb63e81f](https://linux-hardware.org/?probe=e3eb63e81f) | Jan 22, 2022 |
| MSI           | H110M PRO-VD PLUS           | [c51916b063](https://linux-hardware.org/?probe=c51916b063) | Jan 22, 2022 |
| Gigabyte      | B450M S2H                   | [5c8ac15198](https://linux-hardware.org/?probe=5c8ac15198) | Jan 22, 2022 |
| MACHINIST     | B75 PRO V1.0                | [93a2a7dea6](https://linux-hardware.org/?probe=93a2a7dea6) | Jan 22, 2022 |
| Foxconn       | ALOE                        | [a1c7a071c6](https://linux-hardware.org/?probe=a1c7a071c6) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [d2c416e76d](https://linux-hardware.org/?probe=d2c416e76d) | Jan 22, 2022 |
| MSI           | 970 GAMING                  | [963e5b822d](https://linux-hardware.org/?probe=963e5b822d) | Jan 21, 2022 |
| Foxconn       | A76GMV                      | [c25b49803b](https://linux-hardware.org/?probe=c25b49803b) | Jan 21, 2022 |
| ASUSTek       | P8H67-M EVO                 | [515ba182ff](https://linux-hardware.org/?probe=515ba182ff) | Jan 21, 2022 |
| ASUSTek       | M2N-E SLI                   | [bac342fc0f](https://linux-hardware.org/?probe=bac342fc0f) | Jan 21, 2022 |
| ASRock        | N68C-GS FX                  | [7023fd83fc](https://linux-hardware.org/?probe=7023fd83fc) | Jan 21, 2022 |
| HP            | 339A                        | [9a1c8ec615](https://linux-hardware.org/?probe=9a1c8ec615) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Pegatron      | 2AC2                        | [e94ba1d4f2](https://linux-hardware.org/?probe=e94ba1d4f2) | Jan 20, 2022 |
| Acer          | WMCP78M                     | [96428e77d6](https://linux-hardware.org/?probe=96428e77d6) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2a013fff75](https://linux-hardware.org/?probe=2a013fff75) | Jan 20, 2022 |
| Acer          | Aspire TC-390               | [a6a7896071](https://linux-hardware.org/?probe=a6a7896071) | Jan 19, 2022 |
| Dell          | 0F6X5P A00                  | [3caf7fb5f2](https://linux-hardware.org/?probe=3caf7fb5f2) | Jan 19, 2022 |
| HP            | 3029h                       | [21048ac4b2](https://linux-hardware.org/?probe=21048ac4b2) | Jan 19, 2022 |
| Alienware     | 2                           | [e149bdddfa](https://linux-hardware.org/?probe=e149bdddfa) | Jan 18, 2022 |
| ASUSTek       | V-P5G31                     | [ab3ad44c74](https://linux-hardware.org/?probe=ab3ad44c74) | Jan 18, 2022 |
| ASRock        | H61M-HVS                    | [95bbde94a9](https://linux-hardware.org/?probe=95bbde94a9) | Jan 18, 2022 |
| ASUSTek       | P5K-VM                      | [8b7c021ac4](https://linux-hardware.org/?probe=8b7c021ac4) | Jan 17, 2022 |
| MSI           | B450-A PRO MAX              | [5baec4640b](https://linux-hardware.org/?probe=5baec4640b) | Jan 16, 2022 |
| Gigabyte      | 970A-DS3P                   | [d6d4dbbb78](https://linux-hardware.org/?probe=d6d4dbbb78) | Jan 16, 2022 |
| Dell          | 03NVJ6 A02                  | [b59d482466](https://linux-hardware.org/?probe=b59d482466) | Jan 16, 2022 |
| Dell          | 0KC9NP A00                  | [9cc01ad5c0](https://linux-hardware.org/?probe=9cc01ad5c0) | Jan 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | [671180553c](https://linux-hardware.org/?probe=671180553c) | Jan 14, 2022 |
| MSI           | 2A9C                        | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Pegatron      | IPM31G                      | [7ca6a7c129](https://linux-hardware.org/?probe=7ca6a7c129) | Jan 14, 2022 |
| Fujitsu Si... | D2464-B1 S26361-D2464-B1    | [962a3a8bb0](https://linux-hardware.org/?probe=962a3a8bb0) | Jan 14, 2022 |
| MSI           | A320M-A PRO                 | [6b023312e7](https://linux-hardware.org/?probe=6b023312e7) | Jan 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5724c20f52](https://linux-hardware.org/?probe=5724c20f52) | Jan 14, 2022 |
| MSI           | MS-7A66                     | [fcddf8cda4](https://linux-hardware.org/?probe=fcddf8cda4) | Jan 13, 2022 |
| ASUSTek       | PRIME B450M-A               | [ad49cdde74](https://linux-hardware.org/?probe=ad49cdde74) | Jan 13, 2022 |
| ASUSTek       | M2N-MX SE Plus              | [4fae921f3e](https://linux-hardware.org/?probe=4fae921f3e) | Jan 13, 2022 |
| ASUSTek       | A88X-PRO                    | [6dbf0bdf2f](https://linux-hardware.org/?probe=6dbf0bdf2f) | Jan 13, 2022 |
| MSI           | X570-A PRO                  | [cee1b9aefb](https://linux-hardware.org/?probe=cee1b9aefb) | Jan 13, 2022 |
| MSI           | A68HM GRENADE               | [0f44471905](https://linux-hardware.org/?probe=0f44471905) | Jan 10, 2022 |
| Gigabyte      | M52S-S3P                    | [5bdd85e9b5](https://linux-hardware.org/?probe=5bdd85e9b5) | Jan 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| ASUSTek       | P5K-E                       | [f3ebd22f2f](https://linux-hardware.org/?probe=f3ebd22f2f) | Jan 08, 2022 |
| Wortmann      | TERRA_PC                    | [16239fb870](https://linux-hardware.org/?probe=16239fb870) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [30212e6fd6](https://linux-hardware.org/?probe=30212e6fd6) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [f5060a86a8](https://linux-hardware.org/?probe=f5060a86a8) | Jan 07, 2022 |
| Dell          | 0WR7PY A02                  | [6ef0cffa6b](https://linux-hardware.org/?probe=6ef0cffa6b) | Jan 06, 2022 |
| HP            | 8309                        | [3cee70d4fc](https://linux-hardware.org/?probe=3cee70d4fc) | Jan 06, 2022 |
| ASUSTek       | P5GC-MX                     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| Intel         | DG41RQ AAE54511-203         | [2cb2bbbfc6](https://linux-hardware.org/?probe=2cb2bbbfc6) | Jan 06, 2022 |
| MSI           | 760GM-P34                   | [42710e0964](https://linux-hardware.org/?probe=42710e0964) | Jan 06, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7a0e13a7c1](https://linux-hardware.org/?probe=7a0e13a7c1) | Jan 05, 2022 |
| Gateway       | DX4320                      | [64fc897aa2](https://linux-hardware.org/?probe=64fc897aa2) | Jan 04, 2022 |
| MSI           | 880G-E45                    | [b45f683278](https://linux-hardware.org/?probe=b45f683278) | Jan 04, 2022 |
| ASUSTek       | H81T                        | [fb5cc5d8e3](https://linux-hardware.org/?probe=fb5cc5d8e3) | Jan 03, 2022 |
| ASUSTek       | B75M-PLUS                   | [7b813765f3](https://linux-hardware.org/?probe=7b813765f3) | Jan 03, 2022 |
| Dell          | 0F3KHR A00                  | [a1905b9b4a](https://linux-hardware.org/?probe=a1905b9b4a) | Jan 03, 2022 |
| ASUSTek       | CM1735                      | [92165700b1](https://linux-hardware.org/?probe=92165700b1) | Jan 02, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [b1e6f7cd7c](https://linux-hardware.org/?probe=b1e6f7cd7c) | Jan 01, 2022 |
| Dell          | 088DT1 A01                  | [2126000e67](https://linux-hardware.org/?probe=2126000e67) | Jan 01, 2022 |
| ASUSTek       | P5G41T-M LX3                | [2a3dbdc07a](https://linux-hardware.org/?probe=2a3dbdc07a) | Jan 01, 2022 |
| ASUSTek       | PRIME B365M-K               | [428a598475](https://linux-hardware.org/?probe=428a598475) | Dec 31, 2021 |
| HP            | 83E8                        | [c79a0cc45e](https://linux-hardware.org/?probe=c79a0cc45e) | Dec 31, 2021 |
| ASUSTek       | STRIX X99 GAMING            | [f7f99c478d](https://linux-hardware.org/?probe=f7f99c478d) | Dec 31, 2021 |
| ASUSTek       | H110M-A/M.2                 | [667da7e2b7](https://linux-hardware.org/?probe=667da7e2b7) | Dec 31, 2021 |
| Intel         | DP35DP AAD81073-208         | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| ASRock        | 945GCM-S                    | [b089710f53](https://linux-hardware.org/?probe=b089710f53) | Dec 30, 2021 |
| ASUSTek       | PRIME Z690-P WIFI           | [428d5b007d](https://linux-hardware.org/?probe=428d5b007d) | Dec 30, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [b699cbc873](https://linux-hardware.org/?probe=b699cbc873) | Dec 29, 2021 |
| ASRock        | B85M-HDS                    | [8806a9db07](https://linux-hardware.org/?probe=8806a9db07) | Dec 29, 2021 |
| MSI           | B450M PRO-VDH MAX           | [204ffe4516](https://linux-hardware.org/?probe=204ffe4516) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| ASUSTek       | P7H55-M                     | [3550171788](https://linux-hardware.org/?probe=3550171788) | Dec 29, 2021 |
| ASUSTek       | P5QPL-AM                    | [f87be438d3](https://linux-hardware.org/?probe=f87be438d3) | Dec 29, 2021 |
| Biostar       | A960D+V2                    | [447fc7af58](https://linux-hardware.org/?probe=447fc7af58) | Dec 29, 2021 |
| ASRock        | H61MV-ITX                   | [be772b3f4a](https://linux-hardware.org/?probe=be772b3f4a) | Dec 28, 2021 |
| MSI           | B450M PRO-M2 MAX            | [509959fdd1](https://linux-hardware.org/?probe=509959fdd1) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| ASRock        | FM2A68M-DG3+                | [8b9308b9a4](https://linux-hardware.org/?probe=8b9308b9a4) | Dec 28, 2021 |
| MSI           | A68HM GRENADE               | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | MS-7922                     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Intel         | MAHOBAY                     | [e3c3ae36a2](https://linux-hardware.org/?probe=e3c3ae36a2) | Dec 27, 2021 |
| HP            | 0AA0h                       | [8786bc36f4](https://linux-hardware.org/?probe=8786bc36f4) | Dec 27, 2021 |
| ZOTAC         | H55                         | [08e8c1aff2](https://linux-hardware.org/?probe=08e8c1aff2) | Dec 27, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [28aad352f5](https://linux-hardware.org/?probe=28aad352f5) | Dec 26, 2021 |
| Gigabyte      | G31M-S2L                    | [4c00491c87](https://linux-hardware.org/?probe=4c00491c87) | Dec 25, 2021 |
| Gigabyte      | B75M-D3H                    | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| MSI           | 0A90                        | [b08d40599d](https://linux-hardware.org/?probe=b08d40599d) | Dec 23, 2021 |
| Gigabyte      | MJPLNCB-00                  | [fe81720eae](https://linux-hardware.org/?probe=fe81720eae) | Dec 23, 2021 |
| MSI           | A68HM-P33 V2                | [4b36ec9c1a](https://linux-hardware.org/?probe=4b36ec9c1a) | Dec 23, 2021 |
| ASRock        | Q1900M                      | [627eef9622](https://linux-hardware.org/?probe=627eef9622) | Dec 22, 2021 |
| ASUSTek       | A68HM-K                     | [a6fc4a2adb](https://linux-hardware.org/?probe=a6fc4a2adb) | Dec 22, 2021 |
| HP            | 198E                        | [bb9b36a65b](https://linux-hardware.org/?probe=bb9b36a65b) | Dec 22, 2021 |
| HP            | 2B47                        | [64a4b36df8](https://linux-hardware.org/?probe=64a4b36df8) | Dec 22, 2021 |
| Lenovo        | MAHOBAY                     | [2c859e7444](https://linux-hardware.org/?probe=2c859e7444) | Dec 22, 2021 |
| Dell          | 0NW6H5 A00                  | [146165d8d1](https://linux-hardware.org/?probe=146165d8d1) | Dec 22, 2021 |
| Biostar       | A68N-5600E                  | [9ed7856f41](https://linux-hardware.org/?probe=9ed7856f41) | Dec 22, 2021 |
| Gigabyte      | H110M-DS2-CF                | [729cb86592](https://linux-hardware.org/?probe=729cb86592) | Dec 21, 2021 |
| MSI           | Z97-G45 GAMING              | [dd3539200c](https://linux-hardware.org/?probe=dd3539200c) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | [61993c502d](https://linux-hardware.org/?probe=61993c502d) | Dec 19, 2021 |
| ASRock        | G31M-VS                     | [af2a2e4db9](https://linux-hardware.org/?probe=af2a2e4db9) | Dec 19, 2021 |
| Dell          | 0478VN A00                  | [67955910cb](https://linux-hardware.org/?probe=67955910cb) | Dec 18, 2021 |
| ASUSTek       | P5B-MX/WiFi-AP              | [97a556a1b1](https://linux-hardware.org/?probe=97a556a1b1) | Dec 18, 2021 |
| Dell          | 0J468K A00                  | [8233d2b0d6](https://linux-hardware.org/?probe=8233d2b0d6) | Dec 18, 2021 |
| Unknown       | SKYBAY                      | [19694f0921](https://linux-hardware.org/?probe=19694f0921) | Dec 18, 2021 |
| HP            | 0A00h                       | [56585a2839](https://linux-hardware.org/?probe=56585a2839) | Dec 17, 2021 |
| MSI           | G31TM-P35                   | [320ad12871](https://linux-hardware.org/?probe=320ad12871) | Dec 17, 2021 |
| MSI           | 2AE0                        | [f40b9dbbbe](https://linux-hardware.org/?probe=f40b9dbbbe) | Dec 16, 2021 |
| Dell          | 09KPNV A00                  | [52dca5cabc](https://linux-hardware.org/?probe=52dca5cabc) | Dec 16, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | P5GC-MX/1333                | [64d0453982](https://linux-hardware.org/?probe=64d0453982) | Dec 15, 2021 |
| ASUSTek       | H81-GAMER                   | [74658e6a83](https://linux-hardware.org/?probe=74658e6a83) | Dec 15, 2021 |
| ASUSTek       | A_F_K20CE                   | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| ASUSTek       | P8B75-M LX                  | [4575aea29e](https://linux-hardware.org/?probe=4575aea29e) | Dec 14, 2021 |
| Dell          | 0HN7XN A01                  | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| HP            | 18E9                        | [870f4a67a7](https://linux-hardware.org/?probe=870f4a67a7) | Dec 13, 2021 |
| MSI           | A88XM-E35 V2                | [ecd99b833d](https://linux-hardware.org/?probe=ecd99b833d) | Dec 13, 2021 |
| Dell          | 0HJ781                      | [acac78cc8a](https://linux-hardware.org/?probe=acac78cc8a) | Dec 12, 2021 |
| ASRock        | N68-S3 FX                   | [3cbe6d3002](https://linux-hardware.org/?probe=3cbe6d3002) | Dec 12, 2021 |
| Pegatron      | Benicia                     | [500489691f](https://linux-hardware.org/?probe=500489691f) | Dec 11, 2021 |
| ASRock        | 4Core1600-GLAN              | [d533c4790e](https://linux-hardware.org/?probe=d533c4790e) | Dec 10, 2021 |
| HP            | 0A54h                       | [417e076869](https://linux-hardware.org/?probe=417e076869) | Dec 10, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [bc8f942a1a](https://linux-hardware.org/?probe=bc8f942a1a) | Dec 10, 2021 |
| ASUSTek       | Z170M-PLUS                  | [730046deb9](https://linux-hardware.org/?probe=730046deb9) | Dec 09, 2021 |
| Gigabyte      | G41M-ES2L                   | [fe423d9f2d](https://linux-hardware.org/?probe=fe423d9f2d) | Dec 08, 2021 |
| Acer          | M945G                       | [5c72066083](https://linux-hardware.org/?probe=5c72066083) | Dec 08, 2021 |
| Biostar       | NF520-A2 TE                 | [5878187120](https://linux-hardware.org/?probe=5878187120) | Dec 07, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | [e96b1f7f6b](https://linux-hardware.org/?probe=e96b1f7f6b) | Dec 07, 2021 |
| ASUSTek       | Maximus V EXTREME           | [db3905e629](https://linux-hardware.org/?probe=db3905e629) | Dec 07, 2021 |
| OEM           | B75                         | [d6a1e29a32](https://linux-hardware.org/?probe=d6a1e29a32) | Dec 07, 2021 |
| MSI           | H61M-P20                    | [614ffcb196](https://linux-hardware.org/?probe=614ffcb196) | Dec 07, 2021 |
| ASUSTek       | M4A89TD PRO USB3            | [add6c240f9](https://linux-hardware.org/?probe=add6c240f9) | Dec 07, 2021 |
| Huanan        | B85                         | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Gateway       | DT55                        | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| ASRock        | A520M Pro4                  | [5a00aff0fc](https://linux-hardware.org/?probe=5a00aff0fc) | Dec 06, 2021 |
| Unknown       | Phitronics PN73PVS-M        | [f64b92d5b2](https://linux-hardware.org/?probe=f64b92d5b2) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [17c270ac38](https://linux-hardware.org/?probe=17c270ac38) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Gigabyte      | H61M-S2-B3                  | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| Gigabyte      | Z590 VISION G               | [51e33fc095](https://linux-hardware.org/?probe=51e33fc095) | Dec 03, 2021 |
| ASUSTek       | P5K SE                      | [89a5a0d5ac](https://linux-hardware.org/?probe=89a5a0d5ac) | Dec 03, 2021 |
| Gigabyte      | B450M S2H                   | [5df988dd63](https://linux-hardware.org/?probe=5df988dd63) | Dec 03, 2021 |
| ASUSTek       | H81M-K                      | [615600f1dc](https://linux-hardware.org/?probe=615600f1dc) | Dec 03, 2021 |
| ASRock        | M3A770DE                    | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| Gigabyte      | B560 AORUS PRO AX           | [13325b986f](https://linux-hardware.org/?probe=13325b986f) | Dec 01, 2021 |
| Gigabyte      | H81M-DS2                    | [ddcca3f92c](https://linux-hardware.org/?probe=ddcca3f92c) | Dec 01, 2021 |
| MSI           | Z87-GD65 GAMING             | [89046e697d](https://linux-hardware.org/?probe=89046e697d) | Nov 30, 2021 |
| ASUSTek       | M2N                         | [8f674fd086](https://linux-hardware.org/?probe=8f674fd086) | Nov 30, 2021 |
| HP            | 2215                        | [a9a43dfbe0](https://linux-hardware.org/?probe=a9a43dfbe0) | Nov 30, 2021 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | [25d7f6e054](https://linux-hardware.org/?probe=25d7f6e054) | Nov 30, 2021 |
| Gigabyte      | H61M-DS2                    | [59da226d80](https://linux-hardware.org/?probe=59da226d80) | Nov 30, 2021 |
| Intel         | H61                         | [e4a2b68a1b](https://linux-hardware.org/?probe=e4a2b68a1b) | Nov 29, 2021 |
| ASRock        | FM2A78M-DG3+                | [72dfdf487b](https://linux-hardware.org/?probe=72dfdf487b) | Nov 29, 2021 |
| Gigabyte      | B75M-D3H                    | [30820af902](https://linux-hardware.org/?probe=30820af902) | Nov 29, 2021 |
| Lenovo        | H420                        | [46b2e4c604](https://linux-hardware.org/?probe=46b2e4c604) | Nov 29, 2021 |
| ASUSTek       | M3A32-MVP DELUXE            | [2b259d6d47](https://linux-hardware.org/?probe=2b259d6d47) | Nov 27, 2021 |
| HP            | 3047h                       | [4ccf9bec03](https://linux-hardware.org/?probe=4ccf9bec03) | Nov 27, 2021 |
| Dell          | 0M5DCD A00                  | [53441b22f8](https://linux-hardware.org/?probe=53441b22f8) | Nov 27, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [94bbae91a2](https://linux-hardware.org/?probe=94bbae91a2) | Nov 27, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [20e8f6655f](https://linux-hardware.org/?probe=20e8f6655f) | Nov 26, 2021 |
| Dell          | 0WG864                      | [0c33b47ccd](https://linux-hardware.org/?probe=0c33b47ccd) | Nov 26, 2021 |
| ASUSTek       | P7H55-M PRO                 | [5af76e9a00](https://linux-hardware.org/?probe=5af76e9a00) | Nov 25, 2021 |
| Dell          | 048DY8 A01                  | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e8b0ffebd](https://linux-hardware.org/?probe=0e8b0ffebd) | Nov 25, 2021 |
| Gigabyte      | H61M-DS2                    | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| ASUSTek       | M5A97 R2.0                  | [e558eb1777](https://linux-hardware.org/?probe=e558eb1777) | Nov 24, 2021 |
| Toshiba       | STI 012887                  | [f021a9f7a7](https://linux-hardware.org/?probe=f021a9f7a7) | Nov 23, 2021 |
| ASUSTek       | H110M-K                     | [dd276cffaa](https://linux-hardware.org/?probe=dd276cffaa) | Nov 23, 2021 |
| ASRock        | H81M-DGS R2.0               | [138f5b0109](https://linux-hardware.org/?probe=138f5b0109) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8fb57be688](https://linux-hardware.org/?probe=8fb57be688) | Nov 22, 2021 |
| HP            | 1998                        | [258c0fce4a](https://linux-hardware.org/?probe=258c0fce4a) | Nov 22, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [e8c286f335](https://linux-hardware.org/?probe=e8c286f335) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c0960ee402](https://linux-hardware.org/?probe=c0960ee402) | Nov 21, 2021 |
| MSI           | A320M-A PRO MAX             | [4c179204f8](https://linux-hardware.org/?probe=4c179204f8) | Nov 20, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [adc3036124](https://linux-hardware.org/?probe=adc3036124) | Nov 19, 2021 |
| ASUSTek       | Z97M-PLUS                   | [b63110a5f3](https://linux-hardware.org/?probe=b63110a5f3) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | [28722b08e1](https://linux-hardware.org/?probe=28722b08e1) | Nov 19, 2021 |
| Supermicro    | C2SBX Hewlett               | [478694e0e0](https://linux-hardware.org/?probe=478694e0e0) | Nov 19, 2021 |
| ASUSTek       | P5VD2-MX SE                 | [bf34c9fbca](https://linux-hardware.org/?probe=bf34c9fbca) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [1cd779bd1d](https://linux-hardware.org/?probe=1cd779bd1d) | Nov 18, 2021 |
| Gigabyte      | 970A-DS3P                   | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| ASRock        | G31M-GS                     | [63290c282b](https://linux-hardware.org/?probe=63290c282b) | Nov 18, 2021 |
| ASUSTek       | P8Z68-V LX                  | [0415c0798f](https://linux-hardware.org/?probe=0415c0798f) | Nov 18, 2021 |
| Gigabyte      | B75M-D2V                    | [3528c3828b](https://linux-hardware.org/?probe=3528c3828b) | Nov 18, 2021 |
| Biostar       | TH67B                       | [5d655fd2bd](https://linux-hardware.org/?probe=5d655fd2bd) | Nov 17, 2021 |
| Gigabyte      | H310M S2H x.x               | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| HP            | 0A58h                       | [caecb0c75f](https://linux-hardware.org/?probe=caecb0c75f) | Nov 17, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [198dd099be](https://linux-hardware.org/?probe=198dd099be) | Nov 16, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [665b5517a8](https://linux-hardware.org/?probe=665b5517a8) | Nov 16, 2021 |
| HP            | 8054                        | [9f5560c4b7](https://linux-hardware.org/?probe=9f5560c4b7) | Nov 16, 2021 |
| ASUSTek       | H110M-CS/BR                 | [203c43fc12](https://linux-hardware.org/?probe=203c43fc12) | Nov 15, 2021 |
| MSI           | MS-7529                     | [d6f55ff177](https://linux-hardware.org/?probe=d6f55ff177) | Nov 15, 2021 |
| ASUSTek       | P5KPL                       | [6e52b269ee](https://linux-hardware.org/?probe=6e52b269ee) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4b7d36666a](https://linux-hardware.org/?probe=4b7d36666a) | Nov 15, 2021 |
| ASRock        | H470M-HDV                   | [09b482f622](https://linux-hardware.org/?probe=09b482f622) | Nov 15, 2021 |
| Gigabyte      | GA-870A-UD3                 | [58809fa055](https://linux-hardware.org/?probe=58809fa055) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| MSI           | A320M-A PRO MAX             | [09a1713d46](https://linux-hardware.org/?probe=09a1713d46) | Nov 14, 2021 |
| ASRock        | FM2A88X Extreme4+           | [fed47693de](https://linux-hardware.org/?probe=fed47693de) | Nov 14, 2021 |
| MSI           | H81M-P33                    | [76d3a6ff1e](https://linux-hardware.org/?probe=76d3a6ff1e) | Nov 13, 2021 |
| Foxconn       | 2ABF                        | [3fd5da133f](https://linux-hardware.org/?probe=3fd5da133f) | Nov 13, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [cfd9893fd8](https://linux-hardware.org/?probe=cfd9893fd8) | Nov 13, 2021 |
| ASRock        | Z97 Anniversary             | [59ca43cb01](https://linux-hardware.org/?probe=59ca43cb01) | Nov 12, 2021 |
| MSI           | B450M PRO-M2                | [dcf52c1b26](https://linux-hardware.org/?probe=dcf52c1b26) | Nov 12, 2021 |
| Alienware     | 01NYPT A00                  | [995985affc](https://linux-hardware.org/?probe=995985affc) | Nov 12, 2021 |
| HP            | 0A54h                       | [5573fe7b98](https://linux-hardware.org/?probe=5573fe7b98) | Nov 12, 2021 |
| ASUSTek       | P5VD2-MX                    | [2159202a53](https://linux-hardware.org/?probe=2159202a53) | Nov 12, 2021 |
| Gigabyte      | GA-E6010N                   | [7bd45525ce](https://linux-hardware.org/?probe=7bd45525ce) | Nov 12, 2021 |
| MSI           | Z590-A PRO                  | [ed4570b3c1](https://linux-hardware.org/?probe=ed4570b3c1) | Nov 11, 2021 |
| Gigabyte      | P41T-D3P                    | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| Dell          | 0GXM1W A00                  | [98ee61cefe](https://linux-hardware.org/?probe=98ee61cefe) | Nov 11, 2021 |
| Dell          | 0GM819                      | [4f630535ad](https://linux-hardware.org/?probe=4f630535ad) | Nov 11, 2021 |
| Acer          | Aspire X3995                | [351c694ae4](https://linux-hardware.org/?probe=351c694ae4) | Nov 11, 2021 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [468d100cf4](https://linux-hardware.org/?probe=468d100cf4) | Nov 11, 2021 |
| INTELBRAS     | IE-G31TM7                   | [1b854398a1](https://linux-hardware.org/?probe=1b854398a1) | Nov 11, 2021 |
| ASUSTek       | P5G41-M LX                  | [05de777705](https://linux-hardware.org/?probe=05de777705) | Nov 10, 2021 |
| Dell          | 0M5DCD A00                  | [afe9c5ca6f](https://linux-hardware.org/?probe=afe9c5ca6f) | Nov 10, 2021 |
| ASUSTek       | P5P41T-LE                   | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASRock        | A320M-HD                    | [9a8f9d0864](https://linux-hardware.org/?probe=9a8f9d0864) | Nov 10, 2021 |
| MSI           | B450M MORTAR MAX            | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| ASUSTek       | B85-PLUS                    | [c98055d3a7](https://linux-hardware.org/?probe=c98055d3a7) | Nov 09, 2021 |
| ASUSTek       | P5KPL-CM                    | [e89b41000d](https://linux-hardware.org/?probe=e89b41000d) | Nov 09, 2021 |
| ASRock        | N68C-GS FX                  | [ab82eb7e00](https://linux-hardware.org/?probe=ab82eb7e00) | Nov 09, 2021 |
| ASRock        | H61M-HVS                    | [32ffc2e9a5](https://linux-hardware.org/?probe=32ffc2e9a5) | Nov 09, 2021 |
| Lenovo        | ThinkCentre M90p 5450A26    | [53642a2043](https://linux-hardware.org/?probe=53642a2043) | Nov 09, 2021 |
| ASUSTek       | H81M-K                      | [e2c43ab9cf](https://linux-hardware.org/?probe=e2c43ab9cf) | Nov 08, 2021 |
| ASUSTek       | H110M-E/M.2                 | [4abd5bf630](https://linux-hardware.org/?probe=4abd5bf630) | Nov 08, 2021 |
| Gigabyte      | B75M-D2V                    | [49de67bc9e](https://linux-hardware.org/?probe=49de67bc9e) | Nov 08, 2021 |
| MSI           | Z77A-G43                    | [40aaa618d3](https://linux-hardware.org/?probe=40aaa618d3) | Nov 08, 2021 |
| Alienware     | 07W25T A00                  | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| MSI           | X370 GAMING PLUS            | [f04a2bdf6e](https://linux-hardware.org/?probe=f04a2bdf6e) | Nov 07, 2021 |
| ASRock        | B450M Pro4                  | [1fb0114a05](https://linux-hardware.org/?probe=1fb0114a05) | Nov 07, 2021 |
| Biostar       | TA990FXE                    | [09deaa1d44](https://linux-hardware.org/?probe=09deaa1d44) | Nov 06, 2021 |
| Biostar       | H81MHV3                     | [e7d8efbecf](https://linux-hardware.org/?probe=e7d8efbecf) | Nov 04, 2021 |
| Medion        | MS-7621                     | [4a17d1e125](https://linux-hardware.org/?probe=4a17d1e125) | Nov 04, 2021 |
| ASUSTek       | A85XM-A                     | [f28dea1e67](https://linux-hardware.org/?probe=f28dea1e67) | Nov 03, 2021 |
| HP            | 3031h                       | [9803321690](https://linux-hardware.org/?probe=9803321690) | Nov 03, 2021 |
| Acer          | RS740DVF                    | [2828e1ed3e](https://linux-hardware.org/?probe=2828e1ed3e) | Nov 03, 2021 |
| HP            | 82FE 11                     | [948a167989](https://linux-hardware.org/?probe=948a167989) | Nov 03, 2021 |
| MSI           | A320M PRO-VH PLUS           | [7295833004](https://linux-hardware.org/?probe=7295833004) | Nov 03, 2021 |
| MSI           | Z97 GAMING 3                | [75a7ea92de](https://linux-hardware.org/?probe=75a7ea92de) | Nov 03, 2021 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [c8ce4a9635](https://linux-hardware.org/?probe=c8ce4a9635) | Nov 02, 2021 |
| Gigabyte      | H55M-S2                     | [a28dd690ca](https://linux-hardware.org/?probe=a28dd690ca) | Nov 02, 2021 |
| MSI           | B150M MORTAR                | [cc32b13112](https://linux-hardware.org/?probe=cc32b13112) | Nov 02, 2021 |
| ASUSTek       | Z97-C                       | [b061e6ba62](https://linux-hardware.org/?probe=b061e6ba62) | Nov 01, 2021 |
| Gigabyte      | P31-ES3G                    | [11d4cc5eda](https://linux-hardware.org/?probe=11d4cc5eda) | Nov 01, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [7dc6485880](https://linux-hardware.org/?probe=7dc6485880) | Nov 01, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [d935909503](https://linux-hardware.org/?probe=d935909503) | Nov 01, 2021 |
| Gigabyte      | PH67A-UD3-B3                | [91347848ea](https://linux-hardware.org/?probe=91347848ea) | Nov 01, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d0a4db1348](https://linux-hardware.org/?probe=d0a4db1348) | Nov 01, 2021 |
| ASRock        | N68-S                       | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | [24974be67e](https://linux-hardware.org/?probe=24974be67e) | Oct 31, 2021 |
| MSI           | 760GM-P34                   | [1161af8368](https://linux-hardware.org/?probe=1161af8368) | Oct 31, 2021 |
| HP            | 3048h                       | [b62359fcb1](https://linux-hardware.org/?probe=b62359fcb1) | Oct 31, 2021 |
| ASUSTek       | P5G41T-M LE                 | [4e4e73ba37](https://linux-hardware.org/?probe=4e4e73ba37) | Oct 30, 2021 |
| MSI           | H87M-G43                    | [aecd71ac63](https://linux-hardware.org/?probe=aecd71ac63) | Oct 30, 2021 |
| Gigabyte      | B75M-D3H                    | [bb6de8b3e0](https://linux-hardware.org/?probe=bb6de8b3e0) | Oct 30, 2021 |
| MSI           | P55-CD53                    | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| ASUSTek       | H110M-K                     | [7e7d21d8ae](https://linux-hardware.org/?probe=7e7d21d8ae) | Oct 28, 2021 |
| MSI           | Z97M GAMING                 | [3aeeebeb96](https://linux-hardware.org/?probe=3aeeebeb96) | Oct 28, 2021 |
| Foxconn       | 2AB1                        | [d1b1b0530d](https://linux-hardware.org/?probe=d1b1b0530d) | Oct 28, 2021 |
| HP            | 3048h                       | [8473fdedb7](https://linux-hardware.org/?probe=8473fdedb7) | Oct 27, 2021 |
| Dell          | 0XHGV1 A00                  | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [05766074d7](https://linux-hardware.org/?probe=05766074d7) | Oct 26, 2021 |
| ASRock        | 970M Pro3                   | [b42bc6ee49](https://linux-hardware.org/?probe=b42bc6ee49) | Oct 25, 2021 |
| MSI           | H81M-P33                    | [0420edf711](https://linux-hardware.org/?probe=0420edf711) | Oct 25, 2021 |
| ASUSTek       | A_F_K31AN                   | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| ASUSTek       | PRIME B450M-A               | [3b40847ac4](https://linux-hardware.org/?probe=3b40847ac4) | Oct 25, 2021 |
| ASUSTek       | P5Q3                        | [5dcfd80741](https://linux-hardware.org/?probe=5dcfd80741) | Oct 24, 2021 |
| Acer          | FIH57                       | [719b6ffbe5](https://linux-hardware.org/?probe=719b6ffbe5) | Oct 24, 2021 |
| PANSHI        | B85-S1 V1.0                 | [963f2f28d4](https://linux-hardware.org/?probe=963f2f28d4) | Oct 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [780e40d828](https://linux-hardware.org/?probe=780e40d828) | Oct 23, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [879759ba36](https://linux-hardware.org/?probe=879759ba36) | Oct 23, 2021 |
| HP            | 18E7                        | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| MSI           | A75A-G35                    | [7223bfa184](https://linux-hardware.org/?probe=7223bfa184) | Oct 22, 2021 |
| ASRock        | E350M1                      | [84353af140](https://linux-hardware.org/?probe=84353af140) | Oct 21, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [63f68846bb](https://linux-hardware.org/?probe=63f68846bb) | Oct 21, 2021 |
| Gigabyte      | H61M-S2PV                   | [74a6f72f79](https://linux-hardware.org/?probe=74a6f72f79) | Oct 21, 2021 |
| Dell          | 0TP412                      | [61643a7463](https://linux-hardware.org/?probe=61643a7463) | Oct 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a79f5ef1cf](https://linux-hardware.org/?probe=a79f5ef1cf) | Oct 20, 2021 |
| MSI           | H97M-G43                    | [48617be8f2](https://linux-hardware.org/?probe=48617be8f2) | Oct 20, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [96ecc9f1bd](https://linux-hardware.org/?probe=96ecc9f1bd) | Oct 20, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [de600dc6cc](https://linux-hardware.org/?probe=de600dc6cc) | Oct 20, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [6b08158329](https://linux-hardware.org/?probe=6b08158329) | Oct 20, 2021 |
| Dell          | 0T656F A01                  | [7dde642133](https://linux-hardware.org/?probe=7dde642133) | Oct 20, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1276c2e404](https://linux-hardware.org/?probe=1276c2e404) | Oct 20, 2021 |
| ASUSTek       | Basswood                    | [41a11f1678](https://linux-hardware.org/?probe=41a11f1678) | Oct 20, 2021 |
| MSI           | A320M PRO-VH PLUS           | [20613df3d5](https://linux-hardware.org/?probe=20613df3d5) | Oct 19, 2021 |
| HP            | 3032h                       | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| MSI           | H55M-E33                    | [4b6fa6fd54](https://linux-hardware.org/?probe=4b6fa6fd54) | Oct 19, 2021 |
| ASUSTek       | C8HM70-I/HDMI               | [3475f6407e](https://linux-hardware.org/?probe=3475f6407e) | Oct 19, 2021 |
| Gigabyte      | M61PME-S2                   | [7076f55128](https://linux-hardware.org/?probe=7076f55128) | Oct 18, 2021 |
| HP            | 0AA0h                       | [fcd03cf9f8](https://linux-hardware.org/?probe=fcd03cf9f8) | Oct 18, 2021 |
| Intel         | H55                         | [919e9c3fcf](https://linux-hardware.org/?probe=919e9c3fcf) | Oct 17, 2021 |
| Positivo      | POS-EIB75CO POSITIVO        | [73e914eac2](https://linux-hardware.org/?probe=73e914eac2) | Oct 17, 2021 |
| ASUSTek       | PRIME H270-PRO              | [4e41f87995](https://linux-hardware.org/?probe=4e41f87995) | Oct 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| ASUSTek       | P8Z77-V LK                  | [f1b8348661](https://linux-hardware.org/?probe=f1b8348661) | Oct 16, 2021 |
| Gigabyte      | B450M GAMING                | [4e08da267c](https://linux-hardware.org/?probe=4e08da267c) | Oct 16, 2021 |
| ASUSTek       | Z170-A                      | [d3e0e0f937](https://linux-hardware.org/?probe=d3e0e0f937) | Oct 16, 2021 |
| Pegatron      | 2A73h                       | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| HP            | 0B40h                       | [557131b1dd](https://linux-hardware.org/?probe=557131b1dd) | Oct 16, 2021 |
| HP            | 82F2                        | [fef1d213b4](https://linux-hardware.org/?probe=fef1d213b4) | Oct 16, 2021 |
| Dell          | 051FJ8 A02                  | [e89c4e8e1c](https://linux-hardware.org/?probe=e89c4e8e1c) | Oct 16, 2021 |
| Gigabyte      | EP45-UD3R                   | [ee1862fa4f](https://linux-hardware.org/?probe=ee1862fa4f) | Oct 16, 2021 |
| ASRock        | H110M-HG4                   | [8b488cbe13](https://linux-hardware.org/?probe=8b488cbe13) | Oct 15, 2021 |
| MSI           | MAG B550M MORTAR            | [0eaaaa663b](https://linux-hardware.org/?probe=0eaaaa663b) | Oct 15, 2021 |
| Dell          | 0XHGV1 A00                  | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| Philco        | DTC-A55                     | [180d616afd](https://linux-hardware.org/?probe=180d616afd) | Oct 15, 2021 |
| ASUSTek       | P5K PRO                     | [77b7d82f05](https://linux-hardware.org/?probe=77b7d82f05) | Oct 15, 2021 |
| Dell          | 09KPNV A00                  | [ecda4970d8](https://linux-hardware.org/?probe=ecda4970d8) | Oct 15, 2021 |
| ASRock        | H310CM-HDV                  | [4eeb60a709](https://linux-hardware.org/?probe=4eeb60a709) | Oct 14, 2021 |
| ASRock        | B85M Pro4                   | [bf91ce9da1](https://linux-hardware.org/?probe=bf91ce9da1) | Oct 14, 2021 |
| Lenovo        | 3000 IPM31                  | [10c008ff82](https://linux-hardware.org/?probe=10c008ff82) | Oct 14, 2021 |
| Gigabyte      | H61M-D2-B3                  | [1005ec2531](https://linux-hardware.org/?probe=1005ec2531) | Oct 13, 2021 |
| MSI           | 2A78h                       | [65ae698183](https://linux-hardware.org/?probe=65ae698183) | Oct 13, 2021 |
| ASUSTek       | Maximus V GENE              | [ee9c5bf09d](https://linux-hardware.org/?probe=ee9c5bf09d) | Oct 13, 2021 |
| ASRock        | B450M Pro4                  | [5ed3b7e62d](https://linux-hardware.org/?probe=5ed3b7e62d) | Oct 13, 2021 |
| PCWare        | IPX1800E2                   | [509f6b0c67](https://linux-hardware.org/?probe=509f6b0c67) | Oct 13, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [4581d872f7](https://linux-hardware.org/?probe=4581d872f7) | Oct 12, 2021 |
| Gigabyte      | P31-ES3G                    | [473d89ea1a](https://linux-hardware.org/?probe=473d89ea1a) | Oct 12, 2021 |
| Acer          | Aspire X1920                | [e757b4d723](https://linux-hardware.org/?probe=e757b4d723) | Oct 12, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [9261f5cf4c](https://linux-hardware.org/?probe=9261f5cf4c) | Oct 12, 2021 |
| Gigabyte      | P35-S3G                     | [0582e2316b](https://linux-hardware.org/?probe=0582e2316b) | Oct 12, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [f619d93316](https://linux-hardware.org/?probe=f619d93316) | Oct 11, 2021 |
| Gigabyte      | B85M-HD3                    | [47185d16f7](https://linux-hardware.org/?probe=47185d16f7) | Oct 11, 2021 |
| ASUSTek       | P5WDG2-WS                   | [7e4e158b65](https://linux-hardware.org/?probe=7e4e158b65) | Oct 11, 2021 |
| ASUSTek       | PRIME H410M-E               | [b79b71ae45](https://linux-hardware.org/?probe=b79b71ae45) | Oct 11, 2021 |
| MSI           | H170A GAMING PRO            | [2a068afc0c](https://linux-hardware.org/?probe=2a068afc0c) | Oct 11, 2021 |
| ASUSTek       | M4N68T-M LE                 | [a9760c8b4a](https://linux-hardware.org/?probe=a9760c8b4a) | Oct 11, 2021 |
| ASRock        | 960GM-GS3 FX                | [a35ba70698](https://linux-hardware.org/?probe=a35ba70698) | Oct 10, 2021 |
| ASRock        | H81M-HDS                    | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| HP            | 212B                        | [2ae84db0f4](https://linux-hardware.org/?probe=2ae84db0f4) | Oct 10, 2021 |
| MSI           | H110I PRO                   | [33e1bf9b6c](https://linux-hardware.org/?probe=33e1bf9b6c) | Oct 09, 2021 |
| ASUSTek       | CM1730,CM1830               | [f5191dcb50](https://linux-hardware.org/?probe=f5191dcb50) | Oct 09, 2021 |
| MSI           | H310M PRO-VH                | [64f79e5d38](https://linux-hardware.org/?probe=64f79e5d38) | Oct 08, 2021 |
| ASUSTek       | PRIME B360M-A               | [67d172f550](https://linux-hardware.org/?probe=67d172f550) | Oct 08, 2021 |
| Foxconn       | 2AAF                        | [65e2eaccd6](https://linux-hardware.org/?probe=65e2eaccd6) | Oct 08, 2021 |
| HP            | 21D0                        | [4fccb60381](https://linux-hardware.org/?probe=4fccb60381) | Oct 08, 2021 |
| Gigabyte      | H310M S2P                   | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [9156015f5f](https://linux-hardware.org/?probe=9156015f5f) | Oct 08, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [639ef19ce2](https://linux-hardware.org/?probe=639ef19ce2) | Oct 07, 2021 |
| MSI           | B150M MORTAR                | [fd3b108340](https://linux-hardware.org/?probe=fd3b108340) | Oct 07, 2021 |
| HP            | 87D6 SMVB                   | [bf12c5e861](https://linux-hardware.org/?probe=bf12c5e861) | Oct 07, 2021 |
| MSI           | B360M PRO-VH                | [e472116ccb](https://linux-hardware.org/?probe=e472116ccb) | Oct 07, 2021 |
| HP            | 18E9                        | [ff91fbfbe5](https://linux-hardware.org/?probe=ff91fbfbe5) | Oct 07, 2021 |
| MSI           | A68H PC Mate                | [15e5ef3b0e](https://linux-hardware.org/?probe=15e5ef3b0e) | Oct 06, 2021 |
| Gigabyte      | H310M S2H x.x               | [d0b704d0ff](https://linux-hardware.org/?probe=d0b704d0ff) | Oct 06, 2021 |
| Intel         | H61                         | [8ec0d8b02a](https://linux-hardware.org/?probe=8ec0d8b02a) | Oct 06, 2021 |
| ASRock        | A320M-HDV R4.0              | [62b5cc6d0f](https://linux-hardware.org/?probe=62b5cc6d0f) | Oct 06, 2021 |
| Dell          | 0F5C5X A00                  | [519993c906](https://linux-hardware.org/?probe=519993c906) | Oct 05, 2021 |
| ASUSTek       | P5WDG2-WS                   | [1db50356c0](https://linux-hardware.org/?probe=1db50356c0) | Oct 05, 2021 |
| Foxconn       | ALOE                        | [770aad2fe5](https://linux-hardware.org/?probe=770aad2fe5) | Oct 05, 2021 |
| Foxconn       | 2ABF                        | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| Acer          | Aspire M3920                | [515bfbee2e](https://linux-hardware.org/?probe=515bfbee2e) | Oct 04, 2021 |
| HP            | 3047h                       | [15f4144ba7](https://linux-hardware.org/?probe=15f4144ba7) | Oct 03, 2021 |
| Gigabyte      | GA-970A-DS3                 | [97958d9c7e](https://linux-hardware.org/?probe=97958d9c7e) | Oct 03, 2021 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | [57fb928b65](https://linux-hardware.org/?probe=57fb928b65) | Oct 03, 2021 |
| ASUSTek       | P5K                         | [585bfd5e2a](https://linux-hardware.org/?probe=585bfd5e2a) | Oct 02, 2021 |
| ASRock        | G41M-GS3                    | [b0ae6e12c3](https://linux-hardware.org/?probe=b0ae6e12c3) | Oct 02, 2021 |
| ASUSTek       | B85M-G                      | [0d05812341](https://linux-hardware.org/?probe=0d05812341) | Oct 02, 2021 |
| Pegatron      | 2AB5                        | [21453a290c](https://linux-hardware.org/?probe=21453a290c) | Oct 02, 2021 |
| Unknown       | Intel X79                   | [f60e96e04a](https://linux-hardware.org/?probe=f60e96e04a) | Oct 02, 2021 |
| Gigabyte      | X570S AORUS PRO AX          | [6f1d9b0f92](https://linux-hardware.org/?probe=6f1d9b0f92) | Oct 02, 2021 |
| ASUSTek       | P5QL PRO                    | [02d6cacb04](https://linux-hardware.org/?probe=02d6cacb04) | Sep 30, 2021 |
| OEM           | Unknown                     | [a6d82457d0](https://linux-hardware.org/?probe=a6d82457d0) | Sep 30, 2021 |
| Gigabyte      | G1.Sniper A88X-CF           | [8a06541d1e](https://linux-hardware.org/?probe=8a06541d1e) | Sep 29, 2021 |
| Gigabyte      | GA-880GM-D2H                | [574c5e2762](https://linux-hardware.org/?probe=574c5e2762) | Sep 29, 2021 |
| ASUSTek       | H81M-K                      | [42cfc0c15a](https://linux-hardware.org/?probe=42cfc0c15a) | Sep 29, 2021 |
| Gigabyte      | 945G-S3                     | [53e0a8820c](https://linux-hardware.org/?probe=53e0a8820c) | Sep 28, 2021 |
| ASRock        | FM2A55M-HD+                 | [ebdbd50dcb](https://linux-hardware.org/?probe=ebdbd50dcb) | Sep 28, 2021 |
| HP            | 8433 11                     | [4ce1dd7449](https://linux-hardware.org/?probe=4ce1dd7449) | Sep 27, 2021 |
| Shuttle       | XS35V3                      | [11240c3f0f](https://linux-hardware.org/?probe=11240c3f0f) | Sep 26, 2021 |
| ASRock        | Q1900B-ITX                  | [351f306dca](https://linux-hardware.org/?probe=351f306dca) | Sep 26, 2021 |
| MSI           | 790FX-GD70                  | [ba5f2949aa](https://linux-hardware.org/?probe=ba5f2949aa) | Sep 26, 2021 |
| ASRock        | G31M-GS                     | [059439793c](https://linux-hardware.org/?probe=059439793c) | Sep 26, 2021 |
| Gigabyte      | H81M-H                      | [b961548815](https://linux-hardware.org/?probe=b961548815) | Sep 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [469a7b17fa](https://linux-hardware.org/?probe=469a7b17fa) | Sep 25, 2021 |
| ECS           | A55F-M4                     | [627bf10798](https://linux-hardware.org/?probe=627bf10798) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-S2PT               | [c5f2dac6af](https://linux-hardware.org/?probe=c5f2dac6af) | Sep 25, 2021 |
| ASRock        | N68-VS3 FX                  | [b9c8253944](https://linux-hardware.org/?probe=b9c8253944) | Sep 25, 2021 |
| ASUSTek       | P5GV-MX                     | [608cb84fbb](https://linux-hardware.org/?probe=608cb84fbb) | Sep 24, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| Gigabyte      | Z77-DS3H                    | [40468f1cff](https://linux-hardware.org/?probe=40468f1cff) | Sep 23, 2021 |
| Dell          | 0C27VV A01                  | [189c6b9bd1](https://linux-hardware.org/?probe=189c6b9bd1) | Sep 23, 2021 |
| Gigabyte      | H97-HD3                     | [bb4f678d57](https://linux-hardware.org/?probe=bb4f678d57) | Sep 23, 2021 |
| Supermicro    | X7DB8                       | [f235adfa2d](https://linux-hardware.org/?probe=f235adfa2d) | Sep 23, 2021 |
| Gigabyte      | H61M-S1                     | [706bf9f278](https://linux-hardware.org/?probe=706bf9f278) | Sep 22, 2021 |
| Gigabyte      | G31M-S2C                    | [3b43d9b42f](https://linux-hardware.org/?probe=3b43d9b42f) | Sep 22, 2021 |
| ASUSTek       | H81M-R                      | [dfe4dc9048](https://linux-hardware.org/?probe=dfe4dc9048) | Sep 22, 2021 |
| MSI           | A55M-E33                    | [695bc5477d](https://linux-hardware.org/?probe=695bc5477d) | Sep 22, 2021 |
| Gigabyte      | B75M-D3H                    | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| Intel         | D33217GKE G76540-202        | [dfc89bbcfb](https://linux-hardware.org/?probe=dfc89bbcfb) | Sep 22, 2021 |
| HP            | 0AA8h                       | [27262b41aa](https://linux-hardware.org/?probe=27262b41aa) | Sep 22, 2021 |
| ASUSTek       | AM1I-A                      | [0f57a946c9](https://linux-hardware.org/?probe=0f57a946c9) | Sep 22, 2021 |
| Medion        | B460H6-EM                   | [b3850657b1](https://linux-hardware.org/?probe=b3850657b1) | Sep 21, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [79da7d8442](https://linux-hardware.org/?probe=79da7d8442) | Sep 21, 2021 |
| ASRock        | B450M Pro4                  | [7d5a1244bd](https://linux-hardware.org/?probe=7d5a1244bd) | Sep 20, 2021 |
| MSI           | MS-7255                     | [4cdaa67db9](https://linux-hardware.org/?probe=4cdaa67db9) | Sep 19, 2021 |
| ASRock        | G31M-S                      | [987e142046](https://linux-hardware.org/?probe=987e142046) | Sep 19, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [30e4588bc9](https://linux-hardware.org/?probe=30e4588bc9) | Sep 19, 2021 |
| ASUSTek       | P5G41T-M LX3                | [b10cd9626b](https://linux-hardware.org/?probe=b10cd9626b) | Sep 19, 2021 |
| Gigabyte      | H110M-S2H-CF                | [bf9f9e3bb5](https://linux-hardware.org/?probe=bf9f9e3bb5) | Sep 18, 2021 |
| Dell          | 042P49 A02                  | [7ffbfd1e5a](https://linux-hardware.org/?probe=7ffbfd1e5a) | Sep 18, 2021 |
| ASRock        | FM2A58M-HD+ R2.0            | [d4e67ce6aa](https://linux-hardware.org/?probe=d4e67ce6aa) | Sep 18, 2021 |
| ASUSTek       | H110M-E                     | [0458950388](https://linux-hardware.org/?probe=0458950388) | Sep 18, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [a6ad2cfbf4](https://linux-hardware.org/?probe=a6ad2cfbf4) | Sep 18, 2021 |
| Dell          | 07KY25 A01                  | [952d06ed47](https://linux-hardware.org/?probe=952d06ed47) | Sep 17, 2021 |
| AWOW          | AK41                        | [4acb262154](https://linux-hardware.org/?probe=4acb262154) | Sep 17, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [0abd7690c0](https://linux-hardware.org/?probe=0abd7690c0) | Sep 17, 2021 |
| Acer          | RS740DVF                    | [4c36d6b364](https://linux-hardware.org/?probe=4c36d6b364) | Sep 17, 2021 |
| ASUSTek       | P5QL PRO                    | [1630756269](https://linux-hardware.org/?probe=1630756269) | Sep 16, 2021 |
| Dell          | 0773VG A02                  | [5b63f0fc0a](https://linux-hardware.org/?probe=5b63f0fc0a) | Sep 16, 2021 |
| Gigabyte      | B85M-HD3                    | [87c38c92e2](https://linux-hardware.org/?probe=87c38c92e2) | Sep 16, 2021 |
| Acer          | Aspire XC-830               | [ad445dc43a](https://linux-hardware.org/?probe=ad445dc43a) | Sep 15, 2021 |
| ASUSTek       | M4A77TD                     | [b5b48ab672](https://linux-hardware.org/?probe=b5b48ab672) | Sep 15, 2021 |
| Lenovo        | ThinkCentre XXXX 8813AA2    | [3800ed0406](https://linux-hardware.org/?probe=3800ed0406) | Sep 15, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [61c16353ce](https://linux-hardware.org/?probe=61c16353ce) | Sep 14, 2021 |
| ASRock        | B85 Pro4                    | [fd3e875a73](https://linux-hardware.org/?probe=fd3e875a73) | Sep 14, 2021 |
| ASUSTek       | P5GL-MX                     | [e5161b0f36](https://linux-hardware.org/?probe=e5161b0f36) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [526fe68aa2](https://linux-hardware.org/?probe=526fe68aa2) | Sep 13, 2021 |
| ASUSTek       | H81M-R                      | [6a9795f23f](https://linux-hardware.org/?probe=6a9795f23f) | Sep 13, 2021 |
| ASUSTek       | Z170-P                      | [35710b3bec](https://linux-hardware.org/?probe=35710b3bec) | Sep 13, 2021 |
| ECS           | H81H3-M4                    | [5dcb7c25ca](https://linux-hardware.org/?probe=5dcb7c25ca) | Sep 13, 2021 |
| MSI           | H110M PRO-VH PLUS           | [6beea6f903](https://linux-hardware.org/?probe=6beea6f903) | Sep 12, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9127bc0d0a](https://linux-hardware.org/?probe=9127bc0d0a) | Sep 12, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | [01f321a58c](https://linux-hardware.org/?probe=01f321a58c) | Sep 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | [7b4f00a530](https://linux-hardware.org/?probe=7b4f00a530) | Sep 12, 2021 |
| Dell          | 0XCR8D A02                  | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| Acer          | Veriton M4630G V:1.0        | [1fb7ebe327](https://linux-hardware.org/?probe=1fb7ebe327) | Sep 11, 2021 |
| ASUSTek       | M2N68-AM SE2                | [7120a5bd54](https://linux-hardware.org/?probe=7120a5bd54) | Sep 11, 2021 |
| Gigabyte      | P31-ES3G                    | [5d60817fb5](https://linux-hardware.org/?probe=5d60817fb5) | Sep 11, 2021 |
| ASUSTek       | H81M-C                      | [d8d5c45fb5](https://linux-hardware.org/?probe=d8d5c45fb5) | Sep 10, 2021 |
| Intel         | DH61WW AAG23116-206         | [adbe5bb406](https://linux-hardware.org/?probe=adbe5bb406) | Sep 09, 2021 |
| Gigabyte      | X79-UD3                     | [2bcb651e8f](https://linux-hardware.org/?probe=2bcb651e8f) | Sep 09, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [957a8f4549](https://linux-hardware.org/?probe=957a8f4549) | Sep 09, 2021 |
| ASRock        | A75M-HVS                    | [865936d9fc](https://linux-hardware.org/?probe=865936d9fc) | Sep 09, 2021 |
| ASUSTek       | P5KC                        | [3e18f7e5bb](https://linux-hardware.org/?probe=3e18f7e5bb) | Sep 08, 2021 |
| Dell          | 03NVJ6 A01                  | [64435431ed](https://linux-hardware.org/?probe=64435431ed) | Sep 08, 2021 |
| ASUSTek       | P5Q3 DELUXE                 | [c28925fc13](https://linux-hardware.org/?probe=c28925fc13) | Sep 07, 2021 |
| Gigabyte      | GA-970A-D3                  | [42e5ea780a](https://linux-hardware.org/?probe=42e5ea780a) | Sep 06, 2021 |
| Lenovo        | MAHOBAY                     | [768a809221](https://linux-hardware.org/?probe=768a809221) | Sep 06, 2021 |
| MSI           | B450M PRO-M2 MAX            | [c40909a574](https://linux-hardware.org/?probe=c40909a574) | Sep 06, 2021 |
| JW Technol... | JW-A61PM-D3 Ver1.0          | [298389c63c](https://linux-hardware.org/?probe=298389c63c) | Sep 06, 2021 |
| ASRock        | H170 Pro4                   | [9f587f8b51](https://linux-hardware.org/?probe=9f587f8b51) | Sep 06, 2021 |
| Positivo      | POS-EIH61CE SIM             | [fa2919c4c1](https://linux-hardware.org/?probe=fa2919c4c1) | Sep 06, 2021 |
| Fujitsu Si... | MS-7504VP-PV                | [53c7457a1d](https://linux-hardware.org/?probe=53c7457a1d) | Sep 06, 2021 |
| Gigabyte      | B75M-D3H                    | [4b51ce8c11](https://linux-hardware.org/?probe=4b51ce8c11) | Sep 05, 2021 |
| ASRock        | H61M-HVGS                   | [c0aee1b8a4](https://linux-hardware.org/?probe=c0aee1b8a4) | Sep 05, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [64875f65a3](https://linux-hardware.org/?probe=64875f65a3) | Sep 05, 2021 |
| Dell          | 08HPGT A01                  | [eea1f6e691](https://linux-hardware.org/?probe=eea1f6e691) | Sep 04, 2021 |
| HP            | 3029h                       | [9c52ec1eb2](https://linux-hardware.org/?probe=9c52ec1eb2) | Sep 04, 2021 |
| ASUSTek       | H61M-K                      | [541ab60180](https://linux-hardware.org/?probe=541ab60180) | Sep 04, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [c9fd460c11](https://linux-hardware.org/?probe=c9fd460c11) | Sep 04, 2021 |
| HP            | 3047h                       | [1fe7c1728e](https://linux-hardware.org/?probe=1fe7c1728e) | Sep 03, 2021 |
| Gigabyte      | 945P-S3                     | [823bc68829](https://linux-hardware.org/?probe=823bc68829) | Sep 02, 2021 |
| Gigabyte      | GA-MA78G-DS3H               | [c31af0c00d](https://linux-hardware.org/?probe=c31af0c00d) | Sep 02, 2021 |
| MSI           | A75A-G55                    | [eb17249857](https://linux-hardware.org/?probe=eb17249857) | Sep 02, 2021 |
| ASUSTek       | A88XM-A                     | [c5488ab914](https://linux-hardware.org/?probe=c5488ab914) | Sep 02, 2021 |
| Intel         | DG41RQ AAE54511-205         | [d5b6732332](https://linux-hardware.org/?probe=d5b6732332) | Sep 01, 2021 |
| Lenovo        | SHARKBAY NOK                | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| Dell          | 0RY007                      | [52d47340f2](https://linux-hardware.org/?probe=52d47340f2) | Sep 01, 2021 |
| ASUSTek       | Leonite2                    | [c331557969](https://linux-hardware.org/?probe=c331557969) | Sep 01, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c66d74fc61](https://linux-hardware.org/?probe=c66d74fc61) | Sep 01, 2021 |
| IBM           | System Planar Card SIT      | [a6fae29097](https://linux-hardware.org/?probe=a6fae29097) | Sep 01, 2021 |
| ASRock        | M3N78D                      | [731f8a2b99](https://linux-hardware.org/?probe=731f8a2b99) | Aug 31, 2021 |
| ASUSTek       | P5N-MX                      | [f748ee1490](https://linux-hardware.org/?probe=f748ee1490) | Aug 31, 2021 |
| ASRock        | Z77 Pro3                    | [73708f64f4](https://linux-hardware.org/?probe=73708f64f4) | Aug 31, 2021 |
| ASRock        | FM2A68M-DG3+                | [1c39c6a6a7](https://linux-hardware.org/?probe=1c39c6a6a7) | Aug 31, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [2b9238ec6e](https://linux-hardware.org/?probe=2b9238ec6e) | Aug 31, 2021 |
| ASUSTek       | H110M-A                     | [1ce9477a20](https://linux-hardware.org/?probe=1ce9477a20) | Aug 31, 2021 |
| Biostar       | A320MH                      | [ad30d85752](https://linux-hardware.org/?probe=ad30d85752) | Aug 31, 2021 |
| Gigabyte      | J3455N-D3H                  | [24bc89b42a](https://linux-hardware.org/?probe=24bc89b42a) | Aug 31, 2021 |
| Dell          | 0200DY A02                  | [9fd555a4ea](https://linux-hardware.org/?probe=9fd555a4ea) | Aug 31, 2021 |
| ASUSTek       | A8N-E                       | [d2b8571b71](https://linux-hardware.org/?probe=d2b8571b71) | Aug 30, 2021 |
| HP            | 1589                        | [3b97dd5d3e](https://linux-hardware.org/?probe=3b97dd5d3e) | Aug 30, 2021 |
| Intel         | D54250WYK H13922-303        | [33f0fb6241](https://linux-hardware.org/?probe=33f0fb6241) | Aug 30, 2021 |
| MSI           | B450M BAZOOKA PLUS          | [3642f15ab7](https://linux-hardware.org/?probe=3642f15ab7) | Aug 30, 2021 |
| ASUSTek       | Z97-K/USB                   | [071ad478e7](https://linux-hardware.org/?probe=071ad478e7) | Aug 30, 2021 |
| ASRock        | G31M-S                      | [00579ca792](https://linux-hardware.org/?probe=00579ca792) | Aug 30, 2021 |
| Gigabyte      | H97-HD3                     | [010f9676af](https://linux-hardware.org/?probe=010f9676af) | Aug 29, 2021 |
| Foxconn       | 2AA9                        | [22b3d9cf12](https://linux-hardware.org/?probe=22b3d9cf12) | Aug 27, 2021 |
| HP            | 18E4                        | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [9c8cf8ff6a](https://linux-hardware.org/?probe=9c8cf8ff6a) | Aug 27, 2021 |
| Gigabyte      | X58A-UD3R                   | [43ea780a3f](https://linux-hardware.org/?probe=43ea780a3f) | Aug 27, 2021 |
| Gigabyte      | Z77-DS3H                    | [540c64bf79](https://linux-hardware.org/?probe=540c64bf79) | Aug 26, 2021 |
| Gigabyte      | EP45-UD3R                   | [85e6f51a23](https://linux-hardware.org/?probe=85e6f51a23) | Aug 26, 2021 |
| Gigabyte      | B365M DS3H                  | [896c7c1c82](https://linux-hardware.org/?probe=896c7c1c82) | Aug 25, 2021 |
| ASUSTek       | AM1M-A                      | [17f2638893](https://linux-hardware.org/?probe=17f2638893) | Aug 24, 2021 |
| ASUSTek       | Z97-K                       | [0d7edd4742](https://linux-hardware.org/?probe=0d7edd4742) | Aug 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | [fee891d96a](https://linux-hardware.org/?probe=fee891d96a) | Aug 24, 2021 |
| Dell          | 0VHXCD A03                  | [af67059921](https://linux-hardware.org/?probe=af67059921) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [e3c59baa2e](https://linux-hardware.org/?probe=e3c59baa2e) | Aug 23, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [4118ea79d0](https://linux-hardware.org/?probe=4118ea79d0) | Aug 23, 2021 |
| Dell          | 0U7084                      | [9be8fda2ac](https://linux-hardware.org/?probe=9be8fda2ac) | Aug 22, 2021 |
| Gigabyte      | Z170-HD3P-CF                | [8d7072a03f](https://linux-hardware.org/?probe=8d7072a03f) | Aug 22, 2021 |
| ECS           | GeForce6100PM-M2            | [8f16ee8e8c](https://linux-hardware.org/?probe=8f16ee8e8c) | Aug 21, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [3106355282](https://linux-hardware.org/?probe=3106355282) | Aug 21, 2021 |
| Positivo      | POS-PIQ77CL POSITIVO        | [54a0e07f92](https://linux-hardware.org/?probe=54a0e07f92) | Aug 21, 2021 |
| ASUSTek       | P5VD2-VM SE                 | [be5f9f33d4](https://linux-hardware.org/?probe=be5f9f33d4) | Aug 21, 2021 |
| ASUSTek       | M4N68T-M LE                 | [ab3a3225f4](https://linux-hardware.org/?probe=ab3a3225f4) | Aug 21, 2021 |
| MSI           | 760GM-P23                   | [5bff6942d0](https://linux-hardware.org/?probe=5bff6942d0) | Aug 21, 2021 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [443f040d6b](https://linux-hardware.org/?probe=443f040d6b) | Aug 20, 2021 |
| ASUSTek       | P5G41T-M LX                 | [af1cafb6f6](https://linux-hardware.org/?probe=af1cafb6f6) | Aug 20, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [3aceedba10](https://linux-hardware.org/?probe=3aceedba10) | Aug 20, 2021 |
| Dell          | 03NVJ6 A01                  | [79ca915d61](https://linux-hardware.org/?probe=79ca915d61) | Aug 20, 2021 |
| Gigabyte      | H61M-S1                     | [065b6bc3f2](https://linux-hardware.org/?probe=065b6bc3f2) | Aug 19, 2021 |
| Unknown       | Unknown                     | [5df0840f32](https://linux-hardware.org/?probe=5df0840f32) | Aug 19, 2021 |
| Megaware      | OEM                         | [6ac618944e](https://linux-hardware.org/?probe=6ac618944e) | Aug 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [240d31631f](https://linux-hardware.org/?probe=240d31631f) | Aug 19, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1e86163e8a](https://linux-hardware.org/?probe=1e86163e8a) | Aug 18, 2021 |
| HP            | 1998                        | [fe77be8396](https://linux-hardware.org/?probe=fe77be8396) | Aug 18, 2021 |
| Lenovo        | 3176 NOK                    | [ed11430a97](https://linux-hardware.org/?probe=ed11430a97) | Aug 18, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [02cd855bbb](https://linux-hardware.org/?probe=02cd855bbb) | Aug 17, 2021 |
| Dell          | 0D28YY A02                  | [873afd1003](https://linux-hardware.org/?probe=873afd1003) | Aug 17, 2021 |
| MSI           | 2AE0                        | [ee9bcaef5f](https://linux-hardware.org/?probe=ee9bcaef5f) | Aug 17, 2021 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [5c193ba046](https://linux-hardware.org/?probe=5c193ba046) | Aug 17, 2021 |
| Gigabyte      | B250M-Gaming5-CF            | [c34514576a](https://linux-hardware.org/?probe=c34514576a) | Aug 17, 2021 |
| Acer          | H57M01                      | [cd24012069](https://linux-hardware.org/?probe=cd24012069) | Aug 16, 2021 |
| ASUSTek       | PRIME A320M-A               | [e1326f812e](https://linux-hardware.org/?probe=e1326f812e) | Aug 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [26cae4bb7a](https://linux-hardware.org/?probe=26cae4bb7a) | Aug 16, 2021 |
| Gigabyte      | A320M-H-CF                  | [83e29d3882](https://linux-hardware.org/?probe=83e29d3882) | Aug 16, 2021 |
| HP            | 3048h                       | [6c142e320c](https://linux-hardware.org/?probe=6c142e320c) | Aug 15, 2021 |
| Medion        | MS-7800                     | [34b86cf851](https://linux-hardware.org/?probe=34b86cf851) | Aug 15, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [f13ee3f357](https://linux-hardware.org/?probe=f13ee3f357) | Aug 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [4b4a995bad](https://linux-hardware.org/?probe=4b4a995bad) | Aug 15, 2021 |
| Dell          | 0D6H9T A02                  | [38abfc60a9](https://linux-hardware.org/?probe=38abfc60a9) | Aug 14, 2021 |
| MSI           | A68HM-P33 V2                | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [aba8c8d0c4](https://linux-hardware.org/?probe=aba8c8d0c4) | Aug 14, 2021 |
| Acer          | Aspire XC-830               | [1e1a867c2a](https://linux-hardware.org/?probe=1e1a867c2a) | Aug 14, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d3ae7571c2](https://linux-hardware.org/?probe=d3ae7571c2) | Aug 14, 2021 |
| Gigabyte      | M61PME-S2P                  | [46cd16e708](https://linux-hardware.org/?probe=46cd16e708) | Aug 13, 2021 |
| ASUSTek       | Z97-A                       | [5e65f099db](https://linux-hardware.org/?probe=5e65f099db) | Aug 12, 2021 |
| Acer          | Aspire XC-603G              | [fff14b888c](https://linux-hardware.org/?probe=fff14b888c) | Aug 12, 2021 |
| Dell          | 0WR7PY A02                  | [3e13aec14c](https://linux-hardware.org/?probe=3e13aec14c) | Aug 12, 2021 |
| ASRock        | FM2A68M-HD+                 | [45c59105c4](https://linux-hardware.org/?probe=45c59105c4) | Aug 12, 2021 |
| MSI           | B450M-A PRO MAX             | [14e0f895ae](https://linux-hardware.org/?probe=14e0f895ae) | Aug 11, 2021 |
| Dell          | 0C27VV A01                  | [4a0484868d](https://linux-hardware.org/?probe=4a0484868d) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [74f3efe9f6](https://linux-hardware.org/?probe=74f3efe9f6) | Aug 11, 2021 |
| ASUSTek       | G15CX                       | [b38d0b1f72](https://linux-hardware.org/?probe=b38d0b1f72) | Aug 11, 2021 |
| Sony          | VAIO                        | [6a92ab4681](https://linux-hardware.org/?probe=6a92ab4681) | Aug 10, 2021 |
| HP            | 3396                        | [166cc12002](https://linux-hardware.org/?probe=166cc12002) | Aug 09, 2021 |
| ASUSTek       | M5A88-V EVO                 | [66d74f8e04](https://linux-hardware.org/?probe=66d74f8e04) | Aug 09, 2021 |
| Medion        | B360H4-EM V1.0              | [0dd27edc00](https://linux-hardware.org/?probe=0dd27edc00) | Aug 09, 2021 |
| HP            | 21EF                        | [1ab2f81428](https://linux-hardware.org/?probe=1ab2f81428) | Aug 09, 2021 |
| ABIT          | IP35 PRO                    | [da62cd8c37](https://linux-hardware.org/?probe=da62cd8c37) | Aug 08, 2021 |
| Gigabyte      | F2A88XM-D3HP                | [b658f5bf63](https://linux-hardware.org/?probe=b658f5bf63) | Aug 08, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [b8f7efb815](https://linux-hardware.org/?probe=b8f7efb815) | Aug 08, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | [53bb9bce29](https://linux-hardware.org/?probe=53bb9bce29) | Aug 08, 2021 |
| ASRock        | N68-S                       | [5f4575c347](https://linux-hardware.org/?probe=5f4575c347) | Aug 07, 2021 |
| ASRock        | H470M-HDV/M.2               | [8be0194bc4](https://linux-hardware.org/?probe=8be0194bc4) | Aug 07, 2021 |
| PCWare        | APM-A320G                   | [d5283510aa](https://linux-hardware.org/?probe=d5283510aa) | Aug 07, 2021 |
| ASUSTek       | M5A78L-M LX3                | [11621d5877](https://linux-hardware.org/?probe=11621d5877) | Aug 07, 2021 |
| Gigabyte      | H110M-S2H-CF                | [1f0997ab64](https://linux-hardware.org/?probe=1f0997ab64) | Aug 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [08d1639600](https://linux-hardware.org/?probe=08d1639600) | Aug 07, 2021 |
| Toshiba       | Mobile Intel 4 Series/IC... | [3f16c8f90a](https://linux-hardware.org/?probe=3f16c8f90a) | Aug 06, 2021 |
| Foxconn       | 2ABF                        | [5407e26d8d](https://linux-hardware.org/?probe=5407e26d8d) | Aug 05, 2021 |
| ASRock        | A55M-HVS                    | [d5bc156b08](https://linux-hardware.org/?probe=d5bc156b08) | Aug 05, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [0601acbf37](https://linux-hardware.org/?probe=0601acbf37) | Aug 05, 2021 |
| ASUSTek       | M5A97 PLUS                  | [bf5a5f589f](https://linux-hardware.org/?probe=bf5a5f589f) | Aug 05, 2021 |
| Acer          | Aspire XC-603G              | [8cef6da66e](https://linux-hardware.org/?probe=8cef6da66e) | Aug 05, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [c5cf2036f0](https://linux-hardware.org/?probe=c5cf2036f0) | Aug 05, 2021 |
| Gigabyte      | H97M-D3H                    | [d2ec597e7d](https://linux-hardware.org/?probe=d2ec597e7d) | Aug 04, 2021 |
| Gigabyte      | G41MT-S2PT                  | [cf42c809f2](https://linux-hardware.org/?probe=cf42c809f2) | Aug 04, 2021 |
| Intel         | DG31PR AAD97573-205         | [9bda168dc6](https://linux-hardware.org/?probe=9bda168dc6) | Aug 04, 2021 |
| ASUSTek       | M3N78-EMH HDMI              | [6e6ac0f1b7](https://linux-hardware.org/?probe=6e6ac0f1b7) | Aug 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [95bc356b41](https://linux-hardware.org/?probe=95bc356b41) | Aug 03, 2021 |
| Dell          | 0DR845                      | [1714388038](https://linux-hardware.org/?probe=1714388038) | Aug 03, 2021 |
| MSI           | B450 TOMAHAWK               | [ebd09ec38b](https://linux-hardware.org/?probe=ebd09ec38b) | Aug 02, 2021 |
| Dell          | 0GXM1W A00                  | [6aa52c9eb8](https://linux-hardware.org/?probe=6aa52c9eb8) | Aug 02, 2021 |
| HP            | 339A                        | [3226b0e24a](https://linux-hardware.org/?probe=3226b0e24a) | Aug 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [dfdf1e3309](https://linux-hardware.org/?probe=dfdf1e3309) | Aug 02, 2021 |
| HP            | 3047h                       | [18889349d1](https://linux-hardware.org/?probe=18889349d1) | Aug 02, 2021 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [8616a78e1a](https://linux-hardware.org/?probe=8616a78e1a) | Aug 02, 2021 |
| Dell          | 0C2XKD A01                  | [dc0b4aba95](https://linux-hardware.org/?probe=dc0b4aba95) | Aug 02, 2021 |
| MSI           | A55M-E33                    | [be1a7f3ecc](https://linux-hardware.org/?probe=be1a7f3ecc) | Aug 01, 2021 |
| ASUSTek       | P8Z77-V LK                  | [27372d5990](https://linux-hardware.org/?probe=27372d5990) | Aug 01, 2021 |
| ASUSTek       | PRIME H310M-A R2.0          | [682ad8f090](https://linux-hardware.org/?probe=682ad8f090) | Aug 01, 2021 |
| ASRock        | G31M-VS2                    | [ffde05f551](https://linux-hardware.org/?probe=ffde05f551) | Aug 01, 2021 |
| ASRock        | H81M-HDS                    | [f6d31fab90](https://linux-hardware.org/?probe=f6d31fab90) | Aug 01, 2021 |
| Unknown       | Phitronics N68C-M           | [cfd40add6d](https://linux-hardware.org/?probe=cfd40add6d) | Jul 31, 2021 |
| PCWare        | IPX4105G Pro                | [97a4fe1f36](https://linux-hardware.org/?probe=97a4fe1f36) | Jul 31, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [b348c48f96](https://linux-hardware.org/?probe=b348c48f96) | Jul 31, 2021 |
| Gigabyte      | B450M S2H                   | [0401734340](https://linux-hardware.org/?probe=0401734340) | Jul 31, 2021 |
| ASRock        | H570M Pro4                  | [d90b21c903](https://linux-hardware.org/?probe=d90b21c903) | Jul 30, 2021 |
| HP            | 8169                        | [52b2e59c3e](https://linux-hardware.org/?probe=52b2e59c3e) | Jul 30, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1cf978f1d9](https://linux-hardware.org/?probe=1cf978f1d9) | Jul 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| ASUSTek       | H81M-PLUS                   | [02f7a21c31](https://linux-hardware.org/?probe=02f7a21c31) | Jul 29, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [1aebb2e2f7](https://linux-hardware.org/?probe=1aebb2e2f7) | Jul 29, 2021 |
| ASRock        | P67 Extreme6                | [d14c8cf475](https://linux-hardware.org/?probe=d14c8cf475) | Jul 29, 2021 |
| ASRock        | FM2A55M-HD+ R2.0            | [f4587a4a09](https://linux-hardware.org/?probe=f4587a4a09) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c9a8b08abb](https://linux-hardware.org/?probe=c9a8b08abb) | Jul 29, 2021 |
| Intel         | DP67DE AAG10217-300         | [e5f06ddd1f](https://linux-hardware.org/?probe=e5f06ddd1f) | Jul 29, 2021 |
| Dell          | 0WG864                      | [2e28996126](https://linux-hardware.org/?probe=2e28996126) | Jul 28, 2021 |
| Shuttle       | FL10J                       | [0f9fb196fb](https://linux-hardware.org/?probe=0f9fb196fb) | Jul 27, 2021 |
| Foxconn       | 2AAF                        | [9eb5763b8d](https://linux-hardware.org/?probe=9eb5763b8d) | Jul 27, 2021 |
| Acer          | Aspire XC-705               | [381ff0cfb4](https://linux-hardware.org/?probe=381ff0cfb4) | Jul 26, 2021 |
| ASRock        | N68-S3 UCC                  | [81310aad54](https://linux-hardware.org/?probe=81310aad54) | Jul 26, 2021 |
| Gigabyte      | B75M-D3H                    | [3beb3704cf](https://linux-hardware.org/?probe=3beb3704cf) | Jul 25, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [deeb6b1a2f](https://linux-hardware.org/?probe=deeb6b1a2f) | Jul 25, 2021 |
| ASUSTek       | PRIME H410M-E               | [cae2419e98](https://linux-hardware.org/?probe=cae2419e98) | Jul 25, 2021 |
| MSI           | H110M PRO-VH PLUS           | [bbc29a99b7](https://linux-hardware.org/?probe=bbc29a99b7) | Jul 24, 2021 |
| Koloe         | X58                         | [8412204eaf](https://linux-hardware.org/?probe=8412204eaf) | Jul 24, 2021 |
| HP            | 1850                        | [76e386707a](https://linux-hardware.org/?probe=76e386707a) | Jul 24, 2021 |
| Lanix         | ChiefRiver                  | [749fc3ef84](https://linux-hardware.org/?probe=749fc3ef84) | Jul 24, 2021 |
| Dell          | 0C2KJT A00                  | [2187b5051a](https://linux-hardware.org/?probe=2187b5051a) | Jul 24, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [a19ff7fb6a](https://linux-hardware.org/?probe=a19ff7fb6a) | Jul 23, 2021 |
| MSI           | NF750-G55                   | [9fc0813ddd](https://linux-hardware.org/?probe=9fc0813ddd) | Jul 23, 2021 |
| ASRock        | FM2A75M-DGS                 | [3b7b9e608f](https://linux-hardware.org/?probe=3b7b9e608f) | Jul 23, 2021 |
| Gigabyte      | G41MT-S2PT                  | [7e37603df2](https://linux-hardware.org/?probe=7e37603df2) | Jul 23, 2021 |
| Acer          | Veriton X680G               | [3b8774337b](https://linux-hardware.org/?probe=3b8774337b) | Jul 23, 2021 |
| Gigabyte      | H61M-DS2                    | [fec68f6675](https://linux-hardware.org/?probe=fec68f6675) | Jul 23, 2021 |
| Gigabyte      | B360M D3H-CF                | [d836ee6421](https://linux-hardware.org/?probe=d836ee6421) | Jul 22, 2021 |
| Dell          | 0GDG8Y A00                  | [d56411950c](https://linux-hardware.org/?probe=d56411950c) | Jul 22, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [f26bbc82ce](https://linux-hardware.org/?probe=f26bbc82ce) | Jul 22, 2021 |
| Dell          | 0C27VV A01                  | [99b906c497](https://linux-hardware.org/?probe=99b906c497) | Jul 21, 2021 |
| Gigabyte      | B460M DS3H                  | [f51701bc3a](https://linux-hardware.org/?probe=f51701bc3a) | Jul 21, 2021 |
| Dell          | 0FM586                      | [0282db3729](https://linux-hardware.org/?probe=0282db3729) | Jul 21, 2021 |
| MSI           | B450I GAMING PLUS AC        | [04bf0287f0](https://linux-hardware.org/?probe=04bf0287f0) | Jul 21, 2021 |
| MSI           | MS-7309                     | [9be4d2f6ee](https://linux-hardware.org/?probe=9be4d2f6ee) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K               | [62a0cf7f70](https://linux-hardware.org/?probe=62a0cf7f70) | Jul 21, 2021 |
| Dell          | 0GH911                      | [2aa93c89cd](https://linux-hardware.org/?probe=2aa93c89cd) | Jul 21, 2021 |
| HP            | 3646h                       | [fa8c5e24d9](https://linux-hardware.org/?probe=fa8c5e24d9) | Jul 21, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [04f3b034dd](https://linux-hardware.org/?probe=04f3b034dd) | Jul 21, 2021 |
| HP            | 8719                        | [d6615d50f8](https://linux-hardware.org/?probe=d6615d50f8) | Jul 20, 2021 |
| MSI           | H110M PRO-VH PLUS           | [24899222b9](https://linux-hardware.org/?probe=24899222b9) | Jul 20, 2021 |
| Dell          | 0VHWTR A01                  | [5116710fe0](https://linux-hardware.org/?probe=5116710fe0) | Jul 20, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [be19556b36](https://linux-hardware.org/?probe=be19556b36) | Jul 20, 2021 |
| PCWare        | IPMH61R1                    | [16cb1b8b48](https://linux-hardware.org/?probe=16cb1b8b48) | Jul 20, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [01c4a85174](https://linux-hardware.org/?probe=01c4a85174) | Jul 20, 2021 |
| Unknown       | Unknown                     | [8cfcc66d8c](https://linux-hardware.org/?probe=8cfcc66d8c) | Jul 20, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| HP            | 1906                        | [6cd7c6ec7f](https://linux-hardware.org/?probe=6cd7c6ec7f) | Jul 20, 2021 |
| Biostar       | A10N-8800E                  | [aae6a8bcb2](https://linux-hardware.org/?probe=aae6a8bcb2) | Jul 20, 2021 |
| Gigabyte      | H61M-DS2                    | [a6a70ffe29](https://linux-hardware.org/?probe=a6a70ffe29) | Jul 20, 2021 |
| ASUSTek       | B75M-A                      | [ff50f031ed](https://linux-hardware.org/?probe=ff50f031ed) | Jul 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Intel         | DH55HC AAE70933-505         | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| Dell          | 02YRK5 A02                  | [765fb31ee4](https://linux-hardware.org/?probe=765fb31ee4) | Jul 19, 2021 |
| HP            | 83E8                        | [f378108dc3](https://linux-hardware.org/?probe=f378108dc3) | Jul 19, 2021 |
| ASUSTek       | M4A78L-M                    | [fce0d2a812](https://linux-hardware.org/?probe=fce0d2a812) | Jul 19, 2021 |
| ASUSTek       | PRIME Z390-P                | [eb20131cd9](https://linux-hardware.org/?probe=eb20131cd9) | Jul 19, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0b80ffedf6](https://linux-hardware.org/?probe=0b80ffedf6) | Jul 19, 2021 |
| Gigabyte      | X38-DQ6                     | [182c8a0c3d](https://linux-hardware.org/?probe=182c8a0c3d) | Jul 19, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | [214c59a169](https://linux-hardware.org/?probe=214c59a169) | Jul 19, 2021 |
| Acer          | Veriton M290                | [933b393728](https://linux-hardware.org/?probe=933b393728) | Jul 19, 2021 |
| ASUSTek       | Z97-A                       | [b8edd50f3b](https://linux-hardware.org/?probe=b8edd50f3b) | Jul 19, 2021 |
| ASUSTek       | Rampage III GENE            | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Intel         | H61                         | [33ac153fc0](https://linux-hardware.org/?probe=33ac153fc0) | Jul 18, 2021 |
| Positivo      | POS-EIBTPDC                 | [8d82a3932b](https://linux-hardware.org/?probe=8d82a3932b) | Jul 18, 2021 |
| ASRock        | 880GM-LE FX                 | [19b241a883](https://linux-hardware.org/?probe=19b241a883) | Jul 18, 2021 |
| MSI           | A88XM-E45 V2                | [96f8daecd4](https://linux-hardware.org/?probe=96f8daecd4) | Jul 18, 2021 |
| Biostar       | Hi-Fi A70U3P                | [b54825264f](https://linux-hardware.org/?probe=b54825264f) | Jul 18, 2021 |
| ASUSTek       | A88XM-PLUS                  | [4f9f3cbb83](https://linux-hardware.org/?probe=4f9f3cbb83) | Jul 18, 2021 |
| ASUSTek       | P5GC-MX/1333                | [ad468facf2](https://linux-hardware.org/?probe=ad468facf2) | Jul 18, 2021 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [b413b6f067](https://linux-hardware.org/?probe=b413b6f067) | Jul 18, 2021 |
| ASUSTek       | H81M-K                      | [07e568874b](https://linux-hardware.org/?probe=07e568874b) | Jul 18, 2021 |
| MSI           | Z97-G55 SLI                 | [066f6ad76f](https://linux-hardware.org/?probe=066f6ad76f) | Jul 18, 2021 |
| HP            | 339A                        | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| Dell          | 0M863N A00                  | [3d05e8db4a](https://linux-hardware.org/?probe=3d05e8db4a) | Jul 18, 2021 |
| Gigabyte      | H55M-UD2H                   | [7b9ae97fe8](https://linux-hardware.org/?probe=7b9ae97fe8) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [d2f11dc136](https://linux-hardware.org/?probe=d2f11dc136) | Jul 18, 2021 |
| Lenovo        | ThinkCentre M90p 5536B2G    | [4486d669b3](https://linux-hardware.org/?probe=4486d669b3) | Jul 18, 2021 |
| ASUSTek       | PRIME B460I-PLUS            | [626b3cccb3](https://linux-hardware.org/?probe=626b3cccb3) | Jul 18, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [3b293f18b7](https://linux-hardware.org/?probe=3b293f18b7) | Jul 18, 2021 |
| MSI           | Z97 GAMING 3                | [fb4d52b3b2](https://linux-hardware.org/?probe=fb4d52b3b2) | Jul 18, 2021 |
| Pegatron      | 2AB6                        | [b790271fac](https://linux-hardware.org/?probe=b790271fac) | Jul 18, 2021 |
| ASUSTek       | B75M-PLUS                   | [3c8fe5e284](https://linux-hardware.org/?probe=3c8fe5e284) | Jul 18, 2021 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [e89e0336cb](https://linux-hardware.org/?probe=e89e0336cb) | Jul 17, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [715cf27cd7](https://linux-hardware.org/?probe=715cf27cd7) | Jul 17, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.2/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002      | 2251     | 95.5%   |
| 5.11.12-desktop-1omv4002      | 92       | 3.9%    |
| 5.11.0-desktop-clang-1omv4002 | 5        | 0.21%   |
| 5.10.13-desktop-1omv4002      | 4        | 0.17%   |
| 5.8.13-desktop-clang-1omv4002 | 1        | 0.04%   |
| 5.10.9-desktop-1omv4002       | 1        | 0.04%   |
| 5.10.7-desktop-1omv4002       | 1        | 0.04%   |
| 5.10.3-desktop-2omv4002       | 1        | 0.04%   |
| 5.10.15-desktop-1omv4002      | 1        | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.14 | 2251     | 95.5%   |
| 5.11.12 | 92       | 3.9%    |
| 5.11.0  | 5        | 0.21%   |
| 5.10.13 | 4        | 0.17%   |
| 5.8.13  | 1        | 0.04%   |
| 5.10.9  | 1        | 0.04%   |
| 5.10.7  | 1        | 0.04%   |
| 5.10.3  | 1        | 0.04%   |
| 5.10.15 | 1        | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2259     | 95.84%  |
| 5.11    | 97       | 4.12%   |
| 5.8     | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2320     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 2316     | 99.78%  |
| LXQt     | 3        | 0.13%   |
| KDE      | 1        | 0.04%   |
| Cinnamon | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2303     | 99.27%  |
| Wayland | 17       | 0.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 2320     | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 1188     | 50.55%  |
| ru_RU | 187      | 7.96%   |
| de_DE | 174      | 7.4%    |
| fr_FR | 157      | 6.68%   |
| pt_BR | 107      | 4.55%   |
| pl_PL | 92       | 3.91%   |
| it_IT | 69       | 2.94%   |
| es_ES | 64       | 2.72%   |
| en_GB | 28       | 1.19%   |
| es_MX | 27       | 1.15%   |
| cs_CZ | 27       | 1.15%   |
| hu_HU | 24       | 1.02%   |
| es_AR | 21       | 0.89%   |
| de_AT | 17       | 0.72%   |
| en_AU | 15       | 0.64%   |
| nl_NL | 14       | 0.6%    |
| ru_UA | 10       | 0.43%   |
| fr_CA | 10       | 0.43%   |
| de_CH | 9        | 0.38%   |
| fr_BE | 8        | 0.34%   |
| en_HK | 8        | 0.34%   |
| da_DK | 8        | 0.34%   |
| ro_RO | 7        | 0.3%    |
| pt_PT | 6        | 0.26%   |
| es_VE | 6        | 0.26%   |
| en_CA | 6        | 0.26%   |
| nl_BE | 5        | 0.21%   |
| es_CO | 5        | 0.21%   |
| es_CL | 5        | 0.21%   |
| en_IL | 5        | 0.21%   |
| en_IN | 4        | 0.17%   |
| it_CH | 3        | 0.13%   |
| es_SV | 3        | 0.13%   |
| es_EC | 3        | 0.13%   |
| en_ZA | 3        | 0.13%   |
| uk_UA | 2        | 0.09%   |
| nb_NO | 2        | 0.09%   |
| fr_CH | 2        | 0.09%   |
| es_PE | 2        | 0.09%   |
| es_DO | 2        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1533     | 65.88%  |
| EFI  | 794      | 34.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 1931     | 81.34%  |
| Ext4     | 417      | 17.57%  |
| Btrfs    | 16       | 0.67%   |
| Ext3     | 4        | 0.17%   |
| Jfs      | 2        | 0.08%   |
| Xfs      | 1        | 0.04%   |
| Reiserfs | 1        | 0.04%   |
| F2fs     | 1        | 0.04%   |
| Ext2     | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1230     | 52.63%  |
| MBR     | 1095     | 46.85%  |
| Unknown | 12       | 0.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1482     | 63.04%  |
| No        | 869      | 36.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1264     | 54.2%   |
| No        | 1068     | 45.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 595      | 25.65%  |
| Gigabyte Technology | 418      | 18.02%  |
| MSI                 | 239      | 10.3%   |
| ASRock              | 211      | 9.09%   |
| Dell                | 191      | 8.23%   |
| Hewlett-Packard     | 181      | 7.8%    |
| Lenovo              | 85       | 3.66%   |
| Intel               | 64       | 2.76%   |
| Acer                | 48       | 2.07%   |
| Pegatron            | 32       | 1.38%   |
| Biostar             | 32       | 1.38%   |
| Fujitsu             | 31       | 1.34%   |
| Foxconn             | 28       | 1.21%   |
| Medion              | 23       | 0.99%   |
| ECS                 | 20       | 0.86%   |
| Unknown             | 19       | 0.82%   |
| Positivo            | 10       | 0.43%   |
| Shuttle             | 6        | 0.26%   |
| PCWare              | 6        | 0.26%   |
| Packard Bell        | 6        | 0.26%   |
| Supermicro          | 5        | 0.22%   |
| Gateway             | 5        | 0.22%   |
| Fujitsu Siemens     | 5        | 0.22%   |
| Inventec            | 4        | 0.17%   |
| BESSTAR Tech        | 4        | 0.17%   |
| Philco              | 3        | 0.13%   |
| OEM                 | 3        | 0.13%   |
| Itautec             | 3        | 0.13%   |
| Huanan              | 3        | 0.13%   |
| Alienware           | 3        | 0.13%   |
| Semp Toshiba        | 2        | 0.09%   |
| MACHINIST           | 2        | 0.09%   |
| eMachines           | 2        | 0.09%   |
| AZW                 | 2        | 0.09%   |
| AMD                 | 2        | 0.09%   |
| ABIT                | 2        | 0.09%   |
| ZOTAC               | 1        | 0.04%   |
| Wortmann AG         | 1        | 0.04%   |
| VS Company          | 1        | 0.04%   |
| Toshiba             | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS All Series             | 55       | 2.37%   |
| Dell OptiPlex 780           | 25       | 1.08%   |
| Unknown                     | 22       | 0.95%   |
| Dell OptiPlex 7010          | 16       | 0.69%   |
| ASUS PRIME A320M-K          | 14       | 0.6%    |
| Gigabyte 970A-DS3P          | 12       | 0.52%   |
| MSI MS-7817                 | 11       | 0.47%   |
| Gigabyte A320M-S2H          | 11       | 0.47%   |
| Gigabyte B450M DS3H         | 10       | 0.43%   |
| ASUS PRIME B450M-A          | 10       | 0.43%   |
| Intel H61                   | 9        | 0.39%   |
| HP EliteDesk 800 G1 SFF     | 9        | 0.39%   |
| HP Compaq Pro 6300 SFF      | 9        | 0.39%   |
| Dell OptiPlex 9020          | 9        | 0.39%   |
| Dell OptiPlex 3020          | 9        | 0.39%   |
| MSI MS-7721                 | 8        | 0.34%   |
| MSI MS-7641                 | 8        | 0.34%   |
| HP Compaq 8200 Elite SFF PC | 8        | 0.34%   |
| Gigabyte G31M-ES2L          | 8        | 0.34%   |
| Gigabyte B75M-D3H           | 8        | 0.34%   |
| ASRock G31M-S               | 8        | 0.34%   |
| MSI MS-7C52                 | 7        | 0.3%    |
| Gigabyte H61M-DS2           | 7        | 0.3%    |
| Dell OptiPlex 790           | 7        | 0.3%    |
| ASUS TUF Gaming X570-PLUS   | 7        | 0.3%    |
| ASUS P8Z77-V LX             | 7        | 0.3%    |
| ASUS M5A97 R2.0             | 7        | 0.3%    |
| MSI MS-7C37                 | 6        | 0.26%   |
| MSI MS-7B86                 | 6        | 0.26%   |
| MSI MS-7693                 | 6        | 0.26%   |
| Gigabyte H61M-S1            | 6        | 0.26%   |
| Gigabyte GA-78LMT-USB3 6.0  | 6        | 0.26%   |
| Gigabyte B450 AORUS ELITE   | 6        | 0.26%   |
| Dell OptiPlex 390           | 6        | 0.26%   |
| ASUS SABERTOOTH 990FX R2.0  | 6        | 0.26%   |
| ASUS PRIME X470-PRO         | 6        | 0.26%   |
| ASUS PRIME B350-PLUS        | 6        | 0.26%   |
| ASUS P8H61-M LX3 R2.0       | 6        | 0.26%   |
| ASUS M5A78L-M/USB3          | 6        | 0.26%   |
| ASUS M5A78L-M PLUS/USB3     | 6        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 132      | 5.69%   |
| ASUS PRIME             | 92       | 3.97%   |
| HP Compaq              | 75       | 3.23%   |
| ASUS All               | 55       | 2.37%   |
| Lenovo ThinkCentre     | 52       | 2.24%   |
| Acer Aspire            | 35       | 1.51%   |
| ASUS ROG               | 34       | 1.47%   |
| Fujitsu ESPRIMO        | 28       | 1.21%   |
| HP EliteDesk           | 27       | 1.16%   |
| ASUS M5A78L-M          | 27       | 1.16%   |
| ASUS TUF               | 22       | 0.95%   |
| Unknown                | 22       | 0.95%   |
| ASUS P8Z77-V           | 21       | 0.91%   |
| ASUS P8H61-M           | 21       | 0.91%   |
| HP ProDesk             | 20       | 0.86%   |
| Gigabyte B450M         | 19       | 0.82%   |
| Dell Precision         | 17       | 0.73%   |
| Dell Inspiron          | 17       | 0.73%   |
| Lenovo IdeaCentre      | 16       | 0.69%   |
| Gigabyte B450          | 14       | 0.6%    |
| Gigabyte A320M-S2H     | 14       | 0.6%    |
| Dell Vostro            | 14       | 0.6%    |
| Gigabyte X570          | 12       | 0.52%   |
| Gigabyte 970A-DS3P     | 12       | 0.52%   |
| ASUS M5A97             | 12       | 0.52%   |
| MSI MS-7817            | 11       | 0.47%   |
| Gigabyte GA-78LMT-USB3 | 11       | 0.47%   |
| ASUS P5G41T-M          | 11       | 0.47%   |
| Intel H61              | 10       | 0.43%   |
| HP Pavilion            | 9        | 0.39%   |
| ASUS P5K               | 9        | 0.39%   |
| Acer Veriton           | 9        | 0.39%   |
| MSI MS-7721            | 8        | 0.34%   |
| MSI MS-7641            | 8        | 0.34%   |
| Gigabyte G31M-ES2L     | 8        | 0.34%   |
| Gigabyte B75M-D3H      | 8        | 0.34%   |
| ASUS SABERTOOTH        | 8        | 0.34%   |
| ASUS P8P67             | 8        | 0.34%   |
| ASRock G31M-S          | 8        | 0.34%   |
| MSI MS-7C52            | 7        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 295      | 12.72%  |
| 2013 | 217      | 9.35%   |
| 2011 | 209      | 9.01%   |
| 2010 | 186      | 8.02%   |
| 2014 | 182      | 7.84%   |
| 2018 | 171      | 7.37%   |
| 2009 | 164      | 7.07%   |
| 2017 | 148      | 6.38%   |
| 2008 | 134      | 5.78%   |
| 2019 | 113      | 4.87%   |
| 2015 | 106      | 4.57%   |
| 2016 | 96       | 4.14%   |
| 2020 | 93       | 4.01%   |
| 2007 | 90       | 3.88%   |
| 2006 | 56       | 2.41%   |
| 2021 | 40       | 1.72%   |
| 2005 | 13       | 0.56%   |
| 2004 | 5        | 0.22%   |
| 2023 | 1        | 0.04%   |
| 2022 | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2320     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2320     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2320     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 569      | 24.37%  |
| 8.01-16.0       | 560      | 23.98%  |
| 4.01-8.0        | 464      | 19.87%  |
| 16.01-24.0      | 422      | 18.07%  |
| 32.01-64.0      | 140      | 6%      |
| 1.01-2.0        | 94       | 4.03%   |
| 24.01-32.0      | 32       | 1.37%   |
| 2.01-3.0        | 24       | 1.03%   |
| 64.01-256.0     | 22       | 0.94%   |
| 0.51-1.0        | 7        | 0.3%    |
| More than 256.0 | 1        | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 1718     | 72.92%  |
| 0.51-1.0  | 398      | 16.89%  |
| 2.01-3.0  | 131      | 5.56%   |
| 0.01-0.5  | 90       | 3.82%   |
| 3.01-4.0  | 10       | 0.42%   |
| 4.01-8.0  | 7        | 0.3%    |
| 8.01-16.0 | 2        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1130     | 48.39%  |
| 2      | 580      | 24.84%  |
| 3      | 313      | 13.4%   |
| 4      | 157      | 6.72%   |
| 5      | 62       | 2.66%   |
| 0      | 43       | 1.84%   |
| 6      | 20       | 0.86%   |
| 7      | 15       | 0.64%   |
| 8      | 12       | 0.51%   |
| 9      | 2        | 0.09%   |
| 18     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1579     | 67.86%  |
| No        | 748      | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2299     | 99.09%  |
| No        | 21       | 0.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1588     | 68.27%  |
| Yes       | 738      | 31.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1886     | 81.05%  |
| Yes       | 441      | 18.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 272      | 11.72%  |
| Russia      | 241      | 10.38%  |
| USA         | 225      | 9.69%   |
| France      | 189      | 8.14%   |
| Brazil      | 173      | 7.45%   |
| Poland      | 130      | 5.6%    |
| Italy       | 108      | 4.65%   |
| Spain       | 90       | 3.88%   |
| UK          | 68       | 2.93%   |
| Canada      | 62       | 2.67%   |
| Mexico      | 44       | 1.9%    |
| Ukraine     | 40       | 1.72%   |
| Czechia     | 39       | 1.68%   |
| Hungary     | 37       | 1.59%   |
| Australia   | 33       | 1.42%   |
| Argentina   | 31       | 1.34%   |
| Netherlands | 30       | 1.29%   |
| Belgium     | 24       | 1.03%   |
| Greece      | 23       | 0.99%   |
| Austria     | 23       | 0.99%   |
| Romania     | 22       | 0.95%   |
| India       | 22       | 0.95%   |
| Serbia      | 19       | 0.82%   |
| Japan       | 19       | 0.82%   |
| Sweden      | 18       | 0.78%   |
| Finland     | 18       | 0.78%   |
| Bulgaria    | 17       | 0.73%   |
| Switzerland | 16       | 0.69%   |
| Portugal    | 14       | 0.6%    |
| Israel      | 14       | 0.6%    |
| Slovakia    | 13       | 0.56%   |
| Denmark     | 13       | 0.56%   |
| Belarus     | 12       | 0.52%   |
| Hong Kong   | 10       | 0.43%   |
| Taiwan      | 9        | 0.39%   |
| Costa Rica  | 9        | 0.39%   |
| Norway      | 8        | 0.34%   |
| Indonesia   | 8        | 0.34%   |
| Chile       | 8        | 0.34%   |
| Venezuela   | 7        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 39       | 1.66%   |
| Sao Paulo      | 24       | 1.02%   |
| Warsaw         | 19       | 0.81%   |
| St Petersburg  | 18       | 0.76%   |
| Rio de Janeiro | 17       | 0.72%   |
| Berlin         | 16       | 0.68%   |
| Mexico City    | 15       | 0.64%   |
| Paris          | 14       | 0.59%   |
| Milan          | 13       | 0.55%   |
| Rome           | 12       | 0.51%   |
| Porto Alegre   | 10       | 0.42%   |
| Novosibirsk    | 10       | 0.42%   |
| Barcelona      | 10       | 0.42%   |
| Vienna         | 9        | 0.38%   |
| Nuremberg      | 9        | 0.38%   |
| Helsinki       | 9        | 0.38%   |
| Athens         | 9        | 0.38%   |
| Yekaterinburg  | 8        | 0.34%   |
| Stuttgart      | 8        | 0.34%   |
| Prague         | 8        | 0.34%   |
| Hamburg        | 8        | 0.34%   |
| Budapest       | 8        | 0.34%   |
| Perm           | 7        | 0.3%    |
| Montreal       | 7        | 0.3%    |
| Melbourne      | 7        | 0.3%    |
| Madrid         | 7        | 0.3%    |
| Cologne        | 7        | 0.3%    |
| Belgrade       | 7        | 0.3%    |
| Volgograd      | 6        | 0.25%   |
| Sydney         | 6        | 0.25%   |
| New Taipei     | 6        | 0.25%   |
| Munich         | 6        | 0.25%   |
| Kharkiv        | 6        | 0.25%   |
| Essen          | 6        | 0.25%   |
| Central        | 6        | 0.25%   |
| Turin          | 5        | 0.21%   |
| Sofia          | 5        | 0.21%   |
| Seattle        | 5        | 0.21%   |
| Saratov        | 5        | 0.21%   |
| San Salvador   | 5        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 873      | 1136   | 23.09%  |
| Seagate             | 842      | 1066   | 22.27%  |
| Samsung Electronics | 438      | 570    | 11.58%  |
| Toshiba             | 240      | 272    | 6.35%   |
| Kingston            | 221      | 254    | 5.85%   |
| Hitachi             | 159      | 178    | 4.21%   |
| Crucial             | 152      | 182    | 4.02%   |
| SanDisk             | 102      | 109    | 2.7%    |
| A-DATA Technology   | 76       | 87     | 2.01%   |
| Unknown             | 55       | 80     | 1.45%   |
| Maxtor              | 48       | 53     | 1.27%   |
| China               | 48       | 52     | 1.27%   |
| Intel               | 38       | 45     | 1.01%   |
| Intenso             | 36       | 41     | 0.95%   |
| GOODRAM             | 33       | 38     | 0.87%   |
| Patriot             | 32       | 33     | 0.85%   |
| PNY                 | 25       | 26     | 0.66%   |
| Apacer              | 21       | 23     | 0.56%   |
| SPCC                | 20       | 20     | 0.53%   |
| HGST                | 19       | 27     | 0.5%    |
| OCZ                 | 18       | 19     | 0.48%   |
| Corsair             | 15       | 17     | 0.4%    |
| Transcend           | 14       | 14     | 0.37%   |
| Hewlett-Packard     | 14       | 16     | 0.37%   |
| Phison              | 13       | 15     | 0.34%   |
| Plextor             | 12       | 14     | 0.32%   |
| JMicron Technology  | 11       | 12     | 0.29%   |
| Team                | 9        | 10     | 0.24%   |
| SK hynix            | 7        | 7      | 0.19%   |
| Fujitsu             | 7        | 7      | 0.19%   |
| XPG                 | 6        | 7      | 0.16%   |
| Verbatim            | 6        | 9      | 0.16%   |
| Netac               | 6        | 6      | 0.16%   |
| KingSpec            | 6        | 6      | 0.16%   |
| Micron Technology   | 5        | 6      | 0.13%   |
| Gigabyte Technology | 5        | 5      | 0.13%   |
| XrayDisk            | 4        | 4      | 0.11%   |
| WD MediaMax         | 4        | 5      | 0.11%   |
| Silicon Motion      | 4        | 5      | 0.11%   |
| Lexar               | 4        | 4      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 84       | 1.94%   |
| Seagate ST1000DM010-2EP102 1TB   | 65       | 1.5%    |
| Kingston SA400S37240G 240GB SSD  | 57       | 1.32%   |
| Toshiba DT01ACA100 1TB           | 55       | 1.27%   |
| Seagate ST3500418AS 500GB        | 42       | 0.97%   |
| Toshiba DT01ACA050 500GB         | 40       | 0.92%   |
| WDC WD10EZEX-08WN4A0 1TB         | 35       | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB   | 30       | 0.69%   |
| Unknown SD/MMC/MS PRO 128GB      | 29       | 0.67%   |
| Toshiba HDWD110 1TB              | 29       | 0.67%   |
| Kingston SV300S37A120G 120GB SSD | 28       | 0.65%   |
| Kingston SA400S37120G 120GB SSD  | 27       | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 26       | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB   | 25       | 0.58%   |
| Samsung SSD 860 EVO 500GB        | 24       | 0.55%   |
| WDC WD10EZEX-00BN5A0 1TB         | 23       | 0.53%   |
| Seagate ST3500413AS 500GB        | 23       | 0.53%   |
| Samsung SSD 850 EVO 250GB        | 23       | 0.53%   |
| Toshiba DT01ACA200 2TB           | 22       | 0.51%   |
| Samsung SSD 860 EVO 250GB        | 21       | 0.48%   |
| Kingston SA400S37480G 480GB SSD  | 21       | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB   | 20       | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB   | 19       | 0.44%   |
| Crucial CT240BX500SSD1 240GB     | 19       | 0.44%   |
| Seagate ST3160815AS 160GB        | 18       | 0.42%   |
| Seagate ST1000DM003-1SB102 1TB   | 18       | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 17       | 0.39%   |
| Crucial CT500MX500SSD1 500GB     | 17       | 0.39%   |
| Samsung SSD 850 EVO 500GB        | 16       | 0.37%   |
| Samsung HD103SJ 1TB              | 16       | 0.37%   |
| Seagate ST3500312CS 500GB        | 15       | 0.35%   |
| WDC WD20EZRX-00D8PB0 2TB         | 14       | 0.32%   |
| Seagate ST3250318AS 250GB        | 14       | 0.32%   |
| Seagate ST31000528AS 1TB         | 14       | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB   | 14       | 0.32%   |
| Seagate ST1000DM003-9YN162 1TB   | 14       | 0.32%   |
| Crucial CT1000MX500SSD1 1TB      | 14       | 0.32%   |
| A-DATA SU630 240GB SSD           | 14       | 0.32%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 13       | 0.3%    |
| Seagate ST3250310AS 250GB        | 13       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 836      | 1057   | 36.02%  |
| WDC                 | 781      | 992    | 33.65%  |
| Toshiba             | 218      | 247    | 9.39%   |
| Samsung Electronics | 176      | 197    | 7.58%   |
| Hitachi             | 159      | 178    | 6.85%   |
| Maxtor              | 48       | 53     | 2.07%   |
| Unknown             | 30       | 30     | 1.29%   |
| HGST                | 19       | 27     | 0.82%   |
| Fujitsu             | 7        | 7      | 0.3%    |
| JMicron Technology  | 6        | 6      | 0.26%   |
| Hewlett-Packard     | 6        | 6      | 0.26%   |
| WD MediaMax         | 4        | 5      | 0.17%   |
| SABRENT             | 3        | 3      | 0.13%   |
| Quantum             | 3        | 3      | 0.13%   |
| External            | 3        | 3      | 0.13%   |
| ASMT                | 3        | 3      | 0.13%   |
| MDT                 | 2        | 2      | 0.09%   |
| IBM/Hitachi         | 2        | 2      | 0.09%   |
| ExcelStor           | 2        | 2      | 0.09%   |
| ASMedia             | 2        | 2      | 0.09%   |
| USB                 | 1        | 1      | 0.04%   |
| TPH00800640GB       | 1        | 1      | 0.04%   |
| TO Exter            | 1        | 1      | 0.04%   |
| StoreJet            | 1        | 1      | 0.04%   |
| RSH-319             | 1        | 1      | 0.04%   |
| KESU                | 1        | 1      | 0.04%   |
| IB                  | 1        | 2      | 0.04%   |
| HPE                 | 1        | 1      | 0.04%   |
| FC-1307             | 1        | 1      | 0.04%   |
| China               | 1        | 1      | 0.04%   |
| ASMT106x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 204      | 261    | 16.37%  |
| Kingston            | 200      | 228    | 16.05%  |
| Crucial             | 130      | 158    | 10.43%  |
| SanDisk             | 99       | 105    | 7.95%   |
| WDC                 | 98       | 105    | 7.87%   |
| A-DATA Technology   | 70       | 80     | 5.62%   |
| China               | 47       | 51     | 3.77%   |
| Intenso             | 36       | 41     | 2.89%   |
| GOODRAM             | 32       | 37     | 2.57%   |
| Patriot             | 29       | 30     | 2.33%   |
| PNY                 | 25       | 26     | 2.01%   |
| Toshiba             | 20       | 20     | 1.61%   |
| Intel               | 20       | 23     | 1.61%   |
| Apacer              | 19       | 21     | 1.52%   |
| OCZ                 | 18       | 19     | 1.44%   |
| SPCC                | 16       | 16     | 1.28%   |
| Transcend           | 13       | 13     | 1.04%   |
| Unknown             | 12       | 13     | 0.96%   |
| Plextor             | 10       | 12     | 0.8%    |
| Corsair             | 9        | 10     | 0.72%   |
| Team                | 8        | 9      | 0.64%   |
| Verbatim            | 6        | 9      | 0.48%   |
| SK hynix            | 6        | 6      | 0.48%   |
| Netac               | 6        | 6      | 0.48%   |
| KingSpec            | 6        | 6      | 0.48%   |
| Hewlett-Packard     | 6        | 6      | 0.48%   |
| Micron Technology   | 5        | 6      | 0.4%    |
| XrayDisk            | 4        | 4      | 0.32%   |
| KingDian            | 4        | 4      | 0.32%   |
| Seagate             | 3        | 3      | 0.24%   |
| LITEONIT            | 3        | 3      | 0.24%   |
| Lexar               | 3        | 3      | 0.24%   |
| Gigabyte Technology | 3        | 3      | 0.24%   |
| Emtec               | 3        | 3      | 0.24%   |
| DOGGO               | 3        | 3      | 0.24%   |
| Colorful            | 3        | 3      | 0.24%   |
| AMD                 | 3        | 3      | 0.24%   |
| Zheino              | 2        | 2      | 0.16%   |
| VERICO              | 2        | 2      | 0.16%   |
| Vaseky              | 2        | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1787     | 2837   | 58.04%  |
| SSD     | 1024     | 1414   | 33.26%  |
| NVMe    | 235      | 311    | 7.63%   |
| Unknown | 27       | 49     | 0.88%   |
| MMC     | 6        | 6      | 0.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2217     | 4124   | 85.76%  |
| NVMe | 235      | 308    | 9.09%   |
| SAS  | 127      | 179    | 4.91%   |
| MMC  | 6        | 6      | 0.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1769     | 2627   | 58.29%  |
| 0.51-1.0   | 810      | 1046   | 26.69%  |
| 1.01-2.0   | 278      | 351    | 9.16%   |
| 2.01-3.0   | 69       | 89     | 2.27%   |
| 3.01-4.0   | 62       | 83     | 2.04%   |
| 4.01-10.0  | 39       | 47     | 1.29%   |
| 10.01-20.0 | 8        | 8      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1053     | 44.32%  |
| Unknown        | 538      | 22.64%  |
| 101-250        | 266      | 11.2%   |
| 251-500        | 185      | 7.79%   |
| 501-1000       | 96       | 4.04%   |
| 51-100         | 87       | 3.66%   |
| 21-50          | 78       | 3.28%   |
| 1001-2000      | 44       | 1.85%   |
| 2001-3000      | 18       | 0.76%   |
| More than 3000 | 11       | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1623     | 68.63%  |
| Unknown        | 538      | 22.75%  |
| 101-250        | 47       | 1.99%   |
| 51-100         | 38       | 1.61%   |
| 21-50          | 36       | 1.52%   |
| 251-500        | 32       | 1.35%   |
| 501-1000       | 28       | 1.18%   |
| 1001-2000      | 14       | 0.59%   |
| More than 3000 | 5        | 0.21%   |
| 2001-3000      | 4        | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 34       | 34     | 3.84%   |
| Seagate ST3500418AS 500GB         | 21       | 23     | 2.37%   |
| Toshiba DT01ACA100 1TB            | 13       | 13     | 1.47%   |
| Toshiba DT01ACA050 500GB          | 9        | 9      | 1.02%   |
| WDC WD5000AAKX-003CA0 500GB       | 8        | 8      | 0.9%    |
| Seagate ST9500325AS 500GB         | 8        | 8      | 0.9%    |
| Seagate ST31000524AS 1TB          | 8        | 8      | 0.9%    |
| Samsung Electronics HD103SJ 1TB   | 8        | 9      | 0.9%    |
| WDC WD5000AAKX-001CA0 500GB       | 7        | 8      | 0.79%   |
| Seagate ST31000528AS 1TB          | 7        | 7      | 0.79%   |
| Kingston SV300S37A120G 120GB SSD  | 7        | 7      | 0.79%   |
| WDC WD10EADS-00L5B1 1TB           | 6        | 6      | 0.68%   |
| Seagate ST3250310AS 250GB         | 6        | 6      | 0.68%   |
| Seagate ST31500341AS 1TB          | 6        | 6      | 0.68%   |
| Samsung Electronics HD161HJ 160GB | 6        | 6      | 0.68%   |
| Hitachi HDS721050CLA362 500GB     | 6        | 8      | 0.68%   |
| Seagate ST3500413AS 500GB         | 5        | 5      | 0.56%   |
| Seagate ST3320418AS 320GB         | 5        | 5      | 0.56%   |
| Seagate ST3250820AS 250GB         | 5        | 6      | 0.56%   |
| Seagate ST3250410AS 250GB         | 5        | 5      | 0.56%   |
| Seagate ST2000DL003-9VT166 2TB    | 5        | 6      | 0.56%   |
| Samsung Electronics HD502HJ 500GB | 5        | 5      | 0.56%   |
| Samsung Electronics HD322HJ 320GB | 5        | 5      | 0.56%   |
| Hitachi HDS721680PLA380 80GB      | 5        | 5      | 0.56%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 4        | 4      | 0.45%   |
| WDC WD5000AADS-00S9B0 500GB       | 4        | 4      | 0.45%   |
| WDC WD3200AAJS-56M0A0 320GB       | 4        | 4      | 0.45%   |
| WDC WD2500AAKX-753CA1 250GB       | 4        | 5      | 0.45%   |
| WDC WD20PURZ-85GU6Y0 2TB          | 4        | 4      | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB          | 4        | 4      | 0.45%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 5      | 0.45%   |
| Seagate ST3320620AS 320GB         | 4        | 4      | 0.45%   |
| Seagate ST31000333AS 1TB          | 4        | 5      | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB    | 4        | 4      | 0.45%   |
| Seagate ST1000DM003-9YN162 1TB    | 4        | 5      | 0.45%   |
| Samsung Electronics HD250HJ 250GB | 4        | 4      | 0.45%   |
| Samsung Electronics HD103UJ 1TB   | 4        | 4      | 0.45%   |
| Samsung Electronics HD103SI 1TB   | 4        | 4      | 0.45%   |
| Samsung Electronics HD080HJ/ 80GB | 4        | 4      | 0.45%   |
| Kingston SA400S37480G 480GB SSD   | 4        | 5      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 269      | 309    | 32.14%  |
| Seagate             | 258      | 286    | 30.82%  |
| Samsung Electronics | 90       | 97     | 10.75%  |
| Hitachi             | 66       | 75     | 7.89%   |
| Toshiba             | 37       | 38     | 4.42%   |
| Maxtor              | 29       | 29     | 3.46%   |
| Kingston            | 24       | 26     | 2.87%   |
| SanDisk             | 9        | 9      | 1.08%   |
| Crucial             | 8        | 8      | 0.96%   |
| China               | 6        | 6      | 0.72%   |
| A-DATA Technology   | 5        | 5      | 0.6%    |
| Intel               | 4        | 4      | 0.48%   |
| HGST                | 4        | 4      | 0.48%   |
| Fujitsu             | 3        | 3      | 0.36%   |
| OCZ                 | 2        | 2      | 0.24%   |
| Intenso             | 2        | 2      | 0.24%   |
| Hewlett-Packard     | 2        | 2      | 0.24%   |
| Apacer              | 2        | 3      | 0.24%   |
| XPG                 | 1        | 1      | 0.12%   |
| WD MediaMax         | 1        | 1      | 0.12%   |
| Team                | 1        | 1      | 0.12%   |
| SK hynix            | 1        | 1      | 0.12%   |
| Quantum             | 1        | 1      | 0.12%   |
| Plextor             | 1        | 1      | 0.12%   |
| Netac               | 1        | 1      | 0.12%   |
| Neo Forza           | 1        | 1      | 0.12%   |
| LITEON              | 1        | 1      | 0.12%   |
| KingFast            | 1        | 1      | 0.12%   |
| IB                  | 1        | 1      | 0.12%   |
| GOODRAM             | 1        | 1      | 0.12%   |
| faspeed             | 1        | 1      | 0.12%   |
| DRVEO               | 1        | 1      | 0.12%   |
| Corsair             | 1        | 1      | 0.12%   |
| Colorful            | 1        | 1      | 0.12%   |
| Unknown             | 1        | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 261      | 300    | 35.03%  |
| Seagate             | 258      | 286    | 34.63%  |
| Samsung Electronics | 81       | 88     | 10.87%  |
| Hitachi             | 66       | 75     | 8.86%   |
| Toshiba             | 37       | 38     | 4.97%   |
| Maxtor              | 29       | 29     | 3.89%   |
| HGST                | 4        | 4      | 0.54%   |
| Fujitsu             | 3        | 3      | 0.4%    |
| Hewlett-Packard     | 2        | 2      | 0.27%   |
| WD MediaMax         | 1        | 1      | 0.13%   |
| Quantum             | 1        | 1      | 0.13%   |
| IB                  | 1        | 1      | 0.13%   |
| China               | 1        | 1      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 659      | 829    | 87.63%  |
| SSD  | 87       | 90     | 11.57%  |
| NVMe | 6        | 6      | 0.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD20EZRX-00D8PB0 2TB          | 2        | 2      | 10%     |
| Seagate ST3500418AS 500GB         | 2        | 4      | 10%     |
| Seagate ST3250318AS 250GB         | 2        | 2      | 10%     |
| WDC WD800JD-75MSA3 80GB           | 1        | 1      | 5%      |
| WDC WD800JD-00LSA0 80GB           | 1        | 1      | 5%      |
| WDC WD10JPVT-75A1YT0 1TB          | 1        | 1      | 5%      |
| WDC WD10EALX-759BA1 1TB           | 1        | 1      | 5%      |
| TPH00800640GB 640GB               | 1        | 1      | 5%      |
| Seagate STM3250318AS 250GB        | 1        | 1      | 5%      |
| Seagate ST3320418AS 320GB         | 1        | 1      | 5%      |
| Seagate ST31000528AS 1TB          | 1        | 1      | 5%      |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 5%      |
| Samsung Electronics HD502HJ 500GB | 1        | 1      | 5%      |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 5%      |
| Maxtor STM3500320AS 500GB         | 1        | 1      | 5%      |
| Kingston SMS200S360G 64GB SSD     | 1        | 1      | 5%      |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 40%     |
| WDC                 | 6        | 6      | 30%     |
| Samsung Electronics | 2        | 2      | 10%     |
| TPH00800640GB       | 1        | 1      | 5%      |
| Maxtor              | 1        | 1      | 5%      |
| Kingston            | 1        | 1      | 5%      |
| Hitachi             | 1        | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1741     | 3192   | 61.89%  |
| Malfunc  | 732      | 925    | 26.02%  |
| Detected | 320      | 478    | 11.38%  |
| Failed   | 20       | 22     | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1486     | 52.18%  |
| AMD                              | 724      | 25.42%  |
| Nvidia                           | 95       | 3.34%   |
| Samsung Electronics              | 88       | 3.09%   |
| JMicron Technology               | 87       | 3.05%   |
| ASMedia Technology               | 77       | 2.7%    |
| Marvell Technology Group         | 76       | 2.67%   |
| SanDisk                          | 34       | 1.19%   |
| VIA Technologies                 | 33       | 1.16%   |
| Phison Electronics               | 30       | 1.05%   |
| Kingston Technology Company      | 25       | 0.88%   |
| Micron/Crucial Technology        | 22       | 0.77%   |
| Silicon Motion                   | 12       | 0.42%   |
| Silicon Image                    | 8        | 0.28%   |
| ADATA Technology                 | 6        | 0.21%   |
| Toshiba America Info Systems     | 5        | 0.18%   |
| Seagate Technology               | 5        | 0.18%   |
| LSI Logic / Symbios Logic        | 5        | 0.18%   |
| Realtek Semiconductor            | 4        | 0.14%   |
| MAXIO Technology (Hangzhou)      | 3        | 0.11%   |
| Lite-On IT Corp. / Plextor       | 3        | 0.11%   |
| Micron Technology                | 2        | 0.07%   |
| Lite-On Technology               | 2        | 0.07%   |
| KIOXIA                           | 2        | 0.07%   |
| Integrated Technology Express    | 2        | 0.07%   |
| Broadcom / LSI                   | 2        | 0.07%   |
| Solid State Storage Technology   | 1        | 0.04%   |
| SK hynix                         | 1        | 0.04%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |
| Shenzhen Longsys Electronics     | 1        | 0.04%   |
| Promise Technology               | 1        | 0.04%   |
| OCZ Technology Group             | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |
| Biwin Storage Technology         | 1        | 0.04%   |
| Adaptec                          | 1        | 0.04%   |
| 3ware                            | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 396      | 10.18%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 191      | 4.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 174      | 4.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 172      | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 151      | 3.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 129      | 3.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 128      | 3.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 122      | 3.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 120      | 3.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 117      | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 92       | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 84       | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 84       | 2.16%   |
| Intel SATA Controller [RAID mode]                                                       | 78       | 2.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 78       | 2.01%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 70       | 1.8%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 65       | 1.67%   |
| Nvidia MCP61 SATA Controller                                                            | 56       | 1.44%   |
| Nvidia MCP61 IDE                                                                        | 55       | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 54       | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 50       | 1.29%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 49       | 1.26%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 46       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 45       | 1.16%   |
| AMD 300 Series Chipset SATA Controller                                                  | 40       | 1.03%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 39       | 1%      |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 37       | 0.95%   |
| AMD FCH IDE Controller                                                                  | 36       | 0.93%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 35       | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 30       | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 30       | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 30       | 0.77%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 27       | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 25       | 0.64%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 25       | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 24       | 0.62%   |
| AMD 500 Series Chipset SATA Controller                                                  | 24       | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 22       | 0.57%   |
| JMicron JMB368 IDE controller                                                           | 21       | 0.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1676     | 58.05%  |
| IDE  | 855      | 29.62%  |
| NVMe | 233      | 8.07%   |
| RAID | 110      | 3.81%   |
| SCSI | 7        | 0.24%   |
| SAS  | 6        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1512     | 65.17%  |
| AMD    | 808      | 34.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 46       | 1.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 39       | 1.68%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 32       | 1.38%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 29       | 1.25%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 29       | 1.25%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 26       | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor           | 26       | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 25       | 1.08%   |
| AMD FX-8350 Eight-Core Processor            | 25       | 1.08%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 21       | 0.9%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 20       | 0.86%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 20       | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 19       | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 0.77%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 17       | 0.73%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 17       | 0.73%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 16       | 0.69%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 16       | 0.69%   |
| AMD Athlon II X2 250 Processor              | 16       | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.65%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 15       | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 15       | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 15       | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.65%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 15       | 0.65%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 15       | 0.65%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 15       | 0.65%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 15       | 0.65%   |
| AMD Phenom II X4 955 Processor              | 15       | 0.65%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 14       | 0.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 14       | 0.6%    |
| AMD FX-4300 Quad-Core Processor             | 14       | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 13       | 0.56%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 13       | 0.56%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 13       | 0.56%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 13       | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 0.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 13       | 0.56%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 12       | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 377      | 16.23%  |
| Intel Core i3           | 258      | 11.11%  |
| Intel Core i7           | 229      | 9.86%   |
| Intel Core 2 Duo        | 147      | 6.33%   |
| AMD Ryzen 5             | 128      | 5.51%   |
| AMD FX                  | 105      | 4.52%   |
| Intel Pentium           | 101      | 4.35%   |
| Intel Celeron           | 87       | 3.75%   |
| Intel Pentium Dual-Core | 65       | 2.8%    |
| Intel Core 2 Quad       | 64       | 2.76%   |
| AMD Ryzen 7             | 60       | 2.58%   |
| Intel Xeon              | 52       | 2.24%   |
| AMD Ryzen 3             | 50       | 2.15%   |
| AMD Athlon II X2        | 49       | 2.11%   |
| AMD A8                  | 49       | 2.11%   |
| AMD Phenom II X4        | 41       | 1.76%   |
| AMD Athlon 64 X2        | 39       | 1.68%   |
| AMD A10                 | 38       | 1.64%   |
| Intel Core 2            | 34       | 1.46%   |
| AMD A4                  | 31       | 1.33%   |
| AMD Athlon II X4        | 25       | 1.08%   |
| AMD Athlon              | 25       | 1.08%   |
| AMD Ryzen 9             | 24       | 1.03%   |
| AMD A6                  | 22       | 0.95%   |
| Intel Pentium Dual      | 18       | 0.77%   |
| Intel Atom              | 18       | 0.77%   |
| Intel Pentium 4         | 17       | 0.73%   |
| AMD Phenom II X6        | 17       | 0.73%   |
| Other                   | 16       | 0.69%   |
| Intel Pentium D         | 13       | 0.56%   |
| AMD Phenom              | 13       | 0.56%   |
| AMD Sempron             | 12       | 0.52%   |
| Intel Pentium Gold      | 11       | 0.47%   |
| AMD Athlon II X3        | 10       | 0.43%   |
| AMD Athlon 64           | 10       | 0.43%   |
| AMD Athlon X4           | 8        | 0.34%   |
| AMD E                   | 6        | 0.26%   |
| AMD Athlon Dual Core    | 6        | 0.26%   |
| Intel Core i9           | 5        | 0.22%   |
| AMD GX                  | 5        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 960      | 41.34%  |
| 4      | 912      | 39.28%  |
| 6      | 186      | 8.01%   |
| 8      | 95       | 4.09%   |
| 1      | 93       | 4.01%   |
| 3      | 39       | 1.68%   |
| 12     | 23       | 0.99%   |
| 16     | 7        | 0.3%    |
| 10     | 5        | 0.22%   |
| 24     | 1        | 0.04%   |
| 14     | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2315     | 99.78%  |
| 2      | 5        | 0.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1272     | 54.78%  |
| 2      | 1050     | 45.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2319     | 99.96%  |
| Unknown        | 1        | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 253      | 10.85%  |
| 0x306a9    | 212      | 9.09%   |
| 0x1067a    | 210      | 9.01%   |
| 0x206a7    | 188      | 8.06%   |
| Unknown    | 96       | 4.12%   |
| 0x506e3    | 75       | 3.22%   |
| 0x08701021 | 65       | 2.79%   |
| 0x010000c8 | 64       | 2.74%   |
| 0x906e9    | 60       | 2.57%   |
| 0x06001119 | 60       | 2.57%   |
| 0x906ea    | 52       | 2.23%   |
| 0x08101016 | 44       | 1.89%   |
| 0x0800820d | 43       | 1.84%   |
| 0x6fd      | 38       | 1.63%   |
| 0x08108109 | 31       | 1.33%   |
| 0x6fb      | 30       | 1.29%   |
| 0xa0653    | 28       | 1.2%    |
| 0x06000822 | 27       | 1.16%   |
| 0x06003106 | 26       | 1.11%   |
| 0x10676    | 25       | 1.07%   |
| 0x010000b6 | 24       | 1.03%   |
| 0x08001138 | 23       | 0.99%   |
| 0x106e5    | 21       | 0.9%    |
| 0x906eb    | 20       | 0.86%   |
| 0x906ed    | 18       | 0.77%   |
| 0x20655    | 18       | 0.77%   |
| 0x6f6      | 17       | 0.73%   |
| 0x0600081c | 17       | 0.73%   |
| 0x6f2      | 16       | 0.69%   |
| 0x0600611a | 16       | 0.69%   |
| 0x06000852 | 16       | 0.69%   |
| 0x20652    | 15       | 0.64%   |
| 0x106a5    | 15       | 0.64%   |
| 0x010000bf | 15       | 0.64%   |
| 0x30678    | 14       | 0.6%    |
| 0x10677    | 14       | 0.6%    |
| 0x08701013 | 14       | 0.6%    |
| 0xa0655    | 12       | 0.51%   |
| 0x206d7    | 12       | 0.51%   |
| 0x08001137 | 12       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 268      | 11.54%  |
| Penryn        | 249      | 10.72%  |
| IvyBridge     | 217      | 9.35%   |
| SandyBridge   | 200      | 8.61%   |
| K10           | 172      | 7.41%   |
| KabyLake      | 164      | 7.06%   |
| Piledriver    | 152      | 6.55%   |
| Core          | 106      | 4.57%   |
| Zen           | 100      | 4.31%   |
| Zen+          | 92       | 3.96%   |
| Zen 2         | 91       | 3.92%   |
| Skylake       | 81       | 3.49%   |
| K8 Hammer     | 60       | 2.58%   |
| CometLake     | 41       | 1.77%   |
| Nehalem       | 38       | 1.64%   |
| Westmere      | 37       | 1.59%   |
| Silvermont    | 34       | 1.46%   |
| NetBurst      | 34       | 1.46%   |
| Steamroller   | 32       | 1.38%   |
| Excavator     | 26       | 1.12%   |
| Bulldozer     | 26       | 1.12%   |
| K10 Llano     | 16       | 0.69%   |
| Bonnell       | 16       | 0.69%   |
| Zen 3         | 12       | 0.52%   |
| Puma          | 11       | 0.47%   |
| Jaguar        | 10       | 0.43%   |
| Goldmont plus | 10       | 0.43%   |
| Bobcat        | 10       | 0.43%   |
| Unknown       | 8        | 0.34%   |
| Goldmont      | 5        | 0.22%   |
| Broadwell     | 3        | 0.13%   |
| Tremont       | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 893      | 37.29%  |
| Intel                      | 795      | 33.19%  |
| AMD                        | 700      | 29.23%  |
| VIA Technologies           | 3        | 0.13%   |
| Matrox Electronics Systems | 3        | 0.13%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 130      | 5.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 107      | 4.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 92       | 3.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 90       | 3.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 70       | 2.86%   |
| Nvidia GK208B [GeForce GT 710]                                              | 67       | 2.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 53       | 2.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 49       | 2%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 43       | 1.76%   |
| Intel HD Graphics 530                                                       | 43       | 1.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 40       | 1.63%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 40       | 1.63%   |
| Nvidia GK208B [GeForce GT 730]                                              | 35       | 1.43%   |
| Intel HD Graphics 630                                                       | 34       | 1.39%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 33       | 1.35%   |
| Nvidia GF119 [GeForce GT 610]                                               | 32       | 1.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 28       | 1.14%   |
| AMD RS780L [Radeon 3000]                                                    | 27       | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 27       | 1.1%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 24       | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 23       | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 23       | 0.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 21       | 0.86%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 20       | 0.82%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 20       | 0.82%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 20       | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 19       | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 19       | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 19       | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 17       | 0.69%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 17       | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 17       | 0.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 16       | 0.65%   |
| AMD RS880 [Radeon HD 4250]                                                  | 16       | 0.65%   |
| Nvidia GF119 [GeForce GT 520]                                               | 15       | 0.61%   |
| Nvidia GF108 [GeForce GT 630]                                               | 15       | 0.61%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 15       | 0.61%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14       | 0.57%   |
| Nvidia GF108 [GeForce GT 730]                                               | 14       | 0.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 14       | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 851      | 36.65%  |
| 1 x Intel       | 740      | 31.87%  |
| 1 x AMD         | 633      | 27.26%  |
| 2 x AMD         | 46       | 1.98%   |
| Intel + Nvidia  | 21       | 0.9%    |
| AMD + Nvidia    | 16       | 0.69%   |
| Intel + AMD     | 5        | 0.22%   |
| 2 x Nvidia      | 4        | 0.17%   |
| 1 x VIA         | 3        | 0.13%   |
| 1 x Matrox      | 2        | 0.09%   |
| Nvidia + Matrox | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2246     | 96.81%  |
| Unknown     | 71       | 3.06%   |
| Proprietary | 3        | 0.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 777      | 33.39%  |
| 0.51-1.0   | 437      | 18.78%  |
| 1.01-2.0   | 409      | 17.58%  |
| 0.01-0.5   | 373      | 16.03%  |
| 3.01-4.0   | 160      | 6.88%   |
| 7.01-8.0   | 93       | 4%      |
| 5.01-6.0   | 49       | 2.11%   |
| 2.01-3.0   | 22       | 0.95%   |
| 8.01-16.0  | 6        | 0.26%   |
| 4.01-5.0   | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 436      | 19.49%  |
| Goldstar             | 299      | 13.37%  |
| Hewlett-Packard      | 192      | 8.58%   |
| Acer                 | 176      | 7.87%   |
| Dell                 | 168      | 7.51%   |
| Philips              | 132      | 5.9%    |
| AOC                  | 112      | 5.01%   |
| BenQ                 | 109      | 4.87%   |
| Ancor Communications | 93       | 4.16%   |
| Iiyama               | 52       | 2.32%   |
| ViewSonic            | 45       | 2.01%   |
| Fujitsu Siemens      | 27       | 1.21%   |
| ASUSTek Computer     | 27       | 1.21%   |
| NEC Computers        | 26       | 1.16%   |
| Lenovo               | 21       | 0.94%   |
| Eizo                 | 21       | 0.94%   |
| Sony                 | 19       | 0.85%   |
| HannStar             | 18       | 0.8%    |
| Vestel Elektronik    | 12       | 0.54%   |
| Medion               | 12       | 0.54%   |
| Vizio                | 11       | 0.49%   |
| Toshiba              | 11       | 0.49%   |
| Unknown              | 9        | 0.4%    |
| Packard Bell         | 9        | 0.4%    |
| MStar                | 9        | 0.4%    |
| Belinea              | 9        | 0.4%    |
| Sceptre Tech         | 8        | 0.36%   |
| ___                  | 5        | 0.22%   |
| Sharp                | 5        | 0.22%   |
| Panasonic            | 5        | 0.22%   |
| RTK                  | 4        | 0.18%   |
| OEM                  | 4        | 0.18%   |
| Element              | 4        | 0.18%   |
| Compal               | 4        | 0.18%   |
| Arnos Instruments    | 4        | 0.18%   |
| AMO                  | 4        | 0.18%   |
| Unknown (XXX)        | 3        | 0.13%   |
| RIS                  | 3        | 0.13%   |
| KTC                  | 3        | 0.13%   |
| Insignia             | 3        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 16       | 0.71%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 12       | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10       | 0.44%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 10       | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9        | 0.4%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 9        | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 9        | 0.4%    |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 9        | 0.4%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 8        | 0.35%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 8        | 0.35%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 8        | 0.35%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 8        | 0.35%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 7        | 0.31%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 7        | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 7        | 0.31%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 7        | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 7        | 0.31%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 6        | 0.26%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 6        | 0.26%   |
| Goldstar W2240 GSM57A0 1920x1080 477x268mm 21.5-inch                  | 6        | 0.26%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                         | 6        | 0.26%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch   | 5        | 0.22%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 5        | 0.22%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 5        | 0.22%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 5        | 0.22%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 5        | 0.22%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 5        | 0.22%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 5        | 0.22%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 5        | 0.22%   |
| ASUSTek Computer VA249 AUS24C1 1920x1080 527x296mm 23.8-inch          | 5        | 0.22%   |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                        | 5        | 0.22%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 5        | 0.22%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 4        | 0.18%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 4        | 0.18%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 4        | 0.18%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 521x293mm 23.5-inch     | 4        | 0.18%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 4        | 0.18%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch     | 4        | 0.18%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 0.18%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 4        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1071     | 48.57%  |
| 1280x1024 (SXGA)   | 265      | 12.02%  |
| 1680x1050 (WSXGA+) | 181      | 8.21%   |
| 1366x768 (WXGA)    | 134      | 6.08%   |
| 3840x2160 (4K)     | 120      | 5.44%   |
| 1440x900 (WXGA+)   | 116      | 5.26%   |
| 1600x900 (HD+)     | 76       | 3.45%   |
| 2560x1440 (QHD)    | 71       | 3.22%   |
| 1920x1200 (WUXGA)  | 47       | 2.13%   |
| 1360x768           | 40       | 1.81%   |
| 2560x1080          | 15       | 0.68%   |
| 1920x540           | 13       | 0.59%   |
| 1024x768 (XGA)     | 10       | 0.45%   |
| 3440x1440          | 9        | 0.41%   |
| 1600x1200          | 7        | 0.32%   |
| 2560x1600          | 5        | 0.23%   |
| 1280x960           | 5        | 0.23%   |
| 2048x1152          | 3        | 0.14%   |
| 1280x768           | 3        | 0.14%   |
| 1280x720 (HD)      | 3        | 0.14%   |
| 3840x1080          | 2        | 0.09%   |
| 1400x1050          | 2        | 0.09%   |
| 1152x864           | 2        | 0.09%   |
| 3840x1600          | 1        | 0.05%   |
| 2288x1287          | 1        | 0.05%   |
| 2048x1536          | 1        | 0.05%   |
| 1536x2048          | 1        | 0.05%   |
| 1024x600           | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 345      | 15.39%  |
| 21      | 315      | 14.06%  |
| 24      | 243      | 10.84%  |
| 19      | 230      | 10.26%  |
| 27      | 194      | 8.66%   |
| 18      | 163      | 7.27%   |
| 17      | 143      | 6.38%   |
| 22      | 128      | 5.71%   |
| 20      | 95       | 4.24%   |
| 31      | 90       | 4.02%   |
| 15      | 36       | 1.61%   |
| 32      | 27       | 1.2%    |
| 34      | 26       | 1.16%   |
| Unknown | 25       | 1.12%   |
| 84      | 24       | 1.07%   |
| 72      | 20       | 0.89%   |
| 54      | 19       | 0.85%   |
| 40      | 15       | 0.67%   |
| 52      | 12       | 0.54%   |
| 26      | 11       | 0.49%   |
| 25      | 10       | 0.45%   |
| 28      | 8        | 0.36%   |
| 46      | 7        | 0.31%   |
| 74      | 4        | 0.18%   |
| 65      | 4        | 0.18%   |
| 60      | 4        | 0.18%   |
| 39      | 4        | 0.18%   |
| 37      | 4        | 0.18%   |
| 29      | 4        | 0.18%   |
| 49      | 3        | 0.13%   |
| 48      | 3        | 0.13%   |
| 16      | 3        | 0.13%   |
| 58      | 2        | 0.09%   |
| 55      | 2        | 0.09%   |
| 43      | 2        | 0.09%   |
| 42      | 2        | 0.09%   |
| 38      | 2        | 0.09%   |
| 35      | 2        | 0.09%   |
| 33      | 2        | 0.09%   |
| 30      | 2        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 800      | 36.18%  |
| 501-600        | 749      | 33.88%  |
| 301-350        | 172      | 7.78%   |
| 351-400        | 146      | 6.6%    |
| 601-700        | 125      | 5.65%   |
| 1001-1500      | 57       | 2.58%   |
| 701-800        | 55       | 2.49%   |
| 1501-2000      | 49       | 2.22%   |
| 801-900        | 25       | 1.13%   |
| Unknown        | 25       | 1.13%   |
| 901-1000       | 4        | 0.18%   |
| 201-300        | 3        | 0.14%   |
| More than 2000 | 1        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1473     | 67.66%  |
| 16/10   | 345      | 15.85%  |
| 5/4     | 259      | 11.9%   |
| 4/3     | 36       | 1.65%   |
| 21/9    | 26       | 1.19%   |
| 3/2     | 21       | 0.96%   |
| 6/5     | 9        | 0.41%   |
| 32/9    | 4        | 0.18%   |
| 2.01    | 1        | 0.05%   |
| 1.00    | 1        | 0.05%   |
| 0.75    | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 865      | 38.96%  |
| 151-200        | 435      | 19.59%  |
| 141-150        | 263      | 11.85%  |
| 301-350        | 203      | 9.14%   |
| 351-500        | 151      | 6.8%    |
| More than 1000 | 98       | 4.41%   |
| 251-300        | 89       | 4.01%   |
| 501-1000       | 41       | 1.85%   |
| 101-110        | 26       | 1.17%   |
| Unknown        | 25       | 1.13%   |
| 131-140        | 10       | 0.45%   |
| 111-120        | 10       | 0.45%   |
| 91-100         | 2        | 0.09%   |
| 71-80          | 1        | 0.05%   |
| 41-50          | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1607     | 73.78%  |
| 101-120 | 392      | 18%     |
| 1-50    | 97       | 4.45%   |
| 121-160 | 42       | 1.93%   |
| Unknown | 25       | 1.15%   |
| 161-240 | 15       | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2147     | 92.5%   |
| 2     | 129      | 5.56%   |
| 0     | 31       | 1.34%   |
| 3     | 11       | 0.47%   |
| 4     | 2        | 0.09%   |
| 5     | 1        | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1498     | 49.64%  |
| Intel                           | 662      | 21.94%  |
| Qualcomm Atheros                | 258      | 8.55%   |
| Nvidia                          | 83       | 2.75%   |
| Ralink Technology               | 78       | 2.58%   |
| Broadcom                        | 69       | 2.29%   |
| Ralink                          | 52       | 1.72%   |
| TP-Link                         | 34       | 1.13%   |
| Marvell Technology Group        | 28       | 0.93%   |
| Broadcom Limited                | 24       | 0.8%    |
| Qualcomm Atheros Communications | 23       | 0.76%   |
| D-Link System                   | 17       | 0.56%   |
| VIA Technologies                | 15       | 0.5%    |
| D-Link                          | 14       | 0.46%   |
| ZTE WCDMA Technologies MSM      | 11       | 0.36%   |
| Huawei Technologies             | 11       | 0.36%   |
| NetGear                         | 10       | 0.33%   |
| Samsung Electronics             | 9        | 0.3%    |
| Microsoft                       | 9        | 0.3%    |
| ASUSTek Computer                | 9        | 0.3%    |
| 3Com                            | 8        | 0.27%   |
| IMC Networks                    | 7        | 0.23%   |
| Xiaomi                          | 6        | 0.2%    |
| Belkin Components               | 6        | 0.2%    |
| ASIX Electronics                | 6        | 0.2%    |
| MediaTek                        | 5        | 0.17%   |
| Edimax Technology               | 5        | 0.17%   |
| Aquantia                        | 5        | 0.17%   |
| Motorola PCS                    | 4        | 0.13%   |
| Mercucys                        | 3        | 0.1%    |
| Linksys                         | 3        | 0.1%    |
| JMicron Technology              | 3        | 0.1%    |
| DisplayLink                     | 3        | 0.1%    |
| AVM                             | 3        | 0.1%    |
| Wilocity                        | 2        | 0.07%   |
| Wacom                           | 2        | 0.07%   |
| OPPO Electronics                | 2        | 0.07%   |
| Motorola                        | 2        | 0.07%   |
| ICS Advent                      | 2        | 0.07%   |
| IBM                             | 2        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1295     | 39.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 94       | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 78       | 2.37%   |
| Intel I211 Gigabit Network Connection                                  | 61       | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 57       | 1.73%   |
| Intel Ethernet Connection (2) I219-V                                   | 55       | 1.67%   |
| Nvidia MCP61 Ethernet                                                  | 50       | 1.52%   |
| Intel Ethernet Connection I217-LM                                      | 50       | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 48       | 1.46%   |
| Intel 82579V Gigabit Network Connection                                | 48       | 1.46%   |
| Intel Wi-Fi 6 AX200                                                    | 47       | 1.43%   |
| Ralink MT7601U Wireless Adapter                                        | 37       | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 32       | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 30       | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 26       | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 25       | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 23       | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 22       | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 21       | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 20       | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                        | 20       | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 20       | 0.61%   |
| Intel Ethernet Connection I217-V                                       | 19       | 0.58%   |
| Intel Ethernet Controller I225-V                                       | 16       | 0.49%   |
| Ralink RT5370 Wireless Adapter                                         | 15       | 0.46%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 15       | 0.46%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 15       | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 14       | 0.43%   |
| Intel 82574L Gigabit Network Connection                                | 14       | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 13       | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 13       | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 13       | 0.4%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 13       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 13       | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 12       | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 12       | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 12       | 0.36%   |
| Intel Wireless 7265                                                    | 12       | 0.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 12       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 203      | 26.54%  |
| Intel                                 | 159      | 20.78%  |
| Qualcomm Atheros                      | 112      | 14.64%  |
| Ralink Technology                     | 78       | 10.2%   |
| Ralink                                | 52       | 6.8%    |
| TP-Link                               | 33       | 4.31%   |
| Qualcomm Atheros Communications       | 23       | 3.01%   |
| Broadcom                              | 17       | 2.22%   |
| D-Link                                | 14       | 1.83%   |
| Microsoft                             | 9        | 1.18%   |
| ASUSTek Computer                      | 9        | 1.18%   |
| NetGear                               | 8        | 1.05%   |
| IMC Networks                          | 7        | 0.92%   |
| D-Link System                         | 7        | 0.92%   |
| Belkin Components                     | 6        | 0.78%   |
| Edimax Technology                     | 5        | 0.65%   |
| Mercucys                              | 3        | 0.39%   |
| Linksys                               | 3        | 0.39%   |
| AVM                                   | 3        | 0.39%   |
| Wilocity                              | 2        | 0.26%   |
| Wacom                                 | 2        | 0.26%   |
| Guillemot                             | 2        | 0.26%   |
| ZyXEL Communications                  | 1        | 0.13%   |
| ZyDAS                                 | 1        | 0.13%   |
| Sitecom Europe                        | 1        | 0.13%   |
| Micro Star International              | 1        | 0.13%   |
| MediaTek                              | 1        | 0.13%   |
| BUFFALO                               | 1        | 0.13%   |
| Broadcom Limited                      | 1        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 47       | 6.1%    |
| Ralink MT7601U Wireless Adapter                                | 37       | 4.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 32       | 4.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 26       | 3.37%   |
| Qualcomm Atheros AR9271 802.11n                                | 20       | 2.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 20       | 2.59%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 1.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15       | 1.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 15       | 1.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 14       | 1.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 13       | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 13       | 1.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 13       | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12       | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.56%   |
| Intel Wireless 7265                                            | 12       | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12       | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 11       | 1.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 10       | 1.3%    |
| Realtek 802.11ac NIC                                           | 10       | 1.3%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 10       | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 10       | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 10       | 1.3%    |
| Intel Wireless 7260                                            | 10       | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 9        | 1.17%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 9        | 1.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 9        | 1.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 9        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8        | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7        | 0.91%   |
| Intel Wireless 8260                                            | 7        | 0.91%   |
| Intel Wireless 3165                                            | 7        | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6        | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 6        | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 6        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5        | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 5        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1440     | 58.82%  |
| Intel                             | 562      | 22.96%  |
| Qualcomm Atheros                  | 158      | 6.45%   |
| Nvidia                            | 83       | 3.39%   |
| Broadcom                          | 52       | 2.12%   |
| Marvell Technology Group          | 28       | 1.14%   |
| Broadcom Limited                  | 23       | 0.94%   |
| VIA Technologies                  | 13       | 0.53%   |
| Huawei Technologies               | 10       | 0.41%   |
| D-Link System                     | 10       | 0.41%   |
| 3Com                              | 8        | 0.33%   |
| Samsung Electronics               | 7        | 0.29%   |
| Xiaomi                            | 6        | 0.25%   |
| ASIX Electronics                  | 6        | 0.25%   |
| Aquantia                          | 5        | 0.2%    |
| ZTE WCDMA Technologies MSM        | 4        | 0.16%   |
| Motorola PCS                      | 4        | 0.16%   |
| MediaTek                          | 4        | 0.16%   |
| JMicron Technology                | 3        | 0.12%   |
| DisplayLink                       | 3        | 0.12%   |
| TP-Link                           | 2        | 0.08%   |
| OPPO Electronics                  | 2        | 0.08%   |
| NetGear                           | 2        | 0.08%   |
| ICS Advent                        | 2        | 0.08%   |
| Davicom Semiconductor             | 2        | 0.08%   |
| T & A Mobile Phones               | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.04%   |
| LG Electronics                    | 1        | 0.04%   |
| IBM                               | 1        | 0.04%   |
| HMD Global                        | 1        | 0.04%   |
| Foxconn / Hon Hai                 | 1        | 0.04%   |
| Apple                             | 1        | 0.04%   |
| Accton Technology                 | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1295     | 51.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 94       | 3.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 78       | 3.12%   |
| Intel I211 Gigabit Network Connection                                  | 61       | 2.44%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 57       | 2.28%   |
| Intel Ethernet Connection (2) I219-V                                   | 55       | 2.2%    |
| Nvidia MCP61 Ethernet                                                  | 50       | 2%      |
| Intel Ethernet Connection I217-LM                                      | 50       | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 48       | 1.92%   |
| Intel 82579V Gigabit Network Connection                                | 48       | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 30       | 1.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 25       | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 23       | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                      | 22       | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                   | 21       | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 20       | 0.8%    |
| Intel Ethernet Connection I217-V                                       | 19       | 0.76%   |
| Intel Ethernet Controller I225-V                                       | 16       | 0.64%   |
| Intel 82574L Gigabit Network Connection                                | 14       | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 13       | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 13       | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 12       | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 11       | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11       | 0.44%   |
| Intel Ethernet Connection (2) I218-V                                   | 11       | 0.44%   |
| Intel 82578DM Gigabit Network Connection                               | 11       | 0.44%   |
| Intel 82578DC Gigabit Network Connection                               | 11       | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 10       | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 9        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 9        | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 8        | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7        | 0.28%   |
| Nvidia MCP77 Ethernet                                                  | 7        | 0.28%   |
| Nvidia CK804 Ethernet Controller                                       | 7        | 0.28%   |
| Intel Ethernet Connection (7) I219-LM                                  | 7        | 0.28%   |
| Huawei E353/E3131                                                      | 7        | 0.28%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express        | 7        | 0.28%   |
| Nvidia MCP55 Ethernet                                                  | 6        | 0.24%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 6        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2300     | 75.19%  |
| WiFi     | 737      | 24.09%  |
| Modem    | 17       | 0.56%   |
| Unknown  | 5        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1958     | 86.03%  |
| WiFi     | 317      | 13.93%  |
| Modem    | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1729     | 74.43%  |
| 2     | 532      | 22.9%   |
| 3     | 43       | 1.85%   |
| 0     | 14       | 0.6%    |
| 4     | 3        | 0.13%   |
| 7     | 1        | 0.04%   |
| 5     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 1819     | 77.97%  |
| Yes     | 513      | 21.99%  |
| Unknown | 1        | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 154      | 34.68%  |
| Intel                           | 139      | 31.31%  |
| ASUSTek Computer                | 35       | 7.88%   |
| Realtek Semiconductor           | 32       | 7.21%   |
| Broadcom                        | 27       | 6.08%   |
| Qualcomm Atheros Communications | 16       | 3.6%    |
| IMC Networks                    | 10       | 2.25%   |
| Lite-On Technology              | 8        | 1.8%    |
| Integrated System Solution      | 6        | 1.35%   |
| Belkin Components               | 4        | 0.9%    |
| Ralink                          | 2        | 0.45%   |
| Hewlett-Packard                 | 2        | 0.45%   |
| Dynex                           | 2        | 0.45%   |
| Unknown                         | 1        | 0.23%   |
| SiW                             | 1        | 0.23%   |
| Realtek                         | 1        | 0.23%   |
| Micro Star International        | 1        | 0.23%   |
| i.Tech Dynamic Limited          | 1        | 0.23%   |
| Foxconn / Hon Hai               | 1        | 0.23%   |
| Apple                           | 1        | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 154      | 34.68%  |
| Intel Bluetooth wireless interface                       | 42       | 9.46%   |
| Intel AX200 Bluetooth                                    | 41       | 9.23%   |
| Intel Wireless-AC 3168 Bluetooth                         | 21       | 4.73%   |
| Realtek Bluetooth Radio                                  | 19       | 4.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 15       | 3.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 15       | 3.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 13       | 2.93%   |
| Realtek  Bluetooth 4.2 Adapter                           | 8        | 1.8%    |
| IMC Networks Bluetooth Radio                             | 8        | 1.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 8        | 1.8%    |
| ASUS Bluetooth Radio                                     | 8        | 1.8%    |
| Qualcomm Atheros  Bluetooth Device                       | 6        | 1.35%   |
| Lite-On Bluetooth Device                                 | 6        | 1.35%   |
| ASUS Bluetooth Adapter                                   | 6        | 1.35%   |
| Intel AX201 Bluetooth                                    | 5        | 1.13%   |
| Broadcom BCM2045 Bluetooth                               | 5        | 1.13%   |
| ASUS Qualcomm Bluetooth 4.1                              | 5        | 1.13%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 4        | 0.9%    |
| Integrated System Solution Bluetooth Device              | 4        | 0.9%    |
| Broadcom BCM2035 Bluetooth dongle                        | 3        | 0.68%   |
| ASUS BCM20702A0                                          | 3        | 0.68%   |
| Realtek 802.11ac WLAN Adapter                            | 2        | 0.45%   |
| Ralink RT3290 Bluetooth                                  | 2        | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 0.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.45%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 2        | 0.45%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 2        | 0.45%   |
| Broadcom Bluetooth 2.0+EDR dongle                        | 2        | 0.45%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 2        | 0.45%   |
| Belkin Components Bluetooth Mini Dongle                  | 2        | 0.45%   |
| ASUS Bluetooth Device                                    | 2        | 0.45%   |
| ASUS ASUS USB-BT500                                      | 2        | 0.45%   |
| Unknown Bluetooth Device                                 | 1        | 0.23%   |
| SiW SiW                                                  | 1        | 0.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1        | 0.23%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.23%   |
| Realtek RTL8723B Bluetooth                               | 1        | 0.23%   |
| Realtek Bluetooth Radio                                  | 1        | 0.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 1449     | 41.75%  |
| AMD                                             | 907      | 26.13%  |
| Nvidia                                          | 819      | 23.6%   |
| C-Media Electronics                             | 75       | 2.16%   |
| Creative Labs                                   | 63       | 1.82%   |
| VIA Technologies                                | 18       | 0.52%   |
| Logitech                                        | 16       | 0.46%   |
| Texas Instruments                               | 15       | 0.43%   |
| JMTek                                           | 12       | 0.35%   |
| Generalplus Technology                          | 10       | 0.29%   |
| ASUSTek Computer                                | 7        | 0.2%    |
| Creative Technology                             | 5        | 0.14%   |
| Yamaha                                          | 4        | 0.12%   |
| Tenx Technology                                 | 4        | 0.12%   |
| Razer USA                                       | 3        | 0.09%   |
| M-Audio                                         | 3        | 0.09%   |
| Giga-Byte Technology                            | 3        | 0.09%   |
| Ensoniq                                         | 3        | 0.09%   |
| Syntek                                          | 2        | 0.06%   |
| SAVITECH                                        | 2        | 0.06%   |
| Samson Technologies                             | 2        | 0.06%   |
| PreSonus Audio Electronics                      | 2        | 0.06%   |
| Meizu                                           | 2        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.06%   |
| GYROCOM C&C                                     | 2        | 0.06%   |
| GN Netcom                                       | 2        | 0.06%   |
| Focusrite-Novation                              | 2        | 0.06%   |
| Dell                                            | 2        | 0.06%   |
| Bose                                            | 2        | 0.06%   |
| XMOS                                            | 1        | 0.03%   |
| UCQ01000                                        | 1        | 0.03%   |
| Turtle Beach                                    | 1        | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.03%   |
| SteelSeries ApS                                 | 1        | 0.03%   |
| Sony                                            | 1        | 0.03%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.03%   |
| ROCCAT                                          | 1        | 0.03%   |
| QinHeng Electronics                             | 1        | 0.03%   |
| PS Audio                                        | 1        | 0.03%   |
| Nordic Semiconductor ASA                        | 1        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 244      | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 231      | 5.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 207      | 5.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 179      | 4.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 159      | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 148      | 3.63%   |
| AMD FCH Azalia Controller                                                         | 144      | 3.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 108      | 2.65%   |
| Nvidia High Definition Audio Controller                                           | 104      | 2.55%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 101      | 2.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 97       | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 95       | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                                          | 91       | 2.23%   |
| Intel 200 Series PCH HD Audio                                                     | 82       | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 76       | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 63       | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 62       | 1.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 62       | 1.52%   |
| Nvidia GF119 HDMI Audio Controller                                                | 60       | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 58       | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                     | 57       | 1.4%    |
| Nvidia MCP61 High Definition Audio                                                | 53       | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                        | 52       | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 52       | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 51       | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 48       | 1.18%   |
| Nvidia GK107 HDMI Audio Controller                                                | 46       | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 44       | 1.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 44       | 1.08%   |
| AMD Trinity HDMI Audio Controller                                                 | 38       | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 37       | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                                     | 33       | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                          | 33       | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 33       | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                     | 31       | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 30       | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                     | 28       | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 28       | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 28       | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 26       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 622      | 22.97%  |
| Kingston            | 504      | 18.61%  |
| Samsung Electronics | 282      | 10.41%  |
| SK hynix            | 214      | 7.9%    |
| Corsair             | 198      | 7.31%   |
| Crucial             | 177      | 6.54%   |
| Micron Technology   | 132      | 4.87%   |
| G.Skill             | 125      | 4.62%   |
| A-DATA Technology   | 50       | 1.85%   |
| Nanya Technology    | 49       | 1.81%   |
| Patriot             | 32       | 1.18%   |
| Goodram             | 30       | 1.11%   |
| Team                | 24       | 0.89%   |
| Elpida              | 23       | 0.85%   |
| Unknown             | 17       | 0.63%   |
| Ramaxel Technology  | 16       | 0.59%   |
| Apacer              | 15       | 0.55%   |
| Smart               | 14       | 0.52%   |
| Transcend           | 13       | 0.48%   |
| Kingmax             | 12       | 0.44%   |
| GeIL                | 10       | 0.37%   |
| AMD                 | 10       | 0.37%   |
| Unknown (ABCD)      | 8        | 0.3%    |
| Unifosa             | 8        | 0.3%    |
| Silicon Power       | 7        | 0.26%   |
| Qimonda             | 6        | 0.22%   |
| Multilaser          | 5        | 0.18%   |
| Kreton              | 5        | 0.18%   |
| Avant               | 5        | 0.18%   |
| Teikon              | 4        | 0.15%   |
| TakeMS              | 4        | 0.15%   |
| PNY                 | 4        | 0.15%   |
| H                   | 4        | 0.15%   |
| Atermiter           | 4        | 0.15%   |
| Unknown (AB)        | 3        | 0.11%   |
| Toshiba             | 3        | 0.11%   |
| PLEXHD              | 3        | 0.11%   |
| OCZ                 | 3        | 0.11%   |
| Infineon            | 3        | 0.11%   |
| Goldkey             | 3        | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                    | 46       | 1.51%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 41       | 1.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 39       | 1.28%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 35       | 1.15%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 33       | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 28       | 0.92%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 25       | 0.82%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 21       | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 20       | 0.66%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 19       | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 19       | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 18       | 0.59%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 18       | 0.59%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 17       | 0.56%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s         | 17       | 0.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 17       | 0.56%   |
| Unknown                                                | 17       | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 16       | 0.53%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 15       | 0.49%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 15       | 0.49%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s  | 15       | 0.49%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 14       | 0.46%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s | 14       | 0.46%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s  | 14       | 0.46%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 13       | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 13       | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 13       | 0.43%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 13       | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 12       | 0.39%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 12       | 0.39%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 12       | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 12       | 0.39%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 12       | 0.39%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s  | 12       | 0.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 12       | 0.39%   |
| Unknown RAM Module 2GB DIMM                            | 11       | 0.36%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 11       | 0.36%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s    | 11       | 0.36%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 11       | 0.36%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 11       | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 1043     | 44.03%  |
| DDR4    | 616      | 26%     |
| Unknown | 272      | 11.48%  |
| DDR2    | 203      | 8.57%   |
| SDRAM   | 179      | 7.56%   |
| DDR     | 43       | 1.82%   |
| LPDDR4  | 9        | 0.38%   |
| LPDDR3  | 2        | 0.08%   |
| DRAM    | 1        | 0.04%   |
| DDR5    | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 2190     | 95.59%  |
| SODIMM  | 96       | 4.19%   |
| RIMM    | 4        | 0.17%   |
| FB-DIMM | 1        | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 882      | 33.49%  |
| 8192  | 689      | 26.16%  |
| 2048  | 650      | 24.68%  |
| 1024  | 204      | 7.74%   |
| 16384 | 149      | 5.66%   |
| 512   | 31       | 1.18%   |
| 32768 | 25       | 0.95%   |
| 3072  | 1        | 0.04%   |
| 256   | 1        | 0.04%   |
| 64    | 1        | 0.04%   |
| 32    | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 593      | 22.27%  |
| 1333    | 472      | 17.72%  |
| 800     | 180      | 6.76%   |
| 667     | 128      | 4.81%   |
| 2400    | 124      | 4.66%   |
| Unknown | 108      | 4.06%   |
| 2133    | 100      | 3.76%   |
| 2667    | 92       | 3.45%   |
| 3600    | 85       | 3.19%   |
| 3200    | 71       | 2.67%   |
| 1867    | 62       | 2.33%   |
| 1800    | 53       | 1.99%   |
| 1866    | 47       | 1.76%   |
| 1066    | 47       | 1.76%   |
| 400     | 37       | 1.39%   |
| 1067    | 36       | 1.35%   |
| 3400    | 31       | 1.16%   |
| 2933    | 31       | 1.16%   |
| 533     | 28       | 1.05%   |
| 3000    | 24       | 0.9%    |
| 2666    | 22       | 0.83%   |
| 3733    | 17       | 0.64%   |
| 3800    | 16       | 0.6%    |
| 1334    | 16       | 0.6%    |
| 2048    | 14       | 0.53%   |
| 3466    | 13       | 0.49%   |
| 3266    | 13       | 0.49%   |
| 3066    | 13       | 0.49%   |
| 333     | 12       | 0.45%   |
| 4000    | 11       | 0.41%   |
| 2800    | 11       | 0.41%   |
| 1648    | 11       | 0.41%   |
| 2000    | 10       | 0.38%   |
| 1331    | 10       | 0.38%   |
| 2200    | 9        | 0.34%   |
| 49926   | 8        | 0.3%    |
| 3151    | 7        | 0.26%   |
| 3500    | 6        | 0.23%   |
| 3334    | 6        | 0.23%   |
| 2866    | 6        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 70       | 46.05%  |
| Brother Industries    | 27       | 17.76%  |
| Canon                 | 18       | 11.84%  |
| Samsung Electronics   | 16       | 10.53%  |
| Seiko Epson           | 14       | 9.21%   |
| Dymo-CoStar           | 2        | 1.32%   |
| Xerox                 | 1        | 0.66%   |
| Ricoh                 | 1        | 0.66%   |
| Prolific Technology   | 1        | 0.66%   |
| Oki Data              | 1        | 0.66%   |
| Lexmark International | 1        | 0.66%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP DeskJet 2620 All-in-One Printer                         | 5        | 3.23%   |
| HP LaserJet P1006                                          | 4        | 2.58%   |
| HP DeskJet 3630 series                                     | 4        | 2.58%   |
| Samsung M2020 Series                                       | 3        | 1.94%   |
| Seiko Epson XP-243 245 247 Series                          | 2        | 1.29%   |
| Seiko Epson ET-2600 Series                                 | 2        | 1.29%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.29%   |
| Samsung M2070 Series                                       | 2        | 1.29%   |
| HP OfficeJet Pro 6960                                      | 2        | 1.29%   |
| HP LaserJet P1102                                          | 2        | 1.29%   |
| HP ENVY 4520 series                                        | 2        | 1.29%   |
| HP Deskjet F4500 series                                    | 2        | 1.29%   |
| HP DeskJet 916C                                            | 2        | 1.29%   |
| HP DeskJet 845c                                            | 2        | 1.29%   |
| HP DeskJet 840c                                            | 2        | 1.29%   |
| HP Deskjet 3520 series                                     | 2        | 1.29%   |
| HP DeskJet 2700 series                                     | 2        | 1.29%   |
| HP DeskJet 2130 series                                     | 2        | 1.29%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.29%   |
| Canon PIXMA MG3600 Series                                  | 2        | 1.29%   |
| Brother Printer                                            | 2        | 1.29%   |
| Brother DCP-1610W                                          | 2        | 1.29%   |
| Xerox B215                                                 | 1        | 0.65%   |
| Seiko Epson XP-4100 Series                                 | 1        | 0.65%   |
| Seiko Epson WF-2530 Series                                 | 1        | 0.65%   |
| Seiko Epson USB2.0 Printer                                 | 1        | 0.65%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F     | 1        | 0.65%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series              | 1        | 0.65%   |
| Seiko Epson L375 Series                                    | 1        | 0.65%   |
| Seiko Epson L365 Series                                    | 1        | 0.65%   |
| Seiko Epson L120 Series                                    | 1        | 0.65%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.65%   |
| Seiko Epson EPSON WF-2510 Series                           | 1        | 0.65%   |
| Samsung SCX-4650 4x21S Series                              | 1        | 0.65%   |
| Samsung SCX-4300 Series                                    | 1        | 0.65%   |
| Samsung SCX-4200 series                                    | 1        | 0.65%   |
| Samsung SCX-3200 Series                                    | 1        | 0.65%   |
| Samsung ML-1710 Printer                                    | 1        | 0.65%   |
| Samsung ML-1670 Series                                     | 1        | 0.65%   |
| Samsung ML-1660 Series                                     | 1        | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 20       | 48.78%  |
| Hewlett-Packard             | 9        | 21.95%  |
| Seiko Epson                 | 4        | 9.76%   |
| Mustek Systems              | 4        | 9.76%   |
| AGFA-Gevaert NV             | 2        | 4.88%   |
| Plustek                     | 1        | 2.44%   |
| KYE Systems (Mouse Systems) | 1        | 2.44%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 5        | 12.2%   |
| Mustek Systems ScanExpress 1200 UB                       | 2        | 4.88%   |
| HP ScanJet 4500C/5550C                                   | 2        | 4.88%   |
| Canon CanoScan LiDE 70                                   | 2        | 4.88%   |
| Canon CanoScan LIDE 25                                   | 2        | 4.88%   |
| Canon CanoScan LiDE 120                                  | 2        | 4.88%   |
| Canon CanoScan LiDE 110                                  | 2        | 4.88%   |
| Canon CanoScan LiDE 100                                  | 2        | 4.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1        | 2.44%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 2.44%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 2.44%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1        | 2.44%   |
| Plustek 600DPI USB Scanner                               | 1        | 2.44%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1        | 2.44%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1        | 2.44%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 2.44%   |
| HP ScanJet G4010                                         | 1        | 2.44%   |
| HP ScanJet 4370                                          | 1        | 2.44%   |
| HP ScanJet 3800c                                         | 1        | 2.44%   |
| HP ScanJet 3670                                          | 1        | 2.44%   |
| HP ScanJet 2300c                                         | 1        | 2.44%   |
| HP ScanJet 2200c                                         | 1        | 2.44%   |
| HP PSC 1200                                              | 1        | 2.44%   |
| Canon CanoScan N650U/N656U                               | 1        | 2.44%   |
| Canon CanoScan LiDE 700F                                 | 1        | 2.44%   |
| Canon CanoScan LiDE 500F                                 | 1        | 2.44%   |
| Canon CanoScan LiDE 220                                  | 1        | 2.44%   |
| Canon CanoScan LiDE 200                                  | 1        | 2.44%   |
| AGFA-Gevaert NV SnapScan Touch                           | 1        | 2.44%   |
| AGFA-Gevaert NV SnapScan e20                             | 1        | 2.44%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 114      | 35.19%  |
| Microdia                      | 30       | 9.26%   |
| Microsoft                     | 24       | 7.41%   |
| Z-Star Microelectronics       | 15       | 4.63%   |
| GEMBIRD                       | 13       | 4.01%   |
| Chicony Electronics           | 12       | 3.7%    |
| Aveo Technology               | 9        | 2.78%   |
| Sunplus Innovation Technology | 7        | 2.16%   |
| Realtek Semiconductor         | 7        | 2.16%   |
| Cubeternet                    | 7        | 2.16%   |
| Creative Technology           | 7        | 2.16%   |
| Samsung Electronics           | 5        | 1.54%   |
| KYE Systems (Mouse Systems)   | 5        | 1.54%   |
| Huawei Technologies           | 5        | 1.54%   |
| Generalplus Technology        | 5        | 1.54%   |
| ARC International             | 5        | 1.54%   |
| Jieli Technology              | 4        | 1.23%   |
| Trust                         | 3        | 0.93%   |
| Pixart Imaging                | 3        | 0.93%   |
| Genesys Logic                 | 3        | 0.93%   |
| Arkmicro Technologies         | 3        | 0.93%   |
| Apple                         | 3        | 0.93%   |
| Alcor Micro                   | 3        | 0.93%   |
| A4Tech                        | 3        | 0.93%   |
| WCM_USB                       | 2        | 0.62%   |
| Unknown                       | 2        | 0.62%   |
| Sweex                         | 2        | 0.62%   |
| Sonix Technology              | 2        | 0.62%   |
| Silicon Motion                | 2        | 0.62%   |
| MacroSilicon                  | 2        | 0.62%   |
| YGTek                         | 1        | 0.31%   |
| Xiongmai                      | 1        | 0.31%   |
| WaveRider Communications      | 1        | 0.31%   |
| Tobii Technology AB           | 1        | 0.31%   |
| Teslong Camera                | 1        | 0.31%   |
| Spreadtrum Communications     | 1        | 0.31%   |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 0.31%   |
| Sanyo Electric                | 1        | 0.31%   |
| Linux Foundation              | 1        | 0.31%   |
| LG Electronics                | 1        | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 25       | 7.72%   |
| Logitech Webcam C310                              | 17       | 5.25%   |
| Logitech HD Pro Webcam C920                       | 17       | 5.25%   |
| Logitech Webcam C170                              | 11       | 3.4%    |
| Microdia Camera                                   | 9        | 2.78%   |
| Microsoft LifeCam HD-3000                         | 7        | 2.16%   |
| Logitech HD Webcam C525                           | 7        | 2.16%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 7        | 2.16%   |
| Microdia Webcam Vitade AF                         | 6        | 1.85%   |
| Logitech QuickCam Pro 9000                        | 6        | 1.85%   |
| GEMBIRD USB2.0 PC CAMERA                          | 6        | 1.85%   |
| Aveo USB2.0 Camera                                | 6        | 1.85%   |
| Z-Star Vimicro USB Camera (Altair)                | 5        | 1.54%   |
| Samsung Galaxy series, misc. (MTP mode)           | 5        | 1.54%   |
| Huawei HiCamera                                   | 5        | 1.54%   |
| Cubeternet USB2.0 Camera                          | 5        | 1.54%   |
| ARC International Camera                          | 5        | 1.54%   |
| Microsoft LifeCam Cinema                          | 4        | 1.23%   |
| Microdia USB 2.0 Camera                           | 4        | 1.23%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 1.23%   |
| Microdia Integrated Camera                        | 4        | 1.23%   |
| Jieli USB PHY 2.0                                 | 4        | 1.23%   |
| Generalplus GENERAL WEBCAM                        | 4        | 1.23%   |
| Z-Star Venus USB2.0 Camera                        | 3        | 0.93%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 3        | 0.93%   |
| Realtek FULL HD 1080P Webcam                      | 3        | 0.93%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 3        | 0.93%   |
| Microsoft LifeCam VX-5000                         | 3        | 0.93%   |
| Logitech Webcam C300                              | 3        | 0.93%   |
| Creative Live! Cam Sync HD [VF0770]               | 3        | 0.93%   |
| Chicony HP High Definition 1MP Webcam             | 3        | 0.93%   |
| Arkmicro USB2.0 PC CAMERA                         | 3        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 3        | 0.93%   |
| Alcor Micro USB 2.0 PC Camera                     | 3        | 0.93%   |
| Z-Star A4 TECH HD PC Camera                       | 2        | 0.62%   |
| WCM_USB WEB CAM                                   | 2        | 0.62%   |
| Sweex WC060 Series HD Webcam                      | 2        | 0.62%   |
| Sunplus USB Camera                                | 2        | 0.62%   |
| Sunplus HD 720P webcam                            | 2        | 0.62%   |
| Sunplus DICOTA 4K                                 | 2        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 33.33%  |
| Upek             | 1        | 33.33%  |
| AuthenTec        | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 33.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 33.33%  |
| AuthenTec AES1600                                      | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 5        | 35.71%  |
| OmniKey                           | 2        | 14.29%  |
| VASCO Data Security International | 1        | 7.14%   |
| SCM Microsystems                  | 1        | 7.14%   |
| Reiner SCT Kartensysteme          | 1        | 7.14%   |
| Fujitsu Siemens Computers         | 1        | 7.14%   |
| CHERRY                            | 1        | 7.14%   |
| Bit4id                            | 1        | 7.14%   |
| Advanced Card Systems             | 1        | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 21.43%  |
| Alcor Micro Watchdata W 1981                                               | 2        | 14.29%  |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 7.14%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 7.14%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 7.14%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 7.14%   |
| OmniKey CardMan 1021                                                       | 1        | 7.14%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 7.14%   |
| CHERRY SmartTerminal ST-2xxx                                               | 1        | 7.14%   |
| Bit4id miniLector EVO                                                      | 1        | 7.14%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2082     | 89.63%  |
| 1     | 226      | 9.73%   |
| 2     | 13       | 0.56%   |
| 3     | 2        | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 129      | 50.79%  |
| Net/wireless             | 49       | 19.29%  |
| Multimedia controller    | 15       | 5.91%   |
| Communication controller | 14       | 5.51%   |
| Chipcard                 | 12       | 4.72%   |
| Unassigned class         | 11       | 4.33%   |
| Camera                   | 6        | 2.36%   |
| Fingerprint reader       | 3        | 1.18%   |
| Card reader              | 3        | 1.18%   |
| Storage/ata              | 2        | 0.79%   |
| Sound                    | 2        | 0.79%   |
| Network                  | 2        | 0.79%   |
| Modem                    | 2        | 0.79%   |
| Bluetooth                | 2        | 0.79%   |
| Unclassified device      | 1        | 0.39%   |
| Net/ethernet             | 1        | 0.39%   |

