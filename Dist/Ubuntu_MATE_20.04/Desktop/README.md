Ubuntu MATE 20.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-mate-20.04

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H110M-STX                   | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| HP            | 3396                        | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| ASRock        | H110M-STX                   | [a0b807eb42](https://linux-hardware.org/?probe=a0b807eb42) | Aug 30, 2021 |
| MSI           | Z370 PC PRO                 | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| ASRock        | M3A785GMH/128M              | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| MSI           | X79A-GD45                   | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Dell          | 05GD68 A00                  | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | [fe0cf5b120](https://linux-hardware.org/?probe=fe0cf5b120) | Aug 01, 2021 |
| Dell          | 08NPPY A00                  | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| MSI           | H61M-E33                    | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [011a83c682](https://linux-hardware.org/?probe=011a83c682) | Jul 17, 2021 |
| Unknown       | TB-4000                     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| Dell          | 05GD68 A00                  | [ebd157141b](https://linux-hardware.org/?probe=ebd157141b) | Jul 08, 2021 |
| Gigabyte      | H81M-S1                     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| ASUSTek       | Z170-AR                     | [37343856a5](https://linux-hardware.org/?probe=37343856a5) | Jul 02, 2021 |
| Dell          | 05GD68 A00                  | [9bb3c8dbe9](https://linux-hardware.org/?probe=9bb3c8dbe9) | Jul 02, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| HP            | 1495                        | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| eMachines     | EL1352                      | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| ASUSTek       | P8B75-M                     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Dell          | 0KRC95 A00                  | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| Dell          | 02YYK5 A01                  | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | Board                       | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| ASUSTek       | M2N68-AM Plus               | [7761ccf4be](https://linux-hardware.org/?probe=7761ccf4be) | May 07, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| Dell          | 0F6X5P A00                  | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| HP            | 3397                        | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| ASRock        | H310M-STX                   | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f3ac6366a6](https://linux-hardware.org/?probe=f3ac6366a6) | Mar 24, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4d7e0c9e41](https://linux-hardware.org/?probe=4d7e0c9e41) | Mar 23, 2021 |
| Lenovo        | SHARKBAY NOK                | [e9b0291347](https://linux-hardware.org/?probe=e9b0291347) | Mar 21, 2021 |
| HP            | 1497                        | [d35a7eef80](https://linux-hardware.org/?probe=d35a7eef80) | Mar 19, 2021 |
| Intel         | DH61WW AAG23116-203         | [e4faf817fd](https://linux-hardware.org/?probe=e4faf817fd) | Mar 19, 2021 |
| MSI           | MAG B550M MORTAR            | [9210657e45](https://linux-hardware.org/?probe=9210657e45) | Mar 17, 2021 |
| ASRock        | 960GM-S3 FX                 | [5784a74c50](https://linux-hardware.org/?probe=5784a74c50) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| Dell          | 03NVJ6 A00                  | [2b8f8e4cec](https://linux-hardware.org/?probe=2b8f8e4cec) | Mar 14, 2021 |
| MSI           | B85M-P33                    | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | [957f68f2b7](https://linux-hardware.org/?probe=957f68f2b7) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | [839bc4873c](https://linux-hardware.org/?probe=839bc4873c) | Mar 08, 2021 |
| MSI           | Z370-A PRO                  | [b5cf5849a1](https://linux-hardware.org/?probe=b5cf5849a1) | Mar 06, 2021 |
| HP            | 2B2C                        | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [e4437002b3](https://linux-hardware.org/?probe=e4437002b3) | Mar 04, 2021 |
| Medion        | B460H6-EM                   | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| Dell          | 03NVJ6 A00                  | [f1349be70a](https://linux-hardware.org/?probe=f1349be70a) | Feb 19, 2021 |
| Unknown       | XH61X000.100                | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| JINGSHA       | Board                       | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
| Dell          | 03NVJ6 A00                  | [87f43dfecd](https://linux-hardware.org/?probe=87f43dfecd) | Feb 12, 2021 |
| MSI           | B85M GAMING                 | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| Gigabyte      | MZBAYAB-00                  | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| HP            | ProLiant MicroServer        | [394af8312b](https://linux-hardware.org/?probe=394af8312b) | Feb 07, 2021 |
| HP            | ProLiant MicroServer        | [0e61287ad7](https://linux-hardware.org/?probe=0e61287ad7) | Feb 07, 2021 |
| Gateway       | DX4885                      | [48628b0b95](https://linux-hardware.org/?probe=48628b0b95) | Feb 03, 2021 |
| Gigabyte      | H61M-D2H-USB3               | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| Intel         | H61M-S1                     | [38a03ee5be](https://linux-hardware.org/?probe=38a03ee5be) | Jan 31, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [20d082d72c](https://linux-hardware.org/?probe=20d082d72c) | Jan 26, 2021 |
| ASUSTek       | LITHIUM                     | [e2c8ad85fb](https://linux-hardware.org/?probe=e2c8ad85fb) | Jan 24, 2021 |
| ASUSTek       | LITHIUM                     | [3f3f25d596](https://linux-hardware.org/?probe=3f3f25d596) | Jan 24, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [4695d8c639](https://linux-hardware.org/?probe=4695d8c639) | Jan 24, 2021 |
| ASUSTek       | P5N-D                       | [cac7f8ae52](https://linux-hardware.org/?probe=cac7f8ae52) | Jan 23, 2021 |
| ASUSTek       | P5N-D                       | [b637c75d21](https://linux-hardware.org/?probe=b637c75d21) | Jan 23, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Dell          | 0200DY A03                  | [5e5ca98e54](https://linux-hardware.org/?probe=5e5ca98e54) | Jan 13, 2021 |
| ASUSTek       | P8Z68-V PRO                 | [86c7eb6c5b](https://linux-hardware.org/?probe=86c7eb6c5b) | Jan 11, 2021 |
| ASUSTek       | PRIME B250-PRO              | [474542bd76](https://linux-hardware.org/?probe=474542bd76) | Jan 10, 2021 |
| ASUSTek       | P7P55 LX                    | [d13d4667c3](https://linux-hardware.org/?probe=d13d4667c3) | Jan 09, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| MSI           | H87-G43                     | [8b1363882c](https://linux-hardware.org/?probe=8b1363882c) | Jan 03, 2021 |
| Gigabyte      | Z97-HD3                     | [417a2cbe50](https://linux-hardware.org/?probe=417a2cbe50) | Dec 26, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [46e2c41ee6](https://linux-hardware.org/?probe=46e2c41ee6) | Dec 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9ad04d0568](https://linux-hardware.org/?probe=9ad04d0568) | Dec 16, 2020 |
| ASUSTek       | M5A78L LE                   | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [e9fb6116b3](https://linux-hardware.org/?probe=e9fb6116b3) | Dec 14, 2020 |
| ASUSTek       | M5A78L LE                   | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| HP            | 82A2                        | [8b443d9da5](https://linux-hardware.org/?probe=8b443d9da5) | Dec 12, 2020 |
| HP            | 82A2                        | [58faddeba3](https://linux-hardware.org/?probe=58faddeba3) | Dec 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | [e1d03e259e](https://linux-hardware.org/?probe=e1d03e259e) | Dec 09, 2020 |
| Gigabyte      | EP45T-EXTREME               | [9320edd724](https://linux-hardware.org/?probe=9320edd724) | Dec 07, 2020 |
| Gigabyte      | 945GCM-S2C                  | [eba95d11b5](https://linux-hardware.org/?probe=eba95d11b5) | Dec 04, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [94f75b4e92](https://linux-hardware.org/?probe=94f75b4e92) | Nov 22, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| ASUSTek       | WS C246M PRO Series         | [502bd89093](https://linux-hardware.org/?probe=502bd89093) | Nov 18, 2020 |
| ASUSTek       | WS C246M PRO Series         | [dc20d9cf64](https://linux-hardware.org/?probe=dc20d9cf64) | Nov 17, 2020 |
| Medion        | B360H4-EM V1.0              | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | 0WG864                      | [1c2384097b](https://linux-hardware.org/?probe=1c2384097b) | Nov 15, 2020 |
| HP            | 1790                        | [02138cec8b](https://linux-hardware.org/?probe=02138cec8b) | Nov 08, 2020 |
| HP            | 1905                        | [6f20f6aa7d](https://linux-hardware.org/?probe=6f20f6aa7d) | Nov 08, 2020 |
| Intel         | SLIMBOOK                    | [2250e4a10f](https://linux-hardware.org/?probe=2250e4a10f) | Nov 07, 2020 |
| HP            | 3397                        | [17188b10a3](https://linux-hardware.org/?probe=17188b10a3) | Nov 06, 2020 |
| Pegatron      | NARRA3                      | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| Lenovo        | Board                       | [69bc4fbb1b](https://linux-hardware.org/?probe=69bc4fbb1b) | Oct 30, 2020 |
| HP            | 1493                        | [34134cab7f](https://linux-hardware.org/?probe=34134cab7f) | Oct 30, 2020 |
| HP            | 1493                        | [dd1964d532](https://linux-hardware.org/?probe=dd1964d532) | Oct 30, 2020 |
| HP            | 1497                        | [1d068e5c77](https://linux-hardware.org/?probe=1d068e5c77) | Oct 28, 2020 |
| HP            | 3047h                       | [4f58775069](https://linux-hardware.org/?probe=4f58775069) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [a13afb5c54](https://linux-hardware.org/?probe=a13afb5c54) | Oct 27, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [dd929b231e](https://linux-hardware.org/?probe=dd929b231e) | Oct 26, 2020 |
| ASRock        | G31M-GS                     | [0a9aa8dcd2](https://linux-hardware.org/?probe=0a9aa8dcd2) | Oct 26, 2020 |
| Biostar       | A320MH                      | [8c1edce824](https://linux-hardware.org/?probe=8c1edce824) | Oct 24, 2020 |
| Dell          | 0V6XGW A00                  | [1518ff90f9](https://linux-hardware.org/?probe=1518ff90f9) | Oct 24, 2020 |
| Gigabyte      | H110M-H DDR3-CF             | [ab60c752a9](https://linux-hardware.org/?probe=ab60c752a9) | Oct 23, 2020 |
| HP            | 3047h                       | [ecba048272](https://linux-hardware.org/?probe=ecba048272) | Oct 21, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [658b7105e1](https://linux-hardware.org/?probe=658b7105e1) | Oct 21, 2020 |
| HP            | 3047h                       | [4c9083177a](https://linux-hardware.org/?probe=4c9083177a) | Oct 21, 2020 |
| HP            | 3047h                       | [67e7807767](https://linux-hardware.org/?probe=67e7807767) | Oct 21, 2020 |
| HP            | 3047h                       | [4dd1cde645](https://linux-hardware.org/?probe=4dd1cde645) | Oct 20, 2020 |
| HP            | 3047h                       | [d84da1ea3e](https://linux-hardware.org/?probe=d84da1ea3e) | Oct 20, 2020 |
| HP            | 3047h                       | [134da552c2](https://linux-hardware.org/?probe=134da552c2) | Oct 20, 2020 |
| HP            | 304Ah                       | [3163a2892d](https://linux-hardware.org/?probe=3163a2892d) | Oct 19, 2020 |
| HP            | 3397                        | [8bdef2c49c](https://linux-hardware.org/?probe=8bdef2c49c) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e5aa6a33a6](https://linux-hardware.org/?probe=e5aa6a33a6) | Oct 18, 2020 |
| HP            | 3397                        | [5a6fac5a0f](https://linux-hardware.org/?probe=5a6fac5a0f) | Oct 16, 2020 |
| MSI           | B550M PRO-VDH WIFI          | [2c4fc7773a](https://linux-hardware.org/?probe=2c4fc7773a) | Oct 14, 2020 |
| Dell          | 042P49 A01                  | [44c14427a0](https://linux-hardware.org/?probe=44c14427a0) | Oct 13, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Gigabyte      | A320M-H-CF                  | [2c0322f113](https://linux-hardware.org/?probe=2c0322f113) | Oct 10, 2020 |
| Dell          | 0FR6WH A01                  | [2776ae6a1a](https://linux-hardware.org/?probe=2776ae6a1a) | Oct 09, 2020 |
| Dell          | 0T656F A01                  | [f44db9c73a](https://linux-hardware.org/?probe=f44db9c73a) | Oct 09, 2020 |
| Pegatron      | 2A84h                       | [a8d97c37b7](https://linux-hardware.org/?probe=a8d97c37b7) | Oct 08, 2020 |
| Dell          | 0HN7XN A00                  | [885b19f22a](https://linux-hardware.org/?probe=885b19f22a) | Oct 08, 2020 |
| HP            | 3646h                       | [d5dd5824e3](https://linux-hardware.org/?probe=d5dd5824e3) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | [1f6fe3684d](https://linux-hardware.org/?probe=1f6fe3684d) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | [8872b79e71](https://linux-hardware.org/?probe=8872b79e71) | Oct 07, 2020 |
| Dell          | 0TVR1F A01                  | [3de8c4e65d](https://linux-hardware.org/?probe=3de8c4e65d) | Oct 06, 2020 |
| Dell          | 0TVR1F A01                  | [ae1a5155a6](https://linux-hardware.org/?probe=ae1a5155a6) | Oct 05, 2020 |
| Gigabyte      | B460M DS3H                  | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [16d07f52d6](https://linux-hardware.org/?probe=16d07f52d6) | Sep 29, 2020 |
| HP            | 3047h                       | [8276b976a7](https://linux-hardware.org/?probe=8276b976a7) | Sep 28, 2020 |
| HP            | 1497                        | [3c6ed08ddd](https://linux-hardware.org/?probe=3c6ed08ddd) | Sep 25, 2020 |
| Gigabyte      | H81M-H                      | [21991336a9](https://linux-hardware.org/?probe=21991336a9) | Sep 25, 2020 |
| Dell          | 09M8Y8 A01                  | [7086c0ba36](https://linux-hardware.org/?probe=7086c0ba36) | Sep 25, 2020 |
| Intel         | DG43GT AAE62768-301         | [028847b86e](https://linux-hardware.org/?probe=028847b86e) | Sep 21, 2020 |
| Dell          | 0WX729                      | [f2cc61a6f1](https://linux-hardware.org/?probe=f2cc61a6f1) | Sep 17, 2020 |
| Dell          | 0WX729                      | [4fdbabe245](https://linux-hardware.org/?probe=4fdbabe245) | Sep 17, 2020 |
| Dell          | 0D441T A01                  | [a5c5a78a7c](https://linux-hardware.org/?probe=a5c5a78a7c) | Sep 16, 2020 |
| Dell          | 0TW904                      | [20994a3808](https://linux-hardware.org/?probe=20994a3808) | Sep 15, 2020 |
| Dell          | 0T656F A01                  | [a004d9a942](https://linux-hardware.org/?probe=a004d9a942) | Sep 14, 2020 |
| HP            | 18E7                        | [18852c6be3](https://linux-hardware.org/?probe=18852c6be3) | Sep 11, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [0bba6eaf71](https://linux-hardware.org/?probe=0bba6eaf71) | Sep 11, 2020 |
| Dell          | 0T656F A01                  | [6b43e65d15](https://linux-hardware.org/?probe=6b43e65d15) | Sep 10, 2020 |
| Dell          | 0TVR1F A01                  | [22aaefa03b](https://linux-hardware.org/?probe=22aaefa03b) | Sep 10, 2020 |
| Dell          | 042P49 A01                  | [282331caa5](https://linux-hardware.org/?probe=282331caa5) | Sep 10, 2020 |
| Dell          | 0M5DCD A00                  | [bfc77d64c6](https://linux-hardware.org/?probe=bfc77d64c6) | Sep 09, 2020 |
| Dell          | 0M5DCD A00                  | [d269751a9e](https://linux-hardware.org/?probe=d269751a9e) | Sep 09, 2020 |
| Dell          | 0N820C A02                  | [a43f37d51e](https://linux-hardware.org/?probe=a43f37d51e) | Sep 08, 2020 |
| Gigabyte      | H81M-H                      | [3ae339618d](https://linux-hardware.org/?probe=3ae339618d) | Sep 08, 2020 |
| Gigabyte      | H81M-H                      | [d2f477c7f5](https://linux-hardware.org/?probe=d2f477c7f5) | Sep 08, 2020 |
| Dell          | 0M5DCD A00                  | [c39d1b0af6](https://linux-hardware.org/?probe=c39d1b0af6) | Sep 05, 2020 |
| MSI           | Creator TRX40               | [48149893d7](https://linux-hardware.org/?probe=48149893d7) | Sep 04, 2020 |
| HP            | 3397                        | [e9da9cd17f](https://linux-hardware.org/?probe=e9da9cd17f) | Sep 03, 2020 |
| HP            | 339A                        | [5f29fd9231](https://linux-hardware.org/?probe=5f29fd9231) | Sep 03, 2020 |
| HP            | 3397                        | [a8ea68de6d](https://linux-hardware.org/?probe=a8ea68de6d) | Sep 03, 2020 |
| MSI           | MEG X570 UNIFY              | [7e2dae216d](https://linux-hardware.org/?probe=7e2dae216d) | Sep 03, 2020 |
| Dell          | 03K80F A00                  | [a3452cb614](https://linux-hardware.org/?probe=a3452cb614) | Sep 02, 2020 |
| Dell          | 0HY9JP A00                  | [e797b1bf14](https://linux-hardware.org/?probe=e797b1bf14) | Sep 02, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2b44d73e4b](https://linux-hardware.org/?probe=2b44d73e4b) | Sep 02, 2020 |
| HP            | 1497                        | [edf6c3ecfa](https://linux-hardware.org/?probe=edf6c3ecfa) | Sep 01, 2020 |
| Gigabyte      | H81M-H                      | [b5600f5c06](https://linux-hardware.org/?probe=b5600f5c06) | Aug 31, 2020 |
| Gigabyte      | H81M-H                      | [461e0244f4](https://linux-hardware.org/?probe=461e0244f4) | Aug 31, 2020 |
| Gigabyte      | X58A-UD3R                   | [b26cdf0225](https://linux-hardware.org/?probe=b26cdf0225) | Aug 29, 2020 |
| ASUSTek       | PRIME Z270-P                | [b39122c844](https://linux-hardware.org/?probe=b39122c844) | Aug 25, 2020 |
| ASUSTek       | PRIME X399-A                | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| Toshiba       | STI 010432                  | [7d6c45eed4](https://linux-hardware.org/?probe=7d6c45eed4) | Aug 20, 2020 |
| Toshiba       | STI 010432                  | [da8ae751c9](https://linux-hardware.org/?probe=da8ae751c9) | Aug 20, 2020 |
| ASUSTek       | PRIME Z270-P                | [b5c4317a43](https://linux-hardware.org/?probe=b5c4317a43) | Aug 20, 2020 |
| Intel         | Board                       | [0792f8e763](https://linux-hardware.org/?probe=0792f8e763) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | PRIME Z270-P                | [f3ea863c21](https://linux-hardware.org/?probe=f3ea863c21) | Aug 19, 2020 |
| Toshiba       | STI 010432                  | [844d21cfba](https://linux-hardware.org/?probe=844d21cfba) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [d568758fb5](https://linux-hardware.org/?probe=d568758fb5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [93e07b3103](https://linux-hardware.org/?probe=93e07b3103) | Aug 16, 2020 |
| ASRock        | B450M Pro4                  | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Intel         | Board                       | [501444c3d4](https://linux-hardware.org/?probe=501444c3d4) | Aug 12, 2020 |
| Intel         | Board                       | [aca06096b6](https://linux-hardware.org/?probe=aca06096b6) | Aug 12, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1c6f36de59](https://linux-hardware.org/?probe=1c6f36de59) | Aug 10, 2020 |
| Gigabyte      | H97N-WIFI                   | [608ff52425](https://linux-hardware.org/?probe=608ff52425) | Aug 06, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| ASUSTek       | P9X79 DELUXE                | [bd1790913e](https://linux-hardware.org/?probe=bd1790913e) | Aug 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [8936a7017a](https://linux-hardware.org/?probe=8936a7017a) | Jul 28, 2020 |
| ASUSTek       | P9X79 DELUXE                | [3ee7d0dc49](https://linux-hardware.org/?probe=3ee7d0dc49) | Jul 28, 2020 |
| Gigabyte      | M68MT-S2P                   | [e9661e7816](https://linux-hardware.org/?probe=e9661e7816) | Jul 27, 2020 |
| Intel         | DH87RL AAG74240-402         | [dfb8a55f7f](https://linux-hardware.org/?probe=dfb8a55f7f) | Jul 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | [3ff385285a](https://linux-hardware.org/?probe=3ff385285a) | Jul 26, 2020 |
| Biostar       | G31-M7 TE                   | [6affb516f1](https://linux-hardware.org/?probe=6affb516f1) | Jul 24, 2020 |
| ASUSTek       | AM1M-A                      | [8a3873a0c3](https://linux-hardware.org/?probe=8a3873a0c3) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [3e594f7ff4](https://linux-hardware.org/?probe=3e594f7ff4) | Jul 24, 2020 |
| Dell          | 0200DY A03                  | [9dbcace7db](https://linux-hardware.org/?probe=9dbcace7db) | Jul 21, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [292d396a46](https://linux-hardware.org/?probe=292d396a46) | Jul 21, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c3a79140eb](https://linux-hardware.org/?probe=c3a79140eb) | Jul 18, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| ASUSTek       | P5QPL-AM                    | [bd28d2c132](https://linux-hardware.org/?probe=bd28d2c132) | Jul 13, 2020 |
| HP            | 8434 11                     | [377d6d5aa4](https://linux-hardware.org/?probe=377d6d5aa4) | Jul 10, 2020 |
| Lenovo        | Board                       | [30edd53934](https://linux-hardware.org/?probe=30edd53934) | Jul 09, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [994e71e658](https://linux-hardware.org/?probe=994e71e658) | Jul 03, 2020 |
| MSI           | A78M-E35                    | [baf6228acf](https://linux-hardware.org/?probe=baf6228acf) | Jul 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f7afeb0f26](https://linux-hardware.org/?probe=f7afeb0f26) | Jul 01, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| HP            | ProLiant MicroServer        | [1f2d306b05](https://linux-hardware.org/?probe=1f2d306b05) | Jun 20, 2020 |
| IBM           | Board                       | [28e9762210](https://linux-hardware.org/?probe=28e9762210) | Jun 16, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [02f2a001e1](https://linux-hardware.org/?probe=02f2a001e1) | Jun 11, 2020 |
| ASUSTek       | P5QPL-AM                    | [994e3df746](https://linux-hardware.org/?probe=994e3df746) | Jun 11, 2020 |
| ASRock        | H110M-STX                   | [3c35aef096](https://linux-hardware.org/?probe=3c35aef096) | Jun 10, 2020 |
| Dell          | 0478VN A00                  | [f02bda5144](https://linux-hardware.org/?probe=f02bda5144) | Jun 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [8dbad33afb](https://linux-hardware.org/?probe=8dbad33afb) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASUSTek       | P5QPL-AM                    | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| IBM           | Board                       | [784c83d7d6](https://linux-hardware.org/?probe=784c83d7d6) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| Dell          | 0WF810                      | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Dell          | 0WF810                      | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4806bd297f](https://linux-hardware.org/?probe=4806bd297f) | May 16, 2020 |
| ASRock        | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| Lenovo        | SDK0E50510 WIN 262507961... | [0400e155ee](https://linux-hardware.org/?probe=0400e155ee) | May 10, 2020 |
| Gigabyte      | GA-970A-UD3                 | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9a72c58dee](https://linux-hardware.org/?probe=9a72c58dee) | May 04, 2020 |
| Gigabyte      | GA-A75-D3H                  | [88dd0cfbcb](https://linux-hardware.org/?probe=88dd0cfbcb) | May 02, 2020 |
| Gigabyte      | GA-A75-D3H                  | [530009d42a](https://linux-hardware.org/?probe=530009d42a) | May 02, 2020 |
| Intel         | D946GZIS AAD45436-306       | [483b574b1a](https://linux-hardware.org/?probe=483b574b1a) | Apr 25, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [ba2c3155d7](https://linux-hardware.org/?probe=ba2c3155d7) | Apr 22, 2020 |
| ASUSTek       | P9X79 WS                    | [513772febc](https://linux-hardware.org/?probe=513772febc) | Mar 01, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.4.0-48-generic           | 27       | 13.64%  |
| 5.4.0-52-generic           | 13       | 6.57%   |
| 5.4.0-47-generic           | 13       | 6.57%   |
| 5.4.0-42-generic           | 13       | 6.57%   |
| 5.4.0-45-generic           | 10       | 5.05%   |
| 5.4.0-40-generic           | 8        | 4.04%   |
| 5.4.0-66-generic           | 7        | 3.54%   |
| 5.4.0-65-generic           | 7        | 3.54%   |
| 5.4.0-67-generic           | 6        | 3.03%   |
| 5.4.0-80-generic           | 5        | 2.53%   |
| 5.4.0-29-generic           | 5        | 2.53%   |
| 5.8.0-55-generic           | 4        | 2.02%   |
| 5.4.0-74-generic           | 4        | 2.02%   |
| 5.4.0-56-generic           | 4        | 2.02%   |
| 5.4.0-33-generic           | 4        | 2.02%   |
| 5.8.0-59-generic           | 3        | 1.52%   |
| 5.4.0-81-generic           | 3        | 1.52%   |
| 5.4.0-77-generic           | 3        | 1.52%   |
| 5.4.0-72-generic           | 3        | 1.52%   |
| 5.4.0-62-generic           | 3        | 1.52%   |
| 5.4.0-59-generic           | 3        | 1.52%   |
| 5.4.0-58-generic           | 3        | 1.52%   |
| 5.4.0-26-generic           | 3        | 1.52%   |
| 5.8.0-53-generic           | 2        | 1.01%   |
| 5.4.0-73-generic           | 2        | 1.01%   |
| 5.4.0-70-generic           | 2        | 1.01%   |
| 5.4.0-60-generic           | 2        | 1.01%   |
| 5.4.0-51-generic           | 2        | 1.01%   |
| 5.4.0-37-generic           | 2        | 1.01%   |
| 5.4.0-34-generic           | 2        | 1.01%   |
| 5.11.0-25-generic          | 2        | 1.01%   |
| 5.8.0-57-generic           | 1        | 0.51%   |
| 5.8.0-50-generic           | 1        | 0.51%   |
| 5.8.0-48-generic           | 1        | 0.51%   |
| 5.8.0-45-generic           | 1        | 0.51%   |
| 5.8.0-43-generic           | 1        | 0.51%   |
| 5.8.0-41-generic           | 1        | 0.51%   |
| 5.8.0-40-generic           | 1        | 0.51%   |
| 5.7.6-050706-generic       | 1        | 0.51%   |
| 5.7.0-050700-generic       | 1        | 0.51%   |
| 5.4.0-702104061620-generic | 1        | 0.51%   |
| 5.4.0-64-generic           | 1        | 0.51%   |
| 5.4.0-53-lowlatency        | 1        | 0.51%   |
| 5.4.0-53-generic           | 1        | 0.51%   |
| 5.4.0-52-lowlatency        | 1        | 0.51%   |
| 5.4.0-512010201020-generic | 1        | 0.51%   |
| 5.4.0-48-lowlatency        | 1        | 0.51%   |
| 5.4.0-47-lowlatency        | 1        | 0.51%   |
| 5.4.0-44-generic           | 1        | 0.51%   |
| 5.4.0-43-generic           | 1        | 0.51%   |
| 5.4.0-42-lowlatency        | 1        | 0.51%   |
| 5.4.0-392007061620-generic | 1        | 0.51%   |
| 5.4.0-39-generic           | 1        | 0.51%   |
| 5.4.0-31-generic           | 1        | 0.51%   |
| 5.4.0-25-generic           | 1        | 0.51%   |
| 5.4.0-14-generic           | 1        | 0.51%   |
| 5.11.0-27-generic          | 1        | 0.51%   |
| 5.10.5-051005-generic      | 1        | 0.51%   |
| 5.10.0-1013-oem            | 1        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 158      | 87.29%  |
| 5.8.0   | 16       | 8.84%   |
| 5.11.0  | 3        | 1.66%   |
| 5.7.6   | 1        | 0.55%   |
| 5.7.0   | 1        | 0.55%   |
| 5.10.5  | 1        | 0.55%   |
| 5.10.0  | 1        | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 158      | 87.29%  |
| 5.8     | 16       | 8.84%   |
| 5.11    | 3        | 1.66%   |
| 5.7     | 2        | 1.1%    |
| 5.10    | 2        | 1.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 179      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 176      | 98.32%  |
| X-Cinnamon | 1        | 0.56%   |
| Trinity    | 1        | 0.56%   |
| GNOME      | 1        | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 174      | 96.67%  |
| Tty     | 5        | 2.78%   |
| Wayland | 1        | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 105      | 58.01%  |
| Unknown | 64       | 35.36%  |
| LightDM | 7        | 3.87%   |
| GDM     | 4        | 2.21%   |
| SDDM    | 1        | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 54       | 30%     |
| en_US | 43       | 23.89%  |
| de_DE | 12       | 6.67%   |
| fr_FR | 11       | 6.11%   |
| en_GB | 10       | 5.56%   |
| ru_RU | 7        | 3.89%   |
| es_ES | 6        | 3.33%   |
| en_CA | 6        | 3.33%   |
| es_AR | 4        | 2.22%   |
| nl_NL | 3        | 1.67%   |
| it_IT | 3        | 1.67%   |
| pl_PL | 2        | 1.11%   |
| en_AU | 2        | 1.11%   |
| de_CH | 2        | 1.11%   |
| cs_CZ | 2        | 1.11%   |
| sv_SE | 1        | 0.56%   |
| ja_JP | 1        | 0.56%   |
| hr_HR | 1        | 0.56%   |
| fi_FI | 1        | 0.56%   |
| eu_ES | 1        | 0.56%   |
| es_GT | 1        | 0.56%   |
| es_CL | 1        | 0.56%   |
| en_SG | 1        | 0.56%   |
| en_IN | 1        | 0.56%   |
| el_GR | 1        | 0.56%   |
| de_AT | 1        | 0.56%   |
| da_DK | 1        | 0.56%   |
| C     | 1        | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 110      | 60.77%  |
| EFI  | 71       | 39.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 172      | 96.09%  |
| Xfs     | 2        | 1.12%   |
| Overlay | 2        | 1.12%   |
| Zfs     | 1        | 0.56%   |
| ExX4    | 1        | 0.56%   |
| Btrfs   | 1        | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 35.36%  |
| GPT     | 60       | 33.15%  |
| MBR     | 57       | 31.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 86.03%  |
| Yes       | 25       | 13.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 71.98%  |
| Yes       | 51       | 28.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 37       | 20.67%  |
| Hewlett-Packard     | 32       | 17.88%  |
| Dell                | 32       | 17.88%  |
| Gigabyte Technology | 26       | 14.53%  |
| MSI                 | 14       | 7.82%   |
| ASRock              | 13       | 7.26%   |
| Intel               | 7        | 3.91%   |
| Lenovo              | 4        | 2.23%   |
| Pegatron            | 2        | 1.12%   |
| Medion              | 2        | 1.12%   |
| Biostar             | 2        | 1.12%   |
| Unknown             | 2        | 1.12%   |
| Semp Toshiba        | 1        | 0.56%   |
| JINGSHA             | 1        | 0.56%   |
| IBM                 | 1        | 0.56%   |
| Gateway             | 1        | 0.56%   |
| Fujitsu Siemens     | 1        | 0.56%   |
| Acer                | 1        | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| HP Compaq 6005 Pro SFF PC         | 8        | 4.47%   |
| HP Compaq Elite 8300 SFF          | 6        | 3.35%   |
| Dell OptiPlex 3010                | 5        | 2.79%   |
| Dell OptiPlex 390                 | 4        | 2.23%   |
| HP Compaq 6200 Pro SFF PC         | 3        | 1.68%   |
| Dell OptiPlex 360                 | 3        | 1.68%   |
| ASUS M5A78L-M/USB3                | 3        | 1.68%   |
| HP Compaq 4000 Pro SFF PC         | 2        | 1.12%   |
| Gigabyte Z97-HD3                  | 2        | 1.12%   |
| Gigabyte B450M DS3H               | 2        | 1.12%   |
| Dell OptiPlex 780                 | 2        | 1.12%   |
| Dell OptiPlex 755                 | 2        | 1.12%   |
| Dell OptiPlex 380                 | 2        | 1.12%   |
| Dell OptiPlex 330                 | 2        | 1.12%   |
| ASUS P8H61-M LX3 R2.0             | 2        | 1.12%   |
| ASUS M2N68-AM Plus                | 2        | 1.12%   |
| ASUS All Series                   | 2        | 1.12%   |
| ASRock B450M Pro4                 | 2        | 1.12%   |
| Unknown                           | 2        | 1.12%   |
| Semp Toshiba STI                  | 1        | 0.56%   |
| Pegatron FR484AA-UUW m9464sc      | 1        | 0.56%   |
| Pegatron Compaq dx7500 SFF        | 1        | 0.56%   |
| MSI MS-7C95                       | 1        | 0.56%   |
| MSI MS-7C94                       | 1        | 0.56%   |
| MSI MS-7C84                       | 1        | 0.56%   |
| MSI MS-7C59                       | 1        | 0.56%   |
| MSI MS-7C35                       | 1        | 0.56%   |
| MSI MS-7B51                       | 1        | 0.56%   |
| MSI MS-7B49                       | 1        | 0.56%   |
| MSI MS-7B48                       | 1        | 0.56%   |
| MSI MS-7B17                       | 1        | 0.56%   |
| MSI MS-7823                       | 1        | 0.56%   |
| MSI MS-7816                       | 1        | 0.56%   |
| MSI MS-7735                       | 1        | 0.56%   |
| MSI MS-7721                       | 1        | 0.56%   |
| MSI MS-7680                       | 1        | 0.56%   |
| Medion MD34440                    | 1        | 0.56%   |
| Medion MD34207/C746               | 1        | 0.56%   |
| Lenovo ThinkCentre M73 10B00013US | 1        | 0.56%   |
| Lenovo ThinkCentre M73 10AXS5W900 | 1        | 0.56%   |
| Lenovo ThinkCentre M58p 6234DJ1   | 1        | 0.56%   |
| Lenovo ThinkCentre A70 7844P8U    | 1        | 0.56%   |
| JINGSHA Board                     | 1        | 0.56%   |
| Intel SLIMBOOK                    | 1        | 0.56%   |
| Intel H61M-S1                     | 1        | 0.56%   |
| Intel DH87RL AAG74240-402         | 1        | 0.56%   |
| Intel DH61WW AAG23116-203         | 1        | 0.56%   |
| Intel DG43GT AAE62768-301         | 1        | 0.56%   |
| Intel D946GZIS AAD45436-306       | 1        | 0.56%   |
| Intel Board                       | 1        | 0.56%   |
| IBM 9210KGT                       | 1        | 0.56%   |
| HP Z230 Tower Workstation         | 1        | 0.56%   |
| HP Z220 CMT Workstation           | 1        | 0.56%   |
| HP ProLiant MicroServer           | 1        | 0.56%   |
| HP ProDesk 600 G1 SFF             | 1        | 0.56%   |
| HP ProDesk 400 G4 SFF             | 1        | 0.56%   |
| HP Desktop Pro A MT               | 1        | 0.56%   |
| HP Compaq Pro 6300 SFF            | 1        | 0.56%   |
| HP Compaq Elite 8300 CMT          | 1        | 0.56%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 27       | 15.08%  |
| HP Compaq             | 25       | 13.97%  |
| ASUS PRIME            | 6        | 3.35%   |
| Lenovo ThinkCentre    | 4        | 2.23%   |
| ASUS M5A78L-M         | 4        | 2.23%   |
| ASUS M5A97            | 3        | 1.68%   |
| HP ProDesk            | 2        | 1.12%   |
| Gigabyte Z97-HD3      | 2        | 1.12%   |
| Gigabyte X570         | 2        | 1.12%   |
| Gigabyte B450M        | 2        | 1.12%   |
| Gigabyte B450         | 2        | 1.12%   |
| Dell Precision        | 2        | 1.12%   |
| ASUS TUF              | 2        | 1.12%   |
| ASUS P9X79            | 2        | 1.12%   |
| ASUS P8H61-M          | 2        | 1.12%   |
| ASUS M2N68-AM         | 2        | 1.12%   |
| ASUS All              | 2        | 1.12%   |
| ASRock B450M          | 2        | 1.12%   |
| Unknown               | 2        | 1.12%   |
| Semp Toshiba STI      | 1        | 0.56%   |
| Pegatron FR484AA-UUW  | 1        | 0.56%   |
| Pegatron Compaq       | 1        | 0.56%   |
| MSI MS-7C95           | 1        | 0.56%   |
| MSI MS-7C94           | 1        | 0.56%   |
| MSI MS-7C84           | 1        | 0.56%   |
| MSI MS-7C59           | 1        | 0.56%   |
| MSI MS-7C35           | 1        | 0.56%   |
| MSI MS-7B51           | 1        | 0.56%   |
| MSI MS-7B49           | 1        | 0.56%   |
| MSI MS-7B48           | 1        | 0.56%   |
| MSI MS-7B17           | 1        | 0.56%   |
| MSI MS-7823           | 1        | 0.56%   |
| MSI MS-7816           | 1        | 0.56%   |
| MSI MS-7735           | 1        | 0.56%   |
| MSI MS-7721           | 1        | 0.56%   |
| MSI MS-7680           | 1        | 0.56%   |
| Medion MD34440        | 1        | 0.56%   |
| Medion MD34207        | 1        | 0.56%   |
| JINGSHA Board         | 1        | 0.56%   |
| Intel SLIMBOOK        | 1        | 0.56%   |
| Intel H61M-S1         | 1        | 0.56%   |
| Intel DH87RL          | 1        | 0.56%   |
| Intel DH61WW          | 1        | 0.56%   |
| Intel DG43GT          | 1        | 0.56%   |
| Intel D946GZIS        | 1        | 0.56%   |
| Intel Board           | 1        | 0.56%   |
| IBM 9210KGT           | 1        | 0.56%   |
| HP Z230               | 1        | 0.56%   |
| HP Z220               | 1        | 0.56%   |
| HP ProLiant           | 1        | 0.56%   |
| HP Desktop            | 1        | 0.56%   |
| HP 550-142nf          | 1        | 0.56%   |
| Gigabyte Z77P-D3      | 1        | 0.56%   |
| Gigabyte Z390         | 1        | 0.56%   |
| Gigabyte Z170X-Gaming | 1        | 0.56%   |
| Gigabyte X58A-UD3R    | 1        | 0.56%   |
| Gigabyte X470         | 1        | 0.56%   |
| Gigabyte M68MT-S2P    | 1        | 0.56%   |
| Gigabyte H97N-WIFI    | 1        | 0.56%   |
| Gigabyte H81M-S1      | 1        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 27       | 15.08%  |
| 2018 | 25       | 13.97%  |
| 2012 | 19       | 10.61%  |
| 2015 | 15       | 8.38%   |
| 2011 | 15       | 8.38%   |
| 2020 | 14       | 7.82%   |
| 2014 | 13       | 7.26%   |
| 2013 | 11       | 6.15%   |
| 2010 | 11       | 6.15%   |
| 2009 | 8        | 4.47%   |
| 2017 | 5        | 2.79%   |
| 2021 | 4        | 2.23%   |
| 2016 | 4        | 2.23%   |
| 2008 | 3        | 1.68%   |
| 2006 | 3        | 1.68%   |
| 2007 | 1        | 0.56%   |
| 2005 | 1        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 179      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 177      | 98.88%  |
| Enabled  | 2        | 1.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 179      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 63       | 35.2%   |
| 16.01-24.0      | 29       | 16.2%   |
| 8.01-16.0       | 29       | 16.2%   |
| 32.01-64.0      | 20       | 11.17%  |
| 4.01-8.0        | 19       | 10.61%  |
| 64.01-256.0     | 10       | 5.59%   |
| 24.01-32.0      | 4        | 2.23%   |
| 2.01-3.0        | 2        | 1.12%   |
| 1.01-2.0        | 2        | 1.12%   |
| More than 256.0 | 1        | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 59       | 31.55%  |
| 0.51-1.0   | 51       | 27.27%  |
| 2.01-3.0   | 29       | 15.51%  |
| 4.01-8.0   | 18       | 9.63%   |
| 3.01-4.0   | 18       | 9.63%   |
| 8.01-16.0  | 7        | 3.74%   |
| 24.01-32.0 | 2        | 1.07%   |
| 16.01-24.0 | 2        | 1.07%   |
| 32.01-64.0 | 1        | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 50.54%  |
| 2      | 45       | 24.46%  |
| 3      | 23       | 12.5%   |
| 4      | 9        | 4.89%   |
| 7      | 3        | 1.63%   |
| 5      | 3        | 1.63%   |
| 10     | 2        | 1.09%   |
| 8      | 2        | 1.09%   |
| 6      | 2        | 1.09%   |
| 11     | 1        | 0.54%   |
| 0      | 1        | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 108      | 59.67%  |
| No        | 73       | 40.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 178      | 99.44%  |
| No        | 1        | 0.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 67.78%  |
| Yes       | 58       | 32.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 75%     |
| Yes       | 45       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 57       | 31.84%  |
| USA         | 21       | 11.73%  |
| Germany     | 14       | 7.82%   |
| UK          | 11       | 6.15%   |
| France      | 11       | 6.15%   |
| Spain       | 9        | 5.03%   |
| Russia      | 7        | 3.91%   |
| Netherlands | 5        | 2.79%   |
| Czechia     | 5        | 2.79%   |
| Argentina   | 5        | 2.79%   |
| Canada      | 4        | 2.23%   |
| Poland      | 3        | 1.68%   |
| Italy       | 3        | 1.68%   |
| Switzerland | 2        | 1.12%   |
| Japan       | 2        | 1.12%   |
| Greece      | 2        | 1.12%   |
| Finland     | 2        | 1.12%   |
| Australia   | 2        | 1.12%   |
| Ukraine     | 1        | 0.56%   |
| Taiwan      | 1        | 0.56%   |
| Singapore   | 1        | 0.56%   |
| Mexico      | 1        | 0.56%   |
| India       | 1        | 0.56%   |
| Guatemala   | 1        | 0.56%   |
| Denmark     | 1        | 0.56%   |
| Cyprus      | 1        | 0.56%   |
| Croatia     | 1        | 0.56%   |
| Chile       | 1        | 0.56%   |
| Bulgaria    | 1        | 0.56%   |
| Belgium     | 1        | 0.56%   |
| Belarus     | 1        | 0.56%   |
| Austria     | 1        | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| São Paulo              | 25       | 13.66%  |
| Jundiaí                | 20       | 10.93%  |
| Manchester              | 3        | 1.64%   |
| Itatiba                 | 3        | 1.64%   |
| Yekaterinburg           | 2        | 1.09%   |
| Włocławek             | 2        | 1.09%   |
| Melbourne               | 2        | 1.09%   |
| Kirchheim unter Teck    | 2        | 1.09%   |
| Karlsruhe               | 2        | 1.09%   |
| Florence                | 2        | 1.09%   |
| Biysk                   | 2        | 1.09%   |
| Berlin                  | 2        | 1.09%   |
| Bergschenhoek           | 2        | 1.09%   |
| Bagnoles-de-l'Orne      | 2        | 1.09%   |
| Zurich                  | 1        | 0.55%   |
| Zagreb                  | 1        | 0.55%   |
| Worb                    | 1        | 0.55%   |
| Windsor                 | 1        | 0.55%   |
| Westbury                | 1        | 0.55%   |
| Wejherowo               | 1        | 0.55%   |
| Warren                  | 1        | 0.55%   |
| Village-Neuf            | 1        | 0.55%   |
| Vigo                    | 1        | 0.55%   |
| Vienna                  | 1        | 0.55%   |
| Viamão                 | 1        | 0.55%   |
| Valladolid              | 1        | 0.55%   |
| Ushiku                  | 1        | 0.55%   |
| Urretxu                 | 1        | 0.55%   |
| Tremembe                | 1        | 0.55%   |
| Torun                   | 1        | 0.55%   |
| Tilburg                 | 1        | 0.55%   |
| The Hague               | 1        | 0.55%   |
| Thalfingen              | 1        | 0.55%   |
| Tainan City             | 1        | 0.55%   |
| São José dos Pinhais  | 1        | 0.55%   |
| Sunnyvale               | 1        | 0.55%   |
| Sunderland              | 1        | 0.55%   |
| Stezzano                | 1        | 0.55%   |
| Spokane                 | 1        | 0.55%   |
| Sofia                   | 1        | 0.55%   |
| Smolensk                | 1        | 0.55%   |
| Secaucus                | 1        | 0.55%   |
| San Jose                | 1        | 0.55%   |
| San Diego               | 1        | 0.55%   |
| Saint-Laurent-sur-Gorre | 1        | 0.55%   |
| Saint John              | 1        | 0.55%   |
| Revda                   | 1        | 0.55%   |
| Reston                  | 1        | 0.55%   |
| Rakovnik                | 1        | 0.55%   |
| Prague                  | 1        | 0.55%   |
| Ploen                   | 1        | 0.55%   |
| Plano                   | 1        | 0.55%   |
| Oracov                  | 1        | 0.55%   |
| Nottingham              | 1        | 0.55%   |
| Northcote               | 1        | 0.55%   |
| Noisy-le-Grand          | 1        | 0.55%   |
| Newmarket               | 1        | 0.55%   |
| Nangis                  | 1        | 0.55%   |
| Naestved                | 1        | 0.55%   |
| Münster                | 1        | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 77       | 103    | 27.21%  |
| Seagate                   | 61       | 103    | 21.55%  |
| Samsung Electronics       | 40       | 66     | 14.13%  |
| Kingston                  | 19       | 26     | 6.71%   |
| Toshiba                   | 10       | 19     | 3.53%   |
| SanDisk                   | 10       | 11     | 3.53%   |
| Hitachi                   | 10       | 13     | 3.53%   |
| Intel                     | 7        | 8      | 2.47%   |
| Crucial                   | 7        | 11     | 2.47%   |
| Silicon Motion            | 4        | 5      | 1.41%   |
| A-DATA Technology         | 4        | 4      | 1.41%   |
| MAXTOR                    | 3        | 9      | 1.06%   |
| HGST                      | 3        | 5      | 1.06%   |
| Unknown                   | 2        | 2      | 0.71%   |
| PNY                       | 2        | 2      | 0.71%   |
| Patriot                   | 2        | 4      | 0.71%   |
| Apacer                    | 2        | 2      | 0.71%   |
| USB3.0                    | 1        | 1      | 0.35%   |
| TO Exter                  | 1        | 1      | 0.35%   |
| SMI                       | 1        | 1      | 0.35%   |
| SK Hynix                  | 1        | 1      | 0.35%   |
| Phison                    | 1        | 1      | 0.35%   |
| Mushkin                   | 1        | 1      | 0.35%   |
| Micron/Crucial Technology | 1        | 2      | 0.35%   |
| Marlin                    | 1        | 1      | 0.35%   |
| Lexar                     | 1        | 1      | 0.35%   |
| LDLC                      | 1        | 1      | 0.35%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.35%   |
| Intenso                   | 1        | 1      | 0.35%   |
| Inateck                   | 1        | 1      | 0.35%   |
| Hewlett-Packard           | 1        | 1      | 0.35%   |
| ASMT109x                  | 1        | 2      | 0.35%   |
| ASMT                      | 1        | 2      | 0.35%   |
| AMD                       | 1        | 1      | 0.35%   |
| AGI                       | 1        | 1      | 0.35%   |
| addlink                   | 1        | 2      | 0.35%   |
| ADATA SP                  | 1        | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 11       | 3.38%   |
| WDC WD5000AAKX-083CA1 500GB          | 6        | 1.85%   |
| WDC WD5000AAKX-003CA0 500GB          | 6        | 1.85%   |
| Samsung HD322HJ 320GB                | 5        | 1.54%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 1.23%   |
| Toshiba DT01ACA100 1TB               | 4        | 1.23%   |
| Seagate ST3500418AS 500GB            | 4        | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB       | 4        | 1.23%   |
| Kingston SA400S37120G 120GB SSD      | 4        | 1.23%   |
| WDC WD2500AAKX-753CA1 250GB          | 3        | 0.92%   |
| Seagate ST8000DM004-2CX188 8TB       | 3        | 0.92%   |
| Seagate ST2000DM001-1ER164 2TB       | 3        | 0.92%   |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 0.92%   |
| Samsung SSD 860 EVO 500GB            | 3        | 0.92%   |
| Samsung NVMe SSD Drive 500GB         | 3        | 0.92%   |
| Samsung HD502HJ 500GB                | 3        | 0.92%   |
| Kingston SV300S37A120G 120GB SSD     | 3        | 0.92%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2        | 0.62%   |
| WDC WD5000AZLX-75K2TA0 500GB         | 2        | 0.62%   |
| WDC WD3200AAKS-75L9A0 320GB          | 2        | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2        | 0.62%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2        | 0.62%   |
| WDC WD10EARX-00N0YB0 1TB             | 2        | 0.62%   |
| Unknown SD/MMC/MS PRO 64GB           | 2        | 0.62%   |
| Seagate ST3500630AS 500GB            | 2        | 0.62%   |
| Seagate ST3320620AS 320GB            | 2        | 0.62%   |
| Seagate ST31000528AS 1TB             | 2        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB       | 2        | 0.62%   |
| Seagate ST2000DM001-9YN164 2TB       | 2        | 0.62%   |
| Seagate Expansion+ 1TB               | 2        | 0.62%   |
| SanDisk SSD U100 16GB                | 2        | 0.62%   |
| SanDisk SSD PLUS 480GB               | 2        | 0.62%   |
| Samsung SSD 970 PRO 512GB            | 2        | 0.62%   |
| Samsung SSD 970 EVO Plus 250GB       | 2        | 0.62%   |
| Samsung SSD 870 EVO 1TB              | 2        | 0.62%   |
| Samsung SP2504C 250GB                | 2        | 0.62%   |
| Samsung MZ7LN128HCHP-000L1 128GB SSD | 2        | 0.62%   |
| Kingston SV300S37A240G 240GB SSD     | 2        | 0.62%   |
| Kingston SA400S37960G 960GB SSD      | 2        | 0.62%   |
| Hitachi HDP725050GLA360 500GB        | 2        | 0.62%   |
| HGST HDN726040ALE614 4TB             | 2        | 0.62%   |
| Apacer AS350 128GB SSD               | 2        | 0.62%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1        | 0.31%   |
| WDC WDS500G2B0A 500GB SSD            | 1        | 0.31%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 0.31%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.31%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1        | 0.31%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1        | 0.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.31%   |
| WDC WD800BEVT-00ZCT0 80GB            | 1        | 0.31%   |
| WDC WD6400AAKS-41H2B0 640GB          | 1        | 0.31%   |
| WDC WD6400AACS-00D6B1 640GB          | 1        | 0.31%   |
| WDC WD6001FZWX-00A2VA0 6TB           | 1        | 0.31%   |
| WDC WD5000BPKT-00PK4T0 500GB         | 1        | 0.31%   |
| WDC WD5000AZLX-60K2TA0 500GB         | 1        | 0.31%   |
| WDC WD5000AZLX-08K2TA0 500GB         | 1        | 0.31%   |
| WDC WD5000AZLX-00CL5A0 500GB         | 1        | 0.31%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 0.31%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 1        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 68       | 89     | 38.86%  |
| Seagate             | 60       | 102    | 34.29%  |
| Samsung Electronics | 16       | 16     | 9.14%   |
| Toshiba             | 10       | 19     | 5.71%   |
| Hitachi             | 10       | 13     | 5.71%   |
| HGST                | 3        | 5      | 1.71%   |
| Unknown             | 2        | 2      | 1.14%   |
| MAXTOR              | 2        | 7      | 1.14%   |
| USB3.0              | 1        | 1      | 0.57%   |
| TO Exter            | 1        | 1      | 0.57%   |
| ASMT109x            | 1        | 2      | 0.57%   |
| ASMT                | 1        | 2      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 17       | 19     | 20.73%  |
| Samsung Electronics | 15       | 28     | 18.29%  |
| SanDisk             | 10       | 11     | 12.2%   |
| WDC                 | 9        | 13     | 10.98%  |
| Crucial             | 7        | 11     | 8.54%   |
| Intel               | 5        | 6      | 6.1%    |
| A-DATA Technology   | 4        | 4      | 4.88%   |
| PNY                 | 2        | 2      | 2.44%   |
| Patriot             | 2        | 4      | 2.44%   |
| Apacer              | 2        | 2      | 2.44%   |
| SMI                 | 1        | 1      | 1.22%   |
| Seagate             | 1        | 1      | 1.22%   |
| Mushkin             | 1        | 1      | 1.22%   |
| Maxtor              | 1        | 2      | 1.22%   |
| Lexar               | 1        | 1      | 1.22%   |
| LDLC                | 1        | 1      | 1.22%   |
| Intenso             | 1        | 1      | 1.22%   |
| AMD                 | 1        | 1      | 1.22%   |
| ADATA SP            | 1        | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 141      | 259    | 58.26%  |
| SSD     | 71       | 110    | 29.34%  |
| NVMe    | 27       | 45     | 11.16%  |
| Unknown | 3        | 3      | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 168      | 357    | 81.16%  |
| NVMe | 27       | 45     | 13.04%  |
| SAS  | 12       | 15     | 5.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 135      | 201    | 57.2%   |
| 0.51-1.0   | 53       | 82     | 22.46%  |
| 1.01-2.0   | 24       | 36     | 10.17%  |
| 4.01-10.0  | 10       | 25     | 4.24%   |
| 3.01-4.0   | 8        | 13     | 3.39%   |
| 2.01-3.0   | 5        | 11     | 2.12%   |
| 10.01-20.0 | 1        | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 62       | 33.7%   |
| 101-250        | 28       | 15.22%  |
| 501-1000       | 26       | 14.13%  |
| 1001-2000      | 25       | 13.59%  |
| More than 3000 | 20       | 10.87%  |
| 2001-3000      | 7        | 3.8%    |
| 1-20           | 7        | 3.8%    |
| 51-100         | 6        | 3.26%   |
| 21-50          | 3        | 1.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 70       | 37.23%  |
| 101-250        | 27       | 14.36%  |
| 21-50          | 23       | 12.23%  |
| 51-100         | 17       | 9.04%   |
| 251-500        | 14       | 7.45%   |
| 501-1000       | 14       | 7.45%   |
| 1001-2000      | 11       | 5.85%   |
| More than 3000 | 6        | 3.19%   |
| 2001-3000      | 6        | 3.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 5        | 5      | 12.2%   |
| WDC WD5000AAKX-083CA1 500GB       | 4        | 4      | 9.76%   |
| WDC WD5000AAKX-003CA0 500GB       | 2        | 2      | 4.88%   |
| WDC WD2500AAKX-753CA1 250GB       | 2        | 2      | 4.88%   |
| Samsung Electronics HD502HJ 500GB | 2        | 2      | 4.88%   |
| WDC WD2500YS-01SHB1 256GB         | 1        | 1      | 2.44%   |
| WDC WD2500AAKX-75U6AA0 250GB      | 1        | 1      | 2.44%   |
| WDC WD2500AAJS-75M0A0 250GB       | 1        | 1      | 2.44%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 2      | 2.44%   |
| WDC WD15EADS-00P8B0 1TB           | 1        | 1      | 2.44%   |
| WDC WD1200JD-00HBB0 120GB         | 1        | 1      | 2.44%   |
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 1      | 2.44%   |
| Toshiba MK5055GSX 500GB           | 1        | 1      | 2.44%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1      | 2.44%   |
| Seagate ST3750525AS 752GB         | 1        | 1      | 2.44%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 2.44%   |
| Seagate ST3360320AS 360GB         | 1        | 2      | 2.44%   |
| Seagate ST3320620AS 320GB         | 1        | 1      | 2.44%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 2.44%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 2.44%   |
| Seagate ST31000333AS 1TB          | 1        | 1      | 2.44%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 2.44%   |
| SanDisk SSD PLUS 480GB            | 1        | 1      | 2.44%   |
| Samsung Electronics SP2504C 250GB | 1        | 1      | 2.44%   |
| Maxtor 6Y160M0 163GB              | 1        | 1      | 2.44%   |
| Kingston SHPM2280P2H 240G SSD     | 1        | 1      | 2.44%   |
| Intel SSDSA2M080G2GC 80GB         | 1        | 1      | 2.44%   |
| Hitachi HDT721050SLA360 500GB     | 1        | 1      | 2.44%   |
| HGST HDN726040ALE614 4TB          | 1        | 2      | 2.44%   |
| Crucial CT1050MX300SSD1 1050GB    | 1        | 1      | 2.44%   |
| ASMT USB 3.0 Destop H 2TB         | 1        | 2      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 35%     |
| Seagate             | 14       | 15     | 35%     |
| Samsung Electronics | 3        | 3      | 7.5%    |
| Toshiba             | 1        | 1      | 2.5%    |
| SanDisk             | 1        | 1      | 2.5%    |
| Maxtor              | 1        | 1      | 2.5%    |
| Kingston            | 1        | 1      | 2.5%    |
| Intel               | 1        | 1      | 2.5%    |
| Hitachi             | 1        | 1      | 2.5%    |
| HGST                | 1        | 2      | 2.5%    |
| Crucial             | 1        | 1      | 2.5%    |
| ASMT                | 1        | 2      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 38.89%  |
| Seagate             | 14       | 15     | 38.89%  |
| Samsung Electronics | 3        | 3      | 8.33%   |
| Toshiba             | 1        | 1      | 2.78%   |
| Maxtor              | 1        | 1      | 2.78%   |
| Hitachi             | 1        | 1      | 2.78%   |
| HGST                | 1        | 2      | 2.78%   |
| ASMT                | 1        | 2      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 41     | 88.89%  |
| SSD  | 4        | 4      | 11.11%  |

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
| Works    | 94       | 194    | 47.96%  |
| Detected | 68       | 178    | 34.69%  |
| Malfunc  | 34       | 45     | 17.35%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 121      | 53.3%   |
| AMD                           | 52       | 22.91%  |
| Samsung Electronics           | 11       | 4.85%   |
| Marvell Technology Group      | 9        | 3.96%   |
| ASMedia Technology            | 7        | 3.08%   |
| Silicon Motion                | 5        | 2.2%    |
| Nvidia                        | 5        | 2.2%    |
| Kingston Technology Company   | 4        | 1.76%   |
| JMicron Technology            | 3        | 1.32%   |
| Phison Electronics            | 2        | 0.88%   |
| VIA Technologies              | 1        | 0.44%   |
| SK Hynix                      | 1        | 0.44%   |
| Sandisk                       | 1        | 0.44%   |
| Micron/Crucial Technology     | 1        | 0.44%   |
| LSI Logic / Symbios Logic     | 1        | 0.44%   |
| KIOXIA                        | 1        | 0.44%   |
| Integrated Technology Express | 1        | 0.44%   |
| Hewlett-Packard               | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 8.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 5.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 4.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 4.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 4.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 3.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 3.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 3.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 3.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.05%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.05%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 2.05%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 1.71%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.37%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.37%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 4        | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.03%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.03%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.03%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.68%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.68%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 2        | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2        | 0.68%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.68%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.68%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.34%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.34%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.34%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.34%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.34%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.34%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.34%   |
| Nvidia MCP51 IDE                                                                        | 1        | 0.34%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.34%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.34%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.34%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.34%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1        | 0.34%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.34%   |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                          | 1        | 0.34%   |
| KIOXIA Non-Volatile memory controller                                                   | 1        | 0.34%   |
| Kingston Company HyperX Predator PCIe AHCI SSD                                          | 1        | 0.34%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.34%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 141      | 61.04%  |
| IDE  | 54       | 23.38%  |
| NVMe | 26       | 11.26%  |
| RAID | 7        | 3.03%   |
| SAS  | 3        | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 122      | 68.16%  |
| AMD    | 57       | 31.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 8        | 4.47%   |
| AMD Phenom II X4 B97 Processor              | 7        | 3.91%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 5        | 2.79%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 2.23%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 3        | 1.68%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 1.68%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.68%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 1.68%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.68%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 1.68%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.68%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.68%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 1.12%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 1.12%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.12%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 2        | 1.12%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.12%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.12%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.12%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.12%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.12%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.12%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.12%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 2        | 1.12%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.12%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 2        | 1.12%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.12%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.12%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.12%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.12%   |
| Intel Xeon E-2126G CPU @ 3.30GHz            | 1        | 0.56%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.56%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.56%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1        | 0.56%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 0.56%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.56%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.56%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.56%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.56%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.56%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.56%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 0.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.56%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.56%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.56%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.56%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.56%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 19.55%  |
| Intel Core i3           | 22       | 12.29%  |
| Intel Core i7           | 18       | 10.06%  |
| Intel Core 2 Duo        | 13       | 7.26%   |
| AMD FX                  | 10       | 5.59%   |
| AMD Ryzen 7             | 9        | 5.03%   |
| Intel Xeon              | 8        | 4.47%   |
| AMD Ryzen 5             | 8        | 4.47%   |
| AMD Phenom II X4        | 8        | 4.47%   |
| Intel Core 2 Quad       | 7        | 3.91%   |
| AMD Athlon II X2        | 6        | 3.35%   |
| Intel Pentium           | 5        | 2.79%   |
| Intel Celeron           | 4        | 2.23%   |
| AMD Ryzen 9             | 4        | 2.23%   |
| Intel Pentium Dual-Core | 3        | 1.68%   |
| Intel Pentium D         | 2        | 1.12%   |
| Intel Core 2            | 2        | 1.12%   |
| AMD Ryzen Threadripper  | 2        | 1.12%   |
| AMD Ryzen 3             | 2        | 1.12%   |
| AMD Athlon              | 2        | 1.12%   |
| Other                   | 1        | 0.56%   |
| Intel Pentium Dual      | 1        | 0.56%   |
| Intel Pentium 4         | 1        | 0.56%   |
| Intel Core i9           | 1        | 0.56%   |
| AMD Turion II Neo       | 1        | 0.56%   |
| AMD Ryzen 3 PRO         | 1        | 0.56%   |
| AMD Phenom II X6        | 1        | 0.56%   |
| AMD Athlon 64 X2        | 1        | 0.56%   |
| AMD A4                  | 1        | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 81       | 45.25%  |
| 2      | 57       | 31.84%  |
| 6      | 18       | 10.06%  |
| 8      | 10       | 5.59%   |
| 16     | 5        | 2.79%   |
| 24     | 2        | 1.12%   |
| 12     | 2        | 1.12%   |
| 3      | 2        | 1.12%   |
| 1      | 2        | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 176      | 98.32%  |
| 2      | 3        | 1.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 97       | 54.19%  |
| 2      | 82       | 45.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 179      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 21       | 11.67%  |
| 0x306c3    | 17       | 9.44%   |
| 0x206a7    | 16       | 8.89%   |
| Unknown    | 13       | 7.22%   |
| 0x1067a    | 12       | 6.67%   |
| 0x010000c8 | 12       | 6.67%   |
| 0x08701021 | 6        | 3.33%   |
| 0x06000852 | 6        | 3.33%   |
| 0x906ea    | 5        | 2.78%   |
| 0x6fb      | 5        | 2.78%   |
| 0x906e9    | 4        | 2.22%   |
| 0x6fd      | 4        | 2.22%   |
| 0x206d7    | 4        | 2.22%   |
| 0x08701013 | 4        | 2.22%   |
| 0x0800820d | 4        | 2.22%   |
| 0xa0653    | 3        | 1.67%   |
| 0x506e3    | 3        | 1.67%   |
| 0x0810100b | 3        | 1.67%   |
| 0x906eb    | 2        | 1.11%   |
| 0x6f6      | 2        | 1.11%   |
| 0x30678    | 2        | 1.11%   |
| 0x20655    | 2        | 1.11%   |
| 0x106e5    | 2        | 1.11%   |
| 0x10676    | 2        | 1.11%   |
| 0xf62      | 1        | 0.56%   |
| 0xf47      | 1        | 0.56%   |
| 0xf43      | 1        | 0.56%   |
| 0x906ec    | 1        | 0.56%   |
| 0x806ea    | 1        | 0.56%   |
| 0x306f2    | 1        | 0.56%   |
| 0x306e4    | 1        | 0.56%   |
| 0x206d6    | 1        | 0.56%   |
| 0x106a5    | 1        | 0.56%   |
| 0x10677    | 1        | 0.56%   |
| 0x0a201016 | 1        | 0.56%   |
| 0x0a201009 | 1        | 0.56%   |
| 0x08600106 | 1        | 0.56%   |
| 0x08301039 | 1        | 0.56%   |
| 0x08108109 | 1        | 0.56%   |
| 0x08101102 | 1        | 0.56%   |
| 0x08101016 | 1        | 0.56%   |
| 0x08101013 | 1        | 0.56%   |
| 0x08001138 | 1        | 0.56%   |
| 0x08001137 | 1        | 0.56%   |
| 0x06001119 | 1        | 0.56%   |
| 0x0600081f | 1        | 0.56%   |
| 0x0600063e | 1        | 0.56%   |
| 0x010000dc | 1        | 0.56%   |
| 0x010000db | 1        | 0.56%   |
| 0x010000c7 | 1        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 23       | 12.85%  |
| IvyBridge   | 22       | 12.29%  |
| Haswell     | 19       | 10.61%  |
| K10         | 17       | 9.5%    |
| Penryn      | 16       | 8.94%   |
| KabyLake    | 14       | 7.82%   |
| Zen 2       | 12       | 6.7%    |
| Core        | 11       | 6.15%   |
| Piledriver  | 10       | 5.59%   |
| Zen         | 8        | 4.47%   |
| Zen+        | 5        | 2.79%   |
| Skylake     | 4        | 2.23%   |
| NetBurst    | 3        | 1.68%   |
| Nehalem     | 3        | 1.68%   |
| CometLake   | 3        | 1.68%   |
| Zen 3       | 2        | 1.12%   |
| Westmere    | 2        | 1.12%   |
| Silvermont  | 2        | 1.12%   |
| K8 Hammer   | 1        | 0.56%   |
| Jaguar      | 1        | 0.56%   |
| Bulldozer   | 1        | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 74       | 39.15%  |
| Nvidia            | 58       | 30.69%  |
| AMD               | 56       | 29.63%  |
| ASPEED Technology | 1        | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 14       | 7.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14       | 7.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 5.26%   |
| AMD RS880 [Radeon HD 4200]                                                  | 9        | 4.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.21%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 6        | 3.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 3.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 2.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 2.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.11%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 2.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 2.11%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.58%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 3        | 1.58%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.58%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.05%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.05%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 1.05%   |
| Intel HD Graphics 630                                                       | 2        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.05%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.05%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 1.05%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 1.05%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 1.05%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.53%   |
| Nvidia TU104GL [Quadro RTX 4000]                                            | 1        | 0.53%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.53%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 0.53%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.53%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.53%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.53%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.53%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.53%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.53%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.53%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.53%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.53%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.53%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.53%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.53%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.53%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.53%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.53%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 0.53%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.53%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.53%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 66       | 36.67%  |
| 1 x AMD        | 55       | 30.56%  |
| 1 x Nvidia     | 52       | 28.89%  |
| Intel + Nvidia | 4        | 2.22%   |
| 2 x Nvidia     | 1        | 0.56%   |
| Intel + AMD    | 1        | 0.56%   |
| 1 x ASPEED     | 1        | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 136      | 75.14%  |
| Proprietary | 43       | 23.76%  |
| Unknown     | 2        | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 75       | 41.44%  |
| 0.01-0.5   | 28       | 15.47%  |
| 1.01-2.0   | 27       | 14.92%  |
| 0.51-1.0   | 20       | 11.05%  |
| 3.01-4.0   | 14       | 7.73%   |
| 7.01-8.0   | 13       | 7.18%   |
| 5.01-6.0   | 4        | 2.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 58       | 30.85%  |
| Samsung Electronics  | 27       | 14.36%  |
| Goldstar             | 16       | 8.51%   |
| BenQ                 | 13       | 6.91%   |
| Philips              | 10       | 5.32%   |
| Ancor Communications | 9        | 4.79%   |
| Acer                 | 7        | 3.72%   |
| Unknown              | 6        | 3.19%   |
| Hewlett-Packard      | 6        | 3.19%   |
| AOC                  | 6        | 3.19%   |
| Vestel Elektronik    | 2        | 1.06%   |
| Toshiba              | 2        | 1.06%   |
| NEC Computers        | 2        | 1.06%   |
| Lenovo               | 2        | 1.06%   |
| Iiyama               | 2        | 1.06%   |
| HannStar             | 2        | 1.06%   |
| Gateway              | 2        | 1.06%   |
| Vizio                | 1        | 0.53%   |
| VIZ                  | 1        | 0.53%   |
| ViewSonic            | 1        | 0.53%   |
| Targa                | 1        | 0.53%   |
| Sceptre Tech         | 1        | 0.53%   |
| Sceptre              | 1        | 0.53%   |
| Packard Bell         | 1        | 0.53%   |
| Onkyo                | 1        | 0.53%   |
| Medion               | 1        | 0.53%   |
| LG Electronics       | 1        | 0.53%   |
| Fujitsu Siemens      | 1        | 0.53%   |
| Element              | 1        | 0.53%   |
| Eizo                 | 1        | 0.53%   |
| Daewoo               | 1        | 0.53%   |
| Compal               | 1        | 0.53%   |
| Belinea              | 1        | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                       | 31       | 15.35%  |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                       | 5        | 2.48%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                        | 3        | 1.49%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                       | 3        | 1.49%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 2        | 0.99%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch    | 2        | 0.99%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                       | 2        | 0.99%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch                 | 2        | 0.99%   |
| Goldstar W2253 GSM56DB 1920x1080 477x268mm 21.5-inch                    | 2        | 0.99%   |
| Goldstar E2340 GSM57A6 1920x1080 510x290mm 23.1-inch                    | 2        | 0.99%   |
| Goldstar 23LC1R GSM5617 1360x768 930x523mm 42.0-inch                    | 2        | 0.99%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2        | 0.99%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                        | 2        | 0.99%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 2        | 0.99%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                       | 1        | 0.5%    |
| VIZ LCD Monitor E322VL 1920x1080                                        | 1        | 0.5%    |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch                 | 1        | 0.5%    |
| Unknown LCD Monitor Sony SDM-X82 1280x1024                              | 1        | 0.5%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 1        | 0.5%    |
| Unknown LCD Monitor SAMSUNG 1360x768                                    | 1        | 0.5%    |
| Unknown LCD Monitor FormacTFT2010 1600x1200                             | 1        | 0.5%    |
| Unknown LCD Monitor ELE E4SW5017RKU                                     | 1        | 0.5%    |
| Unknown LCD Monitor CHHWJT 1920x1080                                    | 1        | 0.5%    |
| Toshiba TV TSB2017 3840x2160                                            | 1        | 0.5%    |
| Toshiba 49FHD_LCD_TV TSB3700 1920x1080 1360x768mm 61.5-inch             | 1        | 0.5%    |
| Targa LCD Monitor LCDTV16                                               | 1        | 0.5%    |
| Sceptre Tech Sceptre X24WG SPT2401 1920x1200 518x324mm 24.1-inch        | 1        | 0.5%    |
| Sceptre Tech Sceptre T27 SPT0AD7 1920x1080 600x330mm 27.0-inch          | 1        | 0.5%    |
| Sceptre LCD Monitor X24WG 3840x1200                                     | 1        | 0.5%    |
| Sceptre LCD Monitor X24WG                                               | 1        | 0.5%    |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch       | 1        | 0.5%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 0.5%    |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch       | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch     | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch    | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch    | 1        | 0.5%    |
| Samsung Electronics SMB2270HD SAM070C 1920x1080 476x268mm 21.5-inch     | 1        | 0.5%    |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch      | 1        | 0.5%    |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch       | 1        | 0.5%    |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch       | 1        | 0.5%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.5%    |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch       | 1        | 0.5%    |
| Samsung Electronics S22B300 SAM08C8 1920x1080 480x270mm 21.7-inch       | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                    | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch    | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch | 1        | 0.5%    |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                        | 1        | 0.5%    |
| Samsung Electronics LCD Monitor S27B970 1920x1080                       | 1        | 0.5%    |
| Samsung Electronics LCD Monitor S27A950D 1920x1080                      | 1        | 0.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 1        | 0.5%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1        | 0.5%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                | 1        | 0.5%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 0.5%    |
| Philips LCD Monitor PHL 272B8Q 2560x1440                                | 1        | 0.5%    |
| Philips LCD Monitor PHL 237E7 1920x1080                                 | 1        | 0.5%    |
| Philips LCD Monitor PHILIPS FTV 3840x1080                               | 1        | 0.5%    |
| Philips 220X PHLC030 1680x1050 474x296mm 22.0-inch                      | 1        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 31.38%  |
| 1280x1024 (SXGA)   | 45       | 23.94%  |
| 3840x2160 (4K)     | 17       | 9.04%   |
| 1366x768 (WXGA)    | 13       | 6.91%   |
| 1440x900 (WXGA+)   | 10       | 5.32%   |
| 1680x1050 (WSXGA+) | 8        | 4.26%   |
| 1360x768           | 7        | 3.72%   |
| 2560x1440 (QHD)    | 6        | 3.19%   |
| Unknown            | 6        | 3.19%   |
| 1920x1200 (WUXGA)  | 4        | 2.13%   |
| 1600x1200          | 3        | 1.6%    |
| 3440x1440          | 2        | 1.06%   |
| 5040x1050          | 1        | 0.53%   |
| 4240x1440          | 1        | 0.53%   |
| 3840x1200          | 1        | 0.53%   |
| 3840x1080          | 1        | 0.53%   |
| 3000x1920          | 1        | 0.53%   |
| 2640x1024          | 1        | 0.53%   |
| 1152x864           | 1        | 0.53%   |
| 1024x768 (XGA)     | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 41       | 21.58%  |
| Unknown | 26       | 13.68%  |
| 24      | 18       | 9.47%   |
| 23      | 15       | 7.89%   |
| 21      | 15       | 7.89%   |
| 27      | 13       | 6.84%   |
| 18      | 12       | 6.32%   |
| 15      | 11       | 5.79%   |
| 22      | 8        | 4.21%   |
| 84      | 6        | 3.16%   |
| 19      | 6        | 3.16%   |
| 31      | 5        | 2.63%   |
| 72      | 2        | 1.05%   |
| 42      | 2        | 1.05%   |
| 40      | 2        | 1.05%   |
| 33      | 2        | 1.05%   |
| 52      | 1        | 0.53%   |
| 36      | 1        | 0.53%   |
| 34      | 1        | 0.53%   |
| 32      | 1        | 0.53%   |
| 26      | 1        | 0.53%   |
| 20      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 301-350     | 50       | 26.88%  |
| 501-600     | 43       | 23.12%  |
| 401-500     | 38       | 20.43%  |
| Unknown     | 26       | 13.98%  |
| 1501-2000   | 8        | 4.3%    |
| 601-700     | 7        | 3.76%   |
| 701-800     | 5        | 2.69%   |
| 351-400     | 4        | 2.15%   |
| 801-900     | 2        | 1.08%   |
| 901-1000    | 2        | 1.08%   |
| 1001-1500   | 1        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 84       | 46.67%  |
| 5/4     | 41       | 22.78%  |
| 16/10   | 23       | 12.78%  |
| Unknown | 23       | 12.78%  |
| 4/3     | 6        | 3.33%   |
| 3/2     | 2        | 1.11%   |
| 21/9    | 1        | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 48       | 25.53%  |
| 201-250        | 43       | 22.87%  |
| Unknown        | 26       | 13.83%  |
| 301-350        | 14       | 7.45%   |
| 151-200        | 14       | 7.45%   |
| More than 1000 | 9        | 4.79%   |
| 351-500        | 8        | 4.26%   |
| 251-300        | 8        | 4.26%   |
| 101-110        | 8        | 4.26%   |
| 501-1000       | 5        | 2.66%   |
| 111-120        | 3        | 1.6%    |
| 131-140        | 2        | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 116      | 64.44%  |
| 101-120 | 27       | 15%     |
| Unknown | 26       | 14.44%  |
| 121-160 | 5        | 2.78%   |
| 1-50    | 4        | 2.22%   |
| 161-240 | 2        | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 153      | 84.53%  |
| 2     | 23       | 12.71%  |
| 0     | 3        | 1.66%   |
| 3     | 2        | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 94       | 40%     |
| Intel                           | 78       | 33.19%  |
| Broadcom                        | 16       | 6.81%   |
| Qualcomm Atheros                | 8        | 3.4%    |
| TP-Link                         | 5        | 2.13%   |
| Nvidia                          | 5        | 2.13%   |
| Ralink Technology               | 4        | 1.7%    |
| Ralink                          | 3        | 1.28%   |
| ASUSTek Computer                | 3        | 1.28%   |
| Xiaomi                          | 2        | 0.85%   |
| Qualcomm Atheros Communications | 2        | 0.85%   |
| Linksys                         | 2        | 0.85%   |
| Broadcom Limited                | 2        | 0.85%   |
| ASIX Electronics                | 2        | 0.85%   |
| Aquantia                        | 2        | 0.85%   |
| ZyDAS                           | 1        | 0.43%   |
| Sitecom Europe                  | 1        | 0.43%   |
| Samsung Electronics             | 1        | 0.43%   |
| NetGear                         | 1        | 0.43%   |
| MediaTek                        | 1        | 0.43%   |
| Edimax Technology               | 1        | 0.43%   |
| D-Link System                   | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 77       | 29.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 19       | 7.39%   |
| Intel I211 Gigabit Network Connection                              | 9        | 3.5%    |
| Intel Wi-Fi 6 AX200                                                | 8        | 3.11%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 8        | 3.11%   |
| Realtek RTL8125 2.5GbE Controller                                  | 6        | 2.33%   |
| Intel Ethernet Connection I217-V                                   | 5        | 1.95%   |
| Intel 82579V Gigabit Network Connection                            | 5        | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 4        | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4        | 1.56%   |
| Nvidia MCP61 Ethernet                                              | 4        | 1.56%   |
| Intel Ethernet Connection (7) I219-V                               | 4        | 1.56%   |
| Intel Ethernet Connection (2) I219-V                               | 4        | 1.56%   |
| Intel 82567LM-3 Gigabit Network Connection                         | 4        | 1.56%   |
| Intel Ethernet Connection I217-LM                                  | 3        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 3        | 1.17%   |
| Intel 82574L Gigabit Network Connection                            | 3        | 1.17%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                    | 3        | 1.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 2        | 0.78%   |
| TP-Link 802.11n NIC                                                | 2        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 2        | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 2        | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 2        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                    | 2        | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                    | 2        | 0.78%   |
| Intel Wireless-AC 9260                                             | 2        | 0.78%   |
| Intel Wireless 7260                                                | 2        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                           | 2        | 0.78%   |
| Intel 82567V-4 Gigabit Network Connection                          | 2        | 0.78%   |
| Intel 82567V-2 Gigabit Network Connection                          | 2        | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 2        | 0.78%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express      | 2        | 0.78%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 2        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                      | 2        | 0.78%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 2        | 0.78%   |
| ZyDAS ZD1211B 802.11g                                              | 1        | 0.39%   |
| Xiaomi SDM660-MTP _SN:6C524624                                     | 1        | 0.39%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                  | 1        | 0.39%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                              | 1        | 0.39%   |
| Sitecom Europe 802.11n WLAN Adapter                                | 1        | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                      | 1        | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.39%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 1        | 0.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 1        | 0.39%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.39%   |
| Realtek RTL8187 Wireless Adapter                                   | 1        | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                    | 1        | 0.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1        | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter              | 1        | 0.39%   |
| Ralink RT5572 Wireless Adapter                                     | 1        | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 1        | 0.39%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                               | 1        | 0.39%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                               | 1        | 0.39%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                          | 1        | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1        | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 1        | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1        | 0.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1        | 0.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 29.03%  |
| Realtek Semiconductor           | 16       | 25.81%  |
| TP-Link                         | 5        | 8.06%   |
| Ralink Technology               | 4        | 6.45%   |
| Ralink                          | 3        | 4.84%   |
| Qualcomm Atheros                | 3        | 4.84%   |
| ASUSTek Computer                | 3        | 4.84%   |
| Qualcomm Atheros Communications | 2        | 3.23%   |
| Linksys                         | 2        | 3.23%   |
| ZyDAS                           | 1        | 1.61%   |
| Xiaomi                          | 1        | 1.61%   |
| Sitecom Europe                  | 1        | 1.61%   |
| NetGear                         | 1        | 1.61%   |
| MediaTek                        | 1        | 1.61%   |
| Edimax Technology               | 1        | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 8        | 12.9%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 4        | 6.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 3        | 4.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 2        | 3.23%   |
| TP-Link 802.11n NIC                                                       | 2        | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2        | 3.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 2        | 3.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                           | 2        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                           | 2        | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                                           | 2        | 3.23%   |
| Intel Wireless-AC 9260                                                    | 2        | 3.23%   |
| Intel Wireless 7260                                                       | 2        | 3.23%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]        | 2        | 3.23%   |
| ZyDAS ZD1211B 802.11g                                                     | 1        | 1.61%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                         | 1        | 1.61%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                     | 1        | 1.61%   |
| Sitecom Europe 802.11n WLAN Adapter                                       | 1        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.61%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                           | 1        | 1.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.61%   |
| Realtek RTL8187 Wireless Adapter                                          | 1        | 1.61%   |
| Ralink RT5572 Wireless Adapter                                            | 1        | 1.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1        | 1.61%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                      | 1        | 1.61%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                      | 1        | 1.61%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 1        | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 1        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1        | 1.61%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.61%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                        | 1        | 1.61%   |
| Linksys WUSB6400M                                                         | 1        | 1.61%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]             | 1        | 1.61%   |
| Intel Wireless 7265                                                       | 1        | 1.61%   |
| Intel Wireless 3165                                                       | 1        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 1.61%   |
| Edimax AC600 USB                                                          | 1        | 1.61%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                 | 1        | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 88       | 46.32%  |
| Intel                 | 67       | 35.26%  |
| Broadcom              | 16       | 8.42%   |
| Qualcomm Atheros      | 5        | 2.63%   |
| Nvidia                | 5        | 2.63%   |
| Broadcom Limited      | 2        | 1.05%   |
| ASIX Electronics      | 2        | 1.05%   |
| Aquantia              | 2        | 1.05%   |
| Xiaomi                | 1        | 0.53%   |
| Samsung Electronics   | 1        | 0.53%   |
| D-Link System         | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77       | 39.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19       | 9.74%   |
| Intel I211 Gigabit Network Connection                             | 9        | 4.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8        | 4.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 3.08%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.56%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.05%   |
| Nvidia MCP61 Ethernet                                             | 4        | 2.05%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3        | 1.54%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.03%   |
| Intel 82567V-4 Gigabit Network Connection                         | 2        | 1.03%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 1.03%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 2        | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 1.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.03%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 1        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.51%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.51%   |
| Intel PRO/100 VE Network Connection                               | 1        | 0.51%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.51%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1        | 0.51%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.51%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.51%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.51%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.51%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.51%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 178      | 75.42%  |
| WiFi     | 58       | 24.58%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 153      | 77.27%  |
| WiFi     | 45       | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 137      | 76.11%  |
| 2     | 37       | 20.56%  |
| 3     | 4        | 2.22%   |
| 4     | 1        | 0.56%   |
| 0     | 1        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 168      | 93.33%  |
| Yes  | 12       | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 34.04%  |
| Cambridge Silicon Radio         | 15       | 31.91%  |
| Broadcom                        | 6        | 12.77%  |
| Realtek Semiconductor           | 2        | 4.26%   |
| Qualcomm Atheros Communications | 2        | 4.26%   |
| IMC Networks                    | 2        | 4.26%   |
| ASUSTek Computer                | 2        | 4.26%   |
| Lite-On Technology              | 1        | 2.13%   |
| Belkin Components               | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 15       | 31.91%  |
| Intel AX200 Bluetooth                                  | 7        | 14.89%  |
| Intel Bluetooth wireless interface                     | 4        | 8.51%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3        | 6.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                      | 3        | 6.38%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 2        | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1        | 2.13%   |
| Realtek Bluetooth Radio                                | 1        | 2.13%   |
| Lite-On Bluetooth Device                               | 1        | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1        | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 1        | 2.13%   |
| IMC Networks Bluetooth Radio                           | 1        | 2.13%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1        | 2.13%   |
| Broadcom Bluetooth 3.0 Device                          | 1        | 2.13%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter       | 1        | 2.13%   |
| Broadcom BCM2045 Bluetooth                             | 1        | 2.13%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter  | 1        | 2.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 1        | 2.13%   |
| ASUS ASUS USB-BT500                                    | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 122      | 44.85%  |
| AMD                      | 67       | 24.63%  |
| Nvidia                   | 56       | 20.59%  |
| C-Media Electronics      | 6        | 2.21%   |
| Razer USA                | 2        | 0.74%   |
| Logitech                 | 2        | 0.74%   |
| Kingston Technology      | 2        | 0.74%   |
| JMTek                    | 2        | 0.74%   |
| Generalplus Technology   | 2        | 0.74%   |
| Corsair                  | 2        | 0.74%   |
| XMOS                     | 1        | 0.37%   |
| Plantronics              | 1        | 0.37%   |
| Micro Star International | 1        | 0.37%   |
| Hewlett-Packard          | 1        | 0.37%   |
| Focusrite-Novation       | 1        | 0.37%   |
| Creative Technology      | 1        | 0.37%   |
| Creative Labs            | 1        | 0.37%   |
| BEHRINGER International  | 1        | 0.37%   |
| Alesis                   | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 25       | 7.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 23       | 7.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16       | 5.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15       | 4.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14       | 4.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 3.82%   |
| AMD Starship/Matisse HD Audio Controller                                          | 12       | 3.82%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 8        | 2.55%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 2.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 2.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 1.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 1.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.91%   |
| Nvidia High Definition Audio Controller                                           | 5        | 1.59%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 1.59%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.27%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.96%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.96%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.96%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                    | 3        | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 0.96%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 3        | 0.96%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 0.96%   |
| Nvidia TU104 HD Audio Controller                                                  | 2        | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.64%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.64%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 0.64%   |
| Kingston Technology HyperX Virtual Surround Sound                                 | 2        | 0.64%   |
| Intel USB PnP Sound Device                                                        | 2        | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.64%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.64%   |
| AMD FCH Azalia Controller                                                         | 2        | 0.64%   |
| XMOS Khadas Tone Control                                                          | 1        | 0.32%   |
| Razer USA Gaming Headset [Kraken USB]                                             | 1        | 0.32%   |
| Razer USA Electra V2 USB                                                          | 1        | 0.32%   |
| Plantronics Audio 655 DSP                                                         | 1        | 0.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.32%   |
| Nvidia MCP51 High Definition Audio                                                | 1        | 0.32%   |
| Nvidia GF104 High Definition Audio Controller                                     | 1        | 0.32%   |
| Micro Star International USB Audio                                                | 1        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 32       | 25%     |
| Kingston                   | 30       | 23.44%  |
| SK Hynix                   | 11       | 8.59%   |
| Corsair                    | 11       | 8.59%   |
| Crucial                    | 10       | 7.81%   |
| Samsung Electronics        | 9        | 7.03%   |
| G.Skill                    | 6        | 4.69%   |
| Smart                      | 3        | 2.34%   |
| Elpida                     | 3        | 2.34%   |
| Teikon                     | 2        | 1.56%   |
| Team                       | 2        | 1.56%   |
| Patriot                    | 2        | 1.56%   |
| Unknown (00FFFFFFFFFFFFFF) | 1        | 0.78%   |
| Transcend                  | 1        | 0.78%   |
| Nanya Technology           | 1        | 0.78%   |
| Micron Technology          | 1        | 0.78%   |
| GeIL                       | 1        | 0.78%   |
| atermiter                  | 1        | 0.78%   |
| A-DATA Technology          | 1        | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                              | 5        | 3.62%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                               | 2        | 1.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                    | 2        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                               | 2        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                | 2        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                                | 2        | 1.45%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                    | 2        | 1.45%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                      | 2        | 1.45%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                               | 2        | 1.45%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                        | 2        | 1.45%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s                      | 2        | 1.45%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s                      | 2        | 1.45%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4096MB DIMM DDR3 1333MT/s                     | 2        | 1.45%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s                       | 2        | 1.45%   |
| Unknown RAM Module 8192MB DIMM SDRAM                                       | 1        | 0.72%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                               | 1        | 0.72%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                                     | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                       | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                                | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                               | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                                     | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                     | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                                       | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                               | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 1067MT/s                               | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                                | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                     | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                     | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                       | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s                                | 1        | 0.72%   |
| Unknown RAM HB3DU002GFM8MML16 2048MB DIMM DDR3 1333MT/s                    | 1        | 0.72%   |
| Unknown RAM HB3DU002GFM8MMC16 2048MB DIMM DDR3 1600MT/s                    | 1        | 0.72%   |
| Unknown RAM CS4S2666D19321C 32GB SODIMM DDR4 2667MT/s                      | 1        | 0.72%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s  | 1        | 0.72%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                      | 1        | 0.72%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s                      | 1        | 0.72%   |
| Unknown (00FFFFFFFFFFFFFF) RAM 864AY-667D4 2048MB DIMM DDR2 667MT/s        | 1        | 0.72%   |
| Transcend RAM JM667QLU-2G 2048MB DIMM DDR2 667MT/s                         | 1        | 0.72%   |
| Teikon RAM TMT251U6CFR8C-PBH 4096MB DIMM DDR3 1333MT/s                     | 1        | 0.72%   |
| Teikon RAM TMT225U6FR8C-H9HC 2048MB DIMM DDR3 1066MT/s                     | 1        | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3200MT/s                     | 1        | 0.72%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                         | 1        | 0.72%   |
| Smart RAM SH564568FH8N6PHSFR 2048MB DIMM DDR3 1067MT/s                     | 1        | 0.72%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s                        | 1        | 0.72%   |
| Smart RAM SH564568FH8N6PHSF 2048MB DIMM DDR3 1333MT/s                      | 1        | 0.72%   |
| SK Hynix RAM MPPU4GBPC1600 00 4096MB DIMM 533MT/s                          | 1        | 0.72%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s                              | 1        | 0.72%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1600MT/s                              | 1        | 0.72%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1333MT/s                              | 1        | 0.72%   |
| SK Hynix RAM MMXIV 8GB DIMM DDR3 1600MT/s                                  | 1        | 0.72%   |
| SK Hynix RAM HMT41GU7AFR8C-PB 8192MB DIMM DDR3 1333MT/s                    | 1        | 0.72%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                     | 1        | 0.72%   |
| SK Hynix RAM HMA81GU6CJR8N-XN 8192MB DIMM DDR4 3200MT/s                    | 1        | 0.72%   |
| SK Hynix RAM 48594D503132355536344350382D53362020 2048MB DIMM DDR2 800MT/s | 1        | 0.72%   |
| Samsung RAM Module 8192MB DIMM DDR4 2400MT/s                               | 1        | 0.72%   |
| Samsung RAM Module 2048MB DIMM DDR3 1067MT/s                               | 1        | 0.72%   |
| Samsung RAM M391B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s                     | 1        | 0.72%   |
| Samsung RAM M378B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s                     | 1        | 0.72%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM DDR3 1867MT/s                     | 1        | 0.72%   |
| Samsung RAM M378B5173EB0-YK0 4096MB DIMM DDR3 1600MT/s                     | 1        | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 55       | 48.67%  |
| DDR4    | 29       | 25.66%  |
| DDR2    | 12       | 10.62%  |
| Unknown | 10       | 8.85%   |
| SDRAM   | 5        | 4.42%   |
| DDR     | 2        | 1.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 107      | 96.4%   |
| SODIMM | 4        | 3.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 36       | 29.51%  |
| 8192  | 33       | 27.05%  |
| 2048  | 32       | 26.23%  |
| 16384 | 13       | 10.66%  |
| 32768 | 4        | 3.28%   |
| 1024  | 4        | 3.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 27       | 22.88%  |
| 1600    | 24       | 20.34%  |
| 3200    | 11       | 9.32%   |
| 800     | 9        | 7.63%   |
| 2400    | 8        | 6.78%   |
| 667     | 8        | 6.78%   |
| 2667    | 6        | 5.08%   |
| 1067    | 3        | 2.54%   |
| 49926   | 2        | 1.69%   |
| 2666    | 2        | 1.69%   |
| 1867    | 2        | 1.69%   |
| 400     | 2        | 1.69%   |
| Unknown | 2        | 1.69%   |
| 3866    | 1        | 0.85%   |
| 3733    | 1        | 0.85%   |
| 3600    | 1        | 0.85%   |
| 3500    | 1        | 0.85%   |
| 3400    | 1        | 0.85%   |
| 3100    | 1        | 0.85%   |
| 2473    | 1        | 0.85%   |
| 2133    | 1        | 0.85%   |
| 1400    | 1        | 0.85%   |
| 1066    | 1        | 0.85%   |
| 533     | 1        | 0.85%   |
| 266     | 1        | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 7        | 50%     |
| Brother Industries     | 2        | 14.29%  |
| Seiko Epson            | 1        | 7.14%   |
| Samsung Electronics    | 1        | 7.14%   |
| Panasonic (Matsushita) | 1        | 7.14%   |
| Canon                  | 1        | 7.14%   |
| Bixolon                | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| HP LaserJet Professional P 1102w   | 2        | 13.33%  |
| Brother Printer                    | 2        | 13.33%  |
| Seiko Epson PX-105 Series          | 1        | 6.67%   |
| Samsung M2020 Series               | 1        | 6.67%   |
| Panasonic (Matsushita) KX-MB2130RU | 1        | 6.67%   |
| HP OfficeJet 6950                  | 1        | 6.67%   |
| HP LaserJet 1022                   | 1        | 6.67%   |
| HP Deskjet F4500 series            | 1        | 6.67%   |
| HP Deskjet 3050 J610 series        | 1        | 6.67%   |
| HP DeskJet 2130 series             | 1        | 6.67%   |
| Canon Pixma iP4500 Printer         | 1        | 6.67%   |
| Brother HL-3170CDW series          | 1        | 6.67%   |
| Bixolon Printer                    | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 33.33%  |
| Creative Technology           | 2        | 9.52%   |
| Apple                         | 2        | 9.52%   |
| Z-Star Microelectronics       | 1        | 4.76%   |
| Sweex                         | 1        | 4.76%   |
| Sunplus Innovation Technology | 1        | 4.76%   |
| Microsoft                     | 1        | 4.76%   |
| Microdia                      | 1        | 4.76%   |
| KYE Systems (Mouse Systems)   | 1        | 4.76%   |
| IMC Networks                  | 1        | 4.76%   |
| Chicony Electronics           | 1        | 4.76%   |
| Aveo Technology               | 1        | 4.76%   |
| ARC International             | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Logitech Webcam C270                         | 2        | 9.09%   |
| Apple iPhone 5/5C/5S/6/SE                    | 2        | 9.09%   |
| Z-Star Venus USB2.0 Camera                   | 1        | 4.55%   |
| Sweex WC060 Series HD Webcam                 | 1        | 4.55%   |
| Sunplus Integrated_Webcam_HD                 | 1        | 4.55%   |
| Microsoft LifeCam HD-3000                    | 1        | 4.55%   |
| Microdia Integrated Camera                   | 1        | 4.55%   |
| Logitech Webcam C930e                        | 1        | 4.55%   |
| Logitech Webcam C170                         | 1        | 4.55%   |
| Logitech QuickCam Pro 9000                   | 1        | 4.55%   |
| Logitech QuickCam Deluxe for Notebooks       | 1        | 4.55%   |
| Logitech HD Webcam C525                      | 1        | 4.55%   |
| Logitech HD Pro Webcam C920                  | 1        | 4.55%   |
| KYE Systems (Mouse Systems) Genius iSlim 330 | 1        | 4.55%   |
| IMC Networks XHC Camera                      | 1        | 4.55%   |
| Creative Live! Cam Video IM Pro              | 1        | 4.55%   |
| Creative Live! Cam Chat HD [VF0700]          | 1        | 4.55%   |
| Chicony Gateway Webcam                       | 1        | 4.55%   |
| Aveo UVC camera (Bresser microscope)         | 1        | 4.55%   |
| ARC International Camera                     | 1        | 4.55%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 168      | 93.33%  |
| 1     | 11       | 6.11%   |
| 2     | 1        | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 3        | 25%     |
| Net/wireless             | 2        | 16.67%  |
| Graphics card            | 2        | 16.67%  |
| Unassigned class         | 1        | 8.33%   |
| Tv card                  | 1        | 8.33%   |
| Storage/ata              | 1        | 8.33%   |
| Network                  | 1        | 8.33%   |
| Multimedia controller    | 1        | 8.33%   |

