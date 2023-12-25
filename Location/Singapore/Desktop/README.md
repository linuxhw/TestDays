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

Total: 199

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 0B40h                       | [e3ad55af3f](https://linux-hardware.org/?probe=e3ad55af3f) | Dec 24, 2023 |
| ASUSTek       | PRIME Z490-P                | [61724f27e7](https://linux-hardware.org/?probe=61724f27e7) | Dec 23, 2023 |
| MSI           | PRO H410M-B                 | [28d6a6092b](https://linux-hardware.org/?probe=28d6a6092b) | Dec 23, 2023 |
| Acer          | Veriton M4630G V:1.0        | [6e74b5d77f](https://linux-hardware.org/?probe=6e74b5d77f) | Dec 05, 2023 |
| ASRock        | X300TM-ITX                  | [6c74495d5f](https://linux-hardware.org/?probe=6c74495d5f) | Dec 03, 2023 |
| JINGSHA       | X99-D8I                     | [a142726fb0](https://linux-hardware.org/?probe=a142726fb0) | Dec 02, 2023 |
| JINGSHA       | X99-D8I                     | [52a45bbcdb](https://linux-hardware.org/?probe=52a45bbcdb) | Dec 02, 2023 |
| Unknown       | Intel BayTrail Series R1... | [6ab4075642](https://linux-hardware.org/?probe=6ab4075642) | Nov 29, 2023 |
| Unknown       | Unknown                     | [ada9cf1c70](https://linux-hardware.org/?probe=ada9cf1c70) | Nov 07, 2023 |
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
| Ubuntu 20.04                 | 22       | 14.1%   |
| Ubuntu 18.04                 | 15       | 9.62%   |
| Ubuntu 22.04                 | 12       | 7.69%   |
| Arch Rolling                 | 8        | 5.13%   |
| Linux Mint 21                | 5        | 3.21%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 2.56%   |
| Manjaro                      | 4        | 2.56%   |
| KDE neon 20.04               | 4        | 2.56%   |
| Fedora 38                    | 4        | 2.56%   |
| ArcoLinux Rolling            | 4        | 2.56%   |
| Pop!_OS 20.04                | 3        | 1.92%   |
| OpenMandriva 23.03           | 3        | 1.92%   |
| Debian 11                    | 3        | 1.92%   |
| Ubuntu 21.04                 | 2        | 1.28%   |
| Rocky Linux 8.5              | 2        | 1.28%   |
| Pop!_OS 21.04                | 2        | 1.28%   |
| OpenMandriva 4.50            | 2        | 1.28%   |
| OpenMandriva 4.3             | 2        | 1.28%   |
| OpenMandriva 23.11           | 2        | 1.28%   |
| MX 21                        | 2        | 1.28%   |
| Linux Mint 21.2              | 2        | 1.28%   |
| Linux Mint 20.3              | 2        | 1.28%   |
| Linux Mint 20                | 2        | 1.28%   |
| Fedora 37                    | 2        | 1.28%   |
| Fedora 33                    | 2        | 1.28%   |
| Debian 12                    | 2        | 1.28%   |
| Arch                         | 2        | 1.28%   |
| Zorin 16                     | 1        | 0.64%   |
| Xubuntu 23.04                | 1        | 0.64%   |
| Xubuntu 20.04                | 1        | 0.64%   |
| Ubuntu Unity 20.04           | 1        | 0.64%   |
| Ubuntu Unity 16.04           | 1        | 0.64%   |
| Ubuntu MATE 20.04            | 1        | 0.64%   |
| Ubuntu Kylin 22.04           | 1        | 0.64%   |
| Ubuntu 23.10                 | 1        | 0.64%   |
| Ubuntu 23.04                 | 1        | 0.64%   |
| Ubuntu 22.10                 | 1        | 0.64%   |
| Ubuntu 19.10                 | 1        | 0.64%   |
| Ubuntu 19.04                 | 1        | 0.64%   |
| Ubuntu 18.10                 | 1        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 55       | 37.67%  |
| OpenMandriva | 13       | 8.9%    |
| Linux Mint   | 11       | 7.53%   |
| Arch         | 10       | 6.85%   |
| Fedora       | 8        | 5.48%   |
| Pop!_OS      | 7        | 4.79%   |
| Debian       | 6        | 4.11%   |
| Manjaro      | 5        | 3.42%   |
| Rocky Linux  | 4        | 2.74%   |
| openSUSE     | 4        | 2.74%   |
| KDE neon     | 4        | 2.74%   |
| ArcoLinux    | 4        | 2.74%   |
| Xubuntu      | 2        | 1.37%   |
| Ubuntu Unity | 2        | 1.37%   |
| MX           | 2        | 1.37%   |
| Zorin        | 1        | 0.68%   |
| Ubuntu MATE  | 1        | 0.68%   |
| Ubuntu Kylin | 1        | 0.68%   |
| Lubuntu      | 1        | 0.68%   |
| Gentoo       | 1        | 0.68%   |
| Garuda Linux | 1        | 0.68%   |
| EndeavourOS  | 1        | 0.68%   |
| CentOS       | 1        | 0.68%   |
| Atz          | 1        | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.0-56-generic            | 7        | 4.12%   |
| 5.15.0-46-generic            | 4        | 2.35%   |
| 6.2.6-desktop-1omv2390       | 3        | 1.76%   |
| 5.4.0-29-generic             | 3        | 1.76%   |
| 5.15.0-58-generic            | 3        | 1.76%   |
| 6.3.8-zen1-1-zen             | 2        | 1.18%   |
| 6.2.14-300.fc38.x86_64       | 2        | 1.18%   |
| 6.2.0-34-generic             | 2        | 1.18%   |
| 6.2.0-31-generic             | 2        | 1.18%   |
| 6.0.15-300.fc37.x86_64       | 2        | 1.18%   |
| 5.9.8-200.fc33.x86_64        | 2        | 1.18%   |
| 5.4.0-7642-generic           | 2        | 1.18%   |
| 5.4.0-70-generic             | 2        | 1.18%   |
| 5.4.0-42-generic             | 2        | 1.18%   |
| 5.4.0-40-generic             | 2        | 1.18%   |
| 5.4.0-37-generic             | 2        | 1.18%   |
| 5.3.0-51-generic             | 2        | 1.18%   |
| 5.19.0-35-generic            | 2        | 1.18%   |
| 5.16.7-desktop-1omv4003      | 2        | 1.18%   |
| 5.15.0-71-generic            | 2        | 1.18%   |
| 5.15.0-52-generic            | 2        | 1.18%   |
| 5.12.7-desktop-1omv4003      | 2        | 1.18%   |
| 5.11.0-27-generic            | 2        | 1.18%   |
| 5.0.0-36-generic             | 2        | 1.18%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2        | 1.18%   |
| 6.6.7-arch1-1                | 1        | 0.59%   |
| 6.6.2-desktop-1omv2390       | 1        | 0.59%   |
| 6.6.1-desktop-1omv2390       | 1        | 0.59%   |
| 6.5.9-zen2-1-zen             | 1        | 0.59%   |
| 6.5.9-1-default              | 1        | 0.59%   |
| 6.5.8-200.fc38.x86_64        | 1        | 0.59%   |
| 6.5.0-9-generic              | 1        | 0.59%   |
| 6.4.8-desktop-2omv2390       | 1        | 0.59%   |
| 6.4.7-desktop-1omv2390       | 1        | 0.59%   |
| 6.4.6-76060406-generic       | 1        | 0.59%   |
| 6.4.3-zen1-1-zen             | 1        | 0.59%   |
| 6.4.12-200.fc38.x86_64       | 1        | 0.59%   |
| 6.4.10-200.fc38.x86_64       | 1        | 0.59%   |
| 6.3.9-zen1-1-zen             | 1        | 0.59%   |
| 6.3.9-1-default              | 1        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 24       | 14.63%  |
| 5.15.0   | 24       | 14.63%  |
| 6.2.0    | 8        | 4.88%   |
| 5.0.0    | 7        | 4.27%   |
| 5.11.0   | 6        | 3.66%   |
| 5.10.0   | 5        | 3.05%   |
| 4.18.0   | 5        | 3.05%   |
| 4.15.0   | 4        | 2.44%   |
| 6.3.8    | 3        | 1.83%   |
| 6.2.6    | 3        | 1.83%   |
| 5.8.0    | 3        | 1.83%   |
| 5.3.0    | 3        | 1.83%   |
| 5.19.0   | 3        | 1.83%   |
| 6.5.9    | 2        | 1.22%   |
| 6.3.9    | 2        | 1.22%   |
| 6.2.14   | 2        | 1.22%   |
| 6.1.0    | 2        | 1.22%   |
| 6.0.15   | 2        | 1.22%   |
| 5.9.8    | 2        | 1.22%   |
| 5.16.7   | 2        | 1.22%   |
| 5.13.0   | 2        | 1.22%   |
| 5.12.7   | 2        | 1.22%   |
| 6.6.7    | 1        | 0.61%   |
| 6.6.2    | 1        | 0.61%   |
| 6.6.1    | 1        | 0.61%   |
| 6.5.8    | 1        | 0.61%   |
| 6.5.0    | 1        | 0.61%   |
| 6.4.8    | 1        | 0.61%   |
| 6.4.7    | 1        | 0.61%   |
| 6.4.6    | 1        | 0.61%   |
| 6.4.3    | 1        | 0.61%   |
| 6.4.12   | 1        | 0.61%   |
| 6.4.10   | 1        | 0.61%   |
| 6.3.7    | 1        | 0.61%   |
| 6.3.5    | 1        | 0.61%   |
| 6.3.4    | 1        | 0.61%   |
| 6.3.0.11 | 1        | 0.61%   |
| 6.2.9    | 1        | 0.61%   |
| 6.2.2    | 1        | 0.61%   |
| 6.1.6    | 1        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 31       | 19.02%  |
| 5.4     | 24       | 14.72%  |
| 6.2     | 14       | 8.59%   |
| 6.3     | 8        | 4.91%   |
| 6.1     | 7        | 4.29%   |
| 5.11    | 7        | 4.29%   |
| 5.10    | 7        | 4.29%   |
| 5.0     | 7        | 4.29%   |
| 6.4     | 6        | 3.68%   |
| 4.18    | 5        | 3.07%   |
| 6.5     | 4        | 2.45%   |
| 6.0     | 4        | 2.45%   |
| 5.8     | 4        | 2.45%   |
| 5.16    | 4        | 2.45%   |
| 5.13    | 4        | 2.45%   |
| 4.15    | 4        | 2.45%   |
| 6.6     | 3        | 1.84%   |
| 5.9     | 3        | 1.84%   |
| 5.3     | 3        | 1.84%   |
| 5.19    | 3        | 1.84%   |
| 5.14    | 3        | 1.84%   |
| 5.12    | 3        | 1.84%   |
| 6.3.0   | 1        | 0.61%   |
| 5.18    | 1        | 0.61%   |
| 5.17    | 1        | 0.61%   |
| 4.16    | 1        | 0.61%   |
| 3.10    | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 144      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 64       | 42.95%  |
| KDE5          | 25       | 16.78%  |
| Unknown       | 24       | 16.11%  |
| X-Cinnamon    | 13       | 8.72%   |
| XFCE          | 9        | 6.04%   |
| LXQt          | 3        | 2.01%   |
| i3            | 3        | 2.01%   |
| Unity         | 2        | 1.34%   |
| UKUI          | 1        | 0.67%   |
| MATE          | 1        | 0.67%   |
| KDE           | 1        | 0.67%   |
| GNOME Classic | 1        | 0.67%   |
| Cinnamon      | 1        | 0.67%   |
| Budgie        | 1        | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 114      | 76%     |
| Wayland | 19       | 12.67%  |
| Tty     | 9        | 6%      |
| Unknown | 8        | 5.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 46.94%  |
| SDDM    | 26       | 17.69%  |
| GDM3    | 19       | 12.93%  |
| GDM     | 18       | 12.24%  |
| LightDM | 13       | 8.84%   |
| TDM     | 1        | 0.68%   |
| GREETD  | 1        | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 61       | 41.22%  |
| en_SG   | 53       | 35.81%  |
| Unknown | 10       | 6.76%   |
| zh_CN   | 7        | 4.73%   |
| en_AU   | 4        | 2.7%    |
| C       | 4        | 2.7%    |
| de_DE   | 3        | 2.03%   |
| en_GB   | 2        | 1.35%   |
| fr_FR   | 1        | 0.68%   |
| en_PH   | 1        | 0.68%   |
| en_IN   | 1        | 0.68%   |
| en_HK   | 1        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 85       | 59.03%  |
| BIOS | 59       | 40.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 101      | 68.71%  |
| Btrfs   | 19       | 12.93%  |
| Overlay | 12       | 8.16%   |
| Xfs     | 9        | 6.12%   |
| Tmpfs   | 3        | 2.04%   |
| Unknown | 3        | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 73       | 50.34%  |
| Unknown | 59       | 40.69%  |
| MBR     | 13       | 8.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 75.51%  |
| Yes       | 36       | 24.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 62.33%  |
| Yes       | 55       | 37.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 27       | 18.75%  |
| Gigabyte Technology                  | 24       | 16.67%  |
| MSI                                  | 20       | 13.89%  |
| Dell                                 | 17       | 11.81%  |
| ASRock                               | 15       | 10.42%  |
| Hewlett-Packard                      | 8        | 5.56%   |
| Lenovo                               | 5        | 3.47%   |
| Unknown                              | 5        | 3.47%   |
| Foxconn                              | 4        | 2.78%   |
| Acer                                 | 3        | 2.08%   |
| AZW                                  | 2        | 1.39%   |
| SZMZ                                 | 1        | 0.69%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.69%   |
| Pegatron                             | 1        | 0.69%   |
| Novatte                              | 1        | 0.69%   |
| MECHREVO                             | 1        | 0.69%   |
| MACHINIST                            | 1        | 0.69%   |
| LattePanda                           | 1        | 0.69%   |
| JINGSHA                              | 1        | 0.69%   |
| Intel                                | 1        | 0.69%   |
| Huanan                               | 1        | 0.69%   |
| HPE                                  | 1        | 0.69%   |
| ECS                                  | 1        | 0.69%   |
| Biostar                              | 1        | 0.69%   |
| AMI                                  | 1        | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 5        | 3.47%   |
| Unknown                                    | 5        | 3.47%   |
| Gigabyte X570 AORUS PRO WIFI               | 4        | 2.78%   |
| MSI MS-7C84                                | 3        | 2.08%   |
| Foxconn Pro 3330 MT                        | 3        | 2.08%   |
| Dell OptiPlex 9020                         | 3        | 2.08%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 1.39%   |
| Dell OptiPlex 990                          | 2        | 1.39%   |
| ASUS ROG STRIX B550-I GAMING               | 2        | 1.39%   |
| ASRock B450 Pro4                           | 2        | 1.39%   |
| SZMZ X99M-H2                               | 1        | 0.69%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.69%   |
| Pegatron 23-d018d                          | 1        | 0.69%   |
| Novatte M20                                | 1        | 0.69%   |
| MSI MS-7E06                                | 1        | 0.69%   |
| MSI MS-7D82                                | 1        | 0.69%   |
| MSI MS-7D43                                | 1        | 0.69%   |
| MSI MS-7D42                                | 1        | 0.69%   |
| MSI MS-7D30                                | 1        | 0.69%   |
| MSI MS-7D25                                | 1        | 0.69%   |
| MSI MS-7C95                                | 1        | 0.69%   |
| MSI MS-7C91                                | 1        | 0.69%   |
| MSI MS-7C52                                | 1        | 0.69%   |
| MSI MS-7C02                                | 1        | 0.69%   |
| MSI MS-7B89                                | 1        | 0.69%   |
| MSI MS-7A94                                | 1        | 0.69%   |
| MSI MS-7A32                                | 1        | 0.69%   |
| MSI MS-7821                                | 1        | 0.69%   |
| MSI MS-7817                                | 1        | 0.69%   |
| MSI MS-7721                                | 1        | 0.69%   |
| MSI KT308AA-AB4 SR5472CF                   | 1        | 0.69%   |
| MECHREVO F7BFD V1.0                        | 1        | 0.69%   |
| MACHINIST B75 PRO V1.0                     | 1        | 0.69%   |
| Lenovo ThinkStation P620 30E1S3VH00        | 1        | 0.69%   |
| Lenovo ThinkStation P310 30ASS2WG00        | 1        | 0.69%   |
| Lenovo ThinkCentre M90p 5864BM3            | 1        | 0.69%   |
| Lenovo ThinkCentre M73 10AXS26C00          | 1        | 0.69%   |
| Lenovo ThinkCentre M72e 36601Y8            | 1        | 0.69%   |
| LattePanda Alpha                           | 1        | 0.69%   |
| JINGSHA X99-D8I                            | 1        | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 11       | 7.64%   |
| ASUS ROG                                   | 6        | 4.17%   |
| ASUS All                                   | 5        | 3.47%   |
| Unknown                                    | 5        | 3.47%   |
| Gigabyte X570                              | 4        | 2.78%   |
| MSI MS-7C84                                | 3        | 2.08%   |
| Lenovo ThinkCentre                         | 3        | 2.08%   |
| Foxconn Pro                                | 3        | 2.08%   |
| Dell Precision                             | 3        | 2.08%   |
| ASUS PRIME                                 | 3        | 2.08%   |
| Lenovo ThinkStation                        | 2        | 1.39%   |
| HP ProDesk                                 | 2        | 1.39%   |
| Gigabyte B550I                             | 2        | 1.39%   |
| Gigabyte B450M                             | 2        | 1.39%   |
| Gigabyte B365M                             | 2        | 1.39%   |
| ASRock B450                                | 2        | 1.39%   |
| Acer Veriton                               | 2        | 1.39%   |
| SZMZ X99M-H2                               | 1        | 0.69%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.69%   |
| Pegatron 23-d018d                          | 1        | 0.69%   |
| Novatte M20                                | 1        | 0.69%   |
| MSI MS-7E06                                | 1        | 0.69%   |
| MSI MS-7D82                                | 1        | 0.69%   |
| MSI MS-7D43                                | 1        | 0.69%   |
| MSI MS-7D42                                | 1        | 0.69%   |
| MSI MS-7D30                                | 1        | 0.69%   |
| MSI MS-7D25                                | 1        | 0.69%   |
| MSI MS-7C95                                | 1        | 0.69%   |
| MSI MS-7C91                                | 1        | 0.69%   |
| MSI MS-7C52                                | 1        | 0.69%   |
| MSI MS-7C02                                | 1        | 0.69%   |
| MSI MS-7B89                                | 1        | 0.69%   |
| MSI MS-7A94                                | 1        | 0.69%   |
| MSI MS-7A32                                | 1        | 0.69%   |
| MSI MS-7821                                | 1        | 0.69%   |
| MSI MS-7817                                | 1        | 0.69%   |
| MSI MS-7721                                | 1        | 0.69%   |
| MSI KT308AA-AB4                            | 1        | 0.69%   |
| MECHREVO F7BFD                             | 1        | 0.69%   |
| MACHINIST B75                              | 1        | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 18       | 12.5%   |
| 2013 | 17       | 11.81%  |
| 2018 | 16       | 11.11%  |
| 2019 | 13       | 9.03%   |
| 2021 | 12       | 8.33%   |
| 2012 | 10       | 6.94%   |
| 2011 | 10       | 6.94%   |
| 2016 | 7        | 4.86%   |
| 2014 | 7        | 4.86%   |
| 2023 | 6        | 4.17%   |
| 2022 | 6        | 4.17%   |
| 2017 | 6        | 4.17%   |
| 2010 | 6        | 4.17%   |
| 2015 | 5        | 3.47%   |
| 2008 | 2        | 1.39%   |
| 2007 | 2        | 1.39%   |
| 2009 | 1        | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 144      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 141      | 97.92%  |
| Enabled  | 3        | 2.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 144      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 34       | 23.13%  |
| 4.01-8.0        | 28       | 19.05%  |
| 32.01-64.0      | 28       | 19.05%  |
| 8.01-16.0       | 22       | 14.97%  |
| 64.01-256.0     | 13       | 8.84%   |
| 3.01-4.0        | 9        | 6.12%   |
| 24.01-32.0      | 8        | 5.44%   |
| More than 256.0 | 3        | 2.04%   |
| 1.01-2.0        | 2        | 1.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 45       | 28.66%  |
| 2.01-3.0   | 36       | 22.93%  |
| 3.01-4.0   | 31       | 19.75%  |
| 4.01-8.0   | 26       | 16.56%  |
| 8.01-16.0  | 9        | 5.73%   |
| 0.51-1.0   | 6        | 3.82%   |
| 16.01-24.0 | 2        | 1.27%   |
| 32.01-64.0 | 1        | 0.64%   |
| 0.01-0.5   | 1        | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 35.76%  |
| 2      | 42       | 27.81%  |
| 3      | 28       | 18.54%  |
| 4      | 15       | 9.93%   |
| 5      | 8        | 5.3%    |
| 6      | 2        | 1.32%   |
| 0      | 2        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 68.97%  |
| Yes       | 45       | 31.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 143      | 99.31%  |
| No        | 1        | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 53.02%  |
| No        | 70       | 46.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 59.31%  |
| Yes       | 59       | 40.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 144      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 136      | 93.79%  |
| Kampong Pasir Ris | 5        | 3.45%   |
| Jurong West       | 3        | 2.07%   |
| Queenstown Estate | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 49       | 79     | 17.95%  |
| Seagate                      | 40       | 51     | 14.65%  |
| WDC                          | 37       | 66     | 13.55%  |
| Toshiba                      | 22       | 28     | 8.06%   |
| SanDisk                      | 17       | 21     | 6.23%   |
| Unknown                      | 10       | 12     | 3.66%   |
| Crucial                      | 10       | 14     | 3.66%   |
| Kingston                     | 9        | 13     | 3.3%    |
| Hitachi                      | 7        | 8      | 2.56%   |
| Silicon Motion               | 4        | 6      | 1.47%   |
| A-DATA Technology            | 4        | 4      | 1.47%   |
| Plextor                      | 3        | 3      | 1.1%    |
| Phison Electronics           | 3        | 4      | 1.1%    |
| Phison                       | 3        | 3      | 1.1%    |
| Micron/Crucial Technology    | 3        | 4      | 1.1%    |
| JMicron Technology           | 3        | 4      | 1.1%    |
| Intel                        | 3        | 3      | 1.1%    |
| HGST                         | 3        | 5      | 1.1%    |
| China                        | 3        | 3      | 1.1%    |
| Transcend                    | 2        | 2      | 0.73%   |
| SK hynix                     | 2        | 2      | 0.73%   |
| Maxtor                       | 2        | 2      | 0.73%   |
| Lexar                        | 2        | 2      | 0.73%   |
| KLEVV                        | 2        | 2      | 0.73%   |
| Kingston Technology Company  | 2        | 2      | 0.73%   |
| Hewlett-Packard              | 2        | 2      | 0.73%   |
| Yangtze Memory Technologies  | 1        | 1      | 0.37%   |
| WALRAM                       | 1        | 1      | 0.37%   |
| Vaseky                       | 1        | 1      | 0.37%   |
| USB30                        | 1        | 1      | 0.37%   |
| Teclast                      | 1        | 1      | 0.37%   |
| SSK                          | 1        | 1      | 0.37%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.37%   |
| SABRENT                      | 1        | 2      | 0.37%   |
| PNY                          | 1        | 1      | 0.37%   |
| Pioneer                      | 1        | 1      | 0.37%   |
| OCZ                          | 1        | 1      | 0.37%   |
| Mushkin                      | 1        | 1      | 0.37%   |
| MARVELL                      | 1        | 1      | 0.37%   |
| LITEONIT                     | 1        | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 9        | 2.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 6        | 1.9%    |
| Toshiba DT01ACA200 2TB                                | 5        | 1.58%   |
| Samsung SSD 850 EVO 250GB                             | 5        | 1.58%   |
| Seagate ST500DM002-1BD142 500GB                       | 4        | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB                        | 4        | 1.27%   |
| SanDisk NVMe SSD Drive 500GB                          | 4        | 1.27%   |
| Samsung SSD 980 500GB                                 | 4        | 1.27%   |
| Samsung SSD 860 EVO 500GB                             | 4        | 1.27%   |
| Samsung SSD 860 EVO 1TB                               | 4        | 1.27%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 3        | 0.95%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 0.95%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 3        | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3        | 0.95%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.95%   |
| Samsung SSD 980 PRO 1TB                               | 3        | 0.95%   |
| JMicron Generic 250GB                                 | 3        | 0.95%   |
| Crucial CT500MX500SSD1 500GB                          | 3        | 0.95%   |
| A-DATA HC660 1TB SSD                                  | 3        | 0.95%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 2        | 0.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 2        | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2        | 0.63%   |
| Toshiba HDWD110 1TB                                   | 2        | 0.63%   |
| Toshiba DT01ACA050 500GB                              | 2        | 0.63%   |
| SK hynix SC311 SATA 128GB SSD                         | 2        | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                        | 2        | 0.63%   |
| Seagate Expansion HDD 2TB                             | 2        | 0.63%   |
| Seagate BUP Portable 5TB                              | 2        | 0.63%   |
| SanDisk SSD PLUS 480GB                                | 2        | 0.63%   |
| SanDisk SSD PLUS 1000GB                               | 2        | 0.63%   |
| SanDisk NVMe SSD Drive 1TB                            | 2        | 0.63%   |
| Samsung SSD 980 1TB                                   | 2        | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2        | 0.63%   |
| Samsung SSD 960 EVO 250GB                             | 2        | 0.63%   |
| Samsung NVMe SSD Drive 500GB                          | 2        | 0.63%   |
| Samsung NVMe SSD Drive 1024GB                         | 2        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 2        | 0.63%   |
| Samsung HN-M750MBB 752GB                              | 2        | 0.63%   |
| Plextor PX-128M6S 128GB SSD                           | 2        | 0.63%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 39       | 50     | 35.45%  |
| WDC                 | 32       | 59     | 29.09%  |
| Toshiba             | 20       | 26     | 18.18%  |
| Hitachi             | 7        | 8      | 6.36%   |
| Samsung Electronics | 4        | 4      | 3.64%   |
| HGST                | 3        | 5      | 2.73%   |
| Maxtor              | 2        | 2      | 1.82%   |
| Unknown             | 1        | 1      | 0.91%   |
| SSK                 | 1        | 1      | 0.91%   |
| MARVELL             | 1        | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 33     | 28.57%  |
| SanDisk             | 9        | 9      | 9.89%   |
| Crucial             | 8        | 12     | 8.79%   |
| Kingston            | 7        | 9      | 7.69%   |
| WDC                 | 3        | 3      | 3.3%    |
| Plextor             | 3        | 3      | 3.3%    |
| JMicron Technology  | 3        | 4      | 3.3%    |
| China               | 3        | 3      | 3.3%    |
| A-DATA Technology   | 3        | 3      | 3.3%    |
| Transcend           | 2        | 2      | 2.2%    |
| SK hynix            | 2        | 2      | 2.2%    |
| Intel               | 2        | 2      | 2.2%    |
| Hewlett-Packard     | 2        | 2      | 2.2%    |
| WALRAM              | 1        | 1      | 1.1%    |
| Vaseky              | 1        | 1      | 1.1%    |
| USB30               | 1        | 1      | 1.1%    |
| Unknown             | 1        | 1      | 1.1%    |
| Teclast             | 1        | 1      | 1.1%    |
| Pioneer             | 1        | 1      | 1.1%    |
| OCZ                 | 1        | 1      | 1.1%    |
| LITEONIT            | 1        | 1      | 1.1%    |
| Lexar               | 1        | 1      | 1.1%    |
| KLEVV               | 1        | 1      | 1.1%    |
| KingSpec            | 1        | 1      | 1.1%    |
| Kingmax             | 1        | 1      | 1.1%    |
| KINGBANK            | 1        | 1      | 1.1%    |
| GAMER               | 1        | 1      | 1.1%    |
| GALAX               | 1        | 1      | 1.1%    |
| Fanxiang            | 1        | 1      | 1.1%    |
| Apacer              | 1        | 1      | 1.1%    |
| Unknown             | 1        | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 88       | 157    | 39.29%  |
| SSD     | 70       | 105    | 31.25%  |
| NVMe    | 57       | 100    | 25.45%  |
| Unknown | 5        | 7      | 2.23%   |
| MMC     | 4        | 4      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 120      | 248    | 60%     |
| NVMe | 57       | 98     | 28.5%   |
| SAS  | 19       | 23     | 9.5%    |
| MMC  | 4        | 4      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 81       | 117    | 44.75%  |
| 0.51-1.0   | 52       | 76     | 28.73%  |
| 1.01-2.0   | 25       | 32     | 13.81%  |
| 3.01-4.0   | 9        | 12     | 4.97%   |
| 4.01-10.0  | 8        | 17     | 4.42%   |
| 2.01-3.0   | 5        | 5      | 2.76%   |
| 10.01-20.0 | 1        | 3      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 32       | 20.92%  |
| 101-250        | 25       | 16.34%  |
| More than 3000 | 20       | 13.07%  |
| 251-500        | 20       | 13.07%  |
| 1001-2000      | 17       | 11.11%  |
| 2001-3000      | 12       | 7.84%   |
| 1-20           | 12       | 7.84%   |
| Unknown        | 8        | 5.23%   |
| 51-100         | 4        | 2.61%   |
| 21-50          | 3        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 39       | 25.16%  |
| 21-50          | 28       | 18.06%  |
| 101-250        | 22       | 14.19%  |
| 251-500        | 17       | 10.97%  |
| 51-100         | 12       | 7.74%   |
| 501-1000       | 11       | 7.1%    |
| 1001-2000      | 10       | 6.45%   |
| Unknown        | 8        | 5.16%   |
| More than 3000 | 7        | 4.52%   |
| 2001-3000      | 1        | 0.65%   |

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
| Detected | 82       | 177    | 47.13%  |
| Works    | 74       | 171    | 42.53%  |
| Malfunc  | 17       | 24     | 9.77%   |
| Failed   | 1        | 1      | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 93       | 41.15%  |
| AMD                          | 44       | 19.47%  |
| Samsung Electronics          | 29       | 12.83%  |
| SanDisk                      | 12       | 5.31%   |
| ASMedia Technology           | 9        | 3.98%   |
| Silicon Motion               | 6        | 2.65%   |
| Phison Electronics           | 6        | 2.65%   |
| Micron/Crucial Technology    | 5        | 2.21%   |
| Kingston Technology Company  | 4        | 1.77%   |
| Marvell Technology Group     | 3        | 1.33%   |
| Toshiba America Info Systems | 2        | 0.88%   |
| Shenzhen Longsys Electronics | 2        | 0.88%   |
| Realtek Semiconductor        | 2        | 0.88%   |
| Adaptec                      | 2        | 0.88%   |
| Yangtze Memory Technologies  | 1        | 0.44%   |
| VIA Technologies             | 1        | 0.44%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.44%   |
| KIOXIA                       | 1        | 0.44%   |
| JMicron Technology           | 1        | 0.44%   |
| INNOGRIT                     | 1        | 0.44%   |
| Broadcom / LSI               | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 10.89%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15       | 5.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 5.45%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 3.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 3.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 3.11%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.95%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 1.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.56%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.17%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.17%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 2        | 0.78%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.78%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 2        | 0.78%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 0.78%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.78%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.78%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                                  | 2        | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.78%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.78%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 0.78%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 120      | 57.42%  |
| NVMe | 57       | 27.27%  |
| IDE  | 16       | 7.66%   |
| RAID | 12       | 5.74%   |
| SAS  | 4        | 1.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 98       | 68.06%  |
| AMD    | 46       | 31.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 4.17%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 2.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 2.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.39%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.39%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 1.39%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.39%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.39%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.39%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.39%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.39%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.39%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores  | 2        | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.39%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.39%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 1.39%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.39%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.39%   |
| Intel Xeon W-2155 CPU @ 3.30GHz             | 1        | 0.69%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.69%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz         | 1        | 0.69%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz         | 1        | 0.69%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.69%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 0.69%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.69%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 0.69%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 0.69%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.69%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 0.69%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.69%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.69%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.69%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.69%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.69%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.69%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.69%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 35       | 24.31%  |
| AMD Ryzen 5            | 17       | 11.81%  |
| Intel Core i7          | 16       | 11.11%  |
| Intel Xeon             | 13       | 9.03%   |
| Other                  | 9        | 6.25%   |
| Intel Core i3          | 9        | 6.25%   |
| AMD Ryzen 7            | 9        | 6.25%   |
| AMD Ryzen 9            | 5        | 3.47%   |
| Intel Celeron          | 4        | 2.78%   |
| AMD Ryzen Threadripper | 3        | 2.08%   |
| Intel Pentium          | 2        | 1.39%   |
| Intel Core i9          | 2        | 1.39%   |
| Intel Core 2 Quad      | 2        | 1.39%   |
| AMD FX                 | 2        | 1.39%   |
| AMD Athlon             | 2        | 1.39%   |
| AMD A10                | 2        | 1.39%   |
| Intel Pentium Silver   | 1        | 0.69%   |
| Intel Pentium Gold     | 1        | 0.69%   |
| Intel Pentium Dual     | 1        | 0.69%   |
| Intel Pentium 4        | 1        | 0.69%   |
| Intel Core m3          | 1        | 0.69%   |
| Intel Atom             | 1        | 0.69%   |
| AMD Ryzen 5 PRO        | 1        | 0.69%   |
| AMD Ryzen 3            | 1        | 0.69%   |
| AMD PRO A10            | 1        | 0.69%   |
| AMD Phenom II X6       | 1        | 0.69%   |
| AMD Phenom II X4       | 1        | 0.69%   |
| AMD Opteron            | 1        | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 58       | 40.28%  |
| 6      | 28       | 19.44%  |
| 2      | 20       | 13.89%  |
| 8      | 15       | 10.42%  |
| 12     | 8        | 5.56%   |
| 16     | 6        | 4.17%   |
| 10     | 3        | 2.08%   |
| 32     | 1        | 0.69%   |
| 24     | 1        | 0.69%   |
| 22     | 1        | 0.69%   |
| 14     | 1        | 0.69%   |
| 3      | 1        | 0.69%   |
| 1      | 1        | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 143      | 99.31%  |
| 2      | 1        | 0.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 91       | 63.19%  |
| 1      | 53       | 36.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 143      | 99.31%  |
| Unknown        | 1        | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 27.15%  |
| 0x306c3    | 12       | 7.95%   |
| 0x306a9    | 9        | 5.96%   |
| 0x906ea    | 8        | 5.3%    |
| 0x506e3    | 7        | 4.64%   |
| 0x08701021 | 6        | 3.97%   |
| 0x206a7    | 5        | 3.31%   |
| 0x90672    | 4        | 2.65%   |
| 0x306e4    | 4        | 2.65%   |
| 0x20655    | 4        | 2.65%   |
| 0x0a201016 | 3        | 1.99%   |
| 0x08701013 | 3        | 1.99%   |
| 0x06003106 | 3        | 1.99%   |
| 0x906e9    | 2        | 1.32%   |
| 0x906c0    | 2        | 1.32%   |
| 0x50654    | 2        | 1.32%   |
| 0x406f1    | 2        | 1.32%   |
| 0x0a50000d | 2        | 1.32%   |
| 0x0a20120a | 2        | 1.32%   |
| 0x06000852 | 2        | 1.32%   |
| 0xf41      | 1        | 0.66%   |
| 0xb06e0    | 1        | 0.66%   |
| 0xa0671    | 1        | 0.66%   |
| 0xa0655    | 1        | 0.66%   |
| 0x706a1    | 1        | 0.66%   |
| 0x6fd      | 1        | 0.66%   |
| 0x6fb      | 1        | 0.66%   |
| 0x1067a    | 1        | 0.66%   |
| 0x0a601203 | 1        | 0.66%   |
| 0x0a601201 | 1        | 0.66%   |
| 0x0a50000c | 1        | 0.66%   |
| 0x0a404102 | 1        | 0.66%   |
| 0x0a201009 | 1        | 0.66%   |
| 0x08600106 | 1        | 0.66%   |
| 0x0830107a | 1        | 0.66%   |
| 0x0830104d | 1        | 0.66%   |
| 0x08301039 | 1        | 0.66%   |
| 0x08108109 | 1        | 0.66%   |
| 0x08101102 | 1        | 0.66%   |
| 0x08101016 | 1        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 18       | 12.5%   |
| IvyBridge        | 17       | 11.81%  |
| Zen 2            | 15       | 10.42%  |
| KabyLake         | 14       | 9.72%   |
| Zen 3            | 11       | 7.64%   |
| Skylake          | 9        | 6.25%   |
| SandyBridge      | 7        | 4.86%   |
| Westmere         | 6        | 4.17%   |
| Alderlake Hybrid | 6        | 4.17%   |
| Unknown          | 6        | 4.17%   |
| Zen+             | 4        | 2.78%   |
| Zen              | 4        | 2.78%   |
| CometLake        | 4        | 2.78%   |
| Steamroller      | 3        | 2.08%   |
| K10              | 3        | 2.08%   |
| Broadwell        | 3        | 2.08%   |
| Tremont          | 2        | 1.39%   |
| Silvermont       | 2        | 1.39%   |
| Piledriver       | 2        | 1.39%   |
| Core             | 2        | 1.39%   |
| Penryn           | 1        | 0.69%   |
| NetBurst         | 1        | 0.69%   |
| Icelake          | 1        | 0.69%   |
| Goldmont plus    | 1        | 0.69%   |
| Goldmont         | 1        | 0.69%   |
| Excavator        | 1        | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 66       | 38.82%  |
| Intel             | 60       | 35.29%  |
| AMD               | 43       | 25.29%  |
| ASPEED Technology | 1        | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.86%   |
| Intel HD Graphics 530                                                       | 5        | 2.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.29%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.29%   |
| Intel AlderLake-S GT1                                                       | 4        | 2.29%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.71%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.71%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 1.71%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.71%   |
| Intel JasperLake [UHD Graphics]                                             | 3        | 1.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.71%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 1.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 1.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.14%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.14%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.14%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.14%   |
| Nvidia GF119 [GeForce 605]                                                  | 2        | 1.14%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 1.14%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 1.14%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 1.14%   |
| Intel HD Graphics 630                                                       | 2        | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.14%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.14%   |
| AMD Raphael                                                                 | 2        | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.14%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.14%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.14%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]            | 2        | 1.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.14%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 52       | 34.67%  |
| 1 x Intel       | 45       | 30%     |
| 1 x AMD         | 33       | 22%     |
| Intel + Nvidia  | 6        | 4%      |
| 2 x Nvidia      | 4        | 2.67%   |
| Intel + AMD     | 4        | 2.67%   |
| AMD + Nvidia    | 3        | 2%      |
| 2 x AMD         | 2        | 1.33%   |
| Nvidia + ASPEED | 1        | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 94       | 63.95%  |
| Proprietary | 47       | 31.97%  |
| Unknown     | 6        | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 40.67%  |
| 1.01-2.0   | 20       | 13.33%  |
| 7.01-8.0   | 16       | 10.67%  |
| 3.01-4.0   | 15       | 10%     |
| 8.01-16.0  | 12       | 8%      |
| 0.51-1.0   | 12       | 8%      |
| 0.01-0.5   | 7        | 4.67%   |
| 5.01-6.0   | 6        | 4%      |
| 16.01-24.0 | 1        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 39       | 26.17%  |
| Samsung Electronics  | 17       | 11.41%  |
| Hewlett-Packard      | 12       | 8.05%   |
| Goldstar             | 10       | 6.71%   |
| Acer                 | 9        | 6.04%   |
| AOC                  | 7        | 4.7%    |
| Philips              | 6        | 4.03%   |
| ViewSonic            | 3        | 2.01%   |
| PRISM+               | 3        | 2.01%   |
| Denver               | 3        | 2.01%   |
| Unknown (XXX)        | 2        | 1.34%   |
| Sharp                | 2        | 1.34%   |
| Pixio                | 2        | 1.34%   |
| Lenovo Group Limited | 2        | 1.34%   |
| Lenovo               | 2        | 1.34%   |
| AU Optronics         | 2        | 1.34%   |
| ASUSTek Computer     | 2        | 1.34%   |
| Ancor Communications | 2        | 1.34%   |
| Unknown              | 2        | 1.34%   |
| Xiaomi               | 1        | 0.67%   |
| Wacom                | 1        | 0.67%   |
| Toshiba              | 1        | 0.67%   |
| Sony                 | 1        | 0.67%   |
| SGT                  | 1        | 0.67%   |
| SAC                  | 1        | 0.67%   |
| RTK                  | 1        | 0.67%   |
| MSI                  | 1        | 0.67%   |
| Mi                   | 1        | 0.67%   |
| LG Electronics       | 1        | 0.67%   |
| InnoView             | 1        | 0.67%   |
| IDV                  | 1        | 0.67%   |
| HPN                  | 1        | 0.67%   |
| HPD                  | 1        | 0.67%   |
| HKC                  | 1        | 0.67%   |
| GLE                  | 1        | 0.67%   |
| Fujitsu Siemens      | 1        | 0.67%   |
| CVT                  | 1        | 0.67%   |
| CHR                  | 1        | 0.67%   |
| CGC                  | 1        | 0.67%   |
| AUS                  | 1        | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 4        | 2.56%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 2        | 1.28%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 2        | 1.28%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch                 | 2        | 1.28%   |
| Pixio U27I4K WAM2700 3840x2160 600x330mm 27.0-inch                      | 2        | 1.28%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                   | 2        | 1.28%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 2        | 1.28%   |
| Denver GB-2461CF LHC0236 1920x1080 530x280mm 23.6-inch                  | 2        | 1.28%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                     | 2        | 1.28%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                       | 2        | 1.28%   |
| Dell LCD Monitor P2217H 1920x1080                                       | 2        | 1.28%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                      | 2        | 1.28%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                       | 2        | 1.28%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                        | 2        | 1.28%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                        | 2        | 1.28%   |
| Dell D2015H DELF063 1920x1080 440x240mm 19.7-inch                       | 2        | 1.28%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                        | 2        | 1.28%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                        | 2        | 1.28%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                     | 2        | 1.28%   |
| Unknown                                                                 | 2        | 1.28%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                       | 1        | 0.64%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 0.64%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 0.64%   |
| ViewSonic VX2480-2K VSC7B3B 2560x1440 530x300mm 24.0-inch               | 1        | 0.64%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                               | 1        | 0.64%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1        | 0.64%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 0.64%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                       | 1        | 0.64%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                           | 1        | 0.64%   |
| Sharp HDMI SHP1197 1920x1080 1103x622mm 49.9-inch                       | 1        | 0.64%   |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                        | 1        | 0.64%   |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                     | 1        | 0.64%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.64%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch       | 1        | 0.64%   |
| Samsung Electronics S22C300 SAM0A1D 1920x1080 477x268mm 21.5-inch       | 1        | 0.64%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.64%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0F18 3840x2160 1872x1053mm 84.6-inch | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1110x620mm 50.1-inch  | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch   | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 75       | 50.34%  |
| 2560x1440 (QHD)    | 23       | 15.44%  |
| 3840x2160 (4K)     | 22       | 14.77%  |
| 1600x900 (HD+)     | 12       | 8.05%   |
| 3440x1440          | 2        | 1.34%   |
| 2560x1600          | 2        | 1.34%   |
| 2560x1080          | 2        | 1.34%   |
| 1680x1050 (WSXGA+) | 2        | 1.34%   |
| 1366x768 (WXGA)    | 2        | 1.34%   |
| 1360x768           | 2        | 1.34%   |
| 1280x1024 (SXGA)   | 2        | 1.34%   |
| 7680x2160          | 1        | 0.67%   |
| 1440x900 (WXGA+)   | 1        | 0.67%   |
| Unknown            | 1        | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 24       | 16.44%  |
| 23      | 20       | 13.7%   |
| Unknown | 19       | 13.01%  |
| 24      | 15       | 10.27%  |
| 21      | 15       | 10.27%  |
| 20      | 8        | 5.48%   |
| 19      | 7        | 4.79%   |
| 31      | 6        | 4.11%   |
| 18      | 4        | 2.74%   |
| 54      | 3        | 2.05%   |
| 28      | 3        | 2.05%   |
| 15      | 3        | 2.05%   |
| 84      | 2        | 1.37%   |
| 40      | 2        | 1.37%   |
| 32      | 2        | 1.37%   |
| 72      | 1        | 0.68%   |
| 65      | 1        | 0.68%   |
| 55      | 1        | 0.68%   |
| 50      | 1        | 0.68%   |
| 49      | 1        | 0.68%   |
| 39      | 1        | 0.68%   |
| 34      | 1        | 0.68%   |
| 33      | 1        | 0.68%   |
| 26      | 1        | 0.68%   |
| 25      | 1        | 0.68%   |
| 22      | 1        | 0.68%   |
| 17      | 1        | 0.68%   |
| 16      | 1        | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 57       | 39.86%  |
| 401-500     | 33       | 23.08%  |
| Unknown     | 19       | 13.29%  |
| 601-700     | 10       | 6.99%   |
| 1001-1500   | 7        | 4.9%    |
| 701-800     | 4        | 2.8%    |
| 301-350     | 4        | 2.8%    |
| 801-900     | 3        | 2.1%    |
| 351-400     | 3        | 2.1%    |
| 1501-2000   | 3        | 2.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 112      | 80%     |
| Unknown | 17       | 12.14%  |
| 16/10   | 5        | 3.57%   |
| 21/9    | 3        | 2.14%   |
| 5/4     | 2        | 1.43%   |
| 6/5     | 1        | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 29.66%  |
| 301-350        | 24       | 16.55%  |
| 151-200        | 20       | 13.79%  |
| Unknown        | 19       | 13.1%   |
| 351-500        | 12       | 8.28%   |
| More than 1000 | 10       | 6.9%    |
| 251-300        | 6        | 4.14%   |
| 141-150        | 4        | 2.76%   |
| 101-110        | 4        | 2.76%   |
| 501-1000       | 3        | 2.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 72       | 48.98%  |
| 101-120 | 32       | 21.77%  |
| Unknown | 19       | 12.93%  |
| 121-160 | 10       | 6.8%    |
| 161-240 | 8        | 5.44%   |
| 1-50    | 6        | 4.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 123      | 82%     |
| 2     | 17       | 11.33%  |
| 0     | 9        | 6%      |
| 3     | 1        | 0.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 89       | 41.78%  |
| Intel                 | 75       | 35.21%  |
| Qualcomm Atheros      | 12       | 5.63%   |
| TP-Link               | 7        | 3.29%   |
| Broadcom              | 6        | 2.82%   |
| MediaTek              | 5        | 2.35%   |
| Ralink Technology     | 4        | 1.88%   |
| ASUSTek Computer      | 3        | 1.41%   |
| Aquantia              | 3        | 1.41%   |
| Samsung Electronics   | 2        | 0.94%   |
| Qualcomm              | 1        | 0.47%   |
| Linksys               | 1        | 0.47%   |
| Hewlett-Packard       | 1        | 0.47%   |
| Fargo                 | 1        | 0.47%   |
| Exar                  | 1        | 0.47%   |
| Edimax Technology     | 1        | 0.47%   |
| ASIX Electronics      | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 27.46%  |
| Intel Wi-Fi 6 AX200                                               | 15       | 6.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 4.92%   |
| Intel Ethernet Controller I225-V                                  | 12       | 4.92%   |
| Intel I211 Gigabit Network Connection                             | 10       | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 2.87%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.64%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.23%   |
| Intel Wireless 3165                                               | 3        | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 3        | 1.23%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 3        | 1.23%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2        | 0.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.82%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 0.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.82%   |
| Realtek 802.11ac NIC                                              | 2        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.82%   |
| Intel Wireless 7260                                               | 2        | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.82%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.82%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.41%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.41%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1        | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 38       | 47.5%   |
| Realtek Semiconductor | 10       | 12.5%   |
| TP-Link               | 7        | 8.75%   |
| Qualcomm Atheros      | 7        | 8.75%   |
| MediaTek              | 5        | 6.25%   |
| Ralink Technology     | 4        | 5%      |
| Broadcom              | 4        | 5%      |
| ASUSTek Computer      | 3        | 3.75%   |
| Linksys               | 1        | 1.25%   |
| Edimax Technology     | 1        | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 15       | 18.52%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 4        | 4.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 4        | 4.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 4        | 4.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 3        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                 | 3        | 3.7%    |
| Intel Wireless 3165                                             | 3        | 3.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3        | 3.7%    |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3        | 3.7%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                      | 2        | 2.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 2        | 2.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                 | 2        | 2.47%   |
| Realtek 802.11ac NIC                                            | 2        | 2.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 2        | 2.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 2        | 2.47%   |
| Intel Wireless 7260                                             | 2        | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 2.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 1.23%   |
| TP-Link Archer T4U ver.3                                        | 1        | 1.23%   |
| TP-Link 802.11ac WLAN Adapter                                   | 1        | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 1.23%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter           | 1        | 1.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 1        | 1.23%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter             | 1        | 1.23%   |
| Intel Wireless-AC 9260                                          | 1        | 1.23%   |
| Intel Wireless 8260                                             | 1        | 1.23%   |
| Intel Wireless 7265                                             | 1        | 1.23%   |
| Intel Wireless 3160                                             | 1        | 1.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 1        | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1        | 1.23%   |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 1.23%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.23%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter    | 1        | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 84       | 54.19%  |
| Intel                 | 56       | 36.13%  |
| Qualcomm Atheros      | 5        | 3.23%   |
| Aquantia              | 3        | 1.94%   |
| Samsung Electronics   | 2        | 1.29%   |
| Broadcom              | 2        | 1.29%   |
| Qualcomm              | 1        | 0.65%   |
| Hewlett-Packard       | 1        | 0.65%   |
| ASIX Electronics      | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 41.61%  |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 7.45%   |
| Intel Ethernet Controller I225-V                                  | 12       | 7.45%   |
| Intel I211 Gigabit Network Connection                             | 10       | 6.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.11%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.48%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.24%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.24%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.24%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.24%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.24%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.62%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.62%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.62%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.62%   |
| Intel Ethernet Controller X550                                    | 1        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.62%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.62%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.62%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.62%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.62%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1        | 0.62%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.62%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 143      | 64.13%  |
| WiFi     | 78       | 34.98%  |
| Modem    | 1        | 0.45%   |
| Unknown  | 1        | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 71.43%  |
| WiFi     | 43       | 27.92%  |
| Unknown  | 1        | 0.65%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 50%     |
| 2     | 66       | 45.83%  |
| 3     | 4        | 2.78%   |
| 0     | 2        | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 136      | 94.44%  |
| Yes  | 8        | 5.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 48.44%  |
| Cambridge Silicon Radio         | 11       | 17.19%  |
| TP-Link                         | 5        | 7.81%   |
| Realtek Semiconductor           | 5        | 7.81%   |
| MediaTek                        | 5        | 7.81%   |
| Qualcomm Atheros Communications | 3        | 4.69%   |
| Broadcom                        | 2        | 3.13%   |
| SINO WEALTH                     | 1        | 1.56%   |
| Unknown                         | 1        | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 12       | 18.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 17.19%  |
| Intel Bluetooth wireless interface                  | 7        | 10.94%  |
| TP-Link TP-Cdj+ UB5A Adapter                        | 5        | 7.81%   |
| MediaTek Wireless_Device                            | 5        | 7.81%   |
| Realtek Bluetooth Radio                             | 3        | 4.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 4.69%   |
| Intel AX210 Bluetooth                               | 3        | 4.69%   |
| Intel AX201 Bluetooth                               | 3        | 4.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 3.13%   |
| Intel Bluetooth Device                              | 2        | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 3.13%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.56%   |
| Unknown                                             | 1        | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 96       | 39.83%  |
| Nvidia                                       | 61       | 25.31%  |
| AMD                                          | 51       | 21.16%  |
| C-Media Electronics                          | 4        | 1.66%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.83%   |
| SteelSeries ApS                              | 2        | 0.83%   |
| Giga-Byte Technology                         | 2        | 0.83%   |
| Creative Labs                                | 2        | 0.83%   |
| ASUSTek Computer                             | 2        | 0.83%   |
| XMOS                                         | 1        | 0.41%   |
| TTGK Technology                              | 1        | 0.41%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.41%   |
| Texas Instruments                            | 1        | 0.41%   |
| Tenx Technology                              | 1        | 0.41%   |
| Sony                                         | 1        | 0.41%   |
| Setek Elektronik                             | 1        | 0.41%   |
| SAVITECH                                     | 1        | 0.41%   |
| Samson Technologies                          | 1        | 0.41%   |
| RODE Microphones                             | 1        | 0.41%   |
| Realtek Semiconductor                        | 1        | 0.41%   |
| MV                                           | 1        | 0.41%   |
| Micro Star International                     | 1        | 0.41%   |
| Logitech                                     | 1        | 0.41%   |
| JMTek                                        | 1        | 0.41%   |
| Huawei Technologies                          | 1        | 0.41%   |
| FiiO Electronics Technology                  | 1        | 0.41%   |
| DSEA A/S                                     | 1        | 0.41%   |
| BR25                                         | 1        | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 20       | 7.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 6.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 4.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 3.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 3.56%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 2.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.78%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.42%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 1.42%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.42%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.07%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.07%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.07%   |
| Intel Jasper Lake HD Audio                                                 | 3        | 1.07%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.07%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 2        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.71%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 20       | 19.42%  |
| Corsair                        | 11       | 10.68%  |
| SK hynix                       | 10       | 9.71%   |
| Crucial                        | 10       | 9.71%   |
| Samsung Electronics            | 9        | 8.74%   |
| Micron Technology              | 8        | 7.77%   |
| G.Skill                        | 8        | 7.77%   |
| KLEVV                          | 4        | 3.88%   |
| Transcend                      | 3        | 2.91%   |
| A-DATA Technology              | 3        | 2.91%   |
| Unknown (ABCD)                 | 2        | 1.94%   |
| Kingmax                        | 2        | 1.94%   |
| Unknown (0x0E9D)               | 1        | 0.97%   |
| Unknown (0x0B92)               | 1        | 0.97%   |
| Unknown                        | 1        | 0.97%   |
| Qimonda                        | 1        | 0.97%   |
| Patriot                        | 1        | 0.97%   |
| Nanya Technology               | 1        | 0.97%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 0.97%   |
| Lexar                          | 1        | 0.97%   |
| Kingmax Semiconductor          | 1        | 0.97%   |
| Essencore Limited              | 1        | 0.97%   |
| Elpida                         | 1        | 0.97%   |
| ASint Technology               | 1        | 0.97%   |
| Unknown                        | 1        | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                      | 3        | 2.61%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s   | 2        | 1.74%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s                 | 2        | 1.74%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 2        | 1.74%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s               | 2        | 1.74%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s              | 2        | 1.74%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3600MT/s                 | 2        | 1.74%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                         | 2        | 1.74%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                | 1        | 0.87%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1        | 0.87%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s    | 1        | 0.87%   |
| Unknown (0x0B92) RAM Module 16GB DIMM DDR4 3200MT/s                 | 1        | 0.87%   |
| Transcend RAM TS1GSH64V2B 8GB SODIMM DDR4 3200MT/s                  | 1        | 0.87%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                    | 1        | 0.87%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                   | 1        | 0.87%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                          | 1        | 0.87%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1        | 0.87%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB DIMM DDR3 1600MT/s                | 1        | 0.87%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 0.87%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1        | 0.87%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1        | 0.87%   |
| SK hynix RAM HMA84GL7MMR4N-TF 32GB DIMM DDR4 2133MT/s               | 1        | 0.87%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2400MT/s                | 1        | 0.87%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1        | 0.87%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s                 | 1        | 0.87%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s               | 1        | 0.87%   |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s              | 1        | 0.87%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                 | 1        | 0.87%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1        | 0.87%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1        | 0.87%   |
| Samsung RAM M378A2K43CB1-CRC 16GB DIMM DDR4 2400MT/s                | 1        | 0.87%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                 | 1        | 0.87%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                 | 1        | 0.87%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                    | 1        | 0.87%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s                 | 1        | 0.87%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s               | 1        | 0.87%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER RAM Module 2048MB DIMM DDR3 1600MT/s | 1        | 0.87%   |
| Micron RAM TEAMGROUP-UD4-2133 16384MB DIMM DDR4 2134MT/s            | 1        | 0.87%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                 | 1        | 0.87%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 51       | 54.84%  |
| DDR3    | 28       | 30.11%  |
| SDRAM   | 5        | 5.38%   |
| DDR5    | 4        | 4.3%    |
| LPDDR4  | 2        | 2.15%   |
| DDR2    | 2        | 2.15%   |
| Unknown | 1        | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 80       | 90.91%  |
| SODIMM | 8        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 32.32%  |
| 16384 | 30       | 30.3%   |
| 4096  | 20       | 20.2%   |
| 32768 | 8        | 8.08%   |
| 2048  | 8        | 8.08%   |
| 1024  | 1        | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 20       | 18.87%  |
| 2400  | 14       | 13.21%  |
| 3200  | 13       | 12.26%  |
| 3600  | 12       | 11.32%  |
| 1333  | 7        | 6.6%    |
| 2667  | 5        | 4.72%   |
| 2666  | 5        | 4.72%   |
| 2133  | 4        | 3.77%   |
| 3733  | 2        | 1.89%   |
| 3666  | 2        | 1.89%   |
| 3400  | 2        | 1.89%   |
| 2048  | 2        | 1.89%   |
| 1867  | 2        | 1.89%   |
| 1866  | 2        | 1.89%   |
| 1800  | 2        | 1.89%   |
| 7000  | 1        | 0.94%   |
| 5808  | 1        | 0.94%   |
| 5200  | 1        | 0.94%   |
| 4800  | 1        | 0.94%   |
| 4333  | 1        | 0.94%   |
| 4000  | 1        | 0.94%   |
| 3800  | 1        | 0.94%   |
| 3266  | 1        | 0.94%   |
| 2200  | 1        | 0.94%   |
| 2134  | 1        | 0.94%   |
| 1067  | 1        | 0.94%   |
| 667   | 1        | 0.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 33.33%  |
| Philips (or NXP)    | 1        | 33.33%  |
| Brother Industries  | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung M2020 Series         | 1        | 33.33%  |
| Philips (or NXP) USB Printer | 1        | 33.33%  |
| Brother MFC-L2715DW series   | 1        | 33.33%  |

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
| Microdia USB Camera                     | 1        | 7.14%   |
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
| 0     | 120      | 82.76%  |
| 1     | 23       | 15.86%  |
| 6     | 1        | 0.69%   |
| 2     | 1        | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 7        | 25.93%  |
| Graphics card            | 7        | 25.93%  |
| Communication controller | 4        | 14.81%  |
| Unassigned class         | 3        | 11.11%  |
| Network                  | 2        | 7.41%   |
| Multimedia controller    | 2        | 7.41%   |
| Net/ethernet             | 1        | 3.7%    |
| Dvb card                 | 1        | 3.7%    |

