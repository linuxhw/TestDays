CentOS 7 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 7.

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

Total: 236

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | EP45-DS3L                   | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| Supermicro    | X7DWE                       | [a35080b0e5](https://linux-hardware.org/?probe=a35080b0e5) | Jul 31, 2023 |
| MSI           | 870-G45                     | [af7442187f](https://linux-hardware.org/?probe=af7442187f) | Jul 20, 2023 |
| MSI           | 870-G45                     | [9fff23ac6a](https://linux-hardware.org/?probe=9fff23ac6a) | Jul 14, 2023 |
| Gigabyte      | EP45-DS3L                   | [49c764507c](https://linux-hardware.org/?probe=49c764507c) | Jul 01, 2023 |
| Intel         | DG35EC AAE29266-209         | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Supermicro    | X9DAi                       | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| Supermicro    | X10DRG-Q                    | [c03c5ea1b9](https://linux-hardware.org/?probe=c03c5ea1b9) | Jun 08, 2023 |
| Gigabyte      | EP45-DS3L                   | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| AZW           | U59                         | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| MSI           | Z77A-GD80                   | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| MSI           | Z77A-GD80                   | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| Dell          | 03TJ75 A00                  | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| Supermicro    | X10DAI                      | [b777ed256f](https://linux-hardware.org/?probe=b777ed256f) | Mar 01, 2023 |
| HP            | 0AECh D                     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| ASUSTek       | H97M-PLUS                   | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [3406527d4b](https://linux-hardware.org/?probe=3406527d4b) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [e112bdfd74](https://linux-hardware.org/?probe=e112bdfd74) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | [df9a9f0b90](https://linux-hardware.org/?probe=df9a9f0b90) | Feb 14, 2023 |
| Supermicro    | X9DAi                       | [546ea7c2e8](https://linux-hardware.org/?probe=546ea7c2e8) | Feb 09, 2023 |
| HP            | 1494                        | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| MSI           | 870-G45                     | [92b840c75e](https://linux-hardware.org/?probe=92b840c75e) | Feb 04, 2023 |
| MSI           | 870-G45                     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| Gigabyte      | EP45-DS3L                   | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| PCChips       | P49G                        | [24a7d0e02b](https://linux-hardware.org/?probe=24a7d0e02b) | Jan 24, 2023 |
| MSI           | H510M PRO-E                 | [762142dfbb](https://linux-hardware.org/?probe=762142dfbb) | Jan 06, 2023 |
| Gigabyte      | EP45-DS3L                   | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [164a07eda1](https://linux-hardware.org/?probe=164a07eda1) | Dec 08, 2022 |
| Gigabyte      | D525TUD                     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| ABIT          | I-45CV                      | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [74e3fe80fd](https://linux-hardware.org/?probe=74e3fe80fd) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [efd2a439bd](https://linux-hardware.org/?probe=efd2a439bd) | Nov 21, 2022 |
| Dell          | 09D2HH A00                  | [4cafe39785](https://linux-hardware.org/?probe=4cafe39785) | Nov 19, 2022 |
| MSI           | 870-G45                     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| Gigabyte      | EP45-DS3L                   | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| HP            | 8717                        | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| MSI           | 870-G45                     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| HP            | 8717                        | [00cbc9cd2a](https://linux-hardware.org/?probe=00cbc9cd2a) | Nov 03, 2022 |
| Unknown       | Unknown                     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| Gigabyte      | H310M S2H x.x               | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| NORCO         | BPC-7951                    | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| Unknown       | Unknown                     | [f4ce3cf768](https://linux-hardware.org/?probe=f4ce3cf768) | Oct 13, 2022 |
| Dell          | 082WXT A03                  | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| MSI           | 870-G45                     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| MSI           | 870-G45                     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| Unknown       | Unknown                     | [e61dc9628f](https://linux-hardware.org/?probe=e61dc9628f) | Sep 17, 2022 |
| Dell          | 03TJ75 A00                  | [70ef579566](https://linux-hardware.org/?probe=70ef579566) | Sep 15, 2022 |
| Dell          | 0F5C5X A00                  | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| ASRock        | X299 Professional Gaming... | [759afd2f9a](https://linux-hardware.org/?probe=759afd2f9a) | Aug 04, 2022 |
| Dell          | 0KJCC5 A00                  | [4eec45d964](https://linux-hardware.org/?probe=4eec45d964) | Jul 21, 2022 |
| HP            | 0B4Ch D                     | [15e71f4f03](https://linux-hardware.org/?probe=15e71f4f03) | Jul 21, 2022 |
| Gigabyte      | EP45-DS3L                   | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| Intel         | D410PT AAE76528-404         | [b7c62fc4a8](https://linux-hardware.org/?probe=b7c62fc4a8) | Jun 29, 2022 |
| HP            | 3397                        | [f2e8417afc](https://linux-hardware.org/?probe=f2e8417afc) | Jun 04, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [0353933c85](https://linux-hardware.org/?probe=0353933c85) | Jun 02, 2022 |
| HP            | 1998                        | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Gigabyte      | EP45-DS3L                   | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Dell          | 0K068D A00                  | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Dell          | 0Y2YM6 A01                  | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| HP            | 0AECh D                     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| MiTAC         | UltraPoint                  | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| HP            | 0A9Ch                       | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| ASUSTek       | X99-DELUXE                  | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| Gigabyte      | EP45-DS3L                   | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [a355e13859](https://linux-hardware.org/?probe=a355e13859) | Jan 11, 2022 |
| Gigabyte      | G41M-ES2L                   | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| HP            | 3397                        | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [a810f7c0fb](https://linux-hardware.org/?probe=a810f7c0fb) | Dec 28, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| ASUSTek       | Pro Q570M-C                 | [d868c52b5a](https://linux-hardware.org/?probe=d868c52b5a) | Dec 15, 2021 |
| Gigabyte      | H97N-WIFI                   | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| HP            | 8717                        | [a00d17d8c4](https://linux-hardware.org/?probe=a00d17d8c4) | Nov 25, 2021 |
| Dell          | 02K9CR A01                  | [36c6a137fb](https://linux-hardware.org/?probe=36c6a137fb) | Nov 23, 2021 |
| Gigabyte      | B360HD3                     | [71a92047fb](https://linux-hardware.org/?probe=71a92047fb) | Nov 23, 2021 |
| Dell          | 02K9CR A01                  | [7d558b813e](https://linux-hardware.org/?probe=7d558b813e) | Nov 17, 2021 |
| Dell          | 04YP6J A02                  | [6c41e1551e](https://linux-hardware.org/?probe=6c41e1551e) | Nov 09, 2021 |
| Dell          | 04YP6J A02                  | [736e182a15](https://linux-hardware.org/?probe=736e182a15) | Nov 09, 2021 |
| ASRock        | Z77 Extreme4                | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| ASRock        | Z77 Extreme4                | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| Huanan        | X79                         | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| Dell          | 0Y7WYT A00                  | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| Gigabyte      | B85M-D3PH                   | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| HP            | 8751                        | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [8ddb489f03](https://linux-hardware.org/?probe=8ddb489f03) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [d19976dabe](https://linux-hardware.org/?probe=d19976dabe) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [d56fdac07b](https://linux-hardware.org/?probe=d56fdac07b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [3eb59a276c](https://linux-hardware.org/?probe=3eb59a276c) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [3d0db6b81f](https://linux-hardware.org/?probe=3d0db6b81f) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [1fc2375e54](https://linux-hardware.org/?probe=1fc2375e54) | Aug 05, 2021 |
| Dell          | 0YNVJG A01                  | [7952948421](https://linux-hardware.org/?probe=7952948421) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [a653e9beb2](https://linux-hardware.org/?probe=a653e9beb2) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [9a5d8276bf](https://linux-hardware.org/?probe=9a5d8276bf) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [2165980dd3](https://linux-hardware.org/?probe=2165980dd3) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [4a2adade2a](https://linux-hardware.org/?probe=4a2adade2a) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [78c5e3532b](https://linux-hardware.org/?probe=78c5e3532b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [10bdaec1ef](https://linux-hardware.org/?probe=10bdaec1ef) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [70fc6a65ef](https://linux-hardware.org/?probe=70fc6a65ef) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [80244f2809](https://linux-hardware.org/?probe=80244f2809) | Aug 05, 2021 |
| HP            | 8591                        | [6794bdb00e](https://linux-hardware.org/?probe=6794bdb00e) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [f209feb9c8](https://linux-hardware.org/?probe=f209feb9c8) | Aug 05, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [40b8d28af0](https://linux-hardware.org/?probe=40b8d28af0) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | [597de4e10b](https://linux-hardware.org/?probe=597de4e10b) | Aug 01, 2021 |
| ASUSTek       | SABERTOOTH X79              | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| HP            | 2B34                        | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Dell          | 09KPNV A01                  | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| HP            | 1494                        | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Intel         | E98683-353                  | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| HP            | 1589                        | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| ASRock        | J3710M                      | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | 8594                        | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 1825                        | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| HP            | 8591                        | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| HP            | 213D A01                    | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| Gigabyte      | EP43-DS3                    | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| Dell          | 0MWYPT A02                  | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| Gigabyte      | EP45-DS3L                   | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| Gigabyte      | D525TUD                     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| ASUSTek       | PRIME B360M-D               | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| Dell          | 0HHV7N A00                  | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| Gigabyte      | D525TUD                     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| Intel         | DQ67OW AAG12528-309         | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASUSTek       | X99-DELUXE                  | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Gigabyte      | Z77-D3H                     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| Gigabyte      | D525TUD                     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| Dell          | 01NP3N A00                  | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASUSTek       | F2A55-M LE                  | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| ECS           | H61H2-MV                    | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 0AECh D                     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| Zenith        | Orion                       | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| ASUSTek       | P7P55D                      | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| Lenovo        | ThinkServer TS140           | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| Dell          | 08HPGT A02                  | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Gigabyte      | B360M DS3H                  | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| HP            | 0AECh D                     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| HP            | 1589                        | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| ASUSTek       | SABERTOOTH X99              | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Gigabyte      | P85-D3                      | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| ASUSTek       | Crosshair IV Formula        | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| Supermicro    | X10DRG-H                    | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| MSI           | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| Dell          | 0VRWRC A00                  | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| ASRock        | AM1B-ITX                    | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| ASUSTek       | CM1740                      | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Gigabyte      | EP45-DS3L                   | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| HP            | 1495                        | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Supermicro    | X10SDE-DF                   | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| ASUSTek       | Rampage V EXTREME           | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASRock        | X399 Professional Gaming    | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| Gigabyte      | EP45-DS3L                   | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| Dell          | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Gigabyte      | Z170X-UD3-CF                | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| Foxconn       | 2ABF                        | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| ASUSTek       | AT4NM10T-I                  | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| HP            | 18E4                        | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| HP            | 0A98h                       | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| Dell          | 09KPNV A01                  | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Gigabyte      | B150M-D3H-CF                | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| ECS           | H55H-M                      | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Gigabyte      | B360HD3PLM-CF               | [05d00cc5d7](https://linux-hardware.org/?probe=05d00cc5d7) | Sep 09, 2019 |
| Gigabyte      | 970A-D3P                    | [6e3666d8c9](https://linux-hardware.org/?probe=6e3666d8c9) | Sep 04, 2019 |
| AMI           | Cherry Trail CR             | [fe652a02c9](https://linux-hardware.org/?probe=fe652a02c9) | Jul 25, 2019 |
| Dell          | 09KPNV A00                  | [a72c60b73b](https://linux-hardware.org/?probe=a72c60b73b) | Jul 24, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [b2fac79afd](https://linux-hardware.org/?probe=b2fac79afd) | Jun 27, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [44eb4c1fed](https://linux-hardware.org/?probe=44eb4c1fed) | Jun 25, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [4bb11d6dc0](https://linux-hardware.org/?probe=4bb11d6dc0) | Jun 07, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [3fb7cc0574](https://linux-hardware.org/?probe=3fb7cc0574) | Jun 07, 2019 |
| AAEON         | MF-001 V1.0                 | [19f89f5d4e](https://linux-hardware.org/?probe=19f89f5d4e) | Jun 05, 2019 |
| HP            | 8054                        | [8409fbc1c6](https://linux-hardware.org/?probe=8409fbc1c6) | May 28, 2019 |
| Intel         | SHARKBAY                    | [8418bef88a](https://linux-hardware.org/?probe=8418bef88a) | May 15, 2019 |
| ASUSTek       | P5G41T-M LX                 | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Intel         | SHARKBAY                    | [58607accae](https://linux-hardware.org/?probe=58607accae) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | [5e5b4e25a0](https://linux-hardware.org/?probe=5e5b4e25a0) | Apr 08, 2019 |
| ASUSTek       | F1A75-M LE                  | [f8301ffe57](https://linux-hardware.org/?probe=f8301ffe57) | Mar 26, 2019 |
| ASRock        | Z87 Extreme6                | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 81C5 MVB                    | [46ea2e591e](https://linux-hardware.org/?probe=46ea2e591e) | Mar 18, 2019 |
| MSI           | X299 RAIDER                 | [f06f57dde9](https://linux-hardware.org/?probe=f06f57dde9) | Mar 07, 2019 |
| Lenovo        | 4030                        | [10455104fd](https://linux-hardware.org/?probe=10455104fd) | Mar 01, 2019 |
| Gigabyte      | 970A-DS3P                   | [9c8b01fc94](https://linux-hardware.org/?probe=9c8b01fc94) | Dec 22, 2018 |
| Gigabyte      | 970A-DS3P                   | [3b0d00f6c9](https://linux-hardware.org/?probe=3b0d00f6c9) | Dec 22, 2018 |
| Dell          | 0CD6TV A01                  | [7f702ee88f](https://linux-hardware.org/?probe=7f702ee88f) | Oct 29, 2018 |
| Dell          | 0CD6TV A01                  | [46e3d4f4d9](https://linux-hardware.org/?probe=46e3d4f4d9) | Oct 29, 2018 |
| ASRock        | H77 Pro4/MVP                | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 3.10.0-1160.31.1.el7.x86_64 | 12       | 6.42%   |
| 3.10.0-1160.45.1.el7.x86_64 | 9        | 4.81%   |
| 3.10.0-1160.25.1.el7.x86_64 | 9        | 4.81%   |
| 3.10.0-1062.el7.x86_64      | 7        | 3.74%   |
| 3.10.0-957.10.1.el7.x86_64  | 6        | 3.21%   |
| 3.10.0-1160.76.1.el7.x86_64 | 6        | 3.21%   |
| 3.10.0-1160.66.1.el7.x86_64 | 6        | 3.21%   |
| 3.10.0-1160.15.2.el7.x86_64 | 6        | 3.21%   |
| 3.10.0-1062.12.1.el7.x86_64 | 6        | 3.21%   |
| 3.10.0-1160.83.1.el7.x86_64 | 5        | 2.67%   |
| 3.10.0-1160.6.1.el7.x86_64  | 5        | 2.67%   |
| 3.10.0-1160.36.2.el7.x86_64 | 5        | 2.67%   |
| 3.10.0-957.27.2.el7.x86_64  | 4        | 2.14%   |
| 3.10.0-1160.el7.x86_64      | 4        | 2.14%   |
| 3.10.0-1160.59.1.el7.x86_64 | 4        | 2.14%   |
| 3.10.0-1127.el7.x86_64      | 4        | 2.14%   |
| 3.10.0-1062.9.1.el7.x86_64  | 4        | 2.14%   |
| 3.10.0-957.5.1.el7.x86_64   | 3        | 1.6%    |
| 3.10.0-957.1.3.el7.x86_64   | 3        | 1.6%    |
| 3.10.0-1160.49.1.el7.x86_64 | 3        | 1.6%    |
| 3.10.0-1160.24.1.el7.x86_64 | 3        | 1.6%    |
| 3.10.0-1160.21.1.el7.x86_64 | 3        | 1.6%    |
| 3.10.0-1127.19.1.el7.x86_64 | 3        | 1.6%    |
| 3.10.0-1127.13.1.el7.x86_64 | 3        | 1.6%    |
| 3.10.0-957.el7.x86_64       | 2        | 1.07%   |
| 3.10.0-957.12.2.el7.x86_64  | 2        | 1.07%   |
| 3.10.0-693.21.1.el7.x86_64  | 2        | 1.07%   |
| 3.10.0-1160.90.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0-1160.81.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0-1160.62.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0-1160.53.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0-1160.11.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0-1127.10.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0-1062.18.1.el7.x86_64 | 2        | 1.07%   |
| 3.10.0                      | 2        | 1.07%   |
| 6.2.2-1.el7.elrepo.x86_64   | 1        | 0.53%   |
| 6.1.1-1.el7.elrepo.x86_64   | 1        | 0.53%   |
| 5.8.0-1.el7.elrepo.x86_64   | 1        | 0.53%   |
| 5.7.7-1.el7.elrepo.x86_64   | 1        | 0.53%   |
| 5.7.10-1.el7.elrepo.x86_64  | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 3.10.0   | 144      | 87.27%  |
| 6.2.2    | 1        | 0.61%   |
| 6.1.1    | 1        | 0.61%   |
| 5.8.0    | 1        | 0.61%   |
| 5.7.7    | 1        | 0.61%   |
| 5.7.10   | 1        | 0.61%   |
| 5.6.10   | 1        | 0.61%   |
| 5.5.0    | 1        | 0.61%   |
| 5.4.96   | 1        | 0.61%   |
| 5.4.142  | 1        | 0.61%   |
| 5.4.119  | 1        | 0.61%   |
| 5.4.118  | 1        | 0.61%   |
| 5.4.113  | 1        | 0.61%   |
| 5.3.11   | 1        | 0.61%   |
| 5.1.19   | 1        | 0.61%   |
| 4.9.188  | 1        | 0.61%   |
| 4.9.182  | 1        | 0.61%   |
| 4.9.180  | 1        | 0.61%   |
| 4.9.179  | 1        | 0.61%   |
| 4.20.4   | 1        | 0.61%   |
| 4.19.187 | 1        | 0.61%   |
| 4.14.35  | 1        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 3.10    | 144      | 87.27%  |
| 5.4     | 5        | 3.03%   |
| 4.9     | 4        | 2.42%   |
| 5.7     | 2        | 1.21%   |
| 6.2     | 1        | 0.61%   |
| 6.1     | 1        | 0.61%   |
| 5.8     | 1        | 0.61%   |
| 5.6     | 1        | 0.61%   |
| 5.5     | 1        | 0.61%   |
| 5.3     | 1        | 0.61%   |
| 5.1     | 1        | 0.61%   |
| 4.20    | 1        | 0.61%   |
| 4.19    | 1        | 0.61%   |
| 4.14    | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 165      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 69       | 41.57%  |
| GNOME         | 51       | 30.72%  |
| KDE4          | 18       | 10.84%  |
| GNOME Classic | 16       | 9.64%   |
| MATE          | 7        | 4.22%   |
| Cinnamon      | 3        | 1.81%   |
| Xpra          | 1        | 0.6%    |
| X-Cinnamon    | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 139      | 84.24%  |
| Unknown | 25       | 15.15%  |
| Web     | 1        | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 78       | 46.99%  |
| Unknown | 78       | 46.99%  |
| LightDM | 8        | 4.82%   |
| TDM     | 1        | 0.6%    |
| SDDM    | 1        | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 71       | 42.51%  |
| Unknown     | 34       | 20.36%  |
| C           | 15       | 8.98%   |
| ru_RU       | 5        | 2.99%   |
| en_GB       | 5        | 2.99%   |
| en_CA       | 5        | 2.99%   |
| en_AU       | 5        | 2.99%   |
| fr_FR       | 4        | 2.4%    |
| en_IN       | 4        | 2.4%    |
| pt_BR       | 3        | 1.8%    |
| de_DE       | 3        | 1.8%    |
| de_AT       | 3        | 1.8%    |
| zh_CN       | 2        | 1.2%    |
| pl_PL       | 1        | 0.6%    |
| ko_KR       | 1        | 0.6%    |
| fr_CA       | 1        | 0.6%    |
| fi_FI       | 1        | 0.6%    |
| es_MX       | 1        | 0.6%    |
| es_EC       | 1        | 0.6%    |
| en_US.utf-8 | 1        | 0.6%    |
| en_SG       | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 92       | 55.76%  |
| EFI  | 73       | 44.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 111      | 67.27%  |
| Ext4    | 46       | 27.88%  |
| Unknown | 7        | 4.24%   |
| Ext3    | 1        | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 85       | 50.9%   |
| MBR     | 61       | 36.53%  |
| Unknown | 21       | 12.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 77.25%  |
| Yes       | 38       | 22.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 86.67%  |
| Yes       | 22       | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 37       | 22.42%  |
| ASUSTek Computer    | 27       | 16.36%  |
| Hewlett-Packard     | 26       | 15.76%  |
| Gigabyte Technology | 20       | 12.12%  |
| Supermicro          | 8        | 4.85%   |
| ASRock              | 7        | 4.24%   |
| MSI                 | 6        | 3.64%   |
| Intel               | 6        | 3.64%   |
| Unknown             | 4        | 2.42%   |
| ASRockRack          | 3        | 1.82%   |
| MiTAC               | 2        | 1.21%   |
| Lenovo              | 2        | 1.21%   |
| Fujitsu             | 2        | 1.21%   |
| ECS                 | 2        | 1.21%   |
| AMI                 | 2        | 1.21%   |
| Zenith              | 1        | 0.61%   |
| PCChips             | 1        | 0.61%   |
| NORCO               | 1        | 0.61%   |
| Huanan              | 1        | 0.61%   |
| Foxconn             | 1        | 0.61%   |
| eMachines           | 1        | 0.61%   |
| Cisco Systems       | 1        | 0.61%   |
| AZW                 | 1        | 0.61%   |
| AEWIN               | 1        | 0.61%   |
| ABIT                | 1        | 0.61%   |
| AAEON               | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 7040                  | 8        | 4.85%   |
| Dell OptiPlex 9020                  | 7        | 4.24%   |
| ASUS All Series                     | 4        | 2.42%   |
| Unknown                             | 4        | 2.42%   |
| HP Z800 Workstation                 | 3        | 1.82%   |
| HP ProDesk 400 G7 Microtower PC     | 3        | 1.82%   |
| HP Compaq Elite 8300 SFF            | 3        | 1.82%   |
| Dell Precision WorkStation T3500    | 3        | 1.82%   |
| ASRockRack E3C242D4U2-2T            | 3        | 1.82%   |
| HP Z420 Workstation                 | 2        | 1.21%   |
| Gigabyte GA-78LMT-USB3              | 2        | 1.21%   |
| Fujitsu D3401-H1                    | 2        | 1.21%   |
| Zenith Orion                        | 1        | 0.61%   |
| Supermicro X9DAi                    | 1        | 0.61%   |
| Supermicro X7DWE                    | 1        | 0.61%   |
| Supermicro X10DAi                   | 1        | 0.61%   |
| Supermicro SYS-E200-8D              | 1        | 0.61%   |
| Supermicro SYS-7048GR-TR            | 1        | 0.61%   |
| Supermicro SYS-6017B-MTF            | 1        | 0.61%   |
| Supermicro SYS-5038MD-H24TRF-OS012  | 1        | 0.61%   |
| Supermicro SYS-1028GR-TR            | 1        | 0.61%   |
| PCChips P49G                        | 1        | 0.61%   |
| NORCO BPC-7951                      | 1        | 0.61%   |
| MSI MS-7D23                         | 1        | 0.61%   |
| MSI MS-7B89                         | 1        | 0.61%   |
| MSI MS-7A94                         | 1        | 0.61%   |
| MSI MS-7978                         | 1        | 0.61%   |
| MSI MS-7757                         | 1        | 0.61%   |
| MSI MS-7599                         | 1        | 0.61%   |
| MiTAC UltraPoint                    | 1        | 0.61%   |
| MiTAC PD10BI                        | 1        | 0.61%   |
| Lenovo 70UB001NEA ThinkServer TS150 | 1        | 0.61%   |
| Lenovo 70A4000FUX ThinkServer TS140 | 1        | 0.61%   |
| Intel SHARKBAY                      | 1        | 0.61%   |
| Intel SandyBridge Platform          | 1        | 0.61%   |
| Intel H81C                          | 1        | 0.61%   |
| Intel DQ67OW AAG12528-309           | 1        | 0.61%   |
| Intel DG35EC AAE29266-209           | 1        | 0.61%   |
| Intel D410PT AAE76528-404           | 1        | 0.61%   |
| Huanan X79                          | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Dell OptiPlex                      | 22       | 13.33%  |
| Dell Precision                     | 11       | 6.67%   |
| HP EliteDesk                       | 5        | 3.03%   |
| HP Compaq                          | 5        | 3.03%   |
| ASUS PRIME                         | 5        | 3.03%   |
| ASUS All                           | 4        | 2.42%   |
| Unknown                            | 4        | 2.42%   |
| HP Z800                            | 3        | 1.82%   |
| HP ProDesk                         | 3        | 1.82%   |
| ASRockRack E3C242D4U2-2T           | 3        | 1.82%   |
| HP Z420                            | 2        | 1.21%   |
| Gigabyte GA-78LMT-USB3             | 2        | 1.21%   |
| Gigabyte B360                      | 2        | 1.21%   |
| Fujitsu D3401-H1                   | 2        | 1.21%   |
| Dell Inspiron                      | 2        | 1.21%   |
| ASUS ROG                           | 2        | 1.21%   |
| ASUS M5A78L-M                      | 2        | 1.21%   |
| Zenith Orion                       | 1        | 0.61%   |
| Supermicro X9DAi                   | 1        | 0.61%   |
| Supermicro X7DWE                   | 1        | 0.61%   |
| Supermicro X10DAi                  | 1        | 0.61%   |
| Supermicro SYS-E200-8D             | 1        | 0.61%   |
| Supermicro SYS-7048GR-TR           | 1        | 0.61%   |
| Supermicro SYS-6017B-MTF           | 1        | 0.61%   |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1        | 0.61%   |
| Supermicro SYS-1028GR-TR           | 1        | 0.61%   |
| PCChips P49G                       | 1        | 0.61%   |
| NORCO BPC-7951                     | 1        | 0.61%   |
| MSI MS-7D23                        | 1        | 0.61%   |
| MSI MS-7B89                        | 1        | 0.61%   |
| MSI MS-7A94                        | 1        | 0.61%   |
| MSI MS-7978                        | 1        | 0.61%   |
| MSI MS-7757                        | 1        | 0.61%   |
| MSI MS-7599                        | 1        | 0.61%   |
| MiTAC UltraPoint                   | 1        | 0.61%   |
| MiTAC PD10BI                       | 1        | 0.61%   |
| Lenovo 70UB001NEA                  | 1        | 0.61%   |
| Lenovo 70A4000FUX                  | 1        | 0.61%   |
| Intel SHARKBAY                     | 1        | 0.61%   |
| Intel SandyBridge                  | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 17       | 10.3%   |
| 2016    | 16       | 9.7%    |
| 2018    | 15       | 9.09%   |
| 2012    | 15       | 9.09%   |
| 2010    | 14       | 8.48%   |
| 2019    | 13       | 7.88%   |
| 2015    | 13       | 7.88%   |
| 2013    | 12       | 7.27%   |
| 2011    | 11       | 6.67%   |
| 2021    | 9        | 5.45%   |
| 2017    | 9        | 5.45%   |
| 2008    | 8        | 4.85%   |
| 2020    | 7        | 4.24%   |
| 2009    | 4        | 2.42%   |
| Unknown | 2        | 1.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 165      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 162      | 98.18%  |
| Enabled  | 3        | 1.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 164      | 99.39%  |
| Yes  | 1        | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 43       | 26.06%  |
| 32.01-64.0      | 32       | 19.39%  |
| 64.01-256.0     | 23       | 13.94%  |
| 16.01-24.0      | 23       | 13.94%  |
| 8.01-16.0       | 15       | 9.09%   |
| 3.01-4.0        | 14       | 8.48%   |
| 1.01-2.0        | 9        | 5.45%   |
| More than 256.0 | 2        | 1.21%   |
| 24.01-32.0      | 2        | 1.21%   |
| 0.51-1.0        | 2        | 1.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 38       | 22.09%  |
| 2.01-3.0    | 32       | 18.6%   |
| 0.51-1.0    | 26       | 15.12%  |
| 4.01-8.0    | 25       | 14.53%  |
| 3.01-4.0    | 17       | 9.88%   |
| 8.01-16.0   | 15       | 8.72%   |
| 0.01-0.5    | 11       | 6.4%    |
| 24.01-32.0  | 3        | 1.74%   |
| 16.01-24.0  | 3        | 1.74%   |
| 64.01-256.0 | 2        | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 67       | 39.41%  |
| 2      | 44       | 25.88%  |
| 3      | 23       | 13.53%  |
| 4      | 12       | 7.06%   |
| 6      | 5        | 2.94%   |
| 5      | 5        | 2.94%   |
| 10     | 3        | 1.76%   |
| 0      | 3        | 1.76%   |
| 7      | 2        | 1.18%   |
| 71     | 1        | 0.59%   |
| 68     | 1        | 0.59%   |
| 26     | 1        | 0.59%   |
| 15     | 1        | 0.59%   |
| 12     | 1        | 0.59%   |
| 9      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 56.29%  |
| Yes       | 73       | 43.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 163      | 98.79%  |
| No        | 2        | 1.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 80%     |
| Yes       | 33       | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 85.45%  |
| Yes       | 24       | 14.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 45       | 27.27%  |
| Russia       | 16       | 9.7%    |
| Canada       | 13       | 7.88%   |
| France       | 11       | 6.67%   |
| UK           | 9        | 5.45%   |
| India        | 8        | 4.85%   |
| Germany      | 8        | 4.85%   |
| Brazil       | 8        | 4.85%   |
| Australia    | 7        | 4.24%   |
| China        | 4        | 2.42%   |
| Switzerland  | 3        | 1.82%   |
| South Korea  | 3        | 1.82%   |
| Finland      | 3        | 1.82%   |
| Spain        | 2        | 1.21%   |
| Israel       | 2        | 1.21%   |
| Ecuador      | 2        | 1.21%   |
| Czechia      | 2        | 1.21%   |
| Bulgaria     | 2        | 1.21%   |
| Belgium      | 2        | 1.21%   |
| Ukraine      | 1        | 0.61%   |
| Taiwan       | 1        | 0.61%   |
| Sweden       | 1        | 0.61%   |
| South Africa | 1        | 0.61%   |
| Singapore    | 1        | 0.61%   |
| Romania      | 1        | 0.61%   |
| Poland       | 1        | 0.61%   |
| Pakistan     | 1        | 0.61%   |
| Norway       | 1        | 0.61%   |
| Netherlands  | 1        | 0.61%   |
| Mexico       | 1        | 0.61%   |
| Japan        | 1        | 0.61%   |
| Italy        | 1        | 0.61%   |
| Hong Kong    | 1        | 0.61%   |
| Unknown      | 1        | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Rochester            | 16       | 9.36%   |
| Moscow               | 7        | 4.09%   |
| Sydney               | 5        | 2.92%   |
| Paris                | 4        | 2.34%   |
| London               | 4        | 2.34%   |
| Guwahati             | 4        | 2.34%   |
| Frankfurt am Main    | 4        | 2.34%   |
| Alexandria           | 4        | 2.34%   |
| Victoria             | 3        | 1.75%   |
| Vancouver            | 3        | 1.75%   |
| St Petersburg        | 3        | 1.75%   |
| Montreal             | 3        | 1.75%   |
| Wahroonga            | 2        | 1.17%   |
| Tampa                | 2        | 1.17%   |
| Helsinki             | 2        | 1.17%   |
| Guayaquil            | 2        | 1.17%   |
| Brno                 | 2        | 1.17%   |
| Brandon              | 2        | 1.17%   |
| Blanzy-la-Salonnaise | 2        | 1.17%   |
| Xuhui                | 1        | 0.58%   |
| Wheeling             | 1        | 0.58%   |
| Waxhaw               | 1        | 0.58%   |
| Varna                | 1        | 0.58%   |
| UniversitГЎrio     | 1        | 0.58%   |
| Tyumentsevo          | 1        | 0.58%   |
| Tyumen               | 1        | 0.58%   |
| Tuscaloosa           | 1        | 0.58%   |
| Tucson               | 1        | 0.58%   |
| Tours                | 1        | 0.58%   |
| Tokyo                | 1        | 0.58%   |
| Tharwa               | 1        | 0.58%   |
| Tel Aviv             | 1        | 0.58%   |
| Taishan              | 1        | 0.58%   |
| Surgut               | 1        | 0.58%   |
| Sundbyberg           | 1        | 0.58%   |
| St Andrews           | 1        | 0.58%   |
| Springfield          | 1        | 0.58%   |
| Sofia                | 1        | 0.58%   |
| Singapore            | 1        | 0.58%   |
| Shenzhen             | 1        | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 60       | 243    | 22.73%  |
| WDC                       | 54       | 103    | 20.45%  |
| Samsung Electronics       | 36       | 121    | 13.64%  |
| Toshiba                   | 20       | 28     | 7.58%   |
| Kingston                  | 16       | 21     | 6.06%   |
| Hitachi                   | 14       | 44     | 5.3%    |
| SanDisk                   | 10       | 13     | 3.79%   |
| Intel                     | 9        | 29     | 3.41%   |
| Unknown                   | 5        | 14     | 1.89%   |
| HGST                      | 5        | 71     | 1.89%   |
| SK hynix                  | 3        | 3      | 1.14%   |
| SPCC                      | 2        | 2      | 0.76%   |
| OCZ                       | 2        | 6      | 0.76%   |
| Micron Technology         | 2        | 3      | 0.76%   |
| KingDian                  | 2        | 6      | 0.76%   |
| Crucial                   | 2        | 3      | 0.76%   |
| A-DATA Technology         | 2        | 3      | 0.76%   |
| UNIC2                     | 1        | 1      | 0.38%   |
| Transcend                 | 1        | 1      | 0.38%   |
| Sun                       | 1        | 3      | 0.38%   |
| Phison Electronics        | 1        | 2      | 0.38%   |
| OWC                       | 1        | 1      | 0.38%   |
| NVMe                      | 1        | 1      | 0.38%   |
| NORCO                     | 1        | 1      | 0.38%   |
| Micron/Crucial Technology | 1        | 1      | 0.38%   |
| Maxtor                    | 1        | 1      | 0.38%   |
| LITEONIT                  | 1        | 1      | 0.38%   |
| Lenovo                    | 1        | 2      | 0.38%   |
| Kingston Technologies     | 1        | 1      | 0.38%   |
| KingSpec                  | 1        | 1      | 0.38%   |
| Hewlett-Packard           | 1        | 1      | 0.38%   |
| GLOWAY                    | 1        | 1      | 0.38%   |
| Gigabyte Technology       | 1        | 1      | 0.38%   |
| Fujitsu                   | 1        | 1      | 0.38%   |
| Corsair                   | 1        | 1      | 0.38%   |
| China                     | 1        | 1      | 0.38%   |
| ADATA Technology          | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Toshiba DT01ACA050 500GB          | 7        | 2.16%   |
| Seagate ST500DM002-1SB10A 500GB   | 6        | 1.85%   |
| Seagate ST500DM002-1BD142 500GB   | 6        | 1.85%   |
| Seagate ST1000DM010-2EP102 1TB    | 5        | 1.54%   |
| Toshiba DT01ACA100 1TB            | 4        | 1.23%   |
| Samsung SSD 860 EVO 250GB         | 4        | 1.23%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 3        | 0.93%   |
| Seagate ST6000NM0095 6TB          | 3        | 0.93%   |
| Seagate ST6000NM0034 6TB          | 3        | 0.93%   |
| Seagate ST6000NM0014 6TB          | 3        | 0.93%   |
| Seagate ST4000NXCLAR4000 4TB      | 3        | 0.93%   |
| Seagate ST4000NM0023 4TB          | 3        | 0.93%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 2        | 0.62%   |
| WDC WD3200AAKS-75L9A0 320GB       | 2        | 0.62%   |
| WDC WD10EZEX-22MFCA0 1TB          | 2        | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 0.62%   |
| WDC WD1001FALS-00J7B1 1TB         | 2        | 0.62%   |
| Unknown HUH728080ALE601 8TB       | 2        | 0.62%   |
| Toshiba DT01ACA200 2TB            | 2        | 0.62%   |
| SK hynix SHGS31-500GS-2 500GB SSD | 2        | 0.62%   |
| Seagate ST4000VM000-2AF166 4TB    | 2        | 0.62%   |
| Seagate ST3000NC002-1DY166 3TB    | 2        | 0.62%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.62%   |
| Seagate ST16000NM001G-2KK103 16TB | 2        | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.62%   |
| SanDisk WDC WDS100T2B0C 1TB       | 2        | 0.62%   |
| SanDisk WDC CL SN720 SDA 512GB    | 2        | 0.62%   |
| Samsung SSD 850 EVO 250GB         | 2        | 0.62%   |
| Samsung HD322HJ 320GB             | 2        | 0.62%   |
| Samsung HD103SJ 1TB               | 2        | 0.62%   |
| Kingston SV300S37A120G 120GB SSD  | 2        | 0.62%   |
| Kingston SA400S37240G 240GB SSD   | 2        | 0.62%   |
| HGST HUS726060ALS640 6TB          | 2        | 0.62%   |
| HGST H7280A520SUN8.0T 8TB         | 2        | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1        | 0.31%   |
| WDC WDS500G2B0A 500GB SSD         | 1        | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 0.31%   |
| WDC WDS120G1G0A-00SS50 120GB SSD  | 1        | 0.31%   |
| WDC WDS100T2G0A-00JH30 1TB SSD    | 1        | 0.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 60       | 242    | 36.36%  |
| WDC                 | 51       | 93     | 30.91%  |
| Toshiba             | 20       | 28     | 12.12%  |
| Hitachi             | 14       | 44     | 8.48%   |
| Samsung Electronics | 9        | 86     | 5.45%   |
| HGST                | 5        | 24     | 3.03%   |
| Unknown             | 2        | 11     | 1.21%   |
| Sun                 | 1        | 3      | 0.61%   |
| Maxtor              | 1        | 1      | 0.61%   |
| Lenovo              | 1        | 2      | 0.61%   |
| Fujitsu             | 1        | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 24     | 24.05%  |
| Kingston            | 16       | 21     | 20.25%  |
| Intel               | 9        | 28     | 11.39%  |
| WDC                 | 7        | 10     | 8.86%   |
| SanDisk             | 4        | 4      | 5.06%   |
| SK hynix            | 3        | 3      | 3.8%    |
| SPCC                | 2        | 2      | 2.53%   |
| OCZ                 | 2        | 6      | 2.53%   |
| KingDian            | 2        | 6      | 2.53%   |
| Crucial             | 2        | 3      | 2.53%   |
| A-DATA Technology   | 2        | 3      | 2.53%   |
| UNIC2               | 1        | 1      | 1.27%   |
| Transcend           | 1        | 1      | 1.27%   |
| Seagate             | 1        | 1      | 1.27%   |
| OWC                 | 1        | 1      | 1.27%   |
| NORCO               | 1        | 1      | 1.27%   |
| Micron Technology   | 1        | 2      | 1.27%   |
| LITEONIT            | 1        | 1      | 1.27%   |
| Hewlett-Packard     | 1        | 1      | 1.27%   |
| GLOWAY              | 1        | 1      | 1.27%   |
| Corsair             | 1        | 1      | 1.27%   |
| China               | 1        | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 125      | 535    | 56.31%  |
| SSD     | 70       | 122    | 31.53%  |
| NVMe    | 20       | 28     | 9.01%   |
| MMC     | 4        | 4      | 1.8%    |
| Unknown | 3        | 48     | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 145      | 486    | 79.67%  |
| NVMe | 20       | 28     | 10.99%  |
| SAS  | 13       | 219    | 7.14%   |
| MMC  | 4        | 4      | 2.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 100      | 253    | 44.64%  |
| 0.51-1.0   | 61       | 82     | 27.23%  |
| 1.01-2.0   | 20       | 60     | 8.93%   |
| 3.01-4.0   | 14       | 111    | 6.25%   |
| 4.01-10.0  | 12       | 86     | 5.36%   |
| 2.01-3.0   | 11       | 26     | 4.91%   |
| 10.01-20.0 | 6        | 39     | 2.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 46       | 27.06%  |
| More than 3000 | 27       | 15.88%  |
| 501-1000       | 25       | 14.71%  |
| 101-250        | 24       | 14.12%  |
| 1001-2000      | 12       | 7.06%   |
| Unknown        | 11       | 6.47%   |
| 21-50          | 8        | 4.71%   |
| 1-20           | 6        | 3.53%   |
| 51-100         | 6        | 3.53%   |
| 2001-3000      | 5        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 36.53%  |
| 101-250        | 22       | 13.17%  |
| More than 3000 | 15       | 8.98%   |
| 251-500        | 14       | 8.38%   |
| 501-1000       | 13       | 7.78%   |
| 21-50          | 12       | 7.19%   |
| Unknown        | 11       | 6.59%   |
| 51-100         | 10       | 5.99%   |
| 1001-2000      | 5        | 2.99%   |
| 2001-3000      | 3        | 1.8%    |
| 0              | 1        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB             | 3        | 3      | 6.82%   |
| WDC WD1001FALS-00J7B1 1TB                   | 2        | 2      | 4.55%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-08U6AA0 500GB                | 1        | 1      | 2.27%   |
| WDC WD3200AAKS-75L9A0 320GB                 | 1        | 1      | 2.27%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 1        | 3      | 2.27%   |
| WDC WD2500HHTZ-04N21V0 250GB                | 1        | 1      | 2.27%   |
| WDC WD20EARX-00PASB0 2TB                    | 1        | 1      | 2.27%   |
| WDC WD20EARS-00MVWB0 2TB                    | 1        | 2      | 2.27%   |
| WDC WD10EZEX-60WN4A1 1TB                    | 1        | 1      | 2.27%   |
| WDC WD10EADS-00L5B1 1TB                     | 1        | 1      | 2.27%   |
| Seagate ST380211AS 80GB                     | 1        | 1      | 2.27%   |
| Seagate ST380013AS 80GB                     | 1        | 1      | 2.27%   |
| Seagate ST3250620NS 250GB                   | 1        | 2      | 2.27%   |
| Seagate ST31000524NS 1TB                    | 1        | 1      | 2.27%   |
| Seagate ST31000520AS 1TB                    | 1        | 1      | 2.27%   |
| Seagate ST31000340AS 1TB                    | 1        | 1      | 2.27%   |
| Seagate ST3000DM001-1ER166 3TB              | 1        | 1      | 2.27%   |
| Seagate ST3000DM001-1CH166 3TB              | 1        | 1      | 2.27%   |
| Seagate ST2000DM001-9YN164 2TB              | 1        | 1      | 2.27%   |
| Seagate ST1000NX0313 1TB                    | 1        | 1      | 2.27%   |
| SanDisk SDSSDX240GG25 240GB                 | 1        | 1      | 2.27%   |
| Samsung Electronics SSD SM871 2.5 7mm 512GB | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 870 EVO 500GB       | 1        | 3      | 2.27%   |
| Samsung Electronics HD154UI 1TB             | 1        | 1      | 2.27%   |
| Samsung Electronics HD103UI 1TB             | 1        | 1      | 2.27%   |
| Maxtor 6Y080L0 82GB                         | 1        | 1      | 2.27%   |
| LITEONIT LCT-256M3S 256GB SSD               | 1        | 1      | 2.27%   |
| Kingston SV100S264G 64GB SSD                | 1        | 1      | 2.27%   |
| Kingston SNS4151S316G 16GB SSD              | 1        | 1      | 2.27%   |
| Kingston SHFS37A120G 120GB SSD              | 1        | 1      | 2.27%   |
| Intel SSDSCKKW256G8 256GB                   | 1        | 1      | 2.27%   |
| Intel SSDSC2KG480G8 480GB                   | 1        | 2      | 2.27%   |
| Intel SSDSA2M120G2GC 120GB                  | 1        | 1      | 2.27%   |
| Intel SSDSA2M080G2LE 80GB                   | 1        | 15     | 2.27%   |
| Hitachi HTS542512K9A300 120GB               | 1        | 1      | 2.27%   |
| Hitachi HDS728080PLA380 82GB                | 1        | 1      | 2.27%   |
| Hitachi HDS725050KLA360 500GB               | 1        | 1      | 2.27%   |
| Hitachi HDS721050CLA660 500GB               | 1        | 1      | 2.27%   |
| HGST HDN726060ALE610 6TB                    | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 14     | 28.57%  |
| WDC                 | 10       | 14     | 23.81%  |
| Samsung Electronics | 4        | 6      | 9.52%   |
| Intel               | 4        | 19     | 9.52%   |
| Hitachi             | 4        | 4      | 9.52%   |
| Kingston            | 3        | 3      | 7.14%   |
| SanDisk             | 1        | 1      | 2.38%   |
| Maxtor              | 1        | 1      | 2.38%   |
| LITEONIT            | 1        | 1      | 2.38%   |
| HGST                | 1        | 1      | 2.38%   |
| Crucial             | 1        | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 14     | 40%     |
| WDC                 | 10       | 14     | 33.33%  |
| Hitachi             | 4        | 4      | 13.33%  |
| Samsung Electronics | 2        | 2      | 6.67%   |
| Maxtor              | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 36     | 66.67%  |
| SSD  | 12       | 29     | 33.33%  |

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
| Works    | 126      | 410    | 63.96%  |
| Detected | 37       | 262    | 18.78%  |
| Malfunc  | 34       | 65     | 17.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 136      | 62.1%   |
| AMD                         | 20       | 9.13%   |
| Samsung Electronics         | 11       | 5.02%   |
| ASMedia Technology          | 11       | 5.02%   |
| LSI Logic / Symbios Logic   | 7        | 3.2%    |
| SanDisk                     | 5        | 2.28%   |
| JMicron Technology          | 5        | 2.28%   |
| Broadcom / LSI              | 5        | 2.28%   |
| Adaptec                     | 5        | 2.28%   |
| Marvell Technology Group    | 4        | 1.83%   |
| VIA Technologies            | 1        | 0.46%   |
| SK hynix                    | 1        | 0.46%   |
| Silicon Image               | 1        | 0.46%   |
| Phison Electronics          | 1        | 0.46%   |
| Nvidia                      | 1        | 0.46%   |
| Micron/Crucial Technology   | 1        | 0.46%   |
| Micron Technology           | 1        | 0.46%   |
| Kingston Technology Company | 1        | 0.46%   |
| ADATA Technology            | 1        | 0.46%   |
| 3ware                       | 1        | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 7.3%    |
| Intel SATA Controller [RAID mode]                                                       | 16       | 5.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 4.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 3.65%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 3.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 2.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 2.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 2.55%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 2.19%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.82%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.82%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.46%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 3        | 1.09%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 3        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.09%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 1.09%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.09%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 1.09%   |
| Adaptec AAC-RAID                                                                        | 3        | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.73%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.73%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 2        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.73%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 2        | 0.73%   |
| Broadcom / LSI SAS2116 PCI-Express Fusion-MPT SAS-2 [Meteor]                            | 2        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 116      | 52.97%  |
| IDE  | 37       | 16.89%  |
| RAID | 32       | 14.61%  |
| NVMe | 20       | 9.13%   |
| SAS  | 10       | 4.57%   |
| SCSI | 4        | 1.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 145      | 87.88%  |
| AMD    | 20       | 12.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz     | 11       | 6.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz     | 9        | 5.45%   |
| Intel Xeon E-2136 CPU @ 3.30GHz      | 3        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 3        | 1.82%   |
| Intel Core i5-10500 CPU @ 3.10GHz    | 3        | 1.82%   |
| AMD FX-6300 Six-Core Processor       | 3        | 1.82%   |
| Intel Xeon CPU X5680 @ 3.33GHz       | 2        | 1.21%   |
| Intel Xeon CPU W3530 @ 2.80GHz       | 2        | 1.21%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz   | 2        | 1.21%   |
| Intel Core i9-10900K CPU @ 3.70GHz   | 2        | 1.21%   |
| Intel Core i7-7700 CPU @ 3.60GHz     | 2        | 1.21%   |
| Intel Core i5-9500 CPU @ 3.00GHz     | 2        | 1.21%   |
| Intel Core i5-4570 CPU @ 3.20GHz     | 2        | 1.21%   |
| Intel Core i3-4160 CPU @ 3.60GHz     | 2        | 1.21%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz | 2        | 1.21%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz | 2        | 1.21%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz    | 2        | 1.21%   |
| Intel Atom CPU D525 @ 1.80GHz        | 2        | 1.21%   |
| AMD Ryzen 5 1600 Six-Core Processor  | 2        | 1.21%   |
| AMD Phenom II X6 1090T Processor     | 2        | 1.21%   |
| Intel Xeon W-2155 CPU @ 3.30GHz      | 1        | 0.61%   |
| Intel Xeon W-2125 CPU @ 4.00GHz      | 1        | 0.61%   |
| Intel Xeon W-1290 CPU @ 3.20GHz      | 1        | 0.61%   |
| Intel Xeon CPU X5660 @ 2.80GHz       | 1        | 0.61%   |
| Intel Xeon CPU X5650 @ 2.67GHz       | 1        | 0.61%   |
| Intel Xeon CPU X5450 @ 3.00GHz       | 1        | 0.61%   |
| Intel Xeon CPU W3680 @ 3.33GHz       | 1        | 0.61%   |
| Intel Xeon CPU E5620 @ 2.40GHz       | 1        | 0.61%   |
| Intel Xeon CPU E5440 @ 2.83GHz       | 1        | 0.61%   |
| Intel Xeon CPU E5410 @ 2.33GHz       | 1        | 0.61%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz  | 1        | 0.61%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz  | 1        | 0.61%   |
| Intel Xeon CPU E5-2687W v3 @ 3.10GHz | 1        | 0.61%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz   | 1        | 0.61%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz  | 1        | 0.61%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz  | 1        | 0.61%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz  | 1        | 0.61%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz   | 1        | 0.61%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz  | 1        | 0.61%   |
| Intel Xeon CPU E5-2407 v2 @ 2.40GHz  | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 38       | 23.03%  |
| Intel Xeon              | 36       | 21.82%  |
| Intel Core i5           | 27       | 16.36%  |
| Intel Core i3           | 11       | 6.67%   |
| Intel Atom              | 7        | 4.24%   |
| Intel Core 2 Duo        | 6        | 3.64%   |
| AMD FX                  | 6        | 3.64%   |
| Intel Core i9           | 5        | 3.03%   |
| Intel Pentium           | 4        | 2.42%   |
| AMD Ryzen 5             | 4        | 2.42%   |
| Intel Pentium Dual-Core | 3        | 1.82%   |
| Intel Celeron           | 3        | 1.82%   |
| Other                   | 2        | 1.21%   |
| Intel Core 2 Quad       | 2        | 1.21%   |
| AMD Phenom II X6        | 2        | 1.21%   |
| Intel Pentium Dual      | 1        | 0.61%   |
| AMD Ryzen Threadripper  | 1        | 0.61%   |
| AMD Ryzen 7             | 1        | 0.61%   |
| AMD Ryzen 3             | 1        | 0.61%   |
| AMD GX                  | 1        | 0.61%   |
| AMD E2                  | 1        | 0.61%   |
| AMD Athlon              | 1        | 0.61%   |
| AMD A8                  | 1        | 0.61%   |
| AMD A10                 | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 74       | 44.85%  |
| 2      | 29       | 17.58%  |
| 6      | 26       | 15.76%  |
| 8      | 10       | 6.06%   |
| 12     | 6        | 3.64%   |
| 10     | 4        | 2.42%   |
| 3      | 4        | 2.42%   |
| 16     | 3        | 1.82%   |
| 1      | 3        | 1.82%   |
| 20     | 2        | 1.21%   |
| 28     | 1        | 0.61%   |
| 24     | 1        | 0.61%   |
| 18     | 1        | 0.61%   |
| 14     | 1        | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 151      | 91.52%  |
| 2      | 13       | 7.88%   |
| 0      | 1        | 0.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 98       | 59.39%  |
| 1      | 67       | 40.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 157      | 95.15%  |
| Unknown        | 8        | 4.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 23       | 13.77%  |
| Unknown    | 16       | 9.58%   |
| 0x506e3    | 13       | 7.78%   |
| 0x206a7    | 9        | 5.39%   |
| 0x906ea    | 8        | 4.79%   |
| 0x1067a    | 8        | 4.79%   |
| 0x306a9    | 7        | 4.19%   |
| 0x306f2    | 6        | 3.59%   |
| 0x206d7    | 6        | 3.59%   |
| 0xa0655    | 5        | 2.99%   |
| 0x50654    | 5        | 2.99%   |
| 0x206c2    | 5        | 2.99%   |
| 0x06000852 | 5        | 2.99%   |
| 0xa0653    | 4        | 2.4%    |
| 0x906e9    | 4        | 2.4%    |
| 0x106ca    | 4        | 2.4%    |
| 0x406c4    | 3        | 1.8%    |
| 0x906ed    | 2        | 1.2%    |
| 0x406f1    | 2        | 1.2%    |
| 0x106e5    | 2        | 1.2%    |
| 0x106a5    | 2        | 1.2%    |
| 0x10676    | 2        | 1.2%    |
| 0x08701013 | 2        | 1.2%    |
| 0x08001137 | 2        | 1.2%    |
| 0x03000027 | 2        | 1.2%    |
| 0x010000dc | 2        | 1.2%    |
| 0xa0671    | 1        | 0.6%    |
| 0x906ec    | 1        | 0.6%    |
| 0x906eb    | 1        | 0.6%    |
| 0x906c0    | 1        | 0.6%    |
| 0x90672    | 1        | 0.6%    |
| 0x6fd      | 1        | 0.6%    |
| 0x6fb      | 1        | 0.6%    |
| 0x506ca    | 1        | 0.6%    |
| 0x50663    | 1        | 0.6%    |
| 0x406e3    | 1        | 0.6%    |
| 0x406c3    | 1        | 0.6%    |
| 0x40651    | 1        | 0.6%    |
| 0x30678    | 1        | 0.6%    |
| 0x0800820d | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 30       | 18.18%  |
| Skylake     | 21       | 12.73%  |
| SandyBridge | 16       | 9.7%    |
| KabyLake    | 16       | 9.7%    |
| Penryn      | 13       | 7.88%   |
| IvyBridge   | 9        | 5.45%   |
| CometLake   | 9        | 5.45%   |
| Piledriver  | 7        | 4.24%   |
| Westmere    | 6        | 3.64%   |
| Broadwell   | 6        | 3.64%   |
| Silvermont  | 5        | 3.03%   |
| Nehalem     | 4        | 2.42%   |
| Bonnell     | 4        | 2.42%   |
| Zen 2       | 3        | 1.82%   |
| Unknown     | 3        | 1.82%   |
| Zen+        | 2        | 1.21%   |
| Zen         | 2        | 1.21%   |
| K10 Llano   | 2        | 1.21%   |
| K10         | 2        | 1.21%   |
| Jaguar      | 2        | 1.21%   |
| Core        | 2        | 1.21%   |
| Goldmont    | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 69       | 40.12%  |
| Nvidia                                       | 52       | 30.23%  |
| AMD                                          | 39       | 22.67%  |
| ASPEED Technology                            | 7        | 4.07%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 1.16%   |
| Matrox Electronics Systems                   | 2        | 1.16%   |
| Silicon Motion                               | 1        | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 5.62%   |
| Intel HD Graphics 530                                                                    | 8        | 4.49%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8        | 4.49%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 3.93%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7        | 3.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 3.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 3.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3.37%   |
| Nvidia GP107GL [Quadro P400]                                                             | 4        | 2.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 2.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 2.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.25%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 3        | 1.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 1.69%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 1.12%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 2        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2        | 1.12%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2        | 1.12%   |
| Intel HD Graphics 630                                                                    | 2        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.12%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.12%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.56%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                           | 1        | 0.56%   |
| Silicon Motion SM712 LynxEM+                                                             | 1        | 0.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.56%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1        | 0.56%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1        | 0.56%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.56%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.56%   |
| Nvidia GP106GL [Quadro P2200]                                                            | 1        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 62       | 37.58%  |
| 1 x Nvidia              | 45       | 27.27%  |
| 1 x AMD                 | 37       | 22.42%  |
| 1 x ASPEED              | 5        | 3.03%   |
| 2 x Nvidia              | 3        | 1.82%   |
| Other                   | 2        | 1.21%   |
| 1 x XGI                 | 2        | 1.21%   |
| 1 x Matrox              | 2        | 1.21%   |
| Intel + Nvidia          | 2        | 1.21%   |
| 3 x Nvidia + 1 x ASPEED | 1        | 0.61%   |
| 2 x AMD                 | 1        | 0.61%   |
| 1 x Silicon Motion      | 1        | 0.61%   |
| Nvidia + ASPEED         | 1        | 0.61%   |
| Intel + AMD             | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 107      | 64.07%  |
| Unknown     | 32       | 19.16%  |
| Proprietary | 28       | 16.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 79       | 47.59%  |
| 1.01-2.0   | 27       | 16.27%  |
| 0.51-1.0   | 24       | 14.46%  |
| 7.01-8.0   | 11       | 6.63%   |
| 0.01-0.5   | 10       | 6.02%   |
| 3.01-4.0   | 9        | 5.42%   |
| 4.01-5.0   | 3        | 1.81%   |
| 5.01-6.0   | 1        | 0.6%    |
| 2.01-3.0   | 1        | 0.6%    |
| 16.01-24.0 | 1        | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 36       | 28.13%  |
| Samsung Electronics     | 18       | 14.06%  |
| Hewlett-Packard         | 13       | 10.16%  |
| AOC                     | 10       | 7.81%   |
| Goldstar                | 9        | 7.03%   |
| Ancor Communications    | 7        | 5.47%   |
| Acer                    | 7        | 5.47%   |
| Philips                 | 4        | 3.13%   |
| BenQ                    | 4        | 3.13%   |
| ___                     | 2        | 1.56%   |
| ViewSonic               | 2        | 1.56%   |
| Unknown                 | 2        | 1.56%   |
| NEC Computers           | 2        | 1.56%   |
| Eizo                    | 2        | 1.56%   |
| Toshiba                 | 1        | 0.78%   |
| Sceptre Tech            | 1        | 0.78%   |
| Packard Bell            | 1        | 0.78%   |
| NME                     | 1        | 0.78%   |
| LG Electronics          | 1        | 0.78%   |
| Lenovo                  | 1        | 0.78%   |
| GVV                     | 1        | 0.78%   |
| Founder                 | 1        | 0.78%   |
| Chi Mei Optoelectronics | 1        | 0.78%   |
| AMW                     | 1        | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 6        | 4.23%   |
| Dell P2414H DELA09A 1920x1080 530x300mm 24.0-inch                    | 6        | 4.23%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 4        | 2.82%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 3        | 2.11%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 2        | 1.41%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1080 518x324mm 24.1-inch        | 2        | 1.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 1.41%   |
| Dell P2417H DELA0DA 1920x1080 527x296mm 23.8-inch                    | 2        | 1.41%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                    | 2        | 1.41%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1        | 0.7%    |
| ___ LCDTV16 ___0101 1920x1080                                        | 1        | 0.7%    |
| ViewSonic VA702 SERIES VSC231C 1280x1024 338x270mm 17.0-inch         | 1        | 0.7%    |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch            | 1        | 0.7%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1        | 0.7%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                  | 1        | 0.7%    |
| Toshiba LCD Monitor 1 5" LCD000D 1024x768 304x228mm 15.0-inch        | 1        | 0.7%    |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch               | 1        | 0.7%    |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch    | 1        | 0.7%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 0.7%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM037C 1680x1050 470x300mm 22.0-inch | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 0.7%    |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch   | 1        | 0.7%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 1        | 0.7%    |
| Samsung Electronics S27E391 SAM0C16 1920x1080 598x336mm 27.0-inch    | 1        | 0.7%    |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch    | 1        | 0.7%    |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch    | 1        | 0.7%    |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch    | 1        | 0.7%    |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch     | 1        | 0.7%    |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1080                 | 1        | 0.7%    |
| Samsung Electronics LCD Monitor C27F591 1440x900                     | 1        | 0.7%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 1        | 0.7%    |
| Philips PHL 284E5 PHLC0DE 1920x1080 621x341mm 27.9-inch              | 1        | 0.7%    |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                  | 1        | 0.7%    |
| Philips 196V4 PHLC0AF 1366x768 410x230mm 18.5-inch                   | 1        | 0.7%    |
| Philips 190S PHL083F 1280x1024 376x301mm 19.0-inch                   | 1        | 0.7%    |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch        | 1        | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 45.04%  |
| 3840x2160 (4K)     | 8        | 6.11%   |
| 2560x1440 (QHD)    | 8        | 6.11%   |
| 1680x1050 (WSXGA+) | 8        | 6.11%   |
| 1366x768 (WXGA)    | 8        | 6.11%   |
| 1280x1024 (SXGA)   | 8        | 6.11%   |
| 1920x1200 (WUXGA)  | 7        | 5.34%   |
| 1440x900 (WXGA+)   | 6        | 4.58%   |
| Unknown            | 5        | 3.82%   |
| 1600x900 (HD+)     | 3        | 2.29%   |
| 3840x1200          | 2        | 1.53%   |
| 3840x1080          | 2        | 1.53%   |
| 1600x1200          | 2        | 1.53%   |
| 1024x768 (XGA)     | 2        | 1.53%   |
| 5760x1080          | 1        | 0.76%   |
| 1680x1080          | 1        | 0.76%   |
| 1360x768           | 1        | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 29       | 22.31%  |
| 23      | 18       | 13.85%  |
| 21      | 18       | 13.85%  |
| Unknown | 13       | 10%     |
| 27      | 12       | 9.23%   |
| 22      | 7        | 5.38%   |
| 19      | 7        | 5.38%   |
| 18      | 6        | 4.62%   |
| 20      | 4        | 3.08%   |
| 15      | 4        | 3.08%   |
| 17      | 3        | 2.31%   |
| 72      | 2        | 1.54%   |
| 31      | 2        | 1.54%   |
| 42      | 1        | 0.77%   |
| 32      | 1        | 0.77%   |
| 26      | 1        | 0.77%   |
| 25      | 1        | 0.77%   |
| 16      | 1        | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 56       | 44.8%   |
| 401-500     | 36       | 28.8%   |
| Unknown     | 13       | 10.4%   |
| 301-350     | 7        | 5.6%    |
| 351-400     | 5        | 4%      |
| 601-700     | 4        | 3.2%    |
| 1501-2000   | 2        | 1.6%    |
| 701-800     | 1        | 0.8%    |
| 901-1000    | 1        | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 78       | 63.93%  |
| 16/10   | 21       | 17.21%  |
| Unknown | 11       | 9.02%   |
| 5/4     | 7        | 5.74%   |
| 4/3     | 5        | 4.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 44.96%  |
| 151-200        | 16       | 12.4%   |
| Unknown        | 13       | 10.08%  |
| 301-350        | 12       | 9.3%    |
| 251-300        | 11       | 8.53%   |
| 141-150        | 8        | 6.2%    |
| 101-110        | 4        | 3.1%    |
| 351-500        | 3        | 2.33%   |
| More than 1000 | 2        | 1.55%   |
| 111-120        | 1        | 0.78%   |
| 501-1000       | 1        | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 79       | 64.23%  |
| 101-120 | 23       | 18.7%   |
| Unknown | 13       | 10.57%  |
| 121-160 | 5        | 4.07%   |
| 1-50    | 2        | 1.63%   |
| 161-240 | 1        | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 57.65%  |
| 0     | 51       | 30%     |
| 2     | 19       | 11.18%  |
| 3     | 2        | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 94       | 42.34%  |
| Realtek Semiconductor       | 64       | 28.83%  |
| Broadcom                    | 16       | 7.21%   |
| Qualcomm Atheros            | 7        | 3.15%   |
| TP-Link                     | 5        | 2.25%   |
| Ralink Technology           | 5        | 2.25%   |
| D-Link System               | 3        | 1.35%   |
| Mellanox Technologies       | 2        | 0.9%    |
| Marvell Technology Group    | 2        | 0.9%    |
| D-Link                      | 2        | 0.9%    |
| Aquantia                    | 2        | 0.9%    |
| 3Com                        | 2        | 0.9%    |
| Xilinx                      | 1        | 0.45%   |
| Xiaomi                      | 1        | 0.45%   |
| VIA Technologies            | 1        | 0.45%   |
| Sierra Wireless             | 1        | 0.45%   |
| Samsung Electronics         | 1        | 0.45%   |
| NetGear                     | 1        | 0.45%   |
| MYRICOM                     | 1        | 0.45%   |
| MediaTek                    | 1        | 0.45%   |
| LSI                         | 1        | 0.45%   |
| Linux 2.6.31.6 with s3c-udc | 1        | 0.45%   |
| Linksys                     | 1        | 0.45%   |
| ICS Advent                  | 1        | 0.45%   |
| Huawei Technologies         | 1        | 0.45%   |
| Exar                        | 1        | 0.45%   |
| Dresden Elektronik          | 1        | 0.45%   |
| Cisco Systems               | 1        | 0.45%   |
| Broadcom Limited            | 1        | 0.45%   |
| Apple                       | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 52       | 20.8%   |
| Intel Ethernet Connection (2) I219-LM                               | 15       | 6%      |
| Intel Ethernet Connection I217-LM                                   | 14       | 5.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 4.4%    |
| Intel I211 Gigabit Network Connection                               | 6        | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                | 6        | 2.4%    |
| Intel 82574L Gigabit Network Connection                             | 6        | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 5        | 2%      |
| Intel I350 Gigabit Network Connection                               | 5        | 2%      |
| Intel Ethernet Connection (11) I219-LM                              | 5        | 2%      |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 5        | 2%      |
| Intel I210 Gigabit Network Connection                               | 4        | 1.6%    |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 1.6%    |
| Intel Ethernet Connection (2) I218-V                                | 4        | 1.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 4        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3        | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 3        | 1.2%    |
| Intel Ethernet Controller X550                                      | 3        | 1.2%    |
| Intel 82580 Gigabit Network Connection                              | 3        | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.8%    |
| Ralink MT7601U Wireless Adapter                                     | 2        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 0.8%    |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.8%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 2        | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2        | 0.8%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.8%    |
| Xilinx Network controller                                           | 1        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.4%    |
| VIA VT6105/VT6106S [Rhine-III]                                      | 1        | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.4%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.4%    |
| TP-Link 802.11ac WLAN Adapter                                       | 1        | 0.4%    |
| TP-Link 802.11ac NIC                                                | 1        | 0.4%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                     | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 1        | 0.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.4%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                              | 1        | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 21.62%  |
| Intel                 | 7        | 18.92%  |
| TP-Link               | 5        | 13.51%  |
| Ralink Technology     | 5        | 13.51%  |
| Qualcomm Atheros      | 3        | 8.11%   |
| D-Link                | 2        | 5.41%   |
| Broadcom              | 2        | 5.41%   |
| Sierra Wireless       | 1        | 2.7%    |
| NetGear               | 1        | 2.7%    |
| MediaTek              | 1        | 2.7%    |
| Linksys               | 1        | 2.7%    |
| D-Link System         | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 7.89%   |
| Ralink MT7601U Wireless Adapter                                      | 2        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 5.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2        | 5.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 2.63%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]  | 1        | 2.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 2.63%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 2.63%   |
| TP-Link 802.11ac NIC                                                 | 1        | 2.63%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                      | 1        | 2.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 2.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 2.63%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 2.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 2.63%   |
| Ralink RT5572 Wireless Adapter                                       | 1        | 2.63%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 2.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 2.63%   |
| NetGear A6150                                                        | 1        | 2.63%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                   | 1        | 2.63%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]  | 1        | 2.63%   |
| Intel Wireless 7260                                                  | 1        | 2.63%   |
| Intel Wireless 3165                                                  | 1        | 2.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 2.63%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 2.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 2.63%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]    | 1        | 2.63%   |
| D-Link DWA-160 Xtreme N Dual Band USB Adapter(rev.C1)                | 1        | 2.63%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 2.63%   |
| D-Link 802.11 n WLAN                                                 | 1        | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 91       | 47.89%  |
| Realtek Semiconductor    | 63       | 33.16%  |
| Broadcom                 | 14       | 7.37%   |
| Qualcomm Atheros         | 4        | 2.11%   |
| Marvell Technology Group | 2        | 1.05%   |
| D-Link System            | 2        | 1.05%   |
| Aquantia                 | 2        | 1.05%   |
| 3Com                     | 2        | 1.05%   |
| Xiaomi                   | 1        | 0.53%   |
| VIA Technologies         | 1        | 0.53%   |
| Samsung Electronics      | 1        | 0.53%   |
| MYRICOM                  | 1        | 0.53%   |
| Mellanox Technologies    | 1        | 0.53%   |
| ICS Advent               | 1        | 0.53%   |
| Huawei Technologies      | 1        | 0.53%   |
| Cisco Systems            | 1        | 0.53%   |
| Broadcom Limited         | 1        | 0.53%   |
| Apple                    | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 52       | 25.24%  |
| Intel Ethernet Connection (2) I219-LM                                          | 15       | 7.28%   |
| Intel Ethernet Connection I217-LM                                              | 14       | 6.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11       | 5.34%   |
| Intel I211 Gigabit Network Connection                                          | 6        | 2.91%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 2.91%   |
| Intel 82574L Gigabit Network Connection                                        | 6        | 2.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5        | 2.43%   |
| Intel I350 Gigabit Network Connection                                          | 5        | 2.43%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5        | 2.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5        | 2.43%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 1.94%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4        | 1.94%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 1.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4        | 1.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 1.46%   |
| Intel Ethernet Controller X550                                                 | 3        | 1.46%   |
| Intel 82580 Gigabit Network Connection                                         | 3        | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.97%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 0.97%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 2        | 0.97%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 2        | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.49%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.49%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                             | 1        | 0.49%   |
| Mellanox MT27520 Family [ConnectX-3 Pro]                                       | 1        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.49%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1        | 0.49%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                               | 1        | 0.49%   |
| Intel Ethernet Controller I225-V                                               | 1        | 0.49%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.49%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1        | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 163      | 80.69%  |
| WiFi     | 33       | 16.34%  |
| Modem    | 4        | 1.98%   |
| Unknown  | 2        | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 151      | 93.79%  |
| WiFi     | 10       | 6.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 102      | 61.82%  |
| 2     | 39       | 23.64%  |
| 3     | 12       | 7.27%   |
| 4     | 6        | 3.64%   |
| 5     | 2        | 1.21%   |
| 0     | 2        | 1.21%   |
| 8     | 1        | 0.61%   |
| 6     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 147      | 88.55%  |
| Yes  | 19       | 11.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 28%     |
| Intel                           | 5        | 20%     |
| Broadcom                        | 4        | 16%     |
| Realtek Semiconductor           | 3        | 12%     |
| Qualcomm Atheros Communications | 3        | 12%     |
| ASUSTek Computer                | 2        | 8%      |
| Dynex                           | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 7        | 28%     |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 12%     |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 8%      |
| Intel Bluetooth wireless interface                       | 2        | 8%      |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 8%      |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 8%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1        | 4%      |
| Intel AX210 Bluetooth                                    | 1        | 4%      |
| Intel AX201 Bluetooth                                    | 1        | 4%      |
| Intel AX200 Bluetooth                                    | 1        | 4%      |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 4%      |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 4%      |
| Broadcom ANYCOM Blue USB-200/250                         | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 114      | 50.89%  |
| AMD                  | 48       | 21.43%  |
| Nvidia               | 47       | 20.98%  |
| Logitech             | 3        | 1.34%   |
| C-Media Electronics  | 3        | 1.34%   |
| Texas Instruments    | 2        | 0.89%   |
| Creative Labs        | 2        | 0.89%   |
| KTMicro              | 1        | 0.45%   |
| Harman International | 1        | 0.45%   |
| GN Netcom            | 1        | 0.45%   |
| Ensoniq              | 1        | 0.45%   |
| ASUSTek Computer     | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 7.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17       | 6.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 16       | 6.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 4.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 3.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 3.16%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 2.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6        | 2.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 2.37%   |
| Intel Comet Lake PCH cAVS                                                         | 6        | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 2.37%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6        | 2.37%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 6        | 2.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 2.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.98%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 1.98%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 1.98%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.98%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.58%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4        | 1.58%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 1.19%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 3        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.19%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.19%   |
| Nvidia TU102 High Definition Audio Controller                                     | 2        | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.79%   |
| Logitech Headset H390                                                             | 2        | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.79%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 2        | 0.79%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.79%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]             | 2        | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 32       | 19.63%  |
| Kingston            | 32       | 19.63%  |
| SK hynix            | 27       | 16.56%  |
| Unknown             | 24       | 14.72%  |
| Micron Technology   | 18       | 11.04%  |
| Crucial             | 14       | 8.59%   |
| Patriot             | 4        | 2.45%   |
| Corsair             | 4        | 2.45%   |
| G.Skill             | 3        | 1.84%   |
| A-DATA Technology   | 2        | 1.23%   |
| Transcend           | 1        | 0.61%   |
| Nanya Technology    | 1        | 0.61%   |
| Mushkin             | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 6        | 3.26%   |
| Samsung RAM Module 8192MB DIMM DDR4 3200MT/s             | 4        | 2.17%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s      | 4        | 2.17%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2667MT/s | 4        | 2.17%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 2        | 1.09%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s            | 2        | 1.09%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s     | 2        | 1.09%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 2        | 1.09%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8192MB DIMM DDR4 2400MT/s    | 2        | 1.09%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s     | 2        | 1.09%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 2        | 1.09%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s  | 2        | 1.09%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.54%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s              | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM 800MT/s                   | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.54%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s               | 1        | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3 800MT/s            | 1        | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s            | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM LPDDR4 1600MT/s           | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM 1067MT/s                  | 1        | 0.54%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s            | 1        | 0.54%   |
| Unknown RAM Module 16384MB DIMM 1067MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s              | 1        | 0.54%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 1        | 0.54%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 1        | 0.54%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s     | 1        | 0.54%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s         | 1        | 0.54%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s             | 1        | 0.54%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 65535MT/s         | 1        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 62       | 42.76%  |
| DDR4         | 60       | 41.38%  |
| Unknown      | 11       | 7.59%   |
| DDR2         | 8        | 5.52%   |
| SDRAM        | 1        | 0.69%   |
| LPDDR4       | 1        | 0.69%   |
| DDR2 FB-DIMM | 1        | 0.69%   |
| DDR          | 1        | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 133      | 91.1%   |
| SODIMM | 11       | 7.53%   |
| RIMM   | 2        | 1.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 33.13%  |
| 4096  | 48       | 30%     |
| 16384 | 26       | 16.25%  |
| 2048  | 21       | 13.13%  |
| 32768 | 7        | 4.38%   |
| 1024  | 5        | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 34       | 21.38%  |
| 1333    | 25       | 15.72%  |
| 2400    | 19       | 11.95%  |
| 2667    | 17       | 10.69%  |
| 3200    | 11       | 6.92%   |
| 800     | 10       | 6.29%   |
| 2133    | 9        | 5.66%   |
| 2800    | 4        | 2.52%   |
| 667     | 4        | 2.52%   |
| Unknown | 4        | 2.52%   |
| 3600    | 2        | 1.26%   |
| 2134    | 2        | 1.26%   |
| 2000    | 2        | 1.26%   |
| 1800    | 2        | 1.26%   |
| 1648    | 2        | 1.26%   |
| 65535   | 1        | 0.63%   |
| 4333    | 1        | 0.63%   |
| 3500    | 1        | 0.63%   |
| 3466    | 1        | 0.63%   |
| 2933    | 1        | 0.63%   |
| 2666    | 1        | 0.63%   |
| 2465    | 1        | 0.63%   |
| 1867    | 1        | 0.63%   |
| 1866    | 1        | 0.63%   |
| 1336    | 1        | 0.63%   |
| 1067    | 1        | 0.63%   |
| 400     | 1        | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 3        | 50%     |
| Star Micronics     | 1        | 16.67%  |
| Canon              | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Star Micronics TSP100ECO/TSP100II | 1        | 16.67%  |
| HP LaserJet 400 M401a             | 1        | 16.67%  |
| HP LaserJet 3030                  | 1        | 16.67%  |
| HP LaserJet 1020                  | 1        | 16.67%  |
| Canon MF210 Series                | 1        | 16.67%  |
| Brother MFC-9130CW                | 1        | 16.67%  |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 2        | 25%     |
| Z-Star Microelectronics  | 1        | 12.5%   |
| WaveRider Communications | 1        | 12.5%   |
| Samsung Electronics      | 1        | 12.5%   |
| Realtek Semiconductor    | 1        | 12.5%   |
| Microsoft                | 1        | 12.5%   |
| Generalplus Technology   | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera               | 1        | 12.5%   |
| WaveRider USB 2.0 Camera                 | 1        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 12.5%   |
| Realtek USB Camera                       | 1        | 12.5%   |
| Microsoft LifeCam HD-5000                | 1        | 12.5%   |
| Logitech Webcam C310                     | 1        | 12.5%   |
| Logitech HD Pro Webcam C920              | 1        | 12.5%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 12.5%   |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 108      | 64.67%  |
| 1     | 38       | 22.75%  |
| 2     | 11       | 6.59%   |
| 4     | 7        | 4.19%   |
| 3     | 3        | 1.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 30       | 33.71%  |
| Communication controller | 24       | 26.97%  |
| Net/wireless             | 14       | 15.73%  |
| Unassigned class         | 9        | 10.11%  |
| Net/ethernet             | 7        | 7.87%   |
| Storage/raid             | 1        | 1.12%   |
| Sound                    | 1        | 1.12%   |
| Network                  | 1        | 1.12%   |
| Multimedia controller    | 1        | 1.12%   |
| Modem                    | 1        | 1.12%   |

