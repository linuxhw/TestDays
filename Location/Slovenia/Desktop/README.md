Linux in Slovenia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

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

Total: 280

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85-HD3                     | [9fc43e3fa9](https://linux-hardware.org/?probe=9fc43e3fa9) | Dec 25, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [1cc758dd90](https://linux-hardware.org/?probe=1cc758dd90) | Dec 23, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [7386613d29](https://linux-hardware.org/?probe=7386613d29) | Dec 23, 2024 |
| ASUSTek       | PRIME A320M-K               | [03151f3639](https://linux-hardware.org/?probe=03151f3639) | Dec 05, 2024 |
| Shenzhen s... | miniPC                      | [51b66542ff](https://linux-hardware.org/?probe=51b66542ff) | Nov 25, 2024 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [5b576dfbd4](https://linux-hardware.org/?probe=5b576dfbd4) | Nov 19, 2024 |
| ASRock        | A320M Pro4                  | [69c029ae2e](https://linux-hardware.org/?probe=69c029ae2e) | Nov 18, 2024 |
| Sun Micros... | Ultra 27 52                 | [0f59d982bf](https://linux-hardware.org/?probe=0f59d982bf) | Oct 29, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS       | [aefe5002a6](https://linux-hardware.org/?probe=aefe5002a6) | Oct 27, 2024 |
| ASUSTek       | SABERTOOTH Z77              | [46c6dbdba4](https://linux-hardware.org/?probe=46c6dbdba4) | Oct 24, 2024 |
| Lenovo        | 3730 SDK0J40700 WIN 3258... | [3b25a86203](https://linux-hardware.org/?probe=3b25a86203) | Oct 12, 2024 |
| HP            | 3396                        | [96f0a19516](https://linux-hardware.org/?probe=96f0a19516) | Oct 11, 2024 |
| HP            | 3647h                       | [13f1cfebb3](https://linux-hardware.org/?probe=13f1cfebb3) | Oct 03, 2024 |
| ASRock        | B650E Taichi Lite           | [5ab1034596](https://linux-hardware.org/?probe=5ab1034596) | Sep 29, 2024 |
| ASRock        | Z390 Pro4                   | [c8c75cfab5](https://linux-hardware.org/?probe=c8c75cfab5) | Sep 28, 2024 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [d04852d9b1](https://linux-hardware.org/?probe=d04852d9b1) | Sep 26, 2024 |
| ASRock        | B650 LiveMixer              | [d93a1235de](https://linux-hardware.org/?probe=d93a1235de) | Sep 18, 2024 |
| MSI           | B650M GAMING PLUS WIFI      | [34e5a8dcd4](https://linux-hardware.org/?probe=34e5a8dcd4) | Sep 17, 2024 |
| ASUSTek       | X99-A/USB                   | [151237208c](https://linux-hardware.org/?probe=151237208c) | Sep 12, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [6759b6dbf3](https://linux-hardware.org/?probe=6759b6dbf3) | Sep 11, 2024 |
| Lenovo        | 31900058 STD or WIN         | [ce3389610d](https://linux-hardware.org/?probe=ce3389610d) | Sep 10, 2024 |
| HP            | 8592                        | [abba683c46](https://linux-hardware.org/?probe=abba683c46) | Sep 08, 2024 |
| Gigabyte      | AX370-Gaming K7             | [de310bfbfe](https://linux-hardware.org/?probe=de310bfbfe) | Sep 03, 2024 |
| HP            | 8592                        | [d7f2c9eb4c](https://linux-hardware.org/?probe=d7f2c9eb4c) | Aug 29, 2024 |
| ASUSTek       | PRIME B650M-A II            | [435c79deb6](https://linux-hardware.org/?probe=435c79deb6) | Aug 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3d53c7ed41](https://linux-hardware.org/?probe=3d53c7ed41) | Aug 25, 2024 |
| ASRock        | B650 LiveMixer              | [59e07607bc](https://linux-hardware.org/?probe=59e07607bc) | Aug 22, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | [01ce9d6528](https://linux-hardware.org/?probe=01ce9d6528) | Aug 16, 2024 |
| Gigabyte      | EX58-UD3R                   | [5e7086985d](https://linux-hardware.org/?probe=5e7086985d) | Jul 10, 2024 |
| Gigabyte      | G41MT-S2                    | [d468d4f9bd](https://linux-hardware.org/?probe=d468d4f9bd) | Jul 04, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [a33215a452](https://linux-hardware.org/?probe=a33215a452) | May 27, 2024 |
| Gigabyte      | H61M-S2PV                   | [5fb5dd4b81](https://linux-hardware.org/?probe=5fb5dd4b81) | May 26, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1ec3a98637](https://linux-hardware.org/?probe=1ec3a98637) | May 21, 2024 |
| Gigabyte      | X99-UD7 WIFI-CF             | [b7389a656c](https://linux-hardware.org/?probe=b7389a656c) | Apr 27, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [d9d4c8fda0](https://linux-hardware.org/?probe=d9d4c8fda0) | Apr 21, 2024 |
| HP            | 886C                        | [c36efe4b45](https://linux-hardware.org/?probe=c36efe4b45) | Mar 30, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | [82d7d88e80](https://linux-hardware.org/?probe=82d7d88e80) | Mar 25, 2024 |
| Gigabyte      | Z68P-DS3                    | [68be72f718](https://linux-hardware.org/?probe=68be72f718) | Mar 01, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [a0d12d4111](https://linux-hardware.org/?probe=a0d12d4111) | Feb 21, 2024 |
| HP            | 3647h                       | [f504108ab7](https://linux-hardware.org/?probe=f504108ab7) | Feb 10, 2024 |
| ASUSTek       | SABERTOOTH Z77              | [94b425089f](https://linux-hardware.org/?probe=94b425089f) | Jan 24, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [360a430907](https://linux-hardware.org/?probe=360a430907) | Jan 09, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [615d88f290](https://linux-hardware.org/?probe=615d88f290) | Jan 05, 2024 |
| ASRock        | H61M-VG4                    | [6eee51a63f](https://linux-hardware.org/?probe=6eee51a63f) | Dec 31, 2023 |
| ASRock        | H61M-VG4                    | [1c5959e766](https://linux-hardware.org/?probe=1c5959e766) | Dec 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [4202011d88](https://linux-hardware.org/?probe=4202011d88) | Dec 09, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [d46afc319c](https://linux-hardware.org/?probe=d46afc319c) | Nov 30, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [f6e7c5e8a3](https://linux-hardware.org/?probe=f6e7c5e8a3) | Nov 29, 2023 |
| MSI           | A320M PRO-VH PLUS           | [fbee1b0cb7](https://linux-hardware.org/?probe=fbee1b0cb7) | Nov 26, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [829e6fdd78](https://linux-hardware.org/?probe=829e6fdd78) | Nov 23, 2023 |
| HP            | 1589                        | [481cc393d1](https://linux-hardware.org/?probe=481cc393d1) | Nov 19, 2023 |
| Gigabyte      | H61M-D2-B3                  | [358c0e28e9](https://linux-hardware.org/?probe=358c0e28e9) | Nov 17, 2023 |
| ASUSTek       | H110M-A                     | [a721fea460](https://linux-hardware.org/?probe=a721fea460) | Oct 23, 2023 |
| ASUSTek       | PRIME H510M-E               | [375e62bbf4](https://linux-hardware.org/?probe=375e62bbf4) | Oct 17, 2023 |
| ASUSTek       | M5A88-M                     | [e73165d1b3](https://linux-hardware.org/?probe=e73165d1b3) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e590e7eb2c](https://linux-hardware.org/?probe=e590e7eb2c) | Oct 04, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| Foxconn       | 2ABF                        | [b566fc3ff3](https://linux-hardware.org/?probe=b566fc3ff3) | Sep 23, 2023 |
| ASUSTek       | P5Q SE PLUS                 | [311596a316](https://linux-hardware.org/?probe=311596a316) | Aug 30, 2023 |
| HP            | 1589                        | [047e0158e8](https://linux-hardware.org/?probe=047e0158e8) | Aug 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| Gigabyte      | EP45-UD3LR                  | [0f3d20a423](https://linux-hardware.org/?probe=0f3d20a423) | Aug 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [a14f4895b0](https://linux-hardware.org/?probe=a14f4895b0) | Jul 17, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| AZW           | EQ                          | [98e574abed](https://linux-hardware.org/?probe=98e574abed) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| ASRock        | H170M Pro4                  | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| HP            | 2AF7                        | [b459ce46cb](https://linux-hardware.org/?probe=b459ce46cb) | May 27, 2023 |
| ASRock        | B550 Steel Legend           | [35534cbfba](https://linux-hardware.org/?probe=35534cbfba) | Apr 19, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Gigabyte      | M61SME-S2                   | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| ASRock        | Q1900M                      | [dfae44d3f6](https://linux-hardware.org/?probe=dfae44d3f6) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [f46913bb86](https://linux-hardware.org/?probe=f46913bb86) | Apr 02, 2023 |
| HP            | 1998                        | [d88ffd3db4](https://linux-hardware.org/?probe=d88ffd3db4) | Apr 01, 2023 |
| HP            | 8053                        | [6c887800bb](https://linux-hardware.org/?probe=6c887800bb) | Apr 01, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | [7b984afb2c](https://linux-hardware.org/?probe=7b984afb2c) | Mar 29, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| HP            | 1589                        | [5c483a16fc](https://linux-hardware.org/?probe=5c483a16fc) | Mar 18, 2023 |
| ASUSTek       | M5A88-M                     | [4b1712febb](https://linux-hardware.org/?probe=4b1712febb) | Mar 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | EX58-UD5                    | [eaec9511de](https://linux-hardware.org/?probe=eaec9511de) | Feb 27, 2023 |
| Gigabyte      | EX58-UD5                    | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| ASUSTek       | Z97-PRO                     | [0e241538c1](https://linux-hardware.org/?probe=0e241538c1) | Jan 29, 2023 |
| ASUSTek       | Z170-K                      | [2cf59bd38d](https://linux-hardware.org/?probe=2cf59bd38d) | Jan 26, 2023 |
| Lenovo        | MAHOBAY NOK                 | [6bd02bf2c0](https://linux-hardware.org/?probe=6bd02bf2c0) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Medion        | MS-7621                     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| MSI           | Z170-A PRO                  | [3948dcc7ef](https://linux-hardware.org/?probe=3948dcc7ef) | Dec 23, 2022 |
| HP            | 8594                        | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Gigabyte      | B650M GAMING X AX           | [01b7250cea](https://linux-hardware.org/?probe=01b7250cea) | Dec 19, 2022 |
| Gigabyte      | B650M GAMING X AX           | [999cbfe9f7](https://linux-hardware.org/?probe=999cbfe9f7) | Dec 19, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| ASRock        | H55M-LE                     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| HP            | 8591                        | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| Gigabyte      | H81M-S2PV                   | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| ASRock        | H61M-HVS                    | [5348794267](https://linux-hardware.org/?probe=5348794267) | Oct 09, 2022 |
| HP            | 18E4                        | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| ASRock        | H61M-HVS                    | [660419ed49](https://linux-hardware.org/?probe=660419ed49) | Sep 27, 2022 |
| MSI           | X570-A PRO                  | [0306edc8ba](https://linux-hardware.org/?probe=0306edc8ba) | Sep 22, 2022 |
| MSI           | X570-A PRO                  | [56d6df17b5](https://linux-hardware.org/?probe=56d6df17b5) | Sep 22, 2022 |
| ASUSTek       | PRIME B550M-K               | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [600ef31484](https://linux-hardware.org/?probe=600ef31484) | Sep 15, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [4c7f501c2b](https://linux-hardware.org/?probe=4c7f501c2b) | Sep 02, 2022 |
| HP            | 8053                        | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| ASRock        | H110M-DVS R2.0              | [adae304d62](https://linux-hardware.org/?probe=adae304d62) | Aug 24, 2022 |
| Supermicro    | X7SBi-LN4                   | [ec37ffcc15](https://linux-hardware.org/?probe=ec37ffcc15) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | [0e195b05bf](https://linux-hardware.org/?probe=0e195b05bf) | Jul 13, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d59692d648](https://linux-hardware.org/?probe=d59692d648) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [4afafc5b76](https://linux-hardware.org/?probe=4afafc5b76) | Jun 29, 2022 |
| HP            | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| ASRock        | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
| ASRock        | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| Intel         | CM-iAM/SBC-FITPC2i          | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [934d403a31](https://linux-hardware.org/?probe=934d403a31) | May 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| MSI           | X570-A PRO                  | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| ASUSTek       | PRIME B250M-A               | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| ASUSTek       | PRIME A320M-K               | [9d5d5c0ffb](https://linux-hardware.org/?probe=9d5d5c0ffb) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| Dell          | 09M8Y8 A02                  | [202fc1f0b9](https://linux-hardware.org/?probe=202fc1f0b9) | Feb 22, 2022 |
| ASUSTek       | PRIME H410M-A               | [cad9a70c49](https://linux-hardware.org/?probe=cad9a70c49) | Feb 16, 2022 |
| ASUSTek       | PRIME H410M-A               | [676d121bda](https://linux-hardware.org/?probe=676d121bda) | Feb 13, 2022 |
| Gigabyte      | EP45-UD3LR                  | [239eb94a17](https://linux-hardware.org/?probe=239eb94a17) | Feb 07, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| HP            | 1589                        | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Pegatron      | EVE                         | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| ASRock        | B85M-HDS                    | [77cb3218a8](https://linux-hardware.org/?probe=77cb3218a8) | Jan 12, 2022 |
| Lenovo        | ThinkCentre M57e 9439WHV    | [a9b2163945](https://linux-hardware.org/?probe=a9b2163945) | Dec 25, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASUSTek       | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Gigabyte      | H57M-USB3                   | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| Gigabyte      | H61M-S2PV                   | [163092e4b9](https://linux-hardware.org/?probe=163092e4b9) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| ASUSTek       | PRIME Z270-A                | [a11d4b7c50](https://linux-hardware.org/?probe=a11d4b7c50) | Oct 20, 2021 |
| ASRock        | X300M-STX                   | [cd738f5036](https://linux-hardware.org/?probe=cd738f5036) | Oct 11, 2021 |
| ASRock        | X300M-STX                   | [bc1fd03a63](https://linux-hardware.org/?probe=bc1fd03a63) | Oct 10, 2021 |
| ASRock        | X300M-STX                   | [6ec6ce5c81](https://linux-hardware.org/?probe=6ec6ce5c81) | Oct 10, 2021 |
| MSI           | X570-A PRO                  | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| Medion        | Akoya E7226                 | [9367472acb](https://linux-hardware.org/?probe=9367472acb) | Sep 18, 2021 |
| MSI           | X570-A PRO                  | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| ASRock        | H310CM-HDV                  | [0fccd48745](https://linux-hardware.org/?probe=0fccd48745) | Aug 13, 2021 |
| MSI           | X570-A PRO                  | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| ASUSTek       | PRIME A320M-K               | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| MSI           | H61M-P31                    | [ccd9d80d59](https://linux-hardware.org/?probe=ccd9d80d59) | Jul 18, 2021 |
| Pegatron      | 2A73                        | [2bff425af7](https://linux-hardware.org/?probe=2bff425af7) | Jul 14, 2021 |
| Pegatron      | 2A73                        | [44ea7169ef](https://linux-hardware.org/?probe=44ea7169ef) | Jul 14, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [bc18a23953](https://linux-hardware.org/?probe=bc18a23953) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Gigabyte      | F2A88XM-D3HP                | [02bf919368](https://linux-hardware.org/?probe=02bf919368) | Jun 02, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | [3e6d98fe9c](https://linux-hardware.org/?probe=3e6d98fe9c) | Apr 27, 2021 |
| ASRock        | B560 Pro4                   | [ddd384c6cb](https://linux-hardware.org/?probe=ddd384c6cb) | Apr 26, 2021 |
| Lenovo        | ThinkCentre M55e 9389WEG    | [66c2003859](https://linux-hardware.org/?probe=66c2003859) | Apr 20, 2021 |
| HP            | 1905                        | [e0fc243f47](https://linux-hardware.org/?probe=e0fc243f47) | Apr 19, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | [325f4ca461](https://linux-hardware.org/?probe=325f4ca461) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | [1c3958d998](https://linux-hardware.org/?probe=1c3958d998) | Apr 05, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | [1038d58fea](https://linux-hardware.org/?probe=1038d58fea) | Mar 25, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | [8b28b318fd](https://linux-hardware.org/?probe=8b28b318fd) | Mar 19, 2021 |
| Gigabyte      | H61M-D2-B3                  | [453120855b](https://linux-hardware.org/?probe=453120855b) | Mar 18, 2021 |
| Apple         | Mac-F4208DA9 PVT            | [4ab255096c](https://linux-hardware.org/?probe=4ab255096c) | Feb 28, 2021 |
| Dell          | 0C27VV A02                  | [49cd056ca4](https://linux-hardware.org/?probe=49cd056ca4) | Feb 24, 2021 |
| Gigabyte      | P35C-DS3R                   | [bd76fdbde8](https://linux-hardware.org/?probe=bd76fdbde8) | Feb 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [153bb12a6a](https://linux-hardware.org/?probe=153bb12a6a) | Feb 19, 2021 |
| MSI           | H61M-P31                    | [a0192f9d6e](https://linux-hardware.org/?probe=a0192f9d6e) | Feb 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [106c66da60](https://linux-hardware.org/?probe=106c66da60) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| ASUSTek       | P7H55-M SI                  | [e40fe3768d](https://linux-hardware.org/?probe=e40fe3768d) | Feb 09, 2021 |
| Gigabyte      | P35C-DS3R                   | [a31754db23](https://linux-hardware.org/?probe=a31754db23) | Feb 08, 2021 |
| Pegatron      | 2A73                        | [4c2042c088](https://linux-hardware.org/?probe=4c2042c088) | Jan 18, 2021 |
| Pegatron      | 2A73                        | [c6cf8a7efe](https://linux-hardware.org/?probe=c6cf8a7efe) | Jan 18, 2021 |
| MSI           | H55M-P31                    | [3313a8aba5](https://linux-hardware.org/?probe=3313a8aba5) | Jan 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| Gigabyte      | H61M-D2-B3                  | [60d8b9344b](https://linux-hardware.org/?probe=60d8b9344b) | Jan 09, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| Gigabyte      | H270-HD3-CF                 | [b6c93666ee](https://linux-hardware.org/?probe=b6c93666ee) | Dec 29, 2020 |
| Gigabyte      | H270-HD3-CF                 | [7905034ba5](https://linux-hardware.org/?probe=7905034ba5) | Dec 29, 2020 |
| Gigabyte      | H270-HD3-CF                 | [71370e1dd8](https://linux-hardware.org/?probe=71370e1dd8) | Dec 19, 2020 |
| Gigabyte      | B450M GAMING                | [def1b6fff4](https://linux-hardware.org/?probe=def1b6fff4) | Dec 13, 2020 |
| Pegatron      | EVE                         | [08ced52205](https://linux-hardware.org/?probe=08ced52205) | Nov 29, 2020 |
| ASRock        | H110M-HDV R3.0              | [c3df499de1](https://linux-hardware.org/?probe=c3df499de1) | Nov 12, 2020 |
| ASRock        | H110M-HDV R3.0              | [e05c144d2f](https://linux-hardware.org/?probe=e05c144d2f) | Nov 12, 2020 |
| Lenovo        | ThinkCentre M55e 9389WEG    | [2462c80a14](https://linux-hardware.org/?probe=2462c80a14) | Nov 10, 2020 |
| ASUSTek       | Z97-K                       | [e8f7b6ef7e](https://linux-hardware.org/?probe=e8f7b6ef7e) | Nov 07, 2020 |
| ASUSTek       | Z97-K                       | [7e9d52855a](https://linux-hardware.org/?probe=7e9d52855a) | Nov 07, 2020 |
| MSI           | B450 TOMAHAWK               | [1e6ba50614](https://linux-hardware.org/?probe=1e6ba50614) | Nov 04, 2020 |
| Intel         | DH87RL AAG74240-403         | [caa0e9c93b](https://linux-hardware.org/?probe=caa0e9c93b) | Nov 02, 2020 |
| Gigabyte      | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| MSI           | B360M PRO-VDH               | [d336eeaa8d](https://linux-hardware.org/?probe=d336eeaa8d) | Oct 21, 2020 |
| Lenovo        | 3098 NOK                    | [2c592ebb94](https://linux-hardware.org/?probe=2c592ebb94) | Oct 19, 2020 |
| Lenovo        | 3098 NOK                    | [92a22bd753](https://linux-hardware.org/?probe=92a22bd753) | Oct 19, 2020 |
| Gigabyte      | Z68P-DS3                    | [2e8b092dbc](https://linux-hardware.org/?probe=2e8b092dbc) | Oct 12, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [da4740881e](https://linux-hardware.org/?probe=da4740881e) | Oct 04, 2020 |
| Pegatron      | 2A94h                       | [3a1ede6188](https://linux-hardware.org/?probe=3a1ede6188) | Oct 03, 2020 |
| Gigabyte      | F2A88XM-D3HP                | [1d3401ff46](https://linux-hardware.org/?probe=1d3401ff46) | Oct 02, 2020 |
| Intel         | DQ35JO AAD82085-801         | [51c42a0f25](https://linux-hardware.org/?probe=51c42a0f25) | Sep 17, 2020 |
| Pegatron      | 2A73                        | [a4607af679](https://linux-hardware.org/?probe=a4607af679) | Aug 25, 2020 |
| Pegatron      | 2A73                        | [f2c225880d](https://linux-hardware.org/?probe=f2c225880d) | Aug 25, 2020 |
| HP            | 3048h                       | [0bc2b9bafc](https://linux-hardware.org/?probe=0bc2b9bafc) | Aug 17, 2020 |
| ASUSTek       | P7H55-M SI                  | [c323481902](https://linux-hardware.org/?probe=c323481902) | Jun 14, 2020 |
| ASUSTek       | P7H55-M SI                  | [6889f53e3b](https://linux-hardware.org/?probe=6889f53e3b) | Jun 13, 2020 |
| ASRock        | X570 Extreme4               | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | PRIME H370-PLUS             | [d7dee77bfc](https://linux-hardware.org/?probe=d7dee77bfc) | Jun 04, 2020 |
| Gigabyte      | B85M-HD3                    | [03b36ff9c1](https://linux-hardware.org/?probe=03b36ff9c1) | May 28, 2020 |
| ASRock        | Z390 Pro4                   | [e1c0c74ca6](https://linux-hardware.org/?probe=e1c0c74ca6) | May 25, 2020 |
| MSI           | H61M-P31                    | [870b2534d7](https://linux-hardware.org/?probe=870b2534d7) | May 22, 2020 |
| MSI           | H110M ECO                   | [fe6009a465](https://linux-hardware.org/?probe=fe6009a465) | May 15, 2020 |
| Lenovo        | ThinkCentre M55e 9389W11    | [f148017266](https://linux-hardware.org/?probe=f148017266) | Apr 12, 2020 |
| ASUSTek       | H170 PRO GAMING             | [f9c3afb706](https://linux-hardware.org/?probe=f9c3afb706) | Apr 08, 2020 |
| Gigabyte      | B360M DS3H                  | [17dd7e6ddb](https://linux-hardware.org/?probe=17dd7e6ddb) | Apr 05, 2020 |
| Lenovo        | ThinkCentre M57e 9356W2K    | [663d112138](https://linux-hardware.org/?probe=663d112138) | Apr 02, 2020 |
| HP            | 0A58h                       | [0734e4224d](https://linux-hardware.org/?probe=0734e4224d) | Mar 16, 2020 |
| ASUSTek       | H110M-A                     | [9a43e8f82a](https://linux-hardware.org/?probe=9a43e8f82a) | Feb 26, 2020 |
| ASUSTek       | H110M-A                     | [0722f7ccf8](https://linux-hardware.org/?probe=0722f7ccf8) | Feb 22, 2020 |
| ASUSTek       | P8Z77-M PRO                 | [44e0ce8fc8](https://linux-hardware.org/?probe=44e0ce8fc8) | Jan 24, 2020 |
| Medion        | MS-7707                     | [3feacd8f08](https://linux-hardware.org/?probe=3feacd8f08) | Jan 19, 2020 |
| Medion        | MS-7707                     | [5d5096c9a8](https://linux-hardware.org/?probe=5d5096c9a8) | Jan 18, 2020 |
| Biostar       | TH55B HD                    | [3f28da0706](https://linux-hardware.org/?probe=3f28da0706) | Jan 17, 2020 |
| Biostar       | TH55B HD                    | [980b5da590](https://linux-hardware.org/?probe=980b5da590) | Jan 02, 2020 |
| Biostar       | TH55B HD                    | [e13730f188](https://linux-hardware.org/?probe=e13730f188) | Dec 25, 2019 |
| HP            | 1495                        | [d56240bfb5](https://linux-hardware.org/?probe=d56240bfb5) | Dec 07, 2019 |
| Gigabyte      | F2A88XM-D3HP                | [de68096cdc](https://linux-hardware.org/?probe=de68096cdc) | Nov 27, 2019 |
| ASRock        | H61M-DGS R2.0               | [7ad66ff018](https://linux-hardware.org/?probe=7ad66ff018) | Nov 23, 2019 |
| ASRock        | H61M-DGS R2.0               | [837d7c2621](https://linux-hardware.org/?probe=837d7c2621) | Nov 23, 2019 |
| HP            | 1495                        | [7517e7c74d](https://linux-hardware.org/?probe=7517e7c74d) | Nov 20, 2019 |
| HP            | 1495                        | [b4598c0e73](https://linux-hardware.org/?probe=b4598c0e73) | Nov 19, 2019 |
| HP            | 1495                        | [ab3f7ddb42](https://linux-hardware.org/?probe=ab3f7ddb42) | Nov 05, 2019 |
| HP            | 1495                        | [75e4e80f87](https://linux-hardware.org/?probe=75e4e80f87) | Oct 04, 2019 |
| HP            | 1495                        | [470c7daaaa](https://linux-hardware.org/?probe=470c7daaaa) | Sep 20, 2019 |
| HP            | 1495                        | [4f34ee60db](https://linux-hardware.org/?probe=4f34ee60db) | Sep 17, 2019 |
| Medion        | MS-7707                     | [9b50675efd](https://linux-hardware.org/?probe=9b50675efd) | Aug 03, 2019 |
| ASUSTek       | PRIME X470-PRO              | [4a2455eae6](https://linux-hardware.org/?probe=4a2455eae6) | Jul 28, 2019 |
| ASUSTek       | PRIME X470-PRO              | [8d117b8f35](https://linux-hardware.org/?probe=8d117b8f35) | Jul 28, 2019 |
| Gigabyte      | F2A88XM-D3HP                | [ab7980dba3](https://linux-hardware.org/?probe=ab7980dba3) | Jul 01, 2019 |
| Medion        | MS-7707                     | [b843e52e30](https://linux-hardware.org/?probe=b843e52e30) | Jun 03, 2019 |
| Lenovo        | ThinkCentre M57 6072VAM     | [c399cbb5f3](https://linux-hardware.org/?probe=c399cbb5f3) | May 04, 2019 |
| ASUSTek       | PRIME X370-PRO              | [8ad90844e8](https://linux-hardware.org/?probe=8ad90844e8) | Apr 16, 2019 |
| Medion        | MS-7707                     | [71684dcee4](https://linux-hardware.org/?probe=71684dcee4) | Apr 12, 2019 |
| HP            | 0A68h                       | [fa9c3d044f](https://linux-hardware.org/?probe=fa9c3d044f) | Mar 13, 2019 |
| Intel         | DQ67SW AAG12527-310         | [d304d79466](https://linux-hardware.org/?probe=d304d79466) | Mar 10, 2019 |
| ASUSTek       | PRIME X470-PRO              | [8348d3c21e](https://linux-hardware.org/?probe=8348d3c21e) | Feb 23, 2019 |
| HP            | 82A2                        | [0f9aa13b55](https://linux-hardware.org/?probe=0f9aa13b55) | Feb 21, 2019 |
| ASUSTek       | PRIME X470-PRO              | [0407ee67e9](https://linux-hardware.org/?probe=0407ee67e9) | Feb 11, 2019 |
| HP            | 0A68h                       | [7b0d921779](https://linux-hardware.org/?probe=7b0d921779) | Dec 15, 2018 |
| HP            | 0A68h                       | [b773c3a27d](https://linux-hardware.org/?probe=b773c3a27d) | Dec 15, 2018 |
| HP            | 0A68h                       | [11bcd6f218](https://linux-hardware.org/?probe=11bcd6f218) | Dec 15, 2018 |
| Gigabyte      | 970A-UD3P                   | [d48dca3ee3](https://linux-hardware.org/?probe=d48dca3ee3) | Feb 18, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 27       | 13.04%  |
| Ubuntu 22.04                 | 13       | 6.28%   |
| Ubuntu 18.04                 | 9        | 4.35%   |
| OpenMandriva 4.3             | 8        | 3.86%   |
| Zorin 16                     | 6        | 2.9%    |
| ArcoLinux Rolling            | 6        | 2.9%    |
| KDE neon 22.04               | 5        | 2.42%   |
| Arch Rolling                 | 5        | 2.42%   |
| Ubuntu 24.04                 | 4        | 1.93%   |
| OpenMandriva 23.03           | 4        | 1.93%   |
| Kubuntu 22.04                | 4        | 1.93%   |
| KDE neon 20.04               | 4        | 1.93%   |
| Xubuntu 20.04                | 3        | 1.45%   |
| Ubuntu 19.10                 | 3        | 1.45%   |
| Pop!_OS 20.04                | 3        | 1.45%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.45%   |
| OpenMandriva 23.08           | 3        | 1.45%   |
| Linux Mint 19.3              | 3        | 1.45%   |
| Fedora 40                    | 3        | 1.45%   |
| Debian 12                    | 3        | 1.45%   |
| Ubuntu 20.10                 | 2        | 0.97%   |
| Ubuntu 18.10                 | 2        | 0.97%   |
| Pop!_OS 22.04                | 2        | 0.97%   |
| Pop!_OS 21.10                | 2        | 0.97%   |
| OpenMandriva 4.2             | 2        | 0.97%   |
| OpenMandriva 24.07           | 2        | 0.97%   |
| Linux Mint 22                | 2        | 0.97%   |
| Linux Mint 21.3              | 2        | 0.97%   |
| Kubuntu 20.04                | 2        | 0.97%   |
| Fedora 38                    | 2        | 0.97%   |
| Fedora 37                    | 2        | 0.97%   |
| Fedora 35                    | 2        | 0.97%   |
| EndeavourOS Rolling          | 2        | 0.97%   |
| Debian 11                    | 2        | 0.97%   |
| Zorin 17                     | 1        | 0.48%   |
| Zorin 15                     | 1        | 0.48%   |
| Xubuntu 22.04                | 1        | 0.48%   |
| Xubuntu 21.10                | 1        | 0.48%   |
| Xubuntu 18.04                | 1        | 0.48%   |
| Ubuntu Unity 18.04           | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 59       | 30.73%  |
| OpenMandriva  | 20       | 10.42%  |
| Linux Mint    | 12       | 6.25%   |
| Fedora        | 10       | 5.21%   |
| KDE neon      | 9        | 4.69%   |
| Zorin         | 7        | 3.65%   |
| Pop!_OS       | 7        | 3.65%   |
| Kubuntu       | 7        | 3.65%   |
| Xubuntu       | 6        | 3.13%   |
| Manjaro       | 6        | 3.13%   |
| ArcoLinux     | 6        | 3.13%   |
| Arch          | 6        | 3.13%   |
| Debian        | 5        | 2.6%    |
| openSUSE      | 4        | 2.08%   |
| Gentoo        | 4        | 2.08%   |
| EndeavourOS   | 3        | 1.56%   |
| Ubuntu Unity  | 2        | 1.04%   |
| Ubuntu MATE   | 2        | 1.04%   |
| NixOS         | 2        | 1.04%   |
| Endless       | 2        | 1.04%   |
| Ubuntu Kylin  | 1        | 0.52%   |
| Ubuntu Budgie | 1        | 0.52%   |
| ROSA          | 1        | 0.52%   |
| RHEL          | 1        | 0.52%   |
| Mageia        | 1        | 0.52%   |
| Lubuntu       | 1        | 0.52%   |
| Kali          | 1        | 0.52%   |
| Garuda Linux  | 1        | 0.52%   |
| Elementary    | 1        | 0.52%   |
| CentOS        | 1        | 0.52%   |
| CachyOS       | 1        | 0.52%   |
| BlackPanther  | 1        | 0.52%   |
| Artix         | 1        | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 8        | 3.48%   |
| 5.4.0-48-generic         | 5        | 2.17%   |
| 6.8.0-45-generic         | 3        | 1.3%    |
| 6.2.6-desktop-1omv2390   | 3        | 1.3%    |
| 5.8.0-43-generic         | 3        | 1.3%    |
| 5.4.0-31-generic         | 3        | 1.3%    |
| 5.15.0-56-generic        | 3        | 1.3%    |
| 5.15.0-25-generic        | 3        | 1.3%    |
| 6.8.0-48-generic         | 2        | 0.87%   |
| 6.6.2-desktop-1omv2390   | 2        | 0.87%   |
| 6.4.11-desktop-1omv2390  | 2        | 0.87%   |
| 6.2.0-39-generic         | 2        | 0.87%   |
| 6.2.0-33-generic         | 2        | 0.87%   |
| 5.8.0-36-generic         | 2        | 0.87%   |
| 5.4.0-7642-generic       | 2        | 0.87%   |
| 5.4.0-66-generic         | 2        | 0.87%   |
| 5.4.0-60-generic         | 2        | 0.87%   |
| 5.4.0-52-generic         | 2        | 0.87%   |
| 5.4.0-29-generic         | 2        | 0.87%   |
| 5.4.0-104-generic        | 2        | 0.87%   |
| 5.3.0-40-generic         | 2        | 0.87%   |
| 5.3.0-26-generic         | 2        | 0.87%   |
| 5.3.0-23-generic         | 2        | 0.87%   |
| 5.16.15-76051615-generic | 2        | 0.87%   |
| 5.15.0-58-generic        | 2        | 0.87%   |
| 5.15.0-47-generic        | 2        | 0.87%   |
| 5.15.0-46-generic        | 2        | 0.87%   |
| 5.15.0-43-generic        | 2        | 0.87%   |
| 5.13.0-30-generic        | 2        | 0.87%   |
| 5.13.0-27-generic        | 2        | 0.87%   |
| 5.11.0-40-generic        | 2        | 0.87%   |
| 5.10.14-desktop-1omv4002 | 2        | 0.87%   |
| 4.18.0-17-generic        | 2        | 0.87%   |
| 4.18.0-15-generic        | 2        | 0.87%   |
| 4.15.0-45-generic        | 2        | 0.87%   |
| 6.9.7-desktop-1omv2490   | 1        | 0.43%   |
| 6.9.1-cb1.0.fc40.x86_64  | 1        | 0.43%   |
| 6.8.9-1-default          | 1        | 0.43%   |
| 6.8.7-zen1-1-zen         | 1        | 0.43%   |
| 6.8.0-51-generic         | 1        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 15.21%  |
| 5.15.0  | 22       | 10.14%  |
| 5.8.0   | 11       | 5.07%   |
| 5.16.7  | 9        | 4.15%   |
| 6.8.0   | 8        | 3.69%   |
| 5.13.0  | 8        | 3.69%   |
| 4.18.0  | 8        | 3.69%   |
| 5.3.0   | 7        | 3.23%   |
| 5.11.0  | 6        | 2.76%   |
| 4.15.0  | 6        | 2.76%   |
| 6.2.0   | 5        | 2.3%    |
| 6.2.6   | 4        | 1.84%   |
| 6.1.0   | 4        | 1.84%   |
| 5.10.14 | 3        | 1.38%   |
| 6.6.2   | 2        | 0.92%   |
| 6.5.6   | 2        | 0.92%   |
| 6.5.0   | 2        | 0.92%   |
| 6.4.11  | 2        | 0.92%   |
| 5.19.0  | 2        | 0.92%   |
| 5.16.15 | 2        | 0.92%   |
| 5.10.30 | 2        | 0.92%   |
| 5.0.0   | 2        | 0.92%   |
| 6.9.7   | 1        | 0.46%   |
| 6.9.1   | 1        | 0.46%   |
| 6.8.9   | 1        | 0.46%   |
| 6.8.7   | 1        | 0.46%   |
| 6.7.4   | 1        | 0.46%   |
| 6.6.8   | 1        | 0.46%   |
| 6.6.58  | 1        | 0.46%   |
| 6.6.47  | 1        | 0.46%   |
| 6.6.3   | 1        | 0.46%   |
| 6.5.5   | 1        | 0.46%   |
| 6.4.9   | 1        | 0.46%   |
| 6.4.8   | 1        | 0.46%   |
| 6.4.7   | 1        | 0.46%   |
| 6.4.3   | 1        | 0.46%   |
| 6.4.15  | 1        | 0.46%   |
| 6.4.0   | 1        | 0.46%   |
| 6.3.4   | 1        | 0.46%   |
| 6.2.8   | 1        | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 34       | 16.04%  |
| 5.15    | 27       | 12.74%  |
| 5.16    | 12       | 5.66%   |
| 6.2     | 11       | 5.19%   |
| 5.8     | 11       | 5.19%   |
| 6.8     | 10       | 4.72%   |
| 6.1     | 9        | 4.25%   |
| 5.13    | 9        | 4.25%   |
| 4.18    | 9        | 4.25%   |
| 6.4     | 8        | 3.77%   |
| 5.3     | 7        | 3.3%    |
| 5.11    | 7        | 3.3%    |
| 6.6     | 6        | 2.83%   |
| 6.10    | 6        | 2.83%   |
| 5.10    | 6        | 2.83%   |
| 4.15    | 6        | 2.83%   |
| 6.5     | 5        | 2.36%   |
| 5.14    | 4        | 1.89%   |
| 5.19    | 3        | 1.42%   |
| 5.12    | 3        | 1.42%   |
| 6.9     | 2        | 0.94%   |
| 6.11    | 2        | 0.94%   |
| 6.0     | 2        | 0.94%   |
| 5.6     | 2        | 0.94%   |
| 5.0     | 2        | 0.94%   |
| 6.7     | 1        | 0.47%   |
| 6.3     | 1        | 0.47%   |
| 6.12    | 1        | 0.47%   |
| 5.9     | 1        | 0.47%   |
| 5.7     | 1        | 0.47%   |
| 5.18    | 1        | 0.47%   |
| 5.17    | 1        | 0.47%   |
| 4.20    | 1        | 0.47%   |
| 4.1     | 1        | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 182      | 98.38%  |
| i686   | 3        | 1.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 77       | 38.69%  |
| KDE5       | 48       | 24.12%  |
| Unknown    | 18       | 9.05%   |
| XFCE       | 16       | 8.04%   |
| X-Cinnamon | 8        | 4.02%   |
| KDE6       | 7        | 3.52%   |
| KDE        | 6        | 3.02%   |
| LXQt       | 4        | 2.01%   |
| Cinnamon   | 4        | 2.01%   |
| MATE       | 3        | 1.51%   |
| Unity      | 2        | 1.01%   |
| UKUI       | 1        | 0.5%    |
| Pantheon   | 1        | 0.5%    |
| NsCDE      | 1        | 0.5%    |
| KDE4       | 1        | 0.5%    |
| DWM        | 1        | 0.5%    |
| Budgie     | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 131      | 68.23%  |
| Wayland | 40       | 20.83%  |
| Unknown | 14       | 7.29%   |
| Tty     | 7        | 3.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 39.29%  |
| SDDM    | 49       | 25%     |
| GDM3    | 23       | 11.73%  |
| LightDM | 21       | 10.71%  |
| GDM     | 18       | 9.18%   |
| TDM     | 5        | 2.55%   |
| XDM     | 1        | 0.51%   |
| KDM     | 1        | 0.51%   |
| GREETD  | 1        | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 105      | 54.97%  |
| sl_SI   | 53       | 27.75%  |
| Unknown | 15       | 7.85%   |
| en_GB   | 5        | 2.62%   |
| C       | 4        | 2.09%   |
| de_AT   | 2        | 1.05%   |
| ru_RU   | 1        | 0.52%   |
| it_IT   | 1        | 0.52%   |
| es_ES   | 1        | 0.52%   |
| en_AG   | 1        | 0.52%   |
| de_DE   | 1        | 0.52%   |
| C.UTF8  | 1        | 0.52%   |
| bs_BA   | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 105      | 54.69%  |
| EFI  | 87       | 45.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 123      | 63.73%  |
| Overlay | 25       | 12.95%  |
| Btrfs   | 20       | 10.36%  |
| Tmpfs   | 9        | 4.66%   |
| Xfs     | 6        | 3.11%   |
| Unknown | 6        | 3.11%   |
| Zfs     | 4        | 2.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 90       | 47.37%  |
| Unknown | 77       | 40.53%  |
| MBR     | 23       | 12.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 76.56%  |
| Yes       | 45       | 23.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 69.47%  |
| Yes       | 58       | 30.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUSTek Computer                    | 54       | 29.19%  |
| Gigabyte Technology                 | 36       | 19.46%  |
| ASRock                              | 23       | 12.43%  |
| Hewlett-Packard                     | 19       | 10.27%  |
| MSI                                 | 17       | 9.19%   |
| Lenovo                              | 13       | 7.03%   |
| Pegatron                            | 4        | 2.16%   |
| Intel                               | 4        | 2.16%   |
| Medion                              | 3        | 1.62%   |
| Dell                                | 2        | 1.08%   |
| Supermicro                          | 1        | 0.54%   |
| Sun Microsystems                    | 1        | 0.54%   |
| Shenzhen suqiao computer technology | 1        | 0.54%   |
| Nvidia                              | 1        | 0.54%   |
| Fujitsu                             | 1        | 0.54%   |
| Foxconn                             | 1        | 0.54%   |
| Biostar                             | 1        | 0.54%   |
| AZW                                 | 1        | 0.54%   |
| Apple                               | 1        | 0.54%   |
| Unknown                             | 1        | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7C02                                | 4        | 2.16%   |
| ASUS All Series                            | 3        | 1.62%   |
| Pegatron FL308AA-ABD IQ512de               | 2        | 1.08%   |
| MSI MS-7C37                                | 2        | 1.08%   |
| MSI MS-7788                                | 2        | 1.08%   |
| HP Z420 Workstation                        | 2        | 1.08%   |
| Gigabyte Z68P-DS3                          | 2        | 1.08%   |
| Gigabyte F2A88XM-D3HP                      | 2        | 1.08%   |
| Gigabyte B450M DS3H                        | 2        | 1.08%   |
| ASUS TUF B450-PLUS GAMING                  | 2        | 1.08%   |
| ASUS ROG STRIX Z370-F GAMING               | 2        | 1.08%   |
| ASUS ROG STRIX X570-F GAMING               | 2        | 1.08%   |
| ASUS ROG STRIX X570-E GAMING               | 2        | 1.08%   |
| ASUS PRIME B350-PLUS                       | 2        | 1.08%   |
| ASUS PRIME A320M-K                         | 2        | 1.08%   |
| ASUS P7H55-M SI                            | 2        | 1.08%   |
| ASRock Z390 Pro4                           | 2        | 1.08%   |
| Supermicro X7SBi-LN4                       | 1        | 0.54%   |
| Sun Microsystems Ultra 27                  | 1        | 0.54%   |
| Shenzhen suqiao computer technology miniPC | 1        | 0.54%   |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.54%   |
| Pegatron 2A73                              | 1        | 0.54%   |
| Nvidia MCP79                               | 1        | 0.54%   |
| MSI MS-7E24                                | 1        | 0.54%   |
| MSI MS-7D54                                | 1        | 0.54%   |
| MSI MS-7C91                                | 1        | 0.54%   |
| MSI MS-7B86                                | 1        | 0.54%   |
| MSI MS-7B24                                | 1        | 0.54%   |
| MSI MS-7B07                                | 1        | 0.54%   |
| MSI MS-7994                                | 1        | 0.54%   |
| MSI MS-7971                                | 1        | 0.54%   |
| MSI MS-7636                                | 1        | 0.54%   |
| Medion MS-7707                             | 1        | 0.54%   |
| Medion MS-7621                             | 1        | 0.54%   |
| Medion Akoya E7226                         | 1        | 0.54%   |
| Lenovo ThinkStation S20 4157ZSK            | 1        | 0.54%   |
| Lenovo ThinkCentre M93p 10AAS4DT00         | 1        | 0.54%   |
| Lenovo ThinkCentre M92p 32384B0            | 1        | 0.54%   |
| Lenovo ThinkCentre M90p 5498PK8            | 1        | 0.54%   |
| Lenovo ThinkCentre M73 10B4S1VA00          | 1        | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 15       | 8.11%   |
| ASUS ROG                                   | 11       | 5.95%   |
| Lenovo ThinkCentre                         | 10       | 5.41%   |
| ASUS TUF                                   | 10       | 5.41%   |
| HP EliteDesk                               | 5        | 2.7%    |
| HP Compaq                                  | 5        | 2.7%    |
| MSI MS-7C02                                | 4        | 2.16%   |
| Gigabyte B450M                             | 3        | 1.62%   |
| ASUS All                                   | 3        | 1.62%   |
| Pegatron FL308AA-ABD                       | 2        | 1.08%   |
| MSI MS-7C37                                | 2        | 1.08%   |
| MSI MS-7788                                | 2        | 1.08%   |
| HP Z420                                    | 2        | 1.08%   |
| Gigabyte Z68P-DS3                          | 2        | 1.08%   |
| Gigabyte F2A88XM-D3HP                      | 2        | 1.08%   |
| Gigabyte B650                              | 2        | 1.08%   |
| ASUS SABERTOOTH                            | 2        | 1.08%   |
| ASUS P7H55-M                               | 2        | 1.08%   |
| ASUS P5Q                                   | 2        | 1.08%   |
| ASRock Z390                                | 2        | 1.08%   |
| ASRock X570                                | 2        | 1.08%   |
| Supermicro X7SBi-LN4                       | 1        | 0.54%   |
| Sun Microsystems Ultra                     | 1        | 0.54%   |
| Shenzhen suqiao computer technology miniPC | 1        | 0.54%   |
| Pegatron Pro                               | 1        | 0.54%   |
| Pegatron 2A73                              | 1        | 0.54%   |
| Nvidia MCP79                               | 1        | 0.54%   |
| MSI MS-7E24                                | 1        | 0.54%   |
| MSI MS-7D54                                | 1        | 0.54%   |
| MSI MS-7C91                                | 1        | 0.54%   |
| MSI MS-7B86                                | 1        | 0.54%   |
| MSI MS-7B24                                | 1        | 0.54%   |
| MSI MS-7B07                                | 1        | 0.54%   |
| MSI MS-7994                                | 1        | 0.54%   |
| MSI MS-7971                                | 1        | 0.54%   |
| MSI MS-7636                                | 1        | 0.54%   |
| Medion MS-7707                             | 1        | 0.54%   |
| Medion MS-7621                             | 1        | 0.54%   |
| Medion Akoya                               | 1        | 0.54%   |
| Lenovo ThinkStation                        | 1        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 18       | 9.73%   |
| 2019 | 17       | 9.19%   |
| 2009 | 16       | 8.65%   |
| 2017 | 15       | 8.11%   |
| 2013 | 13       | 7.03%   |
| 2011 | 13       | 7.03%   |
| 2015 | 11       | 5.95%   |
| 2020 | 9        | 4.86%   |
| 2014 | 9        | 4.86%   |
| 2022 | 8        | 4.32%   |
| 2016 | 8        | 4.32%   |
| 2012 | 8        | 4.32%   |
| 2010 | 8        | 4.32%   |
| 2008 | 8        | 4.32%   |
| 2023 | 7        | 3.78%   |
| 2021 | 7        | 3.78%   |
| 2007 | 5        | 2.7%    |
| 2006 | 4        | 2.16%   |
| 2024 | 1        | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 185      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 181      | 97.31%  |
| Enabled  | 5        | 2.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 185      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 46       | 24.47%  |
| 8.01-16.0   | 37       | 19.68%  |
| 32.01-64.0  | 31       | 16.49%  |
| 3.01-4.0    | 26       | 13.83%  |
| 4.01-8.0    | 21       | 11.17%  |
| 64.01-256.0 | 12       | 6.38%   |
| 24.01-32.0  | 7        | 3.72%   |
| 2.01-3.0    | 5        | 2.66%   |
| 1.01-2.0    | 3        | 1.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 57       | 27.01%  |
| 4.01-8.0   | 47       | 22.27%  |
| 2.01-3.0   | 44       | 20.85%  |
| 3.01-4.0   | 31       | 14.69%  |
| 0.51-1.0   | 11       | 5.21%   |
| 8.01-16.0  | 10       | 4.74%   |
| 0.01-0.5   | 5        | 2.37%   |
| 16.01-24.0 | 4        | 1.9%    |
| 24.01-32.0 | 2        | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 73       | 37.82%  |
| 2      | 57       | 29.53%  |
| 3      | 26       | 13.47%  |
| 4      | 14       | 7.25%   |
| 5      | 8        | 4.15%   |
| 6      | 6        | 3.11%   |
| 8      | 4        | 2.07%   |
| 7      | 3        | 1.55%   |
| 11     | 1        | 0.52%   |
| 0      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 59.04%  |
| Yes       | 77       | 40.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 183      | 98.92%  |
| No        | 2        | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 64.89%  |
| Yes       | 66       | 35.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 138      | 73.8%   |
| Yes       | 49       | 26.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Slovenia | 185      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ljubljana           | 68       | 33.66%  |
| Maribor             | 8        | 3.96%   |
| Vrhnika             | 5        | 2.48%   |
| Koper               | 5        | 2.48%   |
| Celje               | 5        | 2.48%   |
| Kranj               | 4        | 1.98%   |
| Kamnik              | 4        | 1.98%   |
| Grosuplje           | 4        | 1.98%   |
| Sempeter pri Gorici | 3        | 1.49%   |
| Rence               | 3        | 1.49%   |
| Radovljica          | 3        | 1.49%   |
| Novo Mesto          | 3        | 1.49%   |
| Zrece               | 2        | 0.99%   |
| Žalec              | 2        | 0.99%   |
| Trzin               | 2        | 0.99%   |
| Slovenska Bistrica  | 2        | 0.99%   |
| Škofja Loka        | 2        | 0.99%   |
| Ptuj                | 2        | 0.99%   |
| Pragersko           | 2        | 0.99%   |
| Postojna            | 2        | 0.99%   |
| Oplotnica           | 2        | 0.99%   |
| Medvode             | 2        | 0.99%   |
| Logatec             | 2        | 0.99%   |
| Ilirska Bistrica    | 2        | 0.99%   |
| Ig                  | 2        | 0.99%   |
| Grad                | 2        | 0.99%   |
| Domžale            | 2        | 0.99%   |
| Crensovci           | 2        | 0.99%   |
| Ajdovščina        | 2        | 0.99%   |
| Žužemberk         | 1        | 0.5%    |
| Zirovnica           | 1        | 0.5%    |
| Ziri                | 1        | 0.5%    |
| Zgornje Gorje       | 1        | 0.5%    |
| Zgornja Besnica     | 1        | 0.5%    |
| Vuzenica            | 1        | 0.5%    |
| Volcja Draga        | 1        | 0.5%    |
| Vipava              | 1        | 0.5%    |
| Velenje             | 1        | 0.5%    |
| Štore              | 1        | 0.5%    |
| Stari Trg pri Lozu  | 1        | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 80       | 148    | 23.39%  |
| Samsung Electronics         | 55       | 94     | 16.08%  |
| Seagate                     | 36       | 67     | 10.53%  |
| Kingston                    | 25       | 36     | 7.31%   |
| Crucial                     | 24       | 37     | 7.02%   |
| Toshiba                     | 22       | 32     | 6.43%   |
| Sandisk                     | 17       | 21     | 4.97%   |
| Intel                       | 6        | 8      | 1.75%   |
| SPCC                        | 5        | 6      | 1.46%   |
| Hitachi                     | 5        | 5      | 1.46%   |
| Corsair                     | 5        | 6      | 1.46%   |
| Intenso                     | 4        | 7      | 1.17%   |
| A-DATA Technology           | 4        | 6      | 1.17%   |
| Silicon Motion              | 3        | 3      | 0.88%   |
| OCZ                         | 3        | 8      | 0.88%   |
| Micron/Crucial Technology   | 3        | 4      | 0.88%   |
| JMicron Technology          | 3        | 3      | 0.88%   |
| HGST                        | 3        | 3      | 0.88%   |
| Unknown                     | 2        | 5      | 0.58%   |
| Transcend                   | 2        | 3      | 0.58%   |
| PNY                         | 2        | 2      | 0.58%   |
| Phison Electronics          | 2        | 2      | 0.58%   |
| Patriot                     | 2        | 3      | 0.58%   |
| Kingston Technology Company | 2        | 2      | 0.58%   |
| KingDian                    | 2        | 2      | 0.58%   |
| Hewlett-Packard             | 2        | 2      | 0.58%   |
| GOODRAM                     | 2        | 2      | 0.58%   |
| China                       | 2        | 3      | 0.58%   |
| Apacer                      | 2        | 4      | 0.58%   |
| TS512GMT                    | 1        | 5      | 0.29%   |
| TO Exter                    | 1        | 1      | 0.29%   |
| SK hynix                    | 1        | 1      | 0.29%   |
| Realtek                     | 1        | 1      | 0.29%   |
| Phison                      | 1        | 1      | 0.29%   |
| Netac                       | 1        | 1      | 0.29%   |
| Maxtor                      | 1        | 1      | 0.29%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.29%   |
| LITEONIT                    | 1        | 1      | 0.29%   |
| Lexar                       | 1        | 1      | 0.29%   |
| Leven                       | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 11       | 2.66%   |
| Kingston SA400S37240G 240GB SSD                     | 7        | 1.69%   |
| Toshiba DT01ACA100 1TB                              | 6        | 1.45%   |
| Crucial CT240BX500SSD1 240GB                        | 6        | 1.45%   |
| Toshiba HDWD120 2TB                                 | 5        | 1.21%   |
| Samsung SSD 850 EVO 250GB                           | 5        | 1.21%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4        | 0.97%   |
| WDC WD10EARS-00Y5B1 1TB                             | 4        | 0.97%   |
| Toshiba DT01ACA200 2TB                              | 4        | 0.97%   |
| SanDisk SSD PLUS 1000GB                             | 4        | 0.97%   |
| Samsung SSD 980 1TB                                 | 4        | 0.97%   |
| Samsung SSD 860 EVO 500GB                           | 4        | 0.97%   |
| Crucial CT500MX500SSD1 500GB                        | 4        | 0.97%   |
| WDC WD5000AADS-00S9B0 500GB                         | 3        | 0.72%   |
| Samsung SSD 970 EVO Plus 500GB                      | 3        | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3        | 0.72%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 0.72%   |
| Kingston SA400S37480G 480GB SSD                     | 3        | 0.72%   |
| Kingston SA400S37120G 120GB SSD                     | 3        | 0.72%   |
| JMicron Generic 500GB                               | 3        | 0.72%   |
| Crucial CT480BX500SSD1 480GB                        | 3        | 0.72%   |
| Crucial CT1000MX500SSD1 1TB                         | 3        | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 0.48%   |
| WDC WDS500G2B0A 500GB SSD                           | 2        | 0.48%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 2        | 0.48%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 2        | 0.48%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2        | 0.48%   |
| WDC WD5000AACS-00G8B1 500GB                         | 2        | 0.48%   |
| WDC WD40PURZ-85TTDY0 4TB                            | 2        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2        | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB                            | 2        | 0.48%   |
| WDC WD4004FZWX-00GBGB0 4TB                          | 2        | 0.48%   |
| WDC WD3200AAKS-75B3A0 320GB                         | 2        | 0.48%   |
| WDC WD20PURZ-85GU6Y0 2TB                            | 2        | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 2        | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 2        | 0.48%   |
| WDC WD15EARS-00MVWB0 1TB                            | 2        | 0.48%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 2        | 0.48%   |
| WDC WD10EARS-00MVWB0 1TB                            | 2        | 0.48%   |
| WDC WD10EADS-00L5B1 1TB                             | 2        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 129    | 49.31%  |
| Seagate             | 34       | 63     | 23.61%  |
| Toshiba             | 19       | 29     | 13.19%  |
| Hitachi             | 5        | 5      | 3.47%   |
| Samsung Electronics | 4        | 4      | 2.78%   |
| JMicron Technology  | 3        | 3      | 2.08%   |
| HGST                | 3        | 3      | 2.08%   |
| TO Exter            | 1        | 1      | 0.69%   |
| Maxtor              | 1        | 1      | 0.69%   |
| Intenso             | 1        | 1      | 0.69%   |
| Fujitsu             | 1        | 2      | 0.69%   |
| ASMT109x            | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 40     | 18.94%  |
| Kingston            | 22       | 27     | 16.67%  |
| Crucial             | 22       | 34     | 16.67%  |
| WDC                 | 13       | 16     | 9.85%   |
| SanDisk             | 9        | 11     | 6.82%   |
| Intel               | 6        | 8      | 4.55%   |
| SPCC                | 4        | 4      | 3.03%   |
| A-DATA Technology   | 4        | 6      | 3.03%   |
| OCZ                 | 3        | 8      | 2.27%   |
| Corsair             | 3        | 4      | 2.27%   |
| Transcend           | 2        | 3      | 1.52%   |
| Toshiba             | 2        | 2      | 1.52%   |
| PNY                 | 2        | 2      | 1.52%   |
| Patriot             | 2        | 3      | 1.52%   |
| KingDian            | 2        | 2      | 1.52%   |
| GOODRAM             | 2        | 2      | 1.52%   |
| China               | 2        | 3      | 1.52%   |
| Apacer              | 2        | 4      | 1.52%   |
| Netac               | 1        | 1      | 0.76%   |
| LITEONIT            | 1        | 1      | 0.76%   |
| Leven               | 1        | 1      | 0.76%   |
| Intenso             | 1        | 1      | 0.76%   |
| Integral            | 1        | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 112      | 242    | 38.23%  |
| SSD     | 105      | 184    | 35.84%  |
| NVMe    | 68       | 102    | 23.21%  |
| Unknown | 8        | 19     | 2.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 159      | 415    | 64.9%   |
| NVMe | 68       | 101    | 27.76%  |
| SAS  | 18       | 31     | 7.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 120      | 225    | 49.59%  |
| 0.51-1.0   | 70       | 118    | 28.93%  |
| 1.01-2.0   | 29       | 45     | 11.98%  |
| 3.01-4.0   | 12       | 20     | 4.96%   |
| 4.01-10.0  | 6        | 12     | 2.48%   |
| 2.01-3.0   | 3        | 4      | 1.24%   |
| 10.01-20.0 | 2        | 2      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 20%     |
| 251-500        | 31       | 15.12%  |
| 1001-2000      | 29       | 14.15%  |
| 501-1000       | 26       | 12.68%  |
| More than 3000 | 22       | 10.73%  |
| 1-20           | 22       | 10.73%  |
| 2001-3000      | 12       | 5.85%   |
| 51-100         | 10       | 4.88%   |
| Unknown        | 8        | 3.9%    |
| 21-50          | 4        | 1.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 66       | 32.35%  |
| 21-50          | 29       | 14.22%  |
| 51-100         | 28       | 13.73%  |
| 101-250        | 17       | 8.33%   |
| 251-500        | 14       | 6.86%   |
| 1001-2000      | 13       | 6.37%   |
| 501-1000       | 13       | 6.37%   |
| 2001-3000      | 9        | 4.41%   |
| Unknown        | 8        | 3.92%   |
| More than 3000 | 7        | 3.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB                 | 2        | 3      | 5.56%   |
| Seagate ST2000DM001-1CH164 2TB           | 2        | 3      | 5.56%   |
| SanDisk SSD PLUS 1000GB                  | 2        | 2      | 5.56%   |
| WDC WDS480G2G0A-00JH30 480GB SSD         | 1        | 1      | 2.78%   |
| WDC WD800BD-22LRA0 80GB                  | 1        | 1      | 2.78%   |
| WDC WD5000AADS-00S9B0 500GB              | 1        | 2      | 2.78%   |
| WDC WD40EZRX-00SPEB0 4TB                 | 1        | 1      | 2.78%   |
| WDC WD40EFRX-68N32N0 4TB                 | 1        | 1      | 2.78%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 2.78%   |
| WDC WD2500AAJS-08L7A0 250GB              | 1        | 1      | 2.78%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1        | 1      | 2.78%   |
| Toshiba Q300. 240GB SSD                  | 1        | 1      | 2.78%   |
| Toshiba DT01ACA300 3TB                   | 1        | 1      | 2.78%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 2.78%   |
| Seagate ST3500320NS 500GB                | 1        | 1      | 2.78%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2.78%   |
| Seagate ST3200822AS 200GB                | 1        | 1      | 2.78%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 3      | 2.78%   |
| SanDisk SSD PLUS 480GB                   | 1        | 2      | 2.78%   |
| SanDisk SSD PLUS 240GB                   | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 980 1TB          | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 970 EVO 1TB      | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 850 EVO 250GB    | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 2.78%   |
| Samsung Electronics HD103UJ 1TB          | 1        | 1      | 2.78%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 2      | 2.78%   |
| Kingston SA400S37240G 240GB SSD          | 1        | 1      | 2.78%   |
| Intel SSDSCKKW240H6 240GB                | 1        | 1      | 2.78%   |
| Intel SSDSA2M160G2GC 160GB               | 1        | 1      | 2.78%   |
| HGST HTS541075A9E680 752GB               | 1        | 1      | 2.78%   |
| HGST HTS541010A9E680 1TB                 | 1        | 1      | 2.78%   |
| Hewlett-Packard SSD EX900 500GB          | 1        | 1      | 2.78%   |
| Crucial M4-CT128M4SSD2 128GB             | 1        | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 12     | 27.27%  |
| Seagate             | 5        | 10     | 15.15%  |
| Samsung Electronics | 5        | 5      | 15.15%  |
| SanDisk             | 4        | 5      | 12.12%  |
| Toshiba             | 2        | 2      | 6.06%   |
| Intel               | 2        | 2      | 6.06%   |
| HGST                | 2        | 2      | 6.06%   |
| OCZ                 | 1        | 2      | 3.03%   |
| Kingston            | 1        | 1      | 3.03%   |
| Hewlett-Packard     | 1        | 1      | 3.03%   |
| Crucial             | 1        | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 47.06%  |
| Seagate             | 5        | 10     | 29.41%  |
| HGST                | 2        | 2      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 25     | 48.28%  |
| SSD  | 12       | 15     | 41.38%  |
| NVMe | 3        | 3      | 10.34%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| SPCC   | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 102      | 245    | 47%     |
| Works    | 87       | 258    | 40.09%  |
| Malfunc  | 27       | 43     | 12.44%  |
| Failed   | 1        | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 119      | 41.9%   |
| AMD                           | 62       | 21.83%  |
| Samsung Electronics           | 35       | 12.32%  |
| Sandisk                       | 11       | 3.87%   |
| JMicron Technology            | 8        | 2.82%   |
| Kingston Technology Company   | 7        | 2.46%   |
| ASMedia Technology            | 7        | 2.46%   |
| Silicon Motion                | 6        | 2.11%   |
| Phison Electronics            | 6        | 2.11%   |
| Micron/Crucial Technology     | 4        | 1.41%   |
| Marvell Technology Group      | 4        | 1.41%   |
| Nvidia                        | 3        | 1.06%   |
| LSI Logic / Symbios Logic     | 2        | 0.7%    |
| Toshiba America Info Systems  | 1        | 0.35%   |
| SK hynix                      | 1        | 0.35%   |
| Silicon Image                 | 1        | 0.35%   |
| Shenzhen Longsys Electronics  | 1        | 0.35%   |
| Seagate Technology            | 1        | 0.35%   |
| OCZ Technology Group          | 1        | 0.35%   |
| Micron Technology             | 1        | 0.35%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.35%   |
| KIOXIA                        | 1        | 0.35%   |
| Integrated Technology Express | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36       | 10.11%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21       | 5.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 17       | 4.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 3.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.81%   |
| AMD 600 Series Chipset SATA Controller                                                  | 10       | 2.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.97%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 1.97%   |
| Intel SATA Controller [RAID Mode]                                                       | 6        | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 1.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.4%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.4%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 1.4%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.4%    |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.4%    |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 4        | 1.12%   |
| JMicron JMB368 IDE controller                                                           | 4        | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.12%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.12%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.12%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 4        | 1.12%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3        | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.84%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 2        | 0.56%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 2        | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.56%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 145      | 53.11%  |
| NVMe | 68       | 24.91%  |
| IDE  | 45       | 16.48%  |
| RAID | 10       | 3.66%   |
| SAS  | 3        | 1.1%    |
| SCSI | 2        | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 121      | 65.41%  |
| AMD    | 64       | 34.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor     | 5        | 2.7%    |
| AMD Ryzen 9 7950X 16-Core Processor    | 4        | 2.16%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 2.16%   |
| AMD Ryzen 5 3600 6-Core Processor      | 4        | 2.16%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 3        | 1.62%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 3        | 1.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 3        | 1.62%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 3        | 1.62%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 3        | 1.62%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 1.62%   |
| AMD Ryzen 5 1600X Six-Core Processor   | 3        | 1.62%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 3        | 1.62%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.08%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 2        | 1.08%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 2        | 1.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 2        | 1.08%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 2        | 1.08%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 2        | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 1.08%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 2        | 1.08%   |
| Intel Core i5 CPU 760 @ 2.80GHz        | 2        | 1.08%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 2        | 1.08%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 2        | 1.08%   |
| Intel Core i3-4330 CPU @ 3.50GHz       | 2        | 1.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 2        | 1.08%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz   | 2        | 1.08%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 2        | 1.08%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 2        | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 2        | 1.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 1.08%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 1.08%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 2        | 1.08%   |
| AMD Phenom II X6 1055T Processor       | 2        | 1.08%   |
| Intel Xeon CPU X5365 @ 3.00GHz         | 1        | 0.54%   |
| Intel Xeon CPU W3565 @ 3.20GHz         | 1        | 0.54%   |
| Intel Xeon CPU W3540 @ 2.93GHz         | 1        | 0.54%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 1        | 0.54%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz     | 1        | 0.54%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz    | 1        | 0.54%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz    | 1        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 40       | 21.62%  |
| AMD Ryzen 5             | 24       | 12.97%  |
| Intel Core i7           | 17       | 9.19%   |
| AMD Ryzen 9             | 12       | 6.49%   |
| AMD Ryzen 7             | 12       | 6.49%   |
| Intel Xeon              | 11       | 5.95%   |
| Intel Core i3           | 10       | 5.41%   |
| Intel Core 2 Duo        | 10       | 5.41%   |
| Other                   | 9        | 4.86%   |
| Intel Celeron           | 5        | 2.7%    |
| Intel Pentium           | 4        | 2.16%   |
| Intel Core 2 Quad       | 4        | 2.16%   |
| Intel Core 2            | 4        | 2.16%   |
| Intel Pentium Dual-Core | 3        | 1.62%   |
| AMD Ryzen 3             | 3        | 1.62%   |
| Intel Atom              | 2        | 1.08%   |
| AMD Phenom II X6        | 2        | 1.08%   |
| AMD FX                  | 2        | 1.08%   |
| AMD A10                 | 2        | 1.08%   |
| Intel Pentium D         | 1        | 0.54%   |
| Intel Core i9           | 1        | 0.54%   |
| AMD Ryzen 3 PRO         | 1        | 0.54%   |
| AMD Phenom II X4        | 1        | 0.54%   |
| AMD E                   | 1        | 0.54%   |
| AMD Athlon X4           | 1        | 0.54%   |
| AMD Athlon II X4        | 1        | 0.54%   |
| AMD Athlon II X2        | 1        | 0.54%   |
| AMD Athlon 64 X2        | 1        | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 69       | 37.3%   |
| 6      | 42       | 22.7%   |
| 2      | 40       | 21.62%  |
| 8      | 18       | 9.73%   |
| 16     | 6        | 3.24%   |
| 12     | 6        | 3.24%   |
| 14     | 2        | 1.08%   |
| 1      | 2        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 184      | 99.46%  |
| 2      | 1        | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 102      | 55.14%  |
| 1      | 83       | 44.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 182      | 97.85%  |
| Unknown        | 3        | 1.61%   |
| 32-bit         | 1        | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 35.68%  |
| 0x906ea    | 9        | 4.52%   |
| 0x506e3    | 9        | 4.52%   |
| 0x306c3    | 8        | 4.02%   |
| 0x906e9    | 6        | 3.02%   |
| 0x306a9    | 6        | 3.02%   |
| 0x206a7    | 6        | 3.02%   |
| 0x0a201016 | 6        | 3.02%   |
| 0x1067a    | 5        | 2.51%   |
| 0x106e5    | 4        | 2.01%   |
| 0x10676    | 4        | 2.01%   |
| 0x0800820d | 4        | 2.01%   |
| 0x6fb      | 3        | 1.51%   |
| 0x106a5    | 3        | 1.51%   |
| 0x0a201009 | 3        | 1.51%   |
| 0x08108109 | 3        | 1.51%   |
| 0x08001138 | 3        | 1.51%   |
| 0xa0671    | 2        | 1.01%   |
| 0x906ed    | 2        | 1.01%   |
| 0x20655    | 2        | 1.01%   |
| 0x106c2    | 2        | 1.01%   |
| 0x0a20120a | 2        | 1.01%   |
| 0x08701021 | 2        | 1.01%   |
| 0x08001137 | 2        | 1.01%   |
| 0x010000dc | 2        | 1.01%   |
| 0xf47      | 1        | 0.5%    |
| 0xa0655    | 1        | 0.5%    |
| 0x906eb    | 1        | 0.5%    |
| 0x6fd      | 1        | 0.5%    |
| 0x6f7      | 1        | 0.5%    |
| 0x6f6      | 1        | 0.5%    |
| 0x6f2      | 1        | 0.5%    |
| 0x406f1    | 1        | 0.5%    |
| 0x306e4    | 1        | 0.5%    |
| 0x30678    | 1        | 0.5%    |
| 0x206d7    | 1        | 0.5%    |
| 0x20652    | 1        | 0.5%    |
| 0x0a601203 | 1        | 0.5%    |
| 0x0a601201 | 1        | 0.5%    |
| 0x0a50000c | 1        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 20       | 10.81%  |
| Zen 3            | 16       | 8.65%   |
| Haswell          | 16       | 8.65%   |
| Unknown          | 15       | 8.11%   |
| Penryn           | 13       | 7.03%   |
| IvyBridge        | 12       | 6.49%   |
| SandyBridge      | 11       | 5.95%   |
| Zen+             | 10       | 5.41%   |
| Skylake          | 10       | 5.41%   |
| Core             | 10       | 5.41%   |
| Zen              | 9        | 4.86%   |
| Nehalem          | 8        | 4.32%   |
| Zen 2            | 7        | 3.78%   |
| K10              | 5        | 2.7%    |
| Westmere         | 3        | 1.62%   |
| Piledriver       | 3        | 1.62%   |
| Icelake          | 3        | 1.62%   |
| Silvermont       | 2        | 1.08%   |
| Broadwell        | 2        | 1.08%   |
| Bonnell          | 2        | 1.08%   |
| Alderlake Hybrid | 2        | 1.08%   |
| Steamroller      | 1        | 0.54%   |
| NetBurst         | 1        | 0.54%   |
| K8 Hammer        | 1        | 0.54%   |
| Gracemont        | 1        | 0.54%   |
| Excavator        | 1        | 0.54%   |
| CometLake        | 1        | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 80       | 39.8%   |
| AMD    | 69       | 34.33%  |
| Intel  | 52       | 25.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 8.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.88%   |
| AMD Raphael                                                                 | 6        | 2.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.4%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.92%   |
| Intel HD Graphics 630                                                       | 4        | 1.92%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 4        | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.92%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 1.92%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.44%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.44%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.44%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 1.44%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 3        | 1.44%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.44%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 3        | 1.44%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.96%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.96%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.96%   |
| Nvidia GK107GL [Quadro K2000]                                               | 2        | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 0.96%   |
| Nvidia G98M [GeForce 9300M GS]                                              | 2        | 0.96%   |
| Intel HD Graphics 530                                                       | 2        | 0.96%   |
| Intel HD Graphics 510                                                       | 2        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 0.96%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 2        | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.96%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.96%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 0.96%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 0.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 71       | 37.77%  |
| 1 x AMD        | 56       | 29.79%  |
| 1 x Intel      | 45       | 23.94%  |
| 2 x AMD        | 7        | 3.72%   |
| AMD + Nvidia   | 6        | 3.19%   |
| Intel + Nvidia | 3        | 1.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 139      | 72.02%  |
| Proprietary | 42       | 21.76%  |
| Unknown     | 12       | 6.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 88       | 45.36%  |
| 1.01-2.0   | 23       | 11.86%  |
| 7.01-8.0   | 17       | 8.76%   |
| 0.51-1.0   | 16       | 8.25%   |
| 0.01-0.5   | 16       | 8.25%   |
| 3.01-4.0   | 11       | 5.67%   |
| 8.01-16.0  | 11       | 5.67%   |
| 5.01-6.0   | 9        | 4.64%   |
| 2.01-3.0   | 2        | 1.03%   |
| 4.01-5.0   | 1        | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 46       | 21.6%   |
| Dell                 | 36       | 16.9%   |
| AOC                  | 33       | 15.49%  |
| Goldstar             | 24       | 11.27%  |
| Philips              | 16       | 7.51%   |
| Hewlett-Packard      | 10       | 4.69%   |
| Ancor Communications | 7        | 3.29%   |
| Acer                 | 6        | 2.82%   |
| Unknown              | 4        | 1.88%   |
| Lenovo               | 4        | 1.88%   |
| Iiyama               | 3        | 1.41%   |
| ASUSTek Computer     | 3        | 1.41%   |
| ViewSonic            | 2        | 0.94%   |
| Sony                 | 2        | 0.94%   |
| BenQ                 | 2        | 0.94%   |
| Vestel Elektronik    | 1        | 0.47%   |
| SKY                  | 1        | 0.47%   |
| RS                   | 1        | 0.47%   |
| NEC Computers        | 1        | 0.47%   |
| Marantz              | 1        | 0.47%   |
| LG Display           | 1        | 0.47%   |
| HVR                  | 1        | 0.47%   |
| HannStar             | 1        | 0.47%   |
| Grundig              | 1        | 0.47%   |
| FUN                  | 1        | 0.47%   |
| Elo Touch            | 1        | 0.47%   |
| Eizo                 | 1        | 0.47%   |
| DIF                  | 1        | 0.47%   |
| DENON                | 1        | 0.47%   |
| Arnos Instruments    | 1        | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3        | 1.29%   |
| Philips LCD Monitor FTV 1920x1080                                     | 3        | 1.29%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 3        | 1.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 3        | 1.29%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 3        | 1.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3        | 1.29%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3        | 1.29%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 3        | 1.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.86%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 376x301mm 19.0-inch  | 2        | 0.86%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch  | 2        | 0.86%   |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                      | 2        | 0.86%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2        | 0.86%   |
| Philips PHL 226V6 PHLC11D 1920x1080 480x270mm 21.7-inch               | 2        | 0.86%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 2        | 0.86%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 2        | 0.86%   |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                     | 2        | 0.86%   |
| AOC Q32E2WG5B AOC3202 2560x1440 698x393mm 31.5-inch                   | 2        | 0.86%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 2        | 0.86%   |
| AOC LCD Monitor AG251FWG2 1920x1080                                   | 2        | 0.86%   |
| AOC AG251F1WG2 AOC2510 1920x1080 544x303mm 24.5-inch                  | 2        | 0.86%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 2        | 0.86%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch             | 1        | 0.43%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 1        | 0.43%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1        | 0.43%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                  | 1        | 0.43%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.43%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1        | 0.43%   |
| SKY TV MONITOR SKY0030 3840x2160 708x398mm 32.0-inch                  | 1        | 0.43%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 0.43%   |
| Samsung Electronics T27C350 SAM0AC5 1920x1080 598x336mm 27.0-inch     | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM05EC 1920x1080 597x336mm 27.0-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM04DE 1920x1080 477x268mm 21.5-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                      | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch  | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 82       | 39.61%  |
| 3840x2160 (4K)     | 29       | 14.01%  |
| 2560x1440 (QHD)    | 28       | 13.53%  |
| 1280x1024 (SXGA)   | 16       | 7.73%   |
| 1680x1050 (WSXGA+) | 13       | 6.28%   |
| 1920x1200 (WUXGA)  | 9        | 4.35%   |
| 3440x1440          | 5        | 2.42%   |
| 2560x1080          | 4        | 1.93%   |
| 2288x1287          | 3        | 1.45%   |
| 1600x900 (HD+)     | 3        | 1.45%   |
| 1440x900 (WXGA+)   | 3        | 1.45%   |
| 1366x768 (WXGA)    | 2        | 0.97%   |
| 1024x768 (XGA)     | 2        | 0.97%   |
| 3840x1600          | 1        | 0.48%   |
| 3840x1080          | 1        | 0.48%   |
| 2560x1600          | 1        | 0.48%   |
| 2560x1024          | 1        | 0.48%   |
| 2160x1200          | 1        | 0.48%   |
| 1280x960           | 1        | 0.48%   |
| 1280x720 (HD)      | 1        | 0.48%   |
| Unknown            | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 34       | 15.74%  |
| 27      | 32       | 14.81%  |
| 23      | 23       | 10.65%  |
| 21      | 19       | 8.8%    |
| Unknown | 16       | 7.41%   |
| 19      | 14       | 6.48%   |
| 31      | 12       | 5.56%   |
| 34      | 9        | 4.17%   |
| 22      | 7        | 3.24%   |
| 20      | 7        | 3.24%   |
| 17      | 6        | 2.78%   |
| 84      | 4        | 1.85%   |
| 65      | 4        | 1.85%   |
| 54      | 4        | 1.85%   |
| 142     | 3        | 1.39%   |
| 72      | 3        | 1.39%   |
| 25      | 3        | 1.39%   |
| 33      | 2        | 0.93%   |
| 32      | 2        | 0.93%   |
| 18      | 2        | 0.93%   |
| 15      | 2        | 0.93%   |
| 64      | 1        | 0.46%   |
| 55      | 1        | 0.46%   |
| 49      | 1        | 0.46%   |
| 37      | 1        | 0.46%   |
| 29      | 1        | 0.46%   |
| 28      | 1        | 0.46%   |
| 26      | 1        | 0.46%   |
| 5       | 1        | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 78       | 37.86%  |
| 401-500        | 35       | 16.99%  |
| 601-700        | 21       | 10.19%  |
| Unknown        | 16       | 7.77%   |
| 351-400        | 14       | 6.8%    |
| 701-800        | 13       | 6.31%   |
| 1001-1500      | 10       | 4.85%   |
| 301-350        | 7        | 3.4%    |
| 1501-2000      | 7        | 3.4%    |
| More than 2000 | 3        | 1.46%   |
| 801-900        | 1        | 0.49%   |
| 101-200        | 1        | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 119      | 61.34%  |
| 16/10   | 25       | 12.89%  |
| 5/4     | 18       | 9.28%   |
| Unknown | 13       | 6.7%    |
| 21/9    | 10       | 5.15%   |
| 4/3     | 4        | 2.06%   |
| 1.00    | 3        | 1.55%   |
| 32/9    | 1        | 0.52%   |
| 3/2     | 1        | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 59       | 27.83%  |
| 301-350        | 32       | 15.09%  |
| 351-500        | 27       | 12.74%  |
| 151-200        | 26       | 12.26%  |
| 251-300        | 21       | 9.91%   |
| More than 1000 | 19       | 8.96%   |
| Unknown        | 16       | 7.55%   |
| 141-150        | 6        | 2.83%   |
| 101-110        | 2        | 0.94%   |
| 501-1000       | 2        | 0.94%   |
| 1-40           | 1        | 0.47%   |
| 121-130        | 1        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 113      | 57.65%  |
| 101-120       | 37       | 18.88%  |
| Unknown       | 16       | 8.16%   |
| 1-50          | 14       | 7.14%   |
| 121-160       | 13       | 6.63%   |
| 161-240       | 2        | 1.02%   |
| More than 240 | 1        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 141      | 74.21%  |
| 2     | 35       | 18.42%  |
| 0     | 8        | 4.21%   |
| 3     | 4        | 2.11%   |
| 6     | 1        | 0.53%   |
| 4     | 1        | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 111      | 44.76%  |
| Intel                             | 78       | 31.45%  |
| Qualcomm Atheros                  | 10       | 4.03%   |
| ASUSTek Computer                  | 7        | 2.82%   |
| Broadcom                          | 6        | 2.42%   |
| TP-Link                           | 4        | 1.61%   |
| Ralink Technology                 | 4        | 1.61%   |
| Ralink                            | 4        | 1.61%   |
| Qualcomm Atheros Communications   | 2        | 0.81%   |
| Nvidia                            | 2        | 0.81%   |
| MediaTek                          | 2        | 0.81%   |
| Marvell Technology Group          | 2        | 0.81%   |
| Linksys                           | 2        | 0.81%   |
| Edimax Technology                 | 2        | 0.81%   |
| ZyDAS Technology                  | 1        | 0.4%    |
| ZyDAS                             | 1        | 0.4%    |
| Xiaomi                            | 1        | 0.4%    |
| VIA Technologies                  | 1        | 0.4%    |
| Sundance Technology Inc / IC Plus | 1        | 0.4%    |
| Samsung Electronics               | 1        | 0.4%    |
| Mellanox Technologies             | 1        | 0.4%    |
| IMC Networks                      | 1        | 0.4%    |
| D-Link System                     | 1        | 0.4%    |
| D-Link                            | 1        | 0.4%    |
| Compal Electronics                | 1        | 0.4%    |
| Belkin Components                 | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 88       | 32.35%  |
| Realtek RTL8125 2.5GbE Controller                                      | 15       | 5.51%   |
| Intel I211 Gigabit Network Connection                                  | 13       | 4.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 11       | 4.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7        | 2.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 1.47%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.47%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.1%    |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.74%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 2        | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 0.74%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2        | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.74%   |
| Intel Wireless 7260                                                    | 2        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 0.74%   |
| Intel Ethernet Controller I226-V                                       | 2        | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.74%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.74%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 0.74%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                  | 2        | 0.74%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter           | 2        | 0.74%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                    | 2        | 0.74%   |
| ZyDAS ZD1211 802.11g                                                   | 1        | 0.37%   |
| ZyDAS ZD1212B Wireless Adapter                                         | 1        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.37%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 15       | 22.06%  |
| Intel                           | 14       | 20.59%  |
| ASUSTek Computer                | 7        | 10.29%  |
| Qualcomm Atheros                | 5        | 7.35%   |
| TP-Link                         | 4        | 5.88%   |
| Ralink Technology               | 4        | 5.88%   |
| Ralink                          | 4        | 5.88%   |
| Qualcomm Atheros Communications | 2        | 2.94%   |
| MediaTek                        | 2        | 2.94%   |
| Edimax Technology               | 2        | 2.94%   |
| Broadcom                        | 2        | 2.94%   |
| ZyDAS Technology                | 1        | 1.47%   |
| ZyDAS                           | 1        | 1.47%   |
| Linksys                         | 1        | 1.47%   |
| IMC Networks                    | 1        | 1.47%   |
| D-Link System                   | 1        | 1.47%   |
| D-Link                          | 1        | 1.47%   |
| Belkin Components               | 1        | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 5.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 2.9%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 2        | 2.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2        | 2.9%    |
| Ralink MT7601U Wireless Adapter                                        | 2        | 2.9%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 2.9%    |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 2.9%    |
| Intel Wireless 7260                                                    | 2        | 2.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 2.9%    |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter           | 2        | 2.9%    |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                    | 2        | 2.9%    |
| ZyDAS ZD1211 802.11g                                                   | 1        | 1.45%   |
| ZyDAS ZD1212B Wireless Adapter                                         | 1        | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 1.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 1.45%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 1.45%   |
| TP-Link 802.11ac NIC                                                   | 1        | 1.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 1.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 1.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 1.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1        | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 1.45%   |
| Realtek RTL8187 Wireless Adapter                                       | 1        | 1.45%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 1.45%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1        | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 1.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 1.45%   |
| Qualcomm Atheros AR5513 802.11abg Wireless NIC                         | 1        | 1.45%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 1.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 1.45%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]          | 1        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1        | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 108      | 54.55%  |
| Intel                             | 71       | 35.86%  |
| Qualcomm Atheros                  | 5        | 2.53%   |
| Broadcom                          | 4        | 2.02%   |
| Nvidia                            | 2        | 1.01%   |
| Marvell Technology Group          | 2        | 1.01%   |
| Xiaomi                            | 1        | 0.51%   |
| VIA Technologies                  | 1        | 0.51%   |
| Sundance Technology Inc / IC Plus | 1        | 0.51%   |
| Mellanox Technologies             | 1        | 0.51%   |
| Linksys                           | 1        | 0.51%   |
| Compal Electronics                | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 88       | 43.56%  |
| Realtek RTL8125 2.5GbE Controller                                      | 15       | 7.43%   |
| Intel I211 Gigabit Network Connection                                  | 13       | 6.44%   |
| Intel Ethernet Connection (2) I219-V                                   | 11       | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7        | 3.47%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.98%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 1.49%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2        | 0.99%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.99%   |
| Intel Ethernet Controller I226-V                                       | 2        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.99%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.99%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.99%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.99%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.99%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 0.99%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                  | 2        | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.5%    |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.5%    |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                  | 1        | 0.5%    |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1        | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1        | 0.5%    |
| Nvidia MCP79 Ethernet                                                  | 1        | 0.5%    |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.5%    |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1        | 0.5%    |
| Linksys Gigabit Network Adapter                                        | 1        | 0.5%    |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.5%    |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.5%    |
| Intel Ethernet Connection I217-V                                       | 1        | 0.5%    |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.5%    |
| Intel CNVi: Wi-Fi                                                      | 1        | 0.5%    |
| Intel 82583V Gigabit Network Connection                                | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 183      | 73.2%   |
| WiFi     | 66       | 26.4%   |
| Modem    | 1        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 149      | 78.42%  |
| WiFi     | 41       | 21.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 132      | 70.97%  |
| 2     | 43       | 23.12%  |
| 3     | 6        | 3.23%   |
| 4     | 2        | 1.08%   |
| 0     | 2        | 1.08%   |
| 5     | 1        | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 161      | 83.85%  |
| Yes  | 31       | 16.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 16       | 31.37%  |
| Cambridge Silicon Radio    | 10       | 19.61%  |
| ASUSTek Computer           | 8        | 15.69%  |
| Realtek Semiconductor      | 5        | 9.8%    |
| MediaTek                   | 2        | 3.92%   |
| Integrated System Solution | 2        | 3.92%   |
| Hewlett-Packard            | 2        | 3.92%   |
| Edimax Technology          | 2        | 3.92%   |
| TP-Link                    | 1        | 1.96%   |
| Lite-On Technology         | 1        | 1.96%   |
| IMC Networks               | 1        | 1.96%   |
| Apple                      | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 10       | 19.61%  |
| Realtek Bluetooth Radio                               | 5        | 9.8%    |
| Intel AX210 Bluetooth                                 | 5        | 9.8%    |
| Intel AX201 Bluetooth                                 | 4        | 7.84%   |
| Intel AX200 Bluetooth                                 | 3        | 5.88%   |
| ASUS ASUS USB-BT500                                   | 3        | 5.88%   |
| MediaTek Wireless_Device                              | 2        | 3.92%   |
| Intel Bluetooth wireless interface                    | 2        | 3.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 2        | 3.92%   |
| Edimax Bluetooth Adapter                              | 2        | 3.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 3.92%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 1        | 1.96%   |
| Lite-On Bluetooth Device                              | 1        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.96%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.96%   |
| Integrated System Solution Bluetooth Device           | 1        | 1.96%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.96%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 1.96%   |
| ASUS Bluetooth Radio                                  | 1        | 1.96%   |
| ASUS BCM20702A0                                       | 1        | 1.96%   |
| Apple Bluetooth HCI                                   | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 113      | 35.76%  |
| AMD                         | 86       | 27.22%  |
| Nvidia                      | 72       | 22.78%  |
| C-Media Electronics         | 7        | 2.22%   |
| ASUSTek Computer            | 4        | 1.27%   |
| Logitech                    | 3        | 0.95%   |
| KTMicro                     | 2        | 0.63%   |
| Kingston Technology         | 2        | 0.63%   |
| JMTek                       | 2        | 0.63%   |
| Creative Technology         | 2        | 0.63%   |
| BEHRINGER International     | 2        | 0.63%   |
| Yamaha                      | 1        | 0.32%   |
| Weltrend Semiconductor      | 1        | 0.32%   |
| VIA Technologies            | 1        | 0.32%   |
| Textech International       | 1        | 0.32%   |
| Texas Instruments           | 1        | 0.32%   |
| Tenx Technology             | 1        | 0.32%   |
| Syntek                      | 1        | 0.32%   |
| SteelSeries ApS             | 1        | 0.32%   |
| Sony                        | 1        | 0.32%   |
| SAVITECH                    | 1        | 0.32%   |
| Samson Technologies         | 1        | 0.32%   |
| Roland                      | 1        | 0.32%   |
| Razer USA                   | 1        | 0.32%   |
| PreSonus Audio Electronics  | 1        | 0.32%   |
| Nam Tai E&E Products        | 1        | 0.32%   |
| Mackie Designs              | 1        | 0.32%   |
| iCreate Technologies        | 1        | 0.32%   |
| Hewlett-Packard             | 1        | 0.32%   |
| FiiO Electronics Technology | 1        | 0.32%   |
| Creative Labs               | 1        | 0.32%   |
| AKAI Professional M.I.      | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 19       | 5.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 17       | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 4.09%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 15       | 4.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 14       | 3.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 3%      |
| Intel 200 Series PCH HD Audio                                                     | 11       | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 2.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 2.18%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 8        | 2.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 1.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7        | 1.91%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 1.63%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5        | 1.36%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5        | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 1.36%   |
| AMD Navi 31 HDMI/DP Audio                                                         | 5        | 1.36%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 5        | 1.36%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 1.36%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.09%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 1.09%   |
| AMD Navi 10 HDMI Audio                                                            | 4        | 1.09%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 4        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.82%   |
| Nvidia GP102 HDMI Audio Controller                                                | 3        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 0.82%   |
| Nvidia GK106 HDMI Audio Controller                                                | 3        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3        | 0.82%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.82%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 16.13%  |
| Crucial             | 19       | 15.32%  |
| G.Skill             | 18       | 14.52%  |
| Unknown             | 13       | 10.48%  |
| Samsung Electronics | 12       | 9.68%   |
| SK hynix            | 10       | 8.06%   |
| Corsair             | 8        | 6.45%   |
| Micron Technology   | 4        | 3.23%   |
| Team                | 2        | 1.61%   |
| TakeMS              | 2        | 1.61%   |
| Ramaxel Technology  | 2        | 1.61%   |
| Patriot             | 2        | 1.61%   |
| Nanya Technology    | 2        | 1.61%   |
| GOODRAM             | 2        | 1.61%   |
| A-DATA Technology   | 2        | 1.61%   |
| Transcend           | 1        | 0.81%   |
| Swissbit            | 1        | 0.81%   |
| Silicon Power       | 1        | 0.81%   |
| GLOWAY              | 1        | 0.81%   |
| Elpida              | 1        | 0.81%   |
| Unknown             | 1        | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                   | 2        | 1.49%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                        | 2        | 1.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                       | 2        | 1.49%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s                          | 2        | 1.49%   |
| G.Skill RAM F4-3600C18-16GVK 16GB DIMM DDR4 3733MT/s                       | 2        | 1.49%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                        | 2        | 1.49%   |
| Crucial RAM CT8G4DFS8266.M8FD 8192MB DIMM DDR4 3600MT/s                    | 2        | 1.49%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s                    | 2        | 1.49%   |
| A-DATA RAM DDR4 3600 8GB DIMM DDR4 3800MT/s                                | 2        | 1.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                  | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                       | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                                | 1        | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2                                         | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                        | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                                | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                        | 1        | 0.75%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                      | 1        | 0.75%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                           | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                         | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                         | 1        | 0.75%   |
| TakeMS RAM TMS4GB364F081139EM 4096MB DIMM DDR3 1333MT/s                    | 1        | 0.75%   |
| TakeMS RAM TMS4GB364E081139PP 4GB DIMM DDR3 1333MT/s                       | 1        | 0.75%   |
| TakeMS RAM TMS2GB264D081805EV 2048MB DIMM DDR2 800MT/s                     | 1        | 0.75%   |
| Swissbit RAM MEN02G64D2BF2EP-2A 2GB DIMM SDRAM 2048MT/s                    | 1        | 0.75%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                               | 1        | 0.75%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                                 | 1        | 0.75%   |
| SK hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s                            | 1        | 0.75%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s                       | 1        | 0.75%   |
| SK hynix RAM HMT41GR7MFR4C-PB 8GB DIMM DDR3 1600MT/s                       | 1        | 0.75%   |
| SK hynix RAM HMT41GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s                       | 1        | 0.75%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s                       | 1        | 0.75%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                       | 1        | 0.75%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s                       | 1        | 0.75%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s                       | 1        | 0.75%   |
| SK hynix RAM 48594D503131325536344350382D53362020 1024MB DIMM DDR2 800MT/s | 1        | 0.75%   |
| Silicon Power RAM SP004GBLFU240W02 4GB DIMM DDR4 2400MT/s                  | 1        | 0.75%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                               | 1        | 0.75%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                               | 1        | 0.75%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                     | 1        | 0.75%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1867MT/s                        | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 57       | 50.89%  |
| DDR3    | 24       | 21.43%  |
| DDR2    | 10       | 8.93%   |
| DDR5    | 8        | 7.14%   |
| Unknown | 7        | 6.25%   |
| SDRAM   | 5        | 4.46%   |
| DDR     | 1        | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 104      | 93.69%  |
| SODIMM  | 6        | 5.41%   |
| FB-DIMM | 1        | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 42       | 36.84%  |
| 16384 | 19       | 16.67%  |
| 4096  | 19       | 16.67%  |
| 2048  | 19       | 16.67%  |
| 32768 | 9        | 7.89%   |
| 1024  | 5        | 4.39%   |
| 49152 | 1        | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 13       | 10.48%  |
| 1600    | 13       | 10.48%  |
| 1333    | 10       | 8.06%   |
| 2667    | 8        | 6.45%   |
| 3600    | 7        | 5.65%   |
| 2133    | 7        | 5.65%   |
| 2400    | 6        | 4.84%   |
| 800     | 6        | 4.84%   |
| 3800    | 4        | 3.23%   |
| 3000    | 4        | 3.23%   |
| 667     | 4        | 3.23%   |
| 4800    | 3        | 2.42%   |
| 4000    | 3        | 2.42%   |
| 3733    | 3        | 2.42%   |
| 2048    | 3        | 2.42%   |
| 1867    | 3        | 2.42%   |
| 1800    | 3        | 2.42%   |
| 6000    | 2        | 1.61%   |
| 2800    | 2        | 1.61%   |
| 2666    | 2        | 1.61%   |
| 400     | 2        | 1.61%   |
| 49926   | 1        | 0.81%   |
| 6400    | 1        | 0.81%   |
| 5600    | 1        | 0.81%   |
| 5200    | 1        | 0.81%   |
| 4133    | 1        | 0.81%   |
| 3866    | 1        | 0.81%   |
| 3534    | 1        | 0.81%   |
| 3466    | 1        | 0.81%   |
| 3400    | 1        | 0.81%   |
| 3333    | 1        | 0.81%   |
| 2866    | 1        | 0.81%   |
| 1866    | 1        | 0.81%   |
| 1639    | 1        | 0.81%   |
| 1067    | 1        | 0.81%   |
| 1066    | 1        | 0.81%   |
| Unknown | 1        | 0.81%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 3        | 30%     |
| Xerox                 | 1        | 10%     |
| Seiko Epson           | 1        | 10%     |
| Samsung Electronics   | 1        | 10%     |
| Lexmark International | 1        | 10%     |
| Datamax-O'Neil        | 1        | 10%     |
| Canon                 | 1        | 10%     |
| Brother Industries    | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155               | 1        | 10%     |
| Seiko Epson ET-2720 Series               | 1        | 10%     |
| Samsung M2070 Series                     | 1        | 10%     |
| Lexmark International Laser Printer E232 | 1        | 10%     |
| HP DeskJet 4530 series                   | 1        | 10%     |
| HP DeskJet 2620 All-in-One Printer       | 1        | 10%     |
| HP Color LaserJet 2605dn                 | 1        | 10%     |
| Datamax-O'Neil Datamax E-4304            | 1        | 10%     |
| Canon PIXMA MX390 Series                 | 1        | 10%     |
| Brother DCP-L2530DW series               | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 3        | 75%     |
| Acer Peripherals (now BenQ) | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20       | 1        | 25%     |
| Canon CanoScan LiDE 700F                 | 1        | 25%     |
| Canon CanoScan LiDE 220                  | 1        | 25%     |
| Acer Peripherals (now BenQ) Prisa 1240UT | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 10       | 40%     |
| Chicony Electronics                    | 4        | 16%     |
| Sunplus Innovation Technology          | 2        | 8%      |
| Microdia                               | 2        | 8%      |
| Z-Star Microelectronics                | 1        | 4%      |
| Sony Ericsson Mobile Communications AB | 1        | 4%      |
| Sony                                   | 1        | 4%      |
| Samsung Electronics                    | 1        | 4%      |
| Pixart Imaging                         | 1        | 4%      |
| MacroSilicon                           | 1        | 4%      |
| Cubeternet                             | 1        | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech HD Webcam C910                         | 2        | 8%      |
| Logitech HD Pro Webcam C920                     | 2        | 8%      |
| Chicony CNF7042                                 | 2        | 8%      |
| Z-Star Venus USB2.0 Camera                      | 1        | 4%      |
| Sunplus USB Camera                              | 1        | 4%      |
| Sunplus HD 720P webcam                          | 1        | 4%      |
| Sony Ericsson Mobile AB Xperia 10 II - Dual SIM | 1        | 4%      |
| Sony CEVCECM                                    | 1        | 4%      |
| Samsung Galaxy series, misc. (MTP mode)         | 1        | 4%      |
| Pixart Imaging GE 1.3 MP MiniCam Pro            | 1        | 4%      |
| Microdia Webcam Vitade AF                       | 1        | 4%      |
| Microdia Camera                                 | 1        | 4%      |
| MacroSilicon MS210x Video Grabber [EasierCAP]   | 1        | 4%      |
| Logitech Webcam C310                            | 1        | 4%      |
| Logitech Webcam C270                            | 1        | 4%      |
| Logitech Webcam C210                            | 1        | 4%      |
| Logitech Webcam C170                            | 1        | 4%      |
| Logitech Logitech Webcam C925e                  | 1        | 4%      |
| Logitech BRIO Ultra HD Webcam                   | 1        | 4%      |
| Cubeternet GL-UPC822 UVC WebCam                 | 1        | 4%      |
| Chicony WebCam                                  | 1        | 4%      |
| Chicony USB2.0 HD UVC WebCam                    | 1        | 4%      |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| SCM Microsystems uTrust 3512 SAM slot Token | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 155      | 81.58%  |
| 1     | 34       | 17.89%  |
| 2     | 1        | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 19       | 52.78%  |
| Net/wireless          | 6        | 16.67%  |
| Multimedia controller | 5        | 13.89%  |
| Unassigned class      | 3        | 8.33%   |
| Fingerprint reader    | 1        | 2.78%   |
| Chipcard              | 1        | 2.78%   |
| Card reader           | 1        | 2.78%   |

