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

Total: 184

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Shenzhen M... | HX90G                       | [a6e9f6c7fc](https://linux-hardware.org/?probe=a6e9f6c7fc) | Oct 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ce357bee14](https://linux-hardware.org/?probe=ce357bee14) | Sep 28, 2023 |
| Gigabyte      | B85M-D3H                    | [cfcdb2a961](https://linux-hardware.org/?probe=cfcdb2a961) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [816502caea](https://linux-hardware.org/?probe=816502caea) | Sep 21, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [62d1008e3a](https://linux-hardware.org/?probe=62d1008e3a) | Sep 01, 2023 |
| Huanan        | X99-4MT V1.0                | [b1ebbd0661](https://linux-hardware.org/?probe=b1ebbd0661) | Aug 29, 2023 |
| HP            | 0B4Ch D                     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| Dell          | 04Y8V0 A02                  | [645bd9ed6b](https://linux-hardware.org/?probe=645bd9ed6b) | Aug 20, 2023 |
| ASRock        | H71M-DGS                    | [c200c4f848](https://linux-hardware.org/?probe=c200c4f848) | Aug 14, 2023 |
| Foxconn       | 2A8Ch                       | [a936584caa](https://linux-hardware.org/?probe=a936584caa) | Aug 09, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| Dell          | 09M8Y8 A02                  | [4b57bbf30e](https://linux-hardware.org/?probe=4b57bbf30e) | Aug 04, 2023 |
| Intel         | JSL MRD                     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | PRIME X570-P                | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| Dell          | 00V62H A01                  | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| MECHREVO      | F7BFD V1.0                  | [f9be0fc5a7](https://linux-hardware.org/?probe=f9be0fc5a7) | Jul 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [556e4cd2c9](https://linux-hardware.org/?probe=556e4cd2c9) | Jul 21, 2023 |
| AZW           | Gemini J45                  | [0ed36a4286](https://linux-hardware.org/?probe=0ed36a4286) | Jul 18, 2023 |
| Shenzhen M... | HX90G                       | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| Gigabyte      | Z690 AERO D                 | [f42140d294](https://linux-hardware.org/?probe=f42140d294) | Jul 03, 2023 |
| Shenzhen M... | HX90G                       | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| ASUSTek       | PRIME H510M-E               | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| MSI           | B450M MORTAR                | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [f17ae033ef](https://linux-hardware.org/?probe=f17ae033ef) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| Dell          | 04Y8V0 A02                  | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| AZW           | MINI S 10                   | [c64432906e](https://linux-hardware.org/?probe=c64432906e) | May 10, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [64f08f10f3](https://linux-hardware.org/?probe=64f08f10f3) | May 10, 2023 |
| Dell          | 04Y8V0 A02                  | [d21ef87b63](https://linux-hardware.org/?probe=d21ef87b63) | May 10, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Gigabyte      | H61M-S2PH                   | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [7e0735056c](https://linux-hardware.org/?probe=7e0735056c) | Apr 12, 2023 |
| ASRock        | B450 Pro4                   | [ac4522914d](https://linux-hardware.org/?probe=ac4522914d) | Apr 02, 2023 |
| Pegatron      | 2ADC                        | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| Unknown       | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [c02aa4b9e1](https://linux-hardware.org/?probe=c02aa4b9e1) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| HP            | 1589                        | [2fc61ae7b4](https://linux-hardware.org/?probe=2fc61ae7b4) | Mar 09, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [63f1f6f5dd](https://linux-hardware.org/?probe=63f1f6f5dd) | Mar 08, 2023 |
| SZMZ          | X99M-G2                     | [e2244668d1](https://linux-hardware.org/?probe=e2244668d1) | Mar 02, 2023 |
| SZMZ          | X99M-G2                     | [4e45d95aa1](https://linux-hardware.org/?probe=4e45d95aa1) | Mar 01, 2023 |
| Novatte       | M20                         | [f3b00d12f2](https://linux-hardware.org/?probe=f3b00d12f2) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [de144d5025](https://linux-hardware.org/?probe=de144d5025) | Feb 12, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | [e7cc1c6b15](https://linux-hardware.org/?probe=e7cc1c6b15) | Feb 07, 2023 |
| HPE           | ProLiant MicroServer Gen... | [9a9b3eed69](https://linux-hardware.org/?probe=9a9b3eed69) | Feb 05, 2023 |
| Foxconn       | 17A0                        | [1a98ed31ed](https://linux-hardware.org/?probe=1a98ed31ed) | Feb 05, 2023 |
| Lenovo        | NOK                         | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2e6f75ca07](https://linux-hardware.org/?probe=2e6f75ca07) | Jan 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | [6dac0c0943](https://linux-hardware.org/?probe=6dac0c0943) | Dec 29, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| ASUSTek       | A88XM-A                     | [8633f00865](https://linux-hardware.org/?probe=8633f00865) | Dec 26, 2022 |
| ASUSTek       | A88XM-A                     | [802e7982de](https://linux-hardware.org/?probe=802e7982de) | Dec 26, 2022 |
| HP            | 8061                        | [4427032526](https://linux-hardware.org/?probe=4427032526) | Dec 24, 2022 |
| ASRock        | B75 Pro3-M                  | [e24692f75f](https://linux-hardware.org/?probe=e24692f75f) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | [61f064d35f](https://linux-hardware.org/?probe=61f064d35f) | Dec 22, 2022 |
| ASRock        | B450 Pro4                   | [d387b553bd](https://linux-hardware.org/?probe=d387b553bd) | Dec 22, 2022 |
| Foxconn       | 17A0                        | [58a3486afd](https://linux-hardware.org/?probe=58a3486afd) | Dec 20, 2022 |
| Foxconn       | 17A0                        | [be57227f43](https://linux-hardware.org/?probe=be57227f43) | Dec 17, 2022 |
| Foxconn       | 17A0                        | [b2185eeab5](https://linux-hardware.org/?probe=b2185eeab5) | Dec 16, 2022 |
| Foxconn       | 17A0                        | [4518247b07](https://linux-hardware.org/?probe=4518247b07) | Dec 14, 2022 |
| Foxconn       | 17A0                        | [2f3b2f9fbb](https://linux-hardware.org/?probe=2f3b2f9fbb) | Dec 07, 2022 |
| HP            | 8061                        | [6e4cb7cde8](https://linux-hardware.org/?probe=6e4cb7cde8) | Dec 07, 2022 |
| HP            | 8061                        | [9d30b0126f](https://linux-hardware.org/?probe=9d30b0126f) | Dec 05, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Acer          | RS880M05                    | [7adee2fd97](https://linux-hardware.org/?probe=7adee2fd97) | Oct 21, 2022 |
| ASUSTek       | Maximus IV Extreme          | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Gigabyte      | B550M DS3H AC               | [9ec02e49a3](https://linux-hardware.org/?probe=9ec02e49a3) | Oct 13, 2022 |
| Gigabyte      | X99-Ultra Gaming-CF         | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| ASUSTek       | X99-E WS                    | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| HP            | 843B                        | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Gigabyte      | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Gigabyte      | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| MSI           | Z87-G45 GAMING              | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| ASUSTek       | B85M-E                      | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| ASUSTek       | B85M-E                      | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek       | B85M-E                      | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| Dell          | 06CV2N A00                  | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Dell          | 0NK70N A03                  | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| HP            | 8054                        | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| Dell          | 09M8Y8 A02                  | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Dell          | 06CV2N A00                  | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte      | Z77-D3H                     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| ASRock        | B560M Pro4                  | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell          | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Dell          | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI           | Cherry Trail CR             | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell          | 0C96W1 A02                  | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte      | B365M GAMING HD             | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Dell          | 0XCR8D A03                  | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| MSI           | B450 TOMAHAWK               | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI           | A320M-A PRO MAX             | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI           | A320M-A PRO MAX             | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock        | Z77 Extreme3                | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo        | NOK                         | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Biostar       | TB250-BTC+                  | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell          | 0NKW6Y A00                  | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| LattePanda    | Alpha                       | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda    | Alpha                       | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| HP            | 198E                        | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Gigabyte      | H81M-DS2                    | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock        | HM55-MXM                    | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo        | ThinkCentre M90p 5864BM3    | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell          | 0D6H9T A00                  | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo        | SHARKBAY NOK                | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Dell          | 00V62H A01                  | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell          | 0D02VH A01                  | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Dell          | 0D441T A03                  | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| ASUSTek       | M4A78-EM-1394               | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock        | H110M-HDS R3.0              | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| ASRock        | 990FX Killer                | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| ASUSTek       | M3A78-EM                    | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| ASUSTek       | Z97M-PLUS                   | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Gigabyte      | 945GZM-S2                   | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Gigabyte      | 945GZM-S2                   | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| ASUSTek       | P8H77-V LE                  | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| ASRock        | HM55-MXM                    | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| ECS           | H61H2-MV                    | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| ASUSTek       | P8H77-V LE                  | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| ASUSTek       | H87I-PLUS                   | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock        | H110M-HDS R3.0              | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| ASUSTek       | H87I-PLUS                   | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| ASUSTek       | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock        | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek       | Berkeley                    | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek       | Berkeley                    | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| ASUSTek       | PRIME H310M-A               | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Dell          | 06D7TR A00                  | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Dell          | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell          | 00V62H A01                  | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell          | 00V62H A01                  | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Gigabyte      | Z270X-UD5-CF                | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer          | Aspire X3950                | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASRock        | Z370 Pro4                   | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell          | 0F3KHR A00                  | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| ASUSTek       | P8H67-M PRO                 | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| ASUSTek       | ET2020I                     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| MSI           | X299 RAIDER                 | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI           | X299 RAIDER                 | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI           | Boston                      | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 22       | 15.17%  |
| Ubuntu 18.04                 | 15       | 10.34%  |
| Ubuntu 22.04                 | 11       | 7.59%   |
| Arch Rolling                 | 7        | 4.83%   |
| Linux Mint 21                | 5        | 3.45%   |
| Manjaro                      | 4        | 2.76%   |
| KDE neon 20.04               | 4        | 2.76%   |
| Pop!_OS 20.04                | 3        | 2.07%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 2.07%   |
| OpenMandriva 23.03           | 3        | 2.07%   |
| Fedora 38                    | 3        | 2.07%   |
| Fedora 37                    | 3        | 2.07%   |
| Debian 11                    | 3        | 2.07%   |
| ArcoLinux Rolling            | 3        | 2.07%   |
| Ubuntu 21.04                 | 2        | 1.38%   |
| Rocky Linux 8.5              | 2        | 1.38%   |
| Pop!_OS 21.04                | 2        | 1.38%   |
| OpenMandriva 4.50            | 2        | 1.38%   |
| OpenMandriva 4.3             | 2        | 1.38%   |
| MX 21                        | 2        | 1.38%   |
| Linux Mint 20.3              | 2        | 1.38%   |
| Linux Mint 20                | 2        | 1.38%   |
| Fedora 33                    | 2        | 1.38%   |
| Debian 12                    | 2        | 1.38%   |
| Arch                         | 2        | 1.38%   |
| Zorin 16                     | 1        | 0.69%   |
| Xubuntu 23.04                | 1        | 0.69%   |
| Xubuntu 20.04                | 1        | 0.69%   |
| Ubuntu Unity 20.04           | 1        | 0.69%   |
| Ubuntu Unity 16.04           | 1        | 0.69%   |
| Ubuntu MATE 20.04            | 1        | 0.69%   |
| Ubuntu 23.04                 | 1        | 0.69%   |
| Ubuntu 22.10                 | 1        | 0.69%   |
| Ubuntu 19.10                 | 1        | 0.69%   |
| Ubuntu 19.04                 | 1        | 0.69%   |
| Ubuntu 18.10                 | 1        | 0.69%   |
| Rocky Linux 9.2              | 1        | 0.69%   |
| Rocky Linux 8.7              | 1        | 0.69%   |
| Rocky Linux 8.4              | 1        | 0.69%   |
| Pop!_OS 22.04                | 1        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 53       | 39.26%  |
| OpenMandriva | 10       | 7.41%   |
| Linux Mint   | 9        | 6.67%   |
| Arch         | 9        | 6.67%   |
| Fedora       | 8        | 5.93%   |
| Pop!_OS      | 7        | 5.19%   |
| Debian       | 6        | 4.44%   |
| Manjaro      | 5        | 3.7%    |
| Rocky Linux  | 4        | 2.96%   |
| KDE neon     | 4        | 2.96%   |
| openSUSE     | 3        | 2.22%   |
| ArcoLinux    | 3        | 2.22%   |
| Xubuntu      | 2        | 1.48%   |
| Ubuntu Unity | 2        | 1.48%   |
| MX           | 2        | 1.48%   |
| Zorin        | 1        | 0.74%   |
| Ubuntu MATE  | 1        | 0.74%   |
| Lubuntu      | 1        | 0.74%   |
| Gentoo       | 1        | 0.74%   |
| Garuda Linux | 1        | 0.74%   |
| EndeavourOS  | 1        | 0.74%   |
| CentOS       | 1        | 0.74%   |
| Atz          | 1        | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.0-56-generic            | 7        | 4.43%   |
| 5.15.0-46-generic            | 4        | 2.53%   |
| 6.2.6-desktop-1omv2390       | 3        | 1.9%    |
| 5.4.0-29-generic             | 3        | 1.9%    |
| 5.15.0-58-generic            | 3        | 1.9%    |
| 6.3.8-zen1-1-zen             | 2        | 1.27%   |
| 6.2.14-300.fc38.x86_64       | 2        | 1.27%   |
| 6.0.15-300.fc37.x86_64       | 2        | 1.27%   |
| 5.9.8-200.fc33.x86_64        | 2        | 1.27%   |
| 5.4.0-7642-generic           | 2        | 1.27%   |
| 5.4.0-70-generic             | 2        | 1.27%   |
| 5.4.0-42-generic             | 2        | 1.27%   |
| 5.4.0-40-generic             | 2        | 1.27%   |
| 5.4.0-37-generic             | 2        | 1.27%   |
| 5.3.0-51-generic             | 2        | 1.27%   |
| 5.19.0-35-generic            | 2        | 1.27%   |
| 5.16.7-desktop-1omv4003      | 2        | 1.27%   |
| 5.15.0-71-generic            | 2        | 1.27%   |
| 5.15.0-52-generic            | 2        | 1.27%   |
| 5.12.7-desktop-1omv4003      | 2        | 1.27%   |
| 5.11.0-27-generic            | 2        | 1.27%   |
| 5.0.0-36-generic             | 2        | 1.27%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2        | 1.27%   |
| 6.4.7-desktop-1omv2390       | 1        | 0.63%   |
| 6.4.6-76060406-generic       | 1        | 0.63%   |
| 6.4.3-zen1-1-zen             | 1        | 0.63%   |
| 6.4.12-200.fc38.x86_64       | 1        | 0.63%   |
| 6.4.10-200.fc38.x86_64       | 1        | 0.63%   |
| 6.3.9-zen1-1-zen             | 1        | 0.63%   |
| 6.3.9-1-default              | 1        | 0.63%   |
| 6.3.8-200.fc38.x86_64        | 1        | 0.63%   |
| 6.3.7-zen1-1-zen             | 1        | 0.63%   |
| 6.3.5-desktop-3omv2390       | 1        | 0.63%   |
| 6.3.4-201.fc38.x86_64        | 1        | 0.63%   |
| 6.3.12-100.fc37.x86_64       | 1        | 0.63%   |
| 6.3.0.11.realtime1-1-rt      | 1        | 0.63%   |
| 6.2.9-300.fc38.x86_64        | 1        | 0.63%   |
| 6.2.2-arch1-1                | 1        | 0.63%   |
| 6.2.0-33-generic             | 1        | 0.63%   |
| 6.2.0-31-generic             | 1        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 24       | 15.79%  |
| 5.15.0   | 23       | 15.13%  |
| 5.0.0    | 7        | 4.61%   |
| 5.11.0   | 6        | 3.95%   |
| 5.10.0   | 5        | 3.29%   |
| 4.18.0   | 5        | 3.29%   |
| 6.2.0    | 4        | 2.63%   |
| 4.15.0   | 4        | 2.63%   |
| 6.3.8    | 3        | 1.97%   |
| 6.2.6    | 3        | 1.97%   |
| 5.8.0    | 3        | 1.97%   |
| 5.3.0    | 3        | 1.97%   |
| 5.19.0   | 3        | 1.97%   |
| 6.3.9    | 2        | 1.32%   |
| 6.2.14   | 2        | 1.32%   |
| 6.1.0    | 2        | 1.32%   |
| 6.0.15   | 2        | 1.32%   |
| 5.9.8    | 2        | 1.32%   |
| 5.16.7   | 2        | 1.32%   |
| 5.13.0   | 2        | 1.32%   |
| 5.12.7   | 2        | 1.32%   |
| 6.4.7    | 1        | 0.66%   |
| 6.4.6    | 1        | 0.66%   |
| 6.4.3    | 1        | 0.66%   |
| 6.4.12   | 1        | 0.66%   |
| 6.4.10   | 1        | 0.66%   |
| 6.3.7    | 1        | 0.66%   |
| 6.3.5    | 1        | 0.66%   |
| 6.3.4    | 1        | 0.66%   |
| 6.3.12   | 1        | 0.66%   |
| 6.3.0.11 | 1        | 0.66%   |
| 6.2.9    | 1        | 0.66%   |
| 6.2.2    | 1        | 0.66%   |
| 6.1.6    | 1        | 0.66%   |
| 6.1.53   | 1        | 0.66%   |
| 6.1.4    | 1        | 0.66%   |
| 6.1.39   | 1        | 0.66%   |
| 6.1.1    | 1        | 0.66%   |
| 6.0.2    | 1        | 0.66%   |
| 6.0.0    | 1        | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 30       | 19.87%  |
| 5.4     | 24       | 15.89%  |
| 6.2     | 10       | 6.62%   |
| 6.3     | 9        | 5.96%   |
| 6.1     | 7        | 4.64%   |
| 5.11    | 7        | 4.64%   |
| 5.10    | 7        | 4.64%   |
| 5.0     | 7        | 4.64%   |
| 6.4     | 5        | 3.31%   |
| 4.18    | 5        | 3.31%   |
| 6.0     | 4        | 2.65%   |
| 5.8     | 4        | 2.65%   |
| 5.16    | 4        | 2.65%   |
| 5.13    | 4        | 2.65%   |
| 4.15    | 4        | 2.65%   |
| 5.9     | 3        | 1.99%   |
| 5.3     | 3        | 1.99%   |
| 5.19    | 3        | 1.99%   |
| 5.14    | 3        | 1.99%   |
| 5.12    | 3        | 1.99%   |
| 6.3.0   | 1        | 0.66%   |
| 5.18    | 1        | 0.66%   |
| 5.17    | 1        | 0.66%   |
| 4.16    | 1        | 0.66%   |
| 3.10    | 1        | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 132      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 60       | 43.8%   |
| KDE5          | 23       | 16.79%  |
| Unknown       | 22       | 16.06%  |
| X-Cinnamon    | 11       | 8.03%   |
| XFCE          | 9        | 6.57%   |
| LXQt          | 3        | 2.19%   |
| Unity         | 2        | 1.46%   |
| i3            | 2        | 1.46%   |
| MATE          | 1        | 0.73%   |
| KDE           | 1        | 0.73%   |
| GNOME Classic | 1        | 0.73%   |
| Cinnamon      | 1        | 0.73%   |
| Budgie        | 1        | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 106      | 76.81%  |
| Wayland | 16       | 11.59%  |
| Tty     | 8        | 5.8%    |
| Unknown | 8        | 5.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 47.41%  |
| SDDM    | 22       | 16.3%   |
| GDM     | 18       | 13.33%  |
| GDM3    | 17       | 12.59%  |
| LightDM | 12       | 8.89%   |
| TDM     | 1        | 0.74%   |
| GREETD  | 1        | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 53       | 38.97%  |
| en_SG   | 52       | 38.24%  |
| Unknown | 10       | 7.35%   |
| zh_CN   | 6        | 4.41%   |
| en_AU   | 4        | 2.94%   |
| de_DE   | 3        | 2.21%   |
| C       | 3        | 2.21%   |
| en_GB   | 2        | 1.47%   |
| fr_FR   | 1        | 0.74%   |
| en_PH   | 1        | 0.74%   |
| en_IN   | 1        | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 79       | 59.85%  |
| BIOS | 53       | 40.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 94       | 69.63%  |
| Btrfs   | 18       | 13.33%  |
| Overlay | 10       | 7.41%   |
| Xfs     | 8        | 5.93%   |
| Unknown | 3        | 2.22%   |
| Tmpfs   | 2        | 1.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 67       | 50.38%  |
| Unknown | 55       | 41.35%  |
| MBR     | 11       | 8.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 76.3%   |
| Yes       | 32       | 23.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 60.45%  |
| Yes       | 53       | 39.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 27       | 20.45%  |
| Gigabyte Technology                  | 23       | 17.42%  |
| MSI                                  | 18       | 13.64%  |
| Dell                                 | 17       | 12.88%  |
| ASRock                               | 14       | 10.61%  |
| Hewlett-Packard                      | 6        | 4.55%   |
| Lenovo                               | 5        | 3.79%   |
| Foxconn                              | 4        | 3.03%   |
| AZW                                  | 2        | 1.52%   |
| Acer                                 | 2        | 1.52%   |
| Unknown                              | 2        | 1.52%   |
| SZMZ                                 | 1        | 0.76%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.76%   |
| Pegatron                             | 1        | 0.76%   |
| Novatte                              | 1        | 0.76%   |
| MECHREVO                             | 1        | 0.76%   |
| LattePanda                           | 1        | 0.76%   |
| Intel                                | 1        | 0.76%   |
| Huanan                               | 1        | 0.76%   |
| HPE                                  | 1        | 0.76%   |
| ECS                                  | 1        | 0.76%   |
| Biostar                              | 1        | 0.76%   |
| AMI                                  | 1        | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 5        | 3.79%   |
| Gigabyte X570 AORUS PRO WIFI               | 4        | 3.03%   |
| MSI MS-7C84                                | 3        | 2.27%   |
| Foxconn Pro 3330 MT                        | 3        | 2.27%   |
| Dell OptiPlex 9020                         | 3        | 2.27%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 1.52%   |
| Dell OptiPlex 990                          | 2        | 1.52%   |
| ASUS ROG STRIX B550-I GAMING               | 2        | 1.52%   |
| ASRock B450 Pro4                           | 2        | 1.52%   |
| Unknown                                    | 2        | 1.52%   |
| SZMZ X99M-H2                               | 1        | 0.76%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.76%   |
| Pegatron 23-d018d                          | 1        | 0.76%   |
| Novatte M20                                | 1        | 0.76%   |
| MSI MS-7E06                                | 1        | 0.76%   |
| MSI MS-7D43                                | 1        | 0.76%   |
| MSI MS-7D42                                | 1        | 0.76%   |
| MSI MS-7D30                                | 1        | 0.76%   |
| MSI MS-7D25                                | 1        | 0.76%   |
| MSI MS-7C95                                | 1        | 0.76%   |
| MSI MS-7C91                                | 1        | 0.76%   |
| MSI MS-7C52                                | 1        | 0.76%   |
| MSI MS-7C02                                | 1        | 0.76%   |
| MSI MS-7B89                                | 1        | 0.76%   |
| MSI MS-7A94                                | 1        | 0.76%   |
| MSI MS-7A32                                | 1        | 0.76%   |
| MSI MS-7821                                | 1        | 0.76%   |
| MSI MS-7721                                | 1        | 0.76%   |
| MSI KT308AA-AB4 SR5472CF                   | 1        | 0.76%   |
| MECHREVO F7BFD V1.0                        | 1        | 0.76%   |
| Lenovo ThinkStation P620 30E1S3VH00        | 1        | 0.76%   |
| Lenovo ThinkStation P310 30ASS2WG00        | 1        | 0.76%   |
| Lenovo ThinkCentre M90p 5864BM3            | 1        | 0.76%   |
| Lenovo ThinkCentre M73 10AXS26C00          | 1        | 0.76%   |
| Lenovo ThinkCentre M72e 36601Y8            | 1        | 0.76%   |
| LattePanda Alpha                           | 1        | 0.76%   |
| Intel Jasper Lake Client Platform          | 1        | 0.76%   |
| Huanan X99-4MT V1.0                        | 1        | 0.76%   |
| HPE ProLiant MicroServer Gen10             | 1        | 0.76%   |
| HP Z420 Workstation                        | 1        | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 11       | 8.33%   |
| ASUS ROG                                   | 6        | 4.55%   |
| ASUS All                                   | 5        | 3.79%   |
| Gigabyte X570                              | 4        | 3.03%   |
| MSI MS-7C84                                | 3        | 2.27%   |
| Lenovo ThinkCentre                         | 3        | 2.27%   |
| Foxconn Pro                                | 3        | 2.27%   |
| Dell Precision                             | 3        | 2.27%   |
| ASUS PRIME                                 | 3        | 2.27%   |
| Lenovo ThinkStation                        | 2        | 1.52%   |
| HP ProDesk                                 | 2        | 1.52%   |
| Gigabyte B550I                             | 2        | 1.52%   |
| Gigabyte B450M                             | 2        | 1.52%   |
| Gigabyte B365M                             | 2        | 1.52%   |
| ASRock B450                                | 2        | 1.52%   |
| Unknown                                    | 2        | 1.52%   |
| SZMZ X99M-H2                               | 1        | 0.76%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.76%   |
| Pegatron 23-d018d                          | 1        | 0.76%   |
| Novatte M20                                | 1        | 0.76%   |
| MSI MS-7E06                                | 1        | 0.76%   |
| MSI MS-7D43                                | 1        | 0.76%   |
| MSI MS-7D42                                | 1        | 0.76%   |
| MSI MS-7D30                                | 1        | 0.76%   |
| MSI MS-7D25                                | 1        | 0.76%   |
| MSI MS-7C95                                | 1        | 0.76%   |
| MSI MS-7C91                                | 1        | 0.76%   |
| MSI MS-7C52                                | 1        | 0.76%   |
| MSI MS-7C02                                | 1        | 0.76%   |
| MSI MS-7B89                                | 1        | 0.76%   |
| MSI MS-7A94                                | 1        | 0.76%   |
| MSI MS-7A32                                | 1        | 0.76%   |
| MSI MS-7821                                | 1        | 0.76%   |
| MSI MS-7721                                | 1        | 0.76%   |
| MSI KT308AA-AB4                            | 1        | 0.76%   |
| MECHREVO F7BFD                             | 1        | 0.76%   |
| LattePanda Alpha                           | 1        | 0.76%   |
| Intel Jasper                               | 1        | 0.76%   |
| Huanan X99-4MT                             | 1        | 0.76%   |
| HPE ProLiant                               | 1        | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 16       | 12.12%  |
| 2013 | 16       | 12.12%  |
| 2020 | 15       | 11.36%  |
| 2019 | 13       | 9.85%   |
| 2012 | 12       | 9.09%   |
| 2021 | 9        | 6.82%   |
| 2016 | 7        | 5.3%    |
| 2014 | 7        | 5.3%    |
| 2022 | 6        | 4.55%   |
| 2011 | 6        | 4.55%   |
| 2010 | 6        | 4.55%   |
| 2017 | 5        | 3.79%   |
| 2015 | 5        | 3.79%   |
| 2023 | 4        | 3.03%   |
| 2008 | 2        | 1.52%   |
| 2007 | 2        | 1.52%   |
| 2009 | 1        | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 132      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 128      | 96.97%  |
| Enabled  | 4        | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 132      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 31       | 22.79%  |
| 32.01-64.0      | 29       | 21.32%  |
| 4.01-8.0        | 23       | 16.91%  |
| 8.01-16.0       | 22       | 16.18%  |
| 64.01-256.0     | 12       | 8.82%   |
| 3.01-4.0        | 8        | 5.88%   |
| 24.01-32.0      | 8        | 5.88%   |
| 1.01-2.0        | 2        | 1.47%   |
| More than 256.0 | 1        | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 42       | 28.97%  |
| 2.01-3.0   | 33       | 22.76%  |
| 3.01-4.0   | 30       | 20.69%  |
| 4.01-8.0   | 21       | 14.48%  |
| 8.01-16.0  | 9        | 6.21%   |
| 0.51-1.0   | 6        | 4.14%   |
| 16.01-24.0 | 2        | 1.38%   |
| 32.01-64.0 | 1        | 0.69%   |
| 0.01-0.5   | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 35.25%  |
| 2      | 41       | 29.5%   |
| 3      | 25       | 17.99%  |
| 4      | 15       | 10.79%  |
| 5      | 7        | 5.04%   |
| 0      | 2        | 1.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 66.92%  |
| Yes       | 44       | 33.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 132      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 51.82%  |
| No        | 66       | 48.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 61.65%  |
| Yes       | 51       | 38.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 132      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 124      | 93.23%  |
| Kampong Pasir Ris | 5        | 3.76%   |
| Jurong West       | 3        | 2.26%   |
| Queenstown Estate | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 44       | 68     | 17.53%  |
| Seagate                     | 38       | 48     | 15.14%  |
| WDC                         | 36       | 64     | 14.34%  |
| Toshiba                     | 20       | 26     | 7.97%   |
| SanDisk                     | 18       | 21     | 7.17%   |
| Crucial                     | 10       | 14     | 3.98%   |
| Kingston                    | 8        | 13     | 3.19%   |
| Hitachi                     | 7        | 8      | 2.79%   |
| Unknown                     | 6        | 6      | 2.39%   |
| Phison Electronics          | 4        | 6      | 1.59%   |
| Silicon Motion              | 3        | 5      | 1.2%    |
| Phison                      | 3        | 3      | 1.2%    |
| Micron/Crucial Technology   | 3        | 4      | 1.2%    |
| JMicron Technology          | 3        | 4      | 1.2%    |
| Intel                       | 3        | 3      | 1.2%    |
| HGST                        | 3        | 5      | 1.2%    |
| China                       | 3        | 3      | 1.2%    |
| A-DATA Technology           | 3        | 3      | 1.2%    |
| SK hynix                    | 2        | 2      | 0.8%    |
| Plextor                     | 2        | 2      | 0.8%    |
| Maxtor                      | 2        | 2      | 0.8%    |
| Lexar                       | 2        | 2      | 0.8%    |
| KLEVV                       | 2        | 2      | 0.8%    |
| Kingston Technology Company | 2        | 2      | 0.8%    |
| Hewlett-Packard             | 2        | 2      | 0.8%    |
| Yangtze Memory Technologies | 1        | 1      | 0.4%    |
| WALRAM                      | 1        | 1      | 0.4%    |
| Vaseky                      | 1        | 1      | 0.4%    |
| USB30                       | 1        | 1      | 0.4%    |
| Transcend                   | 1        | 1      | 0.4%    |
| Teclast                     | 1        | 1      | 0.4%    |
| SSK                         | 1        | 1      | 0.4%    |
| SABRENT                     | 1        | 2      | 0.4%    |
| Pioneer                     | 1        | 1      | 0.4%    |
| OCZ                         | 1        | 1      | 0.4%    |
| Mushkin                     | 1        | 1      | 0.4%    |
| MARVELL                     | 1        | 1      | 0.4%    |
| LITEONIT                    | 1        | 1      | 0.4%    |
| KIOXIA-EXCERIA              | 1        | 1      | 0.4%    |
| Kingmax                     | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 7        | 2.41%   |
| Toshiba DT01ACA200 2TB                                | 5        | 1.72%   |
| Samsung SSD 850 EVO 250GB                             | 5        | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 5        | 1.72%   |
| Seagate ST1000DM010-2EP102 1TB                        | 4        | 1.37%   |
| SanDisk NVMe SSD Drive 500GB                          | 4        | 1.37%   |
| Samsung SSD 860 EVO 500GB                             | 4        | 1.37%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 3        | 1.03%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 1.03%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 3        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB                       | 3        | 1.03%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 1.03%   |
| Samsung SSD 980 PRO 1TB                               | 3        | 1.03%   |
| Samsung SSD 980 500GB                                 | 3        | 1.03%   |
| Samsung SSD 860 EVO 1TB                               | 3        | 1.03%   |
| JMicron Generic 240GB                                 | 3        | 1.03%   |
| Crucial CT500MX500SSD1 500GB                          | 3        | 1.03%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 2        | 0.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 2        | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2        | 0.69%   |
| Toshiba HDWD110 1TB                                   | 2        | 0.69%   |
| Toshiba DT01ACA050 500GB                              | 2        | 0.69%   |
| SK hynix SC311 SATA 128GB SSD                         | 2        | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2        | 0.69%   |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.69%   |
| Seagate Expansion HDD 16TB                            | 2        | 0.69%   |
| Seagate BUP Portable 5TB                              | 2        | 0.69%   |
| SanDisk SSD PLUS 480GB                                | 2        | 0.69%   |
| SanDisk SSD PLUS 1000GB                               | 2        | 0.69%   |
| SanDisk NVMe SSD Drive 1TB                            | 2        | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2        | 0.69%   |
| Samsung SSD 960 EVO 250GB                             | 2        | 0.69%   |
| Samsung NVMe SSD Drive 500GB                          | 2        | 0.69%   |
| Samsung NVMe SSD Drive 1024GB                         | 2        | 0.69%   |
| Samsung HN-M750MBB 752GB                              | 2        | 0.69%   |
| Plextor PX-128M6S 128GB SSD                           | 2        | 0.69%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 2        | 0.69%   |
| Maxtor 6V250F0 256GB                                  | 2        | 0.69%   |
| Crucial CT1000MX500SSD1 1TB                           | 2        | 0.69%   |
| A-DATA HC660 1TB SSD                                  | 2        | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 47     | 35.58%  |
| WDC                 | 31       | 57     | 29.81%  |
| Toshiba             | 18       | 24     | 17.31%  |
| Hitachi             | 7        | 8      | 6.73%   |
| Samsung Electronics | 3        | 3      | 2.88%   |
| HGST                | 3        | 5      | 2.88%   |
| Maxtor              | 2        | 2      | 1.92%   |
| SSK                 | 1        | 1      | 0.96%   |
| SABRENT             | 1        | 2      | 0.96%   |
| MARVELL             | 1        | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 32     | 29.76%  |
| SanDisk             | 9        | 9      | 10.71%  |
| Crucial             | 8        | 12     | 9.52%   |
| Kingston            | 6        | 8      | 7.14%   |
| WDC                 | 3        | 3      | 3.57%   |
| JMicron Technology  | 3        | 4      | 3.57%   |
| China               | 3        | 3      | 3.57%   |
| SK hynix            | 2        | 2      | 2.38%   |
| Plextor             | 2        | 2      | 2.38%   |
| Intel               | 2        | 2      | 2.38%   |
| Hewlett-Packard     | 2        | 2      | 2.38%   |
| A-DATA Technology   | 2        | 2      | 2.38%   |
| WALRAM              | 1        | 1      | 1.19%   |
| Vaseky              | 1        | 1      | 1.19%   |
| USB30               | 1        | 1      | 1.19%   |
| Unknown             | 1        | 1      | 1.19%   |
| Transcend           | 1        | 1      | 1.19%   |
| Teclast             | 1        | 1      | 1.19%   |
| Pioneer             | 1        | 1      | 1.19%   |
| OCZ                 | 1        | 1      | 1.19%   |
| LITEONIT            | 1        | 1      | 1.19%   |
| Lexar               | 1        | 1      | 1.19%   |
| KLEVV               | 1        | 1      | 1.19%   |
| Kingmax             | 1        | 1      | 1.19%   |
| KINGBANK            | 1        | 1      | 1.19%   |
| GAMER               | 1        | 1      | 1.19%   |
| GALAX               | 1        | 1      | 1.19%   |
| Fanxiang            | 1        | 1      | 1.19%   |
| Apacer              | 1        | 1      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 84       | 150    | 40.98%  |
| SSD     | 64       | 98     | 31.22%  |
| NVMe    | 52       | 89     | 25.37%  |
| MMC     | 3        | 3      | 1.46%   |
| Unknown | 2        | 2      | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 110      | 234    | 61.45%  |
| NVMe | 52       | 89     | 29.05%  |
| SAS  | 14       | 16     | 7.82%   |
| MMC  | 3        | 3      | 1.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 74       | 109    | 43.79%  |
| 0.51-1.0   | 49       | 73     | 28.99%  |
| 1.01-2.0   | 22       | 29     | 13.02%  |
| 4.01-10.0  | 9        | 18     | 5.33%   |
| 3.01-4.0   | 7        | 10     | 4.14%   |
| 2.01-3.0   | 5        | 5      | 2.96%   |
| 10.01-20.0 | 3        | 4      | 1.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 28       | 20%     |
| 101-250        | 24       | 17.14%  |
| More than 3000 | 17       | 12.14%  |
| 251-500        | 17       | 12.14%  |
| 1001-2000      | 17       | 12.14%  |
| 2001-3000      | 12       | 8.57%   |
| 1-20           | 10       | 7.14%   |
| Unknown        | 8        | 5.71%   |
| 51-100         | 4        | 2.86%   |
| 21-50          | 3        | 2.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 35       | 24.65%  |
| 21-50          | 27       | 19.01%  |
| 101-250        | 19       | 13.38%  |
| 251-500        | 15       | 10.56%  |
| 501-1000       | 11       | 7.75%   |
| 1001-2000      | 10       | 7.04%   |
| 51-100         | 10       | 7.04%   |
| Unknown        | 8        | 5.63%   |
| More than 3000 | 6        | 4.23%   |
| 2001-3000      | 1        | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB     | 3        | 5      | 15.79%  |
| WDC WD5000AVDS-73U7B1 500GB     | 1        | 1      | 5.26%   |
| WDC WD5000AAKS-22V1A0 500GB     | 1        | 1      | 5.26%   |
| WDC WD50 EZRX-00MVLB1 5TB       | 1        | 1      | 5.26%   |
| WDC WD1600AAJS-65WAA0 160GB     | 1        | 1      | 5.26%   |
| WDC WD10EZEX-60M2NA0 1TB        | 1        | 1      | 5.26%   |
| WDC WD1002FAEX-00Z3A0 1TB       | 1        | 1      | 5.26%   |
| WDC WD1002FAEX-00Y9A0 1TB       | 1        | 1      | 5.26%   |
| Toshiba DT01ACA050 500GB        | 1        | 1      | 5.26%   |
| Teclast 480GB A800 SSD          | 1        | 1      | 5.26%   |
| Seagate ST8000NM0055-1RM112 8TB | 1        | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 5.26%   |
| Seagate ST31500341AS 1TB        | 1        | 1      | 5.26%   |
| Seagate ST2000LM007-1R8174 2TB  | 1        | 1      | 5.26%   |
| Hitachi HDS721010CLA632 1TB     | 1        | 1      | 5.26%   |
| HGST HTS545050A7E380 500GB      | 1        | 1      | 5.26%   |
| Crucial CT120M500SSD1 120GB     | 1        | 4      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 9        | 12     | 52.94%  |
| Seagate | 3        | 4      | 17.65%  |
| Toshiba | 1        | 1      | 5.88%   |
| Teclast | 1        | 1      | 5.88%   |
| Hitachi | 1        | 1      | 5.88%   |
| HGST    | 1        | 1      | 5.88%   |
| Crucial | 1        | 4      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 9        | 12     | 60%     |
| Seagate | 3        | 4      | 20%     |
| Toshiba | 1        | 1      | 6.67%   |
| Hitachi | 1        | 1      | 6.67%   |
| HGST    | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 19     | 88.24%  |
| SSD  | 2        | 5      | 11.76%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD1002FAEX-00Z3A0 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 74       | 156    | 46.54%  |
| Works    | 67       | 161    | 42.14%  |
| Malfunc  | 17       | 24     | 10.69%  |
| Failed   | 1        | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 84       | 40%     |
| AMD                          | 43       | 20.48%  |
| Samsung Electronics          | 26       | 12.38%  |
| SanDisk                      | 13       | 6.19%   |
| ASMedia Technology           | 7        | 3.33%   |
| Phison Electronics           | 6        | 2.86%   |
| Silicon Motion               | 5        | 2.38%   |
| Micron/Crucial Technology    | 5        | 2.38%   |
| Kingston Technology Company  | 4        | 1.9%    |
| Marvell Technology Group     | 3        | 1.43%   |
| Toshiba America Info Systems | 2        | 0.95%   |
| Realtek Semiconductor        | 2        | 0.95%   |
| Adaptec                      | 2        | 0.95%   |
| Yangtze Memory Technologies  | 1        | 0.48%   |
| VIA Technologies             | 1        | 0.48%   |
| Shenzhen Longsys Electronics | 1        | 0.48%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.48%   |
| KIOXIA                       | 1        | 0.48%   |
| JMicron Technology           | 1        | 0.48%   |
| INNOGRIT                     | 1        | 0.48%   |
| Broadcom / LSI               | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 11.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 5.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 4.98%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.32%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 3.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.49%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 2.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.66%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 1.66%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.66%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 1.66%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.66%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 1.24%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 1.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.24%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.83%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.83%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 2        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.83%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.83%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.83%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.83%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.83%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 110      | 56.99%  |
| NVMe | 52       | 26.94%  |
| IDE  | 16       | 8.29%   |
| RAID | 11       | 5.7%    |
| SAS  | 4        | 2.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 88       | 66.67%  |
| AMD    | 44       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 4.55%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 3.03%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 3.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.27%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 2.27%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.52%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 1.52%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.52%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.52%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.52%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores  | 2        | 1.52%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.52%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.52%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.52%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 1.52%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.52%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.52%   |
| Intel Xeon W-2155 CPU @ 3.30GHz             | 1        | 0.76%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.76%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.76%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.76%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.76%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.76%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.76%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.76%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.76%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.76%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.76%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.76%   |
| Intel N95                                   | 1        | 0.76%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.76%   |
| Intel Core i9-7940X CPU @ 3.10GHz           | 1        | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 33       | 25%     |
| AMD Ryzen 5            | 16       | 12.12%  |
| Intel Core i7          | 15       | 11.36%  |
| Intel Xeon             | 12       | 9.09%   |
| Other                  | 9        | 6.82%   |
| AMD Ryzen 7            | 9        | 6.82%   |
| Intel Core i3          | 6        | 4.55%   |
| AMD Ryzen 9            | 5        | 3.79%   |
| Intel Celeron          | 3        | 2.27%   |
| Intel Pentium          | 2        | 1.52%   |
| Intel Core 2 Quad      | 2        | 1.52%   |
| AMD Ryzen Threadripper | 2        | 1.52%   |
| AMD FX                 | 2        | 1.52%   |
| AMD Athlon             | 2        | 1.52%   |
| AMD A10                | 2        | 1.52%   |
| Intel Pentium Gold     | 1        | 0.76%   |
| Intel Pentium Dual     | 1        | 0.76%   |
| Intel Pentium 4        | 1        | 0.76%   |
| Intel Core m3          | 1        | 0.76%   |
| Intel Core i9          | 1        | 0.76%   |
| Intel Atom             | 1        | 0.76%   |
| AMD Ryzen 5 PRO        | 1        | 0.76%   |
| AMD Ryzen 3            | 1        | 0.76%   |
| AMD PRO A10            | 1        | 0.76%   |
| AMD Phenom II X6       | 1        | 0.76%   |
| AMD Phenom II X4       | 1        | 0.76%   |
| AMD Opteron            | 1        | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 52       | 39.39%  |
| 6      | 27       | 20.45%  |
| 2      | 18       | 13.64%  |
| 8      | 15       | 11.36%  |
| 12     | 8        | 6.06%   |
| 16     | 6        | 4.55%   |
| 10     | 2        | 1.52%   |
| 24     | 1        | 0.76%   |
| 14     | 1        | 0.76%   |
| 3      | 1        | 0.76%   |
| 1      | 1        | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 131      | 99.24%  |
| 2      | 1        | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 83       | 62.88%  |
| 1      | 49       | 37.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 131      | 99.24%  |
| Unknown        | 1        | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 23.02%  |
| 0x306c3    | 12       | 8.63%   |
| 0x306a9    | 9        | 6.47%   |
| 0x906ea    | 8        | 5.76%   |
| 0x506e3    | 7        | 5.04%   |
| 0x08701021 | 6        | 4.32%   |
| 0x90672    | 4        | 2.88%   |
| 0x306e4    | 4        | 2.88%   |
| 0x206a7    | 4        | 2.88%   |
| 0x20655    | 4        | 2.88%   |
| 0x0a201016 | 3        | 2.16%   |
| 0x08701013 | 3        | 2.16%   |
| 0x06003106 | 3        | 2.16%   |
| 0x906e9    | 2        | 1.44%   |
| 0x906c0    | 2        | 1.44%   |
| 0x50654    | 2        | 1.44%   |
| 0x406f1    | 2        | 1.44%   |
| 0x0a20120a | 2        | 1.44%   |
| 0x0a201009 | 2        | 1.44%   |
| 0x06000852 | 2        | 1.44%   |
| 0xf41      | 1        | 0.72%   |
| 0xb06e0    | 1        | 0.72%   |
| 0xa0671    | 1        | 0.72%   |
| 0xa0655    | 1        | 0.72%   |
| 0x706a1    | 1        | 0.72%   |
| 0x6fd      | 1        | 0.72%   |
| 0x6fb      | 1        | 0.72%   |
| 0x1067a    | 1        | 0.72%   |
| 0x0a601203 | 1        | 0.72%   |
| 0x0a601201 | 1        | 0.72%   |
| 0x0a50000d | 1        | 0.72%   |
| 0x0a404102 | 1        | 0.72%   |
| 0x08600106 | 1        | 0.72%   |
| 0x0830104d | 1        | 0.72%   |
| 0x08301039 | 1        | 0.72%   |
| 0x08108109 | 1        | 0.72%   |
| 0x08101102 | 1        | 0.72%   |
| 0x08101016 | 1        | 0.72%   |
| 0x0800820d | 1        | 0.72%   |
| 0x08001138 | 1        | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 17       | 12.88%  |
| Haswell          | 16       | 12.12%  |
| Zen 2            | 14       | 10.61%  |
| KabyLake         | 13       | 9.85%   |
| Zen 3            | 10       | 7.58%   |
| Skylake          | 9        | 6.82%   |
| SandyBridge      | 6        | 4.55%   |
| Alderlake Hybrid | 6        | 4.55%   |
| Westmere         | 5        | 3.79%   |
| Unknown          | 5        | 3.79%   |
| Zen+             | 4        | 3.03%   |
| Zen              | 4        | 3.03%   |
| Steamroller      | 3        | 2.27%   |
| K10              | 3        | 2.27%   |
| Tremont          | 2        | 1.52%   |
| Piledriver       | 2        | 1.52%   |
| Core             | 2        | 1.52%   |
| CometLake        | 2        | 1.52%   |
| Broadwell        | 2        | 1.52%   |
| Silvermont       | 1        | 0.76%   |
| Penryn           | 1        | 0.76%   |
| NetBurst         | 1        | 0.76%   |
| Icelake          | 1        | 0.76%   |
| Goldmont plus    | 1        | 0.76%   |
| Goldmont         | 1        | 0.76%   |
| Excavator        | 1        | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 62       | 39.74%  |
| Intel             | 53       | 33.97%  |
| AMD               | 40       | 25.64%  |
| ASPEED Technology | 1        | 0.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.11%   |
| Intel HD Graphics 530                                                       | 5        | 3.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 3.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.48%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.48%   |
| Intel AlderLake-S GT1                                                       | 4        | 2.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.86%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.86%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 1.86%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.24%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.24%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.24%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.24%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.24%   |
| Nvidia GF119 [GeForce 605]                                                  | 2        | 1.24%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.24%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.24%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.24%   |
| AMD Raphael                                                                 | 2        | 1.24%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.24%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.24%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.24%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 1.24%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 2        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.62%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 49       | 35.51%  |
| 1 x Intel       | 40       | 28.99%  |
| 1 x AMD         | 31       | 22.46%  |
| Intel + Nvidia  | 5        | 3.62%   |
| 2 x Nvidia      | 4        | 2.9%    |
| Intel + AMD     | 3        | 2.17%   |
| AMD + Nvidia    | 3        | 2.17%   |
| 2 x AMD         | 2        | 1.45%   |
| Nvidia + ASPEED | 1        | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 85       | 62.96%  |
| Proprietary | 44       | 32.59%  |
| Unknown     | 6        | 4.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 38.41%  |
| 1.01-2.0   | 20       | 14.49%  |
| 7.01-8.0   | 16       | 11.59%  |
| 3.01-4.0   | 14       | 10.14%  |
| 8.01-16.0  | 12       | 8.7%    |
| 0.51-1.0   | 12       | 8.7%    |
| 5.01-6.0   | 6        | 4.35%   |
| 0.01-0.5   | 5        | 3.62%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 38       | 28.15%  |
| Samsung Electronics  | 15       | 11.11%  |
| Hewlett-Packard      | 11       | 8.15%   |
| Goldstar             | 9        | 6.67%   |
| Acer                 | 9        | 6.67%   |
| AOC                  | 6        | 4.44%   |
| Philips              | 5        | 3.7%    |
| ViewSonic            | 3        | 2.22%   |
| PRISM+               | 3        | 2.22%   |
| Denver               | 3        | 2.22%   |
| ASUSTek Computer     | 3        | 2.22%   |
| Pixio                | 2        | 1.48%   |
| Lenovo Group Limited | 2        | 1.48%   |
| Lenovo               | 2        | 1.48%   |
| AU Optronics         | 2        | 1.48%   |
| Ancor Communications | 2        | 1.48%   |
| Unknown              | 2        | 1.48%   |
| Xiaomi               | 1        | 0.74%   |
| Wacom                | 1        | 0.74%   |
| Unknown (XXX)        | 1        | 0.74%   |
| Toshiba              | 1        | 0.74%   |
| Sony                 | 1        | 0.74%   |
| Sharp                | 1        | 0.74%   |
| SGT                  | 1        | 0.74%   |
| SAC                  | 1        | 0.74%   |
| RTK                  | 1        | 0.74%   |
| MSI                  | 1        | 0.74%   |
| InnoView             | 1        | 0.74%   |
| HPN                  | 1        | 0.74%   |
| HPD                  | 1        | 0.74%   |
| HKC                  | 1        | 0.74%   |
| CVT                  | 1        | 0.74%   |
| CHR                  | 1        | 0.74%   |
| AUS                  | 1        | 0.74%   |
| AOpen                | 1        | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 4        | 2.82%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 2        | 1.41%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 2        | 1.41%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch                 | 2        | 1.41%   |
| Pixio U27I4K WAM2700 3840x2160 600x330mm 27.0-inch                      | 2        | 1.41%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                   | 2        | 1.41%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 2        | 1.41%   |
| Denver GB-2461CF LHC0236 1920x1080 530x280mm 23.6-inch                  | 2        | 1.41%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                     | 2        | 1.41%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                       | 2        | 1.41%   |
| Dell LCD Monitor P2217H 1920x1080                                       | 2        | 1.41%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                      | 2        | 1.41%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                       | 2        | 1.41%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                        | 2        | 1.41%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                        | 2        | 1.41%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                          | 2        | 1.41%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                        | 2        | 1.41%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                     | 2        | 1.41%   |
| Unknown                                                                 | 2        | 1.41%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                       | 1        | 0.7%    |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 0.7%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 0.7%    |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 530x300mm 24.0-inch               | 1        | 0.7%    |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                               | 1        | 0.7%    |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 0.7%    |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                       | 1        | 0.7%    |
| Sony TV SNY2C02 1920x1080 1218x685mm 55.0-inch                          | 1        | 0.7%    |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                        | 1        | 0.7%    |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                     | 1        | 0.7%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.7%    |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch       | 1        | 0.7%    |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.7%    |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0F18 3840x2160 1872x1053mm 84.6-inch | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                       | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                       | 1        | 0.7%    |
| Samsung Electronics LCD Monitor S27A950D 1920x1080                      | 1        | 0.7%    |
| Samsung Electronics LCD Monitor S24B350 1920x1080                       | 1        | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 50%     |
| 2560x1440 (QHD)    | 22       | 16.42%  |
| 3840x2160 (4K)     | 20       | 14.93%  |
| 1600x900 (HD+)     | 11       | 8.21%   |
| 2560x1600          | 2        | 1.49%   |
| 2560x1080          | 2        | 1.49%   |
| 1680x1050 (WSXGA+) | 2        | 1.49%   |
| 1366x768 (WXGA)    | 2        | 1.49%   |
| 1360x768           | 2        | 1.49%   |
| 1280x1024 (SXGA)   | 2        | 1.49%   |
| 3440x1440          | 1        | 0.75%   |
| 1440x900 (WXGA+)   | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 24       | 18.05%  |
| Unknown | 18       | 13.53%  |
| 23      | 17       | 12.78%  |
| 24      | 15       | 11.28%  |
| 21      | 13       | 9.77%   |
| 20      | 8        | 6.02%   |
| 31      | 6        | 4.51%   |
| 19      | 6        | 4.51%   |
| 18      | 4        | 3.01%   |
| 28      | 3        | 2.26%   |
| 15      | 3        | 2.26%   |
| 84      | 2        | 1.5%    |
| 40      | 2        | 1.5%    |
| 65      | 1        | 0.75%   |
| 55      | 1        | 0.75%   |
| 54      | 1        | 0.75%   |
| 50      | 1        | 0.75%   |
| 39      | 1        | 0.75%   |
| 34      | 1        | 0.75%   |
| 32      | 1        | 0.75%   |
| 26      | 1        | 0.75%   |
| 25      | 1        | 0.75%   |
| 22      | 1        | 0.75%   |
| 17      | 1        | 0.75%   |
| 16      | 1        | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 41.98%  |
| 401-500     | 30       | 22.9%   |
| Unknown     | 18       | 13.74%  |
| 601-700     | 10       | 7.63%   |
| 301-350     | 4        | 3.05%   |
| 1001-1500   | 4        | 3.05%   |
| 801-900     | 3        | 2.29%   |
| 351-400     | 3        | 2.29%   |
| 701-800     | 2        | 1.53%   |
| 1501-2000   | 2        | 1.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 102      | 80.31%  |
| Unknown | 16       | 12.6%   |
| 16/10   | 4        | 3.15%   |
| 5/4     | 2        | 1.57%   |
| 21/9    | 2        | 1.57%   |
| 6/5     | 1        | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 38       | 29.01%  |
| 301-350        | 24       | 18.32%  |
| 151-200        | 18       | 13.74%  |
| Unknown        | 18       | 13.74%  |
| 351-500        | 10       | 7.63%   |
| More than 1000 | 6        | 4.58%   |
| 251-300        | 6        | 4.58%   |
| 141-150        | 4        | 3.05%   |
| 101-110        | 4        | 3.05%   |
| 501-1000       | 3        | 2.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 69       | 51.49%  |
| 101-120 | 28       | 20.9%   |
| Unknown | 18       | 13.43%  |
| 161-240 | 8        | 5.97%   |
| 121-160 | 8        | 5.97%   |
| 1-50    | 3        | 2.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 84.06%  |
| 2     | 13       | 9.42%   |
| 0     | 8        | 5.8%    |
| 3     | 1        | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 79       | 40.72%  |
| Intel                 | 70       | 36.08%  |
| Qualcomm Atheros      | 11       | 5.67%   |
| TP-Link               | 8        | 4.12%   |
| Broadcom              | 6        | 3.09%   |
| MediaTek              | 4        | 2.06%   |
| ASUSTek Computer      | 3        | 1.55%   |
| Samsung Electronics   | 2        | 1.03%   |
| Ralink Technology     | 2        | 1.03%   |
| Aquantia              | 2        | 1.03%   |
| Qualcomm              | 1        | 0.52%   |
| Linksys               | 1        | 0.52%   |
| Hewlett-Packard       | 1        | 0.52%   |
| Fargo                 | 1        | 0.52%   |
| Exar                  | 1        | 0.52%   |
| Edimax Technology     | 1        | 0.52%   |
| ASIX Electronics      | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 26.01%  |
| Intel Wi-Fi 6 AX200                                               | 14       | 6.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 5.38%   |
| Intel Ethernet Controller I225-V                                  | 11       | 4.93%   |
| Intel I211 Gigabit Network Connection                             | 10       | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.14%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.24%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 1.35%   |
| Intel Wireless 3165                                               | 3        | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 1.35%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 3        | 1.35%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2        | 0.9%    |
| TP-Link Archer T4U ver.3                                          | 2        | 0.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.9%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.9%    |
| Realtek 802.11ac NIC                                              | 2        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.9%    |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.9%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.45%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.45%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.45%   |
| Qualcomm POCO M2 Pro                                              | 1        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 34       | 47.89%  |
| TP-Link               | 8        | 11.27%  |
| Realtek Semiconductor | 8        | 11.27%  |
| Qualcomm Atheros      | 6        | 8.45%   |
| MediaTek              | 4        | 5.63%   |
| Broadcom              | 4        | 5.63%   |
| ASUSTek Computer      | 3        | 4.23%   |
| Ralink Technology     | 2        | 2.82%   |
| Linksys               | 1        | 1.41%   |
| Edimax Technology     | 1        | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 14       | 19.44%  |
| Intel Alder Lake-S PCH CNVi WiFi                                | 4        | 5.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 3        | 4.17%   |
| Intel Wireless 3165                                             | 3        | 4.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 3        | 4.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 3        | 4.17%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3        | 4.17%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                      | 2        | 2.78%   |
| TP-Link Archer T4U ver.3                                        | 2        | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 2        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2        | 2.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                 | 2        | 2.78%   |
| Realtek 802.11ac NIC                                            | 2        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                 | 2        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 2        | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 2.78%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                           | 1        | 1.39%   |
| TP-Link 802.11ac WLAN Adapter                                   | 1        | 1.39%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 1.39%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 1.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter           | 1        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1        | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1        | 1.39%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 1        | 1.39%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter             | 1        | 1.39%   |
| Intel Wireless-AC 9260                                          | 1        | 1.39%   |
| Intel Wireless 8260                                             | 1        | 1.39%   |
| Intel Wireless 7265                                             | 1        | 1.39%   |
| Intel Wireless 7260                                             | 1        | 1.39%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 1        | 1.39%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1        | 1.39%   |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 1.39%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.39%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter              | 1        | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 74       | 51.75%  |
| Intel                 | 55       | 38.46%  |
| Qualcomm Atheros      | 5        | 3.5%    |
| Samsung Electronics   | 2        | 1.4%    |
| Broadcom              | 2        | 1.4%    |
| Aquantia              | 2        | 1.4%    |
| Qualcomm              | 1        | 0.7%    |
| Hewlett-Packard       | 1        | 0.7%    |
| ASIX Electronics      | 1        | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 58       | 38.93%  |
| Realtek RTL8125 2.5GbE Controller                                  | 12       | 8.05%   |
| Intel Ethernet Controller I225-V                                   | 11       | 7.38%   |
| Intel I211 Gigabit Network Connection                              | 10       | 6.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7        | 4.7%    |
| Intel Ethernet Connection (2) I219-V                               | 5        | 3.36%   |
| Intel Ethernet Connection I217-LM                                  | 4        | 2.68%   |
| Intel Ethernet Connection I217-V                                   | 3        | 2.01%   |
| Intel Ethernet Connection (2) I219-LM                              | 3        | 2.01%   |
| Samsung Galaxy series, misc. (tethering mode)                      | 2        | 1.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2        | 1.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 2        | 1.34%   |
| Intel Ethernet Connection (2) I218-V                               | 2        | 1.34%   |
| Intel 82578DM Gigabit Network Connection                           | 2        | 1.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                    | 1        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1        | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                              | 1        | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                         | 1        | 0.67%   |
| Qualcomm POCO M2 Pro                                               | 1        | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1        | 0.67%   |
| Intel I350 Gigabit Network Connection                              | 1        | 0.67%   |
| Intel I210 Gigabit Network Connection                              | 1        | 0.67%   |
| Intel Ethernet Controller X550                                     | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                               | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                              | 1        | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                              | 1        | 0.67%   |
| Intel Ethernet Connection (2) I218-LM                              | 1        | 0.67%   |
| Intel Ethernet Connection (14) I219-V                              | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-V                              | 1        | 0.67%   |
| Intel 82583V Gigabit Network Connection                            | 1        | 0.67%   |
| Intel 82579V Gigabit Network Connection                            | 1        | 0.67%   |
| Intel 82566DC-2 Gigabit Network Connection                         | 1        | 0.67%   |
| HP lt4120 Snapdragon X5 LTE                                        | 1        | 0.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                  | 1        | 0.67%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                   | 1        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                      | 1        | 0.67%   |
| Aquantia AQC113C NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.67%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 132      | 64.71%  |
| WiFi     | 70       | 34.31%  |
| Modem    | 1        | 0.49%   |
| Unknown  | 1        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 102      | 71.83%  |
| WiFi     | 39       | 27.46%  |
| Unknown  | 1        | 0.7%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 53.03%  |
| 2     | 57       | 43.18%  |
| 3     | 4        | 3.03%   |
| 0     | 1        | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 125      | 94.7%   |
| Yes  | 7        | 5.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 51.79%  |
| Cambridge Silicon Radio         | 10       | 17.86%  |
| TP-Link                         | 5        | 8.93%   |
| MediaTek                        | 4        | 7.14%   |
| Realtek Semiconductor           | 3        | 5.36%   |
| Qualcomm Atheros Communications | 3        | 5.36%   |
| SINO WEALTH                     | 1        | 1.79%   |
| Broadcom                        | 1        | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 11       | 19.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10       | 17.86%  |
| Intel Bluetooth wireless interface                  | 7        | 12.5%   |
| TP-Link UB5A Adapter                                | 5        | 8.93%   |
| MediaTek Wireless_Device                            | 4        | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 5.36%   |
| Intel AX201 Bluetooth                               | 3        | 5.36%   |
| Realtek Bluetooth Radio                             | 2        | 3.57%   |
| Intel Bluetooth Device                              | 2        | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 3.57%   |
| Intel AX210 Bluetooth                               | 2        | 3.57%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 86       | 38.39%  |
| Nvidia                                       | 59       | 26.34%  |
| AMD                                          | 49       | 21.88%  |
| C-Media Electronics                          | 4        | 1.79%   |
| SteelSeries ApS                              | 2        | 0.89%   |
| Creative Labs                                | 2        | 0.89%   |
| ASUSTek Computer                             | 2        | 0.89%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.45%   |
| XMOS                                         | 1        | 0.45%   |
| TTGK Technology                              | 1        | 0.45%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.45%   |
| Tenx Technology                              | 1        | 0.45%   |
| Sony                                         | 1        | 0.45%   |
| Setek Elektronik                             | 1        | 0.45%   |
| Sennheiser Communications                    | 1        | 0.45%   |
| SAVITECH                                     | 1        | 0.45%   |
| Samson Technologies                          | 1        | 0.45%   |
| RODE Microphones                             | 1        | 0.45%   |
| Realtek Semiconductor                        | 1        | 0.45%   |
| MV                                           | 1        | 0.45%   |
| Micro Star International                     | 1        | 0.45%   |
| Logitech                                     | 1        | 0.45%   |
| JMTek                                        | 1        | 0.45%   |
| Huawei Technologies                          | 1        | 0.45%   |
| Giga-Byte Technology                         | 1        | 0.45%   |
| FiiO Electronics Technology                  | 1        | 0.45%   |
| BR23                                         | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 21       | 8.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 4.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 3.07%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 3.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.3%    |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 2.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.53%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.53%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.15%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.77%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.77%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 17       | 18.28%  |
| Corsair                        | 11       | 11.83%  |
| Crucial                        | 10       | 10.75%  |
| Samsung Electronics            | 8        | 8.6%    |
| G.Skill                        | 8        | 8.6%    |
| SK hynix                       | 7        | 7.53%   |
| Micron Technology              | 7        | 7.53%   |
| KLEVV                          | 4        | 4.3%    |
| A-DATA Technology              | 3        | 3.23%   |
| Unknown (ABCD)                 | 2        | 2.15%   |
| Transcend                      | 2        | 2.15%   |
| Kingmax                        | 2        | 2.15%   |
| Unknown (0x0E9D)               | 1        | 1.08%   |
| Unknown (0x0B92)               | 1        | 1.08%   |
| Unknown                        | 1        | 1.08%   |
| Qimonda                        | 1        | 1.08%   |
| Patriot                        | 1        | 1.08%   |
| Nanya Technology               | 1        | 1.08%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 1.08%   |
| Lexar                          | 1        | 1.08%   |
| Essencore Limited              | 1        | 1.08%   |
| Elpida                         | 1        | 1.08%   |
| ASint Technology               | 1        | 1.08%   |
| Unknown                        | 1        | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s      | 2        | 1.9%    |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                      | 2        | 1.9%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 2        | 1.9%    |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s               | 2        | 1.9%    |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s              | 2        | 1.9%    |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s                 | 2        | 1.9%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                         | 2        | 1.9%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                                | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1        | 0.95%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s    | 1        | 0.95%   |
| Unknown (0x0B92) RAM Module 16GB DIMM DDR4 3200MT/s                 | 1        | 0.95%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                    | 1        | 0.95%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                   | 1        | 0.95%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1        | 0.95%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 0.95%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1        | 0.95%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s                     | 1        | 0.95%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2400MT/s                | 1        | 0.95%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1        | 0.95%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1        | 0.95%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s               | 1        | 0.95%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s                 | 1        | 0.95%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s              | 1        | 0.95%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                 | 1        | 0.95%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1        | 0.95%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1        | 0.95%   |
| Samsung RAM M378A2K43CB1-CRC 16GB DIMM DDR4 2400MT/s                | 1        | 0.95%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                 | 1        | 0.95%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                 | 1        | 0.95%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                    | 1        | 0.95%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s                 | 1        | 0.95%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s               | 1        | 0.95%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER RAM Module 2048MB DIMM DDR3 1600MT/s | 1        | 0.95%   |
| Micron RAM TEAMGROUP-UD4-2133 16384MB DIMM DDR4 2134MT/s            | 1        | 0.95%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                 | 1        | 0.95%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                  | 1        | 0.95%   |
| Micron RAM 36KSF2G72PZ-1G6N1 16GB DIMM DDR3 1600MT/s                | 1        | 0.95%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s                | 1        | 0.95%   |
| Micron RAM 16KTF1G64HZ-1G6J1 8GB SODIMM DDR3 1600MT/s               | 1        | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 47       | 55.95%  |
| DDR3    | 24       | 28.57%  |
| SDRAM   | 4        | 4.76%   |
| DDR5    | 4        | 4.76%   |
| LPDDR4  | 2        | 2.38%   |
| DDR2    | 2        | 2.38%   |
| Unknown | 1        | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 74       | 92.5%   |
| SODIMM | 6        | 7.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 29       | 32.22%  |
| 8192  | 28       | 31.11%  |
| 4096  | 18       | 20%     |
| 32768 | 7        | 7.78%   |
| 2048  | 7        | 7.78%   |
| 1024  | 1        | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 17       | 17.71%  |
| 3200  | 14       | 14.58%  |
| 2400  | 13       | 13.54%  |
| 3600  | 9        | 9.38%   |
| 1333  | 5        | 5.21%   |
| 2667  | 4        | 4.17%   |
| 2666  | 4        | 4.17%   |
| 2133  | 3        | 3.13%   |
| 3733  | 2        | 2.08%   |
| 3666  | 2        | 2.08%   |
| 3400  | 2        | 2.08%   |
| 3266  | 2        | 2.08%   |
| 2048  | 2        | 2.08%   |
| 1867  | 2        | 2.08%   |
| 1866  | 2        | 2.08%   |
| 1800  | 2        | 2.08%   |
| 7000  | 1        | 1.04%   |
| 5808  | 1        | 1.04%   |
| 5200  | 1        | 1.04%   |
| 4800  | 1        | 1.04%   |
| 4333  | 1        | 1.04%   |
| 4000  | 1        | 1.04%   |
| 3800  | 1        | 1.04%   |
| 2200  | 1        | 1.04%   |
| 2134  | 1        | 1.04%   |
| 1067  | 1        | 1.04%   |
| 667   | 1        | 1.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Philips (or NXP)    | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung M2020 Series         | 1        | 50%     |
| Philips (or NXP) USB Printer | 1        | 50%     |

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
| Logitech              | 7        | 50%     |
| Realtek Semiconductor | 2        | 14.29%  |
| Microdia              | 2        | 14.29%  |
| Samsung Electronics   | 1        | 7.14%   |
| Apple                 | 1        | 7.14%   |
| Alcor Micro           | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 3        | 21.43%  |
| Logitech HD Webcam C615                 | 2        | 14.29%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 7.14%   |
| Realtek HP 1.0MP High Definition Webcam | 1        | 7.14%   |
| Realtek Asus laptop camera              | 1        | 7.14%   |
| Microdia Webcam Vitade AF               | 1        | 7.14%   |
| Microdia USB 2.0 Camera                 | 1        | 7.14%   |
| Logitech Webcam C310                    | 1        | 7.14%   |
| Logitech Webcam C270                    | 1        | 7.14%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 1        | 7.14%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 7.14%   |

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
| 0     | 111      | 83.46%  |
| 1     | 21       | 15.79%  |
| 2     | 1        | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 7        | 30.43%  |
| Graphics card            | 7        | 30.43%  |
| Unassigned class         | 2        | 8.7%    |
| Network                  | 2        | 8.7%    |
| Communication controller | 2        | 8.7%    |
| Net/ethernet             | 1        | 4.35%   |
| Multimedia controller    | 1        | 4.35%   |
| Dvb card                 | 1        | 4.35%   |

