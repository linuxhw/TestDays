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

Total: 190

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [d16f2b19b0](https://linux-hardware.org/?probe=d16f2b19b0) | Oct 30, 2023 |
| MACHINIST     | B75 PRO V1.0                | [8927fc6f11](https://linux-hardware.org/?probe=8927fc6f11) | Oct 27, 2023 |
| MSI           | B85M-E45                    | [acc8588daa](https://linux-hardware.org/?probe=acc8588daa) | Oct 16, 2023 |
| SZMZ          | X99M-G2                     | [1b0f7ae9a7](https://linux-hardware.org/?probe=1b0f7ae9a7) | Oct 15, 2023 |
| HP            | 82F2                        | [6a5c62ec30](https://linux-hardware.org/?probe=6a5c62ec30) | Oct 12, 2023 |
| HP            | 82F2                        | [ebf3c3339a](https://linux-hardware.org/?probe=ebf3c3339a) | Oct 12, 2023 |
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
| Ubuntu 20.04                 | 22       | 14.86%  |
| Ubuntu 18.04                 | 15       | 10.14%  |
| Ubuntu 22.04                 | 12       | 8.11%   |
| Arch Rolling                 | 7        | 4.73%   |
| Linux Mint 21                | 5        | 3.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 2.7%    |
| Manjaro                      | 4        | 2.7%    |
| KDE neon 20.04               | 4        | 2.7%    |
| Fedora 38                    | 4        | 2.7%    |
| Pop!_OS 20.04                | 3        | 2.03%   |
| OpenMandriva 23.03           | 3        | 2.03%   |
| Debian 11                    | 3        | 2.03%   |
| ArcoLinux Rolling            | 3        | 2.03%   |
| Ubuntu 21.04                 | 2        | 1.35%   |
| Rocky Linux 8.5              | 2        | 1.35%   |
| Pop!_OS 21.04                | 2        | 1.35%   |
| OpenMandriva 4.50            | 2        | 1.35%   |
| OpenMandriva 4.3             | 2        | 1.35%   |
| MX 21                        | 2        | 1.35%   |
| Linux Mint 20.3              | 2        | 1.35%   |
| Linux Mint 20                | 2        | 1.35%   |
| Fedora 37                    | 2        | 1.35%   |
| Fedora 33                    | 2        | 1.35%   |
| Debian 12                    | 2        | 1.35%   |
| Arch                         | 2        | 1.35%   |
| Zorin 16                     | 1        | 0.68%   |
| Xubuntu 23.04                | 1        | 0.68%   |
| Xubuntu 20.04                | 1        | 0.68%   |
| Ubuntu Unity 20.04           | 1        | 0.68%   |
| Ubuntu Unity 16.04           | 1        | 0.68%   |
| Ubuntu MATE 20.04            | 1        | 0.68%   |
| Ubuntu Kylin 22.04           | 1        | 0.68%   |
| Ubuntu 23.04                 | 1        | 0.68%   |
| Ubuntu 22.10                 | 1        | 0.68%   |
| Ubuntu 19.10                 | 1        | 0.68%   |
| Ubuntu 19.04                 | 1        | 0.68%   |
| Ubuntu 18.10                 | 1        | 0.68%   |
| Rocky Linux 8.7              | 1        | 0.68%   |
| Rocky Linux 8.4              | 1        | 0.68%   |
| Pop!_OS 22.04                | 1        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 54       | 39.13%  |
| OpenMandriva | 10       | 7.25%   |
| Linux Mint   | 10       | 7.25%   |
| Arch         | 9        | 6.52%   |
| Fedora       | 8        | 5.8%    |
| Pop!_OS      | 7        | 5.07%   |
| Debian       | 6        | 4.35%   |
| Manjaro      | 5        | 3.62%   |
| openSUSE     | 4        | 2.9%    |
| KDE neon     | 4        | 2.9%    |
| Rocky Linux  | 3        | 2.17%   |
| ArcoLinux    | 3        | 2.17%   |
| Xubuntu      | 2        | 1.45%   |
| Ubuntu Unity | 2        | 1.45%   |
| MX           | 2        | 1.45%   |
| Zorin        | 1        | 0.72%   |
| Ubuntu MATE  | 1        | 0.72%   |
| Ubuntu Kylin | 1        | 0.72%   |
| Lubuntu      | 1        | 0.72%   |
| Gentoo       | 1        | 0.72%   |
| Garuda Linux | 1        | 0.72%   |
| EndeavourOS  | 1        | 0.72%   |
| CentOS       | 1        | 0.72%   |
| Atz          | 1        | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.0-56-generic            | 7        | 4.32%   |
| 5.15.0-46-generic            | 4        | 2.47%   |
| 6.2.6-desktop-1omv2390       | 3        | 1.85%   |
| 5.4.0-29-generic             | 3        | 1.85%   |
| 5.15.0-58-generic            | 3        | 1.85%   |
| 6.3.8-zen1-1-zen             | 2        | 1.23%   |
| 6.2.14-300.fc38.x86_64       | 2        | 1.23%   |
| 6.2.0-34-generic             | 2        | 1.23%   |
| 6.2.0-31-generic             | 2        | 1.23%   |
| 6.0.15-300.fc37.x86_64       | 2        | 1.23%   |
| 5.9.8-200.fc33.x86_64        | 2        | 1.23%   |
| 5.4.0-7642-generic           | 2        | 1.23%   |
| 5.4.0-70-generic             | 2        | 1.23%   |
| 5.4.0-42-generic             | 2        | 1.23%   |
| 5.4.0-40-generic             | 2        | 1.23%   |
| 5.4.0-37-generic             | 2        | 1.23%   |
| 5.3.0-51-generic             | 2        | 1.23%   |
| 5.19.0-35-generic            | 2        | 1.23%   |
| 5.16.7-desktop-1omv4003      | 2        | 1.23%   |
| 5.15.0-71-generic            | 2        | 1.23%   |
| 5.15.0-52-generic            | 2        | 1.23%   |
| 5.12.7-desktop-1omv4003      | 2        | 1.23%   |
| 5.11.0-27-generic            | 2        | 1.23%   |
| 5.0.0-36-generic             | 2        | 1.23%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2        | 1.23%   |
| 6.5.9-1-default              | 1        | 0.62%   |
| 6.5.8-200.fc38.x86_64        | 1        | 0.62%   |
| 6.4.7-desktop-1omv2390       | 1        | 0.62%   |
| 6.4.6-76060406-generic       | 1        | 0.62%   |
| 6.4.3-zen1-1-zen             | 1        | 0.62%   |
| 6.4.12-200.fc38.x86_64       | 1        | 0.62%   |
| 6.4.10-200.fc38.x86_64       | 1        | 0.62%   |
| 6.3.9-zen1-1-zen             | 1        | 0.62%   |
| 6.3.9-1-default              | 1        | 0.62%   |
| 6.3.8-200.fc38.x86_64        | 1        | 0.62%   |
| 6.3.7-zen1-1-zen             | 1        | 0.62%   |
| 6.3.5-desktop-3omv2390       | 1        | 0.62%   |
| 6.3.4-201.fc38.x86_64        | 1        | 0.62%   |
| 6.3.0.11.realtime1-1-rt      | 1        | 0.62%   |
| 6.2.9-300.fc38.x86_64        | 1        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 24       | 15.38%  |
| 5.15.0   | 24       | 15.38%  |
| 6.2.0    | 7        | 4.49%   |
| 5.0.0    | 7        | 4.49%   |
| 5.11.0   | 6        | 3.85%   |
| 5.10.0   | 5        | 3.21%   |
| 4.18.0   | 5        | 3.21%   |
| 4.15.0   | 4        | 2.56%   |
| 6.3.8    | 3        | 1.92%   |
| 6.2.6    | 3        | 1.92%   |
| 5.8.0    | 3        | 1.92%   |
| 5.3.0    | 3        | 1.92%   |
| 5.19.0   | 3        | 1.92%   |
| 6.3.9    | 2        | 1.28%   |
| 6.2.14   | 2        | 1.28%   |
| 6.1.0    | 2        | 1.28%   |
| 6.0.15   | 2        | 1.28%   |
| 5.9.8    | 2        | 1.28%   |
| 5.16.7   | 2        | 1.28%   |
| 5.13.0   | 2        | 1.28%   |
| 5.12.7   | 2        | 1.28%   |
| 6.5.9    | 1        | 0.64%   |
| 6.5.8    | 1        | 0.64%   |
| 6.4.7    | 1        | 0.64%   |
| 6.4.6    | 1        | 0.64%   |
| 6.4.3    | 1        | 0.64%   |
| 6.4.12   | 1        | 0.64%   |
| 6.4.10   | 1        | 0.64%   |
| 6.3.7    | 1        | 0.64%   |
| 6.3.5    | 1        | 0.64%   |
| 6.3.4    | 1        | 0.64%   |
| 6.3.0.11 | 1        | 0.64%   |
| 6.2.9    | 1        | 0.64%   |
| 6.2.2    | 1        | 0.64%   |
| 6.1.6    | 1        | 0.64%   |
| 6.1.53   | 1        | 0.64%   |
| 6.1.4    | 1        | 0.64%   |
| 6.1.39   | 1        | 0.64%   |
| 6.1.1    | 1        | 0.64%   |
| 6.0.2    | 1        | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 31       | 20%     |
| 5.4     | 24       | 15.48%  |
| 6.2     | 13       | 8.39%   |
| 6.3     | 8        | 5.16%   |
| 6.1     | 7        | 4.52%   |
| 5.11    | 7        | 4.52%   |
| 5.10    | 7        | 4.52%   |
| 5.0     | 7        | 4.52%   |
| 6.4     | 5        | 3.23%   |
| 4.18    | 5        | 3.23%   |
| 6.0     | 4        | 2.58%   |
| 5.8     | 4        | 2.58%   |
| 5.16    | 4        | 2.58%   |
| 5.13    | 4        | 2.58%   |
| 4.15    | 4        | 2.58%   |
| 5.9     | 3        | 1.94%   |
| 5.3     | 3        | 1.94%   |
| 5.19    | 3        | 1.94%   |
| 5.12    | 3        | 1.94%   |
| 6.5     | 2        | 1.29%   |
| 5.14    | 2        | 1.29%   |
| 6.3.0   | 1        | 0.65%   |
| 5.18    | 1        | 0.65%   |
| 5.17    | 1        | 0.65%   |
| 4.16    | 1        | 0.65%   |
| 3.10    | 1        | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 136      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 62       | 43.97%  |
| KDE5          | 23       | 16.31%  |
| Unknown       | 22       | 15.6%   |
| X-Cinnamon    | 12       | 8.51%   |
| XFCE          | 9        | 6.38%   |
| LXQt          | 3        | 2.13%   |
| Unity         | 2        | 1.42%   |
| i3            | 2        | 1.42%   |
| UKUI          | 1        | 0.71%   |
| MATE          | 1        | 0.71%   |
| KDE           | 1        | 0.71%   |
| GNOME Classic | 1        | 0.71%   |
| Cinnamon      | 1        | 0.71%   |
| Budgie        | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 110      | 77.46%  |
| Wayland | 16       | 11.27%  |
| Tty     | 8        | 5.63%   |
| Unknown | 8        | 5.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 66       | 47.48%  |
| SDDM    | 22       | 15.83%  |
| GDM3    | 18       | 12.95%  |
| GDM     | 18       | 12.95%  |
| LightDM | 13       | 9.35%   |
| TDM     | 1        | 0.72%   |
| GREETD  | 1        | 0.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 55       | 39.29%  |
| en_SG   | 53       | 37.86%  |
| Unknown | 10       | 7.14%   |
| zh_CN   | 7        | 5%      |
| en_AU   | 4        | 2.86%   |
| de_DE   | 3        | 2.14%   |
| C       | 3        | 2.14%   |
| en_GB   | 2        | 1.43%   |
| fr_FR   | 1        | 0.71%   |
| en_PH   | 1        | 0.71%   |
| en_IN   | 1        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 80       | 58.82%  |
| BIOS | 56       | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 96       | 69.06%  |
| Btrfs   | 19       | 13.67%  |
| Overlay | 10       | 7.19%   |
| Xfs     | 8        | 5.76%   |
| Tmpfs   | 3        | 2.16%   |
| Unknown | 3        | 2.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 68       | 49.64%  |
| Unknown | 57       | 41.61%  |
| MBR     | 12       | 8.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 76.26%  |
| Yes       | 33       | 23.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 61.59%  |
| Yes       | 53       | 38.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 26       | 19.12%  |
| Gigabyte Technology                  | 24       | 17.65%  |
| MSI                                  | 19       | 13.97%  |
| Dell                                 | 17       | 12.5%   |
| ASRock                               | 14       | 10.29%  |
| Hewlett-Packard                      | 7        | 5.15%   |
| Lenovo                               | 5        | 3.68%   |
| Foxconn                              | 4        | 2.94%   |
| Unknown                              | 3        | 2.21%   |
| AZW                                  | 2        | 1.47%   |
| Acer                                 | 2        | 1.47%   |
| SZMZ                                 | 1        | 0.74%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.74%   |
| Pegatron                             | 1        | 0.74%   |
| Novatte                              | 1        | 0.74%   |
| MECHREVO                             | 1        | 0.74%   |
| MACHINIST                            | 1        | 0.74%   |
| LattePanda                           | 1        | 0.74%   |
| Intel                                | 1        | 0.74%   |
| Huanan                               | 1        | 0.74%   |
| HPE                                  | 1        | 0.74%   |
| ECS                                  | 1        | 0.74%   |
| Biostar                              | 1        | 0.74%   |
| AMI                                  | 1        | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 5        | 3.68%   |
| Gigabyte X570 AORUS PRO WIFI               | 4        | 2.94%   |
| MSI MS-7C84                                | 3        | 2.21%   |
| Foxconn Pro 3330 MT                        | 3        | 2.21%   |
| Dell OptiPlex 9020                         | 3        | 2.21%   |
| Unknown                                    | 3        | 2.21%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 1.47%   |
| Dell OptiPlex 990                          | 2        | 1.47%   |
| ASUS ROG STRIX B550-I GAMING               | 2        | 1.47%   |
| ASRock B450 Pro4                           | 2        | 1.47%   |
| SZMZ X99M-H2                               | 1        | 0.74%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.74%   |
| Pegatron 23-d018d                          | 1        | 0.74%   |
| Novatte M20                                | 1        | 0.74%   |
| MSI MS-7E06                                | 1        | 0.74%   |
| MSI MS-7D43                                | 1        | 0.74%   |
| MSI MS-7D42                                | 1        | 0.74%   |
| MSI MS-7D30                                | 1        | 0.74%   |
| MSI MS-7D25                                | 1        | 0.74%   |
| MSI MS-7C95                                | 1        | 0.74%   |
| MSI MS-7C91                                | 1        | 0.74%   |
| MSI MS-7C52                                | 1        | 0.74%   |
| MSI MS-7C02                                | 1        | 0.74%   |
| MSI MS-7B89                                | 1        | 0.74%   |
| MSI MS-7A94                                | 1        | 0.74%   |
| MSI MS-7A32                                | 1        | 0.74%   |
| MSI MS-7821                                | 1        | 0.74%   |
| MSI MS-7817                                | 1        | 0.74%   |
| MSI MS-7721                                | 1        | 0.74%   |
| MSI KT308AA-AB4 SR5472CF                   | 1        | 0.74%   |
| MECHREVO F7BFD V1.0                        | 1        | 0.74%   |
| MACHINIST B75 PRO V1.0                     | 1        | 0.74%   |
| Lenovo ThinkStation P620 30E1S3VH00        | 1        | 0.74%   |
| Lenovo ThinkStation P310 30ASS2WG00        | 1        | 0.74%   |
| Lenovo ThinkCentre M90p 5864BM3            | 1        | 0.74%   |
| Lenovo ThinkCentre M73 10AXS26C00          | 1        | 0.74%   |
| Lenovo ThinkCentre M72e 36601Y8            | 1        | 0.74%   |
| LattePanda Alpha                           | 1        | 0.74%   |
| Intel Jasper Lake Client Platform          | 1        | 0.74%   |
| Huanan X99-4MT V1.0                        | 1        | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 11       | 8.09%   |
| ASUS ROG                                   | 6        | 4.41%   |
| ASUS All                                   | 5        | 3.68%   |
| Gigabyte X570                              | 4        | 2.94%   |
| MSI MS-7C84                                | 3        | 2.21%   |
| Lenovo ThinkCentre                         | 3        | 2.21%   |
| Foxconn Pro                                | 3        | 2.21%   |
| Dell Precision                             | 3        | 2.21%   |
| Unknown                                    | 3        | 2.21%   |
| Lenovo ThinkStation                        | 2        | 1.47%   |
| HP ProDesk                                 | 2        | 1.47%   |
| Gigabyte B550I                             | 2        | 1.47%   |
| Gigabyte B450M                             | 2        | 1.47%   |
| Gigabyte B365M                             | 2        | 1.47%   |
| ASUS PRIME                                 | 2        | 1.47%   |
| ASRock B450                                | 2        | 1.47%   |
| SZMZ X99M-H2                               | 1        | 0.74%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.74%   |
| Pegatron 23-d018d                          | 1        | 0.74%   |
| Novatte M20                                | 1        | 0.74%   |
| MSI MS-7E06                                | 1        | 0.74%   |
| MSI MS-7D43                                | 1        | 0.74%   |
| MSI MS-7D42                                | 1        | 0.74%   |
| MSI MS-7D30                                | 1        | 0.74%   |
| MSI MS-7D25                                | 1        | 0.74%   |
| MSI MS-7C95                                | 1        | 0.74%   |
| MSI MS-7C91                                | 1        | 0.74%   |
| MSI MS-7C52                                | 1        | 0.74%   |
| MSI MS-7C02                                | 1        | 0.74%   |
| MSI MS-7B89                                | 1        | 0.74%   |
| MSI MS-7A94                                | 1        | 0.74%   |
| MSI MS-7A32                                | 1        | 0.74%   |
| MSI MS-7821                                | 1        | 0.74%   |
| MSI MS-7817                                | 1        | 0.74%   |
| MSI MS-7721                                | 1        | 0.74%   |
| MSI KT308AA-AB4                            | 1        | 0.74%   |
| MECHREVO F7BFD                             | 1        | 0.74%   |
| MACHINIST B75                              | 1        | 0.74%   |
| LattePanda Alpha                           | 1        | 0.74%   |
| Intel Jasper                               | 1        | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 17       | 12.5%   |
| 2020 | 16       | 11.76%  |
| 2018 | 16       | 11.76%  |
| 2019 | 13       | 9.56%   |
| 2021 | 10       | 7.35%   |
| 2012 | 9        | 6.62%   |
| 2011 | 9        | 6.62%   |
| 2016 | 7        | 5.15%   |
| 2014 | 7        | 5.15%   |
| 2022 | 6        | 4.41%   |
| 2010 | 6        | 4.41%   |
| 2023 | 5        | 3.68%   |
| 2017 | 5        | 3.68%   |
| 2015 | 5        | 3.68%   |
| 2008 | 2        | 1.47%   |
| 2007 | 2        | 1.47%   |
| 2009 | 1        | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 136      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 133      | 97.79%  |
| Enabled  | 3        | 2.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 136      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 33       | 23.74%  |
| 32.01-64.0      | 28       | 20.14%  |
| 4.01-8.0        | 25       | 17.99%  |
| 8.01-16.0       | 22       | 15.83%  |
| 64.01-256.0     | 12       | 8.63%   |
| 3.01-4.0        | 8        | 5.76%   |
| 24.01-32.0      | 7        | 5.04%   |
| More than 256.0 | 2        | 1.44%   |
| 1.01-2.0        | 2        | 1.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 43       | 28.86%  |
| 2.01-3.0   | 33       | 22.15%  |
| 3.01-4.0   | 31       | 20.81%  |
| 4.01-8.0   | 23       | 15.44%  |
| 8.01-16.0  | 9        | 6.04%   |
| 0.51-1.0   | 6        | 4.03%   |
| 16.01-24.0 | 2        | 1.34%   |
| 32.01-64.0 | 1        | 0.67%   |
| 0.01-0.5   | 1        | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 36.36%  |
| 2      | 40       | 27.97%  |
| 3      | 26       | 18.18%  |
| 4      | 15       | 10.49%  |
| 5      | 7        | 4.9%    |
| 0      | 2        | 1.4%    |
| 6      | 1        | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 67.88%  |
| Yes       | 44       | 32.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 136      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 74       | 52.48%  |
| No        | 67       | 47.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 59.85%  |
| Yes       | 55       | 40.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 136      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 128      | 93.43%  |
| Kampong Pasir Ris | 5        | 3.65%   |
| Jurong West       | 3        | 2.19%   |
| Queenstown Estate | 1        | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 46       | 74     | 17.9%   |
| Seagate                      | 39       | 50     | 15.18%  |
| WDC                          | 36       | 64     | 14.01%  |
| Toshiba                      | 21       | 27     | 8.17%   |
| SanDisk                      | 17       | 21     | 6.61%   |
| Crucial                      | 10       | 14     | 3.89%   |
| Unknown                      | 8        | 8      | 3.11%   |
| Kingston                     | 8        | 12     | 3.11%   |
| Hitachi                      | 7        | 8      | 2.72%   |
| Silicon Motion               | 3        | 5      | 1.17%   |
| Phison Electronics           | 3        | 4      | 1.17%   |
| Phison                       | 3        | 3      | 1.17%   |
| Micron/Crucial Technology    | 3        | 4      | 1.17%   |
| JMicron Technology           | 3        | 4      | 1.17%   |
| Intel                        | 3        | 3      | 1.17%   |
| HGST                         | 3        | 5      | 1.17%   |
| China                        | 3        | 3      | 1.17%   |
| A-DATA Technology            | 3        | 3      | 1.17%   |
| Transcend                    | 2        | 2      | 0.78%   |
| SK hynix                     | 2        | 2      | 0.78%   |
| Plextor                      | 2        | 2      | 0.78%   |
| Maxtor                       | 2        | 2      | 0.78%   |
| Lexar                        | 2        | 2      | 0.78%   |
| KLEVV                        | 2        | 2      | 0.78%   |
| Kingston Technology Company  | 2        | 2      | 0.78%   |
| Hewlett-Packard              | 2        | 2      | 0.78%   |
| Yangtze Memory Technologies  | 1        | 1      | 0.39%   |
| WALRAM                       | 1        | 1      | 0.39%   |
| Vaseky                       | 1        | 1      | 0.39%   |
| USB30                        | 1        | 1      | 0.39%   |
| Teclast                      | 1        | 1      | 0.39%   |
| SSK                          | 1        | 1      | 0.39%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.39%   |
| SABRENT                      | 1        | 2      | 0.39%   |
| Pioneer                      | 1        | 1      | 0.39%   |
| OCZ                          | 1        | 1      | 0.39%   |
| Mushkin                      | 1        | 1      | 0.39%   |
| MARVELL                      | 1        | 1      | 0.39%   |
| LITEONIT                     | 1        | 1      | 0.39%   |
| KIOXIA-EXCERIA               | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 8        | 2.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 6        | 2.02%   |
| Toshiba DT01ACA200 2TB                                | 5        | 1.68%   |
| Samsung SSD 850 EVO 250GB                             | 5        | 1.68%   |
| Seagate ST1000DM010-2EP102 1TB                        | 4        | 1.35%   |
| SanDisk NVMe SSD Drive 500GB                          | 4        | 1.35%   |
| Samsung SSD 860 EVO 500GB                             | 4        | 1.35%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 3        | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 1.01%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 3        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB                       | 3        | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 1.01%   |
| Samsung SSD 980 PRO 1TB                               | 3        | 1.01%   |
| Samsung SSD 980 500GB                                 | 3        | 1.01%   |
| Samsung SSD 860 EVO 1TB                               | 3        | 1.01%   |
| JMicron Generic 256GB                                 | 3        | 1.01%   |
| Crucial CT500MX500SSD1 500GB                          | 3        | 1.01%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 2        | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 2        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2        | 0.67%   |
| Toshiba HDWD110 1TB                                   | 2        | 0.67%   |
| Toshiba DT01ACA050 500GB                              | 2        | 0.67%   |
| SK hynix SC311 SATA 128GB SSD                         | 2        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2        | 0.67%   |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.67%   |
| Seagate Expansion HDD 8TB                             | 2        | 0.67%   |
| Seagate BUP Portable 4TB                              | 2        | 0.67%   |
| SanDisk SSD PLUS 480GB                                | 2        | 0.67%   |
| SanDisk SSD PLUS 1000GB                               | 2        | 0.67%   |
| SanDisk NVMe SSD Drive 1TB                            | 2        | 0.67%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2        | 0.67%   |
| Samsung SSD 960 EVO 250GB                             | 2        | 0.67%   |
| Samsung NVMe SSD Drive 500GB                          | 2        | 0.67%   |
| Samsung NVMe SSD Drive 1024GB                         | 2        | 0.67%   |
| Samsung HN-M750MBB 752GB                              | 2        | 0.67%   |
| Plextor PX-128M6S 128GB SSD                           | 2        | 0.67%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 2        | 0.67%   |
| Maxtor 6V250F0 256GB                                  | 2        | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                           | 2        | 0.67%   |
| A-DATA HC660 1TB SSD                                  | 2        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 49     | 35.51%  |
| WDC                 | 31       | 57     | 28.97%  |
| Toshiba             | 19       | 25     | 17.76%  |
| Hitachi             | 7        | 8      | 6.54%   |
| Samsung Electronics | 4        | 4      | 3.74%   |
| HGST                | 3        | 5      | 2.8%    |
| Maxtor              | 2        | 2      | 1.87%   |
| Unknown             | 1        | 1      | 0.93%   |
| SSK                 | 1        | 1      | 0.93%   |
| MARVELL             | 1        | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 32     | 30.12%  |
| SanDisk             | 9        | 9      | 10.84%  |
| Crucial             | 8        | 12     | 9.64%   |
| Kingston            | 6        | 8      | 7.23%   |
| WDC                 | 3        | 3      | 3.61%   |
| China               | 3        | 3      | 3.61%   |
| Transcend           | 2        | 2      | 2.41%   |
| SK hynix            | 2        | 2      | 2.41%   |
| Plextor             | 2        | 2      | 2.41%   |
| Intel               | 2        | 2      | 2.41%   |
| Hewlett-Packard     | 2        | 2      | 2.41%   |
| A-DATA Technology   | 2        | 2      | 2.41%   |
| WALRAM              | 1        | 1      | 1.2%    |
| Vaseky              | 1        | 1      | 1.2%    |
| USB30               | 1        | 1      | 1.2%    |
| Unknown             | 1        | 1      | 1.2%    |
| Teclast             | 1        | 1      | 1.2%    |
| SABRENT             | 1        | 2      | 1.2%    |
| Pioneer             | 1        | 1      | 1.2%    |
| OCZ                 | 1        | 1      | 1.2%    |
| LITEONIT            | 1        | 1      | 1.2%    |
| Lexar               | 1        | 1      | 1.2%    |
| KLEVV               | 1        | 1      | 1.2%    |
| Kingmax             | 1        | 1      | 1.2%    |
| KINGBANK            | 1        | 1      | 1.2%    |
| GAMER               | 1        | 1      | 1.2%    |
| GALAX               | 1        | 1      | 1.2%    |
| Fanxiang            | 1        | 1      | 1.2%    |
| Apacer              | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 85       | 153    | 40.67%  |
| SSD     | 64       | 97     | 30.62%  |
| NVMe    | 54       | 96     | 25.84%  |
| MMC     | 3        | 3      | 1.44%   |
| Unknown | 3        | 3      | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 113      | 239    | 61.08%  |
| NVMe | 53       | 92     | 28.65%  |
| SAS  | 16       | 18     | 8.65%   |
| MMC  | 3        | 3      | 1.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 73       | 109    | 43.2%   |
| 0.51-1.0   | 50       | 74     | 29.59%  |
| 1.01-2.0   | 22       | 29     | 13.02%  |
| 3.01-4.0   | 9        | 12     | 5.33%   |
| 4.01-10.0  | 9        | 18     | 5.33%   |
| 2.01-3.0   | 5        | 5      | 2.96%   |
| 10.01-20.0 | 1        | 3      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 30       | 20.69%  |
| 101-250        | 25       | 17.24%  |
| 251-500        | 19       | 13.1%   |
| More than 3000 | 18       | 12.41%  |
| 1001-2000      | 16       | 11.03%  |
| 2001-3000      | 12       | 8.28%   |
| 1-20           | 10       | 6.9%    |
| Unknown        | 8        | 5.52%   |
| 51-100         | 4        | 2.76%   |
| 21-50          | 3        | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 36       | 24.49%  |
| 21-50          | 28       | 19.05%  |
| 101-250        | 21       | 14.29%  |
| 251-500        | 15       | 10.2%   |
| 501-1000       | 11       | 7.48%   |
| 51-100         | 11       | 7.48%   |
| 1001-2000      | 10       | 6.8%    |
| Unknown        | 8        | 5.44%   |
| More than 3000 | 6        | 4.08%   |
| 2001-3000      | 1        | 0.68%   |

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
| Detected | 77       | 167    | 47.24%  |
| Works    | 68       | 160    | 41.72%  |
| Malfunc  | 17       | 24     | 10.43%  |
| Failed   | 1        | 1      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 87       | 40.65%  |
| AMD                          | 43       | 20.09%  |
| Samsung Electronics          | 27       | 12.62%  |
| SanDisk                      | 12       | 5.61%   |
| ASMedia Technology           | 8        | 3.74%   |
| Silicon Motion               | 5        | 2.34%   |
| Phison Electronics           | 5        | 2.34%   |
| Micron/Crucial Technology    | 5        | 2.34%   |
| Kingston Technology Company  | 4        | 1.87%   |
| Marvell Technology Group     | 3        | 1.4%    |
| Toshiba America Info Systems | 2        | 0.93%   |
| Shenzhen Longsys Electronics | 2        | 0.93%   |
| Realtek Semiconductor        | 2        | 0.93%   |
| Adaptec                      | 2        | 0.93%   |
| Yangtze Memory Technologies  | 1        | 0.47%   |
| VIA Technologies             | 1        | 0.47%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.47%   |
| KIOXIA                       | 1        | 0.47%   |
| JMicron Technology           | 1        | 0.47%   |
| INNOGRIT                     | 1        | 0.47%   |
| Broadcom / LSI               | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 11.02%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15       | 6.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 5.31%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 3.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 3.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 3.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.45%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 1.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 1.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.63%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.22%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 2        | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.82%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 2        | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 0.82%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.82%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.82%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                                  | 2        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.82%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.82%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.82%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 0.82%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 113      | 57.36%  |
| NVMe | 53       | 26.9%   |
| IDE  | 16       | 8.12%   |
| RAID | 11       | 5.58%   |
| SAS  | 4        | 2.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 91       | 66.91%  |
| AMD    | 45       | 33.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 4.41%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 2.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.21%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 2.21%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.47%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.47%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 1.47%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.47%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.47%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.47%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.47%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores  | 2        | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.47%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.47%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 1.47%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.47%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.47%   |
| Intel Xeon W-2155 CPU @ 3.30GHz             | 1        | 0.74%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.74%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.74%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.74%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.74%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.74%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.74%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.74%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.74%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.74%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.74%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.74%   |
| Intel N95                                   | 1        | 0.74%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.74%   |
| Intel Core i9-7940X CPU @ 3.10GHz           | 1        | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 34       | 25%     |
| Intel Core i7          | 16       | 11.76%  |
| AMD Ryzen 5            | 16       | 11.76%  |
| Intel Xeon             | 12       | 8.82%   |
| Other                  | 9        | 6.62%   |
| AMD Ryzen 7            | 9        | 6.62%   |
| Intel Core i3          | 7        | 5.15%   |
| AMD Ryzen 9            | 5        | 3.68%   |
| Intel Celeron          | 3        | 2.21%   |
| AMD Ryzen Threadripper | 3        | 2.21%   |
| Intel Pentium          | 2        | 1.47%   |
| Intel Core 2 Quad      | 2        | 1.47%   |
| AMD FX                 | 2        | 1.47%   |
| AMD Athlon             | 2        | 1.47%   |
| AMD A10                | 2        | 1.47%   |
| Intel Pentium Gold     | 1        | 0.74%   |
| Intel Pentium Dual     | 1        | 0.74%   |
| Intel Pentium 4        | 1        | 0.74%   |
| Intel Core m3          | 1        | 0.74%   |
| Intel Core i9          | 1        | 0.74%   |
| Intel Atom             | 1        | 0.74%   |
| AMD Ryzen 5 PRO        | 1        | 0.74%   |
| AMD Ryzen 3            | 1        | 0.74%   |
| AMD PRO A10            | 1        | 0.74%   |
| AMD Phenom II X6       | 1        | 0.74%   |
| AMD Phenom II X4       | 1        | 0.74%   |
| AMD Opteron            | 1        | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 54       | 39.71%  |
| 6      | 27       | 19.85%  |
| 2      | 19       | 13.97%  |
| 8      | 15       | 11.03%  |
| 12     | 8        | 5.88%   |
| 16     | 6        | 4.41%   |
| 10     | 2        | 1.47%   |
| 32     | 1        | 0.74%   |
| 24     | 1        | 0.74%   |
| 14     | 1        | 0.74%   |
| 3      | 1        | 0.74%   |
| 1      | 1        | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 135      | 99.26%  |
| 2      | 1        | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 86       | 63.24%  |
| 1      | 50       | 36.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 135      | 99.26%  |
| Unknown        | 1        | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 23.78%  |
| 0x306c3    | 12       | 8.39%   |
| 0x306a9    | 9        | 6.29%   |
| 0x906ea    | 8        | 5.59%   |
| 0x506e3    | 7        | 4.9%    |
| 0x08701021 | 6        | 4.2%    |
| 0x206a7    | 5        | 3.5%    |
| 0x90672    | 4        | 2.8%    |
| 0x306e4    | 4        | 2.8%    |
| 0x20655    | 4        | 2.8%    |
| 0x0a201016 | 3        | 2.1%    |
| 0x08701013 | 3        | 2.1%    |
| 0x06003106 | 3        | 2.1%    |
| 0x906e9    | 2        | 1.4%    |
| 0x906c0    | 2        | 1.4%    |
| 0x50654    | 2        | 1.4%    |
| 0x406f1    | 2        | 1.4%    |
| 0x0a50000d | 2        | 1.4%    |
| 0x0a20120a | 2        | 1.4%    |
| 0x06000852 | 2        | 1.4%    |
| 0xf41      | 1        | 0.7%    |
| 0xb06e0    | 1        | 0.7%    |
| 0xa0671    | 1        | 0.7%    |
| 0xa0655    | 1        | 0.7%    |
| 0x706a1    | 1        | 0.7%    |
| 0x6fd      | 1        | 0.7%    |
| 0x6fb      | 1        | 0.7%    |
| 0x1067a    | 1        | 0.7%    |
| 0x0a601203 | 1        | 0.7%    |
| 0x0a601201 | 1        | 0.7%    |
| 0x0a404102 | 1        | 0.7%    |
| 0x0a201009 | 1        | 0.7%    |
| 0x08600106 | 1        | 0.7%    |
| 0x0830107a | 1        | 0.7%    |
| 0x0830104d | 1        | 0.7%    |
| 0x08301039 | 1        | 0.7%    |
| 0x08108109 | 1        | 0.7%    |
| 0x08101102 | 1        | 0.7%    |
| 0x08101016 | 1        | 0.7%    |
| 0x0800820d | 1        | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 17       | 12.5%   |
| Haswell          | 17       | 12.5%   |
| Zen 2            | 15       | 11.03%  |
| KabyLake         | 14       | 10.29%  |
| Zen 3            | 10       | 7.35%   |
| Skylake          | 9        | 6.62%   |
| SandyBridge      | 7        | 5.15%   |
| Alderlake Hybrid | 6        | 4.41%   |
| Westmere         | 5        | 3.68%   |
| Unknown          | 5        | 3.68%   |
| Zen+             | 4        | 2.94%   |
| Zen              | 4        | 2.94%   |
| Steamroller      | 3        | 2.21%   |
| K10              | 3        | 2.21%   |
| Tremont          | 2        | 1.47%   |
| Piledriver       | 2        | 1.47%   |
| Core             | 2        | 1.47%   |
| CometLake        | 2        | 1.47%   |
| Broadwell        | 2        | 1.47%   |
| Silvermont       | 1        | 0.74%   |
| Penryn           | 1        | 0.74%   |
| NetBurst         | 1        | 0.74%   |
| Icelake          | 1        | 0.74%   |
| Goldmont plus    | 1        | 0.74%   |
| Goldmont         | 1        | 0.74%   |
| Excavator        | 1        | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 64       | 39.51%  |
| Intel             | 56       | 34.57%  |
| AMD               | 41       | 25.31%  |
| ASPEED Technology | 1        | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.99%   |
| Intel HD Graphics 530                                                       | 5        | 2.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.99%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.4%    |
| Intel AlderLake-S GT1                                                       | 4        | 2.4%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.8%    |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 1.8%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.8%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.2%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.2%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.2%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.2%    |
| Nvidia GF119 [GeForce 605]                                                  | 2        | 1.2%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 1.2%    |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.2%    |
| Intel HD Graphics 630                                                       | 2        | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.2%    |
| AMD Raphael                                                                 | 2        | 1.2%    |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.2%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.2%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.2%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]            | 2        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.2%    |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.2%    |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 2        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 50       | 35.21%  |
| 1 x Intel       | 41       | 28.87%  |
| 1 x AMD         | 31       | 21.83%  |
| Intel + Nvidia  | 6        | 4.23%   |
| 2 x Nvidia      | 4        | 2.82%   |
| Intel + AMD     | 4        | 2.82%   |
| AMD + Nvidia    | 3        | 2.11%   |
| 2 x AMD         | 2        | 1.41%   |
| Nvidia + ASPEED | 1        | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 87       | 62.59%  |
| Proprietary | 46       | 33.09%  |
| Unknown     | 6        | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 39.44%  |
| 1.01-2.0   | 20       | 14.08%  |
| 7.01-8.0   | 16       | 11.27%  |
| 3.01-4.0   | 14       | 9.86%   |
| 8.01-16.0  | 12       | 8.45%   |
| 0.51-1.0   | 12       | 8.45%   |
| 5.01-6.0   | 6        | 4.23%   |
| 0.01-0.5   | 6        | 4.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 38       | 27.14%  |
| Samsung Electronics  | 16       | 11.43%  |
| Hewlett-Packard      | 11       | 7.86%   |
| Goldstar             | 10       | 7.14%   |
| Acer                 | 9        | 6.43%   |
| AOC                  | 7        | 5%      |
| Philips              | 6        | 4.29%   |
| ViewSonic            | 3        | 2.14%   |
| PRISM+               | 3        | 2.14%   |
| Denver               | 3        | 2.14%   |
| Unknown (XXX)        | 2        | 1.43%   |
| Pixio                | 2        | 1.43%   |
| Lenovo Group Limited | 2        | 1.43%   |
| Lenovo               | 2        | 1.43%   |
| AU Optronics         | 2        | 1.43%   |
| ASUSTek Computer     | 2        | 1.43%   |
| Ancor Communications | 2        | 1.43%   |
| Unknown              | 2        | 1.43%   |
| Xiaomi               | 1        | 0.71%   |
| Wacom                | 1        | 0.71%   |
| Toshiba              | 1        | 0.71%   |
| Sony                 | 1        | 0.71%   |
| Sharp                | 1        | 0.71%   |
| SGT                  | 1        | 0.71%   |
| SAC                  | 1        | 0.71%   |
| RTK                  | 1        | 0.71%   |
| MSI                  | 1        | 0.71%   |
| InnoView             | 1        | 0.71%   |
| IDV                  | 1        | 0.71%   |
| HPN                  | 1        | 0.71%   |
| HPD                  | 1        | 0.71%   |
| HKC                  | 1        | 0.71%   |
| CVT                  | 1        | 0.71%   |
| CHR                  | 1        | 0.71%   |
| AUS                  | 1        | 0.71%   |
| AOpen                | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 4        | 2.74%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 2        | 1.37%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 2        | 1.37%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch                 | 2        | 1.37%   |
| Pixio U27I4K WAM2700 3840x2160 600x330mm 27.0-inch                      | 2        | 1.37%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                   | 2        | 1.37%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 2        | 1.37%   |
| Denver GB-2461CF LHC0236 1920x1080 530x280mm 23.6-inch                  | 2        | 1.37%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                     | 2        | 1.37%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                       | 2        | 1.37%   |
| Dell LCD Monitor P2217H 1920x1080                                       | 2        | 1.37%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                      | 2        | 1.37%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                       | 2        | 1.37%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                        | 2        | 1.37%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                        | 2        | 1.37%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                        | 2        | 1.37%   |
| Acer S201HL ACR01A5 1600x900 440x250mm 19.9-inch                        | 2        | 1.37%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                     | 2        | 1.37%   |
| Unknown                                                                 | 2        | 1.37%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                       | 1        | 0.68%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 0.68%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 0.68%   |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 530x300mm 24.0-inch               | 1        | 0.68%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                               | 1        | 0.68%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1        | 0.68%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 0.68%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                       | 1        | 0.68%   |
| Sony TV SNY2C02 1920x1080 1218x685mm 55.0-inch                          | 1        | 0.68%   |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                        | 1        | 0.68%   |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                     | 1        | 0.68%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.68%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch       | 1        | 0.68%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.68%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0F18 3840x2160 1872x1053mm 84.6-inch | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch   | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor S27A950D 1920x1080                      | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 70       | 50.36%  |
| 2560x1440 (QHD)    | 23       | 16.55%  |
| 3840x2160 (4K)     | 21       | 15.11%  |
| 1600x900 (HD+)     | 11       | 7.91%   |
| 2560x1600          | 2        | 1.44%   |
| 2560x1080          | 2        | 1.44%   |
| 1680x1050 (WSXGA+) | 2        | 1.44%   |
| 1366x768 (WXGA)    | 2        | 1.44%   |
| 1360x768           | 2        | 1.44%   |
| 1280x1024 (SXGA)   | 2        | 1.44%   |
| 3440x1440          | 1        | 0.72%   |
| 1440x900 (WXGA+)   | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 24       | 17.52%  |
| 23      | 18       | 13.14%  |
| Unknown | 18       | 13.14%  |
| 24      | 14       | 10.22%  |
| 21      | 14       | 10.22%  |
| 20      | 8        | 5.84%   |
| 31      | 6        | 4.38%   |
| 19      | 6        | 4.38%   |
| 18      | 4        | 2.92%   |
| 54      | 3        | 2.19%   |
| 28      | 3        | 2.19%   |
| 15      | 3        | 2.19%   |
| 84      | 2        | 1.46%   |
| 40      | 2        | 1.46%   |
| 72      | 1        | 0.73%   |
| 65      | 1        | 0.73%   |
| 55      | 1        | 0.73%   |
| 50      | 1        | 0.73%   |
| 39      | 1        | 0.73%   |
| 34      | 1        | 0.73%   |
| 32      | 1        | 0.73%   |
| 26      | 1        | 0.73%   |
| 25      | 1        | 0.73%   |
| 22      | 1        | 0.73%   |
| 17      | 1        | 0.73%   |
| 16      | 1        | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 40.74%  |
| 401-500     | 31       | 22.96%  |
| Unknown     | 18       | 13.33%  |
| 601-700     | 10       | 7.41%   |
| 1001-1500   | 6        | 4.44%   |
| 301-350     | 4        | 2.96%   |
| 801-900     | 3        | 2.22%   |
| 351-400     | 3        | 2.22%   |
| 1501-2000   | 3        | 2.22%   |
| 701-800     | 2        | 1.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 106      | 80.92%  |
| Unknown | 16       | 12.21%  |
| 16/10   | 4        | 3.05%   |
| 5/4     | 2        | 1.53%   |
| 21/9    | 2        | 1.53%   |
| 6/5     | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 40       | 29.41%  |
| 301-350        | 24       | 17.65%  |
| 151-200        | 19       | 13.97%  |
| Unknown        | 18       | 13.24%  |
| 351-500        | 10       | 7.35%   |
| More than 1000 | 9        | 6.62%   |
| 251-300        | 5        | 3.68%   |
| 141-150        | 4        | 2.94%   |
| 101-110        | 4        | 2.94%   |
| 501-1000       | 3        | 2.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 50.36%  |
| 101-120 | 29       | 20.86%  |
| Unknown | 18       | 12.95%  |
| 121-160 | 9        | 6.47%   |
| 161-240 | 8        | 5.76%   |
| 1-50    | 5        | 3.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 119      | 83.8%   |
| 2     | 14       | 9.86%   |
| 0     | 8        | 5.63%   |
| 3     | 1        | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 83       | 41.71%  |
| Intel                 | 72       | 36.18%  |
| Qualcomm Atheros      | 11       | 5.53%   |
| TP-Link               | 7        | 3.52%   |
| Broadcom              | 6        | 3.02%   |
| MediaTek              | 4        | 2.01%   |
| ASUSTek Computer      | 3        | 1.51%   |
| Samsung Electronics   | 2        | 1.01%   |
| Ralink Technology     | 2        | 1.01%   |
| Aquantia              | 2        | 1.01%   |
| Qualcomm              | 1        | 0.5%    |
| Linksys               | 1        | 0.5%    |
| Hewlett-Packard       | 1        | 0.5%    |
| Fargo                 | 1        | 0.5%    |
| Exar                  | 1        | 0.5%    |
| Edimax Technology     | 1        | 0.5%    |
| ASIX Electronics      | 1        | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61       | 26.52%  |
| Intel Wi-Fi 6 AX200                                               | 15       | 6.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 5.22%   |
| Intel Ethernet Controller I225-V                                  | 11       | 4.78%   |
| Intel I211 Gigabit Network Connection                             | 10       | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.04%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 1.3%    |
| Intel Wireless 3165                                               | 3        | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 3        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.3%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 3        | 1.3%    |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 3        | 1.3%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2        | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.87%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 0.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.87%   |
| Realtek 802.11ac NIC                                              | 2        | 0.87%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.87%   |
| Intel Wireless 7260                                               | 2        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.87%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.87%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.43%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.43%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.43%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1        | 0.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.43%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.43%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 36       | 48.65%  |
| Realtek Semiconductor | 10       | 13.51%  |
| TP-Link               | 7        | 9.46%   |
| Qualcomm Atheros      | 6        | 8.11%   |
| MediaTek              | 4        | 5.41%   |
| Broadcom              | 4        | 5.41%   |
| ASUSTek Computer      | 3        | 4.05%   |
| Ralink Technology     | 2        | 2.7%    |
| Linksys               | 1        | 1.35%   |
| Edimax Technology     | 1        | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 15       | 20%     |
| Intel Alder Lake-S PCH CNVi WiFi                                | 4        | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 3        | 4%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 3        | 4%      |
| Intel Wireless 3165                                             | 3        | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 3        | 4%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3        | 4%      |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3        | 4%      |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                      | 2        | 2.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 2        | 2.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                 | 2        | 2.67%   |
| Realtek 802.11ac NIC                                            | 2        | 2.67%   |
| Ralink MT7601U Wireless Adapter                                 | 2        | 2.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 2        | 2.67%   |
| Intel Wireless 7260                                             | 2        | 2.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 2.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 1.33%   |
| TP-Link Archer T4U ver.3                                        | 1        | 1.33%   |
| TP-Link 802.11ac WLAN Adapter                                   | 1        | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 1.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 1.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 1.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter           | 1        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1        | 1.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 1        | 1.33%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter             | 1        | 1.33%   |
| Intel Wireless-AC 9260                                          | 1        | 1.33%   |
| Intel Wireless 8260                                             | 1        | 1.33%   |
| Intel Wireless 7265                                             | 1        | 1.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 1        | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1        | 1.33%   |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 1.33%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.33%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter    | 1        | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 78       | 53.06%  |
| Intel                 | 55       | 37.41%  |
| Qualcomm Atheros      | 5        | 3.4%    |
| Samsung Electronics   | 2        | 1.36%   |
| Broadcom              | 2        | 1.36%   |
| Aquantia              | 2        | 1.36%   |
| Qualcomm              | 1        | 0.68%   |
| Hewlett-Packard       | 1        | 0.68%   |
| ASIX Electronics      | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 61       | 39.87%  |
| Realtek RTL8125 2.5GbE Controller                                  | 12       | 7.84%   |
| Intel Ethernet Controller I225-V                                   | 11       | 7.19%   |
| Intel I211 Gigabit Network Connection                              | 10       | 6.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7        | 4.58%   |
| Intel Ethernet Connection (2) I219-V                               | 5        | 3.27%   |
| Intel Ethernet Connection I217-LM                                  | 4        | 2.61%   |
| Intel Ethernet Connection I217-V                                   | 3        | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                              | 3        | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                      | 2        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2        | 1.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 2        | 1.31%   |
| Intel Ethernet Connection (2) I218-V                               | 2        | 1.31%   |
| Intel 82578DM Gigabit Network Connection                           | 2        | 1.31%   |
| Realtek USB 10/100/1G/2.5G LAN                                     | 1        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                    | 1        | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1        | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                              | 1        | 0.65%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                         | 1        | 0.65%   |
| Qualcomm Redmi Note 8                                              | 1        | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1        | 0.65%   |
| Intel I350 Gigabit Network Connection                              | 1        | 0.65%   |
| Intel I210 Gigabit Network Connection                              | 1        | 0.65%   |
| Intel Ethernet Controller X550                                     | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                               | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                              | 1        | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                              | 1        | 0.65%   |
| Intel Ethernet Connection (2) I218-LM                              | 1        | 0.65%   |
| Intel Ethernet Connection (14) I219-V                              | 1        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                              | 1        | 0.65%   |
| Intel 82583V Gigabit Network Connection                            | 1        | 0.65%   |
| Intel 82579V Gigabit Network Connection                            | 1        | 0.65%   |
| Intel 82566DC-2 Gigabit Network Connection                         | 1        | 0.65%   |
| HP lt4120 Snapdragon X5 LTE                                        | 1        | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                  | 1        | 0.65%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                   | 1        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                      | 1        | 0.65%   |
| Aquantia AQC113C NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 136      | 64.45%  |
| WiFi     | 73       | 34.6%   |
| Modem    | 1        | 0.47%   |
| Unknown  | 1        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 72.11%  |
| WiFi     | 40       | 27.21%  |
| Unknown  | 1        | 0.68%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 71       | 52.21%  |
| 2     | 60       | 44.12%  |
| 3     | 4        | 2.94%   |
| 0     | 1        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 129      | 94.85%  |
| Yes  | 7        | 5.15%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 50%     |
| Cambridge Silicon Radio         | 10       | 16.67%  |
| TP-Link                         | 5        | 8.33%   |
| Realtek Semiconductor           | 5        | 8.33%   |
| MediaTek                        | 4        | 6.67%   |
| Qualcomm Atheros Communications | 3        | 5%      |
| SINO WEALTH                     | 1        | 1.67%   |
| Broadcom                        | 1        | 1.67%   |
| Unknown                         | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 12       | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10       | 16.67%  |
| Intel Bluetooth wireless interface                  | 7        | 11.67%  |
| TP-Link UB500 Adapter                               | 5        | 8.33%   |
| MediaTek Wireless_Device                            | 4        | 6.67%   |
| Realtek Bluetooth Radio                             | 3        | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 5%      |
| Intel AX201 Bluetooth                               | 3        | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 3.33%   |
| Intel Bluetooth Device                              | 2        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 3.33%   |
| Intel AX210 Bluetooth                               | 2        | 3.33%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.67%   |
| Unknown                                             | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 89       | 38.7%   |
| Nvidia                                       | 60       | 26.09%  |
| AMD                                          | 49       | 21.3%   |
| C-Media Electronics                          | 4        | 1.74%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.87%   |
| SteelSeries ApS                              | 2        | 0.87%   |
| Giga-Byte Technology                         | 2        | 0.87%   |
| Creative Labs                                | 2        | 0.87%   |
| ASUSTek Computer                             | 2        | 0.87%   |
| XMOS                                         | 1        | 0.43%   |
| TTGK Technology                              | 1        | 0.43%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.43%   |
| Tenx Technology                              | 1        | 0.43%   |
| Sony                                         | 1        | 0.43%   |
| Setek Elektronik                             | 1        | 0.43%   |
| Sennheiser Communications                    | 1        | 0.43%   |
| SAVITECH                                     | 1        | 0.43%   |
| Samson Technologies                          | 1        | 0.43%   |
| RODE Microphones                             | 1        | 0.43%   |
| Realtek Semiconductor                        | 1        | 0.43%   |
| MV                                           | 1        | 0.43%   |
| Micro Star International                     | 1        | 0.43%   |
| Logitech                                     | 1        | 0.43%   |
| JMTek                                        | 1        | 0.43%   |
| Jieli Technology                             | 1        | 0.43%   |
| Huawei Technologies                          | 1        | 0.43%   |
| FiiO Electronics Technology                  | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 20       | 7.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16       | 5.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 3.36%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 3.36%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 3.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.24%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 2.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 2.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.87%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.49%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.49%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.12%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.12%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.12%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 2        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.75%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.75%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 18       | 19.15%  |
| Corsair                        | 11       | 11.7%   |
| Crucial                        | 10       | 10.64%  |
| Samsung Electronics            | 8        | 8.51%   |
| G.Skill                        | 8        | 8.51%   |
| SK hynix                       | 7        | 7.45%   |
| Micron Technology              | 7        | 7.45%   |
| KLEVV                          | 4        | 4.26%   |
| A-DATA Technology              | 3        | 3.19%   |
| Unknown (ABCD)                 | 2        | 2.13%   |
| Transcend                      | 2        | 2.13%   |
| Kingmax                        | 2        | 2.13%   |
| Unknown (0x0E9D)               | 1        | 1.06%   |
| Unknown (0x0B92)               | 1        | 1.06%   |
| Unknown                        | 1        | 1.06%   |
| Qimonda                        | 1        | 1.06%   |
| Patriot                        | 1        | 1.06%   |
| Nanya Technology               | 1        | 1.06%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 1.06%   |
| Lexar                          | 1        | 1.06%   |
| Essencore Limited              | 1        | 1.06%   |
| Elpida                         | 1        | 1.06%   |
| ASint Technology               | 1        | 1.06%   |
| Unknown                        | 1        | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 2        | 1.89%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                      | 2        | 1.89%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 2        | 1.89%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s               | 2        | 1.89%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s              | 2        | 1.89%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3600MT/s                 | 2        | 1.89%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                         | 2        | 1.89%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                | 1        | 0.94%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1        | 0.94%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s    | 1        | 0.94%   |
| Unknown (0x0B92) RAM Module 16GB DIMM DDR4 3200MT/s                 | 1        | 0.94%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR2 2048MT/s                 | 1        | 0.94%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                   | 1        | 0.94%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1        | 0.94%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 0.94%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1        | 0.94%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s                     | 1        | 0.94%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2400MT/s                | 1        | 0.94%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1        | 0.94%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1        | 0.94%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s               | 1        | 0.94%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s                 | 1        | 0.94%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s                 | 1        | 0.94%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                 | 1        | 0.94%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1        | 0.94%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1        | 0.94%   |
| Samsung RAM M378A2K43CB1-CRC 16GB DIMM DDR4 2400MT/s                | 1        | 0.94%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                 | 1        | 0.94%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                 | 1        | 0.94%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                    | 1        | 0.94%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s                  | 1        | 0.94%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s               | 1        | 0.94%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER RAM Module 2048MB DIMM DDR3 1600MT/s | 1        | 0.94%   |
| Micron RAM TEAMGROUP-UD4-2133 16384MB DIMM DDR4 2134MT/s            | 1        | 0.94%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                 | 1        | 0.94%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                  | 1        | 0.94%   |
| Micron RAM 36KSF2G72PZ-1G6N1 16GB DIMM DDR3 1600MT/s                | 1        | 0.94%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s                | 1        | 0.94%   |
| Micron RAM 16KTF1G64HZ-1G6J1 8GB SODIMM DDR3 1600MT/s               | 1        | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 47       | 55.29%  |
| DDR3    | 25       | 29.41%  |
| SDRAM   | 4        | 4.71%   |
| DDR5    | 4        | 4.71%   |
| LPDDR4  | 2        | 2.35%   |
| DDR2    | 2        | 2.35%   |
| Unknown | 1        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 75       | 92.59%  |
| SODIMM | 6        | 7.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 29       | 31.87%  |
| 8192  | 29       | 31.87%  |
| 4096  | 18       | 19.78%  |
| 32768 | 7        | 7.69%   |
| 2048  | 7        | 7.69%   |
| 1024  | 1        | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 17       | 17.53%  |
| 2400  | 13       | 13.4%   |
| 3200  | 12       | 12.37%  |
| 3600  | 11       | 11.34%  |
| 1333  | 6        | 6.19%   |
| 2667  | 4        | 4.12%   |
| 2666  | 4        | 4.12%   |
| 2133  | 3        | 3.09%   |
| 3733  | 2        | 2.06%   |
| 3666  | 2        | 2.06%   |
| 3400  | 2        | 2.06%   |
| 3266  | 2        | 2.06%   |
| 2048  | 2        | 2.06%   |
| 1867  | 2        | 2.06%   |
| 1866  | 2        | 2.06%   |
| 1800  | 2        | 2.06%   |
| 7000  | 1        | 1.03%   |
| 5808  | 1        | 1.03%   |
| 5200  | 1        | 1.03%   |
| 4800  | 1        | 1.03%   |
| 4333  | 1        | 1.03%   |
| 4000  | 1        | 1.03%   |
| 3800  | 1        | 1.03%   |
| 2200  | 1        | 1.03%   |
| 2134  | 1        | 1.03%   |
| 1067  | 1        | 1.03%   |
| 667   | 1        | 1.03%   |

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
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1        | 7.14%   |
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
| 0     | 115      | 83.94%  |
| 1     | 21       | 15.33%  |
| 2     | 1        | 0.73%   |

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

