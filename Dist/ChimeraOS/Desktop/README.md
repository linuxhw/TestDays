ChimeraOS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

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

Total: 147

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Shenzhen M... | DRBAA                       | [fa3ca24355](https://linux-hardware.org/?probe=fa3ca24355) | Dec 07, 2024 |
| Biostar       | H81MLV3                     | [0b38f93635](https://linux-hardware.org/?probe=0b38f93635) | Nov 29, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | [f86e1fe5ee](https://linux-hardware.org/?probe=f86e1fe5ee) | Oct 23, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | [31611b8c3f](https://linux-hardware.org/?probe=31611b8c3f) | Oct 17, 2024 |
| ASRock        | X570 Taichi                 | [e2c762be95](https://linux-hardware.org/?probe=e2c762be95) | Oct 16, 2024 |
| Gigabyte      | A520I AC                    | [c6a5317149](https://linux-hardware.org/?probe=c6a5317149) | Sep 21, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [109404b71a](https://linux-hardware.org/?probe=109404b71a) | Sep 19, 2024 |
| MSI           | B450M PRO-VDH MAX           | [54ce0b3d34](https://linux-hardware.org/?probe=54ce0b3d34) | Sep 16, 2024 |
| ASRock        | A520M-ITX/ac                | [85947c736b](https://linux-hardware.org/?probe=85947c736b) | Jul 29, 2024 |
| ASRock        | 970A-G                      | [7d66332210](https://linux-hardware.org/?probe=7d66332210) | Jul 26, 2024 |
| ASRock        | B450M Pro4                  | [f5ce4a9f35](https://linux-hardware.org/?probe=f5ce4a9f35) | Jul 25, 2024 |
| Intel         | X99-P4 V8.2                 | [b02cd106bf](https://linux-hardware.org/?probe=b02cd106bf) | Jul 05, 2024 |
| MSI           | PRO B650M-B                 | [624bc9d85a](https://linux-hardware.org/?probe=624bc9d85a) | Jun 29, 2024 |
| MSI           | PRO B650M-B                 | [814e12e091](https://linux-hardware.org/?probe=814e12e091) | Jun 29, 2024 |
| ASUSTek       | PRIME Z370-A                | [f24f6c287a](https://linux-hardware.org/?probe=f24f6c287a) | Jun 13, 2024 |
| ASUSTek       | PRIME B450M-A II            | [deab23a295](https://linux-hardware.org/?probe=deab23a295) | Jun 08, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [178ff3ba92](https://linux-hardware.org/?probe=178ff3ba92) | Jun 06, 2024 |
| HP            | 212A                        | [14d0c6a707](https://linux-hardware.org/?probe=14d0c6a707) | Jun 05, 2024 |
| Gigabyte      | A520I AC                    | [f043ddb98c](https://linux-hardware.org/?probe=f043ddb98c) | May 27, 2024 |
| Gigabyte      | A520I AC                    | [d818c81141](https://linux-hardware.org/?probe=d818c81141) | May 23, 2024 |
| HP            | 83E9                        | [0854536f3e](https://linux-hardware.org/?probe=0854536f3e) | May 19, 2024 |
| AZW           | GTR V02                     | [8ecb74cbb8](https://linux-hardware.org/?probe=8ecb74cbb8) | May 19, 2024 |
| Soyo          | SY-Classic B450M            | [e82641ba3c](https://linux-hardware.org/?probe=e82641ba3c) | May 02, 2024 |
| Shenzhen M... | DRFXI                       | [951a976cb0](https://linux-hardware.org/?probe=951a976cb0) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c0a20b5a39](https://linux-hardware.org/?probe=c0a20b5a39) | Apr 14, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [635072047d](https://linux-hardware.org/?probe=635072047d) | Apr 14, 2024 |
| HP            | 1905                        | [64d13b2833](https://linux-hardware.org/?probe=64d13b2833) | Apr 12, 2024 |
| MSI           | B450M PRO-VDH MAX           | [f939a8ab03](https://linux-hardware.org/?probe=f939a8ab03) | Apr 04, 2024 |
| Dell          | 0Y7WYT A00                  | [5843a8bea7](https://linux-hardware.org/?probe=5843a8bea7) | Mar 25, 2024 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [4811d76465](https://linux-hardware.org/?probe=4811d76465) | Mar 18, 2024 |
| ASUSTek       | P8H61-M LE                  | [75db640e66](https://linux-hardware.org/?probe=75db640e66) | Mar 10, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [d9770af085](https://linux-hardware.org/?probe=d9770af085) | Mar 06, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [964e9fc189](https://linux-hardware.org/?probe=964e9fc189) | Mar 06, 2024 |
| HC Technol... | HCAR6000-MI2                | [e84a5cbddb](https://linux-hardware.org/?probe=e84a5cbddb) | Mar 04, 2024 |
| Dell          | 02YYK5 A01                  | [fa518467ad](https://linux-hardware.org/?probe=fa518467ad) | Mar 04, 2024 |
| Gigabyte      | A520I AC                    | [6623b5eb34](https://linux-hardware.org/?probe=6623b5eb34) | Mar 04, 2024 |
| HC Technol... | HCAR5000-MI                 | [4db4f0aa29](https://linux-hardware.org/?probe=4db4f0aa29) | Mar 02, 2024 |
| Gigabyte      | A620I AX                    | [684be66545](https://linux-hardware.org/?probe=684be66545) | Feb 29, 2024 |
| Intel         | DH61WW AAG23116-302         | [eda91e0749](https://linux-hardware.org/?probe=eda91e0749) | Feb 26, 2024 |
| Dell          | 0NKW6Y A02                  | [59a10b16df](https://linux-hardware.org/?probe=59a10b16df) | Feb 17, 2024 |
| Micro Comp... | HX100G                      | [30d14495d2](https://linux-hardware.org/?probe=30d14495d2) | Feb 15, 2024 |
| ASRock        | 970M Pro3                   | [3fdb7d7227](https://linux-hardware.org/?probe=3fdb7d7227) | Feb 12, 2024 |
| HP            | 89D8 SMVB                   | [2130b12c50](https://linux-hardware.org/?probe=2130b12c50) | Feb 09, 2024 |
| Gigabyte      | A520I AC                    | [914c716ebc](https://linux-hardware.org/?probe=914c716ebc) | Feb 05, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [f39c1ef04f](https://linux-hardware.org/?probe=f39c1ef04f) | Jan 27, 2024 |
| Gateway       | IPISB-VR                    | [31d92a1fe6](https://linux-hardware.org/?probe=31d92a1fe6) | Jan 25, 2024 |
| Intel         | H61                         | [d3895696ad](https://linux-hardware.org/?probe=d3895696ad) | Jan 23, 2024 |
| ASUSTek       | AM1M-A                      | [6b24e4acaf](https://linux-hardware.org/?probe=6b24e4acaf) | Jan 22, 2024 |
| ASUSTek       | PRIME X570-PRO              | [0a04043949](https://linux-hardware.org/?probe=0a04043949) | Jan 22, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | [85f96ac567](https://linux-hardware.org/?probe=85f96ac567) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [3885b0cee8](https://linux-hardware.org/?probe=3885b0cee8) | Jan 12, 2024 |
| HP            | 885F A                      | [3050f4d975](https://linux-hardware.org/?probe=3050f4d975) | Jan 05, 2024 |
| HP            | 885F A                      | [7f484d8166](https://linux-hardware.org/?probe=7f484d8166) | Jan 05, 2024 |
| MSI           | Z87-G41 PC Mate             | [36d3fe7f0a](https://linux-hardware.org/?probe=36d3fe7f0a) | Jan 03, 2024 |
| MSI           | PRO B650-P WIFI             | [544a799ce8](https://linux-hardware.org/?probe=544a799ce8) | Jan 02, 2024 |
| ASRock        | Z77 Professional            | [d1d9fce85d](https://linux-hardware.org/?probe=d1d9fce85d) | Jan 01, 2024 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [dffaa09f84](https://linux-hardware.org/?probe=dffaa09f84) | Dec 29, 2023 |
| Dell          | 07WP95 A02                  | [b5d957b7ec](https://linux-hardware.org/?probe=b5d957b7ec) | Dec 12, 2023 |
| Gigabyte      | 970A-DS3P                   | [ea510ad39c](https://linux-hardware.org/?probe=ea510ad39c) | Dec 09, 2023 |
| Gigabyte      | H81M-H                      | [108ddf7f8e](https://linux-hardware.org/?probe=108ddf7f8e) | Dec 07, 2023 |
| Dell          | 07HXY6 A01                  | [37ba613bd3](https://linux-hardware.org/?probe=37ba613bd3) | Dec 01, 2023 |
| Dell          | 0T0MHW A03                  | [91cd726063](https://linux-hardware.org/?probe=91cd726063) | Nov 30, 2023 |
| ASUSTek       | PRIME X370-A                | [491dd5c51b](https://linux-hardware.org/?probe=491dd5c51b) | Nov 28, 2023 |
| Gigabyte      | A520I AC                    | [9672d50090](https://linux-hardware.org/?probe=9672d50090) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [606a157eb4](https://linux-hardware.org/?probe=606a157eb4) | Nov 24, 2023 |
| Dell          | 03KWTV A00                  | [f641738a49](https://linux-hardware.org/?probe=f641738a49) | Nov 23, 2023 |
| ASUSTek       | PRIME B560M-A               | [4048fd2631](https://linux-hardware.org/?probe=4048fd2631) | Nov 22, 2023 |
| Gigabyte      | A520M H                     | [abba035964](https://linux-hardware.org/?probe=abba035964) | Nov 19, 2023 |
| ASRock        | Z87 Extreme4                | [84a46af7ee](https://linux-hardware.org/?probe=84a46af7ee) | Nov 19, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [694b0754fa](https://linux-hardware.org/?probe=694b0754fa) | Nov 18, 2023 |
| Dell          | 0DY62R A01                  | [03f9c7a1f2](https://linux-hardware.org/?probe=03f9c7a1f2) | Nov 17, 2023 |
| HP            | 8464                        | [2eae0556b2](https://linux-hardware.org/?probe=2eae0556b2) | Nov 16, 2023 |
| MSI           | B550-A PRO                  | [10e26870d7](https://linux-hardware.org/?probe=10e26870d7) | Nov 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b15037e662](https://linux-hardware.org/?probe=b15037e662) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| ASRock        | B550M-HDV                   | [6f0980a8f2](https://linux-hardware.org/?probe=6f0980a8f2) | Nov 07, 2023 |
| MSI           | B550-A PRO                  | [3333de3c07](https://linux-hardware.org/?probe=3333de3c07) | Nov 06, 2023 |
| ASRock        | B550M-HDV                   | [e005a7da3a](https://linux-hardware.org/?probe=e005a7da3a) | Nov 06, 2023 |
| Gigabyte      | B450M S2H                   | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [9f47c70860](https://linux-hardware.org/?probe=9f47c70860) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [e073d8c90a](https://linux-hardware.org/?probe=e073d8c90a) | Nov 03, 2023 |
| Gigabyte      | H61M-DS2                    | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| MSI           | B450 GAMING PLUS            | [d7fb2de5a7](https://linux-hardware.org/?probe=d7fb2de5a7) | Oct 30, 2023 |
| ASUSTek       | H110M-A                     | [a58f65d857](https://linux-hardware.org/?probe=a58f65d857) | Oct 27, 2023 |
| ASUSTek       | Z170-A                      | [480f22e1b7](https://linux-hardware.org/?probe=480f22e1b7) | Oct 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [6d454c05e2](https://linux-hardware.org/?probe=6d454c05e2) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [6cc2145e11](https://linux-hardware.org/?probe=6cc2145e11) | Oct 21, 2023 |
| GMKtec        | NucBox K4                   | [b0f8dc54f3](https://linux-hardware.org/?probe=b0f8dc54f3) | Oct 20, 2023 |
| AZW           | SER V1                      | [eca53f2271](https://linux-hardware.org/?probe=eca53f2271) | Oct 18, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [257a13e71a](https://linux-hardware.org/?probe=257a13e71a) | Oct 02, 2023 |
| Gigabyte      | A520I AC                    | [48f4eb15cc](https://linux-hardware.org/?probe=48f4eb15cc) | Oct 02, 2023 |
| ASRock        | A320M-HDV                   | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [27d1633bc3](https://linux-hardware.org/?probe=27d1633bc3) | Sep 11, 2023 |
| HP            | 18E7                        | [1b966d0110](https://linux-hardware.org/?probe=1b966d0110) | Sep 11, 2023 |
| HP            | 89B5 A                      | [4934bfa1a8](https://linux-hardware.org/?probe=4934bfa1a8) | Sep 09, 2023 |
| ASUSTek       | GD30CI                      | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Gigabyte      | Z490 GAMING X AX y.y        | [94a6d62c4b](https://linux-hardware.org/?probe=94a6d62c4b) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | [5afb05e780](https://linux-hardware.org/?probe=5afb05e780) | Aug 27, 2023 |
| ASRock        | B550M-ITX/ac                | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| Dell          | 05YDCW A01                  | [3f3195be63](https://linux-hardware.org/?probe=3f3195be63) | Aug 12, 2023 |
| Dell          | 05YDCW A01                  | [80c27f0ac1](https://linux-hardware.org/?probe=80c27f0ac1) | Aug 12, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b1b6854522](https://linux-hardware.org/?probe=b1b6854522) | Jul 29, 2023 |
| ASRock        | H97M Anniversary            | [f8a02ab68e](https://linux-hardware.org/?probe=f8a02ab68e) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8a41127a9](https://linux-hardware.org/?probe=c8a41127a9) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9186fec300](https://linux-hardware.org/?probe=9186fec300) | Jul 23, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [80e44d8594](https://linux-hardware.org/?probe=80e44d8594) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Acer          | Veriton X6610G              | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| Dell          | 0KC9NP A01                  | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| HP            | 1791                        | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| HP            | 1998                        | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell          | 02YYK5 A01                  | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte      | B450 AORUS M                | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell          | 07HXY6 A01                  | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| Dell          | 0FDY5C A00                  | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| Dell          | 0XHGV1 A00                  | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel         | DB75EN AAG39650-400         | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Gigabyte      | H77M-D3H                    | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| HP            | 1998                        | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP            | 1998                        | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| Gigabyte      | H510M H                     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| Lenovo        | ThinkCentre M70e 0832B1U    | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| ChimeraOS 44-1 | 41       | 32.54%  |
| ChimeraOS 45-1 | 17       | 13.49%  |
| ChimeraOS 45   | 14       | 11.11%  |
| ChimeraOS 43-1 | 11       | 8.73%   |
| ChimeraOS 42   | 8        | 6.35%   |
| ChimeraOS 39   | 7        | 5.56%   |
| ChimeraOS 43   | 6        | 4.76%   |
| ChimeraOS 46-2 | 5        | 3.97%   |
| ChimeraOS 41   | 4        | 3.17%   |
| ChimeraOS 38   | 4        | 3.17%   |
| ChimeraOS 46   | 3        | 2.38%   |
| ChimeraOS 44   | 3        | 2.38%   |
| ChimeraOS 37   | 2        | 1.59%   |
| ChimeraOS      | 1        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ChimeraOS | 124      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.5.6-chos1-chimeraos-1  | 40       | 31.75%  |
| 6.6.10-chos1-chimeraos-2 | 31       | 24.6%   |
| 6.3.9-chimeraos-1        | 17       | 13.49%  |
| 6.1.27-1-lts             | 8        | 6.35%   |
| 6.1.11-arch1-1           | 7        | 5.56%   |
| 6.9.12-chos7-chimeraos-1 | 5        | 3.97%   |
| 6.1.21-1-lts             | 4        | 3.17%   |
| 6.1.1-arch1-1            | 4        | 3.17%   |
| 6.9.9-chos1-chimeraos-1  | 3        | 2.38%   |
| 6.5.3-chos1-chimeraos-1  | 3        | 2.38%   |
| 6.0.8-arch1-1            | 2        | 1.59%   |
| 6.6.6-arch1-1            | 1        | 0.79%   |
| 6.6.56-0-generic         | 1        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5.6   | 40       | 31.75%  |
| 6.6.10  | 31       | 24.6%   |
| 6.3.9   | 17       | 13.49%  |
| 6.1.27  | 8        | 6.35%   |
| 6.1.11  | 7        | 5.56%   |
| 6.9.12  | 5        | 3.97%   |
| 6.1.21  | 4        | 3.17%   |
| 6.1.1   | 4        | 3.17%   |
| 6.9.9   | 3        | 2.38%   |
| 6.5.3   | 3        | 2.38%   |
| 6.0.8   | 2        | 1.59%   |
| 6.6.6   | 1        | 0.79%   |
| 6.6.56  | 1        | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5     | 43       | 34.4%   |
| 6.6     | 33       | 26.4%   |
| 6.1     | 22       | 17.6%   |
| 6.3     | 17       | 13.6%   |
| 6.9     | 8        | 6.4%    |
| 6.0     | 2        | 1.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 124      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 122      | 98.39%  |
| steamos | 1        | 0.81%   |
| Unknown | 1        | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 118      | 95.16%  |
| X11     | 5        | 4.03%   |
| Unknown | 1        | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 124      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 107      | 86.29%  |
| de_DE   | 4        | 3.23%   |
| fr_FR   | 3        | 2.42%   |
| es_ES   | 3        | 2.42%   |
| pt_BR   | 2        | 1.61%   |
| es_AR   | 2        | 1.61%   |
| ja_JP   | 1        | 0.81%   |
| en_GB   | 1        | 0.81%   |
| Unknown | 1        | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 124      | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 123      | 99.19%  |
| Xfs   | 1        | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 123      | 99.19%  |
| GPT     | 1        | 0.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 99.19%  |
| Yes       | 1        | 0.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte Technology                  | 30       | 24.19%  |
| ASUSTek Computer                     | 28       | 22.58%  |
| Dell                                 | 15       | 12.1%   |
| ASRock                               | 12       | 9.68%   |
| Hewlett-Packard                      | 11       | 8.87%   |
| MSI                                  | 9        | 7.26%   |
| Intel                                | 4        | 3.23%   |
| Shenzhen Meigao Electronic Equipment | 2        | 1.61%   |
| HC Technology.                       | 2        | 1.61%   |
| AZW                                  | 2        | 1.61%   |
| Soyo                                 | 1        | 0.81%   |
| Micro Computer (HK) Tech Limited     | 1        | 0.81%   |
| MACHINIST                            | 1        | 0.81%   |
| Lenovo                               | 1        | 0.81%   |
| GMKtec                               | 1        | 0.81%   |
| Gateway                              | 1        | 0.81%   |
| Fujitsu                              | 1        | 0.81%   |
| Biostar                              | 1        | 0.81%   |
| Acer                                 | 1        | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Gigabyte A520I AC                                     | 6        | 4.84%   |
| Gigabyte B550I AORUS PRO AX                           | 5        | 4.03%   |
| Dell OptiPlex 3060                                    | 3        | 2.42%   |
| MSI MS-7A38                                           | 2        | 1.61%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx             | 2        | 1.61%   |
| HP EliteDesk 800 G1 SFF                               | 2        | 1.61%   |
| Dell OptiPlex 7020                                    | 2        | 1.61%   |
| Dell OptiPlex 5055 Ryzen APU                          | 2        | 1.61%   |
| Dell OptiPlex 3070                                    | 2        | 1.61%   |
| ASUS ROG STRIX B550-F GAMING                          | 2        | 1.61%   |
| Soyo SY-Classic B450M                                 | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment Uranus Series    | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment AtomMan G Series | 1        | 0.81%   |
| MSI MS-7E28                                           | 1        | 0.81%   |
| MSI MS-7D78                                           | 1        | 0.81%   |
| MSI MS-7D73                                           | 1        | 0.81%   |
| MSI MS-7C56                                           | 1        | 0.81%   |
| MSI MS-7C02                                           | 1        | 0.81%   |
| MSI MS-7B86                                           | 1        | 0.81%   |
| MSI MS-7850                                           | 1        | 0.81%   |
| Micro (HK) Tech Limited HX100G                        | 1        | 0.81%   |
| MACHINIST X99-RS9 V2.0                                | 1        | 0.81%   |
| Lenovo ThinkCentre M70e 0832B1U                       | 1        | 0.81%   |
| Intel X99-P4 V8.2                                     | 1        | 0.81%   |
| Intel H61                                             | 1        | 0.81%   |
| Intel DH61WW AAG23116-302                             | 1        | 0.81%   |
| Intel DB75EN AAG39650-400                             | 1        | 0.81%   |
| HP Z640 Workstation                                   | 1        | 0.81%   |
| HP Z230 Tower Workstation                             | 1        | 0.81%   |
| HP Z220 SFF Workstation                               | 1        | 0.81%   |
| HP Slim Desktop S01-pF2xxx                            | 1        | 0.81%   |
| HP ProDesk 600 G1 SFF                                 | 1        | 0.81%   |
| HP EliteDesk 705 G4 DM 65W (TAA)                      | 1        | 0.81%   |
| HP EliteDesk 705 G4 DM 35W                            | 1        | 0.81%   |
| HC Technology. HCAR6000-MI2                           | 1        | 0.81%   |
| HC Technology. HCAR5000-MI                            | 1        | 0.81%   |
| GMKtec NucBox K4                                      | 1        | 0.81%   |
| Gigabyte Z790 AORUS MASTER X                          | 1        | 0.81%   |
| Gigabyte Z490 GAMING X AX                             | 1        | 0.81%   |
| Gigabyte X570S AORUS ELITE AX                         | 1        | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Dell OptiPlex                                | 14       | 11.29%  |
| ASUS ROG                                     | 8        | 6.45%   |
| ASUS PRIME                                   | 7        | 5.65%   |
| Gigabyte A520I                               | 6        | 4.84%   |
| Gigabyte B550I                               | 5        | 4.03%   |
| HP EliteDesk                                 | 4        | 3.23%   |
| ASUS TUF                                     | 4        | 3.23%   |
| MSI MS-7A38                                  | 2        | 1.61%   |
| HP Victus                                    | 2        | 1.61%   |
| Gigabyte X570                                | 2        | 1.61%   |
| Gigabyte B450                                | 2        | 1.61%   |
| Soyo SY-Classic                              | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment Uranus  | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment AtomMan | 1        | 0.81%   |
| MSI MS-7E28                                  | 1        | 0.81%   |
| MSI MS-7D78                                  | 1        | 0.81%   |
| MSI MS-7D73                                  | 1        | 0.81%   |
| MSI MS-7C56                                  | 1        | 0.81%   |
| MSI MS-7C02                                  | 1        | 0.81%   |
| MSI MS-7B86                                  | 1        | 0.81%   |
| MSI MS-7850                                  | 1        | 0.81%   |
| Micro (HK) Tech Limited HX100G               | 1        | 0.81%   |
| MACHINIST X99-RS9                            | 1        | 0.81%   |
| Lenovo ThinkCentre                           | 1        | 0.81%   |
| Intel X99-P4                                 | 1        | 0.81%   |
| Intel H61                                    | 1        | 0.81%   |
| Intel DH61WW                                 | 1        | 0.81%   |
| Intel DB75EN                                 | 1        | 0.81%   |
| HP Z640                                      | 1        | 0.81%   |
| HP Z230                                      | 1        | 0.81%   |
| HP Z220                                      | 1        | 0.81%   |
| HP Slim                                      | 1        | 0.81%   |
| HP ProDesk                                   | 1        | 0.81%   |
| HC Technology. HCAR6000-MI2                  | 1        | 0.81%   |
| HC Technology. HCAR5000-MI                   | 1        | 0.81%   |
| GMKtec NucBox                                | 1        | 0.81%   |
| Gigabyte Z790                                | 1        | 0.81%   |
| Gigabyte Z490                                | 1        | 0.81%   |
| Gigabyte X570S                               | 1        | 0.81%   |
| Gigabyte H81M-H                              | 1        | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 23       | 18.55%  |
| 2021 | 15       | 12.1%   |
| 2019 | 13       | 10.48%  |
| 2023 | 10       | 8.06%   |
| 2018 | 9        | 7.26%   |
| 2013 | 9        | 7.26%   |
| 2022 | 8        | 6.45%   |
| 2015 | 8        | 6.45%   |
| 2012 | 7        | 5.65%   |
| 2017 | 6        | 4.84%   |
| 2011 | 5        | 4.03%   |
| 2014 | 4        | 3.23%   |
| 2024 | 3        | 2.42%   |
| 2016 | 3        | 2.42%   |
| 2010 | 1        | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 124      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 124      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 124      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 29.84%  |
| 32.01-64.0  | 35       | 28.23%  |
| 8.01-16.0   | 21       | 16.94%  |
| 4.01-8.0    | 14       | 11.29%  |
| 24.01-32.0  | 11       | 8.87%   |
| 64.01-256.0 | 6        | 4.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 41       | 32.8%   |
| 1.01-2.0   | 31       | 24.8%   |
| 3.01-4.0   | 26       | 20.8%   |
| 4.01-8.0   | 24       | 19.2%   |
| 8.01-16.0  | 2        | 1.6%    |
| 16.01-24.0 | 1        | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 49.21%  |
| 2      | 31       | 24.6%   |
| 3      | 24       | 19.05%  |
| 4      | 5        | 3.97%   |
| 5      | 3        | 2.38%   |
| 6      | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 81.45%  |
| Yes       | 23       | 18.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 124      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 80       | 64.52%  |
| No        | 44       | 35.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 75       | 60.48%  |
| No        | 49       | 39.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 55       | 44.35%  |
| Germany     | 9        | 7.26%   |
| France      | 7        | 5.65%   |
| Brazil      | 6        | 4.84%   |
| Australia   | 6        | 4.84%   |
| UK          | 5        | 4.03%   |
| Russia      | 5        | 4.03%   |
| Canada      | 4        | 3.23%   |
| Poland      | 3        | 2.42%   |
| Turkey      | 2        | 1.61%   |
| Spain       | 2        | 1.61%   |
| Peru        | 2        | 1.61%   |
| Norway      | 2        | 1.61%   |
| Japan       | 2        | 1.61%   |
| Honduras    | 2        | 1.61%   |
| Argentina   | 2        | 1.61%   |
| Vietnam     | 1        | 0.81%   |
| South Korea | 1        | 0.81%   |
| New Zealand | 1        | 0.81%   |
| Netherlands | 1        | 0.81%   |
| Mexico      | 1        | 0.81%   |
| Malaysia    | 1        | 0.81%   |
| Indonesia   | 1        | 0.81%   |
| Iceland     | 1        | 0.81%   |
| Hungary     | 1        | 0.81%   |
| Chile       | 1        | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Tegucigalpa    | 2        | 1.6%    |
| Sydney         | 2        | 1.6%    |
| Sao Paulo      | 2        | 1.6%    |
| Sanford        | 2        | 1.6%    |
| Salvador       | 2        | 1.6%    |
| Melbourne      | 2        | 1.6%    |
| Istanbul       | 2        | 1.6%    |
| Yekaterinburg  | 1        | 0.8%    |
| Yaroslavl      | 1        | 0.8%    |
| Wroclaw        | 1        | 0.8%    |
| Wilmington     | 1        | 0.8%    |
| Wiehl          | 1        | 0.8%    |
| Watsonville    | 1        | 0.8%    |
| Warsaw         | 1        | 0.8%    |
| Volosovo       | 1        | 0.8%    |
| Vincennes      | 1        | 0.8%    |
| Vancouver      | 1        | 0.8%    |
| Valence        | 1        | 0.8%    |
| Umeda          | 1        | 0.8%    |
| Tucson         | 1        | 0.8%    |
| Toronto        | 1        | 0.8%    |
| Theodore       | 1        | 0.8%    |
| The Hague      | 1        | 0.8%    |
| Tampa          | 1        | 0.8%    |
| Sumaré        | 1        | 0.8%    |
| Steyning       | 1        | 0.8%    |
| Shelbyville    | 1        | 0.8%    |
| Severn         | 1        | 0.8%    |
| Seneca         | 1        | 0.8%    |
| Seattle        | 1        | 0.8%    |
| Sarpsborg      | 1        | 0.8%    |
| Santiago       | 1        | 0.8%    |
| San Leandro    | 1        | 0.8%    |
| San Jose       | 1        | 0.8%    |
| San Bernardino | 1        | 0.8%    |
| Salisbury      | 1        | 0.8%    |
| Round Rock     | 1        | 0.8%    |
| Rockford       | 1        | 0.8%    |
| Roanne         | 1        | 0.8%    |
| Rio Rancho     | 1        | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 29       | 42     | 13.68%  |
| Seagate                      | 26       | 31     | 12.26%  |
| WDC                          | 21       | 25     | 9.91%   |
| SanDisk                      | 15       | 18     | 7.08%   |
| Micron/Crucial Technology    | 12       | 12     | 5.66%   |
| Kingston                     | 12       | 12     | 5.66%   |
| SK hynix                     | 8        | 8      | 3.77%   |
| Crucial                      | 8        | 8      | 3.77%   |
| Toshiba                      | 5        | 5      | 2.36%   |
| Realtek Semiconductor        | 5        | 5      | 2.36%   |
| Phison Electronics           | 5        | 5      | 2.36%   |
| Intel                        | 5        | 7      | 2.36%   |
| ADATA Technology             | 5        | 7      | 2.36%   |
| Unknown                      | 4        | 4      | 1.89%   |
| MAXIO Technology (Hangzhou)  | 4        | 4      | 1.89%   |
| Kingston Technology Company  | 4        | 4      | 1.89%   |
| China                        | 4        | 4      | 1.89%   |
| A-DATA Technology            | 4        | 4      | 1.89%   |
| Silicon Motion               | 3        | 3      | 1.42%   |
| PNY                          | 3        | 3      | 1.42%   |
| Team                         | 2        | 2      | 0.94%   |
| SPCC                         | 2        | 2      | 0.94%   |
| Micron Technology            | 2        | 2      | 0.94%   |
| KIOXIA                       | 2        | 2      | 0.94%   |
| Hitachi                      | 2        | 2      | 0.94%   |
| HGST                         | 2        | 2      | 0.94%   |
| Fanxiang                     | 2        | 2      | 0.94%   |
| AMD                          | 2        | 2      | 0.94%   |
| TO Exter                     | 1        | 1      | 0.47%   |
| Timetec                      | 1        | 1      | 0.47%   |
| SSK                          | 1        | 1      | 0.47%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.47%   |
| RZX                          | 1        | 1      | 0.47%   |
| O2 Micro                     | 1        | 1      | 0.47%   |
| Netac                        | 1        | 1      | 0.47%   |
| KingFast                     | 1        | 1      | 0.47%   |
| HS-SSD-E100                  | 1        | 1      | 0.47%   |
| Hewlett-Packard              | 1        | 1      | 0.47%   |
| GALAX                        | 1        | 1      | 0.47%   |
| Corsair                      | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 10       | 4.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 9        | 3.93%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5        | 2.18%   |
| Kingston Company SNV2S1000G 1TB                                   | 4        | 1.75%   |
| Seagate ST500DM002-1BD142 500GB                                   | 3        | 1.31%   |
| Samsung SSD 980 1TB                                               | 3        | 1.31%   |
| Samsung SSD 860 EVO 1TB                                           | 3        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 3        | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 3        | 1.31%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 3        | 1.31%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 2        | 0.87%   |
| WDC WD1600AAJS-00B4A0 160GB                                       | 2        | 0.87%   |
| WDC WD10EZEX-00BN5A0 1TB                                          | 2        | 0.87%   |
| Unknown NVMe SSD Drive 512GB                                      | 2        | 0.87%   |
| Unknown NVMe SSD Drive 2TB                                        | 2        | 0.87%   |
| SPCC Solid State Disk 1024GB                                      | 2        | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 2        | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 2        | 0.87%   |
| Sandisk WD_BLACK SN770 500GB                                      | 2        | 0.87%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 2        | 0.87%   |
| Samsung SSD 870 QVO 2TB                                           | 2        | 0.87%   |
| Samsung SSD 870 EVO 1TB                                           | 2        | 0.87%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB                       | 2        | 0.87%   |
| Phison E12 NVMe Controller 480GB                                  | 2        | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB                | 2        | 0.87%   |
| Kingston SA400S37120G 120GB SSD                                   | 2        | 0.87%   |
| Crucial CT500MX500SSD1 500GB                                      | 2        | 0.87%   |
| Crucial CT240BX500SSD1 240GB                                      | 2        | 0.87%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                                  | 1        | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 1        | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                                  | 1        | 0.44%   |
| WDC WDBNCE5000PNC 500GB SSD                                       | 1        | 0.44%   |
| WDC WD5000BEVT-22A0RT0 500GB                                      | 1        | 0.44%   |
| WDC WD5000AVDS-63U7B1 500GB                                       | 1        | 0.44%   |
| WDC WD5000AAKX-003CA0 500GB                                       | 1        | 0.44%   |
| WDC WD3200BEKT-08PVMT1 320GB                                      | 1        | 0.44%   |
| WDC WD3200AAKS-00L9A0 320GB                                       | 1        | 0.44%   |
| WDC WD3200AAJS-65B4A0 320GB                                       | 1        | 0.44%   |
| WDC WD20EARX-00PASB0 2TB                                          | 1        | 0.44%   |
| WDC WD1500HLFS-01G6U0 150GB                                       | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 30     | 48.15%  |
| WDC                 | 17       | 18     | 31.48%  |
| Toshiba             | 5        | 5      | 9.26%   |
| Hitachi             | 2        | 2      | 3.7%    |
| HGST                | 2        | 2      | 3.7%    |
| TO Exter            | 1        | 1      | 1.85%   |
| Samsung Electronics | 1        | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 18.31%  |
| Kingston            | 8        | 8      | 11.27%  |
| Crucial             | 8        | 8      | 11.27%  |
| SanDisk             | 7        | 7      | 9.86%   |
| WDC                 | 5        | 7      | 7.04%   |
| China               | 4        | 4      | 5.63%   |
| A-DATA Technology   | 4        | 4      | 5.63%   |
| PNY                 | 3        | 3      | 4.23%   |
| Intel               | 3        | 4      | 4.23%   |
| SPCC                | 2        | 2      | 2.82%   |
| SK hynix            | 2        | 2      | 2.82%   |
| Fanxiang            | 2        | 2      | 2.82%   |
| Team                | 1        | 1      | 1.41%   |
| Seagate             | 1        | 1      | 1.41%   |
| RZX                 | 1        | 1      | 1.41%   |
| Netac               | 1        | 1      | 1.41%   |
| Micron Technology   | 1        | 1      | 1.41%   |
| Hewlett-Packard     | 1        | 1      | 1.41%   |
| GALAX               | 1        | 1      | 1.41%   |
| Corsair             | 1        | 1      | 1.41%   |
| ASMedia             | 1        | 1      | 1.41%   |
| AMD                 | 1        | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 78       | 100    | 41.27%  |
| SSD     | 61       | 78     | 32.28%  |
| HDD     | 46       | 59     | 24.34%  |
| Unknown | 4        | 4      | 2.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 85       | 136    | 50.3%   |
| NVMe | 78       | 99     | 46.15%  |
| SAS  | 6        | 6      | 3.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 55       | 73     | 50%     |
| 0.51-1.0   | 31       | 36     | 28.18%  |
| 1.01-2.0   | 17       | 20     | 15.45%  |
| 4.01-10.0  | 3        | 3      | 2.73%   |
| 3.01-4.0   | 2        | 3      | 1.82%   |
| 2.01-3.0   | 1        | 1      | 0.91%   |
| 10.01-20.0 | 1        | 1      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 57       | 45.97%  |
| 1001-2000      | 31       | 25%     |
| 501-1000       | 21       | 16.94%  |
| 2001-3000      | 11       | 8.87%   |
| 251-500        | 3        | 2.42%   |
| 51-100         | 1        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 31       | 24.6%   |
| 501-1000       | 18       | 14.29%  |
| 1001-2000      | 17       | 13.49%  |
| 101-250        | 15       | 11.9%   |
| 51-100         | 15       | 11.9%   |
| 251-500        | 13       | 10.32%  |
| 2001-3000      | 11       | 8.73%   |
| More than 3000 | 6        | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 123      | 240    | 99.19%  |
| Works    | 1        | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 63       | 29.72%  |
| Intel                        | 57       | 26.89%  |
| Samsung Electronics          | 18       | 8.49%   |
| Micron/Crucial Technology    | 12       | 5.66%   |
| SanDisk                      | 9        | 4.25%   |
| Kingston Technology Company  | 8        | 3.77%   |
| SK hynix                     | 6        | 2.83%   |
| Realtek Semiconductor        | 5        | 2.36%   |
| Phison Electronics           | 5        | 2.36%   |
| ADATA Technology             | 5        | 2.36%   |
| MAXIO Technology (Hangzhou)  | 4        | 1.89%   |
| ASMedia Technology           | 4        | 1.89%   |
| Silicon Motion               | 3        | 1.42%   |
| Solidigm                     | 2        | 0.94%   |
| KIOXIA                       | 2        | 0.94%   |
| VIA Technologies             | 1        | 0.47%   |
| TenaFe                       | 1        | 0.47%   |
| Shenzhen Longsys Electronics | 1        | 0.47%   |
| O2 Micro                     | 1        | 0.47%   |
| Micron Technology            | 1        | 0.47%   |
| Marvell Technology Group     | 1        | 0.47%   |
| Hosin Global Electronics     | 1        | 0.47%   |
| Biwin Storage Technology     | 1        | 0.47%   |
| Unknown                      | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 10%     |
| AMD 500 Series Chipset SATA Controller                                                  | 22       | 9.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 5.42%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 10       | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 3.75%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.92%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 2.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.08%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.25%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 3        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.25%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.25%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.25%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                                    | 2        | 0.83%   |
| SK hynix PC611 NVMe Solid State Drive                                                   | 2        | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.83%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 0.83%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.83%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 2        | 0.83%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 2        | 0.83%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 2        | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.83%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 2        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 51.96%  |
| NVMe | 78       | 38.24%  |
| RAID | 12       | 5.88%   |
| IDE  | 8        | 3.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 69       | 55.65%  |
| Intel  | 55       | 44.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 8        | 6.4%    |
| AMD Ryzen 7 5800X 8-Core Processor              | 6        | 4.8%    |
| AMD Ryzen 5 5600X 6-Core Processor              | 6        | 4.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics          | 5        | 4%      |
| Intel Core i7-7700K CPU @ 4.20GHz               | 3        | 2.4%    |
| AMD Ryzen 9 5950X 16-Core Processor             | 3        | 2.4%    |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 3        | 2.4%    |
| AMD Ryzen 5 5500                                | 3        | 2.4%    |
| Intel Core i5-8500 CPU @ 3.00GHz                | 2        | 1.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2        | 1.6%    |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2        | 1.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2        | 1.6%    |
| AMD Ryzen 9 7945HX with Radeon Graphics         | 2        | 1.6%    |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics      | 2        | 1.6%    |
| AMD Ryzen 7 7800X3D 8-Core Processor            | 2        | 1.6%    |
| AMD Ryzen 7 7700X 8-Core Processor              | 2        | 1.6%    |
| AMD Ryzen 7 5800X3D 8-Core Processor            | 2        | 1.6%    |
| AMD Ryzen 5 5600 6-Core Processor               | 2        | 1.6%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 1.6%    |
| AMD Ryzen 5 2600X Six-Core Processor            | 2        | 1.6%    |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz             | 1        | 0.8%    |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz             | 1        | 0.8%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz             | 1        | 0.8%    |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1        | 0.8%    |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz             | 1        | 0.8%    |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz             | 1        | 0.8%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz             | 1        | 0.8%    |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 0.8%    |
| Intel Core i9-14900K                            | 1        | 0.8%    |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 0.8%    |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 0.8%    |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 0.8%    |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 0.8%    |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1        | 0.8%    |
| Intel Core i7-10700K CPU @ 3.80GHz              | 1        | 0.8%    |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1        | 0.8%    |
| Intel Core i5-9500T CPU @ 2.20GHz               | 1        | 0.8%    |
| Intel Core i5-9500 CPU @ 3.00GHz                | 1        | 0.8%    |
| Intel Core i5-8500T CPU @ 2.10GHz               | 1        | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 5       | 33       | 26.4%   |
| Intel Core i5     | 23       | 18.4%   |
| AMD Ryzen 7       | 18       | 14.4%   |
| Intel Core i7     | 11       | 8.8%    |
| AMD Ryzen 9       | 10       | 8%      |
| Intel Xeon        | 7        | 5.6%    |
| Intel Core i3     | 7        | 5.6%    |
| Other             | 3        | 2.4%    |
| AMD Ryzen 5 PRO   | 3        | 2.4%    |
| AMD FX            | 3        | 2.4%    |
| Intel Pentium     | 1        | 0.8%    |
| Intel Core i9     | 1        | 0.8%    |
| Intel Core 2 Quad | 1        | 0.8%    |
| Intel Celeron     | 1        | 0.8%    |
| AMD PRO A10       | 1        | 0.8%    |
| AMD Athlon        | 1        | 0.8%    |
| AMD A10           | 1        | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 40       | 32%     |
| 6      | 39       | 31.2%   |
| 8      | 23       | 18.4%   |
| 2      | 9        | 7.2%    |
| 16     | 6        | 4.8%    |
| 24     | 3        | 2.4%    |
| 12     | 3        | 2.4%    |
| 10     | 1        | 0.8%    |
| 3      | 1        | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 123      | 99.19%  |
| 2      | 1        | 0.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 98       | 79.03%  |
| 1      | 26       | 20.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 124      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 124      | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 28       | 22.58%  |
| Unknown     | 19       | 15.32%  |
| Haswell     | 14       | 11.29%  |
| KabyLake    | 11       | 8.87%   |
| Zen 2       | 10       | 8.06%   |
| CometLake   | 8        | 6.45%   |
| SandyBridge | 7        | 5.65%   |
| IvyBridge   | 6        | 4.84%   |
| Zen+        | 5        | 4.03%   |
| Zen         | 5        | 4.03%   |
| Piledriver  | 4        | 3.23%   |
| Skylake     | 3        | 2.42%   |
| Penryn      | 1        | 0.81%   |
| Jaguar      | 1        | 0.81%   |
| Excavator   | 1        | 0.81%   |
| Broadwell   | 1        | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 77       | 55.8%   |
| Nvidia | 40       | 28.99%  |
| Intel  | 21       | 15.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Raphael                                                                 | 6        | 4.14%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 6        | 4.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 4.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 3.45%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 3.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 2.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.76%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 4        | 2.76%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 4        | 2.76%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4        | 2.76%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 3        | 2.07%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.07%   |
| AMD Phoenix1                                                                | 3        | 2.07%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 3        | 2.07%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 3        | 2.07%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 2.07%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.38%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.38%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.38%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 1.38%   |
| Intel HD Graphics 530                                                       | 2        | 1.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.38%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.38%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2        | 1.38%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]       | 2        | 1.38%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.38%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.38%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.69%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.69%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 66       | 52.8%   |
| 1 x Nvidia     | 34       | 27.2%   |
| 1 x Intel      | 12       | 9.6%    |
| 2 x AMD        | 7        | 5.6%    |
| Intel + Nvidia | 2        | 1.6%    |
| Intel + AMD    | 2        | 1.6%    |
| AMD + Nvidia   | 2        | 1.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 92       | 74.19%  |
| Unknown     | 18       | 14.52%  |
| Proprietary | 14       | 11.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 121      | 97.58%  |
| 3.01-4.0   | 2        | 1.61%   |
| 8.01-16.0  | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 19.8%   |
| Goldstar             | 8        | 7.92%   |
| Hewlett-Packard      | 6        | 5.94%   |
| Dell                 | 6        | 5.94%   |
| Vizio                | 4        | 3.96%   |
| BenQ                 | 4        | 3.96%   |
| Unknown (XXX)        | 3        | 2.97%   |
| Toshiba              | 3        | 2.97%   |
| Sony                 | 3        | 2.97%   |
| Philips              | 3        | 2.97%   |
| Panasonic            | 3        | 2.97%   |
| ASUSTek Computer     | 3        | 2.97%   |
| Ancor Communications | 3        | 2.97%   |
| Sharp                | 2        | 1.98%   |
| SANYO                | 2        | 1.98%   |
| MSI                  | 2        | 1.98%   |
| Insignia             | 2        | 1.98%   |
| Gigabyte Technology  | 2        | 1.98%   |
| DENON                | 2        | 1.98%   |
| AOC                  | 2        | 1.98%   |
| Acer                 | 2        | 1.98%   |
| Xiaomi               | 1        | 0.99%   |
| ViewSonic            | 1        | 0.99%   |
| VIE                  | 1        | 0.99%   |
| STD                  | 1        | 0.99%   |
| SAC                  | 1        | 0.99%   |
| PXO                  | 1        | 0.99%   |
| Onkyo                | 1        | 0.99%   |
| ITE                  | 1        | 0.99%   |
| IPS                  | 1        | 0.99%   |
| HUAWEI               | 1        | 0.99%   |
| Hitachi              | 1        | 0.99%   |
| Gateway              | 1        | 0.99%   |
| Element              | 1        | 0.99%   |
| CGC                  | 1        | 0.99%   |
| CAP                  | 1        | 0.99%   |
| AGO                  | 1        | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch          | 3        | 2.91%   |
| SANYO TV SAN0206 1920x1080                                              | 2        | 1.94%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 2        | 1.94%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 2        | 1.94%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 2        | 1.94%   |
| Xiaomi Mi TV XMD00E2 1920x1080 950x540mm 43.0-inch                      | 1        | 0.97%   |
| Vizio V435-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                     | 1        | 0.97%   |
| Vizio OLED55-H1 VIZ1040 3840x2160 1209x680mm 54.6-inch                  | 1        | 0.97%   |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                     | 1        | 0.97%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                     | 1        | 0.97%   |
| ViewSonic VA2702w VSCE727 1920x1080 598x336mm 27.0-inch                 | 1        | 0.97%   |
| VIE HORIZON Z24 VIE2380 1920x1080 527x296mm 23.8-inch                   | 1        | 0.97%   |
| Toshiba TV TSB2017 3840x2160                                            | 1        | 0.97%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                      | 1        | 0.97%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                       | 1        | 0.97%   |
| STD Monitor STD2023 1920x1080 600x330mm 27.0-inch                       | 1        | 0.97%   |
| Sony TV SNY7502 1920x1080 1018x573mm 46.0-inch                          | 1        | 0.97%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                           | 1        | 0.97%   |
| Sony TV *30 SNY0406 3840x2160 1439x809mm 65.0-inch                      | 1        | 0.97%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1        | 0.97%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                       | 1        | 0.97%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 0.97%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch    | 1        | 0.97%   |
| Samsung Electronics SyncMaster SAM01AC 1600x1200 312x234mm 15.4-inch    | 1        | 0.97%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch     | 1        | 0.97%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1        | 0.97%   |
| Samsung Electronics QCQ90 SAM733F 3840x2160 950x540mm 43.0-inch         | 1        | 0.97%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch  | 1        | 0.97%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                       | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SAM0512 1360x768                        | 1        | 0.97%   |
| Samsung Electronics LCD Monitor SAM020B 1920x540                        | 1        | 0.97%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1        | 0.97%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 697x392mm 31.5-inch       | 1        | 0.97%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 1        | 0.97%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                   | 1        | 0.97%   |
| PXO Pixio PX279P PXO0279 1920x1080 698x393mm 31.5-inch                  | 1        | 0.97%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 44%     |
| 3840x2160 (4K)     | 28       | 28%     |
| 2560x1440 (QHD)    | 9        | 9%      |
| 2560x1080          | 3        | 3%      |
| 1920x540           | 3        | 3%      |
| 1600x900 (HD+)     | 3        | 3%      |
| 1680x1050 (WSXGA+) | 2        | 2%      |
| 3840x2560          | 1        | 1%      |
| 3840x1600          | 1        | 1%      |
| 3840x1080          | 1        | 1%      |
| 3440x1440          | 1        | 1%      |
| 1600x1200          | 1        | 1%      |
| 1440x900 (WXGA+)   | 1        | 1%      |
| 1366x768 (WXGA)    | 1        | 1%      |
| 1280x720 (HD)      | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 24       | 23.76%  |
| 31      | 9        | 8.91%   |
| 84      | 8        | 7.92%   |
| 24      | 8        | 7.92%   |
| 72      | 4        | 3.96%   |
| 54      | 4        | 3.96%   |
| 23      | 4        | 3.96%   |
| Unknown | 4        | 3.96%   |
| 48      | 3        | 2.97%   |
| 46      | 3        | 2.97%   |
| 34      | 3        | 2.97%   |
| 20      | 3        | 2.97%   |
| 65      | 2        | 1.98%   |
| 40      | 2        | 1.98%   |
| 28      | 2        | 1.98%   |
| 22      | 2        | 1.98%   |
| 74      | 1        | 0.99%   |
| 69      | 1        | 0.99%   |
| 64      | 1        | 0.99%   |
| 52      | 1        | 0.99%   |
| 49      | 1        | 0.99%   |
| 47      | 1        | 0.99%   |
| 43      | 1        | 0.99%   |
| 38      | 1        | 0.99%   |
| 37      | 1        | 0.99%   |
| 32      | 1        | 0.99%   |
| 29      | 1        | 0.99%   |
| 21      | 1        | 0.99%   |
| 19      | 1        | 0.99%   |
| 18      | 1        | 0.99%   |
| 15      | 1        | 0.99%   |
| 12      | 1        | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 32.65%  |
| 1001-1500   | 16       | 16.33%  |
| 601-700     | 14       | 14.29%  |
| 1501-2000   | 13       | 13.27%  |
| 401-500     | 8        | 8.16%   |
| 801-900     | 4        | 4.08%   |
| 701-800     | 4        | 4.08%   |
| Unknown     | 4        | 4.08%   |
| 301-350     | 1        | 1.02%   |
| 201-300     | 1        | 1.02%   |
| 901-1000    | 1        | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 80       | 83.33%  |
| 21/9  | 5        | 5.21%   |
| 16/10 | 4        | 4.17%   |
| 32/9  | 3        | 3.13%   |
| 4/3   | 2        | 2.08%   |
| 3/2   | 1        | 1.04%   |
| 1.96  | 1        | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 25       | 25.77%  |
| More than 1000 | 23       | 23.71%  |
| 351-500        | 13       | 13.4%   |
| 201-250        | 13       | 13.4%   |
| 501-1000       | 11       | 11.34%  |
| 151-200        | 4        | 4.12%   |
| Unknown        | 4        | 4.12%   |
| 71-80          | 1        | 1.03%   |
| 251-300        | 1        | 1.03%   |
| 141-150        | 1        | 1.03%   |
| 111-120        | 1        | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 66       | 67.35%  |
| 1-50    | 11       | 11.22%  |
| 101-120 | 8        | 8.16%   |
| 121-160 | 6        | 6.12%   |
| Unknown | 4        | 4.08%   |
| 161-240 | 3        | 3.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 75.81%  |
| 0     | 20       | 16.13%  |
| 2     | 9        | 7.26%   |
| 3     | 1        | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 81       | 43.32%  |
| Intel                      | 60       | 32.09%  |
| MediaTek                   | 9        | 4.81%   |
| Qualcomm Atheros           | 8        | 4.28%   |
| TP-Link                    | 6        | 3.21%   |
| Microsoft                  | 6        | 3.21%   |
| Broadcom                   | 6        | 3.21%   |
| Ralink                     | 2        | 1.07%   |
| Aquantia                   | 2        | 1.07%   |
| ZTE WCDMA Technologies MSM | 1        | 0.53%   |
| Samsung Electronics        | 1        | 0.53%   |
| Ralink Technology          | 1        | 0.53%   |
| Qualcomm Technologies      | 1        | 0.53%   |
| Qualcomm                   | 1        | 0.53%   |
| Marvell Technology Group   | 1        | 0.53%   |
| Edimax Technology          | 1        | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 55       | 24.34%  |
| Realtek RTL8125 2.5GbE Controller                                      | 18       | 7.96%   |
| Intel Wi-Fi 6 AX200                                                    | 10       | 4.42%   |
| Intel Ethernet Controller I225-V                                       | 9        | 3.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7        | 3.1%    |
| Intel I211 Gigabit Network Connection                                  | 7        | 3.1%    |
| Intel Ethernet Connection I217-LM                                      | 7        | 3.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6        | 2.65%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 5        | 2.21%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 5        | 2.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 2.21%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 4        | 1.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 4        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 1.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 1.77%   |
| Intel Ethernet Controller I226-V                                       | 4        | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 3        | 1.33%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 1.33%   |
| TP-Link Archer T4U ver.3                                               | 2        | 0.88%   |
| TP-Link 802.11ac NIC                                                   | 2        | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 2        | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2        | 0.88%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2        | 0.88%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2        | 0.88%   |
| ZTE WCDMA MSM ZTE Mobile Broadband                                     | 1        | 0.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.44%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1        | 0.44%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1        | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.44%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.44%   |
| Realtek 802.11ac NIC                                                   | 1        | 0.44%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 30       | 34.48%  |
| Realtek Semiconductor | 23       | 26.44%  |
| Qualcomm Atheros      | 7        | 8.05%   |
| MediaTek              | 7        | 8.05%   |
| TP-Link               | 6        | 6.9%    |
| Microsoft             | 6        | 6.9%    |
| Broadcom              | 3        | 3.45%   |
| Ralink                | 2        | 2.3%    |
| Ralink Technology     | 1        | 1.15%   |
| Qualcomm Technologies | 1        | 1.15%   |
| Edimax Technology     | 1        | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                              | 10       | 11.11%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]        | 7        | 7.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 6        | 6.67%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller      | 5        | 5.56%   |
| Microsoft Xbox Wireless Adapter for Windows                      | 5        | 5.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 4        | 4.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 4        | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 4        | 4.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 3        | 3.33%   |
| TP-Link Archer T4U ver.3                                         | 2        | 2.22%   |
| TP-Link 802.11ac NIC                                             | 2        | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 2        | 2.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 2        | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2        | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2        | 2.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter    | 2        | 2.22%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter     | 2        | 2.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                           | 1        | 1.11%   |
| TP-Link 802.11ac WLAN Adapter                                    | 1        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter         | 1        | 1.11%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                       | 1        | 1.11%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                  | 1        | 1.11%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                  | 1        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 1        | 1.11%   |
| Realtek 802.11ac NIC                                             | 1        | 1.11%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                | 1        | 1.11%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800] | 1        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 1        | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                 | 1        | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1        | 1.11%   |
| Microsoft Xbox 360 Wireless Adapter                              | 1        | 1.11%   |
| MediaTek WLAN controller                                         | 1        | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter    | 1        | 1.11%   |
| Intel Wireless 8265 / 8275                                       | 1        | 1.11%   |
| Intel Wireless 7265                                              | 1        | 1.11%   |
| Intel Wireless 3165                                              | 1        | 1.11%   |
| Intel WiFi Link 5100                                             | 1        | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]          | 1        | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 1        | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 77       | 57.89%  |
| Intel                    | 46       | 34.59%  |
| Broadcom                 | 3        | 2.26%   |
| MediaTek                 | 2        | 1.5%    |
| Aquantia                 | 2        | 1.5%    |
| Qualcomm Atheros         | 1        | 0.75%   |
| Qualcomm                 | 1        | 0.75%   |
| Marvell Technology Group | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 55       | 41.04%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 18       | 13.43%  |
| Intel Ethernet Controller I225-V                                                  | 9        | 6.72%   |
| Intel I211 Gigabit Network Connection                                             | 7        | 5.22%   |
| Intel Ethernet Connection I217-LM                                                 | 7        | 5.22%   |
| Intel Ethernet Connection (2) I219-V                                              | 5        | 3.73%   |
| Intel Ethernet Controller I226-V                                                  | 4        | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 3        | 2.24%   |
| Intel 82579V Gigabit Network Connection                                           | 3        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 3        | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 2        | 1.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                     | 2        | 1.49%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                  | 2        | 1.49%   |
| Qualcomm MDM9207-MTP _SN:01E0290C                                                 | 1        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 1        | 0.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                           | 1        | 0.75%   |
| Intel Ethernet Connection I217-V                                                  | 1        | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                                             | 1        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                             | 1        | 0.75%   |
| Intel Ethernet Connection (2) I218-LM                                             | 1        | 0.75%   |
| Intel Ethernet Connection (14) I219-V                                             | 1        | 0.75%   |
| Intel Ethernet Connection (12) I219-V                                             | 1        | 0.75%   |
| Intel Ethernet Connection (11) I219-V                                             | 1        | 0.75%   |
| Intel Ethernet Connection (11) I219-LM                                            | 1        | 0.75%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                   | 1        | 0.75%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 1        | 0.75%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 124      | 60.49%  |
| WiFi     | 79       | 38.54%  |
| Modem    | 2        | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 58.27%  |
| WiFi     | 53       | 41.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 66       | 53.23%  |
| 1     | 53       | 42.74%  |
| 3     | 5        | 4.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 80       | 64.52%  |
| Yes  | 44       | 35.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 34.18%  |
| Realtek Semiconductor           | 13       | 16.46%  |
| Cambridge Silicon Radio         | 13       | 16.46%  |
| IMC Networks                    | 8        | 10.13%  |
| MediaTek                        | 6        | 7.59%   |
| ASUSTek Computer                | 3        | 3.8%    |
| Qualcomm Atheros Communications | 2        | 2.53%   |
| Foxconn / Hon Hai               | 2        | 2.53%   |
| Apple                           | 2        | 2.53%   |
| TP-Link                         | 1        | 1.27%   |
| Dynex                           | 1        | 1.27%   |
| Actions                         | 1        | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                                  | 13       | 16.25%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 13       | 16.25%  |
| Intel AX200 Bluetooth                                    | 9        | 11.25%  |
| MediaTek Wireless_Device                                 | 6        | 7.5%    |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 7.5%    |
| Intel AX210 Bluetooth                                    | 6        | 7.5%    |
| IMC Networks Bluetooth Radio                             | 6        | 7.5%    |
| Intel Bluetooth wireless interface                       | 3        | 3.75%   |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 2.5%    |
| Intel AX201 Bluetooth                                    | 2        | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 2.5%    |
| Apple Bluetooth Host Controller                          | 2        | 2.5%    |
| TP-Link TP-Link Bluetooth USB Adapter                    | 1        | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1        | 1.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 1.25%   |
| IMC Networks Wireless_Device                             | 1        | 1.25%   |
| IMC Networks Bluetooth Device                            | 1        | 1.25%   |
| Foxconn / Hon Hai Wireless_Device                        | 1        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 1.25%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.25%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 1.25%   |
| Actions general adapter                                  | 1        | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 91       | 41.18%  |
| Intel                    | 54       | 24.43%  |
| Nvidia                   | 40       | 18.1%   |
| Logitech                 | 6        | 2.71%   |
| Kingston Technology      | 5        | 2.26%   |
| C-Media Electronics      | 5        | 2.26%   |
| Hewlett-Packard          | 3        | 1.36%   |
| SteelSeries ApS          | 2        | 0.9%    |
| Razer USA                | 2        | 0.9%    |
| ASUSTek Computer         | 2        | 0.9%    |
| Astro Gaming             | 2        | 0.9%    |
| Texas Instruments        | 1        | 0.45%   |
| Sony                     | 1        | 0.45%   |
| Micro Star International | 1        | 0.45%   |
| JMTek                    | 1        | 0.45%   |
| Focusrite-Novation       | 1        | 0.45%   |
| Creative Labs            | 1        | 0.45%   |
| Comtrue                  | 1        | 0.45%   |
| Blue Microphones         | 1        | 0.45%   |
| Arturia                  | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 10.27%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 26       | 8.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 20       | 6.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 4.11%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11       | 3.77%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 11       | 3.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 3.08%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5        | 1.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.71%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.71%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 1.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 1.37%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 1.03%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.03%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 2        | 0.68%   |
| Razer USA Razer Seiren Mini                                                | 2        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.68%   |
| Logitech Yeti X                                                            | 2        | 0.68%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2        | 0.68%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 0.68%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.68%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.68%   |
| C-Media Electronics Auna Mic CM900                                         | 2        | 0.68%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| G.Skill | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| G.Skill RAM F5-6800J3445G32G 32GB DIMM DDR5 4800MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR5 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 4800  | 1        | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Brother HL-L3220CDW series | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 35.71%  |
| Microdia                      | 3        | 21.43%  |
| Sunplus Innovation Technology | 1        | 7.14%   |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 7.14%   |
| Samsung Electronics           | 1        | 7.14%   |
| MacroSilicon                  | 1        | 7.14%   |
| Linux Foundation              | 1        | 7.14%   |
| Huawei Technologies           | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Sunplus HD 720P webcam                  | 1        | 7.14%   |
| SHENZHEN EMEET TECHNOLOGY eMeet Nova    | 1        | 7.14%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 7.14%   |
| Microdia Webcam Vitade AF               | 1        | 7.14%   |
| Microdia USB Camera                     | 1        | 7.14%   |
| Microdia Camera                         | 1        | 7.14%   |
| MacroSilicon USB Video                  | 1        | 7.14%   |
| Logitech Webcam C930e                   | 1        | 7.14%   |
| Logitech Webcam C270                    | 1        | 7.14%   |
| Logitech Webcam C200                    | 1        | 7.14%   |
| Logitech Logi Webcam C920e              | 1        | 7.14%   |
| Logitech HD Pro Webcam C920             | 1        | 7.14%   |
| Linux Foundation EEM Gadget             | 1        | 7.14%   |
| Huawei HiCamera                         | 1        | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

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
| 0     | 81       | 65.32%  |
| 1     | 41       | 33.06%  |
| 2     | 2        | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Graphics card      | 28       | 62.22%  |
| Network            | 6        | 13.33%  |
| Net/wireless       | 4        | 8.89%   |
| Net/ethernet       | 3        | 6.67%   |
| Unassigned class   | 1        | 2.22%   |
| Storage/raid       | 1        | 2.22%   |
| Storage/nvme       | 1        | 2.22%   |
| Fingerprint reader | 1        | 2.22%   |

