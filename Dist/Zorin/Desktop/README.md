Zorin - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 2328

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | 2ADE                        | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Dell          | 0F0TGN A00                  | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| HP            | 18E7                        | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Standard      | X50-V2                      | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | 0HN7XN A01                  | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| HP            | 8350                        | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| ASUSTek       | H87-PRO                     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| Dell          | 0T10XW A00                  | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Gigabyte      | B550 AORUS PRO              | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | 03KWTV A02                  | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| HP            | 2AF7                        | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Acer          | Aspire XC-780               | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | 2AF7                        | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | 2AF7                        | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| HP            | 2AF7                        | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASRock        | G31M-S                      | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| HP            | 09CCh                       | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | 8750                        | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Biostar       | A520MH                      | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| HP            | 82FE 11                     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Biostar       | TPower X58                  | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| AZW           | U59                         | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| HP            | 8433 11                     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| OEM           | H110 Ver:2.21               | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Gateway       | SX2851                      | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| BESSTAR Te... | HM90                        | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Dell          | 0HN7XN A01                  | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| HP            | 822A                        | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | 2AE0                        | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| HP            | 0AA4h                       | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Dell          | 0478VN A00                  | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| HP            | 1850                        | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ASUSTek       | H110M-A                     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Unknown       | 775i65G                     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Biostar       | TPower X58                  | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| MSI           | H81M-P33                    | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Acer          | H81H3-M4                    | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| HP            | 1790                        | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| HP            | 1790                        | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| Dell          | 0HN7XN A01                  | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| ASUSTek       | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| HP            | 1790                        | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Seco          | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | PRIME H370-A                | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gateway       | SX2851                      | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | 0GTK4K A02                  | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| ASUSTek       | H97-PLUS                    | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| HP            | 18E7                        | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| HP            | 2AF3                        | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Unknown       | Unknown                     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| HP            | 304Ah                       | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Standard      | X50-V2                      | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| ASUSTek       | H81M-P                      | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Unknown       | Unknown                     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Acer          | EM61SM/EM61PM               | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| HP            | 822A                        | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| HP            | 2B60 MVB                    | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| HP            | 3397                        | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| HP            | 1632                        | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| HP            | 8055                        | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| ASUSTek       | P5K                         | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Gateway       | FMCP7AM                     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| HP            | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASRock        | B85M Pro4                   | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| ASUSTek       | P5K                         | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | 8055                        | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| ASUSTek       | Benicia                     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| MSI           | MS-7260                     | [52d2fa8c71](https://linux-hardware.org/?probe=52d2fa8c71) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| HP            | 0AA8h                       | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Gigabyte      | Z77-D3H                     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| ECS           | Iris8                       | [dcfb9e172d](https://linux-hardware.org/?probe=dcfb9e172d) | Sep 11, 2022 |
| HP            | 0A54h                       | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| HP            | 3031h                       | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| ECS           | Iris8                       | [29bc0560b4](https://linux-hardware.org/?probe=29bc0560b4) | Sep 10, 2022 |
| HP            | 0AA8h                       | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Intel         | SKYBAY                      | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| ASRock        | B550M/ac                    | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| MSI           | MS-B9201                    | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| MSI           | B250M PRO-VD                | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| Dell          | 0T656F A01                  | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| HP            | 2AF7                        | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Dell          | 0C27VV A03                  | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| ASUSTek       | A88X-PRO                    | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| HP            | 1589                        | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| HP            | 18E7                        | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| MSI           | Z97 GAMING 5                | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| MP            | MS-7848                     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| LORD ELECT... | GM965 Series                | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| ASUSTek       | P7H55-M LX                  | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Supermicro    | C7Q67 V1.01                 | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| ASRock        | Z170 Pro4                   | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Gigabyte      | M68M-S2P                    | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| MSI           | Z97 GAMING 5                | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Foxconn       | 2AAF                        | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| MSI           | B75MA-P45                   | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| System76      | Thelio thelio-r2            | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 0J3C2F A00                  | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Pegatron      | Benicia                     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | 18E4                        | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| Lenovo        | 3098 0B98401 PRO            | [830b5c1c8d](https://linux-hardware.org/?probe=830b5c1c8d) | Jul 07, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| ASUSTek       | M3A78-EM                    | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| HP            | 8350                        | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| Gigabyte      | EP45-DS3                    | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| Dell          | 0HJ054                      | [bb9d7a3a58](https://linux-hardware.org/?probe=bb9d7a3a58) | Jun 30, 2022 |
| Gigabyte      | B360M HD3                   | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Lenovo        | 3098 0B98401 PRO            | [9923c241d9](https://linux-hardware.org/?probe=9923c241d9) | Jun 27, 2022 |
| Dell          | 0U880P A00                  | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| MSI           | A75A-G35                    | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Gigabyte      | EX58-UD3R                   | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Acer          | Aspire M3970                | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| MSI           | MEG Z690 UNIFY              | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| Foxconn       | Irvine HP P/N               | [551f18d133](https://linux-hardware.org/?probe=551f18d133) | Jun 11, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| Dell          | 0XFWHV A00                  | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Dell          | 0WR7PY A03                  | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| ASRock        | 970 Extreme3                | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Biostar       | A78MD                       | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Biostar       | A78MD                       | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| MSI           | Z97 XPOWER AC               | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| ASRock        | B450 Pro4                   | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Gigabyte      | F2A58M-DS2                  | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| Dell          | 088DT1 A01                  | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Dell          | 088DT1 A01                  | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [293f5586bd](https://linux-hardware.org/?probe=293f5586bd) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| MSI           | Z170A GAMING PRO            | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| ASUSTek       | G15DK                       | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [aa8b5a4aec](https://linux-hardware.org/?probe=aa8b5a4aec) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [4b277b05bb](https://linux-hardware.org/?probe=4b277b05bb) | May 17, 2022 |
| HP            | 2ADE                        | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| Dell          | 0C27VV A01                  | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| ASRock        | A88M-G                      | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| MSI           | MS-7260                     | [835ab9042d](https://linux-hardware.org/?probe=835ab9042d) | May 13, 2022 |
| Intel         | DH77EB AAG39073-304         | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Foxconn       | LIMA                        | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| Gateway       | SX2185                      | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| HP            | 1906                        | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| MSI           | B85M-G43                    | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| MSI           | Z590 PRO WIFI               | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| HP            | 1906                        | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| Maxtone       | HIS-G41L V1.1               | [ce61ffd777](https://linux-hardware.org/?probe=ce61ffd777) | May 02, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | [63fc1199bc](https://linux-hardware.org/?probe=63fc1199bc) | May 01, 2022 |
| ASUSTek       | H97I-PLUS                   | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| ASRock        | B365M-HDV                   | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Dell          | 0M017G A01                  | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| HP            | 1791                        | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| BESSTAR Te... | HM90                        | [814f90b822](https://linux-hardware.org/?probe=814f90b822) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| MSI           | MS-6701                     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| MSI           | MS-6701                     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| MSI           | B450 TOMAHAWK               | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| MSI           | 760GM-P21                   | [3582362347](https://linux-hardware.org/?probe=3582362347) | Apr 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [1b392b96c3](https://linux-hardware.org/?probe=1b392b96c3) | Apr 24, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [b36aa38e8a](https://linux-hardware.org/?probe=b36aa38e8a) | Apr 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [da2e3a603d](https://linux-hardware.org/?probe=da2e3a603d) | Apr 23, 2022 |
| Dell          | 0GDG8Y A00                  | [a0ab7e8078](https://linux-hardware.org/?probe=a0ab7e8078) | Apr 22, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [15332404e6](https://linux-hardware.org/?probe=15332404e6) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [b272388aa6](https://linux-hardware.org/?probe=b272388aa6) | Apr 21, 2022 |
| ASUSTek       | P5GC-MX                     | [810607b312](https://linux-hardware.org/?probe=810607b312) | Apr 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [9b742eb785](https://linux-hardware.org/?probe=9b742eb785) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| Gigabyte      | Z68AP-D3                    | [76d25fd5c1](https://linux-hardware.org/?probe=76d25fd5c1) | Apr 20, 2022 |
| MSI           | B450M PRO-VDH MAX           | [73dbb7e52a](https://linux-hardware.org/?probe=73dbb7e52a) | Apr 19, 2022 |
| HP            | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [b3f2a146ea](https://linux-hardware.org/?probe=b3f2a146ea) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [d597e4df9c](https://linux-hardware.org/?probe=d597e4df9c) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| MSI           | 2AE0                        | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| MSI           | MAG B460M MORTAR            | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| ASUSTek       | F2A85-V                     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| Pegatron      | 2A99h                       | [0d208bc673](https://linux-hardware.org/?probe=0d208bc673) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | [7a31392de4](https://linux-hardware.org/?probe=7a31392de4) | Apr 13, 2022 |
| Gigabyte      | Z77-D3H                     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| Foxconn       | 2A92                        | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| Gigabyte      | 945PL-S3                    | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| ECS           | Livermore                   | [afafdb72a7](https://linux-hardware.org/?probe=afafdb72a7) | Apr 06, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| Foxconn       | 2A92                        | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| MSI           | MS-7204                     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| MSI           | MS-7204                     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| MSI           | B75A-G41                    | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| ECS           | Livermore                   | [d801396140](https://linux-hardware.org/?probe=d801396140) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| ASUSTek       | P5GD1 PRO                   | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| Biostar       | X370GT5                     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| Pegatron      | Benicia                     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Dell          | 0P096C A01                  | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| ASRock        | B550 Steel Legend           | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| HP            | 1497                        | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| HP            | 1497                        | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Dell          | 0WMJ54 A01                  | [fe21b2c644](https://linux-hardware.org/?probe=fe21b2c644) | Mar 15, 2022 |
| HP            | 1791                        | [f183c3d0f0](https://linux-hardware.org/?probe=f183c3d0f0) | Mar 15, 2022 |
| HP            | 1497                        | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| TYAN Compu... | D2568 S26361-D2568-A11      | [fd7cbc2300](https://linux-hardware.org/?probe=fd7cbc2300) | Mar 15, 2022 |
| Dell          | 0CU409                      | [2e684afab9](https://linux-hardware.org/?probe=2e684afab9) | Mar 14, 2022 |
| MSI           | B85M-G43                    | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| ASUSTek       | Maximus VIII GENE           | [f264de34b1](https://linux-hardware.org/?probe=f264de34b1) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [a90ce91192](https://linux-hardware.org/?probe=a90ce91192) | Mar 12, 2022 |
| ASUSTek       | P8P67                       | [33bf33cb8d](https://linux-hardware.org/?probe=33bf33cb8d) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| Google        | Buddy                       | [848034437d](https://linux-hardware.org/?probe=848034437d) | Mar 09, 2022 |
| Google        | Buddy                       | [db18fd0c96](https://linux-hardware.org/?probe=db18fd0c96) | Mar 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| MSI           | H110M PRO-VH PLUS           | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| MSI           | A75A-G35                    | [8dfa30cef5](https://linux-hardware.org/?probe=8dfa30cef5) | Mar 07, 2022 |
| ASUSTek       | Z97-DELUXE                  | [7ea271a455](https://linux-hardware.org/?probe=7ea271a455) | Mar 05, 2022 |
| MSI           | B85M-G43                    | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Intel         | H61                         | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [78089f6e8c](https://linux-hardware.org/?probe=78089f6e8c) | Mar 03, 2022 |
| Gigabyte      | Z77-DS3H                    | [16268a74aa](https://linux-hardware.org/?probe=16268a74aa) | Mar 03, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [1d01e4616b](https://linux-hardware.org/?probe=1d01e4616b) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| ASUSTek       | PRIME X370-PRO              | [b74317d80e](https://linux-hardware.org/?probe=b74317d80e) | Mar 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a94729eaf7](https://linux-hardware.org/?probe=a94729eaf7) | Mar 01, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| Gigabyte      | GA-990FXA-D3                | [67943c7786](https://linux-hardware.org/?probe=67943c7786) | Feb 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-990FXA-D3                | [badbd8817c](https://linux-hardware.org/?probe=badbd8817c) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Gigabyte      | N3160TN                     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| IBM           | 819046G                     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| Acer          | K8VM800MAE                  | [e4505f1541](https://linux-hardware.org/?probe=e4505f1541) | Feb 17, 2022 |
| Acer          | K8VM800MAE                  | [ac2f1dab87](https://linux-hardware.org/?probe=ac2f1dab87) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| ASUSTek       | P8P67                       | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | 2B15A                       | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| HP            | 0B54h D                     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| Dell          | 0GM819                      | [bdd485de00](https://linux-hardware.org/?probe=bdd485de00) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 8350                        | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| ASUSTek       | H110M-CS/BR                 | [f4319bd379](https://linux-hardware.org/?probe=f4319bd379) | Feb 05, 2022 |
| Dell          | 0DN075                      | [eb385877ae](https://linux-hardware.org/?probe=eb385877ae) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| Gigabyte      | H81M-S2V                    | [4c9a0cdddb](https://linux-hardware.org/?probe=4c9a0cdddb) | Feb 03, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| ASUSTek       | M4A785-M                    | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Unknown       | Unknown                     | [f302ce9f42](https://linux-hardware.org/?probe=f302ce9f42) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| Gigabyte      | M68MT-D3                    | [8818e2647a](https://linux-hardware.org/?probe=8818e2647a) | Jan 29, 2022 |
| ASUSTek       | H110M-CS/BR                 | [a3f76dfb23](https://linux-hardware.org/?probe=a3f76dfb23) | Jan 29, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | 2AE0                        | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| HP            | 0B4Ch D                     | [e498058bd8](https://linux-hardware.org/?probe=e498058bd8) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| Intel         | DH55TC AAE70932-302         | [d66879ebac](https://linux-hardware.org/?probe=d66879ebac) | Jan 27, 2022 |
| ASRock        | G31M-S                      | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| Dell          | 0CU409                      | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Gigabyte      | M68MT-D3                    | [9f01c8b5ba](https://linux-hardware.org/?probe=9f01c8b5ba) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| Shuttle       | FB62                        | [01c9cc70b3](https://linux-hardware.org/?probe=01c9cc70b3) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [bb0d1c1c68](https://linux-hardware.org/?probe=bb0d1c1c68) | Jan 19, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| MSI           | H61M-P25                    | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [ce5b35b77b](https://linux-hardware.org/?probe=ce5b35b77b) | Jan 10, 2022 |
| Phitronics    | P33G                        | [d21245c1ea](https://linux-hardware.org/?probe=d21245c1ea) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Shuttle       | FB62                        | [704df008d5](https://linux-hardware.org/?probe=704df008d5) | Jan 06, 2022 |
| Shuttle       | FB62                        | [2da02c481d](https://linux-hardware.org/?probe=2da02c481d) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| Dell          | 0GDG8Y A00                  | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| Dell          | 096JG8 A01                  | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| ASUSTek       | NODUSM3                     | [88f0b2e09a](https://linux-hardware.org/?probe=88f0b2e09a) | Jan 05, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| ASRock        | B450M Steel Legend          | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| HP            | 3031h                       | [cc5f90a5be](https://linux-hardware.org/?probe=cc5f90a5be) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | 1998                        | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Gigabyte      | Z97-HD3                     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| Packard Be... | MCP73VT-PM                  | [c4f47dca10](https://linux-hardware.org/?probe=c4f47dca10) | Dec 27, 2021 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Zorin 16 | 914      | 59.86%  |
| Zorin 15 | 537      | 35.17%  |
| Zorin 12 | 76       | 4.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Zorin | 1523     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 67       | 3.86%   |
| 5.11.0-38-generic | 62       | 3.57%   |
| 5.11.0-27-generic | 56       | 3.23%   |
| 5.15.0-46-generic | 55       | 3.17%   |
| 5.11.0-40-generic | 50       | 2.88%   |
| 5.15.0-52-generic | 48       | 2.77%   |
| 5.13.0-39-generic | 48       | 2.77%   |
| 5.15.0-48-generic | 41       | 2.36%   |
| 5.11.0-41-generic | 41       | 2.36%   |
| 5.3.0-40-generic  | 40       | 2.31%   |
| 5.13.0-30-generic | 39       | 2.25%   |
| 5.13.0-40-generic | 38       | 2.19%   |
| 5.11.0-43-generic | 36       | 2.07%   |
| 5.15.0-41-generic | 35       | 2.02%   |
| 5.11.0-37-generic | 35       | 2.02%   |
| 5.4.0-42-generic  | 31       | 1.79%   |
| 5.11.0-34-generic | 31       | 1.79%   |
| 5.13.0-28-generic | 30       | 1.73%   |
| 5.15.0-53-generic | 28       | 1.61%   |
| 5.13.0-35-generic | 28       | 1.61%   |
| 5.0.0-37-generic  | 27       | 1.56%   |
| 5.13.0-27-generic | 26       | 1.5%    |
| 5.13.0-41-generic | 25       | 1.44%   |
| 5.15.0-58-generic | 24       | 1.38%   |
| 5.13.0-52-generic | 24       | 1.38%   |
| 5.13.0-44-generic | 21       | 1.21%   |
| 5.4.0-58-generic  | 20       | 1.15%   |
| 5.4.0-72-generic  | 19       | 1.1%    |
| 5.4.0-47-generic  | 19       | 1.1%    |
| 5.3.0-62-generic  | 17       | 0.98%   |
| 5.3.0-51-generic  | 17       | 0.98%   |
| 5.3.0-46-generic  | 17       | 0.98%   |
| 5.13.0-51-generic | 17       | 0.98%   |
| 5.4.0-54-generic  | 16       | 0.92%   |
| 5.3.0-59-generic  | 16       | 0.92%   |
| 5.3.0-53-generic  | 16       | 0.92%   |
| 5.4.0-74-generic  | 15       | 0.86%   |
| 5.4.0-65-generic  | 15       | 0.86%   |
| 5.3.0-28-generic  | 15       | 0.86%   |
| 5.4.0-80-generic  | 14       | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 333      | 20.88%  |
| 5.4.0   | 309      | 19.37%  |
| 5.15.0  | 305      | 19.12%  |
| 5.13.0  | 289      | 18.12%  |
| 5.3.0   | 158      | 9.91%   |
| 4.15.0  | 75       | 4.7%    |
| 5.0.0   | 58       | 3.64%   |
| 4.18.0  | 27       | 1.69%   |
| 5.8.0   | 26       | 1.63%   |
| 6.1.7   | 1        | 0.06%   |
| 6.0.8   | 1        | 0.06%   |
| 5.8.5   | 1        | 0.06%   |
| 5.7.17  | 1        | 0.06%   |
| 5.7.1   | 1        | 0.06%   |
| 5.7.0   | 1        | 0.06%   |
| 5.19.6  | 1        | 0.06%   |
| 5.19.2  | 1        | 0.06%   |
| 5.19.12 | 1        | 0.06%   |
| 5.17.9  | 1        | 0.06%   |
| 5.17.5  | 1        | 0.06%   |
| 5.17.1  | 1        | 0.06%   |
| 5.15.13 | 1        | 0.06%   |
| 5.14.0  | 1        | 0.06%   |
| 4.4.0   | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 333      | 20.88%  |
| 5.4     | 309      | 19.37%  |
| 5.15    | 306      | 19.18%  |
| 5.13    | 289      | 18.12%  |
| 5.3     | 158      | 9.91%   |
| 4.15    | 75       | 4.7%    |
| 5.0     | 58       | 3.64%   |
| 5.8     | 27       | 1.69%   |
| 4.18    | 27       | 1.69%   |
| 5.7     | 3        | 0.19%   |
| 5.19    | 3        | 0.19%   |
| 5.17    | 3        | 0.19%   |
| 6.1     | 1        | 0.06%   |
| 6.0     | 1        | 0.06%   |
| 5.14    | 1        | 0.06%   |
| 4.4     | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1422     | 93.37%  |
| i686   | 101      | 6.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1150     | 74.29%  |
| XFCE       | 275      | 17.76%  |
| Unknown    | 118      | 7.62%   |
| X-Cinnamon | 1        | 0.06%   |
| MATE       | 1        | 0.06%   |
| KDE5       | 1        | 0.06%   |
| KDE        | 1        | 0.06%   |
| Cinnamon   | 1        | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1456     | 94.79%  |
| Unknown | 67       | 4.36%   |
| Wayland | 12       | 0.78%   |
| Tty     | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1318     | 85.03%  |
| GDM3    | 106      | 6.84%   |
| GDM     | 71       | 4.58%   |
| LightDM | 50       | 3.23%   |
| TDM     | 4        | 0.26%   |
| SDDM    | 1        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 559      | 36.42%  |
| de_DE   | 127      | 8.27%   |
| pt_BR   | 115      | 7.49%   |
| en_GB   | 102      | 6.64%   |
| Unknown | 96       | 6.25%   |
| it_IT   | 42       | 2.74%   |
| en_CA   | 41       | 2.67%   |
| fr_FR   | 39       | 2.54%   |
| en_IN   | 35       | 2.28%   |
| es_ES   | 32       | 2.08%   |
| pl_PL   | 31       | 2.02%   |
| nl_NL   | 30       | 1.95%   |
| en_AU   | 29       | 1.89%   |
| ru_RU   | 23       | 1.5%    |
| es_AR   | 23       | 1.5%    |
| es_MX   | 18       | 1.17%   |
| hu_HU   | 15       | 0.98%   |
| en_ZA   | 13       | 0.85%   |
| fr_CA   | 10       | 0.65%   |
| cs_CZ   | 10       | 0.65%   |
| sv_SE   | 9        | 0.59%   |
| pt_PT   | 7        | 0.46%   |
| es_CO   | 7        | 0.46%   |
| es_CL   | 7        | 0.46%   |
| C       | 7        | 0.46%   |
| tr_TR   | 6        | 0.39%   |
| nb_NO   | 6        | 0.39%   |
| ja_JP   | 6        | 0.39%   |
| nl_BE   | 5        | 0.33%   |
| en_NZ   | 5        | 0.33%   |
| el_GR   | 5        | 0.33%   |
| da_DK   | 5        | 0.33%   |
| es_PE   | 4        | 0.26%   |
| en_PH   | 4        | 0.26%   |
| de_CH   | 4        | 0.26%   |
| bg_BG   | 4        | 0.26%   |
| sr_RS   | 3        | 0.2%    |
| sk_SK   | 3        | 0.2%    |
| es_US   | 3        | 0.2%    |
| sl_SI   | 2        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 983      | 63.96%  |
| EFI  | 554      | 36.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1435     | 93.91%  |
| Overlay  | 32       | 2.09%   |
| Zfs      | 20       | 1.31%   |
| Btrfs    | 12       | 0.79%   |
| Ext2     | 11       | 0.72%   |
| Unknown  | 10       | 0.65%   |
| Ext3     | 4        | 0.26%   |
| Xfs      | 3        | 0.2%    |
| Reiserfs | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1419     | 92.62%  |
| GPT     | 73       | 4.77%   |
| MBR     | 40       | 2.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1413     | 92.05%  |
| Yes       | 122      | 7.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1178     | 76.39%  |
| Yes       | 364      | 23.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 349      | 22.92%  |
| Gigabyte Technology | 232      | 15.23%  |
| Dell                | 161      | 10.57%  |
| Hewlett-Packard     | 137      | 9%      |
| MSI                 | 130      | 8.54%   |
| ASRock              | 124      | 8.14%   |
| Lenovo              | 71       | 4.66%   |
| Intel               | 45       | 2.95%   |
| Pegatron            | 27       | 1.77%   |
| Acer                | 26       | 1.71%   |
| Unknown             | 23       | 1.51%   |
| Foxconn             | 22       | 1.44%   |
| Biostar             | 22       | 1.44%   |
| Fujitsu             | 20       | 1.31%   |
| ECS                 | 17       | 1.12%   |
| Medion              | 7        | 0.46%   |
| Shuttle             | 6        | 0.39%   |
| Positivo            | 6        | 0.39%   |
| Alienware           | 6        | 0.39%   |
| Gateway             | 5        | 0.33%   |
| Apple               | 5        | 0.33%   |
| OEM                 | 4        | 0.26%   |
| IBM                 | 4        | 0.26%   |
| BESSTAR Tech        | 4        | 0.26%   |
| Packard Bell        | 3        | 0.2%    |
| Huanan              | 3        | 0.2%    |
| eMachines           | 3        | 0.2%    |
| ABIT                | 3        | 0.2%    |
| ZOTAC               | 2        | 0.13%   |
| WinFast             | 2        | 0.13%   |
| SiS Technology      | 2        | 0.13%   |
| Semp Toshiba        | 2        | 0.13%   |
| PCWare              | 2        | 0.13%   |
| MAXSUN              | 2        | 0.13%   |
| JGINYUE             | 2        | 0.13%   |
| Google              | 2        | 0.13%   |
| Xi3                 | 1        | 0.07%   |
| Wortmann AG         | 1        | 0.07%   |
| Wistron             | 1        | 0.07%   |
| WIPRO               | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 33       | 2.17%   |
| Unknown                          | 27       | 1.77%   |
| Dell OptiPlex 7010               | 11       | 0.72%   |
| Dell OptiPlex 790                | 10       | 0.66%   |
| Dell OptiPlex 780                | 10       | 0.66%   |
| Gigabyte A320M-S2H               | 8        | 0.53%   |
| Dell OptiPlex 380                | 8        | 0.53%   |
| MSI MS-7C02                      | 7        | 0.46%   |
| Gigabyte 970A-DS3P               | 7        | 0.46%   |
| Dell OptiPlex 990                | 7        | 0.46%   |
| Dell OptiPlex 755                | 7        | 0.46%   |
| ASUS M5A78L-M/USB3               | 7        | 0.46%   |
| MSI MS-7817                      | 6        | 0.39%   |
| HP ProDesk 600 G1 SFF            | 6        | 0.39%   |
| Gigabyte B450 AORUS M            | 6        | 0.39%   |
| Dell OptiPlex 3010               | 6        | 0.39%   |
| ASUS M5A97 R2.0                  | 6        | 0.39%   |
| Gigabyte GA-78LMT-USB3 6.0       | 5        | 0.33%   |
| Gigabyte GA-78LMT-USB3           | 5        | 0.33%   |
| Dell Precision WorkStation T3500 | 5        | 0.33%   |
| Dell Inspiron 3847               | 5        | 0.33%   |
| ASUS TUF Gaming X570-PLUS        | 5        | 0.33%   |
| ASRock N68C-S UCC                | 5        | 0.33%   |
| MSI MS-7721                      | 4        | 0.26%   |
| HP Compaq Pro 6300 SFF           | 4        | 0.26%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.26%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.26%   |
| Gigabyte B450M DS3H              | 4        | 0.26%   |
| Dell Vostro 200                  | 4        | 0.26%   |
| Dell Precision T1600             | 4        | 0.26%   |
| Dell OptiPlex 7040               | 4        | 0.26%   |
| Dell OptiPlex 330                | 4        | 0.26%   |
| ASUS P5G41T-M LX3                | 4        | 0.26%   |
| ASRock B450M Pro4                | 4        | 0.26%   |
| ASRock B450 Pro4                 | 4        | 0.26%   |
| Pegatron NE502AV-ABA a6750t      | 3        | 0.2%    |
| OEM G41 775 ICH7 8712            | 3        | 0.2%    |
| MSI MS-7C75                      | 3        | 0.2%    |
| MSI MS-7C37                      | 3        | 0.2%    |
| MSI MS-7B89                      | 3        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 97       | 6.37%   |
| HP Compaq              | 51       | 3.35%   |
| Lenovo ThinkCentre     | 46       | 3.02%   |
| ASUS PRIME             | 40       | 2.63%   |
| ASUS All               | 33       | 2.17%   |
| ASUS ROG               | 32       | 2.1%    |
| Unknown                | 27       | 1.77%   |
| ASUS TUF               | 24       | 1.58%   |
| Fujitsu ESPRIMO        | 16       | 1.05%   |
| Dell Precision         | 16       | 1.05%   |
| HP EliteDesk           | 14       | 0.92%   |
| Dell Inspiron          | 14       | 0.92%   |
| Acer Aspire            | 13       | 0.85%   |
| Gigabyte B450          | 12       | 0.79%   |
| ASUS M5A78L-M          | 12       | 0.79%   |
| HP ProDesk             | 11       | 0.72%   |
| Gigabyte GA-78LMT-USB3 | 11       | 0.72%   |
| Dell Vostro            | 11       | 0.72%   |
| ASUS M5A97             | 11       | 0.72%   |
| Gigabyte X570          | 9        | 0.59%   |
| Gigabyte A320M-S2H     | 9        | 0.59%   |
| Lenovo IdeaCentre      | 8        | 0.53%   |
| Dell XPS               | 8        | 0.53%   |
| ASRock B450            | 8        | 0.53%   |
| Acer Veriton           | 8        | 0.53%   |
| MSI MS-7C02            | 7        | 0.46%   |
| HP Pavilion            | 7        | 0.46%   |
| Gigabyte B450M         | 7        | 0.46%   |
| Gigabyte 970A-DS3P     | 7        | 0.46%   |
| ASUS P8H61-M           | 7        | 0.46%   |
| ASUS P5G41T-M          | 7        | 0.46%   |
| ASRock B450M           | 7        | 0.46%   |
| MSI MS-7817            | 6        | 0.39%   |
| ASRock N68C-S          | 6        | 0.39%   |
| ASUS P5KPL-AM          | 5        | 0.33%   |
| ASRock 970             | 5        | 0.33%   |
| MSI MS-7721            | 4        | 0.26%   |
| Gigabyte B550          | 4        | 0.26%   |
| Dell Studio            | 4        | 0.26%   |
| ASUS P8Z77-V           | 4        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 138      | 9.06%   |
| 2011    | 134      | 8.8%    |
| 2013    | 131      | 8.6%    |
| 2010    | 125      | 8.21%   |
| 2018    | 122      | 8.01%   |
| 2009    | 107      | 7.03%   |
| 2014    | 102      | 6.7%    |
| 2008    | 100      | 6.57%   |
| 2019    | 77       | 5.06%   |
| 2020    | 76       | 4.99%   |
| 2007    | 74       | 4.86%   |
| 2017    | 65       | 4.27%   |
| 2021    | 61       | 4.01%   |
| 2016    | 57       | 3.74%   |
| 2015    | 49       | 3.22%   |
| 2006    | 42       | 2.76%   |
| 2005    | 26       | 1.71%   |
| 2022    | 16       | 1.05%   |
| 2004    | 10       | 0.66%   |
| 2003    | 6        | 0.39%   |
| Unknown | 4        | 0.26%   |
| 2002    | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1523     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1458     | 95.42%  |
| Enabled  | 70       | 4.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1521     | 99.87%  |
| Yes  | 2        | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 320      | 20.69%  |
| 16.01-24.0  | 314      | 20.3%   |
| 3.01-4.0    | 301      | 19.46%  |
| 4.01-8.0    | 231      | 14.93%  |
| 32.01-64.0  | 153      | 9.89%   |
| 1.01-2.0    | 101      | 6.53%   |
| 2.01-3.0    | 46       | 2.97%   |
| 64.01-256.0 | 38       | 2.46%   |
| 0.51-1.0    | 24       | 1.55%   |
| 24.01-32.0  | 19       | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 706      | 42.92%  |
| 2.01-3.0   | 420      | 25.53%  |
| 3.01-4.0   | 180      | 10.94%  |
| 4.01-8.0   | 161      | 9.79%   |
| 0.51-1.0   | 122      | 7.42%   |
| 8.01-16.0  | 32       | 1.95%   |
| 0.01-0.5   | 16       | 0.97%   |
| 16.01-24.0 | 6        | 0.36%   |
| 32.01-64.0 | 1        | 0.06%   |
| 24.01-32.0 | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 765      | 48.85%  |
| 2      | 429      | 27.39%  |
| 3      | 182      | 11.62%  |
| 4      | 86       | 5.49%   |
| 5      | 47       | 3%      |
| 6      | 27       | 1.72%   |
| 7      | 10       | 0.64%   |
| 0      | 9        | 0.57%   |
| 8      | 8        | 0.51%   |
| 51     | 1        | 0.06%   |
| 11     | 1        | 0.06%   |
| 10     | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 855      | 55.77%  |
| No        | 678      | 44.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1502     | 98.62%  |
| No        | 21       | 1.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 794      | 51.63%  |
| Yes       | 744      | 48.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1122     | 72.9%   |
| Yes       | 417      | 27.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 377      | 24.67%  |
| Germany      | 142      | 9.29%   |
| Brazil       | 128      | 8.38%   |
| UK           | 102      | 6.68%   |
| Canada       | 60       | 3.93%   |
| Italy        | 53       | 3.47%   |
| Netherlands  | 52       | 3.4%    |
| France       | 39       | 2.55%   |
| Spain        | 37       | 2.42%   |
| India        | 37       | 2.42%   |
| Poland       | 33       | 2.16%   |
| Australia    | 32       | 2.09%   |
| Argentina    | 28       | 1.83%   |
| Mexico       | 19       | 1.24%   |
| Hungary      | 19       | 1.24%   |
| Russia       | 18       | 1.18%   |
| Greece       | 16       | 1.05%   |
| Denmark      | 16       | 1.05%   |
| South Africa | 15       | 0.98%   |
| Sweden       | 14       | 0.92%   |
| Norway       | 14       | 0.92%   |
| Indonesia    | 14       | 0.92%   |
| Switzerland  | 13       | 0.85%   |
| Czechia      | 13       | 0.85%   |
| Chile        | 13       | 0.85%   |
| Serbia       | 11       | 0.72%   |
| Portugal     | 11       | 0.72%   |
| Colombia     | 10       | 0.65%   |
| Romania      | 9        | 0.59%   |
| Japan        | 9        | 0.59%   |
| Egypt        | 9        | 0.59%   |
| Belgium      | 9        | 0.59%   |
| Malaysia     | 8        | 0.52%   |
| Bulgaria     | 8        | 0.52%   |
| Ukraine      | 7        | 0.46%   |
| Turkey       | 7        | 0.46%   |
| Philippines  | 7        | 0.46%   |
| Austria      | 6        | 0.39%   |
| Venezuela    | 5        | 0.33%   |
| Slovenia     | 5        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 14       | 0.89%   |
| Berlin         | 13       | 0.82%   |
| Athens         | 13       | 0.82%   |
| Rio de Janeiro | 12       | 0.76%   |
| Munich         | 10       | 0.63%   |
| Milan          | 8        | 0.51%   |
| Buenos Aires   | 8        | 0.51%   |
| Toronto        | 7        | 0.44%   |
| Perth          | 7        | 0.44%   |
| Houston        | 7        | 0.44%   |
| Denver         | 7        | 0.44%   |
| Copenhagen     | 7        | 0.44%   |
| Bengaluru      | 7        | 0.44%   |
| Belgrade       | 7        | 0.44%   |
| Zurich         | 6        | 0.38%   |
| Vienna         | 6        | 0.38%   |
| Santiago       | 6        | 0.38%   |
| London         | 6        | 0.38%   |
| Dallas         | 6        | 0.38%   |
| Cape Town      | 6        | 0.38%   |
| Budapest       | 6        | 0.38%   |
| Bogotá        | 6        | 0.38%   |
| Adelaide       | 6        | 0.38%   |
| Warsaw         | 5        | 0.32%   |
| Sydney         | 5        | 0.32%   |
| Rome           | 5        | 0.32%   |
| Richmond       | 5        | 0.32%   |
| Portland       | 5        | 0.32%   |
| Phoenix        | 5        | 0.32%   |
| Las Vegas      | 5        | 0.32%   |
| Dayton         | 5        | 0.32%   |
| Calgary        | 5        | 0.32%   |
| Brasília      | 5        | 0.32%   |
| Yogyakarta     | 4        | 0.25%   |
| The Hague      | 4        | 0.25%   |
| San Jose       | 4        | 0.25%   |
| Rotterdam      | 4        | 0.25%   |
| Orlando        | 4        | 0.25%   |
| Montreal       | 4        | 0.25%   |
| Mentor         | 4        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 543      | 810    | 21.35%  |
| WDC                       | 475      | 674    | 18.68%  |
| Samsung Electronics       | 322      | 484    | 12.66%  |
| Kingston                  | 160      | 215    | 6.29%   |
| Toshiba                   | 127      | 201    | 4.99%   |
| Hitachi                   | 125      | 154    | 4.92%   |
| SanDisk                   | 117      | 144    | 4.6%    |
| Crucial                   | 82       | 100    | 3.22%   |
| Maxtor                    | 41       | 58     | 1.61%   |
| Unknown                   | 31       | 52     | 1.22%   |
| Phison                    | 31       | 40     | 1.22%   |
| Intel                     | 30       | 37     | 1.18%   |
| China                     | 30       | 34     | 1.18%   |
| A-DATA Technology         | 30       | 36     | 1.18%   |
| Silicon Motion            | 26       | 34     | 1.02%   |
| PNY                       | 21       | 28     | 0.83%   |
| HGST                      | 17       | 25     | 0.67%   |
| OCZ                       | 16       | 19     | 0.63%   |
| Patriot                   | 15       | 23     | 0.59%   |
| Intenso                   | 15       | 18     | 0.59%   |
| SPCC                      | 13       | 15     | 0.51%   |
| SK hynix                  | 13       | 18     | 0.51%   |
| Micron Technology         | 11       | 12     | 0.43%   |
| Hewlett-Packard           | 10       | 14     | 0.39%   |
| Gigabyte Technology       | 10       | 18     | 0.39%   |
| Corsair                   | 10       | 12     | 0.39%   |
| Micron/Crucial Technology | 9        | 9      | 0.35%   |
| KingSpec                  | 9        | 11     | 0.35%   |
| JMicron Technology        | 9        | 14     | 0.35%   |
| Lexar                     | 8        | 8      | 0.31%   |
| GOODRAM                   | 8        | 8      | 0.31%   |
| Apacer                    | 8        | 9      | 0.31%   |
| XPG                       | 7        | 9      | 0.28%   |
| Transcend                 | 7        | 8      | 0.28%   |
| Leven                     | 7        | 8      | 0.28%   |
| SABRENT                   | 6        | 6      | 0.24%   |
| Realtek Semiconductor     | 6        | 6      | 0.24%   |
| Apple                     | 6        | 6      | 0.24%   |
| Netac                     | 5        | 7      | 0.2%    |
| HS-SSD-C100               | 5        | 5      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 52       | 1.8%    |
| Kingston SA400S37240G 240GB SSD  | 43       | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB   | 35       | 1.21%   |
| Samsung SSD 860 EVO 500GB        | 27       | 0.93%   |
| Seagate ST3500418AS 500GB        | 26       | 0.9%    |
| Kingston SA400S37480G 480GB SSD  | 22       | 0.76%   |
| Kingston SA400S37120G 120GB SSD  | 22       | 0.76%   |
| Crucial CT240BX500SSD1 240GB     | 22       | 0.76%   |
| Toshiba DT01ACA100 1TB           | 21       | 0.73%   |
| Samsung NVMe SSD Drive 1TB       | 21       | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB         | 20       | 0.69%   |
| Samsung SSD 850 EVO 250GB        | 20       | 0.69%   |
| Samsung NVMe SSD Drive 500GB     | 20       | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB   | 19       | 0.66%   |
| Toshiba HDWD110 1TB              | 18       | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB   | 18       | 0.62%   |
| Kingston SV300S37A120G 120GB SSD | 18       | 0.62%   |
| SanDisk NVMe SSD Drive 500GB     | 15       | 0.52%   |
| Samsung SSD 850 EVO 500GB        | 15       | 0.52%   |
| Unknown SD/MMC/MS PRO 2GB        | 14       | 0.48%   |
| Seagate ST3500413AS 500GB        | 14       | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB   | 14       | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB   | 14       | 0.48%   |
| Seagate ST1000DM003-1SB102 1TB   | 14       | 0.48%   |
| Toshiba DT01ACA050 500GB         | 13       | 0.45%   |
| Samsung SSD 840 EVO 250GB        | 13       | 0.45%   |
| Seagate ST3500312CS 500GB        | 12       | 0.41%   |
| SanDisk NVMe SSD Drive 1TB       | 12       | 0.41%   |
| Seagate ST31000528AS 1TB         | 11       | 0.38%   |
| Samsung HD103SJ 1TB              | 11       | 0.38%   |
| Hitachi HDS721616PLA380 160GB    | 11       | 0.38%   |
| Crucial CT500MX500SSD1 500GB     | 11       | 0.38%   |
| Crucial CT1000MX500SSD1 1TB      | 11       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB         | 10       | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB   | 10       | 0.35%   |
| Seagate ST3250310AS 250GB        | 10       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB   | 10       | 0.35%   |
| SanDisk SSD PLUS 240GB           | 10       | 0.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 9        | 0.31%   |
| WDC WD10EZEX-00WN4A0 1TB         | 9        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 536      | 792    | 37.91%  |
| WDC                 | 447      | 625    | 31.61%  |
| Hitachi             | 125      | 154    | 8.84%   |
| Toshiba             | 114      | 186    | 8.06%   |
| Samsung Electronics | 101      | 134    | 7.14%   |
| Maxtor              | 40       | 57     | 2.83%   |
| HGST                | 17       | 25     | 1.2%    |
| Unknown             | 14       | 18     | 0.99%   |
| SABRENT             | 6        | 6      | 0.42%   |
| USB3.0              | 3        | 4      | 0.21%   |
| Hewlett-Packard     | 3        | 6      | 0.21%   |
| Apple               | 3        | 3      | 0.21%   |
| Quantum             | 1        | 1      | 0.07%   |
| Fujitsu             | 1        | 1      | 0.07%   |
| ExcelStor           | 1        | 1      | 0.07%   |
| ASMT109x            | 1        | 2      | 0.07%   |
| ASMT                | 1        | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 163      | 234    | 19.52%  |
| Kingston            | 141      | 181    | 16.89%  |
| SanDisk             | 85       | 104    | 10.18%  |
| Crucial             | 80       | 98     | 9.58%   |
| WDC                 | 36       | 42     | 4.31%   |
| A-DATA Technology   | 29       | 35     | 3.47%   |
| China               | 28       | 32     | 3.35%   |
| Intel               | 22       | 27     | 2.63%   |
| PNY                 | 21       | 28     | 2.51%   |
| OCZ                 | 15       | 18     | 1.8%    |
| Patriot             | 14       | 22     | 1.68%   |
| SPCC                | 12       | 14     | 1.44%   |
| Intenso             | 12       | 15     | 1.44%   |
| Micron Technology   | 9        | 10     | 1.08%   |
| Toshiba             | 8        | 9      | 0.96%   |
| Lexar               | 8        | 8      | 0.96%   |
| KingSpec            | 8        | 10     | 0.96%   |
| Gigabyte Technology | 8        | 15     | 0.96%   |
| Corsair             | 8        | 10     | 0.96%   |
| Apacer              | 8        | 9      | 0.96%   |
| Transcend           | 7        | 8      | 0.84%   |
| Leven               | 7        | 8      | 0.84%   |
| Hewlett-Packard     | 7        | 8      | 0.84%   |
| GOODRAM             | 7        | 7      | 0.84%   |
| JMicron Technology  | 6        | 10     | 0.72%   |
| SK hynix            | 5        | 5      | 0.6%    |
| Netac               | 5        | 6      | 0.6%    |
| Team                | 4        | 6      | 0.48%   |
| Super Talent        | 4        | 5      | 0.48%   |
| LITEON              | 4        | 5      | 0.48%   |
| Seagate             | 3        | 5      | 0.36%   |
| Plextor             | 3        | 4      | 0.36%   |
| Pioneer             | 3        | 3      | 0.36%   |
| Drevo               | 3        | 4      | 0.36%   |
| Acer                | 3        | 4      | 0.36%   |
| Zheino              | 2        | 2      | 0.24%   |
| Verbatim            | 2        | 2      | 0.24%   |
| TCSUNBOW            | 2        | 2      | 0.24%   |
| OWC                 | 2        | 2      | 0.24%   |
| Mushkin             | 2        | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1101     | 2016   | 51.54%  |
| SSD     | 707      | 1067   | 33.1%   |
| NVMe    | 257      | 361    | 12.03%  |
| Unknown | 64       | 85     | 3%      |
| MMC     | 7        | 8      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1436     | 3017   | 79.65%  |
| NVMe | 256      | 360    | 14.2%   |
| SAS  | 104      | 152    | 5.77%   |
| MMC  | 7        | 8      | 0.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1132     | 1849   | 59.08%  |
| 0.51-1.0   | 483      | 731    | 25.21%  |
| 1.01-2.0   | 165      | 243    | 8.61%   |
| 3.01-4.0   | 59       | 135    | 3.08%   |
| 4.01-10.0  | 42       | 61     | 2.19%   |
| 2.01-3.0   | 31       | 48     | 1.62%   |
| 10.01-20.0 | 4        | 16     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 477      | 30.09%  |
| 251-500        | 358      | 22.59%  |
| 501-1000       | 225      | 14.2%   |
| 51-100         | 130      | 8.2%    |
| 1001-2000      | 122      | 7.7%    |
| More than 3000 | 97       | 6.12%   |
| 21-50          | 68       | 4.29%   |
| 2001-3000      | 47       | 2.97%   |
| 1-20           | 47       | 2.97%   |
| Unknown        | 14       | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 718      | 43.44%  |
| 21-50          | 338      | 20.45%  |
| 51-100         | 185      | 11.19%  |
| 101-250        | 139      | 8.41%   |
| 251-500        | 85       | 5.14%   |
| 501-1000       | 68       | 4.11%   |
| 1001-2000      | 49       | 2.96%   |
| More than 3000 | 44       | 2.66%   |
| Unknown        | 14       | 0.85%   |
| 2001-3000      | 13       | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00V1A0 500GB          | 1        | 1      | 3.45%   |
| WDC WD3200AAKS-22B3A0 320GB          | 1        | 1      | 3.45%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 1      | 3.45%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1        | 2      | 3.45%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 1      | 3.45%   |
| Toshiba MK8046GSX 80GB               | 1        | 1      | 3.45%   |
| Toshiba MK3265GSX 320GB              | 1        | 1      | 3.45%   |
| Toshiba MG03ACA200 2TB               | 1        | 1      | 3.45%   |
| Silicon Motion Inland NVMe SSD 256GB | 1        | 1      | 3.45%   |
| Seagate ST9500420AS 500GB            | 1        | 1      | 3.45%   |
| Seagate ST8000DM004-2CX188 8TB       | 1        | 1      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1      | 3.45%   |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 1      | 3.45%   |
| Seagate ST3500514NS 500GB            | 1        | 1      | 3.45%   |
| Seagate ST3500413AS 500GB            | 1        | 1      | 3.45%   |
| Seagate ST3320620AS 320GB            | 1        | 1      | 3.45%   |
| Seagate ST3250318AS 249GB            | 1        | 1      | 3.45%   |
| Seagate ST320LT012-1DG14C 320GB      | 1        | 1      | 3.45%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 1      | 3.45%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1      | 3.45%   |
| Seagate ST2000DM001-9YN164 2TB       | 1        | 1      | 3.45%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1      | 3.45%   |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 1      | 3.45%   |
| Samsung Electronics HD154UI 1TB      | 1        | 1      | 3.45%   |
| OCZ VERTEX3 120GB SSD                | 1        | 1      | 3.45%   |
| Kingston SNS4151S316GD 16GB SSD      | 1        | 1      | 3.45%   |
| Intel SSDSC2CW060A3 64GB             | 1        | 1      | 3.45%   |
| A-DATA Technology SX8200PNP 256GB    | 1        | 1      | 3.45%   |
| A-DATA Technology SU630 240GB SSD    | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 14     | 46.43%  |
| WDC                 | 5        | 6      | 17.86%  |
| Toshiba             | 3        | 3      | 10.71%  |
| A-DATA Technology   | 2        | 2      | 7.14%   |
| Silicon Motion      | 1        | 1      | 3.57%   |
| Samsung Electronics | 1        | 1      | 3.57%   |
| OCZ                 | 1        | 1      | 3.57%   |
| Kingston            | 1        | 1      | 3.57%   |
| Intel               | 1        | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 14     | 59.09%  |
| WDC                 | 5        | 6      | 22.73%  |
| Toshiba             | 3        | 3      | 13.64%  |
| Samsung Electronics | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 24     | 76.92%  |
| SSD  | 4        | 4      | 15.38%  |
| NVMe | 2        | 2      | 7.69%   |

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
| Detected | 1438     | 3262   | 92.54%  |
| Works    | 90       | 245    | 5.79%   |
| Malfunc  | 26       | 30     | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 979      | 50.03%  |
| AMD                              | 440      | 22.48%  |
| Samsung Electronics              | 86       | 4.39%   |
| Nvidia                           | 78       | 3.99%   |
| JMicron Technology               | 51       | 2.61%   |
| ASMedia Technology               | 51       | 2.61%   |
| Phison Electronics               | 38       | 1.94%   |
| SanDisk                          | 37       | 1.89%   |
| Marvell Technology Group         | 33       | 1.69%   |
| Silicon Motion                   | 27       | 1.38%   |
| VIA Technologies                 | 24       | 1.23%   |
| Kingston Technology Company      | 24       | 1.23%   |
| Silicon Image                    | 12       | 0.61%   |
| Micron/Crucial Technology        | 11       | 0.56%   |
| ADATA Technology                 | 9        | 0.46%   |
| SK hynix                         | 7        | 0.36%   |
| Silicon Integrated Systems [SiS] | 6        | 0.31%   |
| Realtek Semiconductor            | 6        | 0.31%   |
| Broadcom / LSI                   | 6        | 0.31%   |
| Toshiba America Info Systems     | 4        | 0.2%    |
| Seagate Technology               | 4        | 0.2%    |
| KIOXIA                           | 3        | 0.15%   |
| OCZ Technology Group             | 2        | 0.1%    |
| Micron Technology                | 2        | 0.1%    |
| MAXIO Technology (Hangzhou)      | 2        | 0.1%    |
| INNOGRIT                         | 2        | 0.1%    |
| Apple                            | 2        | 0.1%    |
| Union Memory (Shenzhen)          | 1        | 0.05%   |
| Promise Technology               | 1        | 0.05%   |
| Netac Technology                 | 1        | 0.05%   |
| LSI Logic / Symbios Logic        | 1        | 0.05%   |
| Lite-On Technology               | 1        | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.05%   |
| Integrated Technology Express    | 1        | 0.05%   |
| Hewlett-Packard                  | 1        | 0.05%   |
| Beijing Starblaze Technology     | 1        | 0.05%   |
| Adaptec                          | 1        | 0.05%   |
| Unknown                          | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 224      | 8.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 132      | 5.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 119      | 4.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 107      | 4.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 96       | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 95       | 3.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 77       | 2.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 75       | 2.85%   |
| Intel SATA Controller [RAID mode]                                                       | 66       | 2.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 66       | 2.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 61       | 2.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 50       | 1.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 48       | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 45       | 1.71%   |
| Nvidia MCP61 SATA Controller                                                            | 42       | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 40       | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 39       | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 33       | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 33       | 1.26%   |
| Nvidia MCP61 IDE                                                                        | 29       | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 29       | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 29       | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 25       | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 25       | 0.95%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 24       | 0.91%   |
| AMD FCH SATA Controller D                                                               | 23       | 0.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 22       | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 21       | 0.8%    |
| Phison E12 NVMe Controller                                                              | 21       | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 21       | 0.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 21       | 0.8%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 20       | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 20       | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 19       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 19       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 19       | 0.72%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 19       | 0.72%   |
| AMD 300 Series Chipset SATA Controller                                                  | 19       | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 17       | 0.65%   |
| JMicron JMB368 IDE controller                                                           | 17       | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1067     | 52.56%  |
| IDE  | 578      | 28.47%  |
| NVMe | 255      | 12.56%  |
| RAID | 117      | 5.76%   |
| SAS  | 7        | 0.34%   |
| SCSI | 6        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1013     | 66.51%  |
| AMD    | 510      | 33.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 33       | 2.16%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 26       | 1.7%    |
| AMD Ryzen 5 3600 6-Core Processor           | 22       | 1.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 19       | 1.24%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 16       | 1.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 15       | 0.98%   |
| Intel Pentium 4 CPU 3.00GHz                 | 14       | 0.92%   |
| AMD FX-6300 Six-Core Processor              | 14       | 0.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 13       | 0.85%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 13       | 0.85%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 13       | 0.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 12       | 0.78%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 12       | 0.78%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 12       | 0.78%   |
| AMD FX-8350 Eight-Core Processor            | 12       | 0.78%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 11       | 0.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 11       | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11       | 0.72%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 11       | 0.72%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 11       | 0.72%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 11       | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 11       | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 11       | 0.72%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 10       | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10       | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 10       | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 10       | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 10       | 0.65%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 10       | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 0.65%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 9        | 0.59%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 9        | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 0.59%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 9        | 0.59%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 9        | 0.59%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 9        | 0.59%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 8        | 0.52%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 8        | 0.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 8        | 0.52%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 8        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 260      | 17.02%  |
| Intel Core i7           | 143      | 9.36%   |
| Intel Core i3           | 117      | 7.66%   |
| AMD Ryzen 5             | 87       | 5.69%   |
| Intel Core 2 Duo        | 81       | 5.3%    |
| Intel Xeon              | 72       | 4.71%   |
| AMD FX                  | 67       | 4.38%   |
| Intel Core 2 Quad       | 57       | 3.73%   |
| AMD Ryzen 7             | 57       | 3.73%   |
| Intel Celeron           | 50       | 3.27%   |
| Intel Pentium Dual-Core | 44       | 2.88%   |
| Intel Pentium Dual      | 39       | 2.55%   |
| Intel Pentium           | 37       | 2.42%   |
| Intel Pentium 4         | 34       | 2.23%   |
| AMD Athlon 64 X2        | 32       | 2.09%   |
| AMD Athlon II X2        | 29       | 1.9%    |
| Other                   | 28       | 1.83%   |
| AMD Ryzen 9             | 27       | 1.77%   |
| AMD Ryzen 3             | 24       | 1.57%   |
| AMD Phenom II X4        | 22       | 1.44%   |
| AMD A8                  | 20       | 1.31%   |
| Intel Core 2            | 17       | 1.11%   |
| AMD Athlon              | 14       | 0.92%   |
| AMD A6                  | 14       | 0.92%   |
| AMD A4                  | 14       | 0.92%   |
| AMD A10                 | 14       | 0.92%   |
| Intel Core i9           | 12       | 0.79%   |
| AMD Sempron             | 12       | 0.79%   |
| AMD Athlon II X4        | 12       | 0.79%   |
| Intel Pentium D         | 9        | 0.59%   |
| AMD Phenom II X6        | 9        | 0.59%   |
| AMD Athlon II X3        | 8        | 0.52%   |
| Intel Atom              | 7        | 0.46%   |
| AMD Athlon 64           | 7        | 0.46%   |
| AMD Phenom              | 6        | 0.39%   |
| Intel Pentium Gold      | 5        | 0.33%   |
| AMD Phenom II X2        | 4        | 0.26%   |
| AMD Ryzen Threadripper  | 3        | 0.2%    |
| AMD PRO A10             | 3        | 0.2%    |
| AMD E1                  | 3        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 588      | 38.46%  |
| 2      | 527      | 34.47%  |
| 6      | 145      | 9.48%   |
| 8      | 102      | 6.67%   |
| 1      | 90       | 5.89%   |
| 3      | 31       | 2.03%   |
| 12     | 23       | 1.5%    |
| 16     | 12       | 0.78%   |
| 10     | 10       | 0.65%   |
| 20     | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1511     | 99.21%  |
| 2      | 12       | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 832      | 54.59%  |
| 2      | 692      | 45.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1495     | 98.16%  |
| 32-bit         | 27       | 1.77%   |
| Unknown        | 1        | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 153      | 9.86%   |
| 0x306c3    | 143      | 9.22%   |
| 0x1067a    | 126      | 8.12%   |
| 0x206a7    | 114      | 7.35%   |
| 0x306a9    | 101      | 6.51%   |
| 0x506e3    | 49       | 3.16%   |
| 0x06000852 | 49       | 3.16%   |
| 0x6fd      | 48       | 3.09%   |
| 0x08701021 | 42       | 2.71%   |
| 0x010000c8 | 35       | 2.26%   |
| 0x6fb      | 30       | 1.93%   |
| 0x906e9    | 26       | 1.68%   |
| 0x0800820d | 26       | 1.68%   |
| 0x06001119 | 26       | 1.68%   |
| 0x906ea    | 23       | 1.48%   |
| 0x10676    | 18       | 1.16%   |
| 0x0a201016 | 18       | 1.16%   |
| 0x010000db | 18       | 1.16%   |
| 0x0600063e | 17       | 1.1%    |
| 0xa0655    | 16       | 1.03%   |
| 0xa0653    | 16       | 1.03%   |
| 0x906ed    | 15       | 0.97%   |
| 0x20655    | 15       | 0.97%   |
| 0x106e5    | 15       | 0.97%   |
| 0x06003106 | 14       | 0.9%    |
| 0xa0671    | 13       | 0.84%   |
| 0x906eb    | 12       | 0.77%   |
| 0x106a5    | 12       | 0.77%   |
| 0x6f6      | 11       | 0.71%   |
| 0x20652    | 11       | 0.71%   |
| 0x08701013 | 11       | 0.71%   |
| 0x08108109 | 11       | 0.71%   |
| 0x010000dc | 11       | 0.71%   |
| 0xf41      | 10       | 0.64%   |
| 0x206d7    | 10       | 0.64%   |
| 0x08101016 | 10       | 0.64%   |
| 0x0700010f | 10       | 0.64%   |
| 0x0a201009 | 9        | 0.58%   |
| 0x03000027 | 9        | 0.58%   |
| 0xf43      | 8        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 163      | 10.68%  |
| Penryn           | 154      | 10.09%  |
| SandyBridge      | 128      | 8.39%   |
| IvyBridge        | 110      | 7.21%   |
| Core             | 105      | 6.88%   |
| K10              | 95       | 6.23%   |
| KabyLake         | 86       | 5.64%   |
| Piledriver       | 79       | 5.18%   |
| Zen 2            | 65       | 4.26%   |
| Skylake          | 54       | 3.54%   |
| K8 Hammer        | 54       | 3.54%   |
| NetBurst         | 51       | 3.34%   |
| Zen+             | 48       | 3.15%   |
| Zen 3            | 47       | 3.08%   |
| Zen              | 46       | 3.01%   |
| Westmere         | 35       | 2.29%   |
| Nehalem          | 33       | 2.16%   |
| CometLake        | 33       | 2.16%   |
| Silvermont       | 19       | 1.25%   |
| Bulldozer        | 17       | 1.11%   |
| Steamroller      | 14       | 0.92%   |
| Jaguar           | 11       | 0.72%   |
| Excavator        | 11       | 0.72%   |
| Icelake          | 10       | 0.66%   |
| K10 Llano        | 9        | 0.59%   |
| Alderlake Hybrid | 9        | 0.59%   |
| Unknown          | 9        | 0.59%   |
| Puma             | 6        | 0.39%   |
| Goldmont plus    | 5        | 0.33%   |
| Broadwell        | 5        | 0.33%   |
| Bonnell          | 5        | 0.33%   |
| Bobcat           | 4        | 0.26%   |
| K6               | 3        | 0.2%    |
| TigerLake        | 1        | 0.07%   |
| P6               | 1        | 0.07%   |
| Goldmont         | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 604      | 37.47%  |
| Intel                            | 512      | 31.76%  |
| AMD                              | 484      | 30.02%  |
| VIA Technologies                 | 7        | 0.43%   |
| Silicon Integrated Systems [SiS] | 2        | 0.12%   |
| Trident Microsystems             | 1        | 0.06%   |
| Silicon Motion                   | 1        | 0.06%   |
| Matrox Electronics Systems       | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 76       | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 66       | 3.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 54       | 3.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 52       | 3.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 48       | 2.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 44       | 2.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 27       | 1.63%   |
| Intel HD Graphics 530                                                                    | 27       | 1.63%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27       | 1.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 26       | 1.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 24       | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22       | 1.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 21       | 1.27%   |
| AMD RS780L [Radeon 3000]                                                                 | 21       | 1.27%   |
| Nvidia GT218 [GeForce 210]                                                               | 19       | 1.15%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 18       | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18       | 1.09%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 18       | 1.09%   |
| Intel HD Graphics 630                                                                    | 17       | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16       | 0.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 14       | 0.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 14       | 0.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 14       | 0.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13       | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 13       | 0.79%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 13       | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 12       | 0.73%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 12       | 0.73%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 11       | 0.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 11       | 0.67%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 11       | 0.67%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 11       | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 10       | 0.6%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 10       | 0.6%    |
| Nvidia G96C [GeForce 9500 GT]                                                            | 10       | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10       | 0.6%    |
| AMD RS880 [Radeon HD 4200]                                                               | 10       | 0.6%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 9        | 0.54%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 9        | 0.54%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 9        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 571      | 37.25%  |
| 1 x Intel                | 450      | 29.35%  |
| 1 x AMD                  | 434      | 28.31%  |
| 2 x AMD                  | 28       | 1.83%   |
| Intel + Nvidia           | 16       | 1.04%   |
| Intel + AMD              | 12       | 0.78%   |
| 1 x VIA                  | 7        | 0.46%   |
| AMD + Nvidia             | 7        | 0.46%   |
| 2 x Nvidia               | 3        | 0.2%    |
| 1 x SiS                  | 2        | 0.13%   |
| 1 x Trident Microsystems | 1        | 0.07%   |
| Nvidia + Silicon Motion  | 1        | 0.07%   |
| 1 x Matrox               | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1075     | 69.71%  |
| Proprietary | 355      | 23.02%  |
| Unknown     | 112      | 7.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 627      | 40.12%  |
| 0.01-0.5   | 240      | 15.36%  |
| 1.01-2.0   | 215      | 13.76%  |
| 0.51-1.0   | 211      | 13.5%   |
| 3.01-4.0   | 105      | 6.72%   |
| 7.01-8.0   | 89       | 5.69%   |
| 5.01-6.0   | 32       | 2.05%   |
| 8.01-16.0  | 28       | 1.79%   |
| 2.01-3.0   | 11       | 0.7%    |
| 16.01-24.0 | 4        | 0.26%   |
| 4.01-5.0   | 1        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 224      | 15.07%  |
| Dell                 | 149      | 10.03%  |
| Goldstar             | 144      | 9.69%   |
| Hewlett-Packard      | 126      | 8.48%   |
| Acer                 | 101      | 6.8%    |
| AOC                  | 78       | 5.25%   |
| Philips              | 72       | 4.85%   |
| Ancor Communications | 62       | 4.17%   |
| BenQ                 | 54       | 3.63%   |
| LG Electronics       | 40       | 2.69%   |
| ViewSonic            | 34       | 2.29%   |
| Unknown              | 31       | 2.09%   |
| Lenovo               | 17       | 1.14%   |
| Sony                 | 16       | 1.08%   |
| Iiyama               | 16       | 1.08%   |
| Unknown              | 15       | 1.01%   |
| ASUSTek Computer     | 14       | 0.94%   |
| Vizio                | 13       | 0.87%   |
| Sceptre Tech         | 13       | 0.87%   |
| NEC Computers        | 13       | 0.87%   |
| HPN                  | 10       | 0.67%   |
| Fujitsu Siemens      | 10       | 0.67%   |
| Eizo                 | 10       | 0.67%   |
| Toshiba              | 8        | 0.54%   |
| HannStar             | 7        | 0.47%   |
| Gateway              | 7        | 0.47%   |
| AUS                  | 7        | 0.47%   |
| Sharp                | 6        | 0.4%    |
| Medion               | 6        | 0.4%    |
| MSI                  | 5        | 0.34%   |
| Microstep            | 5        | 0.34%   |
| Idek Iiyama          | 5        | 0.34%   |
| FUS                  | 5        | 0.34%   |
| Envision             | 5        | 0.34%   |
| CVT                  | 5        | 0.34%   |
| ___                  | 4        | 0.27%   |
| VIZ                  | 4        | 0.27%   |
| Panasonic            | 4        | 0.27%   |
| MStar                | 4        | 0.27%   |
| KTC                  | 4        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 15       | 0.96%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 7        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6        | 0.38%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 5        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 4        | 0.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4        | 0.25%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch               | 4        | 0.25%   |
| Philips LCD Monitor FTV 1920x1080                                     | 4        | 0.25%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 4        | 0.25%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 4        | 0.25%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 4        | 0.25%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 4        | 0.25%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 4        | 0.25%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 4        | 0.25%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 0.25%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                    | 3        | 0.19%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                             | 3        | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3        | 0.19%   |
| Unknown LCD Monitor SAMSUNG                                           | 3        | 0.19%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 3        | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch  | 3        | 0.19%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch               | 3        | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.19%   |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                     | 3        | 0.19%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 3        | 0.19%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 3        | 0.19%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                      | 3        | 0.19%   |
| Hewlett-Packard LP2065 HWP0A72 1600x1200 408x306mm 20.1-inch          | 3        | 0.19%   |
| Hewlett-Packard 24fw HPN3546 1920x1080 527x296mm 23.8-inch            | 3        | 0.19%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 3        | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 0.19%   |
| GDH Digital TV GDH0030 1920x540                                       | 3        | 0.19%   |
| Dell ST2010 DELF019 1600x900 443x249mm 20.0-inch                      | 3        | 0.19%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 3        | 0.19%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                     | 3        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 599      | 40.78%  |
| 1280x1024 (SXGA)   | 120      | 8.17%   |
| 3840x2160 (4K)     | 103      | 7.01%   |
| 1680x1050 (WSXGA+) | 85       | 5.79%   |
| 1366x768 (WXGA)    | 77       | 5.24%   |
| 1600x900 (HD+)     | 73       | 4.97%   |
| 1440x900 (WXGA+)   | 65       | 4.42%   |
| Unknown            | 61       | 4.15%   |
| 2560x1440 (QHD)    | 54       | 3.68%   |
| 1360x768           | 47       | 3.2%    |
| 1920x1200 (WUXGA)  | 30       | 2.04%   |
| 3840x1080          | 23       | 1.57%   |
| 3440x1440          | 19       | 1.29%   |
| 1920x540           | 15       | 1.02%   |
| 1024x768 (XGA)     | 14       | 0.95%   |
| 2560x1080          | 12       | 0.82%   |
| 1600x1200          | 7        | 0.48%   |
| 5760x1080          | 5        | 0.34%   |
| 4480x1440          | 4        | 0.27%   |
| 3840x1600          | 4        | 0.27%   |
| 1280x720 (HD)      | 4        | 0.27%   |
| 5760x2160          | 3        | 0.2%    |
| 3600x1080          | 3        | 0.2%    |
| 2560x1600          | 3        | 0.2%    |
| 6400x1440          | 2        | 0.14%   |
| 5440x1080          | 2        | 0.14%   |
| 3360x1080          | 2        | 0.14%   |
| 3200x1200          | 2        | 0.14%   |
| 3200x1080          | 2        | 0.14%   |
| 3120x1050          | 2        | 0.14%   |
| 2944x1080          | 2        | 0.14%   |
| 2720x1024          | 2        | 0.14%   |
| 2048x1152          | 2        | 0.14%   |
| 1152x864           | 2        | 0.14%   |
| 7680x1080          | 1        | 0.07%   |
| 6400x1080          | 1        | 0.07%   |
| 5040x1050          | 1        | 0.07%   |
| 4480x1600          | 1        | 0.07%   |
| 4480x1080          | 1        | 0.07%   |
| 4160x1440          | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 294      | 20.18%  |
| 21      | 127      | 8.72%   |
| 24      | 124      | 8.51%   |
| 23      | 124      | 8.51%   |
| 27      | 120      | 8.24%   |
| 19      | 112      | 7.69%   |
| 18      | 84       | 5.77%   |
| 20      | 76       | 5.22%   |
| 31      | 60       | 4.12%   |
| 22      | 60       | 4.12%   |
| 17      | 60       | 4.12%   |
| 15      | 24       | 1.65%   |
| 34      | 23       | 1.58%   |
| 40      | 20       | 1.37%   |
| 84      | 18       | 1.24%   |
| 72      | 15       | 1.03%   |
| 54      | 15       | 1.03%   |
| 32      | 13       | 0.89%   |
| 26      | 13       | 0.89%   |
| 52      | 7        | 0.48%   |
| 25      | 6        | 0.41%   |
| 65      | 5        | 0.34%   |
| 42      | 5        | 0.34%   |
| 36      | 5        | 0.34%   |
| 33      | 4        | 0.27%   |
| 39      | 3        | 0.21%   |
| 37      | 3        | 0.21%   |
| 28      | 3        | 0.21%   |
| 74      | 2        | 0.14%   |
| 60      | 2        | 0.14%   |
| 57      | 2        | 0.14%   |
| 55      | 2        | 0.14%   |
| 49      | 2        | 0.14%   |
| 48      | 2        | 0.14%   |
| 47      | 2        | 0.14%   |
| 46      | 2        | 0.14%   |
| 43      | 2        | 0.14%   |
| 41      | 2        | 0.14%   |
| 35      | 2        | 0.14%   |
| 29      | 2        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 393      | 27.79%  |
| 501-600     | 345      | 24.4%   |
| Unknown     | 294      | 20.79%  |
| 301-350     | 81       | 5.73%   |
| 601-700     | 75       | 5.3%    |
| 351-400     | 63       | 4.46%   |
| 701-800     | 45       | 3.18%   |
| 1001-1500   | 40       | 2.83%   |
| 1501-2000   | 38       | 2.69%   |
| 801-900     | 28       | 1.98%   |
| 901-1000    | 10       | 0.71%   |
| 201-300     | 2        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 748      | 54.88%  |
| Unknown | 268      | 19.66%  |
| 16/10   | 171      | 12.55%  |
| 5/4     | 107      | 7.85%   |
| 21/9    | 28       | 2.05%   |
| 4/3     | 23       | 1.69%   |
| 32/9    | 9        | 0.66%   |
| 6/5     | 5        | 0.37%   |
| 3/2     | 4        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 344      | 23.96%  |
| Unknown        | 294      | 20.47%  |
| 151-200        | 244      | 16.99%  |
| 301-350        | 122      | 8.5%    |
| 141-150        | 119      | 8.29%   |
| 351-500        | 107      | 7.45%   |
| More than 1000 | 69       | 4.81%   |
| 251-300        | 55       | 3.83%   |
| 501-1000       | 47       | 3.27%   |
| 101-110        | 20       | 1.39%   |
| 131-140        | 7        | 0.49%   |
| 111-120        | 4        | 0.28%   |
| 91-100         | 2        | 0.14%   |
| 81-90          | 1        | 0.07%   |
| 121-130        | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 779      | 56.61%  |
| Unknown | 294      | 21.37%  |
| 101-120 | 192      | 13.95%  |
| 1-50    | 69       | 5.01%   |
| 121-160 | 28       | 2.03%   |
| 161-240 | 14       | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1248     | 80.52%  |
| 2     | 171      | 11.03%  |
| 0     | 108      | 6.97%   |
| 3     | 21       | 1.35%   |
| 4     | 2        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 929      | 41%     |
| Intel                                 | 536      | 23.65%  |
| Qualcomm Atheros                      | 145      | 6.4%    |
| Ralink Technology                     | 89       | 3.93%   |
| Broadcom                              | 87       | 3.84%   |
| Nvidia                                | 67       | 2.96%   |
| TP-Link                               | 46       | 2.03%   |
| Ralink                                | 36       | 1.59%   |
| Broadcom Limited                      | 31       | 1.37%   |
| Marvell Technology Group              | 26       | 1.15%   |
| MediaTek                              | 21       | 0.93%   |
| VIA Technologies                      | 20       | 0.88%   |
| D-Link                                | 20       | 0.88%   |
| NetGear                               | 18       | 0.79%   |
| D-Link System                         | 18       | 0.79%   |
| Samsung Electronics                   | 16       | 0.71%   |
| Xiaomi                                | 12       | 0.53%   |
| Qualcomm Atheros Communications       | 12       | 0.53%   |
| Huawei Technologies                   | 11       | 0.49%   |
| Microsoft                             | 10       | 0.44%   |
| Edimax Technology                     | 9        | 0.4%    |
| ASUSTek Computer                      | 8        | 0.35%   |
| Aquantia                              | 7        | 0.31%   |
| Belkin Components                     | 6        | 0.26%   |
| ASIX Electronics                      | 6        | 0.26%   |
| Silicon Integrated Systems [SiS]      | 5        | 0.22%   |
| Linksys                               | 5        | 0.22%   |
| Qualcomm                              | 4        | 0.18%   |
| Motorola PCS                          | 4        | 0.18%   |
| Gemtek                                | 4        | 0.18%   |
| DisplayLink                           | 4        | 0.18%   |
| Sitecom Europe                        | 3        | 0.13%   |
| OPPO Electronics                      | 3        | 0.13%   |
| JMicron Technology                    | 3        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM            | 2        | 0.09%   |
| TRENDnet                              | 2        | 0.09%   |
| Sundance Technology Inc / IC Plus     | 2        | 0.09%   |
| Senao                                 | 2        | 0.09%   |
| Motorola                              | 2        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 693      | 27.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 84       | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67       | 2.64%   |
| Intel I211 Gigabit Network Connection                             | 57       | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 48       | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 46       | 1.81%   |
| Nvidia MCP61 Ethernet                                             | 40       | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 40       | 1.58%   |
| Ralink MT7601U Wireless Adapter                                   | 39       | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 34       | 1.34%   |
| Realtek 802.11ac NIC                                              | 29       | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 28       | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 27       | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 22       | 0.87%   |
| Intel Ethernet Controller I225-V                                  | 21       | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21       | 0.83%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 20       | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 18       | 0.71%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 18       | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 17       | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17       | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 17       | 0.67%   |
| Intel Wireless 7265                                               | 15       | 0.59%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 14       | 0.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 14       | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 14       | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14       | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14       | 0.55%   |
| Intel Wireless-AC 9260                                            | 14       | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 13       | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 13       | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 12       | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11       | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11       | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 218      | 26.42%  |
| Intel                                 | 175      | 21.21%  |
| Ralink Technology                     | 89       | 10.79%  |
| Qualcomm Atheros                      | 72       | 8.73%   |
| TP-Link                               | 44       | 5.33%   |
| Ralink                                | 36       | 4.36%   |
| Broadcom                              | 36       | 4.36%   |
| D-Link                                | 20       | 2.42%   |
| NetGear                               | 18       | 2.18%   |
| D-Link System                         | 14       | 1.7%    |
| MediaTek                              | 13       | 1.58%   |
| Qualcomm Atheros Communications       | 12       | 1.45%   |
| Broadcom Limited                      | 11       | 1.33%   |
| Microsoft                             | 10       | 1.21%   |
| Edimax Technology                     | 9        | 1.09%   |
| ASUSTek Computer                      | 7        | 0.85%   |
| Belkin Components                     | 6        | 0.73%   |
| Linksys                               | 5        | 0.61%   |
| Marvell Technology Group              | 4        | 0.48%   |
| Gemtek                                | 4        | 0.48%   |
| Sitecom Europe                        | 3        | 0.36%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.36%   |
| TRENDnet                              | 2        | 0.24%   |
| Senao                                 | 2        | 0.24%   |
| Micro Star International              | 2        | 0.24%   |
| AVM                                   | 2        | 0.24%   |
| ZyXEL Communications                  | 1        | 0.12%   |
| ZyDAS                                 | 1        | 0.12%   |
| Xiaomi                                | 1        | 0.12%   |
| Philips (or NXP)                      | 1        | 0.12%   |
| Panasonic (Matsushita)                | 1        | 0.12%   |
| Ovislink                              | 1        | 0.12%   |
| IMC Networks                          | 1        | 0.12%   |
| ADMtek                                | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 46       | 5.5%    |
| Ralink MT7601U Wireless Adapter                                | 39       | 4.67%   |
| Realtek 802.11ac NIC                                           | 29       | 3.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 28       | 3.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 22       | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 20       | 2.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 17       | 2.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17       | 2.03%   |
| Intel Wireless 7265                                            | 15       | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 14       | 1.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 14       | 1.67%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14       | 1.67%   |
| Intel Wireless-AC 9260                                         | 14       | 1.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 13       | 1.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 13       | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9        | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 1.08%   |
| Intel Wireless 8260                                            | 9        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9        | 1.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 8        | 0.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 8        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8        | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8        | 0.96%   |
| Intel Wireless 7260                                            | 8        | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7        | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 7        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7        | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7        | 0.84%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 7        | 0.84%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 7        | 0.84%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 6        | 0.72%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 6        | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 6        | 0.72%   |
| NetGear A6210                                                  | 6        | 0.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 0.72%   |
| Intel Wireless 3165                                            | 6        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 846      | 51.68%  |
| Intel                             | 438      | 26.76%  |
| Qualcomm Atheros                  | 76       | 4.64%   |
| Nvidia                            | 67       | 4.09%   |
| Broadcom                          | 51       | 3.12%   |
| Marvell Technology Group          | 22       | 1.34%   |
| Broadcom Limited                  | 21       | 1.28%   |
| VIA Technologies                  | 20       | 1.22%   |
| Samsung Electronics               | 16       | 0.98%   |
| Xiaomi                            | 11       | 0.67%   |
| Huawei Technologies               | 10       | 0.61%   |
| MediaTek                          | 8        | 0.49%   |
| Aquantia                          | 7        | 0.43%   |
| ASIX Electronics                  | 6        | 0.37%   |
| Silicon Integrated Systems [SiS]  | 5        | 0.31%   |
| Qualcomm                          | 4        | 0.24%   |
| DisplayLink                       | 4        | 0.24%   |
| D-Link System                     | 4        | 0.24%   |
| OPPO Electronics                  | 3        | 0.18%   |
| JMicron Technology                | 3        | 0.18%   |
| TP-Link                           | 2        | 0.12%   |
| Sundance Technology Inc / IC Plus | 2        | 0.12%   |
| Motorola PCS                      | 2        | 0.12%   |
| Apple                             | 2        | 0.12%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.06%   |
| Research In Motion                | 1        | 0.06%   |
| HMD Global                        | 1        | 0.06%   |
| Google                            | 1        | 0.06%   |
| GCT Semiconductor                 | 1        | 0.06%   |
| ASUSTek Computer                  | 1        | 0.06%   |
| 3Com                              | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 693      | 41.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 84       | 5.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67       | 4%      |
| Intel I211 Gigabit Network Connection                             | 57       | 3.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 48       | 2.86%   |
| Nvidia MCP61 Ethernet                                             | 40       | 2.39%   |
| Intel Ethernet Connection I217-LM                                 | 40       | 2.39%   |
| Intel Ethernet Connection (2) I219-V                              | 34       | 2.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 27       | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 21       | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21       | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 20       | 1.19%   |
| Intel Ethernet Connection (2) I218-V                              | 18       | 1.07%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 18       | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 17       | 1.01%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 14       | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14       | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 0.84%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10       | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 10       | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10       | 0.6%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 9        | 0.54%   |
| Nvidia MCP73 Ethernet                                             | 9        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8        | 0.48%   |
| Intel 82578DC Gigabit Network Connection                          | 8        | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 0.42%   |
| Intel NM10/ICH7 Family LAN Controller                             | 7        | 0.42%   |
| Intel 82578DM Gigabit Network Connection                          | 7        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6        | 0.36%   |
| Nvidia MCP51 Ethernet Controller                                  | 6        | 0.36%   |
| MediaTek File-CD Gadget                                           | 6        | 0.36%   |
| Intel 82562V-2 10/100 Network Connection                          | 6        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1502     | 66.17%  |
| WiFi     | 745      | 32.82%  |
| Modem    | 18       | 0.79%   |
| Unknown  | 5        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1122     | 71.15%  |
| WiFi     | 453      | 28.73%  |
| Modem    | 1        | 0.06%   |
| Unknown  | 1        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1044     | 68.01%  |
| 2     | 427      | 27.82%  |
| 3     | 48       | 3.13%   |
| 0     | 10       | 0.65%   |
| 5     | 3        | 0.2%    |
| 4     | 2        | 0.13%   |
| 7     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1193     | 77.12%  |
| Yes  | 354      | 22.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 143      | 33.57%  |
| Cambridge Silicon Radio         | 101      | 23.71%  |
| Realtek Semiconductor           | 51       | 11.97%  |
| Broadcom                        | 30       | 7.04%   |
| ASUSTek Computer                | 20       | 4.69%   |
| Qualcomm Atheros Communications | 19       | 4.46%   |
| IMC Networks                    | 13       | 3.05%   |
| Apple                           | 9        | 2.11%   |
| MediaTek                        | 6        | 1.41%   |
| Dynex                           | 5        | 1.17%   |
| TP-Link                         | 4        | 0.94%   |
| Micro Star International        | 4        | 0.94%   |
| Integrated System Solution      | 4        | 0.94%   |
| Belkin Components               | 3        | 0.7%    |
| Foxconn / Hon Hai               | 2        | 0.47%   |
| Dell                            | 2        | 0.47%   |
| Sitecom Europe                  | 1        | 0.23%   |
| Realtek                         | 1        | 0.23%   |
| National Semiconductor          | 1        | 0.23%   |
| Logitech                        | 1        | 0.23%   |
| Lite-On Technology              | 1        | 0.23%   |
| Hewlett-Packard                 | 1        | 0.23%   |
| Fujitsu                         | 1        | 0.23%   |
| Edimax Technology               | 1        | 0.23%   |
| D-Link System                   | 1        | 0.23%   |
| Actions                         | 1        | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 101      | 23.71%  |
| Realtek Bluetooth Radio                                  | 41       | 9.62%   |
| Intel Bluetooth wireless interface                       | 36       | 8.45%   |
| Intel AX200 Bluetooth                                    | 34       | 7.98%   |
| Intel Wireless-AC 3168 Bluetooth                         | 19       | 4.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 15       | 3.52%   |
| Intel AX210 Bluetooth                                    | 15       | 3.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 11       | 2.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 10       | 2.35%   |
| IMC Networks Bluetooth Radio                             | 10       | 2.35%   |
| Intel Bluetooth Device                                   | 9        | 2.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 9        | 2.11%   |
| MediaTek Wireless_Device                                 | 6        | 1.41%   |
| Realtek RTL8821A Bluetooth                               | 5        | 1.17%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 5        | 1.17%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 5        | 1.17%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5        | 1.17%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 5        | 1.17%   |
| ASUS Bluetooth Radio                                     | 5        | 1.17%   |
| Apple Bluetooth USB Host Controller                      | 5        | 1.17%   |
| TP-Link TPuLink UB500 Adapter                            | 4        | 0.94%   |
| Realtek  Bluetooth 4.2 Adapter                           | 4        | 0.94%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 0.7%    |
| Micro Star International Bluetooth Device                | 3        | 0.7%    |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.7%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 3        | 0.7%    |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.7%    |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.47%   |
| Qualcomm Atheros Bluetooth                               | 2        | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.47%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 2        | 0.47%   |
| Integrated System Solution Bluetooth Device              | 2        | 0.47%   |
| IMC Networks Bluetooth Module                            | 2        | 0.47%   |
| Dell BT Mini-Receiver                                    | 2        | 0.47%   |
| Broadcom Bluetooth 2.0+eDR dongle                        | 2        | 0.47%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 2        | 0.47%   |
| Broadcom BCM92045B3 ROM                                  | 2        | 0.47%   |
| Broadcom BCM2045 Bluetooth                               | 2        | 0.47%   |
| ASUS ASUS USB-BT500                                      | 2        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 966      | 40.08%  |
| AMD                                  | 608      | 25.23%  |
| Nvidia                               | 547      | 22.7%   |
| C-Media Electronics                  | 63       | 2.61%   |
| Creative Labs                        | 30       | 1.24%   |
| VIA Technologies                     | 21       | 0.87%   |
| Logitech                             | 17       | 0.71%   |
| Kingston Technology                  | 12       | 0.5%    |
| JMTek                                | 11       | 0.46%   |
| Texas Instruments                    | 9        | 0.37%   |
| Razer USA                            | 8        | 0.33%   |
| GN Netcom                            | 8        | 0.33%   |
| Plantronics                          | 7        | 0.29%   |
| Generalplus Technology               | 7        | 0.29%   |
| ASUSTek Computer                     | 7        | 0.29%   |
| Silicon Integrated Systems [SiS]     | 6        | 0.25%   |
| Creative Technology                  | 5        | 0.21%   |
| Realtek Semiconductor                | 4        | 0.17%   |
| SteelSeries ApS                      | 3        | 0.12%   |
| Turtle Beach                         | 2        | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.08%   |
| Tenx Technology                      | 2        | 0.08%   |
| Samsung Electronics                  | 2        | 0.08%   |
| RODE Microphones                     | 2        | 0.08%   |
| Micronas                             | 2        | 0.08%   |
| Micro Star International             | 2        | 0.08%   |
| KTMicro                              | 2        | 0.08%   |
| Jieli Technology                     | 2        | 0.08%   |
| Ensoniq                              | 2        | 0.08%   |
| DSEA A/S                             | 2        | 0.08%   |
| DigiTech                             | 2        | 0.08%   |
| Corsair                              | 2        | 0.08%   |
| Cambridge Audio                      | 2        | 0.08%   |
| BEHRINGER International              | 2        | 0.08%   |
| Audio-Technica                       | 2        | 0.08%   |
| Astro Gaming                         | 2        | 0.08%   |
| XMOS                                 | 1        | 0.04%   |
| Valve Software                       | 1        | 0.04%   |
| Swissonic                            | 1        | 0.04%   |
| Silicon Labs                         | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 148      | 5.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 145      | 5.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 136      | 4.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 124      | 4.48%   |
| AMD Starship/Matisse HD Audio Controller                                          | 95       | 3.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 84       | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 79       | 2.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 77       | 2.78%   |
| AMD FCH Azalia Controller                                                         | 68       | 2.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 56       | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 54       | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 53       | 1.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 52       | 1.88%   |
| AMD Family 17h/19h HD Audio Controller                                            | 50       | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 43       | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                        | 42       | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 42       | 1.52%   |
| Nvidia MCP61 High Definition Audio                                                | 41       | 1.48%   |
| Intel 200 Series PCH HD Audio                                                     | 36       | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 35       | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                     | 35       | 1.26%   |
| Nvidia High Definition Audio Controller                                           | 32       | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 32       | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 31       | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 29       | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                | 28       | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 27       | 0.97%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 26       | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                     | 25       | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 24       | 0.87%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 23       | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 22       | 0.79%   |
| Nvidia GP104 High Definition Audio Controller                                     | 20       | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                | 20       | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                          | 20       | 0.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 19       | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                                     | 18       | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                     | 18       | 0.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 18       | 0.65%   |
| AMD Navi 10 HDMI Audio                                                            | 18       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 56       | 23.24%  |
| Kingston            | 34       | 14.11%  |
| Samsung Electronics | 25       | 10.37%  |
| Corsair             | 24       | 9.96%   |
| G.Skill             | 20       | 8.3%    |
| SK hynix            | 19       | 7.88%   |
| Crucial             | 17       | 7.05%   |
| Micron Technology   | 11       | 4.56%   |
| Elpida              | 6        | 2.49%   |
| Team                | 4        | 1.66%   |
| Ramaxel Technology  | 3        | 1.24%   |
| Patriot             | 3        | 1.24%   |
| Qimonda             | 2        | 0.83%   |
| Nanya Technology    | 2        | 0.83%   |
| Avant               | 2        | 0.83%   |
| A-DATA Technology   | 2        | 0.83%   |
| Unknown             | 2        | 0.83%   |
| Wilk                | 1        | 0.41%   |
| Unifosa             | 1        | 0.41%   |
| Ramos Technology    | 1        | 0.41%   |
| PNY                 | 1        | 0.41%   |
| Goldkey             | 1        | 0.41%   |
| F7852C80            | 1        | 0.41%   |
| CSX                 | 1        | 0.41%   |
| ASint Technology    | 1        | 0.41%   |
| AMD                 | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 1GB DIMM SDRAM                       | 4        | 1.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 3        | 1.14%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.76%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 2        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 2        | 0.76%   |
| Unknown RAM Module 4096MB DIMM                          | 2        | 0.76%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR2                        | 2        | 0.76%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2        | 0.76%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s             | 2        | 0.76%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 0.76%   |
| Unknown RAM Module 1024MB DIMM                          | 2        | 0.76%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s     | 2        | 0.76%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 2        | 0.76%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 0.76%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 0.76%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 0.76%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 2        | 0.76%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 0.76%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3              | 2        | 0.76%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.76%   |
| Kingston RAM KCM633-ELC 1024MB DIMM DDR2 2048MT/s       | 2        | 0.76%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 0.76%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s   | 2        | 0.76%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s     | 2        | 0.76%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s   | 2        | 0.76%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s    | 2        | 0.76%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 0.76%   |
| Unknown                                                 | 2        | 0.76%   |
| Wilk RAM IRX3200D464L16A/16G 16GB DIMM DDR4 3200MT/s    | 1        | 0.38%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM SDRAM                    | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 77       | 35.98%  |
| DDR4    | 74       | 34.58%  |
| Unknown | 23       | 10.75%  |
| DDR2    | 20       | 9.35%   |
| SDRAM   | 16       | 7.48%   |
| DDR     | 3        | 1.4%    |
| LPDDR4  | 1        | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 199      | 95.67%  |
| SODIMM       | 7        | 3.37%   |
| Row Of Chips | 1        | 0.48%   |
| FB-DIMM      | 1        | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 76       | 32.2%   |
| 4096  | 65       | 27.54%  |
| 2048  | 41       | 17.37%  |
| 1024  | 26       | 11.02%  |
| 16384 | 21       | 8.9%    |
| 32768 | 6        | 2.54%   |
| 512   | 1        | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 41       | 17.75%  |
| 1333    | 35       | 15.15%  |
| 3200    | 18       | 7.79%   |
| 3600    | 15       | 6.49%   |
| 800     | 15       | 6.49%   |
| Unknown | 13       | 5.63%   |
| 2133    | 9        | 3.9%    |
| 2400    | 7        | 3.03%   |
| 667     | 7        | 3.03%   |
| 3000    | 6        | 2.6%    |
| 1866    | 6        | 2.6%    |
| 2667    | 4        | 1.73%   |
| 2666    | 4        | 1.73%   |
| 1800    | 4        | 1.73%   |
| 1066    | 4        | 1.73%   |
| 333     | 4        | 1.73%   |
| 3866    | 3        | 1.3%    |
| 3466    | 3        | 1.3%    |
| 2800    | 3        | 1.3%    |
| 1867    | 3        | 1.3%    |
| 400     | 3        | 1.3%    |
| 3800    | 2        | 0.87%   |
| 3666    | 2        | 0.87%   |
| 3400    | 2        | 0.87%   |
| 3333    | 2        | 0.87%   |
| 2933    | 2        | 0.87%   |
| 2048    | 2        | 0.87%   |
| 49926   | 1        | 0.43%   |
| 4400    | 1        | 0.43%   |
| 4000    | 1        | 0.43%   |
| 3733    | 1        | 0.43%   |
| 3266    | 1        | 0.43%   |
| 3151    | 1        | 0.43%   |
| 2200    | 1        | 0.43%   |
| 2134    | 1        | 0.43%   |
| 1639    | 1        | 0.43%   |
| 1400    | 1        | 0.43%   |
| 976     | 1        | 0.43%   |
| 533     | 1        | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 23       | 28.4%   |
| Canon               | 18       | 22.22%  |
| Brother Industries  | 15       | 18.52%  |
| Seiko Epson         | 10       | 12.35%  |
| Samsung Electronics | 10       | 12.35%  |
| Toshiba TEC         | 1        | 1.23%   |
| STMicroelectronics  | 1        | 1.23%   |
| Ricoh               | 1        | 1.23%   |
| QinHeng Electronics | 1        | 1.23%   |
| Pantum              | 1        | 1.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Canon TS3100 series                                       | 3        | 3.7%    |
| Canon PIXMA MG2500 Series                                 | 3        | 3.7%    |
| Seiko Epson L3110 Series                                  | 2        | 2.47%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 2.47%   |
| HP ENVY 5000 series                                       | 2        | 2.47%   |
| HP ENVY 4520 series                                       | 2        | 2.47%   |
| HP DeskJet 2130 series                                    | 2        | 2.47%   |
| Canon MF4010 series                                       | 2        | 2.47%   |
| Brother HL-2130 series                                    | 2        | 2.47%   |
| Toshiba TEC e-STD120 USB                                  | 1        | 1.23%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.23%   |
| Seiko Epson XP-7100 Series                                | 1        | 1.23%   |
| Seiko Epson XP-200 Series                                 | 1        | 1.23%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 1.23%   |
| Seiko Epson L365 Series                                   | 1        | 1.23%   |
| Seiko Epson L355 Series                                   | 1        | 1.23%   |
| Seiko Epson L220 Series                                   | 1        | 1.23%   |
| Seiko Epson L120 Series                                   | 1        | 1.23%   |
| Seiko Epson ET-2820 Series                                | 1        | 1.23%   |
| Samsung SCX-483x 5x3x Series                              | 1        | 1.23%   |
| Samsung SCX-4200 series                                   | 1        | 1.23%   |
| Samsung SCX-3400 Series                                   | 1        | 1.23%   |
| Samsung ML-2950 Series                                    | 1        | 1.23%   |
| Samsung ML-2010P Mono Laser Printer                       | 1        | 1.23%   |
| Samsung M2070 Series                                      | 1        | 1.23%   |
| Samsung CLX-3300 Series                                   | 1        | 1.23%   |
| Samsung C460 Series                                       | 1        | 1.23%   |
| Ricoh SP C250SF                                           | 1        | 1.23%   |
| QinHeng CH340S                                            | 1        | 1.23%   |
| Pantum P2500W series                                      | 1        | 1.23%   |
| HP Smart Tank 510 series                                  | 1        | 1.23%   |
| HP PSC 1100 series                                        | 1        | 1.23%   |
| HP Officejet 6600                                         | 1        | 1.23%   |
| HP OfficeJet 4650 series                                  | 1        | 1.23%   |
| HP OfficeJet 3830 series                                  | 1        | 1.23%   |
| HP LaserJet Professional P1102w                           | 1        | 1.23%   |
| HP LaserJet Professional P 1102w                          | 1        | 1.23%   |
| HP LaserJet P2014                                         | 1        | 1.23%   |
| HP LaserJet P1102                                         | 1        | 1.23%   |
| HP LaserJet 3050                                          | 1        | 1.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 8        | 80%     |
| Hewlett-Packard | 2        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan LiDE 100            | 2        | 20%     |
| HP ScanJet 2400c                   | 1        | 10%     |
| HP PSC 1200                        | 1        | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 10%     |
| Canon CanoScan LiDE 60             | 1        | 10%     |
| Canon CanoScan LIDE 25             | 1        | 10%     |
| Canon CanoScan LiDE 110            | 1        | 10%     |
| Canon CanoScan D660U               | 1        | 10%     |
| Canon CanoScan 8800F               | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 59       | 27.7%   |
| Microdia                      | 19       | 8.92%   |
| Microsoft                     | 17       | 7.98%   |
| Apple                         | 14       | 6.57%   |
| Samsung Electronics           | 10       | 4.69%   |
| Sunplus Innovation Technology | 8        | 3.76%   |
| Generalplus Technology        | 8        | 3.76%   |
| Chicony Electronics           | 8        | 3.76%   |
| ARC International             | 6        | 2.82%   |
| Cubeternet                    | 5        | 2.35%   |
| Z-Star Microelectronics       | 4        | 1.88%   |
| Jieli Technology              | 4        | 1.88%   |
| Razer USA                     | 3        | 1.41%   |
| IMC Networks                  | 3        | 1.41%   |
| Aveo Technology               | 3        | 1.41%   |
| Arkmicro Technologies         | 3        | 1.41%   |
| Xiongmai                      | 2        | 0.94%   |
| Sonix Technology              | 2        | 0.94%   |
| Realtek Semiconductor         | 2        | 0.94%   |
| Pixart Imaging                | 2        | 0.94%   |
| lihappe8                      | 2        | 0.94%   |
| Guillemot                     | 2        | 0.94%   |
| Genesys Logic                 | 2        | 0.94%   |
| Creative Technology           | 2        | 0.94%   |
| AVerMedia Technologies        | 2        | 0.94%   |
| Alcor Micro                   | 2        | 0.94%   |
| 2M UVC CAMERA                 | 2        | 0.94%   |
| Unknown                       | 1        | 0.47%   |
| Trust                         | 1        | 0.47%   |
| Tobii Technology AB           | 1        | 0.47%   |
| Teslong Camera                | 1        | 0.47%   |
| Suyin                         | 1        | 0.47%   |
| Sunplus Technology            | 1        | 0.47%   |
| Ruision                       | 1        | 0.47%   |
| Novatel Wireless              | 1        | 0.47%   |
| Novatek Microelectronics      | 1        | 0.47%   |
| LG Electronics                | 1        | 0.47%   |
| Lenovo                        | 1        | 0.47%   |
| INOGENI                       | 1        | 0.47%   |
| Huawei Technologies           | 1        | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 17       | 7.91%   |
| Logitech HD Pro Webcam C920              | 12       | 5.58%   |
| Apple iPhone 5/5C/5S/6/SE                | 12       | 5.58%   |
| Samsung Galaxy A5 (MTP)                  | 10       | 4.65%   |
| Microsoft LifeCam HD-3000                | 7        | 3.26%   |
| Microdia USB 2.0 Camera                  | 6        | 2.79%   |
| ARC International Camera                 | 6        | 2.79%   |
| Chicony HP High Definition 1MP Webcam    | 5        | 2.33%   |
| Logitech HD Webcam C615                  | 4        | 1.86%   |
| Jieli USB PHY 2.0                        | 4        | 1.86%   |
| Generalplus GENERAL WEBCAM               | 4        | 1.86%   |
| Sunplus HD 720P webcam                   | 3        | 1.4%    |
| Sunplus FHD Camera Microphone            | 3        | 1.4%    |
| Razer USA Gaming Webcam [Kiyo]           | 3        | 1.4%    |
| Microdia Webcam Vitade AF                | 3        | 1.4%    |
| Microdia Laptop_Integrated_Webcam_FHD    | 3        | 1.4%    |
| Logitech C922 Pro Stream Webcam          | 3        | 1.4%    |
| Logitech C920 PRO HD Webcam              | 3        | 1.4%    |
| Generalplus 808 Camera #9 (web-cam mode) | 3        | 1.4%    |
| Cubeternet GL-UPC822 UVC WebCam          | 3        | 1.4%    |
| Z-Star Integrated Camera                 | 2        | 0.93%   |
| Xiongmai web camera                      | 2        | 0.93%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 2        | 0.93%   |
| Microsoft LifeCam VX-500 [1357]          | 2        | 0.93%   |
| Microsoft LifeCam VX-2000                | 2        | 0.93%   |
| Microsoft LifeCam HD-5000                | 2        | 0.93%   |
| Microdia USB Live camera                 | 2        | 0.93%   |
| Microdia Camera                          | 2        | 0.93%   |
| Logitech Webcam C310                     | 2        | 0.93%   |
| Logitech Webcam C250                     | 2        | 0.93%   |
| Logitech QuickCam Pro 9000               | 2        | 0.93%   |
| Logitech HD Webcam C910                  | 2        | 0.93%   |
| Logitech HD Webcam C525                  | 2        | 0.93%   |
| lihappe8 USB 2.0 Camera                  | 2        | 0.93%   |
| AVerMedia Live Streamer CAM 313          | 2        | 0.93%   |
| Aveo USB2.0 Camera                       | 2        | 0.93%   |
| Arkmicro USB2.0 PC CAMERA                | 2        | 0.93%   |
| Apple iPhone 4S                          | 2        | 0.93%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam     | 2        | 0.93%   |
| Z-Star Venus USB2.0 Camera               | 1        | 0.47%   |

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


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 2        | 20%     |
| Alcor Micro               | 2        | 20%     |
| Advanced Card Systems     | 2        | 20%     |
| SCM Microsystems          | 1        | 10%     |
| Reiner SCT Kartensysteme  | 1        | 10%     |
| Kobil Systems             | 1        | 10%     |
| Fujitsu Siemens Computers | 1        | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 20%     |
| Alcor Micro AU9540 Smartcard Reader                    | 2        | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 10%     |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad        | 1        | 10%     |
| Kobil Systems KOBIL Class 3 Reader                     | 1        | 10%     |
| Fujitsu Siemens Computers SmartCard Reader 2A          | 1        | 10%     |
| Advanced Card Systems ACR39U                           | 1        | 10%     |
| Advanced Card Systems ACR1281 1S Dual Reader           | 1        | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1233     | 79.75%  |
| 1     | 276      | 17.85%  |
| 2     | 32       | 2.07%   |
| 3     | 4        | 0.26%   |
| 4     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 142      | 41.28%  |
| Net/wireless             | 118      | 34.3%   |
| Communication controller | 26       | 7.56%   |
| Multimedia controller    | 17       | 4.94%   |
| Unassigned class         | 12       | 3.49%   |
| Chipcard                 | 8        | 2.33%   |
| Modem                    | 7        | 2.03%   |
| Sound                    | 3        | 0.87%   |
| Storage/raid             | 2        | 0.58%   |
| Camera                   | 2        | 0.58%   |
| Storage/nvme             | 1        | 0.29%   |
| Storage/ide              | 1        | 0.29%   |
| Storage                  | 1        | 0.29%   |
| Net/ethernet             | 1        | 0.29%   |
| Fingerprint reader       | 1        | 0.29%   |
| Dvb card                 | 1        | 0.29%   |
| Card reader              | 1        | 0.29%   |

