Gentoo - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Gentoo.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 918

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [474bb81b18](https://linux-hardware.org/?probe=474bb81b18) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [f6a1a50a75](https://linux-hardware.org/?probe=f6a1a50a75) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d14605acc1](https://linux-hardware.org/?probe=d14605acc1) | Apr 15, 2022 |
| ASUSTek       | Z97-K/USB                   | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASRock        | A320M-ITX                   | [eaf6bbd74e](https://linux-hardware.org/?probe=eaf6bbd74e) | Apr 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [68dd0c90a1](https://linux-hardware.org/?probe=68dd0c90a1) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| ASUSTek       | M3A78-CM                    | [8bfef0e6a5](https://linux-hardware.org/?probe=8bfef0e6a5) | Apr 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [76f3ee9c71](https://linux-hardware.org/?probe=76f3ee9c71) | Apr 10, 2022 |
| ASRock        | Z390 Extreme4               | [1bd70fbd59](https://linux-hardware.org/?probe=1bd70fbd59) | Apr 09, 2022 |
| Gigabyte      | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| MSI           | MAG B550 TORPEDO            | [ce26da001a](https://linux-hardware.org/?probe=ce26da001a) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [8aad15d96c](https://linux-hardware.org/?probe=8aad15d96c) | Apr 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | M3A78-CM                    | [718536ba53](https://linux-hardware.org/?probe=718536ba53) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [5bcff46ee9](https://linux-hardware.org/?probe=5bcff46ee9) | Apr 04, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [df1549bb3b](https://linux-hardware.org/?probe=df1549bb3b) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| Gigabyte      | X570 GAMING X               | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| ASRock        | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| Gigabyte      | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f4e6e46fc5](https://linux-hardware.org/?probe=f4e6e46fc5) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| ASUSTek       | M3A78-CM                    | [ff9f133207](https://linux-hardware.org/?probe=ff9f133207) | Mar 22, 2022 |
| MSI           | MAG B550M MORTAR            | [78b6d2b02e](https://linux-hardware.org/?probe=78b6d2b02e) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8ed2aea22d](https://linux-hardware.org/?probe=8ed2aea22d) | Mar 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [a2b06f49d3](https://linux-hardware.org/?probe=a2b06f49d3) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [9e32abccd6](https://linux-hardware.org/?probe=9e32abccd6) | Mar 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| Dell          | 0J37VM A00                  | [bbcd3639ab](https://linux-hardware.org/?probe=bbcd3639ab) | Mar 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| MSI           | B560M PRO-VDH WIFI          | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| ASUSTek       | M3A78-CM                    | [9d4cae40f3](https://linux-hardware.org/?probe=9d4cae40f3) | Mar 15, 2022 |
| ASUSTek       | PRIME J4005I-C              | [707cb5ce3b](https://linux-hardware.org/?probe=707cb5ce3b) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-302         | [20682db2fa](https://linux-hardware.org/?probe=20682db2fa) | Mar 14, 2022 |
| Alienware     | 0TYR0X A00                  | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| Dell          | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| ASUSTek       | M3A78-CM                    | [df73d6674b](https://linux-hardware.org/?probe=df73d6674b) | Mar 08, 2022 |
| Gigabyte      | Z590 UD                     | [392c7890c2](https://linux-hardware.org/?probe=392c7890c2) | Mar 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| ASRock        | A300M-STX                   | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| ASUSTek       | M3A78-CM                    | [17fac3a991](https://linux-hardware.org/?probe=17fac3a991) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4c3afa7f](https://linux-hardware.org/?probe=6d4c3afa7f) | Feb 27, 2022 |
| Gigabyte      | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte      | Z590 UD                     | [06d8d67698](https://linux-hardware.org/?probe=06d8d67698) | Feb 24, 2022 |
| Gigabyte      | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Alienware     | 0TYR0X A00                  | [892e886901](https://linux-hardware.org/?probe=892e886901) | Feb 23, 2022 |
| Alienware     | 0TYR0X A00                  | [71cac3ebdd](https://linux-hardware.org/?probe=71cac3ebdd) | Feb 22, 2022 |
| ASUSTek       | M3A78-CM                    | [8991bf4fbe](https://linux-hardware.org/?probe=8991bf4fbe) | Feb 22, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [6d5688db26](https://linux-hardware.org/?probe=6d5688db26) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [e2ae01f560](https://linux-hardware.org/?probe=e2ae01f560) | Feb 21, 2022 |
| MSI           | H81I                        | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [1429fd9ed5](https://linux-hardware.org/?probe=1429fd9ed5) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | [859adc5b97](https://linux-hardware.org/?probe=859adc5b97) | Feb 19, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [eddf69336b](https://linux-hardware.org/?probe=eddf69336b) | Feb 18, 2022 |
| Gigabyte      | B460 HD3                    | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| ASUSTek       | M3A78-CM                    | [0ac87ac69d](https://linux-hardware.org/?probe=0ac87ac69d) | Feb 15, 2022 |
| YANYU         | H17SL                       | [0a6638d9c9](https://linux-hardware.org/?probe=0a6638d9c9) | Feb 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| YANYU         | H17SL                       | [9fabebacc4](https://linux-hardware.org/?probe=9fabebacc4) | Feb 09, 2022 |
| ASRock        | B450 Pro4                   | [9f05ddfb03](https://linux-hardware.org/?probe=9f05ddfb03) | Feb 08, 2022 |
| ASUSTek       | M3A78-CM                    | [1bcbf673fb](https://linux-hardware.org/?probe=1bcbf673fb) | Feb 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| YANYU         | H17SL                       | [cd763ca612](https://linux-hardware.org/?probe=cd763ca612) | Feb 06, 2022 |
| Supermicro    | A1SRM-2758F                 | [33b8806332](https://linux-hardware.org/?probe=33b8806332) | Feb 05, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [59d4e2a5b2](https://linux-hardware.org/?probe=59d4e2a5b2) | Feb 04, 2022 |
| Gigabyte      | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASUSTek       | M3A78-CM                    | [bf11db84ee](https://linux-hardware.org/?probe=bf11db84ee) | Feb 01, 2022 |
| ASUSTek       | PRIME B450M-K               | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [f56c7ea90a](https://linux-hardware.org/?probe=f56c7ea90a) | Jan 29, 2022 |
| ASRock        | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| ASRock        | A88M-G                      | [bb3847af5e](https://linux-hardware.org/?probe=bb3847af5e) | Jan 27, 2022 |
| ASRock        | A88M-G                      | [7f86f91b8f](https://linux-hardware.org/?probe=7f86f91b8f) | Jan 27, 2022 |
| ASUSTek       | M3A78-CM                    | [f683b8cc85](https://linux-hardware.org/?probe=f683b8cc85) | Jan 25, 2022 |
| Gigabyte      | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [db8b77c1ff](https://linux-hardware.org/?probe=db8b77c1ff) | Jan 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [236b39c9bb](https://linux-hardware.org/?probe=236b39c9bb) | Jan 23, 2022 |
| Gigabyte      | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| ASUSTek       | PRIME B450M-K               | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | [d1697052d6](https://linux-hardware.org/?probe=d1697052d6) | Jan 20, 2022 |
| ASUSTek       | PRIME B450M-K               | [23f6223c1a](https://linux-hardware.org/?probe=23f6223c1a) | Jan 19, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | M3A78-CM                    | [0df79731c2](https://linux-hardware.org/?probe=0df79731c2) | Jan 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [bd9fb4fcc1](https://linux-hardware.org/?probe=bd9fb4fcc1) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [81642886bd](https://linux-hardware.org/?probe=81642886bd) | Jan 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [869a119983](https://linux-hardware.org/?probe=869a119983) | Jan 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [b9999bcf7a](https://linux-hardware.org/?probe=b9999bcf7a) | Jan 17, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5ac089dd21](https://linux-hardware.org/?probe=5ac089dd21) | Jan 16, 2022 |
| ASRock        | AM1H-ITX                    | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | [73773b7de6](https://linux-hardware.org/?probe=73773b7de6) | Jan 16, 2022 |
| Lenovo        | 0B98401 PRO                 | [a3711dfcf9](https://linux-hardware.org/?probe=a3711dfcf9) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [c973a9bc0d](https://linux-hardware.org/?probe=c973a9bc0d) | Jan 15, 2022 |
| ASUSTek       | M3A78-CM                    | [cba1c5dc66](https://linux-hardware.org/?probe=cba1c5dc66) | Jan 11, 2022 |
| ASRock        | AM1H-ITX                    | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| ASRock        | X370 Gaming X               | [e233d7c495](https://linux-hardware.org/?probe=e233d7c495) | Jan 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [dfe8ad0ecc](https://linux-hardware.org/?probe=dfe8ad0ecc) | Jan 09, 2022 |
| ASRock        | AM1H-ITX                    | [9cdc9e341f](https://linux-hardware.org/?probe=9cdc9e341f) | Jan 09, 2022 |
| Gigabyte      | B460 HD3                    | [99b99bd757](https://linux-hardware.org/?probe=99b99bd757) | Jan 09, 2022 |
| ASRock        | Q1900-ITX                   | [a0983541e3](https://linux-hardware.org/?probe=a0983541e3) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | [37963d9ed0](https://linux-hardware.org/?probe=37963d9ed0) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| ASUSTek       | M3A78-CM                    | [94b3299adb](https://linux-hardware.org/?probe=94b3299adb) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [582c2d190f](https://linux-hardware.org/?probe=582c2d190f) | Jan 03, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [519b9f223e](https://linux-hardware.org/?probe=519b9f223e) | Jan 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [0c97be2fbd](https://linux-hardware.org/?probe=0c97be2fbd) | Jan 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [87bdd946c8](https://linux-hardware.org/?probe=87bdd946c8) | Jan 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [cd39962883](https://linux-hardware.org/?probe=cd39962883) | Jan 02, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [f24a673d9b](https://linux-hardware.org/?probe=f24a673d9b) | Dec 29, 2021 |
| ASUSTek       | M3A78-CM                    | [f82bc92e4c](https://linux-hardware.org/?probe=f82bc92e4c) | Dec 28, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d7e698988e](https://linux-hardware.org/?probe=d7e698988e) | Dec 26, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| EVGA          | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [53288b1a8b](https://linux-hardware.org/?probe=53288b1a8b) | Dec 23, 2021 |
| Dell          | 0J3C2F A02                  | [a450e584b2](https://linux-hardware.org/?probe=a450e584b2) | Dec 22, 2021 |
| ASUSTek       | M3A78-CM                    | [57b9900cc0](https://linux-hardware.org/?probe=57b9900cc0) | Dec 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [0ac5deaeca](https://linux-hardware.org/?probe=0ac5deaeca) | Dec 19, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f55494010a](https://linux-hardware.org/?probe=f55494010a) | Dec 19, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Dell          | 0J3C2F A02                  | [b6d326beab](https://linux-hardware.org/?probe=b6d326beab) | Dec 16, 2021 |
| MSI           | Z87-G45 GAMING              | [882428b431](https://linux-hardware.org/?probe=882428b431) | Dec 15, 2021 |
| ASUSTek       | M3A78-CM                    | [48f2a95a53](https://linux-hardware.org/?probe=48f2a95a53) | Dec 13, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [89ed93528f](https://linux-hardware.org/?probe=89ed93528f) | Dec 12, 2021 |
| ASUSTek       | M3N78-EM                    | [bf180c5c33](https://linux-hardware.org/?probe=bf180c5c33) | Dec 11, 2021 |
| MSI           | B450 TOMAHAWK               | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [87c78340f0](https://linux-hardware.org/?probe=87c78340f0) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | M3A78-CM                    | [22484fa0ea](https://linux-hardware.org/?probe=22484fa0ea) | Dec 06, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a523b2cfda](https://linux-hardware.org/?probe=a523b2cfda) | Dec 05, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| Dell          | 0J584C A00                  | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek       | M3A78-CM                    | [9b27bd81d4](https://linux-hardware.org/?probe=9b27bd81d4) | Nov 29, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [32229aacc0](https://linux-hardware.org/?probe=32229aacc0) | Nov 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b0329b0b3f](https://linux-hardware.org/?probe=b0329b0b3f) | Nov 25, 2021 |
| MSI           | MEG X570 UNIFY              | [4492677869](https://linux-hardware.org/?probe=4492677869) | Nov 24, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [8145468390](https://linux-hardware.org/?probe=8145468390) | Nov 22, 2021 |
| ASUSTek       | M3A78-CM                    | [ceb2034a96](https://linux-hardware.org/?probe=ceb2034a96) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a480e068e3](https://linux-hardware.org/?probe=a480e068e3) | Nov 21, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [d8c73031f1](https://linux-hardware.org/?probe=d8c73031f1) | Nov 20, 2021 |
| Gigabyte      | H310M S2H x.x               | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| ASUSTek       | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | M3A78-CM                    | [d6be18a4ed](https://linux-hardware.org/?probe=d6be18a4ed) | Nov 15, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [9709dc440a](https://linux-hardware.org/?probe=9709dc440a) | Nov 14, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [6680b20a17](https://linux-hardware.org/?probe=6680b20a17) | Nov 13, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a72afdad07](https://linux-hardware.org/?probe=a72afdad07) | Nov 07, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASRock        | B550M Steel Legend          | [d805977d04](https://linux-hardware.org/?probe=d805977d04) | Nov 06, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| ASUSTek       | PRIME X570-P                | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| MSI           | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek       | M3A78-CM                    | [9fa6c52f38](https://linux-hardware.org/?probe=9fa6c52f38) | Nov 01, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [3ab561bbe8](https://linux-hardware.org/?probe=3ab561bbe8) | Oct 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| Gigabyte      | B460 HD3                    | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASRock        | B550M Steel Legend          | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| HP            | 0B4Ch D                     | [eb0c052885](https://linux-hardware.org/?probe=eb0c052885) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| ASUSTek       | M3A78-CM                    | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [303af363ac](https://linux-hardware.org/?probe=303af363ac) | Oct 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASRock        | X570 Pro4                   | [ba339b925b](https://linux-hardware.org/?probe=ba339b925b) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| ASUSTek       | M3A78-CM                    | [f262f89cbe](https://linux-hardware.org/?probe=f262f89cbe) | Oct 18, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [21110235eb](https://linux-hardware.org/?probe=21110235eb) | Oct 18, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [6933291565](https://linux-hardware.org/?probe=6933291565) | Oct 17, 2021 |
| ASRock        | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [e023c19122](https://linux-hardware.org/?probe=e023c19122) | Oct 17, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [8b5c674cb9](https://linux-hardware.org/?probe=8b5c674cb9) | Oct 17, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [38a6005914](https://linux-hardware.org/?probe=38a6005914) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [a6457a6f8e](https://linux-hardware.org/?probe=a6457a6f8e) | Oct 15, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [5d6b978099](https://linux-hardware.org/?probe=5d6b978099) | Oct 14, 2021 |
| ASRock        | Z390 Extreme4               | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| ASUSTek       | M3A78-CM                    | [2545b52894](https://linux-hardware.org/?probe=2545b52894) | Oct 11, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [786678fb4c](https://linux-hardware.org/?probe=786678fb4c) | Oct 10, 2021 |
| MSI           | MEG X570 UNIFY              | [2e312a734f](https://linux-hardware.org/?probe=2e312a734f) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [8319b2b5c6](https://linux-hardware.org/?probe=8319b2b5c6) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [b1178bb939](https://linux-hardware.org/?probe=b1178bb939) | Oct 07, 2021 |
| Gigabyte      | B450M DS3H V2               | [233f451319](https://linux-hardware.org/?probe=233f451319) | Oct 06, 2021 |
| HP            | 0B4Ch D                     | [02b5492901](https://linux-hardware.org/?probe=02b5492901) | Oct 06, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [67fc73c11e](https://linux-hardware.org/?probe=67fc73c11e) | Oct 04, 2021 |
| ASUSTek       | M3A78-CM                    | [a786c3ecec](https://linux-hardware.org/?probe=a786c3ecec) | Oct 04, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d53525d772](https://linux-hardware.org/?probe=d53525d772) | Oct 03, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| MSI           | Z370-A PRO                  | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [5ce182d7ae](https://linux-hardware.org/?probe=5ce182d7ae) | Oct 01, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [4044b3b3b2](https://linux-hardware.org/?probe=4044b3b3b2) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [6b625a8736](https://linux-hardware.org/?probe=6b625a8736) | Oct 01, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [87f779767d](https://linux-hardware.org/?probe=87f779767d) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| ASRock        | H170 Pro4                   | [a0d0f5002e](https://linux-hardware.org/?probe=a0d0f5002e) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | [5a3652f38b](https://linux-hardware.org/?probe=5a3652f38b) | Sep 29, 2021 |
| Gigabyte      | 990FXA-UD5                  | [c3bb6d3afa](https://linux-hardware.org/?probe=c3bb6d3afa) | Sep 29, 2021 |
| Dell          | 0J3C2F A02                  | [88104169a4](https://linux-hardware.org/?probe=88104169a4) | Sep 28, 2021 |
| ASUSTek       | M3A78-CM                    | [6057971f46](https://linux-hardware.org/?probe=6057971f46) | Sep 27, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [02d9cece31](https://linux-hardware.org/?probe=02d9cece31) | Sep 26, 2021 |
| ASUSTek       | TUF GAMING B450M-PLUS II    | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| ASRock        | X370 Professional Gaming    | [546f692061](https://linux-hardware.org/?probe=546f692061) | Sep 23, 2021 |
| Intel         | DG31PR AAD97573-205         | [2c022c21f0](https://linux-hardware.org/?probe=2c022c21f0) | Sep 22, 2021 |
| ASUSTek       | M3A78-CM                    | [1f6b39fcd2](https://linux-hardware.org/?probe=1f6b39fcd2) | Sep 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [5afde8487e](https://linux-hardware.org/?probe=5afde8487e) | Sep 19, 2021 |
| Gigabyte      | B460 HD3                    | [fcd5acbc90](https://linux-hardware.org/?probe=fcd5acbc90) | Sep 18, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [86d356f643](https://linux-hardware.org/?probe=86d356f643) | Sep 16, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Dell          | 0YJPT1 A00                  | [69d571e9f5](https://linux-hardware.org/?probe=69d571e9f5) | Sep 15, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [308d39b0dc](https://linux-hardware.org/?probe=308d39b0dc) | Sep 15, 2021 |
| ASUSTek       | M3A78-CM                    | [59eb80534c](https://linux-hardware.org/?probe=59eb80534c) | Sep 13, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [cfdc619c18](https://linux-hardware.org/?probe=cfdc619c18) | Sep 12, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| ASUSTek       | M3A78-CM                    | [e89cd90c72](https://linux-hardware.org/?probe=e89cd90c72) | Sep 06, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [0fc45210cc](https://linux-hardware.org/?probe=0fc45210cc) | Sep 05, 2021 |
| ASRock        | B450M-HDV R4.0              | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [f63a2003ab](https://linux-hardware.org/?probe=f63a2003ab) | Sep 05, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [40d01ef03e](https://linux-hardware.org/?probe=40d01ef03e) | Aug 31, 2021 |
| Packard Be... | FMCP7AM                     | [6872ae9fb4](https://linux-hardware.org/?probe=6872ae9fb4) | Aug 31, 2021 |
| ASUSTek       | M3A78-CM                    | [195d8fb53d](https://linux-hardware.org/?probe=195d8fb53d) | Aug 30, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [bb19294c8b](https://linux-hardware.org/?probe=bb19294c8b) | Aug 29, 2021 |
| Gigabyte      | EP43-DS3                    | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Dell          | 0U1325                      | [0a58fab188](https://linux-hardware.org/?probe=0a58fab188) | Aug 28, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [00b0f43680](https://linux-hardware.org/?probe=00b0f43680) | Aug 28, 2021 |
| Packard Be... | FMCP7AM                     | [07fb4f5678](https://linux-hardware.org/?probe=07fb4f5678) | Aug 28, 2021 |
| MSI           | MS-7369                     | [0c6668dee5](https://linux-hardware.org/?probe=0c6668dee5) | Aug 28, 2021 |
| Dell          | 0U1325                      | [1b5dfb4b59](https://linux-hardware.org/?probe=1b5dfb4b59) | Aug 28, 2021 |
| ASUSTek       | P9X79 WS                    | [0569365ea0](https://linux-hardware.org/?probe=0569365ea0) | Aug 26, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [5ff45958cf](https://linux-hardware.org/?probe=5ff45958cf) | Aug 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f521a0c69c](https://linux-hardware.org/?probe=f521a0c69c) | Aug 25, 2021 |
| MSI           | B450M PRO-M2 MAX            | [c09944da60](https://linux-hardware.org/?probe=c09944da60) | Aug 24, 2021 |
| ASUSTek       | M3A78-CM                    | [63f0c13a1f](https://linux-hardware.org/?probe=63f0c13a1f) | Aug 23, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [625e0cf2b0](https://linux-hardware.org/?probe=625e0cf2b0) | Aug 22, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [c6aaf9451f](https://linux-hardware.org/?probe=c6aaf9451f) | Aug 22, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASUSTek       | P5P41C                      | [0eb4111089](https://linux-hardware.org/?probe=0eb4111089) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [4eb4c77752](https://linux-hardware.org/?probe=4eb4c77752) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5ffe57957d](https://linux-hardware.org/?probe=5ffe57957d) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [40f0739800](https://linux-hardware.org/?probe=40f0739800) | Aug 17, 2021 |
| ASUSTek       | M3A78-CM                    | [51860b7bbc](https://linux-hardware.org/?probe=51860b7bbc) | Aug 16, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [211803a510](https://linux-hardware.org/?probe=211803a510) | Aug 15, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d86ce68f12](https://linux-hardware.org/?probe=d86ce68f12) | Aug 15, 2021 |
| MSI           | B550-A PRO                  | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| HP            | 158B                        | [d47aa82b20](https://linux-hardware.org/?probe=d47aa82b20) | Aug 12, 2021 |
| Unknown       | Unknown                     | [711599ea49](https://linux-hardware.org/?probe=711599ea49) | Aug 11, 2021 |
| Intel         | D525MW AAE93082-301         | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [50f209f0b0](https://linux-hardware.org/?probe=50f209f0b0) | Aug 08, 2021 |
| ASUSTek       | M3A78-CM                    | [1fce864564](https://linux-hardware.org/?probe=1fce864564) | Aug 08, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [33fffaf1c3](https://linux-hardware.org/?probe=33fffaf1c3) | Aug 07, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [06b423ce94](https://linux-hardware.org/?probe=06b423ce94) | Aug 01, 2021 |
| ASUSTek       | P6T DELUXE V2               | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| Dell          | 09WH54 A00                  | [9885d45d4f](https://linux-hardware.org/?probe=9885d45d4f) | Jul 28, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [46b71409d7](https://linux-hardware.org/?probe=46b71409d7) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| ASUSTek       | M3A78-CM                    | [124c34e0b9](https://linux-hardware.org/?probe=124c34e0b9) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [ed43bc183f](https://linux-hardware.org/?probe=ed43bc183f) | Jul 25, 2021 |
| Gigabyte      | 990FXA-UD5                  | [9f22a47aea](https://linux-hardware.org/?probe=9f22a47aea) | Jul 22, 2021 |
| Gigabyte      | 990FXA-UD5                  | [5a32ec902e](https://linux-hardware.org/?probe=5a32ec902e) | Jul 22, 2021 |
| Gigabyte      | H110-D3-CF                  | [7d25217f50](https://linux-hardware.org/?probe=7d25217f50) | Jul 22, 2021 |
| ASUSTek       | M3A78-CM                    | [0c48353545](https://linux-hardware.org/?probe=0c48353545) | Jul 19, 2021 |
| Gigabyte      | B460 HD3                    | [e92a7942d5](https://linux-hardware.org/?probe=e92a7942d5) | Jul 18, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [6ab13b1c74](https://linux-hardware.org/?probe=6ab13b1c74) | Jul 18, 2021 |
| Gigabyte      | B460 HD3                    | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [9356542b15](https://linux-hardware.org/?probe=9356542b15) | Jul 12, 2021 |
| ASUSTek       | M3A78-CM                    | [689a063b2b](https://linux-hardware.org/?probe=689a063b2b) | Jul 12, 2021 |
| ASRock        | B550M Steel Legend          | [4d378eb681](https://linux-hardware.org/?probe=4d378eb681) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| ASRock        | B550M Steel Legend          | [ab93056d13](https://linux-hardware.org/?probe=ab93056d13) | Jul 08, 2021 |
| ASUSTek       | M3A78-CM                    | [d185d2fa34](https://linux-hardware.org/?probe=d185d2fa34) | Jul 05, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [8c345139d0](https://linux-hardware.org/?probe=8c345139d0) | Jul 04, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [4ef1e3ccac](https://linux-hardware.org/?probe=4ef1e3ccac) | Jul 03, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [4e618f85f9](https://linux-hardware.org/?probe=4e618f85f9) | Jul 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| MSI           | B450 TOMAHAWK               | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [b0e19feab6](https://linux-hardware.org/?probe=b0e19feab6) | Jun 27, 2021 |
| ASUSTek       | M3A78-CM                    | [1a5b5e8bf0](https://linux-hardware.org/?probe=1a5b5e8bf0) | Jun 27, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Apple         | Mac-F221BEC8                | [84bf6743c1](https://linux-hardware.org/?probe=84bf6743c1) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | [ced7e0d00d](https://linux-hardware.org/?probe=ced7e0d00d) | Jun 25, 2021 |
| ASUSTek       | Rampage V EXTREME           | [4add1f32e4](https://linux-hardware.org/?probe=4add1f32e4) | Jun 23, 2021 |
| Unknown       | Unknown                     | [bb64d32fdf](https://linux-hardware.org/?probe=bb64d32fdf) | Jun 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [0f95a638f3](https://linux-hardware.org/?probe=0f95a638f3) | Jun 20, 2021 |
| ASUSTek       | M3A78-CM                    | [670b5ad32f](https://linux-hardware.org/?probe=670b5ad32f) | Jun 18, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f0c7a3a628](https://linux-hardware.org/?probe=f0c7a3a628) | Jun 15, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [c429704651](https://linux-hardware.org/?probe=c429704651) | Jun 15, 2021 |
| ASUSTek       | P7P55D-E PRO                | [9a91c78c7a](https://linux-hardware.org/?probe=9a91c78c7a) | Jun 14, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [5dfa929798](https://linux-hardware.org/?probe=5dfa929798) | Jun 13, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| ASUSTek       | M3A78-CM                    | [99786fffad](https://linux-hardware.org/?probe=99786fffad) | Jun 11, 2021 |
| MSI           | Z590-A PRO                  | [46c5072a2d](https://linux-hardware.org/?probe=46c5072a2d) | Jun 08, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [cb5c9ef223](https://linux-hardware.org/?probe=cb5c9ef223) | Jun 06, 2021 |
| ASUSTek       | M3A78-CM                    | [e3e4d9d467](https://linux-hardware.org/?probe=e3e4d9d467) | Jun 04, 2021 |
| MSI           | Z97 PC Mate                 | [73ece6c322](https://linux-hardware.org/?probe=73ece6c322) | Jun 02, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a04eb698f8](https://linux-hardware.org/?probe=a04eb698f8) | May 30, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [7fd8ecaab2](https://linux-hardware.org/?probe=7fd8ecaab2) | May 30, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [2767965856](https://linux-hardware.org/?probe=2767965856) | May 27, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [67b0fcc402](https://linux-hardware.org/?probe=67b0fcc402) | May 27, 2021 |
| ASUSTek       | M3A78-CM                    | [3b96e27283](https://linux-hardware.org/?probe=3b96e27283) | May 26, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [843f1d9b38](https://linux-hardware.org/?probe=843f1d9b38) | May 25, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [5794d366c2](https://linux-hardware.org/?probe=5794d366c2) | May 25, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [e3bed34a3f](https://linux-hardware.org/?probe=e3bed34a3f) | May 23, 2021 |
| MSI           | X570-A PRO                  | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| MSI           | X570-A PRO                  | [23efe4a1c8](https://linux-hardware.org/?probe=23efe4a1c8) | May 22, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Unknown       | Cubietech Cubieboard2       | [d777d4b535](https://linux-hardware.org/?probe=d777d4b535) | May 22, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [95fb77ceae](https://linux-hardware.org/?probe=95fb77ceae) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | [5104abb7a7](https://linux-hardware.org/?probe=5104abb7a7) | May 20, 2021 |
| MSI           | Z590-A PRO                  | [7927669f65](https://linux-hardware.org/?probe=7927669f65) | May 20, 2021 |
| HP            | 8643 SMVB                   | [b183baddef](https://linux-hardware.org/?probe=b183baddef) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4f3165b957](https://linux-hardware.org/?probe=4f3165b957) | May 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2679a5931a](https://linux-hardware.org/?probe=2679a5931a) | May 19, 2021 |
| ASUSTek       | M3A78-CM                    | [260b86810f](https://linux-hardware.org/?probe=260b86810f) | May 19, 2021 |
| ASRock        | B450 Pro4                   | [7ae6a0f74b](https://linux-hardware.org/?probe=7ae6a0f74b) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [0df80890c0](https://linux-hardware.org/?probe=0df80890c0) | May 17, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [cd60485f57](https://linux-hardware.org/?probe=cd60485f57) | May 16, 2021 |
| MSI           | Z590-A PRO                  | [8548e79e77](https://linux-hardware.org/?probe=8548e79e77) | May 16, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| ASUSTek       | PRIME X470-PRO              | [065d69be16](https://linux-hardware.org/?probe=065d69be16) | May 13, 2021 |
| ASUSTek       | PRIME B450M-K               | [6bfaa47826](https://linux-hardware.org/?probe=6bfaa47826) | May 13, 2021 |
| ASUSTek       | PRIME B450M-K               | [77a0428e6b](https://linux-hardware.org/?probe=77a0428e6b) | May 13, 2021 |
| ASUSTek       | M3A78-CM                    | [9e4b4373e8](https://linux-hardware.org/?probe=9e4b4373e8) | May 12, 2021 |
| ASUSTek       | PRIME B450M-K               | [88e106999e](https://linux-hardware.org/?probe=88e106999e) | May 11, 2021 |
| ASUSTek       | PRIME B450M-K               | [2b14268533](https://linux-hardware.org/?probe=2b14268533) | May 10, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [c1dcdec760](https://linux-hardware.org/?probe=c1dcdec760) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | M3A78-CM                    | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [801e6126b5](https://linux-hardware.org/?probe=801e6126b5) | May 02, 2021 |
| ASUSTek       | PRIME B450M-K               | [d7ab2def9e](https://linux-hardware.org/?probe=d7ab2def9e) | May 01, 2021 |
| ASUSTek       | PRIME B450M-K               | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [ff1723016b](https://linux-hardware.org/?probe=ff1723016b) | Apr 27, 2021 |
| ASUSTek       | M3A78-CM                    | [677dc5a3c6](https://linux-hardware.org/?probe=677dc5a3c6) | Apr 26, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [48789cb28c](https://linux-hardware.org/?probe=48789cb28c) | Apr 25, 2021 |
| Unknown       | Freecom Silverstore HNCN... | [c54d9f2c0c](https://linux-hardware.org/?probe=c54d9f2c0c) | Apr 23, 2021 |
| Unknown       | Unknown                     | [160f692db0](https://linux-hardware.org/?probe=160f692db0) | Apr 23, 2021 |
| ASUSTek       | M3A78-CM                    | [75a7ea3b75](https://linux-hardware.org/?probe=75a7ea3b75) | Apr 19, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [94022dc903](https://linux-hardware.org/?probe=94022dc903) | Apr 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [0db8148a33](https://linux-hardware.org/?probe=0db8148a33) | Apr 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5bc34889b8](https://linux-hardware.org/?probe=5bc34889b8) | Apr 17, 2021 |
| ASUSTek       | M3A78-CM                    | [ccb567c754](https://linux-hardware.org/?probe=ccb567c754) | Apr 12, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [aa6385c431](https://linux-hardware.org/?probe=aa6385c431) | Apr 11, 2021 |
| MSI           | H310M PRO-VD PLUS           | [de7b86720f](https://linux-hardware.org/?probe=de7b86720f) | Apr 10, 2021 |
| ASRock        | C2550D4I                    | [c881809c02](https://linux-hardware.org/?probe=c881809c02) | Apr 09, 2021 |
| ASRockRack    | E3C232D2I                   | [5f8788ee08](https://linux-hardware.org/?probe=5f8788ee08) | Apr 09, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [07427b8218](https://linux-hardware.org/?probe=07427b8218) | Apr 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [ab8b789fc2](https://linux-hardware.org/?probe=ab8b789fc2) | Apr 06, 2021 |
| Gigabyte      | B450M AORUS ELITE           | [62a8a899ed](https://linux-hardware.org/?probe=62a8a899ed) | Apr 05, 2021 |
| ASUSTek       | M3A78-CM                    | [8feef9482d](https://linux-hardware.org/?probe=8feef9482d) | Apr 05, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [d51b8b7f04](https://linux-hardware.org/?probe=d51b8b7f04) | Apr 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| ASUSTek       | P8H67-M PRO                 | [95722413a6](https://linux-hardware.org/?probe=95722413a6) | Mar 29, 2021 |
| ASUSTek       | M3A78-CM                    | [6a2de1f8a9](https://linux-hardware.org/?probe=6a2de1f8a9) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [65b87ee7d8](https://linux-hardware.org/?probe=65b87ee7d8) | Mar 29, 2021 |
| ASRock        | 970 Pro3 R2.0               | [58e2163a18](https://linux-hardware.org/?probe=58e2163a18) | Mar 29, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f0a7dd3475](https://linux-hardware.org/?probe=f0a7dd3475) | Mar 28, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f4da24790d](https://linux-hardware.org/?probe=f4da24790d) | Mar 27, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | [ea2ebcb877](https://linux-hardware.org/?probe=ea2ebcb877) | Mar 26, 2021 |
| ASRock        | Z68 Pro3                    | [8b7e56f2db](https://linux-hardware.org/?probe=8b7e56f2db) | Mar 25, 2021 |
| ASRock        | Z68 Pro3                    | [b0ddd79606](https://linux-hardware.org/?probe=b0ddd79606) | Mar 24, 2021 |
| ASUSTek       | M4N78-VM                    | [b3d61c6fbd](https://linux-hardware.org/?probe=b3d61c6fbd) | Mar 24, 2021 |
| MSI           | Z390-A PRO                  | [85f1a92a8a](https://linux-hardware.org/?probe=85f1a92a8a) | Mar 24, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [b89f0d11bd](https://linux-hardware.org/?probe=b89f0d11bd) | Mar 23, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [c17cb184a4](https://linux-hardware.org/?probe=c17cb184a4) | Mar 22, 2021 |
| ASUSTek       | M3A78-CM                    | [f9974d1e26](https://linux-hardware.org/?probe=f9974d1e26) | Mar 22, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [26b5c18aba](https://linux-hardware.org/?probe=26b5c18aba) | Mar 22, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a06e6983b1](https://linux-hardware.org/?probe=a06e6983b1) | Mar 21, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| ASRock        | B450M Pro4                  | [41c48a20a2](https://linux-hardware.org/?probe=41c48a20a2) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASRock        | B450M Pro4                  | [b075ade19c](https://linux-hardware.org/?probe=b075ade19c) | Mar 18, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | [003b473b29](https://linux-hardware.org/?probe=003b473b29) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| ASUSTek       | B85M-E                      | [46c2411987](https://linux-hardware.org/?probe=46c2411987) | Mar 17, 2021 |
| ASRock        | X370 Professional Gaming    | [677c76f624](https://linux-hardware.org/?probe=677c76f624) | Mar 17, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [fb88aba821](https://linux-hardware.org/?probe=fb88aba821) | Mar 17, 2021 |
| MSI           | B450I GAMING PLUS AC        | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| ASUSTek       | M3A78-CM                    | [9a912f6a54](https://linux-hardware.org/?probe=9a912f6a54) | Mar 15, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [88b4119893](https://linux-hardware.org/?probe=88b4119893) | Mar 14, 2021 |
| ASUSTek       | PRIME X570-P                | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [7764beb1a1](https://linux-hardware.org/?probe=7764beb1a1) | Mar 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bf856bd378](https://linux-hardware.org/?probe=bf856bd378) | Mar 11, 2021 |
| ASUSTek       | M3A78-CM                    | [ecaa4cd975](https://linux-hardware.org/?probe=ecaa4cd975) | Mar 08, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [fd82158f63](https://linux-hardware.org/?probe=fd82158f63) | Mar 07, 2021 |
| MSI           | X570-A PRO                  | [c19dde029b](https://linux-hardware.org/?probe=c19dde029b) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [0c34f3246f](https://linux-hardware.org/?probe=0c34f3246f) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [fb91319fa1](https://linux-hardware.org/?probe=fb91319fa1) | Mar 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [9f55c5ece0](https://linux-hardware.org/?probe=9f55c5ece0) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [927ea68f9f](https://linux-hardware.org/?probe=927ea68f9f) | Mar 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [413e1f3dd7](https://linux-hardware.org/?probe=413e1f3dd7) | Mar 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [44904f3de6](https://linux-hardware.org/?probe=44904f3de6) | Mar 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [6cd953f597](https://linux-hardware.org/?probe=6cd953f597) | Mar 02, 2021 |
| ASUSTek       | M3A78-CM                    | [e7bfe156f8](https://linux-hardware.org/?probe=e7bfe156f8) | Mar 01, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [38b0d3e407](https://linux-hardware.org/?probe=38b0d3e407) | Feb 28, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [d7a5611d8a](https://linux-hardware.org/?probe=d7a5611d8a) | Feb 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d854654bad](https://linux-hardware.org/?probe=d854654bad) | Feb 23, 2021 |
| MSI           | 970 GAMING                  | [062ccac9ff](https://linux-hardware.org/?probe=062ccac9ff) | Feb 22, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | [0e4ce5d923](https://linux-hardware.org/?probe=0e4ce5d923) | Feb 22, 2021 |
| ASUSTek       | M3A78-CM                    | [ae309000e1](https://linux-hardware.org/?probe=ae309000e1) | Feb 22, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [ede7d0e26c](https://linux-hardware.org/?probe=ede7d0e26c) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d67d9d3b74](https://linux-hardware.org/?probe=d67d9d3b74) | Feb 21, 2021 |
| ASRock        | X370 Gaming X               | [97b686fad6](https://linux-hardware.org/?probe=97b686fad6) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f9639ea950](https://linux-hardware.org/?probe=f9639ea950) | Feb 20, 2021 |
| ASUSTek       | P8H67-M PRO                 | [066c09783c](https://linux-hardware.org/?probe=066c09783c) | Feb 20, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [ac8250480a](https://linux-hardware.org/?probe=ac8250480a) | Feb 16, 2021 |
| MSI           | B450-A PRO                  | [211cb068ce](https://linux-hardware.org/?probe=211cb068ce) | Feb 16, 2021 |
| MSI           | MEG X570 UNIFY              | [8565fa7232](https://linux-hardware.org/?probe=8565fa7232) | Feb 15, 2021 |
| MSI           | B350M BAZOOKA               | [19cf6a4def](https://linux-hardware.org/?probe=19cf6a4def) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | [47dbd40dae](https://linux-hardware.org/?probe=47dbd40dae) | Feb 13, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | [925a360f1f](https://linux-hardware.org/?probe=925a360f1f) | Feb 12, 2021 |
| ASRock        | AM1H-ITX                    | [a1c5772342](https://linux-hardware.org/?probe=a1c5772342) | Feb 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0d787440f2](https://linux-hardware.org/?probe=0d787440f2) | Feb 01, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [ec933f8e8a](https://linux-hardware.org/?probe=ec933f8e8a) | Jan 31, 2021 |
| ASUSTek       | PRIME X570-P                | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Gigabyte      | MZBSWAP-00                  | [970493cf1b](https://linux-hardware.org/?probe=970493cf1b) | Jan 29, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6d86921fcf](https://linux-hardware.org/?probe=6d86921fcf) | Jan 26, 2021 |
| ASRock        | X370 Gaming X               | [8f0d93f4e1](https://linux-hardware.org/?probe=8f0d93f4e1) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [1b3702adc5](https://linux-hardware.org/?probe=1b3702adc5) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [8eb3edac54](https://linux-hardware.org/?probe=8eb3edac54) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [dc087e0399](https://linux-hardware.org/?probe=dc087e0399) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [de171f7a35](https://linux-hardware.org/?probe=de171f7a35) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [23602ad020](https://linux-hardware.org/?probe=23602ad020) | Jan 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8c1e988f7e](https://linux-hardware.org/?probe=8c1e988f7e) | Jan 18, 2021 |
| MSI           | MEG X570 GODLIKE            | [5964a40d34](https://linux-hardware.org/?probe=5964a40d34) | Jan 17, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| ASUSTek       | P8H67-M PRO                 | [1ff6f65135](https://linux-hardware.org/?probe=1ff6f65135) | Jan 15, 2021 |
| Gigabyte      | Z170X-Gaming 3              | [e4ab17605e](https://linux-hardware.org/?probe=e4ab17605e) | Jan 13, 2021 |
| ASRock        | J3455-ITX                   | [89257face1](https://linux-hardware.org/?probe=89257face1) | Jan 12, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [38332ee350](https://linux-hardware.org/?probe=38332ee350) | Jan 11, 2021 |
| HP            | 158B                        | [6bc73950dd](https://linux-hardware.org/?probe=6bc73950dd) | Jan 10, 2021 |
| ASRock        | B450 Pro4                   | [1b9975eef6](https://linux-hardware.org/?probe=1b9975eef6) | Jan 08, 2021 |
| ASRock        | X570 Steel Legend           | [48d53df339](https://linux-hardware.org/?probe=48d53df339) | Jan 08, 2021 |
| HP            | 1495                        | [ffb9d2f433](https://linux-hardware.org/?probe=ffb9d2f433) | Jan 08, 2021 |
| MSI           | 990FXA-GD80                 | [cc4b365068](https://linux-hardware.org/?probe=cc4b365068) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| ASRock        | AB350M Pro4                 | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6f95de2b32](https://linux-hardware.org/?probe=6f95de2b32) | Jan 05, 2021 |
| ASUSTek       | P5Q-E                       | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a011c9b38f](https://linux-hardware.org/?probe=a011c9b38f) | Jan 02, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [182deb31fb](https://linux-hardware.org/?probe=182deb31fb) | Jan 02, 2021 |
| ASRock        | Q1900-ITX                   | [78f7e1012f](https://linux-hardware.org/?probe=78f7e1012f) | Jan 02, 2021 |
| ASRock        | 970 Pro3 R2.0               | [b83ea4b5b3](https://linux-hardware.org/?probe=b83ea4b5b3) | Jan 02, 2021 |
| ASRock        | AM1H-ITX                    | [2bd69bdc3e](https://linux-hardware.org/?probe=2bd69bdc3e) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [87e72db668](https://linux-hardware.org/?probe=87e72db668) | Dec 23, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d00787942f](https://linux-hardware.org/?probe=d00787942f) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| Unknown       | Cubietech Cubieboard2       | [62e837d6a6](https://linux-hardware.org/?probe=62e837d6a6) | Dec 20, 2020 |
| ASRock        | X570 Taichi                 | [29d14ce28a](https://linux-hardware.org/?probe=29d14ce28a) | Dec 19, 2020 |
| MSI           | B350M BAZOOKA               | [4ceacadb9f](https://linux-hardware.org/?probe=4ceacadb9f) | Dec 17, 2020 |
| ASUSTek       | P8H67-M PRO                 | [2fc2502f80](https://linux-hardware.org/?probe=2fc2502f80) | Dec 15, 2020 |
| HP            | 3033h                       | [ff36d785e1](https://linux-hardware.org/?probe=ff36d785e1) | Dec 14, 2020 |
| ASRock        | X570 Phantom Gaming X       | [c1777903bd](https://linux-hardware.org/?probe=c1777903bd) | Dec 14, 2020 |
| ASRock        | H170M Pro4S                 | [debbcde352](https://linux-hardware.org/?probe=debbcde352) | Dec 11, 2020 |
| Acer          | Aspire TC-605               | [844d2c69e2](https://linux-hardware.org/?probe=844d2c69e2) | Dec 07, 2020 |
| MSI           | 970A SLI Krait Edition      | [1bec700189](https://linux-hardware.org/?probe=1bec700189) | Dec 07, 2020 |
| MSI           | 970A SLI Krait Edition      | [8d56de5850](https://linux-hardware.org/?probe=8d56de5850) | Dec 07, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3dc100c9a1](https://linux-hardware.org/?probe=3dc100c9a1) | Dec 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [50917002e1](https://linux-hardware.org/?probe=50917002e1) | Dec 01, 2020 |
| MSI           | B450M PRO-VDH MAX           | [03753743e7](https://linux-hardware.org/?probe=03753743e7) | Nov 30, 2020 |
| Gigabyte      | EP45T-DS3                   | [45142a6931](https://linux-hardware.org/?probe=45142a6931) | Nov 30, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7eeb446aee](https://linux-hardware.org/?probe=7eeb446aee) | Nov 30, 2020 |
| ASUSTek       | P9X79 WS                    | [24cfa19ea6](https://linux-hardware.org/?probe=24cfa19ea6) | Nov 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ba86d65e42](https://linux-hardware.org/?probe=ba86d65e42) | Nov 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78d68d35d8](https://linux-hardware.org/?probe=78d68d35d8) | Nov 26, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [35233c6000](https://linux-hardware.org/?probe=35233c6000) | Nov 26, 2020 |
| ASUSTek       | P8H67-M PRO                 | [4b811e60f6](https://linux-hardware.org/?probe=4b811e60f6) | Nov 26, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dcaf1f3521](https://linux-hardware.org/?probe=dcaf1f3521) | Nov 24, 2020 |
| ASUSTek       | P8Z77-V LX                  | [af91f8b0d0](https://linux-hardware.org/?probe=af91f8b0d0) | Nov 24, 2020 |
| MSI           | B350 GAMING PLUS            | [3e9e5d4c8d](https://linux-hardware.org/?probe=3e9e5d4c8d) | Nov 22, 2020 |
| MSI           | B350 GAMING PLUS            | [6692a5c759](https://linux-hardware.org/?probe=6692a5c759) | Nov 22, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [9b888a1a9c](https://linux-hardware.org/?probe=9b888a1a9c) | Nov 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [a6ab09a54b](https://linux-hardware.org/?probe=a6ab09a54b) | Nov 19, 2020 |
| ASRock        | X570 Pro4                   | [963200e763](https://linux-hardware.org/?probe=963200e763) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-PRO              | [04abcfd451](https://linux-hardware.org/?probe=04abcfd451) | Nov 18, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [7ac134ec7a](https://linux-hardware.org/?probe=7ac134ec7a) | Nov 18, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a4bdac2cea](https://linux-hardware.org/?probe=a4bdac2cea) | Nov 18, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [d46b466047](https://linux-hardware.org/?probe=d46b466047) | Nov 15, 2020 |
| ASRock        | B450 Pro4                   | [c920df4f73](https://linux-hardware.org/?probe=c920df4f73) | Nov 13, 2020 |
| MSI           | Z97-G43                     | [5f93bb3faa](https://linux-hardware.org/?probe=5f93bb3faa) | Nov 13, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [2c09ef9780](https://linux-hardware.org/?probe=2c09ef9780) | Nov 10, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [ca2bc0592f](https://linux-hardware.org/?probe=ca2bc0592f) | Nov 09, 2020 |
| MSI           | B450-A PRO                  | [00aeeab6da](https://linux-hardware.org/?probe=00aeeab6da) | Nov 08, 2020 |
| MSI           | B450-A PRO                  | [cd67b65826](https://linux-hardware.org/?probe=cd67b65826) | Nov 06, 2020 |
| ASUSTek       | P8H67-M PRO                 | [a870d5f1e6](https://linux-hardware.org/?probe=a870d5f1e6) | Nov 06, 2020 |
| ASUSTek       | A88XM-A                     | [45cf973d9c](https://linux-hardware.org/?probe=45cf973d9c) | Oct 31, 2020 |
| MSI           | Z170-A PRO                  | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| ASUSTek       | TUF GAMING B460-PLUS        | [539bba5a4d](https://linux-hardware.org/?probe=539bba5a4d) | Oct 26, 2020 |
| ASRock        | AM1H-ITX                    | [4a6634694e](https://linux-hardware.org/?probe=4a6634694e) | Oct 25, 2020 |
| ASRock        | X370 Gaming X               | [7b50c1e794](https://linux-hardware.org/?probe=7b50c1e794) | Oct 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e24f7d7cf7](https://linux-hardware.org/?probe=e24f7d7cf7) | Oct 24, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | EB1012G                     | [95a54c7d29](https://linux-hardware.org/?probe=95a54c7d29) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-PRO              | [3a4156ad86](https://linux-hardware.org/?probe=3a4156ad86) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [3264edefe8](https://linux-hardware.org/?probe=3264edefe8) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [49f9ade50f](https://linux-hardware.org/?probe=49f9ade50f) | Oct 17, 2020 |
| Gigabyte      | H110M-S2V-CF                | [2fe8128b94](https://linux-hardware.org/?probe=2fe8128b94) | Oct 15, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [0ff8e9dda5](https://linux-hardware.org/?probe=0ff8e9dda5) | Oct 15, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [5f53a7b654](https://linux-hardware.org/?probe=5f53a7b654) | Oct 15, 2020 |
| HP            | 8643 SMVB                   | [b1ebd820ea](https://linux-hardware.org/?probe=b1ebd820ea) | Oct 14, 2020 |
| ASRock        | N3150-ITX                   | [50872ff699](https://linux-hardware.org/?probe=50872ff699) | Oct 14, 2020 |
| MSI           | Z370 PC PRO                 | [6fdfdd701e](https://linux-hardware.org/?probe=6fdfdd701e) | Oct 14, 2020 |
| Dell          | 0PC5F7 A02                  | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| Entroware     | Nyx                         | [e349c62572](https://linux-hardware.org/?probe=e349c62572) | Oct 14, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [bb7e9817f3](https://linux-hardware.org/?probe=bb7e9817f3) | Oct 13, 2020 |
| ASUSTek       | H97M-PLUS                   | [979e26a9ff](https://linux-hardware.org/?probe=979e26a9ff) | Oct 13, 2020 |
| Gigabyte      | H110M-S2V-CF                | [e13bfd8911](https://linux-hardware.org/?probe=e13bfd8911) | Oct 13, 2020 |
| ASRock        | X570M Pro4                  | [11624f2e68](https://linux-hardware.org/?probe=11624f2e68) | Oct 12, 2020 |
| ASRock        | X370 Professional Gaming    | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| ASUSTek       | P6X58D PREMIUM              | [9b3c10083c](https://linux-hardware.org/?probe=9b3c10083c) | Oct 11, 2020 |
| MSI           | MEG X570 UNIFY              | [bc040e4fa3](https://linux-hardware.org/?probe=bc040e4fa3) | Oct 08, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4c9fc71c64](https://linux-hardware.org/?probe=4c9fc71c64) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f3201a0e2c](https://linux-hardware.org/?probe=f3201a0e2c) | Oct 06, 2020 |
| MSI           | H310M PRO-VD PLUS           | [90021d6e51](https://linux-hardware.org/?probe=90021d6e51) | Oct 05, 2020 |
| ASUSTek       | H61M-K                      | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| MSI           | X370 XPOWER GAMING TITAN... | [f09de8f7dc](https://linux-hardware.org/?probe=f09de8f7dc) | Oct 01, 2020 |
| MSI           | X99A SLI PLUS               | [c77d27bdcd](https://linux-hardware.org/?probe=c77d27bdcd) | Sep 29, 2020 |
| Unknown       | Intel X79                   | [3849825892](https://linux-hardware.org/?probe=3849825892) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [b048626385](https://linux-hardware.org/?probe=b048626385) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e26cc6bcb0](https://linux-hardware.org/?probe=e26cc6bcb0) | Sep 29, 2020 |
| ASUSTek       | PRIME X370-PRO              | [ebbc140da9](https://linux-hardware.org/?probe=ebbc140da9) | Sep 28, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6cbcba7414](https://linux-hardware.org/?probe=6cbcba7414) | Sep 28, 2020 |
| ASUSTek       | P9X79                       | [662a97173c](https://linux-hardware.org/?probe=662a97173c) | Sep 28, 2020 |
| MSI           | 970A-G43                    | [f71dd78128](https://linux-hardware.org/?probe=f71dd78128) | Sep 27, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [c8d28c60cd](https://linux-hardware.org/?probe=c8d28c60cd) | Sep 27, 2020 |
| ASRock        | Z170 OC Formula             | [b478607fef](https://linux-hardware.org/?probe=b478607fef) | Sep 26, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [0997ff40b0](https://linux-hardware.org/?probe=0997ff40b0) | Sep 26, 2020 |
| MSI           | X99A SLI PLUS               | [d0cf13bbc8](https://linux-hardware.org/?probe=d0cf13bbc8) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [00290a5d85](https://linux-hardware.org/?probe=00290a5d85) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [449d8022e1](https://linux-hardware.org/?probe=449d8022e1) | Sep 26, 2020 |
| MSI           | X58 Pro-E                   | [1ecbc5ccba](https://linux-hardware.org/?probe=1ecbc5ccba) | Sep 25, 2020 |
| MSI           | X58 Pro-E                   | [28ac8fd1b7](https://linux-hardware.org/?probe=28ac8fd1b7) | Sep 24, 2020 |
| ASUSTek       | H81M-PLUS                   | [87f345b258](https://linux-hardware.org/?probe=87f345b258) | Sep 24, 2020 |
| Supermicro    | A1SRM-2758F                 | [dae3697ff8](https://linux-hardware.org/?probe=dae3697ff8) | Sep 23, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [644c742328](https://linux-hardware.org/?probe=644c742328) | Sep 23, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [aac147ef3c](https://linux-hardware.org/?probe=aac147ef3c) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| ASUSTek       | Z97-A                       | [5104e708b9](https://linux-hardware.org/?probe=5104e708b9) | Sep 20, 2020 |
| ASUSTek       | Z97-A                       | [6505c46aec](https://linux-hardware.org/?probe=6505c46aec) | Sep 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f2bdd44684](https://linux-hardware.org/?probe=f2bdd44684) | Sep 18, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [15e4e278e8](https://linux-hardware.org/?probe=15e4e278e8) | Sep 18, 2020 |
| ASUSTek       | P5K-V                       | [04e5e2e796](https://linux-hardware.org/?probe=04e5e2e796) | Sep 17, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [cc1af2a4aa](https://linux-hardware.org/?probe=cc1af2a4aa) | Sep 16, 2020 |
| ASRock        | 970A-G                      | [c76564a1e5](https://linux-hardware.org/?probe=c76564a1e5) | Sep 16, 2020 |
| Unknown       | Unknown                     | [23a8f5bbfb](https://linux-hardware.org/?probe=23a8f5bbfb) | Sep 14, 2020 |
| Unknown       | Unknown                     | [47de429737](https://linux-hardware.org/?probe=47de429737) | Sep 07, 2020 |
| MSI           | Z170A GAMING PRO            | [a23e1ab6f7](https://linux-hardware.org/?probe=a23e1ab6f7) | Sep 06, 2020 |
| MSI           | Z170A GAMING PRO            | [e12a573590](https://linux-hardware.org/?probe=e12a573590) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a1cc53584d](https://linux-hardware.org/?probe=a1cc53584d) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d3510ce4e2](https://linux-hardware.org/?probe=d3510ce4e2) | Sep 04, 2020 |
| ASRock        | B450M-HDV R4.0              | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4a62067798](https://linux-hardware.org/?probe=4a62067798) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD5H                   | [ced4076cfe](https://linux-hardware.org/?probe=ced4076cfe) | Sep 03, 2020 |
| MSI           | B450M MORTAR MAX            | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [3aacd1b61b](https://linux-hardware.org/?probe=3aacd1b61b) | Sep 03, 2020 |
| MSI           | Z97-G45 GAMING              | [e86bf6dfb8](https://linux-hardware.org/?probe=e86bf6dfb8) | Sep 03, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4bf504d82b](https://linux-hardware.org/?probe=4bf504d82b) | Sep 03, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | [2c3ca5276b](https://linux-hardware.org/?probe=2c3ca5276b) | Sep 03, 2020 |
| MSI           | X470 GAMING PLUS            | [84aef475d9](https://linux-hardware.org/?probe=84aef475d9) | Sep 02, 2020 |
| ASUSTek       | Rampage V EXTREME           | [2669865bf9](https://linux-hardware.org/?probe=2669865bf9) | Aug 31, 2020 |
| ASUSTek       | M5A97                       | [8388fbe3b4](https://linux-hardware.org/?probe=8388fbe3b4) | Aug 31, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [804af7bd77](https://linux-hardware.org/?probe=804af7bd77) | Aug 29, 2020 |
| MSI           | Z77IA-E53                   | [bf99082e95](https://linux-hardware.org/?probe=bf99082e95) | Aug 28, 2020 |
| ASUSTek       | Z170-A                      | [af1f86e610](https://linux-hardware.org/?probe=af1f86e610) | Aug 25, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d17e5bf1f8](https://linux-hardware.org/?probe=d17e5bf1f8) | Aug 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | [a0e30e712f](https://linux-hardware.org/?probe=a0e30e712f) | Aug 23, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [7152566435](https://linux-hardware.org/?probe=7152566435) | Aug 23, 2020 |
| ASUSTek       | Rampage V EXTREME           | [96d6f0ea21](https://linux-hardware.org/?probe=96d6f0ea21) | Aug 23, 2020 |
| Supermicro    | A1SRM-2758F                 | [b91457fee4](https://linux-hardware.org/?probe=b91457fee4) | Aug 22, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [1575c94669](https://linux-hardware.org/?probe=1575c94669) | Aug 20, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| Unknown       | Unknown                     | [41ab260322](https://linux-hardware.org/?probe=41ab260322) | Aug 20, 2020 |
| Unknown       | Unknown                     | [6a7fc0088c](https://linux-hardware.org/?probe=6a7fc0088c) | Aug 19, 2020 |
| MSI           | B350 GAMING PRO CARBON      | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| ASUSTek       | Z97-DELUXE                  | [766495711b](https://linux-hardware.org/?probe=766495711b) | Aug 17, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [32ae11e70f](https://linux-hardware.org/?probe=32ae11e70f) | Aug 15, 2020 |
| Unknown       | Unknown                     | [3d3ed1b8ce](https://linux-hardware.org/?probe=3d3ed1b8ce) | Aug 15, 2020 |
| Unknown       | Unknown                     | [55f1b3cdce](https://linux-hardware.org/?probe=55f1b3cdce) | Aug 15, 2020 |
| ASUSTek       | PRIME X370-PRO              | [7d01f814d5](https://linux-hardware.org/?probe=7d01f814d5) | Aug 10, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d6a59a4350](https://linux-hardware.org/?probe=d6a59a4350) | Aug 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| ASUSTek       | P6X58D-E                    | [3db01937e1](https://linux-hardware.org/?probe=3db01937e1) | Aug 05, 2020 |
| Unknown       | Unknown                     | [978fcb3a51](https://linux-hardware.org/?probe=978fcb3a51) | Jul 31, 2020 |
| ASRock        | B85M-HDS                    | [7e7ad89d55](https://linux-hardware.org/?probe=7e7ad89d55) | Jul 29, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [3729332530](https://linux-hardware.org/?probe=3729332530) | Jul 29, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [9f29db1cee](https://linux-hardware.org/?probe=9f29db1cee) | Jul 28, 2020 |
| ASUSTek       | Rampage V EXTREME           | [554fbd9b8d](https://linux-hardware.org/?probe=554fbd9b8d) | Jul 28, 2020 |
| ASRock        | X570M Pro4                  | [9d082a4d26](https://linux-hardware.org/?probe=9d082a4d26) | Jul 24, 2020 |
| ASRock        | X370 Taichi                 | [e08f62cb80](https://linux-hardware.org/?probe=e08f62cb80) | Jul 23, 2020 |
| Unknown       | Unknown                     | [3ab679a1a1](https://linux-hardware.org/?probe=3ab679a1a1) | Jul 22, 2020 |
| ASUSTek       | X99-M WS                    | [7a813c93b0](https://linux-hardware.org/?probe=7a813c93b0) | Jul 15, 2020 |
| Unknown       | Unknown                     | [d83097e656](https://linux-hardware.org/?probe=d83097e656) | Jul 13, 2020 |
| ASRock        | Z170 Pro4S                  | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASUSTek       | GRYPHON Z97                 | [e7b3ad7e11](https://linux-hardware.org/?probe=e7b3ad7e11) | Jul 07, 2020 |
| ASRock        | Z170 Pro4S                  | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| ASUSTek       | PRIME X570-PRO              | [ce72513578](https://linux-hardware.org/?probe=ce72513578) | Jul 06, 2020 |
| ASUSTek       | M5A97 R2.0                  | [9e43a872bf](https://linux-hardware.org/?probe=9e43a872bf) | Jul 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | [cca87001ef](https://linux-hardware.org/?probe=cca87001ef) | Jul 03, 2020 |
| ASUSTek       | PRIME X570-PRO              | [dd3e957888](https://linux-hardware.org/?probe=dd3e957888) | Jul 03, 2020 |
| MSI           | B450M MORTAR MAX            | [856df3e013](https://linux-hardware.org/?probe=856df3e013) | Jul 01, 2020 |
| ASUSTek       | PRIME X570-P                | [d7dfd2a0d2](https://linux-hardware.org/?probe=d7dfd2a0d2) | Jun 30, 2020 |
| ASUSTek       | PRIME X570-P                | [4a255afdf8](https://linux-hardware.org/?probe=4a255afdf8) | Jun 30, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [f54a86a6b4](https://linux-hardware.org/?probe=f54a86a6b4) | Jun 30, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [c9529f922d](https://linux-hardware.org/?probe=c9529f922d) | Jun 29, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [911703286c](https://linux-hardware.org/?probe=911703286c) | Jun 29, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [9ff481d661](https://linux-hardware.org/?probe=9ff481d661) | Jun 29, 2020 |
| ASRockRack    | C226M WS                    | [adb729fe45](https://linux-hardware.org/?probe=adb729fe45) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [12ca04e727](https://linux-hardware.org/?probe=12ca04e727) | Jun 27, 2020 |
| ASUSTek       | M3A78-CM                    | [32ad3b2344](https://linux-hardware.org/?probe=32ad3b2344) | Jun 27, 2020 |
| Dell          | 0NK70N A03                  | [19fb02ca4e](https://linux-hardware.org/?probe=19fb02ca4e) | Jun 25, 2020 |
| ASUSTek       | PRIME X370-A                | [a2df61648b](https://linux-hardware.org/?probe=a2df61648b) | Jun 24, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASUSTek       | PRIME X570-P                | [392a2f214f](https://linux-hardware.org/?probe=392a2f214f) | Jun 20, 2020 |
| ASRock        | X370 Killer SLI             | [e68e55ff91](https://linux-hardware.org/?probe=e68e55ff91) | Jun 20, 2020 |
| Gigabyte      | H310M S2H x.x               | [7ec1b97719](https://linux-hardware.org/?probe=7ec1b97719) | Jun 20, 2020 |
| Gigabyte      | H310M S2H x.x               | [26018540a4](https://linux-hardware.org/?probe=26018540a4) | Jun 18, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a91b7a6ef3](https://linux-hardware.org/?probe=a91b7a6ef3) | Jun 16, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [78a788e5aa](https://linux-hardware.org/?probe=78a788e5aa) | Jun 14, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [d1c9757c3c](https://linux-hardware.org/?probe=d1c9757c3c) | Jun 11, 2020 |
| MSI           | Z97-G43                     | [1134683267](https://linux-hardware.org/?probe=1134683267) | Jun 11, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8ca08405df](https://linux-hardware.org/?probe=8ca08405df) | Jun 11, 2020 |
| MSI           | X570-A PRO                  | [d330af6317](https://linux-hardware.org/?probe=d330af6317) | Jun 09, 2020 |
| ASUSTek       | Z170-A                      | [81dbec3df4](https://linux-hardware.org/?probe=81dbec3df4) | Jun 09, 2020 |
| ASRock        | B450 Pro4                   | [d57c4c6597](https://linux-hardware.org/?probe=d57c4c6597) | Jun 09, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [40b9dbe4a5](https://linux-hardware.org/?probe=40b9dbe4a5) | Jun 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [50cf5c19df](https://linux-hardware.org/?probe=50cf5c19df) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | UN65U                       | [12d0edec81](https://linux-hardware.org/?probe=12d0edec81) | Jun 07, 2020 |
| ASUSTek       | WS X299 SAGE                | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| ASUSTek       | P8H67-M PRO                 | [07ef877c6b](https://linux-hardware.org/?probe=07ef877c6b) | Jun 05, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [9c7b7cde1e](https://linux-hardware.org/?probe=9c7b7cde1e) | Jun 04, 2020 |
| ASRock        | B150M Pro4                  | [d704cdc9e0](https://linux-hardware.org/?probe=d704cdc9e0) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [e64653b77c](https://linux-hardware.org/?probe=e64653b77c) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [ff470637f1](https://linux-hardware.org/?probe=ff470637f1) | Jun 04, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [cb3e54a9ea](https://linux-hardware.org/?probe=cb3e54a9ea) | Jun 04, 2020 |
| ASUSTek       | PRIME B450M-A               | [38d7220c47](https://linux-hardware.org/?probe=38d7220c47) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [2d804a0477](https://linux-hardware.org/?probe=2d804a0477) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [b379b98120](https://linux-hardware.org/?probe=b379b98120) | Jun 04, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7ec054401d](https://linux-hardware.org/?probe=7ec054401d) | Jun 04, 2020 |
| Gigabyte      | X570 AORUS XTREME           | [cf5cf7d297](https://linux-hardware.org/?probe=cf5cf7d297) | Jun 04, 2020 |
| ASUSTek       | P6X58D-E                    | [219e253757](https://linux-hardware.org/?probe=219e253757) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | [725e4103b2](https://linux-hardware.org/?probe=725e4103b2) | Jun 04, 2020 |
| Gigabyte      | B450 AORUS M                | [8311b78871](https://linux-hardware.org/?probe=8311b78871) | Jun 04, 2020 |
| MSI           | X470 GAMING PLUS            | [713a47cd93](https://linux-hardware.org/?probe=713a47cd93) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | [66b855cb1f](https://linux-hardware.org/?probe=66b855cb1f) | Jun 04, 2020 |
| ASUSTek       | P8H67-M PRO                 | [3eeead93cd](https://linux-hardware.org/?probe=3eeead93cd) | Jun 03, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [19202ed9bc](https://linux-hardware.org/?probe=19202ed9bc) | Jun 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [781f2cda04](https://linux-hardware.org/?probe=781f2cda04) | Jun 03, 2020 |
| HP            | 3396                        | [59e4e46994](https://linux-hardware.org/?probe=59e4e46994) | Jun 03, 2020 |
| Acer          | Aspire X1800                | [f558e48348](https://linux-hardware.org/?probe=f558e48348) | Jun 03, 2020 |
| Intel         | DQ77MK AAG39642-302         | [dee8f8adaa](https://linux-hardware.org/?probe=dee8f8adaa) | Jun 03, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [03524be236](https://linux-hardware.org/?probe=03524be236) | Jun 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ed28ebb0ff](https://linux-hardware.org/?probe=ed28ebb0ff) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4f2cd8d224](https://linux-hardware.org/?probe=4f2cd8d224) | Jun 03, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [452ae63632](https://linux-hardware.org/?probe=452ae63632) | Jun 03, 2020 |
| Intel         | DH77KC AAG39641-400         | [c70d57d5e5](https://linux-hardware.org/?probe=c70d57d5e5) | Jun 03, 2020 |
| ASRock        | X570 Creator                | [ae5e24adcc](https://linux-hardware.org/?probe=ae5e24adcc) | Jun 03, 2020 |
| ASRock        | X399 Taichi                 | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [656aaf0582](https://linux-hardware.org/?probe=656aaf0582) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4b6b3bf141](https://linux-hardware.org/?probe=4b6b3bf141) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [e69d1396bf](https://linux-hardware.org/?probe=e69d1396bf) | Jun 03, 2020 |
| MSI           | X570-A PRO                  | [aeb2569425](https://linux-hardware.org/?probe=aeb2569425) | Jun 03, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [d3ffbfc9c0](https://linux-hardware.org/?probe=d3ffbfc9c0) | Jun 02, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [0c26712766](https://linux-hardware.org/?probe=0c26712766) | Jun 02, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [05f1955ea4](https://linux-hardware.org/?probe=05f1955ea4) | Jun 02, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [5e8c7a8c37](https://linux-hardware.org/?probe=5e8c7a8c37) | Jun 01, 2020 |
| ASRock        | X570 Steel Legend           | [379b9c17e4](https://linux-hardware.org/?probe=379b9c17e4) | May 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | [740ab53ee9](https://linux-hardware.org/?probe=740ab53ee9) | May 30, 2020 |
| Unknown       | Unknown                     | [dc54725d68](https://linux-hardware.org/?probe=dc54725d68) | May 29, 2020 |
| ASUSTek       | Rampage V EXTREME           | [27319b39dc](https://linux-hardware.org/?probe=27319b39dc) | May 29, 2020 |
| ASUSTek       | M5A97                       | [9fe1c71ec5](https://linux-hardware.org/?probe=9fe1c71ec5) | May 29, 2020 |
| ASUSTek       | M5A97                       | [692812f42b](https://linux-hardware.org/?probe=692812f42b) | May 28, 2020 |
| ASUSTek       | M5A97                       | [28e068ce98](https://linux-hardware.org/?probe=28e068ce98) | May 28, 2020 |
| ASUSTek       | Rampage V EXTREME           | [e6b00ae98c](https://linux-hardware.org/?probe=e6b00ae98c) | May 28, 2020 |
| ASUSTek       | Rampage V EXTREME           | [89abf0db25](https://linux-hardware.org/?probe=89abf0db25) | May 28, 2020 |
| ASUSTek       | M5A97                       | [012357c526](https://linux-hardware.org/?probe=012357c526) | May 28, 2020 |
| MSI           | X370 KRAIT GAMING           | [533865a273](https://linux-hardware.org/?probe=533865a273) | May 27, 2020 |
| Acer          | WMCP78M                     | [9e32f34f8e](https://linux-hardware.org/?probe=9e32f34f8e) | May 25, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [58f57667ee](https://linux-hardware.org/?probe=58f57667ee) | May 25, 2020 |
| ASRock        | B450M-HDV R4.0              | [e0cde3f93b](https://linux-hardware.org/?probe=e0cde3f93b) | May 25, 2020 |
| Gigabyte      | GA-E350N-USB3               | [5c759bd365](https://linux-hardware.org/?probe=5c759bd365) | May 23, 2020 |
| ASUSTek       | P6TD DELUXE                 | [2a97c35b6b](https://linux-hardware.org/?probe=2a97c35b6b) | May 23, 2020 |
| Sun Micros... | Ultra 24 50                 | [2541d35bd4](https://linux-hardware.org/?probe=2541d35bd4) | May 23, 2020 |
| Gigabyte      | H370M D3H-CF                | [1f405a7557](https://linux-hardware.org/?probe=1f405a7557) | May 23, 2020 |
| HP            | 3648h                       | [14b2a01c1d](https://linux-hardware.org/?probe=14b2a01c1d) | May 23, 2020 |
| ASRockRack    | X470D4U                     | [09640a1376](https://linux-hardware.org/?probe=09640a1376) | May 23, 2020 |
| HP            | 0B54h D                     | [4ef026497f](https://linux-hardware.org/?probe=4ef026497f) | May 23, 2020 |
| Unknown       | Freecom Silverstore HNCN... | [7444781d69](https://linux-hardware.org/?probe=7444781d69) | May 22, 2020 |
| ASRock        | Z77 Extreme3                | [46d7fb23b0](https://linux-hardware.org/?probe=46d7fb23b0) | May 21, 2020 |
| Unknown       | Freecom Silverstore HNCN... | [149328faf5](https://linux-hardware.org/?probe=149328faf5) | May 21, 2020 |
| Foxconn       | nT-330i                     | [197956f2b4](https://linux-hardware.org/?probe=197956f2b4) | May 20, 2020 |
| ASUSTek       | M2N-CM DVI                  | [e2c38feac9](https://linux-hardware.org/?probe=e2c38feac9) | May 19, 2020 |
| Gigabyte      | B75M-D3H                    | [0e40b91fa8](https://linux-hardware.org/?probe=0e40b91fa8) | May 17, 2020 |
| MSI           | Z170A GAMING M3             | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [ee3c36bba5](https://linux-hardware.org/?probe=ee3c36bba5) | May 13, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [774f11394f](https://linux-hardware.org/?probe=774f11394f) | May 13, 2020 |
| Gigabyte      | M61SME-S2                   | [bd4b1dc757](https://linux-hardware.org/?probe=bd4b1dc757) | May 12, 2020 |
| Gigabyte      | A320M-S2H-CF                | [7d37b8ad19](https://linux-hardware.org/?probe=7d37b8ad19) | May 12, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [4e05b9111b](https://linux-hardware.org/?probe=4e05b9111b) | May 12, 2020 |
| Pegatron      | NARRA5                      | [52991f9a5a](https://linux-hardware.org/?probe=52991f9a5a) | May 11, 2020 |
| Acer          | WMCP78M                     | [2b3ef19bab](https://linux-hardware.org/?probe=2b3ef19bab) | May 11, 2020 |
| ASUSTek       | Z97M-PLUS                   | [1523e8f4a8](https://linux-hardware.org/?probe=1523e8f4a8) | May 11, 2020 |
| HP            | 83C1                        | [8b7d6722b2](https://linux-hardware.org/?probe=8b7d6722b2) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | [42ec09f78b](https://linux-hardware.org/?probe=42ec09f78b) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | [6874d82c83](https://linux-hardware.org/?probe=6874d82c83) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [86a0177aac](https://linux-hardware.org/?probe=86a0177aac) | May 11, 2020 |
| Gigabyte      | B450M S2H                   | [d7cb6417b5](https://linux-hardware.org/?probe=d7cb6417b5) | May 11, 2020 |
| Dell          | 0X8DXD A00                  | [79c618a36d](https://linux-hardware.org/?probe=79c618a36d) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [8bca8a21eb](https://linux-hardware.org/?probe=8bca8a21eb) | May 11, 2020 |
| Dell          | 09PR9H A02                  | [a0f6d2eac4](https://linux-hardware.org/?probe=a0f6d2eac4) | May 11, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [0cf396063f](https://linux-hardware.org/?probe=0cf396063f) | May 11, 2020 |
| ASRock        | X470 Taichi                 | [8ca172b725](https://linux-hardware.org/?probe=8ca172b725) | May 11, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [adac2225d4](https://linux-hardware.org/?probe=adac2225d4) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [b3a2b9b3f7](https://linux-hardware.org/?probe=b3a2b9b3f7) | May 11, 2020 |
| ASUSTek       | P8B75-V                     | [05258aea35](https://linux-hardware.org/?probe=05258aea35) | May 11, 2020 |
| Gigabyte      | Z97P-D3                     | [9ee0d24e00](https://linux-hardware.org/?probe=9ee0d24e00) | May 10, 2020 |
| ASUSTek       | PRIME X470-PRO              | [0a33d02a42](https://linux-hardware.org/?probe=0a33d02a42) | May 10, 2020 |
| Unknown       | Unknown                     | [35a29512ac](https://linux-hardware.org/?probe=35a29512ac) | May 06, 2020 |
| ASRock        | M3A785GXH/128M              | [2c2e4ffd37](https://linux-hardware.org/?probe=2c2e4ffd37) | May 01, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9fce6c2df1](https://linux-hardware.org/?probe=9fce6c2df1) | Apr 25, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [963d9a7731](https://linux-hardware.org/?probe=963d9a7731) | Apr 22, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [8625c51506](https://linux-hardware.org/?probe=8625c51506) | Apr 19, 2020 |
| MSI           | Z270 GAMING M5              | [1b4bf985a0](https://linux-hardware.org/?probe=1b4bf985a0) | Apr 18, 2020 |
| ASRock        | H170M-ITX/DL                | [1ad0702a1c](https://linux-hardware.org/?probe=1ad0702a1c) | Apr 13, 2020 |
| ASRock        | H170M-ITX/DL                | [9e7024131d](https://linux-hardware.org/?probe=9e7024131d) | Apr 13, 2020 |
| ASRock        | H170M-ITX/DL                | [19d2c5bdbe](https://linux-hardware.org/?probe=19d2c5bdbe) | Apr 13, 2020 |
| ASRock        | K10N780SLIX3-WiFi           | [93da818757](https://linux-hardware.org/?probe=93da818757) | Apr 11, 2020 |
| ASUSTek       | Rampage V EDITION 10        | [25c59807fb](https://linux-hardware.org/?probe=25c59807fb) | Apr 09, 2020 |
| ASUSTek       | Rampage V EDITION 10        | [175385911b](https://linux-hardware.org/?probe=175385911b) | Apr 09, 2020 |
| MSI           | X99A SLI PLUS               | [32d5183912](https://linux-hardware.org/?probe=32d5183912) | Apr 06, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [baaff2d847](https://linux-hardware.org/?probe=baaff2d847) | Mar 30, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [22662aad4d](https://linux-hardware.org/?probe=22662aad4d) | Mar 26, 2020 |
| ASUSTek       | PRIME X570-PRO              | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| ASUSTek       | P5LD2-VM                    | [6dccd8d0e9](https://linux-hardware.org/?probe=6dccd8d0e9) | Mar 20, 2020 |
| ASUSTek       | M3A78-CM                    | [1e9b01c58c](https://linux-hardware.org/?probe=1e9b01c58c) | Mar 20, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [4514d59538](https://linux-hardware.org/?probe=4514d59538) | Mar 19, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [26c5187786](https://linux-hardware.org/?probe=26c5187786) | Mar 19, 2020 |
| ASUSTek       | B85M-G                      | [bfb2fb34f1](https://linux-hardware.org/?probe=bfb2fb34f1) | Mar 16, 2020 |
| ASUSTek       | PRIME X570-PRO              | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| ASUSTek       | PRIME X570-PRO              | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASRock        | Z170 OC Formula             | [189475c3f5](https://linux-hardware.org/?probe=189475c3f5) | Mar 04, 2020 |
| ASRock        | Z170 OC Formula             | [a405f01061](https://linux-hardware.org/?probe=a405f01061) | Mar 04, 2020 |
| Acer          | Aspire XC-885 V:1.1         | [ed91ab3535](https://linux-hardware.org/?probe=ed91ab3535) | Feb 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b417c8e979](https://linux-hardware.org/?probe=b417c8e979) | Feb 24, 2020 |
| ASUSTek       | PRIME Z370-A                | [7508b3bb88](https://linux-hardware.org/?probe=7508b3bb88) | Feb 22, 2020 |
| Gigabyte      | GA-990FXA-UD5               | [24bf705591](https://linux-hardware.org/?probe=24bf705591) | Feb 14, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3b1978d721](https://linux-hardware.org/?probe=3b1978d721) | Feb 11, 2020 |
| ASUSTek       | P8Z77-M PRO                 | [44e0ce8fc8](https://linux-hardware.org/?probe=44e0ce8fc8) | Jan 24, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [169fe41d8b](https://linux-hardware.org/?probe=169fe41d8b) | Jan 20, 2020 |
| ASUSTek       | Rampage V EXTREME           | [d13687928d](https://linux-hardware.org/?probe=d13687928d) | Jan 17, 2020 |
| Medion        | B360H4-EM V1.0              | [42bebcc127](https://linux-hardware.org/?probe=42bebcc127) | Jan 11, 2020 |
| Medion        | B360H4-EM V1.0              | [c9d4bfd2a6](https://linux-hardware.org/?probe=c9d4bfd2a6) | Jan 11, 2020 |
| MSI           | X58 Pro-E                   | [1be116c58b](https://linux-hardware.org/?probe=1be116c58b) | Jan 11, 2020 |
| MSI           | X58 Pro-E                   | [eb84478f51](https://linux-hardware.org/?probe=eb84478f51) | Jan 10, 2020 |
| MSI           | X58 Pro-E                   | [a893a616e4](https://linux-hardware.org/?probe=a893a616e4) | Jan 10, 2020 |
| ASRock        | X399 Taichi                 | [5ab003017d](https://linux-hardware.org/?probe=5ab003017d) | Jan 09, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [c609a0f7b0](https://linux-hardware.org/?probe=c609a0f7b0) | Jan 05, 2020 |
| ASRock        | B450 Pro4                   | [a09cfe8fa7](https://linux-hardware.org/?probe=a09cfe8fa7) | Dec 30, 2019 |
| Gigabyte      | GA-990FXA-UD3               | [746ed0f095](https://linux-hardware.org/?probe=746ed0f095) | Dec 29, 2019 |
| Dell          | 0F3KHR A00                  | [779b6b3344](https://linux-hardware.org/?probe=779b6b3344) | Dec 26, 2019 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [878bf77ba1](https://linux-hardware.org/?probe=878bf77ba1) | Dec 05, 2019 |
| ASUSTek       | H110M-R                     | [0b7127611f](https://linux-hardware.org/?probe=0b7127611f) | Dec 04, 2019 |
| ASUSTek       | X99-PRO/USB                 | [a16a7137a3](https://linux-hardware.org/?probe=a16a7137a3) | Dec 03, 2019 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [41a70f4103](https://linux-hardware.org/?probe=41a70f4103) | Dec 02, 2019 |
| MSI           | MPG Z390 GAMING PLUS        | [b903ad14bd](https://linux-hardware.org/?probe=b903ad14bd) | Nov 21, 2019 |
| Gigabyte      | GA-970-Gaming SLI-CF        | [5d68412263](https://linux-hardware.org/?probe=5d68412263) | Oct 01, 2019 |
| Gigabyte      | X399 AORUS Gaming 7         | [174ef29175](https://linux-hardware.org/?probe=174ef29175) | Aug 24, 2019 |
| ASUSTek       | PRIME X570-PRO              | [952e8b5ade](https://linux-hardware.org/?probe=952e8b5ade) | Aug 20, 2019 |
| ASUSTek       | P5LD2-VM                    | [3b64dc358e](https://linux-hardware.org/?probe=3b64dc358e) | Aug 15, 2019 |
| ASUSTek       | P5LD2-VM                    | [96c64ae190](https://linux-hardware.org/?probe=96c64ae190) | Aug 15, 2019 |
| ASUSTek       | P5LD2-VM                    | [6c5841c605](https://linux-hardware.org/?probe=6c5841c605) | Aug 15, 2019 |
| ASUSTek       | P5LD2-VM                    | [e9e46f952b](https://linux-hardware.org/?probe=e9e46f952b) | Aug 15, 2019 |
| ASRock        | J4205-ITX                   | [633a8b8adf](https://linux-hardware.org/?probe=633a8b8adf) | Aug 14, 2019 |
| ASUSTek       | P8H61-M LX2 R2.0 R2.0       | [bed9b97265](https://linux-hardware.org/?probe=bed9b97265) | Aug 01, 2019 |
| ASUSTek       | Z170-A                      | [89f4bb64d7](https://linux-hardware.org/?probe=89f4bb64d7) | Jul 27, 2019 |
| ASUSTek       | Z170-A                      | [3fb755ed84](https://linux-hardware.org/?probe=3fb755ed84) | Jul 27, 2019 |
| Gigabyte      | B75M-D3H                    | [7d2057c89d](https://linux-hardware.org/?probe=7d2057c89d) | Jul 22, 2019 |
| ASUSTek       | Z170-A                      | [ba19900be7](https://linux-hardware.org/?probe=ba19900be7) | Jun 28, 2019 |
| HP            | ProLiant MicroServer Gen... | [fb66d16e30](https://linux-hardware.org/?probe=fb66d16e30) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [ba24031371](https://linux-hardware.org/?probe=ba24031371) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [ed6c08d9c8](https://linux-hardware.org/?probe=ed6c08d9c8) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [7714f555ff](https://linux-hardware.org/?probe=7714f555ff) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [4c5c3eca10](https://linux-hardware.org/?probe=4c5c3eca10) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [e6d552aaf9](https://linux-hardware.org/?probe=e6d552aaf9) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [3d07046aa1](https://linux-hardware.org/?probe=3d07046aa1) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [3ef2c765db](https://linux-hardware.org/?probe=3ef2c765db) | Jun 17, 2019 |
| HP            | ProLiant MicroServer Gen... | [f4321ffaa5](https://linux-hardware.org/?probe=f4321ffaa5) | Jun 16, 2019 |
| HP            | ProLiant MicroServer Gen... | [0e62159093](https://linux-hardware.org/?probe=0e62159093) | Jun 16, 2019 |
| HP            | ProLiant MicroServer Gen... | [571441e6d4](https://linux-hardware.org/?probe=571441e6d4) | Jun 16, 2019 |
| HP            | ProLiant MicroServer Gen... | [7cf6d970ec](https://linux-hardware.org/?probe=7cf6d970ec) | Jun 16, 2019 |
| HP            | ProLiant MicroServer Gen... | [ce73c1eda5](https://linux-hardware.org/?probe=ce73c1eda5) | Jun 16, 2019 |
| HP            | ProLiant MicroServer Gen... | [d07dd9e54c](https://linux-hardware.org/?probe=d07dd9e54c) | Jun 16, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [0d21f94b25](https://linux-hardware.org/?probe=0d21f94b25) | Jun 15, 2019 |
| Gigabyte      | 970A-UD3P                   | [0533339e4e](https://linux-hardware.org/?probe=0533339e4e) | Jun 05, 2019 |
| ASUSTek       | All Series                  | [a3bf15a0bb](https://linux-hardware.org/?probe=a3bf15a0bb) | May 21, 2019 |
| ASUSTek       | H97I-PLUS                   | [da88c70ab8](https://linux-hardware.org/?probe=da88c70ab8) | May 21, 2019 |
| ASRock        | X370 Professional Gaming    | [4bdd2cb29f](https://linux-hardware.org/?probe=4bdd2cb29f) | May 21, 2019 |
| ASRock        | X370 Professional Gaming    | [7f8dda505a](https://linux-hardware.org/?probe=7f8dda505a) | May 04, 2019 |
| ASUSTek       | H97I-PLUS                   | [e06c608ce2](https://linux-hardware.org/?probe=e06c608ce2) | Apr 20, 2019 |
| Foxconn       | ETON                        | [3a624021f2](https://linux-hardware.org/?probe=3a624021f2) | Apr 07, 2019 |
| Shuttle       | SH55J V10                   | [493f8f75a2](https://linux-hardware.org/?probe=493f8f75a2) | Mar 19, 2019 |
| HP            | ProLiant MicroServer Gen... | [f930bc123e](https://linux-hardware.org/?probe=f930bc123e) | Mar 19, 2019 |
| HP            | ProLiant MicroServer Gen... | [e2d3bb524c](https://linux-hardware.org/?probe=e2d3bb524c) | Mar 19, 2019 |
| MSI           | Z170A GAMING M5             | [d1ded92f20](https://linux-hardware.org/?probe=d1ded92f20) | Jan 22, 2019 |
| MSI           | Z170A GAMING M5             | [d90f3585da](https://linux-hardware.org/?probe=d90f3585da) | Jan 22, 2019 |
| Foxconn       | ETON                        | [0a48567e3d](https://linux-hardware.org/?probe=0a48567e3d) | Jan 19, 2019 |
| Foxconn       | ETON                        | [ee2e3cee37](https://linux-hardware.org/?probe=ee2e3cee37) | Jan 19, 2019 |
| ASUSTek       | H110M-R                     | [02243a34e9](https://linux-hardware.org/?probe=02243a34e9) | Jan 17, 2019 |
| ASUSTek       | H110M-R                     | [156d5825a0](https://linux-hardware.org/?probe=156d5825a0) | Jan 17, 2019 |
| ASUSTek       | H110M-R                     | [01a127d0a5](https://linux-hardware.org/?probe=01a127d0a5) | Jan 17, 2019 |
| ASUSTek       | Z170-A                      | [6c5c9c58a6](https://linux-hardware.org/?probe=6c5c9c58a6) | Jan 02, 2019 |
| ASUSTek       | Z170-A                      | [955082b1a3](https://linux-hardware.org/?probe=955082b1a3) | Jan 02, 2019 |
| ASUSTek       | Z170-A                      | [2600b6123e](https://linux-hardware.org/?probe=2600b6123e) | Nov 17, 2018 |
| ASUSTek       | B85M-E                      | [8321542cc3](https://linux-hardware.org/?probe=8321542cc3) | Oct 27, 2018 |
| ASUSTek       | X99-A/USB                   | [abb20b34f4](https://linux-hardware.org/?probe=abb20b34f4) | Oct 27, 2018 |
| ASUSTek       | P8Z77-V LK                  | [28e565d704](https://linux-hardware.org/?probe=28e565d704) | Oct 27, 2018 |
| ASUSTek       | P8Z77-V LK                  | [bb98a5c04e](https://linux-hardware.org/?probe=bb98a5c04e) | Oct 27, 2018 |
| Intel         | DH87RL AAG74240-402         | [8c48173c7b](https://linux-hardware.org/?probe=8c48173c7b) | Oct 26, 2018 |
| ASUSTek       | M5A97                       | [9cb0ac857a](https://linux-hardware.org/?probe=9cb0ac857a) | Oct 26, 2018 |
| ASUSTek       | Rampage V EXTREME           | [cca78b29d4](https://linux-hardware.org/?probe=cca78b29d4) | Oct 26, 2018 |
| Dell          | 0J3C2F A00                  | [d5a5261203](https://linux-hardware.org/?probe=d5a5261203) | Oct 26, 2018 |
| MSI           | B85M-E45                    | [a27e965ab5](https://linux-hardware.org/?probe=a27e965ab5) | Oct 26, 2018 |
| MSI           | B85M-E45                    | [92e6dd5745](https://linux-hardware.org/?probe=92e6dd5745) | Oct 26, 2018 |
| ASRock        | M3N78D                      | [2a34c16ab3](https://linux-hardware.org/?probe=2a34c16ab3) | Oct 19, 2018 |
| ASRock        | M3N78D                      | [5e82f33858](https://linux-hardware.org/?probe=5e82f33858) | Oct 12, 2018 |
| ASRock        | M3N78D                      | [f6fe2e1227](https://linux-hardware.org/?probe=f6fe2e1227) | Oct 12, 2018 |
| Gigabyte      | H77-DS3H                    | [740bf21a40](https://linux-hardware.org/?probe=740bf21a40) | Mar 24, 2018 |
| Gigabyte      | H77-DS3H                    | [91e187d130](https://linux-hardware.org/?probe=91e187d130) | Mar 24, 2018 |
| Gigabyte      | H77-DS3H                    | [455f8ed634](https://linux-hardware.org/?probe=455f8ed634) | Mar 24, 2018 |
| MSI           | 785GTM-E45                  | [9b75a42a1e](https://linux-hardware.org/?probe=9b75a42a1e) | Jan 13, 2018 |
| ASUSTek       | A88XM-E/USB                 | [71aba86389](https://linux-hardware.org/?probe=71aba86389) | Dec 17, 2017 |
| ASUSTek       | M4N78 PRO                   | [5226d38538](https://linux-hardware.org/?probe=5226d38538) | Dec 13, 2017 |
| ASUSTek       | P5KPL-AM                    | [08505850fa](https://linux-hardware.org/?probe=08505850fa) | Oct 22, 2017 |
| ASUSTek       | M2N68-AM SE2                | [ad71b3e918](https://linux-hardware.org/?probe=ad71b3e918) | Sep 25, 2017 |
| ASUSTek       | M2N68-AM SE2                | [1fb16c593e](https://linux-hardware.org/?probe=1fb16c593e) | Sep 25, 2017 |
| MSI           | 785GTM-E45                  | [400867cb6e](https://linux-hardware.org/?probe=400867cb6e) | Apr 15, 2017 |
| MSI           | 785GTM-E45                  | [b9bca139b4](https://linux-hardware.org/?probe=b9bca139b4) | Apr 15, 2017 |
| HP            | ProLiant MicroServer Gen... | [2d74ad691d](https://linux-hardware.org/?probe=2d74ad691d) | Jul 12, 2016 |
| HP            | ProLiant MicroServer        | [cf0d178690](https://linux-hardware.org/?probe=cf0d178690) | Mar 06, 2016 |
| HP            | ProLiant MicroServer Gen... | [0c1af5bc8c](https://linux-hardware.org/?probe=0c1af5bc8c) | Mar 06, 2016 |
| Shuttle       | SH55J V10                   | [45686e785e](https://linux-hardware.org/?probe=45686e785e) | Mar 06, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Gentoo 2.7   | 263      | 53.24%  |
| Gentoo 2.6   | 170      | 34.41%  |
| Gentoo 2.8   | 36       | 7.29%   |
| Gentoo       | 14       | 2.83%   |
| Gentoo 2.4.1 | 4        | 0.81%   |
| Gentoo 2.3   | 2        | 0.4%    |
| Gentoo 2.2   | 2        | 0.4%    |
| Gentoo 1     | 2        | 0.4%    |
| Gentoo 13.0  | 1        | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Gentoo | 460      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.4.38-gentoo           | 14       | 2.28%   |
| 5.4.97-gentoo           | 10       | 1.63%   |
| 5.7.0-gentoo            | 9        | 1.47%   |
| 5.4.28-gentoo           | 9        | 1.47%   |
| 5.10.61-gentoo          | 9        | 1.47%   |
| 5.10.27-gentoo          | 9        | 1.47%   |
| 5.4.38-gentoo-x86_64    | 7        | 1.14%   |
| 5.15.11-gentoo          | 7        | 1.14%   |
| 5.10.76-gentoo-r1       | 7        | 1.14%   |
| 5.10.52-gentoo          | 7        | 1.14%   |
| 5.10.27-gentoo-x86_64   | 7        | 1.14%   |
| 5.4.60-gentoo           | 6        | 0.98%   |
| 5.15.23-gentoo          | 6        | 0.98%   |
| 5.10.61-gentoo-x86_64   | 6        | 0.98%   |
| 5.6.15-gentoo           | 5        | 0.81%   |
| 5.6.11-gentoo           | 5        | 0.81%   |
| 5.4.80-gentoo-r1        | 5        | 0.81%   |
| 5.4.66-gentoo-x86_64    | 5        | 0.81%   |
| 5.4.66-gentoo           | 5        | 0.81%   |
| 5.4.48-gentoo           | 5        | 0.81%   |
| 5.15.26-gentoo          | 5        | 0.81%   |
| 4.19.86-gentoo          | 5        | 0.81%   |
| 5.9.11-gentoo           | 4        | 0.65%   |
| 5.4.80-gentoo-r1-x86_64 | 4        | 0.65%   |
| 5.4.48-gentoo-x86_64    | 4        | 0.65%   |
| 5.9.8-gentoo            | 3        | 0.49%   |
| 5.9.11                  | 3        | 0.49%   |
| 5.9.1-gentoo            | 3        | 0.49%   |
| 5.6.15-gentoo-x86_64    | 3        | 0.49%   |
| 5.4.97-gentoo-x86_64    | 3        | 0.49%   |
| 5.4.72-gentoo           | 3        | 0.49%   |
| 5.4.28-gentoo-x86_64    | 3        | 0.49%   |
| 5.17.1-gentoo-r1        | 3        | 0.49%   |
| 5.15.16-gentoo          | 3        | 0.49%   |
| 5.15.11-gentoo-x86_64   | 3        | 0.49%   |
| 5.15.10-gentoo          | 3        | 0.49%   |
| 5.14.14-gentoo          | 3        | 0.49%   |
| 5.13.5-gentoo           | 3        | 0.49%   |
| 5.11.6-gentoo           | 3        | 0.49%   |
| 5.11.0-gentoo           | 3        | 0.49%   |
| 5.10.7-gentoo           | 3        | 0.49%   |
| 5.10.4-gentoo           | 3        | 0.49%   |
| 5.10.35-gentoo          | 3        | 0.49%   |
| 5.10.2-gentoo           | 3        | 0.49%   |
| 5.1.9-gentoo            | 3        | 0.49%   |
| 5.0.2-gentoo            | 3        | 0.49%   |
| 4.4.4-gentoo            | 3        | 0.49%   |
| 4.19.97-gentoo          | 3        | 0.49%   |
| 4.14.65-gentoo          | 3        | 0.49%   |
| 5.9.9-gentoo            | 2        | 0.33%   |
| 5.9.8                   | 2        | 0.33%   |
| 5.9.13-gentoo           | 2        | 0.33%   |
| 5.8.10-gentoo           | 2        | 0.33%   |
| 5.8.0-gentoo-r1         | 2        | 0.33%   |
| 5.7.9-gentoo            | 2        | 0.33%   |
| 5.7.6-gentoo            | 2        | 0.33%   |
| 5.7.0-gentoo-x86_64     | 2        | 0.33%   |
| 5.6.2-gentoo            | 2        | 0.33%   |
| 5.6.14-gentoo           | 2        | 0.33%   |
| 5.6.13-gentoo           | 2        | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.38  | 28       | 4.56%   |
| 5.10.27 | 20       | 3.26%   |
| 5.10.61 | 17       | 2.77%   |
| 5.4.97  | 15       | 2.44%   |
| 5.4.28  | 14       | 2.28%   |
| 5.7.0   | 13       | 2.12%   |
| 5.10.52 | 13       | 2.12%   |
| 5.4.48  | 12       | 1.95%   |
| 5.10.76 | 12       | 1.95%   |
| 5.6.15  | 11       | 1.79%   |
| 5.4.66  | 11       | 1.79%   |
| 5.15.11 | 10       | 1.63%   |
| 5.9.11  | 9        | 1.47%   |
| 5.4.80  | 9        | 1.47%   |
| 5.4.60  | 9        | 1.47%   |
| 5.15.26 | 8        | 1.3%    |
| 5.6.11  | 7        | 1.14%   |
| 5.15.23 | 7        | 1.14%   |
| 4.19.86 | 7        | 1.14%   |
| 5.9.8   | 6        | 0.98%   |
| 5.8.10  | 6        | 0.98%   |
| 5.4.72  | 6        | 0.98%   |
| 5.11.6  | 6        | 0.98%   |
| 5.6.14  | 5        | 0.81%   |
| 5.6.13  | 5        | 0.81%   |
| 5.17.1  | 5        | 0.81%   |
| 5.15.32 | 5        | 0.81%   |
| 5.15.16 | 5        | 0.81%   |
| 4.19.97 | 5        | 0.81%   |
| 5.9.0   | 4        | 0.65%   |
| 5.8.0   | 4        | 0.65%   |
| 5.6.0   | 4        | 0.65%   |
| 5.17.0  | 4        | 0.65%   |
| 5.15.10 | 4        | 0.65%   |
| 5.14.14 | 4        | 0.65%   |
| 5.14.13 | 4        | 0.65%   |
| 5.13.12 | 4        | 0.65%   |
| 5.10.5  | 4        | 0.65%   |
| 5.10.2  | 4        | 0.65%   |
| 5.10.10 | 4        | 0.65%   |
| 5.9.1   | 3        | 0.49%   |
| 5.8.3   | 3        | 0.49%   |
| 5.8.12  | 3        | 0.49%   |
| 5.7.9   | 3        | 0.49%   |
| 5.7.6   | 3        | 0.49%   |
| 5.7.12  | 3        | 0.49%   |
| 5.5.0   | 3        | 0.49%   |
| 5.16.5  | 3        | 0.49%   |
| 5.15.19 | 3        | 0.49%   |
| 5.15.1  | 3        | 0.49%   |
| 5.15.0  | 3        | 0.49%   |
| 5.14.11 | 3        | 0.49%   |
| 5.13.5  | 3        | 0.49%   |
| 5.13.0  | 3        | 0.49%   |
| 5.12.5  | 3        | 0.49%   |
| 5.12.12 | 3        | 0.49%   |
| 5.11.2  | 3        | 0.49%   |
| 5.11.10 | 3        | 0.49%   |
| 5.11.0  | 3        | 0.49%   |
| 5.10.7  | 3        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 117      | 20.42%  |
| 5.10    | 95       | 16.58%  |
| 5.15    | 46       | 8.03%   |
| 5.6     | 39       | 6.81%   |
| 5.8     | 35       | 6.11%   |
| 5.9     | 30       | 5.24%   |
| 5.7     | 29       | 5.06%   |
| 4.19    | 26       | 4.54%   |
| 5.14    | 23       | 4.01%   |
| 5.11    | 20       | 3.49%   |
| 5.13    | 18       | 3.14%   |
| 5.16    | 15       | 2.62%   |
| 5.12    | 13       | 2.27%   |
| 5.17    | 10       | 1.75%   |
| 5.5     | 9        | 1.57%   |
| 5.2     | 8        | 1.4%    |
| 4.14    | 8        | 1.4%    |
| 5.0     | 6        | 1.05%   |
| 5.1     | 5        | 0.87%   |
| 4.9     | 4        | 0.7%    |
| 4.18    | 4        | 0.7%    |
| 4.4     | 3        | 0.52%   |
| 5.3     | 2        | 0.35%   |
| 6.0     | 1        | 0.17%   |
| 4.6     | 1        | 0.17%   |
| 4.20    | 1        | 0.17%   |
| 4.16    | 1        | 0.17%   |
| 4.13    | 1        | 0.17%   |
| 4.12    | 1        | 0.17%   |
| 4.10    | 1        | 0.17%   |
| 3.18    | 1        | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 445      | 96.74%  |
| i686     | 7        | 1.52%   |
| ppc      | 3        | 0.65%   |
| armv7l   | 2        | 0.43%   |
| ppc64le  | 1        | 0.22%   |
| ppc64    | 1        | 0.22%   |
| armv5tel | 1        | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 233      | 47.36%  |
| KDE5          | 92       | 18.7%   |
| GNOME         | 57       | 11.59%  |
| XFCE          | 43       | 8.74%   |
| KDE           | 30       | 6.1%    |
| MATE          | 13       | 2.64%   |
| dwm           | 5        | 1.02%   |
| X-Cinnamon    | 4        | 0.81%   |
| LXQt          | 3        | 0.61%   |
| sway          | 2        | 0.41%   |
| i3            | 2        | 0.41%   |
| Enlightenment | 2        | 0.41%   |
| XSession      | 1        | 0.2%    |
| openbox       | 1        | 0.2%    |
| LXDE          | 1        | 0.2%    |
| GNOME Classic | 1        | 0.2%    |
| Cinnamon      | 1        | 0.2%    |
| awesome       | 1        | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 278      | 56.85%  |
| Unknown | 111      | 22.7%   |
| Tty     | 73       | 14.93%  |
| Wayland | 27       | 5.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 260      | 54.28%  |
| SDDM    | 105      | 21.92%  |
| LightDM | 47       | 9.81%   |
| GDM     | 40       | 8.35%   |
| SLiM    | 10       | 2.09%   |
| XDM     | 9        | 1.88%   |
| LXDM    | 7        | 1.46%   |
| TDM     | 1        | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_US          | 166      | 34.58%  |
| Unknown        | 86       | 17.92%  |
| en_GB          | 36       | 7.5%    |
| de_DE          | 34       | 7.08%   |
| C.UTF8         | 29       | 6.04%   |
| ru_RU          | 22       | 4.58%   |
| C              | 13       | 2.71%   |
| es_ES          | 10       | 2.08%   |
| en_CA          | 10       | 2.08%   |
| pl_PL          | 9        | 1.88%   |
| fr_FR          | 6        | 1.25%   |
| ru_RU.UTF8     | 5        | 1.04%   |
| sv_SE          | 4        | 0.83%   |
| fi_FI          | 4        | 0.83%   |
| pt_BR          | 3        | 0.63%   |
| nl_NL          | 3        | 0.63%   |
| cs_CZ          | 3        | 0.63%   |
| ro_RO          | 2        | 0.42%   |
| nl_BE          | 2        | 0.42%   |
| ja_JP          | 2        | 0.42%   |
| it_IT          | 2        | 0.42%   |
| en_US.UTF8     | 2        | 0.42%   |
| en_DK          | 2        | 0.42%   |
| en_AU          | 2        | 0.42%   |
| zh_TW          | 1        | 0.21%   |
| zh_CN          | 1        | 0.21%   |
| uk_UA          | 1        | 0.21%   |
| spanish        | 1        | 0.21%   |
| sl_SI          | 1        | 0.21%   |
| ru_UA          | 1        | 0.21%   |
| pt_PT          | 1        | 0.21%   |
| hu_HU          | 1        | 0.21%   |
| fr_FR.UTF8     | 1        | 0.21%   |
| fr_CA          | 1        | 0.21%   |
| et_EE          | 1        | 0.21%   |
| es_AR          | 1        | 0.21%   |
| en_ZA          | 1        | 0.21%   |
| en_NZ          | 1        | 0.21%   |
| en_IN          | 1        | 0.21%   |
| en_IE          | 1        | 0.21%   |
| en_GB.iso88591 | 1        | 0.21%   |
| en_EN          | 1        | 0.21%   |
| en_DE          | 1        | 0.21%   |
| el_GR          | 1        | 0.21%   |
| de_CH.UTF8     | 1        | 0.21%   |
| de_CH          | 1        | 0.21%   |
| ca_ES          | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 287      | 61.32%  |
| BIOS | 181      | 38.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 300      | 63.16%  |
| Btrfs    | 88       | 18.53%  |
| Xfs      | 20       | 4.21%   |
| Zfs      | 19       | 4%      |
| F2fs     | 19       | 4%      |
| Unknown  | 17       | 3.58%   |
| Reiserfs | 8        | 1.68%   |
| XXX      | 2        | 0.42%   |
| Jfs      | 1        | 0.21%   |
| Ext3     | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 368      | 78.63%  |
| MBR     | 67       | 14.32%  |
| Unknown | 33       | 7.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 320      | 65.84%  |
| Yes       | 166      | 34.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 305      | 64.62%  |
| Yes       | 167      | 35.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 168      | 36.52%  |
| MSI                 | 76       | 16.52%  |
| ASRock              | 66       | 14.35%  |
| Gigabyte Technology | 64       | 13.91%  |
| Hewlett-Packard     | 14       | 3.04%   |
| Unknown             | 14       | 3.04%   |
| Dell                | 12       | 2.61%   |
| Intel               | 8        | 1.74%   |
| Fujitsu             | 6        | 1.3%    |
| Acer                | 6        | 1.3%    |
| Tekram Technology   | 3        | 0.65%   |
| Lenovo              | 3        | 0.65%   |
| ASRockRack          | 3        | 0.65%   |
| Foxconn             | 2        | 0.43%   |
| Apple               | 2        | 0.43%   |
| YANYU               | 1        | 0.22%   |
| Supermicro          | 1        | 0.22%   |
| Sun Microsystems    | 1        | 0.22%   |
| Shuttle             | 1        | 0.22%   |
| QDI                 | 1        | 0.22%   |
| Pegatron            | 1        | 0.22%   |
| Packard Bell        | 1        | 0.22%   |
| NZXT                | 1        | 0.22%   |
| Medion              | 1        | 0.22%   |
| EVGA                | 1        | 0.22%   |
| Entroware           | 1        | 0.22%   |
| BESSTAR Tech        | 1        | 0.22%   |
| Alienware           | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 17       | 3.7%    |
| Unknown                            | 14       | 3.04%   |
| ASUS PRIME X470-PRO                | 7        | 1.52%   |
| ASUS TUF GAMING X570-PLUS          | 6        | 1.3%    |
| ASUS PRIME X570-PRO                | 6        | 1.3%    |
| ASUS PRIME X370-PRO                | 5        | 1.09%   |
| MSI MS-7C35                        | 4        | 0.87%   |
| MSI MS-7C02                        | 4        | 0.87%   |
| MSI MS-7B86                        | 4        | 0.87%   |
| MSI MS-7A38                        | 4        | 0.87%   |
| ASUS Z170 PRO GAMING               | 4        | 0.87%   |
| ASUS ROG STRIX B550-F GAMING       | 4        | 0.87%   |
| ASUS ROG CROSSHAIR VIII HERO       | 4        | 0.87%   |
| ASRock B550M Steel Legend          | 4        | 0.87%   |
| ASRock B450 Pro4                   | 4        | 0.87%   |
| Tekram P6B40-A4X-i440BX Rev        | 3        | 0.65%   |
| MSI MS-7C37                        | 3        | 0.65%   |
| MSI MS-7B79                        | 3        | 0.65%   |
| MSI MS-7693                        | 3        | 0.65%   |
| HP ProLiant MicroServer Gen8       | 3        | 0.65%   |
| Fujitsu D3401-H1                   | 3        | 0.65%   |
| ASUS TUF GAMING B550-PLUS          | 3        | 0.65%   |
| ASUS ROG CROSSHAIR VII HERO        | 3        | 0.65%   |
| ASUS PRIME X570-P                  | 3        | 0.65%   |
| ASRock Z390 Extreme4               | 3        | 0.65%   |
| ASRock B450M-HDV R4.0              | 3        | 0.65%   |
| MSI MS-7C91                        | 2        | 0.43%   |
| MSI MS-7C84                        | 2        | 0.43%   |
| MSI MS-7C56                        | 2        | 0.43%   |
| MSI MS-7C34                        | 2        | 0.43%   |
| MSI MS-7B89                        | 2        | 0.43%   |
| MSI MS-7A34                        | 2        | 0.43%   |
| MSI MS-7885                        | 2        | 0.43%   |
| MSI MS-7549                        | 2        | 0.43%   |
| Gigabyte X570 AORUS XTREME         | 2        | 0.43%   |
| Gigabyte X570 AORUS ELITE          | 2        | 0.43%   |
| Gigabyte B450M S2H                 | 2        | 0.43%   |
| Gigabyte B450M DS3H                | 2        | 0.43%   |
| Gigabyte AB350-Gaming 3            | 2        | 0.43%   |
| Fujitsu ESPRIMO P7935              | 2        | 0.43%   |
| Dell OptiPlex 790                  | 2        | 0.43%   |
| ASUS TUF GAMING Z590-PLUS WIFI     | 2        | 0.43%   |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.43%   |
| ASUS ROG STRIX X570-F GAMING       | 2        | 0.43%   |
| ASUS ROG STRIX X570-E GAMING       | 2        | 0.43%   |
| ASUS ROG STRIX X470-F GAMING       | 2        | 0.43%   |
| ASUS ROG STRIX B550-I GAMING       | 2        | 0.43%   |
| ASUS ROG STRIX B450-F GAMING       | 2        | 0.43%   |
| ASUS ROG CROSSHAIR VIII DARK HERO  | 2        | 0.43%   |
| ASUS PRIME B350-PLUS               | 2        | 0.43%   |
| ASUS P6X58D-E                      | 2        | 0.43%   |
| ASUS P5LD2-Deluxe                  | 2        | 0.43%   |
| ASUS Maximus VIII HERO             | 2        | 0.43%   |
| ASUS M4A89GTD-PRO/USB3             | 2        | 0.43%   |
| ASUS M3A78-CM                      | 2        | 0.43%   |
| ASRock X570 Steel Legend           | 2        | 0.43%   |
| ASRock X570 Phantom Gaming-ITX/TB3 | 2        | 0.43%   |
| ASRock X399 Taichi                 | 2        | 0.43%   |
| ASRock X370 Professional Gaming    | 2        | 0.43%   |
| ASRock AM1H-ITX                    | 2        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 37       | 8.04%   |
| ASUS ROG                | 36       | 7.83%   |
| ASUS TUF                | 20       | 4.35%   |
| ASUS All                | 17       | 3.7%    |
| Unknown                 | 14       | 3.04%   |
| Gigabyte X570           | 9        | 1.96%   |
| ASRock X570             | 9        | 1.96%   |
| Dell OptiPlex           | 7        | 1.52%   |
| ASRock X370             | 7        | 1.52%   |
| Gigabyte B450M          | 6        | 1.3%    |
| Acer Aspire             | 6        | 1.3%    |
| HP ProLiant             | 5        | 1.09%   |
| Gigabyte B450           | 5        | 1.09%   |
| MSI MS-7C35             | 4        | 0.87%   |
| MSI MS-7C02             | 4        | 0.87%   |
| MSI MS-7B86             | 4        | 0.87%   |
| MSI MS-7A38             | 4        | 0.87%   |
| HP Compaq               | 4        | 0.87%   |
| ASUS Z170               | 4        | 0.87%   |
| ASUS M5A97              | 4        | 0.87%   |
| ASRock B550M            | 4        | 0.87%   |
| ASRock B450             | 4        | 0.87%   |
| Tekram P6B40-A4X-i440BX | 3        | 0.65%   |
| MSI MS-7C37             | 3        | 0.65%   |
| MSI MS-7B79             | 3        | 0.65%   |
| MSI MS-7693             | 3        | 0.65%   |
| Lenovo ThinkCentre      | 3        | 0.65%   |
| Gigabyte AB350-Gaming   | 3        | 0.65%   |
| Fujitsu D3401-H1        | 3        | 0.65%   |
| Dell Precision          | 3        | 0.65%   |
| ASUS SABERTOOTH         | 3        | 0.65%   |
| ASUS P8Z77-V            | 3        | 0.65%   |
| ASRock Z390             | 3        | 0.65%   |
| ASRock B450M-HDV        | 3        | 0.65%   |
| MSI MS-7C91             | 2        | 0.43%   |
| MSI MS-7C84             | 2        | 0.43%   |
| MSI MS-7C56             | 2        | 0.43%   |
| MSI MS-7C34             | 2        | 0.43%   |
| MSI MS-7B89             | 2        | 0.43%   |
| MSI MS-7A34             | 2        | 0.43%   |
| MSI MS-7885             | 2        | 0.43%   |
| MSI MS-7549             | 2        | 0.43%   |
| Gigabyte Z490           | 2        | 0.43%   |
| Gigabyte Z390           | 2        | 0.43%   |
| Fujitsu ESPRIMO         | 2        | 0.43%   |
| ASUS STRIX              | 2        | 0.43%   |
| ASUS P9X79              | 2        | 0.43%   |
| ASUS P6X58D-E           | 2        | 0.43%   |
| ASUS P5LD2-Deluxe       | 2        | 0.43%   |
| ASUS Maximus            | 2        | 0.43%   |
| ASUS M4A89GTD-PRO       | 2        | 0.43%   |
| ASUS M3A78-CM           | 2        | 0.43%   |
| ASRock Z68              | 2        | 0.43%   |
| ASRock Z170             | 2        | 0.43%   |
| ASRock X470             | 2        | 0.43%   |
| ASRock X399             | 2        | 0.43%   |
| ASRock B550             | 2        | 0.43%   |
| ASRock AM1H-ITX         | 2        | 0.43%   |
| YANYU H17SL             | 1        | 0.22%   |
| Supermicro A1SRM-2758F  | 1        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 74       | 16.09%  |
| 2018    | 69       | 15%     |
| 2020    | 52       | 11.3%   |
| 2017    | 41       | 8.91%   |
| 2015    | 28       | 6.09%   |
| 2013    | 28       | 6.09%   |
| 2012    | 28       | 6.09%   |
| 2016    | 27       | 5.87%   |
| 2009    | 20       | 4.35%   |
| 2010    | 16       | 3.48%   |
| 2021    | 15       | 3.26%   |
| 2011    | 15       | 3.26%   |
| 2014    | 13       | 2.83%   |
| 2008    | 13       | 2.83%   |
| Unknown | 8        | 1.74%   |
| 2007    | 5        | 1.09%   |
| 2000    | 3        | 0.65%   |
| 2005    | 2        | 0.43%   |
| 2022    | 1        | 0.22%   |
| 2004    | 1        | 0.22%   |
| 2003    | 1        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 460      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 453      | 98.05%  |
| Enabled  | 9        | 1.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 460      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 152      | 32.14%  |
| 16.01-24.0  | 129      | 27.27%  |
| 64.01-256.0 | 66       | 13.95%  |
| 8.01-16.0   | 44       | 9.3%    |
| 3.01-4.0    | 22       | 4.65%   |
| 4.01-8.0    | 21       | 4.44%   |
| 24.01-32.0  | 18       | 3.81%   |
| 1.01-2.0    | 10       | 2.11%   |
| 0.51-1.0    | 6        | 1.27%   |
| 2.01-3.0    | 3        | 0.63%   |
| 0.01-0.5    | 1        | 0.21%   |
| Unknown     | 1        | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 118      | 21.61%  |
| 1.01-2.0    | 96       | 17.58%  |
| 2.01-3.0    | 92       | 16.85%  |
| 8.01-16.0   | 64       | 11.72%  |
| 3.01-4.0    | 53       | 9.71%   |
| 0.01-0.5    | 51       | 9.34%   |
| 0.51-1.0    | 32       | 5.86%   |
| 16.01-24.0  | 25       | 4.58%   |
| 32.01-64.0  | 8        | 1.47%   |
| 24.01-32.0  | 4        | 0.73%   |
| 64.01-256.0 | 2        | 0.37%   |
| Unknown     | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 129      | 26.06%  |
| 3      | 108      | 21.82%  |
| 1      | 94       | 18.99%  |
| 4      | 69       | 13.94%  |
| 5      | 46       | 9.29%   |
| 6      | 20       | 4.04%   |
| 7      | 14       | 2.83%   |
| 8      | 5        | 1.01%   |
| 9      | 3        | 0.61%   |
| 0      | 2        | 0.4%    |
| 18     | 1        | 0.2%    |
| 17     | 1        | 0.2%    |
| 13     | 1        | 0.2%    |
| 11     | 1        | 0.2%    |
| 10     | 1        | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 316      | 67.09%  |
| Yes       | 155      | 32.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 452      | 98.26%  |
| No        | 8        | 1.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 301      | 64.45%  |
| Yes       | 166      | 35.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 301      | 64.45%  |
| Yes       | 166      | 35.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 96       | 20.73%  |
| Germany      | 72       | 15.55%  |
| Russia       | 46       | 9.94%   |
| UK           | 29       | 6.26%   |
| Spain        | 20       | 4.32%   |
| Canada       | 18       | 3.89%   |
| Poland       | 17       | 3.67%   |
| France       | 15       | 3.24%   |
| Finland      | 15       | 3.24%   |
| Sweden       | 13       | 2.81%   |
| Ukraine      | 10       | 2.16%   |
| Netherlands  | 7        | 1.51%   |
| Italy        | 7        | 1.51%   |
| Australia    | 7        | 1.51%   |
| Switzerland  | 6        | 1.3%    |
| Czechia      | 6        | 1.3%    |
| Belgium      | 6        | 1.3%    |
| Greece       | 5        | 1.08%   |
| Brazil       | 5        | 1.08%   |
| Austria      | 5        | 1.08%   |
| Norway       | 4        | 0.86%   |
| Estonia      | 4        | 0.86%   |
| China        | 4        | 0.86%   |
| Slovenia     | 3        | 0.65%   |
| Slovakia     | 3        | 0.65%   |
| Romania      | 3        | 0.65%   |
| Mexico       | 3        | 0.65%   |
| Japan        | 3        | 0.65%   |
| Hungary      | 3        | 0.65%   |
| Hong Kong    | 3        | 0.65%   |
| Belarus      | 3        | 0.65%   |
| Argentina    | 3        | 0.65%   |
| Jamaica      | 2        | 0.43%   |
| Denmark      | 2        | 0.43%   |
| Bulgaria     | 2        | 0.43%   |
| Tunisia      | 1        | 0.22%   |
| Taiwan       | 1        | 0.22%   |
| South Africa | 1        | 0.22%   |
| Reunion      | 1        | 0.22%   |
| Philippines  | 1        | 0.22%   |
| New Zealand  | 1        | 0.22%   |
| Malaysia     | 1        | 0.22%   |
| Kazakhstan   | 1        | 0.22%   |
| Ireland      | 1        | 0.22%   |
| India        | 1        | 0.22%   |
| El Salvador  | 1        | 0.22%   |
| Chile        | 1        | 0.22%   |
| Bangladesh   | 1        | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Berlin               | 12       | 2.35%   |
| St Petersburg        | 10       | 1.96%   |
| Moscow               | 10       | 1.96%   |
| Helsinki             | 7        | 1.37%   |
| Warsaw               | 6        | 1.18%   |
| Ottawa               | 6        | 1.18%   |
| Vladivostok          | 5        | 0.98%   |
| Zurich               | 4        | 0.78%   |
| Paris                | 4        | 0.78%   |
| Oulu                 | 4        | 0.78%   |
| Nuremberg            | 4        | 0.78%   |
| Neu-Isenburg         | 4        | 0.78%   |
| Los Angeles          | 4        | 0.78%   |
| Glen Ellyn           | 4        | 0.78%   |
| Fulda                | 4        | 0.78%   |
| Athens               | 4        | 0.78%   |
| Wuelfrath            | 3        | 0.59%   |
| Tallinn              | 3        | 0.59%   |
| Sydney               | 3        | 0.59%   |
| Swansea              | 3        | 0.59%   |
| Pont-l'AbbÃ©       | 3        | 0.59%   |
| Munich               | 3        | 0.59%   |
| Monroe               | 3        | 0.59%   |
| Manitowoc            | 3        | 0.59%   |
| London               | 3        | 0.59%   |
| Kyiv                 | 3        | 0.59%   |
| Freiburg im Breisgau | 3        | 0.59%   |
| Falkenstein          | 3        | 0.59%   |
| Cieszyn              | 3        | 0.59%   |
| Catford              | 3        | 0.59%   |
| Bucharest            | 3        | 0.59%   |
| Brno                 | 3        | 0.59%   |
| Bratislava           | 3        | 0.59%   |
| Antwerp              | 3        | 0.59%   |
| Yekaterinburg        | 2        | 0.39%   |
| Vienna               | 2        | 0.39%   |
| Vancouver            | 2        | 0.39%   |
| Ufa                  | 2        | 0.39%   |
| Tomsk                | 2        | 0.39%   |
| The Villages         | 2        | 0.39%   |
| Tampere              | 2        | 0.39%   |
| Sunnyvale            | 2        | 0.39%   |
| Summerfield          | 2        | 0.39%   |
| Suffolk              | 2        | 0.39%   |
| Stockholm            | 2        | 0.39%   |
| Sofia                | 2        | 0.39%   |
| Smolensk             | 2        | 0.39%   |
| Sao Paulo            | 2        | 0.39%   |
| San Jose             | 2        | 0.39%   |
| Sahuarita            | 2        | 0.39%   |
| Preston              | 2        | 0.39%   |
| Prague               | 2        | 0.39%   |
| Poplar               | 2        | 0.39%   |
| Ocala                | 2        | 0.39%   |
| Novosibirsk          | 2        | 0.39%   |
| Novokuznetsk         | 2        | 0.39%   |
| New York             | 2        | 0.39%   |
| Milan                | 2        | 0.39%   |
| Melbourne            | 2        | 0.39%   |
| Madrid               | 2        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 209      | 500    | 21.52%  |
| Samsung Electronics | 202      | 442    | 20.8%   |
| Seagate             | 164      | 356    | 16.89%  |
| Kingston            | 62       | 85     | 6.39%   |
| SanDisk             | 38       | 53     | 3.91%   |
| Intel               | 36       | 52     | 3.71%   |
| Hitachi             | 34       | 111    | 3.5%    |
| Crucial             | 34       | 59     | 3.5%    |
| Toshiba             | 33       | 67     | 3.4%    |
| A-DATA Technology   | 21       | 29     | 2.16%   |
| HGST                | 18       | 51     | 1.85%   |
| Corsair             | 15       | 28     | 1.54%   |
| Phison              | 13       | 23     | 1.34%   |
| GOODRAM             | 7        | 37     | 0.72%   |
| OCZ                 | 6        | 6      | 0.62%   |
| Unknown             | 5        | 7      | 0.51%   |
| PLEXTOR             | 5        | 6      | 0.51%   |
| Patriot             | 5        | 8      | 0.51%   |
| IBM                 | 5        | 6      | 0.51%   |
| Transcend           | 4        | 6      | 0.41%   |
| SPCC                | 4        | 4      | 0.41%   |
| PNY                 | 4        | 4      | 0.41%   |
| Mushkin             | 4        | 4      | 0.41%   |
| XPG                 | 3        | 3      | 0.31%   |
| LITEONIT            | 3        | 3      | 0.31%   |
| Team                | 2        | 7      | 0.21%   |
| SK Hynix            | 2        | 3      | 0.21%   |
| Micron Technology   | 2        | 4      | 0.21%   |
| MDT                 | 2        | 2      | 0.21%   |
| LaCie               | 2        | 12     | 0.21%   |
| KIOXIA-EXCERIA      | 2        | 3      | 0.21%   |
| Intenso             | 2        | 3      | 0.21%   |
| Gigabyte Technology | 2        | 3      | 0.21%   |
| Apacer              | 2        | 3      | 0.21%   |
| TO Exter            | 1        | 1      | 0.1%    |
| Smartbuy            | 1        | 1      | 0.1%    |
| Silicon Motion      | 1        | 2      | 0.1%    |
| OWC                 | 1        | 1      | 0.1%    |
| OCZ-VERTEX          | 1        | 1      | 0.1%    |
| LITEON              | 1        | 1      | 0.1%    |
| Linux               | 1        | 1      | 0.1%    |
| Leven               | 1        | 2      | 0.1%    |
| KIOXIA              | 1        | 2      | 0.1%    |
| KingDian            | 1        | 1      | 0.1%    |
| Kingchuxing         | 1        | 4      | 0.1%    |
| Hewlett-Packard     | 1        | 1      | 0.1%    |
| EMTEC               | 1        | 3      | 0.1%    |
| Dogfish             | 1        | 1      | 0.1%    |
| CT2000MX            | 1        | 2      | 0.1%    |
| China               | 1        | 1      | 0.1%    |
| ASMedia             | 1        | 1      | 0.1%    |
| AMD-RAID            | 1        | 2      | 0.1%    |
| AMD                 | 1        | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 16       | 1.29%   |
| WDC WD30EFRX-68EUZN0 3TB         | 15       | 1.21%   |
| Samsung SSD 850 EVO 500GB        | 15       | 1.21%   |
| Samsung SSD 860 EVO 250GB        | 14       | 1.13%   |
| Samsung SSD 860 EVO 1TB          | 14       | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB   | 11       | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB   | 10       | 0.81%   |
| Samsung SSD 970 EVO 500GB        | 10       | 0.81%   |
| Samsung SSD 970 EVO 250GB        | 10       | 0.81%   |
| Samsung SSD 970 EVO 1TB          | 10       | 0.81%   |
| Samsung SSD 840 EVO 120GB        | 10       | 0.81%   |
| Seagate ST500DM002-1BD142 500GB  | 9        | 0.73%   |
| Seagate ST3500418AS 500GB        | 9        | 0.73%   |
| Samsung SSD 980 PRO 1TB          | 9        | 0.73%   |
| Samsung SSD 970 EVO Plus 1TB     | 9        | 0.73%   |
| WDC WD40EFRX-68WT0N0 4TB         | 8        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB         | 8        | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB   | 8        | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB   | 8        | 0.65%   |
| Samsung SSD 860 EVO 500GB        | 8        | 0.65%   |
| Samsung SSD 840 EVO 250GB        | 8        | 0.65%   |
| Kingston SA400S37240G 240GB SSD  | 8        | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB         | 7        | 0.56%   |
| WDC WD20EZRX-00D8PB0 2TB         | 7        | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB         | 7        | 0.56%   |
| Seagate ST2000DM006-2DM164 2TB   | 7        | 0.56%   |
| Samsung SSD 970 PRO 512GB        | 7        | 0.56%   |
| Samsung SSD 960 EVO 500GB        | 7        | 0.56%   |
| Kingston SA400S37120G 120GB SSD  | 7        | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 6        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 6        | 0.48%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 6        | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB   | 6        | 0.48%   |
| Samsung SSD 970 EVO Plus 250GB   | 6        | 0.48%   |
| Samsung SSD 850 EVO 1TB          | 6        | 0.48%   |
| A-DATA SX8200PNP 1TB             | 6        | 0.48%   |
| WDC WD10EZEX-08M2NA0 1TB         | 5        | 0.4%    |
| Toshiba DT01ACA100 1TB           | 5        | 0.4%    |
| Seagate ST4000DM000-1F2168 4TB   | 5        | 0.4%    |
| Samsung SSD 960 EVO 250GB        | 5        | 0.4%    |
| Samsung SSD 840 PRO Series 256GB | 5        | 0.4%    |
| Samsung SSD 830 Series 128GB     | 5        | 0.4%    |
| Kingston SUV400S37120G 120GB SSD | 5        | 0.4%    |
| Kingston SA400S37480G 480GB SSD  | 5        | 0.4%    |
| Kingston SA2000M81000G 1TB       | 5        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB      | 5        | 0.4%    |
| WDC WDS500G3X0C-00SJG0 500GB     | 4        | 0.32%   |
| WDC WD30EFRX-68AX9N0 3TB         | 4        | 0.32%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 4        | 0.32%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 4        | 0.32%   |
| WDC WD10EZEX-60WN4A0 1TB         | 4        | 0.32%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 4        | 0.32%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 4        | 0.32%   |
| Seagate ST8000DM004-2CX188 8TB   | 4        | 0.32%   |
| Seagate ST8000AS0002-1NA17Z 8TB  | 4        | 0.32%   |
| Seagate ST4000VN000-1H4168 4TB   | 4        | 0.32%   |
| Seagate ST31000528AS 1TB         | 4        | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.32%   |
| SanDisk SSD PLUS 480GB           | 4        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 188      | 448    | 40.87%  |
| Seagate             | 159      | 351    | 34.57%  |
| Hitachi             | 34       | 111    | 7.39%   |
| Toshiba             | 29       | 62     | 6.3%    |
| Samsung Electronics | 19       | 28     | 4.13%   |
| HGST                | 18       | 51     | 3.91%   |
| IBM                 | 5        | 6      | 1.09%   |
| Unknown             | 3        | 4      | 0.65%   |
| MDT                 | 2        | 2      | 0.43%   |
| LaCie               | 2        | 12     | 0.43%   |
| ASMedia             | 1        | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 123      | 235    | 35.04%  |
| Kingston            | 51       | 64     | 14.53%  |
| SanDisk             | 35       | 50     | 9.97%   |
| Crucial             | 30       | 51     | 8.55%   |
| WDC                 | 22       | 25     | 6.27%   |
| Intel               | 15       | 19     | 4.27%   |
| Corsair             | 9        | 14     | 2.56%   |
| GOODRAM             | 7        | 37     | 1.99%   |
| A-DATA Technology   | 7        | 9      | 1.99%   |
| OCZ                 | 5        | 5      | 1.42%   |
| PLEXTOR             | 4        | 4      | 1.14%   |
| Transcend           | 3        | 5      | 0.85%   |
| Toshiba             | 3        | 3      | 0.85%   |
| SPCC                | 3        | 3      | 0.85%   |
| PNY                 | 3        | 3      | 0.85%   |
| Patriot             | 3        | 6      | 0.85%   |
| Mushkin             | 3        | 3      | 0.85%   |
| LITEONIT            | 3        | 3      | 0.85%   |
| Micron Technology   | 2        | 4      | 0.57%   |
| Intenso             | 2        | 3      | 0.57%   |
| Unknown             | 1        | 1      | 0.28%   |
| TO Exter            | 1        | 1      | 0.28%   |
| Team                | 1        | 2      | 0.28%   |
| Smartbuy            | 1        | 1      | 0.28%   |
| OWC                 | 1        | 1      | 0.28%   |
| OCZ-VERTEX          | 1        | 1      | 0.28%   |
| LITEON              | 1        | 1      | 0.28%   |
| Linux               | 1        | 1      | 0.28%   |
| Leven               | 1        | 2      | 0.28%   |
| KingDian            | 1        | 1      | 0.28%   |
| Hewlett-Packard     | 1        | 1      | 0.28%   |
| EMTEC               | 1        | 3      | 0.28%   |
| Dogfish             | 1        | 1      | 0.28%   |
| CT2000MX            | 1        | 2      | 0.28%   |
| China               | 1        | 1      | 0.28%   |
| Apacer              | 1        | 2      | 0.28%   |
| AMD-RAID            | 1        | 2      | 0.28%   |
| AMD                 | 1        | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 341      | 1076   | 41.08%  |
| SSD     | 277      | 571    | 33.37%  |
| NVMe    | 210      | 369    | 25.3%   |
| MMC     | 1        | 2      | 0.12%   |
| Unknown | 1        | 1      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 410      | 1616   | 64.36%  |
| NVMe | 210      | 369    | 32.97%  |
| SAS  | 16       | 32     | 2.51%   |
| MMC  | 1        | 2      | 0.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 296      | 617    | 41.28%  |
| 0.51-1.0   | 188      | 349    | 26.22%  |
| 1.01-2.0   | 105      | 235    | 14.64%  |
| 3.01-4.0   | 56       | 162    | 7.81%   |
| 2.01-3.0   | 39       | 125    | 5.44%   |
| 4.01-10.0  | 29       | 139    | 4.04%   |
| 10.01-20.0 | 3        | 19     | 0.42%   |
| 20.01-50.0 | 1        | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 88       | 17.67%  |
| 501-1000       | 77       | 15.46%  |
| 1001-2000      | 74       | 14.86%  |
| 101-250        | 71       | 14.26%  |
| 251-500        | 70       | 14.06%  |
| 2001-3000      | 49       | 9.84%   |
| Unknown        | 25       | 5.02%   |
| 1-20           | 19       | 3.82%   |
| 51-100         | 19       | 3.82%   |
| 21-50          | 6        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 76       | 14.76%  |
| 101-250        | 70       | 13.59%  |
| 251-500        | 69       | 13.4%   |
| 501-1000       | 61       | 11.84%  |
| 1001-2000      | 60       | 11.65%  |
| 21-50          | 49       | 9.51%   |
| More than 3000 | 46       | 8.93%   |
| 51-100         | 36       | 6.99%   |
| Unknown        | 25       | 4.85%   |
| 2001-3000      | 23       | 4.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 6        | 8      | 4.35%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 4        | 14     | 2.9%    |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3        | 15     | 2.17%   |
| Seagate ST500DM002-1BD142 500GB              | 3        | 3      | 2.17%   |
| Seagate ST500DM002-1BC142 500GB              | 3        | 3      | 2.17%   |
| IBM DJSA-220 12GB                            | 3        | 3      | 2.17%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 2        | 5      | 1.45%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 2        | 3      | 1.45%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 2        | 3      | 1.45%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2        | 2      | 1.45%   |
| WDC WD15EARS-00Z5B1 1TB                      | 2        | 2      | 1.45%   |
| Seagate ST4000DM000-1F2168 4TB               | 2        | 2      | 1.45%   |
| Seagate ST31000340NS 1TB                     | 2        | 3      | 1.45%   |
| Seagate ST2000DL003-9VT166 2TB               | 2        | 3      | 1.45%   |
| Seagate ST1000NM0011 1TB                     | 2        | 6      | 1.45%   |
| SanDisk SSD PLUS 1000GB                      | 2        | 2      | 1.45%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2        | 4      | 1.45%   |
| Samsung Electronics HD103UJ 1TB              | 2        | 2      | 1.45%   |
| MDT MD2000KS-00MJB0 200GB                    | 2        | 2      | 1.45%   |
| Hitachi HDS722020ALA330 2TB                  | 2        | 16     | 1.45%   |
| Crucial CT525MX300SSD1 528GB                 | 2        | 2      | 1.45%   |
| WDC WD80EFZX-68UW8N0 8TB                     | 1        | 2      | 0.72%   |
| WDC WD7501AALS-00J7B0 752GB                  | 1        | 1      | 0.72%   |
| WDC WD6400AAKS-65A7B2 640GB                  | 1        | 1      | 0.72%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 21     | 0.72%   |
| WDC WD5000BEVT-22ZAT0 500GB                  | 1        | 1      | 0.72%   |
| WDC WD5000AZRX-00A8LB0 500GB                 | 1        | 1      | 0.72%   |
| WDC WD5000AAVS-22G9B1 500GB                  | 1        | 1      | 0.72%   |
| WDC WD5000AAKX-003CA0 500GB                  | 1        | 1      | 0.72%   |
| WDC WD5000AAKS-00UU3A0 500GB                 | 1        | 2      | 0.72%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 1      | 0.72%   |
| WDC WD4004FZWX-00GBGB0 4TB                   | 1        | 1      | 0.72%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1        | 1      | 0.72%   |
| WDC WD2502ABYS-02B7A0 256GB                  | 1        | 1      | 0.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1        | 1      | 0.72%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1        | 1      | 0.72%   |
| WDC WD2003FZEX-00Z4SA0 2TB                   | 1        | 1      | 0.72%   |
| WDC WD2002FAEX-007BA0 2TB                    | 1        | 1      | 0.72%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 1        | 1      | 0.72%   |
| WDC WD10EZRX-00A8LB0 1TB                     | 1        | 1      | 0.72%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1        | 1      | 0.72%   |
| WDC WD10EARS-00Y5B1 1TB                      | 1        | 1      | 0.72%   |
| WDC WD10EACS-22D6B0 1TB                      | 1        | 1      | 0.72%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1        | 2      | 0.72%   |
| WDC WD1002FBYS-18W8B0 1TB                    | 1        | 1      | 0.72%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1        | 1      | 0.72%   |
| WDC WD1002FAEX-00Y9A0 1TB                    | 1        | 1      | 0.72%   |
| Toshiba MQ04ABF100 1TB                       | 1        | 1      | 0.72%   |
| Toshiba HDWD130 3TB                          | 1        | 1      | 0.72%   |
| Toshiba HDWD105 500GB                        | 1        | 2      | 0.72%   |
| Toshiba DT01ACA300 3TB                       | 1        | 1      | 0.72%   |
| Toshiba DT01ABA100V 1TB                      | 1        | 1      | 0.72%   |
| Seagate ST8000VX0022-2EJ112 8TB              | 1        | 2      | 0.72%   |
| Seagate ST500LT012-1DG142 500GB              | 1        | 1      | 0.72%   |
| Seagate ST4000VN000-1H4168 4TB               | 1        | 1      | 0.72%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1      | 0.72%   |
| Seagate ST3808110AS 80GB                     | 1        | 1      | 0.72%   |
| Seagate ST3500630AS 500GB                    | 1        | 1      | 0.72%   |
| Seagate ST3500413AS 500GB                    | 1        | 1      | 0.72%   |
| Seagate ST3320813AS 320GB                    | 1        | 1      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 39       | 64     | 30.23%  |
| WDC                 | 36       | 78     | 27.91%  |
| Samsung Electronics | 13       | 18     | 10.08%  |
| Hitachi             | 9        | 23     | 6.98%   |
| Toshiba             | 5        | 6      | 3.88%   |
| Crucial             | 5        | 5      | 3.88%   |
| SanDisk             | 4        | 5      | 3.1%    |
| IBM                 | 4        | 4      | 3.1%    |
| Kingston            | 3        | 3      | 2.33%   |
| PLEXTOR             | 2        | 2      | 1.55%   |
| MDT                 | 2        | 2      | 1.55%   |
| Corsair             | 2        | 4      | 1.55%   |
| OCZ                 | 1        | 1      | 0.78%   |
| Mushkin             | 1        | 1      | 0.78%   |
| Intel               | 1        | 1      | 0.78%   |
| HGST                | 1        | 1      | 0.78%   |
| EMTEC               | 1        | 2      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 39       | 64     | 39.8%   |
| WDC                 | 36       | 78     | 36.73%  |
| Hitachi             | 9        | 23     | 9.18%   |
| Toshiba             | 5        | 6      | 5.1%    |
| IBM                 | 4        | 4      | 4.08%   |
| Samsung Electronics | 2        | 3      | 2.04%   |
| MDT                 | 2        | 2      | 2.04%   |
| HGST                | 1        | 1      | 1.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 90       | 181    | 74.38%  |
| SSD  | 25       | 31     | 20.66%  |
| NVMe | 6        | 8      | 4.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                     | 1        | 1      | 20%     |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1        | 1      | 20%     |
| Seagate ST3500630AS 500GB                        | 1        | 2      | 20%     |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 20%     |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1        | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 40%     |
| WDC                 | 1        | 1      | 20%     |
| Toshiba             | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 417      | 1655   | 70.32%  |
| Malfunc  | 117      | 220    | 19.73%  |
| Detected | 54       | 137    | 9.11%   |
| Failed   | 5        | 7      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 221      | 29.04%  |
| Intel                            | 218      | 28.65%  |
| Samsung Electronics              | 109      | 14.32%  |
| ASMedia Technology               | 42       | 5.52%   |
| Phison Electronics               | 26       | 3.42%   |
| Marvell Technology Group         | 21       | 2.76%   |
| Sandisk                          | 18       | 2.37%   |
| Nvidia                           | 16       | 2.1%    |
| ADATA Technology                 | 16       | 2.1%    |
| Kingston Technology Company      | 13       | 1.71%   |
| JMicron Technology               | 9        | 1.18%   |
| LSI Logic / Symbios Logic        | 6        | 0.79%   |
| Adaptec                          | 6        | 0.79%   |
| Silicon Motion                   | 5        | 0.66%   |
| Micron/Crucial Technology        | 5        | 0.66%   |
| Seagate Technology               | 4        | 0.53%   |
| Broadcom / LSI                   | 4        | 0.53%   |
| Toshiba America Info Systems     | 3        | 0.39%   |
| Silicon Image                    | 3        | 0.39%   |
| Realtek Semiconductor            | 3        | 0.39%   |
| SK Hynix                         | 2        | 0.26%   |
| KIOXIA                           | 2        | 0.26%   |
| 3ware                            | 2        | 0.26%   |
| VIA Technologies                 | 1        | 0.13%   |
| Solid State Storage Technology   | 1        | 0.13%   |
| Silicon Integrated Systems [SiS] | 1        | 0.13%   |
| OCZ Technology Group             | 1        | 0.13%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.13%   |
| Integrated Technology Express    | 1        | 0.13%   |
| Broadcom                         | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 163      | 17.4%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 72       | 7.68%   |
| AMD 400 Series Chipset SATA Controller                                         | 66       | 7.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 42       | 4.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 37       | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 29       | 3.09%   |
| AMD 500 Series Chipset SATA Controller                                         | 22       | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 18       | 1.92%   |
| AMD X370 Series Chipset SATA Controller                                        | 18       | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 16       | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16       | 1.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16       | 1.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 15       | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 15       | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14       | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14       | 1.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 13       | 1.39%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 12       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12       | 1.28%   |
| Phison E12 NVMe Controller                                                     | 11       | 1.17%   |
| Intel SATA Controller [RAID mode]                                              | 11       | 1.17%   |
| AMD 300 Series Chipset SATA Controller                                         | 11       | 1.17%   |
| Phison E16 PCIe4 NVMe Controller                                               | 10       | 1.07%   |
| Kingston Company A2000 NVMe SSD                                                | 9        | 0.96%   |
| Intel SSD 660P Series                                                          | 9        | 0.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8        | 0.85%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 7        | 0.75%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 7        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7        | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7        | 0.75%   |
| Samsung NVMe SSD Controller 980                                                | 6        | 0.64%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 6        | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5        | 0.53%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 5        | 0.53%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5        | 0.53%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5        | 0.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 5        | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4        | 0.43%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 4        | 0.43%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 4        | 0.43%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 4        | 0.43%   |
| Intel Optane SSD 900P Series                                                   | 4        | 0.43%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4        | 0.43%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 4        | 0.43%   |
| Seagate FireCuda 520 SSD                                                       | 3        | 0.32%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3        | 0.32%   |
| Phison E7 NVMe Controller                                                      | 3        | 0.32%   |
| Nvidia MCP61 SATA Controller                                                   | 3        | 0.32%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 3        | 0.32%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3        | 0.32%   |
| JMicron JMB368 IDE controller                                                  | 3        | 0.32%   |
| Intel SSD 600P Series                                                          | 3        | 0.32%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3        | 0.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3        | 0.32%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 0.32%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 0.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3        | 0.32%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 2        | 0.21%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2        | 0.21%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 414      | 57.26%  |
| NVMe | 211      | 29.18%  |
| IDE  | 58       | 8.02%   |
| RAID | 26       | 3.6%    |
| SAS  | 7        | 0.97%   |
| SCSI | 7        | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 236      | 51.3%   |
| Intel                    | 216      | 46.96%  |
| Marvell Semiconductor    | 2        | 0.43%   |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.22%   |
| PowerMac8,1              | 1        | 0.22%   |
| PowerMac3,6              | 1        | 0.22%   |
| PowerMac10,2             | 1        | 0.22%   |
| PowerBook5,5             | 1        | 0.22%   |
| ARM                      | 1        | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 20       | 4.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 16       | 3.44%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 14       | 3.01%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 13       | 2.8%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 12       | 2.58%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 11       | 2.37%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 11       | 2.37%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 2.37%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 10       | 2.15%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 8        | 1.72%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 8        | 1.72%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 1.72%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 1.72%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 6        | 1.29%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.29%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 1.29%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 6        | 1.29%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5        | 1.08%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 1.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 1.08%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 5        | 1.08%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 5        | 1.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.08%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 4        | 0.86%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 4        | 0.86%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.86%   |
| Intel Pentium III (Katmai)                  | 3        | 0.65%   |
| Intel Pentium 4 CPU 3.20GHz                 | 3        | 0.65%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.65%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 3        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.65%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.65%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 0.65%   |
| Intel Atom CPU 330 @ 1.60GHz                | 3        | 0.65%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.65%   |
| AMD FX-8150 Eight-Core Processor            | 3        | 0.65%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.43%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 0.43%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 2        | 0.43%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 2        | 0.43%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.43%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.43%   |
| Intel Core i7 CPU X 980 @ 3.33GHz           | 2        | 0.43%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.43%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 2        | 0.43%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.43%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.43%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 2        | 0.43%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.43%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.43%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 2        | 0.43%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.43%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 2        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 79       | 17.06%  |
| AMD Ryzen 7             | 75       | 16.2%   |
| AMD Ryzen 5             | 62       | 13.39%  |
| Intel Core i5           | 51       | 11.02%  |
| AMD Ryzen 9             | 38       | 8.21%   |
| Intel Xeon              | 20       | 4.32%   |
| AMD FX                  | 19       | 4.1%    |
| Other                   | 14       | 3.02%   |
| Intel Core i9           | 9        | 1.94%   |
| Intel Core 2 Quad       | 9        | 1.94%   |
| AMD Phenom II X4        | 8        | 1.73%   |
| Intel Pentium           | 7        | 1.51%   |
| Intel Celeron           | 7        | 1.51%   |
| Intel Atom              | 7        | 1.51%   |
| Intel Core 2 Duo        | 6        | 1.3%    |
| AMD Ryzen 3             | 6        | 1.3%    |
| Intel Core i3           | 5        | 1.08%   |
| AMD Ryzen Threadripper  | 5        | 1.08%   |
| Intel Pentium 4         | 4        | 0.86%   |
| AMD Sempron             | 4        | 0.86%   |
| Intel Pentium III       | 3        | 0.65%   |
| AMD Ryzen 7 PRO         | 3        | 0.65%   |
| AMD Phenom II X6        | 3        | 0.65%   |
| AMD Athlon II X3        | 3        | 0.65%   |
| AMD Athlon 64 X2        | 3        | 0.65%   |
| Intel Core 2            | 2        | 0.43%   |
| AMD E                   | 2        | 0.43%   |
| AMD A10                 | 2        | 0.43%   |
| Intel Pentium Dual-Core | 1        | 0.22%   |
| ARM Allwinner           | 1        | 0.22%   |
| AMD Turion II Neo       | 1        | 0.22%   |
| AMD Ryzen 5 PRO         | 1        | 0.22%   |
| AMD Phenom              | 1        | 0.22%   |
| AMD Athlon X4           | 1        | 0.22%   |
| AMD Athlon              | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 146      | 31.6%   |
| 8       | 100      | 21.65%  |
| 6       | 98       | 21.21%  |
| 2       | 40       | 8.66%   |
| 12      | 24       | 5.19%   |
| 16      | 22       | 4.76%   |
| 1       | 15       | 3.25%   |
| 3       | 7        | 1.52%   |
| Unknown | 3        | 0.65%   |
| 10      | 2        | 0.43%   |
| 64      | 1        | 0.22%   |
| 24      | 1        | 0.22%   |
| 22      | 1        | 0.22%   |
| 18      | 1        | 0.22%   |
| 14      | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 452      | 98.26%  |
| 2       | 6        | 1.3%    |
| Unknown | 2        | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 326      | 70.56%  |
| 1       | 132      | 28.57%  |
| Unknown | 3        | 0.65%   |
| 4       | 1        | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 447      | 96.96%  |
| 32-bit         | 8        | 1.74%   |
| Unknown        | 6        | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 14.14%  |
| 0x08701021 | 43       | 8.94%   |
| 0x08701013 | 32       | 6.65%   |
| 0x0800820d | 32       | 6.65%   |
| 0x506e3    | 27       | 5.61%   |
| 0x306c3    | 21       | 4.37%   |
| 0x306a9    | 21       | 4.37%   |
| 0x08001138 | 20       | 4.16%   |
| 0x0a201009 | 16       | 3.33%   |
| 0x906e9    | 15       | 3.12%   |
| 0x0a201016 | 13       | 2.7%    |
| 0x1067a    | 11       | 2.29%   |
| 0xa0655    | 9        | 1.87%   |
| 0x906ed    | 8        | 1.66%   |
| 0x906ea    | 8        | 1.66%   |
| 0xa0671    | 6        | 1.25%   |
| 0x306f2    | 6        | 1.25%   |
| 0x906ec    | 5        | 1.04%   |
| 0x206c2    | 5        | 1.04%   |
| 0x206a7    | 5        | 1.04%   |
| 0x06000822 | 5        | 1.04%   |
| 0x50654    | 4        | 0.83%   |
| 0x306e4    | 4        | 0.83%   |
| 0x0810100b | 4        | 0.83%   |
| 0x0800820b | 4        | 0.83%   |
| 0x06000852 | 4        | 0.83%   |
| 0x010000c8 | 4        | 0.83%   |
| 0xa0653    | 3        | 0.62%   |
| 0x673      | 3        | 0.62%   |
| 0x106c2    | 3        | 0.62%   |
| 0x106a5    | 3        | 0.62%   |
| 0x08008206 | 3        | 0.62%   |
| 0x01000086 | 3        | 0.62%   |
| 0xf43      | 2        | 0.42%   |
| 0x6f6      | 2        | 0.42%   |
| 0x506c9    | 2        | 0.42%   |
| 0x406f1    | 2        | 0.42%   |
| 0x406c3    | 2        | 0.42%   |
| 0x08600106 | 2        | 0.42%   |
| 0x08301039 | 2        | 0.42%   |
| 0x08108109 | 2        | 0.42%   |
| 0x08101013 | 2        | 0.42%   |
| 0x08001129 | 2        | 0.42%   |
| 0x0700010f | 2        | 0.42%   |
| 0x0600063e | 2        | 0.42%   |
| 0x010000c6 | 2        | 0.42%   |
| 0x010000bf | 2        | 0.42%   |
| 0x00000000 | 2        | 0.42%   |
| 0xf29      | 1        | 0.21%   |
| 0x90672    | 1        | 0.21%   |
| 0x806ec    | 1        | 0.21%   |
| 0x806e9    | 1        | 0.21%   |
| 0x706a1    | 1        | 0.21%   |
| 0x6fd      | 1        | 0.21%   |
| 0x6fb      | 1        | 0.21%   |
| 0x406d8    | 1        | 0.21%   |
| 0x40671    | 1        | 0.21%   |
| 0x30673    | 1        | 0.21%   |
| 0x206d7    | 1        | 0.21%   |
| 0x20655    | 1        | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 84       | 18.1%   |
| Zen+             | 45       | 9.7%    |
| KabyLake         | 43       | 9.27%   |
| Haswell          | 32       | 6.9%    |
| Zen 3            | 31       | 6.68%   |
| Zen              | 31       | 6.68%   |
| Skylake          | 31       | 6.68%   |
| IvyBridge        | 27       | 5.82%   |
| Piledriver       | 17       | 3.66%   |
| K10              | 15       | 3.23%   |
| Unknown          | 14       | 3.02%   |
| Penryn           | 13       | 2.8%    |
| CometLake        | 12       | 2.59%   |
| SandyBridge      | 9        | 1.94%   |
| Nehalem          | 7        | 1.51%   |
| Westmere         | 6        | 1.29%   |
| Core             | 6        | 1.29%   |
| Silvermont       | 5        | 1.08%   |
| K8 Hammer        | 5        | 1.08%   |
| Bonnell          | 5        | 1.08%   |
| NetBurst         | 4        | 0.86%   |
| Bulldozer        | 4        | 0.86%   |
| P6               | 3        | 0.65%   |
| Icelake          | 3        | 0.65%   |
| Broadwell        | 3        | 0.65%   |
| Jaguar           | 2        | 0.43%   |
| Goldmont         | 2        | 0.43%   |
| Bobcat           | 2        | 0.43%   |
| Steamroller      | 1        | 0.22%   |
| Goldmont plus    | 1        | 0.22%   |
| Alderlake Hybrid | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 202      | 41.22%  |
| AMD                              | 202      | 41.22%  |
| Intel                            | 74       | 15.1%   |
| ASPEED Technology                | 6        | 1.22%   |
| Matrox Electronics Systems       | 5        | 1.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 60       | 11.76%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 25       | 4.9%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 18       | 3.53%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12       | 2.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 2.16%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 11       | 2.16%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 11       | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 2.16%   |
| Intel HD Graphics 530                                                       | 11       | 2.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 1.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 1.57%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 1.57%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 6        | 1.18%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 1.18%   |
| ASPEED Technology ASPEED Graphics Family                                    | 6        | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.18%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 0.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 0.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 0.98%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 5        | 0.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 0.78%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 4        | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 0.78%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 0.78%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.78%   |
| Intel HD Graphics 630                                                       | 4        | 0.78%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 4        | 0.78%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 0.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.78%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.59%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 3        | 0.59%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 3        | 0.59%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 3        | 0.59%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 0.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.59%   |
| Nvidia C79 [ION]                                                            | 3        | 0.59%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 0.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 0.59%   |
| AMD Turks PRO [Radeon HD 7570]                                              | 3        | 0.59%   |
| AMD RS880 [Radeon HD 4290]                                                  | 3        | 0.59%   |
| AMD Renoir                                                                  | 3        | 0.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 0.59%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.59%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 3        | 0.59%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.39%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.39%   |
| Nvidia NV5 [Riva TNT2 Model 64 / Model 64 Pro]                              | 2        | 0.39%   |
| Nvidia GT215 [GeForce GT 240]                                               | 2        | 0.39%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.39%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.39%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x AMD                  | 182      | 38.97%  |
| 1 x Nvidia               | 179      | 38.33%  |
| 1 x Intel                | 58       | 12.42%  |
| AMD + Nvidia             | 10       | 2.14%   |
| Other                    | 7        | 1.5%    |
| Intel + Nvidia           | 6        | 1.28%   |
| 2 x Nvidia               | 5        | 1.07%   |
| 2 x AMD                  | 5        | 1.07%   |
| 1 x ASPEED               | 5        | 1.07%   |
| 1 x Matrox               | 3        | 0.64%   |
| Intel + AMD              | 2        | 0.43%   |
| 1 x SiS                  | 1        | 0.21%   |
| Nvidia + Matrox          | 1        | 0.21%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.21%   |
| AMD + Matrox             | 1        | 0.21%   |
| AMD + ASPEED             | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 291      | 61.65%  |
| Proprietary | 139      | 29.45%  |
| Unknown     | 42       | 8.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 139      | 28.72%  |
| 7.01-8.0   | 109      | 22.52%  |
| 3.01-4.0   | 53       | 10.95%  |
| 1.01-2.0   | 52       | 10.74%  |
| 0.01-0.5   | 38       | 7.85%   |
| 0.51-1.0   | 32       | 6.61%   |
| 5.01-6.0   | 25       | 5.17%   |
| 8.01-16.0  | 23       | 4.75%   |
| 2.01-3.0   | 9        | 1.86%   |
| 16.01-24.0 | 3        | 0.62%   |
| 4.01-5.0   | 1        | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 68       | 13.05%  |
| Samsung Electronics     | 67       | 12.86%  |
| Goldstar                | 57       | 10.94%  |
| Ancor Communications    | 35       | 6.72%   |
| Hewlett-Packard         | 32       | 6.14%   |
| BenQ                    | 32       | 6.14%   |
| AOC                     | 32       | 6.14%   |
| Iiyama                  | 22       | 4.22%   |
| Acer                    | 21       | 4.03%   |
| ViewSonic               | 16       | 3.07%   |
| Philips                 | 16       | 3.07%   |
| ASUSTek Computer        | 15       | 2.88%   |
| Lenovo                  | 13       | 2.5%    |
| LG Electronics          | 8        | 1.54%   |
| MSI                     | 6        | 1.15%   |
| Fujitsu Siemens         | 6        | 1.15%   |
| Eizo                    | 6        | 1.15%   |
| Idek Iiyama             | 5        | 0.96%   |
| Unknown                 | 4        | 0.77%   |
| NEC Computers           | 4        | 0.77%   |
| Apple                   | 4        | 0.77%   |
| Panasonic               | 3        | 0.58%   |
| Gigabyte Technology     | 3        | 0.58%   |
| Envision Peripherals    | 3        | 0.58%   |
| Yamaha                  | 2        | 0.38%   |
| Sony                    | 2        | 0.38%   |
| KTC                     | 2        | 0.38%   |
| HVR                     | 2        | 0.38%   |
| Hitachi                 | 2        | 0.38%   |
| HannStar                | 2        | 0.38%   |
| Chi Mei Optoelectronics | 2        | 0.38%   |
| AUS                     | 2        | 0.38%   |
| Vizio                   | 1        | 0.19%   |
| Vestel Elektronik       | 1        | 0.19%   |
| Valve                   | 1        | 0.19%   |
| Toshiba                 | 1        | 0.19%   |
| Sunplus                 | 1        | 0.19%   |
| SKY                     | 1        | 0.19%   |
| RTK                     | 1        | 0.19%   |
| PNP                     | 1        | 0.19%   |
| PKB                     | 1        | 0.19%   |
| Packard Bell            | 1        | 0.19%   |
| Onkyo                   | 1        | 0.19%   |
| MStar                   | 1        | 0.19%   |
| Mi                      | 1        | 0.19%   |
| Medion                  | 1        | 0.19%   |
| LYC                     | 1        | 0.19%   |
| Lenovo Group Limited    | 1        | 0.19%   |
| Impression              | 1        | 0.19%   |
| HJW                     | 1        | 0.19%   |
| HannStar Display        | 1        | 0.19%   |
| Gateway                 | 1        | 0.19%   |
| FUN                     | 1        | 0.19%   |
| FOR                     | 1        | 0.19%   |
| Chimei Innolux          | 1        | 0.19%   |
| Belinea                 | 1        | 0.19%   |
| BBY                     | 1        | 0.19%   |
| AGO                     | 1        | 0.19%   |
| Unknown                 | 1        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 6        | 1.05%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 6        | 1.05%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 6        | 1.05%   |
| Iiyama PL2473HD IVM6107 1920x1080 520x290mm 23.4-inch                 | 5        | 0.87%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5        | 0.87%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4        | 0.7%    |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 520x320mm 24.0-inch      | 4        | 0.7%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 4        | 0.7%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.52%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 3        | 0.52%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch    | 3        | 0.52%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 3        | 0.52%   |
| BenQ LCD BNQ801E 3840x2160 596x335mm 26.9-inch                        | 3        | 0.52%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 3        | 0.52%   |
| Yamaha HTR-6064 YMH3169 1920x540                                      | 2        | 0.35%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch            | 2        | 0.35%   |
| Sony LCD Monitor TV  *00 3840x2160                                    | 2        | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.35%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch     | 2        | 0.35%   |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch     | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 700x390mm 31.5-inch | 2        | 0.35%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 2        | 0.35%   |
| Samsung Electronics CF791 SAM0DC4 3440x1440 797x333mm 34.0-inch       | 2        | 0.35%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 2        | 0.35%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch    | 2        | 0.35%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 2        | 0.35%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                  | 2        | 0.35%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 2        | 0.35%   |
| MSI Optix AG32CQ MSI1462 2560x1440 698x393mm 31.5-inch                | 2        | 0.35%   |
| MSI MAG274QRF MSI3CA8 2560x1440 597x336mm 27.0-inch                   | 2        | 0.35%   |
| LG Electronics LCD Monitor LG HDR 4K 7680x2160                        | 2        | 0.35%   |
| LG Electronics LCD Monitor LG HDR 4K                                  | 2        | 0.35%   |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                     | 2        | 0.35%   |
| KTC Q2711SH KTC2700 2560x1440 597x336mm 27.0-inch                     | 2        | 0.35%   |
| Iiyama PLX2783H IVM6648 1920x1080 598x336mm 27.0-inch                 | 2        | 0.35%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                 | 2        | 0.35%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                  | 2        | 0.35%   |
| Idek Iiyama LCD Monitor PLE2607WS                                     | 2        | 0.35%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 2        | 0.35%   |
| Hewlett-Packard LA1951 HWP285B 1280x1024 380x300mm 19.1-inch          | 2        | 0.35%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 2        | 0.35%   |
| Goldstar 27MB85Z GSM5A72 2560x1440 597x336mm 27.0-inch                | 2        | 0.35%   |
| Fujitsu Siemens P24W-5 ECO FUS06A7 1920x1200 518x324mm 24.1-inch      | 2        | 0.35%   |
| Dell U3415W DELA0A7 3440x1440 798x335mm 34.1-inch                     | 2        | 0.35%   |
| Dell U2720Q DEL41B3 3840x2160 597x336mm 27.0-inch                     | 2        | 0.35%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                     | 2        | 0.35%   |
| Dell U2713H DELA091 2560x1440 597x336mm 27.0-inch                     | 2        | 0.35%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 2        | 0.35%   |
| Dell U2414H DELA0A2 1920x1080 527x296mm 23.8-inch                     | 2        | 0.35%   |
| Dell U2410 DELF015 1920x1200 520x320mm 24.0-inch                      | 2        | 0.35%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                    | 2        | 0.35%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 2        | 0.35%   |
| Dell LCD Monitor SE2417HG                                             | 2        | 0.35%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 2        | 0.35%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                     | 2        | 0.35%   |
| BenQ G2200W BNQ780E 1680x1050 473x297mm 22.0-inch                     | 2        | 0.35%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                    | 2        | 0.35%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 2        | 0.35%   |
| AOC 2473W1M AOC2473 1920x1080 527x296mm 23.8-inch                     | 2        | 0.35%   |
| AOC 2369 AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 204      | 39.77%  |
| 2560x1440 (QHD)    | 73       | 14.23%  |
| 3840x2160 (4K)     | 57       | 11.11%  |
| 1920x1200 (WUXGA)  | 29       | 5.65%   |
| 1280x1024 (SXGA)   | 26       | 5.07%   |
| 1680x1050 (WSXGA+) | 21       | 4.09%   |
| 3440x1440          | 20       | 3.9%    |
| Unknown            | 16       | 3.12%   |
| 3840x1080          | 10       | 1.95%   |
| 2560x1080          | 10       | 1.95%   |
| 1600x900 (HD+)     | 8        | 1.56%   |
| 1440x900 (WXGA+)   | 8        | 1.56%   |
| 1366x768 (WXGA)    | 7        | 1.36%   |
| 1600x1200          | 4        | 0.78%   |
| 7680x2160          | 2        | 0.39%   |
| 3840x1200          | 2        | 0.39%   |
| 2160x1200          | 2        | 0.39%   |
| 1920x540           | 2        | 0.39%   |
| 1280x960           | 2        | 0.39%   |
| 6400x2160          | 1        | 0.19%   |
| 5120x1600          | 1        | 0.19%   |
| 4880x1080          | 1        | 0.19%   |
| 3926x1440          | 1        | 0.19%   |
| 3640x1080          | 1        | 0.19%   |
| 3600x1200          | 1        | 0.19%   |
| 3600x1080          | 1        | 0.19%   |
| 2048x1152          | 1        | 0.19%   |
| 1400x1050          | 1        | 0.19%   |
| 1280x720 (HD)      | 1        | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 114      | 22.14%  |
| 24      | 87       | 16.89%  |
| 23      | 75       | 14.56%  |
| Unknown | 53       | 10.29%  |
| 21      | 42       | 8.16%   |
| 34      | 24       | 4.66%   |
| 19      | 24       | 4.66%   |
| 17      | 15       | 2.91%   |
| 22      | 14       | 2.72%   |
| 25      | 9        | 1.75%   |
| 20      | 9        | 1.75%   |
| 31      | 8        | 1.55%   |
| 32      | 6        | 1.17%   |
| 84      | 5        | 0.97%   |
| 48      | 5        | 0.97%   |
| 18      | 5        | 0.97%   |
| 49      | 3        | 0.58%   |
| 47      | 2        | 0.39%   |
| 40      | 2        | 0.39%   |
| 15      | 2        | 0.39%   |
| 14      | 2        | 0.39%   |
| 72      | 1        | 0.19%   |
| 54      | 1        | 0.19%   |
| 50      | 1        | 0.19%   |
| 43      | 1        | 0.19%   |
| 33      | 1        | 0.19%   |
| 28      | 1        | 0.19%   |
| 26      | 1        | 0.19%   |
| 12      | 1        | 0.19%   |
| 11      | 1        | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 239      | 49.08%  |
| 401-500     | 77       | 15.81%  |
| Unknown     | 53       | 10.88%  |
| 701-800     | 31       | 6.37%   |
| 601-700     | 27       | 5.54%   |
| 351-400     | 21       | 4.31%   |
| 301-350     | 16       | 3.29%   |
| 1001-1500   | 12       | 2.46%   |
| 1501-2000   | 6        | 1.23%   |
| 801-900     | 2        | 0.41%   |
| 201-300     | 2        | 0.41%   |
| 901-1000    | 1        | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 284      | 61.34%  |
| 16/10   | 66       | 14.25%  |
| Unknown | 48       | 10.37%  |
| 5/4     | 27       | 5.83%   |
| 21/9    | 24       | 5.18%   |
| 32/9    | 8        | 1.73%   |
| 4/3     | 4        | 0.86%   |
| 6/5     | 1        | 0.22%   |
| 3/2     | 1        | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 162      | 32.08%  |
| 301-350        | 114      | 22.57%  |
| Unknown        | 53       | 10.5%   |
| 251-300        | 47       | 9.31%   |
| 151-200        | 44       | 8.71%   |
| 351-500        | 40       | 7.92%   |
| 141-150        | 16       | 3.17%   |
| 501-1000       | 11       | 2.18%   |
| More than 1000 | 10       | 1.98%   |
| 81-90          | 2        | 0.4%    |
| 131-140        | 2        | 0.4%    |
| 101-110        | 2        | 0.4%    |
| 71-80          | 1        | 0.2%    |
| 51-60          | 1        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 252      | 53.39%  |
| 101-120 | 108      | 22.88%  |
| Unknown | 53       | 11.23%  |
| 121-160 | 30       | 6.36%   |
| 161-240 | 20       | 4.24%   |
| 1-50    | 9        | 1.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 306      | 63.35%  |
| 2     | 104      | 21.53%  |
| 0     | 54       | 11.18%  |
| 3     | 14       | 2.9%    |
| 4     | 5        | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 258      | 41.48%  |
| Realtek Semiconductor           | 221      | 35.53%  |
| Qualcomm Atheros                | 32       | 5.14%   |
| Broadcom                        | 31       | 4.98%   |
| Nvidia                          | 13       | 2.09%   |
| Aquantia                        | 11       | 1.77%   |
| Marvell Technology Group        | 7        | 1.13%   |
| ASIX Electronics                | 5        | 0.8%    |
| TP-Link                         | 4        | 0.64%   |
| Apple                           | 4        | 0.64%   |
| Ralink Technology               | 3        | 0.48%   |
| Qualcomm Atheros Communications | 3        | 0.48%   |
| Microsoft                       | 3        | 0.48%   |
| Netchip Technology              | 2        | 0.32%   |
| MediaTek                        | 2        | 0.32%   |
| Huawei Technologies             | 2        | 0.32%   |
| D-Link System                   | 2        | 0.32%   |
| D-Link                          | 2        | 0.32%   |
| 3Com                            | 2        | 0.32%   |
| Texas Instruments               | 1        | 0.16%   |
| Sigma Designs                   | 1        | 0.16%   |
| Realtek                         | 1        | 0.16%   |
| Raspberry Pi                    | 1        | 0.16%   |
| Ralink                          | 1        | 0.16%   |
| QLogic                          | 1        | 0.16%   |
| Pulse-Eight                     | 1        | 0.16%   |
| OpenMoko                        | 1        | 0.16%   |
| Oculus VR                       | 1        | 0.16%   |
| Metrologic Instruments          | 1        | 0.16%   |
| Kyocera                         | 1        | 0.16%   |
| InterBiometrics                 | 1        | 0.16%   |
| DisplayLink                     | 1        | 0.16%   |
| Davicom Semiconductor           | 1        | 0.16%   |
| Atmel                           | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 181      | 24.79%  |
| Intel I211 Gigabit Network Connection                                         | 84       | 11.51%  |
| Intel Wi-Fi 6 AX200                                                           | 43       | 5.89%   |
| Realtek RTL8125 2.5GbE Controller                                             | 29       | 3.97%   |
| Intel Ethernet Connection (2) I219-V                                          | 26       | 3.56%   |
| Intel 82574L Gigabit Network Connection                                       | 18       | 2.47%   |
| Intel Ethernet Controller I225-V                                              | 15       | 2.05%   |
| Intel Ethernet Connection (7) I219-V                                          | 14       | 1.92%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 1.64%   |
| Intel Wireless-AC 9260                                                        | 10       | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 9        | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9        | 1.23%   |
| Intel I210 Gigabit Network Connection                                         | 8        | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                         | 8        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 8        | 1.1%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 8        | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 7        | 0.96%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 7        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 6        | 0.82%   |
| Nvidia MCP77 Ethernet                                                         | 6        | 0.82%   |
| Intel Wireless 8260                                                           | 6        | 0.82%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 4        | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 4        | 0.55%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 4        | 0.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 3        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.41%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 0.41%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 0.41%   |
| Intel Wireless 7260                                                           | 3        | 0.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3        | 0.41%   |
| Intel Ethernet Connection I217-V                                              | 3        | 0.41%   |
| Intel Ethernet Connection (11) I219-V                                         | 3        | 0.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.41%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                            | 3        | 0.41%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 3        | 0.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 2        | 0.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2        | 0.27%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 2        | 0.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 0.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 2        | 0.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.27%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 2        | 0.27%   |
| Nvidia MCP79 Ethernet                                                         | 2        | 0.27%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                | 2        | 0.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 2        | 0.27%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 99       | 56.57%  |
| Qualcomm Atheros                | 23       | 13.14%  |
| Broadcom                        | 20       | 11.43%  |
| Realtek Semiconductor           | 13       | 7.43%   |
| TP-Link                         | 4        | 2.29%   |
| Ralink Technology               | 3        | 1.71%   |
| Qualcomm Atheros Communications | 3        | 1.71%   |
| Microsoft                       | 3        | 1.71%   |
| D-Link                          | 2        | 1.14%   |
| Texas Instruments               | 1        | 0.57%   |
| Realtek                         | 1        | 0.57%   |
| Ralink                          | 1        | 0.57%   |
| MEDIATEK                        | 1        | 0.57%   |
| D-Link System                   | 1        | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 43       | 24.43%  |
| Intel Wireless-AC 9260                                                  | 10       | 5.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9        | 5.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 8        | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7        | 3.98%   |
| Intel Wireless 8260                                                     | 6        | 3.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 5        | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5        | 2.84%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 4        | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4        | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4        | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3        | 1.7%    |
| Qualcomm Atheros AR9271 802.11n                                         | 3        | 1.7%    |
| Intel Wireless 7260                                                     | 3        | 1.7%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3        | 1.7%    |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 3        | 1.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2        | 1.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2        | 1.14%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2        | 1.14%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 1.14%   |
| Intel Wireless 8265 / 8275                                              | 2        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2        | 1.14%   |
| Broadcom Network controller                                             | 2        | 1.14%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 2        | 1.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2        | 1.14%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1        | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1        | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1        | 0.57%   |
| Realtek 802.11ac WLAN Adapter                                           | 1        | 0.57%   |
| Ralink RT3072 Wireless Adapter                                          | 1        | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1        | 0.57%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 0.57%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1        | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 0.57%   |
| Microsoft XBOX ACC                                                      | 1        | 0.57%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 0.57%   |
| Microsoft Wireless XBox Controller Dongle                               | 1        | 0.57%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 1        | 0.57%   |
| Intel Wireless Gigabit 17265                                            | 1        | 0.57%   |
| Intel Wireless 7265                                                     | 1        | 0.57%   |
| Intel Wireless 3165                                                     | 1        | 0.57%   |
| Intel Wireless 3160                                                     | 1        | 0.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 0.57%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072]    | 1        | 0.57%   |
| D-Link DWL-G132 [Atheros AR5523]                                        | 1        | 0.57%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]           | 1        | 0.57%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1        | 0.57%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 1        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 219      | 43.2%   |
| Intel                    | 219      | 43.2%   |
| Nvidia                   | 13       | 2.56%   |
| Qualcomm Atheros         | 11       | 2.17%   |
| Broadcom                 | 11       | 2.17%   |
| Aquantia                 | 11       | 2.17%   |
| Marvell Technology Group | 7        | 1.38%   |
| ASIX Electronics         | 5        | 0.99%   |
| Apple                    | 4        | 0.79%   |
| 3Com                     | 2        | 0.39%   |
| QLogic                   | 1        | 0.2%    |
| MediaTek                 | 1        | 0.2%    |
| DisplayLink              | 1        | 0.2%    |
| Davicom Semiconductor    | 1        | 0.2%    |
| D-Link System            | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 181      | 33.46%  |
| Intel I211 Gigabit Network Connection                                         | 84       | 15.53%  |
| Realtek RTL8125 2.5GbE Controller                                             | 29       | 5.36%   |
| Intel Ethernet Connection (2) I219-V                                          | 26       | 4.81%   |
| Intel 82574L Gigabit Network Connection                                       | 18       | 3.33%   |
| Intel Ethernet Controller I225-V                                              | 15       | 2.77%   |
| Intel Ethernet Connection (7) I219-V                                          | 14       | 2.59%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9        | 1.66%   |
| Intel I210 Gigabit Network Connection                                         | 8        | 1.48%   |
| Intel Ethernet Connection (2) I219-LM                                         | 8        | 1.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 7        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 6        | 1.11%   |
| Nvidia MCP77 Ethernet                                                         | 6        | 1.11%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 1.11%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 0.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 0.74%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 0.74%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 3        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.55%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 3        | 0.55%   |
| Intel Ethernet Connection (11) I219-V                                         | 3        | 0.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.55%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 3        | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 2        | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.37%   |
| Nvidia MCP79 Ethernet                                                         | 2        | 0.37%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 2        | 0.37%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 0.37%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 0.37%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.37%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 2        | 0.37%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.37%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.37%   |
| ASIX AX88772                                                                  | 2        | 0.37%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.37%   |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.37%   |
| Realtek RTL-8029(AS)                                                          | 1        | 0.18%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.18%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.18%   |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.18%   |
| Nvidia MCP67 Ethernet                                                         | 1        | 0.18%   |
| MediaTek B140DL                                                               | 1        | 0.18%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1        | 0.18%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.18%   |
| Intel Ethernet Connection I354                                                | 1        | 0.18%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.18%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.18%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.18%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 452      | 71.86%  |
| WiFi     | 165      | 26.23%  |
| Modem    | 12       | 1.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 405      | 81.16%  |
| WiFi     | 94       | 18.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 261      | 55.65%  |
| 2     | 145      | 30.92%  |
| 3     | 41       | 8.74%   |
| 4     | 8        | 1.71%   |
| 0     | 7        | 1.49%   |
| 5     | 4        | 0.85%   |
| 12    | 1        | 0.21%   |
| 9     | 1        | 0.21%   |
| 6     | 1        | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 427      | 90.66%  |
| Yes  | 44       | 9.34%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 99       | 57.23%  |
| Cambridge Silicon Radio         | 33       | 19.08%  |
| ASUSTek Computer                | 14       | 8.09%   |
| Apple                           | 7        | 4.05%   |
| Realtek Semiconductor           | 6        | 3.47%   |
| Broadcom                        | 6        | 3.47%   |
| Qualcomm Atheros Communications | 2        | 1.16%   |
| HTC (High Tech Computer)        | 2        | 1.16%   |
| Belkin Components               | 2        | 1.16%   |
| MediaTek                        | 1        | 0.58%   |
| Dynex                           | 1        | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 48       | 27.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 33       | 19.08%  |
| Intel Bluetooth wireless interface                                   | 13       | 7.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 10       | 5.78%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 9        | 5.2%    |
| Intel Bluetooth Device                                               | 9        | 5.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8        | 4.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 8        | 4.62%   |
| Realtek Bluetooth Radio                                              | 5        | 2.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 1.73%   |
| Intel AX210 Bluetooth                                                | 2        | 1.16%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.16%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 2        | 1.16%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.16%   |
| ASUS Bluetooth Radio                                                 | 2        | 1.16%   |
| ASUS BCM20702A0                                                      | 2        | 1.16%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.58%   |
| MediaTek Wireless_Device                                             | 1        | 0.58%   |
| Dynex BCM20702A0                                                     | 1        | 0.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                 | 1        | 0.58%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.58%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.58%   |
| Belkin Components Bluetooth Device with trace filter                 | 1        | 0.58%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.58%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.58%   |
| Apple Bluetooth USB Host Controller                                  | 1        | 0.58%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.58%   |
| Apple Bluetooth HCI                                                  | 1        | 0.58%   |
| Apple Bluetooth Device                                               | 1        | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 268      | 33.37%  |
| Nvidia                                          | 184      | 22.91%  |
| Intel                                           | 177      | 22.04%  |
| C-Media Electronics                             | 29       | 3.61%   |
| Logitech                                        | 15       | 1.87%   |
| Creative Labs                                   | 15       | 1.87%   |
| Creative Technology                             | 9        | 1.12%   |
| Texas Instruments                               | 7        | 0.87%   |
| SteelSeries ApS                                 | 6        | 0.75%   |
| Razer USA                                       | 5        | 0.62%   |
| Kingston Technology                             | 5        | 0.62%   |
| GYROCOM C&C                                     | 5        | 0.62%   |
| Focusrite-Novation                              | 5        | 0.62%   |
| Thesycon Systemsoftware & Consulting            | 4        | 0.5%    |
| JMTek                                           | 4        | 0.5%    |
| BEHRINGER International                         | 4        | 0.5%    |
| AudioQuest                                      | 4        | 0.5%    |
| ASUSTek Computer                                | 4        | 0.5%    |
| Sennheiser Communications                       | 3        | 0.37%   |
| RODE Microphones                                | 3        | 0.37%   |
| Plantronics                                     | 3        | 0.37%   |
| GN Netcom                                       | 3        | 0.37%   |
| Blue Microphones                                | 3        | 0.37%   |
| Yamaha                                          | 2        | 0.25%   |
| SAVITECH                                        | 2        | 0.25%   |
| Samson Technologies                             | 2        | 0.25%   |
| Realtek Semiconductor                           | 2        | 0.25%   |
| Microsoft                                       | 2        | 0.25%   |
| Generalplus Technology                          | 2        | 0.25%   |
| FiiO Electronics Technology                     | 2        | 0.25%   |
| Dell                                            | 2        | 0.25%   |
| Corsair                                         | 2        | 0.25%   |
| Valve Software                                  | 1        | 0.12%   |
| Trust                                           | 1        | 0.12%   |
| Syntek                                          | 1        | 0.12%   |
| Sony                                            | 1        | 0.12%   |
| Solid State Logic                               | 1        | 0.12%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.12%   |
| QinHeng Electronics                             | 1        | 0.12%   |
| Nektar                                          | 1        | 0.12%   |
| Native Instruments                              | 1        | 0.12%   |
| Micronas                                        | 1        | 0.12%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.12%   |
| JOUNIVO                                         | 1        | 0.12%   |
| Ensoniq                                         | 1        | 0.12%   |
| Elgato Systems                                  | 1        | 0.12%   |
| Comtrue                                         | 1        | 0.12%   |
| Cirrus Logic                                    | 1        | 0.12%   |
| B & W Group                                     | 1        | 0.12%   |
| Aureal Semiconductor                            | 1        | 0.12%   |
| Astro Gaming                                    | 1        | 0.12%   |
| Antlion Audio                                   | 1        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 102      | 10.45%  |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 64       | 6.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 62       | 6.35%   |
| AMD Navi 10 HDMI Audio                                                            | 29       | 2.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 28       | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 25       | 2.56%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 18       | 1.84%   |
| Nvidia GP106 High Definition Audio Controller                                     | 17       | 1.74%   |
| Nvidia GP104 High Definition Audio Controller                                     | 16       | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                        | 16       | 1.64%   |
| Intel 200 Series PCH HD Audio                                                     | 16       | 1.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14       | 1.43%   |
| AMD Family 17h/19h HD Audio Controller                                            | 14       | 1.43%   |
| Nvidia GM204 High Definition Audio Controller                                     | 13       | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 13       | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 12       | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 12       | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 12       | 1.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 12       | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                                     | 11       | 1.13%   |
| Nvidia GP102 HDMI Audio Controller                                                | 11       | 1.13%   |
| Nvidia GM206 High Definition Audio Controller                                     | 11       | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 10       | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                     | 9        | 0.92%   |
| Nvidia TU104 HD Audio Controller                                                  | 9        | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 9        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 8        | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 0.82%   |
| Nvidia High Definition Audio Controller                                           | 7        | 0.72%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                         | 7        | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 7        | 0.72%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 7        | 0.72%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 6        | 0.61%   |
| Texas Instruments PCM2902 Audio Codec                                             | 5        | 0.51%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 5        | 0.51%   |
| Nvidia GK106 HDMI Audio Controller                                                | 5        | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                                     | 5        | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5        | 0.51%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 5        | 0.51%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 5        | 0.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 0.51%   |
| AMD FCH Azalia Controller                                                         | 5        | 0.51%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 0.51%   |
| Thesycon Systemsoftware & Consulting D10s                                         | 4        | 0.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 0.41%   |
| Nvidia TU102 High Definition Audio Controller                                     | 4        | 0.41%   |
| Nvidia MCP79 High Definition Audio                                                | 4        | 0.41%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 0.41%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 0.41%   |
| GYROCOM C&C Fiio E10                                                              | 4        | 0.41%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 4        | 0.41%   |
| C-Media Electronics USB Audio Device                                              | 4        | 0.41%   |
| C-Media Electronics CM108 Audio Controller                                        | 4        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 98       | 21.12%  |
| Corsair             | 80       | 17.24%  |
| G.Skill             | 77       | 16.59%  |
| Unknown             | 61       | 13.15%  |
| Crucial             | 57       | 12.28%  |
| Samsung Electronics | 20       | 4.31%   |
| SK Hynix            | 14       | 3.02%   |
| Micron Technology   | 12       | 2.59%   |
| Patriot             | 7        | 1.51%   |
| Team                | 6        | 1.29%   |
| GOODRAM             | 4        | 0.86%   |
| A-DATA Technology   | 4        | 0.86%   |
| Transcend           | 3        | 0.65%   |
| Nanya Technology    | 3        | 0.65%   |
| Toshiba             | 2        | 0.43%   |
| Ramaxel Technology  | 2        | 0.43%   |
| AMD                 | 2        | 0.43%   |
| Thermaltake         | 1        | 0.22%   |
| T-FORCE             | 1        | 0.22%   |
| PUSKILL             | 1        | 0.22%   |
| Kllisre             | 1        | 0.22%   |
| Klevv               | 1        | 0.22%   |
| Hewlett-Packard     | 1        | 0.22%   |
| Golden Empire       | 1        | 0.22%   |
| GeIL                | 1        | 0.22%   |
| Exceleram           | 1        | 0.22%   |
| Chun Well           | 1        | 0.22%   |
| Apacer              | 1        | 0.22%   |
| A Force             | 1        | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 10       | 1.99%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 8        | 1.59%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 7        | 1.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 7        | 1.39%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 5        | 0.99%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s         | 5        | 0.99%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s       | 5        | 0.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 5        | 0.99%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 4        | 0.8%    |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 2667MT/s       | 4        | 0.8%    |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s    | 4        | 0.8%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 4        | 0.8%    |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s        | 4        | 0.8%    |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s | 4        | 0.8%    |
| Corsair RAM CMK16GX4M2A2666C16 8192MB DIMM DDR4 3200MT/s  | 4        | 0.8%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 3        | 0.6%    |
| Unknown RAM Module 512MB DIMM SDRAM                       | 3        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 3        | 0.6%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 3        | 0.6%    |
| Kingston RAM 9965745-002.A00G 16384MB DIMM DDR4 3600MT/s  | 3        | 0.6%    |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s    | 3        | 0.6%    |
| G.Skill RAM F4-3200C16-16GTZ 16384MB DIMM DDR4 2933MT/s   | 3        | 0.6%    |
| G.Skill RAM F4-3200C14-8GTZ 8192MB DIMM DDR4 3733MT/s     | 3        | 0.6%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 3        | 0.6%    |
| G.Skill RAM F4-3000C16-16GISB 16384MB DIMM DDR4 3000MT/s  | 3        | 0.6%    |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s      | 3        | 0.6%    |
| Crucial RAM CT4G4DFS8213.C8FAD11 4GB DIMM DDR4 2133MT/s   | 3        | 0.6%    |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s  | 3        | 0.6%    |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s   | 3        | 0.6%    |
| Corsair RAM CMW32GX4M2C3200C16 16384MB DIMM DDR4 3200MT/s | 3        | 0.6%    |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 3        | 0.6%    |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 2        | 0.4%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 2        | 0.4%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 2        | 0.4%    |
| Unknown RAM Module 4096MB DIMM                            | 2        | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 2        | 0.4%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 2        | 0.4%    |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 2        | 0.4%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 2        | 0.4%    |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s      | 2        | 0.4%    |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s                 | 2        | 0.4%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s       | 2        | 0.4%    |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s       | 2        | 0.4%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 2        | 0.4%    |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s        | 2        | 0.4%    |
| Micron RAM 18KSF1G72AZ-1G6P1 8192MB DIMM DDR3 1600MT/s    | 2        | 0.4%    |
| Kingston RAM Module 8192MB DIMM DDR3 1333MT/s             | 2        | 0.4%    |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                 | 2        | 0.4%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s      | 2        | 0.4%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s    | 2        | 0.4%    |
| Kingston RAM KHX2666C16D4/16GX 16384MB DIMM DDR4 2667MT/s | 2        | 0.4%    |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s      | 2        | 0.4%    |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s    | 2        | 0.4%    |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s      | 2        | 0.4%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 0.4%    |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s  | 2        | 0.4%    |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s     | 2        | 0.4%    |
| GOODRAM RAM GR1600D364L11/2G 2GB DIMM DDR3 1333MT/s       | 2        | 0.4%    |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s    | 2        | 0.4%    |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s       | 2        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 277      | 64.27%  |
| DDR3    | 100      | 23.2%   |
| DDR2    | 23       | 5.34%   |
| Unknown | 18       | 4.18%   |
| SDRAM   | 11       | 2.55%   |
| DDR     | 2        | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 420      | 97.67%  |
| SODIMM | 9        | 2.09%   |
| RIMM   | 1        | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 185      | 39.53%  |
| 16384 | 134      | 28.63%  |
| 4096  | 70       | 14.96%  |
| 2048  | 37       | 7.91%   |
| 32768 | 26       | 5.56%   |
| 1024  | 13       | 2.78%   |
| 512   | 3        | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 67       | 14.26%  |
| 3600    | 55       | 11.7%   |
| 1600    | 52       | 11.06%  |
| 2400    | 34       | 7.23%   |
| 1333    | 34       | 7.23%   |
| 2667    | 28       | 5.96%   |
| 2133    | 28       | 5.96%   |
| 3000    | 23       | 4.89%   |
| 800     | 19       | 4.04%   |
| 3733    | 15       | 3.19%   |
| 667     | 15       | 3.19%   |
| 3400    | 12       | 2.55%   |
| 2933    | 9        | 1.91%   |
| Unknown | 9        | 1.91%   |
| 3466    | 8        | 1.7%    |
| 2666    | 7        | 1.49%   |
| 1867    | 6        | 1.28%   |
| 3800    | 5        | 1.06%   |
| 1866    | 5        | 1.06%   |
| 4000    | 4        | 0.85%   |
| 1066    | 4        | 0.85%   |
| 3333    | 3        | 0.64%   |
| 3100    | 3        | 0.64%   |
| 2048    | 3        | 0.64%   |
| 3866    | 2        | 0.43%   |
| 3666    | 2        | 0.43%   |
| 3533    | 2        | 0.43%   |
| 3066    | 2        | 0.43%   |
| 2465    | 2        | 0.43%   |
| 2134    | 2        | 0.43%   |
| 400     | 2        | 0.43%   |
| 3500    | 1        | 0.21%   |
| 3467    | 1        | 0.21%   |
| 3334    | 1        | 0.21%   |
| 2800    | 1        | 0.21%   |
| 2733    | 1        | 0.21%   |
| 2132    | 1        | 0.21%   |
| 2000    | 1        | 0.21%   |
| 1800    | 1        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 6        | 54.55%  |
| Brother Industries    | 2        | 18.18%  |
| Seiko Epson           | 1        | 9.09%   |
| Samsung Electronics   | 1        | 9.09%   |
| Lexmark International | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson WF-3520 Series           | 1        | 9.09%   |
| Samsung C460 Series                  | 1        | 9.09%   |
| Lexmark International Lexmark E352dn | 1        | 9.09%   |
| HP PhotoSmart 130                    | 1        | 9.09%   |
| HP LaserJet M14-M17                  | 1        | 9.09%   |
| HP LaserJet 1020                     | 1        | 9.09%   |
| HP LaserJet 1018                     | 1        | 9.09%   |
| HP LaserJet 1010                     | 1        | 9.09%   |
| HP Deskjet 2050 J510                 | 1        | 9.09%   |
| Brother MFC-L2700DW                  | 1        | 9.09%   |
| Brother MFC-9130CW                   | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 5        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 2        | 40%     |
| Canon CanoScan LiDE 600F      | 1        | 20%     |
| Canon CanoScan LiDE 220       | 1        | 20%     |
| Canon CanoScan LiDE 110       | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 65       | 61.32%  |
| Microdia                      | 8        | 7.55%   |
| Z-Star Microelectronics       | 5        | 4.72%   |
| Samsung Electronics           | 3        | 2.83%   |
| Creative Technology           | 3        | 2.83%   |
| ARC International             | 3        | 2.83%   |
| Sunplus Innovation Technology | 2        | 1.89%   |
| Realtek Semiconductor         | 2        | 1.89%   |
| MacroSilicon                  | 2        | 1.89%   |
| Chicony Electronics           | 2        | 1.89%   |
| Apple                         | 2        | 1.89%   |
| YGTek                         | 1        | 0.94%   |
| webcam                        | 1        | 0.94%   |
| Valve Software                | 1        | 0.94%   |
| SiGma Micro                   | 1        | 0.94%   |
| Razer USA                     | 1        | 0.94%   |
| KYE Systems (Mouse Systems)   | 1        | 0.94%   |
| Generalplus Technology        | 1        | 0.94%   |
| AVerMedia Technologies        | 1        | 0.94%   |
| A4Tech                        | 1        | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                 | 14       | 12.96%  |
| Logitech Webcam C270                        | 13       | 12.04%  |
| Logitech Webcam C310                        | 5        | 4.63%   |
| Logitech C922 Pro Stream Webcam             | 5        | 4.63%   |
| Logitech BRIO                               | 4        | 3.7%    |
| Z-Star Venus USB2.0 Camera                  | 3        | 2.78%   |
| Samsung Galaxy A5 (MTP)                     | 3        | 2.78%   |
| Microdia USB 2.0 Camera                     | 3        | 2.78%   |
| Microdia Camera                             | 3        | 2.78%   |
| Logitech Webcam C925e                       | 3        | 2.78%   |
| Logitech B525 HD Webcam                     | 3        | 2.78%   |
| ARC International Camera                    | 3        | 2.78%   |
| Z-Star Vimicro USB Camera (Altair)          | 2        | 1.85%   |
| Realtek FULL HD 1080P Webcam                | 2        | 1.85%   |
| MacroSilicon MiraBox Capture                | 2        | 1.85%   |
| Logitech Webcam C930e                       | 2        | 1.85%   |
| Logitech Webcam C200                        | 2        | 1.85%   |
| Logitech HD Webcam C615                     | 2        | 1.85%   |
| Logitech HD Webcam C510                     | 2        | 1.85%   |
| Logitech C920 PRO HD Webcam                 | 2        | 1.85%   |
| Apple iPhone 5/5C/5S/6/SE                   | 2        | 1.85%   |
| YGTek Webcam                                | 1        | 0.93%   |
| webcam webcam                               | 1        | 0.93%   |
| Valve Software 3D Camera                    | 1        | 0.93%   |
| Sunplus UHD Capture                         | 1        | 0.93%   |
| Sunplus Full HD webcam                      | 1        | 0.93%   |
| SiGma Micro Micro USB Web Camera            | 1        | 0.93%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 0.93%   |
| Microdia Webcam Vitade AF                   | 1        | 0.93%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 0.93%   |
| Logitech Webcam Pro 9000                    | 1        | 0.93%   |
| Logitech Webcam C300                        | 1        | 0.93%   |
| Logitech Webcam C170                        | 1        | 0.93%   |
| Logitech StreamCam                          | 1        | 0.93%   |
| Logitech QuickCam Pro 9000                  | 1        | 0.93%   |
| Logitech QuickCam Orbit/Sphere AF           | 1        | 0.93%   |
| Logitech QuickCam Notebook Pro              | 1        | 0.93%   |
| Logitech QuickCam Communicate MP/S5500      | 1        | 0.93%   |
| Logitech HD Webcam C910                     | 1        | 0.93%   |
| Logitech C505e HD Webcam                    | 1        | 0.93%   |
| KYE Systems (Mouse Systems) Genius Webcam   | 1        | 0.93%   |
| Generalplus GENERAL WEBCAM                  | 1        | 0.93%   |
| Creative VF0610 Live! Cam Socialize HD      | 1        | 0.93%   |
| Creative Live! Cam Sync 1080p               | 1        | 0.93%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 0.93%   |
| Chicony HP 720p HD Monitor Webcam           | 1        | 0.93%   |
| Chicony Gateway Webcam                      | 1        | 0.93%   |
| AVerMedia USB Device                        | 1        | 0.93%   |
| A4Tech HD 720P PC Camera                    | 1        | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Clay Logic                        | 3        | 50%     |
| VASCO Data Security International | 1        | 16.67%  |
| Gemalto (was Gemplus)             | 1        | 16.67%  |
| Aktiv                             | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Clay Logic Nitrokey Pro                           | 3        | 50%     |
| VASCO Data Security International DIGIPASS 870    | 1        | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 16.67%  |
| Aktiv Rutoken lite                                | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 271      | 54.64%  |
| 1     | 151      | 30.44%  |
| 2     | 50       | 10.08%  |
| 3     | 18       | 3.63%   |
| 4     | 3        | 0.6%    |
| 5     | 2        | 0.4%    |
| 7     | 1        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 81       | 27.18%  |
| Graphics card            | 51       | 17.11%  |
| Sound                    | 34       | 11.41%  |
| Bluetooth                | 29       | 9.73%   |
| Net/wireless             | 25       | 8.39%   |
| Firewire controller      | 17       | 5.7%    |
| Camera                   | 10       | 3.36%   |
| Storage/ide              | 9        | 3.02%   |
| Unassigned class         | 8        | 2.68%   |
| Network                  | 8        | 2.68%   |
| Net/ethernet             | 6        | 2.01%   |
| Storage/raid             | 3        | 1.01%   |
| Chipcard                 | 3        | 1.01%   |
| Tv card                  | 2        | 0.67%   |
| Multimedia controller    | 2        | 0.67%   |
| Modem                    | 2        | 0.67%   |
| Fingerprint reader       | 2        | 0.67%   |
| Card reader              | 2        | 0.67%   |
| Storage/nvme             | 1        | 0.34%   |
| Storage/ata              | 1        | 0.34%   |
| Storage                  | 1        | 0.34%   |
| Dvb card                 | 1        | 0.34%   |

