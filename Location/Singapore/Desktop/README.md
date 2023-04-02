Linux in Singapore - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

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

Total: 146

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron   | 2ADC                        | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| Unknown    | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [c02aa4b9e1](https://linux-hardware.org/?probe=c02aa4b9e1) | Mar 23, 2023 |
| Gigabyte   | X570 AORUS PRO WIFI         | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| HP         | 1589                        | [2fc61ae7b4](https://linux-hardware.org/?probe=2fc61ae7b4) | Mar 09, 2023 |
| Gigabyte   | X670 AORUS ELITE AX         | [63f1f6f5dd](https://linux-hardware.org/?probe=63f1f6f5dd) | Mar 08, 2023 |
| SZMZ       | X99M-G2                     | [e2244668d1](https://linux-hardware.org/?probe=e2244668d1) | Mar 02, 2023 |
| SZMZ       | X99M-G2                     | [4e45d95aa1](https://linux-hardware.org/?probe=4e45d95aa1) | Mar 01, 2023 |
| Novatte    | M20                         | [f3b00d12f2](https://linux-hardware.org/?probe=f3b00d12f2) | Feb 14, 2023 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [de144d5025](https://linux-hardware.org/?probe=de144d5025) | Feb 12, 2023 |
| MSI        | PRO Z690-A WIFI DDR4        | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| Foxconn    | ETON                        | [e7cc1c6b15](https://linux-hardware.org/?probe=e7cc1c6b15) | Feb 07, 2023 |
| HPE        | ProLiant MicroServer Gen... | [9a9b3eed69](https://linux-hardware.org/?probe=9a9b3eed69) | Feb 05, 2023 |
| Foxconn    | 17A0                        | [1a98ed31ed](https://linux-hardware.org/?probe=1a98ed31ed) | Feb 05, 2023 |
| Lenovo     | NOK                         | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| MSI        | MAG B550 TOMAHAWK           | [2e6f75ca07](https://linux-hardware.org/?probe=2e6f75ca07) | Jan 06, 2023 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Gigabyte   | B660M AORUS PRO AX DDR4     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| ASUSTek    | Z87M-PLUS                   | [6dac0c0943](https://linux-hardware.org/?probe=6dac0c0943) | Dec 29, 2022 |
| Gigabyte   | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock     | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| ASUSTek    | A88XM-A                     | [8633f00865](https://linux-hardware.org/?probe=8633f00865) | Dec 26, 2022 |
| ASUSTek    | A88XM-A                     | [802e7982de](https://linux-hardware.org/?probe=802e7982de) | Dec 26, 2022 |
| HP         | 8061                        | [4427032526](https://linux-hardware.org/?probe=4427032526) | Dec 24, 2022 |
| ASRock     | B75 Pro3-M                  | [e24692f75f](https://linux-hardware.org/?probe=e24692f75f) | Dec 24, 2022 |
| ASRock     | B450 Pro4                   | [61f064d35f](https://linux-hardware.org/?probe=61f064d35f) | Dec 22, 2022 |
| ASRock     | B450 Pro4                   | [d387b553bd](https://linux-hardware.org/?probe=d387b553bd) | Dec 22, 2022 |
| Foxconn    | 17A0                        | [58a3486afd](https://linux-hardware.org/?probe=58a3486afd) | Dec 20, 2022 |
| Foxconn    | 17A0                        | [be57227f43](https://linux-hardware.org/?probe=be57227f43) | Dec 17, 2022 |
| Foxconn    | 17A0                        | [b2185eeab5](https://linux-hardware.org/?probe=b2185eeab5) | Dec 16, 2022 |
| Foxconn    | 17A0                        | [4518247b07](https://linux-hardware.org/?probe=4518247b07) | Dec 14, 2022 |
| Foxconn    | 17A0                        | [2f3b2f9fbb](https://linux-hardware.org/?probe=2f3b2f9fbb) | Dec 07, 2022 |
| HP         | 8061                        | [6e4cb7cde8](https://linux-hardware.org/?probe=6e4cb7cde8) | Dec 07, 2022 |
| HP         | 8061                        | [9d30b0126f](https://linux-hardware.org/?probe=9d30b0126f) | Dec 05, 2022 |
| MSI        | MAG B660M MORTAR DDR4       | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Acer       | RS880M05                    | [7adee2fd97](https://linux-hardware.org/?probe=7adee2fd97) | Oct 21, 2022 |
| ASUSTek    | Maximus IV Extreme          | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Gigabyte   | B550M DS3H AC               | [9ec02e49a3](https://linux-hardware.org/?probe=9ec02e49a3) | Oct 13, 2022 |
| Gigabyte   | X99-Ultra Gaming-CF         | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| ASUSTek    | X99-E WS                    | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| HP         | 843B                        | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Gigabyte   | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI        | PRO B660M-A WIFI DDR4       | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Gigabyte   | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| MSI        | Z87-G45 GAMING              | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| ASUSTek    | B85M-E                      | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| ASUSTek    | B85M-E                      | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek    | B85M-E                      | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| Dell       | 06CV2N A00                  | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Dell       | 0NK70N A03                  | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| HP         | 8054                        | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| Dell       | 09M8Y8 A02                  | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Dell       | 06CV2N A00                  | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte   | Z77-D3H                     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASRock     | AB350 Gaming-ITX/ac         | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| Gigabyte   | B550I AORUS PRO AX          | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| ASRock     | B560M Pro4                  | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell       | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Dell       | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI        | Cherry Trail CR             | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell       | 0C96W1 A02                  | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock     | B450M Steel Legend          | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| MSI        | MPG Z690 CARBON WIFI        | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI        | MPG Z690 CARBON WIFI        | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte   | B365M GAMING HD             | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Dell       | 0XCR8D A03                  | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek    | Z170-A                      | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| MSI        | B450 TOMAHAWK               | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI        | A320M-A PRO MAX             | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI        | A320M-A PRO MAX             | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock     | Z77 Extreme3                | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| Lenovo     | 1046 SDK0T08861 WIN 3305... | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo     | NOK                         | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Biostar    | TB250-BTC+                  | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell       | 0NKW6Y A00                  | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell       | 0NKW6Y A00                  | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| ASUSTek    | M5A78L-M LX V2              | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI        | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| LattePanda | Alpha                       | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda | Alpha                       | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| HP         | 198E                        | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Gigabyte   | H81M-DS2                    | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| ASUSTek    | M5A78L-M LX V2              | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock     | HM55-MXM                    | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo     | ThinkCentre M90p 5864BM3    | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell       | 0D6H9T A00                  | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo     | SHARKBAY NOK                | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Dell       | 00V62H A01                  | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell       | 0D02VH A01                  | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Dell       | 0D441T A03                  | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek    | E3M-ET V5 SERIES            | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek    | E3M-ET V5 SERIES            | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| ASUSTek    | M4A78-EM-1394               | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock     | H110M-HDS R3.0              | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| ASRock     | 990FX Killer                | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| MSI        | X370 GAMING PRO CARBON      | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| ASUSTek    | M3A78-EM                    | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| ASUSTek    | Z97M-PLUS                   | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Gigabyte   | 945GZM-S2                   | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Gigabyte   | 945GZM-S2                   | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| ASUSTek    | P8H77-V LE                  | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| ASRock     | HM55-MXM                    | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| Gigabyte   | G1.Sniper A88X-CF           | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| ECS        | H61H2-MV                    | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| ASUSTek    | P8H77-V LE                  | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| ASUSTek    | H87I-PLUS                   | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| ASRock     | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock     | H110M-HDS R3.0              | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| ASUSTek    | H87I-PLUS                   | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| ASUSTek    | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek    | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock     | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek    | Berkeley                    | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek    | Berkeley                    | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| ASUSTek    | PRIME H310M-A               | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Dell       | 06D7TR A00                  | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek    | ROG CROSSHAIR VII HERO      | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Dell       | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell       | 00V62H A01                  | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell       | 00V62H A01                  | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Gigabyte   | Z270X-UD5-CF                | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer       | Aspire X3950                | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASRock     | Z370 Pro4                   | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo     | 30C0 SDK0J40697 WIN 3305... | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| Gigabyte   | X570 AORUS PRO WIFI         | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte   | X570 AORUS PRO WIFI         | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell       | 0F3KHR A00                  | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| ASUSTek    | P8H67-M PRO                 | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| ASUSTek    | ET2020I                     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| MSI        | X299 RAIDER                 | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI        | X299 RAIDER                 | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI        | Boston                      | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 21       | 18.26%  |
| Ubuntu 18.04                 | 15       | 13.04%  |
| Ubuntu 22.04                 | 6        | 5.22%   |
| Linux Mint 21                | 5        | 4.35%   |
| KDE neon 20.04               | 4        | 3.48%   |
| Arch Rolling                 | 4        | 3.48%   |
| Pop!_OS 20.04                | 3        | 2.61%   |
| Manjaro                      | 3        | 2.61%   |
| Debian 11                    | 3        | 2.61%   |
| Ubuntu 21.04                 | 2        | 1.74%   |
| Rocky Linux 8.5              | 2        | 1.74%   |
| Pop!_OS 21.04                | 2        | 1.74%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.74%   |
| OpenMandriva 4.50            | 2        | 1.74%   |
| OpenMandriva 4.3             | 2        | 1.74%   |
| Linux Mint 20.3              | 2        | 1.74%   |
| Linux Mint 20                | 2        | 1.74%   |
| Fedora 37                    | 2        | 1.74%   |
| Fedora 33                    | 2        | 1.74%   |
| Arch                         | 2        | 1.74%   |
| Xubuntu 20.04                | 1        | 0.87%   |
| Ubuntu Unity 20.04           | 1        | 0.87%   |
| Ubuntu Unity 16.04           | 1        | 0.87%   |
| Ubuntu MATE 20.04            | 1        | 0.87%   |
| Ubuntu 22.10                 | 1        | 0.87%   |
| Ubuntu 19.10                 | 1        | 0.87%   |
| Ubuntu 19.04                 | 1        | 0.87%   |
| Ubuntu 18.10                 | 1        | 0.87%   |
| Rocky Linux 8.7              | 1        | 0.87%   |
| Rocky Linux 8.4              | 1        | 0.87%   |
| Pop!_OS 21.10                | 1        | 0.87%   |
| OpenMandriva 4.2             | 1        | 0.87%   |
| OpenMandriva 23.03           | 1        | 0.87%   |
| OpenMandriva 23.01           | 1        | 0.87%   |
| OpenMandriva 22.11           | 1        | 0.87%   |
| MX 21                        | 1        | 0.87%   |
| Manjaro 20.2                 | 1        | 0.87%   |
| Lubuntu 20.04                | 1        | 0.87%   |
| Linux Mint 21.1              | 1        | 0.87%   |
| Linux Mint 19.3              | 1        | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 47       | 42.34%  |
| Linux Mint   | 9        | 8.11%   |
| OpenMandriva | 8        | 7.21%   |
| Pop!_OS      | 6        | 5.41%   |
| Fedora       | 6        | 5.41%   |
| Arch         | 6        | 5.41%   |
| Debian       | 5        | 4.5%    |
| Manjaro      | 4        | 3.6%    |
| KDE neon     | 4        | 3.6%    |
| Rocky Linux  | 3        | 2.7%    |
| Ubuntu Unity | 2        | 1.8%    |
| openSUSE     | 2        | 1.8%    |
| Xubuntu      | 1        | 0.9%    |
| Ubuntu MATE  | 1        | 0.9%    |
| MX           | 1        | 0.9%    |
| Lubuntu      | 1        | 0.9%    |
| Gentoo       | 1        | 0.9%    |
| EndeavourOS  | 1        | 0.9%    |
| CentOS       | 1        | 0.9%    |
| Atz          | 1        | 0.9%    |
| ArcoLinux    | 1        | 0.9%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.0-56-generic            | 7        | 5.69%   |
| 5.15.0-46-generic            | 4        | 3.25%   |
| 5.4.0-29-generic             | 3        | 2.44%   |
| 6.0.15-300.fc37.x86_64       | 2        | 1.63%   |
| 5.9.8-200.fc33.x86_64        | 2        | 1.63%   |
| 5.4.0-7642-generic           | 2        | 1.63%   |
| 5.4.0-70-generic             | 2        | 1.63%   |
| 5.4.0-42-generic             | 2        | 1.63%   |
| 5.4.0-40-generic             | 2        | 1.63%   |
| 5.4.0-37-generic             | 2        | 1.63%   |
| 5.3.0-51-generic             | 2        | 1.63%   |
| 5.19.0-35-generic            | 2        | 1.63%   |
| 5.16.7-desktop-1omv4003      | 2        | 1.63%   |
| 5.15.0-58-generic            | 2        | 1.63%   |
| 5.15.0-52-generic            | 2        | 1.63%   |
| 5.12.7-desktop-1omv4003      | 2        | 1.63%   |
| 5.11.0-27-generic            | 2        | 1.63%   |
| 5.0.0-36-generic             | 2        | 1.63%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2        | 1.63%   |
| 6.2.6-desktop-1omv2390       | 1        | 0.81%   |
| 6.2.2-arch1-1                | 1        | 0.81%   |
| 6.1.6-1.el8.elrepo.x86_64    | 1        | 0.81%   |
| 6.1.4-desktop-1omv2301       | 1        | 0.81%   |
| 6.1.1-1-default              | 1        | 0.81%   |
| 6.1.0-3-amd64                | 1        | 0.81%   |
| 6.0.2-desktop-1omv4050       | 1        | 0.81%   |
| 6.0.0-6-amd64                | 1        | 0.81%   |
| 5.9.11-3-MANJARO             | 1        | 0.81%   |
| 5.8.18-1-MANJARO             | 1        | 0.81%   |
| 5.8.0-53-generic             | 1        | 0.81%   |
| 5.8.0-48-generic             | 1        | 0.81%   |
| 5.8.0-31-generic             | 1        | 0.81%   |
| 5.4.0-96-generic             | 1        | 0.81%   |
| 5.4.0-81-generic             | 1        | 0.81%   |
| 5.4.0-7634-generic           | 1        | 0.81%   |
| 5.4.0-7629-generic           | 1        | 0.81%   |
| 5.4.0-66-generic             | 1        | 0.81%   |
| 5.4.0-65-generic             | 1        | 0.81%   |
| 5.4.0-53-generic             | 1        | 0.81%   |
| 5.4.0-52-generic             | 1        | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 24       | 20.34%  |
| 5.15.0  | 18       | 15.25%  |
| 5.0.0   | 7        | 5.93%   |
| 5.11.0  | 6        | 5.08%   |
| 4.18.0  | 5        | 4.24%   |
| 5.10.0  | 4        | 3.39%   |
| 4.15.0  | 4        | 3.39%   |
| 5.8.0   | 3        | 2.54%   |
| 5.3.0   | 3        | 2.54%   |
| 5.19.0  | 3        | 2.54%   |
| 6.0.15  | 2        | 1.69%   |
| 5.9.8   | 2        | 1.69%   |
| 5.16.7  | 2        | 1.69%   |
| 5.13.0  | 2        | 1.69%   |
| 5.12.7  | 2        | 1.69%   |
| 6.2.6   | 1        | 0.85%   |
| 6.2.2   | 1        | 0.85%   |
| 6.1.6   | 1        | 0.85%   |
| 6.1.4   | 1        | 0.85%   |
| 6.1.1   | 1        | 0.85%   |
| 6.1.0   | 1        | 0.85%   |
| 6.0.2   | 1        | 0.85%   |
| 6.0.0   | 1        | 0.85%   |
| 5.9.11  | 1        | 0.85%   |
| 5.8.18  | 1        | 0.85%   |
| 5.18.2  | 1        | 0.85%   |
| 5.17.5  | 1        | 0.85%   |
| 5.16.18 | 1        | 0.85%   |
| 5.16.11 | 1        | 0.85%   |
| 5.15.8  | 1        | 0.85%   |
| 5.15.74 | 1        | 0.85%   |
| 5.15.7  | 1        | 0.85%   |
| 5.15.6  | 1        | 0.85%   |
| 5.15.53 | 1        | 0.85%   |
| 5.15.13 | 1        | 0.85%   |
| 5.15.10 | 1        | 0.85%   |
| 5.14.18 | 1        | 0.85%   |
| 5.14.16 | 1        | 0.85%   |
| 5.13.13 | 1        | 0.85%   |
| 5.13.12 | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 25       | 21.19%  |
| 5.4     | 24       | 20.34%  |
| 5.11    | 7        | 5.93%   |
| 5.0     | 7        | 5.93%   |
| 5.10    | 6        | 5.08%   |
| 4.18    | 5        | 4.24%   |
| 6.1     | 4        | 3.39%   |
| 6.0     | 4        | 3.39%   |
| 5.8     | 4        | 3.39%   |
| 5.16    | 4        | 3.39%   |
| 5.13    | 4        | 3.39%   |
| 4.15    | 4        | 3.39%   |
| 5.9     | 3        | 2.54%   |
| 5.3     | 3        | 2.54%   |
| 5.19    | 3        | 2.54%   |
| 5.12    | 3        | 2.54%   |
| 6.2     | 2        | 1.69%   |
| 5.14    | 2        | 1.69%   |
| 5.18    | 1        | 0.85%   |
| 5.17    | 1        | 0.85%   |
| 4.16    | 1        | 0.85%   |
| 3.10    | 1        | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 110      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 51       | 45.54%  |
| Unknown       | 19       | 16.96%  |
| KDE5          | 16       | 14.29%  |
| X-Cinnamon    | 11       | 9.82%   |
| XFCE          | 4        | 3.57%   |
| Unity         | 2        | 1.79%   |
| LXQt          | 2        | 1.79%   |
| i3            | 2        | 1.79%   |
| MATE          | 1        | 0.89%   |
| KDE           | 1        | 0.89%   |
| GNOME Classic | 1        | 0.89%   |
| Cinnamon      | 1        | 0.89%   |
| Budgie        | 1        | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 88       | 78.57%  |
| Wayland | 10       | 8.93%   |
| Unknown | 8        | 7.14%   |
| Tty     | 6        | 5.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 53.64%  |
| GDM     | 17       | 15.45%  |
| SDDM    | 13       | 11.82%  |
| GDM3    | 11       | 10%     |
| LightDM | 9        | 8.18%   |
| TDM     | 1        | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_SG   | 47       | 42.34%  |
| en_US   | 41       | 36.94%  |
| Unknown | 9        | 8.11%   |
| en_AU   | 3        | 2.7%    |
| zh_CN   | 2        | 1.8%    |
| en_GB   | 2        | 1.8%    |
| de_DE   | 2        | 1.8%    |
| C       | 2        | 1.8%    |
| fr_FR   | 1        | 0.9%    |
| en_PH   | 1        | 0.9%    |
| en_IN   | 1        | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 61       | 55.45%  |
| BIOS | 49       | 44.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 83       | 74.77%  |
| Btrfs   | 11       | 9.91%   |
| Xfs     | 8        | 7.21%   |
| Overlay | 6        | 5.41%   |
| Unknown | 3        | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 47.27%  |
| GPT     | 48       | 43.64%  |
| MBR     | 10       | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 79.28%  |
| Yes       | 23       | 20.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 64.55%  |
| Yes       | 39       | 35.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 24       | 21.82%  |
| Gigabyte Technology | 19       | 17.27%  |
| MSI                 | 15       | 13.64%  |
| Dell                | 15       | 13.64%  |
| ASRock              | 12       | 10.91%  |
| Lenovo              | 5        | 4.55%   |
| Hewlett-Packard     | 5        | 4.55%   |
| Foxconn             | 4        | 3.64%   |
| Acer                | 2        | 1.82%   |
| SZMZ                | 1        | 0.91%   |
| Pegatron            | 1        | 0.91%   |
| Novatte             | 1        | 0.91%   |
| LattePanda          | 1        | 0.91%   |
| HPE                 | 1        | 0.91%   |
| ECS                 | 1        | 0.91%   |
| Biostar             | 1        | 0.91%   |
| AMI                 | 1        | 0.91%   |
| Unknown             | 1        | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 5        | 4.55%   |
| Gigabyte X570 AORUS PRO WIFI        | 4        | 3.64%   |
| MSI MS-7C84                         | 3        | 2.73%   |
| Foxconn Pro 3330 MT                 | 3        | 2.73%   |
| Gigabyte B550I AORUS PRO AX         | 2        | 1.82%   |
| Dell OptiPlex 990                   | 2        | 1.82%   |
| Dell OptiPlex 9020                  | 2        | 1.82%   |
| ASUS ROG STRIX B550-I GAMING        | 2        | 1.82%   |
| SZMZ X99M-H2                        | 1        | 0.91%   |
| Pegatron 23-d018d                   | 1        | 0.91%   |
| Novatte M20                         | 1        | 0.91%   |
| MSI MS-7D43                         | 1        | 0.91%   |
| MSI MS-7D42                         | 1        | 0.91%   |
| MSI MS-7D30                         | 1        | 0.91%   |
| MSI MS-7D25                         | 1        | 0.91%   |
| MSI MS-7C91                         | 1        | 0.91%   |
| MSI MS-7C52                         | 1        | 0.91%   |
| MSI MS-7C02                         | 1        | 0.91%   |
| MSI MS-7A94                         | 1        | 0.91%   |
| MSI MS-7A32                         | 1        | 0.91%   |
| MSI MS-7821                         | 1        | 0.91%   |
| MSI MS-7721                         | 1        | 0.91%   |
| MSI KT308AA-AB4 SR5472CF            | 1        | 0.91%   |
| Lenovo ThinkStation P620 30E1S3VH00 | 1        | 0.91%   |
| Lenovo ThinkStation P310 30ASS2WG00 | 1        | 0.91%   |
| Lenovo ThinkCentre M90p 5864BM3     | 1        | 0.91%   |
| Lenovo ThinkCentre M73 10AXS26C00   | 1        | 0.91%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 0.91%   |
| LattePanda Alpha                    | 1        | 0.91%   |
| HPE ProLiant MicroServer Gen10      | 1        | 0.91%   |
| HP Z420 Workstation                 | 1        | 0.91%   |
| HP ProDesk 400 G3 MT                | 1        | 0.91%   |
| HP ProDesk 400 G2 MT                | 1        | 0.91%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.91%   |
| HP EliteDesk 800 G2 SFF             | 1        | 0.91%   |
| Gigabyte Z77-D3H                    | 1        | 0.91%   |
| Gigabyte Z270X-UD5                  | 1        | 0.91%   |
| Gigabyte X99-Ultra Gaming-CF        | 1        | 0.91%   |
| Gigabyte X670 AORUS ELITE AX        | 1        | 0.91%   |
| Gigabyte H87N-WIFI                  | 1        | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 9        | 8.18%   |
| ASUS ROG            | 5        | 4.55%   |
| ASUS All            | 5        | 4.55%   |
| Gigabyte X570       | 4        | 3.64%   |
| MSI MS-7C84         | 3        | 2.73%   |
| Lenovo ThinkCentre  | 3        | 2.73%   |
| Foxconn Pro         | 3        | 2.73%   |
| Dell Precision      | 3        | 2.73%   |
| Lenovo ThinkStation | 2        | 1.82%   |
| HP ProDesk          | 2        | 1.82%   |
| Gigabyte B550I      | 2        | 1.82%   |
| Gigabyte B365M      | 2        | 1.82%   |
| SZMZ X99M-H2        | 1        | 0.91%   |
| Pegatron 23-d018d   | 1        | 0.91%   |
| Novatte M20         | 1        | 0.91%   |
| MSI MS-7D43         | 1        | 0.91%   |
| MSI MS-7D42         | 1        | 0.91%   |
| MSI MS-7D30         | 1        | 0.91%   |
| MSI MS-7D25         | 1        | 0.91%   |
| MSI MS-7C91         | 1        | 0.91%   |
| MSI MS-7C52         | 1        | 0.91%   |
| MSI MS-7C02         | 1        | 0.91%   |
| MSI MS-7A94         | 1        | 0.91%   |
| MSI MS-7A32         | 1        | 0.91%   |
| MSI MS-7821         | 1        | 0.91%   |
| MSI MS-7721         | 1        | 0.91%   |
| MSI KT308AA-AB4     | 1        | 0.91%   |
| LattePanda Alpha    | 1        | 0.91%   |
| HPE ProLiant        | 1        | 0.91%   |
| HP Z420             | 1        | 0.91%   |
| HP Pavilion         | 1        | 0.91%   |
| HP EliteDesk        | 1        | 0.91%   |
| Gigabyte Z77-D3H    | 1        | 0.91%   |
| Gigabyte Z270X-UD5  | 1        | 0.91%   |
| Gigabyte X99-Ultra  | 1        | 0.91%   |
| Gigabyte X670       | 1        | 0.91%   |
| Gigabyte H87N-WIFI  | 1        | 0.91%   |
| Gigabyte H81M-DS2   | 1        | 0.91%   |
| Gigabyte H61M-S2PH  | 1        | 0.91%   |
| Gigabyte G1.Sniper  | 1        | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 16       | 14.55%  |
| 2020 | 14       | 12.73%  |
| 2018 | 12       | 10.91%  |
| 2019 | 10       | 9.09%   |
| 2012 | 10       | 9.09%   |
| 2021 | 8        | 7.27%   |
| 2016 | 7        | 6.36%   |
| 2014 | 6        | 5.45%   |
| 2011 | 6        | 5.45%   |
| 2017 | 5        | 4.55%   |
| 2015 | 5        | 4.55%   |
| 2010 | 5        | 4.55%   |
| 2008 | 2        | 1.82%   |
| 2007 | 2        | 1.82%   |
| 2022 | 1        | 0.91%   |
| 2009 | 1        | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 110      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 108      | 98.18%  |
| Enabled  | 2        | 1.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 110      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 23       | 20.91%  |
| 32.01-64.0      | 22       | 20%     |
| 8.01-16.0       | 21       | 19.09%  |
| 4.01-8.0        | 18       | 16.36%  |
| 64.01-256.0     | 10       | 9.09%   |
| 3.01-4.0        | 8        | 7.27%   |
| 24.01-32.0      | 5        | 4.55%   |
| 1.01-2.0        | 2        | 1.82%   |
| More than 256.0 | 1        | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 35       | 30.43%  |
| 2.01-3.0   | 27       | 23.48%  |
| 3.01-4.0   | 22       | 19.13%  |
| 4.01-8.0   | 16       | 13.91%  |
| 8.01-16.0  | 8        | 6.96%   |
| 0.51-1.0   | 5        | 4.35%   |
| 16.01-24.0 | 1        | 0.87%   |
| 0.01-0.5   | 1        | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 34.82%  |
| 2      | 30       | 26.79%  |
| 3      | 22       | 19.64%  |
| 4      | 14       | 12.5%   |
| 5      | 5        | 4.46%   |
| 0      | 2        | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 62.73%  |
| Yes       | 41       | 37.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 110      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 57       | 50.89%  |
| No        | 55       | 49.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 66.36%  |
| Yes       | 37       | 33.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 110      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 101      | 91.82%  |
| Kampong Pasir Ris | 5        | 4.55%   |
| Jurong West       | 3        | 2.73%   |
| Queenstown Estate | 1        | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 37       | 56     | 18.14%  |
| WDC                         | 33       | 52     | 16.18%  |
| Seagate                     | 32       | 40     | 15.69%  |
| Toshiba                     | 17       | 21     | 8.33%   |
| SanDisk                     | 13       | 14     | 6.37%   |
| Crucial                     | 8        | 9      | 3.92%   |
| Kingston                    | 7        | 9      | 3.43%   |
| Hitachi                     | 7        | 8      | 3.43%   |
| Unknown                     | 3        | 3      | 1.47%   |
| JMicron Technology          | 3        | 4      | 1.47%   |
| HGST                        | 3        | 5      | 1.47%   |
| A-DATA Technology           | 3        | 3      | 1.47%   |
| SK hynix                    | 2        | 2      | 0.98%   |
| Plextor                     | 2        | 2      | 0.98%   |
| Phison Electronics          | 2        | 2      | 0.98%   |
| Phison                      | 2        | 2      | 0.98%   |
| Micron/Crucial Technology   | 2        | 2      | 0.98%   |
| Maxtor                      | 2        | 2      | 0.98%   |
| Lexar                       | 2        | 2      | 0.98%   |
| KLEVV                       | 2        | 2      | 0.98%   |
| Intel                       | 2        | 2      | 0.98%   |
| Hewlett-Packard             | 2        | 2      | 0.98%   |
| Vaseky                      | 1        | 1      | 0.49%   |
| USB30                       | 1        | 1      | 0.49%   |
| Transcend                   | 1        | 1      | 0.49%   |
| Teclast                     | 1        | 1      | 0.49%   |
| Silicon Motion              | 1        | 2      | 0.49%   |
| Pioneer                     | 1        | 1      | 0.49%   |
| OCZ                         | 1        | 1      | 0.49%   |
| Mushkin                     | 1        | 1      | 0.49%   |
| MARVELL                     | 1        | 1      | 0.49%   |
| LITEONIT                    | 1        | 1      | 0.49%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.49%   |
| Kingston Technology Company | 1        | 1      | 0.49%   |
| Kingmax                     | 1        | 1      | 0.49%   |
| KINGBANK                    | 1        | 1      | 0.49%   |
| GAMER                       | 1        | 1      | 0.49%   |
| Drevo                       | 1        | 1      | 0.49%   |
| China                       | 1        | 1      | 0.49%   |
| Apacer                      | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                              | 6        | 2.54%   |
| Toshiba DT01ACA200 2TB                              | 5        | 2.12%   |
| Samsung SSD 850 EVO 250GB                           | 5        | 2.12%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 1.69%   |
| SanDisk NVMe SSD Drive 500GB                        | 4        | 1.69%   |
| Samsung SSD 860 EVO 500GB                           | 4        | 1.69%   |
| WDC WD6400AAKS-22A7B2 640GB                         | 3        | 1.27%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3        | 1.27%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 1.27%   |
| JMicron Generic 500GB                               | 3        | 1.27%   |
| Crucial CT500MX500SSD1 500GB                        | 3        | 1.27%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2        | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 0.85%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 2        | 0.85%   |
| SK hynix SC311 SATA 128GB SSD                       | 2        | 0.85%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.85%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.85%   |
| Seagate Expansion HDD 2TB                           | 2        | 0.85%   |
| Seagate BUP Portable 5TB                            | 2        | 0.85%   |
| SanDisk SSD PLUS 1000GB                             | 2        | 0.85%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 0.85%   |
| Samsung SSD 980 500GB                               | 2        | 0.85%   |
| Samsung SSD 960 EVO 250GB                           | 2        | 0.85%   |
| Samsung NVMe SSD Drive 500GB                        | 2        | 0.85%   |
| Samsung NVMe SSD Drive 1024GB                       | 2        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 0.85%   |
| Samsung HN-M750MBB 752GB                            | 2        | 0.85%   |
| Plextor PX-128M6S 128GB SSD                         | 2        | 0.85%   |
| Maxtor 6V250F0 256GB                                | 2        | 0.85%   |
| A-DATA HC660 1TB SSD                                | 2        | 0.85%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1        | 0.42%   |
| WDC WDS500G1X0E-00AFY0 500GB                        | 1        | 0.42%   |
| WDC WDS200T2B0C-00PXH0 2TB                          | 1        | 0.42%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1        | 0.42%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 1        | 0.42%   |
| WDC WD800JD-08MSA1 80GB                             | 1        | 0.42%   |
| WDC WD6002FFWX-68TZ4N0 6TB                          | 1        | 0.42%   |
| WDC WD5000AZLX-08K2TA0 500GB                        | 1        | 0.42%   |
| WDC WD5000AVDS-73U7B1 500GB                         | 1        | 0.42%   |
| WDC WD5000AUDX-63WNHY0 500GB                        | 1        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 39     | 34.44%  |
| WDC                 | 29       | 46     | 32.22%  |
| Toshiba             | 15       | 19     | 16.67%  |
| Hitachi             | 7        | 8      | 7.78%   |
| HGST                | 3        | 5      | 3.33%   |
| Samsung Electronics | 2        | 2      | 2.22%   |
| Maxtor              | 2        | 2      | 2.22%   |
| MARVELL             | 1        | 1      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 31     | 32.88%  |
| SanDisk             | 8        | 8      | 10.96%  |
| Kingston            | 6        | 8      | 8.22%   |
| Crucial             | 6        | 7      | 8.22%   |
| JMicron Technology  | 3        | 4      | 4.11%   |
| WDC                 | 2        | 2      | 2.74%   |
| SK hynix            | 2        | 2      | 2.74%   |
| Plextor             | 2        | 2      | 2.74%   |
| Hewlett-Packard     | 2        | 2      | 2.74%   |
| A-DATA Technology   | 2        | 2      | 2.74%   |
| Vaseky              | 1        | 1      | 1.37%   |
| USB30               | 1        | 1      | 1.37%   |
| Unknown             | 1        | 1      | 1.37%   |
| Transcend           | 1        | 1      | 1.37%   |
| Teclast             | 1        | 1      | 1.37%   |
| Pioneer             | 1        | 1      | 1.37%   |
| OCZ                 | 1        | 1      | 1.37%   |
| LITEONIT            | 1        | 1      | 1.37%   |
| Lexar               | 1        | 1      | 1.37%   |
| KLEVV               | 1        | 1      | 1.37%   |
| Kingmax             | 1        | 1      | 1.37%   |
| KINGBANK            | 1        | 1      | 1.37%   |
| Intel               | 1        | 1      | 1.37%   |
| GAMER               | 1        | 1      | 1.37%   |
| China               | 1        | 1      | 1.37%   |
| Apacer              | 1        | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 74       | 122    | 43.27%  |
| SSD     | 56       | 84     | 32.75%  |
| NVMe    | 37       | 53     | 21.64%  |
| MMC     | 2        | 2      | 1.17%   |
| Unknown | 2        | 2      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 95       | 195    | 65.07%  |
| NVMe | 37       | 53     | 25.34%  |
| SAS  | 12       | 13     | 8.22%   |
| MMC  | 2        | 2      | 1.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 63       | 93     | 43.45%  |
| 0.51-1.0   | 41       | 60     | 28.28%  |
| 1.01-2.0   | 20       | 27     | 13.79%  |
| 4.01-10.0  | 9        | 11     | 6.21%   |
| 3.01-4.0   | 7        | 10     | 4.83%   |
| 2.01-3.0   | 4        | 4      | 2.76%   |
| 10.01-20.0 | 1        | 1      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 24       | 20.87%  |
| 101-250        | 22       | 19.13%  |
| More than 3000 | 14       | 12.17%  |
| 251-500        | 13       | 11.3%   |
| 1001-2000      | 13       | 11.3%   |
| 2001-3000      | 10       | 8.7%    |
| 1-20           | 7        | 6.09%   |
| Unknown        | 7        | 6.09%   |
| 21-50          | 3        | 2.61%   |
| 51-100         | 2        | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 28       | 24.14%  |
| 21-50          | 21       | 18.1%   |
| 101-250        | 18       | 15.52%  |
| 251-500        | 12       | 10.34%  |
| 501-1000       | 9        | 7.76%   |
| 51-100         | 9        | 7.76%   |
| 1001-2000      | 7        | 6.03%   |
| Unknown        | 7        | 6.03%   |
| More than 3000 | 4        | 3.45%   |
| 2001-3000      | 1        | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB     | 3        | 4      | 20%     |
| WDC WD5000AVDS-73U7B1 500GB     | 1        | 1      | 6.67%   |
| WDC WD5000AAKS-22V1A0 500GB     | 1        | 1      | 6.67%   |
| WDC WD50 EZRX-00MVLB1 5TB       | 1        | 1      | 6.67%   |
| WDC WD10EZEX-60M2NA0 1TB        | 1        | 1      | 6.67%   |
| WDC WD1002FAEX-00Z3A0 1TB       | 1        | 1      | 6.67%   |
| WDC WD1002FAEX-00Y9A0 1TB       | 1        | 1      | 6.67%   |
| Teclast 480GB A800 SSD          | 1        | 1      | 6.67%   |
| Seagate ST8000NM0055-1RM112 8TB | 1        | 1      | 6.67%   |
| Seagate ST31500341AS 1TB        | 1        | 1      | 6.67%   |
| Hitachi HDS721010CLA632 1TB     | 1        | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB      | 1        | 1      | 6.67%   |
| Crucial CT120M500SSD1 120GB     | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 10     | 61.54%  |
| Teclast | 1        | 1      | 7.69%   |
| Seagate | 1        | 2      | 7.69%   |
| Hitachi | 1        | 1      | 7.69%   |
| HGST    | 1        | 1      | 7.69%   |
| Crucial | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 10     | 72.73%  |
| Seagate | 1        | 2      | 9.09%   |
| Hitachi | 1        | 1      | 9.09%   |
| HGST    | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 14     | 84.62%  |
| SSD  | 2        | 2      | 15.38%  |

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
| Detected | 64       | 137    | 50.79%  |
| Works    | 49       | 110    | 38.89%  |
| Malfunc  | 13       | 16     | 10.32%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 72       | 42.86%  |
| AMD                          | 35       | 20.83%  |
| Samsung Electronics          | 20       | 11.9%   |
| SanDisk                      | 9        | 5.36%   |
| ASMedia Technology           | 6        | 3.57%   |
| Phison Electronics           | 4        | 2.38%   |
| Micron/Crucial Technology    | 4        | 2.38%   |
| Silicon Motion               | 3        | 1.79%   |
| Marvell Technology Group     | 3        | 1.79%   |
| Toshiba America Info Systems | 2        | 1.19%   |
| Kingston Technology Company  | 2        | 1.19%   |
| Adaptec                      | 2        | 1.19%   |
| VIA Technologies             | 1        | 0.6%    |
| Shenzhen Longsys Electronics | 1        | 0.6%    |
| Realtek Semiconductor        | 1        | 0.6%    |
| KIOXIA                       | 1        | 0.6%    |
| JMicron Technology           | 1        | 0.6%    |
| Broadcom / LSI               | 1        | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 11.28%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 6.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 5.13%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 3.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 3.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 3.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 3.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 2.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 2.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.54%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2        | 1.03%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.03%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.03%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.03%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.03%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 1.03%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.03%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.03%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.03%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.03%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.51%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 1        | 0.51%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1        | 0.51%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 92       | 58.23%  |
| NVMe | 37       | 23.42%  |
| IDE  | 15       | 9.49%   |
| RAID | 10       | 6.33%   |
| SAS  | 4        | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 75       | 68.18%  |
| AMD    | 35       | 31.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 4.55%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 3.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 3.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 2.73%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.82%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 1.82%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.82%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.82%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.82%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.82%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores  | 2        | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.82%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.82%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.82%   |
| Intel Xeon W-2155 CPU @ 3.30GHz             | 1        | 0.91%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz         | 1        | 0.91%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.91%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.91%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 0.91%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.91%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.91%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.91%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.91%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.91%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.91%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.91%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.91%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.91%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.91%   |
| Intel Core i9-7940X CPU @ 3.10GHz           | 1        | 0.91%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.91%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.91%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1        | 0.91%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.91%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.91%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 30       | 27.27%  |
| Intel Core i7          | 15       | 13.64%  |
| AMD Ryzen 5            | 12       | 10.91%  |
| Intel Xeon             | 10       | 9.09%   |
| Other                  | 6        | 5.45%   |
| AMD Ryzen 7            | 6        | 5.45%   |
| Intel Core i3          | 4        | 3.64%   |
| AMD Ryzen 9            | 4        | 3.64%   |
| Intel Core 2 Quad      | 2        | 1.82%   |
| AMD Ryzen Threadripper | 2        | 1.82%   |
| AMD FX                 | 2        | 1.82%   |
| AMD Athlon             | 2        | 1.82%   |
| AMD A10                | 2        | 1.82%   |
| Intel Pentium Gold     | 1        | 0.91%   |
| Intel Pentium Dual     | 1        | 0.91%   |
| Intel Pentium 4        | 1        | 0.91%   |
| Intel Pentium          | 1        | 0.91%   |
| Intel Core m3          | 1        | 0.91%   |
| Intel Core i9          | 1        | 0.91%   |
| Intel Celeron          | 1        | 0.91%   |
| Intel Atom             | 1        | 0.91%   |
| AMD Ryzen 5 PRO        | 1        | 0.91%   |
| AMD PRO A10            | 1        | 0.91%   |
| AMD Phenom II X6       | 1        | 0.91%   |
| AMD Phenom II X4       | 1        | 0.91%   |
| AMD Opteron            | 1        | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 43       | 39.09%  |
| 6      | 22       | 20%     |
| 2      | 17       | 15.45%  |
| 8      | 11       | 10%     |
| 12     | 7        | 6.36%   |
| 16     | 4        | 3.64%   |
| 10     | 2        | 1.82%   |
| 24     | 1        | 0.91%   |
| 14     | 1        | 0.91%   |
| 3      | 1        | 0.91%   |
| 1      | 1        | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 109      | 99.09%  |
| 2      | 1        | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 68       | 61.82%  |
| 1      | 42       | 38.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 109      | 99.09%  |
| Unknown        | 1        | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 15.32%  |
| 0x306c3    | 10       | 9.01%   |
| 0x306a9    | 9        | 8.11%   |
| 0x906ea    | 8        | 7.21%   |
| 0x506e3    | 7        | 6.31%   |
| 0x08701021 | 5        | 4.5%    |
| 0x90672    | 4        | 3.6%    |
| 0x306e4    | 4        | 3.6%    |
| 0x206a7    | 4        | 3.6%    |
| 0x20655    | 4        | 3.6%    |
| 0x0a201016 | 3        | 2.7%    |
| 0x08701013 | 3        | 2.7%    |
| 0x06003106 | 3        | 2.7%    |
| 0x906e9    | 2        | 1.8%    |
| 0x50654    | 2        | 1.8%    |
| 0x406f1    | 2        | 1.8%    |
| 0x06000852 | 2        | 1.8%    |
| 0xf41      | 1        | 0.9%    |
| 0xa0671    | 1        | 0.9%    |
| 0xa0655    | 1        | 0.9%    |
| 0x706a1    | 1        | 0.9%    |
| 0x6fd      | 1        | 0.9%    |
| 0x6fb      | 1        | 0.9%    |
| 0x1067a    | 1        | 0.9%    |
| 0x0a601201 | 1        | 0.9%    |
| 0x0a20120a | 1        | 0.9%    |
| 0x0a201009 | 1        | 0.9%    |
| 0x08600106 | 1        | 0.9%    |
| 0x0830104d | 1        | 0.9%    |
| 0x08301039 | 1        | 0.9%    |
| 0x08108109 | 1        | 0.9%    |
| 0x08101102 | 1        | 0.9%    |
| 0x08001138 | 1        | 0.9%    |
| 0x08001137 | 1        | 0.9%    |
| 0x0600611a | 1        | 0.9%    |
| 0x0600081c | 1        | 0.9%    |
| 0x010000dc | 1        | 0.9%    |
| 0x010000db | 1        | 0.9%    |
| 0x01000083 | 1        | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 16       | 14.55%  |
| Haswell          | 13       | 11.82%  |
| Zen 2            | 12       | 10.91%  |
| KabyLake         | 12       | 10.91%  |
| Skylake          | 9        | 8.18%   |
| Zen 3            | 7        | 6.36%   |
| SandyBridge      | 6        | 5.45%   |
| Westmere         | 4        | 3.64%   |
| Alderlake Hybrid | 4        | 3.64%   |
| Zen+             | 3        | 2.73%   |
| Zen              | 3        | 2.73%   |
| Steamroller      | 3        | 2.73%   |
| K10              | 3        | 2.73%   |
| Piledriver       | 2        | 1.82%   |
| Core             | 2        | 1.82%   |
| Broadwell        | 2        | 1.82%   |
| Unknown          | 2        | 1.82%   |
| Silvermont       | 1        | 0.91%   |
| Penryn           | 1        | 0.91%   |
| NetBurst         | 1        | 0.91%   |
| Icelake          | 1        | 0.91%   |
| Goldmont plus    | 1        | 0.91%   |
| Excavator        | 1        | 0.91%   |
| CometLake        | 1        | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 51       | 39.23%  |
| Intel             | 44       | 33.85%  |
| AMD               | 34       | 26.15%  |
| ASPEED Technology | 1        | 0.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.73%   |
| Intel HD Graphics 530                                                       | 5        | 3.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.99%   |
| Intel AlderLake-S GT1                                                       | 4        | 2.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.24%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 2.24%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.24%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 2.24%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 2.24%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 2.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 2.24%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.49%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.49%   |
| Nvidia GF119 [GeForce 605]                                                  | 2        | 1.49%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.49%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.49%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.49%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.49%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 1.49%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 2        | 1.49%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.75%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.75%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.75%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.75%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.75%   |
| Nvidia GM200 [GeForce GTX TITAN X]                                          | 1        | 0.75%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.75%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.75%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.75%   |
| Nvidia GK110GL [Tesla K20c]                                                 | 1        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 40       | 35.09%  |
| 1 x Intel       | 32       | 28.07%  |
| 1 x AMD         | 27       | 23.68%  |
| 2 x Nvidia      | 4        | 3.51%   |
| Intel + Nvidia  | 4        | 3.51%   |
| Intel + AMD     | 3        | 2.63%   |
| AMD + Nvidia    | 2        | 1.75%   |
| 2 x AMD         | 1        | 0.88%   |
| Nvidia + ASPEED | 1        | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 65.18%  |
| Proprietary | 36       | 32.14%  |
| Unknown     | 3        | 2.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 35.4%   |
| 1.01-2.0   | 18       | 15.93%  |
| 3.01-4.0   | 13       | 11.5%   |
| 7.01-8.0   | 12       | 10.62%  |
| 0.51-1.0   | 12       | 10.62%  |
| 8.01-16.0  | 9        | 7.96%   |
| 0.01-0.5   | 5        | 4.42%   |
| 5.01-6.0   | 4        | 3.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 33       | 30.56%  |
| Samsung Electronics  | 10       | 9.26%   |
| Hewlett-Packard      | 9        | 8.33%   |
| Goldstar             | 9        | 8.33%   |
| Acer                 | 8        | 7.41%   |
| AOC                  | 5        | 4.63%   |
| Philips              | 4        | 3.7%    |
| PRISM+               | 3        | 2.78%   |
| Denver               | 3        | 2.78%   |
| ViewSonic            | 2        | 1.85%   |
| Lenovo Group Limited | 2        | 1.85%   |
| ASUSTek Computer     | 2        | 1.85%   |
| Unknown              | 2        | 1.85%   |
| Xiaomi               | 1        | 0.93%   |
| Wacom                | 1        | 0.93%   |
| Sony                 | 1        | 0.93%   |
| Sharp                | 1        | 0.93%   |
| SGT                  | 1        | 0.93%   |
| SAC                  | 1        | 0.93%   |
| RTK                  | 1        | 0.93%   |
| Pixio                | 1        | 0.93%   |
| MSI                  | 1        | 0.93%   |
| Lenovo               | 1        | 0.93%   |
| HPN                  | 1        | 0.93%   |
| CVT                  | 1        | 0.93%   |
| CHR                  | 1        | 0.93%   |
| AUS                  | 1        | 0.93%   |
| AU Optronics         | 1        | 0.93%   |
| Ancor Communications | 1        | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 3.57%   |
| Samsung Electronics S24F350 SAM0D22 1920x1080 521x293mm 23.5-inch     | 2        | 1.79%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch               | 2        | 1.79%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 1.79%   |
| Denver GB-2461CF LHC0236 1920x1080 530x280mm 23.6-inch                | 2        | 1.79%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                   | 2        | 1.79%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2        | 1.79%   |
| Dell LCD Monitor P2217H 1920x1080                                     | 2        | 1.79%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                    | 2        | 1.79%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                     | 2        | 1.79%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                      | 2        | 1.79%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 2        | 1.79%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 1.79%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                      | 2        | 1.79%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                   | 2        | 1.79%   |
| Unknown                                                               | 2        | 1.79%   |
| Xiaomi Mi TV XMD004A 1360x768 708x398mm 32.0-inch                     | 1        | 0.89%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 0.89%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 0.89%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                             | 1        | 0.89%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                         | 1        | 0.89%   |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                      | 1        | 0.89%   |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                   | 1        | 0.89%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1        | 0.89%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 0.89%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 950x540mm 43.0-inch | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor S27A950D 1920x1080                    | 1        | 0.89%   |
| Samsung Electronics LCD Monitor S24B350 1920x1080                     | 1        | 0.89%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.89%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 0.89%   |
| RTK FHD HDR RTKBC32 1920x1080 332x186mm 15.0-inch                     | 1        | 0.89%   |
| PRISM+ P270 INN2700 3840x2160 597x336mm 27.0-inch                     | 1        | 0.89%   |
| Pixio PX275h WAM2700 2560x1440 600x330mm 27.0-inch                    | 1        | 0.89%   |
| Philips PHL 342E2 PHLC233 2560x1080 800x335mm 34.1-inch               | 1        | 0.89%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch               | 1        | 0.89%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                 | 1        | 0.89%   |
| Philips 17S4 PHL08D0 1280x1024 338x270mm 17.0-inch                    | 1        | 0.89%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                       | 1        | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 54       | 50%     |
| 2560x1440 (QHD)    | 16       | 14.81%  |
| 3840x2160 (4K)     | 15       | 13.89%  |
| 1600x900 (HD+)     | 11       | 10.19%  |
| 2560x1080          | 2        | 1.85%   |
| 1680x1050 (WSXGA+) | 2        | 1.85%   |
| 1360x768           | 2        | 1.85%   |
| 1280x1024 (SXGA)   | 2        | 1.85%   |
| 3440x1440          | 1        | 0.93%   |
| 2560x1600          | 1        | 0.93%   |
| 1440x900 (WXGA+)   | 1        | 0.93%   |
| 1366x768 (WXGA)    | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 18       | 16.82%  |
| Unknown | 17       | 15.89%  |
| 23      | 14       | 13.08%  |
| 24      | 11       | 10.28%  |
| 21      | 10       | 9.35%   |
| 20      | 8        | 7.48%   |
| 31      | 5        | 4.67%   |
| 19      | 5        | 4.67%   |
| 18      | 4        | 3.74%   |
| 40      | 2        | 1.87%   |
| 28      | 2        | 1.87%   |
| 15      | 2        | 1.87%   |
| 84      | 1        | 0.93%   |
| 65      | 1        | 0.93%   |
| 55      | 1        | 0.93%   |
| 39      | 1        | 0.93%   |
| 34      | 1        | 0.93%   |
| 32      | 1        | 0.93%   |
| 25      | 1        | 0.93%   |
| 22      | 1        | 0.93%   |
| 17      | 1        | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 44       | 41.12%  |
| 401-500     | 26       | 24.3%   |
| Unknown     | 17       | 15.89%  |
| 601-700     | 7        | 6.54%   |
| 801-900     | 3        | 2.8%    |
| 301-350     | 3        | 2.8%    |
| 701-800     | 2        | 1.87%   |
| 351-400     | 2        | 1.87%   |
| 1001-1500   | 2        | 1.87%   |
| 1501-2000   | 1        | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 76.19%  |
| Unknown | 16       | 15.24%  |
| 16/10   | 4        | 3.81%   |
| 5/4     | 2        | 1.9%    |
| 21/9    | 2        | 1.9%    |
| 6/5     | 1        | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 29       | 27.36%  |
| 301-350        | 18       | 16.98%  |
| 151-200        | 17       | 16.04%  |
| Unknown        | 17       | 16.04%  |
| 351-500        | 8        | 7.55%   |
| 251-300        | 5        | 4.72%   |
| 141-150        | 4        | 3.77%   |
| More than 1000 | 3        | 2.83%   |
| 501-1000       | 3        | 2.83%   |
| 101-110        | 2        | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 58       | 53.7%   |
| 101-120 | 18       | 16.67%  |
| Unknown | 17       | 15.74%  |
| 161-240 | 7        | 6.48%   |
| 121-160 | 6        | 5.56%   |
| 1-50    | 2        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 88.5%   |
| 2     | 8        | 7.08%   |
| 0     | 5        | 4.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 66       | 40.74%  |
| Intel                 | 60       | 37.04%  |
| Qualcomm Atheros      | 11       | 6.79%   |
| TP-Link               | 6        | 3.7%    |
| Broadcom              | 5        | 3.09%   |
| ASUSTek Computer      | 3        | 1.85%   |
| Samsung Electronics   | 2        | 1.23%   |
| Ralink Technology     | 1        | 0.62%   |
| MediaTek              | 1        | 0.62%   |
| Linksys               | 1        | 0.62%   |
| Hewlett-Packard       | 1        | 0.62%   |
| Fargo                 | 1        | 0.62%   |
| Exar                  | 1        | 0.62%   |
| Edimax Technology     | 1        | 0.62%   |
| ASIX Electronics      | 1        | 0.62%   |
| Aquantia              | 1        | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 24.19%  |
| Intel Wi-Fi 6 AX200                                               | 14       | 7.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 6.45%   |
| Intel I211 Gigabit Network Connection                             | 10       | 5.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.76%   |
| Intel Ethernet Controller I225-V                                  | 6        | 3.23%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.69%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 1.61%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 3        | 1.61%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2        | 1.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.08%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 1.08%   |
| Intel Wireless 3165                                               | 2        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.08%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.08%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.08%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.54%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.54%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.54%   |
| Realtek 802.11ac NIC                                              | 1        | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 28       | 48.28%  |
| Realtek Semiconductor | 7        | 12.07%  |
| TP-Link               | 6        | 10.34%  |
| Qualcomm Atheros      | 6        | 10.34%  |
| Broadcom              | 4        | 6.9%    |
| ASUSTek Computer      | 3        | 5.17%   |
| Ralink Technology     | 1        | 1.72%   |
| MediaTek              | 1        | 1.72%   |
| Linksys               | 1        | 1.72%   |
| Edimax Technology     | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 14       | 24.14%  |
| Intel Alder Lake-S PCH CNVi WiFi                                | 3        | 5.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 3        | 5.17%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3        | 5.17%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                      | 2        | 3.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 2        | 3.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                 | 2        | 3.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 2        | 3.45%   |
| Intel Wireless 3165                                             | 2        | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 2        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 3.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 1.72%   |
| TP-Link Archer T4U ver.3                                        | 1        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 1.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 1.72%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 1.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter           | 1        | 1.72%   |
| Realtek 802.11ac NIC                                            | 1        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                 | 1        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1        | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 1        | 1.72%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter             | 1        | 1.72%   |
| Intel Wireless-AC 9260                                          | 1        | 1.72%   |
| Intel Wireless 8260                                             | 1        | 1.72%   |
| Intel Wireless 7260                                             | 1        | 1.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1        | 1.72%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.72%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter              | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 61       | 50.83%  |
| Intel                 | 48       | 40%     |
| Qualcomm Atheros      | 5        | 4.17%   |
| Samsung Electronics   | 2        | 1.67%   |
| Hewlett-Packard       | 1        | 0.83%   |
| Broadcom              | 1        | 0.83%   |
| ASIX Electronics      | 1        | 0.83%   |
| Aquantia              | 1        | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 35.71%  |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 9.52%   |
| Intel I211 Gigabit Network Connection                             | 10       | 7.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 6        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.97%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 2.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.59%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.59%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.79%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.79%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.79%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.79%   |
| Intel Ethernet Controller X550                                    | 1        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.79%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.79%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.79%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.79%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.79%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1        | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.79%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 65.09%  |
| WiFi     | 57       | 33.73%  |
| Modem    | 1        | 0.59%   |
| Unknown  | 1        | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 85       | 73.28%  |
| WiFi     | 30       | 25.86%  |
| Unknown  | 1        | 0.86%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 58       | 52.73%  |
| 2     | 47       | 42.73%  |
| 3     | 4        | 3.64%   |
| 0     | 1        | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 103      | 93.64%  |
| Yes  | 7        | 6.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 53.66%  |
| Cambridge Silicon Radio         | 8        | 19.51%  |
| TP-Link                         | 4        | 9.76%   |
| Qualcomm Atheros Communications | 3        | 7.32%   |
| SINO WEALTH                     | 1        | 2.44%   |
| Realtek Semiconductor           | 1        | 2.44%   |
| MediaTek                        | 1        | 2.44%   |
| Broadcom                        | 1        | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 11       | 26.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 19.51%  |
| TP-Link UB500 Adapter                               | 4        | 9.76%   |
| Intel Bluetooth wireless interface                  | 4        | 9.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 7.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 4.88%   |
| Intel AX201 Bluetooth                               | 2        | 4.88%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.44%   |
| MediaTek Wireless_Device                            | 1        | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.44%   |
| Intel AX210 Bluetooth                               | 1        | 2.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 73       | 40.11%  |
| Nvidia                               | 50       | 27.47%  |
| AMD                                  | 40       | 21.98%  |
| SteelSeries ApS                      | 2        | 1.1%    |
| Creative Labs                        | 2        | 1.1%    |
| XMOS                                 | 1        | 0.55%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.55%   |
| Sony                                 | 1        | 0.55%   |
| Setek Elektronik                     | 1        | 0.55%   |
| Sennheiser Communications            | 1        | 0.55%   |
| SAVITECH                             | 1        | 0.55%   |
| Samson Technologies                  | 1        | 0.55%   |
| Realtek Semiconductor                | 1        | 0.55%   |
| Micro Star International             | 1        | 0.55%   |
| Logitech                             | 1        | 0.55%   |
| JMTek                                | 1        | 0.55%   |
| Huawei Technologies                  | 1        | 0.55%   |
| FiiO Electronics Technology          | 1        | 0.55%   |
| C-Media Electronics                  | 1        | 0.55%   |
| ASUSTek Computer                     | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 8.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 5.21%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 3.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 3.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 2.37%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.37%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 2.37%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 2.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 2.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.9%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.9%    |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.42%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.42%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.42%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.42%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.42%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.95%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.95%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.95%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 0.95%   |
| AMD FCH Azalia Controller                                                  | 2        | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 0.95%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1        | 0.47%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1        | 0.47%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1        | 0.47%   |
| SteelSeries ApS Arctis 7+                                                  | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 15       | 20.27%  |
| Corsair                        | 9        | 12.16%  |
| SK hynix                       | 7        | 9.46%   |
| Micron Technology              | 7        | 9.46%   |
| G.Skill                        | 7        | 9.46%   |
| Crucial                        | 7        | 9.46%   |
| Samsung Electronics            | 6        | 8.11%   |
| Transcend                      | 2        | 2.7%    |
| KLEVV                          | 2        | 2.7%    |
| Kingmax                        | 2        | 2.7%    |
| Unknown (ABCD)                 | 1        | 1.35%   |
| Unknown                        | 1        | 1.35%   |
| Qimonda                        | 1        | 1.35%   |
| Patriot                        | 1        | 1.35%   |
| Nanya Technology               | 1        | 1.35%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 1.35%   |
| Essencore Limited              | 1        | 1.35%   |
| Elpida                         | 1        | 1.35%   |
| ASint Technology               | 1        | 1.35%   |
| A-DATA Technology              | 1        | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                      | 2        | 2.47%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 2        | 2.47%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s               | 2        | 2.47%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s              | 2        | 2.47%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s                 | 2        | 2.47%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                | 1        | 1.23%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1        | 1.23%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s        | 1        | 1.23%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR 2048MT/s                  | 1        | 1.23%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                   | 1        | 1.23%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1        | 1.23%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 1.23%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1        | 1.23%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1        | 1.23%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2400MT/s                | 1        | 1.23%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1        | 1.23%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1        | 1.23%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s                 | 1        | 1.23%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s                 | 1        | 1.23%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                 | 1        | 1.23%   |
| Samsung RAM M378A2K43CB1-CRC 16GB DIMM DDR4 2400MT/s                | 1        | 1.23%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                 | 1        | 1.23%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                 | 1        | 1.23%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                    | 1        | 1.23%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s                 | 1        | 1.23%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s                  | 1        | 1.23%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER RAM Module 2048MB DIMM DDR3 1600MT/s | 1        | 1.23%   |
| Micron RAM TEAMGROUP-UD4-2133 16384MB DIMM DDR4 2134MT/s            | 1        | 1.23%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                 | 1        | 1.23%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                  | 1        | 1.23%   |
| Micron RAM 36KSF2G72PZ-1G6N1 16GB DIMM DDR3 1600MT/s                | 1        | 1.23%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s                | 1        | 1.23%   |
| Micron RAM 16KTF1G64HZ-1G6J1 8GB SODIMM DDR3 1600MT/s               | 1        | 1.23%   |
| Micron RAM 16ATF4G64AZ-3G2F1 32GB DIMM DDR4 3200MT/s                | 1        | 1.23%   |
| Micron RAM 16ATF2G64AZ-2G6E1 16GB DIMM DDR4 2667MT/s                | 1        | 1.23%   |
| KLEVV RAM KD4AGUA80-40B190X 16GB DIMM DDR4 4000MT/s                 | 1        | 1.23%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s                  | 1        | 1.23%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 1        | 1.23%   |
| Kingston RAM KHX1866C11D3L/8G 8192MB DIMM DDR3 1867MT/s             | 1        | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 37       | 56.92%  |
| DDR3    | 20       | 30.77%  |
| SDRAM   | 3        | 4.62%   |
| DDR2    | 2        | 3.08%   |
| LPDDR4  | 1        | 1.54%   |
| DDR5    | 1        | 1.54%   |
| Unknown | 1        | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 96.77%  |
| SODIMM | 2        | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 30.43%  |
| 16384 | 20       | 28.99%  |
| 4096  | 16       | 23.19%  |
| 2048  | 6        | 8.7%    |
| 32768 | 5        | 7.25%   |
| 1024  | 1        | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 13       | 17.57%  |
| 2400  | 12       | 16.22%  |
| 3200  | 8        | 10.81%  |
| 3600  | 6        | 8.11%   |
| 1333  | 4        | 5.41%   |
| 2667  | 3        | 4.05%   |
| 2666  | 3        | 4.05%   |
| 2133  | 3        | 4.05%   |
| 3733  | 2        | 2.7%    |
| 3400  | 2        | 2.7%    |
| 3266  | 2        | 2.7%    |
| 2048  | 2        | 2.7%    |
| 1867  | 2        | 2.7%    |
| 1866  | 2        | 2.7%    |
| 1800  | 2        | 2.7%    |
| 5808  | 1        | 1.35%   |
| 4333  | 1        | 1.35%   |
| 4000  | 1        | 1.35%   |
| 3666  | 1        | 1.35%   |
| 2200  | 1        | 1.35%   |
| 2134  | 1        | 1.35%   |
| 1067  | 1        | 1.35%   |
| 667   | 1        | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Samsung M2020 Series | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 6        | 54.55%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Microdia              | 1        | 9.09%   |
| Apple                 | 1        | 9.09%   |
| Alcor Micro           | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 3        | 27.27%  |
| Logitech HD Webcam C615                 | 2        | 18.18%  |
| Realtek HP 1.0MP High Definition Webcam | 1        | 9.09%   |
| Realtek Asus laptop camera              | 1        | 9.09%   |
| Microdia Webcam Vitade AF               | 1        | 9.09%   |
| Logitech Webcam C310                    | 1        | 9.09%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1        | 9.09%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 9.09%   |

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
| 0     | 94       | 85.45%  |
| 1     | 15       | 13.64%  |
| 2     | 1        | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 35.29%  |
| Graphics card            | 4        | 23.53%  |
| Unassigned class         | 2        | 11.76%  |
| Network                  | 2        | 11.76%  |
| Communication controller | 2        | 11.76%  |
| Net/ethernet             | 1        | 5.88%   |

